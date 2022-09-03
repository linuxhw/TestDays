Ubuntu Budgie - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie.

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

Total: 234

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | A88X-PRO                    | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| HP         | 3397                        | [335f59c96f](https://linux-hardware.org/?probe=335f59c96f) | Aug 22, 2022 |
| Intel      | X79M-S                      | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| ASUSTek    | Berkeley                    | [e9998910ee](https://linux-hardware.org/?probe=e9998910ee) | Aug 17, 2022 |
| HP         | 828A                        | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| Biostar    | A960D+V3                    | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock     | A300M-STX                   | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock     | A300M-STX                   | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Intel      | STK1A32SC H95551-301        | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Gigabyte   | GA-890GPA-UD3H              | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP         | 212B                        | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| Gigabyte   | B75M-D3H                    | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Gigabyte   | GA-890GPA-UD3H              | [3195007eb2](https://linux-hardware.org/?probe=3195007eb2) | May 30, 2022 |
| Gigabyte   | F2A78M-HD2                  | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek    | PRIME B560M-A               | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| MSI        | X370 GAMING PRO CARBON      | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Gigabyte   | B75M-D3H                    | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte   | B450 I AORUS PRO WIFI-CF    | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| HP         | 1825                        | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| ASUSTek    | P8Z77-V LX                  | [9f241088c2](https://linux-hardware.org/?probe=9f241088c2) | May 06, 2022 |
| ASUSTek    | P8Z77-V LX                  | [37fa300c26](https://linux-hardware.org/?probe=37fa300c26) | Apr 18, 2022 |
| Gigabyte   | B550 AORUS ELITE AX V2      | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| MSI        | H81M-E33                    | [33547f6d85](https://linux-hardware.org/?probe=33547f6d85) | Apr 11, 2022 |
| Gigabyte   | X570 UD                     | [860fedd7f0](https://linux-hardware.org/?probe=860fedd7f0) | Apr 01, 2022 |
| Gigabyte   | 970A-DS3P                   | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| Gigabyte   | B560 DS3H AC-Y1             | [5be284f90d](https://linux-hardware.org/?probe=5be284f90d) | Feb 26, 2022 |
| ASUSTek    | ROG STRIX B550-E GAMING     | [7fa418eb00](https://linux-hardware.org/?probe=7fa418eb00) | Feb 25, 2022 |
| ASRock     | 970 Pro3 R2.0               | [9b8714532b](https://linux-hardware.org/?probe=9b8714532b) | Feb 20, 2022 |
| Dell       | 0RW199                      | [5cf70558c8](https://linux-hardware.org/?probe=5cf70558c8) | Feb 14, 2022 |
| ASUSTek    | M4A87TD/USB3                | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| ASRock     | B550 Phantom Gaming-ITX/... | [6f4c9d5553](https://linux-hardware.org/?probe=6f4c9d5553) | Jan 27, 2022 |
| Gigabyte   | 970A-DS3P                   | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Gigabyte   | 970A-DS3P                   | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| ASUSTek    | P5KPL-AM SE                 | [e4d4e112f7](https://linux-hardware.org/?probe=e4d4e112f7) | Jan 13, 2022 |
| ASRock     | 4X4-4000 Series             | [172d5b0abc](https://linux-hardware.org/?probe=172d5b0abc) | Jan 12, 2022 |
| ASUSTek    | H81M-C                      | [f0e03ffaed](https://linux-hardware.org/?probe=f0e03ffaed) | Dec 22, 2021 |
| Lenovo     | 36F7 SDK0J40700 WIN 3258... | [ddf55561ad](https://linux-hardware.org/?probe=ddf55561ad) | Dec 21, 2021 |
| Dell       | 0XPDFK A01                  | [8e1c093fb8](https://linux-hardware.org/?probe=8e1c093fb8) | Dec 20, 2021 |
| Dell       | 0XPDFK A01                  | [7eabc884a6](https://linux-hardware.org/?probe=7eabc884a6) | Dec 19, 2021 |
| Lenovo     | 36F7 SDK0J40700 WIN 3258... | [d416ec7878](https://linux-hardware.org/?probe=d416ec7878) | Dec 17, 2021 |
| Dell       | 0XPDFK A01                  | [2aaaff47a4](https://linux-hardware.org/?probe=2aaaff47a4) | Dec 17, 2021 |
| ASUSTek    | PRIME B360M-A               | [d34989fcaa](https://linux-hardware.org/?probe=d34989fcaa) | Dec 16, 2021 |
| ASUSTek    | PRIME B360M-A               | [7587f8f78a](https://linux-hardware.org/?probe=7587f8f78a) | Dec 16, 2021 |
| ASRock     | H61M-HVS                    | [bd9653afdd](https://linux-hardware.org/?probe=bd9653afdd) | Dec 15, 2021 |
| ASRock     | Z370M Pro4                  | [ade1f1db1a](https://linux-hardware.org/?probe=ade1f1db1a) | Dec 07, 2021 |
| Intel      | DP55WB AAE64798-206         | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| ASRock     | 970M Pro3                   | [126c160ef3](https://linux-hardware.org/?probe=126c160ef3) | Dec 04, 2021 |
| Dell       | 0Y2MRG A00                  | [945995abf6](https://linux-hardware.org/?probe=945995abf6) | Dec 02, 2021 |
| Dell       | 0Y2MRG A00                  | [35a82530fb](https://linux-hardware.org/?probe=35a82530fb) | Dec 02, 2021 |
| Pegatron   | IPI43-TTM                   | [3cea520e1f](https://linux-hardware.org/?probe=3cea520e1f) | Nov 29, 2021 |
| Pegatron   | IPI43-TTM                   | [3fbd626bf6](https://linux-hardware.org/?probe=3fbd626bf6) | Nov 27, 2021 |
| Pegatron   | IPI43-TTM                   | [ba184983ea](https://linux-hardware.org/?probe=ba184983ea) | Nov 27, 2021 |
| HP         | 0A5Ch                       | [4858eb5c73](https://linux-hardware.org/?probe=4858eb5c73) | Nov 21, 2021 |
| Gigabyte   | B560M AORUS ELITE           | [b397fce5b8](https://linux-hardware.org/?probe=b397fce5b8) | Nov 20, 2021 |
| ASUSTek    | Pro WS 565-ACE              | [61f2f6aeab](https://linux-hardware.org/?probe=61f2f6aeab) | Nov 19, 2021 |
| Lenovo     | SDK0J40700 WIN              | [f18f314bc7](https://linux-hardware.org/?probe=f18f314bc7) | Nov 01, 2021 |
| Gigabyte   | H410M H V3                  | [6a3a81abd6](https://linux-hardware.org/?probe=6a3a81abd6) | Oct 22, 2021 |
| Gigabyte   | H410M H V3                  | [2f0f49590b](https://linux-hardware.org/?probe=2f0f49590b) | Oct 22, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [cc51204b2c](https://linux-hardware.org/?probe=cc51204b2c) | Oct 20, 2021 |
| HP         | 0A5Ch                       | [8d102a03f6](https://linux-hardware.org/?probe=8d102a03f6) | Oct 19, 2021 |
| HP         | 0A5Ch                       | [139efd1a3d](https://linux-hardware.org/?probe=139efd1a3d) | Oct 19, 2021 |
| Gigabyte   | AB350-Gaming 3-CF           | [4cb5912db3](https://linux-hardware.org/?probe=4cb5912db3) | Oct 15, 2021 |
| ASRock     | Z370M Pro4                  | [17c9df42cd](https://linux-hardware.org/?probe=17c9df42cd) | Sep 07, 2021 |
| ASRock     | Z370M Pro4                  | [01d203a7af](https://linux-hardware.org/?probe=01d203a7af) | Sep 07, 2021 |
| ASRock     | H61M-VG3                    | [7257c7b0bb](https://linux-hardware.org/?probe=7257c7b0bb) | Aug 20, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [15b41a9b17](https://linux-hardware.org/?probe=15b41a9b17) | Aug 16, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [dcbe85bfb3](https://linux-hardware.org/?probe=dcbe85bfb3) | Aug 16, 2021 |
| ASUSTek    | P7P55D                      | [c62d162396](https://linux-hardware.org/?probe=c62d162396) | Aug 02, 2021 |
| ASUSTek    | PRIME B450M-A               | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| ASUSTek    | P7P55D                      | [cd96dbf86a](https://linux-hardware.org/?probe=cd96dbf86a) | Jul 30, 2021 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [6f7de51af1](https://linux-hardware.org/?probe=6f7de51af1) | Jul 25, 2021 |
| ASUSTek    | P7P55D                      | [b983e48d71](https://linux-hardware.org/?probe=b983e48d71) | Jul 24, 2021 |
| Gigabyte   | H110M-S2H-CF                | [18951b50fd](https://linux-hardware.org/?probe=18951b50fd) | Jul 23, 2021 |
| ASUSTek    | P7P55D                      | [2335f32be7](https://linux-hardware.org/?probe=2335f32be7) | Jul 22, 2021 |
| ASUSTek    | PRIME B450M-A               | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Fujitsu    | D3227-A1 S26361-D3227-A1    | [157b9695ae](https://linux-hardware.org/?probe=157b9695ae) | Jul 15, 2021 |
| Gigabyte   | H110M-S2H-CF                | [e0f1466068](https://linux-hardware.org/?probe=e0f1466068) | Jul 09, 2021 |
| HP         | 1588h                       | [28a2da9b7f](https://linux-hardware.org/?probe=28a2da9b7f) | Jul 05, 2021 |
| Dell       | 048DY8 A01                  | [04c41fe4c2](https://linux-hardware.org/?probe=04c41fe4c2) | Jun 30, 2021 |
| Intel      | DB75EN AAG39650-303         | [d90efe186a](https://linux-hardware.org/?probe=d90efe186a) | Jun 25, 2021 |
| ASUSTek    | M4A87TD/USB3                | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| HP         | 1998                        | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| HP         | 1998                        | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| Pegatron   | IPI43-TTM                   | [6a63f48182](https://linux-hardware.org/?probe=6a63f48182) | May 29, 2021 |
| Gigabyte   | Z68M-D2H                    | [75877fb3b1](https://linux-hardware.org/?probe=75877fb3b1) | May 19, 2021 |
| Gigabyte   | Z68M-D2H                    | [91cee123e9](https://linux-hardware.org/?probe=91cee123e9) | May 19, 2021 |
| Gigabyte   | Z68M-D2H                    | [ec195ffe95](https://linux-hardware.org/?probe=ec195ffe95) | May 12, 2021 |
| ASUSTek    | ROG STRIX Z390-H GAMING     | [8260769b47](https://linux-hardware.org/?probe=8260769b47) | May 01, 2021 |
| ASUSTek    | P6T SE                      | [a2fb8f6b18](https://linux-hardware.org/?probe=a2fb8f6b18) | May 01, 2021 |
| ASUSTek    | P8H77-M LE                  | [289b0a89c0](https://linux-hardware.org/?probe=289b0a89c0) | Apr 25, 2021 |
| ASUSTek    | Maximus VIII IMPACT         | [2c0a43e573](https://linux-hardware.org/?probe=2c0a43e573) | Apr 24, 2021 |
| Gigabyte   | Z77X-D3H                    | [28751098a6](https://linux-hardware.org/?probe=28751098a6) | Apr 23, 2021 |
| Gigabyte   | Z68M-D2H                    | [c2c4591ef9](https://linux-hardware.org/?probe=c2c4591ef9) | Apr 16, 2021 |
| ASRock     | X370 Gaming-ITX/ac          | [e0fa7ade7a](https://linux-hardware.org/?probe=e0fa7ade7a) | Apr 06, 2021 |
| Huanan     | X79 249PC V2.2              | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| Pegatron   | IPI43-TTM                   | [87168e11ee](https://linux-hardware.org/?probe=87168e11ee) | Mar 26, 2021 |
| Pegatron   | IPI43-TTM                   | [72adf1881e](https://linux-hardware.org/?probe=72adf1881e) | Mar 26, 2021 |
| ASUSTek    | Z77-A                       | [ca21510412](https://linux-hardware.org/?probe=ca21510412) | Mar 23, 2021 |
| ASUSTek    | PRIME A320M-K               | [4c755699d3](https://linux-hardware.org/?probe=4c755699d3) | Mar 21, 2021 |
| ASUSTek    | P7P55D-E LX                 | [83f55d5bf7](https://linux-hardware.org/?probe=83f55d5bf7) | Mar 20, 2021 |
| HP         | 3031h                       | [ee5e7baf77](https://linux-hardware.org/?probe=ee5e7baf77) | Mar 16, 2021 |
| ASUSTek    | Z97-A                       | [0cc10a7f8b](https://linux-hardware.org/?probe=0cc10a7f8b) | Mar 14, 2021 |
| ASUSTek    | ROG STRIX Z390-H GAMING     | [26c69c1a34](https://linux-hardware.org/?probe=26c69c1a34) | Mar 07, 2021 |
| ASUSTek    | PRIME B450-PLUS             | [79b5c4e048](https://linux-hardware.org/?probe=79b5c4e048) | Mar 07, 2021 |
| Dell       | 0KJCC5 A00                  | [5587c00381](https://linux-hardware.org/?probe=5587c00381) | Mar 02, 2021 |
| Unknown    | Unknown                     | [c6d24d073b](https://linux-hardware.org/?probe=c6d24d073b) | Feb 25, 2021 |
| Unknown    | Unknown                     | [f97163d774](https://linux-hardware.org/?probe=f97163d774) | Feb 24, 2021 |
| BCM        | RX965Q                      | [889ee09398](https://linux-hardware.org/?probe=889ee09398) | Feb 21, 2021 |
| ASUSTek    | ROG STRIX H470-I GAMING     | [f747681c25](https://linux-hardware.org/?probe=f747681c25) | Feb 19, 2021 |
| ASUSTek    | H61M-A                      | [2b8de1db1f](https://linux-hardware.org/?probe=2b8de1db1f) | Feb 19, 2021 |
| Dell       | 0KRC95 A02                  | [745c1185fd](https://linux-hardware.org/?probe=745c1185fd) | Feb 18, 2021 |
| ASUSTek    | H61M-K                      | [d470929ba8](https://linux-hardware.org/?probe=d470929ba8) | Feb 14, 2021 |
| MSI        | A320M PRO-VD PLUS           | [24a9ae34ed](https://linux-hardware.org/?probe=24a9ae34ed) | Feb 13, 2021 |
| Gigabyte   | B450M DS3H-CF               | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte   | B450M DS3H-CF               | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| MSI        | B250M BAZOOKA               | [f48bc9fc78](https://linux-hardware.org/?probe=f48bc9fc78) | Feb 07, 2021 |
| MSI        | B250M BAZOOKA               | [1f3b4b8203](https://linux-hardware.org/?probe=1f3b4b8203) | Feb 07, 2021 |
| MSI        | B250M BAZOOKA               | [005301f0e8](https://linux-hardware.org/?probe=005301f0e8) | Feb 07, 2021 |
| MSI        | B250M BAZOOKA               | [48a778609f](https://linux-hardware.org/?probe=48a778609f) | Feb 06, 2021 |
| Apple      | Mac-F4208DC8 PVT            | [bb89e367c8](https://linux-hardware.org/?probe=bb89e367c8) | Jan 17, 2021 |
| Gigabyte   | H110M-A-CF                  | [3a07ab383e](https://linux-hardware.org/?probe=3a07ab383e) | Jan 15, 2021 |
| Gigabyte   | H110M-A-CF                  | [bb66f59b76](https://linux-hardware.org/?probe=bb66f59b76) | Jan 12, 2021 |
| HP         | 1589                        | [fe93b414cb](https://linux-hardware.org/?probe=fe93b414cb) | Jan 09, 2021 |
| ASUSTek    | TUF Z370-PLUS GAMING        | [276dda536a](https://linux-hardware.org/?probe=276dda536a) | Jan 06, 2021 |
| Gigabyte   | H110M-A-CF                  | [bff63b3c48](https://linux-hardware.org/?probe=bff63b3c48) | Jan 05, 2021 |
| ASUSTek    | TUF Z370-PLUS GAMING        | [a80e8c5eb0](https://linux-hardware.org/?probe=a80e8c5eb0) | Jan 02, 2021 |
| Gigabyte   | B550I AORUS PRO AX          | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| Dell       | 0PK096                      | [e1a520e089](https://linux-hardware.org/?probe=e1a520e089) | Dec 24, 2020 |
| Gigabyte   | B550M AORUS PRO-P           | [c32461bc20](https://linux-hardware.org/?probe=c32461bc20) | Dec 19, 2020 |
| ASUSTek    | PRIME A320M-K/BR            | [d65d3733f6](https://linux-hardware.org/?probe=d65d3733f6) | Dec 07, 2020 |
| Gigabyte   | TRX40 DESIGNARE             | [25ff6d84d0](https://linux-hardware.org/?probe=25ff6d84d0) | Dec 07, 2020 |
| ASRock     | P67 Extreme4                | [ca2f3a785a](https://linux-hardware.org/?probe=ca2f3a785a) | Dec 06, 2020 |
| MSI        | MAG B550 TOMAHAWK           | [77dc96c206](https://linux-hardware.org/?probe=77dc96c206) | Nov 27, 2020 |
| LattePanda | Alpha                       | [706f930815](https://linux-hardware.org/?probe=706f930815) | Nov 26, 2020 |
| LattePanda | Alpha                       | [a5c3e54e65](https://linux-hardware.org/?probe=a5c3e54e65) | Nov 24, 2020 |
| Gigabyte   | 970A-D3P                    | [304945ac43](https://linux-hardware.org/?probe=304945ac43) | Nov 23, 2020 |
| ASUSTek    | Z97-A-USB31                 | [8bbc1a2d1c](https://linux-hardware.org/?probe=8bbc1a2d1c) | Nov 22, 2020 |
| ASUSTek    | P8Z68-V                     | [643bb20dc1](https://linux-hardware.org/?probe=643bb20dc1) | Nov 20, 2020 |
| Gigabyte   | TRX40 DESIGNARE             | [eb2134b274](https://linux-hardware.org/?probe=eb2134b274) | Oct 31, 2020 |
| MSI        | MEG Z490I UNIFY             | [e59b548946](https://linux-hardware.org/?probe=e59b548946) | Oct 31, 2020 |
| MSI        | MEG Z490I UNIFY             | [39348ac053](https://linux-hardware.org/?probe=39348ac053) | Oct 31, 2020 |
| Gigabyte   | Z170X-Gaming 3              | [58b6426d57](https://linux-hardware.org/?probe=58b6426d57) | Oct 30, 2020 |
| ASUSTek    | TUF Gaming X570-PLUS        | [aead0dde26](https://linux-hardware.org/?probe=aead0dde26) | Oct 27, 2020 |
| ASUSTek    | Maximus VIII IMPACT         | [b5a98b7ffa](https://linux-hardware.org/?probe=b5a98b7ffa) | Oct 24, 2020 |
| MSI        | Z370 GAMING PLUS            | [a5246866a5](https://linux-hardware.org/?probe=a5246866a5) | Oct 21, 2020 |
| MSI        | Z370 GAMING PLUS            | [19879c3493](https://linux-hardware.org/?probe=19879c3493) | Oct 21, 2020 |
| HP         | 1998                        | [e8076a87a0](https://linux-hardware.org/?probe=e8076a87a0) | Oct 20, 2020 |
| HP         | 1998                        | [69ed04c55d](https://linux-hardware.org/?probe=69ed04c55d) | Oct 20, 2020 |
| Apple      | Mac-F4208DC8 PVT            | [25565a3bbf](https://linux-hardware.org/?probe=25565a3bbf) | Oct 19, 2020 |
| Apple      | Mac-F4208DC8 PVT            | [3aa954c07b](https://linux-hardware.org/?probe=3aa954c07b) | Oct 19, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [7c78d9b4da](https://linux-hardware.org/?probe=7c78d9b4da) | Oct 18, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [ca85fa1d88](https://linux-hardware.org/?probe=ca85fa1d88) | Oct 18, 2020 |
| ASRock     | Q1900B-ITX                  | [527411a589](https://linux-hardware.org/?probe=527411a589) | Oct 15, 2020 |
| Unknown    | Unknown                     | [f82db8cb1c](https://linux-hardware.org/?probe=f82db8cb1c) | Oct 13, 2020 |
| AAEON      | UP-APL01 V0.4               | [3d2cb2e4d1](https://linux-hardware.org/?probe=3d2cb2e4d1) | Oct 12, 2020 |
| AAEON      | UP-APL01 V0.4               | [16d3bf5578](https://linux-hardware.org/?probe=16d3bf5578) | Oct 12, 2020 |
| ASUSTek    | TUF Z390-PLUS GAMING        | [9d2f2dbd87](https://linux-hardware.org/?probe=9d2f2dbd87) | Oct 12, 2020 |
| Dell       | 0M9KCM A00                  | [f884d19586](https://linux-hardware.org/?probe=f884d19586) | Oct 02, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [4a62de4c07](https://linux-hardware.org/?probe=4a62de4c07) | Oct 01, 2020 |
| ASRock     | B550 Phantom Gaming 4       | [a996c3d55c](https://linux-hardware.org/?probe=a996c3d55c) | Sep 29, 2020 |
| ASUSTek    | P9X79 DELUXE                | [5b7738af52](https://linux-hardware.org/?probe=5b7738af52) | Sep 23, 2020 |
| Dell       | 0RY007                      | [b1ca551538](https://linux-hardware.org/?probe=b1ca551538) | Sep 22, 2020 |
| Gigabyte   | B360 AORUS GAMING 3-CF      | [663a5ef41a](https://linux-hardware.org/?probe=663a5ef41a) | Sep 21, 2020 |
| Dell       | 0200DY A03                  | [e91f9c04b9](https://linux-hardware.org/?probe=e91f9c04b9) | Sep 21, 2020 |
| Gigabyte   | Z68M-D2H                    | [d746ae5a52](https://linux-hardware.org/?probe=d746ae5a52) | Sep 19, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [1037d2b746](https://linux-hardware.org/?probe=1037d2b746) | Sep 09, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [b3d6fb36eb](https://linux-hardware.org/?probe=b3d6fb36eb) | Sep 08, 2020 |
| Gigabyte   | Z390 DESIGNARE-CF           | [d36f3124d1](https://linux-hardware.org/?probe=d36f3124d1) | Sep 06, 2020 |
| ASUSTek    | ROG STRIX X470-F GAMING     | [e90f4fb0e5](https://linux-hardware.org/?probe=e90f4fb0e5) | Sep 06, 2020 |
| PCSMART    | 6.0                         | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| MSI        | Z97 GAMING 5                | [3f1b387a92](https://linux-hardware.org/?probe=3f1b387a92) | Sep 04, 2020 |
| Gigabyte   | G31M-ES2L                   | [ed4a78cd06](https://linux-hardware.org/?probe=ed4a78cd06) | Aug 24, 2020 |
| MSI        | Z87-G41 PC Mate             | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| ASUSTek    | P9X79 DELUXE                | [75f32f4978](https://linux-hardware.org/?probe=75f32f4978) | Aug 16, 2020 |
| Gigabyte   | P55A-UD4P                   | [c908fd4599](https://linux-hardware.org/?probe=c908fd4599) | Aug 07, 2020 |
| ASUSTek    | P8H77-M PRO                 | [d943208a7c](https://linux-hardware.org/?probe=d943208a7c) | Jul 30, 2020 |
| Gigabyte   | Z170-HD3 DDR3-CF            | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| ASUSTek    | STRIX B250F GAMING          | [cb5d511453](https://linux-hardware.org/?probe=cb5d511453) | Jul 28, 2020 |
| ASUSTek    | P8H77-M PRO                 | [87d7bc3077](https://linux-hardware.org/?probe=87d7bc3077) | Jul 28, 2020 |
| MSI        | X370 GAMING PRO CARBON      | [f38e8a0201](https://linux-hardware.org/?probe=f38e8a0201) | Jul 26, 2020 |
| HP         | 82F2                        | [172d6aed2a](https://linux-hardware.org/?probe=172d6aed2a) | Jul 26, 2020 |
| Gigabyte   | B360 AORUS GAMING 3 WIFI... | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| HP         | 3397                        | [edd52c2428](https://linux-hardware.org/?probe=edd52c2428) | Jul 24, 2020 |
| HP         | 3397                        | [20b3d353d8](https://linux-hardware.org/?probe=20b3d353d8) | Jul 24, 2020 |
| Gigabyte   | H61M-S1                     | [3ce4143dee](https://linux-hardware.org/?probe=3ce4143dee) | Jul 24, 2020 |
| Gigabyte   | B360 AORUS GAMING 3 WIFI... | [534a204796](https://linux-hardware.org/?probe=534a204796) | Jul 17, 2020 |
| ASUSTek    | M51AC                       | [fcc0f73453](https://linux-hardware.org/?probe=fcc0f73453) | Jul 15, 2020 |
| ASUSTek    | M4A87TD/USB3                | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek    | M4A87TD/USB3                | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek    | M4A87TD/USB3                | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| Dell       | 0P301D A02                  | [709ca37e1e](https://linux-hardware.org/?probe=709ca37e1e) | Jul 12, 2020 |
| ASUSTek    | M51AC                       | [6af32ff946](https://linux-hardware.org/?probe=6af32ff946) | Jul 01, 2020 |
| ASUSTek    | B85M-E                      | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| Dell       | 09KPNV A00                  | [9f63cccd5c](https://linux-hardware.org/?probe=9f63cccd5c) | Jun 21, 2020 |
| ASUSTek    | P8Z68-V PRO GEN3            | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Gigabyte   | Z68M-D2H                    | [fbbc2c4d98](https://linux-hardware.org/?probe=fbbc2c4d98) | May 30, 2020 |
| Gigabyte   | Z68M-D2H                    | [ca71847ca1](https://linux-hardware.org/?probe=ca71847ca1) | May 30, 2020 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [49486e2abf](https://linux-hardware.org/?probe=49486e2abf) | May 24, 2020 |
| ASUSTek    | P8H77-M PRO                 | [cdaf886b58](https://linux-hardware.org/?probe=cdaf886b58) | May 20, 2020 |
| ASUSTek    | P8H77-M PRO                 | [e8b5bf55c7](https://linux-hardware.org/?probe=e8b5bf55c7) | May 20, 2020 |
| Dell       | 0J32FG A06                  | [d5d2970bc5](https://linux-hardware.org/?probe=d5d2970bc5) | May 15, 2020 |
| Gigabyte   | Z68M-D2H                    | [70c167639c](https://linux-hardware.org/?probe=70c167639c) | May 15, 2020 |
| Dell       | 0TNXNR A01                  | [c16ecd859c](https://linux-hardware.org/?probe=c16ecd859c) | May 11, 2020 |
| Lenovo     | 3704 SDK0R32862 WIN 3258... | [eb7d6f2ec3](https://linux-hardware.org/?probe=eb7d6f2ec3) | May 10, 2020 |
| Biostar    | G31-M7 TE                   | [e9d31442df](https://linux-hardware.org/?probe=e9d31442df) | May 09, 2020 |
| ASRock     | B450 Gaming-ITX/ac          | [2e108e8f82](https://linux-hardware.org/?probe=2e108e8f82) | May 06, 2020 |
| MSI        | Z87-G41 PC Mate             | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| MSI        | MEG Z390 GODLIKE            | [f5c70a1643](https://linux-hardware.org/?probe=f5c70a1643) | Apr 30, 2020 |
| ASUSTek    | TUF B450-PLUS GAMING        | [6982ff0a12](https://linux-hardware.org/?probe=6982ff0a12) | Apr 25, 2020 |
| HP         | 0A80h                       | [f51e29fc6f](https://linux-hardware.org/?probe=f51e29fc6f) | Apr 13, 2020 |
| Gigabyte   | Z68M-D2H                    | [3db29a7f67](https://linux-hardware.org/?probe=3db29a7f67) | Apr 12, 2020 |
| ASRock     | N68C-S UCC                  | [c6df4257a4](https://linux-hardware.org/?probe=c6df4257a4) | Apr 11, 2020 |
| HP         | 8433 11                     | [e20dd4e4a3](https://linux-hardware.org/?probe=e20dd4e4a3) | Apr 02, 2020 |
| HP         | 8433 11                     | [eafaace7ee](https://linux-hardware.org/?probe=eafaace7ee) | Apr 02, 2020 |
| HP         | 8433 11                     | [0e29f294ba](https://linux-hardware.org/?probe=0e29f294ba) | Apr 02, 2020 |
| ASUSTek    | ROG CROSSHAIR VII HERO      | [5b8ef620f7](https://linux-hardware.org/?probe=5b8ef620f7) | Mar 27, 2020 |
| Gigabyte   | AB350-Gaming 3-CF           | [384177f515](https://linux-hardware.org/?probe=384177f515) | Mar 23, 2020 |
| Apple      | Mac-F221BEC8                | [477afd03f4](https://linux-hardware.org/?probe=477afd03f4) | Mar 21, 2020 |
| Dell       | 0J32FG A06                  | [efb8737ca2](https://linux-hardware.org/?probe=efb8737ca2) | Mar 20, 2020 |
| MSI        | Z270-A PRO                  | [5e41eb4c66](https://linux-hardware.org/?probe=5e41eb4c66) | Mar 14, 2020 |
| Dell       | 0C2KJT A00                  | [210b1c0abf](https://linux-hardware.org/?probe=210b1c0abf) | Mar 13, 2020 |
| ASUSTek    | Maximus VIII IMPACT         | [9ca13583bb](https://linux-hardware.org/?probe=9ca13583bb) | Mar 09, 2020 |
| eMachines  | EL1852G                     | [e90ac3f652](https://linux-hardware.org/?probe=e90ac3f652) | Feb 27, 2020 |
| Intel      | DQ965CO AAD34641-506        | [3c3c53b8e5](https://linux-hardware.org/?probe=3c3c53b8e5) | Feb 26, 2020 |
| ASUSTek    | Z97-A                       | [45382a84f3](https://linux-hardware.org/?probe=45382a84f3) | Feb 21, 2020 |
| HP         | 2215                        | [f9ecf106d2](https://linux-hardware.org/?probe=f9ecf106d2) | Feb 19, 2020 |
| Acer       | Veriton L4610G              | [e38723516e](https://linux-hardware.org/?probe=e38723516e) | Feb 17, 2020 |
| Acer       | Veriton L4610G              | [aef314a65c](https://linux-hardware.org/?probe=aef314a65c) | Feb 17, 2020 |
| Gigabyte   | Z68M-D2H                    | [6cfda70306](https://linux-hardware.org/?probe=6cfda70306) | Feb 15, 2020 |
| Intel      | ChiefRiver                  | [1ca590a614](https://linux-hardware.org/?probe=1ca590a614) | Jan 22, 2020 |
| Dell       | 0C27VV A01                  | [b896b0fef0](https://linux-hardware.org/?probe=b896b0fef0) | Jan 18, 2020 |
| Gigabyte   | MSH87TN-00                  | [624e731bcd](https://linux-hardware.org/?probe=624e731bcd) | Jan 16, 2020 |
| Gigabyte   | P55A-UD4P                   | [df0bc17152](https://linux-hardware.org/?probe=df0bc17152) | Jan 13, 2020 |
| Dell       | 0G9322                      | [62b841a44f](https://linux-hardware.org/?probe=62b841a44f) | Jun 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu Budgie 20.04 | 64       | 40.25%  |
| Ubuntu Budgie 20.10 | 23       | 14.47%  |
| Ubuntu Budgie 21.10 | 18       | 11.32%  |
| Ubuntu Budgie 22.04 | 14       | 8.81%   |
| Ubuntu Budgie 21.04 | 13       | 8.18%   |
| Ubuntu Budgie 19.10 | 13       | 8.18%   |
| Ubuntu Budgie 18.04 | 12       | 7.55%   |
| Ubuntu Budgie       | 2        | 1.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu Budgie | 148      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.4.0-42-generic        | 8        | 4.57%   |
| 5.4.0-47-generic        | 5        | 2.86%   |
| 5.8.0-43-generic        | 4        | 2.29%   |
| 5.4.0-52-generic        | 4        | 2.29%   |
| 5.4.0-48-generic        | 4        | 2.29%   |
| 5.4.0-45-generic        | 4        | 2.29%   |
| 5.4.0-37-generic        | 4        | 2.29%   |
| 5.3.0-40-generic        | 4        | 2.29%   |
| 5.3.0-26-generic        | 4        | 2.29%   |
| 5.13.0-22-generic       | 4        | 2.29%   |
| 5.8.0-44-generic        | 3        | 1.71%   |
| 5.8.0-25-generic        | 3        | 1.71%   |
| 5.4.0-31-generic        | 3        | 1.71%   |
| 5.4.0-29-generic        | 3        | 1.71%   |
| 5.3.0-42-generic        | 3        | 1.71%   |
| 5.15.0-30-generic       | 3        | 1.71%   |
| 5.13.0-39-generic       | 3        | 1.71%   |
| 5.11.0-41-generic       | 3        | 1.71%   |
| 5.11.0-22-generic       | 3        | 1.71%   |
| 5.11.0-18-generic       | 3        | 1.71%   |
| 5.8.0-59-generic        | 2        | 1.14%   |
| 5.8.0-50-generic        | 2        | 1.14%   |
| 5.8.0-48-generic        | 2        | 1.14%   |
| 5.8.0-45-generic        | 2        | 1.14%   |
| 5.8.0-31-generic        | 2        | 1.14%   |
| 5.8.0-29-generic        | 2        | 1.14%   |
| 5.8.0-26-generic        | 2        | 1.14%   |
| 5.4.0-91-generic        | 2        | 1.14%   |
| 5.4.0-72-generic        | 2        | 1.14%   |
| 5.4.0-66-generic        | 2        | 1.14%   |
| 5.4.0-59-generic        | 2        | 1.14%   |
| 5.4.0-40-generic        | 2        | 1.14%   |
| 5.3.0-28-generic        | 2        | 1.14%   |
| 5.15.0-46-generic       | 2        | 1.14%   |
| 5.15.0-33-generic       | 2        | 1.14%   |
| 5.15.0-27-generic       | 2        | 1.14%   |
| 5.15.0-25-generic       | 2        | 1.14%   |
| 5.13.0-40-generic       | 2        | 1.14%   |
| 5.13.0-30-generic       | 2        | 1.14%   |
| 5.13.0-21-generic       | 2        | 1.14%   |
| 5.13.0-20-generic       | 2        | 1.14%   |
| 5.13.0-19-generic       | 2        | 1.14%   |
| 5.9.1-050901-generic    | 1        | 0.57%   |
| 5.8.0-59-lowlatency     | 1        | 0.57%   |
| 5.8.0-53-generic        | 1        | 0.57%   |
| 5.8.0-41-generic        | 1        | 0.57%   |
| 5.8.0-33-generic        | 1        | 0.57%   |
| 5.8.0-30-generic        | 1        | 0.57%   |
| 5.8.0-21-generic        | 1        | 0.57%   |
| 5.8.0-18-generic        | 1        | 0.57%   |
| 5.8.0-1027-oracle       | 1        | 0.57%   |
| 5.7.7-xanmod1           | 1        | 0.57%   |
| 5.5.8-050508-lowlatency | 1        | 0.57%   |
| 5.4.0-96-generic        | 1        | 0.57%   |
| 5.4.0-80-generic        | 1        | 0.57%   |
| 5.4.0-70-generic        | 1        | 0.57%   |
| 5.4.0-67-generic        | 1        | 0.57%   |
| 5.4.0-65-generic        | 1        | 0.57%   |
| 5.4.0-62-generic        | 1        | 0.57%   |
| 5.4.0-58-generic        | 1        | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 55       | 34.38%  |
| 5.8.0   | 30       | 18.75%  |
| 5.13.0  | 19       | 11.88%  |
| 5.3.0   | 17       | 10.63%  |
| 5.11.0  | 15       | 9.38%   |
| 5.15.0  | 13       | 8.13%   |
| 4.15.0  | 2        | 1.25%   |
| 5.9.1   | 1        | 0.63%   |
| 5.7.7   | 1        | 0.63%   |
| 5.5.8   | 1        | 0.63%   |
| 5.17.2  | 1        | 0.63%   |
| 5.17.1  | 1        | 0.63%   |
| 5.14.2  | 1        | 0.63%   |
| 5.14.1  | 1        | 0.63%   |
| 5.10.0  | 1        | 0.63%   |
| 5.0.0   | 1        | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 55       | 34.59%  |
| 5.8     | 30       | 18.87%  |
| 5.13    | 19       | 11.95%  |
| 5.3     | 17       | 10.69%  |
| 5.11    | 15       | 9.43%   |
| 5.15    | 13       | 8.18%   |
| 5.17    | 2        | 1.26%   |
| 4.15    | 2        | 1.26%   |
| 5.9     | 1        | 0.63%   |
| 5.7     | 1        | 0.63%   |
| 5.5     | 1        | 0.63%   |
| 5.14    | 1        | 0.63%   |
| 5.10    | 1        | 0.63%   |
| 5.0     | 1        | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 143      | 96.62%  |
| i686   | 5        | 3.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 145      | 97.97%  |
| GNOME  | 2        | 1.35%   |
| KDE    | 1        | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 146      | 98.65%  |
| Wayland | 1        | 0.68%   |
| Tty     | 1        | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 84       | 55.63%  |
| LightDM | 33       | 21.85%  |
| TDM     | 27       | 17.88%  |
| GDM     | 5        | 3.31%   |
| SDDM    | 1        | 0.66%   |
| GDM3    | 1        | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 56       | 37.84%  |
| de_DE   | 21       | 14.19%  |
| fr_FR   | 13       | 8.78%   |
| pt_BR   | 10       | 6.76%   |
| en_CA   | 7        | 4.73%   |
| en_AU   | 5        | 3.38%   |
| es_ES   | 4        | 2.7%    |
| en_GB   | 3        | 2.03%   |
| zh_TW   | 2        | 1.35%   |
| uk_UA   | 2        | 1.35%   |
| pl_PL   | 2        | 1.35%   |
| nl_NL   | 2        | 1.35%   |
| it_IT   | 2        | 1.35%   |
| es_MX   | 2        | 1.35%   |
| es_CO   | 2        | 1.35%   |
| es_AR   | 2        | 1.35%   |
| Unknown | 2        | 1.35%   |
| ru_UA   | 1        | 0.68%   |
| ru_RU   | 1        | 0.68%   |
| ro_RO   | 1        | 0.68%   |
| pt_PT   | 1        | 0.68%   |
| fr_CH   | 1        | 0.68%   |
| fr_CA   | 1        | 0.68%   |
| es_CL   | 1        | 0.68%   |
| en_IN   | 1        | 0.68%   |
| en_IL   | 1        | 0.68%   |
| C       | 1        | 0.68%   |
| bg_BG   | 1        | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 99       | 64.29%  |
| EFI  | 55       | 35.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 140      | 93.96%  |
| Zfs     | 4        | 2.68%   |
| Overlay | 3        | 2.01%   |
| Btrfs   | 2        | 1.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 103      | 68.67%  |
| GPT     | 36       | 24%     |
| MBR     | 11       | 7.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 119      | 78.29%  |
| Yes       | 33       | 21.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 98       | 63.64%  |
| Yes       | 56       | 36.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 42       | 28.38%  |
| Gigabyte Technology | 29       | 19.59%  |
| Hewlett-Packard     | 15       | 10.14%  |
| Dell                | 15       | 10.14%  |
| MSI                 | 12       | 8.11%   |
| ASRock              | 12       | 8.11%   |
| Intel               | 5        | 3.38%   |
| Lenovo              | 3        | 2.03%   |
| Apple               | 3        | 2.03%   |
| Biostar             | 2        | 1.35%   |
| Unknown             | 2        | 1.35%   |
| Pegatron            | 1        | 0.68%   |
| PCSMART             | 1        | 0.68%   |
| LattePanda          | 1        | 0.68%   |
| Huanan              | 1        | 0.68%   |
| Fujitsu             | 1        | 0.68%   |
| eMachines           | 1        | 0.68%   |
| BCM                 | 1        | 0.68%   |
| Acer                | 1        | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 5        | 3.38%   |
| MSI MS-7C84                             | 2        | 1.35%   |
| HP EliteDesk 800 G1 SFF                 | 2        | 1.35%   |
| HP Compaq Elite 8300 SFF                | 2        | 1.35%   |
| Gigabyte Z68M-D2H                       | 2        | 1.35%   |
| Gigabyte AB350-Gaming 3                 | 2        | 1.35%   |
| Dell Precision WorkStation T3500        | 2        | 1.35%   |
| Dell OptiPlex 9010                      | 2        | 1.35%   |
| Dell OptiPlex 780                       | 2        | 1.35%   |
| ASUS P8H77-M PRO                        | 2        | 1.35%   |
| Apple MacPro1,1                         | 2        | 1.35%   |
| Unknown                                 | 2        | 1.35%   |
| Pegatron IPI43-TTM                      | 1        | 0.68%   |
| PCSMART 6.0                             | 1        | 0.68%   |
| MSI MS-7C77                             | 1        | 0.68%   |
| MSI MS-7B61                             | 1        | 0.68%   |
| MSI MS-7B38                             | 1        | 0.68%   |
| MSI MS-7B10                             | 1        | 0.68%   |
| MSI MS-7A71                             | 1        | 0.68%   |
| MSI MS-7A70                             | 1        | 0.68%   |
| MSI MS-7A32                             | 1        | 0.68%   |
| MSI MS-7917                             | 1        | 0.68%   |
| MSI MS-7850                             | 1        | 0.68%   |
| MSI MS-7817                             | 1        | 0.68%   |
| Lenovo Legion T530-28ICB 90L300BQMW     | 1        | 0.68%   |
| Lenovo IdeaCentre 310S-08ASR 90G9007EGE | 1        | 0.68%   |
| Lenovo H30-05 90BJ0086GE                | 1        | 0.68%   |
| LattePanda Alpha                        | 1        | 0.68%   |
| Intel STK1A32SC                         | 1        | 0.68%   |
| Intel DP55WB AAE64798-206               | 1        | 0.68%   |
| Intel DB75EN AAG39650-303               | 1        | 0.68%   |
| Intel CLIENTPRO 385                     | 1        | 0.68%   |
| Intel ChiefRiver                        | 1        | 0.68%   |
| Huanan X79 249PC V2.2                   | 1        | 0.68%   |
| HP Z440 Workstation                     | 1        | 0.68%   |
| HP Z420 Workstation                     | 1        | 0.68%   |
| HP Z210 Workstation                     | 1        | 0.68%   |
| HP rp5700 Business System               | 1        | 0.68%   |
| HP Pavilion Desktop PC 570-p0xx         | 1        | 0.68%   |
| HP Pavilion 590-p0049 3LC38AA           | 1        | 0.68%   |
| HP EliteDesk 800 G1 DM                  | 1        | 0.68%   |
| HP EliteDesk 705 G1 MT                  | 1        | 0.68%   |
| HP Compaq dc7900 Small Form Factor      | 1        | 0.68%   |
| HP Compaq dc7700 Ultra-slim Desktop     | 1        | 0.68%   |
| HP 750-417c                             | 1        | 0.68%   |
| Gigabyte Z77X-D3H                       | 1        | 0.68%   |
| Gigabyte Z390 DESIGNARE                 | 1        | 0.68%   |
| Gigabyte Z170X-Gaming 3                 | 1        | 0.68%   |
| Gigabyte Z170-HD3 DDR3                  | 1        | 0.68%   |
| Gigabyte X570 UD                        | 1        | 0.68%   |
| Gigabyte TRX40 DESIGNARE                | 1        | 0.68%   |
| Gigabyte P55A-UD4P                      | 1        | 0.68%   |
| Gigabyte MSH87TN-00                     | 1        | 0.68%   |
| Gigabyte H61M-S1                        | 1        | 0.68%   |
| Gigabyte H410M H V3                     | 1        | 0.68%   |
| Gigabyte H110M-S2H                      | 1        | 0.68%   |
| Gigabyte GA-890GPA-UD3H                 | 1        | 0.68%   |
| Gigabyte G31M-ES2L                      | 1        | 0.68%   |
| Gigabyte F2A78M-HD2                     | 1        | 0.68%   |
| Gigabyte B75M-D3H                       | 1        | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 7        | 4.73%   |
| ASUS ROG                | 6        | 4.05%   |
| ASUS PRIME              | 6        | 4.05%   |
| Dell Precision          | 5        | 3.38%   |
| ASUS All                | 5        | 3.38%   |
| HP EliteDesk            | 4        | 2.7%    |
| HP Compaq               | 4        | 2.7%    |
| ASUS TUF                | 3        | 2.03%   |
| ASUS P8H77-M            | 3        | 2.03%   |
| MSI MS-7C84             | 2        | 1.35%   |
| HP Pavilion             | 2        | 1.35%   |
| Gigabyte Z68M-D2H       | 2        | 1.35%   |
| Gigabyte B360           | 2        | 1.35%   |
| Gigabyte AB350-Gaming   | 2        | 1.35%   |
| Dell Inspiron           | 2        | 1.35%   |
| ASUS P8Z68-V            | 2        | 1.35%   |
| ASRock B550             | 2        | 1.35%   |
| Apple MacPro1           | 2        | 1.35%   |
| Unknown                 | 2        | 1.35%   |
| Pegatron IPI43-TTM      | 1        | 0.68%   |
| PCSMART 6.0             | 1        | 0.68%   |
| MSI MS-7C77             | 1        | 0.68%   |
| MSI MS-7B61             | 1        | 0.68%   |
| MSI MS-7B38             | 1        | 0.68%   |
| MSI MS-7B10             | 1        | 0.68%   |
| MSI MS-7A71             | 1        | 0.68%   |
| MSI MS-7A70             | 1        | 0.68%   |
| MSI MS-7A32             | 1        | 0.68%   |
| MSI MS-7917             | 1        | 0.68%   |
| MSI MS-7850             | 1        | 0.68%   |
| MSI MS-7817             | 1        | 0.68%   |
| Lenovo Legion           | 1        | 0.68%   |
| Lenovo IdeaCentre       | 1        | 0.68%   |
| Lenovo H30-05           | 1        | 0.68%   |
| LattePanda Alpha        | 1        | 0.68%   |
| Intel STK1A32SC         | 1        | 0.68%   |
| Intel DP55WB            | 1        | 0.68%   |
| Intel DB75EN            | 1        | 0.68%   |
| Intel CLIENTPRO         | 1        | 0.68%   |
| Intel ChiefRiver        | 1        | 0.68%   |
| Huanan X79              | 1        | 0.68%   |
| HP Z440                 | 1        | 0.68%   |
| HP Z420                 | 1        | 0.68%   |
| HP Z210                 | 1        | 0.68%   |
| HP rp5700               | 1        | 0.68%   |
| HP 750-417c             | 1        | 0.68%   |
| Gigabyte Z77X-D3H       | 1        | 0.68%   |
| Gigabyte Z390           | 1        | 0.68%   |
| Gigabyte Z170X-Gaming   | 1        | 0.68%   |
| Gigabyte Z170-HD3       | 1        | 0.68%   |
| Gigabyte X570           | 1        | 0.68%   |
| Gigabyte TRX40          | 1        | 0.68%   |
| Gigabyte P55A-UD4P      | 1        | 0.68%   |
| Gigabyte MSH87TN-00     | 1        | 0.68%   |
| Gigabyte H61M-S1        | 1        | 0.68%   |
| Gigabyte H410M          | 1        | 0.68%   |
| Gigabyte H110M-S2H      | 1        | 0.68%   |
| Gigabyte GA-890GPA-UD3H | 1        | 0.68%   |
| Gigabyte G31M-ES2L      | 1        | 0.68%   |
| Gigabyte F2A78M-HD2     | 1        | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 17       | 11.49%  |
| 2020 | 15       | 10.14%  |
| 2013 | 15       | 10.14%  |
| 2012 | 13       | 8.78%   |
| 2017 | 12       | 8.11%   |
| 2011 | 11       | 7.43%   |
| 2019 | 9        | 6.08%   |
| 2010 | 9        | 6.08%   |
| 2015 | 8        | 5.41%   |
| 2014 | 8        | 5.41%   |
| 2009 | 8        | 5.41%   |
| 2016 | 7        | 4.73%   |
| 2007 | 7        | 4.73%   |
| 2008 | 5        | 3.38%   |
| 2021 | 4        | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 148      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 146      | 97.99%  |
| Enabled  | 3        | 2.01%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 148      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 56       | 37.09%  |
| 8.01-16.0   | 24       | 15.89%  |
| 32.01-64.0  | 20       | 13.25%  |
| 3.01-4.0    | 19       | 12.58%  |
| 4.01-8.0    | 18       | 11.92%  |
| 64.01-256.0 | 10       | 6.62%   |
| 1.01-2.0    | 2        | 1.32%   |
| 24.01-32.0  | 1        | 0.66%   |
| 2.01-3.0    | 1        | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 53       | 32.32%  |
| 1.01-2.0   | 48       | 29.27%  |
| 4.01-8.0   | 28       | 17.07%  |
| 3.01-4.0   | 22       | 13.41%  |
| 8.01-16.0  | 8        | 4.88%   |
| 0.51-1.0   | 4        | 2.44%   |
| 32.01-64.0 | 1        | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 29.49%  |
| 2      | 43       | 27.56%  |
| 3      | 28       | 17.95%  |
| 4      | 18       | 11.54%  |
| 5      | 12       | 7.69%   |
| 8      | 4        | 2.56%   |
| 6      | 3        | 1.92%   |
| 11     | 1        | 0.64%   |
| 9      | 1        | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 77       | 51.68%  |
| No        | 72       | 48.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 145      | 97.97%  |
| No        | 3        | 2.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 51.33%  |
| Yes       | 73       | 48.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 58.94%  |
| Yes       | 62       | 41.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 39       | 26.17%  |
| Germany      | 22       | 14.77%  |
| France       | 14       | 9.4%    |
| Brazil       | 9        | 6.04%   |
| Canada       | 8        | 5.37%   |
| Australia    | 5        | 3.36%   |
| Switzerland  | 4        | 2.68%   |
| Ukraine      | 3        | 2.01%   |
| Spain        | 3        | 2.01%   |
| Poland       | 3        | 2.01%   |
| Netherlands  | 3        | 2.01%   |
| Mexico       | 3        | 2.01%   |
| Croatia      | 3        | 2.01%   |
| Argentina    | 3        | 2.01%   |
| UK           | 2        | 1.34%   |
| Romania      | 2        | 1.34%   |
| Portugal     | 2        | 1.34%   |
| Norway       | 2        | 1.34%   |
| Italy        | 2        | 1.34%   |
| Colombia     | 2        | 1.34%   |
| Thailand     | 1        | 0.67%   |
| Taiwan       | 1        | 0.67%   |
| Sweden       | 1        | 0.67%   |
| Slovenia     | 1        | 0.67%   |
| Saudi Arabia | 1        | 0.67%   |
| Russia       | 1        | 0.67%   |
| Puerto Rico  | 1        | 0.67%   |
| Japan        | 1        | 0.67%   |
| Israel       | 1        | 0.67%   |
| India        | 1        | 0.67%   |
| Hungary      | 1        | 0.67%   |
| Chile        | 1        | 0.67%   |
| Bulgaria     | 1        | 0.67%   |
| Bolivia      | 1        | 0.67%   |
| Belgium      | 1        | 0.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Zagreb                | 2        | 1.32%   |
| Uman                  | 2        | 1.32%   |
| Trondheim             | 2        | 1.32%   |
| Timișoara            | 2        | 1.32%   |
| Sydney                | 2        | 1.32%   |
| Paris                 | 2        | 1.32%   |
| New York              | 2        | 1.32%   |
| Milwaukee             | 2        | 1.32%   |
| Miami                 | 2        | 1.32%   |
| Maringá              | 2        | 1.32%   |
| Hamburg               | 2        | 1.32%   |
| Dallas                | 2        | 1.32%   |
| Caslano               | 2        | 1.32%   |
| Bogotá               | 2        | 1.32%   |
| Barcelona             | 2        | 1.32%   |
| Zurich                | 1        | 0.66%   |
| Zabrze                | 1        | 0.66%   |
| Würzburg             | 1        | 0.66%   |
| Westland              | 1        | 0.66%   |
| West Des Moines       | 1        | 0.66%   |
| Void-Vacon            | 1        | 0.66%   |
| UEbach-Palenberg      | 1        | 0.66%   |
| Tucson                | 1        | 0.66%   |
| Traunstein            | 1        | 0.66%   |
| Toyokawa              | 1        | 0.66%   |
| Toronto               | 1        | 0.66%   |
| Tobyhanna             | 1        | 0.66%   |
| Tlalnepantla          | 1        | 0.66%   |
| Tijuana               | 1        | 0.66%   |
| Thrissur              | 1        | 0.66%   |
| Telford               | 1        | 0.66%   |
| Świnoujście         | 1        | 0.66%   |
| Stara Zagora          | 1        | 0.66%   |
| Smithville            | 1        | 0.66%   |
| Skrad                 | 1        | 0.66%   |
| Shostka               | 1        | 0.66%   |
| Sherbrooke            | 1        | 0.66%   |
| Seraing               | 1        | 0.66%   |
| Senaide               | 1        | 0.66%   |
| Seminary              | 1        | 0.66%   |
| Seattle               | 1        | 0.66%   |
| Sao Paulo             | 1        | 0.66%   |
| Sao Caetano do Sul    | 1        | 0.66%   |
| Sao Bernardo do Campo | 1        | 0.66%   |
| Santa Cruz            | 1        | 0.66%   |
| San Pedro de la Paz   | 1        | 0.66%   |
| San Juan              | 1        | 0.66%   |
| San Jose              | 1        | 0.66%   |
| San Diego             | 1        | 0.66%   |
| San Antonio           | 1        | 0.66%   |
| Salvador              | 1        | 0.66%   |
| Saldan                | 1        | 0.66%   |
| Salach                | 1        | 0.66%   |
| Saint-Paul-de-Vence   | 1        | 0.66%   |
| Saint-Georges-dOrques | 1        | 0.66%   |
| Saint-Denis           | 1        | 0.66%   |
| Rueil-Malmaison       | 1        | 0.66%   |
| Roswell               | 1        | 0.66%   |
| Rio de Janeiro        | 1        | 0.66%   |
| Ravensburg            | 1        | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 58       | 102    | 19.21%  |
| WDC                       | 54       | 95     | 17.88%  |
| Samsung Electronics       | 46       | 73     | 15.23%  |
| Kingston                  | 19       | 29     | 6.29%   |
| Toshiba                   | 16       | 16     | 5.3%    |
| SanDisk                   | 16       | 24     | 5.3%    |
| Phison                    | 11       | 16     | 3.64%   |
| Hitachi                   | 11       | 15     | 3.64%   |
| Crucial                   | 7        | 8      | 2.32%   |
| Unknown                   | 4        | 6      | 1.32%   |
| OCZ                       | 4        | 7      | 1.32%   |
| Intel                     | 4        | 4      | 1.32%   |
| SPCC                      | 3        | 5      | 0.99%   |
| PNY                       | 3        | 3      | 0.99%   |
| Patriot                   | 3        | 5      | 0.99%   |
| Maxtor                    | 3        | 6      | 0.99%   |
| HGST                      | 3        | 4      | 0.99%   |
| China                     | 3        | 4      | 0.99%   |
| A-DATA Technology         | 3        | 6      | 0.99%   |
| Transcend                 | 2        | 2      | 0.66%   |
| Micron/Crucial Technology | 2        | 2      | 0.66%   |
| JMicron Technology        | 2        | 3      | 0.66%   |
| HS-SSD-C100               | 2        | 2      | 0.66%   |
| Apacer                    | 2        | 2      | 0.66%   |
| AMD                       | 2        | 17     | 0.66%   |
| Zheino                    | 1        | 1      | 0.33%   |
| XrayDisk                  | 1        | 1      | 0.33%   |
| TDAS                      | 1        | 3      | 0.33%   |
| SK hynix                  | 1        | 1      | 0.33%   |
| Silicon Motion            | 1        | 1      | 0.33%   |
| SABRENT                   | 1        | 1      | 0.33%   |
| Plextor                   | 1        | 1      | 0.33%   |
| Phison Electronics        | 1        | 1      | 0.33%   |
| Netac                     | 1        | 1      | 0.33%   |
| Micron Technology         | 1        | 3      | 0.33%   |
| MDT                       | 1        | 1      | 0.33%   |
| LDLC                      | 1        | 1      | 0.33%   |
| LaCie                     | 1        | 1      | 0.33%   |
| KingDian                  | 1        | 1      | 0.33%   |
| GOODRAM                   | 1        | 1      | 0.33%   |
| Gigabyte Technology       | 1        | 1      | 0.33%   |
| Axiom                     | 1        | 1      | 0.33%   |
| ASMT109x                  | 1        | 1      | 0.33%   |
| ADATA Technology          | 1        | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung SSD 860 QVO 1TB            | 6        | 1.62%   |
| Samsung SSD 860 EVO 500GB          | 6        | 1.62%   |
| Seagate ST500DM002-1BD142 500GB    | 5        | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB     | 5        | 1.35%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 4        | 1.08%   |
| Seagate ST2000DM001-1ER164 2TB     | 4        | 1.08%   |
| Samsung NVMe SSD Drive 512GB       | 4        | 1.08%   |
| Samsung NVMe SSD Drive 500GB       | 4        | 1.08%   |
| Kingston SA400S37480G 480GB SSD    | 4        | 1.08%   |
| Kingston SA400S37240G 240GB SSD    | 4        | 1.08%   |
| WDC WD5000AAKX-001CA0 500GB        | 3        | 0.81%   |
| Seagate ST9500325AS 500GB          | 3        | 0.81%   |
| Seagate ST4000DM000-1F2168 4TB     | 3        | 0.81%   |
| Seagate ST2000DM006-2DM164 2TB     | 3        | 0.81%   |
| Seagate ST2000DM001-1CH164 2TB     | 3        | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3        | 0.81%   |
| Seagate ST1000DM003-1ER162 1TB     | 3        | 0.81%   |
| SanDisk SDSSDA240G 240GB           | 3        | 0.81%   |
| SanDisk SDSSDA120G 120GB           | 3        | 0.81%   |
| Samsung SSD 850 EVO 500GB          | 3        | 0.81%   |
| Phison NVMe SSD Drive 1TB          | 3        | 0.81%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 2        | 0.54%   |
| WDC WD7501AALS-00J7B1 752GB        | 2        | 0.54%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 2        | 0.54%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 2        | 0.54%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2        | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 0.54%   |
| WDC WD10EZEX-00RKKA0 1TB           | 2        | 0.54%   |
| WDC WD10EADS-00M2B0 1TB            | 2        | 0.54%   |
| Unknown SD/MMC/MS PRO 128GB        | 2        | 0.54%   |
| Toshiba DT01ACA100 1TB             | 2        | 0.54%   |
| SPCC Solid State Disk 256GB        | 2        | 0.54%   |
| Seagate ST3500418AS 500GB          | 2        | 0.54%   |
| Seagate ST3500320AS 500GB          | 2        | 0.54%   |
| Seagate ST3320620AS 320GB          | 2        | 0.54%   |
| Seagate ST31000524AS 1TB           | 2        | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB     | 2        | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB     | 2        | 0.54%   |
| Samsung SSD 860 EVO 250GB          | 2        | 0.54%   |
| Samsung SSD 850 EVO 250GB          | 2        | 0.54%   |
| Samsung NVMe SSD Drive 1TB         | 2        | 0.54%   |
| Phison Sabrent Rocket 4.0 1TB      | 2        | 0.54%   |
| Phison NVMe SSD Drive 240GB        | 2        | 0.54%   |
| Phison NVMe SSD Drive 1024GB       | 2        | 0.54%   |
| OCZ AGILITY3 120GB SSD             | 2        | 0.54%   |
| Micron/Crucial NVMe SSD Drive 1TB  | 2        | 0.54%   |
| Kingston SV300S37A60G 64GB SSD     | 2        | 0.54%   |
| Kingston NVMe SSD Drive 500GB      | 2        | 0.54%   |
| China SATA SSD 240GB               | 2        | 0.54%   |
| Apacer AS510S 64GB SSD             | 2        | 0.54%   |
| AMD R5SL240G 240GB SSD             | 2        | 0.54%   |
| AMD R3SL120G 120GB SSD             | 2        | 0.54%   |
| Zheino CHN-25SATAC3-120 120GB      | 1        | 0.27%   |
| XrayDisk 256GB                     | 1        | 0.27%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 1        | 0.27%   |
| WDC WDS500G2B0A 500GB SSD          | 1        | 0.27%   |
| WDC WDS480G2G0C-00AJM0 480GB       | 1        | 0.27%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1        | 0.27%   |
| WDC WDS200T2B0A 2TB SSD            | 1        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 58       | 102    | 38.93%  |
| WDC                 | 49       | 87     | 32.89%  |
| Toshiba             | 16       | 16     | 10.74%  |
| Hitachi             | 11       | 15     | 7.38%   |
| Samsung Electronics | 5        | 6      | 3.36%   |
| Maxtor              | 3        | 6      | 2.01%   |
| HGST                | 3        | 4      | 2.01%   |
| Unknown             | 2        | 2      | 1.34%   |
| SABRENT             | 1        | 1      | 0.67%   |
| ASMT109x            | 1        | 1      | 0.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 30       | 41     | 28.3%   |
| Kingston            | 17       | 25     | 16.04%  |
| SanDisk             | 13       | 21     | 12.26%  |
| WDC                 | 7        | 7      | 6.6%    |
| Crucial             | 6        | 7      | 5.66%   |
| SPCC                | 3        | 5      | 2.83%   |
| Patriot             | 3        | 5      | 2.83%   |
| OCZ                 | 3        | 3      | 2.83%   |
| China               | 3        | 4      | 2.83%   |
| A-DATA Technology   | 3        | 6      | 2.83%   |
| PNY                 | 2        | 2      | 1.89%   |
| Intel               | 2        | 2      | 1.89%   |
| Apacer              | 2        | 2      | 1.89%   |
| AMD                 | 2        | 17     | 1.89%   |
| Zheino              | 1        | 1      | 0.94%   |
| Transcend           | 1        | 1      | 0.94%   |
| SK hynix            | 1        | 1      | 0.94%   |
| Plextor             | 1        | 1      | 0.94%   |
| Netac               | 1        | 1      | 0.94%   |
| KingDian            | 1        | 1      | 0.94%   |
| JMicron Technology  | 1        | 1      | 0.94%   |
| GOODRAM             | 1        | 1      | 0.94%   |
| Gigabyte Technology | 1        | 1      | 0.94%   |
| Axiom               | 1        | 1      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 110      | 240    | 45.27%  |
| SSD     | 81       | 157    | 33.33%  |
| NVMe    | 41       | 66     | 16.87%  |
| Unknown | 9        | 13     | 3.7%    |
| MMC     | 2        | 3      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 137      | 395    | 72.11%  |
| NVMe | 41       | 66     | 21.58%  |
| SAS  | 10       | 15     | 5.26%   |
| MMC  | 2        | 3      | 1.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 110      | 233    | 51.89%  |
| 0.51-1.0   | 59       | 93     | 27.83%  |
| 1.01-2.0   | 22       | 42     | 10.38%  |
| 3.01-4.0   | 12       | 19     | 5.66%   |
| 4.01-10.0  | 6        | 7      | 2.83%   |
| 2.01-3.0   | 3        | 3      | 1.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 48       | 30.38%  |
| 251-500        | 35       | 22.15%  |
| 501-1000       | 27       | 17.09%  |
| More than 3000 | 16       | 10.13%  |
| 1001-2000      | 12       | 7.59%   |
| 2001-3000      | 5        | 3.16%   |
| 51-100         | 5        | 3.16%   |
| 1-20           | 4        | 2.53%   |
| 21-50          | 3        | 1.9%    |
| Unknown        | 3        | 1.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 50       | 30.86%  |
| 101-250        | 27       | 16.67%  |
| 21-50          | 26       | 16.05%  |
| 251-500        | 17       | 10.49%  |
| 51-100         | 13       | 8.02%   |
| 1001-2000      | 11       | 6.79%   |
| 501-1000       | 7        | 4.32%   |
| More than 3000 | 5        | 3.09%   |
| 2001-3000      | 3        | 1.85%   |
| Unknown        | 3        | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 3        | 3      | 12.5%   |
| WDC WD5000AAKX-001CA0 500GB        | 2        | 2      | 8.33%   |
| WDC WD6000HLHX-01JJPV0 600GB       | 1        | 1      | 4.17%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1        | 1      | 4.17%   |
| WDC WD5000AVCS-632DY1 500GB        | 1        | 1      | 4.17%   |
| WDC WD4003FZEX-00Z4SA0 4TB         | 1        | 1      | 4.17%   |
| WDC WD2500AAJS-60M0A0 250GB        | 1        | 1      | 4.17%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 2      | 4.17%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 1      | 4.17%   |
| Seagate ST9500325AS 500GB          | 1        | 1      | 4.17%   |
| Seagate ST5000DM000-1FK178 5TB     | 1        | 1      | 4.17%   |
| Seagate ST3500320AS 500GB          | 1        | 1      | 4.17%   |
| Seagate ST3320620AS 320GB          | 1        | 1      | 4.17%   |
| Seagate ST3160815AS 160GB          | 1        | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 4.17%   |
| Seagate ST1000DX001-1NS162 1TB     | 1        | 1      | 4.17%   |
| Seagate ST1000DM003-1SB102 1TB     | 1        | 1      | 4.17%   |
| Patriot Pyro m3 240GB SSD          | 1        | 1      | 4.17%   |
| Maxtor STM3250310AS 250GB          | 1        | 1      | 4.17%   |
| Maxtor 6B200M0 208GB               | 1        | 2      | 4.17%   |
| Hitachi HDS721032CLA362 320GB      | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 11     | 45.83%  |
| WDC     | 9        | 10     | 37.5%   |
| Maxtor  | 2        | 3      | 8.33%   |
| Patriot | 1        | 1      | 4.17%   |
| Hitachi | 1        | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 11     | 47.83%  |
| WDC     | 9        | 10     | 39.13%  |
| Maxtor  | 2        | 3      | 8.7%    |
| Hitachi | 1        | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 25     | 94.74%  |
| SSD  | 1        | 1      | 5.26%   |

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
| Detected | 106      | 342    | 63.1%   |
| Works    | 43       | 111    | 25.6%   |
| Malfunc  | 19       | 26     | 11.31%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 104      | 48.37%  |
| AMD                           | 43       | 20%     |
| Samsung Electronics           | 17       | 7.91%   |
| Phison Electronics            | 12       | 5.58%   |
| Marvell Technology Group      | 9        | 4.19%   |
| JMicron Technology            | 6        | 2.79%   |
| ASMedia Technology            | 5        | 2.33%   |
| SanDisk                       | 3        | 1.4%    |
| Micron/Crucial Technology     | 3        | 1.4%    |
| Kingston Technology Company   | 3        | 1.4%    |
| Silicon Motion                | 2        | 0.93%   |
| Unknown                       | 1        | 0.47%   |
| Silicon Image                 | 1        | 0.47%   |
| OCZ Technology Group          | 1        | 0.47%   |
| Nvidia                        | 1        | 0.47%   |
| Micron Technology             | 1        | 0.47%   |
| Integrated Technology Express | 1        | 0.47%   |
| ADATA Technology              | 1        | 0.47%   |
| Adaptec                       | 1        | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27       | 9.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 4.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 3.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 3.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 3.32%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 2.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 2.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.58%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 2.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 2.58%   |
| Phison E12 NVMe Controller                                                              | 6        | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.21%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.48%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 1.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.48%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 4        | 1.48%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 4        | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 1.11%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 1.11%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.11%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 3        | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.11%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.11%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.11%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.11%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.74%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2        | 0.74%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.74%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 2        | 0.74%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.74%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.74%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.74%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.74%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.74%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.74%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.74%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.74%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.74%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.74%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 2        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 0.74%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 0.74%   |
| ASMedia 106x SATA/RAID Controller                                                       | 2        | 0.74%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.74%   |
| Unknown Non-Volatile memory controller                                                  | 1        | 0.37%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.37%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.37%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.37%   |
| SanDisk Non-Volatile memory controller                                                  | 1        | 0.37%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.37%   |
| Phison Electronics Non-Volatile memory controller                                       | 1        | 0.37%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 111      | 53.88%  |
| NVMe | 42       | 20.39%  |
| IDE  | 41       | 19.9%   |
| RAID | 11       | 5.34%   |
| SAS  | 1        | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 104      | 70.27%  |
| AMD    | 44       | 29.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 3.36%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 3.36%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 2.68%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 2.01%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 2.01%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.01%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 2.01%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 2.01%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 2.01%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 2.01%   |
| Intel Xeon CPU 5150 @ 2.66GHz               | 2        | 1.34%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 1.34%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.34%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.34%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.34%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 1.34%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.34%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.34%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.34%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.34%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.34%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.34%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 2        | 1.34%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.34%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.34%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.34%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1        | 0.67%   |
| Intel Xeon CPU X5492 @ 3.40GHz              | 1        | 0.67%   |
| Intel Xeon CPU W3670 @ 3.20GHz              | 1        | 0.67%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 0.67%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz          | 1        | 0.67%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz          | 1        | 0.67%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 0.67%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz         | 1        | 0.67%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.67%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.67%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.67%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.67%   |
| Intel Pentium CPU G2010 @ 2.80GHz           | 1        | 0.67%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.67%   |
| Intel Genuine CPU 0000 @ 3.10GHz            | 1        | 0.67%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1        | 0.67%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 0.67%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.67%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.67%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.67%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.67%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.67%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 0.67%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.67%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 0.67%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 0.67%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1        | 0.67%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 0.67%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.67%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 0.67%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 0.67%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.67%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 33       | 22.15%  |
| Intel Core i5           | 25       | 16.78%  |
| AMD Ryzen 5             | 13       | 8.72%   |
| Intel Xeon              | 10       | 6.71%   |
| AMD Ryzen 7             | 9        | 6.04%   |
| Intel Core i3           | 6        | 4.03%   |
| Intel Core 2 Duo        | 6        | 4.03%   |
| Intel Core 2            | 5        | 3.36%   |
| Intel Pentium           | 4        | 2.68%   |
| AMD Ryzen 3             | 4        | 2.68%   |
| AMD FX                  | 4        | 2.68%   |
| Other                   | 3        | 2.01%   |
| Intel Core i9           | 3        | 2.01%   |
| Intel Pentium Dual      | 2        | 1.34%   |
| Intel Core 2 Quad       | 2        | 1.34%   |
| Intel Celeron           | 2        | 1.34%   |
| AMD Ryzen 9             | 2        | 1.34%   |
| AMD A4                  | 2        | 1.34%   |
| AMD A10                 | 2        | 1.34%   |
| Intel Pentium Dual-Core | 1        | 0.67%   |
| Intel Pentium 4         | 1        | 0.67%   |
| Intel Genuine           | 1        | 0.67%   |
| Intel Core m3           | 1        | 0.67%   |
| Intel Atom              | 1        | 0.67%   |
| AMD Sempron             | 1        | 0.67%   |
| AMD Ryzen Threadripper  | 1        | 0.67%   |
| AMD Phenom II X6        | 1        | 0.67%   |
| AMD Phenom II X4        | 1        | 0.67%   |
| AMD Phenom II X2        | 1        | 0.67%   |
| AMD Athlon              | 1        | 0.67%   |
| AMD A6                  | 1        | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 64       | 43.24%  |
| 2      | 32       | 21.62%  |
| 8      | 21       | 14.19%  |
| 6      | 20       | 13.51%  |
| 1      | 4        | 2.7%    |
| 16     | 2        | 1.35%   |
| 12     | 2        | 1.35%   |
| 3      | 2        | 1.35%   |
| 24     | 1        | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 143      | 96.62%  |
| 2      | 5        | 3.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 85       | 57.05%  |
| 1      | 64       | 42.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 147      | 99.32%  |
| 32-bit         | 1        | 0.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 54       | 34.18%  |
| 0x306c3    | 12       | 7.59%   |
| 0x306a9    | 11       | 6.96%   |
| 0x206a7    | 9        | 5.7%    |
| 0x1067a    | 7        | 4.43%   |
| 0x506e3    | 5        | 3.16%   |
| 0x106e5    | 4        | 2.53%   |
| 0x08701021 | 4        | 2.53%   |
| 0x0800820d | 4        | 2.53%   |
| 0x906ec    | 3        | 1.9%    |
| 0x6f6      | 3        | 1.9%    |
| 0x6f2      | 3        | 1.9%    |
| 0xa0671    | 2        | 1.27%   |
| 0x906ea    | 2        | 1.27%   |
| 0x906e9    | 2        | 1.27%   |
| 0x6fd      | 2        | 1.27%   |
| 0x206d7    | 2        | 1.27%   |
| 0x06000852 | 2        | 1.27%   |
| 0x010000c8 | 2        | 1.27%   |
| 0xf34      | 1        | 0.63%   |
| 0xa0655    | 1        | 0.63%   |
| 0x906ed    | 1        | 0.63%   |
| 0x6fb      | 1        | 0.63%   |
| 0x406f1    | 1        | 0.63%   |
| 0x406c4    | 1        | 0.63%   |
| 0x306f2    | 1        | 0.63%   |
| 0x30678    | 1        | 0.63%   |
| 0x206c2    | 1        | 0.63%   |
| 0x20655    | 1        | 0.63%   |
| 0x106a5    | 1        | 0.63%   |
| 0x0a50000c | 1        | 0.63%   |
| 0x08701013 | 1        | 0.63%   |
| 0x08600103 | 1        | 0.63%   |
| 0x08108109 | 1        | 0.63%   |
| 0x08108102 | 1        | 0.63%   |
| 0x08101016 | 1        | 0.63%   |
| 0x0810100b | 1        | 0.63%   |
| 0x08001137 | 1        | 0.63%   |
| 0x06006704 | 1        | 0.63%   |
| 0x0600611a | 1        | 0.63%   |
| 0x06003109 | 1        | 0.63%   |
| 0x06001119 | 1        | 0.63%   |
| 0x010000dc | 1        | 0.63%   |
| 0x010000c7 | 1        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 16       | 10.81%  |
| IvyBridge   | 16       | 10.81%  |
| Haswell     | 16       | 10.81%  |
| Zen 2       | 14       | 9.46%   |
| SandyBridge | 14       | 9.46%   |
| Core        | 10       | 6.76%   |
| Zen+        | 9        | 6.08%   |
| Penryn      | 9        | 6.08%   |
| Skylake     | 6        | 4.05%   |
| Nehalem     | 6        | 4.05%   |
| Zen         | 5        | 3.38%   |
| Piledriver  | 4        | 2.7%    |
| K10         | 4        | 2.7%    |
| Westmere    | 3        | 2.03%   |
| Zen 3       | 2        | 1.35%   |
| Steamroller | 2        | 1.35%   |
| Silvermont  | 2        | 1.35%   |
| Icelake     | 2        | 1.35%   |
| Excavator   | 2        | 1.35%   |
| CometLake   | 2        | 1.35%   |
| Puma        | 1        | 0.68%   |
| NetBurst    | 1        | 0.68%   |
| Bulldozer   | 1        | 0.68%   |
| Broadwell   | 1        | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 69       | 42.07%  |
| AMD               | 48       | 29.27%  |
| Intel             | 46       | 28.05%  |
| ASPEED Technology | 1        | 0.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 7.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 6.02%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 5.42%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 4.22%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 3.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 3.61%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 5        | 3.01%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 2.41%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 2.41%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 2.41%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 2.41%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.41%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.81%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.81%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.81%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 1.2%    |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.2%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.2%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.2%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.2%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 1.2%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 1.2%    |
| AMD Juniper XT [Radeon HD 5770]                                             | 2        | 1.2%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.6%    |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.6%    |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.6%    |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.6%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.6%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.6%    |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.6%    |
| Nvidia GT200GL [Quadro FX 3800]                                             | 1        | 0.6%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.6%    |
| Nvidia GP104GL [Quadro P4000]                                               | 1        | 0.6%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.6%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.6%    |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.6%    |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 0.6%    |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.6%    |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.6%    |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.6%    |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.6%    |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.6%    |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 0.6%    |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.6%    |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 0.6%    |
| Nvidia GF119 [GeForce GT 625 OEM]                                           | 1        | 0.6%    |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.6%    |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 0.6%    |
| Nvidia GF110 [GeForce GTX 570]                                              | 1        | 0.6%    |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 0.6%    |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.6%    |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.6%    |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.6%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 0.6%    |
| Nvidia G92 [GeForce 9800 GTX+]                                              | 1        | 0.6%    |
| Nvidia G73 [GeForce 7300 GT]                                                | 1        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 61       | 39.61%  |
| 1 x AMD        | 42       | 27.27%  |
| 1 x Intel      | 41       | 26.62%  |
| AMD + Nvidia   | 4        | 2.6%    |
| Intel + Nvidia | 3        | 1.95%   |
| 2 x Nvidia     | 1        | 0.65%   |
| Intel + AMD    | 1        | 0.65%   |
| 1 x ASPEED     | 1        | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 92       | 59.35%  |
| Proprietary | 58       | 37.42%  |
| Unknown     | 5        | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 42.41%  |
| 1.01-2.0   | 21       | 13.29%  |
| 7.01-8.0   | 19       | 12.03%  |
| 5.01-6.0   | 15       | 9.49%   |
| 3.01-4.0   | 15       | 9.49%   |
| 0.51-1.0   | 11       | 6.96%   |
| 0.01-0.5   | 8        | 5.06%   |
| 2.01-3.0   | 1        | 0.63%   |
| 8.01-16.0  | 1        | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 33       | 20%     |
| Dell                 | 23       | 13.94%  |
| Hewlett-Packard      | 11       | 6.67%   |
| Goldstar             | 10       | 6.06%   |
| Acer                 | 10       | 6.06%   |
| Ancor Communications | 9        | 5.45%   |
| AOC                  | 8        | 4.85%   |
| BenQ                 | 6        | 3.64%   |
| Philips              | 5        | 3.03%   |
| Unknown              | 4        | 2.42%   |
| LG Electronics       | 4        | 2.42%   |
| Idek Iiyama          | 4        | 2.42%   |
| ASUSTek Computer     | 4        | 2.42%   |
| Iiyama               | 3        | 1.82%   |
| ViewSonic            | 2        | 1.21%   |
| Sony                 | 2        | 1.21%   |
| Sceptre Tech         | 2        | 1.21%   |
| MStar                | 2        | 1.21%   |
| Medion               | 2        | 1.21%   |
| Fujitsu Siemens      | 2        | 1.21%   |
| Eizo                 | 2        | 1.21%   |
| AGO                  | 2        | 1.21%   |
| Vizio                | 1        | 0.61%   |
| VIZ                  | 1        | 0.61%   |
| Unknown (XXX)        | 1        | 0.61%   |
| Sun                  | 1        | 0.61%   |
| SANYO                | 1        | 0.61%   |
| Pioneer Electronic   | 1        | 0.61%   |
| NEC Computers        | 1        | 0.61%   |
| MPI                  | 1        | 0.61%   |
| Microstep            | 1        | 0.61%   |
| Lenovo               | 1        | 0.61%   |
| Insignia             | 1        | 0.61%   |
| Huion                | 1        | 0.61%   |
| Daewoo               | 1        | 0.61%   |
| AUS                  | 1        | 0.61%   |
| Apple                | 1        | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics S27B550 SAM091B 1920x1080 598x336mm 27.0-inch       | 2        | 1.06%   |
| Samsung Electronics LCD Monitor SAM0BB4 3840x2160 1872x1053mm 84.6-inch | 2        | 1.06%   |
| Samsung Electronics LCD Monitor C34H89x 3440x1440                       | 2        | 1.06%   |
| MStar Demo MST0030 1920x540 708x398mm 32.0-inch                         | 2        | 1.06%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch   | 2        | 1.06%   |
| Vizio E321VL VIZ0067 1920x1080 698x393mm 31.5-inch                      | 1        | 0.53%   |
| Vizio D50u-D1 VIZ1011 3840x2160 941x529mm 42.5-inch                     | 1        | 0.53%   |
| VIZ LCD Monitor M50-C1 3840x2160                                        | 1        | 0.53%   |
| ViewSonic VX2476 Series VSC9939 1920x1080 527x296mm 23.8-inch           | 1        | 0.53%   |
| ViewSonic VA903 SERIES VSC111E 1280x1024 376x301mm 19.0-inch            | 1        | 0.53%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                   | 1        | 0.53%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                    | 1        | 0.53%   |
| Unknown LCD Monitor SAMSUNG                                             | 1        | 0.53%   |
| Unknown LCD Monitor GTW KX2153                                          | 1        | 0.53%   |
| Unknown LCD Monitor EMA E202HL                                          | 1        | 0.53%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1        | 0.53%   |
| Sun X7202A SUN0595 1280x1024 376x301mm 19.0-inch                        | 1        | 0.53%   |
| Sony SDM-HS93 SNY1190 1280x1024 357x286mm 18.0-inch                     | 1        | 0.53%   |
| Sony LCD Monitor TV  *07 5760x2160                                      | 1        | 0.53%   |
| Sony LCD Monitor TV  *07                                                | 1        | 0.53%   |
| Sceptre Tech Sceptre J20 SPT080D 1600x900 435x237mm 19.5-inch           | 1        | 0.53%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 800x340mm 34.2-inch          | 1        | 0.53%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                  | 1        | 0.53%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                  | 1        | 0.53%   |
| Samsung Electronics T24C550 SAM0AA1 1920x1080 521x293mm 23.5-inch       | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                        | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                        | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch    | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM03EE 1680x1050                        | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch    | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch    | 1        | 0.53%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch    | 1        | 0.53%   |
| Samsung Electronics S34J55x SAM0F72 1720x1440                           | 1        | 0.53%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 1        | 0.53%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 1        | 0.53%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.53%   |
| Samsung Electronics S24C650 SAM09E9 1920x1080 521x293mm 23.5-inch       | 1        | 0.53%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch       | 1        | 0.53%   |
| Samsung Electronics S24C300 SAM0A28 1920x1080 531x299mm 24.0-inch       | 1        | 0.53%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch       | 1        | 0.53%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch       | 1        | 0.53%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 1        | 0.53%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 480x270mm 21.7-inch       | 1        | 0.53%   |
| Samsung Electronics LCD Monitor SyncMaster 3600x1080                    | 1        | 0.53%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch   | 1        | 0.53%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch   | 1        | 0.53%   |
| Samsung Electronics LCD Monitor SAM06CA 1920x1080 1110x620mm 50.1-inch  | 1        | 0.53%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1        | 0.53%   |
| Samsung Electronics LCD Monitor S24E310 3840x1080                       | 1        | 0.53%   |
| Samsung Electronics LCD Monitor S24E310                                 | 1        | 0.53%   |
| Samsung Electronics LCD Monitor S24C450 3840x1200                       | 1        | 0.53%   |
| Samsung Electronics LCD Monitor S24C450                                 | 1        | 0.53%   |
| Samsung Electronics LCD Monitor S22C450 1680x1050                       | 1        | 0.53%   |
| Samsung Electronics LCD Monitor C32F391 1920x1080                       | 1        | 0.53%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch       | 1        | 0.53%   |
| Samsung Electronics C27FG70 SAM0DCA 1920x1080 598x337mm 27.0-inch       | 1        | 0.53%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch       | 1        | 0.53%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch       | 1        | 0.53%   |
| Pioneer Electronic LCD Monitor PDP-42FXE10 2646x768                     | 1        | 0.53%   |
| Pioneer Electronic LCD Monitor PDP-42FXE10 2390x768                     | 1        | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 69       | 40.35%  |
| 1280x1024 (SXGA)   | 15       | 8.77%   |
| Unknown            | 13       | 7.6%    |
| 3840x2160 (4K)     | 11       | 6.43%   |
| 1366x768 (WXGA)    | 9        | 5.26%   |
| 1920x1200 (WUXGA)  | 8        | 4.68%   |
| 1680x1050 (WSXGA+) | 7        | 4.09%   |
| 3840x1080          | 5        | 2.92%   |
| 3440x1440          | 5        | 2.92%   |
| 2560x1080          | 5        | 2.92%   |
| 2560x1440 (QHD)    | 4        | 2.34%   |
| 3520x1080          | 2        | 1.17%   |
| 2560x1600          | 2        | 1.17%   |
| 1600x900 (HD+)     | 2        | 1.17%   |
| 5760x2160          | 1        | 0.58%   |
| 4480x1080          | 1        | 0.58%   |
| 3840x1440          | 1        | 0.58%   |
| 3840x1200          | 1        | 0.58%   |
| 3600x1080          | 1        | 0.58%   |
| 3200x1800 (QHD+)   | 1        | 0.58%   |
| 2646x768           | 1        | 0.58%   |
| 2560x1024          | 1        | 0.58%   |
| 2390x768           | 1        | 0.58%   |
| 2048x1152          | 1        | 0.58%   |
| 1920x540           | 1        | 0.58%   |
| 1600x1200          | 1        | 0.58%   |
| 1400x1050          | 1        | 0.58%   |
| 1280x720 (HD)      | 1        | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 40       | 24.84%  |
| 27      | 21       | 13.04%  |
| 24      | 21       | 13.04%  |
| 23      | 18       | 11.18%  |
| 21      | 9        | 5.59%   |
| 19      | 8        | 4.97%   |
| 34      | 6        | 3.73%   |
| 17      | 5        | 3.11%   |
| 15      | 5        | 3.11%   |
| 54      | 3        | 1.86%   |
| 20      | 3        | 1.86%   |
| 18      | 3        | 1.86%   |
| 84      | 2        | 1.24%   |
| 52      | 2        | 1.24%   |
| 31      | 2        | 1.24%   |
| 22      | 2        | 1.24%   |
| 12      | 2        | 1.24%   |
| 63      | 1        | 0.62%   |
| 46      | 1        | 0.62%   |
| 37      | 1        | 0.62%   |
| 29      | 1        | 0.62%   |
| 28      | 1        | 0.62%   |
| 25      | 1        | 0.62%   |
| 16      | 1        | 0.62%   |
| 13      | 1        | 0.62%   |
| 8       | 1        | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 56       | 34.78%  |
| Unknown     | 40       | 24.84%  |
| 401-500     | 18       | 11.18%  |
| 301-350     | 11       | 6.83%   |
| 601-700     | 9        | 5.59%   |
| 351-400     | 7        | 4.35%   |
| 1001-1500   | 7        | 4.35%   |
| 701-800     | 6        | 3.73%   |
| 201-300     | 3        | 1.86%   |
| 1501-2000   | 2        | 1.24%   |
| 801-900     | 1        | 0.62%   |
| 101-200     | 1        | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 73       | 48.67%  |
| Unknown | 37       | 24.67%  |
| 16/10   | 14       | 9.33%   |
| 5/4     | 12       | 8%      |
| 21/9    | 7        | 4.67%   |
| 4/3     | 6        | 4%      |
| 6/5     | 1        | 0.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 40       | 25.48%  |
| 201-250        | 35       | 22.29%  |
| 301-350        | 21       | 13.38%  |
| 151-200        | 14       | 8.92%   |
| 251-300        | 10       | 6.37%   |
| 351-500        | 9        | 5.73%   |
| More than 1000 | 8        | 5.1%    |
| 141-150        | 8        | 5.1%    |
| 71-80          | 3        | 1.91%   |
| 101-110        | 3        | 1.91%   |
| 501-1000       | 2        | 1.27%   |
| 91-100         | 2        | 1.27%   |
| 1-40           | 1        | 0.64%   |
| 131-140        | 1        | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 81       | 53.29%  |
| Unknown       | 40       | 26.32%  |
| 101-120       | 15       | 9.87%   |
| 1-50          | 6        | 3.95%   |
| 121-160       | 5        | 3.29%   |
| 161-240       | 4        | 2.63%   |
| More than 240 | 1        | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 105      | 69.08%  |
| 2     | 36       | 23.68%  |
| 0     | 8        | 5.26%   |
| 3     | 2        | 1.32%   |
| 4     | 1        | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 85       | 39.53%  |
| Intel                           | 74       | 34.42%  |
| Broadcom                        | 14       | 6.51%   |
| Qualcomm Atheros                | 12       | 5.58%   |
| Ralink Technology               | 6        | 2.79%   |
| Microsoft                       | 3        | 1.4%    |
| D-Link System                   | 3        | 1.4%    |
| Ralink                          | 2        | 0.93%   |
| Qualcomm Atheros Communications | 2        | 0.93%   |
| Linksys                         | 2        | 0.93%   |
| D-Link                          | 2        | 0.93%   |
| Belkin Components               | 2        | 0.93%   |
| Xiaomi                          | 1        | 0.47%   |
| Wacom                           | 1        | 0.47%   |
| Nvidia                          | 1        | 0.47%   |
| NetGear                         | 1        | 0.47%   |
| Mercucys                        | 1        | 0.47%   |
| MediaTek                        | 1        | 0.47%   |
| Exar                            | 1        | 0.47%   |
| ASIX Electronics                | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 64       | 26.45%  |
| Intel Wi-Fi 6 AX200                                                                   | 12       | 4.96%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 8        | 3.31%   |
| Intel I211 Gigabit Network Connection                                                 | 7        | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 7        | 2.89%   |
| Intel Ethernet Connection I217-LM                                                     | 6        | 2.48%   |
| Intel Ethernet Connection (7) I219-V                                                  | 6        | 2.48%   |
| Intel Wireless-AC 9260                                                                | 5        | 2.07%   |
| Intel Ethernet Connection (2) I219-V                                                  | 5        | 2.07%   |
| Intel 82579V Gigabit Network Connection                                               | 5        | 2.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 4        | 1.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 4        | 1.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 4        | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 3        | 1.24%   |
| Intel Ethernet Controller I225-V                                                      | 3        | 1.24%   |
| Intel Ethernet Connection (2) I218-V                                                  | 3        | 1.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 3        | 1.24%   |
| Intel 82567LM-3 Gigabit Network Connection                                            | 3        | 1.24%   |
| Intel 82566DM Gigabit Network Connection                                              | 3        | 1.24%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                      | 3        | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2        | 0.83%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 2        | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2        | 0.83%   |
| Realtek 802.11ac NIC                                                                  | 2        | 0.83%   |
| Ralink MT7601U Wireless Adapter                                                       | 2        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 2        | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 2        | 0.83%   |
| Microsoft Xbox 360 Wireless Adapter                                                   | 2        | 0.83%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                                     | 2        | 0.83%   |
| Intel Wireless 7265                                                                   | 2        | 0.83%   |
| Intel I210 Gigabit Network Connection                                                 | 2        | 0.83%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                                | 2        | 0.83%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                               | 2        | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                        | 1        | 0.41%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                              | 1        | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1        | 0.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.41%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                   | 1        | 0.41%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 0.41%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1        | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                       | 1        | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1        | 0.41%   |
| Ralink RT5372 Wireless Adapter                                                        | 1        | 0.41%   |
| Ralink RT5370 Wireless Adapter                                                        | 1        | 0.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                 | 1        | 0.41%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                     | 1        | 0.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1        | 0.41%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                  | 1        | 0.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                             | 1        | 0.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1        | 0.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1        | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 1        | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1        | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1        | 0.41%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 0.41%   |
| Nvidia MCP61 Ethernet                                                                 | 1        | 0.41%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                               | 1        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 30       | 37.04%  |
| Realtek Semiconductor           | 13       | 16.05%  |
| Broadcom                        | 7        | 8.64%   |
| Ralink Technology               | 6        | 7.41%   |
| Qualcomm Atheros                | 6        | 7.41%   |
| Microsoft                       | 3        | 3.7%    |
| Ralink                          | 2        | 2.47%   |
| Qualcomm Atheros Communications | 2        | 2.47%   |
| Linksys                         | 2        | 2.47%   |
| D-Link System                   | 2        | 2.47%   |
| D-Link                          | 2        | 2.47%   |
| Belkin Components               | 2        | 2.47%   |
| Wacom                           | 1        | 1.23%   |
| NetGear                         | 1        | 1.23%   |
| Mercucys                        | 1        | 1.23%   |
| MediaTek                        | 1        | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 12       | 14.46%  |
| Intel Wireless-AC 9260                                                                  | 5        | 6.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 4        | 4.82%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 4        | 4.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                                         | 3        | 3.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                         | 2        | 2.41%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                              | 2        | 2.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 2        | 2.41%   |
| Realtek 802.11ac NIC                                                                    | 2        | 2.41%   |
| Ralink MT7601U Wireless Adapter                                                         | 2        | 2.41%   |
| Qualcomm Atheros AR9271 802.11n                                                         | 2        | 2.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 2        | 2.41%   |
| Microsoft Xbox 360 Wireless Adapter                                                     | 2        | 2.41%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                                       | 2        | 2.41%   |
| Intel Wireless 7265                                                                     | 2        | 2.41%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                                | 1        | 1.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 1        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                | 1        | 1.2%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 1.2%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                         | 1        | 1.2%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                             | 1        | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                                              | 1        | 1.2%    |
| Ralink RT5372 Wireless Adapter                                                          | 1        | 1.2%    |
| Ralink RT5370 Wireless Adapter                                                          | 1        | 1.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                   | 1        | 1.2%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                       | 1        | 1.2%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                               | 1        | 1.2%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                    | 1        | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 1        | 1.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                        | 1        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 1        | 1.2%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express)   | 1        | 1.2%    |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                                 | 1        | 1.2%    |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                             | 1        | 1.2%    |
| Microsoft XBOX ACC                                                                      | 1        | 1.2%    |
| Mercucys 802.11n NIC                                                                    | 1        | 1.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1        | 1.2%    |
| Intel Wireless 8265 / 8275                                                              | 1        | 1.2%    |
| Intel Wireless 3165                                                                     | 1        | 1.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                  | 1        | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                                          | 1        | 1.2%    |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]                       | 1        | 1.2%    |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 1.2%    |
| D-Link DWA-127 Wireless N 150 High-Gain Adapter(rev.A1) [Ralink RT3070]                 | 1        | 1.2%    |
| D-Link 802.11n WLAN Adapter                                                             | 1        | 1.2%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                      | 1        | 1.2%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                  | 1        | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                     | 1        | 1.2%    |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 1.2%    |
| Belkin Components F7D1101 v1 Basic Wireless Adapter [Realtek RTL8188SU]                 | 1        | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 79       | 51.63%  |
| Intel                 | 57       | 37.25%  |
| Broadcom              | 7        | 4.58%   |
| Qualcomm Atheros      | 6        | 3.92%   |
| Xiaomi                | 1        | 0.65%   |
| Nvidia                | 1        | 0.65%   |
| D-Link System         | 1        | 0.65%   |
| ASIX Electronics      | 1        | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64       | 40.51%  |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 5.06%   |
| Intel I211 Gigabit Network Connection                             | 7        | 4.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.43%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 3.8%    |
| Intel Ethernet Connection (7) I219-V                              | 6        | 3.8%    |
| Intel Ethernet Connection (2) I219-V                              | 5        | 3.16%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 3.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 2.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.9%    |
| Intel Ethernet Controller I225-V                                  | 3        | 1.9%    |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.9%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 1.9%    |
| Intel 82566DM Gigabit Network Connection                          | 3        | 1.9%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3        | 1.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.27%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.27%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 2        | 1.27%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.63%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.63%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.63%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.63%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.63%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.63%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.63%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.63%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.63%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.63%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.63%   |
| ASIX AX88772A Fast Ethernet                                       | 1        | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 145      | 66.21%  |
| WiFi     | 73       | 33.33%  |
| Modem    | 1        | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 113      | 71.07%  |
| WiFi     | 46       | 28.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 93       | 62.84%  |
| 2     | 43       | 29.05%  |
| 3     | 11       | 7.43%   |
| 0     | 1        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 128      | 84.77%  |
| Yes  | 23       | 15.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 29       | 46.03%  |
| Cambridge Silicon Radio         | 19       | 30.16%  |
| Qualcomm Atheros Communications | 3        | 4.76%   |
| Broadcom                        | 3        | 4.76%   |
| ASUSTek Computer                | 3        | 4.76%   |
| Realtek Semiconductor           | 2        | 3.17%   |
| Belkin Components               | 2        | 3.17%   |
| MediaTek                        | 1        | 1.59%   |
| Apple                           | 1        | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 19       | 30.16%  |
| Intel AX200 Bluetooth                                 | 12       | 19.05%  |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 5        | 7.94%   |
| Intel Bluetooth wireless interface                    | 4        | 6.35%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 4.76%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2        | 3.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 3.17%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 2        | 3.17%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.59%   |
| Realtek Bluetooth Radio                               | 1        | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 1.59%   |
| MediaTek Wireless_Device                              | 1        | 1.59%   |
| Intel AX210 Bluetooth                                 | 1        | 1.59%   |
| Intel AX201 Bluetooth                                 | 1        | 1.59%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 1.59%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 1.59%   |
| ASUS Bluetooth Radio                                  | 1        | 1.59%   |
| ASUS Bluetooth Adapter                                | 1        | 1.59%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 1        | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 99       | 38.37%  |
| Nvidia                    | 66       | 25.58%  |
| AMD                       | 60       | 23.26%  |
| Logitech                  | 5        | 1.94%   |
| C-Media Electronics       | 5        | 1.94%   |
| Creative Labs             | 4        | 1.55%   |
| Creative Technology       | 3        | 1.16%   |
| JMTek                     | 2        | 0.78%   |
| SteelSeries ApS           | 1        | 0.39%   |
| Sennheiser Communications | 1        | 0.39%   |
| Samson Technologies       | 1        | 0.39%   |
| Realtek Semiconductor     | 1        | 0.39%   |
| OPPO Electronics          | 1        | 0.39%   |
| Native Instruments        | 1        | 0.39%   |
| Nam Tai E&E Products      | 1        | 0.39%   |
| Microsoft                 | 1        | 0.39%   |
| M-Audio                   | 1        | 0.39%   |
| Kingston Technology       | 1        | 0.39%   |
| Giga-Byte Technology      | 1        | 0.39%   |
| Focusrite-Novation        | 1        | 0.39%   |
| Bose                      | 1        | 0.39%   |
| Blue Microphones          | 1        | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13       | 4.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 4.33%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13       | 4.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 3.67%   |
| Nvidia GP106 High Definition Audio Controller                              | 10       | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 3%      |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 3%      |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 3%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 2.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 2.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 6        | 2%      |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 2%      |
| Intel 200 Series PCH HD Audio                                              | 6        | 2%      |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 1.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 1.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 1.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 1.67%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.33%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 1.33%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 1.33%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.33%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.33%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 1%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1%      |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 1%      |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1%      |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 3        | 1%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1%      |
| Nvidia High Definition Audio Controller                                    | 2        | 0.67%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.67%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.67%   |
| Logitech G430 Surround Sound Gaming Headset                                | 2        | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 0.67%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 0.67%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 2        | 0.67%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 2        | 0.67%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2        | 0.67%   |
| C-Media Electronics CM106 Like Sound Device                                | 2        | 0.67%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 0.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 0.67%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 0.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2        | 0.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 0.67%   |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1        | 0.33%   |
| Sennheiser Communications Headset [PC 8]                                   | 1        | 0.33%   |
| Samson Technologies Carbon61                                               | 1        | 0.33%   |
| Realtek Semiconductor USB Audio                                            | 1        | 0.33%   |
| OPPO Electronics UDP-205 USB AUDIO 2.0 DAC                                 | 1        | 0.33%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 17       | 20%     |
| Unknown             | 10       | 11.76%  |
| SK hynix            | 10       | 11.76%  |
| Samsung Electronics | 9        | 10.59%  |
| Crucial             | 9        | 10.59%  |
| G.Skill             | 6        | 7.06%   |
| Corsair             | 6        | 7.06%   |
| Team                | 3        | 3.53%   |
| Micron Technology   | 2        | 2.35%   |
| GOODRAM             | 2        | 2.35%   |
| A-DATA Technology   | 2        | 2.35%   |
| Unknown (0x873E)    | 1        | 1.18%   |
| Transcend           | 1        | 1.18%   |
| Timetec             | 1        | 1.18%   |
| Sesame              | 1        | 1.18%   |
| PNY                 | 1        | 1.18%   |
| Nanya Technology    | 1        | 1.18%   |
| Avant               | 1        | 1.18%   |
| Apacer              | 1        | 1.18%   |
| Unknown             | 1        | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                       | 2        | 2.25%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s      | 2        | 2.25%   |
| Kingston RAM 9905403-199.A00LF 4GB DIMM DDR3 1600MT/s      | 2        | 2.25%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s      | 2        | 2.25%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s     | 2        | 2.25%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s               | 1        | 1.12%   |
| Unknown RAM Module 512MB DIMM 533MT/s                      | 1        | 1.12%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 1.12%   |
| Unknown RAM Module 4096MB DIMM DDR 1066MT/s                | 1        | 1.12%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                     | 1        | 1.12%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 1        | 1.12%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                | 1        | 1.12%   |
| Unknown RAM Module 2048MB DIMM DDR 1066MT/s                | 1        | 1.12%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 1        | 1.12%   |
| Unknown RAM Module 1024MB DIMM DDR2                        | 1        | 1.12%   |
| Unknown RAM DDR3 1600 8G 8192MB DIMM DDR3 1600MT/s         | 1        | 1.12%   |
| Unknown (0x873E) RAM Module 8192MB DIMM DDR3 1333MT/s      | 1        | 1.12%   |
| Transcend RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 1.12%   |
| Timetec RAM ED3-1600 8192MB DIMM DDR3 1600MT/s             | 1        | 1.12%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s        | 1        | 1.12%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s         | 1        | 1.12%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                 | 1        | 1.12%   |
| SK hynix RAM Module 4096MB FB-DIMM DDR2 667MT/s            | 1        | 1.12%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                 | 1        | 1.12%   |
| SK hynix RAM Module 1GB DIMM DDR3 1333MT/s                 | 1        | 1.12%   |
| SK hynix RAM Module 1024MB DIMM DDR3 1333MT/s              | 1        | 1.12%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR 667MT/s         | 1        | 1.12%   |
| SK hynix RAM HYMP112U64CP8-Y5 1024MB DIMM DDR2 1639MT/s    | 1        | 1.12%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3                | 1        | 1.12%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s       | 1        | 1.12%   |
| SK hynix RAM HMA81GR7MFR8N-UH 8192MB RIMM DDR4 2400MT/s    | 1        | 1.12%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s       | 1        | 1.12%   |
| Sesame RAM S939A2UGS-ITR 8GB DIMM DDR3 1600MT/s            | 1        | 1.12%   |
| Samsung RAM Module 2GB FB-DIMM DDR2 667MT/s                | 1        | 1.12%   |
| Samsung RAM Module 1GB DIMM DDR3 1333MT/s                  | 1        | 1.12%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s        | 1        | 1.12%   |
| Samsung RAM M391B5673EH1-CF8 2048MB DIMM DDR3 1066MT/s     | 1        | 1.12%   |
| Samsung RAM M391A4G43AB1-CWE 32GB DIMM DDR4 3200MT/s       | 1        | 1.12%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s        | 1        | 1.12%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s     | 1        | 1.12%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s        | 1        | 1.12%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s     | 1        | 1.12%   |
| PNY RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 1.12%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s         | 1        | 1.12%   |
| Micron RAM Module 512MB FB-DIMM DDR2 667MT/s               | 1        | 1.12%   |
| Micron RAM 16JTF51264AZ-1G6M1 4096MB DIMM DDR3 1600MT/s    | 1        | 1.12%   |
| Kingston RAM Module 1GB DIMM DDR3 1333MT/s                 | 1        | 1.12%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s       | 1        | 1.12%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s          | 1        | 1.12%   |
| Kingston RAM KHX2133C11D3/4GX 4GB DIMM DDR3 2134MT/s       | 1        | 1.12%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s        | 1        | 1.12%   |
| Kingston RAM KHX1600C10D3/ 4GB DIMM DDR3 1600MT/s          | 1        | 1.12%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 1.12%   |
| Kingston RAM 99U5471-002.A01LF 2GB DIMM DDR3 1334MT/s      | 1        | 1.12%   |
| Kingston RAM 99U5428-017.A00LF 8192MB SODIMM DDR3 1600MT/s | 1        | 1.12%   |
| Kingston RAM 99U5403-159.A01LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.12%   |
| Kingston RAM 9965525-140.A 8GB DIMM DDR3 667MT/s           | 1        | 1.12%   |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s          | 1        | 1.12%   |
| Kingston RAM 9905471-001.A01LF 2GB DIMM 1600MT/s           | 1        | 1.12%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.12%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 32       | 44.44%  |
| DDR4    | 26       | 36.11%  |
| DDR2    | 6        | 8.33%   |
| SDRAM   | 4        | 5.56%   |
| Unknown | 3        | 4.17%   |
| DDR     | 1        | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 67       | 93.06%  |
| SODIMM  | 2        | 2.78%   |
| FB-DIMM | 2        | 2.78%   |
| RIMM    | 1        | 1.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 28       | 35.9%   |
| 4096  | 19       | 24.36%  |
| 2048  | 12       | 15.38%  |
| 16384 | 9        | 11.54%  |
| 1024  | 5        | 6.41%   |
| 32768 | 3        | 3.85%   |
| 512   | 2        | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 22       | 27.5%   |
| 3200    | 10       | 12.5%   |
| 1333    | 9        | 11.25%  |
| 2400    | 6        | 7.5%    |
| 800     | 4        | 5%      |
| 667     | 4        | 5%      |
| 3600    | 3        | 3.75%   |
| Unknown | 3        | 3.75%   |
| 2667    | 2        | 2.5%    |
| 1800    | 2        | 2.5%    |
| 1066    | 2        | 2.5%    |
| 3500    | 1        | 1.25%   |
| 3466    | 1        | 1.25%   |
| 3007    | 1        | 1.25%   |
| 3000    | 1        | 1.25%   |
| 2933    | 1        | 1.25%   |
| 2666    | 1        | 1.25%   |
| 2134    | 1        | 1.25%   |
| 2048    | 1        | 1.25%   |
| 1866    | 1        | 1.25%   |
| 1639    | 1        | 1.25%   |
| 1334    | 1        | 1.25%   |
| 533     | 1        | 1.25%   |
| 400     | 1        | 1.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 3        | 50%     |
| Sharp           | 1        | 16.67%  |
| Hewlett-Packard | 1        | 16.67%  |
| Fuji Xerox      | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Sharp AL-2030                 | 1        | 16.67%  |
| HP Deskjet 2540 series        | 1        | 16.67%  |
| Fuji Xerox DocuPrint CM305 df | 1        | 16.67%  |
| Canon TR7500 series           | 1        | 16.67%  |
| Canon MF4010 series           | 1        | 16.67%  |
| Canon MF240 Series V4         | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 120 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 13       | 40.63%  |
| Microsoft                     | 3        | 9.38%   |
| Microdia                      | 3        | 9.38%   |
| Generalplus Technology        | 2        | 6.25%   |
| Tobii Technology AB           | 1        | 3.13%   |
| Sunplus Innovation Technology | 1        | 3.13%   |
| Samsung Electronics           | 1        | 3.13%   |
| Realtek Semiconductor         | 1        | 3.13%   |
| OPPO Electronics              | 1        | 3.13%   |
| Linux Foundation              | 1        | 3.13%   |
| LG Electronics                | 1        | 3.13%   |
| IPEVO                         | 1        | 3.13%   |
| Guillemot                     | 1        | 3.13%   |
| Cubeternet                    | 1        | 3.13%   |
| ARC International             | 1        | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920              | 3        | 9.38%   |
| Microsoft LifeCam HD-3000                | 2        | 6.25%   |
| Logitech Webcam C270                     | 2        | 6.25%   |
| Logitech Webcam B500                     | 2        | 6.25%   |
| Tobii AB EyeChip                         | 1        | 3.13%   |
| Sunplus HD 720P webcam                   | 1        | 3.13%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1        | 3.13%   |
| Realtek Web Camera                       | 1        | 3.13%   |
| OPPO Reno4 5G                            | 1        | 3.13%   |
| Microsoft LifeCam Cinema                 | 1        | 3.13%   |
| Microdia USB camera                      | 1        | 3.13%   |
| Microdia Integrated Camera               | 1        | 3.13%   |
| Microdia Camera                          | 1        | 3.13%   |
| Logitech Webcam C925e                    | 1        | 3.13%   |
| Logitech Webcam C170                     | 1        | 3.13%   |
| Logitech QuickCam Pro for Notebooks      | 1        | 3.13%   |
| Logitech Logitech Webcam C160            | 1        | 3.13%   |
| Logitech HD Webcam C910                  | 1        | 3.13%   |
| Logitech B525 HD Webcam                  | 1        | 3.13%   |
| Linux Foundation EEM Gadget              | 1        | 3.13%   |
| LG Optimus (Various Models) MTP Mode     | 1        | 3.13%   |
| IPEVO V4K                                | 1        | 3.13%   |
| Guillemot Hercules HD Sunset             | 1        | 3.13%   |
| Generalplus GENERAL WEBCAM               | 1        | 3.13%   |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 3.13%   |
| Cubeternet GL-UPC822 UVC WebCam          | 1        | 3.13%   |
| ARC International Camera                 | 1        | 3.13%   |

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
| 0     | 136      | 90.07%  |
| 1     | 11       | 7.28%   |
| 9     | 1        | 0.66%   |
| 4     | 1        | 0.66%   |
| 3     | 1        | 0.66%   |
| 2     | 1        | 0.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 31.82%  |
| Net/wireless             | 5        | 22.73%  |
| Sound                    | 3        | 13.64%  |
| Unassigned class         | 2        | 9.09%   |
| Communication controller | 2        | 9.09%   |
| Net/ethernet             | 1        | 4.55%   |
| Camera                   | 1        | 4.55%   |
| Bluetooth                | 1        | 4.55%   |

