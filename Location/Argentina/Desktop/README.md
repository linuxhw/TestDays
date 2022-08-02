Linux in Argentina - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Argentina.

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

Total: 908

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | F2A68HM-H                   | [047d3c88ad](https://linux-hardware.org/?probe=047d3c88ad) | Jul 31, 2022 |
| Intel         | DH61BF AAG81311-101         | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| MSI           | B550M-A PRO                 | [14bbcb7e47](https://linux-hardware.org/?probe=14bbcb7e47) | Jul 30, 2022 |
| ASRock        | Z97 Pro4                    | [0db03812df](https://linux-hardware.org/?probe=0db03812df) | Jul 29, 2022 |
| MSI           | Z370 GAMING M5              | [b9ec9e3dd4](https://linux-hardware.org/?probe=b9ec9e3dd4) | Jul 28, 2022 |
| Gigabyte      | H410M H                     | [eb92148078](https://linux-hardware.org/?probe=eb92148078) | Jul 28, 2022 |
| ASUSTek       | PRIME A520M-K               | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| Gigabyte      | Z87-D3HP-CF                 | [88b45b1956](https://linux-hardware.org/?probe=88b45b1956) | Jul 26, 2022 |
| Biostar       | G31-M7 TE                   | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| Gigabyte      | 970A-UD3P                   | [72a44c6eea](https://linux-hardware.org/?probe=72a44c6eea) | Jul 23, 2022 |
| ASUSTek       | Maximus IX HERO             | [73a12fbe59](https://linux-hardware.org/?probe=73a12fbe59) | Jul 21, 2022 |
| Gigabyte      | B75M-HD3                    | [321d2817a3](https://linux-hardware.org/?probe=321d2817a3) | Jul 21, 2022 |
| Dell          | 0DR845                      | [cf4bcf9de8](https://linux-hardware.org/?probe=cf4bcf9de8) | Jul 19, 2022 |
| ASUSTek       | PRIME A320M-K               | [48d9b9f502](https://linux-hardware.org/?probe=48d9b9f502) | Jul 18, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | [3e2c54f9f1](https://linux-hardware.org/?probe=3e2c54f9f1) | Jul 17, 2022 |
| ASRock        | A55M-VS                     | [844ac53526](https://linux-hardware.org/?probe=844ac53526) | Jul 14, 2022 |
| ASRock        | A55M-VS                     | [3b8f491017](https://linux-hardware.org/?probe=3b8f491017) | Jul 14, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [c90a0cbab7](https://linux-hardware.org/?probe=c90a0cbab7) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [87fa08ea59](https://linux-hardware.org/?probe=87fa08ea59) | Jul 13, 2022 |
| Lenovo        | Annapurna CRB NOK           | [46d0d5dccc](https://linux-hardware.org/?probe=46d0d5dccc) | Jul 12, 2022 |
| ECS           | H110M4-C23                  | [4a4af6d2e9](https://linux-hardware.org/?probe=4a4af6d2e9) | Jul 08, 2022 |
| Intel         | DG35EC AAE29266-205         | [5b90bd12c7](https://linux-hardware.org/?probe=5b90bd12c7) | Jul 07, 2022 |
| Intel         | DG35EC AAE29266-205         | [9c2136e4eb](https://linux-hardware.org/?probe=9c2136e4eb) | Jul 07, 2022 |
| Gigabyte      | Z87-HD3                     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| Intel         | DN2820FYB H24582-205        | [147320c75c](https://linux-hardware.org/?probe=147320c75c) | Jul 04, 2022 |
| Gigabyte      | Z87-HD3                     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| Intel         | DX58SO AAE29331-703         | [3b22974574](https://linux-hardware.org/?probe=3b22974574) | Jul 01, 2022 |
| Gigabyte      | Z87-HD3                     | [c38c4e9cb9](https://linux-hardware.org/?probe=c38c4e9cb9) | Jun 30, 2022 |
| ASUSTek       | PRIME Z370-A                | [28479b3edf](https://linux-hardware.org/?probe=28479b3edf) | Jun 30, 2022 |
| Gigabyte      | Z87-HD3                     | [8d9a85c7f3](https://linux-hardware.org/?probe=8d9a85c7f3) | Jun 30, 2022 |
| Gigabyte      | Z87-HD3                     | [e1fbeb3d53](https://linux-hardware.org/?probe=e1fbeb3d53) | Jun 29, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | [ff60a3cb61](https://linux-hardware.org/?probe=ff60a3cb61) | Jun 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [af267c59cd](https://linux-hardware.org/?probe=af267c59cd) | Jun 28, 2022 |
| HP            | 8054                        | [82dd44f05f](https://linux-hardware.org/?probe=82dd44f05f) | Jun 26, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | Z87-HD3                     | [21d2b9f0fb](https://linux-hardware.org/?probe=21d2b9f0fb) | Jun 23, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [92944b1e97](https://linux-hardware.org/?probe=92944b1e97) | Jun 22, 2022 |
| HP            | 3646h                       | [d27deccf27](https://linux-hardware.org/?probe=d27deccf27) | Jun 22, 2022 |
| Dell          | 01HYR7 A01                  | [465ffdd126](https://linux-hardware.org/?probe=465ffdd126) | Jun 21, 2022 |
| ASRock        | G41M-GS                     | [9167934132](https://linux-hardware.org/?probe=9167934132) | Jun 18, 2022 |
| HP            | 0A60h                       | [cb42238223](https://linux-hardware.org/?probe=cb42238223) | Jun 17, 2022 |
| Dell          | 01HYR7 A01                  | [4e33fa1a1d](https://linux-hardware.org/?probe=4e33fa1a1d) | Jun 15, 2022 |
| Dell          | 01HYR7 A01                  | [71f9801165](https://linux-hardware.org/?probe=71f9801165) | Jun 15, 2022 |
| MSI           | 3664h                       | [5fbb22c653](https://linux-hardware.org/?probe=5fbb22c653) | Jun 15, 2022 |
| MSI           | B550M PRO-VDH               | [9916ed24a9](https://linux-hardware.org/?probe=9916ed24a9) | Jun 15, 2022 |
| Intel         | DN2820FYB H24582-205        | [c8b26ae553](https://linux-hardware.org/?probe=c8b26ae553) | Jun 13, 2022 |
| Intel         | DN2820FYB H24582-205        | [65bbf05cb0](https://linux-hardware.org/?probe=65bbf05cb0) | Jun 13, 2022 |
| ASRock        | 960GM-VGS3 FX               | [82aa782cce](https://linux-hardware.org/?probe=82aa782cce) | Jun 08, 2022 |
| ASRock        | H55M                        | [058eceb951](https://linux-hardware.org/?probe=058eceb951) | Jun 07, 2022 |
| ASRock        | Z97M Anniversary            | [1855124dd3](https://linux-hardware.org/?probe=1855124dd3) | Jun 07, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | [b3a7546aa9](https://linux-hardware.org/?probe=b3a7546aa9) | Jun 06, 2022 |
| ASRock        | A520M Pro4                  | [6c408a6fd7](https://linux-hardware.org/?probe=6c408a6fd7) | Jun 05, 2022 |
| Gigabyte      | B75M-D3H                    | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| MSI           | B550M-A PRO                 | [94a496851b](https://linux-hardware.org/?probe=94a496851b) | Jun 01, 2022 |
| Intel         | DN2820FYB H24582-205        | [45175a7f3b](https://linux-hardware.org/?probe=45175a7f3b) | Jun 01, 2022 |
| ASUSTek       | H81M-A                      | [d24672a3cd](https://linux-hardware.org/?probe=d24672a3cd) | May 31, 2022 |
| Gigabyte      | B75M-D3V                    | [30be732591](https://linux-hardware.org/?probe=30be732591) | May 29, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [7fd1e065eb](https://linux-hardware.org/?probe=7fd1e065eb) | May 29, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [8546d9cf10](https://linux-hardware.org/?probe=8546d9cf10) | May 27, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [bb0591d5c8](https://linux-hardware.org/?probe=bb0591d5c8) | May 26, 2022 |
| American M... | K7S41GX                     | [b311270c22](https://linux-hardware.org/?probe=b311270c22) | May 26, 2022 |
| ASRock        | Z270 Gaming K6              | [fbf8e08024](https://linux-hardware.org/?probe=fbf8e08024) | May 25, 2022 |
| Gigabyte      | B85M-D3H-A                  | [36e5918bc8](https://linux-hardware.org/?probe=36e5918bc8) | May 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | [0754e1c6e6](https://linux-hardware.org/?probe=0754e1c6e6) | May 23, 2022 |
| Dell          | 01HYR7 A01                  | [2cd1f7fd5e](https://linux-hardware.org/?probe=2cd1f7fd5e) | May 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | [900181bbff](https://linux-hardware.org/?probe=900181bbff) | May 22, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | [830532746e](https://linux-hardware.org/?probe=830532746e) | May 20, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | [27289062cb](https://linux-hardware.org/?probe=27289062cb) | May 19, 2022 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | [ea23b1fec2](https://linux-hardware.org/?probe=ea23b1fec2) | May 18, 2022 |
| MSI           | A320M-A PRO MAX             | [13bacdb7b6](https://linux-hardware.org/?probe=13bacdb7b6) | May 18, 2022 |
| MSI           | B550M PRO-VDH               | [fd15b34806](https://linux-hardware.org/?probe=fd15b34806) | May 13, 2022 |
| Intel         | DN2820FYB H24582-205        | [5af3adc742](https://linux-hardware.org/?probe=5af3adc742) | May 13, 2022 |
| Gigabyte      | A520M H                     | [d3088d7665](https://linux-hardware.org/?probe=d3088d7665) | May 11, 2022 |
| Intel         | DN2820FYB H24582-205        | [ba9835cb43](https://linux-hardware.org/?probe=ba9835cb43) | May 10, 2022 |
| Gigabyte      | B75M-D3H                    | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Foxconn       | LIMA                        | [fc4662a00e](https://linux-hardware.org/?probe=fc4662a00e) | May 09, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [422c9f9cae](https://linux-hardware.org/?probe=422c9f9cae) | May 09, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [f84e562503](https://linux-hardware.org/?probe=f84e562503) | May 06, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [76e6cc98aa](https://linux-hardware.org/?probe=76e6cc98aa) | May 05, 2022 |
| MSI           | B550M PRO-VDH               | [40f4bf344a](https://linux-hardware.org/?probe=40f4bf344a) | May 05, 2022 |
| Gigabyte      | H81M-S1                     | [8a7d82f85b](https://linux-hardware.org/?probe=8a7d82f85b) | May 03, 2022 |
| ASUSTek       | PRIME B550M-K               | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [d3872db37e](https://linux-hardware.org/?probe=d3872db37e) | Apr 29, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [2cfdf9b28a](https://linux-hardware.org/?probe=2cfdf9b28a) | Apr 29, 2022 |
| Dell          | 01HYR7 A01                  | [d7757bf097](https://linux-hardware.org/?probe=d7757bf097) | Apr 27, 2022 |
| ASRock        | B450 Steel Legend           | [bf0a56358c](https://linux-hardware.org/?probe=bf0a56358c) | Apr 27, 2022 |
| MSI           | 880GMA-E35                  | [6ff68166f7](https://linux-hardware.org/?probe=6ff68166f7) | Apr 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [00728feb75](https://linux-hardware.org/?probe=00728feb75) | Apr 26, 2022 |
| Intel         | DN2820FYB H24582-205        | [fb612cbcd5](https://linux-hardware.org/?probe=fb612cbcd5) | Apr 24, 2022 |
| ASUSTek       | H170M-PLUS                  | [86f45617ad](https://linux-hardware.org/?probe=86f45617ad) | Apr 22, 2022 |
| ASUSTek       | H170M-PLUS                  | [c021555957](https://linux-hardware.org/?probe=c021555957) | Apr 21, 2022 |
| ASUSTek       | P5K Deluxe                  | [e7b66178ce](https://linux-hardware.org/?probe=e7b66178ce) | Apr 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f28318e17b](https://linux-hardware.org/?probe=f28318e17b) | Apr 14, 2022 |
| ASUSTek       | Maximus IX HERO             | [624c5a033e](https://linux-hardware.org/?probe=624c5a033e) | Apr 14, 2022 |
| ASUSTek       | P8H77-M                     | [a5a366f7e7](https://linux-hardware.org/?probe=a5a366f7e7) | Apr 13, 2022 |
| MSI           | H81M-E33                    | [460099f77f](https://linux-hardware.org/?probe=460099f77f) | Apr 13, 2022 |
| MSI           | H510M-A PRO                 | [d93ab23121](https://linux-hardware.org/?probe=d93ab23121) | Apr 10, 2022 |
| MSI           | A68HM-E33 V2                | [cfa5407b7f](https://linux-hardware.org/?probe=cfa5407b7f) | Apr 10, 2022 |
| Intel         | DN2820FYB H24582-205        | [48e5060f20](https://linux-hardware.org/?probe=48e5060f20) | Apr 10, 2022 |
| Unknown       | P4M800CE-8237               | [4c6b9a3f5e](https://linux-hardware.org/?probe=4c6b9a3f5e) | Apr 06, 2022 |
| Intel         | DN2820FYB H24582-205        | [a19db5a006](https://linux-hardware.org/?probe=a19db5a006) | Apr 05, 2022 |
| CX / Air C... | CX-H87-M1                   | [ddfbf2df5e](https://linux-hardware.org/?probe=ddfbf2df5e) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | [5a8ee938ce](https://linux-hardware.org/?probe=5a8ee938ce) | Apr 01, 2022 |
| Gigabyte      | H370M DS3H-CF               | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| MSI           | MS-7388                     | [d5eabb8266](https://linux-hardware.org/?probe=d5eabb8266) | Mar 30, 2022 |
| Gigabyte      | Z490 AORUS ELITE            | [f8c03d6697](https://linux-hardware.org/?probe=f8c03d6697) | Mar 28, 2022 |
| Gigabyte      | B450 GAMING X               | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Intel         | DN2820FYB H24582-205        | [87a81b14f0](https://linux-hardware.org/?probe=87a81b14f0) | Mar 25, 2022 |
| ASUSTek       | M5A78L-M LX                 | [b5ee1f293e](https://linux-hardware.org/?probe=b5ee1f293e) | Mar 25, 2022 |
| Gigabyte      | H510M H                     | [d809ca0f7a](https://linux-hardware.org/?probe=d809ca0f7a) | Mar 25, 2022 |
| Gigabyte      | H270-Gaming 3               | [90ce7b8310](https://linux-hardware.org/?probe=90ce7b8310) | Mar 24, 2022 |
| HP            | 8054                        | [38288fadf8](https://linux-hardware.org/?probe=38288fadf8) | Mar 21, 2022 |
| Intel         | DG35EC AAE29266-205         | [0008f2b843](https://linux-hardware.org/?probe=0008f2b843) | Mar 20, 2022 |
| Intel         | DG35EC AAE29266-205         | [34d7600473](https://linux-hardware.org/?probe=34d7600473) | Mar 20, 2022 |
| Gigabyte      | X570 GAMING X               | [555255cb84](https://linux-hardware.org/?probe=555255cb84) | Mar 19, 2022 |
| Gigabyte      | B75M-D3V                    | [116074683a](https://linux-hardware.org/?probe=116074683a) | Mar 19, 2022 |
| ASUSTek       | P7H55D-M EVO                | [2e70de8c8d](https://linux-hardware.org/?probe=2e70de8c8d) | Mar 19, 2022 |
| Gigabyte      | M68MT-S2P                   | [74bdda89c3](https://linux-hardware.org/?probe=74bdda89c3) | Mar 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b2ec039a2e](https://linux-hardware.org/?probe=b2ec039a2e) | Mar 17, 2022 |
| ASRock        | FM2A88X Extreme4+           | [7e32829960](https://linux-hardware.org/?probe=7e32829960) | Mar 13, 2022 |
| MSI           | H110M PRO-VH PLUS           | [fc3707d356](https://linux-hardware.org/?probe=fc3707d356) | Mar 09, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [5aa4d54781](https://linux-hardware.org/?probe=5aa4d54781) | Mar 09, 2022 |
| ASUSTek       | P5GC-MX/1333                | [7708a6ffb9](https://linux-hardware.org/?probe=7708a6ffb9) | Mar 07, 2022 |
| ASRock        | G41M-S3                     | [a5d8ab9493](https://linux-hardware.org/?probe=a5d8ab9493) | Mar 07, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [e79a48e141](https://linux-hardware.org/?probe=e79a48e141) | Feb 27, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [65eae3fe4c](https://linux-hardware.org/?probe=65eae3fe4c) | Feb 25, 2022 |
| ASRock        | G31M-S                      | [1ecf0fe3af](https://linux-hardware.org/?probe=1ecf0fe3af) | Feb 24, 2022 |
| MSI           | B450M PRO-M2 MAX            | [3f99c8072a](https://linux-hardware.org/?probe=3f99c8072a) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | [09aca1c435](https://linux-hardware.org/?probe=09aca1c435) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | [35c00d5889](https://linux-hardware.org/?probe=35c00d5889) | Feb 22, 2022 |
| ASRock        | K10N78M                     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-A II            | [265235f4f4](https://linux-hardware.org/?probe=265235f4f4) | Feb 21, 2022 |
| MSI           | B550M PRO-VDH               | [747899db53](https://linux-hardware.org/?probe=747899db53) | Feb 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | [2a57fc9391](https://linux-hardware.org/?probe=2a57fc9391) | Feb 20, 2022 |
| ECS           | H81H3-M4                    | [d9f8a4991e](https://linux-hardware.org/?probe=d9f8a4991e) | Feb 18, 2022 |
| Advantec      | C15B                        | [708b68ac89](https://linux-hardware.org/?probe=708b68ac89) | Feb 17, 2022 |
| ASUSTek       | PRIME Z270M-PLUS            | [0faabbb741](https://linux-hardware.org/?probe=0faabbb741) | Feb 17, 2022 |
| Dell          | 0RF705                      | [4369e75c27](https://linux-hardware.org/?probe=4369e75c27) | Feb 14, 2022 |
| Gigabyte      | F2A68HM-H                   | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| ASRock        | H55M                        | [85a293bc45](https://linux-hardware.org/?probe=85a293bc45) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [196bd41500](https://linux-hardware.org/?probe=196bd41500) | Feb 12, 2022 |
| MSI           | H510M-A PRO                 | [e189ec36c5](https://linux-hardware.org/?probe=e189ec36c5) | Feb 12, 2022 |
| ASRock        | G31M-S                      | [0e52738a23](https://linux-hardware.org/?probe=0e52738a23) | Feb 11, 2022 |
| Gigabyte      | H81M-H                      | [da554d50b7](https://linux-hardware.org/?probe=da554d50b7) | Feb 10, 2022 |
| Gigabyte      | B365M DS3H                  | [fc6c97721c](https://linux-hardware.org/?probe=fc6c97721c) | Feb 09, 2022 |
| Gigabyte      | F2A55M-HD2                  | [c4cba809c4](https://linux-hardware.org/?probe=c4cba809c4) | Feb 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [dbfba11836](https://linux-hardware.org/?probe=dbfba11836) | Feb 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [b6df9d3243](https://linux-hardware.org/?probe=b6df9d3243) | Feb 08, 2022 |
| Gigabyte      | F2A88XM-D3HP                | [c6783b6b8b](https://linux-hardware.org/?probe=c6783b6b8b) | Feb 07, 2022 |
| HP            | 0A60h                       | [8c9b5ec56f](https://linux-hardware.org/?probe=8c9b5ec56f) | Feb 06, 2022 |
| Unknown       | 865G-M8                     | [ecc67cf3bc](https://linux-hardware.org/?probe=ecc67cf3bc) | Feb 06, 2022 |
| ASUSTek       | H61M-K                      | [0e2c677ddc](https://linux-hardware.org/?probe=0e2c677ddc) | Feb 03, 2022 |
| ASUSTek       | Maximus V GENE              | [749946734b](https://linux-hardware.org/?probe=749946734b) | Feb 03, 2022 |
| Gigabyte      | B75M-D3H                    | [23987146db](https://linux-hardware.org/?probe=23987146db) | Feb 02, 2022 |
| MSI           | A320M-A PRO MAX             | [a5298ee805](https://linux-hardware.org/?probe=a5298ee805) | Feb 02, 2022 |
| MSI           | A320M-A PRO MAX             | [c7af52d518](https://linux-hardware.org/?probe=c7af52d518) | Feb 02, 2022 |
| Gigabyte      | A320M-HD2-CF                | [6ad345c1a5](https://linux-hardware.org/?probe=6ad345c1a5) | Feb 01, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| Dell          | 0NX183 A01                  | [54e546f9ae](https://linux-hardware.org/?probe=54e546f9ae) | Jan 31, 2022 |
| Gigabyte      | B450 AORUS M                | [690eba21e0](https://linux-hardware.org/?probe=690eba21e0) | Jan 30, 2022 |
| Unknown       | P4M800CE-8237               | [ff8ade4a5a](https://linux-hardware.org/?probe=ff8ade4a5a) | Jan 28, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [350f00e69f](https://linux-hardware.org/?probe=350f00e69f) | Jan 27, 2022 |
| MSI           | H110M PRO-VH PLUS           | [62e942ea94](https://linux-hardware.org/?probe=62e942ea94) | Jan 26, 2022 |
| Gigabyte      | H110M-H-CF                  | [f8afc9746e](https://linux-hardware.org/?probe=f8afc9746e) | Jan 24, 2022 |
| ASUSTek       | B85M-G R2.0                 | [a6302c118b](https://linux-hardware.org/?probe=a6302c118b) | Jan 17, 2022 |
| ASUSTek       | B85M-G R2.0                 | [8a0c194baa](https://linux-hardware.org/?probe=8a0c194baa) | Jan 17, 2022 |
| MSI           | MS-7309                     | [b980404ce1](https://linux-hardware.org/?probe=b980404ce1) | Jan 13, 2022 |
| Gigabyte      | H61M-S1                     | [50adc5f773](https://linux-hardware.org/?probe=50adc5f773) | Jan 08, 2022 |
| Gigabyte      | GA-890FXA-UD5               | [1f828632ed](https://linux-hardware.org/?probe=1f828632ed) | Jan 07, 2022 |
| ASRock        | B450M-HDV R4.0              | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| MSI           | H110M PRO-VH PLUS           | [35c962a07f](https://linux-hardware.org/?probe=35c962a07f) | Jan 02, 2022 |
| VS Company    | MCP61M                      | [8009a6fbdf](https://linux-hardware.org/?probe=8009a6fbdf) | Jan 02, 2022 |
| HP            | 0A60h                       | [2812050060](https://linux-hardware.org/?probe=2812050060) | Jan 01, 2022 |
| Gigabyte      | H110M-H-CF                  | [4754d83d04](https://linux-hardware.org/?probe=4754d83d04) | Jan 01, 2022 |
| Intel         | DG965WH AAD41692-305        | [970dba93b8](https://linux-hardware.org/?probe=970dba93b8) | Dec 28, 2021 |
| ASUSTek       | H61M-K                      | [d02d1bb775](https://linux-hardware.org/?probe=d02d1bb775) | Dec 27, 2021 |
| Gigabyte      | H110M-H-CF                  | [d8a2a90482](https://linux-hardware.org/?probe=d8a2a90482) | Dec 27, 2021 |
| Gigabyte      | H110M-H-CF                  | [d2e019564f](https://linux-hardware.org/?probe=d2e019564f) | Dec 26, 2021 |
| Gigabyte      | H110M-H-CF                  | [63b3337725](https://linux-hardware.org/?probe=63b3337725) | Dec 26, 2021 |
| ASUSTek       | PRIME B360M-K               | [8df64a7f80](https://linux-hardware.org/?probe=8df64a7f80) | Dec 21, 2021 |
| ASUSTek       | P8Z68-V PRO                 | [ce7e7de4b4](https://linux-hardware.org/?probe=ce7e7de4b4) | Dec 20, 2021 |
| Dell          | 0RF705                      | [b28693bf2b](https://linux-hardware.org/?probe=b28693bf2b) | Dec 19, 2021 |
| Gigabyte      | H110M-H-CF                  | [bc401cc9a6](https://linux-hardware.org/?probe=bc401cc9a6) | Dec 14, 2021 |
| Gigabyte      | H510M H                     | [e66c15a464](https://linux-hardware.org/?probe=e66c15a464) | Dec 13, 2021 |
| Gigabyte      | H510M H                     | [53588115a6](https://linux-hardware.org/?probe=53588115a6) | Dec 13, 2021 |
| Gigabyte      | B250M-D3H-CF                | [903dfc6f62](https://linux-hardware.org/?probe=903dfc6f62) | Dec 13, 2021 |
| Gigabyte      | H310M H x.x                 | [60cdd8ce45](https://linux-hardware.org/?probe=60cdd8ce45) | Dec 11, 2021 |
| Quanta        | 2AC5                        | [0e0fcca430](https://linux-hardware.org/?probe=0e0fcca430) | Dec 10, 2021 |
| Quanta        | 2AC5                        | [d0c9fba2a4](https://linux-hardware.org/?probe=d0c9fba2a4) | Dec 10, 2021 |
| ASRock        | QC6000M                     | [3475206cb1](https://linux-hardware.org/?probe=3475206cb1) | Dec 10, 2021 |
| Gigabyte      | H410M H                     | [a1b80c28f2](https://linux-hardware.org/?probe=a1b80c28f2) | Dec 09, 2021 |
| ASUSTek       | M3A78-EM                    | [b041919f38](https://linux-hardware.org/?probe=b041919f38) | Dec 08, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | [4c79974ae8](https://linux-hardware.org/?probe=4c79974ae8) | Dec 03, 2021 |
| Biostar       | NF61V-M2                    | [0d21d633c9](https://linux-hardware.org/?probe=0d21d633c9) | Dec 02, 2021 |
| Gigabyte      | B75M-D3H                    | [30820af902](https://linux-hardware.org/?probe=30820af902) | Nov 29, 2021 |
| ECS           | H81H3-M4                    | [4215fcadd9](https://linux-hardware.org/?probe=4215fcadd9) | Nov 25, 2021 |
| Intel         | DH67BL AAG10189-208         | [dbf2659c98](https://linux-hardware.org/?probe=dbf2659c98) | Nov 23, 2021 |
| ASRock        | A320M-HDV R4.0              | [6e2d7fbaed](https://linux-hardware.org/?probe=6e2d7fbaed) | Nov 22, 2021 |
| Intel         | DP35DP AAD81073-205         | [be9ba487cd](https://linux-hardware.org/?probe=be9ba487cd) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | [d8c73031f1](https://linux-hardware.org/?probe=d8c73031f1) | Nov 20, 2021 |
| Gigabyte      | A320M-H-CF                  | [8eeef70a27](https://linux-hardware.org/?probe=8eeef70a27) | Nov 19, 2021 |
| ASRock        | B450M Pro4-F R2.0           | [8dc5c4b2c1](https://linux-hardware.org/?probe=8dc5c4b2c1) | Nov 19, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [5502066af1](https://linux-hardware.org/?probe=5502066af1) | Nov 18, 2021 |
| Gigabyte      | A320M-H-CF                  | [a8e3d44c9e](https://linux-hardware.org/?probe=a8e3d44c9e) | Nov 15, 2021 |
| Gigabyte      | GA-870A-UD3                 | [58809fa055](https://linux-hardware.org/?probe=58809fa055) | Nov 14, 2021 |
| ASRock        | 880GMH/USB3                 | [25aeb2bbf9](https://linux-hardware.org/?probe=25aeb2bbf9) | Nov 14, 2021 |
| ASRock        | 880GMH/USB3                 | [05ce0a8880](https://linux-hardware.org/?probe=05ce0a8880) | Nov 14, 2021 |
| Gigabyte      | H81M-H                      | [a895ed29e0](https://linux-hardware.org/?probe=a895ed29e0) | Nov 14, 2021 |
| ASRock        | A55M-VS                     | [3e40db1efb](https://linux-hardware.org/?probe=3e40db1efb) | Nov 09, 2021 |
| Gigabyte      | F2A68HM-H                   | [77b62d6178](https://linux-hardware.org/?probe=77b62d6178) | Nov 09, 2021 |
| MSI           | 990XA-GD55                  | [461ac78561](https://linux-hardware.org/?probe=461ac78561) | Nov 08, 2021 |
| MSI           | MS-7369                     | [670cc450d8](https://linux-hardware.org/?probe=670cc450d8) | Nov 08, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [c4fd612984](https://linux-hardware.org/?probe=c4fd612984) | Nov 07, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [e21897758d](https://linux-hardware.org/?probe=e21897758d) | Nov 07, 2021 |
| ASUSTek       | A68HM-PLUS                  | [384fb31833](https://linux-hardware.org/?probe=384fb31833) | Nov 06, 2021 |
| ASUSTek       | A68HM-PLUS                  | [7b21a0bc71](https://linux-hardware.org/?probe=7b21a0bc71) | Nov 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [03961f687b](https://linux-hardware.org/?probe=03961f687b) | Nov 06, 2021 |
| Gigabyte      | H510M S2H                   | [1a749d9336](https://linux-hardware.org/?probe=1a749d9336) | Nov 05, 2021 |
| ASUSTek       | PRO A320M-R WI-FI           | [a84ed9f4fc](https://linux-hardware.org/?probe=a84ed9f4fc) | Nov 02, 2021 |
| MSI           | 760GM-P34                   | [1161af8368](https://linux-hardware.org/?probe=1161af8368) | Oct 31, 2021 |
| Unknown       | K8M800-8237                 | [91468b399e](https://linux-hardware.org/?probe=91468b399e) | Oct 25, 2021 |
| Gigabyte      | H410M H V3                  | [6a3a81abd6](https://linux-hardware.org/?probe=6a3a81abd6) | Oct 22, 2021 |
| Gigabyte      | H410M H V3                  | [2f0f49590b](https://linux-hardware.org/?probe=2f0f49590b) | Oct 22, 2021 |
| ASUSTek       | H81M-A                      | [c7a2305704](https://linux-hardware.org/?probe=c7a2305704) | Oct 21, 2021 |
| ASUSTek       | H81M-A                      | [8d1ec3a3b6](https://linux-hardware.org/?probe=8d1ec3a3b6) | Oct 21, 2021 |
| Gigabyte      | B450 GAMING X               | [cb03c494cb](https://linux-hardware.org/?probe=cb03c494cb) | Oct 15, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [a0c897a604](https://linux-hardware.org/?probe=a0c897a604) | Oct 13, 2021 |
| Gigabyte      | H81M-H                      | [a65d72b574](https://linux-hardware.org/?probe=a65d72b574) | Oct 13, 2021 |
| ASRock        | 960GC-GS FX                 | [437c7ad805](https://linux-hardware.org/?probe=437c7ad805) | Oct 11, 2021 |
| MSI           | B150M PRO-VDH               | [da329b10c9](https://linux-hardware.org/?probe=da329b10c9) | Oct 08, 2021 |
| MSI           | B150M PRO-VDH               | [13f8e82e6a](https://linux-hardware.org/?probe=13f8e82e6a) | Oct 08, 2021 |
| MSI           | B550M PRO-VDH               | [b806a146d2](https://linux-hardware.org/?probe=b806a146d2) | Oct 08, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [1939167a1c](https://linux-hardware.org/?probe=1939167a1c) | Oct 06, 2021 |
| ASUSTek       | A68HM-PLUS                  | [00c624b592](https://linux-hardware.org/?probe=00c624b592) | Oct 03, 2021 |
| ASUSTek       | A68HM-PLUS                  | [09b4e39973](https://linux-hardware.org/?probe=09b4e39973) | Oct 03, 2021 |
| Biostar       | P4M89-M7B Ver:1.0           | [c499580572](https://linux-hardware.org/?probe=c499580572) | Sep 26, 2021 |
| Biostar       | P4M89-M7B Ver:1.0           | [e540393e87](https://linux-hardware.org/?probe=e540393e87) | Sep 25, 2021 |
| ASUSTek       | PRIME B450M-A               | [c4a94c7628](https://linux-hardware.org/?probe=c4a94c7628) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-A               | [f93c2362ff](https://linux-hardware.org/?probe=f93c2362ff) | Sep 21, 2021 |
| MSI           | MS-7253                     | [4be11be3f6](https://linux-hardware.org/?probe=4be11be3f6) | Sep 19, 2021 |
| Gigabyte      | 970A-D3                     | [8daebb1450](https://linux-hardware.org/?probe=8daebb1450) | Sep 19, 2021 |
| Unknown       | P4M800CE-8237               | [f7a252e496](https://linux-hardware.org/?probe=f7a252e496) | Sep 18, 2021 |
| Unknown       | P4M800CE-8237               | [13e024d15e](https://linux-hardware.org/?probe=13e024d15e) | Sep 18, 2021 |
| HP            | 0A64h                       | [edcb77e9a1](https://linux-hardware.org/?probe=edcb77e9a1) | Sep 15, 2021 |
| ASRock        | FM2A58M-VG3+ R2.0           | [6d95dbecb4](https://linux-hardware.org/?probe=6d95dbecb4) | Sep 13, 2021 |
| MSI           | A68HM-E33 V2                | [1fc1622a64](https://linux-hardware.org/?probe=1fc1622a64) | Sep 12, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [014c8bb745](https://linux-hardware.org/?probe=014c8bb745) | Sep 07, 2021 |
| ASUSTek       | P5G41T-M LX3                | [2f680da4b8](https://linux-hardware.org/?probe=2f680da4b8) | Sep 07, 2021 |
| Gigabyte      | 970A-D3                     | [e7b06b1276](https://linux-hardware.org/?probe=e7b06b1276) | Sep 06, 2021 |
| Gigabyte      | 970A-D3                     | [df2dd7daca](https://linux-hardware.org/?probe=df2dd7daca) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | [d1773b3e3d](https://linux-hardware.org/?probe=d1773b3e3d) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | [5d2cc7f4ca](https://linux-hardware.org/?probe=5d2cc7f4ca) | Sep 06, 2021 |
| ASRock        | N68-GS4 FX                  | [b1147fa740](https://linux-hardware.org/?probe=b1147fa740) | Sep 05, 2021 |
| ASRock        | N68-GS4 FX                  | [e33cd98e47](https://linux-hardware.org/?probe=e33cd98e47) | Sep 05, 2021 |
| Intel         | DG31PR AAD97573-302         | [7122e4bd16](https://linux-hardware.org/?probe=7122e4bd16) | Sep 04, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [16ef0eab27](https://linux-hardware.org/?probe=16ef0eab27) | Sep 04, 2021 |
| ASUSTek       | P5LD2-SE                    | [99767a5ca2](https://linux-hardware.org/?probe=99767a5ca2) | Sep 02, 2021 |
| Gigabyte      | F2A55M-HD2                  | [e8b8cb1cf7](https://linux-hardware.org/?probe=e8b8cb1cf7) | Sep 01, 2021 |
| Gigabyte      | F2A55M-HD2                  | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [038868057d](https://linux-hardware.org/?probe=038868057d) | Aug 30, 2021 |
| Gigabyte      | F2A55M-HD2                  | [d2ce2247c6](https://linux-hardware.org/?probe=d2ce2247c6) | Aug 30, 2021 |
| ASUSTek       | PRIME A520M-A               | [91f168dd88](https://linux-hardware.org/?probe=91f168dd88) | Aug 29, 2021 |
| ASUSTek       | PRIME B450M-A               | [78eb1f5b7f](https://linux-hardware.org/?probe=78eb1f5b7f) | Aug 29, 2021 |
| Gigabyte      | GA-890FXA-UD5               | [f6b7e268fe](https://linux-hardware.org/?probe=f6b7e268fe) | Aug 28, 2021 |
| Gigabyte      | B75M-D3V                    | [7f53bb7787](https://linux-hardware.org/?probe=7f53bb7787) | Aug 28, 2021 |
| Gigabyte      | A520M H                     | [4b126be26e](https://linux-hardware.org/?probe=4b126be26e) | Aug 26, 2021 |
| ASUSTek       | AM1M-A                      | [17f2638893](https://linux-hardware.org/?probe=17f2638893) | Aug 24, 2021 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [f3f58765e6](https://linux-hardware.org/?probe=f3f58765e6) | Aug 24, 2021 |
| Gigabyte      | H510M S2H                   | [c10c8ceffe](https://linux-hardware.org/?probe=c10c8ceffe) | Aug 23, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [4118ea79d0](https://linux-hardware.org/?probe=4118ea79d0) | Aug 23, 2021 |
| ECS           | GeForce6100PM-M2            | [8f16ee8e8c](https://linux-hardware.org/?probe=8f16ee8e8c) | Aug 21, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | [7f83e1b3c8](https://linux-hardware.org/?probe=7f83e1b3c8) | Aug 21, 2021 |
| Gigabyte      | A320M-S2H-CF                | [54369d3959](https://linux-hardware.org/?probe=54369d3959) | Aug 16, 2021 |
| ASRock        | M3A785GMH/128M              | [4ace1ea1ac](https://linux-hardware.org/?probe=4ace1ea1ac) | Aug 15, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | [c2c86f701d](https://linux-hardware.org/?probe=c2c86f701d) | Aug 13, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [b42acf7c50](https://linux-hardware.org/?probe=b42acf7c50) | Aug 12, 2021 |
| Gigabyte      | 970A-D3                     | [d62c66d9bd](https://linux-hardware.org/?probe=d62c66d9bd) | Aug 12, 2021 |
| Gigabyte      | H310M M.2 x.x               | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte      | H310M M.2 x.x               | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [4c28c43c28](https://linux-hardware.org/?probe=4c28c43c28) | Aug 10, 2021 |
| Gigabyte      | GA-A55M-DS2                 | [8beee2f359](https://linux-hardware.org/?probe=8beee2f359) | Aug 10, 2021 |
| Gigabyte      | GA-A55M-DS2                 | [d2e35c6ccb](https://linux-hardware.org/?probe=d2e35c6ccb) | Aug 10, 2021 |
| ASUSTek       | P7H55D-M EVO                | [88dcb8813a](https://linux-hardware.org/?probe=88dcb8813a) | Aug 10, 2021 |
| ASUSTek       | P7H55D-M EVO                | [07fad2e81c](https://linux-hardware.org/?probe=07fad2e81c) | Aug 10, 2021 |
| Exo           | Ready J7W                   | [df3a9167c8](https://linux-hardware.org/?probe=df3a9167c8) | Aug 09, 2021 |
| Exo           | Ready J7W                   | [c18b993ce6](https://linux-hardware.org/?probe=c18b993ce6) | Aug 09, 2021 |
| ASUSTek       | M4A78LT-M LX                | [bdd403e11c](https://linux-hardware.org/?probe=bdd403e11c) | Aug 09, 2021 |
| ASUSTek       | M4N68T-M-LE-V2              | [53bb9bce29](https://linux-hardware.org/?probe=53bb9bce29) | Aug 08, 2021 |
| Gigabyte      | H81M-H                      | [a54ce42dd4](https://linux-hardware.org/?probe=a54ce42dd4) | Aug 07, 2021 |
| Gigabyte      | 970A-D3                     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| Gigabyte      | Z170X-UD3-CF                | [491856c417](https://linux-hardware.org/?probe=491856c417) | Aug 02, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [a2afaa269d](https://linux-hardware.org/?probe=a2afaa269d) | Jul 31, 2021 |
| ASUSTek       | M2N68-AM Plus               | [0033aa7340](https://linux-hardware.org/?probe=0033aa7340) | Jul 28, 2021 |
| Gigabyte      | B75M-D3V                    | [22361fb7c3](https://linux-hardware.org/?probe=22361fb7c3) | Jul 28, 2021 |
| Intel         | DP55WB AAE64798-206         | [a9e6b7b07f](https://linux-hardware.org/?probe=a9e6b7b07f) | Jul 27, 2021 |
| Intel         | DP55WB AAE64798-206         | [7c880b70f2](https://linux-hardware.org/?probe=7c880b70f2) | Jul 27, 2021 |
| ASUSTek       | M2N68-AM Plus               | [af9bf0e1ff](https://linux-hardware.org/?probe=af9bf0e1ff) | Jul 27, 2021 |
| ASUSTek       | H61M-K                      | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Gigabyte      | A320M-S2H-CF                | [814e38361b](https://linux-hardware.org/?probe=814e38361b) | Jul 23, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [c8f7308ee9](https://linux-hardware.org/?probe=c8f7308ee9) | Jul 22, 2021 |
| ASUSTek       | M5A78L-M LX                 | [bf2209afbd](https://linux-hardware.org/?probe=bf2209afbd) | Jul 18, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [2aeaab8842](https://linux-hardware.org/?probe=2aeaab8842) | Jul 15, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [be94ca90cb](https://linux-hardware.org/?probe=be94ca90cb) | Jul 15, 2021 |
| Gigabyte      | F2A55M-HD2                  | [6a69f09403](https://linux-hardware.org/?probe=6a69f09403) | Jul 15, 2021 |
| ASUSTek       | H110T                       | [ffad10f62a](https://linux-hardware.org/?probe=ffad10f62a) | Jul 14, 2021 |
| ASUSTek       | H110T                       | [651a111373](https://linux-hardware.org/?probe=651a111373) | Jul 14, 2021 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [14b4d9f2ab](https://linux-hardware.org/?probe=14b4d9f2ab) | Jul 14, 2021 |
| Dell          | 0RY007                      | [c49f9f065b](https://linux-hardware.org/?probe=c49f9f065b) | Jul 11, 2021 |
| Dell          | 0RY007                      | [e075d2058a](https://linux-hardware.org/?probe=e075d2058a) | Jul 11, 2021 |
| ASUSTek       | PRIME H410M-E               | [3758d2a6b8](https://linux-hardware.org/?probe=3758d2a6b8) | Jul 09, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [bb267d3e0f](https://linux-hardware.org/?probe=bb267d3e0f) | Jul 09, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [4b5be18ffe](https://linux-hardware.org/?probe=4b5be18ffe) | Jul 09, 2021 |
| ASUSTek       | PRIME X470-PRO              | [448bcb8814](https://linux-hardware.org/?probe=448bcb8814) | Jul 02, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [dfe0d9fbaf](https://linux-hardware.org/?probe=dfe0d9fbaf) | Jun 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b8cc7c380d](https://linux-hardware.org/?probe=b8cc7c380d) | Jun 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2831e5a8cf](https://linux-hardware.org/?probe=2831e5a8cf) | Jun 28, 2021 |
| Dell          | 0G261D A00                  | [5d234cd641](https://linux-hardware.org/?probe=5d234cd641) | Jun 28, 2021 |
| Gigabyte      | H81M-H                      | [0a704c2e3b](https://linux-hardware.org/?probe=0a704c2e3b) | Jun 28, 2021 |
| ASRock        | FM2A78M-HD+                 | [eae811c82c](https://linux-hardware.org/?probe=eae811c82c) | Jun 25, 2021 |
| ECS           | H81H3-M4                    | [838f10c576](https://linux-hardware.org/?probe=838f10c576) | Jun 25, 2021 |
| ECS           | H81H3-M4                    | [bfc9a4d537](https://linux-hardware.org/?probe=bfc9a4d537) | Jun 25, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [95a3ae9f9f](https://linux-hardware.org/?probe=95a3ae9f9f) | Jun 24, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [7fba4b1b78](https://linux-hardware.org/?probe=7fba4b1b78) | Jun 23, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fa222df71a](https://linux-hardware.org/?probe=fa222df71a) | Jun 21, 2021 |
| Gigabyte      | H510M S2H                   | [c40ed6f57e](https://linux-hardware.org/?probe=c40ed6f57e) | Jun 21, 2021 |
| Gigabyte      | H510M S2H                   | [6c5f517ffe](https://linux-hardware.org/?probe=6c5f517ffe) | Jun 21, 2021 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [b2c32f1c8d](https://linux-hardware.org/?probe=b2c32f1c8d) | Jun 19, 2021 |
| Gigabyte      | Z170X-UD3-CF                | [91f4695a06](https://linux-hardware.org/?probe=91f4695a06) | Jun 19, 2021 |
| ASUSTek       | PRIME Z490-P                | [a6bdb9ad52](https://linux-hardware.org/?probe=a6bdb9ad52) | Jun 15, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | [e49acd5f55](https://linux-hardware.org/?probe=e49acd5f55) | Jun 12, 2021 |
| Gigabyte      | Z370 AORUS Gaming 7         | [88df5f0e94](https://linux-hardware.org/?probe=88df5f0e94) | Jun 12, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [3d47d96665](https://linux-hardware.org/?probe=3d47d96665) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [c9bea47caa](https://linux-hardware.org/?probe=c9bea47caa) | Jun 12, 2021 |
| HP            | 0A64h                       | [cd257e99d6](https://linux-hardware.org/?probe=cd257e99d6) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [c9c757474a](https://linux-hardware.org/?probe=c9c757474a) | Jun 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | [c0a212ed13](https://linux-hardware.org/?probe=c0a212ed13) | Jun 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [b47a3aad4b](https://linux-hardware.org/?probe=b47a3aad4b) | Jun 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [5e0580b431](https://linux-hardware.org/?probe=5e0580b431) | Jun 08, 2021 |
| Gigabyte      | H81M-H                      | [cfc0aceaf9](https://linux-hardware.org/?probe=cfc0aceaf9) | Jun 08, 2021 |
| ASRock        | A320M-HDV R4.0              | [b9d021b1e4](https://linux-hardware.org/?probe=b9d021b1e4) | Jun 07, 2021 |
| Gigabyte      | F2A55M-HD2                  | [8daf7e0679](https://linux-hardware.org/?probe=8daf7e0679) | Jun 02, 2021 |
| MSI           | H61M-E23                    | [d555f722d4](https://linux-hardware.org/?probe=d555f722d4) | Jun 01, 2021 |
| MSI           | A320M-A PRO MAX             | [f5bfeb4cb0](https://linux-hardware.org/?probe=f5bfeb4cb0) | Jun 01, 2021 |
| Gigabyte      | B450M DS3H-CF               | [3751085a36](https://linux-hardware.org/?probe=3751085a36) | May 31, 2021 |
| Gigabyte      | B450M DS3H-CF               | [d71af3d423](https://linux-hardware.org/?probe=d71af3d423) | May 31, 2021 |
| Gigabyte      | B365M DS3H                  | [f91a20dd51](https://linux-hardware.org/?probe=f91a20dd51) | May 30, 2021 |
| Gigabyte      | F2A55M-HD2                  | [6dde896b4f](https://linux-hardware.org/?probe=6dde896b4f) | May 30, 2021 |
| ASRock        | H81M-HG4                    | [9285d9b036](https://linux-hardware.org/?probe=9285d9b036) | May 29, 2021 |
| ASRock        | H81M-HG4                    | [c7752a5136](https://linux-hardware.org/?probe=c7752a5136) | May 29, 2021 |
| MSI           | A68HM-E33 V2                | [a9971ed939](https://linux-hardware.org/?probe=a9971ed939) | May 29, 2021 |
| ASUSTek       | M4N68T-M-LE-V2              | [2fffb102d8](https://linux-hardware.org/?probe=2fffb102d8) | May 28, 2021 |
| ASUSTek       | M5A97 PRO                   | [a7526aa47d](https://linux-hardware.org/?probe=a7526aa47d) | May 27, 2021 |
| ASUSTek       | M5A88-V EVO                 | [00f250e5c2](https://linux-hardware.org/?probe=00f250e5c2) | May 25, 2021 |
| Gigabyte      | GA-MA74GM-S2                | [a348b29a71](https://linux-hardware.org/?probe=a348b29a71) | May 25, 2021 |
| MSI           | MS-7369                     | [2a0863dd05](https://linux-hardware.org/?probe=2a0863dd05) | May 23, 2021 |
| MSI           | MS-7369                     | [69c762bef9](https://linux-hardware.org/?probe=69c762bef9) | May 22, 2021 |
| MSI           | H110M PRO-VH                | [4f4586d8e4](https://linux-hardware.org/?probe=4f4586d8e4) | May 20, 2021 |
| MSI           | A320M-A PRO MAX             | [9e9bc74757](https://linux-hardware.org/?probe=9e9bc74757) | May 20, 2021 |
| ASUSTek       | PRIME B450M-A               | [98bdee6a07](https://linux-hardware.org/?probe=98bdee6a07) | May 20, 2021 |
| ASUSTek       | M5A88-M                     | [893aa07acd](https://linux-hardware.org/?probe=893aa07acd) | May 19, 2021 |
| Gigabyte      | Z170X-GamingG1              | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [955eb51481](https://linux-hardware.org/?probe=955eb51481) | May 17, 2021 |
| ASUSTek       | PRIME A320M-K               | [14898777ea](https://linux-hardware.org/?probe=14898777ea) | May 16, 2021 |
| ASUSTek       | PRIME A320M-K               | [9d111b276a](https://linux-hardware.org/?probe=9d111b276a) | May 16, 2021 |
| Gigabyte      | F2A55M-HD2                  | [970f02b452](https://linux-hardware.org/?probe=970f02b452) | May 15, 2021 |
| Gigabyte      | F2A55M-HD2                  | [b39ddf3718](https://linux-hardware.org/?probe=b39ddf3718) | May 14, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [2addb54096](https://linux-hardware.org/?probe=2addb54096) | May 13, 2021 |
| ASRock        | A320M-HDV                   | [f85fceb5f0](https://linux-hardware.org/?probe=f85fceb5f0) | May 11, 2021 |
| ASRock        | H81M-HG4                    | [ed6ba9cf41](https://linux-hardware.org/?probe=ed6ba9cf41) | May 11, 2021 |
| MSI           | H170A GAMING PRO            | [a7c97c0108](https://linux-hardware.org/?probe=a7c97c0108) | May 10, 2021 |
| Gigabyte      | A320M-H-CF                  | [f6defd08d6](https://linux-hardware.org/?probe=f6defd08d6) | May 10, 2021 |
| Dell          | 0P096C A01                  | [36507e909e](https://linux-hardware.org/?probe=36507e909e) | May 10, 2021 |
| Dell          | 0P096C A01                  | [5975fc8fd0](https://linux-hardware.org/?probe=5975fc8fd0) | May 10, 2021 |
| Lenovo        | 312A SDK0K17763 WIN 1801... | [735a791715](https://linux-hardware.org/?probe=735a791715) | May 10, 2021 |
| ASRock        | N68-S                       | [ca240bb5bd](https://linux-hardware.org/?probe=ca240bb5bd) | May 08, 2021 |
| ASRock        | FM2A58M-VG3+ R2.0           | [9b6328f4f9](https://linux-hardware.org/?probe=9b6328f4f9) | May 07, 2021 |
| Gigabyte      | A320M-S2H-CF                | [dc28c67e94](https://linux-hardware.org/?probe=dc28c67e94) | May 05, 2021 |
| MSI           | MAG B460M MORTAR            | [9b72abe5d8](https://linux-hardware.org/?probe=9b72abe5d8) | May 05, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [70b0ad02d8](https://linux-hardware.org/?probe=70b0ad02d8) | May 03, 2021 |
| Lenovo        | 312A SDK0K17763 WIN 1801... | [5067d1973b](https://linux-hardware.org/?probe=5067d1973b) | May 03, 2021 |
| ASUSTek       | P5GC-MX/1333                | [1a9b2e458a](https://linux-hardware.org/?probe=1a9b2e458a) | Apr 30, 2021 |
| ASRock        | D1800M                      | [ac1f5df594](https://linux-hardware.org/?probe=ac1f5df594) | Apr 30, 2021 |
| MSI           | GF615M-P33                  | [4219571ca8](https://linux-hardware.org/?probe=4219571ca8) | Apr 29, 2021 |
| ASRock        | B450M/ac                    | [735520a94e](https://linux-hardware.org/?probe=735520a94e) | Apr 29, 2021 |
| ASUSTek       | PRIME A320M-K               | [3be3ad06bb](https://linux-hardware.org/?probe=3be3ad06bb) | Apr 26, 2021 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [671daf25c5](https://linux-hardware.org/?probe=671daf25c5) | Apr 21, 2021 |
| ASUSTek       | STRIX B250F GAMING          | [8276e1fb2f](https://linux-hardware.org/?probe=8276e1fb2f) | Apr 20, 2021 |
| ASUSTek       | M4N68T-M-LE-V2              | [6c3e2b45b7](https://linux-hardware.org/?probe=6c3e2b45b7) | Apr 18, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [c0d756c373](https://linux-hardware.org/?probe=c0d756c373) | Apr 18, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [c21eda77bd](https://linux-hardware.org/?probe=c21eda77bd) | Apr 18, 2021 |
| ASRock        | FM2A68M-DG3+                | [dbc3d7ed6f](https://linux-hardware.org/?probe=dbc3d7ed6f) | Apr 16, 2021 |
| ECS           | H61H2-MV                    | [789990839d](https://linux-hardware.org/?probe=789990839d) | Apr 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [b141013d8e](https://linux-hardware.org/?probe=b141013d8e) | Apr 12, 2021 |
| ASUSTek       | M5A78L-M LX3                | [580b3a3082](https://linux-hardware.org/?probe=580b3a3082) | Apr 11, 2021 |
| Sun Micros... | Ultra 24 50                 | [e4b76f9137](https://linux-hardware.org/?probe=e4b76f9137) | Apr 10, 2021 |
| Sun Micros... | Ultra 24 50                 | [15691fbc42](https://linux-hardware.org/?probe=15691fbc42) | Apr 10, 2021 |
| ASRock        | A55M-VS                     | [7899d5959f](https://linux-hardware.org/?probe=7899d5959f) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5527015fb6](https://linux-hardware.org/?probe=5527015fb6) | Apr 08, 2021 |
| ASRock        | H81M-VG4 R2.0               | [8f244b3a14](https://linux-hardware.org/?probe=8f244b3a14) | Apr 07, 2021 |
| ASRock        | A55M-VS                     | [dd5b31deb0](https://linux-hardware.org/?probe=dd5b31deb0) | Apr 06, 2021 |
| Gigabyte      | GA-E6010N                   | [1635d5db86](https://linux-hardware.org/?probe=1635d5db86) | Apr 05, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [3701a4c90b](https://linux-hardware.org/?probe=3701a4c90b) | Apr 04, 2021 |
| Pegatron      | 2ADC                        | [e4bfddb8d9](https://linux-hardware.org/?probe=e4bfddb8d9) | Apr 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | [a1d81fc589](https://linux-hardware.org/?probe=a1d81fc589) | Apr 03, 2021 |
| Gigabyte      | H110M-H-CF                  | [d8ad64a9b4](https://linux-hardware.org/?probe=d8ad64a9b4) | Mar 31, 2021 |
| Gigabyte      | H110M-H-CF                  | [8a1974892c](https://linux-hardware.org/?probe=8a1974892c) | Mar 31, 2021 |
| MSI           | A68HM-E33 V2                | [452b661f11](https://linux-hardware.org/?probe=452b661f11) | Mar 29, 2021 |
| MSI           | A68HM-E33 V2                | [d48e29b011](https://linux-hardware.org/?probe=d48e29b011) | Mar 29, 2021 |
| Dell          | 03NVJ6 A03                  | [e3e24e8b49](https://linux-hardware.org/?probe=e3e24e8b49) | Mar 29, 2021 |
| Dell          | 03NVJ6 A03                  | [eca35ad0e3](https://linux-hardware.org/?probe=eca35ad0e3) | Mar 29, 2021 |
| ASUSTek       | Maximus IX HERO             | [a4bdc70396](https://linux-hardware.org/?probe=a4bdc70396) | Mar 28, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [b3de0a1ac2](https://linux-hardware.org/?probe=b3de0a1ac2) | Mar 25, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [b343c27b5a](https://linux-hardware.org/?probe=b343c27b5a) | Mar 25, 2021 |
| MSI           | H81M-E33                    | [0033e285ca](https://linux-hardware.org/?probe=0033e285ca) | Mar 22, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [963860ecf9](https://linux-hardware.org/?probe=963860ecf9) | Mar 19, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [ffbb04d01b](https://linux-hardware.org/?probe=ffbb04d01b) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [bf47d7941d](https://linux-hardware.org/?probe=bf47d7941d) | Mar 17, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [c92b218f5c](https://linux-hardware.org/?probe=c92b218f5c) | Mar 17, 2021 |
| Gigabyte      | B365M DS3H                  | [f2a5b012e3](https://linux-hardware.org/?probe=f2a5b012e3) | Mar 16, 2021 |
| Gigabyte      | B365M DS3H                  | [21aa3df83c](https://linux-hardware.org/?probe=21aa3df83c) | Mar 16, 2021 |
| ASRock        | A75M-HVS                    | [fe8e965db2](https://linux-hardware.org/?probe=fe8e965db2) | Mar 14, 2021 |
| MSI           | A68HM-E33 V2                | [d3b5e8a715](https://linux-hardware.org/?probe=d3b5e8a715) | Mar 12, 2021 |
| ASRock        | H61M-VG3                    | [37e1545431](https://linux-hardware.org/?probe=37e1545431) | Mar 07, 2021 |
| Quanta        | 2AC5                        | [07fe8046cf](https://linux-hardware.org/?probe=07fe8046cf) | Mar 05, 2021 |
| ASUSTek       | PRIME Z390-A                | [cfc3688efa](https://linux-hardware.org/?probe=cfc3688efa) | Mar 05, 2021 |
| ASUSTek       | PRIME X570-PRO              | [bc583e9896](https://linux-hardware.org/?probe=bc583e9896) | Mar 04, 2021 |
| Quanta        | 2AC5                        | [7e85d95373](https://linux-hardware.org/?probe=7e85d95373) | Mar 04, 2021 |
| ASRock        | B550 Extreme4               | [3f3849bf50](https://linux-hardware.org/?probe=3f3849bf50) | Mar 03, 2021 |
| ASRock        | B550 Extreme4               | [644ea81680](https://linux-hardware.org/?probe=644ea81680) | Mar 03, 2021 |
| ASRock        | B550 Extreme4               | [8fb4d18a5d](https://linux-hardware.org/?probe=8fb4d18a5d) | Mar 03, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [56edf5fe97](https://linux-hardware.org/?probe=56edf5fe97) | Mar 01, 2021 |
| ASRock        | G41M-VS3                    | [75cb33cf5e](https://linux-hardware.org/?probe=75cb33cf5e) | Feb 25, 2021 |
| ASRock        | G41M-VS3                    | [6a77858cd4](https://linux-hardware.org/?probe=6a77858cd4) | Feb 25, 2021 |
| ASRock        | H61M-S                      | [f4feb004a2](https://linux-hardware.org/?probe=f4feb004a2) | Feb 25, 2021 |
| Gigabyte      | A320M-HD2-CF                | [9070974dd1](https://linux-hardware.org/?probe=9070974dd1) | Feb 22, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [e84e6da8b3](https://linux-hardware.org/?probe=e84e6da8b3) | Feb 22, 2021 |
| ASRock        | D1800M                      | [a638291757](https://linux-hardware.org/?probe=a638291757) | Feb 22, 2021 |
| MSI           | A68HM-E33 V2                | [82a06b4bea](https://linux-hardware.org/?probe=82a06b4bea) | Feb 21, 2021 |
| ASRock        | FM2A68M-DG3+                | [8e0a2c9417](https://linux-hardware.org/?probe=8e0a2c9417) | Feb 20, 2021 |
| ASUSTek       | PRIME B450M-A               | [aca4e470c3](https://linux-hardware.org/?probe=aca4e470c3) | Feb 19, 2021 |
| Gigabyte      | H81M-H                      | [75358678b8](https://linux-hardware.org/?probe=75358678b8) | Feb 19, 2021 |
| MSI           | H110M PRO-VH PLUS           | [5ec73bb253](https://linux-hardware.org/?probe=5ec73bb253) | Feb 19, 2021 |
| Gigabyte      | H410M H                     | [ee13368ccf](https://linux-hardware.org/?probe=ee13368ccf) | Feb 18, 2021 |
| ECS           | A780GM-A                    | [dc3479d75d](https://linux-hardware.org/?probe=dc3479d75d) | Feb 18, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [3ab509f245](https://linux-hardware.org/?probe=3ab509f245) | Feb 16, 2021 |
| Gigabyte      | A320M-HD2-CF                | [4587ba7aff](https://linux-hardware.org/?probe=4587ba7aff) | Feb 15, 2021 |
| ASUSTek       | Maximus VI GENE             | [045958c66f](https://linux-hardware.org/?probe=045958c66f) | Feb 15, 2021 |
| Gigabyte      | AM1M-S2H                    | [cf87ee00a2](https://linux-hardware.org/?probe=cf87ee00a2) | Feb 15, 2021 |
| ASRock        | D1800M                      | [7aee55a839](https://linux-hardware.org/?probe=7aee55a839) | Feb 14, 2021 |
| Gigabyte      | GA-870A-UD3                 | [392d4d0e90](https://linux-hardware.org/?probe=392d4d0e90) | Feb 14, 2021 |
| MSI           | H55M-E21                    | [384f3ff0af](https://linux-hardware.org/?probe=384f3ff0af) | Feb 12, 2021 |
| MSI           | A68HM-E33 V2                | [d0629b852a](https://linux-hardware.org/?probe=d0629b852a) | Feb 11, 2021 |
| ASUSTek       | F1A55-M LE                  | [64ba6bddae](https://linux-hardware.org/?probe=64ba6bddae) | Feb 11, 2021 |
| ASUSTek       | P8H77-V LE                  | [59efda3efc](https://linux-hardware.org/?probe=59efda3efc) | Feb 08, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [ed00c813b6](https://linux-hardware.org/?probe=ed00c813b6) | Feb 08, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [2f548fff00](https://linux-hardware.org/?probe=2f548fff00) | Feb 05, 2021 |
| ASUSTek       | P8H67-M LE                  | [e2af2071f7](https://linux-hardware.org/?probe=e2af2071f7) | Feb 02, 2021 |
| ASRock        | H110 Pro BTC+               | [7712ee2cf8](https://linux-hardware.org/?probe=7712ee2cf8) | Jan 31, 2021 |
| ASRock        | H110 Pro BTC+               | [50a9d5eb78](https://linux-hardware.org/?probe=50a9d5eb78) | Jan 31, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f5d8ef5c6d](https://linux-hardware.org/?probe=f5d8ef5c6d) | Jan 30, 2021 |
| ASUSTek       | P5VD2-MX SE                 | [e03555e109](https://linux-hardware.org/?probe=e03555e109) | Jan 29, 2021 |
| Gigabyte      | M68MT-S2                    | [c8a65be832](https://linux-hardware.org/?probe=c8a65be832) | Jan 29, 2021 |
| Gigabyte      | M68MT-S2                    | [f602a19d08](https://linux-hardware.org/?probe=f602a19d08) | Jan 28, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [193f9e8bab](https://linux-hardware.org/?probe=193f9e8bab) | Jan 28, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [c0dd8179cd](https://linux-hardware.org/?probe=c0dd8179cd) | Jan 28, 2021 |
| ASUSTek       | H97M-PLUS                   | [5d87cbd136](https://linux-hardware.org/?probe=5d87cbd136) | Jan 28, 2021 |
| ASUSTek       | PRIME A320M-K               | [e665efd758](https://linux-hardware.org/?probe=e665efd758) | Jan 25, 2021 |
| MSI           | H110M PRO-VH PLUS           | [3464ee81c9](https://linux-hardware.org/?probe=3464ee81c9) | Jan 21, 2021 |
| Gigabyte      | F2A68HM-H                   | [1b97915adf](https://linux-hardware.org/?probe=1b97915adf) | Jan 18, 2021 |
| ASUSTek       | M2N-MX SE                   | [7eb3673e0d](https://linux-hardware.org/?probe=7eb3673e0d) | Jan 17, 2021 |
| MSI           | A68HM-E33 V2                | [697b2ce15f](https://linux-hardware.org/?probe=697b2ce15f) | Jan 15, 2021 |
| MSI           | A68HM-E33 V2                | [e0fefe5a7b](https://linux-hardware.org/?probe=e0fefe5a7b) | Jan 15, 2021 |
| ASUSTek       | M5A97 EVO                   | [f37167c44c](https://linux-hardware.org/?probe=f37167c44c) | Jan 15, 2021 |
| ASUSTek       | H81M-A                      | [90f0325a31](https://linux-hardware.org/?probe=90f0325a31) | Jan 11, 2021 |
| Gigabyte      | H61M-S2V-B3                 | [d082458493](https://linux-hardware.org/?probe=d082458493) | Jan 09, 2021 |
| Gigabyte      | H61M-USB3-B3                | [f71cd86b02](https://linux-hardware.org/?probe=f71cd86b02) | Jan 09, 2021 |
| ECS           | H81H3-M4                    | [1cc0f1e4dd](https://linux-hardware.org/?probe=1cc0f1e4dd) | Jan 04, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [30d41b3e77](https://linux-hardware.org/?probe=30d41b3e77) | Jan 03, 2021 |
| PCChips       | A33G                        | [ec9962b7f0](https://linux-hardware.org/?probe=ec9962b7f0) | Jan 02, 2021 |
| Gigabyte      | F2A88XM-HD3                 | [3656c88417](https://linux-hardware.org/?probe=3656c88417) | Jan 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [249d6291cb](https://linux-hardware.org/?probe=249d6291cb) | Dec 29, 2020 |
| Gigabyte      | F2A68HM-H                   | [086d18cb83](https://linux-hardware.org/?probe=086d18cb83) | Dec 28, 2020 |
| ASUSTek       | TUF B360-PLUS GAMING        | [d0d7418d46](https://linux-hardware.org/?probe=d0d7418d46) | Dec 28, 2020 |
| Gigabyte      | F2A68HM-H                   | [48bc196d16](https://linux-hardware.org/?probe=48bc196d16) | Dec 27, 2020 |
| Gigabyte      | F2A88XM-HD3                 | [eb82a63318](https://linux-hardware.org/?probe=eb82a63318) | Dec 24, 2020 |
| MSI           | MS-7388                     | [2470f3c112](https://linux-hardware.org/?probe=2470f3c112) | Dec 22, 2020 |
| Biostar       | G41D3C                      | [72b01ff1d4](https://linux-hardware.org/?probe=72b01ff1d4) | Dec 18, 2020 |
| Gigabyte      | H61M-S1                     | [16326f1aff](https://linux-hardware.org/?probe=16326f1aff) | Dec 18, 2020 |
| ASUSTek       | PRIME B450M-A               | [722fa1b4da](https://linux-hardware.org/?probe=722fa1b4da) | Dec 13, 2020 |
| ASUSTek       | PRIME B450M-A               | [7c6d46c476](https://linux-hardware.org/?probe=7c6d46c476) | Dec 13, 2020 |
| ASRock        | G31M-S                      | [36aed84652](https://linux-hardware.org/?probe=36aed84652) | Dec 12, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | [90fceed1b5](https://linux-hardware.org/?probe=90fceed1b5) | Dec 11, 2020 |
| Gigabyte      | B450M DS3H-CF               | [6ec3b6b77e](https://linux-hardware.org/?probe=6ec3b6b77e) | Dec 10, 2020 |
| Gigabyte      | 945GCM-S2C                  | [e1d03e259e](https://linux-hardware.org/?probe=e1d03e259e) | Dec 09, 2020 |
| MSI           | MS-7309                     | [ae124f45f6](https://linux-hardware.org/?probe=ae124f45f6) | Dec 08, 2020 |
| Gigabyte      | A320M-S2H V2-CF             | [100b3ce3ee](https://linux-hardware.org/?probe=100b3ce3ee) | Dec 06, 2020 |
| Gigabyte      | 945GCM-S2C                  | [eba95d11b5](https://linux-hardware.org/?probe=eba95d11b5) | Dec 04, 2020 |
| ASUSTek       | H87M-E                      | [98952fe4b6](https://linux-hardware.org/?probe=98952fe4b6) | Dec 04, 2020 |
| Biostar       | G31-M7 TE                   | [174de8e1d6](https://linux-hardware.org/?probe=174de8e1d6) | Nov 29, 2020 |
| Biostar       | G31-M7 TE                   | [7b85d35e4d](https://linux-hardware.org/?probe=7b85d35e4d) | Nov 29, 2020 |
| MSI           | MS-7388                     | [6355d205f0](https://linux-hardware.org/?probe=6355d205f0) | Nov 27, 2020 |
| Gigabyte      | H81M-DS2                    | [29efce32cc](https://linux-hardware.org/?probe=29efce32cc) | Nov 25, 2020 |
| Quanta        | 2AC5                        | [18d1d03193](https://linux-hardware.org/?probe=18d1d03193) | Nov 24, 2020 |
| MSI           | 770-C45                     | [394b5d3eb0](https://linux-hardware.org/?probe=394b5d3eb0) | Nov 21, 2020 |
| MSI           | 770-C45                     | [8e06fe0cf3](https://linux-hardware.org/?probe=8e06fe0cf3) | Nov 21, 2020 |
| Gigabyte      | GA-E6010N                   | [099dc85d9f](https://linux-hardware.org/?probe=099dc85d9f) | Nov 21, 2020 |
| Gigabyte      | A320M-H-CF                  | [9fc31cde8f](https://linux-hardware.org/?probe=9fc31cde8f) | Nov 20, 2020 |
| Gigabyte      | A320M-H-CF                  | [0c209e45b2](https://linux-hardware.org/?probe=0c209e45b2) | Nov 20, 2020 |
| ASUSTek       | PRIME X370-A                | [0dd1de106e](https://linux-hardware.org/?probe=0dd1de106e) | Nov 16, 2020 |
| Gigabyte      | A320M-S2H V2-CF             | [7973f58865](https://linux-hardware.org/?probe=7973f58865) | Nov 16, 2020 |
| ASUSTek       | M4N68T-M-LE-V2              | [f038b64822](https://linux-hardware.org/?probe=f038b64822) | Nov 16, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [5364e41335](https://linux-hardware.org/?probe=5364e41335) | Nov 14, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [38989221fb](https://linux-hardware.org/?probe=38989221fb) | Nov 14, 2020 |
| ECS           | Iris8                       | [1614d7d736](https://linux-hardware.org/?probe=1614d7d736) | Nov 14, 2020 |
| ECS           | Iris8                       | [c2d76cebd4](https://linux-hardware.org/?probe=c2d76cebd4) | Nov 14, 2020 |
| ASUSTek       | Z170-P                      | [0c370f7790](https://linux-hardware.org/?probe=0c370f7790) | Nov 13, 2020 |
| Gigabyte      | H61M-S1                     | [7867789c72](https://linux-hardware.org/?probe=7867789c72) | Nov 13, 2020 |
| BANGHO        | MZBSWAP-00                  | [c0b3c1bae1](https://linux-hardware.org/?probe=c0b3c1bae1) | Nov 13, 2020 |
| ASUSTek       | M5A97 PRO                   | [b8ab15a3a1](https://linux-hardware.org/?probe=b8ab15a3a1) | Nov 12, 2020 |
| ASUSTek       | M5A97 PRO                   | [eef85b80ab](https://linux-hardware.org/?probe=eef85b80ab) | Nov 12, 2020 |
| Gigabyte      | B450M DS3H-CF               | [db983b0664](https://linux-hardware.org/?probe=db983b0664) | Nov 11, 2020 |
| Gigabyte      | B450M DS3H-CF               | [7cba0a8ce2](https://linux-hardware.org/?probe=7cba0a8ce2) | Nov 11, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [dbb66895b3](https://linux-hardware.org/?probe=dbb66895b3) | Nov 11, 2020 |
| MSI           | MS-7388                     | [53d8276c31](https://linux-hardware.org/?probe=53d8276c31) | Nov 11, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [ec1f424331](https://linux-hardware.org/?probe=ec1f424331) | Nov 10, 2020 |
| ASUSTek       | M5A97 PRO                   | [d8ba2c8390](https://linux-hardware.org/?probe=d8ba2c8390) | Nov 08, 2020 |
| ASUSTek       | TUF B360-PLUS GAMING        | [bfd35c3502](https://linux-hardware.org/?probe=bfd35c3502) | Nov 07, 2020 |
| ASUSTek       | Z170-P                      | [4040863fb9](https://linux-hardware.org/?probe=4040863fb9) | Nov 06, 2020 |
| ASRock        | G41M-VS3                    | [1f33e0939d](https://linux-hardware.org/?probe=1f33e0939d) | Nov 05, 2020 |
| ASUSTek       | Z170-P                      | [c176e7d9a4](https://linux-hardware.org/?probe=c176e7d9a4) | Nov 04, 2020 |
| Biostar       | NF61V-M2                    | [56595b1eff](https://linux-hardware.org/?probe=56595b1eff) | Nov 01, 2020 |
| HP            | 2B0B 100                    | [a051170e5f](https://linux-hardware.org/?probe=a051170e5f) | Oct 31, 2020 |
| Gigabyte      | GA-970A-D3                  | [8f5f5aba10](https://linux-hardware.org/?probe=8f5f5aba10) | Oct 31, 2020 |
| Gigabyte      | M68M-S2P                    | [1c0157261d](https://linux-hardware.org/?probe=1c0157261d) | Oct 29, 2020 |
| Intel         | BANGHO AIO 2300 ID 6185 ... | [20189fcc91](https://linux-hardware.org/?probe=20189fcc91) | Oct 29, 2020 |
| Gigabyte      | AX370-Gaming K5-CF          | [6255a1cca1](https://linux-hardware.org/?probe=6255a1cca1) | Oct 29, 2020 |
| Gigabyte      | H61M-S1                     | [8ed7fab224](https://linux-hardware.org/?probe=8ed7fab224) | Oct 27, 2020 |
| MSI           | K9A2 Platinum               | [3a4439c3a2](https://linux-hardware.org/?probe=3a4439c3a2) | Oct 25, 2020 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [9baffd48cb](https://linux-hardware.org/?probe=9baffd48cb) | Oct 24, 2020 |
| ASUSTek       | PRIME H410M-E               | [28dcd2a96a](https://linux-hardware.org/?probe=28dcd2a96a) | Oct 24, 2020 |
| ASRock        | H55M                        | [4813b32bf1](https://linux-hardware.org/?probe=4813b32bf1) | Oct 23, 2020 |
| ASRock        | H81M-VG4 R2.0               | [1719c8fbd1](https://linux-hardware.org/?probe=1719c8fbd1) | Oct 21, 2020 |
| ASUSTek       | PRIME B450M-A               | [3b7096c49d](https://linux-hardware.org/?probe=3b7096c49d) | Oct 20, 2020 |
| Gigabyte      | B365M DS3H                  | [6a7ddf692b](https://linux-hardware.org/?probe=6a7ddf692b) | Oct 19, 2020 |
| Gigabyte      | B365M DS3H                  | [51ee5ecb70](https://linux-hardware.org/?probe=51ee5ecb70) | Oct 19, 2020 |
| Gigabyte      | GA-MA74GM-S2                | [10a2e03972](https://linux-hardware.org/?probe=10a2e03972) | Oct 19, 2020 |
| ASUSTek       | P5V800-MX                   | [a88e3e04a8](https://linux-hardware.org/?probe=a88e3e04a8) | Oct 17, 2020 |
| ASUSTek       | P5V800-MX                   | [1820121750](https://linux-hardware.org/?probe=1820121750) | Oct 17, 2020 |
| Intel         | DH55TC AAE70932-206         | [56d9daaa92](https://linux-hardware.org/?probe=56d9daaa92) | Oct 12, 2020 |
| MSI           | A68HM-E33 V2                | [7b0fccc85d](https://linux-hardware.org/?probe=7b0fccc85d) | Oct 12, 2020 |
| Supermicro    | PDSBM                       | [16b38dedcf](https://linux-hardware.org/?probe=16b38dedcf) | Oct 11, 2020 |
| NCR           | Pocono                      | [2b57409200](https://linux-hardware.org/?probe=2b57409200) | Oct 11, 2020 |
| ASUSTek       | PRIME A320M-K               | [55e4fca971](https://linux-hardware.org/?probe=55e4fca971) | Oct 08, 2020 |
| ASUSTek       | M4A88TD-M                   | [c018cdb985](https://linux-hardware.org/?probe=c018cdb985) | Oct 06, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [189babb8be](https://linux-hardware.org/?probe=189babb8be) | Oct 05, 2020 |
| MSI           | A68HM-E33 V2                | [a88be898c1](https://linux-hardware.org/?probe=a88be898c1) | Oct 05, 2020 |
| Intel         | D945GCNL AAD97184-102       | [4a43e3fa8c](https://linux-hardware.org/?probe=4a43e3fa8c) | Oct 03, 2020 |
| Intel         | D945GCNL AAD97184-102       | [db86d15d03](https://linux-hardware.org/?probe=db86d15d03) | Oct 03, 2020 |
| ASUSTek       | Z170-P                      | [f272e0f348](https://linux-hardware.org/?probe=f272e0f348) | Oct 03, 2020 |
| Gigabyte      | B450M DS3H-CF               | [f982eeeb38](https://linux-hardware.org/?probe=f982eeeb38) | Oct 03, 2020 |
| Gigabyte      | B450M DS3H-CF               | [2bb987e655](https://linux-hardware.org/?probe=2bb987e655) | Sep 30, 2020 |
| Gigabyte      | B450M DS3H-CF               | [dc408f0c96](https://linux-hardware.org/?probe=dc408f0c96) | Sep 30, 2020 |
| ECS           | H81H3-M4                    | [f681cbb66b](https://linux-hardware.org/?probe=f681cbb66b) | Sep 29, 2020 |
| Gigabyte      | GA-970A-UD3                 | [1cdb4a8c33](https://linux-hardware.org/?probe=1cdb4a8c33) | Sep 28, 2020 |
| ASUSTek       | B75M-A                      | [18e075741d](https://linux-hardware.org/?probe=18e075741d) | Sep 28, 2020 |
| ASUSTek       | PRIME B450M-A               | [a36b437918](https://linux-hardware.org/?probe=a36b437918) | Sep 28, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [0cbed8486e](https://linux-hardware.org/?probe=0cbed8486e) | Sep 28, 2020 |
| ASUSTek       | P5G41-M LX                  | [9cf41cc07f](https://linux-hardware.org/?probe=9cf41cc07f) | Sep 27, 2020 |
| ASUSTek       | P5G41-M LX                  | [f5e1491d35](https://linux-hardware.org/?probe=f5e1491d35) | Sep 27, 2020 |
| MSI           | MS-7312                     | [6fe2f03579](https://linux-hardware.org/?probe=6fe2f03579) | Sep 26, 2020 |
| MSI           | MS-7312                     | [af9ead3738](https://linux-hardware.org/?probe=af9ead3738) | Sep 26, 2020 |
| ASUSTek       | PRIME A320M-K               | [bb3bd6c311](https://linux-hardware.org/?probe=bb3bd6c311) | Sep 25, 2020 |
| ASUSTek       | P8H77-V LE                  | [9da3e61e08](https://linux-hardware.org/?probe=9da3e61e08) | Sep 25, 2020 |
| ASUSTek       | PRIME A320M-K               | [eea2ace04f](https://linux-hardware.org/?probe=eea2ace04f) | Sep 23, 2020 |
| Gigabyte      | H81M-H                      | [bab729c6d0](https://linux-hardware.org/?probe=bab729c6d0) | Sep 22, 2020 |
| ASUSTek       | PRIME H410M-E               | [c64e54f364](https://linux-hardware.org/?probe=c64e54f364) | Sep 20, 2020 |
| ASUSTek       | PRIME H410M-E               | [df8fbe9e18](https://linux-hardware.org/?probe=df8fbe9e18) | Sep 20, 2020 |
| ASUSTek       | PRIME A320M-K               | [0ffa833c96](https://linux-hardware.org/?probe=0ffa833c96) | Sep 20, 2020 |
| ASRock        | H81M-VG4 R2.0               | [0df54860d9](https://linux-hardware.org/?probe=0df54860d9) | Sep 20, 2020 |
| ASUSTek       | ROG Maximus XII FORMULA     | [5152450400](https://linux-hardware.org/?probe=5152450400) | Sep 19, 2020 |
| ASUSTek       | A88XM-PLUS                  | [bdae1a68a5](https://linux-hardware.org/?probe=bdae1a68a5) | Sep 18, 2020 |
| Biostar       | G41D3C                      | [3a5ff2c1a4](https://linux-hardware.org/?probe=3a5ff2c1a4) | Sep 18, 2020 |
| Gigabyte      | H67M-D2-B3                  | [20e75231a2](https://linux-hardware.org/?probe=20e75231a2) | Sep 17, 2020 |
| ASRock        | H81M-VG4 R2.0               | [942c368251](https://linux-hardware.org/?probe=942c368251) | Sep 15, 2020 |
| ASRock        | H81M-VG4 R2.0               | [343dbd225d](https://linux-hardware.org/?probe=343dbd225d) | Sep 15, 2020 |
| Gigabyte      | H67M-D2-B3                  | [d376ce1c35](https://linux-hardware.org/?probe=d376ce1c35) | Sep 12, 2020 |
| Gigabyte      | H67M-D2-B3                  | [3b21ebc9c9](https://linux-hardware.org/?probe=3b21ebc9c9) | Sep 11, 2020 |
| Gigabyte      | M68MT-S2P                   | [b23396f446](https://linux-hardware.org/?probe=b23396f446) | Sep 10, 2020 |
| ECS           | Nettle3                     | [5e5fd822c7](https://linux-hardware.org/?probe=5e5fd822c7) | Sep 09, 2020 |
| ASRock        | G31M-S                      | [a409d7a8ca](https://linux-hardware.org/?probe=a409d7a8ca) | Sep 09, 2020 |
| Foxconn       | 8657MF-series               | [de8bc81155](https://linux-hardware.org/?probe=de8bc81155) | Sep 09, 2020 |
| ASUSTek       | P8H61-M LE                  | [4fdffb335a](https://linux-hardware.org/?probe=4fdffb335a) | Sep 08, 2020 |
| ASUSTek       | P8H61-M LE                  | [7c9c74b288](https://linux-hardware.org/?probe=7c9c74b288) | Sep 08, 2020 |
| Gigabyte      | GA-78LMT-S2                 | [50084e0fd3](https://linux-hardware.org/?probe=50084e0fd3) | Sep 08, 2020 |
| ASRock        | ALiveNF6P-VSTA              | [dd876ba784](https://linux-hardware.org/?probe=dd876ba784) | Sep 08, 2020 |
| ASRock        | ALiveNF6P-VSTA              | [42997fd9bd](https://linux-hardware.org/?probe=42997fd9bd) | Sep 08, 2020 |
| ASUSTek       | PRO A320M-R WI-FI           | [5c0268cb52](https://linux-hardware.org/?probe=5c0268cb52) | Sep 06, 2020 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | [ad229c7f56](https://linux-hardware.org/?probe=ad229c7f56) | Sep 06, 2020 |
| Gigabyte      | M68MT-S2P                   | [e27a9041fe](https://linux-hardware.org/?probe=e27a9041fe) | Sep 06, 2020 |
| MSI           | A68HM-E33 V2                | [ecc825b433](https://linux-hardware.org/?probe=ecc825b433) | Sep 05, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [e37cdf5cb7](https://linux-hardware.org/?probe=e37cdf5cb7) | Sep 03, 2020 |
| Gigabyte      | GA-890FXA-UD5               | [0f7250a912](https://linux-hardware.org/?probe=0f7250a912) | Sep 03, 2020 |
| MSI           | 785GM-E51                   | [8ba46dbf50](https://linux-hardware.org/?probe=8ba46dbf50) | Sep 02, 2020 |
| ASUSTek       | P8H67-V                     | [9bc61b31d4](https://linux-hardware.org/?probe=9bc61b31d4) | Sep 02, 2020 |
| Gigabyte      | H67MA-USB3-B3               | [fca3922984](https://linux-hardware.org/?probe=fca3922984) | Aug 30, 2020 |
| Gigabyte      | H67MA-USB3-B3               | [de1dc9d501](https://linux-hardware.org/?probe=de1dc9d501) | Aug 30, 2020 |
| MSI           | H310M PRO-VDH PLUS          | [605e926286](https://linux-hardware.org/?probe=605e926286) | Aug 28, 2020 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [0da616aa46](https://linux-hardware.org/?probe=0da616aa46) | Aug 28, 2020 |
| Foxconn       | 8657MF-series               | [23a6324378](https://linux-hardware.org/?probe=23a6324378) | Aug 28, 2020 |
| ASRock        | 980DE3/U3S3                 | [06df79a9b3](https://linux-hardware.org/?probe=06df79a9b3) | Aug 27, 2020 |
| ASUSTek       | H81M-E                      | [a73e097c1b](https://linux-hardware.org/?probe=a73e097c1b) | Aug 27, 2020 |
| ASUSTek       | H81M-E                      | [42f03041d8](https://linux-hardware.org/?probe=42f03041d8) | Aug 27, 2020 |
| ASUSTek       | PRO A320M-R WI-FI           | [06c498cfb4](https://linux-hardware.org/?probe=06c498cfb4) | Aug 27, 2020 |
| Foxconn       | 8657MF-series               | [bf0bb0b5e2](https://linux-hardware.org/?probe=bf0bb0b5e2) | Aug 26, 2020 |
| ECS           | Nettle3                     | [d568550b8f](https://linux-hardware.org/?probe=d568550b8f) | Aug 26, 2020 |
| ECS           | Nettle3                     | [414c2922f1](https://linux-hardware.org/?probe=414c2922f1) | Aug 25, 2020 |
| ASUSTek       | PRIME X370-A                | [8b87bebc57](https://linux-hardware.org/?probe=8b87bebc57) | Aug 25, 2020 |
| ASRock        | 980DE3/U3S3                 | [d61de02369](https://linux-hardware.org/?probe=d61de02369) | Aug 22, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | [b28f9ea079](https://linux-hardware.org/?probe=b28f9ea079) | Aug 22, 2020 |
| ASRock        | 980DE3/U3S3                 | [517fd2ce51](https://linux-hardware.org/?probe=517fd2ce51) | Aug 22, 2020 |
| ECS           | H310H5-M2                   | [54b9e42bda](https://linux-hardware.org/?probe=54b9e42bda) | Aug 22, 2020 |
| Biostar       | P4M900-M7 FE Ver:1.0        | [b3294f30c9](https://linux-hardware.org/?probe=b3294f30c9) | Aug 20, 2020 |
| ASUSTek       | P5LD2-X/1333                | [a54a16f888](https://linux-hardware.org/?probe=a54a16f888) | Aug 20, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | [0e03e9c457](https://linux-hardware.org/?probe=0e03e9c457) | Aug 20, 2020 |
| Unknown       | NF-MCP61                    | [3a4c58927d](https://linux-hardware.org/?probe=3a4c58927d) | Aug 17, 2020 |
| ASRock        | B450 Steel Legend           | [ff8b55d6af](https://linux-hardware.org/?probe=ff8b55d6af) | Aug 17, 2020 |
| ASUSTek       | P8Z77-M                     | [140a10487f](https://linux-hardware.org/?probe=140a10487f) | Aug 15, 2020 |
| ASUSTek       | P8Z77-M                     | [865d3592d4](https://linux-hardware.org/?probe=865d3592d4) | Aug 15, 2020 |
| MSI           | 785GM-E51                   | [825e0ed4c7](https://linux-hardware.org/?probe=825e0ed4c7) | Aug 15, 2020 |
| ASRock        | N68-VS3 UCC                 | [8432cad64a](https://linux-hardware.org/?probe=8432cad64a) | Aug 14, 2020 |
| ASRock        | N68-VS3 UCC                 | [ad3f1c3c1a](https://linux-hardware.org/?probe=ad3f1c3c1a) | Aug 14, 2020 |
| ASUSTek       | M5A78L-M LX V2              | [5f4bd85c68](https://linux-hardware.org/?probe=5f4bd85c68) | Aug 14, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [d0f087d90e](https://linux-hardware.org/?probe=d0f087d90e) | Aug 13, 2020 |
| ASRock        | N68-VS3 FX                  | [9ef9d3c2b8](https://linux-hardware.org/?probe=9ef9d3c2b8) | Aug 12, 2020 |
| ASRock        | N68-VS3 FX                  | [98ad628435](https://linux-hardware.org/?probe=98ad628435) | Aug 12, 2020 |
| Gigabyte      | G41MT-S2PT                  | [cdbaae241b](https://linux-hardware.org/?probe=cdbaae241b) | Aug 11, 2020 |
| ASUSTek       | P5GC-MX/1333                | [26d788d76b](https://linux-hardware.org/?probe=26d788d76b) | Aug 10, 2020 |
| ASRock        | N68-VS3 UCC                 | [7e8c46f1c3](https://linux-hardware.org/?probe=7e8c46f1c3) | Aug 09, 2020 |
| ASUSTek       | M2N68-AM Plus               | [a01b1505e9](https://linux-hardware.org/?probe=a01b1505e9) | Aug 07, 2020 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [7efb86308a](https://linux-hardware.org/?probe=7efb86308a) | Aug 07, 2020 |
| ASRock        | A320M-HDV                   | [311f8aaed4](https://linux-hardware.org/?probe=311f8aaed4) | Aug 04, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [9c79ef0e1c](https://linux-hardware.org/?probe=9c79ef0e1c) | Jul 31, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [242b101828](https://linux-hardware.org/?probe=242b101828) | Jul 31, 2020 |
| MSI           | A320M-A PRO MAX             | [491e07a7fa](https://linux-hardware.org/?probe=491e07a7fa) | Jul 30, 2020 |
| MSI           | A320M-A PRO MAX             | [2c15a4821a](https://linux-hardware.org/?probe=2c15a4821a) | Jul 30, 2020 |
| ASRock        | G41M-VS3                    | [bfa97b70c7](https://linux-hardware.org/?probe=bfa97b70c7) | Jul 29, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [bc3cb07c9b](https://linux-hardware.org/?probe=bc3cb07c9b) | Jul 26, 2020 |
| ASUSTek       | M2N68-AM Plus               | [3ff385285a](https://linux-hardware.org/?probe=3ff385285a) | Jul 26, 2020 |
| Biostar       | NF61V-M2                    | [33b2daa41b](https://linux-hardware.org/?probe=33b2daa41b) | Jul 25, 2020 |
| Intel         | D510MO AAE76523-403         | [66d487e419](https://linux-hardware.org/?probe=66d487e419) | Jul 21, 2020 |
| Lenovo        | ThinkCentre M58e 7303A87    | [ca71ce086f](https://linux-hardware.org/?probe=ca71ce086f) | Jul 20, 2020 |
| ASUSTek       | P5G41T-M LX3                | [ce2b0954ee](https://linux-hardware.org/?probe=ce2b0954ee) | Jul 20, 2020 |
| Lenovo        | ThinkCentre M58e 7303A87    | [0f8c6a8994](https://linux-hardware.org/?probe=0f8c6a8994) | Jul 19, 2020 |
| Gigabyte      | B365M DS3H                  | [79c5cea1c1](https://linux-hardware.org/?probe=79c5cea1c1) | Jul 14, 2020 |
| Gigabyte      | B365M DS3H                  | [8baccc57ec](https://linux-hardware.org/?probe=8baccc57ec) | Jul 12, 2020 |
| ASUSTek       | P5G41T-M LX3                | [b7820ff71c](https://linux-hardware.org/?probe=b7820ff71c) | Jul 12, 2020 |
| ASUSTek       | M5A78L-M LX                 | [471645f069](https://linux-hardware.org/?probe=471645f069) | Jul 11, 2020 |
| ASUSTek       | M5A78L-M LX                 | [f357989666](https://linux-hardware.org/?probe=f357989666) | Jul 11, 2020 |
| ASRock        | N68-S                       | [e16c698a18](https://linux-hardware.org/?probe=e16c698a18) | Jul 11, 2020 |
| Gigabyte      | G31M-ES2C                   | [3e10d07bfb](https://linux-hardware.org/?probe=3e10d07bfb) | Jul 10, 2020 |
| HP            | 3647h                       | [d0dd595c74](https://linux-hardware.org/?probe=d0dd595c74) | Jul 10, 2020 |
| ASRock        | H81M-VG4 R2.0               | [bbdc24bff7](https://linux-hardware.org/?probe=bbdc24bff7) | Jul 10, 2020 |
| Gigabyte      | A320M-S2H-CF                | [46ecf6808a](https://linux-hardware.org/?probe=46ecf6808a) | Jul 08, 2020 |
| Gigabyte      | B75M-HD3                    | [761959fe70](https://linux-hardware.org/?probe=761959fe70) | Jul 07, 2020 |
| ASUSTek       | P5G41T-M LX3                | [0a31017fe1](https://linux-hardware.org/?probe=0a31017fe1) | Jul 05, 2020 |
| Biostar       | N68S3B                      | [0c22d256fe](https://linux-hardware.org/?probe=0c22d256fe) | Jul 04, 2020 |
| Foxconn       | A6GMV 0A                    | [cf9a3beaed](https://linux-hardware.org/?probe=cf9a3beaed) | Jul 04, 2020 |
| ASUSTek       | PRIME A320M-K               | [4cceefbe92](https://linux-hardware.org/?probe=4cceefbe92) | Jul 03, 2020 |
| ECS           | H81H3-M4                    | [cd1a1e7310](https://linux-hardware.org/?probe=cd1a1e7310) | Jul 02, 2020 |
| MSI           | MS-6712                     | [afd7ea22ff](https://linux-hardware.org/?probe=afd7ea22ff) | Jun 29, 2020 |
| MSI           | MS-6712                     | [ed6f338500](https://linux-hardware.org/?probe=ed6f338500) | Jun 29, 2020 |
| ECS           | H61H2-MV                    | [3afcdded4a](https://linux-hardware.org/?probe=3afcdded4a) | Jun 27, 2020 |
| MSI           | 990FXA-GD80                 | [99f7066ad4](https://linux-hardware.org/?probe=99f7066ad4) | Jun 24, 2020 |
| MSI           | 990FXA-GD80                 | [a11ffbfcd3](https://linux-hardware.org/?probe=a11ffbfcd3) | Jun 22, 2020 |
| Gigabyte      | F2A68HM-H                   | [ef2a18ef64](https://linux-hardware.org/?probe=ef2a18ef64) | Jun 22, 2020 |
| ASRock        | H81M-VG4 R2.0               | [772452167b](https://linux-hardware.org/?probe=772452167b) | Jun 21, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [9ab9da5b9a](https://linux-hardware.org/?probe=9ab9da5b9a) | Jun 20, 2020 |
| Gigabyte      | MZBSWBP-00                  | [02c5eb9954](https://linux-hardware.org/?probe=02c5eb9954) | Jun 18, 2020 |
| Gigabyte      | CROSS B02                   | [e510d6bf4b](https://linux-hardware.org/?probe=e510d6bf4b) | Jun 16, 2020 |
| Foxconn       | A6GMV 0A                    | [8027418bd3](https://linux-hardware.org/?probe=8027418bd3) | Jun 16, 2020 |
| Unknown       | P4M800CE-8237               | [1e85cb931c](https://linux-hardware.org/?probe=1e85cb931c) | Jun 14, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [47ca82d479](https://linux-hardware.org/?probe=47ca82d479) | Jun 13, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [848eb42e54](https://linux-hardware.org/?probe=848eb42e54) | Jun 13, 2020 |
| Gigabyte      | AX370-Gaming 5              | [5695883f3d](https://linux-hardware.org/?probe=5695883f3d) | Jun 12, 2020 |
| Intel         | D946GZIS AAD66165-302       | [96386c95f7](https://linux-hardware.org/?probe=96386c95f7) | Jun 10, 2020 |
| Gigabyte      | F2A68HM-H                   | [e8f424ff31](https://linux-hardware.org/?probe=e8f424ff31) | Jun 09, 2020 |
| Gigabyte      | F2A68HM-H                   | [12857735fa](https://linux-hardware.org/?probe=12857735fa) | Jun 09, 2020 |
| MSI           | A68HM-E33 V2                | [cb4c6053ca](https://linux-hardware.org/?probe=cb4c6053ca) | Jun 06, 2020 |
| ASUSTek       | P8H67-M PRO                 | [c60bd8dd4d](https://linux-hardware.org/?probe=c60bd8dd4d) | Jun 06, 2020 |
| ASRock        | P4VM8                       | [6958ec038e](https://linux-hardware.org/?probe=6958ec038e) | Jun 06, 2020 |
| ASUSTek       | M4N68T-M-LE-V2              | [b333954ba8](https://linux-hardware.org/?probe=b333954ba8) | Jun 06, 2020 |
| ASRock        | P4VM8                       | [c018c0a70c](https://linux-hardware.org/?probe=c018c0a70c) | Jun 05, 2020 |
| Gigabyte      | G31M-ES2C                   | [17054b3b8e](https://linux-hardware.org/?probe=17054b3b8e) | Jun 05, 2020 |
| Biostar       | NF61V-M2                    | [1dffe7859c](https://linux-hardware.org/?probe=1dffe7859c) | Jun 02, 2020 |
| Intel         | DG31PR AAD97573-306         | [f87050e6e1](https://linux-hardware.org/?probe=f87050e6e1) | Jun 02, 2020 |
| ASRock        | A320M-HDV R4.0              | [c5d60d0373](https://linux-hardware.org/?probe=c5d60d0373) | May 31, 2020 |
| ASUSTek       | M3N78-VM                    | [8f2d6c11af](https://linux-hardware.org/?probe=8f2d6c11af) | May 30, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [36af19c446](https://linux-hardware.org/?probe=36af19c446) | May 30, 2020 |
| ASUSTek       | PRIME X470-PRO              | [0b43d0512b](https://linux-hardware.org/?probe=0b43d0512b) | May 26, 2020 |
| ASUSTek       | PRIME B350M-A               | [4d27f429f7](https://linux-hardware.org/?probe=4d27f429f7) | May 26, 2020 |
| ASUSTek       | P5G41T-M LX3                | [24d4f4fbc3](https://linux-hardware.org/?probe=24d4f4fbc3) | May 25, 2020 |
| Gigabyte      | F2A68HM-H                   | [ca5470c435](https://linux-hardware.org/?probe=ca5470c435) | May 23, 2020 |
| ASUSTek       | PRIME A320M-K               | [14dfb9eb8c](https://linux-hardware.org/?probe=14dfb9eb8c) | May 22, 2020 |
| ASUSTek       | PRIME A320M-K               | [299eb96cce](https://linux-hardware.org/?probe=299eb96cce) | May 22, 2020 |
| Intel         | SE7525RP2 C96126-401        | [727097891c](https://linux-hardware.org/?probe=727097891c) | May 22, 2020 |
| ASRock        | G31M-S                      | [200fc1596e](https://linux-hardware.org/?probe=200fc1596e) | May 22, 2020 |
| ASRock        | N68-S3 UCC                  | [f0fedacf52](https://linux-hardware.org/?probe=f0fedacf52) | May 22, 2020 |
| Biostar       | G41D3C                      | [2d6caced9f](https://linux-hardware.org/?probe=2d6caced9f) | May 22, 2020 |
| MSI           | 970A-G43                    | [cd78d871ac](https://linux-hardware.org/?probe=cd78d871ac) | May 22, 2020 |
| Intel         | DG31PR AAD97573-306         | [5c19f9adbb](https://linux-hardware.org/?probe=5c19f9adbb) | May 22, 2020 |
| Foxconn       | M61PMV FAB A1               | [040f5183b0](https://linux-hardware.org/?probe=040f5183b0) | May 21, 2020 |
| ASUSTek       | M4N68T-M-LE-V2              | [61282a63e4](https://linux-hardware.org/?probe=61282a63e4) | May 21, 2020 |
| Intel         | SE7525RP2 C96126-401        | [e8ef39c190](https://linux-hardware.org/?probe=e8ef39c190) | May 21, 2020 |
| Intel         | SE7525RP2 C96126-401        | [4822a309f2](https://linux-hardware.org/?probe=4822a309f2) | May 21, 2020 |
| Gigabyte      | M68MT-S2                    | [467964b510](https://linux-hardware.org/?probe=467964b510) | May 18, 2020 |
| ASUSTek       | PRIME X570-PRO              | [964da6438e](https://linux-hardware.org/?probe=964da6438e) | May 17, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [0086bd4a1b](https://linux-hardware.org/?probe=0086bd4a1b) | May 15, 2020 |
| ASUSTek       | M4A87TD/USB3                | [204243c295](https://linux-hardware.org/?probe=204243c295) | May 09, 2020 |
| Gigabyte      | Z97X-Gaming 3               | [8e8643e258](https://linux-hardware.org/?probe=8e8643e258) | May 09, 2020 |
| ASUSTek       | M4A87TD/USB3                | [24306e3a1f](https://linux-hardware.org/?probe=24306e3a1f) | May 08, 2020 |
| ASUSTek       | M4A87TD/USB3                | [af4c24eace](https://linux-hardware.org/?probe=af4c24eace) | May 07, 2020 |
| Exo           | Ready C2 - Style C2         | [aa0bb7e5f4](https://linux-hardware.org/?probe=aa0bb7e5f4) | May 07, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [3c02d68725](https://linux-hardware.org/?probe=3c02d68725) | May 07, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [3617db7eb9](https://linux-hardware.org/?probe=3617db7eb9) | May 05, 2020 |
| Gigabyte      | Z87X-UD5H-CF                | [39798ff3d6](https://linux-hardware.org/?probe=39798ff3d6) | May 05, 2020 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [683ea6779d](https://linux-hardware.org/?probe=683ea6779d) | May 05, 2020 |
| ASUSTek       | H81M-K                      | [bb1837e43e](https://linux-hardware.org/?probe=bb1837e43e) | May 02, 2020 |
| Intel         | DZ77SL-50K AAG55115-300     | [cee90bb8e9](https://linux-hardware.org/?probe=cee90bb8e9) | May 02, 2020 |
| MSI           | FM2-A55M-E33                | [761dd67d16](https://linux-hardware.org/?probe=761dd67d16) | May 01, 2020 |
| MSI           | FM2-A55M-E33                | [2bdb61ec85](https://linux-hardware.org/?probe=2bdb61ec85) | May 01, 2020 |
| ASRock        | N68-VS3 FX                  | [3d59c603a2](https://linux-hardware.org/?probe=3d59c603a2) | Apr 29, 2020 |
| Gigabyte      | E2500N                      | [a19d990c02](https://linux-hardware.org/?probe=a19d990c02) | Apr 29, 2020 |
| Gigabyte      | G31M-ES2C                   | [513463193d](https://linux-hardware.org/?probe=513463193d) | Apr 28, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [085c5b8ed2](https://linux-hardware.org/?probe=085c5b8ed2) | Apr 27, 2020 |
| ASUSTek       | PRIME A320M-K               | [96c694803d](https://linux-hardware.org/?probe=96c694803d) | Apr 26, 2020 |
| ASUSTek       | PRIME A320M-K               | [d36d25f58a](https://linux-hardware.org/?probe=d36d25f58a) | Apr 26, 2020 |
| ASUSTek       | PRIME A320M-A               | [429e1655be](https://linux-hardware.org/?probe=429e1655be) | Apr 24, 2020 |
| Dell          | 0TTDMJ A00                  | [c2f5ed19be](https://linux-hardware.org/?probe=c2f5ed19be) | Apr 24, 2020 |
| ASUSTek       | B150M-A                     | [36acb6d9ac](https://linux-hardware.org/?probe=36acb6d9ac) | Apr 23, 2020 |
| ASUSTek       | B150M-A                     | [17b23101d0](https://linux-hardware.org/?probe=17b23101d0) | Apr 23, 2020 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [d2325d6ddf](https://linux-hardware.org/?probe=d2325d6ddf) | Apr 23, 2020 |
| Gigabyte      | AM1M-S2H                    | [70238ca50c](https://linux-hardware.org/?probe=70238ca50c) | Apr 23, 2020 |
| Gigabyte      | AM1M-S2H                    | [fcb68181d7](https://linux-hardware.org/?probe=fcb68181d7) | Apr 23, 2020 |
| MSI           | Z170A GAMING M3             | [85873789d9](https://linux-hardware.org/?probe=85873789d9) | Apr 18, 2020 |
| MSI           | Z170A GAMING M3             | [28e8f05fbe](https://linux-hardware.org/?probe=28e8f05fbe) | Apr 18, 2020 |
| MSI           | MS-7309 10                  | [e9ae798eec](https://linux-hardware.org/?probe=e9ae798eec) | Apr 17, 2020 |
| MSI           | MS-7309 10                  | [87971d36b2](https://linux-hardware.org/?probe=87971d36b2) | Apr 17, 2020 |
| MSI           | A68HM-E33 V2                | [09867c73ec](https://linux-hardware.org/?probe=09867c73ec) | Apr 17, 2020 |
| MSI           | A68HM-E33 V2                | [64e88cc13b](https://linux-hardware.org/?probe=64e88cc13b) | Apr 16, 2020 |
| MSI           | A68HM-E33 V2                | [614c155963](https://linux-hardware.org/?probe=614c155963) | Apr 16, 2020 |
| ASRock        | 960GC-GS FX                 | [4e01237bc7](https://linux-hardware.org/?probe=4e01237bc7) | Apr 14, 2020 |
| MSI           | A68HM GAMING                | [614f005109](https://linux-hardware.org/?probe=614f005109) | Apr 12, 2020 |
| Gigabyte      | 945GCM-S2C                  | [bd2ab9908f](https://linux-hardware.org/?probe=bd2ab9908f) | Apr 12, 2020 |
| Gigabyte      | 945GCM-S2C                  | [bb2022fdd2](https://linux-hardware.org/?probe=bb2022fdd2) | Apr 11, 2020 |
| ASRock        | N68C-S UCC                  | [c6df4257a4](https://linux-hardware.org/?probe=c6df4257a4) | Apr 11, 2020 |
| Gigabyte      | B75N                        | [8f801d19c5](https://linux-hardware.org/?probe=8f801d19c5) | Apr 09, 2020 |
| Gigabyte      | M68MT-S2                    | [f3a49b7907](https://linux-hardware.org/?probe=f3a49b7907) | Apr 09, 2020 |
| ASUSTek       | M2N-MX SE Plus              | [f0d9f1c866](https://linux-hardware.org/?probe=f0d9f1c866) | Apr 08, 2020 |
| Gigabyte      | Z170M-D3H-CF                | [994cb23a71](https://linux-hardware.org/?probe=994cb23a71) | Apr 04, 2020 |
| Gigabyte      | Z170M-D3H-CF                | [0d7e0a5103](https://linux-hardware.org/?probe=0d7e0a5103) | Apr 04, 2020 |
| ASUSTek       | H170M-E D3                  | [12731c1f47](https://linux-hardware.org/?probe=12731c1f47) | Apr 04, 2020 |
| ASUSTek       | H170M-E D3                  | [5744bb99bd](https://linux-hardware.org/?probe=5744bb99bd) | Mar 30, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | [cedd6e411b](https://linux-hardware.org/?probe=cedd6e411b) | Mar 26, 2020 |
| ASRock        | H110M-HDV R3.0              | [ca124879fe](https://linux-hardware.org/?probe=ca124879fe) | Mar 23, 2020 |
| MSI           | A68HM-E33 V2                | [17a2939033](https://linux-hardware.org/?probe=17a2939033) | Mar 20, 2020 |
| ASUSTek       | B150M-C                     | [f55e47a5ef](https://linux-hardware.org/?probe=f55e47a5ef) | Mar 19, 2020 |
| ASUSTek       | F1A75-M LE                  | [e4e783dd0e](https://linux-hardware.org/?probe=e4e783dd0e) | Mar 17, 2020 |
| ASUSTek       | F1A75-M LE                  | [f576b80a67](https://linux-hardware.org/?probe=f576b80a67) | Mar 17, 2020 |
| Biostar       | G41D3C                      | [be9d183299](https://linux-hardware.org/?probe=be9d183299) | Mar 11, 2020 |
| MSI           | A320M PRO-M2 V2             | [51366f30d7](https://linux-hardware.org/?probe=51366f30d7) | Mar 08, 2020 |
| ASUSTek       | P5GC-MX/1333                | [aa62377696](https://linux-hardware.org/?probe=aa62377696) | Mar 07, 2020 |
| ASUSTek       | M4A87TD/USB3                | [3eaddd0dac](https://linux-hardware.org/?probe=3eaddd0dac) | Mar 04, 2020 |
| ASUSTek       | M4A87TD/USB3                | [4a8c4362e9](https://linux-hardware.org/?probe=4a8c4362e9) | Mar 04, 2020 |
| ASRock        | N68C-S UCC                  | [15922b7027](https://linux-hardware.org/?probe=15922b7027) | Mar 03, 2020 |
| Biostar       | G41D3C                      | [72d048019c](https://linux-hardware.org/?probe=72d048019c) | Feb 29, 2020 |
| ASUSTek       | M3A78-EM                    | [bc863f3ddc](https://linux-hardware.org/?probe=bc863f3ddc) | Feb 29, 2020 |
| ASRock        | FM2A68M-DG3+                | [adf712075e](https://linux-hardware.org/?probe=adf712075e) | Feb 25, 2020 |
| Biostar       | NF61V-M2                    | [9fdb3bad8b](https://linux-hardware.org/?probe=9fdb3bad8b) | Feb 23, 2020 |
| Gigabyte      | M68MT-S2                    | [dd8e2753eb](https://linux-hardware.org/?probe=dd8e2753eb) | Feb 22, 2020 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [85f0d8c596](https://linux-hardware.org/?probe=85f0d8c596) | Feb 20, 2020 |
| ASUSTek       | PRIME X470-PRO              | [95427bc05e](https://linux-hardware.org/?probe=95427bc05e) | Feb 13, 2020 |
| Gigabyte      | H170M-D3H DDR3-CF           | [dc5bc429a8](https://linux-hardware.org/?probe=dc5bc429a8) | Feb 13, 2020 |
| ASUSTek       | H81M-A                      | [4267e74d14](https://linux-hardware.org/?probe=4267e74d14) | Feb 13, 2020 |
| Gigabyte      | G41MT-S2PT                  | [c4f8430eab](https://linux-hardware.org/?probe=c4f8430eab) | Feb 12, 2020 |
| Gigabyte      | G41MT-S2PT                  | [32f58663d3](https://linux-hardware.org/?probe=32f58663d3) | Feb 12, 2020 |
| ASUSTek       | H81M-A                      | [d263970407](https://linux-hardware.org/?probe=d263970407) | Feb 07, 2020 |
| ASUSTek       | Maximus IX HERO             | [e4904effa1](https://linux-hardware.org/?probe=e4904effa1) | Feb 05, 2020 |
| ASUSTek       | Maximus IX HERO             | [91c8a51232](https://linux-hardware.org/?probe=91c8a51232) | Feb 05, 2020 |
| Biostar       | G41D3C                      | [557b25a6aa](https://linux-hardware.org/?probe=557b25a6aa) | Feb 03, 2020 |
| ASRock        | N73V-S                      | [80b08d6e38](https://linux-hardware.org/?probe=80b08d6e38) | Jan 27, 2020 |
| ASRock        | N73V-S                      | [1f67c1102b](https://linux-hardware.org/?probe=1f67c1102b) | Jan 26, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [cf425f706d](https://linux-hardware.org/?probe=cf425f706d) | Jan 16, 2020 |
| Biostar       | NF61V-M2                    | [7f7c5ca1ee](https://linux-hardware.org/?probe=7f7c5ca1ee) | Jan 14, 2020 |
| Biostar       | NF61V-M2                    | [a28808bbd5](https://linux-hardware.org/?probe=a28808bbd5) | Jan 14, 2020 |
| ASRock        | N68-VS3 UCC                 | [1be4dca10e](https://linux-hardware.org/?probe=1be4dca10e) | Dec 31, 2019 |
| ASUSTek       | AM1M-A                      | [c1d6491aeb](https://linux-hardware.org/?probe=c1d6491aeb) | Dec 26, 2019 |
| Intel         | DH55HC AAE70933-501         | [64266b67a2](https://linux-hardware.org/?probe=64266b67a2) | Dec 26, 2019 |
| ASRock        | N68-S                       | [68248270ee](https://linux-hardware.org/?probe=68248270ee) | Dec 23, 2019 |
| ASRock        | N68-S                       | [1879c58976](https://linux-hardware.org/?probe=1879c58976) | Dec 23, 2019 |
| HP            | 1998                        | [93aa57fd71](https://linux-hardware.org/?probe=93aa57fd71) | Dec 03, 2019 |
| MSI           | B350 GAMING PLUS            | [3833787efa](https://linux-hardware.org/?probe=3833787efa) | Nov 28, 2019 |
| ECS           | GeForce 8000 series         | [d9abaf941a](https://linux-hardware.org/?probe=d9abaf941a) | Nov 22, 2019 |
| Gigabyte      | F2A68HM-H                   | [b9efdbd9ea](https://linux-hardware.org/?probe=b9efdbd9ea) | Nov 19, 2019 |
| ASRock        | N68C-GS4 FX                 | [7a029501a0](https://linux-hardware.org/?probe=7a029501a0) | Nov 19, 2019 |
| ASUSTek       | P4S800                      | [9c2f7c51ba](https://linux-hardware.org/?probe=9c2f7c51ba) | Nov 16, 2019 |
| HP            | 0A60h                       | [cb90d2b783](https://linux-hardware.org/?probe=cb90d2b783) | Nov 12, 2019 |
| HP            | 0A60h                       | [3b5309dcee](https://linux-hardware.org/?probe=3b5309dcee) | Nov 11, 2019 |
| ASRock        | N68-S3 UCC                  | [4d8c58a461](https://linux-hardware.org/?probe=4d8c58a461) | Nov 07, 2019 |
| Biostar       | G41D3C                      | [cbb9ad4ce6](https://linux-hardware.org/?probe=cbb9ad4ce6) | Nov 04, 2019 |
| Biostar       | G41D3C                      | [8b86fec777](https://linux-hardware.org/?probe=8b86fec777) | Nov 04, 2019 |
| Biostar       | G41D3C                      | [fa37a129b7](https://linux-hardware.org/?probe=fa37a129b7) | Nov 04, 2019 |
| ASRock        | FM2A88M-HD+ R2.0            | [5a767fdef3](https://linux-hardware.org/?probe=5a767fdef3) | Oct 31, 2019 |
| ASRock        | FM2A88M-HD+ R2.0            | [7272a97208](https://linux-hardware.org/?probe=7272a97208) | Oct 31, 2019 |
| Gigabyte      | 970A-UD3P                   | [9ec37bb569](https://linux-hardware.org/?probe=9ec37bb569) | Oct 24, 2019 |
| MSI           | MS-7309                     | [c137270c84](https://linux-hardware.org/?probe=c137270c84) | Oct 20, 2019 |
| Gigabyte      | GA-MA78GM-US2H              | [2e1913401b](https://linux-hardware.org/?probe=2e1913401b) | Oct 11, 2019 |
| Gigabyte      | A320M-S2H-CF                | [12b9b82e3a](https://linux-hardware.org/?probe=12b9b82e3a) | Oct 04, 2019 |
| Gigabyte      | H61M-S1                     | [dc52bfa103](https://linux-hardware.org/?probe=dc52bfa103) | Oct 04, 2019 |
| ASUSTek       | P5LD2-X/1333                | [198cd7bfca](https://linux-hardware.org/?probe=198cd7bfca) | Sep 26, 2019 |
| Gigabyte      | G31M-S2C                    | [a04efa3977](https://linux-hardware.org/?probe=a04efa3977) | Sep 14, 2019 |
| Gigabyte      | F2A88XM-D3H                 | [e160c46127](https://linux-hardware.org/?probe=e160c46127) | Sep 05, 2019 |
| Intel         | DP67DE AAG10217-304         | [da4007d3c0](https://linux-hardware.org/?probe=da4007d3c0) | Sep 01, 2019 |
| ASUSTek       | PRIME X470-PRO              | [8eefb151a2](https://linux-hardware.org/?probe=8eefb151a2) | Sep 01, 2019 |
| ASRock        | H310M-HDV                   | [cbf4c96a56](https://linux-hardware.org/?probe=cbf4c96a56) | Aug 24, 2019 |
| ASRock        | H310M-HDV                   | [805153a96e](https://linux-hardware.org/?probe=805153a96e) | Aug 24, 2019 |
| Biostar       | G41D3C                      | [bb0f528c46](https://linux-hardware.org/?probe=bb0f528c46) | Aug 22, 2019 |
| Lenovo        | MAHOBAY NO DPK              | [17db309bb5](https://linux-hardware.org/?probe=17db309bb5) | Aug 20, 2019 |
| Biostar       | N61PB-M2S                   | [73e190711f](https://linux-hardware.org/?probe=73e190711f) | Aug 17, 2019 |
| ASRock        | Z77 Pro3                    | [21bbb290c7](https://linux-hardware.org/?probe=21bbb290c7) | Aug 15, 2019 |
| Biostar       | G41D3C                      | [55e1405739](https://linux-hardware.org/?probe=55e1405739) | Aug 14, 2019 |
| Biostar       | G41D3C                      | [cacab2f28b](https://linux-hardware.org/?probe=cacab2f28b) | Aug 06, 2019 |
| ASUSTek       | A88XM-PLUS                  | [af4dda2ab1](https://linux-hardware.org/?probe=af4dda2ab1) | Aug 05, 2019 |
| MSI           | H310M PRO-VH                | [65a25655da](https://linux-hardware.org/?probe=65a25655da) | Jul 29, 2019 |
| Gigabyte      | M61PME-S2P                  | [8b844898f3](https://linux-hardware.org/?probe=8b844898f3) | Jul 29, 2019 |
| Gigabyte      | F2A55M-HD2                  | [32e1c72baa](https://linux-hardware.org/?probe=32e1c72baa) | Jul 27, 2019 |
| ASRock        | AM1B-M                      | [54fb4ae774](https://linux-hardware.org/?probe=54fb4ae774) | Jul 23, 2019 |
| ASRock        | ALiveNF6G-VSTA              | [ff78bfbb07](https://linux-hardware.org/?probe=ff78bfbb07) | Jul 23, 2019 |
| Biostar       | G41D3C                      | [f3698d2f73](https://linux-hardware.org/?probe=f3698d2f73) | Jul 20, 2019 |
| Dell          | 0D28YY A00                  | [5c380fec25](https://linux-hardware.org/?probe=5c380fec25) | Jul 19, 2019 |
| Dell          | 0D28YY A00                  | [7b0bfea310](https://linux-hardware.org/?probe=7b0bfea310) | Jul 19, 2019 |
| ASUSTek       | Z87M-PLUS                   | [9a7b14fc6f](https://linux-hardware.org/?probe=9a7b14fc6f) | Jul 11, 2019 |
| ASUSTek       | P8H61-M LE                  | [4b83e684ca](https://linux-hardware.org/?probe=4b83e684ca) | Jul 08, 2019 |
| Biostar       | G41D3C                      | [c4e5301669](https://linux-hardware.org/?probe=c4e5301669) | Jun 26, 2019 |
| ASUSTek       | P5KPL-AM SE                 | [85261dc7a2](https://linux-hardware.org/?probe=85261dc7a2) | Jun 25, 2019 |
| ASUSTek       | P5KPL-AM SE                 | [dc33037449](https://linux-hardware.org/?probe=dc33037449) | Jun 25, 2019 |
| MSI           | H110M PRO-VH PLUS           | [bd555cc1c4](https://linux-hardware.org/?probe=bd555cc1c4) | Jun 19, 2019 |
| Biostar       | G41D3C                      | [aa57f5b813](https://linux-hardware.org/?probe=aa57f5b813) | Jun 19, 2019 |
| ASUSTek       | P5QPL-VM EPU                | [d5f4bdb1b5](https://linux-hardware.org/?probe=d5f4bdb1b5) | Jun 19, 2019 |
| Biostar       | G41D3C                      | [4ab9c7f396](https://linux-hardware.org/?probe=4ab9c7f396) | Jun 17, 2019 |
| MSI           | H310M PRO-VH                | [673ec6c48f](https://linux-hardware.org/?probe=673ec6c48f) | Jun 07, 2019 |
| Gigabyte      | 970A-UD3P                   | [0533339e4e](https://linux-hardware.org/?probe=0533339e4e) | Jun 05, 2019 |
| ASUSTek       | M2N-MX SE                   | [7a7933f5d5](https://linux-hardware.org/?probe=7a7933f5d5) | Jun 02, 2019 |
| ASUSTek       | M2N-MX SE                   | [bd147041d2](https://linux-hardware.org/?probe=bd147041d2) | May 31, 2019 |
| ASUSTek       | M2N-MX SE                   | [d2433a06e2](https://linux-hardware.org/?probe=d2433a06e2) | May 31, 2019 |
| MSI           | A68HM-E33 V2                | [5d88529d41](https://linux-hardware.org/?probe=5d88529d41) | May 31, 2019 |
| MSI           | FM2-A55M-E33                | [373fa45c3b](https://linux-hardware.org/?probe=373fa45c3b) | May 25, 2019 |
| ASUSTek       | M5A97 PRO                   | [6fb7a2e4d4](https://linux-hardware.org/?probe=6fb7a2e4d4) | May 16, 2019 |
| ASUSTek       | M5A97 PRO                   | [865c2e5830](https://linux-hardware.org/?probe=865c2e5830) | May 15, 2019 |
| Gigabyte      | H61M-S1                     | [b778c1f35d](https://linux-hardware.org/?probe=b778c1f35d) | May 13, 2019 |
| MSI           | FM2-A55M-E33                | [e9d0041bee](https://linux-hardware.org/?probe=e9d0041bee) | May 09, 2019 |
| Intel         | 945GCT-M                    | [413ae4ff4f](https://linux-hardware.org/?probe=413ae4ff4f) | May 07, 2019 |
| Biostar       | G41D3C                      | [3da408f111](https://linux-hardware.org/?probe=3da408f111) | May 06, 2019 |
| Gigabyte      | H61M-S1                     | [56e6743178](https://linux-hardware.org/?probe=56e6743178) | May 06, 2019 |
| Biostar       | NF61V-M2                    | [f62d04edeb](https://linux-hardware.org/?probe=f62d04edeb) | May 01, 2019 |
| ASUSTek       | A88XM-PLUS                  | [61dac138e7](https://linux-hardware.org/?probe=61dac138e7) | May 01, 2019 |
| ASUSTek       | P5KPL-AM SE                 | [03b0dbb48a](https://linux-hardware.org/?probe=03b0dbb48a) | Apr 30, 2019 |
| Biostar       | NF61S-M2B                   | [fefb26c581](https://linux-hardware.org/?probe=fefb26c581) | Apr 29, 2019 |
| Gigabyte      | Z270X-Gaming K5             | [d5e973ef9c](https://linux-hardware.org/?probe=d5e973ef9c) | Apr 29, 2019 |
| Biostar       | GF8100 M2+ TE               | [4c41d80789](https://linux-hardware.org/?probe=4c41d80789) | Apr 22, 2019 |
| ASUSTek       | M2N68-AM SE2                | [da40ffb555](https://linux-hardware.org/?probe=da40ffb555) | Apr 17, 2019 |
| Gigabyte      | F2A68HM-H                   | [0b2b8c9e82](https://linux-hardware.org/?probe=0b2b8c9e82) | Apr 10, 2019 |
| Intel         | DH61WW AAG23116-206         | [3859a12973](https://linux-hardware.org/?probe=3859a12973) | Apr 05, 2019 |
| Gigabyte      | F2A68HM-H                   | [9953055955](https://linux-hardware.org/?probe=9953055955) | Apr 03, 2019 |
| Biostar       | NF61S-M2B                   | [181bcf59f8](https://linux-hardware.org/?probe=181bcf59f8) | Mar 30, 2019 |
| Gigabyte      | Z97X-Gaming 5               | [87b458e743](https://linux-hardware.org/?probe=87b458e743) | Mar 27, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | [292785f9ec](https://linux-hardware.org/?probe=292785f9ec) | Mar 26, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | [58b602ec64](https://linux-hardware.org/?probe=58b602ec64) | Mar 25, 2019 |
| ASUSTek       | Z170M-E D3                  | [6586aa4510](https://linux-hardware.org/?probe=6586aa4510) | Mar 25, 2019 |
| EPoX Compu... | MCP61S DDR2: AGF6110-M S... | [efd322e0ad](https://linux-hardware.org/?probe=efd322e0ad) | Mar 24, 2019 |
| ASUSTek       | P8H77-M                     | [9794c32027](https://linux-hardware.org/?probe=9794c32027) | Mar 22, 2019 |
| Gigabyte      | H170M-D3H-CF                | [2aa617f166](https://linux-hardware.org/?probe=2aa617f166) | Mar 12, 2019 |
| PCChips       | A15G                        | [3f9f5fb840](https://linux-hardware.org/?probe=3f9f5fb840) | Feb 06, 2019 |
| MSI           | A68HM-E33 V2                | [229d3e983a](https://linux-hardware.org/?probe=229d3e983a) | Feb 02, 2019 |
| ASRock        | N68-VS3 FX                  | [33424146a7](https://linux-hardware.org/?probe=33424146a7) | Jan 07, 2019 |
| ASRock        | N68-VS3 FX                  | [4a220985a6](https://linux-hardware.org/?probe=4a220985a6) | Jan 06, 2019 |
| ASRock        | N68-VS3 FX                  | [7702cc876b](https://linux-hardware.org/?probe=7702cc876b) | Jan 06, 2019 |
| MSI           | Z370-A PRO                  | [4ca529a0c5](https://linux-hardware.org/?probe=4ca529a0c5) | Dec 08, 2018 |
| MSI           | Z370-A PRO                  | [9a73264482](https://linux-hardware.org/?probe=9a73264482) | Dec 06, 2018 |
| Gigabyte      | H110N-CF                    | [1e2174ee6b](https://linux-hardware.org/?probe=1e2174ee6b) | Nov 22, 2018 |
| ASUSTek       | P5GC-MX/1333                | [df08e5122c](https://linux-hardware.org/?probe=df08e5122c) | Nov 19, 2018 |
| ASUSTek       | P5GC-MX/1333                | [62b18b22f1](https://linux-hardware.org/?probe=62b18b22f1) | Nov 19, 2018 |
| Gigabyte      | AX370M-Gaming 3-CF          | [25b5150aeb](https://linux-hardware.org/?probe=25b5150aeb) | Nov 10, 2018 |
| Gigabyte      | AX370M-Gaming 3-CF          | [b0bac0bef5](https://linux-hardware.org/?probe=b0bac0bef5) | Nov 10, 2018 |
| Gigabyte      | AX370M-Gaming 3-CF          | [c1463b52ca](https://linux-hardware.org/?probe=c1463b52ca) | Nov 10, 2018 |
| Gigabyte      | H110M-H-CF                  | [730a46747b](https://linux-hardware.org/?probe=730a46747b) | Nov 07, 2018 |
| ASRock        | G31M-VS                     | [3d1c593d0d](https://linux-hardware.org/?probe=3d1c593d0d) | Nov 07, 2018 |
| ASRock        | G31M-VS                     | [82f4eb6692](https://linux-hardware.org/?probe=82f4eb6692) | Nov 07, 2018 |
| Gigabyte      | H110M-H-CF                  | [0e7a915eb4](https://linux-hardware.org/?probe=0e7a915eb4) | Oct 30, 2018 |
| MSI           | MS-7438 100                 | [6596972d8e](https://linux-hardware.org/?probe=6596972d8e) | Oct 26, 2018 |
| MSI           | MS-7438 100                 | [16c1f310cd](https://linux-hardware.org/?probe=16c1f310cd) | Oct 26, 2018 |
| ASUSTek       | P5KPL-AM SE                 | [2c5e69565f](https://linux-hardware.org/?probe=2c5e69565f) | Aug 28, 2018 |
| ASUSTek       | P5V800-MX                   | [edf7bdef30](https://linux-hardware.org/?probe=edf7bdef30) | Mar 14, 2018 |
| ASUSTek       | P5V800-MX                   | [81ea33a552](https://linux-hardware.org/?probe=81ea33a552) | Mar 13, 2018 |
| ASUSTek       | H61M-K                      | [b1ac5c0e7f](https://linux-hardware.org/?probe=b1ac5c0e7f) | Dec 14, 2017 |
| ASRock        | Z97 Pro4                    | [bde4c0bf7f](https://linux-hardware.org/?probe=bde4c0bf7f) | Apr 24, 2017 |
| ASUSTek       | M5A78L-M LX3                | [b5a4e26211](https://linux-hardware.org/?probe=b5a4e26211) | Nov 05, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 111      | 17.32%  |
| Ubuntu 18.04                 | 70       | 10.92%  |
| OpenMandriva 4.2             | 30       | 4.68%   |
| OpenMandriva 4.3             | 19       | 2.96%   |
| Zorin 15                     | 15       | 2.34%   |
| Ubuntu 22.04                 | 15       | 2.34%   |
| Linux Mint 20.2              | 15       | 2.34%   |
| KDE neon 20.04               | 13       | 2.03%   |
| Debian 11                    | 13       | 2.03%   |
| Linux Mint 20.1              | 12       | 1.87%   |
| Linux Mint 20                | 12       | 1.87%   |
| Xubuntu 20.04                | 11       | 1.72%   |
| Linux Mint 19.3              | 11       | 1.72%   |
| Xubuntu 18.04                | 10       | 1.56%   |
| Ubuntu 21.04                 | 10       | 1.56%   |
| Manjaro                      | 10       | 1.56%   |
| Kubuntu 20.04                | 10       | 1.56%   |
| Zorin 16                     | 9        | 1.4%    |
| Ubuntu MATE 20.04            | 9        | 1.4%    |
| Pop!_OS 21.04                | 9        | 1.4%    |
| Linux Mint 20.3              | 8        | 1.25%   |
| ArcoLinux Rolling            | 8        | 1.25%   |
| Arch Rolling                 | 8        | 1.25%   |
| Ubuntu 21.10                 | 7        | 1.09%   |
| Ubuntu 19.10                 | 7        | 1.09%   |
| Ubuntu 19.04                 | 7        | 1.09%   |
| Pop!_OS 20.04                | 6        | 0.94%   |
| Ubuntu 20.10                 | 5        | 0.78%   |
| Ubuntu 16.04                 | 5        | 0.78%   |
| Fedora 36                    | 5        | 0.78%   |
| BlackPanther 18.1            | 5        | 0.78%   |
| Pop!_OS 20.10                | 4        | 0.62%   |
| Linux Mint 19.2              | 4        | 0.62%   |
| Linux Mint 19.1              | 4        | 0.62%   |
| Fedora 34                    | 4        | 0.62%   |
| Fedora 33                    | 4        | 0.62%   |
| Fedora 32                    | 4        | 0.62%   |
| Clear Linux 35000            | 4        | 0.62%   |
| Xubuntu 16.04                | 3        | 0.47%   |
| Ubuntu MATE 18.04            | 3        | 0.47%   |
| Ubuntu 18.10                 | 3        | 0.47%   |
| ROSA R11.1                   | 3        | 0.47%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 0.47%   |
| OpenMandriva 4.50            | 3        | 0.47%   |
| LMDE 4                       | 3        | 0.47%   |
| KDE neon 18.04               | 3        | 0.47%   |
| Fedora 31                    | 3        | 0.47%   |
| Fedora 29                    | 3        | 0.47%   |
| Elementary 6                 | 3        | 0.47%   |
| Arch                         | 3        | 0.47%   |
| UbuntuDDE 20.04              | 2        | 0.31%   |
| Sparky 6                     | 2        | 0.31%   |
| ROSA R8.1                    | 2        | 0.31%   |
| ROSA R11                     | 2        | 0.31%   |
| ROSA R10                     | 2        | 0.31%   |
| ROSA 12.2                    | 2        | 0.31%   |
| RHEL 8                       | 2        | 0.31%   |
| Reborn OS                    | 2        | 0.31%   |
| Peppermint 10                | 2        | 0.31%   |
| Manjaro 21.2.6               | 2        | 0.31%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 231      | 37.44%  |
| Linux Mint    | 60       | 9.72%   |
| OpenMandriva  | 53       | 8.59%   |
| Fedora        | 26       | 4.21%   |
| Xubuntu       | 25       | 4.05%   |
| Zorin         | 24       | 3.89%   |
| Pop!_OS       | 20       | 3.24%   |
| Debian        | 19       | 3.08%   |
| Manjaro       | 17       | 2.76%   |
| KDE neon      | 16       | 2.59%   |
| Ubuntu MATE   | 14       | 2.27%   |
| Kubuntu       | 13       | 2.11%   |
| ROSA          | 12       | 1.94%   |
| Arch          | 11       | 1.78%   |
| Clear Linux   | 8        | 1.3%    |
| ArcoLinux     | 8        | 1.3%    |
| Elementary    | 6        | 0.97%   |
| Endless       | 5        | 0.81%   |
| BlackPanther  | 5        | 0.81%   |
| Lubuntu       | 4        | 0.65%   |
| UbuntuDDE     | 3        | 0.49%   |
| Ubuntu Budgie | 3        | 0.49%   |
| openSUSE      | 3        | 0.49%   |
| LMDE          | 3        | 0.49%   |
| Gentoo        | 3        | 0.49%   |
| EndeavourOS   | 3        | 0.49%   |
| Sparky        | 2        | 0.32%   |
| RHEL          | 2        | 0.32%   |
| Reborn OS     | 2        | 0.32%   |
| Peppermint    | 2        | 0.32%   |
| Devuan        | 2        | 0.32%   |
| Deepin        | 2        | 0.32%   |
| Void Linux    | 1        | 0.16%   |
| Ubuntu Studio | 1        | 0.16%   |
| Q4OS          | 1        | 0.16%   |
| Mageia        | 1        | 0.16%   |
| LinuxFX       | 1        | 0.16%   |
| Garuda Linux  | 1        | 0.16%   |
| Feren OS      | 1        | 0.16%   |
| Artix         | 1        | 0.16%   |
| antiX         | 1        | 0.16%   |
| Alpine        | 1        | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 29       | 4.16%   |
| 5.4.0-42-generic         | 23       | 3.3%    |
| 5.16.7-desktop-1omv4003  | 18       | 2.58%   |
| 5.4.0-48-generic         | 12       | 1.72%   |
| 5.4.0-26-generic         | 10       | 1.43%   |
| 5.8.0-53-generic         | 9        | 1.29%   |
| 5.4.0-52-generic         | 9        | 1.29%   |
| 5.4.0-74-generic         | 8        | 1.15%   |
| 5.4.0-37-generic         | 8        | 1.15%   |
| 5.3.0-53-generic         | 7        | 1%      |
| 5.15.0-41-generic        | 7        | 1%      |
| 5.13.0-28-generic        | 7        | 1%      |
| 5.4.0-91-generic         | 6        | 0.86%   |
| 5.4.0-80-generic         | 6        | 0.86%   |
| 5.4.0-40-generic         | 6        | 0.86%   |
| 5.3.0-46-generic         | 6        | 0.86%   |
| 5.11.0-25-generic        | 6        | 0.86%   |
| 5.8.0-55-generic         | 5        | 0.72%   |
| 5.4.0-77-generic         | 5        | 0.72%   |
| 5.4.0-72-generic         | 5        | 0.72%   |
| 5.4.0-65-generic         | 5        | 0.72%   |
| 5.4.0-53-generic         | 5        | 0.72%   |
| 5.4.0-47-generic         | 5        | 0.72%   |
| 5.4.0-31-generic         | 5        | 0.72%   |
| 5.3.0-51-generic         | 5        | 0.72%   |
| 5.3.0-40-generic         | 5        | 0.72%   |
| 5.3.0-28-generic         | 5        | 0.72%   |
| 4.18.16-desktop-1bP      | 5        | 0.72%   |
| 5.8.0-59-generic         | 4        | 0.57%   |
| 5.4.0-58-generic         | 4        | 0.57%   |
| 5.4.0-45-generic         | 4        | 0.57%   |
| 5.3.0-62-generic         | 4        | 0.57%   |
| 5.15.0-27-generic        | 4        | 0.57%   |
| 5.13.13-1070.native      | 4        | 0.57%   |
| 5.13.0-37-generic        | 4        | 0.57%   |
| 5.11.0-43-generic        | 4        | 0.57%   |
| 5.10.0-9-amd64           | 4        | 0.57%   |
| 4.15.0-55-generic        | 4        | 0.57%   |
| 5.8.0-7630-generic       | 3        | 0.43%   |
| 5.8.0-43-generic         | 3        | 0.43%   |
| 5.4.0-81-generic         | 3        | 0.43%   |
| 5.4.0-66-generic         | 3        | 0.43%   |
| 5.4.0-56-generic         | 3        | 0.43%   |
| 5.4.0-54-generic         | 3        | 0.43%   |
| 5.4.0-51-generic         | 3        | 0.43%   |
| 5.4.0-33-generic         | 3        | 0.43%   |
| 5.4.0-29-generic         | 3        | 0.43%   |
| 5.4.0-28-generic         | 3        | 0.43%   |
| 5.3.0-45-generic         | 3        | 0.43%   |
| 5.3.0-18-generic         | 3        | 0.43%   |
| 5.15.0-40-generic        | 3        | 0.43%   |
| 5.15.0-30-generic        | 3        | 0.43%   |
| 5.13.0-7620-generic      | 3        | 0.43%   |
| 5.13.0-27-generic        | 3        | 0.43%   |
| 5.12.4-desktop-1omv4050  | 3        | 0.43%   |
| 5.11.0-34-generic        | 3        | 0.43%   |
| 5.11.0-27-generic        | 3        | 0.43%   |
| 5.11.0-16-generic        | 3        | 0.43%   |
| 5.10.0-8-amd64           | 3        | 0.43%   |
| 5.0.0-25-generic         | 3        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 169      | 26.37%  |
| 4.15.0  | 54       | 8.42%   |
| 5.8.0   | 40       | 6.24%   |
| 5.3.0   | 35       | 5.46%   |
| 5.13.0  | 34       | 5.3%    |
| 5.11.0  | 33       | 5.15%   |
| 5.10.14 | 30       | 4.68%   |
| 5.15.0  | 25       | 3.9%    |
| 4.18.0  | 21       | 3.28%   |
| 5.0.0   | 20       | 3.12%   |
| 5.16.7  | 18       | 2.81%   |
| 5.10.0  | 17       | 2.65%   |
| 4.19.0  | 7        | 1.09%   |
| 4.18.16 | 6        | 0.94%   |
| 4.4.0   | 5        | 0.78%   |
| 5.13.13 | 4        | 0.62%   |
| 5.12.4  | 4        | 0.62%   |
| 5.13.12 | 3        | 0.47%   |
| 5.9.16  | 2        | 0.31%   |
| 5.8.18  | 2        | 0.31%   |
| 5.6.16  | 2        | 0.31%   |
| 5.3.11  | 2        | 0.31%   |
| 5.18.7  | 2        | 0.31%   |
| 5.17.5  | 2        | 0.31%   |
| 5.17.1  | 2        | 0.31%   |
| 5.16.16 | 2        | 0.31%   |
| 5.15.5  | 2        | 0.31%   |
| 5.13.19 | 2        | 0.31%   |
| 5.11.15 | 2        | 0.31%   |
| 5.11.12 | 2        | 0.31%   |
| 5.10.78 | 2        | 0.31%   |
| 4.9.76  | 2        | 0.31%   |
| 4.9.60  | 2        | 0.31%   |
| 5.9.11  | 1        | 0.16%   |
| 5.9.1   | 1        | 0.16%   |
| 5.8.6   | 1        | 0.16%   |
| 5.8.5   | 1        | 0.16%   |
| 5.8.3   | 1        | 0.16%   |
| 5.8.2   | 1        | 0.16%   |
| 5.8.16  | 1        | 0.16%   |
| 5.8.14  | 1        | 0.16%   |
| 5.8.11  | 1        | 0.16%   |
| 5.8.1   | 1        | 0.16%   |
| 5.7.7   | 1        | 0.16%   |
| 5.7.15  | 1        | 0.16%   |
| 5.7.14  | 1        | 0.16%   |
| 5.7.13  | 1        | 0.16%   |
| 5.7.11  | 1        | 0.16%   |
| 5.6.7   | 1        | 0.16%   |
| 5.6.19  | 1        | 0.16%   |
| 5.6.0   | 1        | 0.16%   |
| 5.5.8   | 1        | 0.16%   |
| 5.5.5   | 1        | 0.16%   |
| 5.5.10  | 1        | 0.16%   |
| 5.4.8   | 1        | 0.16%   |
| 5.4.72  | 1        | 0.16%   |
| 5.4.66  | 1        | 0.16%   |
| 5.4.6   | 1        | 0.16%   |
| 5.4.32  | 1        | 0.16%   |
| 5.4.184 | 1        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 176      | 27.72%  |
| 5.10    | 60       | 9.45%   |
| 4.15    | 54       | 8.5%    |
| 5.8     | 50       | 7.87%   |
| 5.13    | 45       | 7.09%   |
| 5.11    | 39       | 6.14%   |
| 5.3     | 37       | 5.83%   |
| 5.15    | 33       | 5.2%    |
| 5.16    | 27       | 4.25%   |
| 4.18    | 27       | 4.25%   |
| 5.0     | 22       | 3.46%   |
| 5.17    | 9        | 1.42%   |
| 4.9     | 8        | 1.26%   |
| 5.18    | 7        | 1.1%    |
| 4.19    | 7        | 1.1%    |
| 5.12    | 6        | 0.94%   |
| 5.7     | 5        | 0.79%   |
| 5.6     | 5        | 0.79%   |
| 4.4     | 5        | 0.79%   |
| 5.9     | 4        | 0.63%   |
| 5.5     | 3        | 0.47%   |
| 4.20    | 2        | 0.31%   |
| 5.2     | 1        | 0.16%   |
| 5.14    | 1        | 0.16%   |
| 5.1     | 1        | 0.16%   |
| 4.1     | 1        | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 562      | 94.45%  |
| i686   | 33       | 5.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 240      | 38.77%  |
| KDE5            | 95       | 15.35%  |
| Unknown         | 79       | 12.76%  |
| XFCE            | 59       | 9.53%   |
| X-Cinnamon      | 40       | 6.46%   |
| MATE            | 32       | 5.17%   |
| KDE             | 23       | 3.72%   |
| KDE4            | 8        | 1.29%   |
| Unity           | 6        | 0.97%   |
| LXQt            | 5        | 0.81%   |
| Cinnamon        | 5        | 0.81%   |
| Pantheon        | 4        | 0.65%   |
| LXDE            | 4        | 0.65%   |
| Deepin          | 4        | 0.65%   |
| Budgie          | 3        | 0.48%   |
| i3              | 2        | 0.32%   |
| xmonad          | 1        | 0.16%   |
| UKUI            | 1        | 0.16%   |
| trinity         | 1        | 0.16%   |
| qtile           | 1        | 0.16%   |
| icewm           | 1        | 0.16%   |
| i3-with-shmlog  | 1        | 0.16%   |
| GNOME Flashback | 1        | 0.16%   |
| DWM             | 1        | 0.16%   |
| Cutefish        | 1        | 0.16%   |
| bspwm           | 1        | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 512      | 84.49%  |
| Wayland | 49       | 8.09%   |
| Unknown | 37       | 6.11%   |
| Tty     | 8        | 1.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 379      | 62.03%  |
| SDDM    | 92       | 15.06%  |
| GDM     | 47       | 7.69%   |
| LightDM | 37       | 6.06%   |
| GDM3    | 26       | 4.26%   |
| TDM     | 17       | 2.78%   |
| KDM     | 8        | 1.31%   |
| SLiM    | 3        | 0.49%   |
| XDM     | 1        | 0.16%   |
| LXDM    | 1        | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang     | Desktops | Percent |
|----------|----------|---------|
| es_AR    | 368      | 60.33%  |
| en_US    | 108      | 17.7%   |
| Unknown  | 77       | 12.62%  |
| es_ES    | 32       | 5.25%   |
| es_MX    | 11       | 1.8%    |
| C        | 7        | 1.15%   |
| en_GB    | 3        | 0.49%   |
| ru_RU    | 1        | 0.16%   |
| es_CL    | 1        | 0.16%   |
| en_UTF-8 | 1        | 0.16%   |
| C.UTF8   | 1        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 433      | 71.1%   |
| EFI  | 176      | 28.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 498      | 82.18%  |
| Overlay | 50       | 8.25%   |
| Btrfs   | 22       | 3.63%   |
| Unknown | 21       | 3.47%   |
| Xfs     | 7        | 1.16%   |
| Zfs     | 2        | 0.33%   |
| Ext3    | 2        | 0.33%   |
| Ext2    | 2        | 0.33%   |
| Tmpfs   | 1        | 0.17%   |
| F2fs    | 1        | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 397      | 66.17%  |
| GPT     | 120      | 20%     |
| MBR     | 83       | 13.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 500      | 82.37%  |
| Yes       | 107      | 17.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 378      | 61.97%  |
| Yes       | 232      | 38.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 172      | 28.91%  |
| Gigabyte Technology | 168      | 28.24%  |
| MSI                 | 79       | 13.28%  |
| ASRock              | 77       | 12.94%  |
| Intel               | 24       | 4.03%   |
| ECS                 | 13       | 2.18%   |
| Dell                | 10       | 1.68%   |
| Biostar             | 10       | 1.68%   |
| Hewlett-Packard     | 8        | 1.34%   |
| Lenovo              | 6        | 1.01%   |
| Unknown             | 6        | 1.01%   |
| Foxconn             | 5        | 0.84%   |
| Quanta              | 3        | 0.5%    |
| PCChips             | 2        | 0.34%   |
| Exo                 | 2        | 0.34%   |
| VS Company          | 1        | 0.17%   |
| Supermicro          | 1        | 0.17%   |
| Sun Microsystems    | 1        | 0.17%   |
| Pegatron            | 1        | 0.17%   |
| NCR                 | 1        | 0.17%   |
| EPoX Computer       | 1        | 0.17%   |
| CX / Air Computers. | 1        | 0.17%   |
| BANGHO              | 1        | 0.17%   |
| American Megatrends | 1        | 0.17%   |
| Advantec            | 1        | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| MSI MS-7721                        | 18       | 3.03%   |
| ASUS All Series                    | 13       | 2.18%   |
| ASUS PRIME A320M-K                 | 11       | 1.85%   |
| Gigabyte F2A68HM-H                 | 9        | 1.51%   |
| Gigabyte H81M-H                    | 8        | 1.34%   |
| ASUS PRIME B450M-A                 | 8        | 1.34%   |
| Gigabyte A320M-S2H                 | 7        | 1.18%   |
| ASUS P5KPL-AM SE                   | 7        | 1.18%   |
| MSI MS-7A15                        | 6        | 1.01%   |
| Gigabyte H61M-S1                   | 6        | 1.01%   |
| Unknown                            | 6        | 1.01%   |
| MSI MS-7C52                        | 5        | 0.84%   |
| Gigabyte A320M-S2H V2              | 5        | 0.84%   |
| MSI MS-7309                        | 4        | 0.67%   |
| Intel DN2820FYB H24582-205         | 4        | 0.67%   |
| Gigabyte M68MT-S2                  | 4        | 0.67%   |
| Gigabyte H110M-H                   | 4        | 0.67%   |
| Gigabyte F2A55M-HD2                | 4        | 0.67%   |
| Gigabyte B365M DS3H                | 4        | 0.67%   |
| ECS H81H3-M4                       | 4        | 0.67%   |
| ASUS ROG STRIX B550-F GAMING       | 4        | 0.67%   |
| ASUS P5GC-MX/1333                  | 4        | 0.67%   |
| ASUS M4N68T-M-LE-V2                | 4        | 0.67%   |
| ASUS H61M-K                        | 4        | 0.67%   |
| ASRock H81M-VG4 R2.0               | 4        | 0.67%   |
| Gigabyte Z97X-Gaming 3             | 3        | 0.5%    |
| Gigabyte H410M H                   | 3        | 0.5%    |
| Gigabyte G31M-ES2C                 | 3        | 0.5%    |
| Gigabyte B75M-D3V                  | 3        | 0.5%    |
| Gigabyte B75M-D3H                  | 3        | 0.5%    |
| Gigabyte B450M DS3H                | 3        | 0.5%    |
| Gigabyte A320M-H                   | 3        | 0.5%    |
| Gigabyte 970A-UD3P                 | 3        | 0.5%    |
| ASUS P5G41T-M LX3                  | 3        | 0.5%    |
| ASUS M5A97 LE R2.0                 | 3        | 0.5%    |
| ASUS M5A78L-M LX                   | 3        | 0.5%    |
| ASUS M4A88TD-V EVO/USB3            | 3        | 0.5%    |
| ASUS M2N68-AM Plus                 | 3        | 0.5%    |
| ASRock N68-VS3 FX                  | 3        | 0.5%    |
| ASRock N68-S                       | 3        | 0.5%    |
| ASRock G41M-VS3                    | 3        | 0.5%    |
| ASRock G31M-S                      | 3        | 0.5%    |
| ASRock FM2A68M-DG3+                | 3        | 0.5%    |
| ASRock A55M-VS                     | 3        | 0.5%    |
| ASRock A320M-HDV R4.0              | 3        | 0.5%    |
| Quanta 120-1026la                  | 2        | 0.34%   |
| MSI MS-7D22                        | 2        | 0.34%   |
| MSI MS-7C96                        | 2        | 0.34%   |
| MSI MS-7C95                        | 2        | 0.34%   |
| MSI MS-7B84                        | 2        | 0.34%   |
| MSI MS-7978                        | 2        | 0.34%   |
| MSI MS-7817                        | 2        | 0.34%   |
| MSI MS-7641                        | 2        | 0.34%   |
| MSI MS-7640                        | 2        | 0.34%   |
| MSI MS-7388                        | 2        | 0.34%   |
| MSI MS-7369                        | 2        | 0.34%   |
| HP Compaq dc5700 Small Form Factor | 2        | 0.34%   |
| Gigabyte Z370 AORUS Gaming 5       | 2        | 0.34%   |
| Gigabyte M68MT-S2P                 | 2        | 0.34%   |
| Gigabyte H61M-S2V-B3               | 2        | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 39       | 6.55%   |
| MSI MS-7721          | 18       | 3.03%   |
| ASUS All             | 13       | 2.18%   |
| Gigabyte A320M-S2H   | 12       | 2.02%   |
| Gigabyte F2A68HM-H   | 9        | 1.51%   |
| ASUS ROG             | 9        | 1.51%   |
| ASUS M5A78L-M        | 9        | 1.51%   |
| Gigabyte H81M-H      | 8        | 1.34%   |
| Gigabyte B450        | 7        | 1.18%   |
| Dell OptiPlex        | 7        | 1.18%   |
| ASUS P5KPL-AM        | 7        | 1.18%   |
| MSI MS-7A15          | 6        | 1.01%   |
| Lenovo ThinkCentre   | 6        | 1.01%   |
| Gigabyte H61M-S1     | 6        | 1.01%   |
| ASUS M5A97           | 6        | 1.01%   |
| Unknown              | 6        | 1.01%   |
| MSI MS-7C52          | 5        | 0.84%   |
| HP Compaq            | 5        | 0.84%   |
| ASUS TUF             | 5        | 0.84%   |
| ASRock N68-VS3       | 5        | 0.84%   |
| ASRock A320M-HDV     | 5        | 0.84%   |
| MSI MS-7309          | 4        | 0.67%   |
| Intel DN2820FYB      | 4        | 0.67%   |
| Gigabyte Z97X-Gaming | 4        | 0.67%   |
| Gigabyte Z370        | 4        | 0.67%   |
| Gigabyte M68MT-S2    | 4        | 0.67%   |
| Gigabyte H410M       | 4        | 0.67%   |
| Gigabyte H110M-H     | 4        | 0.67%   |
| Gigabyte F2A55M-HD2  | 4        | 0.67%   |
| Gigabyte B365M       | 4        | 0.67%   |
| ECS H81H3-M4         | 4        | 0.67%   |
| ASUS P8H61-M         | 4        | 0.67%   |
| ASUS P5GC-MX         | 4        | 0.67%   |
| ASUS M4N68T-M-LE-V2  | 4        | 0.67%   |
| ASUS M2N68-AM        | 4        | 0.67%   |
| ASUS M2N-MX          | 4        | 0.67%   |
| ASUS H61M-K          | 4        | 0.67%   |
| ASRock H81M-VG4      | 4        | 0.67%   |
| Gigabyte H510M       | 3        | 0.5%    |
| Gigabyte G31M-ES2C   | 3        | 0.5%    |
| Gigabyte B75M-D3V    | 3        | 0.5%    |
| Gigabyte B75M-D3H    | 3        | 0.5%    |
| Gigabyte B450M       | 3        | 0.5%    |
| Gigabyte A320M-H     | 3        | 0.5%    |
| Gigabyte 970A-UD3P   | 3        | 0.5%    |
| ASUS P5G41T-M        | 3        | 0.5%    |
| ASUS Maximus         | 3        | 0.5%    |
| ASUS M4A88TD-V       | 3        | 0.5%    |
| ASRock N68-S         | 3        | 0.5%    |
| ASRock G41M-VS3      | 3        | 0.5%    |
| ASRock G31M-S        | 3        | 0.5%    |
| ASRock FM2A68M-DG3+  | 3        | 0.5%    |
| ASRock A55M-VS       | 3        | 0.5%    |
| Quanta 120-1026la    | 2        | 0.34%   |
| MSI MS-7D22          | 2        | 0.34%   |
| MSI MS-7C96          | 2        | 0.34%   |
| MSI MS-7C95          | 2        | 0.34%   |
| MSI MS-7B84          | 2        | 0.34%   |
| MSI MS-7978          | 2        | 0.34%   |
| MSI MS-7817          | 2        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 60       | 10.08%  |
| 2015 | 52       | 8.74%   |
| 2012 | 52       | 8.74%   |
| 2013 | 49       | 8.24%   |
| 2011 | 45       | 7.56%   |
| 2017 | 44       | 7.39%   |
| 2010 | 40       | 6.72%   |
| 2009 | 35       | 5.88%   |
| 2007 | 35       | 5.88%   |
| 2020 | 34       | 5.71%   |
| 2008 | 34       | 5.71%   |
| 2014 | 31       | 5.21%   |
| 2016 | 25       | 4.2%    |
| 2019 | 23       | 3.87%   |
| 2006 | 19       | 3.19%   |
| 2021 | 9        | 1.51%   |
| 2022 | 3        | 0.5%    |
| 2004 | 3        | 0.5%    |
| 2005 | 1        | 0.17%   |
| 2001 | 1        | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 595      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 583      | 97.82%  |
| Enabled  | 13       | 2.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 595      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 132      | 21.93%  |
| 8.01-16.0   | 124      | 20.6%   |
| 4.01-8.0    | 113      | 18.77%  |
| 16.01-24.0  | 105      | 17.44%  |
| 1.01-2.0    | 51       | 8.47%   |
| 32.01-64.0  | 38       | 6.31%   |
| 2.01-3.0    | 16       | 2.66%   |
| 24.01-32.0  | 10       | 1.66%   |
| 0.51-1.0    | 7        | 1.16%   |
| 64.01-256.0 | 5        | 0.83%   |
| 0.01-0.5    | 1        | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 263      | 40.52%  |
| 2.01-3.0   | 131      | 20.18%  |
| 4.01-8.0   | 76       | 11.71%  |
| 3.01-4.0   | 73       | 11.25%  |
| 0.51-1.0   | 67       | 10.32%  |
| 8.01-16.0  | 21       | 3.24%   |
| 0.01-0.5   | 14       | 2.16%   |
| 16.01-24.0 | 4        | 0.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 278      | 45.13%  |
| 2      | 185      | 30.03%  |
| 3      | 96       | 15.58%  |
| 4      | 39       | 6.33%   |
| 5      | 11       | 1.79%   |
| 6      | 3        | 0.49%   |
| 7      | 2        | 0.32%   |
| 0      | 2        | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 355      | 59.17%  |
| Yes       | 245      | 40.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 586      | 98.49%  |
| No        | 9        | 1.51%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 357      | 58.81%  |
| Yes       | 250      | 41.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 517      | 85.74%  |
| Yes       | 86       | 14.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Argentina | 595      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Buenos Aires                | 155      | 24.96%  |
| Córdoba                    | 33       | 5.31%   |
| Rosario                     | 31       | 4.99%   |
| La Plata                    | 16       | 2.58%   |
| Mar del Plata               | 15       | 2.42%   |
| Lomas de Zamora             | 12       | 1.93%   |
| Lanus                       | 9        | 1.45%   |
| Avellaneda                  | 9        | 1.45%   |
| San Miguel de Tucumán      | 8        | 1.29%   |
| Florencio Varela            | 7        | 1.13%   |
| Viedma                      | 6        | 0.97%   |
| Ramos Mejia                 | 6        | 0.97%   |
| Quilmes                     | 6        | 0.97%   |
| Paraná                     | 6        | 0.97%   |
| Neuquén                    | 6        | 0.97%   |
| Ciudad Evita                | 6        | 0.97%   |
| Bahía Blanca               | 6        | 0.97%   |
| Villa Ballester             | 5        | 0.81%   |
| Santa Fe                    | 5        | 0.81%   |
| San Telmo                   | 5        | 0.81%   |
| Martinez                    | 5        | 0.81%   |
| Yerba Buena                 | 4        | 0.64%   |
| Villa Nueva                 | 4        | 0.64%   |
| San Luis                    | 4        | 0.64%   |
| San Juan                    | 4        | 0.64%   |
| Salta                       | 4        | 0.64%   |
| Pilar                       | 4        | 0.64%   |
| Ituzaingo                   | 4        | 0.64%   |
| General San Martin          | 4        | 0.64%   |
| Corrientes                  | 4        | 0.64%   |
| Concordia                   | 4        | 0.64%   |
| Burzaco                     | 4        | 0.64%   |
| Berazategui                 | 4        | 0.64%   |
| Adrogue                     | 4        | 0.64%   |
| Villa María                | 3        | 0.48%   |
| Tigre                       | 3        | 0.48%   |
| Tandil                      | 3        | 0.48%   |
| San Salvador de Jujuy       | 3        | 0.48%   |
| San Nicolás de los Arroyos | 3        | 0.48%   |
| San Justo                   | 3        | 0.48%   |
| Río Cuarto                 | 3        | 0.48%   |
| Olivos                      | 3        | 0.48%   |
| Olavarría                  | 3        | 0.48%   |
| La Rioja                    | 3        | 0.48%   |
| Caseros                     | 3        | 0.48%   |
| Boca de la Zanja            | 3        | 0.48%   |
| Wilde                       | 2        | 0.32%   |
| Villa Elisa                 | 2        | 0.32%   |
| Villa Atuel                 | 2        | 0.32%   |
| Tablada                     | 2        | 0.32%   |
| San Martin                  | 2        | 0.32%   |
| San Jorge                   | 2        | 0.32%   |
| San Isidro                  | 2        | 0.32%   |
| San Andres                  | 2        | 0.32%   |
| Salsipuedes                 | 2        | 0.32%   |
| Saenz Pena                  | 2        | 0.32%   |
| Resistencia                 | 2        | 0.32%   |
| Rafaela                     | 2        | 0.32%   |
| Posadas                     | 2        | 0.32%   |
| Munro                       | 2        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 345      | 565    | 36.28%  |
| Seagate                   | 132      | 173    | 13.88%  |
| Kingston                  | 121      | 163    | 12.72%  |
| Samsung Electronics       | 90       | 133    | 9.46%   |
| Toshiba                   | 52       | 62     | 5.47%   |
| Hitachi                   | 43       | 47     | 4.52%   |
| A-DATA Technology         | 23       | 25     | 2.42%   |
| SanDisk                   | 20       | 22     | 2.1%    |
| Gigabyte Technology       | 20       | 32     | 2.1%    |
| Maxtor                    | 13       | 14     | 1.37%   |
| Crucial                   | 12       | 19     | 1.26%   |
| HGST                      | 9        | 11     | 0.95%   |
| Corsair                   | 9        | 9      | 0.95%   |
| Hewlett-Packard           | 8        | 13     | 0.84%   |
| PNY                       | 6        | 11     | 0.63%   |
| Phison                    | 5        | 6      | 0.53%   |
| XPG                       | 4        | 4      | 0.42%   |
| Realtek Semiconductor     | 4        | 6      | 0.42%   |
| Colorful                  | 4        | 4      | 0.42%   |
| Lexar                     | 3        | 4      | 0.32%   |
| Intel                     | 3        | 4      | 0.32%   |
| Silicon Motion            | 2        | 3      | 0.21%   |
| Patriot                   | 2        | 3      | 0.21%   |
| OCZ                       | 2        | 2      | 0.21%   |
| Fujitsu                   | 2        | 2      | 0.21%   |
| China                     | 2        | 2      | 0.21%   |
| ADATA Technology          | 2        | 3      | 0.21%   |
| Super Talent              | 1        | 1      | 0.11%   |
| Quantum                   | 1        | 1      | 0.11%   |
| Phison Electronics        | 1        | 1      | 0.11%   |
| Netac                     | 1        | 2      | 0.11%   |
| N300                      | 1        | 1      | 0.11%   |
| Micron/Crucial Technology | 1        | 3      | 0.11%   |
| LITEONIT                  | 1        | 1      | 0.11%   |
| KingFast                  | 1        | 1      | 0.11%   |
| KingDian                  | 1        | 1      | 0.11%   |
| Hikvision                 | 1        | 1      | 0.11%   |
| ExcelStor                 | 1        | 1      | 0.11%   |
| Envoy                     | 1        | 1      | 0.11%   |
| ASMT                      | 1        | 2      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 34       | 3.05%   |
| WDC WD10EZEX-08WN4A0 1TB         | 28       | 2.52%   |
| Kingston SA400S37480G 480GB SSD  | 24       | 2.16%   |
| Seagate ST500DM002-1BD142 500GB  | 20       | 1.8%    |
| WDC WD5000AAKX-001CA0 500GB      | 18       | 1.62%   |
| Seagate ST1000DM010-2EP102 1TB   | 18       | 1.62%   |
| Kingston SA400S37120G 120GB SSD  | 16       | 1.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 15       | 1.35%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 15       | 1.35%   |
| WDC WD10EZEX-00BN5A0 1TB         | 15       | 1.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 14       | 1.26%   |
| Kingston SV300S37A120G 120GB SSD | 13       | 1.17%   |
| Toshiba DT01ACA100 1TB           | 12       | 1.08%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 11       | 0.99%   |
| WDC WD1600AABS-00PRA0 160GB      | 10       | 0.9%    |
| Toshiba DT01ACA050 500GB         | 10       | 0.9%    |
| WDC WD1003FZEX-00MK2A0 1TB       | 9        | 0.81%   |
| Samsung HD502HJ 500GB            | 9        | 0.81%   |
| Samsung HD322HJ 320GB            | 9        | 0.81%   |
| WDC WD20EZRX-00D8PB0 2TB         | 8        | 0.72%   |
| WDC WD10EZEX-21WN4A0 1TB         | 8        | 0.72%   |
| Gigabyte GP-GSTFS31240GNTD 240GB | 8        | 0.72%   |
| WDC WD10EZEX-00WN4A0 1TB         | 7        | 0.63%   |
| WDC WD10EARS-00Y5B1 1TB          | 7        | 0.63%   |
| Kingston SUV400S37240G 240GB SSD | 7        | 0.63%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 6        | 0.54%   |
| WDC WD800BD-22MRA1 80GB          | 6        | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB   | 6        | 0.54%   |
| Seagate ST2000DM001-1CH164 2TB   | 6        | 0.54%   |
| Samsung HD322GJ 320GB            | 6        | 0.54%   |
| Samsung HD103SJ 1TB              | 6        | 0.54%   |
| Kingston SUV400S37120G 120GB SSD | 6        | 0.54%   |
| Hitachi HDS721010CLA332 1TB      | 6        | 0.54%   |
| Gigabyte GP-GSTFS31120GNTD 120GB | 6        | 0.54%   |
| WDC WD3200AAJS-00L7A0 320GB      | 5        | 0.45%   |
| WDC WD20PURZ-85GU6Y0 2TB         | 5        | 0.45%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 5        | 0.45%   |
| WDC WD1002FAEX-00Y9A0 1TB        | 5        | 0.45%   |
| Toshiba MQ01ABD032 320GB         | 5        | 0.45%   |
| Seagate ST500LM030-2E717D 500GB  | 5        | 0.45%   |
| Seagate ST3160815AS 160GB        | 5        | 0.45%   |
| SanDisk SDSSDA240G 240GB         | 5        | 0.45%   |
| Samsung SSD 850 EVO 250GB        | 5        | 0.45%   |
| Samsung SSD 840 EVO 250GB        | 5        | 0.45%   |
| Samsung HD161HJ 160GB            | 5        | 0.45%   |
| Kingston SV300S37A240G 240GB SSD | 5        | 0.45%   |
| Kingston SHFS37A240G 240GB SSD   | 5        | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 4        | 0.36%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 4        | 0.36%   |
| WDC WD800JD-75MSA3 80GB          | 4        | 0.36%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 4        | 0.36%   |
| WDC WD3200AAKS-61L9A0 320GB      | 4        | 0.36%   |
| WDC WD3200AAKS-00L9A0 320GB      | 4        | 0.36%   |
| WDC WD1600AABS-00H4A0 160GB      | 4        | 0.36%   |
| WDC WD10EZEX-60ZF5A0 1TB         | 4        | 0.36%   |
| WDC WD10EZEX-08M2NA0 1TB         | 4        | 0.36%   |
| WDC WD10EZEX-00RKKA0 1TB         | 4        | 0.36%   |
| WDC WD10EZEX-00KUWA0 1TB         | 4        | 0.36%   |
| Seagate ST1000DM003-9YN162 1TB   | 4        | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 312      | 485    | 49.29%  |
| Seagate             | 131      | 172    | 20.7%   |
| Samsung Electronics | 71       | 98     | 11.22%  |
| Toshiba             | 52       | 62     | 8.21%   |
| Hitachi             | 43       | 47     | 6.79%   |
| Maxtor              | 10       | 10     | 1.58%   |
| HGST                | 9        | 11     | 1.42%   |
| Fujitsu             | 2        | 2      | 0.32%   |
| Quantum             | 1        | 1      | 0.16%   |
| ExcelStor           | 1        | 1      | 0.16%   |
| ASMT                | 1        | 2      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 115      | 155    | 40.49%  |
| WDC                 | 49       | 61     | 17.25%  |
| A-DATA Technology   | 21       | 22     | 7.39%   |
| Gigabyte Technology | 17       | 29     | 5.99%   |
| Samsung Electronics | 15       | 22     | 5.28%   |
| SanDisk             | 13       | 15     | 4.58%   |
| Crucial             | 12       | 19     | 4.23%   |
| Corsair             | 7        | 7      | 2.46%   |
| PNY                 | 6        | 11     | 2.11%   |
| Hewlett-Packard     | 5        | 6      | 1.76%   |
| Colorful            | 4        | 4      | 1.41%   |
| Maxtor              | 3        | 4      | 1.06%   |
| Lexar               | 3        | 4      | 1.06%   |
| Patriot             | 2        | 3      | 0.7%    |
| OCZ                 | 2        | 2      | 0.7%    |
| Intel               | 2        | 3      | 0.7%    |
| China               | 2        | 2      | 0.7%    |
| Super Talent        | 1        | 1      | 0.35%   |
| Seagate             | 1        | 1      | 0.35%   |
| Netac               | 1        | 2      | 0.35%   |
| LITEONIT            | 1        | 1      | 0.35%   |
| KingDian            | 1        | 1      | 0.35%   |
| Hikvision           | 1        | 1      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 503      | 891    | 61.04%  |
| SSD     | 261      | 376    | 31.67%  |
| NVMe    | 57       | 89     | 6.92%   |
| Unknown | 3        | 3      | 0.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 581      | 1258   | 89.52%  |
| NVMe | 57       | 89     | 8.78%   |
| SAS  | 11       | 12     | 1.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 478      | 812    | 60.58%  |
| 0.51-1.0   | 220      | 328    | 27.88%  |
| 1.01-2.0   | 61       | 86     | 7.73%   |
| 2.01-3.0   | 11       | 12     | 1.39%   |
| 3.01-4.0   | 10       | 17     | 1.27%   |
| 4.01-10.0  | 9        | 12     | 1.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 165      | 25.74%  |
| 251-500        | 138      | 21.53%  |
| 501-1000       | 92       | 14.35%  |
| 1001-2000      | 70       | 10.92%  |
| 51-100         | 49       | 7.64%   |
| 1-20           | 33       | 5.15%   |
| 21-50          | 31       | 4.84%   |
| 2001-3000      | 30       | 4.68%   |
| More than 3000 | 19       | 2.96%   |
| Unknown        | 14       | 2.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 267      | 40.76%  |
| 21-50          | 83       | 12.67%  |
| 101-250        | 77       | 11.76%  |
| 251-500        | 63       | 9.62%   |
| 51-100         | 63       | 9.62%   |
| 501-1000       | 48       | 7.33%   |
| 1001-2000      | 28       | 4.27%   |
| Unknown        | 14       | 2.14%   |
| More than 3000 | 7        | 1.07%   |
| 2001-3000      | 5        | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB       | 7        | 9      | 7.14%   |
| WDC WD10EZEX-08WN4A0 1TB          | 3        | 3      | 3.06%   |
| WDC WD10EZEX-00BN5A0 1TB          | 3        | 3      | 3.06%   |
| Seagate ST500DM002-1BD142 500GB   | 3        | 3      | 3.06%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 2        | 2      | 2.04%   |
| WDC WD10EARS-00Y5B1 1TB           | 2        | 2      | 2.04%   |
| WDC WD1002FAEX-00Y9A0 1TB         | 2        | 2      | 2.04%   |
| Seagate ST1500DL003-9VT16L 1TB    | 2        | 2      | 2.04%   |
| Samsung Electronics SP0411N 40GB  | 2        | 3      | 2.04%   |
| Samsung Electronics HD322HJ 320GB | 2        | 2      | 2.04%   |
| WDC WDS480G2G0A-00JH30 480GB SSD  | 1        | 2      | 1.02%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1      | 1.02%   |
| WDC WD800JD-00MSA1 80GB           | 1        | 1      | 1.02%   |
| WDC WD800BD-22MRA1 80GB           | 1        | 1      | 1.02%   |
| WDC WD800BB-75JHC0 80GB           | 1        | 1      | 1.02%   |
| WDC WD800BB-00JHC0 80GB           | 1        | 1      | 1.02%   |
| WDC WD6400AAKS-65Z7B0 640GB       | 1        | 1      | 1.02%   |
| WDC WD5000AAVS-00G9B1 500GB       | 1        | 1      | 1.02%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1        | 1      | 1.02%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 1      | 1.02%   |
| WDC WD400BB-23DEA0 40GB           | 1        | 1      | 1.02%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 1.02%   |
| WDC WD3200AAJS-65M0A0 320GB       | 1        | 1      | 1.02%   |
| WDC WD3200AAJS-56B4A0 320GB       | 1        | 2      | 1.02%   |
| WDC WD3200AAJS-00YZCA0 320GB      | 1        | 1      | 1.02%   |
| WDC WD30EZRX-00SPEB0 3TB          | 1        | 1      | 1.02%   |
| WDC WD2500AAJS-00B4A0 250GB       | 1        | 1      | 1.02%   |
| WDC WD20PURZ-85GU6Y0 2TB          | 1        | 2      | 1.02%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 1        | 1      | 1.02%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1        | 1      | 1.02%   |
| WDC WD20EARX-00ZUDB0 2TB          | 1        | 1      | 1.02%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 1.02%   |
| WDC WD1600BEVT-60ZCT1 160GB       | 1        | 1      | 1.02%   |
| WDC WD1600AAJS-00L7A0 160GB       | 1        | 1      | 1.02%   |
| WDC WD15EARS-00S0XB0 1TB          | 1        | 1      | 1.02%   |
| WDC WD10JPVX-60JC3T0 1TB          | 1        | 1      | 1.02%   |
| WDC WD10EZEX-60WN4A1 1TB          | 1        | 1      | 1.02%   |
| WDC WD10EZEX-60M2NA0 1TB          | 1        | 1      | 1.02%   |
| WDC WD10EZEX-07ZF5A0 1TB          | 1        | 1      | 1.02%   |
| WDC WD10EZEX-00RKKA0 1TB          | 1        | 1      | 1.02%   |
| WDC WD10EARX-00N0YB0 1TB          | 1        | 1      | 1.02%   |
| WDC WD10EARS-00MVWB0 1TB          | 1        | 1      | 1.02%   |
| WDC WD10EADS-00L5B1 1TB           | 1        | 1      | 1.02%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1      | 1.02%   |
| WDC WD1003FZEX-00K3CA0 1TB        | 1        | 1      | 1.02%   |
| WDC WD1002FAEX-00Z3A0 1TB         | 1        | 1      | 1.02%   |
| Toshiba MK6461GSY 640GB           | 1        | 1      | 1.02%   |
| Toshiba MK1665GSX 160GB           | 1        | 1      | 1.02%   |
| Toshiba MK1059GSM 1TB             | 1        | 1      | 1.02%   |
| Toshiba DT01ACA050 500GB          | 1        | 1      | 1.02%   |
| Seagate ST9250315AS 250GB         | 1        | 1      | 1.02%   |
| Seagate ST500LM030-2E717D 500GB   | 1        | 1      | 1.02%   |
| Seagate ST3500630AS 500GB         | 1        | 1      | 1.02%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 1.02%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 1.02%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 1.02%   |
| Seagate ST1000VM002-1CT162 1TB    | 1        | 1      | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB    | 1        | 1      | 1.02%   |
| Seagate ST1000DM003-9YN162 1TB    | 1        | 1      | 1.02%   |
| Seagate ST1000DM003-1SB10C 1TB    | 1        | 1      | 1.02%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 47       | 60     | 52.81%  |
| Seagate             | 17       | 18     | 19.1%   |
| Samsung Electronics | 10       | 12     | 11.24%  |
| Toshiba             | 4        | 4      | 4.49%   |
| Hitachi             | 3        | 3      | 3.37%   |
| Maxtor              | 2        | 2      | 2.25%   |
| Kingston            | 2        | 2      | 2.25%   |
| HGST                | 2        | 2      | 2.25%   |
| Quantum             | 1        | 1      | 1.12%   |
| A-DATA Technology   | 1        | 1      | 1.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 45       | 57     | 53.57%  |
| Seagate             | 17       | 18     | 20.24%  |
| Samsung Electronics | 10       | 12     | 11.9%   |
| Toshiba             | 4        | 4      | 4.76%   |
| Hitachi             | 3        | 3      | 3.57%   |
| Maxtor              | 2        | 2      | 2.38%   |
| HGST                | 2        | 2      | 2.38%   |
| Quantum             | 1        | 1      | 1.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 76       | 99     | 93.83%  |
| SSD  | 5        | 6      | 6.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD1600BEVT-80A23T0 160GB      | 1        | 1      | 33.33%  |
| Samsung Electronics HD502HJ 500GB | 1        | 1      | 33.33%  |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 66.67%  |
| WDC                 | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 401      | 918    | 61.88%  |
| Works    | 165      | 333    | 25.46%  |
| Malfunc  | 79       | 105    | 12.19%  |
| Failed   | 3        | 3      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 288      | 41.14%  |
| AMD                              | 230      | 32.86%  |
| Nvidia                           | 61       | 8.71%   |
| VIA Technologies                 | 22       | 3.14%   |
| SanDisk                          | 20       | 2.86%   |
| JMicron Technology               | 12       | 1.71%   |
| Phison Electronics               | 10       | 1.43%   |
| ASMedia Technology               | 10       | 1.43%   |
| Samsung Electronics              | 8        | 1.14%   |
| Realtek Semiconductor            | 8        | 1.14%   |
| Kingston Technology Company      | 8        | 1.14%   |
| Marvell Technology Group         | 6        | 0.86%   |
| Silicon Motion                   | 5        | 0.71%   |
| ADATA Technology                 | 4        | 0.57%   |
| Silicon Integrated Systems [SiS] | 3        | 0.43%   |
| Silicon Image                    | 1        | 0.14%   |
| Promise Technology               | 1        | 0.14%   |
| Micron/Crucial Technology        | 1        | 0.14%   |
| Broadcom / LSI                   | 1        | 0.14%   |
| Adaptec                          | 1        | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 130      | 12.88%  |
| Nvidia MCP61 SATA Controller                                                            | 53       | 5.25%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 48       | 4.76%   |
| Nvidia MCP61 IDE                                                                        | 47       | 4.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 42       | 4.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 40       | 3.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 39       | 3.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 39       | 3.87%   |
| AMD FCH SATA Controller D                                                               | 38       | 3.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 34       | 3.37%   |
| AMD 400 Series Chipset SATA Controller                                                  | 27       | 2.68%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 26       | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 21       | 2.08%   |
| AMD FCH IDE Controller                                                                  | 21       | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 20       | 1.98%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 20       | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 17       | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 17       | 1.68%   |
| AMD 500 Series Chipset SATA Controller                                                  | 15       | 1.49%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 13       | 1.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 1.29%   |
| AMD 300 Series Chipset SATA Controller                                                  | 12       | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 0.99%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9        | 0.89%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 9        | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 9        | 0.89%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 6        | 0.59%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 6        | 0.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 0.59%   |
| Phison E12 NVMe Controller                                                              | 6        | 0.59%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 6        | 0.59%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 6        | 0.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6        | 0.59%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 6        | 0.59%   |
| AMD SB600 IDE                                                                           | 6        | 0.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 5        | 0.5%    |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 5        | 0.5%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 0.5%    |
| Intel SATA Controller [RAID mode]                                                       | 5        | 0.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 0.5%    |
| AMD X370 Series Chipset SATA Controller                                                 | 5        | 0.5%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4        | 0.4%    |
| Phison PS5013 E13 NVMe Controller                                                       | 4        | 0.4%    |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 4        | 0.4%    |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 0.4%    |
| JMicron JMB362 SATA Controller                                                          | 4        | 0.4%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 0.4%    |
| VIA VT6421 IDE/SATA Controller                                                          | 3        | 0.3%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 3        | 0.3%    |
| SanDisk Non-Volatile memory controller                                                  | 3        | 0.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 0.3%    |
| Realtek Realtek Non-Volatile memory controller                                          | 3        | 0.3%    |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 3        | 0.3%    |
| JMicron JMB368 IDE controller                                                           | 3        | 0.3%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3        | 0.3%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 3        | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 420      | 56.68%  |
| IDE  | 249      | 33.6%   |
| NVMe | 58       | 7.83%   |
| RAID | 13       | 1.75%   |
| SCSI | 1        | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 299      | 50.25%  |
| AMD    | 296      | 49.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 11       | 1.85%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 9        | 1.51%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 9        | 1.51%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 8        | 1.34%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 8        | 1.34%   |
| AMD Athlon II X2 250 Processor                  | 8        | 1.34%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G   | 8        | 1.34%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz          | 7        | 1.18%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 7        | 1.18%   |
| AMD FX-6300 Six-Core Processor                  | 7        | 1.18%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 6        | 1.01%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 6        | 1.01%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 6        | 1.01%   |
| Intel Core i3-4170 CPU @ 3.70GHz                | 6        | 1.01%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 6        | 1.01%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 6        | 1.01%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 6        | 1.01%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 6        | 1.01%   |
| AMD Ryzen 5 3600 6-Core Processor               | 6        | 1.01%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 6        | 1.01%   |
| AMD A4-4000 APU with Radeon HD Graphics         | 6        | 1.01%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 5        | 0.84%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 5        | 0.84%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 5        | 0.84%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 5        | 0.84%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 5        | 0.84%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G    | 5        | 0.84%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 4        | 0.67%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 4        | 0.67%   |
| Intel Pentium 4 CPU 3.00GHz                     | 4        | 0.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 4        | 0.67%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 4        | 0.67%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 4        | 0.67%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 4        | 0.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 4        | 0.67%   |
| Intel Core i5-2310 CPU @ 2.90GHz                | 4        | 0.67%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 4        | 0.67%   |
| Intel Core i3-7100 CPU @ 3.90GHz                | 4        | 0.67%   |
| Intel Celeron CPU N2830 @ 2.16GHz               | 4        | 0.67%   |
| AMD Sempron 145 Processor                       | 4        | 0.67%   |
| AMD Sempron 140 Processor                       | 4        | 0.67%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 4        | 0.67%   |
| AMD Phenom II X6 1090T Processor                | 4        | 0.67%   |
| AMD FX-4100 Quad-Core Processor                 | 4        | 0.67%   |
| AMD Athlon II X4 620 Processor                  | 4        | 0.67%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+      | 4        | 0.67%   |
| AMD Athlon 64 X2 Dual Core Processor 4000+      | 4        | 0.67%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G   | 4        | 0.67%   |
| AMD A4-6300 APU with Radeon HD Graphics         | 4        | 0.67%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 4        | 0.67%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz     | 3        | 0.5%    |
| Intel Pentium D CPU 3.00GHz                     | 3        | 0.5%    |
| Intel Pentium D CPU 2.66GHz                     | 3        | 0.5%    |
| Intel Pentium CPU G4560 @ 3.50GHz               | 3        | 0.5%    |
| Intel Core i5-6600K CPU @ 3.50GHz               | 3        | 0.5%    |
| Intel Core i5-6500 CPU @ 3.20GHz                | 3        | 0.5%    |
| Intel Core i5-2500 CPU @ 3.30GHz                | 3        | 0.5%    |
| Intel Core i3-6100 CPU @ 3.70GHz                | 3        | 0.5%    |
| Intel Core i3-4160 CPU @ 3.60GHz                | 3        | 0.5%    |
| Intel Core i3-3240 CPU @ 3.40GHz                | 3        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 92       | 15.46%  |
| Intel Core i7           | 50       | 8.4%    |
| AMD Ryzen 5             | 46       | 7.73%   |
| Intel Core i3           | 44       | 7.39%   |
| AMD FX                  | 27       | 4.54%   |
| AMD A8                  | 26       | 4.37%   |
| Intel Celeron           | 21       | 3.53%   |
| AMD Athlon 64 X2        | 20       | 3.36%   |
| AMD Ryzen 7             | 19       | 3.19%   |
| AMD Athlon II X2        | 19       | 3.19%   |
| AMD Ryzen 3             | 18       | 3.03%   |
| Intel Pentium Dual-Core | 17       | 2.86%   |
| AMD Sempron             | 16       | 2.69%   |
| Intel Core 2 Duo        | 15       | 2.52%   |
| AMD A6                  | 15       | 2.52%   |
| AMD A4                  | 15       | 2.52%   |
| Intel Pentium           | 12       | 2.02%   |
| AMD Phenom II X4        | 11       | 1.85%   |
| AMD A10                 | 11       | 1.85%   |
| Intel Pentium Dual      | 10       | 1.68%   |
| Intel Pentium D         | 9        | 1.51%   |
| AMD Athlon              | 9        | 1.51%   |
| Intel Pentium 4         | 8        | 1.34%   |
| AMD Phenom II X6        | 8        | 1.34%   |
| AMD Athlon II X4        | 7        | 1.18%   |
| Other                   | 6        | 1.01%   |
| Intel Core 2            | 5        | 0.84%   |
| AMD Athlon II X3        | 5        | 0.84%   |
| Intel Core 2 Quad       | 4        | 0.67%   |
| AMD Ryzen 9             | 4        | 0.67%   |
| AMD Phenom              | 4        | 0.67%   |
| Intel Pentium Gold      | 3        | 0.5%    |
| AMD E1                  | 3        | 0.5%    |
| Intel Xeon              | 2        | 0.34%   |
| Intel Core i9           | 2        | 0.34%   |
| Intel Atom              | 2        | 0.34%   |
| AMD Phenom II X2        | 2        | 0.34%   |
| AMD Athlon X2           | 2        | 0.34%   |
| AMD Ryzen 5 PRO         | 1        | 0.17%   |
| AMD Ryzen 3 PRO         | 1        | 0.17%   |
| AMD E2                  | 1        | 0.17%   |
| AMD Athlon XP           | 1        | 0.17%   |
| AMD Athlon Dual Core    | 1        | 0.17%   |
| AMD Athlon 64           | 1        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 228      | 38.32%  |
| 4       | 192      | 32.27%  |
| 6       | 69       | 11.6%   |
| 1       | 57       | 9.58%   |
| 8       | 28       | 4.71%   |
| 3       | 15       | 2.52%   |
| 12      | 3        | 0.5%    |
| 16      | 1        | 0.17%   |
| 10      | 1        | 0.17%   |
| Unknown | 1        | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 594      | 99.83%  |
| 2      | 1        | 0.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 318      | 53.36%  |
| 2       | 277      | 46.48%  |
| Unknown | 1        | 0.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 577      | 96.65%  |
| Unknown        | 13       | 2.18%   |
| 32-bit         | 4        | 0.67%   |
| 64-bit         | 3        | 0.5%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 131      | 21.1%   |
| 0x306c3    | 42       | 6.76%   |
| 0x306a9    | 27       | 4.35%   |
| 0x1067a    | 27       | 4.35%   |
| 0x010000c8 | 26       | 4.19%   |
| 0x906e9    | 23       | 3.7%    |
| 0x206a7    | 23       | 3.7%    |
| 0x08108109 | 19       | 3.06%   |
| 0x906ea    | 18       | 2.9%    |
| 0x506e3    | 18       | 2.9%    |
| 0x06001119 | 16       | 2.58%   |
| 0x06003106 | 15       | 2.42%   |
| 0x0800820d | 13       | 2.09%   |
| 0x06000852 | 13       | 2.09%   |
| 0x6fd      | 12       | 1.93%   |
| 0x08701021 | 12       | 1.93%   |
| 0x0600611a | 11       | 1.77%   |
| 0x08101016 | 9        | 1.45%   |
| 0x0600063e | 9        | 1.45%   |
| 0x010000c7 | 8        | 1.29%   |
| 0xa0655    | 6        | 0.97%   |
| 0xa0653    | 6        | 0.97%   |
| 0x10676    | 6        | 0.97%   |
| 0x06006118 | 6        | 0.97%   |
| 0x010000dc | 6        | 0.97%   |
| 0x010000db | 6        | 0.97%   |
| 0x01000083 | 6        | 0.97%   |
| 0xf65      | 5        | 0.81%   |
| 0x0a50000c | 5        | 0.81%   |
| 0x0700010f | 5        | 0.81%   |
| 0xf47      | 4        | 0.64%   |
| 0x6f2      | 4        | 0.64%   |
| 0xf43      | 3        | 0.48%   |
| 0x906ed    | 3        | 0.48%   |
| 0x406c3    | 3        | 0.48%   |
| 0x30678    | 3        | 0.48%   |
| 0x0a201016 | 3        | 0.48%   |
| 0x0a201009 | 3        | 0.48%   |
| 0x08701013 | 3        | 0.48%   |
| 0x0810100b | 3        | 0.48%   |
| 0x03000027 | 3        | 0.48%   |
| 0x010000bf | 3        | 0.48%   |
| 0xf49      | 2        | 0.32%   |
| 0xf27      | 2        | 0.32%   |
| 0xa0671    | 2        | 0.32%   |
| 0x906ec    | 2        | 0.32%   |
| 0x906eb    | 2        | 0.32%   |
| 0x20655    | 2        | 0.32%   |
| 0x20652    | 2        | 0.32%   |
| 0x10661    | 2        | 0.32%   |
| 0x08001138 | 2        | 0.32%   |
| 0x07030106 | 2        | 0.32%   |
| 0x0700010b | 2        | 0.32%   |
| 0x0600081c | 2        | 0.32%   |
| 0x010000b6 | 2        | 0.32%   |
| 0xf62      | 1        | 0.16%   |
| 0xf41      | 1        | 0.16%   |
| 0x90675    | 1        | 0.16%   |
| 0x6fb      | 1        | 0.16%   |
| 0x6f6      | 1        | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| K10              | 70       | 11.76%  |
| KabyLake         | 61       | 10.25%  |
| Haswell          | 50       | 8.4%    |
| Zen+             | 39       | 6.55%   |
| Penryn           | 38       | 6.39%   |
| Piledriver       | 37       | 6.22%   |
| IvyBridge        | 31       | 5.21%   |
| K8 Hammer        | 28       | 4.71%   |
| SandyBridge      | 26       | 4.37%   |
| Steamroller      | 20       | 3.36%   |
| Core             | 20       | 3.36%   |
| Zen 2            | 19       | 3.19%   |
| Zen              | 19       | 3.19%   |
| Skylake          | 19       | 3.19%   |
| NetBurst         | 19       | 3.19%   |
| Excavator        | 19       | 3.19%   |
| Zen 3            | 16       | 2.69%   |
| CometLake        | 15       | 2.52%   |
| Bulldozer        | 10       | 1.68%   |
| Silvermont       | 8        | 1.34%   |
| K10 Llano        | 7        | 1.18%   |
| Jaguar           | 7        | 1.18%   |
| Westmere         | 5        | 0.84%   |
| Puma             | 3        | 0.5%    |
| Nehalem          | 2        | 0.34%   |
| K6               | 2        | 0.34%   |
| Bonnell          | 2        | 0.34%   |
| Icelake          | 1        | 0.17%   |
| Alderlake Hybrid | 1        | 0.17%   |
| Unknown          | 1        | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| AMD                              | 243      | 38.63%  |
| Intel                            | 188      | 29.89%  |
| Nvidia                           | 186      | 29.57%  |
| VIA Technologies                 | 9        | 1.43%   |
| ATI Technologies                 | 2        | 0.32%   |
| Silicon Integrated Systems [SiS] | 1        | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 26       | 4.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21       | 3.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20       | 3.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17       | 2.64%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 16       | 2.48%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 16       | 2.48%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 16       | 2.48%   |
| Nvidia GT218 [GeForce 210]                                                               | 15       | 2.33%   |
| Intel HD Graphics 630                                                                    | 15       | 2.33%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 15       | 2.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 14       | 2.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 14       | 2.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 13       | 2.02%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 13       | 2.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 12       | 1.86%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 12       | 1.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12       | 1.86%   |
| Intel HD Graphics 530                                                                    | 11       | 1.71%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 11       | 1.71%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10       | 1.55%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 9        | 1.4%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 8        | 1.24%   |
| AMD RS780L [Radeon 3000]                                                                 | 8        | 1.24%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 8        | 1.24%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 8        | 1.24%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 7        | 1.09%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6        | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 6        | 0.93%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 6        | 0.93%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 6        | 0.93%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 6        | 0.93%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 5        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 0.78%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 5        | 0.78%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5        | 0.78%   |
| AMD Cezanne                                                                              | 5        | 0.78%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 0.78%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro]            | 4        | 0.62%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4        | 0.62%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 4        | 0.62%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 4        | 0.62%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4        | 0.62%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 4        | 0.62%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                              | 4        | 0.62%   |
| AMD Richland [Radeon HD 8370D]                                                           | 4        | 0.62%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 4        | 0.62%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 4        | 0.62%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 4        | 0.62%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                                     | 4        | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 3        | 0.47%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 3        | 0.47%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 0.47%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 3        | 0.47%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 3        | 0.47%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 3        | 0.47%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                                     | 3        | 0.47%   |
| Intel HD Graphics 610                                                                    | 3        | 0.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3        | 0.47%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 3        | 0.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 227      | 37.9%   |
| 1 x Nvidia     | 165      | 27.55%  |
| 1 x Intel      | 164      | 27.38%  |
| Intel + Nvidia | 11       | 1.84%   |
| 1 x VIA        | 9        | 1.5%    |
| 2 x AMD        | 8        | 1.34%   |
| Intel + AMD    | 7        | 1.17%   |
| AMD + Nvidia   | 5        | 0.83%   |
| 2 x Nvidia     | 2        | 0.33%   |
| 1 x SiS        | 1        | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 474      | 78.74%  |
| Proprietary | 83       | 13.79%  |
| Unknown     | 45       | 7.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 236      | 38.31%  |
| 0.01-0.5   | 111      | 18.02%  |
| 0.51-1.0   | 88       | 14.29%  |
| 1.01-2.0   | 86       | 13.96%  |
| 3.01-4.0   | 50       | 8.12%   |
| 7.01-8.0   | 26       | 4.22%   |
| 5.01-6.0   | 10       | 1.62%   |
| 2.01-3.0   | 5        | 0.81%   |
| 8.01-16.0  | 4        | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 220      | 37.48%  |
| Goldstar             | 138      | 23.51%  |
| Dell                 | 24       | 4.09%   |
| ViewSonic            | 20       | 3.41%   |
| LG Electronics       | 18       | 3.07%   |
| Hitachi              | 15       | 2.56%   |
| Philips              | 13       | 2.21%   |
| BenQ                 | 13       | 2.21%   |
| SKY                  | 10       | 1.7%    |
| Hewlett-Packard      | 10       | 1.7%    |
| SAC                  | 9        | 1.53%   |
| AOC                  | 8        | 1.36%   |
| Unknown              | 7        | 1.19%   |
| Sony                 | 7        | 1.19%   |
| Lenovo               | 5        | 0.85%   |
| CDR                  | 4        | 0.68%   |
| ASUSTek Computer     | 4        | 0.68%   |
| UTV                  | 3        | 0.51%   |
| Unknown (XXX)        | 3        | 0.51%   |
| RTK                  | 3        | 0.51%   |
| MStar                | 3        | 0.51%   |
| HKC                  | 3        | 0.51%   |
| Ancor Communications | 3        | 0.51%   |
| Acer                 | 3        | 0.51%   |
| STD                  | 2        | 0.34%   |
| SANYO                | 2        | 0.34%   |
| Panasonic            | 2        | 0.34%   |
| LLL                  | 2        | 0.34%   |
| KTC                  | 2        | 0.34%   |
| Konka                | 2        | 0.34%   |
| JRY                  | 2        | 0.34%   |
| ITE                  | 2        | 0.34%   |
| HIB                  | 2        | 0.34%   |
| GDH                  | 2        | 0.34%   |
| Daewoo               | 2        | 0.34%   |
| AGO                  | 2        | 0.34%   |
| ___                  | 1        | 0.17%   |
| Yuraku               | 1        | 0.17%   |
| Targa                | 1        | 0.17%   |
| SKK                  | 1        | 0.17%   |
| OOO                  | 1        | 0.17%   |
| MLT                  | 1        | 0.17%   |
| LG Display           | 1        | 0.17%   |
| KLX                  | 1        | 0.17%   |
| Hisense              | 1        | 0.17%   |
| HIC                  | 1        | 0.17%   |
| HannStar             | 1        | 0.17%   |
| Envision             | 1        | 0.17%   |
| Elo Touch            | 1        | 0.17%   |
| DTV                  | 1        | 0.17%   |
| Compaq Computer      | 1        | 0.17%   |
| Belinea              | 1        | 0.17%   |
| AOpen                | 1        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 14       | 2.28%   |
| Hitachi HDMI HEC0088 1920x540                                        | 10       | 1.63%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                 | 10       | 1.63%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 10       | 1.63%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 9        | 1.47%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 8        | 1.3%    |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 7        | 1.14%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 7        | 1.14%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 7        | 1.14%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 6        | 0.98%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 6        | 0.98%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 6        | 0.98%   |
| SKY TV-monitor SKY0001 1360x768 890x500mm 40.2-inch                  | 5        | 0.81%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch    | 5        | 0.81%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 5        | 0.81%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 5        | 0.81%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 5        | 0.81%   |
| Goldstar W2353 GSM56EE 1920x1080 474x296mm 22.0-inch                 | 5        | 0.81%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                | 5        | 0.81%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                | 5        | 0.81%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch  | 4        | 0.65%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch | 4        | 0.65%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                | 4        | 0.65%   |
| Goldstar T730SH GSM43CB 1280x960 310x230mm 15.2-inch                 | 4        | 0.65%   |
| Goldstar E2340 GSM57C7 1920x1080 510x290mm 23.1-inch                 | 4        | 0.65%   |
| ViewSonic VA2216w SERIE VSC2920 1680x1050 465x291mm 21.6-inch        | 3        | 0.49%   |
| UTV MONITOR UTV0030 1920x1080 580x330mm 26.3-inch                    | 3        | 0.49%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 3        | 0.49%   |
| Samsung Electronics SyncMaster SAM05FB 1920x1080 510x287mm 23.0-inch | 3        | 0.49%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch | 3        | 0.49%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 459x296mm 21.5-inch | 3        | 0.49%   |
| Samsung Electronics SyncMaster SAM0326 1440x900 428x255mm 19.6-inch  | 3        | 0.49%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch  | 3        | 0.49%   |
| Samsung Electronics SyncMaster SAM01AB 1280x1024 312x234mm 15.4-inch | 3        | 0.49%   |
| Samsung Electronics S23B350 SAM08D6 1920x1080 510x287mm 23.0-inch    | 3        | 0.49%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch    | 3        | 0.49%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 3        | 0.49%   |
| SAC LED MONITOR SAC3220 1360x768 477x268mm 21.5-inch                 | 3        | 0.49%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                       | 3        | 0.49%   |
| Hitachi HISENSE HEC0030 3840x2160 1210x680mm 54.6-inch               | 3        | 0.49%   |
| Hewlett-Packard Omni / Pro HWP4219 1600x900 440x250mm 19.9-inch      | 3        | 0.49%   |
| Goldstar W2243 GSM56FF 1920x1080 480x270mm 21.7-inch                 | 3        | 0.49%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                  | 3        | 0.49%   |
| Goldstar W1941 GSM4B91 1360x768 406x229mm 18.4-inch                  | 3        | 0.49%   |
| Goldstar L1753S GSM446F 1280x1024 338x270mm 17.0-inch                | 3        | 0.49%   |
| Goldstar E2342 GSM58C3 1920x1080 510x290mm 23.1-inch                 | 3        | 0.49%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 3        | 0.49%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 3        | 0.49%   |
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                     | 3        | 0.49%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 3        | 0.49%   |
| ViewSonic VG2021wm-2 VSCD91E 1680x1050 433x270mm 20.1-inch           | 2        | 0.33%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 2        | 0.33%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                        | 2        | 0.33%   |
| Sony TV SNY7402 1920x1080 1018x573mm 46.0-inch                       | 2        | 0.33%   |
| SKY TV-monitor SKY0102 1920x1080 885x498mm 40.0-inch                 | 2        | 0.33%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch               | 2        | 0.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 2        | 0.33%   |
| Samsung Electronics T24C550 SAM0AA1 1920x1080 521x293mm 23.5-inch    | 2        | 0.33%   |
| Samsung Electronics T22B350 SAM0934 1920x1080 477x268mm 21.5-inch    | 2        | 0.33%   |
| Samsung Electronics SyncMaster SAM060D 1920x1080 531x299mm 24.0-inch | 2        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 257      | 45.33%  |
| 1366x768 (WXGA)    | 62       | 10.93%  |
| 1280x1024 (SXGA)   | 40       | 7.05%   |
| 3840x2160 (4K)     | 35       | 6.17%   |
| 1360x768           | 35       | 6.17%   |
| 1680x1050 (WSXGA+) | 34       | 6%      |
| 1440x900 (WXGA+)   | 25       | 4.41%   |
| 1600x900 (HD+)     | 22       | 3.88%   |
| 1920x540           | 13       | 2.29%   |
| Unknown            | 7        | 1.23%   |
| 1280x720 (HD)      | 5        | 0.88%   |
| 1024x768 (XGA)     | 5        | 0.88%   |
| 2560x1440 (QHD)    | 4        | 0.71%   |
| 1152x864           | 4        | 0.71%   |
| 1920x1200 (WUXGA)  | 3        | 0.53%   |
| 2560x1080          | 2        | 0.35%   |
| 2048x1152          | 2        | 0.35%   |
| 1280x960           | 2        | 0.35%   |
| 3840x1080          | 1        | 0.18%   |
| 3440x1440          | 1        | 0.18%   |
| 3286x1080          | 1        | 0.18%   |
| 3280x1080          | 1        | 0.18%   |
| 3046x1050          | 1        | 0.18%   |
| 2646x1024          | 1        | 0.18%   |
| 2288x1287          | 1        | 0.18%   |
| 2048x1536          | 1        | 0.18%   |
| 1792x1344          | 1        | 0.18%   |
| 1600x1200          | 1        | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 101      | 16.97%  |
| 21      | 101      | 16.97%  |
| 18      | 76       | 12.77%  |
| Unknown | 48       | 8.07%   |
| 19      | 29       | 4.87%   |
| 20      | 27       | 4.54%   |
| 24      | 26       | 4.37%   |
| 17      | 24       | 4.03%   |
| 15      | 23       | 3.87%   |
| 27      | 19       | 3.19%   |
| 22      | 17       | 2.86%   |
| 40      | 14       | 2.35%   |
| 84      | 12       | 2.02%   |
| 48      | 12       | 2.02%   |
| 31      | 11       | 1.85%   |
| 16      | 9        | 1.51%   |
| 52      | 8        | 1.34%   |
| 46      | 7        | 1.18%   |
| 54      | 5        | 0.84%   |
| 32      | 5        | 0.84%   |
| 13      | 3        | 0.5%    |
| 12      | 3        | 0.5%    |
| 72      | 2        | 0.34%   |
| 47      | 2        | 0.34%   |
| 39      | 2        | 0.34%   |
| 34      | 2        | 0.34%   |
| 25      | 2        | 0.34%   |
| 142     | 1        | 0.17%   |
| 64      | 1        | 0.17%   |
| 43      | 1        | 0.17%   |
| 30      | 1        | 0.17%   |
| 26      | 1        | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 236      | 40.76%  |
| 501-600        | 137      | 23.66%  |
| Unknown        | 48       | 8.29%   |
| 301-350        | 46       | 7.94%   |
| 1001-1500      | 35       | 6.04%   |
| 351-400        | 17       | 2.94%   |
| 801-900        | 16       | 2.76%   |
| 601-700        | 15       | 2.59%   |
| 1501-2000      | 14       | 2.42%   |
| 701-800        | 7        | 1.21%   |
| 201-300        | 6        | 1.04%   |
| More than 2000 | 1        | 0.17%   |
| 901-1000       | 1        | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 381      | 70.17%  |
| 16/10   | 50       | 9.21%   |
| Unknown | 42       | 7.73%   |
| 5/4     | 28       | 5.16%   |
| 4/3     | 25       | 4.6%    |
| 1.96    | 10       | 1.84%   |
| 21/9    | 3        | 0.55%   |
| 3/2     | 2        | 0.37%   |
| 32/9    | 1        | 0.18%   |
| 1.00    | 1        | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 214      | 36.96%  |
| 141-150        | 91       | 15.72%  |
| 151-200        | 76       | 13.13%  |
| Unknown        | 48       | 8.29%   |
| 501-1000       | 36       | 6.22%   |
| More than 1000 | 30       | 5.18%   |
| 301-350        | 20       | 3.45%   |
| 351-500        | 18       | 3.11%   |
| 111-120        | 15       | 2.59%   |
| 101-110        | 9        | 1.55%   |
| 251-300        | 6        | 1.04%   |
| 121-130        | 6        | 1.04%   |
| 81-90          | 3        | 0.52%   |
| 71-80          | 3        | 0.52%   |
| 131-140        | 3        | 0.52%   |
| 91-100         | 1        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 333      | 58.83%  |
| 101-120 | 117      | 20.67%  |
| 1-50    | 55       | 9.72%   |
| Unknown | 48       | 8.48%   |
| 121-160 | 8        | 1.41%   |
| 161-240 | 5        | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 497      | 81.74%  |
| 2     | 72       | 11.84%  |
| 0     | 37       | 6.09%   |
| 3     | 2        | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 415      | 49.94%  |
| Intel                                 | 109      | 13.12%  |
| Qualcomm Atheros                      | 81       | 9.75%   |
| Nvidia                                | 52       | 6.26%   |
| TP-Link                               | 36       | 4.33%   |
| Ralink Technology                     | 23       | 2.77%   |
| Qualcomm Atheros Communications       | 21       | 2.53%   |
| VIA Technologies                      | 15       | 1.81%   |
| Ralink                                | 8        | 0.96%   |
| Microsoft                             | 8        | 0.96%   |
| Samsung Electronics                   | 7        | 0.84%   |
| Broadcom                              | 6        | 0.72%   |
| Motorola PCS                          | 5        | 0.6%    |
| NetGear                               | 4        | 0.48%   |
| Marvell Technology Group              | 4        | 0.48%   |
| D-Link System                         | 4        | 0.48%   |
| Silicon Integrated Systems [SiS]      | 3        | 0.36%   |
| MediaTek                              | 3        | 0.36%   |
| Broadcom Limited                      | 3        | 0.36%   |
| 3Com                                  | 3        | 0.36%   |
| Linksys                               | 2        | 0.24%   |
| Davicom Semiconductor                 | 2        | 0.24%   |
| D-Link                                | 2        | 0.24%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.24%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.12%   |
| Xiaomi                                | 1        | 0.12%   |
| Unknown                               | 1        | 0.12%   |
| Sundance Technology Inc / IC Plus     | 1        | 0.12%   |
| Smart Link                            | 1        | 0.12%   |
| PCTel                                 | 1        | 0.12%   |
| Ovislink                              | 1        | 0.12%   |
| Motorola                              | 1        | 0.12%   |
| Macronix [MXIC]                       | 1        | 0.12%   |
| LG Electronics                        | 1        | 0.12%   |
| Huawei Technologies                   | 1        | 0.12%   |
| Arduino SA                            | 1        | 0.12%   |
| Aquantia                              | 1        | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 355      | 38.8%   |
| Nvidia MCP61 Ethernet                                               | 48       | 5.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 22       | 2.4%    |
| Intel Ethernet Connection (2) I219-V                                | 22       | 2.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 20       | 2.19%   |
| Qualcomm Atheros AR9271 802.11n                                     | 19       | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 16       | 1.75%   |
| Intel I211 Gigabit Network Connection                               | 14       | 1.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 13       | 1.42%   |
| VIA VT6102/VT6103 [Rhine-II]                                        | 12       | 1.31%   |
| Ralink MT7601U Wireless Adapter                                     | 11       | 1.2%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 11       | 1.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 10       | 1.09%   |
| Intel Ethernet Connection (7) I219-V                                | 9        | 0.98%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 8        | 0.87%   |
| Realtek RTL8125 2.5GbE Controller                                   | 8        | 0.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 8        | 0.87%   |
| Intel Wi-Fi 6 AX200                                                 | 8        | 0.87%   |
| TP-Link 802.11ac NIC                                                | 6        | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 6        | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 6        | 0.66%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 6        | 0.66%   |
| Intel Ethernet Controller I225-V                                    | 6        | 0.66%   |
| Intel Ethernet Connection I217-V                                    | 6        | 0.66%   |
| Intel 82579V Gigabit Network Connection                             | 6        | 0.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 5        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 5        | 0.55%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller           | 5        | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 5        | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 5        | 0.55%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                          | 5        | 0.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 5        | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 5        | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 5        | 0.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 4        | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 4        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 0.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 4        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 4        | 0.44%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 4        | 0.44%   |
| Motorola PCS moto g(9) play                                         | 4        | 0.44%   |
| Intel Centrino Wireless-N 2230                                      | 4        | 0.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 4        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 4        | 0.44%   |
| VIA VT6105/VT6106S [Rhine-III]                                      | 3        | 0.33%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 3        | 0.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 3        | 0.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 3        | 0.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 3        | 0.33%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                | 3        | 0.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 3        | 0.33%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]    | 3        | 0.33%   |
| Intel Wireless 7260                                                 | 3        | 0.33%   |
| Intel Wireless 3160                                                 | 3        | 0.33%   |
| Intel Ethernet Connection (2) I218-V                                | 3        | 0.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 0.33%   |
| Intel 82578DC Gigabit Network Connection                            | 3        | 0.33%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]   | 3        | 0.33%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express     | 3        | 0.33%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                     | 3        | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Qualcomm Atheros                      | 57       | 21.59%  |
| Realtek Semiconductor                 | 56       | 21.21%  |
| Intel                                 | 36       | 13.64%  |
| TP-Link                               | 33       | 12.5%   |
| Ralink Technology                     | 23       | 8.71%   |
| Qualcomm Atheros Communications       | 21       | 7.95%   |
| Ralink                                | 8        | 3.03%   |
| Microsoft                             | 8        | 3.03%   |
| NetGear                               | 4        | 1.52%   |
| D-Link System                         | 4        | 1.52%   |
| Broadcom                              | 4        | 1.52%   |
| Linksys                               | 2        | 0.76%   |
| D-Link                                | 2        | 0.76%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.76%   |
| Samsung Electronics                   | 1        | 0.38%   |
| Ovislink                              | 1        | 0.38%   |
| MediaTek                              | 1        | 0.38%   |
| Marvell Technology Group              | 1        | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                              | Desktops | Percent |
|------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                | 20       | 7.46%   |
| Qualcomm Atheros AR9271 802.11n                                                    | 19       | 7.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                   | 16       | 5.97%   |
| Ralink MT7601U Wireless Adapter                                                    | 11       | 4.1%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                   | 11       | 4.1%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                       | 10       | 3.73%   |
| Ralink RT2870/RT3070 Wireless Adapter                                              | 8        | 2.99%   |
| Intel Wi-Fi 6 AX200                                                                | 8        | 2.99%   |
| TP-Link 802.11ac NIC                                                               | 6        | 2.24%   |
| Realtek RTL8188EE Wireless Network Adapter                                         | 6        | 2.24%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                     | 6        | 2.24%   |
| Microsoft Xbox 360 Wireless Adapter                                                | 6        | 2.24%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                         | 5        | 1.87%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                          | 5        | 1.87%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                   | 5        | 1.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                   | 5        | 1.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                        | 4        | 1.49%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                    | 4        | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                     | 4        | 1.49%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]                | 4        | 1.49%   |
| Intel Centrino Wireless-N 2230                                                     | 4        | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                                    | 4        | 1.49%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                           | 3        | 1.12%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                             | 3        | 1.12%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                          | 3        | 1.12%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                               | 3        | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                         | 3        | 1.12%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]                   | 3        | 1.12%   |
| Intel Wireless 7260                                                                | 3        | 1.12%   |
| Intel Wireless 3160                                                                | 3        | 1.12%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]                  | 3        | 1.12%   |
| TP-Link 802.11n NIC                                                                | 2        | 0.75%   |
| TP-Link 802.11ac WLAN Adapter                                                      | 2        | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                           | 2        | 0.75%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                            | 2        | 0.75%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                             | 2        | 0.75%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                              | 2        | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                            | 2        | 0.75%   |
| Realtek 802.11ac NIC                                                               | 2        | 0.75%   |
| Ralink RT5370 Wireless Adapter                                                     | 2        | 0.75%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                   | 2        | 0.75%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                         | 2        | 0.75%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]      | 2        | 0.75%   |
| Microsoft Wireless XBox Controller Dongle                                          | 2        | 0.75%   |
| Intel Wireless 7265                                                                | 2        | 0.75%   |
| Intel Wireless 3165                                                                | 2        | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                                     | 2        | 0.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                 | 2        | 0.75%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB54GC v3 802.11g Adapter [Ralink RT2070L] | 2        | 0.75%   |
| TP-Link WiFi                                                                       | 1        | 0.37%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                            | 1        | 0.37%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                              | 1        | 0.37%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                         | 1        | 0.37%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                                   | 1        | 0.37%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                    | 1        | 0.37%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                         | 1        | 0.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                    | 1        | 0.37%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                    | 1        | 0.37%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                           | 1        | 0.37%   |
| Realtek RTL8187 Wireless Adapter                                                   | 1        | 0.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 400      | 63.69%  |
| Intel                             | 90       | 14.33%  |
| Nvidia                            | 52       | 8.28%   |
| Qualcomm Atheros                  | 33       | 5.25%   |
| VIA Technologies                  | 15       | 2.39%   |
| Samsung Electronics               | 6        | 0.96%   |
| Motorola PCS                      | 4        | 0.64%   |
| TP-Link                           | 3        | 0.48%   |
| Silicon Integrated Systems [SiS]  | 3        | 0.48%   |
| Marvell Technology Group          | 3        | 0.48%   |
| Broadcom Limited                  | 3        | 0.48%   |
| 3Com                              | 3        | 0.48%   |
| MediaTek                          | 2        | 0.32%   |
| Davicom Semiconductor             | 2        | 0.32%   |
| Broadcom                          | 2        | 0.32%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.16%   |
| Xiaomi                            | 1        | 0.16%   |
| Sundance Technology Inc / IC Plus | 1        | 0.16%   |
| Macronix [MXIC]                   | 1        | 0.16%   |
| LG Electronics                    | 1        | 0.16%   |
| Huawei Technologies               | 1        | 0.16%   |
| Aquantia                          | 1        | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 355      | 55.64%  |
| Nvidia MCP61 Ethernet                                                      | 48       | 7.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 22       | 3.45%   |
| Intel Ethernet Connection (2) I219-V                                       | 22       | 3.45%   |
| Intel I211 Gigabit Network Connection                                      | 14       | 2.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 13       | 2.04%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 12       | 1.88%   |
| Intel Ethernet Connection (7) I219-V                                       | 9        | 1.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 8        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                          | 8        | 1.25%   |
| Intel Ethernet Controller I225-V                                           | 6        | 0.94%   |
| Intel Ethernet Connection I217-V                                           | 6        | 0.94%   |
| Intel 82579V Gigabit Network Connection                                    | 6        | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 5        | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 5        | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 5        | 0.78%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 5        | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 5        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 4        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 4        | 0.63%   |
| Motorola PCS moto g(9) play                                                | 4        | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 0.63%   |
| VIA VT6105/VT6106S [Rhine-III]                                             | 3        | 0.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]            | 3        | 0.47%   |
| Intel Ethernet Connection (2) I218-V                                       | 3        | 0.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 3        | 0.47%   |
| Intel 82578DC Gigabit Network Connection                                   | 3        | 0.47%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express            | 3        | 0.47%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                            | 3        | 0.47%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                  | 2        | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 2        | 0.31%   |
| Nvidia MCP77 Ethernet                                                      | 2        | 0.31%   |
| MediaTek moto e(6) plus                                                    | 2        | 0.31%   |
| Intel Ethernet Connection (10) I219-V                                      | 2        | 0.31%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 2        | 0.31%   |
| Intel 82566DC Gigabit Network Connection                                   | 2        | 0.31%   |
| Davicom DM9102 Fast Ethernet Controller                                    | 2        | 0.31%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 0.31%   |
| ZTE WCDMA MSM Z6201V                                                       | 1        | 0.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.16%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.16%   |
| Silicon Integrated Systems [SiS] 190 Ethernet Adapter                      | 1        | 0.16%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.16%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.16%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 1        | 0.16%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.16%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.16%   |
| Nvidia MCP73 Ethernet                                                      | 1        | 0.16%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.16%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1        | 0.16%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 1        | 0.16%   |
| Marvell Group 88E8050 PCI-E ASF Gigabit Ethernet Controller                | 1        | 0.16%   |
| Macronix [MXIC] MX987x5                                                    | 1        | 0.16%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                        | 1        | 0.16%   |
| Intel PRO/100 VE Network Connection                                        | 1        | 0.16%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.16%   |
| Intel Ethernet Connection I217-LM                                          | 1        | 0.16%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 0.16%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 586      | 69.43%  |
| WiFi     | 250      | 29.62%  |
| Modem    | 6        | 0.71%   |
| Unknown  | 2        | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 422      | 69.75%  |
| WiFi     | 183      | 30.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 437      | 73.08%  |
| 2     | 143      | 23.91%  |
| 3     | 12       | 2.01%   |
| 0     | 5        | 0.84%   |
| 32    | 1        | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 538      | 89.67%  |
| Yes  | 62       | 10.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 33       | 37.08%  |
| Cambridge Silicon Radio         | 33       | 37.08%  |
| Realtek Semiconductor           | 6        | 6.74%   |
| ASUSTek Computer                | 4        | 4.49%   |
| Qualcomm Atheros Communications | 2        | 2.25%   |
| Integrated System Solution      | 2        | 2.25%   |
| IMC Networks                    | 2        | 2.25%   |
| Broadcom                        | 2        | 2.25%   |
| TP-Link                         | 1        | 1.12%   |
| Roper                           | 1        | 1.12%   |
| Logitech                        | 1        | 1.12%   |
| Hewlett-Packard                 | 1        | 1.12%   |
| Conwise Technology              | 1        | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 33       | 37.08%  |
| Intel Bluetooth wireless interface                    | 8        | 8.99%   |
| Intel AX200 Bluetooth                                 | 8        | 8.99%   |
| Realtek Bluetooth Radio                               | 6        | 6.74%   |
| Intel Wireless-AC 3168 Bluetooth                      | 5        | 5.62%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 4        | 4.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 4        | 4.49%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 2.25%   |
| Intel AX201 Bluetooth                                 | 2        | 2.25%   |
| ASUS Qualcomm Bluetooth 4.1                           | 2        | 2.25%   |
| ASUS Bluetooth Radio                                  | 2        | 2.25%   |
| TP-Link TP-hink UB500 Adapter                         | 1        | 1.12%   |
| Roper Class 1 Bluetooth Dongle                        | 1        | 1.12%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 1        | 1.12%   |
| Intel Bluetooth Device                                | 1        | 1.12%   |
| Intel AX210 Bluetooth                                 | 1        | 1.12%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 1.12%   |
| Integrated System Solution Bluetooth Device           | 1        | 1.12%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.12%   |
| IMC Networks Bluetooth                                | 1        | 1.12%   |
| HP Bluetooth Adapter                                  | 1        | 1.12%   |
| Conwise CW6622                                        | 1        | 1.12%   |
| Broadcom HP Portable Bumble Bee                       | 1        | 1.12%   |
| Broadcom HP Bluethunder                               | 1        | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 286      | 33.73%  |
| Intel                                           | 280      | 33.02%  |
| Nvidia                                          | 169      | 19.93%  |
| Logitech                                        | 16       | 1.89%   |
| C-Media Electronics                             | 16       | 1.89%   |
| VIA Technologies                                | 14       | 1.65%   |
| Kingston Technology                             | 9        | 1.06%   |
| Creative Labs                                   | 7        | 0.83%   |
| Generalplus Technology                          | 5        | 0.59%   |
| Focusrite-Novation                              | 4        | 0.47%   |
| Silicon Integrated Systems [SiS]                | 3        | 0.35%   |
| Fry's Electronics                               | 3        | 0.35%   |
| Elite Silicon                                   | 3        | 0.35%   |
| Texas Instruments                               | 2        | 0.24%   |
| Samson Technologies                             | 2        | 0.24%   |
| Razer USA                                       | 2        | 0.24%   |
| Plantronics                                     | 2        | 0.24%   |
| M-Audio                                         | 2        | 0.24%   |
| ESI Audiotechnik                                | 2        | 0.24%   |
| ATI Technologies                                | 2        | 0.24%   |
| Yamaha                                          | 1        | 0.12%   |
| TEAC                                            | 1        | 0.12%   |
| Realtek Semiconductor                           | 1        | 0.12%   |
| Pro-Ject                                        | 1        | 0.12%   |
| Microsoft                                       | 1        | 0.12%   |
| Micro Star International                        | 1        | 0.12%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.12%   |
| Holtek Semiconductor                            | 1        | 0.12%   |
| Ensoniq                                         | 1        | 0.12%   |
| Creative Technology                             | 1        | 0.12%   |
| Corsair                                         | 1        | 0.12%   |
| Cirrus Logic                                    | 1        | 0.12%   |
| Chicony Electronics                             | 1        | 0.12%   |
| Casio Computer                                  | 1        | 0.12%   |
| BEHRINGER International                         | 1        | 0.12%   |
| Audient                                         | 1        | 0.12%   |
| ASUSTek Computer                                | 1        | 0.12%   |
| Astro Gaming                                    | 1        | 0.12%   |
| Arturia                                         | 1        | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD FCH Azalia Controller                                                         | 64       | 6.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 60       | 5.68%   |
| Nvidia MCP61 High Definition Audio                                                | 50       | 4.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 47       | 4.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 39       | 3.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 38       | 3.6%    |
| AMD Family 17h/19h HD Audio Controller                                            | 38       | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 37       | 3.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 33       | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 29       | 2.75%   |
| AMD Starship/Matisse HD Audio Controller                                          | 28       | 2.65%   |
| Intel 200 Series PCH HD Audio                                                     | 26       | 2.46%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 25       | 2.37%   |
| AMD Kabini HDMI/DP Audio                                                          | 23       | 2.18%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 23       | 2.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 20       | 1.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 19       | 1.8%    |
| AMD Kaveri HDMI/DP Audio Controller                                               | 19       | 1.8%    |
| Nvidia High Definition Audio Controller                                           | 17       | 1.61%   |
| AMD Trinity HDMI Audio Controller                                                 | 17       | 1.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 16       | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 15       | 1.42%   |
| Intel Cannon Lake PCH cAVS                                                        | 14       | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 13       | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                                     | 12       | 1.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 12       | 1.14%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 11       | 1.04%   |
| Nvidia GM206 High Definition Audio Controller                                     | 9        | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 9        | 0.85%   |
| AMD Navi 10 HDMI Audio                                                            | 9        | 0.85%   |
| Nvidia GM204 High Definition Audio Controller                                     | 8        | 0.76%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 8        | 0.76%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 8        | 0.76%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 7        | 0.66%   |
| Logitech USB Headset                                                              | 7        | 0.66%   |
| C-Media Electronics USB Audio Device                                              | 7        | 0.66%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 0.66%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 6        | 0.57%   |
| Nvidia GF119 HDMI Audio Controller                                                | 6        | 0.57%   |
| Nvidia GF108 High Definition Audio Controller                                     | 6        | 0.57%   |
| Intel Comet Lake PCH-V cAVS                                                       | 6        | 0.57%   |
| Intel Audio device                                                                | 6        | 0.57%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 6        | 0.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 6        | 0.57%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 6        | 0.57%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5        | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                                | 5        | 0.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 5        | 0.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5        | 0.47%   |
| Generalplus Technology USB Audio Device                                           | 5        | 0.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5        | 0.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4        | 0.38%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 4        | 0.38%   |
| Logitech Headset H390                                                             | 4        | 0.38%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 0.38%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                        | 4        | 0.38%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                   | 3        | 0.28%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.28%   |
| Nvidia GA104 High Definition Audio Controller                                     | 3        | 0.28%   |
| Kingston Technology HyperX Cloud Flight Wireless Headset                          | 3        | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 117      | 40.07%  |
| Unknown             | 63       | 21.58%  |
| Crucial             | 29       | 9.93%   |
| Corsair             | 19       | 6.51%   |
| A-DATA Technology   | 10       | 3.42%   |
| Samsung Electronics | 8        | 2.74%   |
| G.Skill             | 7        | 2.4%    |
| Patriot             | 4        | 1.37%   |
| SK hynix            | 3        | 1.03%   |
| Novatech            | 3        | 1.03%   |
| Hewlett-Packard     | 3        | 1.03%   |
| Goldkey             | 3        | 1.03%   |
| Avant               | 3        | 1.03%   |
| Super Talent        | 2        | 0.68%   |
| Magnum Tech         | 2        | 0.68%   |
| Elpida              | 2        | 0.68%   |
| Transcend           | 1        | 0.34%   |
| Thermaltake         | 1        | 0.34%   |
| Team                | 1        | 0.34%   |
| Ramos Technology    | 1        | 0.34%   |
| PNY                 | 1        | 0.34%   |
| OLOY                | 1        | 0.34%   |
| Nanya Technology    | 1        | 0.34%   |
| Mushkin             | 1        | 0.34%   |
| Micron Technology   | 1        | 0.34%   |
| Kreton              | 1        | 0.34%   |
| Hikvision           | 1        | 0.34%   |
| AVEXIR              | 1        | 0.34%   |
| AMD                 | 1        | 0.34%   |
| Unknown             | 1        | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s      | 8        | 2.44%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 7        | 2.13%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s    | 6        | 1.83%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s  | 6        | 1.83%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 5        | 1.52%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 5        | 1.52%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 4        | 1.22%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s  | 4        | 1.22%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s | 4        | 1.22%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 3        | 0.91%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                | 3        | 0.91%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s               | 3        | 0.91%   |
| Kingston RAM KHX1866C10D3/ 8GB DIMM DDR3 1866MT/s      | 3        | 0.91%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s    | 3        | 0.91%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s | 3        | 0.91%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s  | 3        | 0.91%   |
| Kingston RAM 9905702-119.A00G 8GB DIMM DDR4 2667MT/s   | 3        | 0.91%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 2        | 0.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 2        | 0.61%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                 | 2        | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 2        | 0.61%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 2        | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 2        | 0.61%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 2        | 0.61%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s               | 2        | 0.61%   |
| Unknown RAM Module 1GB DIMM                            | 2        | 0.61%   |
| Unknown RAM Module 1024MB DIMM                         | 2        | 0.61%   |
| Super Talent RAM SUPERTALENT02 8GB DIMM DDR3 1600MT/s  | 2        | 0.61%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 2        | 0.61%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1600MT/s         | 2        | 0.61%   |
| Novatech RAM N3D04H1600B REV.00 4GB DIMM DDR3 1600MT/s | 2        | 0.61%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s              | 2        | 0.61%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s    | 2        | 0.61%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s    | 2        | 0.61%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s    | 2        | 0.61%   |
| Kingston RAM KHX1600C10D3/ 4GB DIMM DDR3 1600MT/s      | 2        | 0.61%   |
| Kingston RAM 99U5702-094.A00G 8GB DIMM DDR4 2400MT/s   | 2        | 0.61%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s  | 2        | 0.61%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s  | 2        | 0.61%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s  | 2        | 0.61%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s  | 2        | 0.61%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s  | 2        | 0.61%   |
| Kingston RAM 9905734-180.A00G 16GB DIMM DDR4 2667MT/s  | 2        | 0.61%   |
| Kingston RAM 9905702-204.A00G 8GB DIMM DDR4 2667MT/s   | 2        | 0.61%   |
| Kingston RAM 9905474-019.A00LF 2GB DIMM DDR3 1333MT/s  | 2        | 0.61%   |
| Kingston RAM 9905471-001.A01LF 2GB DIMM 1600MT/s       | 2        | 0.61%   |
| Goldkey RAM GKH400SO51208-1333 4GB DIMM DDR3 1333MT/s  | 2        | 0.61%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s | 2        | 0.61%   |
| Crucial RAM BLS8G4D32AESCK.M8FE 8GB DIMM DDR4 3200MT/s | 2        | 0.61%   |
| Corsair RAM CMV4GX3M1A1600C11 4GB DIMM DDR3 1600MT/s   | 2        | 0.61%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s   | 2        | 0.61%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 2        | 0.61%   |
| Corsair RAM CMK16GX4M1B3000C15 16GB DIMM DDR4 3400MT/s | 2        | 0.61%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 2        | 0.61%   |
| Unknown RAM QDEC3U004G1658HEC 4GB DIMM DDR3 1333MT/s   | 1        | 0.3%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                   | 1        | 0.3%    |
| Unknown RAM Module 8192MB DIMM DDR3 667MT/s            | 1        | 0.3%    |
| Unknown RAM Module 8192MB DIMM 1866MT/s                | 1        | 0.3%    |
| Unknown RAM Module 8192MB DIMM 1600MT/s                | 1        | 0.3%    |
| Unknown RAM Module 8192MB DIMM 1333MT/s                | 1        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 109      | 41.44%  |
| DDR3    | 90       | 34.22%  |
| Unknown | 35       | 13.31%  |
| DDR2    | 17       | 6.46%   |
| SDRAM   | 8        | 3.04%   |
| DDR     | 4        | 1.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 258      | 98.85%  |
| SODIMM | 3        | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 122      | 42.51%  |
| 4096  | 72       | 25.09%  |
| 2048  | 47       | 16.38%  |
| 16384 | 23       | 8.01%   |
| 1024  | 16       | 5.57%   |
| 32768 | 4        | 1.39%   |
| 512   | 3        | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 53       | 17.97%  |
| 1333    | 47       | 15.93%  |
| 2400    | 31       | 10.51%  |
| 3200    | 19       | 6.44%   |
| 2667    | 14       | 4.75%   |
| Unknown | 14       | 4.75%   |
| 3600    | 11       | 3.73%   |
| 2933    | 11       | 3.73%   |
| 2666    | 11       | 3.73%   |
| 2133    | 11       | 3.73%   |
| 667     | 10       | 3.39%   |
| 3466    | 8        | 2.71%   |
| 1866    | 7        | 2.37%   |
| 3000    | 5        | 1.69%   |
| 800     | 5        | 1.69%   |
| 333     | 5        | 1.69%   |
| 1066    | 4        | 1.36%   |
| 533     | 4        | 1.36%   |
| 400     | 4        | 1.36%   |
| 3400    | 3        | 1.02%   |
| 1867    | 3        | 1.02%   |
| 3151    | 2        | 0.68%   |
| 3007    | 2        | 0.68%   |
| 3733    | 1        | 0.34%   |
| 3500    | 1        | 0.34%   |
| 3334    | 1        | 0.34%   |
| 3100    | 1        | 0.34%   |
| 2866    | 1        | 0.34%   |
| 2800    | 1        | 0.34%   |
| 2200    | 1        | 0.34%   |
| 2134    | 1        | 0.34%   |
| 1334    | 1        | 0.34%   |
| 1200    | 1        | 0.34%   |
| 1067    | 1        | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 17       | 44.74%  |
| Brother Industries  | 10       | 26.32%  |
| Seiko Epson         | 4        | 10.53%  |
| Samsung Electronics | 3        | 7.89%   |
| Ricoh               | 1        | 2.63%   |
| Pantum              | 1        | 2.63%   |
| NXP Semiconductors  | 1        | 2.63%   |
| Graphtec America    | 1        | 2.63%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| HP LaserJet Professional P 1102w              | 3        | 7.89%   |
| Brother HL-1210W series                       | 3        | 7.89%   |
| Samsung M2020 Series                          | 2        | 5.26%   |
| HP LaserJet P1006                             | 2        | 5.26%   |
| HP LaserJet P1005                             | 2        | 5.26%   |
| HP Ink Tank 110 series                        | 2        | 5.26%   |
| Brother HL-2130 series                        | 2        | 5.26%   |
| Brother HL-1200 series                        | 2        | 5.26%   |
| Brother HL-1110 series                        | 2        | 5.26%   |
| Seiko Epson XP-243 245 247 Series             | 1        | 2.63%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1        | 2.63%   |
| Seiko Epson L4150 Series                      | 1        | 2.63%   |
| Seiko Epson L355 Series                       | 1        | 2.63%   |
| Samsung Xerox Phaser 3117 Laser Printer       | 1        | 2.63%   |
| Ricoh Printing Support                        | 1        | 2.63%   |
| Pantum P2500W series                          | 1        | 2.63%   |
| NXP Semiconductors Printer-80                 | 1        | 2.63%   |
| HP PSC 1400                                   | 1        | 2.63%   |
| HP LaserJet 3050                              | 1        | 2.63%   |
| HP DeskJet F4100 Printer series               | 1        | 2.63%   |
| HP DeskJet 3630 series                        | 1        | 2.63%   |
| HP Deskjet 3050 J610 series                   | 1        | 2.63%   |
| HP DeskJet 2620 All-in-One Printer            | 1        | 2.63%   |
| HP Deskjet 2050 J510                          | 1        | 2.63%   |
| HP Color LaserJet Pro M478f-9f                | 1        | 2.63%   |
| Graphtec America Graphtec Printer             | 1        | 2.63%   |
| Brother DCP-7055 scanner/printer              | 1        | 2.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| HP ScanJet 2400c | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 26       | 24.3%   |
| Samsung Electronics         | 10       | 9.35%   |
| KYE Systems (Mouse Systems) | 9        | 8.41%   |
| Microdia                    | 7        | 6.54%   |
| Generalplus Technology      | 7        | 6.54%   |
| Z-Star Microelectronics     | 6        | 5.61%   |
| Jieli Technology            | 6        | 5.61%   |
| Chicony Electronics         | 6        | 5.61%   |
| Microsoft                   | 5        | 4.67%   |
| MacroSilicon                | 3        | 2.8%    |
| Apple                       | 3        | 2.8%    |
| Alcor Micro                 | 3        | 2.8%    |
| Silicon Motion              | 2        | 1.87%   |
| Razer USA                   | 2        | 1.87%   |
| Pixart Imaging              | 2        | 1.87%   |
| Cubeternet                  | 2        | 1.87%   |
| ARC International           | 2        | 1.87%   |
| Philips (or NXP)            | 1        | 0.93%   |
| OmniVision Technologies     | 1        | 0.93%   |
| Huawei Technologies         | 1        | 0.93%   |
| Genesys Logic               | 1        | 0.93%   |
| Aveo Technology             | 1        | 0.93%   |
| Acer                        | 1        | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Logitech Webcam C270                               | 11       | 10.28%  |
| Samsung Galaxy A5 (MTP)                            | 9        | 8.41%   |
| Jieli USB PHY 2.0                                  | 6        | 5.61%   |
| Logitech HD Pro Webcam C920                        | 5        | 4.67%   |
| Generalplus WEB CAM                                | 5        | 4.67%   |
| Microsoft LifeCam VX-800                           | 3        | 2.8%    |
| MacroSilicon USB3.0 HD VIDEO                       | 3        | 2.8%    |
| Chicony HP 0.3MP Webcam                            | 3        | 2.8%    |
| Apple iPhone 5/5C/5S/6/SE                          | 3        | 2.8%    |
| Alcor Micro USB 2.0 PC Camera                      | 3        | 2.8%    |
| Z-Star Vimicro USB Camera (Altair)                 | 2        | 1.87%   |
| Z-Star Venus USB2.0 Camera                         | 2        | 1.87%   |
| Microdia Integrated Camera                         | 2        | 1.87%   |
| Logitech C922 Pro Stream Webcam                    | 2        | 1.87%   |
| KYE Systems (Mouse Systems) Genius iSlim 2000AF V2 | 2        | 1.87%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320     | 2        | 1.87%   |
| KYE Systems (Mouse Systems) FaceCam 1000X          | 2        | 1.87%   |
| Generalplus 808 Camera                             | 2        | 1.87%   |
| Cubeternet WebCam                                  | 2        | 1.87%   |
| Chicony HP High Definition 1MP Webcam              | 2        | 1.87%   |
| ARC International Camera                           | 2        | 1.87%   |
| Z-Star USB 2.0 Web Camera                          | 1        | 0.93%   |
| Z-Star Integrated Camera                           | 1        | 0.93%   |
| Silicon Motion SM731 Camera                        | 1        | 0.93%   |
| Silicon Motion Endoscope camera                    | 1        | 0.93%   |
| Samsung Galaxy (debugging mode)                    | 1        | 0.93%   |
| Razer USA Razer Ripsaw HD - Game Capture Card      | 1        | 0.93%   |
| Razer USA Gaming Webcam [Kiyo]                     | 1        | 0.93%   |
| Pixart Imaging Webcam Genius iLook 300             | 1        | 0.93%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro               | 1        | 0.93%   |
| Philips (or NXP) Webcam SPC530NC                   | 1        | 0.93%   |
| OmniVision Monitor Webcam                          | 1        | 0.93%   |
| Microsoft LifeCam VX-500 [1357]                    | 1        | 0.93%   |
| Microsoft LifeCam HD-3000                          | 1        | 0.93%   |
| Microdia USB camera                                | 1        | 0.93%   |
| Microdia USB 2.0 Camera                            | 1        | 0.93%   |
| Microdia HDP Webcam USB                            | 1        | 0.93%   |
| Microdia Camera                                    | 1        | 0.93%   |
| Microdia Amcrest AWC2198 USB Webcam                | 1        | 0.93%   |
| Logitech Webcam C925e                              | 1        | 0.93%   |
| Logitech Webcam C200                               | 1        | 0.93%   |
| Logitech Webcam C170                               | 1        | 0.93%   |
| Logitech StreamCam                                 | 1        | 0.93%   |
| Logitech QuickCam Express                          | 1        | 0.93%   |
| Logitech HD Webcam C525                            | 1        | 0.93%   |
| Logitech HD Webcam C510                            | 1        | 0.93%   |
| Logitech B525 HD Webcam                            | 1        | 0.93%   |
| KYE Systems (Mouse Systems) Slim 1322AF            | 1        | 0.93%   |
| KYE Systems (Mouse Systems) iSlim 1320             | 1        | 0.93%   |
| KYE Systems (Mouse Systems) Genius Webcam          | 1        | 0.93%   |
| Huawei HiCamera                                    | 1        | 0.93%   |
| Genesys Logic Webcam                               | 1        | 0.93%   |
| Chicony USB2.0 HD UVC WebCam                       | 1        | 0.93%   |
| Aveo USB2.0 Camera                                 | 1        | 0.93%   |
| Acer BisonCam, NB Pro                              | 1        | 0.93%   |

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
| 0     | 501      | 82.81%  |
| 1     | 87       | 14.38%  |
| 2     | 15       | 2.48%   |
| 3     | 2        | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 56       | 48.28%  |
| Net/wireless             | 28       | 24.14%  |
| Communication controller | 6        | 5.17%   |
| Camera                   | 6        | 5.17%   |
| Net/ethernet             | 4        | 3.45%   |
| Multimedia controller    | 3        | 2.59%   |
| Modem                    | 3        | 2.59%   |
| Sound                    | 2        | 1.72%   |
| Network                  | 2        | 1.72%   |
| Firewire controller      | 2        | 1.72%   |
| Unassigned class         | 1        | 0.86%   |
| Storage/ide              | 1        | 0.86%   |
| Dvb card                 | 1        | 0.86%   |
| Bluetooth                | 1        | 0.86%   |

