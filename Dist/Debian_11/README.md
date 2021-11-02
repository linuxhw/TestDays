Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | Ugoos UT2                   | Other       | [3d5e473688](https://linux-hardware.org/?probe=3d5e473688) | Oct 31, 2021 |
| Rockchip      | Unknown                     | Soc         | [342ccd2ecf](https://linux-hardware.org/?probe=342ccd2ecf) | Oct 31, 2021 |
| Lenovo        | ThinkPad W530 244743G       | Notebook    | [69a252ccd6](https://linux-hardware.org/?probe=69a252ccd6) | Oct 31, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [e58d33df6b](https://linux-hardware.org/?probe=e58d33df6b) | Oct 31, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [70d528a8fc](https://linux-hardware.org/?probe=70d528a8fc) | Oct 31, 2021 |
| Unknown       | MT8117                      | Notebook    | [b579146661](https://linux-hardware.org/?probe=b579146661) | Oct 31, 2021 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [5adc857043](https://linux-hardware.org/?probe=5adc857043) | Oct 31, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [38b4ba227c](https://linux-hardware.org/?probe=38b4ba227c) | Oct 30, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [b6302b710d](https://linux-hardware.org/?probe=b6302b710d) | Oct 30, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [60f4ac8cc5](https://linux-hardware.org/?probe=60f4ac8cc5) | Oct 30, 2021 |
| Chuwi         | Hi8 Air                     | Tablet      | [a2b23f7796](https://linux-hardware.org/?probe=a2b23f7796) | Oct 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5be083edab](https://linux-hardware.org/?probe=5be083edab) | Oct 29, 2021 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [83857e3215](https://linux-hardware.org/?probe=83857e3215) | Oct 29, 2021 |
| Gigabyte      | P55M-UD2                    | Desktop     | [b14c0e8dd2](https://linux-hardware.org/?probe=b14c0e8dd2) | Oct 29, 2021 |
| HP            | 1998                        | Desktop     | [b9e492678d](https://linux-hardware.org/?probe=b9e492678d) | Oct 29, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [ce2c332b33](https://linux-hardware.org/?probe=ce2c332b33) | Oct 29, 2021 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [58dfae44e0](https://linux-hardware.org/?probe=58dfae44e0) | Oct 29, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [83a2d81e1c](https://linux-hardware.org/?probe=83a2d81e1c) | Oct 29, 2021 |
| Dell          | Latitude E7240              | Notebook    | [dbf0fd04c3](https://linux-hardware.org/?probe=dbf0fd04c3) | Oct 28, 2021 |
| AZW           | SEi                         | Mini pc     | [1155d58828](https://linux-hardware.org/?probe=1155d58828) | Oct 28, 2021 |
| Compal        | QAL51                       | Notebook    | [ffffaf4799](https://linux-hardware.org/?probe=ffffaf4799) | Oct 28, 2021 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [085ef9e58d](https://linux-hardware.org/?probe=085ef9e58d) | Oct 28, 2021 |
| HP            | 0AECh D                     | Desktop     | [15a01d5e13](https://linux-hardware.org/?probe=15a01d5e13) | Oct 28, 2021 |
| HP            | 3047h                       | Desktop     | [eedab3769c](https://linux-hardware.org/?probe=eedab3769c) | Oct 28, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [d85a5ada85](https://linux-hardware.org/?probe=d85a5ada85) | Oct 28, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [a7cc3183f2](https://linux-hardware.org/?probe=a7cc3183f2) | Oct 28, 2021 |
| HP            | Notebook                    | Notebook    | [0ba26ccc72](https://linux-hardware.org/?probe=0ba26ccc72) | Oct 28, 2021 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [6ad4929a33](https://linux-hardware.org/?probe=6ad4929a33) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| Intel         | D945GCCR AAD78647-300       | Desktop     | [d41d75c998](https://linux-hardware.org/?probe=d41d75c998) | Oct 28, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [369b39d1be](https://linux-hardware.org/?probe=369b39d1be) | Oct 28, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [5b7faf1cc6](https://linux-hardware.org/?probe=5b7faf1cc6) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [7c73c4e6f0](https://linux-hardware.org/?probe=7c73c4e6f0) | Oct 27, 2021 |
| ASUSTek       | M4A77T                      | Desktop     | [07942589ae](https://linux-hardware.org/?probe=07942589ae) | Oct 27, 2021 |
| Intel         | H55                         | Desktop     | [b32e64a698](https://linux-hardware.org/?probe=b32e64a698) | Oct 27, 2021 |
| HP            | Laptop 17-by1xxx            | Notebook    | [e6406f34f8](https://linux-hardware.org/?probe=e6406f34f8) | Oct 27, 2021 |
| Dell          | Latitude E6330              | Notebook    | [872cfff7da](https://linux-hardware.org/?probe=872cfff7da) | Oct 26, 2021 |
| Lenovo        | ThinkPad T540p 20BFS05B0... | Notebook    | [5026826dbe](https://linux-hardware.org/?probe=5026826dbe) | Oct 26, 2021 |
| Lenovo        | ThinkPad T540p 20BFS05B0... | Notebook    | [f644310091](https://linux-hardware.org/?probe=f644310091) | Oct 26, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [2f188b606a](https://linux-hardware.org/?probe=2f188b606a) | Oct 25, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b47e0921b6](https://linux-hardware.org/?probe=b47e0921b6) | Oct 25, 2021 |
| Dell          | Latitude E6330              | Notebook    | [c3e7f97c42](https://linux-hardware.org/?probe=c3e7f97c42) | Oct 25, 2021 |
| Dell          | Latitude E6330              | Notebook    | [0e88df3ae7](https://linux-hardware.org/?probe=0e88df3ae7) | Oct 25, 2021 |
| HP            | Pavilion g6                 | Notebook    | [2c2d7620f9](https://linux-hardware.org/?probe=2c2d7620f9) | Oct 25, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [3e6b56c5f9](https://linux-hardware.org/?probe=3e6b56c5f9) | Oct 25, 2021 |
| Acer          | AOA150                      | Notebook    | [1380638bb1](https://linux-hardware.org/?probe=1380638bb1) | Oct 25, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [88030b7fcb](https://linux-hardware.org/?probe=88030b7fcb) | Oct 25, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [ae0cd83502](https://linux-hardware.org/?probe=ae0cd83502) | Oct 25, 2021 |
| Dell          | Latitude E6540              | Notebook    | [df9262f810](https://linux-hardware.org/?probe=df9262f810) | Oct 25, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [487d0f0e12](https://linux-hardware.org/?probe=487d0f0e12) | Oct 24, 2021 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [fd2f79c5fc](https://linux-hardware.org/?probe=fd2f79c5fc) | Oct 24, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [1e4856a770](https://linux-hardware.org/?probe=1e4856a770) | Oct 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [be67e01a7d](https://linux-hardware.org/?probe=be67e01a7d) | Oct 24, 2021 |
| Dell          | 0MD99X A07                  | Server      | [246f93c093](https://linux-hardware.org/?probe=246f93c093) | Oct 24, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [09f6196e70](https://linux-hardware.org/?probe=09f6196e70) | Oct 23, 2021 |
| Dell          | Latitude E6330              | Notebook    | [e7a19ad923](https://linux-hardware.org/?probe=e7a19ad923) | Oct 23, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [6954277377](https://linux-hardware.org/?probe=6954277377) | Oct 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [7aac95cd60](https://linux-hardware.org/?probe=7aac95cd60) | Oct 23, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [c8f19e95d8](https://linux-hardware.org/?probe=c8f19e95d8) | Oct 23, 2021 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [7354eacfc5](https://linux-hardware.org/?probe=7354eacfc5) | Oct 23, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [117223995c](https://linux-hardware.org/?probe=117223995c) | Oct 23, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [e97646cc2e](https://linux-hardware.org/?probe=e97646cc2e) | Oct 23, 2021 |
| Jumper        | EZbook                      | Notebook    | [557738cd7d](https://linux-hardware.org/?probe=557738cd7d) | Oct 23, 2021 |
| HP            | EliteBook 840 Aero G8 No... | Notebook    | [713c29aa23](https://linux-hardware.org/?probe=713c29aa23) | Oct 22, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [bcc008e381](https://linux-hardware.org/?probe=bcc008e381) | Oct 22, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [55dcb690c5](https://linux-hardware.org/?probe=55dcb690c5) | Oct 22, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [08a5e38790](https://linux-hardware.org/?probe=08a5e38790) | Oct 22, 2021 |
| Dell          | Inspiron N4050              | Notebook    | [85a514f622](https://linux-hardware.org/?probe=85a514f622) | Oct 22, 2021 |
| LG Electro... | X120-L.C7L1A9               | Notebook    | [42b7007a7e](https://linux-hardware.org/?probe=42b7007a7e) | Oct 21, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [c7a2305704](https://linux-hardware.org/?probe=c7a2305704) | Oct 21, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [c36147b6a6](https://linux-hardware.org/?probe=c36147b6a6) | Oct 21, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [2815629b34](https://linux-hardware.org/?probe=2815629b34) | Oct 21, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [8d1ec3a3b6](https://linux-hardware.org/?probe=8d1ec3a3b6) | Oct 21, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [0c016119e3](https://linux-hardware.org/?probe=0c016119e3) | Oct 21, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [3cdf9d520e](https://linux-hardware.org/?probe=3cdf9d520e) | Oct 21, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [fe4c73ce24](https://linux-hardware.org/?probe=fe4c73ce24) | Oct 21, 2021 |
| Dell          | 02YRK5 A01                  | Desktop     | [d7c89a5f6a](https://linux-hardware.org/?probe=d7c89a5f6a) | Oct 21, 2021 |
| HP            | 250 G1                      | Notebook    | [b34fa14c55](https://linux-hardware.org/?probe=b34fa14c55) | Oct 21, 2021 |
| ASRock        | B365M Pro4                  | Desktop     | [ec939fb289](https://linux-hardware.org/?probe=ec939fb289) | Oct 20, 2021 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [7039c3e31f](https://linux-hardware.org/?probe=7039c3e31f) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [b5f8d33cc4](https://linux-hardware.org/?probe=b5f8d33cc4) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [920a47f107](https://linux-hardware.org/?probe=920a47f107) | Oct 20, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [e8b00fa29b](https://linux-hardware.org/?probe=e8b00fa29b) | Oct 20, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [cd4a22e83b](https://linux-hardware.org/?probe=cd4a22e83b) | Oct 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2c5f518cc8](https://linux-hardware.org/?probe=2c5f518cc8) | Oct 20, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4899fa0cab](https://linux-hardware.org/?probe=4899fa0cab) | Oct 19, 2021 |
| Digiboard     | MPxx                        | Desktop     | [138c2ef6fb](https://linux-hardware.org/?probe=138c2ef6fb) | Oct 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [0290c2ca6d](https://linux-hardware.org/?probe=0290c2ca6d) | Oct 19, 2021 |
| Lenovo        | ThinkPad 20J10046US         | Notebook    | [cad3a5eb69](https://linux-hardware.org/?probe=cad3a5eb69) | Oct 18, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | Notebook    | [ea23d24f90](https://linux-hardware.org/?probe=ea23d24f90) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [ea22908ff7](https://linux-hardware.org/?probe=ea22908ff7) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [daf0f8d357](https://linux-hardware.org/?probe=daf0f8d357) | Oct 18, 2021 |
| MSI           | GF75 Thin 9SC               | Notebook    | [1f4a66b99a](https://linux-hardware.org/?probe=1f4a66b99a) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [0f5ea2eb9a](https://linux-hardware.org/?probe=0f5ea2eb9a) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [08f117fdcb](https://linux-hardware.org/?probe=08f117fdcb) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [3921dda159](https://linux-hardware.org/?probe=3921dda159) | Oct 18, 2021 |
| Aquarius      | NS585                       | Notebook    | [22c808750d](https://linux-hardware.org/?probe=22c808750d) | Oct 18, 2021 |
| HP            | ProLiant DL360 Gen9         | Server      | [cfffe6aa63](https://linux-hardware.org/?probe=cfffe6aa63) | Oct 18, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [b5f275b4c4](https://linux-hardware.org/?probe=b5f275b4c4) | Oct 17, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [5c4edf2e8d](https://linux-hardware.org/?probe=5c4edf2e8d) | Oct 17, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [66d1015de7](https://linux-hardware.org/?probe=66d1015de7) | Oct 17, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [43bfef3bcd](https://linux-hardware.org/?probe=43bfef3bcd) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [1f4f861804](https://linux-hardware.org/?probe=1f4f861804) | Oct 17, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [d13426531e](https://linux-hardware.org/?probe=d13426531e) | Oct 17, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [c17c589af5](https://linux-hardware.org/?probe=c17c589af5) | Oct 17, 2021 |
| Supermicro    | M11SDV-8CT-LN4F             | Server      | [10f1608197](https://linux-hardware.org/?probe=10f1608197) | Oct 17, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [68ac15eeda](https://linux-hardware.org/?probe=68ac15eeda) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [69fc64df8b](https://linux-hardware.org/?probe=69fc64df8b) | Oct 16, 2021 |
| Lenovo        | S10-3                       | Notebook    | [acb07e4c72](https://linux-hardware.org/?probe=acb07e4c72) | Oct 16, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5e79417ff5](https://linux-hardware.org/?probe=5e79417ff5) | Oct 16, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [7735f49c62](https://linux-hardware.org/?probe=7735f49c62) | Oct 16, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [34fc60e37e](https://linux-hardware.org/?probe=34fc60e37e) | Oct 16, 2021 |
| Dell          | 0D6H9T A01                  | Desktop     | [795b03a6f8](https://linux-hardware.org/?probe=795b03a6f8) | Oct 16, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [b59ab42003](https://linux-hardware.org/?probe=b59ab42003) | Oct 16, 2021 |
| Acer          | TravelMate P215-53          | Notebook    | [3d398d4b58](https://linux-hardware.org/?probe=3d398d4b58) | Oct 16, 2021 |
| Dell          | Latitude 7410               | Convertible | [20fa4b73d7](https://linux-hardware.org/?probe=20fa4b73d7) | Oct 15, 2021 |
| Lenovo        | ThinkPad X60 17068GG        | Notebook    | [2f3b34aac4](https://linux-hardware.org/?probe=2f3b34aac4) | Oct 15, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [dc7e454319](https://linux-hardware.org/?probe=dc7e454319) | Oct 15, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [bf9482b190](https://linux-hardware.org/?probe=bf9482b190) | Oct 15, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [a7045defdf](https://linux-hardware.org/?probe=a7045defdf) | Oct 15, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [ff55772306](https://linux-hardware.org/?probe=ff55772306) | Oct 15, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [d54d095b0d](https://linux-hardware.org/?probe=d54d095b0d) | Oct 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [9005e4d86d](https://linux-hardware.org/?probe=9005e4d86d) | Oct 15, 2021 |
| HP            | 84FD 10                     | Desktop     | [fb32fc7215](https://linux-hardware.org/?probe=fb32fc7215) | Oct 14, 2021 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [3d41f5d139](https://linux-hardware.org/?probe=3d41f5d139) | Oct 14, 2021 |
| Lenovo        | ThinkPad 20J10046US         | Notebook    | [2d46a44cca](https://linux-hardware.org/?probe=2d46a44cca) | Oct 14, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [f78b91b7de](https://linux-hardware.org/?probe=f78b91b7de) | Oct 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [f8f343d12b](https://linux-hardware.org/?probe=f8f343d12b) | Oct 14, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [c3cdfe0336](https://linux-hardware.org/?probe=c3cdfe0336) | Oct 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [7345eddec4](https://linux-hardware.org/?probe=7345eddec4) | Oct 14, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [22a831db3d](https://linux-hardware.org/?probe=22a831db3d) | Oct 14, 2021 |
| Intel         | DP43BF AAE78171-301         | Desktop     | [42df25414b](https://linux-hardware.org/?probe=42df25414b) | Oct 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [d42e0a77d4](https://linux-hardware.org/?probe=d42e0a77d4) | Oct 14, 2021 |
| Intel         | DP43BF AAE78171-301         | Desktop     | [b08c85ef1a](https://linux-hardware.org/?probe=b08c85ef1a) | Oct 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [7b0dd9fe28](https://linux-hardware.org/?probe=7b0dd9fe28) | Oct 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [ea53e809fd](https://linux-hardware.org/?probe=ea53e809fd) | Oct 14, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [7555392d34](https://linux-hardware.org/?probe=7555392d34) | Oct 14, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [7facc39e0e](https://linux-hardware.org/?probe=7facc39e0e) | Oct 14, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [65477965f4](https://linux-hardware.org/?probe=65477965f4) | Oct 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [aaca557699](https://linux-hardware.org/?probe=aaca557699) | Oct 14, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [6847e8306e](https://linux-hardware.org/?probe=6847e8306e) | Oct 14, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [6bd5cc2d9b](https://linux-hardware.org/?probe=6bd5cc2d9b) | Oct 14, 2021 |
| Sony          | SVE14A15FLB                 | Notebook    | [22a4b460cc](https://linux-hardware.org/?probe=22a4b460cc) | Oct 14, 2021 |
| Unknown       | Generic RK322x TV Box       | Mini pc     | [b1424d1c42](https://linux-hardware.org/?probe=b1424d1c42) | Oct 14, 2021 |
| Dell          | 0773VG A02                  | Desktop     | [ecd9b7c720](https://linux-hardware.org/?probe=ecd9b7c720) | Oct 14, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [2ae81cd94f](https://linux-hardware.org/?probe=2ae81cd94f) | Oct 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [000ac750e0](https://linux-hardware.org/?probe=000ac750e0) | Oct 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [69b1046c6e](https://linux-hardware.org/?probe=69b1046c6e) | Oct 13, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [0175c5181a](https://linux-hardware.org/?probe=0175c5181a) | Oct 13, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [cdb34ca184](https://linux-hardware.org/?probe=cdb34ca184) | Oct 13, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [923479d039](https://linux-hardware.org/?probe=923479d039) | Oct 13, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [82de48bc60](https://linux-hardware.org/?probe=82de48bc60) | Oct 13, 2021 |
| Pegatron      | IPXCR-VN1                   | Desktop     | [695f542c6c](https://linux-hardware.org/?probe=695f542c6c) | Oct 13, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e3a92a65f5](https://linux-hardware.org/?probe=e3a92a65f5) | Oct 13, 2021 |
| Unknown       | LakePort                    | Desktop     | [24159c8d9e](https://linux-hardware.org/?probe=24159c8d9e) | Oct 13, 2021 |
| ASUSTek       | TP201SA                     | Notebook    | [504956d2e9](https://linux-hardware.org/?probe=504956d2e9) | Oct 13, 2021 |
| ASUSTek       | UX303LAB                    | Notebook    | [97b9f51735](https://linux-hardware.org/?probe=97b9f51735) | Oct 13, 2021 |
| MSI           | GF75 Thin 9SC               | Notebook    | [db0ef927e0](https://linux-hardware.org/?probe=db0ef927e0) | Oct 13, 2021 |
| MSI           | GF75 Thin 9SC               | Notebook    | [be82875929](https://linux-hardware.org/?probe=be82875929) | Oct 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [f2690f5ec4](https://linux-hardware.org/?probe=f2690f5ec4) | Oct 13, 2021 |
| Lenovo        | SHARKBAY 0B98405 STD        | Desktop     | [6d09c42ade](https://linux-hardware.org/?probe=6d09c42ade) | Oct 12, 2021 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [ec7ba8e11a](https://linux-hardware.org/?probe=ec7ba8e11a) | Oct 12, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [34774c0428](https://linux-hardware.org/?probe=34774c0428) | Oct 12, 2021 |
| HP            | G62                         | Notebook    | [7873481ecb](https://linux-hardware.org/?probe=7873481ecb) | Oct 12, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [b01543c6b8](https://linux-hardware.org/?probe=b01543c6b8) | Oct 12, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [34fe4b38c7](https://linux-hardware.org/?probe=34fe4b38c7) | Oct 12, 2021 |
| MSI           | P43 Neo-F                   | Desktop     | [d79f0f85c1](https://linux-hardware.org/?probe=d79f0f85c1) | Oct 12, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [2a96c0566a](https://linux-hardware.org/?probe=2a96c0566a) | Oct 12, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [69938c221e](https://linux-hardware.org/?probe=69938c221e) | Oct 12, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [4e86b85a4d](https://linux-hardware.org/?probe=4e86b85a4d) | Oct 12, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [59f755658e](https://linux-hardware.org/?probe=59f755658e) | Oct 12, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [6476999787](https://linux-hardware.org/?probe=6476999787) | Oct 12, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [3638982195](https://linux-hardware.org/?probe=3638982195) | Oct 12, 2021 |
| Lenovo        | ThinkPad T520 4242W9B       | Notebook    | [3947636b4d](https://linux-hardware.org/?probe=3947636b4d) | Oct 12, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [e551d622a8](https://linux-hardware.org/?probe=e551d622a8) | Oct 11, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [8ab9e5cc4b](https://linux-hardware.org/?probe=8ab9e5cc4b) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [dce9cc60d3](https://linux-hardware.org/?probe=dce9cc60d3) | Oct 11, 2021 |
| Acer          | Veriton Z4710G              | All in one  | [d5825127bf](https://linux-hardware.org/?probe=d5825127bf) | Oct 11, 2021 |
| Sun Micros... | Ultra 27 52                 | Desktop     | [144b473603](https://linux-hardware.org/?probe=144b473603) | Oct 11, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [e776648230](https://linux-hardware.org/?probe=e776648230) | Oct 11, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [46f9cbae92](https://linux-hardware.org/?probe=46f9cbae92) | Oct 11, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c97f94ce2f](https://linux-hardware.org/?probe=c97f94ce2f) | Oct 10, 2021 |
| HP            | 1589                        | Desktop     | [bb8d8d60cf](https://linux-hardware.org/?probe=bb8d8d60cf) | Oct 10, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [598d90e6b6](https://linux-hardware.org/?probe=598d90e6b6) | Oct 10, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [2a83508f22](https://linux-hardware.org/?probe=2a83508f22) | Oct 10, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [f6a1aece80](https://linux-hardware.org/?probe=f6a1aece80) | Oct 10, 2021 |
| MSI           | B150M Night Elf             | Desktop     | [ed3f4e9937](https://linux-hardware.org/?probe=ed3f4e9937) | Oct 09, 2021 |
| HP            | TouchSmart tm2              | Notebook    | [4a04d297c6](https://linux-hardware.org/?probe=4a04d297c6) | Oct 09, 2021 |
| ASRock        | H110M-ITX/ac                | Desktop     | [261f3477ea](https://linux-hardware.org/?probe=261f3477ea) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [31ae42bc51](https://linux-hardware.org/?probe=31ae42bc51) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5b47e8efcb](https://linux-hardware.org/?probe=5b47e8efcb) | Oct 09, 2021 |
| ASRock        | B75 Pro3-M                  | Desktop     | [62522e187a](https://linux-hardware.org/?probe=62522e187a) | Oct 09, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e709e42b6e](https://linux-hardware.org/?probe=e709e42b6e) | Oct 09, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [3ab285ffb2](https://linux-hardware.org/?probe=3ab285ffb2) | Oct 09, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [cbbb88337f](https://linux-hardware.org/?probe=cbbb88337f) | Oct 09, 2021 |
| Dell          | 0RW199                      | Desktop     | [265977f345](https://linux-hardware.org/?probe=265977f345) | Oct 08, 2021 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [d6391c098d](https://linux-hardware.org/?probe=d6391c098d) | Oct 08, 2021 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [00a9d32484](https://linux-hardware.org/?probe=00a9d32484) | Oct 08, 2021 |
| ASUSTek       | N501VW                      | Notebook    | [40231fbffa](https://linux-hardware.org/?probe=40231fbffa) | Oct 08, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [3c5d005ffb](https://linux-hardware.org/?probe=3c5d005ffb) | Oct 08, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [f180e5db7d](https://linux-hardware.org/?probe=f180e5db7d) | Oct 07, 2021 |
| Dell          | Latitude 7480               | Notebook    | [e4d0ecb120](https://linux-hardware.org/?probe=e4d0ecb120) | Oct 07, 2021 |
| Lenovo        | ThinkPad T490 20N2000KGE    | Notebook    | [cb7f37874e](https://linux-hardware.org/?probe=cb7f37874e) | Oct 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [d76a0d7ff1](https://linux-hardware.org/?probe=d76a0d7ff1) | Oct 07, 2021 |
| Dell          | Latitude E6520              | Notebook    | [18591f972c](https://linux-hardware.org/?probe=18591f972c) | Oct 07, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [7f07c3d457](https://linux-hardware.org/?probe=7f07c3d457) | Oct 07, 2021 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | Desktop     | [b8531e8039](https://linux-hardware.org/?probe=b8531e8039) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9ed170f601](https://linux-hardware.org/?probe=9ed170f601) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [97f69ae3fa](https://linux-hardware.org/?probe=97f69ae3fa) | Oct 07, 2021 |
| HP            | 1998                        | Desktop     | [1a06c2831b](https://linux-hardware.org/?probe=1a06c2831b) | Oct 07, 2021 |
| HP            | 1998                        | Desktop     | [152a505ffd](https://linux-hardware.org/?probe=152a505ffd) | Oct 07, 2021 |
| HP            | 1998                        | Desktop     | [639a06485d](https://linux-hardware.org/?probe=639a06485d) | Oct 07, 2021 |
| Dell          | Vostro A860                 | Notebook    | [02a4dade57](https://linux-hardware.org/?probe=02a4dade57) | Oct 07, 2021 |
| Dell          | Vostro A860                 | Notebook    | [67da5c585b](https://linux-hardware.org/?probe=67da5c585b) | Oct 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [cbb2ea622b](https://linux-hardware.org/?probe=cbb2ea622b) | Oct 07, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [06efedbf24](https://linux-hardware.org/?probe=06efedbf24) | Oct 07, 2021 |
| Pegatron      | 2A99                        | Desktop     | [10f364b4ef](https://linux-hardware.org/?probe=10f364b4ef) | Oct 07, 2021 |
| MSI           | GF63 8RD                    | Notebook    | [42dfecd0fb](https://linux-hardware.org/?probe=42dfecd0fb) | Oct 06, 2021 |
| ASUSTek       | 1015PE                      | Notebook    | [1a2d7bc306](https://linux-hardware.org/?probe=1a2d7bc306) | Oct 06, 2021 |
| MSI           | GF63 8RD                    | Notebook    | [1c72d1e5d7](https://linux-hardware.org/?probe=1c72d1e5d7) | Oct 06, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [9578e01f5b](https://linux-hardware.org/?probe=9578e01f5b) | Oct 06, 2021 |
| ASRock        | AM1B-ITX                    | Desktop     | [417050a11e](https://linux-hardware.org/?probe=417050a11e) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [41ff21e8e8](https://linux-hardware.org/?probe=41ff21e8e8) | Oct 06, 2021 |
| Dell          | Latitude 7480               | Notebook    | [89d642f54a](https://linux-hardware.org/?probe=89d642f54a) | Oct 06, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [eb4d94004c](https://linux-hardware.org/?probe=eb4d94004c) | Oct 06, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [1e7ca025e2](https://linux-hardware.org/?probe=1e7ca025e2) | Oct 06, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [b5e3aaff19](https://linux-hardware.org/?probe=b5e3aaff19) | Oct 06, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [3c8835ecc1](https://linux-hardware.org/?probe=3c8835ecc1) | Oct 05, 2021 |
| HP            | 650                         | Notebook    | [bbe8e793b8](https://linux-hardware.org/?probe=bbe8e793b8) | Oct 05, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [555befb01f](https://linux-hardware.org/?probe=555befb01f) | Oct 05, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [dca9b0f592](https://linux-hardware.org/?probe=dca9b0f592) | Oct 05, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [9a8833b9c4](https://linux-hardware.org/?probe=9a8833b9c4) | Oct 04, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [95f6633ea0](https://linux-hardware.org/?probe=95f6633ea0) | Oct 04, 2021 |
| Dell          | Latitude 7480               | Notebook    | [e8c50a7dbb](https://linux-hardware.org/?probe=e8c50a7dbb) | Oct 04, 2021 |
| Dell          | Latitude E6520              | Notebook    | [b9f0ad8ced](https://linux-hardware.org/?probe=b9f0ad8ced) | Oct 04, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a0fffdb381](https://linux-hardware.org/?probe=a0fffdb381) | Oct 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [572e073021](https://linux-hardware.org/?probe=572e073021) | Oct 04, 2021 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [69ac6e6156](https://linux-hardware.org/?probe=69ac6e6156) | Oct 04, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [bcdf58bee3](https://linux-hardware.org/?probe=bcdf58bee3) | Oct 04, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [6654adaf99](https://linux-hardware.org/?probe=6654adaf99) | Oct 04, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [9622936906](https://linux-hardware.org/?probe=9622936906) | Oct 04, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [ccc383c91f](https://linux-hardware.org/?probe=ccc383c91f) | Oct 03, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [8a9c0fa053](https://linux-hardware.org/?probe=8a9c0fa053) | Oct 03, 2021 |
| Acer          | TMP645-M                    | Notebook    | [c3daab516f](https://linux-hardware.org/?probe=c3daab516f) | Oct 03, 2021 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [52d91383da](https://linux-hardware.org/?probe=52d91383da) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [153c60004b](https://linux-hardware.org/?probe=153c60004b) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [0c7f8d9bc1](https://linux-hardware.org/?probe=0c7f8d9bc1) | Oct 03, 2021 |
| HP            | Laptop 15-ra0xx             | Notebook    | [f053eed9e5](https://linux-hardware.org/?probe=f053eed9e5) | Oct 02, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [5dff50e4bf](https://linux-hardware.org/?probe=5dff50e4bf) | Oct 02, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [eae46e3544](https://linux-hardware.org/?probe=eae46e3544) | Oct 02, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [8169f29a6a](https://linux-hardware.org/?probe=8169f29a6a) | Oct 02, 2021 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [3040e45974](https://linux-hardware.org/?probe=3040e45974) | Oct 02, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [f5565dfb2a](https://linux-hardware.org/?probe=f5565dfb2a) | Oct 01, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [f248667e17](https://linux-hardware.org/?probe=f248667e17) | Oct 01, 2021 |
| HP            | Pavilion g6                 | Notebook    | [ca85ba36e3](https://linux-hardware.org/?probe=ca85ba36e3) | Oct 01, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [85242c59b6](https://linux-hardware.org/?probe=85242c59b6) | Oct 01, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [090eee57b7](https://linux-hardware.org/?probe=090eee57b7) | Oct 01, 2021 |
| TrekStor      | Surfbook A13                | Notebook    | [e393d9bc10](https://linux-hardware.org/?probe=e393d9bc10) | Oct 01, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [666c41eb03](https://linux-hardware.org/?probe=666c41eb03) | Oct 01, 2021 |
| MSI           | GF75 Thin 9SC               | Notebook    | [b62cc852e9](https://linux-hardware.org/?probe=b62cc852e9) | Oct 01, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [0228744a56](https://linux-hardware.org/?probe=0228744a56) | Oct 01, 2021 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [689bc2e25f](https://linux-hardware.org/?probe=689bc2e25f) | Oct 01, 2021 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [29ae8992b5](https://linux-hardware.org/?probe=29ae8992b5) | Sep 30, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [de498adb08](https://linux-hardware.org/?probe=de498adb08) | Sep 30, 2021 |
| HP            | 3047h                       | Desktop     | [89b3f0a1ad](https://linux-hardware.org/?probe=89b3f0a1ad) | Sep 30, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e68e81c986](https://linux-hardware.org/?probe=e68e81c986) | Sep 30, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f273082d09](https://linux-hardware.org/?probe=f273082d09) | Sep 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8fa4158350](https://linux-hardware.org/?probe=8fa4158350) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [201d45c8e0](https://linux-hardware.org/?probe=201d45c8e0) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [508593e110](https://linux-hardware.org/?probe=508593e110) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [0a0b3ced3f](https://linux-hardware.org/?probe=0a0b3ced3f) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [b083b87cc1](https://linux-hardware.org/?probe=b083b87cc1) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [6bf4c617bf](https://linux-hardware.org/?probe=6bf4c617bf) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [2891a2fc4e](https://linux-hardware.org/?probe=2891a2fc4e) | Sep 30, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [1969de09f1](https://linux-hardware.org/?probe=1969de09f1) | Sep 30, 2021 |
| Dell          | Latitude 7480               | Notebook    | [edecedab9c](https://linux-hardware.org/?probe=edecedab9c) | Sep 30, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b8b2183bc1](https://linux-hardware.org/?probe=b8b2183bc1) | Sep 30, 2021 |
| Intel Clie... | LAPBC710                    | Notebook    | [f2535939a1](https://linux-hardware.org/?probe=f2535939a1) | Sep 29, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [75eb93bbe0](https://linux-hardware.org/?probe=75eb93bbe0) | Sep 29, 2021 |
| MSI           | H81M-P33                    | Desktop     | [c7540ecd61](https://linux-hardware.org/?probe=c7540ecd61) | Sep 29, 2021 |
| Timi          | TM1613                      | Notebook    | [f6bb688e77](https://linux-hardware.org/?probe=f6bb688e77) | Sep 29, 2021 |
| Dell          | Precision 3561              | Notebook    | [59bbb944c2](https://linux-hardware.org/?probe=59bbb944c2) | Sep 29, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [885bbac853](https://linux-hardware.org/?probe=885bbac853) | Sep 29, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b8e7519557](https://linux-hardware.org/?probe=b8e7519557) | Sep 29, 2021 |
| Dell          | 07PXPY A02                  | Server      | [9320e12a9a](https://linux-hardware.org/?probe=9320e12a9a) | Sep 29, 2021 |
| Dell          | 07PXPY A02                  | Server      | [5093f7c3c8](https://linux-hardware.org/?probe=5093f7c3c8) | Sep 29, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [d277db28c5](https://linux-hardware.org/?probe=d277db28c5) | Sep 29, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [f7a5bd6c04](https://linux-hardware.org/?probe=f7a5bd6c04) | Sep 29, 2021 |
| Dell          | Latitude D630               | Notebook    | [5e7edac95e](https://linux-hardware.org/?probe=5e7edac95e) | Sep 29, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [01ccd7b321](https://linux-hardware.org/?probe=01ccd7b321) | Sep 28, 2021 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [748880a78e](https://linux-hardware.org/?probe=748880a78e) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [36df7d61be](https://linux-hardware.org/?probe=36df7d61be) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [4514b06137](https://linux-hardware.org/?probe=4514b06137) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [ac6c9be38a](https://linux-hardware.org/?probe=ac6c9be38a) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [36532b595e](https://linux-hardware.org/?probe=36532b595e) | Sep 28, 2021 |
| HP            | Pavilion g6                 | Notebook    | [a349ae4420](https://linux-hardware.org/?probe=a349ae4420) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [b4273a32be](https://linux-hardware.org/?probe=b4273a32be) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [0b6cac4bce](https://linux-hardware.org/?probe=0b6cac4bce) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [3ebd210998](https://linux-hardware.org/?probe=3ebd210998) | Sep 28, 2021 |
| Google        | Enguarde                    | Notebook    | [8ad08b2012](https://linux-hardware.org/?probe=8ad08b2012) | Sep 28, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [b8706044ce](https://linux-hardware.org/?probe=b8706044ce) | Sep 28, 2021 |
| Digiboard     | MPxx                        | Desktop     | [bad4baa7aa](https://linux-hardware.org/?probe=bad4baa7aa) | Sep 28, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [997cfe39d2](https://linux-hardware.org/?probe=997cfe39d2) | Sep 28, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [b633c9e1d1](https://linux-hardware.org/?probe=b633c9e1d1) | Sep 28, 2021 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [55315b68ec](https://linux-hardware.org/?probe=55315b68ec) | Sep 28, 2021 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [5849e72724](https://linux-hardware.org/?probe=5849e72724) | Sep 28, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [05ad040f44](https://linux-hardware.org/?probe=05ad040f44) | Sep 27, 2021 |
| ASUSTek       | X556UAK                     | Notebook    | [6cd310a2c4](https://linux-hardware.org/?probe=6cd310a2c4) | Sep 27, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [6af7a7f851](https://linux-hardware.org/?probe=6af7a7f851) | Sep 27, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [eca410ddc4](https://linux-hardware.org/?probe=eca410ddc4) | Sep 27, 2021 |
| Lenovo        | ThinkPad T430 2349N7G       | Notebook    | [d82d96a0ce](https://linux-hardware.org/?probe=d82d96a0ce) | Sep 27, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [b8427dd0a9](https://linux-hardware.org/?probe=b8427dd0a9) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [61fb50bdf0](https://linux-hardware.org/?probe=61fb50bdf0) | Sep 27, 2021 |
| Dell          | 06FW8P A02                  | Desktop     | [029b85826d](https://linux-hardware.org/?probe=029b85826d) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [af3fbbd82c](https://linux-hardware.org/?probe=af3fbbd82c) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [28c82e6c3c](https://linux-hardware.org/?probe=28c82e6c3c) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7a75c1404b](https://linux-hardware.org/?probe=7a75c1404b) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [79aa111080](https://linux-hardware.org/?probe=79aa111080) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [99b52f5b1a](https://linux-hardware.org/?probe=99b52f5b1a) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7e50f2bf77](https://linux-hardware.org/?probe=7e50f2bf77) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d516cbbc97](https://linux-hardware.org/?probe=d516cbbc97) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [825770fd12](https://linux-hardware.org/?probe=825770fd12) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8e6770f9bd](https://linux-hardware.org/?probe=8e6770f9bd) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a022c3ec02](https://linux-hardware.org/?probe=a022c3ec02) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [991e447de1](https://linux-hardware.org/?probe=991e447de1) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3470189758](https://linux-hardware.org/?probe=3470189758) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8a23b4112f](https://linux-hardware.org/?probe=8a23b4112f) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1843bfdb65](https://linux-hardware.org/?probe=1843bfdb65) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bc4d5fd16b](https://linux-hardware.org/?probe=bc4d5fd16b) | Sep 27, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a01dd88bfb](https://linux-hardware.org/?probe=a01dd88bfb) | Sep 27, 2021 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [c0104aa33d](https://linux-hardware.org/?probe=c0104aa33d) | Sep 27, 2021 |
| Lenovo        | IdeaPad U510 4941           | Notebook    | [f0f189cfc9](https://linux-hardware.org/?probe=f0f189cfc9) | Sep 27, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [9870240430](https://linux-hardware.org/?probe=9870240430) | Sep 27, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [85925128ef](https://linux-hardware.org/?probe=85925128ef) | Sep 27, 2021 |
| HP            | G61                         | Notebook    | [348bab0a1b](https://linux-hardware.org/?probe=348bab0a1b) | Sep 27, 2021 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [ee4f0f6f02](https://linux-hardware.org/?probe=ee4f0f6f02) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | Notebook    | [721c266b6b](https://linux-hardware.org/?probe=721c266b6b) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | Notebook    | [00d9651c96](https://linux-hardware.org/?probe=00d9651c96) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [f290c9b80f](https://linux-hardware.org/?probe=f290c9b80f) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [82bd2ec7eb](https://linux-hardware.org/?probe=82bd2ec7eb) | Sep 27, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [f11ad64d60](https://linux-hardware.org/?probe=f11ad64d60) | Sep 26, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [5236361305](https://linux-hardware.org/?probe=5236361305) | Sep 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8f8f724934](https://linux-hardware.org/?probe=8f8f724934) | Sep 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3b68a00361](https://linux-hardware.org/?probe=3b68a00361) | Sep 26, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [6500bed04d](https://linux-hardware.org/?probe=6500bed04d) | Sep 26, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [abf2c60d3f](https://linux-hardware.org/?probe=abf2c60d3f) | Sep 26, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [97a2a90138](https://linux-hardware.org/?probe=97a2a90138) | Sep 26, 2021 |
| ASUSTek       | TUF GAMING H570-PRO         | Desktop     | [97c090583f](https://linux-hardware.org/?probe=97c090583f) | Sep 26, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [26897714a0](https://linux-hardware.org/?probe=26897714a0) | Sep 26, 2021 |
| Dell          | 018D1Y A00                  | Desktop     | [7ffbeea841](https://linux-hardware.org/?probe=7ffbeea841) | Sep 26, 2021 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [4949f4edef](https://linux-hardware.org/?probe=4949f4edef) | Sep 26, 2021 |
| Toshiba       | Satellite C655D             | Notebook    | [7742f4cfe0](https://linux-hardware.org/?probe=7742f4cfe0) | Sep 26, 2021 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [1f56f02f1d](https://linux-hardware.org/?probe=1f56f02f1d) | Sep 26, 2021 |
| Acer          | TravelMate 2490             | Notebook    | [b09a0d7779](https://linux-hardware.org/?probe=b09a0d7779) | Sep 25, 2021 |
| ECS           | G31T-M9                     | Desktop     | [e0cdbe10a3](https://linux-hardware.org/?probe=e0cdbe10a3) | Sep 25, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [0c67accead](https://linux-hardware.org/?probe=0c67accead) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [10ce8f4e5e](https://linux-hardware.org/?probe=10ce8f4e5e) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b62637ba85](https://linux-hardware.org/?probe=b62637ba85) | Sep 25, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [3b61d0a304](https://linux-hardware.org/?probe=3b61d0a304) | Sep 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [2762c5237d](https://linux-hardware.org/?probe=2762c5237d) | Sep 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [7a1202630f](https://linux-hardware.org/?probe=7a1202630f) | Sep 25, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [4d798633db](https://linux-hardware.org/?probe=4d798633db) | Sep 25, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a97e17fc48](https://linux-hardware.org/?probe=a97e17fc48) | Sep 25, 2021 |
| Dell          | G3 3590                     | Notebook    | [519cea3f38](https://linux-hardware.org/?probe=519cea3f38) | Sep 25, 2021 |
| Dell          | G3 3590                     | Notebook    | [bb25c895cf](https://linux-hardware.org/?probe=bb25c895cf) | Sep 25, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [11ebd06d5f](https://linux-hardware.org/?probe=11ebd06d5f) | Sep 25, 2021 |
| HP            | ProBook 4530s               | Notebook    | [0fc1845cd7](https://linux-hardware.org/?probe=0fc1845cd7) | Sep 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [e9d692e16d](https://linux-hardware.org/?probe=e9d692e16d) | Sep 24, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [76445d703b](https://linux-hardware.org/?probe=76445d703b) | Sep 24, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [c654d6756a](https://linux-hardware.org/?probe=c654d6756a) | Sep 24, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [22132026c3](https://linux-hardware.org/?probe=22132026c3) | Sep 24, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [64af4c4882](https://linux-hardware.org/?probe=64af4c4882) | Sep 24, 2021 |
| Intel         | S1200RP G62251-405          | Server      | [20bb0a8951](https://linux-hardware.org/?probe=20bb0a8951) | Sep 24, 2021 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [652a4e63cd](https://linux-hardware.org/?probe=652a4e63cd) | Sep 24, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | Notebook    | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Dell          | Precision M4800             | Notebook    | [1d4a25cfec](https://linux-hardware.org/?probe=1d4a25cfec) | Sep 24, 2021 |
| Acer          | Revo 70                     | Desktop     | [beb207e679](https://linux-hardware.org/?probe=beb207e679) | Sep 24, 2021 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [5e1a7fc6bc](https://linux-hardware.org/?probe=5e1a7fc6bc) | Sep 24, 2021 |
| ASRock        | AM1B-ITX                    | Desktop     | [5ffe158a0b](https://linux-hardware.org/?probe=5ffe158a0b) | Sep 24, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [166930508c](https://linux-hardware.org/?probe=166930508c) | Sep 24, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [fbe6b1147d](https://linux-hardware.org/?probe=fbe6b1147d) | Sep 24, 2021 |
| Acer          | TravelMate P273             | Notebook    | [125707a56f](https://linux-hardware.org/?probe=125707a56f) | Sep 24, 2021 |
| Lenovo        | ThinkStation S20 4105L1U    | Desktop     | [593eda37d7](https://linux-hardware.org/?probe=593eda37d7) | Sep 23, 2021 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [daab62b41a](https://linux-hardware.org/?probe=daab62b41a) | Sep 23, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [11cfe1c6c6](https://linux-hardware.org/?probe=11cfe1c6c6) | Sep 23, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a9d4d9e61b](https://linux-hardware.org/?probe=a9d4d9e61b) | Sep 23, 2021 |
| Acer          | Revo 70                     | Desktop     | [138db946a6](https://linux-hardware.org/?probe=138db946a6) | Sep 23, 2021 |
| MSI           | GE70 2QE                    | Notebook    | [b1cbbbd78f](https://linux-hardware.org/?probe=b1cbbbd78f) | Sep 23, 2021 |
| ASUSTek       | 1015BXO                     | Notebook    | [0f2bd07e92](https://linux-hardware.org/?probe=0f2bd07e92) | Sep 23, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [5ddd391946](https://linux-hardware.org/?probe=5ddd391946) | Sep 23, 2021 |
| Acer          | Aspire Z3771                | All in one  | [b31e4d7238](https://linux-hardware.org/?probe=b31e4d7238) | Sep 23, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [b77c25619c](https://linux-hardware.org/?probe=b77c25619c) | Sep 23, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [8d162e55d8](https://linux-hardware.org/?probe=8d162e55d8) | Sep 23, 2021 |
| Acer          | Aspire Z3771                | All in one  | [b5fc5f1ee1](https://linux-hardware.org/?probe=b5fc5f1ee1) | Sep 23, 2021 |
| ASRock        | 760GM-HD                    | Desktop     | [3e95020892](https://linux-hardware.org/?probe=3e95020892) | Sep 23, 2021 |
| ASRock        | 760GM-HD                    | Desktop     | [f43227bf66](https://linux-hardware.org/?probe=f43227bf66) | Sep 23, 2021 |
| ASRock        | AM1B-ITX                    | Desktop     | [5896638049](https://linux-hardware.org/?probe=5896638049) | Sep 22, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [f214b7efbe](https://linux-hardware.org/?probe=f214b7efbe) | Sep 22, 2021 |
| HP            | 15                          | Notebook    | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b1fd2fc90a](https://linux-hardware.org/?probe=b1fd2fc90a) | Sep 22, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e36127ceb6](https://linux-hardware.org/?probe=e36127ceb6) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [beea39044c](https://linux-hardware.org/?probe=beea39044c) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [48b0ac8f13](https://linux-hardware.org/?probe=48b0ac8f13) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e7e1e964b7](https://linux-hardware.org/?probe=e7e1e964b7) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [74924ea2e4](https://linux-hardware.org/?probe=74924ea2e4) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5ff0a78d73](https://linux-hardware.org/?probe=5ff0a78d73) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [daf72e6a78](https://linux-hardware.org/?probe=daf72e6a78) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b6b9dd27e1](https://linux-hardware.org/?probe=b6b9dd27e1) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [359496edc0](https://linux-hardware.org/?probe=359496edc0) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [da848bd94a](https://linux-hardware.org/?probe=da848bd94a) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b49beb821b](https://linux-hardware.org/?probe=b49beb821b) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9d5d7d92f2](https://linux-hardware.org/?probe=9d5d7d92f2) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [24924d259f](https://linux-hardware.org/?probe=24924d259f) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [cabfc0b798](https://linux-hardware.org/?probe=cabfc0b798) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7bd83fb3a6](https://linux-hardware.org/?probe=7bd83fb3a6) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d3c7607377](https://linux-hardware.org/?probe=d3c7607377) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a14febce4c](https://linux-hardware.org/?probe=a14febce4c) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0ceb88188b](https://linux-hardware.org/?probe=0ceb88188b) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [04cecd0992](https://linux-hardware.org/?probe=04cecd0992) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [259707c0a4](https://linux-hardware.org/?probe=259707c0a4) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [366475c03d](https://linux-hardware.org/?probe=366475c03d) | Sep 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [72f179ec58](https://linux-hardware.org/?probe=72f179ec58) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [95ba69ad89](https://linux-hardware.org/?probe=95ba69ad89) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [972685a299](https://linux-hardware.org/?probe=972685a299) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [48dc96e8fa](https://linux-hardware.org/?probe=48dc96e8fa) | Sep 22, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4dab5d9a57](https://linux-hardware.org/?probe=4dab5d9a57) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [50f1e050a8](https://linux-hardware.org/?probe=50f1e050a8) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [37c5e8334c](https://linux-hardware.org/?probe=37c5e8334c) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [581dba008c](https://linux-hardware.org/?probe=581dba008c) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [635bf47b02](https://linux-hardware.org/?probe=635bf47b02) | Sep 22, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [8a38fba20f](https://linux-hardware.org/?probe=8a38fba20f) | Sep 22, 2021 |
| ASUSTek       | P8B75-V                     | Desktop     | [84fc3eb5f2](https://linux-hardware.org/?probe=84fc3eb5f2) | Sep 22, 2021 |
| Lenovo        | Mixx-700-12ISK 80QL         | Notebook    | [090e25b77c](https://linux-hardware.org/?probe=090e25b77c) | Sep 22, 2021 |
| HP            | 8298                        | Desktop     | [5517c4780d](https://linux-hardware.org/?probe=5517c4780d) | Sep 22, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [09083b7dad](https://linux-hardware.org/?probe=09083b7dad) | Sep 22, 2021 |
| ASUSTek       | P8B75-V                     | Desktop     | [cf5436e8a1](https://linux-hardware.org/?probe=cf5436e8a1) | Sep 22, 2021 |
| ECS           | G31T-M9                     | Desktop     | [92ecc52d2f](https://linux-hardware.org/?probe=92ecc52d2f) | Sep 22, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [1e8858844a](https://linux-hardware.org/?probe=1e8858844a) | Sep 22, 2021 |
| Dell          | Latitude E7240              | Notebook    | [7048aa6e8b](https://linux-hardware.org/?probe=7048aa6e8b) | Sep 22, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [ff5e9a45c3](https://linux-hardware.org/?probe=ff5e9a45c3) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0f855cbebc](https://linux-hardware.org/?probe=0f855cbebc) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [57b1733974](https://linux-hardware.org/?probe=57b1733974) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b27cdffcdf](https://linux-hardware.org/?probe=b27cdffcdf) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4fe24a3a03](https://linux-hardware.org/?probe=4fe24a3a03) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b662e38e3e](https://linux-hardware.org/?probe=b662e38e3e) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [19bd58d8fd](https://linux-hardware.org/?probe=19bd58d8fd) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [64b5e6acaf](https://linux-hardware.org/?probe=64b5e6acaf) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [57c15e2ce4](https://linux-hardware.org/?probe=57c15e2ce4) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2376be9dc6](https://linux-hardware.org/?probe=2376be9dc6) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [58bdb95875](https://linux-hardware.org/?probe=58bdb95875) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a578c1a29a](https://linux-hardware.org/?probe=a578c1a29a) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1d02729da0](https://linux-hardware.org/?probe=1d02729da0) | Sep 21, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [5e6cd3a827](https://linux-hardware.org/?probe=5e6cd3a827) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d95d7f2e13](https://linux-hardware.org/?probe=d95d7f2e13) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7b0e4f28fa](https://linux-hardware.org/?probe=7b0e4f28fa) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ac53f68bab](https://linux-hardware.org/?probe=ac53f68bab) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4f1ab6ca31](https://linux-hardware.org/?probe=4f1ab6ca31) | Sep 21, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [0dcd3691cd](https://linux-hardware.org/?probe=0dcd3691cd) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [00785cdd23](https://linux-hardware.org/?probe=00785cdd23) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0a46f82c2e](https://linux-hardware.org/?probe=0a46f82c2e) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [11a2d1bf7a](https://linux-hardware.org/?probe=11a2d1bf7a) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [83c6fbb8a4](https://linux-hardware.org/?probe=83c6fbb8a4) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [aa05fd9839](https://linux-hardware.org/?probe=aa05fd9839) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b58a27a7e6](https://linux-hardware.org/?probe=b58a27a7e6) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [47aabdfd32](https://linux-hardware.org/?probe=47aabdfd32) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f49d1d8152](https://linux-hardware.org/?probe=f49d1d8152) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [242501bd61](https://linux-hardware.org/?probe=242501bd61) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [67a23aca3c](https://linux-hardware.org/?probe=67a23aca3c) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [569ef69c19](https://linux-hardware.org/?probe=569ef69c19) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [906d6fd6f3](https://linux-hardware.org/?probe=906d6fd6f3) | Sep 21, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a9789fc53b](https://linux-hardware.org/?probe=a9789fc53b) | Sep 21, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [4ce9cddd8f](https://linux-hardware.org/?probe=4ce9cddd8f) | Sep 21, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [c2a3074723](https://linux-hardware.org/?probe=c2a3074723) | Sep 21, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [8d112d9531](https://linux-hardware.org/?probe=8d112d9531) | Sep 21, 2021 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [65802f1a29](https://linux-hardware.org/?probe=65802f1a29) | Sep 21, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [f2e1fbb30c](https://linux-hardware.org/?probe=f2e1fbb30c) | Sep 21, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [d6e37b9488](https://linux-hardware.org/?probe=d6e37b9488) | Sep 21, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [14ea1aaa38](https://linux-hardware.org/?probe=14ea1aaa38) | Sep 21, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [b767020eb6](https://linux-hardware.org/?probe=b767020eb6) | Sep 21, 2021 |
| Intel         | DQ35JO AAD82085-800         | Desktop     | [3751d2399e](https://linux-hardware.org/?probe=3751d2399e) | Sep 21, 2021 |
| Lenovo        | ThinkPad T480S 20L7002HC... | Notebook    | [18b74e9f12](https://linux-hardware.org/?probe=18b74e9f12) | Sep 21, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [ab40e7b1de](https://linux-hardware.org/?probe=ab40e7b1de) | Sep 21, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [13687ea608](https://linux-hardware.org/?probe=13687ea608) | Sep 21, 2021 |
| ASUSTek       | K50IN                       | Notebook    | [7cdaef32aa](https://linux-hardware.org/?probe=7cdaef32aa) | Sep 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [203ccd91be](https://linux-hardware.org/?probe=203ccd91be) | Sep 20, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [e8748906aa](https://linux-hardware.org/?probe=e8748906aa) | Sep 20, 2021 |
| MSI           | GE70 2QE                    | Notebook    | [a8b9147ea7](https://linux-hardware.org/?probe=a8b9147ea7) | Sep 20, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [22262e98a5](https://linux-hardware.org/?probe=22262e98a5) | Sep 20, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [c266841471](https://linux-hardware.org/?probe=c266841471) | Sep 20, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [81802596f8](https://linux-hardware.org/?probe=81802596f8) | Sep 20, 2021 |
| HP            | Pavilion g6                 | Notebook    | [d7ce22ebcb](https://linux-hardware.org/?probe=d7ce22ebcb) | Sep 20, 2021 |
| HP            | Pavilion g6                 | Notebook    | [3c060f3910](https://linux-hardware.org/?probe=3c060f3910) | Sep 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0UM0... | Notebook    | [bcb44edae6](https://linux-hardware.org/?probe=bcb44edae6) | Sep 20, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7e46c0bea0](https://linux-hardware.org/?probe=7e46c0bea0) | Sep 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0UM0... | Notebook    | [d623d8381b](https://linux-hardware.org/?probe=d623d8381b) | Sep 20, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| Lenovo        | ThinkPad P53 20QQA004CD     | Notebook    | [50b6533131](https://linux-hardware.org/?probe=50b6533131) | Sep 20, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d5776c4fd0](https://linux-hardware.org/?probe=d5776c4fd0) | Sep 20, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [7be63eda40](https://linux-hardware.org/?probe=7be63eda40) | Sep 20, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [72c81ecb73](https://linux-hardware.org/?probe=72c81ecb73) | Sep 19, 2021 |
| HP            | 8433 11                     | Desktop     | [5c7a7c98e8](https://linux-hardware.org/?probe=5c7a7c98e8) | Sep 19, 2021 |
| HP            | 225E                        | Desktop     | [eadad0eb90](https://linux-hardware.org/?probe=eadad0eb90) | Sep 19, 2021 |
| MSI           | U270 series                 | Notebook    | [6b98f78732](https://linux-hardware.org/?probe=6b98f78732) | Sep 19, 2021 |
| Acer          | AOA110                      | Notebook    | [a54c248743](https://linux-hardware.org/?probe=a54c248743) | Sep 19, 2021 |
| HP            | Pavilion dv6                | Notebook    | [b4d25f6f3a](https://linux-hardware.org/?probe=b4d25f6f3a) | Sep 19, 2021 |
| Sony          | VGN-CR21Z_N                 | Notebook    | [6fc19f4c67](https://linux-hardware.org/?probe=6fc19f4c67) | Sep 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [5dabdbd945](https://linux-hardware.org/?probe=5dabdbd945) | Sep 19, 2021 |
| Gigabyte      | GB-BLCE-4105R               | Desktop     | [3a1284b530](https://linux-hardware.org/?probe=3a1284b530) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [61fd64b037](https://linux-hardware.org/?probe=61fd64b037) | Sep 19, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [7a0ce4b17e](https://linux-hardware.org/?probe=7a0ce4b17e) | Sep 19, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [10c1838b9d](https://linux-hardware.org/?probe=10c1838b9d) | Sep 19, 2021 |
| MSI           | U270 series                 | Notebook    | [725e0a6a36](https://linux-hardware.org/?probe=725e0a6a36) | Sep 18, 2021 |
| Acer          | Aspire 5560                 | Notebook    | [f35af81d19](https://linux-hardware.org/?probe=f35af81d19) | Sep 18, 2021 |
| ASUSTek       | PN62S                       | Mini pc     | [7a01c63401](https://linux-hardware.org/?probe=7a01c63401) | Sep 18, 2021 |
| Gigabyte      | P35-DS3                     | Desktop     | [32413546ce](https://linux-hardware.org/?probe=32413546ce) | Sep 18, 2021 |
| Dell          | Latitude E7450              | Notebook    | [f5963dc359](https://linux-hardware.org/?probe=f5963dc359) | Sep 18, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [6dcb59c0e5](https://linux-hardware.org/?probe=6dcb59c0e5) | Sep 18, 2021 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [6ce6f8e7f7](https://linux-hardware.org/?probe=6ce6f8e7f7) | Sep 17, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1ca8880edb](https://linux-hardware.org/?probe=1ca8880edb) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [ebc7aac8d2](https://linux-hardware.org/?probe=ebc7aac8d2) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [cc91d3d293](https://linux-hardware.org/?probe=cc91d3d293) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [cf7b743325](https://linux-hardware.org/?probe=cf7b743325) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [58efd773fc](https://linux-hardware.org/?probe=58efd773fc) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [6f61a4bed1](https://linux-hardware.org/?probe=6f61a4bed1) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [2847b27014](https://linux-hardware.org/?probe=2847b27014) | Sep 17, 2021 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [f6cde497b4](https://linux-hardware.org/?probe=f6cde497b4) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [ca5062256b](https://linux-hardware.org/?probe=ca5062256b) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [8b0908956f](https://linux-hardware.org/?probe=8b0908956f) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [35b84b3b23](https://linux-hardware.org/?probe=35b84b3b23) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [fd3abf36d9](https://linux-hardware.org/?probe=fd3abf36d9) | Sep 17, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [49001d8064](https://linux-hardware.org/?probe=49001d8064) | Sep 17, 2021 |
| Lenovo        | IdeaPad U510 4941           | Notebook    | [f5774645c1](https://linux-hardware.org/?probe=f5774645c1) | Sep 17, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0f6db66354](https://linux-hardware.org/?probe=0f6db66354) | Sep 17, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3fde672bb3](https://linux-hardware.org/?probe=3fde672bb3) | Sep 17, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [2179e59b37](https://linux-hardware.org/?probe=2179e59b37) | Sep 17, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [84394a400e](https://linux-hardware.org/?probe=84394a400e) | Sep 17, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [726f5ed51f](https://linux-hardware.org/?probe=726f5ed51f) | Sep 17, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [e0307085f3](https://linux-hardware.org/?probe=e0307085f3) | Sep 17, 2021 |
| MSI           | GE70 2QE                    | Notebook    | [e7b42c85f1](https://linux-hardware.org/?probe=e7b42c85f1) | Sep 17, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [abd7f0d0a1](https://linux-hardware.org/?probe=abd7f0d0a1) | Sep 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c8208bc767](https://linux-hardware.org/?probe=c8208bc767) | Sep 17, 2021 |
| MSI           | GF75 Thin 9SC               | Notebook    | [47a6cd4031](https://linux-hardware.org/?probe=47a6cd4031) | Sep 17, 2021 |
| MSI           | GE70 2QE                    | Notebook    | [8d4eff5ca2](https://linux-hardware.org/?probe=8d4eff5ca2) | Sep 17, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [f226485da3](https://linux-hardware.org/?probe=f226485da3) | Sep 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [643fafdceb](https://linux-hardware.org/?probe=643fafdceb) | Sep 17, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [381f6460b0](https://linux-hardware.org/?probe=381f6460b0) | Sep 17, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [77f32a8e42](https://linux-hardware.org/?probe=77f32a8e42) | Sep 17, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [e801613095](https://linux-hardware.org/?probe=e801613095) | Sep 17, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [fb0c3317e3](https://linux-hardware.org/?probe=fb0c3317e3) | Sep 17, 2021 |
| MSI           | Z370 PC PRO                 | Desktop     | [c79178e6db](https://linux-hardware.org/?probe=c79178e6db) | Sep 17, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [5282f852aa](https://linux-hardware.org/?probe=5282f852aa) | Sep 17, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [dd5496fa35](https://linux-hardware.org/?probe=dd5496fa35) | Sep 17, 2021 |
| Timi          | TM1801                      | Notebook    | [d0919977cb](https://linux-hardware.org/?probe=d0919977cb) | Sep 17, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [722f184570](https://linux-hardware.org/?probe=722f184570) | Sep 17, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [1fe7a4c597](https://linux-hardware.org/?probe=1fe7a4c597) | Sep 17, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [cbe5d18ac2](https://linux-hardware.org/?probe=cbe5d18ac2) | Sep 17, 2021 |
| Libretrend    | LT1000                      | Desktop     | [781fa86fea](https://linux-hardware.org/?probe=781fa86fea) | Sep 17, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fb9a8ab054](https://linux-hardware.org/?probe=fb9a8ab054) | Sep 16, 2021 |
| ECS           | G31T-M9                     | Desktop     | [ba4a294b69](https://linux-hardware.org/?probe=ba4a294b69) | Sep 16, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [d1a7e38fc8](https://linux-hardware.org/?probe=d1a7e38fc8) | Sep 16, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [10c9991f0b](https://linux-hardware.org/?probe=10c9991f0b) | Sep 16, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3ef71721e0](https://linux-hardware.org/?probe=3ef71721e0) | Sep 16, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [df29a592fb](https://linux-hardware.org/?probe=df29a592fb) | Sep 16, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [e8ac4691b0](https://linux-hardware.org/?probe=e8ac4691b0) | Sep 16, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [6b7410fa5c](https://linux-hardware.org/?probe=6b7410fa5c) | Sep 16, 2021 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [6056c96428](https://linux-hardware.org/?probe=6056c96428) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4bb2af8998](https://linux-hardware.org/?probe=4bb2af8998) | Sep 16, 2021 |
| HP            | 83EB                        | All in one  | [cc989948af](https://linux-hardware.org/?probe=cc989948af) | Sep 16, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [233ad54ef9](https://linux-hardware.org/?probe=233ad54ef9) | Sep 16, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [d4e804931a](https://linux-hardware.org/?probe=d4e804931a) | Sep 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ee258307b1](https://linux-hardware.org/?probe=ee258307b1) | Sep 15, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [bec4c36c67](https://linux-hardware.org/?probe=bec4c36c67) | Sep 15, 2021 |
| PC Special... | Standard                    | Notebook    | [1454a60100](https://linux-hardware.org/?probe=1454a60100) | Sep 15, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [af6b84e00b](https://linux-hardware.org/?probe=af6b84e00b) | Sep 15, 2021 |
| Lenovo        | ThinkPad E460 20EUA00AAC    | Notebook    | [c7d8dc11ca](https://linux-hardware.org/?probe=c7d8dc11ca) | Sep 15, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [576b90b734](https://linux-hardware.org/?probe=576b90b734) | Sep 15, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [e9c177240a](https://linux-hardware.org/?probe=e9c177240a) | Sep 15, 2021 |
| Acer          | AO725                       | Notebook    | [68eeff0c2f](https://linux-hardware.org/?probe=68eeff0c2f) | Sep 15, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [730c0eebf9](https://linux-hardware.org/?probe=730c0eebf9) | Sep 14, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [a062985645](https://linux-hardware.org/?probe=a062985645) | Sep 14, 2021 |
| HP            | 8446                        | All in one  | [7744251d76](https://linux-hardware.org/?probe=7744251d76) | Sep 14, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [7e486cd179](https://linux-hardware.org/?probe=7e486cd179) | Sep 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [7f88a77812](https://linux-hardware.org/?probe=7f88a77812) | Sep 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e606ccc75f](https://linux-hardware.org/?probe=e606ccc75f) | Sep 14, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8622681e00](https://linux-hardware.org/?probe=8622681e00) | Sep 14, 2021 |
| Aquarius      | NS585                       | Notebook    | [f2363c7d5e](https://linux-hardware.org/?probe=f2363c7d5e) | Sep 14, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [db3a48e82e](https://linux-hardware.org/?probe=db3a48e82e) | Sep 14, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f6f26d4c8e](https://linux-hardware.org/?probe=f6f26d4c8e) | Sep 14, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [54e89a0f5a](https://linux-hardware.org/?probe=54e89a0f5a) | Sep 14, 2021 |
| Positivo      | POS-PIQ77CL                 | Desktop     | [87ec217aed](https://linux-hardware.org/?probe=87ec217aed) | Sep 14, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [7f6f4bedd3](https://linux-hardware.org/?probe=7f6f4bedd3) | Sep 14, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0561b8a369](https://linux-hardware.org/?probe=0561b8a369) | Sep 13, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [01008b3cfd](https://linux-hardware.org/?probe=01008b3cfd) | Sep 13, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [cd3844f542](https://linux-hardware.org/?probe=cd3844f542) | Sep 13, 2021 |
| MSI           | H81M-P33                    | Desktop     | [b5b64471de](https://linux-hardware.org/?probe=b5b64471de) | Sep 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eb55a1f000](https://linux-hardware.org/?probe=eb55a1f000) | Sep 13, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [3be45aba31](https://linux-hardware.org/?probe=3be45aba31) | Sep 13, 2021 |
| ASRock        | AM1B-ITX                    | Desktop     | [b15ebc1577](https://linux-hardware.org/?probe=b15ebc1577) | Sep 13, 2021 |
| HP            | Notebook                    | Notebook    | [17f4133e28](https://linux-hardware.org/?probe=17f4133e28) | Sep 13, 2021 |
| Supermicro    | X8DTN                       | Server      | [535e5f1d58](https://linux-hardware.org/?probe=535e5f1d58) | Sep 13, 2021 |
| Supermicro    | X8DTN                       | Server      | [39ace40ad6](https://linux-hardware.org/?probe=39ace40ad6) | Sep 13, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [51cf32f87c](https://linux-hardware.org/?probe=51cf32f87c) | Sep 12, 2021 |
| MSI           | Z170-A PRO                  | Desktop     | [5b702a6c05](https://linux-hardware.org/?probe=5b702a6c05) | Sep 12, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [8109d84e42](https://linux-hardware.org/?probe=8109d84e42) | Sep 12, 2021 |
| Lenovo        | ThinkPad E14 20RB0028BR     | Notebook    | [8b1b3a98ba](https://linux-hardware.org/?probe=8b1b3a98ba) | Sep 12, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [cf7cbe9ec0](https://linux-hardware.org/?probe=cf7cbe9ec0) | Sep 12, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [1fc1622a64](https://linux-hardware.org/?probe=1fc1622a64) | Sep 12, 2021 |
| ASUSTek       | M3N                         | Notebook    | [28a5b48a05](https://linux-hardware.org/?probe=28a5b48a05) | Sep 12, 2021 |
| ASUSTek       | M3N                         | Notebook    | [04307947ae](https://linux-hardware.org/?probe=04307947ae) | Sep 12, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | Desktop     | [f81450ac96](https://linux-hardware.org/?probe=f81450ac96) | Sep 11, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c9bcb0db96](https://linux-hardware.org/?probe=c9bcb0db96) | Sep 11, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | Desktop     | [0e9729a88b](https://linux-hardware.org/?probe=0e9729a88b) | Sep 11, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b6d09ad044](https://linux-hardware.org/?probe=b6d09ad044) | Sep 10, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [035ee1f7ec](https://linux-hardware.org/?probe=035ee1f7ec) | Sep 10, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2136b1f58c](https://linux-hardware.org/?probe=2136b1f58c) | Sep 10, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [da3f4572d1](https://linux-hardware.org/?probe=da3f4572d1) | Sep 10, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5598608780](https://linux-hardware.org/?probe=5598608780) | Sep 10, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [795f6bba58](https://linux-hardware.org/?probe=795f6bba58) | Sep 10, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Acer          | Aspire M3420                | Desktop     | [dfd381db06](https://linux-hardware.org/?probe=dfd381db06) | Sep 10, 2021 |
| Acer          | Aspire M3420                | Desktop     | [7a4ab56f68](https://linux-hardware.org/?probe=7a4ab56f68) | Sep 10, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [10c0154577](https://linux-hardware.org/?probe=10c0154577) | Sep 10, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b95c1b013e](https://linux-hardware.org/?probe=b95c1b013e) | Sep 10, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [bbdd0a3b8c](https://linux-hardware.org/?probe=bbdd0a3b8c) | Sep 10, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2377281799](https://linux-hardware.org/?probe=2377281799) | Sep 09, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [13d65a1a4e](https://linux-hardware.org/?probe=13d65a1a4e) | Sep 09, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c2b2ebce62](https://linux-hardware.org/?probe=c2b2ebce62) | Sep 09, 2021 |
| ASUSTek       | X540NA                      | Notebook    | [f14257cc20](https://linux-hardware.org/?probe=f14257cc20) | Sep 09, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8433dfbbb9](https://linux-hardware.org/?probe=8433dfbbb9) | Sep 09, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [3fa68fe391](https://linux-hardware.org/?probe=3fa68fe391) | Sep 09, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8bc230f7dc](https://linux-hardware.org/?probe=8bc230f7dc) | Sep 09, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fb3d977ed2](https://linux-hardware.org/?probe=fb3d977ed2) | Sep 09, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [488fd18d85](https://linux-hardware.org/?probe=488fd18d85) | Sep 09, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [19d6905d9a](https://linux-hardware.org/?probe=19d6905d9a) | Sep 09, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [1ff67401db](https://linux-hardware.org/?probe=1ff67401db) | Sep 09, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [7add887914](https://linux-hardware.org/?probe=7add887914) | Sep 08, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5c6f3696b2](https://linux-hardware.org/?probe=5c6f3696b2) | Sep 08, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [0baa540bf5](https://linux-hardware.org/?probe=0baa540bf5) | Sep 08, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d21daec9ea](https://linux-hardware.org/?probe=d21daec9ea) | Sep 08, 2021 |
| Lenovo        | ThinkPad T430 2349D10       | Notebook    | [11ab5d413d](https://linux-hardware.org/?probe=11ab5d413d) | Sep 08, 2021 |
| Foxconn       | nT-A3000 series FAB         | Desktop     | [9e22d6dc70](https://linux-hardware.org/?probe=9e22d6dc70) | Sep 08, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [f8aae7ade2](https://linux-hardware.org/?probe=f8aae7ade2) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a826f2f4c9](https://linux-hardware.org/?probe=a826f2f4c9) | Sep 08, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [5aa6e46608](https://linux-hardware.org/?probe=5aa6e46608) | Sep 08, 2021 |
| Lenovo        | ThinkPad X230 2325B12       | Notebook    | [a55f42da78](https://linux-hardware.org/?probe=a55f42da78) | Sep 08, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [2626e29c5f](https://linux-hardware.org/?probe=2626e29c5f) | Sep 08, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [04ecb299d9](https://linux-hardware.org/?probe=04ecb299d9) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [b521805956](https://linux-hardware.org/?probe=b521805956) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [c4f6c7da11](https://linux-hardware.org/?probe=c4f6c7da11) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a4acb4b4d7](https://linux-hardware.org/?probe=a4acb4b4d7) | Sep 08, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [33ae3adcc6](https://linux-hardware.org/?probe=33ae3adcc6) | Sep 08, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [cb2158566c](https://linux-hardware.org/?probe=cb2158566c) | Sep 08, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [65e545345d](https://linux-hardware.org/?probe=65e545345d) | Sep 07, 2021 |
| ASUSTek       | K52F                        | Notebook    | [b1f04036d8](https://linux-hardware.org/?probe=b1f04036d8) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | Notebook    | [19cfc85441](https://linux-hardware.org/?probe=19cfc85441) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [55f595b53f](https://linux-hardware.org/?probe=55f595b53f) | Sep 07, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [41ab6b2f21](https://linux-hardware.org/?probe=41ab6b2f21) | Sep 07, 2021 |
| ASUSTek       | K52F                        | Notebook    | [0d72cf73ac](https://linux-hardware.org/?probe=0d72cf73ac) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | Notebook    | [498dd20152](https://linux-hardware.org/?probe=498dd20152) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6fc35e97d8](https://linux-hardware.org/?probe=6fc35e97d8) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [5acaf42867](https://linux-hardware.org/?probe=5acaf42867) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [4d6ad821df](https://linux-hardware.org/?probe=4d6ad821df) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [511d2e120b](https://linux-hardware.org/?probe=511d2e120b) | Sep 07, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [13256468d1](https://linux-hardware.org/?probe=13256468d1) | Sep 07, 2021 |
| ASUSTek       | P5Q3                        | Desktop     | [3f08e7bf37](https://linux-hardware.org/?probe=3f08e7bf37) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [bcd1f7553d](https://linux-hardware.org/?probe=bcd1f7553d) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [0c0ccb21d8](https://linux-hardware.org/?probe=0c0ccb21d8) | Sep 07, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [cf59508b79](https://linux-hardware.org/?probe=cf59508b79) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [1c85c31f57](https://linux-hardware.org/?probe=1c85c31f57) | Sep 07, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [0183fb8d78](https://linux-hardware.org/?probe=0183fb8d78) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [6cf8ebc24c](https://linux-hardware.org/?probe=6cf8ebc24c) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [bf328adcb8](https://linux-hardware.org/?probe=bf328adcb8) | Sep 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [09e28c958c](https://linux-hardware.org/?probe=09e28c958c) | Sep 07, 2021 |
| HP            | 212A                        | Desktop     | [7f51e384f7](https://linux-hardware.org/?probe=7f51e384f7) | Sep 07, 2021 |
| HP            | 212A                        | Desktop     | [c89a2196ab](https://linux-hardware.org/?probe=c89a2196ab) | Sep 07, 2021 |
| Dell          | Latitude 7480               | Notebook    | [844ab8df38](https://linux-hardware.org/?probe=844ab8df38) | Sep 06, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [9256f3fece](https://linux-hardware.org/?probe=9256f3fece) | Sep 06, 2021 |
| ASUSTek       | STRIX B250H GAMING          | Desktop     | [265822ee2e](https://linux-hardware.org/?probe=265822ee2e) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [7f6c0d6337](https://linux-hardware.org/?probe=7f6c0d6337) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [e6ea97df06](https://linux-hardware.org/?probe=e6ea97df06) | Sep 06, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [a0d1d9b2e6](https://linux-hardware.org/?probe=a0d1d9b2e6) | Sep 06, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [4aec08beef](https://linux-hardware.org/?probe=4aec08beef) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [3aedb68952](https://linux-hardware.org/?probe=3aedb68952) | Sep 06, 2021 |
| Samsung       | NC10                        | Notebook    | [98ba59d155](https://linux-hardware.org/?probe=98ba59d155) | Sep 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e42726b566](https://linux-hardware.org/?probe=e42726b566) | Sep 06, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [b6e28c84c8](https://linux-hardware.org/?probe=b6e28c84c8) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2a4adea555](https://linux-hardware.org/?probe=2a4adea555) | Sep 05, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [28c59930e4](https://linux-hardware.org/?probe=28c59930e4) | Sep 05, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [20f947223f](https://linux-hardware.org/?probe=20f947223f) | Sep 05, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [fe8833475a](https://linux-hardware.org/?probe=fe8833475a) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [0a1850f760](https://linux-hardware.org/?probe=0a1850f760) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [4ba7363e9e](https://linux-hardware.org/?probe=4ba7363e9e) | Sep 05, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [18fe596fba](https://linux-hardware.org/?probe=18fe596fba) | Sep 04, 2021 |
| HP            | Presario CQ62               | Notebook    | [4cdec89015](https://linux-hardware.org/?probe=4cdec89015) | Sep 04, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [af5a140c2e](https://linux-hardware.org/?probe=af5a140c2e) | Sep 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [9e235c4228](https://linux-hardware.org/?probe=9e235c4228) | Sep 04, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [0e32e6945b](https://linux-hardware.org/?probe=0e32e6945b) | Sep 03, 2021 |
| ASRock        | TRX40 Creator               | Desktop     | [0734c9bbd0](https://linux-hardware.org/?probe=0734c9bbd0) | Sep 03, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [db35296aa1](https://linux-hardware.org/?probe=db35296aa1) | Sep 03, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [fafd031d1f](https://linux-hardware.org/?probe=fafd031d1f) | Sep 03, 2021 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [ced0e47579](https://linux-hardware.org/?probe=ced0e47579) | Sep 02, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1449c0a9cd](https://linux-hardware.org/?probe=1449c0a9cd) | Sep 02, 2021 |
| ASUSTek       | UX303LNB                    | Notebook    | [e0756d7ae6](https://linux-hardware.org/?probe=e0756d7ae6) | Sep 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5d183d4587](https://linux-hardware.org/?probe=5d183d4587) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [666c4fef08](https://linux-hardware.org/?probe=666c4fef08) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [d6ee033eb7](https://linux-hardware.org/?probe=d6ee033eb7) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [28fbb3d82d](https://linux-hardware.org/?probe=28fbb3d82d) | Sep 02, 2021 |
| ECS           | G31T-M9                     | Desktop     | [0757de543d](https://linux-hardware.org/?probe=0757de543d) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [27c2ebc917](https://linux-hardware.org/?probe=27c2ebc917) | Sep 02, 2021 |
| Gigabyte      | 8I945P-G                    | Desktop     | [a1eb33a5f1](https://linux-hardware.org/?probe=a1eb33a5f1) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [1d9e3a7503](https://linux-hardware.org/?probe=1d9e3a7503) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [97c9e2dc1f](https://linux-hardware.org/?probe=97c9e2dc1f) | Sep 02, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d4c78cc3c4](https://linux-hardware.org/?probe=d4c78cc3c4) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ca0e00bc0f](https://linux-hardware.org/?probe=ca0e00bc0f) | Sep 01, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | Notebook    | [f1cad98694](https://linux-hardware.org/?probe=f1cad98694) | Sep 01, 2021 |
| ECS           | H61H2-M13                   | Desktop     | [e96ab5fb39](https://linux-hardware.org/?probe=e96ab5fb39) | Sep 01, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [78fafc3314](https://linux-hardware.org/?probe=78fafc3314) | Sep 01, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [d542a6b8f9](https://linux-hardware.org/?probe=d542a6b8f9) | Sep 01, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [d8083308fc](https://linux-hardware.org/?probe=d8083308fc) | Sep 01, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [12a5a0f9c5](https://linux-hardware.org/?probe=12a5a0f9c5) | Sep 01, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [450ffd830c](https://linux-hardware.org/?probe=450ffd830c) | Sep 01, 2021 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [dadb397ef1](https://linux-hardware.org/?probe=dadb397ef1) | Sep 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3267eec643](https://linux-hardware.org/?probe=3267eec643) | Sep 01, 2021 |
| Pegatron      | TRUCKEE                     | Desktop     | [68f16e9542](https://linux-hardware.org/?probe=68f16e9542) | Sep 01, 2021 |
| Dell          | 094MXG A00                  | All in one  | [7fe3c46d72](https://linux-hardware.org/?probe=7fe3c46d72) | Sep 01, 2021 |
| Timi          | TM1613                      | Notebook    | [f25eeca060](https://linux-hardware.org/?probe=f25eeca060) | Sep 01, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | Notebook    | [bc224fb15f](https://linux-hardware.org/?probe=bc224fb15f) | Aug 31, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [9510c18df6](https://linux-hardware.org/?probe=9510c18df6) | Aug 31, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [6521e0d6be](https://linux-hardware.org/?probe=6521e0d6be) | Aug 31, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [783955d696](https://linux-hardware.org/?probe=783955d696) | Aug 31, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | Notebook    | [db94fcaf10](https://linux-hardware.org/?probe=db94fcaf10) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [9c31643811](https://linux-hardware.org/?probe=9c31643811) | Aug 31, 2021 |
| ASUSTek       | P7P55D-E                    | Desktop     | [4c05b36e94](https://linux-hardware.org/?probe=4c05b36e94) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [baf38e8736](https://linux-hardware.org/?probe=baf38e8736) | Aug 31, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [33a45018fc](https://linux-hardware.org/?probe=33a45018fc) | Aug 31, 2021 |
| Pine Micro... | Pine64+                     | Soc         | [433d54a30d](https://linux-hardware.org/?probe=433d54a30d) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [37c3e457bc](https://linux-hardware.org/?probe=37c3e457bc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [0d38048f46](https://linux-hardware.org/?probe=0d38048f46) | Aug 31, 2021 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [d7eaf975a0](https://linux-hardware.org/?probe=d7eaf975a0) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [df9b303eec](https://linux-hardware.org/?probe=df9b303eec) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [d9af23fb86](https://linux-hardware.org/?probe=d9af23fb86) | Aug 31, 2021 |
| AOpen         | D1001 C26361-D1001          | Desktop     | [e27239d870](https://linux-hardware.org/?probe=e27239d870) | Aug 31, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [1470c8cc7f](https://linux-hardware.org/?probe=1470c8cc7f) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [ba7144c0dc](https://linux-hardware.org/?probe=ba7144c0dc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [7204a77b38](https://linux-hardware.org/?probe=7204a77b38) | Aug 31, 2021 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [b26e82328a](https://linux-hardware.org/?probe=b26e82328a) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [70835c3aa7](https://linux-hardware.org/?probe=70835c3aa7) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [3e22f55c7b](https://linux-hardware.org/?probe=3e22f55c7b) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b73b366bb6](https://linux-hardware.org/?probe=b73b366bb6) | Aug 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [c6a754129a](https://linux-hardware.org/?probe=c6a754129a) | Aug 30, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [e1b2dc4810](https://linux-hardware.org/?probe=e1b2dc4810) | Aug 30, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e94ab065a3](https://linux-hardware.org/?probe=e94ab065a3) | Aug 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [a251dca266](https://linux-hardware.org/?probe=a251dca266) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [b1425fa900](https://linux-hardware.org/?probe=b1425fa900) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b5a84f215b](https://linux-hardware.org/?probe=b5a84f215b) | Aug 30, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [f2dbdea931](https://linux-hardware.org/?probe=f2dbdea931) | Aug 30, 2021 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [b7b3f489f2](https://linux-hardware.org/?probe=b7b3f489f2) | Aug 30, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [ca46b71791](https://linux-hardware.org/?probe=ca46b71791) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [d255f48a39](https://linux-hardware.org/?probe=d255f48a39) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [dc0abe4fcd](https://linux-hardware.org/?probe=dc0abe4fcd) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [fc61c24624](https://linux-hardware.org/?probe=fc61c24624) | Aug 30, 2021 |
| Dell          | Latitude E6330              | Notebook    | [95d65375e2](https://linux-hardware.org/?probe=95d65375e2) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [9d1b86643e](https://linux-hardware.org/?probe=9d1b86643e) | Aug 30, 2021 |
| Lenovo        | ThinkPad T61 7661BF3        | Notebook    | [69b6d76471](https://linux-hardware.org/?probe=69b6d76471) | Aug 30, 2021 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [acbb96ba48](https://linux-hardware.org/?probe=acbb96ba48) | Aug 29, 2021 |
| ASUSTek       | K56CB                       | Notebook    | [1a44fc7e8f](https://linux-hardware.org/?probe=1a44fc7e8f) | Aug 29, 2021 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [6fcfbde79d](https://linux-hardware.org/?probe=6fcfbde79d) | Aug 29, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [17ae4593ea](https://linux-hardware.org/?probe=17ae4593ea) | Aug 28, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b9595196ea](https://linux-hardware.org/?probe=b9595196ea) | Aug 28, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [8625d6f2f1](https://linux-hardware.org/?probe=8625d6f2f1) | Aug 28, 2021 |
| Jetway        | 1.0                         | Desktop     | [9c4b8ad466](https://linux-hardware.org/?probe=9c4b8ad466) | Aug 28, 2021 |
| HP            | 0B50 Rev.A                  | All in one  | [4701ae6e71](https://linux-hardware.org/?probe=4701ae6e71) | Aug 27, 2021 |
| MSI           | B150A GAMING PRO            | Desktop     | [06de6cd826](https://linux-hardware.org/?probe=06de6cd826) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [46eacf8d5c](https://linux-hardware.org/?probe=46eacf8d5c) | Aug 27, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [202fe67100](https://linux-hardware.org/?probe=202fe67100) | Aug 27, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [321f53f711](https://linux-hardware.org/?probe=321f53f711) | Aug 27, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [06f4334a82](https://linux-hardware.org/?probe=06f4334a82) | Aug 27, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [d215521170](https://linux-hardware.org/?probe=d215521170) | Aug 27, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [2c85ec0205](https://linux-hardware.org/?probe=2c85ec0205) | Aug 27, 2021 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [7f3a68dd2a](https://linux-hardware.org/?probe=7f3a68dd2a) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [2737cfb67d](https://linux-hardware.org/?probe=2737cfb67d) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [dc9428d8b4](https://linux-hardware.org/?probe=dc9428d8b4) | Aug 27, 2021 |
| Lenovo        | ThinkPad T440p 20AN006GU... | Notebook    | [bca7704bb0](https://linux-hardware.org/?probe=bca7704bb0) | Aug 27, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [14747d88b3](https://linux-hardware.org/?probe=14747d88b3) | Aug 26, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [87904cbe92](https://linux-hardware.org/?probe=87904cbe92) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1c2e910793](https://linux-hardware.org/?probe=1c2e910793) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4a69118897](https://linux-hardware.org/?probe=4a69118897) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [474216fba9](https://linux-hardware.org/?probe=474216fba9) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [76d9383f33](https://linux-hardware.org/?probe=76d9383f33) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [213d3f817b](https://linux-hardware.org/?probe=213d3f817b) | Aug 26, 2021 |
| HP            | 0B0Ch                       | Desktop     | [b5933fde35](https://linux-hardware.org/?probe=b5933fde35) | Aug 26, 2021 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [8c051a0ce9](https://linux-hardware.org/?probe=8c051a0ce9) | Aug 26, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [f26ade88cd](https://linux-hardware.org/?probe=f26ade88cd) | Aug 26, 2021 |
| Dell          | 0WR7PY A00                  | Desktop     | [cb25b1811b](https://linux-hardware.org/?probe=cb25b1811b) | Aug 26, 2021 |
| Gigabyte      | AORUS 15G KB                | Notebook    | [6afefe68d7](https://linux-hardware.org/?probe=6afefe68d7) | Aug 26, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [8dd8862b4b](https://linux-hardware.org/?probe=8dd8862b4b) | Aug 26, 2021 |
| HP            | ProBook 4530s               | Notebook    | [2b4cab4d7c](https://linux-hardware.org/?probe=2b4cab4d7c) | Aug 25, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [7bab6dd9db](https://linux-hardware.org/?probe=7bab6dd9db) | Aug 25, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [a2f161dee0](https://linux-hardware.org/?probe=a2f161dee0) | Aug 25, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [e1e5a14c77](https://linux-hardware.org/?probe=e1e5a14c77) | Aug 25, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [16f399259c](https://linux-hardware.org/?probe=16f399259c) | Aug 25, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [d37f13917f](https://linux-hardware.org/?probe=d37f13917f) | Aug 25, 2021 |
| ASRock        | C2750D4I                    | Desktop     | [6daa3c26bf](https://linux-hardware.org/?probe=6daa3c26bf) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0a79171c9e](https://linux-hardware.org/?probe=0a79171c9e) | Aug 25, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [feed9e2921](https://linux-hardware.org/?probe=feed9e2921) | Aug 25, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [3da8591ac6](https://linux-hardware.org/?probe=3da8591ac6) | Aug 25, 2021 |
| HP            | 630                         | Notebook    | [004d2b364d](https://linux-hardware.org/?probe=004d2b364d) | Aug 25, 2021 |
| Biostar       | Hi-Fi A85W                  | Desktop     | [ffb66dafd4](https://linux-hardware.org/?probe=ffb66dafd4) | Aug 25, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [b06c4079a7](https://linux-hardware.org/?probe=b06c4079a7) | Aug 25, 2021 |
| Dell          | Latitude 7490               | Notebook    | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2882cf9963](https://linux-hardware.org/?probe=2882cf9963) | Aug 25, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [557d74beb9](https://linux-hardware.org/?probe=557d74beb9) | Aug 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [65d82bc8e7](https://linux-hardware.org/?probe=65d82bc8e7) | Aug 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [e1bd0ec7fd](https://linux-hardware.org/?probe=e1bd0ec7fd) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [e5c92fe4ad](https://linux-hardware.org/?probe=e5c92fe4ad) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8a72f87e7b](https://linux-hardware.org/?probe=8a72f87e7b) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [441b8b892e](https://linux-hardware.org/?probe=441b8b892e) | Aug 24, 2021 |
| ASRock        | P4i65G                      | Desktop     | [43ce3e711f](https://linux-hardware.org/?probe=43ce3e711f) | Aug 24, 2021 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [c2179206a9](https://linux-hardware.org/?probe=c2179206a9) | Aug 24, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [1f257714a9](https://linux-hardware.org/?probe=1f257714a9) | Aug 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [102aea0211](https://linux-hardware.org/?probe=102aea0211) | Aug 24, 2021 |
| Unknown       | 1.0                         | Desktop     | [5e638360a8](https://linux-hardware.org/?probe=5e638360a8) | Aug 24, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f755838fd8](https://linux-hardware.org/?probe=f755838fd8) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5cc74103a8](https://linux-hardware.org/?probe=5cc74103a8) | Aug 24, 2021 |
| HP            | 250 G4                      | Notebook    | [5d47aa9804](https://linux-hardware.org/?probe=5d47aa9804) | Aug 24, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [77ce457de4](https://linux-hardware.org/?probe=77ce457de4) | Aug 24, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [df0fa8e968](https://linux-hardware.org/?probe=df0fa8e968) | Aug 24, 2021 |
| ASUSTek       | GA35DX                      | Desktop     | [3843ea048e](https://linux-hardware.org/?probe=3843ea048e) | Aug 24, 2021 |
| Sony          | VPCF115FM                   | Notebook    | [9f9abf79b2](https://linux-hardware.org/?probe=9f9abf79b2) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8a88eabb1c](https://linux-hardware.org/?probe=8a88eabb1c) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c4ecd51a21](https://linux-hardware.org/?probe=c4ecd51a21) | Aug 23, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [1c9d3bb8b4](https://linux-hardware.org/?probe=1c9d3bb8b4) | Aug 23, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [e92004f46a](https://linux-hardware.org/?probe=e92004f46a) | Aug 23, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [14af647cc5](https://linux-hardware.org/?probe=14af647cc5) | Aug 23, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [06c9a1ed3a](https://linux-hardware.org/?probe=06c9a1ed3a) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5bc9372587](https://linux-hardware.org/?probe=5bc9372587) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8bcb9e62e1](https://linux-hardware.org/?probe=8bcb9e62e1) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [6c44c4f7e3](https://linux-hardware.org/?probe=6c44c4f7e3) | Aug 23, 2021 |
| Google        | Enguarde                    | Notebook    | [12a2003770](https://linux-hardware.org/?probe=12a2003770) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [7f190e4ed2](https://linux-hardware.org/?probe=7f190e4ed2) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2db5cafda3](https://linux-hardware.org/?probe=2db5cafda3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [abcab36e0c](https://linux-hardware.org/?probe=abcab36e0c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f3ccb91568](https://linux-hardware.org/?probe=f3ccb91568) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [0d8fa16f47](https://linux-hardware.org/?probe=0d8fa16f47) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [680e8106ec](https://linux-hardware.org/?probe=680e8106ec) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c18b0215e9](https://linux-hardware.org/?probe=c18b0215e9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fcc821b941](https://linux-hardware.org/?probe=fcc821b941) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [59f760dbb9](https://linux-hardware.org/?probe=59f760dbb9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e22a8e2ea4](https://linux-hardware.org/?probe=e22a8e2ea4) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4fc69342da](https://linux-hardware.org/?probe=4fc69342da) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f2fcae5696](https://linux-hardware.org/?probe=f2fcae5696) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2f823b2f52](https://linux-hardware.org/?probe=2f823b2f52) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [adf5b71331](https://linux-hardware.org/?probe=adf5b71331) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [618c1c7838](https://linux-hardware.org/?probe=618c1c7838) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [0dff1056d5](https://linux-hardware.org/?probe=0dff1056d5) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fb0cf0a7a3](https://linux-hardware.org/?probe=fb0cf0a7a3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6b9f550210](https://linux-hardware.org/?probe=6b9f550210) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4b22440e91](https://linux-hardware.org/?probe=4b22440e91) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6bab7cdc7c](https://linux-hardware.org/?probe=6bab7cdc7c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [d2a08022bd](https://linux-hardware.org/?probe=d2a08022bd) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f39d94cf1b](https://linux-hardware.org/?probe=f39d94cf1b) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e35bbfda2d](https://linux-hardware.org/?probe=e35bbfda2d) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [60170675ca](https://linux-hardware.org/?probe=60170675ca) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [64a6aa27db](https://linux-hardware.org/?probe=64a6aa27db) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [06b1dab7a0](https://linux-hardware.org/?probe=06b1dab7a0) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [cec5c36945](https://linux-hardware.org/?probe=cec5c36945) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6f38e35f9a](https://linux-hardware.org/?probe=6f38e35f9a) | Aug 23, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [06234ebe05](https://linux-hardware.org/?probe=06234ebe05) | Aug 23, 2021 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [3c03ce796f](https://linux-hardware.org/?probe=3c03ce796f) | Aug 23, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [73b14ecca0](https://linux-hardware.org/?probe=73b14ecca0) | Aug 23, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [4a647bfabc](https://linux-hardware.org/?probe=4a647bfabc) | Aug 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [e70b15e489](https://linux-hardware.org/?probe=e70b15e489) | Aug 22, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [ebe40b3244](https://linux-hardware.org/?probe=ebe40b3244) | Aug 22, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d98bdb0d1c](https://linux-hardware.org/?probe=d98bdb0d1c) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [d688bffa01](https://linux-hardware.org/?probe=d688bffa01) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [3d52884b6e](https://linux-hardware.org/?probe=3d52884b6e) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | Notebook    | [57b847b12c](https://linux-hardware.org/?probe=57b847b12c) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | Notebook    | [db4b9878fa](https://linux-hardware.org/?probe=db4b9878fa) | Aug 22, 2021 |
| Dell          | Inspiron 6000               | Notebook    | [67c6b36361](https://linux-hardware.org/?probe=67c6b36361) | Aug 22, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [eea45758b7](https://linux-hardware.org/?probe=eea45758b7) | Aug 22, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [dfed5d8b7a](https://linux-hardware.org/?probe=dfed5d8b7a) | Aug 21, 2021 |
| HP            | 085Ch                       | Desktop     | [2e649d07a0](https://linux-hardware.org/?probe=2e649d07a0) | Aug 21, 2021 |
| Dell          | Latitude E7470              | Notebook    | [e954672cb2](https://linux-hardware.org/?probe=e954672cb2) | Aug 21, 2021 |
| HP            | 085Ch                       | Desktop     | [c5b36c5187](https://linux-hardware.org/?probe=c5b36c5187) | Aug 21, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [4d43bca615](https://linux-hardware.org/?probe=4d43bca615) | Aug 21, 2021 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [0f9abf9c63](https://linux-hardware.org/?probe=0f9abf9c63) | Aug 21, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [7f83e1b3c8](https://linux-hardware.org/?probe=7f83e1b3c8) | Aug 21, 2021 |
| HP            | 14s-dq2003nw                | Notebook    | [f4dcd70da5](https://linux-hardware.org/?probe=f4dcd70da5) | Aug 21, 2021 |
| Lenovo        | ThinkPad E570 20H500B4GE    | Notebook    | [be964b556b](https://linux-hardware.org/?probe=be964b556b) | Aug 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [5ecdc39ac1](https://linux-hardware.org/?probe=5ecdc39ac1) | Aug 21, 2021 |
| ASUSTek       | P5B SE                      | Desktop     | [81634fcb22](https://linux-hardware.org/?probe=81634fcb22) | Aug 21, 2021 |
| Dell          | Precision 7520              | Notebook    | [372d627a69](https://linux-hardware.org/?probe=372d627a69) | Aug 21, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [e59c9482f6](https://linux-hardware.org/?probe=e59c9482f6) | Aug 21, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [daa01f79aa](https://linux-hardware.org/?probe=daa01f79aa) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [a96a7ada4f](https://linux-hardware.org/?probe=a96a7ada4f) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c8305c0d4c](https://linux-hardware.org/?probe=c8305c0d4c) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [77359352d0](https://linux-hardware.org/?probe=77359352d0) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5312257240](https://linux-hardware.org/?probe=5312257240) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [75e262ddba](https://linux-hardware.org/?probe=75e262ddba) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [bd216572a3](https://linux-hardware.org/?probe=bd216572a3) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e57aeadfef](https://linux-hardware.org/?probe=e57aeadfef) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [7211565d4a](https://linux-hardware.org/?probe=7211565d4a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [1c490522df](https://linux-hardware.org/?probe=1c490522df) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [16f0b9c14a](https://linux-hardware.org/?probe=16f0b9c14a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [691bb379e5](https://linux-hardware.org/?probe=691bb379e5) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fe880ac0c8](https://linux-hardware.org/?probe=fe880ac0c8) | Aug 20, 2021 |
| Supermicro    | X10SLM-F                    | Server      | [801ee74858](https://linux-hardware.org/?probe=801ee74858) | Aug 20, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [a5a146e42a](https://linux-hardware.org/?probe=a5a146e42a) | Aug 20, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [580838bf3c](https://linux-hardware.org/?probe=580838bf3c) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [cba7d82942](https://linux-hardware.org/?probe=cba7d82942) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [62068f391f](https://linux-hardware.org/?probe=62068f391f) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c60ef3fa1e](https://linux-hardware.org/?probe=c60ef3fa1e) | Aug 20, 2021 |
| Supermicro    | X10DRW-iT                   | Server      | [aaeee85be7](https://linux-hardware.org/?probe=aaeee85be7) | Aug 20, 2021 |
| Timi          | TM1612                      | Notebook    | [485caf5846](https://linux-hardware.org/?probe=485caf5846) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [c980f2d201](https://linux-hardware.org/?probe=c980f2d201) | Aug 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [2a61705899](https://linux-hardware.org/?probe=2a61705899) | Aug 20, 2021 |
| Dell          | 0Y2K8N A01                  | Desktop     | [6b0fd02c91](https://linux-hardware.org/?probe=6b0fd02c91) | Aug 20, 2021 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [17c70c7886](https://linux-hardware.org/?probe=17c70c7886) | Aug 19, 2021 |
| SLIMBOOK      | TITAN                       | Notebook    | [a2abd981d1](https://linux-hardware.org/?probe=a2abd981d1) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1ce6738560](https://linux-hardware.org/?probe=1ce6738560) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [e134a1f7c3](https://linux-hardware.org/?probe=e134a1f7c3) | Aug 19, 2021 |
| HP            | 339A                        | Desktop     | [57d5bbd1e4](https://linux-hardware.org/?probe=57d5bbd1e4) | Aug 19, 2021 |
| RuggedPC      | Caterpillar T20             | Tablet      | [1bf2275be4](https://linux-hardware.org/?probe=1bf2275be4) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [87fa430aab](https://linux-hardware.org/?probe=87fa430aab) | Aug 19, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2151b5cdae](https://linux-hardware.org/?probe=2151b5cdae) | Aug 19, 2021 |
| HP            | 1587h                       | Desktop     | [3ddbdb3101](https://linux-hardware.org/?probe=3ddbdb3101) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [0489699bc4](https://linux-hardware.org/?probe=0489699bc4) | Aug 19, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [cc54b8955c](https://linux-hardware.org/?probe=cc54b8955c) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [757e261c56](https://linux-hardware.org/?probe=757e261c56) | Aug 19, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [df15656fce](https://linux-hardware.org/?probe=df15656fce) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c989eac16b](https://linux-hardware.org/?probe=c989eac16b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [3169e477dd](https://linux-hardware.org/?probe=3169e477dd) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5fcb7fdb26](https://linux-hardware.org/?probe=5fcb7fdb26) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [7afbba35b0](https://linux-hardware.org/?probe=7afbba35b0) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [f1d159bbd1](https://linux-hardware.org/?probe=f1d159bbd1) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [38e8211556](https://linux-hardware.org/?probe=38e8211556) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [bd587e5998](https://linux-hardware.org/?probe=bd587e5998) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [3fa54711ec](https://linux-hardware.org/?probe=3fa54711ec) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [4a7f287161](https://linux-hardware.org/?probe=4a7f287161) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6f5485edfc](https://linux-hardware.org/?probe=6f5485edfc) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [fed5f28778](https://linux-hardware.org/?probe=fed5f28778) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [0ba8599928](https://linux-hardware.org/?probe=0ba8599928) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [e31d43b39d](https://linux-hardware.org/?probe=e31d43b39d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [703cdcf766](https://linux-hardware.org/?probe=703cdcf766) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [9b8ce55c3d](https://linux-hardware.org/?probe=9b8ce55c3d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2b4af51f46](https://linux-hardware.org/?probe=2b4af51f46) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b802b4a25b](https://linux-hardware.org/?probe=b802b4a25b) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [cb421b796b](https://linux-hardware.org/?probe=cb421b796b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [f6c7230675](https://linux-hardware.org/?probe=f6c7230675) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [7116839a4b](https://linux-hardware.org/?probe=7116839a4b) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [04817bfb7f](https://linux-hardware.org/?probe=04817bfb7f) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [1fce0ab0e8](https://linux-hardware.org/?probe=1fce0ab0e8) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [92b401a705](https://linux-hardware.org/?probe=92b401a705) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [f2a438a9be](https://linux-hardware.org/?probe=f2a438a9be) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c9239b499b](https://linux-hardware.org/?probe=c9239b499b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [b708a97ef1](https://linux-hardware.org/?probe=b708a97ef1) | Aug 18, 2021 |
| Lenovo        | Board                       | Desktop     | [3de8569fe7](https://linux-hardware.org/?probe=3de8569fe7) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [31dc792a8b](https://linux-hardware.org/?probe=31dc792a8b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [76a48b344d](https://linux-hardware.org/?probe=76a48b344d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [244aba47d4](https://linux-hardware.org/?probe=244aba47d4) | Aug 18, 2021 |
| ASUSTek       | H81M-R                      | Desktop     | [8598ad2248](https://linux-hardware.org/?probe=8598ad2248) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [b2391216c6](https://linux-hardware.org/?probe=b2391216c6) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [53b311c24c](https://linux-hardware.org/?probe=53b311c24c) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [61de56951c](https://linux-hardware.org/?probe=61de56951c) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [7fd7f1ea77](https://linux-hardware.org/?probe=7fd7f1ea77) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [2a090f8b2a](https://linux-hardware.org/?probe=2a090f8b2a) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [62e4ff915a](https://linux-hardware.org/?probe=62e4ff915a) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [eada085a33](https://linux-hardware.org/?probe=eada085a33) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [474e20b9f2](https://linux-hardware.org/?probe=474e20b9f2) | Aug 18, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [61b641914c](https://linux-hardware.org/?probe=61b641914c) | Aug 18, 2021 |
| ASUSTek       | B150M-K                     | Desktop     | [3f706a2a69](https://linux-hardware.org/?probe=3f706a2a69) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [9f3381d34c](https://linux-hardware.org/?probe=9f3381d34c) | Aug 18, 2021 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [85cfabd795](https://linux-hardware.org/?probe=85cfabd795) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [765f5d340e](https://linux-hardware.org/?probe=765f5d340e) | Aug 18, 2021 |
| ASRock        | J4205-ITX                   | Desktop     | [30de75d2c8](https://linux-hardware.org/?probe=30de75d2c8) | Aug 18, 2021 |
| ASUSTek       | UX305CA                     | Notebook    | [6ab6beca67](https://linux-hardware.org/?probe=6ab6beca67) | Aug 18, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [c7155dfa07](https://linux-hardware.org/?probe=c7155dfa07) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [451fe761a6](https://linux-hardware.org/?probe=451fe761a6) | Aug 18, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [b2ed4bc6fe](https://linux-hardware.org/?probe=b2ed4bc6fe) | Aug 18, 2021 |
| Google        | Enguarde                    | Notebook    | [dd0de8b832](https://linux-hardware.org/?probe=dd0de8b832) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [a6ac2782a6](https://linux-hardware.org/?probe=a6ac2782a6) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [d32e974941](https://linux-hardware.org/?probe=d32e974941) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [fe90c1da98](https://linux-hardware.org/?probe=fe90c1da98) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c3d98780bf](https://linux-hardware.org/?probe=c3d98780bf) | Aug 17, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [4b38b9e598](https://linux-hardware.org/?probe=4b38b9e598) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2c30321150](https://linux-hardware.org/?probe=2c30321150) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2f6317ebc5](https://linux-hardware.org/?probe=2f6317ebc5) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [707606ff5e](https://linux-hardware.org/?probe=707606ff5e) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [0c43bb89c0](https://linux-hardware.org/?probe=0c43bb89c0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [fcb540b848](https://linux-hardware.org/?probe=fcb540b848) | Aug 17, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [46240d5ef9](https://linux-hardware.org/?probe=46240d5ef9) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6e85db6058](https://linux-hardware.org/?probe=6e85db6058) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2e26440865](https://linux-hardware.org/?probe=2e26440865) | Aug 17, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [5ad65197ad](https://linux-hardware.org/?probe=5ad65197ad) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c185e120f1](https://linux-hardware.org/?probe=c185e120f1) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [ee22c0dcc0](https://linux-hardware.org/?probe=ee22c0dcc0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [b3fd5bee39](https://linux-hardware.org/?probe=b3fd5bee39) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [d68e571cd0](https://linux-hardware.org/?probe=d68e571cd0) | Aug 17, 2021 |
| Dell          | Latitude 7480               | Notebook    | [49272ed382](https://linux-hardware.org/?probe=49272ed382) | Aug 17, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [be9383850e](https://linux-hardware.org/?probe=be9383850e) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [28c2f85e9c](https://linux-hardware.org/?probe=28c2f85e9c) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [1f8c3f9487](https://linux-hardware.org/?probe=1f8c3f9487) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [9f6a737d07](https://linux-hardware.org/?probe=9f6a737d07) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4eb4afec6b](https://linux-hardware.org/?probe=4eb4afec6b) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [5949002919](https://linux-hardware.org/?probe=5949002919) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [b0d4ba09f6](https://linux-hardware.org/?probe=b0d4ba09f6) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [12377bdf65](https://linux-hardware.org/?probe=12377bdf65) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f345284082](https://linux-hardware.org/?probe=f345284082) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6229638b59](https://linux-hardware.org/?probe=6229638b59) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [b95e1787ff](https://linux-hardware.org/?probe=b95e1787ff) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [f1d344625b](https://linux-hardware.org/?probe=f1d344625b) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [4d7eaa38ba](https://linux-hardware.org/?probe=4d7eaa38ba) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [8be28c3080](https://linux-hardware.org/?probe=8be28c3080) | Aug 17, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [d8f20bc651](https://linux-hardware.org/?probe=d8f20bc651) | Aug 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | Desktop     | [7911fbd6a6](https://linux-hardware.org/?probe=7911fbd6a6) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [cfdf77fbd9](https://linux-hardware.org/?probe=cfdf77fbd9) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [6e84dfb541](https://linux-hardware.org/?probe=6e84dfb541) | Aug 17, 2021 |
| Google        | Enguarde                    | Notebook    | [2549683d9f](https://linux-hardware.org/?probe=2549683d9f) | Aug 17, 2021 |
| Dell          | Latitude 7410               | Notebook    | [f7f6e5a4d5](https://linux-hardware.org/?probe=f7f6e5a4d5) | Aug 17, 2021 |
| ASUSTek       | 1225B                       | Notebook    | [1dd6877b22](https://linux-hardware.org/?probe=1dd6877b22) | Aug 17, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [6972c43e80](https://linux-hardware.org/?probe=6972c43e80) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Google        | Enguarde                    | Notebook    | [0bdebdb178](https://linux-hardware.org/?probe=0bdebdb178) | Aug 16, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [86cf4755a0](https://linux-hardware.org/?probe=86cf4755a0) | Aug 16, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [3a489f9498](https://linux-hardware.org/?probe=3a489f9498) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [635d3ab3e5](https://linux-hardware.org/?probe=635d3ab3e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2e04ae93d1](https://linux-hardware.org/?probe=2e04ae93d1) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [dffcb4d4f6](https://linux-hardware.org/?probe=dffcb4d4f6) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e3816a3d3a](https://linux-hardware.org/?probe=e3816a3d3a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [d76cf98938](https://linux-hardware.org/?probe=d76cf98938) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [fc7b752ce3](https://linux-hardware.org/?probe=fc7b752ce3) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [346d3ca919](https://linux-hardware.org/?probe=346d3ca919) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [eb7cdde4b5](https://linux-hardware.org/?probe=eb7cdde4b5) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [ae1b239645](https://linux-hardware.org/?probe=ae1b239645) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [d7e9112089](https://linux-hardware.org/?probe=d7e9112089) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [35ab4c3075](https://linux-hardware.org/?probe=35ab4c3075) | Aug 16, 2021 |
| Lenovo        | ThinkPad E490 20N8001EUS    | Notebook    | [40796d62c2](https://linux-hardware.org/?probe=40796d62c2) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1fa30fb77a](https://linux-hardware.org/?probe=1fa30fb77a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [81f2a65461](https://linux-hardware.org/?probe=81f2a65461) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [a54d2e496c](https://linux-hardware.org/?probe=a54d2e496c) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [d0581c16e9](https://linux-hardware.org/?probe=d0581c16e9) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [4704dd7dc2](https://linux-hardware.org/?probe=4704dd7dc2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [2d48e28c72](https://linux-hardware.org/?probe=2d48e28c72) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [dcded26792](https://linux-hardware.org/?probe=dcded26792) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [de06f0cb03](https://linux-hardware.org/?probe=de06f0cb03) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [3171a06ab2](https://linux-hardware.org/?probe=3171a06ab2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [154d3f4aac](https://linux-hardware.org/?probe=154d3f4aac) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 20J10046US      | Notebook    | [6943b835e5](https://linux-hardware.org/?probe=6943b835e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [56e2f75dab](https://linux-hardware.org/?probe=56e2f75dab) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [7e070c3cee](https://linux-hardware.org/?probe=7e070c3cee) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [be42bbb09a](https://linux-hardware.org/?probe=be42bbb09a) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [42a5d4fb48](https://linux-hardware.org/?probe=42a5d4fb48) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [845219864e](https://linux-hardware.org/?probe=845219864e) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99531c5564](https://linux-hardware.org/?probe=99531c5564) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [7e2e8d1364](https://linux-hardware.org/?probe=7e2e8d1364) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [c9b0773c42](https://linux-hardware.org/?probe=c9b0773c42) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [947e3524e3](https://linux-hardware.org/?probe=947e3524e3) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [a30c87c3fe](https://linux-hardware.org/?probe=a30c87c3fe) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [edaac7af9f](https://linux-hardware.org/?probe=edaac7af9f) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [94047a5fdc](https://linux-hardware.org/?probe=94047a5fdc) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [ccd9ef4a72](https://linux-hardware.org/?probe=ccd9ef4a72) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [97aab17694](https://linux-hardware.org/?probe=97aab17694) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [3112135337](https://linux-hardware.org/?probe=3112135337) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [8da303b571](https://linux-hardware.org/?probe=8da303b571) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [449ea4adf6](https://linux-hardware.org/?probe=449ea4adf6) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5bd9662328](https://linux-hardware.org/?probe=5bd9662328) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [079ef9affe](https://linux-hardware.org/?probe=079ef9affe) | Aug 16, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [3d63a976ed](https://linux-hardware.org/?probe=3d63a976ed) | Aug 16, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [c847e8acf2](https://linux-hardware.org/?probe=c847e8acf2) | Aug 16, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [ec9367ff70](https://linux-hardware.org/?probe=ec9367ff70) | Aug 16, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [ea9196699a](https://linux-hardware.org/?probe=ea9196699a) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [9e81b88eb8](https://linux-hardware.org/?probe=9e81b88eb8) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [7b614dd679](https://linux-hardware.org/?probe=7b614dd679) | Aug 16, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [2cd1a890fa](https://linux-hardware.org/?probe=2cd1a890fa) | Aug 16, 2021 |
| Dell          | G3 3590                     | Notebook    | [05e11ad38d](https://linux-hardware.org/?probe=05e11ad38d) | Aug 16, 2021 |
| HP            | 630                         | Notebook    | [a57ed15001](https://linux-hardware.org/?probe=a57ed15001) | Aug 15, 2021 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [51f9388874](https://linux-hardware.org/?probe=51f9388874) | Aug 15, 2021 |
| ASUSTek       | STRIX B250H GAMING          | Desktop     | [88160f850f](https://linux-hardware.org/?probe=88160f850f) | Aug 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [31fcb375f4](https://linux-hardware.org/?probe=31fcb375f4) | Aug 15, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [53aff8d681](https://linux-hardware.org/?probe=53aff8d681) | Aug 15, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | Notebook    | [e3fd79d228](https://linux-hardware.org/?probe=e3fd79d228) | Aug 15, 2021 |
| ECS           | KBN-I                       | Desktop     | [bbfe1ba1a2](https://linux-hardware.org/?probe=bbfe1ba1a2) | Aug 15, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [daf1b7a963](https://linux-hardware.org/?probe=daf1b7a963) | Aug 15, 2021 |
| AMI           | Intel                       | Convertible | [c96146f531](https://linux-hardware.org/?probe=c96146f531) | Aug 15, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [987ab1f3bf](https://linux-hardware.org/?probe=987ab1f3bf) | Aug 15, 2021 |
| Hardkernel    | Odroid XU4                  | Soc         | [dbc542cf3e](https://linux-hardware.org/?probe=dbc542cf3e) | Aug 15, 2021 |
| Hardkernel    | Odroid XU4                  | Soc         | [130a903db8](https://linux-hardware.org/?probe=130a903db8) | Aug 15, 2021 |
| Hardkernel    | Odroid XU4                  | Soc         | [7cfc2e8121](https://linux-hardware.org/?probe=7cfc2e8121) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [0b7f4b2da5](https://linux-hardware.org/?probe=0b7f4b2da5) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | Desktop     | [a6e0859eac](https://linux-hardware.org/?probe=a6e0859eac) | Aug 14, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [f6b6388040](https://linux-hardware.org/?probe=f6b6388040) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | Desktop     | [5ce5d800d3](https://linux-hardware.org/?probe=5ce5d800d3) | Aug 14, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [dfe51161fe](https://linux-hardware.org/?probe=dfe51161fe) | Aug 14, 2021 |
| HP            | Compaq nc6320 (EV073AV)     | Notebook    | [bf6050f750](https://linux-hardware.org/?probe=bf6050f750) | Aug 14, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [0e5746a060](https://linux-hardware.org/?probe=0e5746a060) | Aug 14, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [f3506aaa1c](https://linux-hardware.org/?probe=f3506aaa1c) | Aug 14, 2021 |
| Dell          | 0X9M3X A01                  | Desktop     | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| Dell          | Latitude 7490               | Notebook    | [6ca174eba8](https://linux-hardware.org/?probe=6ca174eba8) | Aug 14, 2021 |
| HP            | 3397                        | Desktop     | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| Dell          | Latitude 7490               | Notebook    | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [cac72ff077](https://linux-hardware.org/?probe=cac72ff077) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [8c489e2c59](https://linux-hardware.org/?probe=8c489e2c59) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [d79905590c](https://linux-hardware.org/?probe=d79905590c) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [7efce8d06b](https://linux-hardware.org/?probe=7efce8d06b) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [c53a0803e7](https://linux-hardware.org/?probe=c53a0803e7) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [410a4b2e26](https://linux-hardware.org/?probe=410a4b2e26) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [cbc9f75923](https://linux-hardware.org/?probe=cbc9f75923) | Aug 13, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [62faddbfaa](https://linux-hardware.org/?probe=62faddbfaa) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [4ca322af56](https://linux-hardware.org/?probe=4ca322af56) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [2af4090c36](https://linux-hardware.org/?probe=2af4090c36) | Aug 13, 2021 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [f59179a579](https://linux-hardware.org/?probe=f59179a579) | Aug 13, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [0fb5cb1e91](https://linux-hardware.org/?probe=0fb5cb1e91) | Aug 13, 2021 |
| ASUSTek       | Z170-PRO                    | Desktop     | [7f9b5606a5](https://linux-hardware.org/?probe=7f9b5606a5) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [43919a91f3](https://linux-hardware.org/?probe=43919a91f3) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [c93dcd9531](https://linux-hardware.org/?probe=c93dcd9531) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [8e7147d832](https://linux-hardware.org/?probe=8e7147d832) | Aug 12, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [65a4eb9f2c](https://linux-hardware.org/?probe=65a4eb9f2c) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [e9f95dc0ed](https://linux-hardware.org/?probe=e9f95dc0ed) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [3b5b9d1698](https://linux-hardware.org/?probe=3b5b9d1698) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [e423d1eee6](https://linux-hardware.org/?probe=e423d1eee6) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [1f00600e9b](https://linux-hardware.org/?probe=1f00600e9b) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [88adc88ccd](https://linux-hardware.org/?probe=88adc88ccd) | Aug 12, 2021 |
| Notebook      | NL4x_NL5xLU                 | Notebook    | [82a8b9c657](https://linux-hardware.org/?probe=82a8b9c657) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [2434eac448](https://linux-hardware.org/?probe=2434eac448) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [d766910df0](https://linux-hardware.org/?probe=d766910df0) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [c0516ce965](https://linux-hardware.org/?probe=c0516ce965) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [728007c621](https://linux-hardware.org/?probe=728007c621) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [b808ac5856](https://linux-hardware.org/?probe=b808ac5856) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [326cc3aae3](https://linux-hardware.org/?probe=326cc3aae3) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [1fddcb2525](https://linux-hardware.org/?probe=1fddcb2525) | Aug 12, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | Notebook    | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| Dell          | G7 7790                     | Notebook    | [99dd172940](https://linux-hardware.org/?probe=99dd172940) | Aug 12, 2021 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [2bc14051d8](https://linux-hardware.org/?probe=2bc14051d8) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | Notebook    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [c0bae6c52e](https://linux-hardware.org/?probe=c0bae6c52e) | Aug 12, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [cbe8c5170f](https://linux-hardware.org/?probe=cbe8c5170f) | Aug 12, 2021 |
| HP            | ProBook 4530s               | Notebook    | [14a78c65a1](https://linux-hardware.org/?probe=14a78c65a1) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| HP            | 3048h                       | Desktop     | [894950911f](https://linux-hardware.org/?probe=894950911f) | Aug 11, 2021 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [7e6788485b](https://linux-hardware.org/?probe=7e6788485b) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [4139a3a855](https://linux-hardware.org/?probe=4139a3a855) | Aug 11, 2021 |
| Notebook      | N13_N140ZU                  | Notebook    | [cbaecf1d3e](https://linux-hardware.org/?probe=cbaecf1d3e) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [48573ed425](https://linux-hardware.org/?probe=48573ed425) | Aug 11, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9b62457757](https://linux-hardware.org/?probe=9b62457757) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f174ea79a1](https://linux-hardware.org/?probe=f174ea79a1) | Aug 11, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a5a2ea2cda](https://linux-hardware.org/?probe=a5a2ea2cda) | Aug 11, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [cabe0ebbc8](https://linux-hardware.org/?probe=cabe0ebbc8) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1dcbf85471](https://linux-hardware.org/?probe=1dcbf85471) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [0c67490330](https://linux-hardware.org/?probe=0c67490330) | Aug 10, 2021 |
| HP            | 2AF7                        | Desktop     | [649ed7df8e](https://linux-hardware.org/?probe=649ed7df8e) | Aug 10, 2021 |
| Dell          | Precision 3551              | Notebook    | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| Intel         | DQ45CB AAE30148-207         | Desktop     | [56a573eeed](https://linux-hardware.org/?probe=56a573eeed) | Aug 10, 2021 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [6f4ad31000](https://linux-hardware.org/?probe=6f4ad31000) | Aug 10, 2021 |
| ASUSTek       | STRIX B250H GAMING          | Desktop     | [78223998b6](https://linux-hardware.org/?probe=78223998b6) | Aug 10, 2021 |
| HP            | 250 G4                      | Notebook    | [5640b0689d](https://linux-hardware.org/?probe=5640b0689d) | Aug 10, 2021 |
| MSI           | B250M PRO-VDH               | Desktop     | [d6be998202](https://linux-hardware.org/?probe=d6be998202) | Aug 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [d650ff0c3e](https://linux-hardware.org/?probe=d650ff0c3e) | Aug 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4ce98656a4](https://linux-hardware.org/?probe=4ce98656a4) | Aug 10, 2021 |
| Dell          | Inspiron ME051              | Notebook    | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Lenovo        | B51-35 80LH                 | Notebook    | [5f87168a65](https://linux-hardware.org/?probe=5f87168a65) | Aug 10, 2021 |
| Dell          | 04MFRM A01                  | Desktop     | [c0094def97](https://linux-hardware.org/?probe=c0094def97) | Aug 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6ab68482c0](https://linux-hardware.org/?probe=6ab68482c0) | Aug 09, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [58b4f52cc0](https://linux-hardware.org/?probe=58b4f52cc0) | Aug 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS3R80... | Notebook    | [fbc29e2063](https://linux-hardware.org/?probe=fbc29e2063) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [e4ce236efd](https://linux-hardware.org/?probe=e4ce236efd) | Aug 09, 2021 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [7ca1257064](https://linux-hardware.org/?probe=7ca1257064) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [1c26f935e6](https://linux-hardware.org/?probe=1c26f935e6) | Aug 09, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [538a15f3cc](https://linux-hardware.org/?probe=538a15f3cc) | Aug 09, 2021 |
| HP            | 2000                        | Notebook    | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [fffaf4c700](https://linux-hardware.org/?probe=fffaf4c700) | Aug 09, 2021 |
| Lenovo        | ThinkPad T580 20L9001AUS    | Notebook    | [65e201224c](https://linux-hardware.org/?probe=65e201224c) | Aug 09, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [516f3cd4e5](https://linux-hardware.org/?probe=516f3cd4e5) | Aug 09, 2021 |
| Gigabyte      | H470M DS3H                  | Desktop     | [29de4693d8](https://linux-hardware.org/?probe=29de4693d8) | Aug 09, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [1a19648b3b](https://linux-hardware.org/?probe=1a19648b3b) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| ASRock        | 970A-G                      | Desktop     | [f1e9959894](https://linux-hardware.org/?probe=f1e9959894) | Aug 09, 2021 |
| Lenovo        | ThinkPad T410 2537E49       | Notebook    | [ea10aead92](https://linux-hardware.org/?probe=ea10aead92) | Aug 08, 2021 |
| Toshiba       | STI 910090 STIJ             | Desktop     | [389ebd7675](https://linux-hardware.org/?probe=389ebd7675) | Aug 08, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [575a84d010](https://linux-hardware.org/?probe=575a84d010) | Aug 08, 2021 |
| Clevo         | W55xEU                      | Notebook    | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| ASRock        | X370 Killer SLI             | Desktop     | [8a0885afb6](https://linux-hardware.org/?probe=8a0885afb6) | Aug 08, 2021 |
| Lenovo        | ThinkPad W500 406152G       | Notebook    | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [eac37d633f](https://linux-hardware.org/?probe=eac37d633f) | Aug 08, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [43aae04fa6](https://linux-hardware.org/?probe=43aae04fa6) | Aug 08, 2021 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b1f5babbfb](https://linux-hardware.org/?probe=b1f5babbfb) | Aug 08, 2021 |
| Lenovo        | ThinkPad X230 23252FG       | Notebook    | [1c7914d660](https://linux-hardware.org/?probe=1c7914d660) | Aug 08, 2021 |
| ASRock        | Z97 Pro4                    | Desktop     | [090d12a96f](https://linux-hardware.org/?probe=090d12a96f) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [39eb5a1578](https://linux-hardware.org/?probe=39eb5a1578) | Aug 08, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c5ef006a35](https://linux-hardware.org/?probe=c5ef006a35) | Aug 08, 2021 |
| Toshiba       | STI 005038 G31T-M7          | Desktop     | [faa8f15725](https://linux-hardware.org/?probe=faa8f15725) | Aug 08, 2021 |
| Acer          | Swift SF314-51              | Notebook    | [88fa728376](https://linux-hardware.org/?probe=88fa728376) | Aug 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e18202a558](https://linux-hardware.org/?probe=e18202a558) | Aug 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [a89cdf06f5](https://linux-hardware.org/?probe=a89cdf06f5) | Aug 07, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| Clevo         | P170EM                      | Notebook    | [f101b2b318](https://linux-hardware.org/?probe=f101b2b318) | Aug 07, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [3caca4f238](https://linux-hardware.org/?probe=3caca4f238) | Aug 07, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [1dbaeef7d2](https://linux-hardware.org/?probe=1dbaeef7d2) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| Google        | Parrot                      | Notebook    | [2efb04c61c](https://linux-hardware.org/?probe=2efb04c61c) | Aug 07, 2021 |
| Lenovo        | ThinkPad T61 7661BK7        | Notebook    | [bbabc03a27](https://linux-hardware.org/?probe=bbabc03a27) | Aug 07, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [da833ac33e](https://linux-hardware.org/?probe=da833ac33e) | Aug 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [80c7711147](https://linux-hardware.org/?probe=80c7711147) | Aug 07, 2021 |
| Sony          | VPCF21AFX                   | Notebook    | [40aa5144f7](https://linux-hardware.org/?probe=40aa5144f7) | Aug 07, 2021 |
| Lenovo        | ThinkPad T450 20BUS16700    | Notebook    | [8123256638](https://linux-hardware.org/?probe=8123256638) | Aug 07, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [e82d4c3561](https://linux-hardware.org/?probe=e82d4c3561) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [4ff5966d22](https://linux-hardware.org/?probe=4ff5966d22) | Aug 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5839492cd8](https://linux-hardware.org/?probe=5839492cd8) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [412f800d01](https://linux-hardware.org/?probe=412f800d01) | Aug 07, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [733a3e325c](https://linux-hardware.org/?probe=733a3e325c) | Aug 07, 2021 |
| Dell          | 08WKV3 A01                  | Desktop     | [8ab0ff9442](https://linux-hardware.org/?probe=8ab0ff9442) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | Notebook    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [69696c0e3a](https://linux-hardware.org/?probe=69696c0e3a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | Notebook    | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| MSI           | MEG X399 CREATION           | Desktop     | [7cada9aaed](https://linux-hardware.org/?probe=7cada9aaed) | Aug 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | Notebook    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | Notebook    | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| HP            | 630                         | Notebook    | [b2d03b8717](https://linux-hardware.org/?probe=b2d03b8717) | Aug 07, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [368abe4066](https://linux-hardware.org/?probe=368abe4066) | Aug 07, 2021 |
| MSI           | B250M PRO-VDH               | Desktop     | [187e4dd872](https://linux-hardware.org/?probe=187e4dd872) | Aug 07, 2021 |
| HP            | 630                         | Notebook    | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SNZ... | Notebook    | [669874ee19](https://linux-hardware.org/?probe=669874ee19) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [ad24cf2899](https://linux-hardware.org/?probe=ad24cf2899) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [9f994fc086](https://linux-hardware.org/?probe=9f994fc086) | Aug 07, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e2b8c558f7](https://linux-hardware.org/?probe=e2b8c558f7) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [8cc604abc2](https://linux-hardware.org/?probe=8cc604abc2) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c9c4b53460](https://linux-hardware.org/?probe=c9c4b53460) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [f54c45ab89](https://linux-hardware.org/?probe=f54c45ab89) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [81fef8f548](https://linux-hardware.org/?probe=81fef8f548) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [4e000b3710](https://linux-hardware.org/?probe=4e000b3710) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [493e2762bc](https://linux-hardware.org/?probe=493e2762bc) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2eb3a16b53](https://linux-hardware.org/?probe=2eb3a16b53) | Aug 06, 2021 |
| Dell          | Precision 3540              | Notebook    | [1b8206cd29](https://linux-hardware.org/?probe=1b8206cd29) | Aug 06, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [10811e8109](https://linux-hardware.org/?probe=10811e8109) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [bba0c0a13c](https://linux-hardware.org/?probe=bba0c0a13c) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [25f1a5ecdf](https://linux-hardware.org/?probe=25f1a5ecdf) | Aug 06, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [a7114078e2](https://linux-hardware.org/?probe=a7114078e2) | Aug 06, 2021 |
| Lenovo        | ThinkPad W520 4284CY1       | Notebook    | [5e1c9e9e30](https://linux-hardware.org/?probe=5e1c9e9e30) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [639bb0ca17](https://linux-hardware.org/?probe=639bb0ca17) | Aug 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [5a268dbc14](https://linux-hardware.org/?probe=5a268dbc14) | Aug 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [6aae1a533f](https://linux-hardware.org/?probe=6aae1a533f) | Aug 06, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [545f7195ab](https://linux-hardware.org/?probe=545f7195ab) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [41d352c625](https://linux-hardware.org/?probe=41d352c625) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [3256d646b0](https://linux-hardware.org/?probe=3256d646b0) | Aug 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [9ec5eaeaf9](https://linux-hardware.org/?probe=9ec5eaeaf9) | Aug 06, 2021 |
| HP            | 2AF7                        | Desktop     | [1737071720](https://linux-hardware.org/?probe=1737071720) | Aug 06, 2021 |
| HP            | 2AF7                        | Desktop     | [c504247f44](https://linux-hardware.org/?probe=c504247f44) | Aug 06, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [31d159af99](https://linux-hardware.org/?probe=31d159af99) | Aug 06, 2021 |
| Dell          | Latitude E7240              | Notebook    | [4dd840f3dd](https://linux-hardware.org/?probe=4dd840f3dd) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [64b6992b74](https://linux-hardware.org/?probe=64b6992b74) | Aug 06, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [249a58dd07](https://linux-hardware.org/?probe=249a58dd07) | Aug 05, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [fa1f3da353](https://linux-hardware.org/?probe=fa1f3da353) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [812e20e37e](https://linux-hardware.org/?probe=812e20e37e) | Aug 05, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [b90c18f9a0](https://linux-hardware.org/?probe=b90c18f9a0) | Aug 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| Lenovo        | Board                       | Desktop     | [18138486db](https://linux-hardware.org/?probe=18138486db) | Aug 05, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [7caf949908](https://linux-hardware.org/?probe=7caf949908) | Aug 05, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [103dba0476](https://linux-hardware.org/?probe=103dba0476) | Aug 05, 2021 |
| HP            | ProBook 6450b               | Notebook    | [ec02a5333b](https://linux-hardware.org/?probe=ec02a5333b) | Aug 05, 2021 |
| HP            | 3085B                       | Notebook    | [6be769f55c](https://linux-hardware.org/?probe=6be769f55c) | Aug 05, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [0a79f49420](https://linux-hardware.org/?probe=0a79f49420) | Aug 05, 2021 |
| HP            | Pavilion dm4                | Notebook    | [7ba854b03e](https://linux-hardware.org/?probe=7ba854b03e) | Aug 05, 2021 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [f71032cd7f](https://linux-hardware.org/?probe=f71032cd7f) | Aug 05, 2021 |
| Unknown       | Intel X79                   | Desktop     | [fc0dedbb3c](https://linux-hardware.org/?probe=fc0dedbb3c) | Aug 05, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [10e9ef3d45](https://linux-hardware.org/?probe=10e9ef3d45) | Aug 05, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [4882999fd5](https://linux-hardware.org/?probe=4882999fd5) | Aug 04, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [a0e7632e28](https://linux-hardware.org/?probe=a0e7632e28) | Aug 04, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [803a6be591](https://linux-hardware.org/?probe=803a6be591) | Aug 04, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [8a70054744](https://linux-hardware.org/?probe=8a70054744) | Aug 04, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [cca5aa2900](https://linux-hardware.org/?probe=cca5aa2900) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2c8c33becf](https://linux-hardware.org/?probe=2c8c33becf) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [97f8f86784](https://linux-hardware.org/?probe=97f8f86784) | Aug 04, 2021 |
| Notebook      | NJ50_70CU                   | Notebook    | [a9b3790d07](https://linux-hardware.org/?probe=a9b3790d07) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2d764714a4](https://linux-hardware.org/?probe=2d764714a4) | Aug 04, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [a3914442ca](https://linux-hardware.org/?probe=a3914442ca) | Aug 04, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [b2a62f65d6](https://linux-hardware.org/?probe=b2a62f65d6) | Aug 04, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [09a6257403](https://linux-hardware.org/?probe=09a6257403) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [eafaf5ece3](https://linux-hardware.org/?probe=eafaf5ece3) | Aug 04, 2021 |
| ASUSTek       | N53Ta                       | Notebook    | [896a02b57b](https://linux-hardware.org/?probe=896a02b57b) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c0bf2b7b10](https://linux-hardware.org/?probe=c0bf2b7b10) | Aug 03, 2021 |
| HP            | 3047h                       | Desktop     | [6294617672](https://linux-hardware.org/?probe=6294617672) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [3d29b58c58](https://linux-hardware.org/?probe=3d29b58c58) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [8b35a81ed6](https://linux-hardware.org/?probe=8b35a81ed6) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [87bca8ecbc](https://linux-hardware.org/?probe=87bca8ecbc) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [fbbd748072](https://linux-hardware.org/?probe=fbbd748072) | Aug 03, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [a7bdbd8ebe](https://linux-hardware.org/?probe=a7bdbd8ebe) | Aug 03, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [71738ebf7e](https://linux-hardware.org/?probe=71738ebf7e) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [06d86172a1](https://linux-hardware.org/?probe=06d86172a1) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [aa415746d6](https://linux-hardware.org/?probe=aa415746d6) | Aug 03, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c8674581d0](https://linux-hardware.org/?probe=c8674581d0) | Aug 03, 2021 |
| Dell          | Latitude E4310              | Notebook    | [75a9aa20f2](https://linux-hardware.org/?probe=75a9aa20f2) | Aug 03, 2021 |
| Google        | Enguarde                    | Notebook    | [c758164470](https://linux-hardware.org/?probe=c758164470) | Aug 03, 2021 |
| Lenovo        | ThinkPad R61e 7650DHU       | Notebook    | [82f2f3a1a7](https://linux-hardware.org/?probe=82f2f3a1a7) | Aug 03, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [1f83d95a2a](https://linux-hardware.org/?probe=1f83d95a2a) | Aug 03, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | Notebook    | [c14dd630ed](https://linux-hardware.org/?probe=c14dd630ed) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99ccdd5455](https://linux-hardware.org/?probe=99ccdd5455) | Aug 02, 2021 |
| Supermicro    | X11SSH-F                    | Desktop     | [641e4fd8ce](https://linux-hardware.org/?probe=641e4fd8ce) | Aug 02, 2021 |
| Lenovo        | Reno                        | Server      | [91a367ab6d](https://linux-hardware.org/?probe=91a367ab6d) | Aug 02, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [aa5aaf6fd0](https://linux-hardware.org/?probe=aa5aaf6fd0) | Aug 02, 2021 |
| SimpliVity    | 04N3DF A03                  | Server      | [c5705e6436](https://linux-hardware.org/?probe=c5705e6436) | Aug 02, 2021 |
| Google        | Stout                       | Notebook    | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | Notebook    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | Desktop     | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | Notebook    | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| ASUSTek       | A88X-PRO                    | Desktop     | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP            | 2187 A01                    | Desktop     | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [8f40021fde](https://linux-hardware.org/?probe=8f40021fde) | Aug 01, 2021 |
| ASRock        | J1900D2Y                    | Desktop     | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | Notebook    | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell          | 0WVYMC A00                  | Desktop     | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | Notebook    | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | Notebook    | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | Notebook    | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [acff56e8e3](https://linux-hardware.org/?probe=acff56e8e3) | Jul 29, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [704ead0e75](https://linux-hardware.org/?probe=704ead0e75) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| Dell          | 0TY915                      | Desktop     | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek       | LEONITE                     | Desktop     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn       | 2AA9                        | Desktop     | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| ASRock        | B85M Pro4                   | Desktop     | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | Notebook    | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | Notebook    | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | Notebook    | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [21c6bb9dde](https://linux-hardware.org/?probe=21c6bb9dde) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [cc099348c2](https://linux-hardware.org/?probe=cc099348c2) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | Notebook    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | Notebook    | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | Notebook    | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | Notebook    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Shuttle       | FX79R                       | Desktop     | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | Notebook    | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| Casper        | C17B                        | Notebook    | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | Notebook    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [72032bc046](https://linux-hardware.org/?probe=72032bc046) | Jul 27, 2021 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | Desktop     | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | Notebook    | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | Notebook    | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | Notebook    | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | Notebook    | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [52e5d3e16d](https://linux-hardware.org/?probe=52e5d3e16d) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | Desktop     | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [e7aeecff98](https://linux-hardware.org/?probe=e7aeecff98) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | Notebook    | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | Notebook    | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Dell          | Studio 1555                 | Notebook    | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | Notebook    | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | Notebook    | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | Notebook    | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | Notebook    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | Notebook    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1e2b68b7d8](https://linux-hardware.org/?probe=1e2b68b7d8) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | Notebook    | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | Desktop     | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | Desktop     | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | Desktop     | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| IBM           | I/O Port                    | Server      | [8538814cd6](https://linux-hardware.org/?probe=8538814cd6) | Jul 25, 2021 |
| Dell          | 0Y1057                      | Desktop     | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | Notebook    | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | Desktop     | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | Notebook    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | Notebook    | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | Notebook    | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | Notebook    | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | Desktop     | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [f8ad21d44a](https://linux-hardware.org/?probe=f8ad21d44a) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | Notebook    | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | Desktop     | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| Lenovo        | 3110 SDK0J40697 WIN 3305... | All in one  | [84b6274afe](https://linux-hardware.org/?probe=84b6274afe) | Jul 25, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e1db015807](https://linux-hardware.org/?probe=e1db015807) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | Notebook    | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | Notebook    | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | Notebook    | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | Notebook    | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| CompuLab      | fitlet2                     | Mini pc     | [9d1571afa4](https://linux-hardware.org/?probe=9d1571afa4) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | Desktop     | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | Desktop     | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | Notebook    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | Notebook    | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Protectli     | FW6                         | Desktop     | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Lenovo        | Yoga 710-11ISK 80TX         | Convertible | [c34bcc095c](https://linux-hardware.org/?probe=c34bcc095c) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | Desktop     | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | Desktop     | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [0c49a20e7c](https://linux-hardware.org/?probe=0c49a20e7c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | Desktop     | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | Notebook    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | Notebook    | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [d3a887bf62](https://linux-hardware.org/?probe=d3a887bf62) | Jul 22, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [c3aac7e847](https://linux-hardware.org/?probe=c3aac7e847) | Jul 22, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [eeb04ca8d9](https://linux-hardware.org/?probe=eeb04ca8d9) | Jul 22, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [650e0a4954](https://linux-hardware.org/?probe=650e0a4954) | Jul 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| Supermicro    | X11DDW-L                    | Server      | [6fab4e3135](https://linux-hardware.org/?probe=6fab4e3135) | Jul 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| Dell          | 0H5J4J A01                  | Server      | [fbdf83f7ff](https://linux-hardware.org/?probe=fbdf83f7ff) | Jul 17, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | Notebook    | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [be4679a65b](https://linux-hardware.org/?probe=be4679a65b) | Jul 14, 2021 |
| Intel         | W7645                       | Notebook    | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8691cb3cb9](https://linux-hardware.org/?probe=8691cb3cb9) | Jul 12, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [d7722f9bbf](https://linux-hardware.org/?probe=d7722f9bbf) | Jul 12, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3eceba473e](https://linux-hardware.org/?probe=3eceba473e) | Jul 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [85da1219ad](https://linux-hardware.org/?probe=85da1219ad) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [145ca872cf](https://linux-hardware.org/?probe=145ca872cf) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [5ab6c73674](https://linux-hardware.org/?probe=5ab6c73674) | Jul 08, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [bccfe7e145](https://linux-hardware.org/?probe=bccfe7e145) | Jul 08, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [73a418aad6](https://linux-hardware.org/?probe=73a418aad6) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| Acer          | Aspire E5-573               | Notebook    | [d946214a58](https://linux-hardware.org/?probe=d946214a58) | Jul 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c80bd2ff96](https://linux-hardware.org/?probe=c80bd2ff96) | Jul 05, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e8da9b3b84](https://linux-hardware.org/?probe=e8da9b3b84) | Jul 05, 2021 |
| HP            | Compaq 6830s                | Notebook    | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| MSI           | MS-6712                     | Desktop     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| HP            | Compaq 6830s                | Notebook    | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [457f309f39](https://linux-hardware.org/?probe=457f309f39) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [945a4600c4](https://linux-hardware.org/?probe=945a4600c4) | Jul 02, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [4ff716ad3a](https://linux-hardware.org/?probe=4ff716ad3a) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| ASUSTek       | K42Jv                       | Notebook    | [88ee690bb2](https://linux-hardware.org/?probe=88ee690bb2) | Jun 30, 2021 |
| Sony          | SVE1512G1RB                 | Notebook    | [41dd93f0c7](https://linux-hardware.org/?probe=41dd93f0c7) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | Notebook    | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [51edb744b9](https://linux-hardware.org/?probe=51edb744b9) | Jun 29, 2021 |
| MSI           | B85M-G43                    | Desktop     | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2) (... | Phone       | [6805b89f3d](https://linux-hardware.org/?probe=6805b89f3d) | Jun 25, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [25956c35fb](https://linux-hardware.org/?probe=25956c35fb) | Jun 24, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | Desktop     | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [f952173995](https://linux-hardware.org/?probe=f952173995) | Jun 23, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| Gigabyte      | B85M-D2V                    | Desktop     | [25f911e59c](https://linux-hardware.org/?probe=25f911e59c) | Jun 23, 2021 |
| Dell          | 04WYPY A04                  | Server      | [20fa770830](https://linux-hardware.org/?probe=20fa770830) | Jun 22, 2021 |
| Gigabyte      | B360M H                     | Desktop     | [fcddb198ec](https://linux-hardware.org/?probe=fcddb198ec) | Jun 22, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Gigabyte      | B85M-D2V                    | Desktop     | [a719f039de](https://linux-hardware.org/?probe=a719f039de) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [16cf7bfb30](https://linux-hardware.org/?probe=16cf7bfb30) | Jun 21, 2021 |
| Dell          | Precision 3560              | Notebook    | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | Notebook    | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [19fb8aa218](https://linux-hardware.org/?probe=19fb8aa218) | Jun 18, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [c334d50b1f](https://linux-hardware.org/?probe=c334d50b1f) | Jun 18, 2021 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [a1f50d7038](https://linux-hardware.org/?probe=a1f50d7038) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [1dc449cb66](https://linux-hardware.org/?probe=1dc449cb66) | Jun 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [6511e56d8f](https://linux-hardware.org/?probe=6511e56d8f) | Jun 16, 2021 |
| Gigabyte      | B360M H                     | Desktop     | [44fd3744da](https://linux-hardware.org/?probe=44fd3744da) | Jun 16, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| ASUSTek       | P7H55                       | Desktop     | [c8abc22ac7](https://linux-hardware.org/?probe=c8abc22ac7) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | Desktop     | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [dc6ae81a40](https://linux-hardware.org/?probe=dc6ae81a40) | Jun 11, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [359862901e](https://linux-hardware.org/?probe=359862901e) | Jun 11, 2021 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [b081ed3973](https://linux-hardware.org/?probe=b081ed3973) | Jun 11, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [0de49e4ceb](https://linux-hardware.org/?probe=0de49e4ceb) | Jun 11, 2021 |
| Kobol         | Helios64                    | Soc         | [33c6248333](https://linux-hardware.org/?probe=33c6248333) | Jun 11, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| Dell          | Latitude E7470              | Notebook    | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | Desktop     | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| Clevo         | W250ENQ / W270ENQ           | Notebook    | [95fe5984c2](https://linux-hardware.org/?probe=95fe5984c2) | Jun 09, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [50a33d0c01](https://linux-hardware.org/?probe=50a33d0c01) | Jun 09, 2021 |
| Clevo         | W250ENQ / W270ENQ           | Notebook    | [b992eee8b5](https://linux-hardware.org/?probe=b992eee8b5) | Jun 09, 2021 |
| ASUSTek       | P5QL-CM                     | Desktop     | [2eb12a165a](https://linux-hardware.org/?probe=2eb12a165a) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | Notebook    | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| Gigabyte      | P43-ES3G                    | Desktop     | [86c3abf0e6](https://linux-hardware.org/?probe=86c3abf0e6) | Jun 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [15fdd98402](https://linux-hardware.org/?probe=15fdd98402) | Jun 07, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | Notebook    | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f543bd7919](https://linux-hardware.org/?probe=f543bd7919) | Jun 02, 2021 |
| Pegatron      | A15                         | Notebook    | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| Intel         | DP965LT AAD41694-209        | Desktop     | [64b76f3b3d](https://linux-hardware.org/?probe=64b76f3b3d) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [446457dc79](https://linux-hardware.org/?probe=446457dc79) | Jun 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d71fba3e59](https://linux-hardware.org/?probe=d71fba3e59) | Jun 01, 2021 |
| ASUSTek       | P5QL-CM                     | Desktop     | [53e36afc53](https://linux-hardware.org/?probe=53e36afc53) | Jun 01, 2021 |
| Intel         | DG965RY AAD41691-206        | Desktop     | [1b04d7a76f](https://linux-hardware.org/?probe=1b04d7a76f) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | Notebook    | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f77e2ebb10](https://linux-hardware.org/?probe=f77e2ebb10) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [31547cbbcf](https://linux-hardware.org/?probe=31547cbbcf) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [4392e54288](https://linux-hardware.org/?probe=4392e54288) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [2fda3b392d](https://linux-hardware.org/?probe=2fda3b392d) | May 31, 2021 |
| Medion        | MS-7616                     | Desktop     | [c3730db7dd](https://linux-hardware.org/?probe=c3730db7dd) | May 31, 2021 |
| ASUSTek       | P7H55                       | Desktop     | [ac572ef424](https://linux-hardware.org/?probe=ac572ef424) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [41c4d75b72](https://linux-hardware.org/?probe=41c4d75b72) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [8b834e3fc0](https://linux-hardware.org/?probe=8b834e3fc0) | May 31, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [8932eef460](https://linux-hardware.org/?probe=8932eef460) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Toshiba       | Satellite U800W             | Notebook    | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [eb3d04e089](https://linux-hardware.org/?probe=eb3d04e089) | May 29, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [92aa2017b9](https://linux-hardware.org/?probe=92aa2017b9) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | CX700                       | Notebook    | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [7ca350189c](https://linux-hardware.org/?probe=7ca350189c) | May 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | Notebook    | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | Notebook    | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [e00920532d](https://linux-hardware.org/?probe=e00920532d) | May 27, 2021 |
| Lenovo        | Z710 20250                  | Notebook    | [76d72eb45f](https://linux-hardware.org/?probe=76d72eb45f) | May 27, 2021 |
| Aquarius      | NS585                       | Notebook    | [e2035017ff](https://linux-hardware.org/?probe=e2035017ff) | May 26, 2021 |
| Aquarius      | NS585                       | Notebook    | [d2b5b53798](https://linux-hardware.org/?probe=d2b5b53798) | May 26, 2021 |
| Aquarius      | NS585                       | Notebook    | [1c84a98f48](https://linux-hardware.org/?probe=1c84a98f48) | May 26, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Gigabyte      | H81M-S1                     | Desktop     | [07fcf530f1](https://linux-hardware.org/?probe=07fcf530f1) | May 24, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [834e2e7b7e](https://linux-hardware.org/?probe=834e2e7b7e) | May 24, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [71c9c1e86f](https://linux-hardware.org/?probe=71c9c1e86f) | May 21, 2021 |
| Dell          | Latitude 7410               | Convertible | [bc7c58f248](https://linux-hardware.org/?probe=bc7c58f248) | May 21, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [8947349c20](https://linux-hardware.org/?probe=8947349c20) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [1c271464f4](https://linux-hardware.org/?probe=1c271464f4) | May 21, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [95f4bad7b5](https://linux-hardware.org/?probe=95f4bad7b5) | May 20, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7410               | Convertible | [cbd8832f44](https://linux-hardware.org/?probe=cbd8832f44) | May 19, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | Notebook    | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| sunxi         | Unknown                     | Soc         | [d54c3a2a33](https://linux-hardware.org/?probe=d54c3a2a33) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [f2d7c64e1c](https://linux-hardware.org/?probe=f2d7c64e1c) | May 18, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [b471b7cf95](https://linux-hardware.org/?probe=b471b7cf95) | May 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FEA0... | Convertible | [2a0eca4670](https://linux-hardware.org/?probe=2a0eca4670) | May 17, 2021 |
| HP            | Compaq Presario C700        | Notebook    | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [1699c8eab5](https://linux-hardware.org/?probe=1699c8eab5) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [bd2a3417a0](https://linux-hardware.org/?probe=bd2a3417a0) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [3a27d20178](https://linux-hardware.org/?probe=3a27d20178) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [17ff2add7a](https://linux-hardware.org/?probe=17ff2add7a) | May 14, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [07ea2a4b8e](https://linux-hardware.org/?probe=07ea2a4b8e) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [823bbbb4ed](https://linux-hardware.org/?probe=823bbbb4ed) | May 12, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [af6e17ac8c](https://linux-hardware.org/?probe=af6e17ac8c) | May 12, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [f6d2299c81](https://linux-hardware.org/?probe=f6d2299c81) | May 12, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [380bf2eacc](https://linux-hardware.org/?probe=380bf2eacc) | May 11, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [589d53b7ce](https://linux-hardware.org/?probe=589d53b7ce) | May 11, 2021 |
| ASUSTek       | T100TAS                     | Notebook    | [0b8e360f8a](https://linux-hardware.org/?probe=0b8e360f8a) | May 07, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| HP            | Split 13 x2 PC              | Notebook    | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [0c87980ed4](https://linux-hardware.org/?probe=0c87980ed4) | Apr 29, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [372d11517d](https://linux-hardware.org/?probe=372d11517d) | Apr 28, 2021 |
| Pegatron      | C15B                        | Desktop     | [54d1d5cde0](https://linux-hardware.org/?probe=54d1d5cde0) | Apr 27, 2021 |
| Lenovo        | G550 20023                  | Notebook    | [69b57eec89](https://linux-hardware.org/?probe=69b57eec89) | Apr 27, 2021 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| Biostar       | B450MH                      | Desktop     | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [89d9898d88](https://linux-hardware.org/?probe=89d9898d88) | Apr 26, 2021 |
| HP            | 3399                        | Desktop     | [4085344b20](https://linux-hardware.org/?probe=4085344b20) | Apr 26, 2021 |
| ASUSTek       | P8Z77-M                     | Desktop     | [8495ecf36e](https://linux-hardware.org/?probe=8495ecf36e) | Apr 26, 2021 |
| Acer          | Aspire 5560                 | Notebook    | [853337664f](https://linux-hardware.org/?probe=853337664f) | Apr 26, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [446238dd0c](https://linux-hardware.org/?probe=446238dd0c) | Apr 25, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [bb76391a12](https://linux-hardware.org/?probe=bb76391a12) | Apr 25, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1c397e42c6](https://linux-hardware.org/?probe=1c397e42c6) | Apr 23, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [fc24c1c56f](https://linux-hardware.org/?probe=fc24c1c56f) | Apr 23, 2021 |
| Dell          | Latitude E6330              | Notebook    | [d2a06d1cde](https://linux-hardware.org/?probe=d2a06d1cde) | Apr 22, 2021 |
| HP            | 3399                        | Desktop     | [a265b73c37](https://linux-hardware.org/?probe=a265b73c37) | Apr 22, 2021 |
| Gigabyte      | H410M S2H                   | Desktop     | [88f270d1d0](https://linux-hardware.org/?probe=88f270d1d0) | Apr 22, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [60eb0d02a7](https://linux-hardware.org/?probe=60eb0d02a7) | Apr 21, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | Notebook    | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6cdd8afad1](https://linux-hardware.org/?probe=6cdd8afad1) | Apr 19, 2021 |
| ECS           | G31T-M7                     | Desktop     | [4e1e8d1c1a](https://linux-hardware.org/?probe=4e1e8d1c1a) | Apr 19, 2021 |
| ECS           | G31T-M7                     | Desktop     | [2ffcd0d78d](https://linux-hardware.org/?probe=2ffcd0d78d) | Apr 19, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [92866f8994](https://linux-hardware.org/?probe=92866f8994) | Apr 17, 2021 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| HP            | 3399                        | Desktop     | [ae0ed46819](https://linux-hardware.org/?probe=ae0ed46819) | Apr 16, 2021 |
| MSI           | G41M-P28                    | Desktop     | [0b714b1814](https://linux-hardware.org/?probe=0b714b1814) | Apr 16, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7a88de99e8](https://linux-hardware.org/?probe=7a88de99e8) | Apr 16, 2021 |
| Intel         | DQ45CB AAE30148-206         | Desktop     | [6a9f891230](https://linux-hardware.org/?probe=6a9f891230) | Apr 15, 2021 |
| HP            | Pavilion g6                 | Notebook    | [8f9f4e211d](https://linux-hardware.org/?probe=8f9f4e211d) | Apr 15, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [7a1d829bbb](https://linux-hardware.org/?probe=7a1d829bbb) | Apr 14, 2021 |
| HP            | Pavilion g6                 | Notebook    | [d3e2f03de0](https://linux-hardware.org/?probe=d3e2f03de0) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [97a320e9df](https://linux-hardware.org/?probe=97a320e9df) | Apr 14, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [c0536c5433](https://linux-hardware.org/?probe=c0536c5433) | Apr 13, 2021 |
| HP            | Pavilion 17                 | Notebook    | [9bd4ef879a](https://linux-hardware.org/?probe=9bd4ef879a) | Apr 12, 2021 |
| Sony          | VPCEJ3S1R                   | Notebook    | [a57c607409](https://linux-hardware.org/?probe=a57c607409) | Apr 12, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [9f79d5f548](https://linux-hardware.org/?probe=9f79d5f548) | Apr 09, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [d90f3a34d1](https://linux-hardware.org/?probe=d90f3a34d1) | Apr 08, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [2f2f027581](https://linux-hardware.org/?probe=2f2f027581) | Apr 07, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [a0bb6867cd](https://linux-hardware.org/?probe=a0bb6867cd) | Apr 07, 2021 |
| ASUSTek       | P5B                         | Desktop     | [e6f18312ca](https://linux-hardware.org/?probe=e6f18312ca) | Apr 07, 2021 |
| Dell          | Latitude E6330              | Notebook    | [46855c6116](https://linux-hardware.org/?probe=46855c6116) | Apr 07, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [1ae4d948e8](https://linux-hardware.org/?probe=1ae4d948e8) | Apr 06, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [b8439c6414](https://linux-hardware.org/?probe=b8439c6414) | Apr 04, 2021 |
| Notebook      | N650DU                      | Notebook    | [34efc4fdfe](https://linux-hardware.org/?probe=34efc4fdfe) | Apr 02, 2021 |
| ECS           | G31T-M9                     | Desktop     | [769cb653f7](https://linux-hardware.org/?probe=769cb653f7) | Apr 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 20HRC... | Notebook    | [354cd6e94e](https://linux-hardware.org/?probe=354cd6e94e) | Apr 02, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [6ba14141a6](https://linux-hardware.org/?probe=6ba14141a6) | Apr 01, 2021 |
| Acer          | TravelMate P259-MG          | Notebook    | [9acbd94cd7](https://linux-hardware.org/?probe=9acbd94cd7) | Apr 01, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [f2e276c03d](https://linux-hardware.org/?probe=f2e276c03d) | Apr 01, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [b93f919e23](https://linux-hardware.org/?probe=b93f919e23) | Mar 31, 2021 |
| Intel         | DG33FB AAD81072-303         | Desktop     | [df4527f66c](https://linux-hardware.org/?probe=df4527f66c) | Mar 31, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [2e925f1ee2](https://linux-hardware.org/?probe=2e925f1ee2) | Mar 30, 2021 |
| ASUSTek       | P5K-VM                      | Desktop     | [4c297474dc](https://linux-hardware.org/?probe=4c297474dc) | Mar 30, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [8d09fd5fad](https://linux-hardware.org/?probe=8d09fd5fad) | Mar 29, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [d22bc80177](https://linux-hardware.org/?probe=d22bc80177) | Mar 29, 2021 |
| Micro Elec... | MG-VCTR002-2060             | Notebook    | [3724755eea](https://linux-hardware.org/?probe=3724755eea) | Mar 28, 2021 |
| HP            | ProBook 4520s               | Notebook    | [7577a208f6](https://linux-hardware.org/?probe=7577a208f6) | Mar 22, 2021 |
| ASUSTek       | Z87I-DELUXE                 | Desktop     | [34a8087893](https://linux-hardware.org/?probe=34a8087893) | Mar 22, 2021 |
| Lenovo        | 3706 SDK0J40700 WIN 3258... | Desktop     | [3876e9ed84](https://linux-hardware.org/?probe=3876e9ed84) | Mar 21, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [2d50a5e736](https://linux-hardware.org/?probe=2d50a5e736) | Mar 21, 2021 |
| Acer          | One S1003                   | Tablet      | [5e5544872a](https://linux-hardware.org/?probe=5e5544872a) | Mar 20, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [be20eafb4f](https://linux-hardware.org/?probe=be20eafb4f) | Mar 20, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [0dd442a763](https://linux-hardware.org/?probe=0dd442a763) | Mar 19, 2021 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [f4050ccf53](https://linux-hardware.org/?probe=f4050ccf53) | Mar 18, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [f20eacbf5c](https://linux-hardware.org/?probe=f20eacbf5c) | Mar 18, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [e3d85d4006](https://linux-hardware.org/?probe=e3d85d4006) | Mar 15, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [3c8f0ff2d4](https://linux-hardware.org/?probe=3c8f0ff2d4) | Mar 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [bcdd60dc85](https://linux-hardware.org/?probe=bcdd60dc85) | Mar 14, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [2f3f591fd0](https://linux-hardware.org/?probe=2f3f591fd0) | Mar 10, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [bd5d97f7e7](https://linux-hardware.org/?probe=bd5d97f7e7) | Mar 07, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [d2ee782761](https://linux-hardware.org/?probe=d2ee782761) | Mar 07, 2021 |
| ASUSTek       | K53E                        | Notebook    | [f84c0f2b1b](https://linux-hardware.org/?probe=f84c0f2b1b) | Mar 05, 2021 |
| Micro Elec... | MG-VCTR002-2060             | Notebook    | [f86910b3b3](https://linux-hardware.org/?probe=f86910b3b3) | Mar 05, 2021 |
| ASUSTek       | K53E                        | Notebook    | [8a98e99c2f](https://linux-hardware.org/?probe=8a98e99c2f) | Mar 05, 2021 |
| Intel         | DG31PR AAD97573-301         | Desktop     | [09e15a8c00](https://linux-hardware.org/?probe=09e15a8c00) | Mar 04, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [db2b8a39be](https://linux-hardware.org/?probe=db2b8a39be) | Mar 03, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | Notebook    | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [d8b4e607e1](https://linux-hardware.org/?probe=d8b4e607e1) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [eca0e7f55f](https://linux-hardware.org/?probe=eca0e7f55f) | Mar 02, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [88c5aee182](https://linux-hardware.org/?probe=88c5aee182) | Mar 02, 2021 |
| Lenovo        | V570 HuronRiver Platform    | Notebook    | [d93b0955fa](https://linux-hardware.org/?probe=d93b0955fa) | Feb 27, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [744852fa69](https://linux-hardware.org/?probe=744852fa69) | Feb 25, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [720734ca06](https://linux-hardware.org/?probe=720734ca06) | Feb 25, 2021 |
| Dell          | Inspiron 5759               | Notebook    | [3710e0320f](https://linux-hardware.org/?probe=3710e0320f) | Feb 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3bb9f3d0f3](https://linux-hardware.org/?probe=3bb9f3d0f3) | Feb 23, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [88bab7f6e7](https://linux-hardware.org/?probe=88bab7f6e7) | Feb 22, 2021 |
| HP            | ENVY Notebook               | Notebook    | [e4cc508565](https://linux-hardware.org/?probe=e4cc508565) | Feb 21, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [6642872403](https://linux-hardware.org/?probe=6642872403) | Feb 19, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [da5067a065](https://linux-hardware.org/?probe=da5067a065) | Feb 18, 2021 |
| Dell          | Latitude E6440              | Notebook    | [ce086f8df0](https://linux-hardware.org/?probe=ce086f8df0) | Feb 18, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [77da992403](https://linux-hardware.org/?probe=77da992403) | Feb 14, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [2e19efe5b1](https://linux-hardware.org/?probe=2e19efe5b1) | Feb 12, 2021 |
| Dell          | Inspiron 5759               | Notebook    | [e7c528c9be](https://linux-hardware.org/?probe=e7c528c9be) | Feb 11, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [97e14d7021](https://linux-hardware.org/?probe=97e14d7021) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [954514a52a](https://linux-hardware.org/?probe=954514a52a) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [67f2a70d2a](https://linux-hardware.org/?probe=67f2a70d2a) | Feb 09, 2021 |
| Dell          | Inspiron 5759               | Notebook    | [cd72d5cd68](https://linux-hardware.org/?probe=cd72d5cd68) | Feb 09, 2021 |
| Dell          | Latitude 7400               | Notebook    | [32c7787bcb](https://linux-hardware.org/?probe=32c7787bcb) | Feb 04, 2021 |
| MSI           | MS-7329                     | Desktop     | [d67a4df7d0](https://linux-hardware.org/?probe=d67a4df7d0) | Feb 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [9b82b49d40](https://linux-hardware.org/?probe=9b82b49d40) | Feb 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [6acba7c545](https://linux-hardware.org/?probe=6acba7c545) | Feb 03, 2021 |
| Unknown       | Unknown                     | Notebook    | [ad10dd6be0](https://linux-hardware.org/?probe=ad10dd6be0) | Feb 03, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [935ccffcd5](https://linux-hardware.org/?probe=935ccffcd5) | Feb 01, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [96d6904297](https://linux-hardware.org/?probe=96d6904297) | Feb 01, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [67cfeeb58a](https://linux-hardware.org/?probe=67cfeeb58a) | Jan 31, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [4bff426962](https://linux-hardware.org/?probe=4bff426962) | Jan 31, 2021 |
| Unknown       | Unknown                     | Notebook    | [ea0d120a2b](https://linux-hardware.org/?probe=ea0d120a2b) | Jan 31, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [288a08d946](https://linux-hardware.org/?probe=288a08d946) | Jan 26, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5d23694899](https://linux-hardware.org/?probe=5d23694899) | Jan 24, 2021 |
| Positivo      | C14CR21                     | Notebook    | [0807ce46f1](https://linux-hardware.org/?probe=0807ce46f1) | Jan 19, 2021 |
| Unknown       | Shenzhen Amediatech Tech... | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [4bdbb16f3d](https://linux-hardware.org/?probe=4bdbb16f3d) | Jan 17, 2021 |
| Acer          | Aspire 5750Z                | Notebook    | [14ca9bb504](https://linux-hardware.org/?probe=14ca9bb504) | Jan 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [286214a4e2](https://linux-hardware.org/?probe=286214a4e2) | Jan 15, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [04b6596686](https://linux-hardware.org/?probe=04b6596686) | Jan 13, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [1ec8c1ccd1](https://linux-hardware.org/?probe=1ec8c1ccd1) | Jan 13, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [6afcc11fef](https://linux-hardware.org/?probe=6afcc11fef) | Jan 08, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [1708c28c7b](https://linux-hardware.org/?probe=1708c28c7b) | Jan 08, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [3653c47477](https://linux-hardware.org/?probe=3653c47477) | Jan 07, 2021 |
| Dell          | 0K83V0 A00                  | Desktop     | [54858a0cb0](https://linux-hardware.org/?probe=54858a0cb0) | Jan 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [1d09a49510](https://linux-hardware.org/?probe=1d09a49510) | Jan 04, 2021 |
| sunxi         | Unknown                     | Soc         | [604dd9d393](https://linux-hardware.org/?probe=604dd9d393) | Feb 25, 2020 |
| Lenovo        | ThinkPad E480 20KN001NMX    | Notebook    | [4f055c0cf5](https://linux-hardware.org/?probe=4f055c0cf5) | Oct 08, 2019 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [8d9dbecbba](https://linux-hardware.org/?probe=8d9dbecbba) | Aug 11, 2019 |
| Dell          | Inspiron 11-3168            | Notebook    | [3831423c95](https://linux-hardware.org/?probe=3831423c95) | Jun 30, 2019 |
| Dell          | Inspiron 11-3168            | Notebook    | [4343600da2](https://linux-hardware.org/?probe=4343600da2) | Jun 30, 2019 |
| Dell          | Inspiron 11-3168            | Notebook    | [a1f5874ef6](https://linux-hardware.org/?probe=a1f5874ef6) | Jun 30, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.0-8-amd64                 | 871       | 55.98%  |
| 5.10.0-7-amd64                 | 256       | 16.45%  |
| 5.10.0-2-amd64                 | 106       | 6.81%   |
| 5.10.0-9-amd64                 | 76        | 4.88%   |
| 5.10.0-6-amd64                 | 44        | 2.83%   |
| 5.10.0-8-arm64                 | 18        | 1.16%   |
| 5.10.0-8-686-pae               | 14        | 0.9%    |
| 5.10.0-3-amd64                 | 14        | 0.9%    |
| 5.10.0-4-amd64                 | 10        | 0.64%   |
| 5.10.0-5-amd64                 | 8         | 0.51%   |
| 5.11.22-4-pve                  | 7         | 0.45%   |
| 5.10.0-8-686                   | 7         | 0.45%   |
| 5.10.0-1-amd64                 | 6         | 0.39%   |
| 5.11.22-5-pve                  | 5         | 0.32%   |
| 5.11.22-1-pve                  | 5         | 0.32%   |
| 5.10.0-9-686                   | 4         | 0.26%   |
| 5.10-sunxi64                   | 4         | 0.26%   |
| 5.13.0-13.1-liquorix-amd64     | 3         | 0.19%   |
| 5.12.0-19.3-liquorix-amd64     | 3         | 0.19%   |
| 5.11.22-2-pve                  | 3         | 0.19%   |
| 5.10.0-9-686-pae               | 3         | 0.19%   |
| 5.10.0-8-rt-amd64              | 3         | 0.19%   |
| 5.10.0-8-armmp-lpae            | 3         | 0.19%   |
| 5.14.0-2-amd64                 | 2         | 0.13%   |
| 5.11.22-3-pve                  | 2         | 0.13%   |
| 5.10.42+truenas                | 2         | 0.13%   |
| 4.19.0-14-amd64                | 2         | 0.13%   |
| 5.9.0-arm-64                   | 1         | 0.06%   |
| 5.8.0-3-amd64                  | 1         | 0.06%   |
| 5.4.18-sunxi64                 | 1         | 0.06%   |
| 5.4.148                        | 1         | 0.06%   |
| 5.4.0-73-generic               | 1         | 0.06%   |
| 5.15.0-rc5-recomp              | 1         | 0.06%   |
| 5.14.9-xanmod1-cacule          | 1         | 0.06%   |
| 5.14.6-ndmnet-sid-1            | 1         | 0.06%   |
| 5.14.6                         | 1         | 0.06%   |
| 5.14.0-trunk-amd64             | 1         | 0.06%   |
| 5.14.0-rc3-prygun              | 1         | 0.06%   |
| 5.14.0-2mx-amd64               | 1         | 0.06%   |
| 5.14.0-14.1-liquorix-amd64     | 1         | 0.06%   |
| 5.14.0+                        | 1         | 0.06%   |
| 5.13.8-xanmod1                 | 1         | 0.06%   |
| 5.13.8-gnu                     | 1         | 0.06%   |
| 5.13.8                         | 1         | 0.06%   |
| 5.13.5-xanmod1                 | 1         | 0.06%   |
| 5.13.4-e5520                   | 1         | 0.06%   |
| 5.13.4                         | 1         | 0.06%   |
| 5.13.3                         | 1         | 0.06%   |
| 5.13.1a                        | 1         | 0.06%   |
| 5.13.15-xanmod1                | 1         | 0.06%   |
| 5.13.13-arch1-1                | 1         | 0.06%   |
| 5.13.13                        | 1         | 0.06%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1         | 0.06%   |
| 5.13.0-12.1-liquorix-amd64     | 1         | 0.06%   |
| 5.13.0-10.3-liquorix-amd64     | 1         | 0.06%   |
| 5.12.4                         | 1         | 0.06%   |
| 5.12.18-amd64-desktop          | 1         | 0.06%   |
| 5.12.14-amd64-desktop          | 1         | 0.06%   |
| 5.12.10                        | 1         | 0.06%   |
| 5.12.1                         | 1         | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 1406      | 93.11%  |
| 5.11.22  | 22        | 1.46%   |
| 5.14.0   | 7         | 0.46%   |
| 4.19.0   | 7         | 0.46%   |
| 5.13.0   | 6         | 0.4%    |
| 5.12.0   | 4         | 0.26%   |
| 5.11.0   | 4         | 0.26%   |
| 5.10     | 4         | 0.26%   |
| 5.13.8   | 3         | 0.2%    |
| 5.14.6   | 2         | 0.13%   |
| 5.13.4   | 2         | 0.13%   |
| 5.13.13  | 2         | 0.13%   |
| 5.11.15  | 2         | 0.13%   |
| 5.10.42  | 2         | 0.13%   |
| 5.10.10  | 2         | 0.13%   |
| 5.1.0    | 2         | 0.13%   |
| 5.9.0    | 1         | 0.07%   |
| 5.8.0    | 1         | 0.07%   |
| 5.4.18   | 1         | 0.07%   |
| 5.4.148  | 1         | 0.07%   |
| 5.4.0    | 1         | 0.07%   |
| 5.15.0   | 1         | 0.07%   |
| 5.14.9   | 1         | 0.07%   |
| 5.13.5   | 1         | 0.07%   |
| 5.13.3   | 1         | 0.07%   |
| 5.13.15  | 1         | 0.07%   |
| 5.13.1   | 1         | 0.07%   |
| 5.12.4   | 1         | 0.07%   |
| 5.12.18  | 1         | 0.07%   |
| 5.12.14  | 1         | 0.07%   |
| 5.12.10  | 1         | 0.07%   |
| 5.12.1   | 1         | 0.07%   |
| 5.11.9   | 1         | 0.07%   |
| 5.11.14  | 1         | 0.07%   |
| 5.10.65  | 1         | 0.07%   |
| 5.10.63  | 1         | 0.07%   |
| 5.10.52  | 1         | 0.07%   |
| 5.10.46  | 1         | 0.07%   |
| 5.10.40  | 1         | 0.07%   |
| 5.10.38  | 1         | 0.07%   |
| 5.10.35  | 1         | 0.07%   |
| 5.10.21  | 1         | 0.07%   |
| 5.10.18  | 1         | 0.07%   |
| 5.10.12  | 1         | 0.07%   |
| 5.1.12   | 1         | 0.07%   |
| 4.4.194  | 1         | 0.07%   |
| 4.4.190  | 1         | 0.07%   |
| 4.19.181 | 1         | 0.07%   |
| 3.10.54  | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 1419      | 94.1%   |
| 5.11    | 30        | 1.99%   |
| 5.13    | 16        | 1.06%   |
| 5.14    | 10        | 0.66%   |
| 5.12    | 9         | 0.6%    |
| 4.19    | 8         | 0.53%   |
| 5       | 4         | 0.27%   |
| 5.4     | 3         | 0.2%    |
| 5.1     | 3         | 0.2%    |
| 4.4     | 2         | 0.13%   |
| 5.9     | 1         | 0.07%   |
| 5.8     | 1         | 0.07%   |
| 5.15    | 1         | 0.07%   |
| 3.10    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1436      | 95.48%  |
| i686    | 33        | 2.19%   |
| aarch64 | 27        | 1.8%    |
| armv7l  | 8         | 0.53%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 650       | 42.85%  |
| GNOME            | 323       | 21.29%  |
| KDE5             | 169       | 11.14%  |
| XFCE             | 126       | 8.31%   |
| MATE             | 55        | 3.63%   |
| LXDE             | 28        | 1.85%   |
| X-Cinnamon       | 27        | 1.78%   |
| KDE              | 27        | 1.78%   |
| Cinnamon         | 27        | 1.78%   |
| i3               | 24        | 1.58%   |
| LXQt             | 16        | 1.05%   |
| lightdm-xsession | 9         | 0.59%   |
| Trinity          | 7         | 0.46%   |
| GNOME Flashback  | 7         | 0.46%   |
| openbox          | 5         | 0.33%   |
| GNOME Classic    | 3         | 0.2%    |
| Budgie           | 3         | 0.2%    |
| awesome          | 3         | 0.2%    |
| sway             | 2         | 0.13%   |
| Enlightenment    | 2         | 0.13%   |
| ICEWM            | 1         | 0.07%   |
| GNUstep          | 1         | 0.07%   |
| default          | 1         | 0.07%   |
| Deepin           | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 624       | 41.13%  |
| Unknown | 557       | 36.72%  |
| Wayland | 230       | 15.16%  |
| Tty     | 106       | 6.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 775       | 51.26%  |
| GDM     | 266       | 17.59%  |
| SDDM    | 171       | 11.31%  |
| TDM     | 154       | 10.19%  |
| LightDM | 131       | 8.66%   |
| GDM3    | 6         | 0.4%    |
| XDM     | 3         | 0.2%    |
| SLiM    | 3         | 0.2%    |
| NODM    | 2         | 0.13%   |
| KDM     | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 431       | 28.58%  |
| Unknown | 299       | 19.83%  |
| ru_RU   | 291       | 19.3%   |
| en_GB   | 61        | 4.05%   |
| es_ES   | 56        | 3.71%   |
| fr_FR   | 48        | 3.18%   |
| de_DE   | 45        | 2.98%   |
| pt_BR   | 34        | 2.25%   |
| it_IT   | 23        | 1.53%   |
| pl_PL   | 21        | 1.39%   |
| en_AU   | 17        | 1.13%   |
| en_CA   | 14        | 0.93%   |
| C       | 12        | 0.8%    |
| es_MX   | 9         | 0.6%    |
| ja_JP   | 8         | 0.53%   |
| en_IN   | 8         | 0.53%   |
| sv_SE   | 7         | 0.46%   |
| es_AR   | 7         | 0.46%   |
| de_CH   | 7         | 0.46%   |
| de_AT   | 7         | 0.46%   |
| zh_CN   | 6         | 0.4%    |
| tr_TR   | 6         | 0.4%    |
| pt_PT   | 6         | 0.4%    |
| nl_BE   | 6         | 0.4%    |
| hu_HU   | 6         | 0.4%    |
| uk_UA   | 5         | 0.33%   |
| en_IE   | 5         | 0.33%   |
| cs_CZ   | 5         | 0.33%   |
| ru_UA   | 3         | 0.2%    |
| nn_NO   | 3         | 0.2%    |
| nl_NL   | 3         | 0.2%    |
| fi_FI   | 3         | 0.2%    |
| es_VE   | 3         | 0.2%    |
| es_CO   | 3         | 0.2%    |
| en_ZA   | 3         | 0.2%    |
| bg_BG   | 3         | 0.2%    |
| zh_TW   | 2         | 0.13%   |
| sk_SK   | 2         | 0.13%   |
| ro_RO   | 2         | 0.13%   |
| hr_HR   | 2         | 0.13%   |
| en_SG   | 2         | 0.13%   |
| en_NZ   | 2         | 0.13%   |
| en_HK   | 2         | 0.13%   |
| en_DK   | 2         | 0.13%   |
| ca_ES   | 2         | 0.13%   |
| sr_RS   | 1         | 0.07%   |
| nb_NO   | 1         | 0.07%   |
| gl_ES   | 1         | 0.07%   |
| fr_CH   | 1         | 0.07%   |
| fr_BE   | 1         | 0.07%   |
| et_EE   | 1         | 0.07%   |
| es_UY   | 1         | 0.07%   |
| es_US   | 1         | 0.07%   |
| es_GT   | 1         | 0.07%   |
| es_EC   | 1         | 0.07%   |
| es_CR   | 1         | 0.07%   |
| es_CL   | 1         | 0.07%   |
| eo      | 1         | 0.07%   |
| en_ZM   | 1         | 0.07%   |
| en_SI   | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 875       | 57.79%  |
| BIOS | 639       | 42.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 818       | 54.35%  |
| Overlay | 579       | 38.47%  |
| Btrfs   | 62        | 4.12%   |
| Zfs     | 16        | 1.06%   |
| Xfs     | 15        | 1%      |
| Ext3    | 7         | 0.47%   |
| Unknown | 4         | 0.27%   |
| Rootfs  | 2         | 0.13%   |
| Tmpfs   | 1         | 0.07%   |
| Ext2    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 923       | 61.04%  |
| MBR     | 427       | 28.24%  |
| Unknown | 162       | 10.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1350      | 89.46%  |
| Yes       | 159       | 10.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1020      | 67.55%  |
| Yes       | 490       | 32.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 277       | 18.42%  |
| ASUSTek Computer        | 222       | 14.76%  |
| Apple                   | 168       | 11.17%  |
| Hewlett-Packard         | 141       | 9.38%   |
| Dell                    | 130       | 8.64%   |
| Gigabyte Technology     | 90        | 5.98%   |
| ASRock                  | 79        | 5.25%   |
| Acer                    | 62        | 4.12%   |
| MSI                     | 57        | 3.79%   |
| Google                  | 49        | 3.26%   |
| Intel                   | 31        | 2.06%   |
| ECS                     | 20        | 1.33%   |
| Raspberry Pi Foundation | 19        | 1.26%   |
| Aquarius                | 12        | 0.8%    |
| Fujitsu                 | 8         | 0.53%   |
| Unknown                 | 8         | 0.53%   |
| Toshiba                 | 7         | 0.47%   |
| Supermicro              | 7         | 0.47%   |
| Samsung Electronics     | 7         | 0.47%   |
| Foxconn                 | 7         | 0.47%   |
| Sony                    | 6         | 0.4%    |
| Pegatron                | 6         | 0.4%    |
| HUAWEI                  | 6         | 0.4%    |
| Timi                    | 4         | 0.27%   |
| Pine Microsystems       | 4         | 0.27%   |
| Notebook                | 4         | 0.27%   |
| Hardkernel              | 4         | 0.27%   |
| Clevo                   | 4         | 0.27%   |
| AMI                     | 4         | 0.27%   |
| sunxi                   | 3         | 0.2%    |
| Fujitsu Siemens         | 3         | 0.2%    |
| SLIMBOOK                | 2         | 0.13%   |
| Semp Toshiba            | 2         | 0.13%   |
| Positivo                | 2         | 0.13%   |
| PC Specialist           | 2         | 0.13%   |
| Microsoft               | 2         | 0.13%   |
| LG Electronics          | 2         | 0.13%   |
| Huanan                  | 2         | 0.13%   |
| HPE                     | 2         | 0.13%   |
| Chuwi                   | 2         | 0.13%   |
| Biostar                 | 2         | 0.13%   |
| ASRockRack              | 2         | 0.13%   |
| ZOTAC                   | 1         | 0.07%   |
| YJKC                    | 1         | 0.07%   |
| UNOWHY                  | 1         | 0.07%   |
| TUXEDO                  | 1         | 0.07%   |
| TrekStor                | 1         | 0.07%   |
| Sun Microsystems        | 1         | 0.07%   |
| SimpliVity              | 1         | 0.07%   |
| Shuttle                 | 1         | 0.07%   |
| Schenker                | 1         | 0.07%   |
| RuggedPC                | 1         | 0.07%   |
| Rockchip                | 1         | 0.07%   |
| Quanta                  | 1         | 0.07%   |
| QIYIDA                  | 1         | 0.07%   |
| Protectli               | 1         | 0.07%   |
| Panasonic               | 1         | 0.07%   |
| Packard Bell            | 1         | 0.07%   |
| Monster                 | 1         | 0.07%   |
| Micro Electronics       | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBookAir7,1                       | 75        | 4.99%   |
| Apple MacBookAir7,2                       | 67        | 4.45%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 55        | 3.66%   |
| Google Enguarde                           | 47        | 3.13%   |
| ASUS All Series                           | 34        | 2.26%   |
| ASRock H470M-HVS                          | 20        | 1.33%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 15        | 1%      |
| Acer Aspire A315-23                       | 15        | 1%      |
| ECS H61H2-M13                             | 13        | 0.86%   |
| Aquarius NS585                            | 12        | 0.8%    |
| Unknown                                   | 11        | 0.73%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 8         | 0.53%   |
| ASUS P8H67-M                              | 7         | 0.47%   |
| ASUS P8H61-M LX3 PLUS R2.0                | 7         | 0.47%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 6         | 0.4%    |
| Gigabyte H81M-S2V                         | 6         | 0.4%    |
| ASRock H61M-VG4                           | 6         | 0.4%    |
| HP EliteBook 8460p                        | 5         | 0.33%   |
| Dell Latitude 7480                        | 5         | 0.33%   |
| ASUS PRIME A320M-K                        | 5         | 0.33%   |
| MSI MS-7721                               | 4         | 0.27%   |
| Gigabyte H61M-DS2 REV 1.2                 | 4         | 0.27%   |
| ECS G31T-M9                               | 4         | 0.27%   |
| Dell XPS 13 9310                          | 4         | 0.27%   |
| Dell OptiPlex 7010                        | 4         | 0.27%   |
| ASUS P8H61-M LX3 R2.0                     | 4         | 0.27%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 3         | 0.2%    |
| MSI MS-7996                               | 3         | 0.2%    |
| MSI MS-7817                               | 3         | 0.2%    |
| Lenovo ThinkPad E475 20H40006US           | 3         | 0.2%    |
| Lenovo IdeaPad L340-15API 81LW            | 3         | 0.2%    |
| Intel Pro, Std, Elt Series                | 3         | 0.2%    |
| Intel DN2820FYK H24582-201                | 3         | 0.2%    |
| HUAWEI NBLK-WAX9X                         | 3         | 0.2%    |
| HP Pavilion Gaming Laptop 15-ec2xxx       | 3         | 0.2%    |
| HP Pavilion g6                            | 3         | 0.2%    |
| Hardkernel Odroid XU4                     | 3         | 0.2%    |
| Gigabyte Z77-D3H                          | 3         | 0.2%    |
| Gigabyte B550I AORUS PRO AX               | 3         | 0.2%    |
| Gigabyte A320M-S2H                        | 3         | 0.2%    |
| Fujitsu ESPRIMO P720                      | 3         | 0.2%    |
| Foxconn H61MXL/H61MXL-K                   | 3         | 0.2%    |
| Dell OptiPlex 3020                        | 3         | 0.2%    |
| ASUS PRIME B450M-K                        | 3         | 0.2%    |
| ASUS PRIME B450M-A                        | 3         | 0.2%    |
| ASUS H110M-R                              | 3         | 0.2%    |
| ASRock G31M-VS2                           | 3         | 0.2%    |
| ASRock B450M Pro4                         | 3         | 0.2%    |
| Apple iMac11,2                            | 3         | 0.2%    |
| Timi TM1613                               | 2         | 0.13%   |
| Semp Toshiba STI                          | 2         | 0.13%   |
| Pine Microsystems Pine64 PinePhone (1.2)  | 2         | 0.13%   |
| MSI MS-7C75                               | 2         | 0.13%   |
| MSI MS-7C56                               | 2         | 0.13%   |
| MSI MS-7C35                               | 2         | 0.13%   |
| MSI MS-7A71                               | 2         | 0.13%   |
| MSI MS-7A70                               | 2         | 0.13%   |
| MSI Bravo 15 A4DDR                        | 2         | 0.13%   |
| Lenovo Yoga 530-14ARR 81H9                | 2         | 0.13%   |
| Lenovo V510-15IKB 80WQ                    | 2         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 198       | 13.16%  |
| Apple MacBookAir7        | 142       | 9.44%   |
| Google Enguarde          | 47        | 3.13%   |
| Acer Aspire              | 43        | 2.86%   |
| Dell Inspiron            | 40        | 2.66%   |
| Lenovo IdeaPad           | 36        | 2.39%   |
| ASUS All                 | 34        | 2.26%   |
| ASUS PRIME               | 31        | 2.06%   |
| Dell Latitude            | 22        | 1.46%   |
| HP EliteBook             | 20        | 1.33%   |
| ASRock H470M-HVS         | 20        | 1.33%   |
| RPi Raspberry            | 19        | 1.26%   |
| HP Pavilion              | 19        | 1.26%   |
| Dell OptiPlex            | 19        | 1.26%   |
| ASUS ROG                 | 18        | 1.2%    |
| HP ProBook               | 17        | 1.13%   |
| HP Compaq                | 17        | 1.13%   |
| Dell XPS                 | 17        | 1.13%   |
| Dell Precision           | 16        | 1.06%   |
| HP Laptop                | 14        | 0.93%   |
| ECS H61H2-M13            | 13        | 0.86%   |
| ASUS P8H61-M             | 13        | 0.86%   |
| ASUS TUF                 | 12        | 0.8%    |
| Aquarius NS585           | 12        | 0.8%    |
| Unknown                  | 11        | 0.73%   |
| Lenovo ThinkCentre       | 8         | 0.53%   |
| Lenovo Yoga              | 7         | 0.47%   |
| Dell Vostro              | 7         | 0.47%   |
| ASUS ZenBook             | 7         | 0.47%   |
| ASUS P8H67-M             | 7         | 0.47%   |
| Toshiba Satellite        | 6         | 0.4%    |
| HP EliteDesk             | 6         | 0.4%    |
| Gigabyte H81M-S2V        | 6         | 0.4%    |
| Gigabyte H61M-DS2        | 6         | 0.4%    |
| ASRock H61M-VG4          | 6         | 0.4%    |
| ASUS VivoBook            | 5         | 0.33%   |
| Acer TravelMate          | 5         | 0.33%   |
| MSI MS-7721              | 4         | 0.27%   |
| Lenovo ThinkBook         | 4         | 0.27%   |
| HP ProLiant              | 4         | 0.27%   |
| HP 250                   | 4         | 0.27%   |
| Gigabyte A320M-S2H       | 4         | 0.27%   |
| Fujitsu ESPRIMO          | 4         | 0.27%   |
| ECS G31T-M9              | 4         | 0.27%   |
| Dell PowerEdge           | 4         | 0.27%   |
| ASUS Pro                 | 4         | 0.27%   |
| ASRock B450M             | 4         | 0.27%   |
| Apple iMac11             | 4         | 0.27%   |
| Acer Swift               | 4         | 0.27%   |
| Pine Microsystems Pine64 | 3         | 0.2%    |
| MSI MS-7996              | 3         | 0.2%    |
| MSI MS-7817              | 3         | 0.2%    |
| Intel Pro                | 3         | 0.2%    |
| Intel DN2820FYK          | 3         | 0.2%    |
| HUAWEI NBLK-WAX9X        | 3         | 0.2%    |
| HP OMEN                  | 3         | 0.2%    |
| HP ENVY                  | 3         | 0.2%    |
| Hardkernel Odroid        | 3         | 0.2%    |
| Gigabyte Z77-D3H         | 3         | 0.2%    |
| Gigabyte B550I           | 3         | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 318       | 21.14%  |
| 2020    | 286       | 19.02%  |
| 2019    | 190       | 12.63%  |
| 2018    | 109       | 7.25%   |
| 2014    | 75        | 4.99%   |
| 2011    | 72        | 4.79%   |
| 2012    | 69        | 4.59%   |
| 2013    | 62        | 4.12%   |
| 2015    | 60        | 3.99%   |
| 2016    | 49        | 3.26%   |
| 2010    | 45        | 2.99%   |
| 2009    | 43        | 2.86%   |
| 2008    | 37        | 2.46%   |
| Unknown | 35        | 2.33%   |
| 2017    | 30        | 1.99%   |
| 2007    | 9         | 0.6%    |
| 2006    | 7         | 0.47%   |
| 2005    | 4         | 0.27%   |
| 2004    | 3         | 0.2%    |
| 2001    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 802       | 53.32%  |
| Desktop        | 539       | 35.84%  |
| Convertible    | 74        | 4.92%   |
| System on chip | 29        | 1.93%   |
| Mini pc        | 20        | 1.33%   |
| Server         | 16        | 1.06%   |
| All in one     | 13        | 0.86%   |
| Tablet         | 7         | 0.47%   |
| Phone          | 3         | 0.2%    |
| Other          | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1424      | 94.56%  |
| Enabled  | 82        | 5.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1453      | 96.61%  |
| Yes  | 51        | 3.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 374       | 24.83%  |
| 3.01-4.0        | 313       | 20.78%  |
| 16.01-24.0      | 311       | 20.65%  |
| 8.01-16.0       | 206       | 13.68%  |
| 32.01-64.0      | 120       | 7.97%   |
| 1.01-2.0        | 67        | 4.45%   |
| 64.01-256.0     | 47        | 3.12%   |
| 2.01-3.0        | 26        | 1.73%   |
| 0.51-1.0        | 23        | 1.53%   |
| 24.01-32.0      | 9         | 0.6%    |
| More than 256.0 | 5         | 0.33%   |
| 0.01-0.5        | 5         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 532       | 34.7%   |
| 0.51-1.0    | 318       | 20.74%  |
| 2.01-3.0    | 230       | 15%     |
| 4.01-8.0    | 164       | 10.7%   |
| 3.01-4.0    | 131       | 8.55%   |
| 0.01-0.5    | 68        | 4.44%   |
| 8.01-16.0   | 58        | 3.78%   |
| 16.01-24.0  | 16        | 1.04%   |
| 24.01-32.0  | 7         | 0.46%   |
| 32.01-64.0  | 6         | 0.39%   |
| 64.01-256.0 | 3         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1040      | 68.92%  |
| 2      | 291       | 19.28%  |
| 3      | 70        | 4.64%   |
| 4      | 46        | 3.05%   |
| 5      | 22        | 1.46%   |
| 8      | 9         | 0.6%    |
| 7      | 7         | 0.46%   |
| 6      | 7         | 0.46%   |
| 0      | 7         | 0.46%   |
| 10     | 3         | 0.2%    |
| 9      | 3         | 0.2%    |
| 13     | 2         | 0.13%   |
| 28     | 1         | 0.07%   |
| 12     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1115      | 74.09%  |
| Yes       | 390       | 25.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1177      | 78.26%  |
| No        | 327       | 21.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1031      | 68.55%  |
| No        | 473       | 31.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 898       | 59.63%  |
| No        | 608       | 40.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 470       | 31.19%  |
| Russia       | 292       | 19.38%  |
| Germany      | 76        | 5.04%   |
| Spain        | 67        | 4.45%   |
| France       | 66        | 4.38%   |
| UK           | 42        | 2.79%   |
| Brazil       | 41        | 2.72%   |
| Poland       | 33        | 2.19%   |
| Switzerland  | 32        | 2.12%   |
| Ukraine      | 31        | 2.06%   |
| Italy        | 26        | 1.73%   |
| Canada       | 20        | 1.33%   |
| Australia    | 19        | 1.26%   |
| Sweden       | 16        | 1.06%   |
| Netherlands  | 16        | 1.06%   |
| Austria      | 14        | 0.93%   |
| Portugal     | 13        | 0.86%   |
| Mexico       | 13        | 0.86%   |
| Belgium      | 13        | 0.86%   |
| Argentina    | 13        | 0.86%   |
| Czechia      | 12        | 0.8%    |
| China        | 11        | 0.73%   |
| Turkey       | 10        | 0.66%   |
| Norway       | 10        | 0.66%   |
| India        | 9         | 0.6%    |
| Hungary      | 9         | 0.6%    |
| Japan        | 8         | 0.53%   |
| Finland      | 7         | 0.46%   |
| Bulgaria     | 7         | 0.46%   |
| Romania      | 6         | 0.4%    |
| Greece       | 6         | 0.4%    |
| Kazakhstan   | 5         | 0.33%   |
| Belarus      | 5         | 0.33%   |
| Venezuela    | 4         | 0.27%   |
| Thailand     | 4         | 0.27%   |
| Ireland      | 4         | 0.27%   |
| Ecuador      | 4         | 0.27%   |
| Taiwan       | 3         | 0.2%    |
| South Africa | 3         | 0.2%    |
| Singapore    | 3         | 0.2%    |
| Philippines  | 3         | 0.2%    |
| Pakistan     | 3         | 0.2%    |
| New Zealand  | 3         | 0.2%    |
| Morocco      | 3         | 0.2%    |
| Latvia       | 3         | 0.2%    |
| Indonesia    | 3         | 0.2%    |
| Croatia      | 3         | 0.2%    |
| Colombia     | 3         | 0.2%    |
| Vietnam      | 2         | 0.13%   |
| Slovenia     | 2         | 0.13%   |
| Guatemala    | 2         | 0.13%   |
| Denmark      | 2         | 0.13%   |
| Costa Rica   | 2         | 0.13%   |
| Chile        | 2         | 0.13%   |
| Bangladesh   | 2         | 0.13%   |
| Zambia       | 1         | 0.07%   |
| Uruguay      | 1         | 0.07%   |
| UAE          | 1         | 0.07%   |
| Syria        | 1         | 0.07%   |
| South Sudan  | 1         | 0.07%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Portland       | 296       | 19.37%  |
| Voronezh       | 228       | 14.92%  |
| St Petersburg  | 21        | 1.37%   |
| M??laga        | 21        | 1.37%   |
| Zurich         | 18        | 1.18%   |
| Paris          | 13        | 0.85%   |
| London         | 12        | 0.79%   |
| Vienna         | 10        | 0.65%   |
| Lyon           | 10        | 0.65%   |
| Frankfort      | 10        | 0.65%   |
| Kyiv           | 9         | 0.59%   |
| Hampden        | 9         | 0.59%   |
| S??o Paulo     | 8         | 0.52%   |
| Moscow         | 8         | 0.52%   |
| Berlin         | 8         | 0.52%   |
| Warsaw         | 7         | 0.46%   |
| Valencia       | 7         | 0.46%   |
| Sofia          | 6         | 0.39%   |
| Ocala          | 6         | 0.39%   |
| Madrid         | 6         | 0.39%   |
| Amsterdam      | 6         | 0.39%   |
| Stockholm      | 5         | 0.33%   |
| Kalamazoo      | 5         | 0.33%   |
| Iasi           | 5         | 0.33%   |
| Athens         | 5         | 0.33%   |
| Sydney         | 4         | 0.26%   |
| Sunnyvale      | 4         | 0.26%   |
| Sevastopol     | 4         | 0.26%   |
| Prague         | 4         | 0.26%   |
| Perm           | 4         | 0.26%   |
| Milan          | 4         | 0.26%   |
| Mesa           | 4         | 0.26%   |
| Melbourne      | 4         | 0.26%   |
| Helsinki       | 4         | 0.26%   |
| Hamburg        | 4         | 0.26%   |
| Ensenada       | 4         | 0.26%   |
| Dublin         | 4         | 0.26%   |
| Bengaluru      | 4         | 0.26%   |
| Bangkok        | 4         | 0.26%   |
| Wroclaw        | 3         | 0.2%    |
| Vladivostok    | 3         | 0.2%    |
| Toronto        | 3         | 0.2%    |
| Thermopolis    | 3         | 0.2%    |
| San Jose       | 3         | 0.2%    |
| Roseville      | 3         | 0.2%    |
| Rome           | 3         | 0.2%    |
| Rio de Janeiro | 3         | 0.2%    |
| Riga           | 3         | 0.2%    |
| Rennes         | 3         | 0.2%    |
| Munich         | 3         | 0.2%    |
| Manchester     | 3         | 0.2%    |
| Lisbon         | 3         | 0.2%    |
| Las Vegas      | 3         | 0.2%    |
| Kharkiv        | 3         | 0.2%    |
| Istanbul       | 3         | 0.2%    |
| Halstead       | 3         | 0.2%    |
| Gloucester     | 3         | 0.2%    |
| Eliot          | 3         | 0.2%    |
| Clitheroe      | 3         | 0.2%    |
| Bern           | 3         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 347       | 436    | 17.09%  |
| WDC                 | 266       | 399    | 13.1%   |
| Seagate             | 258       | 365    | 12.71%  |
| Apple               | 152       | 163    | 7.49%   |
| Unknown             | 126       | 154    | 6.21%   |
| Toshiba             | 121       | 162    | 5.96%   |
| Kingston            | 112       | 130    | 5.52%   |
| Crucial             | 83        | 94     | 4.09%   |
| Hitachi             | 67        | 70     | 3.3%    |
| Sandisk             | 61        | 71     | 3%      |
| Intel               | 52        | 61     | 2.56%   |
| SK Hynix            | 38        | 49     | 1.87%   |
| A-DATA Technology   | 36        | 45     | 1.77%   |
| HGST                | 30        | 37     | 1.48%   |
| Micron Technology   | 24        | 24     | 1.18%   |
| SABRENT             | 22        | 22     | 1.08%   |
| Netac               | 20        | 24     | 0.99%   |
| China               | 16        | 16     | 0.79%   |
| PNY                 | 11        | 11     | 0.54%   |
| Transcend           | 10        | 11     | 0.49%   |
| Fujitsu             | 10        | 14     | 0.49%   |
| SPCC                | 9         | 9      | 0.44%   |
| KIOXIA              | 9         | 10     | 0.44%   |
| LITEON              | 8         | 8      | 0.39%   |
| Silicon Motion      | 7         | 8      | 0.34%   |
| MAXTOR              | 7         | 10     | 0.34%   |
| JMicron             | 7         | 7      | 0.34%   |
| Phison              | 6         | 9      | 0.3%    |
| Patriot             | 6         | 6      | 0.3%    |
| Corsair             | 6         | 7      | 0.3%    |
| XPG                 | 5         | 6      | 0.25%   |
| OCZ                 | 5         | 5      | 0.25%   |
| Lenovo              | 5         | 5      | 0.25%   |
| Intenso             | 5         | 7      | 0.25%   |
| Hewlett-Packard     | 5         | 9      | 0.25%   |
| Union Memory        | 4         | 4      | 0.2%    |
| Team                | 4         | 4      | 0.2%    |
| Mushkin             | 4         | 4      | 0.2%    |
| Lexar               | 4         | 5      | 0.2%    |
| Gigabyte Technology | 4         | 5      | 0.2%    |
| PLEXTOR             | 3         | 5      | 0.15%   |
| Phison Electronics  | 3         | 3      | 0.15%   |
| LITEONIT            | 3         | 3      | 0.15%   |
| Apacer              | 3         | 3      | 0.15%   |
| ZTC                 | 2         | 4      | 0.1%    |
| Solid State Storage | 2         | 2      | 0.1%    |
| Mass                | 2         | 2      | 0.1%    |
| Hajaan              | 2         | 2      | 0.1%    |
| GOODRAM             | 2         | 3      | 0.1%    |
| Xinhaike            | 1         | 1      | 0.05%   |
| USB3.0              | 1         | 1      | 0.05%   |
| TrueNAS             | 1         | 1      | 0.05%   |
| TrekStor            | 1         | 1      | 0.05%   |
| T-FORCE             | 1         | 1      | 0.05%   |
| SILICONMOTION       | 1         | 1      | 0.05%   |
| RDM-II              | 1         | 1      | 0.05%   |
| QGeeM               | 1         | 1      | 0.05%   |
| PNY USB             | 1         | 1      | 0.05%   |
| Pioneer             | 1         | 1      | 0.05%   |
| NAS                 | 1         | 5      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Apple SSD AP0128H 121GB              | 75        | 3.4%    |
| Apple SSD SM0128G 121GB              | 66        | 2.99%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 56        | 2.54%   |
| Seagate ST500DM002-1BD142 500GB      | 26        | 1.18%   |
| Unknown AGND3R  16GB                 | 25        | 1.13%   |
| Toshiba HDWD110 1TB                  | 23        | 1.04%   |
| Seagate ST1000LM035-1RK172 1TB       | 23        | 1.04%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 22        | 1%      |
| SABRENT Disk 320GB                   | 22        | 1%      |
| Kingston SA400S37240G 240GB SSD      | 22        | 1%      |
| Samsung SSD 860 EVO 250GB            | 21        | 0.95%   |
| Netac SSD 240GB                      | 20        | 0.91%   |
| Unknown HAG2e  16GB                  | 19        | 0.86%   |
| Samsung SSD 970 EVO Plus 1TB         | 17        | 0.77%   |
| Kingston SA400S37120G 120GB SSD      | 17        | 0.77%   |
| Samsung SSD 870 EVO 500GB            | 15        | 0.68%   |
| Samsung SSD 860 EVO 1TB              | 15        | 0.68%   |
| Kingston SV300S37A120G 120GB SSD     | 15        | 0.68%   |
| Samsung SSD 860 EVO 500GB            | 14        | 0.63%   |
| Crucial CT500MX500SSD1 500GB         | 14        | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB       | 13        | 0.59%   |
| Samsung SSD 850 EVO 500GB            | 13        | 0.59%   |
| A-DATA SU800 512GB SSD               | 13        | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB       | 12        | 0.54%   |
| Samsung SSD 850 EVO 250GB            | 12        | 0.54%   |
| Crucial CT1000MX500SSD1 1TB          | 11        | 0.5%    |
| Toshiba DT01ACA100 1TB               | 10        | 0.45%   |
| Toshiba DT01ACA050 500GB             | 10        | 0.45%   |
| Seagate ST1000DM003-9YN162 1TB       | 10        | 0.45%   |
| Hitachi HDS721050DLE630 500GB        | 10        | 0.45%   |
| Toshiba MQ04ABF100 1TB               | 9         | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB       | 9         | 0.41%   |
| SanDisk SD8SN8U128G1001 128GB SSD    | 9         | 0.41%   |
| HGST HTS721010A9E630 1TB             | 9         | 0.41%   |
| WDC WD2500AAKX-00ERMA0 250GB         | 8         | 0.36%   |
| Unknown Y032V  32GB                  | 8         | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 8         | 0.36%   |
| Samsung MZNTY128HDHP-000L1 128GB SSD | 8         | 0.36%   |
| Hitachi HDS721050CLA362 500GB        | 8         | 0.36%   |
| Crucial CT250MX500SSD1 250GB         | 8         | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB             | 7         | 0.32%   |
| Unknown SD16G  16GB                  | 7         | 0.32%   |
| Toshiba DT01ACA200 2TB               | 7         | 0.32%   |
| Seagate ST2000DM008-2FR102 2TB       | 7         | 0.32%   |
| SanDisk SSD PLUS 240GB               | 7         | 0.32%   |
| SanDisk SD8SBAT128G1122 128GB SSD    | 7         | 0.32%   |
| Kingston SA400S37480G 480GB SSD      | 7         | 0.32%   |
| Crucial CT240BX500SSD1 240GB         | 7         | 0.32%   |
| Unknown MMC Card  32GB               | 6         | 0.27%   |
| Seagate ST4000DM004-2CV104 4TB       | 6         | 0.27%   |
| Seagate ST2000DM001-1ER164 2TB       | 6         | 0.27%   |
| Samsung SSD 970 EVO 500GB            | 6         | 0.27%   |
| Kingston SUV400S37120G 120GB SSD     | 6         | 0.27%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 5         | 0.23%   |
| Unknown SL16G  16GB                  | 5         | 0.23%   |
| Toshiba MQ01ABF050 500GB             | 5         | 0.23%   |
| Toshiba DT01ACA300 3TB               | 5         | 0.23%   |
| Samsung SSD 980 PRO 1TB              | 5         | 0.23%   |
| Samsung SSD 970 EVO 1TB              | 5         | 0.23%   |
| Samsung SSD 840 PRO Series 256GB     | 5         | 0.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 249       | 343    | 35.02%  |
| WDC                 | 199       | 303    | 27.99%  |
| Toshiba             | 94        | 132    | 13.22%  |
| Hitachi             | 67        | 70     | 9.42%   |
| HGST                | 30        | 37     | 4.22%   |
| SABRENT             | 22        | 22     | 3.09%   |
| Samsung Electronics | 18        | 20     | 2.53%   |
| Fujitsu             | 10        | 14     | 1.41%   |
| MAXTOR              | 6         | 6      | 0.84%   |
| Unknown             | 3         | 3      | 0.42%   |
| JMicron             | 2         | 2      | 0.28%   |
| Hewlett-Packard     | 2         | 4      | 0.28%   |
| Apple               | 2         | 2      | 0.28%   |
| USB3.0              | 1         | 1      | 0.14%   |
| SILICONMOTION       | 1         | 1      | 0.14%   |
| NAS                 | 1         | 5      | 0.14%   |
| MaxDigital          | 1         | 2      | 0.14%   |
| MARSHAL             | 1         | 1      | 0.14%   |
| IBM-ESXS            | 1         | 2      | 0.14%   |
| 128MB               | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 177       | 222    | 24.76%  |
| Kingston            | 99        | 116    | 13.85%  |
| Apple               | 72        | 76     | 10.07%  |
| Crucial             | 70        | 78     | 9.79%   |
| SanDisk             | 48        | 56     | 6.71%   |
| A-DATA Technology   | 28        | 32     | 3.92%   |
| WDC                 | 27        | 34     | 3.78%   |
| Netac               | 20        | 24     | 2.8%    |
| Intel               | 17        | 18     | 2.38%   |
| China               | 15        | 15     | 2.1%    |
| SK Hynix            | 11        | 13     | 1.54%   |
| Transcend           | 10        | 11     | 1.4%    |
| Micron Technology   | 10        | 10     | 1.4%    |
| PNY                 | 9         | 9      | 1.26%   |
| Toshiba             | 8         | 10     | 1.12%   |
| SPCC                | 8         | 8      | 1.12%   |
| Patriot             | 6         | 6      | 0.84%   |
| LITEON              | 6         | 6      | 0.84%   |
| OCZ                 | 5         | 5      | 0.7%    |
| Unknown             | 4         | 4      | 0.56%   |
| Team                | 4         | 4      | 0.56%   |
| Seagate             | 4         | 4      | 0.56%   |
| Mushkin             | 4         | 4      | 0.56%   |
| Lexar               | 4         | 5      | 0.56%   |
| Intenso             | 4         | 4      | 0.56%   |
| PLEXTOR             | 3         | 5      | 0.42%   |
| LITEONIT            | 3         | 3      | 0.42%   |
| JMicron             | 3         | 3      | 0.42%   |
| Apacer              | 3         | 3      | 0.42%   |
| ZTC                 | 2         | 4      | 0.28%   |
| Hajaan              | 2         | 2      | 0.28%   |
| GOODRAM             | 2         | 3      | 0.28%   |
| Xinhaike            | 1         | 1      | 0.14%   |
| Union Memory        | 1         | 1      | 0.14%   |
| TrueNAS             | 1         | 1      | 0.14%   |
| TrekStor            | 1         | 1      | 0.14%   |
| T-FORCE             | 1         | 1      | 0.14%   |
| RDM-II              | 1         | 1      | 0.14%   |
| PNY USB             | 1         | 1      | 0.14%   |
| Pioneer             | 1         | 1      | 0.14%   |
| MyDigitalSSD        | 1         | 1      | 0.14%   |
| MAXTOR              | 1         | 4      | 0.14%   |
| Maximus             | 1         | 1      | 0.14%   |
| Lenovo              | 1         | 1      | 0.14%   |
| LDLC                | 1         | 1      | 0.14%   |
| KingSpec            | 1         | 1      | 0.14%   |
| KingDian            | 1         | 1      | 0.14%   |
| KING                | 1         | 1      | 0.14%   |
| JAMESDONKEY         | 1         | 1      | 0.14%   |
| Hikvision           | 1         | 1      | 0.14%   |
| Gigabyte Technology | 1         | 1      | 0.14%   |
| FORESEE             | 1         | 1      | 0.14%   |
| DREVO               | 1         | 1      | 0.14%   |
| DOGFISH             | 1         | 1      | 0.14%   |
| Corsair             | 1         | 1      | 0.14%   |
| ASUS-PHISON         | 1         | 1      | 0.14%   |
| AMD                 | 1         | 2      | 0.14%   |
| 2-Power             | 1         | 1      | 0.14%   |
| Unknown             | 1         | 1      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 657       | 828    | 34.8%   |
| HDD     | 614       | 971    | 32.52%  |
| NVMe    | 477       | 577    | 25.26%  |
| MMC     | 120       | 150    | 6.36%   |
| Unknown | 20        | 31     | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1035      | 1727   | 60.67%  |
| NVMe | 477       | 577    | 27.96%  |
| MMC  | 120       | 150    | 7.03%   |
| SAS  | 74        | 103    | 4.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 804       | 1069   | 61.23%  |
| 0.51-1.0    | 335       | 415    | 25.51%  |
| 1.01-2.0    | 92        | 130    | 7.01%   |
| 3.01-4.0    | 36        | 75     | 2.74%   |
| 4.01-10.0   | 21        | 48     | 1.6%    |
| 2.01-3.0    | 17        | 25     | 1.29%   |
| 10.01-20.0  | 7         | 33     | 0.53%   |
| 50.01-100.0 | 1         | 4      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 428       | 28.23%  |
| Unknown        | 271       | 17.88%  |
| 251-500        | 265       | 17.48%  |
| 501-1000       | 132       | 8.71%   |
| 1-20           | 129       | 8.51%   |
| 1001-2000      | 87        | 5.74%   |
| More than 3000 | 78        | 5.15%   |
| 51-100         | 60        | 3.96%   |
| 21-50          | 40        | 2.64%   |
| 2001-3000      | 26        | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 627       | 40.98%  |
| Unknown        | 271       | 17.71%  |
| 101-250        | 148       | 9.67%   |
| 21-50          | 122       | 7.97%   |
| 51-100         | 115       | 7.52%   |
| 251-500        | 83        | 5.42%   |
| 501-1000       | 68        | 4.44%   |
| 1001-2000      | 37        | 2.42%   |
| More than 3000 | 33        | 2.16%   |
| 2001-3000      | 17        | 1.11%   |
| 0              | 9         | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB     | 14        | 14     | 6.76%   |
| Seagate ST500DM002-1BD142 500GB  | 7         | 7      | 3.38%   |
| Hitachi HDS721050DLE630 500GB    | 5         | 5      | 2.42%   |
| Seagate ST1000DM003-9YN162 1TB   | 4         | 4      | 1.93%   |
| Kingston SV300S37A120G 120GB SSD | 4         | 4      | 1.93%   |
| WDC WD20EARS-00MVWB0 2TB         | 3         | 3      | 1.45%   |
| Hitachi HTS547575A9E384 752GB    | 3         | 3      | 1.45%   |
| WDC WD10JPVX-22JC3T0 1TB         | 2         | 2      | 0.97%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 2      | 0.97%   |
| Toshiba MQ01ABF050 500GB         | 2         | 2      | 0.97%   |
| Seagate ST500LT012-9WS142 500GB  | 2         | 2      | 0.97%   |
| Seagate ST3500418AS 500GB        | 2         | 2      | 0.97%   |
| Seagate ST3320613AS 320GB        | 2         | 2      | 0.97%   |
| Seagate ST3250310AS 250GB        | 2         | 2      | 0.97%   |
| Seagate ST3160813AS 160GB        | 2         | 2      | 0.97%   |
| Seagate ST31000528AS 1TB         | 2         | 2      | 0.97%   |
| Intel SSDSC2KW120H6 120GB        | 2         | 2      | 0.97%   |
| Intel SSDPEKKW128G7 128GB        | 2         | 3      | 0.97%   |
| Hitachi HTS542516K9SA00 160GB    | 2         | 2      | 0.97%   |
| Hitachi HDS721050CLA362 500GB    | 2         | 2      | 0.97%   |
| HGST HTS545050A7E680 500GB       | 2         | 2      | 0.97%   |
| Crucial CT275MX300SSD1 275GB     | 2         | 2      | 0.97%   |
| Crucial CT128MX100SSD1 128GB     | 2         | 2      | 0.97%   |
| WDC WD7500BPVX-22JC3T0 752GB     | 1         | 1      | 0.48%   |
| WDC WD7500BPVT-80HXZT3 752GB     | 1         | 1      | 0.48%   |
| WDC WD6400BPVT-22HXZT3 640GB     | 1         | 1      | 0.48%   |
| WDC WD6400AAKS-22A7B0 640GB      | 1         | 1      | 0.48%   |
| WDC WD5003ABYX-18WERA0 500GB     | 1         | 2      | 0.48%   |
| WDC WD5002AALX-00J37A0 500GB     | 1         | 1      | 0.48%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 1         | 1      | 0.48%   |
| WDC WD5000AAKX-00U6AA0 500GB     | 1         | 1      | 0.48%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1         | 1      | 0.48%   |
| WDC WD5000AAKS-22V1A0 500GB      | 1         | 1      | 0.48%   |
| WDC WD5000AAJS-22A8B0 500GB      | 1         | 1      | 0.48%   |
| WDC WD40EFZX-68AWUN0 4TB         | 1         | 6      | 0.48%   |
| WDC WD400BB-00DEA0 40GB          | 1         | 1      | 0.48%   |
| WDC WD3200BEKT-75PVMT1 320GB     | 1         | 1      | 0.48%   |
| WDC WD3200AAJS-22B4A0 320GB      | 1         | 1      | 0.48%   |
| WDC WD3200AAJS-08L7A0 320GB      | 1         | 1      | 0.48%   |
| WDC WD3200AAJS-00L7A0 320GB      | 1         | 1      | 0.48%   |
| WDC WD30EZRX-00AZ6B0 3TB         | 1         | 1      | 0.48%   |
| WDC WD2500AAKX-00ERMA0 250GB     | 1         | 1      | 0.48%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1         | 2      | 0.48%   |
| WDC WD20EARX-00PASB0 2TB         | 1         | 1      | 0.48%   |
| WDC WD1600AAJS-00L7A0 160GB      | 1         | 1      | 0.48%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1      | 0.48%   |
| WDC WD10JPVX-60JC3T0 1TB         | 1         | 1      | 0.48%   |
| WDC WD10JPVT-75A1YT0 1TB         | 1         | 1      | 0.48%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1         | 1      | 0.48%   |
| WDC WD10EARS-00Y5B1 1TB          | 1         | 1      | 0.48%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1         | 1      | 0.48%   |
| WDC WD1001FALS-75J7B0 1TB        | 1         | 1      | 0.48%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 0.48%   |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 0.48%   |
| Toshiba MQ01ABD050 500GB         | 1         | 1      | 0.48%   |
| Toshiba MK2565GSX 250GB          | 1         | 1      | 0.48%   |
| Toshiba DT01ACA100 1TB           | 1         | 1      | 0.48%   |
| Toshiba DT01ACA050 500GB         | 1         | 1      | 0.48%   |
| SK Hynix SH920 mSATA 128GB SSD   | 1         | 1      | 0.48%   |
| SK Hynix PC401 NVMe 512GB        | 1         | 6      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 58     | 25%     |
| WDC                 | 50        | 57     | 24.51%  |
| Hitachi             | 30        | 30     | 14.71%  |
| Intel               | 12        | 15     | 5.88%   |
| Samsung Electronics | 11        | 12     | 5.39%   |
| Toshiba             | 8         | 8      | 3.92%   |
| Kingston            | 6         | 6      | 2.94%   |
| A-DATA Technology   | 6         | 7      | 2.94%   |
| SK Hynix            | 5         | 10     | 2.45%   |
| HGST                | 5         | 5      | 2.45%   |
| Micron Technology   | 4         | 4      | 1.96%   |
| Crucial             | 4         | 4      | 1.96%   |
| SanDisk             | 3         | 3      | 1.47%   |
| MAXTOR              | 2         | 2      | 0.98%   |
| PNY                 | 1         | 1      | 0.49%   |
| LITEONIT            | 1         | 1      | 0.49%   |
| LITEON              | 1         | 1      | 0.49%   |
| KingDian            | 1         | 1      | 0.49%   |
| JMicron             | 1         | 1      | 0.49%   |
| Fujitsu             | 1         | 1      | 0.49%   |
| China               | 1         | 1      | 0.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 58     | 33.33%  |
| WDC                 | 50        | 57     | 32.68%  |
| Hitachi             | 30        | 30     | 19.61%  |
| Toshiba             | 8         | 8      | 5.23%   |
| Samsung Electronics | 6         | 6      | 3.92%   |
| HGST                | 5         | 5      | 3.27%   |
| MAXTOR              | 2         | 2      | 1.31%   |
| Fujitsu             | 1         | 1      | 0.65%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 145       | 167    | 73.98%  |
| SSD  | 42        | 45     | 21.43%  |
| NVMe | 9         | 16     | 4.59%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1         | 1      | 33.33%  |
| Seagate ST3500830AS 500GB        | 1         | 1      | 33.33%  |
| HGST HDN724040ALE640 4TB         | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| HGST    | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1131      | 1782   | 68.8%   |
| Detected | 320       | 544    | 19.46%  |
| Malfunc  | 190       | 228    | 11.56%  |
| Failed   | 3         | 3      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 857       | 49.54%  |
| Samsung Electronics              | 249       | 14.39%  |
| AMD                              | 231       | 13.35%  |
| Apple                            | 77        | 4.45%   |
| Sandisk                          | 58        | 3.35%   |
| SK Hynix                         | 26        | 1.5%    |
| Marvell Technology Group         | 26        | 1.5%    |
| JMicron Technology               | 18        | 1.04%   |
| Phison Electronics               | 17        | 0.98%   |
| ASMedia Technology               | 17        | 0.98%   |
| Toshiba America Info Systems     | 15        | 0.87%   |
| Micron/Crucial Technology        | 15        | 0.87%   |
| Micron Technology                | 14        | 0.81%   |
| Kingston Technology Company      | 14        | 0.81%   |
| KIOXIA                           | 13        | 0.75%   |
| VIA Technologies                 | 12        | 0.69%   |
| Nvidia                           | 12        | 0.69%   |
| ADATA Technology                 | 12        | 0.69%   |
| Silicon Motion                   | 11        | 0.64%   |
| LSI Logic / Symbios Logic        | 9         | 0.52%   |
| Broadcom / LSI                   | 6         | 0.35%   |
| Union Memory (Shenzhen)          | 3         | 0.17%   |
| Lenovo                           | 3         | 0.17%   |
| Solid State Storage Technology   | 2         | 0.12%   |
| Seagate Technology               | 2         | 0.12%   |
| Lite-On Technology               | 2         | 0.12%   |
| Adaptec                          | 2         | 0.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| Silicon Image                    | 1         | 0.06%   |
| Realtek Semiconductor            | 1         | 0.06%   |
| OCZ Technology Group             | 1         | 0.06%   |
| Integrated Technology Express    | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Biwin Storage Technology         | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 171       | 8.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 129       | 6.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 88        | 4.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 79        | 4.02%   |
| Apple S1X NVMe Controller                                                               | 75        | 3.81%   |
| Samsung Electronics SATA controller                                                     | 70        | 3.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 60        | 3.05%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 44        | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 44        | 2.24%   |
| AMD 400 Series Chipset SATA Controller                                                  | 35        | 1.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 29        | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 29        | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 26        | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 25        | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 25        | 1.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 25        | 1.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 24        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 21        | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 21        | 1.07%   |
| Samsung NVMe SSD Controller 980                                                         | 20        | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 20        | 1.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 20        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 20        | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 19        | 0.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 19        | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 18        | 0.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 18        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 18        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 17        | 0.86%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 16        | 0.81%   |
| Intel SATA Controller [RAID mode]                                                       | 16        | 0.81%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 15        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 15        | 0.76%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 15        | 0.76%   |
| Micron Non-Volatile memory controller                                                   | 14        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 0.71%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14        | 0.71%   |
| KIOXIA Non-Volatile memory controller                                                   | 13        | 0.66%   |
| Intel SSD 660P Series                                                                   | 13        | 0.66%   |
| Intel SSD 600P Series                                                                   | 12        | 0.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 12        | 0.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 11        | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 11        | 0.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 10        | 0.51%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 10        | 0.51%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 10        | 0.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10        | 0.51%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 10        | 0.51%   |
| AMD FCH SATA Controller D                                                               | 10        | 0.51%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10        | 0.51%   |
| SK Hynix Gold P31 SSD                                                                   | 9         | 0.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 9         | 0.46%   |
| Phison E12 NVMe Controller                                                              | 9         | 0.46%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 9         | 0.46%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 8         | 0.41%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8         | 0.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 8         | 0.41%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8         | 0.41%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 8         | 0.41%   |
| SK Hynix BC511                                                                          | 7         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 994       | 56.77%  |
| NVMe | 477       | 27.24%  |
| IDE  | 188       | 10.74%  |
| RAID | 78        | 4.45%   |
| SAS  | 11        | 0.63%   |
| SCSI | 3         | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1196      | 79.52%  |
| AMD          | 272       | 18.09%  |
| ARM          | 35        | 2.33%   |
| CentaurHauls | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5250U CPU @ 1.60GHz             | 141       | 9.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 68        | 4.52%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 49        | 3.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 28        | 1.86%   |
| ARM Processor                                 | 26        | 1.73%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 22        | 1.46%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 21        | 1.4%    |
| Intel Celeron CPU 3865U @ 1.80GHz             | 17        | 1.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 16        | 1.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 1.06%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 14        | 0.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 0.86%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 12        | 0.8%    |
| AMD Ryzen 5 3600 6-Core Processor             | 12        | 0.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 0.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 0.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 11        | 0.73%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 0.66%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 10        | 0.66%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 10        | 0.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 9         | 0.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 0.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.53%   |
| Intel Core i5-2300 CPU @ 2.80GHz              | 8         | 0.53%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 8         | 0.53%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 0.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 0.47%   |
| Intel Core i3-3210 CPU @ 3.20GHz              | 7         | 0.47%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 7         | 0.47%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 0.47%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 7         | 0.47%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 6         | 0.4%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 6         | 0.4%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 0.4%    |
| Intel Core i5-6400 CPU @ 2.70GHz              | 6         | 0.4%    |
| Intel Core i5-4570 CPU @ 3.20GHz              | 6         | 0.4%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 0.4%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 6         | 0.4%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 6         | 0.4%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 6         | 0.4%    |
| Intel Atom CPU N270 @ 1.60GHz                 | 6         | 0.4%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 6         | 0.4%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.33%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 5         | 0.33%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 5         | 0.33%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.33%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 5         | 0.33%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 5         | 0.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.33%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 0.33%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 5         | 0.33%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 5         | 0.33%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 5         | 0.33%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.33%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 406       | 26.99%  |
| Intel Core i7           | 217       | 14.43%  |
| Other                   | 131       | 8.71%   |
| Intel Core i3           | 113       | 7.51%   |
| Intel Celeron           | 111       | 7.38%   |
| AMD Ryzen 5             | 84        | 5.59%   |
| Intel Pentium           | 74        | 4.92%   |
| Intel Core 2 Duo        | 58        | 3.86%   |
| AMD Ryzen 7             | 44        | 2.93%   |
| Intel Xeon              | 34        | 2.26%   |
| Intel Atom              | 20        | 1.33%   |
| AMD Ryzen 9             | 18        | 1.2%    |
| AMD FX                  | 14        | 0.93%   |
| Intel Pentium Dual-Core | 13        | 0.86%   |
| AMD Ryzen 3             | 13        | 0.86%   |
| Intel Core 2 Quad       | 10        | 0.66%   |
| AMD Ryzen 7 PRO         | 10        | 0.66%   |
| AMD Ryzen Threadripper  | 9         | 0.6%    |
| Intel Core 2            | 8         | 0.53%   |
| AMD A8                  | 7         | 0.47%   |
| AMD A10                 | 7         | 0.47%   |
| AMD Phenom II X4        | 6         | 0.4%    |
| AMD Athlon              | 6         | 0.4%    |
| AMD A6                  | 6         | 0.4%    |
| Intel Pentium M         | 5         | 0.33%   |
| Intel Pentium Gold      | 5         | 0.33%   |
| Intel Pentium 4         | 5         | 0.33%   |
| AMD A4                  | 5         | 0.33%   |
| Intel Genuine           | 4         | 0.27%   |
| Intel Core i9           | 4         | 0.27%   |
| Intel Celeron M         | 4         | 0.27%   |
| AMD E                   | 4         | 0.27%   |
| Intel Pentium Dual      | 3         | 0.2%    |
| AMD EPYC                | 3         | 0.2%    |
| AMD Athlon X4           | 3         | 0.2%    |
| AMD Athlon II X2        | 3         | 0.2%    |
| Intel Core m7           | 2         | 0.13%   |
| Intel Core m3           | 2         | 0.13%   |
| AMD Turion 64 Mobile    | 2         | 0.13%   |
| AMD Phenom II X3        | 2         | 0.13%   |
| AMD Opteron             | 2         | 0.13%   |
| AMD E1                  | 2         | 0.13%   |
| AMD C-60                | 2         | 0.13%   |
| AMD Athlon XP           | 2         | 0.13%   |
| AMD Athlon 64 X2        | 2         | 0.13%   |
| AMD A12                 | 2         | 0.13%   |
| Intel Xeon Silver       | 1         | 0.07%   |
| Intel Pentium Silver    | 1         | 0.07%   |
| CentaurHauls VIA Eden   | 1         | 0.07%   |
| ARM BCM                 | 1         | 0.07%   |
| ARM ARMv7               | 1         | 0.07%   |
| ARM Allwinner           | 1         | 0.07%   |
| ARM AArch64             | 1         | 0.07%   |
| AMD Sempron             | 1         | 0.07%   |
| AMD PRO A8              | 1         | 0.07%   |
| AMD Phenom II X6        | 1         | 0.07%   |
| AMD GX                  | 1         | 0.07%   |
| AMD C-50                | 1         | 0.07%   |
| AMD C-30                | 1         | 0.07%   |
| AMD Athlon II X4        | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 712       | 47.34%  |
| 4      | 509       | 33.84%  |
| 8      | 101       | 6.72%   |
| 6      | 100       | 6.65%   |
| 1      | 41        | 2.73%   |
| 12     | 15        | 1%      |
| 16     | 13        | 0.86%   |
| 3      | 4         | 0.27%   |
| 24     | 3         | 0.2%    |
| 32     | 2         | 0.13%   |
| 44     | 1         | 0.07%   |
| 28     | 1         | 0.07%   |
| 20     | 1         | 0.07%   |
| 14     | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1485      | 98.74%  |
| 2      | 19        | 1.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 985       | 65.49%  |
| 1      | 519       | 34.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1467      | 97.54%  |
| 32-bit         | 23        | 1.53%   |
| Unknown        | 10        | 0.66%   |
| 64-bit         | 4         | 0.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 255       | 16.82%  |
| 0x306d4    | 161       | 10.62%  |
| 0x206a7    | 86        | 5.67%   |
| 0x306c3    | 85        | 5.61%   |
| 0x806c1    | 82        | 5.41%   |
| 0x306a9    | 75        | 4.95%   |
| 0x30678    | 54        | 3.56%   |
| 0x1067a    | 48        | 3.17%   |
| 0x806e9    | 46        | 3.03%   |
| 0x08108109 | 34        | 2.24%   |
| 0x806ec    | 30        | 1.98%   |
| 0x906ea    | 28        | 1.85%   |
| 0x406e3    | 27        | 1.78%   |
| 0x08701021 | 25        | 1.65%   |
| 0xa0655    | 23        | 1.52%   |
| 0x806ea    | 23        | 1.52%   |
| 0x506e3    | 23        | 1.52%   |
| 0x906e9    | 19        | 1.25%   |
| 0x40651    | 15        | 0.99%   |
| 0x906eb    | 14        | 0.92%   |
| 0xa0652    | 13        | 0.86%   |
| 0x20655    | 13        | 0.86%   |
| 0x706e5    | 12        | 0.79%   |
| 0x6fd      | 12        | 0.79%   |
| 0x08600106 | 11        | 0.73%   |
| 0x0800820d | 10        | 0.66%   |
| 0x506c9    | 9         | 0.59%   |
| 0x206d7    | 9         | 0.59%   |
| 0x08600104 | 9         | 0.59%   |
| 0x806eb    | 8         | 0.53%   |
| 0x6fb      | 8         | 0.53%   |
| 0x406c4    | 8         | 0.53%   |
| 0x106c2    | 8         | 0.53%   |
| 0x06003106 | 8         | 0.53%   |
| 0x906ed    | 7         | 0.46%   |
| 0x306f2    | 7         | 0.46%   |
| 0x0a201009 | 7         | 0.46%   |
| 0xa0653    | 6         | 0.4%    |
| 0x6d8      | 6         | 0.4%    |
| 0x10676    | 6         | 0.4%    |
| 0x0a201016 | 6         | 0.4%    |
| 0x0600611a | 6         | 0.4%    |
| 0x010000c8 | 6         | 0.4%    |
| 0x6f6      | 5         | 0.33%   |
| 0x406c3    | 5         | 0.33%   |
| 0x206c2    | 5         | 0.33%   |
| 0x0a50000c | 5         | 0.33%   |
| 0x08608103 | 5         | 0.33%   |
| 0x08108102 | 5         | 0.33%   |
| 0x0810100b | 5         | 0.33%   |
| 0x010000b6 | 5         | 0.33%   |
| 0xa0671    | 4         | 0.26%   |
| 0x706a8    | 4         | 0.26%   |
| 0x106e5    | 4         | 0.26%   |
| 0x0a50000b | 4         | 0.26%   |
| 0x08600103 | 4         | 0.26%   |
| 0x08101016 | 4         | 0.26%   |
| 0x08001138 | 4         | 0.26%   |
| 0x08001137 | 4         | 0.26%   |
| 0x06006705 | 4         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 217       | 14.43%  |
| Broadwell     | 165       | 10.97%  |
| Haswell       | 130       | 8.64%   |
| SandyBridge   | 105       | 6.98%   |
| IvyBridge     | 95        | 6.32%   |
| TigerLake     | 91        | 6.05%   |
| Silvermont    | 76        | 5.05%   |
| Zen 2         | 67        | 4.45%   |
| Skylake       | 65        | 4.32%   |
| Penryn        | 63        | 4.19%   |
| Zen+          | 61        | 4.06%   |
| Unknown       | 47        | 3.13%   |
| CometLake     | 46        | 3.06%   |
| Core          | 37        | 2.46%   |
| Westmere      | 31        | 2.06%   |
| Zen 3         | 26        | 1.73%   |
| Zen           | 25        | 1.66%   |
| IceLake       | 16        | 1.06%   |
| K10           | 15        | 1%      |
| Piledriver    | 14        | 0.93%   |
| Excavator     | 13        | 0.86%   |
| Steamroller   | 11        | 0.73%   |
| Nehalem       | 11        | 0.73%   |
| Goldmont      | 11        | 0.73%   |
| P6            | 10        | 0.66%   |
| Bonnell       | 10        | 0.66%   |
| Bobcat        | 8         | 0.53%   |
| Goldmont plus | 7         | 0.47%   |
| NetBurst      | 6         | 0.4%    |
| K8 Hammer     | 6         | 0.4%    |
| Puma          | 5         | 0.33%   |
| Bulldozer     | 5         | 0.33%   |
| Jaguar        | 4         | 0.27%   |
| K10 Llano     | 3         | 0.2%    |
| K6            | 2         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 966       | 58.37%  |
| Nvidia                           | 378       | 22.84%  |
| AMD                              | 288       | 17.4%   |
| ASPEED Technology                | 12        | 0.73%   |
| Matrox Electronics Systems       | 8         | 0.48%   |
| VIA Technologies                 | 2         | 0.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 6000                                                                   | 142       | 8.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 88        | 5.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 64        | 3.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 59        | 3.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 50        | 2.94%   |
| AMD Picasso                                                                              | 45        | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 42        | 2.47%   |
| Intel UHD Graphics 620                                                                   | 32        | 1.88%   |
| Intel HD Graphics 620                                                                    | 30        | 1.77%   |
| AMD Renoir                                                                               | 30        | 1.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 29        | 1.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 1.53%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 25        | 1.47%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 24        | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 1.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 1.24%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 20        | 1.18%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 20        | 1.18%   |
| Intel HD Graphics 5500                                                                   | 20        | 1.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 1.18%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 18        | 1.06%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 18        | 1.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 16        | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 16        | 0.94%   |
| Intel HD Graphics 630                                                                    | 16        | 0.94%   |
| Intel HD Graphics 530                                                                    | 15        | 0.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 0.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 15        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 0.88%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 15        | 0.88%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 14        | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 13        | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 0.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 13        | 0.77%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 12        | 0.71%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 12        | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12        | 0.71%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 12        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 0.65%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 11        | 0.65%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 10        | 0.59%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.53%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 9         | 0.53%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 9         | 0.53%   |
| AMD Cezanne                                                                              | 9         | 0.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.41%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 7         | 0.41%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.41%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 7         | 0.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 0.41%   |
| Nvidia TU117M                                                                            | 6         | 0.35%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 6         | 0.35%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 6         | 0.35%   |
| AMD Lucienne                                                                             | 6         | 0.35%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 6         | 0.35%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.29%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 800       | 53.05%  |
| 1 x Nvidia         | 238       | 15.78%  |
| 1 x AMD            | 235       | 15.58%  |
| Intel + Nvidia     | 122       | 8.09%   |
| Other              | 37        | 2.45%   |
| Intel + AMD        | 25        | 1.66%   |
| AMD + Nvidia       | 15        | 0.99%   |
| 2 x AMD            | 11        | 0.73%   |
| 1 x ASPEED         | 11        | 0.73%   |
| 1 x Matrox         | 7         | 0.46%   |
| 1 x VIA            | 2         | 0.13%   |
| Intel + 2 x Nvidia | 2         | 0.13%   |
| 1 x SiS            | 1         | 0.07%   |
| Nvidia + Matrox    | 1         | 0.07%   |
| AMD + ASPEED       | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1069      | 70.79%  |
| Unknown     | 292       | 19.34%  |
| Proprietary | 149       | 9.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1170      | 77.28%  |
| 0.01-0.5   | 93        | 6.14%   |
| 1.01-2.0   | 70        | 4.62%   |
| 3.01-4.0   | 59        | 3.9%    |
| 0.51-1.0   | 54        | 3.57%   |
| 7.01-8.0   | 38        | 2.51%   |
| 5.01-6.0   | 17        | 1.12%   |
| 2.01-3.0   | 5         | 0.33%   |
| 8.01-16.0  | 5         | 0.33%   |
| 16.01-24.0 | 2         | 0.13%   |
| 24.01-32.0 | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 189       | 13.78%  |
| Apple                   | 165       | 12.03%  |
| BOE                     | 131       | 9.55%   |
| Samsung Electronics     | 115       | 8.38%   |
| Chimei Innolux          | 105       | 7.65%   |
| LG Display              | 91        | 6.63%   |
| Dell                    | 67        | 4.88%   |
| Goldstar                | 53        | 3.86%   |
| Ancor Communications    | 37        | 2.7%    |
| Hewlett-Packard         | 35        | 2.55%   |
| Acer                    | 35        | 2.55%   |
| BenQ                    | 33        | 2.41%   |
| Lenovo                  | 31        | 2.26%   |
| Sharp                   | 25        | 1.82%   |
| Philips                 | 24        | 1.75%   |
| AOC                     | 23        | 1.68%   |
| Unknown                 | 17        | 1.24%   |
| InfoVision              | 17        | 1.24%   |
| ViewSonic               | 16        | 1.17%   |
| NEC Computers           | 15        | 1.09%   |
| Eizo                    | 13        | 0.95%   |
| PANDA                   | 12        | 0.87%   |
| Chi Mei Optoelectronics | 12        | 0.87%   |
| ASUSTek Computer        | 9         | 0.66%   |
| Iiyama                  | 8         | 0.58%   |
| Sony                    | 6         | 0.44%   |
| LG Philips              | 6         | 0.44%   |
| HannStar                | 6         | 0.44%   |
| Vestel Elektronik       | 4         | 0.29%   |
| LG Electronics          | 4         | 0.29%   |
| MSI                     | 3         | 0.22%   |
| Fujitsu Siemens         | 3         | 0.22%   |
| CSO                     | 3         | 0.22%   |
| CPT                     | 3         | 0.22%   |
| ___                     | 2         | 0.15%   |
| Vizio                   | 2         | 0.15%   |
| ONN                     | 2         | 0.15%   |
| MStar                   | 2         | 0.15%   |
| ITL                     | 2         | 0.15%   |
| Hitachi                 | 2         | 0.15%   |
| Unknown                 | 2         | 0.15%   |
| WTC                     | 1         | 0.07%   |
| VMO                     | 1         | 0.07%   |
| TXD                     | 1         | 0.07%   |
| TPU                     | 1         | 0.07%   |
| Toshiba                 | 1         | 0.07%   |
| TEO                     | 1         | 0.07%   |
| TCL                     | 1         | 0.07%   |
| SGT                     | 1         | 0.07%   |
| Sceptre Tech            | 1         | 0.07%   |
| Sangyo                  | 1         | 0.07%   |
| RIC                     | 1         | 0.07%   |
| Quanta Display          | 1         | 0.07%   |
| Prestigio               | 1         | 0.07%   |
| PPC                     | 1         | 0.07%   |
| Panasonic               | 1         | 0.07%   |
| Onkyo                   | 1         | 0.07%   |
| ODH                     | 1         | 0.07%   |
| NCS                     | 1         | 0.07%   |
| Mitsubishi              | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch            | 56        | 4%      |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 40        | 2.86%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 40        | 2.86%   |
| Apple Color LCD APP9CF2 1366x768 260x140mm 11.6-inch                      | 35        | 2.5%    |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 30        | 2.14%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 23        | 1.64%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 12        | 0.86%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 10        | 0.71%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 10        | 0.71%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch            | 10        | 0.71%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch             | 10        | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 9         | 0.64%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                    | 7         | 0.5%    |
| InfoVision LCD Monitor IVO0533 1366x768 293x164mm 13.2-inch               | 7         | 0.5%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 7         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 6         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 6         | 0.43%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 5         | 0.36%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch            | 5         | 0.36%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 5         | 0.36%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 4         | 0.29%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 4         | 0.29%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                   | 4         | 0.29%   |
| NEC Computers LCD1550V NEC65C6 1024x768 304x228mm 15.0-inch               | 4         | 0.29%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch               | 4         | 0.29%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 4         | 0.29%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch               | 4         | 0.29%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 4         | 0.29%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                         | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 4         | 0.29%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                     | 4         | 0.29%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 4         | 0.29%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 4         | 0.29%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch    | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch      | 3         | 0.21%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 3         | 0.21%   |
| Philips 220WS PHL0851 1680x1050 474x296mm 22.0-inch                       | 3         | 0.21%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 3         | 0.21%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 3         | 0.21%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 3         | 0.21%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 3         | 0.21%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 3         | 0.21%   |
| Dell P2415Q DELA0BE 2048x1280 530x300mm 24.0-inch                         | 3         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch          | 3         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch          | 3         | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 3         | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 3         | 0.21%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 3         | 0.21%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                     | 3         | 0.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch             | 3         | 0.21%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch             | 3         | 0.21%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 3         | 0.21%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch              | 3         | 0.21%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                         | 3         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 545       | 40.92%  |
| 1366x768 (WXGA)    | 295       | 22.15%  |
| 1440x900 (WXGA+)   | 85        | 6.38%   |
| 3840x2160 (4K)     | 60        | 4.5%    |
| 1280x1024 (SXGA)   | 51        | 3.83%   |
| 2560x1440 (QHD)    | 49        | 3.68%   |
| 1600x900 (HD+)     | 36        | 2.7%    |
| 1920x1200 (WUXGA)  | 34        | 2.55%   |
| 1680x1050 (WSXGA+) | 29        | 2.18%   |
| 1280x800 (WXGA)    | 28        | 2.1%    |
| 1024x768 (XGA)     | 15        | 1.13%   |
| Unknown            | 15        | 1.13%   |
| 2288x1287          | 12        | 0.9%    |
| 1024x600           | 11        | 0.83%   |
| 2560x1080          | 8         | 0.6%    |
| 3440x1440          | 7         | 0.53%   |
| 3840x1080          | 6         | 0.45%   |
| 2880x1800          | 6         | 0.45%   |
| 1600x1200          | 6         | 0.45%   |
| 2560x1600          | 5         | 0.38%   |
| 1920x540           | 5         | 0.38%   |
| 2160x1440          | 4         | 0.3%    |
| 4480x1440          | 2         | 0.15%   |
| 3200x1800 (QHD+)   | 2         | 0.15%   |
| 1360x768           | 2         | 0.15%   |
| 7680x4320          | 1         | 0.08%   |
| 6400x2160          | 1         | 0.08%   |
| 5760x1080          | 1         | 0.08%   |
| 5360x1440          | 1         | 0.08%   |
| 5120x1080          | 1         | 0.08%   |
| 3840x2400          | 1         | 0.08%   |
| 3360x1080          | 1         | 0.08%   |
| 3360x1050          | 1         | 0.08%   |
| 2880x1920          | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2560x1024          | 1         | 0.08%   |
| 2256x1504          | 1         | 0.08%   |
| 1800x1200          | 1         | 0.08%   |
| 1792x768           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 260       | 19.17%  |
| 15      | 235       | 17.33%  |
| 11      | 138       | 10.18%  |
| 14      | 93        | 6.86%   |
| 24      | 90        | 6.64%   |
| 23      | 71        | 5.24%   |
| 27      | 67        | 4.94%   |
| 21      | 59        | 4.35%   |
| 17      | 56        | 4.13%   |
| 12      | 40        | 2.95%   |
| Unknown | 40        | 2.95%   |
| 19      | 30        | 2.21%   |
| 22      | 23        | 1.7%    |
| 18      | 22        | 1.62%   |
| 31      | 19        | 1.4%    |
| 20      | 13        | 0.96%   |
| 142     | 12        | 0.88%   |
| 34      | 12        | 0.88%   |
| 10      | 10        | 0.74%   |
| 84      | 8         | 0.59%   |
| 72      | 7         | 0.52%   |
| 25      | 7         | 0.52%   |
| 32      | 6         | 0.44%   |
| 40      | 4         | 0.29%   |
| 28      | 4         | 0.29%   |
| 16      | 4         | 0.29%   |
| 52      | 3         | 0.22%   |
| 33      | 3         | 0.22%   |
| 65      | 2         | 0.15%   |
| 49      | 2         | 0.15%   |
| 48      | 2         | 0.15%   |
| 47      | 2         | 0.15%   |
| 46      | 2         | 0.15%   |
| 29      | 2         | 0.15%   |
| 8       | 2         | 0.15%   |
| 74      | 1         | 0.07%   |
| 55      | 1         | 0.07%   |
| 54      | 1         | 0.07%   |
| 38      | 1         | 0.07%   |
| 35      | 1         | 0.07%   |
| 26      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 424       | 31.64%  |
| 201-300        | 375       | 27.99%  |
| 501-600        | 213       | 15.9%   |
| 401-500        | 120       | 8.96%   |
| 351-400        | 61        | 4.55%   |
| Unknown        | 40        | 2.99%   |
| 601-700        | 36        | 2.69%   |
| 701-800        | 20        | 1.49%   |
| 1501-2000      | 16        | 1.19%   |
| 1001-1500      | 15        | 1.12%   |
| More than 2000 | 12        | 0.9%    |
| 801-900        | 6         | 0.45%   |
| 101-200        | 2         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 922       | 73.12%  |
| 16/10   | 184       | 14.59%  |
| 5/4     | 46        | 3.65%   |
| Unknown | 36        | 2.85%   |
| 4/3     | 26        | 2.06%   |
| 21/9    | 16        | 1.27%   |
| 3/2     | 13        | 1.03%   |
| 1.00    | 13        | 1.03%   |
| 6/5     | 3         | 0.24%   |
| 32/9    | 1         | 0.08%   |
| 1.96    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 235       | 17.41%  |
| 81-90          | 205       | 15.19%  |
| 201-250        | 192       | 14.22%  |
| 71-80          | 149       | 11.04%  |
| 51-60          | 138       | 10.22%  |
| 301-350        | 67        | 4.96%   |
| 151-200        | 64        | 4.74%   |
| 351-500        | 45        | 3.33%   |
| 141-150        | 40        | 2.96%   |
| Unknown        | 40        | 2.96%   |
| 251-300        | 39        | 2.89%   |
| 61-70          | 38        | 2.81%   |
| More than 1000 | 36        | 2.67%   |
| 121-130        | 31        | 2.3%    |
| 501-1000       | 11        | 0.81%   |
| 41-50          | 10        | 0.74%   |
| 131-140        | 4         | 0.3%    |
| 1-40           | 2         | 0.15%   |
| 111-120        | 2         | 0.15%   |
| 91-100         | 2         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 523       | 39.5%   |
| 51-100        | 361       | 27.27%  |
| 101-120       | 227       | 17.15%  |
| 161-240       | 121       | 9.14%   |
| Unknown       | 40        | 3.02%   |
| 1-50          | 35        | 2.64%   |
| More than 240 | 17        | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1032      | 68.16%  |
| 0     | 291       | 19.22%  |
| 2     | 173       | 11.43%  |
| 3     | 16        | 1.06%   |
| 4     | 2         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 696       | 34.83%  |
| Intel                             | 677       | 33.88%  |
| Qualcomm Atheros                  | 195       | 9.76%   |
| Broadcom Limited                  | 163       | 8.16%   |
| Broadcom                          | 94        | 4.7%    |
| Marvell Technology Group          | 18        | 0.9%    |
| Ralink                            | 15        | 0.75%   |
| Nvidia                            | 11        | 0.55%   |
| TP-Link                           | 10        | 0.5%    |
| Ralink Technology                 | 9         | 0.45%   |
| Standard Microsystems             | 7         | 0.35%   |
| Sierra Wireless                   | 7         | 0.35%   |
| Microsoft                         | 6         | 0.3%    |
| MEDIATEK                          | 6         | 0.3%    |
| DisplayLink                       | 6         | 0.3%    |
| Dell                              | 5         | 0.25%   |
| D-Link                            | 5         | 0.25%   |
| Qualcomm Atheros Communications   | 4         | 0.2%    |
| NetGear                           | 4         | 0.2%    |
| JMicron Technology                | 4         | 0.2%    |
| Ericsson Business Mobile Networks | 4         | 0.2%    |
| Mellanox Technologies             | 3         | 0.15%   |
| Lenovo                            | 3         | 0.15%   |
| Belkin Components                 | 3         | 0.15%   |
| ASUSTek Computer                  | 3         | 0.15%   |
| AMD                               | 3         | 0.15%   |
| Xiaomi                            | 2         | 0.1%    |
| VIA Technologies                  | 2         | 0.1%    |
| Hewlett-Packard                   | 2         | 0.1%    |
| Google                            | 2         | 0.1%    |
| Fibocom                           | 2         | 0.1%    |
| Edimax Technology                 | 2         | 0.1%    |
| Cypress Semiconductor             | 2         | 0.1%    |
| Attansic Technology               | 2         | 0.1%    |
| ASIX Electronics                  | 2         | 0.1%    |
| Aquantia                          | 2         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.05%   |
| Wilocity                          | 1         | 0.05%   |
| U-Blox                            | 1         | 0.05%   |
| STMicroelectronics                | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.05%   |
| Samsung Electronics               | 1         | 0.05%   |
| Qualcomm                          | 1         | 0.05%   |
| QLogic                            | 1         | 0.05%   |
| OPPO Electronics                  | 1         | 0.05%   |
| Microchip Technology              | 1         | 0.05%   |
| Micro Star International          | 1         | 0.05%   |
| IMC Networks                      | 1         | 0.05%   |
| IBM                               | 1         | 0.05%   |
| Huawei Technologies               | 1         | 0.05%   |
| D-Link System                     | 1         | 0.05%   |
| American Megatrends               | 1         | 0.05%   |
| ADMtek                            | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 515       | 21.91%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 142       | 6.04%   |
| Intel Wi-Fi 6 AX201                                                     | 76        | 3.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 72        | 3.06%   |
| Intel Wireless 7260                                                     | 68        | 2.89%   |
| Intel Ethernet Connection (13) I219-V                                   | 60        | 2.55%   |
| Intel Wi-Fi 6 AX200                                                     | 57        | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 54        | 2.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 53        | 2.26%   |
| Intel Wireless 8265 / 8275                                              | 53        | 2.26%   |
| Intel I211 Gigabit Network Connection                                   | 29        | 1.23%   |
| Intel Ethernet Connection (4) I219-V                                    | 29        | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 29        | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 28        | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.15%   |
| Intel Wireless 8260                                                     | 25        | 1.06%   |
| Intel Wireless 7265                                                     | 23        | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 22        | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                       | 18        | 0.77%   |
| Intel Ethernet Connection (2) I219-V                                    | 18        | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 0.72%   |
| Intel Wireless 3165                                                     | 16        | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 0.64%   |
| Intel I210 Gigabit Network Connection                                   | 14        | 0.6%    |
| Intel Ethernet Connection I217-LM                                       | 14        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                                   | 12        | 0.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 0.43%   |
| Intel Ethernet Connection I219-LM                                       | 10        | 0.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 0.43%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 0.43%   |
| Intel 82579V Gigabit Network Connection                                 | 10        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 0.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 9         | 0.38%   |
| Intel Wireless 3160                                                     | 9         | 0.38%   |
| Intel Ethernet Connection I218-LM                                       | 9         | 0.38%   |
| Intel Ethernet Connection (6) I219-V                                    | 9         | 0.38%   |
| Intel Ethernet Connection (3) I218-LM                                   | 9         | 0.38%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 8         | 0.34%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 0.34%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.34%   |
| Intel Wireless-AC 9260                                                  | 8         | 0.34%   |
| Intel Ethernet Connection I217-V                                        | 8         | 0.34%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.34%   |
| Intel Centrino Ultimate-N 6300                                          | 8         | 0.34%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 0.34%   |
| Standard Microsystems SMSC9512/9514 Fast Ethernet Adapter               | 7         | 0.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 7         | 0.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 0.3%    |
| Intel 82574L Gigabit Network Connection                                 | 7         | 0.3%    |
| Intel 82567LM-3 Gigabit Network Connection                              | 7         | 0.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                        | 7         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 519       | 48.64%  |
| Qualcomm Atheros                | 157       | 14.71%  |
| Broadcom Limited                | 153       | 14.34%  |
| Realtek Semiconductor           | 110       | 10.31%  |
| Broadcom                        | 49        | 4.59%   |
| Ralink                          | 15        | 1.41%   |
| Ralink Technology               | 9         | 0.84%   |
| TP-Link                         | 7         | 0.66%   |
| Sierra Wireless                 | 7         | 0.66%   |
| Microsoft                       | 5         | 0.47%   |
| MEDIATEK                        | 5         | 0.47%   |
| Qualcomm Atheros Communications | 4         | 0.37%   |
| NetGear                         | 4         | 0.37%   |
| D-Link                          | 4         | 0.37%   |
| Dell                            | 3         | 0.28%   |
| Belkin Components               | 3         | 0.28%   |
| ASUSTek Computer                | 3         | 0.28%   |
| Fibocom                         | 2         | 0.19%   |
| Edimax Technology               | 2         | 0.19%   |
| Wilocity                        | 1         | 0.09%   |
| Qualcomm                        | 1         | 0.09%   |
| Micro Star International        | 1         | 0.09%   |
| Marvell Technology Group        | 1         | 0.09%   |
| IMC Networks                    | 1         | 0.09%   |
| D-Link System                   | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 142       | 13.25%  |
| Intel Wi-Fi 6 AX201                                                     | 76        | 7.09%   |
| Intel Wireless 7260                                                     | 68        | 6.34%   |
| Intel Wi-Fi 6 AX200                                                     | 57        | 5.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 53        | 4.94%   |
| Intel Wireless 8265 / 8275                                              | 53        | 4.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 29        | 2.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 27        | 2.52%   |
| Intel Wireless 8260                                                     | 25        | 2.33%   |
| Intel Wireless 7265                                                     | 23        | 2.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 22        | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 1.59%   |
| Intel Wireless 3165                                                     | 16        | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 1.4%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.84%   |
| Intel Wireless 3160                                                     | 9         | 0.84%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 8         | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.75%   |
| Intel Wireless-AC 9260                                                  | 8         | 0.75%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.75%   |
| Intel Centrino Ultimate-N 6300                                          | 8         | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.47%   |
| MEDIATEK Network controller                                             | 5         | 0.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 0.47%   |
| Sierra Wireless EM7345 4G LTE                                           | 4         | 0.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.37%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 4         | 0.37%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 4         | 0.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.37%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.37%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.37%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 4         | 0.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.37%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 4         | 0.37%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 0.37%   |
| Sierra Wireless EM7455                                                  | 3         | 0.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.28%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.28%   |
| Ralink RT5370 Wireless Adapter                                          | 3         | 0.28%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.28%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.28%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 648       | 52.68%  |
| Intel                            | 386       | 31.38%  |
| Broadcom                         | 56        | 4.55%   |
| Qualcomm Atheros                 | 49        | 3.98%   |
| Marvell Technology Group         | 17        | 1.38%   |
| Nvidia                           | 11        | 0.89%   |
| Broadcom Limited                 | 11        | 0.89%   |
| Standard Microsystems            | 7         | 0.57%   |
| DisplayLink                      | 6         | 0.49%   |
| JMicron Technology               | 4         | 0.33%   |
| TP-LINK                          | 3         | 0.24%   |
| Mellanox Technologies            | 3         | 0.24%   |
| Lenovo                           | 3         | 0.24%   |
| Xiaomi                           | 2         | 0.16%   |
| VIA Technologies                 | 2         | 0.16%   |
| Cypress Semiconductor            | 2         | 0.16%   |
| Attansic Technology              | 2         | 0.16%   |
| ASIX Electronics                 | 2         | 0.16%   |
| Aquantia                         | 2         | 0.16%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |
| Samsung Electronics              | 1         | 0.08%   |
| QLogic                           | 1         | 0.08%   |
| OPPO Electronics                 | 1         | 0.08%   |
| Microsoft                        | 1         | 0.08%   |
| Microchip Technology             | 1         | 0.08%   |
| MediaTek                         | 1         | 0.08%   |
| IBM                              | 1         | 0.08%   |
| Huawei Technologies              | 1         | 0.08%   |
| Google                           | 1         | 0.08%   |
| D-Link                           | 1         | 0.08%   |
| American Megatrends              | 1         | 0.08%   |
| ADMtek                           | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 515       | 40.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 72        | 5.72%   |
| Intel Ethernet Connection (13) I219-V                             | 60        | 4.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 54        | 4.29%   |
| Intel I211 Gigabit Network Connection                             | 29        | 2.3%    |
| Intel Ethernet Connection (4) I219-V                              | 29        | 2.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 1.43%   |
| Intel Ethernet Connection (2) I219-V                              | 18        | 1.43%   |
| Intel I210 Gigabit Network Connection                             | 14        | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.95%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.71%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.71%   |
| Intel Ethernet Connection I217-V                                  | 8         | 0.64%   |
| Standard Microsystems SMSC9512/9514 Fast Ethernet Adapter         | 7         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.56%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7         | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.4%    |
| Nvidia MCP61 Ethernet                                             | 5         | 0.4%    |
| Intel Ethernet Connection I219-V                                  | 5         | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.4%    |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.4%    |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.4%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 0.4%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 0.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.32%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 4         | 0.32%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 4         | 0.32%   |
| Intel Ethernet Connection (5) I219-LM                             | 4         | 0.32%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 0.32%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 3         | 0.24%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.24%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.24%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.24%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.24%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.24%   |
| Intel I350 Gigabit Network Connection                             | 3         | 0.24%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.24%   |
| Intel Ethernet Controller 10G X550T                               | 3         | 0.24%   |
| Intel Ethernet Connection (11) I219-V                             | 3         | 0.24%   |
| Intel 82599 10 Gigabit Dual Port Network Connection               | 3         | 0.24%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.24%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.24%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 0.24%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1176      | 52.93%  |
| WiFi     | 1027      | 46.22%  |
| Modem    | 18        | 0.81%   |
| Unknown  | 1         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1018      | 53.41%  |
| WiFi     | 885       | 46.43%  |
| Modem    | 2         | 0.1%    |
| Unknown  | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 734       | 48.8%   |
| 2     | 686       | 45.61%  |
| 0     | 43        | 2.86%   |
| 3     | 26        | 1.73%   |
| 4     | 8         | 0.53%   |
| 6     | 3         | 0.2%    |
| 5     | 2         | 0.13%   |
| 13    | 1         | 0.07%   |
| 8     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1311      | 86.82%  |
| Yes  | 199       | 13.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 434       | 48.06%  |
| Apple                           | 164       | 18.16%  |
| Realtek Semiconductor           | 59        | 6.53%   |
| Qualcomm Atheros Communications | 59        | 6.53%   |
| Broadcom                        | 37        | 4.1%    |
| Lite-On Technology              | 34        | 3.77%   |
| Cambridge Silicon Radio         | 33        | 3.65%   |
| IMC Networks                    | 23        | 2.55%   |
| Foxconn / Hon Hai               | 12        | 1.33%   |
| ASUSTek Computer                | 11        | 1.22%   |
| Realtek                         | 6         | 0.66%   |
| Ralink                          | 6         | 0.66%   |
| Hewlett-Packard                 | 6         | 0.66%   |
| Dell                            | 5         | 0.55%   |
| Toshiba                         | 4         | 0.44%   |
| Taiyo Yuden                     | 2         | 0.22%   |
| Belkin Components               | 2         | 0.22%   |
| USI                             | 1         | 0.11%   |
| Sitecom Europe                  | 1         | 0.11%   |
| Qcom                            | 1         | 0.11%   |
| Micro Star International        | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| Alps Electric                   | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Apple Bluetooth USB Host Controller                       | 146       | 16.13%  |
| Intel Bluetooth wireless interface                        | 115       | 12.71%  |
| Intel AX201 Bluetooth                                     | 104       | 11.49%  |
| Intel Bluetooth Device                                    | 84        | 9.28%   |
| Intel AX200 Bluetooth                                     | 59        | 6.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 54        | 5.97%   |
| Realtek Bluetooth Radio                                   | 39        | 4.31%   |
| Qualcomm Atheros  Bluetooth Device                        | 37        | 4.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 33        | 3.65%   |
| Lite-On Bluetooth Device                                  | 26        | 2.87%   |
| Realtek  Bluetooth 4.2 Adapter                            | 14        | 1.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 9         | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                          | 9         | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 8         | 0.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                | 8         | 0.88%   |
| Apple Bluetooth Host Controller                           | 8         | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 7         | 0.77%   |
| IMC Networks Bluetooth Radio                              | 7         | 0.77%   |
| Broadcom BCM2045B (BDC-2.1)                               | 7         | 0.77%   |
| Realtek Bluetooth Radio                                   | 6         | 0.66%   |
| Ralink RT3290 Bluetooth                                   | 6         | 0.66%   |
| IMC Networks Bluetooth Device                             | 6         | 0.66%   |
| Foxconn / Hon Hai Bluetooth Device                        | 6         | 0.66%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                      | 6         | 0.66%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 5         | 0.55%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 4         | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                          | 4         | 0.44%   |
| Broadcom BCM43142A0 Bluetooth 4.0                         | 4         | 0.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 4         | 0.44%   |
| Toshiba Bluetooth Device                                  | 3         | 0.33%   |
| Realtek RTL8723B Bluetooth                                | 3         | 0.33%   |
| Lite-On Atheros AR3012 Bluetooth                          | 3         | 0.33%   |
| IMC Networks Wireless_Device                              | 3         | 0.33%   |
| IMC Networks Bluetooth                                    | 3         | 0.33%   |
| Broadcom BCM2045 Bluetooth                                | 3         | 0.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                   | 2         | 0.22%   |
| Qualcomm Atheros Bluetooth USB Host Controller            | 2         | 0.22%   |
| Lite-On BCM43142A0                                        | 2         | 0.22%   |
| IMC Networks Bluetooth module                             | 2         | 0.22%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller           | 2         | 0.22%   |
| Dell DW375 Bluetooth Module                               | 2         | 0.22%   |
| Broadcom BCM43142 Bluetooth 4.0                           | 2         | 0.22%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]          | 2         | 0.22%   |
| ASUS Bluetooth Device                                     | 2         | 0.22%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                 | 2         | 0.22%   |
| Apple Bluetooth HCI                                       | 2         | 0.22%   |
| USI Bluetooth Module BCM92070                             | 1         | 0.11%   |
| Toshiba Atheros AR3012 Bluetooth                          | 1         | 0.11%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)                   | 1         | 0.11%   |
| Taiyo Yuden Bluetooth Device                              | 1         | 0.11%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1         | 0.11%   |
| Realtek RTL8723A Bluetooth                                | 1         | 0.11%   |
| Realtek CSR BS8510                                        | 1         | 0.11%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 1         | 0.11%   |
| Qcom Broadcom Bluetooth USB                               | 1         | 0.11%   |
| Micro Star International Bluetooth EDR Device             | 1         | 0.11%   |
| Lite-On Wireless_Device                                   | 1         | 0.11%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device              | 1         | 0.11%   |
| Lite-On Bluetooth Radio                                   | 1         | 0.11%   |
| Intel AX210 Bluetooth                                     | 1         | 0.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1153      | 61.04%  |
| AMD                              | 308       | 16.3%   |
| Nvidia                           | 290       | 15.35%  |
| C-Media Electronics              | 19        | 1.01%   |
| Logitech                         | 12        | 0.64%   |
| Generalplus Technology           | 12        | 0.64%   |
| Creative Labs                    | 8         | 0.42%   |
| Texas Instruments                | 5         | 0.26%   |
| RODE Microphones                 | 5         | 0.26%   |
| Plantronics                      | 5         | 0.26%   |
| GN Netcom                        | 5         | 0.26%   |
| Creative Technology              | 5         | 0.26%   |
| VIA Technologies                 | 4         | 0.21%   |
| Lenovo                           | 4         | 0.21%   |
| GYROCOM C&C                      | 4         | 0.21%   |
| Unknown                          | 3         | 0.16%   |
| JMTek                            | 3         | 0.16%   |
| Cambridge Silicon Radio          | 3         | 0.16%   |
| Yamaha                           | 2         | 0.11%   |
| XMOS                             | 2         | 0.11%   |
| SteelSeries ApS                  | 2         | 0.11%   |
| Sennheiser Communications        | 2         | 0.11%   |
| Samson Technologies              | 2         | 0.11%   |
| Razer USA                        | 2         | 0.11%   |
| BEHRINGER International          | 2         | 0.11%   |
| ASUSTek Computer                 | 2         | 0.11%   |
| TerraTec Electronic              | 1         | 0.05%   |
| TEAC                             | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| SAVITECH                         | 1         | 0.05%   |
| ROCCAT                           | 1         | 0.05%   |
| Realtek Semiconductor            | 1         | 0.05%   |
| PreSonus Audio Electronics       | 1         | 0.05%   |
| Musical Fidelity                 | 1         | 0.05%   |
| Microsoft                        | 1         | 0.05%   |
| Micronas                         | 1         | 0.05%   |
| M-Audio                          | 1         | 0.05%   |
| Kingston Technology              | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Hangzhou Worlde                  | 1         | 0.05%   |
| Focusrite-Novation               | 1         | 0.05%   |
| DisplayLink                      | 1         | 0.05%   |
| Dell                             | 1         | 0.05%   |
| CMX Systems                      | 1         | 0.05%   |
| Blue Microphones                 | 1         | 0.05%   |
| B & W Group                      | 1         | 0.05%   |
| AXELVOX                          | 1         | 0.05%   |
| AVID Technology                  | 1         | 0.05%   |
| Audioengine                      | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |
| Alesis                           | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Broadwell-U Audio Controller                                                                | 163       | 7.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 162       | 6.98%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 117       | 5.04%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 103       | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 100       | 4.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 91        | 3.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 89        | 3.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 88        | 3.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 67        | 2.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 57        | 2.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 54        | 2.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 52        | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 50        | 2.15%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 49        | 2.11%   |
| Intel Comet Lake PCH cAVS                                                                         | 40        | 1.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 39        | 1.68%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 37        | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 32        | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 31        | 1.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 30        | 1.29%   |
| AMD FCH Azalia Controller                                                                         | 30        | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 28        | 1.21%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 28        | 1.21%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 26        | 1.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 26        | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 26        | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 25        | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 23        | 0.99%   |
| Intel 200 Series PCH HD Audio                                                                     | 22        | 0.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 21        | 0.9%    |
| Intel 8 Series HD Audio Controller                                                                | 21        | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 20        | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 20        | 0.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 20        | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 17        | 0.73%   |
| AMD Kabini HDMI/DP Audio                                                                          | 17        | 0.73%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 14        | 0.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 14        | 0.6%    |
| AMD Navi 10 HDMI Audio                                                                            | 14        | 0.6%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 13        | 0.56%   |
| Generalplus Technology Usb Audio Device                                                           | 12        | 0.52%   |
| Nvidia High Definition Audio Controller                                                           | 11        | 0.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 11        | 0.47%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 10        | 0.43%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 10        | 0.43%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 0.43%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 10        | 0.43%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 9         | 0.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 0.39%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 8         | 0.34%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 8         | 0.34%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 7         | 0.3%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 7         | 0.3%    |
| Intel CM238 HD Audio Controller                                                                   | 7         | 0.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 0.3%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 7         | 0.3%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 7         | 0.3%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 7         | 0.3%    |
| AMD Wrestler HDMI Audio                                                                           | 7         | 0.3%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 0.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 390       | 25.91%  |
| SK Hynix            | 218       | 14.49%  |
| Kingston            | 170       | 11.3%   |
| Unknown             | 133       | 8.84%   |
| Crucial             | 130       | 8.64%   |
| Micron Technology   | 119       | 7.91%   |
| Corsair             | 61        | 4.05%   |
| Elpida              | 57        | 3.79%   |
| Patriot             | 33        | 2.19%   |
| G.Skill             | 32        | 2.13%   |
| Ramaxel Technology  | 27        | 1.79%   |
| A-DATA Technology   | 23        | 1.53%   |
| Hikvision           | 20        | 1.33%   |
| Nanya Technology    | 15        | 1%      |
| Team                | 10        | 0.66%   |
| Smart               | 9         | 0.6%    |
| GOODRAM             | 5         | 0.33%   |
| AMD                 | 5         | 0.33%   |
| Unknown (ABCD)      | 4         | 0.27%   |
| Transcend           | 4         | 0.27%   |
| Kllisre             | 3         | 0.2%    |
| Unknown (0x07D5)    | 2         | 0.13%   |
| Unifosa             | 2         | 0.13%   |
| Qimonda             | 2         | 0.13%   |
| PNY                 | 2         | 0.13%   |
| Kingmax             | 2         | 0.13%   |
| Infineon            | 2         | 0.13%   |
| Goldkey             | 2         | 0.13%   |
| ASint Technology    | 2         | 0.13%   |
| Apacer              | 2         | 0.13%   |
| Wilk                | 1         | 0.07%   |
| V-Color             | 1         | 0.07%   |
| TwinMOS             | 1         | 0.07%   |
| Toshiba             | 1         | 0.07%   |
| TIMETEC             | 1         | 0.07%   |
| Teikon              | 1         | 0.07%   |
| SMART Brazil        | 1         | 0.07%   |
| Silicon Power       | 1         | 0.07%   |
| Sesame              | 1         | 0.07%   |
| SemsoTai            | 1         | 0.07%   |
| OCZ                 | 1         | 0.07%   |
| Novatech            | 1         | 0.07%   |
| KETECH              | 1         | 0.07%   |
| Hyundai lnc         | 1         | 0.07%   |
| Hewlett-Packard     | 1         | 0.07%   |
| GeIL                | 1         | 0.07%   |
| Avant               | 1         | 0.07%   |
| A-TECH              | 1         | 0.07%   |
| 48spaces            | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 66        | 4.08%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                 | 61        | 3.77%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s       | 39        | 2.41%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                  | 30        | 1.86%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 22        | 1.36%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1600MT/s       | 22        | 1.36%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                 | 20        | 1.24%   |
| Hikvision RAM HKED4161DAA1D0MA1 16384MB DIMM DDR4 2667MT/s  | 20        | 1.24%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 19        | 1.18%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s      | 19        | 1.18%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                  | 15        | 0.93%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s     | 12        | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 11        | 0.68%   |
| Patriot RAM PSD32G13332 2048MB DIMM DDR3 1333MT/s           | 10        | 0.62%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s        | 10        | 0.62%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 8         | 0.5%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 8         | 0.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 8         | 0.5%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 7         | 0.43%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s    | 7         | 0.43%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s             | 7         | 0.43%   |
| Kingston RAM 99U5474-025.A00LF 2GB DIMM DDR3 1333MT/s       | 7         | 0.43%   |
| Kingston RAM 9905474-012.A00LF 2048MB DIMM DDR3 1333MT/s    | 7         | 0.43%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 6         | 0.37%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 6         | 0.37%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 6         | 0.37%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s   | 6         | 0.37%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s   | 6         | 0.37%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s       | 6         | 0.37%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 6         | 0.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 6         | 0.37%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s      | 6         | 0.37%   |
| Patriot RAM PSD32G133381 2GB DIMM DDR3 1333MT/s             | 6         | 0.37%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 6         | 0.37%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 6         | 0.37%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s      | 6         | 0.37%   |
| Crucial RAM CT25664BA160B.D8FE 2GB DIMM DDR3 1600MT/s       | 6         | 0.37%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s       | 6         | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                 | 5         | 0.31%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s   | 5         | 0.31%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s   | 5         | 0.31%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 5         | 0.31%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s | 5         | 0.31%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                   | 4         | 0.25%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                   | 4         | 0.25%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 4         | 0.25%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                        | 4         | 0.25%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 4         | 0.25%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                 | 4         | 0.25%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                     | 4         | 0.25%   |
| Unknown RAM Module 1GB DIMM SDRAM                           | 4         | 0.25%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 0.25%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s    | 4         | 0.25%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 4         | 0.25%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 4         | 0.25%   |
| Kingston RAM 99U5584-017.A00LF 4GB DIMM DDR3 1600MT/s       | 4         | 0.25%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s     | 4         | 0.25%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 4         | 0.25%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 3         | 0.19%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 3         | 0.19%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 590       | 44.49%  |
| DDR4    | 544       | 41.03%  |
| DDR2    | 64        | 4.83%   |
| SDRAM   | 32        | 2.41%   |
| Unknown | 31        | 2.34%   |
| LPDDR3  | 29        | 2.19%   |
| LPDDR4  | 20        | 1.51%   |
| DDR     | 15        | 1.13%   |
| DRAM    | 1         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 787       | 59.26%  |
| DIMM         | 481       | 36.22%  |
| Row Of Chips | 49        | 3.69%   |
| Chip         | 8         | 0.6%    |
| RIMM         | 1         | 0.08%   |
| FB-DIMM      | 1         | 0.08%   |
| Unknown      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 441       | 30.77%  |
| 4096  | 416       | 29.03%  |
| 2048  | 300       | 20.94%  |
| 16384 | 149       | 10.4%   |
| 1024  | 64        | 4.47%   |
| 32768 | 38        | 2.65%   |
| 512   | 17        | 1.19%   |
| 256   | 5         | 0.35%   |
| 65536 | 3         | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 439       | 30.87%  |
| 2667    | 195       | 13.71%  |
| 3200    | 192       | 13.5%   |
| 1333    | 126       | 8.86%   |
| 2400    | 77        | 5.41%   |
| 2133    | 57        | 4.01%   |
| Unknown | 33        | 2.32%   |
| 800     | 31        | 2.18%   |
| 1334    | 30        | 2.11%   |
| 667     | 28        | 1.97%   |
| 1867    | 23        | 1.62%   |
| 1067    | 18        | 1.27%   |
| 3600    | 17        | 1.2%    |
| 2666    | 13        | 0.91%   |
| 3266    | 11        | 0.77%   |
| 1866    | 11        | 0.77%   |
| 1066    | 11        | 0.77%   |
| 3000    | 10        | 0.7%    |
| 533     | 10        | 0.7%    |
| 4267    | 9         | 0.63%   |
| 2933    | 9         | 0.63%   |
| 3466    | 6         | 0.42%   |
| 3400    | 6         | 0.42%   |
| 400     | 6         | 0.42%   |
| 975     | 5         | 0.35%   |
| 333     | 5         | 0.35%   |
| 4199    | 4         | 0.28%   |
| 1800    | 4         | 0.28%   |
| 4333    | 3         | 0.21%   |
| 3733    | 3         | 0.21%   |
| 3100    | 3         | 0.21%   |
| 1400    | 3         | 0.21%   |
| 4266    | 2         | 0.14%   |
| 3533    | 2         | 0.14%   |
| 3500    | 2         | 0.14%   |
| 3066    | 2         | 0.14%   |
| 2465    | 2         | 0.14%   |
| 2048    | 2         | 0.14%   |
| 2000    | 2         | 0.14%   |
| 3866    | 1         | 0.07%   |
| 3800    | 1         | 0.07%   |
| 3333    | 1         | 0.07%   |
| 2866    | 1         | 0.07%   |
| 2267    | 1         | 0.07%   |
| 2187    | 1         | 0.07%   |
| 2134    | 1         | 0.07%   |
| 1777    | 1         | 0.07%   |
| 1367    | 1         | 0.07%   |
| 66      | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 13        | 50%     |
| Brother Industries  | 4         | 15.38%  |
| Samsung Electronics | 3         | 11.54%  |
| Canon               | 3         | 11.54%  |
| Prolific Technology | 1         | 3.85%   |
| Konica Minolta      | 1         | 3.85%   |
| Dymo-CoStar         | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| HP LaserJet M101-M106               | 2         | 7.69%   |
| HP LaserJet 1200                    | 2         | 7.69%   |
| HP ENVY 4520 series                 | 2         | 7.69%   |
| Samsung SCX-4650 4x21S Series       | 1         | 3.85%   |
| Samsung ML-2010P Mono Laser Printer | 1         | 3.85%   |
| Samsung ML-1660 Series              | 1         | 3.85%   |
| Prolific PL2305 Parallel Port       | 1         | 3.85%   |
| Konica Minolta bizhub 4402P         | 1         | 3.85%   |
| HP Officejet J4500 series           | 1         | 3.85%   |
| HP LaserJet P1006                   | 1         | 3.85%   |
| HP LaserJet 400 M401n               | 1         | 3.85%   |
| HP LaserJet 1150                    | 1         | 3.85%   |
| HP LaserJet 1020                    | 1         | 3.85%   |
| HP ENVY 5000 series                 | 1         | 3.85%   |
| HP DeskJet 2130 series              | 1         | 3.85%   |
| Dymo-CoStar LabelWriter 450         | 1         | 3.85%   |
| Canon PIXMA MX920 Series            | 1         | 3.85%   |
| Canon LiDE 400                      | 1         | 3.85%   |
| Canon iP2700 series                 | 1         | 3.85%   |
| Brother MFC-L2710DW series          | 1         | 3.85%   |
| Brother MFC-L2707DW                 | 1         | 3.85%   |
| Brother HL-2240 series              | 1         | 3.85%   |
| Brother FAX-2940                    | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 5         | 62.5%   |
| Canon           | 2         | 25%     |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 25%     |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1         | 12.5%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 12.5%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 1         | 12.5%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]            | 1         | 12.5%   |
| Seiko Epson GT-7700U [Perfection 1240U]                  | 1         | 12.5%   |
| HP ScanJet 3970c                                         | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 176       | 22.34%  |
| Acer                                   | 123       | 15.61%  |
| Quanta                                 | 76        | 9.64%   |
| IMC Networks                           | 73        | 9.26%   |
| Microdia                               | 55        | 6.98%   |
| Logitech                               | 47        | 5.96%   |
| Realtek Semiconductor                  | 46        | 5.84%   |
| Suyin                                  | 20        | 2.54%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 2.54%   |
| Apple                                  | 20        | 2.54%   |
| Sunplus Innovation Technology          | 19        | 2.41%   |
| Lite-On Technology                     | 18        | 2.28%   |
| Syntek                                 | 13        | 1.65%   |
| Luxvisions Innotech Limited            | 8         | 1.02%   |
| Silicon Motion                         | 7         | 0.89%   |
| Lenovo                                 | 7         | 0.89%   |
| Z-Star Microelectronics                | 6         | 0.76%   |
| Samsung Electronics                    | 5         | 0.63%   |
| Generalplus Technology                 | 5         | 0.63%   |
| Alcor Micro                            | 5         | 0.63%   |
| Primax Electronics                     | 3         | 0.38%   |
| Microsoft                              | 3         | 0.38%   |
| Ricoh                                  | 2         | 0.25%   |
| Intel                                  | 2         | 0.25%   |
| Genesys Logic                          | 2         | 0.25%   |
| eMPIA Technology                       | 2         | 0.25%   |
| Creative Technology                    | 2         | 0.25%   |
| Xiongmai                               | 1         | 0.13%   |
| Unknown                                | 1         | 0.13%   |
| Sunplus Technology                     | 1         | 0.13%   |
| Sonix Technology                       | 1         | 0.13%   |
| SiGma Micro                            | 1         | 0.13%   |
| Razer USA                              | 1         | 0.13%   |
| Pixart Imaging                         | 1         | 0.13%   |
| Philips (or NXP)                       | 1         | 0.13%   |
| OmniVision Technologies                | 1         | 0.13%   |
| Novatek Microelectronics               | 1         | 0.13%   |
| Nintendo                               | 1         | 0.13%   |
| Mimaki Engineering                     | 1         | 0.13%   |
| KYE Systems (Mouse Systems)            | 1         | 0.13%   |
| Jieli Technology                       | 1         | 0.13%   |
| Importek                               | 1         | 0.13%   |
| Huawei Technologies                    | 1         | 0.13%   |
| Holitech                               | 1         | 0.13%   |
| Hewlett-Packard                        | 1         | 0.13%   |
| AVerMedia Technologies                 | 1         | 0.13%   |
| ARC International                      | 1         | 0.13%   |
| ALi                                    | 1         | 0.13%   |
| A4Tech                                 | 1         | 0.13%   |
| 8SSC20F27114V1SR0C71XEG                | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Acer Integrated Camera                                                     | 75        | 9.2%    |
| Chicony Integrated Camera                                                  | 56        | 6.87%   |
| Quanta Chromebook HD Camera                                                | 37        | 4.54%   |
| Chicony Integrated 5M Camera                                               | 30        | 3.68%   |
| Acer Integrated 5M Camera                                                  | 25        | 3.07%   |
| Microdia Integrated_Webcam_HD                                              | 24        | 2.94%   |
| IMC Networks Integrated Camera                                             | 24        | 2.94%   |
| Chicony HD WebCam                                                          | 19        | 2.33%   |
| Realtek Integrated_Webcam_HD                                               | 17        | 2.09%   |
| Quanta VGA WebCam                                                          | 17        | 2.09%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 15        | 1.84%   |
| Acer BisonCam, NB Pro                                                      | 15        | 1.84%   |
| Logitech Webcam C270                                                       | 13        | 1.6%    |
| Chicony Chromebook HD Camera                                               | 10        | 1.23%   |
| Acer SunplusIT Integrated Camera                                           | 10        | 1.23%   |
| Sunplus Integrated_Webcam_HD                                               | 8         | 0.98%   |
| Chicony HP HD Camera                                                       | 8         | 0.98%   |
| Syntek Integrated Camera                                                   | 7         | 0.86%   |
| Lite-On Integrated Camera                                                  | 7         | 0.86%   |
| Apple Built-in iSight                                                      | 7         | 0.86%   |
| Logitech HD Pro Webcam C920                                                | 6         | 0.74%   |
| Chicony Integrated Camera (1280x720@30)                                    | 6         | 0.74%   |
| Acer Lenovo EasyCamera                                                     | 6         | 0.74%   |
| Samsung Galaxy A5 (MTP)                                                    | 5         | 0.61%   |
| Realtek Integrated Webcam                                                  | 5         | 0.61%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 0.61%   |
| Microdia Webcam Vitade AF                                                  | 5         | 0.61%   |
| Microdia USB 2.0 Camera                                                    | 5         | 0.61%   |
| Microdia Integrated Webcam                                                 | 5         | 0.61%   |
| Logitech C922 Pro Stream Webcam                                            | 5         | 0.61%   |
| Lite-On HP HD Camera                                                       | 5         | 0.61%   |
| Lenovo Integrated Webcam                                                   | 5         | 0.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 5         | 0.61%   |
| Chicony Lenovo EasyCamera                                                  | 5         | 0.61%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 5         | 0.61%   |
| Quanta HD WebCam                                                           | 4         | 0.49%   |
| Quanta HD User Facing                                                      | 4         | 0.49%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 4         | 0.49%   |
| IMC Networks HP TrueVision HD Camera                                       | 4         | 0.49%   |
| Chicony USB2.0 Camera                                                      | 4         | 0.49%   |
| Chicony EasyCamera                                                         | 4         | 0.49%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 4         | 0.49%   |
| Acer EasyCamera                                                            | 4         | 0.49%   |
| Z-Star Venus USB2.0 Camera                                                 | 3         | 0.37%   |
| Suyin Acer CrystalEye Webcam                                               | 3         | 0.37%   |
| Realtek Integrated Webcam HD                                               | 3         | 0.37%   |
| Realtek HD WebCam                                                          | 3         | 0.37%   |
| Quanta HP Webcam                                                           | 3         | 0.37%   |
| Microdia Integrated Webcam HD                                              | 3         | 0.37%   |
| Logitech Webcam C170                                                       | 3         | 0.37%   |
| Logitech HD Webcam C615                                                    | 3         | 0.37%   |
| IMC Networks UVC VGA Webcam                                                | 3         | 0.37%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 3         | 0.37%   |
| IMC Networks SunplusIT Integrated Camera                                   | 3         | 0.37%   |
| IMC Networks ov9734_azurewave_camera                                       | 3         | 0.37%   |
| Generalplus GENERAL WEBCAM                                                 | 3         | 0.37%   |
| Chicony HP TrueVision HD Camera                                            | 3         | 0.37%   |
| Chicony HP Truevision HD                                                   | 3         | 0.37%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam               | 3         | 0.37%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.37%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 95        | 48.72%  |
| Validity Sensors           | 53        | 27.18%  |
| Shenzhen Goodix Technology | 22        | 11.28%  |
| Upek                       | 7         | 3.59%   |
| AuthenTec                  | 7         | 3.59%   |
| Elan Microelectronics      | 5         | 2.56%   |
| LighTuning Technology      | 4         | 2.05%   |
| STMicroelectronics         | 2         | 1.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 73        | 37.44%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 21        | 10.77%  |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 6.15%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 4.62%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 4.1%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 3.59%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 3.08%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 2.56%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 2.56%   |
| Elan ELAN:Fingerprint                                                      | 5         | 2.56%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 2.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.05%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.05%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.54%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.54%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.54%   |
| Synaptics  WBDI                                                            | 3         | 1.54%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.54%   |
| Unknown                                                                    | 3         | 1.54%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.03%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.03%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.51%   |
| Validity Sensors VFS491                                                    | 1         | 0.51%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.51%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.51%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.51%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 21        | 33.87%  |
| Alcor Micro           | 20        | 32.26%  |
| Upek                  | 7         | 11.29%  |
| Lenovo                | 7         | 11.29%  |
| O2 Micro              | 2         | 3.23%   |
| Yubico.com            | 1         | 1.61%   |
| OmniKey               | 1         | 1.61%   |
| Gemalto (was Gemplus) | 1         | 1.61%   |
| Chicony Electronics   | 1         | 1.61%   |
| Cherry                | 1         | 1.61%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 32.26%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 11.29%  |
| Lenovo Integrated Smart Card Reader                                          | 7         | 11.29%  |
| Broadcom 5880                                                                | 7         | 11.29%  |
| Broadcom 58200                                                               | 6         | 9.68%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 8.06%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.23%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 3.23%   |
| Yubico.com Yubikey 4 CCID                                                    | 1         | 1.61%   |
| OmniKey CardMan 4321                                                         | 1         | 1.61%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.61%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.61%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.61%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.61%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 779       | 51.56%  |
| 1     | 629       | 41.63%  |
| 2     | 86        | 5.69%   |
| 3     | 14        | 0.93%   |
| 5     | 2         | 0.13%   |
| 4     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 295       | 36.69%  |
| Fingerprint reader       | 194       | 24.13%  |
| Multimedia controller    | 165       | 20.52%  |
| Chipcard                 | 50        | 6.22%   |
| Net/wireless             | 32        | 3.98%   |
| Communication controller | 17        | 2.11%   |
| Bluetooth                | 15        | 1.87%   |
| Unassigned class         | 10        | 1.24%   |
| Storage                  | 5         | 0.62%   |
| Sound                    | 5         | 0.62%   |
| Card reader              | 4         | 0.5%    |
| Network                  | 3         | 0.37%   |
| Dvb card                 | 2         | 0.25%   |
| Tv card                  | 1         | 0.12%   |
| Storage/ide              | 1         | 0.12%   |
| Net/ethernet             | 1         | 0.12%   |
| Modem                    | 1         | 0.12%   |
| Flash memory             | 1         | 0.12%   |
| Firewire controller      | 1         | 0.12%   |
| Camera                   | 1         | 0.12%   |

