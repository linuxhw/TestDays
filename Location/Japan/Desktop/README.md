Linux in Japan - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Japan.

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

Total: 821

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P5B-E Plus                  | [78c413cac5](https://linux-hardware.org/?probe=78c413cac5) | Sep 30, 2023 |
| Unknown       | TB-5000                     | [9c67baa34f](https://linux-hardware.org/?probe=9c67baa34f) | Sep 29, 2023 |
| GMKtec        | NucBox3                     | [c99750febd](https://linux-hardware.org/?probe=c99750febd) | Sep 28, 2023 |
| ASRock        | Z370 Pro4                   | [a70543ae67](https://linux-hardware.org/?probe=a70543ae67) | Sep 28, 2023 |
| ASUSTek       | PRO H410M-C                 | [6554d255c3](https://linux-hardware.org/?probe=6554d255c3) | Sep 27, 2023 |
| AAEON         | MIX-H310D1 V1.0             | [7a3b3d3b2d](https://linux-hardware.org/?probe=7a3b3d3b2d) | Sep 27, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | [fa9b30f699](https://linux-hardware.org/?probe=fa9b30f699) | Sep 18, 2023 |
| MSI           | H510I PRO WIFI              | [e8f9c86131](https://linux-hardware.org/?probe=e8f9c86131) | Sep 16, 2023 |
| ASRock        | B450 Pro4                   | [b3d56132ec](https://linux-hardware.org/?probe=b3d56132ec) | Sep 15, 2023 |
| Intel         | DG41TY AAE47335-202         | [cd00ffcda2](https://linux-hardware.org/?probe=cd00ffcda2) | Sep 09, 2023 |
| Intel         | DG41TY AAE47335-202         | [4cdbce3b75](https://linux-hardware.org/?probe=4cdbce3b75) | Sep 09, 2023 |
| NEC Comput... | MS-7451MA                   | [963dde730a](https://linux-hardware.org/?probe=963dde730a) | Sep 03, 2023 |
| MSI           | X99A WORKSTATION            | [46d1af7083](https://linux-hardware.org/?probe=46d1af7083) | Sep 01, 2023 |
| HP            | 806A                        | [638dfe4edc](https://linux-hardware.org/?probe=638dfe4edc) | Aug 31, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [c95eb85e58](https://linux-hardware.org/?probe=c95eb85e58) | Aug 30, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | [ad154077da](https://linux-hardware.org/?probe=ad154077da) | Aug 28, 2023 |
| ASRock        | A320M-HDV R4.0              | [ccc34d5a51](https://linux-hardware.org/?probe=ccc34d5a51) | Aug 25, 2023 |
| MSI           | A320M-A PRO                 | [25dc707bff](https://linux-hardware.org/?probe=25dc707bff) | Aug 24, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [62ac8a7715](https://linux-hardware.org/?probe=62ac8a7715) | Aug 23, 2023 |
| HP            | 18E7                        | [7c200916bf](https://linux-hardware.org/?probe=7c200916bf) | Aug 22, 2023 |
| HP            | 18E7                        | [6cd6ef6396](https://linux-hardware.org/?probe=6cd6ef6396) | Aug 22, 2023 |
| Shenzhen M... | F7BSC                       | [94b9b057b4](https://linux-hardware.org/?probe=94b9b057b4) | Aug 17, 2023 |
| Dell          | 0XFWHV A00                  | [0ddde115f9](https://linux-hardware.org/?probe=0ddde115f9) | Aug 17, 2023 |
| ASUSTek       | H170-PRO                    | [a5086e207e](https://linux-hardware.org/?probe=a5086e207e) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c5ad691377](https://linux-hardware.org/?probe=c5ad691377) | Aug 14, 2023 |
| ASUSTek       | Rampage IV GENE             | [2a494a04b5](https://linux-hardware.org/?probe=2a494a04b5) | Aug 12, 2023 |
| Fujitsu       | JIQ87Y                      | [b11d99014e](https://linux-hardware.org/?probe=b11d99014e) | Aug 12, 2023 |
| NEC Comput... | 312C                        | [770ffcfcf5](https://linux-hardware.org/?probe=770ffcfcf5) | Aug 10, 2023 |
| Biostar       | B350GTN                     | [5ae18cae6c](https://linux-hardware.org/?probe=5ae18cae6c) | Aug 04, 2023 |
| Dell          | 07PR60 A00                  | [590695e09f](https://linux-hardware.org/?probe=590695e09f) | Aug 02, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [993a10a30b](https://linux-hardware.org/?probe=993a10a30b) | Aug 01, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | [44937ea360](https://linux-hardware.org/?probe=44937ea360) | Jul 30, 2023 |
| ASRock        | H270 Pro4                   | [52cefaf6dd](https://linux-hardware.org/?probe=52cefaf6dd) | Jul 28, 2023 |
| Dell          | 07PR60 A00                  | [67ef05bdd5](https://linux-hardware.org/?probe=67ef05bdd5) | Jul 27, 2023 |
| Biostar       | H81MHV3 5.0                 | [06e3fae658](https://linux-hardware.org/?probe=06e3fae658) | Jul 24, 2023 |
| MSI           | Z87-G43                     | [f153badd8c](https://linux-hardware.org/?probe=f153badd8c) | Jul 23, 2023 |
| Shenzhen M... | F7BFC                       | [a9639fb963](https://linux-hardware.org/?probe=a9639fb963) | Jul 22, 2023 |
| HP            | 158A                        | [a2a4176353](https://linux-hardware.org/?probe=a2a4176353) | Jul 22, 2023 |
| Intel         | JSL MRD                     | [4c9c765884](https://linux-hardware.org/?probe=4c9c765884) | Jul 21, 2023 |
| Pegatron      | IPM41G                      | [9d29cf9820](https://linux-hardware.org/?probe=9d29cf9820) | Jul 18, 2023 |
| MSI           | PRO Z690-A WIFI             | [d20f9ee7a7](https://linux-hardware.org/?probe=d20f9ee7a7) | Jul 14, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [00e22b8fa7](https://linux-hardware.org/?probe=00e22b8fa7) | Jul 10, 2023 |
| Pegatron      | IPM41G                      | [be1f42c658](https://linux-hardware.org/?probe=be1f42c658) | Jul 09, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [13195d7ff3](https://linux-hardware.org/?probe=13195d7ff3) | Jul 02, 2023 |
| Dell          | 08NPPY A00                  | [9f1aec7e08](https://linux-hardware.org/?probe=9f1aec7e08) | Jul 01, 2023 |
| HP            | 0A54h                       | [7383b90fc8](https://linux-hardware.org/?probe=7383b90fc8) | Jun 24, 2023 |
| HP            | 0A54h                       | [8cf79bc35e](https://linux-hardware.org/?probe=8cf79bc35e) | Jun 23, 2023 |
| ASUSTek       | PRIME B365M-A               | [4e877b9c8d](https://linux-hardware.org/?probe=4e877b9c8d) | Jun 22, 2023 |
| ASRock        | B760 Pro RS/D4              | [bf19dd1c4b](https://linux-hardware.org/?probe=bf19dd1c4b) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [2e14ad6bce](https://linux-hardware.org/?probe=2e14ad6bce) | Jun 20, 2023 |
| ASRock        | H270 Pro4                   | [e3b13a5c7f](https://linux-hardware.org/?probe=e3b13a5c7f) | Jun 20, 2023 |
| ASRock        | B760 Pro RS/D4              | [6767dd6968](https://linux-hardware.org/?probe=6767dd6968) | Jun 16, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [09b0f43143](https://linux-hardware.org/?probe=09b0f43143) | Jun 14, 2023 |
| MouseCompu... | B360M                       | [6a7f26bdae](https://linux-hardware.org/?probe=6a7f26bdae) | Jun 12, 2023 |
| ASRock        | G41C-GS R2.0                | [6e4835c7bc](https://linux-hardware.org/?probe=6e4835c7bc) | Jun 06, 2023 |
| Acer          | Veriton X4630G V:1.0        | [5106e40f32](https://linux-hardware.org/?probe=5106e40f32) | Jun 04, 2023 |
| Gigabyte      | H61M-DS2 x.x                | [e58b7bfc92](https://linux-hardware.org/?probe=e58b7bfc92) | May 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ea5ba11b48](https://linux-hardware.org/?probe=ea5ba11b48) | May 27, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [769f5c0d23](https://linux-hardware.org/?probe=769f5c0d23) | May 25, 2023 |
| EPSON DIRE... | MR7200E-L                   | [a436b49a11](https://linux-hardware.org/?probe=a436b49a11) | May 24, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [31ea0c4ab8](https://linux-hardware.org/?probe=31ea0c4ab8) | May 24, 2023 |
| Gigabyte      | B75M-D3H                    | [00a6f60d75](https://linux-hardware.org/?probe=00a6f60d75) | May 23, 2023 |
| ASRock        | H77M                        | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| ASRock        | H310M-STX                   | [c5d385dd80](https://linux-hardware.org/?probe=c5d385dd80) | May 22, 2023 |
| ASRock        | B550M-ITX/ac                | [b03cb56dfa](https://linux-hardware.org/?probe=b03cb56dfa) | May 21, 2023 |
| Fujitsu       | D3420-U1 S26361-D3420-U1    | [958b2ab1f9](https://linux-hardware.org/?probe=958b2ab1f9) | May 17, 2023 |
| EPSON DIRE... | MR7200E-L                   | [fed1ba2b90](https://linux-hardware.org/?probe=fed1ba2b90) | May 17, 2023 |
| EPSON DIRE... | MR7200E-L                   | [b0710623f7](https://linux-hardware.org/?probe=b0710623f7) | May 17, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [35990f19da](https://linux-hardware.org/?probe=35990f19da) | May 12, 2023 |
| ASUSTek       | H170-PRO                    | [8f41b17a9b](https://linux-hardware.org/?probe=8f41b17a9b) | May 10, 2023 |
| Acer          | EG43M                       | [01704e814c](https://linux-hardware.org/?probe=01704e814c) | May 09, 2023 |
| ASRock        | B760 Pro RS/D4              | [cf7cf903c0](https://linux-hardware.org/?probe=cf7cf903c0) | May 08, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [e7b77f5cf0](https://linux-hardware.org/?probe=e7b77f5cf0) | May 08, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | [22bd54d6d1](https://linux-hardware.org/?probe=22bd54d6d1) | May 08, 2023 |
| NEC Comput... | IH81M                       | [407098c17f](https://linux-hardware.org/?probe=407098c17f) | May 07, 2023 |
| ASUSTek       | STRIX B250I GAMING          | [536e6e7cc9](https://linux-hardware.org/?probe=536e6e7cc9) | May 07, 2023 |
| HP            | 1998                        | [92772a7c11](https://linux-hardware.org/?probe=92772a7c11) | May 06, 2023 |
| MouseCompu... | B75M-D3V-JP                 | [a72531bd2d](https://linux-hardware.org/?probe=a72531bd2d) | May 04, 2023 |
| ASRock        | B760 Pro RS/D4              | [78dbd4cfb6](https://linux-hardware.org/?probe=78dbd4cfb6) | May 04, 2023 |
| Intel         | PH10LU E13069-531           | [432b5e380d](https://linux-hardware.org/?probe=432b5e380d) | May 03, 2023 |
| Intel         | PH10LU E13069-531           | [f34e545b00](https://linux-hardware.org/?probe=f34e545b00) | May 03, 2023 |
| HP            | 158A                        | [fb7aef7883](https://linux-hardware.org/?probe=fb7aef7883) | Apr 28, 2023 |
| MSI           | A78M-E35 V2                 | [5eb0f9d104](https://linux-hardware.org/?probe=5eb0f9d104) | Apr 27, 2023 |
| HP            | 158A                        | [c3189bccb1](https://linux-hardware.org/?probe=c3189bccb1) | Apr 26, 2023 |
| ASUSTek       | STRIX B250I GAMING          | [beabf00341](https://linux-hardware.org/?probe=beabf00341) | Apr 24, 2023 |
| ASUSTek       | STRIX B250I GAMING          | [0e96ee4471](https://linux-hardware.org/?probe=0e96ee4471) | Apr 23, 2023 |
| Shenzhen M... | F6CQW                       | [c2be3dd62b](https://linux-hardware.org/?probe=c2be3dd62b) | Apr 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [cc80f06375](https://linux-hardware.org/?probe=cc80f06375) | Apr 23, 2023 |
| ASUSTek       | Z87-PRO                     | [08ebdd71ab](https://linux-hardware.org/?probe=08ebdd71ab) | Apr 23, 2023 |
| Fujitsu       | FJNB037                     | [00e5e30f9b](https://linux-hardware.org/?probe=00e5e30f9b) | Apr 22, 2023 |
| Dell          | 0K240Y A02                  | [2d1b73d846](https://linux-hardware.org/?probe=2d1b73d846) | Apr 22, 2023 |
| ECS           | APLD-MINI                   | [8f3546722b](https://linux-hardware.org/?probe=8f3546722b) | Apr 22, 2023 |
| MouseCompu... | Z87-S01                     | [8caff0d2f2](https://linux-hardware.org/?probe=8caff0d2f2) | Apr 21, 2023 |
| ASRock        | Z270 Taichi                 | [faf3402431](https://linux-hardware.org/?probe=faf3402431) | Apr 21, 2023 |
| ECS           | BSW-MINI                    | [5d3161092f](https://linux-hardware.org/?probe=5d3161092f) | Apr 19, 2023 |
| ASRock        | B550M Pro4                  | [5fa6c74be4](https://linux-hardware.org/?probe=5fa6c74be4) | Apr 19, 2023 |
| ASUSTek       | Z87-PRO                     | [7981ad8440](https://linux-hardware.org/?probe=7981ad8440) | Apr 19, 2023 |
| NEC Comput... | MS-7451VM                   | [dc094ceba3](https://linux-hardware.org/?probe=dc094ceba3) | Apr 18, 2023 |
| ASRock        | B450M Pro4                  | [4c6abc2653](https://linux-hardware.org/?probe=4c6abc2653) | Apr 18, 2023 |
| ASRock        | Z270 Taichi                 | [5f3eb929b7](https://linux-hardware.org/?probe=5f3eb929b7) | Apr 18, 2023 |
| ASUSTek       | P8H67-M PRO                 | [9eb59318e2](https://linux-hardware.org/?probe=9eb59318e2) | Apr 18, 2023 |
| ASRock        | B450M Pro4                  | [eb66896af3](https://linux-hardware.org/?probe=eb66896af3) | Apr 18, 2023 |
| ASUSTek       | B85M-G                      | [8f5803697f](https://linux-hardware.org/?probe=8f5803697f) | Apr 17, 2023 |
| ASRock        | A520M TW                    | [0fc8e9ca06](https://linux-hardware.org/?probe=0fc8e9ca06) | Apr 17, 2023 |
| ASUSTek       | PRIME A320M-K               | [a2596e8d06](https://linux-hardware.org/?probe=a2596e8d06) | Apr 16, 2023 |
| Gigabyte      | F2A85XN-WIFI                | [80a8d69a06](https://linux-hardware.org/?probe=80a8d69a06) | Apr 15, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [0ec41c7bd8](https://linux-hardware.org/?probe=0ec41c7bd8) | Apr 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [9cf22928fb](https://linux-hardware.org/?probe=9cf22928fb) | Apr 13, 2023 |
| MSI           | B450I GAMING PLUS AC        | [e34683f5f0](https://linux-hardware.org/?probe=e34683f5f0) | Apr 07, 2023 |
| MSI           | B450M MORTAR MAX            | [0077b88576](https://linux-hardware.org/?probe=0077b88576) | Apr 06, 2023 |
| ASUSTek       | P5KPL-CM                    | [78c525b19b](https://linux-hardware.org/?probe=78c525b19b) | Apr 05, 2023 |
| ASRock        | B450M Pro4                  | [6bf9bb58c5](https://linux-hardware.org/?probe=6bf9bb58c5) | Apr 04, 2023 |
| ASRock        | B460M Pro4                  | [1f3b96d1a0](https://linux-hardware.org/?probe=1f3b96d1a0) | Apr 01, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [393fc00a5d](https://linux-hardware.org/?probe=393fc00a5d) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [f0540604bc](https://linux-hardware.org/?probe=f0540604bc) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [1c575e8cb6](https://linux-hardware.org/?probe=1c575e8cb6) | Mar 30, 2023 |
| ASUSTek       | A88XM-A                     | [405e95a907](https://linux-hardware.org/?probe=405e95a907) | Mar 28, 2023 |
| MSI           | B450M MORTAR MAX            | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| Huanan        | X99-F8 V2.0                 | [922d8a7941](https://linux-hardware.org/?probe=922d8a7941) | Mar 26, 2023 |
| MSI           | MEG B550 UNIFY              | [492a70f1c3](https://linux-hardware.org/?probe=492a70f1c3) | Mar 26, 2023 |
| HP            | 158A                        | [9ed0f8f65f](https://linux-hardware.org/?probe=9ed0f8f65f) | Mar 25, 2023 |
| MSI           | B450M MORTAR MAX            | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| HP            | 158A                        | [033f7a5abd](https://linux-hardware.org/?probe=033f7a5abd) | Mar 21, 2023 |
| MSI           | B450M MORTAR MAX            | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| ASUSTek       | PRIME B350M-A               | [9ee81ffe32](https://linux-hardware.org/?probe=9ee81ffe32) | Mar 20, 2023 |
| ASRock        | 4X4-4000 Series             | [3718d345ca](https://linux-hardware.org/?probe=3718d345ca) | Mar 18, 2023 |
| Lenovo        | ThinkCentre A58 7522M4J     | [ba0a303be5](https://linux-hardware.org/?probe=ba0a303be5) | Mar 17, 2023 |
| HP            | 806A                        | [2203b83131](https://linux-hardware.org/?probe=2203b83131) | Mar 13, 2023 |
| Unknown       | HX90                        | [51aca581e4](https://linux-hardware.org/?probe=51aca581e4) | Mar 11, 2023 |
| Gigabyte      | P55-UD3R                    | [e720741a00](https://linux-hardware.org/?probe=e720741a00) | Mar 11, 2023 |
| ASUSTek       | B85M-G                      | [70f4bed81b](https://linux-hardware.org/?probe=70f4bed81b) | Mar 08, 2023 |
| ASUSTek       | PRO H410M-C                 | [a97c12b513](https://linux-hardware.org/?probe=a97c12b513) | Mar 08, 2023 |
| Wistron       | ProLiant ML110 G5           | [a36361538b](https://linux-hardware.org/?probe=a36361538b) | Mar 07, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [f85824345a](https://linux-hardware.org/?probe=f85824345a) | Mar 06, 2023 |
| Gigabyte      | GA-E7AUM-DS2H               | [825b26708c](https://linux-hardware.org/?probe=825b26708c) | Mar 04, 2023 |
| ASUSTek       | PRO H410M-C                 | [b0076c9250](https://linux-hardware.org/?probe=b0076c9250) | Mar 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ed5432e979](https://linux-hardware.org/?probe=ed5432e979) | Mar 01, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [3887cb1418](https://linux-hardware.org/?probe=3887cb1418) | Feb 26, 2023 |
| Gigabyte      | B85N PHOENIX                | [5fe00f35c4](https://linux-hardware.org/?probe=5fe00f35c4) | Feb 25, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [7864921f8d](https://linux-hardware.org/?probe=7864921f8d) | Feb 25, 2023 |
| ASUSTek       | PRO H410M-C                 | [d6edc5401d](https://linux-hardware.org/?probe=d6edc5401d) | Feb 22, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [a7270cf962](https://linux-hardware.org/?probe=a7270cf962) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [b8b41b7a6e](https://linux-hardware.org/?probe=b8b41b7a6e) | Feb 19, 2023 |
| HP            | 158A                        | [ce217224ba](https://linux-hardware.org/?probe=ce217224ba) | Feb 19, 2023 |
| Gigabyte      | B450M S2H                   | [eb04bfdc84](https://linux-hardware.org/?probe=eb04bfdc84) | Feb 14, 2023 |
| ASUSTek       | H110M-A/M.2                 | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| ASUSTek       | H110M-A/M.2                 | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| ASUSTek       | PRIME A320M-A               | [9de02793ea](https://linux-hardware.org/?probe=9de02793ea) | Feb 04, 2023 |
| ASRock        | Z87M Extreme4               | [8821f128c8](https://linux-hardware.org/?probe=8821f128c8) | Feb 03, 2023 |
| NEC Comput... | MS9666 011                  | [26a38770fe](https://linux-hardware.org/?probe=26a38770fe) | Feb 02, 2023 |
| Wistron       | ProLiant ML110 G5           | [4af666d5b3](https://linux-hardware.org/?probe=4af666d5b3) | Feb 02, 2023 |
| BESSTAR Te... | HM90                        | [3f958de9bb](https://linux-hardware.org/?probe=3f958de9bb) | Feb 01, 2023 |
| ASUSTek       | PRIME B350M-A               | [e2721d08d6](https://linux-hardware.org/?probe=e2721d08d6) | Jan 30, 2023 |
| ASUSTek       | PRIME Z270-P                | [15644c39de](https://linux-hardware.org/?probe=15644c39de) | Jan 25, 2023 |
| MSI           | H110M PRO-VH                | [7068e861ba](https://linux-hardware.org/?probe=7068e861ba) | Jan 21, 2023 |
| Unknown       | HX90                        | [2b034e44e2](https://linux-hardware.org/?probe=2b034e44e2) | Jan 18, 2023 |
| ASRock        | B550M Pro4                  | [b781eb32d2](https://linux-hardware.org/?probe=b781eb32d2) | Jan 18, 2023 |
| HC            | HCAR357-MI V1.0             | [ef934af180](https://linux-hardware.org/?probe=ef934af180) | Jan 16, 2023 |
| ASUSTek       | J1900I-C                    | [6a2ef2080d](https://linux-hardware.org/?probe=6a2ef2080d) | Jan 09, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [99e2769927](https://linux-hardware.org/?probe=99e2769927) | Jan 07, 2023 |
| ASUSTek       | PRIME B365-PLUS             | [d3bab9b69b](https://linux-hardware.org/?probe=d3bab9b69b) | Jan 02, 2023 |
| HP            | 2B36                        | [4b363628a9](https://linux-hardware.org/?probe=4b363628a9) | Dec 30, 2022 |
| HP            | 2B36                        | [be6670b1ad](https://linux-hardware.org/?probe=be6670b1ad) | Dec 30, 2022 |
| ASUSTek       | P6T DELUXE V2               | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| ASRock        | X570M Pro4                  | [71d2c76079](https://linux-hardware.org/?probe=71d2c76079) | Dec 28, 2022 |
| HP            | 18E7                        | [260119e159](https://linux-hardware.org/?probe=260119e159) | Dec 25, 2022 |
| Dell          | 0C2KJT A00                  | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [117f4c04d6](https://linux-hardware.org/?probe=117f4c04d6) | Dec 21, 2022 |
| ASUSTek       | H170-PRO                    | [3d866a7ec8](https://linux-hardware.org/?probe=3d866a7ec8) | Dec 19, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [17618a8281](https://linux-hardware.org/?probe=17618a8281) | Dec 18, 2022 |
| HP            | 8054                        | [98d0f316b3](https://linux-hardware.org/?probe=98d0f316b3) | Dec 18, 2022 |
| MSI           | MS-7360                     | [2f5a9baf11](https://linux-hardware.org/?probe=2f5a9baf11) | Dec 18, 2022 |
| Dell          | 042P49 A02                  | [8b97211b80](https://linux-hardware.org/?probe=8b97211b80) | Dec 11, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7d6b3699e7](https://linux-hardware.org/?probe=7d6b3699e7) | Dec 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [c22c7dfa5c](https://linux-hardware.org/?probe=c22c7dfa5c) | Dec 09, 2022 |
| ASRock        | Z370 Pro4                   | [769fed352d](https://linux-hardware.org/?probe=769fed352d) | Dec 06, 2022 |
| ASRock        | A320M-HDV R4.0              | [eeb0795100](https://linux-hardware.org/?probe=eeb0795100) | Dec 05, 2022 |
| ASUSTek       | X99-PRO                     | [6906303697](https://linux-hardware.org/?probe=6906303697) | Nov 25, 2022 |
| Biostar       | X470GTA                     | [83dcb407ba](https://linux-hardware.org/?probe=83dcb407ba) | Nov 23, 2022 |
| ASRock        | Z370 Pro4                   | [ced8851dc3](https://linux-hardware.org/?probe=ced8851dc3) | Nov 23, 2022 |
| Gigabyte      | B660M DS3H DDR4             | [4956957df8](https://linux-hardware.org/?probe=4956957df8) | Nov 19, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [14318910c1](https://linux-hardware.org/?probe=14318910c1) | Nov 18, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [c4bf12a3e5](https://linux-hardware.org/?probe=c4bf12a3e5) | Nov 18, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [4ba72d9f3b](https://linux-hardware.org/?probe=4ba72d9f3b) | Nov 16, 2022 |
| MSI           | Z590 PRO WIFI               | [c53f301391](https://linux-hardware.org/?probe=c53f301391) | Nov 16, 2022 |
| HP            | 83EE                        | [182682b17c](https://linux-hardware.org/?probe=182682b17c) | Nov 16, 2022 |
| HP            | 83EE                        | [65d7bade6e](https://linux-hardware.org/?probe=65d7bade6e) | Nov 16, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [07a9b0efe0](https://linux-hardware.org/?probe=07a9b0efe0) | Nov 10, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [8ee7171b61](https://linux-hardware.org/?probe=8ee7171b61) | Nov 03, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | [573a028791](https://linux-hardware.org/?probe=573a028791) | Nov 03, 2022 |
| Dell          | 0WMJ54 A01                  | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | [1627ad94ef](https://linux-hardware.org/?probe=1627ad94ef) | Oct 27, 2022 |
| ASUSTek       | PRO H410M-C                 | [00e64f6075](https://linux-hardware.org/?probe=00e64f6075) | Oct 25, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [daa76e4b78](https://linux-hardware.org/?probe=daa76e4b78) | Oct 25, 2022 |
| ASRock        | Z370 Pro4                   | [cd2e9dd7af](https://linux-hardware.org/?probe=cd2e9dd7af) | Oct 23, 2022 |
| ASRock        | Z370 Pro4                   | [5962a98f24](https://linux-hardware.org/?probe=5962a98f24) | Oct 23, 2022 |
| HP            | 18E7                        | [db33d9c2c2](https://linux-hardware.org/?probe=db33d9c2c2) | Oct 18, 2022 |
| ASUSTek       | PRIME B365M-K               | [5fb0a15135](https://linux-hardware.org/?probe=5fb0a15135) | Oct 18, 2022 |
| ASRock        | X300-ITX                    | [a391ce99bf](https://linux-hardware.org/?probe=a391ce99bf) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| HP            | 2AF7                        | [e5cd1d0cce](https://linux-hardware.org/?probe=e5cd1d0cce) | Oct 15, 2022 |
| ASUSTek       | PRO H410M-C                 | [13581dc0a2](https://linux-hardware.org/?probe=13581dc0a2) | Oct 13, 2022 |
| Dell          | 0Y2MRG A00                  | [2e8206e823](https://linux-hardware.org/?probe=2e8206e823) | Oct 12, 2022 |
| Dell          | 0Y2MRG A00                  | [5eab8a8351](https://linux-hardware.org/?probe=5eab8a8351) | Oct 12, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [55bb52409c](https://linux-hardware.org/?probe=55bb52409c) | Oct 12, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [dd3d3724d6](https://linux-hardware.org/?probe=dd3d3724d6) | Oct 10, 2022 |
| ASUSTek       | F2A85-M PRO                 | [571cb4bb05](https://linux-hardware.org/?probe=571cb4bb05) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [82b73270ca](https://linux-hardware.org/?probe=82b73270ca) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [a1f261d09d](https://linux-hardware.org/?probe=a1f261d09d) | Sep 25, 2022 |
| MSI           | X470 GAMING PLUS            | [efe1609ac0](https://linux-hardware.org/?probe=efe1609ac0) | Sep 24, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [11ea16f0d6](https://linux-hardware.org/?probe=11ea16f0d6) | Sep 22, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [b48eda0e37](https://linux-hardware.org/?probe=b48eda0e37) | Sep 18, 2022 |
| Gigabyte      | G31M-ES2L                   | [e074efb108](https://linux-hardware.org/?probe=e074efb108) | Sep 18, 2022 |
| Gigabyte      | G31M-ES2L                   | [4b8841b706](https://linux-hardware.org/?probe=4b8841b706) | Sep 18, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [e633838a51](https://linux-hardware.org/?probe=e633838a51) | Sep 15, 2022 |
| Gigabyte      | Z77X-UP7                    | [3bdc70035e](https://linux-hardware.org/?probe=3bdc70035e) | Sep 11, 2022 |
| ASRock        | H370 Pro4                   | [f6b34cb2b6](https://linux-hardware.org/?probe=f6b34cb2b6) | Sep 10, 2022 |
| ASRock        | B450 Pro4                   | [4d5b865aed](https://linux-hardware.org/?probe=4d5b865aed) | Sep 05, 2022 |
| Intel         | D34010WYB H14771-304        | [47d9609ba8](https://linux-hardware.org/?probe=47d9609ba8) | Sep 01, 2022 |
| Intel         | D34010WYB H14771-304        | [fd34481bf8](https://linux-hardware.org/?probe=fd34481bf8) | Sep 01, 2022 |
| HP            | 18E7                        | [613d55d0e9](https://linux-hardware.org/?probe=613d55d0e9) | Aug 27, 2022 |
| Biostar       | B660MX-E                    | [4fa9d132c2](https://linux-hardware.org/?probe=4fa9d132c2) | Aug 26, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [05a337504b](https://linux-hardware.org/?probe=05a337504b) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| ASRock        | B660-ITX                    | [316ae22af8](https://linux-hardware.org/?probe=316ae22af8) | Aug 24, 2022 |
| ASUSTek       | P7H55-M                     | [7596762e80](https://linux-hardware.org/?probe=7596762e80) | Aug 17, 2022 |
| ASUSTek       | P7H55-M                     | [bbcdb246aa](https://linux-hardware.org/?probe=bbcdb246aa) | Aug 16, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [79b28d4c5f](https://linux-hardware.org/?probe=79b28d4c5f) | Aug 16, 2022 |
| ASUSTek       | P7H55-M                     | [5106d4eda8](https://linux-hardware.org/?probe=5106d4eda8) | Aug 15, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [e59ee250ad](https://linux-hardware.org/?probe=e59ee250ad) | Aug 13, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [4ec9a5896d](https://linux-hardware.org/?probe=4ec9a5896d) | Aug 12, 2022 |
| ASRock        | B450 Pro4                   | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Gigabyte      | EP45-UD3R                   | [6c434341ce](https://linux-hardware.org/?probe=6c434341ce) | Aug 07, 2022 |
| Gigabyte      | Z170X-UD3-CF                | [450fee0496](https://linux-hardware.org/?probe=450fee0496) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [6b790e8a9b](https://linux-hardware.org/?probe=6b790e8a9b) | Aug 02, 2022 |
| MSI           | MEG X570 UNIFY              | [9be9a3e83b](https://linux-hardware.org/?probe=9be9a3e83b) | Aug 01, 2022 |
| ASUSTek       | M4N78                       | [870702db59](https://linux-hardware.org/?probe=870702db59) | Jul 29, 2022 |
| ASRock        | A88M-ITX/ac                 | [e339941033](https://linux-hardware.org/?probe=e339941033) | Jul 27, 2022 |
| ASRock        | FM2A88X-ITX+                | [24e0844619](https://linux-hardware.org/?probe=24e0844619) | Jul 27, 2022 |
| ASRock        | H470M Pro4                  | [5a709f059c](https://linux-hardware.org/?probe=5a709f059c) | Jul 25, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [b63e85ff7e](https://linux-hardware.org/?probe=b63e85ff7e) | Jul 25, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | [36edefbce1](https://linux-hardware.org/?probe=36edefbce1) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [de6f28d0f7](https://linux-hardware.org/?probe=de6f28d0f7) | Jul 24, 2022 |
| ASRock        | J5005-ITX                   | [8fdd045c35](https://linux-hardware.org/?probe=8fdd045c35) | Jul 24, 2022 |
| ASUSTek       | PRIME Z390-A                | [9a3ffce1a4](https://linux-hardware.org/?probe=9a3ffce1a4) | Jul 24, 2022 |
| GALAX         | H310M-A V2                  | [db46aaa3aa](https://linux-hardware.org/?probe=db46aaa3aa) | Jul 24, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [a09d9de883](https://linux-hardware.org/?probe=a09d9de883) | Jul 23, 2022 |
| Gigabyte      | Z390 DESIGNARE-CF           | [a81e48e206](https://linux-hardware.org/?probe=a81e48e206) | Jul 15, 2022 |
| ASRock        | AMCP7A-ION                  | [339f0e7944](https://linux-hardware.org/?probe=339f0e7944) | Jul 10, 2022 |
| ASRock        | A300M-STX                   | [8cf2a64c6b](https://linux-hardware.org/?probe=8cf2a64c6b) | Jul 10, 2022 |
| HP            | 158A                        | [e1bec79951](https://linux-hardware.org/?probe=e1bec79951) | Jul 10, 2022 |
| MSI           | A520M-A PRO                 | [85fe785be5](https://linux-hardware.org/?probe=85fe785be5) | Jul 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [85dbd84c37](https://linux-hardware.org/?probe=85dbd84c37) | Jul 09, 2022 |
| ASRock        | X399 Taichi                 | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| ASUSTek       | PRO H410M-C                 | [9f705aea75](https://linux-hardware.org/?probe=9f705aea75) | Jun 29, 2022 |
| MSI           | Creator X299                | [279caedd2f](https://linux-hardware.org/?probe=279caedd2f) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b841edf2b7](https://linux-hardware.org/?probe=b841edf2b7) | Jun 19, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| ASUSTek       | X99-A                       | [2f722cf462](https://linux-hardware.org/?probe=2f722cf462) | Jun 17, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| Intel         | DB75EN AAG39650-400         | [5fa7614020](https://linux-hardware.org/?probe=5fa7614020) | Jun 12, 2022 |
| Gigabyte      | GA-MA69GM-S2H               | [a382b54934](https://linux-hardware.org/?probe=a382b54934) | Jun 11, 2022 |
| MSI           | H510I PRO WIFI              | [7cb5b3fd8a](https://linux-hardware.org/?probe=7cb5b3fd8a) | Jun 06, 2022 |
| ASUSTek       | PRIME B365M-K               | [0cf459f0db](https://linux-hardware.org/?probe=0cf459f0db) | Jun 06, 2022 |
| ASRock        | A520M-HDV                   | [a8ade4e46f](https://linux-hardware.org/?probe=a8ade4e46f) | Jun 06, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [0d24b53837](https://linux-hardware.org/?probe=0d24b53837) | Jun 02, 2022 |
| ASUSTek       | P5Q SE                      | [386a88c2b6](https://linux-hardware.org/?probe=386a88c2b6) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | [5a51cc8767](https://linux-hardware.org/?probe=5a51cc8767) | May 30, 2022 |
| ASUSTek       | VM60                        | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [ca67455f28](https://linux-hardware.org/?probe=ca67455f28) | May 29, 2022 |
| MSI           | H510I PRO WIFI              | [b4b8c3db64](https://linux-hardware.org/?probe=b4b8c3db64) | May 29, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0cf6ee749e](https://linux-hardware.org/?probe=0cf6ee749e) | May 27, 2022 |
| Gigabyte      | Z77X-UP7                    | [8b4b27f72d](https://linux-hardware.org/?probe=8b4b27f72d) | May 20, 2022 |
| MouseCompu... | B360M-ITX                   | [bee48ca0b0](https://linux-hardware.org/?probe=bee48ca0b0) | May 18, 2022 |
| HP            | 158A                        | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| ASUSTek       | PRO H410M-C                 | [1b0cb5afca](https://linux-hardware.org/?probe=1b0cb5afca) | May 16, 2022 |
| Unknown       | MSL01 Series                | [1c66319969](https://linux-hardware.org/?probe=1c66319969) | May 11, 2022 |
| MouseCompu... | X99-S01                     | [69ac1048e9](https://linux-hardware.org/?probe=69ac1048e9) | May 11, 2022 |
| Gigabyte      | G31M-S2L                    | [78b1868a67](https://linux-hardware.org/?probe=78b1868a67) | May 08, 2022 |
| ASUSTek       | PRIME B365M-A               | [a281b3c075](https://linux-hardware.org/?probe=a281b3c075) | May 07, 2022 |
| ASRock        | QC5000-ITX/WiFi             | [ec48bca283](https://linux-hardware.org/?probe=ec48bca283) | May 05, 2022 |
| HP            | 158A                        | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [5498c8b84f](https://linux-hardware.org/?probe=5498c8b84f) | May 01, 2022 |
| Gigabyte      | Z77X-UD3H                   | [f30bbca593](https://linux-hardware.org/?probe=f30bbca593) | May 01, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| ASUSTek       | P8Z77-V                     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Gigabyte      | Z77X-UD3H                   | [b07e1c97aa](https://linux-hardware.org/?probe=b07e1c97aa) | Apr 29, 2022 |
| MSI           | H510I PRO WIFI              | [5e6c23c3b5](https://linux-hardware.org/?probe=5e6c23c3b5) | Apr 28, 2022 |
| MSI           | H510I PRO WIFI              | [f6df392394](https://linux-hardware.org/?probe=f6df392394) | Apr 27, 2022 |
| Dell          | 0NW73C A01                  | [430f7b0e3a](https://linux-hardware.org/?probe=430f7b0e3a) | Apr 23, 2022 |
| ASRock        | P5B-DE                      | [b9b6d17274](https://linux-hardware.org/?probe=b9b6d17274) | Apr 23, 2022 |
| Dell          | 0KV62T A01                  | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0ad6471ecf](https://linux-hardware.org/?probe=0ad6471ecf) | Apr 16, 2022 |
| Gigabyte      | EP45-UD3P                   | [973d2cc2f1](https://linux-hardware.org/?probe=973d2cc2f1) | Apr 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3fade276ac](https://linux-hardware.org/?probe=3fade276ac) | Apr 13, 2022 |
| MSI           | H170A PC MATE               | [404f32fc8a](https://linux-hardware.org/?probe=404f32fc8a) | Apr 11, 2022 |
| MSI           | B350I PRO AC                | [8065d41c05](https://linux-hardware.org/?probe=8065d41c05) | Apr 10, 2022 |
| ASUSTek       | H170 PRO GAMING             | [88d231a24a](https://linux-hardware.org/?probe=88d231a24a) | Apr 08, 2022 |
| Gigabyte      | AX370-Gaming K7             | [2759f18a1f](https://linux-hardware.org/?probe=2759f18a1f) | Apr 04, 2022 |
| ASUSTek       | H170 PRO GAMING             | [f7bc6dd5a3](https://linux-hardware.org/?probe=f7bc6dd5a3) | Apr 03, 2022 |
| ASUSTek       | PB50                        | [32ab9e7da2](https://linux-hardware.org/?probe=32ab9e7da2) | Apr 02, 2022 |
| Gigabyte      | AX370-Gaming K7             | [20aac26c6d](https://linux-hardware.org/?probe=20aac26c6d) | Mar 31, 2022 |
| ASRock        | FM2A88X-ITX+                | [edf21d564c](https://linux-hardware.org/?probe=edf21d564c) | Mar 30, 2022 |
| MouseCompu... | B85H3-M4/2.0                | [3b58b2a122](https://linux-hardware.org/?probe=3b58b2a122) | Mar 30, 2022 |
| Gigabyte      | E350N WIN8                  | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| ASRock        | FM2A88X-ITX+                | [dc35b742d2](https://linux-hardware.org/?probe=dc35b742d2) | Mar 26, 2022 |
| MSI           | B350I PRO AC                | [9d5ead8832](https://linux-hardware.org/?probe=9d5ead8832) | Mar 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | [5c3993ef06](https://linux-hardware.org/?probe=5c3993ef06) | Mar 14, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [b170ce8fbe](https://linux-hardware.org/?probe=b170ce8fbe) | Mar 11, 2022 |
| ASUSTek       | M4A87TD/USB3                | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| HP            | 18E7                        | [07d0861eff](https://linux-hardware.org/?probe=07d0861eff) | Feb 28, 2022 |
| ASRock        | H77M                        | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [9483d7b48e](https://linux-hardware.org/?probe=9483d7b48e) | Feb 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2c1109afb8](https://linux-hardware.org/?probe=2c1109afb8) | Feb 21, 2022 |
| ASRock        | AB350M-HDV                  | [4675d06ffb](https://linux-hardware.org/?probe=4675d06ffb) | Feb 19, 2022 |
| NEC Comput... | IH81M                       | [5e60991665](https://linux-hardware.org/?probe=5e60991665) | Feb 18, 2022 |
| Unknown       | Unknown                     | [15ae5870b9](https://linux-hardware.org/?probe=15ae5870b9) | Feb 16, 2022 |
| Unknown       | Unknown                     | [e55e0df499](https://linux-hardware.org/?probe=e55e0df499) | Feb 16, 2022 |
| ASUSTek       | M4A87TD/USB3                | [041b4e9976](https://linux-hardware.org/?probe=041b4e9976) | Feb 16, 2022 |
| ASUSTek       | P7H55-M                     | [b2414fb6fc](https://linux-hardware.org/?probe=b2414fb6fc) | Feb 15, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [efcb060233](https://linux-hardware.org/?probe=efcb060233) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [1ee503a497](https://linux-hardware.org/?probe=1ee503a497) | Feb 13, 2022 |
| MSI           | X570-A PRO                  | [976cefe591](https://linux-hardware.org/?probe=976cefe591) | Feb 13, 2022 |
| ASRock        | A320M-HDV R4.0              | [a5d02d3a03](https://linux-hardware.org/?probe=a5d02d3a03) | Feb 13, 2022 |
| MouseCompu... | B75H2-M2                    | [f0199da02b](https://linux-hardware.org/?probe=f0199da02b) | Feb 11, 2022 |
| ASUSTek       | M4A87TD/USB3                | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| ASUSTek       | P5Q                         | [bc3f44c0b9](https://linux-hardware.org/?probe=bc3f44c0b9) | Feb 10, 2022 |
| ASRock        | B550M Steel Legend          | [0c54ad1557](https://linux-hardware.org/?probe=0c54ad1557) | Feb 10, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [218f370835](https://linux-hardware.org/?probe=218f370835) | Feb 10, 2022 |
| ASRock        | H55DE3                      | [7d4fb5775f](https://linux-hardware.org/?probe=7d4fb5775f) | Feb 09, 2022 |
| ASRock        | B250M-HDV                   | [fcaddfe60e](https://linux-hardware.org/?probe=fcaddfe60e) | Feb 09, 2022 |
| MCJ           | H67H2-M4                    | [3814208f36](https://linux-hardware.org/?probe=3814208f36) | Feb 08, 2022 |
| MSI           | H510I PRO WIFI              | [b9c77d9df2](https://linux-hardware.org/?probe=b9c77d9df2) | Feb 08, 2022 |
| Dell          | 04YP6J A01                  | [61cc7bdcc2](https://linux-hardware.org/?probe=61cc7bdcc2) | Feb 06, 2022 |
| HP            | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| ASUSTek       | P8Z77-M                     | [cb5f618a4b](https://linux-hardware.org/?probe=cb5f618a4b) | Jan 31, 2022 |
| ASUSTek       | P8Z77-M                     | [0c1b8480b6](https://linux-hardware.org/?probe=0c1b8480b6) | Jan 31, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| HP            | 3048h                       | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| ASRock        | B450M Pro4                  | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| Gigabyte      | H81M-S                      | [9418716c6b](https://linux-hardware.org/?probe=9418716c6b) | Jan 14, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [57fe150494](https://linux-hardware.org/?probe=57fe150494) | Jan 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| MSI           | H510I PRO WIFI              | [efc8b1b1ff](https://linux-hardware.org/?probe=efc8b1b1ff) | Jan 13, 2022 |
| ASUSTek       | N3150I-C                    | [ae91e3cc7b](https://linux-hardware.org/?probe=ae91e3cc7b) | Jan 13, 2022 |
| Gigabyte      | GA-970A-D3                  | [7539f3648f](https://linux-hardware.org/?probe=7539f3648f) | Jan 09, 2022 |
| ASUSTek       | P8H61-I                     | [261ea10bf8](https://linux-hardware.org/?probe=261ea10bf8) | Jan 08, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | [b56f576ff8](https://linux-hardware.org/?probe=b56f576ff8) | Jan 05, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | [36da2e6d4e](https://linux-hardware.org/?probe=36da2e6d4e) | Dec 26, 2021 |
| HP            | 83EE                        | [225f3c4b8d](https://linux-hardware.org/?probe=225f3c4b8d) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [526e490544](https://linux-hardware.org/?probe=526e490544) | Dec 17, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [7d976b30fc](https://linux-hardware.org/?probe=7d976b30fc) | Dec 17, 2021 |
| ASRock        | B550 TW                     | [83c53ad524](https://linux-hardware.org/?probe=83c53ad524) | Dec 17, 2021 |
| HP            | 8054                        | [454fd4c8c7](https://linux-hardware.org/?probe=454fd4c8c7) | Dec 13, 2021 |
| ASUSTek       | P5Q                         | [dac259cc34](https://linux-hardware.org/?probe=dac259cc34) | Dec 13, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [3e6b2c12f8](https://linux-hardware.org/?probe=3e6b2c12f8) | Dec 05, 2021 |
| MSI           | X470 GAMING PLUS            | [289027e0cf](https://linux-hardware.org/?probe=289027e0cf) | Nov 26, 2021 |
| MSI           | H510I PRO WIFI              | [1abf510439](https://linux-hardware.org/?probe=1abf510439) | Nov 24, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [2879c07a24](https://linux-hardware.org/?probe=2879c07a24) | Nov 23, 2021 |
| ASUSTek       | P8H61-I                     | [bb8c25b299](https://linux-hardware.org/?probe=bb8c25b299) | Nov 20, 2021 |
| MouseCompu... | B75M-D3V-JP                 | [161d355bcc](https://linux-hardware.org/?probe=161d355bcc) | Nov 18, 2021 |
| MouseCompu... | B360M                       | [cab585062a](https://linux-hardware.org/?probe=cab585062a) | Nov 13, 2021 |
| ASUSTek       | H97-PRO                     | [99f09523d8](https://linux-hardware.org/?probe=99f09523d8) | Nov 12, 2021 |
| ASUSTek       | H170-PRO                    | [f3a3f86928](https://linux-hardware.org/?probe=f3a3f86928) | Nov 12, 2021 |
| HP            | 3047h                       | [192742e5a6](https://linux-hardware.org/?probe=192742e5a6) | Nov 12, 2021 |
| ASUSTek       | Z170-A                      | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| HP            | 3047h                       | [935aac64ef](https://linux-hardware.org/?probe=935aac64ef) | Nov 11, 2021 |
| ASRock        | X570 Taichi Razer Editio... | [982fbc9995](https://linux-hardware.org/?probe=982fbc9995) | Nov 10, 2021 |
| MouseCompu... | Z490M-S01                   | [bd810f8122](https://linux-hardware.org/?probe=bd810f8122) | Nov 10, 2021 |
| Gigabyte      | B85M-HD3                    | [80a8e89f7e](https://linux-hardware.org/?probe=80a8e89f7e) | Nov 06, 2021 |
| Gigabyte      | B85M-HD3                    | [834bf06329](https://linux-hardware.org/?probe=834bf06329) | Nov 03, 2021 |
| Dell          | 0P301D A02                  | [26462404f4](https://linux-hardware.org/?probe=26462404f4) | Oct 30, 2021 |
| HP            | 3047h                       | [afa4f5c1d0](https://linux-hardware.org/?probe=afa4f5c1d0) | Oct 28, 2021 |
| HP            | 3047h                       | [d5e5504f54](https://linux-hardware.org/?probe=d5e5504f54) | Oct 28, 2021 |
| ASRock        | Z370 Pro4                   | [a0bf764d45](https://linux-hardware.org/?probe=a0bf764d45) | Oct 25, 2021 |
| Lenovo        | 36E7 SDK0R32862 WIN 3258... | [1d14b9b944](https://linux-hardware.org/?probe=1d14b9b944) | Oct 24, 2021 |
| Gigabyte      | H87N-WIFI                   | [fb7beb9612](https://linux-hardware.org/?probe=fb7beb9612) | Oct 20, 2021 |
| EPSON DIRE... | ST170E                      | [dfa0ed56ab](https://linux-hardware.org/?probe=dfa0ed56ab) | Oct 18, 2021 |
| Lenovo        | 36E7 SDK0R32862 WIN 3258... | [4efe80812c](https://linux-hardware.org/?probe=4efe80812c) | Oct 16, 2021 |
| ASRock        | B450M Pro4                  | [5ed3b7e62d](https://linux-hardware.org/?probe=5ed3b7e62d) | Oct 13, 2021 |
| ASRock        | H67DE                       | [491ac17e42](https://linux-hardware.org/?probe=491ac17e42) | Oct 10, 2021 |
| ASRock        | FM2A88X-ITX+                | [f6a1aece80](https://linux-hardware.org/?probe=f6a1aece80) | Oct 10, 2021 |
| Gigabyte      | Z77X-UD5H                   | [e1543ea8f8](https://linux-hardware.org/?probe=e1543ea8f8) | Oct 09, 2021 |
| ASUSTek       | M51AC                       | [0d9722a373](https://linux-hardware.org/?probe=0d9722a373) | Oct 05, 2021 |
| ASUSTek       | B85M-G                      | [0d05812341](https://linux-hardware.org/?probe=0d05812341) | Oct 02, 2021 |
| Gigabyte      | GA-MA69GM-S2H               | [b1f14324be](https://linux-hardware.org/?probe=b1f14324be) | Sep 29, 2021 |
| ASRock        | H67DE                       | [296abe4896](https://linux-hardware.org/?probe=296abe4896) | Sep 28, 2021 |
| ASRock        | H67DE                       | [e663e151d6](https://linux-hardware.org/?probe=e663e151d6) | Sep 28, 2021 |
| MSI           | B450I GAMING PLUS AC        | [8b3dfbb8a4](https://linux-hardware.org/?probe=8b3dfbb8a4) | Sep 25, 2021 |
| Gigabyte      | Z77X-UD5H                   | [b613f0c8a9](https://linux-hardware.org/?probe=b613f0c8a9) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [2f9b27ad89](https://linux-hardware.org/?probe=2f9b27ad89) | Sep 16, 2021 |
| Gigabyte      | B75M-D2P                    | [617e5dd237](https://linux-hardware.org/?probe=617e5dd237) | Sep 08, 2021 |
| EPSON DIRE... | ST150E                      | [22d7fff01c](https://linux-hardware.org/?probe=22d7fff01c) | Aug 27, 2021 |
| EPSON DIRE... | ST150E                      | [5736465e27](https://linux-hardware.org/?probe=5736465e27) | Aug 27, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [f26ade88cd](https://linux-hardware.org/?probe=f26ade88cd) | Aug 26, 2021 |
| Biostar       | Hi-Fi A85W                  | [ffb66dafd4](https://linux-hardware.org/?probe=ffb66dafd4) | Aug 25, 2021 |
| EPSON DIRE... | ST150E                      | [797ec7ec81](https://linux-hardware.org/?probe=797ec7ec81) | Aug 24, 2021 |
| ASRock        | B450 Steel Legend           | [8fdfffdbac](https://linux-hardware.org/?probe=8fdfffdbac) | Aug 20, 2021 |
| ASRock        | B550M Steel Legend          | [68496a4cb7](https://linux-hardware.org/?probe=68496a4cb7) | Aug 18, 2021 |
| ASRock        | N3150M                      | [932c7baf1a](https://linux-hardware.org/?probe=932c7baf1a) | Aug 17, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| MSI           | Z170A GAMING PRO CARBON     | [ab538f5af7](https://linux-hardware.org/?probe=ab538f5af7) | Aug 15, 2021 |
| ASUSTek       | SABERTOOTH X79              | [5d6732e14c](https://linux-hardware.org/?probe=5d6732e14c) | Aug 09, 2021 |
| ASRock        | Z370 Pro4                   | [5b7a8411f5](https://linux-hardware.org/?probe=5b7a8411f5) | Aug 09, 2021 |
| Intel         | D945GNT AAC96315-402        | [a2d256eee3](https://linux-hardware.org/?probe=a2d256eee3) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [2f7d7bbb1d](https://linux-hardware.org/?probe=2f7d7bbb1d) | Aug 06, 2021 |
| NEC Comput... | MS-7770HH                   | [7ca677a33c](https://linux-hardware.org/?probe=7ca677a33c) | Aug 03, 2021 |
| Gigabyte      | B450M S2H                   | [0401734340](https://linux-hardware.org/?probe=0401734340) | Jul 31, 2021 |
| ASRock        | B550M Steel Legend          | [1e02007526](https://linux-hardware.org/?probe=1e02007526) | Jul 30, 2021 |
| MSI           | H510I PRO WIFI              | [e896a37f1d](https://linux-hardware.org/?probe=e896a37f1d) | Jul 29, 2021 |
| ASRock        | A300M-STX                   | [161a673775](https://linux-hardware.org/?probe=161a673775) | Jul 28, 2021 |
| ASRock        | A300M-STX                   | [264959862d](https://linux-hardware.org/?probe=264959862d) | Jul 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c824226d1e](https://linux-hardware.org/?probe=c824226d1e) | Jul 26, 2021 |
| HP            | 18E7                        | [c0cddf4243](https://linux-hardware.org/?probe=c0cddf4243) | Jul 23, 2021 |
| Unknown       | XH61X000.100                | [6604251e58](https://linux-hardware.org/?probe=6604251e58) | Jul 23, 2021 |
| ASRock        | FM2A88X-ITX+                | [93a813bbba](https://linux-hardware.org/?probe=93a813bbba) | Jul 22, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | [b7a612e4ec](https://linux-hardware.org/?probe=b7a612e4ec) | Jul 20, 2021 |
| HP            | 1906                        | [6cd7c6ec7f](https://linux-hardware.org/?probe=6cd7c6ec7f) | Jul 20, 2021 |
| ASRock        | 880GM-LE                    | [4808dde963](https://linux-hardware.org/?probe=4808dde963) | Jul 18, 2021 |
| ASRock        | X300M-STX                   | [3a35cafb7f](https://linux-hardware.org/?probe=3a35cafb7f) | Jul 17, 2021 |
| HP            | 18E7                        | [03d84525e8](https://linux-hardware.org/?probe=03d84525e8) | Jul 13, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [d6410ac1a0](https://linux-hardware.org/?probe=d6410ac1a0) | Jul 11, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [1b63a19bd1](https://linux-hardware.org/?probe=1b63a19bd1) | Jul 08, 2021 |
| ASRock        | Z370 Pro4                   | [673b1c670f](https://linux-hardware.org/?probe=673b1c670f) | Jul 08, 2021 |
| ASRock        | Z370 Pro4                   | [14789c0301](https://linux-hardware.org/?probe=14789c0301) | Jul 07, 2021 |
| Gigabyte      | GA-990FXA-UD3               | [cb030b0e9f](https://linux-hardware.org/?probe=cb030b0e9f) | Jul 04, 2021 |
| Intel         | DZ77BH-55K AAG39008-400     | [04692a4293](https://linux-hardware.org/?probe=04692a4293) | Jul 02, 2021 |
| HP            | 1906                        | [95bfd2283b](https://linux-hardware.org/?probe=95bfd2283b) | Jun 29, 2021 |
| Lenovo        | ThinkCentre M57 6062A25     | [e5a404d35c](https://linux-hardware.org/?probe=e5a404d35c) | Jun 29, 2021 |
| ASUSTek       | PRIME H570-PLUS             | [be23e213b9](https://linux-hardware.org/?probe=be23e213b9) | Jun 26, 2021 |
| ASRock        | Z390 Pro4                   | [6c86be2586](https://linux-hardware.org/?probe=6c86be2586) | Jun 24, 2021 |
| MSI           | H510I PRO WIFI              | [06e8d9bce7](https://linux-hardware.org/?probe=06e8d9bce7) | Jun 23, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [c2285d9014](https://linux-hardware.org/?probe=c2285d9014) | Jun 22, 2021 |
| ASRock        | X470 Master SLI             | [76096c0075](https://linux-hardware.org/?probe=76096c0075) | Jun 19, 2021 |
| MSI           | H510I PRO WIFI              | [b2c184af4f](https://linux-hardware.org/?probe=b2c184af4f) | Jun 18, 2021 |
| ASRock        | X470 Master SLI             | [03b329894a](https://linux-hardware.org/?probe=03b329894a) | Jun 18, 2021 |
| ASRock        | X570 Steel Legend           | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI           | MEG X570 GODLIKE            | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| ASUSTek       | M4A87TD/USB3                | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| ASUSTek       | Z170M-PLUS                  | [4c0e4ebaa4](https://linux-hardware.org/?probe=4c0e4ebaa4) | Jun 16, 2021 |
| ASUSTek       | PRIME Z370-A                | [0b50c157fe](https://linux-hardware.org/?probe=0b50c157fe) | Jun 14, 2021 |
| ASRock        | X300M-STX                   | [fd6970af13](https://linux-hardware.org/?probe=fd6970af13) | Jun 12, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [1fe01a8a37](https://linux-hardware.org/?probe=1fe01a8a37) | Jun 05, 2021 |
| ECS           | G41T-M2                     | [3005be6650](https://linux-hardware.org/?probe=3005be6650) | Jun 04, 2021 |
| Biostar       | B350GTN                     | [6ba7f458da](https://linux-hardware.org/?probe=6ba7f458da) | Jun 01, 2021 |
| Intel         | D945GNT AAC96315-402        | [36fb4e2aba](https://linux-hardware.org/?probe=36fb4e2aba) | May 29, 2021 |
| ASRock        | FM2A88X-ITX+                | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| ASUSTek       | PRIME X299-A                | [d5cdc97c3b](https://linux-hardware.org/?probe=d5cdc97c3b) | May 13, 2021 |
| Gigabyte      | EP45-UD3R                   | [25abeee3ef](https://linux-hardware.org/?probe=25abeee3ef) | May 12, 2021 |
| Gigabyte      | EG41MF-US2H                 | [f416a7a6b3](https://linux-hardware.org/?probe=f416a7a6b3) | May 09, 2021 |
| Gigabyte      | B75M-D3H                    | [aa1f42a8a9](https://linux-hardware.org/?probe=aa1f42a8a9) | May 08, 2021 |
| ASRock        | H310CM-HDV/M.2              | [af0ec6cab7](https://linux-hardware.org/?probe=af0ec6cab7) | May 04, 2021 |
| HP            | 3047h                       | [3de6f89fae](https://linux-hardware.org/?probe=3de6f89fae) | May 02, 2021 |
| ASRock        | FM2A88X-ITX+                | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| ASRock        | X300M-STX                   | [0f15e44442](https://linux-hardware.org/?probe=0f15e44442) | Apr 26, 2021 |
| ASRock        | P5B-DE                      | [04084bd0ef](https://linux-hardware.org/?probe=04084bd0ef) | Apr 24, 2021 |
| ASUSTek       | N3150I-C                    | [4cfbe212a4](https://linux-hardware.org/?probe=4cfbe212a4) | Apr 22, 2021 |
| Gigabyte      | B75M-D3H                    | [af34567550](https://linux-hardware.org/?probe=af34567550) | Apr 17, 2021 |
| MSI           | MAG B550M MORTAR            | [b7991a35ba](https://linux-hardware.org/?probe=b7991a35ba) | Apr 16, 2021 |
| ASUSTek       | P5Q-EM                      | [a7ed7cc477](https://linux-hardware.org/?probe=a7ed7cc477) | Apr 14, 2021 |
| ASUSTek       | P4V800D-X                   | [c469d16946](https://linux-hardware.org/?probe=c469d16946) | Apr 09, 2021 |
| ASUSTek       | PRO H410M-C                 | [a5b2555cc2](https://linux-hardware.org/?probe=a5b2555cc2) | Apr 06, 2021 |
| ASRock        | AB350 Pro4                  | [ba17a463a7](https://linux-hardware.org/?probe=ba17a463a7) | Apr 03, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [a579757204](https://linux-hardware.org/?probe=a579757204) | Apr 03, 2021 |
| ASUSTek       | P7P55D-E                    | [52b2fb4ebb](https://linux-hardware.org/?probe=52b2fb4ebb) | Mar 22, 2021 |
| ASRock        | X300M-STX                   | [d5722fd82b](https://linux-hardware.org/?probe=d5722fd82b) | Mar 22, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [e5ce81269b](https://linux-hardware.org/?probe=e5ce81269b) | Mar 22, 2021 |
| ASRock        | X370 Pro4                   | [6c6d145ad3](https://linux-hardware.org/?probe=6c6d145ad3) | Mar 20, 2021 |
| ASRock        | FM2A88X+ Killer             | [64164ccce2](https://linux-hardware.org/?probe=64164ccce2) | Mar 19, 2021 |
| ASRock        | X300M-STX                   | [b36b41329b](https://linux-hardware.org/?probe=b36b41329b) | Mar 14, 2021 |
| ASUSTek       | P7H55-M                     | [cff1baf251](https://linux-hardware.org/?probe=cff1baf251) | Mar 14, 2021 |
| ASRock        | FM2A88X-ITX+                | [7a38886add](https://linux-hardware.org/?probe=7a38886add) | Mar 14, 2021 |
| HP            | 212B                        | [6afcf12073](https://linux-hardware.org/?probe=6afcf12073) | Mar 12, 2021 |
| Biostar       | Hi-Fi A88ZN                 | [72cff94e15](https://linux-hardware.org/?probe=72cff94e15) | Mar 12, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [bca1731a58](https://linux-hardware.org/?probe=bca1731a58) | Mar 08, 2021 |
| HP            | 212B                        | [acee068006](https://linux-hardware.org/?probe=acee068006) | Mar 06, 2021 |
| MSI           | C236A WORKSTATION           | [dc9e6c2670](https://linux-hardware.org/?probe=dc9e6c2670) | Mar 03, 2021 |
| MSI           | MEG X570 GODLIKE            | [3d2e576c95](https://linux-hardware.org/?probe=3d2e576c95) | Mar 03, 2021 |
| MSI           | B450I GAMING PLUS AC        | [aa41662477](https://linux-hardware.org/?probe=aa41662477) | Mar 02, 2021 |
| ASUSTek       | M3A78-EM                    | [c08f9a30dc](https://linux-hardware.org/?probe=c08f9a30dc) | Feb 28, 2021 |
| ASUSTek       | Rampage IV GENE             | [16cf45ce16](https://linux-hardware.org/?probe=16cf45ce16) | Feb 28, 2021 |
| Dell          | 0T1D10 A01                  | [3577c78a56](https://linux-hardware.org/?probe=3577c78a56) | Feb 27, 2021 |
| Gigabyte      | H110M-S2PH-CF               | [501d2317f9](https://linux-hardware.org/?probe=501d2317f9) | Feb 26, 2021 |
| ASUSTek       | PRIME X570-P                | [7e4e426453](https://linux-hardware.org/?probe=7e4e426453) | Feb 22, 2021 |
| Biostar       | B450GT3                     | [18e0346ed0](https://linux-hardware.org/?probe=18e0346ed0) | Feb 22, 2021 |
| MSI           | C236A WORKSTATION           | [9e2effbe63](https://linux-hardware.org/?probe=9e2effbe63) | Feb 22, 2021 |
| ASRock        | A300M-STX                   | [5c5b3ce155](https://linux-hardware.org/?probe=5c5b3ce155) | Feb 19, 2021 |
| MSI           | A78M-E35 V2                 | [173e28a6b2](https://linux-hardware.org/?probe=173e28a6b2) | Feb 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a2e399875d](https://linux-hardware.org/?probe=a2e399875d) | Feb 15, 2021 |
| ASRock        | A300M-STX                   | [c364bd22bf](https://linux-hardware.org/?probe=c364bd22bf) | Feb 14, 2021 |
| Biostar       | X470NH                      | [b4ae665275](https://linux-hardware.org/?probe=b4ae665275) | Feb 13, 2021 |
| ASRock        | B75M R2.0                   | [6b1142fdaa](https://linux-hardware.org/?probe=6b1142fdaa) | Feb 13, 2021 |
| Gigabyte      | H67A-D3H-B3                 | [b384cb32dc](https://linux-hardware.org/?probe=b384cb32dc) | Feb 13, 2021 |
| MSI           | H270I GAMING PRO AC         | [dcae892f29](https://linux-hardware.org/?probe=dcae892f29) | Feb 13, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [168dfeabe8](https://linux-hardware.org/?probe=168dfeabe8) | Feb 08, 2021 |
| ASRock        | X570 Taichi Razer Editio... | [256969ebac](https://linux-hardware.org/?probe=256969ebac) | Feb 07, 2021 |
| ASRock        | A300M-STX                   | [ceda1f734f](https://linux-hardware.org/?probe=ceda1f734f) | Feb 04, 2021 |
| Biostar       | B450GT                      | [2cb5b97972](https://linux-hardware.org/?probe=2cb5b97972) | Feb 02, 2021 |
| ASRock        | B450 Pro4                   | [ebe6b1d494](https://linux-hardware.org/?probe=ebe6b1d494) | Feb 02, 2021 |
| Wistron       | J361Y                       | [347eb6b747](https://linux-hardware.org/?probe=347eb6b747) | Jan 31, 2021 |
| NEC Comput... | IS8XM                       | [5ef77bc965](https://linux-hardware.org/?probe=5ef77bc965) | Jan 25, 2021 |
| HP            | 0A54h                       | [9f8677d69a](https://linux-hardware.org/?probe=9f8677d69a) | Jan 23, 2021 |
| ASRock        | A300M-STX                   | [4f8794ed64](https://linux-hardware.org/?probe=4f8794ed64) | Jan 21, 2021 |
| HP            | 0A54h                       | [6b91501381](https://linux-hardware.org/?probe=6b91501381) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [4d2fb6eb87](https://linux-hardware.org/?probe=4d2fb6eb87) | Jan 19, 2021 |
| Acer          | Aspire XC-602 V1.0          | [f9111a7765](https://linux-hardware.org/?probe=f9111a7765) | Jan 16, 2021 |
| Gigabyte      | G33-DS3R                    | [490a799d8b](https://linux-hardware.org/?probe=490a799d8b) | Jan 13, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [c77878fdf4](https://linux-hardware.org/?probe=c77878fdf4) | Jan 12, 2021 |
| Gigabyte      | 970A-D3P                    | [5cea01c3c1](https://linux-hardware.org/?probe=5cea01c3c1) | Jan 12, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [3b66143d43](https://linux-hardware.org/?probe=3b66143d43) | Jan 11, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [293bb6fc26](https://linux-hardware.org/?probe=293bb6fc26) | Jan 10, 2021 |
| Dell          | 0R7935 A03                  | [1d936da792](https://linux-hardware.org/?probe=1d936da792) | Jan 09, 2021 |
| Acer          | Aspire XC-602 V1.0          | [0e8be5137f](https://linux-hardware.org/?probe=0e8be5137f) | Jan 08, 2021 |
| HP            | 158A                        | [0539eeeeb8](https://linux-hardware.org/?probe=0539eeeeb8) | Jan 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6d67af2066](https://linux-hardware.org/?probe=6d67af2066) | Jan 06, 2021 |
| MSI           | Creator X299                | [b66f2c1d16](https://linux-hardware.org/?probe=b66f2c1d16) | Jan 06, 2021 |
| ASRock        | J5005-ITX                   | [81bba5a535](https://linux-hardware.org/?probe=81bba5a535) | Jan 04, 2021 |
| Unknown       | Unknown                     | [34d77cfa6e](https://linux-hardware.org/?probe=34d77cfa6e) | Jan 03, 2021 |
| Unknown       | Unknown                     | [07fb95c682](https://linux-hardware.org/?probe=07fb95c682) | Jan 03, 2021 |
| Acer          | Aspire XC-602 V1.0          | [bb166b2faa](https://linux-hardware.org/?probe=bb166b2faa) | Jan 03, 2021 |
| ASRock        | H110 Pro BTC+               | [f56caad73c](https://linux-hardware.org/?probe=f56caad73c) | Jan 02, 2021 |
| ASRock        | A300M-STX                   | [bd23fb61ad](https://linux-hardware.org/?probe=bd23fb61ad) | Jan 01, 2021 |
| ASRock        | H470M-ITX/ac                | [c6ea824e48](https://linux-hardware.org/?probe=c6ea824e48) | Dec 31, 2020 |
| ASRock        | B360M-ITX/ac                | [8e0bce5edb](https://linux-hardware.org/?probe=8e0bce5edb) | Dec 30, 2020 |
| Gateway       | G33M05G1 MP                 | [460acf5c52](https://linux-hardware.org/?probe=460acf5c52) | Dec 30, 2020 |
| MSI           | FM2-A75IA-E53               | [ec03bb47a4](https://linux-hardware.org/?probe=ec03bb47a4) | Dec 28, 2020 |
| ASRock        | FM2A85X-ITX                 | [5401d7dd29](https://linux-hardware.org/?probe=5401d7dd29) | Dec 23, 2020 |
| ASRock        | B360M-ITX/ac                | [39d7373b8e](https://linux-hardware.org/?probe=39d7373b8e) | Dec 23, 2020 |
| ASUSTek       | Maximus VIII GENE           | [ca0c3d2795](https://linux-hardware.org/?probe=ca0c3d2795) | Dec 21, 2020 |
| ASUSTek       | Maximus VIII GENE           | [97e9570360](https://linux-hardware.org/?probe=97e9570360) | Dec 21, 2020 |
| HP            | 158A                        | [d48f153026](https://linux-hardware.org/?probe=d48f153026) | Dec 21, 2020 |
| FIC           | PTM33 PCB                   | [0e1437dede](https://linux-hardware.org/?probe=0e1437dede) | Dec 18, 2020 |
| Supermicro    | X9DA7/E                     | [7d84e25468](https://linux-hardware.org/?probe=7d84e25468) | Dec 14, 2020 |
| ASRock        | Z390 Pro4                   | [d988af7e73](https://linux-hardware.org/?probe=d988af7e73) | Dec 13, 2020 |
| Intel         | D945GNT AAC96315-402        | [bf27b4bfee](https://linux-hardware.org/?probe=bf27b4bfee) | Dec 12, 2020 |
| NEC Comput... | MS9666 012                  | [9cc98a743f](https://linux-hardware.org/?probe=9cc98a743f) | Dec 11, 2020 |
| Dell          | 002KVM A01                  | [bee5c78b3b](https://linux-hardware.org/?probe=bee5c78b3b) | Dec 08, 2020 |
| Gigabyte      | Z77X-UD3H                   | [772f864f4e](https://linux-hardware.org/?probe=772f864f4e) | Dec 05, 2020 |
| MSI           | H270 PC MATE                | [35866ce8fb](https://linux-hardware.org/?probe=35866ce8fb) | Dec 02, 2020 |
| ASRock        | B550 Taichi                 | [dd9ebdf6b5](https://linux-hardware.org/?probe=dd9ebdf6b5) | Dec 02, 2020 |
| MSI           | H270 PC MATE                | [3151fefb19](https://linux-hardware.org/?probe=3151fefb19) | Dec 02, 2020 |
| Gateway       | G33M05G1 MP                 | [8ec0050494](https://linux-hardware.org/?probe=8ec0050494) | Dec 01, 2020 |
| Dell          | 0NW73C A01                  | [1ddf8958ef](https://linux-hardware.org/?probe=1ddf8958ef) | Nov 27, 2020 |
| ASUSTek       | P5KPL-CM                    | [ca9077ede2](https://linux-hardware.org/?probe=ca9077ede2) | Nov 27, 2020 |
| ASRock        | B550 Taichi                 | [047af22dea](https://linux-hardware.org/?probe=047af22dea) | Nov 27, 2020 |
| ASUSTek       | P5KPL-CM                    | [9148a1a402](https://linux-hardware.org/?probe=9148a1a402) | Nov 25, 2020 |
| ASUSTek       | P5KPL-CM                    | [054642cdd4](https://linux-hardware.org/?probe=054642cdd4) | Nov 25, 2020 |
| Dell          | 0R7935 A03                  | [92a6a98f06](https://linux-hardware.org/?probe=92a6a98f06) | Nov 23, 2020 |
| Dell          | 0R7935 A03                  | [a826e1045e](https://linux-hardware.org/?probe=a826e1045e) | Nov 22, 2020 |
| ASUSTek       | B85M-E                      | [3a74151cb6](https://linux-hardware.org/?probe=3a74151cb6) | Nov 22, 2020 |
| Gateway       | IPISB-VR                    | [9a9f3b244c](https://linux-hardware.org/?probe=9a9f3b244c) | Nov 21, 2020 |
| Gigabyte      | GA-880GM-USB3               | [8d591fed02](https://linux-hardware.org/?probe=8d591fed02) | Nov 21, 2020 |
| ASRock        | H310CM-HDV/M.2              | [da70709a86](https://linux-hardware.org/?probe=da70709a86) | Nov 20, 2020 |
| Gateway       | SX2370                      | [69a18194ba](https://linux-hardware.org/?probe=69a18194ba) | Nov 19, 2020 |
| ASRock        | B460M Pro4                  | [ac90684a5f](https://linux-hardware.org/?probe=ac90684a5f) | Nov 15, 2020 |
| NEC Comput... | G1BJN A                     | [300e280e8c](https://linux-hardware.org/?probe=300e280e8c) | Nov 15, 2020 |
| NEC Comput... | G1BJN A                     | [7344b2e1a1](https://linux-hardware.org/?probe=7344b2e1a1) | Nov 12, 2020 |
| HP            | 0B4Ch D                     | [64fbbc3a2c](https://linux-hardware.org/?probe=64fbbc3a2c) | Nov 08, 2020 |
| ASRock        | H110 Pro BTC+               | [fa4cc0d2b6](https://linux-hardware.org/?probe=fa4cc0d2b6) | Nov 07, 2020 |
| HP            | 0B4Ch D                     | [595b65bc4b](https://linux-hardware.org/?probe=595b65bc4b) | Nov 07, 2020 |
| ECS           | H77H2-M4                    | [e2dc1539b4](https://linux-hardware.org/?probe=e2dc1539b4) | Nov 06, 2020 |
| ASRock        | H110 Pro BTC+               | [38482fe4b4](https://linux-hardware.org/?probe=38482fe4b4) | Nov 04, 2020 |
| NEC Comput... | IS8XM                       | [ca22c03b0e](https://linux-hardware.org/?probe=ca22c03b0e) | Nov 04, 2020 |
| HP            | 0AECh D                     | [84f95d0a66](https://linux-hardware.org/?probe=84f95d0a66) | Nov 04, 2020 |
| Lenovo        | 30C9 SDK0J40700 WIN 3258... | [7b86aebf60](https://linux-hardware.org/?probe=7b86aebf60) | Nov 03, 2020 |
| Dell          | 0F428D A00                  | [e70707332f](https://linux-hardware.org/?probe=e70707332f) | Nov 01, 2020 |
| Dell          | 0F428D A00                  | [86139a47f6](https://linux-hardware.org/?probe=86139a47f6) | Nov 01, 2020 |
| HP            | 0B4Ch D                     | [5621053db7](https://linux-hardware.org/?probe=5621053db7) | Nov 01, 2020 |
| ASRock        | 939A785GMH/128M             | [e5b7c1b0d3](https://linux-hardware.org/?probe=e5b7c1b0d3) | Oct 30, 2020 |
| Shuttle       | FS61                        | [c8b13a3e56](https://linux-hardware.org/?probe=c8b13a3e56) | Oct 25, 2020 |
| Shuttle       | FS61                        | [0e89874393](https://linux-hardware.org/?probe=0e89874393) | Oct 25, 2020 |
| ASUSTek       | P5Q-EM                      | [2b7dc5564c](https://linux-hardware.org/?probe=2b7dc5564c) | Oct 24, 2020 |
| ASRock        | H110M-ITX                   | [c6e251789a](https://linux-hardware.org/?probe=c6e251789a) | Oct 24, 2020 |
| ASRock        | B460M Pro4                  | [40a43c769a](https://linux-hardware.org/?probe=40a43c769a) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [70b6395f2f](https://linux-hardware.org/?probe=70b6395f2f) | Oct 17, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ba5634435e](https://linux-hardware.org/?probe=ba5634435e) | Oct 17, 2020 |
| Supermicro    | C7B75                       | [34cb26f10c](https://linux-hardware.org/?probe=34cb26f10c) | Oct 14, 2020 |
| Pegatron      | IPM41G                      | [fa3b72447f](https://linux-hardware.org/?probe=fa3b72447f) | Oct 12, 2020 |
| Pegatron      | IPM41G                      | [4d26fb41ea](https://linux-hardware.org/?probe=4d26fb41ea) | Oct 12, 2020 |
| Lenovo        | MAHOBAY                     | [467a3d55ed](https://linux-hardware.org/?probe=467a3d55ed) | Oct 09, 2020 |
| ECS           | G43T-3L                     | [7cf090fb8f](https://linux-hardware.org/?probe=7cf090fb8f) | Oct 08, 2020 |
| ECS           | G43T-3L                     | [3533b87774](https://linux-hardware.org/?probe=3533b87774) | Oct 08, 2020 |
| MouseCompu... | Z370-S01                    | [26497a27c8](https://linux-hardware.org/?probe=26497a27c8) | Oct 08, 2020 |
| MouseCompu... | Z370-S01                    | [969cdedc18](https://linux-hardware.org/?probe=969cdedc18) | Oct 08, 2020 |
| Unknown       | Unknown                     | [89eee20d80](https://linux-hardware.org/?probe=89eee20d80) | Oct 05, 2020 |
| ECS           | G43T-3L                     | [b97fcd2011](https://linux-hardware.org/?probe=b97fcd2011) | Oct 02, 2020 |
| Intel         | DG41TX AAE78178-303         | [2ba4c11c35](https://linux-hardware.org/?probe=2ba4c11c35) | Oct 02, 2020 |
| MSI           | H270 PC MATE                | [3c5eb42494](https://linux-hardware.org/?probe=3c5eb42494) | Sep 30, 2020 |
| Gigabyte      | H97-D3H-CF                  | [121f0b68c0](https://linux-hardware.org/?probe=121f0b68c0) | Sep 29, 2020 |
| ASUSTek       | P8H77-V                     | [954984a1e5](https://linux-hardware.org/?probe=954984a1e5) | Sep 23, 2020 |
| MSI           | B450 TOMAHAWK               | [21822dbd0d](https://linux-hardware.org/?probe=21822dbd0d) | Sep 19, 2020 |
| MSI           | B450 TOMAHAWK               | [692295c2b0](https://linux-hardware.org/?probe=692295c2b0) | Sep 19, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [988b8ec0f7](https://linux-hardware.org/?probe=988b8ec0f7) | Sep 14, 2020 |
| Foxconn       | A7DA-S/A7DA                 | [7974b8af2f](https://linux-hardware.org/?probe=7974b8af2f) | Sep 11, 2020 |
| HP            | 0AECh D                     | [acc13196ef](https://linux-hardware.org/?probe=acc13196ef) | Sep 11, 2020 |
| Gigabyte      | H67A-D3H-B3                 | [e50977ee7b](https://linux-hardware.org/?probe=e50977ee7b) | Sep 11, 2020 |
| ASRock        | X79 Extreme4                | [7cd6a3625c](https://linux-hardware.org/?probe=7cd6a3625c) | Sep 10, 2020 |
| ECS           | G31T-M                      | [5b10fa37b2](https://linux-hardware.org/?probe=5b10fa37b2) | Sep 09, 2020 |
| ASRock        | Z170 Extreme4               | [688b4a3ae6](https://linux-hardware.org/?probe=688b4a3ae6) | Sep 06, 2020 |
| Shuttle       | B10IE01                     | [b9e6801288](https://linux-hardware.org/?probe=b9e6801288) | Sep 06, 2020 |
| Shuttle       | B10IE01                     | [176ca21f28](https://linux-hardware.org/?probe=176ca21f28) | Sep 06, 2020 |
| Gigabyte      | H67A-D3H-B3                 | [1bc05191d3](https://linux-hardware.org/?probe=1bc05191d3) | Sep 01, 2020 |
| Dell          | 0NW73C A01                  | [6d64ca0ffc](https://linux-hardware.org/?probe=6d64ca0ffc) | Aug 29, 2020 |
| Unknown       | XH61X000.100                | [1173d1c86c](https://linux-hardware.org/?probe=1173d1c86c) | Aug 16, 2020 |
| MSI           | B450M BAZOOKA PLUS          | [abd9798aa8](https://linux-hardware.org/?probe=abd9798aa8) | Aug 15, 2020 |
| Lenovo        | 30C9 SDK0J40700 WIN 3258... | [729d1212fc](https://linux-hardware.org/?probe=729d1212fc) | Aug 09, 2020 |
| Intel         | D945GNT AAC96315-402        | [58a4a2906c](https://linux-hardware.org/?probe=58a4a2906c) | Aug 09, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc14f627f3](https://linux-hardware.org/?probe=cc14f627f3) | Aug 07, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d76a630eb2](https://linux-hardware.org/?probe=d76a630eb2) | Aug 07, 2020 |
| Fujitsu       | D3523-Ax S26361-D3523-Ax    | [b5164ce426](https://linux-hardware.org/?probe=b5164ce426) | Aug 06, 2020 |
| Unknown       | Unknown                     | [e94665aec0](https://linux-hardware.org/?probe=e94665aec0) | Jul 31, 2020 |
| Acer          | F690GVM                     | [71f0df745c](https://linux-hardware.org/?probe=71f0df745c) | Jul 30, 2020 |
| ASRock        | H55M-GE                     | [374978dac5](https://linux-hardware.org/?probe=374978dac5) | Jul 29, 2020 |
| ASRock        | H55M-GE                     | [235e00b675](https://linux-hardware.org/?probe=235e00b675) | Jul 29, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [bb8dec90c6](https://linux-hardware.org/?probe=bb8dec90c6) | Jul 27, 2020 |
| Dell          | 0Y7WYT A00                  | [efc2b837a2](https://linux-hardware.org/?probe=efc2b837a2) | Jul 26, 2020 |
| Dell          | 0WMJ54 A01                  | [0eeeb834c1](https://linux-hardware.org/?probe=0eeeb834c1) | Jul 23, 2020 |
| HP            | 158A                        | [68f61abed8](https://linux-hardware.org/?probe=68f61abed8) | Jul 20, 2020 |
| IBM           | eServer x3105 -[434722J]... | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| AOpen         | AX4SG-N 918AT10202          | [44e42d5468](https://linux-hardware.org/?probe=44e42d5468) | Jul 19, 2020 |
| ASUSTek       | M3A78-EM                    | [c21bfaa19a](https://linux-hardware.org/?probe=c21bfaa19a) | Jul 18, 2020 |
| Intel         | D510MO AAE76523-403         | [a8297ffb6c](https://linux-hardware.org/?probe=a8297ffb6c) | Jul 17, 2020 |
| Shuttle       | FG41 V20                    | [a714d062a3](https://linux-hardware.org/?probe=a714d062a3) | Jul 15, 2020 |
| Lenovo        | SHARKBAY NOK                | [faca3dbfa3](https://linux-hardware.org/?probe=faca3dbfa3) | Jul 15, 2020 |
| ASRock        | X470 Master SLI             | [efa706ee83](https://linux-hardware.org/?probe=efa706ee83) | Jul 15, 2020 |
| Lenovo        | SHARKBAY NOK                | [4f60404fb3](https://linux-hardware.org/?probe=4f60404fb3) | Jul 15, 2020 |
| ASUSTek       | M4A87TD/USB3                | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek       | M4A87TD/USB3                | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| HP            | 0A54h                       | [944573af57](https://linux-hardware.org/?probe=944573af57) | Jul 13, 2020 |
| HP            | 158A                        | [f5c2d58594](https://linux-hardware.org/?probe=f5c2d58594) | Jul 13, 2020 |
| HP            | 158A                        | [52e8f357cc](https://linux-hardware.org/?probe=52e8f357cc) | Jul 10, 2020 |
| Foxconn       | 2ADA                        | [004f2e3d8b](https://linux-hardware.org/?probe=004f2e3d8b) | Jul 10, 2020 |
| EPSON DIRE... | ST170E                      | [fa44f643d1](https://linux-hardware.org/?probe=fa44f643d1) | Jul 09, 2020 |
| Lenovo        | SHARKBAY NOK                | [31285675c8](https://linux-hardware.org/?probe=31285675c8) | Jul 09, 2020 |
| ASUSTek       | K8V-X SE                    | [3348cccfcf](https://linux-hardware.org/?probe=3348cccfcf) | Jul 07, 2020 |
| NEC Comput... | MS-7594VH                   | [7bb53810f4](https://linux-hardware.org/?probe=7bb53810f4) | Jul 04, 2020 |
| ASUSTek       | P8Z77-V DELUXE              | [f8d281db4b](https://linux-hardware.org/?probe=f8d281db4b) | Jul 04, 2020 |
| ASRock        | B450M Pro4                  | [96bbacdb7a](https://linux-hardware.org/?probe=96bbacdb7a) | Jul 04, 2020 |
| Dell          | 0MF252                      | [682081179d](https://linux-hardware.org/?probe=682081179d) | Jul 03, 2020 |
| MSI           | AM1I                        | [b67361f132](https://linux-hardware.org/?probe=b67361f132) | Jul 03, 2020 |
| MSI           | AM1I                        | [34352c7324](https://linux-hardware.org/?probe=34352c7324) | Jul 03, 2020 |
| Gigabyte      | Z390 UD                     | [52981221fb](https://linux-hardware.org/?probe=52981221fb) | Jul 02, 2020 |
| ASUSTek       | P8Z77-V DELUXE              | [13aec875c0](https://linux-hardware.org/?probe=13aec875c0) | Jun 28, 2020 |
| Gigabyte      | G33-DS3R                    | [ba90c2bc8a](https://linux-hardware.org/?probe=ba90c2bc8a) | Jun 28, 2020 |
| ASUSTek       | Rampage Formula             | [d6042911d7](https://linux-hardware.org/?probe=d6042911d7) | Jun 26, 2020 |
| ASUSTek       | Rampage Formula             | [0cef269aa8](https://linux-hardware.org/?probe=0cef269aa8) | Jun 26, 2020 |
| Intel         | DH61BE AAG14062-206         | [13043e1664](https://linux-hardware.org/?probe=13043e1664) | Jun 26, 2020 |
| ASRock        | Z87 Extreme4                | [78ee2fc419](https://linux-hardware.org/?probe=78ee2fc419) | Jun 24, 2020 |
| Gigabyte      | 970A-DS3P                   | [7d3ab72cf8](https://linux-hardware.org/?probe=7d3ab72cf8) | Jun 23, 2020 |
| ASUSTek       | P5B-E Plus                  | [03c7fbadbe](https://linux-hardware.org/?probe=03c7fbadbe) | Jun 22, 2020 |
| Gigabyte      | Z390 UD                     | [637edc299c](https://linux-hardware.org/?probe=637edc299c) | Jun 20, 2020 |
| Fujitsu       | FJNB04F                     | [15202a6cae](https://linux-hardware.org/?probe=15202a6cae) | Jun 19, 2020 |
| Fujitsu       | FJNB04F                     | [199eca36a2](https://linux-hardware.org/?probe=199eca36a2) | Jun 19, 2020 |
| ASRock        | B460M Pro4                  | [9b0c21ddaf](https://linux-hardware.org/?probe=9b0c21ddaf) | Jun 19, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [216109b0bf](https://linux-hardware.org/?probe=216109b0bf) | Jun 19, 2020 |
| Pegatron      | IPMSB-H61                   | [6182092aa0](https://linux-hardware.org/?probe=6182092aa0) | Jun 18, 2020 |
| ASRock        | J4105M                      | [a1620f0637](https://linux-hardware.org/?probe=a1620f0637) | Jun 18, 2020 |
| MSI           | H67MA-E45                   | [e54c477ff4](https://linux-hardware.org/?probe=e54c477ff4) | Jun 17, 2020 |
| MSI           | H67MA-E45                   | [7ec2ad02d1](https://linux-hardware.org/?probe=7ec2ad02d1) | Jun 17, 2020 |
| Gigabyte      | G33-DS3R                    | [94cd0685d0](https://linux-hardware.org/?probe=94cd0685d0) | Jun 16, 2020 |
| Dell          | 0T10XW A01                  | [c713e8fe0a](https://linux-hardware.org/?probe=c713e8fe0a) | Jun 16, 2020 |
| Dell          | 0T10XW A01                  | [24ba426f14](https://linux-hardware.org/?probe=24ba426f14) | Jun 16, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a01cc45fc9](https://linux-hardware.org/?probe=a01cc45fc9) | Jun 15, 2020 |
| Gigabyte      | G33-DS3R                    | [7608803f5f](https://linux-hardware.org/?probe=7608803f5f) | Jun 14, 2020 |
| ASRock        | H67DE3                      | [7a70672456](https://linux-hardware.org/?probe=7a70672456) | Jun 13, 2020 |
| ASRock        | H67DE3                      | [cc6d5aa5c4](https://linux-hardware.org/?probe=cc6d5aa5c4) | Jun 13, 2020 |
| ASUSTek       | VM42                        | [0e8e6fd4f6](https://linux-hardware.org/?probe=0e8e6fd4f6) | Jun 13, 2020 |
| HP            | 18E7                        | [5d52f06e43](https://linux-hardware.org/?probe=5d52f06e43) | Jun 11, 2020 |
| ASRock        | X370 Gaming K4              | [75f3ae6145](https://linux-hardware.org/?probe=75f3ae6145) | Jun 10, 2020 |
| Foxconn       | A7DA-S/A7DA                 | [0811f5f8ff](https://linux-hardware.org/?probe=0811f5f8ff) | Jun 09, 2020 |
| ASUSTek       | K8V-X SE                    | [8480b7d838](https://linux-hardware.org/?probe=8480b7d838) | Jun 06, 2020 |
| HP            | 805A                        | [ff57395238](https://linux-hardware.org/?probe=ff57395238) | Jun 05, 2020 |
| Gigabyte      | GA-MA69G-S3H                | [09e6763a1e](https://linux-hardware.org/?probe=09e6763a1e) | Jun 04, 2020 |
| Dell          | 0CKCXH A04                  | [0b782c6457](https://linux-hardware.org/?probe=0b782c6457) | Jun 03, 2020 |
| HP            | 18E7                        | [98c9458523](https://linux-hardware.org/?probe=98c9458523) | Jun 02, 2020 |
| Gigabyte      | GA-MA69G-S3H                | [b67c33afab](https://linux-hardware.org/?probe=b67c33afab) | Jun 01, 2020 |
| Gateway       | IPISB-VR                    | [9fcd287a96](https://linux-hardware.org/?probe=9fcd287a96) | May 31, 2020 |
| Gateway       | IPISB-VR                    | [fbb92a7b21](https://linux-hardware.org/?probe=fbb92a7b21) | May 31, 2020 |
| MSI           | H110M GAMING                | [58c02952ac](https://linux-hardware.org/?probe=58c02952ac) | May 31, 2020 |
| ASUSTek       | H87I-PLUS                   | [f830159e63](https://linux-hardware.org/?probe=f830159e63) | May 30, 2020 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [4cdd92c012](https://linux-hardware.org/?probe=4cdd92c012) | May 29, 2020 |
| Supermicro    | X9DA7/E                     | [c1586ca94e](https://linux-hardware.org/?probe=c1586ca94e) | May 27, 2020 |
| HP            | 18E7                        | [e85c8c8c1f](https://linux-hardware.org/?probe=e85c8c8c1f) | May 27, 2020 |
| MouseCompu... | B360M                       | [33e415ae9c](https://linux-hardware.org/?probe=33e415ae9c) | May 25, 2020 |
| Onkyo         | ONKYOPC                     | [cc90a61c2f](https://linux-hardware.org/?probe=cc90a61c2f) | May 24, 2020 |
| ASUSTek       | P8H77-V LE                  | [7b5401d05e](https://linux-hardware.org/?probe=7b5401d05e) | May 22, 2020 |
| ASRock        | J5005-ITX                   | [e3f18b5738](https://linux-hardware.org/?probe=e3f18b5738) | May 21, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [ab3c4986e4](https://linux-hardware.org/?probe=ab3c4986e4) | May 21, 2020 |
| NEC Comput... | MS-7777N1                   | [5cea911946](https://linux-hardware.org/?probe=5cea911946) | May 18, 2020 |
| NEC Comput... | MS-7777N1                   | [0afcb9ba8d](https://linux-hardware.org/?probe=0afcb9ba8d) | May 17, 2020 |
| ASUSTek       | P5E                         | [67df8c58c9](https://linux-hardware.org/?probe=67df8c58c9) | May 16, 2020 |
| ASUSTek       | P6T                         | [90b5a63736](https://linux-hardware.org/?probe=90b5a63736) | May 16, 2020 |
| ASUSTek       | P5E                         | [140c3b0db8](https://linux-hardware.org/?probe=140c3b0db8) | May 11, 2020 |
| HP            | 158A                        | [5af55dbc63](https://linux-hardware.org/?probe=5af55dbc63) | May 09, 2020 |
| MSI           | MEG X570 ACE                | [dc7e369d45](https://linux-hardware.org/?probe=dc7e369d45) | May 08, 2020 |
| ASRock        | B450M Pro4                  | [01445b6224](https://linux-hardware.org/?probe=01445b6224) | May 07, 2020 |
| ASRock        | 970 Extreme3                | [5391547134](https://linux-hardware.org/?probe=5391547134) | May 05, 2020 |
| Supermicro    | X9DA7/E                     | [a36a61fc42](https://linux-hardware.org/?probe=a36a61fc42) | May 05, 2020 |
| ASUSTek       | P8B75-M                     | [64b3255738](https://linux-hardware.org/?probe=64b3255738) | May 05, 2020 |
| Supermicro    | X9DA7/E                     | [0e1b63c36e](https://linux-hardware.org/?probe=0e1b63c36e) | May 05, 2020 |
| ASRock        | X370 Gaming K4              | [9b591e104f](https://linux-hardware.org/?probe=9b591e104f) | May 04, 2020 |
| ASUSTek       | P8B75-M                     | [38669e151b](https://linux-hardware.org/?probe=38669e151b) | Apr 17, 2020 |
| UNITCOM       | B85H3-M4/2.0                | [7e39b26e35](https://linux-hardware.org/?probe=7e39b26e35) | Apr 17, 2020 |
| UNITCOM       | B85H3-M4/2.0                | [a622ca867c](https://linux-hardware.org/?probe=a622ca867c) | Apr 17, 2020 |
| FIC           | PTM33 PCB                   | [a258fe9d3c](https://linux-hardware.org/?probe=a258fe9d3c) | Apr 17, 2020 |
| FIC           | PTM33 PCB                   | [5c757ca851](https://linux-hardware.org/?probe=5c757ca851) | Apr 17, 2020 |
| MouseCompu... | Z170-S01                    | [48ca5fe277](https://linux-hardware.org/?probe=48ca5fe277) | Apr 15, 2020 |
| MouseCompu... | Z170-S01                    | [9157166443](https://linux-hardware.org/?probe=9157166443) | Apr 15, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [6169eb8c91](https://linux-hardware.org/?probe=6169eb8c91) | Apr 14, 2020 |
| ASRock        | H310CM-HDV/M.2              | [253ee15233](https://linux-hardware.org/?probe=253ee15233) | Apr 12, 2020 |
| MCJ           | H55M-P33                    | [cb5e96a31a](https://linux-hardware.org/?probe=cb5e96a31a) | Apr 08, 2020 |
| ASUSTek       | F1A75-V PRO                 | [abe59477d7](https://linux-hardware.org/?probe=abe59477d7) | Apr 05, 2020 |
| ASUSTek       | F1A75-V PRO                 | [41eee8b868](https://linux-hardware.org/?probe=41eee8b868) | Apr 04, 2020 |
| ASRock        | H310M-STX                   | [5fbe6e4ee6](https://linux-hardware.org/?probe=5fbe6e4ee6) | Apr 01, 2020 |
| ASRock        | H310M-STX                   | [4a58d0cf1f](https://linux-hardware.org/?probe=4a58d0cf1f) | Apr 01, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [6fc123427e](https://linux-hardware.org/?probe=6fc123427e) | Mar 21, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [ec5fdd7cf2](https://linux-hardware.org/?probe=ec5fdd7cf2) | Mar 21, 2020 |
| ASUSTek       | P5E-VM HDMI                 | [95d96a6705](https://linux-hardware.org/?probe=95d96a6705) | Mar 14, 2020 |
| ASUSTek       | P8Z77-V LX                  | [edda861710](https://linux-hardware.org/?probe=edda861710) | Mar 01, 2020 |
| ECS           | G31T-M                      | [b765a7fa7f](https://linux-hardware.org/?probe=b765a7fa7f) | Feb 11, 2020 |
| ASRock        | H87M Pro4                   | [ca641865e0](https://linux-hardware.org/?probe=ca641865e0) | Feb 06, 2020 |
| ASUSTek       | PRIME H310M-A               | [2e4119c423](https://linux-hardware.org/?probe=2e4119c423) | Jan 30, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [043ccd92f3](https://linux-hardware.org/?probe=043ccd92f3) | Jan 29, 2020 |
| ASRock        | A88M-G                      | [3949599c5d](https://linux-hardware.org/?probe=3949599c5d) | Jan 28, 2020 |
| HP            | 0A54h                       | [356168fec6](https://linux-hardware.org/?probe=356168fec6) | Jan 28, 2020 |
| ASRock        | A88M-G                      | [bb36145452](https://linux-hardware.org/?probe=bb36145452) | Jan 25, 2020 |
| ASRock        | A88M-G                      | [07e625051c](https://linux-hardware.org/?probe=07e625051c) | Jan 25, 2020 |
| Gateway       | RS780                       | [09cf381b3c](https://linux-hardware.org/?probe=09cf381b3c) | Jan 25, 2020 |
| Gateway       | RS780                       | [3fe382995a](https://linux-hardware.org/?probe=3fe382995a) | Jan 13, 2020 |
| ASUSTek       | X99-A                       | [67389da431](https://linux-hardware.org/?probe=67389da431) | Jan 04, 2020 |
| Gateway       | RS780                       | [3b7741a3a0](https://linux-hardware.org/?probe=3b7741a3a0) | Jan 04, 2020 |
| ASUSTek       | X99-A                       | [8893153b1b](https://linux-hardware.org/?probe=8893153b1b) | Jan 01, 2020 |
| Gigabyte      | 965G-DS3                    | [a7a0b9ab30](https://linux-hardware.org/?probe=a7a0b9ab30) | Dec 28, 2019 |
| ASRock        | J3160DC-ITX                 | [b41206f2fd](https://linux-hardware.org/?probe=b41206f2fd) | Dec 22, 2019 |
| Fujitsu       | JIH61Y3                     | [5a7487a856](https://linux-hardware.org/?probe=5a7487a856) | Dec 21, 2019 |
| Gigabyte      | Z97X-UD3H-CF                | [a66e24484e](https://linux-hardware.org/?probe=a66e24484e) | Dec 19, 2019 |
| Wistron       | JIB65Y                      | [ed496b7bdf](https://linux-hardware.org/?probe=ed496b7bdf) | Dec 19, 2019 |
| ECS           | G31T-M                      | [7052a98f3b](https://linux-hardware.org/?probe=7052a98f3b) | Dec 19, 2019 |
| ASUSTek       | PRIME Z390-A                | [91947835b4](https://linux-hardware.org/?probe=91947835b4) | Dec 04, 2019 |
| Gigabyte      | 970A-D3P                    | [65bd7a0352](https://linux-hardware.org/?probe=65bd7a0352) | Nov 30, 2019 |
| ASRock        | H87M Pro4                   | [54341a6439](https://linux-hardware.org/?probe=54341a6439) | Nov 26, 2019 |
| MSI           | AM1I                        | [e6dcc8ef69](https://linux-hardware.org/?probe=e6dcc8ef69) | Nov 11, 2019 |
| Gigabyte      | Z390 M GAMING-CF            | [91ed990d94](https://linux-hardware.org/?probe=91ed990d94) | Oct 28, 2019 |
| NEC Comput... | MS-7594VH                   | [9ddd905922](https://linux-hardware.org/?probe=9ddd905922) | Oct 27, 2019 |
| ECS           | G31T-M                      | [21dce1ded7](https://linux-hardware.org/?probe=21dce1ded7) | Oct 26, 2019 |
| ASUSTek       | PRIME H370-A                | [7b0b66861a](https://linux-hardware.org/?probe=7b0b66861a) | Oct 12, 2019 |
| HP            | 2ADE                        | [eba5a305b7](https://linux-hardware.org/?probe=eba5a305b7) | Oct 07, 2019 |
| ASUSTek       | PRIME X299-A                | [049af64f1e](https://linux-hardware.org/?probe=049af64f1e) | Oct 04, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [9db5f37aab](https://linux-hardware.org/?probe=9db5f37aab) | Oct 03, 2019 |
| ASRock        | H77 Pro4/MVP                | [306e5b04f7](https://linux-hardware.org/?probe=306e5b04f7) | Sep 28, 2019 |
| ASRock        | Z87 Killer                  | [ee533a4daf](https://linux-hardware.org/?probe=ee533a4daf) | Sep 26, 2019 |
| ECS           | G31T-M                      | [5cefc9e8d2](https://linux-hardware.org/?probe=5cefc9e8d2) | Sep 24, 2019 |
| Gigabyte      | H81M-DS2                    | [2d44575da5](https://linux-hardware.org/?probe=2d44575da5) | Sep 23, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [f9ce29fec6](https://linux-hardware.org/?probe=f9ce29fec6) | Sep 19, 2019 |
| ASUSTek       | PRIME Z390-A                | [a9d1c2f51c](https://linux-hardware.org/?probe=a9d1c2f51c) | Sep 18, 2019 |
| ASUSTek       | PRIME Z390-A                | [a6ed7aa983](https://linux-hardware.org/?probe=a6ed7aa983) | Sep 18, 2019 |
| ASUSTek       | M4A78-VM                    | [fc5bd8749b](https://linux-hardware.org/?probe=fc5bd8749b) | Sep 17, 2019 |
| ASRock        | Z87 Killer                  | [3918b7d23a](https://linux-hardware.org/?probe=3918b7d23a) | Sep 14, 2019 |
| ECS           | A75F-M2                     | [f891e8f1d5](https://linux-hardware.org/?probe=f891e8f1d5) | Sep 06, 2019 |
| ASRock        | Z87 Killer                  | [a1d5416305](https://linux-hardware.org/?probe=a1d5416305) | Sep 01, 2019 |
| ECS           | G31T-M                      | [78a1016ee6](https://linux-hardware.org/?probe=78a1016ee6) | Aug 30, 2019 |
| ASUSTek       | PRIME X299-A                | [4ad9989703](https://linux-hardware.org/?probe=4ad9989703) | Aug 28, 2019 |
| ASRock        | Z87 Killer                  | [16e84b9fb7](https://linux-hardware.org/?probe=16e84b9fb7) | Aug 24, 2019 |
| ASUSTek       | GL12CP                      | [0b7ad9054f](https://linux-hardware.org/?probe=0b7ad9054f) | Aug 19, 2019 |
| ASUSTek       | PRIME X299-A                | [1f914d8603](https://linux-hardware.org/?probe=1f914d8603) | Aug 15, 2019 |
| Fujitsu       | JIH61Y3                     | [0bdef2ed89](https://linux-hardware.org/?probe=0bdef2ed89) | Aug 15, 2019 |
| ASUSTek       | GL12CP                      | [314f1278b8](https://linux-hardware.org/?probe=314f1278b8) | Aug 13, 2019 |
| ASUSTek       | GL12CP                      | [7e8a4409ab](https://linux-hardware.org/?probe=7e8a4409ab) | Aug 13, 2019 |
| NEC Comput... | MS9666 012                  | [e0ccec3cb3](https://linux-hardware.org/?probe=e0ccec3cb3) | Aug 08, 2019 |
| HP            | 158B                        | [f588fb7831](https://linux-hardware.org/?probe=f588fb7831) | Aug 05, 2019 |
| Gigabyte      | G41M-Combo                  | [7a7a55bb9f](https://linux-hardware.org/?probe=7a7a55bb9f) | Aug 01, 2019 |
| ASUSTek       | P5SD2-VM                    | [63f518652d](https://linux-hardware.org/?probe=63f518652d) | Aug 01, 2019 |
| ASUSTek       | P5SD2-VM                    | [2985c7f780](https://linux-hardware.org/?probe=2985c7f780) | Jul 27, 2019 |
| HP            | 1589                        | [2eeb0dcbef](https://linux-hardware.org/?probe=2eeb0dcbef) | Jul 18, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [8d70085277](https://linux-hardware.org/?probe=8d70085277) | Jul 16, 2019 |
| MCJ           | CO.,LTD                     | [0cca59b833](https://linux-hardware.org/?probe=0cca59b833) | Jul 13, 2019 |
| MCJ           | CO.,LTD                     | [262f82967e](https://linux-hardware.org/?probe=262f82967e) | Jul 12, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [c77e3987e8](https://linux-hardware.org/?probe=c77e3987e8) | Jul 12, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [03894447bb](https://linux-hardware.org/?probe=03894447bb) | Jul 12, 2019 |
| Fujitsu       | JIH61Y3                     | [ef1765e325](https://linux-hardware.org/?probe=ef1765e325) | Jul 12, 2019 |
| Fujitsu       | JIH61Y3                     | [f457a91893](https://linux-hardware.org/?probe=f457a91893) | Jul 12, 2019 |
| ASUSTek       | M4A88T-I DELUXE             | [7011e7619b](https://linux-hardware.org/?probe=7011e7619b) | Jul 04, 2019 |
| ASRock        | H77 Pro4/MVP                | [3ac82eca46](https://linux-hardware.org/?probe=3ac82eca46) | Jun 29, 2019 |
| NEC Comput... | MS-7594VH                   | [e61c26fd4c](https://linux-hardware.org/?probe=e61c26fd4c) | Jun 25, 2019 |
| ASUSTek       | X99-E-10G WS                | [f7605b7f95](https://linux-hardware.org/?probe=f7605b7f95) | Jun 18, 2019 |
| ASUSTek       | H110M-A/M.2                 | [6e8096d588](https://linux-hardware.org/?probe=6e8096d588) | May 28, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | [4cf90e52e8](https://linux-hardware.org/?probe=4cf90e52e8) | May 28, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | [279621d15c](https://linux-hardware.org/?probe=279621d15c) | May 20, 2019 |
| Dell          | 0XPDFK A01                  | [b545ad5544](https://linux-hardware.org/?probe=b545ad5544) | May 10, 2019 |
| Dell          | 0XPDFK A01                  | [d4c3d2990b](https://linux-hardware.org/?probe=d4c3d2990b) | May 09, 2019 |
| Onkyo         | ONKYOPC 0A                  | [d298e61165](https://linux-hardware.org/?probe=d298e61165) | May 04, 2019 |
| ASRock        | X370 Gaming K4              | [f3883ffe3f](https://linux-hardware.org/?probe=f3883ffe3f) | May 03, 2019 |
| ASUSTek       | PRIME H370M-PLUS            | [d92d4f0666](https://linux-hardware.org/?probe=d92d4f0666) | May 02, 2019 |
| HP            | 3398                        | [915f8eec67](https://linux-hardware.org/?probe=915f8eec67) | Apr 30, 2019 |
| Gigabyte      | A320M-HD2-CF                | [740fc92339](https://linux-hardware.org/?probe=740fc92339) | Apr 26, 2019 |
| Dell          | 09KPNV A00                  | [ac628634d2](https://linux-hardware.org/?probe=ac628634d2) | Mar 30, 2019 |
| MCJ           | H55-S01                     | [24d0907973](https://linux-hardware.org/?probe=24d0907973) | Mar 21, 2019 |
| Dell          | 0J584C A00                  | [7f79951f35](https://linux-hardware.org/?probe=7f79951f35) | Mar 10, 2019 |
| Gigabyte      | M61P-S3                     | [b6505655d3](https://linux-hardware.org/?probe=b6505655d3) | Feb 22, 2019 |
| Gigabyte      | M61P-S3                     | [d1f1dd8c96](https://linux-hardware.org/?probe=d1f1dd8c96) | Feb 19, 2019 |
| ASUSTek       | M3A78-EM                    | [0120bc4801](https://linux-hardware.org/?probe=0120bc4801) | Feb 04, 2019 |
| Pegatron      | 2AB5                        | [c87217d642](https://linux-hardware.org/?probe=c87217d642) | Feb 03, 2019 |
| Intel         | DG965RY AAD41691-205        | [15252dcf05](https://linux-hardware.org/?probe=15252dcf05) | Jan 20, 2019 |
| MCJ           | H55-S01                     | [f694a85c3b](https://linux-hardware.org/?probe=f694a85c3b) | Jan 20, 2019 |
| MCJ           | H55-S01                     | [b72a8388df](https://linux-hardware.org/?probe=b72a8388df) | Jan 20, 2019 |
| Gigabyte      | B450 AORUS M                | [7d4741d740](https://linux-hardware.org/?probe=7d4741d740) | Nov 17, 2018 |
| MSI           | P67A-S40                    | [4104f2eabe](https://linux-hardware.org/?probe=4104f2eabe) | Nov 12, 2018 |
| Dell          | 0WJ771                      | [1a6e39d574](https://linux-hardware.org/?probe=1a6e39d574) | Dec 07, 2017 |
| ASRock        | 990FX Extreme4              | [b1702d4023](https://linux-hardware.org/?probe=b1702d4023) | Apr 21, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Japan/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 105      | 17.89%  |
| Ubuntu 18.04       | 58       | 9.88%   |
| Ubuntu 22.04       | 42       | 7.16%   |
| OpenMandriva 4.3   | 29       | 4.94%   |
| OpenMandriva 23.03 | 26       | 4.43%   |
| OpenMandriva 4.2   | 18       | 3.07%   |
| Xubuntu 20.04      | 16       | 2.73%   |
| Debian 11          | 14       | 2.39%   |
| Arch Rolling       | 11       | 1.87%   |
| Xubuntu 18.04      | 10       | 1.7%    |
| OpenMandriva 23.01 | 10       | 1.7%    |
| Ubuntu 21.10       | 9        | 1.53%   |
| Ubuntu 20.10       | 8        | 1.36%   |
| Pop!_OS 22.04      | 8        | 1.36%   |
| Linux Mint 21.1    | 8        | 1.36%   |
| Ubuntu 19.04       | 7        | 1.19%   |
| BlackPanther 18.1  | 7        | 1.19%   |
| Ubuntu 21.04       | 6        | 1.02%   |
| OpenMandriva 4.50  | 6        | 1.02%   |
| Fedora 34          | 6        | 1.02%   |
| Arch               | 6        | 1.02%   |
| Zorin 16           | 5        | 0.85%   |
| Ubuntu 22.10       | 5        | 0.85%   |
| Pop!_OS 21.04      | 5        | 0.85%   |
| OpenMandriva 23.08 | 5        | 0.85%   |
| Linux Mint 20.3    | 5        | 0.85%   |
| Linux Mint 19.3    | 5        | 0.85%   |
| Fedora 36          | 5        | 0.85%   |
| ArcoLinux Rolling  | 5        | 0.85%   |
| ROSA R11           | 4        | 0.68%   |
| Manjaro            | 4        | 0.68%   |
| Lubuntu 20.04      | 4        | 0.68%   |
| Linux Mint 20      | 4        | 0.68%   |
| KDE neon 20.04     | 4        | 0.68%   |
| Fedora 33          | 4        | 0.68%   |
| Fedora 32          | 4        | 0.68%   |
| Zorin 15           | 3        | 0.51%   |
| Ubuntu 19.10       | 3        | 0.51%   |
| Ubuntu 16.04       | 3        | 0.51%   |
| Linux Mint 21      | 3        | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 235      | 42.88%  |
| OpenMandriva  | 89       | 16.24%  |
| Linux Mint    | 30       | 5.47%   |
| Xubuntu       | 25       | 4.56%   |
| Fedora        | 25       | 4.56%   |
| Debian        | 21       | 3.83%   |
| Arch          | 17       | 3.1%    |
| Pop!_OS       | 16       | 2.92%   |
| Zorin         | 9        | 1.64%   |
| ROSA          | 8        | 1.46%   |
| Manjaro       | 8        | 1.46%   |
| BlackPanther  | 7        | 1.28%   |
| Gentoo        | 5        | 0.91%   |
| ArcoLinux     | 5        | 0.91%   |
| Lubuntu       | 4        | 0.73%   |
| Kubuntu       | 4        | 0.73%   |
| KDE neon      | 4        | 0.73%   |
| Elementary    | 4        | 0.73%   |
| openSUSE      | 3        | 0.55%   |
| CentOS        | 3        | 0.55%   |
| Ubuntu Unity  | 2        | 0.36%   |
| Ubuntu MATE   | 2        | 0.36%   |
| Slackware     | 2        | 0.36%   |
| Parrot        | 2        | 0.36%   |
| Nobara        | 2        | 0.36%   |
| Endless       | 2        | 0.36%   |
| Clear Linux   | 2        | 0.36%   |
| Ubuntu Budgie | 1        | 0.18%   |
| Rocky Linux   | 1        | 0.18%   |
| RHEL          | 1        | 0.18%   |
| Redcore       | 1        | 0.18%   |
| Kali          | 1        | 0.18%   |
| Garuda Linux  | 1        | 0.18%   |
| EndeavourOS   | 1        | 0.18%   |
| ChimeraOS     | 1        | 0.18%   |
| BunsenLabs    | 1        | 0.18%   |
| BigLinux      | 1        | 0.18%   |
| Artix         | 1        | 0.18%   |
| antiX         | 1        | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 28       | 4.26%   |
| 6.2.6-desktop-1omv2390   | 23       | 3.5%    |
| 5.10.14-desktop-1omv4002 | 17       | 2.59%   |
| 5.4.0-42-generic         | 10       | 1.52%   |
| 6.1.1-desktop-1omv2290   | 9        | 1.37%   |
| 5.4.0-40-generic         | 9        | 1.37%   |
| 5.4.0-33-generic         | 9        | 1.37%   |
| 5.4.0-58-generic         | 8        | 1.22%   |
| 5.4.0-37-generic         | 8        | 1.22%   |
| 5.15.0-56-generic        | 8        | 1.22%   |
| 5.4.0-52-generic         | 7        | 1.07%   |
| 4.18.16-desktop-1bP      | 7        | 1.07%   |
| 5.4.0-54-generic         | 6        | 0.91%   |
| 5.4.0-29-generic         | 5        | 0.76%   |
| 5.16.13-desktop-1omv4003 | 5        | 0.76%   |
| 5.13.0-40-generic        | 5        | 0.76%   |
| 5.13.0-30-generic        | 5        | 0.76%   |
| 5.11.0-38-generic        | 5        | 0.76%   |
| 6.4.11-desktop-1omv2390  | 4        | 0.61%   |
| 6.2.0-33-generic         | 4        | 0.61%   |
| 5.4.0-66-generic         | 4        | 0.61%   |
| 5.19.0-41-generic        | 4        | 0.61%   |
| 5.19.0-38-generic        | 4        | 0.61%   |
| 5.15.0-50-generic        | 4        | 0.61%   |
| 5.15.0-46-generic        | 4        | 0.61%   |
| 5.13.0-39-generic        | 4        | 0.61%   |
| 5.10.0-16-amd64          | 4        | 0.61%   |
| 5.0.0-29-generic         | 4        | 0.61%   |
| 4.15.0-72-generic        | 4        | 0.61%   |
| 4.15.0-48-generic        | 4        | 0.61%   |
| 6.2.6-76060206-generic   | 3        | 0.46%   |
| 5.8.0-59-generic         | 3        | 0.46%   |
| 5.8.0-55-generic         | 3        | 0.46%   |
| 5.8.0-50-generic         | 3        | 0.46%   |
| 5.8.0-43-generic         | 3        | 0.46%   |
| 5.4.0-99-generic         | 3        | 0.46%   |
| 5.4.0-67-generic         | 3        | 0.46%   |
| 5.4.0-39-generic         | 3        | 0.46%   |
| 5.4.0-31-generic         | 3        | 0.46%   |
| 5.3.0-28-generic         | 3        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 112      | 18.54%  |
| 4.15.0  | 48       | 7.95%   |
| 5.15.0  | 47       | 7.78%   |
| 5.13.0  | 29       | 4.8%    |
| 5.16.7  | 28       | 4.64%   |
| 5.8.0   | 27       | 4.47%   |
| 5.11.0  | 27       | 4.47%   |
| 6.2.6   | 26       | 4.3%    |
| 5.19.0  | 22       | 3.64%   |
| 5.10.14 | 18       | 2.98%   |
| 5.3.0   | 16       | 2.65%   |
| 5.10.0  | 16       | 2.65%   |
| 5.0.0   | 16       | 2.65%   |
| 6.1.1   | 10       | 1.66%   |
| 6.2.0   | 7        | 1.16%   |
| 4.18.16 | 7        | 1.16%   |
| 5.16.13 | 6        | 0.99%   |
| 6.4.11  | 5        | 0.83%   |
| 4.18.0  | 5        | 0.83%   |
| 6.1.0   | 3        | 0.5%    |
| 6.0.8   | 3        | 0.5%    |
| 5.3.18  | 3        | 0.5%    |
| 5.14.0  | 3        | 0.5%    |
| 5.12.4  | 3        | 0.5%    |
| 4.4.0   | 3        | 0.5%    |
| 6.5.0   | 2        | 0.33%   |
| 6.3.5   | 2        | 0.33%   |
| 6.2.2   | 2        | 0.33%   |
| 6.1.4   | 2        | 0.33%   |
| 6.1.12  | 2        | 0.33%   |
| 6.0.6   | 2        | 0.33%   |
| 6.0.0   | 2        | 0.33%   |
| 5.9.0   | 2        | 0.33%   |
| 5.7.9   | 2        | 0.33%   |
| 5.19.10 | 2        | 0.33%   |
| 5.15.2  | 2        | 0.33%   |
| 5.15.15 | 2        | 0.33%   |
| 4.9.60  | 2        | 0.33%   |
| 4.19.0  | 2        | 0.33%   |
| 6.5.4   | 1        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 113      | 18.99%  |
| 5.15    | 56       | 9.41%   |
| 4.15    | 48       | 8.07%   |
| 5.10    | 41       | 6.89%   |
| 6.2     | 39       | 6.55%   |
| 5.13    | 34       | 5.71%   |
| 5.8     | 31       | 5.21%   |
| 5.16    | 31       | 5.21%   |
| 5.11    | 29       | 4.87%   |
| 5.19    | 28       | 4.71%   |
| 6.1     | 20       | 3.36%   |
| 5.3     | 19       | 3.19%   |
| 5.0     | 18       | 3.03%   |
| 6.0     | 12       | 2.02%   |
| 4.18    | 12       | 2.02%   |
| 5.9     | 7        | 1.18%   |
| 6.4     | 6        | 1.01%   |
| 5.12    | 6        | 1.01%   |
| 6.3     | 5        | 0.84%   |
| 5.14    | 5        | 0.84%   |
| 5.7     | 4        | 0.67%   |
| 5.6     | 4        | 0.67%   |
| 5.17    | 4        | 0.67%   |
| 6.5     | 3        | 0.5%    |
| 5.5     | 3        | 0.5%    |
| 5.2     | 3        | 0.5%    |
| 5.18    | 3        | 0.5%    |
| 4.9     | 3        | 0.5%    |
| 4.4     | 3        | 0.5%    |
| 4.19    | 3        | 0.5%    |
| 4.8     | 1        | 0.17%   |
| 3.10    | 1        | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 529      | 97.96%  |
| i686        | 10       | 1.85%   |
| loongarch64 | 1        | 0.19%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| GNOME                    | 253      | 45.67%  |
| KDE5                     | 114      | 20.58%  |
| Unknown                  | 62       | 11.19%  |
| XFCE                     | 39       | 7.04%   |
| X-Cinnamon               | 27       | 4.87%   |
| MATE                     | 9        | 1.62%   |
| LXQt                     | 9        | 1.62%   |
| KDE                      | 9        | 1.62%   |
| Pantheon                 | 4        | 0.72%   |
| KDE4                     | 4        | 0.72%   |
| Budgie                   | 4        | 0.72%   |
| LXDE                     | 3        | 0.54%   |
| Unity                    | 2        | 0.36%   |
| sway                     | 2        | 0.36%   |
| GNOME Classic            | 2        | 0.36%   |
| Cinnamon                 | 2        | 0.36%   |
| awesome                  | 2        | 0.36%   |
| XSession                 | 1        | 0.18%   |
| Openbox                  | 1        | 0.18%   |
| i3                       | 1        | 0.18%   |
| Enlightenment            | 1        | 0.18%   |
| Deepin                   | 1        | 0.18%   |
| BunsenLabs               | 1        | 0.18%   |
| /usr/bin/openbox-session | 1        | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 409      | 74.09%  |
| Wayland | 83       | 15.04%  |
| Unknown | 41       | 7.43%   |
| Tty     | 19       | 3.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 273      | 48.75%  |
| SDDM    | 115      | 20.54%  |
| GDM3    | 76       | 13.57%  |
| GDM     | 45       | 8.04%   |
| LightDM | 32       | 5.71%   |
| TDM     | 8        | 1.43%   |
| KDM     | 3        | 0.54%   |
| NODM    | 2        | 0.36%   |
| LXDM    | 2        | 0.36%   |
| GREETD  | 2        | 0.36%   |
| XDM     | 1        | 0.18%   |
| SLiM    | 1        | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| ja_JP       | 278      | 51.01%  |
| en_US       | 149      | 27.34%  |
| Unknown     | 62       | 11.38%  |
| pt_BR       | 12       | 2.2%    |
| zh_CN       | 10       | 1.83%   |
| en_GB       | 10       | 1.83%   |
| C           | 4        | 0.73%   |
| ru_RU       | 2        | 0.37%   |
| it_IT       | 2        | 0.37%   |
| en_IN       | 2        | 0.37%   |
| en_AU       | 2        | 0.37%   |
| en_AG       | 2        | 0.37%   |
| UTF-8       | 1        | 0.18%   |
| tr_TR       | 1        | 0.18%   |
| sr_RS       | 1        | 0.18%   |
| sk_SK       | 1        | 0.18%   |
| ja_JP.utf-8 | 1        | 0.18%   |
| fr_FR       | 1        | 0.18%   |
| fr_CA       | 1        | 0.18%   |
| es_ES       | 1        | 0.18%   |
| de_DE       | 1        | 0.18%   |
| af_ZA       | 1        | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 330      | 60.44%  |
| EFI  | 216      | 39.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 409      | 73.69%  |
| Overlay | 65       | 11.71%  |
| Btrfs   | 31       | 5.59%   |
| Tmpfs   | 15       | 2.7%    |
| Xfs     | 14       | 2.52%   |
| Unknown | 12       | 2.16%   |
| Zfs     | 5        | 0.9%    |
| Jfs     | 2        | 0.36%   |
| F2fs    | 1        | 0.18%   |
| Ext3    | 1        | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 305      | 54.95%  |
| GPT     | 199      | 35.86%  |
| MBR     | 51       | 9.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 406      | 73.42%  |
| Yes       | 147      | 26.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 366      | 66.06%  |
| Yes       | 188      | 33.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 127      | 23.65%  |
| ASRock                               | 105      | 19.55%  |
| Gigabyte Technology                  | 67       | 12.48%  |
| MSI                                  | 51       | 9.5%    |
| Hewlett-Packard                      | 31       | 5.77%   |
| Dell                                 | 26       | 4.84%   |
| NEC Computers                        | 13       | 2.42%   |
| MouseComputer                        | 13       | 2.42%   |
| Intel                                | 12       | 2.23%   |
| Fujitsu                              | 10       | 1.86%   |
| Biostar                              | 10       | 1.86%   |
| ECS                                  | 9        | 1.68%   |
| Lenovo                               | 8        | 1.49%   |
| Unknown                              | 8        | 1.49%   |
| MCJ                                  | 4        | 0.74%   |
| Gateway                              | 4        | 0.74%   |
| Acer                                 | 4        | 0.74%   |
| Wistron                              | 3        | 0.56%   |
| Shuttle                              | 3        | 0.56%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.56%   |
| Pegatron                             | 3        | 0.56%   |
| Foxconn                              | 3        | 0.56%   |
| EPSON DIRECT                         | 3        | 0.56%   |
| Supermicro                           | 2        | 0.37%   |
| Onkyo                                | 2        | 0.37%   |
| XFX                                  | 1        | 0.19%   |
| UNITCOM                              | 1        | 0.19%   |
| Loongson                             | 1        | 0.19%   |
| IBM                                  | 1        | 0.19%   |
| Huanan                               | 1        | 0.19%   |
| HC                                   | 1        | 0.19%   |
| GMKtec                               | 1        | 0.19%   |
| GALAX                                | 1        | 0.19%   |
| FIC                                  | 1        | 0.19%   |
| BESSTAR Tech                         | 1        | 0.19%   |
| Apple                                | 1        | 0.19%   |
| AOpen                                | 1        | 0.19%   |
| AAEON                                | 1        | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 14       | 2.61%   |
| Unknown                                    | 8        | 1.49%   |
| HP ProDesk 600 G1 SFF                      | 5        | 0.93%   |
| ASRock B450M Pro4                          | 5        | 0.93%   |
| MSI MS-7A40                                | 4        | 0.74%   |
| ASRock Z87 Killer                          | 4        | 0.74%   |
| ASRock B450 Pro4                           | 4        | 0.74%   |
| ASRock B450 Gaming-ITX/ac                  | 4        | 0.74%   |
| NEC Computers Express5800/S70 [N8100-9021] | 3        | 0.56%   |
| HP Z620 Workstation                        | 3        | 0.56%   |
| ECS G31T-M                                 | 3        | 0.56%   |
| Dell Precision WorkStation T3500           | 3        | 0.56%   |
| Dell OptiPlex 3020                         | 3        | 0.56%   |
| ASUS PRIME H670-PLUS D4                    | 3        | 0.56%   |
| ASUS P7H55-M                               | 3        | 0.56%   |
| ASUS H170-PRO                              | 3        | 0.56%   |
| ASRock Z370 Pro4                           | 3        | 0.56%   |
| ASRock Prime Series                        | 3        | 0.56%   |
| ASRock J5005-ITX                           | 3        | 0.56%   |
| ASRock B460M Pro4                          | 3        | 0.56%   |
| ASRock A300M-STX                           | 3        | 0.56%   |
| Onkyo ONKYOPC                              | 2        | 0.37%   |
| MSI MS-7D16                                | 2        | 0.37%   |
| MSI MS-7C95                                | 2        | 0.37%   |
| MSI MS-7C94                                | 2        | 0.37%   |
| MSI MS-7C37                                | 2        | 0.37%   |
| MSI MS-7C35                                | 2        | 0.37%   |
| MSI MS-7C02                                | 2        | 0.37%   |
| MSI MS-7B86                                | 2        | 0.37%   |
| MSI MS-7B79                                | 2        | 0.37%   |
| MSI MS-7A72                                | 2        | 0.37%   |
| MSI MS-7865                                | 2        | 0.37%   |
| MouseComputer B75M-D3V-JP                  | 2        | 0.37%   |
| MouseComputer B360M                        | 2        | 0.37%   |
| HP ProDesk 600 G4 SFF                      | 2        | 0.37%   |
| HP ProDesk 400 G2 MINI                     | 2        | 0.37%   |
| HP Compaq dc7700p Small Form Factor        | 2        | 0.37%   |
| Gigabyte Z77X-UD3H                         | 2        | 0.37%   |
| Gigabyte Z170X-Gaming 3                    | 2        | 0.37%   |
| Gigabyte H67A-D3H-B3                       | 2        | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS PRIME                | 26       | 4.84%   |
| ASUS TUF                  | 14       | 2.61%   |
| ASUS All                  | 14       | 2.61%   |
| ASUS ROG                  | 11       | 2.05%   |
| HP ProDesk                | 9        | 1.68%   |
| Dell OptiPlex             | 9        | 1.68%   |
| ASRock B450               | 9        | 1.68%   |
| Unknown                   | 8        | 1.49%   |
| HP Compaq                 | 7        | 1.3%    |
| Dell Vostro               | 7        | 1.3%    |
| Lenovo ThinkCentre        | 6        | 1.12%   |
| Dell Precision            | 5        | 0.93%   |
| ASUS P8Z77-V              | 5        | 0.93%   |
| ASRock Z87                | 5        | 0.93%   |
| ASRock B450M              | 5        | 0.93%   |
| MSI MS-7A40               | 4        | 0.74%   |
| Gigabyte Z390             | 4        | 0.74%   |
| ASRock Prime              | 4        | 0.74%   |
| NEC Computers Express5800 | 3        | 0.56%   |
| HP Z620                   | 3        | 0.56%   |
| HP EliteDesk              | 3        | 0.56%   |
| EPSON DIRECT Endeavor     | 3        | 0.56%   |
| ECS G31T-M                | 3        | 0.56%   |
| ASUS P7H55-M              | 3        | 0.56%   |
| ASUS H170-PRO             | 3        | 0.56%   |
| ASRock Z370               | 3        | 0.56%   |
| ASRock X370               | 3        | 0.56%   |
| ASRock J5005-ITX          | 3        | 0.56%   |
| ASRock B550M              | 3        | 0.56%   |
| ASRock B460M              | 3        | 0.56%   |
| ASRock A300M-STX          | 3        | 0.56%   |
| Acer Aspire               | 3        | 0.56%   |
| Onkyo ONKYOPC             | 2        | 0.37%   |
| MSI MS-7D16               | 2        | 0.37%   |
| MSI MS-7C95               | 2        | 0.37%   |
| MSI MS-7C94               | 2        | 0.37%   |
| MSI MS-7C37               | 2        | 0.37%   |
| MSI MS-7C35               | 2        | 0.37%   |
| MSI MS-7C02               | 2        | 0.37%   |
| MSI MS-7B86               | 2        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 65       | 12.1%   |
| 2013    | 58       | 10.8%   |
| 2012    | 53       | 9.87%   |
| 2020    | 43       | 8.01%   |
| 2019    | 36       | 6.7%    |
| 2010    | 31       | 5.77%   |
| 2021    | 29       | 5.4%    |
| 2016    | 29       | 5.4%    |
| 2017    | 27       | 5.03%   |
| 2009    | 26       | 4.84%   |
| 2015    | 25       | 4.66%   |
| 2014    | 24       | 4.47%   |
| 2011    | 23       | 4.28%   |
| 2008    | 20       | 3.72%   |
| 2007    | 19       | 3.54%   |
| 2022    | 10       | 1.86%   |
| 2006    | 9        | 1.68%   |
| 2005    | 5        | 0.93%   |
| 2023    | 3        | 0.56%   |
| 2003    | 1        | 0.19%   |
| Unknown | 1        | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 537      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 519      | 96.47%  |
| Enabled  | 19       | 3.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 537      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 127      | 22.88%  |
| 8.01-16.0       | 120      | 21.62%  |
| 32.01-64.0      | 86       | 15.5%   |
| 4.01-8.0        | 78       | 14.05%  |
| 3.01-4.0        | 74       | 13.33%  |
| 64.01-256.0     | 28       | 5.05%   |
| 24.01-32.0      | 18       | 3.24%   |
| 1.01-2.0        | 15       | 2.7%    |
| 2.01-3.0        | 6        | 1.08%   |
| More than 256.0 | 2        | 0.36%   |
| 0.51-1.0        | 1        | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 256      | 41.63%  |
| 2.01-3.0   | 123      | 20%     |
| 4.01-8.0   | 70       | 11.38%  |
| 3.01-4.0   | 68       | 11.06%  |
| 0.51-1.0   | 51       | 8.29%   |
| 8.01-16.0  | 28       | 4.55%   |
| 16.01-24.0 | 8        | 1.3%    |
| 0.01-0.5   | 6        | 0.98%   |
| 24.01-32.0 | 4        | 0.65%   |
| 32.01-64.0 | 1        | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 233      | 41.39%  |
| 2      | 160      | 28.42%  |
| 3      | 85       | 15.1%   |
| 4      | 44       | 7.82%   |
| 5      | 22       | 3.91%   |
| 6      | 8        | 1.42%   |
| 7      | 5        | 0.89%   |
| 0      | 3        | 0.53%   |
| 11     | 1        | 0.18%   |
| 9      | 1        | 0.18%   |
| 8      | 1        | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 315      | 57.69%  |
| No        | 231      | 42.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 536      | 99.81%  |
| No        | 1        | 0.19%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 349      | 64.27%  |
| Yes       | 194      | 35.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 370      | 67.4%   |
| Yes       | 179      | 32.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Japan   | 537      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| Tokyo       | 49       | 8.48%   |
| Yokohama    | 28       | 4.84%   |
| Osaka       | 21       | 3.63%   |
| Nagoya      | 17       | 2.94%   |
| Shinjuku    | 16       | 2.77%   |
| Minato-ku   | 10       | 1.73%   |
| Tsukuba     | 9        | 1.56%   |
| Sapporo     | 9        | 1.56%   |
| Fukuoka     | 9        | 1.56%   |
| Saitama     | 7        | 1.21%   |
| Minatomirai | 7        | 1.21%   |
| Niigata     | 6        | 1.04%   |
| Miyazaki    | 6        | 1.04%   |
| Kobe        | 6        | 1.04%   |
| Takamatsu   | 5        | 0.87%   |
| Okayama     | 5        | 0.87%   |
| Kawasaki    | 5        | 0.87%   |
| Kanazawa    | 5        | 0.87%   |
| Kameido     | 5        | 0.87%   |
| Hiroshima   | 5        | 0.87%   |
| Toyokawa    | 4        | 0.69%   |
| Okazaki     | 4        | 0.69%   |
| Nagano      | 4        | 0.69%   |
| Morioka     | 4        | 0.69%   |
| Mito        | 4        | 0.69%   |
| Matsudo     | 4        | 0.69%   |
| Maebashi    | 4        | 0.69%   |
| Kyoto       | 4        | 0.69%   |
| Kumamoto    | 4        | 0.69%   |
| Koto        | 4        | 0.69%   |
| Kochi       | 4        | 0.69%   |
| Honcho      | 4        | 0.69%   |
| Gifu City   | 4        | 0.69%   |
| Chiyoda-ku  | 4        | 0.69%   |
| Chiyoda     | 4        | 0.69%   |
| Chiba       | 4        | 0.69%   |
| Umeda       | 3        | 0.52%   |
| Toyama      | 3        | 0.52%   |
| Tokushima   | 3        | 0.52%   |
| Tokorozawa  | 3        | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 174      | 275    | 17.72%  |
| WDC                         | 170      | 295    | 17.31%  |
| Samsung Electronics         | 89       | 128    | 9.06%   |
| Crucial                     | 64       | 87     | 6.52%   |
| Hitachi                     | 63       | 84     | 6.42%   |
| Toshiba                     | 57       | 76     | 5.8%    |
| SanDisk                     | 46       | 68     | 4.68%   |
| Intel                       | 37       | 51     | 3.77%   |
| A-DATA Technology           | 27       | 31     | 2.75%   |
| SPCC                        | 21       | 27     | 2.14%   |
| Kingston                    | 15       | 18     | 1.53%   |
| Phison                      | 13       | 18     | 1.32%   |
| Unknown                     | 12       | 15     | 1.22%   |
| Transcend                   | 10       | 13     | 1.02%   |
| Micron/Crucial Technology   | 10       | 14     | 1.02%   |
| HGST                        | 10       | 12     | 1.02%   |
| Silicon Motion              | 8        | 15     | 0.81%   |
| Unknown                     | 8        | 9      | 0.81%   |
| China                       | 7        | 11     | 0.71%   |
| Plextor                     | 6        | 8      | 0.61%   |
| Phison Electronics          | 6        | 10     | 0.61%   |
| OCZ                         | 6        | 6      | 0.61%   |
| Micron Technology           | 6        | 7      | 0.61%   |
| KIOXIA-EXCERIA              | 6        | 6      | 0.61%   |
| Dogfish                     | 6        | 6      | 0.61%   |
| Lexar                       | 5        | 6      | 0.51%   |
| Teclast                     | 4        | 4      | 0.41%   |
| Patriot                     | 4        | 4      | 0.41%   |
| Maxtor                      | 4        | 6      | 0.41%   |
| Green House                 | 4        | 5      | 0.41%   |
| Apacer                      | 4        | 5      | 0.41%   |
| MAXIO Technology (Hangzhou) | 3        | 3      | 0.31%   |
| KLEVV                       | 3        | 9      | 0.31%   |
| Hewlett-Packard             | 3        | 9      | 0.31%   |
| Fujitsu                     | 3        | 3      | 0.31%   |
| CFD                         | 3        | 3      | 0.31%   |
| BUFFALO                     | 3        | 4      | 0.31%   |
| Zheino                      | 2        | 2      | 0.2%    |
| Yangtze Memory Technologies | 2        | 2      | 0.2%    |
| Team                        | 2        | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                              | 18       | 1.61%   |
| Crucial CT500MX500SSD1 500GB                        | 12       | 1.08%   |
| Crucial CT240BX500SSD1 240GB                        | 12       | 1.08%   |
| Seagate ST4000DM004-2CV104 4TB                      | 10       | 0.9%    |
| Toshiba DT01ACA200 2TB                              | 9        | 0.81%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 8        | 0.72%   |
| Seagate ST2000DM001-1CH164 2TB                      | 8        | 0.72%   |
| Unknown                                             | 8        | 0.72%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 7        | 0.63%   |
| Seagate ST500DM002-1BD142 500GB                     | 7        | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB                      | 7        | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB                      | 7        | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB                      | 7        | 0.63%   |
| Crucial CT1000MX500SSD1 1TB                         | 7        | 0.63%   |
| SPCC Solid State Disk 256GB                         | 6        | 0.54%   |
| Seagate ST3500418AS 500GB                           | 6        | 0.54%   |
| Seagate ST2000DM006-2DM164 2TB                      | 6        | 0.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 6        | 0.54%   |
| Hitachi HDS721010CLA332 1TB                         | 6        | 0.54%   |
| Crucial CT525MX300SSD1 528GB                        | 6        | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 5        | 0.45%   |
| WDC WD10EADS-22M2B0 1TB                             | 5        | 0.45%   |
| WDC WD10EADS-00L5B1 1TB                             | 5        | 0.45%   |
| SPCC Solid State Disk 512GB                         | 5        | 0.45%   |
| Seagate ST31000528AS 1TB                            | 5        | 0.45%   |
| Seagate ST2000DM005-2CW102 2TB                      | 5        | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB                      | 5        | 0.45%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                  | 5        | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB                      | 5        | 0.45%   |
| Samsung SSD 860 EVO 250GB                           | 5        | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                    | 5        | 0.45%   |
| Hitachi HDS722020ALA330 2TB                         | 5        | 0.45%   |
| Hitachi HDS721050CLA362 500GB                       | 5        | 0.45%   |
| Crucial CT120BX500SSD1 120GB                        | 5        | 0.45%   |
| WDC WD5000AZLX-60K2TA0 500GB                        | 4        | 0.36%   |
| WDC WD20EZAZ-00GGJB0 2TB                            | 4        | 0.36%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 4        | 0.36%   |
| WDC WD10EADS-00M2B0 1TB                             | 4        | 0.36%   |
| SPCC Solid State Disk 240GB                         | 4        | 0.36%   |
| Seagate ST9500325AS 500GB                           | 4        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 170      | 267    | 35.27%  |
| WDC                 | 150      | 246    | 31.12%  |
| Hitachi             | 62       | 83     | 12.86%  |
| Toshiba             | 50       | 67     | 10.37%  |
| Samsung Electronics | 21       | 24     | 4.36%   |
| HGST                | 10       | 12     | 2.07%   |
| Maxtor              | 4        | 6      | 0.83%   |
| Hewlett-Packard     | 3        | 9      | 0.62%   |
| Fujitsu             | 3        | 3      | 0.62%   |
| MARVELL             | 2        | 4      | 0.41%   |
| External            | 2        | 2      | 0.41%   |
| USB3.0              | 1        | 1      | 0.21%   |
| StoreJet            | 1        | 1      | 0.21%   |
| SABRENT             | 1        | 1      | 0.21%   |
| Quantum             | 1        | 1      | 0.21%   |
| KESU                | 1        | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 58       | 78     | 16.2%   |
| Samsung Electronics | 45       | 62     | 12.57%  |
| SanDisk             | 31       | 42     | 8.66%   |
| A-DATA Technology   | 24       | 27     | 6.7%    |
| Intel               | 22       | 27     | 6.15%   |
| WDC                 | 21       | 30     | 5.87%   |
| SPCC                | 19       | 25     | 5.31%   |
| Kingston            | 13       | 16     | 3.63%   |
| Transcend           | 9        | 12     | 2.51%   |
| Unknown             | 8        | 9      | 2.23%   |
| Toshiba             | 7        | 8      | 1.96%   |
| China               | 7        | 11     | 1.96%   |
| Plextor             | 6        | 8      | 1.68%   |
| OCZ                 | 6        | 6      | 1.68%   |
| Dogfish             | 6        | 6      | 1.68%   |
| Micron Technology   | 4        | 5      | 1.12%   |
| Lexar               | 4        | 5      | 1.12%   |
| Green House         | 4        | 5      | 1.12%   |
| Apacer              | 4        | 5      | 1.12%   |
| Unknown             | 3        | 3      | 0.84%   |
| Teclast             | 3        | 3      | 0.84%   |
| Seagate             | 3        | 5      | 0.84%   |
| KLEVV               | 3        | 9      | 0.84%   |
| KIOXIA-EXCERIA      | 3        | 3      | 0.84%   |
| CFD                 | 3        | 3      | 0.84%   |
| BUFFALO             | 3        | 4      | 0.84%   |
| Team                | 2        | 2      | 0.56%   |
| SUNEAST             | 2        | 2      | 0.56%   |
| Patriot             | 2        | 2      | 0.56%   |
| KingDian            | 2        | 3      | 0.56%   |
| Hanye               | 2        | 2      | 0.56%   |
| Corsair             | 2        | 2      | 0.56%   |
| Biostar             | 2        | 2      | 0.56%   |
| Apple               | 2        | 2      | 0.56%   |
| AEGO                | 2        | 2      | 0.56%   |
| Zheino              | 1        | 1      | 0.28%   |
| XSTAR               | 1        | 1      | 0.28%   |
| TO Exter            | 1        | 1      | 0.28%   |
| TCSUNBOW            | 1        | 1      | 0.28%   |
| SATA3 51            | 1        | 2      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 372      | 728    | 46.21%  |
| SSD     | 289      | 459    | 35.9%   |
| NVMe    | 131      | 215    | 16.27%  |
| Unknown | 12       | 21     | 1.49%   |
| MMC     | 1        | 1      | 0.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 492      | 1158   | 74.89%  |
| NVMe | 131      | 215    | 19.94%  |
| SAS  | 33       | 50     | 5.02%   |
| MMC  | 1        | 1      | 0.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 367      | 653    | 51.33%  |
| 0.51-1.0   | 154      | 230    | 21.54%  |
| 1.01-2.0   | 102      | 148    | 14.27%  |
| 3.01-4.0   | 37       | 58     | 5.17%   |
| 4.01-10.0  | 29       | 60     | 4.06%   |
| 2.01-3.0   | 23       | 35     | 3.22%   |
| 10.01-20.0 | 3        | 3      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 147      | 25.79%  |
| 251-500        | 94       | 16.49%  |
| 501-1000       | 75       | 13.16%  |
| More than 3000 | 59       | 10.35%  |
| 1001-2000      | 50       | 8.77%   |
| 1-20           | 44       | 7.72%   |
| 2001-3000      | 33       | 5.79%   |
| 51-100         | 33       | 5.79%   |
| Unknown        | 27       | 4.74%   |
| 21-50          | 8        | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 231      | 39.09%  |
| 21-50          | 83       | 14.04%  |
| 101-250        | 59       | 9.98%   |
| 51-100         | 53       | 8.97%   |
| 251-500        | 39       | 6.6%    |
| 501-1000       | 38       | 6.43%   |
| 1001-2000      | 29       | 4.91%   |
| Unknown        | 27       | 4.57%   |
| More than 3000 | 22       | 3.72%   |
| 2001-3000      | 10       | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD10EADS-22M2B0 1TB            | 5        | 5      | 7.94%   |
| SanDisk SD6SF1M128G1022I 128GB SSD | 5        | 5      | 7.94%   |
| Seagate ST9500325AS 500GB          | 3        | 4      | 4.76%   |
| Seagate ST2000DM001-1CH164 2TB     | 2        | 2      | 3.17%   |
| Hitachi HDS721010CLA332 1TB        | 2        | 2      | 3.17%   |
| WDC WD5000LPLX-66ZNTT0 500GB       | 1        | 1      | 1.59%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1        | 1      | 1.59%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1        | 1      | 1.59%   |
| WDC WD3200LPCX-24C6HT0 320GB       | 1        | 1      | 1.59%   |
| WDC WD30EZRX-00DC0B0 3TB           | 1        | 2      | 1.59%   |
| WDC WD30EZRX-00D8PB0 3TB           | 1        | 1      | 1.59%   |
| WDC WD25EZRX-00MMMB0 2TB           | 1        | 1      | 1.59%   |
| WDC WD10EALX-009BA0 1TB            | 1        | 1      | 1.59%   |
| WDC WD10EADS-00L5B1 1TB            | 1        | 1      | 1.59%   |
| WDC WD10EACS-00D6B0 1TB            | 1        | 2      | 1.59%   |
| Transcend TS240GSSD220S 240GB      | 1        | 1      | 1.59%   |
| Toshiba MQ01ABD100 1TB             | 1        | 1      | 1.59%   |
| SPCC Solid State DiskB28 128GB     | 1        | 1      | 1.59%   |
| SPCC Solid State Disk 512GB        | 1        | 2      | 1.59%   |
| Seagate ST9320320AS 320GB          | 1        | 1      | 1.59%   |
| Seagate ST3500418AS 500GB          | 1        | 2      | 1.59%   |
| Seagate ST3320820AS 320GB          | 1        | 1      | 1.59%   |
| Seagate ST3250310AS 250GB          | 1        | 2      | 1.59%   |
| Seagate ST3120026A 120GB           | 1        | 1      | 1.59%   |
| Seagate ST31000528AS 1TB           | 1        | 1      | 1.59%   |
| Seagate ST31000333AS 1TB           | 1        | 1      | 1.59%   |
| Seagate ST3000VM002-1ET166 3TB     | 1        | 1      | 1.59%   |
| Seagate ST250DM000-1BD141 250GB    | 1        | 1      | 1.59%   |
| Seagate ST2000LX001-1RG174 2TB     | 1        | 1      | 1.59%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 1.59%   |
| Seagate ST2000DX002-2DV164 2TB     | 1        | 1      | 1.59%   |
| Seagate ST2000DX001-1NS164 2TB     | 1        | 1      | 1.59%   |
| Seagate ST2000DM001-1ER164 2TB     | 1        | 1      | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 1.59%   |
| Seagate ST1000DM003-1ER162 1TB     | 1        | 1      | 1.59%   |
| Samsung Electronics HD160HJ 160GB  | 1        | 1      | 1.59%   |
| Kingston SV300S37A120G 120GB SSD   | 1        | 1      | 1.59%   |
| Intel SSDSCKJW120H6 120GB          | 1        | 1      | 1.59%   |
| Hitachi HTS727575A9E364 752GB      | 1        | 1      | 1.59%   |
| Hitachi HTS541080G9SA00 80GB       | 1        | 1      | 1.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 24     | 32.79%  |
| WDC                 | 15       | 17     | 24.59%  |
| Hitachi             | 9        | 11     | 14.75%  |
| SanDisk             | 5        | 5      | 8.2%    |
| SPCC                | 2        | 3      | 3.28%   |
| A-DATA Technology   | 2        | 2      | 3.28%   |
| Transcend           | 1        | 1      | 1.64%   |
| Toshiba             | 1        | 1      | 1.64%   |
| Samsung Electronics | 1        | 1      | 1.64%   |
| Kingston            | 1        | 1      | 1.64%   |
| Intel               | 1        | 1      | 1.64%   |
| Crucial             | 1        | 1      | 1.64%   |
| Corsair             | 1        | 1      | 1.64%   |
| C300-CTF            | 1        | 1      | 1.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 24     | 43.48%  |
| WDC                 | 15       | 17     | 32.61%  |
| Hitachi             | 9        | 11     | 19.57%  |
| Toshiba             | 1        | 1      | 2.17%   |
| Samsung Electronics | 1        | 1      | 2.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 39       | 54     | 72.22%  |
| SSD  | 15       | 16     | 27.78%  |

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
| Detected | 338      | 922    | 58.18%  |
| Works    | 194      | 432    | 33.39%  |
| Malfunc  | 49       | 70     | 8.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 368      | 46.82%  |
| AMD                              | 159      | 20.23%  |
| ASMedia Technology               | 43       | 5.47%   |
| Samsung Electronics              | 33       | 4.2%    |
| SanDisk                          | 25       | 3.18%   |
| Marvell Technology Group         | 23       | 2.93%   |
| Phison Electronics               | 22       | 2.8%    |
| JMicron Technology               | 20       | 2.54%   |
| Micron/Crucial Technology        | 17       | 2.16%   |
| Silicon Motion                   | 12       | 1.53%   |
| VIA Technologies                 | 10       | 1.27%   |
| Nvidia                           | 7        | 0.89%   |
| Broadcom / LSI                   | 6        | 0.76%   |
| ADATA Technology                 | 5        | 0.64%   |
| MAXIO Technology (Hangzhou)      | 4        | 0.51%   |
| Seagate Technology               | 3        | 0.38%   |
| Micron Technology                | 3        | 0.38%   |
| KIOXIA                           | 3        | 0.38%   |
| Kingston Technology Company      | 3        | 0.38%   |
| Adaptec                          | 3        | 0.38%   |
| Yangtze Memory Technologies      | 2        | 0.25%   |
| SK hynix                         | 2        | 0.25%   |
| Silicon Image                    | 2        | 0.25%   |
| Realtek Semiconductor            | 2        | 0.25%   |
| HighPoint Technologies           | 2        | 0.25%   |
| ULi Electronics                  | 1        | 0.13%   |
| Toshiba America Info Systems     | 1        | 0.13%   |
| Solidigm                         | 1        | 0.13%   |
| Silicon Integrated Systems [SiS] | 1        | 0.13%   |
| Promise Technology               | 1        | 0.13%   |
| LSI Logic / Symbios Logic        | 1        | 0.13%   |
| Loongson Technology              | 1        | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 92       | 9.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 46       | 4.65%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 38       | 3.84%   |
| AMD 400 Series Chipset SATA Controller                                                  | 38       | 3.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 32       | 3.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 28       | 2.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 28       | 2.83%   |
| AMD 500 Series Chipset SATA Controller                                                  | 25       | 2.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 24       | 2.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 21       | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 21       | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20       | 2.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 19       | 1.92%   |
| Intel SATA Controller [RAID mode]                                                       | 17       | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 16       | 1.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15       | 1.52%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 14       | 1.42%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 13       | 1.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 12       | 1.21%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 11       | 1.11%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 10       | 1.01%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 10       | 1.01%   |
| AMD FCH IDE Controller                                                                  | 10       | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 9        | 0.91%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 0.91%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 0.91%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 8        | 0.81%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 8        | 0.81%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 8        | 0.81%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 0.81%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 8        | 0.81%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 8        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 0.81%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 7        | 0.71%   |
| Phison E12 NVMe Controller                                                              | 7        | 0.71%   |
| JMicron JMB368 IDE controller                                                           | 7        | 0.71%   |
| Intel SSD 660P Series                                                                   | 7        | 0.71%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 7        | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 431      | 57.7%   |
| IDE  | 134      | 17.94%  |
| NVMe | 131      | 17.54%  |
| RAID | 39       | 5.22%   |
| SAS  | 6        | 0.8%    |
| SCSI | 6        | 0.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 369      | 68.72%  |
| AMD      | 167      | 31.1%   |
| Loongson | 1        | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 14       | 2.58%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 10       | 1.85%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 9        | 1.66%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 9        | 1.66%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 1.48%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 7        | 1.29%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 6        | 1.11%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 5        | 0.92%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 0.92%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 5        | 0.92%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 0.92%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 5        | 0.92%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 5        | 0.92%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 0.92%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 5        | 0.92%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 5        | 0.92%   |
| AMD Athlon 200GE with Radeon Vega Graphics  | 5        | 0.92%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 4        | 0.74%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 0.74%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 4        | 0.74%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 4        | 0.74%   |
| Intel Core i5-4570TE CPU @ 2.70GHz          | 4        | 0.74%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 0.74%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 4        | 0.74%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 0.74%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 4        | 0.74%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 0.74%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 4        | 0.74%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 4        | 0.74%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 0.74%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 4        | 0.74%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 4        | 0.74%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 0.74%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 3        | 0.55%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 0.55%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 0.55%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 3        | 0.55%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.55%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 3        | 0.55%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 3        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 92       | 17.07%  |
| Intel Core i5           | 82       | 15.21%  |
| AMD Ryzen 5             | 43       | 7.98%   |
| Intel Core i3           | 39       | 7.24%   |
| AMD Ryzen 7             | 37       | 6.86%   |
| Intel Xeon              | 32       | 5.94%   |
| Intel Core 2 Duo        | 21       | 3.9%    |
| Intel Celeron           | 21       | 3.9%    |
| Other                   | 17       | 3.15%   |
| Intel Core 2 Quad       | 16       | 2.97%   |
| AMD Ryzen 9             | 13       | 2.41%   |
| Intel Pentium           | 11       | 2.04%   |
| Intel Core 2            | 10       | 1.86%   |
| AMD Athlon              | 10       | 1.86%   |
| Intel Core i9           | 9        | 1.67%   |
| AMD A10                 | 9        | 1.67%   |
| AMD Ryzen 3             | 7        | 1.3%    |
| AMD Phenom II X4        | 6        | 1.11%   |
| AMD FX                  | 6        | 1.11%   |
| Intel Pentium 4         | 5        | 0.93%   |
| AMD Athlon 64 X2        | 5        | 0.93%   |
| AMD A8                  | 5        | 0.93%   |
| Intel Pentium Gold      | 4        | 0.74%   |
| Intel Pentium Dual-Core | 4        | 0.74%   |
| Intel Pentium Silver    | 3        | 0.56%   |
| Intel Atom              | 3        | 0.56%   |
| AMD Sempron             | 2        | 0.37%   |
| AMD Ryzen Threadripper  | 2        | 0.37%   |
| AMD Phenom II X6        | 2        | 0.37%   |
| AMD Phenom              | 2        | 0.37%   |
| AMD Athlon II X4        | 2        | 0.37%   |
| AMD Athlon II X2        | 2        | 0.37%   |
| AMD Athlon Dual Core    | 2        | 0.37%   |
| AMD Athlon 64           | 2        | 0.37%   |
| AMD A6                  | 2        | 0.37%   |
| AMD A4                  | 2        | 0.37%   |
| AMD A12                 | 2        | 0.37%   |
| Intel Pentium Dual      | 1        | 0.19%   |
| Intel Pentium D         | 1        | 0.19%   |
| Intel Core 2 Extreme    | 1        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 203      | 37.59%  |
| 2      | 145      | 26.85%  |
| 6      | 85       | 15.74%  |
| 8      | 59       | 10.93%  |
| 1      | 13       | 2.41%   |
| 16     | 11       | 2.04%   |
| 12     | 8        | 1.48%   |
| 10     | 5        | 0.93%   |
| 3      | 4        | 0.74%   |
| 24     | 2        | 0.37%   |
| 20     | 2        | 0.37%   |
| 14     | 2        | 0.37%   |
| 32     | 1        | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 531      | 98.88%  |
| 2      | 6        | 1.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 326      | 60.48%  |
| 1      | 212      | 39.33%  |
| 8      | 1        | 0.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 532      | 98.7%   |
| Unknown        | 4        | 0.74%   |
| 32-bit         | 3        | 0.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 148      | 26.48%  |
| 0x306c3    | 39       | 6.98%   |
| 0x306a9    | 36       | 6.44%   |
| 0x08701021 | 25       | 4.47%   |
| 0x1067a    | 24       | 4.29%   |
| 0x206a7    | 21       | 3.76%   |
| 0x906ea    | 20       | 3.58%   |
| 0x506e3    | 17       | 3.04%   |
| 0x906e9    | 11       | 1.97%   |
| 0x906ed    | 9        | 1.61%   |
| 0x106e5    | 8        | 1.43%   |
| 0x0800820d | 8        | 1.43%   |
| 0x06003106 | 8        | 1.43%   |
| 0x306f2    | 6        | 1.07%   |
| 0x06001119 | 6        | 1.07%   |
| 0x010000db | 6        | 1.07%   |
| 0xa0655    | 5        | 0.89%   |
| 0x6fb      | 5        | 0.89%   |
| 0x206d7    | 5        | 0.89%   |
| 0x0a50000c | 5        | 0.89%   |
| 0x0a201016 | 5        | 0.89%   |
| 0x08108109 | 5        | 0.89%   |
| 0xa0653    | 4        | 0.72%   |
| 0x706a1    | 4        | 0.72%   |
| 0x6f6      | 4        | 0.72%   |
| 0x50654    | 4        | 0.72%   |
| 0x306e4    | 4        | 0.72%   |
| 0x10676    | 4        | 0.72%   |
| 0x08600106 | 4        | 0.72%   |
| 0x08101016 | 4        | 0.72%   |
| 0x0810100b | 4        | 0.72%   |
| 0x08001138 | 4        | 0.72%   |
| 0x010000c8 | 4        | 0.72%   |
| 0x906eb    | 3        | 0.54%   |
| 0x206c2    | 3        | 0.54%   |
| 0x20655    | 3        | 0.54%   |
| 0x10677    | 3        | 0.54%   |
| 0x0a50000d | 3        | 0.54%   |
| 0x08701013 | 3        | 0.54%   |
| 0x0600063e | 3        | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 64       | 11.87%  |
| KabyLake         | 63       | 11.69%  |
| IvyBridge        | 47       | 8.72%   |
| Zen 2            | 43       | 7.98%   |
| Penryn           | 37       | 6.86%   |
| SandyBridge      | 30       | 5.57%   |
| Skylake          | 29       | 5.38%   |
| Zen 3            | 24       | 4.45%   |
| Zen              | 23       | 4.27%   |
| Zen+             | 21       | 3.9%    |
| Core             | 18       | 3.34%   |
| K10              | 16       | 2.97%   |
| CometLake        | 15       | 2.78%   |
| Nehalem          | 13       | 2.41%   |
| Westmere         | 12       | 2.23%   |
| Unknown          | 11       | 2.04%   |
| K8 Hammer        | 10       | 1.86%   |
| Piledriver       | 9        | 1.67%   |
| Steamroller      | 8        | 1.48%   |
| Alderlake Hybrid | 8        | 1.48%   |
| NetBurst         | 7        | 1.3%    |
| Silvermont       | 6        | 1.11%   |
| Goldmont plus    | 5        | 0.93%   |
| Bulldozer        | 4        | 0.74%   |
| K10 Llano        | 3        | 0.56%   |
| Jaguar           | 3        | 0.56%   |
| Bonnell          | 3        | 0.56%   |
| Excavator        | 2        | 0.37%   |
| Tremont          | 1        | 0.19%   |
| Icelake          | 1        | 0.19%   |
| Goldmont         | 1        | 0.19%   |
| Broadwell        | 1        | 0.19%   |
| Bobcat           | 1        | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 217      | 38%     |
| AMD                        | 183      | 32.05%  |
| Intel                      | 168      | 29.42%  |
| VIA Technologies           | 1        | 0.18%   |
| Matrox Electronics Systems | 1        | 0.18%   |
| Loongson Technology        | 1        | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 24       | 4.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 21       | 3.54%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 15       | 2.53%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 14       | 2.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 14       | 2.36%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 13       | 2.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13       | 2.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12       | 2.02%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12       | 2.02%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 11       | 1.85%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 11       | 1.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11       | 1.85%   |
| Intel HD Graphics 630                                                                    | 10       | 1.69%   |
| Intel HD Graphics 530                                                                    | 10       | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10       | 1.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 9        | 1.52%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 9        | 1.52%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8        | 1.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7        | 1.18%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 7        | 1.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7        | 1.18%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 7        | 1.18%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6        | 1.01%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 6        | 1.01%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 6        | 1.01%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 0.84%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 5        | 0.84%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 5        | 0.84%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 5        | 0.84%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 5        | 0.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 0.84%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5        | 0.84%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 5        | 0.84%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 5        | 0.84%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 5        | 0.84%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 4        | 0.67%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 4        | 0.67%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 0.67%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 4        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| 1 x Nvidia                | 196      | 36.23%  |
| 1 x AMD                   | 166      | 30.68%  |
| 1 x Intel                 | 148      | 27.36%  |
| 2 x AMD                   | 6        | 1.11%   |
| AMD + Nvidia              | 6        | 1.11%   |
| 2 x Nvidia                | 5        | 0.92%   |
| Intel + Nvidia            | 5        | 0.92%   |
| Intel + 2 x Nvidia        | 2        | 0.37%   |
| Other                     | 1        | 0.18%   |
| 1 x VIA                   | 1        | 0.18%   |
| Intel + 2 x AMD           | 1        | 0.18%   |
| Intel + AMD + 1 x Nvidia  | 1        | 0.18%   |
| Intel + AMD               | 1        | 0.18%   |
| AMD + Matrox              | 1        | 0.18%   |
| AMD + Loongson Technology | 1        | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 418      | 76.28%  |
| Proprietary | 114      | 20.8%   |
| Unknown     | 16       | 2.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 219      | 39.39%  |
| 0.01-0.5   | 79       | 14.21%  |
| 1.01-2.0   | 72       | 12.95%  |
| 0.51-1.0   | 69       | 12.41%  |
| 3.01-4.0   | 44       | 7.91%   |
| 7.01-8.0   | 34       | 6.12%   |
| 5.01-6.0   | 17       | 3.06%   |
| 8.01-16.0  | 15       | 2.7%    |
| 16.01-24.0 | 5        | 0.9%    |
| 2.01-3.0   | 2        | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 58       | 10.03%  |
| IOD                  | 47       | 8.13%   |
| Goldstar             | 41       | 7.09%   |
| BenQ                 | 39       | 6.75%   |
| Mitsubishi           | 33       | 5.71%   |
| Iiyama               | 32       | 5.54%   |
| Acer                 | 30       | 5.19%   |
| Hewlett-Packard      | 24       | 4.15%   |
| Philips              | 23       | 3.98%   |
| Eizo                 | 22       | 3.81%   |
| Unknown              | 17       | 2.94%   |
| Sharp                | 17       | 2.94%   |
| Samsung Electronics  | 15       | 2.6%    |
| NEC Computers        | 15       | 2.6%    |
| Ancor Communications | 15       | 2.6%    |
| AOC                  | 14       | 2.42%   |
| Sony                 | 9        | 1.56%   |
| Lenovo               | 7        | 1.21%   |
| Idek Iiyama          | 7        | 1.21%   |
| ASUSTek Computer     | 7        | 1.21%   |
| ViewSonic            | 6        | 1.04%   |
| Panasonic            | 6        | 1.04%   |
| LG Electronics       | 6        | 1.04%   |
| Fujitsu              | 6        | 1.04%   |
| Toshiba              | 5        | 0.87%   |
| Onkyo                | 4        | 0.69%   |
| MSI                  | 4        | 0.69%   |
| Hitachi              | 4        | 0.69%   |
| Unknown              | 4        | 0.69%   |
| Unknown (XXX)        | 3        | 0.52%   |
| PTF                  | 3        | 0.52%   |
| ___                  | 2        | 0.35%   |
| SKY                  | 2        | 0.35%   |
| Pixio                | 2        | 0.35%   |
| Orion                | 2        | 0.35%   |
| MPI                  | 2        | 0.35%   |
| LYC                  | 2        | 0.35%   |
| INNOCN               | 2        | 0.35%   |
| HKM                  | 2        | 0.35%   |
| BUFFALO              | 2        | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 28E850 AOC0CCD 2560x1440 480x270mm 21.7-inch                     | 5        | 0.8%    |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch          | 4        | 0.64%   |
| Iiyama PL2290 IVM562C 1920x1080 476x268mm 21.5-inch                  | 4        | 0.64%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 4        | 0.64%   |
| Unknown                                                              | 4        | 0.64%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                   | 3        | 0.48%   |
| Mitsubishi MDT241WG MEL478E 1920x1200 520x320mm 24.0-inch            | 3        | 0.48%   |
| IOD EX-LD2071T IOD150D 1920x1080 458x258mm 20.7-inch                 | 3        | 0.48%   |
| Iiyama PL2390 IVM562D 1920x1080 509x286mm 23.0-inch                  | 3        | 0.48%   |
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                 | 3        | 0.48%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 3        | 0.48%   |
| Fujitsu VL-200SSWL FUJ4911 1600x900 442x249mm 20.0-inch              | 3        | 0.48%   |
| Dell U2410 DELF016 1920x1200 520x320mm 24.0-inch                     | 3        | 0.48%   |
| Dell S2421HS DEL41F4 1920x1080 530x300mm 24.0-inch                   | 3        | 0.48%   |
| Dell E177FP DELA023 1280x1024 340x270mm 17.1-inch                    | 3        | 0.48%   |
| ASUSTek Computer VZ239 AUS23CC 1920x1080 509x286mm 23.0-inch         | 3        | 0.48%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch     | 3        | 0.48%   |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                    | 3        | 0.48%   |
| Acer B193 ACR001D 1280x1024 376x301mm 19.0-inch                      | 3        | 0.48%   |
| ___ LCDTV16 ___9000 1360x768                                         | 2        | 0.32%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch           | 2        | 0.32%   |
| Unknown LCD Monitor Mitsubishi RDT233WLM 1920x1080                   | 2        | 0.32%   |
| SKY TV-monitor SKY1901 3840x2160 1210x680mm 54.6-inch                | 2        | 0.32%   |
| Sharp LCD SHP104D 1920x1080 820x460mm 37.0-inch                      | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch | 2        | 0.32%   |
| Philips PHL 328P6VU PHL0927 3840x2160 698x393mm 31.5-inch            | 2        | 0.32%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch              | 2        | 0.32%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 2        | 0.32%   |
| Onkyo LA21TW ONK5060 1920x1080 478x269mm 21.6-inch                   | 2        | 0.32%   |
| Mitsubishi RDT234WLM MEL4887 1920x1080 509x286mm 23.0-inch           | 2        | 0.32%   |
| Mitsubishi RDT195V MEL4698 1280x1024 376x301mm 19.0-inch             | 2        | 0.32%   |
| Mitsubishi RDT194S MEL4685 1280x1024 376x301mm 19.0-inch             | 2        | 0.32%   |
| Mitsubishi RDT1714VM MEL4764 1280x1024 338x270mm 17.0-inch           | 2        | 0.32%   |
| Mitsubishi MEL-TV(WXGA) MEL332E 1920x540                             | 2        | 0.32%   |
| LYC L2106 LYC0001 1920x1080 480x260mm 21.5-inch                      | 2        | 0.32%   |
| IOD LCD-RDT242XP IOD1891 1920x1080 527x296mm 23.8-inch               | 2        | 0.32%   |
| IOD LCD-MF221X IOD1685 1920x1080 476x268mm 21.5-inch                 | 2        | 0.32%   |
| IOD LCD-AD173SE IOD11D7 1280x1024 337x270mm 17.0-inch                | 2        | 0.32%   |
| IOD KH2750V-UHD IOD1B2A 3840x2160 598x336mm 27.0-inch                | 2        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 264      | 45.83%  |
| 3840x2160 (4K)     | 60       | 10.42%  |
| 1280x1024 (SXGA)   | 56       | 9.72%   |
| 2560x1440 (QHD)    | 38       | 6.6%    |
| 1920x1200 (WUXGA)  | 29       | 5.03%   |
| 1680x1050 (WSXGA+) | 17       | 2.95%   |
| Unknown            | 16       | 2.78%   |
| 1440x900 (WXGA+)   | 15       | 2.6%    |
| 1920x540           | 10       | 1.74%   |
| 1600x1200          | 9        | 1.56%   |
| 1600x900 (HD+)     | 6        | 1.04%   |
| 1360x768           | 6        | 1.04%   |
| 1024x768 (XGA)     | 6        | 1.04%   |
| 3840x1080          | 5        | 0.87%   |
| 2560x1080          | 5        | 0.87%   |
| 1400x1050          | 4        | 0.69%   |
| 1366x768 (WXGA)    | 4        | 0.69%   |
| 3440x1440          | 3        | 0.52%   |
| 1280x720 (HD)      | 3        | 0.52%   |
| 3520x1080          | 2        | 0.35%   |
| 3200x1200          | 2        | 0.35%   |
| 1360x765           | 2        | 0.35%   |
| 800x480            | 1        | 0.17%   |
| 7680x2160          | 1        | 0.17%   |
| 7360x1200          | 1        | 0.17%   |
| 640x480            | 1        | 0.17%   |
| 5760x1200          | 1        | 0.17%   |
| 5440x1200          | 1        | 0.17%   |
| 4480x1080          | 1        | 0.17%   |
| 3200x2160          | 1        | 0.17%   |
| 3200x1080          | 1        | 0.17%   |
| 2560x1600          | 1        | 0.17%   |
| 2560x1024          | 1        | 0.17%   |
| 2048x1152          | 1        | 0.17%   |
| 1792x1344          | 1        | 0.17%   |
| 1280x960           | 1        | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 83       | 14.59%  |
| 21      | 76       | 13.36%  |
| 23      | 74       | 13.01%  |
| 24      | 73       | 12.83%  |
| Unknown | 73       | 12.83%  |
| 19      | 38       | 6.68%   |
| 17      | 28       | 4.92%   |
| 31      | 21       | 3.69%   |
| 20      | 21       | 3.69%   |
| 22      | 9        | 1.58%   |
| 18      | 8        | 1.41%   |
| 15      | 8        | 1.41%   |
| 37      | 6        | 1.05%   |
| 34      | 6        | 1.05%   |
| 72      | 5        | 0.88%   |
| 54      | 5        | 0.88%   |
| 84      | 4        | 0.7%    |
| 42      | 4        | 0.7%    |
| 43      | 3        | 0.53%   |
| 40      | 3        | 0.53%   |
| 32      | 3        | 0.53%   |
| 14      | 3        | 0.53%   |
| 49      | 2        | 0.35%   |
| 30      | 2        | 0.35%   |
| 26      | 2        | 0.35%   |
| 25      | 2        | 0.35%   |
| 74      | 1        | 0.18%   |
| 64      | 1        | 0.18%   |
| 48      | 1        | 0.18%   |
| 39      | 1        | 0.18%   |
| 35      | 1        | 0.18%   |
| 13      | 1        | 0.18%   |
| 10      | 1        | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 219      | 39.11%  |
| 401-500     | 123      | 21.96%  |
| Unknown     | 73       | 13.04%  |
| 301-350     | 33       | 5.89%   |
| 601-700     | 32       | 5.71%   |
| 351-400     | 30       | 5.36%   |
| 801-900     | 11       | 1.96%   |
| 1501-2000   | 10       | 1.79%   |
| 1001-1500   | 10       | 1.79%   |
| 701-800     | 9        | 1.61%   |
| 901-1000    | 6        | 1.07%   |
| 201-300     | 4        | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 337      | 62.18%  |
| 16/10   | 61       | 11.25%  |
| Unknown | 60       | 11.07%  |
| 5/4     | 49       | 9.04%   |
| 4/3     | 17       | 3.14%   |
| 21/9    | 7        | 1.29%   |
| 32/9    | 6        | 1.11%   |
| 1.00    | 2        | 0.37%   |
| 6/5     | 1        | 0.18%   |
| 3/2     | 1        | 0.18%   |
| 1.96    | 1        | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 162      | 28.57%  |
| 151-200        | 98       | 17.28%  |
| 301-350        | 83       | 14.64%  |
| Unknown        | 73       | 12.87%  |
| 251-300        | 38       | 6.7%    |
| 351-500        | 34       | 6%      |
| 141-150        | 30       | 5.29%   |
| More than 1000 | 18       | 3.17%   |
| 501-1000       | 16       | 2.82%   |
| 101-110        | 9        | 1.59%   |
| 91-100         | 2        | 0.35%   |
| 71-80          | 1        | 0.18%   |
| 41-50          | 1        | 0.18%   |
| 131-140        | 1        | 0.18%   |
| 121-130        | 1        | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 308      | 55.8%   |
| 101-120 | 110      | 19.93%  |
| Unknown | 73       | 13.22%  |
| 121-160 | 33       | 5.98%   |
| 161-240 | 16       | 2.9%    |
| 1-50    | 12       | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 454      | 82.4%   |
| 2     | 68       | 12.34%  |
| 0     | 21       | 3.81%   |
| 3     | 5        | 0.91%   |
| 4     | 2        | 0.36%   |
| 6     | 1        | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 314      | 42.26%  |
| Intel                            | 239      | 32.17%  |
| Qualcomm Atheros                 | 42       | 5.65%   |
| Broadcom                         | 30       | 4.04%   |
| BUFFALO                          | 18       | 2.42%   |
| TP-Link                          | 15       | 2.02%   |
| PLANEX                           | 12       | 1.62%   |
| Marvell Technology Group         | 10       | 1.35%   |
| MediaTek                         | 8        | 1.08%   |
| Nvidia                           | 6        | 0.81%   |
| Elecom                           | 5        | 0.67%   |
| ASIX Electronics                 | 5        | 0.67%   |
| VIA Technologies                 | 4        | 0.54%   |
| Broadcom Limited                 | 4        | 0.54%   |
| Aquantia                         | 4        | 0.54%   |
| Logitec                          | 2        | 0.27%   |
| Huawei Technologies              | 2        | 0.27%   |
| Wilocity                         | 1        | 0.13%   |
| Wacom                            | 1        | 0.13%   |
| vivo                             | 1        | 0.13%   |
| ULi Electronics                  | 1        | 0.13%   |
| U-Blox                           | 1        | 0.13%   |
| Silicon Integrated Systems [SiS] | 1        | 0.13%   |
| Samsung Electronics              | 1        | 0.13%   |
| Ralink Technology                | 1        | 0.13%   |
| Qualcomm Atheros Communications  | 1        | 0.13%   |
| Padix (Rockfire)                 | 1        | 0.13%   |
| OPPO Electronics                 | 1        | 0.13%   |
| NetGear                          | 1        | 0.13%   |
| Netchip Technology               | 1        | 0.13%   |
| NEC Computers                    | 1        | 0.13%   |
| Microchip Technology             | 1        | 0.13%   |
| LSI                              | 1        | 0.13%   |
| Loongson Technology              | 1        | 0.13%   |
| JMicron Technology               | 1        | 0.13%   |
| Edimax Technology                | 1        | 0.13%   |
| Corega K.K.                      | 1        | 0.13%   |
| ASUSTek Computer                 | 1        | 0.13%   |
| ADMtek                           | 1        | 0.13%   |
| 3Com                             | 1        | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 252      | 30.22%  |
| Realtek RTL8125 2.5GbE Controller                                 | 35       | 4.2%    |
| Intel Ethernet Connection (2) I219-V                              | 35       | 4.2%    |
| Intel I211 Gigabit Network Connection                             | 26       | 3.12%   |
| Intel Wi-Fi 6 AX200                                               | 25       | 3%      |
| Intel Ethernet Connection (7) I219-V                              | 22       | 2.64%   |
| Intel Ethernet Connection I217-V                                  | 15       | 1.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 14       | 1.68%   |
| Intel 82579V Gigabit Network Connection                           | 14       | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 13       | 1.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 11       | 1.32%   |
| Intel Ethernet Controller I225-V                                  | 11       | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 10       | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 1.08%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 8        | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.84%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 7        | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7        | 0.84%   |
| Intel 82574L Gigabit Network Connection                           | 7        | 0.84%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6        | 0.72%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 0.72%   |
| BUFFALO 802.11ac WLAN Adapter                                     | 6        | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5        | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 5        | 0.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5        | 0.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5        | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 5        | 0.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4        | 0.48%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.48%   |
| Intel Ethernet Connection (12) I219-V                             | 4        | 0.48%   |
| Intel Ethernet Connection (11) I219-V                             | 4        | 0.48%   |
| BUFFALO WLI-UC-GNM Wireless LAN Adapter [Ralink RT8070]           | 4        | 0.48%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3        | 0.36%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3        | 0.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 76       | 36.19%  |
| Realtek Semiconductor           | 38       | 18.1%   |
| Qualcomm Atheros                | 22       | 10.48%  |
| BUFFALO                         | 18       | 8.57%   |
| TP-Link                         | 15       | 7.14%   |
| PLANEX                          | 12       | 5.71%   |
| MediaTek                        | 8        | 3.81%   |
| Broadcom                        | 7        | 3.33%   |
| Elecom                          | 4        | 1.9%    |
| Logitec                         | 2        | 0.95%   |
| Wilocity                        | 1        | 0.48%   |
| Wacom                           | 1        | 0.48%   |
| Ralink Technology               | 1        | 0.48%   |
| Qualcomm Atheros Communications | 1        | 0.48%   |
| NetGear                         | 1        | 0.48%   |
| NEC Computers                   | 1        | 0.48%   |
| Edimax Technology               | 1        | 0.48%   |
| ASUSTek Computer                | 1        | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                | 25       | 11.74%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 14       | 6.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 11       | 5.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 10       | 4.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]         | 8        | 3.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                            | 7        | 3.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 7        | 3.29%   |
| BUFFALO 802.11ac WLAN Adapter                                      | 6        | 2.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 5        | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 5        | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 4        | 1.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 4        | 1.88%   |
| BUFFALO WLI-UC-GNM Wireless LAN Adapter [Ralink RT8070]            | 4        | 1.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                             | 3        | 1.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 3        | 1.41%   |
| Realtek 802.11ac NIC                                               | 3        | 1.41%   |
| PLANEX GW-USValue-EZ 802.11n Wireless Adapter [Realtek RTL8188CUS] | 3        | 1.41%   |
| PLANEX GW-USNano2 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 3        | 1.41%   |
| Intel Wireless 7260                                                | 3        | 1.41%   |
| Elecom WDC-150SU2M                                                 | 3        | 1.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                 | 3        | 1.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 2        | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 2        | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2        | 0.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 2        | 0.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)     | 2        | 0.94%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter         | 2        | 0.94%   |
| PLANEX GW-900D                                                     | 2        | 0.94%   |
| Intel Wireless-AC 9260                                             | 2        | 0.94%   |
| Intel Wireless 8265 / 8275                                         | 2        | 0.94%   |
| Intel Wireless 8260                                                | 2        | 0.94%   |
| Intel Wireless 7265                                                | 2        | 0.94%   |
| Intel Wireless 3165                                                | 2        | 0.94%   |
| Intel Wireless 3160                                                | 2        | 0.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 2        | 0.94%   |
| Intel Centrino Wireless-N 2230                                     | 2        | 0.94%   |
| Intel 700 Series Chipset Family Wi-Fi                              | 2        | 0.94%   |
| BUFFALO 802.11 n WLAN                                              | 2        | 0.94%   |
| Broadcom BCM43228 802.11a/b/g/n                                    | 2        | 0.94%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                 | 1        | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 298      | 50.68%  |
| Intel                            | 198      | 33.67%  |
| Broadcom                         | 24       | 4.08%   |
| Qualcomm Atheros                 | 23       | 3.91%   |
| Marvell Technology Group         | 10       | 1.7%    |
| Nvidia                           | 6        | 1.02%   |
| ASIX Electronics                 | 5        | 0.85%   |
| VIA Technologies                 | 4        | 0.68%   |
| Broadcom Limited                 | 4        | 0.68%   |
| Aquantia                         | 4        | 0.68%   |
| Huawei Technologies              | 2        | 0.34%   |
| Silicon Integrated Systems [SiS] | 1        | 0.17%   |
| Samsung Electronics              | 1        | 0.17%   |
| OPPO Electronics                 | 1        | 0.17%   |
| Netchip Technology               | 1        | 0.17%   |
| Loongson Technology              | 1        | 0.17%   |
| JMicron Technology               | 1        | 0.17%   |
| Elecom                           | 1        | 0.17%   |
| Corega K.K.                      | 1        | 0.17%   |
| ADMtek                           | 1        | 0.17%   |
| 3Com                             | 1        | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 252      | 41.18%  |
| Realtek RTL8125 2.5GbE Controller                                 | 35       | 5.72%   |
| Intel Ethernet Connection (2) I219-V                              | 35       | 5.72%   |
| Intel I211 Gigabit Network Connection                             | 26       | 4.25%   |
| Intel Ethernet Connection (7) I219-V                              | 22       | 3.59%   |
| Intel Ethernet Connection I217-V                                  | 15       | 2.45%   |
| Intel 82579V Gigabit Network Connection                           | 14       | 2.29%   |
| Intel Ethernet Connection I217-LM                                 | 13       | 2.12%   |
| Intel Ethernet Controller I225-V                                  | 11       | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 1.14%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 1.14%   |
| Intel 82574L Gigabit Network Connection                           | 7        | 1.14%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6        | 0.98%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 0.98%   |
| Intel I210 Gigabit Network Connection                             | 5        | 0.82%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5        | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5        | 0.82%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.65%   |
| Intel Ethernet Connection (12) I219-V                             | 4        | 0.65%   |
| Intel Ethernet Connection (11) I219-V                             | 4        | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.49%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.49%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 0.49%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.49%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 0.49%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 3        | 0.49%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 3        | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3        | 0.49%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2        | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.33%   |
| Nvidia MCP79 Ethernet                                             | 2        | 0.33%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.33%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 536      | 72.63%  |
| WiFi     | 193      | 26.15%  |
| Modem    | 7        | 0.95%   |
| Unknown  | 2        | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 456      | 80.71%  |
| WiFi     | 109      | 19.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 370      | 68.52%  |
| 2     | 143      | 26.48%  |
| 3     | 22       | 4.07%   |
| 4     | 3        | 0.56%   |
| 7     | 1        | 0.19%   |
| 0     | 1        | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 394      | 71.77%  |
| Yes  | 155      | 28.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 70       | 37.84%  |
| Cambridge Silicon Radio         | 67       | 36.22%  |
| Realtek Semiconductor           | 11       | 5.95%   |
| MediaTek                        | 7        | 3.78%   |
| Qualcomm Atheros Communications | 6        | 3.24%   |
| TP-Link                         | 5        | 2.7%    |
| ASUSTek Computer                | 5        | 2.7%    |
| Broadcom                        | 3        | 1.62%   |
| Lite-On Technology              | 2        | 1.08%   |
| IMC Networks                    | 2        | 1.08%   |
| Apple                           | 2        | 1.08%   |
| Realtek                         | 1        | 0.54%   |
| Foxconn / Hon Hai               | 1        | 0.54%   |
| Creative Technology             | 1        | 0.54%   |
| BUFFALO                         | 1        | 0.54%   |
| Actions                         | 1        | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 67       | 36.22%  |
| Intel AX200 Bluetooth                               | 23       | 12.43%  |
| Intel Wireless-AC 3168 Bluetooth                    | 14       | 7.57%   |
| Intel Bluetooth wireless interface                  | 12       | 6.49%   |
| Realtek Bluetooth Radio                             | 10       | 5.41%   |
| MediaTek Wireless_Device                            | 7        | 3.78%   |
| Intel AX210 Bluetooth                               | 7        | 3.78%   |
| TP-Link UB5A Adapter                                | 5        | 2.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5        | 2.7%    |
| Intel Bluetooth Device                              | 3        | 1.62%   |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 1.08%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2        | 1.08%   |
| Lite-On Bluetooth Device                            | 2        | 1.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2        | 1.08%   |
| Intel AX201 Bluetooth                               | 2        | 1.08%   |
| IMC Networks Bluetooth Device                       | 2        | 1.08%   |
| ASUS BCM20702A0                                     | 2        | 1.08%   |
| Apple Bluetooth Host Controller                     | 2        | 1.08%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1        | 0.54%   |
| Realtek Bluetooth Radio                             | 1        | 0.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 0.54%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 0.54%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1        | 0.54%   |
| Creative Bluetooth Audio W2                         | 1        | 0.54%   |
| BUFFALO Bluetooth Radio                             | 1        | 0.54%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 0.54%   |
| Broadcom Bluetooth V3.0 USB Device                  | 1        | 0.54%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 0.54%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 0.54%   |
| ASUS Bluetooth Radio                                | 1        | 0.54%   |
| ASUS Bluetooth Device                               | 1        | 0.54%   |
| Actions general adapter                             | 1        | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 351      | 38.61%  |
| AMD                                             | 231      | 25.41%  |
| Nvidia                                          | 188      | 20.68%  |
| C-Media Electronics                             | 25       | 2.75%   |
| VIA Technologies                                | 13       | 1.43%   |
| Texas Instruments                               | 13       | 1.43%   |
| Creative Technology                             | 13       | 1.43%   |
| Harman                                          | 9        | 0.99%   |
| JMTek                                           | 7        | 0.77%   |
| Generalplus Technology                          | 6        | 0.66%   |
| Creative Labs                                   | 6        | 0.66%   |
| Yamaha                                          | 5        | 0.55%   |
| TOWA Electronics                                | 3        | 0.33%   |
| Sony                                            | 3        | 0.33%   |
| GN Netcom                                       | 3        | 0.33%   |
| XMOS                                            | 2        | 0.22%   |
| Roland                                          | 2        | 0.22%   |
| Onkyo                                           | 2        | 0.22%   |
| Elitegroup Computer Systems (ECS)               | 2        | 0.22%   |
| ASUSTek Computer                                | 2        | 0.22%   |
| www.hirestech.com 2012 REV 2.1                  | 1        | 0.11%   |
| ULi Electronics                                 | 1        | 0.11%   |
| Thesycon Systemsoftware & Consulting            | 1        | 0.11%   |
| Tenx Technology                                 | 1        | 0.11%   |
| SteelSeries ApS                                 | 1        | 0.11%   |
| Silicon Integrated Systems [SiS]                | 1        | 0.11%   |
| RME                                             | 1        | 0.11%   |
| Realtek Semiconductor                           | 1        | 0.11%   |
| Razer USA                                       | 1        | 0.11%   |
| RATOC System                                    | 1        | 0.11%   |
| Rasteme                                         | 1        | 0.11%   |
| Philips (or NXP)                                | 1        | 0.11%   |
| Medeli Electronics                              | 1        | 0.11%   |
| Loongson Technology                             | 1        | 0.11%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.11%   |
| Focusrite-Novation                              | 1        | 0.11%   |
| DSEA A/S                                        | 1        | 0.11%   |
| Dell                                            | 1        | 0.11%   |
| Blue Microphones                                | 1        | 0.11%   |
| BEHRINGER International                         | 1        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 49       | 4.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 44       | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 36       | 3.41%   |
| AMD Family 17h/19h HD Audio Controller                                            | 36       | 3.41%   |
| Intel 200 Series PCH HD Audio                                                     | 31       | 2.94%   |
| Intel Cannon Lake PCH cAVS                                                        | 29       | 2.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 29       | 2.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 28       | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 28       | 2.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 26       | 2.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 26       | 2.46%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 24       | 2.27%   |
| AMD FCH Azalia Controller                                                         | 21       | 1.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 20       | 1.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 20       | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 19       | 1.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 18       | 1.71%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 18       | 1.71%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 17       | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 17       | 1.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 17       | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 16       | 1.52%   |
| Nvidia TU116 High Definition Audio Controller                                     | 14       | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 12       | 1.14%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 12       | 1.14%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 11       | 1.04%   |
| Nvidia GK107 HDMI Audio Controller                                                | 11       | 1.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 11       | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                                     | 10       | 0.95%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 10       | 0.95%   |
| Intel Alder Lake-S HD Audio Controller                                            | 10       | 0.95%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 10       | 0.95%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 9        | 0.85%   |
| AMD Navi 10 HDMI Audio                                                            | 9        | 0.85%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 8        | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                                     | 8        | 0.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 8        | 0.76%   |
| Harman JBL Pebbles                                                                | 8        | 0.76%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                 | 7        | 0.66%   |
| Nvidia GK106 HDMI Audio Controller                                                | 7        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 33       | 12.99%  |
| Kingston                                | 32       | 12.6%   |
| Crucial                                 | 32       | 12.6%   |
| Samsung Electronics                     | 17       | 6.69%   |
| A-DATA Technology                       | 17       | 6.69%   |
| Team                                    | 16       | 6.3%    |
| SK hynix                                | 16       | 6.3%    |
| Corsair                                 | 14       | 5.51%   |
| G.Skill                                 | 12       | 4.72%   |
| Micron Technology                       | 10       | 3.94%   |
| Panram                                  | 8        | 3.15%   |
| Nanya Technology                        | 8        | 3.15%   |
| Silicon Power                           | 5        | 1.97%   |
| KLEVV                                   | 5        | 1.97%   |
| Transcend                               | 4        | 1.57%   |
| Unknown                                 | 4        | 1.57%   |
| SanMax                                  | 2        | 0.79%   |
| Chun Well                               | 2        | 0.79%   |
| V-Color                                 | 1        | 0.39%   |
| Unknown (8AD3)                          | 1        | 0.39%   |
| Unknown (0x09EE)                        | 1        | 0.39%   |
| Unknown (04E9)                          | 1        | 0.39%   |
| UMAX                                    | 1        | 0.39%   |
| Silicon Power Computer & Communications | 1        | 0.39%   |
| Ramos Technology                        | 1        | 0.39%   |
| Patriot Memory (PDP Systems)            | 1        | 0.39%   |
| Patriot                                 | 1        | 0.39%   |
| Kingmax                                 | 1        | 0.39%   |
| Innodisk                                | 1        | 0.39%   |
| GeIL                                    | 1        | 0.39%   |
| Essencore Limited                       | 1        | 0.39%   |
| Elpida                                  | 1        | 0.39%   |
| Century Micro                           | 1        | 0.39%   |
| ASint Technology                        | 1        | 0.39%   |
| Apacer                                  | 1        | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s    | 4        | 1.52%   |
| Unknown                                                  | 4        | 1.52%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 3        | 1.14%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s       | 3        | 1.14%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s       | 3        | 1.14%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s     | 3        | 1.14%   |
| Nanya RAM M2X4G64CB8HG9N-DG 4GB DIMM DDR3 1600MT/s       | 3        | 1.14%   |
| KLEVV RAM KD48GU881-26N190A 8GB DIMM DDR4 2667MT/s       | 3        | 1.14%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s      | 3        | 1.14%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2667MT/s       | 3        | 1.14%   |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s   | 3        | 1.14%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 3        | 1.14%   |
| A-DATA RAM Module 32GB DIMM DDR4 3200MT/s                | 3        | 1.14%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                | 2        | 0.76%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2        | 0.76%   |
| Unknown RAM Module 1GB DIMM 800MT/s                      | 2        | 0.76%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s       | 2        | 0.76%   |
| Team RAM TEAMGROUP-UD3-1600 8192MB DIMM DDR3 1600MT/s    | 2        | 0.76%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 2        | 0.76%   |
| Silicon Power RAM DCLT8GN128S 8192MB DIMM DDR3 1600MT/s  | 2        | 0.76%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 2        | 0.76%   |
| Panram RAM PUD31600C118G2VS 8GB DIMM DDR3 1600MT/s       | 2        | 0.76%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s   | 2        | 0.76%   |
| Kingston RAM CBD26D4U9S8ME-8 8GB DIMM DDR4 2667MT/s      | 2        | 0.76%   |
| Kingston RAM 9905622-057.A00G 4096MB DIMM DDR4 2133MT/s  | 2        | 0.76%   |
| G.Skill RAM F3-2400C10-4GTX 4GB DIMM DDR3 2400MT/s       | 2        | 0.76%   |
| Crucial RAM CT51264BA160BJ.C8F 4096MB DIMM DDR3 1600MT/s | 2        | 0.76%   |
| Crucial RAM CT16G4DFD8266.C16FD1 16GB DIMM DDR4 2667MT/s | 2        | 0.76%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s    | 2        | 0.76%   |
| A-DATA RAM Module 8GB DIMM DDR4 3200MT/s                 | 2        | 0.76%   |
| V-Color RAM TD48G26S819K-VC 8GB DIMM DDR4 2667MT/s       | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 0.38%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.38%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.38%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 135      | 58.44%  |
| DDR3    | 65       | 28.14%  |
| SDRAM   | 11       | 4.76%   |
| Unknown | 9        | 3.9%    |
| DDR2    | 7        | 3.03%   |
| DDR5    | 2        | 0.87%   |
| LPDDR4  | 1        | 0.43%   |
| DDR     | 1        | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 208      | 90.83%  |
| SODIMM       | 18       | 7.86%   |
| RIMM         | 2        | 0.87%   |
| Row Of Chips | 1        | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 88       | 36.67%  |
| 4096  | 48       | 20%     |
| 16384 | 46       | 19.17%  |
| 2048  | 27       | 11.25%  |
| 32768 | 22       | 9.17%   |
| 1024  | 8        | 3.33%   |
| 512   | 1        | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 38       | 15.64%  |
| 2667    | 34       | 13.99%  |
| 1600    | 34       | 13.99%  |
| 2133    | 17       | 7%      |
| 2400    | 16       | 6.58%   |
| 1333    | 15       | 6.17%   |
| 3600    | 12       | 4.94%   |
| 800     | 10       | 4.12%   |
| 2666    | 9        | 3.7%    |
| 1800    | 9        | 3.7%    |
| 2933    | 7        | 2.88%   |
| Unknown | 6        | 2.47%   |
| 3800    | 5        | 2.06%   |
| 667     | 5        | 2.06%   |
| 3400    | 3        | 1.23%   |
| 1866    | 3        | 1.23%   |
| 533     | 3        | 1.23%   |
| 3000    | 2        | 0.82%   |
| 1066    | 2        | 0.82%   |
| 5600    | 1        | 0.41%   |
| 4800    | 1        | 0.41%   |
| 4133    | 1        | 0.41%   |
| 3733    | 1        | 0.41%   |
| 3534    | 1        | 0.41%   |
| 3100    | 1        | 0.41%   |
| 3007    | 1        | 0.41%   |
| 2733    | 1        | 0.41%   |
| 2048    | 1        | 0.41%   |
| 2000    | 1        | 0.41%   |
| 1867    | 1        | 0.41%   |
| 1648    | 1        | 0.41%   |
| 1334    | 1        | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 4        | 33.33%  |
| Brother Industries | 4        | 33.33%  |
| Seiko Epson        | 2        | 16.67%  |
| Hewlett-Packard    | 1        | 8.33%   |
| Fuji Xerox         | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother HL-1440 Laser Printer | 2        | 16.67%  |
| Seiko Epson XP-100 Series     | 1        | 8.33%   |
| Seiko Epson EP-306 Series     | 1        | 8.33%   |
| HP ENVY 5000 series           | 1        | 8.33%   |
| Fuji Xerox MultiWriter 5600C  | 1        | 8.33%   |
| Canon TS5300 series           | 1        | 8.33%   |
| Canon PIXMA iX6850 Printer    | 1        | 8.33%   |
| Canon PIXMA iP4600 Printer    | 1        | 8.33%   |
| Canon iP2700 series           | 1        | 8.33%   |
| Brother HL-L2360D series      | 1        | 8.33%   |
| Brother HL-52x0 series        | 1        | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Canon       | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 50%     |
| Canon CanoScan LiDE 100                                       | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 14       | 23.33%  |
| Elecom                        | 7        | 11.67%  |
| Sunplus Innovation Technology | 5        | 8.33%   |
| Microsoft                     | 3        | 5%      |
| MacroSilicon                  | 3        | 5%      |
| BUFFALO                       | 3        | 5%      |
| Microdia                      | 2        | 3.33%   |
| Generalplus Technology        | 2        | 3.33%   |
| Cubeternet                    | 2        | 3.33%   |
| Chicony Electronics           | 2        | 3.33%   |
| Z-Star Microelectronics       | 1        | 1.67%   |
| WaveRider Communications      | 1        | 1.67%   |
| Syntek                        | 1        | 1.67%   |
| SHENZHEN EMEET TECHNOLOGY     | 1        | 1.67%   |
| Samsung Electronics           | 1        | 1.67%   |
| Ruision                       | 1        | 1.67%   |
| Realtek Semiconductor         | 1        | 1.67%   |
| Pixart Imaging                | 1        | 1.67%   |
| OmniVision Technologies       | 1        | 1.67%   |
| Jieli Technology              | 1        | 1.67%   |
| Huawei Technologies           | 1        | 1.67%   |
| HD USB Camera                 | 1        | 1.67%   |
| GEMBIRD                       | 1        | 1.67%   |
| Etron Technology              | 1        | 1.67%   |
| eMeet                         | 1        | 1.67%   |
| Apple                         | 1        | 1.67%   |
| Alcor Micro                   | 1        | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 5        | 8.2%    |
| MacroSilicon USB3. 0 capture                   | 3        | 4.92%   |
| BUFFALO USB 2.0 Camera                         | 3        | 4.92%   |
| Sunplus Integrated_Webcam_HD                   | 2        | 3.28%   |
| Microdia Webcam Vitade AF                      | 2        | 3.28%   |
| Logitech HD Webcam C615                        | 2        | 3.28%   |
| Logitech HD Pro Webcam C920                    | 2        | 3.28%   |
| Generalplus 808 Camera                         | 2        | 3.28%   |
| Elecom UCAM-DLE300T                            | 2        | 3.28%   |
| Elecom ELECOM 5MP Webcam                       | 2        | 3.28%   |
| Elecom ELECOM 1MP Webcam                       | 2        | 3.28%   |
| Chicony FJ Camera                              | 2        | 3.28%   |
| Z-Star Venus USB2.0 Camera                     | 1        | 1.64%   |
| WaveRider USB Live camera                      | 1        | 1.64%   |
| Syntek BUFFALO BSW20K06H USB PC Camera         | 1        | 1.64%   |
| Sunplus SPCA2085 PC Camera                     | 1        | 1.64%   |
| Sunplus HD720P Webcam                          | 1        | 1.64%   |
| Sunplus FHD Camera                             | 1        | 1.64%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1        | 1.64%   |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 1.64%   |
| Ruision UVC Camera                             | 1        | 1.64%   |
| Realtek USB Camera                             | 1        | 1.64%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 1        | 1.64%   |
| OmniVision OV511+ Webcam                       | 1        | 1.64%   |
| Microsoft MicrosoftÂ LifeCam Studio           | 1        | 1.64%   |
| Microsoft LifeCam HD-3000                      | 1        | 1.64%   |
| Microsoft LifeCam Cinema                       | 1        | 1.64%   |
| Logitech Webcam C310                           | 1        | 1.64%   |
| Logitech QuickCam Orbit/Sphere AF              | 1        | 1.64%   |
| Logitech HD Webcam C910                        | 1        | 1.64%   |
| Logitech C922 Pro Stream Webcam                | 1        | 1.64%   |
| Logitech BRIO                                  | 1        | 1.64%   |
| Jieli USB PHY 2.0                              | 1        | 1.64%   |
| Huawei HiCamera                                | 1        | 1.64%   |
| HD USB Camera HD USB Camera                    | 1        | 1.64%   |
| GEMBIRD USB2.0 PC CAMERA                       | 1        | 1.64%   |
| Etron BUFFALO BSW32KM03 USB PC Camera          | 1        | 1.64%   |
| eMeet HD Webcam C960                           | 1        | 1.64%   |
| Elecom UCAM-DLB200TA                           | 1        | 1.64%   |
| Cubeternet WebCam                              | 1        | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| STMicroelectronics    | 2        | 40%     |
| Elan Microelectronics | 2        | 40%     |
| Synaptics             | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader        | 2        | 40%     |
| Elan fingerprint sensor [FeinTech FPS00200]  | 2        | 40%     |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Alcor Micro      | 3        | 50%     |
| SCM Microsystems | 2        | 33.33%  |
| Yubico.com       | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 3        | 50%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 2        | 33.33%  |
| Yubico.com Yubikey 4/5 U2F+CCID                        | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 455      | 83.03%  |
| 1     | 80       | 14.6%   |
| 2     | 11       | 2.01%   |
| 8     | 1        | 0.18%   |
| 7     | 1        | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 28       | 26.67%  |
| Graphics card            | 24       | 22.86%  |
| Multimedia controller    | 12       | 11.43%  |
| Unassigned class         | 10       | 9.52%   |
| Communication controller | 7        | 6.67%   |
| Fingerprint reader       | 5        | 4.76%   |
| Sound                    | 4        | 3.81%   |
| Modem                    | 3        | 2.86%   |
| Chipcard                 | 3        | 2.86%   |
| Storage/raid             | 2        | 1.9%    |
| Bluetooth                | 2        | 1.9%    |
| Storage/nvme             | 1        | 0.95%   |
| Storage/ata              | 1        | 0.95%   |
| Network                  | 1        | 0.95%   |
| Net/ethernet             | 1        | 0.95%   |
| Camera                   | 1        | 0.95%   |

