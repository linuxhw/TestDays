Gentoo 2.7 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.7.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 548

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M3A78-CM                    | [b9b5673dac](https://linux-hardware.org/?probe=b9b5673dac) | Apr 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [66bb137352](https://linux-hardware.org/?probe=66bb137352) | Apr 24, 2022 |
| ASUSTek       | M3A78-CM                    | [40898b5295](https://linux-hardware.org/?probe=40898b5295) | Apr 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [2e392a500b](https://linux-hardware.org/?probe=2e392a500b) | Apr 17, 2022 |
| ASUSTek       | Z97-K/USB                   | [16aaadda77](https://linux-hardware.org/?probe=16aaadda77) | Apr 14, 2022 |
| Gigabyte      | B460 HD3                    | [c3c9ea3a20](https://linux-hardware.org/?probe=c3c9ea3a20) | Apr 14, 2022 |
| ASUSTek       | M3A78-CM                    | [8bfef0e6a5](https://linux-hardware.org/?probe=8bfef0e6a5) | Apr 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [76f3ee9c71](https://linux-hardware.org/?probe=76f3ee9c71) | Apr 10, 2022 |
| ASRock        | Z390 Extreme4               | [ed2dd10e6e](https://linux-hardware.org/?probe=ed2dd10e6e) | Apr 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3f086610fc](https://linux-hardware.org/?probe=3f086610fc) | Apr 05, 2022 |
| ASUSTek       | M3A78-CM                    | [718536ba53](https://linux-hardware.org/?probe=718536ba53) | Apr 05, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [df1549bb3b](https://linux-hardware.org/?probe=df1549bb3b) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | [368a64422d](https://linux-hardware.org/?probe=368a64422d) | Apr 03, 2022 |
| ASUSTek       | M3A78-CM                    | [ff9f133207](https://linux-hardware.org/?probe=ff9f133207) | Mar 22, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [8ed2aea22d](https://linux-hardware.org/?probe=8ed2aea22d) | Mar 20, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3be092b600](https://linux-hardware.org/?probe=3be092b600) | Mar 18, 2022 |
| MSI           | B560M PRO-VDH WIFI          | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| ASUSTek       | M3A78-CM                    | [9d4cae40f3](https://linux-hardware.org/?probe=9d4cae40f3) | Mar 15, 2022 |
| Alienware     | 0TYR0X A00                  | [b82ab5d2d7](https://linux-hardware.org/?probe=b82ab5d2d7) | Mar 14, 2022 |
| ASUSTek       | M3A78-CM                    | [df73d6674b](https://linux-hardware.org/?probe=df73d6674b) | Mar 08, 2022 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| ASUSTek       | M3A78-CM                    | [17fac3a991](https://linux-hardware.org/?probe=17fac3a991) | Mar 01, 2022 |
| Alienware     | 0TYR0X A00                  | [17eda5de26](https://linux-hardware.org/?probe=17eda5de26) | Feb 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [875e06d62c](https://linux-hardware.org/?probe=875e06d62c) | Feb 27, 2022 |
| ASUSTek       | M3A78-CM                    | [8991bf4fbe](https://linux-hardware.org/?probe=8991bf4fbe) | Feb 22, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [e2ae01f560](https://linux-hardware.org/?probe=e2ae01f560) | Feb 21, 2022 |
| MSI           | H81I                        | [c556e9c713](https://linux-hardware.org/?probe=c556e9c713) | Feb 20, 2022 |
| Gigabyte      | B460 HD3                    | [661166a163](https://linux-hardware.org/?probe=661166a163) | Feb 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| ASUSTek       | M3A78-CM                    | [0ac87ac69d](https://linux-hardware.org/?probe=0ac87ac69d) | Feb 15, 2022 |
| ASUSTek       | M3A78-CM                    | [1bcbf673fb](https://linux-hardware.org/?probe=1bcbf673fb) | Feb 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [68c1afd184](https://linux-hardware.org/?probe=68c1afd184) | Feb 06, 2022 |
| ASUSTek       | M3A78-CM                    | [bf11db84ee](https://linux-hardware.org/?probe=bf11db84ee) | Feb 01, 2022 |
| ASUSTek       | PRIME B450M-K               | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [f56c7ea90a](https://linux-hardware.org/?probe=f56c7ea90a) | Jan 29, 2022 |
| ASUSTek       | M3A78-CM                    | [f683b8cc85](https://linux-hardware.org/?probe=f683b8cc85) | Jan 25, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [236b39c9bb](https://linux-hardware.org/?probe=236b39c9bb) | Jan 23, 2022 |
| ASUSTek       | PRIME B450M-K               | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| ASRock        | 970 Pro3 R2.0               | [d1697052d6](https://linux-hardware.org/?probe=d1697052d6) | Jan 20, 2022 |
| ASUSTek       | PRIME B450M-K               | [23f6223c1a](https://linux-hardware.org/?probe=23f6223c1a) | Jan 19, 2022 |
| ASUSTek       | M3A78-CM                    | [0df79731c2](https://linux-hardware.org/?probe=0df79731c2) | Jan 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [bd9fb4fcc1](https://linux-hardware.org/?probe=bd9fb4fcc1) | Jan 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [869a119983](https://linux-hardware.org/?probe=869a119983) | Jan 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [b9999bcf7a](https://linux-hardware.org/?probe=b9999bcf7a) | Jan 17, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5ac089dd21](https://linux-hardware.org/?probe=5ac089dd21) | Jan 16, 2022 |
| ASRock        | AM1H-ITX                    | [d22612635e](https://linux-hardware.org/?probe=d22612635e) | Jan 16, 2022 |
| Gigabyte      | AX370-Gaming 3-CF           | [73773b7de6](https://linux-hardware.org/?probe=73773b7de6) | Jan 16, 2022 |
| ASUSTek       | M3A78-CM                    | [cba1c5dc66](https://linux-hardware.org/?probe=cba1c5dc66) | Jan 11, 2022 |
| ASRock        | AM1H-ITX                    | [32aec4ead0](https://linux-hardware.org/?probe=32aec4ead0) | Jan 10, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [dfe8ad0ecc](https://linux-hardware.org/?probe=dfe8ad0ecc) | Jan 09, 2022 |
| ASRock        | AM1H-ITX                    | [9cdc9e341f](https://linux-hardware.org/?probe=9cdc9e341f) | Jan 09, 2022 |
| Gigabyte      | B460 HD3                    | [99b99bd757](https://linux-hardware.org/?probe=99b99bd757) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [596fafa091](https://linux-hardware.org/?probe=596fafa091) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [d4b7cd87ac](https://linux-hardware.org/?probe=d4b7cd87ac) | Jan 05, 2022 |
| ASRock        | Q1900-ITX                   | [e7b19454b7](https://linux-hardware.org/?probe=e7b19454b7) | Jan 04, 2022 |
| ASUSTek       | M3A78-CM                    | [94b3299adb](https://linux-hardware.org/?probe=94b3299adb) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [582c2d190f](https://linux-hardware.org/?probe=582c2d190f) | Jan 03, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [519b9f223e](https://linux-hardware.org/?probe=519b9f223e) | Jan 03, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [0c97be2fbd](https://linux-hardware.org/?probe=0c97be2fbd) | Jan 02, 2022 |
| ASUSTek       | M3A78-CM                    | [f82bc92e4c](https://linux-hardware.org/?probe=f82bc92e4c) | Dec 28, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [d7e698988e](https://linux-hardware.org/?probe=d7e698988e) | Dec 26, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| Dell          | 0J3C2F A02                  | [a450e584b2](https://linux-hardware.org/?probe=a450e584b2) | Dec 22, 2021 |
| ASUSTek       | M3A78-CM                    | [57b9900cc0](https://linux-hardware.org/?probe=57b9900cc0) | Dec 20, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [0ac5deaeca](https://linux-hardware.org/?probe=0ac5deaeca) | Dec 19, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [f55494010a](https://linux-hardware.org/?probe=f55494010a) | Dec 19, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| Dell          | 0J3C2F A02                  | [b6d326beab](https://linux-hardware.org/?probe=b6d326beab) | Dec 16, 2021 |
| MSI           | Z87-G45 GAMING              | [882428b431](https://linux-hardware.org/?probe=882428b431) | Dec 15, 2021 |
| ASUSTek       | M3A78-CM                    | [48f2a95a53](https://linux-hardware.org/?probe=48f2a95a53) | Dec 13, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [89ed93528f](https://linux-hardware.org/?probe=89ed93528f) | Dec 12, 2021 |
| ASUSTek       | M3N78-EM                    | [bf180c5c33](https://linux-hardware.org/?probe=bf180c5c33) | Dec 11, 2021 |
| MSI           | B450 TOMAHAWK               | [4b39700892](https://linux-hardware.org/?probe=4b39700892) | Dec 09, 2021 |
| ASUSTek       | M3A78-CM                    | [22484fa0ea](https://linux-hardware.org/?probe=22484fa0ea) | Dec 06, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [a523b2cfda](https://linux-hardware.org/?probe=a523b2cfda) | Dec 05, 2021 |
| Dell          | 0J584C A00                  | [d443412bd4](https://linux-hardware.org/?probe=d443412bd4) | Dec 03, 2021 |
| ASUSTek       | M3A78-CM                    | [9b27bd81d4](https://linux-hardware.org/?probe=9b27bd81d4) | Nov 29, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [32229aacc0](https://linux-hardware.org/?probe=32229aacc0) | Nov 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [b0329b0b3f](https://linux-hardware.org/?probe=b0329b0b3f) | Nov 25, 2021 |
| MSI           | MEG X570 UNIFY              | [4492677869](https://linux-hardware.org/?probe=4492677869) | Nov 24, 2021 |
| ASUSTek       | M3A78-CM                    | [ceb2034a96](https://linux-hardware.org/?probe=ceb2034a96) | Nov 22, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [a480e068e3](https://linux-hardware.org/?probe=a480e068e3) | Nov 21, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | [ddb6ba2a2b](https://linux-hardware.org/?probe=ddb6ba2a2b) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | [f8501c9239](https://linux-hardware.org/?probe=f8501c9239) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | [734028d2b9](https://linux-hardware.org/?probe=734028d2b9) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | [be9ba487cd](https://linux-hardware.org/?probe=be9ba487cd) | Nov 21, 2021 |
| Gigabyte      | H310M S2H x.x               | [10578c9535](https://linux-hardware.org/?probe=10578c9535) | Nov 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [6d93d44cf9](https://linux-hardware.org/?probe=6d93d44cf9) | Nov 17, 2021 |
| Gigabyte      | B150M-HD3-CF                | [c35117afe2](https://linux-hardware.org/?probe=c35117afe2) | Nov 17, 2021 |
| ASUSTek       | M3A78-CM                    | [d6be18a4ed](https://linux-hardware.org/?probe=d6be18a4ed) | Nov 15, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [9709dc440a](https://linux-hardware.org/?probe=9709dc440a) | Nov 14, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [a72afdad07](https://linux-hardware.org/?probe=a72afdad07) | Nov 07, 2021 |
| ASRock        | B550M Steel Legend          | [fada2e4c02](https://linux-hardware.org/?probe=fada2e4c02) | Nov 06, 2021 |
| ASRock        | B550M Steel Legend          | [d805977d04](https://linux-hardware.org/?probe=d805977d04) | Nov 06, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [d1dcf79c72](https://linux-hardware.org/?probe=d1dcf79c72) | Nov 05, 2021 |
| ASUSTek       | PRIME X570-P                | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| ASUSTek       | M3A78-CM                    | [9fa6c52f38](https://linux-hardware.org/?probe=9fa6c52f38) | Nov 01, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [3ab561bbe8](https://linux-hardware.org/?probe=3ab561bbe8) | Oct 31, 2021 |
| Gigabyte      | B460 HD3                    | [d3aa74a821](https://linux-hardware.org/?probe=d3aa74a821) | Oct 29, 2021 |
| ASRock        | B550M Steel Legend          | [df8ab9effb](https://linux-hardware.org/?probe=df8ab9effb) | Oct 28, 2021 |
| HP            | 0B4Ch D                     | [eb0c052885](https://linux-hardware.org/?probe=eb0c052885) | Oct 26, 2021 |
| ASUSTek       | PRIME A520M-K               | [740c97fb1c](https://linux-hardware.org/?probe=740c97fb1c) | Oct 26, 2021 |
| ASUSTek       | M3A78-CM                    | [aa48dedaf3](https://linux-hardware.org/?probe=aa48dedaf3) | Oct 25, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [303af363ac](https://linux-hardware.org/?probe=303af363ac) | Oct 24, 2021 |
| ASRock        | X570 Pro4                   | [ba339b925b](https://linux-hardware.org/?probe=ba339b925b) | Oct 21, 2021 |
| ASUSTek       | PRIME X570-PRO              | [7ffce9bbc2](https://linux-hardware.org/?probe=7ffce9bbc2) | Oct 21, 2021 |
| ASUSTek       | PRIME X570-P                | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| ASUSTek       | M3A78-CM                    | [f262f89cbe](https://linux-hardware.org/?probe=f262f89cbe) | Oct 18, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [e023c19122](https://linux-hardware.org/?probe=e023c19122) | Oct 17, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [8b5c674cb9](https://linux-hardware.org/?probe=8b5c674cb9) | Oct 17, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [38a6005914](https://linux-hardware.org/?probe=38a6005914) | Oct 15, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [a6457a6f8e](https://linux-hardware.org/?probe=a6457a6f8e) | Oct 15, 2021 |
| ASRock        | Z390 Extreme4               | [2da9a06ef2](https://linux-hardware.org/?probe=2da9a06ef2) | Oct 11, 2021 |
| ASUSTek       | M3A78-CM                    | [2545b52894](https://linux-hardware.org/?probe=2545b52894) | Oct 11, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [786678fb4c](https://linux-hardware.org/?probe=786678fb4c) | Oct 10, 2021 |
| MSI           | MEG X570 UNIFY              | [2e312a734f](https://linux-hardware.org/?probe=2e312a734f) | Oct 08, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [8319b2b5c6](https://linux-hardware.org/?probe=8319b2b5c6) | Oct 08, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [b1178bb939](https://linux-hardware.org/?probe=b1178bb939) | Oct 07, 2021 |
| Gigabyte      | B450M DS3H V2               | [233f451319](https://linux-hardware.org/?probe=233f451319) | Oct 06, 2021 |
| HP            | 0B4Ch D                     | [02b5492901](https://linux-hardware.org/?probe=02b5492901) | Oct 06, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [67fc73c11e](https://linux-hardware.org/?probe=67fc73c11e) | Oct 04, 2021 |
| ASUSTek       | M3A78-CM                    | [a786c3ecec](https://linux-hardware.org/?probe=a786c3ecec) | Oct 04, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [d53525d772](https://linux-hardware.org/?probe=d53525d772) | Oct 03, 2021 |
| MSI           | Z370-A PRO                  | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [5ce182d7ae](https://linux-hardware.org/?probe=5ce182d7ae) | Oct 01, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [4044b3b3b2](https://linux-hardware.org/?probe=4044b3b3b2) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [6b625a8736](https://linux-hardware.org/?probe=6b625a8736) | Oct 01, 2021 |
| ASUSTek       | Maximus VIII HERO           | [1fce457ac6](https://linux-hardware.org/?probe=1fce457ac6) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [87f779767d](https://linux-hardware.org/?probe=87f779767d) | Oct 01, 2021 |
| Acer          | Aspire XC-780               | [f723ac396a](https://linux-hardware.org/?probe=f723ac396a) | Oct 01, 2021 |
| ASRock        | H170 Pro4                   | [a0d0f5002e](https://linux-hardware.org/?probe=a0d0f5002e) | Sep 29, 2021 |
| ASRock        | H170 Pro4                   | [5a3652f38b](https://linux-hardware.org/?probe=5a3652f38b) | Sep 29, 2021 |
| Gigabyte      | 990FXA-UD5                  | [c3bb6d3afa](https://linux-hardware.org/?probe=c3bb6d3afa) | Sep 29, 2021 |
| Dell          | 0J3C2F A02                  | [88104169a4](https://linux-hardware.org/?probe=88104169a4) | Sep 28, 2021 |
| ASUSTek       | M3A78-CM                    | [6057971f46](https://linux-hardware.org/?probe=6057971f46) | Sep 27, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [02d9cece31](https://linux-hardware.org/?probe=02d9cece31) | Sep 26, 2021 |
| ASUSTek       | TUF GAMING B450M-PLUS II    | [241866fa37](https://linux-hardware.org/?probe=241866fa37) | Sep 26, 2021 |
| ASRock        | X370 Professional Gaming    | [546f692061](https://linux-hardware.org/?probe=546f692061) | Sep 23, 2021 |
| Intel         | DG31PR AAD97573-205         | [2c022c21f0](https://linux-hardware.org/?probe=2c022c21f0) | Sep 22, 2021 |
| ASUSTek       | M3A78-CM                    | [1f6b39fcd2](https://linux-hardware.org/?probe=1f6b39fcd2) | Sep 20, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [5afde8487e](https://linux-hardware.org/?probe=5afde8487e) | Sep 19, 2021 |
| Gigabyte      | B460 HD3                    | [fcd5acbc90](https://linux-hardware.org/?probe=fcd5acbc90) | Sep 18, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [86d356f643](https://linux-hardware.org/?probe=86d356f643) | Sep 16, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [2f9b27ad89](https://linux-hardware.org/?probe=2f9b27ad89) | Sep 16, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [308d39b0dc](https://linux-hardware.org/?probe=308d39b0dc) | Sep 15, 2021 |
| ASUSTek       | M3A78-CM                    | [59eb80534c](https://linux-hardware.org/?probe=59eb80534c) | Sep 13, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [cfdc619c18](https://linux-hardware.org/?probe=cfdc619c18) | Sep 12, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [19555ed132](https://linux-hardware.org/?probe=19555ed132) | Sep 07, 2021 |
| ASUSTek       | M3A78-CM                    | [e89cd90c72](https://linux-hardware.org/?probe=e89cd90c72) | Sep 06, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [0fc45210cc](https://linux-hardware.org/?probe=0fc45210cc) | Sep 05, 2021 |
| ASRock        | B450M-HDV R4.0              | [78fc85808c](https://linux-hardware.org/?probe=78fc85808c) | Sep 05, 2021 |
| ASUSTek       | P5P41C                      | [e68f372c7b](https://linux-hardware.org/?probe=e68f372c7b) | Sep 05, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [f63a2003ab](https://linux-hardware.org/?probe=f63a2003ab) | Sep 05, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [40d01ef03e](https://linux-hardware.org/?probe=40d01ef03e) | Aug 31, 2021 |
| Packard Be... | FMCP7AM                     | [6872ae9fb4](https://linux-hardware.org/?probe=6872ae9fb4) | Aug 31, 2021 |
| ASUSTek       | M3A78-CM                    | [195d8fb53d](https://linux-hardware.org/?probe=195d8fb53d) | Aug 30, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [bb19294c8b](https://linux-hardware.org/?probe=bb19294c8b) | Aug 29, 2021 |
| Gigabyte      | EP43-DS3                    | [0eaf518e06](https://linux-hardware.org/?probe=0eaf518e06) | Aug 29, 2021 |
| Dell          | 0U1325                      | [0a58fab188](https://linux-hardware.org/?probe=0a58fab188) | Aug 28, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [00b0f43680](https://linux-hardware.org/?probe=00b0f43680) | Aug 28, 2021 |
| Packard Be... | FMCP7AM                     | [07fb4f5678](https://linux-hardware.org/?probe=07fb4f5678) | Aug 28, 2021 |
| MSI           | MS-7369                     | [0c6668dee5](https://linux-hardware.org/?probe=0c6668dee5) | Aug 28, 2021 |
| Dell          | 0U1325                      | [1b5dfb4b59](https://linux-hardware.org/?probe=1b5dfb4b59) | Aug 28, 2021 |
| ASUSTek       | P9X79 WS                    | [0569365ea0](https://linux-hardware.org/?probe=0569365ea0) | Aug 26, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [f521a0c69c](https://linux-hardware.org/?probe=f521a0c69c) | Aug 25, 2021 |
| MSI           | B450M PRO-M2 MAX            | [c09944da60](https://linux-hardware.org/?probe=c09944da60) | Aug 24, 2021 |
| ASUSTek       | M3A78-CM                    | [63f0c13a1f](https://linux-hardware.org/?probe=63f0c13a1f) | Aug 23, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [625e0cf2b0](https://linux-hardware.org/?probe=625e0cf2b0) | Aug 22, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [ae02b6e88b](https://linux-hardware.org/?probe=ae02b6e88b) | Aug 19, 2021 |
| ASUSTek       | P5P41C                      | [0eb4111089](https://linux-hardware.org/?probe=0eb4111089) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | [4eb4c77752](https://linux-hardware.org/?probe=4eb4c77752) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5ffe57957d](https://linux-hardware.org/?probe=5ffe57957d) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | [40f0739800](https://linux-hardware.org/?probe=40f0739800) | Aug 17, 2021 |
| ASUSTek       | M3A78-CM                    | [51860b7bbc](https://linux-hardware.org/?probe=51860b7bbc) | Aug 16, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [211803a510](https://linux-hardware.org/?probe=211803a510) | Aug 15, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [d86ce68f12](https://linux-hardware.org/?probe=d86ce68f12) | Aug 15, 2021 |
| MSI           | B550-A PRO                  | [b3ff3985c5](https://linux-hardware.org/?probe=b3ff3985c5) | Aug 13, 2021 |
| HP            | 158B                        | [d47aa82b20](https://linux-hardware.org/?probe=d47aa82b20) | Aug 12, 2021 |
| Intel         | D525MW AAE93082-301         | [fc72f0a0ea](https://linux-hardware.org/?probe=fc72f0a0ea) | Aug 11, 2021 |
| ASUSTek       | PRIME X470-PRO              | [21b619d91b](https://linux-hardware.org/?probe=21b619d91b) | Aug 11, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [d74d9e37ce](https://linux-hardware.org/?probe=d74d9e37ce) | Aug 10, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [50f209f0b0](https://linux-hardware.org/?probe=50f209f0b0) | Aug 08, 2021 |
| ASUSTek       | M3A78-CM                    | [1fce864564](https://linux-hardware.org/?probe=1fce864564) | Aug 08, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [33fffaf1c3](https://linux-hardware.org/?probe=33fffaf1c3) | Aug 07, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [ef7a0635f4](https://linux-hardware.org/?probe=ef7a0635f4) | Aug 04, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [06b423ce94](https://linux-hardware.org/?probe=06b423ce94) | Aug 01, 2021 |
| ASUSTek       | P6T DELUXE V2               | [51a1b8132e](https://linux-hardware.org/?probe=51a1b8132e) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [754750effc](https://linux-hardware.org/?probe=754750effc) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0f19cc3c0e](https://linux-hardware.org/?probe=0f19cc3c0e) | Jul 31, 2021 |
| Dell          | 09WH54 A00                  | [9885d45d4f](https://linux-hardware.org/?probe=9885d45d4f) | Jul 28, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [46b71409d7](https://linux-hardware.org/?probe=46b71409d7) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c824226d1e](https://linux-hardware.org/?probe=c824226d1e) | Jul 26, 2021 |
| ASUSTek       | M3A78-CM                    | [124c34e0b9](https://linux-hardware.org/?probe=124c34e0b9) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [ed43bc183f](https://linux-hardware.org/?probe=ed43bc183f) | Jul 25, 2021 |
| Gigabyte      | 990FXA-UD5                  | [9f22a47aea](https://linux-hardware.org/?probe=9f22a47aea) | Jul 22, 2021 |
| Gigabyte      | 990FXA-UD5                  | [5a32ec902e](https://linux-hardware.org/?probe=5a32ec902e) | Jul 22, 2021 |
| Gigabyte      | H110-D3-CF                  | [7d25217f50](https://linux-hardware.org/?probe=7d25217f50) | Jul 22, 2021 |
| ASUSTek       | M3A78-CM                    | [0c48353545](https://linux-hardware.org/?probe=0c48353545) | Jul 19, 2021 |
| Gigabyte      | B460 HD3                    | [e92a7942d5](https://linux-hardware.org/?probe=e92a7942d5) | Jul 18, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [6ab13b1c74](https://linux-hardware.org/?probe=6ab13b1c74) | Jul 18, 2021 |
| Gigabyte      | B460 HD3                    | [a43624a24b](https://linux-hardware.org/?probe=a43624a24b) | Jul 18, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [9356542b15](https://linux-hardware.org/?probe=9356542b15) | Jul 12, 2021 |
| ASUSTek       | M3A78-CM                    | [689a063b2b](https://linux-hardware.org/?probe=689a063b2b) | Jul 12, 2021 |
| ASRock        | B550M Steel Legend          | [4d378eb681](https://linux-hardware.org/?probe=4d378eb681) | Jul 10, 2021 |
| MSI           | MEG X570 GODLIKE            | [517a612c58](https://linux-hardware.org/?probe=517a612c58) | Jul 10, 2021 |
| ASRock        | B550M Steel Legend          | [ab93056d13](https://linux-hardware.org/?probe=ab93056d13) | Jul 08, 2021 |
| ASUSTek       | M3A78-CM                    | [d185d2fa34](https://linux-hardware.org/?probe=d185d2fa34) | Jul 05, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [8c345139d0](https://linux-hardware.org/?probe=8c345139d0) | Jul 04, 2021 |
| MSI           | Z590-A PRO                  | [50d75ad77d](https://linux-hardware.org/?probe=50d75ad77d) | Jul 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [4ef1e3ccac](https://linux-hardware.org/?probe=4ef1e3ccac) | Jul 03, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [4e618f85f9](https://linux-hardware.org/?probe=4e618f85f9) | Jul 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a2acbde7fd](https://linux-hardware.org/?probe=a2acbde7fd) | Jul 02, 2021 |
| Intel         | DZ77BH-55K AAG39008-400     | [04692a4293](https://linux-hardware.org/?probe=04692a4293) | Jul 02, 2021 |
| MSI           | B450 TOMAHAWK               | [ac2a4b3aea](https://linux-hardware.org/?probe=ac2a4b3aea) | Jul 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b8cc7c380d](https://linux-hardware.org/?probe=b8cc7c380d) | Jun 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2831e5a8cf](https://linux-hardware.org/?probe=2831e5a8cf) | Jun 28, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [b0e19feab6](https://linux-hardware.org/?probe=b0e19feab6) | Jun 27, 2021 |
| ASUSTek       | M3A78-CM                    | [1a5b5e8bf0](https://linux-hardware.org/?probe=1a5b5e8bf0) | Jun 27, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d442a66371](https://linux-hardware.org/?probe=d442a66371) | Jun 27, 2021 |
| Apple         | Mac-F221BEC8                | [84bf6743c1](https://linux-hardware.org/?probe=84bf6743c1) | Jun 25, 2021 |
| Apple         | Mac-F221BEC8                | [ced7e0d00d](https://linux-hardware.org/?probe=ced7e0d00d) | Jun 25, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [0f95a638f3](https://linux-hardware.org/?probe=0f95a638f3) | Jun 20, 2021 |
| ASUSTek       | M3A78-CM                    | [670b5ad32f](https://linux-hardware.org/?probe=670b5ad32f) | Jun 18, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | [f0c7a3a628](https://linux-hardware.org/?probe=f0c7a3a628) | Jun 15, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | [c429704651](https://linux-hardware.org/?probe=c429704651) | Jun 15, 2021 |
| ASUSTek       | P7P55D-E PRO                | [9a91c78c7a](https://linux-hardware.org/?probe=9a91c78c7a) | Jun 14, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [5dfa929798](https://linux-hardware.org/?probe=5dfa929798) | Jun 13, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [704bf0bba3](https://linux-hardware.org/?probe=704bf0bba3) | Jun 12, 2021 |
| ASUSTek       | M3A78-CM                    | [99786fffad](https://linux-hardware.org/?probe=99786fffad) | Jun 11, 2021 |
| MSI           | Z590-A PRO                  | [46c5072a2d](https://linux-hardware.org/?probe=46c5072a2d) | Jun 08, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [cb5c9ef223](https://linux-hardware.org/?probe=cb5c9ef223) | Jun 06, 2021 |
| ASUSTek       | M3A78-CM                    | [e3e4d9d467](https://linux-hardware.org/?probe=e3e4d9d467) | Jun 04, 2021 |
| MSI           | Z97 PC Mate                 | [73ece6c322](https://linux-hardware.org/?probe=73ece6c322) | Jun 02, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [a04eb698f8](https://linux-hardware.org/?probe=a04eb698f8) | May 30, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [7fd8ecaab2](https://linux-hardware.org/?probe=7fd8ecaab2) | May 30, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | [2767965856](https://linux-hardware.org/?probe=2767965856) | May 27, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | [67b0fcc402](https://linux-hardware.org/?probe=67b0fcc402) | May 27, 2021 |
| ASUSTek       | M3A78-CM                    | [3b96e27283](https://linux-hardware.org/?probe=3b96e27283) | May 26, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | [843f1d9b38](https://linux-hardware.org/?probe=843f1d9b38) | May 25, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | [5794d366c2](https://linux-hardware.org/?probe=5794d366c2) | May 25, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [49458a2df1](https://linux-hardware.org/?probe=49458a2df1) | May 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [73ff247804](https://linux-hardware.org/?probe=73ff247804) | May 24, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [e3bed34a3f](https://linux-hardware.org/?probe=e3bed34a3f) | May 23, 2021 |
| MSI           | X570-A PRO                  | [61a5d17b5b](https://linux-hardware.org/?probe=61a5d17b5b) | May 22, 2021 |
| MSI           | X570-A PRO                  | [23efe4a1c8](https://linux-hardware.org/?probe=23efe4a1c8) | May 22, 2021 |
| MSI           | Z590-A PRO                  | [b74e96d4be](https://linux-hardware.org/?probe=b74e96d4be) | May 22, 2021 |
| Unknown       | Cubietech Cubieboard2       | [d777d4b535](https://linux-hardware.org/?probe=d777d4b535) | May 22, 2021 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [95fb77ceae](https://linux-hardware.org/?probe=95fb77ceae) | May 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [1c2f94847e](https://linux-hardware.org/?probe=1c2f94847e) | May 20, 2021 |
| Apple         | Mac-F221BEC8                | [5104abb7a7](https://linux-hardware.org/?probe=5104abb7a7) | May 20, 2021 |
| MSI           | Z590-A PRO                  | [7927669f65](https://linux-hardware.org/?probe=7927669f65) | May 20, 2021 |
| HP            | 8643 SMVB                   | [b183baddef](https://linux-hardware.org/?probe=b183baddef) | May 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4f3165b957](https://linux-hardware.org/?probe=4f3165b957) | May 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2679a5931a](https://linux-hardware.org/?probe=2679a5931a) | May 19, 2021 |
| ASUSTek       | M3A78-CM                    | [260b86810f](https://linux-hardware.org/?probe=260b86810f) | May 19, 2021 |
| ASRock        | B450 Pro4                   | [7ae6a0f74b](https://linux-hardware.org/?probe=7ae6a0f74b) | May 18, 2021 |
| ASUSTek       | PRIME B450M-K               | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| ASUSTek       | PRIME B450M-K               | [0df80890c0](https://linux-hardware.org/?probe=0df80890c0) | May 17, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [cd60485f57](https://linux-hardware.org/?probe=cd60485f57) | May 16, 2021 |
| MSI           | Z590-A PRO                  | [8548e79e77](https://linux-hardware.org/?probe=8548e79e77) | May 16, 2021 |
| MSI           | Z590-A PRO                  | [b2cc4333b0](https://linux-hardware.org/?probe=b2cc4333b0) | May 16, 2021 |
| ASUSTek       | PRIME X470-PRO              | [065d69be16](https://linux-hardware.org/?probe=065d69be16) | May 13, 2021 |
| ASUSTek       | PRIME B450M-K               | [6bfaa47826](https://linux-hardware.org/?probe=6bfaa47826) | May 13, 2021 |
| ASUSTek       | PRIME B450M-K               | [77a0428e6b](https://linux-hardware.org/?probe=77a0428e6b) | May 13, 2021 |
| ASUSTek       | M3A78-CM                    | [9e4b4373e8](https://linux-hardware.org/?probe=9e4b4373e8) | May 12, 2021 |
| ASUSTek       | PRIME B450M-K               | [88e106999e](https://linux-hardware.org/?probe=88e106999e) | May 11, 2021 |
| ASUSTek       | PRIME B450M-K               | [2b14268533](https://linux-hardware.org/?probe=2b14268533) | May 10, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [c1dcdec760](https://linux-hardware.org/?probe=c1dcdec760) | May 09, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [46242d579f](https://linux-hardware.org/?probe=46242d579f) | May 09, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [0b6b9eab78](https://linux-hardware.org/?probe=0b6b9eab78) | May 07, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [70bb3aecd9](https://linux-hardware.org/?probe=70bb3aecd9) | May 05, 2021 |
| ASUSTek       | M3A78-CM                    | [e305a7301f](https://linux-hardware.org/?probe=e305a7301f) | May 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [193ecc62cf](https://linux-hardware.org/?probe=193ecc62cf) | May 03, 2021 |
| QDI           | P4I865A                     | [a3df896b35](https://linux-hardware.org/?probe=a3df896b35) | May 03, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [801e6126b5](https://linux-hardware.org/?probe=801e6126b5) | May 02, 2021 |
| ASUSTek       | PRIME B450M-K               | [d7ab2def9e](https://linux-hardware.org/?probe=d7ab2def9e) | May 01, 2021 |
| ASUSTek       | PRIME B450M-K               | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| ASUSTek       | PRIME Z270-A                | [aff27ae264](https://linux-hardware.org/?probe=aff27ae264) | Apr 29, 2021 |
| MSI           | MEG X570 UNIFY              | [fe32c3d470](https://linux-hardware.org/?probe=fe32c3d470) | Apr 29, 2021 |
| ASUSTek       | M3A78-CM                    | [677dc5a3c6](https://linux-hardware.org/?probe=677dc5a3c6) | Apr 26, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [48789cb28c](https://linux-hardware.org/?probe=48789cb28c) | Apr 25, 2021 |
| Unknown       | Freecom Silverstore HNCN... | [c54d9f2c0c](https://linux-hardware.org/?probe=c54d9f2c0c) | Apr 23, 2021 |
| ASUSTek       | M3A78-CM                    | [75a7ea3b75](https://linux-hardware.org/?probe=75a7ea3b75) | Apr 19, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [94022dc903](https://linux-hardware.org/?probe=94022dc903) | Apr 18, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [0db8148a33](https://linux-hardware.org/?probe=0db8148a33) | Apr 17, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [5bc34889b8](https://linux-hardware.org/?probe=5bc34889b8) | Apr 17, 2021 |
| ASUSTek       | M3A78-CM                    | [ccb567c754](https://linux-hardware.org/?probe=ccb567c754) | Apr 12, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [aa6385c431](https://linux-hardware.org/?probe=aa6385c431) | Apr 11, 2021 |
| MSI           | H310M PRO-VD PLUS           | [de7b86720f](https://linux-hardware.org/?probe=de7b86720f) | Apr 10, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | [07427b8218](https://linux-hardware.org/?probe=07427b8218) | Apr 09, 2021 |
| ASUSTek       | PRIME X470-PRO              | [ab8b789fc2](https://linux-hardware.org/?probe=ab8b789fc2) | Apr 06, 2021 |
| ASUSTek       | M3A78-CM                    | [8feef9482d](https://linux-hardware.org/?probe=8feef9482d) | Apr 05, 2021 |
| Gigabyte      | X570 AORUS XTREME           | [39f6ad5463](https://linux-hardware.org/?probe=39f6ad5463) | Apr 04, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [1f560968ab](https://linux-hardware.org/?probe=1f560968ab) | Apr 04, 2021 |
| ASUSTek       | PRIME X570-PRO              | [d51b8b7f04](https://linux-hardware.org/?probe=d51b8b7f04) | Apr 02, 2021 |
| MSI           | B450I GAMING PLUS AC        | [88b1b582b5](https://linux-hardware.org/?probe=88b1b582b5) | Apr 01, 2021 |
| ASUSTek       | P8H67-M PRO                 | [95722413a6](https://linux-hardware.org/?probe=95722413a6) | Mar 29, 2021 |
| ASUSTek       | M3A78-CM                    | [6a2de1f8a9](https://linux-hardware.org/?probe=6a2de1f8a9) | Mar 29, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [65b87ee7d8](https://linux-hardware.org/?probe=65b87ee7d8) | Mar 29, 2021 |
| ASRock        | 970 Pro3 R2.0               | [58e2163a18](https://linux-hardware.org/?probe=58e2163a18) | Mar 29, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [f0a7dd3475](https://linux-hardware.org/?probe=f0a7dd3475) | Mar 28, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | [f4da24790d](https://linux-hardware.org/?probe=f4da24790d) | Mar 27, 2021 |
| BESSTAR Te... | DMAF5 V1.0                  | [ea2ebcb877](https://linux-hardware.org/?probe=ea2ebcb877) | Mar 26, 2021 |
| ASUSTek       | M4N78-VM                    | [b3d61c6fbd](https://linux-hardware.org/?probe=b3d61c6fbd) | Mar 24, 2021 |
| Gigabyte      | Z490 AORUS MASTER           | [b89f0d11bd](https://linux-hardware.org/?probe=b89f0d11bd) | Mar 23, 2021 |
| Gigabyte      | Z490 AORUS MASTER           | [c17cb184a4](https://linux-hardware.org/?probe=c17cb184a4) | Mar 22, 2021 |
| ASUSTek       | M3A78-CM                    | [f9974d1e26](https://linux-hardware.org/?probe=f9974d1e26) | Mar 22, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [26b5c18aba](https://linux-hardware.org/?probe=26b5c18aba) | Mar 22, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [a06e6983b1](https://linux-hardware.org/?probe=a06e6983b1) | Mar 21, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [63c58340d1](https://linux-hardware.org/?probe=63c58340d1) | Mar 20, 2021 |
| ASRock        | B450M Pro4                  | [41c48a20a2](https://linux-hardware.org/?probe=41c48a20a2) | Mar 19, 2021 |
| ASUSTek       | PRIME X470-PRO              | [c3f70afbd8](https://linux-hardware.org/?probe=c3f70afbd8) | Mar 18, 2021 |
| ASRock        | B450M Pro4                  | [b075ade19c](https://linux-hardware.org/?probe=b075ade19c) | Mar 18, 2021 |
| ASUSTek       | P5Q-E                       | [8e8d411ccb](https://linux-hardware.org/?probe=8e8d411ccb) | Mar 17, 2021 |
| ASUSTek       | B85M-E                      | [46c2411987](https://linux-hardware.org/?probe=46c2411987) | Mar 17, 2021 |
| ASRock        | X370 Professional Gaming    | [677c76f624](https://linux-hardware.org/?probe=677c76f624) | Mar 17, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [fb88aba821](https://linux-hardware.org/?probe=fb88aba821) | Mar 17, 2021 |
| MSI           | B450I GAMING PLUS AC        | [3d16f2ffb4](https://linux-hardware.org/?probe=3d16f2ffb4) | Mar 16, 2021 |
| ASUSTek       | M3A78-CM                    | [9a912f6a54](https://linux-hardware.org/?probe=9a912f6a54) | Mar 15, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [88b4119893](https://linux-hardware.org/?probe=88b4119893) | Mar 14, 2021 |
| ASUSTek       | PRIME X570-P                | [01681dba78](https://linux-hardware.org/?probe=01681dba78) | Mar 14, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [7764beb1a1](https://linux-hardware.org/?probe=7764beb1a1) | Mar 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [bf856bd378](https://linux-hardware.org/?probe=bf856bd378) | Mar 11, 2021 |
| ASUSTek       | M3A78-CM                    | [ecaa4cd975](https://linux-hardware.org/?probe=ecaa4cd975) | Mar 08, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [fd82158f63](https://linux-hardware.org/?probe=fd82158f63) | Mar 07, 2021 |
| MSI           | X570-A PRO                  | [c19dde029b](https://linux-hardware.org/?probe=c19dde029b) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [0c34f3246f](https://linux-hardware.org/?probe=0c34f3246f) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [fb91319fa1](https://linux-hardware.org/?probe=fb91319fa1) | Mar 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [9f55c5ece0](https://linux-hardware.org/?probe=9f55c5ece0) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [4c28c6d22c](https://linux-hardware.org/?probe=4c28c6d22c) | Mar 03, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [6cd953f597](https://linux-hardware.org/?probe=6cd953f597) | Mar 02, 2021 |
| ASUSTek       | M3A78-CM                    | [e7bfe156f8](https://linux-hardware.org/?probe=e7bfe156f8) | Mar 01, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [38b0d3e407](https://linux-hardware.org/?probe=38b0d3e407) | Feb 28, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [d7a5611d8a](https://linux-hardware.org/?probe=d7a5611d8a) | Feb 23, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d854654bad](https://linux-hardware.org/?probe=d854654bad) | Feb 23, 2021 |
| MSI           | 970 GAMING                  | [062ccac9ff](https://linux-hardware.org/?probe=062ccac9ff) | Feb 22, 2021 |
| ASUSTek       | PRIME H470M-PLUS            | [0e4ce5d923](https://linux-hardware.org/?probe=0e4ce5d923) | Feb 22, 2021 |
| ASUSTek       | M3A78-CM                    | [ae309000e1](https://linux-hardware.org/?probe=ae309000e1) | Feb 22, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [d67d9d3b74](https://linux-hardware.org/?probe=d67d9d3b74) | Feb 21, 2021 |
| ASRock        | X370 Gaming X               | [97b686fad6](https://linux-hardware.org/?probe=97b686fad6) | Feb 21, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [f9639ea950](https://linux-hardware.org/?probe=f9639ea950) | Feb 20, 2021 |
| ASUSTek       | P8H67-M PRO                 | [066c09783c](https://linux-hardware.org/?probe=066c09783c) | Feb 20, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [ac8250480a](https://linux-hardware.org/?probe=ac8250480a) | Feb 16, 2021 |
| MSI           | MEG X570 UNIFY              | [8565fa7232](https://linux-hardware.org/?probe=8565fa7232) | Feb 15, 2021 |
| MSI           | B350M BAZOOKA               | [19cf6a4def](https://linux-hardware.org/?probe=19cf6a4def) | Feb 15, 2021 |
| ASUSTek       | P8Z68-V LX                  | [47dbd40dae](https://linux-hardware.org/?probe=47dbd40dae) | Feb 13, 2021 |
| ASRock        | AM1H-ITX                    | [a1c5772342](https://linux-hardware.org/?probe=a1c5772342) | Feb 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0d787440f2](https://linux-hardware.org/?probe=0d787440f2) | Feb 01, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [ec933f8e8a](https://linux-hardware.org/?probe=ec933f8e8a) | Jan 31, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [6d86921fcf](https://linux-hardware.org/?probe=6d86921fcf) | Jan 26, 2021 |
| ASRock        | X370 Gaming X               | [8f0d93f4e1](https://linux-hardware.org/?probe=8f0d93f4e1) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [1b3702adc5](https://linux-hardware.org/?probe=1b3702adc5) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [8eb3edac54](https://linux-hardware.org/?probe=8eb3edac54) | Jan 24, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [dc087e0399](https://linux-hardware.org/?probe=dc087e0399) | Jan 24, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [de171f7a35](https://linux-hardware.org/?probe=de171f7a35) | Jan 24, 2021 |
| MSI           | Z170-A PRO                  | [6c8926dc8c](https://linux-hardware.org/?probe=6c8926dc8c) | Jan 23, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [23602ad020](https://linux-hardware.org/?probe=23602ad020) | Jan 20, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [b5f6cc5993](https://linux-hardware.org/?probe=b5f6cc5993) | Jan 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [8c1e988f7e](https://linux-hardware.org/?probe=8c1e988f7e) | Jan 18, 2021 |
| MSI           | MEG X570 GODLIKE            | [5964a40d34](https://linux-hardware.org/?probe=5964a40d34) | Jan 17, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [25fb58cc9f](https://linux-hardware.org/?probe=25fb58cc9f) | Jan 16, 2021 |
| ASUSTek       | P8H67-M PRO                 | [1ff6f65135](https://linux-hardware.org/?probe=1ff6f65135) | Jan 15, 2021 |
| Gigabyte      | Z170X-Gaming 3              | [e4ab17605e](https://linux-hardware.org/?probe=e4ab17605e) | Jan 13, 2021 |
| ASRock        | J3455-ITX                   | [89257face1](https://linux-hardware.org/?probe=89257face1) | Jan 12, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [38332ee350](https://linux-hardware.org/?probe=38332ee350) | Jan 11, 2021 |
| HP            | 158B                        | [6bc73950dd](https://linux-hardware.org/?probe=6bc73950dd) | Jan 10, 2021 |
| ASRock        | B450 Pro4                   | [1b9975eef6](https://linux-hardware.org/?probe=1b9975eef6) | Jan 08, 2021 |
| ASRock        | X570 Steel Legend           | [48d53df339](https://linux-hardware.org/?probe=48d53df339) | Jan 08, 2021 |
| MSI           | 990FXA-GD80                 | [cc4b365068](https://linux-hardware.org/?probe=cc4b365068) | Jan 08, 2021 |
| ASRock        | B550M Steel Legend          | [a6b6bbef69](https://linux-hardware.org/?probe=a6b6bbef69) | Jan 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6d67af2066](https://linux-hardware.org/?probe=6d67af2066) | Jan 06, 2021 |
| ASRock        | AB350M Pro4                 | [b75dcb6545](https://linux-hardware.org/?probe=b75dcb6545) | Jan 05, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [6f95de2b32](https://linux-hardware.org/?probe=6f95de2b32) | Jan 05, 2021 |
| ASUSTek       | P5Q-E                       | [7c04f61d39](https://linux-hardware.org/?probe=7c04f61d39) | Jan 04, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a011c9b38f](https://linux-hardware.org/?probe=a011c9b38f) | Jan 02, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [182deb31fb](https://linux-hardware.org/?probe=182deb31fb) | Jan 02, 2021 |
| ASRock        | 970 Pro3 R2.0               | [b83ea4b5b3](https://linux-hardware.org/?probe=b83ea4b5b3) | Jan 02, 2021 |
| ASRock        | AM1H-ITX                    | [2bd69bdc3e](https://linux-hardware.org/?probe=2bd69bdc3e) | Dec 27, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [87e72db668](https://linux-hardware.org/?probe=87e72db668) | Dec 23, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d00787942f](https://linux-hardware.org/?probe=d00787942f) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [a733d01196](https://linux-hardware.org/?probe=a733d01196) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [bd927d4e12](https://linux-hardware.org/?probe=bd927d4e12) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [a41b1e7e12](https://linux-hardware.org/?probe=a41b1e7e12) | Dec 22, 2020 |
| ASRock        | X570 Taichi                 | [29d14ce28a](https://linux-hardware.org/?probe=29d14ce28a) | Dec 19, 2020 |
| ASUSTek       | P8H67-M PRO                 | [2fc2502f80](https://linux-hardware.org/?probe=2fc2502f80) | Dec 15, 2020 |
| ASRock        | H170M Pro4S                 | [debbcde352](https://linux-hardware.org/?probe=debbcde352) | Dec 11, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | [e8e2d0cdfc](https://linux-hardware.org/?probe=e8e2d0cdfc) | Dec 05, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [3dc100c9a1](https://linux-hardware.org/?probe=3dc100c9a1) | Dec 03, 2020 |
| MSI           | B450M PRO-VDH MAX           | [50917002e1](https://linux-hardware.org/?probe=50917002e1) | Dec 01, 2020 |
| MSI           | B450M PRO-VDH MAX           | [03753743e7](https://linux-hardware.org/?probe=03753743e7) | Nov 30, 2020 |
| Gigabyte      | EP45T-DS3                   | [45142a6931](https://linux-hardware.org/?probe=45142a6931) | Nov 30, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7eeb446aee](https://linux-hardware.org/?probe=7eeb446aee) | Nov 30, 2020 |
| ASUSTek       | P9X79 WS                    | [24cfa19ea6](https://linux-hardware.org/?probe=24cfa19ea6) | Nov 30, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ba86d65e42](https://linux-hardware.org/?probe=ba86d65e42) | Nov 27, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [78d68d35d8](https://linux-hardware.org/?probe=78d68d35d8) | Nov 26, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [35233c6000](https://linux-hardware.org/?probe=35233c6000) | Nov 26, 2020 |
| ASUSTek       | P8H67-M PRO                 | [4b811e60f6](https://linux-hardware.org/?probe=4b811e60f6) | Nov 26, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [dcaf1f3521](https://linux-hardware.org/?probe=dcaf1f3521) | Nov 24, 2020 |
| ASUSTek       | P8Z77-V LX                  | [af91f8b0d0](https://linux-hardware.org/?probe=af91f8b0d0) | Nov 24, 2020 |
| MSI           | B350 GAMING PLUS            | [3e9e5d4c8d](https://linux-hardware.org/?probe=3e9e5d4c8d) | Nov 22, 2020 |
| ASUSTek       | PRIME TRX40-PRO             | [9b888a1a9c](https://linux-hardware.org/?probe=9b888a1a9c) | Nov 21, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [a6ab09a54b](https://linux-hardware.org/?probe=a6ab09a54b) | Nov 19, 2020 |
| ASRock        | X570 Pro4                   | [963200e763](https://linux-hardware.org/?probe=963200e763) | Nov 18, 2020 |
| ASUSTek       | PRIME X370-PRO              | [04abcfd451](https://linux-hardware.org/?probe=04abcfd451) | Nov 18, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [7ac134ec7a](https://linux-hardware.org/?probe=7ac134ec7a) | Nov 18, 2020 |
| ASUSTek       | PRIME X470-PRO              | [a4bdac2cea](https://linux-hardware.org/?probe=a4bdac2cea) | Nov 18, 2020 |
| ASRock        | B450 Pro4                   | [c920df4f73](https://linux-hardware.org/?probe=c920df4f73) | Nov 13, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [ca2bc0592f](https://linux-hardware.org/?probe=ca2bc0592f) | Nov 09, 2020 |
| MSI           | B450-A PRO                  | [00aeeab6da](https://linux-hardware.org/?probe=00aeeab6da) | Nov 08, 2020 |
| MSI           | B450-A PRO                  | [cd67b65826](https://linux-hardware.org/?probe=cd67b65826) | Nov 06, 2020 |
| ASUSTek       | P8H67-M PRO                 | [a870d5f1e6](https://linux-hardware.org/?probe=a870d5f1e6) | Nov 06, 2020 |
| ASUSTek       | A88XM-A                     | [45cf973d9c](https://linux-hardware.org/?probe=45cf973d9c) | Oct 31, 2020 |
| MSI           | Z170-A PRO                  | [6f36f04e56](https://linux-hardware.org/?probe=6f36f04e56) | Oct 31, 2020 |
| ASUSTek       | TUF GAMING B460-PLUS        | [539bba5a4d](https://linux-hardware.org/?probe=539bba5a4d) | Oct 26, 2020 |
| ASRock        | AM1H-ITX                    | [4a6634694e](https://linux-hardware.org/?probe=4a6634694e) | Oct 25, 2020 |
| ASRock        | X370 Gaming X               | [7b50c1e794](https://linux-hardware.org/?probe=7b50c1e794) | Oct 25, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [b7a16467ac](https://linux-hardware.org/?probe=b7a16467ac) | Oct 19, 2020 |
| ASUSTek       | PRIME X570-PRO              | [3a4156ad86](https://linux-hardware.org/?probe=3a4156ad86) | Oct 17, 2020 |
| MSI           | H110M PRO-VD PLUS           | [3264edefe8](https://linux-hardware.org/?probe=3264edefe8) | Oct 17, 2020 |
| MSI           | H110M PRO-VD PLUS           | [49f9ade50f](https://linux-hardware.org/?probe=49f9ade50f) | Oct 17, 2020 |
| Gigabyte      | H110M-S2V-CF                | [2fe8128b94](https://linux-hardware.org/?probe=2fe8128b94) | Oct 15, 2020 |
| HP            | 8643 SMVB                   | [b1ebd820ea](https://linux-hardware.org/?probe=b1ebd820ea) | Oct 14, 2020 |
| ASRock        | N3150-ITX                   | [50872ff699](https://linux-hardware.org/?probe=50872ff699) | Oct 14, 2020 |
| MSI           | Z370 PC PRO                 | [6fdfdd701e](https://linux-hardware.org/?probe=6fdfdd701e) | Oct 14, 2020 |
| Dell          | 0PC5F7 A02                  | [0b4436db73](https://linux-hardware.org/?probe=0b4436db73) | Oct 14, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [bb7e9817f3](https://linux-hardware.org/?probe=bb7e9817f3) | Oct 13, 2020 |
| ASUSTek       | H97M-PLUS                   | [979e26a9ff](https://linux-hardware.org/?probe=979e26a9ff) | Oct 13, 2020 |
| Gigabyte      | H110M-S2V-CF                | [e13bfd8911](https://linux-hardware.org/?probe=e13bfd8911) | Oct 13, 2020 |
| ASRock        | X570M Pro4                  | [11624f2e68](https://linux-hardware.org/?probe=11624f2e68) | Oct 12, 2020 |
| ASRock        | X370 Professional Gaming    | [2b432df0be](https://linux-hardware.org/?probe=2b432df0be) | Oct 12, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [4c9fc71c64](https://linux-hardware.org/?probe=4c9fc71c64) | Oct 06, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [f3201a0e2c](https://linux-hardware.org/?probe=f3201a0e2c) | Oct 06, 2020 |
| ASUSTek       | H61M-K                      | [f813fe20d2](https://linux-hardware.org/?probe=f813fe20d2) | Oct 04, 2020 |
| MSI           | X370 XPOWER GAMING TITAN... | [f09de8f7dc](https://linux-hardware.org/?probe=f09de8f7dc) | Oct 01, 2020 |
| Unknown       | Intel X79                   | [3849825892](https://linux-hardware.org/?probe=3849825892) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [b048626385](https://linux-hardware.org/?probe=b048626385) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [e26cc6bcb0](https://linux-hardware.org/?probe=e26cc6bcb0) | Sep 29, 2020 |
| ASUSTek       | PRIME X370-PRO              | [ebbc140da9](https://linux-hardware.org/?probe=ebbc140da9) | Sep 28, 2020 |
| Gigabyte      | B450 AORUS PRO-CF           | [c8d28c60cd](https://linux-hardware.org/?probe=c8d28c60cd) | Sep 27, 2020 |
| ASRock        | Z170 OC Formula             | [b478607fef](https://linux-hardware.org/?probe=b478607fef) | Sep 26, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [0997ff40b0](https://linux-hardware.org/?probe=0997ff40b0) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | [00290a5d85](https://linux-hardware.org/?probe=00290a5d85) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | [449d8022e1](https://linux-hardware.org/?probe=449d8022e1) | Sep 26, 2020 |
| ASUSTek       | H81M-PLUS                   | [87f345b258](https://linux-hardware.org/?probe=87f345b258) | Sep 24, 2020 |
| Acer          | Aspire XC-710 V:1.1         | [644c742328](https://linux-hardware.org/?probe=644c742328) | Sep 23, 2020 |
| MSI           | B450M PRO-VDH PLUS          | [aac147ef3c](https://linux-hardware.org/?probe=aac147ef3c) | Sep 22, 2020 |
| ASRock        | AB350M Pro4                 | [6cd6f20aef](https://linux-hardware.org/?probe=6cd6f20aef) | Sep 22, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [f2bdd44684](https://linux-hardware.org/?probe=f2bdd44684) | Sep 18, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [15e4e278e8](https://linux-hardware.org/?probe=15e4e278e8) | Sep 18, 2020 |
| ASRock        | 970A-G                      | [c76564a1e5](https://linux-hardware.org/?probe=c76564a1e5) | Sep 16, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a1cc53584d](https://linux-hardware.org/?probe=a1cc53584d) | Sep 05, 2020 |
| ASRock        | B450M-HDV R4.0              | [cf465b6ceb](https://linux-hardware.org/?probe=cf465b6ceb) | Sep 05, 2020 |
| ASRock        | B450M-HDV R4.0              | [34b84c17b7](https://linux-hardware.org/?probe=34b84c17b7) | Sep 04, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | [4a62067798](https://linux-hardware.org/?probe=4a62067798) | Sep 03, 2020 |
| Gigabyte      | Z77X-UD5H                   | [ced4076cfe](https://linux-hardware.org/?probe=ced4076cfe) | Sep 03, 2020 |
| MSI           | B450M MORTAR MAX            | [aacb67377f](https://linux-hardware.org/?probe=aacb67377f) | Sep 03, 2020 |
| MSI           | B450M PRO-VDH MAX           | [3aacd1b61b](https://linux-hardware.org/?probe=3aacd1b61b) | Sep 03, 2020 |
| MSI           | Z97-G45 GAMING              | [e86bf6dfb8](https://linux-hardware.org/?probe=e86bf6dfb8) | Sep 03, 2020 |
| ASUSTek       | PRIME X370-PRO              | [4bf504d82b](https://linux-hardware.org/?probe=4bf504d82b) | Sep 03, 2020 |
| MSI           | X470 GAMING PLUS            | [84aef475d9](https://linux-hardware.org/?probe=84aef475d9) | Sep 02, 2020 |
| MSI           | Z77IA-E53                   | [bf99082e95](https://linux-hardware.org/?probe=bf99082e95) | Aug 28, 2020 |
| ASUSTek       | Z170-A                      | [af1f86e610](https://linux-hardware.org/?probe=af1f86e610) | Aug 25, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d17e5bf1f8](https://linux-hardware.org/?probe=d17e5bf1f8) | Aug 25, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0230526040](https://linux-hardware.org/?probe=0230526040) | Aug 20, 2020 |
| Unknown       | Unknown                     | [41ab260322](https://linux-hardware.org/?probe=41ab260322) | Aug 20, 2020 |
| Unknown       | Unknown                     | [6a7fc0088c](https://linux-hardware.org/?probe=6a7fc0088c) | Aug 19, 2020 |
| MSI           | B350 GAMING PRO CARBON      | [762b0fed7b](https://linux-hardware.org/?probe=762b0fed7b) | Aug 18, 2020 |
| Unknown       | Unknown                     | [3d3ed1b8ce](https://linux-hardware.org/?probe=3d3ed1b8ce) | Aug 15, 2020 |
| Unknown       | Unknown                     | [55f1b3cdce](https://linux-hardware.org/?probe=55f1b3cdce) | Aug 15, 2020 |
| ASUSTek       | PRIME X370-PRO              | [7d01f814d5](https://linux-hardware.org/?probe=7d01f814d5) | Aug 10, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc14f627f3](https://linux-hardware.org/?probe=cc14f627f3) | Aug 07, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d76a630eb2](https://linux-hardware.org/?probe=d76a630eb2) | Aug 07, 2020 |
| ASUSTek       | P6X58D-E                    | [3db01937e1](https://linux-hardware.org/?probe=3db01937e1) | Aug 05, 2020 |
| ASRock        | X370 Taichi                 | [e08f62cb80](https://linux-hardware.org/?probe=e08f62cb80) | Jul 23, 2020 |
| ASUSTek       | X99-M WS                    | [7a813c93b0](https://linux-hardware.org/?probe=7a813c93b0) | Jul 15, 2020 |
| Unknown       | Unknown                     | [d83097e656](https://linux-hardware.org/?probe=d83097e656) | Jul 13, 2020 |
| ASUSTek       | GRYPHON Z97                 | [e7b3ad7e11](https://linux-hardware.org/?probe=e7b3ad7e11) | Jul 07, 2020 |
| ASUSTek       | PRIME X570-PRO              | [dd3e957888](https://linux-hardware.org/?probe=dd3e957888) | Jul 03, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [f54a86a6b4](https://linux-hardware.org/?probe=f54a86a6b4) | Jun 30, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [c9529f922d](https://linux-hardware.org/?probe=c9529f922d) | Jun 29, 2020 |
| ASRockRack    | C226M WS                    | [adb729fe45](https://linux-hardware.org/?probe=adb729fe45) | Jun 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [12ca04e727](https://linux-hardware.org/?probe=12ca04e727) | Jun 27, 2020 |
| ASUSTek       | PRIME X570-P                | [16394021f5](https://linux-hardware.org/?probe=16394021f5) | Jun 21, 2020 |
| ASRock        | X370 Killer SLI             | [e68e55ff91](https://linux-hardware.org/?probe=e68e55ff91) | Jun 20, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a91b7a6ef3](https://linux-hardware.org/?probe=a91b7a6ef3) | Jun 16, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [78a788e5aa](https://linux-hardware.org/?probe=78a788e5aa) | Jun 14, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [d1c9757c3c](https://linux-hardware.org/?probe=d1c9757c3c) | Jun 11, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8ca08405df](https://linux-hardware.org/?probe=8ca08405df) | Jun 11, 2020 |
| MSI           | X570-A PRO                  | [d330af6317](https://linux-hardware.org/?probe=d330af6317) | Jun 09, 2020 |
| ASUSTek       | Z170-A                      | [81dbec3df4](https://linux-hardware.org/?probe=81dbec3df4) | Jun 09, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [40b9dbe4a5](https://linux-hardware.org/?probe=40b9dbe4a5) | Jun 08, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [50cf5c19df](https://linux-hardware.org/?probe=50cf5c19df) | Jun 08, 2020 |
| ASRock        | X570 Extreme4               | [add6daf97a](https://linux-hardware.org/?probe=add6daf97a) | Jun 07, 2020 |
| ASUSTek       | WS X299 SAGE                | [bfc9505d4b](https://linux-hardware.org/?probe=bfc9505d4b) | Jun 05, 2020 |
| ASUSTek       | P8H67-M PRO                 | [07ef877c6b](https://linux-hardware.org/?probe=07ef877c6b) | Jun 05, 2020 |
| MSI           | X470 GAMING PRO CARBON      | [9c7b7cde1e](https://linux-hardware.org/?probe=9c7b7cde1e) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | [e64653b77c](https://linux-hardware.org/?probe=e64653b77c) | Jun 04, 2020 |
| ASRock        | X399 Taichi                 | [ff470637f1](https://linux-hardware.org/?probe=ff470637f1) | Jun 04, 2020 |
| ASUSTek       | PRIME B450M-A               | [38d7220c47](https://linux-hardware.org/?probe=38d7220c47) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | [2d804a0477](https://linux-hardware.org/?probe=2d804a0477) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | [b379b98120](https://linux-hardware.org/?probe=b379b98120) | Jun 04, 2020 |
| Gigabyte      | X570 AORUS XTREME           | [cf5cf7d297](https://linux-hardware.org/?probe=cf5cf7d297) | Jun 04, 2020 |
| ASUSTek       | P6X58D-E                    | [219e253757](https://linux-hardware.org/?probe=219e253757) | Jun 04, 2020 |
| MSI           | X470 GAMING PLUS            | [713a47cd93](https://linux-hardware.org/?probe=713a47cd93) | Jun 04, 2020 |
| ASUSTek       | PRIME X370-PRO              | [66b855cb1f](https://linux-hardware.org/?probe=66b855cb1f) | Jun 04, 2020 |
| ASUSTek       | P8H67-M PRO                 | [3eeead93cd](https://linux-hardware.org/?probe=3eeead93cd) | Jun 03, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [19202ed9bc](https://linux-hardware.org/?probe=19202ed9bc) | Jun 03, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [781f2cda04](https://linux-hardware.org/?probe=781f2cda04) | Jun 03, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [03524be236](https://linux-hardware.org/?probe=03524be236) | Jun 03, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [452ae63632](https://linux-hardware.org/?probe=452ae63632) | Jun 03, 2020 |
| Intel         | DH77KC AAG39641-400         | [c70d57d5e5](https://linux-hardware.org/?probe=c70d57d5e5) | Jun 03, 2020 |
| ASRock        | X399 Taichi                 | [9c9844febe](https://linux-hardware.org/?probe=9c9844febe) | Jun 03, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [656aaf0582](https://linux-hardware.org/?probe=656aaf0582) | Jun 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [e69d1396bf](https://linux-hardware.org/?probe=e69d1396bf) | Jun 03, 2020 |
| ASRock        | X570 Steel Legend           | [379b9c17e4](https://linux-hardware.org/?probe=379b9c17e4) | May 31, 2020 |
| ASRock        | B450M-HDV R4.0              | [e0cde3f93b](https://linux-hardware.org/?probe=e0cde3f93b) | May 25, 2020 |
| ASUSTek       | P6TD DELUXE                 | [2a97c35b6b](https://linux-hardware.org/?probe=2a97c35b6b) | May 23, 2020 |
| Sun Micros... | Ultra 24 50                 | [2541d35bd4](https://linux-hardware.org/?probe=2541d35bd4) | May 23, 2020 |
| Gigabyte      | H370M D3H-CF                | [1f405a7557](https://linux-hardware.org/?probe=1f405a7557) | May 23, 2020 |
| HP            | 3648h                       | [14b2a01c1d](https://linux-hardware.org/?probe=14b2a01c1d) | May 23, 2020 |
| ASRockRack    | X470D4U                     | [09640a1376](https://linux-hardware.org/?probe=09640a1376) | May 23, 2020 |
| HP            | 0B54h D                     | [4ef026497f](https://linux-hardware.org/?probe=4ef026497f) | May 23, 2020 |
| Gigabyte      | A320M-S2H-CF                | [7d37b8ad19](https://linux-hardware.org/?probe=7d37b8ad19) | May 12, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [4e05b9111b](https://linux-hardware.org/?probe=4e05b9111b) | May 12, 2020 |
| HP            | 83C1                        | [8b7d6722b2](https://linux-hardware.org/?probe=8b7d6722b2) | May 11, 2020 |
| ASRock        | X370 Gaming K4              | [42ec09f78b](https://linux-hardware.org/?probe=42ec09f78b) | May 11, 2020 |
| ASRock        | X370 Gaming K4              | [6874d82c83](https://linux-hardware.org/?probe=6874d82c83) | May 11, 2020 |
| Gigabyte      | G31M-ES2L                   | [86a0177aac](https://linux-hardware.org/?probe=86a0177aac) | May 11, 2020 |
| Gigabyte      | G31M-ES2L                   | [8bca8a21eb](https://linux-hardware.org/?probe=8bca8a21eb) | May 11, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [0cf396063f](https://linux-hardware.org/?probe=0cf396063f) | May 11, 2020 |
| ASRock        | X470 Taichi                 | [8ca172b725](https://linux-hardware.org/?probe=8ca172b725) | May 11, 2020 |
| ASUSTek       | STRIX H270F GAMING          | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| ASUSTek       | P8B75-V                     | [05258aea35](https://linux-hardware.org/?probe=05258aea35) | May 11, 2020 |
| ASUSTek       | PRIME X470-PRO              | [0a33d02a42](https://linux-hardware.org/?probe=0a33d02a42) | May 10, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9fce6c2df1](https://linux-hardware.org/?probe=9fce6c2df1) | Apr 25, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [8625c51506](https://linux-hardware.org/?probe=8625c51506) | Apr 19, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [baaff2d847](https://linux-hardware.org/?probe=baaff2d847) | Mar 30, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [22662aad4d](https://linux-hardware.org/?probe=22662aad4d) | Mar 26, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [4514d59538](https://linux-hardware.org/?probe=4514d59538) | Mar 19, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [26c5187786](https://linux-hardware.org/?probe=26c5187786) | Mar 19, 2020 |
| ASRock        | Z170 OC Formula             | [189475c3f5](https://linux-hardware.org/?probe=189475c3f5) | Mar 04, 2020 |
| ASRock        | Z170 OC Formula             | [a405f01061](https://linux-hardware.org/?probe=a405f01061) | Mar 04, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b417c8e979](https://linux-hardware.org/?probe=b417c8e979) | Feb 24, 2020 |
| Gigabyte      | GA-990FXA-UD5               | [24bf705591](https://linux-hardware.org/?probe=24bf705591) | Feb 14, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [169fe41d8b](https://linux-hardware.org/?probe=169fe41d8b) | Jan 20, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.10.61-gentoo               | 9        | 2.56%   |
| 5.10.27-gentoo               | 9        | 2.56%   |
| 5.7.0-gentoo                 | 8        | 2.27%   |
| 5.10.76-gentoo-r1            | 7        | 1.99%   |
| 5.10.52-gentoo               | 7        | 1.99%   |
| 5.10.27-gentoo-x86_64        | 7        | 1.99%   |
| 5.4.97-gentoo                | 6        | 1.7%    |
| 5.10.61-gentoo-x86_64        | 6        | 1.7%    |
| 5.6.15-gentoo                | 5        | 1.42%   |
| 5.6.11-gentoo                | 5        | 1.42%   |
| 5.9.11-gentoo                | 4        | 1.14%   |
| 5.15.11-gentoo               | 4        | 1.14%   |
| 5.9.8-gentoo                 | 3        | 0.85%   |
| 5.9.11                       | 3        | 0.85%   |
| 5.9.1-gentoo                 | 3        | 0.85%   |
| 5.6.15-gentoo-x86_64         | 3        | 0.85%   |
| 5.4.80-gentoo-r1             | 3        | 0.85%   |
| 5.15.26-gentoo               | 3        | 0.85%   |
| 5.15.23-gentoo               | 3        | 0.85%   |
| 5.13.5-gentoo                | 3        | 0.85%   |
| 5.11.6-gentoo                | 3        | 0.85%   |
| 5.11.0-gentoo                | 3        | 0.85%   |
| 5.10.7-gentoo                | 3        | 0.85%   |
| 5.10.4-gentoo                | 3        | 0.85%   |
| 5.10.35-gentoo               | 3        | 0.85%   |
| 5.10.2-gentoo                | 3        | 0.85%   |
| 5.9.9-gentoo                 | 2        | 0.57%   |
| 5.9.8                        | 2        | 0.57%   |
| 5.9.13-gentoo                | 2        | 0.57%   |
| 5.8.10-gentoo                | 2        | 0.57%   |
| 5.8.0-gentoo-r1              | 2        | 0.57%   |
| 5.7.9-gentoo                 | 2        | 0.57%   |
| 5.7.6-gentoo                 | 2        | 0.57%   |
| 5.6.2-gentoo                 | 2        | 0.57%   |
| 5.6.14-gentoo                | 2        | 0.57%   |
| 5.6.13                       | 2        | 0.57%   |
| 5.5.0-gentoo-x86_64          | 2        | 0.57%   |
| 5.4.97-gentoo-x86_64         | 2        | 0.57%   |
| 5.4.72-gentoo                | 2        | 0.57%   |
| 5.14.14-gentoo               | 2        | 0.57%   |
| 5.13.12                      | 2        | 0.57%   |
| 5.13.0-gentoo                | 2        | 0.57%   |
| 5.12.5-gentoo                | 2        | 0.57%   |
| 5.11.21-gentoo-dist          | 2        | 0.57%   |
| 5.11.2-gentoo-rt9-x86_64     | 2        | 0.57%   |
| 5.11.11-gentoo               | 2        | 0.57%   |
| 5.11.10-gentoo               | 2        | 0.57%   |
| 5.10.52-gentoo-x86_64        | 2        | 0.57%   |
| 5.10.52-gentoo-P6B40-A4X     | 2        | 0.57%   |
| 5.10.33-gentoo-67.P4_drivers | 2        | 0.57%   |
| 5.10.16                      | 2        | 0.57%   |
| 5.10.10-zen1                 | 2        | 0.57%   |
| 5.10.10-gentoo               | 2        | 0.57%   |
| 5.10.1-gentoo                | 2        | 0.57%   |
| 5.9.8-gentoo-x86_64          | 1        | 0.28%   |
| 5.9.7                        | 1        | 0.28%   |
| 5.9.6-gentoo                 | 1        | 0.28%   |
| 5.9.2-gentoo                 | 1        | 0.28%   |
| 5.9.16-gentoo-x86_64         | 1        | 0.28%   |
| 5.9.15-gentoo-x86_64         | 1        | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.27 | 20       | 5.68%   |
| 5.10.61 | 17       | 4.83%   |
| 5.10.52 | 13       | 3.69%   |
| 5.10.76 | 12       | 3.41%   |
| 5.7.0   | 11       | 3.13%   |
| 5.6.15  | 11       | 3.13%   |
| 5.9.11  | 9        | 2.56%   |
| 5.4.97  | 9        | 2.56%   |
| 5.6.11  | 7        | 1.99%   |
| 5.9.8   | 6        | 1.7%    |
| 5.8.10  | 6        | 1.7%    |
| 5.11.6  | 6        | 1.7%    |
| 5.15.11 | 5        | 1.42%   |
| 5.9.0   | 4        | 1.14%   |
| 5.8.0   | 4        | 1.14%   |
| 5.6.14  | 4        | 1.14%   |
| 5.6.13  | 4        | 1.14%   |
| 5.6.0   | 4        | 1.14%   |
| 5.4.80  | 4        | 1.14%   |
| 5.10.5  | 4        | 1.14%   |
| 5.10.2  | 4        | 1.14%   |
| 5.10.10 | 4        | 1.14%   |
| 5.9.1   | 3        | 0.85%   |
| 5.8.12  | 3        | 0.85%   |
| 5.7.9   | 3        | 0.85%   |
| 5.7.6   | 3        | 0.85%   |
| 5.5.0   | 3        | 0.85%   |
| 5.15.26 | 3        | 0.85%   |
| 5.15.23 | 3        | 0.85%   |
| 5.13.5  | 3        | 0.85%   |
| 5.13.12 | 3        | 0.85%   |
| 5.13.0  | 3        | 0.85%   |
| 5.12.5  | 3        | 0.85%   |
| 5.11.2  | 3        | 0.85%   |
| 5.11.10 | 3        | 0.85%   |
| 5.11.0  | 3        | 0.85%   |
| 5.10.7  | 3        | 0.85%   |
| 5.10.6  | 3        | 0.85%   |
| 5.10.4  | 3        | 0.85%   |
| 5.10.35 | 3        | 0.85%   |
| 5.9.9   | 2        | 0.57%   |
| 5.9.13  | 2        | 0.57%   |
| 5.8.9   | 2        | 0.57%   |
| 5.8.6   | 2        | 0.57%   |
| 5.8.5   | 2        | 0.57%   |
| 5.8.3   | 2        | 0.57%   |
| 5.8.18  | 2        | 0.57%   |
| 5.8.14  | 2        | 0.57%   |
| 5.7.8   | 2        | 0.57%   |
| 5.6.8   | 2        | 0.57%   |
| 5.6.2   | 2        | 0.57%   |
| 5.4.72  | 2        | 0.57%   |
| 5.4.60  | 2        | 0.57%   |
| 5.17.1  | 2        | 0.57%   |
| 5.14.14 | 2        | 0.57%   |
| 5.14.13 | 2        | 0.57%   |
| 5.14.0  | 2        | 0.57%   |
| 5.13.9  | 2        | 0.57%   |
| 5.13.11 | 2        | 0.57%   |
| 5.12.13 | 2        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 93       | 28.62%  |
| 5.6     | 37       | 11.38%  |
| 5.8     | 32       | 9.85%   |
| 5.9     | 30       | 9.23%   |
| 5.4     | 24       | 7.38%   |
| 5.7     | 23       | 7.08%   |
| 5.11    | 20       | 6.15%   |
| 5.13    | 17       | 5.23%   |
| 5.14    | 14       | 4.31%   |
| 5.12    | 11       | 3.38%   |
| 5.15    | 10       | 3.08%   |
| 5.5     | 7        | 2.15%   |
| 4.19    | 3        | 0.92%   |
| 5.17    | 2        | 0.62%   |
| 5.16    | 1        | 0.31%   |
| 4.9     | 1        | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| x86_64   | 253      | 96.2%   |
| i686     | 7        | 2.66%   |
| ppc64le  | 1        | 0.38%   |
| armv7l   | 1        | 0.38%   |
| armv5tel | 1        | 0.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 100      | 35.59%  |
| KDE5          | 59       | 21%     |
| GNOME         | 46       | 16.37%  |
| XFCE          | 29       | 10.32%  |
| KDE           | 20       | 7.12%   |
| MATE          | 12       | 4.27%   |
| X-Cinnamon    | 3        | 1.07%   |
| sway          | 2        | 0.71%   |
| LXQt          | 2        | 0.71%   |
| DWM           | 2        | 0.71%   |
| XSession      | 1        | 0.36%   |
| openbox       | 1        | 0.36%   |
| LXDE          | 1        | 0.36%   |
| i3            | 1        | 0.36%   |
| Enlightenment | 1        | 0.36%   |
| awesome       | 1        | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 159      | 56.99%  |
| Unknown | 58       | 20.79%  |
| Tty     | 49       | 17.56%  |
| Wayland | 13       | 4.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 122      | 44.36%  |
| SDDM    | 69       | 25.09%  |
| LightDM | 38       | 13.82%  |
| GDM     | 28       | 10.18%  |
| SLiM    | 7        | 2.55%   |
| XDM     | 5        | 1.82%   |
| LXDM    | 5        | 1.82%   |
| TDM     | 1        | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| en_US          | 110      | 40.59%  |
| en_GB          | 22       | 8.12%   |
| Unknown        | 19       | 7.01%   |
| de_DE          | 18       | 6.64%   |
| ru_RU          | 14       | 5.17%   |
| C.UTF8         | 10       | 3.69%   |
| C              | 10       | 3.69%   |
| es_ES          | 8        | 2.95%   |
| en_CA          | 8        | 2.95%   |
| pl_PL          | 7        | 2.58%   |
| ru_RU.UTF8     | 5        | 1.85%   |
| sv_SE          | 4        | 1.48%   |
| fr_FR          | 4        | 1.48%   |
| pt_BR          | 3        | 1.11%   |
| nl_NL          | 3        | 1.11%   |
| fi_FI          | 3        | 1.11%   |
| ja_JP          | 2        | 0.74%   |
| en_US.UTF8     | 2        | 0.74%   |
| en_AU          | 2        | 0.74%   |
| uk_UA          | 1        | 0.37%   |
| ru_UA          | 1        | 0.37%   |
| pt_PT          | 1        | 0.37%   |
| it_IT          | 1        | 0.37%   |
| hu_HU          | 1        | 0.37%   |
| fr_FR.UTF8     | 1        | 0.37%   |
| et_EE          | 1        | 0.37%   |
| es_AR          | 1        | 0.37%   |
| en_NZ          | 1        | 0.37%   |
| en_IE          | 1        | 0.37%   |
| en_GB.iso88591 | 1        | 0.37%   |
| en_EN          | 1        | 0.37%   |
| en_DK          | 1        | 0.37%   |
| en_DE          | 1        | 0.37%   |
| el_GR          | 1        | 0.37%   |
| de_CH          | 1        | 0.37%   |
| ca_ES          | 1        | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 169      | 63.53%  |
| BIOS | 97       | 36.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 161      | 59.63%  |
| Btrfs    | 53       | 19.63%  |
| Xfs      | 15       | 5.56%   |
| Zfs      | 14       | 5.19%   |
| F2fs     | 14       | 5.19%   |
| Reiserfs | 7        | 2.59%   |
| XXX      | 2        | 0.74%   |
| Unknown  | 2        | 0.74%   |
| Jfs      | 1        | 0.37%   |
| Ext3     | 1        | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 217      | 81.58%  |
| MBR     | 36       | 13.53%  |
| Unknown | 13       | 4.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 182      | 65.47%  |
| Yes       | 96       | 34.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 164      | 60.97%  |
| Yes       | 105      | 39.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 98       | 37.26%  |
| MSI                 | 45       | 17.11%  |
| Gigabyte Technology | 38       | 14.45%  |
| ASRock              | 38       | 14.45%  |
| Hewlett-Packard     | 7        | 2.66%   |
| Unknown             | 6        | 2.28%   |
| Intel               | 5        | 1.9%    |
| Fujitsu             | 5        | 1.9%    |
| Dell                | 5        | 1.9%    |
| Tekram Technology   | 3        | 1.14%   |
| ASRockRack          | 2        | 0.76%   |
| Apple               | 2        | 0.76%   |
| Acer                | 2        | 0.76%   |
| Sun Microsystems    | 1        | 0.38%   |
| QDI                 | 1        | 0.38%   |
| Packard Bell        | 1        | 0.38%   |
| NZXT                | 1        | 0.38%   |
| Lenovo              | 1        | 0.38%   |
| BESSTAR Tech        | 1        | 0.38%   |
| Alienware           | 1        | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS PRIME X470-PRO            | 7        | 2.66%   |
| ASUS All Series                | 6        | 2.28%   |
| Unknown                        | 6        | 2.28%   |
| MSI MS-7A38                    | 4        | 1.52%   |
| ASUS ROG STRIX B550-F GAMING   | 4        | 1.52%   |
| ASRock B550M Steel Legend      | 4        | 1.52%   |
| Tekram P6B40-A4X-i440BX Rev    | 3        | 1.14%   |
| MSI MS-7C35                    | 3        | 1.14%   |
| MSI MS-7C02                    | 3        | 1.14%   |
| MSI MS-7B79                    | 3        | 1.14%   |
| ASUS Z170 PRO GAMING           | 3        | 1.14%   |
| ASUS TUF GAMING X570-PLUS      | 3        | 1.14%   |
| ASUS ROG CROSSHAIR VIII HERO   | 3        | 1.14%   |
| ASUS PRIME X570-PRO            | 3        | 1.14%   |
| ASUS PRIME X370-PRO            | 3        | 1.14%   |
| ASRock B450M-HDV R4.0          | 3        | 1.14%   |
| MSI MS-7C84                    | 2        | 0.76%   |
| MSI MS-7C37                    | 2        | 0.76%   |
| MSI MS-7C34                    | 2        | 0.76%   |
| MSI MS-7A34                    | 2        | 0.76%   |
| Gigabyte X570 AORUS XTREME     | 2        | 0.76%   |
| Gigabyte X570 AORUS ELITE      | 2        | 0.76%   |
| Gigabyte AB350-Gaming 3        | 2        | 0.76%   |
| Fujitsu ESPRIMO P7935          | 2        | 0.76%   |
| Fujitsu D3401-H1               | 2        | 0.76%   |
| ASUS TUF Gaming Z590-PLUS WIFI | 2        | 0.76%   |
| ASUS SABERTOOTH 990FX R2.0     | 2        | 0.76%   |
| ASUS ROG STRIX X570-F GAMING   | 2        | 0.76%   |
| ASUS ROG STRIX B550-I GAMING   | 2        | 0.76%   |
| ASUS ROG CROSSHAIR VII HERO    | 2        | 0.76%   |
| ASUS PRIME X570-P              | 2        | 0.76%   |
| ASUS P6X58D-E                  | 2        | 0.76%   |
| ASUS P5LD2-Deluxe              | 2        | 0.76%   |
| ASUS M4A89GTD-PRO/USB3         | 2        | 0.76%   |
| ASRock Z390 Extreme4           | 2        | 0.76%   |
| ASRock X570 Steel Legend       | 2        | 0.76%   |
| ASRock X399 Taichi             | 2        | 0.76%   |
| ASRock AM1H-ITX                | 2        | 0.76%   |
| Sun Microsystems Ultra 24      | 1        | 0.38%   |
| QDI P4I865A                    | 1        | 0.38%   |
| Packard Bell IMEDIA X5705 GE   | 1        | 0.38%   |
| NZXT N7 Z370                   | 1        | 0.38%   |
| MSI MS-7D18                    | 1        | 0.38%   |
| MSI MS-7D09                    | 1        | 0.38%   |
| MSI MS-7C91                    | 1        | 0.38%   |
| MSI MS-7C56                    | 1        | 0.38%   |
| MSI MS-7C13                    | 1        | 0.38%   |
| MSI MS-7B93                    | 1        | 0.38%   |
| MSI MS-7B89                    | 1        | 0.38%   |
| MSI MS-7B86                    | 1        | 0.38%   |
| MSI MS-7B84                    | 1        | 0.38%   |
| MSI MS-7B78                    | 1        | 0.38%   |
| MSI MS-7B49                    | 1        | 0.38%   |
| MSI MS-7B48                    | 1        | 0.38%   |
| MSI MS-7B00                    | 1        | 0.38%   |
| MSI MS-7A40                    | 1        | 0.38%   |
| MSI MS-7A31                    | 1        | 0.38%   |
| MSI MS-7A15                    | 1        | 0.38%   |
| MSI MS-7971                    | 1        | 0.38%   |
| MSI MS-7851                    | 1        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 25       | 9.51%   |
| ASUS ROG                | 24       | 9.13%   |
| ASUS TUF                | 10       | 3.8%    |
| Gigabyte X570           | 6        | 2.28%   |
| ASUS All                | 6        | 2.28%   |
| ASRock X570             | 6        | 2.28%   |
| Unknown                 | 6        | 2.28%   |
| ASRock X370             | 5        | 1.9%    |
| MSI MS-7A38             | 4        | 1.52%   |
| ASRock B550M            | 4        | 1.52%   |
| Tekram P6B40-A4X-i440BX | 3        | 1.14%   |
| MSI MS-7C35             | 3        | 1.14%   |
| MSI MS-7C02             | 3        | 1.14%   |
| MSI MS-7B79             | 3        | 1.14%   |
| Gigabyte B450           | 3        | 1.14%   |
| Gigabyte AB350-Gaming   | 3        | 1.14%   |
| Dell OptiPlex           | 3        | 1.14%   |
| ASUS Z170               | 3        | 1.14%   |
| ASRock B450M-HDV        | 3        | 1.14%   |
| MSI MS-7C84             | 2        | 0.76%   |
| MSI MS-7C37             | 2        | 0.76%   |
| MSI MS-7C34             | 2        | 0.76%   |
| MSI MS-7A34             | 2        | 0.76%   |
| Gigabyte Z390           | 2        | 0.76%   |
| Gigabyte B450M          | 2        | 0.76%   |
| Fujitsu ESPRIMO         | 2        | 0.76%   |
| Fujitsu D3401-H1        | 2        | 0.76%   |
| ASUS STRIX              | 2        | 0.76%   |
| ASUS SABERTOOTH         | 2        | 0.76%   |
| ASUS P6X58D-E           | 2        | 0.76%   |
| ASUS P5LD2-Deluxe       | 2        | 0.76%   |
| ASUS M4A89GTD-PRO       | 2        | 0.76%   |
| ASRock Z390             | 2        | 0.76%   |
| ASRock X399             | 2        | 0.76%   |
| ASRock AM1H-ITX         | 2        | 0.76%   |
| Acer Aspire             | 2        | 0.76%   |
| Sun Microsystems Ultra  | 1        | 0.38%   |
| QDI P4I865A             | 1        | 0.38%   |
| Packard Bell IMEDIA     | 1        | 0.38%   |
| NZXT N7                 | 1        | 0.38%   |
| MSI MS-7D18             | 1        | 0.38%   |
| MSI MS-7D09             | 1        | 0.38%   |
| MSI MS-7C91             | 1        | 0.38%   |
| MSI MS-7C56             | 1        | 0.38%   |
| MSI MS-7C13             | 1        | 0.38%   |
| MSI MS-7B93             | 1        | 0.38%   |
| MSI MS-7B89             | 1        | 0.38%   |
| MSI MS-7B86             | 1        | 0.38%   |
| MSI MS-7B84             | 1        | 0.38%   |
| MSI MS-7B78             | 1        | 0.38%   |
| MSI MS-7B49             | 1        | 0.38%   |
| MSI MS-7B48             | 1        | 0.38%   |
| MSI MS-7B00             | 1        | 0.38%   |
| MSI MS-7A40             | 1        | 0.38%   |
| MSI MS-7A31             | 1        | 0.38%   |
| MSI MS-7A15             | 1        | 0.38%   |
| MSI MS-7971             | 1        | 0.38%   |
| MSI MS-7851             | 1        | 0.38%   |
| MSI MS-7850             | 1        | 0.38%   |
| MSI MS-7821             | 1        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 51       | 19.39%  |
| 2018    | 40       | 15.21%  |
| 2020    | 37       | 14.07%  |
| 2017    | 25       | 9.51%   |
| 2015    | 15       | 5.7%    |
| 2016    | 13       | 4.94%   |
| 2013    | 13       | 4.94%   |
| 2012    | 12       | 4.56%   |
| 2010    | 10       | 3.8%    |
| 2008    | 10       | 3.8%    |
| 2009    | 7        | 2.66%   |
| 2021    | 6        | 2.28%   |
| 2014    | 6        | 2.28%   |
| 2011    | 6        | 2.28%   |
| 2000    | 3        | 1.14%   |
| Unknown | 3        | 1.14%   |
| 2007    | 2        | 0.76%   |
| 2005    | 2        | 0.76%   |
| 2004    | 1        | 0.38%   |
| 2003    | 1        | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 263      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 261      | 99.24%  |
| Enabled  | 2        | 0.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 263      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 99       | 36.8%   |
| 16.01-24.0  | 64       | 23.79%  |
| 64.01-256.0 | 45       | 16.73%  |
| 8.01-16.0   | 22       | 8.18%   |
| 3.01-4.0    | 11       | 4.09%   |
| 24.01-32.0  | 11       | 4.09%   |
| 4.01-8.0    | 10       | 3.72%   |
| 0.51-1.0    | 4        | 1.49%   |
| 2.01-3.0    | 1        | 0.37%   |
| 1.01-2.0    | 1        | 0.37%   |
| 0.01-0.5    | 1        | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 72       | 22.78%  |
| 2.01-3.0    | 56       | 17.72%  |
| 1.01-2.0    | 50       | 15.82%  |
| 8.01-16.0   | 40       | 12.66%  |
| 3.01-4.0    | 37       | 11.71%  |
| 0.01-0.5    | 22       | 6.96%   |
| 16.01-24.0  | 15       | 4.75%   |
| 0.51-1.0    | 14       | 4.43%   |
| 32.01-64.0  | 6        | 1.9%    |
| 24.01-32.0  | 3        | 0.95%   |
| 64.01-256.0 | 1        | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 73       | 25.8%   |
| 3      | 65       | 22.97%  |
| 4      | 46       | 16.25%  |
| 1      | 45       | 15.9%   |
| 5      | 29       | 10.25%  |
| 6      | 9        | 3.18%   |
| 7      | 7        | 2.47%   |
| 9      | 2        | 0.71%   |
| 8      | 2        | 0.71%   |
| 18     | 1        | 0.35%   |
| 17     | 1        | 0.35%   |
| 13     | 1        | 0.35%   |
| 11     | 1        | 0.35%   |
| 0      | 1        | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 186      | 68.63%  |
| Yes       | 85       | 31.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 258      | 98.1%   |
| No        | 5        | 1.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 166      | 61.94%  |
| Yes       | 102      | 38.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 163      | 61.28%  |
| Yes       | 103      | 38.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 52       | 19.55%  |
| Germany     | 41       | 15.41%  |
| Russia      | 23       | 8.65%   |
| UK          | 19       | 7.14%   |
| Poland      | 13       | 4.89%   |
| Spain       | 12       | 4.51%   |
| Finland     | 12       | 4.51%   |
| Canada      | 12       | 4.51%   |
| Ukraine     | 8        | 3.01%   |
| Sweden      | 8        | 3.01%   |
| France      | 8        | 3.01%   |
| Netherlands | 6        | 2.26%   |
| Greece      | 4        | 1.5%    |
| Switzerland | 3        | 1.13%   |
| Norway      | 3        | 1.13%   |
| Japan       | 3        | 1.13%   |
| China       | 3        | 1.13%   |
| Brazil      | 3        | 1.13%   |
| Australia   | 3        | 1.13%   |
| Slovakia    | 2        | 0.75%   |
| Mexico      | 2        | 0.75%   |
| Jamaica     | 2        | 0.75%   |
| Italy       | 2        | 0.75%   |
| Hong Kong   | 2        | 0.75%   |
| Czechia     | 2        | 0.75%   |
| Belarus     | 2        | 0.75%   |
| Austria     | 2        | 0.75%   |
| Argentina   | 2        | 0.75%   |
| Tunisia     | 1        | 0.38%   |
| Slovenia    | 1        | 0.38%   |
| Romania     | 1        | 0.38%   |
| Reunion     | 1        | 0.38%   |
| Philippines | 1        | 0.38%   |
| New Zealand | 1        | 0.38%   |
| Hungary     | 1        | 0.38%   |
| Estonia     | 1        | 0.38%   |
| El Salvador | 1        | 0.38%   |
| Denmark     | 1        | 0.38%   |
| Bulgaria    | 1        | 0.38%   |
| Belgium     | 1        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Warsaw               | 5        | 1.73%   |
| Vladivostok          | 5        | 1.73%   |
| Ottawa               | 5        | 1.73%   |
| Berlin               | 5        | 1.73%   |
| St Petersburg        | 4        | 1.38%   |
| Oulu                 | 4        | 1.38%   |
| Moscow               | 4        | 1.38%   |
| Helsinki             | 4        | 1.38%   |
| Fulda                | 4        | 1.38%   |
| Swansea              | 3        | 1.04%   |
| Nuremberg            | 3        | 1.04%   |
| London               | 3        | 1.04%   |
| Kyiv                 | 3        | 1.04%   |
| Cieszyn              | 3        | 1.04%   |
| Athens               | 3        | 1.04%   |
| Zurich               | 2        | 0.69%   |
| Yekaterinburg        | 2        | 0.69%   |
| Vancouver            | 2        | 0.69%   |
| Tampere              | 2        | 0.69%   |
| Sunnyvale            | 2        | 0.69%   |
| Suffolk              | 2        | 0.69%   |
| Sao Paulo            | 2        | 0.69%   |
| Paris                | 2        | 0.69%   |
| Novosibirsk          | 2        | 0.69%   |
| Munich               | 2        | 0.69%   |
| Madrid               | 2        | 0.69%   |
| Los Angeles          | 2        | 0.69%   |
| LÃ¼denscheid       | 2        | 0.69%   |
| Karlstad             | 2        | 0.69%   |
| Irvine               | 2        | 0.69%   |
| High Wycombe         | 2        | 0.69%   |
| Geleshan             | 2        | 0.69%   |
| Freiburg im Breisgau | 2        | 0.69%   |
| Ferrol               | 2        | 0.69%   |
| Falkenstein          | 2        | 0.69%   |
| Bratislava           | 2        | 0.69%   |
| Baton Rouge          | 2        | 0.69%   |
| Amsterdam            | 2        | 0.69%   |
| Almere Stad          | 2        | 0.69%   |
| Algermissen          | 2        | 0.69%   |
| Zielona GÃ³ra      | 1        | 0.35%   |
| Zaragoza             | 1        | 0.35%   |
| Yucaipa              | 1        | 0.35%   |
| Wyoming              | 1        | 0.35%   |
| Wroclaw              | 1        | 0.35%   |
| Wrentham             | 1        | 0.35%   |
| Wolvercote           | 1        | 0.35%   |
| Wilhelmsthal         | 1        | 0.35%   |
| Wijk bij Duurstede   | 1        | 0.35%   |
| Wiesau               | 1        | 0.35%   |
| West Hollywood       | 1        | 0.35%   |
| Waterloo             | 1        | 0.35%   |
| Warrington           | 1        | 0.35%   |
| Wantagh              | 1        | 0.35%   |
| Wandsworth           | 1        | 0.35%   |
| Visby                | 1        | 0.35%   |
| Virginia Beach       | 1        | 0.35%   |
| Vinnytsia            | 1        | 0.35%   |
| Vienna               | 1        | 0.35%   |
| Victoria             | 1        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 122      | 253    | 20.96%  |
| Samsung Electronics | 119      | 258    | 20.45%  |
| Seagate             | 99       | 236    | 17.01%  |
| Kingston            | 40       | 54     | 6.87%   |
| Intel               | 26       | 37     | 4.47%   |
| Hitachi             | 21       | 88     | 3.61%   |
| Toshiba             | 20       | 42     | 3.44%   |
| Crucial             | 19       | 27     | 3.26%   |
| SanDisk             | 16       | 25     | 2.75%   |
| A-DATA Technology   | 16       | 23     | 2.75%   |
| Phison              | 10       | 18     | 1.72%   |
| Corsair             | 10       | 15     | 1.72%   |
| HGST                | 8        | 27     | 1.37%   |
| Unknown             | 5        | 5      | 0.86%   |
| OCZ                 | 5        | 5      | 0.86%   |
| GOODRAM             | 5        | 33     | 0.86%   |
| PLEXTOR             | 4        | 4      | 0.69%   |
| IBM                 | 4        | 5      | 0.69%   |
| Mushkin             | 3        | 3      | 0.52%   |
| XPG                 | 2        | 2      | 0.34%   |
| Team                | 2        | 5      | 0.34%   |
| SPCC                | 2        | 2      | 0.34%   |
| Patriot             | 2        | 3      | 0.34%   |
| MDT                 | 2        | 2      | 0.34%   |
| Intenso             | 2        | 3      | 0.34%   |
| Gigabyte Technology | 2        | 3      | 0.34%   |
| Apacer              | 2        | 3      | 0.34%   |
| Transcend           | 1        | 1      | 0.17%   |
| SK Hynix            | 1        | 2      | 0.17%   |
| Silicon Motion      | 1        | 2      | 0.17%   |
| PNY                 | 1        | 1      | 0.17%   |
| Micron Technology   | 1        | 3      | 0.17%   |
| LITEONIT            | 1        | 1      | 0.17%   |
| Leven               | 1        | 2      | 0.17%   |
| KIOXIA              | 1        | 2      | 0.17%   |
| KingDian            | 1        | 1      | 0.17%   |
| Kingchuxing         | 1        | 2      | 0.17%   |
| EMTEC               | 1        | 3      | 0.17%   |
| China               | 1        | 1      | 0.17%   |
| AMD-RAID            | 1        | 2      | 0.17%   |
| AMD                 | 1        | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB        | 10       | 1.36%   |
| Samsung SSD 970 EVO 500GB        | 9        | 1.23%   |
| Samsung SSD 860 EVO 1TB          | 9        | 1.23%   |
| Samsung SSD 850 EVO 250GB        | 9        | 1.23%   |
| Samsung SSD 840 EVO 120GB        | 9        | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB   | 8        | 1.09%   |
| Samsung SSD 860 EVO 250GB        | 8        | 1.09%   |
| WDC WD30EFRX-68EUZN0 3TB         | 7        | 0.95%   |
| WDC WD40EFRX-68WT0N0 4TB         | 6        | 0.82%   |
| WDC WD40EFRX-68N32N0 4TB         | 6        | 0.82%   |
| Seagate ST2000DM001-1ER164 2TB   | 6        | 0.82%   |
| Samsung SSD 970 EVO Plus 500GB   | 6        | 0.82%   |
| Samsung SSD 970 EVO 250GB        | 6        | 0.82%   |
| Samsung SSD 970 EVO 1TB          | 6        | 0.82%   |
| Samsung SSD 960 EVO 500GB        | 6        | 0.82%   |
| Samsung SSD 860 EVO 500GB        | 6        | 0.82%   |
| Kingston SA400S37240G 240GB SSD  | 6        | 0.82%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 5        | 0.68%   |
| WDC WD20EFRX-68EUZN0 2TB         | 5        | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB         | 5        | 0.68%   |
| Seagate ST4000DM004-2CV104 4TB   | 5        | 0.68%   |
| Seagate ST3500418AS 500GB        | 5        | 0.68%   |
| Seagate ST1000DM003-1CH162 1TB   | 5        | 0.68%   |
| Samsung SSD 840 PRO Series 256GB | 5        | 0.68%   |
| Samsung SSD 840 EVO 250GB        | 5        | 0.68%   |
| Kingston SA400S37480G 480GB SSD  | 5        | 0.68%   |
| Kingston SA400S37120G 120GB SSD  | 5        | 0.68%   |
| Kingston SA2000M81000G 1TB       | 5        | 0.68%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 4        | 0.55%   |
| WDC WD10EZEX-08M2NA0 1TB         | 4        | 0.55%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 4        | 0.55%   |
| Seagate ST2000DM006-2DM164 2TB   | 4        | 0.55%   |
| Samsung SSD 980 PRO 1TB          | 4        | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB     | 4        | 0.55%   |
| Samsung SSD 850 EVO 1TB          | 4        | 0.55%   |
| Phison Sabrent Rocket 4.0 1TB    | 4        | 0.55%   |
| Kingston SUV400S37120G 120GB SSD | 4        | 0.55%   |
| Intel SSDPEKNW512G8 512GB        | 4        | 0.55%   |
| Crucial CT275MX300SSD1 275GB     | 4        | 0.55%   |
| A-DATA SX8200PNP 1TB             | 4        | 0.55%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 3        | 0.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 3        | 0.41%   |
| WDC WD20EZRX-00D8PB0 2TB         | 3        | 0.41%   |
| WDC WD1003FZEX-00K3CA0 1TB       | 3        | 0.41%   |
| Unknown SD/MMC/MS PRO 16GB       | 3        | 0.41%   |
| Toshiba DT01ACA300 3TB           | 3        | 0.41%   |
| Seagate ST8000DM004-2CX188 8TB   | 3        | 0.41%   |
| Seagate ST8000AS0002-1NA17Z 8TB  | 3        | 0.41%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 0.41%   |
| Seagate ST500DM002-1BC142 500GB  | 3        | 0.41%   |
| Seagate ST3000DM001-1ER166 3TB   | 3        | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 0.41%   |
| Samsung SSD 970 PRO 512GB        | 3        | 0.41%   |
| Samsung SSD 970 EVO Plus 250GB   | 3        | 0.41%   |
| Samsung SSD 860 EVO 2TB          | 3        | 0.41%   |
| Samsung SSD 840 EVO 1TB          | 3        | 0.41%   |
| Intel SSDSC2CW120A3 120GB        | 3        | 0.41%   |
| Intel SSDPED1D280GA 280GB        | 3        | 0.41%   |
| IBM DJSA-220 12GB                | 3        | 0.41%   |
| Hitachi HDS723020BLA642 2TB      | 3        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 109      | 220    | 40.22%  |
| Seagate             | 96       | 233    | 35.42%  |
| Hitachi             | 21       | 88     | 7.75%   |
| Toshiba             | 18       | 40     | 6.64%   |
| Samsung Electronics | 10       | 15     | 3.69%   |
| HGST                | 8        | 27     | 2.95%   |
| IBM                 | 4        | 5      | 1.48%   |
| Unknown             | 3        | 3      | 1.11%   |
| MDT                 | 2        | 2      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 76       | 135    | 37.81%  |
| Kingston            | 33       | 40     | 16.42%  |
| Crucial             | 18       | 26     | 8.96%   |
| SanDisk             | 13       | 22     | 6.47%   |
| WDC                 | 9        | 11     | 4.48%   |
| Intel               | 9        | 10     | 4.48%   |
| OCZ                 | 5        | 5      | 2.49%   |
| GOODRAM             | 5        | 33     | 2.49%   |
| A-DATA Technology   | 5        | 7      | 2.49%   |
| PLEXTOR             | 4        | 4      | 1.99%   |
| Corsair             | 4        | 5      | 1.99%   |
| Mushkin             | 2        | 2      | 1%      |
| Intenso             | 2        | 3      | 1%      |
| Unknown             | 1        | 1      | 0.5%    |
| Transcend           | 1        | 1      | 0.5%    |
| Toshiba             | 1        | 1      | 0.5%    |
| Team                | 1        | 2      | 0.5%    |
| SPCC                | 1        | 1      | 0.5%    |
| PNY                 | 1        | 1      | 0.5%    |
| Patriot             | 1        | 2      | 0.5%    |
| Micron Technology   | 1        | 3      | 0.5%    |
| LITEONIT            | 1        | 1      | 0.5%    |
| Leven               | 1        | 2      | 0.5%    |
| KingDian            | 1        | 1      | 0.5%    |
| EMTEC               | 1        | 3      | 0.5%    |
| China               | 1        | 1      | 0.5%    |
| Apacer              | 1        | 2      | 0.5%    |
| AMD-RAID            | 1        | 2      | 0.5%    |
| AMD                 | 1        | 1      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 194      | 633    | 39.43%  |
| SSD     | 154      | 328    | 31.3%   |
| NVMe    | 142      | 242    | 28.86%  |
| MMC     | 1        | 1      | 0.2%    |
| Unknown | 1        | 1      | 0.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 230      | 951    | 60.21%  |
| NVMe | 142      | 242    | 37.17%  |
| SAS  | 9        | 11     | 2.36%   |
| MMC  | 1        | 1      | 0.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 162      | 372    | 40.2%   |
| 0.51-1.0   | 104      | 179    | 25.81%  |
| 1.01-2.0   | 59       | 131    | 14.64%  |
| 3.01-4.0   | 35       | 99     | 8.68%   |
| 2.01-3.0   | 24       | 81     | 5.96%   |
| 4.01-10.0  | 16       | 81     | 3.97%   |
| 10.01-20.0 | 2        | 17     | 0.5%    |
| 20.01-50.0 | 1        | 1      | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 55       | 19.5%   |
| 501-1000       | 51       | 18.09%  |
| 1001-2000      | 43       | 15.25%  |
| 251-500        | 40       | 14.18%  |
| 101-250        | 32       | 11.35%  |
| 2001-3000      | 25       | 8.87%   |
| Unknown        | 13       | 4.61%   |
| 1-20           | 11       | 3.9%    |
| 51-100         | 7        | 2.48%   |
| 21-50          | 5        | 1.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 40       | 13.47%  |
| 501-1000       | 40       | 13.47%  |
| 251-500        | 38       | 12.79%  |
| 101-250        | 38       | 12.79%  |
| 21-50          | 33       | 11.11%  |
| 1-20           | 31       | 10.44%  |
| More than 3000 | 28       | 9.43%   |
| 51-100         | 21       | 7.07%   |
| 2001-3000      | 15       | 5.05%   |
| Unknown        | 13       | 4.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB                    | 4        | 6      | 4.21%   |
| WDC WD40EFRX-68WT0N0 4TB                     | 3        | 13     | 3.16%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 3        | 15     | 3.16%   |
| Seagate ST500DM002-1BC142 500GB              | 3        | 3      | 3.16%   |
| IBM DJSA-220 12GB                            | 3        | 3      | 3.16%   |
| Seagate ST31000340NS 1TB                     | 2        | 3      | 2.11%   |
| Seagate ST2000DL003-9VT166 2TB               | 2        | 3      | 2.11%   |
| Seagate ST1000NM0011 1TB                     | 2        | 6      | 2.11%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 2        | 4      | 2.11%   |
| MDT MD2000KS-00MJB0 200GB                    | 2        | 2      | 2.11%   |
| Hitachi HDS722020ALA330 2TB                  | 2        | 14     | 2.11%   |
| WDC WD80EFZX-68UW8N0 8TB                     | 1        | 2      | 1.05%   |
| WDC WD6400AAKS-65A7B2 640GB                  | 1        | 1      | 1.05%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 1        | 1      | 1.05%   |
| WDC WD60EFRX-68L0BN1 6TB                     | 1        | 6      | 1.05%   |
| WDC WD5000AAVS-22G9B1 500GB                  | 1        | 1      | 1.05%   |
| WDC WD5000AAKX-003CA0 500GB                  | 1        | 1      | 1.05%   |
| WDC WD40EFRX-68N32N0 4TB                     | 1        | 1      | 1.05%   |
| WDC WD4004FZWX-00GBGB0 4TB                   | 1        | 1      | 1.05%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1        | 1      | 1.05%   |
| WDC WD30EFRX-68AX9N0 3TB                     | 1        | 1      | 1.05%   |
| WDC WD2502ABYS-02B7A0 256GB                  | 1        | 1      | 1.05%   |
| WDC WD20EZRZ-00Z5HB0 2TB                     | 1        | 1      | 1.05%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 1        | 2      | 1.05%   |
| WDC WD2003FZEX-00Z4SA0 2TB                   | 1        | 1      | 1.05%   |
| WDC WD2002FAEX-007BA0 2TB                    | 1        | 1      | 1.05%   |
| WDC WD1600AAJS-75B4A0 160GB                  | 1        | 1      | 1.05%   |
| WDC WD10EZRX-00A8LB0 1TB                     | 1        | 1      | 1.05%   |
| WDC WD10EACS-22D6B0 1TB                      | 1        | 1      | 1.05%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 1        | 2      | 1.05%   |
| Toshiba MQ04ABF100 1TB                       | 1        | 1      | 1.05%   |
| Toshiba HDWD130 3TB                          | 1        | 1      | 1.05%   |
| Toshiba HDWD105 500GB                        | 1        | 2      | 1.05%   |
| Toshiba DT01ACA300 3TB                       | 1        | 1      | 1.05%   |
| Toshiba DT01ABA100V 1TB                      | 1        | 1      | 1.05%   |
| Seagate ST8000VX0022-2EJ112 8TB              | 1        | 2      | 1.05%   |
| Seagate ST500LT012-1DG142 500GB              | 1        | 1      | 1.05%   |
| Seagate ST4000DM004-2CV104 4TB               | 1        | 1      | 1.05%   |
| Seagate ST4000DM000-1F2168 4TB               | 1        | 1      | 1.05%   |
| Seagate ST3808110AS 80GB                     | 1        | 1      | 1.05%   |
| Seagate ST3500630AS 500GB                    | 1        | 1      | 1.05%   |
| Seagate ST3500413AS 500GB                    | 1        | 1      | 1.05%   |
| Seagate ST3320813AS 320GB                    | 1        | 1      | 1.05%   |
| Seagate ST3250824AS 250GB                    | 1        | 1      | 1.05%   |
| Seagate ST3250318AS 250GB                    | 1        | 1      | 1.05%   |
| Seagate ST320413A 20GB                       | 1        | 1      | 1.05%   |
| Seagate ST3120026A 120GB                     | 1        | 1      | 1.05%   |
| Seagate ST31000528AS 1TB                     | 1        | 1      | 1.05%   |
| Seagate ST3000DM001-9YN166 3TB               | 1        | 1      | 1.05%   |
| Seagate ST2000DX002-2DV164 2TB               | 1        | 1      | 1.05%   |
| Seagate ST1000NC001-1DY162 1TB               | 1        | 1      | 1.05%   |
| Seagate ST1000DM003-1CH162 1TB               | 1        | 1      | 1.05%   |
| SanDisk SSD i100 32GB                        | 1        | 1      | 1.05%   |
| Samsung Electronics SSD 970 EVO 500GB        | 1        | 1      | 1.05%   |
| Samsung Electronics SSD 970 EVO 250GB        | 1        | 1      | 1.05%   |
| Samsung Electronics SSD 960 PRO 1TB          | 1        | 2      | 1.05%   |
| Samsung Electronics SSD 960 EVO 250GB        | 1        | 2      | 1.05%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1        | 1      | 1.05%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1        | 1      | 1.05%   |
| Samsung Electronics SSD 840 250GB            | 1        | 1      | 1.05%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 54     | 32.95%  |
| WDC                 | 20       | 40     | 22.73%  |
| Samsung Electronics | 10       | 15     | 11.36%  |
| Hitachi             | 6        | 18     | 6.82%   |
| Toshiba             | 5        | 6      | 5.68%   |
| IBM                 | 3        | 3      | 3.41%   |
| PLEXTOR             | 2        | 2      | 2.27%   |
| MDT                 | 2        | 2      | 2.27%   |
| Kingston            | 2        | 2      | 2.27%   |
| Crucial             | 2        | 2      | 2.27%   |
| SanDisk             | 1        | 1      | 1.14%   |
| OCZ                 | 1        | 1      | 1.14%   |
| Mushkin             | 1        | 1      | 1.14%   |
| Intel               | 1        | 1      | 1.14%   |
| HGST                | 1        | 1      | 1.14%   |
| EMTEC               | 1        | 2      | 1.14%   |
| Corsair             | 1        | 2      | 1.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 54     | 43.28%  |
| WDC                 | 20       | 40     | 29.85%  |
| Hitachi             | 6        | 18     | 8.96%   |
| Toshiba             | 5        | 6      | 7.46%   |
| IBM                 | 3        | 3      | 4.48%   |
| MDT                 | 2        | 2      | 2.99%   |
| Samsung Electronics | 1        | 2      | 1.49%   |
| HGST                | 1        | 1      | 1.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 61       | 126    | 74.39%  |
| SSD  | 16       | 20     | 19.51%  |
| NVMe | 5        | 7      | 6.1%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB                     | 1        | 1      | 33.33%  |
| Seagate ST31500341AS 1TB                         | 1        | 1      | 33.33%  |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1        | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 33.33%  |
| Seagate             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 247      | 989    | 69.97%  |
| Malfunc  | 80       | 153    | 22.66%  |
| Detected | 23       | 59     | 6.52%   |
| Failed   | 3        | 4      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| AMD                           | 142      | 31.21%  |
| Intel                         | 117      | 25.71%  |
| Samsung Electronics           | 66       | 14.51%  |
| ASMedia Technology            | 24       | 5.27%   |
| Phison Electronics            | 21       | 4.62%   |
| Sandisk                       | 15       | 3.3%    |
| ADATA Technology              | 13       | 2.86%   |
| Marvell Technology Group      | 11       | 2.42%   |
| Kingston Technology Company   | 9        | 1.98%   |
| JMicron Technology            | 6        | 1.32%   |
| Nvidia                        | 4        | 0.88%   |
| LSI Logic / Symbios Logic     | 4        | 0.88%   |
| Silicon Motion                | 3        | 0.66%   |
| Silicon Image                 | 3        | 0.66%   |
| Realtek Semiconductor         | 3        | 0.66%   |
| Adaptec                       | 3        | 0.66%   |
| Toshiba America Info Systems  | 2        | 0.44%   |
| Seagate Technology            | 2        | 0.44%   |
| Broadcom / LSI                | 2        | 0.44%   |
| VIA Technologies              | 1        | 0.22%   |
| SK Hynix                      | 1        | 0.22%   |
| Micron/Crucial Technology     | 1        | 0.22%   |
| Lite-On IT Corp. / Plextor    | 1        | 0.22%   |
| Integrated Technology Express | 1        | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 109      | 19.36%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 43       | 7.64%   |
| AMD 400 Series Chipset SATA Controller                                         | 43       | 7.64%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 24       | 4.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 21       | 3.73%   |
| AMD 500 Series Chipset SATA Controller                                         | 15       | 2.66%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 13       | 2.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12       | 2.13%   |
| AMD X370 Series Chipset SATA Controller                                        | 12       | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12       | 2.13%   |
| Phison E16 PCIe4 NVMe Controller                                               | 10       | 1.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 10       | 1.78%   |
| Intel SSD 660P Series                                                          | 9        | 1.6%    |
| Intel SATA Controller [RAID mode]                                              | 9        | 1.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9        | 1.6%    |
| AMD 300 Series Chipset SATA Controller                                         | 9        | 1.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8        | 1.42%   |
| Phison E12 NVMe Controller                                                     | 7        | 1.24%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7        | 1.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7        | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7        | 1.24%   |
| Kingston Company A2000 NVMe SSD                                                | 6        | 1.07%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 5        | 0.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5        | 0.89%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5        | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5        | 0.89%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4        | 0.71%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 4        | 0.71%   |
| Intel Optane SSD 900P Series                                                   | 4        | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 0.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4        | 0.71%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 0.71%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3        | 0.53%   |
| Samsung NVMe SSD Controller 980                                                | 3        | 0.53%   |
| Realtek Realtek Non-Volatile memory controller                                 | 3        | 0.53%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 0.53%   |
| JMicron JMB368 IDE controller                                                  | 3        | 0.53%   |
| Intel SSD 600P Series                                                          | 3        | 0.53%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 3        | 0.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3        | 0.53%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 2        | 0.36%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 2        | 0.36%   |
| Sandisk Non-Volatile memory controller                                         | 2        | 0.36%   |
| Phison E7 NVMe Controller                                                      | 2        | 0.36%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 2        | 0.36%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 2        | 0.36%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 2        | 0.36%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2        | 0.36%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 0.36%   |
| JMicron JMB361 AHCI/IDE                                                        | 2        | 0.36%   |
| Intel Non-Volatile memory controller                                           | 2        | 0.36%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2        | 0.36%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 0.36%   |
| Intel 82801EB (ICH5) SATA Controller                                           | 2        | 0.36%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 0.36%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                            | 2        | 0.36%   |
| AMD X399 Series Chipset SATA Controller                                        | 2        | 0.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2        | 0.36%   |
| VIA VT6421 IDE/SATA Controller                                                 | 1        | 0.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 236      | 54.25%  |
| NVMe | 142      | 32.64%  |
| IDE  | 31       | 7.13%   |
| RAID | 18       | 4.14%   |
| SAS  | 4        | 0.92%   |
| SCSI | 4        | 0.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 148      | 56.27%  |
| Intel                    | 112      | 42.59%  |
| PowerNV C1P9S01 REV 1.01 | 1        | 0.38%   |
| Marvell Semiconductor    | 1        | 0.38%   |
| ARM                      | 1        | 0.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor                                       | 15       | 5.64%   |
| AMD Ryzen 7 2700X Eight-Core Processor                                   | 13       | 4.89%   |
| AMD Ryzen 5 3600 6-Core Processor                                        | 11       | 4.14%   |
| AMD Ryzen 9 3950X 16-Core Processor                                      | 10       | 3.76%   |
| AMD Ryzen 5 5600X 6-Core Processor                                       | 9        | 3.38%   |
| AMD Ryzen 7 3800X 8-Core Processor                                       | 8        | 3.01%   |
| AMD Ryzen 5 2600 Six-Core Processor                                      | 8        | 3.01%   |
| AMD Ryzen 9 5950X 16-Core Processor                                      | 6        | 2.26%   |
| AMD Ryzen 9 3900X 12-Core Processor                                      | 6        | 2.26%   |
| AMD Ryzen 7 2700 Eight-Core Processor                                    | 5        | 1.88%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics                              | 5        | 1.88%   |
| AMD FX-8350 Eight-Core Processor                                         | 5        | 1.88%   |
| Intel Core i9-9900K CPU @ 3.60GHz                                        | 4        | 1.5%    |
| Intel Core i7-8700K CPU @ 3.70GHz                                        | 4        | 1.5%    |
| Intel Core i7-7700K CPU @ 4.20GHz                                        | 4        | 1.5%    |
| Intel Core i7-6700K CPU @ 4.00GHz                                        | 4        | 1.5%    |
| AMD Ryzen 7 1700 Eight-Core Processor                                    | 4        | 1.5%    |
| AMD Ryzen 5 1600 Six-Core Processor                                      | 4        | 1.5%    |
| Intel Pentium III (Katmai)                                               | 3        | 1.13%   |
| Intel Pentium 4 CPU 3.20GHz                                              | 3        | 1.13%   |
| Intel Core i7-6700 CPU @ 3.40GHz                                         | 3        | 1.13%   |
| Intel Core i7-4790K CPU @ 4.00GHz                                        | 3        | 1.13%   |
| AMD Ryzen 9 5900X 12-Core Processor                                      | 3        | 1.13%   |
| AMD Ryzen 7 1700X Eight-Core Processor                                   | 3        | 1.13%   |
| AMD Ryzen 5 1600X Six-Core Processor                                     | 3        | 1.13%   |
| Intel Core i9-10850K CPU @ 3.60GHz                                       | 2        | 0.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz                                         | 2        | 0.75%   |
| Intel Core i7-3770K CPU @ 3.50GHz                                        | 2        | 0.75%   |
| Intel Core i7-10700K CPU @ 3.80GHz                                       | 2        | 0.75%   |
| Intel Core i7 CPU X 980 @ 3.33GHz                                        | 2        | 0.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz                                         | 2        | 0.75%   |
| Intel Core i5-6400 CPU @ 2.70GHz                                         | 2        | 0.75%   |
| Intel Core i5-10600KF CPU @ 4.10GHz                                      | 2        | 0.75%   |
| Intel Core i3-6100 CPU @ 3.70GHz                                         | 2        | 0.75%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz                                    | 2        | 0.75%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz                                    | 2        | 0.75%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz                                     | 2        | 0.75%   |
| Intel 11th Gen Core i5-11600KF @ 3.90GHz                                 | 2        | 0.75%   |
| AMD Sempron 3850 APU with Radeon R3                                      | 2        | 0.75%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics                               | 2        | 0.75%   |
| AMD Ryzen 7 5800X 8-Core Processor                                       | 2        | 0.75%   |
| AMD Ryzen 7 1800X Eight-Core Processor                                   | 2        | 0.75%   |
| AMD Ryzen 5 3600XT 6-Core Processor                                      | 2        | 0.75%   |
| AMD Ryzen 5 3500X 6-Core Processor                                       | 2        | 0.75%   |
| AMD Phenom II X4 970 Processor                                           | 2        | 0.75%   |
| AMD FX-6300 Six-Core Processor                                           | 2        | 0.75%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported                       | 1        | 0.38%   |
| Marvell Semiconductor Marvell Kirkwood (Flattened Device Tree) Processor | 1        | 0.38%   |
| Intel Xeon CPU X5675 @ 3.07GHz                                           | 1        | 0.38%   |
| Intel Xeon CPU X5570 @ 2.93GHz                                           | 1        | 0.38%   |
| Intel Xeon CPU X5470 @ 3.33GHz                                           | 1        | 0.38%   |
| Intel Xeon CPU W3565 @ 3.20GHz                                           | 1        | 0.38%   |
| Intel Xeon CPU E5520 @ 2.27GHz                                           | 1        | 0.38%   |
| Intel Xeon CPU E5502 @ 1.87GHz                                           | 1        | 0.38%   |
| Intel Xeon CPU E5-2695 v4 @ 2.10GHz                                      | 1        | 0.38%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz                                       | 1        | 0.38%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz                                      | 1        | 0.38%   |
| Intel Xeon CPU E3-1285 v4 @ 3.50GHz                                      | 1        | 0.38%   |
| Intel Xeon CPU E3-1275 v6 @ 3.80GHz                                      | 1        | 0.38%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz                                      | 1        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 7            | 52       | 19.7%   |
| AMD Ryzen 5            | 40       | 15.15%  |
| Intel Core i7          | 36       | 13.64%  |
| AMD Ryzen 9            | 25       | 9.47%   |
| Intel Core i5          | 23       | 8.71%   |
| Intel Xeon             | 12       | 4.55%   |
| AMD FX                 | 9        | 3.41%   |
| Intel Core i9          | 7        | 2.65%   |
| Intel Core 2 Quad      | 7        | 2.65%   |
| Other                  | 5        | 1.89%   |
| Intel Core i3          | 5        | 1.89%   |
| AMD Ryzen 3            | 5        | 1.89%   |
| Intel Pentium 4        | 4        | 1.52%   |
| Intel Pentium          | 4        | 1.52%   |
| Intel Core 2 Duo       | 4        | 1.52%   |
| AMD Ryzen Threadripper | 4        | 1.52%   |
| AMD Phenom II X4       | 4        | 1.52%   |
| Intel Pentium III      | 3        | 1.14%   |
| Intel Celeron          | 2        | 0.76%   |
| AMD Sempron            | 2        | 0.76%   |
| AMD Ryzen 7 PRO        | 2        | 0.76%   |
| AMD Phenom II X6       | 2        | 0.76%   |
| AMD Athlon 64 X2       | 2        | 0.76%   |
| Intel Core 2           | 1        | 0.38%   |
| Intel Atom             | 1        | 0.38%   |
| ARM Allwinner          | 1        | 0.38%   |
| AMD Ryzen 5 PRO        | 1        | 0.38%   |
| AMD A10                | 1        | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 76       | 28.79%  |
| 8      | 65       | 24.62%  |
| 6      | 59       | 22.35%  |
| 2      | 19       | 7.2%    |
| 16     | 16       | 6.06%   |
| 12     | 13       | 4.92%   |
| 1      | 8        | 3.03%   |
| 10     | 2        | 0.76%   |
| 3      | 2        | 0.76%   |
| 64     | 1        | 0.38%   |
| 24     | 1        | 0.38%   |
| 18     | 1        | 0.38%   |
| 14     | 1        | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 259      | 98.48%  |
| 2      | 4        | 1.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 196      | 74.24%  |
| 1      | 67       | 25.38%  |
| 4      | 1        | 0.38%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 255      | 96.96%  |
| 32-bit         | 5        | 1.9%    |
| Unknown        | 3        | 1.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 12.73%  |
| 0x08701021 | 31       | 11.27%  |
| 0x0800820d | 25       | 9.09%   |
| 0x08701013 | 21       | 7.64%   |
| 0x506e3    | 15       | 5.45%   |
| 0x0a201009 | 14       | 5.09%   |
| 0x08001138 | 11       | 4%      |
| 0x306c3    | 10       | 3.64%   |
| 0x906e9    | 9        | 3.27%   |
| 0x0a201016 | 8        | 2.91%   |
| 0xa0655    | 7        | 2.55%   |
| 0x306a9    | 7        | 2.55%   |
| 0x1067a    | 7        | 2.55%   |
| 0x906ea    | 5        | 1.82%   |
| 0x906ec    | 4        | 1.45%   |
| 0x206c2    | 4        | 1.45%   |
| 0xa0671    | 3        | 1.09%   |
| 0x673      | 3        | 1.09%   |
| 0x206a7    | 3        | 1.09%   |
| 0x106a5    | 3        | 1.09%   |
| 0x0810100b | 3        | 1.09%   |
| 0xf43      | 2        | 0.73%   |
| 0x906ed    | 2        | 0.73%   |
| 0x306e4    | 2        | 0.73%   |
| 0x08600106 | 2        | 0.73%   |
| 0x08301039 | 2        | 0.73%   |
| 0x08101013 | 2        | 0.73%   |
| 0x08008206 | 2        | 0.73%   |
| 0x08001129 | 2        | 0.73%   |
| 0x0700010f | 2        | 0.73%   |
| 0x06000852 | 2        | 0.73%   |
| 0x06000822 | 2        | 0.73%   |
| 0x010000c8 | 2        | 0.73%   |
| 0xf29      | 1        | 0.36%   |
| 0xa0653    | 1        | 0.36%   |
| 0x806ec    | 1        | 0.36%   |
| 0x6fd      | 1        | 0.36%   |
| 0x6fb      | 1        | 0.36%   |
| 0x6f6      | 1        | 0.36%   |
| 0x506c9    | 1        | 0.36%   |
| 0x50654    | 1        | 0.36%   |
| 0x406f1    | 1        | 0.36%   |
| 0x406c3    | 1        | 0.36%   |
| 0x40671    | 1        | 0.36%   |
| 0x206d7    | 1        | 0.36%   |
| 0x106e5    | 1        | 0.36%   |
| 0x10677    | 1        | 0.36%   |
| 0x08108102 | 1        | 0.36%   |
| 0x0800820b | 1        | 0.36%   |
| 0x0800111c | 1        | 0.36%   |
| 0x0600081f | 1        | 0.36%   |
| 0x06000817 | 1        | 0.36%   |
| 0x06000803 | 1        | 0.36%   |
| 0x010000db | 1        | 0.36%   |
| 0x010000bf | 1        | 0.36%   |
| 0x00000000 | 1        | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 61       | 22.93%  |
| Zen+        | 30       | 11.28%  |
| KabyLake    | 24       | 9.02%   |
| Zen 3       | 20       | 7.52%   |
| Zen         | 20       | 7.52%   |
| Skylake     | 17       | 6.39%   |
| Haswell     | 11       | 4.14%   |
| Piledriver  | 9        | 3.38%   |
| Penryn      | 9        | 3.38%   |
| IvyBridge   | 9        | 3.38%   |
| CometLake   | 8        | 3.01%   |
| Nehalem     | 6        | 2.26%   |
| K10         | 6        | 2.26%   |
| Unknown     | 6        | 2.26%   |
| SandyBridge | 5        | 1.88%   |
| Westmere    | 4        | 1.5%    |
| NetBurst    | 4        | 1.5%    |
| Core        | 4        | 1.5%    |
| P6          | 3        | 1.13%   |
| K8 Hammer   | 2        | 0.75%   |
| Jaguar      | 2        | 0.75%   |
| Broadwell   | 2        | 0.75%   |
| Silvermont  | 1        | 0.38%   |
| Goldmont    | 1        | 0.38%   |
| Bulldozer   | 1        | 0.38%   |
| Bonnell     | 1        | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 130      | 46.59%  |
| Nvidia                     | 109      | 39.07%  |
| Intel                      | 36       | 12.9%   |
| Matrox Electronics Systems | 2        | 0.72%   |
| ASPEED Technology          | 2        | 0.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 37       | 12.63%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 20       | 6.83%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 14       | 4.78%   |
| Intel HD Graphics 530                                                       | 9        | 3.07%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 6        | 2.05%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 6        | 2.05%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 2.05%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 2.05%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 5        | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 1.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.71%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 4        | 1.37%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.37%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.37%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 1.37%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 1.37%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.37%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1.02%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 1.02%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 3        | 1.02%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.02%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.02%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 3        | 1.02%   |
| Intel HD Graphics 630                                                       | 3        | 1.02%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.02%   |
| AMD RS880 [Radeon HD 4290]                                                  | 3        | 1.02%   |
| AMD Renoir                                                                  | 3        | 1.02%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 1.02%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1.02%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.68%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.68%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.68%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.68%   |
| Nvidia NV5 [Riva TNT2 Model 64 / Model 64 Pro]                              | 2        | 0.68%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 0.68%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 0.68%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 2        | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.68%   |
| Nvidia GK107 [GeForce GT 740]                                               | 2        | 0.68%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 2        | 0.68%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 2        | 0.68%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 2        | 0.68%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 0.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 0.68%   |
| ASPEED Technology ASPEED Graphics Family                                    | 2        | 0.68%   |
| AMD Vega 20 [Radeon VII]                                                    | 2        | 0.68%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2        | 0.68%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 2        | 0.68%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                   | 2        | 0.68%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 0.68%   |
| AMD Kabini [Radeon HD 8280 / R3 Series]                                     | 2        | 0.68%   |
| AMD Ellesmere [Radeon Pro WX 7100]                                          | 2        | 0.68%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 0.68%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2        | 0.68%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 2        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.34%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.34%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.34%   |
| Nvidia TU104GL [Quadro RTX 4000]                                            | 1        | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x AMD                  | 115      | 43.23%  |
| 1 x Nvidia               | 95       | 35.71%  |
| 1 x Intel                | 28       | 10.53%  |
| AMD + Nvidia             | 6        | 2.26%   |
| Other                    | 5        | 1.88%   |
| 2 x AMD                  | 5        | 1.88%   |
| 2 x Nvidia               | 3        | 1.13%   |
| Intel + Nvidia           | 3        | 1.13%   |
| Nvidia + Matrox          | 1        | 0.38%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.38%   |
| Intel + AMD              | 1        | 0.38%   |
| 1 x ASPEED               | 1        | 0.38%   |
| AMD + Matrox             | 1        | 0.38%   |
| AMD + ASPEED             | 1        | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 170      | 63.67%  |
| Proprietary | 80       | 29.96%  |
| Unknown     | 17       | 6.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 73       | 26.26%  |
| 7.01-8.0   | 72       | 25.9%   |
| 3.01-4.0   | 29       | 10.43%  |
| 1.01-2.0   | 29       | 10.43%  |
| 0.01-0.5   | 24       | 8.63%   |
| 5.01-6.0   | 15       | 5.4%    |
| 0.51-1.0   | 14       | 5.04%   |
| 8.01-16.0  | 12       | 4.32%   |
| 2.01-3.0   | 7        | 2.52%   |
| 16.01-24.0 | 3        | 1.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 39       | 12.79%  |
| Dell                    | 38       | 12.46%  |
| Goldstar                | 37       | 12.13%  |
| BenQ                    | 21       | 6.89%   |
| AOC                     | 18       | 5.9%    |
| Iiyama                  | 17       | 5.57%   |
| Hewlett-Packard         | 17       | 5.57%   |
| Ancor Communications    | 17       | 5.57%   |
| Acer                    | 11       | 3.61%   |
| Philips                 | 10       | 3.28%   |
| ViewSonic               | 9        | 2.95%   |
| Lenovo                  | 7        | 2.3%    |
| ASUSTek Computer        | 7        | 2.3%    |
| Fujitsu Siemens         | 6        | 1.97%   |
| MSI                     | 5        | 1.64%   |
| Idek Iiyama             | 4        | 1.31%   |
| Eizo                    | 4        | 1.31%   |
| Unknown                 | 3        | 0.98%   |
| LG Electronics          | 3        | 0.98%   |
| Envision Peripherals    | 3        | 0.98%   |
| NEC Computers           | 2        | 0.66%   |
| Gigabyte Technology     | 2        | 0.66%   |
| AUS                     | 2        | 0.66%   |
| Apple                   | 2        | 0.66%   |
| Yamaha                  | 1        | 0.33%   |
| Vizio                   | 1        | 0.33%   |
| Vestel Elektronik       | 1        | 0.33%   |
| Sunplus                 | 1        | 0.33%   |
| Sony                    | 1        | 0.33%   |
| RTK                     | 1        | 0.33%   |
| PNP                     | 1        | 0.33%   |
| PKB                     | 1        | 0.33%   |
| Panasonic               | 1        | 0.33%   |
| Packard Bell            | 1        | 0.33%   |
| Lenovo Group Limited    | 1        | 0.33%   |
| KTC                     | 1        | 0.33%   |
| Impression              | 1        | 0.33%   |
| HVR                     | 1        | 0.33%   |
| HJW                     | 1        | 0.33%   |
| HannStar Display        | 1        | 0.33%   |
| HannStar                | 1        | 0.33%   |
| FUN                     | 1        | 0.33%   |
| Chimei Innolux          | 1        | 0.33%   |
| Chi Mei Optoelectronics | 1        | 0.33%   |
| BBY                     | 1        | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Iiyama PL2473HD IVM6107 1920x1080 520x290mm 23.4-inch                  | 4        | 1.2%    |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                  | 4        | 1.2%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch               | 4        | 1.2%    |
| Goldstar Ultra HD GSM5B09 3780x2160 600x340mm 27.2-inch                | 4        | 1.2%    |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 4        | 1.2%    |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 520x320mm 24.0-inch       | 4        | 1.2%    |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                      | 4        | 1.2%    |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 3        | 0.9%    |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch               | 3        | 0.9%    |
| Envision Peripherals LCD2361 ENV2361 1920x1080 521x293mm 23.5-inch     | 3        | 0.9%    |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                     | 3        | 0.9%    |
| BenQ LCD BNQ801E 3840x2160 596x335mm 26.9-inch                         | 3        | 0.9%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 2        | 0.6%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 2        | 0.6%    |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch      | 2        | 0.6%    |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 700x390mm 31.5-inch  | 2        | 0.6%    |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 2        | 0.6%    |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch     | 2        | 0.6%    |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch     | 2        | 0.6%    |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch               | 2        | 0.6%    |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                     | 2        | 0.6%    |
| MSI G273Q MSI3CA8 2560x1440 597x336mm 27.0-inch                        | 2        | 0.6%    |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                   | 2        | 0.6%    |
| Idek Iiyama LCD Monitor PLE2607WS                                      | 2        | 0.6%    |
| Hewlett-Packard LA1951 HWP285B 1280x1024 380x300mm 19.1-inch           | 2        | 0.6%    |
| Goldstar 27MB85Z GSM5A72 2560x1440 597x336mm 27.0-inch                 | 2        | 0.6%    |
| Fujitsu Siemens P24W-5 ECO FUS06A7 1920x1200 518x324mm 24.1-inch       | 2        | 0.6%    |
| Dell U2720Q DEL41B3 3840x2160 600x340mm 27.2-inch                      | 2        | 0.6%    |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                      | 2        | 0.6%    |
| BenQ E2200HD BNQ790C 1920x1080 477x268mm 21.5-inch                     | 2        | 0.6%    |
| AOC 24E1W1 AOC2401 1920x1080 527x296mm 23.8-inch                       | 2        | 0.6%    |
| AOC 2473W1M AOC2473 1920x1080 527x296mm 23.8-inch                      | 2        | 0.6%    |
| AOC 2369 AOC2369 1920x1080 509x286mm 23.0-inch                         | 2        | 0.6%    |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch       | 2        | 0.6%    |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 600x340mm 27.2-inch  | 2        | 0.6%    |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 0.6%    |
| Ancor Communications ASUS PB238 ACI23A2 1920x1080 509x286mm 23.0-inch  | 2        | 0.6%    |
| Yamaha HTR-6064 YMH3169 1920x540                                       | 1        | 0.3%    |
| Vizio D43n-E1 VIZ1009 1920x1080 953x543mm 43.2-inch                    | 1        | 0.3%    |
| ViewSonic VX700 VSC6206 1280x1024 337x270mm 17.0-inch                  | 1        | 0.3%    |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1        | 0.3%    |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch             | 1        | 0.3%    |
| ViewSonic VX2458 Series VSC36AF 1920x1080 521x293mm 23.5-inch          | 1        | 0.3%    |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch          | 1        | 0.3%    |
| ViewSonic VP2770 SERIES VSC832B 2560x1440 597x336mm 27.0-inch          | 1        | 0.3%    |
| ViewSonic VG3448 VSC0D38 3440x1440 800x330mm 34.1-inch                 | 1        | 0.3%    |
| ViewSonic VG2249 Series VSCF232 1920x1080 476x268mm 21.5-inch          | 1        | 0.3%    |
| ViewSonic VA2710-FHD VSCA736 1920x1080 598x336mm 27.0-inch             | 1        | 0.3%    |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch   | 1        | 0.3%    |
| Unknown LCD Monitor XMI Mi Monitor 3440x1440                           | 1        | 0.3%    |
| Unknown LCD Monitor Impression *22W1*                                  | 1        | 0.3%    |
| Unknown LCD Monitor GBT G27Q 2560x1440                                 | 1        | 0.3%    |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch               | 1        | 0.3%    |
| Sony LCD Monitor TV  *00 3840x2160                                     | 1        | 0.3%    |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch      | 1        | 0.3%    |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch      | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM0584 2048x1152 510x287mm 23.0-inch   | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM056A 1680x1050 470x300mm 22.0-inch   | 1        | 0.3%    |
| Samsung Electronics SyncMaster SAM02D9 1680x1050 433x271mm 20.1-inch   | 1        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 118      | 39.2%   |
| 2560x1440 (QHD)    | 42       | 13.95%  |
| 3840x2160 (4K)     | 37       | 12.29%  |
| 1920x1200 (WUXGA)  | 20       | 6.64%   |
| 3440x1440          | 17       | 5.65%   |
| 1280x1024 (SXGA)   | 13       | 4.32%   |
| 1680x1050 (WSXGA+) | 9        | 2.99%   |
| 3840x1080          | 7        | 2.33%   |
| 2560x1080          | 7        | 2.33%   |
| Unknown            | 7        | 2.33%   |
| 1600x900 (HD+)     | 6        | 1.99%   |
| 1440x900 (WXGA+)   | 3        | 1%      |
| 3840x1200          | 2        | 0.66%   |
| 1600x1200          | 2        | 0.66%   |
| 1366x768 (WXGA)    | 2        | 0.66%   |
| 1280x960           | 2        | 0.66%   |
| 4880x1080          | 1        | 0.33%   |
| 3926x1440          | 1        | 0.33%   |
| 3600x1080          | 1        | 0.33%   |
| 2160x1200          | 1        | 0.33%   |
| 2048x1152          | 1        | 0.33%   |
| 1920x540           | 1        | 0.33%   |
| 1400x1050          | 1        | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 60       | 19.87%  |
| 24      | 57       | 18.87%  |
| 23      | 46       | 15.23%  |
| Unknown | 31       | 10.26%  |
| 21      | 22       | 7.28%   |
| 34      | 18       | 5.96%   |
| 19      | 13       | 4.3%    |
| 31      | 7        | 2.32%   |
| 20      | 7        | 2.32%   |
| 17      | 6        | 1.99%   |
| 48      | 5        | 1.66%   |
| 25      | 5        | 1.66%   |
| 22      | 5        | 1.66%   |
| 32      | 4        | 1.32%   |
| 84      | 3        | 0.99%   |
| 49      | 2        | 0.66%   |
| 47      | 2        | 0.66%   |
| 18      | 2        | 0.66%   |
| 54      | 1        | 0.33%   |
| 43      | 1        | 0.33%   |
| 40      | 1        | 0.33%   |
| 33      | 1        | 0.33%   |
| 26      | 1        | 0.33%   |
| 14      | 1        | 0.33%   |
| 11      | 1        | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 142      | 50%     |
| 401-500     | 39       | 13.73%  |
| Unknown     | 31       | 10.92%  |
| 701-800     | 23       | 8.1%    |
| 601-700     | 17       | 5.99%   |
| 1001-1500   | 10       | 3.52%   |
| 351-400     | 9        | 3.17%   |
| 301-350     | 7        | 2.46%   |
| 1501-2000   | 3        | 1.06%   |
| 801-900     | 1        | 0.35%   |
| 201-300     | 1        | 0.35%   |
| 901-1000    | 1        | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 167      | 61.17%  |
| 16/10   | 37       | 13.55%  |
| Unknown | 28       | 10.26%  |
| 21/9    | 18       | 6.59%   |
| 5/4     | 13       | 4.76%   |
| 32/9    | 7        | 2.56%   |
| 4/3     | 2        | 0.73%   |
| 6/5     | 1        | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 95       | 32.09%  |
| 301-350        | 60       | 20.27%  |
| 251-300        | 31       | 10.47%  |
| Unknown        | 31       | 10.47%  |
| 351-500        | 30       | 10.14%  |
| 151-200        | 24       | 8.11%   |
| 501-1000       | 10       | 3.38%   |
| 141-150        | 8        | 2.7%    |
| More than 1000 | 5        | 1.69%   |
| 81-90          | 1        | 0.34%   |
| 51-60          | 1        | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 147      | 52.5%   |
| 101-120 | 62       | 22.14%  |
| Unknown | 31       | 11.07%  |
| 121-160 | 21       | 7.5%    |
| 161-240 | 13       | 4.64%   |
| 1-50    | 6        | 2.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 180      | 65.69%  |
| 2     | 61       | 22.26%  |
| 0     | 24       | 8.76%   |
| 3     | 7        | 2.55%   |
| 4     | 2        | 0.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 155      | 43.06%  |
| Realtek Semiconductor           | 125      | 34.72%  |
| Qualcomm Atheros                | 21       | 5.83%   |
| Broadcom                        | 15       | 4.17%   |
| Aquantia                        | 7        | 1.94%   |
| Marvell Technology Group        | 6        | 1.67%   |
| ASIX Electronics                | 5        | 1.39%   |
| TP-Link                         | 4        | 1.11%   |
| Nvidia                          | 3        | 0.83%   |
| Qualcomm Atheros Communications | 2        | 0.56%   |
| Netchip Technology              | 2        | 0.56%   |
| D-Link                          | 2        | 0.56%   |
| 3Com                            | 2        | 0.56%   |
| Texas Instruments               | 1        | 0.28%   |
| Ralink Technology               | 1        | 0.28%   |
| Ralink                          | 1        | 0.28%   |
| QLogic                          | 1        | 0.28%   |
| Pulse-Eight                     | 1        | 0.28%   |
| Metrologic Instruments          | 1        | 0.28%   |
| MediaTek                        | 1        | 0.28%   |
| Kyocera                         | 1        | 0.28%   |
| InterBiometrics                 | 1        | 0.28%   |
| Davicom Semiconductor           | 1        | 0.28%   |
| D-Link System                   | 1        | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 102      | 23.78%  |
| Intel I211 Gigabit Network Connection                                         | 57       | 13.29%  |
| Intel Wi-Fi 6 AX200                                                           | 31       | 7.23%   |
| Realtek RTL8125 2.5GbE Controller                                             | 17       | 3.96%   |
| Intel Ethernet Connection (2) I219-V                                          | 14       | 3.26%   |
| Intel Ethernet Controller I225-V                                              | 12       | 2.8%    |
| Intel 82574L Gigabit Network Connection                                       | 9        | 2.1%    |
| Intel Ethernet Connection (7) I219-V                                          | 7        | 1.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 6        | 1.4%    |
| Intel Wireless-AC 9260                                                        | 5        | 1.17%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.17%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5        | 1.17%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 5        | 1.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 4        | 0.93%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 4        | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4        | 0.93%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 4        | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 4        | 0.93%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 0.93%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 4        | 0.93%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3        | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 0.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 3        | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 3        | 0.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 3        | 0.7%    |
| Intel Wireless 8260                                                           | 3        | 0.7%    |
| Intel Wireless 7260                                                           | 3        | 0.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                                | 3        | 0.7%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3        | 0.7%    |
| Intel I350 Gigabit Network Connection                                         | 3        | 0.7%    |
| Intel I210 Gigabit Network Connection                                         | 3        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 3        | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.7%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 2        | 0.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 2        | 0.47%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.47%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 0.47%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 2        | 0.47%   |
| Nvidia MCP77 Ethernet                                                         | 2        | 0.47%   |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                                | 2        | 0.47%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 2        | 0.47%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 0.47%   |
| Intel Ethernet Connection (11) I219-V                                         | 2        | 0.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 0.47%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.47%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 2        | 0.47%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.47%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 2        | 0.47%   |
| ASIX AX88772                                                                  | 2        | 0.47%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 1        | 0.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.23%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1        | 0.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 0.23%   |
| Realtek RTL-8029(AS)                                                          | 1        | 0.23%   |
| Ralink MT7601U Wireless Adapter                                               | 1        | 0.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 64       | 59.26%  |
| Qualcomm Atheros                | 17       | 15.74%  |
| Realtek Semiconductor           | 8        | 7.41%   |
| Broadcom                        | 8        | 7.41%   |
| TP-Link                         | 4        | 3.7%    |
| Qualcomm Atheros Communications | 2        | 1.85%   |
| D-Link                          | 2        | 1.85%   |
| Texas Instruments               | 1        | 0.93%   |
| Ralink Technology               | 1        | 0.93%   |
| Ralink                          | 1        | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 31       | 28.44%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6        | 5.5%    |
| Intel Wireless-AC 9260                                         | 5        | 4.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 4        | 3.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4        | 3.67%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 4        | 3.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4        | 3.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4        | 3.67%   |
| Intel Wireless 8260                                            | 3        | 2.75%   |
| Intel Wireless 7260                                            | 3        | 2.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3        | 2.75%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection       | 3        | 2.75%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3        | 2.75%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2        | 1.83%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2        | 1.83%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2        | 1.83%   |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 1.83%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 2        | 1.83%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2        | 1.83%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 0.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 0.92%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface            | 1        | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 0.92%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 0.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 0.92%   |
| Ralink MT7601U Wireless Adapter                                | 1        | 0.92%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                           | 1        | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 0.92%   |
| Intel Wireless Gigabit 17265                                   | 1        | 0.92%   |
| Intel Wireless 3165                                            | 1        | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 0.92%   |
| D-Link DWL-G132 [Atheros AR5523]                               | 1        | 0.92%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]  | 1        | 0.92%   |
| Broadcom Network controller                                    | 1        | 0.92%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1        | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 130      | 44.22%  |
| Realtek Semiconductor    | 125      | 42.52%  |
| Broadcom                 | 7        | 2.38%   |
| Aquantia                 | 7        | 2.38%   |
| Marvell Technology Group | 6        | 2.04%   |
| Qualcomm Atheros         | 5        | 1.7%    |
| ASIX Electronics         | 5        | 1.7%    |
| Nvidia                   | 3        | 1.02%   |
| 3Com                     | 2        | 0.68%   |
| QLogic                   | 1        | 0.34%   |
| MediaTek                 | 1        | 0.34%   |
| Davicom Semiconductor    | 1        | 0.34%   |
| D-Link System            | 1        | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 102      | 32.48%  |
| Intel I211 Gigabit Network Connection                                         | 57       | 18.15%  |
| Realtek RTL8125 2.5GbE Controller                                             | 17       | 5.41%   |
| Intel Ethernet Connection (2) I219-V                                          | 14       | 4.46%   |
| Intel Ethernet Controller I225-V                                              | 12       | 3.82%   |
| Intel 82574L Gigabit Network Connection                                       | 9        | 2.87%   |
| Intel Ethernet Connection (7) I219-V                                          | 7        | 2.23%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.59%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5        | 1.59%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 5        | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 4        | 1.27%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 1.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3        | 0.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 0.96%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 3        | 0.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 3        | 0.96%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 3        | 0.96%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 0.96%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 0.96%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.96%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 0.64%   |
| Nvidia MCP77 Ethernet                                                         | 2        | 0.64%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 2        | 0.64%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 0.64%   |
| Intel Ethernet Connection (11) I219-V                                         | 2        | 0.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 0.64%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.64%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 2        | 0.64%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 0.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.64%   |
| ASIX AX88772                                                                  | 2        | 0.64%   |
| Realtek RTL-8029(AS)                                                          | 1        | 0.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.32%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.32%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 0.32%   |
| MediaTek NOA N2                                                               | 1        | 0.32%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1        | 0.32%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1        | 0.32%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.32%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.32%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 0.32%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.32%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 0.32%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.32%   |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1        | 0.32%   |
| Davicom DM9621A USB To FastEther                                              | 1        | 0.32%   |
| D-Link System RTL8139 Ethernet                                                | 1        | 0.32%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 0.32%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1        | 0.32%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                                   | 1        | 0.32%   |
| ASIX AX88772B Fast Ethernet Controller                                        | 1        | 0.32%   |
| ASIX AX88772B                                                                 | 1        | 0.32%   |
| ASIX AX88178A                                                                 | 1        | 0.32%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 0.32%   |
| Aquantia AQC108 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 0.32%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                               | 1        | 0.32%   |
| 3Com 3c900B-Combo Etherlink XL [Cyclone]                                      | 1        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 258      | 70.68%  |
| WiFi     | 101      | 27.67%  |
| Modem    | 6        | 1.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 227      | 78.82%  |
| WiFi     | 61       | 21.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 143      | 52.96%  |
| 2     | 90       | 33.33%  |
| 3     | 21       | 7.78%   |
| 4     | 6        | 2.22%   |
| 5     | 4        | 1.48%   |
| 0     | 4        | 1.48%   |
| 9     | 1        | 0.37%   |
| 6     | 1        | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 238      | 89.14%  |
| Yes  | 29       | 10.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 64       | 60.95%  |
| Cambridge Silicon Radio         | 21       | 20%     |
| ASUSTek Computer                | 5        | 4.76%   |
| Realtek Semiconductor           | 4        | 3.81%   |
| Broadcom                        | 4        | 3.81%   |
| Apple                           | 4        | 3.81%   |
| Qualcomm Atheros Communications | 1        | 0.95%   |
| HTC (High Tech Computer)        | 1        | 0.95%   |
| Belkin Components               | 1        | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 36       | 34.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 21       | 20%     |
| Intel Wireless-AC 3168 Bluetooth                                     | 6        | 5.71%   |
| Intel Bluetooth wireless interface                                   | 6        | 5.71%   |
| Intel Bluetooth Device                                               | 6        | 5.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 5        | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4        | 3.81%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 4        | 3.81%   |
| Realtek Bluetooth Radio                                              | 3        | 2.86%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle                   | 2        | 1.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 1.9%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 2        | 1.9%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.95%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 0.95%   |
| Intel AX210 Bluetooth                                                | 1        | 0.95%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.95%   |
| Belkin Components Bluetooth Device with trace filter                 | 1        | 0.95%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.95%   |
| Apple Bluetooth USB Host Controller                                  | 1        | 0.95%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 167      | 35.76%  |
| Nvidia                               | 96       | 20.56%  |
| Intel                                | 92       | 19.7%   |
| C-Media Electronics                  | 21       | 4.5%    |
| Logitech                             | 11       | 2.36%   |
| Creative Labs                        | 11       | 2.36%   |
| Texas Instruments                    | 6        | 1.28%   |
| Creative Technology                  | 6        | 1.28%   |
| Kingston Technology                  | 5        | 1.07%   |
| Razer USA                            | 4        | 0.86%   |
| Focusrite-Novation                   | 4        | 0.86%   |
| BEHRINGER International              | 4        | 0.86%   |
| JMTek                                | 3        | 0.64%   |
| ASUSTek Computer                     | 3        | 0.64%   |
| SteelSeries ApS                      | 2        | 0.43%   |
| Sennheiser Communications            | 2        | 0.43%   |
| SAVITECH                             | 2        | 0.43%   |
| RODE Microphones                     | 2        | 0.43%   |
| GYROCOM C&C                          | 2        | 0.43%   |
| GN Netcom                            | 2        | 0.43%   |
| AudioQuest                           | 2        | 0.43%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.21%   |
| Syntek                               | 1        | 0.21%   |
| Solid State Logic                    | 1        | 0.21%   |
| Samson Technologies                  | 1        | 0.21%   |
| Realtek Semiconductor                | 1        | 0.21%   |
| QinHeng Electronics                  | 1        | 0.21%   |
| Plantronics                          | 1        | 0.21%   |
| Nektar                               | 1        | 0.21%   |
| Microsoft                            | 1        | 0.21%   |
| Micronas                             | 1        | 0.21%   |
| JOUNIVO                              | 1        | 0.21%   |
| Generalplus Technology               | 1        | 0.21%   |
| FiiO Electronics Technology          | 1        | 0.21%   |
| Ensoniq                              | 1        | 0.21%   |
| Elgato Systems                       | 1        | 0.21%   |
| Dell                                 | 1        | 0.21%   |
| Cirrus Logic                         | 1        | 0.21%   |
| Blue Microphones                     | 1        | 0.21%   |
| Aureal Semiconductor                 | 1        | 0.21%   |
| Antlion Audio                        | 1        | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 71       | 12.22%  |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 41       | 7.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 39       | 6.71%   |
| AMD Navi 10 HDMI Audio                                                            | 23       | 3.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 16       | 2.75%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 14       | 2.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 12       | 2.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 10       | 1.72%   |
| Intel 200 Series PCH HD Audio                                                     | 10       | 1.72%   |
| AMD Family 17h/19h HD Audio Controller                                            | 9        | 1.55%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 9        | 1.55%   |
| Nvidia GP104 High Definition Audio Controller                                     | 8        | 1.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8        | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                                     | 7        | 1.2%    |
| Nvidia TU104 HD Audio Controller                                                  | 7        | 1.2%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 7        | 1.2%    |
| Intel Cannon Lake PCH cAVS                                                        | 7        | 1.2%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 7        | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                                     | 6        | 1.03%   |
| Nvidia GP102 HDMI Audio Controller                                                | 6        | 1.03%   |
| Nvidia GM206 High Definition Audio Controller                                     | 6        | 1.03%   |
| Nvidia GM204 High Definition Audio Controller                                     | 6        | 1.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6        | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 6        | 1.03%   |
| Nvidia TU106 High Definition Audio Controller                                     | 5        | 0.86%   |
| Nvidia GA102 High Definition Audio Controller                                     | 5        | 0.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 5        | 0.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5        | 0.86%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 5        | 0.86%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 5        | 0.86%   |
| Texas Instruments PCM2902 Audio Codec                                             | 4        | 0.69%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 0.69%   |
| Intel Comet Lake PCH cAVS                                                         | 4        | 0.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 0.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 0.69%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 4        | 0.69%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 4        | 0.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 0.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3        | 0.52%   |
| Nvidia High Definition Audio Controller                                           | 3        | 0.52%   |
| Nvidia GK106 HDMI Audio Controller                                                | 3        | 0.52%   |
| Nvidia GA104 High Definition Audio Controller                                     | 3        | 0.52%   |
| Logitech USB Headset                                                              | 3        | 0.52%   |
| Kingston Technology HyperX 7.1 Audio                                              | 3        | 0.52%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 0.52%   |
| Intel Comet Lake PCH-V cAVS                                                       | 3        | 0.52%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 3        | 0.52%   |
| Creative Technology Sound Blaster Premium HD [SBX]                                | 3        | 0.52%   |
| C-Media Electronics USB Audio Device                                              | 3        | 0.52%   |
| C-Media Electronics CM108 Audio Controller                                        | 3        | 0.52%   |
| BEHRINGER International UMC202HD 192k                                             | 3        | 0.52%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 3        | 0.52%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 3        | 0.52%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 3        | 0.52%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 0.52%   |
| AMD FCH Azalia Controller                                                         | 3        | 0.52%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 0.52%   |
| SteelSeries ApS SteelSeries Arctis 7                                              | 2        | 0.34%   |
| SAVITECH SA9023 audio controller                                                  | 2        | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 54       | 19.64%  |
| Kingston            | 53       | 19.27%  |
| Corsair             | 45       | 16.36%  |
| Unknown             | 33       | 12%     |
| Crucial             | 32       | 11.64%  |
| Samsung Electronics | 12       | 4.36%   |
| SK Hynix            | 10       | 3.64%   |
| Micron Technology   | 6        | 2.18%   |
| Team                | 5        | 1.82%   |
| Patriot             | 5        | 1.82%   |
| Nanya Technology    | 3        | 1.09%   |
| GOODRAM             | 3        | 1.09%   |
| A-DATA Technology   | 3        | 1.09%   |
| Transcend           | 1        | 0.36%   |
| T-FORCE             | 1        | 0.36%   |
| Ramaxel Technology  | 1        | 0.36%   |
| Kllisre             | 1        | 0.36%   |
| Klevv               | 1        | 0.36%   |
| Golden Empire       | 1        | 0.36%   |
| GeIL                | 1        | 0.36%   |
| Exceleram           | 1        | 0.36%   |
| Chun Well           | 1        | 0.36%   |
| AMD                 | 1        | 0.36%   |
| A Force             | 1        | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 6        | 2.02%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 6        | 2.02%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 5        | 1.68%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s    | 5        | 1.68%   |
| Unknown RAM Module 512MB DIMM SDRAM                       | 3        | 1.01%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 3        | 1.01%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 3        | 1.01%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 2667MT/s       | 3        | 1.01%   |
| Kingston RAM 9965745-002.A00G 16384MB DIMM DDR4 3600MT/s  | 3        | 1.01%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s    | 3        | 1.01%   |
| G.Skill RAM F4-3200C16-16GTZ 16384MB DIMM DDR4 2933MT/s   | 3        | 1.01%   |
| G.Skill RAM F4-3200C14-8GTZ 8192MB DIMM DDR4 3733MT/s     | 3        | 1.01%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 3        | 1.01%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s      | 3        | 1.01%   |
| Crucial RAM CT4G4DFS8213.C8FAD11 4GB DIMM DDR4 2133MT/s   | 3        | 1.01%   |
| Corsair RAM CMK32GX4M2B3000C15 16384MB DIMM DDR4 3000MT/s | 3        | 1.01%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s    | 3        | 1.01%   |
| Unknown RAM Module 4096MB DIMM                            | 2        | 0.67%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s     | 2        | 0.67%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s       | 2        | 0.67%   |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s      | 2        | 0.67%   |
| Samsung RAM Module 4GB DIMM DDR3 1066MT/s                 | 2        | 0.67%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s        | 2        | 0.67%   |
| Nanya RAM M2F4G64CB88B7N-DI 4GB DIMM DDR3 1600MT/s        | 2        | 0.67%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                 | 2        | 0.67%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s     | 2        | 0.67%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s     | 2        | 0.67%   |
| Kingston RAM 9905625-066.A00G 16GB DIMM DDR4 2667MT/s     | 2        | 0.67%   |
| GOODRAM RAM GR1600D364L11/2G 2GB DIMM DDR3 1333MT/s       | 2        | 0.67%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 2        | 0.67%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s    | 2        | 0.67%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s       | 2        | 0.67%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s        | 2        | 0.67%   |
| G.Skill RAM F4-3200C14-16GVK 16GB DIMM DDR4 3200MT/s      | 2        | 0.67%   |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3000MT/s     | 2        | 0.67%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s     | 2        | 0.67%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s     | 2        | 0.67%   |
| Crucial RAM BLS8G4D26BFSCK.8FD 8GB DIMM DDR4 2400MT/s     | 2        | 0.67%   |
| Crucial RAM BLS16G4D32AESB.M16FE 16GB DIMM DDR4 3800MT/s  | 2        | 0.67%   |
| Crucial RAM BL16G32C16U4B.M16FE 16GB DIMM DDR4 3200MT/s   | 2        | 0.67%   |
| Corsair RAM CMW32GX4M2C3200C16 16384MB DIMM DDR4 3200MT/s | 2        | 0.67%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s    | 2        | 0.67%   |
| Corsair RAM CMK32GX4M2A2400C16 16GB DIMM DDR4 2400MT/s    | 2        | 0.67%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 2        | 0.67%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 2        | 0.67%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s     | 2        | 0.67%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s     | 2        | 0.67%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3200MT/s              | 2        | 0.67%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1333MT/s            | 1        | 0.34%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s              | 1        | 0.34%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                   | 1        | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                  | 1        | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR2 667MT/s                  | 1        | 0.34%   |
| Unknown RAM Module 4GB DIMM 400MT/s                       | 1        | 0.34%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 0.34%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s               | 1        | 0.34%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1        | 0.34%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s               | 1        | 0.34%   |
| Unknown RAM Module 32GB DIMM DDR4 2666MT/s                | 1        | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                  | 1        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 175      | 69.72%  |
| DDR3    | 48       | 19.12%  |
| DDR2    | 11       | 4.38%   |
| Unknown | 9        | 3.59%   |
| SDRAM   | 6        | 2.39%   |
| DDR     | 2        | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 245      | 98%     |
| SODIMM | 4        | 1.6%    |
| RIMM   | 1        | 0.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 96       | 35.16%  |
| 16384 | 93       | 34.07%  |
| 4096  | 36       | 13.19%  |
| 32768 | 19       | 6.96%   |
| 2048  | 19       | 6.96%   |
| 1024  | 7        | 2.56%   |
| 512   | 3        | 1.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 39       | 14.18%  |
| 3200    | 39       | 14.18%  |
| 1600    | 30       | 10.91%  |
| 2400    | 18       | 6.55%   |
| 1333    | 17       | 6.18%   |
| 3000    | 16       | 5.82%   |
| 2133    | 14       | 5.09%   |
| 3733    | 11       | 4%      |
| 2667    | 11       | 4%      |
| 800     | 10       | 3.64%   |
| 3466    | 9        | 3.27%   |
| 667     | 8        | 2.91%   |
| 2933    | 6        | 2.18%   |
| Unknown | 6        | 2.18%   |
| 3400    | 5        | 1.82%   |
| 2666    | 5        | 1.82%   |
| 3800    | 4        | 1.45%   |
| 3333    | 3        | 1.09%   |
| 3100    | 3        | 1.09%   |
| 1066    | 3        | 1.09%   |
| 4000    | 2        | 0.73%   |
| 3866    | 2        | 0.73%   |
| 3066    | 2        | 0.73%   |
| 2465    | 2        | 0.73%   |
| 1866    | 2        | 0.73%   |
| 400     | 2        | 0.73%   |
| 3666    | 1        | 0.36%   |
| 3467    | 1        | 0.36%   |
| 2800    | 1        | 0.36%   |
| 2134    | 1        | 0.36%   |
| 1867    | 1        | 0.36%   |
| 1800    | 1        | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 5        | 83.33%  |
| Brother Industries | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| HP PhotoSmart 130   | 1        | 16.67%  |
| HP LaserJet M14-M17 | 1        | 16.67%  |
| HP LaserJet 1020    | 1        | 16.67%  |
| HP LaserJet 1018    | 1        | 16.67%  |
| HP LaserJet 1010    | 1        | 16.67%  |
| Brother MFC-9130CW  | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 3        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1        | 33.33%  |
| Canon CanoScan LiDE 600F      | 1        | 33.33%  |
| Canon CanoScan LiDE 110       | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 44       | 65.67%  |
| Z-Star Microelectronics       | 4        | 5.97%   |
| Microdia                      | 4        | 5.97%   |
| Samsung Electronics           | 3        | 4.48%   |
| ARC International             | 3        | 4.48%   |
| Realtek Semiconductor         | 2        | 2.99%   |
| MacroSilicon                  | 2        | 2.99%   |
| webcam                        | 1        | 1.49%   |
| Sunplus Innovation Technology | 1        | 1.49%   |
| KYE Systems (Mouse Systems)   | 1        | 1.49%   |
| Creative Technology           | 1        | 1.49%   |
| A4Tech                        | 1        | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                 | 11       | 16.18%  |
| Logitech Webcam C270                        | 8        | 11.76%  |
| Logitech C922 Pro Stream Webcam             | 4        | 5.88%   |
| Z-Star Venus USB2.0 Camera                  | 3        | 4.41%   |
| Samsung Galaxy A5 (MTP)                     | 3        | 4.41%   |
| Logitech Webcam C310                        | 3        | 4.41%   |
| ARC International Camera                    | 3        | 4.41%   |
| Realtek FULL HD 1080P Webcam                | 2        | 2.94%   |
| MacroSilicon USB Video                      | 2        | 2.94%   |
| Logitech Webcam C925e                       | 2        | 2.94%   |
| Logitech Webcam C200                        | 2        | 2.94%   |
| Logitech HD Webcam C615                     | 2        | 2.94%   |
| Logitech C920 PRO HD Webcam                 | 2        | 2.94%   |
| Logitech B525 HD Webcam                     | 2        | 2.94%   |
| Z-Star Vimicro USB Camera (Altair)          | 1        | 1.47%   |
| webcam webcam                               | 1        | 1.47%   |
| Sunplus UHD Capture                         | 1        | 1.47%   |
| Microdia Webcam Vitade AF                   | 1        | 1.47%   |
| Microdia JP001                              | 1        | 1.47%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 1.47%   |
| Microdia Camera                             | 1        | 1.47%   |
| Logitech Webcam Pro 9000                    | 1        | 1.47%   |
| Logitech Webcam C930e                       | 1        | 1.47%   |
| Logitech Webcam C300                        | 1        | 1.47%   |
| Logitech Webcam C170                        | 1        | 1.47%   |
| Logitech QuickCam Pro 9000                  | 1        | 1.47%   |
| Logitech QuickCam Communicate MP/S5500      | 1        | 1.47%   |
| Logitech HD Webcam C510                     | 1        | 1.47%   |
| Logitech C505e HD Webcam                    | 1        | 1.47%   |
| Logitech BRIO Ultra HD Webcam               | 1        | 1.47%   |
| KYE Systems (Mouse Systems) Genius Webcam   | 1        | 1.47%   |
| Creative VF0610 Live! Cam Socialize HD      | 1        | 1.47%   |
| A4Tech HD 720P PC Camera                    | 1        | 1.47%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Clay Logic                        | 2        | 50%     |
| VASCO Data Security International | 1        | 25%     |
| Aktiv                             | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Clay Logic Nitrokey Pro                        | 2        | 50%     |
| VASCO Data Security International DIGIPASS 870 | 1        | 25%     |
| Aktiv Rutoken lite                             | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 165      | 58.51%  |
| 1     | 84       | 29.79%  |
| 2     | 21       | 7.45%   |
| 3     | 10       | 3.55%   |
| 5     | 1        | 0.35%   |
| 4     | 1        | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 38       | 24.84%  |
| Sound                    | 20       | 13.07%  |
| Bluetooth                | 19       | 12.42%  |
| Graphics card            | 18       | 11.76%  |
| Net/wireless             | 15       | 9.8%    |
| Firewire controller      | 12       | 7.84%   |
| Camera                   | 7        | 4.58%   |
| Storage/ide              | 4        | 2.61%   |
| Network                  | 4        | 2.61%   |
| Net/ethernet             | 4        | 2.61%   |
| Tv card                  | 2        | 1.31%   |
| Storage/raid             | 2        | 1.31%   |
| Chipcard                 | 2        | 1.31%   |
| Unassigned class         | 1        | 0.65%   |
| Storage                  | 1        | 0.65%   |
| Multimedia controller    | 1        | 0.65%   |
| Modem                    | 1        | 0.65%   |
| Dvb card                 | 1        | 0.65%   |
| Card reader              | 1        | 0.65%   |

