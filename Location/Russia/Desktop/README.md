Linux in Russia - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Russia.

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

Total: 20181

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | A520M PRO                   | [b83b272494](https://linux-hardware.org/?probe=b83b272494) | Nov 06, 2023 |
| ASUSTek       | A68HM-K                     | [c3e5415128](https://linux-hardware.org/?probe=c3e5415128) | Nov 06, 2023 |
| Huanan        | X99-QD4 V1.0                | [3cedc8f704](https://linux-hardware.org/?probe=3cedc8f704) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8ee603dbfc](https://linux-hardware.org/?probe=8ee603dbfc) | Nov 05, 2023 |
| ASUSTek       | P5K PRO                     | [7dd5e78310](https://linux-hardware.org/?probe=7dd5e78310) | Nov 05, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [3d09b709c4](https://linux-hardware.org/?probe=3d09b709c4) | Nov 05, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [e079b95148](https://linux-hardware.org/?probe=e079b95148) | Nov 05, 2023 |
| Gigabyte      | X570 UD                     | [287ceab4df](https://linux-hardware.org/?probe=287ceab4df) | Nov 05, 2023 |
| Gigabyte      | X570 UD                     | [1c9b1632b8](https://linux-hardware.org/?probe=1c9b1632b8) | Nov 05, 2023 |
| Pegatron      | IPMIP-H55-GEN               | [f87bf6e0dd](https://linux-hardware.org/?probe=f87bf6e0dd) | Nov 04, 2023 |
| Intel         | DG33BU AAD79951-407         | [734dafca4e](https://linux-hardware.org/?probe=734dafca4e) | Nov 04, 2023 |
| MSI           | H110M PRO-D                 | [9a7337554c](https://linux-hardware.org/?probe=9a7337554c) | Nov 04, 2023 |
| Gigabyte      | GA-870A-USB3L               | [d2412dfd7c](https://linux-hardware.org/?probe=d2412dfd7c) | Nov 04, 2023 |
| Lenovo        | 317E NOK                    | [1d038af880](https://linux-hardware.org/?probe=1d038af880) | Nov 04, 2023 |
| Gigabyte      | H470M K                     | [d69493b7d2](https://linux-hardware.org/?probe=d69493b7d2) | Nov 04, 2023 |
| Pegatron      | E60                         | [42e0c4ad61](https://linux-hardware.org/?probe=42e0c4ad61) | Nov 04, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [cda17ca99b](https://linux-hardware.org/?probe=cda17ca99b) | Nov 04, 2023 |
| Gigabyte      | H470M K                     | [80085c7047](https://linux-hardware.org/?probe=80085c7047) | Nov 04, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [18bafa67dc](https://linux-hardware.org/?probe=18bafa67dc) | Nov 04, 2023 |
| Supermicro    | X9DRW                       | [d9bb198389](https://linux-hardware.org/?probe=d9bb198389) | Nov 03, 2023 |
| ASUSTek       | P5QD TURBO                  | [4a350b6fdb](https://linux-hardware.org/?probe=4a350b6fdb) | Nov 03, 2023 |
| ASRock        | A770DE+                     | [330e203c8a](https://linux-hardware.org/?probe=330e203c8a) | Nov 03, 2023 |
| Intel         | H610-MIX v1.0               | [eeaea55301](https://linux-hardware.org/?probe=eeaea55301) | Nov 03, 2023 |
| Supermicro    | X10DRL-i                    | [cada5224ab](https://linux-hardware.org/?probe=cada5224ab) | Nov 03, 2023 |
| ASRock        | H170M Pro4                  | [b87ccd7768](https://linux-hardware.org/?probe=b87ccd7768) | Nov 03, 2023 |
| MSI           | 760GM-P21                   | [f3b16a05ae](https://linux-hardware.org/?probe=f3b16a05ae) | Nov 03, 2023 |
| Supermicro    | X10DRU-i+B                  | [305ce5bbcc](https://linux-hardware.org/?probe=305ce5bbcc) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | [8a0ff875f1](https://linux-hardware.org/?probe=8a0ff875f1) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | [3138fbde8e](https://linux-hardware.org/?probe=3138fbde8e) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | [f3023a2a6f](https://linux-hardware.org/?probe=f3023a2a6f) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | [d9dcb6003e](https://linux-hardware.org/?probe=d9dcb6003e) | Nov 03, 2023 |
| Shenzhen M... | F7BFD                       | [f2b8e311c3](https://linux-hardware.org/?probe=f2b8e311c3) | Nov 02, 2023 |
| ASUSTek       | A88XM-E                     | [b828019cc1](https://linux-hardware.org/?probe=b828019cc1) | Nov 02, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [54a7f5d1fa](https://linux-hardware.org/?probe=54a7f5d1fa) | Nov 02, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [175020104d](https://linux-hardware.org/?probe=175020104d) | Nov 02, 2023 |
| Supermicro    | X10DRU-i+A                  | [2eee634512](https://linux-hardware.org/?probe=2eee634512) | Nov 02, 2023 |
| Supermicro    | X9DRW                       | [406a1425ae](https://linux-hardware.org/?probe=406a1425ae) | Nov 02, 2023 |
| Supermicro    | X10DRL-i                    | [7d77c86bc5](https://linux-hardware.org/?probe=7d77c86bc5) | Nov 02, 2023 |
| MSI           | 760GM-P21                   | [2d08e07e5d](https://linux-hardware.org/?probe=2d08e07e5d) | Nov 02, 2023 |
| ASRock        | H61M-VS                     | [677490b7c2](https://linux-hardware.org/?probe=677490b7c2) | Nov 02, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [3de1d3a50f](https://linux-hardware.org/?probe=3de1d3a50f) | Nov 02, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [64a57926cf](https://linux-hardware.org/?probe=64a57926cf) | Nov 02, 2023 |
| Gigabyte      | 945GCMX-S2                  | [9e43e8bb79](https://linux-hardware.org/?probe=9e43e8bb79) | Nov 01, 2023 |
| ASRock        | N68C-S UCC                  | [cc636af8e3](https://linux-hardware.org/?probe=cc636af8e3) | Nov 01, 2023 |
| ASUSTek       | PRIME B350M-K               | [bc9c6a8334](https://linux-hardware.org/?probe=bc9c6a8334) | Nov 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [be72cba293](https://linux-hardware.org/?probe=be72cba293) | Nov 01, 2023 |
| Aquarius      | AQX300M                     | [b70a012245](https://linux-hardware.org/?probe=b70a012245) | Nov 01, 2023 |
| MAINBRD       | OPS62A-SHA                  | [41dc7afbc6](https://linux-hardware.org/?probe=41dc7afbc6) | Nov 01, 2023 |
| Gigabyte      | X570 GAMING X               | [fee5d3eded](https://linux-hardware.org/?probe=fee5d3eded) | Nov 01, 2023 |
| ASRock        | B450M-HDV R4.0              | [c962dd6f41](https://linux-hardware.org/?probe=c962dd6f41) | Nov 01, 2023 |
| Unknown       | Unknown                     | [ae244bf378](https://linux-hardware.org/?probe=ae244bf378) | Nov 01, 2023 |
| Gigabyte      | B760 GAMING X               | [a360fd740f](https://linux-hardware.org/?probe=a360fd740f) | Nov 01, 2023 |
| Unknown       | Unknown                     | [e135ca8165](https://linux-hardware.org/?probe=e135ca8165) | Oct 31, 2023 |
| Gigabyte      | AX370M-Gaming 3-CF          | [d271d2ae41](https://linux-hardware.org/?probe=d271d2ae41) | Oct 31, 2023 |
| Gigabyte      | EP43T-UD3L                  | [a3a25165b1](https://linux-hardware.org/?probe=a3a25165b1) | Oct 31, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [763630b66c](https://linux-hardware.org/?probe=763630b66c) | Oct 31, 2023 |
| Gigabyte      | B75M-D3V                    | [c6d1fc4965](https://linux-hardware.org/?probe=c6d1fc4965) | Oct 31, 2023 |
| Unknown       | Unknown                     | [4e9f4aa1ab](https://linux-hardware.org/?probe=4e9f4aa1ab) | Oct 31, 2023 |
| Gigabyte      | H510M H                     | [d89e17690d](https://linux-hardware.org/?probe=d89e17690d) | Oct 31, 2023 |
| Gigabyte      | H610M H DDR4                | [6e876b597c](https://linux-hardware.org/?probe=6e876b597c) | Oct 31, 2023 |
| Gigabyte      | H610M H DDR4                | [01f9a9c872](https://linux-hardware.org/?probe=01f9a9c872) | Oct 31, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [b522c4b372](https://linux-hardware.org/?probe=b522c4b372) | Oct 31, 2023 |
| ASRock        | B450M-HDV R4.0              | [54a16261d5](https://linux-hardware.org/?probe=54a16261d5) | Oct 31, 2023 |
| Gigabyte      | Z590 D                      | [d986377165](https://linux-hardware.org/?probe=d986377165) | Oct 31, 2023 |
| ASUSTek       | P8Z77-M                     | [69cd55a4dc](https://linux-hardware.org/?probe=69cd55a4dc) | Oct 31, 2023 |
| Huanan        | X99-F8                      | [0bcf4adaf6](https://linux-hardware.org/?probe=0bcf4adaf6) | Oct 31, 2023 |
| ASUSTek       | M5A78L LE                   | [d7dd5dbdf7](https://linux-hardware.org/?probe=d7dd5dbdf7) | Oct 30, 2023 |
| Gigabyte      | H97M-HD3                    | [0d712d2765](https://linux-hardware.org/?probe=0d712d2765) | Oct 30, 2023 |
| Supermicro    | X10DRU-i+B                  | [516d10eb4d](https://linux-hardware.org/?probe=516d10eb4d) | Oct 30, 2023 |
| Supermicro    | X10DRU-i+A                  | [87881094e7](https://linux-hardware.org/?probe=87881094e7) | Oct 30, 2023 |
| Supermicro    | X10DDW-i                    | [175f00718f](https://linux-hardware.org/?probe=175f00718f) | Oct 30, 2023 |
| Supermicro    | X10DDW-i                    | [a3b51e3697](https://linux-hardware.org/?probe=a3b51e3697) | Oct 30, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [c8b24699a5](https://linux-hardware.org/?probe=c8b24699a5) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [102224106e](https://linux-hardware.org/?probe=102224106e) | Oct 30, 2023 |
| ASUSTek       | PRIME B250-PRO              | [ac060a5eb6](https://linux-hardware.org/?probe=ac060a5eb6) | Oct 29, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [0be3861a6a](https://linux-hardware.org/?probe=0be3861a6a) | Oct 29, 2023 |
| Intel         | H81 V2.3                    | [ad1b4d2589](https://linux-hardware.org/?probe=ad1b4d2589) | Oct 29, 2023 |
| Biostar       | H610MH                      | [82198b27e1](https://linux-hardware.org/?probe=82198b27e1) | Oct 29, 2023 |
| Dell          | 0Y5DDC A00                  | [537823e1ce](https://linux-hardware.org/?probe=537823e1ce) | Oct 29, 2023 |
| ASUSTek       | PRIME H410M-R               | [c9a6bd4217](https://linux-hardware.org/?probe=c9a6bd4217) | Oct 29, 2023 |
| ASUSTek       | M5A87                       | [7e4a0870d1](https://linux-hardware.org/?probe=7e4a0870d1) | Oct 29, 2023 |
| Shenzhen M... | F7BFD                       | [28096584b1](https://linux-hardware.org/?probe=28096584b1) | Oct 28, 2023 |
| MSI           | MS-7235                     | [a20f50ce09](https://linux-hardware.org/?probe=a20f50ce09) | Oct 28, 2023 |
| Gigabyte      | EG41MF-US2H                 | [e79e5c88a2](https://linux-hardware.org/?probe=e79e5c88a2) | Oct 28, 2023 |
| Gigabyte      | EG41MF-US2H                 | [54665c8266](https://linux-hardware.org/?probe=54665c8266) | Oct 28, 2023 |
| Gigabyte      | B75M-D3H                    | [97d8cfe6f0](https://linux-hardware.org/?probe=97d8cfe6f0) | Oct 28, 2023 |
| MSI           | A320M GRENADE               | [723b3a152b](https://linux-hardware.org/?probe=723b3a152b) | Oct 28, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | [7610254116](https://linux-hardware.org/?probe=7610254116) | Oct 27, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [2cb1fb1ec9](https://linux-hardware.org/?probe=2cb1fb1ec9) | Oct 27, 2023 |
| Gigabyte      | Z370M D3H-CF                | [80b6c027b0](https://linux-hardware.org/?probe=80b6c027b0) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a8e35b3846](https://linux-hardware.org/?probe=a8e35b3846) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [4ae7cd098c](https://linux-hardware.org/?probe=4ae7cd098c) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [27eeb454c8](https://linux-hardware.org/?probe=27eeb454c8) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [a822fb4575](https://linux-hardware.org/?probe=a822fb4575) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [7b1a0dde51](https://linux-hardware.org/?probe=7b1a0dde51) | Oct 27, 2023 |
| Gigabyte      | Z590 Gaming X               | [86bb741092](https://linux-hardware.org/?probe=86bb741092) | Oct 27, 2023 |
| Acer          | Veriton N4660G              | [712511f568](https://linux-hardware.org/?probe=712511f568) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [6afb6d264d](https://linux-hardware.org/?probe=6afb6d264d) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [36fadbfb7a](https://linux-hardware.org/?probe=36fadbfb7a) | Oct 27, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [298718536d](https://linux-hardware.org/?probe=298718536d) | Oct 26, 2023 |
| ASRock        | G31M-GS                     | [362c4857dd](https://linux-hardware.org/?probe=362c4857dd) | Oct 26, 2023 |
| ASUSTek       | P5G41T-M LE                 | [ca332e91ff](https://linux-hardware.org/?probe=ca332e91ff) | Oct 26, 2023 |
| Intel         | X99                         | [c23c2dd478](https://linux-hardware.org/?probe=c23c2dd478) | Oct 26, 2023 |
| MSI           | A320M-A PRO                 | [5a0de31e5c](https://linux-hardware.org/?probe=5a0de31e5c) | Oct 26, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [fff464540a](https://linux-hardware.org/?probe=fff464540a) | Oct 26, 2023 |
| Pegatron      | 2AC3                        | [1508d1c2f7](https://linux-hardware.org/?probe=1508d1c2f7) | Oct 26, 2023 |
| Unknown       | Unknown                     | [4631da3dbf](https://linux-hardware.org/?probe=4631da3dbf) | Oct 26, 2023 |
| Intel         | H81                         | [59ac163151](https://linux-hardware.org/?probe=59ac163151) | Oct 26, 2023 |
| MSI           | B450M PRO-VDH MAX           | [df61e58a34](https://linux-hardware.org/?probe=df61e58a34) | Oct 26, 2023 |
| Huanan        | X99-T8 GAMING V2.0          | [27d22c45c8](https://linux-hardware.org/?probe=27d22c45c8) | Oct 26, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [b74c61d287](https://linux-hardware.org/?probe=b74c61d287) | Oct 25, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [7ed95a4707](https://linux-hardware.org/?probe=7ed95a4707) | Oct 25, 2023 |
| MSI           | H110M PRO-VD                | [b62701c032](https://linux-hardware.org/?probe=b62701c032) | Oct 25, 2023 |
| Huanan        | X99-F8                      | [69329218c9](https://linux-hardware.org/?probe=69329218c9) | Oct 25, 2023 |
| Gigabyte      | A320M-S2H-CF                | [b3e80c2dc5](https://linux-hardware.org/?probe=b3e80c2dc5) | Oct 25, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [893389d935](https://linux-hardware.org/?probe=893389d935) | Oct 25, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [56826e6464](https://linux-hardware.org/?probe=56826e6464) | Oct 25, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [b4e2c4d9b6](https://linux-hardware.org/?probe=b4e2c4d9b6) | Oct 25, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [7107e2ed21](https://linux-hardware.org/?probe=7107e2ed21) | Oct 25, 2023 |
| Gigabyte      | H77M-D3H                    | [1d3f58a610](https://linux-hardware.org/?probe=1d3f58a610) | Oct 25, 2023 |
| ECS           | A55F-M3                     | [6da483b400](https://linux-hardware.org/?probe=6da483b400) | Oct 25, 2023 |
| ASRock        | X570 Taichi                 | [e0a94cc59e](https://linux-hardware.org/?probe=e0a94cc59e) | Oct 25, 2023 |
| Gigabyte      | X570 GAMING X               | [78716080bb](https://linux-hardware.org/?probe=78716080bb) | Oct 24, 2023 |
| ASUSTek       | B85M-G                      | [a7463f3745](https://linux-hardware.org/?probe=a7463f3745) | Oct 24, 2023 |
| ASRock        | N68C-GS FX                  | [0c3142b94d](https://linux-hardware.org/?probe=0c3142b94d) | Oct 24, 2023 |
| ASUSTek       | M5A87                       | [273561af88](https://linux-hardware.org/?probe=273561af88) | Oct 24, 2023 |
| Gigabyte      | A320M-H-CF                  | [3d211c5277](https://linux-hardware.org/?probe=3d211c5277) | Oct 24, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [4e13c711c7](https://linux-hardware.org/?probe=4e13c711c7) | Oct 24, 2023 |
| ASUSTek       | H81M-PLUS                   | [541d6f63b0](https://linux-hardware.org/?probe=541d6f63b0) | Oct 23, 2023 |
| ASUSTek       | P5G41-M LX2/GB              | [ffc0782186](https://linux-hardware.org/?probe=ffc0782186) | Oct 23, 2023 |
| ASUSTek       | P6X58D-E                    | [6af3baae7b](https://linux-hardware.org/?probe=6af3baae7b) | Oct 23, 2023 |
| MSI           | 770-C45                     | [9b5876d0eb](https://linux-hardware.org/?probe=9b5876d0eb) | Oct 23, 2023 |
| ASRock        | P67 Pro3                    | [93d23ddc07](https://linux-hardware.org/?probe=93d23ddc07) | Oct 23, 2023 |
| Gigabyte      | MZBSWAP-00                  | [1d274146ba](https://linux-hardware.org/?probe=1d274146ba) | Oct 23, 2023 |
| Gigabyte      | G41MT-S2                    | [3df6a3e3e4](https://linux-hardware.org/?probe=3df6a3e3e4) | Oct 23, 2023 |
| Gigabyte      | GA-870A-UD3                 | [e0cffa70b5](https://linux-hardware.org/?probe=e0cffa70b5) | Oct 23, 2023 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [9bf87234d6](https://linux-hardware.org/?probe=9bf87234d6) | Oct 23, 2023 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [d1f56e838d](https://linux-hardware.org/?probe=d1f56e838d) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-K II            | [4123085fec](https://linux-hardware.org/?probe=4123085fec) | Oct 22, 2023 |
| ASUSTek       | P5KPL-SE                    | [2a58496283](https://linux-hardware.org/?probe=2a58496283) | Oct 22, 2023 |
| Gigabyte      | B450M DS3H V2               | [7c81d548d6](https://linux-hardware.org/?probe=7c81d548d6) | Oct 22, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7b963d7fff](https://linux-hardware.org/?probe=7b963d7fff) | Oct 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [53a0ed7609](https://linux-hardware.org/?probe=53a0ed7609) | Oct 21, 2023 |
| WinFast       | 761GXK8MC                   | [7b4f49eda5](https://linux-hardware.org/?probe=7b4f49eda5) | Oct 21, 2023 |
| ASRock        | D1800B-ITX                  | [c332512757](https://linux-hardware.org/?probe=c332512757) | Oct 21, 2023 |
| ASRock        | P45DE3                      | [2f9bd57442](https://linux-hardware.org/?probe=2f9bd57442) | Oct 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [57a08b87d8](https://linux-hardware.org/?probe=57a08b87d8) | Oct 21, 2023 |
| ASRock        | B650E PG Riptide WiFi       | [3c5e76a975](https://linux-hardware.org/?probe=3c5e76a975) | Oct 21, 2023 |
| ASRock        | H61M                        | [b58eae7b88](https://linux-hardware.org/?probe=b58eae7b88) | Oct 21, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [0748fa3430](https://linux-hardware.org/?probe=0748fa3430) | Oct 21, 2023 |
| Gigabyte      | 970A-DS3P                   | [10fab00c5f](https://linux-hardware.org/?probe=10fab00c5f) | Oct 21, 2023 |
| ASUSTek       | PRIME H410M-R               | [e5362858a0](https://linux-hardware.org/?probe=e5362858a0) | Oct 20, 2023 |
| ASUSTek       | PRIME H410M-R               | [01544384cc](https://linux-hardware.org/?probe=01544384cc) | Oct 20, 2023 |
| ASUSTek       | P8H77-M PRO                 | [968efc7996](https://linux-hardware.org/?probe=968efc7996) | Oct 20, 2023 |
| ASUSTek       | PRIME B450M-K               | [a0b48d8a7e](https://linux-hardware.org/?probe=a0b48d8a7e) | Oct 20, 2023 |
| ASRock        | A320M-HDV R4.0              | [17f5bf3cef](https://linux-hardware.org/?probe=17f5bf3cef) | Oct 20, 2023 |
| ASUSTek       | P7H55-M                     | [ad3f143871](https://linux-hardware.org/?probe=ad3f143871) | Oct 20, 2023 |
| MSI           | 760GM-P23                   | [77ee2b1957](https://linux-hardware.org/?probe=77ee2b1957) | Oct 20, 2023 |
| ASRock        | J3455M                      | [9e627ef04c](https://linux-hardware.org/?probe=9e627ef04c) | Oct 20, 2023 |
| MSI           | A320M-A PRO                 | [6290cec60c](https://linux-hardware.org/?probe=6290cec60c) | Oct 20, 2023 |
| MSI           | A320M-A PRO                 | [287fa14302](https://linux-hardware.org/?probe=287fa14302) | Oct 20, 2023 |
| MACHINIST     | X79 Z9-D7 V1.2              | [7ad6760006](https://linux-hardware.org/?probe=7ad6760006) | Oct 19, 2023 |
| Supermicro    | X10DDW-i                    | [7f765cc00f](https://linux-hardware.org/?probe=7f765cc00f) | Oct 19, 2023 |
| Supermicro    | X10DDW-i                    | [fbe57c97ea](https://linux-hardware.org/?probe=fbe57c97ea) | Oct 19, 2023 |
| Supermicro    | X10DRL-i                    | [3ff4f4f39b](https://linux-hardware.org/?probe=3ff4f4f39b) | Oct 19, 2023 |
| Supermicro    | X10DDW-i                    | [bc6515ee92](https://linux-hardware.org/?probe=bc6515ee92) | Oct 19, 2023 |
| Supermicro    | X10DDW-i                    | [2d8d01b0df](https://linux-hardware.org/?probe=2d8d01b0df) | Oct 19, 2023 |
| Supermicro    | X10DDW-i                    | [494b45d07d](https://linux-hardware.org/?probe=494b45d07d) | Oct 19, 2023 |
| Supermicro    | X10DRL-i                    | [f25155c26d](https://linux-hardware.org/?probe=f25155c26d) | Oct 19, 2023 |
| Supermicro    | X10DRL-i                    | [78fdf3830c](https://linux-hardware.org/?probe=78fdf3830c) | Oct 19, 2023 |
| MSI           | 760GM-P23                   | [5936be0473](https://linux-hardware.org/?probe=5936be0473) | Oct 19, 2023 |
| ASUSTek       | M5A78L-M LE                 | [3f5646fdfb](https://linux-hardware.org/?probe=3f5646fdfb) | Oct 19, 2023 |
| ASRock        | J3455M                      | [a65255a6ec](https://linux-hardware.org/?probe=a65255a6ec) | Oct 19, 2023 |
| Gigabyte      | B550M K                     | [2167b15aa8](https://linux-hardware.org/?probe=2167b15aa8) | Oct 19, 2023 |
| Gigabyte      | B75M-D3V                    | [0fd9732532](https://linux-hardware.org/?probe=0fd9732532) | Oct 19, 2023 |
| Gigabyte      | X58A-UD3R                   | [e5ecd53787](https://linux-hardware.org/?probe=e5ecd53787) | Oct 19, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [745f21d8bc](https://linux-hardware.org/?probe=745f21d8bc) | Oct 19, 2023 |
| Yadro         | YadroB560                   | [d231d3b930](https://linux-hardware.org/?probe=d231d3b930) | Oct 19, 2023 |
| ASUSTek       | P8H61-M LE                  | [4d8a513d99](https://linux-hardware.org/?probe=4d8a513d99) | Oct 19, 2023 |
| MSI           | H110M PRO-VD                | [d0664cf154](https://linux-hardware.org/?probe=d0664cf154) | Oct 19, 2023 |
| Lenovo        | 3708 NOK                    | [398302b1e5](https://linux-hardware.org/?probe=398302b1e5) | Oct 19, 2023 |
| Gigabyte      | B550M K                     | [05c587e8e0](https://linux-hardware.org/?probe=05c587e8e0) | Oct 18, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [6e17195f7d](https://linux-hardware.org/?probe=6e17195f7d) | Oct 18, 2023 |
| Gigabyte      | H510M H                     | [a0282a457d](https://linux-hardware.org/?probe=a0282a457d) | Oct 18, 2023 |
| Supermicro    | X10DDW-i                    | [b3685de812](https://linux-hardware.org/?probe=b3685de812) | Oct 18, 2023 |
| Supermicro    | X10DDW-i                    | [a84fa735c7](https://linux-hardware.org/?probe=a84fa735c7) | Oct 18, 2023 |
| MSI           | B360M PRO-VD                | [4d1cd49c1c](https://linux-hardware.org/?probe=4d1cd49c1c) | Oct 18, 2023 |
| Supermicro    | X10DRU-i+B                  | [f2e360b8e4](https://linux-hardware.org/?probe=f2e360b8e4) | Oct 18, 2023 |
| Supermicro    | X10DRU-i+A                  | [1245e9bcc8](https://linux-hardware.org/?probe=1245e9bcc8) | Oct 18, 2023 |
| Supermicro    | X9DRW                       | [c57bad94cc](https://linux-hardware.org/?probe=c57bad94cc) | Oct 18, 2023 |
| Gigabyte      | G31M-S2L                    | [4d40f6adef](https://linux-hardware.org/?probe=4d40f6adef) | Oct 18, 2023 |
| ASUSTek       | PRIME Z270-P                | [07d65e0ac6](https://linux-hardware.org/?probe=07d65e0ac6) | Oct 18, 2023 |
| Supermicro    | X10DRU-i+A                  | [8f574baa5b](https://linux-hardware.org/?probe=8f574baa5b) | Oct 18, 2023 |
| Gigabyte      | H310M S2 x.x                | [dd1f79a66a](https://linux-hardware.org/?probe=dd1f79a66a) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [3e5a5380d7](https://linux-hardware.org/?probe=3e5a5380d7) | Oct 18, 2023 |
| MACHINIST     | X79 Z9-D7 V1.2              | [bc7e7d2817](https://linux-hardware.org/?probe=bc7e7d2817) | Oct 17, 2023 |
| QBIC          | BXT-512-7100U               | [e23f579099](https://linux-hardware.org/?probe=e23f579099) | Oct 17, 2023 |
| MSI           | PRO X670-P WIFI             | [9d4c7bd9ba](https://linux-hardware.org/?probe=9d4c7bd9ba) | Oct 17, 2023 |
| MSI           | PRO X670-P WIFI             | [47378e3400](https://linux-hardware.org/?probe=47378e3400) | Oct 17, 2023 |
| Unknown       | Unknown                     | [9947f3f38b](https://linux-hardware.org/?probe=9947f3f38b) | Oct 17, 2023 |
| ASRock        | H510M-HVS R2.0              | [83c36787ea](https://linux-hardware.org/?probe=83c36787ea) | Oct 17, 2023 |
| Intel         | H81                         | [317de00832](https://linux-hardware.org/?probe=317de00832) | Oct 17, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a80532e1a0](https://linux-hardware.org/?probe=a80532e1a0) | Oct 17, 2023 |
| Gigabyte      | B360M DS3H                  | [cf5190078f](https://linux-hardware.org/?probe=cf5190078f) | Oct 17, 2023 |
| Unknown       | Unknown                     | [4e34e33eee](https://linux-hardware.org/?probe=4e34e33eee) | Oct 17, 2023 |
| Gigabyte      | B360M DS3H                  | [06e6e5db34](https://linux-hardware.org/?probe=06e6e5db34) | Oct 17, 2023 |
| Unknown       | Unknown                     | [fc0368a716](https://linux-hardware.org/?probe=fc0368a716) | Oct 17, 2023 |
| OEM           | X79G                        | [887a2b8f36](https://linux-hardware.org/?probe=887a2b8f36) | Oct 17, 2023 |
| HP            | 2820h                       | [73769961eb](https://linux-hardware.org/?probe=73769961eb) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | [66c28b84cf](https://linux-hardware.org/?probe=66c28b84cf) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | [982543f4bc](https://linux-hardware.org/?probe=982543f4bc) | Oct 16, 2023 |
| Gigabyte      | B450M S2H V2                | [72258458a5](https://linux-hardware.org/?probe=72258458a5) | Oct 16, 2023 |
| ASUSTek       | PRIME H510M-A               | [8f5d44a983](https://linux-hardware.org/?probe=8f5d44a983) | Oct 16, 2023 |
| MSI           | A520M-A PRO                 | [478d753363](https://linux-hardware.org/?probe=478d753363) | Oct 16, 2023 |
| ASUSTek       | PRIME H510M-A               | [bad56db313](https://linux-hardware.org/?probe=bad56db313) | Oct 16, 2023 |
| MSI           | B360M PRO-VD                | [98deafd70e](https://linux-hardware.org/?probe=98deafd70e) | Oct 15, 2023 |
| MSI           | H110M PRO-D                 | [14ad3343a7](https://linux-hardware.org/?probe=14ad3343a7) | Oct 15, 2023 |
| ASUSTek       | P5K PRO                     | [a4c386b42e](https://linux-hardware.org/?probe=a4c386b42e) | Oct 15, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [e040ec5e03](https://linux-hardware.org/?probe=e040ec5e03) | Oct 15, 2023 |
| ASUSTek       | P5K PRO                     | [aa244a1f00](https://linux-hardware.org/?probe=aa244a1f00) | Oct 15, 2023 |
| AZW           | MINI S                      | [0083fabd4c](https://linux-hardware.org/?probe=0083fabd4c) | Oct 15, 2023 |
| MSI           | PRO B660M-P DDR4            | [364fd8849a](https://linux-hardware.org/?probe=364fd8849a) | Oct 15, 2023 |
| ECS           | G31T-M                      | [8f11ce9a6a](https://linux-hardware.org/?probe=8f11ce9a6a) | Oct 15, 2023 |
| MSI           | X299 RAIDER                 | [28f37d6590](https://linux-hardware.org/?probe=28f37d6590) | Oct 14, 2023 |
| MSI           | 770-C45                     | [c1e11a6e3d](https://linux-hardware.org/?probe=c1e11a6e3d) | Oct 14, 2023 |
| Gigabyte      | EP43-DS3L                   | [7cc4c9f010](https://linux-hardware.org/?probe=7cc4c9f010) | Oct 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [6457a793cd](https://linux-hardware.org/?probe=6457a793cd) | Oct 14, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [8ee594360c](https://linux-hardware.org/?probe=8ee594360c) | Oct 14, 2023 |
| Gigabyte      | 970A-UD3P                   | [1d90e142fd](https://linux-hardware.org/?probe=1d90e142fd) | Oct 14, 2023 |
| Biostar       | H81MHV3 5.0                 | [11b853321a](https://linux-hardware.org/?probe=11b853321a) | Oct 14, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [a8e7e9b968](https://linux-hardware.org/?probe=a8e7e9b968) | Oct 14, 2023 |
| ASUSTek       | P5QD TURBO                  | [63c82d8692](https://linux-hardware.org/?probe=63c82d8692) | Oct 13, 2023 |
| Biostar       | H81MHV3 5.0                 | [9fdaa00358](https://linux-hardware.org/?probe=9fdaa00358) | Oct 13, 2023 |
| Unknown       | Unknown                     | [05b441657d](https://linux-hardware.org/?probe=05b441657d) | Oct 13, 2023 |
| Unknown       | HX90                        | [f247716ab0](https://linux-hardware.org/?probe=f247716ab0) | Oct 13, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [a654820b23](https://linux-hardware.org/?probe=a654820b23) | Oct 13, 2023 |
| ASRock        | H55M-LE                     | [db9ce33137](https://linux-hardware.org/?probe=db9ce33137) | Oct 13, 2023 |
| Gigabyte      | H510M H                     | [f5edac9c7d](https://linux-hardware.org/?probe=f5edac9c7d) | Oct 13, 2023 |
| Biostar       | H510MHP                     | [1de1d57c17](https://linux-hardware.org/?probe=1de1d57c17) | Oct 13, 2023 |
| ASUSTek       | H110M-R                     | [6b5ff499ec](https://linux-hardware.org/?probe=6b5ff499ec) | Oct 13, 2023 |
| Gigabyte      | H55M-USB3                   | [ba758fb431](https://linux-hardware.org/?probe=ba758fb431) | Oct 13, 2023 |
| Gigabyte      | A320M-S2H-CF                | [683a06d3a1](https://linux-hardware.org/?probe=683a06d3a1) | Oct 12, 2023 |
| MSI           | PRO H610M-B DDR4            | [5a954486f1](https://linux-hardware.org/?probe=5a954486f1) | Oct 12, 2023 |
| Intel         | X99 V3.0                    | [10d96ed192](https://linux-hardware.org/?probe=10d96ed192) | Oct 12, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [f39e659abb](https://linux-hardware.org/?probe=f39e659abb) | Oct 12, 2023 |
| MSI           | Z390-A PRO                  | [41ceddf203](https://linux-hardware.org/?probe=41ceddf203) | Oct 12, 2023 |
| Intel         | X99 V3.0                    | [e22c1235d0](https://linux-hardware.org/?probe=e22c1235d0) | Oct 12, 2023 |
| DEPO Compu... | DPA520S                     | [d6cf338b8c](https://linux-hardware.org/?probe=d6cf338b8c) | Oct 12, 2023 |
| Gigabyte      | B550M S2H                   | [fdcf79df44](https://linux-hardware.org/?probe=fdcf79df44) | Oct 12, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [b756b81d33](https://linux-hardware.org/?probe=b756b81d33) | Oct 12, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [8d4eefa612](https://linux-hardware.org/?probe=8d4eefa612) | Oct 12, 2023 |
| ASUSTek       | M2N68-AM SE2                | [398c921a7c](https://linux-hardware.org/?probe=398c921a7c) | Oct 11, 2023 |
| ASUSTek       | PRIME A320M-K               | [9af9d0ea5e](https://linux-hardware.org/?probe=9af9d0ea5e) | Oct 11, 2023 |
| Lenovo        | 317E NOK                    | [618b7ebe59](https://linux-hardware.org/?probe=618b7ebe59) | Oct 11, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [e185192929](https://linux-hardware.org/?probe=e185192929) | Oct 11, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d9183a2d23](https://linux-hardware.org/?probe=d9183a2d23) | Oct 11, 2023 |
| ASUSTek       | B85-PLUS                    | [62e3b0f03f](https://linux-hardware.org/?probe=62e3b0f03f) | Oct 11, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [f4bae74275](https://linux-hardware.org/?probe=f4bae74275) | Oct 11, 2023 |
| Acer          | Aspire XC-830               | [21a3b6601a](https://linux-hardware.org/?probe=21a3b6601a) | Oct 10, 2023 |
| Acer          | Aspire XC-830               | [c7453db83a](https://linux-hardware.org/?probe=c7453db83a) | Oct 10, 2023 |
| Unknown       | SpringdalePE                | [e29427ba94](https://linux-hardware.org/?probe=e29427ba94) | Oct 10, 2023 |
| MSI           | 785GM-E51                   | [6034bcda1d](https://linux-hardware.org/?probe=6034bcda1d) | Oct 10, 2023 |
| Lenovo        | 3752 NOK                    | [e3eda8aae7](https://linux-hardware.org/?probe=e3eda8aae7) | Oct 10, 2023 |
| Gigabyte      | H55M-USB3                   | [9bf81b8cb2](https://linux-hardware.org/?probe=9bf81b8cb2) | Oct 09, 2023 |
| Gigabyte      | GA-8S655FX-L                | [4c81a7a377](https://linux-hardware.org/?probe=4c81a7a377) | Oct 09, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [2c7e31eb6f](https://linux-hardware.org/?probe=2c7e31eb6f) | Oct 09, 2023 |
| ASUSTek       | Z170M-PLUS                  | [dc37b22fc2](https://linux-hardware.org/?probe=dc37b22fc2) | Oct 09, 2023 |
| ASUSTek       | M2A-VM                      | [ac2f8ef69c](https://linux-hardware.org/?probe=ac2f8ef69c) | Oct 09, 2023 |
| ASRock        | N68C-GS FX                  | [2da75b7afa](https://linux-hardware.org/?probe=2da75b7afa) | Oct 09, 2023 |
| ASUSTek       | P5KPL-AM IN/GB              | [a1db2cd9a7](https://linux-hardware.org/?probe=a1db2cd9a7) | Oct 09, 2023 |
| MSI           | Z87I                        | [6cd843a979](https://linux-hardware.org/?probe=6cd843a979) | Oct 09, 2023 |
| ASUSTek       | PRIME B450M-K               | [c21d708813](https://linux-hardware.org/?probe=c21d708813) | Oct 09, 2023 |
| Biostar       | A320MH                      | [9623471fc7](https://linux-hardware.org/?probe=9623471fc7) | Oct 09, 2023 |
| Gigabyte      | B450M K-CF                  | [4f495e0c37](https://linux-hardware.org/?probe=4f495e0c37) | Oct 09, 2023 |
| Gigabyte      | G41MT-S2P                   | [3988bb6847](https://linux-hardware.org/?probe=3988bb6847) | Oct 09, 2023 |
| ASRock        | H410M-HVS                   | [bf5a178b35](https://linux-hardware.org/?probe=bf5a178b35) | Oct 09, 2023 |
| Intel         | SKYBAY                      | [a501059141](https://linux-hardware.org/?probe=a501059141) | Oct 09, 2023 |
| ASUSTek       | M2A74-AM SE                 | [05c13f10df](https://linux-hardware.org/?probe=05c13f10df) | Oct 09, 2023 |
| Gigabyte      | B550M DS3H                  | [7070641150](https://linux-hardware.org/?probe=7070641150) | Oct 08, 2023 |
| Unknown       | Unknown                     | [27022c7042](https://linux-hardware.org/?probe=27022c7042) | Oct 08, 2023 |
| Pegatron      | 2A94h                       | [4c5ce13f3a](https://linux-hardware.org/?probe=4c5ce13f3a) | Oct 08, 2023 |
| ASRock        | N68C-GS FX                  | [67ebeba633](https://linux-hardware.org/?probe=67ebeba633) | Oct 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [b8d92e6419](https://linux-hardware.org/?probe=b8d92e6419) | Oct 08, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [bb515300c4](https://linux-hardware.org/?probe=bb515300c4) | Oct 08, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [e401b0c370](https://linux-hardware.org/?probe=e401b0c370) | Oct 07, 2023 |
| Biostar       | A58MD                       | [4a953dc846](https://linux-hardware.org/?probe=4a953dc846) | Oct 07, 2023 |
| Gigabyte      | 970A-DS3P                   | [5b05f29471](https://linux-hardware.org/?probe=5b05f29471) | Oct 07, 2023 |
| ASUSTek       | Leonite2                    | [67f5bc1c0a](https://linux-hardware.org/?probe=67f5bc1c0a) | Oct 07, 2023 |
| ASUSTek       | P7H55                       | [89472bd2f3](https://linux-hardware.org/?probe=89472bd2f3) | Oct 07, 2023 |
| Gigabyte      | H97-D3H-CF                  | [6f0b19f927](https://linux-hardware.org/?probe=6f0b19f927) | Oct 07, 2023 |
| Gigabyte      | B75M-D3V                    | [17cdd65d6b](https://linux-hardware.org/?probe=17cdd65d6b) | Oct 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | [75ceec744e](https://linux-hardware.org/?probe=75ceec744e) | Oct 07, 2023 |
| Gigabyte      | GA-K8NE                     | [8cb50a99b7](https://linux-hardware.org/?probe=8cb50a99b7) | Oct 07, 2023 |
| Huanan        | X99-BD4 V1.33               | [9477d90e51](https://linux-hardware.org/?probe=9477d90e51) | Oct 07, 2023 |
| Gigabyte      | F2A55M-DS2                  | [75d90cf644](https://linux-hardware.org/?probe=75d90cf644) | Oct 07, 2023 |
| ASUSTek       | P8H77-V LE                  | [0b38be8780](https://linux-hardware.org/?probe=0b38be8780) | Oct 06, 2023 |
| Huanan        | X99-TF GAMING V2.0          | [cab0ac17ec](https://linux-hardware.org/?probe=cab0ac17ec) | Oct 06, 2023 |
| MACHINIST     | E5-V2.82H V1.1              | [2a5bdb0b90](https://linux-hardware.org/?probe=2a5bdb0b90) | Oct 06, 2023 |
| Supermicro    | X9DRW                       | [e593458a23](https://linux-hardware.org/?probe=e593458a23) | Oct 06, 2023 |
| Supermicro    | X10DRL-i                    | [ef056af977](https://linux-hardware.org/?probe=ef056af977) | Oct 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [63087df172](https://linux-hardware.org/?probe=63087df172) | Oct 06, 2023 |
| ASUSTek       | Z87-PRO                     | [31248aa2bf](https://linux-hardware.org/?probe=31248aa2bf) | Oct 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | [37d9a6d75f](https://linux-hardware.org/?probe=37d9a6d75f) | Oct 06, 2023 |
| ASUSTek       | P8H77-V LE                  | [26a7af1326](https://linux-hardware.org/?probe=26a7af1326) | Oct 06, 2023 |
| Intel         | SKYBAY                      | [9f8bbc14f4](https://linux-hardware.org/?probe=9f8bbc14f4) | Oct 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [c2fcd9d06e](https://linux-hardware.org/?probe=c2fcd9d06e) | Oct 05, 2023 |
| Lenovo        | 3752 NOK                    | [5e3d37b336](https://linux-hardware.org/?probe=5e3d37b336) | Oct 05, 2023 |
| ECS           | H61H2-M13                   | [7a5404c2d6](https://linux-hardware.org/?probe=7a5404c2d6) | Oct 05, 2023 |
| Gigabyte      | X570 GAMING X               | [3f46a7499f](https://linux-hardware.org/?probe=3f46a7499f) | Oct 05, 2023 |
| Gigabyte      | GA-870A-UD3                 | [fca602c192](https://linux-hardware.org/?probe=fca602c192) | Oct 05, 2023 |
| AZW           | T4 PRO                      | [6d08ccbaf2](https://linux-hardware.org/?probe=6d08ccbaf2) | Oct 05, 2023 |
| AZW           | T4 PRO                      | [f435cc8ab2](https://linux-hardware.org/?probe=f435cc8ab2) | Oct 05, 2023 |
| ASUSTek       | PRIME B365M-C               | [81ab5fe3f3](https://linux-hardware.org/?probe=81ab5fe3f3) | Oct 04, 2023 |
| MSI           | P43 Neo-F                   | [4b19989894](https://linux-hardware.org/?probe=4b19989894) | Oct 04, 2023 |
| ASUSTek       | PRIME H510M-K               | [9483230f98](https://linux-hardware.org/?probe=9483230f98) | Oct 04, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [a3ea9b4b56](https://linux-hardware.org/?probe=a3ea9b4b56) | Oct 04, 2023 |
| ASUSTek       | P5K PRO                     | [2d4ce43693](https://linux-hardware.org/?probe=2d4ce43693) | Oct 04, 2023 |
| MSI           | P43 Neo-F                   | [c4e8261756](https://linux-hardware.org/?probe=c4e8261756) | Oct 04, 2023 |
| Gigabyte      | X570S AERO G                | [5ddc45085a](https://linux-hardware.org/?probe=5ddc45085a) | Oct 04, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | [a74a8b1c25](https://linux-hardware.org/?probe=a74a8b1c25) | Oct 04, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | [38db8e9cf2](https://linux-hardware.org/?probe=38db8e9cf2) | Oct 04, 2023 |
| ASUSTek       | PRIME Z270-P                | [207efb7a0a](https://linux-hardware.org/?probe=207efb7a0a) | Oct 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [ab02b2a3e7](https://linux-hardware.org/?probe=ab02b2a3e7) | Oct 04, 2023 |
| Unknown       | Unknown                     | [3493650868](https://linux-hardware.org/?probe=3493650868) | Oct 03, 2023 |
| ASUSTek       | P5K                         | [83eea396c1](https://linux-hardware.org/?probe=83eea396c1) | Oct 03, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | [88d950a0fc](https://linux-hardware.org/?probe=88d950a0fc) | Oct 03, 2023 |
| ECS           | H61H2-M13                   | [df2309fcb0](https://linux-hardware.org/?probe=df2309fcb0) | Oct 03, 2023 |
| ASUSTek       | PRIME H510M-K               | [62e437adf3](https://linux-hardware.org/?probe=62e437adf3) | Oct 03, 2023 |
| ASRock        | H110M-DGS R3.0              | [a8d8ab9d2c](https://linux-hardware.org/?probe=a8d8ab9d2c) | Oct 02, 2023 |
| MSI           | FM2-A55M-E33                | [ed22a192a5](https://linux-hardware.org/?probe=ed22a192a5) | Oct 02, 2023 |
| Biostar       | H510MHP                     | [1d6b309a9a](https://linux-hardware.org/?probe=1d6b309a9a) | Oct 02, 2023 |
| ASRock        | N68C-GS FX                  | [49d7edb011](https://linux-hardware.org/?probe=49d7edb011) | Oct 02, 2023 |
| ASUSTek       | P5K                         | [e8cf25ae85](https://linux-hardware.org/?probe=e8cf25ae85) | Oct 02, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | [e1f02a7f4f](https://linux-hardware.org/?probe=e1f02a7f4f) | Oct 02, 2023 |
| MSI           | Z170A TOMAHAWK              | [6f48b6d79c](https://linux-hardware.org/?probe=6f48b6d79c) | Oct 02, 2023 |
| Unknown       | X79                         | [64628cc08d](https://linux-hardware.org/?probe=64628cc08d) | Oct 01, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [0236b6af15](https://linux-hardware.org/?probe=0236b6af15) | Oct 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [7109a8a11b](https://linux-hardware.org/?probe=7109a8a11b) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [e9ec306962](https://linux-hardware.org/?probe=e9ec306962) | Oct 01, 2023 |
| Gigabyte      | 970A-D3                     | [9b47949b87](https://linux-hardware.org/?probe=9b47949b87) | Oct 01, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [cd4c3fb654](https://linux-hardware.org/?probe=cd4c3fb654) | Oct 01, 2023 |
| Huanan        | X99 F8D V2.2                | [50101ff8ee](https://linux-hardware.org/?probe=50101ff8ee) | Oct 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [b85781f0d8](https://linux-hardware.org/?probe=b85781f0d8) | Oct 01, 2023 |
| Gigabyte      | H61M-S2-B3                  | [447e04bd9d](https://linux-hardware.org/?probe=447e04bd9d) | Sep 30, 2023 |
| ECS           | G31T-M7                     | [0749fa9352](https://linux-hardware.org/?probe=0749fa9352) | Sep 30, 2023 |
| ASUSTek       | H110M-R                     | [b8aadf6823](https://linux-hardware.org/?probe=b8aadf6823) | Sep 30, 2023 |
| MSI           | 890FXA-GD70                 | [f9c2509bc6](https://linux-hardware.org/?probe=f9c2509bc6) | Sep 30, 2023 |
| Gigabyte      | G31M-S2L                    | [4f147c1f3a](https://linux-hardware.org/?probe=4f147c1f3a) | Sep 30, 2023 |
| Gigabyte      | G31M-S2L                    | [391af7c221](https://linux-hardware.org/?probe=391af7c221) | Sep 30, 2023 |
| ASUSTek       | P8H61-M LX2                 | [b2a213cc18](https://linux-hardware.org/?probe=b2a213cc18) | Sep 30, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [813b0bcb38](https://linux-hardware.org/?probe=813b0bcb38) | Sep 30, 2023 |
| ASUSTek       | P8H61-M LX2                 | [60e32143f5](https://linux-hardware.org/?probe=60e32143f5) | Sep 29, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | [7cc521d927](https://linux-hardware.org/?probe=7cc521d927) | Sep 29, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | [b952cdd71d](https://linux-hardware.org/?probe=b952cdd71d) | Sep 29, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [b34539564f](https://linux-hardware.org/?probe=b34539564f) | Sep 29, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [f79a27e406](https://linux-hardware.org/?probe=f79a27e406) | Sep 29, 2023 |
| Gigabyte      | H97-D3H-CF                  | [c0c34400ad](https://linux-hardware.org/?probe=c0c34400ad) | Sep 29, 2023 |
| ASRock        | H510M-HVS R2.0              | [f50b0e51d3](https://linux-hardware.org/?probe=f50b0e51d3) | Sep 29, 2023 |
| Wistron       | ProLiant ML110 G6           | [4284ef7737](https://linux-hardware.org/?probe=4284ef7737) | Sep 28, 2023 |
| Wistron       | ProLiant ML110 G6           | [6282804553](https://linux-hardware.org/?probe=6282804553) | Sep 28, 2023 |
| ASUSTek       | PRIME X470-PRO              | [1f420db3fd](https://linux-hardware.org/?probe=1f420db3fd) | Sep 28, 2023 |
| ASRock        | B450 Pro4 R2.0              | [82562e75c3](https://linux-hardware.org/?probe=82562e75c3) | Sep 28, 2023 |
| ASUSTek       | PRIME X370-PRO              | [872af2bc77](https://linux-hardware.org/?probe=872af2bc77) | Sep 28, 2023 |
| Gigabyte      | H410M H V3                  | [3a08b7188c](https://linux-hardware.org/?probe=3a08b7188c) | Sep 28, 2023 |
| Intel         | X99H                        | [d5390cf599](https://linux-hardware.org/?probe=d5390cf599) | Sep 28, 2023 |
| Pegatron      | IPMSB-H61                   | [d0e64d2ebf](https://linux-hardware.org/?probe=d0e64d2ebf) | Sep 28, 2023 |
| Gigabyte      | C1037UN-EU                  | [3a4cc5469a](https://linux-hardware.org/?probe=3a4cc5469a) | Sep 28, 2023 |
| Gigabyte      | C1037UN-EU                  | [1c2d4da0c6](https://linux-hardware.org/?probe=1c2d4da0c6) | Sep 27, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [1458dfe403](https://linux-hardware.org/?probe=1458dfe403) | Sep 27, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [cfc3a037ed](https://linux-hardware.org/?probe=cfc3a037ed) | Sep 27, 2023 |
| Huanan        | X99-BD4 V1.34, NALEX        | [493d23b3f0](https://linux-hardware.org/?probe=493d23b3f0) | Sep 27, 2023 |
| ASUSTek       | P5QD TURBO                  | [9e8a75e698](https://linux-hardware.org/?probe=9e8a75e698) | Sep 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | [e5cd50e4ea](https://linux-hardware.org/?probe=e5cd50e4ea) | Sep 27, 2023 |
| Gigabyte      | B85M-D3H                    | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| MSI           | H81M-P33                    | [8b0d086b89](https://linux-hardware.org/?probe=8b0d086b89) | Sep 27, 2023 |
| ASRock        | B450M Steel Legend          | [b4de4fe266](https://linux-hardware.org/?probe=b4de4fe266) | Sep 27, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [ef982a7d39](https://linux-hardware.org/?probe=ef982a7d39) | Sep 26, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d8f229b5d7](https://linux-hardware.org/?probe=d8f229b5d7) | Sep 26, 2023 |
| Supermicro    | X10DRL-i                    | [4215bb2639](https://linux-hardware.org/?probe=4215bb2639) | Sep 26, 2023 |
| ASUSTek       | H110M-K                     | [a067d2e97d](https://linux-hardware.org/?probe=a067d2e97d) | Sep 26, 2023 |
| ASUSTek       | P8B75-M LE                  | [96d214417d](https://linux-hardware.org/?probe=96d214417d) | Sep 26, 2023 |
| ASUSTek       | H110M-K                     | [74a379288b](https://linux-hardware.org/?probe=74a379288b) | Sep 26, 2023 |
| ASRock        | A320M-HDV R3.0              | [c8d5bce997](https://linux-hardware.org/?probe=c8d5bce997) | Sep 26, 2023 |
| DEPO Compu... | DPA520S                     | [45d07666f9](https://linux-hardware.org/?probe=45d07666f9) | Sep 26, 2023 |
| Intel         | DP35DP AAD81073-206         | [426e9aff0f](https://linux-hardware.org/?probe=426e9aff0f) | Sep 26, 2023 |
| MSI           | B450M-A PRO MAX             | [41f2aab706](https://linux-hardware.org/?probe=41f2aab706) | Sep 26, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [fc79d63b87](https://linux-hardware.org/?probe=fc79d63b87) | Sep 26, 2023 |
| Shenzhen M... | F7BFD                       | [a4891e1691](https://linux-hardware.org/?probe=a4891e1691) | Sep 25, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [977a189b29](https://linux-hardware.org/?probe=977a189b29) | Sep 25, 2023 |
| ASUSTek       | P6T DELUXE V2               | [a0fa16f85c](https://linux-hardware.org/?probe=a0fa16f85c) | Sep 25, 2023 |
| HP            | 8949 11                     | [acb62cff2b](https://linux-hardware.org/?probe=acb62cff2b) | Sep 25, 2023 |
| HP            | 2AF9                        | [0e6399ab05](https://linux-hardware.org/?probe=0e6399ab05) | Sep 25, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [85663cb9a6](https://linux-hardware.org/?probe=85663cb9a6) | Sep 25, 2023 |
| MSI           | FM2-A55M-E33                | [40ef9a86ab](https://linux-hardware.org/?probe=40ef9a86ab) | Sep 25, 2023 |
| Biostar       | B550MH                      | [4ef9bbad17](https://linux-hardware.org/?probe=4ef9bbad17) | Sep 24, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [57a4e724b8](https://linux-hardware.org/?probe=57a4e724b8) | Sep 24, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [945e2bc260](https://linux-hardware.org/?probe=945e2bc260) | Sep 24, 2023 |
| ASUSTek       | E520                        | [50ea664229](https://linux-hardware.org/?probe=50ea664229) | Sep 24, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [39e26bf376](https://linux-hardware.org/?probe=39e26bf376) | Sep 24, 2023 |
| Unknown       | Unknown                     | [7e1caa679f](https://linux-hardware.org/?probe=7e1caa679f) | Sep 24, 2023 |
| Unknown       | Unknown                     | [5a57428971](https://linux-hardware.org/?probe=5a57428971) | Sep 24, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [d17427680f](https://linux-hardware.org/?probe=d17427680f) | Sep 24, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [1c0c7815dd](https://linux-hardware.org/?probe=1c0c7815dd) | Sep 24, 2023 |
| ASRock        | H97 Anniversary             | [018c8fa4d1](https://linux-hardware.org/?probe=018c8fa4d1) | Sep 24, 2023 |
| MSI           | H110M PRO-VD PLUS           | [b8d1509801](https://linux-hardware.org/?probe=b8d1509801) | Sep 24, 2023 |
| Gigabyte      | G31M-ES2L                   | [bbf676f129](https://linux-hardware.org/?probe=bbf676f129) | Sep 24, 2023 |
| Gigabyte      | H61M-D2-B3                  | [90bdd8a3e6](https://linux-hardware.org/?probe=90bdd8a3e6) | Sep 23, 2023 |
| Gigabyte      | H61M-D2-B3                  | [41dba827f2](https://linux-hardware.org/?probe=41dba827f2) | Sep 23, 2023 |
| ASUSTek       | Z97-C                       | [e4c1f075b9](https://linux-hardware.org/?probe=e4c1f075b9) | Sep 23, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [17963d3a87](https://linux-hardware.org/?probe=17963d3a87) | Sep 23, 2023 |
| Gigabyte      | H110-D3-CF                  | [0762df27f4](https://linux-hardware.org/?probe=0762df27f4) | Sep 23, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [e3023f5f8c](https://linux-hardware.org/?probe=e3023f5f8c) | Sep 23, 2023 |
| ASUSTek       | PRIME X370-PRO              | [1f987f4720](https://linux-hardware.org/?probe=1f987f4720) | Sep 23, 2023 |
| MSI           | B460M PRO-VDH               | [c5429120bb](https://linux-hardware.org/?probe=c5429120bb) | Sep 23, 2023 |
| ASUSTek       | H81M-A                      | [09ce373b34](https://linux-hardware.org/?probe=09ce373b34) | Sep 22, 2023 |
| Gigabyte      | H61M-DS2H                   | [f3e31ed154](https://linux-hardware.org/?probe=f3e31ed154) | Sep 22, 2023 |
| Gigabyte      | P43-ES3G                    | [79557b8229](https://linux-hardware.org/?probe=79557b8229) | Sep 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [a9f9ccb4f9](https://linux-hardware.org/?probe=a9f9ccb4f9) | Sep 22, 2023 |
| Gigabyte      | H87M-HD3                    | [f5fead6eb4](https://linux-hardware.org/?probe=f5fead6eb4) | Sep 22, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [85c3791741](https://linux-hardware.org/?probe=85c3791741) | Sep 21, 2023 |
| ASRock        | A320M-DVS R4.0              | [893ef72c0c](https://linux-hardware.org/?probe=893ef72c0c) | Sep 21, 2023 |
| ASRock        | A520M-ITX/ac                | [35be6167f1](https://linux-hardware.org/?probe=35be6167f1) | Sep 21, 2023 |
| Biostar       | A68MHE                      | [8ab720b66b](https://linux-hardware.org/?probe=8ab720b66b) | Sep 21, 2023 |
| Gigabyte      | GA-E350N-USB3               | [b9a29448e1](https://linux-hardware.org/?probe=b9a29448e1) | Sep 21, 2023 |
| HP            | 2820h                       | [cd402f5dad](https://linux-hardware.org/?probe=cd402f5dad) | Sep 21, 2023 |
| Unknown       | Unknown                     | [339f506aa1](https://linux-hardware.org/?probe=339f506aa1) | Sep 21, 2023 |
| Gigabyte      | B360M D3H-CF                | [875f4f3f2a](https://linux-hardware.org/?probe=875f4f3f2a) | Sep 21, 2023 |
| ASUSTek       | E520                        | [f5be06ecdb](https://linux-hardware.org/?probe=f5be06ecdb) | Sep 21, 2023 |
| Gigabyte      | B560M DS3H V2               | [182384fdaa](https://linux-hardware.org/?probe=182384fdaa) | Sep 20, 2023 |
| Shenzhen M... | F7BFD                       | [b898184916](https://linux-hardware.org/?probe=b898184916) | Sep 20, 2023 |
| iEi           | SAT3 V1.03                  | [d303736416](https://linux-hardware.org/?probe=d303736416) | Sep 20, 2023 |
| ASUSTek       | P7H55-M SI                  | [26648aff1a](https://linux-hardware.org/?probe=26648aff1a) | Sep 20, 2023 |
| HP            | 3048h                       | [f140c33d20](https://linux-hardware.org/?probe=f140c33d20) | Sep 20, 2023 |
| ASRock        | N68C-GS FX                  | [7c54afbcbd](https://linux-hardware.org/?probe=7c54afbcbd) | Sep 20, 2023 |
| ASRock        | H310CM-ITX/ac               | [4959eecff1](https://linux-hardware.org/?probe=4959eecff1) | Sep 19, 2023 |
| Gigabyte      | H81M-DS2                    | [85d35b008d](https://linux-hardware.org/?probe=85d35b008d) | Sep 19, 2023 |
| ASUSTek       | P8H61-M LE                  | [7f04e1eefd](https://linux-hardware.org/?probe=7f04e1eefd) | Sep 19, 2023 |
| MSI           | A320M-A PRO                 | [03da63d741](https://linux-hardware.org/?probe=03da63d741) | Sep 19, 2023 |
| ASUSTek       | H81M-K                      | [6735d18449](https://linux-hardware.org/?probe=6735d18449) | Sep 19, 2023 |
| Supermicro    | X9DRW                       | [6f4a97a40b](https://linux-hardware.org/?probe=6f4a97a40b) | Sep 19, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [2666cd8dbe](https://linux-hardware.org/?probe=2666cd8dbe) | Sep 19, 2023 |
| ASRock        | FM2A78 Pro4+                | [cad8cdf94c](https://linux-hardware.org/?probe=cad8cdf94c) | Sep 19, 2023 |
| Gigabyte      | 970A-DS3P                   | [0ddcc2944f](https://linux-hardware.org/?probe=0ddcc2944f) | Sep 19, 2023 |
| AZW           | GTR V02                     | [094b661573](https://linux-hardware.org/?probe=094b661573) | Sep 18, 2023 |
| Unknown       | DMB-A520-MCA01              | [a959513e7c](https://linux-hardware.org/?probe=a959513e7c) | Sep 18, 2023 |
| MSI           | MS-7366                     | [96731b6fc6](https://linux-hardware.org/?probe=96731b6fc6) | Sep 18, 2023 |
| ASUSTek       | J1800I-C                    | [970e148d8d](https://linux-hardware.org/?probe=970e148d8d) | Sep 18, 2023 |
| MSI           | H81M-P33                    | [d0287bbd0f](https://linux-hardware.org/?probe=d0287bbd0f) | Sep 18, 2023 |
| ASRock        | B450M-HDV R4.0              | [e517de2d8f](https://linux-hardware.org/?probe=e517de2d8f) | Sep 18, 2023 |
| Gigabyte      | H410M H V3                  | [cdb4402859](https://linux-hardware.org/?probe=cdb4402859) | Sep 18, 2023 |
| ASUSTek       | P5GC-MX/1333                | [232bd09926](https://linux-hardware.org/?probe=232bd09926) | Sep 17, 2023 |
| Lenovo        | H420                        | [3cb3765e4c](https://linux-hardware.org/?probe=3cb3765e4c) | Sep 17, 2023 |
| MSI           | B450M MORTAR MAX            | [beaa4e5554](https://linux-hardware.org/?probe=beaa4e5554) | Sep 17, 2023 |
| Supermicro    | X9DR3-F                     | [c2f0532df1](https://linux-hardware.org/?probe=c2f0532df1) | Sep 17, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [b07ec8f845](https://linux-hardware.org/?probe=b07ec8f845) | Sep 17, 2023 |
| Unknown       | Unknown                     | [bd72d25583](https://linux-hardware.org/?probe=bd72d25583) | Sep 17, 2023 |
| MSI           | B460M-A PRO                 | [b2d52a5d1c](https://linux-hardware.org/?probe=b2d52a5d1c) | Sep 16, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [12b833e456](https://linux-hardware.org/?probe=12b833e456) | Sep 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [0f3cba16d7](https://linux-hardware.org/?probe=0f3cba16d7) | Sep 16, 2023 |
| Gigabyte      | EP45T-DS3                   | [0e22b4fe1d](https://linux-hardware.org/?probe=0e22b4fe1d) | Sep 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [bef465f035](https://linux-hardware.org/?probe=bef465f035) | Sep 16, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [c63f4e5865](https://linux-hardware.org/?probe=c63f4e5865) | Sep 16, 2023 |
| Unknown       | Unknown                     | [ce7fc75838](https://linux-hardware.org/?probe=ce7fc75838) | Sep 15, 2023 |
| Supermicro    | X10DRU-i+A                  | [d0cee7fa36](https://linux-hardware.org/?probe=d0cee7fa36) | Sep 15, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [b6a802c0ac](https://linux-hardware.org/?probe=b6a802c0ac) | Sep 15, 2023 |
| MSI           | A520M-A PRO                 | [d97b8e1ce0](https://linux-hardware.org/?probe=d97b8e1ce0) | Sep 15, 2023 |
| Gigabyte      | B450 AORUS M                | [119acd8c0d](https://linux-hardware.org/?probe=119acd8c0d) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [2f12035902](https://linux-hardware.org/?probe=2f12035902) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [c46a08bb48](https://linux-hardware.org/?probe=c46a08bb48) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [aa351597ea](https://linux-hardware.org/?probe=aa351597ea) | Sep 15, 2023 |
| Gigabyte      | H110M-H-CF                  | [5eadb71ae4](https://linux-hardware.org/?probe=5eadb71ae4) | Sep 15, 2023 |
| ASUSTek       | M3A78-CM                    | [5a47ad5c25](https://linux-hardware.org/?probe=5a47ad5c25) | Sep 15, 2023 |
| ASUSTek       | M3A78-CM                    | [876175ae24](https://linux-hardware.org/?probe=876175ae24) | Sep 15, 2023 |
| Gigabyte      | H55M-USB3                   | [6cf3ece600](https://linux-hardware.org/?probe=6cf3ece600) | Sep 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [3b3ba64d46](https://linux-hardware.org/?probe=3b3ba64d46) | Sep 14, 2023 |
| Gigabyte      | H61M-S1                     | [40ffb44424](https://linux-hardware.org/?probe=40ffb44424) | Sep 14, 2023 |
| ASRock        | N68-S3 UCC                  | [4164e2d7c7](https://linux-hardware.org/?probe=4164e2d7c7) | Sep 14, 2023 |
| Gigabyte      | B450 AORUS M                | [9b3fc9218b](https://linux-hardware.org/?probe=9b3fc9218b) | Sep 14, 2023 |
| ASUSTek       | B75M-PLUS                   | [6cc800f5dc](https://linux-hardware.org/?probe=6cc800f5dc) | Sep 14, 2023 |
| ASUSTek       | PRIME H510M-A               | [b66654e80e](https://linux-hardware.org/?probe=b66654e80e) | Sep 14, 2023 |
| ASRock        | B450 Pro4                   | [b961eae623](https://linux-hardware.org/?probe=b961eae623) | Sep 14, 2023 |
| ASRock        | B650M PG Riptide            | [3a1c100a69](https://linux-hardware.org/?probe=3a1c100a69) | Sep 14, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [3c09b49188](https://linux-hardware.org/?probe=3c09b49188) | Sep 14, 2023 |
| Intel         | DH87MC AAG74242-401         | [6c37cc0b51](https://linux-hardware.org/?probe=6c37cc0b51) | Sep 14, 2023 |
| MSI           | PRO H610M-G DDR4            | [33f52069d5](https://linux-hardware.org/?probe=33f52069d5) | Sep 13, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [5923e88c3b](https://linux-hardware.org/?probe=5923e88c3b) | Sep 13, 2023 |
| Supermicro    | X10DRU-i+B                  | [3650d44342](https://linux-hardware.org/?probe=3650d44342) | Sep 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [904a4a7d23](https://linux-hardware.org/?probe=904a4a7d23) | Sep 13, 2023 |
| Acer          | Veriton X275                | [6dcd8b863a](https://linux-hardware.org/?probe=6dcd8b863a) | Sep 13, 2023 |
| Unknown       | Unknown                     | [2035ddd158](https://linux-hardware.org/?probe=2035ddd158) | Sep 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [d178c2211b](https://linux-hardware.org/?probe=d178c2211b) | Sep 13, 2023 |
| ASRock        | X470 Taichi                 | [49aca37979](https://linux-hardware.org/?probe=49aca37979) | Sep 13, 2023 |
| ASUSTek       | H110M-R                     | [3530c6e606](https://linux-hardware.org/?probe=3530c6e606) | Sep 13, 2023 |
| ASUSTek       | PRIME X570-PRO              | [746f94b75d](https://linux-hardware.org/?probe=746f94b75d) | Sep 13, 2023 |
| ASRock        | K10N78D                     | [fa2852026b](https://linux-hardware.org/?probe=fa2852026b) | Sep 13, 2023 |
| ASRock        | K10N78D                     | [adf8e09915](https://linux-hardware.org/?probe=adf8e09915) | Sep 13, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [035fb7f099](https://linux-hardware.org/?probe=035fb7f099) | Sep 13, 2023 |
| Supermicro    | X11SSH-F                    | [3a9630bdc5](https://linux-hardware.org/?probe=3a9630bdc5) | Sep 13, 2023 |
| Lenovo        | BRASWELL NOK                | [621f570151](https://linux-hardware.org/?probe=621f570151) | Sep 13, 2023 |
| ASRock        | E350M1                      | [49c94468cf](https://linux-hardware.org/?probe=49c94468cf) | Sep 13, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [279517882b](https://linux-hardware.org/?probe=279517882b) | Sep 13, 2023 |
| Gigabyte      | G1.Assassin                 | [4b60be7fca](https://linux-hardware.org/?probe=4b60be7fca) | Sep 12, 2023 |
| Gigabyte      | A520M AORUS ELITE           | [05ac023ab9](https://linux-hardware.org/?probe=05ac023ab9) | Sep 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d8747ce048](https://linux-hardware.org/?probe=d8747ce048) | Sep 12, 2023 |
| Dell          | 0J190T A01                  | [b14e059cea](https://linux-hardware.org/?probe=b14e059cea) | Sep 12, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [e6879c5a23](https://linux-hardware.org/?probe=e6879c5a23) | Sep 12, 2023 |
| MSI           | H510M-A PRO                 | [f1a2a6d936](https://linux-hardware.org/?probe=f1a2a6d936) | Sep 12, 2023 |
| Gigabyte      | GA-870A-UD3                 | [b3acd03fb0](https://linux-hardware.org/?probe=b3acd03fb0) | Sep 12, 2023 |
| Biostar       | TF570 SLI A2+               | [718a7467d0](https://linux-hardware.org/?probe=718a7467d0) | Sep 12, 2023 |
| ASUSTek       | PRIME X570-P                | [efc20753cd](https://linux-hardware.org/?probe=efc20753cd) | Sep 12, 2023 |
| ASUSTek       | PRIME X570-P                | [c6f2b822c7](https://linux-hardware.org/?probe=c6f2b822c7) | Sep 12, 2023 |
| MSI           | 785GT-E63                   | [ac5b6e8a67](https://linux-hardware.org/?probe=ac5b6e8a67) | Sep 12, 2023 |
| Gigabyte      | H77N-WIFI                   | [fe040c7510](https://linux-hardware.org/?probe=fe040c7510) | Sep 12, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [53cdc3e4f0](https://linux-hardware.org/?probe=53cdc3e4f0) | Sep 12, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [d7b21557f8](https://linux-hardware.org/?probe=d7b21557f8) | Sep 12, 2023 |
| Gigabyte      | EP45-UD3LR                  | [7dc196091d](https://linux-hardware.org/?probe=7dc196091d) | Sep 12, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [b99104eeb7](https://linux-hardware.org/?probe=b99104eeb7) | Sep 11, 2023 |
| Intel         | H81 V2.3                    | [0673e1f5ed](https://linux-hardware.org/?probe=0673e1f5ed) | Sep 11, 2023 |
| ASRock        | B560M-HDV                   | [4df04c540a](https://linux-hardware.org/?probe=4df04c540a) | Sep 11, 2023 |
| Gigabyte      | M68MT-S2                    | [cb129260e1](https://linux-hardware.org/?probe=cb129260e1) | Sep 11, 2023 |
| ECS           | G31T-M9                     | [9d2ba7fe88](https://linux-hardware.org/?probe=9d2ba7fe88) | Sep 11, 2023 |
| Gigabyte      | GA-M56S-S3                  | [df2602c134](https://linux-hardware.org/?probe=df2602c134) | Sep 11, 2023 |
| ASUSTek       | P5KPL-AM                    | [3f55a69040](https://linux-hardware.org/?probe=3f55a69040) | Sep 11, 2023 |
| Intel         | H81                         | [9844243c1a](https://linux-hardware.org/?probe=9844243c1a) | Sep 11, 2023 |
| Intel         | SKYBAY                      | [63b6f62eae](https://linux-hardware.org/?probe=63b6f62eae) | Sep 11, 2023 |
| ASUSTek       | PRIME H410M-R               | [962fd46c5c](https://linux-hardware.org/?probe=962fd46c5c) | Sep 11, 2023 |
| Unknown       | X79A                        | [96d6dc2e5d](https://linux-hardware.org/?probe=96d6dc2e5d) | Sep 10, 2023 |
| ASRock        | H110M-DVS R3.0              | [b0305f4ba4](https://linux-hardware.org/?probe=b0305f4ba4) | Sep 10, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [5cb754a533](https://linux-hardware.org/?probe=5cb754a533) | Sep 10, 2023 |
| ASUSTek       | PRIME H310M-K               | [a17cc2a1d2](https://linux-hardware.org/?probe=a17cc2a1d2) | Sep 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [e49a8302ef](https://linux-hardware.org/?probe=e49a8302ef) | Sep 10, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [91b6565880](https://linux-hardware.org/?probe=91b6565880) | Sep 09, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [b3957e19eb](https://linux-hardware.org/?probe=b3957e19eb) | Sep 09, 2023 |
| ASUSTek       | H81M-E                      | [4bb36bc968](https://linux-hardware.org/?probe=4bb36bc968) | Sep 09, 2023 |
| ASUSTek       | P8H61-MX                    | [be54d62e88](https://linux-hardware.org/?probe=be54d62e88) | Sep 09, 2023 |
| ASUSTek       | P8H61-MX                    | [f9568de8f3](https://linux-hardware.org/?probe=f9568de8f3) | Sep 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [099e89d09f](https://linux-hardware.org/?probe=099e89d09f) | Sep 08, 2023 |
| Unknown       | Unknown                     | [72447e3c4b](https://linux-hardware.org/?probe=72447e3c4b) | Sep 08, 2023 |
| ASUSTek       | Pro H610T D4                | [ebced0bee8](https://linux-hardware.org/?probe=ebced0bee8) | Sep 08, 2023 |
| ASRock        | H510M-HVS R2.0              | [018a3b8abe](https://linux-hardware.org/?probe=018a3b8abe) | Sep 08, 2023 |
| MSI           | 760GA-P43                   | [b067d69499](https://linux-hardware.org/?probe=b067d69499) | Sep 08, 2023 |
| Supermicro    | X10DRU-i+A                  | [abdec86bab](https://linux-hardware.org/?probe=abdec86bab) | Sep 07, 2023 |
| ASUSTek       | B75M-PLUS                   | [394dd17b98](https://linux-hardware.org/?probe=394dd17b98) | Sep 07, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [881837a1cb](https://linux-hardware.org/?probe=881837a1cb) | Sep 07, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [7684d60e85](https://linux-hardware.org/?probe=7684d60e85) | Sep 07, 2023 |
| ASUSTek       | P8H77-V LE                  | [38ebaae5c3](https://linux-hardware.org/?probe=38ebaae5c3) | Sep 07, 2023 |
| Gigabyte      | Z790 UD                     | [3f67617c93](https://linux-hardware.org/?probe=3f67617c93) | Sep 07, 2023 |
| Gigabyte      | H610M S2 V2 DDR4            | [7323821425](https://linux-hardware.org/?probe=7323821425) | Sep 07, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [ade0754252](https://linux-hardware.org/?probe=ade0754252) | Sep 07, 2023 |
| Biostar       | A320MH                      | [87ae9fef79](https://linux-hardware.org/?probe=87ae9fef79) | Sep 07, 2023 |
| Acer          | Veriton X2640G V:1.0        | [76b044add6](https://linux-hardware.org/?probe=76b044add6) | Sep 07, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [67934ce24a](https://linux-hardware.org/?probe=67934ce24a) | Sep 07, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [43fa75d035](https://linux-hardware.org/?probe=43fa75d035) | Sep 07, 2023 |
| Biostar       | B550M-SILVER                | [12ad2e157b](https://linux-hardware.org/?probe=12ad2e157b) | Sep 07, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d095848fec](https://linux-hardware.org/?probe=d095848fec) | Sep 06, 2023 |
| ASRock        | Z68 Pro3                    | [757ebbe056](https://linux-hardware.org/?probe=757ebbe056) | Sep 06, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [ffe10aadbe](https://linux-hardware.org/?probe=ffe10aadbe) | Sep 06, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [48cc912b75](https://linux-hardware.org/?probe=48cc912b75) | Sep 06, 2023 |
| Lenovo        | H420                        | [f84aae6411](https://linux-hardware.org/?probe=f84aae6411) | Sep 06, 2023 |
| Lenovo        | 3708 NOK                    | [153f0dfa9d](https://linux-hardware.org/?probe=153f0dfa9d) | Sep 06, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [5ba13c092c](https://linux-hardware.org/?probe=5ba13c092c) | Sep 06, 2023 |
| Gigabyte      | H61M-S2PV                   | [c22fad9c67](https://linux-hardware.org/?probe=c22fad9c67) | Sep 06, 2023 |
| MSI           | MS-B0A41                    | [c93409061c](https://linux-hardware.org/?probe=c93409061c) | Sep 06, 2023 |
| Supermicro    | X9DRW                       | [01d640708d](https://linux-hardware.org/?probe=01d640708d) | Sep 06, 2023 |
| Gigabyte      | H410M H V3                  | [c7bdf1cee6](https://linux-hardware.org/?probe=c7bdf1cee6) | Sep 06, 2023 |
| MSI           | B550-A PRO                  | [4a5a98638e](https://linux-hardware.org/?probe=4a5a98638e) | Sep 06, 2023 |
| ASRock        | Z690 PG Velocita            | [0064d9d9e2](https://linux-hardware.org/?probe=0064d9d9e2) | Sep 06, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [1c8b9eed31](https://linux-hardware.org/?probe=1c8b9eed31) | Sep 06, 2023 |
| Biostar       | A68MHE                      | [65bd192bf0](https://linux-hardware.org/?probe=65bd192bf0) | Sep 06, 2023 |
| Gigabyte      | B550M S2H                   | [54556adb0b](https://linux-hardware.org/?probe=54556adb0b) | Sep 05, 2023 |
| ECS           | A740GM-M                    | [132b141a7d](https://linux-hardware.org/?probe=132b141a7d) | Sep 05, 2023 |
| Gigabyte      | F2A85X-UP4                  | [9c7d201848](https://linux-hardware.org/?probe=9c7d201848) | Sep 05, 2023 |
| ASRock        | A320M-HDV R4.0              | [0f5597eb7e](https://linux-hardware.org/?probe=0f5597eb7e) | Sep 05, 2023 |
| Foxconn       | 2ABF                        | [baad816533](https://linux-hardware.org/?probe=baad816533) | Sep 05, 2023 |
| ASRock        | X670E Steel Legend          | [8bca1f8244](https://linux-hardware.org/?probe=8bca1f8244) | Sep 05, 2023 |
| Intel         | DP43TF AAE34878-404         | [d83ba68fcb](https://linux-hardware.org/?probe=d83ba68fcb) | Sep 05, 2023 |
| Biostar       | A68MHE                      | [65a3d0ff34](https://linux-hardware.org/?probe=65a3d0ff34) | Sep 05, 2023 |
| ASRock        | B450M Pro4-F R2.0           | [3eef4ac5d3](https://linux-hardware.org/?probe=3eef4ac5d3) | Sep 05, 2023 |
| Gigabyte      | EP31-DS3L                   | [bce72e53fa](https://linux-hardware.org/?probe=bce72e53fa) | Sep 04, 2023 |
| HP            | 8526 MVB, A                 | [3133ab688e](https://linux-hardware.org/?probe=3133ab688e) | Sep 04, 2023 |
| MACHINIST     | X99-K9 V2.0                 | [3462791aa1](https://linux-hardware.org/?probe=3462791aa1) | Sep 04, 2023 |
| OEM           | Intel H81                   | [649a092684](https://linux-hardware.org/?probe=649a092684) | Sep 04, 2023 |
| ASRock        | 960GM-VGS3 FX               | [c3059a2ebc](https://linux-hardware.org/?probe=c3059a2ebc) | Sep 04, 2023 |
| MSI           | B360M MORTAR                | [d023a05e0b](https://linux-hardware.org/?probe=d023a05e0b) | Sep 04, 2023 |
| Foxconn       | 2ABF                        | [8928cdbfa8](https://linux-hardware.org/?probe=8928cdbfa8) | Sep 04, 2023 |
| ASUSTek       | Leonite2                    | [543ae5c1f3](https://linux-hardware.org/?probe=543ae5c1f3) | Sep 04, 2023 |
| ASUSTek       | Leonite2                    | [cb59b205d9](https://linux-hardware.org/?probe=cb59b205d9) | Sep 04, 2023 |
| ASRock        | 970 Pro3 R2.0               | [590b5224d9](https://linux-hardware.org/?probe=590b5224d9) | Sep 04, 2023 |
| MSI           | B360M MORTAR ILYA MUROME... | [0899e4058a](https://linux-hardware.org/?probe=0899e4058a) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [0eff1074a1](https://linux-hardware.org/?probe=0eff1074a1) | Sep 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c5ffec4746](https://linux-hardware.org/?probe=c5ffec4746) | Sep 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d8b388ed5f](https://linux-hardware.org/?probe=d8b388ed5f) | Sep 03, 2023 |
| ASRock        | FM2A78M-HD+                 | [a2d8c14a71](https://linux-hardware.org/?probe=a2d8c14a71) | Sep 03, 2023 |
| ASRock        | A320D4-P1                   | [244c92966f](https://linux-hardware.org/?probe=244c92966f) | Sep 03, 2023 |
| ASUSTek       | H97M-E                      | [6624329e1c](https://linux-hardware.org/?probe=6624329e1c) | Sep 03, 2023 |
| Gigabyte      | GA-780T-D3L                 | [f0c5bbc0c1](https://linux-hardware.org/?probe=f0c5bbc0c1) | Sep 03, 2023 |
| ASUSTek       | M2N                         | [1df62dde56](https://linux-hardware.org/?probe=1df62dde56) | Sep 03, 2023 |
| MSI           | 770-C45                     | [002c1856c6](https://linux-hardware.org/?probe=002c1856c6) | Sep 03, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [6b33c9cb36](https://linux-hardware.org/?probe=6b33c9cb36) | Sep 02, 2023 |
| MSI           | MAG B550M MORTAR            | [3ee4e0f848](https://linux-hardware.org/?probe=3ee4e0f848) | Sep 02, 2023 |
| ASUSTek       | P7P55-M                     | [c74782636f](https://linux-hardware.org/?probe=c74782636f) | Sep 02, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [1b5109eb83](https://linux-hardware.org/?probe=1b5109eb83) | Sep 02, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [48c352470d](https://linux-hardware.org/?probe=48c352470d) | Sep 02, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [3ea725d275](https://linux-hardware.org/?probe=3ea725d275) | Sep 02, 2023 |
| ASRock        | Z370M Pro4                  | [b50da6446a](https://linux-hardware.org/?probe=b50da6446a) | Sep 02, 2023 |
| Gigabyte      | H510M H                     | [1aeb1ffd17](https://linux-hardware.org/?probe=1aeb1ffd17) | Sep 02, 2023 |
| Foxconn       | 45CS                        | [56c503e42c](https://linux-hardware.org/?probe=56c503e42c) | Sep 02, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [91d7a53a1b](https://linux-hardware.org/?probe=91d7a53a1b) | Sep 01, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [1e51610ea3](https://linux-hardware.org/?probe=1e51610ea3) | Sep 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [238b7ca83d](https://linux-hardware.org/?probe=238b7ca83d) | Sep 01, 2023 |
| Huanan        | X99-QD4 V1.0                | [45c37720b0](https://linux-hardware.org/?probe=45c37720b0) | Sep 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | [52911d341d](https://linux-hardware.org/?probe=52911d341d) | Sep 01, 2023 |
| ASRock        | N68-GS4 FX                  | [87f94b4ba7](https://linux-hardware.org/?probe=87f94b4ba7) | Sep 01, 2023 |
| ASUSTek       | N3050T                      | [fa4b0cbf08](https://linux-hardware.org/?probe=fa4b0cbf08) | Sep 01, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [dd5735f315](https://linux-hardware.org/?probe=dd5735f315) | Sep 01, 2023 |
| Acer          | Veriton N4660G              | [25339d5009](https://linux-hardware.org/?probe=25339d5009) | Aug 31, 2023 |
| Gigabyte      | B450M K-CF                  | [2086d348b2](https://linux-hardware.org/?probe=2086d348b2) | Aug 31, 2023 |
| Intel         | B75                         | [55695d0962](https://linux-hardware.org/?probe=55695d0962) | Aug 31, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [a829cc0dce](https://linux-hardware.org/?probe=a829cc0dce) | Aug 31, 2023 |
| ASUSTek       | P5Q SE2                     | [293c912276](https://linux-hardware.org/?probe=293c912276) | Aug 31, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [9cb322dda0](https://linux-hardware.org/?probe=9cb322dda0) | Aug 30, 2023 |
| Supermicro    | X9DRW                       | [a71700e059](https://linux-hardware.org/?probe=a71700e059) | Aug 30, 2023 |
| MSI           | H510M-A PRO                 | [afb724c8da](https://linux-hardware.org/?probe=afb724c8da) | Aug 30, 2023 |
| ASUSTek       | P8H61 EVO                   | [facd465366](https://linux-hardware.org/?probe=facd465366) | Aug 30, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [d4f09e50b2](https://linux-hardware.org/?probe=d4f09e50b2) | Aug 30, 2023 |
| Gigabyte      | B450M H                     | [cd7bf0b2db](https://linux-hardware.org/?probe=cd7bf0b2db) | Aug 30, 2023 |
| MSI           | A68HM-P33 V2                | [44d09f93c9](https://linux-hardware.org/?probe=44d09f93c9) | Aug 30, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [91d3472ba6](https://linux-hardware.org/?probe=91d3472ba6) | Aug 30, 2023 |
| Gigabyte      | 970A-DS3P                   | [3eb3a344ee](https://linux-hardware.org/?probe=3eb3a344ee) | Aug 30, 2023 |
| ASRock        | M3A UCC                     | [b46f15b2d2](https://linux-hardware.org/?probe=b46f15b2d2) | Aug 30, 2023 |
| Supermicro    | X9DRW                       | [1ff3234fa5](https://linux-hardware.org/?probe=1ff3234fa5) | Aug 30, 2023 |
| Foxconn       | H55MXV Series               | [af9d0ad662](https://linux-hardware.org/?probe=af9d0ad662) | Aug 30, 2023 |
| Foxconn       | 2ABF                        | [26558ed0ce](https://linux-hardware.org/?probe=26558ed0ce) | Aug 30, 2023 |
| Dell          | 0J2J3Y A00                  | [57ac609885](https://linux-hardware.org/?probe=57ac609885) | Aug 30, 2023 |
| Huanan        | X99-QD4 V1.0                | [c5030f8fa1](https://linux-hardware.org/?probe=c5030f8fa1) | Aug 30, 2023 |
| Gigabyte      | G41M-Combo                  | [927a574e71](https://linux-hardware.org/?probe=927a574e71) | Aug 30, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [708fc220a9](https://linux-hardware.org/?probe=708fc220a9) | Aug 29, 2023 |
| MSI           | PH61-SP35                   | [590f47f3fd](https://linux-hardware.org/?probe=590f47f3fd) | Aug 29, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [4acce51a96](https://linux-hardware.org/?probe=4acce51a96) | Aug 29, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [205286a7e8](https://linux-hardware.org/?probe=205286a7e8) | Aug 29, 2023 |
| ASUSTek       | P8H61-MX                    | [861e741d6a](https://linux-hardware.org/?probe=861e741d6a) | Aug 29, 2023 |
| ASRock        | B460 Steel Legend           | [09ed405682](https://linux-hardware.org/?probe=09ed405682) | Aug 29, 2023 |
| ASUSTek       | STRIX B250G GAMING          | [16d3d84013](https://linux-hardware.org/?probe=16d3d84013) | Aug 29, 2023 |
| ASRock        | X670E Steel Legend          | [6bd291c8b0](https://linux-hardware.org/?probe=6bd291c8b0) | Aug 29, 2023 |
| Gigabyte      | H110-D3-CF                  | [e0d36eed9a](https://linux-hardware.org/?probe=e0d36eed9a) | Aug 29, 2023 |
| Intel         | SKYBAY                      | [59cfa4ea58](https://linux-hardware.org/?probe=59cfa4ea58) | Aug 29, 2023 |
| Huanan        | X99-ZD4 V2.1                | [2ab7a21e20](https://linux-hardware.org/?probe=2ab7a21e20) | Aug 29, 2023 |
| ASUSTek       | M3N78-EH                    | [c0fb869905](https://linux-hardware.org/?probe=c0fb869905) | Aug 29, 2023 |
| Gigabyte      | 8IPE1000                    | [50a9455c00](https://linux-hardware.org/?probe=50a9455c00) | Aug 28, 2023 |
| MSI           | 770-C45                     | [6f52d0be24](https://linux-hardware.org/?probe=6f52d0be24) | Aug 28, 2023 |
| Gigabyte      | 8IPE1000                    | [eb4740694a](https://linux-hardware.org/?probe=eb4740694a) | Aug 28, 2023 |
| ASRock        | Z97 Pro4                    | [6c232e36c3](https://linux-hardware.org/?probe=6c232e36c3) | Aug 28, 2023 |
| ASUSTek       | P5QL/EPU                    | [b2bc9269e5](https://linux-hardware.org/?probe=b2bc9269e5) | Aug 28, 2023 |
| ASUSTek       | PRIME H510M-R               | [c6614846b5](https://linux-hardware.org/?probe=c6614846b5) | Aug 28, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [9d90b80d9a](https://linux-hardware.org/?probe=9d90b80d9a) | Aug 27, 2023 |
| ASRock        | B460 Steel Legend           | [ad478d48ad](https://linux-hardware.org/?probe=ad478d48ad) | Aug 27, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [4e7e2a9946](https://linux-hardware.org/?probe=4e7e2a9946) | Aug 27, 2023 |
| MSI           | A320M-A PRO                 | [14d4e6bf4c](https://linux-hardware.org/?probe=14d4e6bf4c) | Aug 27, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [1f59c17089](https://linux-hardware.org/?probe=1f59c17089) | Aug 27, 2023 |
| MSI           | A320M-A PRO                 | [5ad490f8cb](https://linux-hardware.org/?probe=5ad490f8cb) | Aug 27, 2023 |
| Gigabyte      | Z490 GAMING X               | [ee07c69165](https://linux-hardware.org/?probe=ee07c69165) | Aug 27, 2023 |
| ASRock        | N68PV-GS                    | [d9171bedd5](https://linux-hardware.org/?probe=d9171bedd5) | Aug 27, 2023 |
| Unknown       | Unknown                     | [4d432af6c0](https://linux-hardware.org/?probe=4d432af6c0) | Aug 27, 2023 |
| Gigabyte      | F2A55M-DS2                  | [3efec986ee](https://linux-hardware.org/?probe=3efec986ee) | Aug 27, 2023 |
| ASRock        | X670E Steel Legend          | [c675cc9767](https://linux-hardware.org/?probe=c675cc9767) | Aug 27, 2023 |
| Gigabyte      | H61M-S2-B3                  | [c9505b94ed](https://linux-hardware.org/?probe=c9505b94ed) | Aug 26, 2023 |
| ASUSTek       | PRIME H310M-K               | [1f606cb9da](https://linux-hardware.org/?probe=1f606cb9da) | Aug 26, 2023 |
| Gigabyte      | Z87-HD3                     | [3601cce38e](https://linux-hardware.org/?probe=3601cce38e) | Aug 26, 2023 |
| ASUSTek       | P8Z77-V LX                  | [9f1872b5e9](https://linux-hardware.org/?probe=9f1872b5e9) | Aug 26, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [5d4b85d28b](https://linux-hardware.org/?probe=5d4b85d28b) | Aug 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [e4200e4c9a](https://linux-hardware.org/?probe=e4200e4c9a) | Aug 25, 2023 |
| ASUSTek       | PRIME X370-PRO              | [fd03f60906](https://linux-hardware.org/?probe=fd03f60906) | Aug 25, 2023 |
| Gigabyte      | 990FXA-UD3                  | [083aa2f63c](https://linux-hardware.org/?probe=083aa2f63c) | Aug 25, 2023 |
| MSI           | B450M MORTAR MAX            | [b328603445](https://linux-hardware.org/?probe=b328603445) | Aug 25, 2023 |
| ASRock        | M3N78D                      | [cbaee686c2](https://linux-hardware.org/?probe=cbaee686c2) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0cc7a0f138](https://linux-hardware.org/?probe=0cc7a0f138) | Aug 25, 2023 |
| ASUSTek       | M4N78 SE                    | [aff07fea82](https://linux-hardware.org/?probe=aff07fea82) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [241fead3e6](https://linux-hardware.org/?probe=241fead3e6) | Aug 25, 2023 |
| Biostar       | TF570 SLI A2+               | [825725cf8d](https://linux-hardware.org/?probe=825725cf8d) | Aug 25, 2023 |
| Gigabyte      | H87-HD3                     | [84ef801923](https://linux-hardware.org/?probe=84ef801923) | Aug 24, 2023 |
| Intel         | D2700DC AAG32420-602        | [d3743d52fa](https://linux-hardware.org/?probe=d3743d52fa) | Aug 24, 2023 |
| Gigabyte      | H110-D3-CF                  | [2436229edb](https://linux-hardware.org/?probe=2436229edb) | Aug 24, 2023 |
| Intel         | D2700DC AAG32420-602        | [3381b3de96](https://linux-hardware.org/?probe=3381b3de96) | Aug 24, 2023 |
| Gigabyte      | B450M S2H                   | [9d09e14624](https://linux-hardware.org/?probe=9d09e14624) | Aug 24, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [eeff109a12](https://linux-hardware.org/?probe=eeff109a12) | Aug 24, 2023 |
| ASUSTek       | P8H77-M PRO                 | [4953513629](https://linux-hardware.org/?probe=4953513629) | Aug 24, 2023 |
| ASUSTek       | M5A78L-M LX3                | [b96cc7270e](https://linux-hardware.org/?probe=b96cc7270e) | Aug 24, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [083700ba74](https://linux-hardware.org/?probe=083700ba74) | Aug 23, 2023 |
| ASRock        | M3N78D                      | [86e93b6cec](https://linux-hardware.org/?probe=86e93b6cec) | Aug 23, 2023 |
| ASRock        | P4i945GC                    | [5fd422ae68](https://linux-hardware.org/?probe=5fd422ae68) | Aug 23, 2023 |
| Gigabyte      | F2A55M-DS2                  | [2889ef1f56](https://linux-hardware.org/?probe=2889ef1f56) | Aug 23, 2023 |
| ASRock        | X370 Pro4                   | [190a0f1eee](https://linux-hardware.org/?probe=190a0f1eee) | Aug 23, 2023 |
| Biostar       | A68MHE                      | [3ff360b5c5](https://linux-hardware.org/?probe=3ff360b5c5) | Aug 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [1510eba46f](https://linux-hardware.org/?probe=1510eba46f) | Aug 22, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [64f3da359d](https://linux-hardware.org/?probe=64f3da359d) | Aug 22, 2023 |
| Gigabyte      | H61M-S2PV                   | [df34a2b0db](https://linux-hardware.org/?probe=df34a2b0db) | Aug 22, 2023 |
| MSI           | G31TM-P21                   | [c8aa8973a4](https://linux-hardware.org/?probe=c8aa8973a4) | Aug 22, 2023 |
| Foxconn       | 2ABF                        | [82b421a678](https://linux-hardware.org/?probe=82b421a678) | Aug 22, 2023 |
| ASUSTek       | P5Q-E                       | [39fa23e4b7](https://linux-hardware.org/?probe=39fa23e4b7) | Aug 22, 2023 |
| ASUSTek       | E35M1-M                     | [5b3a30e3bc](https://linux-hardware.org/?probe=5b3a30e3bc) | Aug 22, 2023 |
| MSI           | H510M-A PRO                 | [e405022cc9](https://linux-hardware.org/?probe=e405022cc9) | Aug 22, 2023 |
| ASUSTek       | P7P55-M                     | [01ee3a9784](https://linux-hardware.org/?probe=01ee3a9784) | Aug 21, 2023 |
| Gigabyte      | H61M-S2PV                   | [2e06223da9](https://linux-hardware.org/?probe=2e06223da9) | Aug 21, 2023 |
| MSI           | X470 GAMING PLUS            | [191c724d49](https://linux-hardware.org/?probe=191c724d49) | Aug 21, 2023 |
| ASUSTek       | E35M1-M                     | [c3207e25fd](https://linux-hardware.org/?probe=c3207e25fd) | Aug 21, 2023 |
| WeiBu         | H310CX1B V1.0               | [b3ec8e66ae](https://linux-hardware.org/?probe=b3ec8e66ae) | Aug 21, 2023 |
| Gigabyte      | M68M-S2P                    | [41ba06b203](https://linux-hardware.org/?probe=41ba06b203) | Aug 21, 2023 |
| Biostar       | TF570 SLI A2+               | [3d706eb2f3](https://linux-hardware.org/?probe=3d706eb2f3) | Aug 21, 2023 |
| ASRock        | H510M-HVS R2.0              | [7993a53688](https://linux-hardware.org/?probe=7993a53688) | Aug 21, 2023 |
| Intel         | X99                         | [c1ad35e185](https://linux-hardware.org/?probe=c1ad35e185) | Aug 20, 2023 |
| Gigabyte      | GA-970A-D3                  | [e784b29438](https://linux-hardware.org/?probe=e784b29438) | Aug 20, 2023 |
| Intel         | X99                         | [3f141e2bd1](https://linux-hardware.org/?probe=3f141e2bd1) | Aug 20, 2023 |
| Gigabyte      | B660 DS3H DDR4              | [581265dcb6](https://linux-hardware.org/?probe=581265dcb6) | Aug 20, 2023 |
| Lenovo        | H420                        | [0741adee29](https://linux-hardware.org/?probe=0741adee29) | Aug 20, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [11d699cccd](https://linux-hardware.org/?probe=11d699cccd) | Aug 20, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [d8fd2a6d98](https://linux-hardware.org/?probe=d8fd2a6d98) | Aug 20, 2023 |
| ASUSTek       | P5P41D                      | [4ccbd3e19e](https://linux-hardware.org/?probe=4ccbd3e19e) | Aug 20, 2023 |
| Biostar       | H310MHC2                    | [12f3b0d269](https://linux-hardware.org/?probe=12f3b0d269) | Aug 20, 2023 |
| Lenovo        | H420                        | [ef44de6298](https://linux-hardware.org/?probe=ef44de6298) | Aug 20, 2023 |
| Intel         | X99                         | [e16fe5b0f3](https://linux-hardware.org/?probe=e16fe5b0f3) | Aug 19, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [34a23c836c](https://linux-hardware.org/?probe=34a23c836c) | Aug 19, 2023 |
| K-Systems     | Unknown                     | [52ff91dc03](https://linux-hardware.org/?probe=52ff91dc03) | Aug 19, 2023 |
| Huanan        | X99-F8D V2.4                | [8af741a2c4](https://linux-hardware.org/?probe=8af741a2c4) | Aug 19, 2023 |
| ASRock        | Z370 Pro4                   | [9b7cf0384c](https://linux-hardware.org/?probe=9b7cf0384c) | Aug 18, 2023 |
| ASUSTek       | P8H61-MX                    | [767b42eeca](https://linux-hardware.org/?probe=767b42eeca) | Aug 18, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [097825338b](https://linux-hardware.org/?probe=097825338b) | Aug 18, 2023 |
| Gigabyte      | B560M D3H                   | [7a9ae970e6](https://linux-hardware.org/?probe=7a9ae970e6) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [7911ff1df6](https://linux-hardware.org/?probe=7911ff1df6) | Aug 18, 2023 |
| ASRock        | H510M-HVS R2.0              | [0a2d342da5](https://linux-hardware.org/?probe=0a2d342da5) | Aug 18, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [2de4fc4556](https://linux-hardware.org/?probe=2de4fc4556) | Aug 18, 2023 |
| ASRock        | H510M-HVS R2.0              | [b83a6ac1b7](https://linux-hardware.org/?probe=b83a6ac1b7) | Aug 18, 2023 |
| ASUSTek       | P8H77-M PRO                 | [98b50f195d](https://linux-hardware.org/?probe=98b50f195d) | Aug 18, 2023 |
| Biostar       | A68MHE                      | [0c88bf33f4](https://linux-hardware.org/?probe=0c88bf33f4) | Aug 18, 2023 |
| DEPO Compu... | DPH410S                     | [88076446b3](https://linux-hardware.org/?probe=88076446b3) | Aug 18, 2023 |
| DEPO Compu... | DPH410S                     | [201a0612e4](https://linux-hardware.org/?probe=201a0612e4) | Aug 18, 2023 |
| Gigabyte      | H61M-S1                     | [dbe8d496ac](https://linux-hardware.org/?probe=dbe8d496ac) | Aug 17, 2023 |
| ASRock        | 970 Pro3 R2.0               | [54a5786749](https://linux-hardware.org/?probe=54a5786749) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [4b8894823c](https://linux-hardware.org/?probe=4b8894823c) | Aug 17, 2023 |
| Supermicro    | X9DRW                       | [eb0dd75419](https://linux-hardware.org/?probe=eb0dd75419) | Aug 17, 2023 |
| Intel         | X99H                        | [ee1fff7602](https://linux-hardware.org/?probe=ee1fff7602) | Aug 17, 2023 |
| Gigabyte      | B360M DS3H                  | [31165e8a73](https://linux-hardware.org/?probe=31165e8a73) | Aug 17, 2023 |
| Intel         | DE3815TYKH H26998-402       | [a2a8c567a3](https://linux-hardware.org/?probe=a2a8c567a3) | Aug 17, 2023 |
| Gigabyte      | B85M-D3H                    | [fe8d01fa26](https://linux-hardware.org/?probe=fe8d01fa26) | Aug 17, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [83e6c3323d](https://linux-hardware.org/?probe=83e6c3323d) | Aug 16, 2023 |
| Gigabyte      | 965P-S3                     | [d9557da16c](https://linux-hardware.org/?probe=d9557da16c) | Aug 16, 2023 |
| ASRock        | H310CM-DVS                  | [26b07a9b9c](https://linux-hardware.org/?probe=26b07a9b9c) | Aug 16, 2023 |
| Gigabyte      | P55-USB3                    | [4e25d8ef9f](https://linux-hardware.org/?probe=4e25d8ef9f) | Aug 16, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [25279b238a](https://linux-hardware.org/?probe=25279b238a) | Aug 16, 2023 |
| ASUSTek       | PRIME B450M-K II            | [7052cd45dc](https://linux-hardware.org/?probe=7052cd45dc) | Aug 15, 2023 |
| Unknown       | Unknown                     | [632e853b38](https://linux-hardware.org/?probe=632e853b38) | Aug 15, 2023 |
| ASUSTek       | P8H61-M LX                  | [e1d0ef3bb8](https://linux-hardware.org/?probe=e1d0ef3bb8) | Aug 15, 2023 |
| ASUSTek       | M4A77TD                     | [a2c6278e77](https://linux-hardware.org/?probe=a2c6278e77) | Aug 15, 2023 |
| ASUSTek       | P5K SE                      | [8d6a3e990c](https://linux-hardware.org/?probe=8d6a3e990c) | Aug 15, 2023 |
| Supermicro    | X9DRW                       | [0fdb533afb](https://linux-hardware.org/?probe=0fdb533afb) | Aug 15, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [ac6dd63085](https://linux-hardware.org/?probe=ac6dd63085) | Aug 15, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [0d21b420ac](https://linux-hardware.org/?probe=0d21b420ac) | Aug 15, 2023 |
| HP            | 1495                        | [d038a45bbd](https://linux-hardware.org/?probe=d038a45bbd) | Aug 15, 2023 |
| Acer          | Veriton X2640G V:1.0        | [f4ba515a8d](https://linux-hardware.org/?probe=f4ba515a8d) | Aug 14, 2023 |
| Acer          | Veriton X2640G V:1.0        | [2473d1c807](https://linux-hardware.org/?probe=2473d1c807) | Aug 14, 2023 |
| ASRock        | G41C-GS R2.0                | [82d639b155](https://linux-hardware.org/?probe=82d639b155) | Aug 14, 2023 |
| ASUSTek       | P8H61-M LX                  | [63c0e75955](https://linux-hardware.org/?probe=63c0e75955) | Aug 14, 2023 |
| ASRock        | B550M-ITX/ac                | [64aa93e41b](https://linux-hardware.org/?probe=64aa93e41b) | Aug 14, 2023 |
| ASUSTek       | B85-PLUS                    | [64c547a12b](https://linux-hardware.org/?probe=64c547a12b) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [ee66d3a81c](https://linux-hardware.org/?probe=ee66d3a81c) | Aug 13, 2023 |
| ECS           | G41T-M2                     | [b67afe5845](https://linux-hardware.org/?probe=b67afe5845) | Aug 13, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d11f1184c5](https://linux-hardware.org/?probe=d11f1184c5) | Aug 13, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX-W       | [ccaf390b87](https://linux-hardware.org/?probe=ccaf390b87) | Aug 13, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX-W       | [aeee4a0b68](https://linux-hardware.org/?probe=aeee4a0b68) | Aug 13, 2023 |
| ASUSTek       | PRIME B365M-K               | [1f86102443](https://linux-hardware.org/?probe=1f86102443) | Aug 12, 2023 |
| Gigabyte      | Z77X-D3H                    | [8599cd2ad3](https://linux-hardware.org/?probe=8599cd2ad3) | Aug 12, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ae8c13e17e](https://linux-hardware.org/?probe=ae8c13e17e) | Aug 12, 2023 |
| MSI           | P67A-GD65                   | [1024e95ca9](https://linux-hardware.org/?probe=1024e95ca9) | Aug 12, 2023 |
| Gigabyte      | Z77X-D3H                    | [f57a3e9f6a](https://linux-hardware.org/?probe=f57a3e9f6a) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [2c92ed92eb](https://linux-hardware.org/?probe=2c92ed92eb) | Aug 12, 2023 |
| ASUSTek       | M5A97 R2.0                  | [96995d7026](https://linux-hardware.org/?probe=96995d7026) | Aug 12, 2023 |
| Gigabyte      | B560M DS3H V2               | [2805e140b5](https://linux-hardware.org/?probe=2805e140b5) | Aug 11, 2023 |
| Unknown       | Unknown                     | [e32bb1bbb2](https://linux-hardware.org/?probe=e32bb1bbb2) | Aug 11, 2023 |
| Gigabyte      | B85M-D2V                    | [d8d7d7bad7](https://linux-hardware.org/?probe=d8d7d7bad7) | Aug 11, 2023 |
| MSI           | G33M                        | [65de454e8b](https://linux-hardware.org/?probe=65de454e8b) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [cc7efa7eba](https://linux-hardware.org/?probe=cc7efa7eba) | Aug 11, 2023 |
| Huanan        | X99-F8 V2.0                 | [f028b8f65d](https://linux-hardware.org/?probe=f028b8f65d) | Aug 11, 2023 |
| MSI           | B450M PRO-M2 MAX            | [07e0bad7da](https://linux-hardware.org/?probe=07e0bad7da) | Aug 10, 2023 |
| ASUSTek       | P7P55-M                     | [6f80191c4a](https://linux-hardware.org/?probe=6f80191c4a) | Aug 10, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [fb99152b24](https://linux-hardware.org/?probe=fb99152b24) | Aug 10, 2023 |
| Lenovo        | H420                        | [d418e9d1d1](https://linux-hardware.org/?probe=d418e9d1d1) | Aug 10, 2023 |
| MSI           | H97 GAMING 3                | [584a47e4ae](https://linux-hardware.org/?probe=584a47e4ae) | Aug 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4a7cc2835f](https://linux-hardware.org/?probe=4a7cc2835f) | Aug 09, 2023 |
| ASUSTek       | B85M-G                      | [9fcf84ff7c](https://linux-hardware.org/?probe=9fcf84ff7c) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | [a43111576a](https://linux-hardware.org/?probe=a43111576a) | Aug 09, 2023 |
| Gigabyte      | Z370M D3H-CF                | [9326dd9736](https://linux-hardware.org/?probe=9326dd9736) | Aug 09, 2023 |
| Supermicro    | X8ST3                       | [13099babf6](https://linux-hardware.org/?probe=13099babf6) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [5aeb5ebcbf](https://linux-hardware.org/?probe=5aeb5ebcbf) | Aug 09, 2023 |
| ASUSTek       | P8H67-M LX                  | [62d3166469](https://linux-hardware.org/?probe=62d3166469) | Aug 09, 2023 |
| ASUSTek       | PRIME H510M-R               | [38ab435feb](https://linux-hardware.org/?probe=38ab435feb) | Aug 08, 2023 |
| MSI           | H61M-P31                    | [3fa41aaf62](https://linux-hardware.org/?probe=3fa41aaf62) | Aug 08, 2023 |
| MSI           | H97M-G43                    | [f8905cffe2](https://linux-hardware.org/?probe=f8905cffe2) | Aug 08, 2023 |
| Gigabyte      | B360HD3                     | [4dc4fb1691](https://linux-hardware.org/?probe=4dc4fb1691) | Aug 08, 2023 |
| MSI           | H97 GAMING 3                | [04962a5072](https://linux-hardware.org/?probe=04962a5072) | Aug 08, 2023 |
| Soyo          | SY-Classic B450M            | [708e9837c5](https://linux-hardware.org/?probe=708e9837c5) | Aug 07, 2023 |
| ASUSTek       | Z170-K                      | [209b568765](https://linux-hardware.org/?probe=209b568765) | Aug 07, 2023 |
| DEPO Compu... | DPA520S                     | [71b00682fc](https://linux-hardware.org/?probe=71b00682fc) | Aug 07, 2023 |
| ASUSTek       | M4A77TD                     | [667b258dd5](https://linux-hardware.org/?probe=667b258dd5) | Aug 06, 2023 |
| Soyo          | SY-Classic B450M            | [04a850b33b](https://linux-hardware.org/?probe=04a850b33b) | Aug 06, 2023 |
| MSI           | B450M-A PRO MAX             | [ec1bd43523](https://linux-hardware.org/?probe=ec1bd43523) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | [4c1ef04fe9](https://linux-hardware.org/?probe=4c1ef04fe9) | Aug 05, 2023 |
| ASRock        | B550 PG Velocita            | [71ca443602](https://linux-hardware.org/?probe=71ca443602) | Aug 05, 2023 |
| ASUSTek       | H81M-C                      | [cd16d74fc1](https://linux-hardware.org/?probe=cd16d74fc1) | Aug 04, 2023 |
| ASUSTek       | AT4NM10T-I                  | [a650338ead](https://linux-hardware.org/?probe=a650338ead) | Aug 04, 2023 |
| ASUSTek       | P5K SE/EPU                  | [c125911c18](https://linux-hardware.org/?probe=c125911c18) | Aug 04, 2023 |
| ASRock        | G31M-S                      | [02bb341cc9](https://linux-hardware.org/?probe=02bb341cc9) | Aug 04, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [701c63b20d](https://linux-hardware.org/?probe=701c63b20d) | Aug 04, 2023 |
| Gigabyte      | H77-DS3H                    | [4c677637c2](https://linux-hardware.org/?probe=4c677637c2) | Aug 04, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [6d37036a76](https://linux-hardware.org/?probe=6d37036a76) | Aug 03, 2023 |
| MSI           | PRO B550M-P GEN3            | [163708151e](https://linux-hardware.org/?probe=163708151e) | Aug 03, 2023 |
| ASUSTek       | P9X79                       | [381ebee880](https://linux-hardware.org/?probe=381ebee880) | Aug 03, 2023 |
| MSI           | H110M PRO-VD Plus           | [de9bb54769](https://linux-hardware.org/?probe=de9bb54769) | Aug 03, 2023 |
| ASUSTek       | P8B75-M LX                  | [6d7ac5bfd2](https://linux-hardware.org/?probe=6d7ac5bfd2) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | [beddea6e34](https://linux-hardware.org/?probe=beddea6e34) | Aug 03, 2023 |
| Supermicro    | X7DWN+                      | [92bf3762f2](https://linux-hardware.org/?probe=92bf3762f2) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | [37ebe498c2](https://linux-hardware.org/?probe=37ebe498c2) | Aug 03, 2023 |
| Supermicro    | X7DWN+                      | [53edc778db](https://linux-hardware.org/?probe=53edc778db) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | [dc1c75a471](https://linux-hardware.org/?probe=dc1c75a471) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | [28007801d5](https://linux-hardware.org/?probe=28007801d5) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | [5e3a46dee8](https://linux-hardware.org/?probe=5e3a46dee8) | Aug 03, 2023 |
| ASUSTek       | PRIME Z270-P                | [219278bb56](https://linux-hardware.org/?probe=219278bb56) | Aug 03, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [448ad2c06a](https://linux-hardware.org/?probe=448ad2c06a) | Aug 03, 2023 |
| Gigabyte      | H67A-USB3-B3                | [5a368bb70f](https://linux-hardware.org/?probe=5a368bb70f) | Aug 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | [bd5d07f54f](https://linux-hardware.org/?probe=bd5d07f54f) | Aug 02, 2023 |
| ASUSTek       | P5K PRO                     | [b8c2590139](https://linux-hardware.org/?probe=b8c2590139) | Aug 02, 2023 |
| ASUSTek       | P8H77-M PRO                 | [1ea7139d7e](https://linux-hardware.org/?probe=1ea7139d7e) | Aug 02, 2023 |
| MSI           | B560M PRO-E                 | [b10154befd](https://linux-hardware.org/?probe=b10154befd) | Aug 02, 2023 |
| Gigabyte      | H67A-USB3-B3                | [23ba156377](https://linux-hardware.org/?probe=23ba156377) | Aug 02, 2023 |
| ASUSTek       | H110M-K                     | [c12e9ed368](https://linux-hardware.org/?probe=c12e9ed368) | Aug 02, 2023 |
| Gigabyte      | H61M-S2PV                   | [70c8bcf589](https://linux-hardware.org/?probe=70c8bcf589) | Aug 02, 2023 |
| ASUSTek       | P7F-M                       | [5c04bf12d0](https://linux-hardware.org/?probe=5c04bf12d0) | Aug 02, 2023 |
| Dell          | 0GRJJ9 A01                  | [dca7ee3fdc](https://linux-hardware.org/?probe=dca7ee3fdc) | Aug 02, 2023 |
| ASRock        | B450M-HDV                   | [56c71bf2d5](https://linux-hardware.org/?probe=56c71bf2d5) | Aug 01, 2023 |
| MSI           | G41M-P33 Combo              | [ec5e4c2338](https://linux-hardware.org/?probe=ec5e4c2338) | Aug 01, 2023 |
| Gigabyte      | Z490 UD                     | [bdf93fa781](https://linux-hardware.org/?probe=bdf93fa781) | Jul 31, 2023 |
| ASUSTek       | TUF H310-PLUS GAMING        | [a9326ba27e](https://linux-hardware.org/?probe=a9326ba27e) | Jul 31, 2023 |
| Supermicro    | X7DWE                       | [a35080b0e5](https://linux-hardware.org/?probe=a35080b0e5) | Jul 31, 2023 |
| Gigabyte      | Z490 GAMING X               | [f710ad8b96](https://linux-hardware.org/?probe=f710ad8b96) | Jul 31, 2023 |
| ASRock        | ALiveSATA2-GLAN             | [3c4fbfa426](https://linux-hardware.org/?probe=3c4fbfa426) | Jul 31, 2023 |
| Gigabyte      | B75M-D3V                    | [ef86202c7f](https://linux-hardware.org/?probe=ef86202c7f) | Jul 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [e11390bc86](https://linux-hardware.org/?probe=e11390bc86) | Jul 31, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [6bf2e91f31](https://linux-hardware.org/?probe=6bf2e91f31) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [0f9accc3e8](https://linux-hardware.org/?probe=0f9accc3e8) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | [df34eb4472](https://linux-hardware.org/?probe=df34eb4472) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | [0449350f3d](https://linux-hardware.org/?probe=0449350f3d) | Jul 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX-W       | [9c5eccdca7](https://linux-hardware.org/?probe=9c5eccdca7) | Jul 29, 2023 |
| ASRock        | G41M-VS2                    | [74564d3418](https://linux-hardware.org/?probe=74564d3418) | Jul 28, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [3ef07a69e6](https://linux-hardware.org/?probe=3ef07a69e6) | Jul 28, 2023 |
| Gigabyte      | P55-UD3L                    | [82a3947c74](https://linux-hardware.org/?probe=82a3947c74) | Jul 28, 2023 |
| ECS           | G33T_M                      | [cfaf5eaf20](https://linux-hardware.org/?probe=cfaf5eaf20) | Jul 28, 2023 |
| Lenovo        | No DPK                      | [c6af16725d](https://linux-hardware.org/?probe=c6af16725d) | Jul 28, 2023 |
| ASUSTek       | A88XM-A                     | [3ef67c1e1c](https://linux-hardware.org/?probe=3ef67c1e1c) | Jul 27, 2023 |
| ASRock        | X670E Pro RS                | [27a13f80b2](https://linux-hardware.org/?probe=27a13f80b2) | Jul 27, 2023 |
| Gigabyte      | GA-870A-UD3                 | [cc502a8417](https://linux-hardware.org/?probe=cc502a8417) | Jul 27, 2023 |
| Unknown       | SCHNEIDER                   | [6ab609f07e](https://linux-hardware.org/?probe=6ab609f07e) | Jul 27, 2023 |
| HP            | 1495                        | [7db2d77f67](https://linux-hardware.org/?probe=7db2d77f67) | Jul 27, 2023 |
| HP            | 1495                        | [376f9777d4](https://linux-hardware.org/?probe=376f9777d4) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [23183da982](https://linux-hardware.org/?probe=23183da982) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [77d42f4b5c](https://linux-hardware.org/?probe=77d42f4b5c) | Jul 27, 2023 |
| Acer          | Aspire XC-885 V:1.1         | [eebd657892](https://linux-hardware.org/?probe=eebd657892) | Jul 27, 2023 |
| Gigabyte      | Z490 UD                     | [370243099a](https://linux-hardware.org/?probe=370243099a) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [e8abbb213e](https://linux-hardware.org/?probe=e8abbb213e) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [bb4812527c](https://linux-hardware.org/?probe=bb4812527c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [2b7085bd2b](https://linux-hardware.org/?probe=2b7085bd2b) | Jul 27, 2023 |
| MSI           | Z97A GAMING 7               | [cf2d32f045](https://linux-hardware.org/?probe=cf2d32f045) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [a375e21964](https://linux-hardware.org/?probe=a375e21964) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [d0e6321772](https://linux-hardware.org/?probe=d0e6321772) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [28ea1c85d1](https://linux-hardware.org/?probe=28ea1c85d1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [3fd18c9a77](https://linux-hardware.org/?probe=3fd18c9a77) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [d974298840](https://linux-hardware.org/?probe=d974298840) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [b06f493001](https://linux-hardware.org/?probe=b06f493001) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [894bb319dc](https://linux-hardware.org/?probe=894bb319dc) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [7ec6d64d2f](https://linux-hardware.org/?probe=7ec6d64d2f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [09662b0f5d](https://linux-hardware.org/?probe=09662b0f5d) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [3c8721254c](https://linux-hardware.org/?probe=3c8721254c) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [7dfa96789f](https://linux-hardware.org/?probe=7dfa96789f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [c538742db7](https://linux-hardware.org/?probe=c538742db7) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [9da53986f9](https://linux-hardware.org/?probe=9da53986f9) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [c950f7dbc1](https://linux-hardware.org/?probe=c950f7dbc1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [dcf4ead958](https://linux-hardware.org/?probe=dcf4ead958) | Jul 26, 2023 |
| ASRock        | N68C-GS FX                  | [6b35cdc0ae](https://linux-hardware.org/?probe=6b35cdc0ae) | Jul 26, 2023 |
| Gigabyte      | Z490 UD                     | [29aa67256f](https://linux-hardware.org/?probe=29aa67256f) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [759b0f997f](https://linux-hardware.org/?probe=759b0f997f) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [a1ef57fb8e](https://linux-hardware.org/?probe=a1ef57fb8e) | Jul 26, 2023 |
| ASRock        | A320M Pro4                  | [9ecdd1e4d3](https://linux-hardware.org/?probe=9ecdd1e4d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [f45c4baaa3](https://linux-hardware.org/?probe=f45c4baaa3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [7abbda5ed3](https://linux-hardware.org/?probe=7abbda5ed3) | Jul 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3a59ab6dd1](https://linux-hardware.org/?probe=3a59ab6dd1) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [67036356d3](https://linux-hardware.org/?probe=67036356d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [5a134aede2](https://linux-hardware.org/?probe=5a134aede2) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [28c92b6f8d](https://linux-hardware.org/?probe=28c92b6f8d) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | [808dae186a](https://linux-hardware.org/?probe=808dae186a) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | [b45586c5cf](https://linux-hardware.org/?probe=b45586c5cf) | Jul 26, 2023 |
| AZW           | U59                         | [fcf46a9025](https://linux-hardware.org/?probe=fcf46a9025) | Jul 25, 2023 |
| Gigabyte      | A320M-H-CF                  | [1852d1455f](https://linux-hardware.org/?probe=1852d1455f) | Jul 25, 2023 |
| Shenzhen M... | F7BAA                       | [761f825569](https://linux-hardware.org/?probe=761f825569) | Jul 25, 2023 |
| Gigabyte      | B360HD3                     | [b297b777be](https://linux-hardware.org/?probe=b297b777be) | Jul 25, 2023 |
| ASUSTek       | P7H55-M LX                  | [543257c1b1](https://linux-hardware.org/?probe=543257c1b1) | Jul 25, 2023 |
| ASUSTek       | D500TC                      | [4fa391d922](https://linux-hardware.org/?probe=4fa391d922) | Jul 25, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [bfa56fe825](https://linux-hardware.org/?probe=bfa56fe825) | Jul 25, 2023 |
| Intel         | D34010WYK H14771-304        | [c5960175bc](https://linux-hardware.org/?probe=c5960175bc) | Jul 25, 2023 |
| MSI           | ZH77A-G41                   | [8528da5360](https://linux-hardware.org/?probe=8528da5360) | Jul 24, 2023 |
| SiS Techno... | 760                         | [1c5bd52522](https://linux-hardware.org/?probe=1c5bd52522) | Jul 24, 2023 |
| Gigabyte      | H110M-H-CF                  | [6dbfb1d71e](https://linux-hardware.org/?probe=6dbfb1d71e) | Jul 24, 2023 |
| ASUSTek       | PRIME B250M-K               | [5b6e05fa3b](https://linux-hardware.org/?probe=5b6e05fa3b) | Jul 24, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [b571da19fb](https://linux-hardware.org/?probe=b571da19fb) | Jul 24, 2023 |
| ASUSTek       | M4A87TD EVO                 | [2a23928116](https://linux-hardware.org/?probe=2a23928116) | Jul 24, 2023 |
| ASUSTek       | M4A87TD EVO                 | [247870abec](https://linux-hardware.org/?probe=247870abec) | Jul 24, 2023 |
| Gigabyte      | Z77-DS3H                    | [27a5af5007](https://linux-hardware.org/?probe=27a5af5007) | Jul 24, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [f8df0d0706](https://linux-hardware.org/?probe=f8df0d0706) | Jul 24, 2023 |
| MSI           | H110M PRO-VD                | [7076b096fd](https://linux-hardware.org/?probe=7076b096fd) | Jul 24, 2023 |
| ASRock        | N68-GS4 FX                  | [304505406b](https://linux-hardware.org/?probe=304505406b) | Jul 24, 2023 |
| Dell          | 0Y5DDC A00                  | [a0cb68bf97](https://linux-hardware.org/?probe=a0cb68bf97) | Jul 24, 2023 |
| Gigabyte      | H510M S2H V2                | [95290b34e3](https://linux-hardware.org/?probe=95290b34e3) | Jul 23, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [3eadaff590](https://linux-hardware.org/?probe=3eadaff590) | Jul 23, 2023 |
| MSI           | Z87 MPOWER                  | [dcbda0f556](https://linux-hardware.org/?probe=dcbda0f556) | Jul 23, 2023 |
| Intel         | X79 V1.x                    | [dda9563d4a](https://linux-hardware.org/?probe=dda9563d4a) | Jul 23, 2023 |
| Gigabyte      | X570 GAMING X               | [b0e064a98a](https://linux-hardware.org/?probe=b0e064a98a) | Jul 23, 2023 |
| Gigabyte      | B360M D2V                   | [eef08e2598](https://linux-hardware.org/?probe=eef08e2598) | Jul 22, 2023 |
| ASUSTek       | P9X79                       | [2f8efec736](https://linux-hardware.org/?probe=2f8efec736) | Jul 22, 2023 |
| Biostar       | A320MH                      | [b4ad5e7452](https://linux-hardware.org/?probe=b4ad5e7452) | Jul 22, 2023 |
| HP            | 2AA6 PVT                    | [de8572b8cf](https://linux-hardware.org/?probe=de8572b8cf) | Jul 22, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [d47c43e734](https://linux-hardware.org/?probe=d47c43e734) | Jul 22, 2023 |
| ASRock        | M3N78D                      | [4ab55414b4](https://linux-hardware.org/?probe=4ab55414b4) | Jul 21, 2023 |
| ASRock        | M3N78D                      | [8175c636e8](https://linux-hardware.org/?probe=8175c636e8) | Jul 21, 2023 |
| Lenovo        | ThinkCentre M81 5049C12     | [a3cb3aa377](https://linux-hardware.org/?probe=a3cb3aa377) | Jul 21, 2023 |
| ASUSTek       | P5Q-PRO                     | [cc299998bb](https://linux-hardware.org/?probe=cc299998bb) | Jul 20, 2023 |
| Gigabyte      | H61M-DS2V                   | [4720d80645](https://linux-hardware.org/?probe=4720d80645) | Jul 20, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [97c85ab250](https://linux-hardware.org/?probe=97c85ab250) | Jul 20, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b0efbdb752](https://linux-hardware.org/?probe=b0efbdb752) | Jul 20, 2023 |
| Gigabyte      | H81M-S2V                    | [014e4a907f](https://linux-hardware.org/?probe=014e4a907f) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [39742015a1](https://linux-hardware.org/?probe=39742015a1) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [e69885810c](https://linux-hardware.org/?probe=e69885810c) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [02958438e7](https://linux-hardware.org/?probe=02958438e7) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [28850b9e94](https://linux-hardware.org/?probe=28850b9e94) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [35c4f96184](https://linux-hardware.org/?probe=35c4f96184) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [3b0be53d2b](https://linux-hardware.org/?probe=3b0be53d2b) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [f35f948278](https://linux-hardware.org/?probe=f35f948278) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [cb12281aa1](https://linux-hardware.org/?probe=cb12281aa1) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [3bfca8e034](https://linux-hardware.org/?probe=3bfca8e034) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [667a30309b](https://linux-hardware.org/?probe=667a30309b) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [08cca00ba4](https://linux-hardware.org/?probe=08cca00ba4) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [646ef2c43e](https://linux-hardware.org/?probe=646ef2c43e) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [b380a59bd3](https://linux-hardware.org/?probe=b380a59bd3) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [d1f453b1cf](https://linux-hardware.org/?probe=d1f453b1cf) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [0525e36038](https://linux-hardware.org/?probe=0525e36038) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [56571f9682](https://linux-hardware.org/?probe=56571f9682) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | [b4516f6d51](https://linux-hardware.org/?probe=b4516f6d51) | Jul 19, 2023 |
| ASRock        | A520M-HVS                   | [9dd9b64ff1](https://linux-hardware.org/?probe=9dd9b64ff1) | Jul 19, 2023 |
| Biostar       | H61MHV2                     | [c108eac8f6](https://linux-hardware.org/?probe=c108eac8f6) | Jul 19, 2023 |
| ASUSTek       | P5QL-CM                     | [65fe34f4ce](https://linux-hardware.org/?probe=65fe34f4ce) | Jul 19, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [278c03b690](https://linux-hardware.org/?probe=278c03b690) | Jul 19, 2023 |
| ASUSTek       | H81M-K                      | [5facab887b](https://linux-hardware.org/?probe=5facab887b) | Jul 18, 2023 |
| ASUSTek       | P8H61-MX                    | [c68138ca5c](https://linux-hardware.org/?probe=c68138ca5c) | Jul 18, 2023 |
| Gigabyte      | Z77-DS3H                    | [0eea552cfa](https://linux-hardware.org/?probe=0eea552cfa) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | [866bc45d05](https://linux-hardware.org/?probe=866bc45d05) | Jul 18, 2023 |
| ASUSTek       | P5B-Deluxe                  | [0cf82c02d3](https://linux-hardware.org/?probe=0cf82c02d3) | Jul 18, 2023 |
| ASRock        | X99M Extreme4               | [f799654e45](https://linux-hardware.org/?probe=f799654e45) | Jul 18, 2023 |
| Gigabyte      | B85M-D3H                    | [0e8d97083a](https://linux-hardware.org/?probe=0e8d97083a) | Jul 18, 2023 |
| Unknown       | X79A                        | [2ed232ccd6](https://linux-hardware.org/?probe=2ed232ccd6) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | [3c5ef629e4](https://linux-hardware.org/?probe=3c5ef629e4) | Jul 18, 2023 |
| Gigabyte      | J1800N-D2H                  | [a62fb79aac](https://linux-hardware.org/?probe=a62fb79aac) | Jul 17, 2023 |
| ASUSTek       | H81M-C                      | [d75cfffdca](https://linux-hardware.org/?probe=d75cfffdca) | Jul 17, 2023 |
| Gigabyte      | H77N-WIFI                   | [6bbfd9fb86](https://linux-hardware.org/?probe=6bbfd9fb86) | Jul 17, 2023 |
| Gigabyte      | H77N-WIFI                   | [3f0741555c](https://linux-hardware.org/?probe=3f0741555c) | Jul 17, 2023 |
| ASUSTek       | B85M-G                      | [fc5b33ac00](https://linux-hardware.org/?probe=fc5b33ac00) | Jul 17, 2023 |
| ASUSTek       | P5B-Deluxe                  | [da27044389](https://linux-hardware.org/?probe=da27044389) | Jul 17, 2023 |
| Dell          | 0Y5DDC A00                  | [dd5a0bc45b](https://linux-hardware.org/?probe=dd5a0bc45b) | Jul 17, 2023 |
| MSI           | H61M-P32/W8                 | [e6fab16cf4](https://linux-hardware.org/?probe=e6fab16cf4) | Jul 17, 2023 |
| Gigabyte      | G41M-ES2L                   | [69a2bba4a9](https://linux-hardware.org/?probe=69a2bba4a9) | Jul 16, 2023 |
| ECS           | H61H2-M17                   | [853b239a9a](https://linux-hardware.org/?probe=853b239a9a) | Jul 16, 2023 |
| MSI           | 890FXA-GD70                 | [43f7b3e0e2](https://linux-hardware.org/?probe=43f7b3e0e2) | Jul 16, 2023 |
| MACHINIST     | X99-RS9 V3.0                | [4cb2ff7ed5](https://linux-hardware.org/?probe=4cb2ff7ed5) | Jul 15, 2023 |
| ASUSTek       | P8Z77-V LK                  | [f29be846e3](https://linux-hardware.org/?probe=f29be846e3) | Jul 15, 2023 |
| AZW           | MINI S 10                   | [8f835cc3a7](https://linux-hardware.org/?probe=8f835cc3a7) | Jul 15, 2023 |
| Dell          | 0KWVT8 A03                  | [e07a936bc3](https://linux-hardware.org/?probe=e07a936bc3) | Jul 14, 2023 |
| PC Partner    | A512-H110 HYOSUNG TNS       | [67a987c4e7](https://linux-hardware.org/?probe=67a987c4e7) | Jul 14, 2023 |
| MSI           | B450M PRO-VDH MAX           | [47d9a3330d](https://linux-hardware.org/?probe=47d9a3330d) | Jul 14, 2023 |
| Biostar       | H310MHC2                    | [7952179adb](https://linux-hardware.org/?probe=7952179adb) | Jul 14, 2023 |
| ASUSTek       | H110M-R                     | [b52ebf4fc9](https://linux-hardware.org/?probe=b52ebf4fc9) | Jul 13, 2023 |
| Lenovo        | ThinkCentre M90p 3853W1B    | [72b02c6cc1](https://linux-hardware.org/?probe=72b02c6cc1) | Jul 13, 2023 |
| ASUSTek       | PRIME H510M-R               | [d251995cde](https://linux-hardware.org/?probe=d251995cde) | Jul 13, 2023 |
| Unknown       | Unknown                     | [5dbf56c4bb](https://linux-hardware.org/?probe=5dbf56c4bb) | Jul 13, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [45a5b265be](https://linux-hardware.org/?probe=45a5b265be) | Jul 13, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [d7abb793a4](https://linux-hardware.org/?probe=d7abb793a4) | Jul 12, 2023 |
| ASUSTek       | PRIME B450M-A               | [6321a0ad87](https://linux-hardware.org/?probe=6321a0ad87) | Jul 12, 2023 |
| ASUSTek       | H81M-R                      | [d06f7da2b4](https://linux-hardware.org/?probe=d06f7da2b4) | Jul 12, 2023 |
| ASUSTek       | PRIME B360M-K               | [3a06b254a5](https://linux-hardware.org/?probe=3a06b254a5) | Jul 12, 2023 |
| ASRock        | X370 Pro4                   | [4e8926a95b](https://linux-hardware.org/?probe=4e8926a95b) | Jul 11, 2023 |
| Huanan        | X99 F8D V2.2                | [b170940e9c](https://linux-hardware.org/?probe=b170940e9c) | Jul 11, 2023 |
| AZW           | MINI S 10                   | [3517d6f744](https://linux-hardware.org/?probe=3517d6f744) | Jul 11, 2023 |
| ASRock        | 4Core1600-GLAN              | [3e733151f2](https://linux-hardware.org/?probe=3e733151f2) | Jul 11, 2023 |
| Unknown       | X79                         | [95331fcaf5](https://linux-hardware.org/?probe=95331fcaf5) | Jul 11, 2023 |
| Foxconn       | G33M03                      | [487435e6e7](https://linux-hardware.org/?probe=487435e6e7) | Jul 11, 2023 |
| iRU           | AraT                        | [e3b810837e](https://linux-hardware.org/?probe=e3b810837e) | Jul 11, 2023 |
| ASUSTek       | P5K                         | [c80746e740](https://linux-hardware.org/?probe=c80746e740) | Jul 11, 2023 |
| Gigabyte      | GA-MA770-ES3                | [9af789d1d2](https://linux-hardware.org/?probe=9af789d1d2) | Jul 10, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ROSA R11           | 1606     | 10.76%  |
| ROSA R10           | 1538     | 10.3%   |
| ROSA R8.1          | 1139     | 7.63%   |
| ROSA R8            | 1050     | 7.03%   |
| ROSA R9            | 928      | 6.22%   |
| ROSA 12.2          | 918      | 6.15%   |
| ROSA R11.1         | 891      | 5.97%   |
| Debian 11          | 703      | 4.71%   |
| ROSA 12.4          | 447      | 2.99%   |
| ROSA 12.3          | 443      | 2.97%   |
| Ubuntu 20.04       | 339      | 2.27%   |
| OpenMandriva 4.2   | 234      | 1.57%   |
| Ubuntu 18.04       | 205      | 1.37%   |
| Debian 12          | 195      | 1.31%   |
| OpenMandriva 4.3   | 185      | 1.24%   |
| Ubuntu 22.04       | 176      | 1.18%   |
| ROSA 12.1          | 157      | 1.05%   |
| Arch Rolling       | 147      | 0.98%   |
| ROSA 12            | 119      | 0.8%    |
| KDE neon 20.04     | 87       | 0.58%   |
| Debian 10          | 85       | 0.57%   |
| Xubuntu 20.04      | 81       | 0.54%   |
| Kometa P10         | 81       | 0.54%   |
| OpenMandriva 23.01 | 74       | 0.5%    |
| Manjaro            | 73       | 0.49%   |
| Red OS 7.3         | 72       | 0.48%   |
| OpenMandriva 23.03 | 72       | 0.48%   |
| Arch               | 68       | 0.46%   |
| Linux Mint 20.3    | 58       | 0.39%   |
| RED X3             | 56       | 0.38%   |
| RED X4             | 52       | 0.35%   |
| ALT Linux 10.1     | 52       | 0.35%   |
| Linux Mint 18.3    | 51       | 0.34%   |
| Kubuntu 20.04      | 51       | 0.34%   |
| Fedora 36          | 49       | 0.33%   |
| Red OS 7.3.2       | 47       | 0.31%   |
| Red OS 7.3.1       | 47       | 0.31%   |
| Linux Mint 21.1    | 47       | 0.31%   |
| Fedora 38          | 47       | 0.31%   |
| Linux Mint 19.3    | 44       | 0.29%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| ROSA             | 7900     | 60.31%  |
| Debian           | 981      | 7.49%   |
| Ubuntu           | 870      | 6.64%   |
| OpenMandriva     | 644      | 4.92%   |
| Linux Mint       | 435      | 3.32%   |
| Fedora           | 273      | 2.08%   |
| ALT Linux        | 254      | 1.94%   |
| Manjaro          | 246      | 1.88%   |
| Arch             | 209      | 1.6%    |
| Red OS           | 165      | 1.26%   |
| Xubuntu          | 126      | 0.96%   |
| KDE neon         | 118      | 0.9%    |
| RED              | 114      | 0.87%   |
| Kubuntu          | 109      | 0.83%   |
| Gentoo           | 63       | 0.48%   |
| Pop!_OS          | 54       | 0.41%   |
| Endless          | 54       | 0.41%   |
| openSUSE         | 48       | 0.37%   |
| Ubuntu MATE      | 31       | 0.24%   |
| Elementary       | 31       | 0.24%   |
| ArcoLinux        | 28       | 0.21%   |
| Clear Linux      | 27       | 0.21%   |
| CentOS           | 25       | 0.19%   |
| RELS             | 23       | 0.18%   |
| Zorin            | 21       | 0.16%   |
| Ubuntu Unity     | 20       | 0.15%   |
| Lubuntu          | 19       | 0.15%   |
| LMDE             | 19       | 0.15%   |
| Kali             | 18       | 0.14%   |
| EndeavourOS      | 12       | 0.09%   |
| MX               | 10       | 0.08%   |
| Astra Linux      | 10       | 0.08%   |
| Artix            | 8        | 0.06%   |
| Xero             | 6        | 0.05%   |
| Solus            | 6        | 0.05%   |
| Nobara           | 6        | 0.05%   |
| NixOS            | 6        | 0.05%   |
| Rocky Linux      | 5        | 0.04%   |
| org.kde.Platform | 5        | 0.04%   |
| Devuan           | 5        | 0.04%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.74-generic-2rosa2021.1-x86_64  | 797      | 4.96%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 702      | 4.37%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 697      | 4.34%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 667      | 4.15%   |
| 5.10.0-7-amd64                      | 472      | 2.94%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 401      | 2.5%    |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 332      | 2.07%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 318      | 1.98%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 255      | 1.59%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 250      | 1.56%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 235      | 1.46%   |
| 5.10.14-desktop-1omv4002            | 224      | 1.39%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 205      | 1.28%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 199      | 1.24%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 196      | 1.22%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 195      | 1.21%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 189      | 1.18%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 186      | 1.16%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 183      | 1.14%   |
| 5.16.7-desktop-1omv4003             | 171      | 1.06%   |
| 4.15.0-desktop-45.1rosa-i586        | 169      | 1.05%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 168      | 1.05%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 165      | 1.03%   |
| 5.4.32-generic-2rosa-x86_64         | 161      | 1%      |
| 6.1.0-4-amd64                       | 151      | 0.94%   |
| 5.4.83-generic-2rosa-x86_64         | 151      | 0.94%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 151      | 0.94%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 149      | 0.93%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 148      | 0.92%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 138      | 0.86%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 137      | 0.85%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 112      | 0.7%    |
| 4.1.25-nrj-desktop-1rosa-i586       | 112      | 0.7%    |
| 5.10.0-2-amd64                      | 110      | 0.68%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 93       | 0.58%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 92       | 0.57%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 91       | 0.57%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 83       | 0.52%   |
| 6.1.46-generic-2rosa2021.1-x86_64   | 78       | 0.49%   |
| 6.2.6-desktop-1omv2390              | 71       | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 2015     | 12.93%  |
| 4.9.60   | 884      | 5.67%   |
| 4.9.20   | 846      | 5.43%   |
| 5.10.74  | 811      | 5.2%    |
| 5.10.0   | 704      | 4.52%   |
| 5.4.0    | 559      | 3.59%   |
| 4.1.34   | 546      | 3.5%    |
| 4.1.38   | 434      | 2.79%   |
| 4.1.25   | 430      | 2.76%   |
| 4.9.9    | 402      | 2.58%   |
| 4.9.124  | 395      | 2.53%   |
| 5.15.0   | 312      | 2%      |
| 4.9.155  | 264      | 1.69%   |
| 4.9.76   | 251      | 1.61%   |
| 4.9.41   | 250      | 1.6%    |
| 6.1.20   | 247      | 1.59%   |
| 5.10.14  | 224      | 1.44%   |
| 5.4.32   | 215      | 1.38%   |
| 6.1.0    | 206      | 1.32%   |
| 5.4.83   | 194      | 1.24%   |
| 5.10.118 | 174      | 1.12%   |
| 5.16.7   | 172      | 1.1%    |
| 5.15.75  | 162      | 1.04%   |
| 5.8.0    | 139      | 0.89%   |
| 5.15.79  | 138      | 0.89%   |
| 5.3.0    | 137      | 0.88%   |
| 5.11.0   | 130      | 0.83%   |
| 4.9.95   | 120      | 0.77%   |
| 5.0.0    | 111      | 0.71%   |
| 4.9.111  | 104      | 0.67%   |
| 5.19.0   | 99       | 0.64%   |
| 5.10.71  | 94       | 0.6%    |
| 5.13.0   | 89       | 0.57%   |
| 4.18.0   | 83       | 0.53%   |
| 4.9.87   | 82       | 0.53%   |
| 6.1.46   | 80       | 0.51%   |
| 6.2.6    | 78       | 0.5%    |
| 4.19.0   | 76       | 0.49%   |
| 6.1.1    | 72       | 0.46%   |
| 6.1.38   | 69       | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 3195     | 21.98%  |
| 5.10    | 2258     | 15.53%  |
| 4.15    | 2027     | 13.94%  |
| 4.1     | 1369     | 9.42%   |
| 5.4     | 1143     | 7.86%   |
| 5.15    | 961      | 6.61%   |
| 6.1     | 766      | 5.27%   |
| 5.16    | 242      | 1.66%   |
| 5.11    | 208      | 1.43%   |
| 5.8     | 196      | 1.35%   |
| 5.3     | 186      | 1.28%   |
| 6.2     | 183      | 1.26%   |
| 5.19    | 145      | 1%      |
| 5.0     | 130      | 0.89%   |
| 5.13    | 125      | 0.86%   |
| 5.18    | 124      | 0.85%   |
| 6.0     | 117      | 0.8%    |
| 4.19    | 111      | 0.76%   |
| 4.18    | 93       | 0.64%   |
| 6.4     | 92       | 0.63%   |
| 5.17    | 85       | 0.58%   |
| 5.14    | 72       | 0.5%    |
| 6.5     | 63       | 0.43%   |
| 5.6     | 60       | 0.41%   |
| 5.9     | 57       | 0.39%   |
| 4.4     | 52       | 0.36%   |
| 4.13    | 51       | 0.35%   |
| 5.12    | 47       | 0.32%   |
| 6.3     | 42       | 0.29%   |
| 3.10    | 40       | 0.28%   |
| 5.7     | 38       | 0.26%   |
| 4.8     | 36       | 0.25%   |
| 5.5     | 27       | 0.19%   |
| 4.14    | 26       | 0.18%   |
| 4.16    | 25       | 0.17%   |
| 3.14    | 23       | 0.16%   |
| 5.2     | 21       | 0.14%   |
| 4.10    | 20       | 0.14%   |
| 4.20    | 13       | 0.09%   |
| 4.17    | 13       | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 11175    | 87.15%  |
| i686        | 1639     | 12.78%  |
| e2k         | 5        | 0.04%   |
| ppc64       | 1        | 0.01%   |
| loongarch64 | 1        | 0.01%   |
| armv6l      | 1        | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| KDE4              | 4729     | 34.73%  |
| KDE5              | 3801     | 27.91%  |
| GNOME             | 1907     | 14%     |
| Unknown           | 1261     | 9.26%   |
| XFCE              | 428      | 3.14%   |
| MATE              | 406      | 2.98%   |
| LXQt              | 359      | 2.64%   |
| X-Cinnamon        | 220      | 1.62%   |
| Cinnamon          | 200      | 1.47%   |
| KDE               | 137      | 1.01%   |
| Pantheon          | 30       | 0.22%   |
| LXDE              | 25       | 0.18%   |
| Unity             | 20       | 0.15%   |
| i3                | 17       | 0.12%   |
| Budgie            | 11       | 0.08%   |
| GNOME Flashback   | 8        | 0.06%   |
| Deepin            | 8        | 0.06%   |
| GNOME Classic     | 7        | 0.05%   |
| Openbox           | 6        | 0.04%   |
| fly               | 6        | 0.04%   |
| awesome           | 5        | 0.04%   |
| Hyprland          | 4        | 0.03%   |
| sway              | 3        | 0.02%   |
| lightdm-xsession  | 3        | 0.02%   |
| ICEWM             | 3        | 0.02%   |
| bspwm             | 3        | 0.02%   |
| xmonad            | 2        | 0.01%   |
| DWM               | 2        | 0.01%   |
| x-session-manager | 1        | 0.01%   |
| X-Generic         | 1        | 0.01%   |
| Trinity           | 1        | 0.01%   |
| steamos           | 1        | 0.01%   |
| i3-with-shmlog    | 1        | 0.01%   |
| /etc/X11/Xsession | 1        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 10054    | 76.67%  |
| Wayland | 1992     | 15.19%  |
| Unknown | 908      | 6.92%   |
| Tty     | 159      | 1.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDM     | 4771     | 35.17%  |
| SDDM    | 3830     | 28.23%  |
| Unknown | 2268     | 16.72%  |
| GDM     | 1534     | 11.31%  |
| LightDM | 506      | 3.73%   |
| TDM     | 320      | 2.36%   |
| GDM3    | 276      | 2.03%   |
| MDM     | 22       | 0.16%   |
| XDM     | 10       | 0.07%   |
| SLiM    | 8        | 0.06%   |
| LXDM    | 8        | 0.06%   |
| FLY-DM  | 7        | 0.05%   |
| Ly      | 2        | 0.01%   |
| WDM     | 1        | 0.01%   |
| NODM    | 1        | 0.01%   |
| LDM     | 1        | 0.01%   |
| GREETD  | 1        | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 6247     | 47.19%  |
| ru_RU       | 5844     | 44.14%  |
| en_US       | 988      | 7.46%   |
| C           | 75       | 0.57%   |
| en_GB       | 27       | 0.2%    |
| ru_UA       | 9        | 0.07%   |
| ru_RU.UTF_8 | 9        | 0.07%   |
| ru_RU.UTF8  | 8        | 0.06%   |
| C.UTF8      | 7        | 0.05%   |
| POSIX       | 4        | 0.03%   |
| cv_RU       | 4        | 0.03%   |
| en_DK       | 3        | 0.02%   |
| tt_RU       | 2        | 0.02%   |
| ba_RU       | 2        | 0.02%   |
| zh_CN       | 1        | 0.01%   |
| uk_UA       | 1        | 0.01%   |
| myv_RU      | 1        | 0.01%   |
| fr_FR       | 1        | 0.01%   |
| en_RU       | 1        | 0.01%   |
| en_CA       | 1        | 0.01%   |
| en_AU       | 1        | 0.01%   |
| en_AG       | 1        | 0.01%   |
| de_DE       | 1        | 0.01%   |
| ce_RU       | 1        | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 9191     | 70.68%  |
| EFI  | 3813     | 29.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 7434     | 55.14%  |
| Unknown  | 3833     | 28.43%  |
| Overlay  | 1276     | 9.47%   |
| Btrfs    | 637      | 4.73%   |
| Xfs      | 107      | 0.79%   |
| Ext3     | 46       | 0.34%   |
| Zfs      | 40       | 0.3%    |
| Tmpfs    | 37       | 0.27%   |
| F2fs     | 27       | 0.2%    |
| Ext2     | 20       | 0.15%   |
| Aufs     | 6        | 0.04%   |
| Reiserfs | 4        | 0.03%   |
| Jfs      | 4        | 0.03%   |
| XXXXXXX  | 3        | 0.02%   |
| SAMSUNG  | 3        | 0.02%   |
| Rootfs   | 2        | 0.01%   |
| XXXXX    | 1        | 0.01%   |
| Exfat    | 1        | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 6143     | 45.51%  |
| GPT     | 4201     | 31.12%  |
| Unknown | 3155     | 23.37%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10967    | 83.07%  |
| Yes       | 2235     | 16.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 8338     | 62.53%  |
| Yes       | 4996     | 37.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 4441     | 35.02%  |
| Gigabyte Technology | 3116     | 24.57%  |
| ASRock              | 1380     | 10.88%  |
| MSI                 | 1374     | 10.84%  |
| Intel               | 390      | 3.08%   |
| ECS                 | 277      | 2.18%   |
| Unknown             | 206      | 1.62%   |
| Hewlett-Packard     | 197      | 1.55%   |
| Acer                | 156      | 1.23%   |
| Biostar             | 143      | 1.13%   |
| Foxconn             | 128      | 1.01%   |
| Lenovo              | 111      | 0.88%   |
| Dell                | 99       | 0.78%   |
| Huanan              | 96       | 0.76%   |
| Pegatron            | 87       | 0.69%   |
| Supermicro          | 51       | 0.4%    |
| AZW                 | 28       | 0.22%   |
| DEPO Computers      | 27       | 0.21%   |
| EPoX Computer       | 25       | 0.2%    |
| WinFast             | 21       | 0.17%   |
| Fujitsu             | 19       | 0.15%   |
| Aquarius            | 17       | 0.13%   |
| MACHINIST           | 16       | 0.13%   |
| Fujitsu Siemens     | 13       | 0.1%    |
| OEM                 | 12       | 0.09%   |
| Nvidia              | 10       | 0.08%   |
| AMD                 | 10       | 0.08%   |
| Kraftway            | 9        | 0.07%   |
| iRU                 | 9        | 0.07%   |
| SiS Technology      | 8        | 0.06%   |
| Shuttle             | 8        | 0.06%   |
| JW Technology       | 8        | 0.06%   |
| Kllisre             | 7        | 0.06%   |
| ABIT                | 6        | 0.05%   |
| 3Logic Group        | 6        | 0.05%   |
| Packard Bell        | 5        | 0.04%   |
| MAINBRD             | 5        | 0.04%   |
| Lite-On             | 5        | 0.04%   |
| IBM                 | 5        | 0.04%   |
| eMachines           | 5        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS All Series          | 402      | 3.17%   |
| Unknown                  | 224      | 1.77%   |
| MSI MS-7996              | 78       | 0.62%   |
| Gigabyte 970A-DS3P       | 73       | 0.58%   |
| MSI MS-7817              | 72       | 0.57%   |
| ASUS M5A78L-M LX3        | 69       | 0.54%   |
| ASUS H110M-R             | 64       | 0.5%    |
| ASUS P8H61-M LX3 R2.0    | 60       | 0.47%   |
| ASUS S20 K29             | 55       | 0.43%   |
| Intel SKYBAY             | 53       | 0.42%   |
| ASUS P5K                 | 51       | 0.4%    |
| ASUS M5A97 R2.0          | 50       | 0.39%   |
| ASRock G31M-S            | 47       | 0.37%   |
| MSI MS-7529              | 46       | 0.36%   |
| Gigabyte H61M-S1         | 46       | 0.36%   |
| Gigabyte G31M-ES2L       | 45       | 0.35%   |
| ASUS P5G41T-M LX2/GB     | 45       | 0.35%   |
| ASUS P5KPL-AM            | 44       | 0.35%   |
| Gigabyte H61M-S2PV       | 43       | 0.34%   |
| ASUS PRIME A320M-K       | 43       | 0.34%   |
| MSI MS-7592              | 41       | 0.32%   |
| ASRock N68C-S UCC        | 40       | 0.32%   |
| Gigabyte H81M-S2V        | 39       | 0.31%   |
| ASUS M5A78L-M/USB3       | 39       | 0.31%   |
| ASUS M5A97 LE R2.0       | 38       | 0.3%    |
| ECS G31T-M9              | 36       | 0.28%   |
| Gigabyte Z77-DS3H        | 35       | 0.28%   |
| Gigabyte A320M-S2H V2    | 34       | 0.27%   |
| ASUS P5B                 | 34       | 0.27%   |
| ASUS A68HM-K             | 34       | 0.27%   |
| ASUS PRIME H310M-R R2.0  | 33       | 0.26%   |
| ASUS P5Q SE2             | 33       | 0.26%   |
| ASUS P5KPL-AM IN/ROEM/SI | 33       | 0.26%   |
| ASUS P8Z77-V LX          | 32       | 0.25%   |
| ASUS H110M-K             | 32       | 0.25%   |
| ASRock G41M-VS3          | 32       | 0.25%   |
| MSI MS-7721              | 31       | 0.24%   |
| Gigabyte GA-78LMT-S2     | 31       | 0.24%   |
| Gigabyte GA-78LMT-S2P    | 30       | 0.24%   |
| ASUS P8B75-V             | 30       | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 465      | 3.67%   |
| ASUS All           | 402      | 3.17%   |
| Unknown            | 224      | 1.77%   |
| ASUS P8H61-M       | 198      | 1.56%   |
| ASUS M5A78L-M      | 180      | 1.42%   |
| ASUS P5KPL-AM      | 130      | 1.03%   |
| ASUS M5A97         | 118      | 0.93%   |
| ASUS P5G41T-M      | 112      | 0.88%   |
| ASUS P5K           | 105      | 0.83%   |
| ASUS TUF           | 93       | 0.73%   |
| Acer Aspire        | 92       | 0.73%   |
| ASUS P8Z77-V       | 91       | 0.72%   |
| ASUS ROG           | 88       | 0.69%   |
| Gigabyte B450M     | 80       | 0.63%   |
| MSI MS-7996        | 78       | 0.62%   |
| HP Compaq          | 74       | 0.58%   |
| Gigabyte 970A-DS3P | 74       | 0.58%   |
| ASUS P5Q           | 74       | 0.58%   |
| MSI MS-7817        | 72       | 0.57%   |
| Dell OptiPlex      | 68       | 0.54%   |
| ASUS H110M-R       | 64       | 0.5%    |
| Gigabyte B450      | 59       | 0.47%   |
| Gigabyte A320M-S2H | 56       | 0.44%   |
| ASUS S20           | 55       | 0.43%   |
| ASUS P8H77-V       | 55       | 0.43%   |
| ASUS P8H67-M       | 55       | 0.43%   |
| ASUS P8H61-MX      | 54       | 0.43%   |
| Lenovo ThinkCentre | 53       | 0.42%   |
| Intel SKYBAY       | 53       | 0.42%   |
| ASUS SABERTOOTH    | 51       | 0.4%    |
| Acer Veriton       | 50       | 0.39%   |
| ASUS P7H55-M       | 48       | 0.38%   |
| ASRock G31M-S      | 47       | 0.37%   |
| MSI MS-7529        | 46       | 0.36%   |
| Gigabyte H61M-S1   | 46       | 0.36%   |
| Gigabyte H310M     | 46       | 0.36%   |
| Gigabyte G31M-ES2L | 45       | 0.35%   |
| ASUS P8B75-M       | 45       | 0.35%   |
| Gigabyte H61M-S2PV | 43       | 0.34%   |
| Gigabyte H410M     | 42       | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 1679     | 13.24%  |
| 2009    | 1083     | 8.54%   |
| 2011    | 1068     | 8.42%   |
| 2010    | 973      | 7.67%   |
| 2018    | 954      | 7.52%   |
| 2013    | 901      | 7.11%   |
| 2008    | 797      | 6.29%   |
| 2007    | 755      | 5.95%   |
| 2014    | 525      | 4.14%   |
| 2016    | 513      | 4.05%   |
| 2020    | 506      | 3.99%   |
| 2006    | 489      | 3.86%   |
| 2019    | 482      | 3.8%    |
| 2017    | 467      | 3.68%   |
| 2015    | 455      | 3.59%   |
| 2021    | 453      | 3.57%   |
| 2022    | 205      | 1.62%   |
| 2005    | 199      | 1.57%   |
| 2004    | 71       | 0.56%   |
| 2003    | 44       | 0.35%   |
| 2023    | 27       | 0.21%   |
| Unknown | 21       | 0.17%   |
| 2002    | 8        | 0.06%   |
| 2001    | 4        | 0.03%   |
| 2000    | 1        | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 12680    | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 12590    | 99.24%  |
| Enabled  | 97       | 0.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12678    | 99.98%  |
| Yes  | 2        | 0.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 3197     | 24.2%   |
| 8.01-16.0       | 2884     | 21.83%  |
| 4.01-8.0        | 2100     | 15.89%  |
| 16.01-24.0      | 1990     | 15.06%  |
| 1.01-2.0        | 1055     | 7.98%   |
| 32.01-64.0      | 766      | 5.8%    |
| 2.01-3.0        | 665      | 5.03%   |
| 64.01-256.0     | 210      | 1.59%   |
| 24.01-32.0      | 162      | 1.23%   |
| 0.51-1.0        | 159      | 1.2%    |
| 0.01-0.5        | 13       | 0.1%    |
| More than 256.0 | 9        | 0.07%   |
| Unknown         | 3        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 5484     | 37.99%  |
| 0.51-1.0    | 4752     | 32.92%  |
| 2.01-3.0    | 1861     | 12.89%  |
| 4.01-8.0    | 882      | 6.11%   |
| 3.01-4.0    | 763      | 5.29%   |
| 0.01-0.5    | 307      | 2.13%   |
| 8.01-16.0   | 270      | 1.87%   |
| 16.01-24.0  | 60       | 0.42%   |
| 32.01-64.0  | 21       | 0.15%   |
| 24.01-32.0  | 19       | 0.13%   |
| Unknown     | 12       | 0.08%   |
| 64.01-256.0 | 6        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 6605     | 49.04%  |
| 2       | 3647     | 27.08%  |
| 3       | 1798     | 13.35%  |
| 4       | 794      | 5.9%    |
| 5       | 328      | 2.44%   |
| 6       | 109      | 0.81%   |
| 0       | 90       | 0.67%   |
| 7       | 48       | 0.36%   |
| 8       | 23       | 0.17%   |
| 9       | 10       | 0.07%   |
| 10      | 5        | 0.04%   |
| 17      | 2        | 0.01%   |
| 12      | 2        | 0.01%   |
| Unknown | 2        | 0.01%   |
| 26      | 1        | 0.01%   |
| 25      | 1        | 0.01%   |
| 18      | 1        | 0.01%   |
| 16      | 1        | 0.01%   |
| 13      | 1        | 0.01%   |
| 11      | 1        | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 6984     | 53.79%  |
| Yes       | 6001     | 46.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12561    | 99.05%  |
| No        | 120      | 0.95%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9775     | 75.76%  |
| Yes       | 3127     | 24.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11011    | 85.59%  |
| Yes       | 1854     | 14.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 12680    | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Moscow           | 2234     | 16.5%   |
| St Petersburg    | 884      | 6.53%   |
| Voronezh         | 877      | 6.48%   |
| Pecherskoye      | 421      | 3.11%   |
| Novosibirsk      | 405      | 2.99%   |
| Yekaterinburg    | 344      | 2.54%   |
| Krasnodar        | 298      | 2.2%    |
| Samara           | 263      | 1.94%   |
| Nizhniy Novgorod | 253      | 1.87%   |
| Rostov-on-Don    | 244      | 1.8%    |
| Perm             | 218      | 1.61%   |
| Chelyabinsk      | 211      | 1.56%   |
| Krasnoyarsk      | 167      | 1.23%   |
| Saratov          | 148      | 1.09%   |
| Omsk             | 145      | 1.07%   |
| Volgograd        | 135      | 1%      |
| Ufa              | 133      | 0.98%   |
| Kazan’         | 127      | 0.94%   |
| Vladivostok      | 116      | 0.86%   |
| Stavropol        | 113      | 0.83%   |
| Barnaul          | 111      | 0.82%   |
| Irkutsk          | 105      | 0.78%   |
| Tyumen           | 103      | 0.76%   |
| Khabarovsk       | 101      | 0.75%   |
| Ulyanovsk        | 87       | 0.64%   |
| Tomsk            | 85       | 0.63%   |
| Orenburg         | 83       | 0.61%   |
| Bryansk          | 82       | 0.61%   |
| Kemerovo         | 79       | 0.58%   |
| Tolyatti         | 78       | 0.58%   |
| Yaroslavl        | 77       | 0.57%   |
| Novokuznetsk     | 77       | 0.57%   |
| Belgorod         | 77       | 0.57%   |
| Tula             | 73       | 0.54%   |
| Cheboksary       | 72       | 0.53%   |
| Izhevsk          | 67       | 0.49%   |
| Penza            | 65       | 0.48%   |
| Lipetsk          | 65       | 0.48%   |
| Kaliningrad      | 64       | 0.47%   |
| Ryazan           | 63       | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5053     | 8243   | 23.87%  |
| WDC                 | 5004     | 8701   | 23.64%  |
| Samsung Electronics | 1871     | 2888   | 8.84%   |
| Toshiba             | 1419     | 2136   | 6.7%    |
| Kingston            | 1129     | 1560   | 5.33%   |
| Hitachi             | 1089     | 1565   | 5.15%   |
| A-DATA Technology   | 396      | 550    | 1.87%   |
| China               | 361      | 514    | 1.71%   |
| Crucial             | 355      | 472    | 1.68%   |
| SPCC                | 317      | 406    | 1.5%    |
| Maxtor              | 294      | 374    | 1.39%   |
| Intel               | 254      | 458    | 1.2%    |
| OCZ                 | 250      | 324    | 1.18%   |
| SanDisk             | 239      | 360    | 1.13%   |
| Apacer              | 231      | 312    | 1.09%   |
| HGST                | 211      | 333    | 1%      |
| Plextor             | 208      | 320    | 0.98%   |
| Patriot             | 141      | 186    | 0.67%   |
| AMD                 | 141      | 181    | 0.67%   |
| Smartbuy            | 135      | 187    | 0.64%   |
| Silicon Motion      | 113      | 143    | 0.53%   |
| Netac               | 106      | 206    | 0.5%    |
| KingSpec            | 102      | 127    | 0.48%   |
| Transcend           | 94       | 118    | 0.44%   |
| HUAWEI              | 90       | 106    | 0.43%   |
| GOODRAM             | 89       | 125    | 0.42%   |
| Corsair             | 86       | 126    | 0.41%   |
| Unknown             | 77       | 118    | 0.36%   |
| Gigabyte Technology | 69       | 84     | 0.33%   |
| Phison              | 58       | 67     | 0.27%   |
| XPG                 | 50       | 66     | 0.24%   |
| XrayDisk            | 48       | 62     | 0.23%   |
| KingDian            | 47       | 74     | 0.22%   |
| Fujitsu             | 44       | 59     | 0.21%   |
| JMicron Technology  | 41       | 42     | 0.19%   |
| Foxline             | 38       | 47     | 0.18%   |
| Unknown             | 38       | 41     | 0.18%   |
| Kingmax             | 35       | 63     | 0.17%   |
| Hewlett-Packard     | 34       | 55     | 0.16%   |
| AXIOMTEK            | 30       | 32     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 410      | 1.69%   |
| Toshiba DT01ACA050 500GB         | 302      | 1.24%   |
| Seagate ST1000DM010-2EP102 1TB   | 276      | 1.14%   |
| Toshiba HDWD110 1TB              | 270      | 1.11%   |
| Seagate ST3500418AS 500GB        | 262      | 1.08%   |
| WDC WD10EZEX-08WN4A0 1TB         | 245      | 1.01%   |
| Seagate ST1000DM003-1CH162 1TB   | 211      | 0.87%   |
| Toshiba DT01ACA100 1TB           | 207      | 0.85%   |
| Kingston SA400S37240G 240GB SSD  | 182      | 0.75%   |
| Kingston SA400S37120G 120GB SSD  | 172      | 0.71%   |
| Samsung SSD 860 EVO 250GB        | 155      | 0.64%   |
| Kingston SV300S37A120G 120GB SSD | 151      | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 145      | 0.6%    |
| WDC WD5000AAKX-001CA0 500GB      | 142      | 0.58%   |
| Seagate ST3250410AS 250GB        | 141      | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB   | 139      | 0.57%   |
| Seagate ST380011A 80GB           | 132      | 0.54%   |
| Seagate ST380815AS 80GB          | 130      | 0.54%   |
| Seagate ST31000524AS 1TB         | 127      | 0.52%   |
| Seagate ST3160815AS 160GB        | 124      | 0.51%   |
| Seagate ST31000528AS 1TB         | 122      | 0.5%    |
| Hitachi HDS721050CLA362 500GB    | 122      | 0.5%    |
| Seagate ST3250310AS 250GB        | 118      | 0.49%   |
| Toshiba HDWD105 500GB            | 109      | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 108      | 0.44%   |
| Seagate ST1000DM003-9YN162 1TB   | 107      | 0.44%   |
| Crucial CT480BX500SSD1 480GB     | 106      | 0.44%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 95       | 0.39%   |
| Seagate ST250DM000-1BD141 250GB  | 95       | 0.39%   |
| Seagate ST3500413AS 500GB        | 94       | 0.39%   |
| Seagate ST3250318AS 250GB        | 92       | 0.38%   |
| WDC WD10EZEX-00BN5A0 1TB         | 88       | 0.36%   |
| Samsung SSD 860 EVO 500GB        | 84       | 0.35%   |
| SPCC Solid State Disk 120GB      | 83       | 0.34%   |
| Seagate ST3320613AS 320GB        | 83       | 0.34%   |
| Crucial CT240BX500SSD1 240GB     | 81       | 0.33%   |
| Seagate ST2000DM001-1CH164 2TB   | 80       | 0.33%   |
| WDC WD5000AADS-00S9B0 500GB      | 77       | 0.32%   |
| Seagate ST3320620AS 320GB        | 77       | 0.32%   |
| Kingston SA400S37480G 480GB SSD  | 76       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5035     | 8198   | 37.09%  |
| WDC                 | 4664     | 7932   | 34.35%  |
| Toshiba             | 1362     | 2018   | 10.03%  |
| Hitachi             | 1088     | 1564   | 8.01%   |
| Samsung Electronics | 780      | 1128   | 5.75%   |
| Maxtor              | 291      | 371    | 2.14%   |
| HGST                | 211      | 333    | 1.55%   |
| Fujitsu             | 43       | 58     | 0.32%   |
| Unknown             | 21       | 33     | 0.15%   |
| IBM/Hitachi         | 12       | 15     | 0.09%   |
| Hewlett-Packard     | 11       | 22     | 0.08%   |
| External            | 9        | 11     | 0.07%   |
| USB3.0              | 5        | 5      | 0.04%   |
| IBM                 | 4        | 4      | 0.03%   |
| Quantum             | 3        | 3      | 0.02%   |
| ASMT                | 3        | 14     | 0.02%   |
| WD MediaMax         | 2        | 2      | 0.01%   |
| USB                 | 2        | 2      | 0.01%   |
| Synology            | 2        | 3      | 0.01%   |
| JMicron Technology  | 2        | 2      | 0.01%   |
| ExcelStor           | 2        | 2      | 0.01%   |
| CLOVER              | 2        | 2      | 0.01%   |
| ASMT106x            | 2        | 3      | 0.01%   |
| Apple               | 2        | 2      | 0.01%   |
| Unknown             | 2        | 2      | 0.01%   |
| USB 3.0             | 1        | 1      | 0.01%   |
| TDAS                | 1        | 4      | 0.01%   |
| StoreJet            | 1        | 1      | 0.01%   |
| Silicon             | 1        | 1      | 0.01%   |
| SAGE                | 1        | 1      | 0.01%   |
| Pioneer             | 1        | 1      | 0.01%   |
| MR2020              | 1        | 1      | 0.01%   |
| Min Yi U            | 1        | 1      | 0.01%   |
| MARVELL             | 1        | 1      | 0.01%   |
| MARSHAL             | 1        | 1      | 0.01%   |
| LIO-ORG             | 1        | 1      | 0.01%   |
| KESU                | 1        | 1      | 0.01%   |
| IET                 | 1        | 2      | 0.01%   |
| HPE                 | 1        | 2      | 0.01%   |
| HGST HTS            | 1        | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 998      | 1366   | 16.21%  |
| Samsung Electronics | 718      | 1058   | 11.66%  |
| WDC                 | 507      | 693    | 8.23%   |
| China               | 358      | 511    | 5.81%   |
| Crucial             | 343      | 454    | 5.57%   |
| A-DATA Technology   | 323      | 430    | 5.25%   |
| SPCC                | 298      | 380    | 4.84%   |
| OCZ                 | 249      | 323    | 4.04%   |
| Apacer              | 200      | 267    | 3.25%   |
| Plextor             | 189      | 277    | 3.07%   |
| SanDisk             | 186      | 284    | 3.02%   |
| Intel               | 180      | 341    | 2.92%   |
| Patriot             | 130      | 174    | 2.11%   |
| AMD                 | 128      | 160    | 2.08%   |
| Smartbuy            | 125      | 174    | 2.03%   |
| KingSpec            | 100      | 125    | 1.62%   |
| Transcend           | 83       | 102    | 1.35%   |
| Netac               | 83       | 177    | 1.35%   |
| Goodram             | 83       | 119    | 1.35%   |
| Corsair             | 80       | 116    | 1.3%    |
| Toshiba             | 79       | 111    | 1.28%   |
| Gigabyte Technology | 50       | 56     | 0.81%   |
| KingDian            | 47       | 74     | 0.76%   |
| XrayDisk            | 38       | 51     | 0.62%   |
| Foxline             | 36       | 45     | 0.58%   |
| Kingmax             | 35       | 63     | 0.57%   |
| AXIOMTEK            | 30       | 32     | 0.49%   |
| Unknown             | 26       | 29     | 0.42%   |
| Qumo                | 23       | 31     | 0.37%   |
| Team                | 18       | 20     | 0.29%   |
| Hewlett-Packard     | 17       | 24     | 0.28%   |
| Micron Technology   | 14       | 18     | 0.23%   |
| KingFast            | 14       | 18     | 0.23%   |
| Seagate             | 13       | 25     | 0.21%   |
| Londisk             | 13       | 15     | 0.21%   |
| Palit               | 11       | 16     | 0.18%   |
| OCZ-VERTEX3         | 11       | 16     | 0.18%   |
| Zheino              | 10       | 14     | 0.16%   |
| TO Exter            | 10       | 11     | 0.16%   |
| PNY                 | 10       | 12     | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 10500    | 21750  | 60.72%  |
| SSD     | 5134     | 8608   | 29.69%  |
| NVMe    | 1402     | 2155   | 8.11%   |
| Unknown | 237      | 277    | 1.37%   |
| MMC     | 19       | 25     | 0.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 12199    | 30056  | 86.91%  |
| NVMe | 1381     | 2123   | 9.84%   |
| SAS  | 438      | 611    | 3.12%   |
| MMC  | 19       | 25     | 0.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 10374    | 19931  | 63.14%  |
| 0.51-1.0        | 4308     | 7423   | 26.22%  |
| 1.01-2.0        | 1142     | 1920   | 6.95%   |
| 2.01-3.0        | 265      | 448    | 1.61%   |
| 3.01-4.0        | 201      | 341    | 1.22%   |
| 4.01-10.0       | 107      | 236    | 0.65%   |
| 10.01-20.0      | 24       | 49     | 0.15%   |
| More than 100.0 | 7        | 8      | 0.04%   |
| 20.01-50.0      | 1        | 1      | 0.01%   |
| 0               | 1        | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 3589     | 25.08%  |
| 251-500        | 2482     | 17.34%  |
| 501-1000       | 1803     | 12.6%   |
| 1-20           | 1453     | 10.15%  |
| 51-100         | 1389     | 9.71%   |
| 1001-2000      | 1117     | 7.81%   |
| Unknown        | 848      | 5.93%   |
| 21-50          | 803      | 5.61%   |
| More than 3000 | 416      | 2.91%   |
| 2001-3000      | 411      | 2.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 7382     | 51.4%   |
| 21-50          | 1493     | 10.39%  |
| 101-250        | 1189     | 8.28%   |
| 51-100         | 977      | 6.8%    |
| 251-500        | 927      | 6.45%   |
| Unknown        | 848      | 5.9%    |
| 501-1000       | 768      | 5.35%   |
| 1001-2000      | 466      | 3.24%   |
| More than 3000 | 173      | 1.2%    |
| 2001-3000      | 139      | 0.97%   |
| 0              | 1        | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 155      | 193    | 2.65%   |
| Seagate ST3500418AS 500GB         | 115      | 149    | 1.97%   |
| Seagate ST3250410AS 250GB         | 94       | 120    | 1.61%   |
| WDC WD5000AAKX-001CA0 500GB       | 71       | 90     | 1.21%   |
| Seagate ST3250310AS 250GB         | 69       | 114    | 1.18%   |
| Seagate ST3320613AS 320GB         | 63       | 85     | 1.08%   |
| Seagate ST1000DM003-1CH162 1TB    | 58       | 89     | 0.99%   |
| Seagate ST31000528AS 1TB          | 56       | 63     | 0.96%   |
| Seagate ST1000DM003-9YN162 1TB    | 55       | 65     | 0.94%   |
| Hitachi HDS721050CLA362 500GB     | 49       | 59     | 0.84%   |
| WDC WD5000AADS-00S9B0 500GB       | 46       | 53     | 0.79%   |
| Seagate ST380011A 80GB            | 45       | 48     | 0.77%   |
| Seagate ST3160815AS 160GB         | 45       | 56     | 0.77%   |
| Seagate ST250DM000-1BD141 250GB   | 45       | 60     | 0.77%   |
| Seagate ST31000524AS 1TB          | 44       | 59     | 0.75%   |
| WDC WD3200AAJS-00L7A0 320GB       | 42       | 47     | 0.72%   |
| Seagate ST3250318AS 250GB         | 41       | 53     | 0.7%    |
| WDC WD5000AAKX-60U6AA0 500GB      | 39       | 60     | 0.67%   |
| Hitachi HDS721010CLA332 1TB       | 39       | 46     | 0.67%   |
| WDC WD10EARS-00Y5B1 1TB           | 38       | 62     | 0.65%   |
| Hitachi HDS721616PLA380 164GB     | 38       | 52     | 0.65%   |
| Seagate ST3160811AS 160GB         | 36       | 52     | 0.62%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 35       | 45     | 0.6%    |
| Seagate ST380815AS 80GB           | 35       | 47     | 0.6%    |
| Seagate ST3500413AS 500GB         | 34       | 37     | 0.58%   |
| Samsung Electronics HD160JJ 160GB | 34       | 54     | 0.58%   |
| Kingston SV300S37A120G 120GB SSD  | 34       | 35     | 0.58%   |
| Samsung Electronics HD080HJ 80GB  | 32       | 42     | 0.55%   |
| Maxtor STM3250310AS 250GB         | 31       | 40     | 0.53%   |
| Seagate ST31500341AS 1TB          | 29       | 38     | 0.5%    |
| Hitachi HDP725050GLA360 500GB     | 28       | 40     | 0.48%   |
| WDC WD5000AAKS-00V1A0 500GB       | 26       | 31     | 0.44%   |
| Seagate ST3320620AS 320GB         | 26       | 34     | 0.44%   |
| Toshiba DT01ACA050 500GB          | 25       | 37     | 0.43%   |
| Samsung Electronics HD161HJ 160GB | 25       | 31     | 0.43%   |
| Toshiba DT01ACA100 1TB            | 24       | 37     | 0.41%   |
| Seagate ST3500320AS 500GB         | 23       | 27     | 0.39%   |
| Seagate ST3320418AS 320GB         | 23       | 27     | 0.39%   |
| Kingston SHFS37A120G 120GB SSD    | 23       | 29     | 0.39%   |
| Hitachi HDS721050CLA360 500GB     | 23       | 28     | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1997     | 2869   | 36.63%  |
| WDC                 | 1629     | 2306   | 29.88%  |
| Hitachi             | 493      | 661    | 9.04%   |
| Samsung Electronics | 415      | 583    | 7.61%   |
| Toshiba             | 190      | 253    | 3.48%   |
| Maxtor              | 169      | 203    | 3.1%    |
| Kingston            | 103      | 116    | 1.89%   |
| OCZ                 | 54       | 72     | 0.99%   |
| SPCC                | 38       | 45     | 0.7%    |
| HGST                | 36       | 43     | 0.66%   |
| A-DATA Technology   | 35       | 50     | 0.64%   |
| Intel               | 32       | 46     | 0.59%   |
| Corsair             | 30       | 45     | 0.55%   |
| Kingmax             | 24       | 46     | 0.44%   |
| KingSpec            | 15       | 17     | 0.28%   |
| China               | 15       | 18     | 0.28%   |
| AMD                 | 15       | 18     | 0.28%   |
| SanDisk             | 14       | 19     | 0.26%   |
| Plextor             | 14       | 26     | 0.26%   |
| Netac               | 11       | 11     | 0.2%    |
| IBM/Hitachi         | 11       | 14     | 0.2%    |
| Fujitsu             | 10       | 13     | 0.18%   |
| Crucial             | 10       | 20     | 0.18%   |
| Neo                 | 8        | 16     | 0.15%   |
| OCZ-VERTEX3         | 6        | 11     | 0.11%   |
| Apacer              | 5        | 5      | 0.09%   |
| Unknown             | 5        | 6      | 0.09%   |
| KingDian            | 4        | 5      | 0.07%   |
| XPG                 | 3        | 7      | 0.06%   |
| Silicon Motion      | 3        | 4      | 0.06%   |
| Qumo                | 3        | 7      | 0.06%   |
| PNY                 | 3        | 3      | 0.06%   |
| LITEONIT            | 3        | 3      | 0.06%   |
| IBM                 | 3        | 3      | 0.06%   |
| Hewlett-Packard     | 3        | 4      | 0.06%   |
| XrayDisk            | 2        | 4      | 0.04%   |
| Verbatim            | 2        | 2      | 0.04%   |
| Smartbuy            | 2        | 3      | 0.04%   |
| Quantum             | 2        | 2      | 0.04%   |
| Patriot             | 2        | 2      | 0.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1996     | 2866   | 40.83%  |
| WDC                 | 1593     | 2244   | 32.59%  |
| Hitachi             | 493      | 661    | 10.09%  |
| Samsung Electronics | 380      | 540    | 7.77%   |
| Toshiba             | 187      | 250    | 3.83%   |
| Maxtor              | 169      | 203    | 3.46%   |
| HGST                | 36       | 43     | 0.74%   |
| IBM/Hitachi         | 11       | 14     | 0.23%   |
| Fujitsu             | 10       | 13     | 0.2%    |
| IBM                 | 3        | 3      | 0.06%   |
| Hewlett-Packard     | 3        | 4      | 0.06%   |
| Quantum             | 2        | 2      | 0.04%   |
| WD MediaMax         | 1        | 1      | 0.02%   |
| MARSHAL             | 1        | 1      | 0.02%   |
| ExcelStor           | 1        | 1      | 0.02%   |
| ASMT                | 1        | 2      | 0.02%   |
| Unknown             | 1        | 1      | 0.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4291     | 6849   | 88.44%  |
| SSD  | 528      | 722    | 10.88%  |
| NVMe | 33       | 52     | 0.68%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST31000528AS 1TB          | 8        | 10     | 4.23%   |
| Seagate ST31000524AS 1TB          | 7        | 9      | 3.7%    |
| Hitachi HDS721010DLE630 1TB       | 6        | 7      | 3.17%   |
| Seagate ST3500418AS 500GB         | 5        | 6      | 2.65%   |
| Seagate ST3500412AS 500GB         | 5        | 6      | 2.65%   |
| Seagate ST3320613AS 320GB         | 4        | 5      | 2.12%   |
| Seagate ST31000333AS 1TB          | 3        | 3      | 1.59%   |
| Samsung Electronics SP0411N 40GB  | 3        | 4      | 1.59%   |
| Maxtor 6Y080L0 82GB               | 3        | 3      | 1.59%   |
| Hitachi HDS721010CLA332 1TB       | 3        | 3      | 1.59%   |
| HGST HTS545050A7E380 500GB        | 3        | 3      | 1.59%   |
| WDC WD5000AAKS-00V1A0 500GB       | 2        | 2      | 1.06%   |
| WDC WD3200AAJS-00L7A0 320GB       | 2        | 2      | 1.06%   |
| WDC WD20EARS-00MVWB0 2TB          | 2        | 2      | 1.06%   |
| WDC WD15EARS-00MVWB0 1TB          | 2        | 4      | 1.06%   |
| Seagate STM3500418AS 500GB        | 2        | 2      | 1.06%   |
| Seagate ST500DM005 HD502HJ 500GB  | 2        | 3      | 1.06%   |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 1.06%   |
| Seagate ST500DM002-1BC142 500GB   | 2        | 2      | 1.06%   |
| Seagate ST3750528AS 752GB         | 2        | 2      | 1.06%   |
| Seagate ST3250318AS 250GB         | 2        | 2      | 1.06%   |
| Seagate ST32000542AS 2TB          | 2        | 4      | 1.06%   |
| Seagate ST3160318AS 160GB         | 2        | 2      | 1.06%   |
| Seagate ST250DM000-1BD141 250GB   | 2        | 2      | 1.06%   |
| Samsung Electronics HD503HI 500GB | 2        | 2      | 1.06%   |
| Samsung Electronics HD204UI 2TB   | 2        | 2      | 1.06%   |
| Samsung Electronics HD105SI 1TB   | 2        | 2      | 1.06%   |
| Hitachi HDT721032SLA380 320GB     | 2        | 2      | 1.06%   |
| Hitachi HDS721050DLE630 500GB     | 2        | 2      | 1.06%   |
| Hitachi HDS721025CLA382 250GB     | 2        | 2      | 1.06%   |
| WDC WD800JD-22LSA0 80GB           | 1        | 1      | 0.53%   |
| WDC WD800JB-00JJC0 80GB           | 1        | 1      | 0.53%   |
| WDC WD800JB-00FMA0 80GB           | 1        | 1      | 0.53%   |
| WDC WD800BB-55JKC0 80GB           | 1        | 2      | 0.53%   |
| WDC WD800BB-22JHA0 80GB           | 1        | 1      | 0.53%   |
| WDC WD800BB-00JKC0 80GB           | 1        | 2      | 0.53%   |
| WDC WD800BB-00JHC0 80GB           | 1        | 1      | 0.53%   |
| WDC WD7501AALS-00J7B0 752GB       | 1        | 2      | 0.53%   |
| WDC WD6400AACS-00G8B0 640GB       | 1        | 1      | 0.53%   |
| WDC WD5001AALS-00E3A0 500GB       | 1        | 1      | 0.53%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 70       | 82     | 37.43%  |
| WDC                 | 48       | 64     | 25.67%  |
| Samsung Electronics | 22       | 24     | 11.76%  |
| Hitachi             | 18       | 19     | 9.63%   |
| Toshiba             | 7        | 7      | 3.74%   |
| Maxtor              | 7        | 7      | 3.74%   |
| HGST                | 6        | 7      | 3.21%   |
| Intel               | 2        | 5      | 1.07%   |
| Transcend           | 1        | 1      | 0.53%   |
| OCZ                 | 1        | 1      | 0.53%   |
| Hewlett-Packard     | 1        | 1      | 0.53%   |
| GOODRAM             | 1        | 1      | 0.53%   |
| Crucial             | 1        | 1      | 0.53%   |
| Corsair             | 1        | 1      | 0.53%   |
| A-DATA Technology   | 1        | 1      | 0.53%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 8922     | 20154  | 56.16%  |
| Malfunc  | 4672     | 7623   | 29.41%  |
| Detected | 2109     | 4816   | 13.28%  |
| Failed   | 183      | 222    | 1.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 8397     | 52.19%  |
| AMD                              | 3357     | 20.87%  |
| JMicron Technology               | 815      | 5.07%   |
| Nvidia                           | 792      | 4.92%   |
| Samsung Electronics              | 480      | 2.98%   |
| Marvell Technology Group         | 461      | 2.87%   |
| ASMedia Technology               | 413      | 2.57%   |
| VIA Technologies                 | 216      | 1.34%   |
| Silicon Motion                   | 195      | 1.21%   |
| Kingston Technology Company      | 166      | 1.03%   |
| Phison Electronics               | 160      | 0.99%   |
| SanDisk                          | 106      | 0.66%   |
| ADATA Technology                 | 93       | 0.58%   |
| Realtek Semiconductor            | 73       | 0.45%   |
| Silicon Integrated Systems [SiS] | 41       | 0.25%   |
| MAXIO Technology (Hangzhou)      | 39       | 0.24%   |
| Silicon Image                    | 36       | 0.22%   |
| Lite-On Technology               | 31       | 0.19%   |
| Integrated Technology Express    | 31       | 0.19%   |
| Netac Technology                 | 21       | 0.13%   |
| Micron/Crucial Technology        | 20       | 0.12%   |
| Adaptec                          | 20       | 0.12%   |
| SK hynix                         | 17       | 0.11%   |
| Broadcom / LSI                   | 13       | 0.08%   |
| LSI Logic / Symbios Logic        | 10       | 0.06%   |
| INNOGRIT                         | 7        | 0.04%   |
| Toshiba America Info Systems     | 6        | 0.04%   |
| Shenzhen Longsys Electronics     | 6        | 0.04%   |
| Micron Technology                | 6        | 0.04%   |
| KIOXIA                           | 6        | 0.04%   |
| Hewlett-Packard                  | 6        | 0.04%   |
| MCST                             | 5        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 5        | 0.03%   |
| ULi Electronics                  | 4        | 0.02%   |
| Seagate Technology               | 4        | 0.02%   |
| Promise Technology               | 4        | 0.02%   |
| Biwin Storage Technology         | 4        | 0.02%   |
| Union Memory (Shenzhen)          | 3        | 0.02%   |
| Solid State Storage Technology   | 3        | 0.02%   |
| OCZ Technology Group             | 3        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1457     | 6.48%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1363     | 6.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1102     | 4.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1097     | 4.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 782      | 3.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 757      | 3.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 652      | 2.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 646      | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 627      | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 626      | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 620      | 2.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 505      | 2.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 493      | 2.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 470      | 2.09%   |
| Nvidia MCP61 SATA Controller                                                            | 408      | 1.81%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 400      | 1.78%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 397      | 1.77%   |
| Nvidia MCP61 IDE                                                                        | 381      | 1.69%   |
| JMicron JMB368 IDE controller                                                           | 312      | 1.39%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 292      | 1.3%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 290      | 1.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 282      | 1.25%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 276      | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 258      | 1.15%   |
| AMD 500 Series Chipset SATA Controller                                                  | 227      | 1.01%   |
| AMD FCH SATA Controller D                                                               | 221      | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 217      | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 201      | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 201      | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 194      | 0.86%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 193      | 0.86%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 180      | 0.8%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 174      | 0.77%   |
| AMD 300 Series Chipset SATA Controller                                                  | 156      | 0.69%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 150      | 0.67%   |
| AMD FCH IDE Controller                                                                  | 149      | 0.66%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 139      | 0.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 131      | 0.58%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 127      | 0.56%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 124      | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 8300     | 51.52%  |
| IDE  | 6066     | 37.65%  |
| NVMe | 1384     | 8.59%   |
| RAID | 322      | 2%      |
| SAS  | 30       | 0.19%   |
| SCSI | 8        | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 8538     | 67.33%  |
| AMD          | 4132     | 32.58%  |
| CentaurHauls | 2        | 0.02%   |
| Unknown      | 2        | 0.02%   |
| PowerMac7,2  | 1        | 0.01%   |
| MBE8C-PC     | 1        | 0.01%   |
| Loongson     | 1        | 0.01%   |
| Elbrus-MCST  | 1        | 0.01%   |
| E8C/EATX     | 1        | 0.01%   |
| E8C-SWTX     | 1        | 0.01%   |
| E8C-mITX     | 1        | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 171      | 1.33%   |
| AMD Ryzen 5 3600 6-Core Processor           | 127      | 0.99%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 124      | 0.97%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 117      | 0.91%   |
| Intel Pentium 4 CPU 3.00GHz                 | 113      | 0.88%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 112      | 0.87%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 111      | 0.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 110      | 0.86%   |
| AMD FX-6300 Six-Core Processor              | 110      | 0.86%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 103      | 0.8%    |
| AMD Athlon II X2 250 Processor              | 98       | 0.76%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 95       | 0.74%   |
| AMD FX-8350 Eight-Core Processor            | 94       | 0.73%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 89       | 0.69%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 87       | 0.68%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 86       | 0.67%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 85       | 0.66%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 83       | 0.65%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 80       | 0.62%   |
| AMD FX-4300 Quad-Core Processor             | 78       | 0.61%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 76       | 0.59%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 76       | 0.59%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 75       | 0.58%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 70       | 0.55%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 70       | 0.55%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 69       | 0.54%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 67       | 0.52%   |
| AMD FX-8320 Eight-Core Processor            | 67       | 0.52%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 65       | 0.51%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 63       | 0.49%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 62       | 0.48%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 62       | 0.48%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 61       | 0.48%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 61       | 0.48%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 61       | 0.48%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 61       | 0.48%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 61       | 0.48%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 60       | 0.47%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 59       | 0.46%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 59       | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1757     | 13.73%  |
| Intel Core i3           | 1333     | 10.42%  |
| Intel Core 2 Duo        | 778      | 6.08%   |
| Intel Celeron           | 745      | 5.82%   |
| Intel Pentium           | 723      | 5.65%   |
| Intel Core i7           | 706      | 5.52%   |
| AMD FX                  | 646      | 5.05%   |
| AMD Ryzen 5             | 642      | 5.02%   |
| Intel Xeon              | 618      | 4.83%   |
| AMD Athlon 64 X2        | 413      | 3.23%   |
| Intel Pentium Dual-Core | 403      | 3.15%   |
| Intel Core 2 Quad       | 362      | 2.83%   |
| AMD Athlon II X2        | 336      | 2.63%   |
| Intel Pentium 4         | 261      | 2.04%   |
| AMD Ryzen 7             | 258      | 2.02%   |
| Other                   | 223      | 1.74%   |
| AMD Phenom II X4        | 214      | 1.67%   |
| AMD Ryzen 3             | 190      | 1.49%   |
| AMD Athlon II X4        | 155      | 1.21%   |
| Intel Pentium Dual      | 146      | 1.14%   |
| Intel Core 2            | 140      | 1.09%   |
| Intel Atom              | 122      | 0.95%   |
| AMD Athlon II X3        | 121      | 0.95%   |
| AMD A8                  | 112      | 0.88%   |
| Intel Pentium D         | 109      | 0.85%   |
| AMD A10                 | 107      | 0.84%   |
| AMD Phenom              | 102      | 0.8%    |
| AMD A4                  | 98       | 0.77%   |
| AMD Athlon 64           | 93       | 0.73%   |
| AMD Phenom II X6        | 86       | 0.67%   |
| Intel Pentium Gold      | 84       | 0.66%   |
| AMD Ryzen 9             | 84       | 0.66%   |
| AMD Athlon              | 83       | 0.65%   |
| AMD A6                  | 78       | 0.61%   |
| AMD Athlon X4           | 75       | 0.59%   |
| AMD Sempron             | 44       | 0.34%   |
| Intel Core i9           | 39       | 0.3%    |
| Intel Genuine           | 38       | 0.3%    |
| AMD Phenom II X2        | 33       | 0.26%   |
| AMD Ryzen 5 PRO         | 29       | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 5170     | 39.73%  |
| 4       | 3934     | 30.23%  |
| 6       | 1298     | 9.97%   |
| Unknown | 794      | 6.1%    |
| 1       | 658      | 5.06%   |
| 8       | 547      | 4.2%    |
| 3       | 324      | 2.49%   |
| 12      | 119      | 0.91%   |
| 16      | 59       | 0.45%   |
| 10      | 58       | 0.45%   |
| 24      | 23       | 0.18%   |
| 14      | 9        | 0.07%   |
| 18      | 7        | 0.05%   |
| 28      | 4        | 0.03%   |
| 20      | 4        | 0.03%   |
| 32      | 2        | 0.02%   |
| 36      | 1        | 0.01%   |
| 22      | 1        | 0.01%   |
| 15      | 1        | 0.01%   |
| 5       | 1        | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 12585    | 99.21%  |
| 2       | 91       | 0.72%   |
| Unknown | 7        | 0.06%   |
| 4       | 1        | 0.01%   |
| 0       | 1        | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 7120     | 54.87%  |
| 2       | 5057     | 38.97%  |
| Unknown | 794      | 6.12%   |
| 8       | 2        | 0.02%   |
| 6       | 2        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 12429    | 97.92%  |
| 32-bit         | 188      | 1.48%   |
| Unknown        | 71       | 0.56%   |
| 64-bit         | 5        | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1506     | 11.51%  |
| 0x1067a    | 1064     | 8.13%   |
| 0x206a7    | 960      | 7.34%   |
| 0x306c3    | 872      | 6.66%   |
| 0x306a9    | 870      | 6.65%   |
| 0x010000c8 | 510      | 3.9%    |
| 0x506e3    | 437      | 3.34%   |
| 0x906e9    | 325      | 2.48%   |
| 0x906ea    | 312      | 2.38%   |
| 0x6fd      | 283      | 2.16%   |
| 0x10676    | 272      | 2.08%   |
| 0x6fb      | 236      | 1.8%    |
| 0x06000852 | 234      | 1.79%   |
| 0x06001119 | 228      | 1.74%   |
| 0xa0653    | 221      | 1.69%   |
| 0x08701021 | 187      | 1.43%   |
| 0x0800820d | 186      | 1.42%   |
| 0x0600084f | 171      | 1.31%   |
| 0x010000db | 146      | 1.12%   |
| 0x106e5    | 129      | 0.99%   |
| 0x08108109 | 114      | 0.87%   |
| 0x20655    | 112      | 0.86%   |
| 0x06003106 | 105      | 0.8%    |
| 0x906eb    | 100      | 0.76%   |
| 0x306f2    | 100      | 0.76%   |
| 0x08001138 | 99       | 0.76%   |
| 0x206d7    | 93       | 0.71%   |
| 0x08101016 | 92       | 0.7%    |
| 0xf49      | 86       | 0.66%   |
| 0x6f6      | 83       | 0.63%   |
| 0x6f2      | 82       | 0.63%   |
| 0xa0671    | 77       | 0.59%   |
| 0x010000c7 | 76       | 0.58%   |
| 0xf41      | 74       | 0.57%   |
| 0x20652    | 74       | 0.57%   |
| 0x03000027 | 72       | 0.55%   |
| 0x010000dc | 72       | 0.55%   |
| 0x906ed    | 71       | 0.54%   |
| 0x0600063d | 69       | 0.53%   |
| 0x0600063e | 65       | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 1379     | 10.77%  |
| SandyBridge      | 1106     | 8.64%   |
| K10              | 1073     | 8.38%   |
| Haswell          | 1044     | 8.16%   |
| IvyBridge        | 1001     | 7.82%   |
| KabyLake         | 925      | 7.23%   |
| Core             | 817      | 6.38%   |
| Piledriver       | 737      | 5.76%   |
| K8 Hammer        | 521      | 4.07%   |
| Skylake          | 493      | 3.85%   |
| NetBurst         | 484      | 3.78%   |
| Zen+             | 357      | 2.79%   |
| Zen              | 355      | 2.77%   |
| Zen 2            | 342      | 2.67%   |
| CometLake        | 338      | 2.64%   |
| Zen 3            | 226      | 1.77%   |
| Westmere         | 222      | 1.73%   |
| Unknown          | 212      | 1.66%   |
| Nehalem          | 187      | 1.46%   |
| Bulldozer        | 147      | 1.15%   |
| Steamroller      | 116      | 0.91%   |
| Silvermont       | 110      | 0.86%   |
| Bonnell          | 99       | 0.77%   |
| K10 Llano        | 78       | 0.61%   |
| Alderlake Hybrid | 78       | 0.61%   |
| Excavator        | 61       | 0.48%   |
| Goldmont plus    | 57       | 0.45%   |
| Icelake          | 55       | 0.43%   |
| Broadwell        | 42       | 0.33%   |
| Goldmont         | 31       | 0.24%   |
| Bobcat           | 26       | 0.2%    |
| Jaguar           | 25       | 0.2%    |
| Tremont          | 22       | 0.17%   |
| K6               | 11       | 0.09%   |
| TigerLake        | 8        | 0.06%   |
| Puma             | 7        | 0.05%   |
| P6               | 5        | 0.04%   |
| K8 & K10 hybrid  | 1        | 0.01%   |
| Gracemont        | 1        | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 6281     | 46.7%   |
| AMD                                          | 3608     | 26.82%  |
| Intel                                        | 3467     | 25.78%  |
| ASPEED Technology                            | 37       | 0.28%   |
| Matrox Electronics Systems                   | 22       | 0.16%   |
| VIA Technologies                             | 16       | 0.12%   |
| ATI Technologies                             | 8        | 0.06%   |
| Silicon Integrated Systems [SiS]             | 3        | 0.02%   |
| S3 Graphics                                  | 3        | 0.02%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.01%   |
| Silicon Motion                               | 2        | 0.01%   |
| Zhaoxin                                      | 1        | 0.01%   |
| Loongson Technology                          | 1        | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 401      | 2.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 401      | 2.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 333      | 2.38%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 312      | 2.23%   |
| Nvidia GK208B [GeForce GT 710]                                              | 281      | 2%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 280      | 2%      |
| Nvidia GT218 [GeForce 210]                                                  | 266      | 1.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 237      | 1.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 230      | 1.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 229      | 1.63%   |
| Nvidia GF108 [GeForce GT 630]                                               | 185      | 1.32%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 182      | 1.3%    |
| Intel HD Graphics 530                                                       | 181      | 1.29%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 176      | 1.26%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 172      | 1.23%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 159      | 1.13%   |
| Nvidia GF119 [GeForce GT 610]                                               | 153      | 1.09%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 152      | 1.08%   |
| Intel HD Graphics 630                                                       | 149      | 1.06%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 145      | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 143      | 1.02%   |
| Nvidia GK208B [GeForce GT 730]                                              | 137      | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 137      | 0.98%   |
| Nvidia GF108 [GeForce GT 430]                                               | 132      | 0.94%   |
| AMD RS780L [Radeon 3000]                                                    | 127      | 0.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 122      | 0.87%   |
| Nvidia GF108 [GeForce GT 440]                                               | 121      | 0.86%   |
| Nvidia G92 [GeForce GTS 250]                                                | 120      | 0.86%   |
| Nvidia GF108 [GeForce GT 730]                                               | 119      | 0.85%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 117      | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 114      | 0.81%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 114      | 0.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 113      | 0.81%   |
| Nvidia GT215 [GeForce GT 240]                                               | 102      | 0.73%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 102      | 0.73%   |
| Intel HD Graphics 510                                                       | 100      | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 94       | 0.67%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 94       | 0.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 94       | 0.67%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 93       | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| 1 x Nvidia                    | 5999     | 46.23%  |
| 1 x AMD                       | 3237     | 24.95%  |
| 1 x Intel                     | 3026     | 23.32%  |
| 2 x AMD                       | 275      | 2.12%   |
| Intel + Nvidia                | 182      | 1.4%    |
| AMD + Nvidia                  | 64       | 0.49%   |
| Intel + AMD                   | 45       | 0.35%   |
| 1 x ASPEED                    | 35       | 0.27%   |
| 2 x Nvidia                    | 34       | 0.26%   |
| 1 x Matrox                    | 19       | 0.15%   |
| 1 x VIA                       | 16       | 0.12%   |
| Other                         | 10       | 0.08%   |
| 3 x AMD                       | 4        | 0.03%   |
| 3 x Nvidia                    | 3        | 0.02%   |
| 2 x Intel                     | 3        | 0.02%   |
| 1 x SiS                       | 3        | 0.02%   |
| Nvidia + Matrox               | 3        | 0.02%   |
| Intel + 2 x AMD               | 3        | 0.02%   |
| 1 x XGI                       | 2        | 0.02%   |
| 1 x Silicon Motion            | 2        | 0.02%   |
| 1 x S3 Graphics               | 2        | 0.02%   |
| 3 x Nvidia + 1 x ASPEED       | 1        | 0.01%   |
| 2 x AMD + 1 x Nvidia          | 1        | 0.01%   |
| Nvidia + Zhaoxin              | 1        | 0.01%   |
| Nvidia + ASPEED               | 1        | 0.01%   |
| 1 x Loongson Technology       | 1        | 0.01%   |
| Intel + 2 x Nvidia            | 1        | 0.01%   |
| Intel + SiS + 1 x S3 Graphics | 1        | 0.01%   |
| Intel + AMD + 4 x Nvidia      | 1        | 0.01%   |
| AMD + 2 x Nvidia              | 1        | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 9267     | 69.46%  |
| Proprietary | 2580     | 19.34%  |
| Unknown     | 1494     | 11.2%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3885     | 28.88%  |
| 1.01-2.0   | 2593     | 19.28%  |
| 0.51-1.0   | 2481     | 18.44%  |
| 0.01-0.5   | 2422     | 18%     |
| 3.01-4.0   | 1019     | 7.58%   |
| 7.01-8.0   | 492      | 3.66%   |
| 5.01-6.0   | 250      | 1.86%   |
| 2.01-3.0   | 166      | 1.23%   |
| 8.01-16.0  | 126      | 0.94%   |
| 16.01-24.0 | 12       | 0.09%   |
| 4.01-5.0   | 6        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 2864     | 23.7%   |
| Goldstar             | 1671     | 13.83%  |
| Acer                 | 1308     | 10.82%  |
| BenQ                 | 1020     | 8.44%   |
| Philips              | 820      | 6.79%   |
| ViewSonic            | 584      | 4.83%   |
| AOC                  | 570      | 4.72%   |
| Dell                 | 535      | 4.43%   |
| Ancor Communications | 394      | 3.26%   |
| Hewlett-Packard      | 342      | 2.83%   |
| NEC Computers        | 262      | 2.17%   |
| Iiyama               | 161      | 1.33%   |
| Sony                 | 111      | 0.92%   |
| ASUSTek Computer     | 93       | 0.77%   |
| Unknown              | 85       | 0.7%    |
| LG Electronics       | 64       | 0.53%   |
| Envision Peripherals | 63       | 0.52%   |
| Plain Tree Systems   | 58       | 0.48%   |
| Packard Bell         | 52       | 0.43%   |
| HHT                  | 51       | 0.42%   |
| Lenovo               | 49       | 0.41%   |
| Mi                   | 38       | 0.31%   |
| ___                  | 34       | 0.28%   |
| MSI                  | 30       | 0.25%   |
| Toshiba              | 27       | 0.22%   |
| HUAWEI               | 27       | 0.22%   |
| Fujitsu Siemens      | 25       | 0.21%   |
| CHR                  | 25       | 0.21%   |
| KTC                  | 22       | 0.18%   |
| MStar                | 21       | 0.17%   |
| MiTAC                | 21       | 0.17%   |
| VIE                  | 20       | 0.17%   |
| JRY                  | 20       | 0.17%   |
| HannStar             | 19       | 0.16%   |
| RTK                  | 17       | 0.14%   |
| Unknown              | 17       | 0.14%   |
| HKC                  | 16       | 0.13%   |
| Haier                | 16       | 0.13%   |
| Panasonic            | 15       | 0.12%   |
| AGO                  | 15       | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 85       | 0.68%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 74       | 0.59%   |
| Acer AL1717 A ACRAD46 1280x1024 338x270mm 17.0-inch                  | 71       | 0.56%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch | 67       | 0.53%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 63       | 0.5%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 62       | 0.49%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 60       | 0.48%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 52       | 0.41%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 52       | 0.41%   |
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch              | 50       | 0.4%    |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                    | 48       | 0.38%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 376x301mm 19.0-inch  | 44       | 0.35%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 42       | 0.33%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                  | 41       | 0.33%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 39       | 0.31%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch          | 39       | 0.31%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 39       | 0.31%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 38       | 0.3%    |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 35       | 0.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 34       | 0.27%   |
| Acer AL1916 ACRAD49 1280x1024 376x301mm 19.0-inch                    | 33       | 0.26%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                     | 32       | 0.25%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 31       | 0.25%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 31       | 0.25%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 30       | 0.24%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 29       | 0.23%   |
| Goldstar L1942 GSM4B85 1280x1024 376x301mm 19.0-inch                 | 29       | 0.23%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch            | 29       | 0.23%   |
| AOC 2470W1M AOC2470 1920x1080 527x296mm 23.8-inch                    | 29       | 0.23%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch | 28       | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 27       | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 27       | 0.21%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 27       | 0.21%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                      | 27       | 0.21%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                | 26       | 0.21%   |
| Plain Tree Systems LCD Monitor PTS06A5 1280x1024 337x270mm 17.0-inch | 25       | 0.2%    |
| Goldstar L1952S GSM4AE0 1280x1024 376x301mm 19.0-inch                | 25       | 0.2%    |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 24       | 0.19%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch | 23       | 0.18%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 23       | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 5202     | 43.8%   |
| 1280x1024 (SXGA)   | 2332     | 19.64%  |
| 1680x1050 (WSXGA+) | 656      | 5.52%   |
| 1440x900 (WXGA+)   | 579      | 4.88%   |
| 2560x1440 (QHD)    | 492      | 4.14%   |
| 1366x768 (WXGA)    | 473      | 3.98%   |
| 3840x2160 (4K)     | 470      | 3.96%   |
| 1600x900 (HD+)     | 415      | 3.49%   |
| 1920x1200 (WUXGA)  | 226      | 1.9%    |
| 1360x768           | 201      | 1.69%   |
| 1024x768 (XGA)     | 165      | 1.39%   |
| 2560x1080          | 103      | 0.87%   |
| Unknown            | 100      | 0.84%   |
| 1600x1200          | 90       | 0.76%   |
| 3440x1440          | 65       | 0.55%   |
| 1280x720 (HD)      | 39       | 0.33%   |
| 1920x540           | 33       | 0.28%   |
| 3840x1080          | 29       | 0.24%   |
| 1400x1050          | 27       | 0.23%   |
| 2288x1287          | 22       | 0.19%   |
| 1280x960           | 14       | 0.12%   |
| 1152x864           | 14       | 0.12%   |
| 2048x1536          | 13       | 0.11%   |
| 4480x1440          | 10       | 0.08%   |
| 2560x1600          | 10       | 0.08%   |
| 2048x1152          | 9        | 0.08%   |
| 1920x1440          | 8        | 0.07%   |
| 5760x2160          | 6        | 0.05%   |
| 3200x1080          | 5        | 0.04%   |
| 2160x1200          | 5        | 0.04%   |
| 7680x2160          | 4        | 0.03%   |
| 5760x1080          | 4        | 0.03%   |
| 3840x2560          | 4        | 0.03%   |
| 3600x1080          | 4        | 0.03%   |
| 5120x1440          | 3        | 0.03%   |
| 3840x1600          | 3        | 0.03%   |
| 1280x768           | 3        | 0.03%   |
| 5120x1080          | 2        | 0.02%   |
| 4093x4093          | 2        | 0.02%   |
| 4000x1440          | 2        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 1941     | 15.98%  |
| 19      | 1654     | 13.62%  |
| 23      | 1579     | 13%     |
| 24      | 1287     | 10.59%  |
| 17      | 1143     | 9.41%   |
| 27      | 874      | 7.19%   |
| 18      | 653      | 5.38%   |
| 20      | 551      | 4.54%   |
| Unknown | 506      | 4.17%   |
| 22      | 402      | 3.31%   |
| 15      | 299      | 2.46%   |
| 31      | 204      | 1.68%   |
| 34      | 149      | 1.23%   |
| 40      | 128      | 1.05%   |
| 72      | 96       | 0.79%   |
| 54      | 94       | 0.77%   |
| 32      | 90       | 0.74%   |
| 52      | 52       | 0.43%   |
| 16      | 45       | 0.37%   |
| 25      | 41       | 0.34%   |
| 84      | 37       | 0.3%    |
| 48      | 28       | 0.23%   |
| 46      | 28       | 0.23%   |
| 28      | 23       | 0.19%   |
| 26      | 23       | 0.19%   |
| 12      | 23       | 0.19%   |
| 42      | 22       | 0.18%   |
| 142     | 20       | 0.16%   |
| 43      | 19       | 0.16%   |
| 14      | 17       | 0.14%   |
| 33      | 13       | 0.11%   |
| 29      | 13       | 0.11%   |
| 65      | 12       | 0.1%    |
| 13      | 12       | 0.1%    |
| 58      | 8        | 0.07%   |
| 39      | 8        | 0.07%   |
| 37      | 7        | 0.06%   |
| 60      | 6        | 0.05%   |
| 50      | 6        | 0.05%   |
| 99      | 5        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 4048     | 33.9%   |
| 501-600        | 3565     | 29.86%  |
| 301-350        | 1458     | 12.21%  |
| 351-400        | 1170     | 9.8%    |
| Unknown        | 506      | 4.24%   |
| 601-700        | 290      | 2.43%   |
| 701-800        | 255      | 2.14%   |
| 1001-1500      | 245      | 2.05%   |
| 1501-2000      | 138      | 1.16%   |
| 801-900        | 97       | 0.81%   |
| 901-1000       | 93       | 0.78%   |
| 201-300        | 50       | 0.42%   |
| More than 2000 | 25       | 0.21%   |
| 1-100          | 1        | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 6733     | 58.12%  |
| 5/4     | 2215     | 19.12%  |
| 16/10   | 1389     | 11.99%  |
| 4/3     | 471      | 4.07%   |
| Unknown | 387      | 3.34%   |
| 21/9    | 212      | 1.83%   |
| 3/2     | 106      | 0.92%   |
| 6/5     | 37       | 0.32%   |
| 1.00    | 20       | 0.17%   |
| 32/9    | 11       | 0.09%   |
| 2.00    | 2        | 0.02%   |
| 0.56    | 1        | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 4433     | 37.02%  |
| 151-200        | 2699     | 22.54%  |
| 141-150        | 1628     | 13.6%   |
| 301-350        | 895      | 7.47%   |
| Unknown        | 506      | 4.23%   |
| 351-500        | 471      | 3.93%   |
| More than 1000 | 369      | 3.08%   |
| 251-300        | 342      | 2.86%   |
| 501-1000       | 230      | 1.92%   |
| 101-110        | 194      | 1.62%   |
| 111-120        | 124      | 1.04%   |
| 71-80          | 25       | 0.21%   |
| 121-130        | 25       | 0.21%   |
| 131-140        | 16       | 0.13%   |
| 81-90          | 9        | 0.08%   |
| 91-100         | 5        | 0.04%   |
| 61-70          | 1        | 0.01%   |
| 51-60          | 1        | 0.01%   |
| 1-40           | 1        | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 7990     | 69.05%  |
| 101-120       | 2354     | 20.34%  |
| Unknown       | 506      | 4.37%   |
| 1-50          | 423      | 3.66%   |
| 121-160       | 196      | 1.69%   |
| 161-240       | 100      | 0.86%   |
| More than 240 | 2        | 0.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10571    | 81.49%  |
| 0     | 1257     | 9.69%   |
| 2     | 1067     | 8.23%   |
| 3     | 72       | 0.56%   |
| 4     | 5        | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 9104     | 55.67%  |
| Intel                                  | 1994     | 12.19%  |
| Qualcomm Atheros                       | 1515     | 9.26%   |
| Nvidia                                 | 683      | 4.18%   |
| Ralink Technology                      | 416      | 2.54%   |
| Huawei Technologies                    | 270      | 1.65%   |
| TP-Link                                | 243      | 1.49%   |
| Marvell Technology Group               | 232      | 1.42%   |
| Ralink                                 | 203      | 1.24%   |
| VIA Technologies                       | 188      | 1.15%   |
| D-Link System                          | 152      | 0.93%   |
| Broadcom                               | 143      | 0.87%   |
| D-Link                                 | 132      | 0.81%   |
| ASUSTek Computer                       | 108      | 0.66%   |
| Qualcomm Atheros Communications        | 100      | 0.61%   |
| MediaTek                               | 96       | 0.59%   |
| Xiaomi                                 | 74       | 0.45%   |
| Broadcom Limited                       | 73       | 0.45%   |
| ZTE WCDMA Technologies MSM             | 71       | 0.43%   |
| Samsung Electronics                    | 48       | 0.29%   |
| Sundance Technology Inc / IC Plus      | 37       | 0.23%   |
| 3Com                                   | 32       | 0.2%    |
| Silicon Integrated Systems [SiS]       | 31       | 0.19%   |
| Microsoft                              | 28       | 0.17%   |
| NetGear                                | 21       | 0.13%   |
| Mercucys                               | 20       | 0.12%   |
| IMC Networks                           | 16       | 0.1%    |
| ZyXEL Communications                   | 15       | 0.09%   |
| HTC (High Tech Computer)               | 15       | 0.09%   |
| Gemtek                                 | 15       | 0.09%   |
| ASIX Electronics                       | 15       | 0.09%   |
| Aquantia                               | 15       | 0.09%   |
| Qualcomm                               | 14       | 0.09%   |
| OPPO Electronics                       | 13       | 0.08%   |
| Spreadtrum Communications              | 12       | 0.07%   |
| Sony Ericsson Mobile Communications AB | 10       | 0.06%   |
| LSI                                    | 10       | 0.06%   |
| Tenda                                  | 9        | 0.06%   |
| T & A Mobile Phones                    | 9        | 0.06%   |
| Vimtron Electronics                    | 8        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7657     | 43.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 492      | 2.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 421      | 2.4%    |
| Nvidia MCP61 Ethernet                                             | 363      | 2.07%   |
| Ralink MT7601U Wireless Adapter                                   | 263      | 1.5%    |
| Intel Ethernet Connection (2) I219-V                              | 243      | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 217      | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 216      | 1.23%   |
| Intel I211 Gigabit Network Connection                             | 208      | 1.19%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 187      | 1.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 176      | 1%      |
| Intel 82579V Gigabit Network Connection                           | 165      | 0.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 155      | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 141      | 0.8%    |
| Huawei Modem/Networkcard                                          | 135      | 0.77%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 130      | 0.74%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 122      | 0.7%    |
| Intel Wi-Fi 6 AX200                                               | 110      | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 109      | 0.62%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 109      | 0.62%   |
| Intel Ethernet Connection (14) I219-V                             | 100      | 0.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 99       | 0.56%   |
| Intel Ethernet Controller I225-V                                  | 91       | 0.52%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 86       | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                   | 81       | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 79       | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 79       | 0.45%   |
| Intel Ethernet Connection (7) I219-V                              | 79       | 0.45%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 78       | 0.44%   |
| Realtek 802.11ac NIC                                              | 74       | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 74       | 0.42%   |
| Nvidia MCP77 Ethernet                                             | 70       | 0.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 70       | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 69       | 0.39%   |
| Nvidia CK804 Ethernet Controller                                  | 69       | 0.39%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 68       | 0.39%   |
| Intel 82574L Gigabit Network Connection                           | 68       | 0.39%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 67       | 0.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 65       | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 64       | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 824      | 24.98%  |
| Intel                                 | 520      | 15.77%  |
| Ralink Technology                     | 416      | 12.61%  |
| Qualcomm Atheros                      | 412      | 12.49%  |
| TP-Link                               | 238      | 7.22%   |
| Ralink                                | 203      | 6.16%   |
| D-Link                                | 128      | 3.88%   |
| ASUSTek Computer                      | 102      | 3.09%   |
| Qualcomm Atheros Communications       | 100      | 3.03%   |
| Broadcom                              | 81       | 2.46%   |
| D-Link System                         | 63       | 1.91%   |
| MediaTek                              | 49       | 1.49%   |
| Microsoft                             | 28       | 0.85%   |
| NetGear                               | 20       | 0.61%   |
| Mercucys                              | 20       | 0.61%   |
| IMC Networks                          | 16       | 0.49%   |
| Broadcom Limited                      | 14       | 0.42%   |
| ZyXEL Communications                  | 13       | 0.39%   |
| Tenda                                 | 9        | 0.27%   |
| Xiaomi                                | 8        | 0.24%   |
| ZyDAS                                 | 3        | 0.09%   |
| VIA Technologies                      | 3        | 0.09%   |
| Texas Instruments                     | 3        | 0.09%   |
| Micro Star International              | 3        | 0.09%   |
| Marvell Technology Group              | 3        | 0.09%   |
| Edimax Technology                     | 3        | 0.09%   |
| TRENDnet                              | 2        | 0.06%   |
| Linksys                               | 2        | 0.06%   |
| Z-Com                                 | 1        | 0.03%   |
| Wilocity                              | 1        | 0.03%   |
| Sierra Wireless                       | 1        | 0.03%   |
| Gemtek                                | 1        | 0.03%   |
| Chu Yuen Enterprise                   | 1        | 0.03%   |
| BUFFALO                               | 1        | 0.03%   |
| Belkin Components                     | 1        | 0.03%   |
| ASUSTek Computer (wrong ID)           | 1        | 0.03%   |
| AirTies Wireless Networks             | 1        | 0.03%   |
| Accton Technology                     | 1        | 0.03%   |
| AboCom Systems                        | 1        | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                    | 263      | 7.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 176      | 5.28%   |
| Intel Wi-Fi 6 AX200                                                | 110      | 3.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 109      | 3.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                             | 99       | 2.97%   |
| Qualcomm Atheros AR9271 802.11n                                    | 81       | 2.43%   |
| Realtek 802.11ac NIC                                               | 74       | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 70       | 2.1%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                   | 68       | 2.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 64       | 1.92%   |
| Ralink RT5370 Wireless Adapter                                     | 63       | 1.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 55       | 1.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 52       | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 52       | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 50       | 1.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                              | 49       | 1.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 47       | 1.41%   |
| Intel Wireless 3165                                                | 47       | 1.41%   |
| Intel Wireless-AC 9260                                             | 42       | 1.26%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                               | 41       | 1.23%   |
| Ralink RT2561/RT61 rev B 802.11g                                   | 40       | 1.2%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                         | 39       | 1.17%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter         | 37       | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)     | 36       | 1.08%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 33       | 0.99%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                               | 33       | 0.99%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                   | 33       | 0.99%   |
| Intel Wireless 7265                                                | 33       | 0.99%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 32       | 0.96%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                | 32       | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 31       | 0.93%   |
| D-Link 802.11 n WLAN                                               | 28       | 0.84%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]          | 28       | 0.84%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                    | 27       | 0.81%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter       | 27       | 0.81%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                | 26       | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 25       | 0.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                          | 24       | 0.72%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                            | 22       | 0.66%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 20       | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 8843     | 64.88%  |
| Intel                                  | 1696     | 12.44%  |
| Qualcomm Atheros                       | 1145     | 8.4%    |
| Nvidia                                 | 683      | 5.01%   |
| Marvell Technology Group               | 229      | 1.68%   |
| VIA Technologies                       | 183      | 1.34%   |
| D-Link System                          | 90       | 0.66%   |
| Huawei Technologies                    | 89       | 0.65%   |
| ZTE WCDMA Technologies MSM             | 66       | 0.48%   |
| Xiaomi                                 | 66       | 0.48%   |
| Broadcom                               | 62       | 0.45%   |
| Broadcom Limited                       | 59       | 0.43%   |
| Samsung Electronics                    | 48       | 0.35%   |
| MediaTek                               | 46       | 0.34%   |
| Sundance Technology Inc / IC Plus      | 37       | 0.27%   |
| 3Com                                   | 32       | 0.23%   |
| Silicon Integrated Systems [SiS]       | 31       | 0.23%   |
| HTC (High Tech Computer)               | 15       | 0.11%   |
| ASIX Electronics                       | 15       | 0.11%   |
| Aquantia                               | 15       | 0.11%   |
| Qualcomm                               | 14       | 0.1%    |
| Gemtek                                 | 14       | 0.1%    |
| OPPO Electronics                       | 13       | 0.1%    |
| Spreadtrum Communications              | 12       | 0.09%   |
| Sony Ericsson Mobile Communications AB | 10       | 0.07%   |
| T & A Mobile Phones                    | 9        | 0.07%   |
| Vimtron Electronics                    | 8        | 0.06%   |
| GCT Semiconductor                      | 8        | 0.06%   |
| JMicron Technology                     | 7        | 0.05%   |
| TP-Link                                | 6        | 0.04%   |
| HMD Global                             | 6        | 0.04%   |
| ASUSTek Computer                       | 6        | 0.04%   |
| MCST                                   | 5        | 0.04%   |
| Lenovo                                 | 5        | 0.04%   |
| ULi Electronics                        | 4        | 0.03%   |
| Mellanox Technologies                  | 4        | 0.03%   |
| D-Link                                 | 4        | 0.03%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.02%   |
| ICS Advent                             | 3        | 0.02%   |
| Davicom Semiconductor                  | 3        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7657     | 54.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 492      | 3.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 421      | 3.02%   |
| Nvidia MCP61 Ethernet                                             | 363      | 2.6%    |
| Intel Ethernet Connection (2) I219-V                              | 243      | 1.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 217      | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 216      | 1.55%   |
| Intel I211 Gigabit Network Connection                             | 208      | 1.49%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 187      | 1.34%   |
| Intel 82579V Gigabit Network Connection                           | 165      | 1.18%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 155      | 1.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 141      | 1.01%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 130      | 0.93%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 122      | 0.87%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 109      | 0.78%   |
| Intel Ethernet Connection (14) I219-V                             | 100      | 0.72%   |
| Intel Ethernet Controller I225-V                                  | 91       | 0.65%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 86       | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 79       | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 79       | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 79       | 0.57%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 78       | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 74       | 0.53%   |
| Nvidia MCP77 Ethernet                                             | 70       | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 69       | 0.49%   |
| Nvidia CK804 Ethernet Controller                                  | 69       | 0.49%   |
| Intel 82574L Gigabit Network Connection                           | 68       | 0.49%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 67       | 0.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 65       | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 64       | 0.46%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 58       | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 57       | 0.41%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 53       | 0.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 52       | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 51       | 0.37%   |
| Nvidia MCP55 Ethernet                                             | 51       | 0.37%   |
| Huawei ALP-AL00                                                   | 49       | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 44       | 0.32%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 42       | 0.3%    |
| Intel I210 Gigabit Network Connection                             | 41       | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12555    | 78.74%  |
| WiFi     | 3127     | 19.61%  |
| Modem    | 243      | 1.52%   |
| Unknown  | 20       | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10637    | 84.3%   |
| WiFi     | 1980     | 15.69%  |
| Modem    | 1        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10179    | 79.7%   |
| 2     | 2250     | 17.62%  |
| 3     | 183      | 1.43%   |
| 0     | 107      | 0.84%   |
| 4     | 41       | 0.32%   |
| 6     | 3        | 0.02%   |
| 5     | 3        | 0.02%   |
| 8     | 2        | 0.02%   |
| 33    | 1        | 0.01%   |
| 13    | 1        | 0.01%   |
| 7     | 1        | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12507    | 98.3%   |
| Yes  | 216      | 1.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 775      | 40.75%  |
| Intel                           | 473      | 24.87%  |
| ASUSTek Computer                | 156      | 8.2%    |
| Realtek Semiconductor           | 154      | 8.1%    |
| Broadcom                        | 92       | 4.84%   |
| Qualcomm Atheros Communications | 52       | 2.73%   |
| MediaTek                        | 39       | 2.05%   |
| Integrated System Solution      | 28       | 1.47%   |
| TP-Link                         | 23       | 1.21%   |
| IMC Networks                    | 22       | 1.16%   |
| Lite-On Technology              | 12       | 0.63%   |
| Apple                           | 11       | 0.58%   |
| ISSC                            | 9        | 0.47%   |
| Conwise Technology              | 9        | 0.47%   |
| Ralink                          | 6        | 0.32%   |
| Foxconn / Hon Hai               | 6        | 0.32%   |
| Roper                           | 5        | 0.26%   |
| HTC (High Tech Computer)        | 5        | 0.26%   |
| Actions                         | 5        | 0.26%   |
| Logitech                        | 4        | 0.21%   |
| D-Link System                   | 4        | 0.21%   |
| Realtek                         | 3        | 0.16%   |
| Hewlett-Packard                 | 3        | 0.16%   |
| Micro Star International        | 2        | 0.11%   |
| Edimax Technology               | 2        | 0.11%   |
| TRENDnet                        | 1        | 0.05%   |
| Toshiba                         | 1        | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 775      | 40.66%  |
| Realtek Bluetooth Radio                                              | 141      | 7.4%    |
| Intel Bluetooth wireless interface                                   | 126      | 6.61%   |
| Intel AX200 Bluetooth                                                | 107      | 5.61%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 68       | 3.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 65       | 3.41%   |
| Intel AX210 Bluetooth                                                | 50       | 2.62%   |
| MediaTek Wireless_Device                                             | 39       | 2.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 37       | 1.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 35       | 1.84%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 31       | 1.63%   |
| Intel AX201 Bluetooth                                                | 25       | 1.31%   |
| TP-Link UB500 Adapter                                                | 23       | 1.21%   |
| ASUS Bluetooth Adapter                                               | 23       | 1.21%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 21       | 1.1%    |
| Broadcom BCM2045 Bluetooth                                           | 20       | 1.05%   |
| ASUS BCM20702A0                                                      | 19       | 1%      |
| Broadcom Bluetooth 3.0 USB Dongle                                    | 17       | 0.89%   |
| Intel Bluetooth Device                                               | 16       | 0.84%   |
| Integrated System Solution Bluetooth Device                          | 16       | 0.84%   |
| ASUS ASUS USB-BT500                                                  | 16       | 0.84%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 12       | 0.63%   |
| ASUS Bluetooth Radio                                                 | 12       | 0.63%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 11       | 0.58%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 10       | 0.52%   |
| Lite-On Bluetooth Device                                             | 10       | 0.52%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 10       | 0.52%   |
| ISSC Bluetooth Device                                                | 9        | 0.47%   |
| Conwise CW6622                                                       | 9        | 0.47%   |
| Qualcomm Atheros  Bluetooth Device                                   | 7        | 0.37%   |
| Apple Bluetooth Host Controller                                      | 7        | 0.37%   |
| Ralink RT3290 Bluetooth                                              | 6        | 0.31%   |
| IMC Networks Bluetooth Radio                                         | 6        | 0.31%   |
| ASUS Bluetooth Device                                                | 6        | 0.31%   |
| Roper Class 1 Bluetooth Dongle                                       | 5        | 0.26%   |
| Qualcomm Atheros Bluetooth (AR3011)                                  | 5        | 0.26%   |
| IMC Networks Wireless_Device                                         | 5        | 0.26%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 5        | 0.26%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 5        | 0.26%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle                   | 5        | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 8097     | 39.94%  |
| Nvidia                               | 5459     | 26.93%  |
| AMD                                  | 4738     | 23.37%  |
| C-Media Electronics                  | 526      | 2.59%   |
| Creative Labs                        | 325      | 1.6%    |
| VIA Technologies                     | 122      | 0.6%    |
| Creative Technology                  | 88       | 0.43%   |
| JMTek                                | 81       | 0.4%    |
| Logitech                             | 79       | 0.39%   |
| Texas Instruments                    | 55       | 0.27%   |
| Generalplus Technology               | 55       | 0.27%   |
| Silicon Integrated Systems [SiS]     | 39       | 0.19%   |
| ASUSTek Computer                     | 31       | 0.15%   |
| Kingston Technology                  | 26       | 0.13%   |
| Plantronics                          | 20       | 0.1%    |
| Razer USA                            | 19       | 0.09%   |
| Micro Star International             | 19       | 0.09%   |
| Sony                                 | 17       | 0.08%   |
| KTMicro                              | 17       | 0.08%   |
| Yamaha                               | 15       | 0.07%   |
| A4Tech                               | 13       | 0.06%   |
| GN Netcom                            | 12       | 0.06%   |
| Focusrite-Novation                   | 12       | 0.06%   |
| SteelSeries ApS                      | 11       | 0.05%   |
| Samson Technologies                  | 11       | 0.05%   |
| Pixart Imaging                       | 11       | 0.05%   |
| M-Audio                              | 10       | 0.05%   |
| Ensoniq                              | 10       | 0.05%   |
| XMOS                                 | 9        | 0.04%   |
| BEHRINGER International              | 9        | 0.04%   |
| FIFINE Microphones                   | 8        | 0.04%   |
| Conexant Systems                     | 8        | 0.04%   |
| ATI Technologies                     | 8        | 0.04%   |
| Realtek Semiconductor                | 7        | 0.03%   |
| Microsoft                            | 7        | 0.03%   |
| ESS Technology                       | 7        | 0.03%   |
| Thesycon Systemsoftware & Consulting | 6        | 0.03%   |
| Tenx Technology                      | 6        | 0.03%   |
| Shenzhen Rapoo Technology            | 6        | 0.03%   |
| Nordic Semiconductor ASA             | 6        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1467     | 6.43%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1457     | 6.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1208     | 5.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 795      | 3.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 713      | 3.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 633      | 2.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 590      | 2.59%   |
| Intel 200 Series PCH HD Audio                                              | 486      | 2.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 470      | 2.06%   |
| AMD Family 17h/19h HD Audio Controller                                     | 469      | 2.06%   |
| AMD FCH Azalia Controller                                                  | 460      | 2.02%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 457      | 2%      |
| Nvidia High Definition Audio Controller                                    | 453      | 1.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 453      | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 413      | 1.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 411      | 1.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 398      | 1.74%   |
| Nvidia MCP61 High Definition Audio                                         | 394      | 1.73%   |
| AMD Starship/Matisse HD Audio Controller                                   | 388      | 1.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 329      | 1.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 327      | 1.43%   |
| Nvidia GK107 HDMI Audio Controller                                         | 318      | 1.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 307      | 1.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 255      | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                              | 242      | 1.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 236      | 1.03%   |
| Nvidia GK106 HDMI Audio Controller                                         | 233      | 1.02%   |
| Nvidia GF119 HDMI Audio Controller                                         | 227      | 1%      |
| Intel Cannon Lake PCH cAVS                                                 | 227      | 1%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 216      | 0.95%   |
| Nvidia GF116 High Definition Audio Controller                              | 211      | 0.92%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 178      | 0.78%   |
| Nvidia GK104 HDMI Audio Controller                                         | 172      | 0.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 150      | 0.66%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 148      | 0.65%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 147      | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 145      | 0.64%   |
| Nvidia GP108 High Definition Audio Controller                              | 145      | 0.64%   |
| Nvidia GP104 High Definition Audio Controller                              | 145      | 0.64%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 139      | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 4796     | 38.68%  |
| Kingston                     | 2397     | 19.33%  |
| Crucial                      | 998      | 8.05%   |
| Samsung Electronics          | 805      | 6.49%   |
| SK hynix                     | 512      | 4.13%   |
| Corsair                      | 489      | 3.94%   |
| AMD                          | 345      | 2.78%   |
| Patriot                      | 341      | 2.75%   |
| Micron Technology            | 196      | 1.58%   |
| A-DATA Technology            | 148      | 1.19%   |
| Goodram                      | 104      | 0.84%   |
| G.Skill                      | 104      | 0.84%   |
| Apacer                       | 85       | 0.69%   |
| Nanya Technology             | 84       | 0.68%   |
| Unknown                      | 76       | 0.61%   |
| Kingmax                      | 70       | 0.56%   |
| Foxline                      | 65       | 0.52%   |
| Qumo                         | 63       | 0.51%   |
| Silicon Power                | 54       | 0.44%   |
| Goldkey                      | 52       | 0.42%   |
| Elpida                       | 45       | 0.36%   |
| Kllisre                      | 40       | 0.32%   |
| Transcend                    | 38       | 0.31%   |
| KETECH                       | 30       | 0.24%   |
| GeIL                         | 29       | 0.23%   |
| Atermiter                    | 28       | 0.23%   |
| Ramaxel Technology           | 27       | 0.22%   |
| Hikvision                    | 27       | 0.22%   |
| Unifosa                      | 23       | 0.19%   |
| Team                         | 22       | 0.18%   |
| Unknown (ABCD)               | 19       | 0.15%   |
| Ramos Technology             | 17       | 0.14%   |
| Patriot Memory (PDP Systems) | 16       | 0.13%   |
| Qimonda                      | 14       | 0.11%   |
| Patriot Memory               | 12       | 0.1%    |
| Neo Forza                    | 11       | 0.09%   |
| TakeMS                       | 9        | 0.07%   |
| KingSpec                     | 9        | 0.07%   |
| Juhor                        | 9        | 0.07%   |
| Wilk Elektronik              | 7        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 291      | 2.02%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 269      | 1.86%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                | 263      | 1.82%   |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 223      | 1.55%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s               | 214      | 1.48%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s               | 206      | 1.43%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s           | 188      | 1.3%    |
| Unknown RAM Module 1024MB DIMM 800MT/s                | 142      | 0.98%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s           | 138      | 0.96%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s           | 123      | 0.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                     | 112      | 0.78%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s   | 99       | 0.69%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 97       | 0.67%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                | 89       | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 87       | 0.6%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s               | 86       | 0.6%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                | 86       | 0.6%    |
| Unknown RAM Module 512MB DIMM SDRAM                   | 83       | 0.58%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                | 83       | 0.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 78       | 0.54%   |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 78       | 0.54%   |
| Unknown                                               | 76       | 0.53%   |
| Unknown RAM Module 1024MB DIMM                        | 71       | 0.49%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s | 70       | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s          | 69       | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s           | 65       | 0.45%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                | 64       | 0.44%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 63       | 0.44%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s          | 61       | 0.42%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s   | 61       | 0.42%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s           | 60       | 0.42%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s | 60       | 0.42%   |
| Unknown RAM Module 512MB DIMM                         | 50       | 0.35%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s     | 50       | 0.35%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s | 50       | 0.35%   |
| Unknown RAM Module 1GB DIMM SDRAM                     | 48       | 0.33%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s  | 48       | 0.33%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 47       | 0.33%   |
| Unknown RAM Module 2048MB DIMM                        | 47       | 0.33%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s | 47       | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR3         | 3749     | 33.3%   |
| DDR4         | 2795     | 24.83%  |
| Unknown      | 2009     | 17.85%  |
| DDR2         | 1293     | 11.49%  |
| SDRAM        | 1006     | 8.94%   |
| DDR          | 298      | 2.65%   |
| DDR5         | 54       | 0.48%   |
| LPDDR4       | 28       | 0.25%   |
| DRAM         | 22       | 0.2%    |
| DDR2 FB-DIMM | 2        | 0.02%   |
| LPDDR3       | 1        | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 10786    | 96.7%   |
| SODIMM       | 357      | 3.2%    |
| FB-DIMM      | 6        | 0.05%   |
| Row Of Chips | 4        | 0.04%   |
| RIMM         | 1        | 0.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 3627     | 28.12%  |
| 2048  | 3296     | 25.55%  |
| 8192  | 2910     | 22.56%  |
| 1024  | 1700     | 13.18%  |
| 16384 | 656      | 5.09%   |
| 512   | 420      | 3.26%   |
| 32768 | 190      | 1.47%   |
| 256   | 89       | 0.69%   |
| 32    | 5        | 0.04%   |
| 128   | 2        | 0.02%   |
| 16    | 2        | 0.02%   |
| 65536 | 1        | 0.01%   |
| 24576 | 1        | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 2118     | 17.23%  |
| 1333    | 1892     | 15.39%  |
| 800     | 1290     | 10.49%  |
| Unknown | 1001     | 8.14%   |
| 667     | 712      | 5.79%   |
| 2400    | 616      | 5.01%   |
| 2667    | 521      | 4.24%   |
| 3200    | 474      | 3.86%   |
| 2133    | 461      | 3.75%   |
| 400     | 287      | 2.33%   |
| 1866    | 242      | 1.97%   |
| 1867    | 234      | 1.9%    |
| 3600    | 225      | 1.83%   |
| 1066    | 182      | 1.48%   |
| 2666    | 146      | 1.19%   |
| 333     | 137      | 1.11%   |
| 533     | 136      | 1.11%   |
| 3400    | 133      | 1.08%   |
| 2933    | 125      | 1.02%   |
| 1800    | 106      | 0.86%   |
| 3466    | 75       | 0.61%   |
| 3733    | 73       | 0.59%   |
| 3266    | 67       | 0.55%   |
| 3000    | 67       | 0.55%   |
| 1067    | 61       | 0.5%    |
| 2800    | 59       | 0.48%   |
| 266     | 59       | 0.48%   |
| 1334    | 48       | 0.39%   |
| 3333    | 43       | 0.35%   |
| 2866    | 43       | 0.35%   |
| 1648    | 36       | 0.29%   |
| 66      | 33       | 0.27%   |
| 2000    | 30       | 0.24%   |
| 3334    | 28       | 0.23%   |
| 2134    | 28       | 0.23%   |
| 1400    | 26       | 0.21%   |
| 4800    | 25       | 0.2%    |
| 3066    | 24       | 0.2%    |
| 4333    | 21       | 0.17%   |
| 3800    | 20       | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Hewlett-Packard                 | 297      | 29.2%   |
| Canon                           | 215      | 21.14%  |
| Samsung Electronics             | 170      | 16.72%  |
| Seiko Epson                     | 91       | 8.95%   |
| Brother Industries              | 72       | 7.08%   |
| Xerox                           | 37       | 3.64%   |
| Pantum                          | 37       | 3.64%   |
| Panasonic (Matsushita)          | 25       | 2.46%   |
| Kyocera                         | 20       | 1.97%   |
| QinHeng Electronics             | 12       | 1.18%   |
| Ricoh                           | 10       | 0.98%   |
| Prolific Technology             | 7        | 0.69%   |
| TSC Auto ID Technology          | 2        | 0.2%    |
| STMicroelectronics              | 2        | 0.2%    |
| NXP Semiconductors              | 2        | 0.2%    |
| Lexmark International           | 2        | 0.2%    |
| Konica Minolta                  | 2        | 0.2%    |
| Custom Engineering SPA          | 2        | 0.2%    |
| cab Produkttechnik GmbH & Co KG | 2        | 0.2%    |
| Apple                           | 2        | 0.2%    |
| Sharp                           | 1        | 0.1%    |
| Samsung Info. Systems America   | 1        | 0.1%    |
| NCR                             | 1        | 0.1%    |
| KODAK                           | 1        | 0.1%    |
| HIPER                           | 1        | 0.1%    |
| GODEX INTERNATIONAL             | 1        | 0.1%    |
| Fuji Xerox                      | 1        | 0.1%    |
| Datamax-O'Neil                  | 1        | 0.1%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| HP LaserJet 1020                     | 31       | 3.03%   |
| HP LaserJet 1018                     | 29       | 2.83%   |
| Canon LBP2900                        | 29       | 2.83%   |
| Samsung SCX-4200 series              | 28       | 2.73%   |
| HP LaserJet P1102                    | 27       | 2.64%   |
| Panasonic (Matsushita) KX-MB1500RU   | 18       | 1.76%   |
| HP LaserJet 1010                     | 18       | 1.76%   |
| HP LaserJet P1005                    | 16       | 1.56%   |
| Samsung SCX-3400 Series              | 15       | 1.46%   |
| Seiko Epson Printer                  | 14       | 1.37%   |
| Samsung SCX-3200 Series              | 14       | 1.37%   |
| Canon MF4410                         | 14       | 1.37%   |
| HP LaserJet 1320                     | 13       | 1.27%   |
| Canon MF4010 series                  | 13       | 1.27%   |
| Canon MF3010                         | 13       | 1.27%   |
| Seiko Epson USB2.0 Printer           | 12       | 1.17%   |
| Samsung M2070 Series                 | 12       | 1.17%   |
| QinHeng CH340S                       | 12       | 1.17%   |
| Pantum P2200 series                  | 12       | 1.17%   |
| HP DeskJet 2130 series               | 11       | 1.07%   |
| HP LaserJet 1300                     | 10       | 0.98%   |
| HP LaserJet 1200                     | 10       | 0.98%   |
| Seiko Epson L210 Series              | 9        | 0.88%   |
| Samsung SCX-4100 Scanner             | 9        | 0.88%   |
| Samsung ML-2010P Mono Laser Printer  | 9        | 0.88%   |
| Samsung ML-1640 Series Laser Printer | 9        | 0.88%   |
| Pantum M6500 series                  | 9        | 0.88%   |
| HP LaserJet 1022                     | 9        | 0.88%   |
| Canon LBP810                         | 9        | 0.88%   |
| Canon LBP3010/LBP3018/LBP3050        | 9        | 0.88%   |
| Xerox Phaser 3140 and 3155           | 8        | 0.78%   |
| Samsung ML-216x Series Laser Printer | 8        | 0.78%   |
| Samsung ML-1210 Printer              | 8        | 0.78%   |
| Canon PIXMA MG2500 Series            | 8        | 0.78%   |
| Canon LBP6000                        | 8        | 0.78%   |
| Brother HL-2030 Laser Printer        | 8        | 0.78%   |
| Brother HL-1110 series               | 8        | 0.78%   |
| Brother DCP-7057 scanner/printer     | 8        | 0.78%   |
| Xerox WorkCentre 3119 Series         | 7        | 0.68%   |
| Xerox Phaser 3020                    | 7        | 0.68%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 106      | 38.13%  |
| Seiko Epson                 | 67       | 24.1%   |
| Hewlett-Packard             | 48       | 17.27%  |
| Mustek Systems              | 29       | 10.43%  |
| Acer Peripherals (now BenQ) | 11       | 3.96%   |
| Ultima Electronics          | 10       | 3.6%    |
| KYE Systems (Mouse Systems) | 3        | 1.08%   |
| Avision                     | 2        | 0.72%   |
| Plustek                     | 1        | 0.36%   |
| Canon Electronics           | 1        | 0.36%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| HP ScanJet 2400c                                                                      | 18       | 6.45%   |
| Canon CanoScan LIDE 25                                                                | 18       | 6.45%   |
| Canon CanoScan LiDE 110                                                               | 18       | 6.45%   |
| Canon CanoScan LiDE 120                                                               | 16       | 5.73%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 11       | 3.94%   |
| Canon CanoScan LiDE 210                                                               | 11       | 3.94%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 9        | 3.23%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 9        | 3.23%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 8        | 2.87%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 8        | 2.87%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 8        | 2.87%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 8        | 2.87%   |
| Mustek Systems SNAPSCAN e22                                                           | 6        | 2.15%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 6        | 2.15%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 5        | 1.79%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 5        | 1.79%   |
| Canon CanoScan LiDE 60                                                                | 5        | 1.79%   |
| Canon CanoScan LiDE 220                                                               | 5        | 1.79%   |
| Canon CanoScan LiDE 100                                                               | 5        | 1.79%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 4        | 1.43%   |
| HP ScanJet 3800c                                                                      | 4        | 1.43%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 4        | 1.43%   |
| Seiko Epson Perfection 660                                                            | 3        | 1.08%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 3        | 1.08%   |
| HP ScanJet 3970c                                                                      | 3        | 1.08%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 3        | 1.08%   |
| Canon CanoScan LiDE 70                                                                | 3        | 1.08%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 3        | 1.08%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 0.72%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 2        | 0.72%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 2        | 0.72%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 2        | 0.72%   |
| HP ScanJet G4050                                                                      | 2        | 0.72%   |
| HP Scanjet G2710                                                                      | 2        | 0.72%   |
| HP ScanJet 4300c                                                                      | 2        | 0.72%   |
| HP ScanJet 2300c                                                                      | 2        | 0.72%   |
| Canon CanoScan LiDE 700F                                                              | 2        | 0.72%   |
| Canon CanoScan LiDE 200                                                               | 2        | 0.72%   |
| Canon CanoScan                                                                        | 2        | 0.72%   |
| Avision iVina FB1600/UMAX Astra 4500                                                  | 2        | 0.72%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 810      | 33.16%  |
| Z-Star Microelectronics                | 392      | 16.05%  |
| Microdia                               | 184      | 7.53%   |
| Microsoft                              | 123      | 5.03%   |
| KYE Systems (Mouse Systems)            | 97       | 3.97%   |
| Arkmicro Technologies                  | 75       | 3.07%   |
| GEMBIRD                                | 69       | 2.82%   |
| Aveo Technology                        | 62       | 2.54%   |
| Cubeternet                             | 53       | 2.17%   |
| Chicony Electronics                    | 52       | 2.13%   |
| Pixart Imaging                         | 51       | 2.09%   |
| Creative Technology                    | 47       | 1.92%   |
| Realtek Semiconductor                  | 45       | 1.84%   |
| Alcor Micro                            | 43       | 1.76%   |
| Sunplus Innovation Technology          | 38       | 1.56%   |
| Apple                                  | 33       | 1.35%   |
| Samsung Electronics                    | 23       | 0.94%   |
| A4Tech                                 | 21       | 0.86%   |
| Genesys Logic                          | 18       | 0.74%   |
| SunplusIT                              | 15       | 0.61%   |
| Guillemot                              | 14       | 0.57%   |
| Hewlett-Packard                        | 13       | 0.53%   |
| lihappe8                               | 11       | 0.45%   |
| Generalplus Technology                 | 11       | 0.45%   |
| AVerMedia Technologies                 | 11       | 0.45%   |
| Philips (or NXP)                       | 10       | 0.41%   |
| SiGma Micro                            | 8        | 0.33%   |
| IMC Networks                           | 8        | 0.33%   |
| Trust                                  | 7        | 0.29%   |
| Jieli Technology                       | 7        | 0.29%   |
| Xiaomi                                 | 4        | 0.16%   |
| Unknown                                | 4        | 0.16%   |
| Silicon Motion                         | 4        | 0.16%   |
| Cheng Uei Precision Industry (Foxlink) | 4        | 0.16%   |
| ANYKA                                  | 4        | 0.16%   |
| Suyin                                  | 3        | 0.12%   |
| Sony                                   | 3        | 0.12%   |
| Sonix Technology                       | 3        | 0.12%   |
| OPPO Electronics                       | 3        | 0.12%   |
| Nokia Mobile Phones                    | 3        | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 293      | 11.97%  |
| Z-Star Venus USB2.0 Camera                        | 168      | 6.87%   |
| Microdia Camera                                   | 118      | 4.82%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 110      | 4.5%    |
| Z-Star A4 TECH USB2.0 PC Camera E                 | 82       | 3.35%   |
| Arkmicro USB2.0 PC CAMERA                         | 69       | 2.82%   |
| Logitech Webcam C170                              | 67       | 2.74%   |
| Logitech Webcam C310                              | 62       | 2.53%   |
| Logitech HD Webcam C525                           | 58       | 2.37%   |
| Logitech Webcam C210                              | 47       | 1.92%   |
| Microsoft LifeCam HD-3000                         | 39       | 1.59%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 38       | 1.55%   |
| GEMBIRD USB2.0 PC CAMERA                          | 37       | 1.51%   |
| Logitech HD Pro Webcam C920                       | 32       | 1.31%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 31       | 1.27%   |
| Cubeternet GL-UPC822 UVC WebCam                   | 30       | 1.23%   |
| Alcor Micro USB 2.0 PC Camera                     | 29       | 1.19%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 28       | 1.14%   |
| Logitech Webcam C110                              | 27       | 1.1%    |
| Logitech HD Webcam C510                           | 26       | 1.06%   |
| Aveo Camera                                       | 24       | 0.98%   |
| Samsung Galaxy series, misc. (MTP mode)           | 22       | 0.9%    |
| Microsoft LifeCam VX-800                          | 22       | 0.9%    |
| Logitech Logitech Webcam C160                     | 20       | 0.82%   |
| Logitech HD Webcam C615                           | 20       | 0.82%   |
| Sunplus Full HD webcam                            | 19       | 0.78%   |
| Logitech HD Webcam C910                           | 19       | 0.78%   |
| Aveo USB2.0 Camera                                | 19       | 0.78%   |
| Realtek Full HD webcam                            | 18       | 0.74%   |
| Microdia USB 2.0 Camera                           | 17       | 0.69%   |
| Z-Star Full HD 1080P PC Camera                    | 16       | 0.65%   |
| Cubeternet USB2.0 Camera                          | 16       | 0.65%   |
| Microdia Sonix USB 2.0 Camera                     | 15       | 0.61%   |
| Aveo UVC camera (Bresser microscope)              | 15       | 0.61%   |
| Microsoft LifeCam VX-2000                         | 14       | 0.57%   |
| Microsoft LifeCam HD-5000                         | 14       | 0.57%   |
| Logitech Logitech Webcam C100                     | 14       | 0.57%   |
| A4Tech FHD 1080P PC Camera                        | 14       | 0.57%   |
| Microsoft LifeCam Cinema                          | 13       | 0.53%   |
| Genesys Logic Camera                              | 12       | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 5        | 50%     |
| STMicroelectronics    | 2        | 20%     |
| Microsoft             | 2        | 20%     |
| Elan Microelectronics | 1        | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor               | 3        | 30%     |
| STMicroelectronics Fingerprint Reader       | 2        | 20%     |
| Microsoft Fingerprint Reader                | 2        | 20%     |
| LighTuning ES603 Swipe Fingerprint Sensor   | 1        | 10%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 1        | 10%     |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Aktiv                      | 13       | 26%     |
| Aladdin Knowledge Systems  | 11       | 22%     |
| Aladdin R.D.               | 8        | 16%     |
| Athena Smartcard Solutions | 4        | 8%      |
| Alcor Micro                | 4        | 8%      |
| Advanced Card Systems      | 4        | 8%      |
| Yubico.com                 | 2        | 4%      |
| Realtek Semiconductor      | 1        | 2%      |
| OmniKey                    | 1        | 2%      |
| Gemalto (was Gemplus)      | 1        | 2%      |
| Castles Technology         | 1        | 2%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Aktiv Rutoken lite                                | 13       | 26%     |
| Aladdin Knowledge Systems Token JC                | 11       | 22%     |
| Aladdin R.D. JaCarta                              | 6        | 12%     |
| Athena Smartcard Solutions ASEDrive CCID          | 4        | 8%      |
| Alcor Micro Watchdata W 1981                      | 3        | 6%      |
| Yubico.com Yubikey 4/5 U2F+CCID                   | 2        | 4%      |
| Realtek Semiconductor Smart Card Reader Interface | 1        | 2%      |
| OmniKey Smart Card Reader USB                     | 1        | 2%      |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader  | 1        | 2%      |
| Castles Technology EZCCID Smart Card Reader       | 1        | 2%      |
| Alcor Micro AU9540 Smartcard Reader               | 1        | 2%      |
| Aladdin R.D. Smart card reader JCR721             | 1        | 2%      |
| Aladdin R.D. JaCarta LT                           | 1        | 2%      |
| Advanced Card Systems ACR39U                      | 1        | 2%      |
| Advanced Card Systems ACR3901U                    | 1        | 2%      |
| Advanced Card Systems ACR38 SmartCard Reader      | 1        | 2%      |
| Advanced Card Systems ACR1281 1S Dual Reader      | 1        | 2%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 10616    | 81.55%  |
| 1     | 2124     | 16.32%  |
| 2     | 210      | 1.61%   |
| 3     | 31       | 0.24%   |
| 4     | 29       | 0.22%   |
| 6     | 3        | 0.02%   |
| 5     | 3        | 0.02%   |
| 9     | 1        | 0.01%   |
| 7     | 1        | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 1711     | 65.16%  |
| Net/wireless             | 257      | 9.79%   |
| Communication controller | 173      | 6.59%   |
| Unassigned class         | 127      | 4.84%   |
| Multimedia controller    | 70       | 2.67%   |
| Sound                    | 62       | 2.36%   |
| Camera                   | 39       | 1.49%   |
| Chipcard                 | 36       | 1.37%   |
| Net/ethernet             | 30       | 1.14%   |
| Bluetooth                | 22       | 0.84%   |
| Network                  | 20       | 0.76%   |
| Modem                    | 17       | 0.65%   |
| Storage/raid             | 14       | 0.53%   |
| Fingerprint reader       | 10       | 0.38%   |
| Firewire controller      | 8        | 0.3%    |
| Dvb card                 | 8        | 0.3%    |
| Storage/ata              | 7        | 0.27%   |
| Storage/ide              | 5        | 0.19%   |
| Tv card                  | 4        | 0.15%   |
| Storage                  | 3        | 0.11%   |
| Video                    | 1        | 0.04%   |
| Unclassified device      | 1        | 0.04%   |
| Card reader              | 1        | 0.04%   |

