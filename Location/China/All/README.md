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

Total: 2009

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [dad31fab00](https://linux-hardware.org/?probe=dad31fab00) | Aug 12, 2023 |
| Unknown       | Unknown                     | Soc         | [a28cd220cd](https://linux-hardware.org/?probe=a28cd220cd) | Aug 12, 2023 |
| Unknown       | Unknown                     | Soc         | [f62d9a8a9a](https://linux-hardware.org/?probe=f62d9a8a9a) | Aug 12, 2023 |
| Jumper        | EZpad                       | Notebook    | [5fa2e934c3](https://linux-hardware.org/?probe=5fa2e934c3) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [a064a2d5fd](https://linux-hardware.org/?probe=a064a2d5fd) | Aug 11, 2023 |
| TYAN Compu... | S8030GM2NE                  | Server      | [bc9cacebe8](https://linux-hardware.org/?probe=bc9cacebe8) | Aug 11, 2023 |
| TYAN Compu... | S8030GM2NE                  | Server      | [99458c04da](https://linux-hardware.org/?probe=99458c04da) | Aug 10, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [19cadaab1b](https://linux-hardware.org/?probe=19cadaab1b) | Aug 10, 2023 |
| YANYU         | EPIC-C57                    | Desktop     | [6d42c0f9af](https://linux-hardware.org/?probe=6d42c0f9af) | Aug 10, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [f4dd9cbbbd](https://linux-hardware.org/?probe=f4dd9cbbbd) | Aug 10, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [385c88301b](https://linux-hardware.org/?probe=385c88301b) | Aug 10, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [4a1def29d3](https://linux-hardware.org/?probe=4a1def29d3) | Aug 09, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [d8939be040](https://linux-hardware.org/?probe=d8939be040) | Aug 06, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| GMKtec        | NucBox K4                   | Desktop     | [64b27a1390](https://linux-hardware.org/?probe=64b27a1390) | Aug 05, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [ca109297da](https://linux-hardware.org/?probe=ca109297da) | Aug 05, 2023 |
| HP            | ZHAN 99 Mobile Workstati... | Notebook    | [b3422c4e37](https://linux-hardware.org/?probe=b3422c4e37) | Aug 04, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [2d4fc6f4ce](https://linux-hardware.org/?probe=2d4fc6f4ce) | Aug 03, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [d74aab937a](https://linux-hardware.org/?probe=d74aab937a) | Aug 02, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [8918c544fe](https://linux-hardware.org/?probe=8918c544fe) | Aug 01, 2023 |
| MECHREVO      | WUJIE 14                    | Notebook    | [e6c48375f0](https://linux-hardware.org/?probe=e6c48375f0) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [216622d3d0](https://linux-hardware.org/?probe=216622d3d0) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [96f70f73b1](https://linux-hardware.org/?probe=96f70f73b1) | Jul 28, 2023 |
| MECHREVO      | WUJIE 14                    | Notebook    | [89b0f29570](https://linux-hardware.org/?probe=89b0f29570) | Jul 28, 2023 |
| Google        | Atlas                       | Notebook    | [c3f0326575](https://linux-hardware.org/?probe=c3f0326575) | Jul 28, 2023 |
| GreatWall     | GW-XXXXXX-XXX               | Soc         | [8709162441](https://linux-hardware.org/?probe=8709162441) | Jul 27, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [2231e66b3d](https://linux-hardware.org/?probe=2231e66b3d) | Jul 26, 2023 |
| Dell          | Latitude E6400              | Notebook    | [a9333607eb](https://linux-hardware.org/?probe=a9333607eb) | Jul 26, 2023 |
| Lenovo        | No DPK                      | All in one  | [1b1fa8ccec](https://linux-hardware.org/?probe=1b1fa8ccec) | Jul 26, 2023 |
| HONOR         | NBLK-WAX9X                  | Notebook    | [1081b2e480](https://linux-hardware.org/?probe=1081b2e480) | Jul 26, 2023 |
| HONOR         | NBLK-WAX9X                  | Notebook    | [9919413d6e](https://linux-hardware.org/?probe=9919413d6e) | Jul 25, 2023 |
| HUAWEI        | PAK-AL09                    | Tablet      | [367318c8f5](https://linux-hardware.org/?probe=367318c8f5) | Jul 24, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [136d063ffc](https://linux-hardware.org/?probe=136d063ffc) | Jul 23, 2023 |
| THTF          | ChaoXiangQ620-T1            | Soc         | [45e36895f0](https://linux-hardware.org/?probe=45e36895f0) | Jul 23, 2023 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [b8c39bfcff](https://linux-hardware.org/?probe=b8c39bfcff) | Jul 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d957d5efe0](https://linux-hardware.org/?probe=d957d5efe0) | Jul 22, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [45065697ac](https://linux-hardware.org/?probe=45065697ac) | Jul 22, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [ef3c6c941e](https://linux-hardware.org/?probe=ef3c6c941e) | Jul 18, 2023 |
| ONDA          | A320SD4-ITX Ver:2.00        | Desktop     | [ffe435deca](https://linux-hardware.org/?probe=ffe435deca) | Jul 18, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [7217058966](https://linux-hardware.org/?probe=7217058966) | Jul 18, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [e68c02f317](https://linux-hardware.org/?probe=e68c02f317) | Jul 18, 2023 |
| Lenovo        | B50-45 20388                | Notebook    | [54b4137669](https://linux-hardware.org/?probe=54b4137669) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [50e78d6df5](https://linux-hardware.org/?probe=50e78d6df5) | Jul 18, 2023 |
| Shenzhen P... | MOMO8W_P806                 | Notebook    | [fef8b63a34](https://linux-hardware.org/?probe=fef8b63a34) | Jul 17, 2023 |
| Supermicro    | X10SRL-FB                   | Server      | [9ff74b63c7](https://linux-hardware.org/?probe=9ff74b63c7) | Jul 17, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [899c1452e4](https://linux-hardware.org/?probe=899c1452e4) | Jul 16, 2023 |
| MSI           | MAG Z690 TORPEDO            | Desktop     | [8f4a9f7202](https://linux-hardware.org/?probe=8f4a9f7202) | Jul 16, 2023 |
| HP            | ZBook Power 15.6 inch G1... | Notebook    | [c2042a2e0e](https://linux-hardware.org/?probe=c2042a2e0e) | Jul 15, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [538375bd43](https://linux-hardware.org/?probe=538375bd43) | Jul 14, 2023 |
| Lenovo        | ThinkPad T61 6465CTO        | Notebook    | [fcf6ce5b9e](https://linux-hardware.org/?probe=fcf6ce5b9e) | Jul 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [beea313884](https://linux-hardware.org/?probe=beea313884) | Jul 13, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [6e8dd65f63](https://linux-hardware.org/?probe=6e8dd65f63) | Jul 12, 2023 |
| Intel         | NUC11ATBC4 M53051-303       | Mini pc     | [ea706db679](https://linux-hardware.org/?probe=ea706db679) | Jul 12, 2023 |
| Supermicro    | H11DSi                      | Server      | [b52c1f494c](https://linux-hardware.org/?probe=b52c1f494c) | Jul 11, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [3924343595](https://linux-hardware.org/?probe=3924343595) | Jul 10, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | Desktop     | [97348ef480](https://linux-hardware.org/?probe=97348ef480) | Jul 10, 2023 |
| WeiBu         | ADL-N Prod                  | Desktop     | [23746411d7](https://linux-hardware.org/?probe=23746411d7) | Jul 10, 2023 |
| HUAWEI        | QingYun L420 KLVV-W5821     | Notebook    | [e3227788f6](https://linux-hardware.org/?probe=e3227788f6) | Jul 08, 2023 |
| Supermicro    | X9DAi                       | Desktop     | [952f122742](https://linux-hardware.org/?probe=952f122742) | Jul 07, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [733b12f6a4](https://linux-hardware.org/?probe=733b12f6a4) | Jul 07, 2023 |
| Lenovo        | Legion R9000P2021 82JS      | Notebook    | [0376dd3cbd](https://linux-hardware.org/?probe=0376dd3cbd) | Jul 07, 2023 |
| HP            | 8860 A                      | Desktop     | [5bc7810c4b](https://linux-hardware.org/?probe=5bc7810c4b) | Jul 06, 2023 |
| MECHREVO      | Jiaolong Series MRID6       | Notebook    | [c9ee671981](https://linux-hardware.org/?probe=c9ee671981) | Jul 06, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [4ce9143c78](https://linux-hardware.org/?probe=4ce9143c78) | Jul 05, 2023 |
| Lenovo        | ThinkCentre M6300T          | Desktop     | [d70e22a967](https://linux-hardware.org/?probe=d70e22a967) | Jul 05, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [d990795943](https://linux-hardware.org/?probe=d990795943) | Jul 05, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [0ba3c7bad7](https://linux-hardware.org/?probe=0ba3c7bad7) | Jul 05, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [6e2dff39cc](https://linux-hardware.org/?probe=6e2dff39cc) | Jul 05, 2023 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [0abe31a850](https://linux-hardware.org/?probe=0abe31a850) | Jul 05, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [fc1c7254b3](https://linux-hardware.org/?probe=fc1c7254b3) | Jul 04, 2023 |
| Acer          | Aspire E1-470G              | Notebook    | [db4125a1c5](https://linux-hardware.org/?probe=db4125a1c5) | Jul 04, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | Desktop     | [10aeee3539](https://linux-hardware.org/?probe=10aeee3539) | Jul 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [7fee63007e](https://linux-hardware.org/?probe=7fee63007e) | Jul 02, 2023 |
| Supermicro    | H11DSi                      | Server      | [39710a4809](https://linux-hardware.org/?probe=39710a4809) | Jul 02, 2023 |
| Lenovo        | ThinkBook 16 G5+ ARP 21J... | Notebook    | [211f5e5cf1](https://linux-hardware.org/?probe=211f5e5cf1) | Jul 02, 2023 |
| Supermicro    | H11DSi                      | Server      | [04bac4b25f](https://linux-hardware.org/?probe=04bac4b25f) | Jul 01, 2023 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [0c2a7393bc](https://linux-hardware.org/?probe=0c2a7393bc) | Jul 01, 2023 |
| Dell          | 0H21J3 A07                  | Server      | [621e96507a](https://linux-hardware.org/?probe=621e96507a) | Jun 30, 2023 |
| Dell          | G3 3590                     | Notebook    | [5c7312fed9](https://linux-hardware.org/?probe=5c7312fed9) | Jun 30, 2023 |
| Phytium       | FT-2000/4 V0001             | Server      | [5f78f7d216](https://linux-hardware.org/?probe=5f78f7d216) | Jun 30, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [e21f5d35bb](https://linux-hardware.org/?probe=e21f5d35bb) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d6cb722f64](https://linux-hardware.org/?probe=d6cb722f64) | Jun 29, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | Desktop     | [7baa260d16](https://linux-hardware.org/?probe=7baa260d16) | Jun 29, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [98a588f9ff](https://linux-hardware.org/?probe=98a588f9ff) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [9814b54843](https://linux-hardware.org/?probe=9814b54843) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [5b82e1dd39](https://linux-hardware.org/?probe=5b82e1dd39) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [80b6536a46](https://linux-hardware.org/?probe=80b6536a46) | Jun 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [6615a04065](https://linux-hardware.org/?probe=6615a04065) | Jun 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [8c2e9b8870](https://linux-hardware.org/?probe=8c2e9b8870) | Jun 27, 2023 |
| ASUSTek       | EX-B250M-V3                 | Desktop     | [0746c8e92b](https://linux-hardware.org/?probe=0746c8e92b) | Jun 27, 2023 |
| HP            | EliteBook 835 13 inch G1... | Notebook    | [e43818af40](https://linux-hardware.org/?probe=e43818af40) | Jun 26, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [bc4e778aa5](https://linux-hardware.org/?probe=bc4e778aa5) | Jun 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [5115b6e139](https://linux-hardware.org/?probe=5115b6e139) | Jun 26, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [9dbf9f98a6](https://linux-hardware.org/?probe=9dbf9f98a6) | Jun 26, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | Notebook    | [ebfe7d469a](https://linux-hardware.org/?probe=ebfe7d469a) | Jun 24, 2023 |
| HONOR         | GLO-GXXX                    | Notebook    | [0e22fb1d65](https://linux-hardware.org/?probe=0e22fb1d65) | Jun 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [a373e679ae](https://linux-hardware.org/?probe=a373e679ae) | Jun 23, 2023 |
| HASEE Comp... | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [2c0be5d314](https://linux-hardware.org/?probe=2c0be5d314) | Jun 19, 2023 |
| Timi          | A34R                        | Notebook    | [da4d787d75](https://linux-hardware.org/?probe=da4d787d75) | Jun 19, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c454cb2cf0](https://linux-hardware.org/?probe=c454cb2cf0) | Jun 18, 2023 |
| MSI           | B660M BOMBER DDR4           | Desktop     | [bebc7de8d4](https://linux-hardware.org/?probe=bebc7de8d4) | Jun 17, 2023 |
| MSI           | B660M BOMBER DDR4           | Desktop     | [0a02c36bd6](https://linux-hardware.org/?probe=0a02c36bd6) | Jun 17, 2023 |
| Lenovo        | MAHOBAY 31900005 STD        | All in one  | [dfe01fa6dd](https://linux-hardware.org/?probe=dfe01fa6dd) | Jun 17, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [bfa70344e3](https://linux-hardware.org/?probe=bfa70344e3) | Jun 16, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [ec1b8c4ef4](https://linux-hardware.org/?probe=ec1b8c4ef4) | Jun 16, 2023 |
| Timi          | TM1612                      | Notebook    | [7ec35d1268](https://linux-hardware.org/?probe=7ec35d1268) | Jun 16, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | Desktop     | [53a0b2f173](https://linux-hardware.org/?probe=53a0b2f173) | Jun 15, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [d512f1865e](https://linux-hardware.org/?probe=d512f1865e) | Jun 15, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [b559c07f2d](https://linux-hardware.org/?probe=b559c07f2d) | Jun 13, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [9c70c12c1f](https://linux-hardware.org/?probe=9c70c12c1f) | Jun 13, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [99f7eebfd4](https://linux-hardware.org/?probe=99f7eebfd4) | Jun 13, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [675f082570](https://linux-hardware.org/?probe=675f082570) | Jun 12, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [fc0318992c](https://linux-hardware.org/?probe=fc0318992c) | Jun 12, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [272de7ad6b](https://linux-hardware.org/?probe=272de7ad6b) | Jun 11, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [a165849009](https://linux-hardware.org/?probe=a165849009) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [05c07442a3](https://linux-hardware.org/?probe=05c07442a3) | Jun 09, 2023 |
| WOOKING       | X16                         | Notebook    | [aa543651fc](https://linux-hardware.org/?probe=aa543651fc) | Jun 08, 2023 |
| Win elemen... | M600                        | Desktop     | [360ab80d9b](https://linux-hardware.org/?probe=360ab80d9b) | Jun 06, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [6640281a3b](https://linux-hardware.org/?probe=6640281a3b) | Jun 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [f06cb8954c](https://linux-hardware.org/?probe=f06cb8954c) | Jun 06, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [a71d7442d7](https://linux-hardware.org/?probe=a71d7442d7) | Jun 05, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [964cd10c8e](https://linux-hardware.org/?probe=964cd10c8e) | Jun 05, 2023 |
| HP            | 8768 A                      | Desktop     | [17d0560a85](https://linux-hardware.org/?probe=17d0560a85) | Jun 05, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [f8f07099c7](https://linux-hardware.org/?probe=f8f07099c7) | Jun 05, 2023 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [f4e7c7034f](https://linux-hardware.org/?probe=f4e7c7034f) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [54e2e07ac6](https://linux-hardware.org/?probe=54e2e07ac6) | Jun 05, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [4ba1a29c23](https://linux-hardware.org/?probe=4ba1a29c23) | Jun 05, 2023 |
| Unknown       | Unknown                     | Tablet      | [33c4d481d9](https://linux-hardware.org/?probe=33c4d481d9) | Jun 05, 2023 |
| Unknown       | Unknown                     | Soc         | [9cb76f0184](https://linux-hardware.org/?probe=9cb76f0184) | Jun 04, 2023 |
| Unknown       | Unknown                     | Soc         | [7e2052896c](https://linux-hardware.org/?probe=7e2052896c) | Jun 04, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [b6411e69f3](https://linux-hardware.org/?probe=b6411e69f3) | Jun 04, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [f88c53fd11](https://linux-hardware.org/?probe=f88c53fd11) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | Notebook    | [01e8918ef6](https://linux-hardware.org/?probe=01e8918ef6) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | Notebook    | [4dc30f1c10](https://linux-hardware.org/?probe=4dc30f1c10) | Jun 04, 2023 |
| GPD           | G1619-04                    | Notebook    | [fcc919c1c2](https://linux-hardware.org/?probe=fcc919c1c2) | Jun 03, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [c142ea01cd](https://linux-hardware.org/?probe=c142ea01cd) | Jun 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0523005c68](https://linux-hardware.org/?probe=0523005c68) | Jun 03, 2023 |
| GPD           | G1618-04                    | All in one  | [63ca853c36](https://linux-hardware.org/?probe=63ca853c36) | Jun 03, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [ab7c62da47](https://linux-hardware.org/?probe=ab7c62da47) | Jun 02, 2023 |
| Dell          | Inspiron 5468               | Notebook    | [b16aeda09e](https://linux-hardware.org/?probe=b16aeda09e) | Jun 02, 2023 |
| IPASON        | P3                          | Notebook    | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| Unknown       | Unknown                     | Tablet      | [40aebbf364](https://linux-hardware.org/?probe=40aebbf364) | Jun 01, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [d21f59bea5](https://linux-hardware.org/?probe=d21f59bea5) | May 31, 2023 |
| Lenovo        | ZhaoYangN4620Z 20A0Z037K... | Notebook    | [7e07cca977](https://linux-hardware.org/?probe=7e07cca977) | May 31, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [202bf4f657](https://linux-hardware.org/?probe=202bf4f657) | May 29, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [bb60c42e07](https://linux-hardware.org/?probe=bb60c42e07) | May 29, 2023 |
| Unknown       | Unknown                     | Soc         | [0f85a652ad](https://linux-hardware.org/?probe=0f85a652ad) | May 28, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [1375d36b0f](https://linux-hardware.org/?probe=1375d36b0f) | May 28, 2023 |
| ONDA          | M3 miniPC VER               | Desktop     | [1a6a6ab3e6](https://linux-hardware.org/?probe=1a6a6ab3e6) | May 27, 2023 |
| Dell          | 0WCJNT A06                  | Server      | [b3215bf901](https://linux-hardware.org/?probe=b3215bf901) | May 27, 2023 |
| Unknown       | Xiaobao Nas I               | Soc         | [bc71966f2f](https://linux-hardware.org/?probe=bc71966f2f) | May 26, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [84953a504d](https://linux-hardware.org/?probe=84953a504d) | May 26, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [f4de9c8a5f](https://linux-hardware.org/?probe=f4de9c8a5f) | May 26, 2023 |
| Lenovo        | ThinkPad X200 74574AC       | Notebook    | [e770387a34](https://linux-hardware.org/?probe=e770387a34) | May 25, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [00979b3baa](https://linux-hardware.org/?probe=00979b3baa) | May 24, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [84d9f5a2cc](https://linux-hardware.org/?probe=84d9f5a2cc) | May 24, 2023 |
| ONDA          | M3 miniPC VER               | Desktop     | [c4c78fe843](https://linux-hardware.org/?probe=c4c78fe843) | May 24, 2023 |
| Unknown       | Unknown                     | Tablet      | [8a83b799d5](https://linux-hardware.org/?probe=8a83b799d5) | May 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [4c3c861f80](https://linux-hardware.org/?probe=4c3c861f80) | May 23, 2023 |
| Unknown       | Unknown                     | Soc         | [39ae5b4339](https://linux-hardware.org/?probe=39ae5b4339) | May 23, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a2986e9b7a](https://linux-hardware.org/?probe=a2986e9b7a) | May 23, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | Notebook    | [c4040a0905](https://linux-hardware.org/?probe=c4040a0905) | May 23, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [04d3c59d2c](https://linux-hardware.org/?probe=04d3c59d2c) | May 22, 2023 |
| Dell          | 0J1C3P A00                  | Desktop     | [5f3d8a94e6](https://linux-hardware.org/?probe=5f3d8a94e6) | May 22, 2023 |
| Unknown       | Unknown                     | Soc         | [48690c2413](https://linux-hardware.org/?probe=48690c2413) | May 21, 2023 |
| Unknown       | Unknown                     | Soc         | [84bd3a247e](https://linux-hardware.org/?probe=84bd3a247e) | May 21, 2023 |
| AZW           | SER V01                     | Mini pc     | [e0c2283aa1](https://linux-hardware.org/?probe=e0c2283aa1) | May 20, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [cf1d4ac757](https://linux-hardware.org/?probe=cf1d4ac757) | May 18, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [4d1cd4ec12](https://linux-hardware.org/?probe=4d1cd4ec12) | May 17, 2023 |
| Toshiba       | Satellite C805D             | Notebook    | [21ee852978](https://linux-hardware.org/?probe=21ee852978) | May 16, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [3d9b02954b](https://linux-hardware.org/?probe=3d9b02954b) | May 16, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [2323128fd2](https://linux-hardware.org/?probe=2323128fd2) | May 16, 2023 |
| Unknown       | Unknown                     | Soc         | [8fa49f6af8](https://linux-hardware.org/?probe=8fa49f6af8) | May 14, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [e4f7010e78](https://linux-hardware.org/?probe=e4f7010e78) | May 13, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [0d4d8571bf](https://linux-hardware.org/?probe=0d4d8571bf) | May 13, 2023 |
| Phytium       | FT-2000/4 V0001             | Server      | [ef9af7edf3](https://linux-hardware.org/?probe=ef9af7edf3) | May 09, 2023 |
| Koloe         | X58                         | Desktop     | [7c1acc3b84](https://linux-hardware.org/?probe=7c1acc3b84) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [d615a9b90f](https://linux-hardware.org/?probe=d615a9b90f) | May 08, 2023 |
| Quanta        | TWH                         | Notebook    | [724b4d7343](https://linux-hardware.org/?probe=724b4d7343) | May 06, 2023 |
| Lenovo        | IdeaPad Y480 20131          | Notebook    | [d625664bee](https://linux-hardware.org/?probe=d625664bee) | May 06, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [850ea7c843](https://linux-hardware.org/?probe=850ea7c843) | May 06, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [eb289c3d5f](https://linux-hardware.org/?probe=eb289c3d5f) | May 06, 2023 |
| Unknown       | Unknown                     | Soc         | [043c078caf](https://linux-hardware.org/?probe=043c078caf) | May 05, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [d63ef842c1](https://linux-hardware.org/?probe=d63ef842c1) | May 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5f4447aa45](https://linux-hardware.org/?probe=5f4447aa45) | May 05, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [1dacd7233b](https://linux-hardware.org/?probe=1dacd7233b) | May 05, 2023 |
| Raspberry ... | Raspberry Pi 3 Model A P... | Soc         | [d0c2c987fc](https://linux-hardware.org/?probe=d0c2c987fc) | May 03, 2023 |
| Microsoft     | Surface with Windows RT     | Tablet      | [7d6459d367](https://linux-hardware.org/?probe=7d6459d367) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ab21408c4c](https://linux-hardware.org/?probe=ab21408c4c) | May 03, 2023 |
| HP            | 83C3 A01                    | Mini pc     | [bb29a94285](https://linux-hardware.org/?probe=bb29a94285) | May 03, 2023 |
| GreatWall     | DF                          | Soc         | [5a3cb266db](https://linux-hardware.org/?probe=5a3cb266db) | May 03, 2023 |
| Huanan        | B75                         | Desktop     | [597233d5d2](https://linux-hardware.org/?probe=597233d5d2) | May 02, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [528ba302c0](https://linux-hardware.org/?probe=528ba302c0) | May 02, 2023 |
| Quanta        | TWH                         | Notebook    | [e760482286](https://linux-hardware.org/?probe=e760482286) | May 02, 2023 |
| Google        | Homestar (rev4+)            | Soc         | [9184b7f306](https://linux-hardware.org/?probe=9184b7f306) | May 02, 2023 |
| MECHREVO      | WUJIE16 Pro                 | Notebook    | [c19e8370e5](https://linux-hardware.org/?probe=c19e8370e5) | May 02, 2023 |
| Huanan        | B75                         | Desktop     | [1f988e5101](https://linux-hardware.org/?probe=1f988e5101) | May 02, 2023 |
| MAXSUN        | MS-A86FX FS M.3             | Desktop     | [3ce20d3b05](https://linux-hardware.org/?probe=3ce20d3b05) | May 01, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [b37927b9d4](https://linux-hardware.org/?probe=b37927b9d4) | May 01, 2023 |
| Timi          | TM1612                      | Notebook    | [3c06f7495e](https://linux-hardware.org/?probe=3c06f7495e) | May 01, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [a188684584](https://linux-hardware.org/?probe=a188684584) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | Desktop     | [233ea7cdd8](https://linux-hardware.org/?probe=233ea7cdd8) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | Desktop     | [177fe2fc00](https://linux-hardware.org/?probe=177fe2fc00) | Apr 30, 2023 |
| HEDYCOMPUT... | IH81MF-Q3                   | Desktop     | [3444236ed4](https://linux-hardware.org/?probe=3444236ed4) | Apr 30, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [6750e5f83d](https://linux-hardware.org/?probe=6750e5f83d) | Apr 30, 2023 |
| Dell          | Vostro 5468                 | Notebook    | [93eb16d30d](https://linux-hardware.org/?probe=93eb16d30d) | Apr 30, 2023 |
| Colorful T... | CVN Z590 GAMING PRO V20     | Desktop     | [209ec5e477](https://linux-hardware.org/?probe=209ec5e477) | Apr 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [b1e6130b77](https://linux-hardware.org/?probe=b1e6130b77) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | Desktop     | [429d6f994a](https://linux-hardware.org/?probe=429d6f994a) | Apr 28, 2023 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [9a22f330c4](https://linux-hardware.org/?probe=9a22f330c4) | Apr 28, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4fb9a937f3](https://linux-hardware.org/?probe=4fb9a937f3) | Apr 27, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [97a3b73c44](https://linux-hardware.org/?probe=97a3b73c44) | Apr 27, 2023 |
| Timi          | TM1612                      | Notebook    | [f3127f0186](https://linux-hardware.org/?probe=f3127f0186) | Apr 27, 2023 |
| Phytium       | FT-2000/4 V0001             | Server      | [d59b9ff270](https://linux-hardware.org/?probe=d59b9ff270) | Apr 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [c5824f9cae](https://linux-hardware.org/?probe=c5824f9cae) | Apr 25, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [298d51ae78](https://linux-hardware.org/?probe=298d51ae78) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [aa23589794](https://linux-hardware.org/?probe=aa23589794) | Apr 23, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [f5b9a50e56](https://linux-hardware.org/?probe=f5b9a50e56) | Apr 23, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [edcf4e959d](https://linux-hardware.org/?probe=edcf4e959d) | Apr 23, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [d1ca2bb309](https://linux-hardware.org/?probe=d1ca2bb309) | Apr 23, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [8209f53171](https://linux-hardware.org/?probe=8209f53171) | Apr 22, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c5b0278699](https://linux-hardware.org/?probe=c5b0278699) | Apr 22, 2023 |
| Unknown       | BXTH265BC                   | Notebook    | [37293a672b](https://linux-hardware.org/?probe=37293a672b) | Apr 21, 2023 |
| Timi          | A34R                        | Notebook    | [310e4d7b63](https://linux-hardware.org/?probe=310e4d7b63) | Apr 20, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [ddf678b11a](https://linux-hardware.org/?probe=ddf678b11a) | Apr 20, 2023 |
| MECHREVO      | Code10-7CC6U                | Notebook    | [0964cd2b26](https://linux-hardware.org/?probe=0964cd2b26) | Apr 20, 2023 |
| MECHREVO      | Code10-7CC6U                | Notebook    | [5ddc83a95c](https://linux-hardware.org/?probe=5ddc83a95c) | Apr 20, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [905e23cca7](https://linux-hardware.org/?probe=905e23cca7) | Apr 20, 2023 |
| UGREEN        | DX4600                      | Desktop     | [cbe70de89c](https://linux-hardware.org/?probe=cbe70de89c) | Apr 19, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [49d7cdd068](https://linux-hardware.org/?probe=49d7cdd068) | Apr 18, 2023 |
| Timi          | TM1612                      | Notebook    | [7be723d412](https://linux-hardware.org/?probe=7be723d412) | Apr 16, 2023 |
| Unknown       | Unknown                     | Soc         | [018daf402b](https://linux-hardware.org/?probe=018daf402b) | Apr 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [d45af08c99](https://linux-hardware.org/?probe=d45af08c99) | Apr 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [6925c48705](https://linux-hardware.org/?probe=6925c48705) | Apr 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [158dacc1ce](https://linux-hardware.org/?probe=158dacc1ce) | Apr 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [52aeca6f98](https://linux-hardware.org/?probe=52aeca6f98) | Apr 13, 2023 |
| HP            | ZHAN 99 Mobile Workstati... | Notebook    | [3dcc7ab043](https://linux-hardware.org/?probe=3dcc7ab043) | Apr 12, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [6bec4cb4a8](https://linux-hardware.org/?probe=6bec4cb4a8) | Apr 12, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [6182cca953](https://linux-hardware.org/?probe=6182cca953) | Apr 12, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [8d4288ca33](https://linux-hardware.org/?probe=8d4288ca33) | Apr 09, 2023 |
| ASRock        | B150 Combo                  | Desktop     | [c4acc08020](https://linux-hardware.org/?probe=c4acc08020) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3358152092](https://linux-hardware.org/?probe=3358152092) | Apr 06, 2023 |
| ASUSTek       | A68HM-E                     | Desktop     | [0c9ae9bcd7](https://linux-hardware.org/?probe=0c9ae9bcd7) | Apr 06, 2023 |
| Timi          | RedmiBook Pro 15            | Notebook    | [4eb4d46bfc](https://linux-hardware.org/?probe=4eb4d46bfc) | Apr 05, 2023 |
| HP            | 1790                        | Desktop     | [55e3d423e0](https://linux-hardware.org/?probe=55e3d423e0) | Apr 05, 2023 |
| Dell          | 0PVVD2 A01                  | Server      | [465c40dd0f](https://linux-hardware.org/?probe=465c40dd0f) | Apr 04, 2023 |
| Dell          | 0RN4PJ A01                  | Server      | [93dbb217b4](https://linux-hardware.org/?probe=93dbb217b4) | Apr 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [cdd67e12ca](https://linux-hardware.org/?probe=cdd67e12ca) | Apr 03, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [a85a9274d5](https://linux-hardware.org/?probe=a85a9274d5) | Apr 03, 2023 |
| HASEE Comp... | CV15S                       | Notebook    | [6c31986832](https://linux-hardware.org/?probe=6c31986832) | Apr 03, 2023 |
| HASEE Comp... | CV15S                       | Notebook    | [47c3d8f7b6](https://linux-hardware.org/?probe=47c3d8f7b6) | Apr 03, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [091d2eda88](https://linux-hardware.org/?probe=091d2eda88) | Apr 01, 2023 |
| Intel         | H81U                        | Notebook    | [43d7179dc3](https://linux-hardware.org/?probe=43d7179dc3) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [da1e07f122](https://linux-hardware.org/?probe=da1e07f122) | Mar 30, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [a33a768662](https://linux-hardware.org/?probe=a33a768662) | Mar 29, 2023 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [eb153b5f5d](https://linux-hardware.org/?probe=eb153b5f5d) | Mar 29, 2023 |
| Dell          | 0R5KF8 A03                  | Desktop     | [decf0f5193](https://linux-hardware.org/?probe=decf0f5193) | Mar 28, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [caf2461355](https://linux-hardware.org/?probe=caf2461355) | Mar 28, 2023 |
| Unknown       | FT2000plus Generic Borad... | Desktop     | [43ec5396f3](https://linux-hardware.org/?probe=43ec5396f3) | Mar 28, 2023 |
| Unknown       | FT2000plus Generic Borad... | Desktop     | [c305aa7562](https://linux-hardware.org/?probe=c305aa7562) | Mar 28, 2023 |
| ASRock        | A320M-HDV                   | Desktop     | [9685e81600](https://linux-hardware.org/?probe=9685e81600) | Mar 27, 2023 |
| ASUSTek       | Z97-K R2.0                  | Desktop     | [b1e1f4d711](https://linux-hardware.org/?probe=b1e1f4d711) | Mar 27, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | Notebook    | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [aafbb2815f](https://linux-hardware.org/?probe=aafbb2815f) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [300fe5d1b2](https://linux-hardware.org/?probe=300fe5d1b2) | Mar 24, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [8291e7598a](https://linux-hardware.org/?probe=8291e7598a) | Mar 24, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [7f98044a04](https://linux-hardware.org/?probe=7f98044a04) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4731c6e59f](https://linux-hardware.org/?probe=4731c6e59f) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [127173d60b](https://linux-hardware.org/?probe=127173d60b) | Mar 23, 2023 |
| Timi          | TM1613                      | Notebook    | [3016a40df3](https://linux-hardware.org/?probe=3016a40df3) | Mar 23, 2023 |
| Timi          | TM1613                      | Notebook    | [ddbc83a8d3](https://linux-hardware.org/?probe=ddbc83a8d3) | Mar 23, 2023 |
| Lenovo        | ThinkPad X230s 20AHS0070... | Notebook    | [9d86eaf558](https://linux-hardware.org/?probe=9d86eaf558) | Mar 21, 2023 |
| Dell          | 0NDYHG A00                  | Desktop     | [f007ab3692](https://linux-hardware.org/?probe=f007ab3692) | Mar 20, 2023 |
| Intel         | NUC12SNKi72 M45201-500      | Mini pc     | [67985889b2](https://linux-hardware.org/?probe=67985889b2) | Mar 17, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [f980742ab8](https://linux-hardware.org/?probe=f980742ab8) | Mar 16, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [3b6514e9c4](https://linux-hardware.org/?probe=3b6514e9c4) | Mar 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [0eb13c3117](https://linux-hardware.org/?probe=0eb13c3117) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [6e24f7a3c1](https://linux-hardware.org/?probe=6e24f7a3c1) | Mar 15, 2023 |
| sunxi         | LeMaker Banana Pi           | Soc         | [d27d307085](https://linux-hardware.org/?probe=d27d307085) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [eac2f2ae40](https://linux-hardware.org/?probe=eac2f2ae40) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d9d4f5649a](https://linux-hardware.org/?probe=d9d4f5649a) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [70de894994](https://linux-hardware.org/?probe=70de894994) | Mar 13, 2023 |
| GPD           | G1621-02                    | Notebook    | [21394d0975](https://linux-hardware.org/?probe=21394d0975) | Mar 12, 2023 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [bcbf6544cd](https://linux-hardware.org/?probe=bcbf6544cd) | Mar 11, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [4ffe64e472](https://linux-hardware.org/?probe=4ffe64e472) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [49130084c4](https://linux-hardware.org/?probe=49130084c4) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [a6091bc2e2](https://linux-hardware.org/?probe=a6091bc2e2) | Mar 11, 2023 |
| Lenovo        | 313A SDK0L77767 WIN 3423... | Desktop     | [869582f7a7](https://linux-hardware.org/?probe=869582f7a7) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [a5a874dac0](https://linux-hardware.org/?probe=a5a874dac0) | Mar 10, 2023 |
| AZW           | GTR V02                     | Desktop     | [06b17c5206](https://linux-hardware.org/?probe=06b17c5206) | Mar 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CMA... | Notebook    | [f15426402c](https://linux-hardware.org/?probe=f15426402c) | Mar 09, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [30d91acf27](https://linux-hardware.org/?probe=30d91acf27) | Mar 07, 2023 |
| GPD           | P2 MAX                      | Notebook    | [d73c7b9146](https://linux-hardware.org/?probe=d73c7b9146) | Mar 07, 2023 |
| Lenovo        | 313A SDK0L77767 WIN 3423... | Desktop     | [828ae3c8fd](https://linux-hardware.org/?probe=828ae3c8fd) | Mar 07, 2023 |
| Gigabyte      | Z690 UD DDR4 V2             | Desktop     | [fa84567d3f](https://linux-hardware.org/?probe=fa84567d3f) | Mar 06, 2023 |
| Gigabyte      | Z690 UD DDR4 V2             | Desktop     | [b58f671799](https://linux-hardware.org/?probe=b58f671799) | Mar 06, 2023 |
| Lenovo        | Unknown                     | Notebook    | [2ae9263125](https://linux-hardware.org/?probe=2ae9263125) | Mar 06, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [bb68a61939](https://linux-hardware.org/?probe=bb68a61939) | Mar 05, 2023 |
| Lenovo        | ThinkPad 11e 20D9S00C00     | Notebook    | [dbae54f9d4](https://linux-hardware.org/?probe=dbae54f9d4) | Mar 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [89822406cc](https://linux-hardware.org/?probe=89822406cc) | Feb 28, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [dd2f99b3ca](https://linux-hardware.org/?probe=dd2f99b3ca) | Feb 27, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [3c4718f66e](https://linux-hardware.org/?probe=3c4718f66e) | Feb 26, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Server      | [ffa58f1702](https://linux-hardware.org/?probe=ffa58f1702) | Feb 26, 2023 |
| ASUSTek       | H87-PLUS                    | Desktop     | [f56bb767fd](https://linux-hardware.org/?probe=f56bb767fd) | Feb 26, 2023 |
| ASUSTek       | H87-PLUS                    | Desktop     | [98e70b4028](https://linux-hardware.org/?probe=98e70b4028) | Feb 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [65a35ffeea](https://linux-hardware.org/?probe=65a35ffeea) | Feb 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [3d8e9cb31b](https://linux-hardware.org/?probe=3d8e9cb31b) | Feb 24, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | Notebook    | [ade006d016](https://linux-hardware.org/?probe=ade006d016) | Feb 24, 2023 |
| Lenovo        | KaiTian N70z G1d            | Notebook    | [cbc8e4e008](https://linux-hardware.org/?probe=cbc8e4e008) | Feb 24, 2023 |
| Dell          | 0CNWVK A02                  | Desktop     | [1fd825c3df](https://linux-hardware.org/?probe=1fd825c3df) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [028814b990](https://linux-hardware.org/?probe=028814b990) | Feb 24, 2023 |
| Dell          | 0V7K5Y A00                  | Desktop     | [831a493e15](https://linux-hardware.org/?probe=831a493e15) | Feb 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [cc10e54ab9](https://linux-hardware.org/?probe=cc10e54ab9) | Feb 20, 2023 |
| ASUSTek       | X99-M WS                    | Desktop     | [69eb540783](https://linux-hardware.org/?probe=69eb540783) | Feb 20, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [c4ec00ef99](https://linux-hardware.org/?probe=c4ec00ef99) | Feb 17, 2023 |
| Acer          | Aspire 5540                 | Notebook    | [ce25cbe4f9](https://linux-hardware.org/?probe=ce25cbe4f9) | Feb 17, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | Desktop     | [cd5fcc7d4c](https://linux-hardware.org/?probe=cd5fcc7d4c) | Feb 17, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | Desktop     | [8ef4a011f7](https://linux-hardware.org/?probe=8ef4a011f7) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [5160909d57](https://linux-hardware.org/?probe=5160909d57) | Feb 17, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [2c3699dc3c](https://linux-hardware.org/?probe=2c3699dc3c) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [21ef26978d](https://linux-hardware.org/?probe=21ef26978d) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [ba50ff27b1](https://linux-hardware.org/?probe=ba50ff27b1) | Feb 17, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | Desktop     | [ad9381188b](https://linux-hardware.org/?probe=ad9381188b) | Feb 17, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [96e79838f4](https://linux-hardware.org/?probe=96e79838f4) | Feb 17, 2023 |
| Dell          | 06WXJT A01                  | Server      | [0737c1856c](https://linux-hardware.org/?probe=0737c1856c) | Feb 17, 2023 |
| Inspur        | NF5280M6 YZMB-01642-103     | Server      | [87802011ec](https://linux-hardware.org/?probe=87802011ec) | Feb 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [ddafe146cc](https://linux-hardware.org/?probe=ddafe146cc) | Feb 17, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | Desktop     | [386273f2fc](https://linux-hardware.org/?probe=386273f2fc) | Feb 17, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | Desktop     | [1a9e50653b](https://linux-hardware.org/?probe=1a9e50653b) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [d97f8e5a87](https://linux-hardware.org/?probe=d97f8e5a87) | Feb 17, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [a8816819e2](https://linux-hardware.org/?probe=a8816819e2) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [38223114be](https://linux-hardware.org/?probe=38223114be) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [afe7d688f2](https://linux-hardware.org/?probe=afe7d688f2) | Feb 17, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [cbc7919c26](https://linux-hardware.org/?probe=cbc7919c26) | Feb 17, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | Desktop     | [4a97ea8e7a](https://linux-hardware.org/?probe=4a97ea8e7a) | Feb 17, 2023 |
| Dell          | 06WXJT A01                  | Server      | [431e2ccfa8](https://linux-hardware.org/?probe=431e2ccfa8) | Feb 17, 2023 |
| Inspur        | NF5280M6 YZMB-01642-103     | Server      | [0b2730526f](https://linux-hardware.org/?probe=0b2730526f) | Feb 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [976a71dfac](https://linux-hardware.org/?probe=976a71dfac) | Feb 17, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [fd678baa9f](https://linux-hardware.org/?probe=fd678baa9f) | Feb 16, 2023 |
| Lenovo        | ThinkPad E460 20ETA00CCD    | Notebook    | [cb29661ee9](https://linux-hardware.org/?probe=cb29661ee9) | Feb 16, 2023 |
| Lenovo        | ThinkPad E460 20ETA00CCD    | Notebook    | [158769574f](https://linux-hardware.org/?probe=158769574f) | Feb 16, 2023 |
| HP            | 1000                        | Notebook    | [57de0f3103](https://linux-hardware.org/?probe=57de0f3103) | Feb 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [fe12f077df](https://linux-hardware.org/?probe=fe12f077df) | Feb 15, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [991db4f096](https://linux-hardware.org/?probe=991db4f096) | Feb 14, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | Desktop     | [63a1a75985](https://linux-hardware.org/?probe=63a1a75985) | Feb 14, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | Desktop     | [b1d0b59ec2](https://linux-hardware.org/?probe=b1d0b59ec2) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [7c15b6acdf](https://linux-hardware.org/?probe=7c15b6acdf) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [9e6adb8535](https://linux-hardware.org/?probe=9e6adb8535) | Feb 14, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | Desktop     | [df0ce521b3](https://linux-hardware.org/?probe=df0ce521b3) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [f427323448](https://linux-hardware.org/?probe=f427323448) | Feb 14, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [c62c075365](https://linux-hardware.org/?probe=c62c075365) | Feb 14, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [2bde59c923](https://linux-hardware.org/?probe=2bde59c923) | Feb 14, 2023 |
| Inspur        | NF5280M6 YZMB-01642-103     | Server      | [7f890dfbbf](https://linux-hardware.org/?probe=7f890dfbbf) | Feb 14, 2023 |
| Dell          | 06WXJT A01                  | Server      | [39cdba86e5](https://linux-hardware.org/?probe=39cdba86e5) | Feb 14, 2023 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [745ac39390](https://linux-hardware.org/?probe=745ac39390) | Feb 14, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [6a952f7024](https://linux-hardware.org/?probe=6a952f7024) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [c49317ce12](https://linux-hardware.org/?probe=c49317ce12) | Feb 13, 2023 |
| Lenovo        | ThinkPad X220 4290CTO       | Notebook    | [1e9debee03](https://linux-hardware.org/?probe=1e9debee03) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [b1d1f36f51](https://linux-hardware.org/?probe=b1d1f36f51) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [e8ba753fae](https://linux-hardware.org/?probe=e8ba753fae) | Feb 13, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [59a015c31d](https://linux-hardware.org/?probe=59a015c31d) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | Notebook    | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| Lenovo        | XiaoXinPro 14ACH 2021 82... | Notebook    | [29326a6340](https://linux-hardware.org/?probe=29326a6340) | Feb 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [770938dc90](https://linux-hardware.org/?probe=770938dc90) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [1423d5ac1b](https://linux-hardware.org/?probe=1423d5ac1b) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [bb589c5e58](https://linux-hardware.org/?probe=bb589c5e58) | Feb 10, 2023 |
| Unknown       | Unknown                     | Soc         | [2ba7af4017](https://linux-hardware.org/?probe=2ba7af4017) | Feb 09, 2023 |
| Loongson      | LS3A5000-7A1000-1w-EVB-V... | Desktop     | [cbf5d56cfc](https://linux-hardware.org/?probe=cbf5d56cfc) | Feb 09, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [a127a79277](https://linux-hardware.org/?probe=a127a79277) | Feb 07, 2023 |
| Inspur        | Shuyu                       | Server      | [37c2630b8f](https://linux-hardware.org/?probe=37c2630b8f) | Feb 07, 2023 |
| Lenovo        | 3328 SDK0T76479 WIN 3423... | Desktop     | [8667299d04](https://linux-hardware.org/?probe=8667299d04) | Feb 04, 2023 |
| Lenovo        | 3328 SDK0T76479 WIN 3423... | Desktop     | [7862a9afc7](https://linux-hardware.org/?probe=7862a9afc7) | Feb 04, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [af8a076192](https://linux-hardware.org/?probe=af8a076192) | Feb 03, 2023 |
| Alienware     | x17 R2                      | Notebook    | [474a70c148](https://linux-hardware.org/?probe=474a70c148) | Feb 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [13077754a1](https://linux-hardware.org/?probe=13077754a1) | Feb 02, 2023 |
| Timi          | A34R                        | Notebook    | [18ab422614](https://linux-hardware.org/?probe=18ab422614) | Jan 31, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [dd9e1146ff](https://linux-hardware.org/?probe=dd9e1146ff) | Jan 31, 2023 |
| Lenovo        | 3148 NOK                    | Desktop     | [72815c2ab8](https://linux-hardware.org/?probe=72815c2ab8) | Jan 30, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [a7ef98ea02](https://linux-hardware.org/?probe=a7ef98ea02) | Jan 30, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [06f297243d](https://linux-hardware.org/?probe=06f297243d) | Jan 28, 2023 |
| OEM           | KX-01 V1.0                  | Desktop     | [75d9dc396c](https://linux-hardware.org/?probe=75d9dc396c) | Jan 28, 2023 |
| MECHREVO      | Code10-7CC6U                | Notebook    | [86e769b2a3](https://linux-hardware.org/?probe=86e769b2a3) | Jan 27, 2023 |
| Lenovo        | ThinkPad E495 20NEA00ACD    | Notebook    | [70dad952b2](https://linux-hardware.org/?probe=70dad952b2) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [510b879339](https://linux-hardware.org/?probe=510b879339) | Jan 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [68dcd57886](https://linux-hardware.org/?probe=68dcd57886) | Jan 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [e9ac3c25b8](https://linux-hardware.org/?probe=e9ac3c25b8) | Jan 19, 2023 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [5e5628739f](https://linux-hardware.org/?probe=5e5628739f) | Jan 16, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [8382d0f8eb](https://linux-hardware.org/?probe=8382d0f8eb) | Jan 16, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [314c5ba951](https://linux-hardware.org/?probe=314c5ba951) | Jan 16, 2023 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [68fcb008b1](https://linux-hardware.org/?probe=68fcb008b1) | Jan 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [53b2d510d6](https://linux-hardware.org/?probe=53b2d510d6) | Jan 14, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [c05f45c326](https://linux-hardware.org/?probe=c05f45c326) | Jan 14, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [9bfcd0f555](https://linux-hardware.org/?probe=9bfcd0f555) | Jan 14, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [a4fb531cc9](https://linux-hardware.org/?probe=a4fb531cc9) | Jan 13, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [eab87def73](https://linux-hardware.org/?probe=eab87def73) | Jan 12, 2023 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [a595895c7e](https://linux-hardware.org/?probe=a595895c7e) | Jan 11, 2023 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [56544d809f](https://linux-hardware.org/?probe=56544d809f) | Jan 11, 2023 |
| ASUSTek       | TUF Gaming FX505GM_FX86F... | Notebook    | [5ab0bf0018](https://linux-hardware.org/?probe=5ab0bf0018) | Jan 10, 2023 |
| Inspur        | NF5280M6 YZMB-01642-101     | Server      | [22275687f9](https://linux-hardware.org/?probe=22275687f9) | Jan 10, 2023 |
| AZW           | EQ59                        | Desktop     | [3eb85d9ee5](https://linux-hardware.org/?probe=3eb85d9ee5) | Jan 10, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [02c6515f49](https://linux-hardware.org/?probe=02c6515f49) | Jan 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [cef6a9db45](https://linux-hardware.org/?probe=cef6a9db45) | Jan 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [8defa5d641](https://linux-hardware.org/?probe=8defa5d641) | Jan 05, 2023 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [b54f312c7d](https://linux-hardware.org/?probe=b54f312c7d) | Jan 05, 2023 |
| Unknown       | Unknown                     | Soc         | [6a3439a8e1](https://linux-hardware.org/?probe=6a3439a8e1) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430u 33519LC      | Notebook    | [87af3fa7f0](https://linux-hardware.org/?probe=87af3fa7f0) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480s 20L7A00HH... | Notebook    | [801c1bad94](https://linux-hardware.org/?probe=801c1bad94) | Jan 02, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | Notebook    | [a22f1e75b3](https://linux-hardware.org/?probe=a22f1e75b3) | Jan 01, 2023 |
| Lenovo        | ThinkPad Edge E545 20B2S... | Notebook    | [c83f51d7d9](https://linux-hardware.org/?probe=c83f51d7d9) | Dec 31, 2022 |
| Phytium       | D2000                       | Server      | [497220c5dd](https://linux-hardware.org/?probe=497220c5dd) | Dec 30, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3980... | Notebook    | [43783d2dda](https://linux-hardware.org/?probe=43783d2dda) | Dec 29, 2022 |
| Intel         | JSL MRD                     | Desktop     | [f567ba0a06](https://linux-hardware.org/?probe=f567ba0a06) | Dec 24, 2022 |
| MSI           | H510M BOMBER                | Desktop     | [bb7a4c8457](https://linux-hardware.org/?probe=bb7a4c8457) | Dec 23, 2022 |
| Phytium       | D2000                       | Server      | [cafd5716ad](https://linux-hardware.org/?probe=cafd5716ad) | Dec 22, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [5fd1a2d6e1](https://linux-hardware.org/?probe=5fd1a2d6e1) | Dec 21, 2022 |
| Timi          | TM1612                      | Notebook    | [3e7f998f8d](https://linux-hardware.org/?probe=3e7f998f8d) | Dec 21, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [37de981132](https://linux-hardware.org/?probe=37de981132) | Dec 21, 2022 |
| Lenovo        | ThinkPad T460s 20F9A02PC... | Notebook    | [da548ee1cb](https://linux-hardware.org/?probe=da548ee1cb) | Dec 21, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [b270e219ba](https://linux-hardware.org/?probe=b270e219ba) | Dec 20, 2022 |
| Timi          | TM1612                      | Notebook    | [0400dd08c6](https://linux-hardware.org/?probe=0400dd08c6) | Dec 20, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [c4170b9ea3](https://linux-hardware.org/?probe=c4170b9ea3) | Dec 20, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [525bdfe9c0](https://linux-hardware.org/?probe=525bdfe9c0) | Dec 20, 2022 |
| Timi          | TM1612                      | Notebook    | [12efe96e3b](https://linux-hardware.org/?probe=12efe96e3b) | Dec 20, 2022 |
| Timi          | TM1612                      | Notebook    | [428430456f](https://linux-hardware.org/?probe=428430456f) | Dec 20, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [d1d5c6a19e](https://linux-hardware.org/?probe=d1d5c6a19e) | Dec 19, 2022 |
| Unknown       | Unknown                     | Soc         | [4a4114c957](https://linux-hardware.org/?probe=4a4114c957) | Dec 18, 2022 |
| Unknown       | Unknown                     | Soc         | [78a211835b](https://linux-hardware.org/?probe=78a211835b) | Dec 18, 2022 |
| Dell          | 0J1C3P A00                  | Desktop     | [1bd9b328b2](https://linux-hardware.org/?probe=1bd9b328b2) | Dec 17, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [e4ba0262b4](https://linux-hardware.org/?probe=e4ba0262b4) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [1a9c49eb4f](https://linux-hardware.org/?probe=1a9c49eb4f) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d872d58e4c](https://linux-hardware.org/?probe=d872d58e4c) | Dec 15, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [11e15101d3](https://linux-hardware.org/?probe=11e15101d3) | Dec 14, 2022 |
| Dell          | 06WXJT A01                  | Server      | [452bad8c1f](https://linux-hardware.org/?probe=452bad8c1f) | Dec 13, 2022 |
| ASUSTek       | Z10PH-D16 Series            | Desktop     | [18911cf243](https://linux-hardware.org/?probe=18911cf243) | Dec 13, 2022 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [559c3f32f8](https://linux-hardware.org/?probe=559c3f32f8) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [eb0d410f64](https://linux-hardware.org/?probe=eb0d410f64) | Dec 12, 2022 |
| Dell          | 0NK5PH A00                  | Desktop     | [08b0ff8839](https://linux-hardware.org/?probe=08b0ff8839) | Dec 12, 2022 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [89da872b13](https://linux-hardware.org/?probe=89da872b13) | Dec 12, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7541ce9ac6](https://linux-hardware.org/?probe=7541ce9ac6) | Dec 11, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [ebdb63b56f](https://linux-hardware.org/?probe=ebdb63b56f) | Dec 10, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [247beb66fb](https://linux-hardware.org/?probe=247beb66fb) | Dec 10, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [2534d396c6](https://linux-hardware.org/?probe=2534d396c6) | Dec 10, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [573736f441](https://linux-hardware.org/?probe=573736f441) | Dec 10, 2022 |
| Huanan        | X99-T8D V1.0                | Desktop     | [e4bd42a26b](https://linux-hardware.org/?probe=e4bd42a26b) | Dec 09, 2022 |
| Dell          | 06WXJT A01                  | Server      | [e2eb41854d](https://linux-hardware.org/?probe=e2eb41854d) | Dec 09, 2022 |
| Dell          | 06WXJT A01                  | Server      | [2f52fdbb5b](https://linux-hardware.org/?probe=2f52fdbb5b) | Dec 08, 2022 |
| Dell          | 06WXJT A01                  | Server      | [219cc5461b](https://linux-hardware.org/?probe=219cc5461b) | Dec 08, 2022 |
| Jumper        | EZpad                       | Tablet      | [68b8181601](https://linux-hardware.org/?probe=68b8181601) | Dec 07, 2022 |
| Lenovo        | ThinkPad Z61t 9441MY4       | Notebook    | [9ddc30d9b9](https://linux-hardware.org/?probe=9ddc30d9b9) | Dec 07, 2022 |
| HUAWEI        | HUAWEIPGU-WBY0              | Soc         | [b4f452d2d8](https://linux-hardware.org/?probe=b4f452d2d8) | Dec 06, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [b2aac5194c](https://linux-hardware.org/?probe=b2aac5194c) | Dec 06, 2022 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [eb86e5af95](https://linux-hardware.org/?probe=eb86e5af95) | Dec 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [8032977c84](https://linux-hardware.org/?probe=8032977c84) | Dec 05, 2022 |
| Lenovo        | ThinkPad neo 14 21DN0009... | Notebook    | [80c8d84387](https://linux-hardware.org/?probe=80c8d84387) | Dec 05, 2022 |
| HP            | ZHAN 66 Pro 14 inch G5 N... | Notebook    | [b2b5c92aeb](https://linux-hardware.org/?probe=b2b5c92aeb) | Dec 04, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9fec7bdfdc](https://linux-hardware.org/?probe=9fec7bdfdc) | Dec 04, 2022 |
| MECHREVO      | X3 Series GK7CP6R           | Notebook    | [7990b26bbf](https://linux-hardware.org/?probe=7990b26bbf) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [f93dd5ad2d](https://linux-hardware.org/?probe=f93dd5ad2d) | Dec 03, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [85e1d9b8bc](https://linux-hardware.org/?probe=85e1d9b8bc) | Dec 03, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [2cef9980e6](https://linux-hardware.org/?probe=2cef9980e6) | Dec 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [1fdf6ffce7](https://linux-hardware.org/?probe=1fdf6ffce7) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [40111c09eb](https://linux-hardware.org/?probe=40111c09eb) | Dec 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [b0bf36f700](https://linux-hardware.org/?probe=b0bf36f700) | Dec 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [f5a5a30379](https://linux-hardware.org/?probe=f5a5a30379) | Dec 01, 2022 |
| ONDA          | M3 miniPC VER               | Desktop     | [35f4c45eb5](https://linux-hardware.org/?probe=35f4c45eb5) | Dec 01, 2022 |
| Dell          | Vostro 3480                 | Notebook    | [bf353a87c5](https://linux-hardware.org/?probe=bf353a87c5) | Dec 01, 2022 |
| Pegatron      | BYT-X1                      | Desktop     | [edadb85201](https://linux-hardware.org/?probe=edadb85201) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | Desktop     | [b248df8671](https://linux-hardware.org/?probe=b248df8671) | Nov 30, 2022 |
| Intel         | H81U                        | Notebook    | [87a1cceaae](https://linux-hardware.org/?probe=87a1cceaae) | Nov 29, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [8d0514a0df](https://linux-hardware.org/?probe=8d0514a0df) | Nov 28, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [4f937eabac](https://linux-hardware.org/?probe=4f937eabac) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [f0d9943604](https://linux-hardware.org/?probe=f0d9943604) | Nov 28, 2022 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [fc54a7e10e](https://linux-hardware.org/?probe=fc54a7e10e) | Nov 27, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [f168cc5b93](https://linux-hardware.org/?probe=f168cc5b93) | Nov 27, 2022 |
| Lenovo        | ThinkPad Z61t 9441MY4       | Notebook    | [e24f9d12e5](https://linux-hardware.org/?probe=e24f9d12e5) | Nov 25, 2022 |
| Dell          | Inspiron 5488               | Notebook    | [32b350c3f6](https://linux-hardware.org/?probe=32b350c3f6) | Nov 25, 2022 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [4ef7a46399](https://linux-hardware.org/?probe=4ef7a46399) | Nov 25, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [8a27b5d8b3](https://linux-hardware.org/?probe=8a27b5d8b3) | Nov 24, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [60732590be](https://linux-hardware.org/?probe=60732590be) | Nov 24, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [d742abf044](https://linux-hardware.org/?probe=d742abf044) | Nov 23, 2022 |
| Sony          | SVD1321L2EW                 | Notebook    | [2fcc5aa10a](https://linux-hardware.org/?probe=2fcc5aa10a) | Nov 23, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [cac488b207](https://linux-hardware.org/?probe=cac488b207) | Nov 21, 2022 |
| Dell          | 06WXJT A01                  | Server      | [d6726fca7e](https://linux-hardware.org/?probe=d6726fca7e) | Nov 21, 2022 |
| Dell          | 06WXJT A01                  | Server      | [d4fee9fdf4](https://linux-hardware.org/?probe=d4fee9fdf4) | Nov 21, 2022 |
| Lenovo        | ThinkPad 10 20C1CTO1WW      | Tablet      | [f5e2cc92e2](https://linux-hardware.org/?probe=f5e2cc92e2) | Nov 19, 2022 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [fcce3d8a66](https://linux-hardware.org/?probe=fcce3d8a66) | Nov 18, 2022 |
| Intel         | NUC11ATBC4 M53051-302       | Mini pc     | [b03e6d95e5](https://linux-hardware.org/?probe=b03e6d95e5) | Nov 18, 2022 |
| GuoGuang      | IC2M1028N-3                 | Desktop     | [32351ceb62](https://linux-hardware.org/?probe=32351ceb62) | Nov 16, 2022 |
| HP            | 212B                        | Desktop     | [e1c7e7693e](https://linux-hardware.org/?probe=e1c7e7693e) | Nov 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [a3c41dcc96](https://linux-hardware.org/?probe=a3c41dcc96) | Nov 16, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [55f47f2c19](https://linux-hardware.org/?probe=55f47f2c19) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [1104a26017](https://linux-hardware.org/?probe=1104a26017) | Nov 16, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [340f38c8e2](https://linux-hardware.org/?probe=340f38c8e2) | Nov 15, 2022 |
| Lenovo        | 3716 SDK0K17763 WIN 1801... | Desktop     | [93c2091f01](https://linux-hardware.org/?probe=93c2091f01) | Nov 15, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [346303c711](https://linux-hardware.org/?probe=346303c711) | Nov 14, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [2e29461f3b](https://linux-hardware.org/?probe=2e29461f3b) | Nov 13, 2022 |
| Lenovo        | XiaoXinPro 14ACH 2021 82... | Notebook    | [d74b37eebb](https://linux-hardware.org/?probe=d74b37eebb) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0A... | Notebook    | [016d7c275d](https://linux-hardware.org/?probe=016d7c275d) | Nov 13, 2022 |
| Timi          | Redmi G 2022                | Notebook    | [86f8128511](https://linux-hardware.org/?probe=86f8128511) | Nov 12, 2022 |
| AZW           | SER V01                     | Mini pc     | [5123518533](https://linux-hardware.org/?probe=5123518533) | Nov 12, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3d18010536](https://linux-hardware.org/?probe=3d18010536) | Nov 12, 2022 |
| GreatWall     | TN140A2                     | Notebook    | [4bc596cd45](https://linux-hardware.org/?probe=4bc596cd45) | Nov 10, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [9f4cb2a547](https://linux-hardware.org/?probe=9f4cb2a547) | Nov 09, 2022 |
| Dell          | 0CNWVK A02                  | Desktop     | [726074bce6](https://linux-hardware.org/?probe=726074bce6) | Nov 09, 2022 |
| Dell          | 0CNWVK A02                  | Desktop     | [3ac38eb9be](https://linux-hardware.org/?probe=3ac38eb9be) | Nov 09, 2022 |
| Unknown       | Unknown                     | Soc         | [ccda18b6b6](https://linux-hardware.org/?probe=ccda18b6b6) | Nov 08, 2022 |
| Intel         | NUC8i7HVB J68196-503        | Mini pc     | [71a3658f21](https://linux-hardware.org/?probe=71a3658f21) | Nov 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [ff3d968ae9](https://linux-hardware.org/?probe=ff3d968ae9) | Nov 08, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [0fa75a005b](https://linux-hardware.org/?probe=0fa75a005b) | Nov 08, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [010836bb97](https://linux-hardware.org/?probe=010836bb97) | Nov 07, 2022 |
| IBM           | M97IP SIT                   | Desktop     | [78703d62ae](https://linux-hardware.org/?probe=78703d62ae) | Nov 07, 2022 |
| ONDA          | M3 miniPC VER               | Desktop     | [d485a7def3](https://linux-hardware.org/?probe=d485a7def3) | Nov 07, 2022 |
| IBM           | M97IP SIT                   | Desktop     | [0301b99674](https://linux-hardware.org/?probe=0301b99674) | Nov 07, 2022 |
| MSI           | 880GMS-E41                  | Desktop     | [2f53fa13ed](https://linux-hardware.org/?probe=2f53fa13ed) | Nov 06, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [e5abd4f928](https://linux-hardware.org/?probe=e5abd4f928) | Nov 06, 2022 |
| Acer          | Aspire V3-572G              | Notebook    | [77f939bab4](https://linux-hardware.org/?probe=77f939bab4) | Nov 05, 2022 |
| Clevo         | Modified by dsanke          | Notebook    | [b0c6c10d48](https://linux-hardware.org/?probe=b0c6c10d48) | Nov 05, 2022 |
| COLORFUL      | X15 XS 22                   | Notebook    | [38bc70c9b2](https://linux-hardware.org/?probe=38bc70c9b2) | Nov 04, 2022 |
| COLORFUL      | X15 XS 22                   | Notebook    | [342a90f101](https://linux-hardware.org/?probe=342a90f101) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa1a843244](https://linux-hardware.org/?probe=aa1a843244) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [0a55753066](https://linux-hardware.org/?probe=0a55753066) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [0e60d35498](https://linux-hardware.org/?probe=0e60d35498) | Nov 04, 2022 |
| Intel         | ChiefRiver                  | Desktop     | [1e1f44f251](https://linux-hardware.org/?probe=1e1f44f251) | Nov 04, 2022 |
| Dell          | 0CNWVK A02                  | Desktop     | [9017e31507](https://linux-hardware.org/?probe=9017e31507) | Nov 04, 2022 |
| Intel         | ChiefRiver                  | Desktop     | [64e4630da2](https://linux-hardware.org/?probe=64e4630da2) | Nov 04, 2022 |
| Lenovo        | Legion Y9000X IAH7 82TF     | Notebook    | [73ba8f75b7](https://linux-hardware.org/?probe=73ba8f75b7) | Nov 04, 2022 |
| Phytium       | D2000                       | Server      | [481bd29f0e](https://linux-hardware.org/?probe=481bd29f0e) | Nov 04, 2022 |
| Phytium       | D2000                       | Server      | [3e26835339](https://linux-hardware.org/?probe=3e26835339) | Nov 04, 2022 |
| Dell          | 0N0992 A01                  | Desktop     | [6f4decf3b2](https://linux-hardware.org/?probe=6f4decf3b2) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4457bb7b7e](https://linux-hardware.org/?probe=4457bb7b7e) | Nov 03, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [dda5d2dd10](https://linux-hardware.org/?probe=dda5d2dd10) | Nov 03, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [c0f68304d1](https://linux-hardware.org/?probe=c0f68304d1) | Nov 03, 2022 |
| GPD           | P3 MAX                      | Notebook    | [8b198da775](https://linux-hardware.org/?probe=8b198da775) | Nov 02, 2022 |
| GPD           | P3 MAX                      | Notebook    | [aea8f8bb50](https://linux-hardware.org/?probe=aea8f8bb50) | Nov 02, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [dbacfbd3b0](https://linux-hardware.org/?probe=dbacfbd3b0) | Nov 02, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [a0029fb797](https://linux-hardware.org/?probe=a0029fb797) | Nov 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [bc4f9a5a35](https://linux-hardware.org/?probe=bc4f9a5a35) | Nov 02, 2022 |
| Notebook      | P65xHP                      | Notebook    | [68d40fd2c7](https://linux-hardware.org/?probe=68d40fd2c7) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [48c0ef6251](https://linux-hardware.org/?probe=48c0ef6251) | Nov 02, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [4c80b212c6](https://linux-hardware.org/?probe=4c80b212c6) | Nov 01, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [4e92800709](https://linux-hardware.org/?probe=4e92800709) | Nov 01, 2022 |
| HP            | 829E                        | Mini pc     | [f568895fbb](https://linux-hardware.org/?probe=f568895fbb) | Nov 01, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [1cc623c804](https://linux-hardware.org/?probe=1cc623c804) | Nov 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [f87c0b1010](https://linux-hardware.org/?probe=f87c0b1010) | Nov 01, 2022 |
| OEM           | H310MD4                     | Desktop     | [947bf0d86f](https://linux-hardware.org/?probe=947bf0d86f) | Nov 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [0e92fb8c99](https://linux-hardware.org/?probe=0e92fb8c99) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [673c23713c](https://linux-hardware.org/?probe=673c23713c) | Oct 30, 2022 |
| Huanan        | H510-D4 V4.0                | Desktop     | [89b298973c](https://linux-hardware.org/?probe=89b298973c) | Oct 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [a517f2e2dd](https://linux-hardware.org/?probe=a517f2e2dd) | Oct 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [03f3800569](https://linux-hardware.org/?probe=03f3800569) | Oct 29, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [0dde1fbb38](https://linux-hardware.org/?probe=0dde1fbb38) | Oct 28, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [8cf64e81cd](https://linux-hardware.org/?probe=8cf64e81cd) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [806e4d754d](https://linux-hardware.org/?probe=806e4d754d) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [d6ccf0a2d8](https://linux-hardware.org/?probe=d6ccf0a2d8) | Oct 28, 2022 |
| THTF          | CR F860-T1                  | Notebook    | [9f0a52783f](https://linux-hardware.org/?probe=9f0a52783f) | Oct 27, 2022 |
| THTF          | CR F860-T1                  | Notebook    | [0e20f4f61a](https://linux-hardware.org/?probe=0e20f4f61a) | Oct 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [79b9335389](https://linux-hardware.org/?probe=79b9335389) | Oct 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [07a0af33a1](https://linux-hardware.org/?probe=07a0af33a1) | Oct 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [3ba090d9a2](https://linux-hardware.org/?probe=3ba090d9a2) | Oct 26, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [0e38f0e485](https://linux-hardware.org/?probe=0e38f0e485) | Oct 26, 2022 |
| Phytium       | D2000                       | Server      | [f3f6092888](https://linux-hardware.org/?probe=f3f6092888) | Oct 26, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [5b6f2b76da](https://linux-hardware.org/?probe=5b6f2b76da) | Oct 25, 2022 |
| Dell          | 0MWYPT A02                  | Desktop     | [cf186994cc](https://linux-hardware.org/?probe=cf186994cc) | Oct 25, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [3dbec91bce](https://linux-hardware.org/?probe=3dbec91bce) | Oct 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [50e747dd27](https://linux-hardware.org/?probe=50e747dd27) | Oct 23, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [e31e22263a](https://linux-hardware.org/?probe=e31e22263a) | Oct 23, 2022 |
| NORCO         | BPC-7951                    | Desktop     | [7612662684](https://linux-hardware.org/?probe=7612662684) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [a66d2944a8](https://linux-hardware.org/?probe=a66d2944a8) | Oct 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [0a198cb541](https://linux-hardware.org/?probe=0a198cb541) | Oct 18, 2022 |
| Phytium       | D2000                       | Server      | [9459c517ee](https://linux-hardware.org/?probe=9459c517ee) | Oct 18, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [f5eec71426](https://linux-hardware.org/?probe=f5eec71426) | Oct 18, 2022 |
| Phytium       | D2000                       | Server      | [e43b580add](https://linux-hardware.org/?probe=e43b580add) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7afa527ad7](https://linux-hardware.org/?probe=7afa527ad7) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [547c973486](https://linux-hardware.org/?probe=547c973486) | Oct 17, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [8ce5134a88](https://linux-hardware.org/?probe=8ce5134a88) | Oct 17, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [5fbae9cfcf](https://linux-hardware.org/?probe=5fbae9cfcf) | Oct 17, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [d49a7e728d](https://linux-hardware.org/?probe=d49a7e728d) | Oct 17, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [156e3942e5](https://linux-hardware.org/?probe=156e3942e5) | Oct 16, 2022 |
| Intel         | NUC7i5BNB J31144-303        | Mini pc     | [452cd6dfd3](https://linux-hardware.org/?probe=452cd6dfd3) | Oct 14, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [f9c2c298c4](https://linux-hardware.org/?probe=f9c2c298c4) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [ca42d57a93](https://linux-hardware.org/?probe=ca42d57a93) | Oct 14, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [07b0072cfb](https://linux-hardware.org/?probe=07b0072cfb) | Oct 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [2fa12ac832](https://linux-hardware.org/?probe=2fa12ac832) | Oct 13, 2022 |
| AMD           | A88                         | Desktop     | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [b4a34edd03](https://linux-hardware.org/?probe=b4a34edd03) | Oct 11, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [04cb107be2](https://linux-hardware.org/?probe=04cb107be2) | Oct 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [c88027a227](https://linux-hardware.org/?probe=c88027a227) | Oct 11, 2022 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [bf283ab356](https://linux-hardware.org/?probe=bf283ab356) | Oct 11, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [42b7bc6ee4](https://linux-hardware.org/?probe=42b7bc6ee4) | Oct 10, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [f2b2df8e8c](https://linux-hardware.org/?probe=f2b2df8e8c) | Oct 08, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [b161e7fe73](https://linux-hardware.org/?probe=b161e7fe73) | Oct 08, 2022 |
| ASUSTek       | V-P8H67E                    | Desktop     | [b4f0f561d2](https://linux-hardware.org/?probe=b4f0f561d2) | Oct 08, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [bacb30816f](https://linux-hardware.org/?probe=bacb30816f) | Oct 07, 2022 |
| ASUSTek       | ProArt Studiobook H7600Z... | Notebook    | [5db7aac5d3](https://linux-hardware.org/?probe=5db7aac5d3) | Oct 07, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [108ff1fbdd](https://linux-hardware.org/?probe=108ff1fbdd) | Oct 07, 2022 |
| HUAWEI        | L410 KLVU-WDU0              | Notebook    | [00edb23106](https://linux-hardware.org/?probe=00edb23106) | Oct 07, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | Notebook    | [8a49ad19f4](https://linux-hardware.org/?probe=8a49ad19f4) | Oct 06, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [150cd334ca](https://linux-hardware.org/?probe=150cd334ca) | Oct 05, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [7ac647f707](https://linux-hardware.org/?probe=7ac647f707) | Oct 05, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | Notebook    | [27d780177e](https://linux-hardware.org/?probe=27d780177e) | Oct 05, 2022 |
| Acer          | S50-54                      | Notebook    | [7680195105](https://linux-hardware.org/?probe=7680195105) | Oct 04, 2022 |
| GPD           | G1621-02                    | Notebook    | [1f88eb2bec](https://linux-hardware.org/?probe=1f88eb2bec) | Oct 03, 2022 |
| OEM           | Unknown                     | Desktop     | [306d50f7e3](https://linux-hardware.org/?probe=306d50f7e3) | Oct 03, 2022 |
| Acer          | S50-54                      | Notebook    | [a7ff4f9792](https://linux-hardware.org/?probe=a7ff4f9792) | Oct 02, 2022 |
| Phytium       | FT2000/4                    | Server      | [5f7f5d61af](https://linux-hardware.org/?probe=5f7f5d61af) | Oct 02, 2022 |
| Unknown       | Xiaobao Nas I               | Soc         | [d74d764466](https://linux-hardware.org/?probe=d74d764466) | Oct 01, 2022 |
| Phytium       | FT2000/4                    | Server      | [c8aa4d1457](https://linux-hardware.org/?probe=c8aa4d1457) | Sep 30, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [703687bcd7](https://linux-hardware.org/?probe=703687bcd7) | Sep 30, 2022 |
| OEM           | Unknown                     | Desktop     | [68b7e03b06](https://linux-hardware.org/?probe=68b7e03b06) | Sep 29, 2022 |
| Phytium       | FT2000/4                    | Server      | [ff17710900](https://linux-hardware.org/?probe=ff17710900) | Sep 29, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [b12e5d06a3](https://linux-hardware.org/?probe=b12e5d06a3) | Sep 28, 2022 |
| Timi          | TM1612                      | Notebook    | [ad37b74e1e](https://linux-hardware.org/?probe=ad37b74e1e) | Sep 27, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2A... | Notebook    | [ce132fc63e](https://linux-hardware.org/?probe=ce132fc63e) | Sep 27, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [f750ea8b83](https://linux-hardware.org/?probe=f750ea8b83) | Sep 26, 2022 |
| AZW           | SER V01                     | Mini pc     | [b6337c3dc4](https://linux-hardware.org/?probe=b6337c3dc4) | Sep 26, 2022 |
| Timi          | TM1612                      | Notebook    | [a7c23ad10b](https://linux-hardware.org/?probe=a7c23ad10b) | Sep 26, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | Notebook    | [5cff3798b0](https://linux-hardware.org/?probe=5cff3798b0) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | Notebook    | [b32a413aa9](https://linux-hardware.org/?probe=b32a413aa9) | Sep 25, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [f35b53ca7c](https://linux-hardware.org/?probe=f35b53ca7c) | Sep 25, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [18246c5a9e](https://linux-hardware.org/?probe=18246c5a9e) | Sep 25, 2022 |
| NEC Comput... | PC-VK25LCZDM                | Notebook    | [97ab1f723e](https://linux-hardware.org/?probe=97ab1f723e) | Sep 23, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [aa0a31a88d](https://linux-hardware.org/?probe=aa0a31a88d) | Sep 23, 2022 |
| Mbenben       | Mai II                      | Notebook    | [2cfb10385b](https://linux-hardware.org/?probe=2cfb10385b) | Sep 22, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [c1edc96aa7](https://linux-hardware.org/?probe=c1edc96aa7) | Sep 21, 2022 |
| Inspur        | CE520F                      | Soc         | [b8ea59e9f8](https://linux-hardware.org/?probe=b8ea59e9f8) | Sep 21, 2022 |
| Timi          | TM1612                      | Notebook    | [3d9866e9ff](https://linux-hardware.org/?probe=3d9866e9ff) | Sep 20, 2022 |
| ASRock        | E3V5 Performance Gaming/... | Desktop     | [3653dbd804](https://linux-hardware.org/?probe=3653dbd804) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [b84e8d2682](https://linux-hardware.org/?probe=b84e8d2682) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [4779dfc2b0](https://linux-hardware.org/?probe=4779dfc2b0) | Sep 20, 2022 |
| GreatWall     | Unknown                     | Notebook    | [12ee24a7c7](https://linux-hardware.org/?probe=12ee24a7c7) | Sep 20, 2022 |
| GreatWall     | TN140A2                     | Notebook    | [2c4ddb8e4b](https://linux-hardware.org/?probe=2c4ddb8e4b) | Sep 20, 2022 |
| Lenovo        | ThinkPad SL400 2743AQC      | Notebook    | [beb74c65cc](https://linux-hardware.org/?probe=beb74c65cc) | Sep 19, 2022 |
| AZW           | GK55                        | Desktop     | [9a9019eee6](https://linux-hardware.org/?probe=9a9019eee6) | Sep 19, 2022 |
| Lenovo        | ThinkPad E480 20KNA040CD    | Notebook    | [8cd233ffbb](https://linux-hardware.org/?probe=8cd233ffbb) | Sep 19, 2022 |
| Unknown       | Unknown                     | Notebook    | [fab82ec455](https://linux-hardware.org/?probe=fab82ec455) | Sep 18, 2022 |
| Lenovo        | Legion Y9000X IAH7 82TF     | Notebook    | [3b63a75571](https://linux-hardware.org/?probe=3b63a75571) | Sep 16, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [4dce87f7fa](https://linux-hardware.org/?probe=4dce87f7fa) | Sep 16, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [750bf03293](https://linux-hardware.org/?probe=750bf03293) | Sep 14, 2022 |
| Timi          | TM1604                      | Notebook    | [80f52c9545](https://linux-hardware.org/?probe=80f52c9545) | Sep 14, 2022 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [1b7cb7f0d2](https://linux-hardware.org/?probe=1b7cb7f0d2) | Sep 14, 2022 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [0ac056f016](https://linux-hardware.org/?probe=0ac056f016) | Sep 14, 2022 |
| ONDA          | M3 miniPC VER               | Desktop     | [81ebde1d65](https://linux-hardware.org/?probe=81ebde1d65) | Sep 13, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [d666daaeb2](https://linux-hardware.org/?probe=d666daaeb2) | Sep 13, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [ad3cd5381f](https://linux-hardware.org/?probe=ad3cd5381f) | Sep 13, 2022 |
| Unknown       | Unknown                     | Soc         | [abccb6d05a](https://linux-hardware.org/?probe=abccb6d05a) | Sep 12, 2022 |
| Unknown       | Unknown                     | Soc         | [1e94b50834](https://linux-hardware.org/?probe=1e94b50834) | Sep 12, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [9f244f4236](https://linux-hardware.org/?probe=9f244f4236) | Sep 12, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [c55fd8d477](https://linux-hardware.org/?probe=c55fd8d477) | Sep 11, 2022 |
| Colorful T... | H510M-D M.2 V20 V20         | Desktop     | [9b25859acf](https://linux-hardware.org/?probe=9b25859acf) | Sep 11, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [697d152bcc](https://linux-hardware.org/?probe=697d152bcc) | Sep 11, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2e0d41f272](https://linux-hardware.org/?probe=2e0d41f272) | Sep 10, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [06ee689632](https://linux-hardware.org/?probe=06ee689632) | Sep 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [a0c1db14a0](https://linux-hardware.org/?probe=a0c1db14a0) | Sep 09, 2022 |
| ONDA          | M3 miniPC VER               | Desktop     | [40f73e6e82](https://linux-hardware.org/?probe=40f73e6e82) | Sep 07, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| Dell          | Precision 3571              | Notebook    | [d9939fbfd4](https://linux-hardware.org/?probe=d9939fbfd4) | Sep 05, 2022 |
| Timi          | TM1709                      | Notebook    | [2fb5436031](https://linux-hardware.org/?probe=2fb5436031) | Sep 04, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d02a951b89](https://linux-hardware.org/?probe=d02a951b89) | Sep 04, 2022 |
| Lenovo        | ThinkPad E450 20DCA087CD    | Notebook    | [26928f83da](https://linux-hardware.org/?probe=26928f83da) | Sep 04, 2022 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [d510db88c4](https://linux-hardware.org/?probe=d510db88c4) | Sep 02, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [6456a1b04f](https://linux-hardware.org/?probe=6456a1b04f) | Sep 02, 2022 |
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
| Unknown       | Unknown                     | Soc         | [23e67d3f72](https://linux-hardware.org/?probe=23e67d3f72) | Aug 10, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [9ac3c0b157](https://linux-hardware.org/?probe=9ac3c0b157) | Aug 09, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [1d8eaa7564](https://linux-hardware.org/?probe=1d8eaa7564) | Aug 08, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [949598482f](https://linux-hardware.org/?probe=949598482f) | Aug 07, 2022 |
| ASRock        | H81M-HDS                    | Desktop     | [1d636956f2](https://linux-hardware.org/?probe=1d636956f2) | Aug 07, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [054c0beb4f](https://linux-hardware.org/?probe=054c0beb4f) | Aug 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [7d2ea1146a](https://linux-hardware.org/?probe=7d2ea1146a) | Aug 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [dbafe167dc](https://linux-hardware.org/?probe=dbafe167dc) | Aug 06, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [c1d23f2838](https://linux-hardware.org/?probe=c1d23f2838) | Aug 06, 2022 |
| Unknown       | Unknown                     | Soc         | [8330cc179c](https://linux-hardware.org/?probe=8330cc179c) | Aug 04, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [7a3c7a2886](https://linux-hardware.org/?probe=7a3c7a2886) | Aug 04, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [28eaeed6dd](https://linux-hardware.org/?probe=28eaeed6dd) | Aug 04, 2022 |
| Lenovo        | ThinkPad E470c 20H3A000C... | Notebook    | [047888752c](https://linux-hardware.org/?probe=047888752c) | Aug 04, 2022 |
| Lenovo        | 102F NO DPK                 | Desktop     | [1a040c2717](https://linux-hardware.org/?probe=1a040c2717) | Aug 04, 2022 |
| Intel         | X99                         | Desktop     | [33e0d23783](https://linux-hardware.org/?probe=33e0d23783) | Aug 04, 2022 |
| Unknown       | Xiaobao Nas I               | Soc         | [052379f89e](https://linux-hardware.org/?probe=052379f89e) | Aug 04, 2022 |
| Google        | Dratini                     | Notebook    | [e61c92a95b](https://linux-hardware.org/?probe=e61c92a95b) | Aug 04, 2022 |
| Unknown       | Xiaobao Nas I               | Soc         | [68434806c3](https://linux-hardware.org/?probe=68434806c3) | Aug 03, 2022 |
| Notebook      | NH5xAx                      | Notebook    | [7716e60398](https://linux-hardware.org/?probe=7716e60398) | Aug 03, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [563bd9cecd](https://linux-hardware.org/?probe=563bd9cecd) | Aug 02, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [dd8b9dc221](https://linux-hardware.org/?probe=dd8b9dc221) | Aug 02, 2022 |
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
| Unknown       | Unknown                     | Soc         | [d1d5741aff](https://linux-hardware.org/?probe=d1d5741aff) | Jun 09, 2022 |
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
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [d4698d909e](https://linux-hardware.org/?probe=d4698d909e) | May 31, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2855e4c95](https://linux-hardware.org/?probe=e2855e4c95) | May 31, 2022 |
| Acer          | Aspire T5000                | Notebook    | [7bdeb5fb3b](https://linux-hardware.org/?probe=7bdeb5fb3b) | May 31, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/China/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 177       | 12.2%   |
| Ubuntu 18.04                 | 136       | 9.37%   |
| Ubuntu 22.04                 | 86        | 5.93%   |
| Debian 11                    | 76        | 5.24%   |
| Arch Rolling                 | 65        | 4.48%   |
| Arch                         | 50        | 3.45%   |
| Debian 10                    | 25        | 1.72%   |
| UOS 20                       | 23        | 1.59%   |
| OpenMandriva 4.3             | 23        | 1.59%   |
| openSUSE Tumbleweed-XXXXXXXX | 22        | 1.52%   |
| Manjaro                      | 22        | 1.52%   |
| Ubuntu 19.04                 | 21        | 1.45%   |
| OpenMandriva 4.2             | 20        | 1.38%   |
| Kylin V10                    | 20        | 1.38%   |
| Ubuntu 16.04                 | 19        | 1.31%   |
| Gentoo 2.8                   | 19        | 1.31%   |
| KDE neon 20.04               | 17        | 1.17%   |
| Debian 12                    | 17        | 1.17%   |
| Ubuntu 21.10                 | 16        | 1.1%    |
| Gentoo 2.7                   | 16        | 1.1%    |
| Ubuntu 21.04                 | 14        | 0.96%   |
| Ubuntu 19.10                 | 14        | 0.96%   |
| Ubuntu 22.10                 | 13        | 0.9%    |
| Fedora 33                    | 13        | 0.9%    |
| Linux Mint 20.1              | 12        | 0.83%   |
| CentOS 7                     | 12        | 0.83%   |
| Ubuntu 23.04                 | 11        | 0.76%   |
| CentOS 8                     | 11        | 0.76%   |
| ArcoLinux Rolling            | 11        | 0.76%   |
| OpenMandriva 23.03           | 10        | 0.69%   |
| Linux Mint 20.3              | 10        | 0.69%   |
| OpenMandriva 4.50            | 9         | 0.62%   |
| Gentoo 2.6                   | 9         | 0.62%   |
| Fedora 35                    | 9         | 0.62%   |
| Ubuntu 20.10                 | 8         | 0.55%   |
| Linux Mint 20.2              | 8         | 0.55%   |
| Fedora 38                    | 8         | 0.55%   |
| Fedora 36                    | 8         | 0.55%   |
| Fedora 34                    | 8         | 0.55%   |
| Fedora 32                    | 8         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 504       | 36.05%  |
| Debian       | 146       | 10.44%  |
| Arch         | 112       | 8.01%   |
| Manjaro      | 71        | 5.08%   |
| Fedora       | 66        | 4.72%   |
| OpenMandriva | 64        | 4.58%   |
| Linux Mint   | 47        | 3.36%   |
| Gentoo       | 45        | 3.22%   |
| Deepin       | 38        | 2.72%   |
| openSUSE     | 26        | 1.86%   |
| CentOS       | 25        | 1.79%   |
| Kylin        | 22        | 1.57%   |
| KDE neon     | 20        | 1.43%   |
| Atz          | 18        | 1.29%   |
| Kubuntu      | 16        | 1.14%   |
| SteamOS      | 14        | 1%      |
| Pop!_OS      | 14        | 1%      |
| Xubuntu      | 12        | 0.86%   |
| Ubuntu Unity | 12        | 0.86%   |
| ROSA         | 12        | 0.86%   |
| ArcoLinux    | 12        | 0.86%   |
| Kali         | 11        | 0.79%   |
| Elementary   | 10        | 0.72%   |
| Clear Linux  | 8         | 0.57%   |
| Zorin        | 6         | 0.43%   |
| BlackPanther | 4         | 0.29%   |
| Android      | 4         | 0.29%   |
| Ubuntu MATE  | 3         | 0.21%   |
| Trisquel     | 3         | 0.21%   |
| NFS Desktop  | 3         | 0.21%   |
| LMDE         | 3         | 0.21%   |
| Guix         | 3         | 0.21%   |
| Alpine       | 3         | 0.21%   |
| Ubuntu Kylin | 2         | 0.14%   |
| RHEL         | 2         | 0.14%   |
| RedFlag      | 2         | 0.14%   |
| Raspbian     | 2         | 0.14%   |
| Parabola     | 2         | 0.14%   |
| OpenEuler    | 2         | 0.14%   |
| MX           | 2         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 21        | 1.35%   |
| 5.10.14-desktop-1omv4002 | 19        | 1.23%   |
| 5.4.0-42-generic         | 15        | 0.97%   |
| 6.2.6-desktop-1omv2390   | 10        | 0.65%   |
| 5.15.0-56-generic        | 10        | 0.65%   |
| 5.13.0-30-generic        | 10        | 0.65%   |
| 5.10.0-8-amd64           | 10        | 0.65%   |
| 5.0.0-23-generic         | 10        | 0.65%   |
| 5.15.0-46-generic        | 9         | 0.58%   |
| 6.2.0-20-generic         | 8         | 0.52%   |
| 5.19.0-46-generic        | 8         | 0.52%   |
| 5.11.0-43-generic        | 8         | 0.52%   |
| 4.18.0-25-generic        | 8         | 0.52%   |
| 5.4.0-58-generic         | 7         | 0.45%   |
| 5.19.0-26-generic        | 7         | 0.45%   |
| 5.19.0-23-generic        | 7         | 0.45%   |
| 5.15.0-52-generic        | 7         | 0.45%   |
| 5.12.4-desktop-1omv4050  | 7         | 0.45%   |
| 5.11.0-27-generic        | 7         | 0.45%   |
| 5.10.0-21-amd64          | 7         | 0.45%   |
| 5.0.0-13-generic         | 7         | 0.45%   |
| 4.18.0-16-generic        | 7         | 0.45%   |
| 6.2.0-26-generic         | 6         | 0.39%   |
| 6.1.0-9-amd64            | 6         | 0.39%   |
| 5.8.0-50-generic         | 6         | 0.39%   |
| 5.4.0-74-generic         | 6         | 0.39%   |
| 5.4.0-73-generic         | 6         | 0.39%   |
| 5.4.0-48-generic         | 6         | 0.39%   |
| 5.4.0-33-generic         | 6         | 0.39%   |
| 5.4.0-29-generic         | 6         | 0.39%   |
| 5.3.0-46-generic         | 6         | 0.39%   |
| 5.19.0-41-generic        | 6         | 0.39%   |
| 5.15.0-67-generic        | 6         | 0.39%   |
| 5.15.0-58-generic        | 6         | 0.39%   |
| 5.15.0-53-generic        | 6         | 0.39%   |
| 5.15.0-41-generic        | 6         | 0.39%   |
| 5.15.0-25-generic        | 6         | 0.39%   |
| 5.11.0-34-generic        | 6         | 0.39%   |
| 4.15.0-142-generic       | 6         | 0.39%   |
| 5.8.0-63-generic         | 5         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 148       | 9.97%   |
| 5.15.0   | 107       | 7.21%   |
| 5.10.0   | 88        | 5.93%   |
| 4.15.0   | 65        | 4.38%   |
| 5.13.0   | 62        | 4.18%   |
| 5.11.0   | 60        | 4.04%   |
| 5.8.0    | 45        | 3.03%   |
| 5.19.0   | 45        | 3.03%   |
| 4.18.0   | 45        | 3.03%   |
| 5.0.0    | 44        | 2.96%   |
| 5.3.0    | 35        | 2.36%   |
| 4.19.0   | 29        | 1.95%   |
| 5.16.7   | 22        | 1.48%   |
| 5.10.14  | 19        | 1.28%   |
| 6.1.0    | 17        | 1.14%   |
| 6.2.0    | 15        | 1.01%   |
| 6.2.6    | 11        | 0.74%   |
| 5.14.0   | 11        | 0.74%   |
| 3.10.0   | 10        | 0.67%   |
| 5.4.18   | 8         | 0.54%   |
| 5.18.0   | 8         | 0.54%   |
| 5.16.0   | 8         | 0.54%   |
| 6.0.0    | 7         | 0.47%   |
| 5.6.14   | 7         | 0.47%   |
| 5.17.0   | 7         | 0.47%   |
| 5.12.4   | 7         | 0.47%   |
| 4.1.42   | 7         | 0.47%   |
| 6.3.5    | 6         | 0.4%    |
| 5.18.12  | 6         | 0.4%    |
| 6.3.3    | 5         | 0.34%   |
| 5.6.0    | 5         | 0.34%   |
| 5.17.5   | 5         | 0.34%   |
| 5.10.41  | 5         | 0.34%   |
| 5.10.36  | 5         | 0.34%   |
| 4.9.60   | 5         | 0.34%   |
| 4.19.147 | 5         | 0.34%   |
| 6.4.3    | 4         | 0.27%   |
| 6.4.0    | 4         | 0.27%   |
| 6.3.8    | 4         | 0.27%   |
| 6.2.9    | 4         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 186       | 12.68%  |
| 5.15    | 170       | 11.59%  |
| 5.10    | 163       | 11.11%  |
| 5.11    | 77        | 5.25%   |
| 5.13    | 73        | 4.98%   |
| 4.15    | 65        | 4.43%   |
| 5.8     | 61        | 4.16%   |
| 5.19    | 56        | 3.82%   |
| 5.0     | 48        | 3.27%   |
| 4.18    | 47        | 3.2%    |
| 5.16    | 45        | 3.07%   |
| 4.19    | 45        | 3.07%   |
| 6.1     | 43        | 2.93%   |
| 5.3     | 42        | 2.86%   |
| 6.2     | 40        | 2.73%   |
| 5.18    | 37        | 2.52%   |
| 5.14    | 29        | 1.98%   |
| 6.0     | 28        | 1.91%   |
| 5.17    | 27        | 1.84%   |
| 5.12    | 24        | 1.64%   |
| 6.3     | 22        | 1.5%    |
| 5.9     | 20        | 1.36%   |
| 5.6     | 19        | 1.3%    |
| 4.9     | 14        | 0.95%   |
| 6.4     | 13        | 0.89%   |
| 5.7     | 12        | 0.82%   |
| 3.10    | 12        | 0.82%   |
| 4.1     | 9         | 0.61%   |
| 5.5     | 8         | 0.55%   |
| 5.1     | 5         | 0.34%   |
| 4.4     | 4         | 0.27%   |
| 4.14    | 4         | 0.27%   |
| 4.13    | 3         | 0.2%    |
| 6.5     | 2         | 0.14%   |
| 5.2     | 2         | 0.14%   |
| 4.20    | 2         | 0.14%   |
| 3.4     | 2         | 0.14%   |
| 2.6     | 2         | 0.14%   |
| 4.6     | 1         | 0.07%   |
| 4.17    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 1273      | 93.26%  |
| aarch64     | 46        | 3.37%   |
| riscv64     | 11        | 0.81%   |
| i686        | 11        | 0.81%   |
| ppc64       | 7         | 0.51%   |
| armv7l      | 6         | 0.44%   |
| ppc64le     | 2         | 0.15%   |
| loongarch64 | 2         | 0.15%   |
| sparc64     | 1         | 0.07%   |
| sh4a        | 1         | 0.07%   |
| ppc         | 1         | 0.07%   |
| mips64      | 1         | 0.07%   |
| i586        | 1         | 0.07%   |
| armv8l      | 1         | 0.07%   |
| Unknown     | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 581       | 41.18%  |
| Unknown         | 253       | 17.93%  |
| KDE5            | 241       | 17.08%  |
| XFCE            | 102       | 7.23%   |
| X-Cinnamon      | 39        | 2.76%   |
| Deepin          | 37        | 2.62%   |
| KDE             | 35        | 2.48%   |
| MATE            | 19        | 1.35%   |
| i3              | 15        | 1.06%   |
| UKUI            | 13        | 0.92%   |
| Unity           | 11        | 0.78%   |
| Pantheon        | 10        | 0.71%   |
| Cinnamon        | 8         | 0.57%   |
| LXDE            | 7         | 0.5%    |
| LXQt            | 5         | 0.35%   |
| KDE4            | 5         | 0.35%   |
| Budgie          | 5         | 0.35%   |
| sway            | 4         | 0.28%   |
| GNOME Flashback | 4         | 0.28%   |
| GNOME Classic   | 4         | 0.28%   |
| Openbox         | 3         | 0.21%   |
| Hyprland        | 2         | 0.14%   |
| GNUstep         | 2         | 0.14%   |
| xmonad          | 1         | 0.07%   |
| Wayfire         | 1         | 0.07%   |
| qtile           | 1         | 0.07%   |
| default         | 1         | 0.07%   |
| bspwm           | 1         | 0.07%   |
| awesome         | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 951       | 67.78%  |
| Wayland | 224       | 15.97%  |
| Unknown | 128       | 9.12%   |
| Tty     | 100       | 7.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 587       | 42.08%  |
| SDDM    | 200       | 14.34%  |
| GDM3    | 192       | 13.76%  |
| GDM     | 188       | 13.48%  |
| LightDM | 174       | 12.47%  |
| TDM     | 43        | 3.08%   |
| KDM     | 4         | 0.29%   |
| LXDM    | 3         | 0.22%   |
| XDM     | 2         | 0.14%   |
| SLiM    | 2         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| zh_CN       | 614       | 44.2%   |
| en_US       | 489       | 35.21%  |
| Unknown     | 184       | 13.25%  |
| C           | 43        | 3.1%    |
| en_HK       | 16        | 1.15%   |
| en_GB       | 12        | 0.86%   |
| C.UTF8      | 6         | 0.43%   |
| mn_CN       | 4         | 0.29%   |
| ru_RU       | 3         | 0.22%   |
| en_AU       | 3         | 0.22%   |
| ja_JP       | 2         | 0.14%   |
| fr_FR       | 2         | 0.14%   |
| de_DE       | 2         | 0.14%   |
| zh_TW       | 1         | 0.07%   |
| th_TH       | 1         | 0.07%   |
| POSIX       | 1         | 0.07%   |
| en_ZA       | 1         | 0.07%   |
| en_US.UTF8  | 1         | 0.07%   |
| en_US.utf-8 | 1         | 0.07%   |
| en_US,UTF-8 | 1         | 0.07%   |
| en_SG       | 1         | 0.07%   |
| .en_US      | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 900       | 65.26%  |
| BIOS | 479       | 34.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Computers | Percent |
|------------|-----------|---------|
| Ext4       | 1049      | 75.85%  |
| Btrfs      | 144       | 10.41%  |
| Overlay    | 60        | 4.34%   |
| Xfs        | 56        | 4.05%   |
| Unknown    | 32        | 2.31%   |
| Tmpfs      | 20        | 1.45%   |
| Zfs        | 12        | 0.87%   |
| F2fs       | 4         | 0.29%   |
| Rootfs     | 3         | 0.22%   |
| XXXXXXX    | 1         | 0.07%   |
| Reiserfs   | 1         | 0.07%   |
| Fuse.sshfs | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 755       | 54.71%  |
| Unknown | 508       | 36.81%  |
| MBR     | 117       | 8.48%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1169      | 83.98%  |
| Yes       | 223       | 16.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 836       | 60.89%  |
| Yes       | 537       | 39.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 342       | 25.07%  |
| ASUSTek Computer               | 139       | 10.19%  |
| Dell                           | 134       | 9.82%   |
| Hewlett-Packard                | 104       | 7.62%   |
| HUAWEI                         | 56        | 4.11%   |
| Gigabyte Technology            | 56        | 4.11%   |
| Unknown                        | 52        | 3.81%   |
| MSI                            | 50        | 3.67%   |
| Timi                           | 40        | 2.93%   |
| Intel                          | 38        | 2.79%   |
| Acer                           | 34        | 2.49%   |
| Apple                          | 17        | 1.25%   |
| ASRock                         | 16        | 1.17%   |
| MECHREVO                       | 15        | 1.1%    |
| HASEE Computer                 | 14        | 1.03%   |
| Supermicro                     | 10        | 0.73%   |
| Phytium                        | 10        | 0.73%   |
| Toshiba                        | 9         | 0.66%   |
| Raspberry Pi Foundation        | 9         | 0.66%   |
| Microsoft                      | 9         | 0.66%   |
| GPD                            | 9         | 0.66%   |
| Valve                          | 8         | 0.59%   |
| Google                         | 8         | 0.59%   |
| Sony                           | 7         | 0.51%   |
| AMI                            | 7         | 0.51%   |
| Huanan                         | 6         | 0.44%   |
| GreatWall                      | 6         | 0.44%   |
| Colorful Technology            | 6         | 0.44%   |
| AZW                            | 6         | 0.44%   |
| TSINGHUA TONGFANG COMPUTER     | 5         | 0.37%   |
| Shanghai Zhaoxin Semiconductor | 5         | 0.37%   |
| OEM                            | 5         | 0.37%   |
| Inspur                         | 5         | 0.37%   |
| HONOR                          | 5         | 0.37%   |
| Samsung Electronics            | 4         | 0.29%   |
| Notebook                       | 4         | 0.29%   |
| Jumper                         | 4         | 0.29%   |
| Intel Client Systems           | 4         | 0.29%   |
| Fujitsu                        | 4         | 0.29%   |
| Win element                    | 3         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 67        | 4.91%   |
| ASUS All Series                     | 14        | 1.03%   |
| Valve Jupiter                       | 8         | 0.59%   |
| HUAWEI HLY-WX9XX                    | 8         | 0.59%   |
| Lenovo Legion R9000P2021H 82JQ      | 7         | 0.51%   |
| MSI MS-7B89                         | 6         | 0.44%   |
| TSINGHUA TONGFANG COMPUTER E500     | 5         | 0.37%   |
| Timi TM1701                         | 5         | 0.37%   |
| Timi RedmiBook Pro 15S              | 5         | 0.37%   |
| Supermicro Super Server             | 5         | 0.37%   |
| Phytium FT-2000/4                   | 5         | 0.37%   |
| Lenovo Legion R7000 2020 82B6       | 5         | 0.37%   |
| ASUS TUF Gaming B550M-PLUS          | 5         | 0.37%   |
| AMI Aptio CRB                       | 5         | 0.37%   |
| Shanghai Zhaoxin ZXE CRB            | 4         | 0.29%   |
| MSI MS-7C94                         | 4         | 0.29%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM   | 4         | 0.29%   |
| Lenovo XiaoXin-15ARE 2020 81YR      | 4         | 0.29%   |
| Lenovo ThinkStation P520 30BFSG3Y00 | 4         | 0.29%   |
| Lenovo ThinkBook 15p Gen 2 21B1     | 4         | 0.29%   |
| Lenovo Legion Y7000 81FW            | 4         | 0.29%   |
| HUAWEI NBLK-WAX9X                   | 4         | 0.29%   |
| HUAWEI KPRC-WX0                     | 4         | 0.29%   |
| HUAWEI BOHK-WAX9X                   | 4         | 0.29%   |
| Dell XPS 15 9570                    | 4         | 0.29%   |
| Dell PowerEdge R730xd               | 4         | 0.29%   |
| Acer Swift SF314-512                | 4         | 0.29%   |
| Timi TM1709                         | 3         | 0.22%   |
| Timi TM1613                         | 3         | 0.22%   |
| Timi RedmiBook 14 II                | 3         | 0.22%   |
| RPi Raspberry Pi                    | 3         | 0.22%   |
| Phytium D2000                       | 3         | 0.22%   |
| Microsoft Surface Go                | 3         | 0.22%   |
| Lenovo ZHAOYANG K4e-ITL 82F8        | 3         | 0.22%   |
| Lenovo Yoga 14cACN 2021 82N7        | 3         | 0.22%   |
| Lenovo XiaoXinPro-13IML 2019 81XB   | 3         | 0.22%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN   | 3         | 0.22%   |
| Lenovo ThinkBook 14p Gen 2 20YN     | 3         | 0.22%   |
| Lenovo ThinkBook 14 G2 ITL 20VD     | 3         | 0.22%   |
| Intel NUC11ATKC4                    | 3         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 122       | 8.94%   |
| Unknown                         | 67        | 4.91%   |
| Lenovo Legion                   | 36        | 2.64%   |
| Dell Inspiron                   | 32        | 2.35%   |
| Lenovo ThinkBook                | 25        | 1.83%   |
| ASUS TUF                        | 22        | 1.61%   |
| ASUS ROG                        | 22        | 1.61%   |
| Dell Latitude                   | 20        | 1.47%   |
| HP EliteBook                    | 19        | 1.39%   |
| Dell Precision                  | 19        | 1.39%   |
| Dell OptiPlex                   | 18        | 1.32%   |
| ASUS PRIME                      | 18        | 1.32%   |
| Acer Aspire                     | 17        | 1.25%   |
| HP ZHAN                         | 16        | 1.17%   |
| HP OMEN                         | 16        | 1.17%   |
| Lenovo Yoga                     | 14        | 1.03%   |
| Lenovo ThinkCentre              | 14        | 1.03%   |
| Dell XPS                        | 14        | 1.03%   |
| ASUS All                        | 14        | 1.03%   |
| Lenovo ZHAOYANG                 | 13        | 0.95%   |
| Lenovo IdeaPad                  | 13        | 0.95%   |
| Dell PowerEdge                  | 13        | 0.95%   |
| Timi RedmiBook                  | 12        | 0.88%   |
| Lenovo ThinkStation             | 11        | 0.81%   |
| Acer Swift                      | 11        | 0.81%   |
| RPi Raspberry                   | 9         | 0.66%   |
| Microsoft Surface               | 9         | 0.66%   |
| HP ProBook                      | 9         | 0.66%   |
| HP ENVY                         | 9         | 0.66%   |
| Dell Vostro                     | 9         | 0.66%   |
| Valve Jupiter                   | 8         | 0.59%   |
| HUAWEI HLY-WX9XX                | 8         | 0.59%   |
| Lenovo XiaoXinPro               | 7         | 0.51%   |
| MSI MS-7B89                     | 6         | 0.44%   |
| HP Pavilion                     | 6         | 0.44%   |
| TSINGHUA TONGFANG COMPUTER E500 | 5         | 0.37%   |
| Toshiba Satellite               | 5         | 0.37%   |
| Timi TM1701                     | 5         | 0.37%   |
| Supermicro Super                | 5         | 0.37%   |
| Phytium FT-2000                 | 5         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 186       | 13.64%  |
| 2020    | 174       | 12.76%  |
| 2019    | 154       | 11.29%  |
| 2018    | 145       | 10.63%  |
| 2022    | 111       | 8.14%   |
| 2017    | 95        | 6.96%   |
| 2015    | 78        | 5.72%   |
| 2012    | 72        | 5.28%   |
| 2014    | 59        | 4.33%   |
| 2013    | 59        | 4.33%   |
| 2016    | 57        | 4.18%   |
| Unknown | 52        | 3.81%   |
| 2011    | 44        | 3.23%   |
| 2023    | 23        | 1.69%   |
| 2008    | 17        | 1.25%   |
| 2010    | 14        | 1.03%   |
| 2009    | 13        | 0.95%   |
| 2007    | 8         | 0.59%   |
| 2006    | 3         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 773       | 56.67%  |
| Desktop        | 412       | 30.21%  |
| Server         | 53        | 3.89%   |
| Mini pc        | 39        | 2.86%   |
| System on chip | 29        | 2.13%   |
| Tablet         | 26        | 1.91%   |
| Convertible    | 19        | 1.39%   |
| All in one     | 9         | 0.66%   |
| Phone          | 4         | 0.29%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1268      | 92.42%  |
| Enabled  | 104       | 7.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1357      | 99.49%  |
| Yes  | 7         | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 317       | 22.95%  |
| 8.01-16.0       | 305       | 22.09%  |
| 4.01-8.0        | 278       | 20.13%  |
| 32.01-64.0      | 167       | 12.09%  |
| 3.01-4.0        | 130       | 9.41%   |
| 64.01-256.0     | 71        | 5.14%   |
| 24.01-32.0      | 39        | 2.82%   |
| 1.01-2.0        | 29        | 2.1%    |
| Unknown         | 15        | 1.09%   |
| More than 256.0 | 12        | 0.87%   |
| 0.51-1.0        | 12        | 0.87%   |
| 0.01-0.5        | 3         | 0.22%   |
| 2.01-3.0        | 2         | 0.14%   |
| 0               | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 396       | 26.83%  |
| 2.01-3.0    | 365       | 24.73%  |
| 4.01-8.0    | 252       | 17.07%  |
| 3.01-4.0    | 213       | 14.43%  |
| 0.51-1.0    | 85        | 5.76%   |
| 8.01-16.0   | 71        | 4.81%   |
| 0.01-0.5    | 41        | 2.78%   |
| Unknown     | 21        | 1.42%   |
| 16.01-24.0  | 16        | 1.08%   |
| 24.01-32.0  | 6         | 0.41%   |
| 32.01-64.0  | 5         | 0.34%   |
| 64.01-256.0 | 5         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 761       | 54.91%  |
| 2       | 430       | 31.02%  |
| 3       | 105       | 7.58%   |
| 4       | 39        | 2.81%   |
| 5       | 18        | 1.3%    |
| 0       | 11        | 0.79%   |
| 6       | 6         | 0.43%   |
| 10      | 4         | 0.29%   |
| 9       | 3         | 0.22%   |
| 8       | 2         | 0.14%   |
| 46      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 32      | 1         | 0.07%   |
| 27      | 1         | 0.07%   |
| 21      | 1         | 0.07%   |
| 11      | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1189      | 86.79%  |
| Yes       | 181       | 13.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1072      | 78.13%  |
| No        | 300       | 21.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1050      | 76.64%  |
| No        | 320       | 23.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 884       | 64.24%  |
| No        | 492       | 35.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| China   | 1364      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Beijing          | 259       | 17.95%  |
| Shenzhen         | 115       | 7.97%   |
| Shanghai         | 115       | 7.97%   |
| Guangzhou        | 96        | 6.65%   |
| Hangzhou         | 58        | 4.02%   |
| Chengdu          | 47        | 3.26%   |
| Wuhan            | 37        | 2.56%   |
| Nanjing          | 30        | 2.08%   |
| Xi'an            | 24        | 1.66%   |
| Jinrongjie       | 20        | 1.39%   |
| Chongqing        | 20        | 1.39%   |
| Zhengzhou        | 19        | 1.32%   |
| Tianjin          | 19        | 1.32%   |
| Xuhui            | 18        | 1.25%   |
| Foshan           | 17        | 1.18%   |
| Haidian          | 16        | 1.11%   |
| Suzhou           | 15        | 1.04%   |
| Changsha         | 15        | 1.04%   |
| Qingdao          | 14        | 0.97%   |
| Kunming          | 14        | 0.97%   |
| Dongguan         | 14        | 0.97%   |
| Hefei            | 13        | 0.9%    |
| Shenyang         | 12        | 0.83%   |
| Nanning          | 12        | 0.83%   |
| Jinan            | 12        | 0.83%   |
| Huangpu          | 12        | 0.83%   |
| Xiamen           | 11        | 0.76%   |
| Fuzhou           | 10        | 0.69%   |
| Dalian           | 10        | 0.69%   |
| Nanhao           | 9         | 0.62%   |
| Bieligutai       | 8         | 0.55%   |
| Shijiazhuang     | 7         | 0.49%   |
| Putuo            | 7         | 0.49%   |
| Hohhot           | 7         | 0.49%   |
| Guiyang          | 7         | 0.49%   |
| Xicheng District | 6         | 0.42%   |
| Pudong           | 6         | 0.42%   |
| Ningbo           | 6         | 0.42%   |
| Jianshui         | 6         | 0.42%   |
| Hongkou          | 6         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 350       | 465    | 17.02%  |
| WDC                         | 259       | 358    | 12.59%  |
| Seagate                     | 233       | 429    | 11.33%  |
| Toshiba                     | 118       | 175    | 5.74%   |
| SanDisk                     | 106       | 125    | 5.15%   |
| Unknown                     | 100       | 132    | 4.86%   |
| Intel                       | 67        | 102    | 3.26%   |
| SK hynix                    | 65        | 80     | 3.16%   |
| Kingston                    | 62        | 76     | 3.01%   |
| Micron Technology           | 43        | 45     | 2.09%   |
| HGST                        | 43        | 74     | 2.09%   |
| Silicon Motion              | 31        | 40     | 1.51%   |
| Plextor                     | 29        | 33     | 1.41%   |
| Hitachi                     | 23        | 34     | 1.12%   |
| Crucial                     | 22        | 26     | 1.07%   |
| Lenovo                      | 21        | 30     | 1.02%   |
| KIOXIA                      | 20        | 24     | 0.97%   |
| LITEON                      | 19        | 23     | 0.92%   |
| Unknown                     | 19        | 23     | 0.92%   |
| Phison                      | 15        | 19     | 0.73%   |
| A-DATA Technology           | 15        | 20     | 0.73%   |
| Yangtze Memory Technologies | 14        | 16     | 0.68%   |
| Hewlett-Packard             | 14        | 17     | 0.68%   |
| FORESEE                     | 14        | 17     | 0.68%   |
| ZHITAI                      | 13        | 16     | 0.63%   |
| China                       | 13        | 23     | 0.63%   |
| Apple                       | 12        | 12     | 0.58%   |
| Teclast                     | 11        | 11     | 0.53%   |
| JMicron Technology          | 11        | 9      | 0.53%   |
| Colorful                    | 11        | 13     | 0.53%   |
| MAXIO Technology (Hangzhou) | 10        | 11     | 0.49%   |
| GALAX                       | 10        | 10     | 0.49%   |
| Netac                       | 9         | 10     | 0.44%   |
| Hikvision                   | 9         | 13     | 0.44%   |
| KIOXIA-EXCERIA              | 8         | 11     | 0.39%   |
| Kingston Technology Company | 8         | 9      | 0.39%   |
| GLOWAY                      | 8         | 11     | 0.39%   |
| Phison Electronics          | 7         | 7      | 0.34%   |
| Kingchuxing                 | 7         | 7      | 0.34%   |
| Fujitsu                     | 7         | 7      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                            | 23        | 1.02%   |
| Samsung NVMe SSD Drive 512GB                        | 23        | 1.02%   |
| SanDisk NVMe SSD Drive 512GB                        | 20        | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 19        | 0.85%   |
| Unknown                                             | 19        | 0.85%   |
| Seagate ST1000LM035-1RK172 1TB                      | 17        | 0.76%   |
| Samsung SSD 860 EVO 500GB                           | 17        | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB                      | 16        | 0.71%   |
| HGST HTS721010A9E630 1TB                            | 16        | 0.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 15        | 0.67%   |
| Seagate ST1000DM003-1SB102 1TB                      | 14        | 0.62%   |
| Samsung MZVLB512HBJQ-000L2 512GB                    | 14        | 0.62%   |
| Seagate ST1000LM048-2E7172 1TB                      | 13        | 0.58%   |
| SanDisk NVMe SSD Drive 1TB                          | 12        | 0.53%   |
| Samsung NVMe SSD Drive 256GB                        | 12        | 0.53%   |
| Samsung NVMe SSD Drive 1024GB                       | 12        | 0.53%   |
| Samsung SSD 980 1TB                                 | 11        | 0.49%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 10        | 0.45%   |
| SK hynix NVMe SSD Drive 512GB                       | 10        | 0.45%   |
| Seagate ST500LT012-1DG142 500GB                     | 10        | 0.45%   |
| Seagate ST500DM002-1BD142 500GB                     | 10        | 0.45%   |
| Samsung MZVLB512HAJQ-00000 512GB                    | 10        | 0.45%   |
| Unknown MMC Card  64GB                              | 9         | 0.4%    |
| Toshiba MQ01ABD100 1TB                              | 9         | 0.4%    |
| SK hynix SKHynix_HFS512GDE9X084N 512GB              | 9         | 0.4%    |
| Seagate ST500LM021-1KJ152 500GB                     | 9         | 0.4%    |
| Seagate ST2000LM007-1R8174 2TB                      | 9         | 0.4%    |
| HGST HTS725050A7E630 500GB                          | 9         | 0.4%    |
| WDC WD10EZEX-08M2NA0 1TB                            | 8         | 0.36%   |
| Unknown MMC Card  128GB                             | 8         | 0.36%   |
| Toshiba NVMe SSD Drive 128GB                        | 8         | 0.36%   |
| Seagate ST6000NM0115-1YZ110 6TB                     | 8         | 0.36%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 8         | 0.36%   |
| Plextor PX-128M6S 128GB SSD                         | 8         | 0.36%   |
| Kingston SA400S37480G 480GB SSD                     | 8         | 0.36%   |
| Toshiba DT01ACA200 2TB                              | 7         | 0.31%   |
| Seagate ST3500418AS 500GB                           | 7         | 0.31%   |
| Samsung NVMe SSD Drive 1TB                          | 7         | 0.31%   |
| Samsung NVMe SSD Drive 128GB                        | 7         | 0.31%   |
| JMicron Generic 512GB                               | 7         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 231       | 426    | 39.42%  |
| WDC                 | 186       | 258    | 31.74%  |
| Toshiba             | 53        | 95     | 9.04%   |
| HGST                | 43        | 74     | 7.34%   |
| Hitachi             | 23        | 34     | 3.92%   |
| Samsung Electronics | 10        | 11     | 1.71%   |
| JMicron Technology  | 7         | 7      | 1.19%   |
| Fujitsu             | 7         | 7      | 1.19%   |
| Pear 2TB            | 5         | 5      | 0.85%   |
| External            | 5         | 8      | 0.85%   |
| ASMT                | 2         | 2      | 0.34%   |
| ACASIS              | 2         | 2      | 0.34%   |
| Unknown             | 2         | 3      | 0.34%   |
| SSK                 | 1         | 1      | 0.17%   |
| LIO-ORG             | 1         | 9      | 0.17%   |
| IBM H0              | 1         | 1      | 0.17%   |
| HGST HTS            | 1         | 1      | 0.17%   |
| Hewlett-Packard     | 1         | 1      | 0.17%   |
| GOKE                | 1         | 1      | 0.17%   |
| FORESEE             | 1         | 1      | 0.17%   |
| ExcelStor           | 1         | 1      | 0.17%   |
| DELLBOSS            | 1         | 1      | 0.17%   |
| Apple               | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 112       | 161    | 20.18%  |
| Kingston            | 39        | 49     | 7.03%   |
| SanDisk             | 33        | 36     | 5.95%   |
| Toshiba             | 28        | 34     | 5.05%   |
| Plextor             | 26        | 29     | 4.68%   |
| Intel               | 25        | 36     | 4.5%    |
| LITEON              | 18        | 22     | 3.24%   |
| WDC                 | 17        | 22     | 3.06%   |
| Lenovo              | 15        | 19     | 2.7%    |
| Crucial             | 15        | 19     | 2.7%    |
| China               | 13        | 23     | 2.34%   |
| Micron Technology   | 12        | 13     | 2.16%   |
| A-DATA Technology   | 12        | 16     | 2.16%   |
| Teclast             | 11        | 11     | 1.98%   |
| GALAX               | 10        | 10     | 1.8%    |
| Netac               | 8         | 9      | 1.44%   |
| Kingchuxing         | 7         | 7      | 1.26%   |
| FORESEE             | 7         | 8      | 1.26%   |
| Unknown             | 7         | 9      | 1.26%   |
| ZHITAI              | 6         | 7      | 1.08%   |
| SK hynix            | 6         | 6      | 1.08%   |
| GLOWAY              | 6         | 9      | 1.08%   |
| Unknown             | 5         | 6      | 0.9%    |
| Transcend           | 5         | 6      | 0.9%    |
| Colorful            | 5         | 5      | 0.9%    |
| Apple               | 5         | 5      | 0.9%    |
| Q200                | 4         | 7      | 0.72%   |
| LITEONIT            | 4         | 4      | 0.72%   |
| Hewlett-Packard     | 4         | 7      | 0.72%   |
| tigo                | 3         | 3      | 0.54%   |
| Phison              | 3         | 4      | 0.54%   |
| Lexar               | 3         | 3      | 0.54%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.54%   |
| faspeed             | 3         | 3      | 0.54%   |
| Vaseky              | 2         | 2      | 0.36%   |
| UNIC2               | 2         | 2      | 0.36%   |
| TO Exter            | 2         | 2      | 0.36%   |
| StoreJet            | 2         | 2      | 0.36%   |
| Pear                | 2         | 8      | 0.36%   |
| OCZ                 | 2         | 2      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 710       | 973    | 38.4%   |
| HDD     | 505       | 950    | 27.31%  |
| SSD     | 486       | 728    | 26.28%  |
| MMC     | 93        | 120    | 5.03%   |
| Unknown | 55        | 66     | 2.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 781       | 1615   | 46.6%   |
| NVMe | 708       | 969    | 42.24%  |
| SAS  | 94        | 133    | 5.61%   |
| MMC  | 93        | 120    | 5.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 534       | 858    | 52.15%  |
| 0.51-1.0   | 326       | 412    | 31.84%  |
| 1.01-2.0   | 79        | 131    | 7.71%   |
| 4.01-10.0  | 28        | 177    | 2.73%   |
| 3.01-4.0   | 23        | 37     | 2.25%   |
| 2.01-3.0   | 19        | 35     | 1.86%   |
| 10.01-20.0 | 15        | 28     | 1.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 350       | 24.67%  |
| 101-250        | 337       | 23.75%  |
| 501-1000       | 201       | 14.16%  |
| 51-100         | 118       | 8.32%   |
| 1001-2000      | 113       | 7.96%   |
| 1-20           | 82        | 5.78%   |
| More than 3000 | 75        | 5.29%   |
| 21-50          | 61        | 4.3%    |
| Unknown        | 43        | 3.03%   |
| 2001-3000      | 39        | 2.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 555       | 38.17%  |
| 21-50          | 240       | 16.51%  |
| 101-250        | 196       | 13.48%  |
| 51-100         | 157       | 10.8%   |
| 251-500        | 116       | 7.98%   |
| 501-1000       | 62        | 4.26%   |
| 1001-2000      | 44        | 3.03%   |
| Unknown        | 43        | 2.96%   |
| More than 3000 | 24        | 1.65%   |
| 2001-3000      | 17        | 1.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB              | 2         | 2      | 2.47%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 2.47%   |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 2      | 2.47%   |
| Seagate ST31000524AS 1TB            | 2         | 2      | 2.47%   |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 2      | 2.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 2      | 2.47%   |
| HGST HTS725050A7E630 500GB          | 2         | 2      | 2.47%   |
| HGST HTS721010A9E630 1TB            | 2         | 2      | 2.47%   |
| Crucial CT240M500SSD1 240GB         | 2         | 2      | 2.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 1      | 1.23%   |
| WDC WD5003ABYZ-011FA0 500GB         | 1         | 1      | 1.23%   |
| WDC WD5003ABYX-01WERA1 500GB        | 1         | 1      | 1.23%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1         | 1      | 1.23%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 1         | 1      | 1.23%   |
| WDC WD5000AAKX-083CA1 500GB         | 1         | 1      | 1.23%   |
| WDC WD5000AAKX-00PWEA0 500GB        | 1         | 1      | 1.23%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 1.23%   |
| WDC WD5000AAKX-0 500GB              | 1         | 1      | 1.23%   |
| WDC WD40EJRX-89AKWY0 4TB            | 1         | 3      | 1.23%   |
| WDC WD20EARX-00PASB0 2TB            | 1         | 1      | 1.23%   |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 1      | 1.23%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 1.23%   |
| WDC WD10JPLX-00MBPT1 1TB            | 1         | 2      | 1.23%   |
| WDC WD10EZEX-00BN5A0 1TB            | 1         | 1      | 1.23%   |
| WDC WD100EZAZ-11TDBA0 10TB          | 1         | 2      | 1.23%   |
| WDC WD10 JPVX-75JC3T0 1TB           | 1         | 1      | 1.23%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.23%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 1.23%   |
| Toshiba MK2555GSX 250GB             | 1         | 1      | 1.23%   |
| Toshiba DT01ACA300 3TB              | 1         | 1      | 1.23%   |
| Toshiba DT01ACA100 1TB              | 1         | 1      | 1.23%   |
| Seagate ST980811AS 80GB             | 1         | 1      | 1.23%   |
| Seagate ST750LM028-1KK162 752GB     | 1         | 1      | 1.23%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 1.23%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 2      | 1.23%   |
| Seagate ST500DM009-2DM14C 500GB     | 1         | 1      | 1.23%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 1.23%   |
| Seagate ST5000AS0011-1L5178 5TB     | 1         | 1      | 1.23%   |
| Seagate ST4000VX007-2DT166 4TB      | 1         | 1      | 1.23%   |
| Seagate ST3500413AS 500GB           | 1         | 1      | 1.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 22     | 22.78%  |
| WDC                 | 17        | 21     | 21.52%  |
| Toshiba             | 7         | 7      | 8.86%   |
| Samsung Electronics | 5         | 16     | 6.33%   |
| Intel               | 4         | 4      | 5.06%   |
| Hitachi             | 4         | 4      | 5.06%   |
| HGST                | 4         | 4      | 5.06%   |
| Fujitsu             | 3         | 3      | 3.8%    |
| Crucial             | 3         | 3      | 3.8%    |
| SanDisk             | 2         | 2      | 2.53%   |
| Plextor             | 2         | 2      | 2.53%   |
| GLOWAY              | 2         | 5      | 2.53%   |
| A-DATA Technology   | 2         | 3      | 2.53%   |
| Ramsta              | 1         | 1      | 1.27%   |
| Netac               | 1         | 1      | 1.27%   |
| Lenovo              | 1         | 1      | 1.27%   |
| Hewlett-Packard     | 1         | 1      | 1.27%   |
| ExcelStor           | 1         | 1      | 1.27%   |
| Colorful            | 1         | 1      | 1.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 18        | 22     | 33.96%  |
| WDC       | 16        | 20     | 30.19%  |
| Toshiba   | 7         | 7      | 13.21%  |
| Hitachi   | 4         | 4      | 7.55%   |
| HGST      | 4         | 4      | 7.55%   |
| Fujitsu   | 3         | 3      | 5.66%   |
| ExcelStor | 1         | 1      | 1.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 52        | 61     | 68.42%  |
| SSD  | 19        | 36     | 25%     |
| NVMe | 5         | 5      | 6.58%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 11.11%  |
| Seagate ST31500341AS 1TB          | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 11.11%  |
| Samsung Electronics HS06THB 64GB  | 1         | 1      | 11.11%  |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 11.11%  |
| Phison ESO128GTLC9-E8C-2 128GB    | 1         | 1      | 11.11%  |
| HGST HUH728080ALN600 8TB          | 1         | 1      | 11.11%  |
| HGST HTS725050A7E630 500GB        | 1         | 2      | 11.11%  |
| Hewlett-Packard SSD S700 500GB    | 1         | 2      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 33.33%  |
| Seagate             | 2         | 2      | 22.22%  |
| HGST                | 2         | 3      | 22.22%  |
| Phison              | 1         | 1      | 11.11%  |
| Hewlett-Packard     | 1         | 2      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 700       | 1316   | 47.3%   |
| Works    | 698       | 1408   | 47.16%  |
| Malfunc  | 73        | 102    | 4.93%   |
| Failed   | 9         | 11     | 0.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 777       | 42.55%  |
| Samsung Electronics              | 242       | 13.25%  |
| AMD                              | 196       | 10.73%  |
| SanDisk                          | 133       | 7.28%   |
| SK hynix                         | 58        | 3.18%   |
| Silicon Motion                   | 49        | 2.68%   |
| Toshiba America Info Systems     | 42        | 2.3%    |
| Micron Technology                | 31        | 1.7%    |
| Kingston Technology Company      | 31        | 1.7%    |
| Phison Electronics               | 27        | 1.48%   |
| KIOXIA                           | 26        | 1.42%   |
| Marvell Technology Group         | 25        | 1.37%   |
| Yangtze Memory Technologies      | 22        | 1.2%    |
| ASMedia Technology               | 18        | 0.99%   |
| Broadcom / LSI                   | 16        | 0.88%   |
| MAXIO Technology (Hangzhou)      | 15        | 0.82%   |
| Shenzhen Longsys Electronics     | 9         | 0.49%   |
| LSI Logic / Symbios Logic        | 9         | 0.49%   |
| Biwin Storage Technology         | 9         | 0.49%   |
| Micron/Crucial Technology        | 8         | 0.44%   |
| Zhaoxin                          | 7         | 0.38%   |
| Lite-On Technology               | 7         | 0.38%   |
| Apple                            | 6         | 0.33%   |
| ADATA Technology                 | 6         | 0.33%   |
| Union Memory (Shenzhen)          | 5         | 0.27%   |
| Solid State Storage Technology   | 5         | 0.27%   |
| JMicron Technology               | 5         | 0.27%   |
| IBM                              | 5         | 0.27%   |
| Huawei Technologies              | 4         | 0.22%   |
| Silicon Integrated Systems [SiS] | 3         | 0.16%   |
| O2 Micro                         | 3         | 0.16%   |
| Loongson Technology              | 3         | 0.16%   |
| Silicon Image                    | 2         | 0.11%   |
| Realtek Semiconductor            | 2         | 0.11%   |
| Phytium Technology               | 2         | 0.11%   |
| Mylex                            | 2         | 0.11%   |
| INNOGRIT                         | 2         | 0.11%   |
| Hefei DATANG Storage Technology  | 2         | 0.11%   |
| Beijing Starblaze Technology     | 2         | 0.11%   |
| ULi Electronics                  | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 156       | 7.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 123       | 6.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 72        | 3.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 52        | 2.57%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 46        | 2.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 45        | 2.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 43        | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 36        | 1.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 34        | 1.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 34        | 1.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 34        | 1.68%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 31        | 1.53%   |
| Samsung NVMe SSD Controller 980                                                | 31        | 1.53%   |
| AMD 400 Series Chipset SATA Controller                                         | 31        | 1.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 30        | 1.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 29        | 1.43%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 27        | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 27        | 1.34%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 25        | 1.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 1.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 1.14%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 22        | 1.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 22        | 1.09%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 22        | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                          | 20        | 0.99%   |
| AMD 500 Series Chipset SATA Controller                                         | 19        | 0.94%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 17        | 0.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 17        | 0.84%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 15        | 0.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 15        | 0.74%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 15        | 0.74%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 14        | 0.69%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 13        | 0.64%   |
| Intel SSD 660P Series                                                          | 13        | 0.64%   |
| Intel SATA Controller [RAID mode]                                              | 13        | 0.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 13        | 0.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 13        | 0.64%   |
| Phison PS5013 E13 NVMe Controller                                              | 12        | 0.59%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 12        | 0.59%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 12        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 881       | 48.7%   |
| NVMe | 712       | 39.36%  |
| RAID | 111       | 6.14%   |
| IDE  | 87        | 4.81%   |
| SAS  | 13        | 0.72%   |
| SCSI | 5         | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 957       | 70.16%  |
| AMD               | 319       | 23.39%  |
| ARM               | 23        | 1.69%   |
| Phytium           | 20        | 1.47%   |
| Unknown           | 12        | 0.88%   |
| CentaurHauls      | 9         | 0.66%   |
| CHRP IBM,8233-E8B | 5         | 0.37%   |
| sifive,u74-mc     | 4         | 0.29%   |
| QUALCOMM          | 4         | 0.29%   |
| sifive,bullet0    | 3         | 0.22%   |
| CHRP IBM,9131-52A | 2         | 0.15%   |
| thead,c906        | 1         | 0.07%   |
| PowerNV FP5466G2  | 1         | 0.07%   |
| PowerNV C829UAG3  | 1         | 0.07%   |
| Loongson          | 1         | 0.07%   |
| HISILICON         | 1         | 0.07%   |
| FSP-1             | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics         | 34        | 2.49%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 25        | 1.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 20        | 1.46%   |
| Intel Core i5-8250U CPU @ 1.60GHz              | 20        | 1.46%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 19        | 1.39%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 18        | 1.32%   |
| ARM Processor                                  | 17        | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 16        | 1.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 15        | 1.1%    |
| Intel Core i5-10210U CPU @ 1.60GHz             | 15        | 1.1%    |
| Intel 12th Gen Core i7-12700H                  | 15        | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz              | 14        | 1.02%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 13        | 0.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 12        | 0.88%   |
| AMD Ryzen 7 6800H with Radeon Graphics         | 12        | 0.88%   |
|                                                | 12        | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 11        | 0.81%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 11        | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 10        | 0.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 10        | 0.73%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 10        | 0.73%   |
| Intel 12th Gen Core i5-1240P                   | 10        | 0.73%   |
| Intel Core i5-8300H CPU @ 2.30GHz              | 9         | 0.66%   |
| Intel Celeron N5105 @ 2.00GHz                  | 9         | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 8         | 0.59%   |
| Intel Core i7-7800X CPU @ 3.50GHz              | 8         | 0.59%   |
| Intel Core i7-7700 CPU @ 3.60GHz               | 8         | 0.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 8         | 0.59%   |
| AMD Custom APU 0405                            | 8         | 0.59%   |
| Phytium FT-2000/4                              | 7         | 0.51%   |
| PHYTIUM D2000/8 E8C                            | 7         | 0.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 7         | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 7         | 0.51%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 7         | 0.51%   |
| Intel Core i7-10710U CPU @ 1.10GHz             | 7         | 0.51%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 7         | 0.51%   |
| Intel Core i5-5200U CPU @ 2.20GHz              | 7         | 0.51%   |
| Intel Celeron CPU J1900 @ 1.99GHz              | 7         | 0.51%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 7         | 0.51%   |
| AMD Ryzen 5 4600U with Radeon Graphics         | 7         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 265       | 19.41%  |
| Intel Core i7           | 253       | 18.53%  |
| Other                   | 229       | 16.78%  |
| AMD Ryzen 7             | 110       | 8.06%   |
| AMD Ryzen 5             | 93        | 6.81%   |
| Intel Xeon              | 67        | 4.91%   |
| Intel Core i3           | 62        | 4.54%   |
| Intel Celeron           | 51        | 3.74%   |
| Intel Pentium           | 23        | 1.68%   |
| Intel Atom              | 22        | 1.61%   |
| AMD Ryzen 9             | 21        | 1.54%   |
| Intel Core 2 Duo        | 20        | 1.47%   |
| AMD Ryzen 7 PRO         | 16        | 1.17%   |
| Intel Core i9           | 9         | 0.66%   |
| AMD A8                  | 9         | 0.66%   |
| Intel Core m3           | 7         | 0.51%   |
| AMD FX                  | 7         | 0.51%   |
| Intel Xeon Silver       | 6         | 0.44%   |
| Intel Pentium Silver    | 6         | 0.44%   |
| Intel Genuine           | 6         | 0.44%   |
| AMD Ryzen 5 PRO         | 6         | 0.44%   |
| AMD Athlon II X2        | 6         | 0.44%   |
| AMD A6                  | 6         | 0.44%   |
| AMD A10                 | 6         | 0.44%   |
| Intel Xeon Gold         | 5         | 0.37%   |
| Intel Pentium Dual      | 4         | 0.29%   |
| AMD Athlon X4           | 4         | 0.29%   |
| AMD Athlon              | 4         | 0.29%   |
| Intel Pentium Dual-Core | 3         | 0.22%   |
| Intel Core 2            | 3         | 0.22%   |
| AMD Ryzen 3             | 3         | 0.22%   |
| AMD EPYC                | 3         | 0.22%   |
| Intel Xeon Platinum     | 2         | 0.15%   |
| Intel Core M            | 2         | 0.15%   |
| Intel Core 2 Quad       | 2         | 0.15%   |
| ARM BCM                 | 2         | 0.15%   |
| ARM Allwinner           | 2         | 0.15%   |
| AMD E2                  | 2         | 0.15%   |
| AMD E                   | 2         | 0.15%   |
| AMD A4                  | 2         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 515       | 37.67%  |
| 2       | 329       | 24.07%  |
| 8       | 192       | 14.05%  |
| 6       | 175       | 12.8%   |
| 12      | 36        | 2.63%   |
| 16      | 23        | 1.68%   |
| 14      | 19        | 1.39%   |
| 1       | 18        | 1.32%   |
| Unknown | 15        | 1.1%    |
| 10      | 12        | 0.88%   |
| 24      | 10        | 0.73%   |
| 64      | 4         | 0.29%   |
| 32      | 4         | 0.29%   |
| 96      | 2         | 0.15%   |
| 48      | 2         | 0.15%   |
| 40      | 2         | 0.15%   |
| 36      | 2         | 0.15%   |
| 28      | 2         | 0.15%   |
| 20      | 2         | 0.15%   |
| 26      | 1         | 0.07%   |
| 22      | 1         | 0.07%   |
| 3       | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1294      | 94.8%   |
| 2       | 49        | 3.59%   |
| Unknown | 15        | 1.1%    |
| 3       | 4         | 0.29%   |
| 16      | 1         | 0.07%   |
| 6       | 1         | 0.07%   |
| 4       | 1         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1001      | 73.23%  |
| 1       | 344       | 25.16%  |
| Unknown | 15        | 1.1%    |
| 4       | 6         | 0.44%   |
| 8       | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1312      | 96.05%  |
| Unknown        | 46        | 3.37%   |
| 32-bit         | 5         | 0.37%   |
| 64-bit         | 3         | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 384       | 27.61%  |
| 0x906ea    | 60        | 4.31%   |
| 0x306a9    | 53        | 3.81%   |
| 0x306c3    | 49        | 3.52%   |
| 0x0a50000c | 42        | 3.02%   |
| 0x206a7    | 37        | 2.66%   |
| 0x806ec    | 36        | 2.59%   |
| 0x806ea    | 36        | 2.59%   |
| 0x806e9    | 33        | 2.37%   |
| 0x806c1    | 33        | 2.37%   |
| 0x506e3    | 32        | 2.3%    |
| 0x906e9    | 31        | 2.23%   |
| 0x08600106 | 30        | 2.16%   |
| 0x40651    | 24        | 1.73%   |
| 0x906a3    | 23        | 1.65%   |
| 0x306d4    | 20        | 1.44%   |
| 0x406e3    | 19        | 1.37%   |
| 0x08108102 | 17        | 1.22%   |
| 0x1067a    | 15        | 1.08%   |
| 0x08108109 | 15        | 1.08%   |
| 0x50654    | 14        | 1.01%   |
| 0x0a404102 | 14        | 1.01%   |
| 0xa0652    | 13        | 0.93%   |
| 0x806d1    | 12        | 0.86%   |
| 0x08600104 | 12        | 0.86%   |
| 0xa0655    | 11        | 0.79%   |
| 0x30678    | 11        | 0.79%   |
| 0x08701013 | 11        | 0.79%   |
| 0x906c0    | 10        | 0.72%   |
| 0x306f2    | 10        | 0.72%   |
| 0x50657    | 9         | 0.65%   |
| 0x90672    | 8         | 0.58%   |
| 0x706e5    | 8         | 0.58%   |
| 0x706a1    | 8         | 0.58%   |
| 0xa0660    | 7         | 0.5%    |
| 0x306e4    | 7         | 0.5%    |
| 0x06003106 | 7         | 0.5%    |
| 0xa0671    | 6         | 0.43%   |
| 0x806eb    | 6         | 0.43%   |
| 0x0a704103 | 6         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 268       | 19.6%   |
| Unknown          | 176       | 12.87%  |
| Haswell          | 113       | 8.27%   |
| Skylake          | 90        | 6.58%   |
| Zen 2            | 80        | 5.85%   |
| IvyBridge        | 79        | 5.78%   |
| Zen 3            | 74        | 5.41%   |
| TigerLake        | 56        | 4.1%    |
| CometLake        | 52        | 3.8%    |
| SandyBridge      | 49        | 3.58%   |
| Zen+             | 41        | 3%      |
| Silvermont       | 33        | 2.41%   |
| Alderlake Hybrid | 31        | 2.27%   |
| Icelake          | 30        | 2.19%   |
| Broadwell        | 30        | 2.19%   |
| Penryn           | 26        | 1.9%    |
| Zen              | 21        | 1.54%   |
| Goldmont plus    | 13        | 0.95%   |
| Piledriver       | 12        | 0.88%   |
| Westmere         | 11        | 0.8%    |
| Tremont          | 10        | 0.73%   |
| Steamroller      | 10        | 0.73%   |
| Core             | 10        | 0.73%   |
| K10              | 9         | 0.66%   |
| Goldmont         | 7         | 0.51%   |
| Bonnell          | 6         | 0.44%   |
| Puma             | 4         | 0.29%   |
| Nehalem          | 4         | 0.29%   |
| Excavator        | 4         | 0.29%   |
| Bobcat           | 4         | 0.29%   |
| P6               | 3         | 0.22%   |
| Sapphire Rapids  | 2         | 0.15%   |
| K10 Llano        | 2         | 0.15%   |
| Jaguar           | 2         | 0.15%   |
| Bulldozer        | 2         | 0.15%   |
| NetBurst         | 1         | 0.07%   |
| K8 Hammer        | 1         | 0.07%   |
| Gracemont        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 755       | 44.91%  |
| Nvidia                           | 459       | 27.31%  |
| AMD                              | 401       | 23.85%  |
| ASPEED Technology                | 22        | 1.31%   |
| Matrox Electronics Systems       | 21        | 1.25%   |
| Zhaoxin                          | 9         | 0.54%   |
| Phytium Technology               | 3         | 0.18%   |
| Loongson Technology              | 3         | 0.18%   |
| Silicon Integrated Systems [SiS] | 2         | 0.12%   |
| Silicon Motion                   | 1         | 0.06%   |
| Nanjing Ruixinview Technology    | 1         | 0.06%   |
| Moore Threads Technology         | 1         | 0.06%   |
| Huawei Technologies              | 1         | 0.06%   |
| Cirrus Logic                     | 1         | 0.06%   |
| 3DLabs                           | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 55        | 3.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 53        | 3.09%   |
| AMD Renoir                                                                               | 50        | 2.91%   |
| Intel UHD Graphics 620                                                                   | 44        | 2.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 44        | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 39        | 2.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 35        | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 34        | 1.98%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 32        | 1.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 1.75%   |
| Intel HD Graphics 630                                                                    | 28        | 1.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.63%   |
| AMD Rembrandt [Radeon 680M]                                                              | 28        | 1.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 26        | 1.51%   |
| Intel HD Graphics 620                                                                    | 26        | 1.51%   |
| Intel HD Graphics 530                                                                    | 26        | 1.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 24        | 1.4%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 22        | 1.28%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 22        | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 1.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 18        | 1.05%   |
| Nvidia GP108M [GeForce MX150]                                                            | 17        | 0.99%   |
| Nvidia GP108M [GeForce MX250]                                                            | 16        | 0.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 0.93%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 15        | 0.87%   |
| Intel JasperLake [UHD Graphics]                                                          | 15        | 0.87%   |
| Intel HD Graphics 5500                                                                   | 15        | 0.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 14        | 0.82%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 14        | 0.82%   |
| Nvidia TU117M [GeForce MX450]                                                            | 13        | 0.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 0.76%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 12        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 11        | 0.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 0.64%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 11        | 0.64%   |
| Nvidia TU117M                                                                            | 10        | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 458       | 33.33%  |
| 1 x AMD                           | 288       | 20.96%  |
| Intel + Nvidia                    | 232       | 16.89%  |
| 1 x Nvidia                        | 175       | 12.74%  |
| Intel + AMD                       | 45        | 3.28%   |
| AMD + Nvidia                      | 40        | 2.91%   |
| Other                             | 39        | 2.84%   |
| 1 x Matrox                        | 19        | 1.38%   |
| 2 x AMD                           | 17        | 1.24%   |
| 1 x ASPEED                        | 13        | 0.95%   |
| 1 x Zhaoxin                       | 9         | 0.66%   |
| 2 x Nvidia                        | 5         | 0.36%   |
| 2 x Intel                         | 5         | 0.36%   |
| Nvidia + ASPEED                   | 5         | 0.36%   |
| AMD + Matrox                      | 4         | 0.29%   |
| AMD + ASPEED                      | 4         | 0.29%   |
| 1 x Phytium Technology            | 3         | 0.22%   |
| 1 x SiS                           | 2         | 0.15%   |
| 1 x Loongson Technology           | 2         | 0.15%   |
| 1 x Silicon Motion                | 1         | 0.07%   |
| Nvidia + Huawei Technologies      | 1         | 0.07%   |
| 1 x Nanjing Ruixinview Technology | 1         | 0.07%   |
| 1 x Moore Threads Technology      | 1         | 0.07%   |
| 1 x Intel + 3 x Nvidia            | 1         | 0.07%   |
| Intel + 2 x Nvidia                | 1         | 0.07%   |
| 1 x Cirrus Logic                  | 1         | 0.07%   |
| AMD + Loongson Technology         | 1         | 0.07%   |
| AMD + 3DLabs                      | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 998       | 72.27%  |
| Proprietary | 236       | 17.09%  |
| Unknown     | 147       | 10.64%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 794       | 57.12%  |
| 1.01-2.0   | 173       | 12.45%  |
| 0.01-0.5   | 115       | 8.27%   |
| 0.51-1.0   | 103       | 7.41%   |
| 3.01-4.0   | 87        | 6.26%   |
| 5.01-6.0   | 44        | 3.17%   |
| 7.01-8.0   | 41        | 2.95%   |
| 8.01-16.0  | 13        | 0.94%   |
| 2.01-3.0   | 8         | 0.58%   |
| 4.01-5.0   | 6         | 0.43%   |
| 16.01-24.0 | 4         | 0.29%   |
| 24.01-32.0 | 2         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 159       | 12.01%  |
| AU Optronics            | 132       | 9.97%   |
| LG Display              | 113       | 8.53%   |
| Chimei Innolux          | 112       | 8.46%   |
| Dell                    | 106       | 8.01%   |
| AOC                     | 74        | 5.59%   |
| Lenovo                  | 71        | 5.36%   |
| Samsung Electronics     | 68        | 5.14%   |
| Sharp                   | 42        | 3.17%   |
| Philips                 | 42        | 3.17%   |
| CSO                     | 42        | 3.17%   |
| Goldstar                | 25        | 1.89%   |
| Hewlett-Packard         | 22        | 1.66%   |
| ViewSonic               | 21        | 1.59%   |
| TMX                     | 15        | 1.13%   |
| PANDA                   | 15        | 1.13%   |
| BenQ                    | 14        | 1.06%   |
| InfoVision              | 13        | 0.98%   |
| Apple                   | 13        | 0.98%   |
| Acer                    | 13        | 0.98%   |
| Xiaomi                  | 12        | 0.91%   |
| RTK                     | 11        | 0.83%   |
| HKC                     | 10        | 0.76%   |
| Mi                      | 8         | 0.6%    |
| IPS                     | 7         | 0.53%   |
| Valve                   | 6         | 0.45%   |
| Sony                    | 6         | 0.45%   |
| SGT                     | 6         | 0.45%   |
| Unknown                 | 6         | 0.45%   |
| Chi Mei Optoelectronics | 5         | 0.38%   |
| Unknown                 | 4         | 0.3%    |
| SKY                     | 4         | 0.3%    |
| Panasonic               | 4         | 0.3%    |
| JDI                     | 4         | 0.3%    |
| CHD                     | 4         | 0.3%    |
| Ancor Communications    | 4         | 0.3%    |
| LGD                     | 3         | 0.23%   |
| LG Electronics          | 3         | 0.23%   |
| Lenovo Group Limited    | 3         | 0.23%   |
| KOIOS                   | 3         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch | 14        | 1.03%   |
| Xiaomi Mi TV XMD004A 1920x1080 890x500mm 40.2-inch               | 9         | 0.66%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch          | 8         | 0.59%   |
| Dell P2422H DELA1C5 1920x1080 530x300mm 24.0-inch                | 8         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch | 8         | 0.59%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch            | 8         | 0.59%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch            | 7         | 0.52%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch   | 7         | 0.52%   |
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                 | 7         | 0.52%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch              | 6         | 0.44%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch          | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch | 6         | 0.44%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch            | 6         | 0.44%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch            | 6         | 0.44%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch    | 6         | 0.44%   |
| AOC 2790 AOC2790 1920x1080 598x336mm 27.0-inch                   | 6         | 0.44%   |
| Unknown                                                          | 6         | 0.44%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch          | 5         | 0.37%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch      | 5         | 0.37%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch            | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch | 5         | 0.37%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch            | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch   | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch    | 5         | 0.37%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch          | 4         | 0.29%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch          | 4         | 0.29%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch          | 4         | 0.29%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch      | 4         | 0.29%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch     | 4         | 0.29%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch     | 4         | 0.29%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch      | 4         | 0.29%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch       | 4         | 0.29%   |
| IPS DP IPS2700 3840x2160 619x348mm 28.0-inch                     | 4         | 0.29%   |
| InfoVision LCD Monitor IVO061F 1920x1080 344x194mm 15.5-inch     | 4         | 0.29%   |
| CSO LCD Monitor CSO076D 2560x1600 286x179mm 13.3-inch            | 4         | 0.29%   |
| CHD CHUD CHD0030 3840x2160 1394x784mm 63.0-inch                  | 4         | 0.29%   |
| BOE LCD Monitor BOE098E 1920x1080 344x194mm 15.5-inch            | 4         | 0.29%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch            | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO45ED 1920x1080 344x193mm 15.5-inch   | 4         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 639       | 49.92%  |
| 1366x768 (WXGA)    | 129       | 10.08%  |
| 3840x2160 (4K)     | 112       | 8.75%   |
| 2560x1440 (QHD)    | 85        | 6.64%   |
| 2560x1600          | 54        | 4.22%   |
| 1440x900 (WXGA+)   | 30        | 2.34%   |
| 1920x1200 (WUXGA)  | 23        | 1.8%    |
| 1600x900 (HD+)     | 21        | 1.64%   |
| 2880x1800          | 17        | 1.33%   |
| 1680x1050 (WSXGA+) | 17        | 1.33%   |
| 1280x1024 (SXGA)   | 16        | 1.25%   |
| 2160x1440          | 15        | 1.17%   |
| 3440x1440          | 12        | 0.94%   |
| Unknown            | 12        | 0.94%   |
| 1280x800 (WXGA)    | 11        | 0.86%   |
| 3200x2000          | 10        | 0.78%   |
| 800x1280           | 8         | 0.63%   |
| 2240x1400          | 6         | 0.47%   |
| 3840x2400          | 5         | 0.39%   |
| 2560x1080          | 5         | 0.39%   |
| 3072x1920          | 4         | 0.31%   |
| 3000x2000          | 3         | 0.23%   |
| 2736x1824          | 3         | 0.23%   |
| 2160x1350          | 3         | 0.23%   |
| 1800x1200          | 3         | 0.23%   |
| 3360x1080          | 2         | 0.16%   |
| 3286x1080          | 2         | 0.16%   |
| 2880x1920          | 2         | 0.16%   |
| 2520x1680          | 2         | 0.16%   |
| 2288x1287          | 2         | 0.16%   |
| 2256x1504          | 2         | 0.16%   |
| 2200x1650          | 2         | 0.16%   |
| 1920x1280          | 2         | 0.16%   |
| 1400x1050          | 2         | 0.16%   |
| 1024x768 (XGA)     | 2         | 0.16%   |
| 1024x600           | 2         | 0.16%   |
| 6400x2160          | 1         | 0.08%   |
| 5206x1080          | 1         | 0.08%   |
| 4480x1440          | 1         | 0.08%   |
| 4382x1080          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 241       | 18.22%  |
| 13      | 189       | 14.29%  |
| 14      | 172       | 13%     |
| 23      | 113       | 8.54%   |
| 24      | 93        | 7.03%   |
| 27      | 91        | 6.88%   |
| 21      | 59        | 4.46%   |
| 16      | 53        | 4.01%   |
| Unknown | 50        | 3.78%   |
| 17      | 39        | 2.95%   |
| 12      | 39        | 2.95%   |
| 19      | 24        | 1.81%   |
| 22      | 17        | 1.28%   |
| 18      | 16        | 1.21%   |
| 31      | 14        | 1.06%   |
| 65      | 11        | 0.83%   |
| 34      | 11        | 0.83%   |
| 40      | 10        | 0.76%   |
| 25      | 10        | 0.76%   |
| 20      | 10        | 0.76%   |
| 11      | 8         | 0.6%    |
| 10      | 7         | 0.53%   |
| 7       | 7         | 0.53%   |
| 26      | 6         | 0.45%   |
| 32      | 5         | 0.38%   |
| 63      | 4         | 0.3%    |
| 142     | 2         | 0.15%   |
| 84      | 2         | 0.15%   |
| 57      | 2         | 0.15%   |
| 54      | 2         | 0.15%   |
| 43      | 2         | 0.15%   |
| 36      | 2         | 0.15%   |
| 28      | 2         | 0.15%   |
| 3       | 2         | 0.15%   |
| 72      | 1         | 0.08%   |
| 67      | 1         | 0.08%   |
| 55      | 1         | 0.08%   |
| 46      | 1         | 0.08%   |
| 42      | 1         | 0.08%   |
| 39      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 537       | 41.09%  |
| 501-600        | 290       | 22.19%  |
| 201-300        | 160       | 12.24%  |
| 401-500        | 118       | 9.03%   |
| 351-400        | 55        | 4.21%   |
| Unknown        | 50        | 3.83%   |
| 601-700        | 27        | 2.07%   |
| 701-800        | 20        | 1.53%   |
| 1001-1500      | 19        | 1.45%   |
| 801-900        | 14        | 1.07%   |
| 1-100          | 8         | 0.61%   |
| 1501-2000      | 3         | 0.23%   |
| 901-1000       | 3         | 0.23%   |
| More than 2000 | 2         | 0.15%   |
| 101-200        | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 883       | 73.22%  |
| 16/10   | 187       | 15.51%  |
| Unknown | 47        | 3.9%    |
| 3/2     | 35        | 2.9%    |
| 5/4     | 16        | 1.33%   |
| 21/9    | 13        | 1.08%   |
| 4/3     | 11        | 0.91%   |
| 0.67    | 6         | 0.5%    |
| 6/5     | 2         | 0.17%   |
| 1.00    | 2         | 0.17%   |
| 0.56    | 2         | 0.17%   |
| 2.00    | 1         | 0.08%   |
| 0.45    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 276       | 20.94%  |
| 101-110        | 247       | 18.74%  |
| 201-250        | 223       | 16.92%  |
| 301-350        | 97        | 7.36%   |
| 71-80          | 90        | 6.83%   |
| 151-200        | 81        | 6.15%   |
| Unknown        | 50        | 3.79%   |
| 111-120        | 43        | 3.26%   |
| 61-70          | 32        | 2.43%   |
| 351-500        | 32        | 2.43%   |
| 251-300        | 32        | 2.43%   |
| 121-130        | 28        | 2.12%   |
| More than 1000 | 26        | 1.97%   |
| 501-1000       | 17        | 1.29%   |
| 141-150        | 15        | 1.14%   |
| 1-40           | 9         | 0.68%   |
| 51-60          | 7         | 0.53%   |
| 91-100         | 7         | 0.53%   |
| 41-50          | 6         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 399       | 30.76%  |
| 51-100        | 340       | 26.21%  |
| 101-120       | 220       | 16.96%  |
| 161-240       | 204       | 15.73%  |
| More than 240 | 64        | 4.93%   |
| Unknown       | 50        | 3.86%   |
| 1-50          | 20        | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1035      | 74.35%  |
| 2     | 176       | 12.64%  |
| 0     | 171       | 12.28%  |
| 3     | 10        | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 748       | 37.74%  |
| Realtek Semiconductor            | 741       | 37.39%  |
| Qualcomm Atheros                 | 150       | 7.57%   |
| Broadcom                         | 63        | 3.18%   |
| MediaTek                         | 58        | 2.93%   |
| Broadcom Limited                 | 26        | 1.31%   |
| ASIX Electronics                 | 26        | 1.31%   |
| Ralink Technology                | 25        | 1.26%   |
| Huawei Technologies              | 20        | 1.01%   |
| Xiaomi                           | 13        | 0.66%   |
| Qualcomm                         | 11        | 0.55%   |
| Marvell Technology Group         | 9         | 0.45%   |
| Microsoft                        | 8         | 0.4%    |
| IBM                              | 6         | 0.3%    |
| Ralink                           | 5         | 0.25%   |
| Quectel Wireless Solutions       | 5         | 0.25%   |
| Dell                             | 5         | 0.25%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.2%    |
| TP-Link                          | 4         | 0.2%    |
| Qualcomm Atheros Communications  | 4         | 0.2%    |
| OPPO Electronics                 | 4         | 0.2%    |
| Tenda                            | 3         | 0.15%   |
| Samsung Electronics              | 3         | 0.15%   |
| NetGear                          | 3         | 0.15%   |
| Loongson Technology              | 3         | 0.15%   |
| D-Link                           | 3         | 0.15%   |
| Aquantia                         | 3         | 0.15%   |
| Silicon Integrated Systems [SiS] | 2         | 0.1%    |
| Sierra Wireless                  | 2         | 0.1%    |
| Oculus VR                        | 2         | 0.1%    |
| Mellanox Technologies            | 2         | 0.1%    |
| DisplayLink                      | 2         | 0.1%    |
| Wilocity                         | 1         | 0.05%   |
| vivo                             | 1         | 0.05%   |
| ST-Ericsson                      | 1         | 0.05%   |
| Shenzhen Goodix Technology       | 1         | 0.05%   |
| Sagem                            | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.05%   |
| Nvidia                           | 1         | 0.05%   |
| NetXen Incorporated              | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 466       | 20.27%  |
| Intel Wi-Fi 6 AX200                                               | 91        | 3.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 58        | 2.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 52        | 2.26%   |
| Intel Wireless 8265 / 8275                                        | 52        | 2.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 47        | 2.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 41        | 1.78%   |
| Intel Wi-Fi 6 AX201                                               | 39        | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 33        | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 32        | 1.39%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 32        | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 31        | 1.35%   |
| Intel Wireless 7265                                               | 30        | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 29        | 1.26%   |
| Intel Wireless 7260                                               | 25        | 1.09%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 1.09%   |
| Intel I211 Gigabit Network Connection                             | 23        | 1%      |
| Intel Wireless 8260                                               | 22        | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 21        | 0.91%   |
| Intel Wireless 3165                                               | 21        | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 0.87%   |
| Intel Ethernet Controller I225-V                                  | 20        | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 19        | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 18        | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 18        | 0.78%   |
| Ralink MT7601U Wireless Adapter                                   | 17        | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 17        | 0.74%   |
| Intel I350 Gigabit Network Connection                             | 17        | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 16        | 0.7%    |
| Realtek 802.11ac NIC                                              | 16        | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 0.65%   |
| Intel I210 Gigabit Network Connection                             | 15        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 15        | 0.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 14        | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 574       | 52.47%  |
| Realtek Semiconductor           | 212       | 19.38%  |
| Qualcomm Atheros                | 118       | 10.79%  |
| MediaTek                        | 58        | 5.3%    |
| Broadcom                        | 37        | 3.38%   |
| Ralink Technology               | 25        | 2.29%   |
| Broadcom Limited                | 20        | 1.83%   |
| Qualcomm                        | 7         | 0.64%   |
| Ralink                          | 5         | 0.46%   |
| Quectel Wireless Solutions      | 5         | 0.46%   |
| TP-Link                         | 4         | 0.37%   |
| Qualcomm Atheros Communications | 4         | 0.37%   |
| Microsoft                       | 4         | 0.37%   |
| Xiaomi                          | 3         | 0.27%   |
| NetGear                         | 3         | 0.27%   |
| Marvell Technology Group        | 3         | 0.27%   |
| D-Link                          | 3         | 0.27%   |
| Sierra Wireless                 | 2         | 0.18%   |
| Dell                            | 2         | 0.18%   |
| Wilocity                        | 1         | 0.09%   |
| Sagem                           | 1         | 0.09%   |
| Hewlett-Packard                 | 1         | 0.09%   |
| Fibocom                         | 1         | 0.09%   |
| D-Link System                   | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 91        | 8.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 58        | 5.25%   |
| Intel Wireless 8265 / 8275                                     | 52        | 4.71%   |
| Intel Wi-Fi 6 AX201                                            | 39        | 3.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 33        | 2.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 32        | 2.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 32        | 2.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 31        | 2.81%   |
| Intel Wireless 7265                                            | 30        | 2.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 29        | 2.63%   |
| Intel Wireless 7260                                            | 25        | 2.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 2.26%   |
| Intel Wireless 8260                                            | 22        | 1.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 21        | 1.9%    |
| Intel Wireless 3165                                            | 21        | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20        | 1.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 19        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 18        | 1.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 18        | 1.63%   |
| Ralink MT7601U Wireless Adapter                                | 17        | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 17        | 1.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 16        | 1.45%   |
| Realtek 802.11ac NIC                                           | 16        | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 1.36%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 15        | 1.36%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 14        | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 13        | 1.18%   |
| Intel Wireless-AC 9260                                         | 13        | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 0.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 10        | 0.91%   |
| Intel Wireless 3160                                            | 10        | 0.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 9         | 0.82%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)      | 9         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 9         | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 0.82%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter             | 9         | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 8         | 0.72%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 8         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 616       | 54.42%  |
| Intel                            | 333       | 29.42%  |
| Qualcomm Atheros                 | 45        | 3.98%   |
| Broadcom                         | 28        | 2.47%   |
| ASIX Electronics                 | 26        | 2.3%    |
| Huawei Technologies              | 16        | 1.41%   |
| Xiaomi                           | 10        | 0.88%   |
| Marvell Technology Group         | 6         | 0.53%   |
| IBM                              | 6         | 0.53%   |
| Broadcom Limited                 | 6         | 0.53%   |
| OPPO Electronics                 | 4         | 0.35%   |
| Tenda                            | 3         | 0.27%   |
| Samsung Electronics              | 3         | 0.27%   |
| Qualcomm                         | 3         | 0.27%   |
| Microsoft                        | 3         | 0.27%   |
| Loongson Technology              | 3         | 0.27%   |
| Dell                             | 3         | 0.27%   |
| Aquantia                         | 3         | 0.27%   |
| Silicon Integrated Systems [SiS] | 2         | 0.18%   |
| Mellanox Technologies            | 2         | 0.18%   |
| DisplayLink                      | 2         | 0.18%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.09%   |
| Nvidia                           | 1         | 0.09%   |
| NetXen Incorporated              | 1         | 0.09%   |
| Microchip Technology             | 1         | 0.09%   |
| ICS Advent                       | 1         | 0.09%   |
| Google                           | 1         | 0.09%   |
| Attansic Technology              | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 466       | 39.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 52        | 4.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 47        | 4%      |
| Realtek RTL8125 2.5GbE Controller                                 | 41        | 3.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 2.55%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 2.13%   |
| Intel I211 Gigabit Network Connection                             | 23        | 1.96%   |
| Intel Ethernet Controller I225-V                                  | 20        | 1.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 1.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 1.53%   |
| Intel I350 Gigabit Network Connection                             | 17        | 1.45%   |
| Intel I210 Gigabit Network Connection                             | 15        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 1.28%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 1.11%   |
| Intel Ethernet Connection (10) I219-V                             | 11        | 0.94%   |
| Huawei WLZ-AN00                                                   | 11        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.68%   |
| Intel Ethernet Connection (12) I219-V                             | 8         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.68%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 8         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.6%    |
| Intel Ethernet Connection (16) I219-V                             | 7         | 0.6%    |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 6         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.51%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.51%   |
| Intel Ethernet Connection (3) I219-LM                             | 6         | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                              | 6         | 0.51%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 6         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.43%   |
| Intel Ethernet Connection X722 for 1GbE                           | 5         | 0.43%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.43%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.43%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1066      | 49.98%  |
| WiFi     | 1048      | 49.13%  |
| Unknown  | 11        | 0.52%   |
| Modem    | 8         | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 778       | 58.1%   |
| Ethernet | 560       | 41.82%  |
| Unknown  | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 661       | 48.32%  |
| 1     | 559       | 40.86%  |
| 0     | 70        | 5.12%   |
| 3     | 45        | 3.29%   |
| 4     | 20        | 1.46%   |
| 6     | 7         | 0.51%   |
| 8     | 2         | 0.15%   |
| 5     | 2         | 0.15%   |
| 42    | 1         | 0.07%   |
| 7     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1163      | 83.79%  |
| Yes  | 225       | 16.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 508       | 57.08%  |
| Realtek Semiconductor           | 80        | 8.99%   |
| Qualcomm Atheros Communications | 60        | 6.74%   |
| Cambridge Silicon Radio         | 48        | 5.39%   |
| Foxconn / Hon Hai               | 36        | 4.04%   |
| Realtek                         | 27        | 3.03%   |
| Broadcom                        | 27        | 3.03%   |
| IMC Networks                    | 25        | 2.81%   |
| MediaTek                        | 15        | 1.69%   |
| Apple                           | 13        | 1.46%   |
| Lite-On Technology              | 12        | 1.35%   |
| ASUSTek Computer                | 9         | 1.01%   |
| Opticis                         | 5         | 0.56%   |
| Dell                            | 5         | 0.56%   |
| Foxconn International           | 4         | 0.45%   |
| Ralink                          | 3         | 0.34%   |
| Marvell Semiconductor           | 3         | 0.34%   |
| Hewlett-Packard                 | 3         | 0.34%   |
| Toshiba                         | 2         | 0.22%   |
| Taiyo Yuden                     | 2         | 0.22%   |
| Alps Electric                   | 2         | 0.22%   |
| USI                             | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 162       | 18.2%   |
| Intel AX201 Bluetooth                                 | 106       | 11.91%  |
| Intel AX200 Bluetooth                                 | 86        | 9.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 71        | 7.98%   |
| Realtek Bluetooth Radio                               | 58        | 6.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 48        | 5.39%   |
| Qualcomm Atheros  Bluetooth Device                    | 40        | 4.49%   |
| Intel AX210 Bluetooth                                 | 29        | 3.26%   |
| Intel Bluetooth Device                                | 26        | 2.92%   |
| Realtek 802.11ac WLAN Adapter                         | 25        | 2.81%   |
| MediaTek Wireless_Device                              | 15        | 1.69%   |
| IMC Networks Bluetooth Radio                          | 14        | 1.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 12        | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 12        | 1.35%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 12        | 1.35%   |
| Realtek  Bluetooth 4.2 Adapter                        | 9         | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                    | 9         | 1.01%   |
| Foxconn / Hon Hai Wireless_Device                     | 8         | 0.9%    |
| Apple Bluetooth Host Controller                       | 8         | 0.9%    |
| Realtek RTL8723B Bluetooth                            | 7         | 0.79%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 7         | 0.79%   |
| IMC Networks Wireless_Device                          | 7         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 0.67%   |
| Lite-On Bluetooth Device                              | 6         | 0.67%   |
| Broadcom BCM2045B (BDC-2.1)                           | 6         | 0.67%   |
| Opticis Bluetooth Radio                               | 5         | 0.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 5         | 0.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 5         | 0.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 4         | 0.45%   |
| Intel Wireless-AC 3168 Bluetooth                      | 4         | 0.45%   |
| IMC Networks Bluetooth Device                         | 4         | 0.45%   |
| Foxconn International BCM43142A0 Bluetooth module     | 4         | 0.45%   |
| ASUS Bluetooth Radio                                  | 4         | 0.45%   |
| Apple Bluetooth USB Host Controller                   | 4         | 0.45%   |
| Ralink RT3290 Bluetooth                               | 3         | 0.34%   |
| Marvell Bluetooth and Wireless LAN Composite          | 3         | 0.34%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 3         | 0.34%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 3         | 0.34%   |
| Taiyo Yuden Bluetooth Device                          | 2         | 0.22%   |
| Realtek Bluetooth Radio                               | 2         | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 893       | 52.68%  |
| AMD                                          | 396       | 23.36%  |
| Nvidia                                       | 296       | 17.46%  |
| C-Media Electronics                          | 12        | 0.71%   |
| Zhaoxin                                      | 9         | 0.53%   |
| Zoran Co. Personal Media Division (Nogatech) | 7         | 0.41%   |
| Realtek Semiconductor                        | 6         | 0.35%   |
| Creative Labs                                | 6         | 0.35%   |
| Apple                                        | 6         | 0.35%   |
| Generalplus Technology                       | 5         | 0.29%   |
| XMOS                                         | 4         | 0.24%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.18%   |
| Phytium Technology                           | 3         | 0.18%   |
| Loongson Technology                          | 3         | 0.18%   |
| Huawei Technologies                          | 3         | 0.18%   |
| Texas Instruments                            | 2         | 0.12%   |
| JMTek                                        | 2         | 0.12%   |
| Jieli Technology                             | 2         | 0.12%   |
| Giga-Byte Technology                         | 2         | 0.12%   |
| Dell                                         | 2         | 0.12%   |
| BY EDIFIER                                   | 2         | 0.12%   |
| Yamaha                                       | 1         | 0.06%   |
| VIA Technologies                             | 1         | 0.06%   |
| USB-Speaker                                  | 1         | 0.06%   |
| ULi Electronics                              | 1         | 0.06%   |
| TerraTec Electronic                          | 1         | 0.06%   |
| SteelSeries ApS                              | 1         | 0.06%   |
| Specialix                                    | 1         | 0.06%   |
| Sony                                         | 1         | 0.06%   |
| Sennheiser Communications                    | 1         | 0.06%   |
| Samsung Electronics                          | 1         | 0.06%   |
| Polycom                                      | 1         | 0.06%   |
| NXP Semiconductors                           | 1         | 0.06%   |
| Moore Threads Technology                     | 1         | 0.06%   |
| Micro Star International                     | 1         | 0.06%   |
| Medeli Electronics                           | 1         | 0.06%   |
| KTMicro                                      | 1         | 0.06%   |
| Kingston Technology                          | 1         | 0.06%   |
| FUXIN                                        | 1         | 0.06%   |
| Fry's Electronics                            | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 212       | 10.34%  |
| Intel Sunrise Point-LP HD Audio                                                   | 112       | 5.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 95        | 4.63%   |
| Intel Cannon Lake PCH cAVS                                                        | 65        | 3.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 62        | 3.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 61        | 2.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 55        | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 51        | 2.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 50        | 2.44%   |
| Intel 200 Series PCH HD Audio                                                     | 49        | 2.39%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 43        | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 41        | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 40        | 1.95%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 36        | 1.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 35        | 1.71%   |
| Intel Haswell-ULT HD Audio Controller                                             | 31        | 1.51%   |
| Intel 8 Series HD Audio Controller                                                | 31        | 1.51%   |
| AMD Starship/Matisse HD Audio Controller                                          | 31        | 1.51%   |
| Nvidia GA106 High Definition Audio Controller                                     | 29        | 1.41%   |
| AMD FCH Azalia Controller                                                         | 29        | 1.41%   |
| Nvidia GP106 High Definition Audio Controller                                     | 28        | 1.37%   |
| Nvidia TU106 High Definition Audio Controller                                     | 25        | 1.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 25        | 1.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 25        | 1.22%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 24        | 1.17%   |
| Intel Broadwell-U Audio Controller                                                | 24        | 1.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 23        | 1.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 23        | 1.12%   |
| Intel Comet Lake PCH cAVS                                                         | 22        | 1.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 21        | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 21        | 1.02%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 21        | 1.02%   |
| Nvidia GP104 High Definition Audio Controller                                     | 19        | 0.93%   |
| Nvidia Audio device                                                               | 19        | 0.93%   |
| Intel Comet Lake PCH-V cAVS                                                       | 17        | 0.83%   |
| Intel CM238 HD Audio Controller                                                   | 17        | 0.83%   |
| Nvidia TU116 High Definition Audio Controller                                     | 16        | 0.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 16        | 0.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 16        | 0.78%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 15        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 271       | 28.47%  |
| SK hynix            | 165       | 17.33%  |
| Kingston            | 141       | 14.81%  |
| Micron Technology   | 113       | 11.87%  |
| Unknown             | 55        | 5.78%   |
| Crucial             | 36        | 3.78%   |
| A-DATA Technology   | 27        | 2.84%   |
| Ramaxel Technology  | 23        | 2.42%   |
| Corsair             | 13        | 1.37%   |
| Unknown             | 13        | 1.37%   |
| Elpida              | 7         | 0.74%   |
| Unknown (ABCD)      | 6         | 0.63%   |
| Transcend           | 6         | 0.63%   |
| Team                | 6         | 0.63%   |
| Nanya Technology    | 5         | 0.53%   |
| G.Skill             | 5         | 0.53%   |
| Kingmax             | 4         | 0.42%   |
| KINGBANK            | 4         | 0.42%   |
| UniIC               | 3         | 0.32%   |
| Shenzhen WODPOSIT   | 3         | 0.32%   |
| Ramsta              | 3         | 0.32%   |
| Lenovo              | 3         | 0.32%   |
| Juhor               | 3         | 0.32%   |
| Apacer              | 3         | 0.32%   |
| Unknown (08C8)      | 2         | 0.21%   |
| Unknown (08B5)      | 2         | 0.21%   |
| KLEVV               | 2         | 0.21%   |
| GLOWAY              | 2         | 0.21%   |
| Unknown (8AF1)      | 1         | 0.11%   |
| Unknown (0x0B92)    | 1         | 0.11%   |
| UNILC               | 1         | 0.11%   |
| tigo                | 1         | 0.11%   |
| Thermaltake         | 1         | 0.11%   |
| SK_Hynix            | 1         | 0.11%   |
| Shenzhen Mic        | 1         | 0.11%   |
| Shenzhen Longsys    | 1         | 0.11%   |
| SHARETRONIC         | 1         | 0.11%   |
| Sesame              | 1         | 0.11%   |
| PCCOOLER            | 1         | 0.11%   |
| MTASE               | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 18        | 1.74%   |
| Unknown                                                          | 13        | 1.26%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.97%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 9         | 0.87%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 0.87%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 9         | 0.87%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 6         | 0.58%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.58%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.58%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 6         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.58%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 6         | 0.58%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                       | 5         | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.48%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 5         | 0.48%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 5         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 5         | 0.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.48%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 5         | 0.48%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 5         | 0.48%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.48%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.48%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 5         | 0.48%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 5         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.39%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.39%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.39%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.39%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 4         | 0.39%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 4         | 0.39%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s             | 4         | 0.39%   |
| Samsung RAM 6478545886 16GB DIMM DDR4 2668MT/s                   | 4         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 472       | 55.33%  |
| DDR3    | 198       | 23.21%  |
| LPDDR4  | 47        | 5.51%   |
| LPDDR3  | 38        | 4.45%   |
| DDR5    | 34        | 3.99%   |
| LPDDR5  | 22        | 2.58%   |
| Unknown | 17        | 1.99%   |
| SDRAM   | 12        | 1.41%   |
| DDR2    | 12        | 1.41%   |
| DDR     | 1         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 445       | 51.86%  |
| DIMM         | 252       | 29.37%  |
| Row Of Chips | 151       | 17.6%   |
| Chip         | 6         | 0.7%    |
| Unknown      | 3         | 0.35%   |
| RIMM         | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 403       | 44.29%  |
| 4096  | 198       | 21.76%  |
| 16384 | 188       | 20.66%  |
| 2048  | 55        | 6.04%   |
| 32768 | 48        | 5.27%   |
| 1024  | 11        | 1.21%   |
| 65536 | 5         | 0.55%   |
| 512   | 2         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 178       | 19.52%  |
| 2667    | 157       | 17.21%  |
| 1600    | 138       | 15.13%  |
| 2400    | 64        | 7.02%   |
| 2133    | 60        | 6.58%   |
| 4800    | 32        | 3.51%   |
| 1333    | 32        | 3.51%   |
| 2666    | 27        | 2.96%   |
| 4267    | 24        | 2.63%   |
| 6400    | 22        | 2.41%   |
| 1867    | 22        | 2.41%   |
| 3600    | 19        | 2.08%   |
| 1066    | 10        | 1.1%    |
| 800     | 10        | 1.1%    |
| 1334    | 9         | 0.99%   |
| 4266    | 8         | 0.88%   |
| Unknown | 8         | 0.88%   |
| 3733    | 7         | 0.77%   |
| 3266    | 7         | 0.77%   |
| 2933    | 6         | 0.66%   |
| 2668    | 6         | 0.66%   |
| 1866    | 6         | 0.66%   |
| 1067    | 6         | 0.66%   |
| 667     | 6         | 0.66%   |
| 3466    | 5         | 0.55%   |
| 3000    | 5         | 0.55%   |
| 1800    | 4         | 0.44%   |
| 8400    | 3         | 0.33%   |
| 5600    | 3         | 0.33%   |
| 4199    | 3         | 0.33%   |
| 2048    | 3         | 0.33%   |
| 3400    | 2         | 0.22%   |
| 2800    | 2         | 0.22%   |
| 266     | 2         | 0.22%   |
| 65535   | 1         | 0.11%   |
| 7500    | 1         | 0.11%   |
| 5200    | 1         | 0.11%   |
| 4133    | 1         | 0.11%   |
| 4000    | 1         | 0.11%   |
| 3933    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Hewlett-Packard                    | 5         | 50%     |
| Canon                              | 2         | 20%     |
| Seiko Epson                        | 1         | 10%     |
| Brother Industries                 | 1         | 10%     |
| BeiJing LanXum Computer Technology | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                        | 2         | 20%     |
| Seiko Epson M105 Series                                 | 1         | 10%     |
| HP Officejet 4500 G510g-m                               | 1         | 10%     |
| HP LaserJet P1102                                       | 1         | 10%     |
| HP DeskJet 2130 series                                  | 1         | 10%     |
| Canon PIXMA MP280                                       | 1         | 10%     |
| Canon iP1100 series                                     | 1         | 10%     |
| Brother HL-5440D series                                 | 1         | 10%     |
| BeiJing LanXum Technology Black and White Laser Printer | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 142       | 19.59%  |
| IMC Networks                           | 116       | 16%     |
| Realtek Semiconductor                  | 51        | 7.03%   |
| Microdia                               | 50        | 6.9%    |
| Sunplus Innovation Technology          | 43        | 5.93%   |
| Quanta                                 | 41        | 5.66%   |
| Bison Electronics                      | 37        | 5.1%    |
| Acer                                   | 35        | 4.83%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 4.28%   |
| Syntek                                 | 24        | 3.31%   |
| Luxvisions Innotech Limited            | 21        | 2.9%    |
| Lite-On Technology                     | 18        | 2.48%   |
| Suyin                                  | 16        | 2.21%   |
| Apple                                  | 12        | 1.66%   |
| Alcor Micro                            | 11        | 1.52%   |
| Logitech                               | 9         | 1.24%   |
| Silicon Motion                         | 7         | 0.97%   |
| Z-Star Microelectronics                | 6         | 0.83%   |
| Lenovo                                 | 5         | 0.69%   |
| SunplusIT                              | 4         | 0.55%   |
| Ricoh                                  | 4         | 0.55%   |
| icSpring                               | 4         | 0.55%   |
| SN0002                                 | 3         | 0.41%   |
| Importek                               | 3         | 0.41%   |
| GEMBIRD                                | 3         | 0.41%   |
| Unknown (0000066029)                   | 2         | 0.28%   |
| Sonix Technology                       | 2         | 0.28%   |
| Nebraska Furniture Mart                | 2         | 0.28%   |
| Google                                 | 2         | 0.28%   |
| Genesys Logic                          | 2         | 0.28%   |
| Y Media                                | 1         | 0.14%   |
| Unknown                                | 1         | 0.14%   |
| Tripath Technology                     | 1         | 0.14%   |
| ShineOptics                            | 1         | 0.14%   |
| Primax Electronics                     | 1         | 0.14%   |
| Mitsumi                                | 1         | 0.14%   |
| Microsoft                              | 1         | 0.14%   |
| MacroSilicon                           | 1         | 0.14%   |
| kingcome                               | 1         | 0.14%   |
| JSXRGB0230-D046                        | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 66        | 9.02%   |
| IMC Networks Integrated Camera                               | 43        | 5.87%   |
| Microdia Integrated_Webcam_HD                                | 29        | 3.96%   |
| IMC Networks HD Camera                                       | 22        | 3.01%   |
| Syntek Integrated Camera                                     | 17        | 2.32%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 16        | 2.19%   |
| Acer Integrated Camera                                       | 15        | 2.05%   |
| Bison Integrated Camera                                      | 14        | 1.91%   |
| Realtek Integrated_Webcam_HD                                 | 13        | 1.78%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 13        | 1.78%   |
| Sunplus XiaoMi USB 2.0 Webcam                                | 11        | 1.5%    |
| Sunplus Integrated_Webcam_HD                                 | 11        | 1.5%    |
| IMC Networks ov9734_azurewave_camera                         | 11        | 1.5%    |
| Chicony HD Webcam                                            | 11        | 1.5%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                              | 9         | 1.23%   |
| Quanta HP HD Camera                                          | 8         | 1.09%   |
| Quanta hm1091_techfront                                      | 8         | 1.09%   |
| Luxvisions Innotech Limited Integrated Camera                | 8         | 1.09%   |
| Bison SunplusIT Integrated Camera                            | 8         | 1.09%   |
| Realtek Integrated Webcam                                    | 7         | 0.96%   |
| Lite-On Integrated Camera                                    | 7         | 0.96%   |
| Chicony XiaoMi USB 2.0 Webcam                                | 7         | 0.96%   |
| Sunplus HD WebCam                                            | 6         | 0.82%   |
| Realtek USB Camera                                           | 6         | 0.82%   |
| Quanta HD User Facing                                        | 6         | 0.82%   |
| Silicon Motion 300k Pixel Camera                             | 5         | 0.68%   |
| Realtek HP Wide Vision HD Camera                             | 5         | 0.68%   |
| Quanta HP Wide Vision HD Camera                              | 5         | 0.68%   |
| Microdia Webcam Vitade AF                                    | 5         | 0.68%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 5         | 0.68%   |
| IMC Networks XHC Camera                                      | 5         | 0.68%   |
| IMC Networks Lenovo EasyCamera                               | 5         | 0.68%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 5         | 0.68%   |
| Chicony Integrated Camera (1280x720@30)                      | 5         | 0.68%   |
| Alcor Micro USB 2.0 Camera                                   | 5         | 0.68%   |
| Syntek Lenovo EasyCamera                                     | 4         | 0.55%   |
| Quanta ov9734_techfront_camera                               | 4         | 0.55%   |
| Lite-On HP Wide Vision HD Camera                             | 4         | 0.55%   |
| Lite-On HP HD Camera                                         | 4         | 0.55%   |
| icSpring camera                                              | 4         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 66        | 32.35%  |
| Synaptics                  | 58        | 28.43%  |
| Validity Sensors           | 45        | 22.06%  |
| Elan Microelectronics      | 13        | 6.37%   |
| Upek                       | 10        | 4.9%    |
| AuthenTec                  | 4         | 1.96%   |
| LighTuning Technology      | 3         | 1.47%   |
| Focal-systems.Corp         | 3         | 1.47%   |
| STMicroelectronics         | 2         | 0.98%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 38        | 18.63%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 12.75%  |
| Shenzhen Goodix Fingerprint Reader                                         | 26        | 12.75%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 5.39%   |
| Elan ELAN:Fingerprint                                                      | 11        | 5.39%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 4.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 3.92%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.94%   |
| Synaptics WBDI Device                                                      | 4         | 1.96%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.96%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 1.96%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.47%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 1.47%   |
| Validity Sensors VFS491                                                    | 3         | 1.47%   |
| Synaptics WBDI                                                             | 3         | 1.47%   |
| Synaptics UWP WBDI Device                                                  | 3         | 1.47%   |
| Synaptics UWP WBDI                                                         | 3         | 1.47%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.47%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 1.47%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.98%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.98%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.98%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.98%   |
| AuthenTec AES2810                                                          | 2         | 0.98%   |
| Unknown                                                                    | 2         | 0.98%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.49%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.49%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.49%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.49%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.49%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.49%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.49%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.49%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 13        | 65%     |
| Upek        | 2         | 10%     |
| Clay Logic  | 2         | 10%     |
| Alcor Micro | 2         | 10%     |
| Yubico.com  | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 5         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 15%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 15%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 10%     |
| Clay Logic CanoKey Pigeon                                                    | 2         | 10%     |
| Broadcom 58200                                                               | 2         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 10%     |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 833       | 59.5%   |
| 1     | 416       | 29.71%  |
| 2     | 99        | 7.07%   |
| 4     | 21        | 1.5%    |
| 3     | 20        | 1.43%   |
| 5     | 5         | 0.36%   |
| 8     | 2         | 0.14%   |
| 6     | 2         | 0.14%   |
| 10    | 1         | 0.07%   |
| 7     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 201       | 26.41%  |
| Graphics card            | 192       | 25.23%  |
| Net/wireless             | 82        | 10.78%  |
| Communication controller | 64        | 8.41%   |
| Multimedia controller    | 42        | 5.52%   |
| Unassigned class         | 40        | 5.26%   |
| Sound                    | 40        | 5.26%   |
| Bluetooth                | 26        | 3.42%   |
| Camera                   | 22        | 2.89%   |
| Chipcard                 | 17        | 2.23%   |
| Net/ethernet             | 10        | 1.31%   |
| Network                  | 7         | 0.92%   |
| Storage/raid             | 5         | 0.66%   |
| Card reader              | 5         | 0.66%   |
| Storage                  | 3         | 0.39%   |
| Storage/ata              | 2         | 0.26%   |
| Storage/nvme             | 1         | 0.13%   |
| Modem                    | 1         | 0.13%   |
| Dvb card                 | 1         | 0.13%   |

