Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

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

Total: 6725

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T440p 20AN0079M... | Notebook    | [79261239c1](https://linux-hardware.org/?probe=79261239c1) | Dec 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e03c6b53ed](https://linux-hardware.org/?probe=e03c6b53ed) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [674157de54](https://linux-hardware.org/?probe=674157de54) | Dec 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [44f13beada](https://linux-hardware.org/?probe=44f13beada) | Dec 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3131016a26](https://linux-hardware.org/?probe=3131016a26) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | Notebook    | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | Notebook    | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [5fa6ceed90](https://linux-hardware.org/?probe=5fa6ceed90) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [f0dba35258](https://linux-hardware.org/?probe=f0dba35258) | Dec 01, 2022 |
| sunxi         | FriendlyARM NanoPi NEO 2    | Soc         | [f1e2cbe354](https://linux-hardware.org/?probe=f1e2cbe354) | Nov 30, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [baa969bf8b](https://linux-hardware.org/?probe=baa969bf8b) | Nov 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [0fc7017b0c](https://linux-hardware.org/?probe=0fc7017b0c) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | Desktop     | [edadb85201](https://linux-hardware.org/?probe=edadb85201) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | Desktop     | [b248df8671](https://linux-hardware.org/?probe=b248df8671) | Nov 30, 2022 |
| Dell          | 0Y2G81 A01                  | Server      | [7ce42afb90](https://linux-hardware.org/?probe=7ce42afb90) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [dc5ec6eb84](https://linux-hardware.org/?probe=dc5ec6eb84) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [6b21f343c3](https://linux-hardware.org/?probe=6b21f343c3) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [952c3681c0](https://linux-hardware.org/?probe=952c3681c0) | Nov 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3e3ccd1471](https://linux-hardware.org/?probe=3e3ccd1471) | Nov 30, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [00232e7345](https://linux-hardware.org/?probe=00232e7345) | Nov 29, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [81bf84e7e5](https://linux-hardware.org/?probe=81bf84e7e5) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [9dd6019148](https://linux-hardware.org/?probe=9dd6019148) | Nov 29, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [a97334be81](https://linux-hardware.org/?probe=a97334be81) | Nov 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [eae94e440a](https://linux-hardware.org/?probe=eae94e440a) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [a20e18af73](https://linux-hardware.org/?probe=a20e18af73) | Nov 29, 2022 |
| Dell          | Latitude 7490               | Notebook    | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| ASRock        | H510M-HDV                   | Desktop     | [03a1675c85](https://linux-hardware.org/?probe=03a1675c85) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [9c87ab493e](https://linux-hardware.org/?probe=9c87ab493e) | Nov 29, 2022 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [8b3da34947](https://linux-hardware.org/?probe=8b3da34947) | Nov 28, 2022 |
| Lenovo        | ThinkPad X301 2776LEG       | Notebook    | [ebaea0c805](https://linux-hardware.org/?probe=ebaea0c805) | Nov 28, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [8d0514a0df](https://linux-hardware.org/?probe=8d0514a0df) | Nov 28, 2022 |
| Dell          | Precision M6400             | Notebook    | [05f69c6917](https://linux-hardware.org/?probe=05f69c6917) | Nov 28, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [1e84d5c704](https://linux-hardware.org/?probe=1e84d5c704) | Nov 28, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [edc0678b85](https://linux-hardware.org/?probe=edc0678b85) | Nov 28, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [88988d4d0d](https://linux-hardware.org/?probe=88988d4d0d) | Nov 28, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [076eeadd80](https://linux-hardware.org/?probe=076eeadd80) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| HP            | 212B                        | Desktop     | [53471968c2](https://linux-hardware.org/?probe=53471968c2) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | Notebook    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [e0e0efb9be](https://linux-hardware.org/?probe=e0e0efb9be) | Nov 27, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | Notebook    | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | Notebook    | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [32bfa52fc1](https://linux-hardware.org/?probe=32bfa52fc1) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [3d1b8f282a](https://linux-hardware.org/?probe=3d1b8f282a) | Nov 27, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| HP            | Laptop 15-da3xxx            | Notebook    | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [2902b75068](https://linux-hardware.org/?probe=2902b75068) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [973662f8d5](https://linux-hardware.org/?probe=973662f8d5) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [bede773ce4](https://linux-hardware.org/?probe=bede773ce4) | Nov 26, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [6ea1a60122](https://linux-hardware.org/?probe=6ea1a60122) | Nov 26, 2022 |
| ASUSTek       | A6R                         | Notebook    | [68f38deab1](https://linux-hardware.org/?probe=68f38deab1) | Nov 26, 2022 |
| Dell          | Latitude E7240              | Notebook    | [634ebb2a88](https://linux-hardware.org/?probe=634ebb2a88) | Nov 25, 2022 |
| HP            | Pavilion TS Sleekbook 14    | Notebook    | [26440cddbb](https://linux-hardware.org/?probe=26440cddbb) | Nov 25, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [a15ef33296](https://linux-hardware.org/?probe=a15ef33296) | Nov 25, 2022 |
| Lenovo        | ThinkPad E14 20RBS3LE00     | Notebook    | [83203a04f2](https://linux-hardware.org/?probe=83203a04f2) | Nov 25, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [2dfd7f3926](https://linux-hardware.org/?probe=2dfd7f3926) | Nov 25, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | Notebook    | [f82ee02c50](https://linux-hardware.org/?probe=f82ee02c50) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [618ea5fb0e](https://linux-hardware.org/?probe=618ea5fb0e) | Nov 25, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f5a6bcf0fb](https://linux-hardware.org/?probe=f5a6bcf0fb) | Nov 24, 2022 |
| ASUSTek       | X551CAP                     | Notebook    | [f40e3110d0](https://linux-hardware.org/?probe=f40e3110d0) | Nov 24, 2022 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [fcc81ea02b](https://linux-hardware.org/?probe=fcc81ea02b) | Nov 24, 2022 |
| Dell          | Latitude 5310               | Notebook    | [8b4ad51670](https://linux-hardware.org/?probe=8b4ad51670) | Nov 24, 2022 |
| Dell          | Latitude 5310               | Notebook    | [a5265c8a0e](https://linux-hardware.org/?probe=a5265c8a0e) | Nov 24, 2022 |
| Dell          | Latitude E6500              | Notebook    | [73d607f9e1](https://linux-hardware.org/?probe=73d607f9e1) | Nov 24, 2022 |
| ASUSTek       | P5Q3                        | Desktop     | [655065ee03](https://linux-hardware.org/?probe=655065ee03) | Nov 24, 2022 |
| Lenovo        | 312A NOK                    | Desktop     | [94cdaff2c9](https://linux-hardware.org/?probe=94cdaff2c9) | Nov 24, 2022 |
| Aquarius      | NS585                       | Notebook    | [d54530cbcb](https://linux-hardware.org/?probe=d54530cbcb) | Nov 24, 2022 |
| Aquarius      | NS585                       | Notebook    | [64d9bcbcde](https://linux-hardware.org/?probe=64d9bcbcde) | Nov 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [93e1fc870a](https://linux-hardware.org/?probe=93e1fc870a) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [38aca80776](https://linux-hardware.org/?probe=38aca80776) | Nov 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c0ce9a3ff3](https://linux-hardware.org/?probe=c0ce9a3ff3) | Nov 23, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| Lenovo        | ThinkPad T495 20NK000UUS    | Notebook    | [0e8c0e6f07](https://linux-hardware.org/?probe=0e8c0e6f07) | Nov 23, 2022 |
| Lenovo        | ThinkPad T490 20N3S8T211    | Notebook    | [97ea649145](https://linux-hardware.org/?probe=97ea649145) | Nov 23, 2022 |
| Dell          | Latitude E6530              | Notebook    | [71623eedf3](https://linux-hardware.org/?probe=71623eedf3) | Nov 23, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [ca3bcfa403](https://linux-hardware.org/?probe=ca3bcfa403) | Nov 23, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e57ddd940](https://linux-hardware.org/?probe=1e57ddd940) | Nov 23, 2022 |
| MSI           | MS-ACD31                    | All in one  | [12e48e36c7](https://linux-hardware.org/?probe=12e48e36c7) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [e8ab5ad410](https://linux-hardware.org/?probe=e8ab5ad410) | Nov 23, 2022 |
| ASRock        | H410M-HVS R2.0              | Desktop     | [3f381f9fa3](https://linux-hardware.org/?probe=3f381f9fa3) | Nov 23, 2022 |
| HP            | Compaq 6720s                | Notebook    | [63a0e0161c](https://linux-hardware.org/?probe=63a0e0161c) | Nov 22, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9311837a60](https://linux-hardware.org/?probe=9311837a60) | Nov 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [363e0b0149](https://linux-hardware.org/?probe=363e0b0149) | Nov 22, 2022 |
| VIT           | M2400-01                    | Mini pc     | [4b590aa76a](https://linux-hardware.org/?probe=4b590aa76a) | Nov 22, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [0e778da8b6](https://linux-hardware.org/?probe=0e778da8b6) | Nov 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [1de34b67e2](https://linux-hardware.org/?probe=1de34b67e2) | Nov 22, 2022 |
| Dell          | Latitude 3420               | Notebook    | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| TMAX          | TM101W638L                  | Tablet      | [ac8adad039](https://linux-hardware.org/?probe=ac8adad039) | Nov 22, 2022 |
| Unknown       | Wiren Board rev. 7.3.1 (... | Notebook    | [1f9ccab914](https://linux-hardware.org/?probe=1f9ccab914) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [6d50058ef8](https://linux-hardware.org/?probe=6d50058ef8) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [f6a783a27a](https://linux-hardware.org/?probe=f6a783a27a) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [423fbc1fa0](https://linux-hardware.org/?probe=423fbc1fa0) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [debc5b7ab9](https://linux-hardware.org/?probe=debc5b7ab9) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [dc53077baa](https://linux-hardware.org/?probe=dc53077baa) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [856bb3def2](https://linux-hardware.org/?probe=856bb3def2) | Nov 22, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [d140a0f503](https://linux-hardware.org/?probe=d140a0f503) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [ee55108218](https://linux-hardware.org/?probe=ee55108218) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [ec03d1b050](https://linux-hardware.org/?probe=ec03d1b050) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [1f2a4089cc](https://linux-hardware.org/?probe=1f2a4089cc) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [4190bbb2d8](https://linux-hardware.org/?probe=4190bbb2d8) | Nov 22, 2022 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [add4f71bc0](https://linux-hardware.org/?probe=add4f71bc0) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [570a11d74b](https://linux-hardware.org/?probe=570a11d74b) | Nov 22, 2022 |
| HP            | ENVY 6                      | Notebook    | [feb348843e](https://linux-hardware.org/?probe=feb348843e) | Nov 22, 2022 |
| Dell          | Inspiron 7586               | Convertible | [ea152cdb94](https://linux-hardware.org/?probe=ea152cdb94) | Nov 22, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [404927f4cc](https://linux-hardware.org/?probe=404927f4cc) | Nov 22, 2022 |
| Lenovo        | Y520-15IKBA 80WY            | Notebook    | [c1cccb2b2a](https://linux-hardware.org/?probe=c1cccb2b2a) | Nov 22, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [b5ed1b189a](https://linux-hardware.org/?probe=b5ed1b189a) | Nov 22, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [aef32a0e69](https://linux-hardware.org/?probe=aef32a0e69) | Nov 22, 2022 |
| Dell          | 05DN3X A00                  | Desktop     | [f15eef78fa](https://linux-hardware.org/?probe=f15eef78fa) | Nov 22, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [c127a0db71](https://linux-hardware.org/?probe=c127a0db71) | Nov 21, 2022 |
| Lenovo        | ThinkPad E14 20RAS04700     | Notebook    | [63d93d05db](https://linux-hardware.org/?probe=63d93d05db) | Nov 21, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [e6d5440b09](https://linux-hardware.org/?probe=e6d5440b09) | Nov 21, 2022 |
| Dell          | Latitude 5310               | Notebook    | [9c19a3de68](https://linux-hardware.org/?probe=9c19a3de68) | Nov 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5c1c053b03](https://linux-hardware.org/?probe=5c1c053b03) | Nov 21, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f634446cde](https://linux-hardware.org/?probe=f634446cde) | Nov 21, 2022 |
| Acer          | Popcorn                     | Notebook    | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | Notebook    | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | Notebook    | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| HP            | Pro x2 612 G2               | Tablet      | [6c49fe9d07](https://linux-hardware.org/?probe=6c49fe9d07) | Nov 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [dba99c363e](https://linux-hardware.org/?probe=dba99c363e) | Nov 20, 2022 |
| Intel         | JSL MRD                     | Desktop     | [469567b71f](https://linux-hardware.org/?probe=469567b71f) | Nov 20, 2022 |
| Dell          | 0WPMFG A00                  | Desktop     | [8b3a3dc37f](https://linux-hardware.org/?probe=8b3a3dc37f) | Nov 20, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c209fc2b22](https://linux-hardware.org/?probe=c209fc2b22) | Nov 20, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [5cb7f434ac](https://linux-hardware.org/?probe=5cb7f434ac) | Nov 20, 2022 |
| Acer          | Nitro N50-620               | Desktop     | [ecd8e9ec1b](https://linux-hardware.org/?probe=ecd8e9ec1b) | Nov 20, 2022 |
| Intel         | JSL MRD                     | Desktop     | [e8171566d3](https://linux-hardware.org/?probe=e8171566d3) | Nov 19, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [a90cea62ff](https://linux-hardware.org/?probe=a90cea62ff) | Nov 19, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [d42bddbd11](https://linux-hardware.org/?probe=d42bddbd11) | Nov 19, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [3e3d8f727c](https://linux-hardware.org/?probe=3e3d8f727c) | Nov 19, 2022 |
| Aquarius      | NS585                       | Notebook    | [a0bc8d3f44](https://linux-hardware.org/?probe=a0bc8d3f44) | Nov 19, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [8c080caac2](https://linux-hardware.org/?probe=8c080caac2) | Nov 19, 2022 |
| Fujitsu       | FMVNQL7PM                   | Notebook    | [28ee68da79](https://linux-hardware.org/?probe=28ee68da79) | Nov 19, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [c9cee6c5e5](https://linux-hardware.org/?probe=c9cee6c5e5) | Nov 19, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [da08e08dec](https://linux-hardware.org/?probe=da08e08dec) | Nov 18, 2022 |
| Dell          | Latitude 7410               | Notebook    | [ce222880fe](https://linux-hardware.org/?probe=ce222880fe) | Nov 18, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [e913feb821](https://linux-hardware.org/?probe=e913feb821) | Nov 18, 2022 |
| Dynabook      | TECRA A50-J                 | Notebook    | [c0ae8746e0](https://linux-hardware.org/?probe=c0ae8746e0) | Nov 18, 2022 |
| HP            | 650                         | Notebook    | [43998a620b](https://linux-hardware.org/?probe=43998a620b) | Nov 18, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [0278a1f18d](https://linux-hardware.org/?probe=0278a1f18d) | Nov 18, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [57c6327e27](https://linux-hardware.org/?probe=57c6327e27) | Nov 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d1d9ddf9f3](https://linux-hardware.org/?probe=d1d9ddf9f3) | Nov 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [da04bee118](https://linux-hardware.org/?probe=da04bee118) | Nov 18, 2022 |
| Intel         | NUC11ATBC4 M53051-302       | Mini pc     | [b03e6d95e5](https://linux-hardware.org/?probe=b03e6d95e5) | Nov 18, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [f0fa194e20](https://linux-hardware.org/?probe=f0fa194e20) | Nov 18, 2022 |
| Google        | Terra                       | Notebook    | [9fcc3fb18a](https://linux-hardware.org/?probe=9fcc3fb18a) | Nov 18, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [06a234be2c](https://linux-hardware.org/?probe=06a234be2c) | Nov 17, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | Notebook    | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| Dell          | Latitude 5310               | Notebook    | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | Notebook    | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| Lenovo        | B475 Sabine                 | Notebook    | [5be5a7cd5f](https://linux-hardware.org/?probe=5be5a7cd5f) | Nov 17, 2022 |
| HP            | EliteBook 745 G5            | Notebook    | [9d7fefd253](https://linux-hardware.org/?probe=9d7fefd253) | Nov 17, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [550bd99088](https://linux-hardware.org/?probe=550bd99088) | Nov 17, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [f1fdc384f9](https://linux-hardware.org/?probe=f1fdc384f9) | Nov 17, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d71e1be6dc](https://linux-hardware.org/?probe=d71e1be6dc) | Nov 17, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [14c23218a5](https://linux-hardware.org/?probe=14c23218a5) | Nov 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [814b5d3d2e](https://linux-hardware.org/?probe=814b5d3d2e) | Nov 17, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b3e809f3d2](https://linux-hardware.org/?probe=b3e809f3d2) | Nov 17, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [5aa50e7f6c](https://linux-hardware.org/?probe=5aa50e7f6c) | Nov 17, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [523e8a1c6b](https://linux-hardware.org/?probe=523e8a1c6b) | Nov 17, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b21e07c887](https://linux-hardware.org/?probe=b21e07c887) | Nov 16, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [3c9865d86e](https://linux-hardware.org/?probe=3c9865d86e) | Nov 16, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f6202bb6fa](https://linux-hardware.org/?probe=f6202bb6fa) | Nov 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [8fe0bcfe69](https://linux-hardware.org/?probe=8fe0bcfe69) | Nov 16, 2022 |
| GuoGuang      | IC2M1028N-3                 | Desktop     | [32351ceb62](https://linux-hardware.org/?probe=32351ceb62) | Nov 16, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [757a1066ff](https://linux-hardware.org/?probe=757a1066ff) | Nov 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [a3c41dcc96](https://linux-hardware.org/?probe=a3c41dcc96) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Gigabyte      | P75-D3                      | Desktop     | [02bdf99508](https://linux-hardware.org/?probe=02bdf99508) | Nov 16, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [71c99edeb1](https://linux-hardware.org/?probe=71c99edeb1) | Nov 16, 2022 |
| ASUSTek       | PN51-E1                     | Mini pc     | [d6bae26c19](https://linux-hardware.org/?probe=d6bae26c19) | Nov 16, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [55f47f2c19](https://linux-hardware.org/?probe=55f47f2c19) | Nov 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [a86465b0f3](https://linux-hardware.org/?probe=a86465b0f3) | Nov 16, 2022 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [769e7a63d1](https://linux-hardware.org/?probe=769e7a63d1) | Nov 16, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [41a49817ef](https://linux-hardware.org/?probe=41a49817ef) | Nov 16, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [35a7094f72](https://linux-hardware.org/?probe=35a7094f72) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [f29e7d7659](https://linux-hardware.org/?probe=f29e7d7659) | Nov 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [867825d906](https://linux-hardware.org/?probe=867825d906) | Nov 15, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ab62b77bfb](https://linux-hardware.org/?probe=ab62b77bfb) | Nov 15, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [e907b4c718](https://linux-hardware.org/?probe=e907b4c718) | Nov 15, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [0674cb5916](https://linux-hardware.org/?probe=0674cb5916) | Nov 15, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c3cacc3ed6](https://linux-hardware.org/?probe=c3cacc3ed6) | Nov 15, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [ee8a80240d](https://linux-hardware.org/?probe=ee8a80240d) | Nov 15, 2022 |
| HP            | 871A                        | Mini pc     | [ac658f992a](https://linux-hardware.org/?probe=ac658f992a) | Nov 15, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [a46c1d62cf](https://linux-hardware.org/?probe=a46c1d62cf) | Nov 15, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [f8d8191f69](https://linux-hardware.org/?probe=f8d8191f69) | Nov 15, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [8e55592803](https://linux-hardware.org/?probe=8e55592803) | Nov 15, 2022 |
| Dell          | G7 7700                     | Notebook    | [2440bebe2c](https://linux-hardware.org/?probe=2440bebe2c) | Nov 15, 2022 |
| Chuwi         | LarkBox X                   | Mini pc     | [cbfdfc82b4](https://linux-hardware.org/?probe=cbfdfc82b4) | Nov 15, 2022 |
| IBM           | ThinkPad X31 2672JBU        | Notebook    | [ea0c82f4eb](https://linux-hardware.org/?probe=ea0c82f4eb) | Nov 15, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [fe84036164](https://linux-hardware.org/?probe=fe84036164) | Nov 15, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [e69c2f0da4](https://linux-hardware.org/?probe=e69c2f0da4) | Nov 15, 2022 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [137906fffe](https://linux-hardware.org/?probe=137906fffe) | Nov 15, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [862e9a2c25](https://linux-hardware.org/?probe=862e9a2c25) | Nov 15, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [a94cf56482](https://linux-hardware.org/?probe=a94cf56482) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [16e5672a66](https://linux-hardware.org/?probe=16e5672a66) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [2029195495](https://linux-hardware.org/?probe=2029195495) | Nov 14, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [9fe9bc94a0](https://linux-hardware.org/?probe=9fe9bc94a0) | Nov 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [28df02c741](https://linux-hardware.org/?probe=28df02c741) | Nov 14, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [100714ed23](https://linux-hardware.org/?probe=100714ed23) | Nov 14, 2022 |
| Gigabyte      | P75-D3                      | Desktop     | [37f9da1b7f](https://linux-hardware.org/?probe=37f9da1b7f) | Nov 14, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [8267ec6686](https://linux-hardware.org/?probe=8267ec6686) | Nov 14, 2022 |
| Toshiba       | Satellite P50-B-10Q         | Notebook    | [f28064cdad](https://linux-hardware.org/?probe=f28064cdad) | Nov 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [277739769b](https://linux-hardware.org/?probe=277739769b) | Nov 14, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [53a532435e](https://linux-hardware.org/?probe=53a532435e) | Nov 14, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [80cce966ce](https://linux-hardware.org/?probe=80cce966ce) | Nov 14, 2022 |
| HP            | 530 Notebook PC(KD092AA#... | Notebook    | [b6c682238c](https://linux-hardware.org/?probe=b6c682238c) | Nov 13, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2a6473f450](https://linux-hardware.org/?probe=2a6473f450) | Nov 13, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [d7ae86ad73](https://linux-hardware.org/?probe=d7ae86ad73) | Nov 13, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [d31168230f](https://linux-hardware.org/?probe=d31168230f) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [ff0881b6e4](https://linux-hardware.org/?probe=ff0881b6e4) | Nov 13, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [4788a2a91d](https://linux-hardware.org/?probe=4788a2a91d) | Nov 13, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7e9c7562d6](https://linux-hardware.org/?probe=7e9c7562d6) | Nov 13, 2022 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [acce4cc1af](https://linux-hardware.org/?probe=acce4cc1af) | Nov 13, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [57952c1512](https://linux-hardware.org/?probe=57952c1512) | Nov 13, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [8cb389e68e](https://linux-hardware.org/?probe=8cb389e68e) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [dc2a41e0ee](https://linux-hardware.org/?probe=dc2a41e0ee) | Nov 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6677ca6be8](https://linux-hardware.org/?probe=6677ca6be8) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [978facebde](https://linux-hardware.org/?probe=978facebde) | Nov 12, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [904b7c0e89](https://linux-hardware.org/?probe=904b7c0e89) | Nov 12, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [53d2019fae](https://linux-hardware.org/?probe=53d2019fae) | Nov 12, 2022 |
| HP            | Notebook                    | Notebook    | [2419e7d149](https://linux-hardware.org/?probe=2419e7d149) | Nov 12, 2022 |
| HP            | Notebook                    | Notebook    | [97c6c3c412](https://linux-hardware.org/?probe=97c6c3c412) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [9e0c2df66d](https://linux-hardware.org/?probe=9e0c2df66d) | Nov 12, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3d18010536](https://linux-hardware.org/?probe=3d18010536) | Nov 12, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d9dd29ce39](https://linux-hardware.org/?probe=d9dd29ce39) | Nov 12, 2022 |
| IBM           | ThinkPad X31 2672JBU        | Notebook    | [9f627ba3f8](https://linux-hardware.org/?probe=9f627ba3f8) | Nov 12, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e69a98ce67](https://linux-hardware.org/?probe=e69a98ce67) | Nov 11, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [22ab694d81](https://linux-hardware.org/?probe=22ab694d81) | Nov 11, 2022 |
| Lenovo        | ThinkPad W700 275236U       | Notebook    | [c79bbe36c5](https://linux-hardware.org/?probe=c79bbe36c5) | Nov 11, 2022 |
| HP            | 872E                        | Mini pc     | [b2e72a139e](https://linux-hardware.org/?probe=b2e72a139e) | Nov 11, 2022 |
| NCA Group     | iRU_Notebook                | Notebook    | [6d22b3942e](https://linux-hardware.org/?probe=6d22b3942e) | Nov 11, 2022 |
| HP            | Spectre x2 Detachable       | Notebook    | [0c480bd74d](https://linux-hardware.org/?probe=0c480bd74d) | Nov 11, 2022 |
| ASUSTek       | K50IE                       | Notebook    | [4bd91fccfa](https://linux-hardware.org/?probe=4bd91fccfa) | Nov 11, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [b81b19a472](https://linux-hardware.org/?probe=b81b19a472) | Nov 11, 2022 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [46ee069dd8](https://linux-hardware.org/?probe=46ee069dd8) | Nov 11, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [524b1115eb](https://linux-hardware.org/?probe=524b1115eb) | Nov 11, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3acc2b87a6](https://linux-hardware.org/?probe=3acc2b87a6) | Nov 11, 2022 |
| Positivo B... | VJFE53F11X-XXXXXX           | Notebook    | [7e81c7cf85](https://linux-hardware.org/?probe=7e81c7cf85) | Nov 10, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [ae40e6e5b3](https://linux-hardware.org/?probe=ae40e6e5b3) | Nov 10, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [f8cd836199](https://linux-hardware.org/?probe=f8cd836199) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [8bb3389cc1](https://linux-hardware.org/?probe=8bb3389cc1) | Nov 10, 2022 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [45dc316bea](https://linux-hardware.org/?probe=45dc316bea) | Nov 10, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [1e0c308a85](https://linux-hardware.org/?probe=1e0c308a85) | Nov 10, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [a885b61478](https://linux-hardware.org/?probe=a885b61478) | Nov 10, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [475ad820cd](https://linux-hardware.org/?probe=475ad820cd) | Nov 10, 2022 |
| ASUSTek       | K50IE                       | Notebook    | [5176f404f1](https://linux-hardware.org/?probe=5176f404f1) | Nov 10, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [9a69ea4724](https://linux-hardware.org/?probe=9a69ea4724) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6dd51f8707](https://linux-hardware.org/?probe=6dd51f8707) | Nov 10, 2022 |
| Dell          | Latitude E6530              | Notebook    | [f71e1a930c](https://linux-hardware.org/?probe=f71e1a930c) | Nov 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [9d27997bce](https://linux-hardware.org/?probe=9d27997bce) | Nov 09, 2022 |
| Gigabyte      | Sabre 15                    | Notebook    | [1edede0895](https://linux-hardware.org/?probe=1edede0895) | Nov 09, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [0841a971e1](https://linux-hardware.org/?probe=0841a971e1) | Nov 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [098d4ab9ec](https://linux-hardware.org/?probe=098d4ab9ec) | Nov 09, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [33a4a1ea9a](https://linux-hardware.org/?probe=33a4a1ea9a) | Nov 09, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [29641e8b7c](https://linux-hardware.org/?probe=29641e8b7c) | Nov 09, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [67129f7239](https://linux-hardware.org/?probe=67129f7239) | Nov 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [6b1f5f2c2a](https://linux-hardware.org/?probe=6b1f5f2c2a) | Nov 08, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [b3db07cbc7](https://linux-hardware.org/?probe=b3db07cbc7) | Nov 08, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [e6eee311ea](https://linux-hardware.org/?probe=e6eee311ea) | Nov 08, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [a90c14df17](https://linux-hardware.org/?probe=a90c14df17) | Nov 08, 2022 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [11c3b15916](https://linux-hardware.org/?probe=11c3b15916) | Nov 08, 2022 |
| Aquarius      | NS585                       | Notebook    | [9b20fcc4b8](https://linux-hardware.org/?probe=9b20fcc4b8) | Nov 08, 2022 |
| Dell          | Latitude E7470              | Notebook    | [3938dbeadd](https://linux-hardware.org/?probe=3938dbeadd) | Nov 08, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [873668d836](https://linux-hardware.org/?probe=873668d836) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [da41b87b7c](https://linux-hardware.org/?probe=da41b87b7c) | Nov 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [f3c625be2d](https://linux-hardware.org/?probe=f3c625be2d) | Nov 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [6af513692f](https://linux-hardware.org/?probe=6af513692f) | Nov 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [b4859caaba](https://linux-hardware.org/?probe=b4859caaba) | Nov 07, 2022 |
| Lenovo        | ThinkPad W700 275236U       | Notebook    | [d3580b26c6](https://linux-hardware.org/?probe=d3580b26c6) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [32b59c7a7d](https://linux-hardware.org/?probe=32b59c7a7d) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f0c8aff40f](https://linux-hardware.org/?probe=f0c8aff40f) | Nov 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8c5e823980](https://linux-hardware.org/?probe=8c5e823980) | Nov 06, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [4d260267d7](https://linux-hardware.org/?probe=4d260267d7) | Nov 06, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [789df18cfb](https://linux-hardware.org/?probe=789df18cfb) | Nov 06, 2022 |
| Dell          | Latitude E6520              | Notebook    | [9593951427](https://linux-hardware.org/?probe=9593951427) | Nov 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [e872e8551e](https://linux-hardware.org/?probe=e872e8551e) | Nov 06, 2022 |
| Dell          | Latitude E6520              | Notebook    | [53eedbde1f](https://linux-hardware.org/?probe=53eedbde1f) | Nov 06, 2022 |
| Xunlong       | Orange Pi Zero              | Soc         | [024050e40a](https://linux-hardware.org/?probe=024050e40a) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [55d115647e](https://linux-hardware.org/?probe=55d115647e) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| Acer          | Aspire V3-572G              | Notebook    | [77f939bab4](https://linux-hardware.org/?probe=77f939bab4) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | Notebook    | [2d165dd7b0](https://linux-hardware.org/?probe=2d165dd7b0) | Nov 05, 2022 |
| Lenovo        | ThinkPad L380 20M50013MH    | Notebook    | [80ac51627a](https://linux-hardware.org/?probe=80ac51627a) | Nov 05, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [1b0d72cfeb](https://linux-hardware.org/?probe=1b0d72cfeb) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | Notebook    | [b89c7882f3](https://linux-hardware.org/?probe=b89c7882f3) | Nov 05, 2022 |
| Dell          | Inspiron 7570               | Notebook    | [158f7b0bcd](https://linux-hardware.org/?probe=158f7b0bcd) | Nov 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [e4d9794c31](https://linux-hardware.org/?probe=e4d9794c31) | Nov 05, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [97d0b022d2](https://linux-hardware.org/?probe=97d0b022d2) | Nov 05, 2022 |
| Foxconn       | A88GMV                      | Desktop     | [1391b33f62](https://linux-hardware.org/?probe=1391b33f62) | Nov 05, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [605e06c6ad](https://linux-hardware.org/?probe=605e06c6ad) | Nov 04, 2022 |
| Google        | Terra                       | Notebook    | [90518f31df](https://linux-hardware.org/?probe=90518f31df) | Nov 04, 2022 |
| Google        | Terra                       | Notebook    | [46ffa8092b](https://linux-hardware.org/?probe=46ffa8092b) | Nov 04, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [ab4089c760](https://linux-hardware.org/?probe=ab4089c760) | Nov 04, 2022 |
| Google        | Terra                       | Notebook    | [fc3f4b0ba5](https://linux-hardware.org/?probe=fc3f4b0ba5) | Nov 04, 2022 |
| Google        | Terra                       | Notebook    | [41017e02e4](https://linux-hardware.org/?probe=41017e02e4) | Nov 04, 2022 |
| Google        | Terra                       | Notebook    | [7429a311e4](https://linux-hardware.org/?probe=7429a311e4) | Nov 04, 2022 |
| SK hynix      | HyBook                      | Notebook    | [e758cde5ed](https://linux-hardware.org/?probe=e758cde5ed) | Nov 04, 2022 |
| Dell          | 0UW816 A00                  | Server      | [a41cabb3d6](https://linux-hardware.org/?probe=a41cabb3d6) | Nov 04, 2022 |
| Dell          | 0UW816 A00                  | Server      | [a9a5e01e23](https://linux-hardware.org/?probe=a9a5e01e23) | Nov 04, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [8607fcf09d](https://linux-hardware.org/?probe=8607fcf09d) | Nov 04, 2022 |
| ASUSTek       | X99-E WS/USB                | Desktop     | [7a65820be2](https://linux-hardware.org/?probe=7a65820be2) | Nov 04, 2022 |
| HP            | ProBook 6450b               | Notebook    | [7e595214cb](https://linux-hardware.org/?probe=7e595214cb) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [391881cdd5](https://linux-hardware.org/?probe=391881cdd5) | Nov 03, 2022 |
| Olimex        | A20-Olinuxino Micro         | Soc         | [82674b87bb](https://linux-hardware.org/?probe=82674b87bb) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [67e9f8d2f4](https://linux-hardware.org/?probe=67e9f8d2f4) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [ecf54fa708](https://linux-hardware.org/?probe=ecf54fa708) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [8681693f03](https://linux-hardware.org/?probe=8681693f03) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [d4d0f735d4](https://linux-hardware.org/?probe=d4d0f735d4) | Nov 03, 2022 |
| HP            | 8458                        | Mini pc     | [4da864256d](https://linux-hardware.org/?probe=4da864256d) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [04e15fb2d7](https://linux-hardware.org/?probe=04e15fb2d7) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [c80c7a9048](https://linux-hardware.org/?probe=c80c7a9048) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [e507b9a974](https://linux-hardware.org/?probe=e507b9a974) | Nov 03, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [521e8b0053](https://linux-hardware.org/?probe=521e8b0053) | Nov 03, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [4021f75f8e](https://linux-hardware.org/?probe=4021f75f8e) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [7a5f1eaf6c](https://linux-hardware.org/?probe=7a5f1eaf6c) | Nov 03, 2022 |
| SAGER         | D900F                       | Notebook    | [7e0d0de36a](https://linux-hardware.org/?probe=7e0d0de36a) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [cecc0cca9d](https://linux-hardware.org/?probe=cecc0cca9d) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [464cc2acc3](https://linux-hardware.org/?probe=464cc2acc3) | Nov 03, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [a473b71b4e](https://linux-hardware.org/?probe=a473b71b4e) | Nov 03, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [23fa7a2cf8](https://linux-hardware.org/?probe=23fa7a2cf8) | Nov 03, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d4f292aa03](https://linux-hardware.org/?probe=d4f292aa03) | Nov 03, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [1bbd4f8bd9](https://linux-hardware.org/?probe=1bbd4f8bd9) | Nov 03, 2022 |
| Foxconn       | 2A92                        | Desktop     | [927cf971e9](https://linux-hardware.org/?probe=927cf971e9) | Nov 02, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [36612b5e01](https://linux-hardware.org/?probe=36612b5e01) | Nov 02, 2022 |
| Shenzhen a... | AC1-DP                      | Desktop     | [754335ffe9](https://linux-hardware.org/?probe=754335ffe9) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [d59bd1e8f1](https://linux-hardware.org/?probe=d59bd1e8f1) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [4342ecb0f9](https://linux-hardware.org/?probe=4342ecb0f9) | Nov 02, 2022 |
| Google        | Terra                       | Notebook    | [46299bf228](https://linux-hardware.org/?probe=46299bf228) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [fd32769391](https://linux-hardware.org/?probe=fd32769391) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [d3c1c92563](https://linux-hardware.org/?probe=d3c1c92563) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [0ffaee423b](https://linux-hardware.org/?probe=0ffaee423b) | Nov 02, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| Dell          | 0JGM7F A00                  | Desktop     | [28f4800b2b](https://linux-hardware.org/?probe=28f4800b2b) | Nov 02, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [1fb0a79791](https://linux-hardware.org/?probe=1fb0a79791) | Nov 02, 2022 |
| HP            | G42                         | Notebook    | [18c487d99d](https://linux-hardware.org/?probe=18c487d99d) | Nov 02, 2022 |
| Digma         | EVE 11 C422 ES1068EW        | Notebook    | [f5177de131](https://linux-hardware.org/?probe=f5177de131) | Nov 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [47c34f9269](https://linux-hardware.org/?probe=47c34f9269) | Nov 02, 2022 |
| Foxconn       | 2A92                        | Desktop     | [0898482b18](https://linux-hardware.org/?probe=0898482b18) | Nov 02, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [dcf7112b3d](https://linux-hardware.org/?probe=dcf7112b3d) | Nov 01, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [a333f47ffa](https://linux-hardware.org/?probe=a333f47ffa) | Nov 01, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [0092b0ddaf](https://linux-hardware.org/?probe=0092b0ddaf) | Nov 01, 2022 |
| Phoenix       | POULSBO                     | Desktop     | [177f05205b](https://linux-hardware.org/?probe=177f05205b) | Nov 01, 2022 |
| Gigabyte      | H610M H DDR4                | Desktop     | [b726668f90](https://linux-hardware.org/?probe=b726668f90) | Nov 01, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [dc3d60731e](https://linux-hardware.org/?probe=dc3d60731e) | Nov 01, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [08649bd1e9](https://linux-hardware.org/?probe=08649bd1e9) | Nov 01, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [92fccb6716](https://linux-hardware.org/?probe=92fccb6716) | Nov 01, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [3eea020596](https://linux-hardware.org/?probe=3eea020596) | Nov 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [dab530a737](https://linux-hardware.org/?probe=dab530a737) | Nov 01, 2022 |
| Acer          | Aspire one                  | Notebook    | [bfb9f97d74](https://linux-hardware.org/?probe=bfb9f97d74) | Oct 31, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c9e0b81f80](https://linux-hardware.org/?probe=c9e0b81f80) | Oct 31, 2022 |
| MSI           | MEG Z590 ACE                | Desktop     | [1082f00d60](https://linux-hardware.org/?probe=1082f00d60) | Oct 31, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [f31f613901](https://linux-hardware.org/?probe=f31f613901) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | Notebook    | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [6f1d41a85c](https://linux-hardware.org/?probe=6f1d41a85c) | Oct 31, 2022 |
| Acer          | Aspire one                  | Notebook    | [82b34552f6](https://linux-hardware.org/?probe=82b34552f6) | Oct 31, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [fb96cd8e21](https://linux-hardware.org/?probe=fb96cd8e21) | Oct 31, 2022 |
| Chuwi         | LarkBox X                   | Mini pc     | [ed3f906a17](https://linux-hardware.org/?probe=ed3f906a17) | Oct 31, 2022 |
| Intel         | DG41AN AAE92991-401         | Desktop     | [cd670cef3d](https://linux-hardware.org/?probe=cd670cef3d) | Oct 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [e4b4e0456d](https://linux-hardware.org/?probe=e4b4e0456d) | Oct 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [0c1875c94f](https://linux-hardware.org/?probe=0c1875c94f) | Oct 31, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [4179fe16d6](https://linux-hardware.org/?probe=4179fe16d6) | Oct 31, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [00e1f1f754](https://linux-hardware.org/?probe=00e1f1f754) | Oct 31, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [a872c9888a](https://linux-hardware.org/?probe=a872c9888a) | Oct 30, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3fbcca75d5](https://linux-hardware.org/?probe=3fbcca75d5) | Oct 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [45f670d99f](https://linux-hardware.org/?probe=45f670d99f) | Oct 30, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| HP            | 158B                        | Desktop     | [9c02b7fe58](https://linux-hardware.org/?probe=9c02b7fe58) | Oct 30, 2022 |
| Chuwi         | LarkBox X                   | Mini pc     | [5cd057be2a](https://linux-hardware.org/?probe=5cd057be2a) | Oct 30, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [eea92055f3](https://linux-hardware.org/?probe=eea92055f3) | Oct 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [9991d15803](https://linux-hardware.org/?probe=9991d15803) | Oct 30, 2022 |
| ASUSTek       | TP401CA                     | Convertible | [8d97908e58](https://linux-hardware.org/?probe=8d97908e58) | Oct 30, 2022 |
| Dell          | Latitude 5501               | Notebook    | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| Notebook      | W230SD                      | Notebook    | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d99707ef15](https://linux-hardware.org/?probe=d99707ef15) | Oct 29, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [16815dacc1](https://linux-hardware.org/?probe=16815dacc1) | Oct 29, 2022 |
| Dell          | Latitude 5590               | Notebook    | [c7fa986fbd](https://linux-hardware.org/?probe=c7fa986fbd) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| Insyde        | Braswell                    | Notebook    | [d98b2d9661](https://linux-hardware.org/?probe=d98b2d9661) | Oct 29, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | Notebook    | [4acb2d0863](https://linux-hardware.org/?probe=4acb2d0863) | Oct 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [182d67f23e](https://linux-hardware.org/?probe=182d67f23e) | Oct 29, 2022 |
| Dell          | XPS 17 9720                 | Notebook    | [270b988521](https://linux-hardware.org/?probe=270b988521) | Oct 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [30f6ad7a26](https://linux-hardware.org/?probe=30f6ad7a26) | Oct 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [b81923dbd2](https://linux-hardware.org/?probe=b81923dbd2) | Oct 29, 2022 |
| libre-comp... | aml-s905x-cc                | Soc         | [0258982a5a](https://linux-hardware.org/?probe=0258982a5a) | Oct 29, 2022 |
| MSI           | Modern 15 A10RBS            | Notebook    | [ddc3eded89](https://linux-hardware.org/?probe=ddc3eded89) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [60d1db050b](https://linux-hardware.org/?probe=60d1db050b) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [2a9f06c2b4](https://linux-hardware.org/?probe=2a9f06c2b4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [787904d265](https://linux-hardware.org/?probe=787904d265) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [0971db18ed](https://linux-hardware.org/?probe=0971db18ed) | Oct 28, 2022 |
| Supermicro    | X12DPU-6A                   | Server      | [28c143d1f2](https://linux-hardware.org/?probe=28c143d1f2) | Oct 28, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [0fa70f29d4](https://linux-hardware.org/?probe=0fa70f29d4) | Oct 28, 2022 |
| Lenovo        | ThinkPad T530 239242U       | Notebook    | [dbf70338e9](https://linux-hardware.org/?probe=dbf70338e9) | Oct 28, 2022 |
| Unknown       | 775V88+                     | Desktop     | [f1a685b497](https://linux-hardware.org/?probe=f1a685b497) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| Dell          | Latitude 5280               | Notebook    | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [81121b7762](https://linux-hardware.org/?probe=81121b7762) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [0696abd43c](https://linux-hardware.org/?probe=0696abd43c) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [d42867d201](https://linux-hardware.org/?probe=d42867d201) | Oct 28, 2022 |
| Unknown       | Unknown                     | Soc         | [44fc490d82](https://linux-hardware.org/?probe=44fc490d82) | Oct 28, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [bace747804](https://linux-hardware.org/?probe=bace747804) | Oct 28, 2022 |
| HP            | 3396                        | Desktop     | [d42479acb8](https://linux-hardware.org/?probe=d42479acb8) | Oct 28, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [78b0c55e62](https://linux-hardware.org/?probe=78b0c55e62) | Oct 28, 2022 |
| Unknown       | Unknown                     | Server      | [cdca95f7e5](https://linux-hardware.org/?probe=cdca95f7e5) | Oct 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d3cf194e94](https://linux-hardware.org/?probe=d3cf194e94) | Oct 28, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [02c6d1fe1a](https://linux-hardware.org/?probe=02c6d1fe1a) | Oct 28, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | Notebook    | [768c6c8357](https://linux-hardware.org/?probe=768c6c8357) | Oct 28, 2022 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [db8c0489f4](https://linux-hardware.org/?probe=db8c0489f4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [63565608d1](https://linux-hardware.org/?probe=63565608d1) | Oct 28, 2022 |
| Google        | Boten                       | Notebook    | [2ed6baabf0](https://linux-hardware.org/?probe=2ed6baabf0) | Oct 27, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [2b886c255e](https://linux-hardware.org/?probe=2b886c255e) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [24da197a3a](https://linux-hardware.org/?probe=24da197a3a) | Oct 27, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [0bf03c49f7](https://linux-hardware.org/?probe=0bf03c49f7) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [3ab1fbc8e8](https://linux-hardware.org/?probe=3ab1fbc8e8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [faafe16cfb](https://linux-hardware.org/?probe=faafe16cfb) | Oct 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b682a38061](https://linux-hardware.org/?probe=b682a38061) | Oct 27, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [175f39979c](https://linux-hardware.org/?probe=175f39979c) | Oct 27, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [98cd87adf9](https://linux-hardware.org/?probe=98cd87adf9) | Oct 27, 2022 |
| THTF          | CR F860-T1                  | Notebook    | [0e20f4f61a](https://linux-hardware.org/?probe=0e20f4f61a) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1bc5db124b](https://linux-hardware.org/?probe=1bc5db124b) | Oct 27, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [bfd570bbef](https://linux-hardware.org/?probe=bfd570bbef) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [58820ca517](https://linux-hardware.org/?probe=58820ca517) | Oct 26, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [acdfb9b02e](https://linux-hardware.org/?probe=acdfb9b02e) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [6b9a3ab27e](https://linux-hardware.org/?probe=6b9a3ab27e) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [a5bd8bebc7](https://linux-hardware.org/?probe=a5bd8bebc7) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [bce3a8b1b3](https://linux-hardware.org/?probe=bce3a8b1b3) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [65a1d5242f](https://linux-hardware.org/?probe=65a1d5242f) | Oct 26, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [0d3545c6aa](https://linux-hardware.org/?probe=0d3545c6aa) | Oct 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [118fed891f](https://linux-hardware.org/?probe=118fed891f) | Oct 26, 2022 |
| Lenovo        | ThinkPad L380 Yoga 20M7C... | Convertible | [1d55c9b411](https://linux-hardware.org/?probe=1d55c9b411) | Oct 26, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [0b8dc998a9](https://linux-hardware.org/?probe=0b8dc998a9) | Oct 26, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [c1067e423b](https://linux-hardware.org/?probe=c1067e423b) | Oct 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ff62c670fd](https://linux-hardware.org/?probe=ff62c670fd) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [93b8dd8c3e](https://linux-hardware.org/?probe=93b8dd8c3e) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [5e08852d18](https://linux-hardware.org/?probe=5e08852d18) | Oct 25, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [b5dcdb6844](https://linux-hardware.org/?probe=b5dcdb6844) | Oct 25, 2022 |
| IBM           | 81Y7045                     | Server      | [27bd1ebecd](https://linux-hardware.org/?probe=27bd1ebecd) | Oct 25, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [08b673e57b](https://linux-hardware.org/?probe=08b673e57b) | Oct 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b0f36ae0c5](https://linux-hardware.org/?probe=b0f36ae0c5) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [438afb4185](https://linux-hardware.org/?probe=438afb4185) | Oct 25, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [739b6fc4a9](https://linux-hardware.org/?probe=739b6fc4a9) | Oct 25, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [f8466185a4](https://linux-hardware.org/?probe=f8466185a4) | Oct 25, 2022 |
| Toshiba       | dynabook MX/33KBL           | Notebook    | [7ee9057da2](https://linux-hardware.org/?probe=7ee9057da2) | Oct 25, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [bb1a7da646](https://linux-hardware.org/?probe=bb1a7da646) | Oct 25, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [c0fb49f07a](https://linux-hardware.org/?probe=c0fb49f07a) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9604dda439](https://linux-hardware.org/?probe=9604dda439) | Oct 24, 2022 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [54710cefe5](https://linux-hardware.org/?probe=54710cefe5) | Oct 24, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [1deed99314](https://linux-hardware.org/?probe=1deed99314) | Oct 24, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [ee86cdac2a](https://linux-hardware.org/?probe=ee86cdac2a) | Oct 24, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [eae727e6a0](https://linux-hardware.org/?probe=eae727e6a0) | Oct 24, 2022 |
| Dell          | 0M5WNK A00                  | Desktop     | [fad0f2f50e](https://linux-hardware.org/?probe=fad0f2f50e) | Oct 24, 2022 |
| Packard Be... | DOT S                       | Notebook    | [f280a6ccbc](https://linux-hardware.org/?probe=f280a6ccbc) | Oct 24, 2022 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [0d21d658ee](https://linux-hardware.org/?probe=0d21d658ee) | Oct 24, 2022 |
| Lenovo        | ThinkPad T470 20HES4VB00    | Notebook    | [f7b39d371a](https://linux-hardware.org/?probe=f7b39d371a) | Oct 24, 2022 |
| Packard Be... | H17HV                       | Notebook    | [2e94cfdd84](https://linux-hardware.org/?probe=2e94cfdd84) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [f64d3223c5](https://linux-hardware.org/?probe=f64d3223c5) | Oct 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dd05575bb4](https://linux-hardware.org/?probe=dd05575bb4) | Oct 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d2cb5dc9c7](https://linux-hardware.org/?probe=d2cb5dc9c7) | Oct 24, 2022 |
| Alienware     | M11xR3                      | Notebook    | [62bf8b7b02](https://linux-hardware.org/?probe=62bf8b7b02) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [c4fddde4b6](https://linux-hardware.org/?probe=c4fddde4b6) | Oct 24, 2022 |
| HP            | Pavilion g4                 | Notebook    | [3b6666b5ba](https://linux-hardware.org/?probe=3b6666b5ba) | Oct 24, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [083b2c218e](https://linux-hardware.org/?probe=083b2c218e) | Oct 24, 2022 |
| Biostar       | B450MH                      | Desktop     | [048cd18957](https://linux-hardware.org/?probe=048cd18957) | Oct 24, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [ce3e956a0a](https://linux-hardware.org/?probe=ce3e956a0a) | Oct 24, 2022 |
| ASRock        | Z97 Anniversary             | Desktop     | [9c94714d56](https://linux-hardware.org/?probe=9c94714d56) | Oct 24, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [86e8f9141a](https://linux-hardware.org/?probe=86e8f9141a) | Oct 24, 2022 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [9d2d49b8e4](https://linux-hardware.org/?probe=9d2d49b8e4) | Oct 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [50b6612f7d](https://linux-hardware.org/?probe=50b6612f7d) | Oct 23, 2022 |
| ASRock        | G31M-S                      | Desktop     | [5f1ca232ea](https://linux-hardware.org/?probe=5f1ca232ea) | Oct 23, 2022 |
| Dell          | Precision 7750              | Notebook    | [dd51bb7ccd](https://linux-hardware.org/?probe=dd51bb7ccd) | Oct 23, 2022 |
| HP            | Pavilion g4                 | Notebook    | [487a972bda](https://linux-hardware.org/?probe=487a972bda) | Oct 23, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [678916671d](https://linux-hardware.org/?probe=678916671d) | Oct 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [dcb8b694a7](https://linux-hardware.org/?probe=dcb8b694a7) | Oct 23, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [1a49be478c](https://linux-hardware.org/?probe=1a49be478c) | Oct 22, 2022 |
| Panasonic     | CF-LX3J-50M3                | Notebook    | [949acb4c3a](https://linux-hardware.org/?probe=949acb4c3a) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [6437fb22e1](https://linux-hardware.org/?probe=6437fb22e1) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [a19b5987c6](https://linux-hardware.org/?probe=a19b5987c6) | Oct 22, 2022 |
| Dell          | Latitude E6520              | Notebook    | [88af6c857c](https://linux-hardware.org/?probe=88af6c857c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | Notebook    | [246517ceab](https://linux-hardware.org/?probe=246517ceab) | Oct 22, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [2570a4e51f](https://linux-hardware.org/?probe=2570a4e51f) | Oct 22, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [165ce75570](https://linux-hardware.org/?probe=165ce75570) | Oct 21, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [168cbb8438](https://linux-hardware.org/?probe=168cbb8438) | Oct 21, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [2449f6a1b7](https://linux-hardware.org/?probe=2449f6a1b7) | Oct 21, 2022 |
| Aquarius      | NS585                       | Notebook    | [c953c5090c](https://linux-hardware.org/?probe=c953c5090c) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [efbd4959b8](https://linux-hardware.org/?probe=efbd4959b8) | Oct 21, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [55a46537f8](https://linux-hardware.org/?probe=55a46537f8) | Oct 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [a59f545a7b](https://linux-hardware.org/?probe=a59f545a7b) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [b13dc58884](https://linux-hardware.org/?probe=b13dc58884) | Oct 20, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [f60716afd0](https://linux-hardware.org/?probe=f60716afd0) | Oct 20, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [c9d76cd138](https://linux-hardware.org/?probe=c9d76cd138) | Oct 20, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [3bfbc8dcac](https://linux-hardware.org/?probe=3bfbc8dcac) | Oct 20, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [823d998220](https://linux-hardware.org/?probe=823d998220) | Oct 20, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [1e76467975](https://linux-hardware.org/?probe=1e76467975) | Oct 20, 2022 |
| Gigabyte      | GA-6LXSV 00000001           | Desktop     | [ac15415eca](https://linux-hardware.org/?probe=ac15415eca) | Oct 20, 2022 |
| Aquarius      | NS585                       | Notebook    | [a134ed693c](https://linux-hardware.org/?probe=a134ed693c) | Oct 20, 2022 |
| Dell          | 0D4MD1 A02                  | Desktop     | [becbded076](https://linux-hardware.org/?probe=becbded076) | Oct 20, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [162e7a20b2](https://linux-hardware.org/?probe=162e7a20b2) | Oct 20, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [e7875c59bc](https://linux-hardware.org/?probe=e7875c59bc) | Oct 20, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7799fd6266](https://linux-hardware.org/?probe=7799fd6266) | Oct 20, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [565e5d5e3b](https://linux-hardware.org/?probe=565e5d5e3b) | Oct 20, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| HP            | 245 G7                      | Notebook    | [9ec088c343](https://linux-hardware.org/?probe=9ec088c343) | Oct 19, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [d54932d557](https://linux-hardware.org/?probe=d54932d557) | Oct 19, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [5b61fd3a38](https://linux-hardware.org/?probe=5b61fd3a38) | Oct 19, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [285e78cfbe](https://linux-hardware.org/?probe=285e78cfbe) | Oct 19, 2022 |
| Dell          | Inspiron 7590               | Notebook    | [43ec5b2df8](https://linux-hardware.org/?probe=43ec5b2df8) | Oct 19, 2022 |
| HP            | 876C SMVB                   | Desktop     | [384313312d](https://linux-hardware.org/?probe=384313312d) | Oct 19, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1bdb835242](https://linux-hardware.org/?probe=1bdb835242) | Oct 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [67ebd92594](https://linux-hardware.org/?probe=67ebd92594) | Oct 19, 2022 |
| MSI           | H81M-P33                    | Desktop     | [784b068521](https://linux-hardware.org/?probe=784b068521) | Oct 19, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [42a1bedb35](https://linux-hardware.org/?probe=42a1bedb35) | Oct 19, 2022 |
| HP            | 8061                        | Desktop     | [8692ad745b](https://linux-hardware.org/?probe=8692ad745b) | Oct 19, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5e02a12da7](https://linux-hardware.org/?probe=5e02a12da7) | Oct 19, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [93584b3b67](https://linux-hardware.org/?probe=93584b3b67) | Oct 19, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [46a99f3d0e](https://linux-hardware.org/?probe=46a99f3d0e) | Oct 18, 2022 |
| Fujitsu       | LIFEBOOK E753               | Notebook    | [1fbb05ae6b](https://linux-hardware.org/?probe=1fbb05ae6b) | Oct 18, 2022 |
| HP            | 0A58h                       | Desktop     | [4c8d533bb0](https://linux-hardware.org/?probe=4c8d533bb0) | Oct 18, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [e800d683ef](https://linux-hardware.org/?probe=e800d683ef) | Oct 18, 2022 |
| Dell          | 0K7CVF A03                  | Server      | [f5274874b0](https://linux-hardware.org/?probe=f5274874b0) | Oct 18, 2022 |
| HP            | 3047h                       | Desktop     | [c1716b926a](https://linux-hardware.org/?probe=c1716b926a) | Oct 18, 2022 |
| Giga-Byte ... | i440BX-W977                 | Desktop     | [018daa60e1](https://linux-hardware.org/?probe=018daa60e1) | Oct 18, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [5ee12be257](https://linux-hardware.org/?probe=5ee12be257) | Oct 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [40c831481b](https://linux-hardware.org/?probe=40c831481b) | Oct 18, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [86b92cdc50](https://linux-hardware.org/?probe=86b92cdc50) | Oct 18, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [f7f13866aa](https://linux-hardware.org/?probe=f7f13866aa) | Oct 18, 2022 |
| Dell          | 0DFRFW A01                  | Desktop     | [dd4ada0631](https://linux-hardware.org/?probe=dd4ada0631) | Oct 18, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [db3ce64578](https://linux-hardware.org/?probe=db3ce64578) | Oct 18, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [621cca0fca](https://linux-hardware.org/?probe=621cca0fca) | Oct 18, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d458ae27cf](https://linux-hardware.org/?probe=d458ae27cf) | Oct 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e61760eab3](https://linux-hardware.org/?probe=e61760eab3) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IAH7 82S... | Notebook    | [dfa3140411](https://linux-hardware.org/?probe=dfa3140411) | Oct 17, 2022 |
| Dell          | 0WG864                      | Desktop     | [2feb42b3cf](https://linux-hardware.org/?probe=2feb42b3cf) | Oct 17, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [5368bd3ad6](https://linux-hardware.org/?probe=5368bd3ad6) | Oct 17, 2022 |
| HP            | 8158 A01                    | Mini pc     | [d7021dfe8a](https://linux-hardware.org/?probe=d7021dfe8a) | Oct 17, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [e076f9208c](https://linux-hardware.org/?probe=e076f9208c) | Oct 17, 2022 |
| HP            | 1589                        | Desktop     | [a6be3ee931](https://linux-hardware.org/?probe=a6be3ee931) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [10bcc184e7](https://linux-hardware.org/?probe=10bcc184e7) | Oct 17, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [6a523a41da](https://linux-hardware.org/?probe=6a523a41da) | Oct 17, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [d86b86e8a8](https://linux-hardware.org/?probe=d86b86e8a8) | Oct 17, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [464ce69071](https://linux-hardware.org/?probe=464ce69071) | Oct 17, 2022 |
| HP            | 1589                        | Desktop     | [c36aa260eb](https://linux-hardware.org/?probe=c36aa260eb) | Oct 17, 2022 |
| Acer          | MCP7A                       | Desktop     | [32f914d009](https://linux-hardware.org/?probe=32f914d009) | Oct 17, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [d55b50c6c7](https://linux-hardware.org/?probe=d55b50c6c7) | Oct 16, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [4af4c60051](https://linux-hardware.org/?probe=4af4c60051) | Oct 16, 2022 |
| Gigabyte      | C246N-WU2-CF                | Desktop     | [cb7ca4eb5a](https://linux-hardware.org/?probe=cb7ca4eb5a) | Oct 16, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [a88a291921](https://linux-hardware.org/?probe=a88a291921) | Oct 16, 2022 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [b6162e2c5e](https://linux-hardware.org/?probe=b6162e2c5e) | Oct 16, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [c0feb12708](https://linux-hardware.org/?probe=c0feb12708) | Oct 16, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| Dell          | Latitude 3320               | Notebook    | [e4645890b8](https://linux-hardware.org/?probe=e4645890b8) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [ae7d737ee5](https://linux-hardware.org/?probe=ae7d737ee5) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5cbc449f36](https://linux-hardware.org/?probe=5cbc449f36) | Oct 16, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [f26592e956](https://linux-hardware.org/?probe=f26592e956) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [fb37bc6617](https://linux-hardware.org/?probe=fb37bc6617) | Oct 15, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [6a6f7314c0](https://linux-hardware.org/?probe=6a6f7314c0) | Oct 15, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [f9568da63c](https://linux-hardware.org/?probe=f9568da63c) | Oct 15, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [b226135430](https://linux-hardware.org/?probe=b226135430) | Oct 15, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [27e1ded122](https://linux-hardware.org/?probe=27e1ded122) | Oct 15, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [aee52607f0](https://linux-hardware.org/?probe=aee52607f0) | Oct 14, 2022 |
| Panasonic     | CF-LX3J-50M3                | Notebook    | [95386977de](https://linux-hardware.org/?probe=95386977de) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [8cf96a6d0b](https://linux-hardware.org/?probe=8cf96a6d0b) | Oct 14, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [ea0fc2d497](https://linux-hardware.org/?probe=ea0fc2d497) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [a68e7df338](https://linux-hardware.org/?probe=a68e7df338) | Oct 14, 2022 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [ebada4e791](https://linux-hardware.org/?probe=ebada4e791) | Oct 14, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [85766540b3](https://linux-hardware.org/?probe=85766540b3) | Oct 14, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [82a7e620f0](https://linux-hardware.org/?probe=82a7e620f0) | Oct 14, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [06e46e98b4](https://linux-hardware.org/?probe=06e46e98b4) | Oct 14, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [5a0485a292](https://linux-hardware.org/?probe=5a0485a292) | Oct 14, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [9554b1f29a](https://linux-hardware.org/?probe=9554b1f29a) | Oct 14, 2022 |
| Dell          | Latitude E6330              | Notebook    | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| ASUSTek       | P5QL-CM                     | Desktop     | [34c01c8045](https://linux-hardware.org/?probe=34c01c8045) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| MSI           | PRO B550-VC                 | Desktop     | [0141458d01](https://linux-hardware.org/?probe=0141458d01) | Oct 14, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| MSI           | MS-N014                     | Notebook    | [87e6e540be](https://linux-hardware.org/?probe=87e6e540be) | Oct 14, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [76678b6d58](https://linux-hardware.org/?probe=76678b6d58) | Oct 14, 2022 |
| Google        | Robo                        | Notebook    | [d070697e72](https://linux-hardware.org/?probe=d070697e72) | Oct 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ede8c7fa36](https://linux-hardware.org/?probe=ede8c7fa36) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a1b02901a1](https://linux-hardware.org/?probe=a1b02901a1) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a0f4cd454d](https://linux-hardware.org/?probe=a0f4cd454d) | Oct 13, 2022 |
| Dell          | 0JD6X3 A05                  | Server      | [746232aa34](https://linux-hardware.org/?probe=746232aa34) | Oct 13, 2022 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [6a810d253c](https://linux-hardware.org/?probe=6a810d253c) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [dfc5a5f754](https://linux-hardware.org/?probe=dfc5a5f754) | Oct 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1e2eda446c](https://linux-hardware.org/?probe=1e2eda446c) | Oct 13, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [067097bef8](https://linux-hardware.org/?probe=067097bef8) | Oct 13, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [3a9f1fa240](https://linux-hardware.org/?probe=3a9f1fa240) | Oct 13, 2022 |
| HP            | 158A                        | Desktop     | [6b1d53174a](https://linux-hardware.org/?probe=6b1d53174a) | Oct 12, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | Notebook    | [e560a29570](https://linux-hardware.org/?probe=e560a29570) | Oct 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [00d174fcf4](https://linux-hardware.org/?probe=00d174fcf4) | Oct 12, 2022 |
| HP            | 3047h                       | Desktop     | [ba7f593887](https://linux-hardware.org/?probe=ba7f593887) | Oct 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [744091dcaa](https://linux-hardware.org/?probe=744091dcaa) | Oct 12, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [55bb52409c](https://linux-hardware.org/?probe=55bb52409c) | Oct 12, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [585b7e9773](https://linux-hardware.org/?probe=585b7e9773) | Oct 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [ccee0b66d9](https://linux-hardware.org/?probe=ccee0b66d9) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | Notebook    | [22904f1270](https://linux-hardware.org/?probe=22904f1270) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | Notebook    | [ecd8555f97](https://linux-hardware.org/?probe=ecd8555f97) | Oct 12, 2022 |
| Thomson       | N14C4WH64                   | Notebook    | [bfc16b9ded](https://linux-hardware.org/?probe=bfc16b9ded) | Oct 12, 2022 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [400bc2da98](https://linux-hardware.org/?probe=400bc2da98) | Oct 11, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [300975f708](https://linux-hardware.org/?probe=300975f708) | Oct 11, 2022 |
| ASUSTek       | N53Jg                       | Notebook    | [0b4302ed6c](https://linux-hardware.org/?probe=0b4302ed6c) | Oct 11, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [eac6add22e](https://linux-hardware.org/?probe=eac6add22e) | Oct 11, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [8b4c66e10a](https://linux-hardware.org/?probe=8b4c66e10a) | Oct 11, 2022 |
| Dell          | Precision 7720              | Notebook    | [2252c7bd79](https://linux-hardware.org/?probe=2252c7bd79) | Oct 11, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f512c7bf3f](https://linux-hardware.org/?probe=f512c7bf3f) | Oct 11, 2022 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [6a9fe776d8](https://linux-hardware.org/?probe=6a9fe776d8) | Oct 10, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [2504ad4fa5](https://linux-hardware.org/?probe=2504ad4fa5) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4687cf8900](https://linux-hardware.org/?probe=4687cf8900) | Oct 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [97bbb3b52b](https://linux-hardware.org/?probe=97bbb3b52b) | Oct 09, 2022 |
| Unknown       | Seagate Personal Cloud (... | Desktop     | [40ea197650](https://linux-hardware.org/?probe=40ea197650) | Oct 09, 2022 |
| Toshiba       | Satellite A100              | Notebook    | [f280857c1c](https://linux-hardware.org/?probe=f280857c1c) | Oct 09, 2022 |
| Dell          | Inspiron 14 5420            | Notebook    | [d9f937a8c4](https://linux-hardware.org/?probe=d9f937a8c4) | Oct 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bef5f7f7d7](https://linux-hardware.org/?probe=bef5f7f7d7) | Oct 09, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [1a6ea38863](https://linux-hardware.org/?probe=1a6ea38863) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [7785f0ebfb](https://linux-hardware.org/?probe=7785f0ebfb) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [ce045937bc](https://linux-hardware.org/?probe=ce045937bc) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [487fd1959f](https://linux-hardware.org/?probe=487fd1959f) | Oct 08, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [939e426600](https://linux-hardware.org/?probe=939e426600) | Oct 08, 2022 |
| Dell          | 003KPJ A00                  | Desktop     | [e151f6645b](https://linux-hardware.org/?probe=e151f6645b) | Oct 08, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9b5141f179](https://linux-hardware.org/?probe=9b5141f179) | Oct 08, 2022 |
| MSI           | H81M-E34                    | Desktop     | [154cb109bf](https://linux-hardware.org/?probe=154cb109bf) | Oct 08, 2022 |
| ASUSTek       | V-P8H67E                    | Desktop     | [b4f0f561d2](https://linux-hardware.org/?probe=b4f0f561d2) | Oct 08, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1798b09b89](https://linux-hardware.org/?probe=1798b09b89) | Oct 08, 2022 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [5b543dbd16](https://linux-hardware.org/?probe=5b543dbd16) | Oct 08, 2022 |
| Shuttle       | FS81                        | Desktop     | [ba7c22e135](https://linux-hardware.org/?probe=ba7c22e135) | Oct 07, 2022 |
| Shuttle       | FS81                        | Desktop     | [63ec5c8971](https://linux-hardware.org/?probe=63ec5c8971) | Oct 07, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [68137e0e8d](https://linux-hardware.org/?probe=68137e0e8d) | Oct 07, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [aa89234022](https://linux-hardware.org/?probe=aa89234022) | Oct 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [e6eac5c882](https://linux-hardware.org/?probe=e6eac5c882) | Oct 07, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [b27c3b70a7](https://linux-hardware.org/?probe=b27c3b70a7) | Oct 07, 2022 |
| ASRock        | Z68 Extreme4                | Desktop     | [6b96459f0a](https://linux-hardware.org/?probe=6b96459f0a) | Oct 07, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ab48a5156b](https://linux-hardware.org/?probe=ab48a5156b) | Oct 06, 2022 |
| Lenovo        | Inagua CRB                  | All in one  | [861af1fd97](https://linux-hardware.org/?probe=861af1fd97) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [d29b5fa9b0](https://linux-hardware.org/?probe=d29b5fa9b0) | Oct 06, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [bbf95bf34d](https://linux-hardware.org/?probe=bbf95bf34d) | Oct 06, 2022 |
| ASUSTek       | P5GDC Pro                   | Desktop     | [25ac480f76](https://linux-hardware.org/?probe=25ac480f76) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [1b09c0a820](https://linux-hardware.org/?probe=1b09c0a820) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a12d335502](https://linux-hardware.org/?probe=a12d335502) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0fa7893206](https://linux-hardware.org/?probe=0fa7893206) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [fd49fda31a](https://linux-hardware.org/?probe=fd49fda31a) | Oct 06, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [0f3387ce35](https://linux-hardware.org/?probe=0f3387ce35) | Oct 06, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ff783e01db](https://linux-hardware.org/?probe=ff783e01db) | Oct 06, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [0f3e9273a6](https://linux-hardware.org/?probe=0f3e9273a6) | Oct 06, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [de29fa755f](https://linux-hardware.org/?probe=de29fa755f) | Oct 05, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0432411e08](https://linux-hardware.org/?probe=0432411e08) | Oct 05, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [c287d961f7](https://linux-hardware.org/?probe=c287d961f7) | Oct 05, 2022 |
| Google        | Akemi                       | Notebook    | [5a165f46bc](https://linux-hardware.org/?probe=5a165f46bc) | Oct 05, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [1b399dcbb2](https://linux-hardware.org/?probe=1b399dcbb2) | Oct 05, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [3079a45a56](https://linux-hardware.org/?probe=3079a45a56) | Oct 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [96b4cda722](https://linux-hardware.org/?probe=96b4cda722) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [02d4090cce](https://linux-hardware.org/?probe=02d4090cce) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [4f037d4c3d](https://linux-hardware.org/?probe=4f037d4c3d) | Oct 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [bbea875fdc](https://linux-hardware.org/?probe=bbea875fdc) | Oct 05, 2022 |
| Lenovo        | ThinkStation S30 0569BE3    | Desktop     | [026d1ee25e](https://linux-hardware.org/?probe=026d1ee25e) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [93698d1670](https://linux-hardware.org/?probe=93698d1670) | Oct 05, 2022 |
| Toshiba       | NB505                       | Notebook    | [9de39780b5](https://linux-hardware.org/?probe=9de39780b5) | Oct 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [0ed1bfe4ef](https://linux-hardware.org/?probe=0ed1bfe4ef) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [dea0d04059](https://linux-hardware.org/?probe=dea0d04059) | Oct 05, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [ab3508b938](https://linux-hardware.org/?probe=ab3508b938) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [8b9d1152e4](https://linux-hardware.org/?probe=8b9d1152e4) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [8631c6f717](https://linux-hardware.org/?probe=8631c6f717) | Oct 04, 2022 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| TrekStor      | Primebook C13               | Convertible | [8e07444c9b](https://linux-hardware.org/?probe=8e07444c9b) | Oct 04, 2022 |
| HP            | EliteBook 735 G6            | Notebook    | [c3f86b0e1a](https://linux-hardware.org/?probe=c3f86b0e1a) | Oct 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [33b42f3ed1](https://linux-hardware.org/?probe=33b42f3ed1) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [5b2fac59ea](https://linux-hardware.org/?probe=5b2fac59ea) | Oct 04, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Lenovo        | ThinkPad Twist 20C41A3      | Notebook    | [3da96ac399](https://linux-hardware.org/?probe=3da96ac399) | Oct 04, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [e799907aba](https://linux-hardware.org/?probe=e799907aba) | Oct 04, 2022 |
| Dell          | Precision M4800             | Notebook    | [1099761dca](https://linux-hardware.org/?probe=1099761dca) | Oct 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [31fa8b62ff](https://linux-hardware.org/?probe=31fa8b62ff) | Oct 04, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [38f5b56e5d](https://linux-hardware.org/?probe=38f5b56e5d) | Oct 04, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [ed3bf1e99b](https://linux-hardware.org/?probe=ed3bf1e99b) | Oct 04, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4ab2e51cc3](https://linux-hardware.org/?probe=4ab2e51cc3) | Oct 04, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [a9e9513b41](https://linux-hardware.org/?probe=a9e9513b41) | Oct 04, 2022 |
| Dell          | 0D4MD1 A00                  | Desktop     | [9ab1446c27](https://linux-hardware.org/?probe=9ab1446c27) | Oct 04, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [851214001a](https://linux-hardware.org/?probe=851214001a) | Oct 04, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [1c6fd70d5f](https://linux-hardware.org/?probe=1c6fd70d5f) | Oct 04, 2022 |
| Dell          | Latitude E7240              | Notebook    | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| HP            | 1906                        | Desktop     | [a6f705f119](https://linux-hardware.org/?probe=a6f705f119) | Oct 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [81ac41d8b9](https://linux-hardware.org/?probe=81ac41d8b9) | Oct 03, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [bc9c9eb996](https://linux-hardware.org/?probe=bc9c9eb996) | Oct 03, 2022 |
| Dell          | Latitude 2110               | Notebook    | [3fbbac2c8a](https://linux-hardware.org/?probe=3fbbac2c8a) | Oct 03, 2022 |
| Supermicro    | X11SCH-F                    | Server      | [77cbd84a68](https://linux-hardware.org/?probe=77cbd84a68) | Oct 03, 2022 |
| ASUSTek       | 1225B                       | Notebook    | [9bb2d54ca7](https://linux-hardware.org/?probe=9bb2d54ca7) | Oct 03, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [1fb6d9ec64](https://linux-hardware.org/?probe=1fb6d9ec64) | Oct 03, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [47d31ff25c](https://linux-hardware.org/?probe=47d31ff25c) | Oct 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [1031dfcd50](https://linux-hardware.org/?probe=1031dfcd50) | Oct 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [64f2393fde](https://linux-hardware.org/?probe=64f2393fde) | Oct 03, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [66e22581f7](https://linux-hardware.org/?probe=66e22581f7) | Oct 03, 2022 |
| Dell          | Precision 3570              | Notebook    | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [0ea51f0746](https://linux-hardware.org/?probe=0ea51f0746) | Oct 03, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [e3a783a839](https://linux-hardware.org/?probe=e3a783a839) | Oct 02, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [ae39aea3e9](https://linux-hardware.org/?probe=ae39aea3e9) | Oct 02, 2022 |
| Lenovo        | ThinkPad T460s 20F90060G... | Notebook    | [8d17d38142](https://linux-hardware.org/?probe=8d17d38142) | Oct 02, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [31dcf67714](https://linux-hardware.org/?probe=31dcf67714) | Oct 02, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [97afbe98b8](https://linux-hardware.org/?probe=97afbe98b8) | Oct 02, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [78ff851478](https://linux-hardware.org/?probe=78ff851478) | Oct 02, 2022 |
| ASUSTek       | X71Q                        | Notebook    | [830c8ab6d2](https://linux-hardware.org/?probe=830c8ab6d2) | Oct 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [9b2e1432f2](https://linux-hardware.org/?probe=9b2e1432f2) | Oct 02, 2022 |
| Toshiba       | Satellite L45               | Notebook    | [79ff097329](https://linux-hardware.org/?probe=79ff097329) | Oct 02, 2022 |
| Acer          | Aspire A715-41G             | Notebook    | [1a473e9809](https://linux-hardware.org/?probe=1a473e9809) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [7915b298b2](https://linux-hardware.org/?probe=7915b298b2) | Oct 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [27bb1c39eb](https://linux-hardware.org/?probe=27bb1c39eb) | Oct 01, 2022 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | Notebook    | [fbe1e53387](https://linux-hardware.org/?probe=fbe1e53387) | Oct 01, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [29c4292c62](https://linux-hardware.org/?probe=29c4292c62) | Oct 01, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [3edc4043a3](https://linux-hardware.org/?probe=3edc4043a3) | Oct 01, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [21a601e10a](https://linux-hardware.org/?probe=21a601e10a) | Sep 30, 2022 |
| Intel         | NUC11ATBPE M49844-202       | Mini pc     | [9e0aff1fbd](https://linux-hardware.org/?probe=9e0aff1fbd) | Sep 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3c0e0b12ee](https://linux-hardware.org/?probe=3c0e0b12ee) | Sep 30, 2022 |
| HP            | 859C                        | Desktop     | [08161b9516](https://linux-hardware.org/?probe=08161b9516) | Sep 30, 2022 |
| Lenovo        | ThinkPad L380 20M5SSIN11    | Notebook    | [0cad79b1f7](https://linux-hardware.org/?probe=0cad79b1f7) | Sep 30, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [40e65e38cf](https://linux-hardware.org/?probe=40e65e38cf) | Sep 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [786e0c1f5d](https://linux-hardware.org/?probe=786e0c1f5d) | Sep 30, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [ee72cbd627](https://linux-hardware.org/?probe=ee72cbd627) | Sep 29, 2022 |
| HP            | Compaq nx6325 (EY344EA#A... | Notebook    | [8808f98c62](https://linux-hardware.org/?probe=8808f98c62) | Sep 29, 2022 |
| ECS           | G31T-M9                     | Desktop     | [45b25aaf8c](https://linux-hardware.org/?probe=45b25aaf8c) | Sep 29, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [6652e85ddd](https://linux-hardware.org/?probe=6652e85ddd) | Sep 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [64a7e86e22](https://linux-hardware.org/?probe=64a7e86e22) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | Notebook    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| Biostar       | H55 HD                      | Desktop     | [bde8e0a133](https://linux-hardware.org/?probe=bde8e0a133) | Sep 28, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [2045e665b1](https://linux-hardware.org/?probe=2045e665b1) | Sep 28, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [6d92b99f8e](https://linux-hardware.org/?probe=6d92b99f8e) | Sep 28, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b063a72d21](https://linux-hardware.org/?probe=b063a72d21) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| HP            | 339A                        | Desktop     | [5c961ef93f](https://linux-hardware.org/?probe=5c961ef93f) | Sep 28, 2022 |
| HP            | 339A                        | Desktop     | [ac9538b489](https://linux-hardware.org/?probe=ac9538b489) | Sep 28, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [82b108b3b8](https://linux-hardware.org/?probe=82b108b3b8) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | Notebook    | [ca9c7bf57b](https://linux-hardware.org/?probe=ca9c7bf57b) | Sep 28, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8990a66f30](https://linux-hardware.org/?probe=8990a66f30) | Sep 27, 2022 |
| Samsung       | SDNE-R78BA2-20              | Other       | [2278a5c6ea](https://linux-hardware.org/?probe=2278a5c6ea) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0031772f40](https://linux-hardware.org/?probe=0031772f40) | Sep 27, 2022 |
| MSI           | B365M PRO-VDH               | Desktop     | [45e07c7119](https://linux-hardware.org/?probe=45e07c7119) | Sep 27, 2022 |
| Medion        | MS-7728                     | Desktop     | [0b9b2ca570](https://linux-hardware.org/?probe=0b9b2ca570) | Sep 27, 2022 |
| HP            | 339A                        | Desktop     | [25ef7556cc](https://linux-hardware.org/?probe=25ef7556cc) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [757d465447](https://linux-hardware.org/?probe=757d465447) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [e3826dca71](https://linux-hardware.org/?probe=e3826dca71) | Sep 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fdf2d015bc](https://linux-hardware.org/?probe=fdf2d015bc) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [76a7224818](https://linux-hardware.org/?probe=76a7224818) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| HP            | 339A                        | Desktop     | [07986ca95e](https://linux-hardware.org/?probe=07986ca95e) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| HP            | 0B40h                       | Desktop     | [d72bb749ff](https://linux-hardware.org/?probe=d72bb749ff) | Sep 26, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [508c873693](https://linux-hardware.org/?probe=508c873693) | Sep 26, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [56e06deea2](https://linux-hardware.org/?probe=56e06deea2) | Sep 26, 2022 |
| IBM           | 69Y1006 SIT                 | Server      | [b1ab802cb1](https://linux-hardware.org/?probe=b1ab802cb1) | Sep 25, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [4e228116be](https://linux-hardware.org/?probe=4e228116be) | Sep 25, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6c9c3f13d0](https://linux-hardware.org/?probe=6c9c3f13d0) | Sep 25, 2022 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [779faa3cfd](https://linux-hardware.org/?probe=779faa3cfd) | Sep 25, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [2d7ce63bce](https://linux-hardware.org/?probe=2d7ce63bce) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [107011cb20](https://linux-hardware.org/?probe=107011cb20) | Sep 25, 2022 |
| Dell          | 00NH4P A07                  | Server      | [8b34a52b83](https://linux-hardware.org/?probe=8b34a52b83) | Sep 25, 2022 |
| Dell          | 0DPRKF A06                  | Server      | [f5fb43d9c5](https://linux-hardware.org/?probe=f5fb43d9c5) | Sep 25, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fdb7e646ca](https://linux-hardware.org/?probe=fdb7e646ca) | Sep 25, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [9ae6efbc0f](https://linux-hardware.org/?probe=9ae6efbc0f) | Sep 25, 2022 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [d09f4c4501](https://linux-hardware.org/?probe=d09f4c4501) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [65d54e7273](https://linux-hardware.org/?probe=65d54e7273) | Sep 25, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | Notebook    | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| Dell          | Inspiron 14 5425            | Notebook    | [209be443ac](https://linux-hardware.org/?probe=209be443ac) | Sep 24, 2022 |
| Google        | Teemo                       | Desktop     | [5ddc8b97b8](https://linux-hardware.org/?probe=5ddc8b97b8) | Sep 24, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [1d76ae9f44](https://linux-hardware.org/?probe=1d76ae9f44) | Sep 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [8a734f0799](https://linux-hardware.org/?probe=8a734f0799) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | Notebook    | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [0299e4f7b1](https://linux-hardware.org/?probe=0299e4f7b1) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [cad0f6f375](https://linux-hardware.org/?probe=cad0f6f375) | Sep 24, 2022 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [405ea9a4ca](https://linux-hardware.org/?probe=405ea9a4ca) | Sep 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4658ef6703](https://linux-hardware.org/?probe=4658ef6703) | Sep 24, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | Notebook    | [0adb7bc0b1](https://linux-hardware.org/?probe=0adb7bc0b1) | Sep 24, 2022 |
| VIT           | P2402                       | Notebook    | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [91d179670c](https://linux-hardware.org/?probe=91d179670c) | Sep 23, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5f1b4b1679](https://linux-hardware.org/?probe=5f1b4b1679) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Google        | Robo                        | Notebook    | [4772493ae3](https://linux-hardware.org/?probe=4772493ae3) | Sep 23, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [13ad69a13e](https://linux-hardware.org/?probe=13ad69a13e) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [8a4819f23d](https://linux-hardware.org/?probe=8a4819f23d) | Sep 23, 2022 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | Notebook    | [077c05c78d](https://linux-hardware.org/?probe=077c05c78d) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [6c884d4968](https://linux-hardware.org/?probe=6c884d4968) | Sep 23, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [985fa1c4c7](https://linux-hardware.org/?probe=985fa1c4c7) | Sep 23, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [39a94459dc](https://linux-hardware.org/?probe=39a94459dc) | Sep 23, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [c9f00bec8e](https://linux-hardware.org/?probe=c9f00bec8e) | Sep 23, 2022 |
| HP            | 876C SMVB                   | Desktop     | [c6fbf7c631](https://linux-hardware.org/?probe=c6fbf7c631) | Sep 23, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [f77dda559d](https://linux-hardware.org/?probe=f77dda559d) | Sep 23, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [c05619dc16](https://linux-hardware.org/?probe=c05619dc16) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | Notebook    | [412296c83f](https://linux-hardware.org/?probe=412296c83f) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [3d7933270a](https://linux-hardware.org/?probe=3d7933270a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [1e6b1b068a](https://linux-hardware.org/?probe=1e6b1b068a) | Sep 22, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [db6f733994](https://linux-hardware.org/?probe=db6f733994) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | Notebook    | [21ba0d8f46](https://linux-hardware.org/?probe=21ba0d8f46) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [a978086f1b](https://linux-hardware.org/?probe=a978086f1b) | Sep 22, 2022 |
| BESSTAR Te... | GB1                         | Mini pc     | [e2d1cd31c3](https://linux-hardware.org/?probe=e2d1cd31c3) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | Notebook    | [0c4627555a](https://linux-hardware.org/?probe=0c4627555a) | Sep 22, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [7e3170527c](https://linux-hardware.org/?probe=7e3170527c) | Sep 22, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7866b58669](https://linux-hardware.org/?probe=7866b58669) | Sep 22, 2022 |
| HP            | Notebook                    | Notebook    | [18b9221add](https://linux-hardware.org/?probe=18b9221add) | Sep 22, 2022 |
| Toshiba       | Satellite P745              | Notebook    | [963d04c729](https://linux-hardware.org/?probe=963d04c729) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [630b3877c4](https://linux-hardware.org/?probe=630b3877c4) | Sep 22, 2022 |
| MSI           | GS60 2PE                    | Notebook    | [1aaaa99706](https://linux-hardware.org/?probe=1aaaa99706) | Sep 22, 2022 |
| HP            | Presario CQ57               | Notebook    | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | Notebook    | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [fb451b6d7d](https://linux-hardware.org/?probe=fb451b6d7d) | Sep 22, 2022 |
| Avell High... | B.ON                        | Notebook    | [95c7e35ef3](https://linux-hardware.org/?probe=95c7e35ef3) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [41af175db4](https://linux-hardware.org/?probe=41af175db4) | Sep 21, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [c0cc0dc101](https://linux-hardware.org/?probe=c0cc0dc101) | Sep 21, 2022 |
| Lenovo        | ThinkCentre A70z 0401R6U    | Desktop     | [2a93ca040a](https://linux-hardware.org/?probe=2a93ca040a) | Sep 21, 2022 |
| Thecus        | N2810 0001                  | Desktop     | [f54df3994c](https://linux-hardware.org/?probe=f54df3994c) | Sep 21, 2022 |
| Avell High... | B.ON                        | Notebook    | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| ECS           | G31T-M9                     | Desktop     | [6e67780df1](https://linux-hardware.org/?probe=6e67780df1) | Sep 21, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a9e18191f7](https://linux-hardware.org/?probe=a9e18191f7) | Sep 21, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [e267d78b42](https://linux-hardware.org/?probe=e267d78b42) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| Inspur        | CE520F                      | Soc         | [b8ea59e9f8](https://linux-hardware.org/?probe=b8ea59e9f8) | Sep 21, 2022 |
| Dell          | Precision 7540              | Notebook    | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| Xunlong       | Orange Pi Zero              | Soc         | [0aa622cc13](https://linux-hardware.org/?probe=0aa622cc13) | Sep 21, 2022 |
| ECS           | G31T-M9                     | Desktop     | [46fd18ee44](https://linux-hardware.org/?probe=46fd18ee44) | Sep 21, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [03e6d4f5bc](https://linux-hardware.org/?probe=03e6d4f5bc) | Sep 21, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [658141844b](https://linux-hardware.org/?probe=658141844b) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| Lenovo        | ThinkCentre M57 6072WMD     | Desktop     | [eb8221088f](https://linux-hardware.org/?probe=eb8221088f) | Sep 21, 2022 |
| HP            | 158A                        | Desktop     | [428326af76](https://linux-hardware.org/?probe=428326af76) | Sep 21, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5c6ebb2cfe](https://linux-hardware.org/?probe=5c6ebb2cfe) | Sep 21, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [da32f7dbfb](https://linux-hardware.org/?probe=da32f7dbfb) | Sep 21, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [0ada4a5b83](https://linux-hardware.org/?probe=0ada4a5b83) | Sep 20, 2022 |
| ASUSTek       | G20CB                       | Desktop     | [34f4d43b97](https://linux-hardware.org/?probe=34f4d43b97) | Sep 20, 2022 |
| Shuttle       | FS81                        | Desktop     | [4c1fb942aa](https://linux-hardware.org/?probe=4c1fb942aa) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [172fd1874d](https://linux-hardware.org/?probe=172fd1874d) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | Desktop     | [e1258b712e](https://linux-hardware.org/?probe=e1258b712e) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | Desktop     | [6f2ce8e794](https://linux-hardware.org/?probe=6f2ce8e794) | Sep 20, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [f9fa37f0d2](https://linux-hardware.org/?probe=f9fa37f0d2) | Sep 20, 2022 |
| Lenovo        | ThinkPad T490 20N2001YUS    | Notebook    | [5861c90514](https://linux-hardware.org/?probe=5861c90514) | Sep 20, 2022 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [450a86c900](https://linux-hardware.org/?probe=450a86c900) | Sep 20, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [ecd62e14f4](https://linux-hardware.org/?probe=ecd62e14f4) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad X260 20F5003EMB    | Notebook    | [302eacc4ff](https://linux-hardware.org/?probe=302eacc4ff) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Unknown       | 1.0                         | Desktop     | [1ef071c553](https://linux-hardware.org/?probe=1ef071c553) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [7967e43f1d](https://linux-hardware.org/?probe=7967e43f1d) | Sep 20, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [37fcfc48c5](https://linux-hardware.org/?probe=37fcfc48c5) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | Notebook    | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [979765d106](https://linux-hardware.org/?probe=979765d106) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [a0a61b5d8c](https://linux-hardware.org/?probe=a0a61b5d8c) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [bb8e3ae62a](https://linux-hardware.org/?probe=bb8e3ae62a) | Sep 20, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [14351cab57](https://linux-hardware.org/?probe=14351cab57) | Sep 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [96e0712ca0](https://linux-hardware.org/?probe=96e0712ca0) | Sep 19, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [ee235bf98c](https://linux-hardware.org/?probe=ee235bf98c) | Sep 19, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e98a0964e8](https://linux-hardware.org/?probe=e98a0964e8) | Sep 19, 2022 |
| Lenovo        | ThinkPad SL400 2743AQC      | Notebook    | [beb74c65cc](https://linux-hardware.org/?probe=beb74c65cc) | Sep 19, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [89adb3b190](https://linux-hardware.org/?probe=89adb3b190) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [9457acbe13](https://linux-hardware.org/?probe=9457acbe13) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HP            | 15                          | Notebook    | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [0f049ae5d6](https://linux-hardware.org/?probe=0f049ae5d6) | Sep 19, 2022 |
| HP            | 15                          | Notebook    | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [74e31be1be](https://linux-hardware.org/?probe=74e31be1be) | Sep 19, 2022 |
| AZW           | GK55                        | Desktop     | [9a9019eee6](https://linux-hardware.org/?probe=9a9019eee6) | Sep 19, 2022 |
| HP            | G42                         | Notebook    | [3f584eb1af](https://linux-hardware.org/?probe=3f584eb1af) | Sep 19, 2022 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [d202b0a504](https://linux-hardware.org/?probe=d202b0a504) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| HUAWEI        | PGU-WBY0                    | Soc         | [3f3d475864](https://linux-hardware.org/?probe=3f3d475864) | Sep 19, 2022 |
| Supermicro    | X10DRi-T4+                  | Desktop     | [1f507cde8c](https://linux-hardware.org/?probe=1f507cde8c) | Sep 19, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [37fc6237e2](https://linux-hardware.org/?probe=37fc6237e2) | Sep 19, 2022 |
| Panasonic     | CF-53JAWZYDE                | Notebook    | [f8b1ca10d1](https://linux-hardware.org/?probe=f8b1ca10d1) | Sep 19, 2022 |
| HP            | 1998                        | Desktop     | [14eeedb712](https://linux-hardware.org/?probe=14eeedb712) | Sep 18, 2022 |
| Dell          | 0KY237 A01                  | Desktop     | [8b2d50f5d1](https://linux-hardware.org/?probe=8b2d50f5d1) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| Lenovo        | IdeaPad 720s-13ARR 81BR     | Notebook    | [fa45602fc5](https://linux-hardware.org/?probe=fa45602fc5) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [b94564300a](https://linux-hardware.org/?probe=b94564300a) | Sep 18, 2022 |
| Dell          | Latitude E6330              | Notebook    | [bbb0a5f1a1](https://linux-hardware.org/?probe=bbb0a5f1a1) | Sep 18, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4de8502362](https://linux-hardware.org/?probe=4de8502362) | Sep 18, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7b918ebeb8](https://linux-hardware.org/?probe=7b918ebeb8) | Sep 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [87c3b99589](https://linux-hardware.org/?probe=87c3b99589) | Sep 18, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [c1045050d6](https://linux-hardware.org/?probe=c1045050d6) | Sep 17, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [3de0a6e725](https://linux-hardware.org/?probe=3de0a6e725) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [6c5b0c0659](https://linux-hardware.org/?probe=6c5b0c0659) | Sep 17, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | Notebook    | [1fa176a244](https://linux-hardware.org/?probe=1fa176a244) | Sep 17, 2022 |
| Intel         | NUC11ATBC4 M53051-303       | Mini pc     | [e90f168305](https://linux-hardware.org/?probe=e90f168305) | Sep 17, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [221b15c3e0](https://linux-hardware.org/?probe=221b15c3e0) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [e552983263](https://linux-hardware.org/?probe=e552983263) | Sep 17, 2022 |
| Rockchip      | RK3288 Asus Tinker Board... | Soc         | [33cd540c8b](https://linux-hardware.org/?probe=33cd540c8b) | Sep 17, 2022 |
| Dell          | 0T2HR0 A02                  | Desktop     | [46dd4dfa8f](https://linux-hardware.org/?probe=46dd4dfa8f) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8c355ea88e](https://linux-hardware.org/?probe=8c355ea88e) | Sep 17, 2022 |
| HP            | Notebook                    | Notebook    | [9fcfcab16e](https://linux-hardware.org/?probe=9fcfcab16e) | Sep 17, 2022 |
| AZW           | Gemini T34-M                | Desktop     | [baafe96fc5](https://linux-hardware.org/?probe=baafe96fc5) | Sep 17, 2022 |
| Dell          | 0UW816 A00                  | Server      | [bd29b42f73](https://linux-hardware.org/?probe=bd29b42f73) | Sep 17, 2022 |
| Dell          | 0UW816 A00                  | Server      | [9959a5f63d](https://linux-hardware.org/?probe=9959a5f63d) | Sep 17, 2022 |
| HP            | Unknown                     | Notebook    | [e87c925eb0](https://linux-hardware.org/?probe=e87c925eb0) | Sep 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [189e23ff6a](https://linux-hardware.org/?probe=189e23ff6a) | Sep 16, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [3ace24ebfc](https://linux-hardware.org/?probe=3ace24ebfc) | Sep 16, 2022 |
| ASUSTek       | LITHIUM                     | Desktop     | [3aab1aa49f](https://linux-hardware.org/?probe=3aab1aa49f) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| ASUSTek       | KCMA-D8                     | Desktop     | [dc8ecec94f](https://linux-hardware.org/?probe=dc8ecec94f) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [7e865e8b3f](https://linux-hardware.org/?probe=7e865e8b3f) | Sep 16, 2022 |
| Gigabyte      | B150M-D3P-WG-CF             | Desktop     | [e37ff8fec3](https://linux-hardware.org/?probe=e37ff8fec3) | Sep 16, 2022 |
| Aquarius      | NS585                       | Notebook    | [84054aaa40](https://linux-hardware.org/?probe=84054aaa40) | Sep 16, 2022 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [b030fff6bb](https://linux-hardware.org/?probe=b030fff6bb) | Sep 16, 2022 |
| Aquarius      | NS585                       | Notebook    | [c4ad74720a](https://linux-hardware.org/?probe=c4ad74720a) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Aquarius      | NS585                       | Notebook    | [400485718e](https://linux-hardware.org/?probe=400485718e) | Sep 16, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [59c06bcd6f](https://linux-hardware.org/?probe=59c06bcd6f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [382325db11](https://linux-hardware.org/?probe=382325db11) | Sep 16, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [205e3937a8](https://linux-hardware.org/?probe=205e3937a8) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [a1f16914f7](https://linux-hardware.org/?probe=a1f16914f7) | Sep 16, 2022 |
| Aquarius      | NS585                       | Notebook    | [249e3f9a7c](https://linux-hardware.org/?probe=249e3f9a7c) | Sep 16, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c63f6d45b4](https://linux-hardware.org/?probe=c63f6d45b4) | Sep 16, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [283a38bb80](https://linux-hardware.org/?probe=283a38bb80) | Sep 16, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [00ca986a4c](https://linux-hardware.org/?probe=00ca986a4c) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [14cbf91f0c](https://linux-hardware.org/?probe=14cbf91f0c) | Sep 15, 2022 |
| Google        | Stout                       | Notebook    | [82b966b9ad](https://linux-hardware.org/?probe=82b966b9ad) | Sep 15, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3cb0c31aff](https://linux-hardware.org/?probe=3cb0c31aff) | Sep 15, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b99fc6c4d7](https://linux-hardware.org/?probe=b99fc6c4d7) | Sep 15, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [23194305f6](https://linux-hardware.org/?probe=23194305f6) | Sep 15, 2022 |
| Aquarius      | NS585                       | Notebook    | [e86929e9a3](https://linux-hardware.org/?probe=e86929e9a3) | Sep 15, 2022 |
| Aquarius      | NS585                       | Notebook    | [a1568949cd](https://linux-hardware.org/?probe=a1568949cd) | Sep 15, 2022 |
| Aquarius      | NS585                       | Notebook    | [feedc8a0ba](https://linux-hardware.org/?probe=feedc8a0ba) | Sep 15, 2022 |
| Aquarius      | NS585                       | Notebook    | [eb2906fdc5](https://linux-hardware.org/?probe=eb2906fdc5) | Sep 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [9f2a08c261](https://linux-hardware.org/?probe=9f2a08c261) | Sep 15, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [007e9d4205](https://linux-hardware.org/?probe=007e9d4205) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [3bf32bc004](https://linux-hardware.org/?probe=3bf32bc004) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [aa5d8a2fc6](https://linux-hardware.org/?probe=aa5d8a2fc6) | Sep 15, 2022 |
| Positivo      | Mobile                      | Notebook    | [f0f7335929](https://linux-hardware.org/?probe=f0f7335929) | Sep 15, 2022 |
| INFINITY      | Unknown                     | Notebook    | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| HP            | 876C SMVB                   | Desktop     | [adc81b2fd5](https://linux-hardware.org/?probe=adc81b2fd5) | Sep 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [5bdc2b7041](https://linux-hardware.org/?probe=5bdc2b7041) | Sep 14, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [af4b9d7add](https://linux-hardware.org/?probe=af4b9d7add) | Sep 14, 2022 |
| Google        | Terra                       | Notebook    | [9dae30736d](https://linux-hardware.org/?probe=9dae30736d) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [01d92ffc28](https://linux-hardware.org/?probe=01d92ffc28) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [c04d19fe27](https://linux-hardware.org/?probe=c04d19fe27) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [ad0ac85a1c](https://linux-hardware.org/?probe=ad0ac85a1c) | Sep 14, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 961       | 17.98%  |
| 5.10.0-7-amd64         | 682       | 12.76%  |
| 5.10.0-10-amd64        | 570       | 10.66%  |
| 5.10.0-16-amd64        | 366       | 6.85%   |
| 5.10.0-9-amd64         | 318       | 5.95%   |
| 5.10.0-13-amd64        | 259       | 4.85%   |
| 5.10.0-18-amd64        | 249       | 4.66%   |
| 5.10.0-11-amd64        | 191       | 3.57%   |
| 5.10.0-19-amd64        | 189       | 3.54%   |
| 5.10.0-14-amd64        | 136       | 2.54%   |
| 5.10.0-17-amd64        | 123       | 2.3%    |
| 5.10.0-2-amd64         | 105       | 1.96%   |
| 5.10.0-15-amd64        | 83        | 1.55%   |
| 5.10.0-12-amd64        | 73        | 1.37%   |
| 5.10.0-6-amd64         | 46        | 0.86%   |
| 5.15.0-2-amd64         | 38        | 0.71%   |
| 5.18.0-0.deb11.4-amd64 | 33        | 0.62%   |
| 5.10.0-13-686-pae      | 30        | 0.56%   |
| 5.16.0-0.bpo.4-amd64   | 29        | 0.54%   |
| 5.14.0-0.bpo.2-amd64   | 25        | 0.47%   |
| 5.18.0-0.bpo.1-amd64   | 24        | 0.45%   |
| 5.13.19-6-pve          | 18        | 0.34%   |
| 5.10.0-8-arm64         | 18        | 0.34%   |
| 5.19.0-0.deb11.2-amd64 | 17        | 0.32%   |
| 5.19.0-2-amd64         | 16        | 0.3%    |
| 5.15.32-v8+            | 16        | 0.3%    |
| 5.13.19-2-pve          | 16        | 0.3%    |
| 5.15.30-2-pve          | 15        | 0.28%   |
| 5.10.0-3-amd64         | 15        | 0.28%   |
| 5.15.53-1-pve          | 14        | 0.26%   |
| 5.10.0-8-686-pae       | 14        | 0.26%   |
| 5.15.35-1-pve          | 12        | 0.22%   |
| 5.10.92-v8+            | 12        | 0.22%   |
| 5.10.0-9-686-pae       | 12        | 0.22%   |
| 5.10.0-9-686           | 12        | 0.22%   |
| 5.15.61-v8+            | 11        | 0.21%   |
| 5.15.0-0.bpo.2-amd64   | 11        | 0.21%   |
| 5.18.0-2-amd64         | 10        | 0.19%   |
| 5.17.0-1-amd64         | 10        | 0.19%   |
| 5.10.0-4-amd64         | 10        | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 4171      | 84.71%  |
| 5.18.0   | 84        | 1.71%   |
| 5.15.0   | 75        | 1.52%   |
| 5.16.0   | 59        | 1.2%    |
| 5.13.19  | 52        | 1.06%   |
| 5.19.0   | 47        | 0.95%   |
| 5.14.0   | 41        | 0.83%   |
| 5.11.22  | 25        | 0.51%   |
| 5.17.0   | 24        | 0.49%   |
| 5.15.39  | 18        | 0.37%   |
| 5.15.35  | 17        | 0.35%   |
| 5.15.32  | 17        | 0.35%   |
| 5.15.30  | 16        | 0.32%   |
| 5.15.53  | 14        | 0.28%   |
| 5.10.92  | 13        | 0.26%   |
| 5.15.61  | 11        | 0.22%   |
| 6.0.0    | 10        | 0.2%    |
| 4.19.0   | 10        | 0.2%    |
| 5.13.0   | 7         | 0.14%   |
| 5.10.63  | 7         | 0.14%   |
| 5.15.76  | 6         | 0.12%   |
| 5.10.60  | 6         | 0.12%   |
| 5.10.109 | 5         | 0.1%    |
| 6.0.8    | 4         | 0.08%   |
| 5.16.5   | 4         | 0.08%   |
| 5.15.74  | 4         | 0.08%   |
| 5.15.64  | 4         | 0.08%   |
| 5.15.60  | 4         | 0.08%   |
| 5.12.0   | 4         | 0.08%   |
| 5.11.0   | 4         | 0.08%   |
| 5.10.103 | 4         | 0.08%   |
| 5.10     | 4         | 0.08%   |
| 5.9.0    | 3         | 0.06%   |
| 5.4.0    | 3         | 0.06%   |
| 5.17.5   | 3         | 0.06%   |
| 5.15.48  | 3         | 0.06%   |
| 5.15.19  | 3         | 0.06%   |
| 5.13.8   | 3         | 0.06%   |
| 5.13.13  | 3         | 0.06%   |
| 5.10.57  | 3         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 4236      | 86.27%  |
| 5.15    | 207       | 4.22%   |
| 5.18    | 93        | 1.89%   |
| 5.13    | 71        | 1.45%   |
| 5.16    | 65        | 1.32%   |
| 5.19    | 56        | 1.14%   |
| 5.14    | 48        | 0.98%   |
| 5.17    | 34        | 0.69%   |
| 5.11    | 34        | 0.69%   |
| 6.0     | 16        | 0.33%   |
| 4.19    | 12        | 0.24%   |
| 5.12    | 9         | 0.18%   |
| 5.4     | 7         | 0.14%   |
| 5       | 5         | 0.1%    |
| 5.9     | 3         | 0.06%   |
| 5.1     | 3         | 0.06%   |
| 4.9     | 2         | 0.04%   |
| 4.4     | 2         | 0.04%   |
| 3.18    | 2         | 0.04%   |
| 5.8     | 1         | 0.02%   |
| 5.5     | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 3.8     | 1         | 0.02%   |
| 3.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4542      | 94.15%  |
| i686    | 149       | 3.09%   |
| aarch64 | 108       | 2.24%   |
| armv7l  | 23        | 0.48%   |
| riscv64 | 2         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 2007      | 41.05%  |
| GNOME             | 1028      | 21.03%  |
| KDE5              | 522       | 10.68%  |
| XFCE              | 500       | 10.23%  |
| MATE              | 167       | 3.42%   |
| LXDE              | 132       | 2.7%    |
| X-Cinnamon        | 127       | 2.6%    |
| Cinnamon          | 103       | 2.11%   |
| lxqt              | 57        | 1.17%   |
| i3                | 57        | 1.17%   |
| KDE               | 41        | 0.84%   |
| GNOME Flashback   | 32        | 0.65%   |
| openbox           | 26        | 0.53%   |
| lightdm-xsession  | 24        | 0.49%   |
| Trinity           | 17        | 0.35%   |
| Budgie            | 9         | 0.18%   |
| GNOME Classic     | 8         | 0.16%   |
| sway              | 5         | 0.1%    |
| awesome           | 5         | 0.1%    |
| Enlightenment     | 3         | 0.06%   |
| DWM               | 3         | 0.06%   |
| Cutefish          | 3         | 0.06%   |
| ICEWM             | 2         | 0.04%   |
| xmonad            | 1         | 0.02%   |
| x-session-manager | 1         | 0.02%   |
| wmaker-common     | 1         | 0.02%   |
| UKUI              | 1         | 0.02%   |
| Phosh:GNOME       | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| e16-session       | 1         | 0.02%   |
| default           | 1         | 0.02%   |
| Deepin            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2081      | 42.63%  |
| Unknown | 1639      | 33.57%  |
| Wayland | 699       | 14.32%  |
| Tty     | 462       | 9.46%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2537      | 52.06%  |
| GDM     | 818       | 16.79%  |
| LightDM | 793       | 16.27%  |
| SDDM    | 467       | 9.58%   |
| TDM     | 154       | 3.16%   |
| GDM3    | 80        | 1.64%   |
| XDM     | 9         | 0.18%   |
| SLiM    | 9         | 0.18%   |
| NODM    | 3         | 0.06%   |
| LXDM    | 2         | 0.04%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1459      | 29.97%  |
| Unknown | 862       | 17.7%   |
| ru_RU   | 825       | 16.94%  |
| de_DE   | 245       | 5.03%   |
| en_GB   | 214       | 4.4%    |
| fr_FR   | 210       | 4.31%   |
| es_ES   | 140       | 2.88%   |
| it_IT   | 106       | 2.18%   |
| pt_BR   | 99        | 2.03%   |
| pl_PL   | 71        | 1.46%   |
| en_AU   | 58        | 1.19%   |
| en_CA   | 48        | 0.99%   |
| C       | 47        | 0.97%   |
| es_MX   | 33        | 0.68%   |
| zh_CN   | 27        | 0.55%   |
| hu_HU   | 26        | 0.53%   |
| es_VE   | 25        | 0.51%   |
| es_AR   | 24        | 0.49%   |
| ja_JP   | 21        | 0.43%   |
| en_IN   | 21        | 0.43%   |
| en_IE   | 17        | 0.35%   |
| de_AT   | 16        | 0.33%   |
| pt_PT   | 14        | 0.29%   |
| nl_NL   | 14        | 0.29%   |
| de_CH   | 14        | 0.29%   |
| sv_SE   | 12        | 0.25%   |
| es_CL   | 12        | 0.25%   |
| en_NZ   | 11        | 0.23%   |
| en_ZA   | 10        | 0.21%   |
| es_CO   | 9         | 0.18%   |
| cs_CZ   | 9         | 0.18%   |
| uk_UA   | 8         | 0.16%   |
| tr_TR   | 8         | 0.16%   |
| fi_FI   | 8         | 0.16%   |
| nl_BE   | 7         | 0.14%   |
| es_PE   | 7         | 0.14%   |
| en_SG   | 7         | 0.14%   |
| en_HK   | 7         | 0.14%   |
| ru_UA   | 6         | 0.12%   |
| nb_NO   | 6         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2766      | 56.76%  |
| BIOS | 2107      | 43.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2881      | 59.49%  |
| Overlay | 1669      | 34.46%  |
| Btrfs   | 151       | 3.12%   |
| Zfs     | 62        | 1.28%   |
| Xfs     | 48        | 0.99%   |
| Ext3    | 10        | 0.21%   |
| Tmpfs   | 8         | 0.17%   |
| Unknown | 7         | 0.14%   |
| Ext2    | 5         | 0.1%    |
| Rootfs  | 2         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2845      | 58.24%  |
| MBR     | 1364      | 27.92%  |
| Unknown | 676       | 13.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3901      | 80.28%  |
| Yes       | 958       | 19.72%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3312      | 68.05%  |
| Yes       | 1555      | 31.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 725       | 15.04%  |
| Lenovo                  | 707       | 14.66%  |
| Apple                   | 598       | 12.4%   |
| Hewlett-Packard         | 489       | 10.14%  |
| Dell                    | 436       | 9.04%   |
| Gigabyte Technology     | 313       | 6.49%   |
| MSI                     | 229       | 4.75%   |
| ASRock                  | 174       | 3.61%   |
| Acer                    | 154       | 3.19%   |
| Google                  | 123       | 2.55%   |
| Intel                   | 100       | 2.07%   |
| Raspberry Pi Foundation | 80        | 1.66%   |
| Unknown                 | 51        | 1.06%   |
| Aquarius                | 46        | 0.95%   |
| ECS                     | 44        | 0.91%   |
| Supermicro              | 36        | 0.75%   |
| Samsung Electronics     | 32        | 0.66%   |
| Toshiba                 | 31        | 0.64%   |
| Fujitsu                 | 30        | 0.62%   |
| Foxconn                 | 26        | 0.54%   |
| HUAWEI                  | 25        | 0.52%   |
| Sony                    | 16        | 0.33%   |
| ASRockRack              | 15        | 0.31%   |
| Packard Bell            | 12        | 0.25%   |
| Notebook                | 12        | 0.25%   |
| Pegatron                | 11        | 0.23%   |
| Biostar                 | 10        | 0.21%   |
| AZW                     | 9         | 0.19%   |
| Medion                  | 8         | 0.17%   |
| IBM                     | 8         | 0.17%   |
| sunxi                   | 7         | 0.15%   |
| Positivo                | 7         | 0.15%   |
| Microsoft               | 7         | 0.15%   |
| Hardkernel              | 7         | 0.15%   |
| Fujitsu Siemens         | 7         | 0.15%   |
| BESSTAR Tech            | 7         | 0.15%   |
| AMI                     | 7         | 0.15%   |
| ZOTAC                   | 6         | 0.12%   |
| Xunlong                 | 6         | 0.12%   |
| GPU Company             | 6         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 305       | 6.33%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 2.36%   |
| Apple MacBookAir7,1                       | 75        | 1.56%   |
| Google Enguarde                           | 74        | 1.53%   |
| Apple MacBookAir7,2                       | 74        | 1.53%   |
| ASUS All Series                           | 73        | 1.51%   |
| Unknown                                   | 61        | 1.27%   |
| ASUS S20 K29                              | 55        | 1.14%   |
| Apple MacBook2,1                          | 55        | 1.14%   |
| Aquarius NS585                            | 44        | 0.91%   |
| MSI MS-7996                               | 36        | 0.75%   |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.5%    |
| Google Terra                              | 23        | 0.48%   |
| Apple MacBook4,1                          | 21        | 0.44%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 20        | 0.41%   |
| ECS G31T-M9                               | 20        | 0.41%   |
| ASRock H470M-HVS                          | 20        | 0.41%   |
| MSI MS-7817                               | 18        | 0.37%   |
| Gigabyte H81M-S2V                         | 17        | 0.35%   |
| ASUS PRIME H510M-A                        | 17        | 0.35%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.33%   |
| Gigabyte H410M S2H                        | 16        | 0.33%   |
| ECS H61H2-M13                             | 16        | 0.33%   |
| Acer Aspire A315-23                       | 15        | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 14        | 0.29%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 14        | 0.29%   |
| ASUS P8H61-M LX3 R2.0                     | 14        | 0.29%   |
| ASUS 1005HA                               | 14        | 0.29%   |
| HP Notebook                               | 12        | 0.25%   |
| HP Pavilion g6                            | 10        | 0.21%   |
| Dell OptiPlex 7010                        | 10        | 0.21%   |
| Supermicro Super Server                   | 9         | 0.19%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 9         | 0.19%   |
| HP EliteBook 8460p                        | 9         | 0.19%   |
| Google Reks                               | 9         | 0.19%   |
| ASUS PRIME B450M-A                        | 9         | 0.19%   |
| HP Laptop 15-db0xxx                       | 8         | 0.17%   |
| Gigabyte B450M DS3H                       | 8         | 0.17%   |
| ASUS H110M-R                              | 8         | 0.17%   |
| Gigabyte B360M H                          | 7         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 471       | 9.77%   |
| Apple MacBook5     | 305       | 6.33%   |
| Apple MacBookAir7  | 149       | 3.09%   |
| Dell Latitude      | 112       | 2.32%   |
| Dell Inspiron      | 101       | 2.09%   |
| Acer Aspire        | 100       | 2.07%   |
| ASUS PRIME         | 93        | 1.93%   |
| Lenovo IdeaPad     | 81        | 1.68%   |
| RPi Raspberry      | 80        | 1.66%   |
| Google Enguarde    | 74        | 1.53%   |
| ASUS All           | 73        | 1.51%   |
| HP Pavilion        | 65        | 1.35%   |
| HP EliteBook       | 63        | 1.31%   |
| Dell OptiPlex      | 61        | 1.27%   |
| Unknown            | 61        | 1.27%   |
| HP Laptop          | 56        | 1.16%   |
| ASUS S20           | 55        | 1.14%   |
| Apple MacBook2     | 55        | 1.14%   |
| HP Compaq          | 49        | 1.02%   |
| Dell Precision     | 48        | 1%      |
| Dell XPS           | 46        | 0.95%   |
| HP ProBook         | 44        | 0.91%   |
| Aquarius NS585     | 44        | 0.91%   |
| ASUS ROG           | 39        | 0.81%   |
| Lenovo ThinkCentre | 38        | 0.79%   |
| MSI MS-7996        | 36        | 0.75%   |
| ASUS VivoBook      | 32        | 0.66%   |
| ASUS TUF           | 31        | 0.64%   |
| Dell Vostro        | 29        | 0.6%    |
| ASUS P8H61-M       | 28        | 0.58%   |
| Toshiba Satellite  | 25        | 0.52%   |
| Dell PowerEdge     | 25        | 0.52%   |
| Google Terra       | 23        | 0.48%   |
| HP ProLiant        | 21        | 0.44%   |
| Apple MacBook4     | 21        | 0.44%   |
| Gigabyte B450M     | 20        | 0.41%   |
| ECS G31T-M9        | 20        | 0.41%   |
| ASUS ZenBook       | 20        | 0.41%   |
| ASRock H470M-HVS   | 20        | 0.41%   |
| ASUS Pro           | 19        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 625       | 12.96%  |
| 2009    | 468       | 9.71%   |
| 2021    | 441       | 9.15%   |
| 2019    | 377       | 7.82%   |
| 2018    | 336       | 6.97%   |
| 2012    | 326       | 6.76%   |
| 2015    | 285       | 5.91%   |
| 2013    | 263       | 5.45%   |
| 2011    | 259       | 5.37%   |
| 2016    | 254       | 5.27%   |
| 2017    | 232       | 4.81%   |
| 2014    | 197       | 4.09%   |
| 2010    | 155       | 3.21%   |
| 2008    | 140       | 2.9%    |
| 2022    | 135       | 2.8%    |
| 2007    | 134       | 2.78%   |
| Unknown | 111       | 2.3%    |
| 2006    | 30        | 0.62%   |
| 2005    | 28        | 0.58%   |
| 2003    | 13        | 0.27%   |
| 2004    | 8         | 0.17%   |
| 2001    | 3         | 0.06%   |
| 2002    | 1         | 0.02%   |
| 2000    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2548      | 52.84%  |
| Desktop        | 1747      | 36.23%  |
| Convertible    | 168       | 3.48%   |
| System on chip | 119       | 2.47%   |
| Mini pc        | 99        | 2.05%   |
| Server         | 75        | 1.56%   |
| All in one     | 38        | 0.79%   |
| Tablet         | 23        | 0.48%   |
| Phone          | 3         | 0.06%   |
| Other          | 2         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4583      | 94.61%  |
| Enabled  | 261       | 5.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4692      | 97.28%  |
| Yes  | 131       | 2.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1137      | 23.42%  |
| 3.01-4.0        | 872       | 17.96%  |
| 16.01-24.0      | 861       | 17.73%  |
| 8.01-16.0       | 592       | 12.19%  |
| 1.01-2.0        | 554       | 11.41%  |
| 32.01-64.0      | 360       | 7.42%   |
| 64.01-256.0     | 189       | 3.89%   |
| 2.01-3.0        | 99        | 2.04%   |
| 0.51-1.0        | 89        | 1.83%   |
| 24.01-32.0      | 62        | 1.28%   |
| 0.01-0.5        | 24        | 0.49%   |
| More than 256.0 | 15        | 0.31%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1803      | 35.68%  |
| 0.51-1.0    | 993       | 19.65%  |
| 2.01-3.0    | 794       | 15.71%  |
| 4.01-8.0    | 540       | 10.69%  |
| 3.01-4.0    | 424       | 8.39%   |
| 0.01-0.5    | 215       | 4.25%   |
| 8.01-16.0   | 174       | 3.44%   |
| 16.01-24.0  | 50        | 0.99%   |
| 32.01-64.0  | 30        | 0.59%   |
| 24.01-32.0  | 20        | 0.4%    |
| 64.01-256.0 | 8         | 0.16%   |
| Unknown     | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3443      | 70.38%  |
| 2      | 816       | 16.68%  |
| 3      | 258       | 5.27%   |
| 4      | 157       | 3.21%   |
| 5      | 73        | 1.49%   |
| 0      | 38        | 0.78%   |
| 6      | 35        | 0.72%   |
| 7      | 24        | 0.49%   |
| 8      | 19        | 0.39%   |
| 10     | 8         | 0.16%   |
| 9      | 5         | 0.1%    |
| 14     | 4         | 0.08%   |
| 12     | 4         | 0.08%   |
| 28     | 2         | 0.04%   |
| 13     | 2         | 0.04%   |
| 11     | 2         | 0.04%   |
| 27     | 1         | 0.02%   |
| 16     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3257      | 67.35%  |
| Yes       | 1579      | 32.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4139      | 85.69%  |
| No        | 691       | 14.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3280      | 67.88%  |
| No        | 1552      | 32.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2760      | 56.98%  |
| No        | 2084      | 43.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1392      | 28.8%   |
| Russia       | 863       | 17.85%  |
| Germany      | 379       | 7.84%   |
| France       | 271       | 5.61%   |
| Spain        | 181       | 3.74%   |
| Italy        | 137       | 2.83%   |
| Brazil       | 129       | 2.67%   |
| UK           | 119       | 2.46%   |
| Poland       | 106       | 2.19%   |
| Canada       | 84        | 1.74%   |
| Australia    | 73        | 1.51%   |
| Switzerland  | 66        | 1.37%   |
| Netherlands  | 66        | 1.37%   |
| Mexico       | 56        | 1.16%   |
| China        | 51        | 1.06%   |
| Argentina    | 44        | 0.91%   |
| Ukraine      | 43        | 0.89%   |
| Sweden       | 39        | 0.81%   |
| Hungary      | 38        | 0.79%   |
| Austria      | 38        | 0.79%   |
| Portugal     | 32        | 0.66%   |
| Belgium      | 30        | 0.62%   |
| Venezuela    | 29        | 0.6%    |
| Japan        | 28        | 0.58%   |
| Czechia      | 28        | 0.58%   |
| India        | 27        | 0.56%   |
| Turkey       | 26        | 0.54%   |
| Norway       | 26        | 0.54%   |
| Finland      | 24        | 0.5%    |
| Bulgaria     | 22        | 0.46%   |
| Greece       | 18        | 0.37%   |
| Romania      | 17        | 0.35%   |
| New Zealand  | 16        | 0.33%   |
| Ireland      | 16        | 0.33%   |
| Croatia      | 15        | 0.31%   |
| Colombia     | 15        | 0.31%   |
| Chile        | 15        | 0.31%   |
| South Africa | 14        | 0.29%   |
| Kazakhstan   | 12        | 0.25%   |
| Indonesia    | 11        | 0.23%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangor            | 675       | 13.43%  |
| Voronezh          | 662       | 13.17%  |
| Dover-Foxcroft    | 305       | 6.07%   |
| Seville           | 46        | 0.92%   |
| Paris             | 43        | 0.86%   |
| St Petersburg     | 39        | 0.78%   |
| Moscow            | 37        | 0.74%   |
| Berlin            | 32        | 0.64%   |
| Vienna            | 28        | 0.56%   |
| Madrid            | 26        | 0.52%   |
| Zurich            | 25        | 0.5%    |
| Warsaw            | 24        | 0.48%   |
| Barcelona         | 24        | 0.48%   |
| Munich            | 23        | 0.46%   |
| Amsterdam         | 23        | 0.46%   |
| Milan             | 22        | 0.44%   |
| Sao Paulo         | 18        | 0.36%   |
| Perm              | 18        | 0.36%   |
| Sydney            | 17        | 0.34%   |
| Brisbane          | 17        | 0.34%   |
| London            | 16        | 0.32%   |
| Toronto           | 15        | 0.3%    |
| Frankfurt am Main | 15        | 0.3%    |
| Lyon              | 13        | 0.26%   |
| Blizniew          | 13        | 0.26%   |
| Melbourne         | 12        | 0.24%   |
| Falkenstein       | 12        | 0.24%   |
| Caracas           | 12        | 0.24%   |
| Budapest          | 12        | 0.24%   |
| Athens            | 12        | 0.24%   |
| Winterport        | 11        | 0.22%   |
| Stockholm         | 11        | 0.22%   |
| San Jose          | 11        | 0.22%   |
| Prague            | 11        | 0.22%   |
| Leipzig           | 11        | 0.22%   |
| Helsinki          | 11        | 0.22%   |
| Dublin            | 11        | 0.22%   |
| Buenos Aires      | 11        | 0.22%   |
| Zagreb            | 10        | 0.2%    |
| Valencia          | 10        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 960       | 1405   | 14.84%  |
| WDC                 | 865       | 1326   | 13.37%  |
| Seagate             | 815       | 1320   | 12.6%   |
| Toshiba             | 470       | 676    | 7.27%   |
| Kingston            | 393       | 495    | 6.08%   |
| Unknown             | 362       | 464    | 5.6%    |
| Crucial             | 312       | 377    | 4.82%   |
| Fujitsu             | 245       | 252    | 3.79%   |
| SanDisk             | 239       | 296    | 3.7%    |
| Hitachi             | 195       | 248    | 3.01%   |
| Apple               | 176       | 206    | 2.72%   |
| Intel               | 135       | 166    | 2.09%   |
| SK hynix            | 134       | 161    | 2.07%   |
| A-DATA Technology   | 130       | 219    | 2.01%   |
| HGST                | 89        | 135    | 1.38%   |
| Micron Technology   | 82        | 86     | 1.27%   |
| China               | 60        | 68     | 0.93%   |
| SPCC                | 42        | 47     | 0.65%   |
| Unknown             | 40        | 41     | 0.62%   |
| KIOXIA              | 39        | 43     | 0.6%    |
| PNY                 | 30        | 35     | 0.46%   |
| Transcend           | 29        | 35     | 0.45%   |
| Phison              | 29        | 38     | 0.45%   |
| Netac               | 28        | 85     | 0.43%   |
| SABRENT             | 26        | 27     | 0.4%    |
| Intenso             | 26        | 32     | 0.4%    |
| LITEON              | 23        | 26     | 0.36%   |
| Patriot             | 21        | 23     | 0.32%   |
| JMicron Technology  | 20        | 20     | 0.31%   |
| Silicon Motion      | 19        | 23     | 0.29%   |
| Maxtor              | 19        | 24     | 0.29%   |
| Hewlett-Packard     | 19        | 34     | 0.29%   |
| GOODRAM             | 18        | 28     | 0.28%   |
| Corsair             | 17        | 27     | 0.26%   |
| OCZ                 | 15        | 18     | 0.23%   |
| LITEONIT            | 14        | 18     | 0.22%   |
| Gigabyte Technology | 14        | 16     | 0.22%   |
| XPG                 | 10        | 12     | 0.15%   |
| Team                | 10        | 19     | 0.15%   |
| ASMT                | 10        | 12     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 201       | 2.86%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 121       | 1.72%   |
| Kingston SA400S37240G 240GB SSD    | 96        | 1.37%   |
| Apple SSD AP0128H 121GB            | 75        | 1.07%   |
| Crucial CT480BX500SSD1 480GB       | 71        | 1.01%   |
| Apple SSD SM0128G 121GB            | 71        | 1.01%   |
| Seagate ST500DM002-1BD142 500GB    | 68        | 0.97%   |
| Kingston SA400S37120G 120GB SSD    | 50        | 0.71%   |
| A-DATA SU800 512GB SSD             | 48        | 0.68%   |
| Toshiba MK1655GSXF 160GB           | 47        | 0.67%   |
| Toshiba DT01ACA050 500GB           | 47        | 0.67%   |
| Samsung SSD 860 EVO 250GB          | 46        | 0.65%   |
| Kingston SV300S37A120G 120GB SSD   | 46        | 0.65%   |
| Toshiba MK1653GSX 160GB            | 43        | 0.61%   |
| Samsung SSD 860 EVO 500GB          | 43        | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB     | 41        | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB     | 41        | 0.58%   |
| Unknown                            | 40        | 0.57%   |
| Unknown AGND3R  16GB               | 39        | 0.55%   |
| Kingston SA400S37480G 480GB SSD    | 39        | 0.55%   |
| Crucial CT1000MX500SSD1 1TB        | 38        | 0.54%   |
| Samsung SSD 860 EVO 1TB            | 36        | 0.51%   |
| Crucial CT500MX500SSD1 500GB       | 36        | 0.51%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 34        | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB       | 34        | 0.48%   |
| Samsung SSD 970 EVO Plus 500GB     | 31        | 0.44%   |
| Unknown HAG2e  16GB                | 30        | 0.43%   |
| Unknown MMC Card  32GB             | 29        | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 29        | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB           | 28        | 0.4%    |
| Toshiba HDWD110 1TB                | 28        | 0.4%    |
| Toshiba DT01ACA100 1TB             | 28        | 0.4%    |
| Samsung SSD 850 EVO 250GB          | 28        | 0.4%    |
| Hitachi HDS721050CLA362 500GB      | 28        | 0.4%    |
| Crucial CT240BX500SSD1 240GB       | 28        | 0.4%    |
| SABRENT Disk 500GB                 | 26        | 0.37%   |
| Unknown SDW16G  16GB               | 25        | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB     | 25        | 0.36%   |
| Samsung SSD 850 EVO 500GB          | 23        | 0.33%   |
| Toshiba MQ01ABF050 500GB           | 22        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 792       | 1282   | 31.63%  |
| WDC                 | 639       | 1017   | 25.52%  |
| Toshiba             | 397       | 593    | 15.85%  |
| Fujitsu             | 245       | 252    | 9.78%   |
| Hitachi             | 195       | 248    | 7.79%   |
| HGST                | 89        | 135    | 3.55%   |
| Samsung Electronics | 57        | 73     | 2.28%   |
| Unknown             | 18        | 27     | 0.72%   |
| Maxtor              | 18        | 20     | 0.72%   |
| ASMT                | 7         | 9      | 0.28%   |
| Apple               | 7         | 9      | 0.28%   |
| Hewlett-Packard     | 5         | 14     | 0.2%    |
| JMicron Technology  | 3         | 3      | 0.12%   |
| Intenso             | 3         | 3      | 0.12%   |
| ASMedia             | 3         | 3      | 0.12%   |
| USB3.0              | 2         | 2      | 0.08%   |
| IBM/Hitachi         | 2         | 2      | 0.08%   |
| IBM-ESXS            | 2         | 4      | 0.08%   |
| HPE                 | 2         | 6      | 0.08%   |
| Unknown (CF)        | 1         | 1      | 0.04%   |
| TrueNAS             | 1         | 1      | 0.04%   |
| Synology            | 1         | 1      | 0.04%   |
| SILICONMOTION       | 1         | 1      | 0.04%   |
| RSH-319             | 1         | 1      | 0.04%   |
| QNAP                | 1         | 1      | 0.04%   |
| pqi                 | 1         | 1      | 0.04%   |
| Pear 2TB            | 1         | 1      | 0.04%   |
| NAS                 | 1         | 5      | 0.04%   |
| Maxone              | 1         | 1      | 0.04%   |
| MaxDigital          | 1         | 4      | 0.04%   |
| MARSHAL             | 1         | 1      | 0.04%   |
| Hajaan              | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 1      | 0.04%   |
| AMP                 | 1         | 1      | 0.04%   |
| Advantech           | 1         | 1      | 0.04%   |
| 3ware               | 1         | 4      | 0.04%   |
| 128MB               | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 446       | 599    | 20.75%  |
| Kingston            | 332       | 423    | 15.45%  |
| Crucial             | 281       | 336    | 13.08%  |
| SanDisk             | 175       | 219    | 8.14%   |
| A-DATA Technology   | 102       | 174    | 4.75%   |
| WDC                 | 88        | 105    | 4.09%   |
| Apple               | 87        | 91     | 4.05%   |
| China               | 59        | 67     | 2.75%   |
| Intel               | 52        | 63     | 2.42%   |
| SPCC                | 36        | 38     | 1.68%   |
| Micron Technology   | 36        | 37     | 1.68%   |
| Toshiba             | 29        | 32     | 1.35%   |
| Netac               | 28        | 85     | 1.3%    |
| Transcend           | 27        | 33     | 1.26%   |
| SK hynix            | 27        | 35     | 1.26%   |
| PNY                 | 24        | 28     | 1.12%   |
| Intenso             | 21        | 25     | 0.98%   |
| Patriot             | 19        | 20     | 0.88%   |
| LITEON              | 19        | 22     | 0.88%   |
| OCZ                 | 15        | 18     | 0.7%    |
| LITEONIT            | 14        | 18     | 0.65%   |
| Goodram             | 14        | 20     | 0.65%   |
| Unknown             | 12        | 13     | 0.56%   |
| JMicron Technology  | 10        | 10     | 0.47%   |
| Team                | 9         | 17     | 0.42%   |
| Seagate             | 9         | 10     | 0.42%   |
| Apacer              | 9         | 9      | 0.42%   |
| Gigabyte Technology | 8         | 8      | 0.37%   |
| Unknown             | 7         | 10     | 0.33%   |
| Plextor             | 7         | 10     | 0.33%   |
| Hewlett-Packard     | 7         | 9      | 0.33%   |
| Hajaan              | 7         | 8      | 0.33%   |
| Corsair             | 7         | 10     | 0.33%   |
| Lexar               | 6         | 8      | 0.28%   |
| Mushkin             | 5         | 6      | 0.23%   |
| KingDian            | 5         | 5      | 0.23%   |
| Dogfish             | 5         | 5      | 0.23%   |
| Xinhaike            | 4         | 6      | 0.19%   |
| LDLC                | 4         | 4      | 0.19%   |
| KIOXIA-EXCERIA      | 4         | 7      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2199      | 3730   | 37%     |
| SSD     | 1917      | 2754   | 32.26%  |
| NVMe    | 1393      | 1905   | 23.44%  |
| MMC     | 368       | 454    | 6.19%   |
| Unknown | 66        | 100    | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3460      | 6198   | 63.64%  |
| NVMe | 1368      | 1868   | 25.16%  |
| MMC  | 368       | 454    | 6.77%   |
| SAS  | 241       | 423    | 4.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 2761      | 3830   | 64.25%  |
| 0.51-1.0    | 975       | 1448   | 22.69%  |
| 1.01-2.0    | 247       | 422    | 5.75%   |
| 3.01-4.0    | 118       | 295    | 2.75%   |
| 4.01-10.0   | 108       | 271    | 2.51%   |
| 2.01-3.0    | 56        | 89     | 1.3%    |
| 10.01-20.0  | 30        | 123    | 0.7%    |
| 20.01-50.0  | 1         | 2      | 0.02%   |
| 50.01-100.0 | 1         | 4      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1282      | 25.98%  |
| 101-250        | 1046      | 21.2%   |
| 251-500        | 816       | 16.53%  |
| 501-1000       | 507       | 10.27%  |
| 1-20           | 282       | 5.71%   |
| 51-100         | 262       | 5.31%   |
| 1001-2000      | 247       | 5.01%   |
| More than 3000 | 219       | 4.44%   |
| 21-50          | 175       | 3.55%   |
| 2001-3000      | 99        | 2.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1732      | 34.5%   |
| Unknown        | 1282      | 25.53%  |
| 101-250        | 441       | 8.78%   |
| 21-50          | 439       | 8.74%   |
| 51-100         | 380       | 7.57%   |
| 251-500        | 278       | 5.54%   |
| 501-1000       | 199       | 3.96%   |
| 1001-2000      | 106       | 2.11%   |
| More than 3000 | 96        | 1.91%   |
| 2001-3000      | 49        | 0.98%   |
| 0              | 19        | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB         | 20        | 23     | 3.01%   |
| Fujitsu MHZ2160BH FFS G1 160GB       | 20        | 20     | 3.01%   |
| Seagate ST500DM002-1BD142 500GB      | 16        | 16     | 2.41%   |
| Kingston SV300S37A120G 120GB SSD     | 14        | 14     | 2.11%   |
| Toshiba MK1653GSX 160GB              | 9         | 9      | 1.36%   |
| Toshiba MK1655GSXF 160GB             | 8         | 8      | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 8         | 9      | 1.2%    |
| Hitachi HDS721050CLA362 500GB        | 8         | 8      | 1.2%    |
| Seagate ST9500325AS 500GB            | 7         | 9      | 1.05%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 6         | 6      | 0.9%    |
| Hitachi HTS543216L9SA02 160GB        | 6         | 6      | 0.9%    |
| Seagate ST9500420AS 500GB            | 5         | 5      | 0.75%   |
| Seagate ST3500418AS 500GB            | 5         | 6      | 0.75%   |
| Seagate ST3250318AS 250GB            | 5         | 5      | 0.75%   |
| Seagate ST250DM000-1BD141 250GB      | 5         | 5      | 0.75%   |
| Seagate ST1000DM003-9YN162 1TB       | 5         | 6      | 0.75%   |
| Hitachi HTS542512K9SA00 120GB        | 5         | 6      | 0.75%   |
| Hitachi HDS721050DLE630 500GB        | 5         | 10     | 0.75%   |
| WDC WD20EARS-00MVWB0 2TB             | 4         | 4      | 0.6%    |
| WDC WD1600BUDT-63DPZY0 160GB         | 4         | 4      | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 4      | 0.6%    |
| Toshiba DT01ACA050 500GB             | 4         | 5      | 0.6%    |
| Seagate ST500LT012-1DG142 500GB      | 4         | 4      | 0.6%    |
| Seagate ST31500341AS 1TB             | 4         | 6      | 0.6%    |
| Seagate ST31000528AS 1TB             | 4         | 4      | 0.6%    |
| Hitachi HTS547575A9E384 752GB        | 4         | 4      | 0.6%    |
| Hitachi HTS545050B9A300 500GB        | 4         | 4      | 0.6%    |
| HGST HTS725050A7E630 500GB           | 4         | 4      | 0.6%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 3      | 0.45%   |
| WDC WD5000AAKX-001CA0 500GB          | 3         | 3      | 0.45%   |
| WDC WD3200AAJS-08L7A0 320GB          | 3         | 3      | 0.45%   |
| WDC WD2500AAJS-00YZCA0 250GB         | 3         | 3      | 0.45%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 3         | 3      | 0.45%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 3      | 0.45%   |
| Seagate ST500LM021-1KJ152 500GB      | 3         | 3      | 0.45%   |
| Seagate ST500LM000-SSHD-8GB          | 3         | 3      | 0.45%   |
| Seagate ST3320620AS 320GB            | 3         | 5      | 0.45%   |
| Seagate ST3320613AS 320GB            | 3         | 3      | 0.45%   |
| Seagate ST3120827AS 120GB            | 3         | 4      | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB       | 3         | 3      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 171       | 212    | 26.31%  |
| WDC                 | 153       | 187    | 23.54%  |
| Hitachi             | 74        | 89     | 11.38%  |
| Toshiba             | 41        | 43     | 6.31%   |
| Samsung Electronics | 37        | 40     | 5.69%   |
| Fujitsu             | 29        | 30     | 4.46%   |
| Kingston            | 28        | 33     | 4.31%   |
| Intel               | 22        | 28     | 3.38%   |
| HGST                | 15        | 16     | 2.31%   |
| SK hynix            | 14        | 17     | 2.15%   |
| A-DATA Technology   | 10        | 13     | 1.54%   |
| SanDisk             | 9         | 10     | 1.38%   |
| Crucial             | 9         | 12     | 1.38%   |
| Micron Technology   | 8         | 8      | 1.23%   |
| Maxtor              | 7         | 7      | 1.08%   |
| LITEONIT            | 4         | 5      | 0.62%   |
| LITEON              | 3         | 3      | 0.46%   |
| Hewlett-Packard     | 2         | 3      | 0.31%   |
| China               | 2         | 2      | 0.31%   |
| USB3.0              | 1         | 1      | 0.15%   |
| ShiJi               | 1         | 1      | 0.15%   |
| PNY                 | 1         | 1      | 0.15%   |
| Lenovo              | 1         | 1      | 0.15%   |
| KingDian            | 1         | 1      | 0.15%   |
| JMicron Technology  | 1         | 1      | 0.15%   |
| IBM/Hitachi         | 1         | 1      | 0.15%   |
| GOODRAM             | 1         | 1      | 0.15%   |
| DGM                 | 1         | 1      | 0.15%   |
| ASMedia             | 1         | 1      | 0.15%   |
| Apple               | 1         | 1      | 0.15%   |
| Unknown             | 1         | 1      | 0.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 171       | 212    | 33.6%   |
| WDC                 | 148       | 181    | 29.08%  |
| Hitachi             | 74        | 89     | 14.54%  |
| Toshiba             | 41        | 43     | 8.06%   |
| Fujitsu             | 29        | 30     | 5.7%    |
| Samsung Electronics | 17        | 17     | 3.34%   |
| HGST                | 15        | 16     | 2.95%   |
| Maxtor              | 7         | 7      | 1.38%   |
| Hewlett-Packard     | 2         | 3      | 0.39%   |
| USB3.0              | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| IBM/Hitachi         | 1         | 1      | 0.2%    |
| ASMedia             | 1         | 1      | 0.2%    |
| Apple               | 1         | 1      | 0.2%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 488       | 603    | 77.46%  |
| SSD  | 117       | 136    | 18.57%  |
| NVMe | 25        | 31     | 3.97%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 6.25%   |
| WDC WD4001FFSX-68JNUN0 4TB                      | 1         | 1      | 6.25%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 6.25%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 6.25%   |
| Seagate ST500DM005 HD502HJ 500GB                | 1         | 1      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 2      | 6.25%   |
| Seagate ST3500830AS 500GB                       | 1         | 1      | 6.25%   |
| Seagate ST3500630A 500GB                        | 1         | 1      | 6.25%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 6.25%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 6.25%   |
| Samsung Electronics HD253GJ 250GB               | 1         | 1      | 6.25%   |
| KingDian S400 120GB                             | 1         | 1      | 6.25%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 6.25%   |
| HGST HUH728080ALN600 8TB                        | 1         | 1      | 6.25%   |
| HGST HDN724040ALE640 4TB                        | 1         | 1      | 6.25%   |
| Hewlett-Packard SSD S700 500GB                  | 1         | 2      | 6.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 7      | 37.5%   |
| Samsung Electronics | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| HGST                | 2         | 2      | 12.5%   |
| KingDian            | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 2      | 6.25%   |
| Hewlett-Packard     | 1         | 2      | 6.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3496      | 6035   | 66.57%  |
| Detected | 1121      | 2117   | 21.34%  |
| Malfunc  | 617       | 770    | 11.75%  |
| Failed   | 16        | 19     | 0.3%    |
| Limited  | 2         | 2      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2809      | 49.93%  |
| AMD                              | 719       | 12.78%  |
| Samsung Electronics              | 594       | 10.56%  |
| Nvidia                           | 364       | 6.47%   |
| SanDisk                          | 213       | 3.79%   |
| SK hynix                         | 104       | 1.85%   |
| ASMedia Technology               | 82        | 1.46%   |
| Apple                            | 82        | 1.46%   |
| Phison Electronics               | 69        | 1.23%   |
| Kingston Technology Company      | 66        | 1.17%   |
| Marvell Technology Group         | 57        | 1.01%   |
| JMicron Technology               | 49        | 0.87%   |
| Toshiba America Info Systems     | 48        | 0.85%   |
| Micron Technology                | 47        | 0.84%   |
| Micron/Crucial Technology        | 41        | 0.73%   |
| KIOXIA                           | 41        | 0.73%   |
| Silicon Motion                   | 38        | 0.68%   |
| LSI Logic / Symbios Logic        | 37        | 0.66%   |
| ADATA Technology                 | 34        | 0.6%    |
| Broadcom / LSI                   | 26        | 0.46%   |
| VIA Technologies                 | 21        | 0.37%   |
| Solid State Storage Technology   | 11        | 0.2%    |
| Hewlett-Packard                  | 8         | 0.14%   |
| Union Memory (Shenzhen)          | 7         | 0.12%   |
| Realtek Semiconductor            | 7         | 0.12%   |
| Adaptec                          | 7         | 0.12%   |
| Seagate Technology               | 6         | 0.11%   |
| Silicon Image                    | 5         | 0.09%   |
| Shenzhen Longsys Electronics     | 4         | 0.07%   |
| Lite-On Technology               | 4         | 0.07%   |
| Lenovo                           | 4         | 0.07%   |
| Unknown                          | 4         | 0.07%   |
| Silicon Integrated Systems [SiS] | 3         | 0.05%   |
| 3ware                            | 3         | 0.05%   |
| ULi Electronics                  | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 500       | 7.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 340       | 5.25%   |
| Nvidia MCP79 AHCI Controller                                                            | 315       | 4.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 220       | 3.4%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 188       | 2.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 152       | 2.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 147       | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 122       | 1.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 120       | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 112       | 1.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 109       | 1.68%   |
| AMD 400 Series Chipset SATA Controller                                                  | 104       | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 101       | 1.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 99        | 1.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 91        | 1.41%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 87        | 1.34%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 85        | 1.31%   |
| Samsung NVMe SSD Controller 980                                                         | 83        | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 81        | 1.25%   |
| Samsung Electronics SATA controller                                                     | 80        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 80        | 1.24%   |
| Apple S1X NVMe Controller                                                               | 77        | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 68        | 1.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 66        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 64        | 0.99%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 63        | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                                  | 63        | 0.97%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 62        | 0.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 60        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 57        | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 56        | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 56        | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 55        | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 52        | 0.8%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 49        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 48        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 48        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 48        | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 48        | 0.74%   |
| Micron Non-Volatile memory controller                                                   | 44        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3354      | 57.91%  |
| NVMe | 1368      | 23.62%  |
| IDE  | 690       | 11.91%  |
| RAID | 316       | 5.46%   |
| SAS  | 51        | 0.88%   |
| SCSI | 13        | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 3809      | 78.98%  |
| AMD                   | 875       | 18.14%  |
| ARM                   | 126       | 2.61%   |
| CentaurHauls          | 6         | 0.12%   |
| Phytium               | 3         | 0.06%   |
| Unknown               | 2         | 0.04%   |
| Marvell Semiconductor | 1         | 0.02%   |
| HISILICON             | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 307       | 6.36%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 168       | 3.48%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 144       | 2.98%   |
| ARM Processor                                 | 100       | 2.07%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 86        | 1.78%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 59        | 1.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 59        | 1.22%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 58        | 1.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 48        | 0.99%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 45        | 0.93%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 40        | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 38        | 0.79%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 35        | 0.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 35        | 0.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 31        | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 29        | 0.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 29        | 0.6%    |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 28        | 0.58%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 28        | 0.58%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 27        | 0.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 25        | 0.52%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 25        | 0.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 25        | 0.52%   |
| AMD Ryzen 5 3600 6-Core Processor             | 25        | 0.52%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.5%    |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 23        | 0.48%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 23        | 0.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 23        | 0.48%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 22        | 0.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 22        | 0.46%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 22        | 0.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 0.43%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 21        | 0.43%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 20        | 0.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 20        | 0.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 20        | 0.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 20        | 0.41%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 20        | 0.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 19        | 0.39%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 19        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 968       | 20.07%  |
| Intel Core i7           | 563       | 11.67%  |
| Other                   | 497       | 10.3%   |
| Intel Core 2 Duo        | 484       | 10.03%  |
| Intel Core i3           | 357       | 7.4%    |
| Intel Celeron           | 336       | 6.97%   |
| AMD Ryzen 5             | 226       | 4.68%   |
| Intel Pentium           | 197       | 4.08%   |
| Intel Xeon              | 162       | 3.36%   |
| AMD Ryzen 7             | 136       | 2.82%   |
| Intel Atom              | 92        | 1.91%   |
| Intel Core 2            | 70        | 1.45%   |
| AMD Ryzen 9             | 60        | 1.24%   |
| Intel Pentium Dual-Core | 58        | 1.2%    |
| AMD FX                  | 51        | 1.06%   |
| AMD Ryzen 3             | 44        | 0.91%   |
| Intel Core 2 Quad       | 29        | 0.6%    |
| AMD Ryzen 7 PRO         | 29        | 0.6%    |
| AMD A6                  | 25        | 0.52%   |
| Intel Core i9           | 22        | 0.46%   |
| AMD A10                 | 22        | 0.46%   |
| AMD Ryzen Threadripper  | 20        | 0.41%   |
| AMD Athlon              | 20        | 0.41%   |
| Intel Pentium M         | 19        | 0.39%   |
| Intel Pentium Gold      | 18        | 0.37%   |
| Intel Pentium 4         | 18        | 0.37%   |
| Intel Genuine           | 17        | 0.35%   |
| AMD Ryzen 5 PRO         | 17        | 0.35%   |
| Intel Pentium Dual      | 15        | 0.31%   |
| AMD A4                  | 15        | 0.31%   |
| AMD Athlon 64 X2        | 14        | 0.29%   |
| AMD Athlon II X2        | 13        | 0.27%   |
| AMD A8                  | 13        | 0.27%   |
| AMD Phenom II X4        | 12        | 0.25%   |
| ARM Allwinner           | 11        | 0.23%   |
| AMD E1                  | 10        | 0.21%   |
| Intel Pentium Silver    | 9         | 0.19%   |
| Intel Celeron M         | 9         | 0.19%   |
| AMD Opteron             | 9         | 0.19%   |
| AMD Phenom II X6        | 8         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2174      | 45.03%  |
| 4       | 1595      | 33.04%  |
| 6       | 402       | 8.33%   |
| 8       | 298       | 6.17%   |
| 1       | 173       | 3.58%   |
| 16      | 52        | 1.08%   |
| 12      | 49        | 1.01%   |
| 3       | 22        | 0.46%   |
| 10      | 16        | 0.33%   |
| 32      | 11        | 0.23%   |
| Unknown | 8         | 0.17%   |
| 24      | 7         | 0.14%   |
| 14      | 6         | 0.12%   |
| 20      | 4         | 0.08%   |
| 28      | 3         | 0.06%   |
| 48      | 2         | 0.04%   |
| 44      | 2         | 0.04%   |
| 80      | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 56      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4746      | 98.36%  |
| 2       | 70        | 1.45%   |
| Unknown | 8         | 0.17%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2743      | 56.83%  |
| 1       | 2075      | 42.99%  |
| Unknown | 8         | 0.17%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4680      | 96.99%  |
| 32-bit         | 94        | 1.95%   |
| Unknown        | 37        | 0.77%   |
| 64-bit         | 14        | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 867       | 17.74%  |
| 0x1067a    | 459       | 9.39%   |
| 0x806c1    | 235       | 4.81%   |
| 0x306c3    | 215       | 4.4%    |
| 0x306a9    | 206       | 4.21%   |
| 0x206a7    | 204       | 4.17%   |
| 0x306d4    | 198       | 4.05%   |
| 0x906ea    | 127       | 2.6%    |
| 0x506e3    | 109       | 2.23%   |
| 0x30678    | 105       | 2.15%   |
| 0x806ec    | 94        | 1.92%   |
| 0x806e9    | 86        | 1.76%   |
| 0x08108109 | 75        | 1.53%   |
| 0x806ea    | 70        | 1.43%   |
| 0x6f6      | 67        | 1.37%   |
| 0xa0653    | 65        | 1.33%   |
| 0x406e3    | 60        | 1.23%   |
| 0x406c4    | 60        | 1.23%   |
| 0x906eb    | 59        | 1.21%   |
| 0x906e9    | 58        | 1.19%   |
| 0x40651    | 56        | 1.15%   |
| 0x08701021 | 51        | 1.04%   |
| 0x08600106 | 47        | 0.96%   |
| 0x10676    | 45        | 0.92%   |
| 0xa0652    | 44        | 0.9%    |
| 0x20655    | 43        | 0.88%   |
| 0x0a50000c | 41        | 0.84%   |
| 0xa0655    | 39        | 0.8%    |
| 0x706a8    | 37        | 0.76%   |
| 0x6fd      | 36        | 0.74%   |
| 0x0600611a | 36        | 0.74%   |
| 0x106c2    | 31        | 0.63%   |
| 0x706e5    | 30        | 0.61%   |
| 0x506c9    | 30        | 0.61%   |
| 0x08608103 | 30        | 0.61%   |
| 0x0a201016 | 29        | 0.59%   |
| 0xa0671    | 27        | 0.55%   |
| 0x0800820d | 27        | 0.55%   |
| 0x206d7    | 24        | 0.49%   |
| 0x6fb      | 21        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 644       | 13.34%  |
| Penryn           | 535       | 11.08%  |
| Haswell          | 361       | 7.48%   |
| SandyBridge      | 275       | 5.7%    |
| IvyBridge        | 273       | 5.65%   |
| TigerLake        | 271       | 5.61%   |
| Unknown          | 229       | 4.74%   |
| Broadwell        | 227       | 4.7%    |
| Skylake          | 212       | 4.39%   |
| Silvermont       | 206       | 4.27%   |
| Zen 2            | 172       | 3.56%   |
| CometLake        | 172       | 3.56%   |
| Zen+             | 161       | 3.33%   |
| Core             | 155       | 3.21%   |
| Zen 3            | 122       | 2.53%   |
| Westmere         | 96        | 1.99%   |
| Excavator        | 75        | 1.55%   |
| Zen              | 63        | 1.3%    |
| K10              | 60        | 1.24%   |
| Goldmont plus    | 59        | 1.22%   |
| Bonnell          | 57        | 1.18%   |
| Icelake          | 54        | 1.12%   |
| Piledriver       | 51        | 1.06%   |
| P6               | 41        | 0.85%   |
| Goldmont         | 36        | 0.75%   |
| Nehalem          | 33        | 0.68%   |
| NetBurst         | 29        | 0.6%    |
| K8 Hammer        | 27        | 0.56%   |
| Bobcat           | 22        | 0.46%   |
| Tremont          | 17        | 0.35%   |
| Steamroller      | 17        | 0.35%   |
| Puma             | 17        | 0.35%   |
| Bulldozer        | 16        | 0.33%   |
| Jaguar           | 15        | 0.31%   |
| Alderlake Hybrid | 13        | 0.27%   |
| K10 Llano        | 10        | 0.21%   |
| K6               | 3         | 0.06%   |
| K8 & K10 hybrid  | 2         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2836      | 53.93%  |
| Nvidia                           | 1379      | 26.22%  |
| AMD                              | 928       | 17.65%  |
| Matrox Electronics Systems       | 53        | 1.01%   |
| ASPEED Technology                | 50        | 0.95%   |
| VIA Technologies                 | 6         | 0.11%   |
| Silicon Integrated Systems [SiS] | 3         | 0.06%   |
| Zhaoxin                          | 2         | 0.04%   |
| S3 Graphics                      | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 305       | 5.58%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 255       | 4.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 182       | 3.33%   |
| Intel HD Graphics 6000                                                                   | 150       | 2.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 141       | 2.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 137       | 2.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 125       | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 120       | 2.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 116       | 2.12%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 93        | 1.7%    |
| Intel UHD Graphics 620                                                                   | 88        | 1.61%   |
| AMD Renoir                                                                               | 88        | 1.61%   |
| Intel HD Graphics 620                                                                    | 78        | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 76        | 1.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 72        | 1.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 70        | 1.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 70        | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 70        | 1.28%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 67        | 1.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 65        | 1.19%   |
| Intel HD Graphics 530                                                                    | 58        | 1.06%   |
| Intel HD Graphics 5500                                                                   | 56        | 1.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 56        | 1.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 55        | 1.01%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 53        | 0.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 51        | 0.93%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 50        | 0.91%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 50        | 0.91%   |
| Intel HD Graphics 630                                                                    | 49        | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 49        | 0.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 49        | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 48        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 48        | 0.88%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 48        | 0.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 46        | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 45        | 0.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 41        | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 38        | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 37        | 0.68%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 37        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 2338      | 48.3%   |
| 1 x Nvidia                        | 933       | 19.27%  |
| 1 x AMD                           | 758       | 15.66%  |
| Intel + Nvidia                    | 379       | 7.83%   |
| Other                             | 147       | 3.04%   |
| Intel + AMD                       | 65        | 1.34%   |
| AMD + Nvidia                      | 52        | 1.07%   |
| 1 x Matrox                        | 50        | 1.03%   |
| 2 x AMD                           | 46        | 0.95%   |
| 1 x ASPEED                        | 39        | 0.81%   |
| 1 x VIA                           | 6         | 0.12%   |
| AMD + ASPEED                      | 5         | 0.1%    |
| 2 x Nvidia                        | 4         | 0.08%   |
| Nvidia + ASPEED                   | 4         | 0.08%   |
| 1 x SiS                           | 3         | 0.06%   |
| Intel + 2 x Nvidia                | 3         | 0.06%   |
| 1 x Zhaoxin                       | 2         | 0.04%   |
| Nvidia + Matrox                   | 2         | 0.04%   |
| 3 x AMD                           | 1         | 0.02%   |
| 2 x Nvidia + 1 x ASPEED           | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.02%   |
| 1 x S3 Graphics                   | 1         | 0.02%   |
| AMD + Matrox                      | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3424      | 70.6%   |
| Unknown     | 1037      | 21.38%  |
| Proprietary | 389       | 8.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 3485      | 71.56%  |
| 0.01-0.5       | 621       | 12.75%  |
| 1.01-2.0       | 252       | 5.17%   |
| 3.01-4.0       | 163       | 3.35%   |
| 0.51-1.0       | 162       | 3.33%   |
| 7.01-8.0       | 89        | 1.83%   |
| 5.01-6.0       | 54        | 1.11%   |
| 2.01-3.0       | 18        | 0.37%   |
| 8.01-16.0      | 16        | 0.33%   |
| 16.01-24.0     | 6         | 0.12%   |
| 4.01-5.0       | 2         | 0.04%   |
| More than 64.0 | 1         | 0.02%   |
| 24.01-32.0     | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 582       | 13.63%  |
| AU Optronics            | 543       | 12.72%  |
| Samsung Electronics     | 390       | 9.14%   |
| BOE                     | 366       | 8.57%   |
| LG Display              | 296       | 6.93%   |
| Chimei Innolux          | 292       | 6.84%   |
| Dell                    | 208       | 4.87%   |
| Goldstar                | 187       | 4.38%   |
| Hewlett-Packard         | 114       | 2.67%   |
| BenQ                    | 103       | 2.41%   |
| Acer                    | 97        | 2.27%   |
| AOC                     | 88        | 2.06%   |
| Lenovo                  | 86        | 2.01%   |
| Ancor Communications    | 82        | 1.92%   |
| Philips                 | 74        | 1.73%   |
| Sharp                   | 60        | 1.41%   |
| Iiyama                  | 48        | 1.12%   |
| ViewSonic               | 46        | 1.08%   |
| Unknown                 | 44        | 1.03%   |
| Chi Mei Optoelectronics | 44        | 1.03%   |
| InfoVision              | 36        | 0.84%   |
| Eizo                    | 35        | 0.82%   |
| PANDA                   | 28        | 0.66%   |
| ASUSTek Computer        | 27        | 0.63%   |
| HannStar                | 25        | 0.59%   |
| NEC Computers           | 22        | 0.52%   |
| Sony                    | 19        | 0.45%   |
| LG Philips              | 16        | 0.37%   |
| LG Electronics          | 15        | 0.35%   |
| CSO                     | 13        | 0.3%    |
| Panasonic               | 11        | 0.26%   |
| Toshiba                 | 10        | 0.23%   |
| Vestel Elektronik       | 9         | 0.21%   |
| MSI                     | 8         | 0.19%   |
| Medion                  | 7         | 0.16%   |
| Unknown                 | 7         | 0.16%   |
| Vizio                   | 6         | 0.14%   |
| RTK                     | 6         | 0.14%   |
| CPT                     | 6         | 0.14%   |
| Pixio                   | 5         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                      | 199       | 4.56%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 150       | 3.44%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch            | 112       | 2.57%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 52        | 1.19%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 41        | 0.94%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 40        | 0.92%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 39        | 0.89%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                      | 35        | 0.8%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 34        | 0.78%   |
| BOE LCD Monitor BOE06B3 1920x1080 310x170mm 13.9-inch                     | 25        | 0.57%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 25        | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 22        | 0.5%    |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                      | 21        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 20        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 19        | 0.44%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                  | 18        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 16        | 0.37%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                    | 15        | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 15        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 13        | 0.3%    |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                      | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 12        | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 11        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 11        | 0.25%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 11        | 0.25%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 11        | 0.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 10        | 0.23%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                         | 10        | 0.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 10        | 0.23%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 9         | 0.21%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch               | 9         | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 9         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 9         | 0.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 9         | 0.21%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 9         | 0.21%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 9         | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch         | 8         | 0.18%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 8         | 0.18%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch               | 8         | 0.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 8         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1625      | 39.58%  |
| 1366x768 (WXGA)    | 726       | 17.68%  |
| 1280x800 (WXGA)    | 450       | 10.96%  |
| 3840x2160 (4K)     | 200       | 4.87%   |
| 2560x1440 (QHD)    | 155       | 3.77%   |
| 1280x1024 (SXGA)   | 141       | 3.43%   |
| 1440x900 (WXGA+)   | 137       | 3.34%   |
| 1600x900 (HD+)     | 125       | 3.04%   |
| 1920x1200 (WUXGA)  | 88        | 2.14%   |
| 1680x1050 (WSXGA+) | 74        | 1.8%    |
| Unknown            | 44        | 1.07%   |
| 1024x600           | 40        | 0.97%   |
| 2288x1287          | 35        | 0.85%   |
| 1024x768 (XGA)     | 34        | 0.83%   |
| 1360x768           | 26        | 0.63%   |
| 2560x1080          | 25        | 0.61%   |
| 3440x1440          | 23        | 0.56%   |
| 2560x1600          | 20        | 0.49%   |
| 3840x1080          | 19        | 0.46%   |
| 1600x1200          | 18        | 0.44%   |
| 1920x540           | 11        | 0.27%   |
| 3840x2400          | 9         | 0.22%   |
| 2880x1800          | 8         | 0.19%   |
| 2160x1440          | 7         | 0.17%   |
| 4480x1440          | 5         | 0.12%   |
| 1920x1280          | 5         | 0.12%   |
| 1400x1050          | 5         | 0.12%   |
| 2736x1824          | 4         | 0.1%    |
| 3200x1080          | 3         | 0.07%   |
| 5760x1080          | 2         | 0.05%   |
| 5360x1440          | 2         | 0.05%   |
| 3840x1600          | 2         | 0.05%   |
| 3840x1100          | 2         | 0.05%   |
| 3360x1050          | 2         | 0.05%   |
| 3200x1800 (QHD+)   | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |
| 2048x1152          | 2         | 0.05%   |
| 1800x1200          | 2         | 0.05%   |
| 1280x720 (HD)      | 2         | 0.05%   |
| 7680x4320          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 920       | 21.75%  |
| 15      | 781       | 18.47%  |
| 14      | 301       | 7.12%   |
| 24      | 285       | 6.74%   |
| 27      | 242       | 5.72%   |
| 23      | 238       | 5.63%   |
| 11      | 229       | 5.41%   |
| 17      | 191       | 4.52%   |
| 21      | 180       | 4.26%   |
| Unknown | 124       | 2.93%   |
| 19      | 102       | 2.41%   |
| 12      | 94        | 2.22%   |
| 18      | 78        | 1.84%   |
| 31      | 71        | 1.68%   |
| 22      | 57        | 1.35%   |
| 10      | 43        | 1.02%   |
| 20      | 41        | 0.97%   |
| 142     | 34        | 0.8%    |
| 34      | 33        | 0.78%   |
| 84      | 22        | 0.52%   |
| 32      | 17        | 0.4%    |
| 72      | 16        | 0.38%   |
| 25      | 16        | 0.38%   |
| 16      | 14        | 0.33%   |
| 29      | 11        | 0.26%   |
| 54      | 9         | 0.21%   |
| 28      | 9         | 0.21%   |
| 52      | 7         | 0.17%   |
| 40      | 6         | 0.14%   |
| 33      | 6         | 0.14%   |
| 26      | 6         | 0.14%   |
| 48      | 5         | 0.12%   |
| 46      | 5         | 0.12%   |
| 65      | 4         | 0.09%   |
| 55      | 4         | 0.09%   |
| 47      | 3         | 0.07%   |
| 43      | 3         | 0.07%   |
| 42      | 3         | 0.07%   |
| 39      | 3         | 0.07%   |
| 35      | 3         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1333      | 32%     |
| 201-300        | 1093      | 26.24%  |
| 501-600        | 706       | 16.95%  |
| 401-500        | 390       | 9.36%   |
| 351-400        | 206       | 4.94%   |
| Unknown        | 124       | 2.98%   |
| 601-700        | 122       | 2.93%   |
| 701-800        | 53        | 1.27%   |
| 1001-1500      | 41        | 0.98%   |
| 1501-2000      | 40        | 0.96%   |
| More than 2000 | 34        | 0.82%   |
| 801-900        | 15        | 0.36%   |
| 901-1000       | 6         | 0.14%   |
| 101-200        | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2650      | 68.26%  |
| 16/10   | 803       | 20.69%  |
| 5/4     | 132       | 3.4%    |
| Unknown | 97        | 2.5%    |
| 4/3     | 67        | 1.73%   |
| 21/9    | 43        | 1.11%   |
| 1.00    | 36        | 0.93%   |
| 3/2     | 33        | 0.85%   |
| 6/5     | 7         | 0.18%   |
| 2.65    | 5         | 0.13%   |
| 32/9    | 4         | 0.1%    |
| 3.40    | 2         | 0.05%   |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 914       | 21.82%  |
| 101-110        | 776       | 18.52%  |
| 201-250        | 597       | 14.25%  |
| 71-80          | 307       | 7.33%   |
| 301-350        | 246       | 5.87%   |
| 51-60          | 231       | 5.51%   |
| 151-200        | 203       | 4.85%   |
| 351-500        | 140       | 3.34%   |
| 141-150        | 134       | 3.2%    |
| Unknown        | 124       | 2.96%   |
| 251-300        | 110       | 2.63%   |
| 121-130        | 102       | 2.43%   |
| More than 1000 | 101       | 2.41%   |
| 61-70          | 88        | 2.1%    |
| 41-50          | 43        | 1.03%   |
| 501-1000       | 30        | 0.72%   |
| 131-140        | 20        | 0.48%   |
| 111-120        | 11        | 0.26%   |
| 91-100         | 9         | 0.21%   |
| 1-40           | 3         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1217      | 29.68%  |
| 101-120       | 1169      | 28.51%  |
| 51-100        | 1134      | 27.66%  |
| 161-240       | 308       | 7.51%   |
| Unknown       | 124       | 3.02%   |
| 1-50          | 92        | 2.24%   |
| More than 240 | 56        | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3213      | 65.68%  |
| 0     | 1074      | 21.95%  |
| 2     | 541       | 11.06%  |
| 3     | 61        | 1.25%   |
| 4     | 2         | 0.04%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2235      | 32.3%   |
| Intel                             | 2093      | 30.25%  |
| Qualcomm Atheros                  | 635       | 9.18%   |
| Broadcom                          | 610       | 8.82%   |
| Nvidia                            | 357       | 5.16%   |
| Broadcom Limited                  | 221       | 3.19%   |
| Marvell Technology Group          | 121       | 1.75%   |
| Ralink Technology                 | 54        | 0.78%   |
| MediaTek                          | 49        | 0.71%   |
| TP-Link                           | 47        | 0.68%   |
| Ralink                            | 43        | 0.62%   |
| ASIX Electronics                  | 38        | 0.55%   |
| Samsung Electronics               | 27        | 0.39%   |
| Microchip Technology              | 19        | 0.27%   |
| Dell                              | 19        | 0.27%   |
| Qualcomm Atheros Communications   | 18        | 0.26%   |
| Sierra Wireless                   | 16        | 0.23%   |
| Qualcomm                          | 16        | 0.23%   |
| Mellanox Technologies             | 14        | 0.2%    |
| Huawei Technologies               | 14        | 0.2%    |
| DisplayLink                       | 13        | 0.19%   |
| Xiaomi                            | 12        | 0.17%   |
| NetGear                           | 12        | 0.17%   |
| Lenovo                            | 11        | 0.16%   |
| Dresden Elektronik                | 11        | 0.16%   |
| D-Link System                     | 11        | 0.16%   |
| D-Link                            | 11        | 0.16%   |
| ASUSTek Computer                  | 11        | 0.16%   |
| Aquantia                          | 11        | 0.16%   |
| Microsoft                         | 10        | 0.14%   |
| JMicron Technology                | 8         | 0.12%   |
| ICS Advent                        | 8         | 0.12%   |
| VIA Technologies                  | 7         | 0.1%    |
| Ericsson Business Mobile Networks | 7         | 0.1%    |
| Hewlett-Packard                   | 6         | 0.09%   |
| Fibocom                           | 6         | 0.09%   |
| Cypress Semiconductor             | 6         | 0.09%   |
| Standard Microsystems             | 5         | 0.07%   |
| Edimax Technology                 | 5         | 0.07%   |
| American Megatrends               | 5         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1608      | 20.01%  |
| Nvidia MCP79 Ethernet                                                                 | 316       | 3.93%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 309       | 3.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 237       | 2.95%   |
| Intel Wi-Fi 6 AX201                                                                   | 222       | 2.76%   |
| Intel Wi-Fi 6 AX200                                                                   | 156       | 1.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 154       | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 148       | 1.84%   |
| Intel Ethernet Connection (13) I219-V                                                 | 133       | 1.66%   |
| Intel Wireless 7260                                                                   | 131       | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 126       | 1.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 116       | 1.44%   |
| Intel Wireless 8265 / 8275                                                            | 115       | 1.43%   |
| Intel Wireless 7265                                                                   | 109       | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 74        | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 72        | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 71        | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 71        | 0.88%   |
| Intel I211 Gigabit Network Connection                                                 | 68        | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 66        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 66        | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 62        | 0.77%   |
| Intel Wireless 8260                                                                   | 61        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 59        | 0.73%   |
| Intel I210 Gigabit Network Connection                                                 | 57        | 0.71%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 0.7%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 56        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                                        | 56        | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 54        | 0.67%   |
| Intel Wireless 3165                                                                   | 51        | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 45        | 0.56%   |
| Intel Ethernet Connection I217-LM                                                     | 44        | 0.55%   |
| Intel Ethernet Connection (4) I219-V                                                  | 44        | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 42        | 0.52%   |
| Intel Ethernet Connection (2) I219-V                                                  | 41        | 0.51%   |
| Intel Ethernet Controller I225-V                                                      | 40        | 0.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 35        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 35        | 0.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 35        | 0.44%   |
| Intel 82574L Gigabit Network Connection                                               | 35        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1517      | 44.55%  |
| Qualcomm Atheros                | 517       | 15.18%  |
| Broadcom                        | 469       | 13.77%  |
| Realtek Semiconductor           | 411       | 12.07%  |
| Broadcom Limited                | 188       | 5.52%   |
| Ralink Technology               | 54        | 1.59%   |
| MediaTek                        | 46        | 1.35%   |
| Ralink                          | 43        | 1.26%   |
| TP-Link                         | 31        | 0.91%   |
| Qualcomm Atheros Communications | 18        | 0.53%   |
| Sierra Wireless                 | 16        | 0.47%   |
| NetGear                         | 12        | 0.35%   |
| ASUSTek Computer                | 11        | 0.32%   |
| Dell                            | 10        | 0.29%   |
| D-Link                          | 8         | 0.23%   |
| Microsoft                       | 7         | 0.21%   |
| Fibocom                         | 6         | 0.18%   |
| D-Link System                   | 6         | 0.18%   |
| Qualcomm                        | 5         | 0.15%   |
| Edimax Technology               | 5         | 0.15%   |
| Marvell Technology Group        | 4         | 0.12%   |
| IMC Networks                    | 3         | 0.09%   |
| Gemtek                          | 3         | 0.09%   |
| Belkin Components               | 3         | 0.09%   |
| Wilocity                        | 2         | 0.06%   |
| Hewlett-Packard                 | 2         | 0.06%   |
| AVM                             | 2         | 0.06%   |
| Z-Com                           | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Linksys                         | 1         | 0.03%   |
| BUFFALO                         | 1         | 0.03%   |
| 3Com                            | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 309       | 9.04%   |
| Intel Wi-Fi 6 AX201                                                                   | 222       | 6.5%    |
| Intel Wi-Fi 6 AX200                                                                   | 156       | 4.56%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 154       | 4.51%   |
| Intel Wireless 7260                                                                   | 131       | 3.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 126       | 3.69%   |
| Intel Wireless 8265 / 8275                                                            | 115       | 3.36%   |
| Intel Wireless 7265                                                                   | 109       | 3.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 74        | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 72        | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 71        | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 66        | 1.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 66        | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 62        | 1.81%   |
| Intel Wireless 8260                                                                   | 61        | 1.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 59        | 1.73%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 56        | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 54        | 1.58%   |
| Intel Wireless 3165                                                                   | 51        | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 45        | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 42        | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 35        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 35        | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 34        | 0.99%   |
| Intel Wireless-AC 9260                                                                | 31        | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 30        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 28        | 0.82%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 26        | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 25        | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 23        | 0.67%   |
| Intel Wireless 3160                                                                   | 23        | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 22        | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 22        | 0.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 22        | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 21        | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 21        | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 20        | 0.59%   |
| Ralink RT5370 Wireless Adapter                                                        | 19        | 0.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 19        | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2073      | 47.17%  |
| Intel                            | 1187      | 27.01%  |
| Nvidia                           | 357       | 8.12%   |
| Qualcomm Atheros                 | 173       | 3.94%   |
| Broadcom                         | 173       | 3.94%   |
| Marvell Technology Group         | 117       | 2.66%   |
| ASIX Electronics                 | 38        | 0.86%   |
| Broadcom Limited                 | 36        | 0.82%   |
| Samsung Electronics              | 27        | 0.61%   |
| Microchip Technology             | 19        | 0.43%   |
| TP-Link                          | 16        | 0.36%   |
| DisplayLink                      | 13        | 0.3%    |
| Xiaomi                           | 12        | 0.27%   |
| Mellanox Technologies            | 12        | 0.27%   |
| Lenovo                           | 11        | 0.25%   |
| Aquantia                         | 11        | 0.25%   |
| Qualcomm                         | 10        | 0.23%   |
| Huawei Technologies              | 10        | 0.23%   |
| JMicron Technology               | 8         | 0.18%   |
| ICS Advent                       | 8         | 0.18%   |
| VIA Technologies                 | 7         | 0.16%   |
| Cypress Semiconductor            | 6         | 0.14%   |
| Standard Microsystems            | 5         | 0.11%   |
| D-Link System                    | 5         | 0.11%   |
| American Megatrends              | 5         | 0.11%   |
| Silicon Integrated Systems [SiS] | 4         | 0.09%   |
| OPPO Electronics                 | 4         | 0.09%   |
| Attansic Technology              | 4         | 0.09%   |
| NetXen Incorporated              | 3         | 0.07%   |
| Motorola PCS                     | 3         | 0.07%   |
| Microsoft                        | 3         | 0.07%   |
| IBM                              | 3         | 0.07%   |
| D-Link                           | 3         | 0.07%   |
| Apple                            | 3         | 0.07%   |
| QLogic                           | 2         | 0.05%   |
| National Semiconductor           | 2         | 0.05%   |
| MediaTek                         | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| Google                           | 2         | 0.05%   |
| 3Com                             | 2         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1608      | 35.59%  |
| Nvidia MCP79 Ethernet                                             | 316       | 6.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 237       | 5.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 148       | 3.28%   |
| Intel Ethernet Connection (13) I219-V                             | 133       | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 116       | 2.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 71        | 1.57%   |
| Intel I211 Gigabit Network Connection                             | 68        | 1.51%   |
| Intel I210 Gigabit Network Connection                             | 57        | 1.26%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 56        | 1.24%   |
| Intel Ethernet Connection I217-LM                                 | 44        | 0.97%   |
| Intel Ethernet Connection (4) I219-V                              | 44        | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 41        | 0.91%   |
| Intel Ethernet Controller I225-V                                  | 40        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 35        | 0.77%   |
| Intel 82574L Gigabit Network Connection                           | 35        | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 34        | 0.75%   |
| Intel Ethernet Connection (14) I219-V                             | 33        | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                     | 29        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 28        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 28        | 0.62%   |
| Intel Ethernet Connection I219-LM                                 | 27        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 26        | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 26        | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 0.58%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 24        | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                             | 24        | 0.53%   |
| Intel Ethernet Connection (10) I219-V                             | 24        | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 0.51%   |
| Nvidia MCP61 Ethernet                                             | 23        | 0.51%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.51%   |
| Intel I350 Gigabit Network Connection                             | 21        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 19        | 0.42%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 18        | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 17        | 0.38%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 17        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 16        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4136      | 55.07%  |
| WiFi     | 3277      | 43.64%  |
| Modem    | 88        | 1.17%   |
| Unknown  | 9         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2449      | 50.71%  |
| WiFi     | 2380      | 49.29%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2465      | 51.02%  |
| 1     | 1998      | 41.36%  |
| 0     | 170       | 3.52%   |
| 3     | 120       | 2.48%   |
| 4     | 42        | 0.87%   |
| 6     | 14        | 0.29%   |
| 5     | 12        | 0.25%   |
| 8     | 4         | 0.08%   |
| 7     | 2         | 0.04%   |
| 14    | 1         | 0.02%   |
| 13    | 1         | 0.02%   |
| 12    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4031      | 83.1%   |
| Yes  | 820       | 16.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1241      | 44.59%  |
| Apple                           | 585       | 21.02%  |
| Realtek Semiconductor           | 207       | 7.44%   |
| Qualcomm Atheros Communications | 178       | 6.4%    |
| Cambridge Silicon Radio         | 113       | 4.06%   |
| Broadcom                        | 103       | 3.7%    |
| IMC Networks                    | 87        | 3.13%   |
| Lite-On Technology              | 76        | 2.73%   |
| Foxconn / Hon Hai               | 45        | 1.62%   |
| Dell                            | 29        | 1.04%   |
| ASUSTek Computer                | 28        | 1.01%   |
| Hewlett-Packard                 | 20        | 0.72%   |
| Realtek                         | 14        | 0.5%    |
| Ralink                          | 11        | 0.4%    |
| Toshiba                         | 10        | 0.36%   |
| MediaTek                        | 10        | 0.36%   |
| Ralink Technology               | 4         | 0.14%   |
| Taiyo Yuden                     | 3         | 0.11%   |
| Foxconn International           | 3         | 0.11%   |
| Fujitsu                         | 2         | 0.07%   |
| Edimax Technology               | 2         | 0.07%   |
| Belkin Components               | 2         | 0.07%   |
| Alps Electric                   | 2         | 0.07%   |
| USI                             | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Microsoft                       | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Integrated System Solution      | 1         | 0.04%   |
| Dynex                           | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 470       | 16.88%  |
| Intel AX201 Bluetooth                               | 330       | 11.85%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 313       | 11.24%  |
| Apple Bluetooth USB Host Controller                 | 168       | 6.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 158       | 5.68%   |
| Intel AX200 Bluetooth                               | 148       | 5.32%   |
| Realtek Bluetooth Radio                             | 138       | 4.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 113       | 4.06%   |
| Qualcomm Atheros  Bluetooth Device                  | 109       | 3.92%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.73%   |
| Realtek  Bluetooth 4.2 Adapter                      | 51        | 1.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 34        | 1.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 31        | 1.11%   |
| IMC Networks Bluetooth Radio                        | 28        | 1.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 27        | 0.97%   |
| Intel AX210 Bluetooth                               | 26        | 0.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 24        | 0.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 23        | 0.83%   |
| IMC Networks Bluetooth Device                       | 23        | 0.83%   |
| Apple Bluetooth Host Controller                     | 22        | 0.79%   |
| Lite-On Bluetooth Device                            | 21        | 0.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 17        | 0.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 17        | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 17        | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 0.57%   |
| Realtek Bluetooth Radio                             | 14        | 0.5%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 14        | 0.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 14        | 0.5%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 13        | 0.47%   |
| IMC Networks Wireless_Device                        | 13        | 0.47%   |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 0.47%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.43%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.4%    |
| Intel Bluetooth Device                              | 11        | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.36%   |
| MediaTek Wireless_Device                            | 9         | 0.32%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.29%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 8         | 0.29%   |
| Dell DW375 Bluetooth Module                         | 8         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3293      | 56.53%  |
| Nvidia                                       | 1102      | 18.92%  |
| AMD                                          | 974       | 16.72%  |
| C-Media Electronics                          | 69        | 1.18%   |
| Logitech                                     | 37        | 0.64%   |
| Creative Labs                                | 23        | 0.39%   |
| Texas Instruments                            | 22        | 0.38%   |
| Generalplus Technology                       | 21        | 0.36%   |
| Plantronics                                  | 16        | 0.27%   |
| Creative Technology                          | 15        | 0.26%   |
| ASUSTek Computer                             | 15        | 0.26%   |
| Lenovo                                       | 14        | 0.24%   |
| Realtek Semiconductor                        | 13        | 0.22%   |
| JMTek                                        | 12        | 0.21%   |
| Kingston Technology                          | 11        | 0.19%   |
| GN Netcom                                    | 11        | 0.19%   |
| Focusrite-Novation                           | 11        | 0.19%   |
| VIA Technologies                             | 10        | 0.17%   |
| Sennheiser Communications                    | 7         | 0.12%   |
| RODE Microphones                             | 7         | 0.12%   |
| GYROCOM C&C                                  | 7         | 0.12%   |
| SteelSeries ApS                              | 6         | 0.1%    |
| Hewlett-Packard                              | 6         | 0.1%    |
| Razer USA                                    | 5         | 0.09%   |
| Microsoft                                    | 5         | 0.09%   |
| Micro Star International                     | 5         | 0.09%   |
| Cambridge Silicon Radio                      | 5         | 0.09%   |
| BEHRINGER International                      | 5         | 0.09%   |
| Yamaha                                       | 4         | 0.07%   |
| Unknown                                      | 4         | 0.07%   |
| Tenx Technology                              | 3         | 0.05%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.05%   |
| Samson Technologies                          | 3         | 0.05%   |
| M-Audio                                      | 3         | 0.05%   |
| Dell                                         | 3         | 0.05%   |
| CMX Systems                                  | 3         | 0.05%   |
| Blue Microphones                             | 3         | 0.05%   |
| Apple                                        | 3         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| Zhaoxin                                      | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 335       | 4.85%   |
| Nvidia MCP79 High Definition Audio                                                                | 318       | 4.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 273       | 3.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 270       | 3.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 244       | 3.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 242       | 3.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 232       | 3.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 224       | 3.24%   |
| Intel Broadwell-U Audio Controller                                                                | 213       | 3.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 208       | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 186       | 2.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 155       | 2.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 152       | 2.2%    |
| Intel Cannon Lake PCH cAVS                                                                        | 136       | 1.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 133       | 1.92%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 131       | 1.9%    |
| Intel 200 Series PCH HD Audio                                                                     | 122       | 1.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 114       | 1.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 112       | 1.62%   |
| Intel Comet Lake PCH cAVS                                                                         | 102       | 1.48%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 96        | 1.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 87        | 1.26%   |
| AMD FCH Azalia Controller                                                                         | 78        | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 77        | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 77        | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 76        | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                                          | 76        | 1.1%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 72        | 1.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 72        | 1.04%   |
| Intel 8 Series HD Audio Controller                                                                | 72        | 1.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 70        | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 68        | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 61        | 0.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 60        | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 59        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 58        | 0.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 58        | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 50        | 0.72%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 50        | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 46        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 1012      | 21.72%  |
| Samsung Electronics | 1011      | 21.7%   |
| Kingston            | 490       | 10.52%  |
| Unknown             | 425       | 9.12%   |
| Crucial             | 418       | 8.97%   |
| Micron Technology   | 341       | 7.32%   |
| Corsair             | 154       | 3.31%   |
| G.Skill             | 102       | 2.19%   |
| Elpida              | 97        | 2.08%   |
| A-DATA Technology   | 75        | 1.61%   |
| Patriot             | 63        | 1.35%   |
| Ramaxel Technology  | 61        | 1.31%   |
| Unknown             | 56        | 1.2%    |
| Nanya Technology    | 44        | 0.94%   |
| Unknown (ABCD)      | 38        | 0.82%   |
| Team                | 28        | 0.6%    |
| GOODRAM             | 23        | 0.49%   |
| Hikvision           | 21        | 0.45%   |
| Smart               | 18        | 0.39%   |
| Transcend           | 17        | 0.36%   |
| AMD                 | 17        | 0.36%   |
| Qimonda             | 8         | 0.17%   |
| Apacer              | 7         | 0.15%   |
| Hewlett-Packard     | 6         | 0.13%   |
| Timetec             | 5         | 0.11%   |
| Silicon Power       | 5         | 0.11%   |
| GeIL                | 5         | 0.11%   |
| Wilk                | 4         | 0.09%   |
| Unifosa             | 4         | 0.09%   |
| PNY                 | 4         | 0.09%   |
| Infineon            | 4         | 0.09%   |
| Goldkey             | 4         | 0.09%   |
| ASint Technology    | 4         | 0.09%   |
| 48spaces            | 4         | 0.09%   |
| Toshiba             | 3         | 0.06%   |
| Teikon              | 3         | 0.06%   |
| Smart Brazil        | 3         | 0.06%   |
| Neo Forza           | 3         | 0.06%   |
| Kllisre             | 3         | 0.06%   |
| Kingmax             | 3         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 257       | 5.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 141       | 2.84%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.37%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 61        | 1.23%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 61        | 1.23%   |
| Unknown                                                          | 56        | 1.13%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 0.89%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 38        | 0.77%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 37        | 0.75%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s            | 33        | 0.67%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s            | 31        | 0.62%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.58%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 28        | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 27        | 0.54%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 27        | 0.54%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s           | 26        | 0.52%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.5%    |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 24        | 0.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 24        | 0.48%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s             | 24        | 0.48%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 22        | 0.44%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 22        | 0.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.42%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s          | 20        | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 19        | 0.38%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 19        | 0.38%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.38%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 18        | 0.36%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 18        | 0.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.36%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s            | 18        | 0.36%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 0.34%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 17        | 0.34%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 16        | 0.32%   |
| Patriot RAM PSD34G160081 4096MB DIMM DDR3 1600MT/s               | 16        | 0.32%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s             | 16        | 0.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 15        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 1726      | 41.61%  |
| DDR3         | 1357      | 32.71%  |
| DDR2         | 538       | 12.97%  |
| SDRAM        | 142       | 3.42%   |
| Unknown      | 124       | 2.99%   |
| LPDDR4       | 102       | 2.46%   |
| LPDDR3       | 93        | 2.24%   |
| DDR          | 48        | 1.16%   |
| DRAM         | 8         | 0.19%   |
| DDR5         | 7         | 0.17%   |
| LPDDR5       | 2         | 0.05%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2393      | 57.8%   |
| DIMM         | 1524      | 36.81%  |
| Row Of Chips | 149       | 3.6%    |
| Unknown      | 40        | 0.97%   |
| Chip         | 27        | 0.65%   |
| FB-DIMM      | 5         | 0.12%   |
| RIMM         | 2         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1370      | 30.77%  |
| 4096  | 1085      | 24.37%  |
| 2048  | 720       | 16.17%  |
| 1024  | 549       | 12.33%  |
| 16384 | 495       | 11.12%  |
| 32768 | 157       | 3.53%   |
| 512   | 51        | 1.15%   |
| 256   | 17        | 0.38%   |
| 65536 | 6         | 0.13%   |
| 1536  | 1         | 0.02%   |
| 128   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 918       | 20.81%  |
| 3200    | 631       | 14.31%  |
| 2667    | 550       | 12.47%  |
| 800     | 404       | 9.16%   |
| 1333    | 307       | 6.96%   |
| 2400    | 274       | 6.21%   |
| 2133    | 173       | 3.92%   |
| 667     | 171       | 3.88%   |
| Unknown | 127       | 2.88%   |
| 1334    | 93        | 2.11%   |
| 3600    | 71        | 1.61%   |
| 1867    | 64        | 1.45%   |
| 1866    | 61        | 1.38%   |
| 2666    | 60        | 1.36%   |
| 1067    | 53        | 1.2%    |
| 4267    | 38        | 0.86%   |
| 1066    | 37        | 0.84%   |
| 3000    | 26        | 0.59%   |
| 2866    | 25        | 0.57%   |
| 3400    | 24        | 0.54%   |
| 3266    | 24        | 0.54%   |
| 533     | 21        | 0.48%   |
| 2933    | 20        | 0.45%   |
| 3466    | 19        | 0.43%   |
| 4199    | 17        | 0.39%   |
| 3733    | 16        | 0.36%   |
| 1800    | 16        | 0.36%   |
| 2048    | 14        | 0.32%   |
| 400     | 14        | 0.32%   |
| 333     | 12        | 0.27%   |
| 4800    | 10        | 0.23%   |
| 266     | 10        | 0.23%   |
| 3866    | 9         | 0.2%    |
| 3800    | 8         | 0.18%   |
| 975     | 8         | 0.18%   |
| 8400    | 7         | 0.16%   |
| 4333    | 7         | 0.16%   |
| 4266    | 6         | 0.14%   |
| 3066    | 6         | 0.14%   |
| 3100    | 5         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 35        | 36.46%  |
| Brother Industries     | 16        | 16.67%  |
| Canon                  | 9         | 9.38%   |
| Xerox                  | 8         | 8.33%   |
| Samsung Electronics    | 7         | 7.29%   |
| Seiko Epson            | 4         | 4.17%   |
| Dymo-CoStar            | 4         | 4.17%   |
| Prolific Technology    | 3         | 3.13%   |
| Zebra                  | 2         | 2.08%   |
| Pantum                 | 2         | 2.08%   |
| STMicroelectronics     | 1         | 1.04%   |
| Panasonic (Matsushita) | 1         | 1.04%   |
| Kyocera                | 1         | 1.04%   |
| Konica Minolta         | 1         | 1.04%   |
| GODEX INTERNATIONAL    | 1         | 1.04%   |
| Apple                  | 1         | 1.04%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xerox B205                                                            | 7         | 7.29%   |
| Prolific PL2305 Parallel Port                                         | 3         | 3.13%   |
| HP LaserJet M101-M106                                                 | 3         | 3.13%   |
| HP LaserJet 1200                                                      | 3         | 3.13%   |
| HP LaserJet 1020                                                      | 3         | 3.13%   |
| Samsung ML-1660 Series                                                | 2         | 2.08%   |
| HP LaserJet P1005                                                     | 2         | 2.08%   |
| HP ENVY 4520 series                                                   | 2         | 2.08%   |
| HP DeskJet 2620 All-in-One Printer                                    | 2         | 2.08%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 2.08%   |
| Canon LiDE 400                                                        | 2         | 2.08%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 1.04%   |
| Zebra ZTC ZD420-203dpi ZPL                                            | 1         | 1.04%   |
| Xerox Phaser 3250                                                     | 1         | 1.04%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 1.04%   |
| Seiko Epson XP-200 Series                                             | 1         | 1.04%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 1.04%   |
| Seiko Epson L4150 Series                                              | 1         | 1.04%   |
| Seiko Epson ET-2850 Series                                            | 1         | 1.04%   |
| Samsung SCX-4650 4x21S Series                                         | 1         | 1.04%   |
| Samsung SCX-3200 Series                                               | 1         | 1.04%   |
| Samsung ML-216x Series Laser Printer                                  | 1         | 1.04%   |
| Samsung ML-2010P Mono Laser Printer                                   | 1         | 1.04%   |
| Samsung ML-1520 Laser Printer                                         | 1         | 1.04%   |
| Pantum P2500W series                                                  | 1         | 1.04%   |
| Pantum M6500-series                                                   | 1         | 1.04%   |
| Panasonic (Matsushita) KX-MB1500RU                                    | 1         | 1.04%   |
| Kyocera ECOSYS M5521cdn                                               | 1         | 1.04%   |
| Konica Minolta bizhub 4402P                                           | 1         | 1.04%   |
| HP Officejet J4500 series                                             | 1         | 1.04%   |
| HP Officejet 7110 series                                              | 1         | 1.04%   |
| HP LaserJet Pro M404-M405                                             | 1         | 1.04%   |
| HP LaserJet Pro M148-M149                                             | 1         | 1.04%   |
| HP LaserJet P2055 series                                              | 1         | 1.04%   |
| HP Laserjet P1505                                                     | 1         | 1.04%   |
| HP LaserJet P1006                                                     | 1         | 1.04%   |
| HP LaserJet M14-M17                                                   | 1         | 1.04%   |
| HP LaserJet 400 M401dne                                               | 1         | 1.04%   |
| HP LaserJet 1300                                                      | 1         | 1.04%   |
| HP LaserJet 1160 series                                               | 1         | 1.04%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 15        | 57.69%  |
| Seiko Epson     | 6         | 23.08%  |
| Hewlett-Packard | 3         | 11.54%  |
| AGFA-Gevaert NV | 2         | 7.69%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                       | 4         | 15.38%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 3         | 11.54%  |
| Canon CanoScan LiDE 120                                       | 2         | 7.69%   |
| Canon CanoScan LiDE 110                                       | 2         | 7.69%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2         | 7.69%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 3.85%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1         | 3.85%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 3.85%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 3.85%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                 | 1         | 3.85%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 3.85%   |
| HP ScanJet Pro 2500 f1                                        | 1         | 3.85%   |
| HP ScanJet 3970c                                              | 1         | 3.85%   |
| HP Scanjet 300                                                | 1         | 3.85%   |
| Canon CanoScan LIDE 25                                        | 1         | 3.85%   |
| Canon CanoScan LiDE 210                                       | 1         | 3.85%   |
| Canon CanoScan 8800F                                          | 1         | 3.85%   |
| Canon CanoScan 5600F                                          | 1         | 3.85%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 538       | 23.14%  |
| Acer                                   | 308       | 13.25%  |
| IMC Networks                           | 225       | 9.68%   |
| Quanta                                 | 188       | 8.09%   |
| Microdia                               | 163       | 7.01%   |
| Realtek Semiconductor                  | 139       | 5.98%   |
| Logitech                               | 128       | 5.51%   |
| Sunplus Innovation Technology          | 85        | 3.66%   |
| Cheng Uei Precision Industry (Foxlink) | 64        | 2.75%   |
| Apple                                  | 61        | 2.62%   |
| Suyin                                  | 53        | 2.28%   |
| Lite-On Technology                     | 45        | 1.94%   |
| Syntek                                 | 44        | 1.89%   |
| Luxvisions Innotech Limited            | 36        | 1.55%   |
| Silicon Motion                         | 19        | 0.82%   |
| Alcor Micro                            | 19        | 0.82%   |
| Lenovo                                 | 17        | 0.73%   |
| Z-Star Microelectronics                | 13        | 0.56%   |
| Generalplus Technology                 | 13        | 0.56%   |
| Ricoh                                  | 11        | 0.47%   |
| Microsoft                              | 11        | 0.47%   |
| Samsung Electronics                    | 10        | 0.43%   |
| Sonix Technology                       | 9         | 0.39%   |
| Primax Electronics                     | 7         | 0.3%    |
| Creative Technology                    | 7         | 0.3%    |
| KYE Systems (Mouse Systems)            | 6         | 0.26%   |
| Genesys Logic                          | 6         | 0.26%   |
| SunplusIT                              | 5         | 0.22%   |
| Jieli Technology                       | 5         | 0.22%   |
| Importek                               | 5         | 0.22%   |
| ARC International                      | 5         | 0.22%   |
| ALi                                    | 5         | 0.22%   |
| Unknown                                | 4         | 0.17%   |
| Intel                                  | 4         | 0.17%   |
| Y Media                                | 3         | 0.13%   |
| Novatek Microelectronics               | 3         | 0.13%   |
| Mimaki Engineering                     | 3         | 0.13%   |
| MacroSilicon                           | 3         | 0.13%   |
| GEMBIRD                                | 3         | 0.13%   |
| DJKANA19IDX53W                         | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 181       | 7.62%   |
| Acer Integrated Camera                              | 127       | 5.35%   |
| Microdia Integrated_Webcam_HD                       | 74        | 3.12%   |
| Acer Integrated 5M Camera                           | 73        | 3.07%   |
| IMC Networks Integrated Camera                      | 71        | 2.99%   |
| Quanta Chromebook HD Camera                         | 67        | 2.82%   |
| Acer BisonCam, NB Pro                               | 52        | 2.19%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 49        | 2.06%   |
| Realtek Integrated_Webcam_HD                        | 48        | 2.02%   |
| Chicony Integrated 5M Camera                        | 43        | 1.81%   |
| Logitech Webcam C270                                | 41        | 1.73%   |
| Chicony HD Webcam                                   | 40        | 1.68%   |
| Chicony USB2.0 HD UVC WebCam                        | 29        | 1.22%   |
| Sunplus Integrated_Webcam_HD                        | 26        | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 25        | 1.05%   |
| Syntek Integrated Camera                            | 24        | 1.01%   |
| Chicony HP HD Camera                                | 24        | 1.01%   |
| Quanta HP TrueVision HD Camera                      | 23        | 0.97%   |
| Apple Built-in iSight                               | 22        | 0.93%   |
| Quanta VGA WebCam                                   | 21        | 0.88%   |
| Realtek USB Camera                                  | 19        | 0.8%    |
| Quanta HD User Facing                               | 19        | 0.8%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 18        | 0.76%   |
| Apple iPhone 5/5C/5S/6/SE                           | 18        | 0.76%   |
| Lite-On Integrated Camera                           | 17        | 0.72%   |
| Acer SunplusIT Integrated Camera                    | 17        | 0.72%   |
| Chicony Integrated Camera (1280x720@30)             | 15        | 0.63%   |
| Chicony Chromebook HD Camera                        | 15        | 0.63%   |
| Microdia Integrated Webcam                          | 14        | 0.59%   |
| Logitech HD Pro Webcam C920                         | 13        | 0.55%   |
| Logitech C922 Pro Stream Webcam                     | 13        | 0.55%   |
| IMC Networks USB 2.0 Camera                         | 13        | 0.55%   |
| Chicony HP Webcam                                   | 13        | 0.55%   |
| Apple FaceTime HD Camera (Built-in)                 | 13        | 0.55%   |
| Quanta HP HD Camera                                 | 12        | 0.51%   |
| Chicony HP TrueVision HD Camera                     | 12        | 0.51%   |
| Chicony HD User Facing                              | 12        | 0.51%   |
| Acer Lenovo Integrated Webcam                       | 12        | 0.51%   |
| Suyin HP TrueVision HD                              | 11        | 0.46%   |
| Luxvisions Innotech Limited HP HD Camera            | 11        | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 245       | 46.4%   |
| Validity Sensors                   | 143       | 27.08%  |
| Shenzhen Goodix Technology         | 60        | 11.36%  |
| AuthenTec                          | 21        | 3.98%   |
| Elan Microelectronics              | 19        | 3.6%    |
| Upek                               | 18        | 3.41%   |
| LighTuning Technology              | 13        | 2.46%   |
| STMicroelectronics                 | 7         | 1.33%   |
| Samsung Electronics                | 1         | 0.19%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 169       | 32.01%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 37        | 7.01%   |
| Shenzhen Goodix  Fingerprint Device                                        | 31        | 5.87%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 28        | 5.3%    |
| Unknown                                                                    | 27        | 5.11%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 4.36%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 3.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 3.03%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 2.84%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 2.65%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 2.46%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.27%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 1.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.33%   |
| Synaptics  WBDI                                                            | 7         | 1.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 1.33%   |
| Elan ELAN:ARM-M4                                                           | 7         | 1.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.14%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 0.95%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 0.95%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 0.95%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 0.95%   |
| AuthenTec AES2810                                                          | 4         | 0.76%   |
| Validity Sensors VFS491                                                    | 3         | 0.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.57%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.38%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.38%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.38%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.38%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.38%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.38%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.38%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.19%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.19%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 73        | 35.61%  |
| Broadcom                  | 67        | 32.68%  |
| Upek                      | 19        | 9.27%   |
| O2 Micro                  | 14        | 6.83%   |
| Lenovo                    | 13        | 6.34%   |
| Gemalto (was Gemplus)     | 4         | 1.95%   |
| Yubico.com                | 3         | 1.46%   |
| SCM Microsystems          | 2         | 0.98%   |
| Clay Logic                | 2         | 0.98%   |
| Cherry                    | 2         | 0.98%   |
| Aladdin Knowledge Systems | 2         | 0.98%   |
| Reiner SCT Kartensysteme  | 1         | 0.49%   |
| OmniKey                   | 1         | 0.49%   |
| Chicony Electronics       | 1         | 0.49%   |
| C3PO                      | 1         | 0.49%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 71        | 34.63%  |
| Broadcom 58200                                                               | 22        | 10.73%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 9.76%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 19        | 9.27%   |
| Broadcom 5880                                                                | 16        | 7.8%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 12        | 5.85%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 5.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 3.9%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.98%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 0.98%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.98%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.98%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.98%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.98%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.49%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.49%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.49%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.49%   |
| OmniKey CardMan 4321                                                         | 1         | 0.49%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.49%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.49%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.49%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.49%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.49%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.49%   |
| C3PO LTC31v2                                                                 | 1         | 0.49%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.49%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2777      | 57.07%  |
| 1     | 1725      | 35.45%  |
| 2     | 294       | 6.04%   |
| 3     | 57        | 1.17%   |
| 4     | 7         | 0.14%   |
| 5     | 4         | 0.08%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1072      | 44.44%  |
| Fingerprint reader       | 526       | 21.81%  |
| Multimedia controller    | 212       | 8.79%   |
| Chipcard                 | 180       | 7.46%   |
| Net/wireless             | 168       | 6.97%   |
| Communication controller | 67        | 2.78%   |
| Unassigned class         | 44        | 1.82%   |
| Bluetooth                | 36        | 1.49%   |
| Card reader              | 22        | 0.91%   |
| Storage                  | 19        | 0.79%   |
| Sound                    | 18        | 0.75%   |
| Camera                   | 14        | 0.58%   |
| Net/ethernet             | 9         | 0.37%   |
| Network                  | 7         | 0.29%   |
| Modem                    | 6         | 0.25%   |
| Tv card                  | 3         | 0.12%   |
| Storage/raid             | 3         | 0.12%   |
| Flash memory             | 2         | 0.08%   |
| Dvb card                 | 2         | 0.08%   |
| Storage/ide              | 1         | 0.04%   |
| Firewire controller      | 1         | 0.04%   |

