OpenMandriva 4.3 - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_4.3/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_4.3/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 4112

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite A305D             | Notebook    | [b85a377462](https://linux-hardware.org/?probe=b85a377462) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | UN45                        | Desktop     | [bde2e2efb1](https://linux-hardware.org/?probe=bde2e2efb1) | Dec 31, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [9126e1035f](https://linux-hardware.org/?probe=9126e1035f) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b0dd8fc6b5](https://linux-hardware.org/?probe=b0dd8fc6b5) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | Notebook    | [f83ed1dd39](https://linux-hardware.org/?probe=f83ed1dd39) | Dec 30, 2022 |
| ASUSTek       | TP501UA                     | Notebook    | [1f2aaf8804](https://linux-hardware.org/?probe=1f2aaf8804) | Dec 30, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [e4c90250df](https://linux-hardware.org/?probe=e4c90250df) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | Notebook    | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b0bfa9530a](https://linux-hardware.org/?probe=b0bfa9530a) | Dec 29, 2022 |
| ASUSTek       | STRIKER II EXTREME          | Desktop     | [3258ffa0c1](https://linux-hardware.org/?probe=3258ffa0c1) | Dec 29, 2022 |
| ASUSTek       | G1                          | Notebook    | [1f8e426f96](https://linux-hardware.org/?probe=1f8e426f96) | Dec 29, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| HP            | Notebook                    | Notebook    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Samsung       | NB30/N146                   | Notebook    | [7f9b976789](https://linux-hardware.org/?probe=7f9b976789) | Dec 29, 2022 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [3f0c89985c](https://linux-hardware.org/?probe=3f0c89985c) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [4734f4370b](https://linux-hardware.org/?probe=4734f4370b) | Dec 28, 2022 |
| Lenovo        | V560                        | Notebook    | [f937de4c61](https://linux-hardware.org/?probe=f937de4c61) | Dec 28, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [92ece593f5](https://linux-hardware.org/?probe=92ece593f5) | Dec 28, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [bd56ec4f01](https://linux-hardware.org/?probe=bd56ec4f01) | Dec 28, 2022 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [879a5b77ff](https://linux-hardware.org/?probe=879a5b77ff) | Dec 28, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [6e1255aa44](https://linux-hardware.org/?probe=6e1255aa44) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| Positivo      | Hendrix                     | Notebook    | [55aa2f92d7](https://linux-hardware.org/?probe=55aa2f92d7) | Dec 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| Pegatron      | APX85-GS                    | Desktop     | [82db9f15c6](https://linux-hardware.org/?probe=82db9f15c6) | Dec 27, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [7a3513a2e1](https://linux-hardware.org/?probe=7a3513a2e1) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Acer          | Aspire TC-865 V:1.1         | Desktop     | [0c8add55fe](https://linux-hardware.org/?probe=0c8add55fe) | Dec 27, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [8ecb7e11b3](https://linux-hardware.org/?probe=8ecb7e11b3) | Dec 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [705baed85a](https://linux-hardware.org/?probe=705baed85a) | Dec 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6703f01cfc](https://linux-hardware.org/?probe=6703f01cfc) | Dec 26, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | Notebook    | [dfb555f802](https://linux-hardware.org/?probe=dfb555f802) | Dec 26, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [14611d6c99](https://linux-hardware.org/?probe=14611d6c99) | Dec 26, 2022 |
| HP            | 2AF7                        | Desktop     | [96344d97ba](https://linux-hardware.org/?probe=96344d97ba) | Dec 26, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [e012bb5bc1](https://linux-hardware.org/?probe=e012bb5bc1) | Dec 25, 2022 |
| ASUSTek       | M51Tr                       | Notebook    | [dffa412a98](https://linux-hardware.org/?probe=dffa412a98) | Dec 25, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [500abd4186](https://linux-hardware.org/?probe=500abd4186) | Dec 25, 2022 |
| ASUSTek       | NARRA3                      | Desktop     | [cc0a64d0df](https://linux-hardware.org/?probe=cc0a64d0df) | Dec 25, 2022 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [4d1a2299dc](https://linux-hardware.org/?probe=4d1a2299dc) | Dec 24, 2022 |
| Dell          | G7 7790                     | Notebook    | [da767d5fd4](https://linux-hardware.org/?probe=da767d5fd4) | Dec 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [8c835888d6](https://linux-hardware.org/?probe=8c835888d6) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [435933801a](https://linux-hardware.org/?probe=435933801a) | Dec 24, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [11eb39826a](https://linux-hardware.org/?probe=11eb39826a) | Dec 24, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [f2e0369ba1](https://linux-hardware.org/?probe=f2e0369ba1) | Dec 24, 2022 |
| Positivo      | Mobile                      | Notebook    | [6031910e64](https://linux-hardware.org/?probe=6031910e64) | Dec 24, 2022 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [f540a3a892](https://linux-hardware.org/?probe=f540a3a892) | Dec 23, 2022 |
| Positivo      | H14BT58                     | Notebook    | [9914219613](https://linux-hardware.org/?probe=9914219613) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [f993ebb9ed](https://linux-hardware.org/?probe=f993ebb9ed) | Dec 23, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [00e62a7231](https://linux-hardware.org/?probe=00e62a7231) | Dec 23, 2022 |
| MSI           | 880GM-E41                   | Desktop     | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [561b98afc3](https://linux-hardware.org/?probe=561b98afc3) | Dec 23, 2022 |
| Dell          | 0JJW8N A03                  | Desktop     | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| ASRock        | FM2A88M-HD+                 | Desktop     | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| Dell          | Latitude 5280               | Notebook    | [59002e923b](https://linux-hardware.org/?probe=59002e923b) | Dec 22, 2022 |
| HP            | Pavilion dv9000 (RR329EA... | Notebook    | [6fc7281f2f](https://linux-hardware.org/?probe=6fc7281f2f) | Dec 22, 2022 |
| ASUSTek       | 1015BXO                     | Notebook    | [7cce9a65ec](https://linux-hardware.org/?probe=7cce9a65ec) | Dec 22, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [8f81c02bbf](https://linux-hardware.org/?probe=8f81c02bbf) | Dec 21, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [003ac98d7f](https://linux-hardware.org/?probe=003ac98d7f) | Dec 21, 2022 |
| PERTOSA       | GA-H110TN-M                 | Desktop     | [048d8cca49](https://linux-hardware.org/?probe=048d8cca49) | Dec 21, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ec2528ae6f](https://linux-hardware.org/?probe=ec2528ae6f) | Dec 20, 2022 |
| Acer          | Aspire 5336                 | Notebook    | [9724b5d705](https://linux-hardware.org/?probe=9724b5d705) | Dec 20, 2022 |
| RM Educati... | RM                          | Notebook    | [758b521362](https://linux-hardware.org/?probe=758b521362) | Dec 20, 2022 |
| Langchao      | NF5110                      | Server      | [3578ca8ceb](https://linux-hardware.org/?probe=3578ca8ceb) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | Notebook    | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| ECS           | G31T-M7                     | Desktop     | [327ac25b68](https://linux-hardware.org/?probe=327ac25b68) | Dec 20, 2022 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [3b9937e6df](https://linux-hardware.org/?probe=3b9937e6df) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| LG Electro... | 17Z90P-G.AA56F              | Notebook    | [fa43417151](https://linux-hardware.org/?probe=fa43417151) | Dec 19, 2022 |
| MSI           | H81M-E34                    | Desktop     | [3aa811568d](https://linux-hardware.org/?probe=3aa811568d) | Dec 19, 2022 |
| Toshiba       | EQUIUM A300D                | Notebook    | [ffde5ccef4](https://linux-hardware.org/?probe=ffde5ccef4) | Dec 19, 2022 |
| ASUSTek       | P5QL PRO                    | Desktop     | [5f3343c803](https://linux-hardware.org/?probe=5f3343c803) | Dec 19, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [d1d5c6a19e](https://linux-hardware.org/?probe=d1d5c6a19e) | Dec 19, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b5c4e6cf61](https://linux-hardware.org/?probe=b5c4e6cf61) | Dec 19, 2022 |
| Dell          | 0M858N A00                  | Desktop     | [e46a95080d](https://linux-hardware.org/?probe=e46a95080d) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [ff287eecab](https://linux-hardware.org/?probe=ff287eecab) | Dec 18, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [71ebf721cc](https://linux-hardware.org/?probe=71ebf721cc) | Dec 17, 2022 |
| HP            | 8055                        | Desktop     | [6c7fa83dc9](https://linux-hardware.org/?probe=6c7fa83dc9) | Dec 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [770c00f7d9](https://linux-hardware.org/?probe=770c00f7d9) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| Dell          | 0RW203                      | Desktop     | [2f5bede488](https://linux-hardware.org/?probe=2f5bede488) | Dec 16, 2022 |
| Lenovo        | Yoga 2-11 20332             | Notebook    | [92a038a164](https://linux-hardware.org/?probe=92a038a164) | Dec 16, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [04cc986bf6](https://linux-hardware.org/?probe=04cc986bf6) | Dec 15, 2022 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [80358a5ba1](https://linux-hardware.org/?probe=80358a5ba1) | Dec 15, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [b2b98c19da](https://linux-hardware.org/?probe=b2b98c19da) | Dec 15, 2022 |
| Acer          | Veriton N2620G              | Desktop     | [a626bf668e](https://linux-hardware.org/?probe=a626bf668e) | Dec 15, 2022 |
| Dell          | 050Nt9 A00                  | All in one  | [075f206957](https://linux-hardware.org/?probe=075f206957) | Dec 15, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [a41e0d92a7](https://linux-hardware.org/?probe=a41e0d92a7) | Dec 15, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [ffe60f958c](https://linux-hardware.org/?probe=ffe60f958c) | Dec 15, 2022 |
| ASUSTek       | K40IJ                       | Notebook    | [191b6ded65](https://linux-hardware.org/?probe=191b6ded65) | Dec 15, 2022 |
| Dell          | 0FR6WH A01                  | Desktop     | [46d6c645fe](https://linux-hardware.org/?probe=46d6c645fe) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| HP            | 2AFB                        | Desktop     | [4c57ea0ee7](https://linux-hardware.org/?probe=4c57ea0ee7) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| Lenovo        | ThinkPad X230 23245QP       | Notebook    | [e525a77c95](https://linux-hardware.org/?probe=e525a77c95) | Dec 15, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [b76fa704f7](https://linux-hardware.org/?probe=b76fa704f7) | Dec 15, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [a9d66f9686](https://linux-hardware.org/?probe=a9d66f9686) | Dec 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [259226594a](https://linux-hardware.org/?probe=259226594a) | Dec 14, 2022 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [d5aa2c3900](https://linux-hardware.org/?probe=d5aa2c3900) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | Desktop     | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [0a564c9f0f](https://linux-hardware.org/?probe=0a564c9f0f) | Dec 14, 2022 |
| Datto         | SSD                         | Desktop     | [a9bff0a51c](https://linux-hardware.org/?probe=a9bff0a51c) | Dec 14, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [373f71370e](https://linux-hardware.org/?probe=373f71370e) | Dec 14, 2022 |
| HP            | 304Ah                       | Desktop     | [d8b600f39e](https://linux-hardware.org/?probe=d8b600f39e) | Dec 13, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| Dell          | Latitude E7250              | Notebook    | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| ASUSTek       | Z10PH-D16 Series            | Desktop     | [18911cf243](https://linux-hardware.org/?probe=18911cf243) | Dec 13, 2022 |
| HP            | Notebook                    | Notebook    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [074195107c](https://linux-hardware.org/?probe=074195107c) | Dec 12, 2022 |
| Gigabyte      | H310M S2V                   | Desktop     | [6895902fe7](https://linux-hardware.org/?probe=6895902fe7) | Dec 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c832b9b688](https://linux-hardware.org/?probe=c832b9b688) | Dec 12, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [ec5acc536f](https://linux-hardware.org/?probe=ec5acc536f) | Dec 12, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [4784b53f14](https://linux-hardware.org/?probe=4784b53f14) | Dec 12, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [62f6fd5f8d](https://linux-hardware.org/?probe=62f6fd5f8d) | Dec 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [9537bff125](https://linux-hardware.org/?probe=9537bff125) | Dec 11, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Dell          | 0KG317                      | Desktop     | [cf7f697a0a](https://linux-hardware.org/?probe=cf7f697a0a) | Dec 11, 2022 |
| HP            | 650                         | Notebook    | [9bb3729969](https://linux-hardware.org/?probe=9bb3729969) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [d7ea1184a2](https://linux-hardware.org/?probe=d7ea1184a2) | Dec 10, 2022 |
| Acer          | Aspire V5-573               | Notebook    | [1d88db5ee2](https://linux-hardware.org/?probe=1d88db5ee2) | Dec 10, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [344383d85d](https://linux-hardware.org/?probe=344383d85d) | Dec 10, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | Desktop     | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| HP            | 18E7                        | Desktop     | [9759493e06](https://linux-hardware.org/?probe=9759493e06) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | Desktop     | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| Positivo      | Mobile                      | Notebook    | [bc5f4e6c85](https://linux-hardware.org/?probe=bc5f4e6c85) | Dec 09, 2022 |
| Acer          | TravelMate 5720             | Notebook    | [d0a54f621e](https://linux-hardware.org/?probe=d0a54f621e) | Dec 09, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [99e671f55f](https://linux-hardware.org/?probe=99e671f55f) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| Dell          | 0P301D A02                  | Desktop     | [8ab7a916f1](https://linux-hardware.org/?probe=8ab7a916f1) | Dec 08, 2022 |
| HP            | 15                          | Notebook    | [20dfd7b8f5](https://linux-hardware.org/?probe=20dfd7b8f5) | Dec 08, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [29337f7359](https://linux-hardware.org/?probe=29337f7359) | Dec 08, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [0203e79add](https://linux-hardware.org/?probe=0203e79add) | Dec 08, 2022 |
| Packard Be... | DOT S                       | Notebook    | [753f17a658](https://linux-hardware.org/?probe=753f17a658) | Dec 08, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | Notebook    | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [469f0a1d1f](https://linux-hardware.org/?probe=469f0a1d1f) | Dec 07, 2022 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [dabda33265](https://linux-hardware.org/?probe=dabda33265) | Dec 07, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [3ab56a93d6](https://linux-hardware.org/?probe=3ab56a93d6) | Dec 07, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [1a35ba24c1](https://linux-hardware.org/?probe=1a35ba24c1) | Dec 07, 2022 |
| ASUSTek       | K53SV                       | Notebook    | [a745b1ead9](https://linux-hardware.org/?probe=a745b1ead9) | Dec 07, 2022 |
| Positivo      | H14BT58                     | Notebook    | [c038df5c8c](https://linux-hardware.org/?probe=c038df5c8c) | Dec 07, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | Desktop     | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [741c3e22b7](https://linux-hardware.org/?probe=741c3e22b7) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b0bc15145c](https://linux-hardware.org/?probe=b0bc15145c) | Dec 06, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [13ca001c57](https://linux-hardware.org/?probe=13ca001c57) | Dec 06, 2022 |
| HP            | 15                          | Notebook    | [e5a0cdc9de](https://linux-hardware.org/?probe=e5a0cdc9de) | Dec 06, 2022 |
| Lenovo        | 0x36A017AA 31900058 STD     | Desktop     | [ccc212b757](https://linux-hardware.org/?probe=ccc212b757) | Dec 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [20786b000c](https://linux-hardware.org/?probe=20786b000c) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [d8a4f4a923](https://linux-hardware.org/?probe=d8a4f4a923) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | Desktop     | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| ECS           | 945P/PL-A                   | Desktop     | [8db8eec28d](https://linux-hardware.org/?probe=8db8eec28d) | Dec 05, 2022 |
| HP            | Pavilion dv6000 (RV009UA... | Notebook    | [6dcd661136](https://linux-hardware.org/?probe=6dcd661136) | Dec 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [fa3aeacc17](https://linux-hardware.org/?probe=fa3aeacc17) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [ee8183087b](https://linux-hardware.org/?probe=ee8183087b) | Dec 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [e98fcde376](https://linux-hardware.org/?probe=e98fcde376) | Dec 04, 2022 |
| Sony          | VPCEL2S1E                   | Notebook    | [0c98b9d570](https://linux-hardware.org/?probe=0c98b9d570) | Dec 04, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [af63449087](https://linux-hardware.org/?probe=af63449087) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | Notebook    | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [fd9114a304](https://linux-hardware.org/?probe=fd9114a304) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | Desktop     | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| Sony          | VGN-NW31JF_S                | Notebook    | [ebfbfb034a](https://linux-hardware.org/?probe=ebfbfb034a) | Dec 04, 2022 |
| ASUSTek       | K42F                        | Notebook    | [05ddce411d](https://linux-hardware.org/?probe=05ddce411d) | Dec 04, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [bfe28498bd](https://linux-hardware.org/?probe=bfe28498bd) | Dec 04, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [1dbda8e648](https://linux-hardware.org/?probe=1dbda8e648) | Dec 04, 2022 |
| Dell          | Latitude E5510              | Notebook    | [6027856ab6](https://linux-hardware.org/?probe=6027856ab6) | Dec 03, 2022 |
| Acer          | Aspire X3950                | Desktop     | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f8f94617e8](https://linux-hardware.org/?probe=f8f94617e8) | Dec 03, 2022 |
| HP            | 8648                        | Desktop     | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [d9bba42204](https://linux-hardware.org/?probe=d9bba42204) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [78f2f440eb](https://linux-hardware.org/?probe=78f2f440eb) | Dec 02, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [8a2aad437e](https://linux-hardware.org/?probe=8a2aad437e) | Dec 02, 2022 |
| Langchao      | NF5110                      | Server      | [ae8b7868da](https://linux-hardware.org/?probe=ae8b7868da) | Dec 02, 2022 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [b566591b3c](https://linux-hardware.org/?probe=b566591b3c) | Dec 02, 2022 |
| Dell          | Latitude E6420              | Notebook    | [011df4cb7f](https://linux-hardware.org/?probe=011df4cb7f) | Dec 02, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | Desktop     | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| Medion        | MS-7748                     | Desktop     | [0e92aa55ca](https://linux-hardware.org/?probe=0e92aa55ca) | Nov 30, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | Desktop     | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| Samsung       | 550XDA                      | Notebook    | [7614fde301](https://linux-hardware.org/?probe=7614fde301) | Nov 30, 2022 |
| Medion        | MS-7800                     | Desktop     | [a5658a6933](https://linux-hardware.org/?probe=a5658a6933) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| Dell          | 0YHMCJ A01                  | Server      | [77f946c99b](https://linux-hardware.org/?probe=77f946c99b) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | Desktop     | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9505f905e8](https://linux-hardware.org/?probe=9505f905e8) | Nov 30, 2022 |
| Dell          | Inspiron 5423               | Notebook    | [db57850733](https://linux-hardware.org/?probe=db57850733) | Nov 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1a742c23df](https://linux-hardware.org/?probe=1a742c23df) | Nov 29, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [fa36933936](https://linux-hardware.org/?probe=fa36933936) | Nov 29, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [f03f3a9325](https://linux-hardware.org/?probe=f03f3a9325) | Nov 29, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [20219ca82a](https://linux-hardware.org/?probe=20219ca82a) | Nov 29, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| ECS           | 945P/PL-A                   | Desktop     | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| Toshiba       | Satellite L875              | Notebook    | [2d5e211d72](https://linux-hardware.org/?probe=2d5e211d72) | Nov 28, 2022 |
| Toshiba       | PORTEGE Z30t-A              | Notebook    | [8af94993bd](https://linux-hardware.org/?probe=8af94993bd) | Nov 28, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [51d2b67ca3](https://linux-hardware.org/?probe=51d2b67ca3) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| Medion        | E11201                      | Notebook    | [0838f9db75](https://linux-hardware.org/?probe=0838f9db75) | Nov 27, 2022 |
| Gateway       | M-1631U                     | Notebook    | [f0f0517dab](https://linux-hardware.org/?probe=f0f0517dab) | Nov 27, 2022 |
| Medion        | E2292                       | Convertible | [98818a6a22](https://linux-hardware.org/?probe=98818a6a22) | Nov 27, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | Desktop     | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| ASRock        | A88M-G                      | Desktop     | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| Lenovo        | 3000 N500 42336DS           | Notebook    | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| MSI           | P55-CD53                    | Desktop     | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [06c7fdf5c9](https://linux-hardware.org/?probe=06c7fdf5c9) | Nov 26, 2022 |
| Dell          | Latitude E6220              | Notebook    | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| HP            | 3397                        | Desktop     | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [d70d7496df](https://linux-hardware.org/?probe=d70d7496df) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| HP            | 0AECh D                     | Desktop     | [857616948b](https://linux-hardware.org/?probe=857616948b) | Nov 26, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [3413fb7947](https://linux-hardware.org/?probe=3413fb7947) | Nov 26, 2022 |
| HP            | 1589                        | Desktop     | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| Acer          | NC-ES1-512-C3AH             | Notebook    | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| HP            | 2215                        | Desktop     | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [9f49ff06cf](https://linux-hardware.org/?probe=9f49ff06cf) | Nov 24, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [418849100f](https://linux-hardware.org/?probe=418849100f) | Nov 24, 2022 |
| HP            | 650                         | Notebook    | [15c69c43ca](https://linux-hardware.org/?probe=15c69c43ca) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [600e3f0f09](https://linux-hardware.org/?probe=600e3f0f09) | Nov 24, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [adcb4db30d](https://linux-hardware.org/?probe=adcb4db30d) | Nov 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [9b50d75b30](https://linux-hardware.org/?probe=9b50d75b30) | Nov 24, 2022 |
| Foxconn       | 2A92                        | Desktop     | [e21715c047](https://linux-hardware.org/?probe=e21715c047) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | Desktop     | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | Desktop     | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | Notebook    | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| HP            | 8582 01100                  | All in one  | [4977f9d91d](https://linux-hardware.org/?probe=4977f9d91d) | Nov 23, 2022 |
| Sony          | VPCEG16EG                   | Notebook    | [ee22559858](https://linux-hardware.org/?probe=ee22559858) | Nov 23, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [ca7e5eab8d](https://linux-hardware.org/?probe=ca7e5eab8d) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| HP            | Notebook                    | Notebook    | [616c071073](https://linux-hardware.org/?probe=616c071073) | Nov 23, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [063ffbb0e8](https://linux-hardware.org/?probe=063ffbb0e8) | Nov 23, 2022 |
| Lenovo        | IdeaPad U310 Touch          | Notebook    | [09beadc5ae](https://linux-hardware.org/?probe=09beadc5ae) | Nov 22, 2022 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [ae2fb8d0b3](https://linux-hardware.org/?probe=ae2fb8d0b3) | Nov 22, 2022 |
| Intel         | powered classmate PC        | Notebook    | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Lenovo        | ThinkPad R500 2716AZJ       | Notebook    | [ecf18761e4](https://linux-hardware.org/?probe=ecf18761e4) | Nov 22, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| HP            | 3399                        | Desktop     | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | Desktop     | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [d8632e2872](https://linux-hardware.org/?probe=d8632e2872) | Nov 21, 2022 |
| ASRock        | P67 Extreme4                | Desktop     | [569fd8178d](https://linux-hardware.org/?probe=569fd8178d) | Nov 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [049f06f11d](https://linux-hardware.org/?probe=049f06f11d) | Nov 21, 2022 |
| AZW           | SEi                         | Desktop     | [a8e813c483](https://linux-hardware.org/?probe=a8e813c483) | Nov 21, 2022 |
| Dell          | 00NNT0 A00                  | Desktop     | [c25787d8b9](https://linux-hardware.org/?probe=c25787d8b9) | Nov 20, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [880e6565e8](https://linux-hardware.org/?probe=880e6565e8) | Nov 20, 2022 |
| Alienware     | M17xR3                      | Notebook    | [d472e55685](https://linux-hardware.org/?probe=d472e55685) | Nov 20, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [eeefed51e4](https://linux-hardware.org/?probe=eeefed51e4) | Nov 20, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [7d3f0e5604](https://linux-hardware.org/?probe=7d3f0e5604) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [5b31194732](https://linux-hardware.org/?probe=5b31194732) | Nov 20, 2022 |
| Chuwi         | LapBook SE                  | Notebook    | [ecc56a3703](https://linux-hardware.org/?probe=ecc56a3703) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Shuttle       | FS61                        | Desktop     | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| Lenovo        | S145-15API 81UT             | Notebook    | [fd832d05e2](https://linux-hardware.org/?probe=fd832d05e2) | Nov 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [fae1d08109](https://linux-hardware.org/?probe=fae1d08109) | Nov 19, 2022 |
| Pegatron      | 2A94h                       | Desktop     | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| HP            | Pavilion dm4                | Notebook    | [d90ac7b5c2](https://linux-hardware.org/?probe=d90ac7b5c2) | Nov 19, 2022 |
| ECS           | G41T-M7                     | Desktop     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Intel         | X99                         | Desktop     | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [04b3ba4242](https://linux-hardware.org/?probe=04b3ba4242) | Nov 18, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fc7b21bd04](https://linux-hardware.org/?probe=fc7b21bd04) | Nov 18, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| HP            | Notebook                    | Notebook    | [ded915d6cd](https://linux-hardware.org/?probe=ded915d6cd) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | Desktop     | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| HP            | Presario CQ43               | Notebook    | [0ed80872c0](https://linux-hardware.org/?probe=0ed80872c0) | Nov 18, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [c27978fdc4](https://linux-hardware.org/?probe=c27978fdc4) | Nov 18, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [05ad62f97d](https://linux-hardware.org/?probe=05ad62f97d) | Nov 17, 2022 |
| Packard Be... | EasyNote TK81               | Notebook    | [c396423368](https://linux-hardware.org/?probe=c396423368) | Nov 17, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [dd25be7aef](https://linux-hardware.org/?probe=dd25be7aef) | Nov 17, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [ba95174feb](https://linux-hardware.org/?probe=ba95174feb) | Nov 17, 2022 |
| Compaq        | 420                         | Notebook    | [07ab1c2b0f](https://linux-hardware.org/?probe=07ab1c2b0f) | Nov 17, 2022 |
| Dell          | 0FDT3J A03                  | Server      | [438f28559c](https://linux-hardware.org/?probe=438f28559c) | Nov 16, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| HP            | 843B                        | Desktop     | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| Intel         | H61                         | Desktop     | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| Medion        | MS-7728                     | Desktop     | [813d86814d](https://linux-hardware.org/?probe=813d86814d) | Nov 16, 2022 |
| MSI           | CR620                       | Notebook    | [4d90de18ca](https://linux-hardware.org/?probe=4d90de18ca) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | Desktop     | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Toshiba       | Satellite Pro U500          | Notebook    | [064a36a5bb](https://linux-hardware.org/?probe=064a36a5bb) | Nov 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [6f3ecf327d](https://linux-hardware.org/?probe=6f3ecf327d) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | Desktop     | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| AZW           | Gemini M                    | Desktop     | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [3f95d3f191](https://linux-hardware.org/?probe=3f95d3f191) | Nov 15, 2022 |
| LDLC          | SPC-N                       | Notebook    | [acec489419](https://linux-hardware.org/?probe=acec489419) | Nov 15, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [ff63827781](https://linux-hardware.org/?probe=ff63827781) | Nov 15, 2022 |
| Dell          | 0UR033 A00                  | Server      | [2ff8924b15](https://linux-hardware.org/?probe=2ff8924b15) | Nov 15, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| ASUSTek       | N751JX                      | Notebook    | [cea52af467](https://linux-hardware.org/?probe=cea52af467) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [298f1bd357](https://linux-hardware.org/?probe=298f1bd357) | Nov 14, 2022 |
| HP            | 22F8                        | Desktop     | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| Lenovo        | G550 20023                  | Notebook    | [80be7e8e25](https://linux-hardware.org/?probe=80be7e8e25) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | Notebook    | [4121297e16](https://linux-hardware.org/?probe=4121297e16) | Nov 14, 2022 |
| Sony          | SVE1411EGXB                 | Notebook    | [dafea482eb](https://linux-hardware.org/?probe=dafea482eb) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [2d904e2be7](https://linux-hardware.org/?probe=2d904e2be7) | Nov 13, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [9506350a75](https://linux-hardware.org/?probe=9506350a75) | Nov 13, 2022 |
| Lenovo        | 0x36C4 SDK0K17763 WIN 18... | All in one  | [7a3f735fc0](https://linux-hardware.org/?probe=7a3f735fc0) | Nov 13, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| HP            | 84FD                        | Desktop     | [6ee4b6828c](https://linux-hardware.org/?probe=6ee4b6828c) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | Desktop     | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| MSI           | H97 GUARD-PRO               | Desktop     | [3ea9d7a74a](https://linux-hardware.org/?probe=3ea9d7a74a) | Nov 13, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [e5a8d4700d](https://linux-hardware.org/?probe=e5a8d4700d) | Nov 12, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [c5952a73e7](https://linux-hardware.org/?probe=c5952a73e7) | Nov 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [f6b2530682](https://linux-hardware.org/?probe=f6b2530682) | Nov 12, 2022 |
| HP            | ProBook 455 G2              | Notebook    | [1a5d0a1618](https://linux-hardware.org/?probe=1a5d0a1618) | Nov 12, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [be3a3b081d](https://linux-hardware.org/?probe=be3a3b081d) | Nov 12, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [d5166a002a](https://linux-hardware.org/?probe=d5166a002a) | Nov 11, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Toshiba       | Satellite C870-D7K          | Notebook    | [b2f60a1b4d](https://linux-hardware.org/?probe=b2f60a1b4d) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [d5e58b3718](https://linux-hardware.org/?probe=d5e58b3718) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| MSI           | U270DX                      | Notebook    | [2a68a6ba02](https://linux-hardware.org/?probe=2a68a6ba02) | Nov 10, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [aa006ea111](https://linux-hardware.org/?probe=aa006ea111) | Nov 10, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [0e624570e1](https://linux-hardware.org/?probe=0e624570e1) | Nov 10, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d43f2e3fc](https://linux-hardware.org/?probe=8d43f2e3fc) | Nov 10, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [5a5633f611](https://linux-hardware.org/?probe=5a5633f611) | Nov 09, 2022 |
| Acer          | RS880M05                    | Desktop     | [cb216f090c](https://linux-hardware.org/?probe=cb216f090c) | Nov 09, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [673c961915](https://linux-hardware.org/?probe=673c961915) | Nov 09, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8383f208a6](https://linux-hardware.org/?probe=8383f208a6) | Nov 09, 2022 |
| Fujitsu       | FMVXN4MN2Z                  | Notebook    | [7a08a94b1e](https://linux-hardware.org/?probe=7a08a94b1e) | Nov 09, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [fb87099a0d](https://linux-hardware.org/?probe=fb87099a0d) | Nov 09, 2022 |
| Dell          | 0V52N7 A02                  | Server      | [3151a21ebf](https://linux-hardware.org/?probe=3151a21ebf) | Nov 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [c46b9195f3](https://linux-hardware.org/?probe=c46b9195f3) | Nov 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [a8e36a1579](https://linux-hardware.org/?probe=a8e36a1579) | Nov 08, 2022 |
| Acer          | Aspire X1700                | Desktop     | [764516b8f0](https://linux-hardware.org/?probe=764516b8f0) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| Dell          | Latitude E6400              | Notebook    | [22ccbac81a](https://linux-hardware.org/?probe=22ccbac81a) | Nov 07, 2022 |
| HP            | Notebook                    | Notebook    | [0164126ac9](https://linux-hardware.org/?probe=0164126ac9) | Nov 07, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [f0b56da15d](https://linux-hardware.org/?probe=f0b56da15d) | Nov 07, 2022 |
| HP            | ProBook 4530s               | Notebook    | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| ASUSTek       | K53E                        | Notebook    | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| HP            | Notebook                    | Notebook    | [59b70f4c7c](https://linux-hardware.org/?probe=59b70f4c7c) | Nov 06, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| Pegatron      | 2AE3                        | Desktop     | [19ae75aacc](https://linux-hardware.org/?probe=19ae75aacc) | Nov 06, 2022 |
| Lenovo        | G485 20136                  | Notebook    | [f8ee5082f8](https://linux-hardware.org/?probe=f8ee5082f8) | Nov 06, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [e1a81edea7](https://linux-hardware.org/?probe=e1a81edea7) | Nov 05, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| Acer          | TravelMate P259-G2-M        | Notebook    | [4a85f586b3](https://linux-hardware.org/?probe=4a85f586b3) | Nov 05, 2022 |
| Acer          | Aspire A717-71G             | Notebook    | [a6fa794196](https://linux-hardware.org/?probe=a6fa794196) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [e2cadc512e](https://linux-hardware.org/?probe=e2cadc512e) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| HP            | 2820h                       | Desktop     | [6378a2e9c3](https://linux-hardware.org/?probe=6378a2e9c3) | Nov 05, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [c125fc089c](https://linux-hardware.org/?probe=c125fc089c) | Nov 05, 2022 |
| VS Company    | MCP61M                      | Desktop     | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| Lenovo        | ThinkPad L520 78596CG       | Notebook    | [094f09bcf8](https://linux-hardware.org/?probe=094f09bcf8) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | Notebook    | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | Notebook    | [010fd86c32](https://linux-hardware.org/?probe=010fd86c32) | Nov 04, 2022 |
| Lenovo        | B50-45 80F0                 | Notebook    | [2d36803ec6](https://linux-hardware.org/?probe=2d36803ec6) | Nov 04, 2022 |
| ASUSTek       | H170I-PLUS D3               | Desktop     | [74df37995c](https://linux-hardware.org/?probe=74df37995c) | Nov 04, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | Notebook    | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [1d618807a7](https://linux-hardware.org/?probe=1d618807a7) | Nov 03, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| Samsung       | 400B2B/400B2B               | Notebook    | [a909b4b203](https://linux-hardware.org/?probe=a909b4b203) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [f9f727f7e5](https://linux-hardware.org/?probe=f9f727f7e5) | Nov 02, 2022 |
| HP            | ENVY m6                     | Notebook    | [9043724da5](https://linux-hardware.org/?probe=9043724da5) | Nov 02, 2022 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [83a1fc191a](https://linux-hardware.org/?probe=83a1fc191a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [0a79270558](https://linux-hardware.org/?probe=0a79270558) | Nov 02, 2022 |
| Panasonic     | CF-C1BWFBZ1M                | Notebook    | [18a81d5db2](https://linux-hardware.org/?probe=18a81d5db2) | Nov 02, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [44f768478e](https://linux-hardware.org/?probe=44f768478e) | Nov 02, 2022 |
| Acer          | Aspire X1430                | Desktop     | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [44c6e56cd9](https://linux-hardware.org/?probe=44c6e56cd9) | Nov 01, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [0470f02ccb](https://linux-hardware.org/?probe=0470f02ccb) | Nov 01, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| ASUSTek       | M4A78 PLUS                  | Desktop     | [bac044cd22](https://linux-hardware.org/?probe=bac044cd22) | Oct 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [8f2639b285](https://linux-hardware.org/?probe=8f2639b285) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | Desktop     | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Prestigio     | PSB133S01ZFP                | Notebook    | [e10becbd35](https://linux-hardware.org/?probe=e10becbd35) | Oct 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [7605a5bf1c](https://linux-hardware.org/?probe=7605a5bf1c) | Oct 30, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [12b6232cdd](https://linux-hardware.org/?probe=12b6232cdd) | Oct 30, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [f8bdcbce4e](https://linux-hardware.org/?probe=f8bdcbce4e) | Oct 29, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| Dell          | Studio 1737                 | Notebook    | [97f398804e](https://linux-hardware.org/?probe=97f398804e) | Oct 29, 2022 |
| HP            | Compaq 615                  | Notebook    | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| MSI           | P45 Platinum                | Desktop     | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [ffb4369f83](https://linux-hardware.org/?probe=ffb4369f83) | Oct 29, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| ASUSTek       | M5A87                       | Desktop     | [88e6b582c9](https://linux-hardware.org/?probe=88e6b582c9) | Oct 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6b57390808](https://linux-hardware.org/?probe=6b57390808) | Oct 28, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [0ca2ea7180](https://linux-hardware.org/?probe=0ca2ea7180) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [ca5c26654a](https://linux-hardware.org/?probe=ca5c26654a) | Oct 27, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [4d5068a3be](https://linux-hardware.org/?probe=4d5068a3be) | Oct 27, 2022 |
| Acer          | Aspire 8730                 | Notebook    | [86bffd9523](https://linux-hardware.org/?probe=86bffd9523) | Oct 27, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [fd34f66305](https://linux-hardware.org/?probe=fd34f66305) | Oct 26, 2022 |
| Acer          | Veriton M275                | Desktop     | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [e2f30e0f1e](https://linux-hardware.org/?probe=e2f30e0f1e) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [fa0daeab26](https://linux-hardware.org/?probe=fa0daeab26) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [2fb43f4be2](https://linux-hardware.org/?probe=2fb43f4be2) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | Desktop     | [218d55e0ca](https://linux-hardware.org/?probe=218d55e0ca) | Oct 25, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | Desktop     | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| Panasonic     | CFSX4-1                     | Notebook    | [2ddae6e0e1](https://linux-hardware.org/?probe=2ddae6e0e1) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bfa28dd791](https://linux-hardware.org/?probe=bfa28dd791) | Oct 24, 2022 |
| Dell          | 0GX297                      | Desktop     | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d6e17c05b2](https://linux-hardware.org/?probe=d6e17c05b2) | Oct 24, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [b7315785a1](https://linux-hardware.org/?probe=b7315785a1) | Oct 24, 2022 |
| ASUSTek       | A7U                         | Notebook    | [867f26dde1](https://linux-hardware.org/?probe=867f26dde1) | Oct 24, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| Acer          | TravelMate B311-31          | Notebook    | [010dd1e876](https://linux-hardware.org/?probe=010dd1e876) | Oct 24, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [683ac39f80](https://linux-hardware.org/?probe=683ac39f80) | Oct 24, 2022 |
| Packard Be... | EasyNote ENTE70BH           | Notebook    | [2135a5aed7](https://linux-hardware.org/?probe=2135a5aed7) | Oct 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| Acer          | WMCP78M                     | Desktop     | [f4e3945dea](https://linux-hardware.org/?probe=f4e3945dea) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| Lenovo        | ThinkPad X240 20AMS01M00    | Notebook    | [2f1c7b7716](https://linux-hardware.org/?probe=2f1c7b7716) | Oct 23, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [12b83ecfd4](https://linux-hardware.org/?probe=12b83ecfd4) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Dell          | 0HX555                      | Desktop     | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Philco        | DTC-A55                     | Desktop     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| Acer          | WG43M                       | Desktop     | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| Dell          | Precision M6800             | Notebook    | [9b909039ee](https://linux-hardware.org/?probe=9b909039ee) | Oct 21, 2022 |
| ZOTAC         | ZBOX-QCM7T3000/EN072080S... | Mini pc     | [612f0f6e06](https://linux-hardware.org/?probe=612f0f6e06) | Oct 21, 2022 |
| MSI           | H61M-P20                    | Desktop     | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| Lenovo        | ThinkPad T520 42434WU       | Notebook    | [d118d39c58](https://linux-hardware.org/?probe=d118d39c58) | Oct 21, 2022 |
| MSI           | GT70 0NC/GT70 0NC           | Notebook    | [592b788d62](https://linux-hardware.org/?probe=592b788d62) | Oct 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [6c32002395](https://linux-hardware.org/?probe=6c32002395) | Oct 20, 2022 |
| Dell          | Latitude E5410              | Notebook    | [f3b5d196ef](https://linux-hardware.org/?probe=f3b5d196ef) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| Sony          | SVE1513B1EW                 | Notebook    | [77ef0b542b](https://linux-hardware.org/?probe=77ef0b542b) | Oct 20, 2022 |
| Dell          | 0V52N7 A01                  | Server      | [c3990d0066](https://linux-hardware.org/?probe=c3990d0066) | Oct 19, 2022 |
| Acer          | Aspire E5-574               | Notebook    | [d9797d9fa7](https://linux-hardware.org/?probe=d9797d9fa7) | Oct 19, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [239627f1d1](https://linux-hardware.org/?probe=239627f1d1) | Oct 19, 2022 |
| HP            | 1825                        | Desktop     | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Samsung       | 550XDA                      | Notebook    | [fcfceeaf04](https://linux-hardware.org/?probe=fcfceeaf04) | Oct 19, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [e14791bb51](https://linux-hardware.org/?probe=e14791bb51) | Oct 19, 2022 |
| HP            | 805D                        | Desktop     | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| MSI           | GE62 6QC                    | Notebook    | [92ac4fbaa6](https://linux-hardware.org/?probe=92ac4fbaa6) | Oct 19, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [770d8bf876](https://linux-hardware.org/?probe=770d8bf876) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| ASUSTek       | P5KPL-E                     | Desktop     | [2f1e1cbbf4](https://linux-hardware.org/?probe=2f1e1cbbf4) | Oct 18, 2022 |
| Lenovo        | G480                        | Notebook    | [984691a38d](https://linux-hardware.org/?probe=984691a38d) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| HP            | Unknown                     | Notebook    | [4a0df43034](https://linux-hardware.org/?probe=4a0df43034) | Oct 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [a1e9be5323](https://linux-hardware.org/?probe=a1e9be5323) | Oct 17, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [29f6ba9612](https://linux-hardware.org/?probe=29f6ba9612) | Oct 17, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [5872b35f8c](https://linux-hardware.org/?probe=5872b35f8c) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [9e37b60507](https://linux-hardware.org/?probe=9e37b60507) | Oct 16, 2022 |
| Dell          | Latitude E6430              | Notebook    | [2e8f3bd664](https://linux-hardware.org/?probe=2e8f3bd664) | Oct 16, 2022 |
| ASRock        | Z87 Pro3                    | Desktop     | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| Dell          | Latitude E6420              | Notebook    | [913e2b1acd](https://linux-hardware.org/?probe=913e2b1acd) | Oct 15, 2022 |
| HP            | 1850                        | Desktop     | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Lenovo        | ThinkPad L560 20F1000TJP    | Notebook    | [e9b7a4ffc2](https://linux-hardware.org/?probe=e9b7a4ffc2) | Oct 15, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [a19fc69283](https://linux-hardware.org/?probe=a19fc69283) | Oct 15, 2022 |
| Intel         | DP45SG AAE27733-403         | Desktop     | [f391a78f4d](https://linux-hardware.org/?probe=f391a78f4d) | Oct 15, 2022 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [a0b3b8e905](https://linux-hardware.org/?probe=a0b3b8e905) | Oct 15, 2022 |
| Dell          | Latitude 3340               | Notebook    | [d99dbe3b99](https://linux-hardware.org/?probe=d99dbe3b99) | Oct 14, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [1feb9942e8](https://linux-hardware.org/?probe=1feb9942e8) | Oct 14, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [e5f4bf84f8](https://linux-hardware.org/?probe=e5f4bf84f8) | Oct 14, 2022 |
| Compaq        | PRESARIOCQ18                | Notebook    | [5172032993](https://linux-hardware.org/?probe=5172032993) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| Dell          | Latitude E5440              | Notebook    | [432aa93109](https://linux-hardware.org/?probe=432aa93109) | Oct 14, 2022 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [a9f67e3f57](https://linux-hardware.org/?probe=a9f67e3f57) | Oct 13, 2022 |
| Dell          | Inspiron 5551               | Notebook    | [64865d9bb5](https://linux-hardware.org/?probe=64865d9bb5) | Oct 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [6144d2247a](https://linux-hardware.org/?probe=6144d2247a) | Oct 13, 2022 |
| Dell          | Precision 7720              | Notebook    | [4cadd86832](https://linux-hardware.org/?probe=4cadd86832) | Oct 13, 2022 |
| Dell          | Studio 1555                 | Notebook    | [52104abe69](https://linux-hardware.org/?probe=52104abe69) | Oct 13, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3a190d5718](https://linux-hardware.org/?probe=3a190d5718) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [bb386c7d60](https://linux-hardware.org/?probe=bb386c7d60) | Oct 13, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [65e0a41b8d](https://linux-hardware.org/?probe=65e0a41b8d) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| HP            | G42                         | Notebook    | [fd42e3aedb](https://linux-hardware.org/?probe=fd42e3aedb) | Oct 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| Star Labs     | StarLite                    | Notebook    | [627ad33197](https://linux-hardware.org/?probe=627ad33197) | Oct 12, 2022 |
| HP            | 1497                        | Desktop     | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| Dell          | Latitude E6440              | Notebook    | [3b13c28e46](https://linux-hardware.org/?probe=3b13c28e46) | Oct 12, 2022 |
| AMD           | A88                         | Desktop     | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | Desktop     | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | Notebook    | [18c02300b9](https://linux-hardware.org/?probe=18c02300b9) | Oct 11, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [1680fa50c0](https://linux-hardware.org/?probe=1680fa50c0) | Oct 11, 2022 |
| HP            | 2171                        | Desktop     | [105af7e899](https://linux-hardware.org/?probe=105af7e899) | Oct 11, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| Lenovo        | ThinkCentre M58 7359WES     | Desktop     | [1c00ee45c1](https://linux-hardware.org/?probe=1c00ee45c1) | Oct 11, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d1b0bd16b5](https://linux-hardware.org/?probe=d1b0bd16b5) | Oct 11, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [92ab2501ea](https://linux-hardware.org/?probe=92ab2501ea) | Oct 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Acer          | Aspire XC-230               | Desktop     | [d213bca85f](https://linux-hardware.org/?probe=d213bca85f) | Oct 10, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [792528e3b2](https://linux-hardware.org/?probe=792528e3b2) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | Desktop     | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| HP            | 829E                        | Mini pc     | [465ec7a2fe](https://linux-hardware.org/?probe=465ec7a2fe) | Oct 10, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [a219433035](https://linux-hardware.org/?probe=a219433035) | Oct 10, 2022 |
| AZW           | U59                         | Desktop     | [8300f61a93](https://linux-hardware.org/?probe=8300f61a93) | Oct 10, 2022 |
| HP            | 805D                        | Desktop     | [8938f51322](https://linux-hardware.org/?probe=8938f51322) | Oct 09, 2022 |
| Lenovo        | Dory CRB                    | Desktop     | [33ae78632a](https://linux-hardware.org/?probe=33ae78632a) | Oct 09, 2022 |
| Dell          | Latitude E6410              | Notebook    | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3e7ef86329](https://linux-hardware.org/?probe=3e7ef86329) | Oct 09, 2022 |
| ASUSTek       | X550VB                      | Notebook    | [a7c1c1cb1b](https://linux-hardware.org/?probe=a7c1c1cb1b) | Oct 09, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d58156239](https://linux-hardware.org/?probe=8d58156239) | Oct 09, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [8918b1b82e](https://linux-hardware.org/?probe=8918b1b82e) | Oct 09, 2022 |
| Chuwi         | RZBOX                       | Desktop     | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| MSI           | A55M-P33                    | Desktop     | [127b8f180e](https://linux-hardware.org/?probe=127b8f180e) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3665682cc6](https://linux-hardware.org/?probe=3665682cc6) | Oct 08, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9d44a35e48](https://linux-hardware.org/?probe=9d44a35e48) | Oct 08, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [e40ba3988f](https://linux-hardware.org/?probe=e40ba3988f) | Oct 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [feb96964b1](https://linux-hardware.org/?probe=feb96964b1) | Oct 08, 2022 |
| Dell          | 0MN1TX A01                  | Desktop     | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [3e7cc2c14a](https://linux-hardware.org/?probe=3e7cc2c14a) | Oct 07, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [b699753cc6](https://linux-hardware.org/?probe=b699753cc6) | Oct 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [509deb10b3](https://linux-hardware.org/?probe=509deb10b3) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| Toshiba       | Satellite R830              | Notebook    | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [7a7bc387f4](https://linux-hardware.org/?probe=7a7bc387f4) | Oct 06, 2022 |
| Medion        | MS-7797                     | Desktop     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | Desktop     | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| HP            | 18E4                        | Desktop     | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| Positivo      | C14CR01                     | Notebook    | [7c0d0b2efd](https://linux-hardware.org/?probe=7c0d0b2efd) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f9224c972e](https://linux-hardware.org/?probe=f9224c972e) | Oct 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f7626421b2](https://linux-hardware.org/?probe=f7626421b2) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [8a18115a5b](https://linux-hardware.org/?probe=8a18115a5b) | Oct 04, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [612b4b36a1](https://linux-hardware.org/?probe=612b4b36a1) | Oct 04, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [65103a04c3](https://linux-hardware.org/?probe=65103a04c3) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b8ad7a8464](https://linux-hardware.org/?probe=b8ad7a8464) | Oct 04, 2022 |
| Dell          | Latitude 3120               | Convertible | [60de9a1977](https://linux-hardware.org/?probe=60de9a1977) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5e60e8faae](https://linux-hardware.org/?probe=5e60e8faae) | Oct 04, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Intel         | H55                         | Desktop     | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [cc0d33aedb](https://linux-hardware.org/?probe=cc0d33aedb) | Oct 03, 2022 |
| Acer          | TravelMate 5744             | Notebook    | [4817d4810d](https://linux-hardware.org/?probe=4817d4810d) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [36b32fe8c0](https://linux-hardware.org/?probe=36b32fe8c0) | Oct 03, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [c6e6708366](https://linux-hardware.org/?probe=c6e6708366) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M58p 6234FB9    | Desktop     | [3c772e3e1d](https://linux-hardware.org/?probe=3c772e3e1d) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [47a7282318](https://linux-hardware.org/?probe=47a7282318) | Oct 02, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [43694e5952](https://linux-hardware.org/?probe=43694e5952) | Oct 02, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [bfd8dc3c18](https://linux-hardware.org/?probe=bfd8dc3c18) | Oct 02, 2022 |
| MSI           | A75A-G35                    | Desktop     | [66b1d71092](https://linux-hardware.org/?probe=66b1d71092) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| Biostar       | A75MG                       | Desktop     | [ba1785b4b6](https://linux-hardware.org/?probe=ba1785b4b6) | Oct 02, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | Desktop     | [ce1567bb35](https://linux-hardware.org/?probe=ce1567bb35) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| MSI           | MS-7235                     | Desktop     | [838e2c27f1](https://linux-hardware.org/?probe=838e2c27f1) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | Notebook    | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [68b0c0ca1a](https://linux-hardware.org/?probe=68b0c0ca1a) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [982b143d73](https://linux-hardware.org/?probe=982b143d73) | Oct 01, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [d967f57569](https://linux-hardware.org/?probe=d967f57569) | Oct 01, 2022 |
| ASUSTek       | M5A87                       | Desktop     | [89ca067566](https://linux-hardware.org/?probe=89ca067566) | Oct 01, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [8c24fa2271](https://linux-hardware.org/?probe=8c24fa2271) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [646f4ffa8e](https://linux-hardware.org/?probe=646f4ffa8e) | Oct 01, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [75b0aa3c75](https://linux-hardware.org/?probe=75b0aa3c75) | Sep 30, 2022 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [a6b14fdcf3](https://linux-hardware.org/?probe=a6b14fdcf3) | Sep 30, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| Acer          | Batman A01                  | Desktop     | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [cfe1aba7e6](https://linux-hardware.org/?probe=cfe1aba7e6) | Sep 30, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [66877298d4](https://linux-hardware.org/?probe=66877298d4) | Sep 30, 2022 |
| Dell          | Latitude E6520              | Notebook    | [04817b4ceb](https://linux-hardware.org/?probe=04817b4ceb) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [11e4602764](https://linux-hardware.org/?probe=11e4602764) | Sep 30, 2022 |
| Dell          | Latitude 3310               | Notebook    | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| Toshiba       | Satellite L505              | Notebook    | [3e91e2bfaf](https://linux-hardware.org/?probe=3e91e2bfaf) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
| HP            | Compaq 6720s                | Notebook    | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [88d57c6319](https://linux-hardware.org/?probe=88d57c6319) | Sep 29, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Corei... | Desktop     | [a40d59533c](https://linux-hardware.org/?probe=a40d59533c) | Sep 29, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [9414d73ae0](https://linux-hardware.org/?probe=9414d73ae0) | Sep 29, 2022 |
| Acer          | Veriton M275                | Desktop     | [f871926a8e](https://linux-hardware.org/?probe=f871926a8e) | Sep 29, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [5a7ad7dba9](https://linux-hardware.org/?probe=5a7ad7dba9) | Sep 28, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6f1ecca2f0](https://linux-hardware.org/?probe=6f1ecca2f0) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| Dell          | Latitude 3310               | Notebook    | [c21a321dce](https://linux-hardware.org/?probe=c21a321dce) | Sep 28, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [2e9902fee0](https://linux-hardware.org/?probe=2e9902fee0) | Sep 28, 2022 |
| Dell          | Vostro 5391                 | Notebook    | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [932a938506](https://linux-hardware.org/?probe=932a938506) | Sep 28, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [c3041b210f](https://linux-hardware.org/?probe=c3041b210f) | Sep 28, 2022 |
| Sony          | VPCEH1S1R                   | Notebook    | [5214bb023f](https://linux-hardware.org/?probe=5214bb023f) | Sep 27, 2022 |
| Dell          | Latitude 3300               | Notebook    | [365349d964](https://linux-hardware.org/?probe=365349d964) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [af23e43e99](https://linux-hardware.org/?probe=af23e43e99) | Sep 27, 2022 |
| Dell          | Latitude 3310               | Notebook    | [313ab64584](https://linux-hardware.org/?probe=313ab64584) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [d46d96565b](https://linux-hardware.org/?probe=d46d96565b) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f5f99a7234](https://linux-hardware.org/?probe=f5f99a7234) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7cea84adb2](https://linux-hardware.org/?probe=7cea84adb2) | Sep 27, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [a33ab40c8b](https://linux-hardware.org/?probe=a33ab40c8b) | Sep 27, 2022 |
| Dell          | Latitude 3120               | Convertible | [bc34bf4d73](https://linux-hardware.org/?probe=bc34bf4d73) | Sep 27, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [3bafc34ffc](https://linux-hardware.org/?probe=3bafc34ffc) | Sep 27, 2022 |
| Packard Be... | EasyNote LS44SB             | Notebook    | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [56ac60a3dc](https://linux-hardware.org/?probe=56ac60a3dc) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [898f9bf963](https://linux-hardware.org/?probe=898f9bf963) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [8736347f60](https://linux-hardware.org/?probe=8736347f60) | Sep 26, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ee7c1fce66](https://linux-hardware.org/?probe=ee7c1fce66) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9d1392e945](https://linux-hardware.org/?probe=9d1392e945) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0f1fb4687f](https://linux-hardware.org/?probe=0f1fb4687f) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [6ce0a09785](https://linux-hardware.org/?probe=6ce0a09785) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [a6ce17cd6b](https://linux-hardware.org/?probe=a6ce17cd6b) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [87af9a8980](https://linux-hardware.org/?probe=87af9a8980) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [9458cffde8](https://linux-hardware.org/?probe=9458cffde8) | Sep 26, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8749a17d26](https://linux-hardware.org/?probe=8749a17d26) | Sep 25, 2022 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [a7aadaeed0](https://linux-hardware.org/?probe=a7aadaeed0) | Sep 25, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [41db205ec7](https://linux-hardware.org/?probe=41db205ec7) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | Notebook    | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| ASUSTek       | CM1740                      | Desktop     | [6ebc913933](https://linux-hardware.org/?probe=6ebc913933) | Sep 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [6c6ae30eba](https://linux-hardware.org/?probe=6c6ae30eba) | Sep 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [02925c7220](https://linux-hardware.org/?probe=02925c7220) | Sep 24, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [c354f2b293](https://linux-hardware.org/?probe=c354f2b293) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| Dell          | 0PTTT9 A00                  | Desktop     | [21bde061e9](https://linux-hardware.org/?probe=21bde061e9) | Sep 23, 2022 |
| Dell          | Latitude 3120               | Convertible | [5281ee08e1](https://linux-hardware.org/?probe=5281ee08e1) | Sep 23, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4c5dc33267](https://linux-hardware.org/?probe=4c5dc33267) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9c4d48864b](https://linux-hardware.org/?probe=9c4d48864b) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | Desktop     | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [443df1ca5c](https://linux-hardware.org/?probe=443df1ca5c) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [061ef6f153](https://linux-hardware.org/?probe=061ef6f153) | Sep 23, 2022 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [a99682c38d](https://linux-hardware.org/?probe=a99682c38d) | Sep 23, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [2b37d81d4c](https://linux-hardware.org/?probe=2b37d81d4c) | Sep 22, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [2527dc6ea0](https://linux-hardware.org/?probe=2527dc6ea0) | Sep 22, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [9b451feb14](https://linux-hardware.org/?probe=9b451feb14) | Sep 22, 2022 |
| HP            | Compaq 15                   | Notebook    | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Lenovo        | ThinkPad X200s 7470WWD      | Notebook    | [268aa65de3](https://linux-hardware.org/?probe=268aa65de3) | Sep 22, 2022 |
| ASUSTek       | K70AD                       | Notebook    | [49dff3ffb5](https://linux-hardware.org/?probe=49dff3ffb5) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | Notebook    | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [989f23b214](https://linux-hardware.org/?probe=989f23b214) | Sep 21, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| HP            | 1998                        | Desktop     | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| Dell          | G5 5505                     | Notebook    | [82017aa2ae](https://linux-hardware.org/?probe=82017aa2ae) | Sep 21, 2022 |
| MACHINIST     | B75 PRO V1.0                | Desktop     | [752cb8efae](https://linux-hardware.org/?probe=752cb8efae) | Sep 21, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [dd730980b1](https://linux-hardware.org/?probe=dd730980b1) | Sep 20, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a82f4ceccc](https://linux-hardware.org/?probe=a82f4ceccc) | Sep 20, 2022 |
| Lenovo        | 3728 SDK0R32862 WIN 3258... | Desktop     | [d78d85bde3](https://linux-hardware.org/?probe=d78d85bde3) | Sep 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8003baae8c](https://linux-hardware.org/?probe=8003baae8c) | Sep 19, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [a2d230d217](https://linux-hardware.org/?probe=a2d230d217) | Sep 19, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [33e582251a](https://linux-hardware.org/?probe=33e582251a) | Sep 19, 2022 |
| Lenovo        | G50-80 80R0                 | Notebook    | [f04ed15344](https://linux-hardware.org/?probe=f04ed15344) | Sep 19, 2022 |
| Samsung       | R530/R730                   | Notebook    | [0d4e13e70f](https://linux-hardware.org/?probe=0d4e13e70f) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0e1784b38d](https://linux-hardware.org/?probe=0e1784b38d) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [983266d6ba](https://linux-hardware.org/?probe=983266d6ba) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [374de3c13c](https://linux-hardware.org/?probe=374de3c13c) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [bc2dd8505b](https://linux-hardware.org/?probe=bc2dd8505b) | Sep 19, 2022 |
| HP            | 2B34                        | Desktop     | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [55332651e0](https://linux-hardware.org/?probe=55332651e0) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [e6b9b405e8](https://linux-hardware.org/?probe=e6b9b405e8) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [448ba707f6](https://linux-hardware.org/?probe=448ba707f6) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Notebook    | [558e95141d](https://linux-hardware.org/?probe=558e95141d) | Sep 19, 2022 |
| Dell          | Latitude 3300               | Notebook    | [a2513a9849](https://linux-hardware.org/?probe=a2513a9849) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [892c3fb361](https://linux-hardware.org/?probe=892c3fb361) | Sep 18, 2022 |
| NEC Comput... | PC-VK26MXZCE                | Notebook    | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| HP            | 2B29                        | Desktop     | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| HP            | 843F                        | Desktop     | [7694ed2ffa](https://linux-hardware.org/?probe=7694ed2ffa) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [65c4f113d8](https://linux-hardware.org/?probe=65c4f113d8) | Sep 18, 2022 |
| HP            | ProBook 6470b               | Notebook    | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| Acer          | Switch SA5-271P             | Tablet      | [c9900a8e2f](https://linux-hardware.org/?probe=c9900a8e2f) | Sep 17, 2022 |
| HP            | Notebook                    | Notebook    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | ThinkPad E570 20H5009NUS    | Notebook    | [c64258edc0](https://linux-hardware.org/?probe=c64258edc0) | Sep 17, 2022 |
| Toshiba       | TECRA S10                   | Notebook    | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| Toshiba       | Satellite P845T             | Notebook    | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [f75308c465](https://linux-hardware.org/?probe=f75308c465) | Sep 17, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [19d0260ef6](https://linux-hardware.org/?probe=19d0260ef6) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | Notebook    | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e472e7fdde](https://linux-hardware.org/?probe=e472e7fdde) | Sep 16, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [1ccce4a76a](https://linux-hardware.org/?probe=1ccce4a76a) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e04ec1834f](https://linux-hardware.org/?probe=e04ec1834f) | Sep 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | Notebook    | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| HP            | 1495                        | Desktop     | [462389df36](https://linux-hardware.org/?probe=462389df36) | Sep 14, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [832824de54](https://linux-hardware.org/?probe=832824de54) | Sep 14, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [6ee9d3e2c4](https://linux-hardware.org/?probe=6ee9d3e2c4) | Sep 14, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Timi          | TM1612                      | Notebook    | [536fc04dcb](https://linux-hardware.org/?probe=536fc04dcb) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Lenovo        | ThinkPad X230 2324GA1       | Notebook    | [c4e6cc1489](https://linux-hardware.org/?probe=c4e6cc1489) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | Notebook    | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| HP            | Notebook                    | Notebook    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| Dell          | Latitude 3120               | Convertible | [a8315e1147](https://linux-hardware.org/?probe=a8315e1147) | Sep 13, 2022 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [ea845ec5ea](https://linux-hardware.org/?probe=ea845ec5ea) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | Notebook    | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| MSI           | Z97 MPOWER                  | Desktop     | [a98aedda05](https://linux-hardware.org/?probe=a98aedda05) | Sep 13, 2022 |
| Compal        | NCL60/61                    | Notebook    | [f1f5499af8](https://linux-hardware.org/?probe=f1f5499af8) | Sep 12, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [0937dcb89c](https://linux-hardware.org/?probe=0937dcb89c) | Sep 12, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [2eb979e980](https://linux-hardware.org/?probe=2eb979e980) | Sep 12, 2022 |
| Toshiba       | Satellite C655              | Notebook    | [16a4aa3cd8](https://linux-hardware.org/?probe=16a4aa3cd8) | Sep 12, 2022 |
| Dell          | 0H8052                      | Desktop     | [1ade497706](https://linux-hardware.org/?probe=1ade497706) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| Shuttle       | XH310V2                     | Desktop     | [c99efae947](https://linux-hardware.org/?probe=c99efae947) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| HP            | 158B                        | Desktop     | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [58b48039ce](https://linux-hardware.org/?probe=58b48039ce) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| HP            | 304Bh                       | Desktop     | [0a7bcbdd9e](https://linux-hardware.org/?probe=0a7bcbdd9e) | Sep 11, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [5d0092ffc1](https://linux-hardware.org/?probe=5d0092ffc1) | Sep 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| MSI           | B560M PRO                   | Desktop     | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| HP            | Notebook                    | Notebook    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| MSI           | 0A48                        | Desktop     | [2619140b48](https://linux-hardware.org/?probe=2619140b48) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b5842ca017](https://linux-hardware.org/?probe=b5842ca017) | Sep 10, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [021bcda428](https://linux-hardware.org/?probe=021bcda428) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | Notebook    | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| LG Electro... | U560-G.BG31P1               | Notebook    | [741c3eddbe](https://linux-hardware.org/?probe=741c3eddbe) | Sep 10, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [40c43aff10](https://linux-hardware.org/?probe=40c43aff10) | Sep 10, 2022 |
| Samsung       | SX60P                       | Notebook    | [1e0ea8e787](https://linux-hardware.org/?probe=1e0ea8e787) | Sep 09, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [cd84312899](https://linux-hardware.org/?probe=cd84312899) | Sep 09, 2022 |
| Dell          | 04075X A00                  | All in one  | [e2ff438b3c](https://linux-hardware.org/?probe=e2ff438b3c) | Sep 09, 2022 |
| Dell          | Precision 7560              | Notebook    | [3e2d1a120c](https://linux-hardware.org/?probe=3e2d1a120c) | Sep 09, 2022 |
| Dell          | Latitude E4300              | Notebook    | [634c1467f8](https://linux-hardware.org/?probe=634c1467f8) | Sep 09, 2022 |
| Dell          | Latitude 3120               | Convertible | [6b2b6b7aa9](https://linux-hardware.org/?probe=6b2b6b7aa9) | Sep 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [36b349b529](https://linux-hardware.org/?probe=36b349b529) | Sep 09, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [5c21c2acc6](https://linux-hardware.org/?probe=5c21c2acc6) | Sep 09, 2022 |
| Positivo      | H14BT58                     | Notebook    | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [1a5c8e32b7](https://linux-hardware.org/?probe=1a5c8e32b7) | Sep 09, 2022 |
| Lenovo        | IdeaPad S400 20195          | Notebook    | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [ee7071f4e7](https://linux-hardware.org/?probe=ee7071f4e7) | Sep 08, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [036c262ad4](https://linux-hardware.org/?probe=036c262ad4) | Sep 08, 2022 |
| Lenovo        | B5400 20278                 | Notebook    | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4a39ae67d5](https://linux-hardware.org/?probe=4a39ae67d5) | Sep 07, 2022 |
| Lenovo        | G580                        | Notebook    | [922ede2a50](https://linux-hardware.org/?probe=922ede2a50) | Sep 07, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [70e3d85420](https://linux-hardware.org/?probe=70e3d85420) | Sep 07, 2022 |
| MSI           | IONA                        | Desktop     | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | Desktop     | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | Desktop     | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [cf398ae303](https://linux-hardware.org/?probe=cf398ae303) | Sep 07, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [cca59cbb3c](https://linux-hardware.org/?probe=cca59cbb3c) | Sep 07, 2022 |
| Positivo      | Mobile                      | Notebook    | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad Edge E531 68856... | Notebook    | [498682ac13](https://linux-hardware.org/?probe=498682ac13) | Sep 06, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [8a66fbdadd](https://linux-hardware.org/?probe=8a66fbdadd) | Sep 06, 2022 |
| Sony          | VPCSB3X9E                   | Notebook    | [03bd901e4f](https://linux-hardware.org/?probe=03bd901e4f) | Sep 06, 2022 |
| ECS           | GeForce 8000 series         | Desktop     | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | Notebook    | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [78e0cb1ca2](https://linux-hardware.org/?probe=78e0cb1ca2) | Sep 06, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [39bc7728ac](https://linux-hardware.org/?probe=39bc7728ac) | Sep 06, 2022 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Lenovo        | ThinkPad L440 20ASS11T00    | Notebook    | [526d97c730](https://linux-hardware.org/?probe=526d97c730) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [537708f71a](https://linux-hardware.org/?probe=537708f71a) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | Notebook    | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Dell          | Latitude E6220              | Notebook    | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| Lenovo        | ThinkPad T530 2429W4Y       | Notebook    | [572b46f025](https://linux-hardware.org/?probe=572b46f025) | Sep 05, 2022 |
| ASUSTek       | K53BY                       | Notebook    | [efbc2be1a7](https://linux-hardware.org/?probe=efbc2be1a7) | Sep 05, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [d9a3103936](https://linux-hardware.org/?probe=d9a3103936) | Sep 05, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| Toshiba       | Satellite C55-A-157         | Notebook    | [483a0f4f49](https://linux-hardware.org/?probe=483a0f4f49) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| HP            | 8076                        | Desktop     | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [4d5b865aed](https://linux-hardware.org/?probe=4d5b865aed) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [e2115bf207](https://linux-hardware.org/?probe=e2115bf207) | Sep 05, 2022 |
| ASUSTek       | X45C                        | Notebook    | [7267b251b6](https://linux-hardware.org/?probe=7267b251b6) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | Desktop     | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [b36d7be7c1](https://linux-hardware.org/?probe=b36d7be7c1) | Sep 04, 2022 |
| HP            | 304Bh                       | Desktop     | [d395dd6c91](https://linux-hardware.org/?probe=d395dd6c91) | Sep 04, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [dcfbebc2dd](https://linux-hardware.org/?probe=dcfbebc2dd) | Sep 04, 2022 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [fb64be85f1](https://linux-hardware.org/?probe=fb64be85f1) | Sep 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [113f737135](https://linux-hardware.org/?probe=113f737135) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [792cbc3418](https://linux-hardware.org/?probe=792cbc3418) | Sep 04, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [3ba0635033](https://linux-hardware.org/?probe=3ba0635033) | Sep 04, 2022 |
| MSI           | MS-168B                     | Notebook    | [a0a6645eef](https://linux-hardware.org/?probe=a0a6645eef) | Sep 04, 2022 |
| Jumper        | EZbook                      | Notebook    | [d67fae436c](https://linux-hardware.org/?probe=d67fae436c) | Sep 04, 2022 |
| HP            | 8767 A                      | Desktop     | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| Gigabyte      | B560 AORUS PRO AX           | Desktop     | [fbd2e39516](https://linux-hardware.org/?probe=fbd2e39516) | Sep 04, 2022 |
| ECS           | H61H-G11/7.0                | Desktop     | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [3d542c8484](https://linux-hardware.org/?probe=3d542c8484) | Sep 03, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [c2251f33ef](https://linux-hardware.org/?probe=c2251f33ef) | Sep 03, 2022 |
| HP            | 620                         | Notebook    | [34002dc814](https://linux-hardware.org/?probe=34002dc814) | Sep 02, 2022 |
| Unknown       | Intel X79                   | Desktop     | [9e666e1530](https://linux-hardware.org/?probe=9e666e1530) | Sep 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| Getac         | B300-X                      | Notebook    | [927b99c2e0](https://linux-hardware.org/?probe=927b99c2e0) | Sep 02, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| Dell          | Latitude 3120               | Notebook    | [8716f564d8](https://linux-hardware.org/?probe=8716f564d8) | Sep 02, 2022 |
| Dell          | Latitude 3120               | Convertible | [44a711d7ce](https://linux-hardware.org/?probe=44a711d7ce) | Sep 02, 2022 |
| Dell          | Latitude 3120               | Convertible | [cb976a52d2](https://linux-hardware.org/?probe=cb976a52d2) | Sep 02, 2022 |
| HP            | 8053                        | Desktop     | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| Dell          | 0TP412                      | Desktop     | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [b9502cc4a9](https://linux-hardware.org/?probe=b9502cc4a9) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d27c20dcf9](https://linux-hardware.org/?probe=d27c20dcf9) | Sep 01, 2022 |
| Packard Be... | DOT S                       | Notebook    | [b5b03f1cf7](https://linux-hardware.org/?probe=b5b03f1cf7) | Sep 01, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [e2fc506c38](https://linux-hardware.org/?probe=e2fc506c38) | Sep 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [d30269b33c](https://linux-hardware.org/?probe=d30269b33c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [c9a801a4d2](https://linux-hardware.org/?probe=c9a801a4d2) | Sep 01, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7140822520](https://linux-hardware.org/?probe=7140822520) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | Notebook    | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1a173c5ea0](https://linux-hardware.org/?probe=1a173c5ea0) | Sep 01, 2022 |
| HP            | Pavilion g6                 | Notebook    | [cc725d880c](https://linux-hardware.org/?probe=cc725d880c) | Aug 31, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [710d1e9a9b](https://linux-hardware.org/?probe=710d1e9a9b) | Aug 31, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [120400698e](https://linux-hardware.org/?probe=120400698e) | Aug 31, 2022 |
| Vorke         | V1 Plus                     | Desktop     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [0ea749e83c](https://linux-hardware.org/?probe=0ea749e83c) | Aug 30, 2022 |
| Dell          | Precision M6400             | Notebook    | [3cf32e24fa](https://linux-hardware.org/?probe=3cf32e24fa) | Aug 30, 2022 |
| HP            | 0A60h                       | Desktop     | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [33aaa7baf4](https://linux-hardware.org/?probe=33aaa7baf4) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | Desktop     | [0099ab3432](https://linux-hardware.org/?probe=0099ab3432) | Aug 29, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [536742931b](https://linux-hardware.org/?probe=536742931b) | Aug 29, 2022 |
| Dell          | Latitude 3300               | Notebook    | [bea8e53929](https://linux-hardware.org/?probe=bea8e53929) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M58p 6234CL2    | Desktop     | [14449a705a](https://linux-hardware.org/?probe=14449a705a) | Aug 29, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [99f7df96c2](https://linux-hardware.org/?probe=99f7df96c2) | Aug 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| Dell          | Studio 1735                 | Notebook    | [912f409b37](https://linux-hardware.org/?probe=912f409b37) | Aug 28, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [d8a4e4d954](https://linux-hardware.org/?probe=d8a4e4d954) | Aug 28, 2022 |
| HP            | 620                         | Notebook    | [b16c60f4cf](https://linux-hardware.org/?probe=b16c60f4cf) | Aug 28, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [91371e505d](https://linux-hardware.org/?probe=91371e505d) | Aug 28, 2022 |
| Acer          | AO722                       | Notebook    | [377ad8686f](https://linux-hardware.org/?probe=377ad8686f) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [a18db0fafd](https://linux-hardware.org/?probe=a18db0fafd) | Aug 27, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [f74dc71ad8](https://linux-hardware.org/?probe=f74dc71ad8) | Aug 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [d6c013a669](https://linux-hardware.org/?probe=d6c013a669) | Aug 27, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [67712f11d9](https://linux-hardware.org/?probe=67712f11d9) | Aug 27, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [cf0bc232f5](https://linux-hardware.org/?probe=cf0bc232f5) | Aug 26, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [22cc477cd2](https://linux-hardware.org/?probe=22cc477cd2) | Aug 26, 2022 |
| Apple         | Mac-CFF7D910A743CAAF iMa... | All in one  | [1b562e8768](https://linux-hardware.org/?probe=1b562e8768) | Aug 26, 2022 |
| MSI           | 760GM-P21                   | Desktop     | [7e45cde899](https://linux-hardware.org/?probe=7e45cde899) | Aug 26, 2022 |
| HP            | 1497                        | Desktop     | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [e4a6425675](https://linux-hardware.org/?probe=e4a6425675) | Aug 26, 2022 |
| HP            | 15                          | Notebook    | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| Dell          | 06MC09 A00                  | Mini pc     | [71402e3c39](https://linux-hardware.org/?probe=71402e3c39) | Aug 26, 2022 |
| Dell          | 0RJ290                      | Desktop     | [ca82162ed5](https://linux-hardware.org/?probe=ca82162ed5) | Aug 25, 2022 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [0b76e0f97d](https://linux-hardware.org/?probe=0b76e0f97d) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [72888e9acb](https://linux-hardware.org/?probe=72888e9acb) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [82da7782ec](https://linux-hardware.org/?probe=82da7782ec) | Aug 25, 2022 |
| HP            | 829A                        | Mini pc     | [76cb57e98d](https://linux-hardware.org/?probe=76cb57e98d) | Aug 25, 2022 |
| OEM           | A320                        | Desktop     | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [b201192ebb](https://linux-hardware.org/?probe=b201192ebb) | Aug 25, 2022 |
| Dell          | Latitude E5510              | Notebook    | [c237161d31](https://linux-hardware.org/?probe=c237161d31) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d1cae6aca8](https://linux-hardware.org/?probe=d1cae6aca8) | Aug 24, 2022 |
| HP            | 21D0                        | Desktop     | [1bd58d519c](https://linux-hardware.org/?probe=1bd58d519c) | Aug 24, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | Notebook    | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f20e68e820](https://linux-hardware.org/?probe=f20e68e820) | Aug 24, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [e75751c55b](https://linux-hardware.org/?probe=e75751c55b) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [c824203d0a](https://linux-hardware.org/?probe=c824203d0a) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | Notebook    | [81b42d221d](https://linux-hardware.org/?probe=81b42d221d) | Aug 24, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [744f838dc2](https://linux-hardware.org/?probe=744f838dc2) | Aug 24, 2022 |
| Supermicro    | X10SDV-8C+-LN2F             | Server      | [a4ec1f93e5](https://linux-hardware.org/?probe=a4ec1f93e5) | Aug 23, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [685d6acc51](https://linux-hardware.org/?probe=685d6acc51) | Aug 23, 2022 |
| ICP / iEi     | B217 V1.0                   | Desktop     | [9b540ece9f](https://linux-hardware.org/?probe=9b540ece9f) | Aug 23, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| Dell          | Latitude E5470              | Notebook    | [4cf5f4680f](https://linux-hardware.org/?probe=4cf5f4680f) | Aug 23, 2022 |
| HP            | 8158 A01                    | Mini pc     | [443d203df8](https://linux-hardware.org/?probe=443d203df8) | Aug 22, 2022 |
| Google        | Galtic                      | Notebook    | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [1de0aeba8f](https://linux-hardware.org/?probe=1de0aeba8f) | Aug 22, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003       | 3942      | 96.33%  |
| 5.16.13-desktop-1omv4003      | 114       | 2.79%   |
| 5.17.1-desktop-2omv4050       | 17        | 0.42%   |
| 5.14.14-desktop-1omv4050      | 5         | 0.12%   |
| 5.16.5-desktop-2omv4003       | 3         | 0.07%   |
| 5.17.1-desktop-clang-2omv4050 | 2         | 0.05%   |
| 5.16.9-desktop-1omv4003       | 2         | 0.05%   |
| 5.16.3-desktop-2omv4050       | 2         | 0.05%   |
| 5.17.7-desktop-1omv4090       | 1         | 0.02%   |
| 5.16.9-desktop-1omv4050       | 1         | 0.02%   |
| 5.16.7-desktop-clang-1omv4003 | 1         | 0.02%   |
| 5.15.14-1-lts                 | 1         | 0.02%   |
| 5.10.14-desktop-1omv4002      | 1         | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.7  | 3943      | 96.36%  |
| 5.16.13 | 114       | 2.79%   |
| 5.17.1  | 19        | 0.46%   |
| 5.14.14 | 5         | 0.12%   |
| 5.16.9  | 3         | 0.07%   |
| 5.16.5  | 3         | 0.07%   |
| 5.16.3  | 2         | 0.05%   |
| 5.17.7  | 1         | 0.02%   |
| 5.15.14 | 1         | 0.02%   |
| 5.10.14 | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 4063      | 99.34%  |
| 5.17    | 20        | 0.49%   |
| 5.14    | 5         | 0.12%   |
| 5.15    | 1         | 0.02%   |
| 5.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 4090      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDE5    | 4076      | 99.66%  |
| LXQt    | 8         | 0.2%    |
| Unknown | 6         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4063      | 99.34%  |
| Wayland | 27        | 0.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 4089      | 99.98%  |
| LightDM | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 2318      | 56.65%  |
| de_DE | 359       | 8.77%   |
| ru_RU | 198       | 4.84%   |
| fr_FR | 197       | 4.81%   |
| pt_BR | 166       | 4.06%   |
| pl_PL | 118       | 2.88%   |
| it_IT | 109       | 2.66%   |
| en_GB | 83        | 2.03%   |
| es_ES | 81        | 1.98%   |
| es_AR | 42        | 1.03%   |
| cs_CZ | 41        | 1%      |
| de_AT | 39        | 0.95%   |
| es_MX | 34        | 0.83%   |
| en_IN | 24        | 0.59%   |
| hu_HU | 22        | 0.54%   |
| tr_TR | 20        | 0.49%   |
| en_CA | 19        | 0.46%   |
| pt_PT | 18        | 0.44%   |
| es_CO | 16        | 0.39%   |
| fr_CA | 15        | 0.37%   |
| en_AU | 15        | 0.37%   |
| de_CH | 15        | 0.37%   |
| nl_NL | 14        | 0.34%   |
| es_CL | 13        | 0.32%   |
| es_VE | 11        | 0.27%   |
| fr_BE | 10        | 0.24%   |
| ru_UA | 9         | 0.22%   |
| nl_BE | 9         | 0.22%   |
| es_PE | 8         | 0.2%    |
| da_DK | 7         | 0.17%   |
| nb_NO | 5         | 0.12%   |
| fr_CH | 5         | 0.12%   |
| es_CR | 5         | 0.12%   |
| ro_RO | 4         | 0.1%    |
| es_UY | 4         | 0.1%    |
| uk_UA | 3         | 0.07%   |
| es_SV | 3         | 0.07%   |
| es_EC | 3         | 0.07%   |
| en_ZA | 3         | 0.07%   |
| en_HK | 3         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2141      | 52.35%  |
| BIOS | 1949      | 47.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 3424      | 83.68%  |
| Ext4     | 654       | 15.98%  |
| Xfs      | 5         | 0.12%   |
| F2fs     | 3         | 0.07%   |
| Btrfs    | 3         | 0.07%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| Ext3     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2732      | 66.76%  |
| MBR     | 1342      | 32.8%   |
| Unknown | 18        | 0.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2266      | 55.39%  |
| No        | 1825      | 44.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2079      | 50.83%  |
| Yes       | 2011      | 49.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUSTek Computer      | 655       | 16.01%  |
| Dell                  | 559       | 13.67%  |
| Hewlett-Packard       | 523       | 12.79%  |
| Lenovo                | 487       | 11.91%  |
| Gigabyte Technology   | 352       | 8.61%   |
| Acer                  | 269       | 6.58%   |
| MSI                   | 235       | 5.75%   |
| ASRock                | 171       | 4.18%   |
| Toshiba               | 98        | 2.4%    |
| Intel                 | 88        | 2.15%   |
| Fujitsu               | 64        | 1.56%   |
| Apple                 | 62        | 1.52%   |
| Sony                  | 44        | 1.08%   |
| Samsung Electronics   | 44        | 1.08%   |
| Positivo              | 32        | 0.78%   |
| Medion                | 25        | 0.61%   |
| Foxconn               | 24        | 0.59%   |
| Biostar               | 24        | 0.59%   |
| Packard Bell          | 23        | 0.56%   |
| Pegatron              | 20        | 0.49%   |
| Unknown               | 19        | 0.46%   |
| ECS                   | 15        | 0.37%   |
| AZW                   | 11        | 0.27%   |
| TUXEDO                | 10        | 0.24%   |
| HUAWEI                | 10        | 0.24%   |
| Fujitsu Siemens       | 10        | 0.24%   |
| BESSTAR Tech          | 10        | 0.24%   |
| Alienware             | 10        | 0.24%   |
| Philco                | 8         | 0.2%    |
| LG Electronics        | 8         | 0.2%    |
| Chuwi                 | 8         | 0.2%    |
| Shuttle               | 7         | 0.17%   |
| Notebook              | 7         | 0.17%   |
| Compaq                | 7         | 0.17%   |
| Supermicro            | 6         | 0.15%   |
| Gateway               | 6         | 0.15%   |
| eMachines             | 6         | 0.15%   |
| Microsoft             | 5         | 0.12%   |
| Positivo Bahia - VAIO | 4         | 0.1%    |
| MACHINIST             | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Latitude 3120             | 48        | 1.17%   |
| ASUS All Series                | 38        | 0.93%   |
| Dell Latitude 3190 2-in-1      | 34        | 0.83%   |
| Unknown                        | 34        | 0.83%   |
| Dell Latitude 3310             | 29        | 0.71%   |
| Gigabyte H410M H V3            | 27        | 0.66%   |
| HP Notebook                    | 20        | 0.49%   |
| ASUS SABERTOOTH Z77            | 19        | 0.46%   |
| Dell OptiPlex 7010             | 14        | 0.34%   |
| Lenovo IdeaPad 1 14ADA05 82GW  | 11        | 0.27%   |
| ASUS UX31E                     | 11        | 0.27%   |
| Intel H61                      | 9         | 0.22%   |
| HP Pavilion g6                 | 9         | 0.22%   |
| Dell OptiPlex 780              | 9         | 0.22%   |
| Positivo Mobile                | 8         | 0.2%    |
| Dell OptiPlex 790              | 8         | 0.2%    |
| Dell OptiPlex 380              | 8         | 0.2%    |
| Dell Latitude 3300             | 8         | 0.2%    |
| ASUS PRIME B450M-A II          | 8         | 0.2%    |
| Sony VGN-FZ31Z                 | 7         | 0.17%   |
| MSI MS-7C91                    | 7         | 0.17%   |
| Lenovo IdeaPad S145-15AST 81N3 | 7         | 0.17%   |
| HP Pavilion dv6                | 7         | 0.17%   |
| Dell XPS 15 9530               | 7         | 0.17%   |
| Dell Latitude E7450            | 7         | 0.17%   |
| Dell Latitude E6420            | 7         | 0.17%   |
| MSI MS-7C37                    | 6         | 0.15%   |
| MSI MS-7B79                    | 6         | 0.15%   |
| MSI MS-7A38                    | 6         | 0.15%   |
| MSI MS-7721                    | 6         | 0.15%   |
| HP Pavilion 15                 | 6         | 0.15%   |
| HP Laptop 14-fq0xxx            | 6         | 0.15%   |
| HP EliteDesk 800 G1 SFF        | 6         | 0.15%   |
| HP Compaq Pro 6300 SFF         | 6         | 0.15%   |
| HP 15                          | 6         | 0.15%   |
| Gigabyte 970A-DS3P             | 6         | 0.15%   |
| Dell Precision M6800           | 6         | 0.15%   |
| Dell OptiPlex 9020             | 6         | 0.15%   |
| Dell OptiPlex 7020             | 6         | 0.15%   |
| Dell OptiPlex 3020             | 6         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 270       | 6.6%    |
| Acer Aspire           | 183       | 4.47%   |
| Lenovo ThinkPad       | 151       | 3.69%   |
| Lenovo IdeaPad        | 128       | 3.13%   |
| Dell OptiPlex         | 103       | 2.52%   |
| HP Pavilion           | 97        | 2.37%   |
| Toshiba Satellite     | 81        | 1.98%   |
| HP Compaq             | 77        | 1.88%   |
| ASUS PRIME            | 77        | 1.88%   |
| Dell Inspiron         | 75        | 1.83%   |
| Lenovo ThinkCentre    | 58        | 1.42%   |
| HP Laptop             | 57        | 1.39%   |
| HP ProBook            | 47        | 1.15%   |
| ASUS VivoBook         | 41        | 1%      |
| ASUS TUF              | 40        | 0.98%   |
| ASUS All              | 38        | 0.93%   |
| ASUS ROG              | 36        | 0.88%   |
| Unknown               | 34        | 0.83%   |
| Gigabyte H410M        | 31        | 0.76%   |
| Dell Precision        | 31        | 0.76%   |
| HP EliteBook          | 29        | 0.71%   |
| HP EliteDesk          | 27        | 0.66%   |
| Fujitsu LIFEBOOK      | 27        | 0.66%   |
| Dell XPS              | 26        | 0.64%   |
| Dell Vostro           | 25        | 0.61%   |
| ASUS SABERTOOTH       | 25        | 0.61%   |
| HP ProDesk            | 24        | 0.59%   |
| Fujitsu ESPRIMO       | 23        | 0.56%   |
| Lenovo IdeaCentre     | 21        | 0.51%   |
| HP Notebook           | 20        | 0.49%   |
| ASUS M5A78L-M         | 17        | 0.42%   |
| Acer Nitro            | 17        | 0.42%   |
| Packard Bell EasyNote | 16        | 0.39%   |
| Lenovo Yoga           | 13        | 0.32%   |
| Gigabyte B450M        | 13        | 0.32%   |
| Acer Swift            | 13        | 0.32%   |
| ASUS UX31E            | 11        | 0.27%   |
| Acer TravelMate       | 11        | 0.27%   |
| Acer Extensa          | 11        | 0.27%   |
| Intel H61             | 10        | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 407       | 9.95%   |
| 2011    | 372       | 9.1%    |
| 2013    | 329       | 8.04%   |
| 2021    | 327       | 8%      |
| 2019    | 324       | 7.92%   |
| 2020    | 312       | 7.63%   |
| 2018    | 283       | 6.92%   |
| 2014    | 276       | 6.75%   |
| 2010    | 264       | 6.45%   |
| 2016    | 207       | 5.06%   |
| 2017    | 201       | 4.91%   |
| 2015    | 198       | 4.84%   |
| 2009    | 193       | 4.72%   |
| 2008    | 183       | 4.47%   |
| 2007    | 121       | 2.96%   |
| 2006    | 53        | 1.3%    |
| 2022    | 31        | 0.76%   |
| 2005    | 5         | 0.12%   |
| Unknown | 4         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1934      | 47.29%  |
| Desktop     | 1879      | 45.94%  |
| Convertible | 120       | 2.93%   |
| Mini pc     | 65        | 1.59%   |
| All in one  | 64        | 1.56%   |
| Server      | 17        | 0.42%   |
| Tablet      | 11        | 0.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4090      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4085      | 99.88%  |
| Yes  | 5         | 0.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1173      | 28.68%  |
| 3.01-4.0        | 1065      | 26.04%  |
| 8.01-16.0       | 719       | 17.58%  |
| 16.01-24.0      | 601       | 14.69%  |
| 32.01-64.0      | 236       | 5.77%   |
| 1.01-2.0        | 132       | 3.23%   |
| 2.01-3.0        | 52        | 1.27%   |
| 64.01-256.0     | 50        | 1.22%   |
| 24.01-32.0      | 49        | 1.2%    |
| 0.51-1.0        | 10        | 0.24%   |
| More than 256.0 | 3         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 3038      | 74.28%  |
| 0.51-1.0  | 664       | 16.23%  |
| 2.01-3.0  | 276       | 6.75%   |
| 0.01-0.5  | 57        | 1.39%   |
| 3.01-4.0  | 29        | 0.71%   |
| 4.01-8.0  | 16        | 0.39%   |
| 8.01-16.0 | 10        | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2409      | 58.9%   |
| 2      | 997       | 24.38%  |
| 3      | 318       | 7.78%   |
| 4      | 168       | 4.11%   |
| 0      | 77        | 1.88%   |
| 5      | 66        | 1.61%   |
| 6      | 27        | 0.66%   |
| 7      | 11        | 0.27%   |
| 8      | 6         | 0.15%   |
| 9      | 4         | 0.1%    |
| 12     | 3         | 0.07%   |
| 11     | 2         | 0.05%   |
| 15     | 1         | 0.02%   |
| 10     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2076      | 50.76%  |
| Yes       | 2014      | 49.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3671      | 89.76%  |
| No        | 419       | 10.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2814      | 68.79%  |
| No        | 1277      | 31.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2079      | 50.83%  |
| No        | 2011      | 49.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 493       | 12.05%  |
| USA         | 471       | 11.52%  |
| Brazil      | 272       | 6.65%   |
| France      | 264       | 6.45%   |
| Russia      | 250       | 6.11%   |
| Poland      | 201       | 4.91%   |
| Netherlands | 191       | 4.67%   |
| Italy       | 172       | 4.21%   |
| UK          | 129       | 3.15%   |
| Spain       | 113       | 2.76%   |
| Canada      | 107       | 2.62%   |
| Mexico      | 74        | 1.81%   |
| India       | 73        | 1.78%   |
| Australia   | 70        | 1.71%   |
| Czechia     | 58        | 1.42%   |
| Indonesia   | 53        | 1.3%    |
| Japan       | 52        | 1.27%   |
| Austria     | 52        | 1.27%   |
| Argentina   | 52        | 1.27%   |
| Portugal    | 47        | 1.15%   |
| Ukraine     | 43        | 1.05%   |
| Turkey      | 41        | 1%      |
| Switzerland | 41        | 1%      |
| Romania     | 41        | 1%      |
| Sweden      | 37        | 0.9%    |
| Hungary     | 34        | 0.83%   |
| Belgium     | 34        | 0.83%   |
| Colombia    | 32        | 0.78%   |
| Slovakia    | 25        | 0.61%   |
| Serbia      | 25        | 0.61%   |
| Greece      | 22        | 0.54%   |
| Finland     | 21        | 0.51%   |
| China       | 21        | 0.51%   |
| Chile       | 21        | 0.51%   |
| Bulgaria    | 21        | 0.51%   |
| Peru        | 19        | 0.46%   |
| Egypt       | 19        | 0.46%   |
| Venezuela   | 17        | 0.42%   |
| Israel      | 17        | 0.42%   |
| Norway      | 16        | 0.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Schagen        | 137       | 3.35%   |
| Moscow         | 51        | 1.25%   |
| Sao Paulo      | 33        | 0.81%   |
| Paris          | 33        | 0.81%   |
| Berlin         | 32        | 0.78%   |
| Warsaw         | 31        | 0.76%   |
| Vienna         | 26        | 0.64%   |
| Milan          | 23        | 0.56%   |
| Prague         | 22        | 0.54%   |
| Gonikoppal     | 22        | 0.54%   |
| Sydney         | 20        | 0.49%   |
| Mexico City    | 19        | 0.46%   |
| Munich         | 18        | 0.44%   |
| Strzyzow       | 17        | 0.42%   |
| Istanbul       | 17        | 0.42%   |
| St Petersburg  | 16        | 0.39%   |
| Hamburg        | 16        | 0.39%   |
| Rio de Janeiro | 15        | 0.37%   |
| Jakarta        | 15        | 0.37%   |
| Belgrade       | 15        | 0.37%   |
| Madrid         | 13        | 0.32%   |
| Lima           | 13        | 0.32%   |
| Cairo          | 13        | 0.32%   |
| Rome           | 12        | 0.29%   |
| Krakow         | 12        | 0.29%   |
| Brisbane       | 12        | 0.29%   |
| Cascais        | 11        | 0.27%   |
| Bengaluru      | 11        | 0.27%   |
| Zagreb         | 10        | 0.24%   |
| Wroclaw        | 10        | 0.24%   |
| Montreal       | 10        | 0.24%   |
| Buenos Aires   | 10        | 0.24%   |
| Barcelona      | 10        | 0.24%   |
| San José      | 9         | 0.22%   |
| Montevideo     | 9         | 0.22%   |
| Kyiv           | 9         | 0.22%   |
| Helsinki       | 9         | 0.22%   |
| Gdansk         | 9         | 0.22%   |
| Dortmund       | 9         | 0.22%   |
| Curitiba       | 9         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 988       | 1185   | 16.83%  |
| Seagate             | 871       | 1054   | 14.84%  |
| Samsung Electronics | 759       | 899    | 12.93%  |
| Toshiba             | 409       | 431    | 6.97%   |
| Kingston            | 343       | 364    | 5.84%   |
| Crucial             | 260       | 299    | 4.43%   |
| SanDisk             | 249       | 275    | 4.24%   |
| Hitachi             | 235       | 243    | 4%      |
| Unknown             | 157       | 169    | 2.67%   |
| A-DATA Technology   | 146       | 154    | 2.49%   |
| SK hynix            | 135       | 139    | 2.3%    |
| HGST                | 109       | 119    | 1.86%   |
| Intel               | 69        | 74     | 1.18%   |
| China               | 63        | 69     | 1.07%   |
| Micron Technology   | 52        | 52     | 0.89%   |
| GOODRAM             | 44        | 46     | 0.75%   |
| Unknown             | 41        | 43     | 0.7%    |
| PNY                 | 40        | 47     | 0.68%   |
| SPCC                | 37        | 40     | 0.63%   |
| Intenso             | 37        | 38     | 0.63%   |
| Patriot             | 35        | 37     | 0.6%    |
| LITEON              | 35        | 35     | 0.6%    |
| KIOXIA              | 33        | 33     | 0.56%   |
| ASMT                | 31        | 34     | 0.53%   |
| Maxtor              | 30        | 34     | 0.51%   |
| Apacer              | 29        | 30     | 0.49%   |
| JMicron Technology  | 28        | 29     | 0.48%   |
| Apple               | 28        | 28     | 0.48%   |
| Gigabyte Technology | 27        | 27     | 0.46%   |
| Fujitsu             | 27        | 28     | 0.46%   |
| Corsair             | 24        | 25     | 0.41%   |
| SSSTC               | 23        | 23     | 0.39%   |
| Phison              | 23        | 25     | 0.39%   |
| Netac               | 23        | 24     | 0.39%   |
| Transcend           | 22        | 24     | 0.37%   |
| OCZ                 | 22        | 22     | 0.37%   |
| Hewlett-Packard     | 20        | 23     | 0.34%   |
| KingSpec            | 18        | 18     | 0.31%   |
| Silicon Motion      | 17        | 19     | 0.29%   |
| Team                | 16        | 16     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 81        | 1.26%   |
| Seagate ST500DM002-1BD142 500GB    | 63        | 0.98%   |
| Seagate ST1000DM010-2EP102 1TB     | 51        | 0.79%   |
| Samsung SSD 860 EVO 500GB          | 44        | 0.69%   |
| Kingston SA400S37120G 120GB SSD    | 43        | 0.67%   |
| Samsung SSD 860 EVO 250GB          | 42        | 0.65%   |
| Toshiba MQ01ABF050 500GB           | 41        | 0.64%   |
| Samsung SSD 850 EVO 250GB          | 41        | 0.64%   |
| Unknown                            | 41        | 0.64%   |
| Kingston SA400S37480G 480GB SSD    | 40        | 0.62%   |
| Toshiba MQ01ABD100 1TB             | 39        | 0.61%   |
| Crucial CT500MX500SSD1 500GB       | 39        | 0.61%   |
| Unknown SD/MMC/MS PRO 64GB         | 38        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 38        | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB           | 37        | 0.58%   |
| Seagate ST2000DM008-2FR102 2TB     | 33        | 0.51%   |
| Crucial CT240BX500SSD1 240GB       | 33        | 0.51%   |
| Toshiba DT01ACA100 1TB             | 31        | 0.48%   |
| Seagate ST500LT012-1DG142 500GB    | 31        | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB     | 30        | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 28        | 0.44%   |
| Toshiba MQ04ABF100 1TB             | 28        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD   | 27        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB        | 27        | 0.42%   |
| Toshiba DT01ACA050 500GB           | 26        | 0.41%   |
| Samsung SSD 970 EVO Plus 500GB     | 25        | 0.39%   |
| Samsung SSD 850 EVO 500GB          | 25        | 0.39%   |
| Crucial CT480BX500SSD1 480GB       | 25        | 0.39%   |
| Seagate ST1000DM003-1ER162 1TB     | 23        | 0.36%   |
| SK hynix BC711 NVMe 128GB          | 22        | 0.34%   |
| Seagate ST9500325AS 500GB          | 22        | 0.34%   |
| SanDisk SSD PLUS 240GB             | 22        | 0.34%   |
| HGST HTS545050A7E680 500GB         | 22        | 0.34%   |
| A-DATA SU750 256GB SSD             | 22        | 0.34%   |
| Samsung SSD 970 EVO Plus 1TB       | 21        | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 19        | 0.3%    |
| Seagate ST3500418AS 500GB          | 19        | 0.3%    |
| Seagate ST2000DM001-1ER164 2TB     | 19        | 0.3%    |
| HGST HTS721010A9E630 1TB           | 19        | 0.3%    |
| Toshiba HDWD110 1TB                | 18        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 858       | 1032   | 31.81%  |
| WDC                 | 801       | 936    | 29.7%   |
| Toshiba             | 362       | 380    | 13.42%  |
| Hitachi             | 235       | 243    | 8.71%   |
| Samsung Electronics | 160       | 180    | 5.93%   |
| HGST                | 109       | 119    | 4.04%   |
| Unknown             | 39        | 39     | 1.45%   |
| Maxtor              | 28        | 32     | 1.04%   |
| Fujitsu             | 27        | 28     | 1%      |
| ASMT                | 17        | 20     | 0.63%   |
| Apple               | 14        | 14     | 0.52%   |
| USB3.0              | 5         | 5      | 0.19%   |
| WD MediaMax         | 4         | 5      | 0.15%   |
| ASMedia             | 4         | 4      | 0.15%   |
| SAGE                | 3         | 3      | 0.11%   |
| Magnetic Data       | 3         | 3      | 0.11%   |
| JMicron Technology  | 3         | 3      | 0.11%   |
| Intenso             | 3         | 3      | 0.11%   |
| IBM/Hitachi         | 3         | 3      | 0.11%   |
| Hewlett-Packard     | 3         | 3      | 0.11%   |
| HPE                 | 2         | 2      | 0.07%   |
| Unknown             | 2         | 2      | 0.07%   |
| USB                 | 1         | 1      | 0.04%   |
| RSH-339             | 1         | 1      | 0.04%   |
| Quantum             | 1         | 1      | 0.04%   |
| QC-FT-D             | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 1      | 0.04%   |
| Initio              | 1         | 1      | 0.04%   |
| Inateck             | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| Config              | 1         | 1      | 0.04%   |
| China               | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 417       | 462    | 18.86%  |
| Kingston            | 284       | 298    | 12.84%  |
| Crucial             | 223       | 254    | 10.09%  |
| SanDisk             | 219       | 240    | 9.91%   |
| WDC                 | 122       | 132    | 5.52%   |
| A-DATA Technology   | 114       | 115    | 5.16%   |
| China               | 62        | 68     | 2.8%    |
| GOODRAM             | 42        | 42     | 1.9%    |
| SK hynix            | 37        | 38     | 1.67%   |
| Micron Technology   | 36        | 36     | 1.63%   |
| PNY                 | 35        | 40     | 1.58%   |
| Toshiba             | 33        | 34     | 1.49%   |
| LITEON              | 32        | 32     | 1.45%   |
| Intenso             | 31        | 32     | 1.4%    |
| Intel               | 31        | 32     | 1.4%    |
| Patriot             | 30        | 32     | 1.36%   |
| SPCC                | 28        | 30     | 1.27%   |
| Apacer              | 26        | 26     | 1.18%   |
| Unknown             | 24        | 25     | 1.09%   |
| OCZ                 | 22        | 22     | 1%      |
| Transcend           | 20        | 21     | 0.9%    |
| Netac               | 20        | 21     | 0.9%    |
| JMicron Technology  | 19        | 20     | 0.86%   |
| KingSpec            | 18        | 18     | 0.81%   |
| Gigabyte Technology | 16        | 16     | 0.72%   |
| Team                | 15        | 15     | 0.68%   |
| LITEONIT            | 13        | 13     | 0.59%   |
| Hewlett-Packard     | 12        | 14     | 0.54%   |
| Apple               | 12        | 12     | 0.54%   |
| Corsair             | 11        | 11     | 0.5%    |
| ASMT                | 11        | 11     | 0.5%    |
| Lexar               | 8         | 8      | 0.36%   |
| KIOXIA-EXCERIA      | 8         | 8      | 0.36%   |
| KingFast            | 8         | 8      | 0.36%   |
| KingDian            | 7         | 7      | 0.32%   |
| TO Exter            | 6         | 6      | 0.27%   |
| Seagate             | 6         | 6      | 0.27%   |
| Leven               | 6         | 6      | 0.27%   |
| TCSUNBOW            | 5         | 5      | 0.23%   |
| XrayDisk            | 4         | 4      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2299      | 3071   | 44.09%  |
| SSD     | 1890      | 2360   | 36.25%  |
| NVMe    | 826       | 949    | 15.84%  |
| MMC     | 141       | 149    | 2.7%    |
| Unknown | 58        | 71     | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3481      | 5196   | 73.84%  |
| NVMe | 818       | 932    | 17.35%  |
| SAS  | 274       | 323    | 5.81%   |
| MMC  | 141       | 149    | 2.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2780      | 3566   | 64.29%  |
| 0.51-1.0   | 1085      | 1299   | 25.09%  |
| 1.01-2.0   | 269       | 324    | 6.22%   |
| 3.01-4.0   | 71        | 95     | 1.64%   |
| 2.01-3.0   | 55        | 65     | 1.27%   |
| 4.01-10.0  | 54        | 72     | 1.25%   |
| 10.01-20.0 | 10        | 10     | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2351      | 57.47%  |
| 101-250        | 551       | 13.47%  |
| 251-500        | 332       | 8.12%   |
| Unknown        | 332       | 8.12%   |
| 501-1000       | 168       | 4.11%   |
| 51-100         | 146       | 3.57%   |
| 21-50          | 137       | 3.35%   |
| 1001-2000      | 50        | 1.22%   |
| More than 3000 | 14        | 0.34%   |
| 2001-3000      | 10        | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3477      | 84.99%  |
| Unknown        | 332       | 8.12%   |
| 101-250        | 75        | 1.83%   |
| 51-100         | 65        | 1.59%   |
| 21-50          | 63        | 1.54%   |
| 251-500        | 37        | 0.9%    |
| 501-1000       | 23        | 0.56%   |
| 1001-2000      | 13        | 0.32%   |
| More than 3000 | 3         | 0.07%   |
| 2001-3000      | 3         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 27        | 28     | 2.24%   |
| HGST HTS545050A7E680 500GB          | 18        | 18     | 1.49%   |
| Seagate ST9500325AS 500GB           | 15        | 15     | 1.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 15        | 15     | 1.24%   |
| Toshiba MQ01ABF050 500GB            | 12        | 12     | 0.99%   |
| SanDisk SSD U100 256GB              | 11        | 11     | 0.91%   |
| HGST HTS541010A9E680 1TB            | 11        | 11     | 0.91%   |
| Seagate ST9320325AS 320GB           | 10        | 10     | 0.83%   |
| Samsung Electronics HD322HJ 320GB   | 9         | 10     | 0.75%   |
| Kingston SV300S37A120G 120GB SSD    | 9         | 9      | 0.75%   |
| Hitachi HTS543232A7A384 320GB       | 9         | 9      | 0.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 8         | 8      | 0.66%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 8      | 0.66%   |
| Seagate ST3500413AS 500GB           | 8         | 8      | 0.66%   |
| Seagate ST1000DM003-9YN162 1TB      | 8         | 8      | 0.66%   |
| Toshiba MQ01ABD100 1TB              | 7         | 7      | 0.58%   |
| Toshiba MQ01ABD050 500GB            | 7         | 7      | 0.58%   |
| Seagate ST3500418AS 500GB           | 7         | 7      | 0.58%   |
| Seagate ST1000LM035-1RK172 1TB      | 7         | 7      | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB      | 7         | 7      | 0.58%   |
| Hitachi HTS725032A7E630 320GB       | 7         | 7      | 0.58%   |
| HGST HTS721010A9E630 1TB            | 7         | 8      | 0.58%   |
| HGST HTS545050A7E380 500GB          | 7         | 7      | 0.58%   |
| Crucial CT240M500SSD1 240GB         | 7         | 7      | 0.58%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 6         | 6      | 0.5%    |
| SanDisk SSD PLUS 240GB              | 6         | 6      | 0.5%    |
| Samsung Electronics HD502HJ 500GB   | 6         | 6      | 0.5%    |
| HGST HTS725050A7E630 500GB          | 6         | 6      | 0.5%    |
| WDC WD5000AAKS-00V1A0 500GB         | 5         | 5      | 0.41%   |
| WDC WD5000AADS-00S9B0 500GB         | 5         | 5      | 0.41%   |
| Seagate ST9250410AS 250GB           | 5         | 5      | 0.41%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 0.41%   |
| Seagate ST3320418AS 320GB           | 5         | 5      | 0.41%   |
| Seagate ST31000524AS 1TB            | 5         | 5      | 0.41%   |
| Seagate ST2000DM001-1CH164 2TB      | 5         | 5      | 0.41%   |
| Seagate ST1000DM003-1SB102 1TB      | 5         | 5      | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB      | 5         | 5      | 0.41%   |
| SanDisk SSD PLUS 480GB              | 5         | 5      | 0.41%   |
| Hitachi HTS547575A9E384 752GB       | 5         | 5      | 0.41%   |
| Hitachi HDS721050CLA362 500GB       | 5         | 5      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 314       | 335    | 26.79%  |
| WDC                 | 252       | 270    | 21.5%   |
| Hitachi             | 120       | 122    | 10.24%  |
| Toshiba             | 103       | 103    | 8.79%   |
| Samsung Electronics | 94        | 100    | 8.02%   |
| HGST                | 59        | 60     | 5.03%   |
| SanDisk             | 36        | 36     | 3.07%   |
| Kingston            | 26        | 26     | 2.22%   |
| Crucial             | 23        | 24     | 1.96%   |
| Maxtor              | 18        | 18     | 1.54%   |
| A-DATA Technology   | 15        | 15     | 1.28%   |
| Intel               | 12        | 12     | 1.02%   |
| Fujitsu             | 11        | 11     | 0.94%   |
| SK hynix            | 8         | 9      | 0.68%   |
| Micron Technology   | 8         | 8      | 0.68%   |
| China               | 7         | 7      | 0.6%    |
| GOODRAM             | 5         | 5      | 0.43%   |
| Apple               | 5         | 5      | 0.43%   |
| OCZ                 | 4         | 4      | 0.34%   |
| ASMT                | 4         | 4      | 0.34%   |
| LITEON              | 3         | 3      | 0.26%   |
| IBM/Hitachi         | 3         | 3      | 0.26%   |
| Corsair             | 3         | 3      | 0.26%   |
| Transcend           | 2         | 2      | 0.17%   |
| SPCC                | 2         | 2      | 0.17%   |
| Patriot             | 2         | 2      | 0.17%   |
| KingSpec            | 2         | 2      | 0.17%   |
| Hewlett-Packard     | 2         | 2      | 0.17%   |
| ASMedia             | 2         | 2      | 0.17%   |
| Unknown             | 2         | 2      | 0.17%   |
| WDC WDS2            | 1         | 1      | 0.09%   |
| WD MediaMax         | 1         | 1      | 0.09%   |
| Vaseky              | 1         | 1      | 0.09%   |
| USB3.0              | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| TEXTORM             | 1         | 1      | 0.09%   |
| TCSUNBOW            | 1         | 1      | 0.09%   |
| RSH-339             | 1         | 1      | 0.09%   |
| PNY                 | 1         | 1      | 0.09%   |
| Neo                 | 1         | 1      | 0.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 314       | 335    | 32.88%  |
| WDC                 | 240       | 256    | 25.13%  |
| Hitachi             | 120       | 122    | 12.57%  |
| Toshiba             | 100       | 100    | 10.47%  |
| Samsung Electronics | 77        | 82     | 8.06%   |
| HGST                | 59        | 60     | 6.18%   |
| Maxtor              | 18        | 18     | 1.88%   |
| Fujitsu             | 11        | 11     | 1.15%   |
| IBM/Hitachi         | 3         | 3      | 0.31%   |
| Apple               | 3         | 3      | 0.31%   |
| ASMedia             | 2         | 2      | 0.21%   |
| WD MediaMax         | 1         | 1      | 0.1%    |
| USB3.0              | 1         | 1      | 0.1%    |
| RSH-339             | 1         | 1      | 0.1%    |
| Magnetic Data       | 1         | 1      | 0.1%    |
| Initio              | 1         | 1      | 0.1%    |
| HPE                 | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 1      | 0.1%    |
| Unknown             | 1         | 1      | 0.1%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 885       | 1000   | 80.38%  |
| SSD     | 204       | 210    | 18.53%  |
| NVMe    | 11        | 12     | 1%      |
| Unknown | 1         | 1      | 0.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HD103SJ 1TB                  | 3         | 3      | 7.5%    |
| Apple HDD HTS541010A9E662 1TB                    | 3         | 3      | 7.5%    |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 5%      |
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 5%      |
| WDC WD5000BEVT-22ZAT0 500GB                      | 1         | 1      | 2.5%    |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 2.5%    |
| WDC WD3200BEKT-60KA9T0 320GB                     | 1         | 1      | 2.5%    |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1         | 1      | 2.5%    |
| WDC WD2500BEVT-60ZCT1 250GB                      | 1         | 1      | 2.5%    |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 2.5%    |
| WDC WD1600YS-23SHB0 160GB                        | 1         | 1      | 2.5%    |
| WDC WD1600BEVT-75A23T0 160GB                     | 1         | 1      | 2.5%    |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 2.5%    |
| Toshiba MQ01ABD050 500GB                         | 1         | 1      | 2.5%    |
| Toshiba MK3265GSXN 320GB                         | 1         | 1      | 2.5%    |
| Toshiba MK3256GSY 320GB                          | 1         | 1      | 2.5%    |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 2.5%    |
| Seagate STM31000528AS 1TB                        | 1         | 1      | 2.5%    |
| Seagate ST980811AS 80GB                          | 1         | 1      | 2.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.5%    |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 2.5%    |
| Seagate ST3160215A 160GB                         | 1         | 1      | 2.5%    |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 2.5%    |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 2.5%    |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 2.5%    |
| Samsung Electronics HD502IJ 500GB                | 1         | 1      | 2.5%    |
| Samsung Electronics HD103UJ 1TB                  | 1         | 1      | 2.5%    |
| Intel SSDSA2BW160G3 160GB                        | 1         | 1      | 2.5%    |
| Hitachi HTS725050A7E630 500GB                    | 1         | 1      | 2.5%    |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 2.5%    |
| Hitachi HDS721010DLE630 1TB                      | 1         | 1      | 2.5%    |
| Hitachi HDP725050GLA360 500GB                    | 1         | 1      | 2.5%    |
| GOODRAM SSDPR-PX500-256-80 256GB                 | 1         | 1      | 2.5%    |
| Apple HDD HTS545050A7E362 500GB                  | 1         | 1      | 2.5%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 27.5%   |
| Samsung Electronics | 8         | 8      | 20%     |
| Toshiba             | 6         | 6      | 15%     |
| Seagate             | 5         | 5      | 12.5%   |
| Hitachi             | 4         | 4      | 10%     |
| Apple               | 4         | 4      | 10%     |
| Intel               | 1         | 1      | 2.5%    |
| GOODRAM             | 1         | 1      | 2.5%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3219      | 4907   | 68.39%  |
| Malfunc  | 1078      | 1223   | 22.9%   |
| Detected | 371       | 430    | 7.88%   |
| Failed   | 39        | 40     | 0.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2876      | 58.2%   |
| AMD                              | 863       | 17.46%  |
| Samsung Electronics              | 243       | 4.92%   |
| SanDisk                          | 125       | 2.53%   |
| SK hynix                         | 91        | 1.84%   |
| Nvidia                           | 86        | 1.74%   |
| JMicron Technology               | 83        | 1.68%   |
| ASMedia Technology               | 74        | 1.5%    |
| Marvell Technology Group         | 66        | 1.34%   |
| Phison Electronics               | 63        | 1.27%   |
| Kingston Technology Company      | 63        | 1.27%   |
| Silicon Motion                   | 43        | 0.87%   |
| Micron/Crucial Technology        | 40        | 0.81%   |
| KIOXIA                           | 34        | 0.69%   |
| ADATA Technology                 | 29        | 0.59%   |
| Solid State Storage Technology   | 22        | 0.45%   |
| VIA Technologies                 | 20        | 0.4%    |
| Micron Technology                | 20        | 0.4%    |
| Toshiba America Info Systems     | 17        | 0.34%   |
| Realtek Semiconductor            | 17        | 0.34%   |
| Broadcom / LSI                   | 10        | 0.2%    |
| Union Memory (Shenzhen)          | 9         | 0.18%   |
| Seagate Technology               | 8         | 0.16%   |
| Lite-On Technology               | 6         | 0.12%   |
| Silicon Integrated Systems [SiS] | 5         | 0.1%    |
| Integrated Technology Express    | 5         | 0.1%    |
| LSI Logic / Symbios Logic        | 4         | 0.08%   |
| Shenzhen Longsys Electronics     | 3         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| Silicon Image                    | 2         | 0.04%   |
| Apple                            | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |
| 3ware                            | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 506       | 8.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 220       | 3.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 218       | 3.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 176       | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 145       | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 136       | 2.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 129       | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 123       | 2.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 122       | 2.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 118       | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 114       | 1.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 107       | 1.83%   |
| AMD 400 Series Chipset SATA Controller                                                  | 106       | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 105       | 1.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 93        | 1.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 85        | 1.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 85        | 1.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 75        | 1.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 74        | 1.27%   |
| Samsung NVMe SSD Controller 980                                                         | 73        | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 72        | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 71        | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 70        | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                                  | 69        | 1.18%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 68        | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 67        | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 67        | 1.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 66        | 1.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 65        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 63        | 1.08%   |
| Intel SATA Controller [RAID mode]                                                       | 62        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 62        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 62        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 56        | 0.96%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 54        | 0.93%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 43        | 0.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 39        | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 39        | 0.67%   |
| Nvidia MCP61 SATA Controller                                                            | 37        | 0.63%   |
| AMD FCH SATA Controller D                                                               | 37        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3152      | 62.6%   |
| NVMe | 814       | 16.17%  |
| IDE  | 797       | 15.83%  |
| RAID | 257       | 5.1%    |
| SAS  | 8         | 0.16%   |
| SCSI | 7         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3076      | 75.21%  |
| AMD    | 1014      | 24.79%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 54        | 1.32%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 40        | 0.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 34        | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 31        | 0.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 31        | 0.76%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 30        | 0.73%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 30        | 0.73%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 28        | 0.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 27        | 0.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 26        | 0.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 26        | 0.64%   |
| AMD Ryzen 5 3600 6-Core Processor             | 24        | 0.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 24        | 0.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 23        | 0.56%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 23        | 0.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 22        | 0.54%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 22        | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 22        | 0.54%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 21        | 0.51%   |
| AMD 3020e with Radeon Graphics                | 21        | 0.51%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 20        | 0.49%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 20        | 0.49%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 20        | 0.49%   |
| AMD FX-8350 Eight-Core Processor              | 20        | 0.49%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 19        | 0.46%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 19        | 0.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 18        | 0.44%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 18        | 0.44%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 18        | 0.44%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 18        | 0.44%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 17        | 0.42%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 17        | 0.42%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 17        | 0.42%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 17        | 0.42%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 17        | 0.42%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 16        | 0.39%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 16        | 0.39%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 16        | 0.39%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 0.39%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 16        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 964       | 23.57%  |
| Intel Core i3           | 456       | 11.15%  |
| Intel Core i7           | 414       | 10.12%  |
| Intel Celeron           | 296       | 7.24%   |
| Intel Core 2 Duo        | 227       | 5.55%   |
| AMD Ryzen 5             | 179       | 4.38%   |
| Intel Pentium           | 161       | 3.94%   |
| AMD Ryzen 7             | 133       | 3.25%   |
| Other                   | 119       | 2.91%   |
| Intel Pentium Silver    | 100       | 2.44%   |
| AMD FX                  | 81        | 1.98%   |
| Intel Xeon              | 77        | 1.88%   |
| Intel Pentium Dual-Core | 76        | 1.86%   |
| Intel Core 2 Quad       | 63        | 1.54%   |
| AMD Ryzen 3             | 60        | 1.47%   |
| AMD A8                  | 48        | 1.17%   |
| AMD A6                  | 44        | 1.08%   |
| AMD A4                  | 44        | 1.08%   |
| AMD A10                 | 37        | 0.9%    |
| AMD Athlon              | 32        | 0.78%   |
| AMD E1                  | 30        | 0.73%   |
| Intel Pentium Dual      | 29        | 0.71%   |
| Intel Atom              | 29        | 0.71%   |
| AMD Phenom II X4        | 29        | 0.71%   |
| Intel Core 2            | 28        | 0.68%   |
| AMD Athlon II X2        | 28        | 0.68%   |
| AMD Ryzen 9             | 26        | 0.64%   |
| AMD E                   | 25        | 0.61%   |
| AMD Athlon 64 X2        | 22        | 0.54%   |
| Intel Core i9           | 17        | 0.42%   |
| AMD E2                  | 14        | 0.34%   |
| Intel Genuine           | 12        | 0.29%   |
| AMD Ryzen 5 PRO         | 12        | 0.29%   |
| Intel Pentium Gold      | 11        | 0.27%   |
| AMD Sempron             | 10        | 0.24%   |
| AMD C-60                | 10        | 0.24%   |
| AMD Athlon II X4        | 10        | 0.24%   |
| AMD Phenom              | 9         | 0.22%   |
| AMD Athlon X4           | 9         | 0.22%   |
| AMD Athlon II X3        | 9         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2111      | 51.61%  |
| 4      | 1280      | 31.3%   |
| 6      | 334       | 8.17%   |
| 8      | 183       | 4.47%   |
| 1      | 92        | 2.25%   |
| 3      | 36        | 0.88%   |
| 12     | 22        | 0.54%   |
| 16     | 16        | 0.39%   |
| 10     | 10        | 0.24%   |
| 14     | 2         | 0.05%   |
| 128    | 1         | 0.02%   |
| 44     | 1         | 0.02%   |
| 28     | 1         | 0.02%   |
| 20     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4071      | 99.54%  |
| 2      | 19        | 0.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2226      | 54.43%  |
| 1      | 1852      | 45.28%  |
| 8      | 9         | 0.22%   |
| 4      | 3         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4088      | 99.95%  |
| Unknown        | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 350       | 8.56%   |
| 0x306a9    | 339       | 8.29%   |
| 0x306c3    | 267       | 6.53%   |
| 0x1067a    | 256       | 6.26%   |
| Unknown    | 111       | 2.71%   |
| 0x20655    | 108       | 2.64%   |
| 0x906ea    | 101       | 2.47%   |
| 0x506e3    | 93        | 2.27%   |
| 0x306d4    | 87        | 2.13%   |
| 0x406e3    | 86        | 2.1%    |
| 0x806e9    | 76        | 1.86%   |
| 0x08108109 | 76        | 1.86%   |
| 0x40651    | 75        | 1.83%   |
| 0x6fd      | 71        | 1.74%   |
| 0x906c0    | 68        | 1.66%   |
| 0x08701021 | 66        | 1.61%   |
| 0x806ea    | 65        | 1.59%   |
| 0x706a8    | 65        | 1.59%   |
| 0x906e9    | 63        | 1.54%   |
| 0x30678    | 59        | 1.44%   |
| 0x806ec    | 57        | 1.39%   |
| 0xa0655    | 49        | 1.2%    |
| 0x10676    | 47        | 1.15%   |
| 0x706a1    | 46        | 1.12%   |
| 0x6fb      | 46        | 1.12%   |
| 0x0a50000c | 41        | 1%      |
| 0x06001119 | 41        | 1%      |
| 0x010000c8 | 40        | 0.98%   |
| 0x20652    | 39        | 0.95%   |
| 0xa0653    | 38        | 0.93%   |
| 0x506c9    | 38        | 0.93%   |
| 0x806c1    | 34        | 0.83%   |
| 0x706e5    | 34        | 0.83%   |
| 0x406c4    | 34        | 0.83%   |
| 0x0800820d | 34        | 0.83%   |
| 0x06006705 | 33        | 0.81%   |
| 0x106e5    | 31        | 0.76%   |
| 0x08600106 | 31        | 0.76%   |
| 0x07030105 | 29        | 0.71%   |
| 0x06003106 | 29        | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 430       | 10.51%  |
| SandyBridge      | 365       | 8.92%   |
| Haswell          | 356       | 8.7%    |
| IvyBridge        | 351       | 8.58%   |
| Penryn           | 313       | 7.65%   |
| Skylake          | 188       | 4.6%    |
| Core             | 168       | 4.11%   |
| Westmere         | 159       | 3.89%   |
| Zen+             | 137       | 3.35%   |
| Zen 2            | 125       | 3.06%   |
| Silvermont       | 123       | 3.01%   |
| Piledriver       | 117       | 2.86%   |
| K10              | 113       | 2.76%   |
| Goldmont plus    | 111       | 2.71%   |
| CometLake        | 104       | 2.54%   |
| Broadwell        | 96        | 2.35%   |
| Zen 3            | 92        | 2.25%   |
| Zen              | 84        | 2.05%   |
| Tremont          | 68        | 1.66%   |
| Excavator        | 60        | 1.47%   |
| IceLake          | 58        | 1.42%   |
| Bobcat           | 51        | 1.25%   |
| K8 Hammer        | 47        | 1.15%   |
| Nehalem          | 46        | 1.12%   |
| Puma             | 42        | 1.03%   |
| Unknown          | 40        | 0.98%   |
| Goldmont         | 39        | 0.95%   |
| TigerLake        | 36        | 0.88%   |
| Steamroller      | 35        | 0.86%   |
| Jaguar           | 29        | 0.71%   |
| K10 Llano        | 27        | 0.66%   |
| Bonnell          | 25        | 0.61%   |
| NetBurst         | 16        | 0.39%   |
| Alderlake Hybrid | 15        | 0.37%   |
| Bulldozer        | 14        | 0.34%   |
| K8 & K10 hybrid  | 10        | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2297      | 50.76%  |
| Nvidia                           | 1107      | 24.46%  |
| AMD                              | 1099      | 24.29%  |
| Matrox Electronics Systems       | 8         | 0.18%   |
| ASPEED Technology                | 5         | 0.11%   |
| Silicon Integrated Systems [SiS] | 4         | 0.09%   |
| VIA Technologies                 | 3         | 0.07%   |
| Conexant Systems                 | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 289       | 6.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 188       | 4.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 115       | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 112       | 2.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 100       | 2.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 84        | 1.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 81        | 1.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 75        | 1.62%   |
| Intel HD Graphics 620                                                                    | 73        | 1.58%   |
| Intel HD Graphics 5500                                                                   | 73        | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 69        | 1.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 68        | 1.47%   |
| Intel JasperLake [UHD Graphics]                                                          | 68        | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 67        | 1.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 65        | 1.4%    |
| Intel HD Graphics 530                                                                    | 63        | 1.36%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 59        | 1.27%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 56        | 1.21%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 53        | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 53        | 1.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 52        | 1.12%   |
| Intel UHD Graphics 620                                                                   | 51        | 1.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 51        | 1.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 48        | 1.04%   |
| AMD Renoir                                                                               | 48        | 1.04%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 44        | 0.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 42        | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 42        | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 40        | 0.86%   |
| Intel HD Graphics 630                                                                    | 40        | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 39        | 0.84%   |
| Nvidia GT218 [GeForce 210]                                                               | 36        | 0.78%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 33        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 31        | 0.67%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 30        | 0.65%   |
| Intel HD Graphics 500                                                                    | 30        | 0.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 29        | 0.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 28        | 0.6%    |
| AMD Lucienne                                                                             | 28        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1884      | 46.06%  |
| 1 x AMD                  | 956       | 23.37%  |
| 1 x Nvidia               | 774       | 18.92%  |
| Intel + Nvidia           | 305       | 7.46%   |
| Intel + AMD              | 68        | 1.66%   |
| 2 x AMD                  | 56        | 1.37%   |
| AMD + Nvidia             | 19        | 0.46%   |
| 2 x Nvidia               | 6         | 0.15%   |
| 1 x Matrox               | 6         | 0.15%   |
| 1 x SiS                  | 4         | 0.1%    |
| 1 x ASPEED               | 4         | 0.1%    |
| 1 x VIA                  | 3         | 0.07%   |
| 3 x AMD                  | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.02%   |
| Nvidia + Matrox          | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |
| Intel + Conexant Systems | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3986      | 97.46%  |
| Unknown     | 101       | 2.47%   |
| Proprietary | 3         | 0.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2029      | 49.61%  |
| 0.01-0.5   | 612       | 14.96%  |
| 1.01-2.0   | 542       | 13.25%  |
| 0.51-1.0   | 449       | 10.98%  |
| 3.01-4.0   | 201       | 4.91%   |
| 7.01-8.0   | 132       | 3.23%   |
| 5.01-6.0   | 71        | 1.74%   |
| 2.01-3.0   | 32        | 0.78%   |
| 8.01-16.0  | 18        | 0.44%   |
| 16.01-24.0 | 4         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 555       | 13.53%  |
| AU Optronics            | 449       | 10.95%  |
| LG Display              | 379       | 9.24%   |
| BOE                     | 308       | 7.51%   |
| Chimei Innolux          | 304       | 7.41%   |
| Goldstar                | 240       | 5.85%   |
| Dell                    | 210       | 5.12%   |
| Hewlett-Packard         | 205       | 5%      |
| Acer                    | 156       | 3.8%    |
| Philips                 | 136       | 3.32%   |
| AOC                     | 128       | 3.12%   |
| BenQ                    | 89        | 2.17%   |
| Lenovo                  | 85        | 2.07%   |
| Chi Mei Optoelectronics | 72        | 1.76%   |
| Ancor Communications    | 71        | 1.73%   |
| ViewSonic               | 58        | 1.41%   |
| Apple                   | 51        | 1.24%   |
| Iiyama                  | 39        | 0.95%   |
| Sharp                   | 33        | 0.8%    |
| Sony                    | 29        | 0.71%   |
| Eizo                    | 28        | 0.68%   |
| InfoVision              | 26        | 0.63%   |
| LG Philips              | 25        | 0.61%   |
| ASUSTek Computer        | 23        | 0.56%   |
| Toshiba                 | 19        | 0.46%   |
| NEC Computers           | 19        | 0.46%   |
| HannStar                | 17        | 0.41%   |
| PANDA                   | 16        | 0.39%   |
| CPT                     | 16        | 0.39%   |
| Fujitsu Siemens         | 15        | 0.37%   |
| Panasonic               | 13        | 0.32%   |
| Hitachi                 | 11        | 0.27%   |
| Unknown                 | 10        | 0.24%   |
| Sceptre Tech            | 10        | 0.24%   |
| ___                     | 9         | 0.22%   |
| TCL                     | 9         | 0.22%   |
| Vestel Elektronik       | 8         | 0.2%    |
| MSI                     | 8         | 0.2%    |
| Medion                  | 8         | 0.2%    |
| Vizio                   | 7         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                     | 33        | 0.8%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 23        | 0.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.53%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                         | 22        | 0.53%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 0.48%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 17        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 17        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 16        | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 15        | 0.36%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.36%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.34%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 14        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.31%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 13        | 0.31%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.31%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 12        | 0.29%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch            | 12        | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 11        | 0.27%   |
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 11        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.27%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 10        | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 10        | 0.24%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 10        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.24%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                     | 10        | 0.24%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 10        | 0.24%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                          | 10        | 0.24%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 9         | 0.22%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 9         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 9         | 0.22%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 9         | 0.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 9         | 0.22%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch     | 8         | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 8         | 0.19%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 8         | 0.19%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 8         | 0.19%   |
| BOE LCD Monitor BOE097B 1366x768 256x144mm 11.6-inch                     | 8         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1552      | 38.55%  |
| 1366x768 (WXGA)    | 1123      | 27.89%  |
| 3840x2160 (4K)     | 212       | 5.27%   |
| 1600x900 (HD+)     | 206       | 5.12%   |
| 1280x1024 (SXGA)   | 177       | 4.4%    |
| 2560x1440 (QHD)    | 129       | 3.2%    |
| 1440x900 (WXGA+)   | 127       | 3.15%   |
| 1680x1050 (WSXGA+) | 117       | 2.91%   |
| 1280x800 (WXGA)    | 104       | 2.58%   |
| 1920x1200 (WUXGA)  | 72        | 1.79%   |
| 1360x768           | 44        | 1.09%   |
| 3440x1440          | 25        | 0.62%   |
| 2560x1080          | 24        | 0.6%    |
| 1920x540           | 15        | 0.37%   |
| 1024x768 (XGA)     | 13        | 0.32%   |
| 3200x1800 (QHD+)   | 12        | 0.3%    |
| 2560x1600          | 12        | 0.3%    |
| 1600x1200          | 8         | 0.2%    |
| 2160x1440          | 6         | 0.15%   |
| 1280x720 (HD)      | 6         | 0.15%   |
| 2880x1800          | 4         | 0.1%    |
| 2288x1287          | 4         | 0.1%    |
| 2048x1152          | 4         | 0.1%    |
| 1920x1280          | 4         | 0.1%    |
| 1280x960           | 4         | 0.1%    |
| 1024x600           | 4         | 0.1%    |
| 2736x1824          | 3         | 0.07%   |
| 3840x1080          | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |
| 1680x945           | 2         | 0.05%   |
| 1280x768           | 2         | 0.05%   |
| 3840x2400          | 1         | 0.02%   |
| 3840x1600          | 1         | 0.02%   |
| 3840x1200          | 1         | 0.02%   |
| 3456x2160          | 1         | 0.02%   |
| 3200x2000          | 1         | 0.02%   |
| 1400x1050          | 1         | 0.02%   |
| Unknown            | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 951       | 23.18%  |
| 13      | 350       | 8.53%   |
| 23      | 313       | 7.63%   |
| 27      | 302       | 7.36%   |
| 21      | 302       | 7.36%   |
| 17      | 279       | 6.8%    |
| 24      | 249       | 6.07%   |
| 14      | 227       | 5.53%   |
| 19      | 169       | 4.12%   |
| 11      | 138       | 3.36%   |
| 18      | 128       | 3.12%   |
| 31      | 101       | 2.46%   |
| 22      | 90        | 2.19%   |
| 12      | 90        | 2.19%   |
| 20      | 71        | 1.73%   |
| 84      | 43        | 1.05%   |
| 34      | 43        | 1.05%   |
| 32      | 27        | 0.66%   |
| Unknown | 24        | 0.59%   |
| 72      | 18        | 0.44%   |
| 54      | 18        | 0.44%   |
| 26      | 17        | 0.41%   |
| 40      | 15        | 0.37%   |
| 25      | 15        | 0.37%   |
| 16      | 13        | 0.32%   |
| 65      | 12        | 0.29%   |
| 52      | 10        | 0.24%   |
| 10      | 10        | 0.24%   |
| 48      | 8         | 0.2%    |
| 39      | 7         | 0.17%   |
| 33      | 6         | 0.15%   |
| 74      | 5         | 0.12%   |
| 47      | 5         | 0.12%   |
| 43      | 5         | 0.12%   |
| 142     | 4         | 0.1%    |
| 46      | 4         | 0.1%    |
| 42      | 4         | 0.1%    |
| 37      | 4         | 0.1%    |
| 35      | 4         | 0.1%    |
| 29      | 4         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1424      | 35.03%  |
| 501-600        | 838       | 20.62%  |
| 401-500        | 670       | 16.48%  |
| 201-300        | 410       | 10.09%  |
| 351-400        | 312       | 7.68%   |
| 601-700        | 134       | 3.3%    |
| 701-800        | 76        | 1.87%   |
| 1001-1500      | 68        | 1.67%   |
| 1501-2000      | 66        | 1.62%   |
| 801-900        | 31        | 0.76%   |
| Unknown        | 24        | 0.59%   |
| 901-1000       | 8         | 0.2%    |
| More than 2000 | 4         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3159      | 80.57%  |
| 16/10   | 465       | 11.86%  |
| 5/4     | 171       | 4.36%   |
| 21/9    | 47        | 1.2%    |
| 4/3     | 38        | 0.97%   |
| 3/2     | 26        | 0.66%   |
| 6/5     | 4         | 0.1%    |
| 1.00    | 4         | 0.1%    |
| 32/9    | 3         | 0.08%   |
| 1.96    | 2         | 0.05%   |
| 3.20    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 945       | 23.16%  |
| 201-250        | 771       | 18.9%   |
| 81-90          | 427       | 10.47%  |
| 151-200        | 334       | 8.19%   |
| 301-350        | 316       | 7.75%   |
| 141-150        | 196       | 4.8%    |
| 351-500        | 182       | 4.46%   |
| 71-80          | 159       | 3.9%    |
| 121-130        | 153       | 3.75%   |
| 51-60          | 138       | 3.38%   |
| More than 1000 | 124       | 3.04%   |
| 251-300        | 111       | 2.72%   |
| 61-70          | 80        | 1.96%   |
| 501-1000       | 53        | 1.3%    |
| 131-140        | 37        | 0.91%   |
| Unknown        | 24        | 0.59%   |
| 111-120        | 14        | 0.34%   |
| 41-50          | 10        | 0.25%   |
| 91-100         | 6         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1620      | 40.35%  |
| 101-120       | 1293      | 32.2%   |
| 121-160       | 798       | 19.88%  |
| 161-240       | 152       | 3.79%   |
| 1-50          | 106       | 2.64%   |
| Unknown       | 24        | 0.6%    |
| More than 240 | 22        | 0.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3714      | 90.81%  |
| 2     | 303       | 7.41%   |
| 0     | 53        | 1.3%    |
| 3     | 18        | 0.44%   |
| 7     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2395      | 40.24%  |
| Intel                             | 1693      | 28.44%  |
| Qualcomm Atheros                  | 781       | 13.12%  |
| Broadcom                          | 293       | 4.92%   |
| Ralink Technology                 | 91        | 1.53%   |
| Ralink                            | 82        | 1.38%   |
| Marvell Technology Group          | 78        | 1.31%   |
| Nvidia                            | 68        | 1.14%   |
| Broadcom Limited                  | 63        | 1.06%   |
| TP-Link                           | 50        | 0.84%   |
| MediaTek                          | 29        | 0.49%   |
| Samsung Electronics               | 28        | 0.47%   |
| Huawei Technologies               | 20        | 0.34%   |
| Qualcomm Atheros Communications   | 19        | 0.32%   |
| JMicron Technology                | 19        | 0.32%   |
| Dell                              | 18        | 0.3%    |
| Ericsson Business Mobile Networks | 17        | 0.29%   |
| D-Link System                     | 14        | 0.24%   |
| ASIX Electronics                  | 14        | 0.24%   |
| NetGear                           | 13        | 0.22%   |
| D-Link                            | 13        | 0.22%   |
| Motorola PCS                      | 12        | 0.2%    |
| Sierra Wireless                   | 10        | 0.17%   |
| VIA Technologies                  | 9         | 0.15%   |
| Hewlett-Packard                   | 8         | 0.13%   |
| Aquantia                          | 8         | 0.13%   |
| Microsoft                         | 7         | 0.12%   |
| Xiaomi                            | 6         | 0.1%    |
| Edimax Technology                 | 6         | 0.1%    |
| Belkin Components                 | 6         | 0.1%    |
| ASUSTek Computer                  | 6         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 5         | 0.08%   |
| IMC Networks                      | 5         | 0.08%   |
| DisplayLink                       | 5         | 0.08%   |
| AVM                               | 5         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.05%   |
| Spreadtrum Communications         | 3         | 0.05%   |
| Mellanox Technologies             | 3         | 0.05%   |
| Linksys                           | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1695      | 24.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 315       | 4.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 174       | 2.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 116       | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 104       | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 102       | 1.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 100       | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 96        | 1.39%   |
| Intel Wi-Fi 6 AX200                                               | 96        | 1.39%   |
| Intel Wireless 8265 / 8275                                        | 92        | 1.34%   |
| Intel Wireless 7265                                               | 86        | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 77        | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 72        | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 72        | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 69        | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 68        | 0.99%   |
| Intel Wireless 3165                                               | 63        | 0.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 60        | 0.87%   |
| Intel Wireless 7260                                               | 60        | 0.87%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 60        | 0.87%   |
| Intel I211 Gigabit Network Connection                             | 59        | 0.86%   |
| Intel 82579V Gigabit Network Connection                           | 55        | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 53        | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 52        | 0.76%   |
| Intel Wireless 8260                                               | 50        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                              | 50        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 46        | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 45        | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 43        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 42        | 0.61%   |
| Intel Wireless 3160                                               | 39        | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 37        | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 35        | 0.51%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 34        | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 34        | 0.49%   |
| Intel Ethernet Connection (7) I219-V                              | 33        | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 32        | 0.46%   |
| Ralink MT7601U Wireless Adapter                                   | 32        | 0.46%   |
| Nvidia MCP61 Ethernet                                             | 31        | 0.45%   |
| Intel Ethernet Controller I225-V                                  | 30        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1172      | 40.15%  |
| Qualcomm Atheros                      | 623       | 21.34%  |
| Realtek Semiconductor                 | 561       | 19.22%  |
| Broadcom                              | 175       | 6%      |
| Ralink Technology                     | 91        | 3.12%   |
| Ralink                                | 82        | 2.81%   |
| TP-Link                               | 35        | 1.2%    |
| Broadcom Limited                      | 28        | 0.96%   |
| MediaTek                              | 27        | 0.92%   |
| Qualcomm Atheros Communications       | 19        | 0.65%   |
| D-Link                                | 13        | 0.45%   |
| NetGear                               | 11        | 0.38%   |
| Sierra Wireless                       | 10        | 0.34%   |
| Dell                                  | 10        | 0.34%   |
| Microsoft                             | 7         | 0.24%   |
| D-Link System                         | 7         | 0.24%   |
| Edimax Technology                     | 6         | 0.21%   |
| ASUSTek Computer                      | 6         | 0.21%   |
| IMC Networks                          | 5         | 0.17%   |
| Belkin Components                     | 5         | 0.17%   |
| AVM                                   | 5         | 0.17%   |
| Marvell Technology Group              | 4         | 0.14%   |
| Hewlett-Packard                       | 4         | 0.14%   |
| Linksys                               | 3         | 0.1%    |
| Chu Yuen Enterprise                   | 2         | 0.07%   |
| ZyDAS                                 | 1         | 0.03%   |
| TRENDnet                              | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Qcom                                  | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Logitec                               | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 116       | 3.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 104       | 3.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 102       | 3.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 100       | 3.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 96        | 3.28%   |
| Intel Wi-Fi 6 AX200                                                     | 96        | 3.28%   |
| Intel Wireless 8265 / 8275                                              | 92        | 3.15%   |
| Intel Wireless 7265                                                     | 86        | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 72        | 2.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 69        | 2.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 68        | 2.32%   |
| Intel Wireless 3165                                                     | 63        | 2.15%   |
| Intel Wireless 7260                                                     | 60        | 2.05%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 60        | 2.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 53        | 1.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 52        | 1.78%   |
| Intel Wireless 8260                                                     | 50        | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 45        | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 43        | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 42        | 1.44%   |
| Intel Wireless 3160                                                     | 39        | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 37        | 1.26%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 35        | 1.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 34        | 1.16%   |
| Ralink MT7601U Wireless Adapter                                         | 32        | 1.09%   |
| Intel WiFi Link 5100                                                    | 28        | 0.96%   |
| Intel Centrino Wireless-N 2230                                          | 28        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 27        | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 27        | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 27        | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 26        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 26        | 0.89%   |
| Intel Wi-Fi 6 AX201                                                     | 25        | 0.85%   |
| Intel Centrino Ultimate-N 6300                                          | 25        | 0.85%   |
| Intel Wireless-AC 9260                                                  | 24        | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 24        | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 23        | 0.79%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 21        | 0.72%   |
| Realtek 802.11n WLAN Adapter                                            | 20        | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 20        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2177      | 56.78%  |
| Intel                             | 902       | 23.53%  |
| Qualcomm Atheros                  | 234       | 6.1%    |
| Broadcom                          | 162       | 4.23%   |
| Marvell Technology Group          | 74        | 1.93%   |
| Nvidia                            | 68        | 1.77%   |
| Broadcom Limited                  | 35        | 0.91%   |
| Samsung Electronics               | 28        | 0.73%   |
| JMicron Technology                | 19        | 0.5%    |
| TP-Link                           | 15        | 0.39%   |
| Huawei Technologies               | 15        | 0.39%   |
| ASIX Electronics                  | 14        | 0.37%   |
| VIA Technologies                  | 9         | 0.23%   |
| Aquantia                          | 8         | 0.21%   |
| Motorola PCS                      | 7         | 0.18%   |
| D-Link System                     | 7         | 0.18%   |
| Xiaomi                            | 6         | 0.16%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.13%   |
| DisplayLink                       | 5         | 0.13%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 3         | 0.08%   |
| Spreadtrum Communications         | 3         | 0.08%   |
| HTC (High Tech Computer)          | 3         | 0.08%   |
| Hewlett-Packard                   | 3         | 0.08%   |
| Google                            | 3         | 0.08%   |
| T & A Mobile Phones               | 2         | 0.05%   |
| Qualcomm                          | 2         | 0.05%   |
| OPPO Electronics                  | 2         | 0.05%   |
| NetGear                           | 2         | 0.05%   |
| Mellanox Technologies             | 2         | 0.05%   |
| MediaTek                          | 2         | 0.05%   |
| ICS Advent                        | 2         | 0.05%   |
| 3Com                              | 2         | 0.05%   |
| vivo                              | 1         | 0.03%   |
| Sundance Technology Inc / IC Plus | 1         | 0.03%   |
| Netchip Technology                | 1         | 0.03%   |
| Lenovo                            | 1         | 0.03%   |
| Emulex                            | 1         | 0.03%   |
| Davicom Semiconductor             | 1         | 0.03%   |
| Belkin Components                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1695      | 43.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 315       | 8.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 174       | 4.45%   |
| Intel Ethernet Connection I217-LM                                              | 77        | 1.97%   |
| Realtek RTL8125 2.5GbE Controller                                              | 72        | 1.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 60        | 1.53%   |
| Intel I211 Gigabit Network Connection                                          | 59        | 1.51%   |
| Intel 82579V Gigabit Network Connection                                        | 55        | 1.41%   |
| Intel Ethernet Connection (2) I219-V                                           | 50        | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 46        | 1.18%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 34        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                                           | 33        | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 32        | 0.82%   |
| Nvidia MCP61 Ethernet                                                          | 31        | 0.79%   |
| Intel Ethernet Controller I225-V                                               | 30        | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 28        | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 26        | 0.66%   |
| Intel Ethernet Connection I217-V                                               | 25        | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 24        | 0.61%   |
| Intel 82577LM Gigabit Network Connection                                       | 24        | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                          | 23        | 0.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 23        | 0.59%   |
| Intel Ethernet Connection I218-LM                                              | 22        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                          | 21        | 0.54%   |
| Intel Ethernet Connection I219-LM                                              | 20        | 0.51%   |
| Intel 82567LM Gigabit Network Connection                                       | 20        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 18        | 0.46%   |
| Intel 82574L Gigabit Network Connection                                        | 17        | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 17        | 0.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 17        | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 15        | 0.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 15        | 0.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 14        | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 14        | 0.36%   |
| Nvidia MCP79 Ethernet                                                          | 14        | 0.36%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 13        | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 13        | 0.33%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 13        | 0.33%   |
| Intel Ethernet Connection (2) I218-V                                           | 13        | 0.33%   |
| Intel 82578DM Gigabit Network Connection                                       | 13        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3669      | 56.2%   |
| WiFi     | 2815      | 43.12%  |
| Modem    | 34        | 0.52%   |
| Unknown  | 10        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2232      | 55.77%  |
| WiFi     | 1769      | 44.2%   |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2132      | 52.13%  |
| 1     | 1852      | 45.28%  |
| 3     | 61        | 1.49%   |
| 0     | 36        | 0.88%   |
| 4     | 7         | 0.17%   |
| 10    | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2920      | 71.39%  |
| Yes  | 1170      | 28.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 876       | 41.79%  |
| Realtek Semiconductor           | 219       | 10.45%  |
| Qualcomm Atheros Communications | 192       | 9.16%   |
| Broadcom                        | 139       | 6.63%   |
| Cambridge Silicon Radio         | 134       | 6.39%   |
| Lite-On Technology              | 97        | 4.63%   |
| IMC Networks                    | 87        | 4.15%   |
| Foxconn / Hon Hai               | 64        | 3.05%   |
| Apple                           | 59        | 2.81%   |
| Dell                            | 44        | 2.1%    |
| Toshiba                         | 33        | 1.57%   |
| ASUSTek Computer                | 32        | 1.53%   |
| Hewlett-Packard                 | 27        | 1.29%   |
| Ralink                          | 26        | 1.24%   |
| Realtek                         | 8         | 0.38%   |
| MediaTek                        | 7         | 0.33%   |
| Alps Electric                   | 7         | 0.33%   |
| Ralink Technology               | 6         | 0.29%   |
| Marvell Semiconductor           | 4         | 0.19%   |
| Fujitsu                         | 4         | 0.19%   |
| Edimax Technology               | 4         | 0.19%   |
| TP-Link                         | 3         | 0.14%   |
| Foxconn International           | 3         | 0.14%   |
| Askey Computer                  | 3         | 0.14%   |
| Unknown                         | 3         | 0.14%   |
| Unknown                         | 2         | 0.1%    |
| Integrated System Solution      | 2         | 0.1%    |
| Chicony Electronics             | 2         | 0.1%    |
| Belkin Components               | 2         | 0.1%    |
| USI                             | 1         | 0.05%   |
| Taiyo Yuden                     | 1         | 0.05%   |
| SINO WEALTH                     | 1         | 0.05%   |
| Primax Electronics              | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Dynex                           | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 393       | 18.75%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 134       | 6.39%   |
| Realtek Bluetooth Radio                                                             | 132       | 6.3%    |
| Intel AX201 Bluetooth                                                               | 123       | 5.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 115       | 5.49%   |
| Intel AX200 Bluetooth                                                               | 94        | 4.48%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 75        | 3.58%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 67        | 3.2%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 50        | 2.39%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 39        | 1.86%   |
| IMC Networks Bluetooth Radio                                                        | 39        | 1.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 36        | 1.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 35        | 1.67%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 31        | 1.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 30        | 1.43%   |
| IMC Networks Bluetooth Device                                                       | 29        | 1.38%   |
| Lite-On Bluetooth Device                                                            | 28        | 1.34%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 28        | 1.34%   |
| Ralink RT3290 Bluetooth                                                             | 26        | 1.24%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 25        | 1.19%   |
| Dell DW375 Bluetooth Module                                                         | 24        | 1.15%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 23        | 1.1%    |
| Apple Bluetooth Host Controller                                                     | 21        | 1%      |
| Lite-On Atheros AR3012 Bluetooth                                                    | 20        | 0.95%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 20        | 0.95%   |
| Apple Bluetooth USB Host Controller                                                 | 19        | 0.91%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 18        | 0.86%   |
| Intel AX210 Bluetooth                                                               | 17        | 0.81%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 16        | 0.76%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 14        | 0.67%   |
| Realtek RTL8723B Bluetooth                                                          | 12        | 0.57%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 11        | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 10        | 0.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 10        | 0.48%   |
| Toshiba RT Bluetooth Radio                                                          | 9         | 0.43%   |
| Broadcom BCM2045 Bluetooth                                                          | 9         | 0.43%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 9         | 0.43%   |
| ASUS Bluetooth Device                                                               | 9         | 0.43%   |
| Realtek Bluetooth Radio                                                             | 8         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2989      | 55.02%  |
| AMD                                          | 1215      | 22.36%  |
| Nvidia                                       | 862       | 15.87%  |
| C-Media Electronics                          | 78        | 1.44%   |
| Creative Labs                                | 48        | 0.88%   |
| Logitech                                     | 34        | 0.63%   |
| Texas Instruments                            | 20        | 0.37%   |
| Creative Technology                          | 15        | 0.28%   |
| JMTek                                        | 14        | 0.26%   |
| Generalplus Technology                       | 12        | 0.22%   |
| ASUSTek Computer                             | 10        | 0.18%   |
| VIA Technologies                             | 7         | 0.13%   |
| GN Netcom                                    | 7         | 0.13%   |
| XMOS                                         | 5         | 0.09%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.09%   |
| Tenx Technology                              | 4         | 0.07%   |
| Realtek Semiconductor                        | 4         | 0.07%   |
| Plantronics                                  | 4         | 0.07%   |
| Focusrite-Novation                           | 4         | 0.07%   |
| Blue Microphones                             | 4         | 0.07%   |
| SteelSeries ApS                              | 3         | 0.06%   |
| Sony                                         | 3         | 0.06%   |
| Samson Technologies                          | 3         | 0.06%   |
| Razer USA                                    | 3         | 0.06%   |
| Kingston Technology                          | 3         | 0.06%   |
| Hewlett-Packard                              | 3         | 0.06%   |
| Apple                                        | 3         | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.04%   |
| Trust                                        | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.04%   |
| ROCCAT                                       | 2         | 0.04%   |
| PreSonus Audio Electronics                   | 2         | 0.04%   |
| No brand                                     | 2         | 0.04%   |
| M-Audio                                      | 2         | 0.04%   |
| Lenovo                                       | 2         | 0.04%   |
| KTMicro                                      | 2         | 0.04%   |
| GYROCOM C&C                                  | 2         | 0.04%   |
| FiiO Electronics Technology                  | 2         | 0.04%   |
| ESS Technology                               | 2         | 0.04%   |
| Dell                                         | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 358       | 5.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 336       | 5.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 288       | 4.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 238       | 3.66%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 223       | 3.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 217       | 3.34%   |
| AMD FCH Azalia Controller                                                                         | 202       | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 186       | 2.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 175       | 2.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 162       | 2.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 142       | 2.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 141       | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 122       | 1.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 110       | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 107       | 1.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 106       | 1.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 104       | 1.6%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 100       | 1.54%   |
| Intel Broadwell-U Audio Controller                                                                | 91        | 1.4%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 89        | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 88        | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 88        | 1.35%   |
| Intel 200 Series PCH HD Audio                                                                     | 79        | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                                          | 78        | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 76        | 1.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 76        | 1.17%   |
| Intel 8 Series HD Audio Controller                                                                | 76        | 1.17%   |
| Nvidia High Definition Audio Controller                                                           | 71        | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 70        | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 69        | 1.06%   |
| Intel Jasper Lake HD Audio                                                                        | 68        | 1.05%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 63        | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 60        | 0.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 60        | 0.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 58        | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 56        | 0.86%   |
| Intel Audio device                                                                                | 51        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 49        | 0.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 44        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 42        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 908       | 18.68%  |
| SK hynix            | 762       | 15.68%  |
| Unknown             | 635       | 13.07%  |
| Kingston            | 610       | 12.55%  |
| Micron Technology   | 404       | 8.31%   |
| Crucial             | 247       | 5.08%   |
| Corsair             | 199       | 4.09%   |
| G.Skill             | 157       | 3.23%   |
| A-DATA Technology   | 114       | 2.35%   |
| Ramaxel Technology  | 97        | 2%      |
| Elpida              | 83        | 1.71%   |
| Unknown             | 65        | 1.34%   |
| Smart               | 63        | 1.3%    |
| Nanya Technology    | 62        | 1.28%   |
| Unknown (ABCD)      | 45        | 0.93%   |
| Patriot             | 43        | 0.88%   |
| Team                | 35        | 0.72%   |
| GOODRAM             | 21        | 0.43%   |
| AMD                 | 20        | 0.41%   |
| Transcend           | 18        | 0.37%   |
| Teikon              | 18        | 0.37%   |
| Silicon Power       | 12        | 0.25%   |
| ASint Technology    | 12        | 0.25%   |
| Apacer              | 12        | 0.25%   |
| CSX                 | 11        | 0.23%   |
| Qimonda             | 10        | 0.21%   |
| PNY                 | 8         | 0.16%   |
| Unifosa             | 7         | 0.14%   |
| Kingmax             | 7         | 0.14%   |
| GeIL                | 7         | 0.14%   |
| Avant               | 7         | 0.14%   |
| Smart Brazil        | 6         | 0.12%   |
| High Bridge         | 6         | 0.12%   |
| Goldkey             | 6         | 0.12%   |
| Toshiba             | 5         | 0.1%    |
| Multilaser          | 5         | 0.1%    |
| Super Talent        | 4         | 0.08%   |
| Sesame              | 4         | 0.08%   |
| OM Nanotech         | 4         | 0.08%   |
| Kllisre             | 4         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 65        | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 56        | 1.06%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 52        | 0.99%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 50        | 0.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 50        | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 44        | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 44        | 0.83%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 44        | 0.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 40        | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 33        | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 33        | 0.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 32        | 0.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 32        | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 31        | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 31        | 0.59%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 30        | 0.57%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 30        | 0.57%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 24        | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 23        | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 21        | 0.4%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 20        | 0.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 20        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 19        | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.36%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 19        | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 18        | 0.34%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 18        | 0.34%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                         | 18        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.34%   |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s             | 18        | 0.34%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s            | 18        | 0.34%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 17        | 0.32%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 17        | 0.32%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 17        | 0.32%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.32%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 0.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.32%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 17        | 0.32%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 17        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 1849      | 44.79%  |
| DDR4    | 1371      | 33.21%  |
| DDR2    | 323       | 7.82%   |
| SDRAM   | 190       | 4.6%    |
| Unknown | 176       | 4.26%   |
| LPDDR4  | 138       | 3.34%   |
| DDR     | 33        | 0.8%    |
| LPDDR3  | 31        | 0.75%   |
| DRAM    | 12        | 0.29%   |
| DDR5    | 5         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2132      | 52.43%  |
| DIMM         | 1777      | 43.7%   |
| Row Of Chips | 136       | 3.34%   |
| Chip         | 12        | 0.3%    |
| Unknown      | 4         | 0.1%    |
| FB-DIMM      | 3         | 0.07%   |
| RIMM         | 2         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1691      | 37.1%   |
| 8192  | 1390      | 30.5%   |
| 2048  | 907       | 19.9%   |
| 16384 | 282       | 6.19%   |
| 1024  | 210       | 4.61%   |
| 32768 | 56        | 1.23%   |
| 512   | 21        | 0.46%   |
| 65536 | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1170      | 25.62%  |
| 1333    | 472       | 10.34%  |
| 2667    | 421       | 9.22%   |
| 3200    | 347       | 7.6%    |
| 2400    | 341       | 7.47%   |
| 1334    | 206       | 4.51%   |
| 800     | 176       | 3.85%   |
| 667     | 164       | 3.59%   |
| 2133    | 152       | 3.33%   |
| Unknown | 130       | 2.85%   |
| 3600    | 106       | 2.32%   |
| 1067    | 93        | 2.04%   |
| 1867    | 87        | 1.91%   |
| 4267    | 60        | 1.31%   |
| 2666    | 57        | 1.25%   |
| 1866    | 54        | 1.18%   |
| 1066    | 46        | 1.01%   |
| 2048    | 37        | 0.81%   |
| 4199    | 35        | 0.77%   |
| 3266    | 33        | 0.72%   |
| 533     | 33        | 0.72%   |
| 3400    | 28        | 0.61%   |
| 3000    | 28        | 0.61%   |
| 975     | 23        | 0.5%    |
| 400     | 22        | 0.48%   |
| 1800    | 21        | 0.46%   |
| 2933    | 18        | 0.39%   |
| 3866    | 16        | 0.35%   |
| 3733    | 14        | 0.31%   |
| 3466    | 13        | 0.28%   |
| 333     | 13        | 0.28%   |
| 8400    | 11        | 0.24%   |
| 2800    | 10        | 0.22%   |
| 49926   | 8         | 0.18%   |
| 4266    | 8         | 0.18%   |
| 3066    | 8         | 0.18%   |
| 1639    | 8         | 0.18%   |
| 2000    | 7         | 0.15%   |
| 3800    | 6         | 0.13%   |
| 1648    | 6         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 58        | 39.46%  |
| Brother Industries    | 32        | 21.77%  |
| Canon                 | 22        | 14.97%  |
| Samsung Electronics   | 12        | 8.16%   |
| Seiko Epson           | 9         | 6.12%   |
| Lexmark International | 5         | 3.4%    |
| Xerox                 | 2         | 1.36%   |
| Kyocera               | 2         | 1.36%   |
| Ricoh                 | 1         | 0.68%   |
| QinHeng Electronics   | 1         | 0.68%   |
| Prolific Technology   | 1         | 0.68%   |
| NXP Semiconductors    | 1         | 0.68%   |
| Citizen               | 1         | 0.68%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Brother DCP-7055W                            | 4         | 2.72%   |
| HP LaserJet 1010                             | 3         | 2.04%   |
| Seiko Epson ET-4760 Series                   | 2         | 1.36%   |
| Samsung SCX-3400 Series                      | 2         | 1.36%   |
| Samsung M2070 Series                         | 2         | 1.36%   |
| Samsung M2020 Series                         | 2         | 1.36%   |
| Samsung CLP-310 Color Laser Printer          | 2         | 1.36%   |
| HP OfficeJet Pro 7740 series                 | 2         | 1.36%   |
| HP LaserJet P1005                            | 2         | 1.36%   |
| HP LaserJet 1200                             | 2         | 1.36%   |
| HP LaserJet 1020                             | 2         | 1.36%   |
| HP LaserJet 1018                             | 2         | 1.36%   |
| HP Ink Tank Wireless 410 series              | 2         | 1.36%   |
| HP ENVY 4520 series                          | 2         | 1.36%   |
| HP ENVY 4500 series                          | 2         | 1.36%   |
| HP DeskJet 2700 series                       | 2         | 1.36%   |
| HP DeskJet 2620 All-in-One Printer           | 2         | 1.36%   |
| HP Deskjet 1050 J410                         | 2         | 1.36%   |
| Canon TS5100 series                          | 2         | 1.36%   |
| Brother MFC-L2710DW series                   | 2         | 1.36%   |
| Brother MFC-J470DW                           | 2         | 1.36%   |
| Brother DCP-T310                             | 2         | 1.36%   |
| Xerox Phaser 6510                            | 1         | 0.68%   |
| Xerox Phaser 6010N                           | 1         | 0.68%   |
| Seiko Epson XP-2100 Series                   | 1         | 0.68%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.68%   |
| Seiko Epson L365 Series                      | 1         | 0.68%   |
| Seiko Epson L355 Series                      | 1         | 0.68%   |
| Seiko Epson L3210 Series                     | 1         | 0.68%   |
| Seiko Epson L120 Series                      | 1         | 0.68%   |
| Seiko Epson ET-3750 Series                   | 1         | 0.68%   |
| Samsung ML-2850 Series                       | 1         | 0.68%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 0.68%   |
| Samsung M267x 287x Series                    | 1         | 0.68%   |
| Samsung CLP-325 Color Laser Printer          | 1         | 0.68%   |
| Ricoh SP 211                                 | 1         | 0.68%   |
| QinHeng CH340S                               | 1         | 0.68%   |
| Prolific PL2305 Parallel Port                | 1         | 0.68%   |
| NXP Semiconductors Printer-80                | 1         | 0.68%   |
| Lexmark International X364dn                 | 1         | 0.68%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 15        | 71.43%  |
| Seiko Epson     | 3         | 14.29%  |
| Mustek Systems  | 2         | 9.52%   |
| Hewlett-Packard | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                  | 3         | 14.29%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2         | 9.52%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 9.52%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 9.52%   |
| Canon CanoScan LiDE 120                                  | 2         | 9.52%   |
| Canon CanoScan LiDE 100                                  | 2         | 9.52%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 4.76%   |
| Mustek Systems SNAPSCAN e22                              | 1         | 4.76%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 4.76%   |
| HP ScanJet 2400c                                         | 1         | 4.76%   |
| Canon CanoScan LiDE 600F                                 | 1         | 4.76%   |
| Canon CanoScan LIDE 25                                   | 1         | 4.76%   |
| Canon CanoScan LiDE 210                                  | 1         | 4.76%   |
| Canon CanoScan 5200F                                     | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 472       | 22.04%  |
| Realtek Semiconductor                  | 247       | 11.53%  |
| Microdia                               | 232       | 10.83%  |
| IMC Networks                           | 128       | 5.98%   |
| Sunplus Innovation Technology          | 123       | 5.74%   |
| Acer                                   | 111       | 5.18%   |
| Logitech                               | 106       | 4.95%   |
| Suyin                                  | 83        | 3.87%   |
| Cheng Uei Precision Industry (Foxlink) | 77        | 3.59%   |
| Quanta                                 | 75        | 3.5%    |
| Syntek                                 | 58        | 2.71%   |
| Apple                                  | 49        | 2.29%   |
| Lite-On Technology                     | 45        | 2.1%    |
| Silicon Motion                         | 41        | 1.91%   |
| Ricoh                                  | 33        | 1.54%   |
| Alcor Micro                            | 32        | 1.49%   |
| ALi                                    | 20        | 0.93%   |
| Microsoft                              | 19        | 0.89%   |
| Importek                               | 17        | 0.79%   |
| Z-Star Microelectronics                | 16        | 0.75%   |
| Lenovo                                 | 16        | 0.75%   |
| Luxvisions Innotech Limited            | 12        | 0.56%   |
| Primax Electronics                     | 10        | 0.47%   |
| Generalplus Technology                 | 10        | 0.47%   |
| Sonix Technology                       | 9         | 0.42%   |
| Samsung Electronics                    | 6         | 0.28%   |
| KYE Systems (Mouse Systems)            | 6         | 0.28%   |
| Sunplus Technology                     | 5         | 0.23%   |
| Hewlett-Packard                        | 5         | 0.23%   |
| DigiTech                               | 5         | 0.23%   |
| Cubeternet                             | 5         | 0.23%   |
| Aveo Technology                        | 5         | 0.23%   |
| Unknown                                | 4         | 0.19%   |
| Trust                                  | 4         | 0.19%   |
| GEMBIRD                                | 4         | 0.19%   |
| ARC International                      | 4         | 0.19%   |
| Jieli Technology                       | 3         | 0.14%   |
| Creative Technology                    | 3         | 0.14%   |
| Pixart Imaging                         | 2         | 0.09%   |
| OmniVision Technologies                | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 103       | 4.73%   |
| Chicony Integrated Camera                | 62        | 2.85%   |
| Realtek Integrated_Webcam_5M             | 59        | 2.71%   |
| Realtek Integrated_Webcam_HD             | 58        | 2.66%   |
| Sunplus Integrated_Webcam_HD             | 49        | 2.25%   |
| Chicony HD WebCam                        | 47        | 2.16%   |
| Acer Integrated Camera                   | 32        | 1.47%   |
| Microdia Integrated Webcam               | 30        | 1.38%   |
| Syntek Integrated Camera                 | 28        | 1.29%   |
| Chicony USB 2.0 Camera                   | 27        | 1.24%   |
| Logitech Webcam C270                     | 26        | 1.19%   |
| IMC Networks USB2.0 HD UVC WebCam        | 25        | 1.15%   |
| Realtek USB Camera                       | 24        | 1.1%    |
| IMC Networks Integrated Camera           | 23        | 1.06%   |
| Microdia USB 2.0 Camera                  | 22        | 1.01%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 21        | 0.96%   |
| Chicony TOSHIBA Web Camera - HD          | 21        | 0.96%   |
| Chicony VGA WebCam                       | 20        | 0.92%   |
| Chicony USB2.0 VGA UVC WebCam            | 19        | 0.87%   |
| Chicony Lenovo EasyCamera                | 19        | 0.87%   |
| Microdia Integrated_Webcam_5M            | 17        | 0.78%   |
| Chicony FJ Camera                        | 17        | 0.78%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 16        | 0.73%   |
| Chicony HD User Facing                   | 16        | 0.73%   |
| Apple Built-in iSight                    | 16        | 0.73%   |
| Acer Lenovo EasyCamera                   | 16        | 0.73%   |
| Sunplus HD WebCam                        | 15        | 0.69%   |
| Realtek EasyCamera                       | 15        | 0.69%   |
| Quanta HD User Facing                    | 15        | 0.69%   |
| Chicony HP TrueVision HD Camera          | 15        | 0.69%   |
| Lite-On Integrated Camera                | 14        | 0.64%   |
| Chicony HP TrueVision HD                 | 14        | 0.64%   |
| Realtek Lenovo EasyCamera                | 13        | 0.6%    |
| Quanta HP TrueVision HD Camera           | 13        | 0.6%    |
| Logitech HD Pro Webcam C920              | 13        | 0.6%    |
| Chicony USB2.0 HD UVC WebCam             | 13        | 0.6%    |
| Chicony HP Webcam                        | 13        | 0.6%    |
| Apple FaceTime HD Camera (Built-in)      | 13        | 0.6%    |
| ALi Gateway Webcam                       | 13        | 0.6%    |
| Syntek Lenovo EasyCamera                 | 12        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 69        | 35.2%   |
| AuthenTec                  | 30        | 15.31%  |
| Upek                       | 24        | 12.24%  |
| Elan Microelectronics      | 18        | 9.18%   |
| Synaptics                  | 17        | 8.67%   |
| Shenzhen Goodix Technology | 16        | 8.16%   |
| LighTuning Technology      | 11        | 5.61%   |
| STMicroelectronics         | 8         | 4.08%   |
| Samsung Electronics        | 1         | 0.51%   |
| HOLTEK                     | 1         | 0.51%   |
| Focal-systems.Corp         | 1         | 0.51%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 23        | 11.73%  |
| Validity Sensors VFS495 Fingerprint Reader                  | 17        | 8.67%   |
| Shenzhen Goodix  Fingerprint Device                         | 11        | 5.61%   |
| Elan ELAN:Fingerprint                                       | 10        | 5.1%    |
| STMicroelectronics Fingerprint Reader                       | 8         | 4.08%   |
| Elan ELAN:ARM-M4                                            | 8         | 4.08%   |
| Validity Sensors VFS491                                     | 7         | 3.57%   |
| AuthenTec AES2810                                           | 7         | 3.57%   |
| AuthenTec AES2501 Fingerprint Sensor                        | 7         | 3.57%   |
| AuthenTec AES1600                                           | 7         | 3.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 6         | 3.06%   |
| Validity Sensors Swipe Fingerprint Sensor                   | 6         | 3.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 5         | 2.55%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 5         | 2.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 5         | 2.55%   |
| AuthenTec Fingerprint Sensor                                | 5         | 2.55%   |
| Unknown                                                     | 5         | 2.55%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 4         | 2.04%   |
| Validity Sensors Synaptics WBDI                             | 4         | 2.04%   |
| Validity Sensors Fingerprint scanner                        | 4         | 2.04%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 4         | 2.04%   |
| Shenzhen Goodix Fingerprint Reader                          | 4         | 2.04%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 3         | 1.53%   |
| Validity Sensors VFS301 Fingerprint Reader                  | 3         | 1.53%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint  | 3         | 1.53%   |
| LighTuning ES603 Swipe Fingerprint Sensor                   | 3         | 1.53%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 3         | 1.53%   |
| Validity Sensors VFS300 Fingerprint Reader                  | 2         | 1.02%   |
| LighTuning Fingerprint Reader                               | 2         | 1.02%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor           | 1         | 0.51%   |
| Validity Sensors VFS101 Fingerprint Reader                  | 1         | 0.51%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 0.51%   |
| Upek TCS5B Fingerprint sensor                               | 1         | 0.51%   |
| Synaptics WBDI Device                                       | 1         | 0.51%   |
| Synaptics  WBDI                                             | 1         | 0.51%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 0.51%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 0.51%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 1         | 0.51%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 0.51%   |
| Samsung Fingerprint Sensor Device - 730B                    | 1         | 0.51%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 78        | 52.7%   |
| O2 Micro              | 18        | 12.16%  |
| Alcor Micro           | 16        | 10.81%  |
| Upek                  | 14        | 9.46%   |
| Lenovo                | 11        | 7.43%   |
| SCM Microsystems      | 3         | 2.03%   |
| Realtek Semiconductor | 3         | 2.03%   |
| Gemalto (was Gemplus) | 3         | 2.03%   |
| Cherry                | 1         | 0.68%   |
| BIT4ID                | 1         | 0.68%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 36        | 24.32%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 16.22%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 11.49%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 10.14%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 9.46%   |
| Broadcom 5880                                                                | 12        | 8.11%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 7.43%   |
| Broadcom 58200                                                               | 5         | 3.38%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 2.03%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.35%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.35%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.68%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.68%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.68%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.68%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.68%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.68%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.68%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3386      | 82.77%  |
| 1     | 611       | 14.94%  |
| 2     | 82        | 2%      |
| 3     | 9         | 0.22%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 196       | 24.75%  |
| Graphics card            | 147       | 18.56%  |
| Chipcard                 | 143       | 18.06%  |
| Net/wireless             | 76        | 9.6%    |
| Multimedia controller    | 74        | 9.34%   |
| Bluetooth                | 53        | 6.69%   |
| Storage                  | 25        | 3.16%   |
| Communication controller | 23        | 2.9%    |
| Camera                   | 19        | 2.4%    |
| Unassigned class         | 14        | 1.77%   |
| Network                  | 7         | 0.88%   |
| Sound                    | 4         | 0.51%   |
| Wireless                 | 3         | 0.38%   |
| Flash memory             | 3         | 0.38%   |
| Net/ethernet             | 2         | 0.25%   |
| Card reader              | 2         | 0.25%   |
| Storage/raid             | 1         | 0.13%   |

