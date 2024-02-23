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

Total: 2378

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MECHREVO      | S1 Pro Series               | Notebook    | [ba68410f96](https://linux-hardware.org/?probe=ba68410f96) | Feb 02, 2024 |
| Lenovo        | NO DPK                      | Desktop     | [ce1ff05aed](https://linux-hardware.org/?probe=ce1ff05aed) | Feb 02, 2024 |
| MSI           | MAG B550M MORTAR            | Desktop     | [7ad6a0ecce](https://linux-hardware.org/?probe=7ad6a0ecce) | Jan 31, 2024 |
| Lenovo        | NO DPK                      | Desktop     | [fd4b4dd902](https://linux-hardware.org/?probe=fd4b4dd902) | Jan 31, 2024 |
| MECHREVO      | WUJIE14 PRO                 | Notebook    | [5e58868dbf](https://linux-hardware.org/?probe=5e58868dbf) | Jan 30, 2024 |
| Huanan        | X99-4MF V1.0                | Desktop     | [63f228ae04](https://linux-hardware.org/?probe=63f228ae04) | Jan 29, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [385d8d4782](https://linux-hardware.org/?probe=385d8d4782) | Jan 29, 2024 |
| Lenovo        | G40-45 80E1                 | Notebook    | [1e01df8e73](https://linux-hardware.org/?probe=1e01df8e73) | Jan 27, 2024 |
| ASUSTek       | B85M-K                      | Desktop     | [78e893cbdb](https://linux-hardware.org/?probe=78e893cbdb) | Jan 26, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TDA... | Notebook    | [6456dc0020](https://linux-hardware.org/?probe=6456dc0020) | Jan 26, 2024 |
| ASUSTek       | B85M-K                      | Desktop     | [42c598a7c2](https://linux-hardware.org/?probe=42c598a7c2) | Jan 23, 2024 |
| Dell          | Inspiron 5557               | Notebook    | [e331563298](https://linux-hardware.org/?probe=e331563298) | Jan 22, 2024 |
| Colorful T... | CVN B550M GAMING FROZEN ... | Desktop     | [1d6e70910a](https://linux-hardware.org/?probe=1d6e70910a) | Jan 21, 2024 |
| HP            | ProBook 455R G6             | Notebook    | [59026d385f](https://linux-hardware.org/?probe=59026d385f) | Jan 21, 2024 |
| Dell          | 0WCJNT A06                  | Server      | [f98fce82ef](https://linux-hardware.org/?probe=f98fce82ef) | Jan 21, 2024 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [5c7cfc2209](https://linux-hardware.org/?probe=5c7cfc2209) | Jan 20, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [5b51e88413](https://linux-hardware.org/?probe=5b51e88413) | Jan 20, 2024 |
| Great Wall    | MBX-Z60AR110 TBD            | Desktop     | [fdfa81d344](https://linux-hardware.org/?probe=fdfa81d344) | Jan 18, 2024 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [53e10082bf](https://linux-hardware.org/?probe=53e10082bf) | Jan 17, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [fe24385194](https://linux-hardware.org/?probe=fe24385194) | Jan 16, 2024 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [bfbba978c3](https://linux-hardware.org/?probe=bfbba978c3) | Jan 16, 2024 |
| Dell          | Inspiron 5557               | Notebook    | [938a3ee950](https://linux-hardware.org/?probe=938a3ee950) | Jan 16, 2024 |
| Dell          | Vostro 5470                 | Notebook    | [21f78f0847](https://linux-hardware.org/?probe=21f78f0847) | Jan 16, 2024 |
| HP            | ProBook 450 15.6 inch G1... | Notebook    | [54ed51acbb](https://linux-hardware.org/?probe=54ed51acbb) | Jan 15, 2024 |
| Acer          | Swift SFX14-41G             | Notebook    | [947678b939](https://linux-hardware.org/?probe=947678b939) | Jan 15, 2024 |
| MSI           | Z370-OC PRO                 | Desktop     | [4ffb04a6df](https://linux-hardware.org/?probe=4ffb04a6df) | Jan 15, 2024 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a77f0d6a70](https://linux-hardware.org/?probe=a77f0d6a70) | Jan 15, 2024 |
| Timi          | TM1612                      | Notebook    | [89ef61c3ee](https://linux-hardware.org/?probe=89ef61c3ee) | Jan 14, 2024 |
| Unknown       | Unknown                     | Soc         | [951b07d2a5](https://linux-hardware.org/?probe=951b07d2a5) | Jan 13, 2024 |
| SPESTECH      | IB.IELK.CW01                | Desktop     | [3a97c43bcc](https://linux-hardware.org/?probe=3a97c43bcc) | Jan 11, 2024 |
| YanRay Tec... | B1904                       | Desktop     | [a9c8ebfbbd](https://linux-hardware.org/?probe=a9c8ebfbbd) | Jan 09, 2024 |
| Phytium       | FT2000/4                    | Server      | [a7c0849de0](https://linux-hardware.org/?probe=a7c0849de0) | Jan 08, 2024 |
| MECHREVO      | S1 Pro Series               | Notebook    | [419dfc25b2](https://linux-hardware.org/?probe=419dfc25b2) | Jan 08, 2024 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [1188890272](https://linux-hardware.org/?probe=1188890272) | Jan 07, 2024 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [cb8f846b0f](https://linux-hardware.org/?probe=cb8f846b0f) | Jan 07, 2024 |
| Dell          | Inspiron 5493               | Notebook    | [eb9b8edc2c](https://linux-hardware.org/?probe=eb9b8edc2c) | Jan 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [98da18a6c0](https://linux-hardware.org/?probe=98da18a6c0) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [2602d65d52](https://linux-hardware.org/?probe=2602d65d52) | Jan 06, 2024 |
| MECHREVO      | S1 Pro Series               | Notebook    | [da21c08192](https://linux-hardware.org/?probe=da21c08192) | Jan 06, 2024 |
| AZW           | SER                         | Mini pc     | [f4be01e0c9](https://linux-hardware.org/?probe=f4be01e0c9) | Jan 05, 2024 |
| Intel         | X99                         | Desktop     | [ed34568c2b](https://linux-hardware.org/?probe=ed34568c2b) | Jan 05, 2024 |
| ASUSTek       | B760M-AYW WIFI              | Desktop     | [6a471fb5e8](https://linux-hardware.org/?probe=6a471fb5e8) | Jan 05, 2024 |
| KUU           | Andes II                    | Notebook    | [512394ef85](https://linux-hardware.org/?probe=512394ef85) | Jan 04, 2024 |
| Timi          | TM1709                      | Notebook    | [79d0628d57](https://linux-hardware.org/?probe=79d0628d57) | Jan 03, 2024 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | Desktop     | [b8716bfb8f](https://linux-hardware.org/?probe=b8716bfb8f) | Jan 03, 2024 |
| Timi          | TM1709                      | Notebook    | [b934e033e4](https://linux-hardware.org/?probe=b934e033e4) | Jan 03, 2024 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [d53af9a54d](https://linux-hardware.org/?probe=d53af9a54d) | Jan 03, 2024 |
| ASUSTek       | H610A-IM-A                  | Desktop     | [a3d7b469e5](https://linux-hardware.org/?probe=a3d7b469e5) | Jan 03, 2024 |
| MECHREVO      | S2 Air Series PF4NU1F       | Notebook    | [08703baf6e](https://linux-hardware.org/?probe=08703baf6e) | Jan 03, 2024 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | Desktop     | [a7f5e10167](https://linux-hardware.org/?probe=a7f5e10167) | Jan 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [b3ada6c407](https://linux-hardware.org/?probe=b3ada6c407) | Jan 02, 2024 |
| Lenovo        | Legion Y7000P2020H 82AX     | Notebook    | [59d5eb147b](https://linux-hardware.org/?probe=59d5eb147b) | Jan 01, 2024 |
| Centerm       | C92                         | Desktop     | [5ede09f987](https://linux-hardware.org/?probe=5ede09f987) | Jan 01, 2024 |
| Centerm       | C92                         | Desktop     | [0201370bf4](https://linux-hardware.org/?probe=0201370bf4) | Jan 01, 2024 |
| Win Elemen... | M9                          | Desktop     | [33b3133a1c](https://linux-hardware.org/?probe=33b3133a1c) | Jan 01, 2024 |
| Win Elemen... | M9                          | Desktop     | [93f17e23c2](https://linux-hardware.org/?probe=93f17e23c2) | Jan 01, 2024 |
| Timi          | A34R                        | Notebook    | [d72018ec19](https://linux-hardware.org/?probe=d72018ec19) | Dec 29, 2023 |
| Google        | Dratini                     | Notebook    | [a81971bf37](https://linux-hardware.org/?probe=a81971bf37) | Dec 28, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [25e05316e9](https://linux-hardware.org/?probe=25e05316e9) | Dec 28, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [151f072ac9](https://linux-hardware.org/?probe=151f072ac9) | Dec 27, 2023 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [136b8b5f83](https://linux-hardware.org/?probe=136b8b5f83) | Dec 27, 2023 |
| GITSTAR       | GDC-1461                    | Notebook    | [398e4f42e4](https://linux-hardware.org/?probe=398e4f42e4) | Dec 26, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [76b6b08744](https://linux-hardware.org/?probe=76b6b08744) | Dec 26, 2023 |
| Gigabyte      | Z790 D DDR4                 | Desktop     | [68f5cfe720](https://linux-hardware.org/?probe=68f5cfe720) | Dec 25, 2023 |
| MECHREVO      | S2 Air Series PF4NU1F       | Notebook    | [edb1d110e2](https://linux-hardware.org/?probe=edb1d110e2) | Dec 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f47caaa0e1](https://linux-hardware.org/?probe=f47caaa0e1) | Dec 25, 2023 |
| Lenovo        | ThinkPad W530 2436CT0       | Notebook    | [7f8be52856](https://linux-hardware.org/?probe=7f8be52856) | Dec 24, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [2394204218](https://linux-hardware.org/?probe=2394204218) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [74c274a303](https://linux-hardware.org/?probe=74c274a303) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [123aa39382](https://linux-hardware.org/?probe=123aa39382) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9549fcd83e](https://linux-hardware.org/?probe=9549fcd83e) | Dec 23, 2023 |
| GITSTAR       | GDC-1461                    | Notebook    | [5412cf0f39](https://linux-hardware.org/?probe=5412cf0f39) | Dec 23, 2023 |
| Timi          | TM1612                      | Notebook    | [cf4f859193](https://linux-hardware.org/?probe=cf4f859193) | Dec 23, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [f6f10099c2](https://linux-hardware.org/?probe=f6f10099c2) | Dec 22, 2023 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [e6f38cb85e](https://linux-hardware.org/?probe=e6f38cb85e) | Dec 22, 2023 |
| Dell          | 0D4MD1 A00                  | Desktop     | [858b84769f](https://linux-hardware.org/?probe=858b84769f) | Dec 22, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [2af66f541d](https://linux-hardware.org/?probe=2af66f541d) | Dec 22, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [271869a253](https://linux-hardware.org/?probe=271869a253) | Dec 21, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [4e4e1e2329](https://linux-hardware.org/?probe=4e4e1e2329) | Dec 21, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [d111002a9c](https://linux-hardware.org/?probe=d111002a9c) | Dec 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [32f0587c3f](https://linux-hardware.org/?probe=32f0587c3f) | Dec 20, 2023 |
| HUAWEI        | W515 PGUV-WBY0              | Soc         | [b3d022d177](https://linux-hardware.org/?probe=b3d022d177) | Dec 19, 2023 |
| Timi          | TM1612                      | Notebook    | [38a41877ef](https://linux-hardware.org/?probe=38a41877ef) | Dec 19, 2023 |
| Win elemen... | M600                        | Desktop     | [0d0f7a6719](https://linux-hardware.org/?probe=0d0f7a6719) | Dec 19, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [5de00ab671](https://linux-hardware.org/?probe=5de00ab671) | Dec 18, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [b6e59d6e3e](https://linux-hardware.org/?probe=b6e59d6e3e) | Dec 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [3764b249f4](https://linux-hardware.org/?probe=3764b249f4) | Dec 18, 2023 |
| Sony          | SVD1321L2EW                 | Notebook    | [b753425d70](https://linux-hardware.org/?probe=b753425d70) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [c88b531754](https://linux-hardware.org/?probe=c88b531754) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [e3d9d4d8a7](https://linux-hardware.org/?probe=e3d9d4d8a7) | Dec 17, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [f04605f94c](https://linux-hardware.org/?probe=f04605f94c) | Dec 17, 2023 |
| Lenovo        | XiaoXinDuoduet IAU7 82TQ    | Tablet      | [93610bc88d](https://linux-hardware.org/?probe=93610bc88d) | Dec 15, 2023 |
| Lenovo        | XiaoXinDuoduet IAU7 82TQ    | Tablet      | [f662912ecd](https://linux-hardware.org/?probe=f662912ecd) | Dec 15, 2023 |
| Dell          | 09PR9H A03                  | Desktop     | [25d5c9ce02](https://linux-hardware.org/?probe=25d5c9ce02) | Dec 13, 2023 |
| Dell          | 0101XX A00                  | Desktop     | [87b101a810](https://linux-hardware.org/?probe=87b101a810) | Dec 13, 2023 |
| Unknown       | Unknown                     | Soc         | [9c60527586](https://linux-hardware.org/?probe=9c60527586) | Dec 13, 2023 |
| Unknown       | Unknown                     | Soc         | [50c635dba3](https://linux-hardware.org/?probe=50c635dba3) | Dec 13, 2023 |
| Lenovo        | Tilapia CRB                 | Desktop     | [1527115ecf](https://linux-hardware.org/?probe=1527115ecf) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [4fd70c36f8](https://linux-hardware.org/?probe=4fd70c36f8) | Dec 12, 2023 |
| MSI           | H610M BOMBER DDR4           | Desktop     | [7ea9e34c4c](https://linux-hardware.org/?probe=7ea9e34c4c) | Dec 11, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [74c10ca70c](https://linux-hardware.org/?probe=74c10ca70c) | Dec 11, 2023 |
| HUAWEI        | RLEFG-XX                    | Notebook    | [d47423dd6f](https://linux-hardware.org/?probe=d47423dd6f) | Dec 11, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [40cbcb37ea](https://linux-hardware.org/?probe=40cbcb37ea) | Dec 11, 2023 |
| MECHREVO      | Kuangshi16Pro Series GM6... | Notebook    | [e551d0d31e](https://linux-hardware.org/?probe=e551d0d31e) | Dec 11, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [a869089d9a](https://linux-hardware.org/?probe=a869089d9a) | Dec 09, 2023 |
| Pegatron      | 3580                        | Desktop     | [580355d3da](https://linux-hardware.org/?probe=580355d3da) | Dec 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [dd97dbccbd](https://linux-hardware.org/?probe=dd97dbccbd) | Dec 08, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [1d8b3c85a3](https://linux-hardware.org/?probe=1d8b3c85a3) | Dec 07, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [e9ddadffad](https://linux-hardware.org/?probe=e9ddadffad) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [13c1812169](https://linux-hardware.org/?probe=13c1812169) | Dec 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [d59a49d5b5](https://linux-hardware.org/?probe=d59a49d5b5) | Dec 06, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [cf753bfc89](https://linux-hardware.org/?probe=cf753bfc89) | Dec 05, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [a13beb506c](https://linux-hardware.org/?probe=a13beb506c) | Dec 05, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [0964d78171](https://linux-hardware.org/?probe=0964d78171) | Dec 04, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [468a017a07](https://linux-hardware.org/?probe=468a017a07) | Dec 04, 2023 |
| Lenovo        | 30BD NOK                    | Desktop     | [0bc5f46c93](https://linux-hardware.org/?probe=0bc5f46c93) | Dec 02, 2023 |
| ONDA          | H81M                        | Desktop     | [76c44af7fc](https://linux-hardware.org/?probe=76c44af7fc) | Dec 02, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [8f5c7fb36e](https://linux-hardware.org/?probe=8f5c7fb36e) | Dec 02, 2023 |
| Lenovo        | ThinkPad X220 4291OL3       | Notebook    | [d07f89fdd6](https://linux-hardware.org/?probe=d07f89fdd6) | Dec 02, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [797de8d000](https://linux-hardware.org/?probe=797de8d000) | Dec 01, 2023 |
| Gigabyte      | B250-D3A-CF                 | Desktop     | [5d3de45ec6](https://linux-hardware.org/?probe=5d3de45ec6) | Dec 01, 2023 |
| ASUSTek       | M4A88T-M LE                 | Desktop     | [a2f1655886](https://linux-hardware.org/?probe=a2f1655886) | Dec 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [96a30d5a91](https://linux-hardware.org/?probe=96a30d5a91) | Nov 30, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [6169504543](https://linux-hardware.org/?probe=6169504543) | Nov 30, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [67f4d1ef37](https://linux-hardware.org/?probe=67f4d1ef37) | Nov 30, 2023 |
| Dell          | Precision 7750              | Notebook    | [1edebf75b2](https://linux-hardware.org/?probe=1edebf75b2) | Nov 30, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [a28950ea38](https://linux-hardware.org/?probe=a28950ea38) | Nov 30, 2023 |
| ASUSTek       | M4A88T-M LE                 | Desktop     | [1e982d5ac9](https://linux-hardware.org/?probe=1e982d5ac9) | Nov 30, 2023 |
| AZW           | LZX TBD                     | Desktop     | [11f35f4369](https://linux-hardware.org/?probe=11f35f4369) | Nov 30, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [f16bc78368](https://linux-hardware.org/?probe=f16bc78368) | Nov 29, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [879c59cf41](https://linux-hardware.org/?probe=879c59cf41) | Nov 29, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [4cd53ef516](https://linux-hardware.org/?probe=4cd53ef516) | Nov 29, 2023 |
| HP            | 8053                        | Desktop     | [6d6877e008](https://linux-hardware.org/?probe=6d6877e008) | Nov 29, 2023 |
| Founder       | Q87H3-AM V:1.0              | Desktop     | [56a7ef0f8a](https://linux-hardware.org/?probe=56a7ef0f8a) | Nov 29, 2023 |
| Notebook      | P7xxTM                      | Notebook    | [d1a0cf0f45](https://linux-hardware.org/?probe=d1a0cf0f45) | Nov 28, 2023 |
| GITSTAR       | GDC-1461                    | Notebook    | [26a9582fb3](https://linux-hardware.org/?probe=26a9582fb3) | Nov 28, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [db0496034a](https://linux-hardware.org/?probe=db0496034a) | Nov 28, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [12a35cc75d](https://linux-hardware.org/?probe=12a35cc75d) | Nov 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [d2e56a6b92](https://linux-hardware.org/?probe=d2e56a6b92) | Nov 27, 2023 |
| Google        | Terra                       | Notebook    | [b21072bf0e](https://linux-hardware.org/?probe=b21072bf0e) | Nov 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [97e207d679](https://linux-hardware.org/?probe=97e207d679) | Nov 27, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [63c8ac9339](https://linux-hardware.org/?probe=63c8ac9339) | Nov 27, 2023 |
| Lenovo        | ThinkPad X200 7458PN6       | Notebook    | [e37f4ef1d4](https://linux-hardware.org/?probe=e37f4ef1d4) | Nov 27, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [eda83a98f2](https://linux-hardware.org/?probe=eda83a98f2) | Nov 27, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [a6ab0954e0](https://linux-hardware.org/?probe=a6ab0954e0) | Nov 25, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [4ce52b15f5](https://linux-hardware.org/?probe=4ce52b15f5) | Nov 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [c45c9df0f9](https://linux-hardware.org/?probe=c45c9df0f9) | Nov 24, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | Notebook    | [4065934176](https://linux-hardware.org/?probe=4065934176) | Nov 22, 2023 |
| Loongson      | LS3A6000-7A2000-1w-V0.1-... | Desktop     | [7930532d04](https://linux-hardware.org/?probe=7930532d04) | Nov 21, 2023 |
| Lenovo        | Legion R7000P ARH7 82RE     | Notebook    | [0ae39d9390](https://linux-hardware.org/?probe=0ae39d9390) | Nov 20, 2023 |
| MACHENIKE     | L16W                        | Notebook    | [7c881a79a6](https://linux-hardware.org/?probe=7c881a79a6) | Nov 19, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [da00d0b6ca](https://linux-hardware.org/?probe=da00d0b6ca) | Nov 18, 2023 |
| ASUSTek       | S300CA                      | Notebook    | [0d1a79b878](https://linux-hardware.org/?probe=0d1a79b878) | Nov 18, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [8337bc9061](https://linux-hardware.org/?probe=8337bc9061) | Nov 17, 2023 |
| BananaPi      | RK3568-BPI-R2PRO-PC HDMI... | Soc         | [9395029e63](https://linux-hardware.org/?probe=9395029e63) | Nov 17, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [8fd3066986](https://linux-hardware.org/?probe=8fd3066986) | Nov 16, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [6de33389c6](https://linux-hardware.org/?probe=6de33389c6) | Nov 16, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [6ca61734e4](https://linux-hardware.org/?probe=6ca61734e4) | Nov 16, 2023 |
| Lenovo        | XiaoXinPro 16 IRH8 83AQ     | Notebook    | [1eb15d0477](https://linux-hardware.org/?probe=1eb15d0477) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [5d3a796122](https://linux-hardware.org/?probe=5d3a796122) | Nov 14, 2023 |
| HP            | ZHAN 66 Pro G2 Notebook ... | Notebook    | [f93402c5f5](https://linux-hardware.org/?probe=f93402c5f5) | Nov 14, 2023 |
| WanYou        | WanYouChunXiao              | Desktop     | [82c62804fc](https://linux-hardware.org/?probe=82c62804fc) | Nov 13, 2023 |
| Timi          | TM1612                      | Notebook    | [3f53f3ed81](https://linux-hardware.org/?probe=3f53f3ed81) | Nov 13, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [090f08ef48](https://linux-hardware.org/?probe=090f08ef48) | Nov 12, 2023 |
| Lenovo        | XINYUANMENGF2895            | Desktop     | [14d0895e0f](https://linux-hardware.org/?probe=14d0895e0f) | Nov 12, 2023 |
| Timi          | TM1612                      | Notebook    | [e8b2659a5f](https://linux-hardware.org/?probe=e8b2659a5f) | Nov 11, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [cf0781bb38](https://linux-hardware.org/?probe=cf0781bb38) | Nov 11, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [7235010ee8](https://linux-hardware.org/?probe=7235010ee8) | Nov 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [671a836d23](https://linux-hardware.org/?probe=671a836d23) | Nov 10, 2023 |
| Loongson      | LS3A6000-7A2000-1w-V0.1-... | Desktop     | [ea4b644bef](https://linux-hardware.org/?probe=ea4b644bef) | Nov 10, 2023 |
| Lenovo        | NOK                         | Desktop     | [6964dd3654](https://linux-hardware.org/?probe=6964dd3654) | Nov 10, 2023 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | Desktop     | [8d9e3d8367](https://linux-hardware.org/?probe=8d9e3d8367) | Nov 10, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [38694893da](https://linux-hardware.org/?probe=38694893da) | Nov 10, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [838e2f455b](https://linux-hardware.org/?probe=838e2f455b) | Nov 09, 2023 |
| ASUSTek       | TX300CA                     | Notebook    | [b6176e4138](https://linux-hardware.org/?probe=b6176e4138) | Nov 09, 2023 |
| Dell          | 0101XX A00                  | Desktop     | [da57698f7d](https://linux-hardware.org/?probe=da57698f7d) | Nov 09, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [1de1299edf](https://linux-hardware.org/?probe=1de1299edf) | Nov 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a5b74f84c4](https://linux-hardware.org/?probe=a5b74f84c4) | Nov 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9010e8e3d3](https://linux-hardware.org/?probe=9010e8e3d3) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [715aee0ee7](https://linux-hardware.org/?probe=715aee0ee7) | Nov 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [54b91fa265](https://linux-hardware.org/?probe=54b91fa265) | Nov 08, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [ec440eff42](https://linux-hardware.org/?probe=ec440eff42) | Nov 08, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [655da69777](https://linux-hardware.org/?probe=655da69777) | Nov 07, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [ec05870944](https://linux-hardware.org/?probe=ec05870944) | Nov 07, 2023 |
| GITSTAR       | GDC-1461                    | Notebook    | [4139b9476a](https://linux-hardware.org/?probe=4139b9476a) | Nov 07, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [c9a30d1e0b](https://linux-hardware.org/?probe=c9a30d1e0b) | Nov 07, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX95D... | Notebook    | [050ecd56d1](https://linux-hardware.org/?probe=050ecd56d1) | Nov 06, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [ea2142174c](https://linux-hardware.org/?probe=ea2142174c) | Nov 06, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [fcd42a2056](https://linux-hardware.org/?probe=fcd42a2056) | Nov 06, 2023 |
| MECHREVO      | Code 01 Series PF5NU1G      | Notebook    | [767c3ff7fa](https://linux-hardware.org/?probe=767c3ff7fa) | Nov 05, 2023 |
| Lenovo        | XiaoXinPro 14 IRH8 83AL     | Notebook    | [de5461c78b](https://linux-hardware.org/?probe=de5461c78b) | Nov 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [b0487db7bf](https://linux-hardware.org/?probe=b0487db7bf) | Nov 04, 2023 |
| Timi          | TM1612                      | Notebook    | [f4284a928a](https://linux-hardware.org/?probe=f4284a928a) | Nov 04, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [b29e9ebfbe](https://linux-hardware.org/?probe=b29e9ebfbe) | Nov 03, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [3618f2a4b5](https://linux-hardware.org/?probe=3618f2a4b5) | Nov 03, 2023 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [249f2a954a](https://linux-hardware.org/?probe=249f2a954a) | Nov 02, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [6b3d70f496](https://linux-hardware.org/?probe=6b3d70f496) | Nov 01, 2023 |
| Dell          | Vostro 5590                 | Notebook    | [300630cf8c](https://linux-hardware.org/?probe=300630cf8c) | Nov 01, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [fdc23b8b95](https://linux-hardware.org/?probe=fdc23b8b95) | Oct 31, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [99ca6d62d6](https://linux-hardware.org/?probe=99ca6d62d6) | Oct 31, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [1472813490](https://linux-hardware.org/?probe=1472813490) | Oct 31, 2023 |
| Gigabyte      | X299 AORUS Gaming 3 Pro-... | Desktop     | [ed34df5e34](https://linux-hardware.org/?probe=ed34df5e34) | Oct 30, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [75cde64adb](https://linux-hardware.org/?probe=75cde64adb) | Oct 30, 2023 |
| Gigabyte      | X299 AORUS Gaming 3 Pro-... | Desktop     | [6e367fa914](https://linux-hardware.org/?probe=6e367fa914) | Oct 30, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [672304cacd](https://linux-hardware.org/?probe=672304cacd) | Oct 29, 2023 |
| GITSTAR       | GDC-1461                    | Notebook    | [ece71c7e63](https://linux-hardware.org/?probe=ece71c7e63) | Oct 29, 2023 |
| Win elemen... | M600                        | Desktop     | [6a027c490c](https://linux-hardware.org/?probe=6a027c490c) | Oct 28, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | Notebook    | [d6486c4e50](https://linux-hardware.org/?probe=d6486c4e50) | Oct 27, 2023 |
| Timi          | TM1612                      | Notebook    | [067b75cd11](https://linux-hardware.org/?probe=067b75cd11) | Oct 27, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [9444fd16a7](https://linux-hardware.org/?probe=9444fd16a7) | Oct 26, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b65f692868](https://linux-hardware.org/?probe=b65f692868) | Oct 26, 2023 |
| Lemote        | LS3B4000-7A1000-2w-V01-s... | Server      | [bb997db6d6](https://linux-hardware.org/?probe=bb997db6d6) | Oct 25, 2023 |
| Lemote        | LS3B4000-7A1000-2w-V01-s... | Server      | [52a1551f31](https://linux-hardware.org/?probe=52a1551f31) | Oct 25, 2023 |
| GITSTAR       | GDC-1461                    | Notebook    | [dbde4628a1](https://linux-hardware.org/?probe=dbde4628a1) | Oct 25, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [35b07b6e34](https://linux-hardware.org/?probe=35b07b6e34) | Oct 25, 2023 |
| WUYING        | NS01-4BGXG                  | Notebook    | [5c999216df](https://linux-hardware.org/?probe=5c999216df) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming FX505GT          | Notebook    | [a5fde2a0ed](https://linux-hardware.org/?probe=a5fde2a0ed) | Oct 24, 2023 |
| Timi          | A34S                        | Notebook    | [56c5c23ce9](https://linux-hardware.org/?probe=56c5c23ce9) | Oct 23, 2023 |
| Lenovo        | Unknown                     | Notebook    | [8681ebe19c](https://linux-hardware.org/?probe=8681ebe19c) | Oct 22, 2023 |
| Lenovo        | ThinkBook 16p Gen 3 21EK    | Notebook    | [f96d0ccdef](https://linux-hardware.org/?probe=f96d0ccdef) | Oct 21, 2023 |
| MSI           | B85M-E45                    | Desktop     | [faedd980e0](https://linux-hardware.org/?probe=faedd980e0) | Oct 20, 2023 |
| Dell          | Precision 7680              | Notebook    | [70f6453d4c](https://linux-hardware.org/?probe=70f6453d4c) | Oct 18, 2023 |
| Dell          | 0MWYPT A02                  | Desktop     | [c0e68da51a](https://linux-hardware.org/?probe=c0e68da51a) | Oct 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [626c7e1591](https://linux-hardware.org/?probe=626c7e1591) | Oct 16, 2023 |
| GITSTAR       | GDC-1461                    | Notebook    | [120e7ba365](https://linux-hardware.org/?probe=120e7ba365) | Oct 15, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [059145d98c](https://linux-hardware.org/?probe=059145d98c) | Oct 15, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a55a8998ea](https://linux-hardware.org/?probe=a55a8998ea) | Oct 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a9438a93a7](https://linux-hardware.org/?probe=a9438a93a7) | Oct 15, 2023 |
| Intel         | X79 V3.0                    | Desktop     | [525be51dcd](https://linux-hardware.org/?probe=525be51dcd) | Oct 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [5584acb2f0](https://linux-hardware.org/?probe=5584acb2f0) | Oct 14, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [14103b4b6a](https://linux-hardware.org/?probe=14103b4b6a) | Oct 14, 2023 |
| HASEE Comp... | CV15S                       | Notebook    | [3bb0d698b5](https://linux-hardware.org/?probe=3bb0d698b5) | Oct 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8be373f42f](https://linux-hardware.org/?probe=8be373f42f) | Oct 14, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [a5124741f5](https://linux-hardware.org/?probe=a5124741f5) | Oct 12, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [25cc758735](https://linux-hardware.org/?probe=25cc758735) | Oct 12, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [c221b8e1e6](https://linux-hardware.org/?probe=c221b8e1e6) | Oct 12, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [39e3632f1f](https://linux-hardware.org/?probe=39e3632f1f) | Oct 11, 2023 |
| Timi          | TM1612                      | Notebook    | [e8c807e4c6](https://linux-hardware.org/?probe=e8c807e4c6) | Oct 11, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [b1b0f03790](https://linux-hardware.org/?probe=b1b0f03790) | Oct 11, 2023 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | Desktop     | [b0ed209424](https://linux-hardware.org/?probe=b0ed209424) | Oct 10, 2023 |
| Timi          | TM1612                      | Notebook    | [e853046494](https://linux-hardware.org/?probe=e853046494) | Oct 10, 2023 |
| Unknown       | Unknown                     | Soc         | [35b752ce47](https://linux-hardware.org/?probe=35b752ce47) | Oct 10, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [6e8b2311e4](https://linux-hardware.org/?probe=6e8b2311e4) | Oct 09, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [406f3baace](https://linux-hardware.org/?probe=406f3baace) | Oct 09, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [38e3f527a6](https://linux-hardware.org/?probe=38e3f527a6) | Oct 07, 2023 |
| Dell          | 0WG860                      | Desktop     | [122cbed188](https://linux-hardware.org/?probe=122cbed188) | Oct 07, 2023 |
| Timi          | RedmiBook Air 13            | Notebook    | [63ea7be36f](https://linux-hardware.org/?probe=63ea7be36f) | Oct 07, 2023 |
| HONOR         | FRI-HXX                     | Notebook    | [fd2a01c055](https://linux-hardware.org/?probe=fd2a01c055) | Oct 06, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [06e6c33346](https://linux-hardware.org/?probe=06e6c33346) | Oct 05, 2023 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | Desktop     | [389a1e8c4e](https://linux-hardware.org/?probe=389a1e8c4e) | Oct 03, 2023 |
| TH510         | D4 v2.3                     | All in one  | [36210c2a9c](https://linux-hardware.org/?probe=36210c2a9c) | Oct 02, 2023 |
| Colorful T... | BATTLE-AX B365M-D V20       | Desktop     | [0beb9e9e28](https://linux-hardware.org/?probe=0beb9e9e28) | Oct 01, 2023 |
| Colorful T... | BATTLE-AX B365M-D V20       | Desktop     | [f8c7c20100](https://linux-hardware.org/?probe=f8c7c20100) | Oct 01, 2023 |
| Colorful T... | BATTLE-AX B365M-D V20       | Desktop     | [c118982282](https://linux-hardware.org/?probe=c118982282) | Oct 01, 2023 |
| Colorful T... | BATTLE-AX B365M-D V20       | Desktop     | [e212af9208](https://linux-hardware.org/?probe=e212af9208) | Sep 30, 2023 |
| Dell          | Vostro 3350                 | Notebook    | [1034a53a9d](https://linux-hardware.org/?probe=1034a53a9d) | Sep 30, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [2d31a3d858](https://linux-hardware.org/?probe=2d31a3d858) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [a5467c367d](https://linux-hardware.org/?probe=a5467c367d) | Sep 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [49090587ce](https://linux-hardware.org/?probe=49090587ce) | Sep 28, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e7b135256f](https://linux-hardware.org/?probe=e7b135256f) | Sep 28, 2023 |
| GreatWall     | GW-001Y1B-FTF               | All in one  | [7a7a16fc50](https://linux-hardware.org/?probe=7a7a16fc50) | Sep 28, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [89d08f5ea8](https://linux-hardware.org/?probe=89d08f5ea8) | Sep 28, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [576c14796a](https://linux-hardware.org/?probe=576c14796a) | Sep 28, 2023 |
| Colorful T... | BATTLE-AX B365M-D V20       | Desktop     | [dfdb4a33bd](https://linux-hardware.org/?probe=dfdb4a33bd) | Sep 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [124f7a0f29](https://linux-hardware.org/?probe=124f7a0f29) | Sep 26, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [cb9b76af08](https://linux-hardware.org/?probe=cb9b76af08) | Sep 25, 2023 |
| Dell          | Vostro 3350                 | Notebook    | [8bb6c19a73](https://linux-hardware.org/?probe=8bb6c19a73) | Sep 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1af364233f](https://linux-hardware.org/?probe=1af364233f) | Sep 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3bb5a0e5a0](https://linux-hardware.org/?probe=3bb5a0e5a0) | Sep 22, 2023 |
| Biostar       | B85MG                       | Desktop     | [f71d8a75fc](https://linux-hardware.org/?probe=f71d8a75fc) | Sep 22, 2023 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [454afdd117](https://linux-hardware.org/?probe=454afdd117) | Sep 21, 2023 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [a020038e27](https://linux-hardware.org/?probe=a020038e27) | Sep 21, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [94e8c710d5](https://linux-hardware.org/?probe=94e8c710d5) | Sep 20, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [5cab8957eb](https://linux-hardware.org/?probe=5cab8957eb) | Sep 18, 2023 |
| GreatWall     | Unknown                     | Soc         | [9b283b5931](https://linux-hardware.org/?probe=9b283b5931) | Sep 18, 2023 |
| HP            | 8062                        | Desktop     | [248710765a](https://linux-hardware.org/?probe=248710765a) | Sep 18, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [290f6c66d1](https://linux-hardware.org/?probe=290f6c66d1) | Sep 17, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | Notebook    | [20d35c7482](https://linux-hardware.org/?probe=20d35c7482) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [3306655fb2](https://linux-hardware.org/?probe=3306655fb2) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [75a8af42cd](https://linux-hardware.org/?probe=75a8af42cd) | Sep 17, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [4b250084f8](https://linux-hardware.org/?probe=4b250084f8) | Sep 17, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [f74d2ae164](https://linux-hardware.org/?probe=f74d2ae164) | Sep 16, 2023 |
| Lenovo        | Legion R9000X2021R 82K8     | Notebook    | [de832cd47a](https://linux-hardware.org/?probe=de832cd47a) | Sep 16, 2023 |
| Lenovo        | ThinkPad T530 235927C       | Notebook    | [85c9a93599](https://linux-hardware.org/?probe=85c9a93599) | Sep 15, 2023 |
| Lenovo        | ThinkPad E470 20H1A0A3CD    | Notebook    | [f71a427eaf](https://linux-hardware.org/?probe=f71a427eaf) | Sep 13, 2023 |
| HP            | 8062                        | Desktop     | [21d9cabd77](https://linux-hardware.org/?probe=21d9cabd77) | Sep 13, 2023 |
| Lenovo        | ThinkPad E470 20H1A0A3CD    | Notebook    | [1f5e019771](https://linux-hardware.org/?probe=1f5e019771) | Sep 13, 2023 |
| AZW           | SER                         | Mini pc     | [f811aed169](https://linux-hardware.org/?probe=f811aed169) | Sep 12, 2023 |
| Google        | Tricky                      | Desktop     | [369d9cc69f](https://linux-hardware.org/?probe=369d9cc69f) | Sep 12, 2023 |
| HP            | 82A1                        | Desktop     | [8a68160c22](https://linux-hardware.org/?probe=8a68160c22) | Sep 12, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | Notebook    | [53961bd222](https://linux-hardware.org/?probe=53961bd222) | Sep 12, 2023 |
| AZW           | SER                         | Mini pc     | [b21cbfa2d7](https://linux-hardware.org/?probe=b21cbfa2d7) | Sep 11, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [0dabf67d5f](https://linux-hardware.org/?probe=0dabf67d5f) | Sep 11, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [b409947c26](https://linux-hardware.org/?probe=b409947c26) | Sep 11, 2023 |
| Timi          | Redmi G 2022                | Notebook    | [320bbb4e83](https://linux-hardware.org/?probe=320bbb4e83) | Sep 10, 2023 |
| Timi          | Redmi G 2022                | Notebook    | [534003f1ab](https://linux-hardware.org/?probe=534003f1ab) | Sep 10, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [f7f7964c03](https://linux-hardware.org/?probe=f7f7964c03) | Sep 09, 2023 |
| ASUSTek       | ROG Strix G733PY_G733PY     | Notebook    | [d5c5247f67](https://linux-hardware.org/?probe=d5c5247f67) | Sep 09, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [0d1c562190](https://linux-hardware.org/?probe=0d1c562190) | Sep 08, 2023 |
| Lenovo        | ZhaoYangN4620Z 20A0Z037K... | Notebook    | [1a6a64e046](https://linux-hardware.org/?probe=1a6a64e046) | Sep 08, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [872f12f24c](https://linux-hardware.org/?probe=872f12f24c) | Sep 08, 2023 |
| Acer          | Swift SF514-55T             | Notebook    | [35816546f8](https://linux-hardware.org/?probe=35816546f8) | Sep 08, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | Notebook    | [9ebc45f613](https://linux-hardware.org/?probe=9ebc45f613) | Sep 07, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [250bc7b8ea](https://linux-hardware.org/?probe=250bc7b8ea) | Sep 07, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [6459a498c5](https://linux-hardware.org/?probe=6459a498c5) | Sep 07, 2023 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [46729805b3](https://linux-hardware.org/?probe=46729805b3) | Sep 07, 2023 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [4ffdbcca94](https://linux-hardware.org/?probe=4ffdbcca94) | Sep 07, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [c57f9232a2](https://linux-hardware.org/?probe=c57f9232a2) | Sep 05, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [48e1f16931](https://linux-hardware.org/?probe=48e1f16931) | Sep 05, 2023 |
| Unknown       | Unknown                     | Soc         | [ac8b7f6a77](https://linux-hardware.org/?probe=ac8b7f6a77) | Sep 05, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [453335f199](https://linux-hardware.org/?probe=453335f199) | Sep 04, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [b3e23f1718](https://linux-hardware.org/?probe=b3e23f1718) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [0c53c2df55](https://linux-hardware.org/?probe=0c53c2df55) | Sep 04, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [8b11ecfd36](https://linux-hardware.org/?probe=8b11ecfd36) | Sep 04, 2023 |
| Notebook      | NK50S5_SZ                   | Notebook    | [f0718be353](https://linux-hardware.org/?probe=f0718be353) | Sep 03, 2023 |
| Broadcom      | platform                    | Soc         | [7b330403ca](https://linux-hardware.org/?probe=7b330403ca) | Sep 02, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [edca0e0264](https://linux-hardware.org/?probe=edca0e0264) | Sep 02, 2023 |
| Lenovo        | IdeaPad Z370                | Notebook    | [5c21431c9d](https://linux-hardware.org/?probe=5c21431c9d) | Sep 01, 2023 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | Desktop     | [f20796c492](https://linux-hardware.org/?probe=f20796c492) | Aug 31, 2023 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | Desktop     | [434c880abf](https://linux-hardware.org/?probe=434c880abf) | Aug 31, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [a99a5ccc55](https://linux-hardware.org/?probe=a99a5ccc55) | Aug 30, 2023 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [f82a030bce](https://linux-hardware.org/?probe=f82a030bce) | Aug 30, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [0eeb1276f0](https://linux-hardware.org/?probe=0eeb1276f0) | Aug 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [dfb8d0f76b](https://linux-hardware.org/?probe=dfb8d0f76b) | Aug 28, 2023 |
| ASUSTek       | X542BP                      | Notebook    | [58cc535a58](https://linux-hardware.org/?probe=58cc535a58) | Aug 26, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [ac607e5597](https://linux-hardware.org/?probe=ac607e5597) | Aug 25, 2023 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [f5f6d366a1](https://linux-hardware.org/?probe=f5f6d366a1) | Aug 24, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | Notebook    | [4b21c7c00f](https://linux-hardware.org/?probe=4b21c7c00f) | Aug 24, 2023 |
| Lenovo        | IdeaPad Z485 20151          | Notebook    | [599346f806](https://linux-hardware.org/?probe=599346f806) | Aug 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [d3bc465020](https://linux-hardware.org/?probe=d3bc465020) | Aug 23, 2023 |
| Google        | Nami                        | Notebook    | [db2c6bfb0a](https://linux-hardware.org/?probe=db2c6bfb0a) | Aug 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [bbae205fe2](https://linux-hardware.org/?probe=bbae205fe2) | Aug 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [a1b816015e](https://linux-hardware.org/?probe=a1b816015e) | Aug 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [266edae3d0](https://linux-hardware.org/?probe=266edae3d0) | Aug 23, 2023 |
| FriendlyEl... | NanoPi R2S                  | Soc         | [9777892665](https://linux-hardware.org/?probe=9777892665) | Aug 23, 2023 |
| MSI           | Z370-OC PRO                 | Desktop     | [4ee0bb1c63](https://linux-hardware.org/?probe=4ee0bb1c63) | Aug 23, 2023 |
| Google        | Nami                        | Notebook    | [69d8c7bfb8](https://linux-hardware.org/?probe=69d8c7bfb8) | Aug 22, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [236b200fd8](https://linux-hardware.org/?probe=236b200fd8) | Aug 22, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [ae599c9d4b](https://linux-hardware.org/?probe=ae599c9d4b) | Aug 22, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [16d770ddb1](https://linux-hardware.org/?probe=16d770ddb1) | Aug 22, 2023 |
| MSI           | Z370-OC PRO                 | Desktop     | [bbd85c94d6](https://linux-hardware.org/?probe=bbd85c94d6) | Aug 22, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [c0e0a27946](https://linux-hardware.org/?probe=c0e0a27946) | Aug 22, 2023 |
| Lenovo        | xxxx IdeaCentre A300        | All in one  | [988ed124ee](https://linux-hardware.org/?probe=988ed124ee) | Aug 21, 2023 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [d2d0a35161](https://linux-hardware.org/?probe=d2d0a35161) | Aug 20, 2023 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [09b4672dc1](https://linux-hardware.org/?probe=09b4672dc1) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | Notebook    | [b156da40ac](https://linux-hardware.org/?probe=b156da40ac) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | Notebook    | [8b4709e684](https://linux-hardware.org/?probe=8b4709e684) | Aug 20, 2023 |
| Lenovo        | xxxx IdeaCentre A300        | All in one  | [402e225e25](https://linux-hardware.org/?probe=402e225e25) | Aug 19, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [006d138f62](https://linux-hardware.org/?probe=006d138f62) | Aug 19, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [3223b9a4bb](https://linux-hardware.org/?probe=3223b9a4bb) | Aug 19, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | Desktop     | [cc09706b5f](https://linux-hardware.org/?probe=cc09706b5f) | Aug 19, 2023 |
| HUAWEI        | FRD-WX9                     | Notebook    | [678a3a9328](https://linux-hardware.org/?probe=678a3a9328) | Aug 19, 2023 |
| AZW           | EQ                          | Desktop     | [6fda99ad46](https://linux-hardware.org/?probe=6fda99ad46) | Aug 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [b8ceea98b8](https://linux-hardware.org/?probe=b8ceea98b8) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4656cc9656](https://linux-hardware.org/?probe=4656cc9656) | Aug 17, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [14ea4148dc](https://linux-hardware.org/?probe=14ea4148dc) | Aug 17, 2023 |
| CWWK          | N3050 P1                    | Desktop     | [dd3dfb0c02](https://linux-hardware.org/?probe=dd3dfb0c02) | Aug 17, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [bfe3223b92](https://linux-hardware.org/?probe=bfe3223b92) | Aug 17, 2023 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [815cb59889](https://linux-hardware.org/?probe=815cb59889) | Aug 16, 2023 |
| HUAWEI        | WRT-WX9                     | Notebook    | [39a98650a3](https://linux-hardware.org/?probe=39a98650a3) | Aug 16, 2023 |
| TSINGHUA T... | B460-N2                     | Desktop     | [f7f87f7a07](https://linux-hardware.org/?probe=f7f87f7a07) | Aug 16, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [253750d7f8](https://linux-hardware.org/?probe=253750d7f8) | Aug 15, 2023 |
| MSI           | Z790 GAMING WIFI            | Notebook    | [95e340d91b](https://linux-hardware.org/?probe=95e340d91b) | Aug 14, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [871c589fb9](https://linux-hardware.org/?probe=871c589fb9) | Aug 13, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [d978d063e8](https://linux-hardware.org/?probe=d978d063e8) | Aug 13, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [a6212b25ea](https://linux-hardware.org/?probe=a6212b25ea) | Aug 13, 2023 |
| Dell          | 0GNVHC A00                  | Desktop     | [27e3be4942](https://linux-hardware.org/?probe=27e3be4942) | Aug 12, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [dad31fab00](https://linux-hardware.org/?probe=dad31fab00) | Aug 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [a28cd220cd](https://linux-hardware.org/?probe=a28cd220cd) | Aug 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [f62d9a8a9a](https://linux-hardware.org/?probe=f62d9a8a9a) | Aug 12, 2023 |
| Jumper        | EZpad                       | Notebook    | [5fa2e934c3](https://linux-hardware.org/?probe=5fa2e934c3) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [a064a2d5fd](https://linux-hardware.org/?probe=a064a2d5fd) | Aug 11, 2023 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | Desktop     | [bc9cacebe8](https://linux-hardware.org/?probe=bc9cacebe8) | Aug 11, 2023 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | Desktop     | [99458c04da](https://linux-hardware.org/?probe=99458c04da) | Aug 10, 2023 |
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
| Phytium       | FT2000/4                    | Server      | [5f78f7d216](https://linux-hardware.org/?probe=5f78f7d216) | Jun 30, 2023 |
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
| Unknown       | Unknown                     | Desktop     | [9cb76f0184](https://linux-hardware.org/?probe=9cb76f0184) | Jun 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e2052896c](https://linux-hardware.org/?probe=7e2052896c) | Jun 04, 2023 |
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
| Unknown       | Unknown                     | Desktop     | [0f85a652ad](https://linux-hardware.org/?probe=0f85a652ad) | May 28, 2023 |
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
| Phytium       | FT2000/4                    | Server      | [ef9af7edf3](https://linux-hardware.org/?probe=ef9af7edf3) | May 09, 2023 |
| Koloe         | X58                         | Desktop     | [7c1acc3b84](https://linux-hardware.org/?probe=7c1acc3b84) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [d615a9b90f](https://linux-hardware.org/?probe=d615a9b90f) | May 08, 2023 |
| Quanta        | TWH                         | Notebook    | [724b4d7343](https://linux-hardware.org/?probe=724b4d7343) | May 06, 2023 |
| Lenovo        | IdeaPad Y480 20131          | Notebook    | [d625664bee](https://linux-hardware.org/?probe=d625664bee) | May 06, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [850ea7c843](https://linux-hardware.org/?probe=850ea7c843) | May 06, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [eb289c3d5f](https://linux-hardware.org/?probe=eb289c3d5f) | May 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [043c078caf](https://linux-hardware.org/?probe=043c078caf) | May 05, 2023 |
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
| Phytium       | FT2000/4                    | Server      | [d59b9ff270](https://linux-hardware.org/?probe=d59b9ff270) | Apr 26, 2023 |
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
| Unknown       | Unknown                     | Desktop     | [018daf402b](https://linux-hardware.org/?probe=018daf402b) | Apr 15, 2023 |
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
| Lenovo        | Unknown                     | Notebook    | [9bfcd0f555](https://linux-hardware.org/?probe=9bfcd0f555) | Jan 14, 2023 |
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
| Phytium       | FT2000/4                    | Server      | [11e15101d3](https://linux-hardware.org/?probe=11e15101d3) | Dec 14, 2022 |
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
| Phytium       | FT2000/4                    | Server      | [0e38f0e485](https://linux-hardware.org/?probe=0e38f0e485) | Oct 26, 2022 |
| Phytium       | D2000                       | Server      | [f3f6092888](https://linux-hardware.org/?probe=f3f6092888) | Oct 26, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [5b6f2b76da](https://linux-hardware.org/?probe=5b6f2b76da) | Oct 25, 2022 |
| Dell          | 0MWYPT A02                  | Desktop     | [cf186994cc](https://linux-hardware.org/?probe=cf186994cc) | Oct 25, 2022 |
| Phytium       | FT2000/4                    | Server      | [3dbec91bce](https://linux-hardware.org/?probe=3dbec91bce) | Oct 25, 2022 |
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
| Ubuntu 20.04                 | 192       | 11.24%  |
| Ubuntu 18.04                 | 138       | 8.08%   |
| Ubuntu 22.04                 | 128       | 7.49%   |
| Arch Rolling                 | 85        | 4.98%   |
| Debian 11                    | 81        | 4.74%   |
| Arch                         | 50        | 2.93%   |
| Debian 12                    | 37        | 2.17%   |
| Kylin V10                    | 29        | 1.7%    |
| UOS 20                       | 28        | 1.64%   |
| Debian 10                    | 27        | 1.58%   |
| Manjaro                      | 25        | 1.46%   |
| openSUSE Tumbleweed-XXXXXXXX | 24        | 1.41%   |
| OpenMandriva 4.3             | 24        | 1.41%   |
| Ubuntu 19.04                 | 21        | 1.23%   |
| OpenMandriva 4.2             | 20        | 1.17%   |
| Ubuntu 16.04                 | 19        | 1.11%   |
| Gentoo 2.8                   | 19        | 1.11%   |
| KDE neon 20.04               | 17        | 1%      |
| Fedora 38                    | 17        | 1%      |
| Ubuntu 21.10                 | 16        | 0.94%   |
| Gentoo 2.7                   | 16        | 0.94%   |
| ArcoLinux Rolling            | 16        | 0.94%   |
| Ubuntu 23.04                 | 15        | 0.88%   |
| Ubuntu 21.04                 | 14        | 0.82%   |
| Ubuntu 19.10                 | 14        | 0.82%   |
| CentOS 7                     | 14        | 0.82%   |
| Ubuntu 22.10                 | 13        | 0.76%   |
| Fedora 33                    | 13        | 0.76%   |
| Linux Mint 20.3              | 12        | 0.7%    |
| Linux Mint 20.1              | 12        | 0.7%    |
| Fedora 39                    | 11        | 0.64%   |
| CentOS 8                     | 11        | 0.64%   |
| OpenMandriva 23.03           | 10        | 0.59%   |
| Xero Rolling                 | 9         | 0.53%   |
| OpenMandriva 4.50            | 9         | 0.53%   |
| OpenMandriva 23.08           | 9         | 0.53%   |
| Gentoo 2.6                   | 9         | 0.53%   |
| Fedora 35                    | 9         | 0.53%   |
| Zorin 16                     | 8         | 0.47%   |
| Ubuntu 23.10                 | 8         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 571       | 35.01%  |
| Debian       | 174       | 10.67%  |
| Arch         | 132       | 8.09%   |
| Fedora       | 83        | 5.09%   |
| OpenMandriva | 79        | 4.84%   |
| Manjaro      | 76        | 4.66%   |
| Gentoo       | 52        | 3.19%   |
| Linux Mint   | 50        | 3.07%   |
| Deepin       | 46        | 2.82%   |
| Kylin        | 31        | 1.9%    |
| openSUSE     | 29        | 1.78%   |
| CentOS       | 27        | 1.66%   |
| Kubuntu      | 25        | 1.53%   |
| Atz          | 23        | 1.41%   |
| KDE neon     | 20        | 1.23%   |
| ArcoLinux    | 17        | 1.04%   |
| SteamOS      | 16        | 0.98%   |
| Kali         | 16        | 0.98%   |
| Pop!_OS      | 15        | 0.92%   |
| Xubuntu      | 14        | 0.86%   |
| Ubuntu Unity | 13        | 0.8%    |
| ROSA         | 12        | 0.74%   |
| Elementary   | 10        | 0.61%   |
| Xero         | 9         | 0.55%   |
| Zorin        | 8         | 0.49%   |
| Clear Linux  | 8         | 0.49%   |
| OpenEuler    | 5         | 0.31%   |
| BlackPanther | 4         | 0.25%   |
| Android      | 4         | 0.25%   |
| Ubuntu MATE  | 3         | 0.18%   |
| Trisquel     | 3         | 0.18%   |
| NFS Desktop  | 3         | 0.18%   |
| LMDE         | 3         | 0.18%   |
| Guix         | 3         | 0.18%   |
| Alpine       | 3         | 0.18%   |
| Ubuntu Kylin | 2         | 0.12%   |
| Solus        | 2         | 0.12%   |
| Slackware    | 2         | 0.12%   |
| Rocky Linux  | 2         | 0.12%   |
| RHEL         | 2         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 22        | 1.2%    |
| 5.10.14-desktop-1omv4002 | 19        | 1.04%   |
| 6.2.0-26-generic         | 17        | 0.93%   |
| 5.4.0-42-generic         | 15        | 0.82%   |
| 6.1.0-13-amd64           | 12        | 0.66%   |
| 6.5.0-14-generic         | 10        | 0.55%   |
| 6.2.6-desktop-1omv2390   | 10        | 0.55%   |
| 5.19.0-46-generic        | 10        | 0.55%   |
| 5.15.0-56-generic        | 10        | 0.55%   |
| 5.13.0-30-generic        | 10        | 0.55%   |
| 5.10.0-8-amd64           | 10        | 0.55%   |
| 5.0.0-23-generic         | 10        | 0.55%   |
| 6.2.0-32-generic         | 9         | 0.49%   |
| 5.15.0-46-generic        | 9         | 0.49%   |
| 6.2.0-20-generic         | 8         | 0.44%   |
| 5.15.0-67-generic        | 8         | 0.44%   |
| 5.11.0-43-generic        | 8         | 0.44%   |
| 5.11.0-27-generic        | 8         | 0.44%   |
| 4.18.0-25-generic        | 8         | 0.44%   |
| 6.4.11-desktop-1omv2390  | 7         | 0.38%   |
| 6.2.0-39-generic         | 7         | 0.38%   |
| 6.1.0-9-amd64            | 7         | 0.38%   |
| 5.4.0-58-generic         | 7         | 0.38%   |
| 5.19.0-26-generic        | 7         | 0.38%   |
| 5.19.0-23-generic        | 7         | 0.38%   |
| 5.15.0-52-generic        | 7         | 0.38%   |
| 5.12.4-desktop-1omv4050  | 7         | 0.38%   |
| 5.10.0-amd64-desktop     | 7         | 0.38%   |
| 5.10.0-21-amd64          | 7         | 0.38%   |
| 5.0.0-13-generic         | 7         | 0.38%   |
| 4.18.0-16-generic        | 7         | 0.38%   |
| 6.6.2-desktop-1omv2390   | 6         | 0.33%   |
| 5.8.0-50-generic         | 6         | 0.33%   |
| 5.4.0-74-generic         | 6         | 0.33%   |
| 5.4.0-73-generic         | 6         | 0.33%   |
| 5.4.0-48-generic         | 6         | 0.33%   |
| 5.4.0-33-generic         | 6         | 0.33%   |
| 5.4.0-29-generic         | 6         | 0.33%   |
| 5.3.0-46-generic         | 6         | 0.33%   |
| 5.19.0-41-generic        | 6         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 153       | 8.73%   |
| 5.15.0  | 126       | 7.19%   |
| 5.10.0  | 99        | 5.65%   |
| 4.15.0  | 66        | 3.76%   |
| 5.13.0  | 62        | 3.54%   |
| 6.2.0   | 61        | 3.48%   |
| 5.11.0  | 61        | 3.48%   |
| 5.19.0  | 48        | 2.74%   |
| 5.8.0   | 45        | 2.57%   |
| 4.18.0  | 45        | 2.57%   |
| 5.0.0   | 44        | 2.51%   |
| 6.1.0   | 38        | 2.17%   |
| 5.3.0   | 35        | 2%      |
| 4.19.0  | 32        | 1.83%   |
| 6.5.0   | 24        | 1.37%   |
| 5.16.7  | 23        | 1.31%   |
| 5.10.14 | 19        | 1.08%   |
| 5.14.0  | 12        | 0.68%   |
| 3.10.0  | 12        | 0.68%   |
| 6.4.11  | 11        | 0.63%   |
| 6.2.6   | 11        | 0.63%   |
| 5.4.18  | 10        | 0.57%   |
| 5.18.0  | 8         | 0.46%   |
| 5.16.0  | 8         | 0.46%   |
| 6.6.2   | 7         | 0.4%    |
| 6.5.3   | 7         | 0.4%    |
| 6.0.0   | 7         | 0.4%    |
| 5.6.14  | 7         | 0.4%    |
| 5.17.0  | 7         | 0.4%    |
| 5.12.4  | 7         | 0.4%    |
| 4.1.42  | 7         | 0.4%    |
| 6.6.9   | 6         | 0.34%   |
| 6.4.0   | 6         | 0.34%   |
| 6.3.5   | 6         | 0.34%   |
| 5.18.12 | 6         | 0.34%   |
| 6.6.1   | 5         | 0.29%   |
| 6.4.10  | 5         | 0.29%   |
| 6.3.3   | 5         | 0.29%   |
| 6.2.9   | 5         | 0.29%   |
| 6.1.11  | 5         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 193       | 11.15%  |
| 5.15    | 193       | 11.15%  |
| 5.10    | 181       | 10.46%  |
| 6.2     | 88        | 5.08%   |
| 6.1     | 80        | 4.62%   |
| 5.11    | 78        | 4.51%   |
| 5.13    | 73        | 4.22%   |
| 4.15    | 66        | 3.81%   |
| 5.8     | 61        | 3.52%   |
| 5.19    | 59        | 3.41%   |
| 6.5     | 51        | 2.95%   |
| 4.19    | 49        | 2.83%   |
| 5.0     | 48        | 2.77%   |
| 4.18    | 47        | 2.72%   |
| 5.16    | 46        | 2.66%   |
| 5.3     | 42        | 2.43%   |
| 6.4     | 40        | 2.31%   |
| 5.18    | 37        | 2.14%   |
| 6.6     | 33        | 1.91%   |
| 5.14    | 31        | 1.79%   |
| 6.0     | 28        | 1.62%   |
| 5.17    | 27        | 1.56%   |
| 6.3     | 25        | 1.44%   |
| 5.12    | 24        | 1.39%   |
| 5.9     | 21        | 1.21%   |
| 5.6     | 19        | 1.1%    |
| 4.9     | 14        | 0.81%   |
| 3.10    | 14        | 0.81%   |
| 5.7     | 12        | 0.69%   |
| 4.1     | 9         | 0.52%   |
| 5.5     | 8         | 0.46%   |
| 5.1     | 5         | 0.29%   |
| 4.14    | 5         | 0.29%   |
| 4.4     | 4         | 0.23%   |
| 4.13    | 3         | 0.17%   |
| 2.6     | 3         | 0.17%   |
| 6.7     | 2         | 0.12%   |
| 5.2     | 2         | 0.12%   |
| 4.20    | 2         | 0.12%   |
| 3.4     | 2         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 1481      | 93.14%  |
| aarch64     | 56        | 3.52%   |
| riscv64     | 14        | 0.88%   |
| i686        | 11        | 0.69%   |
| ppc64       | 7         | 0.44%   |
| armv7l      | 6         | 0.38%   |
| loongarch64 | 4         | 0.25%   |
| ppc64le     | 2         | 0.13%   |
| mips64      | 2         | 0.13%   |
| sparc64     | 1         | 0.06%   |
| sh4a        | 1         | 0.06%   |
| ppc         | 1         | 0.06%   |
| i586        | 1         | 0.06%   |
| i486        | 1         | 0.06%   |
| armv8l      | 1         | 0.06%   |
| Unknown     | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 683       | 41.47%  |
| KDE5            | 286       | 17.36%  |
| Unknown         | 274       | 16.64%  |
| XFCE            | 129       | 7.83%   |
| Deepin          | 45        | 2.73%   |
| X-Cinnamon      | 41        | 2.49%   |
| KDE             | 35        | 2.13%   |
| MATE            | 27        | 1.64%   |
| i3              | 21        | 1.28%   |
| UKUI            | 17        | 1.03%   |
| Unity           | 12        | 0.73%   |
| Pantheon        | 10        | 0.61%   |
| LXDE            | 8         | 0.49%   |
| Cinnamon        | 8         | 0.49%   |
| KDE4            | 6         | 0.36%   |
| Budgie          | 6         | 0.36%   |
| LXQt            | 5         | 0.3%    |
| GNOME Flashback | 5         | 0.3%    |
| sway            | 4         | 0.24%   |
| Openbox         | 4         | 0.24%   |
| Hyprland        | 4         | 0.24%   |
| GNOME Classic   | 4         | 0.24%   |
| GNUstep         | 2         | 0.12%   |
| DWM             | 2         | 0.12%   |
| DDE             | 2         | 0.12%   |
| xmonad          | 1         | 0.06%   |
| Wayfire         | 1         | 0.06%   |
| qtile           | 1         | 0.06%   |
| default         | 1         | 0.06%   |
| chadwm          | 1         | 0.06%   |
| bspwm           | 1         | 0.06%   |
| awesome         | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1070      | 65.48%  |
| Wayland | 296       | 18.12%  |
| Unknown | 135       | 8.26%   |
| Tty     | 133       | 8.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 637       | 39.18%  |
| GDM3    | 252       | 15.5%   |
| SDDM    | 244       | 15.01%  |
| LightDM | 219       | 13.47%  |
| GDM     | 217       | 13.35%  |
| TDM     | 43        | 2.64%   |
| KDM     | 4         | 0.25%   |
| XDM     | 3         | 0.18%   |
| LXDM    | 3         | 0.18%   |
| SLiM    | 2         | 0.12%   |
| LY-DM   | 2         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| zh_CN       | 731       | 45.04%  |
| en_US       | 581       | 35.8%   |
| Unknown     | 190       | 11.71%  |
| C           | 55        | 3.39%   |
| en_HK       | 17        | 1.05%   |
| en_GB       | 15        | 0.92%   |
| C.UTF8      | 6         | 0.37%   |
| mn_CN       | 4         | 0.25%   |
| ru_RU       | 3         | 0.18%   |
| en_AU       | 3         | 0.18%   |
| zh_TW       | 2         | 0.12%   |
| ja_JP       | 2         | 0.12%   |
| fr_FR       | 2         | 0.12%   |
| de_DE       | 2         | 0.12%   |
| zh_HK       | 1         | 0.06%   |
| th_TH       | 1         | 0.06%   |
| pt_PT       | 1         | 0.06%   |
| POSIX       | 1         | 0.06%   |
| en_ZA       | 1         | 0.06%   |
| en_US.UTF8  | 1         | 0.06%   |
| en_US.utf-8 | 1         | 0.06%   |
| en_US,UTF-8 | 1         | 0.06%   |
| en_SG       | 1         | 0.06%   |
| .en_US      | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1074      | 66.83%  |
| BIOS | 533       | 33.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Computers | Percent |
|------------|-----------|---------|
| Ext4       | 1197      | 74.07%  |
| Btrfs      | 182       | 11.26%  |
| Overlay    | 71        | 4.39%   |
| Xfs        | 64        | 3.96%   |
| Tmpfs      | 46        | 2.85%   |
| Unknown    | 32        | 1.98%   |
| Zfs        | 13        | 0.8%    |
| Rootfs     | 4         | 0.25%   |
| F2fs       | 4         | 0.25%   |
| XXXXXXX    | 1         | 0.06%   |
| Reiserfs   | 1         | 0.06%   |
| Fuse.sshfs | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 937       | 58.34%  |
| Unknown | 531       | 33.06%  |
| MBR     | 138       | 8.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1357      | 83.66%  |
| Yes       | 265       | 16.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 977       | 61.02%  |
| Yes       | 624       | 38.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 384       | 24.17%  |
| ASUSTek Computer               | 181       | 11.39%  |
| Dell                           | 154       | 9.69%   |
| Hewlett-Packard                | 123       | 7.74%   |
| HUAWEI                         | 64        | 4.03%   |
| Gigabyte Technology            | 61        | 3.84%   |
| Unknown                        | 61        | 3.84%   |
| MSI                            | 57        | 3.59%   |
| Timi                           | 47        | 2.96%   |
| Intel                          | 42        | 2.64%   |
| Acer                           | 37        | 2.33%   |
| MECHREVO                       | 20        | 1.26%   |
| Apple                          | 19        | 1.2%    |
| ASRock                         | 16        | 1.01%   |
| HASEE Computer                 | 15        | 0.94%   |
| Google                         | 11        | 0.69%   |
| AZW                            | 11        | 0.69%   |
| Valve                          | 10        | 0.63%   |
| Supermicro                     | 10        | 0.63%   |
| Raspberry Pi Foundation        | 10        | 0.63%   |
| Phytium                        | 10        | 0.63%   |
| Microsoft                      | 10        | 0.63%   |
| Toshiba                        | 9         | 0.57%   |
| GPD                            | 9         | 0.57%   |
| TSINGHUA TONGFANG COMPUTER     | 8         | 0.5%    |
| Sony                           | 8         | 0.5%    |
| GreatWall                      | 8         | 0.5%    |
| Huanan                         | 7         | 0.44%   |
| HONOR                          | 7         | 0.44%   |
| Colorful Technology            | 7         | 0.44%   |
| AMI                            | 7         | 0.44%   |
| Samsung Electronics            | 6         | 0.38%   |
| Notebook                       | 6         | 0.38%   |
| Shanghai Zhaoxin Semiconductor | 5         | 0.31%   |
| OEM                            | 5         | 0.31%   |
| Loongson                       | 5         | 0.31%   |
| Inspur                         | 5         | 0.31%   |
| Win element                    | 4         | 0.25%   |
| ONDA                           | 4         | 0.25%   |
| Jumper                         | 4         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 78        | 4.91%   |
| ASUS All Series                     | 18        | 1.13%   |
| Valve Jupiter                       | 10        | 0.63%   |
| Lenovo Legion R9000P2021H 82JQ      | 10        | 0.63%   |
| TSINGHUA TONGFANG COMPUTER E500     | 8         | 0.5%    |
| HUAWEI HLY-WX9XX                    | 8         | 0.5%    |
| MSI MS-7B89                         | 7         | 0.44%   |
| Timi RedmiBook Pro 15S              | 6         | 0.38%   |
| AZW SER                             | 6         | 0.38%   |
| Timi TM1701                         | 5         | 0.31%   |
| Supermicro Super Server             | 5         | 0.31%   |
| MSI MS-7C94                         | 5         | 0.31%   |
| Lenovo Legion R7000 2020 82B6       | 5         | 0.31%   |
| ASUS TUF Gaming B550M-PLUS          | 5         | 0.31%   |
| AMI Aptio CRB                       | 5         | 0.31%   |
| Timi TM1709                         | 4         | 0.25%   |
| Shanghai Zhaoxin ZXE CRB            | 4         | 0.25%   |
| Phytium FT-2000/4                   | 4         | 0.25%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM   | 4         | 0.25%   |
| Lenovo XiaoXin-15ARE 2020 81YR      | 4         | 0.25%   |
| Lenovo ThinkStation P520 30BFSG3Y00 | 4         | 0.25%   |
| Lenovo ThinkBook 15p Gen 2 21B1     | 4         | 0.25%   |
| Lenovo ThinkBook 14 G2 ITL 20VD     | 4         | 0.25%   |
| Lenovo Legion Y7000 81FW            | 4         | 0.25%   |
| HUAWEI NBLK-WAX9X                   | 4         | 0.25%   |
| HUAWEI KPRC-WX0                     | 4         | 0.25%   |
| HUAWEI BOHK-WAX9X                   | 4         | 0.25%   |
| Dell XPS 15 9570                    | 4         | 0.25%   |
| Dell PowerEdge R730xd               | 4         | 0.25%   |
| ASUS M5A78L-M LX3 PLUS              | 4         | 0.25%   |
| Apple MacBookPro16,1                | 4         | 0.25%   |
| Acer Swift SF314-512                | 4         | 0.25%   |
| Timi TM1613                         | 3         | 0.19%   |
| Timi RedmiBook 14-APCS              | 3         | 0.19%   |
| Timi RedmiBook 14 II                | 3         | 0.19%   |
| RPi Raspberry Pi 4 Model B Rev 1.5  | 3         | 0.19%   |
| RPi Raspberry Pi                    | 3         | 0.19%   |
| Phytium FT2000/4                    | 3         | 0.19%   |
| Phytium D2000                       | 3         | 0.19%   |
| Microsoft Surface Go                | 3         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 133       | 8.37%   |
| Unknown                         | 78        | 4.91%   |
| Lenovo Legion                   | 45        | 2.83%   |
| Dell Inspiron                   | 35        | 2.2%    |
| ASUS ROG                        | 32        | 2.01%   |
| Lenovo ThinkBook                | 29        | 1.83%   |
| ASUS TUF                        | 27        | 1.7%    |
| Dell Precision                  | 24        | 1.51%   |
| ASUS PRIME                      | 24        | 1.51%   |
| HP EliteBook                    | 23        | 1.45%   |
| Dell Latitude                   | 22        | 1.38%   |
| Dell OptiPlex                   | 21        | 1.32%   |
| HP OMEN                         | 20        | 1.26%   |
| HP ZHAN                         | 18        | 1.13%   |
| ASUS All                        | 18        | 1.13%   |
| Acer Aspire                     | 17        | 1.07%   |
| Lenovo IdeaPad                  | 16        | 1.01%   |
| Timi RedmiBook                  | 15        | 0.94%   |
| Lenovo Yoga                     | 15        | 0.94%   |
| Lenovo ThinkCentre              | 15        | 0.94%   |
| Dell XPS                        | 15        | 0.94%   |
| Lenovo ZHAOYANG                 | 13        | 0.82%   |
| Dell PowerEdge                  | 13        | 0.82%   |
| Acer Swift                      | 13        | 0.82%   |
| Dell Vostro                     | 12        | 0.76%   |
| Lenovo ThinkStation             | 11        | 0.69%   |
| HP ProBook                      | 11        | 0.69%   |
| Valve Jupiter                   | 10        | 0.63%   |
| RPi Raspberry                   | 10        | 0.63%   |
| Microsoft Surface               | 10        | 0.63%   |
| Lenovo XiaoXinPro               | 9         | 0.57%   |
| HP ENVY                         | 9         | 0.57%   |
| TSINGHUA TONGFANG COMPUTER E500 | 8         | 0.5%    |
| HUAWEI HLY-WX9XX                | 8         | 0.5%    |
| HP Pavilion                     | 8         | 0.5%    |
| MSI MS-7B89                     | 7         | 0.44%   |
| Lenovo XiaoXin                  | 6         | 0.38%   |
| HP ProDesk                      | 6         | 0.38%   |
| Gigabyte X299                   | 6         | 0.38%   |
| AZW SER                         | 6         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 211       | 13.28%  |
| 2020    | 198       | 12.46%  |
| 2019    | 167       | 10.51%  |
| 2018    | 153       | 9.63%   |
| 2022    | 147       | 9.25%   |
| 2017    | 108       | 6.8%    |
| 2015    | 76        | 4.78%   |
| 2012    | 75        | 4.72%   |
| 2014    | 71        | 4.47%   |
| 2013    | 71        | 4.47%   |
| 2016    | 67        | 4.22%   |
| 2023    | 62        | 3.9%    |
| Unknown | 61        | 3.84%   |
| 2011    | 50        | 3.15%   |
| 2008    | 22        | 1.38%   |
| 2010    | 20        | 1.26%   |
| 2009    | 14        | 0.88%   |
| 2007    | 11        | 0.69%   |
| 2006    | 3         | 0.19%   |
| 2024    | 2         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 892       | 56.14%  |
| Desktop        | 495       | 31.15%  |
| Server         | 53        | 3.34%   |
| Mini pc        | 44        | 2.77%   |
| System on chip | 39        | 2.45%   |
| Tablet         | 29        | 1.83%   |
| Convertible    | 21        | 1.32%   |
| All in one     | 12        | 0.76%   |
| Phone          | 4         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1480      | 92.5%   |
| Enabled  | 120       | 7.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1577      | 99.24%  |
| Yes  | 12        | 0.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 362       | 22.47%  |
| 8.01-16.0       | 359       | 22.28%  |
| 4.01-8.0        | 312       | 19.37%  |
| 32.01-64.0      | 211       | 13.1%   |
| 3.01-4.0        | 150       | 9.31%   |
| 64.01-256.0     | 89        | 5.52%   |
| 24.01-32.0      | 47        | 2.92%   |
| 1.01-2.0        | 32        | 1.99%   |
| Unknown         | 15        | 0.93%   |
| More than 256.0 | 14        | 0.87%   |
| 0.51-1.0        | 13        | 0.81%   |
| 0.01-0.5        | 3         | 0.19%   |
| 2.01-3.0        | 2         | 0.12%   |
| 0               | 2         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 444       | 25.66%  |
| 2.01-3.0    | 423       | 24.45%  |
| 4.01-8.0    | 299       | 17.28%  |
| 3.01-4.0    | 259       | 14.97%  |
| 0.51-1.0    | 100       | 5.78%   |
| 8.01-16.0   | 92        | 5.32%   |
| 0.01-0.5    | 52        | 3.01%   |
| Unknown     | 22        | 1.27%   |
| 16.01-24.0  | 19        | 1.1%    |
| 24.01-32.0  | 8         | 0.46%   |
| 32.01-64.0  | 6         | 0.35%   |
| 64.01-256.0 | 6         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 881       | 54.55%  |
| 2       | 504       | 31.21%  |
| 3       | 127       | 7.86%   |
| 4       | 44        | 2.72%   |
| 5       | 21        | 1.3%    |
| 0       | 12        | 0.74%   |
| 6       | 8         | 0.5%    |
| 10      | 5         | 0.31%   |
| 9       | 3         | 0.19%   |
| 8       | 2         | 0.12%   |
| 46      | 1         | 0.06%   |
| 36      | 1         | 0.06%   |
| 32      | 1         | 0.06%   |
| 27      | 1         | 0.06%   |
| 21      | 1         | 0.06%   |
| 11      | 1         | 0.06%   |
| 7       | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1397      | 87.53%  |
| Yes       | 199       | 12.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1255      | 78.54%  |
| No        | 343       | 21.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1221      | 76.46%  |
| No        | 376       | 23.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1037      | 64.69%  |
| No        | 566       | 35.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| China   | 1589      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Beijing          | 296       | 17.55%  |
| Shanghai         | 143       | 8.48%   |
| Shenzhen         | 131       | 7.77%   |
| Guangzhou        | 109       | 6.46%   |
| Hangzhou         | 64        | 3.79%   |
| Chengdu          | 56        | 3.32%   |
| Wuhan            | 51        | 3.02%   |
| Nanjing          | 38        | 2.25%   |
| Xi'an            | 28        | 1.66%   |
| Jinrongjie       | 27        | 1.6%    |
| Zhengzhou        | 24        | 1.42%   |
| Chongqing        | 23        | 1.36%   |
| Tianjin          | 21        | 1.24%   |
| Haidian          | 20        | 1.19%   |
| Xuhui            | 18        | 1.07%   |
| Suzhou           | 18        | 1.07%   |
| Kunming          | 18        | 1.07%   |
| Shenyang         | 17        | 1.01%   |
| Jinan            | 17        | 1.01%   |
| Foshan           | 17        | 1.01%   |
| Dongguan         | 17        | 1.01%   |
| Changsha         | 17        | 1.01%   |
| Qingdao          | 16        | 0.95%   |
| Hefei            | 16        | 0.95%   |
| Nanning          | 14        | 0.83%   |
| Xiamen           | 12        | 0.71%   |
| Huangpu          | 12        | 0.71%   |
| Fuzhou           | 12        | 0.71%   |
| Jianshui         | 10        | 0.59%   |
| Dalian           | 10        | 0.59%   |
| Bieligutai       | 10        | 0.59%   |
| Nanhao           | 9         | 0.53%   |
| Hohhot           | 9         | 0.53%   |
| Pudong           | 8         | 0.47%   |
| Shijiazhuang     | 7         | 0.41%   |
| Putuo            | 7         | 0.41%   |
| Ningbo           | 7         | 0.41%   |
| Guiyang          | 7         | 0.41%   |
| Zhangzhou        | 6         | 0.36%   |
| Xicheng District | 6         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 402       | 538    | 16.56%  |
| WDC                         | 299       | 416    | 12.32%  |
| Seagate                     | 259       | 468    | 10.67%  |
| Sandisk                     | 135       | 159    | 5.56%   |
| Toshiba                     | 133       | 193    | 5.48%   |
| Unknown                     | 122       | 160    | 5.03%   |
| SK hynix                    | 78        | 95     | 3.21%   |
| Intel                       | 77        | 119    | 3.17%   |
| Kingston                    | 72        | 89     | 2.97%   |
| HGST                        | 51        | 82     | 2.1%    |
| Micron Technology           | 48        | 53     | 1.98%   |
| Silicon Motion              | 35        | 48     | 1.44%   |
| Plextor                     | 30        | 34     | 1.24%   |
| Unknown                     | 30        | 36     | 1.24%   |
| Hitachi                     | 29        | 43     | 1.19%   |
| Yangtze Memory Technologies | 26        | 32     | 1.07%   |
| Crucial                     | 26        | 31     | 1.07%   |
| KIOXIA                      | 25        | 32     | 1.03%   |
| Lenovo                      | 24        | 34     | 0.99%   |
| Phison                      | 20        | 24     | 0.82%   |
| MAXIO Technology (Hangzhou) | 20        | 23     | 0.82%   |
| ZHITAI                      | 19        | 22     | 0.78%   |
| LITEON                      | 19        | 23     | 0.78%   |
| China                       | 17        | 29     | 0.7%    |
| Hewlett-Packard             | 16        | 20     | 0.66%   |
| A-DATA Technology           | 16        | 21     | 0.66%   |
| FORESEE                     | 15        | 18     | 0.62%   |
| Colorful                    | 14        | 18     | 0.58%   |
| Apple                       | 14        | 14     | 0.58%   |
| Teclast                     | 12        | 12     | 0.49%   |
| Kingston Technology Company | 12        | 15     | 0.49%   |
| JMicron Technology          | 11        | 9      | 0.45%   |
| Phison Electronics          | 10        | 10     | 0.41%   |
| Netac                       | 10        | 11     | 0.41%   |
| KIOXIA-EXCERIA              | 10        | 13     | 0.41%   |
| Hikvision                   | 10        | 17     | 0.41%   |
| GLOWAY                      | 10        | 13     | 0.41%   |
| GALAX                       | 10        | 10     | 0.41%   |
| Fanxiang                    | 9         | 9      | 0.37%   |
| Transcend                   | 7         | 8      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 30        | 1.14%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 26        | 0.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 26        | 0.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 24        | 0.91%   |
| Samsung NVMe SSD Drive 512GB                          | 23        | 0.87%   |
| SanDisk NVMe SSD Drive 512GB                          | 21        | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB                        | 18        | 0.68%   |
| Seagate ST1000DM010-2EP102 1TB                        | 17        | 0.64%   |
| Samsung SSD 860 EVO 500GB                             | 17        | 0.64%   |
| SanDisk NVMe SSD Drive 1TB                            | 16        | 0.61%   |
| HGST HTS721010A9E630 1TB                              | 16        | 0.61%   |
| Seagate ST1000DM003-1SB102 1TB                        | 15        | 0.57%   |
| Samsung MZVLB512HBJQ-000L2 512GB                      | 14        | 0.53%   |
| Seagate ST500LT012-1DG142 500GB                       | 13        | 0.49%   |
| Seagate ST500DM002-1BD142 500GB                       | 13        | 0.49%   |
| Seagate ST1000LM048-2E7172 1TB                        | 13        | 0.49%   |
| Samsung SSD 980 1TB                                   | 13        | 0.49%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 12        | 0.45%   |
| Samsung NVMe SSD Drive 1024GB                         | 12        | 0.45%   |
| Yangtze Memory ZHITAI TiPlus5000 1TB                  | 11        | 0.42%   |
| Unknown MMC Card  64GB                                | 11        | 0.42%   |
| Toshiba MQ01ABD100 1TB                                | 11        | 0.42%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB                | 11        | 0.42%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 11        | 0.42%   |
| WDC WDS100T2B0C-00PXH0 1TB                            | 10        | 0.38%   |
| Toshiba DT01ACA200 2TB                                | 10        | 0.38%   |
| SK hynix NVMe SSD Drive 512GB                         | 10        | 0.38%   |
| Seagate ST500LM021-1KJ152 500GB                       | 10        | 0.38%   |
| Seagate ST2000LM007-1R8174 2TB                        | 10        | 0.38%   |
| Samsung MZVLB512HAJQ-00000 512GB                      | 10        | 0.38%   |
| HGST HTS725050A7E630 500GB                            | 10        | 0.38%   |
| Plextor PX-128M6S 128GB SSD                           | 9         | 0.34%   |
| Kingston SA400S37480G 480GB SSD                       | 9         | 0.34%   |
| WDC WD10EZEX-08M2NA0 1TB                              | 8         | 0.3%    |
| Unknown MMC Card  128GB                               | 8         | 0.3%    |
| Toshiba NVMe SSD Drive 128GB                          | 8         | 0.3%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 8         | 0.3%    |
| Seagate ST6000NM0115-1YZ110 6TB                       | 8         | 0.3%    |
| Samsung MZVLB512HBJQ-000L7 512GB                      | 8         | 0.3%    |
| WDC PC SN730 SDBPNTY-512G-1101 512GB                  | 7         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 257       | 465    | 38.13%  |
| WDC                 | 216       | 300    | 32.05%  |
| Toshiba             | 67        | 110    | 9.94%   |
| HGST                | 51        | 82     | 7.57%   |
| Hitachi             | 29        | 43     | 4.3%    |
| Samsung Electronics | 12        | 13     | 1.78%   |
| JMicron Technology  | 7         | 7      | 1.04%   |
| Fujitsu             | 7         | 7      | 1.04%   |
| Pear 2TB            | 5         | 5      | 0.74%   |
| External            | 5         | 8      | 0.74%   |
| TO Exter            | 2         | 2      | 0.3%    |
| StoreJet            | 2         | 2      | 0.3%    |
| ACASIS              | 2         | 2      | 0.3%    |
| Unknown             | 2         | 3      | 0.3%    |
| SSK                 | 1         | 1      | 0.15%   |
| LIO-ORG             | 1         | 9      | 0.15%   |
| IBM H0              | 1         | 1      | 0.15%   |
| HGST HTS            | 1         | 1      | 0.15%   |
| Hewlett-Packard     | 1         | 1      | 0.15%   |
| GOKE                | 1         | 1      | 0.15%   |
| FORESEE             | 1         | 1      | 0.15%   |
| ExcelStor           | 1         | 1      | 0.15%   |
| DELLBOSS            | 1         | 1      | 0.15%   |
| Apple               | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 124       | 178    | 19.97%  |
| Kingston            | 45        | 56     | 7.25%   |
| SanDisk             | 37        | 40     | 5.96%   |
| Toshiba             | 29        | 36     | 4.67%   |
| Plextor             | 27        | 30     | 4.35%   |
| Intel               | 27        | 43     | 4.35%   |
| WDC                 | 20        | 29     | 3.22%   |
| Crucial             | 19        | 24     | 3.06%   |
| LITEON              | 18        | 22     | 2.9%    |
| Lenovo              | 17        | 22     | 2.74%   |
| China               | 17        | 29     | 2.74%   |
| Micron Technology   | 13        | 15     | 2.09%   |
| A-DATA Technology   | 13        | 17     | 2.09%   |
| Teclast             | 12        | 12     | 1.93%   |
| Unknown             | 11        | 15     | 1.77%   |
| GALAX               | 10        | 10     | 1.61%   |
| Netac               | 9         | 10     | 1.45%   |
| SK hynix            | 8         | 8      | 1.29%   |
| GLOWAY              | 8         | 11     | 1.29%   |
| FORESEE             | 8         | 9      | 1.29%   |
| ZHITAI              | 7         | 8      | 1.13%   |
| Kingchuxing         | 7         | 9      | 1.13%   |
| Colorful            | 7         | 7      | 1.13%   |
| Transcend           | 6         | 7      | 0.97%   |
| Apple               | 6         | 6      | 0.97%   |
| Unknown             | 5         | 6      | 0.81%   |
| Hewlett-Packard     | 5         | 8      | 0.81%   |
| Q200                | 4         | 7      | 0.64%   |
| LITEONIT            | 4         | 4      | 0.64%   |
| tigo                | 3         | 3      | 0.48%   |
| Phison              | 3         | 4      | 0.48%   |
| Pear                | 3         | 12     | 0.48%   |
| Lexar               | 3         | 3      | 0.48%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.48%   |
| KINGBANK            | 3         | 3      | 0.48%   |
| Galaxy              | 3         | 3      | 0.48%   |
| Faspeed             | 3         | 3      | 0.48%   |
| ASMT                | 3         | 6      | 0.48%   |
| Vaseky              | 2         | 2      | 0.32%   |
| UNIC2               | 2         | 2      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 853       | 1219   | 39.62%  |
| HDD     | 580       | 1067   | 26.94%  |
| SSD     | 546       | 824    | 25.36%  |
| MMC     | 108       | 140    | 5.02%   |
| Unknown | 66        | 82     | 3.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 892       | 1826   | 45.42%  |
| NVMe | 851       | 1210   | 43.33%  |
| SAS  | 113       | 156    | 5.75%   |
| MMC  | 108       | 140    | 5.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 603       | 980    | 52.03%  |
| 0.51-1.0   | 363       | 462    | 31.32%  |
| 1.01-2.0   | 89        | 148    | 7.68%   |
| 3.01-4.0   | 32        | 49     | 2.76%   |
| 4.01-10.0  | 32        | 181    | 2.76%   |
| 2.01-3.0   | 23        | 43     | 1.98%   |
| 10.01-20.0 | 17        | 28     | 1.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 404       | 24.34%  |
| 101-250        | 372       | 22.41%  |
| 501-1000       | 247       | 14.88%  |
| 1001-2000      | 143       | 8.61%   |
| 51-100         | 138       | 8.31%   |
| More than 3000 | 98        | 5.9%    |
| 1-20           | 92        | 5.54%   |
| 21-50          | 67        | 4.04%   |
| 2001-3000      | 51        | 3.07%   |
| Unknown        | 48        | 2.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 616       | 36.17%  |
| 21-50          | 278       | 16.32%  |
| 101-250        | 237       | 13.92%  |
| 51-100         | 184       | 10.8%   |
| 251-500        | 147       | 8.63%   |
| 501-1000       | 86        | 5.05%   |
| 1001-2000      | 55        | 3.23%   |
| Unknown        | 48        | 2.82%   |
| More than 3000 | 30        | 1.76%   |
| 2001-3000      | 21        | 1.23%   |
| 0              | 1         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 3         | 3      | 2.97%   |
| HGST HTS725050A7E630 500GB         | 3         | 3      | 2.97%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 2         | 2      | 1.98%   |
| Toshiba MQ04ABF100 1TB             | 2         | 2      | 1.98%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 2      | 1.98%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 2      | 1.98%   |
| Seagate ST31000524AS 1TB           | 2         | 2      | 1.98%   |
| Seagate ST1000LM048-2E7172 1TB     | 2         | 2      | 1.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 1.98%   |
| Hitachi HUS724030ALE641 3TB        | 2         | 2      | 1.98%   |
| HGST HTS721010A9E630 1TB           | 2         | 2      | 1.98%   |
| Crucial CT240M500SSD1 240GB        | 2         | 2      | 1.98%   |
| A-DATA Technology SP900 128GB SSD  | 2         | 3      | 1.98%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1         | 1      | 0.99%   |
| WDC WD5003ABYZ-011FA0 500GB        | 1         | 1      | 0.99%   |
| WDC WD5003ABYX-01WERA1 500GB       | 1         | 1      | 0.99%   |
| WDC WD5000AZLX-60K2TA0 500GB       | 1         | 1      | 0.99%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1         | 1      | 0.99%   |
| WDC WD5000AAKX-08ERMA0 500GB       | 1         | 1      | 0.99%   |
| WDC WD5000AAKX-083CA1 500GB        | 1         | 2      | 0.99%   |
| WDC WD5000AAKX-00PWEA0 500GB       | 1         | 1      | 0.99%   |
| WDC WD5000AAKX-001CA0 500GB        | 1         | 1      | 0.99%   |
| WDC WD5000AAKX-0 500GB             | 1         | 1      | 0.99%   |
| WDC WD40EJRX-89AKWY0 4TB           | 1         | 3      | 0.99%   |
| WDC WD20EARX-00PASB0 2TB           | 1         | 1      | 0.99%   |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 1      | 0.99%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 0.99%   |
| WDC WD10JPLX-00MBPT1 1TB           | 1         | 2      | 0.99%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1         | 1      | 0.99%   |
| WDC WD100EZAZ-11TDBA0 10TB         | 1         | 2      | 0.99%   |
| WDC WD10 JPVX-75JC3T0 1TB          | 1         | 1      | 0.99%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 0.99%   |
| Toshiba MK3259GSXP 320GB           | 1         | 1      | 0.99%   |
| Toshiba MK2555GSX 250GB            | 1         | 1      | 0.99%   |
| Toshiba DT01ACA300 3TB             | 1         | 1      | 0.99%   |
| Toshiba DT01ACA100 1TB             | 1         | 1      | 0.99%   |
| Toshiba DT01ACA050 500GB           | 1         | 1      | 0.99%   |
| Seagate ST980811AS 80GB            | 1         | 1      | 0.99%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 0.99%   |
| Seagate ST750LM028-1KK162 752GB    | 1         | 1      | 0.99%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 26     | 22.22%  |
| WDC                 | 20        | 25     | 20.2%   |
| Toshiba             | 8         | 8      | 8.08%   |
| Hitachi             | 6         | 6      | 6.06%   |
| HGST                | 6         | 6      | 6.06%   |
| Samsung Electronics | 5         | 16     | 5.05%   |
| Intel               | 4         | 4      | 4.04%   |
| GLOWAY              | 3         | 6      | 3.03%   |
| Fujitsu             | 3         | 3      | 3.03%   |
| Crucial             | 3         | 3      | 3.03%   |
| A-DATA Technology   | 3         | 4      | 3.03%   |
| SanDisk             | 2         | 2      | 2.02%   |
| Plextor             | 2         | 2      | 2.02%   |
| Lenovo              | 2         | 2      | 2.02%   |
| Colorful            | 2         | 2      | 2.02%   |
| Ramsta              | 1         | 1      | 1.01%   |
| Netac               | 1         | 1      | 1.01%   |
| Kingston            | 1         | 1      | 1.01%   |
| HS-SSD-C160         | 1         | 1      | 1.01%   |
| Hewlett-Packard     | 1         | 1      | 1.01%   |
| HANCHU              | 1         | 1      | 1.01%   |
| Flashwar            | 1         | 1      | 1.01%   |
| ExcelStor           | 1         | 1      | 1.01%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 22        | 26     | 33.85%  |
| WDC       | 19        | 24     | 29.23%  |
| Toshiba   | 8         | 8      | 12.31%  |
| Hitachi   | 6         | 6      | 9.23%   |
| HGST      | 6         | 6      | 9.23%   |
| Fujitsu   | 3         | 3      | 4.62%   |
| ExcelStor | 1         | 1      | 1.54%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 64        | 74     | 66.67%  |
| SSD  | 27        | 44     | 28.13%  |
| NVMe | 5         | 5      | 5.21%   |

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
| Works    | 845       | 1713   | 48.7%   |
| Detected | 789       | 1485   | 45.48%  |
| Malfunc  | 92        | 123    | 5.3%    |
| Failed   | 9         | 11     | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 881       | 40.75%  |
| Samsung Electronics                     | 281       | 13%     |
| AMD                                     | 237       | 10.96%  |
| SanDisk                                 | 166       | 7.68%   |
| SK hynix                                | 69        | 3.19%   |
| Silicon Motion                          | 54        | 2.5%    |
| Toshiba America Info Systems            | 42        | 1.94%   |
| Yangtze Memory Technologies             | 39        | 1.8%    |
| Kingston Technology Company             | 38        | 1.76%   |
| Phison Electronics                      | 35        | 1.62%   |
| Micron Technology                       | 35        | 1.62%   |
| MAXIO Technology (Hangzhou)             | 35        | 1.62%   |
| KIOXIA                                  | 34        | 1.57%   |
| Marvell Technology Group                | 29        | 1.34%   |
| ASMedia Technology                      | 24        | 1.11%   |
| Broadcom / LSI                          | 17        | 0.79%   |
| Shenzhen Longsys Electronics            | 11        | 0.51%   |
| Micron/Crucial Technology               | 10        | 0.46%   |
| Biwin Storage Technology                | 10        | 0.46%   |
| Zhaoxin                                 | 9         | 0.42%   |
| LSI Logic / Symbios Logic               | 9         | 0.42%   |
| Lite-On Technology                      | 7         | 0.32%   |
| Apple                                   | 7         | 0.32%   |
| Solid State Storage Technology          | 6         | 0.28%   |
| Loongson Technology                     | 6         | 0.28%   |
| JMicron Technology                      | 6         | 0.28%   |
| ADATA Technology                        | 6         | 0.28%   |
| Union Memory (Shenzhen)                 | 5         | 0.23%   |
| INNOGRIT                                | 5         | 0.23%   |
| IBM                                     | 5         | 0.23%   |
| Huawei Technologies                     | 5         | 0.23%   |
| Realtek Semiconductor                   | 4         | 0.19%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.14%   |
| Shenzhen Unionmemory Information System | 3         | 0.14%   |
| O2 Micro                                | 3         | 0.14%   |
| Beijing Starblaze Technology            | 3         | 0.14%   |
| Solidigm                                | 2         | 0.09%   |
| Silicon Image                           | 2         | 0.09%   |
| Seagate Technology                      | 2         | 0.09%   |
| Phytium Technology                      | 2         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 183       | 7.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 137       | 5.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 79        | 3.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 61        | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 58        | 2.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 53        | 2.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 50        | 2.1%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 46        | 1.93%   |
| Intel Volume Management Device NVMe RAID Controller                            | 41        | 1.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 38        | 1.59%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 38        | 1.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 37        | 1.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 35        | 1.47%   |
| AMD 400 Series Chipset SATA Controller                                         | 34        | 1.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 33        | 1.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 32        | 1.34%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 31        | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 31        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 31        | 1.3%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 27        | 1.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 25        | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 24        | 1.01%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 23        | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 0.96%   |
| Intel SATA Controller [RAID mode]                                              | 22        | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 21        | 0.88%   |
| AMD 500 Series Chipset SATA Controller                                         | 20        | 0.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 18        | 0.76%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 18        | 0.76%   |
| Yangtze Memory ZHITAI TiPro5000 NVMe SSD                                       | 17        | 0.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 17        | 0.71%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 17        | 0.71%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 17        | 0.71%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 17        | 0.71%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 16        | 0.67%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                       | 16        | 0.67%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 16        | 0.67%   |
| Intel SSD 660P Series                                                          | 16        | 0.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 16        | 0.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 16        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1026      | 48.37%  |
| NVMe | 856       | 40.36%  |
| RAID | 128       | 6.03%   |
| IDE  | 91        | 4.29%   |
| SAS  | 15        | 0.71%   |
| SCSI | 5         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 1093      | 68.79%  |
| AMD               | 388       | 24.42%  |
| ARM               | 30        | 1.89%   |
| Phytium           | 22        | 1.38%   |
| Unknown           | 16        | 1.01%   |
| CentaurHauls      | 13        | 0.82%   |
| CHRP IBM,8233-E8B | 5         | 0.31%   |
| sifive,u74-mc     | 4         | 0.25%   |
| QUALCOMM          | 4         | 0.25%   |
| sifive,bullet0    | 3         | 0.19%   |
| Loongson          | 3         | 0.19%   |
| CHRP IBM,9131-52A | 2         | 0.13%   |
| thead,c906        | 1         | 0.06%   |
| PowerNV FP5466G2  | 1         | 0.06%   |
| PowerNV C829UAG3  | 1         | 0.06%   |
| HUAWEI            | 1         | 0.06%   |
| HISILICON         | 1         | 0.06%   |
| FSP-1             | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics         | 44        | 2.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 31        | 1.94%   |
| ARM Processor                                  | 24        | 1.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 23        | 1.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz              | 22        | 1.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 21        | 1.32%   |
| Intel 12th Gen Core i7-12700H                  | 20        | 1.25%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 19        | 1.19%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 18        | 1.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 16        | 1%      |
|                                                | 16        | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz              | 15        | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 15        | 0.94%   |
| AMD Ryzen 7 6800H with Radeon Graphics         | 14        | 0.88%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 14        | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 13        | 0.82%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 13        | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 12        | 0.75%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 11        | 0.69%   |
| Intel 12th Gen Core i5-1240P                   | 11        | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 10        | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 10        | 0.63%   |
| AMD Custom APU 0405                            | 10        | 0.63%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 9         | 0.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 9         | 0.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz               | 9         | 0.56%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 9         | 0.56%   |
| Intel Core i5-8300H CPU @ 2.30GHz              | 9         | 0.56%   |
| Intel Celeron N5105 @ 2.00GHz                  | 9         | 0.56%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 9         | 0.56%   |
| Phytium D2000/8 E8C                            | 8         | 0.5%    |
| Intel Core i7-7800X CPU @ 3.50GHz              | 8         | 0.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 8         | 0.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz               | 8         | 0.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz             | 8         | 0.5%    |
| Intel Core i5-6500 CPU @ 3.20GHz               | 8         | 0.5%    |
| Intel Celeron CPU J1900 @ 1.99GHz              | 8         | 0.5%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx  | 8         | 0.5%    |
| Phytium FT-2000/4                              | 7         | 0.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 7         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 297       | 18.68%  |
| Other                   | 293       | 18.43%  |
| Intel Core i7           | 279       | 17.55%  |
| AMD Ryzen 7             | 137       | 8.62%   |
| AMD Ryzen 5             | 101       | 6.35%   |
| Intel Core i3           | 72        | 4.53%   |
| Intel Xeon              | 71        | 4.47%   |
| Intel Celeron           | 60        | 3.77%   |
| AMD Ryzen 9             | 37        | 2.33%   |
| Intel Pentium           | 27        | 1.7%    |
| Intel Atom              | 23        | 1.45%   |
| Intel Core 2 Duo        | 21        | 1.32%   |
| AMD Ryzen 7 PRO         | 19        | 1.19%   |
| Intel Core i9           | 13        | 0.82%   |
| AMD A8                  | 9         | 0.57%   |
| AMD A6                  | 8         | 0.5%    |
| Intel Core m3           | 7         | 0.44%   |
| AMD Ryzen 5 PRO         | 7         | 0.44%   |
| AMD FX                  | 7         | 0.44%   |
| AMD Athlon II X2        | 7         | 0.44%   |
| Intel Xeon Silver       | 6         | 0.38%   |
| Intel Pentium Silver    | 6         | 0.38%   |
| Intel Genuine           | 6         | 0.38%   |
| AMD A10                 | 6         | 0.38%   |
| Intel Xeon Gold         | 5         | 0.31%   |
| AMD Athlon II X4        | 5         | 0.31%   |
| Intel Pentium Dual-Core | 4         | 0.25%   |
| Intel Pentium Dual      | 4         | 0.25%   |
| Intel Core 2            | 4         | 0.25%   |
| AMD EPYC                | 4         | 0.25%   |
| AMD Athlon X4           | 4         | 0.25%   |
| AMD Athlon              | 4         | 0.25%   |
| AMD Ryzen 3             | 3         | 0.19%   |
| AMD E2                  | 3         | 0.19%   |
| AMD E                   | 3         | 0.19%   |
| Intel Xeon Platinum     | 2         | 0.13%   |
| Intel Core M            | 2         | 0.13%   |
| Intel Core 2 Quad       | 2         | 0.13%   |
| ARM BCM                 | 2         | 0.13%   |
| ARM Allwinner           | 2         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 579       | 36.35%  |
| 2       | 367       | 23.04%  |
| 8       | 243       | 15.25%  |
| 6       | 195       | 12.24%  |
| 12      | 44        | 2.76%   |
| 16      | 35        | 2.2%    |
| 14      | 31        | 1.95%   |
| Unknown | 21        | 1.32%   |
| 10      | 19        | 1.19%   |
| 1       | 19        | 1.19%   |
| 24      | 14        | 0.88%   |
| 32      | 5         | 0.31%   |
| 64      | 4         | 0.25%   |
| 20      | 4         | 0.25%   |
| 96      | 2         | 0.13%   |
| 48      | 2         | 0.13%   |
| 40      | 2         | 0.13%   |
| 36      | 2         | 0.13%   |
| 28      | 2         | 0.13%   |
| 26      | 1         | 0.06%   |
| 22      | 1         | 0.06%   |
| 3       | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1508      | 94.84%  |
| 2       | 52        | 3.27%   |
| Unknown | 21        | 1.32%   |
| 3       | 5         | 0.31%   |
| 4       | 2         | 0.13%   |
| 16      | 1         | 0.06%   |
| 6       | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1164      | 73.07%  |
| 1       | 401       | 25.17%  |
| Unknown | 21        | 1.32%   |
| 4       | 6         | 0.38%   |
| 8       | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1528      | 96.04%  |
| Unknown        | 55        | 3.46%   |
| 32-bit         | 5         | 0.31%   |
| 64-bit         | 3         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 511       | 31.39%  |
| 0x906ea    | 61        | 3.75%   |
| 0x306a9    | 55        | 3.38%   |
| 0x306c3    | 50        | 3.07%   |
| 0x0a50000c | 50        | 3.07%   |
| 0x206a7    | 39        | 2.4%    |
| 0x806ec    | 38        | 2.33%   |
| 0x806ea    | 38        | 2.33%   |
| 0x806c1    | 36        | 2.21%   |
| 0x506e3    | 35        | 2.15%   |
| 0x906e9    | 34        | 2.09%   |
| 0x806e9    | 33        | 2.03%   |
| 0x08600106 | 31        | 1.9%    |
| 0x40651    | 26        | 1.6%    |
| 0x906a3    | 23        | 1.41%   |
| 0x0a404102 | 23        | 1.41%   |
| 0x406e3    | 20        | 1.23%   |
| 0x306d4    | 20        | 1.23%   |
| 0x08108102 | 18        | 1.11%   |
| 0x08108109 | 17        | 1.04%   |
| 0x1067a    | 16        | 0.98%   |
| 0x50654    | 15        | 0.92%   |
| 0xa0655    | 14        | 0.86%   |
| 0xa0652    | 14        | 0.86%   |
| 0x30678    | 14        | 0.86%   |
| 0x08600104 | 13        | 0.8%    |
| 0x906c0    | 12        | 0.74%   |
| 0x806d1    | 12        | 0.74%   |
| 0x0a704103 | 11        | 0.68%   |
| 0x0a50000d | 11        | 0.68%   |
| 0x08701013 | 11        | 0.68%   |
| 0x50657    | 10        | 0.61%   |
| 0x306f2    | 10        | 0.61%   |
| 0x90672    | 9         | 0.55%   |
| 0x706e5    | 8         | 0.49%   |
| 0x706a1    | 8         | 0.49%   |
| 0x0a601203 | 8         | 0.49%   |
| 0x08600103 | 8         | 0.49%   |
| 0xa0660    | 7         | 0.43%   |
| 0x306e4    | 7         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 296       | 18.57%  |
| Unknown          | 232       | 14.55%  |
| Haswell          | 128       | 8.03%   |
| Skylake          | 99        | 6.21%   |
| Zen 3            | 93        | 5.83%   |
| Zen 2            | 89        | 5.58%   |
| IvyBridge        | 87        | 5.46%   |
| TigerLake        | 64        | 4.02%   |
| CometLake        | 63        | 3.95%   |
| Alderlake Hybrid | 56        | 3.51%   |
| SandyBridge      | 55        | 3.45%   |
| Zen+             | 44        | 2.76%   |
| Silvermont       | 39        | 2.45%   |
| IceLake          | 33        | 2.07%   |
| Broadwell        | 31        | 1.94%   |
| Penryn           | 28        | 1.76%   |
| Zen              | 22        | 1.38%   |
| K10              | 15        | 0.94%   |
| Goldmont plus    | 14        | 0.88%   |
| Tremont          | 13        | 0.82%   |
| Piledriver       | 13        | 0.82%   |
| Westmere         | 11        | 0.69%   |
| Core             | 11        | 0.69%   |
| Steamroller      | 10        | 0.63%   |
| Goldmont         | 7         | 0.44%   |
| Bonnell          | 6         | 0.38%   |
| Puma             | 5         | 0.31%   |
| Excavator        | 5         | 0.31%   |
| Nehalem          | 4         | 0.25%   |
| Bobcat           | 4         | 0.25%   |
| P6               | 3         | 0.19%   |
| Jaguar           | 3         | 0.19%   |
| Gracemont        | 3         | 0.19%   |
| Sapphire Rapids  | 2         | 0.13%   |
| K10 Llano        | 2         | 0.13%   |
| Bulldozer        | 2         | 0.13%   |
| NetBurst         | 1         | 0.06%   |
| K8 Hammer        | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 863       | 43.92%  |
| Nvidia                           | 547       | 27.84%  |
| AMD                              | 480       | 24.43%  |
| ASPEED Technology                | 24        | 1.22%   |
| Matrox Electronics Systems       | 21        | 1.07%   |
| Zhaoxin                          | 13        | 0.66%   |
| Loongson Technology              | 5         | 0.25%   |
| Phytium Technology               | 3         | 0.15%   |
| Silicon Integrated Systems [SiS] | 2         | 0.1%    |
| Silicon Motion                   | 1         | 0.05%   |
| Nanjing Ruixinview Technology    | 1         | 0.05%   |
| Moore Threads Technology         | 1         | 0.05%   |
| Jingjia Microelectronics         | 1         | 0.05%   |
| Huawei Technologies              | 1         | 0.05%   |
| Cirrus Logic                     | 1         | 0.05%   |
| 3DLabs                           | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 63        | 3.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 63        | 3.14%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 56        | 2.79%   |
| Intel UHD Graphics 620                                                                   | 49        | 2.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 49        | 2.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 44        | 2.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 1.94%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 38        | 1.89%   |
| AMD Rembrandt [Radeon 680M]                                                              | 37        | 1.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 37        | 1.84%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 35        | 1.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 35        | 1.74%   |
| Intel HD Graphics 630                                                                    | 31        | 1.54%   |
| Intel HD Graphics 530                                                                    | 31        | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 1.49%   |
| Intel HD Graphics 620                                                                    | 28        | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 27        | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 1.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 24        | 1.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 1.19%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 24        | 1.19%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 22        | 1.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 1.05%   |
| Nvidia GP108M [GeForce MX250]                                                            | 20        | 1%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 0.95%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 18        | 0.9%    |
| Nvidia GP108M [GeForce MX150]                                                            | 17        | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17        | 0.85%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 17        | 0.85%   |
| Intel JasperLake [UHD Graphics]                                                          | 16        | 0.8%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 15        | 0.75%   |
| Intel HD Graphics 5500                                                                   | 15        | 0.75%   |
| Nvidia TU117M [GeForce MX450]                                                            | 14        | 0.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 0.7%    |
| AMD Phoenix1                                                                             | 14        | 0.7%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 14        | 0.7%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 13        | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 13        | 0.65%   |
| Zhaoxin KX-6000 C-960 GPU                                                                | 12        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 516       | 32.17%  |
| 1 x AMD                           | 339       | 21.13%  |
| Intel + Nvidia                    | 274       | 17.08%  |
| 1 x Nvidia                        | 201       | 12.53%  |
| AMD + Nvidia                      | 58        | 3.62%   |
| Other                             | 50        | 3.12%   |
| Intel + AMD                       | 50        | 3.12%   |
| 2 x AMD                           | 22        | 1.37%   |
| 1 x Matrox                        | 19        | 1.18%   |
| 1 x ASPEED                        | 14        | 0.87%   |
| 1 x Zhaoxin                       | 13        | 0.81%   |
| 2 x Nvidia                        | 7         | 0.44%   |
| 2 x Intel                         | 7         | 0.44%   |
| Nvidia + ASPEED                   | 6         | 0.37%   |
| AMD + Matrox                      | 4         | 0.25%   |
| AMD + ASPEED                      | 4         | 0.25%   |
| 1 x Phytium Technology            | 3         | 0.19%   |
| 1 x Loongson Technology           | 3         | 0.19%   |
| 1 x SiS                           | 2         | 0.12%   |
| AMD + Loongson Technology         | 2         | 0.12%   |
| 1 x Silicon Motion                | 1         | 0.06%   |
| Nvidia + Matrox                   | 1         | 0.06%   |
| Nvidia + Huawei Technologies      | 1         | 0.06%   |
| 1 x Nanjing Ruixinview Technology | 1         | 0.06%   |
| 1 x Moore Threads Technology      | 1         | 0.06%   |
| 1 x Jingjia Microelectronics      | 1         | 0.06%   |
| 1 x Intel + 3 x Nvidia            | 1         | 0.06%   |
| Intel + 2 x Nvidia                | 1         | 0.06%   |
| 1 x Cirrus Logic                  | 1         | 0.06%   |
| AMD + 3DLabs                      | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1145      | 70.99%  |
| Proprietary | 289       | 17.92%  |
| Unknown     | 179       | 11.1%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 929       | 57.13%  |
| 1.01-2.0   | 197       | 12.12%  |
| 0.01-0.5   | 146       | 8.98%   |
| 0.51-1.0   | 116       | 7.13%   |
| 3.01-4.0   | 99        | 6.09%   |
| 5.01-6.0   | 52        | 3.2%    |
| 7.01-8.0   | 49        | 3.01%   |
| 8.01-16.0  | 15        | 0.92%   |
| 2.01-3.0   | 8         | 0.49%   |
| 16.01-24.0 | 7         | 0.43%   |
| 4.01-5.0   | 6         | 0.37%   |
| 24.01-32.0 | 2         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 189       | 12.28%  |
| AU Optronics            | 159       | 10.33%  |
| Dell                    | 127       | 8.25%   |
| Chimei Innolux          | 124       | 8.06%   |
| LG Display              | 121       | 7.86%   |
| AOC                     | 83        | 5.39%   |
| Samsung Electronics     | 78        | 5.07%   |
| Lenovo                  | 78        | 5.07%   |
| CSO                     | 52        | 3.38%   |
| Philips                 | 50        | 3.25%   |
| Sharp                   | 46        | 2.99%   |
| Goldstar                | 30        | 1.95%   |
| Hewlett-Packard         | 28        | 1.82%   |
| ViewSonic               | 23        | 1.49%   |
| PANDA                   | 19        | 1.23%   |
| TMX                     | 18        | 1.17%   |
| BenQ                    | 15        | 0.97%   |
| Apple                   | 15        | 0.97%   |
| InfoVision              | 14        | 0.91%   |
| RTK                     | 13        | 0.84%   |
| HKC                     | 13        | 0.84%   |
| Acer                    | 13        | 0.84%   |
| Xiaomi                  | 12        | 0.78%   |
| Mi                      | 11        | 0.71%   |
| Valve                   | 8         | 0.52%   |
| SGT                     | 8         | 0.52%   |
| IPS                     | 7         | 0.45%   |
| Chi Mei Optoelectronics | 7         | 0.45%   |
| Sony                    | 6         | 0.39%   |
| Unknown                 | 6         | 0.39%   |
| Unknown                 | 5         | 0.32%   |
| Panasonic               | 5         | 0.32%   |
| SKY                     | 4         | 0.26%   |
| Lenovo Group Limited    | 4         | 0.26%   |
| JDI                     | 4         | 0.26%   |
| CHD                     | 4         | 0.26%   |
| ASUSTek Computer        | 4         | 0.26%   |
| Ancor Communications    | 4         | 0.26%   |
| SAC                     | 3         | 0.19%   |
| LGD                     | 3         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch | 15        | 0.95%   |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                | 9         | 0.57%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch          | 9         | 0.57%   |
| Dell P2422H DELA1C5 1920x1080 527x296mm 23.8-inch                | 9         | 0.57%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch            | 9         | 0.57%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch              | 8         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch | 8         | 0.51%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch            | 7         | 0.44%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch            | 7         | 0.44%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch   | 7         | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch   | 7         | 0.44%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                 | 7         | 0.44%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch          | 6         | 0.38%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch          | 6         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch | 6         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch | 6         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch | 6         | 0.38%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch            | 6         | 0.38%   |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch            | 6         | 0.38%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch    | 6         | 0.38%   |
| AOC Q2790 AOC2790 2560x1440 597x336mm 27.0-inch                  | 6         | 0.38%   |
| Unknown                                                          | 6         | 0.38%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch     | 5         | 0.32%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch      | 5         | 0.32%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch            | 5         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 355x199mm 16.0-inch | 5         | 0.32%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch    | 5         | 0.32%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch               | 5         | 0.32%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch          | 4         | 0.25%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch          | 4         | 0.25%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch          | 4         | 0.25%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                 | 4         | 0.25%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch     | 4         | 0.25%   |
| LG Display LCD Monitor LGD0619 1920x1080 309x174mm 14.0-inch     | 4         | 0.25%   |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch     | 4         | 0.25%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch     | 4         | 0.25%   |
| LG Display LCD Monitor LGD02F8 1366x768 310x170mm 13.9-inch      | 4         | 0.25%   |
| Lenovo T24s-28 LEN62C7 1920x1080 527x296mm 23.8-inch             | 4         | 0.25%   |
| Lenovo LEN LI2364 LEN65C7 1920x1080 509x286mm 23.0-inch          | 4         | 0.25%   |
| Lenovo L2250p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch         | 4         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 725       | 48.72%  |
| 1366x768 (WXGA)    | 147       | 9.88%   |
| 3840x2160 (4K)     | 128       | 8.6%    |
| 2560x1440 (QHD)    | 110       | 7.39%   |
| 2560x1600          | 71        | 4.77%   |
| 1440x900 (WXGA+)   | 34        | 2.28%   |
| 1920x1200 (WUXGA)  | 32        | 2.15%   |
| 1600x900 (HD+)     | 22        | 1.48%   |
| 2880x1800          | 21        | 1.41%   |
| 2160x1440          | 19        | 1.28%   |
| 1680x1050 (WSXGA+) | 18        | 1.21%   |
| 1280x1024 (SXGA)   | 18        | 1.21%   |
| 3200x2000          | 13        | 0.87%   |
| Unknown            | 13        | 0.87%   |
| 3440x1440          | 12        | 0.81%   |
| 1280x800 (WXGA)    | 12        | 0.81%   |
| 800x1280           | 10        | 0.67%   |
| 3840x2400          | 6         | 0.4%    |
| 3072x1920          | 6         | 0.4%    |
| 2560x1080          | 6         | 0.4%    |
| 2240x1400          | 6         | 0.4%    |
| 3000x2000          | 4         | 0.27%   |
| 2288x1287          | 4         | 0.27%   |
| 2736x1824          | 3         | 0.2%    |
| 2520x1680          | 3         | 0.2%    |
| 2256x1504          | 3         | 0.2%    |
| 2160x1350          | 3         | 0.2%    |
| 1920x1280          | 3         | 0.2%    |
| 1800x1200          | 3         | 0.2%    |
| 1400x1050          | 3         | 0.2%    |
| 3360x1080          | 2         | 0.13%   |
| 3286x1080          | 2         | 0.13%   |
| 2880x1920          | 2         | 0.13%   |
| 2200x1650          | 2         | 0.13%   |
| 1920x540           | 2         | 0.13%   |
| 1024x768 (XGA)     | 2         | 0.13%   |
| 1024x600           | 2         | 0.13%   |
| 6400x2160          | 1         | 0.07%   |
| 5206x1080          | 1         | 0.07%   |
| 4480x1440          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 273       | 17.74%  |
| 13      | 211       | 13.71%  |
| 14      | 198       | 12.87%  |
| 23      | 132       | 8.58%   |
| 27      | 114       | 7.41%   |
| 24      | 114       | 7.41%   |
| 16      | 77        | 5%      |
| 21      | 70        | 4.55%   |
| Unknown | 52        | 3.38%   |
| 17      | 44        | 2.86%   |
| 12      | 43        | 2.79%   |
| 19      | 28        | 1.82%   |
| 31      | 19        | 1.23%   |
| 22      | 18        | 1.17%   |
| 18      | 17        | 1.1%    |
| 34      | 12        | 0.78%   |
| 65      | 11        | 0.71%   |
| 40      | 11        | 0.71%   |
| 20      | 11        | 0.71%   |
| 25      | 10        | 0.65%   |
| 11      | 10        | 0.65%   |
| 7       | 9         | 0.58%   |
| 10      | 7         | 0.45%   |
| 32      | 6         | 0.39%   |
| 26      | 6         | 0.39%   |
| 63      | 4         | 0.26%   |
| 142     | 3         | 0.19%   |
| 52      | 3         | 0.19%   |
| 43      | 3         | 0.19%   |
| 28      | 3         | 0.19%   |
| 84      | 2         | 0.13%   |
| 72      | 2         | 0.13%   |
| 57      | 2         | 0.13%   |
| 54      | 2         | 0.13%   |
| 36      | 2         | 0.13%   |
| 3       | 2         | 0.13%   |
| 67      | 1         | 0.06%   |
| 55      | 1         | 0.06%   |
| 49      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 619       | 40.72%  |
| 501-600        | 349       | 22.96%  |
| 201-300        | 181       | 11.91%  |
| 401-500        | 134       | 8.82%   |
| 351-400        | 68        | 4.47%   |
| Unknown        | 52        | 3.42%   |
| 601-700        | 35        | 2.3%    |
| 1001-1500      | 23        | 1.51%   |
| 701-800        | 22        | 1.45%   |
| 801-900        | 14        | 0.92%   |
| 1-100          | 10        | 0.66%   |
| 1501-2000      | 4         | 0.26%   |
| 901-1000       | 4         | 0.26%   |
| More than 2000 | 3         | 0.2%    |
| 101-200        | 2         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1024      | 72.99%  |
| 16/10   | 225       | 16.04%  |
| Unknown | 48        | 3.42%   |
| 3/2     | 43        | 3.06%   |
| 5/4     | 19        | 1.35%   |
| 21/9    | 13        | 0.93%   |
| 4/3     | 12        | 0.86%   |
| 0.67    | 8         | 0.57%   |
| 1.00    | 4         | 0.29%   |
| 6/5     | 2         | 0.14%   |
| 0.56    | 2         | 0.14%   |
| 32/9    | 1         | 0.07%   |
| 2.00    | 1         | 0.07%   |
| 0.45    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 312       | 20.37%  |
| 101-110        | 281       | 18.34%  |
| 201-250        | 265       | 17.3%   |
| 301-350        | 120       | 7.83%   |
| 71-80          | 100       | 6.53%   |
| 151-200        | 94        | 6.14%   |
| 111-120        | 64        | 4.18%   |
| Unknown        | 52        | 3.39%   |
| 351-500        | 39        | 2.55%   |
| 61-70          | 35        | 2.28%   |
| 251-300        | 34        | 2.22%   |
| 121-130        | 32        | 2.09%   |
| More than 1000 | 31        | 2.02%   |
| 501-1000       | 20        | 1.31%   |
| 141-150        | 17        | 1.11%   |
| 1-40           | 12        | 0.78%   |
| 51-60          | 9         | 0.59%   |
| 91-100         | 9         | 0.59%   |
| 41-50          | 6         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 449       | 29.75%  |
| 51-100        | 400       | 26.51%  |
| 101-120       | 259       | 17.16%  |
| 161-240       | 250       | 16.57%  |
| More than 240 | 76        | 5.04%   |
| Unknown       | 52        | 3.45%   |
| 1-50          | 23        | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1204      | 74.28%  |
| 0     | 204       | 12.58%  |
| 2     | 202       | 12.46%  |
| 3     | 11        | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 873       | 37.66%  |
| Intel                            | 872       | 37.62%  |
| Qualcomm Atheros                 | 171       | 7.38%   |
| MediaTek                         | 69        | 2.98%   |
| Broadcom                         | 67        | 2.89%   |
| ASIX Electronics                 | 35        | 1.51%   |
| Broadcom Limited                 | 27        | 1.16%   |
| Ralink Technology                | 26        | 1.12%   |
| Huawei Technologies              | 23        | 0.99%   |
| Xiaomi                           | 15        | 0.65%   |
| Qualcomm                         | 14        | 0.6%    |
| Microsoft                        | 11        | 0.47%   |
| Marvell Technology Group         | 10        | 0.43%   |
| TP-Link                          | 6         | 0.26%   |
| Ralink                           | 6         | 0.26%   |
| Quectel Wireless Solutions       | 6         | 0.26%   |
| IBM                              | 6         | 0.26%   |
| Qualcomm Atheros Communications  | 5         | 0.22%   |
| OPPO Electronics                 | 5         | 0.22%   |
| NetGear                          | 5         | 0.22%   |
| Dell                             | 5         | 0.22%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.17%   |
| Tenda                            | 4         | 0.17%   |
| Samsung Electronics              | 4         | 0.17%   |
| Loongson Technology              | 4         | 0.17%   |
| Mellanox Technologies            | 3         | 0.13%   |
| ICS Advent                       | 3         | 0.13%   |
| DisplayLink                      | 3         | 0.13%   |
| D-Link                           | 3         | 0.13%   |
| Aquantia                         | 3         | 0.13%   |
| Wilocity                         | 2         | 0.09%   |
| vivo                             | 2         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.09%   |
| Sierra Wireless                  | 2         | 0.09%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.09%   |
| Oculus VR                        | 2         | 0.09%   |
| Unknown                          | 2         | 0.09%   |
| ST-Ericsson                      | 1         | 0.04%   |
| Shenzhen Goodix Technology       | 1         | 0.04%   |
| Sagem                            | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 549       | 20.41%  |
| Intel Wi-Fi 6 AX200                                                    | 108       | 4.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 65        | 2.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 60        | 2.23%   |
| Realtek RTL8125 2.5GbE Controller                                      | 59        | 2.19%   |
| Intel Wireless 8265 / 8275                                             | 54        | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 53        | 1.97%   |
| Intel Wi-Fi 6 AX201                                                    | 46        | 1.71%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 45        | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 43        | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 35        | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 35        | 1.3%    |
| Intel Wireless 7265                                                    | 34        | 1.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 34        | 1.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 32        | 1.19%   |
| Intel Wireless 7260                                                    | 29        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 29        | 1.08%   |
| Intel I211 Gigabit Network Connection                                  | 28        | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                   | 28        | 1.04%   |
| Intel Ethernet Controller I225-V                                       | 27        | 1%      |
| ASIX AX88179 Gigabit Ethernet                                          | 27        | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 23        | 0.86%   |
| Intel Wireless 8260                                                    | 23        | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 22        | 0.82%   |
| Intel Wireless 3165                                                    | 22        | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 22        | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 21        | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                                  | 21        | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 21        | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 20        | 0.74%   |
| Realtek 802.11ac NIC                                                   | 19        | 0.71%   |
| Ralink MT7601U Wireless Adapter                                        | 18        | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 18        | 0.67%   |
| Intel I350 Gigabit Network Connection                                  | 18        | 0.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 17        | 0.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 17        | 0.63%   |
| Intel I210 Gigabit Network Connection                                  | 17        | 0.63%   |
| Intel Ethernet Connection I217-LM                                      | 16        | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 15        | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 14        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 669       | 52.31%  |
| Realtek Semiconductor           | 248       | 19.39%  |
| Qualcomm Atheros                | 135       | 10.56%  |
| MediaTek                        | 69        | 5.39%   |
| Broadcom                        | 40        | 3.13%   |
| Ralink Technology               | 26        | 2.03%   |
| Broadcom Limited                | 21        | 1.64%   |
| Qualcomm                        | 10        | 0.78%   |
| TP-Link                         | 6         | 0.47%   |
| Ralink                          | 6         | 0.47%   |
| Quectel Wireless Solutions      | 6         | 0.47%   |
| Microsoft                       | 6         | 0.47%   |
| Qualcomm Atheros Communications | 5         | 0.39%   |
| NetGear                         | 5         | 0.39%   |
| Xiaomi                          | 4         | 0.31%   |
| Tenda                           | 4         | 0.31%   |
| Marvell Technology Group        | 4         | 0.31%   |
| D-Link                          | 3         | 0.23%   |
| Wilocity                        | 2         | 0.16%   |
| Sierra Wireless                 | 2         | 0.16%   |
| Dell                            | 2         | 0.16%   |
| Unknown                         | 2         | 0.16%   |
| Sagem                           | 1         | 0.08%   |
| Hewlett-Packard                 | 1         | 0.08%   |
| Fibocom                         | 1         | 0.08%   |
| D-Link System                   | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 108       | 8.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 65        | 5.04%   |
| Intel Wireless 8265 / 8275                                     | 54        | 4.19%   |
| Intel Wi-Fi 6 AX201                                            | 46        | 3.57%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 45        | 3.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 43        | 3.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 35        | 2.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 35        | 2.72%   |
| Intel Wireless 7265                                            | 34        | 2.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 32        | 2.48%   |
| Intel Wireless 7260                                            | 29        | 2.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 29        | 2.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 23        | 1.78%   |
| Intel Wireless 8260                                            | 23        | 1.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 22        | 1.71%   |
| Intel Wireless 3165                                            | 22        | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 22        | 1.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 21        | 1.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 21        | 1.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 20        | 1.55%   |
| Realtek 802.11ac NIC                                           | 19        | 1.47%   |
| Ralink MT7601U Wireless Adapter                                | 18        | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 18        | 1.4%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 17        | 1.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 17        | 1.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 15        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 14        | 1.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 14        | 1.09%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 14        | 1.09%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 13        | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 11        | 0.85%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 10        | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 0.78%   |
| Intel Wireless 3160                                            | 10        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 9         | 0.7%    |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)      | 9         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 9         | 0.7%    |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter             | 9         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 732       | 55.2%   |
| Intel                            | 385       | 29.03%  |
| Qualcomm Atheros                 | 51        | 3.85%   |
| ASIX Electronics                 | 35        | 2.64%   |
| Broadcom                         | 29        | 2.19%   |
| Huawei Technologies              | 18        | 1.36%   |
| Xiaomi                           | 11        | 0.83%   |
| Marvell Technology Group         | 6         | 0.45%   |
| IBM                              | 6         | 0.45%   |
| Broadcom Limited                 | 6         | 0.45%   |
| OPPO Electronics                 | 5         | 0.38%   |
| Samsung Electronics              | 4         | 0.3%    |
| Microsoft                        | 4         | 0.3%    |
| Loongson Technology              | 4         | 0.3%    |
| Qualcomm                         | 3         | 0.23%   |
| Mellanox Technologies            | 3         | 0.23%   |
| ICS Advent                       | 3         | 0.23%   |
| DisplayLink                      | 3         | 0.23%   |
| Dell                             | 3         | 0.23%   |
| Aquantia                         | 3         | 0.23%   |
| Silicon Integrated Systems [SiS] | 2         | 0.15%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.08%   |
| Nvidia                           | 1         | 0.08%   |
| NetXen Incorporated              | 1         | 0.08%   |
| Microchip Technology             | 1         | 0.08%   |
| Lenovo                           | 1         | 0.08%   |
| Google                           | 1         | 0.08%   |
| Attansic Technology              | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |
| American Megatrends              | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 549       | 39.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 60        | 4.34%   |
| Realtek RTL8125 2.5GbE Controller                                      | 59        | 4.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 53        | 3.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 34        | 2.46%   |
| Intel I211 Gigabit Network Connection                                  | 28        | 2.03%   |
| Intel Ethernet Connection (2) I219-V                                   | 28        | 2.03%   |
| Intel Ethernet Controller I225-V                                       | 27        | 1.96%   |
| ASIX AX88179 Gigabit Ethernet                                          | 27        | 1.96%   |
| Intel Ethernet Connection (2) I219-LM                                  | 21        | 1.52%   |
| Intel I350 Gigabit Network Connection                                  | 18        | 1.3%    |
| Intel I210 Gigabit Network Connection                                  | 17        | 1.23%   |
| Intel Ethernet Connection I217-LM                                      | 16        | 1.16%   |
| Intel Ethernet Connection (4) I219-V                                   | 13        | 0.94%   |
| Huawei STG-LX1                                                         | 12        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                                   | 11        | 0.8%    |
| Intel Ethernet Connection (10) I219-V                                  | 11        | 0.8%    |
| Intel Ethernet Connection (16) I219-V                                  | 10        | 0.72%   |
| Intel Ethernet Connection (12) I219-V                                  | 10        | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 9         | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 9         | 0.65%   |
| Intel Ethernet Connection (13) I219-V                                  | 9         | 0.65%   |
| Intel 82567LM Gigabit Network Connection                               | 9         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 8         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                  | 8         | 0.58%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 8         | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 7         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 7         | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                                  | 7         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                   | 7         | 0.51%   |
| Intel 82574L Gigabit Network Connection                                | 7         | 0.51%   |
| ASIX AX88772B                                                          | 7         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 6         | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6         | 0.43%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 0.43%   |
| Intel Ethernet Connection (3) I219-LM                                  | 6         | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 0.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 6         | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 0.36%   |
| Realtek Killer E2600 GbE Controller                                    | 5         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1248      | 50.14%  |
| WiFi     | 1221      | 49.06%  |
| Unknown  | 12        | 0.48%   |
| Modem    | 8         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 903       | 57.88%  |
| Ethernet | 656       | 42.05%  |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 768       | 48.12%  |
| 1     | 655       | 41.04%  |
| 0     | 81        | 5.08%   |
| 3     | 51        | 3.2%    |
| 4     | 25        | 1.57%   |
| 6     | 9         | 0.56%   |
| 8     | 2         | 0.13%   |
| 7     | 2         | 0.13%   |
| 5     | 2         | 0.13%   |
| 42    | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1338      | 82.34%  |
| Yes  | 287       | 17.66%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 598       | 57.28%  |
| Realtek Semiconductor           | 93        | 8.91%   |
| Qualcomm Atheros Communications | 66        | 6.32%   |
| Cambridge Silicon Radio         | 54        | 5.17%   |
| Foxconn / Hon Hai               | 44        | 4.21%   |
| IMC Networks                    | 37        | 3.54%   |
| Realtek                         | 31        | 2.97%   |
| Broadcom                        | 31        | 2.97%   |
| MediaTek                        | 18        | 1.72%   |
| Lite-On Technology              | 14        | 1.34%   |
| Apple                           | 14        | 1.34%   |
| ASUSTek Computer                | 12        | 1.15%   |
| Opticis                         | 6         | 0.57%   |
| Dell                            | 5         | 0.48%   |
| Foxconn International           | 4         | 0.38%   |
| Ralink                          | 3         | 0.29%   |
| Marvell Semiconductor           | 3         | 0.29%   |
| Hewlett-Packard                 | 3         | 0.29%   |
| Toshiba                         | 2         | 0.19%   |
| Taiyo Yuden                     | 2         | 0.19%   |
| Alps Electric                   | 2         | 0.19%   |
| USI                             | 1         | 0.1%    |
| Actions                         | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 175       | 16.76%  |
| Intel AX201 Bluetooth                                 | 130       | 12.45%  |
| Intel AX200 Bluetooth                                 | 100       | 9.58%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 79        | 7.57%   |
| Realtek Bluetooth Radio                               | 69        | 6.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 54        | 5.17%   |
| Intel Bluetooth Device                                | 45        | 4.31%   |
| Qualcomm Atheros  Bluetooth Device                    | 43        | 4.12%   |
| Intel AX210 Bluetooth                                 | 43        | 4.12%   |
| Realtek Bluetooth Radio                               | 31        | 2.97%   |
| Foxconn / Hon Hai Wireless_Device                     | 25        | 2.39%   |
| IMC Networks Bluetooth Radio                          | 20        | 1.92%   |
| MediaTek Wireless_Device                              | 18        | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 13        | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 12        | 1.15%   |
| Foxconn / Hon Hai Bluetooth Device                    | 12        | 1.15%   |
| IMC Networks Wireless_Device                          | 11        | 1.05%   |
| Realtek  Bluetooth 4.2 Adapter                        | 10        | 0.96%   |
| Apple Bluetooth Host Controller                       | 10        | 0.96%   |
| Realtek RTL8723B Bluetooth                            | 8         | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 8         | 0.77%   |
| Lite-On Bluetooth Device                              | 7         | 0.67%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 7         | 0.67%   |
| Broadcom BCM2045B (BDC-2.1)                           | 7         | 0.67%   |
| Opticis Bluetooth Radio                               | 6         | 0.57%   |
| Intel Wireless-AC 3168 Bluetooth                      | 6         | 0.57%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 6         | 0.57%   |
| IMC Networks Bluetooth Device                         | 5         | 0.48%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 5         | 0.48%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 4         | 0.38%   |
| Foxconn International BCM43142A0 Bluetooth module     | 4         | 0.38%   |
| ASUS Bluetooth Radio                                  | 4         | 0.38%   |
| Ralink RT3290 Bluetooth                               | 3         | 0.29%   |
| Marvell Bluetooth and Wireless LAN Composite          | 3         | 0.29%   |
| Foxconn / Hon Hai BCM20702A0                          | 3         | 0.29%   |
| ASUS Qualcomm Bluetooth 4.1                           | 3         | 0.29%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 3         | 0.29%   |
| Apple Bluetooth USB Host Controller                   | 3         | 0.29%   |
| Taiyo Yuden Bluetooth Device                          | 2         | 0.19%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2         | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1026      | 51.27%  |
| AMD                                          | 480       | 23.99%  |
| Nvidia                                       | 360       | 17.99%  |
| C-Media Electronics                          | 16        | 0.8%    |
| Zhaoxin                                      | 13        | 0.65%   |
| Zoran Co. Personal Media Division (Nogatech) | 9         | 0.45%   |
| Realtek Semiconductor                        | 7         | 0.35%   |
| Apple                                        | 7         | 0.35%   |
| Loongson Technology                          | 6         | 0.3%    |
| Creative Labs                                | 6         | 0.3%    |
| XMOS                                         | 5         | 0.25%   |
| Generalplus Technology                       | 5         | 0.25%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.15%   |
| Phytium Technology                           | 3         | 0.15%   |
| Huawei Technologies                          | 3         | 0.15%   |
| BR23                                         | 3         | 0.15%   |
| ASUSTek Computer                             | 3         | 0.15%   |
| Yamaha                                       | 2         | 0.1%    |
| Texas Instruments                            | 2         | 0.1%    |
| Micro Star International                     | 2         | 0.1%    |
| KTMicro                                      | 2         | 0.1%    |
| JMTek                                        | 2         | 0.1%    |
| Giga-Byte Technology                         | 2         | 0.1%    |
| Dell                                         | 2         | 0.1%    |
| Anlya.cn                                     | 2         | 0.1%    |
| VIA Technologies                             | 1         | 0.05%   |
| USB-Speaker                                  | 1         | 0.05%   |
| ULi Electronics                              | 1         | 0.05%   |
| TerraTec Electronic                          | 1         | 0.05%   |
| SteelSeries ApS                              | 1         | 0.05%   |
| Specialix                                    | 1         | 0.05%   |
| SoundPlus Technology                         | 1         | 0.05%   |
| Sony                                         | 1         | 0.05%   |
| Sennheiser Communications                    | 1         | 0.05%   |
| Samsung Electronics                          | 1         | 0.05%   |
| Razer USA                                    | 1         | 0.05%   |
| Polycom                                      | 1         | 0.05%   |
| NXP Semiconductors                           | 1         | 0.05%   |
| Moore Threads Technology                     | 1         | 0.05%   |
| Microsoft                                    | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 258       | 10.66%  |
| Intel Sunrise Point-LP HD Audio                                                   | 122       | 5.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 112       | 4.63%   |
| Intel Cannon Lake PCH cAVS                                                        | 71        | 2.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 70        | 2.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 70        | 2.89%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 64        | 2.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 63        | 2.6%    |
| Intel 200 Series PCH HD Audio                                                     | 58        | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 57        | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 53        | 2.19%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 47        | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 46        | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 44        | 1.82%   |
| Nvidia GA106 High Definition Audio Controller                                     | 40        | 1.65%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 38        | 1.57%   |
| AMD Starship/Matisse HD Audio Controller                                          | 37        | 1.53%   |
| Intel Haswell-ULT HD Audio Controller                                             | 36        | 1.49%   |
| Intel 8 Series HD Audio Controller                                                | 36        | 1.49%   |
| Nvidia Audio device                                                               | 32        | 1.32%   |
| AMD FCH Azalia Controller                                                         | 32        | 1.32%   |
| Nvidia GP106 High Definition Audio Controller                                     | 30        | 1.24%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 30        | 1.24%   |
| Nvidia TU106 High Definition Audio Controller                                     | 29        | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 28        | 1.16%   |
| Intel Comet Lake PCH cAVS                                                         | 28        | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 28        | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 26        | 1.07%   |
| Intel Broadwell-U Audio Controller                                                | 25        | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 24        | 0.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 24        | 0.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 24        | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 22        | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 22        | 0.91%   |
| Nvidia GP104 High Definition Audio Controller                                     | 21        | 0.87%   |
| Intel Comet Lake PCH-V cAVS                                                       | 21        | 0.87%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 20        | 0.83%   |
| Nvidia TU116 High Definition Audio Controller                                     | 19        | 0.78%   |
| Intel Alder Lake-S HD Audio Controller                                            | 19        | 0.78%   |
| Intel CM238 HD Audio Controller                                                   | 17        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 318       | 27.58%  |
| SK hynix                   | 202       | 17.52%  |
| Kingston                   | 169       | 14.66%  |
| Micron Technology          | 138       | 11.97%  |
| Unknown                    | 63        | 5.46%   |
| Crucial                    | 46        | 3.99%   |
| A-DATA Technology          | 31        | 2.69%   |
| Ramaxel Technology         | 25        | 2.17%   |
| Unknown                    | 21        | 1.82%   |
| Corsair                    | 20        | 1.73%   |
| Elpida                     | 8         | 0.69%   |
| KINGBANK                   | 7         | 0.61%   |
| Unknown (ABCD)             | 6         | 0.52%   |
| Transcend                  | 6         | 0.52%   |
| Team                       | 6         | 0.52%   |
| Nanya Technology           | 6         | 0.52%   |
| G.Skill                    | 6         | 0.52%   |
| Lenovo                     | 5         | 0.43%   |
| Juhor                      | 5         | 0.43%   |
| UniIC                      | 4         | 0.35%   |
| Kingmax                    | 4         | 0.35%   |
| Unknown (0x0B92)           | 3         | 0.26%   |
| Shenzhen WODPOSIT          | 3         | 0.26%   |
| Ramsta                     | 3         | 0.26%   |
| Asgard                     | 3         | 0.26%   |
| Apacer                     | 3         | 0.26%   |
| Xi'an UniIC Semiconductors | 2         | 0.17%   |
| Unknown (08C8)             | 2         | 0.17%   |
| Unknown (08B5)             | 2         | 0.17%   |
| tigo                       | 2         | 0.17%   |
| KLEVV                      | 2         | 0.17%   |
| Kimtigo                    | 2         | 0.17%   |
| GLOWAY                     | 2         | 0.17%   |
| Colorful                   | 2         | 0.17%   |
| Unknown (8AF1)             | 1         | 0.09%   |
| Unknown (88BC)             | 1         | 0.09%   |
| UNILC                      | 1         | 0.09%   |
| Thermaltake                | 1         | 0.09%   |
| SK_Hynix                   | 1         | 0.09%   |
| Shenzhen Mic               | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 22        | 1.76%   |
| Unknown                                                             | 21        | 1.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 10        | 0.8%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 10        | 0.8%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 10        | 0.8%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 10        | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 9         | 0.72%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s        | 9         | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 9         | 0.72%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 8         | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 7         | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 7         | 0.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 0.56%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s             | 7         | 0.56%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s              | 7         | 0.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 6         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 6         | 0.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 6         | 0.48%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 6         | 0.48%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 6         | 0.48%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 6         | 0.48%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s             | 6         | 0.48%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s         | 6         | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 6         | 0.48%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                | 6         | 0.48%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 6         | 0.48%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                          | 5         | 0.4%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 5         | 0.4%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 5         | 0.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 5         | 0.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 5         | 0.4%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 5         | 0.4%    |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s         | 5         | 0.4%    |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM DDR5 4800MT/s             | 5         | 0.4%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 5         | 0.4%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 5         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 4         | 0.32%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 4         | 0.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.32%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 561       | 54.73%  |
| DDR3    | 226       | 22.05%  |
| DDR5    | 62        | 6.05%   |
| LPDDR4  | 55        | 5.37%   |
| LPDDR3  | 42        | 4.1%    |
| LPDDR5  | 30        | 2.93%   |
| Unknown | 19        | 1.85%   |
| SDRAM   | 13        | 1.27%   |
| DDR2    | 13        | 1.27%   |
| DRAM    | 2         | 0.2%    |
| DDR     | 2         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 531       | 51.35%  |
| DIMM         | 314       | 30.37%  |
| Row Of Chips | 176       | 17.02%  |
| Chip         | 8         | 0.77%   |
| Unknown      | 4         | 0.39%   |
| RIMM         | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 487       | 44.31%  |
| 16384 | 229       | 20.84%  |
| 4096  | 229       | 20.84%  |
| 32768 | 70        | 6.37%   |
| 2048  | 63        | 5.73%   |
| 1024  | 11        | 1%      |
| 65536 | 5         | 0.45%   |
| 49152 | 2         | 0.18%   |
| 512   | 2         | 0.18%   |
| 16315 | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 218       | 19.96%  |
| 2667    | 180       | 16.48%  |
| 1600    | 166       | 15.2%   |
| 2400    | 71        | 6.5%    |
| 2133    | 67        | 6.14%   |
| 4800    | 53        | 4.85%   |
| 2666    | 33        | 3.02%   |
| 1333    | 33        | 3.02%   |
| 6400    | 32        | 2.93%   |
| 4267    | 30        | 2.75%   |
| 1867    | 23        | 2.11%   |
| 3600    | 18        | 1.65%   |
| 800     | 12        | 1.1%    |
| 3733    | 11        | 1.01%   |
| 1066    | 11        | 1.01%   |
| 4266    | 10        | 0.92%   |
| 1334    | 10        | 0.92%   |
| Unknown | 9         | 0.82%   |
| 1866    | 8         | 0.73%   |
| 3466    | 7         | 0.64%   |
| 3266    | 7         | 0.64%   |
| 2668    | 7         | 0.64%   |
| 1067    | 7         | 0.64%   |
| 667     | 7         | 0.64%   |
| 5600    | 6         | 0.55%   |
| 2933    | 6         | 0.55%   |
| 3000    | 5         | 0.46%   |
| 1800    | 5         | 0.46%   |
| 8400    | 3         | 0.27%   |
| 4199    | 3         | 0.27%   |
| 3400    | 3         | 0.27%   |
| 2048    | 3         | 0.27%   |
| 3933    | 2         | 0.18%   |
| 3500    | 2         | 0.18%   |
| 3066    | 2         | 0.18%   |
| 2448    | 2         | 0.18%   |
| 266     | 2         | 0.18%   |
| 65535   | 1         | 0.09%   |
| 7500    | 1         | 0.09%   |
| 7000    | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Hewlett-Packard                    | 5         | 41.67%  |
| Canon                              | 2         | 16.67%  |
| Brother Industries                 | 2         | 16.67%  |
| Seiko Epson                        | 1         | 8.33%   |
| Pantum                             | 1         | 8.33%   |
| BeiJing LanXum Computer Technology | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                        | 2         | 16.67%  |
| Seiko Epson M105 Series                                 | 1         | 8.33%   |
| Pantum P2200W-series                                    | 1         | 8.33%   |
| HP Officejet 4500 G510g-m                               | 1         | 8.33%   |
| HP LaserJet P1102                                       | 1         | 8.33%   |
| HP DeskJet 2130 series                                  | 1         | 8.33%   |
| Canon PIXMA MP280                                       | 1         | 8.33%   |
| Canon iP1100 series                                     | 1         | 8.33%   |
| Brother HL-L8260CDN series                              | 1         | 8.33%   |
| Brother HL-5440D series                                 | 1         | 8.33%   |
| BeiJing LanXum Technology Black and White Laser Printer | 1         | 8.33%   |

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
| Chicony Electronics                    | 159       | 18.95%  |
| IMC Networks                           | 137       | 16.33%  |
| Realtek Semiconductor                  | 58        | 6.91%   |
| Microdia                               | 57        | 6.79%   |
| Sunplus Innovation Technology          | 49        | 5.84%   |
| Quanta                                 | 48        | 5.72%   |
| Bison Electronics                      | 46        | 5.48%   |
| Acer                                   | 37        | 4.41%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 4.17%   |
| Luxvisions Innotech Limited            | 34        | 4.05%   |
| Syntek                                 | 27        | 3.22%   |
| Lite-On Technology                     | 20        | 2.38%   |
| Suyin                                  | 17        | 2.03%   |
| Apple                                  | 12        | 1.43%   |
| Alcor Micro                            | 11        | 1.31%   |
| Logitech                               | 9         | 1.07%   |
| Silicon Motion                         | 8         | 0.95%   |
| Z-Star Microelectronics                | 7         | 0.83%   |
| SunplusIT                              | 7         | 0.83%   |
| Lenovo                                 | 6         | 0.72%   |
| USB Camera                             | 4         | 0.48%   |
| Sonix Technology                       | 4         | 0.48%   |
| Ricoh                                  | 4         | 0.48%   |
| SN0002                                 | 3         | 0.36%   |
| Importek                               | 3         | 0.36%   |
| GEMBIRD                                | 3         | 0.36%   |
| Unknown (0000066029)                   | 2         | 0.24%   |
| ShineTech                              | 2         | 0.24%   |
| Nebraska Furniture Mart                | 2         | 0.24%   |
| Microsoft                              | 2         | 0.24%   |
| Google                                 | 2         | 0.24%   |
| Genesys Logic                          | 2         | 0.24%   |
| Y Media                                | 1         | 0.12%   |
| Vimicro                                | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |
| Tripath Technology                     | 1         | 0.12%   |
| ShineOptics                            | 1         | 0.12%   |
| Samsung Electronics                    | 1         | 0.12%   |
| Primax Electronics                     | 1         | 0.12%   |
| OPPO Electronics                       | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 70        | 8.26%   |
| IMC Networks Integrated Camera                               | 49        | 5.79%   |
| Microdia Integrated_Webcam_HD                                | 32        | 3.78%   |
| IMC Networks ov9734_azurewave_camera                         | 24        | 2.83%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 23        | 2.72%   |
| Bison Integrated Camera                                      | 22        | 2.6%    |
| Syntek Integrated Camera                                     | 20        | 2.36%   |
| Chicony HD Webcam                                            | 17        | 2.01%   |
| Realtek Integrated_Webcam_HD                                 | 16        | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 14        | 1.65%   |
| IMC Networks HD Camera                                       | 13        | 1.53%   |
| Sunplus Integrated_Webcam_HD                                 | 12        | 1.42%   |
| Sunplus XiaoMi USB 2.0 Webcam                                | 11        | 1.3%    |
| Luxvisions Innotech Limited Integrated Camera                | 10        | 1.18%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                           | 9         | 1.06%   |
| Acer Integrated Camera                                       | 9         | 1.06%   |
| Realtek USB Camera                                           | 8         | 0.94%   |
| Quanta HP HD Camera                                          | 8         | 0.94%   |
| Quanta hm1091_techfront                                      | 8         | 0.94%   |
| Quanta HD User Facing                                        | 8         | 0.94%   |
| Luxvisions Innotech Limited Integrated RGB Camera            | 8         | 0.94%   |
| Acer SunplusIT Integrated Camera                             | 8         | 0.94%   |
| Realtek Integrated Webcam                                    | 7         | 0.83%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 7         | 0.83%   |
| Lite-On Integrated Camera                                    | 7         | 0.83%   |
| Chicony XiaoMi USB 2.0 Webcam                                | 7         | 0.83%   |
| Sunplus HD WebCam                                            | 6         | 0.71%   |
| Quanta ov9734_techfront_camera                               | 6         | 0.71%   |
| Microdia Webcam Vitade AF                                    | 6         | 0.71%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 6         | 0.71%   |
| Bison BisonCam,NB Pro                                        | 6         | 0.71%   |
| Silicon Motion 300k Pixel Camera                             | 5         | 0.59%   |
| Realtek HP Wide Vision HD Camera                             | 5         | 0.59%   |
| Quanta HP Wide Vision HD Camera                              | 5         | 0.59%   |
| Luxvisions Innotech Limited HP 5MP Camera                    | 5         | 0.59%   |
| Lite-On HP Wide Vision HD Camera                             | 5         | 0.59%   |
| Lite-On HP HD Camera                                         | 5         | 0.59%   |
| IMC Networks XHC Camera                                      | 5         | 0.59%   |
| IMC Networks Lenovo EasyCamera                               | 5         | 0.59%   |
| Chicony USB 2.0 Camera                                       | 5         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 75        | 32.61%  |
| Synaptics                          | 66        | 28.7%   |
| Validity Sensors                   | 50        | 21.74%  |
| Elan Microelectronics              | 13        | 5.65%   |
| Upek                               | 10        | 4.35%   |
| AuthenTec                          | 5         | 2.17%   |
| Focal-systems.Corp                 | 4         | 1.74%   |
| LighTuning Technology              | 3         | 1.3%    |
| STMicroelectronics                 | 2         | 0.87%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.43%   |
| FocalTech                          | 1         | 0.43%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 46        | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 11.74%  |
| Shenzhen Goodix Fingerprint Reader                                         | 26        | 11.3%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 6.09%   |
| Elan ELAN:Fingerprint                                                      | 11        | 4.78%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 3.91%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 3.48%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 3.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 3.04%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.61%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.61%   |
| Synaptics WBDI Device                                                      | 5         | 2.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.74%   |
| Synaptics UWP WBDI Device                                                  | 4         | 1.74%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 1.74%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 4         | 1.74%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 1.3%    |
| Validity Sensors VFS491                                                    | 3         | 1.3%    |
| Synaptics WBDI                                                             | 3         | 1.3%    |
| Synaptics UWP WBDI                                                         | 3         | 1.3%    |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.3%    |
| AuthenTec AES2810                                                          | 3         | 1.3%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.87%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.87%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.87%   |
| Unknown                                                                    | 2         | 0.87%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.43%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.43%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.43%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.43%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.43%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.43%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.43%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.43%   |
| FocalTech Fingerprint Device                                               | 1         | 0.43%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.43%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 15        | 62.5%   |
| Upek        | 4         | 16.67%  |
| Clay Logic  | 2         | 8.33%   |
| Alcor Micro | 2         | 8.33%   |
| Yubico.com  | 1         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 6         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 12.5%   |
| Broadcom 58200                                                               | 3         | 12.5%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 8.33%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 974       | 59.64%  |
| 1     | 481       | 29.45%  |
| 2     | 118       | 7.23%   |
| 3     | 28        | 1.71%   |
| 4     | 20        | 1.22%   |
| 5     | 6         | 0.37%   |
| 6     | 3         | 0.18%   |
| 8     | 2         | 0.12%   |
| 10    | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 227       | 25.82%  |
| Graphics card            | 225       | 25.6%   |
| Net/wireless             | 99        | 11.26%  |
| Communication controller | 67        | 7.62%   |
| Multimedia controller    | 53        | 6.03%   |
| Sound                    | 47        | 5.35%   |
| Unassigned class         | 43        | 4.89%   |
| Bluetooth                | 29        | 3.3%    |
| Camera                   | 25        | 2.84%   |
| Chipcard                 | 20        | 2.28%   |
| Net/ethernet             | 12        | 1.37%   |
| Network                  | 9         | 1.02%   |
| Storage/raid             | 7         | 0.8%    |
| Card reader              | 5         | 0.57%   |
| Storage                  | 4         | 0.46%   |
| Storage/nvme             | 2         | 0.23%   |
| Storage/ata              | 2         | 0.23%   |
| Wireless                 | 1         | 0.11%   |
| Modem                    | 1         | 0.11%   |
| Dvb card                 | 1         | 0.11%   |

