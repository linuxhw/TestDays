openSUSE - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for openSUSE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE/Desktop/README.md) and [notebooks](/Dist/openSUSE/Notebook/README.md).

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

Total: 3477

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Y580 2099           | Notebook    | [d0db961274](https://linux-hardware.org/?probe=d0db961274) | Sep 07, 2023 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | Desktop     | [1e743d0b2d](https://linux-hardware.org/?probe=1e743d0b2d) | Sep 06, 2023 |
| HP            | ProBook 4530s               | Notebook    | [782493cb7d](https://linux-hardware.org/?probe=782493cb7d) | Sep 06, 2023 |
| HP            | ProBook 4540s               | Notebook    | [be4077d1c0](https://linux-hardware.org/?probe=be4077d1c0) | Sep 06, 2023 |
| Sony          | SVF1521A7EB                 | Notebook    | [8b130feb09](https://linux-hardware.org/?probe=8b130feb09) | Sep 06, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [0d796a5d20](https://linux-hardware.org/?probe=0d796a5d20) | Sep 05, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [12ed8aee3f](https://linux-hardware.org/?probe=12ed8aee3f) | Sep 05, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [fdcab89946](https://linux-hardware.org/?probe=fdcab89946) | Sep 05, 2023 |
| Samsung       | 750QUA                      | Convertible | [d409932f7d](https://linux-hardware.org/?probe=d409932f7d) | Sep 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | Notebook    | [8253da4d01](https://linux-hardware.org/?probe=8253da4d01) | Sep 04, 2023 |
| HP            | 2129                        | Desktop     | [d021b12b77](https://linux-hardware.org/?probe=d021b12b77) | Sep 04, 2023 |
| ASRock        | Z490 Phantom Gaming 4/ac    | Desktop     | [5fa23571c9](https://linux-hardware.org/?probe=5fa23571c9) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [a0e83b70f5](https://linux-hardware.org/?probe=a0e83b70f5) | Sep 03, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [91bc08d933](https://linux-hardware.org/?probe=91bc08d933) | Sep 03, 2023 |
| Alienware     | m15 R7                      | Notebook    | [3d070813ea](https://linux-hardware.org/?probe=3d070813ea) | Sep 03, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [8ed88aa6f1](https://linux-hardware.org/?probe=8ed88aa6f1) | Sep 03, 2023 |
| Medion        | S15449                      | Notebook    | [7e8cd1a434](https://linux-hardware.org/?probe=7e8cd1a434) | Sep 02, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [78037f5e38](https://linux-hardware.org/?probe=78037f5e38) | Sep 02, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [1521626729](https://linux-hardware.org/?probe=1521626729) | Sep 02, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [22c3bee6fa](https://linux-hardware.org/?probe=22c3bee6fa) | Sep 02, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [315510322c](https://linux-hardware.org/?probe=315510322c) | Sep 02, 2023 |
| Dell          | Precision 7560              | Notebook    | [d9d73d82f2](https://linux-hardware.org/?probe=d9d73d82f2) | Sep 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [318dc8ce55](https://linux-hardware.org/?probe=318dc8ce55) | Sep 01, 2023 |
| Acer          | Aspire A317-32              | Notebook    | [0a46c781fc](https://linux-hardware.org/?probe=0a46c781fc) | Sep 01, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [e7c4150ded](https://linux-hardware.org/?probe=e7c4150ded) | Sep 01, 2023 |
| Lenovo        | ThinkPad T420 42364A1       | Notebook    | [968cd5e999](https://linux-hardware.org/?probe=968cd5e999) | Aug 31, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [fd3c900751](https://linux-hardware.org/?probe=fd3c900751) | Aug 31, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [b68a6514c4](https://linux-hardware.org/?probe=b68a6514c4) | Aug 30, 2023 |
| ASUSTek       | UX303LN                     | Notebook    | [43e624c0b4](https://linux-hardware.org/?probe=43e624c0b4) | Aug 30, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [ad844f1a8c](https://linux-hardware.org/?probe=ad844f1a8c) | Aug 30, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [0c279f8cf0](https://linux-hardware.org/?probe=0c279f8cf0) | Aug 30, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [a21f3ba335](https://linux-hardware.org/?probe=a21f3ba335) | Aug 30, 2023 |
| Dell          | 0K06NC A00                  | All in one  | [75acf7c3bf](https://linux-hardware.org/?probe=75acf7c3bf) | Aug 30, 2023 |
| Dell          | 0K06NC A00                  | All in one  | [616c88aa53](https://linux-hardware.org/?probe=616c88aa53) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470p 20J60014P... | Notebook    | [7690eb9089](https://linux-hardware.org/?probe=7690eb9089) | Aug 30, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [704a62ef33](https://linux-hardware.org/?probe=704a62ef33) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [beb1174dde](https://linux-hardware.org/?probe=beb1174dde) | Aug 29, 2023 |
| Huanan        | X99-ZD4 V2.1                | Desktop     | [2ab7a21e20](https://linux-hardware.org/?probe=2ab7a21e20) | Aug 29, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [a9cd91e3be](https://linux-hardware.org/?probe=a9cd91e3be) | Aug 28, 2023 |
| Dell          | 068CDY A01                  | Server      | [1debff900a](https://linux-hardware.org/?probe=1debff900a) | Aug 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [11d516749d](https://linux-hardware.org/?probe=11d516749d) | Aug 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [960039f680](https://linux-hardware.org/?probe=960039f680) | Aug 28, 2023 |
| Gigabyte      | B75M-D3P                    | Desktop     | [73562af96c](https://linux-hardware.org/?probe=73562af96c) | Aug 28, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [b2ecdef159](https://linux-hardware.org/?probe=b2ecdef159) | Aug 27, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [08ec98196f](https://linux-hardware.org/?probe=08ec98196f) | Aug 27, 2023 |
| Biostar       | B550GTA                     | Desktop     | [218cce14a5](https://linux-hardware.org/?probe=218cce14a5) | Aug 26, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [821972776e](https://linux-hardware.org/?probe=821972776e) | Aug 26, 2023 |
| HP            | 2129                        | Desktop     | [7ebe21012d](https://linux-hardware.org/?probe=7ebe21012d) | Aug 26, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [c5b6554c6b](https://linux-hardware.org/?probe=c5b6554c6b) | Aug 26, 2023 |
| Dell          | Vostro 1450                 | Notebook    | [1aad0f5aa3](https://linux-hardware.org/?probe=1aad0f5aa3) | Aug 26, 2023 |
| Dell          | Latitude E6440              | Notebook    | [b2f6ae2fdd](https://linux-hardware.org/?probe=b2f6ae2fdd) | Aug 26, 2023 |
| Dell          | Latitude E6440              | Notebook    | [1a9a8b3267](https://linux-hardware.org/?probe=1a9a8b3267) | Aug 26, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | Notebook    | [adb5d31da7](https://linux-hardware.org/?probe=adb5d31da7) | Aug 25, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [083aa2f63c](https://linux-hardware.org/?probe=083aa2f63c) | Aug 25, 2023 |
| Biostar       | TF570 SLI A2+               | Desktop     | [825725cf8d](https://linux-hardware.org/?probe=825725cf8d) | Aug 25, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [f5e13ec783](https://linux-hardware.org/?probe=f5e13ec783) | Aug 25, 2023 |
| Dell          | Latitude 3440               | Notebook    | [ec46985a7b](https://linux-hardware.org/?probe=ec46985a7b) | Aug 24, 2023 |
| ASUSTek       | Z9NA-D6                     | Server      | [4e4302c5f0](https://linux-hardware.org/?probe=4e4302c5f0) | Aug 24, 2023 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [0cf842e282](https://linux-hardware.org/?probe=0cf842e282) | Aug 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [58d50740e7](https://linux-hardware.org/?probe=58d50740e7) | Aug 24, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b141917712](https://linux-hardware.org/?probe=b141917712) | Aug 23, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [28c491dd90](https://linux-hardware.org/?probe=28c491dd90) | Aug 23, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [e5e47ca15c](https://linux-hardware.org/?probe=e5e47ca15c) | Aug 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6b9175d89e](https://linux-hardware.org/?probe=6b9175d89e) | Aug 22, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [a89271bc7d](https://linux-hardware.org/?probe=a89271bc7d) | Aug 22, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [10345216a9](https://linux-hardware.org/?probe=10345216a9) | Aug 22, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [625ff7df38](https://linux-hardware.org/?probe=625ff7df38) | Aug 22, 2023 |
| Biostar       | TF570 SLI A2+               | Desktop     | [3d706eb2f3](https://linux-hardware.org/?probe=3d706eb2f3) | Aug 21, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [2e8b5e3b34](https://linux-hardware.org/?probe=2e8b5e3b34) | Aug 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | Notebook    | [1a86753f1c](https://linux-hardware.org/?probe=1a86753f1c) | Aug 20, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [99cdeba16c](https://linux-hardware.org/?probe=99cdeba16c) | Aug 20, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [58eff7a9fb](https://linux-hardware.org/?probe=58eff7a9fb) | Aug 20, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [857e3132c1](https://linux-hardware.org/?probe=857e3132c1) | Aug 19, 2023 |
| ASRock        | Z270 Pro4                   | Desktop     | [de0587ccf3](https://linux-hardware.org/?probe=de0587ccf3) | Aug 19, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [60545dcc97](https://linux-hardware.org/?probe=60545dcc97) | Aug 19, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [f59c0429a1](https://linux-hardware.org/?probe=f59c0429a1) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6249529a81](https://linux-hardware.org/?probe=6249529a81) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [a58174338d](https://linux-hardware.org/?probe=a58174338d) | Aug 18, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [2c42cc3ebb](https://linux-hardware.org/?probe=2c42cc3ebb) | Aug 18, 2023 |
| Dell          | Latitude 5414               | Notebook    | [0716b41629](https://linux-hardware.org/?probe=0716b41629) | Aug 18, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [e21dbce888](https://linux-hardware.org/?probe=e21dbce888) | Aug 17, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [5a62fd8541](https://linux-hardware.org/?probe=5a62fd8541) | Aug 17, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | Notebook    | [98629bd8c4](https://linux-hardware.org/?probe=98629bd8c4) | Aug 17, 2023 |
| Lenovo        | K14 Gen 1 21CUS02600        | Notebook    | [6fedf0eae5](https://linux-hardware.org/?probe=6fedf0eae5) | Aug 17, 2023 |
| Dell          | Latitude 7290               | Notebook    | [eb12e0d829](https://linux-hardware.org/?probe=eb12e0d829) | Aug 17, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [4c36ef643e](https://linux-hardware.org/?probe=4c36ef643e) | Aug 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [d2b1d6e9ad](https://linux-hardware.org/?probe=d2b1d6e9ad) | Aug 16, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [cf9cfddfa5](https://linux-hardware.org/?probe=cf9cfddfa5) | Aug 16, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [6c3b1a6ddd](https://linux-hardware.org/?probe=6c3b1a6ddd) | Aug 16, 2023 |
| Dell          | Latitude 5414               | Notebook    | [74b8020613](https://linux-hardware.org/?probe=74b8020613) | Aug 16, 2023 |
| Gigabyte      | Z590 VISION G               | Desktop     | [0954ff78e7](https://linux-hardware.org/?probe=0954ff78e7) | Aug 16, 2023 |
| ASUSTek       | M4A77TD                     | Desktop     | [a2c6278e77](https://linux-hardware.org/?probe=a2c6278e77) | Aug 15, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [620d12291b](https://linux-hardware.org/?probe=620d12291b) | Aug 15, 2023 |
| Toshiba       | Satellite Pro C70-A         | Notebook    | [dbb00fe95b](https://linux-hardware.org/?probe=dbb00fe95b) | Aug 15, 2023 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [488d5ee081](https://linux-hardware.org/?probe=488d5ee081) | Aug 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4e79ef6905](https://linux-hardware.org/?probe=4e79ef6905) | Aug 15, 2023 |
| Dell          | Latitude 5414               | Notebook    | [de4295d568](https://linux-hardware.org/?probe=de4295d568) | Aug 15, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5432051007](https://linux-hardware.org/?probe=5432051007) | Aug 15, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [cbd08a7649](https://linux-hardware.org/?probe=cbd08a7649) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b62ff7f358](https://linux-hardware.org/?probe=b62ff7f358) | Aug 14, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [2f82c5eb18](https://linux-hardware.org/?probe=2f82c5eb18) | Aug 14, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [ceebf749ba](https://linux-hardware.org/?probe=ceebf749ba) | Aug 14, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [f523831970](https://linux-hardware.org/?probe=f523831970) | Aug 14, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [53717914de](https://linux-hardware.org/?probe=53717914de) | Aug 14, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e2fadc37f2](https://linux-hardware.org/?probe=e2fadc37f2) | Aug 14, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [b0e10f6505](https://linux-hardware.org/?probe=b0e10f6505) | Aug 13, 2023 |
| Intel         | DX58OG AAG10926-205         | Desktop     | [cb3a9289f9](https://linux-hardware.org/?probe=cb3a9289f9) | Aug 13, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [66bcc74be2](https://linux-hardware.org/?probe=66bcc74be2) | Aug 13, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [f0f6b13bf3](https://linux-hardware.org/?probe=f0f6b13bf3) | Aug 13, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [d1fddefbb1](https://linux-hardware.org/?probe=d1fddefbb1) | Aug 13, 2023 |
| HP            | EliteBook 845 G9            | Notebook    | [cf6dfa50ef](https://linux-hardware.org/?probe=cf6dfa50ef) | Aug 12, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d3d3ef7119](https://linux-hardware.org/?probe=d3d3ef7119) | Aug 12, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [5d96610622](https://linux-hardware.org/?probe=5d96610622) | Aug 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [a737674e04](https://linux-hardware.org/?probe=a737674e04) | Aug 12, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e374cc3341](https://linux-hardware.org/?probe=e374cc3341) | Aug 12, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [9aa2cd7b81](https://linux-hardware.org/?probe=9aa2cd7b81) | Aug 12, 2023 |
| Dell          | G7 7790                     | Notebook    | [b5062f0928](https://linux-hardware.org/?probe=b5062f0928) | Aug 12, 2023 |
| HP            | 1589                        | Desktop     | [1a38154020](https://linux-hardware.org/?probe=1a38154020) | Aug 12, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8193c225e5](https://linux-hardware.org/?probe=8193c225e5) | Aug 11, 2023 |
| MSI           | Sword 17 A11UD              | Notebook    | [8ad81394c8](https://linux-hardware.org/?probe=8ad81394c8) | Aug 11, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [1c2e98b598](https://linux-hardware.org/?probe=1c2e98b598) | Aug 11, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6f722400c2](https://linux-hardware.org/?probe=6f722400c2) | Aug 11, 2023 |
| Acer          | Aspire V5-471P              | Notebook    | [cbd4a63b2e](https://linux-hardware.org/?probe=cbd4a63b2e) | Aug 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f20a32551b](https://linux-hardware.org/?probe=f20a32551b) | Aug 10, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [9ce8c0dd74](https://linux-hardware.org/?probe=9ce8c0dd74) | Aug 10, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [f4dd9cbbbd](https://linux-hardware.org/?probe=f4dd9cbbbd) | Aug 10, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [c2b7b4e760](https://linux-hardware.org/?probe=c2b7b4e760) | Aug 10, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [45c782fc7e](https://linux-hardware.org/?probe=45c782fc7e) | Aug 10, 2023 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [0ca6c48c2f](https://linux-hardware.org/?probe=0ca6c48c2f) | Aug 09, 2023 |
| HP            | 8433 11                     | Desktop     | [eac08c7b54](https://linux-hardware.org/?probe=eac08c7b54) | Aug 09, 2023 |
| Dell          | 0272WF A00                  | Server      | [39abbc5ab8](https://linux-hardware.org/?probe=39abbc5ab8) | Aug 09, 2023 |
| Lenovo        | SDK0E50510 WIN 262508147... | Desktop     | [badd1c22ff](https://linux-hardware.org/?probe=badd1c22ff) | Aug 09, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [fdbe025351](https://linux-hardware.org/?probe=fdbe025351) | Aug 09, 2023 |
| Lenovo        | SDK0E50510 WIN 262508147... | Desktop     | [f74262edcd](https://linux-hardware.org/?probe=f74262edcd) | Aug 09, 2023 |
| ASUSTek       | K75VJ                       | Notebook    | [7d1e95601c](https://linux-hardware.org/?probe=7d1e95601c) | Aug 09, 2023 |
| HP            | EliteBook 845 G9            | Notebook    | [1ff8d81e4e](https://linux-hardware.org/?probe=1ff8d81e4e) | Aug 09, 2023 |
| Dell          | Precision 7740              | Notebook    | [954d8472e5](https://linux-hardware.org/?probe=954d8472e5) | Aug 09, 2023 |
| Dell          | 0DT021 A00                  | Server      | [f472313f3a](https://linux-hardware.org/?probe=f472313f3a) | Aug 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [88c76f027a](https://linux-hardware.org/?probe=88c76f027a) | Aug 08, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [3fea8d650e](https://linux-hardware.org/?probe=3fea8d650e) | Aug 08, 2023 |
| AZW           | MINI S 10                   | Desktop     | [1de6b9a754](https://linux-hardware.org/?probe=1de6b9a754) | Aug 08, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [2fa2ae29cc](https://linux-hardware.org/?probe=2fa2ae29cc) | Aug 07, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [bb99f6f69e](https://linux-hardware.org/?probe=bb99f6f69e) | Aug 07, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [35e4fef6c6](https://linux-hardware.org/?probe=35e4fef6c6) | Aug 07, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [f4beee823e](https://linux-hardware.org/?probe=f4beee823e) | Aug 07, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [37bf6e8191](https://linux-hardware.org/?probe=37bf6e8191) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [b1d5aab527](https://linux-hardware.org/?probe=b1d5aab527) | Aug 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7637f0d91d](https://linux-hardware.org/?probe=7637f0d91d) | Aug 06, 2023 |
| HP            | 2B4B                        | Desktop     | [f85fada33f](https://linux-hardware.org/?probe=f85fada33f) | Aug 06, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [ee882ba789](https://linux-hardware.org/?probe=ee882ba789) | Aug 06, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ea4d9240fb](https://linux-hardware.org/?probe=ea4d9240fb) | Aug 05, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [f8f4442b09](https://linux-hardware.org/?probe=f8f4442b09) | Aug 05, 2023 |
| ASUSTek       | Z97-PRO/USB                 | Desktop     | [edd74878c3](https://linux-hardware.org/?probe=edd74878c3) | Aug 05, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [297a14921c](https://linux-hardware.org/?probe=297a14921c) | Aug 04, 2023 |
| HP            | 470 G7 Notebook PC          | Notebook    | [7e4a9b4618](https://linux-hardware.org/?probe=7e4a9b4618) | Aug 04, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [420353bf79](https://linux-hardware.org/?probe=420353bf79) | Aug 04, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [a9072f3117](https://linux-hardware.org/?probe=a9072f3117) | Aug 04, 2023 |
| Dell          | 0DT021 A00                  | Server      | [354c40df4e](https://linux-hardware.org/?probe=354c40df4e) | Aug 04, 2023 |
| MSI           | H81M-E35 V2                 | Desktop     | [2e72dc6560](https://linux-hardware.org/?probe=2e72dc6560) | Aug 04, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [fe0a1dbc45](https://linux-hardware.org/?probe=fe0a1dbc45) | Aug 04, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [90aecb9ada](https://linux-hardware.org/?probe=90aecb9ada) | Aug 04, 2023 |
| Dell          | 0W13NR A06                  | Server      | [b1820a9229](https://linux-hardware.org/?probe=b1820a9229) | Aug 04, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b2004d5d59](https://linux-hardware.org/?probe=b2004d5d59) | Aug 04, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [46e96687a1](https://linux-hardware.org/?probe=46e96687a1) | Aug 04, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [1318f4d842](https://linux-hardware.org/?probe=1318f4d842) | Aug 03, 2023 |
| Dell          | 082WXT A03                  | Desktop     | [27a50c4491](https://linux-hardware.org/?probe=27a50c4491) | Aug 03, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [573e7f6ad0](https://linux-hardware.org/?probe=573e7f6ad0) | Aug 03, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e5649696d0](https://linux-hardware.org/?probe=e5649696d0) | Aug 03, 2023 |
| MSI           | X370 GAMING PRO             | Desktop     | [b684b97e44](https://linux-hardware.org/?probe=b684b97e44) | Aug 02, 2023 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [aa4285c237](https://linux-hardware.org/?probe=aa4285c237) | Aug 02, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [8fb651def8](https://linux-hardware.org/?probe=8fb651def8) | Aug 02, 2023 |
| Toshiba       | QOSMIO X775                 | Notebook    | [6a4cd21dbf](https://linux-hardware.org/?probe=6a4cd21dbf) | Aug 02, 2023 |
| Toshiba       | QOSMIO X775                 | Notebook    | [982148fe9c](https://linux-hardware.org/?probe=982148fe9c) | Aug 02, 2023 |
| Schenker      | XMG FOCUS (Mid 2021)        | Notebook    | [d7fa14789f](https://linux-hardware.org/?probe=d7fa14789f) | Aug 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [bc84705e8f](https://linux-hardware.org/?probe=bc84705e8f) | Aug 01, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [89bc7e5c48](https://linux-hardware.org/?probe=89bc7e5c48) | Aug 01, 2023 |
| Lenovo        | ThinkPad P1 20MD001VUS      | Notebook    | [f353e39414](https://linux-hardware.org/?probe=f353e39414) | Jul 31, 2023 |
| Lenovo        | ThinkPad T560 20FH001TUS    | Notebook    | [8cb9cf099a](https://linux-hardware.org/?probe=8cb9cf099a) | Jul 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [940a0b000a](https://linux-hardware.org/?probe=940a0b000a) | Jul 31, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [356dae8360](https://linux-hardware.org/?probe=356dae8360) | Jul 30, 2023 |
| Lenovo        | ThinkPad T440p 20AN009FG... | Notebook    | [f2cc6379cc](https://linux-hardware.org/?probe=f2cc6379cc) | Jul 30, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9d93bef2df](https://linux-hardware.org/?probe=9d93bef2df) | Jul 30, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | Notebook    | [24c271e6fd](https://linux-hardware.org/?probe=24c271e6fd) | Jul 30, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | Notebook    | [bb2245d195](https://linux-hardware.org/?probe=bb2245d195) | Jul 30, 2023 |
| Dell          | 0272WF A00                  | Server      | [ab789b12e1](https://linux-hardware.org/?probe=ab789b12e1) | Jul 30, 2023 |
| Biostar       | A320MH                      | Desktop     | [8fbc21fb3e](https://linux-hardware.org/?probe=8fbc21fb3e) | Jul 29, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [c098429c68](https://linux-hardware.org/?probe=c098429c68) | Jul 29, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [7d5b443b84](https://linux-hardware.org/?probe=7d5b443b84) | Jul 29, 2023 |
| Dell          | 0272WF A00                  | Server      | [2867ef6d1f](https://linux-hardware.org/?probe=2867ef6d1f) | Jul 29, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [3a81b2b0d9](https://linux-hardware.org/?probe=3a81b2b0d9) | Jul 29, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [4d6a620df3](https://linux-hardware.org/?probe=4d6a620df3) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [cd83e4a73a](https://linux-hardware.org/?probe=cd83e4a73a) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [56918c8bad](https://linux-hardware.org/?probe=56918c8bad) | Jul 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [07feda799a](https://linux-hardware.org/?probe=07feda799a) | Jul 28, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [270ce3344c](https://linux-hardware.org/?probe=270ce3344c) | Jul 28, 2023 |
| HP            | 250 G3                      | Notebook    | [49b5a143cf](https://linux-hardware.org/?probe=49b5a143cf) | Jul 28, 2023 |
| Sony          | Unknown                     | Notebook    | [80613731cb](https://linux-hardware.org/?probe=80613731cb) | Jul 28, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [ba47e8e20f](https://linux-hardware.org/?probe=ba47e8e20f) | Jul 27, 2023 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [7e89496549](https://linux-hardware.org/?probe=7e89496549) | Jul 27, 2023 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [3652a64ac1](https://linux-hardware.org/?probe=3652a64ac1) | Jul 27, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [6799c4be4a](https://linux-hardware.org/?probe=6799c4be4a) | Jul 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [75dec2a4a4](https://linux-hardware.org/?probe=75dec2a4a4) | Jul 27, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a0a79ddb19](https://linux-hardware.org/?probe=a0a79ddb19) | Jul 27, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | Notebook    | [af1671633e](https://linux-hardware.org/?probe=af1671633e) | Jul 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ed591a913a](https://linux-hardware.org/?probe=ed591a913a) | Jul 26, 2023 |
| Lenovo        | ThinkPad T560 20FH001TUS    | Notebook    | [0cb1602cad](https://linux-hardware.org/?probe=0cb1602cad) | Jul 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [9d891afae0](https://linux-hardware.org/?probe=9d891afae0) | Jul 26, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [10db13c772](https://linux-hardware.org/?probe=10db13c772) | Jul 26, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [1568ba2843](https://linux-hardware.org/?probe=1568ba2843) | Jul 25, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [d23913a471](https://linux-hardware.org/?probe=d23913a471) | Jul 25, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [5300c80b7e](https://linux-hardware.org/?probe=5300c80b7e) | Jul 24, 2023 |
| Lenovo        | ThinkPad T560 20FH001TUS    | Notebook    | [533c44b02e](https://linux-hardware.org/?probe=533c44b02e) | Jul 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d3ba6058c7](https://linux-hardware.org/?probe=d3ba6058c7) | Jul 24, 2023 |
| HP            | 1589                        | Desktop     | [5c0bd1ec07](https://linux-hardware.org/?probe=5c0bd1ec07) | Jul 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [fd2add1e0f](https://linux-hardware.org/?probe=fd2add1e0f) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [b7c7b058b7](https://linux-hardware.org/?probe=b7c7b058b7) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [edf7b092ec](https://linux-hardware.org/?probe=edf7b092ec) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [421c2ff6b0](https://linux-hardware.org/?probe=421c2ff6b0) | Jul 23, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [405387be09](https://linux-hardware.org/?probe=405387be09) | Jul 23, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [447b84f067](https://linux-hardware.org/?probe=447b84f067) | Jul 23, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f0dcdf797e](https://linux-hardware.org/?probe=f0dcdf797e) | Jul 23, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [49fc9fb8ce](https://linux-hardware.org/?probe=49fc9fb8ce) | Jul 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [c741f10f18](https://linux-hardware.org/?probe=c741f10f18) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [83df4e51e4](https://linux-hardware.org/?probe=83df4e51e4) | Jul 22, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [47cf8f41db](https://linux-hardware.org/?probe=47cf8f41db) | Jul 22, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [01f822dec1](https://linux-hardware.org/?probe=01f822dec1) | Jul 22, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cda75b5e7a](https://linux-hardware.org/?probe=cda75b5e7a) | Jul 22, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [b00e97471c](https://linux-hardware.org/?probe=b00e97471c) | Jul 22, 2023 |
| Medion        | E6224                       | Notebook    | [c33b8a1fb1](https://linux-hardware.org/?probe=c33b8a1fb1) | Jul 22, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [4c5a8d18b9](https://linux-hardware.org/?probe=4c5a8d18b9) | Jul 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [2c2c4bdcf2](https://linux-hardware.org/?probe=2c2c4bdcf2) | Jul 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8d58cb5fb](https://linux-hardware.org/?probe=d8d58cb5fb) | Jul 21, 2023 |
| MSI           | GL72 6QF                    | Notebook    | [0484bc209c](https://linux-hardware.org/?probe=0484bc209c) | Jul 21, 2023 |
| Razer         | Blade 15 Base Model (Mid... | Notebook    | [d2d53e7406](https://linux-hardware.org/?probe=d2d53e7406) | Jul 21, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [7b6300dfc7](https://linux-hardware.org/?probe=7b6300dfc7) | Jul 20, 2023 |
| Sony          | Unknown                     | Notebook    | [427e52d6a6](https://linux-hardware.org/?probe=427e52d6a6) | Jul 20, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [65da6837ae](https://linux-hardware.org/?probe=65da6837ae) | Jul 20, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [a2779c6ac8](https://linux-hardware.org/?probe=a2779c6ac8) | Jul 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [158ce24cd5](https://linux-hardware.org/?probe=158ce24cd5) | Jul 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2f067394f6](https://linux-hardware.org/?probe=2f067394f6) | Jul 19, 2023 |
| Acer          | MCP7A                       | Desktop     | [06afe36113](https://linux-hardware.org/?probe=06afe36113) | Jul 18, 2023 |
| Dell          | XPS L501X                   | Notebook    | [0879ff6b9d](https://linux-hardware.org/?probe=0879ff6b9d) | Jul 18, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [af9244e836](https://linux-hardware.org/?probe=af9244e836) | Jul 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [b48286d288](https://linux-hardware.org/?probe=b48286d288) | Jul 18, 2023 |
| Lenovo        | ThinkPad E480 20KN005CRT    | Notebook    | [722170f1f3](https://linux-hardware.org/?probe=722170f1f3) | Jul 17, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [0236d26da7](https://linux-hardware.org/?probe=0236d26da7) | Jul 17, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [fe065234a9](https://linux-hardware.org/?probe=fe065234a9) | Jul 17, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [295bc58365](https://linux-hardware.org/?probe=295bc58365) | Jul 17, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [7ca76c0d32](https://linux-hardware.org/?probe=7ca76c0d32) | Jul 17, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [52d550e878](https://linux-hardware.org/?probe=52d550e878) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [4c3185f447](https://linux-hardware.org/?probe=4c3185f447) | Jul 17, 2023 |
| Medion        | E6224                       | Notebook    | [4ffae87044](https://linux-hardware.org/?probe=4ffae87044) | Jul 17, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [81db5657d9](https://linux-hardware.org/?probe=81db5657d9) | Jul 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [553bd7c29e](https://linux-hardware.org/?probe=553bd7c29e) | Jul 16, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [fd05b31515](https://linux-hardware.org/?probe=fd05b31515) | Jul 16, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [d9270dc2df](https://linux-hardware.org/?probe=d9270dc2df) | Jul 16, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [7108435241](https://linux-hardware.org/?probe=7108435241) | Jul 15, 2023 |
| Irbis         | NB131                       | Convertible | [c7efdcc615](https://linux-hardware.org/?probe=c7efdcc615) | Jul 15, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [01b8ada2a7](https://linux-hardware.org/?probe=01b8ada2a7) | Jul 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6b351b341e](https://linux-hardware.org/?probe=6b351b341e) | Jul 15, 2023 |
| Irbis         | NB131                       | Convertible | [b14dbb093f](https://linux-hardware.org/?probe=b14dbb093f) | Jul 15, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [d1aa3f2d70](https://linux-hardware.org/?probe=d1aa3f2d70) | Jul 15, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [1917d24a87](https://linux-hardware.org/?probe=1917d24a87) | Jul 15, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [34871aac58](https://linux-hardware.org/?probe=34871aac58) | Jul 15, 2023 |
| Alienware     | m17 R5 AMD                  | Notebook    | [a2bb315c61](https://linux-hardware.org/?probe=a2bb315c61) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 2394W19       | Notebook    | [874f8b41a7](https://linux-hardware.org/?probe=874f8b41a7) | Jul 14, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [78f620581b](https://linux-hardware.org/?probe=78f620581b) | Jul 14, 2023 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [9760be79b1](https://linux-hardware.org/?probe=9760be79b1) | Jul 13, 2023 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [542d77f366](https://linux-hardware.org/?probe=542d77f366) | Jul 13, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [9bee6805c0](https://linux-hardware.org/?probe=9bee6805c0) | Jul 13, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [35373c9acf](https://linux-hardware.org/?probe=35373c9acf) | Jul 13, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [9b03d78d55](https://linux-hardware.org/?probe=9b03d78d55) | Jul 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [e56a404324](https://linux-hardware.org/?probe=e56a404324) | Jul 13, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [480fe73577](https://linux-hardware.org/?probe=480fe73577) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [bc78a01502](https://linux-hardware.org/?probe=bc78a01502) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [c01febb128](https://linux-hardware.org/?probe=c01febb128) | Jul 12, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [1c7a630efb](https://linux-hardware.org/?probe=1c7a630efb) | Jul 12, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [458df6678a](https://linux-hardware.org/?probe=458df6678a) | Jul 12, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [93d94feca6](https://linux-hardware.org/?probe=93d94feca6) | Jul 11, 2023 |
| ASUSTek       | K53SM                       | Notebook    | [7aac135bc0](https://linux-hardware.org/?probe=7aac135bc0) | Jul 11, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [becf9726c7](https://linux-hardware.org/?probe=becf9726c7) | Jul 11, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [90f5732595](https://linux-hardware.org/?probe=90f5732595) | Jul 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [a52e535dcb](https://linux-hardware.org/?probe=a52e535dcb) | Jul 11, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [e9a45b4e27](https://linux-hardware.org/?probe=e9a45b4e27) | Jul 11, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [1a540134de](https://linux-hardware.org/?probe=1a540134de) | Jul 11, 2023 |
| Dell          | Latitude E5410              | Notebook    | [8d980136c2](https://linux-hardware.org/?probe=8d980136c2) | Jul 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [8c2add9768](https://linux-hardware.org/?probe=8c2add9768) | Jul 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [2cc9f44232](https://linux-hardware.org/?probe=2cc9f44232) | Jul 10, 2023 |
| Medion        | Akoya P2214T                | Notebook    | [341fc04e6c](https://linux-hardware.org/?probe=341fc04e6c) | Jul 10, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [9f920e8a7e](https://linux-hardware.org/?probe=9f920e8a7e) | Jul 10, 2023 |
| HP            | Notebook                    | Notebook    | [a1c37a6a4b](https://linux-hardware.org/?probe=a1c37a6a4b) | Jul 09, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [36b6c49552](https://linux-hardware.org/?probe=36b6c49552) | Jul 09, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [6d96bf0f5b](https://linux-hardware.org/?probe=6d96bf0f5b) | Jul 09, 2023 |
| Lenovo        | Unknown                     | Convertible | [7c4ddbebf7](https://linux-hardware.org/?probe=7c4ddbebf7) | Jul 09, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [ffa5984711](https://linux-hardware.org/?probe=ffa5984711) | Jul 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [5d91f63280](https://linux-hardware.org/?probe=5d91f63280) | Jul 09, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [c00debe968](https://linux-hardware.org/?probe=c00debe968) | Jul 08, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [a72d3eff75](https://linux-hardware.org/?probe=a72d3eff75) | Jul 08, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [8a5cbee239](https://linux-hardware.org/?probe=8a5cbee239) | Jul 08, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [9fc07d1102](https://linux-hardware.org/?probe=9fc07d1102) | Jul 08, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [f94c183910](https://linux-hardware.org/?probe=f94c183910) | Jul 08, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [dde4874147](https://linux-hardware.org/?probe=dde4874147) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7cbaa33271](https://linux-hardware.org/?probe=7cbaa33271) | Jul 07, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [bb2f259ef6](https://linux-hardware.org/?probe=bb2f259ef6) | Jul 07, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [f32ffc678f](https://linux-hardware.org/?probe=f32ffc678f) | Jul 07, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [54262c3aeb](https://linux-hardware.org/?probe=54262c3aeb) | Jul 07, 2023 |
| Lenovo        | 20RD001FHV                  | Notebook    | [79166ca12f](https://linux-hardware.org/?probe=79166ca12f) | Jul 07, 2023 |
| Medion        | Akoya P2214T                | Notebook    | [e2c31b421a](https://linux-hardware.org/?probe=e2c31b421a) | Jul 07, 2023 |
| Lenovo        | 20RD001FHV                  | Notebook    | [de3ed49995](https://linux-hardware.org/?probe=de3ed49995) | Jul 07, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [5ee0aa7d94](https://linux-hardware.org/?probe=5ee0aa7d94) | Jul 07, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [0d98ce8578](https://linux-hardware.org/?probe=0d98ce8578) | Jul 07, 2023 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [f459621198](https://linux-hardware.org/?probe=f459621198) | Jul 06, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [f156a2bbfa](https://linux-hardware.org/?probe=f156a2bbfa) | Jul 06, 2023 |
| HP            | 8B3B A                      | Desktop     | [b003988978](https://linux-hardware.org/?probe=b003988978) | Jul 05, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [b3530f3e0e](https://linux-hardware.org/?probe=b3530f3e0e) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | Desktop     | [7592c0cc37](https://linux-hardware.org/?probe=7592c0cc37) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | Desktop     | [71505f347f](https://linux-hardware.org/?probe=71505f347f) | Jul 05, 2023 |
| Acer          | Swift SF114-33              | Notebook    | [e3bd5bf60f](https://linux-hardware.org/?probe=e3bd5bf60f) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [40b7950cb2](https://linux-hardware.org/?probe=40b7950cb2) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [73435e5646](https://linux-hardware.org/?probe=73435e5646) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [eef5ee5c9a](https://linux-hardware.org/?probe=eef5ee5c9a) | Jul 05, 2023 |
| Teclast       | X4                          | Tablet      | [6aab5b6610](https://linux-hardware.org/?probe=6aab5b6610) | Jul 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [6b1beb7eeb](https://linux-hardware.org/?probe=6b1beb7eeb) | Jul 05, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [427fc931a0](https://linux-hardware.org/?probe=427fc931a0) | Jul 04, 2023 |
| Gigabyte      | Z690 AERO D                 | Desktop     | [f42140d294](https://linux-hardware.org/?probe=f42140d294) | Jul 03, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [9561990119](https://linux-hardware.org/?probe=9561990119) | Jul 03, 2023 |
| Dell          | Latitude E6510              | Notebook    | [bc2c3c520a](https://linux-hardware.org/?probe=bc2c3c520a) | Jul 02, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f91dbee23b](https://linux-hardware.org/?probe=f91dbee23b) | Jul 02, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [57f5458dfa](https://linux-hardware.org/?probe=57f5458dfa) | Jul 02, 2023 |
| ASUSTek       | P5E Deluxe                  | Desktop     | [895759fa79](https://linux-hardware.org/?probe=895759fa79) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [27c53e1152](https://linux-hardware.org/?probe=27c53e1152) | Jul 01, 2023 |
| Lenovo        | ThinkPad T530 2394W19       | Notebook    | [a1fc2e0020](https://linux-hardware.org/?probe=a1fc2e0020) | Jul 01, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [3702fd669f](https://linux-hardware.org/?probe=3702fd669f) | Jul 01, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [10dc1c07c8](https://linux-hardware.org/?probe=10dc1c07c8) | Jul 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d9b6645cae](https://linux-hardware.org/?probe=d9b6645cae) | Jul 01, 2023 |
| HP            | ProBook 455 G6              | Notebook    | [f4b853f43e](https://linux-hardware.org/?probe=f4b853f43e) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| Gigabyte      | P67A-UD5-B3                 | Desktop     | [b763c860fa](https://linux-hardware.org/?probe=b763c860fa) | Jun 30, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [5e11bea093](https://linux-hardware.org/?probe=5e11bea093) | Jun 30, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [ef3b3cf51e](https://linux-hardware.org/?probe=ef3b3cf51e) | Jun 30, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [70ddebe460](https://linux-hardware.org/?probe=70ddebe460) | Jun 30, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [7ae106bfd6](https://linux-hardware.org/?probe=7ae106bfd6) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [70ce1e280f](https://linux-hardware.org/?probe=70ce1e280f) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [b5e0044759](https://linux-hardware.org/?probe=b5e0044759) | Jun 30, 2023 |
| HP            | 8055                        | Desktop     | [47536e2cde](https://linux-hardware.org/?probe=47536e2cde) | Jun 29, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [64e81a22a5](https://linux-hardware.org/?probe=64e81a22a5) | Jun 29, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6c7621fe04](https://linux-hardware.org/?probe=6c7621fe04) | Jun 29, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [6cc649e9ba](https://linux-hardware.org/?probe=6cc649e9ba) | Jun 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2dd6be0ddc](https://linux-hardware.org/?probe=2dd6be0ddc) | Jun 29, 2023 |
| Lenovo        | ThinkPad X200 7458AH8       | Notebook    | [a81af2d7e2](https://linux-hardware.org/?probe=a81af2d7e2) | Jun 29, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [9d4c4f5506](https://linux-hardware.org/?probe=9d4c4f5506) | Jun 29, 2023 |
| HP            | 1589                        | Desktop     | [dcb3289360](https://linux-hardware.org/?probe=dcb3289360) | Jun 29, 2023 |
| Dell          | 00X7CK A04                  | Server      | [c59e7b7f26](https://linux-hardware.org/?probe=c59e7b7f26) | Jun 28, 2023 |
| Intel         | DG965SS AAD41678-304        | Desktop     | [696cd9ce01](https://linux-hardware.org/?probe=696cd9ce01) | Jun 28, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1ef1762ac3](https://linux-hardware.org/?probe=1ef1762ac3) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6a29eda577](https://linux-hardware.org/?probe=6a29eda577) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bf4abd6e9e](https://linux-hardware.org/?probe=bf4abd6e9e) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [3ea9e41d03](https://linux-hardware.org/?probe=3ea9e41d03) | Jun 28, 2023 |
| Gigabyte      | EG45M-DS2H                  | Desktop     | [b9b25df5a3](https://linux-hardware.org/?probe=b9b25df5a3) | Jun 27, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [465cc8968f](https://linux-hardware.org/?probe=465cc8968f) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [fce3ec0379](https://linux-hardware.org/?probe=fce3ec0379) | Jun 27, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [731b4a6479](https://linux-hardware.org/?probe=731b4a6479) | Jun 26, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [97b1fc630a](https://linux-hardware.org/?probe=97b1fc630a) | Jun 25, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a8c0f33ffe](https://linux-hardware.org/?probe=a8c0f33ffe) | Jun 25, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [32ab15a1eb](https://linux-hardware.org/?probe=32ab15a1eb) | Jun 25, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [1fe3acdf83](https://linux-hardware.org/?probe=1fe3acdf83) | Jun 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [17c221fa68](https://linux-hardware.org/?probe=17c221fa68) | Jun 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6c015f633b](https://linux-hardware.org/?probe=6c015f633b) | Jun 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [31d19c3462](https://linux-hardware.org/?probe=31d19c3462) | Jun 24, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [71f17d4d74](https://linux-hardware.org/?probe=71f17d4d74) | Jun 24, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | Notebook    | [ebfe7d469a](https://linux-hardware.org/?probe=ebfe7d469a) | Jun 24, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [905653d393](https://linux-hardware.org/?probe=905653d393) | Jun 24, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [68b591e6d8](https://linux-hardware.org/?probe=68b591e6d8) | Jun 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [1d6a241c9e](https://linux-hardware.org/?probe=1d6a241c9e) | Jun 23, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [fed92425f3](https://linux-hardware.org/?probe=fed92425f3) | Jun 23, 2023 |
| HP            | 8055                        | Desktop     | [21f11f538d](https://linux-hardware.org/?probe=21f11f538d) | Jun 23, 2023 |
| HP            | 8055                        | Desktop     | [54e0de7a72](https://linux-hardware.org/?probe=54e0de7a72) | Jun 23, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [761a478742](https://linux-hardware.org/?probe=761a478742) | Jun 22, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [55873c7a70](https://linux-hardware.org/?probe=55873c7a70) | Jun 21, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5fbfa89321](https://linux-hardware.org/?probe=5fbfa89321) | Jun 21, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [86ee4e619f](https://linux-hardware.org/?probe=86ee4e619f) | Jun 21, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5cbbd51d7f](https://linux-hardware.org/?probe=5cbbd51d7f) | Jun 20, 2023 |
| Pegatron      | JESSE                       | Desktop     | [fa09a247a7](https://linux-hardware.org/?probe=fa09a247a7) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [405e91f460](https://linux-hardware.org/?probe=405e91f460) | Jun 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [e3ded6b5e4](https://linux-hardware.org/?probe=e3ded6b5e4) | Jun 19, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1f1209bd20](https://linux-hardware.org/?probe=1f1209bd20) | Jun 19, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [733af664a4](https://linux-hardware.org/?probe=733af664a4) | Jun 18, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [7412881615](https://linux-hardware.org/?probe=7412881615) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [34610e62fe](https://linux-hardware.org/?probe=34610e62fe) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [bd4abe1a68](https://linux-hardware.org/?probe=bd4abe1a68) | Jun 18, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6ff9be62b8](https://linux-hardware.org/?probe=6ff9be62b8) | Jun 18, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7c7742bf5a](https://linux-hardware.org/?probe=7c7742bf5a) | Jun 18, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [bbb32d23be](https://linux-hardware.org/?probe=bbb32d23be) | Jun 17, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [23b64edd39](https://linux-hardware.org/?probe=23b64edd39) | Jun 17, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [269309f364](https://linux-hardware.org/?probe=269309f364) | Jun 16, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [da0a4b3bf0](https://linux-hardware.org/?probe=da0a4b3bf0) | Jun 16, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | Notebook    | [0210669ff3](https://linux-hardware.org/?probe=0210669ff3) | Jun 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [940ab1af2a](https://linux-hardware.org/?probe=940ab1af2a) | Jun 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [4d81fc8320](https://linux-hardware.org/?probe=4d81fc8320) | Jun 15, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [df63208f37](https://linux-hardware.org/?probe=df63208f37) | Jun 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [f802893b92](https://linux-hardware.org/?probe=f802893b92) | Jun 15, 2023 |
| HP            | 3397                        | Desktop     | [e67824996f](https://linux-hardware.org/?probe=e67824996f) | Jun 14, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [cb6681d609](https://linux-hardware.org/?probe=cb6681d609) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [9b67ef406b](https://linux-hardware.org/?probe=9b67ef406b) | Jun 14, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [b972bb9890](https://linux-hardware.org/?probe=b972bb9890) | Jun 14, 2023 |
| Gigabyte      | AORUS 17X AXF               | Notebook    | [3715cf9513](https://linux-hardware.org/?probe=3715cf9513) | Jun 14, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [1cddf187c5](https://linux-hardware.org/?probe=1cddf187c5) | Jun 13, 2023 |
| MSI           | P67A-C45                    | Desktop     | [4f3aa2017f](https://linux-hardware.org/?probe=4f3aa2017f) | Jun 13, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [fdc4101cba](https://linux-hardware.org/?probe=fdc4101cba) | Jun 13, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [f4f10ca549](https://linux-hardware.org/?probe=f4f10ca549) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3f3cbfd7fe](https://linux-hardware.org/?probe=3f3cbfd7fe) | Jun 12, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | Desktop     | [ed8bd3839f](https://linux-hardware.org/?probe=ed8bd3839f) | Jun 12, 2023 |
| HP            | 18E4                        | Desktop     | [a0d8b92e3a](https://linux-hardware.org/?probe=a0d8b92e3a) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5f4978fc61](https://linux-hardware.org/?probe=5f4978fc61) | Jun 12, 2023 |
| HP            | 2B16                        | Desktop     | [0f2ea937e9](https://linux-hardware.org/?probe=0f2ea937e9) | Jun 12, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [effdc6a5a3](https://linux-hardware.org/?probe=effdc6a5a3) | Jun 12, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [7221d4851c](https://linux-hardware.org/?probe=7221d4851c) | Jun 11, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [008148f553](https://linux-hardware.org/?probe=008148f553) | Jun 11, 2023 |
| HP            | 158A                        | Desktop     | [ce5c3c88d4](https://linux-hardware.org/?probe=ce5c3c88d4) | Jun 11, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [75285a62bd](https://linux-hardware.org/?probe=75285a62bd) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [74e0ea4d38](https://linux-hardware.org/?probe=74e0ea4d38) | Jun 11, 2023 |
| Lenovo        | ThinkPad T450 20BU000BIX    | Notebook    | [d82c175e3e](https://linux-hardware.org/?probe=d82c175e3e) | Jun 10, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [c8e822d0d7](https://linux-hardware.org/?probe=c8e822d0d7) | Jun 10, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| HP            | 2B4B                        | Desktop     | [3ade78a07e](https://linux-hardware.org/?probe=3ade78a07e) | Jun 10, 2023 |
| HP            | 2B4B                        | Desktop     | [2da60252b5](https://linux-hardware.org/?probe=2da60252b5) | Jun 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [758afab931](https://linux-hardware.org/?probe=758afab931) | Jun 10, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d9e9a51e48](https://linux-hardware.org/?probe=d9e9a51e48) | Jun 10, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [5648ca2620](https://linux-hardware.org/?probe=5648ca2620) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [30dbebd931](https://linux-hardware.org/?probe=30dbebd931) | Jun 09, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [77145a587d](https://linux-hardware.org/?probe=77145a587d) | Jun 09, 2023 |
| Gigabyte      | AORUS 17X AXF               | Notebook    | [685ba556b4](https://linux-hardware.org/?probe=685ba556b4) | Jun 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [797dea9c96](https://linux-hardware.org/?probe=797dea9c96) | Jun 09, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1bae25f67b](https://linux-hardware.org/?probe=1bae25f67b) | Jun 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [cc1f571000](https://linux-hardware.org/?probe=cc1f571000) | Jun 09, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [6d989f49b6](https://linux-hardware.org/?probe=6d989f49b6) | Jun 09, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | Desktop     | [9fb55abc56](https://linux-hardware.org/?probe=9fb55abc56) | Jun 08, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [e68e693394](https://linux-hardware.org/?probe=e68e693394) | Jun 08, 2023 |
| Dell          | Precision 5540              | Notebook    | [0e925c8b3c](https://linux-hardware.org/?probe=0e925c8b3c) | Jun 08, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [ad5baed526](https://linux-hardware.org/?probe=ad5baed526) | Jun 08, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [a2c63b86b0](https://linux-hardware.org/?probe=a2c63b86b0) | Jun 08, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | Desktop     | [d5d7ffe9df](https://linux-hardware.org/?probe=d5d7ffe9df) | Jun 08, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [f6fddfcd65](https://linux-hardware.org/?probe=f6fddfcd65) | Jun 07, 2023 |
| MSI           | P67A-C45                    | Desktop     | [673f3774bc](https://linux-hardware.org/?probe=673f3774bc) | Jun 07, 2023 |
| MSI           | CreatorPro X17 A12UKS       | Notebook    | [ee827c186c](https://linux-hardware.org/?probe=ee827c186c) | Jun 07, 2023 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [1d36e85f27](https://linux-hardware.org/?probe=1d36e85f27) | Jun 07, 2023 |
| Gigabyte      | AORUS 17X AXF               | Notebook    | [87bd8323b6](https://linux-hardware.org/?probe=87bd8323b6) | Jun 07, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e45ed702a4](https://linux-hardware.org/?probe=e45ed702a4) | Jun 07, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [47c5d7587a](https://linux-hardware.org/?probe=47c5d7587a) | Jun 06, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [5fb7d63e80](https://linux-hardware.org/?probe=5fb7d63e80) | Jun 06, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | Desktop     | [23b41d16db](https://linux-hardware.org/?probe=23b41d16db) | Jun 06, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2508cbfdd2](https://linux-hardware.org/?probe=2508cbfdd2) | Jun 06, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [3d0f46c6ed](https://linux-hardware.org/?probe=3d0f46c6ed) | Jun 06, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [acae4ee06e](https://linux-hardware.org/?probe=acae4ee06e) | Jun 06, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [8d150fb2b0](https://linux-hardware.org/?probe=8d150fb2b0) | Jun 05, 2023 |
| Sony          | VPCEH25EN                   | Notebook    | [2b47c1b9a5](https://linux-hardware.org/?probe=2b47c1b9a5) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [b4f165f28d](https://linux-hardware.org/?probe=b4f165f28d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [e0ce9df73c](https://linux-hardware.org/?probe=e0ce9df73c) | Jun 05, 2023 |
| Acer          | Aspire 3820                 | Notebook    | [edbf91844a](https://linux-hardware.org/?probe=edbf91844a) | Jun 04, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8e0a13cdd1](https://linux-hardware.org/?probe=8e0a13cdd1) | Jun 04, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [4d82d8bf8b](https://linux-hardware.org/?probe=4d82d8bf8b) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [cdbebd8a7e](https://linux-hardware.org/?probe=cdbebd8a7e) | Jun 04, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [a8baa03316](https://linux-hardware.org/?probe=a8baa03316) | Jun 03, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [25ffe9ad37](https://linux-hardware.org/?probe=25ffe9ad37) | Jun 03, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [76cd01b045](https://linux-hardware.org/?probe=76cd01b045) | Jun 03, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [75ba9fba2f](https://linux-hardware.org/?probe=75ba9fba2f) | Jun 03, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [e91c644324](https://linux-hardware.org/?probe=e91c644324) | Jun 02, 2023 |
| Dell          | G15 5520                    | Notebook    | [5880c98c54](https://linux-hardware.org/?probe=5880c98c54) | Jun 02, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [ab7c62da47](https://linux-hardware.org/?probe=ab7c62da47) | Jun 02, 2023 |
| Panasonic     | CF-SX2JDHYS                 | Notebook    | [2bcfc48199](https://linux-hardware.org/?probe=2bcfc48199) | Jun 02, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [2cf19f7b32](https://linux-hardware.org/?probe=2cf19f7b32) | Jun 02, 2023 |
| Portwell      | RuggedBookJ10               | Tablet      | [828336f149](https://linux-hardware.org/?probe=828336f149) | Jun 01, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [71c2818f01](https://linux-hardware.org/?probe=71c2818f01) | Jun 01, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [976fcb80b0](https://linux-hardware.org/?probe=976fcb80b0) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [01692ad602](https://linux-hardware.org/?probe=01692ad602) | May 31, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [bb8f972443](https://linux-hardware.org/?probe=bb8f972443) | May 31, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [a313036ec2](https://linux-hardware.org/?probe=a313036ec2) | May 31, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [2881299761](https://linux-hardware.org/?probe=2881299761) | May 30, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [c75d4298dc](https://linux-hardware.org/?probe=c75d4298dc) | May 30, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [5bd3cb3a3a](https://linux-hardware.org/?probe=5bd3cb3a3a) | May 29, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [02f6d0b74b](https://linux-hardware.org/?probe=02f6d0b74b) | May 29, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [a9ff8334b4](https://linux-hardware.org/?probe=a9ff8334b4) | May 28, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [d3afe375cf](https://linux-hardware.org/?probe=d3afe375cf) | May 28, 2023 |
| ASUSTek       | Z87I-DELUXE                 | Desktop     | [5d683647ae](https://linux-hardware.org/?probe=5d683647ae) | May 28, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [a890415f0e](https://linux-hardware.org/?probe=a890415f0e) | May 28, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [4feb3e3196](https://linux-hardware.org/?probe=4feb3e3196) | May 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [0f3f548ff0](https://linux-hardware.org/?probe=0f3f548ff0) | May 27, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [eb9ee9f38e](https://linux-hardware.org/?probe=eb9ee9f38e) | May 27, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [aeb6fa2258](https://linux-hardware.org/?probe=aeb6fa2258) | May 26, 2023 |
| Dell          | Latitude 3440               | Notebook    | [1d32fe235f](https://linux-hardware.org/?probe=1d32fe235f) | May 26, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [f4de9c8a5f](https://linux-hardware.org/?probe=f4de9c8a5f) | May 26, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [1c272c65dc](https://linux-hardware.org/?probe=1c272c65dc) | May 26, 2023 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [5b0dffc2c3](https://linux-hardware.org/?probe=5b0dffc2c3) | May 26, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [c8c9f63237](https://linux-hardware.org/?probe=c8c9f63237) | May 25, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [e0920f015d](https://linux-hardware.org/?probe=e0920f015d) | May 25, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [f3e564d17d](https://linux-hardware.org/?probe=f3e564d17d) | May 25, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [776f5c2411](https://linux-hardware.org/?probe=776f5c2411) | May 25, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [e2110ab5da](https://linux-hardware.org/?probe=e2110ab5da) | May 25, 2023 |
| ASRock        | 890GX Extreme3              | Desktop     | [016f2a8ada](https://linux-hardware.org/?probe=016f2a8ada) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [61b85cdced](https://linux-hardware.org/?probe=61b85cdced) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [b167237d46](https://linux-hardware.org/?probe=b167237d46) | May 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [585b85e476](https://linux-hardware.org/?probe=585b85e476) | May 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ca5f5ee7bf](https://linux-hardware.org/?probe=ca5f5ee7bf) | May 23, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [f133543500](https://linux-hardware.org/?probe=f133543500) | May 23, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [56fba05f01](https://linux-hardware.org/?probe=56fba05f01) | May 22, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [926421c6be](https://linux-hardware.org/?probe=926421c6be) | May 22, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [c903e06758](https://linux-hardware.org/?probe=c903e06758) | May 22, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [8b4b66a085](https://linux-hardware.org/?probe=8b4b66a085) | May 22, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [93074475ac](https://linux-hardware.org/?probe=93074475ac) | May 22, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [b34371b4ba](https://linux-hardware.org/?probe=b34371b4ba) | May 21, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [3fb6e257a6](https://linux-hardware.org/?probe=3fb6e257a6) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [87bf7a95c8](https://linux-hardware.org/?probe=87bf7a95c8) | May 21, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [a6e8e03e74](https://linux-hardware.org/?probe=a6e8e03e74) | May 21, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a69a8746ff](https://linux-hardware.org/?probe=a69a8746ff) | May 20, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [d5213cca3c](https://linux-hardware.org/?probe=d5213cca3c) | May 20, 2023 |
| Dell          | 0F3KHR A01                  | Desktop     | [c48ab194c6](https://linux-hardware.org/?probe=c48ab194c6) | May 20, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [5352a94049](https://linux-hardware.org/?probe=5352a94049) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1f6220f21a](https://linux-hardware.org/?probe=1f6220f21a) | May 19, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [12da248164](https://linux-hardware.org/?probe=12da248164) | May 19, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c571a25585](https://linux-hardware.org/?probe=c571a25585) | May 19, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [c2f9737977](https://linux-hardware.org/?probe=c2f9737977) | May 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8EG0... | Notebook    | [0735cab104](https://linux-hardware.org/?probe=0735cab104) | May 18, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [7087600ab6](https://linux-hardware.org/?probe=7087600ab6) | May 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [ad17e04f3b](https://linux-hardware.org/?probe=ad17e04f3b) | May 17, 2023 |
| Dell          | Inspiron 7573               | Convertible | [8f57130549](https://linux-hardware.org/?probe=8f57130549) | May 17, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [74c412b40a](https://linux-hardware.org/?probe=74c412b40a) | May 16, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [8517139acb](https://linux-hardware.org/?probe=8517139acb) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [c33be8e25c](https://linux-hardware.org/?probe=c33be8e25c) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5e8463c682](https://linux-hardware.org/?probe=5e8463c682) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [093e6a63c8](https://linux-hardware.org/?probe=093e6a63c8) | May 16, 2023 |
| Dell          | Inspiron 7573               | Convertible | [6f1d226305](https://linux-hardware.org/?probe=6f1d226305) | May 16, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7d44c65f86](https://linux-hardware.org/?probe=7d44c65f86) | May 16, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [443ee2bf3a](https://linux-hardware.org/?probe=443ee2bf3a) | May 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [61499d189f](https://linux-hardware.org/?probe=61499d189f) | May 15, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a438db6a33](https://linux-hardware.org/?probe=a438db6a33) | May 15, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [1560f547ad](https://linux-hardware.org/?probe=1560f547ad) | May 14, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [2dc2bdd057](https://linux-hardware.org/?probe=2dc2bdd057) | May 14, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [6335ace28b](https://linux-hardware.org/?probe=6335ace28b) | May 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8d819952c9](https://linux-hardware.org/?probe=8d819952c9) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ab7d27081e](https://linux-hardware.org/?probe=ab7d27081e) | May 13, 2023 |
| Dell          | 0F0XJ6 A11                  | Server      | [4bc8e971f7](https://linux-hardware.org/?probe=4bc8e971f7) | May 13, 2023 |
| Dell          | 0F0XJ6 A11                  | Server      | [be75daf81a](https://linux-hardware.org/?probe=be75daf81a) | May 13, 2023 |
| HP            | 339A                        | Desktop     | [2ba14f8397](https://linux-hardware.org/?probe=2ba14f8397) | May 12, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [30bda7d8cb](https://linux-hardware.org/?probe=30bda7d8cb) | May 12, 2023 |
| Lenovo        | ThinkPad L540 20AUS01H00    | Notebook    | [d39599a293](https://linux-hardware.org/?probe=d39599a293) | May 12, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3d43aab6fd](https://linux-hardware.org/?probe=3d43aab6fd) | May 12, 2023 |
| Huanan        | B75 V10.1 376               | Desktop     | [3293d10187](https://linux-hardware.org/?probe=3293d10187) | May 12, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [99ad79383e](https://linux-hardware.org/?probe=99ad79383e) | May 11, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [17282aeeb3](https://linux-hardware.org/?probe=17282aeeb3) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [6d0f055f82](https://linux-hardware.org/?probe=6d0f055f82) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [7f90473be2](https://linux-hardware.org/?probe=7f90473be2) | May 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [165d6e12b4](https://linux-hardware.org/?probe=165d6e12b4) | May 11, 2023 |
| Lenovo        | ThinkPad T530 23926CU       | Notebook    | [4e7cab81f3](https://linux-hardware.org/?probe=4e7cab81f3) | May 11, 2023 |
| Lenovo        | ThinkPad W541 20EF001UGE    | Notebook    | [29c8170a0e](https://linux-hardware.org/?probe=29c8170a0e) | May 10, 2023 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | Desktop     | [cde6cec9c8](https://linux-hardware.org/?probe=cde6cec9c8) | May 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [49e9002825](https://linux-hardware.org/?probe=49e9002825) | May 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0a3aa24894](https://linux-hardware.org/?probe=0a3aa24894) | May 10, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [8eae6560cb](https://linux-hardware.org/?probe=8eae6560cb) | May 10, 2023 |
| Lenovo        | RD450X                      | Server      | [6fca1885fc](https://linux-hardware.org/?probe=6fca1885fc) | May 10, 2023 |
| Lenovo        | RD450X                      | Server      | [5cd314b0af](https://linux-hardware.org/?probe=5cd314b0af) | May 10, 2023 |
| Lenovo        | ThinkPad T570 20HAS0UU00    | Notebook    | [c0ad43f440](https://linux-hardware.org/?probe=c0ad43f440) | May 09, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [922a392eee](https://linux-hardware.org/?probe=922a392eee) | May 09, 2023 |
| Lenovo        | ThinkPad T570 20HAS0UU00    | Notebook    | [f3572c500c](https://linux-hardware.org/?probe=f3572c500c) | May 09, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [c74bb83ac9](https://linux-hardware.org/?probe=c74bb83ac9) | May 08, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [9430b8c328](https://linux-hardware.org/?probe=9430b8c328) | May 08, 2023 |
| Lenovo        | ThinkPad T410 2522K3U       | Notebook    | [55756e1659](https://linux-hardware.org/?probe=55756e1659) | May 07, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [2a321db63e](https://linux-hardware.org/?probe=2a321db63e) | May 07, 2023 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [eeb37c9c4f](https://linux-hardware.org/?probe=eeb37c9c4f) | May 07, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [05c9e752a5](https://linux-hardware.org/?probe=05c9e752a5) | May 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b661127bb7](https://linux-hardware.org/?probe=b661127bb7) | May 06, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [9cb4890df2](https://linux-hardware.org/?probe=9cb4890df2) | May 06, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [aaad2fda16](https://linux-hardware.org/?probe=aaad2fda16) | May 06, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [c6b9cf8729](https://linux-hardware.org/?probe=c6b9cf8729) | May 05, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [2a4b061b07](https://linux-hardware.org/?probe=2a4b061b07) | May 05, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [54417e14cf](https://linux-hardware.org/?probe=54417e14cf) | May 05, 2023 |
| HP            | 304Ah                       | Desktop     | [d9a160845c](https://linux-hardware.org/?probe=d9a160845c) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [98d7593057](https://linux-hardware.org/?probe=98d7593057) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [f9a56b49f3](https://linux-hardware.org/?probe=f9a56b49f3) | May 05, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [0d4ad3c608](https://linux-hardware.org/?probe=0d4ad3c608) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ab21408c4c](https://linux-hardware.org/?probe=ab21408c4c) | May 03, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [99870f2da6](https://linux-hardware.org/?probe=99870f2da6) | May 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [9ff86ca1f1](https://linux-hardware.org/?probe=9ff86ca1f1) | May 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e9bd630708](https://linux-hardware.org/?probe=e9bd630708) | May 01, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [82d7303d5c](https://linux-hardware.org/?probe=82d7303d5c) | May 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [0cb8947c84](https://linux-hardware.org/?probe=0cb8947c84) | Apr 30, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [9109b0a7ed](https://linux-hardware.org/?probe=9109b0a7ed) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9876205c45](https://linux-hardware.org/?probe=9876205c45) | Apr 30, 2023 |
| AMI           | INTEL                       | Convertible | [3a67944d4f](https://linux-hardware.org/?probe=3a67944d4f) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fcd7a6a42b](https://linux-hardware.org/?probe=fcd7a6a42b) | Apr 30, 2023 |
| HP            | 1998                        | Desktop     | [4ba5ef1211](https://linux-hardware.org/?probe=4ba5ef1211) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c36b7b72de](https://linux-hardware.org/?probe=c36b7b72de) | Apr 29, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [c880b8dcdd](https://linux-hardware.org/?probe=c880b8dcdd) | Apr 29, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | Notebook    | [e84690f2d5](https://linux-hardware.org/?probe=e84690f2d5) | Apr 29, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [33e30c562d](https://linux-hardware.org/?probe=33e30c562d) | Apr 29, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [0295ab04a7](https://linux-hardware.org/?probe=0295ab04a7) | Apr 28, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [a1584c31ec](https://linux-hardware.org/?probe=a1584c31ec) | Apr 28, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [5f191f449f](https://linux-hardware.org/?probe=5f191f449f) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ca70475f8a](https://linux-hardware.org/?probe=ca70475f8a) | Apr 28, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [0e403fcd17](https://linux-hardware.org/?probe=0e403fcd17) | Apr 27, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [6c35501215](https://linux-hardware.org/?probe=6c35501215) | Apr 27, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [ec41184680](https://linux-hardware.org/?probe=ec41184680) | Apr 27, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5c5fece872](https://linux-hardware.org/?probe=5c5fece872) | Apr 27, 2023 |
| Lenovo        | QIWY3                       | Notebook    | [a7c04857e4](https://linux-hardware.org/?probe=a7c04857e4) | Apr 27, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [29d2a588e0](https://linux-hardware.org/?probe=29d2a588e0) | Apr 27, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [3ec3c7aa7b](https://linux-hardware.org/?probe=3ec3c7aa7b) | Apr 26, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [53c0f79af9](https://linux-hardware.org/?probe=53c0f79af9) | Apr 26, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [018ade4782](https://linux-hardware.org/?probe=018ade4782) | Apr 26, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [48e88f7bd1](https://linux-hardware.org/?probe=48e88f7bd1) | Apr 25, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2ccfcd2b27](https://linux-hardware.org/?probe=2ccfcd2b27) | Apr 25, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [45199e8296](https://linux-hardware.org/?probe=45199e8296) | Apr 25, 2023 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [19c145fab1](https://linux-hardware.org/?probe=19c145fab1) | Apr 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d73e1b6350](https://linux-hardware.org/?probe=d73e1b6350) | Apr 24, 2023 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [46a27a7551](https://linux-hardware.org/?probe=46a27a7551) | Apr 23, 2023 |
| Notebook      | W54_55_94_95_97AU,AUQ       | Notebook    | [f4e4c58948](https://linux-hardware.org/?probe=f4e4c58948) | Apr 23, 2023 |
| Google        | Kefka                       | Notebook    | [2802d83837](https://linux-hardware.org/?probe=2802d83837) | Apr 23, 2023 |
| ASUSTek       | GL703VM                     | Notebook    | [f3c76b5075](https://linux-hardware.org/?probe=f3c76b5075) | Apr 23, 2023 |
| HP            | 8433 11                     | Desktop     | [e885f0469c](https://linux-hardware.org/?probe=e885f0469c) | Apr 22, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [2aa36b9cfd](https://linux-hardware.org/?probe=2aa36b9cfd) | Apr 22, 2023 |
| Allview       | Allbook J                   | Notebook    | [96a3d7d3ef](https://linux-hardware.org/?probe=96a3d7d3ef) | Apr 22, 2023 |
| HP            | Spectre x360 Convertible    | Convertible | [1a3ff160a7](https://linux-hardware.org/?probe=1a3ff160a7) | Apr 21, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [4fad4d4a09](https://linux-hardware.org/?probe=4fad4d4a09) | Apr 21, 2023 |
| Gateway       | NV55C                       | Notebook    | [e77192c3b1](https://linux-hardware.org/?probe=e77192c3b1) | Apr 20, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [50f90c0b1f](https://linux-hardware.org/?probe=50f90c0b1f) | Apr 20, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [e299a6ed8e](https://linux-hardware.org/?probe=e299a6ed8e) | Apr 20, 2023 |
| Dell          | Latitude 7410               | Notebook    | [36e2aea9ea](https://linux-hardware.org/?probe=36e2aea9ea) | Apr 19, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1943314777](https://linux-hardware.org/?probe=1943314777) | Apr 19, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [69b2b1c95f](https://linux-hardware.org/?probe=69b2b1c95f) | Apr 19, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [17eb54bee6](https://linux-hardware.org/?probe=17eb54bee6) | Apr 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [17b3242021](https://linux-hardware.org/?probe=17b3242021) | Apr 18, 2023 |
| Allview       | Allbook J                   | Notebook    | [4ff8627338](https://linux-hardware.org/?probe=4ff8627338) | Apr 18, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [f44b68cf93](https://linux-hardware.org/?probe=f44b68cf93) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [482a8c29cc](https://linux-hardware.org/?probe=482a8c29cc) | Apr 16, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [55309d71c2](https://linux-hardware.org/?probe=55309d71c2) | Apr 16, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [3fd496c5f8](https://linux-hardware.org/?probe=3fd496c5f8) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [0dfc78d12a](https://linux-hardware.org/?probe=0dfc78d12a) | Apr 15, 2023 |
| HP            | Mini 210-1000               | Notebook    | [e8b0b26e10](https://linux-hardware.org/?probe=e8b0b26e10) | Apr 15, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c5f2678609](https://linux-hardware.org/?probe=c5f2678609) | Apr 15, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [11b817e884](https://linux-hardware.org/?probe=11b817e884) | Apr 15, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [c4f2e4e7d8](https://linux-hardware.org/?probe=c4f2e4e7d8) | Apr 14, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [f7029b5f3b](https://linux-hardware.org/?probe=f7029b5f3b) | Apr 14, 2023 |
| ASUSTek       | GL502VM                     | Notebook    | [4d31e0eb90](https://linux-hardware.org/?probe=4d31e0eb90) | Apr 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [b7786541c0](https://linux-hardware.org/?probe=b7786541c0) | Apr 13, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [356ff49c7c](https://linux-hardware.org/?probe=356ff49c7c) | Apr 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bba5f185af](https://linux-hardware.org/?probe=bba5f185af) | Apr 13, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [76f2d6b30c](https://linux-hardware.org/?probe=76f2d6b30c) | Apr 13, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [3ac19a6abf](https://linux-hardware.org/?probe=3ac19a6abf) | Apr 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6e34f5a7b8](https://linux-hardware.org/?probe=6e34f5a7b8) | Apr 13, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [23371691ec](https://linux-hardware.org/?probe=23371691ec) | Apr 12, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [dc40d51336](https://linux-hardware.org/?probe=dc40d51336) | Apr 12, 2023 |
| ASUSTek       | TP500LAG                    | Notebook    | [ae048d3165](https://linux-hardware.org/?probe=ae048d3165) | Apr 12, 2023 |
| HP            | 8433 11                     | Desktop     | [61c92812be](https://linux-hardware.org/?probe=61c92812be) | Apr 12, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [8297ce2712](https://linux-hardware.org/?probe=8297ce2712) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [e3fc8c8f43](https://linux-hardware.org/?probe=e3fc8c8f43) | Apr 11, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [6037aee790](https://linux-hardware.org/?probe=6037aee790) | Apr 11, 2023 |
| MSI           | P67A-C45                    | Desktop     | [25a90d2595](https://linux-hardware.org/?probe=25a90d2595) | Apr 10, 2023 |
| ASUSTek       | TP500LAG                    | Notebook    | [b67954cc59](https://linux-hardware.org/?probe=b67954cc59) | Apr 10, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [0f078152ca](https://linux-hardware.org/?probe=0f078152ca) | Apr 10, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [5bd37d599e](https://linux-hardware.org/?probe=5bd37d599e) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [19fd2b6d0d](https://linux-hardware.org/?probe=19fd2b6d0d) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [7dc7e5e5c3](https://linux-hardware.org/?probe=7dc7e5e5c3) | Apr 09, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [d938c02967](https://linux-hardware.org/?probe=d938c02967) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [bc402eee2e](https://linux-hardware.org/?probe=bc402eee2e) | Apr 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ab81a719b](https://linux-hardware.org/?probe=1ab81a719b) | Apr 08, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [840f96a7df](https://linux-hardware.org/?probe=840f96a7df) | Apr 08, 2023 |
| Dell          | Latitude 5431               | Notebook    | [d85ac2917b](https://linux-hardware.org/?probe=d85ac2917b) | Apr 07, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [241572fcea](https://linux-hardware.org/?probe=241572fcea) | Apr 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a9882c4012](https://linux-hardware.org/?probe=a9882c4012) | Apr 06, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [7e3ef5fa45](https://linux-hardware.org/?probe=7e3ef5fa45) | Apr 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b949468335](https://linux-hardware.org/?probe=b949468335) | Apr 05, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [62debd585f](https://linux-hardware.org/?probe=62debd585f) | Apr 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [f1398d5ada](https://linux-hardware.org/?probe=f1398d5ada) | Apr 05, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [dcf97ad331](https://linux-hardware.org/?probe=dcf97ad331) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [dad967cc87](https://linux-hardware.org/?probe=dad967cc87) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [0f75295895](https://linux-hardware.org/?probe=0f75295895) | Apr 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f89b2c8b2a](https://linux-hardware.org/?probe=f89b2c8b2a) | Apr 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [9f251621b1](https://linux-hardware.org/?probe=9f251621b1) | Apr 04, 2023 |
| Dell          | Precision 5530              | Notebook    | [bf568860cb](https://linux-hardware.org/?probe=bf568860cb) | Apr 04, 2023 |
| Lenovo        | Unknown                     | Notebook    | [4216d2969c](https://linux-hardware.org/?probe=4216d2969c) | Apr 04, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [a03fbcf098](https://linux-hardware.org/?probe=a03fbcf098) | Apr 03, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [6906a8d309](https://linux-hardware.org/?probe=6906a8d309) | Apr 03, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [d447871547](https://linux-hardware.org/?probe=d447871547) | Apr 03, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [82a3b55b60](https://linux-hardware.org/?probe=82a3b55b60) | Apr 02, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [fabc275714](https://linux-hardware.org/?probe=fabc275714) | Apr 01, 2023 |
| MSI           | P67A-C43                    | Desktop     | [f3e7913310](https://linux-hardware.org/?probe=f3e7913310) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [36e57fb4cf](https://linux-hardware.org/?probe=36e57fb4cf) | Apr 01, 2023 |
| ASRock        | Z87 Extreme11/ac            | Desktop     | [283593a105](https://linux-hardware.org/?probe=283593a105) | Mar 31, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c3f0c2a691](https://linux-hardware.org/?probe=c3f0c2a691) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [cdb78d0527](https://linux-hardware.org/?probe=cdb78d0527) | Mar 30, 2023 |
| MSI           | 2AE0                        | Desktop     | [29c86e9653](https://linux-hardware.org/?probe=29c86e9653) | Mar 29, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [872733b74c](https://linux-hardware.org/?probe=872733b74c) | Mar 29, 2023 |
| MSI           | 2AE0                        | Desktop     | [53e6254c56](https://linux-hardware.org/?probe=53e6254c56) | Mar 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [6de889ae8a](https://linux-hardware.org/?probe=6de889ae8a) | Mar 29, 2023 |
| ASUSTek       | N550JX                      | Notebook    | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| ASUSTek       | A78M-A                      | Desktop     | [e2ee931df2](https://linux-hardware.org/?probe=e2ee931df2) | Mar 28, 2023 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| HP            | Compaq 6730s                | Notebook    | [8d4cea5a81](https://linux-hardware.org/?probe=8d4cea5a81) | Mar 28, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [42601709f3](https://linux-hardware.org/?probe=42601709f3) | Mar 27, 2023 |
| Gigabyte      | H110M-S2PV DDR3-CF          | Desktop     | [022acc16f7](https://linux-hardware.org/?probe=022acc16f7) | Mar 27, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [98df8e769b](https://linux-hardware.org/?probe=98df8e769b) | Mar 26, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [438f4cb9d9](https://linux-hardware.org/?probe=438f4cb9d9) | Mar 26, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [6c942c5a39](https://linux-hardware.org/?probe=6c942c5a39) | Mar 26, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [3c68ddf942](https://linux-hardware.org/?probe=3c68ddf942) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [f78ca791e0](https://linux-hardware.org/?probe=f78ca791e0) | Mar 25, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [6a03f43f29](https://linux-hardware.org/?probe=6a03f43f29) | Mar 25, 2023 |
| HP            | 8433 11                     | Desktop     | [5ab010ffd4](https://linux-hardware.org/?probe=5ab010ffd4) | Mar 25, 2023 |
| Purism        | Librem 13 v2                | Notebook    | [ef5cf3e08f](https://linux-hardware.org/?probe=ef5cf3e08f) | Mar 25, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [f2a2593a06](https://linux-hardware.org/?probe=f2a2593a06) | Mar 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [6a2a55ca61](https://linux-hardware.org/?probe=6a2a55ca61) | Mar 24, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [640a9ac505](https://linux-hardware.org/?probe=640a9ac505) | Mar 24, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | Desktop     | [2f50a76b96](https://linux-hardware.org/?probe=2f50a76b96) | Mar 22, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | Notebook    | [b618258a5c](https://linux-hardware.org/?probe=b618258a5c) | Mar 22, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [982f47fec3](https://linux-hardware.org/?probe=982f47fec3) | Mar 22, 2023 |
| Dell          | Latitude D530               | Notebook    | [92cf04edba](https://linux-hardware.org/?probe=92cf04edba) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7b772c82ca](https://linux-hardware.org/?probe=7b772c82ca) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bd045deb23](https://linux-hardware.org/?probe=bd045deb23) | Mar 21, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | Notebook    | [c87a678cf5](https://linux-hardware.org/?probe=c87a678cf5) | Mar 21, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [c7c5415a8c](https://linux-hardware.org/?probe=c7c5415a8c) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [de1c89d1b0](https://linux-hardware.org/?probe=de1c89d1b0) | Mar 21, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [0c0bff4f29](https://linux-hardware.org/?probe=0c0bff4f29) | Mar 20, 2023 |
| HP            | 304Ah                       | Desktop     | [49adbe8acf](https://linux-hardware.org/?probe=49adbe8acf) | Mar 20, 2023 |
| Lenovo        | LEGION5PRO-16ACH6H 82JQ     | Notebook    | [4f3cbedf85](https://linux-hardware.org/?probe=4f3cbedf85) | Mar 20, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [b7cf9d91ee](https://linux-hardware.org/?probe=b7cf9d91ee) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [888ec192b4](https://linux-hardware.org/?probe=888ec192b4) | Mar 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [729a1432a0](https://linux-hardware.org/?probe=729a1432a0) | Mar 19, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [9cdd00c854](https://linux-hardware.org/?probe=9cdd00c854) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [f35715c399](https://linux-hardware.org/?probe=f35715c399) | Mar 18, 2023 |
| Gigabyte      | Z68XP-UD4                   | Desktop     | [9d5f79bbf4](https://linux-hardware.org/?probe=9d5f79bbf4) | Mar 18, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [87ba801b00](https://linux-hardware.org/?probe=87ba801b00) | Mar 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [2cb5e6ce4f](https://linux-hardware.org/?probe=2cb5e6ce4f) | Mar 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [5d43e434bc](https://linux-hardware.org/?probe=5d43e434bc) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [92d818d184](https://linux-hardware.org/?probe=92d818d184) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [60114cc9c8](https://linux-hardware.org/?probe=60114cc9c8) | Mar 16, 2023 |
| Dell          | 0PGKWF A00                  | Desktop     | [d03e035ed6](https://linux-hardware.org/?probe=d03e035ed6) | Mar 16, 2023 |
| Dell          | 0PGKWF A00                  | Desktop     | [2b34503276](https://linux-hardware.org/?probe=2b34503276) | Mar 16, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [4a47120f89](https://linux-hardware.org/?probe=4a47120f89) | Mar 15, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [a1e7a34896](https://linux-hardware.org/?probe=a1e7a34896) | Mar 14, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [6e2a63edaa](https://linux-hardware.org/?probe=6e2a63edaa) | Mar 14, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [bc12f3e2e4](https://linux-hardware.org/?probe=bc12f3e2e4) | Mar 14, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dfd3b8546c](https://linux-hardware.org/?probe=dfd3b8546c) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [2b69e73996](https://linux-hardware.org/?probe=2b69e73996) | Mar 14, 2023 |
| Lenovo        | ThinkPad Edge E530 3259H... | Notebook    | [74348d01f3](https://linux-hardware.org/?probe=74348d01f3) | Mar 13, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [8dc295e39b](https://linux-hardware.org/?probe=8dc295e39b) | Mar 13, 2023 |
| Wortmann      | Terra 3100                  | Desktop     | [126586f434](https://linux-hardware.org/?probe=126586f434) | Mar 12, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [2002eaa403](https://linux-hardware.org/?probe=2002eaa403) | Mar 12, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [fac1ee2528](https://linux-hardware.org/?probe=fac1ee2528) | Mar 12, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [8f3c49d011](https://linux-hardware.org/?probe=8f3c49d011) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK U939X              | Convertible | [359ca913fe](https://linux-hardware.org/?probe=359ca913fe) | Mar 12, 2023 |
| ASUSTek       | PN50                        | Mini pc     | [9ce749e52e](https://linux-hardware.org/?probe=9ce749e52e) | Mar 12, 2023 |
| ASRock        | AB350M-HDV                  | Desktop     | [45a5fbc5e7](https://linux-hardware.org/?probe=45a5fbc5e7) | Mar 12, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [5bf763c288](https://linux-hardware.org/?probe=5bf763c288) | Mar 11, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e5cdf2201f](https://linux-hardware.org/?probe=e5cdf2201f) | Mar 11, 2023 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [97741c600c](https://linux-hardware.org/?probe=97741c600c) | Mar 11, 2023 |
| Jumper        | EZbook                      | Notebook    | [ed607c4113](https://linux-hardware.org/?probe=ed607c4113) | Mar 11, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5cb06ca8ce](https://linux-hardware.org/?probe=5cb06ca8ce) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [54e498fb2e](https://linux-hardware.org/?probe=54e498fb2e) | Mar 10, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [689186d7de](https://linux-hardware.org/?probe=689186d7de) | Mar 10, 2023 |
| HP            | ProBook 6460b               | Notebook    | [4374107e07](https://linux-hardware.org/?probe=4374107e07) | Mar 10, 2023 |
| HP            | ProBook 6460b               | Notebook    | [7a01d6124d](https://linux-hardware.org/?probe=7a01d6124d) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [661125aac2](https://linux-hardware.org/?probe=661125aac2) | Mar 10, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [d524e6c586](https://linux-hardware.org/?probe=d524e6c586) | Mar 10, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [2d75f5ea8b](https://linux-hardware.org/?probe=2d75f5ea8b) | Mar 10, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [e72ba8b8aa](https://linux-hardware.org/?probe=e72ba8b8aa) | Mar 08, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [d7ac4c2edb](https://linux-hardware.org/?probe=d7ac4c2edb) | Mar 08, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [c1339ac8de](https://linux-hardware.org/?probe=c1339ac8de) | Mar 08, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [30221f1500](https://linux-hardware.org/?probe=30221f1500) | Mar 07, 2023 |
| MSI           | P67A-C45                    | Desktop     | [52e013338c](https://linux-hardware.org/?probe=52e013338c) | Mar 07, 2023 |
| Acer          | Veriton X4610G              | Desktop     | [7f5cb2ac6a](https://linux-hardware.org/?probe=7f5cb2ac6a) | Mar 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ca3d88758](https://linux-hardware.org/?probe=4ca3d88758) | Mar 07, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1490c281bd](https://linux-hardware.org/?probe=1490c281bd) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [9b1357d5c0](https://linux-hardware.org/?probe=9b1357d5c0) | Mar 06, 2023 |
| Gigabyte      | Z68XP-UD3P                  | Desktop     | [bfb7053ff8](https://linux-hardware.org/?probe=bfb7053ff8) | Mar 06, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [09e8aaf103](https://linux-hardware.org/?probe=09e8aaf103) | Mar 05, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [386fe6d7ab](https://linux-hardware.org/?probe=386fe6d7ab) | Mar 05, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [d81384080b](https://linux-hardware.org/?probe=d81384080b) | Mar 05, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [3e4fdfbb73](https://linux-hardware.org/?probe=3e4fdfbb73) | Mar 05, 2023 |
| HP            | 1905                        | Desktop     | [3a15a8a255](https://linux-hardware.org/?probe=3a15a8a255) | Mar 05, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [4b47face39](https://linux-hardware.org/?probe=4b47face39) | Mar 05, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [38e61e3fb5](https://linux-hardware.org/?probe=38e61e3fb5) | Mar 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [daefae334b](https://linux-hardware.org/?probe=daefae334b) | Mar 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [19bd4c1e4e](https://linux-hardware.org/?probe=19bd4c1e4e) | Mar 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f9a2075d54](https://linux-hardware.org/?probe=f9a2075d54) | Mar 04, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [066ce423c0](https://linux-hardware.org/?probe=066ce423c0) | Mar 03, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [587096ec48](https://linux-hardware.org/?probe=587096ec48) | Mar 03, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [3edae4d4f7](https://linux-hardware.org/?probe=3edae4d4f7) | Mar 03, 2023 |
| HP            | 2B4B                        | Desktop     | [6fe13bec4d](https://linux-hardware.org/?probe=6fe13bec4d) | Mar 02, 2023 |
| HP            | 2B4B                        | Desktop     | [d97467e5aa](https://linux-hardware.org/?probe=d97467e5aa) | Mar 02, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [e87ce2454c](https://linux-hardware.org/?probe=e87ce2454c) | Mar 02, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [5cb58db69b](https://linux-hardware.org/?probe=5cb58db69b) | Mar 02, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a279108842](https://linux-hardware.org/?probe=a279108842) | Mar 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [d008353c16](https://linux-hardware.org/?probe=d008353c16) | Mar 01, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [0242801bbc](https://linux-hardware.org/?probe=0242801bbc) | Mar 01, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [0f19d5c037](https://linux-hardware.org/?probe=0f19d5c037) | Mar 01, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [5bc379ea65](https://linux-hardware.org/?probe=5bc379ea65) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [268413a47c](https://linux-hardware.org/?probe=268413a47c) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [169e938f25](https://linux-hardware.org/?probe=169e938f25) | Mar 01, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [71b8cbeda5](https://linux-hardware.org/?probe=71b8cbeda5) | Feb 28, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [0710c7be6e](https://linux-hardware.org/?probe=0710c7be6e) | Feb 28, 2023 |
| HP            | ProBook 4540s               | Notebook    | [a52b9c7637](https://linux-hardware.org/?probe=a52b9c7637) | Feb 27, 2023 |
| HP            | ProBook 4540s               | Notebook    | [45e989b539](https://linux-hardware.org/?probe=45e989b539) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [ee2645efa8](https://linux-hardware.org/?probe=ee2645efa8) | Feb 27, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [8c0dc3ba82](https://linux-hardware.org/?probe=8c0dc3ba82) | Feb 27, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [ca878d6577](https://linux-hardware.org/?probe=ca878d6577) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [0d838134b7](https://linux-hardware.org/?probe=0d838134b7) | Feb 27, 2023 |
| AXDIA Inte... | WINDESK9 3G v2              | Notebook    | [49282044d3](https://linux-hardware.org/?probe=49282044d3) | Feb 26, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [c3156c3f23](https://linux-hardware.org/?probe=c3156c3f23) | Feb 26, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [899c2066a1](https://linux-hardware.org/?probe=899c2066a1) | Feb 25, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b367bf6276](https://linux-hardware.org/?probe=b367bf6276) | Feb 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [86ab345b56](https://linux-hardware.org/?probe=86ab345b56) | Feb 24, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [f7d1c79daa](https://linux-hardware.org/?probe=f7d1c79daa) | Feb 24, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [105209c356](https://linux-hardware.org/?probe=105209c356) | Feb 24, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5027942f8b](https://linux-hardware.org/?probe=5027942f8b) | Feb 24, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [2c490934fb](https://linux-hardware.org/?probe=2c490934fb) | Feb 24, 2023 |
| MSI           | X58 Pro                     | Desktop     | [22509b3e42](https://linux-hardware.org/?probe=22509b3e42) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [48cbefb8f6](https://linux-hardware.org/?probe=48cbefb8f6) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [0dac92bb9d](https://linux-hardware.org/?probe=0dac92bb9d) | Feb 23, 2023 |
| Dell          | XPS 9320                    | Notebook    | [896a21551e](https://linux-hardware.org/?probe=896a21551e) | Feb 22, 2023 |
| HP            | 2B4B                        | Desktop     | [92c45eb54f](https://linux-hardware.org/?probe=92c45eb54f) | Feb 21, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [892b3930a6](https://linux-hardware.org/?probe=892b3930a6) | Feb 21, 2023 |
| Lenovo        | IdeaPad Y900-17ISK 80Q1     | Notebook    | [d852e3306a](https://linux-hardware.org/?probe=d852e3306a) | Feb 20, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e434f7f85a](https://linux-hardware.org/?probe=e434f7f85a) | Feb 20, 2023 |
| SK hynix      | HyBook                      | Notebook    | [494c1a322d](https://linux-hardware.org/?probe=494c1a322d) | Feb 20, 2023 |
| Acer          | Aspire X3950                | Desktop     | [f5b4a3baa3](https://linux-hardware.org/?probe=f5b4a3baa3) | Feb 20, 2023 |
| HP            | ProBook 4540s               | Notebook    | [079a5f512d](https://linux-hardware.org/?probe=079a5f512d) | Feb 20, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [e5b5f4792c](https://linux-hardware.org/?probe=e5b5f4792c) | Feb 19, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [c73a9b9ee2](https://linux-hardware.org/?probe=c73a9b9ee2) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [19bdc55bfd](https://linux-hardware.org/?probe=19bdc55bfd) | Feb 19, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2a35f99890](https://linux-hardware.org/?probe=2a35f99890) | Feb 18, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [f4065623e5](https://linux-hardware.org/?probe=f4065623e5) | Feb 18, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | Notebook    | [5fb2330e71](https://linux-hardware.org/?probe=5fb2330e71) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [8942075e7b](https://linux-hardware.org/?probe=8942075e7b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [76c8c6f7ba](https://linux-hardware.org/?probe=76c8c6f7ba) | Feb 17, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | Notebook    | [9497d288f6](https://linux-hardware.org/?probe=9497d288f6) | Feb 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4a5c7432ae](https://linux-hardware.org/?probe=4a5c7432ae) | Feb 17, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [beabc46f67](https://linux-hardware.org/?probe=beabc46f67) | Feb 14, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [fb1ff4a6d9](https://linux-hardware.org/?probe=fb1ff4a6d9) | Feb 14, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [2947200c5c](https://linux-hardware.org/?probe=2947200c5c) | Feb 14, 2023 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [84a46ec9ce](https://linux-hardware.org/?probe=84a46ec9ce) | Feb 14, 2023 |
| Google        | Lillipup                    | Notebook    | [af7451beff](https://linux-hardware.org/?probe=af7451beff) | Feb 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9b84a7339e](https://linux-hardware.org/?probe=9b84a7339e) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [20428fc0ed](https://linux-hardware.org/?probe=20428fc0ed) | Feb 13, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [762dd6fa2e](https://linux-hardware.org/?probe=762dd6fa2e) | Feb 13, 2023 |
| HP            | ProBook 6460b               | Notebook    | [5436445da0](https://linux-hardware.org/?probe=5436445da0) | Feb 13, 2023 |
| HP            | ProBook 6460b               | Notebook    | [ba14b45543](https://linux-hardware.org/?probe=ba14b45543) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [0a6d50bc2a](https://linux-hardware.org/?probe=0a6d50bc2a) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [75980f2f55](https://linux-hardware.org/?probe=75980f2f55) | Feb 13, 2023 |
| Samsung       | 550XDA                      | Notebook    | [0c3e0dd389](https://linux-hardware.org/?probe=0c3e0dd389) | Feb 13, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [86026e4f54](https://linux-hardware.org/?probe=86026e4f54) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [df52d514c9](https://linux-hardware.org/?probe=df52d514c9) | Feb 12, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [a384bb740c](https://linux-hardware.org/?probe=a384bb740c) | Feb 11, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [e1dc99210d](https://linux-hardware.org/?probe=e1dc99210d) | Feb 11, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [79204339d0](https://linux-hardware.org/?probe=79204339d0) | Feb 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [df97c92c82](https://linux-hardware.org/?probe=df97c92c82) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [9621fdeccb](https://linux-hardware.org/?probe=9621fdeccb) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [523c8db418](https://linux-hardware.org/?probe=523c8db418) | Feb 11, 2023 |
| Dell          | Precision 5570              | Notebook    | [8398c80e6b](https://linux-hardware.org/?probe=8398c80e6b) | Feb 11, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [92cbb2e876](https://linux-hardware.org/?probe=92cbb2e876) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2f721ad33a](https://linux-hardware.org/?probe=2f721ad33a) | Feb 10, 2023 |
| Acer          | Veriton N4680G              | Desktop     | [4198835011](https://linux-hardware.org/?probe=4198835011) | Feb 10, 2023 |
| Dell          | Latitude 5421               | Notebook    | [e7c6fbfeb8](https://linux-hardware.org/?probe=e7c6fbfeb8) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3b71a70207](https://linux-hardware.org/?probe=3b71a70207) | Feb 09, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [a07b2a4444](https://linux-hardware.org/?probe=a07b2a4444) | Feb 09, 2023 |
| Schenker      | VIA 15                      | Notebook    | [8096682644](https://linux-hardware.org/?probe=8096682644) | Feb 09, 2023 |
| Lenovo        | ThinkPad T440s 20ARS2V90... | Notebook    | [a2e7b3b9b7](https://linux-hardware.org/?probe=a2e7b3b9b7) | Feb 08, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [acbbbca6e7](https://linux-hardware.org/?probe=acbbbca6e7) | Feb 08, 2023 |
| ASRock        | X399M Taichi                | Desktop     | [c6bf333a82](https://linux-hardware.org/?probe=c6bf333a82) | Feb 08, 2023 |
| HP            | 1494                        | Desktop     | [ba7c61bf23](https://linux-hardware.org/?probe=ba7c61bf23) | Feb 07, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [dc2172d485](https://linux-hardware.org/?probe=dc2172d485) | Feb 07, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3b6bf45c6b](https://linux-hardware.org/?probe=3b6bf45c6b) | Feb 07, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [70f715ffb4](https://linux-hardware.org/?probe=70f715ffb4) | Feb 06, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [f7ca9a94c5](https://linux-hardware.org/?probe=f7ca9a94c5) | Feb 06, 2023 |
| HP            | 0B54h D                     | Desktop     | [fa38931f1f](https://linux-hardware.org/?probe=fa38931f1f) | Feb 06, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [9b92561723](https://linux-hardware.org/?probe=9b92561723) | Feb 06, 2023 |
| Medion        | P6624                       | Notebook    | [5a31124376](https://linux-hardware.org/?probe=5a31124376) | Feb 06, 2023 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [16f0d33c85](https://linux-hardware.org/?probe=16f0d33c85) | Feb 06, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [4a971615e8](https://linux-hardware.org/?probe=4a971615e8) | Feb 05, 2023 |
| Dell          | Latitude E7470              | Notebook    | [88a8b69cc3](https://linux-hardware.org/?probe=88a8b69cc3) | Feb 05, 2023 |
| HP            | 845A                        | Desktop     | [3e744bcf5b](https://linux-hardware.org/?probe=3e744bcf5b) | Feb 05, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | Notebook    | [bbe182e4c2](https://linux-hardware.org/?probe=bbe182e4c2) | Feb 04, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [81c4e4ce60](https://linux-hardware.org/?probe=81c4e4ce60) | Feb 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [fd8c9d9ccf](https://linux-hardware.org/?probe=fd8c9d9ccf) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9b0a8de7a1](https://linux-hardware.org/?probe=9b0a8de7a1) | Feb 02, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [bd22f26ad1](https://linux-hardware.org/?probe=bd22f26ad1) | Jan 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [28ea3cafe8](https://linux-hardware.org/?probe=28ea3cafe8) | Jan 31, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [f2636de53b](https://linux-hardware.org/?probe=f2636de53b) | Jan 31, 2023 |
| Lenovo        | 3717 SDK0J40697 WIN 3305... | Desktop     | [175a0fcf9a](https://linux-hardware.org/?probe=175a0fcf9a) | Jan 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e0e7acce8d](https://linux-hardware.org/?probe=e0e7acce8d) | Jan 31, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [32dfb5ebe2](https://linux-hardware.org/?probe=32dfb5ebe2) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [fc09442b7c](https://linux-hardware.org/?probe=fc09442b7c) | Jan 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b78602c91d](https://linux-hardware.org/?probe=b78602c91d) | Jan 30, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [8d7c1dbf4d](https://linux-hardware.org/?probe=8d7c1dbf4d) | Jan 30, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [6bf8eb9c73](https://linux-hardware.org/?probe=6bf8eb9c73) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [78d987fedf](https://linux-hardware.org/?probe=78d987fedf) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a178301183](https://linux-hardware.org/?probe=a178301183) | Jan 30, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [1746dfe4b1](https://linux-hardware.org/?probe=1746dfe4b1) | Jan 30, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [9b0891d54d](https://linux-hardware.org/?probe=9b0891d54d) | Jan 30, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b61ed06b1e](https://linux-hardware.org/?probe=b61ed06b1e) | Jan 30, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [de8c055a8a](https://linux-hardware.org/?probe=de8c055a8a) | Jan 29, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [327e2d4e3e](https://linux-hardware.org/?probe=327e2d4e3e) | Jan 28, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b5ca740834](https://linux-hardware.org/?probe=b5ca740834) | Jan 28, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f20e47b9d7](https://linux-hardware.org/?probe=f20e47b9d7) | Jan 28, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [4a33511e43](https://linux-hardware.org/?probe=4a33511e43) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [de71656929](https://linux-hardware.org/?probe=de71656929) | Jan 27, 2023 |
| Lenovo        | ThinkPad R500 2718WA3       | Notebook    | [2bb86279a8](https://linux-hardware.org/?probe=2bb86279a8) | Jan 27, 2023 |
| Intel         | X99                         | Desktop     | [1fbd6cf5bd](https://linux-hardware.org/?probe=1fbd6cf5bd) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [cf662e2730](https://linux-hardware.org/?probe=cf662e2730) | Jan 25, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [c2ff1b1e23](https://linux-hardware.org/?probe=c2ff1b1e23) | Jan 25, 2023 |
| Fujitsu       | LIFEBOOK U7511              | Notebook    | [7b9b00eccb](https://linux-hardware.org/?probe=7b9b00eccb) | Jan 24, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [723d6a91bb](https://linux-hardware.org/?probe=723d6a91bb) | Jan 24, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5abd524783](https://linux-hardware.org/?probe=5abd524783) | Jan 24, 2023 |
| HP            | 2B34                        | Desktop     | [ca97840b4b](https://linux-hardware.org/?probe=ca97840b4b) | Jan 24, 2023 |
| Biostar       | Hi-Fi A85W                  | Desktop     | [4da9f87ebb](https://linux-hardware.org/?probe=4da9f87ebb) | Jan 23, 2023 |
| Acer          | Swift SFX16-52G             | Notebook    | [62e1cc77f9](https://linux-hardware.org/?probe=62e1cc77f9) | Jan 23, 2023 |
| HP            | 8399                        | Desktop     | [db427c8bc9](https://linux-hardware.org/?probe=db427c8bc9) | Jan 22, 2023 |
| HP            | 8399                        | Desktop     | [cdf9d12bb4](https://linux-hardware.org/?probe=cdf9d12bb4) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [ffc0fa7fb5](https://linux-hardware.org/?probe=ffc0fa7fb5) | Jan 22, 2023 |
| HP            | Pavilion dv4                | Notebook    | [9fd79086c8](https://linux-hardware.org/?probe=9fd79086c8) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [7933a58a32](https://linux-hardware.org/?probe=7933a58a32) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 20RD0019RT     | Notebook    | [282161cc92](https://linux-hardware.org/?probe=282161cc92) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 20RD0019RT     | Notebook    | [8d235b1b8d](https://linux-hardware.org/?probe=8d235b1b8d) | Jan 22, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [5e28e4cbdc](https://linux-hardware.org/?probe=5e28e4cbdc) | Jan 21, 2023 |
| Dell          | Latitude 9420               | Notebook    | [4b847961df](https://linux-hardware.org/?probe=4b847961df) | Jan 21, 2023 |
| Fujitsu       | LIFEBOOK P1630              | Notebook    | [5ee218deb4](https://linux-hardware.org/?probe=5ee218deb4) | Jan 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [bd51c2a953](https://linux-hardware.org/?probe=bd51c2a953) | Jan 20, 2023 |
| Medion        | P6624                       | Notebook    | [344d427f44](https://linux-hardware.org/?probe=344d427f44) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [31698019a3](https://linux-hardware.org/?probe=31698019a3) | Jan 20, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [f6b68c1767](https://linux-hardware.org/?probe=f6b68c1767) | Jan 19, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [6c8d492f56](https://linux-hardware.org/?probe=6c8d492f56) | Jan 19, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [e7548596d1](https://linux-hardware.org/?probe=e7548596d1) | Jan 19, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [1f56f8cb21](https://linux-hardware.org/?probe=1f56f8cb21) | Jan 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [890980b6a9](https://linux-hardware.org/?probe=890980b6a9) | Jan 19, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [28a15ffc38](https://linux-hardware.org/?probe=28a15ffc38) | Jan 19, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [b0716d3518](https://linux-hardware.org/?probe=b0716d3518) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [004b2669ef](https://linux-hardware.org/?probe=004b2669ef) | Jan 18, 2023 |
| Fujitsu       | LIFEBOOK P1630              | Notebook    | [5a9662e39b](https://linux-hardware.org/?probe=5a9662e39b) | Jan 17, 2023 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [de3dde0785](https://linux-hardware.org/?probe=de3dde0785) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [9dba648ced](https://linux-hardware.org/?probe=9dba648ced) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [17fd020689](https://linux-hardware.org/?probe=17fd020689) | Jan 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [9b874af8a4](https://linux-hardware.org/?probe=9b874af8a4) | Jan 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [ae33b4bb24](https://linux-hardware.org/?probe=ae33b4bb24) | Jan 16, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [aae8dcf220](https://linux-hardware.org/?probe=aae8dcf220) | Jan 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [64bb2953ec](https://linux-hardware.org/?probe=64bb2953ec) | Jan 15, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [6309c0f057](https://linux-hardware.org/?probe=6309c0f057) | Jan 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [212fa962a2](https://linux-hardware.org/?probe=212fa962a2) | Jan 15, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [9bfcd0f555](https://linux-hardware.org/?probe=9bfcd0f555) | Jan 14, 2023 |
| MSI           | P67A-C45                    | Desktop     | [625a573f22](https://linux-hardware.org/?probe=625a573f22) | Jan 13, 2023 |
| Dell          | 0WG261                      | Desktop     | [c994d9e8ee](https://linux-hardware.org/?probe=c994d9e8ee) | Jan 13, 2023 |
| Dell          | Latitude 5414               | Notebook    | [bc4fdb0971](https://linux-hardware.org/?probe=bc4fdb0971) | Jan 13, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8674044a95](https://linux-hardware.org/?probe=8674044a95) | Jan 13, 2023 |
| Dell          | 0WG261                      | Desktop     | [5d1fe40a1f](https://linux-hardware.org/?probe=5d1fe40a1f) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [64a9cc7b90](https://linux-hardware.org/?probe=64a9cc7b90) | Jan 13, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [3665659d26](https://linux-hardware.org/?probe=3665659d26) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [6b20e87c33](https://linux-hardware.org/?probe=6b20e87c33) | Jan 13, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [e8bf140d81](https://linux-hardware.org/?probe=e8bf140d81) | Jan 12, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | Convertible | [f3bf17dba0](https://linux-hardware.org/?probe=f3bf17dba0) | Jan 11, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a5ea710efd](https://linux-hardware.org/?probe=a5ea710efd) | Jan 11, 2023 |
| Dell          | Latitude 9420               | Convertible | [1446885eb7](https://linux-hardware.org/?probe=1446885eb7) | Jan 11, 2023 |
| ASUSTek       | P5B                         | Desktop     | [9fd56e9b73](https://linux-hardware.org/?probe=9fd56e9b73) | Jan 08, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2f2f7a3a60](https://linux-hardware.org/?probe=2f2f7a3a60) | Jan 08, 2023 |
| HP            | ENVY 15                     | Notebook    | [bff59f1d42](https://linux-hardware.org/?probe=bff59f1d42) | Jan 08, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [a6d6bf8d28](https://linux-hardware.org/?probe=a6d6bf8d28) | Jan 08, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c272167e6a](https://linux-hardware.org/?probe=c272167e6a) | Jan 08, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [da3dc83a74](https://linux-hardware.org/?probe=da3dc83a74) | Jan 07, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [a4b5bc192d](https://linux-hardware.org/?probe=a4b5bc192d) | Jan 06, 2023 |
| Dell          | 081VG9 A05                  | Server      | [23031aa11a](https://linux-hardware.org/?probe=23031aa11a) | Jan 06, 2023 |
| Dell          | G7 7790                     | Notebook    | [ffaafd92cf](https://linux-hardware.org/?probe=ffaafd92cf) | Jan 05, 2023 |
| Dell          | Latitude 5430               | Notebook    | [4e8033e0f6](https://linux-hardware.org/?probe=4e8033e0f6) | Jan 05, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [6b475a50fc](https://linux-hardware.org/?probe=6b475a50fc) | Jan 05, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [922db531b3](https://linux-hardware.org/?probe=922db531b3) | Jan 05, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [e11b38ed14](https://linux-hardware.org/?probe=e11b38ed14) | Jan 05, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ed1bc83961](https://linux-hardware.org/?probe=ed1bc83961) | Jan 04, 2023 |
| Dell          | G3 3579                     | Notebook    | [becea24616](https://linux-hardware.org/?probe=becea24616) | Jan 04, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9e01a37071](https://linux-hardware.org/?probe=9e01a37071) | Jan 04, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [8a502c849f](https://linux-hardware.org/?probe=8a502c849f) | Jan 03, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [138a853640](https://linux-hardware.org/?probe=138a853640) | Jan 02, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [704cc86124](https://linux-hardware.org/?probe=704cc86124) | Jan 01, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [092aa8fe44](https://linux-hardware.org/?probe=092aa8fe44) | Jan 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [a8ce1c44a8](https://linux-hardware.org/?probe=a8ce1c44a8) | Jan 01, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [b68fa80860](https://linux-hardware.org/?probe=b68fa80860) | Dec 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [2508c5972e](https://linux-hardware.org/?probe=2508c5972e) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [133d8a7f70](https://linux-hardware.org/?probe=133d8a7f70) | Dec 31, 2022 |
| Intel Clie... | LAPRC710                    | Notebook    | [47e562afc7](https://linux-hardware.org/?probe=47e562afc7) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [60989ad0c4](https://linux-hardware.org/?probe=60989ad0c4) | Dec 31, 2022 |
| Dell          | XPS 9320                    | Notebook    | [c7a7749a95](https://linux-hardware.org/?probe=c7a7749a95) | Dec 30, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [0053ddb3c9](https://linux-hardware.org/?probe=0053ddb3c9) | Dec 30, 2022 |
| Dell          | XPS 9320                    | Notebook    | [458727c26e](https://linux-hardware.org/?probe=458727c26e) | Dec 30, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [250104c525](https://linux-hardware.org/?probe=250104c525) | Dec 29, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/openSUSE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| openSUSE Tumbleweed-XXXXXXXX | 1484      | 63.8%   |
| openSUSE Leap-15.2           | 211       | 9.07%   |
| openSUSE Leap-15.3           | 134       | 5.76%   |
| openSUSE Leap-15.4           | 133       | 5.72%   |
| openSUSE Leap-15.1           | 123       | 5.29%   |
| openSUSE Leap-15.5           | 107       | 4.6%    |
| openSUSE Microos-XXXXXXXX    | 68        | 2.92%   |
| openSUSE Leap-15.0           | 48        | 2.06%   |
| openSUSE 13.2                | 5         | 0.21%   |
| openSUSE Leap-42.2           | 3         | 0.13%   |
| openSUSE 42.3                | 3         | 0.13%   |
| openSUSE                     | 3         | 0.13%   |
| openSUSE Leap-42.3           | 2         | 0.09%   |
| openSUSE Leap-42.1           | 1         | 0.04%   |
| openSUSE 13.1                | 1         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| openSUSE | 2258      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.14.21-150500.53-default    | 50        | 1.85%   |
| 5.17.4-1-default             | 49        | 1.81%   |
| 4.12.14-lp151.28.44-default  | 43        | 1.59%   |
| 6.3.9-1-default              | 42        | 1.55%   |
| 6.0.8-1-default              | 35        | 1.29%   |
| 5.6.0-1-default              | 31        | 1.14%   |
| 6.3.2-1-default              | 29        | 1.07%   |
| 6.2.12-1-default             | 29        | 1.07%   |
| 6.3.4-1-default              | 27        | 1%      |
| 6.1.8-1-default              | 26        | 0.96%   |
| 6.0.12-1-default             | 26        | 0.96%   |
| 6.2.9-1-default              | 25        | 0.92%   |
| 6.1.12-1-default             | 25        | 0.92%   |
| 5.14.21-150400.22-default    | 25        | 0.92%   |
| 6.4.6-1-default              | 24        | 0.89%   |
| 6.4.11-1-default             | 24        | 0.89%   |
| 5.19.2-1-default             | 24        | 0.89%   |
| 6.0.10-1-default             | 23        | 0.85%   |
| 4.18.15-1-default            | 23        | 0.85%   |
| 5.3.18-lp152.63-default      | 22        | 0.81%   |
| 6.4.9-1-default              | 21        | 0.77%   |
| 6.2.1-1-default              | 21        | 0.77%   |
| 6.1.10-1-default             | 21        | 0.77%   |
| 5.14.14-1-default            | 21        | 0.77%   |
| 6.3.1-1-default              | 20        | 0.74%   |
| 6.2.6-1-default              | 20        | 0.74%   |
| 5.17.9-1-default             | 20        | 0.74%   |
| 5.16.11-1-default            | 20        | 0.74%   |
| 6.4.3-1-default              | 19        | 0.7%    |
| 6.3.7-1-default              | 19        | 0.7%    |
| 5.6.2-1-default              | 19        | 0.7%    |
| 5.17.1-1-default             | 19        | 0.7%    |
| 5.14.21-150500.55.19-default | 19        | 0.7%    |
| 6.4.8-1-default              | 18        | 0.66%   |
| 5.3.18-lp152.57-default      | 18        | 0.66%   |
| 5.3.18-59.37-default         | 18        | 0.66%   |
| 5.11.6-1-default             | 18        | 0.66%   |
| 5.8.4-1-default              | 17        | 0.63%   |
| 5.3.18-lp152.41-default      | 17        | 0.63%   |
| 5.19.8-1-default             | 17        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 315       | 12.04%  |
| 5.14.21 | 231       | 8.83%   |
| 4.12.14 | 158       | 6.04%   |
| 5.17.4  | 49        | 1.87%   |
| 6.3.9   | 42        | 1.6%    |
| 6.0.8   | 35        | 1.34%   |
| 5.6.0   | 33        | 1.26%   |
| 5.14.14 | 31        | 1.18%   |
| 6.3.1   | 30        | 1.15%   |
| 6.3.2   | 29        | 1.11%   |
| 6.2.12  | 29        | 1.11%   |
| 6.3.4   | 27        | 1.03%   |
| 6.0.12  | 27        | 1.03%   |
| 6.2.9   | 26        | 0.99%   |
| 6.1.8   | 26        | 0.99%   |
| 6.4.6   | 25        | 0.96%   |
| 6.1.12  | 25        | 0.96%   |
| 6.4.11  | 24        | 0.92%   |
| 6.0.10  | 24        | 0.92%   |
| 5.19.2  | 24        | 0.92%   |
| 6.1.10  | 23        | 0.88%   |
| 4.18.15 | 23        | 0.88%   |
| 6.4.9   | 21        | 0.8%    |
| 6.2.1   | 21        | 0.8%    |
| 5.6.2   | 21        | 0.8%    |
| 6.2.6   | 20        | 0.76%   |
| 5.17.9  | 20        | 0.76%   |
| 5.17.1  | 20        | 0.76%   |
| 5.16.11 | 20        | 0.76%   |
| 6.4.3   | 19        | 0.73%   |
| 6.3.7   | 19        | 0.73%   |
| 5.12.4  | 19        | 0.73%   |
| 5.11.6  | 19        | 0.73%   |
| 6.4.8   | 18        | 0.69%   |
| 5.8.4   | 18        | 0.69%   |
| 5.14.6  | 18        | 0.69%   |
| 5.10.7  | 18        | 0.69%   |
| 5.19.8  | 17        | 0.65%   |
| 5.18.6  | 17        | 0.65%   |
| 6.2.10  | 16        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3     | 336       | 13.21%  |
| 5.14    | 319       | 12.54%  |
| 4.12    | 158       | 6.21%   |
| 6.3     | 156       | 6.13%   |
| 6.0     | 144       | 5.66%   |
| 6.1     | 141       | 5.54%   |
| 6.4     | 134       | 5.27%   |
| 6.2     | 132       | 5.19%   |
| 5.17    | 114       | 4.48%   |
| 5.6     | 82        | 3.22%   |
| 5.16    | 77        | 3.03%   |
| 5.18    | 76        | 2.99%   |
| 5.12    | 72        | 2.83%   |
| 5.8     | 70        | 2.75%   |
| 5.10    | 68        | 2.67%   |
| 5.19    | 67        | 2.63%   |
| 5.11    | 59        | 2.32%   |
| 5.15    | 58        | 2.28%   |
| 5.13    | 49        | 1.93%   |
| 5.9     | 40        | 1.57%   |
| 5.7     | 36        | 1.42%   |
| 5.5     | 34        | 1.34%   |
| 4.18    | 27        | 1.06%   |
| 5.4     | 21        | 0.83%   |
| 5.0     | 14        | 0.55%   |
| 5.2     | 13        | 0.51%   |
| 4.17    | 11        | 0.43%   |
| 4.4     | 9         | 0.35%   |
| 5.1     | 5         | 0.2%    |
| 4.20    | 5         | 0.2%    |
| 4.3     | 4         | 0.16%   |
| 3.16    | 4         | 0.16%   |
| 4.19    | 3         | 0.12%   |
| 4.16    | 2         | 0.08%   |
| 4.7     | 1         | 0.04%   |
| 4.1     | 1         | 0.04%   |
| 3.12    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2236      | 98.98%  |
| i686    | 15        | 0.66%   |
| aarch64 | 7         | 0.31%   |
| armv7l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 1293      | 55.35%  |
| GNOME         | 441       | 18.88%  |
| KDE           | 213       | 9.12%   |
| Unknown       | 156       | 6.68%   |
| XFCE          | 112       | 4.79%   |
| MATE          | 22        | 0.94%   |
| X-Cinnamon    | 18        | 0.77%   |
| Cinnamon      | 14        | 0.6%    |
| LXQt          | 10        | 0.43%   |
| KDE4          | 9         | 0.39%   |
| ICEWM         | 8         | 0.34%   |
| LXDE          | 6         | 0.26%   |
| Budgie        | 5         | 0.21%   |
| sway          | 4         | 0.17%   |
| Deepin        | 4         | 0.17%   |
| i3            | 3         | 0.13%   |
| GNOME Classic | 3         | 0.13%   |
| WindowMaker   | 2         | 0.09%   |
| Pantheon      | 2         | 0.09%   |
| Hyprland      | 2         | 0.09%   |
| awesome       | 2         | 0.09%   |
| Trinity       | 1         | 0.04%   |
| plasma5       | 1         | 0.04%   |
| openbox       | 1         | 0.04%   |
| Herbstluftwm  | 1         | 0.04%   |
| fvwm2         | 1         | 0.04%   |
| default       | 1         | 0.04%   |
| custom        | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1795      | 77.34%  |
| Wayland     | 440       | 18.96%  |
| Tty         | 43        | 1.85%   |
| Unknown     | 41        | 1.77%   |
| Unspecified | 2         | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1010      | 43.57%  |
| LightDM | 612       | 26.4%   |
| SDDM    | 544       | 23.47%  |
| XDM     | 126       | 5.44%   |
| GDM     | 25        | 1.08%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 847       | 36.54%  |
| de_DE   | 297       | 12.81%  |
| POSIX   | 208       | 8.97%   |
| Unknown | 179       | 7.72%   |
| en_GB   | 151       | 6.51%   |
| pt_BR   | 101       | 4.36%   |
| ru_RU   | 86        | 3.71%   |
| es_ES   | 82        | 3.54%   |
| it_IT   | 52        | 2.24%   |
| fr_FR   | 48        | 2.07%   |
| pl_PL   | 31        | 1.34%   |
| nl_NL   | 21        | 0.91%   |
| pt_PT   | 20        | 0.86%   |
| zh_CN   | 14        | 0.6%    |
| cs_CZ   | 14        | 0.6%    |
| hu_HU   | 11        | 0.47%   |
| fi_FI   | 9         | 0.39%   |
| C       | 9         | 0.39%   |
| es_MX   | 7         | 0.3%    |
| sv_SE   | 6         | 0.26%   |
| nb_NO   | 6         | 0.26%   |
| es_AR   | 6         | 0.26%   |
| en_IN   | 6         | 0.26%   |
| en_IE   | 6         | 0.26%   |
| en_DE   | 6         | 0.26%   |
| nl_BE   | 5         | 0.22%   |
| es_DO   | 5         | 0.22%   |
| en_AU   | 5         | 0.22%   |
| bg_BG   | 5         | 0.22%   |
| tr_TR   | 4         | 0.17%   |
| nn_NO   | 4         | 0.17%   |
| ja_JP   | 4         | 0.17%   |
| en_DK   | 4         | 0.17%   |
| ro_RO   | 3         | 0.13%   |
| hr_HR   | 3         | 0.13%   |
| en_FI   | 3         | 0.13%   |
| en_CH   | 3         | 0.13%   |
| cv_RU   | 3         | 0.13%   |
| ca_ES   | 3         | 0.13%   |
| sk_SK   | 2         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1506      | 66.05%  |
| BIOS | 774       | 33.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Btrfs    | 1630      | 71.37%  |
| Ext4     | 471       | 20.62%  |
| Xfs      | 87        | 3.81%   |
| Unknown  | 61        | 2.67%   |
| Overlay  | 20        | 0.88%   |
| Tmpfs    | 7         | 0.31%   |
| Ext3     | 3         | 0.13%   |
| Ext2     | 2         | 0.09%   |
| Zfs      | 1         | 0.04%   |
| Reiserfs | 1         | 0.04%   |
| F2fs     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1191      | 51.74%  |
| Unknown | 929       | 40.36%  |
| MBR     | 182       | 7.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1966      | 85.4%   |
| Yes       | 336       | 14.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1713      | 74.74%  |
| Yes       | 579       | 25.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 366       | 16.21%  |
| Lenovo                  | 347       | 15.37%  |
| Hewlett-Packard         | 327       | 14.48%  |
| Dell                    | 265       | 11.74%  |
| Gigabyte Technology     | 178       | 7.88%   |
| MSI                     | 158       | 7%      |
| Acer                    | 107       | 4.74%   |
| ASRock                  | 106       | 4.69%   |
| Apple                   | 60        | 2.66%   |
| Fujitsu                 | 28        | 1.24%   |
| Toshiba                 | 24        | 1.06%   |
| Intel                   | 20        | 0.89%   |
| HUAWEI                  | 19        | 0.84%   |
| TUXEDO                  | 18        | 0.8%    |
| Sony                    | 15        | 0.66%   |
| Samsung Electronics     | 15        | 0.66%   |
| Biostar                 | 12        | 0.53%   |
| Medion                  | 11        | 0.49%   |
| Unknown                 | 10        | 0.44%   |
| Supermicro              | 9         | 0.4%    |
| Alienware               | 9         | 0.4%    |
| Notebook                | 8         | 0.35%   |
| Microsoft               | 8         | 0.35%   |
| Fujitsu Siemens         | 8         | 0.35%   |
| Pegatron                | 7         | 0.31%   |
| Google                  | 5         | 0.22%   |
| Foxconn                 | 5         | 0.22%   |
| Timi                    | 4         | 0.18%   |
| Schenker                | 4         | 0.18%   |
| Raspberry Pi Foundation | 4         | 0.18%   |
| Positivo                | 4         | 0.18%   |
| SLIMBOOK                | 3         | 0.13%   |
| Razer                   | 3         | 0.13%   |
| LG Electronics          | 3         | 0.13%   |
| Gateway                 | 3         | 0.13%   |
| Clevo                   | 3         | 0.13%   |
| BESSTAR Tech            | 3         | 0.13%   |
| Avell High Performance  | 3         | 0.13%   |
| Wortmann AG             | 2         | 0.09%   |
| TYAN Computer           | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS All Series                      | 25        | 1.11%   |
| Unknown                              | 18        | 0.8%    |
| Dell OptiPlex 9020                   | 11        | 0.49%   |
| HP Notebook                          | 9         | 0.4%    |
| Apple MacBookPro9,2                  | 9         | 0.4%    |
| MSI MS-7B86                          | 8         | 0.35%   |
| ASUS TUF Gaming X570-PLUS            | 7         | 0.31%   |
| ASRock B450M Pro4                    | 7         | 0.31%   |
| MSI MS-7C37                          | 6         | 0.27%   |
| MSI MS-7B89                          | 6         | 0.27%   |
| Gigabyte B450M DS3H                  | 6         | 0.27%   |
| Gigabyte 970A-DS3P                   | 6         | 0.27%   |
| Dell Precision 5530                  | 6         | 0.27%   |
| MSI MS-7C02                          | 5         | 0.22%   |
| MSI MS-7A34                          | 5         | 0.22%   |
| HP Pavilion dv7                      | 5         | 0.22%   |
| HP Pavilion dv6                      | 5         | 0.22%   |
| HP Laptop 17-ca0xxx                  | 5         | 0.22%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx | 5         | 0.22%   |
| Gigabyte B450 AORUS M                | 5         | 0.22%   |
| Dell Latitude 7490                   | 5         | 0.22%   |
| ASUS PRIME A320M-K                   | 5         | 0.22%   |
| ASRock X570 Steel Legend             | 5         | 0.22%   |
| TUXEDO Pulse 15 Gen1                 | 4         | 0.18%   |
| MSI MS-7C91                          | 4         | 0.18%   |
| MSI MS-7B79                          | 4         | 0.18%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 4         | 0.18%   |
| Lenovo G50-45 80E3                   | 4         | 0.18%   |
| HP Z620 Workstation                  | 4         | 0.18%   |
| HP Pavilion g6                       | 4         | 0.18%   |
| HP OMEN Laptop 15-en0xxx             | 4         | 0.18%   |
| HP OMEN by Laptop                    | 4         | 0.18%   |
| Gigabyte X570 AORUS MASTER           | 4         | 0.18%   |
| Dell XPS 15 9560                     | 4         | 0.18%   |
| Dell Latitude E7470                  | 4         | 0.18%   |
| ASUS ROG STRIX B550-F GAMING         | 4         | 0.18%   |
| ASUS PRIME B550-PLUS                 | 4         | 0.18%   |
| ASUS M5A99X EVO R2.0                 | 4         | 0.18%   |
| ASUS M5A97 R2.0                      | 4         | 0.18%   |
| ASUS M5A78L-M/USB3                   | 4         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 183       | 8.1%    |
| Acer Aspire        | 69        | 3.06%   |
| Dell Latitude      | 61        | 2.7%    |
| Dell Inspiron      | 59        | 2.61%   |
| Lenovo IdeaPad     | 54        | 2.39%   |
| ASUS PRIME         | 51        | 2.26%   |
| HP Pavilion        | 49        | 2.17%   |
| HP EliteBook       | 44        | 1.95%   |
| ASUS ROG           | 42        | 1.86%   |
| Dell OptiPlex      | 35        | 1.55%   |
| Dell XPS           | 34        | 1.51%   |
| ASUS TUF           | 32        | 1.42%   |
| HP Laptop          | 31        | 1.37%   |
| Dell Precision     | 30        | 1.33%   |
| ASUS VivoBook      | 28        | 1.24%   |
| HP ProBook         | 27        | 1.2%    |
| HP ENVY            | 26        | 1.15%   |
| ASUS All           | 25        | 1.11%   |
| Lenovo Yoga        | 22        | 0.97%   |
| HP Compaq          | 21        | 0.93%   |
| Toshiba Satellite  | 20        | 0.89%   |
| Lenovo ThinkCentre | 18        | 0.8%    |
| HP ZBook           | 18        | 0.8%    |
| Dell PowerEdge     | 18        | 0.8%    |
| Unknown            | 18        | 0.8%    |
| HP OMEN            | 16        | 0.71%   |
| Fujitsu LIFEBOOK   | 15        | 0.66%   |
| ASUS ZenBook       | 13        | 0.58%   |
| Gigabyte X570      | 12        | 0.53%   |
| Dell Vostro        | 12        | 0.53%   |
| ASRock B450M       | 11        | 0.49%   |
| Acer Swift         | 11        | 0.49%   |
| Gigabyte B550      | 10        | 0.44%   |
| ASUS ASUS          | 10        | 0.44%   |
| Lenovo Legion      | 9         | 0.4%    |
| HP Notebook        | 9         | 0.4%    |
| ASUS M5A78L-M      | 9         | 0.4%    |
| ASRock X570        | 9         | 0.4%    |
| Apple MacBookPro9  | 9         | 0.4%    |
| MSI MS-7B86        | 8         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 258       | 11.43%  |
| 2018 | 232       | 10.27%  |
| 2019 | 222       | 9.83%   |
| 2021 | 204       | 9.03%   |
| 2017 | 174       | 7.71%   |
| 2012 | 163       | 7.22%   |
| 2013 | 162       | 7.17%   |
| 2015 | 132       | 5.85%   |
| 2011 | 117       | 5.18%   |
| 2014 | 111       | 4.92%   |
| 2022 | 108       | 4.78%   |
| 2016 | 102       | 4.52%   |
| 2010 | 92        | 4.07%   |
| 2009 | 64        | 2.83%   |
| 2008 | 54        | 2.39%   |
| 2007 | 23        | 1.02%   |
| 2023 | 21        | 0.93%   |
| 2006 | 11        | 0.49%   |
| 2005 | 5         | 0.22%   |
| 2004 | 2         | 0.09%   |
| 2000 | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1162      | 51.46%  |
| Desktop        | 903       | 39.99%  |
| Convertible    | 85        | 3.76%   |
| Server         | 34        | 1.51%   |
| Mini pc        | 32        | 1.42%   |
| All in one     | 22        | 0.97%   |
| Tablet         | 13        | 0.58%   |
| System on chip | 6         | 0.27%   |
| Firewall       | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1941      | 84.72%  |
| Enabled  | 350       | 15.28%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2250      | 99.65%  |
| Yes  | 8         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 575       | 25.15%  |
| 4.01-8.0        | 492       | 21.52%  |
| 8.01-16.0       | 451       | 19.73%  |
| 32.01-64.0      | 350       | 15.31%  |
| 3.01-4.0        | 198       | 8.66%   |
| 64.01-256.0     | 97        | 4.24%   |
| 24.01-32.0      | 57        | 2.49%   |
| 1.01-2.0        | 31        | 1.36%   |
| 2.01-3.0        | 12        | 0.52%   |
| Unknown         | 10        | 0.44%   |
| 0.51-1.0        | 7         | 0.31%   |
| More than 256.0 | 4         | 0.17%   |
| 0.01-0.5        | 2         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 645       | 26.07%  |
| 4.01-8.0   | 600       | 24.25%  |
| 1.01-2.0   | 514       | 20.78%  |
| 3.01-4.0   | 427       | 17.26%  |
| 8.01-16.0  | 156       | 6.31%   |
| 0.51-1.0   | 76        | 3.07%   |
| 16.01-24.0 | 22        | 0.89%   |
| 0.01-0.5   | 16        | 0.65%   |
| Unknown    | 10        | 0.4%    |
| 24.01-32.0 | 7         | 0.28%   |
| 32.01-64.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1167      | 50.22%  |
| 2       | 619       | 26.64%  |
| 3       | 235       | 10.11%  |
| 4       | 145       | 6.24%   |
| 5       | 76        | 3.27%   |
| 6       | 40        | 1.72%   |
| 7       | 19        | 0.82%   |
| 0       | 7         | 0.3%    |
| 8       | 5         | 0.22%   |
| 13      | 3         | 0.13%   |
| 10      | 3         | 0.13%   |
| 9       | 2         | 0.09%   |
| 35      | 1         | 0.04%   |
| 16      | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1467      | 64.51%  |
| Yes       | 807       | 35.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1957      | 86.48%  |
| No        | 306       | 13.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1694      | 74.76%  |
| No        | 572       | 25.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1460      | 64.04%  |
| No        | 820       | 35.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 416       | 18.36%  |
| Germany      | 408       | 18.01%  |
| Brazil       | 143       | 6.31%   |
| Russia       | 107       | 4.72%   |
| Italy        | 89        | 3.93%   |
| UK           | 81        | 3.57%   |
| France       | 76        | 3.35%   |
| Netherlands  | 69        | 3.05%   |
| Spain        | 62        | 2.74%   |
| Canada       | 52        | 2.29%   |
| Switzerland  | 48        | 2.12%   |
| Poland       | 47        | 2.07%   |
| Australia    | 36        | 1.59%   |
| Sweden       | 35        | 1.54%   |
| India        | 34        | 1.5%    |
| Mexico       | 29        | 1.28%   |
| Belgium      | 29        | 1.28%   |
| Czechia      | 28        | 1.24%   |
| Austria      | 28        | 1.24%   |
| China        | 26        | 1.15%   |
| Hungary      | 23        | 1.02%   |
| Portugal     | 21        | 0.93%   |
| Norway       | 21        | 0.93%   |
| Finland      | 21        | 0.93%   |
| Romania      | 19        | 0.84%   |
| Bulgaria     | 17        | 0.75%   |
| Ukraine      | 16        | 0.71%   |
| Turkey       | 16        | 0.71%   |
| Argentina    | 16        | 0.71%   |
| Greece       | 15        | 0.66%   |
| Serbia       | 13        | 0.57%   |
| Chile        | 13        | 0.57%   |
| Peru         | 10        | 0.44%   |
| Indonesia    | 10        | 0.44%   |
| South Africa | 9         | 0.4%    |
| Japan        | 9         | 0.4%    |
| Colombia     | 9         | 0.4%    |
| Belarus      | 9         | 0.4%    |
| Thailand     | 8         | 0.35%   |
| Luxembourg   | 8         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 32        | 1.34%   |
| Moscow            | 31        | 1.3%    |
| Rio de Janeiro    | 19        | 0.8%    |
| Munich            | 17        | 0.71%   |
| Vienna            | 16        | 0.67%   |
| Sao Paulo         | 16        | 0.67%   |
| Prague            | 15        | 0.63%   |
| Zurich            | 14        | 0.59%   |
| Sydney            | 14        | 0.59%   |
| St Petersburg     | 14        | 0.59%   |
| Paris             | 14        | 0.59%   |
| Milan             | 14        | 0.59%   |
| Frankfurt am Main | 14        | 0.59%   |
| Budapest          | 14        | 0.59%   |
| Amsterdam         | 14        | 0.59%   |
| Warsaw            | 12        | 0.5%    |
| Los Angeles       | 12        | 0.5%    |
| Hamburg           | 12        | 0.5%    |
| Littleton         | 11        | 0.46%   |
| Madrid            | 10        | 0.42%   |
| Stuttgart         | 9         | 0.38%   |
| Sofia             | 9         | 0.38%   |
| Neuchatel         | 9         | 0.38%   |
| Melbourne         | 9         | 0.38%   |
| Rome              | 8         | 0.34%   |
| Riverton          | 8         | 0.34%   |
| Cologne           | 8         | 0.34%   |
| Bengaluru         | 8         | 0.34%   |
| Belgrade          | 8         | 0.34%   |
| Athens            | 8         | 0.34%   |
| Stockholm         | 7         | 0.29%   |
| Santiago          | 7         | 0.29%   |
| Montreal          | 7         | 0.29%   |
| Mexico City       | 7         | 0.29%   |
| Houston           | 7         | 0.29%   |
| Gothenburg        | 7         | 0.29%   |
| Essen             | 7         | 0.29%   |
| Barcelona         | 7         | 0.29%   |
| The Hague         | 6         | 0.25%   |
| Schrobenhausen    | 6         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 713       | 1114   | 19.17%  |
| Seagate                     | 537       | 933    | 14.44%  |
| WDC                         | 525       | 907    | 14.12%  |
| Toshiba                     | 226       | 291    | 6.08%   |
| Kingston                    | 203       | 264    | 5.46%   |
| SanDisk                     | 198       | 265    | 5.32%   |
| Crucial                     | 161       | 212    | 4.33%   |
| Intel                       | 101       | 129    | 2.72%   |
| SK hynix                    | 98        | 140    | 2.64%   |
| Unknown                     | 87        | 123    | 2.34%   |
| Hitachi                     | 75        | 87     | 2.02%   |
| Micron Technology           | 57        | 68     | 1.53%   |
| HGST                        | 56        | 78     | 1.51%   |
| A-DATA Technology           | 41        | 53     | 1.1%    |
| Phison Electronics          | 31        | 39     | 0.83%   |
| KIOXIA                      | 30        | 34     | 0.81%   |
| Silicon Motion              | 29        | 30     | 0.78%   |
| SPCC                        | 26        | 34     | 0.7%    |
| PNY                         | 26        | 34     | 0.7%    |
| Phison                      | 25        | 35     | 0.67%   |
| China                       | 25        | 27     | 0.67%   |
| Apple                       | 25        | 30     | 0.67%   |
| Intenso                     | 24        | 35     | 0.65%   |
| Micron/Crucial Technology   | 20        | 27     | 0.54%   |
| Kingston Technology Company | 19        | 20     | 0.51%   |
| Hewlett-Packard             | 15        | 29     | 0.4%    |
| Transcend                   | 14        | 16     | 0.38%   |
| LITEON                      | 13        | 14     | 0.35%   |
| Fujitsu                     | 13        | 16     | 0.35%   |
| Corsair                     | 12        | 13     | 0.32%   |
| Patriot                     | 11        | 12     | 0.3%    |
| OCZ                         | 11        | 16     | 0.3%    |
| JMicron Technology          | 10        | 10     | 0.27%   |
| Team                        | 9         | 12     | 0.24%   |
| Maxtor                      | 9         | 9      | 0.24%   |
| GOODRAM                     | 9         | 9      | 0.24%   |
| ADATA Technology            | 8         | 10     | 0.22%   |
| XrayDisk                    | 7         | 7      | 0.19%   |
| XPG                         | 7         | 9      | 0.19%   |
| Realtek Semiconductor       | 7         | 7      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 59        | 1.39%   |
| Samsung SSD 860 EVO 500GB                             | 49        | 1.16%   |
| Samsung SSD 850 EVO 250GB                             | 37        | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 37        | 0.87%   |
| Samsung SSD 860 EVO 1TB                               | 34        | 0.8%    |
| Seagate ST2000DM008-2FR102 2TB                        | 32        | 0.76%   |
| Kingston SA400S37480G 480GB SSD                       | 31        | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 28        | 0.66%   |
| Kingston SA400S37240G 240GB SSD                       | 28        | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB                        | 26        | 0.61%   |
| Crucial CT500MX500SSD1 500GB                          | 26        | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB                        | 24        | 0.57%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 22        | 0.52%   |
| Samsung SSD 850 EVO 500GB                             | 22        | 0.52%   |
| Samsung SSD 840 EVO 250GB                             | 21        | 0.5%    |
| Kingston SA400S37120G 120GB SSD                       | 21        | 0.5%    |
| HGST HTS721010A9E630 1TB                              | 21        | 0.5%    |
| Seagate ST500DM002-1BD142 500GB                       | 20        | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB                        | 20        | 0.47%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 19        | 0.45%   |
| Toshiba MQ01ABD100 1TB                                | 18        | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                          | 18        | 0.42%   |
| Unknown SD/MMC/MS PRO 1GB                             | 17        | 0.4%    |
| Seagate ST1000DM003-1CH162 1TB                        | 17        | 0.4%    |
| Samsung SSD 860 EVO 250GB                             | 17        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                          | 17        | 0.4%    |
| Toshiba MQ04ABF100 1TB                                | 16        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB                           | 16        | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 15        | 0.35%   |
| Toshiba DT01ACA100 1TB                                | 15        | 0.35%   |
| Seagate Expansion 2TB                                 | 15        | 0.35%   |
| Samsung SSD 970 EVO 500GB                             | 15        | 0.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 15        | 0.35%   |
| Seagate ST3500418AS 500GB                             | 14        | 0.33%   |
| Samsung SSD 970 EVO Plus 500GB                        | 14        | 0.33%   |
| Samsung SSD 860 QVO 1TB                               | 14        | 0.33%   |
| Samsung SSD 850 PRO 256GB                             | 14        | 0.33%   |
| Samsung NVMe SSD Drive 1TB                            | 14        | 0.33%   |
| Kingston SV300S37A120G 120GB SSD                      | 14        | 0.33%   |
| Samsung NVMe SSD Drive 500GB                          | 13        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 526       | 905    | 37.65%  |
| WDC                 | 422       | 726    | 30.21%  |
| Toshiba             | 158       | 210    | 11.31%  |
| Hitachi             | 75        | 87     | 5.37%   |
| Samsung Electronics | 73        | 111    | 5.23%   |
| HGST                | 56        | 78     | 4.01%   |
| Unknown             | 18        | 20     | 1.29%   |
| Fujitsu             | 13        | 16     | 0.93%   |
| Apple               | 9         | 11     | 0.64%   |
| Maxtor              | 8         | 8      | 0.57%   |
| Hewlett-Packard     | 6         | 18     | 0.43%   |
| SABRENT             | 5         | 6      | 0.36%   |
| WD MediaMax         | 3         | 3      | 0.21%   |
| SSK                 | 3         | 4      | 0.21%   |
| Intenso             | 3         | 8      | 0.21%   |
| USB3.0              | 2         | 3      | 0.14%   |
| Pioneer             | 2         | 7      | 0.14%   |
| JMicron Technology  | 2         | 2      | 0.14%   |
| USB                 | 1         | 1      | 0.07%   |
| UD0401              | 1         | 1      | 0.07%   |
| Synology            | 1         | 1      | 0.07%   |
| Maxone              | 1         | 1      | 0.07%   |
| MaxDigital          | 1         | 1      | 0.07%   |
| Magnetic Data       | 1         | 2      | 0.07%   |
| Inateck             | 1         | 1      | 0.07%   |
| IBM-207x            | 1         | 8      | 0.07%   |
| IB-377U3            | 1         | 1      | 0.07%   |
| HGST HTS            | 1         | 1      | 0.07%   |
| DELLBOSS            | 1         | 1      | 0.07%   |
| ASMT                | 1         | 2      | 0.07%   |
| ASMedia             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 354       | 526    | 27.61%  |
| Kingston            | 153       | 200    | 11.93%  |
| Crucial             | 149       | 195    | 11.62%  |
| SanDisk             | 112       | 141    | 8.74%   |
| WDC                 | 88        | 117    | 6.86%   |
| Intel               | 30        | 41     | 2.34%   |
| A-DATA Technology   | 30        | 37     | 2.34%   |
| Toshiba             | 26        | 31     | 2.03%   |
| China               | 25        | 27     | 1.95%   |
| SK hynix            | 21        | 32     | 1.64%   |
| PNY                 | 21        | 25     | 1.64%   |
| SPCC                | 20        | 28     | 1.56%   |
| Micron Technology   | 20        | 28     | 1.56%   |
| Intenso             | 19        | 23     | 1.48%   |
| LITEON              | 13        | 14     | 1.01%   |
| Apple               | 13        | 16     | 1.01%   |
| Transcend           | 11        | 13     | 0.86%   |
| Patriot             | 11        | 12     | 0.86%   |
| OCZ                 | 11        | 16     | 0.86%   |
| Team                | 8         | 11     | 0.62%   |
| GOODRAM             | 8         | 8      | 0.62%   |
| Corsair             | 8         | 8      | 0.62%   |
| Seagate             | 6         | 7      | 0.47%   |
| LITEONIT            | 6         | 6      | 0.47%   |
| JMicron Technology  | 6         | 6      | 0.47%   |
| Hewlett-Packard     | 6         | 8      | 0.47%   |
| XrayDisk            | 5         | 5      | 0.39%   |
| Plextor             | 5         | 8      | 0.39%   |
| KingSpec            | 5         | 10     | 0.39%   |
| TO Exter            | 4         | 4      | 0.31%   |
| Mushkin             | 4         | 7      | 0.31%   |
| Leven               | 4         | 4      | 0.31%   |
| Apacer              | 4         | 7      | 0.31%   |
| Smartbuy            | 3         | 5      | 0.23%   |
| Netac               | 3         | 3      | 0.23%   |
| Gigabyte Technology | 3         | 6      | 0.23%   |
| Fanxiang            | 3         | 6      | 0.23%   |
| Biostar             | 3         | 5      | 0.23%   |
| ASMT                | 3         | 3      | 0.23%   |
| Unknown             | 3         | 3      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1099      | 2245   | 33.93%  |
| SSD     | 1087      | 1715   | 33.56%  |
| NVMe    | 948       | 1369   | 29.27%  |
| MMC     | 64        | 88     | 1.98%   |
| Unknown | 41        | 52     | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1639      | 3780   | 58.56%  |
| NVMe | 948       | 1366   | 33.87%  |
| SAS  | 148       | 235    | 5.29%   |
| MMC  | 64        | 88     | 2.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1181      | 1933   | 49.46%  |
| 0.51-1.0   | 722       | 1176   | 30.23%  |
| 1.01-2.0   | 288       | 498    | 12.06%  |
| 3.01-4.0   | 71        | 132    | 2.97%   |
| 2.01-3.0   | 67        | 109    | 2.81%   |
| 4.01-10.0  | 50        | 98     | 2.09%   |
| 10.01-20.0 | 9         | 14     | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 754       | 32%     |
| 1001-2000      | 511       | 21.69%  |
| 501-1000       | 344       | 14.6%   |
| 2001-3000      | 297       | 12.61%  |
| 251-500        | 210       | 8.91%   |
| 101-250        | 124       | 5.26%   |
| Unknown        | 45        | 1.91%   |
| 51-100         | 34        | 1.44%   |
| 1-20           | 19        | 0.81%   |
| 21-50          | 18        | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 488       | 19.92%  |
| 251-500        | 417       | 17.02%  |
| 51-100         | 379       | 15.47%  |
| 501-1000       | 327       | 13.35%  |
| 1001-2000      | 293       | 11.96%  |
| More than 3000 | 147       | 6%      |
| 1-20           | 134       | 5.47%   |
| 21-50          | 114       | 4.65%   |
| 2001-3000      | 105       | 4.29%   |
| Unknown        | 45        | 1.84%   |
| 0              | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7         | 9      | 2.47%   |
| Seagate ST3500418AS 500GB             | 5         | 5      | 1.77%   |
| Samsung Electronics SSD 840 EVO 120GB | 5         | 6      | 1.77%   |
| Seagate ST2000DM001-1ER164 2TB        | 4         | 4      | 1.41%   |
| Seagate ST2000DM001-1CH164 2TB        | 4         | 5      | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 4      | 1.41%   |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 1.41%   |
| WDC WD10JFCX-68N6GN0 1TB              | 3         | 4      | 1.06%   |
| Toshiba MQ01ABD100 1TB                | 3         | 3      | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 1.06%   |
| Seagate ST1000DM003-1SB102 1TB        | 3         | 4      | 1.06%   |
| Samsung Electronics HD501LJ 500GB     | 3         | 4      | 1.06%   |
| WDC WD6400AAKS-22A7B2 640GB           | 2         | 2      | 0.71%   |
| WDC WD20EZRX-00DC0B0 2TB              | 2         | 3      | 0.71%   |
| WDC WD20EFRX-68EUZN0 2TB              | 2         | 2      | 0.71%   |
| WD MediaMax WL5000GSA12872B 5TB       | 2         | 2      | 0.71%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 0.71%   |
| Toshiba MK5055GSX 500GB               | 2         | 4      | 0.71%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.71%   |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 2      | 0.71%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 0.71%   |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 0.71%   |
| Seagate ST31000528AS 1TB              | 2         | 5      | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB        | 2         | 2      | 0.71%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD   | 2         | 2      | 0.71%   |
| Samsung Electronics HN-M500MBB 500GB  | 2         | 2      | 0.71%   |
| Samsung Electronics HD322HJ 320GB     | 2         | 2      | 0.71%   |
| Samsung Electronics HD103SJ 1TB       | 2         | 3      | 0.71%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 3      | 0.71%   |
| Kingston SMS200S3240G 240GB SSD       | 2         | 2      | 0.71%   |
| Kingston SHFS37A120G 120GB SSD        | 2         | 2      | 0.71%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.71%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 0.71%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.71%   |
| Crucial CT1000P1SSD8 1TB              | 2         | 2      | 0.71%   |
| XrayDisk SSD 256GB                    | 1         | 1      | 0.35%   |
| XPG GAMMIX S41 256GB                  | 1         | 1      | 0.35%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.35%   |
| WDC WD800AAJS-75M0A0 80GB             | 1         | 1      | 0.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 74        | 91     | 26.91%  |
| WDC                      | 51        | 60     | 18.55%  |
| Samsung Electronics      | 33        | 42     | 12%     |
| Toshiba                  | 26        | 36     | 9.45%   |
| Hitachi                  | 13        | 15     | 4.73%   |
| Kingston                 | 10        | 17     | 3.64%   |
| Crucial                  | 10        | 11     | 3.64%   |
| Intel                    | 7         | 8      | 2.55%   |
| HGST                     | 7         | 7      | 2.55%   |
| SanDisk                  | 6         | 6      | 2.18%   |
| Maxtor                   | 4         | 4      | 1.45%   |
| WD MediaMax              | 2         | 2      | 0.73%   |
| Transcend                | 2         | 3      | 0.73%   |
| SK hynix                 | 2         | 2      | 0.73%   |
| Patriot                  | 2         | 2      | 0.73%   |
| OCZ                      | 2         | 2      | 0.73%   |
| Micron Technology        | 2         | 2      | 0.73%   |
| LITEONIT                 | 2         | 2      | 0.73%   |
| Fujitsu                  | 2         | 3      | 0.73%   |
| Corsair                  | 2         | 2      | 0.73%   |
| XrayDisk                 | 1         | 1      | 0.36%   |
| XPG                      | 1         | 1      | 0.36%   |
| SuperTalent              | 1         | 1      | 0.36%   |
| SSSTC                    | 1         | 1      | 0.36%   |
| SPCC                     | 1         | 1      | 0.36%   |
| Silicon Motion           | 1         | 1      | 0.36%   |
| Phison                   | 1         | 1      | 0.36%   |
| Netac                    | 1         | 1      | 0.36%   |
| LEQIXIANG                | 1         | 1      | 0.36%   |
| KingFast                 | 1         | 1      | 0.36%   |
| Intenso                  | 1         | 1      | 0.36%   |
| Hewlett-Packard          | 1         | 1      | 0.36%   |
| GOODRAM                  | 1         | 1      | 0.36%   |
| Biwin Storage Technology | 1         | 1      | 0.36%   |
| Apple                    | 1         | 1      | 0.36%   |
| A-DATA Technology        | 1         | 2      | 0.36%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 74        | 91     | 37.95%  |
| WDC                 | 49        | 58     | 25.13%  |
| Toshiba             | 25        | 35     | 12.82%  |
| Samsung Electronics | 17        | 23     | 8.72%   |
| Hitachi             | 13        | 15     | 6.67%   |
| HGST                | 7         | 7      | 3.59%   |
| Maxtor              | 4         | 4      | 2.05%   |
| WD MediaMax         | 2         | 2      | 1.03%   |
| Fujitsu             | 2         | 3      | 1.03%   |
| Hewlett-Packard     | 1         | 1      | 0.51%   |
| Apple               | 1         | 1      | 0.51%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 176       | 240    | 69.29%  |
| SSD  | 63        | 79     | 24.8%   |
| NVMe | 15        | 15     | 5.91%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EADS-00R6B0 2TB           | 1         | 1      | 25%     |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 25%     |
| Samsung Electronics HD502HJ 500GB | 1         | 5      | 25%     |
| Hitachi HDS721025CLA382 250GB     | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 6      | 50%     |
| WDC                 | 1         | 1      | 25%     |
| Hitachi             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1270      | 2651   | 50.08%  |
| Detected | 1019      | 2476   | 40.18%  |
| Malfunc  | 243       | 334    | 9.58%   |
| Failed   | 4         | 8      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1341      | 42.71%  |
| AMD                                     | 595       | 18.95%  |
| Samsung Electronics                     | 353       | 11.24%  |
| SanDisk                                 | 137       | 4.36%   |
| SK hynix                                | 77        | 2.45%   |
| Kingston Technology Company             | 73        | 2.32%   |
| ASMedia Technology                      | 67        | 2.13%   |
| Phison Electronics                      | 64        | 2.04%   |
| Toshiba America Info Systems            | 47        | 1.5%    |
| Micron Technology                       | 38        | 1.21%   |
| Marvell Technology Group                | 38        | 1.21%   |
| Silicon Motion                          | 34        | 1.08%   |
| JMicron Technology                      | 34        | 1.08%   |
| Micron/Crucial Technology               | 32        | 1.02%   |
| Nvidia                                  | 30        | 0.96%   |
| KIOXIA                                  | 28        | 0.89%   |
| LSI Logic / Symbios Logic               | 20        | 0.64%   |
| ADATA Technology                        | 19        | 0.61%   |
| Broadcom / LSI                          | 16        | 0.51%   |
| Realtek Semiconductor                   | 13        | 0.41%   |
| Solid State Storage Technology          | 9         | 0.29%   |
| MAXIO Technology (Hangzhou)             | 8         | 0.25%   |
| Seagate Technology                      | 7         | 0.22%   |
| Union Memory (Shenzhen)                 | 6         | 0.19%   |
| Silicon Image                           | 6         | 0.19%   |
| Adaptec                                 | 6         | 0.19%   |
| VIA Technologies                        | 5         | 0.16%   |
| Shenzhen Longsys Electronics            | 5         | 0.16%   |
| Yangtze Memory Technologies             | 4         | 0.13%   |
| Lite-On Technology                      | 3         | 0.1%    |
| Lenovo                                  | 3         | 0.1%    |
| INNOGRIT                                | 3         | 0.1%    |
| Apple                                   | 3         | 0.1%    |
| Promise Technology                      | 2         | 0.06%   |
| Hewlett-Packard                         | 2         | 0.06%   |
| Biwin Storage Technology                | 2         | 0.06%   |
| Tekram Technology                       | 1         | 0.03%   |
| Solidigm                                | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 401       | 11.15%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 182       | 5.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 117       | 3.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 115       | 3.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 88        | 2.45%   |
| AMD 400 Series Chipset SATA Controller                                         | 87        | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 69        | 1.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 67        | 1.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 63        | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                         | 63        | 1.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 62        | 1.72%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 61        | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 56        | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 54        | 1.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 53        | 1.47%   |
| Samsung NVMe SSD Controller 980                                                | 53        | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 50        | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 41        | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 40        | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 40        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 39        | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 37        | 1.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 37        | 1.03%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 36        | 1%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 36        | 1%      |
| Intel SSD 660P Series                                                          | 35        | 0.97%   |
| Phison E12 NVMe Controller                                                     | 34        | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 33        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 33        | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 32        | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 32        | 0.89%   |
| AMD 300 Series Chipset SATA Controller                                         | 32        | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 29        | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 28        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                          | 26        | 0.72%   |
| Intel SATA Controller [RAID mode]                                              | 25        | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                            | 22        | 0.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 21        | 0.58%   |
| AMD FCH SATA Controller D                                                      | 21        | 0.58%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 20        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1699      | 54.56%  |
| NVMe | 941       | 30.22%  |
| IDE  | 231       | 7.42%   |
| RAID | 209       | 6.71%   |
| SAS  | 21        | 0.67%   |
| SCSI | 13        | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 1514      | 67.05%  |
| AMD       | 736       | 32.6%   |
| ARM       | 7         | 0.31%   |
| HISILICON | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 31        | 1.37%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 26        | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 1.11%   |
| AMD Ryzen 5 3600 6-Core Processor             | 24        | 1.06%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 21        | 0.93%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 21        | 0.93%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 20        | 0.88%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 20        | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 19        | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 19        | 0.84%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 18        | 0.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 18        | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 18        | 0.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 0.75%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 17        | 0.75%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 17        | 0.75%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 16        | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.66%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 15        | 0.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 15        | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 15        | 0.66%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 15        | 0.66%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 15        | 0.66%   |
| AMD FX-8350 Eight-Core Processor              | 15        | 0.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 0.62%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 14        | 0.62%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 0.62%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 13        | 0.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 13        | 0.57%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 12        | 0.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 12        | 0.53%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 12        | 0.53%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 11        | 0.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 11        | 0.49%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 11        | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 11        | 0.49%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 11        | 0.49%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 11        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 471       | 20.84%  |
| Intel Core i5           | 438       | 19.38%  |
| AMD Ryzen 5             | 212       | 9.38%   |
| Other                   | 193       | 8.54%   |
| AMD Ryzen 7             | 170       | 7.52%   |
| Intel Core i3           | 110       | 4.87%   |
| Intel Xeon              | 86        | 3.81%   |
| AMD Ryzen 9             | 64        | 2.83%   |
| Intel Core 2 Duo        | 56        | 2.48%   |
| AMD FX                  | 49        | 2.17%   |
| Intel Celeron           | 48        | 2.12%   |
| Intel Pentium           | 33        | 1.46%   |
| AMD Ryzen 3             | 30        | 1.33%   |
| AMD Ryzen 7 PRO         | 21        | 0.93%   |
| Intel Core i9           | 18        | 0.8%    |
| AMD Phenom II X4        | 18        | 0.8%    |
| AMD A10                 | 18        | 0.8%    |
| AMD A8                  | 17        | 0.75%   |
| Intel Atom              | 15        | 0.66%   |
| AMD A6                  | 15        | 0.66%   |
| Intel Core 2 Quad       | 14        | 0.62%   |
| Intel Pentium Silver    | 13        | 0.58%   |
| Intel Pentium Dual-Core | 13        | 0.58%   |
| AMD Athlon              | 13        | 0.58%   |
| AMD Ryzen 5 PRO         | 11        | 0.49%   |
| AMD Phenom II X6        | 10        | 0.44%   |
| AMD Athlon II X2        | 8         | 0.35%   |
| AMD A4                  | 8         | 0.35%   |
| AMD Ryzen Threadripper  | 7         | 0.31%   |
| AMD Opteron             | 7         | 0.31%   |
| Intel Core 2            | 6         | 0.27%   |
| AMD E2                  | 5         | 0.22%   |
| AMD Ryzen 3 PRO         | 4         | 0.18%   |
| Intel Pentium Dual      | 3         | 0.13%   |
| Intel Genuine           | 3         | 0.13%   |
| AMD EPYC                | 3         | 0.13%   |
| AMD E                   | 3         | 0.13%   |
| AMD Athlon II X3        | 3         | 0.13%   |
| AMD Athlon 64 X2        | 3         | 0.13%   |
| Intel Xeon Silver       | 2         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 826       | 36.5%   |
| 2       | 675       | 29.83%  |
| 6       | 291       | 12.86%  |
| 8       | 260       | 11.49%  |
| 12      | 60        | 2.65%   |
| 16      | 35        | 1.55%   |
| 1       | 32        | 1.41%   |
| 10      | 22        | 0.97%   |
| 3       | 17        | 0.75%   |
| 14      | 14        | 0.62%   |
| 24      | 11        | 0.49%   |
| 32      | 6         | 0.27%   |
| Unknown | 4         | 0.18%   |
| 40      | 3         | 0.13%   |
| 20      | 2         | 0.09%   |
| 64      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 44      | 1         | 0.04%   |
| 36      | 1         | 0.04%   |
| 18      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2213      | 97.96%  |
| 2       | 37        | 1.64%   |
| 4       | 6         | 0.27%   |
| Unknown | 3         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1717      | 75.91%  |
| 1       | 539       | 23.83%  |
| Unknown | 4         | 0.18%   |
| 8       | 2         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2199      | 97.13%  |
| Unknown        | 56        | 2.47%   |
| 32-bit         | 7         | 0.31%   |
| 64-bit         | 2         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 506       | 21.86%  |
| 0x306c3    | 102       | 4.41%   |
| 0x206a7    | 96        | 4.15%   |
| 0x306a9    | 94        | 4.06%   |
| 0x806c1    | 65        | 2.81%   |
| 0x906ea    | 61        | 2.63%   |
| 0x506e3    | 57        | 2.46%   |
| 0x08701021 | 51        | 2.2%    |
| 0x406e3    | 50        | 2.16%   |
| 0x0a50000c | 49        | 2.12%   |
| 0x806ec    | 48        | 2.07%   |
| 0x906e9    | 43        | 1.86%   |
| 0x806ea    | 43        | 1.86%   |
| 0x0800820d | 43        | 1.86%   |
| 0x1067a    | 40        | 1.73%   |
| 0x08108109 | 40        | 1.73%   |
| 0x806e9    | 39        | 1.68%   |
| 0x40651    | 37        | 1.6%    |
| 0x08600106 | 36        | 1.56%   |
| 0x06000852 | 36        | 1.56%   |
| 0x306d4    | 32        | 1.38%   |
| 0x08608103 | 27        | 1.17%   |
| 0x010000c8 | 24        | 1.04%   |
| 0x0a50000d | 23        | 0.99%   |
| 0x20655    | 22        | 0.95%   |
| 0x08108102 | 20        | 0.86%   |
| 0x08001138 | 20        | 0.86%   |
| 0x08600104 | 19        | 0.82%   |
| 0x906a3    | 18        | 0.78%   |
| 0x0a201009 | 17        | 0.73%   |
| 0x08701013 | 17        | 0.73%   |
| 0x06001119 | 17        | 0.73%   |
| 0x0a20120a | 15        | 0.65%   |
| 0x0810100b | 15        | 0.65%   |
| 0x806eb    | 14        | 0.6%    |
| 0x906ed    | 13        | 0.56%   |
| 0x706a8    | 13        | 0.56%   |
| 0x806d1    | 12        | 0.52%   |
| 0x706e5    | 12        | 0.52%   |
| 0x706a1    | 12        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 347       | 15.35%  |
| Haswell          | 210       | 9.29%   |
| Zen 2            | 148       | 6.55%   |
| IvyBridge        | 147       | 6.5%    |
| Skylake          | 145       | 6.41%   |
| SandyBridge      | 130       | 5.75%   |
| Zen 3            | 126       | 5.57%   |
| Zen+             | 113       | 5%      |
| Unknown          | 84        | 3.72%   |
| TigerLake        | 83        | 3.67%   |
| Zen              | 79        | 3.49%   |
| Penryn           | 69        | 3.05%   |
| Piledriver       | 61        | 2.7%    |
| Alderlake Hybrid | 58        | 2.57%   |
| Westmere         | 53        | 2.34%   |
| K10              | 51        | 2.26%   |
| Broadwell        | 45        | 1.99%   |
| Icelake          | 44        | 1.95%   |
| CometLake        | 39        | 1.72%   |
| Core             | 35        | 1.55%   |
| Goldmont plus    | 33        | 1.46%   |
| Nehalem          | 27        | 1.19%   |
| Excavator        | 22        | 0.97%   |
| Silvermont       | 14        | 0.62%   |
| Steamroller      | 13        | 0.57%   |
| Puma             | 11        | 0.49%   |
| Bulldozer        | 10        | 0.44%   |
| Jaguar           | 9         | 0.4%    |
| Bonnell          | 9         | 0.4%    |
| Bobcat           | 9         | 0.4%    |
| Goldmont         | 8         | 0.35%   |
| K8 Hammer        | 7         | 0.31%   |
| K10 Llano        | 7         | 0.31%   |
| Tremont          | 4         | 0.18%   |
| P6               | 3         | 0.13%   |
| K8 & K10 hybrid  | 3         | 0.13%   |
| Gracemont        | 3         | 0.13%   |
| NetBurst         | 2         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1139      | 42.44%  |
| Nvidia                     | 767       | 28.58%  |
| AMD                        | 752       | 28.02%  |
| Matrox Electronics Systems | 17        | 0.63%   |
| ASPEED Technology          | 6         | 0.22%   |
| S3 Graphics                | 2         | 0.07%   |
| VIA Technologies           | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 85        | 3.06%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 77        | 2.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 76        | 2.73%   |
| AMD Renoir                                                                  | 70        | 2.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 67        | 2.41%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 64        | 2.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 63        | 2.27%   |
| Intel UHD Graphics 620                                                      | 62        | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 62        | 2.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 51        | 1.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 51        | 1.84%   |
| Intel HD Graphics 620                                                       | 50        | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 49        | 1.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 45        | 1.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 44        | 1.58%   |
| Intel HD Graphics 530                                                       | 41        | 1.48%   |
| AMD Lucienne                                                                | 39        | 1.4%    |
| Intel HD Graphics 630                                                       | 34        | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                         | 33        | 1.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 30        | 1.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 30        | 1.08%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 29        | 1.04%   |
| Intel HD Graphics 5500                                                      | 28        | 1.01%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 26        | 0.94%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 21        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 19        | 0.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 19        | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 18        | 0.65%   |
| AMD Rembrandt [Radeon 680M]                                                 | 18        | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 17        | 0.61%   |
| Nvidia GK208B [GeForce GT 710]                                              | 17        | 0.61%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 16        | 0.58%   |
| Nvidia GK208B [GeForce GT 730]                                              | 15        | 0.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 15        | 0.54%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 15        | 0.54%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 14        | 0.5%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 14        | 0.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 14        | 0.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 14        | 0.5%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 14        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 775       | 34.13%  |
| 1 x AMD            | 592       | 26.07%  |
| 1 x Nvidia         | 408       | 17.97%  |
| Intel + Nvidia     | 285       | 12.55%  |
| AMD + Nvidia       | 61        | 2.69%   |
| Intel + AMD        | 51        | 2.25%   |
| 2 x AMD            | 48        | 2.11%   |
| 1 x Matrox         | 14        | 0.62%   |
| Other              | 9         | 0.4%    |
| 2 x Nvidia         | 9         | 0.4%    |
| 2 x Intel          | 5         | 0.22%   |
| Nvidia + ASPEED    | 3         | 0.13%   |
| 1 x ASPEED         | 3         | 0.13%   |
| 1 x S3 Graphics    | 2         | 0.09%   |
| Nvidia + Matrox    | 2         | 0.09%   |
| 1 x VIA            | 1         | 0.04%   |
| Intel + 2 x Nvidia | 1         | 0.04%   |
| AMD + 2 x Nvidia   | 1         | 0.04%   |
| AMD + Matrox       | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1820      | 79.62%  |
| Proprietary | 419       | 18.33%  |
| Unknown     | 47        | 2.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1095      | 47.4%   |
| 1.01-2.0   | 283       | 12.25%  |
| 0.01-0.5   | 276       | 11.95%  |
| 3.01-4.0   | 190       | 8.23%   |
| 0.51-1.0   | 161       | 6.97%   |
| 7.01-8.0   | 156       | 6.75%   |
| 5.01-6.0   | 59        | 2.55%   |
| 8.01-16.0  | 59        | 2.55%   |
| 2.01-3.0   | 20        | 0.87%   |
| 16.01-24.0 | 9         | 0.39%   |
| 4.01-5.0   | 1         | 0.04%   |
| 24.01-32.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 313       | 11.99%  |
| AU Optronics            | 286       | 10.95%  |
| BOE                     | 216       | 8.27%   |
| Chimei Innolux          | 211       | 8.08%   |
| LG Display              | 192       | 7.35%   |
| Dell                    | 187       | 7.16%   |
| Goldstar                | 158       | 6.05%   |
| Hewlett-Packard         | 104       | 3.98%   |
| Acer                    | 84        | 3.22%   |
| Ancor Communications    | 80        | 3.06%   |
| BenQ                    | 76        | 2.91%   |
| AOC                     | 62        | 2.37%   |
| Philips                 | 54        | 2.07%   |
| Lenovo                  | 51        | 1.95%   |
| Apple                   | 50        | 1.91%   |
| Sharp                   | 49        | 1.88%   |
| PANDA                   | 27        | 1.03%   |
| ASUSTek Computer        | 27        | 1.03%   |
| InfoVision              | 25        | 0.96%   |
| Iiyama                  | 25        | 0.96%   |
| ViewSonic               | 24        | 0.92%   |
| Chi Mei Optoelectronics | 20        | 0.77%   |
| Fujitsu Siemens         | 18        | 0.69%   |
| Unknown                 | 17        | 0.65%   |
| Eizo                    | 16        | 0.61%   |
| LG Electronics          | 14        | 0.54%   |
| Sony                    | 13        | 0.5%    |
| Vizio                   | 9         | 0.34%   |
| Panasonic               | 9         | 0.34%   |
| Sceptre Tech            | 8         | 0.31%   |
| NEC Computers           | 8         | 0.31%   |
| LG Philips              | 8         | 0.31%   |
| CSO                     | 8         | 0.31%   |
| Pixio                   | 7         | 0.27%   |
| MSI                     | 7         | 0.27%   |
| Medion                  | 7         | 0.27%   |
| Insignia                | 6         | 0.23%   |
| HUAWEI                  | 6         | 0.23%   |
| Gigabyte Technology     | 6         | 0.23%   |
| TMX                     | 5         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 13        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 13        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 13        | 0.48%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 9         | 0.33%   |
| BenQ GW2760HS BNQ78CA 1920x1080 600x340mm 27.2-inch                   | 9         | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 8         | 0.29%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 8         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 8         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 8         | 0.29%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 7         | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 7         | 0.26%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 7         | 0.26%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 6         | 0.22%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 6         | 0.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 6         | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 6         | 0.22%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 6         | 0.22%   |
| Fujitsu Siemens P19-2 FUS0552 1280x1024 376x301mm 19.0-inch           | 6         | 0.22%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                      | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 6         | 0.22%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 6         | 0.22%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 6         | 0.22%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 5         | 0.18%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 5         | 0.18%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 5         | 0.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 5         | 0.18%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch               | 5         | 0.18%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5         | 0.18%   |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                      | 5         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1208      | 48.15%  |
| 1366x768 (WXGA)    | 297       | 11.84%  |
| 2560x1440 (QHD)    | 168       | 6.7%    |
| 3840x2160 (4K)     | 167       | 6.66%   |
| 1600x900 (HD+)     | 87        | 3.47%   |
| 1920x1200 (WUXGA)  | 80        | 3.19%   |
| 1280x1024 (SXGA)   | 68        | 2.71%   |
| 1680x1050 (WSXGA+) | 58        | 2.31%   |
| 1440x900 (WXGA+)   | 44        | 1.75%   |
| 1280x800 (WXGA)    | 44        | 1.75%   |
| 2560x1080          | 42        | 1.67%   |
| 3440x1440          | 30        | 1.2%    |
| Unknown            | 29        | 1.16%   |
| 2560x1600          | 27        | 1.08%   |
| 3840x1080          | 18        | 0.72%   |
| 1024x768 (XGA)     | 16        | 0.64%   |
| 2880x1800          | 15        | 0.6%    |
| 1360x768           | 11        | 0.44%   |
| 1920x540           | 7         | 0.28%   |
| 3200x1800 (QHD+)   | 6         | 0.24%   |
| 2160x1440          | 6         | 0.24%   |
| 1600x1200          | 6         | 0.24%   |
| 3840x1600          | 5         | 0.2%    |
| 2288x1287          | 5         | 0.2%    |
| 3840x2400          | 4         | 0.16%   |
| 3840x1200          | 4         | 0.16%   |
| 1024x600           | 4         | 0.16%   |
| 2736x1824          | 3         | 0.12%   |
| 2520x1680          | 3         | 0.12%   |
| 2256x1504          | 3         | 0.12%   |
| 2240x1400          | 3         | 0.12%   |
| 1280x720 (HD)      | 3         | 0.12%   |
| 4480x1440          | 2         | 0.08%   |
| 3456x2160          | 2         | 0.08%   |
| 3200x2000          | 2         | 0.08%   |
| 2048x1536          | 2         | 0.08%   |
| 2048x1152          | 2         | 0.08%   |
| 1400x1050          | 2         | 0.08%   |
| 1280x960           | 2         | 0.08%   |
| 8960x2160          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 593       | 22.68%  |
| 27      | 267       | 10.21%  |
| 24      | 209       | 7.99%   |
| 14      | 208       | 7.95%   |
| 13      | 207       | 7.92%   |
| 21      | 168       | 6.42%   |
| 23      | 154       | 5.89%   |
| 17      | 147       | 5.62%   |
| Unknown | 94        | 3.59%   |
| 19      | 67        | 2.56%   |
| 31      | 65        | 2.49%   |
| 34      | 56        | 2.14%   |
| 12      | 50        | 1.91%   |
| 22      | 38        | 1.45%   |
| 18      | 37        | 1.41%   |
| 20      | 31        | 1.19%   |
| 16      | 27        | 1.03%   |
| 32      | 22        | 0.84%   |
| 84      | 19        | 0.73%   |
| 11      | 18        | 0.69%   |
| 25      | 14        | 0.54%   |
| 26      | 13        | 0.5%    |
| 54      | 12        | 0.46%   |
| 29      | 12        | 0.46%   |
| 72      | 10        | 0.38%   |
| 40      | 10        | 0.38%   |
| 37      | 7         | 0.27%   |
| 28      | 6         | 0.23%   |
| 142     | 5         | 0.19%   |
| 42      | 5         | 0.19%   |
| 10      | 5         | 0.19%   |
| 49      | 4         | 0.15%   |
| 33      | 4         | 0.15%   |
| 74      | 3         | 0.11%   |
| 52      | 3         | 0.11%   |
| 48      | 3         | 0.11%   |
| 43      | 3         | 0.11%   |
| 35      | 3         | 0.11%   |
| 60      | 2         | 0.08%   |
| 38      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 915       | 35.73%  |
| 501-600        | 582       | 22.73%  |
| 401-500        | 295       | 11.52%  |
| 201-300        | 188       | 7.34%   |
| 351-400        | 187       | 7.3%    |
| 601-700        | 118       | 4.61%   |
| Unknown        | 94        | 3.67%   |
| 701-800        | 82        | 3.2%    |
| 1501-2000      | 33        | 1.29%   |
| 1001-1500      | 28        | 1.09%   |
| 801-900        | 23        | 0.9%    |
| 901-1000       | 8         | 0.31%   |
| More than 2000 | 5         | 0.2%    |
| 101-200        | 2         | 0.08%   |
| 1-100          | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1766      | 75.73%  |
| 16/10   | 281       | 12.05%  |
| Unknown | 73        | 3.13%   |
| 21/9    | 66        | 2.83%   |
| 5/4     | 59        | 2.53%   |
| 4/3     | 35        | 1.5%    |
| 3/2     | 27        | 1.16%   |
| 6/5     | 7         | 0.3%    |
| 32/9    | 5         | 0.21%   |
| 1.00    | 5         | 0.21%   |
| 2.65    | 4         | 0.17%   |
| 3.73    | 1         | 0.04%   |
| 3.40    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 1.96    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 595       | 23.01%  |
| 201-250        | 442       | 17.09%  |
| 81-90          | 326       | 12.61%  |
| 301-350        | 274       | 10.6%   |
| 351-500        | 161       | 6.23%   |
| 151-200        | 149       | 5.76%   |
| 121-130        | 110       | 4.25%   |
| Unknown        | 94        | 3.63%   |
| 251-300        | 92        | 3.56%   |
| 71-80          | 91        | 3.52%   |
| More than 1000 | 59        | 2.28%   |
| 141-150        | 48        | 1.86%   |
| 61-70          | 44        | 1.7%    |
| 501-1000       | 33        | 1.28%   |
| 111-120        | 21        | 0.81%   |
| 51-60          | 20        | 0.77%   |
| 131-140        | 15        | 0.58%   |
| 41-50          | 5         | 0.19%   |
| 91-100         | 5         | 0.19%   |
| 1-40           | 2         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 830       | 33.17%  |
| 121-160       | 699       | 27.94%  |
| 101-120       | 593       | 23.7%   |
| 161-240       | 177       | 7.07%   |
| Unknown       | 94        | 3.76%   |
| More than 240 | 63        | 2.52%   |
| 1-50          | 46        | 1.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1748      | 75.34%  |
| 2     | 457       | 19.7%   |
| 0     | 61        | 2.63%   |
| 3     | 49        | 2.11%   |
| 4     | 5         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1242      | 36.62%  |
| Intel                             | 1177      | 34.7%   |
| Qualcomm Atheros                  | 288       | 8.49%   |
| Broadcom                          | 188       | 5.54%   |
| MediaTek                          | 67        | 1.98%   |
| Broadcom Limited                  | 34        | 1%      |
| Ralink Technology                 | 33        | 0.97%   |
| TP-Link                           | 30        | 0.88%   |
| Ralink                            | 25        | 0.74%   |
| Nvidia                            | 25        | 0.74%   |
| ASIX Electronics                  | 25        | 0.74%   |
| Marvell Technology Group          | 24        | 0.71%   |
| Sierra Wireless                   | 15        | 0.44%   |
| Dell                              | 12        | 0.35%   |
| Lenovo                            | 11        | 0.32%   |
| DisplayLink                       | 11        | 0.32%   |
| Samsung Electronics               | 10        | 0.29%   |
| D-Link                            | 10        | 0.29%   |
| NetGear                           | 8         | 0.24%   |
| Edimax Technology                 | 8         | 0.24%   |
| Microsoft                         | 7         | 0.21%   |
| Huawei Technologies               | 7         | 0.21%   |
| Ericsson Business Mobile Networks | 7         | 0.21%   |
| Aquantia                          | 7         | 0.21%   |
| Linksys                           | 6         | 0.18%   |
| Hewlett-Packard                   | 6         | 0.18%   |
| D-Link System                     | 6         | 0.18%   |
| ASUSTek Computer                  | 6         | 0.18%   |
| Xiaomi                            | 5         | 0.15%   |
| U-Blox                            | 5         | 0.15%   |
| Qualcomm                          | 5         | 0.15%   |
| Qualcomm Atheros Communications   | 4         | 0.12%   |
| Cypress Semiconductor             | 4         | 0.12%   |
| Belkin Components                 | 4         | 0.12%   |
| AVM                               | 4         | 0.12%   |
| Motorola PCS                      | 3         | 0.09%   |
| Microchip Technology              | 3         | 0.09%   |
| Mellanox Technologies             | 3         | 0.09%   |
| JMicron Technology                | 3         | 0.09%   |
| ICS Advent                        | 3         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 902       | 22.36%  |
| Intel Wi-Fi 6 AX200                                               | 156       | 3.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 81        | 2.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 79        | 1.96%   |
| Intel Wireless 8265 / 8275                                        | 77        | 1.91%   |
| Intel I211 Gigabit Network Connection                             | 73        | 1.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 71        | 1.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 63        | 1.56%   |
| Intel Wi-Fi 6 AX201                                               | 63        | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 62        | 1.54%   |
| Intel Wireless 8260                                               | 58        | 1.44%   |
| Intel Wireless 7260                                               | 53        | 1.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 52        | 1.29%   |
| Intel Wireless-AC 9260                                            | 43        | 1.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 42        | 1.04%   |
| Intel Wireless 7265                                               | 41        | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 36        | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 36        | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 34        | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 34        | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 33        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 32        | 0.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 31        | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 29        | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 29        | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 28        | 0.69%   |
| Intel Ethernet Controller I225-V                                  | 27        | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 26        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 23        | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 22        | 0.55%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 22        | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 21        | 0.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 21        | 0.52%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 20        | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 19        | 0.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 19        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 896       | 50.06%  |
| Realtek Semiconductor                 | 281       | 15.7%   |
| Qualcomm Atheros                      | 224       | 12.51%  |
| Broadcom                              | 124       | 6.93%   |
| MediaTek                              | 62        | 3.46%   |
| Ralink Technology                     | 33        | 1.84%   |
| Ralink                                | 25        | 1.4%    |
| TP-Link                               | 21        | 1.17%   |
| Broadcom Limited                      | 20        | 1.12%   |
| Sierra Wireless                       | 15        | 0.84%   |
| D-Link                                | 10        | 0.56%   |
| NetGear                               | 8         | 0.45%   |
| Edimax Technology                     | 8         | 0.45%   |
| Dell                                  | 8         | 0.45%   |
| Linksys                               | 6         | 0.34%   |
| ASUSTek Computer                      | 6         | 0.34%   |
| Microsoft                             | 5         | 0.28%   |
| Qualcomm Atheros Communications       | 4         | 0.22%   |
| Qualcomm                              | 4         | 0.22%   |
| Marvell Technology Group              | 4         | 0.22%   |
| D-Link System                         | 4         | 0.22%   |
| Belkin Components                     | 4         | 0.22%   |
| AVM                                   | 4         | 0.22%   |
| ZyXEL Communications                  | 1         | 0.06%   |
| Xiaomi                                | 1         | 0.06%   |
| Wacom                                 | 1         | 0.06%   |
| Samsung Electronics                   | 1         | 0.06%   |
| Realtek                               | 1         | 0.06%   |
| Qualcomm Technologies                 | 1         | 0.06%   |
| Micro Star International              | 1         | 0.06%   |
| Intersil                              | 1         | 0.06%   |
| IMC Networks                          | 1         | 0.06%   |
| Hewlett-Packard                       | 1         | 0.06%   |
| Fibocom                               | 1         | 0.06%   |
| Ericsson Business Mobile Networks     | 1         | 0.06%   |
| BUFFALO                               | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 156       | 8.64%   |
| Intel Wireless 8265 / 8275                                     | 77        | 4.26%   |
| Intel Wi-Fi 6 AX201                                            | 63        | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 62        | 3.43%   |
| Intel Wireless 8260                                            | 58        | 3.21%   |
| Intel Wireless 7260                                            | 53        | 2.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 52        | 2.88%   |
| Intel Wireless-AC 9260                                         | 43        | 2.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 42        | 2.33%   |
| Intel Wireless 7265                                            | 41        | 2.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 36        | 1.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 34        | 1.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 34        | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 33        | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 32        | 1.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 31        | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 29        | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 29        | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 28        | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 26        | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 22        | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 21        | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 21        | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 20        | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 19        | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 18        | 1%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 17        | 0.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 17        | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                  | 17        | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 16        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16        | 0.89%   |
| Intel Wireless 3160                                            | 16        | 0.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 16        | 0.89%   |
| Intel Centrino Ultimate-N 6300                                 | 16        | 0.89%   |
| Intel Wireless 3165                                            | 15        | 0.83%   |
| Realtek 802.11ac NIC                                           | 13        | 0.72%   |
| Intel Centrino Advanced-N 6235                                 | 13        | 0.72%   |
| Ralink MT7601U Wireless Adapter                                | 12        | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 11        | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 11        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1125      | 52.79%  |
| Intel                                  | 633       | 29.7%   |
| Broadcom                               | 95        | 4.46%   |
| Qualcomm Atheros                       | 87        | 4.08%   |
| Nvidia                                 | 25        | 1.17%   |
| ASIX Electronics                       | 25        | 1.17%   |
| Marvell Technology Group               | 20        | 0.94%   |
| Broadcom Limited                       | 14        | 0.66%   |
| Lenovo                                 | 11        | 0.52%   |
| DisplayLink                            | 11        | 0.52%   |
| TP-Link                                | 9         | 0.42%   |
| Samsung Electronics                    | 9         | 0.42%   |
| Aquantia                               | 7         | 0.33%   |
| Huawei Technologies                    | 6         | 0.28%   |
| MediaTek                               | 5         | 0.23%   |
| Xiaomi                                 | 4         | 0.19%   |
| Cypress Semiconductor                  | 4         | 0.19%   |
| Motorola PCS                           | 3         | 0.14%   |
| JMicron Technology                     | 3         | 0.14%   |
| ICS Advent                             | 3         | 0.14%   |
| Dell                                   | 3         | 0.14%   |
| VIA Technologies                       | 2         | 0.09%   |
| NetXen Incorporated                    | 2         | 0.09%   |
| Microsoft                              | 2         | 0.09%   |
| HMD Global                             | 2         | 0.09%   |
| D-Link System                          | 2         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Solarflare Communications              | 1         | 0.05%   |
| Sitecom Europe                         | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.05%   |
| Qualcomm                               | 1         | 0.05%   |
| OPPO Electronics                       | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| National Semiconductor                 | 1         | 0.05%   |
| MosChip Semiconductor                  | 1         | 0.05%   |
| Microchip Technology                   | 1         | 0.05%   |
| IBM                                    | 1         | 0.05%   |
| Hewlett-Packard                        | 1         | 0.05%   |
| Google                                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 902       | 41.26%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 81        | 3.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 79        | 3.61%   |
| Intel I211 Gigabit Network Connection                             | 73        | 3.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 71        | 3.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 63        | 2.88%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 1.78%   |
| Intel Ethernet Connection (2) I219-V                              | 36        | 1.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 1.42%   |
| Intel Ethernet Controller I225-V                                  | 27        | 1.24%   |
| ASIX AX88179 Gigabit Ethernet                                     | 23        | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 1.01%   |
| Intel Ethernet Connection I217-V                                  | 22        | 1.01%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 0.91%   |
| Intel I210 Gigabit Network Connection                             | 19        | 0.87%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 18        | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.82%   |
| Intel 82579V Gigabit Network Connection                           | 17        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.73%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.69%   |
| Intel Ethernet Connection I219-V                                  | 14        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 0.64%   |
| Nvidia MCP79 Ethernet                                             | 13        | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 13        | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.46%   |
| Intel Ethernet Connection (10) I219-V                             | 10        | 0.46%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 10        | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 0.41%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 9         | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 9         | 0.41%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 8         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8         | 0.37%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 0.37%   |
| Intel Ethernet Connection (11) I219-V                             | 8         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1954      | 53.03%  |
| WiFi     | 1691      | 45.89%  |
| Modem    | 28        | 0.76%   |
| Unknown  | 12        | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1261      | 52.41%  |
| Ethernet | 1144      | 47.55%  |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1233      | 54.46%  |
| 1     | 903       | 39.89%  |
| 3     | 72        | 3.18%   |
| 0     | 27        | 1.19%   |
| 4     | 21        | 0.93%   |
| 5     | 6         | 0.27%   |
| 8     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1804      | 78.23%  |
| Yes  | 502       | 21.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 747       | 50.54%  |
| Realtek Semiconductor           | 145       | 9.81%   |
| Cambridge Silicon Radio         | 107       | 7.24%   |
| Qualcomm Atheros Communications | 88        | 5.95%   |
| Broadcom                        | 63        | 4.26%   |
| Apple                           | 60        | 4.06%   |
| Lite-On Technology              | 57        | 3.86%   |
| IMC Networks                    | 51        | 3.45%   |
| Foxconn / Hon Hai               | 47        | 3.18%   |
| ASUSTek Computer                | 27        | 1.83%   |
| Hewlett-Packard                 | 11        | 0.74%   |
| Dell                            | 11        | 0.74%   |
| Realtek                         | 10        | 0.68%   |
| MediaTek                        | 10        | 0.68%   |
| Toshiba                         | 6         | 0.41%   |
| TP-Link                         | 4         | 0.27%   |
| Ralink                          | 4         | 0.27%   |
| Marvell Semiconductor           | 4         | 0.27%   |
| Belkin Components               | 3         | 0.2%    |
| USI                             | 2         | 0.14%   |
| Taiyo Yuden                     | 2         | 0.14%   |
| Smart Modular Technologies      | 2         | 0.14%   |
| Integrated System Solution      | 2         | 0.14%   |
| HTC (High Tech Computer)        | 2         | 0.14%   |
| Foxconn International           | 2         | 0.14%   |
| Alps Electric                   | 2         | 0.14%   |
| Unknown                         | 1         | 0.07%   |
| SINO WEALTH                     | 1         | 0.07%   |
| Ralink Technology               | 1         | 0.07%   |
| Qcom                            | 1         | 0.07%   |
| Opticis                         | 1         | 0.07%   |
| Mobile Action Technology        | 1         | 0.07%   |
| Micro Star International        | 1         | 0.07%   |
| Kensington                      | 1         | 0.07%   |
| Edimax Technology               | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 238       | 16.07%  |
| Intel AX200 Bluetooth                                                               | 148       | 9.99%   |
| Intel AX201 Bluetooth                                                               | 124       | 8.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 107       | 7.22%   |
| Realtek Bluetooth Radio                                                             | 98        | 6.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 79        | 5.33%   |
| Intel Bluetooth Device                                                              | 64        | 4.32%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 42        | 2.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 41        | 2.77%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 37        | 2.5%    |
| Apple Bluetooth Host Controller                                                     | 33        | 2.23%   |
| Intel AX210 Bluetooth                                                               | 31        | 2.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 20        | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 20        | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 19        | 1.28%   |
| IMC Networks Bluetooth Radio                                                        | 18        | 1.22%   |
| IMC Networks Wireless_Device                                                        | 16        | 1.08%   |
| Apple Bluetooth USB Host Controller                                                 | 15        | 1.01%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 14        | 0.95%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 12        | 0.81%   |
| Lite-On Wireless_Device                                                             | 11        | 0.74%   |
| IMC Networks Bluetooth Device                                                       | 11        | 0.74%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 10        | 0.68%   |
| MediaTek Wireless_Device                                                            | 10        | 0.68%   |
| Realtek 802.11ac WLAN Adapter                                                       | 9         | 0.61%   |
| Lite-On Bluetooth Device                                                            | 9         | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 9         | 0.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 9         | 0.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 8         | 0.54%   |
| ASUS ASUS USB-BT500                                                                 | 8         | 0.54%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 8         | 0.54%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 7         | 0.47%   |
| Realtek RTL8821A Bluetooth                                                          | 6         | 0.41%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 0.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 6         | 0.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.34%   |
| Broadcom HP Portable Bumble Bee                                                     | 5         | 0.34%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 5         | 0.34%   |
| TP-Link UB5A Adapter                                                                | 4         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1445      | 44.96%  |
| AMD                                          | 832       | 25.89%  |
| Nvidia                                       | 500       | 15.56%  |
| C-Media Electronics                          | 58        | 1.8%    |
| Logitech                                     | 33        | 1.03%   |
| Creative Labs                                | 29        | 0.9%    |
| Texas Instruments                            | 22        | 0.68%   |
| Realtek Semiconductor                        | 15        | 0.47%   |
| JMTek                                        | 14        | 0.44%   |
| Lenovo                                       | 13        | 0.4%    |
| Razer USA                                    | 12        | 0.37%   |
| Kingston Technology                          | 12        | 0.37%   |
| GN Netcom                                    | 11        | 0.34%   |
| Generalplus Technology                       | 11        | 0.34%   |
| Creative Technology                          | 11        | 0.34%   |
| ASUSTek Computer                             | 10        | 0.31%   |
| BEHRINGER International                      | 9         | 0.28%   |
| RODE Microphones                             | 8         | 0.25%   |
| Plantronics                                  | 8         | 0.25%   |
| M-Audio                                      | 8         | 0.25%   |
| SteelSeries ApS                              | 7         | 0.22%   |
| Corsair                                      | 7         | 0.22%   |
| Yamaha                                       | 6         | 0.19%   |
| Sennheiser Communications                    | 6         | 0.19%   |
| Focusrite-Novation                           | 6         | 0.19%   |
| VIA Technologies                             | 5         | 0.16%   |
| Hewlett-Packard                              | 5         | 0.16%   |
| FiiO Electronics Technology                  | 5         | 0.16%   |
| Samson Technologies                          | 4         | 0.12%   |
| SAVITECH                                     | 3         | 0.09%   |
| Micro Star International                     | 3         | 0.09%   |
| Dell                                         | 3         | 0.09%   |
| Apple                                        | 3         | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.06%   |
| ZOOM                                         | 2         | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.06%   |
| TerraTec Electronic                          | 2         | 0.06%   |
| Tenx Technology                              | 2         | 0.06%   |
| Sony                                         | 2         | 0.06%   |
| Solid State Logic                            | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 304       | 7.65%   |
| Intel Sunrise Point-LP HD Audio                                            | 183       | 4.61%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 169       | 4.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 136       | 3.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 124       | 3.12%   |
| AMD Starship/Matisse HD Audio Controller                                   | 120       | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 110       | 2.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 97        | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 91        | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 88        | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 87        | 2.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 87        | 2.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 83        | 2.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 74        | 1.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 72        | 1.81%   |
| AMD FCH Azalia Controller                                                  | 58        | 1.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 57        | 1.44%   |
| Intel 8 Series HD Audio Controller                                         | 51        | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 50        | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 45        | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 38        | 0.96%   |
| Intel Broadwell-U Audio Controller                                         | 38        | 0.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 38        | 0.96%   |
| Intel 200 Series PCH HD Audio                                              | 38        | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 37        | 0.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 37        | 0.93%   |
| AMD Navi 10 HDMI Audio                                                     | 37        | 0.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 37        | 0.93%   |
| Nvidia GP104 High Definition Audio Controller                              | 34        | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 33        | 0.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 33        | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                               | 32        | 0.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 32        | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 31        | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 29        | 0.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 29        | 0.73%   |
| AMD Kabini HDMI/DP Audio                                                   | 29        | 0.73%   |
| Intel Comet Lake PCH cAVS                                                  | 27        | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 26        | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 25        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 361       | 21.69%  |
| SK hynix               | 282       | 16.95%  |
| Kingston               | 201       | 12.08%  |
| Micron Technology      | 173       | 10.4%   |
| Unknown                | 122       | 7.33%   |
| Crucial                | 114       | 6.85%   |
| Corsair                | 109       | 6.55%   |
| G.Skill                | 89        | 5.35%   |
| A-DATA Technology      | 24        | 1.44%   |
| Ramaxel Technology     | 22        | 1.32%   |
| Elpida                 | 18        | 1.08%   |
| Unknown (ABCD)         | 16        | 0.96%   |
| Patriot                | 16        | 0.96%   |
| Team                   | 14        | 0.84%   |
| Smart                  | 12        | 0.72%   |
| Nanya Technology       | 12        | 0.72%   |
| Unknown                | 10        | 0.6%    |
| Avant                  | 8         | 0.48%   |
| Transcend              | 7         | 0.42%   |
| GOODRAM                | 6         | 0.36%   |
| AMD                    | 4         | 0.24%   |
| Teikon                 | 2         | 0.12%   |
| Qimonda                | 2         | 0.12%   |
| PNY                    | 2         | 0.12%   |
| Lexar                  | 2         | 0.12%   |
| Kingmax                | 2         | 0.12%   |
| Exceleram              | 2         | 0.12%   |
| ChangXin Memory        | 2         | 0.12%   |
| ASint Technology       | 2         | 0.12%   |
| Apacer                 | 2         | 0.12%   |
| Unknown (0x02BA)       | 1         | 0.06%   |
| Unknown (07FB)         | 1         | 0.06%   |
| Unknown (000004B30000) | 1         | 0.06%   |
| Unifosa                | 1         | 0.06%   |
| Toshiba                | 1         | 0.06%   |
| Timetec                | 1         | 0.06%   |
| TakeMS                 | 1         | 0.06%   |
| Super Talent           | 1         | 0.06%   |
| Smart Modular          | 1         | 0.06%   |
| Smart Brazil           | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 17        | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 11        | 0.62%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.62%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.57%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 0.57%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 10        | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.57%   |
| Unknown                                                          | 10        | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.51%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.51%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 9         | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.45%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 8         | 0.45%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.4%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.4%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 7         | 0.4%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.4%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.4%    |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 7         | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.4%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 7         | 0.4%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 7         | 0.4%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 6         | 0.34%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 6         | 0.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 6         | 0.34%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 6         | 0.34%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.34%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.34%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.34%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.34%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 6         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 747       | 52.83%  |
| DDR3    | 421       | 29.77%  |
| LPDDR4  | 57        | 4.03%   |
| DDR2    | 44        | 3.11%   |
| Unknown | 40        | 2.83%   |
| LPDDR3  | 33        | 2.33%   |
| DDR5    | 25        | 1.77%   |
| SDRAM   | 23        | 1.63%   |
| LPDDR5  | 12        | 0.85%   |
| DDR     | 8         | 0.57%   |
| DRAM    | 4         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 775       | 54.42%  |
| DIMM         | 532       | 37.36%  |
| Row Of Chips | 98        | 6.88%   |
| Chip         | 14        | 0.98%   |
| RIMM         | 2         | 0.14%   |
| FB-DIMM      | 2         | 0.14%   |
| Unknown      | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 655       | 41.93%  |
| 4096  | 385       | 24.65%  |
| 16384 | 276       | 17.67%  |
| 2048  | 134       | 8.58%   |
| 32768 | 71        | 4.55%   |
| 1024  | 37        | 2.37%   |
| 512   | 2         | 0.13%   |
| 49152 | 1         | 0.06%   |
| 128   | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 280       | 18.06%  |
| 3200    | 261       | 16.84%  |
| 2667    | 234       | 15.1%   |
| 2400    | 115       | 7.42%   |
| 1333    | 107       | 6.9%    |
| 2133    | 90        | 5.81%   |
| 3600    | 51        | 3.29%   |
| 1334    | 40        | 2.58%   |
| 1867    | 29        | 1.87%   |
| 800     | 26        | 1.68%   |
| 667     | 23        | 1.48%   |
| 4267    | 21        | 1.35%   |
| 4800    | 19        | 1.23%   |
| 3266    | 17        | 1.1%    |
| 3400    | 15        | 0.97%   |
| 1067    | 13        | 0.84%   |
| Unknown | 13        | 0.84%   |
| 6400    | 12        | 0.77%   |
| 1066    | 12        | 0.77%   |
| 3800    | 11        | 0.71%   |
| 2933    | 11        | 0.71%   |
| 2666    | 11        | 0.71%   |
| 4266    | 10        | 0.65%   |
| 3000    | 10        | 0.65%   |
| 3533    | 9         | 0.58%   |
| 1866    | 9         | 0.58%   |
| 2048    | 8         | 0.52%   |
| 8400    | 7         | 0.45%   |
| 3733    | 6         | 0.39%   |
| 3666    | 6         | 0.39%   |
| 2800    | 6         | 0.39%   |
| 1800    | 6         | 0.39%   |
| 3866    | 5         | 0.32%   |
| 975     | 5         | 0.32%   |
| 533     | 5         | 0.32%   |
| 5600    | 4         | 0.26%   |
| 4199    | 4         | 0.26%   |
| 3466    | 4         | 0.26%   |
| 3933    | 3         | 0.19%   |
| 333     | 3         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 30        | 42.25%  |
| Seiko Epson         | 10        | 14.08%  |
| Samsung Electronics | 10        | 14.08%  |
| Brother Industries  | 10        | 14.08%  |
| Canon               | 6         | 8.45%   |
| Prolific Technology | 2         | 2.82%   |
| Star Micronics      | 1         | 1.41%   |
| Pantum              | 1         | 1.41%   |
| Kyocera             | 1         | 1.41%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                      | 2         | 2.7%    |
| Samsung M267x 287x Series                       | 2         | 2.7%    |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 2.7%    |
| Prolific PL2305 Parallel Port                   | 2         | 2.7%    |
| HP Officejet 4500 G510g-m                       | 2         | 2.7%    |
| HP LaserJet 1320                                | 2         | 2.7%    |
| HP ENVY 4520 series                             | 2         | 2.7%    |
| HP Color LaserJet CP1215                        | 2         | 2.7%    |
| Brother Printer                                 | 2         | 2.7%    |
| Star Micronics TSP100ECO/TSP100II               | 1         | 1.35%   |
| Seiko Epson XP-4200 Series                      | 1         | 1.35%   |
| Seiko Epson XP-240 Series                       | 1         | 1.35%   |
| Seiko Epson XP-230 Series                       | 1         | 1.35%   |
| Seiko Epson WF-4830 Series                      | 1         | 1.35%   |
| Seiko Epson WF-2510 Series                      | 1         | 1.35%   |
| Seiko Epson L1300 Series                        | 1         | 1.35%   |
| Seiko Epson ET-3840 Series                      | 1         | 1.35%   |
| Seiko Epson ET-2820 Series                      | 1         | 1.35%   |
| Seiko Epson ET-2720 Series                      | 1         | 1.35%   |
| Samsung SCX-4200 series                         | 1         | 1.35%   |
| Samsung SCX-3400 Series                         | 1         | 1.35%   |
| Samsung Phaser 3121                             | 1         | 1.35%   |
| Samsung ML-191x/ML-252x Laser Printer           | 1         | 1.35%   |
| Samsung ML-1865                                 | 1         | 1.35%   |
| Samsung M2020 Series                            | 1         | 1.35%   |
| Pantum P2500W-series                            | 1         | 1.35%   |
| Kyocera FS-1030D printer                        | 1         | 1.35%   |
| HP Smart Tank Plus 550 series                   | 1         | 1.35%   |
| HP Smart Install                                | 1         | 1.35%   |
| HP Officejet Pro 6230                           | 1         | 1.35%   |
| HP Officejet 7110 series                        | 1         | 1.35%   |
| HP OfficeJet 5200 series                        | 1         | 1.35%   |
| HP Officejet 4620 series                        | 1         | 1.35%   |
| HP OfficeJet 3830 series                        | 1         | 1.35%   |
| HP LaserJet Professional P 1102w                | 1         | 1.35%   |
| HP LaserJet P1102                               | 1         | 1.35%   |
| HP LaserJet CM1415fn                            | 1         | 1.35%   |
| HP LaserJet 1200                                | 1         | 1.35%   |
| HP LaserJet 1020                                | 1         | 1.35%   |
| HP LaserJet 1018                                | 1         | 1.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 10        | 43.48%  |
| Seiko Epson     | 7         | 30.43%  |
| Hewlett-Packard | 3         | 13.04%  |
| AGFA-Gevaert NV | 2         | 8.7%    |
| Mustek Systems  | 1         | 4.35%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                       | 4         | 17.39%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 2         | 8.7%    |
| Canon CanoScan LiDE 110                                       | 2         | 8.7%    |
| Seiko Epson Scanner                                           | 1         | 4.35%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]              | 1         | 4.35%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 1         | 4.35%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 1         | 4.35%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]           | 1         | 4.35%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 4.35%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                 | 1         | 4.35%   |
| Mustek Systems ScanExpress A3 USB                             | 1         | 4.35%   |
| HP Scanjet G2710                                              | 1         | 4.35%   |
| HP ScanJet 5300c/5370c                                        | 1         | 4.35%   |
| HP ScanJet 3970c                                              | 1         | 4.35%   |
| Canon CanoScan N1240U/LiDE 30                                 | 1         | 4.35%   |
| Canon CanoScan LiDE 220                                       | 1         | 4.35%   |
| AGFA-Gevaert NV SnapScan e20                                  | 1         | 4.35%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 1         | 4.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 305       | 22.39%  |
| IMC Networks                           | 134       | 9.84%   |
| Microdia                               | 120       | 8.81%   |
| Logitech                               | 110       | 8.08%   |
| Realtek Semiconductor                  | 97        | 7.12%   |
| Bison Electronics                      | 84        | 6.17%   |
| Quanta                                 | 76        | 5.58%   |
| Sunplus Innovation Technology          | 72        | 5.29%   |
| Apple                                  | 45        | 3.3%    |
| Cheng Uei Precision Industry (Foxlink) | 40        | 2.94%   |
| Luxvisions Innotech Limited            | 36        | 2.64%   |
| Syntek                                 | 32        | 2.35%   |
| Lite-On Technology                     | 30        | 2.2%    |
| Suyin                                  | 23        | 1.69%   |
| Acer                                   | 19        | 1.4%    |
| Microsoft                              | 14        | 1.03%   |
| Silicon Motion                         | 10        | 0.73%   |
| Alcor Micro                            | 9         | 0.66%   |
| Lenovo                                 | 7         | 0.51%   |
| Generalplus Technology                 | 7         | 0.51%   |
| Sonix Technology                       | 6         | 0.44%   |
| Z-Star Microelectronics                | 5         | 0.37%   |
| Samsung Electronics                    | 5         | 0.37%   |
| Ricoh                                  | 4         | 0.29%   |
| Primax Electronics                     | 4         | 0.29%   |
| Creative Technology                    | 4         | 0.29%   |
| ARC International                      | 4         | 0.29%   |
| SunplusIT                              | 3         | 0.22%   |
| Hewlett-Packard                        | 3         | 0.22%   |
| Y Media                                | 2         | 0.15%   |
| Trust                                  | 2         | 0.15%   |
| Tobii Technology AB                    | 2         | 0.15%   |
| OmniVision Technologies                | 2         | 0.15%   |
| LG Electronics                         | 2         | 0.15%   |
| Intel                                  | 2         | 0.15%   |
| Importek                               | 2         | 0.15%   |
| Cubeternet                             | 2         | 0.15%   |
| Arkmicro Technologies                  | 2         | 0.15%   |
| ALi                                    | 2         | 0.15%   |
| 2M UVC CAMERA                          | 2         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony integrated camera                            | 75        | 5.46%   |
| IMC Networks Integrated Camera                       | 50        | 3.64%   |
| Microdia Integrated_Webcam_HD                        | 49        | 3.57%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 41        | 2.99%   |
| Realtek Integrated_Webcam_HD                         | 35        | 2.55%   |
| Logitech Webcam C270                                 | 31        | 2.26%   |
| Bison Integrated Camera                              | 28        | 2.04%   |
| Chicony HD WebCam                                    | 27        | 1.97%   |
| Sunplus Integrated_Webcam_HD                         | 21        | 1.53%   |
| Syntek Integrated Camera                             | 20        | 1.46%   |
| Chicony HP HD Camera                                 | 19        | 1.38%   |
| Apple Built-in iSight                                | 15        | 1.09%   |
| Logitech HD Pro Webcam C920                          | 14        | 1.02%   |
| Apple FaceTime HD Camera                             | 13        | 0.95%   |
| Quanta HP HD Camera                                  | 12        | 0.87%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 12        | 0.87%   |
| Chicony Integrated Camera (1280x720@30)              | 12        | 0.87%   |
| Quanta HD User Facing                                | 11        | 0.8%    |
| Chicony USB2.0 Camera                                | 11        | 0.8%    |
| Bison HD Webcam                                      | 11        | 0.8%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 11        | 0.8%    |
| Realtek Integrated Webcam HD                         | 10        | 0.73%   |
| Lite-On Integrated Camera                            | 10        | 0.73%   |
| Chicony HP HD Webcam                                 | 10        | 0.73%   |
| Sunplus HD WebCam                                    | 9         | 0.66%   |
| Quanta VGA WebCam                                    | 9         | 0.66%   |
| Microdia Integrated Webcam                           | 9         | 0.66%   |
| Microdia GC02M2                                      | 9         | 0.66%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 9         | 0.66%   |
| Chicony HD User Facing                               | 9         | 0.66%   |
| Bison BisonCam, NB Pro                               | 9         | 0.66%   |
| Realtek USB Camera                                   | 8         | 0.58%   |
| Quanta HP TrueVision HD Camera                       | 8         | 0.58%   |
| Microdia Webcam Vitade AF                            | 8         | 0.58%   |
| Logitech HD Webcam C615                              | 8         | 0.58%   |
| Chicony FJ Camera                                    | 8         | 0.58%   |
| Luxvisions Innotech Limited Integrated Camera        | 7         | 0.51%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 7         | 0.51%   |
| Luxvisions Innotech Limited HP HD Camera             | 7         | 0.51%   |
| Logitech C922 Pro Stream Webcam                      | 7         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 100       | 37.04%  |
| Synaptics                  | 95        | 35.19%  |
| Shenzhen Goodix Technology | 38        | 14.07%  |
| Upek                       | 11        | 4.07%   |
| AuthenTec                  | 11        | 4.07%   |
| Elan Microelectronics      | 10        | 3.7%    |
| LighTuning Technology      | 2         | 0.74%   |
| STMicroelectronics         | 1         | 0.37%   |
| Samsung Electronics        | 1         | 0.37%   |
| Focal-systems.Corp         | 1         | 0.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 29        | 10.74%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 25        | 9.26%   |
| Shenzhen Goodix  FingerPrint Device                                        | 25        | 9.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 5.93%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 4.44%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 4.44%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 4.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 4.07%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 3.7%    |
| Synaptics UWP WBDI                                                         | 9         | 3.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 3.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 2.59%   |
| Synaptics WBDI                                                             | 7         | 2.59%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 2.59%   |
| Elan ELAN:ARM-M4                                                           | 6         | 2.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.85%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.85%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.85%   |
| Validity Sensors VFS491                                                    | 4         | 1.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.48%   |
| Synaptics  WBDI                                                            | 4         | 1.48%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.48%   |
| Synaptics WBDI Device                                                      | 3         | 1.11%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 1.11%   |
| Unknown                                                                    | 3         | 1.11%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.74%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.74%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.74%   |
| Elan ELAN:Fingerprint                                                      | 2         | 0.74%   |
| AuthenTec AES2810                                                          | 2         | 0.74%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.74%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.74%   |
| AuthenTec AES1600                                                          | 2         | 0.74%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.37%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.37%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.37%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.37%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 45        | 40.54%  |
| Broadcom                   | 41        | 36.94%  |
| Gemalto (was Gemplus)      | 6         | 5.41%   |
| Upek                       | 5         | 4.5%    |
| O2 Micro                   | 3         | 2.7%    |
| Hewlett-Packard            | 3         | 2.7%    |
| Lenovo                     | 2         | 1.8%    |
| Yubico.com                 | 1         | 0.9%    |
| Watchdata                  | 1         | 0.9%    |
| SCM Microsystems           | 1         | 0.9%    |
| Clay Logic                 | 1         | 0.9%    |
| Castles Technology         | 1         | 0.9%    |
| Athena Smartcard Solutions | 1         | 0.9%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 43        | 38.74%  |
| Broadcom 5880                                                                | 16        | 14.41%  |
| Broadcom 58200                                                               | 13        | 11.71%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 7.21%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.5%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 4.5%    |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 3.6%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 2.7%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 3         | 2.7%    |
| Lenovo Integrated Smart Card Reader                                          | 2         | 1.8%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.9%    |
| Watchdata USB Key                                                            | 1         | 0.9%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.9%    |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.9%    |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.9%    |
| Castles Technology EZCCID Smart Card Reader                                  | 1         | 0.9%    |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.9%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.9%    |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.9%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1607      | 68.76%  |
| 1     | 580       | 24.82%  |
| 2     | 126       | 5.39%   |
| 3     | 19        | 0.81%   |
| 4     | 4         | 0.17%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 268       | 31.16%  |
| Graphics card            | 188       | 21.86%  |
| Chipcard                 | 101       | 11.74%  |
| Net/wireless             | 90        | 10.47%  |
| Multimedia controller    | 57        | 6.63%   |
| Sound                    | 33        | 3.84%   |
| Camera                   | 25        | 2.91%   |
| Unassigned class         | 23        | 2.67%   |
| Communication controller | 21        | 2.44%   |
| Card reader              | 15        | 1.74%   |
| Bluetooth                | 14        | 1.63%   |
| Storage                  | 8         | 0.93%   |
| Network                  | 5         | 0.58%   |
| Net/ethernet             | 4         | 0.47%   |
| Firewire controller      | 4         | 0.47%   |
| Modem                    | 2         | 0.23%   |
| Storage/raid             | 1         | 0.12%   |
| Flash memory             | 1         | 0.12%   |

