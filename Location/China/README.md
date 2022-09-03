Linux in China - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in China.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/China/Desktop/README.md) and [notebooks](/Location/China/Notebook/README.md).

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

Total: 1350

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [5a51c31ac9](https://linux-hardware.org/?probe=5a51c31ac9) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [ef43339df1](https://linux-hardware.org/?probe=ef43339df1) | Aug 28, 2022 |
| BBEN          | G16                         | Notebook    | [6b0b170e1c](https://linux-hardware.org/?probe=6b0b170e1c) | Aug 28, 2022 |
| BBEN          | G16                         | Notebook    | [66fc9bd46b](https://linux-hardware.org/?probe=66fc9bd46b) | Aug 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2KU0... | Notebook    | [6500c142f5](https://linux-hardware.org/?probe=6500c142f5) | Aug 27, 2022 |
| Dell          | Precision 7720              | Notebook    | [7fafc0e50b](https://linux-hardware.org/?probe=7fafc0e50b) | Aug 26, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [3c6266b13d](https://linux-hardware.org/?probe=3c6266b13d) | Aug 23, 2022 |
| retsamarre... | Unknown                     | Desktop     | [5bc4dd4776](https://linux-hardware.org/?probe=5bc4dd4776) | Aug 23, 2022 |
| retsamarre... | Unknown                     | Desktop     | [8f8e0f49df](https://linux-hardware.org/?probe=8f8e0f49df) | Aug 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [c0372aaa91](https://linux-hardware.org/?probe=c0372aaa91) | Aug 22, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [be6beefb03](https://linux-hardware.org/?probe=be6beefb03) | Aug 22, 2022 |
| Lenovo        | 36FB SDK0L77769 WIN 3423... | All in one  | [c65b675fc8](https://linux-hardware.org/?probe=c65b675fc8) | Aug 22, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [8898d24c48](https://linux-hardware.org/?probe=8898d24c48) | Aug 22, 2022 |
| BBEN          | G16                         | Notebook    | [f9768aedb9](https://linux-hardware.org/?probe=f9768aedb9) | Aug 21, 2022 |
| BBEN          | G16                         | Notebook    | [d491f08ce0](https://linux-hardware.org/?probe=d491f08ce0) | Aug 21, 2022 |
| Biostar       | B550M-SILVER                | Desktop     | [d3a371bce6](https://linux-hardware.org/?probe=d3a371bce6) | Aug 20, 2022 |
| Lenovo        | 3102 SDK0L77767 WIN 3423... | Desktop     | [5d884c320f](https://linux-hardware.org/?probe=5d884c320f) | Aug 16, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [058273fa11](https://linux-hardware.org/?probe=058273fa11) | Aug 14, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ee6f495403](https://linux-hardware.org/?probe=ee6f495403) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [289850f128](https://linux-hardware.org/?probe=289850f128) | Aug 13, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [baf348cae9](https://linux-hardware.org/?probe=baf348cae9) | Aug 12, 2022 |
| HP            | 8183                        | Desktop     | [19f5199de8](https://linux-hardware.org/?probe=19f5199de8) | Aug 12, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [b1498c810e](https://linux-hardware.org/?probe=b1498c810e) | Aug 12, 2022 |
| HP            | 8183                        | Desktop     | [c441ead9f8](https://linux-hardware.org/?probe=c441ead9f8) | Aug 11, 2022 |
| Timi          | TM1709                      | Notebook    | [26b592f734](https://linux-hardware.org/?probe=26b592f734) | Aug 11, 2022 |
| Unknown       | Unknown                     | Other       | [23e67d3f72](https://linux-hardware.org/?probe=23e67d3f72) | Aug 10, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [9ac3c0b157](https://linux-hardware.org/?probe=9ac3c0b157) | Aug 09, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [1d8eaa7564](https://linux-hardware.org/?probe=1d8eaa7564) | Aug 08, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [949598482f](https://linux-hardware.org/?probe=949598482f) | Aug 07, 2022 |
| ASRock        | H81M-HDS                    | Desktop     | [1d636956f2](https://linux-hardware.org/?probe=1d636956f2) | Aug 07, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [054c0beb4f](https://linux-hardware.org/?probe=054c0beb4f) | Aug 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [7d2ea1146a](https://linux-hardware.org/?probe=7d2ea1146a) | Aug 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [dbafe167dc](https://linux-hardware.org/?probe=dbafe167dc) | Aug 06, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [c1d23f2838](https://linux-hardware.org/?probe=c1d23f2838) | Aug 06, 2022 |
| Unknown       | Unknown                     | Other       | [8330cc179c](https://linux-hardware.org/?probe=8330cc179c) | Aug 04, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [7a3c7a2886](https://linux-hardware.org/?probe=7a3c7a2886) | Aug 04, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [28eaeed6dd](https://linux-hardware.org/?probe=28eaeed6dd) | Aug 04, 2022 |
| Lenovo        | ThinkPad E470c 20H3A000C... | Notebook    | [047888752c](https://linux-hardware.org/?probe=047888752c) | Aug 04, 2022 |
| Lenovo        | 102F NO DPK                 | Desktop     | [1a040c2717](https://linux-hardware.org/?probe=1a040c2717) | Aug 04, 2022 |
| Intel         | X99                         | Desktop     | [33e0d23783](https://linux-hardware.org/?probe=33e0d23783) | Aug 04, 2022 |
| Unknown       | Xiaobao Nas I               | Soc         | [052379f89e](https://linux-hardware.org/?probe=052379f89e) | Aug 04, 2022 |
| Google        | Dratini                     | Notebook    | [e61c92a95b](https://linux-hardware.org/?probe=e61c92a95b) | Aug 04, 2022 |
| Unknown       | Xiaobao Nas I               | Soc         | [68434806c3](https://linux-hardware.org/?probe=68434806c3) | Aug 03, 2022 |
| Notebook      | NH5xAx                      | Notebook    | [7716e60398](https://linux-hardware.org/?probe=7716e60398) | Aug 03, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [d01d805978](https://linux-hardware.org/?probe=d01d805978) | Aug 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [563bd9cecd](https://linux-hardware.org/?probe=563bd9cecd) | Aug 02, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [dd8b9dc221](https://linux-hardware.org/?probe=dd8b9dc221) | Aug 02, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [20ff37511f](https://linux-hardware.org/?probe=20ff37511f) | Jul 30, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [08a5cff3a6](https://linux-hardware.org/?probe=08a5cff3a6) | Jul 29, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | Desktop     | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| ASUSTek       | F2A55-M LK2 PLUS            | Desktop     | [a0a4abeb19](https://linux-hardware.org/?probe=a0a4abeb19) | Jul 28, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [88a326be83](https://linux-hardware.org/?probe=88a326be83) | Jul 28, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [2ed7d049e7](https://linux-hardware.org/?probe=2ed7d049e7) | Jul 27, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [a8dc9cfc07](https://linux-hardware.org/?probe=a8dc9cfc07) | Jul 27, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [5ff32931fa](https://linux-hardware.org/?probe=5ff32931fa) | Jul 27, 2022 |
| Phytium       | D2000                       | Server      | [7e0be651b1](https://linux-hardware.org/?probe=7e0be651b1) | Jul 27, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [52764ae22f](https://linux-hardware.org/?probe=52764ae22f) | Jul 26, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [ce9121a53b](https://linux-hardware.org/?probe=ce9121a53b) | Jul 25, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [baf09f6525](https://linux-hardware.org/?probe=baf09f6525) | Jul 24, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [5e4ca4abd6](https://linux-hardware.org/?probe=5e4ca4abd6) | Jul 23, 2022 |
| Gigabyte      | Z690I A ULTRA PLUS D4       | Desktop     | [453b2cce27](https://linux-hardware.org/?probe=453b2cce27) | Jul 22, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [3428364c49](https://linux-hardware.org/?probe=3428364c49) | Jul 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d5ca3d7f7e](https://linux-hardware.org/?probe=d5ca3d7f7e) | Jul 22, 2022 |
| X79-1356      | Unknown                     | Desktop     | [2db70d0471](https://linux-hardware.org/?probe=2db70d0471) | Jul 22, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [7a5b89e10c](https://linux-hardware.org/?probe=7a5b89e10c) | Jul 22, 2022 |
| Supermicro    | X11DPi-N                    | Server      | [38ae00936b](https://linux-hardware.org/?probe=38ae00936b) | Jul 22, 2022 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [1a0ea0050f](https://linux-hardware.org/?probe=1a0ea0050f) | Jul 22, 2022 |
| Lenovo        | NOK                         | Desktop     | [a47a727578](https://linux-hardware.org/?probe=a47a727578) | Jul 22, 2022 |
| METAPHYUNI    | MetamechBook                | Notebook    | [169a9a0636](https://linux-hardware.org/?probe=169a9a0636) | Jul 21, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [d101f95ac2](https://linux-hardware.org/?probe=d101f95ac2) | Jul 20, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | Notebook    | [cafc6119f3](https://linux-hardware.org/?probe=cafc6119f3) | Jul 18, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [f2bfdb1f13](https://linux-hardware.org/?probe=f2bfdb1f13) | Jul 17, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [321c1a6e7a](https://linux-hardware.org/?probe=321c1a6e7a) | Jul 17, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6ff44b9490](https://linux-hardware.org/?probe=6ff44b9490) | Jul 15, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [92c267f273](https://linux-hardware.org/?probe=92c267f273) | Jul 15, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [845432a1d3](https://linux-hardware.org/?probe=845432a1d3) | Jul 15, 2022 |
| Lenovo        | V470 HuronRiver Platform    | Notebook    | [021fb24a0a](https://linux-hardware.org/?probe=021fb24a0a) | Jul 14, 2022 |
| Lenovo        | V470 HuronRiver Platform    | Notebook    | [f3b112e72a](https://linux-hardware.org/?probe=f3b112e72a) | Jul 14, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [4d636c74d3](https://linux-hardware.org/?probe=4d636c74d3) | Jul 14, 2022 |
| HP            | 829E                        | Mini pc     | [27c2c68afb](https://linux-hardware.org/?probe=27c2c68afb) | Jul 13, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [3ae3afeece](https://linux-hardware.org/?probe=3ae3afeece) | Jul 13, 2022 |
| MSI           | Z370-OC PRO                 | Desktop     | [2c9d1d78df](https://linux-hardware.org/?probe=2c9d1d78df) | Jul 12, 2022 |
| Colorful T... | H310M-T PRO V21             | Desktop     | [b922e2142b](https://linux-hardware.org/?probe=b922e2142b) | Jul 11, 2022 |
| Fujitsu       | FMVNP7HER                   | Notebook    | [e87161bce7](https://linux-hardware.org/?probe=e87161bce7) | Jul 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [179ad71f6a](https://linux-hardware.org/?probe=179ad71f6a) | Jul 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [7cfc308ed6](https://linux-hardware.org/?probe=7cfc308ed6) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [f67a64f833](https://linux-hardware.org/?probe=f67a64f833) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [5bdfb575ae](https://linux-hardware.org/?probe=5bdfb575ae) | Jul 07, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [62fb099dfd](https://linux-hardware.org/?probe=62fb099dfd) | Jul 07, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [15b290d046](https://linux-hardware.org/?probe=15b290d046) | Jul 07, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [dc3ab840d6](https://linux-hardware.org/?probe=dc3ab840d6) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [7b1c72c3e7](https://linux-hardware.org/?probe=7b1c72c3e7) | Jul 06, 2022 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [ad60f0abf2](https://linux-hardware.org/?probe=ad60f0abf2) | Jul 04, 2022 |
| Dell          | Vostro 3549                 | Notebook    | [d23ff685fc](https://linux-hardware.org/?probe=d23ff685fc) | Jul 03, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [c1e5d91a40](https://linux-hardware.org/?probe=c1e5d91a40) | Jul 02, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [253c441703](https://linux-hardware.org/?probe=253c441703) | Jul 02, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [2ae62ac227](https://linux-hardware.org/?probe=2ae62ac227) | Jun 30, 2022 |
| MSI           | Z68A-GD80                   | Desktop     | [2e2ca703b0](https://linux-hardware.org/?probe=2e2ca703b0) | Jun 30, 2022 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | Notebook    | [4b2106c800](https://linux-hardware.org/?probe=4b2106c800) | Jun 29, 2022 |
| Gigabyte      | EP45-UD3                    | Desktop     | [bb62363ad2](https://linux-hardware.org/?probe=bb62363ad2) | Jun 29, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [1a50f7c080](https://linux-hardware.org/?probe=1a50f7c080) | Jun 27, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [607f489961](https://linux-hardware.org/?probe=607f489961) | Jun 25, 2022 |
| Dell          | Precision 3541              | Notebook    | [816c91b81b](https://linux-hardware.org/?probe=816c91b81b) | Jun 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [b3def4c8ad](https://linux-hardware.org/?probe=b3def4c8ad) | Jun 25, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [eaf51fc79f](https://linux-hardware.org/?probe=eaf51fc79f) | Jun 24, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [209001317a](https://linux-hardware.org/?probe=209001317a) | Jun 23, 2022 |
| IPASON        | SMN86A                      | Notebook    | [834382148b](https://linux-hardware.org/?probe=834382148b) | Jun 21, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [8b520f803c](https://linux-hardware.org/?probe=8b520f803c) | Jun 21, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [385b65c320](https://linux-hardware.org/?probe=385b65c320) | Jun 19, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [fb120ddb6d](https://linux-hardware.org/?probe=fb120ddb6d) | Jun 19, 2022 |
| HUAWEI        | KPR-WX9                     | Notebook    | [4c08060155](https://linux-hardware.org/?probe=4c08060155) | Jun 18, 2022 |
| ASUSTek       | S550CM                      | Notebook    | [43ddcf21fb](https://linux-hardware.org/?probe=43ddcf21fb) | Jun 17, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [8d56f09226](https://linux-hardware.org/?probe=8d56f09226) | Jun 17, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| Clevo         | P7xxTM(1)                   | Notebook    | [48afb16c13](https://linux-hardware.org/?probe=48afb16c13) | Jun 16, 2022 |
| Timi          | TM1701                      | Notebook    | [e57d1ac956](https://linux-hardware.org/?probe=e57d1ac956) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [d77ce7a3f7](https://linux-hardware.org/?probe=d77ce7a3f7) | Jun 13, 2022 |
| Timi          | A7S                         | Notebook    | [a43809f0a8](https://linux-hardware.org/?probe=a43809f0a8) | Jun 12, 2022 |
| Lenovo        | MIIX710-12IKB 80W1          | Tablet      | [50d3528425](https://linux-hardware.org/?probe=50d3528425) | Jun 12, 2022 |
| Lenovo        | MIIX710-12IKB 80W1          | Tablet      | [6e29236ae6](https://linux-hardware.org/?probe=6e29236ae6) | Jun 11, 2022 |
| Acer          | Aspire T5000                | Notebook    | [38e164657d](https://linux-hardware.org/?probe=38e164657d) | Jun 11, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [6e70632a8c](https://linux-hardware.org/?probe=6e70632a8c) | Jun 10, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [197f417cea](https://linux-hardware.org/?probe=197f417cea) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [f237211ddb](https://linux-hardware.org/?probe=f237211ddb) | Jun 09, 2022 |
| Unknown       | Unknown                     | Other       | [d1d5741aff](https://linux-hardware.org/?probe=d1d5741aff) | Jun 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [96dfe73713](https://linux-hardware.org/?probe=96dfe73713) | Jun 07, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [6d46a6107c](https://linux-hardware.org/?probe=6d46a6107c) | Jun 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [2a25ea86fc](https://linux-hardware.org/?probe=2a25ea86fc) | Jun 05, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [ecef8fb98e](https://linux-hardware.org/?probe=ecef8fb98e) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [5f55de3d8e](https://linux-hardware.org/?probe=5f55de3d8e) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [db08be8e6c](https://linux-hardware.org/?probe=db08be8e6c) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [818930c012](https://linux-hardware.org/?probe=818930c012) | Jun 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4c36218f66](https://linux-hardware.org/?probe=4c36218f66) | Jun 04, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [a9c714d138](https://linux-hardware.org/?probe=a9c714d138) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [bcb55ce8ce](https://linux-hardware.org/?probe=bcb55ce8ce) | Jun 01, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [ee8d9751b0](https://linux-hardware.org/?probe=ee8d9751b0) | Jun 01, 2022 |
| Acer          | Aspire T5000                | Notebook    | [55aaebdab5](https://linux-hardware.org/?probe=55aaebdab5) | May 31, 2022 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [d4698d909e](https://linux-hardware.org/?probe=d4698d909e) | May 31, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2855e4c95](https://linux-hardware.org/?probe=e2855e4c95) | May 31, 2022 |
| Acer          | Aspire T5000                | Notebook    | [7bdeb5fb3b](https://linux-hardware.org/?probe=7bdeb5fb3b) | May 31, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [3d58c27cd7](https://linux-hardware.org/?probe=3d58c27cd7) | May 31, 2022 |
| Lenovo        | Yoga Duet IML 2020 82E9     | Tablet      | [63eab4a6b5](https://linux-hardware.org/?probe=63eab4a6b5) | May 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [24a7b3121f](https://linux-hardware.org/?probe=24a7b3121f) | May 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [5e77f9d2f9](https://linux-hardware.org/?probe=5e77f9d2f9) | May 29, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [3ddc17645b](https://linux-hardware.org/?probe=3ddc17645b) | May 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [1da299e36e](https://linux-hardware.org/?probe=1da299e36e) | May 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [91306ce19f](https://linux-hardware.org/?probe=91306ce19f) | May 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [114a036605](https://linux-hardware.org/?probe=114a036605) | May 28, 2022 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [fc581d0fb4](https://linux-hardware.org/?probe=fc581d0fb4) | May 26, 2022 |
| Intel         | NUC11ATBC4 M53051-202       | Mini pc     | [fe6eb17434](https://linux-hardware.org/?probe=fe6eb17434) | May 25, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c0fe1740e0](https://linux-hardware.org/?probe=c0fe1740e0) | May 25, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [59eda31291](https://linux-hardware.org/?probe=59eda31291) | May 24, 2022 |
| Dell          | Latitude 5300               | Notebook    | [b2e8f91f15](https://linux-hardware.org/?probe=b2e8f91f15) | May 24, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [f2c3a907b7](https://linux-hardware.org/?probe=f2c3a907b7) | May 24, 2022 |
| MSI           | H97M-P35                    | Desktop     | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [1ebb900517](https://linux-hardware.org/?probe=1ebb900517) | May 22, 2022 |
| Dell          | Latitude 3490               | Notebook    | [36a2ce11ef](https://linux-hardware.org/?probe=36a2ce11ef) | May 22, 2022 |
| Google        | Atlas                       | Notebook    | [d9406ed20d](https://linux-hardware.org/?probe=d9406ed20d) | May 21, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [fce678a9e8](https://linux-hardware.org/?probe=fce678a9e8) | May 21, 2022 |
| Lenovo        | NOK                         | Desktop     | [567c167a97](https://linux-hardware.org/?probe=567c167a97) | May 20, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [a60048a58a](https://linux-hardware.org/?probe=a60048a58a) | May 19, 2022 |
| Lenovo        | IdeaPad U430p 20269         | Notebook    | [bcf848458f](https://linux-hardware.org/?probe=bcf848458f) | May 18, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [e5c6c46d14](https://linux-hardware.org/?probe=e5c6c46d14) | May 18, 2022 |
| MECHREVO      | X10Ti-S Series GM7MPHS      | Notebook    | [3af043f369](https://linux-hardware.org/?probe=3af043f369) | May 17, 2022 |
| MAXSUN        | MS-M3A78EL                  | Desktop     | [98d8c5a6ee](https://linux-hardware.org/?probe=98d8c5a6ee) | May 14, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [2b7a0725f0](https://linux-hardware.org/?probe=2b7a0725f0) | May 14, 2022 |
| Lenovo        | ThinkPad S2 5th Gen 20R7... | Notebook    | [a4ba7cbcfa](https://linux-hardware.org/?probe=a4ba7cbcfa) | May 13, 2022 |
| Google        | Atlas                       | Notebook    | [ae85df2f65](https://linux-hardware.org/?probe=ae85df2f65) | May 12, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [a83103153b](https://linux-hardware.org/?probe=a83103153b) | May 12, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [b0db2e2b60](https://linux-hardware.org/?probe=b0db2e2b60) | May 11, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [f62715aee5](https://linux-hardware.org/?probe=f62715aee5) | May 11, 2022 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [3c126b8a1d](https://linux-hardware.org/?probe=3c126b8a1d) | May 10, 2022 |
| Clevo         | P7xxTM(1)                   | Notebook    | [fdebb20557](https://linux-hardware.org/?probe=fdebb20557) | May 10, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [24340ea9a8](https://linux-hardware.org/?probe=24340ea9a8) | May 06, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [428f653301](https://linux-hardware.org/?probe=428f653301) | May 05, 2022 |
| Timi          | Redmi G                     | Notebook    | [a2738a4d6e](https://linux-hardware.org/?probe=a2738a4d6e) | May 05, 2022 |
| Dell          | Latitude 7420               | Notebook    | [7fd2239abb](https://linux-hardware.org/?probe=7fd2239abb) | May 05, 2022 |
| Google        | Atlas                       | Notebook    | [dce87f3691](https://linux-hardware.org/?probe=dce87f3691) | May 05, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [dc8d8b070e](https://linux-hardware.org/?probe=dc8d8b070e) | May 05, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [6103e540b9](https://linux-hardware.org/?probe=6103e540b9) | May 04, 2022 |
| Dell          | Latitude 5300               | Notebook    | [fa0246b764](https://linux-hardware.org/?probe=fa0246b764) | May 04, 2022 |
| Dell          | Precision 3541              | Notebook    | [feaee0b7ff](https://linux-hardware.org/?probe=feaee0b7ff) | May 04, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [b812cd9eb1](https://linux-hardware.org/?probe=b812cd9eb1) | May 04, 2022 |
| Lenovo        | IdeaPad Y470 20090          | Notebook    | [690c12e995](https://linux-hardware.org/?probe=690c12e995) | May 03, 2022 |
| HP            | G42                         | Notebook    | [6ee2b19fc7](https://linux-hardware.org/?probe=6ee2b19fc7) | May 01, 2022 |
| HP            | G42                         | Notebook    | [731ba8d968](https://linux-hardware.org/?probe=731ba8d968) | May 01, 2022 |
| HP            | G42                         | Notebook    | [e23740df6e](https://linux-hardware.org/?probe=e23740df6e) | Apr 30, 2022 |
| HP            | G42                         | Notebook    | [f6ca4559f5](https://linux-hardware.org/?probe=f6ca4559f5) | Apr 30, 2022 |
| Dell          | Inspiron 7400               | Notebook    | [0c0af6919d](https://linux-hardware.org/?probe=0c0af6919d) | Apr 29, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ff9b46fd29](https://linux-hardware.org/?probe=ff9b46fd29) | Apr 29, 2022 |
| OEM           | V1.0                        | Desktop     | [167ee50568](https://linux-hardware.org/?probe=167ee50568) | Apr 29, 2022 |
| Dell          | Inspiron 7400               | Notebook    | [8e5289a5e7](https://linux-hardware.org/?probe=8e5289a5e7) | Apr 28, 2022 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [4f15ab06cc](https://linux-hardware.org/?probe=4f15ab06cc) | Apr 28, 2022 |
| Lenovo        | AILZx                       | Notebook    | [efa15d667f](https://linux-hardware.org/?probe=efa15d667f) | Apr 26, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [07ccc93cd4](https://linux-hardware.org/?probe=07ccc93cd4) | Apr 25, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f0671e360b](https://linux-hardware.org/?probe=f0671e360b) | Apr 25, 2022 |
| ASRock        | Z170 Gaming K4              | Desktop     | [96b772b4e6](https://linux-hardware.org/?probe=96b772b4e6) | Apr 24, 2022 |
| Timi          | TM1612                      | Notebook    | [9e6b6f4737](https://linux-hardware.org/?probe=9e6b6f4737) | Apr 24, 2022 |
| GreatWall     | TN140A2                     | Notebook    | [69043361cf](https://linux-hardware.org/?probe=69043361cf) | Apr 24, 2022 |
| Dell          | Latitude 5290               | Notebook    | [e373cb6fa1](https://linux-hardware.org/?probe=e373cb6fa1) | Apr 23, 2022 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [c56c469d4f](https://linux-hardware.org/?probe=c56c469d4f) | Apr 21, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [d7e77fd856](https://linux-hardware.org/?probe=d7e77fd856) | Apr 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5f78518f42](https://linux-hardware.org/?probe=5f78518f42) | Apr 21, 2022 |
| ASRock        | Z170 Gaming K4              | Desktop     | [81e06a1dcb](https://linux-hardware.org/?probe=81e06a1dcb) | Apr 18, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [c4561b1073](https://linux-hardware.org/?probe=c4561b1073) | Apr 18, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [3faf048414](https://linux-hardware.org/?probe=3faf048414) | Apr 18, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| J&W           | J1900T                      | Desktop     | [7c87f17ed7](https://linux-hardware.org/?probe=7c87f17ed7) | Apr 17, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [3c5f232016](https://linux-hardware.org/?probe=3c5f232016) | Apr 17, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [aa88339957](https://linux-hardware.org/?probe=aa88339957) | Apr 16, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [e29970db9c](https://linux-hardware.org/?probe=e29970db9c) | Apr 16, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [7e346154a5](https://linux-hardware.org/?probe=7e346154a5) | Apr 16, 2022 |
| Timi          | A34                         | Notebook    | [ff24fc7e19](https://linux-hardware.org/?probe=ff24fc7e19) | Apr 15, 2022 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [2394088db1](https://linux-hardware.org/?probe=2394088db1) | Apr 14, 2022 |
| Unknown       | Xiaobao Nas I               | Soc         | [0acc620cac](https://linux-hardware.org/?probe=0acc620cac) | Apr 13, 2022 |
| Lenovo        | MAHOBAY 31900005 STD        | Desktop     | [d82d73ba0a](https://linux-hardware.org/?probe=d82d73ba0a) | Apr 12, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [a8e2ef2c76](https://linux-hardware.org/?probe=a8e2ef2c76) | Apr 12, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [090560f0c5](https://linux-hardware.org/?probe=090560f0c5) | Apr 12, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [f676b9a255](https://linux-hardware.org/?probe=f676b9a255) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a86b688768](https://linux-hardware.org/?probe=a86b688768) | Apr 11, 2022 |
| Lenovo        | XiaoXin Air 13IML 81WV      | Notebook    | [c5ae7c810d](https://linux-hardware.org/?probe=c5ae7c810d) | Apr 09, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [e8e6eefea7](https://linux-hardware.org/?probe=e8e6eefea7) | Apr 09, 2022 |
| HP            | OMEN by Laptop 17-ck1xxx    | Notebook    | [10654de5c8](https://linux-hardware.org/?probe=10654de5c8) | Apr 08, 2022 |
| HP            | Tablet 11-be0xxx            | Tablet      | [e3bcbaf593](https://linux-hardware.org/?probe=e3bcbaf593) | Apr 08, 2022 |
| HP            | OMEN by Laptop 17-ck1xxx    | Notebook    | [60cd34cb85](https://linux-hardware.org/?probe=60cd34cb85) | Apr 07, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [686ef53bc5](https://linux-hardware.org/?probe=686ef53bc5) | Apr 07, 2022 |
| Lenovo        | ThinkPad S2 5th Gen 20R7... | Notebook    | [4e1cbba139](https://linux-hardware.org/?probe=4e1cbba139) | Apr 07, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [aad4b24a04](https://linux-hardware.org/?probe=aad4b24a04) | Apr 06, 2022 |
| Timi          | TM1701                      | Notebook    | [e2930f3884](https://linux-hardware.org/?probe=e2930f3884) | Apr 06, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| Lenovo        | ThinkPad L470 20J5A240CD    | Notebook    | [2c7d1c1f02](https://linux-hardware.org/?probe=2c7d1c1f02) | Apr 04, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [9c1fd6c304](https://linux-hardware.org/?probe=9c1fd6c304) | Apr 04, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [f1f8a33de1](https://linux-hardware.org/?probe=f1f8a33de1) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [aac8a6f7e4](https://linux-hardware.org/?probe=aac8a6f7e4) | Apr 03, 2022 |
| Lenovo        | 32E9 SDK0T76479 WIN 3423... | Desktop     | [d8dbd14b3e](https://linux-hardware.org/?probe=d8dbd14b3e) | Apr 02, 2022 |
| Gigabyte      | P65                         | Notebook    | [28a10c32cf](https://linux-hardware.org/?probe=28a10c32cf) | Apr 02, 2022 |
| Lenovo        | QiTianM7150                 | Desktop     | [a6a37565b7](https://linux-hardware.org/?probe=a6a37565b7) | Apr 02, 2022 |
| MECHREVO      | X10 Pro Series GM7TG8S      | Notebook    | [eceb9b69ed](https://linux-hardware.org/?probe=eceb9b69ed) | Apr 01, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [802940c8ef](https://linux-hardware.org/?probe=802940c8ef) | Mar 30, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [51f7153768](https://linux-hardware.org/?probe=51f7153768) | Mar 30, 2022 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [8fdae867c0](https://linux-hardware.org/?probe=8fdae867c0) | Mar 30, 2022 |
| Unknown       | X133                        | Notebook    | [996dfaa50f](https://linux-hardware.org/?probe=996dfaa50f) | Mar 28, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [b9bbb89cca](https://linux-hardware.org/?probe=b9bbb89cca) | Mar 28, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [6385010257](https://linux-hardware.org/?probe=6385010257) | Mar 28, 2022 |
| Lenovo        | ThinkPad R400 2784A48       | Notebook    | [f760bbcc2f](https://linux-hardware.org/?probe=f760bbcc2f) | Mar 27, 2022 |
| Lenovo        | ThinkPad R400 2784A48       | Notebook    | [b7093f8912](https://linux-hardware.org/?probe=b7093f8912) | Mar 27, 2022 |
| Acer          | Swift SF314-510G            | Notebook    | [a105ea5158](https://linux-hardware.org/?probe=a105ea5158) | Mar 27, 2022 |
| Inspur        | NF5270M3                    | Desktop     | [053fcd58fc](https://linux-hardware.org/?probe=053fcd58fc) | Mar 26, 2022 |
| ASUSTek       | B360M-D3H                   | Desktop     | [bf6e46cd01](https://linux-hardware.org/?probe=bf6e46cd01) | Mar 26, 2022 |
| Lenovo        | ThinkPad A485 20MU0007CD    | Notebook    | [1e231d6b08](https://linux-hardware.org/?probe=1e231d6b08) | Mar 26, 2022 |
| Timi          | A7S                         | Notebook    | [c39211692e](https://linux-hardware.org/?probe=c39211692e) | Mar 25, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [847b9e1fbb](https://linux-hardware.org/?probe=847b9e1fbb) | Mar 23, 2022 |
| Dell          | 0D61XP A02                  | Server      | [87f57e757f](https://linux-hardware.org/?probe=87f57e757f) | Mar 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4A... | Notebook    | [a257719dcf](https://linux-hardware.org/?probe=a257719dcf) | Mar 23, 2022 |
| Dell          | 0NT78X A08                  | Server      | [99cdcd7a9d](https://linux-hardware.org/?probe=99cdcd7a9d) | Mar 23, 2022 |
| HUAWEI        | FRD-WX9                     | Notebook    | [e027a60ac6](https://linux-hardware.org/?probe=e027a60ac6) | Mar 23, 2022 |
| IBM           | Unknown                     | Notebook    | [2bcbb8a946](https://linux-hardware.org/?probe=2bcbb8a946) | Mar 21, 2022 |
| Lenovo        | ThinkPad P53 20QQA004CD     | Notebook    | [c99fae499f](https://linux-hardware.org/?probe=c99fae499f) | Mar 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [ee813d0051](https://linux-hardware.org/?probe=ee813d0051) | Mar 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [6adea9d280](https://linux-hardware.org/?probe=6adea9d280) | Mar 19, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [c06992ac2b](https://linux-hardware.org/?probe=c06992ac2b) | Mar 18, 2022 |
| Notebook      | NH5xAx                      | Notebook    | [cddad9e5c8](https://linux-hardware.org/?probe=cddad9e5c8) | Mar 17, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [7e92a522e9](https://linux-hardware.org/?probe=7e92a522e9) | Mar 16, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [4c4039754c](https://linux-hardware.org/?probe=4c4039754c) | Mar 13, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [70a5dc4f94](https://linux-hardware.org/?probe=70a5dc4f94) | Mar 12, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [8fdeae3b33](https://linux-hardware.org/?probe=8fdeae3b33) | Mar 12, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [9c61029e1f](https://linux-hardware.org/?probe=9c61029e1f) | Mar 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [1f84b1e42d](https://linux-hardware.org/?probe=1f84b1e42d) | Mar 11, 2022 |
| Lenovo        | 3187 SDK0L77769 WIN 3423... | Desktop     | [545b878c51](https://linux-hardware.org/?probe=545b878c51) | Mar 10, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [2b4cd63d88](https://linux-hardware.org/?probe=2b4cd63d88) | Mar 10, 2022 |
| Samsung       | 500R5L/501R5L/500R5P/550... | Notebook    | [8d792e6db0](https://linux-hardware.org/?probe=8d792e6db0) | Mar 09, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [3edcfcdf53](https://linux-hardware.org/?probe=3edcfcdf53) | Mar 08, 2022 |
| Timi          | RedmiBook Air 13            | Notebook    | [cb1fd6a511](https://linux-hardware.org/?probe=cb1fd6a511) | Mar 08, 2022 |
| Toshiba       | Satellite C850-C008         | Notebook    | [d18b844729](https://linux-hardware.org/?probe=d18b844729) | Mar 07, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [e1da80ec6f](https://linux-hardware.org/?probe=e1da80ec6f) | Mar 05, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [c697a91a8e](https://linux-hardware.org/?probe=c697a91a8e) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [cd7e96054b](https://linux-hardware.org/?probe=cd7e96054b) | Mar 01, 2022 |
| Dell          | Latitude 7285               | Notebook    | [8d3fe46d72](https://linux-hardware.org/?probe=8d3fe46d72) | Mar 01, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [f2fb3da876](https://linux-hardware.org/?probe=f2fb3da876) | Mar 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2511c4e555](https://linux-hardware.org/?probe=2511c4e555) | Feb 28, 2022 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Lenovo        | NOK                         | Desktop     | [05c2b02bd3](https://linux-hardware.org/?probe=05c2b02bd3) | Feb 26, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [93aca5cd19](https://linux-hardware.org/?probe=93aca5cd19) | Feb 25, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [7fe4a3390b](https://linux-hardware.org/?probe=7fe4a3390b) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | TM1709                      | Notebook    | [16e699bea8](https://linux-hardware.org/?probe=16e699bea8) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| LG Electro... | 16Z90P-G.AA56C              | Notebook    | [f4b91cfb92](https://linux-hardware.org/?probe=f4b91cfb92) | Feb 22, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [cde7566ecb](https://linux-hardware.org/?probe=cde7566ecb) | Feb 22, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [a07d445338](https://linux-hardware.org/?probe=a07d445338) | Feb 21, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [5dea4207b1](https://linux-hardware.org/?probe=5dea4207b1) | Feb 20, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [5c3eba73d5](https://linux-hardware.org/?probe=5c3eba73d5) | Feb 20, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [215889b22b](https://linux-hardware.org/?probe=215889b22b) | Feb 19, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [b91f497b74](https://linux-hardware.org/?probe=b91f497b74) | Feb 19, 2022 |
| Lenovo        | NOK                         | Desktop     | [3936474618](https://linux-hardware.org/?probe=3936474618) | Feb 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [1236b9a36b](https://linux-hardware.org/?probe=1236b9a36b) | Feb 17, 2022 |
| MSI           | A88XM-E45                   | Desktop     | [b58bd64798](https://linux-hardware.org/?probe=b58bd64798) | Feb 17, 2022 |
| Lenovo        | XiaoXinPro 14IHU 2021 82... | Notebook    | [d994752dc6](https://linux-hardware.org/?probe=d994752dc6) | Feb 15, 2022 |
| MSI           | WT72 2OM                    | Notebook    | [e266645b4a](https://linux-hardware.org/?probe=e266645b4a) | Feb 14, 2022 |
| Dell          | System Inspiron N4110       | Notebook    | [695b7bb3dd](https://linux-hardware.org/?probe=695b7bb3dd) | Feb 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2fe2235d74](https://linux-hardware.org/?probe=2fe2235d74) | Feb 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [fa14786b94](https://linux-hardware.org/?probe=fa14786b94) | Feb 13, 2022 |
| Acer          | Swift SF314-510G            | Notebook    | [6c4dbc81d8](https://linux-hardware.org/?probe=6c4dbc81d8) | Feb 12, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [62bdd11635](https://linux-hardware.org/?probe=62bdd11635) | Feb 11, 2022 |
| Dell          | G7 7500                     | Notebook    | [61f4625e4c](https://linux-hardware.org/?probe=61f4625e4c) | Feb 11, 2022 |
| ASUSTek       | PN40                        | Mini pc     | [27bb88805d](https://linux-hardware.org/?probe=27bb88805d) | Feb 10, 2022 |
| ASUSTek       | PN40                        | Mini pc     | [6f558be780](https://linux-hardware.org/?probe=6f558be780) | Feb 10, 2022 |
| Lenovo        | ThinkPad T61p 64608VU       | Notebook    | [73fddf3dcc](https://linux-hardware.org/?probe=73fddf3dcc) | Feb 10, 2022 |
| Lenovo        | ThinkPad X230 2324A14       | Notebook    | [502457cef5](https://linux-hardware.org/?probe=502457cef5) | Feb 09, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [b9019fac00](https://linux-hardware.org/?probe=b9019fac00) | Feb 09, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [beb9e79811](https://linux-hardware.org/?probe=beb9e79811) | Feb 09, 2022 |
| Lenovo        | ThinkPad X61 76733NJ        | Notebook    | [42dec79e1d](https://linux-hardware.org/?probe=42dec79e1d) | Feb 08, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [a154ac8369](https://linux-hardware.org/?probe=a154ac8369) | Feb 08, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [0e264c593f](https://linux-hardware.org/?probe=0e264c593f) | Feb 07, 2022 |
| Lenovo        | Unknown                     | Notebook    | [8f315e1abe](https://linux-hardware.org/?probe=8f315e1abe) | Feb 07, 2022 |
| HUAWEI        | KLV-WX9                     | Notebook    | [80eec7db33](https://linux-hardware.org/?probe=80eec7db33) | Feb 07, 2022 |
| Lenovo        | Unknown                     | Notebook    | [bf281646d9](https://linux-hardware.org/?probe=bf281646d9) | Feb 07, 2022 |
| Dell          | Inspiron 3476               | Notebook    | [468adecdcc](https://linux-hardware.org/?probe=468adecdcc) | Feb 05, 2022 |
| Lenovo        | ThinkPad E450 20DCA07JCD    | Notebook    | [ce693a499b](https://linux-hardware.org/?probe=ce693a499b) | Feb 05, 2022 |
| Timi          | TM1612                      | Notebook    | [fe85c2d733](https://linux-hardware.org/?probe=fe85c2d733) | Feb 05, 2022 |
| Synology      | DS216+                      | Notebook    | [f4d851d128](https://linux-hardware.org/?probe=f4d851d128) | Feb 04, 2022 |
| ECS           | BSWI-DA                     | Desktop     | [2b3dda83e5](https://linux-hardware.org/?probe=2b3dda83e5) | Feb 04, 2022 |
| Lenovo        | Yoga Duet IML 2020 82E9     | Tablet      | [927ed071b3](https://linux-hardware.org/?probe=927ed071b3) | Jan 30, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [b79cd8c2b0](https://linux-hardware.org/?probe=b79cd8c2b0) | Jan 30, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | Notebook    | [5802ec7cbc](https://linux-hardware.org/?probe=5802ec7cbc) | Jan 30, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | Notebook    | [d2d9c64d63](https://linux-hardware.org/?probe=d2d9c64d63) | Jan 30, 2022 |
| HP            | ProLiant DL580 G7           | Server      | [fe6b8cb2e4](https://linux-hardware.org/?probe=fe6b8cb2e4) | Jan 29, 2022 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [0bef76b548](https://linux-hardware.org/?probe=0bef76b548) | Jan 28, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [e578c5f173](https://linux-hardware.org/?probe=e578c5f173) | Jan 28, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [fb7e1fcf47](https://linux-hardware.org/?probe=fb7e1fcf47) | Jan 28, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [53b2c696ff](https://linux-hardware.org/?probe=53b2c696ff) | Jan 26, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [7b2482036e](https://linux-hardware.org/?probe=7b2482036e) | Jan 26, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| Unknown       | 0XWDCF A01                  | Server      | [f5f07bffc2](https://linux-hardware.org/?probe=f5f07bffc2) | Jan 24, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [a3aa535c25](https://linux-hardware.org/?probe=a3aa535c25) | Jan 24, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8d72f7a752](https://linux-hardware.org/?probe=8d72f7a752) | Jan 23, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [d22caa9915](https://linux-hardware.org/?probe=d22caa9915) | Jan 23, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [fb18e68215](https://linux-hardware.org/?probe=fb18e68215) | Jan 22, 2022 |
| Intel         | G41 V1.0                    | Desktop     | [e1f1c99851](https://linux-hardware.org/?probe=e1f1c99851) | Jan 22, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [794a06d193](https://linux-hardware.org/?probe=794a06d193) | Jan 22, 2022 |
| HP            | ProLiant DL580 G7           | Server      | [8c817d64a7](https://linux-hardware.org/?probe=8c817d64a7) | Jan 21, 2022 |
| Timi          | A7S                         | Notebook    | [9c419e0bab](https://linux-hardware.org/?probe=9c419e0bab) | Jan 20, 2022 |
| Acer          | Aspire V5-471G              | Notebook    | [7c07d2e27d](https://linux-hardware.org/?probe=7c07d2e27d) | Jan 19, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [90b4523b21](https://linux-hardware.org/?probe=90b4523b21) | Jan 19, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [152a75acd0](https://linux-hardware.org/?probe=152a75acd0) | Jan 19, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [75c70d6dee](https://linux-hardware.org/?probe=75c70d6dee) | Jan 19, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [51d6b35ddf](https://linux-hardware.org/?probe=51d6b35ddf) | Jan 17, 2022 |
| MSI           | H310M-S03                   | Desktop     | [8c009a1259](https://linux-hardware.org/?probe=8c009a1259) | Jan 17, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [31b2f44066](https://linux-hardware.org/?probe=31b2f44066) | Jan 17, 2022 |
| Lenovo        | ThinkPad T470 20HDA022CD    | Notebook    | [3b3eeaa6b7](https://linux-hardware.org/?probe=3b3eeaa6b7) | Jan 14, 2022 |
| Synology      | DS216+                      | Notebook    | [8650ca59f1](https://linux-hardware.org/?probe=8650ca59f1) | Jan 10, 2022 |
| Dell          | Latitude E6400              | Notebook    | [ba6b82b98b](https://linux-hardware.org/?probe=ba6b82b98b) | Jan 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [45d678095f](https://linux-hardware.org/?probe=45d678095f) | Jan 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b3a76ceb99](https://linux-hardware.org/?probe=b3a76ceb99) | Dec 31, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [8d56c47c8d](https://linux-hardware.org/?probe=8d56c47c8d) | Dec 31, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [666b0b18f5](https://linux-hardware.org/?probe=666b0b18f5) | Dec 30, 2021 |
| Dell          | 0MWYPT A02                  | Desktop     | [08d5ba6a97](https://linux-hardware.org/?probe=08d5ba6a97) | Dec 30, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [590ae02fdb](https://linux-hardware.org/?probe=590ae02fdb) | Dec 29, 2021 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [ad94c90825](https://linux-hardware.org/?probe=ad94c90825) | Dec 29, 2021 |
| Samsung       | 500R5L/501R5L/500R5P/550... | Notebook    | [1f24ba261b](https://linux-hardware.org/?probe=1f24ba261b) | Dec 27, 2021 |
| Google        | Akemi                       | Notebook    | [295fd594af](https://linux-hardware.org/?probe=295fd594af) | Dec 27, 2021 |
| HP            | EliteBook 8470w             | Notebook    | [87c1cb1da7](https://linux-hardware.org/?probe=87c1cb1da7) | Dec 23, 2021 |
| Microsoft     | Surface Go 3                | Tablet      | [70703de094](https://linux-hardware.org/?probe=70703de094) | Dec 22, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [8447bd4156](https://linux-hardware.org/?probe=8447bd4156) | Dec 22, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [a7cc31a69f](https://linux-hardware.org/?probe=a7cc31a69f) | Dec 22, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [fabd656de1](https://linux-hardware.org/?probe=fabd656de1) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [50d0f206e1](https://linux-hardware.org/?probe=50d0f206e1) | Dec 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [c2474eed31](https://linux-hardware.org/?probe=c2474eed31) | Dec 21, 2021 |
| Microsoft     | Surface Go 3                | Tablet      | [1081ed2c15](https://linux-hardware.org/?probe=1081ed2c15) | Dec 20, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [1564f2f5ea](https://linux-hardware.org/?probe=1564f2f5ea) | Dec 18, 2021 |
| Lenovo        | Unknown                     | Desktop     | [64951d70ab](https://linux-hardware.org/?probe=64951d70ab) | Dec 16, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [1146dc777c](https://linux-hardware.org/?probe=1146dc777c) | Dec 15, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [e3c15cfedb](https://linux-hardware.org/?probe=e3c15cfedb) | Dec 14, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [5559a99303](https://linux-hardware.org/?probe=5559a99303) | Dec 14, 2021 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [c029d9c42b](https://linux-hardware.org/?probe=c029d9c42b) | Dec 14, 2021 |
| ASUSTek       | B85M-F                      | Desktop     | [04b3b165f6](https://linux-hardware.org/?probe=04b3b165f6) | Dec 14, 2021 |
| Lenovo        | [9532AC1] STC               | Server      | [78113d1370](https://linux-hardware.org/?probe=78113d1370) | Dec 13, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [ce9a3f2c74](https://linux-hardware.org/?probe=ce9a3f2c74) | Dec 13, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [4f8e294d95](https://linux-hardware.org/?probe=4f8e294d95) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [bf19b30902](https://linux-hardware.org/?probe=bf19b30902) | Dec 13, 2021 |
| Lenovo        | 3141 NOK                    | Desktop     | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [877a0414c3](https://linux-hardware.org/?probe=877a0414c3) | Dec 12, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [c4efae322a](https://linux-hardware.org/?probe=c4efae322a) | Dec 12, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [bd4021ec3d](https://linux-hardware.org/?probe=bd4021ec3d) | Dec 11, 2021 |
| Insyde        | CherryTrail                 | Notebook    | [1525831810](https://linux-hardware.org/?probe=1525831810) | Dec 11, 2021 |
| Lenovo        | Legion Y9000X 2020 81YY     | Notebook    | [acd0b9c831](https://linux-hardware.org/?probe=acd0b9c831) | Dec 11, 2021 |
| HASEE Comp... | E400                        | Notebook    | [32bee165ba](https://linux-hardware.org/?probe=32bee165ba) | Dec 11, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [8c952bfc3d](https://linux-hardware.org/?probe=8c952bfc3d) | Dec 11, 2021 |
| Lenovo        | Unknown                     | Convertible | [fac9e252e4](https://linux-hardware.org/?probe=fac9e252e4) | Dec 11, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [fe97757850](https://linux-hardware.org/?probe=fe97757850) | Dec 10, 2021 |
| Fujitsu       | FMVNQ8P9                    | Notebook    | [fe3a7ec790](https://linux-hardware.org/?probe=fe3a7ec790) | Dec 10, 2021 |
| Fujitsu       | FMVNQ8P9                    | Notebook    | [c6f3827cb1](https://linux-hardware.org/?probe=c6f3827cb1) | Dec 09, 2021 |
| Fujitsu       | FMVNQ8P9                    | Notebook    | [04ca55ea2b](https://linux-hardware.org/?probe=04ca55ea2b) | Dec 09, 2021 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [ff8706d7ac](https://linux-hardware.org/?probe=ff8706d7ac) | Dec 07, 2021 |
| OEM           | TOP77D Ver1.0               | Desktop     | [5747ccfcd4](https://linux-hardware.org/?probe=5747ccfcd4) | Dec 07, 2021 |
| ASRock        | B360M-ITX/ac                | Desktop     | [2490a94114](https://linux-hardware.org/?probe=2490a94114) | Dec 07, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [801df46937](https://linux-hardware.org/?probe=801df46937) | Dec 07, 2021 |
| Supermicro    | X10DRL-i                    | Server      | [e7819a0518](https://linux-hardware.org/?probe=e7819a0518) | Dec 06, 2021 |
| Nvidia        | Tegra                       | Soc         | [b62c884aec](https://linux-hardware.org/?probe=b62c884aec) | Dec 05, 2021 |
| AOC           | A815HB                      | Desktop     | [b1aec8b16c](https://linux-hardware.org/?probe=b1aec8b16c) | Dec 04, 2021 |
| Lenovo        | B41-80 80LG                 | Notebook    | [96e84134f0](https://linux-hardware.org/?probe=96e84134f0) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [63dade9d7b](https://linux-hardware.org/?probe=63dade9d7b) | Dec 01, 2021 |
| OEM           | TOP77D Ver1.0               | Desktop     | [6b91b58b81](https://linux-hardware.org/?probe=6b91b58b81) | Nov 30, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [8e84498214](https://linux-hardware.org/?probe=8e84498214) | Nov 30, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [69a76fd0b6](https://linux-hardware.org/?probe=69a76fd0b6) | Nov 29, 2021 |
| HUAWEI        | BC11SPCC V100R001C10        | Server      | [eb5771b190](https://linux-hardware.org/?probe=eb5771b190) | Nov 29, 2021 |
| Lenovo        | Unknown                     | Notebook    | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| Timi          | A7S                         | Notebook    | [625bafd45f](https://linux-hardware.org/?probe=625bafd45f) | Nov 27, 2021 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [109d14527f](https://linux-hardware.org/?probe=109d14527f) | Nov 27, 2021 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [b316c12d03](https://linux-hardware.org/?probe=b316c12d03) | Nov 27, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [27a4935e65](https://linux-hardware.org/?probe=27a4935e65) | Nov 26, 2021 |
| Jemper        | EZPAD WS_reserve            | Notebook    | [de173db361](https://linux-hardware.org/?probe=de173db361) | Nov 25, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c487bf6a9c](https://linux-hardware.org/?probe=c487bf6a9c) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [fa956800a1](https://linux-hardware.org/?probe=fa956800a1) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3d27077285](https://linux-hardware.org/?probe=3d27077285) | Nov 24, 2021 |
| ASUSTek       | B85M-G PLUS                 | Desktop     | [e198df930c](https://linux-hardware.org/?probe=e198df930c) | Nov 23, 2021 |
| ASUSTek       | B85M-G PLUS                 | Desktop     | [023ab776cd](https://linux-hardware.org/?probe=023ab776cd) | Nov 23, 2021 |
| Google        | Panther                     | Desktop     | [5e5d9936ec](https://linux-hardware.org/?probe=5e5d9936ec) | Nov 23, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [6a0bda5a7d](https://linux-hardware.org/?probe=6a0bda5a7d) | Nov 22, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [af9a5a76c3](https://linux-hardware.org/?probe=af9a5a76c3) | Nov 22, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| Lenovo        | 3734 SDK0L77769 WIN 3423... | All in one  | [53462f848a](https://linux-hardware.org/?probe=53462f848a) | Nov 20, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [7734a8d28c](https://linux-hardware.org/?probe=7734a8d28c) | Nov 18, 2021 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [69c06885de](https://linux-hardware.org/?probe=69c06885de) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [6da7601574](https://linux-hardware.org/?probe=6da7601574) | Nov 18, 2021 |
| ASRock        | TRX40 Creator               | Desktop     | [bdd3471fa2](https://linux-hardware.org/?probe=bdd3471fa2) | Nov 17, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [4d73c8557a](https://linux-hardware.org/?probe=4d73c8557a) | Nov 17, 2021 |
| Lenovo        | ThinkPad T430 2347G61       | Notebook    | [12ee1cee2b](https://linux-hardware.org/?probe=12ee1cee2b) | Nov 16, 2021 |
| AOC           | A815HB                      | Desktop     | [e56b509a5a](https://linux-hardware.org/?probe=e56b509a5a) | Nov 16, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [8c23aaf339](https://linux-hardware.org/?probe=8c23aaf339) | Nov 15, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [01b7731b34](https://linux-hardware.org/?probe=01b7731b34) | Nov 14, 2021 |
| MSI           | Delta 15 A5EFK              | Notebook    | [bc348014b5](https://linux-hardware.org/?probe=bc348014b5) | Nov 13, 2021 |
| Lenovo        | Legion R7000P2021H 82JU     | Notebook    | [19ffbfb846](https://linux-hardware.org/?probe=19ffbfb846) | Nov 13, 2021 |
| Dell          | Inspiron 7447               | Notebook    | [4ca16063da](https://linux-hardware.org/?probe=4ca16063da) | Nov 12, 2021 |
| Lenovo        | 3734 SDK0L77769 WIN 3423... | All in one  | [51d1a5ac24](https://linux-hardware.org/?probe=51d1a5ac24) | Nov 12, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [00e34bc46e](https://linux-hardware.org/?probe=00e34bc46e) | Nov 11, 2021 |
| Shanghai Z... | EA170_ TBD                  | Desktop     | [edc1846e0f](https://linux-hardware.org/?probe=edc1846e0f) | Nov 10, 2021 |
| Shanghai Z... | EA170_ TBD                  | Desktop     | [9f839630ac](https://linux-hardware.org/?probe=9f839630ac) | Nov 10, 2021 |
| Jumper        | EZbook                      | Notebook    | [f1391c1f4b](https://linux-hardware.org/?probe=f1391c1f4b) | Nov 10, 2021 |
| Dell          | Inspiron 7472               | Notebook    | [2508fadf63](https://linux-hardware.org/?probe=2508fadf63) | Nov 10, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [74d845aae1](https://linux-hardware.org/?probe=74d845aae1) | Nov 07, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [67670eea60](https://linux-hardware.org/?probe=67670eea60) | Nov 07, 2021 |
| Dell          | G15 5515                    | Notebook    | [1e5e0ab274](https://linux-hardware.org/?probe=1e5e0ab274) | Nov 06, 2021 |
| Google        | Akemi                       | Notebook    | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | Notebook    | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [17339fe912](https://linux-hardware.org/?probe=17339fe912) | Nov 03, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [7aa37239c1](https://linux-hardware.org/?probe=7aa37239c1) | Nov 03, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [0d89b6423c](https://linux-hardware.org/?probe=0d89b6423c) | Oct 31, 2021 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [127b977658](https://linux-hardware.org/?probe=127b977658) | Oct 31, 2021 |
| Timi          | A34R                        | Notebook    | [f5385d6b10](https://linux-hardware.org/?probe=f5385d6b10) | Oct 31, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [8a74691ba9](https://linux-hardware.org/?probe=8a74691ba9) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [cafc4421b2](https://linux-hardware.org/?probe=cafc4421b2) | Oct 29, 2021 |
| Dell          | G3 3500                     | Notebook    | [a2d09beb8d](https://linux-hardware.org/?probe=a2d09beb8d) | Oct 25, 2021 |
| Toshiba       | dynabook Satellite T772/... | Notebook    | [070723f36c](https://linux-hardware.org/?probe=070723f36c) | Oct 24, 2021 |
| Lenovo        | 3107 SDK0L77769 WIN 3423... | Desktop     | [6a7a621271](https://linux-hardware.org/?probe=6a7a621271) | Oct 22, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [2815629b34](https://linux-hardware.org/?probe=2815629b34) | Oct 21, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [9f2d69e4c4](https://linux-hardware.org/?probe=9f2d69e4c4) | Oct 20, 2021 |
| Dell          | 0H21J3 A07                  | Server      | [c7b39e92ca](https://linux-hardware.org/?probe=c7b39e92ca) | Oct 19, 2021 |
| Dell          | 0H21J3 A07                  | Server      | [9b3a90c143](https://linux-hardware.org/?probe=9b3a90c143) | Oct 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [2fb1797d3d](https://linux-hardware.org/?probe=2fb1797d3d) | Oct 19, 2021 |
| Dell          | G3 3500                     | Notebook    | [ec734562a6](https://linux-hardware.org/?probe=ec734562a6) | Oct 19, 2021 |
| Timi          | A34                         | Notebook    | [e2fbec93e6](https://linux-hardware.org/?probe=e2fbec93e6) | Oct 17, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20T2A... | Notebook    | [0c261084db](https://linux-hardware.org/?probe=0c261084db) | Oct 16, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [00196d9727](https://linux-hardware.org/?probe=00196d9727) | Oct 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [4aa5287a00](https://linux-hardware.org/?probe=4aa5287a00) | Oct 15, 2021 |
| ASRock        | B85M Pro4                   | Desktop     | [bf91ce9da1](https://linux-hardware.org/?probe=bf91ce9da1) | Oct 14, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [050314f62a](https://linux-hardware.org/?probe=050314f62a) | Oct 13, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [d2b877508b](https://linux-hardware.org/?probe=d2b877508b) | Oct 13, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [d3fdfb0745](https://linux-hardware.org/?probe=d3fdfb0745) | Oct 13, 2021 |
| Dell          | 0C96W1 A02                  | Desktop     | [edb83b3d2f](https://linux-hardware.org/?probe=edb83b3d2f) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [3eb7a24e5a](https://linux-hardware.org/?probe=3eb7a24e5a) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [38bb1cfdc4](https://linux-hardware.org/?probe=38bb1cfdc4) | Oct 12, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [5e8e9aea62](https://linux-hardware.org/?probe=5e8e9aea62) | Oct 12, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [bce3e39f4c](https://linux-hardware.org/?probe=bce3e39f4c) | Oct 10, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [1c4fbe0fa4](https://linux-hardware.org/?probe=1c4fbe0fa4) | Oct 10, 2021 |
| HP            | 520                         | Notebook    | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| HP            | ZHAN 66 Pro G1              | Notebook    | [a1a1c41c6a](https://linux-hardware.org/?probe=a1a1c41c6a) | Oct 09, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [d63fd746be](https://linux-hardware.org/?probe=d63fd746be) | Oct 09, 2021 |
| HP            | ZHAN 66 Pro G1              | Notebook    | [fcc291e2f1](https://linux-hardware.org/?probe=fcc291e2f1) | Oct 08, 2021 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [bc9337f46e](https://linux-hardware.org/?probe=bc9337f46e) | Oct 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [cbb2ea622b](https://linux-hardware.org/?probe=cbb2ea622b) | Oct 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [abd011c6b2](https://linux-hardware.org/?probe=abd011c6b2) | Oct 06, 2021 |
| ASUSTek       | A55BM-E                     | Desktop     | [970153a68c](https://linux-hardware.org/?probe=970153a68c) | Oct 03, 2021 |
| HP            | ZHAN 66 Pro 15 G3           | Notebook    | [0f58e969f6](https://linux-hardware.org/?probe=0f58e969f6) | Oct 03, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| Timi          | TM1613                      | Notebook    | [f6bb688e77](https://linux-hardware.org/?probe=f6bb688e77) | Sep 29, 2021 |
| Lenovo        | Legion Y7000 2020 82AV      | Notebook    | [64d71e1177](https://linux-hardware.org/?probe=64d71e1177) | Sep 29, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [f1420c5af0](https://linux-hardware.org/?probe=f1420c5af0) | Sep 29, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [de13c8f3fa](https://linux-hardware.org/?probe=de13c8f3fa) | Sep 29, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [1b471b415d](https://linux-hardware.org/?probe=1b471b415d) | Sep 29, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [5f5ae3035b](https://linux-hardware.org/?probe=5f5ae3035b) | Sep 29, 2021 |
| ASRock        | TRX40 Creator               | Desktop     | [c7b8fcc312](https://linux-hardware.org/?probe=c7b8fcc312) | Sep 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [4c18e17d7d](https://linux-hardware.org/?probe=4c18e17d7d) | Sep 29, 2021 |
| Soyo          | SY-Thin Mini H110           | Mini pc     | [ca900f89d0](https://linux-hardware.org/?probe=ca900f89d0) | Sep 28, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [8adcff21a2](https://linux-hardware.org/?probe=8adcff21a2) | Sep 27, 2021 |
| Lenovo        | XiaoXinAir 14ALC 2021 82... | Notebook    | [df352fba0f](https://linux-hardware.org/?probe=df352fba0f) | Sep 27, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [bb17541aae](https://linux-hardware.org/?probe=bb17541aae) | Sep 26, 2021 |
| Terrans Fo... | AMD                         | Notebook    | [db4b9e36ab](https://linux-hardware.org/?probe=db4b9e36ab) | Sep 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [10ce8f4e5e](https://linux-hardware.org/?probe=10ce8f4e5e) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b62637ba85](https://linux-hardware.org/?probe=b62637ba85) | Sep 25, 2021 |
| ASRockRack    | EPC621D8A                   | Server      | [2244eb7809](https://linux-hardware.org/?probe=2244eb7809) | Sep 24, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [01362b36bf](https://linux-hardware.org/?probe=01362b36bf) | Sep 24, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | Notebook    | [be9156bd20](https://linux-hardware.org/?probe=be9156bd20) | Sep 24, 2021 |
| Lenovo        | XiaoXin-15IWL 2019 81QS     | Notebook    | [f726b13948](https://linux-hardware.org/?probe=f726b13948) | Sep 22, 2021 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | Notebook    | [0a99b9ac87](https://linux-hardware.org/?probe=0a99b9ac87) | Sep 22, 2021 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | Notebook    | [ea86578390](https://linux-hardware.org/?probe=ea86578390) | Sep 22, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [508bab38ae](https://linux-hardware.org/?probe=508bab38ae) | Sep 20, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QTA0... | Notebook    | [9a59e3a4f1](https://linux-hardware.org/?probe=9a59e3a4f1) | Sep 20, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [8b09747789](https://linux-hardware.org/?probe=8b09747789) | Sep 20, 2021 |
| Lenovo        | ThinkPad P53 20QQA004CD     | Notebook    | [50b6533131](https://linux-hardware.org/?probe=50b6533131) | Sep 20, 2021 |
| Sapphire      | Pure Platinum 970A-PLUS     | Desktop     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [bc175433f9](https://linux-hardware.org/?probe=bc175433f9) | Sep 18, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [80017bc79b](https://linux-hardware.org/?probe=80017bc79b) | Sep 18, 2021 |
| ASUSTek       | B360M-BASALT                | Desktop     | [f1783ce369](https://linux-hardware.org/?probe=f1783ce369) | Sep 18, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | Notebook    | [18cbc8a35f](https://linux-hardware.org/?probe=18cbc8a35f) | Sep 18, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | Notebook    | [5debd35710](https://linux-hardware.org/?probe=5debd35710) | Sep 18, 2021 |
| GXNOVA Com... | GX2                         | Notebook    | [ab148b2b4e](https://linux-hardware.org/?probe=ab148b2b4e) | Sep 14, 2021 |
| Lenovo        | NOK                         | Desktop     | [61a15d9531](https://linux-hardware.org/?probe=61a15d9531) | Sep 14, 2021 |
| Notebook      | P65xHP                      | Notebook    | [12a7ec2b86](https://linux-hardware.org/?probe=12a7ec2b86) | Sep 14, 2021 |
| Intel         | AST2600EVB                  | Server      | [aead99f55d](https://linux-hardware.org/?probe=aead99f55d) | Sep 14, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAA... | Notebook    | [ebcb7d7982](https://linux-hardware.org/?probe=ebcb7d7982) | Sep 14, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [a48ec730b7](https://linux-hardware.org/?probe=a48ec730b7) | Sep 13, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [db46242eec](https://linux-hardware.org/?probe=db46242eec) | Sep 13, 2021 |
| HP            | 431                         | Notebook    | [c2510d05b4](https://linux-hardware.org/?probe=c2510d05b4) | Sep 12, 2021 |
| HP            | 431                         | Notebook    | [d19b47e4d8](https://linux-hardware.org/?probe=d19b47e4d8) | Sep 12, 2021 |
| Sony          | SVT11215CGW                 | Notebook    | [0e12747ab1](https://linux-hardware.org/?probe=0e12747ab1) | Sep 12, 2021 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [35ee76ca1b](https://linux-hardware.org/?probe=35ee76ca1b) | Sep 08, 2021 |
| Intel         | EAGLESTREAM E63448-400      | Server      | [7c59811abb](https://linux-hardware.org/?probe=7c59811abb) | Sep 08, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [35ee0ea8e4](https://linux-hardware.org/?probe=35ee0ea8e4) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2a4adea555](https://linux-hardware.org/?probe=2a4adea555) | Sep 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [025d2a8ddb](https://linux-hardware.org/?probe=025d2a8ddb) | Sep 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [9bbf3f2d82](https://linux-hardware.org/?probe=9bbf3f2d82) | Sep 05, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [3758bf5026](https://linux-hardware.org/?probe=3758bf5026) | Sep 01, 2021 |
| Timi          | TM1613                      | Notebook    | [f25eeca060](https://linux-hardware.org/?probe=f25eeca060) | Sep 01, 2021 |
| Dell          | Latitude E6530              | Notebook    | [5996acf813](https://linux-hardware.org/?probe=5996acf813) | Aug 31, 2021 |
| GPD           | G1618-03                    | Notebook    | [d680dd4360](https://linux-hardware.org/?probe=d680dd4360) | Aug 31, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [27b23ba02b](https://linux-hardware.org/?probe=27b23ba02b) | Aug 29, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [8625d6f2f1](https://linux-hardware.org/?probe=8625d6f2f1) | Aug 28, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [2d0a7ed28d](https://linux-hardware.org/?probe=2d0a7ed28d) | Aug 28, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [fc294326ce](https://linux-hardware.org/?probe=fc294326ce) | Aug 28, 2021 |
| Lenovo        | ThinkPad X220 429044C       | Notebook    | [20057996af](https://linux-hardware.org/?probe=20057996af) | Aug 27, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [03b37f86b2](https://linux-hardware.org/?probe=03b37f86b2) | Aug 27, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [08b5160307](https://linux-hardware.org/?probe=08b5160307) | Aug 27, 2021 |
| Lenovo        | K4450 20229                 | Notebook    | [70e7af9fae](https://linux-hardware.org/?probe=70e7af9fae) | Aug 26, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [4563619600](https://linux-hardware.org/?probe=4563619600) | Aug 25, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [33cc1aba5f](https://linux-hardware.org/?probe=33cc1aba5f) | Aug 25, 2021 |
| Lenovo        | K4450 20229                 | Notebook    | [e1c019df72](https://linux-hardware.org/?probe=e1c019df72) | Aug 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [e0e805180d](https://linux-hardware.org/?probe=e0e805180d) | Aug 22, 2021 |
| Lenovo        | ThinkPad E455 20DEA027CD    | Notebook    | [8edb3642cb](https://linux-hardware.org/?probe=8edb3642cb) | Aug 22, 2021 |
| Timi          | TM1612                      | Notebook    | [485caf5846](https://linux-hardware.org/?probe=485caf5846) | Aug 20, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [ce37ed52aa](https://linux-hardware.org/?probe=ce37ed52aa) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [18f0785e64](https://linux-hardware.org/?probe=18f0785e64) | Aug 19, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [321cf3c58f](https://linux-hardware.org/?probe=321cf3c58f) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [753b5b706d](https://linux-hardware.org/?probe=753b5b706d) | Aug 18, 2021 |
| Acer          | Nitro AN515-57              | Notebook    | [3c18d3a700](https://linux-hardware.org/?probe=3c18d3a700) | Aug 17, 2021 |
| Alienware     | m17                         | Notebook    | [5fdd4a64a3](https://linux-hardware.org/?probe=5fdd4a64a3) | Aug 17, 2021 |
| Lenovo        | Legion R9000K2021H 82N6     | Notebook    | [048b8332cc](https://linux-hardware.org/?probe=048b8332cc) | Aug 13, 2021 |
| Lenovo        | ThinkPad L430 2466EY7       | Notebook    | [b93128f327](https://linux-hardware.org/?probe=b93128f327) | Aug 12, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5e1cc5b229](https://linux-hardware.org/?probe=5e1cc5b229) | Aug 11, 2021 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [aaef52aca2](https://linux-hardware.org/?probe=aaef52aca2) | Aug 10, 2021 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [98a65d0b3b](https://linux-hardware.org/?probe=98a65d0b3b) | Aug 10, 2021 |
| Yanling       | YL-KBRL2 Series Ver:1.01    | Desktop     | [ad2f5f75d8](https://linux-hardware.org/?probe=ad2f5f75d8) | Aug 10, 2021 |
| TSINGHUA T... | B460-N2                     | Desktop     | [59d9384348](https://linux-hardware.org/?probe=59d9384348) | Aug 09, 2021 |
| ASUSTek       | Z97-PRO                     | Desktop     | [a0e65d5ee7](https://linux-hardware.org/?probe=a0e65d5ee7) | Aug 08, 2021 |
| ASUSTek       | FX503VD                     | Notebook    | [7c2b153867](https://linux-hardware.org/?probe=7c2b153867) | Aug 08, 2021 |
| Fujitsu       | LIFEBOOK V1020              | Notebook    | [8eff816347](https://linux-hardware.org/?probe=8eff816347) | Aug 08, 2021 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [293b45eded](https://linux-hardware.org/?probe=293b45eded) | Aug 07, 2021 |
| GPD           | G1618-03                    | Notebook    | [25a0b540aa](https://linux-hardware.org/?probe=25a0b540aa) | Aug 07, 2021 |
| Dell          | Inspiron 11-3168            | Notebook    | [67552d79ac](https://linux-hardware.org/?probe=67552d79ac) | Aug 05, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [30526e56ab](https://linux-hardware.org/?probe=30526e56ab) | Aug 05, 2021 |
| Lenovo        | ZHAOYANG K3-ITL 82E3        | Notebook    | [ee2be4cea9](https://linux-hardware.org/?probe=ee2be4cea9) | Aug 03, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [07e9ee8610](https://linux-hardware.org/?probe=07e9ee8610) | Aug 02, 2021 |
| Chuwi         | UBook                       | Tablet      | [1da6b43703](https://linux-hardware.org/?probe=1da6b43703) | Aug 02, 2021 |
| Lenovo        | MIIX 2 8 20326              | Tablet      | [205a7c853a](https://linux-hardware.org/?probe=205a7c853a) | Jul 31, 2021 |
| Gigabyte      | MZ71-CE1-00 01000100        | Server      | [c6e1e678f5](https://linux-hardware.org/?probe=c6e1e678f5) | Jul 30, 2021 |
| Gigabyte      | MZ71-CE1-00 01000100        | Server      | [8d9705bd2a](https://linux-hardware.org/?probe=8d9705bd2a) | Jul 30, 2021 |
| Apple         | MacBookPro16,1              | Notebook    | [124425a1ed](https://linux-hardware.org/?probe=124425a1ed) | Jul 28, 2021 |
| MSI           | GT62VR 7RE                  | Notebook    | [5f02658195](https://linux-hardware.org/?probe=5f02658195) | Jul 27, 2021 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [e411a84d3c](https://linux-hardware.org/?probe=e411a84d3c) | Jul 26, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | Notebook    | [1722982c29](https://linux-hardware.org/?probe=1722982c29) | Jul 26, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [474dfcb3e3](https://linux-hardware.org/?probe=474dfcb3e3) | Jul 26, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [e4d71ee9a8](https://linux-hardware.org/?probe=e4d71ee9a8) | Jul 24, 2021 |
| Intel         | Corbett Park CRB Revisio... | Notebook    | [17f1a1e73e](https://linux-hardware.org/?probe=17f1a1e73e) | Jul 21, 2021 |
| Lenovo        | Legion R70002020 82B6       | Notebook    | [d620ec97eb](https://linux-hardware.org/?probe=d620ec97eb) | Jul 21, 2021 |
| Lenovo        | G50-70m 20423               | Notebook    | [0b1a40c724](https://linux-hardware.org/?probe=0b1a40c724) | Jul 21, 2021 |
| Lenovo        | ThinkPad X230 23257Y1       | Notebook    | [f282cf1244](https://linux-hardware.org/?probe=f282cf1244) | Jul 18, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [06221fa5e9](https://linux-hardware.org/?probe=06221fa5e9) | Jul 16, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [9f2fb87684](https://linux-hardware.org/?probe=9f2fb87684) | Jul 16, 2021 |
| Toshiba       | NB300                       | Notebook    | [03b62f85cb](https://linux-hardware.org/?probe=03b62f85cb) | Jul 15, 2021 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [dd73dac900](https://linux-hardware.org/?probe=dd73dac900) | Jul 15, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | Desktop     | [d84332d50b](https://linux-hardware.org/?probe=d84332d50b) | Jul 14, 2021 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [d563d62b5f](https://linux-hardware.org/?probe=d563d62b5f) | Jul 14, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | Desktop     | [f68b508049](https://linux-hardware.org/?probe=f68b508049) | Jul 14, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [82c1959e49](https://linux-hardware.org/?probe=82c1959e49) | Jul 13, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [60c8b3011a](https://linux-hardware.org/?probe=60c8b3011a) | Jul 12, 2021 |
| AMD           | BL2 V2.3                    | Desktop     | [1053adf355](https://linux-hardware.org/?probe=1053adf355) | Jul 12, 2021 |
| HASEE Comp... | Computer                    | Notebook    | [641cab4c92](https://linux-hardware.org/?probe=641cab4c92) | Jul 11, 2021 |
| Clevo         | P7xxTM(1)                   | Notebook    | [98eeef735f](https://linux-hardware.org/?probe=98eeef735f) | Jul 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [9d18d07e36](https://linux-hardware.org/?probe=9d18d07e36) | Jul 06, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [26b5b9e3d3](https://linux-hardware.org/?probe=26b5b9e3d3) | Jul 06, 2021 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [f5a3e8f307](https://linux-hardware.org/?probe=f5a3e8f307) | Jul 06, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [d90c6cbf04](https://linux-hardware.org/?probe=d90c6cbf04) | Jul 04, 2021 |
| Quanta        | Winterfell                  | Server      | [e0ef143493](https://linux-hardware.org/?probe=e0ef143493) | Jul 03, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [50d75ad77d](https://linux-hardware.org/?probe=50d75ad77d) | Jul 03, 2021 |
| Dell          | 0GX297                      | Desktop     | [f4debf994a](https://linux-hardware.org/?probe=f4debf994a) | Jun 30, 2021 |
| Lenovo        | ZHAOYANG CF4620Z-A123 59... | Notebook    | [6f716961de](https://linux-hardware.org/?probe=6f716961de) | Jun 29, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [279dea011e](https://linux-hardware.org/?probe=279dea011e) | Jun 28, 2021 |
| HP            | 18E7                        | Desktop     | [5f0e216922](https://linux-hardware.org/?probe=5f0e216922) | Jun 28, 2021 |
| Terrans Fo... | X511                        | Notebook    | [7c131d9b3c](https://linux-hardware.org/?probe=7c131d9b3c) | Jun 27, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [c9180096a8](https://linux-hardware.org/?probe=c9180096a8) | Jun 26, 2021 |
| Toshiba       | Satellite C600              | Notebook    | [2be9935e22](https://linux-hardware.org/?probe=2be9935e22) | Jun 25, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [48335e0b08](https://linux-hardware.org/?probe=48335e0b08) | Jun 24, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | Desktop     | [70d8ede642](https://linux-hardware.org/?probe=70d8ede642) | Jun 23, 2021 |
| Dell          | G7 7500                     | Notebook    | [fc4a38d0b1](https://linux-hardware.org/?probe=fc4a38d0b1) | Jun 23, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [61460e5cfc](https://linux-hardware.org/?probe=61460e5cfc) | Jun 23, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [c916e64b0d](https://linux-hardware.org/?probe=c916e64b0d) | Jun 23, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | Desktop     | [8431bcbed8](https://linux-hardware.org/?probe=8431bcbed8) | Jun 22, 2021 |
| Apple         | MacBookAir5,2               | Notebook    | [6c83856ca5](https://linux-hardware.org/?probe=6c83856ca5) | Jun 22, 2021 |
| Toshiba       | Satellite C850-C008         | Notebook    | [91fc03f063](https://linux-hardware.org/?probe=91fc03f063) | Jun 21, 2021 |
| Timi          | TM1612                      | Notebook    | [c4fb55cbfd](https://linux-hardware.org/?probe=c4fb55cbfd) | Jun 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [f1200f8ad1](https://linux-hardware.org/?probe=f1200f8ad1) | Jun 20, 2021 |
| Timi          | TM1612                      | Notebook    | [dcb999a722](https://linux-hardware.org/?probe=dcb999a722) | Jun 20, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [c76462e732](https://linux-hardware.org/?probe=c76462e732) | Jun 20, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [c0ecdee03e](https://linux-hardware.org/?probe=c0ecdee03e) | Jun 20, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [4373344c26](https://linux-hardware.org/?probe=4373344c26) | Jun 20, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [43ef80b625](https://linux-hardware.org/?probe=43ef80b625) | Jun 19, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [439593d28e](https://linux-hardware.org/?probe=439593d28e) | Jun 19, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [45b203fa1d](https://linux-hardware.org/?probe=45b203fa1d) | Jun 19, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [8b9f25c98b](https://linux-hardware.org/?probe=8b9f25c98b) | Jun 19, 2021 |
| MSI           | GS66 Stealth 10SFS          | Notebook    | [7535868db2](https://linux-hardware.org/?probe=7535868db2) | Jun 18, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [c9a19ce57f](https://linux-hardware.org/?probe=c9a19ce57f) | Jun 18, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [c8249a8836](https://linux-hardware.org/?probe=c8249a8836) | Jun 17, 2021 |
| MSI           | GS66 Stealth 10SFS          | Notebook    | [c095a4437c](https://linux-hardware.org/?probe=c095a4437c) | Jun 17, 2021 |
| Hampoo        | Cherry Trail CR V300        | Notebook    | [344ff5676f](https://linux-hardware.org/?probe=344ff5676f) | Jun 16, 2021 |
| Loongson      | LS3A3000-7A1000-1w-V1.2-... | Desktop     | [014bdabb68](https://linux-hardware.org/?probe=014bdabb68) | Jun 16, 2021 |
| Lenovo        | Legion Y9000K 2019 SE 81... | Notebook    | [374ace3f30](https://linux-hardware.org/?probe=374ace3f30) | Jun 15, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [54128eb7cf](https://linux-hardware.org/?probe=54128eb7cf) | Jun 13, 2021 |
| HP            | Pavilion 15                 | Notebook    | [9e0e3015c3](https://linux-hardware.org/?probe=9e0e3015c3) | Jun 13, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [c178189191](https://linux-hardware.org/?probe=c178189191) | Jun 12, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [82334ce2ee](https://linux-hardware.org/?probe=82334ce2ee) | Jun 12, 2021 |
| Lenovo        | H310                        | Desktop     | [309031a039](https://linux-hardware.org/?probe=309031a039) | Jun 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [8834a1f44c](https://linux-hardware.org/?probe=8834a1f44c) | Jun 11, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [41d143b254](https://linux-hardware.org/?probe=41d143b254) | Jun 09, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [c8937f439d](https://linux-hardware.org/?probe=c8937f439d) | Jun 09, 2021 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [72f511586b](https://linux-hardware.org/?probe=72f511586b) | Jun 09, 2021 |
| HASEE Comp... | CW67S                       | Notebook    | [3012373a54](https://linux-hardware.org/?probe=3012373a54) | Jun 08, 2021 |
| Advantech     | DMS-BC30 A101-2             | Desktop     | [e9ee5e90e8](https://linux-hardware.org/?probe=e9ee5e90e8) | Jun 08, 2021 |
| Advantech     | DMS-BC30 A101-2             | Desktop     | [2fd059f38d](https://linux-hardware.org/?probe=2fd059f38d) | Jun 08, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [2ddd57f551](https://linux-hardware.org/?probe=2ddd57f551) | Jun 06, 2021 |
| Lenovo        | H310                        | Desktop     | [f36653c4fb](https://linux-hardware.org/?probe=f36653c4fb) | Jun 06, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [efb0b681f0](https://linux-hardware.org/?probe=efb0b681f0) | Jun 05, 2021 |
| Timi          | TM1612                      | Notebook    | [40318f2d95](https://linux-hardware.org/?probe=40318f2d95) | Jun 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [173f1c74f4](https://linux-hardware.org/?probe=173f1c74f4) | Jun 04, 2021 |
| Unknown       | Kunpeng Desktop Board D9... | Desktop     | [2a8b1a08bc](https://linux-hardware.org/?probe=2a8b1a08bc) | Jun 04, 2021 |
| Unknown       | Kunpeng Desktop Board D9... | Desktop     | [ead2c4250e](https://linux-hardware.org/?probe=ead2c4250e) | Jun 04, 2021 |
| Huanghe       | PRO H410M-C                 | Desktop     | [37534d085b](https://linux-hardware.org/?probe=37534d085b) | Jun 04, 2021 |
| Lenovo        | ThinkPad X230 23257Y1       | Notebook    | [d507dfaef3](https://linux-hardware.org/?probe=d507dfaef3) | Jun 02, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [7a11677611](https://linux-hardware.org/?probe=7a11677611) | Jun 01, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [eed35a825a](https://linux-hardware.org/?probe=eed35a825a) | May 31, 2021 |
| Lenovo        | ZHAOYANG K29 20186          | Notebook    | [f02d15e805](https://linux-hardware.org/?probe=f02d15e805) | May 31, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [b6047b1557](https://linux-hardware.org/?probe=b6047b1557) | May 31, 2021 |
| Huanghe       | PRO H410M-C                 | Desktop     | [1c92e63940](https://linux-hardware.org/?probe=1c92e63940) | May 31, 2021 |
| Supermicro    | X8DTH                       | Server      | [d9ed4f04a3](https://linux-hardware.org/?probe=d9ed4f04a3) | May 30, 2021 |
| Huanan        | X79 VAA1                    | Desktop     | [150afcb2d1](https://linux-hardware.org/?probe=150afcb2d1) | May 30, 2021 |
| Toshiba       | Satellite U800W             | Notebook    | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [32ca60dcea](https://linux-hardware.org/?probe=32ca60dcea) | May 30, 2021 |
| HUAWEI        | KPR-WX9                     | Notebook    | [9c73a8d7d6](https://linux-hardware.org/?probe=9c73a8d7d6) | May 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [83d261308f](https://linux-hardware.org/?probe=83d261308f) | May 26, 2021 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [a22fbcde28](https://linux-hardware.org/?probe=a22fbcde28) | May 26, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [59f94e4db6](https://linux-hardware.org/?probe=59f94e4db6) | May 25, 2021 |
| Centerm       | C92                         | Desktop     | [fe4761d2b2](https://linux-hardware.org/?probe=fe4761d2b2) | May 25, 2021 |
| Acer          | Aspire TC-606               | Desktop     | [db910234a6](https://linux-hardware.org/?probe=db910234a6) | May 25, 2021 |
| Soyo          | SY-I5GC2-L                  | Desktop     | [02a90f300e](https://linux-hardware.org/?probe=02a90f300e) | May 24, 2021 |
| Soyo          | SY-I5GC2-L                  | Desktop     | [91bdc4a9a0](https://linux-hardware.org/?probe=91bdc4a9a0) | May 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [c4842eda94](https://linux-hardware.org/?probe=c4842eda94) | May 24, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [5dca660f7e](https://linux-hardware.org/?probe=5dca660f7e) | May 22, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [b74e96d4be](https://linux-hardware.org/?probe=b74e96d4be) | May 22, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [c9e7ae41ba](https://linux-hardware.org/?probe=c9e7ae41ba) | May 21, 2021 |
| Lenovo        | ThinkPad X220 4290BB8       | Notebook    | [e147d7b57e](https://linux-hardware.org/?probe=e147d7b57e) | May 21, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [72904aba23](https://linux-hardware.org/?probe=72904aba23) | May 20, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [6331748487](https://linux-hardware.org/?probe=6331748487) | May 20, 2021 |
| ASUSTek       | UX302LA                     | Notebook    | [c04c98c26f](https://linux-hardware.org/?probe=c04c98c26f) | May 19, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [fa2352afac](https://linux-hardware.org/?probe=fa2352afac) | May 19, 2021 |
| HP            | Laptop 14s-fr0xxx           | Notebook    | [ee4105df76](https://linux-hardware.org/?probe=ee4105df76) | May 18, 2021 |
| MSI           | GS60 6QE                    | Notebook    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |
| MSI           | GS60 6QE                    | Notebook    | [41fe777475](https://linux-hardware.org/?probe=41fe777475) | May 18, 2021 |
| Dell          | Vostro 13 5310              | Notebook    | [ed812af95a](https://linux-hardware.org/?probe=ed812af95a) | May 17, 2021 |
| Gigabyte      | B365M D2V                   | Desktop     | [887f18105e](https://linux-hardware.org/?probe=887f18105e) | May 17, 2021 |
| Gigabyte      | B365M D2V                   | Desktop     | [644431aa47](https://linux-hardware.org/?probe=644431aa47) | May 17, 2021 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [41fbd83170](https://linux-hardware.org/?probe=41fbd83170) | May 17, 2021 |
| Lenovo        | 3176 SDK0L77767 WIN 3423... | Desktop     | [d418b8e0e9](https://linux-hardware.org/?probe=d418b8e0e9) | May 17, 2021 |
| Lenovo        | 3176 SDK0L77767 WIN 3423... | Desktop     | [b04d956c6e](https://linux-hardware.org/?probe=b04d956c6e) | May 17, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [b2cc4333b0](https://linux-hardware.org/?probe=b2cc4333b0) | May 16, 2021 |
| Dell          | Inspiron 7370               | Notebook    | [ee3ff1a75d](https://linux-hardware.org/?probe=ee3ff1a75d) | May 15, 2021 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [ef3422dd2d](https://linux-hardware.org/?probe=ef3422dd2d) | May 14, 2021 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [96c74bb052](https://linux-hardware.org/?probe=96c74bb052) | May 14, 2021 |
| Jumper        | EZbook                      | Notebook    | [8a28589e34](https://linux-hardware.org/?probe=8a28589e34) | May 13, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [049f443199](https://linux-hardware.org/?probe=049f443199) | May 11, 2021 |
| Jumper        | EZbook                      | Notebook    | [9c48c2d8c5](https://linux-hardware.org/?probe=9c48c2d8c5) | May 07, 2021 |
| HP            | EliteBook 745 G5            | Notebook    | [21422647b7](https://linux-hardware.org/?probe=21422647b7) | May 06, 2021 |
| Jumper        | EZbook                      | Notebook    | [741a5fbc51](https://linux-hardware.org/?probe=741a5fbc51) | May 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9e86c8ede5](https://linux-hardware.org/?probe=9e86c8ede5) | May 05, 2021 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [f813c25e0d](https://linux-hardware.org/?probe=f813c25e0d) | May 05, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [b3ffc8d1cb](https://linux-hardware.org/?probe=b3ffc8d1cb) | May 04, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [321f62efb9](https://linux-hardware.org/?probe=321f62efb9) | May 04, 2021 |
| Lenovo        | ThinkPad E480 20KN000UCD    | Notebook    | [f665cfa22e](https://linux-hardware.org/?probe=f665cfa22e) | May 04, 2021 |
| Lenovo        | ThinkPad E14 20RA002JCD     | Notebook    | [ca3b61c51a](https://linux-hardware.org/?probe=ca3b61c51a) | May 04, 2021 |
| ASUSTek       | X455LJ                      | Notebook    | [e769a18f8a](https://linux-hardware.org/?probe=e769a18f8a) | May 04, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [586195f9e8](https://linux-hardware.org/?probe=586195f9e8) | May 03, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [0f71a5127c](https://linux-hardware.org/?probe=0f71a5127c) | May 01, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [ebe2901cc8](https://linux-hardware.org/?probe=ebe2901cc8) | Apr 30, 2021 |
| HP            | ZHAN 99 G2 Mobile Workst... | Notebook    | [8647f6f8fb](https://linux-hardware.org/?probe=8647f6f8fb) | Apr 29, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [6ee00932dc](https://linux-hardware.org/?probe=6ee00932dc) | Apr 29, 2021 |
| HASEE Comp... | QTC6                        | Notebook    | [7f1f85fd8c](https://linux-hardware.org/?probe=7f1f85fd8c) | Apr 28, 2021 |
| Dell          | Inspiron 3482               | Notebook    | [a8ab0451de](https://linux-hardware.org/?probe=a8ab0451de) | Apr 27, 2021 |
| Lenovo        | ZHAOYANG K43c-80 81HX       | Notebook    | [de6628af88](https://linux-hardware.org/?probe=de6628af88) | Apr 27, 2021 |
| Lenovo        | No DPK                      | Desktop     | [15a0f7dbe3](https://linux-hardware.org/?probe=15a0f7dbe3) | Apr 27, 2021 |
| ELSKY         | M219F-6C                    | Desktop     | [85ce077799](https://linux-hardware.org/?probe=85ce077799) | Apr 22, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [5f7bac315c](https://linux-hardware.org/?probe=5f7bac315c) | Apr 19, 2021 |
| Acer          | Swift SF313-52              | Notebook    | [0f4028c401](https://linux-hardware.org/?probe=0f4028c401) | Apr 19, 2021 |
| Samsung       | 535U4C                      | Notebook    | [1bdb581e3d](https://linux-hardware.org/?probe=1bdb581e3d) | Apr 17, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [ee1c82a186](https://linux-hardware.org/?probe=ee1c82a186) | Apr 15, 2021 |
| Samsung       | 535U4C                      | Notebook    | [1f61906add](https://linux-hardware.org/?probe=1f61906add) | Apr 15, 2021 |
| HASEE Comp... | Unknown                     | Notebook    | [5abcc341b3](https://linux-hardware.org/?probe=5abcc341b3) | Apr 14, 2021 |
| HASEE Comp... | Unknown                     | Notebook    | [76f3519f3f](https://linux-hardware.org/?probe=76f3519f3f) | Apr 14, 2021 |
| Lenovo        | ThinkPad T410s 2912B99      | Notebook    | [cce75356c4](https://linux-hardware.org/?probe=cce75356c4) | Apr 11, 2021 |
| Unknown       | Unknown                     | Phone       | [1fb0779a5b](https://linux-hardware.org/?probe=1fb0779a5b) | Apr 10, 2021 |
| HP            | EliteBook 8770w             | Notebook    | [4b01a44998](https://linux-hardware.org/?probe=4b01a44998) | Apr 10, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [7c883d58c6](https://linux-hardware.org/?probe=7c883d58c6) | Apr 10, 2021 |
| Lenovo        | V10 ThinkPad X63            | Notebook    | [60ee0c7112](https://linux-hardware.org/?probe=60ee0c7112) | Apr 08, 2021 |
| Lenovo        | V10 ThinkPad X63            | Notebook    | [dfa1081980](https://linux-hardware.org/?probe=dfa1081980) | Apr 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [e03bf9d1a9](https://linux-hardware.org/?probe=e03bf9d1a9) | Apr 07, 2021 |
| MECHREVO      | S3 Pro                      | Notebook    | [a8656190d7](https://linux-hardware.org/?probe=a8656190d7) | Apr 04, 2021 |
| Dell          | System XPS L702X            | Notebook    | [e15be45763](https://linux-hardware.org/?probe=e15be45763) | Apr 04, 2021 |
| Dell          | 0H21J3 A09                  | Server      | [51fb8fee00](https://linux-hardware.org/?probe=51fb8fee00) | Apr 04, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [c557439d9f](https://linux-hardware.org/?probe=c557439d9f) | Apr 03, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [66d76dda01](https://linux-hardware.org/?probe=66d76dda01) | Apr 03, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [8406dee7f4](https://linux-hardware.org/?probe=8406dee7f4) | Apr 02, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [6e403bbf50](https://linux-hardware.org/?probe=6e403bbf50) | Apr 02, 2021 |
| GPD           | P2 MAX                      | Notebook    | [b07bc1f694](https://linux-hardware.org/?probe=b07bc1f694) | Apr 02, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [aa8f00686c](https://linux-hardware.org/?probe=aa8f00686c) | Apr 01, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [7ffd62b3fa](https://linux-hardware.org/?probe=7ffd62b3fa) | Mar 31, 2021 |
| ASUSTek       | UX370UAF                    | Convertible | [6570252e3e](https://linux-hardware.org/?probe=6570252e3e) | Mar 30, 2021 |
| Lenovo        | Unknown                     | Notebook    | [98ed905fb1](https://linux-hardware.org/?probe=98ed905fb1) | Mar 28, 2021 |
| ASUSTek       | UX370UAF                    | Convertible | [5965f6dec2](https://linux-hardware.org/?probe=5965f6dec2) | Mar 28, 2021 |
| Lenovo        | ThinkPad X230 2324DM2       | Notebook    | [2cf882da9e](https://linux-hardware.org/?probe=2cf882da9e) | Mar 28, 2021 |
| Dell          | Latitude E6400              | Notebook    | [ac6d60eaa9](https://linux-hardware.org/?probe=ac6d60eaa9) | Mar 26, 2021 |
| Dell          | Latitude E6400              | Notebook    | [7b97516ad8](https://linux-hardware.org/?probe=7b97516ad8) | Mar 26, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [4ff6ff15fc](https://linux-hardware.org/?probe=4ff6ff15fc) | Mar 26, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [16f1d9e647](https://linux-hardware.org/?probe=16f1d9e647) | Mar 18, 2021 |
| HP            | ZHAN 99 G2 Mobile Workst... | Notebook    | [d16fc044eb](https://linux-hardware.org/?probe=d16fc044eb) | Mar 18, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [a95086c30b](https://linux-hardware.org/?probe=a95086c30b) | Mar 18, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [d98e2dea30](https://linux-hardware.org/?probe=d98e2dea30) | Mar 17, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [e10243fa5c](https://linux-hardware.org/?probe=e10243fa5c) | Mar 17, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [b96252ab8f](https://linux-hardware.org/?probe=b96252ab8f) | Mar 15, 2021 |
| SYWZ          | S210H Series                | Desktop     | [2e8183b6eb](https://linux-hardware.org/?probe=2e8183b6eb) | Mar 14, 2021 |
| SYWZ          | S210H Series                | Desktop     | [d0f36756ab](https://linux-hardware.org/?probe=d0f36756ab) | Mar 14, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [d73ebe56eb](https://linux-hardware.org/?probe=d73ebe56eb) | Mar 11, 2021 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [4202717644](https://linux-hardware.org/?probe=4202717644) | Mar 05, 2021 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [3b64f161c0](https://linux-hardware.org/?probe=3b64f161c0) | Mar 05, 2021 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [f3cfea77ac](https://linux-hardware.org/?probe=f3cfea77ac) | Mar 04, 2021 |
| Lenovo        | ThinkPad X220 4291HL8       | Notebook    | [f8dd5d3807](https://linux-hardware.org/?probe=f8dd5d3807) | Mar 02, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [229409a8dc](https://linux-hardware.org/?probe=229409a8dc) | Feb 25, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [336e949796](https://linux-hardware.org/?probe=336e949796) | Feb 24, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [96a3577708](https://linux-hardware.org/?probe=96a3577708) | Feb 24, 2021 |
| HP            | 1000                        | Notebook    | [2ab8891f42](https://linux-hardware.org/?probe=2ab8891f42) | Feb 23, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [44013b0bb4](https://linux-hardware.org/?probe=44013b0bb4) | Feb 23, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [93e1220042](https://linux-hardware.org/?probe=93e1220042) | Feb 22, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [78ec6d58ba](https://linux-hardware.org/?probe=78ec6d58ba) | Feb 22, 2021 |
| Dell          | 03CPWF A00                  | Desktop     | [126a2e8974](https://linux-hardware.org/?probe=126a2e8974) | Feb 22, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [0ac46a588c](https://linux-hardware.org/?probe=0ac46a588c) | Feb 21, 2021 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [bbace409ed](https://linux-hardware.org/?probe=bbace409ed) | Feb 18, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [df1e1e308b](https://linux-hardware.org/?probe=df1e1e308b) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [94362e140c](https://linux-hardware.org/?probe=94362e140c) | Feb 18, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [6e1c4be9d8](https://linux-hardware.org/?probe=6e1c4be9d8) | Feb 17, 2021 |
| HASEE Comp... | E460                        | Notebook    | [5af90fef31](https://linux-hardware.org/?probe=5af90fef31) | Feb 17, 2021 |
| Gigabyte      | B85M-D2V-SI                 | Desktop     | [a0779807a2](https://linux-hardware.org/?probe=a0779807a2) | Feb 15, 2021 |
| Timi          | TM1703                      | Notebook    | [53183984c3](https://linux-hardware.org/?probe=53183984c3) | Feb 14, 2021 |
| Dell          | 04VF8V A01                  | Desktop     | [14d2de53c9](https://linux-hardware.org/?probe=14d2de53c9) | Feb 14, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [5b5df6dbfc](https://linux-hardware.org/?probe=5b5df6dbfc) | Feb 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [3792a88564](https://linux-hardware.org/?probe=3792a88564) | Feb 08, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [797c58c227](https://linux-hardware.org/?probe=797c58c227) | Feb 08, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [d844c4f50e](https://linux-hardware.org/?probe=d844c4f50e) | Feb 05, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [5c23d11a52](https://linux-hardware.org/?probe=5c23d11a52) | Feb 05, 2021 |
| Lenovo        | Unknown                     | Convertible | [1dad570af9](https://linux-hardware.org/?probe=1dad570af9) | Feb 04, 2021 |
| HUAWEI        | SP1PGUM M1020               | Desktop     | [bd05c84564](https://linux-hardware.org/?probe=bd05c84564) | Feb 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d538017b75](https://linux-hardware.org/?probe=d538017b75) | Feb 04, 2021 |
| HP            | 81C6 MVB 0C                 | Server      | [279b8964e5](https://linux-hardware.org/?probe=279b8964e5) | Feb 03, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [1ed34422ce](https://linux-hardware.org/?probe=1ed34422ce) | Feb 02, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [02cd7a5160](https://linux-hardware.org/?probe=02cd7a5160) | Feb 02, 2021 |
| HUAWEI        | NBLL-WXX9                   | Notebook    | [b8558ad233](https://linux-hardware.org/?probe=b8558ad233) | Feb 02, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [c0cd6afd03](https://linux-hardware.org/?probe=c0cd6afd03) | Feb 02, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [2135ddb8dd](https://linux-hardware.org/?probe=2135ddb8dd) | Feb 02, 2021 |
| Dell          | 06JWJY A00                  | Desktop     | [1f2099e9d3](https://linux-hardware.org/?probe=1f2099e9d3) | Feb 02, 2021 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [8db56c19da](https://linux-hardware.org/?probe=8db56c19da) | Feb 02, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [5b274af228](https://linux-hardware.org/?probe=5b274af228) | Feb 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [39c3dd1edd](https://linux-hardware.org/?probe=39c3dd1edd) | Feb 02, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [9c21c30887](https://linux-hardware.org/?probe=9c21c30887) | Jan 30, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [32ba9cc321](https://linux-hardware.org/?probe=32ba9cc321) | Jan 29, 2021 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [35d97e2d21](https://linux-hardware.org/?probe=35d97e2d21) | Jan 28, 2021 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [5e7f5ea64a](https://linux-hardware.org/?probe=5e7f5ea64a) | Jan 28, 2021 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [81aa504e98](https://linux-hardware.org/?probe=81aa504e98) | Jan 28, 2021 |
| Dell          | 0CYTN6 A00                  | All in one  | [48d68a1579](https://linux-hardware.org/?probe=48d68a1579) | Jan 28, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [11db0c5d50](https://linux-hardware.org/?probe=11db0c5d50) | Jan 27, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [a7106e3642](https://linux-hardware.org/?probe=a7106e3642) | Jan 27, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [a1c263681f](https://linux-hardware.org/?probe=a1c263681f) | Jan 26, 2021 |
| ASUSTek       | PRIME H310M-F R2.0          | Desktop     | [3c4d584c27](https://linux-hardware.org/?probe=3c4d584c27) | Jan 26, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [f888388942](https://linux-hardware.org/?probe=f888388942) | Jan 23, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | Notebook    | [583f0d9ea2](https://linux-hardware.org/?probe=583f0d9ea2) | Jan 22, 2021 |
| Dell          | 0CYTN6 A00                  | All in one  | [e77cf82db6](https://linux-hardware.org/?probe=e77cf82db6) | Jan 21, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [1b100a591d](https://linux-hardware.org/?probe=1b100a591d) | Jan 19, 2021 |
| Dell          | Precision 5750              | Notebook    | [11a4cc2ef1](https://linux-hardware.org/?probe=11a4cc2ef1) | Jan 19, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [66efbfed55](https://linux-hardware.org/?probe=66efbfed55) | Jan 19, 2021 |
| Lenovo        | 317E SDK0L77767 WIN 3423... | Desktop     | [6e82572f07](https://linux-hardware.org/?probe=6e82572f07) | Jan 17, 2021 |
| Lenovo        | IdeaPad 320C-15IKB 81FU     | Notebook    | [32af8085e3](https://linux-hardware.org/?probe=32af8085e3) | Jan 15, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [edbfbb65b8](https://linux-hardware.org/?probe=edbfbb65b8) | Jan 15, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [1e5e57866d](https://linux-hardware.org/?probe=1e5e57866d) | Jan 14, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [4149fbf824](https://linux-hardware.org/?probe=4149fbf824) | Jan 14, 2021 |
| Lenovo        | Unknown                     | Notebook    | [38c41d5178](https://linux-hardware.org/?probe=38c41d5178) | Jan 13, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [ca1391c20d](https://linux-hardware.org/?probe=ca1391c20d) | Jan 13, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [1a4ee1ce22](https://linux-hardware.org/?probe=1a4ee1ce22) | Jan 13, 2021 |
| HP            | ZHAN 66 Pro 15 G3           | Notebook    | [309b0b4383](https://linux-hardware.org/?probe=309b0b4383) | Jan 12, 2021 |
| HP            | ProBook 6565b               | Notebook    | [517e898344](https://linux-hardware.org/?probe=517e898344) | Jan 12, 2021 |
| Lenovo        | 3107 NOK                    | Desktop     | [902ea74b31](https://linux-hardware.org/?probe=902ea74b31) | Jan 08, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [8b678d540d](https://linux-hardware.org/?probe=8b678d540d) | Jan 06, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [95eb2199fd](https://linux-hardware.org/?probe=95eb2199fd) | Jan 06, 2021 |
| Dell          | G3 3500                     | Notebook    | [584259b642](https://linux-hardware.org/?probe=584259b642) | Jan 02, 2021 |
| Lenovo        | Unknown                     | Notebook    | [bfa46b3e89](https://linux-hardware.org/?probe=bfa46b3e89) | Jan 01, 2021 |
| Google        | Zako                        | Desktop     | [d8df4eefd6](https://linux-hardware.org/?probe=d8df4eefd6) | Jan 01, 2021 |
| Dell          | G3 3579                     | Notebook    | [200c758b4b](https://linux-hardware.org/?probe=200c758b4b) | Jan 01, 2021 |
| Google        | Zako                        | Desktop     | [6bedd150e9](https://linux-hardware.org/?probe=6bedd150e9) | Jan 01, 2021 |
| HP            | 82A4                        | Desktop     | [bf686ef745](https://linux-hardware.org/?probe=bf686ef745) | Jan 01, 2021 |
| ASUSTek       | F81Se                       | Notebook    | [78420c272f](https://linux-hardware.org/?probe=78420c272f) | Dec 30, 2020 |
| ASUSTek       | F81Se                       | Notebook    | [f88933df38](https://linux-hardware.org/?probe=f88933df38) | Dec 30, 2020 |
| Lenovo        | G580 20150                  | Notebook    | [3e777432b1](https://linux-hardware.org/?probe=3e777432b1) | Dec 29, 2020 |
| Lenovo        | Unknown                     | Notebook    | [d789a34be2](https://linux-hardware.org/?probe=d789a34be2) | Dec 29, 2020 |
| Lenovo        | Unknown                     | Notebook    | [9ea48b71d6](https://linux-hardware.org/?probe=9ea48b71d6) | Dec 29, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [258a4745bf](https://linux-hardware.org/?probe=258a4745bf) | Dec 29, 2020 |
| Timi          | RedmiBook 14 II             | Notebook    | [6d6ce6a47a](https://linux-hardware.org/?probe=6d6ce6a47a) | Dec 29, 2020 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [c9a2d0d9e0](https://linux-hardware.org/?probe=c9a2d0d9e0) | Dec 28, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [dc8521e74c](https://linux-hardware.org/?probe=dc8521e74c) | Dec 28, 2020 |
| Lenovo        | 1.0                         | Desktop     | [897523f5fd](https://linux-hardware.org/?probe=897523f5fd) | Dec 27, 2020 |
| Lenovo        | 1.0                         | Desktop     | [53a763dc24](https://linux-hardware.org/?probe=53a763dc24) | Dec 27, 2020 |
| ASUSTek       | F81Se                       | Notebook    | [f33f999200](https://linux-hardware.org/?probe=f33f999200) | Dec 26, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [fd025ae38b](https://linux-hardware.org/?probe=fd025ae38b) | Dec 23, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a141f2ed51](https://linux-hardware.org/?probe=a141f2ed51) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | Notebook    | [0b958b270d](https://linux-hardware.org/?probe=0b958b270d) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | Notebook    | [94d64e448f](https://linux-hardware.org/?probe=94d64e448f) | Dec 21, 2020 |
| Lenovo        | MIIX 520-12IKB 20M4         | Tablet      | [f78d607b1f](https://linux-hardware.org/?probe=f78d607b1f) | Dec 18, 2020 |
| HASEE Comp... | PF4WN2F                     | Notebook    | [9855617493](https://linux-hardware.org/?probe=9855617493) | Dec 15, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [224c36cf4d](https://linux-hardware.org/?probe=224c36cf4d) | Dec 15, 2020 |
| ASRock        | Z170 Gaming K4              | Desktop     | [a246612b17](https://linux-hardware.org/?probe=a246612b17) | Dec 13, 2020 |
| Lenovo        | ThinkPad X230 2325DV4       | Notebook    | [03eaed4dcb](https://linux-hardware.org/?probe=03eaed4dcb) | Dec 11, 2020 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [0c0911cd7b](https://linux-hardware.org/?probe=0c0911cd7b) | Dec 11, 2020 |
| GPD           | P2 MAX                      | Notebook    | [f6249e6387](https://linux-hardware.org/?probe=f6249e6387) | Dec 11, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [87cfa2982d](https://linux-hardware.org/?probe=87cfa2982d) | Dec 09, 2020 |
| Unknown       | Unknown                     | Notebook    | [8b7c746735](https://linux-hardware.org/?probe=8b7c746735) | Dec 08, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [b20c8c639e](https://linux-hardware.org/?probe=b20c8c639e) | Dec 08, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [290c53b26c](https://linux-hardware.org/?probe=290c53b26c) | Dec 08, 2020 |
| HUAWEI        | Kunpeng Desktop             | Desktop     | [cbd268b858](https://linux-hardware.org/?probe=cbd268b858) | Dec 04, 2020 |
| HUAWEI        | Kunpeng Desktop             | Desktop     | [da163e34c7](https://linux-hardware.org/?probe=da163e34c7) | Dec 04, 2020 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [7eb641e51d](https://linux-hardware.org/?probe=7eb641e51d) | Dec 01, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [216a0f765e](https://linux-hardware.org/?probe=216a0f765e) | Dec 01, 2020 |
| Gigabyte      | B250-D3A-CF                 | Desktop     | [907d35d953](https://linux-hardware.org/?probe=907d35d953) | Nov 30, 2020 |
| Lenovo        | ThinkPad P53 20QQA004CD     | Notebook    | [a9e2438f51](https://linux-hardware.org/?probe=a9e2438f51) | Nov 28, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [d1c0a8df13](https://linux-hardware.org/?probe=d1c0a8df13) | Nov 23, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [7975ba3888](https://linux-hardware.org/?probe=7975ba3888) | Nov 23, 2020 |
| Unknown       | Unknown                     | Desktop     | [d58e8b793e](https://linux-hardware.org/?probe=d58e8b793e) | Nov 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [c0e8909067](https://linux-hardware.org/?probe=c0e8909067) | Nov 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [c0d7c657b1](https://linux-hardware.org/?probe=c0d7c657b1) | Nov 22, 2020 |
| Gigabyte      | 970-GAMING                  | Desktop     | [44f42f7676](https://linux-hardware.org/?probe=44f42f7676) | Nov 21, 2020 |
| Lenovo        | Legion Y9000X 2020 81TH     | Notebook    | [2aa8c29fb4](https://linux-hardware.org/?probe=2aa8c29fb4) | Nov 21, 2020 |
| Dell          | 028PX1 A00                  | Server      | [00fda23065](https://linux-hardware.org/?probe=00fda23065) | Nov 20, 2020 |
| Colorful T... | C.H110M-K PRO V21           | Desktop     | [c8211ace73](https://linux-hardware.org/?probe=c8211ace73) | Nov 20, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [73c5a8bd67](https://linux-hardware.org/?probe=73c5a8bd67) | Nov 19, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [23418fe6cc](https://linux-hardware.org/?probe=23418fe6cc) | Nov 19, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [0999a52054](https://linux-hardware.org/?probe=0999a52054) | Nov 18, 2020 |
| Apple         | MacBookPro11,3              | Notebook    | [a01b45c371](https://linux-hardware.org/?probe=a01b45c371) | Nov 17, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [37dbdd4b85](https://linux-hardware.org/?probe=37dbdd4b85) | Nov 16, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [5182cf15a5](https://linux-hardware.org/?probe=5182cf15a5) | Nov 16, 2020 |
| Acer          | Aspire V5-571G              | Notebook    | [49707be15c](https://linux-hardware.org/?probe=49707be15c) | Nov 16, 2020 |
| Lenovo        | Y430P 20435                 | Notebook    | [2ee9b87c44](https://linux-hardware.org/?probe=2ee9b87c44) | Nov 15, 2020 |
| HASEE Comp... | QTH6                        | Notebook    | [a2a60413b1](https://linux-hardware.org/?probe=a2a60413b1) | Nov 13, 2020 |
| HASEE Comp... | QL9S                        | Notebook    | [a1bd3a60dc](https://linux-hardware.org/?probe=a1bd3a60dc) | Nov 13, 2020 |
| HASEE Comp... | QL9S                        | Notebook    | [799ba586bd](https://linux-hardware.org/?probe=799ba586bd) | Nov 13, 2020 |
| Dell          | Inspiron 3576               | Notebook    | [d68d6cdf18](https://linux-hardware.org/?probe=d68d6cdf18) | Nov 13, 2020 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [069182cff6](https://linux-hardware.org/?probe=069182cff6) | Nov 12, 2020 |
| Dell          | Latitude 5490               | Notebook    | [894bd38b38](https://linux-hardware.org/?probe=894bd38b38) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [28c7cf4458](https://linux-hardware.org/?probe=28c7cf4458) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [b4fbf1f2e6](https://linux-hardware.org/?probe=b4fbf1f2e6) | Nov 11, 2020 |
| Dell          | Precision 7510              | Notebook    | [5cb1751259](https://linux-hardware.org/?probe=5cb1751259) | Nov 11, 2020 |
| Sony          | VPCZ115FC                   | Notebook    | [7e886b81d0](https://linux-hardware.org/?probe=7e886b81d0) | Nov 09, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c9dbcdd42b](https://linux-hardware.org/?probe=c9dbcdd42b) | Nov 09, 2020 |
| Lenovo        | Unknown                     | Notebook    | [d689908218](https://linux-hardware.org/?probe=d689908218) | Nov 08, 2020 |
| Lenovo        | ThinkPad X250 20CLA272CD    | Notebook    | [a9075402e1](https://linux-hardware.org/?probe=a9075402e1) | Nov 08, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [ed3c250112](https://linux-hardware.org/?probe=ed3c250112) | Nov 03, 2020 |
| HP            | 8455                        | Desktop     | [8fbf07649a](https://linux-hardware.org/?probe=8fbf07649a) | Nov 03, 2020 |
| Lenovo        | Legion R7000P2020H 82GR     | Notebook    | [907de62181](https://linux-hardware.org/?probe=907de62181) | Oct 31, 2020 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [105a5c3241](https://linux-hardware.org/?probe=105a5c3241) | Oct 31, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [d69c97a2c3](https://linux-hardware.org/?probe=d69c97a2c3) | Oct 30, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [1affea93fd](https://linux-hardware.org/?probe=1affea93fd) | Oct 27, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [e930aac9b6](https://linux-hardware.org/?probe=e930aac9b6) | Oct 27, 2020 |
| HUAWEI        | KPL-W0X                     | Notebook    | [cf48a4f7b0](https://linux-hardware.org/?probe=cf48a4f7b0) | Oct 26, 2020 |
| Intel         | SKYBAY                      | Desktop     | [ebc35582c8](https://linux-hardware.org/?probe=ebc35582c8) | Oct 23, 2020 |
| Intel         | SKYBAY                      | Desktop     | [ce89df6806](https://linux-hardware.org/?probe=ce89df6806) | Oct 23, 2020 |
| Lenovo        | M5400 20281                 | Notebook    | [08fa33ca8e](https://linux-hardware.org/?probe=08fa33ca8e) | Oct 22, 2020 |
| HP            | ZHAN 66 Pro 15 G2           | Notebook    | [adb6a00cd2](https://linux-hardware.org/?probe=adb6a00cd2) | Oct 22, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [f101c9246f](https://linux-hardware.org/?probe=f101c9246f) | Oct 17, 2020 |
| Dell          | G3 3500                     | Notebook    | [5cb1ce307e](https://linux-hardware.org/?probe=5cb1ce307e) | Oct 16, 2020 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [6faf6514f5](https://linux-hardware.org/?probe=6faf6514f5) | Oct 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [5af00a6f4a](https://linux-hardware.org/?probe=5af00a6f4a) | Oct 13, 2020 |
| Unknown       | Unknown                     | Notebook    | [b4ead91a12](https://linux-hardware.org/?probe=b4ead91a12) | Oct 05, 2020 |
| HP            | ZHAN 66 Pro 14 G2           | Notebook    | [b690ea4e11](https://linux-hardware.org/?probe=b690ea4e11) | Oct 03, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [88e5775f0f](https://linux-hardware.org/?probe=88e5775f0f) | Oct 02, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2972557e3e](https://linux-hardware.org/?probe=2972557e3e) | Oct 02, 2020 |
| Acidanther... | Mac-DB15BD556843C820 iMa... | All in one  | [ca7807180d](https://linux-hardware.org/?probe=ca7807180d) | Sep 30, 2020 |
| Lenovo        | ThinkPad E580 20KS002BCD    | Notebook    | [e89a66365d](https://linux-hardware.org/?probe=e89a66365d) | Sep 29, 2020 |
| Lenovo        | M5400 20281                 | Notebook    | [839f6b0ddc](https://linux-hardware.org/?probe=839f6b0ddc) | Sep 28, 2020 |
| Dell          | Inspiron 7720               | Notebook    | [cafa640700](https://linux-hardware.org/?probe=cafa640700) | Sep 27, 2020 |
| Gigabyte      | B85M-D2V                    | Desktop     | [3393bfd809](https://linux-hardware.org/?probe=3393bfd809) | Sep 25, 2020 |
| Gigabyte      | B85M-D2V                    | Desktop     | [4ef60f3d1d](https://linux-hardware.org/?probe=4ef60f3d1d) | Sep 25, 2020 |
| ASRock        | FM2A85M-DG3                 | Desktop     | [8516ddc869](https://linux-hardware.org/?probe=8516ddc869) | Sep 24, 2020 |
| HUAWEI        | KPL-W0X                     | Notebook    | [b53090f7ec](https://linux-hardware.org/?probe=b53090f7ec) | Sep 20, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [814cb96243](https://linux-hardware.org/?probe=814cb96243) | Sep 19, 2020 |
| HP            | ProBook 6565b               | Notebook    | [92c570e1f9](https://linux-hardware.org/?probe=92c570e1f9) | Sep 18, 2020 |
| Dell          | 04WYPY A05                  | Server      | [4c88b2e09b](https://linux-hardware.org/?probe=4c88b2e09b) | Sep 18, 2020 |
| Dell          | 04WYPY A05                  | Server      | [76edc44044](https://linux-hardware.org/?probe=76edc44044) | Sep 18, 2020 |
| Lenovo        | ThinkPad T450s 20BX002GH... | Notebook    | [2e10a094c7](https://linux-hardware.org/?probe=2e10a094c7) | Sep 17, 2020 |
| Lenovo        | Legion R7000P2020H 82GR     | Notebook    | [dae1221cfd](https://linux-hardware.org/?probe=dae1221cfd) | Sep 16, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [55bf2ea24a](https://linux-hardware.org/?probe=55bf2ea24a) | Sep 16, 2020 |
| AEWIN         | SCB-1711A                   | Desktop     | [2d8dbb0d3a](https://linux-hardware.org/?probe=2d8dbb0d3a) | Sep 09, 2020 |
| Dell          | Precision 5510              | Notebook    | [f4f4ec51bf](https://linux-hardware.org/?probe=f4f4ec51bf) | Sep 09, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [d8db035524](https://linux-hardware.org/?probe=d8db035524) | Sep 05, 2020 |
| RBQ           | RongBotQiu X79.810          | Desktop     | [71e839ea6f](https://linux-hardware.org/?probe=71e839ea6f) | Sep 03, 2020 |
| Lenovo        | 36EF SDK0L77767 WIN 3423... | Desktop     | [a01c93c314](https://linux-hardware.org/?probe=a01c93c314) | Sep 01, 2020 |
| Lenovo        | IdeaPad S410 20301          | Notebook    | [b4410055a6](https://linux-hardware.org/?probe=b4410055a6) | Aug 31, 2020 |
| Lenovo        | Unknown                     | Notebook    | [7dad252a0d](https://linux-hardware.org/?probe=7dad252a0d) | Aug 31, 2020 |
| Lenovo        | 36EF SDK0L77767 WIN 3423... | Desktop     | [2800d63edf](https://linux-hardware.org/?probe=2800d63edf) | Aug 30, 2020 |
| Intel         | H81U                        | Notebook    | [9dfe47a2b3](https://linux-hardware.org/?probe=9dfe47a2b3) | Aug 26, 2020 |
| Intel         | H81U                        | Notebook    | [65f88785ff](https://linux-hardware.org/?probe=65f88785ff) | Aug 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f0150526b6](https://linux-hardware.org/?probe=f0150526b6) | Aug 24, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [d53a271c2a](https://linux-hardware.org/?probe=d53a271c2a) | Aug 23, 2020 |
| Lenovo        | Unknown                     | Notebook    | [7ba1cf5064](https://linux-hardware.org/?probe=7ba1cf5064) | Aug 19, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [fb2ef05779](https://linux-hardware.org/?probe=fb2ef05779) | Aug 17, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [c51c0d5538](https://linux-hardware.org/?probe=c51c0d5538) | Aug 15, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [f0d9b71d6d](https://linux-hardware.org/?probe=f0d9b71d6d) | Aug 15, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2b3d080fd4](https://linux-hardware.org/?probe=2b3d080fd4) | Aug 14, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [e32815911a](https://linux-hardware.org/?probe=e32815911a) | Aug 11, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [36a4789e67](https://linux-hardware.org/?probe=36a4789e67) | Aug 10, 2020 |
| HASEE Comp... | GJ5CN64                     | Notebook    | [629359f065](https://linux-hardware.org/?probe=629359f065) | Aug 07, 2020 |
| Sony          | VPCYB35JC                   | Notebook    | [7872a30f96](https://linux-hardware.org/?probe=7872a30f96) | Aug 06, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [b948b0ffe7](https://linux-hardware.org/?probe=b948b0ffe7) | Aug 03, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [0f826bb295](https://linux-hardware.org/?probe=0f826bb295) | Aug 03, 2020 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [c84ef6859b](https://linux-hardware.org/?probe=c84ef6859b) | Aug 03, 2020 |
| Lenovo        | Unknown                     | Notebook    | [570aec33e6](https://linux-hardware.org/?probe=570aec33e6) | Aug 02, 2020 |
| Lenovo        | Unknown                     | Notebook    | [cdabfce7b7](https://linux-hardware.org/?probe=cdabfce7b7) | Aug 02, 2020 |
| TR            | ThundeRobot                 | Notebook    | [c22560abf3](https://linux-hardware.org/?probe=c22560abf3) | Aug 02, 2020 |
| Acer          | Aspire 4560                 | Notebook    | [aacc9842e1](https://linux-hardware.org/?probe=aacc9842e1) | Aug 01, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [0defe9b34c](https://linux-hardware.org/?probe=0defe9b34c) | Aug 01, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [44e1ce47dc](https://linux-hardware.org/?probe=44e1ce47dc) | Aug 01, 2020 |
| Lenovo        | ThinkPad W550s 20E2000CM... | Notebook    | [fae2775795](https://linux-hardware.org/?probe=fae2775795) | Jul 30, 2020 |
| Teclast       | tPAD                        | Notebook    | [2fdb26f348](https://linux-hardware.org/?probe=2fdb26f348) | Jul 29, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| Lenovo        | NOK                         | Desktop     | [99cea2b8c1](https://linux-hardware.org/?probe=99cea2b8c1) | Jul 22, 2020 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [cb12b1101c](https://linux-hardware.org/?probe=cb12b1101c) | Jul 20, 2020 |
| Lenovo        | Unknown                     | Desktop     | [9e428d8ef9](https://linux-hardware.org/?probe=9e428d8ef9) | Jul 16, 2020 |
| MSI           | 880GM-E41                   | Desktop     | [620e8dbc2c](https://linux-hardware.org/?probe=620e8dbc2c) | Jul 13, 2020 |
| Gigabyte      | AB350M-DS2-CF               | Desktop     | [014b2718ae](https://linux-hardware.org/?probe=014b2718ae) | Jul 13, 2020 |
| Gigabyte      | AB350M-DS2-CF               | Desktop     | [6ea3c86837](https://linux-hardware.org/?probe=6ea3c86837) | Jul 13, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a577a84015](https://linux-hardware.org/?probe=a577a84015) | Jul 12, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [cc4958e2d1](https://linux-hardware.org/?probe=cc4958e2d1) | Jul 12, 2020 |
| HP            | ZHAN 66 Pro G1              | Notebook    | [a2da22d929](https://linux-hardware.org/?probe=a2da22d929) | Jul 11, 2020 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [ce5f57a42d](https://linux-hardware.org/?probe=ce5f57a42d) | Jul 09, 2020 |
| Lenovo        | ThinkPad P53 20QQA01JCD     | Notebook    | [38faa849ff](https://linux-hardware.org/?probe=38faa849ff) | Jul 08, 2020 |
| Unknown       | Unknown                     | Phone       | [2f52d0b34d](https://linux-hardware.org/?probe=2f52d0b34d) | Jul 07, 2020 |
| Lenovo        | ThinkPad X395 20NL000YCD    | Notebook    | [8ce881d65e](https://linux-hardware.org/?probe=8ce881d65e) | Jul 06, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [2a05830be5](https://linux-hardware.org/?probe=2a05830be5) | Jul 05, 2020 |
| Intel         | H81C                        | Desktop     | [54732275c2](https://linux-hardware.org/?probe=54732275c2) | Jul 04, 2020 |
| Lenovo        | IdeaPad Y460                | Notebook    | [eec296f86e](https://linux-hardware.org/?probe=eec296f86e) | Jul 04, 2020 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [6d2e4339ac](https://linux-hardware.org/?probe=6d2e4339ac) | Jul 02, 2020 |
| Dell          | 0PYVT1 A03                  | Server      | [b7f3606e31](https://linux-hardware.org/?probe=b7f3606e31) | Jun 30, 2020 |
| HP            | ProBook 6565b               | Notebook    | [19bad7a13f](https://linux-hardware.org/?probe=19bad7a13f) | Jun 30, 2020 |
| HP            | ProBook 6565b               | Notebook    | [3a81652253](https://linux-hardware.org/?probe=3a81652253) | Jun 30, 2020 |
| Dell          | Precision 5520              | Notebook    | [c2407629ef](https://linux-hardware.org/?probe=c2407629ef) | Jun 30, 2020 |
| Dell          | XPS 15 9500                 | Notebook    | [b0029da795](https://linux-hardware.org/?probe=b0029da795) | Jun 27, 2020 |
| IP3 Tech      | AB4                         | Mini pc     | [c242dec3cc](https://linux-hardware.org/?probe=c242dec3cc) | Jun 27, 2020 |
| IP3 Tech      | AB4                         | Mini pc     | [c49176954b](https://linux-hardware.org/?probe=c49176954b) | Jun 27, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [670706063d](https://linux-hardware.org/?probe=670706063d) | Jun 25, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [176c1bcb0a](https://linux-hardware.org/?probe=176c1bcb0a) | Jun 24, 2020 |
| Supermicro    | X11DPG-QTA                  | Server      | [f9d0b2bc99](https://linux-hardware.org/?probe=f9d0b2bc99) | Jun 22, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [2a82160500](https://linux-hardware.org/?probe=2a82160500) | Jun 19, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [b5360affff](https://linux-hardware.org/?probe=b5360affff) | Jun 18, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [f532f4f740](https://linux-hardware.org/?probe=f532f4f740) | Jun 17, 2020 |
| Qualcomm T... | MSM8992 MTP (DT)            | Phone       | [3549318c8d](https://linux-hardware.org/?probe=3549318c8d) | Jun 16, 2020 |
| HP            | ENVY Laptop 13-ah1xxx       | Notebook    | [b9c34fddc7](https://linux-hardware.org/?probe=b9c34fddc7) | Jun 15, 2020 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [0c9dfeb831](https://linux-hardware.org/?probe=0c9dfeb831) | Jun 15, 2020 |
| AVITA         | NS14A8                      | Notebook    | [6148b267ec](https://linux-hardware.org/?probe=6148b267ec) | Jun 13, 2020 |
| HP            | ENVY Laptop 13-ah1xxx       | Notebook    | [3fa545e765](https://linux-hardware.org/?probe=3fa545e765) | Jun 12, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [443ec260d7](https://linux-hardware.org/?probe=443ec260d7) | Jun 12, 2020 |
| HP            | ENVY Laptop 13-ah1xxx       | Notebook    | [ed5af09293](https://linux-hardware.org/?probe=ed5af09293) | Jun 09, 2020 |
| MSI           | Z370-OC PRO                 | Desktop     | [a37abc19ef](https://linux-hardware.org/?probe=a37abc19ef) | Jun 08, 2020 |
| Lenovo        | Y430P 20435                 | Notebook    | [1a02a65fe2](https://linux-hardware.org/?probe=1a02a65fe2) | Jun 07, 2020 |
| HUAWEI        | KPR-WX9                     | Notebook    | [383ede6256](https://linux-hardware.org/?probe=383ede6256) | Jun 06, 2020 |
| Lenovo        | XiaoXinAir-14IIL 2020 81... | Notebook    | [761aaee925](https://linux-hardware.org/?probe=761aaee925) | Jun 06, 2020 |
| ASUSTek       | Z97-PRO                     | Desktop     | [c534bc4bc6](https://linux-hardware.org/?probe=c534bc4bc6) | Jun 04, 2020 |
| Lenovo        | ThinkPad W500 4063RT3       | Notebook    | [1263b95cf5](https://linux-hardware.org/?probe=1263b95cf5) | Jun 01, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [e4105f6fc1](https://linux-hardware.org/?probe=e4105f6fc1) | May 31, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [29eb8f828b](https://linux-hardware.org/?probe=29eb8f828b) | May 30, 2020 |
| Lenovo        | ThinkPad T470 20HDA01MCD    | Notebook    | [bd45efa3fb](https://linux-hardware.org/?probe=bd45efa3fb) | May 29, 2020 |
| Acer          | Aspire E5-553G              | Notebook    | [334a330b2b](https://linux-hardware.org/?probe=334a330b2b) | May 29, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1ef79c4312](https://linux-hardware.org/?probe=1ef79c4312) | May 27, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [49337f4321](https://linux-hardware.org/?probe=49337f4321) | May 27, 2020 |
| ASUSTek       | T100TAF                     | Notebook    | [6d2999ebb1](https://linux-hardware.org/?probe=6d2999ebb1) | May 26, 2020 |
| Sony          | SVF15N17DJS                 | Notebook    | [da222707b2](https://linux-hardware.org/?probe=da222707b2) | May 26, 2020 |
| HP            | 82A1                        | Desktop     | [ddd727fd22](https://linux-hardware.org/?probe=ddd727fd22) | May 25, 2020 |
| HP            | 807D                        | Desktop     | [0523c549d5](https://linux-hardware.org/?probe=0523c549d5) | May 25, 2020 |
| LG Electro... | 13Z990-V.AA53C              | Notebook    | [2674ee06bd](https://linux-hardware.org/?probe=2674ee06bd) | May 24, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [220e504029](https://linux-hardware.org/?probe=220e504029) | May 23, 2020 |
| HP            | 807D                        | Desktop     | [d82ca940de](https://linux-hardware.org/?probe=d82ca940de) | May 22, 2020 |
| Lenovo        | Legion Y9000X 2020 81TH     | Notebook    | [bd60f2ac06](https://linux-hardware.org/?probe=bd60f2ac06) | May 22, 2020 |
| Lenovo        | ThinkPad X220 4287A11       | Notebook    | [ac9926d32d](https://linux-hardware.org/?probe=ac9926d32d) | May 19, 2020 |
| Dell          | Inspiron 7537               | Notebook    | [5e800e551c](https://linux-hardware.org/?probe=5e800e551c) | May 18, 2020 |
| Unknown       | Unknown                     | Notebook    | [e70916ddfb](https://linux-hardware.org/?probe=e70916ddfb) | May 18, 2020 |
| Biostar       | H110MLC                     | Desktop     | [70e9170fa4](https://linux-hardware.org/?probe=70e9170fa4) | May 15, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [ffd9df1914](https://linux-hardware.org/?probe=ffd9df1914) | May 14, 2020 |
| Dell          | 09PR9H A02                  | Desktop     | [a0f6d2eac4](https://linux-hardware.org/?probe=a0f6d2eac4) | May 11, 2020 |
| ASUSTek       | X541UJ                      | Notebook    | [d02c3d787d](https://linux-hardware.org/?probe=d02c3d787d) | May 11, 2020 |
| ASUSTek       | X541UJ                      | Notebook    | [7f3ef9343e](https://linux-hardware.org/?probe=7f3ef9343e) | May 11, 2020 |
| ASUSTek       | X541UJ                      | Notebook    | [b9be90e66e](https://linux-hardware.org/?probe=b9be90e66e) | May 11, 2020 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | Notebook    | [8d8b69ef00](https://linux-hardware.org/?probe=8d8b69ef00) | May 10, 2020 |
| ASUSTek       | Z97-C                       | Desktop     | [6eb7ec99eb](https://linux-hardware.org/?probe=6eb7ec99eb) | May 08, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b89e15e7c5](https://linux-hardware.org/?probe=b89e15e7c5) | May 07, 2020 |
| Dell          | Latitude E6220              | Notebook    | [a4db1d31a5](https://linux-hardware.org/?probe=a4db1d31a5) | May 05, 2020 |
| Dell          | Latitude E6220              | Notebook    | [c0152a3b02](https://linux-hardware.org/?probe=c0152a3b02) | May 05, 2020 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [a244f111f8](https://linux-hardware.org/?probe=a244f111f8) | May 05, 2020 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [69210022d8](https://linux-hardware.org/?probe=69210022d8) | May 05, 2020 |
| Lenovo        | ThinkPad X201s 5397G4C      | Notebook    | [e37ac78744](https://linux-hardware.org/?probe=e37ac78744) | May 05, 2020 |
| Acer          | Aspire E1-471G              | Notebook    | [6ebcffa76b](https://linux-hardware.org/?probe=6ebcffa76b) | May 04, 2020 |
| Lenovo        | ZHAOYANG E42-80 80T8        | Notebook    | [58d0c0c1af](https://linux-hardware.org/?probe=58d0c0c1af) | May 03, 2020 |
| Dell          | 0VRC38 A06                  | Server      | [9d14faedef](https://linux-hardware.org/?probe=9d14faedef) | May 02, 2020 |
| Dell          | 0VRC38 A06                  | Server      | [961a6e8ebe](https://linux-hardware.org/?probe=961a6e8ebe) | May 02, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4a3b758c10](https://linux-hardware.org/?probe=4a3b758c10) | May 02, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [729a079629](https://linux-hardware.org/?probe=729a079629) | Apr 28, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6e5f544240](https://linux-hardware.org/?probe=6e5f544240) | Apr 28, 2020 |
| Gigabyte      | F2A88XM-DS2-TE              | Desktop     | [2b96fc655b](https://linux-hardware.org/?probe=2b96fc655b) | Apr 28, 2020 |
| Gigabyte      | F2A88XM-DS2-TE              | Desktop     | [c53b21972a](https://linux-hardware.org/?probe=c53b21972a) | Apr 28, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [1339b47680](https://linux-hardware.org/?probe=1339b47680) | Apr 22, 2020 |
| Samsung       | R440                        | Notebook    | [2b527c692e](https://linux-hardware.org/?probe=2b527c692e) | Apr 21, 2020 |
| Samsung       | R440                        | Notebook    | [7c20fb1986](https://linux-hardware.org/?probe=7c20fb1986) | Apr 21, 2020 |
| Dell          | 042P49 A02                  | Desktop     | [bd064eace3](https://linux-hardware.org/?probe=bd064eace3) | Apr 21, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [baed6b33b5](https://linux-hardware.org/?probe=baed6b33b5) | Apr 20, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [38be8071f2](https://linux-hardware.org/?probe=38be8071f2) | Apr 19, 2020 |
| Lenovo        | Tiger Hill                  | Desktop     | [7f92e05b46](https://linux-hardware.org/?probe=7f92e05b46) | Apr 14, 2020 |
| Lenovo        | Legion Y9000X 2020 81TH     | Notebook    | [bc52c2ff9a](https://linux-hardware.org/?probe=bc52c2ff9a) | Apr 12, 2020 |
| Lenovo        | ThinkPad X220 4287A11       | Notebook    | [97e8cae9bb](https://linux-hardware.org/?probe=97e8cae9bb) | Apr 11, 2020 |
| HP            | Laptop 14-bw0xx             | Notebook    | [50cfedd24a](https://linux-hardware.org/?probe=50cfedd24a) | Apr 11, 2020 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | Notebook    | [ca529580d5](https://linux-hardware.org/?probe=ca529580d5) | Apr 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2e5075d2e8](https://linux-hardware.org/?probe=2e5075d2e8) | Apr 10, 2020 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [4d780e5077](https://linux-hardware.org/?probe=4d780e5077) | Apr 09, 2020 |
| Insyde        | Braswell                    | Notebook    | [ad8f4d2408](https://linux-hardware.org/?probe=ad8f4d2408) | Apr 07, 2020 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | Notebook    | [e6963791cb](https://linux-hardware.org/?probe=e6963791cb) | Apr 07, 2020 |
| HP            | EliteBook 8770w             | Notebook    | [c8c1149b77](https://linux-hardware.org/?probe=c8c1149b77) | Apr 04, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | Notebook    | [a602b4a98e](https://linux-hardware.org/?probe=a602b4a98e) | Apr 02, 2020 |
| Dell          | 040DDP A01                  | Desktop     | [ab41c29212](https://linux-hardware.org/?probe=ab41c29212) | Mar 31, 2020 |
| Microsoft     | Surface Book                | Tablet      | [41b3cfd135](https://linux-hardware.org/?probe=41b3cfd135) | Mar 25, 2020 |
| ECS           | H61H2-TAIO                  | Desktop     | [e6f8d21b5a](https://linux-hardware.org/?probe=e6f8d21b5a) | Mar 24, 2020 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [dc892ce89f](https://linux-hardware.org/?probe=dc892ce89f) | Mar 22, 2020 |
| Lenovo        | ThinkPad X220 4290FP2       | Notebook    | [46bf7f136a](https://linux-hardware.org/?probe=46bf7f136a) | Mar 22, 2020 |
| Dell          | Latitude E7250              | Notebook    | [db8f980af7](https://linux-hardware.org/?probe=db8f980af7) | Mar 21, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [4629800e33](https://linux-hardware.org/?probe=4629800e33) | Mar 19, 2020 |
| Lenovo        | XiaoXin V4000 80MY          | Notebook    | [f84cb81dba](https://linux-hardware.org/?probe=f84cb81dba) | Mar 18, 2020 |
| MECHREVO      | X9Ti-R Series GK7CP0S       | Notebook    | [ee88c9e543](https://linux-hardware.org/?probe=ee88c9e543) | Mar 13, 2020 |
| MECHREVO      | X9Ti-R Series GK7CP0S       | Notebook    | [f65b70dee5](https://linux-hardware.org/?probe=f65b70dee5) | Mar 12, 2020 |
| Acer          | Aspire V5-552G              | Notebook    | [1e7e0572b2](https://linux-hardware.org/?probe=1e7e0572b2) | Mar 12, 2020 |
| Gigabyte      | B85-HD3                     | Desktop     | [fb4cdf6f1a](https://linux-hardware.org/?probe=fb4cdf6f1a) | Mar 09, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [b76f9f945c](https://linux-hardware.org/?probe=b76f9f945c) | Mar 07, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9946078bc6](https://linux-hardware.org/?probe=9946078bc6) | Mar 07, 2020 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | Notebook    | [005dfa63d7](https://linux-hardware.org/?probe=005dfa63d7) | Mar 07, 2020 |
| HP            | Pavilion dv6                | Notebook    | [f125c0e156](https://linux-hardware.org/?probe=f125c0e156) | Mar 05, 2020 |
| Acer          | Aspire VN7-792G             | Notebook    | [3924df2c92](https://linux-hardware.org/?probe=3924df2c92) | Feb 28, 2020 |
| ECS           | H61H2-TAIO                  | Desktop     | [6ee3574f22](https://linux-hardware.org/?probe=6ee3574f22) | Feb 26, 2020 |
| ECS           | H61H2-TAIO                  | Desktop     | [32a0959f61](https://linux-hardware.org/?probe=32a0959f61) | Feb 25, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [676d073b68](https://linux-hardware.org/?probe=676d073b68) | Feb 24, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [426bc40176](https://linux-hardware.org/?probe=426bc40176) | Feb 24, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [04ff15312c](https://linux-hardware.org/?probe=04ff15312c) | Feb 24, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [63d24474a4](https://linux-hardware.org/?probe=63d24474a4) | Feb 24, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [6f0a1ae634](https://linux-hardware.org/?probe=6f0a1ae634) | Feb 22, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c686b99849](https://linux-hardware.org/?probe=c686b99849) | Feb 20, 2020 |
| ASUSTek       | N82JQ                       | Notebook    | [f03777a2b9](https://linux-hardware.org/?probe=f03777a2b9) | Feb 20, 2020 |
| Lenovo        | XiaoXin Air 13IWL 81J8      | Notebook    | [4d3479c7df](https://linux-hardware.org/?probe=4d3479c7df) | Feb 19, 2020 |
| Unknown       | p6                          | Notebook    | [235b076f4f](https://linux-hardware.org/?probe=235b076f4f) | Feb 19, 2020 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [8cfec181a0](https://linux-hardware.org/?probe=8cfec181a0) | Feb 18, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [73afca4618](https://linux-hardware.org/?probe=73afca4618) | Feb 17, 2020 |
| Acer          | Aspire 4736Z                | Notebook    | [2b6edf8d9a](https://linux-hardware.org/?probe=2b6edf8d9a) | Feb 15, 2020 |
| Lenovo        | ThinkPad T440s 20ARS2H40... | Notebook    | [0f32bfa665](https://linux-hardware.org/?probe=0f32bfa665) | Feb 11, 2020 |
| Dell          | Precision 5510              | Notebook    | [bab9a0d0c8](https://linux-hardware.org/?probe=bab9a0d0c8) | Feb 11, 2020 |
| Dell          | Precision 5510              | Notebook    | [4c17778c81](https://linux-hardware.org/?probe=4c17778c81) | Feb 05, 2020 |
| Lenovo        | ZHAOYANG E40-80 80HR        | Notebook    | [78f39c1935](https://linux-hardware.org/?probe=78f39c1935) | Feb 05, 2020 |
| Timi          | TM1709                      | Notebook    | [ffc5e87668](https://linux-hardware.org/?probe=ffc5e87668) | Feb 03, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [03731a6e89](https://linux-hardware.org/?probe=03731a6e89) | Jan 28, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [81586acd13](https://linux-hardware.org/?probe=81586acd13) | Jan 27, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [a9cada02fe](https://linux-hardware.org/?probe=a9cada02fe) | Jan 27, 2020 |
| Toshiba       | Satellite L55-B             | Notebook    | [cbf62518f7](https://linux-hardware.org/?probe=cbf62518f7) | Jan 25, 2020 |
| Colorful T... | C.Q1900M PRO V20            | Desktop     | [17664b4797](https://linux-hardware.org/?probe=17664b4797) | Jan 25, 2020 |
| Colorful T... | C.Q1900M PRO V20            | Desktop     | [8bc2fe0d86](https://linux-hardware.org/?probe=8bc2fe0d86) | Jan 25, 2020 |
| ASUSTek       | ZenBook UX433FN_U4300FN     | Notebook    | [cb91151a43](https://linux-hardware.org/?probe=cb91151a43) | Jan 22, 2020 |
| ASUSTek       | ZenBook UX433FN_U4300FN     | Notebook    | [f3558727ea](https://linux-hardware.org/?probe=f3558727ea) | Jan 22, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [9f6e79326e](https://linux-hardware.org/?probe=9f6e79326e) | Jan 14, 2020 |
| Sony          | VGN-CR322H_P                | Notebook    | [459dd43900](https://linux-hardware.org/?probe=459dd43900) | Jan 11, 2020 |
| Sony          | VGN-CR322H_P                | Notebook    | [a131f14c28](https://linux-hardware.org/?probe=a131f14c28) | Jan 11, 2020 |
| MSI           | B450M MORTAR                | Desktop     | [eb4106d83f](https://linux-hardware.org/?probe=eb4106d83f) | Jan 10, 2020 |
| MSI           | GF72 8RE                    | Notebook    | [ff9ee83e94](https://linux-hardware.org/?probe=ff9ee83e94) | Jan 09, 2020 |
| Dell          | Inspiron 7560               | Notebook    | [262434461f](https://linux-hardware.org/?probe=262434461f) | Jan 08, 2020 |
| ASUSTek       | Z97-PRO                     | Desktop     | [e814486254](https://linux-hardware.org/?probe=e814486254) | Jan 07, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [34f134e5b0](https://linux-hardware.org/?probe=34f134e5b0) | Jan 06, 2020 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [df17ba12c1](https://linux-hardware.org/?probe=df17ba12c1) | Jan 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [95488c6be1](https://linux-hardware.org/?probe=95488c6be1) | Jan 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [925412ddcd](https://linux-hardware.org/?probe=925412ddcd) | Jan 02, 2020 |
| Lenovo        | ThinkPad T530 2429C54       | Notebook    | [e100864771](https://linux-hardware.org/?probe=e100864771) | Jan 02, 2020 |
| Timi          | TM1709                      | Notebook    | [3914d93846](https://linux-hardware.org/?probe=3914d93846) | Dec 29, 2019 |
| Intel         | MAHOBAY                     | Desktop     | [30a583066a](https://linux-hardware.org/?probe=30a583066a) | Dec 29, 2019 |
| HUAWEI        | WRT-WX9                     | Notebook    | [895ba48236](https://linux-hardware.org/?probe=895ba48236) | Dec 29, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [79fd5db054](https://linux-hardware.org/?probe=79fd5db054) | Dec 28, 2019 |
| MECHREVO      | Z2 Air Series GK5CP5X       | Notebook    | [9959b07810](https://linux-hardware.org/?probe=9959b07810) | Dec 28, 2019 |
| Dell          | Latitude 7300               | Notebook    | [f576ddf5dc](https://linux-hardware.org/?probe=f576ddf5dc) | Dec 25, 2019 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [53631f5f96](https://linux-hardware.org/?probe=53631f5f96) | Dec 20, 2019 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [243373ad36](https://linux-hardware.org/?probe=243373ad36) | Dec 19, 2019 |
| Timi          | TM1701                      | Notebook    | [4dcfeff869](https://linux-hardware.org/?probe=4dcfeff869) | Dec 19, 2019 |
| Timi          | TM1701                      | Notebook    | [452b0f742b](https://linux-hardware.org/?probe=452b0f742b) | Dec 19, 2019 |
| Lenovo        | Legion Y9000X 2020 81TH     | Notebook    | [dbca41493b](https://linux-hardware.org/?probe=dbca41493b) | Dec 16, 2019 |
| Dell          | 0VRJCG A05                  | Server      | [0fc3f83656](https://linux-hardware.org/?probe=0fc3f83656) | Dec 14, 2019 |
| Dell          | Latitude E7450              | Notebook    | [611a318d07](https://linux-hardware.org/?probe=611a318d07) | Dec 14, 2019 |
| HUAWEI        | KPL-W0X                     | Notebook    | [85df07509c](https://linux-hardware.org/?probe=85df07509c) | Dec 13, 2019 |
| ONDA          | B320-IPC Ver:1.02           | Desktop     | [06286179c2](https://linux-hardware.org/?probe=06286179c2) | Dec 09, 2019 |
| Lenovo        | Legion Y9000X 2020 81TH     | Notebook    | [626a3add4b](https://linux-hardware.org/?probe=626a3add4b) | Dec 09, 2019 |
| Lenovo        | ThinkPad T440s 20AQS0110... | Notebook    | [7d62d9cb36](https://linux-hardware.org/?probe=7d62d9cb36) | Dec 06, 2019 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [65df5317a4](https://linux-hardware.org/?probe=65df5317a4) | Dec 06, 2019 |
| Dell          | Inspiron 5498               | Notebook    | [6028d35682](https://linux-hardware.org/?probe=6028d35682) | Dec 03, 2019 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [73176f470c](https://linux-hardware.org/?probe=73176f470c) | Nov 24, 2019 |
| Dell          | 0XR1GT A00                  | Desktop     | [76dba7bb94](https://linux-hardware.org/?probe=76dba7bb94) | Nov 22, 2019 |
| Lenovo        | XiaoXin Air 15IKBR 81GY     | Notebook    | [772f437ade](https://linux-hardware.org/?probe=772f437ade) | Nov 22, 2019 |
| ASUSTek       | M5A97                       | Desktop     | [ac3e990070](https://linux-hardware.org/?probe=ac3e990070) | Nov 20, 2019 |
| ASUSTek       | M5A97                       | Desktop     | [742601efb5](https://linux-hardware.org/?probe=742601efb5) | Nov 20, 2019 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [3cb609415c](https://linux-hardware.org/?probe=3cb609415c) | Nov 17, 2019 |
| Gigabyte      | Z87P-D3                     | Desktop     | [db5a6d60dd](https://linux-hardware.org/?probe=db5a6d60dd) | Nov 17, 2019 |
| ASUSTek       | B75M-A                      | Desktop     | [bba74ed5a2](https://linux-hardware.org/?probe=bba74ed5a2) | Nov 15, 2019 |
| HP            | 843C                        | Desktop     | [e5e15df58d](https://linux-hardware.org/?probe=e5e15df58d) | Nov 14, 2019 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [8295b3db5f](https://linux-hardware.org/?probe=8295b3db5f) | Nov 13, 2019 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [bda577e787](https://linux-hardware.org/?probe=bda577e787) | Nov 12, 2019 |
| HP            | Notebook                    | Notebook    | [4aae147ff7](https://linux-hardware.org/?probe=4aae147ff7) | Nov 01, 2019 |
| Lenovo        | 3107 NOK                    | Desktop     | [8545691fd8](https://linux-hardware.org/?probe=8545691fd8) | Oct 24, 2019 |
| Lenovo        | ThinkPad T470 20HDA01FCD    | Notebook    | [83338c47ea](https://linux-hardware.org/?probe=83338c47ea) | Oct 19, 2019 |
| Dell          | Inspiron 3541               | Notebook    | [91758c6727](https://linux-hardware.org/?probe=91758c6727) | Oct 19, 2019 |
| AMI           | Aptio CRB                   | Mini pc     | [268f9a3cb7](https://linux-hardware.org/?probe=268f9a3cb7) | Oct 19, 2019 |
| Lenovo        | ThinkPad T470 20HDA01FCD    | Notebook    | [6d6e604144](https://linux-hardware.org/?probe=6d6e604144) | Oct 18, 2019 |
| ASUSTek       | X455LD                      | Notebook    | [33104ec50e](https://linux-hardware.org/?probe=33104ec50e) | Oct 17, 2019 |
| ASUSTek       | P2440UQ                     | Notebook    | [e75ef73723](https://linux-hardware.org/?probe=e75ef73723) | Oct 15, 2019 |
| MSI           | Z370 GAMING PRO CARBON A... | Desktop     | [30939907c1](https://linux-hardware.org/?probe=30939907c1) | Oct 13, 2019 |
| MSI           | Z370 GAMING PRO CARBON A... | Desktop     | [6b0db76cfd](https://linux-hardware.org/?probe=6b0db76cfd) | Oct 12, 2019 |
| Dell          | 0D2D5F A03                  | Server      | [8fc5d79962](https://linux-hardware.org/?probe=8fc5d79962) | Oct 12, 2019 |
| Sony          | VGN-TZ37N_X                 | Notebook    | [7b4b0311ea](https://linux-hardware.org/?probe=7b4b0311ea) | Oct 07, 2019 |
| Dell          | Latitude E4200              | Notebook    | [1e42f988c0](https://linux-hardware.org/?probe=1e42f988c0) | Oct 05, 2019 |
| Sony          | VGN-TZ37N_X                 | Notebook    | [7fb842e685](https://linux-hardware.org/?probe=7fb842e685) | Oct 05, 2019 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [5eab0577d3](https://linux-hardware.org/?probe=5eab0577d3) | Sep 28, 2019 |
| GPD           | MicroPC                     | Notebook    | [8fc0176f69](https://linux-hardware.org/?probe=8fc0176f69) | Sep 28, 2019 |
| ASUSTek       | B85M-G PLUS/USB             | Desktop     | [174aed26d5](https://linux-hardware.org/?probe=174aed26d5) | Sep 27, 2019 |
| H3C           | C100                        | Notebook    | [ffeae72515](https://linux-hardware.org/?probe=ffeae72515) | Sep 25, 2019 |
| Lenovo        | QiTianM6900                 | Desktop     | [670fee2c10](https://linux-hardware.org/?probe=670fee2c10) | Sep 20, 2019 |
| Unknown       | Unknown                     | Notebook    | [4f9b8fb05a](https://linux-hardware.org/?probe=4f9b8fb05a) | Sep 05, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [9f0b99fb29](https://linux-hardware.org/?probe=9f0b99fb29) | Sep 03, 2019 |
| Lenovo        | 36EB SDK0L77769 WIN 3423... | Desktop     | [5697eebc76](https://linux-hardware.org/?probe=5697eebc76) | Sep 02, 2019 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [5652e9e755](https://linux-hardware.org/?probe=5652e9e755) | Aug 31, 2019 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [1245fd6da5](https://linux-hardware.org/?probe=1245fd6da5) | Aug 30, 2019 |
| Dell          | Precision 7540              | Notebook    | [840094a0e1](https://linux-hardware.org/?probe=840094a0e1) | Aug 27, 2019 |
| HP            | 81C7 MVB 0C                 | Desktop     | [931ea9a398](https://linux-hardware.org/?probe=931ea9a398) | Aug 27, 2019 |
| Unknown       | Unknown                     | Tablet      | [84a981f74b](https://linux-hardware.org/?probe=84a981f74b) | Aug 24, 2019 |
| Dell          | Precision 7540              | Notebook    | [da3219e516](https://linux-hardware.org/?probe=da3219e516) | Aug 22, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [faa579ff30](https://linux-hardware.org/?probe=faa579ff30) | Aug 22, 2019 |
| Lenovo        | ThinkPad T480 20L5001YCD    | Notebook    | [7d7e6ad5d5](https://linux-hardware.org/?probe=7d7e6ad5d5) | Aug 21, 2019 |
| Dell          | 0GDG8Y A00                  | Desktop     | [a055c74af6](https://linux-hardware.org/?probe=a055c74af6) | Aug 18, 2019 |
| Gigabyte      | M68M-S2P                    | Desktop     | [0decbcaa1f](https://linux-hardware.org/?probe=0decbcaa1f) | Aug 16, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [e95e422e8a](https://linux-hardware.org/?probe=e95e422e8a) | Aug 15, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [ee8b6a4998](https://linux-hardware.org/?probe=ee8b6a4998) | Aug 14, 2019 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [641383210d](https://linux-hardware.org/?probe=641383210d) | Aug 12, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [e87b327f29](https://linux-hardware.org/?probe=e87b327f29) | Aug 11, 2019 |
| AMI           | PB_1900A                    | Desktop     | [2c3f429517](https://linux-hardware.org/?probe=2c3f429517) | Aug 10, 2019 |
| ASUSTek       | Z97-AR                      | Desktop     | [510b031ce9](https://linux-hardware.org/?probe=510b031ce9) | Aug 09, 2019 |
| Lenovo        | 36E7 SDK0L77769 WIN 3423... | Desktop     | [69d10d1093](https://linux-hardware.org/?probe=69d10d1093) | Aug 02, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [da4eaeda69](https://linux-hardware.org/?probe=da4eaeda69) | Aug 02, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [58d8b334ea](https://linux-hardware.org/?probe=58d8b334ea) | Aug 02, 2019 |
| Dell          | Precision 5530              | Notebook    | [23f5fb44a9](https://linux-hardware.org/?probe=23f5fb44a9) | Jul 31, 2019 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [6e93995c1c](https://linux-hardware.org/?probe=6e93995c1c) | Jul 25, 2019 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [04b0989528](https://linux-hardware.org/?probe=04b0989528) | Jul 25, 2019 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [565953b703](https://linux-hardware.org/?probe=565953b703) | Jul 24, 2019 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [a6db64d021](https://linux-hardware.org/?probe=a6db64d021) | Jul 24, 2019 |
| ASUSTek       | Zephyrus S GX531GW_GX531... | Notebook    | [383a34edd1](https://linux-hardware.org/?probe=383a34edd1) | Jul 23, 2019 |
| Dell          | 0N9Y46 A00                  | Desktop     | [3548830389](https://linux-hardware.org/?probe=3548830389) | Jul 23, 2019 |
| Gigabyte      | B250M-D3V-CF                | Desktop     | [cba535c695](https://linux-hardware.org/?probe=cba535c695) | Jul 18, 2019 |
| HP            | ProBook 455R G6             | Notebook    | [0d375562bd](https://linux-hardware.org/?probe=0d375562bd) | Jul 17, 2019 |
| HP            | ProBook 455R G6             | Notebook    | [12d1faa353](https://linux-hardware.org/?probe=12d1faa353) | Jul 17, 2019 |
| Lenovo        | M40-70 20445                | Notebook    | [afd92bf265](https://linux-hardware.org/?probe=afd92bf265) | Jul 15, 2019 |
| Alienware     | 17                          | Notebook    | [d5269a87b6](https://linux-hardware.org/?probe=d5269a87b6) | Jul 10, 2019 |
| HP            | 0B10H                       | Desktop     | [758924e4f2](https://linux-hardware.org/?probe=758924e4f2) | Jul 08, 2019 |
| Dell          | Latitude 7390               | Notebook    | [dbb0ffdb96](https://linux-hardware.org/?probe=dbb0ffdb96) | Jul 07, 2019 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [74dfe126d0](https://linux-hardware.org/?probe=74dfe126d0) | Jul 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4b9beb25c2](https://linux-hardware.org/?probe=4b9beb25c2) | Jul 03, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [af9708b601](https://linux-hardware.org/?probe=af9708b601) | Jul 03, 2019 |
| Lenovo        | ThinkPad E485 20KUA00FCD    | Notebook    | [12b55814de](https://linux-hardware.org/?probe=12b55814de) | Jun 30, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [b2644c9243](https://linux-hardware.org/?probe=b2644c9243) | Jun 30, 2019 |
| Lenovo        | ThinkPad Edge E531 68851... | Notebook    | [c25904b3ca](https://linux-hardware.org/?probe=c25904b3ca) | Jun 27, 2019 |
| Dell          | 0DNKMN A00                  | Desktop     | [24870345d1](https://linux-hardware.org/?probe=24870345d1) | Jun 25, 2019 |
| Dell          | 0DNKMN A00                  | Desktop     | [44e012b7fb](https://linux-hardware.org/?probe=44e012b7fb) | Jun 25, 2019 |
| Lenovo        | 1038 NO DPK                 | Server      | [ed799888eb](https://linux-hardware.org/?probe=ed799888eb) | Jun 25, 2019 |
| Lenovo        | IdeaPad Y430 20005          | Notebook    | [5988593465](https://linux-hardware.org/?probe=5988593465) | Jun 21, 2019 |
| Dell          | Inspiron 5488               | Notebook    | [1e82deb58e](https://linux-hardware.org/?probe=1e82deb58e) | Jun 20, 2019 |
| Dell          | 0C96W1 A03                  | Desktop     | [3d80eacdfc](https://linux-hardware.org/?probe=3d80eacdfc) | Jun 18, 2019 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | Notebook    | [f7a1ce2a5b](https://linux-hardware.org/?probe=f7a1ce2a5b) | Jun 15, 2019 |
| Lenovo        | ThinkPad T400 276711U       | Notebook    | [3a3a57b619](https://linux-hardware.org/?probe=3a3a57b619) | Jun 14, 2019 |
| Timi          | TM1701                      | Notebook    | [cde89e0f6e](https://linux-hardware.org/?probe=cde89e0f6e) | Jun 13, 2019 |
| Lenovo        | ZHAOYANG E42-80 80T9        | Notebook    | [bd7312440f](https://linux-hardware.org/?probe=bd7312440f) | Jun 13, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [579eebbcea](https://linux-hardware.org/?probe=579eebbcea) | Jun 07, 2019 |
| ASUSTek       | P8P67 LE                    | Desktop     | [63f1b6d26c](https://linux-hardware.org/?probe=63f1b6d26c) | Jun 06, 2019 |
| ASUSTek       | P8P67 LE                    | Desktop     | [928d66c1a0](https://linux-hardware.org/?probe=928d66c1a0) | Jun 06, 2019 |
| ASUSTek       | P8P67 LE                    | Desktop     | [7ece60be1d](https://linux-hardware.org/?probe=7ece60be1d) | Jun 05, 2019 |
| ASUSTek       | P8P67 LE                    | Desktop     | [83a1805c76](https://linux-hardware.org/?probe=83a1805c76) | Jun 05, 2019 |
| Lenovo        | ZHENGJIUZHE REN7000-28IC... | Desktop     | [1b85d8db4e](https://linux-hardware.org/?probe=1b85d8db4e) | Jun 04, 2019 |
| Gigabyte      | B85M-D2V-SI                 | Desktop     | [6be6da3a8e](https://linux-hardware.org/?probe=6be6da3a8e) | May 31, 2019 |
| Gigabyte      | B85M-D2V-SI                 | Desktop     | [900bc7e93c](https://linux-hardware.org/?probe=900bc7e93c) | May 31, 2019 |
| BenQ          | Joybook R43                 | Notebook    | [f367ae30d1](https://linux-hardware.org/?probe=f367ae30d1) | May 27, 2019 |
| ASUSTek       | PRIME H310T                 | Desktop     | [851b9539e3](https://linux-hardware.org/?probe=851b9539e3) | May 24, 2019 |
| Dell          | 0XFWHV A00                  | Desktop     | [6dac78db97](https://linux-hardware.org/?probe=6dac78db97) | May 23, 2019 |
| MECHREVO      | X6Ti Series                 | Notebook    | [c27e2b94d0](https://linux-hardware.org/?probe=c27e2b94d0) | May 23, 2019 |
| Dell          | 0XFWHV A00                  | Desktop     | [82e6a2d735](https://linux-hardware.org/?probe=82e6a2d735) | May 19, 2019 |
| HP            | EliteBook 8770w             | Notebook    | [ea9a7cc6f1](https://linux-hardware.org/?probe=ea9a7cc6f1) | May 15, 2019 |
| Dell          | Inspiron 3568               | Notebook    | [fb4851964c](https://linux-hardware.org/?probe=fb4851964c) | May 14, 2019 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [e9440445bc](https://linux-hardware.org/?probe=e9440445bc) | May 09, 2019 |
| Gigabyte      | B85N PHOENIX-CF             | Desktop     | [734eb3795e](https://linux-hardware.org/?probe=734eb3795e) | May 08, 2019 |
| ASUSTek       | M2A-VM                      | Desktop     | [3a02e6759d](https://linux-hardware.org/?probe=3a02e6759d) | May 08, 2019 |
| ASUSTek       | H61M-E                      | Desktop     | [6f9f39bbb6](https://linux-hardware.org/?probe=6f9f39bbb6) | May 07, 2019 |
| ASUSTek       | M2A-VM                      | Desktop     | [ac318056f7](https://linux-hardware.org/?probe=ac318056f7) | May 07, 2019 |
| Unknown       | Unknown                     | Notebook    | [f00e135a18](https://linux-hardware.org/?probe=f00e135a18) | May 07, 2019 |
| Acer          | Aspire TC-606               | Desktop     | [5de5deb65e](https://linux-hardware.org/?probe=5de5deb65e) | May 06, 2019 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [8df3c6b792](https://linux-hardware.org/?probe=8df3c6b792) | May 06, 2019 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [62c7769c30](https://linux-hardware.org/?probe=62c7769c30) | May 06, 2019 |
| Acer          | Aspire TC-606               | Desktop     | [1900e5ff06](https://linux-hardware.org/?probe=1900e5ff06) | May 06, 2019 |
| HP            | EliteBook 8770w             | Notebook    | [06ce50566b](https://linux-hardware.org/?probe=06ce50566b) | May 06, 2019 |
| Lenovo        | IdeaPad Y470 20090          | Notebook    | [df1a1447c6](https://linux-hardware.org/?probe=df1a1447c6) | May 05, 2019 |
| Lenovo        | ZHAOYANG E40-70 80EQ003R... | Notebook    | [0a41151a39](https://linux-hardware.org/?probe=0a41151a39) | May 01, 2019 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [61bd5624bb](https://linux-hardware.org/?probe=61bd5624bb) | Apr 30, 2019 |
| Dell          | Precision 5510              | Notebook    | [37725757fc](https://linux-hardware.org/?probe=37725757fc) | Apr 28, 2019 |
| Dell          | Precision 5510              | Notebook    | [77456e54b0](https://linux-hardware.org/?probe=77456e54b0) | Apr 28, 2019 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [0b66bdfee9](https://linux-hardware.org/?probe=0b66bdfee9) | Apr 25, 2019 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [b0a660db1e](https://linux-hardware.org/?probe=b0a660db1e) | Apr 23, 2019 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [3fd02cfa82](https://linux-hardware.org/?probe=3fd02cfa82) | Apr 23, 2019 |
| Intel         | NUC7JYB J67967-401          | Mini pc     | [8f42487a13](https://linux-hardware.org/?probe=8f42487a13) | Apr 21, 2019 |
| Intel         | NUC7JYB J67967-401          | Mini pc     | [f7c28e5bd5](https://linux-hardware.org/?probe=f7c28e5bd5) | Apr 21, 2019 |
| ASUSTek       | B85M-G PLUS/USB             | Desktop     | [8f686df361](https://linux-hardware.org/?probe=8f686df361) | Apr 15, 2019 |
| Lenovo        | ZHAOYANG E40-70 80EQ003R... | Notebook    | [1b42c99fc5](https://linux-hardware.org/?probe=1b42c99fc5) | Apr 15, 2019 |
| AMI           | Aptio CRB                   | Mini pc     | [4e82dec8fe](https://linux-hardware.org/?probe=4e82dec8fe) | Apr 13, 2019 |
| Lenovo        | ZHAOYANG E40-70 80EQ003R... | Notebook    | [d69b467ad1](https://linux-hardware.org/?probe=d69b467ad1) | Apr 12, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [6a9582e524](https://linux-hardware.org/?probe=6a9582e524) | Apr 10, 2019 |
| AMI           | Aptio CRB                   | Mini pc     | [ea343990ce](https://linux-hardware.org/?probe=ea343990ce) | Apr 09, 2019 |
| ASRock        | B360M-HDV                   | Desktop     | [59151791cf](https://linux-hardware.org/?probe=59151791cf) | Apr 09, 2019 |
| Lenovo        | ZHAOYANG E42-80 80T9        | Notebook    | [cd29b46afd](https://linux-hardware.org/?probe=cd29b46afd) | Apr 07, 2019 |
| Gigabyte      | B150M-Power2-EC-CF          | Desktop     | [68b2380c53](https://linux-hardware.org/?probe=68b2380c53) | Apr 05, 2019 |
| Gigabyte      | Z170X-Gaming 5              | Desktop     | [4efc7fbdc6](https://linux-hardware.org/?probe=4efc7fbdc6) | Apr 01, 2019 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [14cba25e3e](https://linux-hardware.org/?probe=14cba25e3e) | Apr 01, 2019 |
| Dell          | Inspiron 7447               | Notebook    | [ecb26ec38f](https://linux-hardware.org/?probe=ecb26ec38f) | Apr 01, 2019 |
| Lenovo        | ThinkPad R400 7445A64       | Notebook    | [c5fb273856](https://linux-hardware.org/?probe=c5fb273856) | Mar 31, 2019 |
| Timi          | TM1801                      | Notebook    | [abab034f2c](https://linux-hardware.org/?probe=abab034f2c) | Mar 31, 2019 |
| Lenovo        | ThinkPad R400 7445A64       | Notebook    | [ca66ac8ff7](https://linux-hardware.org/?probe=ca66ac8ff7) | Mar 31, 2019 |
| MSI           | GL62 6QF                    | Notebook    | [a8aec7c577](https://linux-hardware.org/?probe=a8aec7c577) | Mar 31, 2019 |
| Lenovo        | ThinkPad P50 20EQS0UP00     | Notebook    | [c30803f7e0](https://linux-hardware.org/?probe=c30803f7e0) | Mar 31, 2019 |
| Lenovo        | ThinkPad P50 20EQS0UP00     | Notebook    | [723ee99eb3](https://linux-hardware.org/?probe=723ee99eb3) | Mar 31, 2019 |
| Dell          | Latitude E5420              | Notebook    | [d53b90fc99](https://linux-hardware.org/?probe=d53b90fc99) | Mar 30, 2019 |
| Dell          | Latitude E5420              | Notebook    | [19583c2aa2](https://linux-hardware.org/?probe=19583c2aa2) | Mar 29, 2019 |
| Lenovo        | 1030 SBB0J05441 WIN 3305... | Desktop     | [92262238c3](https://linux-hardware.org/?probe=92262238c3) | Mar 28, 2019 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [175525d48c](https://linux-hardware.org/?probe=175525d48c) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [dccca67c2e](https://linux-hardware.org/?probe=dccca67c2e) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d0787d5045](https://linux-hardware.org/?probe=d0787d5045) | Mar 25, 2019 |
| Lenovo        | 36E7 SDK0L77767 WIN 3423... | Desktop     | [80816fc39e](https://linux-hardware.org/?probe=80816fc39e) | Mar 25, 2019 |
| Gigabyte      | Z87-HD3                     | Desktop     | [050c0abdc8](https://linux-hardware.org/?probe=050c0abdc8) | Mar 18, 2019 |
| HASEE Comp... | CN17S                       | Notebook    | [5d40a7ddb4](https://linux-hardware.org/?probe=5d40a7ddb4) | Mar 17, 2019 |
| ASUSTek       | G501VW                      | Notebook    | [66160704ce](https://linux-hardware.org/?probe=66160704ce) | Mar 15, 2019 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [0b6eea7daa](https://linux-hardware.org/?probe=0b6eea7daa) | Mar 15, 2019 |
| Yeston Dig... | YESTON A78L Policeman V3... | Desktop     | [3a74ed7842](https://linux-hardware.org/?probe=3a74ed7842) | Mar 12, 2019 |
| Yeston Dig... | YESTON A78L Policeman V3... | Desktop     | [3c900dd5ac](https://linux-hardware.org/?probe=3c900dd5ac) | Mar 12, 2019 |
| Gigabyte      | Z87-HD3                     | Desktop     | [a4ad17d97c](https://linux-hardware.org/?probe=a4ad17d97c) | Mar 02, 2019 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [f8e464a0c0](https://linux-hardware.org/?probe=f8e464a0c0) | Feb 22, 2019 |
| Notebook      | P95_HR                      | Notebook    | [c8a8910a82](https://linux-hardware.org/?probe=c8a8910a82) | Feb 21, 2019 |
| Toshiba       | Satellite L855              | Notebook    | [2393db4d67](https://linux-hardware.org/?probe=2393db4d67) | Feb 19, 2019 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [a9e837c9eb](https://linux-hardware.org/?probe=a9e837c9eb) | Feb 08, 2019 |
| Lenovo        | 36E7 SDK0L77769 WIN 3423... | Desktop     | [1b722df896](https://linux-hardware.org/?probe=1b722df896) | Jan 21, 2019 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e077ae4d59](https://linux-hardware.org/?probe=e077ae4d59) | Jan 20, 2019 |
| HP            | 2B4F                        | Desktop     | [188b0e90bc](https://linux-hardware.org/?probe=188b0e90bc) | Jan 08, 2019 |
| Lenovo        | Unknown                     | Notebook    | [433ec22487](https://linux-hardware.org/?probe=433ec22487) | Jan 07, 2019 |
| Lenovo        | Unknown                     | Notebook    | [e43d9001ec](https://linux-hardware.org/?probe=e43d9001ec) | Jan 07, 2019 |
| Dell          | 077RRV A00                  | Desktop     | [c7b9c0beb8](https://linux-hardware.org/?probe=c7b9c0beb8) | Dec 29, 2018 |
| Dell          | 077RRV A00                  | Desktop     | [88d3983de4](https://linux-hardware.org/?probe=88d3983de4) | Dec 29, 2018 |
| Intel         | S2600CP                     | Server      | [f65ec09250](https://linux-hardware.org/?probe=f65ec09250) | Dec 09, 2018 |
| ASUSTek       | UX31E                       | Notebook    | [2333e930af](https://linux-hardware.org/?probe=2333e930af) | Dec 06, 2018 |
| Timi          | TM1709                      | Notebook    | [c8d28d98f3](https://linux-hardware.org/?probe=c8d28d98f3) | Dec 04, 2018 |
| ASUSTek       | B85M-G PLUS/USB             | Desktop     | [cbb464c414](https://linux-hardware.org/?probe=cbb464c414) | Dec 04, 2018 |
| HASEE Comp... | P870TM_TM1                  | Notebook    | [a7db7c544f](https://linux-hardware.org/?probe=a7db7c544f) | Nov 26, 2018 |
| Timi          | TM1604                      | Notebook    | [09435f5ab9](https://linux-hardware.org/?probe=09435f5ab9) | Nov 26, 2018 |
| HASEE Comp... | P870TM_TM1                  | Notebook    | [8ba4b8de88](https://linux-hardware.org/?probe=8ba4b8de88) | Nov 23, 2018 |
| HASEE Comp... | P870TM_TM1                  | Notebook    | [93547de344](https://linux-hardware.org/?probe=93547de344) | Nov 23, 2018 |
| Dell          | 084YMW A07                  | Server      | [cbfb7c31d8](https://linux-hardware.org/?probe=cbfb7c31d8) | Nov 22, 2018 |
| Dell          | 084YMW A07                  | Server      | [ab025272de](https://linux-hardware.org/?probe=ab025272de) | Nov 22, 2018 |
| Lenovo        | 3102 SDK0L77769 WIN 3423... | Desktop     | [2143ae0253](https://linux-hardware.org/?probe=2143ae0253) | Nov 13, 2018 |
| Huanan        | X79 PLUS V6.11              | Desktop     | [0a36000504](https://linux-hardware.org/?probe=0a36000504) | Nov 05, 2018 |
| Fujitsu       | LIFEBOOK U2010              | Notebook    | [c4e618e233](https://linux-hardware.org/?probe=c4e618e233) | Nov 01, 2018 |
| Dell          | Inspiron 11-3157            | Notebook    | [22a545025c](https://linux-hardware.org/?probe=22a545025c) | Oct 29, 2018 |
| Huanan        | X79 V1.4                    | Desktop     | [1204ed863a](https://linux-hardware.org/?probe=1204ed863a) | Oct 29, 2018 |
| Lenovo        | 36C5 SDK0L77767 WIN 3423... | Desktop     | [73b72b86b8](https://linux-hardware.org/?probe=73b72b86b8) | Oct 29, 2018 |
| MSI           | GE60 0NC\0ND                | Notebook    | [4500f40ba8](https://linux-hardware.org/?probe=4500f40ba8) | Oct 26, 2018 |
| MSI           | GE60 0NC\0ND                | Notebook    | [50d4655cc8](https://linux-hardware.org/?probe=50d4655cc8) | Oct 26, 2018 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [c843257cd9](https://linux-hardware.org/?probe=c843257cd9) | Oct 26, 2018 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [b79afee742](https://linux-hardware.org/?probe=b79afee742) | Oct 26, 2018 |
| Lenovo        | B450 1S16800336200F7        | Notebook    | [23ed383b90](https://linux-hardware.org/?probe=23ed383b90) | Sep 25, 2018 |
| Lenovo        | ThinkPad X240 20AMS0KG00    | Notebook    | [1069f23a4c](https://linux-hardware.org/?probe=1069f23a4c) | Jul 03, 2018 |
| Dell          | Inspiron 3559               | Notebook    | [b3ad3b61ac](https://linux-hardware.org/?probe=b3ad3b61ac) | Jun 03, 2018 |
| Dell          | Inspiron 3559               | Notebook    | [15b2cb5350](https://linux-hardware.org/?probe=15b2cb5350) | May 02, 2018 |
| Dell          | Inspiron 3559               | Notebook    | [d068125f3c](https://linux-hardware.org/?probe=d068125f3c) | Apr 28, 2018 |
| Dell          | Inspiron 3559               | Notebook    | [5d77eff84b](https://linux-hardware.org/?probe=5d77eff84b) | Apr 28, 2018 |
| ASUSTek       | K56CB                       | Notebook    | [c2992a0291](https://linux-hardware.org/?probe=c2992a0291) | Apr 14, 2018 |
| Dell          | Inspiron 3559               | Notebook    | [f1d49b5cb9](https://linux-hardware.org/?probe=f1d49b5cb9) | Feb 25, 2018 |
| Lenovo        | Erazer Y40-70 20407         | Notebook    | [3aaa7ea4d0](https://linux-hardware.org/?probe=3aaa7ea4d0) | Feb 12, 2018 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [94d087771b](https://linux-hardware.org/?probe=94d087771b) | Sep 24, 2017 |
| Dell          | Inspiron 7560               | Notebook    | [49389100fc](https://linux-hardware.org/?probe=49389100fc) | Apr 15, 2017 |
| MSI           | GS60 6QC                    | Notebook    | [404f145917](https://linux-hardware.org/?probe=404f145917) | May 18, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 153       | 15.24%  |
| Ubuntu 18.04                 | 128       | 12.75%  |
| Arch                         | 50        | 4.98%   |
| Debian 11                    | 39        | 3.88%   |
| Arch Rolling                 | 29        | 2.89%   |
| Ubuntu 22.04                 | 22        | 2.19%   |
| Ubuntu 19.04                 | 21        | 2.09%   |
| OpenMandriva 4.2             | 20        | 1.99%   |
| Debian 10                    | 19        | 1.89%   |
| OpenMandriva 4.3             | 18        | 1.79%   |
| Manjaro                      | 18        | 1.79%   |
| UOS 20                       | 17        | 1.69%   |
| Ubuntu 16.04                 | 17        | 1.69%   |
| Ubuntu 21.10                 | 16        | 1.59%   |
| KDE neon 20.04               | 16        | 1.59%   |
| Gentoo 2.7                   | 16        | 1.59%   |
| Ubuntu 21.04                 | 15        | 1.49%   |
| openSUSE Tumbleweed-XXXXXXXX | 15        | 1.49%   |
| Ubuntu 19.10                 | 14        | 1.39%   |
| Fedora 33                    | 13        | 1.29%   |
| Linux Mint 20.1              | 12        | 1.2%    |
| Linux Mint 20.3              | 10        | 1%      |
| Gentoo 2.8                   | 10        | 1%      |
| CentOS 7                     | 10        | 1%      |
| Gentoo 2.6                   | 9         | 0.9%    |
| Fedora 35                    | 9         | 0.9%    |
| CentOS 8                     | 9         | 0.9%    |
| Ubuntu 20.10                 | 8         | 0.8%    |
| Linux Mint 20.2              | 8         | 0.8%    |
| Fedora 34                    | 8         | 0.8%    |
| Fedora 32                    | 8         | 0.8%    |
| ROSA R10                     | 7         | 0.7%    |
| Linux Mint 20                | 7         | 0.7%    |
| Debian Testing               | 7         | 0.7%    |
| OpenMandriva 4.50            | 6         | 0.6%    |
| ArcoLinux Rolling            | 6         | 0.6%    |
| Manjaro 18.1.4               | 5         | 0.5%    |
| Kubuntu 20.04                | 5         | 0.5%    |
| Fedora 36                    | 5         | 0.5%    |
| Atz 11.3                     | 5         | 0.5%    |
| Ubuntu 18.10                 | 4         | 0.4%    |
| Pop!_OS 20.04                | 4         | 0.4%    |
| Kylin V10                    | 4         | 0.4%    |
| Fedora 31                    | 4         | 0.4%    |
| Debian Unstable              | 4         | 0.4%    |
| BlackPanther 18.1            | 4         | 0.4%    |
| Android                      | 4         | 0.4%    |
| Xubuntu 20.04                | 3         | 0.3%    |
| Pop!_OS 21.04                | 3         | 0.3%    |
| Manjaro 21.2.6               | 3         | 0.3%    |
| Manjaro 20.2.1               | 3         | 0.3%    |
| Manjaro 20.2                 | 3         | 0.3%    |
| Manjaro 20.0                 | 3         | 0.3%    |
| Manjaro 19.0.2               | 3         | 0.3%    |
| Kubuntu 22.10                | 3         | 0.3%    |
| Elementary 6.1               | 3         | 0.3%    |
| Debian 9                     | 3         | 0.3%    |
| Zorin 16                     | 2         | 0.2%    |
| Xubuntu 18.04                | 2         | 0.2%    |
| RHEL 8                       | 2         | 0.2%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 389       | 39.73%  |
| Arch         | 77        | 7.87%   |
| Debian       | 76        | 7.76%   |
| Manjaro      | 56        | 5.72%   |
| Fedora       | 48        | 4.9%    |
| OpenMandriva | 46        | 4.7%    |
| Linux Mint   | 41        | 4.19%   |
| Gentoo       | 33        | 3.37%   |
| Deepin       | 28        | 2.86%   |
| CentOS       | 19        | 1.94%   |
| openSUSE     | 18        | 1.84%   |
| KDE neon     | 18        | 1.84%   |
| Kubuntu      | 13        | 1.33%   |
| Pop!_OS      | 12        | 1.23%   |
| ROSA         | 11        | 1.12%   |
| Kali         | 8         | 0.82%   |
| Xubuntu      | 7         | 0.72%   |
| Elementary   | 7         | 0.72%   |
| Clear Linux  | 7         | 0.72%   |
| Atz          | 7         | 0.72%   |
| ArcoLinux    | 7         | 0.72%   |
| Kylin        | 6         | 0.61%   |
| BlackPanther | 4         | 0.41%   |
| Android      | 4         | 0.41%   |
| Ubuntu MATE  | 3         | 0.31%   |
| Zorin        | 2         | 0.2%    |
| Ubuntu Kylin | 2         | 0.2%    |
| RHEL         | 2         | 0.2%    |
| RedFlag      | 2         | 0.2%    |
| NFS Desktop  | 2         | 0.2%    |
| MX           | 2         | 0.2%    |
| LMDE         | 2         | 0.2%    |
| Guix         | 2         | 0.2%    |
| Endless      | 2         | 0.2%    |
| Trisquel     | 1         | 0.1%    |
| SteamOS      | 1         | 0.1%    |
| Solus        | 1         | 0.1%    |
| Rocky Linux  | 1         | 0.1%    |
| RED          | 1         | 0.1%    |
| Raspbian     | 1         | 0.1%    |
| PureOS       | 1         | 0.1%    |
| OpenEuler    | 1         | 0.1%    |
| Lubuntu      | 1         | 0.1%    |
| LinuxFX      | 1         | 0.1%    |
| Garuda Linux | 1         | 0.1%    |
| DSM          | 1         | 0.1%    |
| Artix        | 1         | 0.1%    |
| AOSC OS      | 1         | 0.1%    |
| ALT Linux    | 1         | 0.1%    |
| Alpine       | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 19        | 1.78%   |
| 5.16.7-desktop-1omv4003  | 17        | 1.59%   |
| 5.4.0-42-generic         | 14        | 1.31%   |
| 5.10.0-8-amd64           | 10        | 0.94%   |
| 5.13.0-30-generic        | 9         | 0.84%   |
| 5.0.0-23-generic         | 9         | 0.84%   |
| 5.11.0-43-generic        | 8         | 0.75%   |
| 4.18.0-25-generic        | 8         | 0.75%   |
| 5.4.0-58-generic         | 7         | 0.66%   |
| 5.0.0-13-generic         | 7         | 0.66%   |
| 4.18.0-16-generic        | 7         | 0.66%   |
| 5.8.0-50-generic         | 6         | 0.56%   |
| 5.4.0-74-generic         | 6         | 0.56%   |
| 5.4.0-73-generic         | 6         | 0.56%   |
| 5.4.0-48-generic         | 6         | 0.56%   |
| 5.4.0-33-generic         | 6         | 0.56%   |
| 5.4.0-29-generic         | 6         | 0.56%   |
| 5.3.0-46-generic         | 6         | 0.56%   |
| 5.15.0-41-generic        | 6         | 0.56%   |
| 5.15.0-25-generic        | 6         | 0.56%   |
| 5.12.4-desktop-1omv4050  | 6         | 0.56%   |
| 5.11.0-34-generic        | 6         | 0.56%   |
| 5.8.0-63-generic         | 5         | 0.47%   |
| 5.8.0-43-generic         | 5         | 0.47%   |
| 5.4.0-77-generic         | 5         | 0.47%   |
| 5.4.0-54-generic         | 5         | 0.47%   |
| 5.4.0-52-generic         | 5         | 0.47%   |
| 5.3.0-28-generic         | 5         | 0.47%   |
| 5.15.0-46-generic        | 5         | 0.47%   |
| 5.15.0-2-amd64           | 5         | 0.47%   |
| 5.13.0-35-generic        | 5         | 0.47%   |
| 5.13.0-22-generic        | 5         | 0.47%   |
| 5.11.0-41-generic        | 5         | 0.47%   |
| 5.11.0-40-generic        | 5         | 0.47%   |
| 5.11.0-37-generic        | 5         | 0.47%   |
| 5.11.0-27-generic        | 5         | 0.47%   |
| 5.10.41-amd64-desktop    | 5         | 0.47%   |
| 5.0.0-25-generic         | 5         | 0.47%   |
| 4.18.0-15-generic        | 5         | 0.47%   |
| 5.8.0-55-generic         | 4         | 0.37%   |
| 5.6.14-desktop-2bP       | 4         | 0.37%   |
| 5.4.0-53-generic         | 4         | 0.37%   |
| 5.4.0-47-generic         | 4         | 0.37%   |
| 5.4.0-40-generic         | 4         | 0.37%   |
| 5.4.0-37-generic         | 4         | 0.37%   |
| 5.4.0-107-generic        | 4         | 0.37%   |
| 5.3.0-24-generic         | 4         | 0.37%   |
| 5.3.0-18-generic         | 4         | 0.37%   |
| 5.15.0-27-generic        | 4         | 0.37%   |
| 5.13.0-44-generic        | 4         | 0.37%   |
| 5.13.0-41-generic        | 4         | 0.37%   |
| 5.13.0-28-generic        | 4         | 0.37%   |
| 5.11.0-25-generic        | 4         | 0.37%   |
| 5.10.36-2-MANJARO        | 4         | 0.37%   |
| 5.10.0-9-amd64           | 4         | 0.37%   |
| 5.10.0-1011-oem          | 4         | 0.37%   |
| 5.0.0-37-generic         | 4         | 0.37%   |
| 4.18.0-17-generic        | 4         | 0.37%   |
| 4.15.0-58-generic        | 4         | 0.37%   |
| 4.15.0-47-generic        | 4         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 132       | 12.78%  |
| 5.11.0  | 57        | 5.52%   |
| 4.15.0  | 57        | 5.52%   |
| 5.13.0  | 50        | 4.84%   |
| 5.10.0  | 46        | 4.45%   |
| 5.8.0   | 45        | 4.36%   |
| 4.18.0  | 45        | 4.36%   |
| 5.0.0   | 43        | 4.16%   |
| 5.3.0   | 35        | 3.39%   |
| 5.15.0  | 33        | 3.19%   |
| 4.19.0  | 24        | 2.32%   |
| 5.10.14 | 19        | 1.84%   |
| 5.16.7  | 18        | 1.74%   |
| 3.10.0  | 9         | 0.87%   |
| 5.16.0  | 8         | 0.77%   |
| 5.6.14  | 7         | 0.68%   |
| 5.18.12 | 6         | 0.58%   |
| 5.12.4  | 6         | 0.58%   |
| 5.6.0   | 5         | 0.48%   |
| 5.14.0  | 5         | 0.48%   |
| 5.10.41 | 5         | 0.48%   |
| 5.10.36 | 5         | 0.48%   |
| 4.9.60  | 5         | 0.48%   |
| 5.9.16  | 4         | 0.39%   |
| 5.9.11  | 4         | 0.39%   |
| 5.7.7   | 4         | 0.39%   |
| 5.4.2   | 4         | 0.39%   |
| 5.4.18  | 4         | 0.39%   |
| 5.18.0  | 4         | 0.39%   |
| 5.17.5  | 4         | 0.39%   |
| 5.17.1  | 4         | 0.39%   |
| 5.17.0  | 4         | 0.39%   |
| 5.14.6  | 4         | 0.39%   |
| 5.10.27 | 4         | 0.39%   |
| 5.8.18  | 3         | 0.29%   |
| 5.18.9  | 3         | 0.29%   |
| 5.18.5  | 3         | 0.29%   |
| 5.18.15 | 3         | 0.29%   |
| 5.17.9  | 3         | 0.29%   |
| 5.17.8  | 3         | 0.29%   |
| 5.17.4  | 3         | 0.29%   |
| 5.16.9  | 3         | 0.29%   |
| 5.15.5  | 3         | 0.29%   |
| 5.15.32 | 3         | 0.29%   |
| 5.15.28 | 3         | 0.29%   |
| 5.13.13 | 3         | 0.29%   |
| 5.12.9  | 3         | 0.29%   |
| 5.12.10 | 3         | 0.29%   |
| 5.12.0  | 3         | 0.29%   |
| 5.11.12 | 3         | 0.29%   |
| 5.10.60 | 3         | 0.29%   |
| 5.10.4  | 3         | 0.29%   |
| 5.10.35 | 3         | 0.29%   |
| 4.9.0   | 3         | 0.29%   |
| 4.13.0  | 3         | 0.29%   |
| 4.1.42  | 3         | 0.29%   |
| 5.9.8   | 2         | 0.19%   |
| 5.9.12  | 2         | 0.19%   |
| 5.9.10  | 2         | 0.19%   |
| 5.9.0   | 2         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 162       | 15.85%  |
| 5.10    | 116       | 11.35%  |
| 5.11    | 74        | 7.24%   |
| 5.15    | 72        | 7.05%   |
| 5.8     | 61        | 5.97%   |
| 5.13    | 61        | 5.97%   |
| 4.15    | 57        | 5.58%   |
| 5.0     | 47        | 4.6%    |
| 4.18    | 47        | 4.6%    |
| 5.3     | 42        | 4.11%   |
| 5.16    | 39        | 3.82%   |
| 4.19    | 30        | 2.94%   |
| 5.18    | 29        | 2.84%   |
| 5.17    | 24        | 2.35%   |
| 5.12    | 23        | 2.25%   |
| 5.14    | 22        | 2.15%   |
| 5.9     | 20        | 1.96%   |
| 5.6     | 19        | 1.86%   |
| 5.7     | 12        | 1.17%   |
| 4.9     | 12        | 1.17%   |
| 3.10    | 11        | 1.08%   |
| 5.5     | 8         | 0.78%   |
| 5.1     | 5         | 0.49%   |
| 4.1     | 5         | 0.49%   |
| 4.14    | 4         | 0.39%   |
| 5.19    | 3         | 0.29%   |
| 4.4     | 3         | 0.29%   |
| 4.13    | 3         | 0.29%   |
| 5.2     | 2         | 0.2%    |
| 4.20    | 2         | 0.2%    |
| 3.4     | 2         | 0.2%    |
| 4.6     | 1         | 0.1%    |
| 4.17    | 1         | 0.1%    |
| 4.12    | 1         | 0.1%    |
| 4.10    | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 913       | 95.4%   |
| aarch64 | 20        | 2.09%   |
| i686    | 8         | 0.84%   |
| riscv64 | 7         | 0.73%   |
| ppc64   | 3         | 0.31%   |
| armv7l  | 2         | 0.21%   |
| sh4a    | 1         | 0.1%    |
| mips64  | 1         | 0.1%    |
| armv8l  | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 403       | 41.08%  |
| Unknown         | 191       | 19.47%  |
| KDE5            | 148       | 15.09%  |
| XFCE            | 59        | 6.01%   |
| KDE             | 34        | 3.47%   |
| X-Cinnamon      | 33        | 3.36%   |
| Deepin          | 26        | 2.65%   |
| i3              | 15        | 1.53%   |
| MATE            | 12        | 1.22%   |
| Unity           | 10        | 1.02%   |
| Pantheon        | 7         | 0.71%   |
| Cinnamon        | 7         | 0.71%   |
| UKUI            | 6         | 0.61%   |
| LXDE            | 5         | 0.51%   |
| KDE4            | 5         | 0.51%   |
| GNOME Flashback | 4         | 0.41%   |
| Budgie          | 4         | 0.41%   |
| GNOME Classic   | 3         | 0.31%   |
| GNUstep         | 2         | 0.2%    |
| xmonad          | 1         | 0.1%    |
| sway            | 1         | 0.1%    |
| qtile           | 1         | 0.1%    |
| Openbox         | 1         | 0.1%    |
| LXQt            | 1         | 0.1%    |
| bspwm           | 1         | 0.1%    |
| awesome         | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 712       | 72.8%   |
| Wayland | 123       | 12.58%  |
| Unknown | 96        | 9.82%   |
| Tty     | 47        | 4.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 464       | 47.44%  |
| GDM     | 150       | 15.34%  |
| SDDM    | 135       | 13.8%   |
| LightDM | 94        | 9.61%   |
| GDM3    | 82        | 8.38%   |
| TDM     | 44        | 4.5%    |
| KDM     | 4         | 0.41%   |
| XDM     | 2         | 0.2%    |
| LXDM    | 2         | 0.2%    |
| SLiM    | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| zh_CN       | 408       | 41.89%  |
| en_US       | 346       | 35.52%  |
| Unknown     | 165       | 16.94%  |
| C           | 16        | 1.64%   |
| en_GB       | 10        | 1.03%   |
| en_HK       | 8         | 0.82%   |
| mn_CN       | 4         | 0.41%   |
| en_AU       | 3         | 0.31%   |
| ja_JP       | 2         | 0.21%   |
| de_DE       | 2         | 0.21%   |
| C.UTF8      | 2         | 0.21%   |
| th_TH       | 1         | 0.1%    |
| ru_RU       | 1         | 0.1%    |
| POSIX       | 1         | 0.1%    |
| fr_FR       | 1         | 0.1%    |
| en_ZA       | 1         | 0.1%    |
| en_US.utf-8 | 1         | 0.1%    |
| en_SG       | 1         | 0.1%    |
| .en_US      | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 627       | 64.57%  |
| BIOS | 344       | 35.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type       | Computers | Percent |
|------------|-----------|---------|
| Ext4       | 768       | 79.18%  |
| Btrfs      | 72        | 7.42%   |
| Overlay    | 43        | 4.43%   |
| Xfs        | 40        | 4.12%   |
| Unknown    | 30        | 3.09%   |
| Zfs        | 9         | 0.93%   |
| F2fs       | 4         | 0.41%   |
| Tmpfs      | 1         | 0.1%    |
| Rootfs     | 1         | 0.1%    |
| Reiserfs   | 1         | 0.1%    |
| Fuse.sshfs | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 444       | 46.06%  |
| GPT     | 440       | 45.64%  |
| MBR     | 80        | 8.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 831       | 85.49%  |
| Yes       | 141       | 14.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 579       | 60.12%  |
| Yes       | 384       | 39.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 259       | 27.09%  |
| Dell                           | 108       | 11.3%   |
| ASUSTek Computer               | 92        | 9.62%   |
| Hewlett-Packard                | 78        | 8.16%   |
| HUAWEI                         | 44        | 4.6%    |
| Gigabyte Technology            | 44        | 4.6%    |
| MSI                            | 40        | 4.18%   |
| Timi                           | 29        | 3.03%   |
| Intel                          | 27        | 2.82%   |
| Unknown                        | 26        | 2.72%   |
| Acer                           | 24        | 2.51%   |
| HASEE Computer                 | 12        | 1.26%   |
| ASRock                         | 11        | 1.15%   |
| Apple                          | 10        | 1.05%   |
| Raspberry Pi Foundation        | 7         | 0.73%   |
| Microsoft                      | 7         | 0.73%   |
| Toshiba                        | 6         | 0.63%   |
| Supermicro                     | 6         | 0.63%   |
| Sony                           | 6         | 0.63%   |
| MECHREVO                       | 6         | 0.63%   |
| Google                         | 6         | 0.63%   |
| AMI                            | 6         | 0.63%   |
| TSINGHUA TONGFANG COMPUTER     | 5         | 0.52%   |
| Phytium                        | 5         | 0.52%   |
| GPD                            | 4         | 0.42%   |
| Fujitsu                        | 4         | 0.42%   |
| Samsung Electronics            | 3         | 0.31%   |
| Notebook                       | 3         | 0.31%   |
| Intel Client Systems           | 3         | 0.31%   |
| Huanan                         | 3         | 0.31%   |
| Colorful Technology            | 3         | 0.31%   |
| Terrans Force                  | 2         | 0.21%   |
| Soyo                           | 2         | 0.21%   |
| Shanghai Zhaoxin Semiconductor | 2         | 0.21%   |
| OEM                            | 2         | 0.21%   |
| LG Electronics                 | 2         | 0.21%   |
| Jumper                         | 2         | 0.21%   |
| IPASON                         | 2         | 0.21%   |
| Insyde                         | 2         | 0.21%   |
| ECS                            | 2         | 0.21%   |
| Biostar                        | 2         | 0.21%   |
| Alienware                      | 2         | 0.21%   |
| Yeston Digital Technology      | 1         | 0.1%    |
| Yanling                        | 1         | 0.1%    |
| X79-1356                       | 1         | 0.1%    |
| win element                    | 1         | 0.1%    |
| TR                             | 1         | 0.1%    |
| Teclast                        | 1         | 0.1%    |
| SYWZ                           | 1         | 0.1%    |
| Synology                       | 1         | 0.1%    |
| Schenker                       | 1         | 0.1%    |
| Sapphire                       | 1         | 0.1%    |
| retsamarret                    | 1         | 0.1%    |
| RBQ                            | 1         | 0.1%    |
| Razer                          | 1         | 0.1%    |
| Quanta                         | 1         | 0.1%    |
| Qualcomm Technologies          | 1         | 0.1%    |
| ONDA                           | 1         | 0.1%    |
| Nvidia                         | 1         | 0.1%    |
| METAPHYUNI                     | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 38        | 3.97%   |
| ASUS All Series                          | 10        | 1.05%   |
| HUAWEI HLY-WX9XX                         | 8         | 0.84%   |
| Lenovo Legion R9000P2021H 82JQ           | 6         | 0.63%   |
| TSINGHUA TONGFANG COMPUTER E500          | 5         | 0.52%   |
| Timi TM1701                              | 5         | 0.52%   |
| MSI MS-7B89                              | 5         | 0.52%   |
| Lenovo Legion R7000 2020 82B6            | 5         | 0.52%   |
| Phytium FT-2000/4                        | 4         | 0.42%   |
| MSI MS-7C94                              | 4         | 0.42%   |
| Lenovo ThinkBook 15p Gen 2 21B1          | 4         | 0.42%   |
| HUAWEI NBLK-WAX9X                        | 4         | 0.42%   |
| HUAWEI BOHK-WAX9X                        | 4         | 0.42%   |
| AMI Aptio CRB                            | 4         | 0.42%   |
| Timi TM1709                              | 3         | 0.31%   |
| Timi RedmiBook Pro 15S                   | 3         | 0.31%   |
| Timi RedmiBook 14 II                     | 3         | 0.31%   |
| Supermicro Super Server                  | 3         | 0.31%   |
| Microsoft Surface Go                     | 3         | 0.31%   |
| Lenovo ZHAOYANG K4e-ITL 82F8             | 3         | 0.31%   |
| Lenovo Yoga 14cACN 2021 82N7             | 3         | 0.31%   |
| Lenovo XiaoXinPro-13IML 2019 81XB        | 3         | 0.31%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN        | 3         | 0.31%   |
| Lenovo XiaoXin-15ARE 2020 81YR           | 3         | 0.31%   |
| Lenovo ThinkBook 14 G2 ITL 20VD          | 3         | 0.31%   |
| Lenovo Legion Y7000 81FW                 | 3         | 0.31%   |
| Intel Client Systems LAPKC71F            | 3         | 0.31%   |
| HUAWEI KPRC-WX0                          | 3         | 0.31%   |
| HUAWEI KPR-WX9                           | 3         | 0.31%   |
| HUAWEI KPL-W0X                           | 3         | 0.31%   |
| HP ENVY Laptop 13-ad1xx                  | 3         | 0.31%   |
| Dell XPS 15 9570                         | 3         | 0.31%   |
| ASUS TUF Gaming B550M-PLUS               | 3         | 0.31%   |
| ASUS M5A78L-M LX3 PLUS                   | 3         | 0.31%   |
| Acer Swift SF314-42                      | 3         | 0.31%   |
| Timi TM1613                              | 2         | 0.21%   |
| Timi Mi Laptop Pro 15                    | 2         | 0.21%   |
| Shanghai Zhaoxin ZXE CRB                 | 2         | 0.21%   |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 2         | 0.21%   |
| RPi Raspberry Pi 4 Model B Rev 1.1       | 2         | 0.21%   |
| RPi Raspberry Pi                         | 2         | 0.21%   |
| MSI MS-7A40                              | 2         | 0.21%   |
| Lenovo ZHAOYANG E42-80 80T9              | 2         | 0.21%   |
| Lenovo Yoga C940-14IIL 81Q9              | 2         | 0.21%   |
| Lenovo Yoga 14sARH 2021 82LB             | 2         | 0.21%   |
| Lenovo YangTianT4900c-00 90ETCTO1WW      | 2         | 0.21%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM        | 2         | 0.21%   |
| Lenovo ThinkStation P300 10DACTO1WW      | 2         | 0.21%   |
| Lenovo ThinkPad T14 Gen 1 20UD0004CD     | 2         | 0.21%   |
| Lenovo ThinkPad E555 20DHA01MCD          | 2         | 0.21%   |
| Lenovo ThinkCentre M910t-N000 10N9CTO1WW | 2         | 0.21%   |
| Lenovo ThinkBook 14p Gen 2 20YN          | 2         | 0.21%   |
| Lenovo Legion Y9000X 2020 81TH           | 2         | 0.21%   |
| Lenovo Legion R7000P2020H 82GR           | 2         | 0.21%   |
| Lenovo IdeaPad Y470 20090                | 2         | 0.21%   |
| Lenovo G510 20238                        | 2         | 0.21%   |
| Jumper EZbook                            | 2         | 0.21%   |
| Intel NUC5PPYB H76558-109                | 2         | 0.21%   |
| Intel NUC10i7FNH                         | 2         | 0.21%   |
| HUAWEI WRT-WX9                           | 2         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 88        | 9.21%   |
| Unknown                         | 38        | 3.97%   |
| Dell Inspiron                   | 30        | 3.14%   |
| Lenovo Legion                   | 29        | 3.03%   |
| Dell Latitude                   | 19        | 1.99%   |
| Lenovo ThinkBook                | 15        | 1.57%   |
| ASUS PRIME                      | 15        | 1.57%   |
| HP ZHAN                         | 13        | 1.36%   |
| HP EliteBook                    | 13        | 1.36%   |
| Dell OptiPlex                   | 13        | 1.36%   |
| Acer Aspire                     | 13        | 1.36%   |
| Lenovo ZHAOYANG                 | 12        | 1.26%   |
| Dell XPS                        | 12        | 1.26%   |
| Dell Precision                  | 12        | 1.26%   |
| ASUS TUF                        | 12        | 1.26%   |
| Lenovo Yoga                     | 11        | 1.15%   |
| Lenovo ThinkCentre              | 11        | 1.15%   |
| Lenovo IdeaPad                  | 11        | 1.15%   |
| HP OMEN                         | 10        | 1.05%   |
| ASUS All                        | 10        | 1.05%   |
| Dell PowerEdge                  | 9         | 0.94%   |
| ASUS ROG                        | 9         | 0.94%   |
| HUAWEI HLY-WX9XX                | 8         | 0.84%   |
| Timi RedmiBook                  | 7         | 0.73%   |
| RPi Raspberry                   | 7         | 0.73%   |
| Microsoft Surface               | 7         | 0.73%   |
| Lenovo ThinkStation             | 7         | 0.73%   |
| HP ProBook                      | 7         | 0.73%   |
| HP ENVY                         | 7         | 0.73%   |
| Acer Swift                      | 7         | 0.73%   |
| TSINGHUA TONGFANG COMPUTER E500 | 5         | 0.52%   |
| Timi TM1701                     | 5         | 0.52%   |
| MSI MS-7B89                     | 5         | 0.52%   |
| Lenovo XiaoXin                  | 5         | 0.52%   |
| Dell Vostro                     | 5         | 0.52%   |
| Toshiba Satellite               | 4         | 0.42%   |
| Phytium FT-2000                 | 4         | 0.42%   |
| MSI MS-7C94                     | 4         | 0.42%   |
| Lenovo ZHENGJIUZHE              | 4         | 0.42%   |
| HUAWEI NBLK-WAX9X               | 4         | 0.42%   |
| HUAWEI BOHK-WAX9X               | 4         | 0.42%   |
| HP ProDesk                      | 4         | 0.42%   |
| HP Pavilion                     | 4         | 0.42%   |
| AMI Aptio                       | 4         | 0.42%   |
| Acer Nitro                      | 4         | 0.42%   |
| Timi TM1709                     | 3         | 0.31%   |
| Timi Mi                         | 3         | 0.31%   |
| Supermicro Super                | 3         | 0.31%   |
| Lenovo XiaoXinPro-13IML         | 3         | 0.31%   |
| Lenovo XiaoXinPro               | 3         | 0.31%   |
| Lenovo XiaoXinAir-14ARE         | 3         | 0.31%   |
| Lenovo XiaoXin-15ARE            | 3         | 0.31%   |
| Intel Client Systems LAPKC71F   | 3         | 0.31%   |
| HUAWEI KPRC-WX0                 | 3         | 0.31%   |
| HUAWEI KPR-WX9                  | 3         | 0.31%   |
| HUAWEI KPL-W0X                  | 3         | 0.31%   |
| Huanan X79                      | 3         | 0.31%   |
| HP Laptop                       | 3         | 0.31%   |
| Dell G3                         | 3         | 0.31%   |
| ASUS M5A78L-M                   | 3         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 140       | 14.64%  |
| 2019    | 124       | 12.97%  |
| 2018    | 123       | 12.87%  |
| 2021    | 115       | 12.03%  |
| 2017    | 76        | 7.95%   |
| 2015    | 64        | 6.69%   |
| 2013    | 49        | 5.13%   |
| 2016    | 46        | 4.81%   |
| 2012    | 45        | 4.71%   |
| 2014    | 43        | 4.5%    |
| 2011    | 37        | 3.87%   |
| Unknown | 25        | 2.62%   |
| 2022    | 23        | 2.41%   |
| 2009    | 14        | 1.46%   |
| 2010    | 13        | 1.36%   |
| 2008    | 11        | 1.15%   |
| 2007    | 7         | 0.73%   |
| 2006    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 562       | 58.79%  |
| Desktop        | 283       | 29.6%   |
| Server         | 36        | 3.77%   |
| Mini pc        | 22        | 2.3%    |
| Tablet         | 17        | 1.78%   |
| Convertible    | 16        | 1.67%   |
| System on chip | 10        | 1.05%   |
| All in one     | 5         | 0.52%   |
| Phone          | 3         | 0.31%   |
| Other          | 2         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 878       | 91.27%  |
| Enabled  | 84        | 8.73%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 950       | 99.37%  |
| Yes  | 6         | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 234       | 24.25%  |
| 4.01-8.0        | 217       | 22.49%  |
| 8.01-16.0       | 209       | 21.66%  |
| 3.01-4.0        | 105       | 10.88%  |
| 32.01-64.0      | 97        | 10.05%  |
| 64.01-256.0     | 44        | 4.56%   |
| 1.01-2.0        | 20        | 2.07%   |
| 24.01-32.0      | 19        | 1.97%   |
| 0.51-1.0        | 8         | 0.83%   |
| Unknown         | 6         | 0.62%   |
| More than 256.0 | 4         | 0.41%   |
| 2.01-3.0        | 1         | 0.1%    |
| 0.01-0.5        | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 294       | 28.35%  |
| 2.01-3.0    | 267       | 25.75%  |
| 4.01-8.0    | 174       | 16.78%  |
| 3.01-4.0    | 150       | 14.46%  |
| 0.51-1.0    | 58        | 5.59%   |
| 8.01-16.0   | 44        | 4.24%   |
| 0.01-0.5    | 25        | 2.41%   |
| Unknown     | 10        | 0.96%   |
| 16.01-24.0  | 8         | 0.77%   |
| 32.01-64.0  | 4         | 0.39%   |
| 24.01-32.0  | 2         | 0.19%   |
| 64.01-256.0 | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 534       | 55.05%  |
| 2       | 306       | 31.55%  |
| 3       | 71        | 7.32%   |
| 4       | 27        | 2.78%   |
| 5       | 12        | 1.24%   |
| 0       | 8         | 0.82%   |
| 6       | 4         | 0.41%   |
| 10      | 3         | 0.31%   |
| 9       | 2         | 0.21%   |
| 36      | 1         | 0.1%    |
| 11      | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 811       | 84.22%  |
| Yes       | 152       | 15.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 763       | 79.4%   |
| No        | 198       | 20.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 744       | 77.5%   |
| No        | 216       | 22.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 625       | 64.7%   |
| No        | 341       | 35.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| China   | 956       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Beijing          | 192       | 19.1%   |
| Shanghai         | 84        | 8.36%   |
| Shenzhen         | 79        | 7.86%   |
| Guangzhou        | 71        | 7.06%   |
| Hangzhou         | 31        | 3.08%   |
| Wuhan            | 30        | 2.99%   |
| Chengdu          | 30        | 2.99%   |
| Nanjing          | 21        | 2.09%   |
| Xi'an            | 19        | 1.89%   |
| Tianjin          | 16        | 1.59%   |
| Xuhui            | 15        | 1.49%   |
| Zhengzhou        | 12        | 1.19%   |
| Suzhou           | 11        | 1.09%   |
| Haidian          | 11        | 1.09%   |
| Dongguan         | 11        | 1.09%   |
| Nanning          | 10        | 1%      |
| Huangpu          | 10        | 1%      |
| Hefei            | 10        | 1%      |
| Foshan           | 10        | 1%      |
| Dalian           | 10        | 1%      |
| Chongqing        | 10        | 1%      |
| Qingdao          | 9         | 0.9%    |
| Jinan            | 9         | 0.9%    |
| Changsha         | 9         | 0.9%    |
| Shenyang         | 8         | 0.8%    |
| Kunming          | 8         | 0.8%    |
| Fuzhou           | 8         | 0.8%    |
| Hohhot           | 7         | 0.7%    |
| Xicheng District | 6         | 0.6%    |
| Xiamen           | 6         | 0.6%    |
| Putuo            | 6         | 0.6%    |
| Hongkou          | 6         | 0.6%    |
| Guiyang          | 6         | 0.6%    |
| Changchun        | 6         | 0.6%    |
| Xining           | 5         | 0.5%    |
| Pudong           | 5         | 0.5%    |
| Jinrongjie       | 5         | 0.5%    |
| Zhenjiang        | 4         | 0.4%    |
| Taiyuan          | 4         | 0.4%    |
| Jiangmen         | 4         | 0.4%    |
| Zhaoqing         | 3         | 0.3%    |
| Xinyang          | 3         | 0.3%    |
| Ürümqi         | 3         | 0.3%    |
| Shaoxing         | 3         | 0.3%    |
| Qikeshu          | 3         | 0.3%    |
| Liuli            | 3         | 0.3%    |
| Lanzhou          | 3         | 0.3%    |
| Futian           | 3         | 0.3%    |
| Baoqiao          | 3         | 0.3%    |
| Zhongba          | 2         | 0.2%    |
| Yanqing          | 2         | 0.2%    |
| Wuxi             | 2         | 0.2%    |
| Shijiazhuang     | 2         | 0.2%    |
| Qinnan           | 2         | 0.2%    |
| Qingxiucun       | 2         | 0.2%    |
| Ningbo           | 2         | 0.2%    |
| Nanyang          | 2         | 0.2%    |
| Nanhao           | 2         | 0.2%    |
| Nanchang         | 2         | 0.2%    |
| Meizhou          | 2         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 251       | 314    | 17.45%  |
| WDC                         | 196       | 255    | 13.63%  |
| Seagate                     | 182       | 254    | 12.66%  |
| Toshiba                     | 94        | 116    | 6.54%   |
| SanDisk                     | 68        | 79     | 4.73%   |
| Unknown                     | 67        | 89     | 4.66%   |
| Intel                       | 51        | 73     | 3.55%   |
| SK hynix                    | 44        | 54     | 3.06%   |
| Kingston                    | 40        | 48     | 2.78%   |
| HGST                        | 32        | 48     | 2.23%   |
| Plextor                     | 25        | 28     | 1.74%   |
| Micron Technology           | 25        | 25     | 1.74%   |
| Silicon Motion              | 20        | 23     | 1.39%   |
| Hitachi                     | 17        | 27     | 1.18%   |
| Lenovo                      | 16        | 23     | 1.11%   |
| LITEON                      | 14        | 18     | 0.97%   |
| Crucial                     | 14        | 17     | 0.97%   |
| A-DATA Technology           | 13        | 16     | 0.9%    |
| Phison                      | 12        | 16     | 0.83%   |
| GALAX                       | 10        | 10     | 0.7%    |
| Netac                       | 9         | 10     | 0.63%   |
| JMicron Technology          | 9         | 7      | 0.63%   |
| FORESEE                     | 9         | 11     | 0.63%   |
| Hikvision                   | 8         | 8      | 0.56%   |
| Colorful                    | 8         | 10     | 0.56%   |
| Apple                       | 8         | 8      | 0.56%   |
| Unknown                     | 8         | 9      | 0.56%   |
| Teclast                     | 7         | 7      | 0.49%   |
| KIOXIA-EXCERIA              | 7         | 10     | 0.49%   |
| KIOXIA                      | 7         | 10     | 0.49%   |
| Hewlett-Packard             | 7         | 8      | 0.49%   |
| ZHITAI                      | 6         | 6      | 0.42%   |
| Transcend                   | 6         | 7      | 0.42%   |
| Lite-On                     | 6         | 8      | 0.42%   |
| Fujitsu                     | 6         | 6      | 0.42%   |
| China                       | 6         | 8      | 0.42%   |
| KINGBANK                    | 5         | 8      | 0.35%   |
| GLOWAY                      | 5         | 5      | 0.35%   |
| Faspeed                     | 5         | 5      | 0.35%   |
| Pear 2TB                    | 4         | 4      | 0.28%   |
| External                    | 4         | 6      | 0.28%   |
| UMIS                        | 3         | 3      | 0.21%   |
| LITEONIT                    | 3         | 3      | 0.21%   |
| Lexar                       | 3         | 3      | 0.21%   |
| KingSpec                    | 3         | 3      | 0.21%   |
| Kingchuxing                 | 3         | 3      | 0.21%   |
| Yangtze Memory Technologies | 2         | 2      | 0.14%   |
| Vaseky                      | 2         | 2      | 0.14%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.14%   |
| tigo                        | 2         | 2      | 0.14%   |
| Q200                        | 2         | 5      | 0.14%   |
| Phison Electronics          | 2         | 2      | 0.14%   |
| OCZ                         | 2         | 2      | 0.14%   |
| MAXIO Technology (Hangzhou) | 2         | 3      | 0.14%   |
| KingShare                   | 2         | 2      | 0.14%   |
| KDATA                       | 2         | 3      | 0.14%   |
| Getrich                     | 2         | 2      | 0.14%   |
| Galaxy                      | 2         | 2      | 0.14%   |
| ASMT                        | 2         | 5      | 0.14%   |
| ADATA Technology            | 2         | 2      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB            | 23        | 1.47%   |
| WDC WD10EZEX-08WN4A0 1TB                | 16        | 1.02%   |
| SanDisk NVMe SSD Drive 512GB            | 16        | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB          | 15        | 0.96%   |
| HGST HTS721010A9E630 1TB                | 14        | 0.89%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 13        | 0.83%   |
| Samsung MZVLB512HBJQ-000L2 512GB        | 13        | 0.83%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 12        | 0.77%   |
| Samsung NVMe SSD Drive 256GB            | 12        | 0.77%   |
| Seagate ST1000LM048-2E7172 1TB          | 11        | 0.7%    |
| Seagate ST1000DM003-1SB102 1TB          | 11        | 0.7%    |
| Samsung SSD 860 EVO 500GB               | 11        | 0.7%    |
| WDC WDS100T2B0C-00PXH0 1TB              | 10        | 0.64%   |
| SK hynix NVMe SSD Drive 512GB           | 10        | 0.64%   |
| Seagate ST500LT012-1DG142 500GB         | 10        | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB          | 10        | 0.64%   |
| SanDisk NVMe SSD Drive 1TB              | 9         | 0.57%   |
| Unknown MMC Card  64GB                  | 8         | 0.51%   |
| Seagate ST500DM002-1BD142 500GB         | 8         | 0.51%   |
| Seagate ST2000LM007-1R8174 2TB          | 8         | 0.51%   |
| Samsung MZVLB512HBJQ-000L7 512GB        | 8         | 0.51%   |
| Samsung MZVLB512HAJQ-00000 512GB        | 8         | 0.51%   |
| Plextor PX-128M6S 128GB SSD             | 8         | 0.51%   |
| Unknown                                 | 8         | 0.51%   |
| Toshiba MQ01ABD100 1TB                  | 7         | 0.45%   |
| Seagate ST500LM021-1KJ152 500GB         | 7         | 0.45%   |
| WDC WD10EZEX-08M2NA0 1TB                | 6         | 0.38%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB    | 6         | 0.38%   |
| Toshiba DT01ACA200 2TB                  | 6         | 0.38%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB  | 6         | 0.38%   |
| Seagate ST3500418AS 500GB               | 6         | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 6         | 0.38%   |
| Samsung SSD 860 EVO 250GB               | 6         | 0.38%   |
| Samsung SM963 2.5" NVMe PCIe SSD 128GB  | 6         | 0.38%   |
| Samsung NVMe SSD Drive 500GB            | 6         | 0.38%   |
| Samsung NVMe SSD Drive 1TB              | 6         | 0.38%   |
| JMicron Generic 160GB                   | 6         | 0.38%   |
| GALAX TA1D0240A 240GB                   | 6         | 0.38%   |
| Unknown MMC Card  32GB                  | 5         | 0.32%   |
| Unknown MMC Card  128GB                 | 5         | 0.32%   |
| Toshiba TR200 480GB SSD                 | 5         | 0.32%   |
| Toshiba NVMe SSD Drive 512GB            | 5         | 0.32%   |
| Seagate ST1000DM003-1ER162 1TB          | 5         | 0.32%   |
| SanDisk NVMe SSD Drive 2TB              | 5         | 0.32%   |
| Intel SSDPEKNW010T8 1TB                 | 5         | 0.32%   |
| Intel NVMe SSD Drive 512GB              | 5         | 0.32%   |
| Hikvision HS-SSD-E2000L 512G            | 5         | 0.32%   |
| HGST HTS725050A7E630 500GB              | 5         | 0.32%   |
| WDC WD10SPZX-22Z10T0 1TB                | 4         | 0.26%   |
| WDC WD10EZEX-22MFCA0 1TB                | 4         | 0.26%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 4         | 0.26%   |
| Unknown SD64G  64GB                     | 4         | 0.26%   |
| Unknown MMC Card  16GB                  | 4         | 0.26%   |
| Silicon Motion NVMe SSD Drive 1TB       | 4         | 0.26%   |
| Silicon Motion NVMe SSD Drive 1024GB    | 4         | 0.26%   |
| Seagate ST3000DM008-2DM166 3TB          | 4         | 0.26%   |
| Seagate ST3000DM001-1ER166 3TB          | 4         | 0.26%   |
| Seagate ST2000DM006-2DM164 2TB          | 4         | 0.26%   |
| Samsung SSD 980 1TB                     | 4         | 0.26%   |
| Samsung NVMe SSD Drive 250GB            | 4         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 181       | 252    | 41.8%   |
| WDC                 | 139       | 175    | 32.1%   |
| Toshiba             | 40        | 51     | 9.24%   |
| HGST                | 32        | 48     | 7.39%   |
| Hitachi             | 17        | 27     | 3.93%   |
| Samsung Electronics | 9         | 10     | 2.08%   |
| Fujitsu             | 6         | 6      | 1.39%   |
| Pear 2TB            | 4         | 4      | 0.92%   |
| ACASIS              | 2         | 2      | 0.46%   |
| LIO-ORG             | 1         | 9      | 0.23%   |
| IBM H0              | 1         | 1      | 0.23%   |
| ASMT                | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 84        | 101    | 20.49%  |
| SanDisk             | 26        | 28     | 6.34%   |
| Kingston            | 26        | 32     | 6.34%   |
| Toshiba             | 24        | 27     | 5.85%   |
| Plextor             | 22        | 24     | 5.37%   |
| Intel               | 18        | 23     | 4.39%   |
| WDC                 | 14        | 16     | 3.41%   |
| LITEON              | 13        | 17     | 3.17%   |
| Micron Technology   | 11        | 11     | 2.68%   |
| Crucial             | 11        | 14     | 2.68%   |
| A-DATA Technology   | 11        | 14     | 2.68%   |
| Lenovo              | 10        | 12     | 2.44%   |
| GALAX               | 10        | 10     | 2.44%   |
| Netac               | 8         | 9      | 1.95%   |
| Teclast             | 7         | 7      | 1.71%   |
| JMicron Technology  | 6         | 6      | 1.46%   |
| China               | 6         | 8      | 1.46%   |
| Transcend           | 5         | 6      | 1.22%   |
| SK hynix            | 5         | 5      | 1.22%   |
| GLOWAY              | 4         | 4      | 0.98%   |
| FORESEE             | 4         | 4      | 0.98%   |
| Colorful            | 4         | 4      | 0.98%   |
| Apple               | 4         | 4      | 0.98%   |
| Unknown             | 4         | 5      | 0.98%   |
| Unknown             | 3         | 4      | 0.73%   |
| LITEONIT            | 3         | 3      | 0.73%   |
| Lexar               | 3         | 3      | 0.73%   |
| Kingchuxing         | 3         | 3      | 0.73%   |
| ZHITAI              | 2         | 2      | 0.49%   |
| Vaseky              | 2         | 2      | 0.49%   |
| tigo                | 2         | 2      | 0.49%   |
| Q200                | 2         | 5      | 0.49%   |
| Phison              | 2         | 3      | 0.49%   |
| OCZ                 | 2         | 2      | 0.49%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.49%   |
| KingShare           | 2         | 2      | 0.49%   |
| KINGBANK            | 2         | 2      | 0.49%   |
| Hewlett-Packard     | 2         | 3      | 0.49%   |
| Galaxy              | 2         | 2      | 0.49%   |
| Faspeed             | 2         | 2      | 0.49%   |
| Xinsujie            | 1         | 1      | 0.24%   |
| WDC WDS1            | 1         | 1      | 0.24%   |
| UNIC2               | 1         | 1      | 0.24%   |
| TurXun              | 1         | 1      | 0.24%   |
| TOPMORE             | 1         | 1      | 0.24%   |
| TO Exter            | 1         | 1      | 0.24%   |
| TAISU               | 1         | 1      | 0.24%   |
| StoreJet            | 1         | 1      | 0.24%   |
| Soyo                | 1         | 1      | 0.24%   |
| ShineDisk           | 1         | 1      | 0.24%   |
| SCWW                | 1         | 1      | 0.24%   |
| Pear                | 1         | 1      | 0.24%   |
| NGFF                | 1         | 1      | 0.24%   |
| MX                  | 1         | 1      | 0.24%   |
| MR                  | 1         | 3      | 0.24%   |
| Maxmemroy           | 1         | 1      | 0.24%   |
| MAXIO               | 1         | 1      | 0.24%   |
| Lite-On             | 1         | 1      | 0.24%   |
| LIO-ORG             | 1         | 24     | 0.24%   |
| LenovoSPEED         | 1         | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 460       | 632    | 35.47%  |
| HDD     | 378       | 586    | 29.14%  |
| SSD     | 354       | 502    | 27.29%  |
| MMC     | 60        | 77     | 4.63%   |
| Unknown | 45        | 54     | 3.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 586       | 1067   | 49.87%  |
| NVMe | 460       | 625    | 39.15%  |
| SAS  | 69        | 82     | 5.87%   |
| MMC  | 60        | 77     | 5.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 399       | 620    | 53.77%  |
| 0.51-1.0   | 236       | 293    | 31.81%  |
| 1.01-2.0   | 59        | 73     | 7.95%   |
| 3.01-4.0   | 17        | 29     | 2.29%   |
| 2.01-3.0   | 13        | 23     | 1.75%   |
| 4.01-10.0  | 13        | 40     | 1.75%   |
| 10.01-20.0 | 5         | 10     | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 244       | 24.67%  |
| 251-500        | 234       | 23.66%  |
| 501-1000       | 150       | 15.17%  |
| 51-100         | 90        | 9.1%    |
| 1001-2000      | 77        | 7.79%   |
| 1-20           | 56        | 5.66%   |
| More than 3000 | 48        | 4.85%   |
| 21-50          | 37        | 3.74%   |
| 2001-3000      | 29        | 2.93%   |
| Unknown        | 24        | 2.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 408       | 40.08%  |
| 21-50          | 162       | 15.91%  |
| 101-250        | 136       | 13.36%  |
| 51-100         | 106       | 10.41%  |
| 251-500        | 83        | 8.15%   |
| 501-1000       | 44        | 4.32%   |
| 1001-2000      | 29        | 2.85%   |
| Unknown        | 24        | 2.36%   |
| More than 3000 | 14        | 1.38%   |
| 2001-3000      | 12        | 1.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB                       | 2         | 2      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB              | 2         | 2      | 3.85%   |
| Seagate ST1000LM048-2E7172 1TB               | 2         | 2      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 3.85%   |
| Crucial CT240M500SSD1 240GB                  | 2         | 2      | 3.85%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 1      | 1.92%   |
| WDC WD5003ABYZ-011FA0 500GB                  | 1         | 1      | 1.92%   |
| WDC WD5000AAKX-08ERMA0 500GB                 | 1         | 1      | 1.92%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1      | 1.92%   |
| WDC WD5000AAKX-0 500GB                       | 1         | 1      | 1.92%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 1      | 1.92%   |
| WDC WD10SPZX-60Z10T0 1TB                     | 1         | 1      | 1.92%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 1      | 1.92%   |
| WDC WD10EZEX-00BN5A0 1TB                     | 1         | 1      | 1.92%   |
| Toshiba MK3259GSXP 320GB                     | 1         | 1      | 1.92%   |
| Toshiba MK2555GSX 250GB                      | 1         | 1      | 1.92%   |
| Toshiba DT01ACA300 3TB                       | 1         | 1      | 1.92%   |
| Seagate ST980811AS 80GB                      | 1         | 1      | 1.92%   |
| Seagate ST750LM028-1KK162 752GB              | 1         | 1      | 1.92%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 1.92%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 2      | 1.92%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 1.92%   |
| Seagate ST500DM009-2DM14C 500GB              | 1         | 1      | 1.92%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 1.92%   |
| Seagate ST5000AS0011-1L5178 5TB              | 1         | 1      | 1.92%   |
| Seagate ST31000524AS 1TB                     | 1         | 1      | 1.92%   |
| SanDisk SSD U100 128GB                       | 1         | 1      | 1.92%   |
| SanDisk SD9SN8W-256G-1006 256GB SSD          | 1         | 1      | 1.92%   |
| Samsung Electronics SSD 970 EVO 500GB        | 1         | 1      | 1.92%   |
| Samsung Electronics MZVLW512HMJP-00000 512GB | 1         | 1      | 1.92%   |
| Plextor PX-256M6S+ 256GB SSD                 | 1         | 1      | 1.92%   |
| Plextor PX-128M6S 128GB SSD                  | 1         | 1      | 1.92%   |
| Netac SSD 120GB                              | 1         | 1      | 1.92%   |
| Lenovo SSD SL700 120G                        | 1         | 1      | 1.92%   |
| Intel SSDSC2KW240H6 240GB                    | 1         | 1      | 1.92%   |
| Intel SSDSC2BW360H6 360GB                    | 1         | 1      | 1.92%   |
| Intel SSDPEKKF256G7H 256GB                   | 1         | 1      | 1.92%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 1.92%   |
| Hitachi HTS541060G9SA00 64GB                 | 1         | 1      | 1.92%   |
| Hitachi HTS541040G9AT00 40GB                 | 1         | 1      | 1.92%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 1.92%   |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 1.92%   |
| Fujitsu MJA2250BH G2 250GB                   | 1         | 1      | 1.92%   |
| Fujitsu MHV2100BH PL 100GB                   | 1         | 1      | 1.92%   |
| Crucial M4-CT128M4SSD1 128GB                 | 1         | 1      | 1.92%   |
| Colorful SL500 320GB SSD                     | 1         | 1      | 1.92%   |
| A-DATA Technology SP900 128GB SSD            | 1         | 2      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 16     | 27.45%  |
| WDC                 | 9         | 9      | 17.65%  |
| Toshiba             | 5         | 5      | 9.8%    |
| Intel               | 3         | 3      | 5.88%   |
| Hitachi             | 3         | 3      | 5.88%   |
| Crucial             | 3         | 3      | 5.88%   |
| SanDisk             | 2         | 2      | 3.92%   |
| Samsung Electronics | 2         | 2      | 3.92%   |
| Plextor             | 2         | 2      | 3.92%   |
| HGST                | 2         | 2      | 3.92%   |
| Fujitsu             | 2         | 2      | 3.92%   |
| Netac               | 1         | 1      | 1.96%   |
| Lenovo              | 1         | 1      | 1.96%   |
| Colorful            | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 2      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 16     | 41.18%  |
| WDC     | 8         | 8      | 23.53%  |
| Toshiba | 5         | 5      | 14.71%  |
| Hitachi | 3         | 3      | 8.82%   |
| HGST    | 2         | 2      | 5.88%   |
| Fujitsu | 2         | 2      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 36     | 68.75%  |
| SSD  | 12        | 15     | 25%     |
| NVMe | 3         | 3      | 6.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST31500341AS 1TB          | 1         | 1      | 25%     |
| Samsung Electronics HS06THB 64GB  | 1         | 1      | 25%     |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 25%     |
| Phison ESO128GTLC9-E8C-2 128GB    | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 50%     |
| Seagate             | 1         | 1      | 25%     |
| Phison              | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 524       | 982    | 51.12%  |
| Works    | 451       | 811    | 44%     |
| Malfunc  | 46        | 54     | 4.49%   |
| Failed   | 4         | 4      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 581       | 46.15%  |
| Samsung Electronics              | 170       | 13.5%   |
| AMD                              | 145       | 11.52%  |
| SanDisk                          | 88        | 6.99%   |
| SK hynix                         | 39        | 3.1%    |
| Toshiba America Info Systems     | 33        | 2.62%   |
| Silicon Motion                   | 32        | 2.54%   |
| Phison Electronics               | 18        | 1.43%   |
| Micron Technology                | 14        | 1.11%   |
| Marvell Technology Group         | 14        | 1.11%   |
| KIOXIA                           | 14        | 1.11%   |
| Kingston Technology Company      | 14        | 1.11%   |
| ASMedia Technology               | 10        | 0.79%   |
| Broadcom / LSI                   | 8         | 0.64%   |
| LSI Logic / Symbios Logic        | 7         | 0.56%   |
| Lite-On Technology               | 7         | 0.56%   |
| Shenzhen Longsys Electronics     | 6         | 0.48%   |
| Yangtze Memory Technologies      | 5         | 0.4%    |
| JMicron Technology               | 5         | 0.4%    |
| ADATA Technology                 | 5         | 0.4%    |
| Union Memory (Shenzhen)          | 4         | 0.32%   |
| Solid State Storage Technology   | 4         | 0.32%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.32%   |
| Apple                            | 4         | 0.32%   |
| Zhaoxin                          | 3         | 0.24%   |
| Silicon Integrated Systems [SiS] | 3         | 0.24%   |
| Micron/Crucial Technology        | 3         | 0.24%   |
| Huawei Technologies              | 3         | 0.24%   |
| Mylex                            | 2         | 0.16%   |
| Biwin Storage Technology         | 2         | 0.16%   |
| Beijing Starblaze Technology     | 2         | 0.16%   |
| Silicon Image                    | 1         | 0.08%   |
| Seagate Technology               | 1         | 0.08%   |
| Realtek Semiconductor            | 1         | 0.08%   |
| Nvidia                           | 1         | 0.08%   |
| Loongson Technology              | 1         | 0.08%   |
| Lenovo                           | 1         | 0.08%   |
| IBM                              | 1         | 0.08%   |
| HighPoint Technologies           | 1         | 0.08%   |
| Hewlett-Packard                  | 1         | 0.08%   |
| Hefei DATANG Storage Technology  | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 113       | 8.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 99        | 7.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 61        | 4.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 45        | 3.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 35        | 2.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 31        | 2.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 29        | 2.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 26        | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                           | 25        | 1.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 23        | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 22        | 1.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 21        | 1.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 21        | 1.51%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 21        | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 21        | 1.51%   |
| SK hynix Gold P31 SSD                                                            | 20        | 1.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 20        | 1.44%   |
| Samsung NVMe SSD Controller 980                                                  | 20        | 1.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 20        | 1.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 20        | 1.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 20        | 1.44%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 18        | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                              | 17        | 1.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 16        | 1.15%   |
| SanDisk Non-Volatile memory controller                                           | 15        | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 15        | 1.08%   |
| Micron Non-Volatile memory controller                                            | 14        | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                            | 14        | 1.01%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 13        | 0.93%   |
| AMD 500 Series Chipset SATA Controller                                           | 13        | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 12        | 0.86%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 11        | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 11        | 0.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 11        | 0.79%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 10        | 0.72%   |
| Intel SATA Controller [RAID mode]                                                | 10        | 0.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 10        | 0.72%   |
| SK hynix Non-Volatile memory controller                                          | 9         | 0.65%   |
| Phison PS5013 E13 NVMe Controller                                                | 9         | 0.65%   |
| Intel Tiger Lake-LP SATA Controller                                              | 9         | 0.65%   |
| Intel SSD 660P Series                                                            | 9         | 0.65%   |
| Intel SSD 600P Series                                                            | 9         | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 0.65%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 9         | 0.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 9         | 0.65%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 8         | 0.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 0.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 0.57%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 8         | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 0.57%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 7         | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 0.5%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 7         | 0.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 7         | 0.5%    |
| SK hynix BC511                                                                   | 6         | 0.43%   |
| Lite-On Non-Volatile memory controller                                           | 6         | 0.43%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 6         | 0.43%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 6         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 647       | 51.47%  |
| NVMe | 464       | 36.91%  |
| RAID | 71        | 5.65%   |
| IDE  | 66        | 5.25%   |
| SAS  | 7         | 0.56%   |
| SCSI | 2         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 707       | 73.95%  |
| AMD               | 211       | 22.07%  |
| ARM               | 10        | 1.05%   |
| Unknown           | 8         | 0.84%   |
| Phytium           | 7         | 0.73%   |
| sifive,bullet0    | 3         | 0.31%   |
| CentaurHauls      | 3         | 0.31%   |
| sifive,u74-mc     | 2         | 0.21%   |
| QUALCOMM          | 2         | 0.21%   |
| CHRP IBM,9131-52A | 2         | 0.21%   |
| CHRP IBM,8233-E8B | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 2.3%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 1.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 16        | 1.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 1.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.36%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 1.25%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.15%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 1.04%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 10        | 1.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 9         | 0.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.94%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 9         | 0.94%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 8         | 0.84%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.84%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 8         | 0.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.84%   |
| ARM Processor                                 | 8         | 0.84%   |
|                                               | 8         | 0.84%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 7         | 0.73%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 7         | 0.73%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 7         | 0.73%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.63%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.63%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 6         | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.63%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 6         | 0.63%   |
| AMD Ryzen 5 4600U with Radeon Graphics        | 6         | 0.63%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 0.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 6         | 0.63%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 6         | 0.63%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 5         | 0.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.52%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 5         | 0.52%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.52%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 5         | 0.52%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 0.52%   |
| Phytium FT-2000/4                             | 4         | 0.42%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 0.42%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 4         | 0.42%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 4         | 0.42%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.42%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.42%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 4         | 0.42%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 4         | 0.42%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.42%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.42%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.42%   |
| Intel 12th Gen Core i7-12700H                 | 4         | 0.42%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics    | 4         | 0.42%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 0.42%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 0.42%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 4         | 0.42%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 4         | 0.42%   |
| sifive,bullet0 rv64imafdc                     | 3         | 0.31%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 213       | 22.28%  |
| Intel Core i7           | 210       | 21.97%  |
| Other                   | 103       | 10.77%  |
| AMD Ryzen 5             | 73        | 7.64%   |
| AMD Ryzen 7             | 63        | 6.59%   |
| Intel Xeon              | 46        | 4.81%   |
| Intel Core i3           | 46        | 4.81%   |
| Intel Celeron           | 31        | 3.24%   |
| Intel Pentium           | 20        | 2.09%   |
| Intel Core 2 Duo        | 15        | 1.57%   |
| Intel Atom              | 15        | 1.57%   |
| AMD Ryzen 7 PRO         | 13        | 1.36%   |
| Intel Core i9           | 9         | 0.94%   |
| AMD Ryzen 9             | 8         | 0.84%   |
| AMD FX                  | 6         | 0.63%   |
| AMD Athlon II X2        | 6         | 0.63%   |
| AMD A6                  | 6         | 0.63%   |
| AMD A10                 | 6         | 0.63%   |
| Intel Core m3           | 5         | 0.52%   |
| AMD Ryzen 5 PRO         | 5         | 0.52%   |
| AMD A8                  | 5         | 0.52%   |
| Intel Xeon Silver       | 4         | 0.42%   |
| Intel Pentium Dual      | 4         | 0.42%   |
| Intel Xeon Gold         | 3         | 0.31%   |
| Intel Pentium Silver    | 3         | 0.31%   |
| Intel Pentium Dual-Core | 3         | 0.31%   |
| Intel Genuine           | 3         | 0.31%   |
| AMD Athlon              | 3         | 0.31%   |
| Intel Core M            | 2         | 0.21%   |
| Intel Core 2 Quad       | 2         | 0.21%   |
| Intel Core 2            | 2         | 0.21%   |
| AMD Ryzen 3             | 2         | 0.21%   |
| AMD EPYC                | 2         | 0.21%   |
| AMD Athlon X4           | 2         | 0.21%   |
| QUALCOMM AArch64        | 1         | 0.1%    |
| Intel Xeon Platinum     | 1         | 0.1%    |
| Intel Xeon Bronze       | 1         | 0.1%    |
| Intel Pentium M         | 1         | 0.1%    |
| Intel Core m5           | 1         | 0.1%    |
| Intel Core Duo          | 1         | 0.1%    |
| Intel Core              | 1         | 0.1%    |
| Intel Celeron Dual-Core | 1         | 0.1%    |
| ARM BCM                 | 1         | 0.1%    |
| ARM AArch64             | 1         | 0.1%    |
| AMD Ryzen Threadripper  | 1         | 0.1%    |
| AMD Phenom II X4        | 1         | 0.1%    |
| AMD E2                  | 1         | 0.1%    |
| AMD E                   | 1         | 0.1%    |
| AMD C-50                | 1         | 0.1%    |
| AMD Athlon 64 X2        | 1         | 0.1%    |
| AMD A4                  | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 378       | 39.46%  |
| 2       | 259       | 27.04%  |
| 6       | 127       | 13.26%  |
| 8       | 116       | 12.11%  |
| 12      | 17        | 1.77%   |
| 1       | 13        | 1.36%   |
| 16      | 10        | 1.04%   |
| Unknown | 8         | 0.84%   |
| 24      | 7         | 0.73%   |
| 10      | 6         | 0.63%   |
| 14      | 4         | 0.42%   |
| 32      | 3         | 0.31%   |
| 96      | 2         | 0.21%   |
| 20      | 2         | 0.21%   |
| 64      | 1         | 0.1%    |
| 40      | 1         | 0.1%    |
| 36      | 1         | 0.1%    |
| 28      | 1         | 0.1%    |
| 26      | 1         | 0.1%    |
| 3       | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 914       | 95.51%  |
| 2       | 32        | 3.34%   |
| Unknown | 8         | 0.84%   |
| 6       | 1         | 0.1%    |
| 4       | 1         | 0.1%    |
| 3       | 1         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 722       | 75.37%  |
| 1       | 227       | 23.7%   |
| Unknown | 8         | 0.84%   |
| 4       | 1         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 923       | 96.35%  |
| Unknown        | 29        | 3.03%   |
| 32-bit         | 4         | 0.42%   |
| 64-bit         | 2         | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 202       | 20.65%  |
| 0x906ea    | 50        | 5.11%   |
| 0x306c3    | 45        | 4.6%    |
| 0x306a9    | 43        | 4.4%    |
| 0x206a7    | 34        | 3.48%   |
| 0x806ea    | 33        | 3.37%   |
| 0x806e9    | 30        | 3.07%   |
| 0x506e3    | 29        | 2.97%   |
| 0x806ec    | 28        | 2.86%   |
| 0x806c1    | 27        | 2.76%   |
| 0x0a50000c | 27        | 2.76%   |
| 0x906e9    | 26        | 2.66%   |
| 0x08600106 | 24        | 2.45%   |
| 0x40651    | 21        | 2.15%   |
| 0x306d4    | 19        | 1.94%   |
| 0x406e3    | 16        | 1.64%   |
| 0x08108102 | 15        | 1.53%   |
| 0x1067a    | 13        | 1.33%   |
| 0xa0652    | 12        | 1.23%   |
| 0x08600104 | 12        | 1.23%   |
| 0x806d1    | 11        | 1.12%   |
| 0x08108109 | 11        | 1.12%   |
| 0xa0655    | 9         | 0.92%   |
| 0x706e5    | 8         | 0.82%   |
| 0xa0660    | 7         | 0.72%   |
| 0x906a3    | 7         | 0.72%   |
| 0x50654    | 7         | 0.72%   |
| 0x306e4    | 7         | 0.72%   |
| 0x30678    | 7         | 0.72%   |
| 0x08701013 | 7         | 0.72%   |
| 0x706a1    | 6         | 0.61%   |
| 0x306f2    | 6         | 0.61%   |
| 0x08600103 | 6         | 0.61%   |
| 0x0810100b | 6         | 0.61%   |
| 0x806eb    | 5         | 0.51%   |
| 0x6fd      | 5         | 0.51%   |
| 0x406c3    | 5         | 0.51%   |
| 0x06001119 | 5         | 0.51%   |
| 0x906ed    | 4         | 0.41%   |
| 0x90672    | 4         | 0.41%   |
| 0x206d7    | 4         | 0.41%   |
| 0x206c2    | 4         | 0.41%   |
| 0x08701021 | 4         | 0.41%   |
| 0x08101007 | 4         | 0.41%   |
| 0x010000c8 | 4         | 0.41%   |
| 0xa0671    | 3         | 0.31%   |
| 0xa0653    | 3         | 0.31%   |
| 0x906c0    | 3         | 0.31%   |
| 0x706a8    | 3         | 0.31%   |
| 0x50657    | 3         | 0.31%   |
| 0x30679    | 3         | 0.31%   |
| 0x20655    | 3         | 0.31%   |
| 0x0a50000b | 3         | 0.31%   |
| 0x08600102 | 3         | 0.31%   |
| 0x0800820d | 3         | 0.31%   |
| 0x08001138 | 3         | 0.31%   |
| 0x906eb    | 2         | 0.2%    |
| 0x806f3    | 2         | 0.2%    |
| 0x806c2    | 2         | 0.2%    |
| 0x506ca    | 2         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 221       | 23.07%  |
| Haswell          | 89        | 9.29%   |
| Zen 2            | 66        | 6.89%   |
| Skylake          | 65        | 6.78%   |
| IvyBridge        | 57        | 5.95%   |
| Unknown          | 53        | 5.53%   |
| Zen 3            | 44        | 4.59%   |
| SandyBridge      | 41        | 4.28%   |
| CometLake        | 40        | 4.18%   |
| TigerLake        | 39        | 4.07%   |
| Zen+             | 34        | 3.55%   |
| Silvermont       | 26        | 2.71%   |
| Broadwell        | 25        | 2.61%   |
| Icelake          | 21        | 2.19%   |
| Penryn           | 20        | 2.09%   |
| Zen              | 19        | 1.98%   |
| Westmere         | 10        | 1.04%   |
| Piledriver       | 10        | 1.04%   |
| Goldmont plus    | 9         | 0.94%   |
| Core             | 9         | 0.94%   |
| Alderlake Hybrid | 9         | 0.94%   |
| K10              | 8         | 0.84%   |
| Steamroller      | 5         | 0.52%   |
| Goldmont         | 5         | 0.52%   |
| Bonnell          | 5         | 0.52%   |
| Nehalem          | 4         | 0.42%   |
| Excavator        | 4         | 0.42%   |
| Tremont          | 3         | 0.31%   |
| Puma             | 3         | 0.31%   |
| Sapphire Rapids  | 2         | 0.21%   |
| P6               | 2         | 0.21%   |
| K10 Llano        | 2         | 0.21%   |
| Jaguar           | 2         | 0.21%   |
| Bulldozer        | 2         | 0.21%   |
| Bobcat           | 2         | 0.21%   |
| NetBurst         | 1         | 0.1%    |
| K8 Hammer        | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 568       | 47.37%  |
| Nvidia                           | 329       | 27.44%  |
| AMD                              | 269       | 22.44%  |
| Matrox Electronics Systems       | 14        | 1.17%   |
| ASPEED Technology                | 11        | 0.92%   |
| Zhaoxin                          | 3         | 0.25%   |
| Silicon Integrated Systems [SiS] | 2         | 0.17%   |
| Phytium Technology               | 1         | 0.08%   |
| Loongson Technology              | 1         | 0.08%   |
| Huawei Technologies              | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 44        | 3.6%    |
| Intel UHD Graphics 620                                                                   | 39        | 3.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 39        | 3.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 2.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 2.7%    |
| AMD Cezanne                                                                              | 31        | 2.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 2.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 28        | 2.29%   |
| Intel HD Graphics 630                                                                    | 24        | 1.96%   |
| Intel HD Graphics 530                                                                    | 24        | 1.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 1.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 22        | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 21        | 1.72%   |
| Intel HD Graphics 620                                                                    | 21        | 1.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 19        | 1.55%   |
| Nvidia GP108M [GeForce MX150]                                                            | 16        | 1.31%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 16        | 1.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 1.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 1.23%   |
| Intel HD Graphics 5500                                                                   | 14        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14        | 1.14%   |
| Nvidia GP108M [GeForce MX250]                                                            | 12        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 0.98%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 11        | 0.9%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 11        | 0.9%    |
| Nvidia TU117M [GeForce MX450]                                                            | 10        | 0.82%   |
| Nvidia TU117M                                                                            | 10        | 0.82%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 10        | 0.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 10        | 0.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 0.74%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 9         | 0.74%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 8         | 0.65%   |
| Intel Comet Lake UHD Graphics                                                            | 8         | 0.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 8         | 0.65%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 8         | 0.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 0.65%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 0.57%   |
| Intel UHD Graphics 615                                                                   | 7         | 0.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.57%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 7         | 0.57%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.49%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 6         | 0.49%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 0.49%   |
| Matrox Electronics Systems G200eR2                                                       | 6         | 0.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 0.49%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.49%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 5         | 0.41%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 5         | 0.41%   |
| Intel HD Graphics 615                                                                    | 5         | 0.41%   |
| Intel HD Graphics 500                                                                    | 5         | 0.41%   |
| AMD Rembrandt [Radeon 680M]                                                              | 5         | 0.41%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.33%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 4         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| 1 x Intel                    | 339       | 35.24%  |
| 1 x AMD                      | 189       | 19.65%  |
| Intel + Nvidia               | 176       | 18.3%   |
| 1 x Nvidia                   | 123       | 12.79%  |
| Intel + AMD                  | 39        | 4.05%   |
| AMD + Nvidia                 | 23        | 2.39%   |
| Other                        | 19        | 1.98%   |
| 2 x AMD                      | 13        | 1.35%   |
| 1 x Matrox                   | 12        | 1.25%   |
| 1 x ASPEED                   | 6         | 0.62%   |
| 2 x Nvidia                   | 3         | 0.31%   |
| 2 x Intel                    | 3         | 0.31%   |
| 1 x Zhaoxin                  | 3         | 0.31%   |
| AMD + ASPEED                 | 3         | 0.31%   |
| 1 x SiS                      | 2         | 0.21%   |
| Nvidia + ASPEED              | 2         | 0.21%   |
| AMD + Matrox                 | 2         | 0.21%   |
| 1 x Phytium Technology       | 1         | 0.1%    |
| Nvidia + Huawei Technologies | 1         | 0.1%    |
| 1 x Loongson Technology      | 1         | 0.1%    |
| 1 x Intel + 3 x Nvidia       | 1         | 0.1%    |
| Intel + 2 x Nvidia           | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 717       | 74.15%  |
| Proprietary | 169       | 17.48%  |
| Unknown     | 81        | 8.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 533       | 54.78%  |
| 1.01-2.0   | 131       | 13.46%  |
| 0.01-0.5   | 81        | 8.32%   |
| 0.51-1.0   | 76        | 7.81%   |
| 3.01-4.0   | 60        | 6.17%   |
| 5.01-6.0   | 36        | 3.7%    |
| 7.01-8.0   | 35        | 3.6%    |
| 8.01-16.0  | 10        | 1.03%   |
| 2.01-3.0   | 6         | 0.62%   |
| 24.01-32.0 | 2         | 0.21%   |
| 16.01-24.0 | 2         | 0.21%   |
| 4.01-5.0   | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 116       | 11.95%  |
| AU Optronics            | 97        | 9.99%   |
| LG Display              | 93        | 9.58%   |
| Chimei Innolux          | 91        | 9.37%   |
| Dell                    | 80        | 8.24%   |
| Samsung Electronics     | 53        | 5.46%   |
| Lenovo                  | 53        | 5.46%   |
| AOC                     | 52        | 5.36%   |
| Sharp                   | 36        | 3.71%   |
| Philips                 | 25        | 2.57%   |
| Goldstar                | 21        | 2.16%   |
| Hewlett-Packard         | 20        | 2.06%   |
| CSO                     | 20        | 2.06%   |
| ViewSonic               | 13        | 1.34%   |
| BenQ                    | 12        | 1.24%   |
| PANDA                   | 11        | 1.13%   |
| InfoVision              | 10        | 1.03%   |
| Apple                   | 10        | 1.03%   |
| Acer                    | 10        | 1.03%   |
| Xiaomi                  | 8         | 0.82%   |
| HKC                     | 8         | 0.82%   |
| TMX                     | 5         | 0.51%   |
| SGT                     | 5         | 0.51%   |
| Unknown                 | 4         | 0.41%   |
| Mi                      | 4         | 0.41%   |
| IPS                     | 4         | 0.41%   |
| CHD                     | 4         | 0.41%   |
| RTK                     | 3         | 0.31%   |
| Panasonic               | 3         | 0.31%   |
| LGD                     | 3         | 0.31%   |
| KOIOS                   | 3         | 0.31%   |
| HannStar                | 3         | 0.31%   |
| CHR                     | 3         | 0.31%   |
| Chi Mei Optoelectronics | 3         | 0.31%   |
| BOE Technology Group    | 3         | 0.31%   |
| ASUSTek Computer        | 3         | 0.31%   |
| Ancor Communications    | 3         | 0.31%   |
| TFC                     | 2         | 0.21%   |
| Sony                    | 2         | 0.21%   |
| SKY                     | 2         | 0.21%   |
| NEC Computers           | 2         | 0.21%   |
| LG Electronics          | 2         | 0.21%   |
| Lenovo Group Limited    | 2         | 0.21%   |
| JDI                     | 2         | 0.21%   |
| InnoLux Display         | 2         | 0.21%   |
| Envision Peripherals    | 2         | 0.21%   |
| Eizo                    | 2         | 0.21%   |
| DST                     | 2         | 0.21%   |
| DSC                     | 2         | 0.21%   |
| AGO                     | 2         | 0.21%   |
| Unknown                 | 2         | 0.21%   |
| ZTY                     | 1         | 0.1%    |
| ZLS                     | 1         | 0.1%    |
| Unknown (AAA)           | 1         | 0.1%    |
| TUP                     | 1         | 0.1%    |
| TCL                     | 1         | 0.1%    |
| SUG                     | 1         | 0.1%    |
| SLE                     | 1         | 0.1%    |
| SAC                     | 1         | 0.1%    |
| QSM                     | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 0.9%    |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                     | 7         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 7         | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 7         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 6         | 0.6%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 6         | 0.6%    |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 6         | 0.6%    |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 6         | 0.6%    |
| Dell P2422H DELA1C5 1920x1080 530x300mm 24.0-inch                     | 5         | 0.5%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 5         | 0.5%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 5         | 0.5%    |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 4         | 0.4%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 4         | 0.4%    |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 4         | 0.4%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.4%    |
| Lenovo LT2252p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch             | 4         | 0.4%    |
| InfoVision LCD Monitor IVO061F 1920x1080 344x194mm 15.5-inch          | 4         | 0.4%    |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 4         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 4         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 4         | 0.4%    |
| CHD CHHWJT CHD0030 1920x1080 934x532mm 42.3-inch                      | 4         | 0.4%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 4         | 0.4%    |
| AOC G2790G4 AOC2790 1920x1080 598x336mm 27.0-inch                     | 4         | 0.4%    |
| AOC 2491W AOC2491 1920x1080 521x293mm 23.5-inch                       | 4         | 0.4%    |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch               | 3         | 0.3%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.3%    |
| Samsung Electronics LCD Monitor SEC414C 1366x768 309x174mm 14.0-inch  | 3         | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 3         | 0.3%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 3         | 0.3%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.3%    |
| Panasonic LCD Monitor MEI96A2 3840x2160 382x215mm 17.3-inch           | 3         | 0.3%    |
| Mi Monitor XMI23C3 1920x1080 530x290mm 23.8-inch                      | 3         | 0.3%    |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch          | 3         | 0.3%    |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 3         | 0.3%    |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 3         | 0.3%    |
| Lenovo LEN T2254A LEN60CD 1680x1050 474x296mm 22.0-inch               | 3         | 0.3%    |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 3         | 0.3%    |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                 | 3         | 0.3%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 3         | 0.3%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 3         | 0.3%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 3         | 0.3%    |
| Dell E2216HV DELF06F 1920x1080 476x268mm 21.5-inch                    | 3         | 0.3%    |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1603 1920x1080 355x199mm 16.0-inch      | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 3         | 0.3%    |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 3         | 0.3%    |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 3         | 0.3%    |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 3         | 0.3%    |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 3         | 0.3%    |
| AU Optronics LCD Monitor AUO45ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.3%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 0.3%    |
| AOC G2490W1G4 AOC2490 1920x1080 527x296mm 23.8-inch                   | 3         | 0.3%    |
| Xiaomi Mi TV XMD0002 1920x1080 708x398mm 32.0-inch                    | 2         | 0.2%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2         | 0.2%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.2%    |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch     | 2         | 0.2%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2         | 0.2%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 2         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 484       | 51.99%  |
| 1366x768 (WXGA)    | 105       | 11.28%  |
| 3840x2160 (4K)     | 79        | 8.49%   |
| 2560x1440 (QHD)    | 63        | 6.77%   |
| 2560x1600          | 25        | 2.69%   |
| 1440x900 (WXGA+)   | 25        | 2.69%   |
| 1600x900 (HD+)     | 19        | 2.04%   |
| 1920x1200 (WUXGA)  | 15        | 1.61%   |
| 1680x1050 (WSXGA+) | 13        | 1.4%    |
| 1280x1024 (SXGA)   | 12        | 1.29%   |
| 2160x1440          | 9         | 0.97%   |
| Unknown            | 9         | 0.97%   |
| 3440x1440          | 7         | 0.75%   |
| 2880x1800          | 6         | 0.64%   |
| 1280x800 (WXGA)    | 6         | 0.64%   |
| 3200x2000          | 4         | 0.43%   |
| 2560x1080          | 3         | 0.32%   |
| 2240x1400          | 3         | 0.32%   |
| 1800x1200          | 3         | 0.32%   |
| 3360x1080          | 2         | 0.21%   |
| 3286x1080          | 2         | 0.21%   |
| 3072x1920          | 2         | 0.21%   |
| 3000x2000          | 2         | 0.21%   |
| 2736x1824          | 2         | 0.21%   |
| 2288x1287          | 2         | 0.21%   |
| 2256x1504          | 2         | 0.21%   |
| 2200x1650          | 2         | 0.21%   |
| 2160x1350          | 2         | 0.21%   |
| 1920x1280          | 2         | 0.21%   |
| 1400x1050          | 2         | 0.21%   |
| 1024x768 (XGA)     | 2         | 0.21%   |
| 1024x600           | 2         | 0.21%   |
| 5206x1080          | 1         | 0.11%   |
| 4480x1440          | 1         | 0.11%   |
| 4382x1080          | 1         | 0.11%   |
| 3840x2400          | 1         | 0.11%   |
| 3840x1080          | 1         | 0.11%   |
| 3600x1080          | 1         | 0.11%   |
| 3520x1080          | 1         | 0.11%   |
| 3200x1800 (QHD+)   | 1         | 0.11%   |
| 2880x1920          | 1         | 0.11%   |
| 2800x1752          | 1         | 0.11%   |
| 2520x1680          | 1         | 0.11%   |
| 1920x540           | 1         | 0.11%   |
| 1792x768           | 1         | 0.11%   |
| 1360x768           | 1         | 0.11%   |
| 1280x960           | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 189       | 19.52%  |
| 13      | 145       | 14.98%  |
| 14      | 121       | 12.5%   |
| 23      | 79        | 8.16%   |
| 27      | 68        | 7.02%   |
| 24      | 68        | 7.02%   |
| 21      | 43        | 4.44%   |
| Unknown | 40        | 4.13%   |
| 12      | 32        | 3.31%   |
| 17      | 31        | 3.2%    |
| 16      | 25        | 2.58%   |
| 19      | 19        | 1.96%   |
| 18      | 15        | 1.55%   |
| 31      | 12        | 1.24%   |
| 22      | 11        | 1.14%   |
| 65      | 8         | 0.83%   |
| 25      | 8         | 0.83%   |
| 20      | 8         | 0.83%   |
| 34      | 7         | 0.72%   |
| 11      | 7         | 0.72%   |
| 10      | 6         | 0.62%   |
| 40      | 5         | 0.52%   |
| 63      | 4         | 0.41%   |
| 32      | 3         | 0.31%   |
| 26      | 3         | 0.31%   |
| 142     | 2         | 0.21%   |
| 43      | 2         | 0.21%   |
| 66      | 1         | 0.1%    |
| 54      | 1         | 0.1%    |
| 46      | 1         | 0.1%    |
| 42      | 1         | 0.1%    |
| 37      | 1         | 0.1%    |
| 36      | 1         | 0.1%    |
| 28      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 393       | 41.07%  |
| 501-600        | 207       | 21.63%  |
| 201-300        | 124       | 12.96%  |
| 401-500        | 89        | 9.3%    |
| 351-400        | 44        | 4.6%    |
| Unknown        | 40        | 4.18%   |
| 601-700        | 24        | 2.51%   |
| 1001-1500      | 14        | 1.46%   |
| 701-800        | 10        | 1.04%   |
| 801-900        | 7         | 0.73%   |
| 901-1000       | 3         | 0.31%   |
| More than 2000 | 2         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 672       | 76.62%  |
| 16/10   | 114       | 13%     |
| Unknown | 38        | 4.33%   |
| 3/2     | 24        | 2.74%   |
| 5/4     | 13        | 1.48%   |
| 21/9    | 8         | 0.91%   |
| 4/3     | 5         | 0.57%   |
| 1.00    | 2         | 0.23%   |
| 0.45    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 199       | 20.6%   |
| 101-110        | 195       | 20.19%  |
| 201-250        | 157       | 16.25%  |
| 301-350        | 72        | 7.45%   |
| 71-80          | 71        | 7.35%   |
| 151-200        | 62        | 6.42%   |
| Unknown        | 40        | 4.14%   |
| 61-70          | 26        | 2.69%   |
| 251-300        | 26        | 2.69%   |
| 121-130        | 23        | 2.38%   |
| 351-500        | 22        | 2.28%   |
| More than 1000 | 16        | 1.66%   |
| 111-120        | 15        | 1.55%   |
| 141-150        | 13        | 1.35%   |
| 501-1000       | 11        | 1.14%   |
| 51-60          | 8         | 0.83%   |
| 41-50          | 5         | 0.52%   |
| 91-100         | 5         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 321       | 33.61%  |
| 51-100        | 244       | 25.55%  |
| 101-120       | 168       | 17.59%  |
| 161-240       | 132       | 13.82%  |
| Unknown       | 40        | 4.19%   |
| More than 240 | 35        | 3.66%   |
| 1-50          | 15        | 1.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 741       | 76.08%  |
| 2     | 133       | 13.66%  |
| 0     | 91        | 9.34%   |
| 3     | 9         | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 539       | 38.75%  |
| Realtek Semiconductor            | 519       | 37.31%  |
| Qualcomm Atheros                 | 119       | 8.55%   |
| Broadcom                         | 41        | 2.95%   |
| MediaTek                         | 22        | 1.58%   |
| Broadcom Limited                 | 20        | 1.44%   |
| Ralink Technology                | 18        | 1.29%   |
| Huawei Technologies              | 13        | 0.93%   |
| Xiaomi                           | 12        | 0.86%   |
| ASIX Electronics                 | 12        | 0.86%   |
| Marvell Technology Group         | 8         | 0.58%   |
| Microsoft                        | 6         | 0.43%   |
| Ralink                           | 5         | 0.36%   |
| Qualcomm                         | 4         | 0.29%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.22%   |
| TP-Link                          | 3         | 0.22%   |
| Samsung Electronics              | 3         | 0.22%   |
| Realtek                          | 3         | 0.22%   |
| Quectel Wireless Solutions       | 3         | 0.22%   |
| Qualcomm Atheros Communications  | 3         | 0.22%   |
| Dell                             | 3         | 0.22%   |
| Silicon Integrated Systems [SiS] | 2         | 0.14%   |
| Sierra Wireless                  | 2         | 0.14%   |
| OPPO Electronics                 | 2         | 0.14%   |
| NetGear                          | 2         | 0.14%   |
| IBM                              | 2         | 0.14%   |
| D-Link                           | 2         | 0.14%   |
| Aquantia                         | 2         | 0.14%   |
| Wilocity                         | 1         | 0.07%   |
| vivo                             | 1         | 0.07%   |
| ST-Ericsson                      | 1         | 0.07%   |
| Shenzhen Goodix Technology       | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.07%   |
| Oculus VR                        | 1         | 0.07%   |
| Nvidia                           | 1         | 0.07%   |
| NetXen Incorporated              | 1         | 0.07%   |
| Meizu                            | 1         | 0.07%   |
| Loongson Technology              | 1         | 0.07%   |
| ICS Advent                       | 1         | 0.07%   |
| Hewlett-Packard                  | 1         | 0.07%   |
| Fibocom                          | 1         | 0.07%   |
| Exar                             | 1         | 0.07%   |
| DisplayLink                      | 1         | 0.07%   |
| D-Link System                    | 1         | 0.07%   |
| Attansic Technology              | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 344       | 21.22%  |
| Intel Wi-Fi 6 AX200                                               | 72        | 4.44%   |
| Intel Wireless 8265 / 8275                                        | 48        | 2.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45        | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 40        | 2.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 2.04%   |
| Intel Wi-Fi 6 AX201                                               | 28        | 1.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 28        | 1.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 24        | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 24        | 1.48%   |
| Intel Wireless 7265                                               | 24        | 1.48%   |
| Intel Wireless 7260                                               | 21        | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 1.23%   |
| Intel Wireless 8260                                               | 18        | 1.11%   |
| Intel Wireless 3165                                               | 18        | 1.11%   |
| Intel I211 Gigabit Network Connection                             | 18        | 1.11%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 15        | 0.93%   |
| Realtek 802.11ac NIC                                              | 14        | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 14        | 0.86%   |
| Ralink MT7601U Wireless Adapter                                   | 12        | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 12        | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 12        | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 12        | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 11        | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 10        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.62%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 9         | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 9         | 0.56%   |
| Intel Wireless-AC 9260                                            | 9         | 0.56%   |
| Intel Ethernet Connection (10) I219-V                             | 9         | 0.56%   |
| Huawei JNY-LX1                                                    | 9         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 0.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 0.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.49%   |
| Intel Wireless 3160                                               | 8         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.43%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 7         | 0.43%   |
| Intel I350 Gigabit Network Connection                             | 7         | 0.43%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.43%   |
| Intel Ethernet Connection (12) I219-V                             | 7         | 0.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 0.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 6         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.37%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                | 6         | 0.37%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.37%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 0.37%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 434       | 56%     |
| Realtek Semiconductor           | 130       | 16.77%  |
| Qualcomm Atheros                | 93        | 12%     |
| Broadcom                        | 26        | 3.35%   |
| MediaTek                        | 22        | 2.84%   |
| Ralink Technology               | 18        | 2.32%   |
| Broadcom Limited                | 15        | 1.94%   |
| Ralink                          | 5         | 0.65%   |
| Xiaomi                          | 3         | 0.39%   |
| TP-Link                         | 3         | 0.39%   |
| Realtek                         | 3         | 0.39%   |
| Quectel Wireless Solutions      | 3         | 0.39%   |
| Qualcomm Atheros Communications | 3         | 0.39%   |
| Sierra Wireless                 | 2         | 0.26%   |
| Qualcomm                        | 2         | 0.26%   |
| NetGear                         | 2         | 0.26%   |
| Microsoft                       | 2         | 0.26%   |
| Marvell Technology Group        | 2         | 0.26%   |
| Dell                            | 2         | 0.26%   |
| D-Link                          | 2         | 0.26%   |
| Wilocity                        | 1         | 0.13%   |
| Hewlett-Packard                 | 1         | 0.13%   |
| D-Link System                   | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 72        | 9.22%   |
| Intel Wireless 8265 / 8275                                              | 48        | 6.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 40        | 5.12%   |
| Intel Wi-Fi 6 AX201                                                     | 28        | 3.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 3.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 3.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 24        | 3.07%   |
| Intel Wireless 7265                                                     | 24        | 3.07%   |
| Intel Wireless 7260                                                     | 21        | 2.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 20        | 2.56%   |
| Intel Wireless 8260                                                     | 18        | 2.3%    |
| Intel Wireless 3165                                                     | 18        | 2.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 1.92%   |
| Realtek 802.11ac NIC                                                    | 14        | 1.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 14        | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 1.79%   |
| Ralink MT7601U Wireless Adapter                                         | 12        | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 12        | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 1.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 11        | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 1.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 1.15%   |
| Intel Wireless-AC 9260                                                  | 9         | 1.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.02%   |
| Intel Wireless 3160                                                     | 8         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 0.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 0.77%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 6         | 0.77%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 6         | 0.77%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)               | 5         | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 5         | 0.64%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.64%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.51%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 0.51%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 4         | 0.51%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 4         | 0.51%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 4         | 0.51%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 4         | 0.51%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.51%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 0.51%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                       | 3         | 0.38%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                   | 3         | 0.38%   |
| Realtek Realtek Network controller                                      | 3         | 0.38%   |
| Realtek 802.11n NIC                                                     | 3         | 0.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 0.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.38%   |
| Quectel Wireless Solutions Quectel EM05-CE                              | 3         | 0.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.38%   |
| MediaTek 802.11 n WLAN                                                  | 3         | 0.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 0.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 446       | 56.17%  |
| Intel                            | 231       | 29.09%  |
| Qualcomm Atheros                 | 33        | 4.16%   |
| Broadcom                         | 16        | 2.02%   |
| Huawei Technologies              | 12        | 1.51%   |
| ASIX Electronics                 | 12        | 1.51%   |
| Xiaomi                           | 9         | 1.13%   |
| Marvell Technology Group         | 6         | 0.76%   |
| Broadcom Limited                 | 5         | 0.63%   |
| Samsung Electronics              | 3         | 0.38%   |
| Microsoft                        | 3         | 0.38%   |
| Silicon Integrated Systems [SiS] | 2         | 0.25%   |
| OPPO Electronics                 | 2         | 0.25%   |
| IBM                              | 2         | 0.25%   |
| Aquantia                         | 2         | 0.25%   |
| Qualcomm                         | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.13%   |
| Nvidia                           | 1         | 0.13%   |
| NetXen Incorporated              | 1         | 0.13%   |
| Loongson Technology              | 1         | 0.13%   |
| ICS Advent                       | 1         | 0.13%   |
| Fibocom                          | 1         | 0.13%   |
| DisplayLink                      | 1         | 0.13%   |
| Attansic Technology              | 1         | 0.13%   |
| Apple                            | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 344       | 41.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45        | 5.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 3.03%   |
| Intel I211 Gigabit Network Connection                             | 18        | 2.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 2.06%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 1.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 12        | 1.45%   |
| Intel Ethernet Controller I225-V                                  | 10        | 1.21%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 1.21%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 1.21%   |
| Intel Ethernet Connection (10) I219-V                             | 9         | 1.09%   |
| Huawei JNY-LX1                                                    | 9         | 1.09%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.85%   |
| Intel I350 Gigabit Network Connection                             | 7         | 0.85%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.85%   |
| Intel Ethernet Connection (12) I219-V                             | 7         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.73%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.73%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 5         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.61%   |
| Intel Ethernet Connection X722 for 1GbE                           | 5         | 0.61%   |
| Intel Ethernet Connection (3) I219-LM                             | 5         | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.61%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 5         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.61%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 0.61%   |
| ASIX AX88772B                                                     | 5         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.48%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.36%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 3         | 0.36%   |
| Intel Ethernet Controller I225-LM                                 | 3         | 0.36%   |
| Intel Ethernet Connection X722                                    | 3         | 0.36%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.36%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.36%   |
| Intel 82576 Gigabit Network Connection                            | 3         | 0.36%   |
| Huawei HNS GE/10GE/25GE RDMA Network Controller                   | 3         | 0.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.36%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.24%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.24%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.24%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.24%   |
| OPPO 9R                                                           | 2         | 0.24%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.24%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.24%   |
| Intel Ethernet controller                                         | 2         | 0.24%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.24%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 759       | 50.03%  |
| WiFi     | 744       | 49.04%  |
| Unknown  | 8         | 0.53%   |
| Modem    | 6         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 564       | 58.93%  |
| Ethernet | 392       | 40.96%  |
| Unknown  | 1         | 0.1%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 481       | 50.26%  |
| 1     | 393       | 41.07%  |
| 0     | 40        | 4.18%   |
| 3     | 27        | 2.82%   |
| 4     | 10        | 1.04%   |
| 6     | 4         | 0.42%   |
| 8     | 1         | 0.1%    |
| 5     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 847       | 87.14%  |
| Yes  | 125       | 12.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 377       | 59.94%  |
| Realtek Semiconductor           | 53        | 8.43%   |
| Qualcomm Atheros Communications | 48        | 7.63%   |
| Cambridge Silicon Radio         | 34        | 5.41%   |
| Realtek                         | 25        | 3.97%   |
| Broadcom                        | 20        | 3.18%   |
| Foxconn / Hon Hai               | 16        | 2.54%   |
| IMC Networks                    | 9         | 1.43%   |
| Lite-On Technology              | 8         | 1.27%   |
| Apple                           | 8         | 1.27%   |
| ASUSTek Computer                | 5         | 0.79%   |
| Opticis                         | 4         | 0.64%   |
| Dell                            | 4         | 0.64%   |
| Ralink                          | 3         | 0.48%   |
| Foxconn International           | 3         | 0.48%   |
| Toshiba                         | 2         | 0.32%   |
| Taiyo Yuden                     | 2         | 0.32%   |
| MediaTek                        | 2         | 0.32%   |
| Marvell Semiconductor           | 2         | 0.32%   |
| Hewlett-Packard                 | 2         | 0.32%   |
| Alps Electric                   | 2         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 137       | 21.78%  |
| Intel AX201 Bluetooth                                 | 75        | 11.92%  |
| Intel AX200 Bluetooth                                 | 69        | 10.97%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 54        | 8.59%   |
| Realtek Bluetooth Radio                               | 37        | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                    | 34        | 5.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 34        | 5.41%   |
| Realtek Bluetooth Radio                               | 25        | 3.97%   |
| Intel AX210 Bluetooth                                 | 12        | 1.91%   |
| Realtek  Bluetooth 4.2 Adapter                        | 8         | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 8         | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 7         | 1.11%   |
| Foxconn / Hon Hai Wireless_Device                     | 7         | 1.11%   |
| Realtek RTL8723B Bluetooth                            | 6         | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 6         | 0.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 0.95%   |
| Intel Bluetooth Device                                | 6         | 0.95%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 5         | 0.79%   |
| Broadcom BCM2045B (BDC-2.1)                           | 5         | 0.79%   |
| Opticis Bluetooth Radio                               | 4         | 0.64%   |
| Lite-On Bluetooth Device                              | 4         | 0.64%   |
| Intel Wireless-AC 3168 Bluetooth                      | 4         | 0.64%   |
| IMC Networks Bluetooth Device                         | 4         | 0.64%   |
| Foxconn / Hon Hai Bluetooth Device                    | 4         | 0.64%   |
| Apple Bluetooth Host Controller                       | 4         | 0.64%   |
| Ralink RT3290 Bluetooth                               | 3         | 0.48%   |
| IMC Networks Wireless_Device                          | 3         | 0.48%   |
| Foxconn International BCM43142A0 Bluetooth module     | 3         | 0.48%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 3         | 0.48%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 3         | 0.48%   |
| Apple Bluetooth USB Host Controller                   | 3         | 0.48%   |
| Taiyo Yuden Bluetooth Device                          | 2         | 0.32%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 2         | 0.32%   |
| MediaTek Wireless_Device                              | 2         | 0.32%   |
| Marvell Bluetooth and Wireless LAN Composite          | 2         | 0.32%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]           | 2         | 0.32%   |
| IMC Networks Bluetooth Radio                          | 2         | 0.32%   |
| HP Broadcom 2070 Bluetooth Combo                      | 2         | 0.32%   |
| Foxconn / Hon Hai BCM20702A0                          | 2         | 0.32%   |
| Dell DW375 Bluetooth Module                           | 2         | 0.32%   |
| Broadcom Bluetooth 3.0 Dongle                         | 2         | 0.32%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2         | 0.32%   |
| Broadcom BCM20702A0 Bluetooth                         | 2         | 0.32%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2         | 0.32%   |
| Toshiba RT Bluetooth Radio                            | 1         | 0.16%   |
| Toshiba Atheros AR3012 Bluetooth                      | 1         | 0.16%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.16%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 1         | 0.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1         | 0.16%   |
| Lite-On Atheros Bluetooth                             | 1         | 0.16%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device       | 1         | 0.16%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 0.16%   |
| Foxconn / Hon Hai BCM2045A0                           | 1         | 0.16%   |
| Dell Wireless 370 Bluetooth Mini-card                 | 1         | 0.16%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.16%   |
| Broadcom HP Portable SoftSailing                      | 1         | 0.16%   |
| Broadcom BCM2070 Bluetooth Device                     | 1         | 0.16%   |
| Broadcom BCM2046 Bluetooth Device                     | 1         | 0.16%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1         | 0.16%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1         | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 664       | 55.7%   |
| AMD                                          | 265       | 22.23%  |
| Nvidia                                       | 201       | 16.86%  |
| C-Media Electronics                          | 9         | 0.76%   |
| Realtek Semiconductor                        | 5         | 0.42%   |
| XMOS                                         | 4         | 0.34%   |
| Creative Labs                                | 4         | 0.34%   |
| Apple                                        | 4         | 0.34%   |
| Zhaoxin                                      | 3         | 0.25%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.25%   |
| Huawei Technologies                          | 3         | 0.25%   |
| Generalplus Technology                       | 3         | 0.25%   |
| Texas Instruments                            | 2         | 0.17%   |
| Dell                                         | 2         | 0.17%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.08%   |
| Unknown                                      | 1         | 0.08%   |
| TerraTec Electronic                          | 1         | 0.08%   |
| Specialix                                    | 1         | 0.08%   |
| Sony                                         | 1         | 0.08%   |
| Sennheiser Communications                    | 1         | 0.08%   |
| Polycom                                      | 1         | 0.08%   |
| Phytium Technology                           | 1         | 0.08%   |
| NXP Semiconductors                           | 1         | 0.08%   |
| Loongson Technology                          | 1         | 0.08%   |
| JMTek                                        | 1         | 0.08%   |
| Giga-Byte Technology                         | 1         | 0.08%   |
| Fry's Electronics                            | 1         | 0.08%   |
| ESI                                          | 1         | 0.08%   |
| Creative Technology                          | 1         | 0.08%   |
| Cambridge Silicon Radio                      | 1         | 0.08%   |
| BY EDIFIER                                   | 1         | 0.08%   |
| AudioQuest                                   | 1         | 0.08%   |
| Atmel                                        | 1         | 0.08%   |
| ACTIONS                                      | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 136       | 9.48%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 94        | 6.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 66        | 4.6%    |
| Intel Cannon Lake PCH cAVS                                                                        | 54        | 3.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 53        | 3.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 47        | 3.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 42        | 2.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 39        | 2.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 38        | 2.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 36        | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 34        | 2.37%   |
| Intel 200 Series PCH HD Audio                                                                     | 32        | 2.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 30        | 2.09%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 24        | 1.67%   |
| Intel 8 Series HD Audio Controller                                                                | 24        | 1.67%   |
| Intel Broadwell-U Audio Controller                                                                | 22        | 1.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 1.46%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 21        | 1.46%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 20        | 1.39%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 20        | 1.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 19        | 1.32%   |
| AMD FCH Azalia Controller                                                                         | 19        | 1.32%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 18        | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 1.18%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 1.18%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 17        | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 15        | 1.05%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 15        | 1.05%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 15        | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 15        | 1.05%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 15        | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 14        | 0.98%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 0.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 11        | 0.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 10        | 0.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 0.7%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 9         | 0.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 0.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 0.63%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 8         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 0.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 7         | 0.49%   |
| Intel Lewisburg MROM 0                                                                            | 7         | 0.49%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 0.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 0.49%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 7         | 0.49%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 7         | 0.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.42%   |
| Nvidia Audio device                                                                               | 6         | 0.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 0.42%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 0.42%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 0.42%   |
| Realtek Semiconductor USB Audio                                                                   | 5         | 0.35%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 5         | 0.35%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 5         | 0.35%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 5         | 0.35%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 5         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 186       | 29.02%  |
| SK hynix            | 124       | 19.34%  |
| Kingston            | 110       | 17.16%  |
| Micron Technology   | 66        | 10.3%   |
| Unknown             | 37        | 5.77%   |
| A-DATA Technology   | 24        | 3.74%   |
| Ramaxel Technology  | 19        | 2.96%   |
| Crucial             | 13        | 2.03%   |
| Corsair             | 7         | 1.09%   |
| Elpida              | 6         | 0.94%   |
| Transcend           | 5         | 0.78%   |
| Unknown             | 5         | 0.78%   |
| Team                | 4         | 0.62%   |
| Unknown (ABCD)      | 3         | 0.47%   |
| G.Skill             | 3         | 0.47%   |
| Apacer              | 3         | 0.47%   |
| Lenovo              | 2         | 0.31%   |
| Kingmax             | 2         | 0.31%   |
| Unknown (08C8)      | 1         | 0.16%   |
| Unknown (08B5)      | 1         | 0.16%   |
| tigo                | 1         | 0.16%   |
| Thermaltake         | 1         | 0.16%   |
| Shenzhen WODPOSIT   | 1         | 0.16%   |
| Shenzhen Longsys    | 1         | 0.16%   |
| SHARETRONIC         | 1         | 0.16%   |
| Ramsta              | 1         | 0.16%   |
| Nanya Technology    | 1         | 0.16%   |
| MTASE               | 1         | 0.16%   |
| Mircon              | 1         | 0.16%   |
| MAXSUN              | 1         | 0.16%   |
| Lexar Co Limited    | 1         | 0.16%   |
| KLEVV               | 1         | 0.16%   |
| KINGBANK            | 1         | 0.16%   |
| Kimtigo             | 1         | 0.16%   |
| Juhor               | 1         | 0.16%   |
| JEDEC ID: 0000h     | 1         | 0.16%   |
| GLOWAY              | 1         | 0.16%   |
| GeIL                | 1         | 0.16%   |
| Essencore           | 1         | 0.16%   |
| 06F104B306F1        | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 11        | 1.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 9         | 1.3%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s        | 8         | 1.15%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 6         | 0.86%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 6         | 0.86%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s              | 6         | 0.86%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 5         | 0.72%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 5         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 0.72%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 5         | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 5         | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s      | 5         | 0.72%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                | 5         | 0.72%   |
| Unknown                                                             | 5         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.58%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB Row Of Chips DDR4 2667MT/s     | 4         | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 0.58%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 4         | 0.58%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.58%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.58%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.58%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s         | 4         | 0.58%   |
| Samsung RAM 6478545886 16GB DIMM DDR4 2668MT/s                      | 4         | 0.58%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 4         | 0.58%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 4         | 0.58%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s         | 4         | 0.58%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 4         | 0.58%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s             | 4         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 0.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s     | 3         | 0.43%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.43%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 3         | 0.43%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 3         | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 0.43%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 3         | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 0.43%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 3         | 0.43%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 0.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.43%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s                | 3         | 0.43%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 3         | 0.43%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s        | 3         | 0.43%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s           | 3         | 0.43%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 3         | 0.43%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 3         | 0.43%   |
| Kingston RAM TF32D4U2S1MEH-8 8GB DIMM DDR4 3200MT/s                 | 3         | 0.43%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                | 3         | 0.43%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s             | 3         | 0.43%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s               | 3         | 0.43%   |
| Kingston RAM 99U5469-041.A00LF 4GB SODIMM DDR3 1600MT/s             | 3         | 0.43%   |
| Kingston RAM 99P5471-033.A00LF 8GB DIMM DDR3 1600MT/s               | 3         | 0.43%   |
| Kingston RAM 6478545886 16GB DIMM DDR4 2400MT/s                     | 3         | 0.43%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                 | 2         | 0.29%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 2         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 318       | 55.59%  |
| DDR3    | 154       | 26.92%  |
| LPDDR3  | 33        | 5.77%   |
| LPDDR4  | 28        | 4.9%    |
| Unknown | 16        | 2.8%    |
| SDRAM   | 10        | 1.75%   |
| DDR2    | 8         | 1.4%    |
| DDR5    | 3         | 0.52%   |
| LPDDR5  | 1         | 0.17%   |
| DDR     | 1         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 308       | 53.75%  |
| DIMM         | 160       | 27.92%  |
| Row Of Chips | 101       | 17.63%  |
| Chip         | 3         | 0.52%   |
| Unknown      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 263       | 43.54%  |
| 4096  | 158       | 26.16%  |
| 16384 | 108       | 17.88%  |
| 2048  | 36        | 5.96%   |
| 32768 | 27        | 4.47%   |
| 1024  | 8         | 1.32%   |
| 65536 | 3         | 0.5%    |
| 512   | 1         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 116       | 18.99%  |
| 3200    | 112       | 18.33%  |
| 1600    | 110       | 18%     |
| 2400    | 44        | 7.2%    |
| 2133    | 38        | 6.22%   |
| 1333    | 26        | 4.26%   |
| 1867    | 18        | 2.95%   |
| 4267    | 16        | 2.62%   |
| 2666    | 15        | 2.45%   |
| 3600    | 12        | 1.96%   |
| 800     | 10        | 1.64%   |
| 4800    | 9         | 1.47%   |
| 1334    | 7         | 1.15%   |
| 3266    | 5         | 0.82%   |
| 2933    | 5         | 0.82%   |
| 1066    | 5         | 0.82%   |
| Unknown | 5         | 0.82%   |
| 4266    | 4         | 0.65%   |
| 3733    | 4         | 0.65%   |
| 3466    | 4         | 0.65%   |
| 2668    | 4         | 0.65%   |
| 1866    | 4         | 0.65%   |
| 1067    | 4         | 0.65%   |
| 667     | 4         | 0.65%   |
| 8400    | 3         | 0.49%   |
| 4199    | 3         | 0.49%   |
| 3400    | 3         | 0.49%   |
| 3000    | 3         | 0.49%   |
| 6400    | 2         | 0.33%   |
| 2800    | 2         | 0.33%   |
| 1800    | 2         | 0.33%   |
| 266     | 2         | 0.33%   |
| 4133    | 1         | 0.16%   |
| 3800    | 1         | 0.16%   |
| 3500    | 1         | 0.16%   |
| 3467    | 1         | 0.16%   |
| 2200    | 1         | 0.16%   |
| 2187    | 1         | 0.16%   |
| 2048    | 1         | 0.16%   |
| 533     | 1         | 0.16%   |
| 400     | 1         | 0.16%   |
| 333     | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Hewlett-Packard                    | 3         | 42.86%  |
| Canon                              | 2         | 28.57%  |
| Brother Industries                 | 1         | 14.29%  |
| BeiJing LanXum Computer Technology | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                        | 2         | 28.57%  |
| HP Officejet 4500 G510g-m                               | 1         | 14.29%  |
| Canon PIXMA MP280                                       | 1         | 14.29%  |
| Canon iP1100 series                                     | 1         | 14.29%  |
| Brother HL-5440D series                                 | 1         | 14.29%  |
| BeiJing LanXum Technology Black and White Laser Printer | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 107       | 19.96%  |
| IMC Networks                           | 84        | 15.67%  |
| Acer                                   | 58        | 10.82%  |
| Realtek Semiconductor                  | 38        | 7.09%   |
| Microdia                               | 36        | 6.72%   |
| Sunplus Innovation Technology          | 33        | 6.16%   |
| Quanta                                 | 28        | 5.22%   |
| Cheng Uei Precision Industry (Foxlink) | 27        | 5.04%   |
| Syntek                                 | 20        | 3.73%   |
| Suyin                                  | 15        | 2.8%    |
| Lite-On Technology                     | 12        | 2.24%   |
| Luxvisions Innotech Limited            | 10        | 1.87%   |
| Logitech                               | 9         | 1.68%   |
| Apple                                  | 9         | 1.68%   |
| Alcor Micro                            | 8         | 1.49%   |
| Silicon Motion                         | 6         | 1.12%   |
| Ricoh                                  | 4         | 0.75%   |
| Z-Star Microelectronics                | 3         | 0.56%   |
| Lenovo                                 | 3         | 0.56%   |
| Importek                               | 3         | 0.56%   |
| SN0002                                 | 2         | 0.37%   |
| Nebraska Furniture Mart                | 2         | 0.37%   |
| Google                                 | 2         | 0.37%   |
| GEMBIRD                                | 2         | 0.37%   |
| Y Media                                | 1         | 0.19%   |
| Unknown                                | 1         | 0.19%   |
| U0AS01A-0                              | 1         | 0.19%   |
| SunplusIT                              | 1         | 0.19%   |
| Sonix Technology                       | 1         | 0.19%   |
| Primax Electronics                     | 1         | 0.19%   |
| Mitsumi                                | 1         | 0.19%   |
| Microsoft                              | 1         | 0.19%   |
| MacroSilicon                           | 1         | 0.19%   |
| icSpring                               | 1         | 0.19%   |
| Goodong Industry                       | 1         | 0.19%   |
| Genesys Logic                          | 1         | 0.19%   |
| Cypress Semiconductor                  | 1         | 0.19%   |
| Cubeternet                             | 1         | 0.19%   |
| ARC International                      | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 46        | 8.49%   |
| IMC Networks Integrated Camera                                             | 34        | 6.27%   |
| Acer Integrated Camera                                                     | 25        | 4.61%   |
| Microdia Integrated_Webcam_HD                                              | 23        | 4.24%   |
| IMC Networks HD Camera                                                     | 19        | 3.51%   |
| Syntek Integrated Camera                                                   | 13        | 2.4%    |
| Chicony HD Webcam                                                          | 13        | 2.4%    |
| Realtek Integrated_Webcam_HD                                               | 12        | 2.21%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam               | 12        | 2.21%   |
| Sunplus Integrated_Webcam_HD                                               | 11        | 2.03%   |
| IMC Networks ov9734_azurewave_camera                                       | 8         | 1.48%   |
| Quanta hm1091_techfront                                                    | 7         | 1.29%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 7         | 1.29%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 7         | 1.29%   |
| Sunplus HD WebCam                                                          | 6         | 1.11%   |
| Realtek Integrated Webcam                                                  | 6         | 1.11%   |
| Quanta HP HD Camera                                                        | 6         | 1.11%   |
| Quanta HD User Facing                                                      | 6         | 1.11%   |
| Luxvisions Innotech Limited Integrated Camera                              | 6         | 1.11%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 6         | 1.11%   |
| Acer BisonCam, NB Pro                                                      | 6         | 1.11%   |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 5         | 0.92%   |
| Silicon Motion 300k Pixel Camera                                           | 5         | 0.92%   |
| Realtek HP Wide Vision HD Camera                                           | 5         | 0.92%   |
| Lite-On Integrated Camera                                                  | 5         | 0.92%   |
| Acer Lenovo EasyCamera                                                     | 5         | 0.92%   |
| Syntek Lenovo EasyCamera                                                   | 4         | 0.74%   |
| IMC Networks Lenovo EasyCamera                                             | 4         | 0.74%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 4         | 0.74%   |
| Chicony Integrated Camera (1280x720@30)                                    | 4         | 0.74%   |
| Chicony HP Wide Vision HD Camera                                           | 4         | 0.74%   |
| Chicony HP HD Camera                                                       | 4         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 0.74%   |
| Alcor Micro USB 2.0 Camera                                                 | 4         | 0.74%   |
| Acer SunplusIT Integrated Camera                                           | 4         | 0.74%   |
| Suyin 1.3M HD WebCam                                                       | 3         | 0.55%   |
| Sunplus HP Wide Vision HD                                                  | 3         | 0.55%   |
| Realtek USB Camera                                                         | 3         | 0.55%   |
| Microdia Webcam Vitade AF                                                  | 3         | 0.55%   |
| Logitech HD Pro Webcam C920                                                | 3         | 0.55%   |
| Lite-On HP Wide Vision HD Camera                                           | 3         | 0.55%   |
| Lite-On HP HD Camera                                                       | 3         | 0.55%   |
| Chicony USB 2.0 Camera                                                     | 3         | 0.55%   |
| Chicony EasyCamera                                                         | 3         | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 3         | 0.55%   |
| Acer ThinkPad Integrated Camera                                            | 3         | 0.55%   |
| Acer HD Webcam                                                             | 3         | 0.55%   |
| Acer BisonCam,NB Pro                                                       | 3         | 0.55%   |
| Syntek EasyCamera                                                          | 2         | 0.37%   |
| Suyin Lenovo EasyCamera                                                    | 2         | 0.37%   |
| Suyin Integrated_Webcam_HD                                                 | 2         | 0.37%   |
| Suyin Integrated Webcam                                                    | 2         | 0.37%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 2         | 0.37%   |
| Sunplus Integrated_Webcam_FHD                                              | 2         | 0.37%   |
| Realtek Lenovo EasyCamera                                                  | 2         | 0.37%   |
| Quanta ov9734_techfront_camera                                             | 2         | 0.37%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 0.37%   |
| Quanta HD Webcam                                                           | 2         | 0.37%   |
| Nebraska Furniture Mart USB 2.0 PC cam                                     | 2         | 0.37%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 2         | 0.37%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 53        | 33.54%  |
| Validity Sensors           | 40        | 25.32%  |
| Synaptics                  | 40        | 25.32%  |
| Elan Microelectronics      | 11        | 6.96%   |
| Upek                       | 8         | 5.06%   |
| AuthenTec                  | 3         | 1.9%    |
| LighTuning Technology      | 2         | 1.27%   |
| STMicroelectronics         | 1         | 0.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 28        | 17.72%  |
| Shenzhen Goodix Fingerprint Reader                                         | 23        | 14.56%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 12.66%  |
| Elan ELAN:Fingerprint                                                      | 10        | 6.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 5.7%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 5.06%   |
| Unknown                                                                    | 8         | 5.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 4.43%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 3.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 3.16%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.53%   |
| Validity Sensors VFS491                                                    | 3         | 1.9%    |
| Synaptics WBDI Device                                                      | 3         | 1.9%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.27%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 1.27%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.27%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.27%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.27%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.63%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.63%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.63%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.63%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.63%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.63%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.63%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.63%   |
| AuthenTec AES2810                                                          | 1         | 0.63%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 12        | 70.59%  |
| Clay Logic  | 2         | 11.76%  |
| Alcor Micro | 2         | 11.76%  |
| Upek        | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 5         | 29.41%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 17.65%  |
| Clay Logic CanoKey Pigeon                                                    | 2         | 11.76%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 11.76%  |
| Broadcom 58200                                                               | 2         | 11.76%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 11.76%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 579       | 59.02%  |
| 1     | 313       | 31.91%  |
| 2     | 59        | 6.01%   |
| 4     | 11        | 1.12%   |
| 3     | 11        | 1.12%   |
| 5     | 5         | 0.51%   |
| 8     | 2         | 0.2%    |
| 6     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 155       | 30.21%  |
| Graphics card            | 122       | 23.78%  |
| Net/wireless             | 56        | 10.92%  |
| Communication controller | 40        | 7.8%    |
| Multimedia controller    | 29        | 5.65%   |
| Unassigned class         | 23        | 4.48%   |
| Sound                    | 22        | 4.29%   |
| Bluetooth                | 17        | 3.31%   |
| Chipcard                 | 15        | 2.92%   |
| Camera                   | 11        | 2.14%   |
| Network                  | 6         | 1.17%   |
| Net/ethernet             | 6         | 1.17%   |
| Storage/raid             | 3         | 0.58%   |
| Storage                  | 3         | 0.58%   |
| Card reader              | 3         | 0.58%   |
| Storage/ata              | 1         | 0.19%   |
| Modem                    | 1         | 0.19%   |

