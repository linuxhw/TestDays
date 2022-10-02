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

Total: 6121

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A715-41G             | Notebook    | [1a473e9809](https://linux-hardware.org/?probe=1a473e9809) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [9b59ddb3b2](https://linux-hardware.org/?probe=9b59ddb3b2) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [7915b298b2](https://linux-hardware.org/?probe=7915b298b2) | Oct 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [27bb1c39eb](https://linux-hardware.org/?probe=27bb1c39eb) | Oct 01, 2022 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | Notebook    | [fbe1e53387](https://linux-hardware.org/?probe=fbe1e53387) | Oct 01, 2022 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [6dc0730b6a](https://linux-hardware.org/?probe=6dc0730b6a) | Oct 01, 2022 |
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
| Dell          | Vostro 15 5510              | Notebook    | [730653ea29](https://linux-hardware.org/?probe=730653ea29) | Sep 27, 2022 |
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
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [6cdacdb935](https://linux-hardware.org/?probe=6cdacdb935) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | Notebook    | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [0299e4f7b1](https://linux-hardware.org/?probe=0299e4f7b1) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [cad0f6f375](https://linux-hardware.org/?probe=cad0f6f375) | Sep 24, 2022 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [405ea9a4ca](https://linux-hardware.org/?probe=405ea9a4ca) | Sep 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4658ef6703](https://linux-hardware.org/?probe=4658ef6703) | Sep 24, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | Notebook    | [0adb7bc0b1](https://linux-hardware.org/?probe=0adb7bc0b1) | Sep 24, 2022 |
| VIT           | P2402                       | Notebook    | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [91d179670c](https://linux-hardware.org/?probe=91d179670c) | Sep 23, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5f1b4b1679](https://linux-hardware.org/?probe=5f1b4b1679) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [40b47d9065](https://linux-hardware.org/?probe=40b47d9065) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Google        | Garg360                     | Notebook    | [4772493ae3](https://linux-hardware.org/?probe=4772493ae3) | Sep 23, 2022 |
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
| Dell          | Vostro 15 5510              | Notebook    | [5488a2b9ff](https://linux-hardware.org/?probe=5488a2b9ff) | Sep 22, 2022 |
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
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [ae4e13ddc1](https://linux-hardware.org/?probe=ae4e13ddc1) | Sep 19, 2022 |
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
| Dell          | 0KY237 A01                  | Desktop     | [c639777548](https://linux-hardware.org/?probe=c639777548) | Sep 18, 2022 |
| Dell          | 0KY237 A01                  | Desktop     | [8b2d50f5d1](https://linux-hardware.org/?probe=8b2d50f5d1) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [1fa9b05720](https://linux-hardware.org/?probe=1fa9b05720) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| Lenovo        | IdeaPad 720s-13ARR 81BR     | Notebook    | [fa45602fc5](https://linux-hardware.org/?probe=fa45602fc5) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [b94564300a](https://linux-hardware.org/?probe=b94564300a) | Sep 18, 2022 |
| Dell          | Latitude E6330              | Notebook    | [bbb0a5f1a1](https://linux-hardware.org/?probe=bbb0a5f1a1) | Sep 18, 2022 |
| Dell          | Latitude E6330              | Notebook    | [8ddda1480b](https://linux-hardware.org/?probe=8ddda1480b) | Sep 18, 2022 |
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
| Dell          | Latitude E6330              | Notebook    | [eb58d87a1d](https://linux-hardware.org/?probe=eb58d87a1d) | Sep 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [a5b11eaaaf](https://linux-hardware.org/?probe=a5b11eaaaf) | Sep 17, 2022 |
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
| Gigabyte      | EP45T-UD3R                  | Desktop     | [04a99c2508](https://linux-hardware.org/?probe=04a99c2508) | Sep 16, 2022 |
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
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d2a3eb186f](https://linux-hardware.org/?probe=d2a3eb186f) | Sep 15, 2022 |
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
| Positivo      | Mobile                      | Notebook    | [ef02cc05aa](https://linux-hardware.org/?probe=ef02cc05aa) | Sep 15, 2022 |
| INFINITY      | Unknown                     | Notebook    | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| HP            | 876C SMVB                   | Desktop     | [adc81b2fd5](https://linux-hardware.org/?probe=adc81b2fd5) | Sep 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [5bdc2b7041](https://linux-hardware.org/?probe=5bdc2b7041) | Sep 14, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [af4b9d7add](https://linux-hardware.org/?probe=af4b9d7add) | Sep 14, 2022 |
| Google        | Terra                       | Notebook    | [9dae30736d](https://linux-hardware.org/?probe=9dae30736d) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [01d92ffc28](https://linux-hardware.org/?probe=01d92ffc28) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [c04d19fe27](https://linux-hardware.org/?probe=c04d19fe27) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [ad0ac85a1c](https://linux-hardware.org/?probe=ad0ac85a1c) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [6cb46b9558](https://linux-hardware.org/?probe=6cb46b9558) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [bec6da09ae](https://linux-hardware.org/?probe=bec6da09ae) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [0366b6294c](https://linux-hardware.org/?probe=0366b6294c) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [a914907c0f](https://linux-hardware.org/?probe=a914907c0f) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [662117584a](https://linux-hardware.org/?probe=662117584a) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [272b6ec971](https://linux-hardware.org/?probe=272b6ec971) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [2528bbb7ac](https://linux-hardware.org/?probe=2528bbb7ac) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [212a063241](https://linux-hardware.org/?probe=212a063241) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [2b6d3fc6f0](https://linux-hardware.org/?probe=2b6d3fc6f0) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [9bc2776801](https://linux-hardware.org/?probe=9bc2776801) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [4048396126](https://linux-hardware.org/?probe=4048396126) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [7036d4bc55](https://linux-hardware.org/?probe=7036d4bc55) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [e4147da882](https://linux-hardware.org/?probe=e4147da882) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [f85ab5e109](https://linux-hardware.org/?probe=f85ab5e109) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [8fb883495e](https://linux-hardware.org/?probe=8fb883495e) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [2c51e9e9c2](https://linux-hardware.org/?probe=2c51e9e9c2) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [54a3f9eec9](https://linux-hardware.org/?probe=54a3f9eec9) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [3760a35f01](https://linux-hardware.org/?probe=3760a35f01) | Sep 14, 2022 |
| Dell          | Precision 3571              | Notebook    | [72e1a27ea7](https://linux-hardware.org/?probe=72e1a27ea7) | Sep 14, 2022 |
| HP            | 876C SMVB                   | Desktop     | [347ab44533](https://linux-hardware.org/?probe=347ab44533) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [7927c44ef0](https://linux-hardware.org/?probe=7927c44ef0) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [eaa0e46c9f](https://linux-hardware.org/?probe=eaa0e46c9f) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8935b3f204](https://linux-hardware.org/?probe=8935b3f204) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [a904acc9e9](https://linux-hardware.org/?probe=a904acc9e9) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [7f883700cf](https://linux-hardware.org/?probe=7f883700cf) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [8ef03a6208](https://linux-hardware.org/?probe=8ef03a6208) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [c3f844b853](https://linux-hardware.org/?probe=c3f844b853) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [0a77a87395](https://linux-hardware.org/?probe=0a77a87395) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [344bf802ef](https://linux-hardware.org/?probe=344bf802ef) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [6be4965b4d](https://linux-hardware.org/?probe=6be4965b4d) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [f627c1d051](https://linux-hardware.org/?probe=f627c1d051) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [67eca2e394](https://linux-hardware.org/?probe=67eca2e394) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [8c8644f284](https://linux-hardware.org/?probe=8c8644f284) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [09ca233ab5](https://linux-hardware.org/?probe=09ca233ab5) | Sep 14, 2022 |
| Dell          | Latitude E7250              | Notebook    | [80a2e50cfc](https://linux-hardware.org/?probe=80a2e50cfc) | Sep 14, 2022 |
| Aquarius      | NS585                       | Notebook    | [df1a5c5ca1](https://linux-hardware.org/?probe=df1a5c5ca1) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | Notebook    | [b8665b7aed](https://linux-hardware.org/?probe=b8665b7aed) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [e65b9d439e](https://linux-hardware.org/?probe=e65b9d439e) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | Notebook    | [22c2adf69b](https://linux-hardware.org/?probe=22c2adf69b) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | Notebook    | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [8ec7217b7d](https://linux-hardware.org/?probe=8ec7217b7d) | Sep 14, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [c8994c7912](https://linux-hardware.org/?probe=c8994c7912) | Sep 14, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [c3b834caec](https://linux-hardware.org/?probe=c3b834caec) | Sep 14, 2022 |
| Google        | Terra                       | Notebook    | [a7150f06c7](https://linux-hardware.org/?probe=a7150f06c7) | Sep 13, 2022 |
| Lenovo        | SHARKBAY 0C48431 WIN        | Desktop     | [4598920e84](https://linux-hardware.org/?probe=4598920e84) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| HP            | 876C SMVB                   | Desktop     | [61df16cfc9](https://linux-hardware.org/?probe=61df16cfc9) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| Aquarius      | NS585                       | Notebook    | [f76497447f](https://linux-hardware.org/?probe=f76497447f) | Sep 13, 2022 |
| HP            | 876C SMVB                   | Desktop     | [15ec81ce9d](https://linux-hardware.org/?probe=15ec81ce9d) | Sep 13, 2022 |
| Aquarius      | NS585                       | Notebook    | [0adf35b80f](https://linux-hardware.org/?probe=0adf35b80f) | Sep 13, 2022 |
| Aquarius      | NS585                       | Notebook    | [042a81998b](https://linux-hardware.org/?probe=042a81998b) | Sep 13, 2022 |
| Aquarius      | NS585                       | Notebook    | [e5078cd5f4](https://linux-hardware.org/?probe=e5078cd5f4) | Sep 13, 2022 |
| Biostar       | NF560-A2G                   | Desktop     | [96c296c2f3](https://linux-hardware.org/?probe=96c296c2f3) | Sep 13, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [e63dd14c21](https://linux-hardware.org/?probe=e63dd14c21) | Sep 13, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [16942cfd78](https://linux-hardware.org/?probe=16942cfd78) | Sep 13, 2022 |
| Aquarius      | NS585                       | Notebook    | [adb7dadad9](https://linux-hardware.org/?probe=adb7dadad9) | Sep 13, 2022 |
| ASRock        | H470M-HDV                   | Desktop     | [41977548bc](https://linux-hardware.org/?probe=41977548bc) | Sep 13, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [47ff6a8255](https://linux-hardware.org/?probe=47ff6a8255) | Sep 13, 2022 |
| Positivo      | POS-EINM10CB POSITIVO       | Desktop     | [7c876e560b](https://linux-hardware.org/?probe=7c876e560b) | Sep 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fcbe85674b](https://linux-hardware.org/?probe=fcbe85674b) | Sep 13, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [7acd0e62aa](https://linux-hardware.org/?probe=7acd0e62aa) | Sep 12, 2022 |
| Google        | Terra                       | Notebook    | [6b591d8c39](https://linux-hardware.org/?probe=6b591d8c39) | Sep 12, 2022 |
| Google        | Terra                       | Notebook    | [b3993f460f](https://linux-hardware.org/?probe=b3993f460f) | Sep 12, 2022 |
| HP            | 8464                        | Desktop     | [fcc16a5a56](https://linux-hardware.org/?probe=fcc16a5a56) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | Notebook    | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [31ca5d0add](https://linux-hardware.org/?probe=31ca5d0add) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d76d427a61](https://linux-hardware.org/?probe=d76d427a61) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [c996d652d3](https://linux-hardware.org/?probe=c996d652d3) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d08cb8e35b](https://linux-hardware.org/?probe=d08cb8e35b) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [0c2d66313e](https://linux-hardware.org/?probe=0c2d66313e) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [5461cdbf3b](https://linux-hardware.org/?probe=5461cdbf3b) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [c055d82971](https://linux-hardware.org/?probe=c055d82971) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [8c0d419ac8](https://linux-hardware.org/?probe=8c0d419ac8) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| Google        | Reks                        | Notebook    | [28f0932e1a](https://linux-hardware.org/?probe=28f0932e1a) | Sep 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2af6edb7a0](https://linux-hardware.org/?probe=2af6edb7a0) | Sep 12, 2022 |
| ASUSTek       | G20CB                       | Desktop     | [a52ff97f3b](https://linux-hardware.org/?probe=a52ff97f3b) | Sep 12, 2022 |
| ASUSTek       | G20CB                       | Desktop     | [2d737743f4](https://linux-hardware.org/?probe=2d737743f4) | Sep 12, 2022 |
| Lenovo        | ThinkPad X240 20AL00ETGE    | Notebook    | [95a3df06c9](https://linux-hardware.org/?probe=95a3df06c9) | Sep 12, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| MSI           | GS60 2PE                    | Notebook    | [0164cbee91](https://linux-hardware.org/?probe=0164cbee91) | Sep 12, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [e8da6da2b0](https://linux-hardware.org/?probe=e8da6da2b0) | Sep 12, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [613f741235](https://linux-hardware.org/?probe=613f741235) | Sep 12, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [09d0fcce0e](https://linux-hardware.org/?probe=09d0fcce0e) | Sep 12, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [3a6e62d846](https://linux-hardware.org/?probe=3a6e62d846) | Sep 12, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [c18f89b2bb](https://linux-hardware.org/?probe=c18f89b2bb) | Sep 11, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [e007728e0a](https://linux-hardware.org/?probe=e007728e0a) | Sep 11, 2022 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [5987ef39e4](https://linux-hardware.org/?probe=5987ef39e4) | Sep 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [cd49377ddf](https://linux-hardware.org/?probe=cd49377ddf) | Sep 11, 2022 |
| HP            | G42                         | Notebook    | [092b9e2c38](https://linux-hardware.org/?probe=092b9e2c38) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [21ae14e7a0](https://linux-hardware.org/?probe=21ae14e7a0) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [3ddd0d7aa0](https://linux-hardware.org/?probe=3ddd0d7aa0) | Sep 11, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [a683b361e4](https://linux-hardware.org/?probe=a683b361e4) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [cca78f4488](https://linux-hardware.org/?probe=cca78f4488) | Sep 11, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7aad54fefa](https://linux-hardware.org/?probe=7aad54fefa) | Sep 11, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [9cbf9fdc4a](https://linux-hardware.org/?probe=9cbf9fdc4a) | Sep 11, 2022 |
| Lenovo        | ThinkPad L460 20FVS1BC0S    | Notebook    | [e668edf31d](https://linux-hardware.org/?probe=e668edf31d) | Sep 11, 2022 |
| HP            | 84DE                        | All in one  | [cdb6233482](https://linux-hardware.org/?probe=cdb6233482) | Sep 10, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [41b9796681](https://linux-hardware.org/?probe=41b9796681) | Sep 10, 2022 |
| HP            | 1998                        | Desktop     | [37cd896e72](https://linux-hardware.org/?probe=37cd896e72) | Sep 10, 2022 |
| HP            | 1998                        | Desktop     | [3da9c3ef8e](https://linux-hardware.org/?probe=3da9c3ef8e) | Sep 10, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [9768e1fbf4](https://linux-hardware.org/?probe=9768e1fbf4) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5a7c8dfacf](https://linux-hardware.org/?probe=5a7c8dfacf) | Sep 10, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [cf028f9b8c](https://linux-hardware.org/?probe=cf028f9b8c) | Sep 10, 2022 |
| Google        | Treeya                      | Notebook    | [d7a00caa63](https://linux-hardware.org/?probe=d7a00caa63) | Sep 10, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [b8a5448c05](https://linux-hardware.org/?probe=b8a5448c05) | Sep 10, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [2f4b4e4203](https://linux-hardware.org/?probe=2f4b4e4203) | Sep 10, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | Desktop     | [102cf248e9](https://linux-hardware.org/?probe=102cf248e9) | Sep 10, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [6a4fa8ebe7](https://linux-hardware.org/?probe=6a4fa8ebe7) | Sep 09, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [965f8fe14d](https://linux-hardware.org/?probe=965f8fe14d) | Sep 09, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [70c2613095](https://linux-hardware.org/?probe=70c2613095) | Sep 09, 2022 |
| Acer          | AO532h                      | Notebook    | [3ea8a4ba38](https://linux-hardware.org/?probe=3ea8a4ba38) | Sep 09, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Biostar       | NF560-A2G                   | Desktop     | [68ffa42095](https://linux-hardware.org/?probe=68ffa42095) | Sep 09, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [4f0ec780ee](https://linux-hardware.org/?probe=4f0ec780ee) | Sep 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e4d2c1c120](https://linux-hardware.org/?probe=e4d2c1c120) | Sep 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d28677add3](https://linux-hardware.org/?probe=d28677add3) | Sep 09, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [2557dd83ce](https://linux-hardware.org/?probe=2557dd83ce) | Sep 09, 2022 |
| Dell          | Latitude E6330              | Notebook    | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c008fc6206](https://linux-hardware.org/?probe=c008fc6206) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [92ae6811fa](https://linux-hardware.org/?probe=92ae6811fa) | Sep 09, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [d37b0f4483](https://linux-hardware.org/?probe=d37b0f4483) | Sep 08, 2022 |
| ASRock        | Q1900M                      | Desktop     | [aadbe54f8d](https://linux-hardware.org/?probe=aadbe54f8d) | Sep 08, 2022 |
| HP            | ProLiant DL585 G7           | Server      | [1dbd0517e3](https://linux-hardware.org/?probe=1dbd0517e3) | Sep 08, 2022 |
| HP            | ProLiant DL585 G7           | Server      | [1f46338236](https://linux-hardware.org/?probe=1f46338236) | Sep 08, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [c8f2e1da45](https://linux-hardware.org/?probe=c8f2e1da45) | Sep 08, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [17675b7bc8](https://linux-hardware.org/?probe=17675b7bc8) | Sep 08, 2022 |
| Google        | Reks                        | Notebook    | [a171b11595](https://linux-hardware.org/?probe=a171b11595) | Sep 08, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [478d0564a6](https://linux-hardware.org/?probe=478d0564a6) | Sep 08, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [1c48e52b18](https://linux-hardware.org/?probe=1c48e52b18) | Sep 08, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [141712c674](https://linux-hardware.org/?probe=141712c674) | Sep 07, 2022 |
| Lenovo        | B570e 521524G               | Notebook    | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c75460abba](https://linux-hardware.org/?probe=c75460abba) | Sep 07, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c65eb0b5c8](https://linux-hardware.org/?probe=c65eb0b5c8) | Sep 07, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [044bee5e0c](https://linux-hardware.org/?probe=044bee5e0c) | Sep 07, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [b090ccb8fe](https://linux-hardware.org/?probe=b090ccb8fe) | Sep 07, 2022 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [6949fd04b7](https://linux-hardware.org/?probe=6949fd04b7) | Sep 07, 2022 |
| ASUSTek       | X99-E WS                    | Desktop     | [fcf815d38f](https://linux-hardware.org/?probe=fcf815d38f) | Sep 07, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [754b9daf74](https://linux-hardware.org/?probe=754b9daf74) | Sep 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [c0e98bf9e5](https://linux-hardware.org/?probe=c0e98bf9e5) | Sep 06, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [e3d0a2c84c](https://linux-hardware.org/?probe=e3d0a2c84c) | Sep 06, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [9012dd4a5d](https://linux-hardware.org/?probe=9012dd4a5d) | Sep 06, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [92af2339e3](https://linux-hardware.org/?probe=92af2339e3) | Sep 06, 2022 |
| Aquarius      | NS585                       | Notebook    | [74e50c07d8](https://linux-hardware.org/?probe=74e50c07d8) | Sep 06, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5ed6ed5f28](https://linux-hardware.org/?probe=5ed6ed5f28) | Sep 06, 2022 |
| ECS           | G31T-M9                     | Desktop     | [5005d8382e](https://linux-hardware.org/?probe=5005d8382e) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [f7b09fb3e3](https://linux-hardware.org/?probe=f7b09fb3e3) | Sep 06, 2022 |
| HP            | ENVY 17                     | Notebook    | [63411dc061](https://linux-hardware.org/?probe=63411dc061) | Sep 06, 2022 |
| Lenovo        | ThinkPad P51s 20HB000URT    | Notebook    | [8214e1ba30](https://linux-hardware.org/?probe=8214e1ba30) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | Notebook    | [fefa3f4935](https://linux-hardware.org/?probe=fefa3f4935) | Sep 06, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dacafc4729](https://linux-hardware.org/?probe=dacafc4729) | Sep 06, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [b76e5a62e8](https://linux-hardware.org/?probe=b76e5a62e8) | Sep 06, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [1020dfb637](https://linux-hardware.org/?probe=1020dfb637) | Sep 06, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | Desktop     | [2c5b0be3af](https://linux-hardware.org/?probe=2c5b0be3af) | Sep 06, 2022 |
| Dell          | Latitude 5530               | Notebook    | [4a2fb0c4c2](https://linux-hardware.org/?probe=4a2fb0c4c2) | Sep 06, 2022 |
| Dell          | Latitude 5530               | Notebook    | [a0896a063c](https://linux-hardware.org/?probe=a0896a063c) | Sep 06, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [b10937286d](https://linux-hardware.org/?probe=b10937286d) | Sep 06, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [4071a8ff9b](https://linux-hardware.org/?probe=4071a8ff9b) | Sep 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [312e33b434](https://linux-hardware.org/?probe=312e33b434) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [6bd37547d3](https://linux-hardware.org/?probe=6bd37547d3) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [5df6bc21c7](https://linux-hardware.org/?probe=5df6bc21c7) | Sep 05, 2022 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [4c68e17f1a](https://linux-hardware.org/?probe=4c68e17f1a) | Sep 05, 2022 |
| Dell          | 0N36HY A06                  | Server      | [ad80e5c56d](https://linux-hardware.org/?probe=ad80e5c56d) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e6117fb016](https://linux-hardware.org/?probe=e6117fb016) | Sep 05, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [beb1aeb4ad](https://linux-hardware.org/?probe=beb1aeb4ad) | Sep 05, 2022 |
| HP            | 805D                        | Desktop     | [fdf50a9e36](https://linux-hardware.org/?probe=fdf50a9e36) | Sep 05, 2022 |
| Acer          | Aspire A517-52G             | Notebook    | [c1709e40b7](https://linux-hardware.org/?probe=c1709e40b7) | Sep 05, 2022 |
| Dell          | 06FW8P A00                  | Desktop     | [6023e5aa76](https://linux-hardware.org/?probe=6023e5aa76) | Sep 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [efb1e9883d](https://linux-hardware.org/?probe=efb1e9883d) | Sep 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [20178af23f](https://linux-hardware.org/?probe=20178af23f) | Sep 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f44a7ef51c](https://linux-hardware.org/?probe=f44a7ef51c) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [f85aa66b33](https://linux-hardware.org/?probe=f85aa66b33) | Sep 04, 2022 |
| Dell          | 0N36HY A06                  | Server      | [e50147dafa](https://linux-hardware.org/?probe=e50147dafa) | Sep 04, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [b9f3857d65](https://linux-hardware.org/?probe=b9f3857d65) | Sep 04, 2022 |
| Dell          | Latitude E6330              | Notebook    | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| ASRock        | Q1900M                      | Desktop     | [55a86f60b9](https://linux-hardware.org/?probe=55a86f60b9) | Sep 04, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [ea93dfd855](https://linux-hardware.org/?probe=ea93dfd855) | Sep 04, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [fe5c97cc44](https://linux-hardware.org/?probe=fe5c97cc44) | Sep 04, 2022 |
| Hardkernel    | ODROID-U3 board based on... | Soc         | [04b62e9eb2](https://linux-hardware.org/?probe=04b62e9eb2) | Sep 04, 2022 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [8ffe312747](https://linux-hardware.org/?probe=8ffe312747) | Sep 04, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [438d359ee9](https://linux-hardware.org/?probe=438d359ee9) | Sep 04, 2022 |
| AZW           | SER                         | Mini pc     | [2c0baab61c](https://linux-hardware.org/?probe=2c0baab61c) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 232438J       | Notebook    | [dca0e2fa77](https://linux-hardware.org/?probe=dca0e2fa77) | Sep 04, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [eb29524a90](https://linux-hardware.org/?probe=eb29524a90) | Sep 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [3a599be2f2](https://linux-hardware.org/?probe=3a599be2f2) | Sep 03, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [082520f2d8](https://linux-hardware.org/?probe=082520f2d8) | Sep 03, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| PC Special... | 14 Fusion IV                | Notebook    | [dd9ed93b55](https://linux-hardware.org/?probe=dd9ed93b55) | Sep 03, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9b8eef74b8](https://linux-hardware.org/?probe=9b8eef74b8) | Sep 03, 2022 |
| HP            | Compaq 6910p                | Notebook    | [0165c7d3c6](https://linux-hardware.org/?probe=0165c7d3c6) | Sep 03, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [5c0b32f572](https://linux-hardware.org/?probe=5c0b32f572) | Sep 03, 2022 |
| Aquarius      | NS585                       | Notebook    | [b11a34556d](https://linux-hardware.org/?probe=b11a34556d) | Sep 03, 2022 |
| Dell          | Latitude E6330              | Notebook    | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | Notebook    | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [9a2200f8f8](https://linux-hardware.org/?probe=9a2200f8f8) | Sep 03, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [0be6c5963d](https://linux-hardware.org/?probe=0be6c5963d) | Sep 02, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [262c6222d1](https://linux-hardware.org/?probe=262c6222d1) | Sep 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [acdd27f635](https://linux-hardware.org/?probe=acdd27f635) | Sep 02, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [3870423379](https://linux-hardware.org/?probe=3870423379) | Sep 02, 2022 |
| Pine Micro... | Pine64+                     | Soc         | [dc7e6f17d4](https://linux-hardware.org/?probe=dc7e6f17d4) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [c8bf09dd8d](https://linux-hardware.org/?probe=c8bf09dd8d) | Sep 02, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [11f9e9fa68](https://linux-hardware.org/?probe=11f9e9fa68) | Sep 02, 2022 |
| Aquarius      | NS585                       | Notebook    | [86de3c4954](https://linux-hardware.org/?probe=86de3c4954) | Sep 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f42a136e4f](https://linux-hardware.org/?probe=f42a136e4f) | Sep 02, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [e9f6cafc6c](https://linux-hardware.org/?probe=e9f6cafc6c) | Sep 02, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [277340da8a](https://linux-hardware.org/?probe=277340da8a) | Sep 02, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [6c7b47158f](https://linux-hardware.org/?probe=6c7b47158f) | Sep 02, 2022 |
| Google        | Enguarde                    | Notebook    | [50369de0be](https://linux-hardware.org/?probe=50369de0be) | Sep 01, 2022 |
| Dell          | Latitude E6330              | Notebook    | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [b59a9615cd](https://linux-hardware.org/?probe=b59a9615cd) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [7acc7436b0](https://linux-hardware.org/?probe=7acc7436b0) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [671a062f6e](https://linux-hardware.org/?probe=671a062f6e) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [baabafd42b](https://linux-hardware.org/?probe=baabafd42b) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [4c1595c83e](https://linux-hardware.org/?probe=4c1595c83e) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [bb6b28b279](https://linux-hardware.org/?probe=bb6b28b279) | Sep 01, 2022 |
| Google        | Terra                       | Notebook    | [b7940ab738](https://linux-hardware.org/?probe=b7940ab738) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [0cbe57b975](https://linux-hardware.org/?probe=0cbe57b975) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [9f20842cc5](https://linux-hardware.org/?probe=9f20842cc5) | Sep 01, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [bc316a8d3f](https://linux-hardware.org/?probe=bc316a8d3f) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [06969489cc](https://linux-hardware.org/?probe=06969489cc) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [2b4231258e](https://linux-hardware.org/?probe=2b4231258e) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [1a0596c60d](https://linux-hardware.org/?probe=1a0596c60d) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [4dfdb5e364](https://linux-hardware.org/?probe=4dfdb5e364) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [c6db81251c](https://linux-hardware.org/?probe=c6db81251c) | Sep 01, 2022 |
| Google        | Enguarde                    | Notebook    | [05f112ddb7](https://linux-hardware.org/?probe=05f112ddb7) | Sep 01, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [1c58d69316](https://linux-hardware.org/?probe=1c58d69316) | Sep 01, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [e14cc69370](https://linux-hardware.org/?probe=e14cc69370) | Sep 01, 2022 |
| MSI           | H81M-P33                    | Desktop     | [8d15799ff9](https://linux-hardware.org/?probe=8d15799ff9) | Sep 01, 2022 |
| HP            | ProLiant DL165 G7           | Server      | [3955b91269](https://linux-hardware.org/?probe=3955b91269) | Sep 01, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [b226dd8bc2](https://linux-hardware.org/?probe=b226dd8bc2) | Sep 01, 2022 |
| HP            | ProLiant DL165 G7           | Server      | [3148482797](https://linux-hardware.org/?probe=3148482797) | Sep 01, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [10dd5d1e15](https://linux-hardware.org/?probe=10dd5d1e15) | Sep 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ad36524b16](https://linux-hardware.org/?probe=ad36524b16) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| ASUSTek       | UX550VD                     | Notebook    | [a43d53b3b7](https://linux-hardware.org/?probe=a43d53b3b7) | Sep 01, 2022 |
| HP            | 871A                        | Mini pc     | [d6261d6fb1](https://linux-hardware.org/?probe=d6261d6fb1) | Sep 01, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [7277e72eb4](https://linux-hardware.org/?probe=7277e72eb4) | Aug 31, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8e8a47df1b](https://linux-hardware.org/?probe=8e8a47df1b) | Aug 31, 2022 |
| Google        | Enguarde                    | Notebook    | [4a240c438e](https://linux-hardware.org/?probe=4a240c438e) | Aug 31, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [0c62d097f0](https://linux-hardware.org/?probe=0c62d097f0) | Aug 31, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [7931f65300](https://linux-hardware.org/?probe=7931f65300) | Aug 31, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d0fd41cd07](https://linux-hardware.org/?probe=d0fd41cd07) | Aug 31, 2022 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [3d2275b1f9](https://linux-hardware.org/?probe=3d2275b1f9) | Aug 31, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [38306e56ae](https://linux-hardware.org/?probe=38306e56ae) | Aug 31, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [28fbbd943e](https://linux-hardware.org/?probe=28fbbd943e) | Aug 31, 2022 |
| AZW           | SER                         | Mini pc     | [4ac98abc0e](https://linux-hardware.org/?probe=4ac98abc0e) | Aug 31, 2022 |
| Dell          | Latitude E6330              | Notebook    | [b5766d41fa](https://linux-hardware.org/?probe=b5766d41fa) | Aug 31, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [29b9669488](https://linux-hardware.org/?probe=29b9669488) | Aug 31, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [c0a39342c3](https://linux-hardware.org/?probe=c0a39342c3) | Aug 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [e9386667fa](https://linux-hardware.org/?probe=e9386667fa) | Aug 31, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [9c9e1d1ff1](https://linux-hardware.org/?probe=9c9e1d1ff1) | Aug 31, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [688dcf88c9](https://linux-hardware.org/?probe=688dcf88c9) | Aug 30, 2022 |
| HP            | Compaq 8510w                | Notebook    | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [4ccef99860](https://linux-hardware.org/?probe=4ccef99860) | Aug 30, 2022 |
| Google        | Enguarde                    | Notebook    | [7aa44db561](https://linux-hardware.org/?probe=7aa44db561) | Aug 30, 2022 |
| Dell          | 0WG864                      | Desktop     | [234e8953bc](https://linux-hardware.org/?probe=234e8953bc) | Aug 30, 2022 |
| HP            | Compaq nc6400 (RU626ET#A... | Notebook    | [e94cb8e943](https://linux-hardware.org/?probe=e94cb8e943) | Aug 30, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [354c669532](https://linux-hardware.org/?probe=354c669532) | Aug 30, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [c89b1e69f4](https://linux-hardware.org/?probe=c89b1e69f4) | Aug 30, 2022 |
| Google        | Reks                        | Notebook    | [71f6228c3d](https://linux-hardware.org/?probe=71f6228c3d) | Aug 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [16b07a7497](https://linux-hardware.org/?probe=16b07a7497) | Aug 30, 2022 |
| Google        | Reks                        | Notebook    | [48174b01b3](https://linux-hardware.org/?probe=48174b01b3) | Aug 30, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [f9a9be3a35](https://linux-hardware.org/?probe=f9a9be3a35) | Aug 30, 2022 |
| Google        | Terra                       | Notebook    | [25f50ae6d9](https://linux-hardware.org/?probe=25f50ae6d9) | Aug 30, 2022 |
| Google        | Reks                        | Notebook    | [e768a1940e](https://linux-hardware.org/?probe=e768a1940e) | Aug 30, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [28f3abde34](https://linux-hardware.org/?probe=28f3abde34) | Aug 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [cfd6369e5a](https://linux-hardware.org/?probe=cfd6369e5a) | Aug 30, 2022 |
| Fujitsu       | D3348-B1 S26361-D3348-B1    | Desktop     | [9721d1f81d](https://linux-hardware.org/?probe=9721d1f81d) | Aug 30, 2022 |
| Lenovo        | ThinkPad L490 20Q5001YPB    | Notebook    | [daae538154](https://linux-hardware.org/?probe=daae538154) | Aug 30, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [ca01260ab8](https://linux-hardware.org/?probe=ca01260ab8) | Aug 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [251b320d54](https://linux-hardware.org/?probe=251b320d54) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c917d8e9ee](https://linux-hardware.org/?probe=c917d8e9ee) | Aug 29, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d2690990ee](https://linux-hardware.org/?probe=d2690990ee) | Aug 29, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [30b240a3fe](https://linux-hardware.org/?probe=30b240a3fe) | Aug 29, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ded0b0e3f9](https://linux-hardware.org/?probe=ded0b0e3f9) | Aug 29, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [fd6324377f](https://linux-hardware.org/?probe=fd6324377f) | Aug 29, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5a8b177558](https://linux-hardware.org/?probe=5a8b177558) | Aug 29, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c96457b375](https://linux-hardware.org/?probe=c96457b375) | Aug 29, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [12ec01d9fb](https://linux-hardware.org/?probe=12ec01d9fb) | Aug 29, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [ddc175428b](https://linux-hardware.org/?probe=ddc175428b) | Aug 29, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3191045f89](https://linux-hardware.org/?probe=3191045f89) | Aug 29, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4c62620474](https://linux-hardware.org/?probe=4c62620474) | Aug 29, 2022 |
| Dell          | Latitude 5590               | Notebook    | [e06f40dae9](https://linux-hardware.org/?probe=e06f40dae9) | Aug 29, 2022 |
| Acer          | TravelMate P215-53          | Notebook    | [4ba2e9fbba](https://linux-hardware.org/?probe=4ba2e9fbba) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [fd4ab67b77](https://linux-hardware.org/?probe=fd4ab67b77) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [4d1df25a9f](https://linux-hardware.org/?probe=4d1df25a9f) | Aug 29, 2022 |
| ASUSTek       | K55VM                       | Notebook    | [ec5806d544](https://linux-hardware.org/?probe=ec5806d544) | Aug 29, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | Notebook    | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [dff587f11e](https://linux-hardware.org/?probe=dff587f11e) | Aug 28, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [f17bcbfc4b](https://linux-hardware.org/?probe=f17bcbfc4b) | Aug 28, 2022 |
| Dell          | Latitude 5420               | Notebook    | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [4960a57d91](https://linux-hardware.org/?probe=4960a57d91) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | Notebook    | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [859b3cb78a](https://linux-hardware.org/?probe=859b3cb78a) | Aug 28, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | Notebook    | [a10cbdb73b](https://linux-hardware.org/?probe=a10cbdb73b) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | Notebook    | [562d827323](https://linux-hardware.org/?probe=562d827323) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c155c4b324](https://linux-hardware.org/?probe=c155c4b324) | Aug 27, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6398be9a3e](https://linux-hardware.org/?probe=6398be9a3e) | Aug 27, 2022 |
| HP            | Compaq 6910p                | Notebook    | [894b5297c8](https://linux-hardware.org/?probe=894b5297c8) | Aug 27, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e0fedafd62](https://linux-hardware.org/?probe=e0fedafd62) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8231da35ed](https://linux-hardware.org/?probe=8231da35ed) | Aug 27, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2KU0... | Notebook    | [6500c142f5](https://linux-hardware.org/?probe=6500c142f5) | Aug 27, 2022 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [186a63fa9e](https://linux-hardware.org/?probe=186a63fa9e) | Aug 27, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [c3d134ca75](https://linux-hardware.org/?probe=c3d134ca75) | Aug 27, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [3c63953ca6](https://linux-hardware.org/?probe=3c63953ca6) | Aug 27, 2022 |
| Medion        | Akoya P2213T                | Notebook    | [c8d10c3b3f](https://linux-hardware.org/?probe=c8d10c3b3f) | Aug 27, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [915f3e44cd](https://linux-hardware.org/?probe=915f3e44cd) | Aug 26, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [fbfc58655a](https://linux-hardware.org/?probe=fbfc58655a) | Aug 26, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b02644baa9](https://linux-hardware.org/?probe=b02644baa9) | Aug 26, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [33c08b0444](https://linux-hardware.org/?probe=33c08b0444) | Aug 26, 2022 |
| Google        | Terra                       | Notebook    | [717b3cc17f](https://linux-hardware.org/?probe=717b3cc17f) | Aug 26, 2022 |
| Google        | Terra                       | Notebook    | [f9856d813e](https://linux-hardware.org/?probe=f9856d813e) | Aug 26, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [5351e31366](https://linux-hardware.org/?probe=5351e31366) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [7728612d53](https://linux-hardware.org/?probe=7728612d53) | Aug 26, 2022 |
| Lenovo        | ThinkPad T590 20N4001NUS    | Notebook    | [479ef1a89c](https://linux-hardware.org/?probe=479ef1a89c) | Aug 26, 2022 |
| ASUSTek       | M70Vn                       | Notebook    | [2e84d460f5](https://linux-hardware.org/?probe=2e84d460f5) | Aug 26, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fd644a3651](https://linux-hardware.org/?probe=fd644a3651) | Aug 26, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c7675aa2e6](https://linux-hardware.org/?probe=c7675aa2e6) | Aug 26, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [12bee9bc64](https://linux-hardware.org/?probe=12bee9bc64) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [ee6cec5f61](https://linux-hardware.org/?probe=ee6cec5f61) | Aug 26, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [73c598ebe7](https://linux-hardware.org/?probe=73c598ebe7) | Aug 26, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [5d4e41a441](https://linux-hardware.org/?probe=5d4e41a441) | Aug 26, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [8418a8e83c](https://linux-hardware.org/?probe=8418a8e83c) | Aug 26, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [2a3114af33](https://linux-hardware.org/?probe=2a3114af33) | Aug 26, 2022 |
| ASUSTek       | IPN73-BA                    | Desktop     | [89f8b175e2](https://linux-hardware.org/?probe=89f8b175e2) | Aug 26, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [46efca142c](https://linux-hardware.org/?probe=46efca142c) | Aug 26, 2022 |
| Lenovo        | ThinkPad T400 2768BM2       | Notebook    | [f2d91055c9](https://linux-hardware.org/?probe=f2d91055c9) | Aug 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | Notebook    | [a624a45cda](https://linux-hardware.org/?probe=a624a45cda) | Aug 26, 2022 |
| Dell          | 0K7CVF A03                  | Server      | [e4ead551b7](https://linux-hardware.org/?probe=e4ead551b7) | Aug 26, 2022 |
| HP            | 18E5                        | Desktop     | [9196bf639b](https://linux-hardware.org/?probe=9196bf639b) | Aug 26, 2022 |
| Lenovo        | 7033EW4                     | Desktop     | [54417ae55f](https://linux-hardware.org/?probe=54417ae55f) | Aug 26, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [84b14ba399](https://linux-hardware.org/?probe=84b14ba399) | Aug 26, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [5769de3299](https://linux-hardware.org/?probe=5769de3299) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [843ee79f1b](https://linux-hardware.org/?probe=843ee79f1b) | Aug 25, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [2ee74a388d](https://linux-hardware.org/?probe=2ee74a388d) | Aug 25, 2022 |
| Dell          | 0WG864                      | Desktop     | [7cbb2239ba](https://linux-hardware.org/?probe=7cbb2239ba) | Aug 25, 2022 |
| Google        | Terra                       | Notebook    | [72965945d5](https://linux-hardware.org/?probe=72965945d5) | Aug 25, 2022 |
| Dell          | 0D4MD1 A02                  | Desktop     | [7a06622253](https://linux-hardware.org/?probe=7a06622253) | Aug 25, 2022 |
| Google        | Terra                       | Notebook    | [78436fd3bf](https://linux-hardware.org/?probe=78436fd3bf) | Aug 25, 2022 |
| Dell          | 0WG864                      | Desktop     | [a333ec7f99](https://linux-hardware.org/?probe=a333ec7f99) | Aug 25, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [27095a2962](https://linux-hardware.org/?probe=27095a2962) | Aug 25, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e399d35565](https://linux-hardware.org/?probe=e399d35565) | Aug 25, 2022 |
| ASUSTek       | A7N8X2.0                    | Desktop     | [f063b3e61a](https://linux-hardware.org/?probe=f063b3e61a) | Aug 25, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b2dc63405c](https://linux-hardware.org/?probe=b2dc63405c) | Aug 25, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [222aa7a498](https://linux-hardware.org/?probe=222aa7a498) | Aug 25, 2022 |
| Fujitsu       | D3173-A1 S26361-D3173-A1    | Mini pc     | [273ce0954a](https://linux-hardware.org/?probe=273ce0954a) | Aug 25, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [a6aaf03cfe](https://linux-hardware.org/?probe=a6aaf03cfe) | Aug 25, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [42cd205688](https://linux-hardware.org/?probe=42cd205688) | Aug 25, 2022 |
| ASUSTek       | IPN73-BA                    | Desktop     | [da7e1db516](https://linux-hardware.org/?probe=da7e1db516) | Aug 25, 2022 |
| Dell          | Inspiron 600m               | Notebook    | [6acc515c79](https://linux-hardware.org/?probe=6acc515c79) | Aug 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [0b0b30459b](https://linux-hardware.org/?probe=0b0b30459b) | Aug 25, 2022 |
| Dell          | Latitude 3570               | Notebook    | [287cfa2ce8](https://linux-hardware.org/?probe=287cfa2ce8) | Aug 25, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [604a0a7789](https://linux-hardware.org/?probe=604a0a7789) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [413cc5a3c3](https://linux-hardware.org/?probe=413cc5a3c3) | Aug 24, 2022 |
| HP            | 339A                        | Desktop     | [961ac650aa](https://linux-hardware.org/?probe=961ac650aa) | Aug 24, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [6f1c64ae10](https://linux-hardware.org/?probe=6f1c64ae10) | Aug 24, 2022 |
| Lenovo        | ThinkPad E490 20N8001EUS    | Notebook    | [1620f0e5ff](https://linux-hardware.org/?probe=1620f0e5ff) | Aug 24, 2022 |
| Dell          | 0D4MD1 A02                  | Desktop     | [b634bcdfa9](https://linux-hardware.org/?probe=b634bcdfa9) | Aug 24, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | Notebook    | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [11cfa7a502](https://linux-hardware.org/?probe=11cfa7a502) | Aug 24, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [bc4f5f8811](https://linux-hardware.org/?probe=bc4f5f8811) | Aug 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4b5ebc25d2](https://linux-hardware.org/?probe=4b5ebc25d2) | Aug 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [8b346ab142](https://linux-hardware.org/?probe=8b346ab142) | Aug 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [aa03f81ccc](https://linux-hardware.org/?probe=aa03f81ccc) | Aug 24, 2022 |
| Google        | Reks                        | Notebook    | [043b648dc5](https://linux-hardware.org/?probe=043b648dc5) | Aug 23, 2022 |
| Google        | Terra                       | Notebook    | [b720f3ca23](https://linux-hardware.org/?probe=b720f3ca23) | Aug 23, 2022 |
| Google        | Terra                       | Notebook    | [0fd5baced8](https://linux-hardware.org/?probe=0fd5baced8) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [dfbced302f](https://linux-hardware.org/?probe=dfbced302f) | Aug 23, 2022 |
| Google        | Terra                       | Notebook    | [92efdef775](https://linux-hardware.org/?probe=92efdef775) | Aug 23, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [e5d3453caa](https://linux-hardware.org/?probe=e5d3453caa) | Aug 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [cdfd15fef9](https://linux-hardware.org/?probe=cdfd15fef9) | Aug 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [182b375456](https://linux-hardware.org/?probe=182b375456) | Aug 23, 2022 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [f0691dc9d8](https://linux-hardware.org/?probe=f0691dc9d8) | Aug 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [91f1311a5f](https://linux-hardware.org/?probe=91f1311a5f) | Aug 23, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [351d3809aa](https://linux-hardware.org/?probe=351d3809aa) | Aug 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [57f614fe8e](https://linux-hardware.org/?probe=57f614fe8e) | Aug 23, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [801a4be04d](https://linux-hardware.org/?probe=801a4be04d) | Aug 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5de3b172a8](https://linux-hardware.org/?probe=5de3b172a8) | Aug 23, 2022 |
| Aquarius      | AQH310CM                    | Desktop     | [5e7e2820f4](https://linux-hardware.org/?probe=5e7e2820f4) | Aug 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [66b1fdd7f4](https://linux-hardware.org/?probe=66b1fdd7f4) | Aug 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [06663792e5](https://linux-hardware.org/?probe=06663792e5) | Aug 23, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [2ac415ca87](https://linux-hardware.org/?probe=2ac415ca87) | Aug 23, 2022 |
| ASUSTek       | A7N8X2.0                    | Desktop     | [56416fa002](https://linux-hardware.org/?probe=56416fa002) | Aug 23, 2022 |
| Dell          | 0MWYPT A02                  | Desktop     | [017af6f58d](https://linux-hardware.org/?probe=017af6f58d) | Aug 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1672b2625e](https://linux-hardware.org/?probe=1672b2625e) | Aug 23, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [3224d8bdcc](https://linux-hardware.org/?probe=3224d8bdcc) | Aug 23, 2022 |
| Dell          | 0WG864                      | Desktop     | [e199a1a176](https://linux-hardware.org/?probe=e199a1a176) | Aug 23, 2022 |
| VANT          | MOOVE3-15                   | Notebook    | [854b7f42d4](https://linux-hardware.org/?probe=854b7f42d4) | Aug 22, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [6692313edb](https://linux-hardware.org/?probe=6692313edb) | Aug 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [0e2b064aed](https://linux-hardware.org/?probe=0e2b064aed) | Aug 22, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [348bfefbea](https://linux-hardware.org/?probe=348bfefbea) | Aug 22, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b4787e9532](https://linux-hardware.org/?probe=b4787e9532) | Aug 22, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [13b47f963c](https://linux-hardware.org/?probe=13b47f963c) | Aug 22, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d16f428a43](https://linux-hardware.org/?probe=d16f428a43) | Aug 22, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [7652f87b3a](https://linux-hardware.org/?probe=7652f87b3a) | Aug 22, 2022 |
| ASUSTek       | Z10PA-U8 Series             | Desktop     | [3e560a4018](https://linux-hardware.org/?probe=3e560a4018) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [35270005d4](https://linux-hardware.org/?probe=35270005d4) | Aug 22, 2022 |
| Biostar       | A68N-5100                   | Desktop     | [2c6df92279](https://linux-hardware.org/?probe=2c6df92279) | Aug 22, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2431fa78d1](https://linux-hardware.org/?probe=2431fa78d1) | Aug 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [532e1358b6](https://linux-hardware.org/?probe=532e1358b6) | Aug 21, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3eed86b908](https://linux-hardware.org/?probe=3eed86b908) | Aug 21, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [8ab7fcb6ff](https://linux-hardware.org/?probe=8ab7fcb6ff) | Aug 21, 2022 |
| Dell          | Precision 7720              | Notebook    | [60ad0b7b3d](https://linux-hardware.org/?probe=60ad0b7b3d) | Aug 21, 2022 |
| ASRock        | Z77 Extreme6                | Desktop     | [660091e5bb](https://linux-hardware.org/?probe=660091e5bb) | Aug 20, 2022 |
| Positivo      | Mobile                      | Notebook    | [8678ddf7ac](https://linux-hardware.org/?probe=8678ddf7ac) | Aug 20, 2022 |
| Positivo      | Mobile                      | Notebook    | [d1cf6b8c9e](https://linux-hardware.org/?probe=d1cf6b8c9e) | Aug 20, 2022 |
| VANT          | MOOVE3-15                   | Notebook    | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [9f5e59e0b9](https://linux-hardware.org/?probe=9f5e59e0b9) | Aug 20, 2022 |
| MSI           | GF75 Thin 10SCSXR           | Notebook    | [095c130069](https://linux-hardware.org/?probe=095c130069) | Aug 20, 2022 |
| Google        | Teemo                       | Desktop     | [4cc9295e6d](https://linux-hardware.org/?probe=4cc9295e6d) | Aug 20, 2022 |
| HP            | 620                         | Notebook    | [d3b1eb8b4e](https://linux-hardware.org/?probe=d3b1eb8b4e) | Aug 20, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [6ba8616656](https://linux-hardware.org/?probe=6ba8616656) | Aug 20, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [9131aa23c4](https://linux-hardware.org/?probe=9131aa23c4) | Aug 20, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [e5e74eea07](https://linux-hardware.org/?probe=e5e74eea07) | Aug 19, 2022 |
| Google        | Reks                        | Notebook    | [e5cde69ff7](https://linux-hardware.org/?probe=e5cde69ff7) | Aug 19, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [139de551c8](https://linux-hardware.org/?probe=139de551c8) | Aug 19, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [9e72f598eb](https://linux-hardware.org/?probe=9e72f598eb) | Aug 19, 2022 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [a67c5b1926](https://linux-hardware.org/?probe=a67c5b1926) | Aug 19, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [696fd40644](https://linux-hardware.org/?probe=696fd40644) | Aug 19, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7ee3d377c3](https://linux-hardware.org/?probe=7ee3d377c3) | Aug 19, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [38cbeed056](https://linux-hardware.org/?probe=38cbeed056) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [45bfdfa985](https://linux-hardware.org/?probe=45bfdfa985) | Aug 19, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [2f99e182f6](https://linux-hardware.org/?probe=2f99e182f6) | Aug 19, 2022 |
| HP            | 620                         | Notebook    | [259635c419](https://linux-hardware.org/?probe=259635c419) | Aug 19, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [b6c2448d15](https://linux-hardware.org/?probe=b6c2448d15) | Aug 19, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [dd60bc456d](https://linux-hardware.org/?probe=dd60bc456d) | Aug 19, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [2c703ecc1c](https://linux-hardware.org/?probe=2c703ecc1c) | Aug 19, 2022 |
| ICL           | N7x0WU                      | Notebook    | [7b9c4ad6b1](https://linux-hardware.org/?probe=7b9c4ad6b1) | Aug 19, 2022 |
| HP            | Compaq nx7300 (RH678EA#A... | Notebook    | [6fc01cef23](https://linux-hardware.org/?probe=6fc01cef23) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [e6003f393e](https://linux-hardware.org/?probe=e6003f393e) | Aug 19, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [f7fc2a9686](https://linux-hardware.org/?probe=f7fc2a9686) | Aug 19, 2022 |
| Dell          | Latitude 5500               | Notebook    | [1c7c8639aa](https://linux-hardware.org/?probe=1c7c8639aa) | Aug 19, 2022 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [e6a9f975ae](https://linux-hardware.org/?probe=e6a9f975ae) | Aug 18, 2022 |
| Google        | Reks                        | Notebook    | [d09d250717](https://linux-hardware.org/?probe=d09d250717) | Aug 18, 2022 |
| Google        | Terra                       | Notebook    | [4eca7693ab](https://linux-hardware.org/?probe=4eca7693ab) | Aug 18, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4851f9ba90](https://linux-hardware.org/?probe=4851f9ba90) | Aug 18, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [38eed67854](https://linux-hardware.org/?probe=38eed67854) | Aug 18, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2bf6063217](https://linux-hardware.org/?probe=2bf6063217) | Aug 18, 2022 |
| Gateway       | DS50                        | Desktop     | [3d4faf13bb](https://linux-hardware.org/?probe=3d4faf13bb) | Aug 18, 2022 |
| Google        | Reks                        | Notebook    | [9fc034e8a0](https://linux-hardware.org/?probe=9fc034e8a0) | Aug 18, 2022 |
| Google        | Terra                       | Notebook    | [aabdca917b](https://linux-hardware.org/?probe=aabdca917b) | Aug 18, 2022 |
| Acer          | TravelMate 5620             | Notebook    | [5b1df1054c](https://linux-hardware.org/?probe=5b1df1054c) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [58b22885a8](https://linux-hardware.org/?probe=58b22885a8) | Aug 18, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4abfd8a6c0](https://linux-hardware.org/?probe=4abfd8a6c0) | Aug 18, 2022 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [84e861fd2c](https://linux-hardware.org/?probe=84e861fd2c) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [fb83ed3720](https://linux-hardware.org/?probe=fb83ed3720) | Aug 18, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b0b0747ce6](https://linux-hardware.org/?probe=b0b0747ce6) | Aug 18, 2022 |
| ECS           | G31T-M9                     | Desktop     | [d5b3edd559](https://linux-hardware.org/?probe=d5b3edd559) | Aug 18, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | Desktop     | [16e54152fd](https://linux-hardware.org/?probe=16e54152fd) | Aug 18, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | Desktop     | [e0208cab99](https://linux-hardware.org/?probe=e0208cab99) | Aug 18, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Dell          | 0WG864                      | Desktop     | [c4aee967b4](https://linux-hardware.org/?probe=c4aee967b4) | Aug 18, 2022 |
| Acer          | TravelMate 5620             | Notebook    | [cdb6e6d5d6](https://linux-hardware.org/?probe=cdb6e6d5d6) | Aug 17, 2022 |
| ASUSTek       | K70IJ                       | Notebook    | [99bb1459e7](https://linux-hardware.org/?probe=99bb1459e7) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [762c1d4ca6](https://linux-hardware.org/?probe=762c1d4ca6) | Aug 17, 2022 |
| MSI           | B85M-E45                    | Desktop     | [cb991c0789](https://linux-hardware.org/?probe=cb991c0789) | Aug 17, 2022 |
| Shuttle       | DS437                       | Notebook    | [21e0ca6a77](https://linux-hardware.org/?probe=21e0ca6a77) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [eadf4aa206](https://linux-hardware.org/?probe=eadf4aa206) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6cfc1604da](https://linux-hardware.org/?probe=6cfc1604da) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9547f3a6c6](https://linux-hardware.org/?probe=9547f3a6c6) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [dec4f58731](https://linux-hardware.org/?probe=dec4f58731) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [cf2c47ca4a](https://linux-hardware.org/?probe=cf2c47ca4a) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5d5dc44bc1](https://linux-hardware.org/?probe=5d5dc44bc1) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [44196b38e4](https://linux-hardware.org/?probe=44196b38e4) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [23ba190eb0](https://linux-hardware.org/?probe=23ba190eb0) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6fd776c9ef](https://linux-hardware.org/?probe=6fd776c9ef) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [819b5be1bb](https://linux-hardware.org/?probe=819b5be1bb) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c409f02456](https://linux-hardware.org/?probe=c409f02456) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d85efa32be](https://linux-hardware.org/?probe=d85efa32be) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e384856047](https://linux-hardware.org/?probe=e384856047) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d9705face9](https://linux-hardware.org/?probe=d9705face9) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fa5d4671bc](https://linux-hardware.org/?probe=fa5d4671bc) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [88ae3a7f46](https://linux-hardware.org/?probe=88ae3a7f46) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [17c37ac51d](https://linux-hardware.org/?probe=17c37ac51d) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8e714e37b9](https://linux-hardware.org/?probe=8e714e37b9) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4e5efc2b45](https://linux-hardware.org/?probe=4e5efc2b45) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f600dc5571](https://linux-hardware.org/?probe=f600dc5571) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [090390a858](https://linux-hardware.org/?probe=090390a858) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3ef824b092](https://linux-hardware.org/?probe=3ef824b092) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6360d9a2ac](https://linux-hardware.org/?probe=6360d9a2ac) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e262f6b963](https://linux-hardware.org/?probe=e262f6b963) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6968426580](https://linux-hardware.org/?probe=6968426580) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7a668f339d](https://linux-hardware.org/?probe=7a668f339d) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5c71ea72fe](https://linux-hardware.org/?probe=5c71ea72fe) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [45f822152d](https://linux-hardware.org/?probe=45f822152d) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6a899b0236](https://linux-hardware.org/?probe=6a899b0236) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4bd4e21f0c](https://linux-hardware.org/?probe=4bd4e21f0c) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [549970a619](https://linux-hardware.org/?probe=549970a619) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0110227072](https://linux-hardware.org/?probe=0110227072) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a55d54836a](https://linux-hardware.org/?probe=a55d54836a) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3e0e445b26](https://linux-hardware.org/?probe=3e0e445b26) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d8b1cb2061](https://linux-hardware.org/?probe=d8b1cb2061) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [51b8352efa](https://linux-hardware.org/?probe=51b8352efa) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c870d31a49](https://linux-hardware.org/?probe=c870d31a49) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ca3ec0ff43](https://linux-hardware.org/?probe=ca3ec0ff43) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [733b464bd0](https://linux-hardware.org/?probe=733b464bd0) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [bf2bf3fbf8](https://linux-hardware.org/?probe=bf2bf3fbf8) | Aug 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2c4ebf882d](https://linux-hardware.org/?probe=2c4ebf882d) | Aug 17, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [b648d56b04](https://linux-hardware.org/?probe=b648d56b04) | Aug 17, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [d066e1bcdf](https://linux-hardware.org/?probe=d066e1bcdf) | Aug 17, 2022 |
| ECS           | G31T-M9                     | Desktop     | [6192258c32](https://linux-hardware.org/?probe=6192258c32) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [125fdc6af1](https://linux-hardware.org/?probe=125fdc6af1) | Aug 17, 2022 |
| Dell          | Precision M6600             | Notebook    | [2e1eaedbc4](https://linux-hardware.org/?probe=2e1eaedbc4) | Aug 17, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [9cefc23bb3](https://linux-hardware.org/?probe=9cefc23bb3) | Aug 17, 2022 |
| Dell          | Latitude 7410               | Convertible | [8488673ce2](https://linux-hardware.org/?probe=8488673ce2) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5d34dfe506](https://linux-hardware.org/?probe=5d34dfe506) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4b8c96576d](https://linux-hardware.org/?probe=4b8c96576d) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e8fa3a15e8](https://linux-hardware.org/?probe=e8fa3a15e8) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e773c904ab](https://linux-hardware.org/?probe=e773c904ab) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9ecb9c55ac](https://linux-hardware.org/?probe=9ecb9c55ac) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5e931f57b4](https://linux-hardware.org/?probe=5e931f57b4) | Aug 16, 2022 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [468b2624c3](https://linux-hardware.org/?probe=468b2624c3) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [dde4cacbc3](https://linux-hardware.org/?probe=dde4cacbc3) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [33acf43c27](https://linux-hardware.org/?probe=33acf43c27) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [04b16b8812](https://linux-hardware.org/?probe=04b16b8812) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [cf43730577](https://linux-hardware.org/?probe=cf43730577) | Aug 16, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [fdeea5b020](https://linux-hardware.org/?probe=fdeea5b020) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b62ac95dc0](https://linux-hardware.org/?probe=b62ac95dc0) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8ffe986da5](https://linux-hardware.org/?probe=8ffe986da5) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [eda33575d3](https://linux-hardware.org/?probe=eda33575d3) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8f5dbb62bb](https://linux-hardware.org/?probe=8f5dbb62bb) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [68cd90eac1](https://linux-hardware.org/?probe=68cd90eac1) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [138c2c6162](https://linux-hardware.org/?probe=138c2c6162) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [cc495a1749](https://linux-hardware.org/?probe=cc495a1749) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f7ad4f16ab](https://linux-hardware.org/?probe=f7ad4f16ab) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [00f2fedc6a](https://linux-hardware.org/?probe=00f2fedc6a) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [522ee33d91](https://linux-hardware.org/?probe=522ee33d91) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [09f29afcaf](https://linux-hardware.org/?probe=09f29afcaf) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fdf3945ada](https://linux-hardware.org/?probe=fdf3945ada) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0dd5eba09b](https://linux-hardware.org/?probe=0dd5eba09b) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3cc70e4b68](https://linux-hardware.org/?probe=3cc70e4b68) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1779564319](https://linux-hardware.org/?probe=1779564319) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1792826354](https://linux-hardware.org/?probe=1792826354) | Aug 16, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | Notebook    | [74e8d1be5b](https://linux-hardware.org/?probe=74e8d1be5b) | Aug 16, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | Notebook    | [d04d18b241](https://linux-hardware.org/?probe=d04d18b241) | Aug 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3ad34a904a](https://linux-hardware.org/?probe=3ad34a904a) | Aug 16, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [84a3ba511d](https://linux-hardware.org/?probe=84a3ba511d) | Aug 16, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [47ecca331e](https://linux-hardware.org/?probe=47ecca331e) | Aug 16, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3e7b575743](https://linux-hardware.org/?probe=3e7b575743) | Aug 16, 2022 |
| PCBOX         | Kant                        | Notebook    | [1b5c160d93](https://linux-hardware.org/?probe=1b5c160d93) | Aug 16, 2022 |
| Lenovo        | 3190 SDK0T76530 WIN 3556... | Mini pc     | [766a8b38a6](https://linux-hardware.org/?probe=766a8b38a6) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [1999369ff0](https://linux-hardware.org/?probe=1999369ff0) | Aug 16, 2022 |
| sunxi         | Unknown                     | Soc         | [a57117f63f](https://linux-hardware.org/?probe=a57117f63f) | Aug 15, 2022 |
| Google        | Terra                       | Notebook    | [8c5b7a9814](https://linux-hardware.org/?probe=8c5b7a9814) | Aug 15, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [dc4a6c4f34](https://linux-hardware.org/?probe=dc4a6c4f34) | Aug 15, 2022 |
| Google        | Terra                       | Notebook    | [43c28dadff](https://linux-hardware.org/?probe=43c28dadff) | Aug 15, 2022 |
| Google        | Terra                       | Notebook    | [98b7a9a377](https://linux-hardware.org/?probe=98b7a9a377) | Aug 15, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [959d35921a](https://linux-hardware.org/?probe=959d35921a) | Aug 15, 2022 |
| Google        | Terra                       | Notebook    | [3bfcb2b1b4](https://linux-hardware.org/?probe=3bfcb2b1b4) | Aug 15, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [26811058c5](https://linux-hardware.org/?probe=26811058c5) | Aug 15, 2022 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [c1e007def0](https://linux-hardware.org/?probe=c1e007def0) | Aug 15, 2022 |
| Dell          | Latitude 5420               | Notebook    | [0dec3e9676](https://linux-hardware.org/?probe=0dec3e9676) | Aug 15, 2022 |
| HP            | 3047h                       | Desktop     | [bba72086af](https://linux-hardware.org/?probe=bba72086af) | Aug 15, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [2c02d907a6](https://linux-hardware.org/?probe=2c02d907a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [8a91001294](https://linux-hardware.org/?probe=8a91001294) | Aug 15, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0427ba54e2](https://linux-hardware.org/?probe=0427ba54e2) | Aug 15, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [16f67ec18b](https://linux-hardware.org/?probe=16f67ec18b) | Aug 15, 2022 |
| ASUSTek       | WS C422 DC                  | Desktop     | [92d816348a](https://linux-hardware.org/?probe=92d816348a) | Aug 15, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [fee71ca4bf](https://linux-hardware.org/?probe=fee71ca4bf) | Aug 15, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [bfcafd66de](https://linux-hardware.org/?probe=bfcafd66de) | Aug 15, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [9a1ff39910](https://linux-hardware.org/?probe=9a1ff39910) | Aug 15, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [39da8f51fe](https://linux-hardware.org/?probe=39da8f51fe) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [fcdd677280](https://linux-hardware.org/?probe=fcdd677280) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [eeed6b3d08](https://linux-hardware.org/?probe=eeed6b3d08) | Aug 14, 2022 |
| HP            | Compaq 6910p                | Notebook    | [97e8467d4d](https://linux-hardware.org/?probe=97e8467d4d) | Aug 13, 2022 |
| Dell          | Latitude E5430 vPro         | Notebook    | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [cdba281a27](https://linux-hardware.org/?probe=cdba281a27) | Aug 13, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [8b417889e1](https://linux-hardware.org/?probe=8b417889e1) | Aug 13, 2022 |
| ASRock        | AB350 Gaming K4             | Desktop     | [8a6141848a](https://linux-hardware.org/?probe=8a6141848a) | Aug 13, 2022 |
| Dell          | 0WWJRX A00                  | Desktop     | [c9a3a6e952](https://linux-hardware.org/?probe=c9a3a6e952) | Aug 13, 2022 |
| HP            | Presario CQ56               | Notebook    | [48dfc2da91](https://linux-hardware.org/?probe=48dfc2da91) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [188bfa465d](https://linux-hardware.org/?probe=188bfa465d) | Aug 13, 2022 |
| Dell          | Latitude E6330              | Notebook    | [b48c021700](https://linux-hardware.org/?probe=b48c021700) | Aug 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [94eb72e4ac](https://linux-hardware.org/?probe=94eb72e4ac) | Aug 13, 2022 |
| Intel         | S1200BTL E98681-352         | Server      | [1db51bcff9](https://linux-hardware.org/?probe=1db51bcff9) | Aug 12, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [5b24d3e87b](https://linux-hardware.org/?probe=5b24d3e87b) | Aug 12, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [3dd4d44be4](https://linux-hardware.org/?probe=3dd4d44be4) | Aug 12, 2022 |
| Dell          | 0WG864                      | Desktop     | [de74f89735](https://linux-hardware.org/?probe=de74f89735) | Aug 12, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [471a1ec71e](https://linux-hardware.org/?probe=471a1ec71e) | Aug 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [ed94063eb8](https://linux-hardware.org/?probe=ed94063eb8) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [ed37ad46b6](https://linux-hardware.org/?probe=ed37ad46b6) | Aug 12, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [7afaba2067](https://linux-hardware.org/?probe=7afaba2067) | Aug 12, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [57be8a8829](https://linux-hardware.org/?probe=57be8a8829) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [2fab557514](https://linux-hardware.org/?probe=2fab557514) | Aug 12, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [6f828c5743](https://linux-hardware.org/?probe=6f828c5743) | Aug 12, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [c38e80ade4](https://linux-hardware.org/?probe=c38e80ade4) | Aug 11, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [efd4ec3ee7](https://linux-hardware.org/?probe=efd4ec3ee7) | Aug 11, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [059e0786bf](https://linux-hardware.org/?probe=059e0786bf) | Aug 11, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [934583e785](https://linux-hardware.org/?probe=934583e785) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6ae410e9dc](https://linux-hardware.org/?probe=6ae410e9dc) | Aug 11, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a3b402ea54](https://linux-hardware.org/?probe=a3b402ea54) | Aug 11, 2022 |
| Aquarius      | AQH310CM                    | Desktop     | [4084737708](https://linux-hardware.org/?probe=4084737708) | Aug 11, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [830489f44c](https://linux-hardware.org/?probe=830489f44c) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | Notebook    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [d8432224a8](https://linux-hardware.org/?probe=d8432224a8) | Aug 11, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [1325d40c4e](https://linux-hardware.org/?probe=1325d40c4e) | Aug 11, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [d64d35a05d](https://linux-hardware.org/?probe=d64d35a05d) | Aug 11, 2022 |
| ASRock        | H61M/U3S3                   | Desktop     | [be0d853621](https://linux-hardware.org/?probe=be0d853621) | Aug 11, 2022 |
| Dell          | Latitude 6430U              | Notebook    | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [33dc68fe04](https://linux-hardware.org/?probe=33dc68fe04) | Aug 11, 2022 |
| ASUSTek       | H81T                        | Desktop     | [4049aa824c](https://linux-hardware.org/?probe=4049aa824c) | Aug 11, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [23b946fc6d](https://linux-hardware.org/?probe=23b946fc6d) | Aug 11, 2022 |
| Unknown       | Handsome Openstick          | Soc         | [6b68f00cab](https://linux-hardware.org/?probe=6b68f00cab) | Aug 11, 2022 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [6e1650d26d](https://linux-hardware.org/?probe=6e1650d26d) | Aug 11, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [9fa1e00c24](https://linux-hardware.org/?probe=9fa1e00c24) | Aug 10, 2022 |
| Toshiba       | TECRA R950                  | Notebook    | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| ASRock        | G31M-S                      | Desktop     | [335a6f8616](https://linux-hardware.org/?probe=335a6f8616) | Aug 10, 2022 |
| MSI           | H81M-P33                    | Desktop     | [fd910dc3ca](https://linux-hardware.org/?probe=fd910dc3ca) | Aug 10, 2022 |
| MSI           | G41M-P28                    | Desktop     | [c20d54489d](https://linux-hardware.org/?probe=c20d54489d) | Aug 10, 2022 |
| Intel         | DP35DP AAD81073-207         | Desktop     | [3f55eb1ae4](https://linux-hardware.org/?probe=3f55eb1ae4) | Aug 10, 2022 |
| Intel         | DH87RL AAG74240-402         | Desktop     | [a83fd820d4](https://linux-hardware.org/?probe=a83fd820d4) | Aug 10, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [51ba94d8f9](https://linux-hardware.org/?probe=51ba94d8f9) | Aug 10, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [c28a56202d](https://linux-hardware.org/?probe=c28a56202d) | Aug 10, 2022 |
| MSI           | H81M-P33                    | Desktop     | [243392c01f](https://linux-hardware.org/?probe=243392c01f) | Aug 10, 2022 |
| ASUSTek       | X751LJ                      | Notebook    | [5c3767ccc2](https://linux-hardware.org/?probe=5c3767ccc2) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [ea9b6a4757](https://linux-hardware.org/?probe=ea9b6a4757) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [4e9256cf7f](https://linux-hardware.org/?probe=4e9256cf7f) | Aug 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [b92ffbefad](https://linux-hardware.org/?probe=b92ffbefad) | Aug 09, 2022 |
| Intel         | DH87RL AAG74240-402         | Desktop     | [8ea693190b](https://linux-hardware.org/?probe=8ea693190b) | Aug 09, 2022 |
| ASUSTek       | X751LJ                      | Notebook    | [e35689c8f1](https://linux-hardware.org/?probe=e35689c8f1) | Aug 09, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [19346d16de](https://linux-hardware.org/?probe=19346d16de) | Aug 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [1713317338](https://linux-hardware.org/?probe=1713317338) | Aug 09, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [b73567b27b](https://linux-hardware.org/?probe=b73567b27b) | Aug 09, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [21fdf57c32](https://linux-hardware.org/?probe=21fdf57c32) | Aug 09, 2022 |
| HP            | EliteBook 725 G3            | Notebook    | [7e36a68724](https://linux-hardware.org/?probe=7e36a68724) | Aug 09, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a24a03a6dd](https://linux-hardware.org/?probe=a24a03a6dd) | Aug 09, 2022 |
| NVN-ED01      | Unknown                     | Notebook    | [0a677cad6c](https://linux-hardware.org/?probe=0a677cad6c) | Aug 09, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [b66253f362](https://linux-hardware.org/?probe=b66253f362) | Aug 09, 2022 |
| Alienware     | m15 R6                      | Notebook    | [675208eaec](https://linux-hardware.org/?probe=675208eaec) | Aug 09, 2022 |
| Dell          | Precision 7720              | Notebook    | [e79faaa4c0](https://linux-hardware.org/?probe=e79faaa4c0) | Aug 08, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [fb01a8303f](https://linux-hardware.org/?probe=fb01a8303f) | Aug 08, 2022 |
| Unknown       | MT6737 (DT)                 | Soc         | [eca75207bf](https://linux-hardware.org/?probe=eca75207bf) | Aug 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [b8ae818291](https://linux-hardware.org/?probe=b8ae818291) | Aug 08, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [b07157a232](https://linux-hardware.org/?probe=b07157a232) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [49c2378f28](https://linux-hardware.org/?probe=49c2378f28) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [9943b58e25](https://linux-hardware.org/?probe=9943b58e25) | Aug 08, 2022 |
| Dell          | Latitude E7450              | Notebook    | [f2d8a030f4](https://linux-hardware.org/?probe=f2d8a030f4) | Aug 08, 2022 |
| Foxconn       | G41MXP/G41MXP-V             | Desktop     | [91fb10e9c6](https://linux-hardware.org/?probe=91fb10e9c6) | Aug 08, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [1d8eaa7564](https://linux-hardware.org/?probe=1d8eaa7564) | Aug 08, 2022 |
| ECS           | G31T-M9                     | Desktop     | [6d24097613](https://linux-hardware.org/?probe=6d24097613) | Aug 08, 2022 |
| HP            | EliteBook 725 G3            | Notebook    | [e48eff307c](https://linux-hardware.org/?probe=e48eff307c) | Aug 08, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7bb5745101](https://linux-hardware.org/?probe=7bb5745101) | Aug 08, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5526416e86](https://linux-hardware.org/?probe=5526416e86) | Aug 08, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [46b74e61f0](https://linux-hardware.org/?probe=46b74e61f0) | Aug 08, 2022 |
| Dell          | Latitude E6430              | Notebook    | [17d0fce9e5](https://linux-hardware.org/?probe=17d0fce9e5) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b1420b630f](https://linux-hardware.org/?probe=b1420b630f) | Aug 07, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [31d08ab231](https://linux-hardware.org/?probe=31d08ab231) | Aug 07, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [18935d4aff](https://linux-hardware.org/?probe=18935d4aff) | Aug 07, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [19b3f7fe4b](https://linux-hardware.org/?probe=19b3f7fe4b) | Aug 07, 2022 |
| Gigabyte      | MZGLKAP-00                  | Desktop     | [5a349b05d2](https://linux-hardware.org/?probe=5a349b05d2) | Aug 07, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | Desktop     | [67934f8ed6](https://linux-hardware.org/?probe=67934f8ed6) | Aug 07, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | Desktop     | [d6d5cc239f](https://linux-hardware.org/?probe=d6d5cc239f) | Aug 07, 2022 |
| Intel         | NUC11ATBC4 M53051-202       | Mini pc     | [95e97a827b](https://linux-hardware.org/?probe=95e97a827b) | Aug 07, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [db3d9f24c6](https://linux-hardware.org/?probe=db3d9f24c6) | Aug 07, 2022 |
| Dell          | Precision 7720              | Notebook    | [db2f868372](https://linux-hardware.org/?probe=db2f868372) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0564acfb6c](https://linux-hardware.org/?probe=0564acfb6c) | Aug 07, 2022 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [1eba623e90](https://linux-hardware.org/?probe=1eba623e90) | Aug 06, 2022 |
| Unknown       | Unknown                     | Soc         | [9efd347024](https://linux-hardware.org/?probe=9efd347024) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [468c10942e](https://linux-hardware.org/?probe=468c10942e) | Aug 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e0cfa37515](https://linux-hardware.org/?probe=e0cfa37515) | Aug 05, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3c3a5af037](https://linux-hardware.org/?probe=3c3a5af037) | Aug 05, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [53c997fe1f](https://linux-hardware.org/?probe=53c997fe1f) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [d5786b75a3](https://linux-hardware.org/?probe=d5786b75a3) | Aug 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [24d8a6228c](https://linux-hardware.org/?probe=24d8a6228c) | Aug 05, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [61ab908bd6](https://linux-hardware.org/?probe=61ab908bd6) | Aug 05, 2022 |
| ECS           | G31T-M9                     | Desktop     | [8cdebd57de](https://linux-hardware.org/?probe=8cdebd57de) | Aug 05, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [83c6e58e51](https://linux-hardware.org/?probe=83c6e58e51) | Aug 05, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [696740d407](https://linux-hardware.org/?probe=696740d407) | Aug 05, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d12e654f35](https://linux-hardware.org/?probe=d12e654f35) | Aug 05, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [9d032c38b4](https://linux-hardware.org/?probe=9d032c38b4) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [433126127b](https://linux-hardware.org/?probe=433126127b) | Aug 05, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [18cdd03a10](https://linux-hardware.org/?probe=18cdd03a10) | Aug 05, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [d17f96ad0d](https://linux-hardware.org/?probe=d17f96ad0d) | Aug 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3f1ac55a4b](https://linux-hardware.org/?probe=3f1ac55a4b) | Aug 05, 2022 |
| Acer          | Aspire 5315                 | Notebook    | [7be46d4930](https://linux-hardware.org/?probe=7be46d4930) | Aug 05, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5013513fca](https://linux-hardware.org/?probe=5013513fca) | Aug 04, 2022 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [87d90381e1](https://linux-hardware.org/?probe=87d90381e1) | Aug 04, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7948505598](https://linux-hardware.org/?probe=7948505598) | Aug 04, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [36615df149](https://linux-hardware.org/?probe=36615df149) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e74155922c](https://linux-hardware.org/?probe=e74155922c) | Aug 04, 2022 |
| Lenovo        | 102F NO DPK                 | Desktop     | [1a040c2717](https://linux-hardware.org/?probe=1a040c2717) | Aug 04, 2022 |
| Intel         | X99                         | Desktop     | [33e0d23783](https://linux-hardware.org/?probe=33e0d23783) | Aug 04, 2022 |
| Acer          | AO532h                      | Notebook    | [9a35f25fba](https://linux-hardware.org/?probe=9a35f25fba) | Aug 04, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5fe90b268d](https://linux-hardware.org/?probe=5fe90b268d) | Aug 04, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [a2ebd67b7b](https://linux-hardware.org/?probe=a2ebd67b7b) | Aug 04, 2022 |
| Unknown       | Unknown                     | Soc         | [6574d40a4f](https://linux-hardware.org/?probe=6574d40a4f) | Aug 03, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [52e4d5e94f](https://linux-hardware.org/?probe=52e4d5e94f) | Aug 03, 2022 |
| Google        | Droid                       | Notebook    | [15d4518ba0](https://linux-hardware.org/?probe=15d4518ba0) | Aug 03, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [3d945110f8](https://linux-hardware.org/?probe=3d945110f8) | Aug 03, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [97b2316a06](https://linux-hardware.org/?probe=97b2316a06) | Aug 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [d5e820b393](https://linux-hardware.org/?probe=d5e820b393) | Aug 03, 2022 |
| HP            | 8876 11                     | Desktop     | [150fcb8977](https://linux-hardware.org/?probe=150fcb8977) | Aug 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [cdd2c530de](https://linux-hardware.org/?probe=cdd2c530de) | Aug 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [38606dd48d](https://linux-hardware.org/?probe=38606dd48d) | Aug 03, 2022 |
| HP            | 8876 11                     | Desktop     | [029813dfc5](https://linux-hardware.org/?probe=029813dfc5) | Aug 03, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [ca1d7dd61b](https://linux-hardware.org/?probe=ca1d7dd61b) | Aug 03, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [63553d673b](https://linux-hardware.org/?probe=63553d673b) | Aug 03, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [94ccc2e14f](https://linux-hardware.org/?probe=94ccc2e14f) | Aug 03, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [74cd42b826](https://linux-hardware.org/?probe=74cd42b826) | Aug 03, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [0bf365f767](https://linux-hardware.org/?probe=0bf365f767) | Aug 02, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [e586e6ee53](https://linux-hardware.org/?probe=e586e6ee53) | Aug 02, 2022 |
| HP            | 255 G3                      | Notebook    | [46ad188006](https://linux-hardware.org/?probe=46ad188006) | Aug 02, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [80512402c0](https://linux-hardware.org/?probe=80512402c0) | Aug 02, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [d01d805978](https://linux-hardware.org/?probe=d01d805978) | Aug 02, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [d2c534d06f](https://linux-hardware.org/?probe=d2c534d06f) | Aug 02, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9e48213e39](https://linux-hardware.org/?probe=9e48213e39) | Aug 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 961       | 20%     |
| 5.10.0-7-amd64         | 654       | 13.61%  |
| 5.10.0-10-amd64        | 567       | 11.8%   |
| 5.10.0-16-amd64        | 350       | 7.28%   |
| 5.10.0-9-amd64         | 321       | 6.68%   |
| 5.10.0-13-amd64        | 256       | 5.33%   |
| 5.10.0-11-amd64        | 191       | 3.98%   |
| 5.10.0-14-amd64        | 136       | 2.83%   |
| 5.10.0-17-amd64        | 118       | 2.46%   |
| 5.10.0-2-amd64         | 105       | 2.19%   |
| 5.10.0-18-amd64        | 94        | 1.96%   |
| 5.10.0-15-amd64        | 82        | 1.71%   |
| 5.10.0-12-amd64        | 72        | 1.5%    |
| 5.10.0-6-amd64         | 46        | 0.96%   |
| 5.15.0-2-amd64         | 38        | 0.79%   |
| 5.10.0-13-686-pae      | 30        | 0.62%   |
| 5.16.0-0.bpo.4-amd64   | 29        | 0.6%    |
| 5.18.0-0.bpo.1-amd64   | 25        | 0.52%   |
| 5.14.0-0.bpo.2-amd64   | 24        | 0.5%    |
| 5.10.0-8-arm64         | 18        | 0.37%   |
| 5.13.19-6-pve          | 17        | 0.35%   |
| 5.15.32-v8+            | 16        | 0.33%   |
| 5.13.19-2-pve          | 16        | 0.33%   |
| 5.10.0-3-amd64         | 15        | 0.31%   |
| 5.10.0-8-686-pae       | 14        | 0.29%   |
| 5.18.0-0.deb11.4-amd64 | 13        | 0.27%   |
| 5.15.35-1-pve          | 12        | 0.25%   |
| 5.10.92-v8+            | 12        | 0.25%   |
| 5.10.0-9-686-pae       | 12        | 0.25%   |
| 5.15.53-1-pve          | 11        | 0.23%   |
| 5.15.30-2-pve          | 11        | 0.23%   |
| 5.15.0-0.bpo.2-amd64   | 11        | 0.23%   |
| 5.10.0-9-686           | 11        | 0.23%   |
| 5.18.0-2-amd64         | 10        | 0.21%   |
| 5.10.0-4-amd64         | 10        | 0.21%   |
| 5.17.0-1-amd64         | 9         | 0.19%   |
| 5.10.0-13-686          | 9         | 0.19%   |
| 5.15.0-0.bpo.3-amd64   | 8         | 0.17%   |
| 5.13.19-1-pve          | 8         | 0.17%   |
| 5.11.22-4-pve          | 8         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 3818      | 85.76%  |
| 5.15.0   | 75        | 1.68%   |
| 5.18.0   | 63        | 1.42%   |
| 5.16.0   | 59        | 1.33%   |
| 5.13.19  | 51        | 1.15%   |
| 5.14.0   | 40        | 0.9%    |
| 5.11.22  | 25        | 0.56%   |
| 5.17.0   | 23        | 0.52%   |
| 5.15.39  | 17        | 0.38%   |
| 5.15.35  | 17        | 0.38%   |
| 5.15.32  | 17        | 0.38%   |
| 5.19.0   | 14        | 0.31%   |
| 5.10.92  | 13        | 0.29%   |
| 5.15.30  | 12        | 0.27%   |
| 5.15.53  | 11        | 0.25%   |
| 4.19.0   | 10        | 0.22%   |
| 5.13.0   | 7         | 0.16%   |
| 5.10.63  | 7         | 0.16%   |
| 5.15.61  | 6         | 0.13%   |
| 5.10.60  | 6         | 0.13%   |
| 5.10.109 | 5         | 0.11%   |
| 5.16.5   | 4         | 0.09%   |
| 5.12.0   | 4         | 0.09%   |
| 5.11.0   | 4         | 0.09%   |
| 5.10.103 | 4         | 0.09%   |
| 5.10     | 4         | 0.09%   |
| 5.9.0    | 3         | 0.07%   |
| 5.4.0    | 3         | 0.07%   |
| 5.17.5   | 3         | 0.07%   |
| 5.15.48  | 3         | 0.07%   |
| 5.15.19  | 3         | 0.07%   |
| 5.13.8   | 3         | 0.07%   |
| 5.13.13  | 3         | 0.07%   |
| 5.10.57  | 3         | 0.07%   |
| 6.0.0    | 2         | 0.04%   |
| 5.19.1   | 2         | 0.04%   |
| 5.18.6   | 2         | 0.04%   |
| 5.18.15  | 2         | 0.04%   |
| 5.17.11  | 2         | 0.04%   |
| 5.15.44  | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 3878      | 87.3%   |
| 5.15    | 177       | 3.98%   |
| 5.13    | 70        | 1.58%   |
| 5.18    | 69        | 1.55%   |
| 5.16    | 64        | 1.44%   |
| 5.14    | 46        | 1.04%   |
| 5.17    | 33        | 0.74%   |
| 5.11    | 33        | 0.74%   |
| 5.19    | 20        | 0.45%   |
| 4.19    | 12        | 0.27%   |
| 5.12    | 9         | 0.2%    |
| 5.4     | 7         | 0.16%   |
| 5       | 5         | 0.11%   |
| 5.9     | 3         | 0.07%   |
| 5.1     | 3         | 0.07%   |
| 6.0     | 2         | 0.05%   |
| 4.9     | 2         | 0.05%   |
| 4.4     | 2         | 0.05%   |
| 3.18    | 2         | 0.05%   |
| 5.8     | 1         | 0.02%   |
| 5.5     | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 3.8     | 1         | 0.02%   |
| 3.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4129      | 94.49%  |
| i686    | 128       | 2.93%   |
| aarch64 | 93        | 2.13%   |
| armv7l  | 18        | 0.41%   |
| riscv64 | 2         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 1915      | 43.33%  |
| GNOME             | 888       | 20.09%  |
| KDE5              | 452       | 10.23%  |
| XFCE              | 437       | 9.89%   |
| MATE              | 153       | 3.46%   |
| LXDE              | 112       | 2.53%   |
| X-Cinnamon        | 105       | 2.38%   |
| Cinnamon          | 92        | 2.08%   |
| LXQt              | 47        | 1.06%   |
| i3                | 47        | 1.06%   |
| KDE               | 40        | 0.9%    |
| GNOME Flashback   | 26        | 0.59%   |
| lightdm-xsession  | 24        | 0.54%   |
| Openbox           | 23        | 0.52%   |
| trinity           | 14        | 0.32%   |
| Budgie            | 8         | 0.18%   |
| GNOME Classic     | 6         | 0.14%   |
| sway              | 5         | 0.11%   |
| awesome           | 5         | 0.11%   |
| Enlightenment     | 3         | 0.07%   |
| DWM               | 3         | 0.07%   |
| Cutefish          | 3         | 0.07%   |
| ICEWM             | 2         | 0.05%   |
| xmonad            | 1         | 0.02%   |
| x-session-manager | 1         | 0.02%   |
| wmaker-common     | 1         | 0.02%   |
| UKUI              | 1         | 0.02%   |
| Phosh:GNOME       | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| default           | 1         | 0.02%   |
| Deepin            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1810      | 40.97%  |
| Unknown | 1586      | 35.9%   |
| Wayland | 621       | 14.06%  |
| Tty     | 401       | 9.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2391      | 54.23%  |
| GDM     | 711       | 16.13%  |
| LightDM | 668       | 15.15%  |
| SDDM    | 402       | 9.12%   |
| TDM     | 154       | 3.49%   |
| GDM3    | 62        | 1.41%   |
| XDM     | 8         | 0.18%   |
| SLiM    | 8         | 0.18%   |
| NODM    | 2         | 0.05%   |
| LXDM    | 2         | 0.05%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1280      | 29.06%  |
| Unknown | 843       | 19.14%  |
| ru_RU   | 781       | 17.73%  |
| de_DE   | 215       | 4.88%   |
| en_GB   | 192       | 4.36%   |
| fr_FR   | 177       | 4.02%   |
| es_ES   | 127       | 2.88%   |
| pt_BR   | 90        | 2.04%   |
| it_IT   | 78        | 1.77%   |
| pl_PL   | 62        | 1.41%   |
| en_AU   | 54        | 1.23%   |
| en_CA   | 39        | 0.89%   |
| C       | 39        | 0.89%   |
| es_MX   | 29        | 0.66%   |
| zh_CN   | 23        | 0.52%   |
| es_VE   | 22        | 0.5%    |
| hu_HU   | 21        | 0.48%   |
| es_AR   | 21        | 0.48%   |
| ja_JP   | 20        | 0.45%   |
| en_IN   | 19        | 0.43%   |
| en_IE   | 17        | 0.39%   |
| de_AT   | 14        | 0.32%   |
| nl_NL   | 13        | 0.3%    |
| pt_PT   | 12        | 0.27%   |
| de_CH   | 12        | 0.27%   |
| sv_SE   | 11        | 0.25%   |
| es_CL   | 11        | 0.25%   |
| en_ZA   | 10        | 0.23%   |
| en_NZ   | 10        | 0.23%   |
| fi_FI   | 8         | 0.18%   |
| es_CO   | 8         | 0.18%   |
| cs_CZ   | 8         | 0.18%   |
| uk_UA   | 7         | 0.16%   |
| tr_TR   | 7         | 0.16%   |
| ru_UA   | 6         | 0.14%   |
| nl_BE   | 6         | 0.14%   |
| hr_HR   | 6         | 0.14%   |
| fr_BE   | 6         | 0.14%   |
| es_PE   | 6         | 0.14%   |
| es_EC   | 5         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2495      | 56.51%  |
| BIOS | 1920      | 43.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2514      | 57.36%  |
| Overlay | 1612      | 36.78%  |
| Btrfs   | 129       | 2.94%   |
| Zfs     | 53        | 1.21%   |
| Xfs     | 45        | 1.03%   |
| Ext3    | 10        | 0.23%   |
| Unknown | 7         | 0.16%   |
| Tmpfs   | 6         | 0.14%   |
| Ext2    | 5         | 0.11%   |
| Rootfs  | 2         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2551      | 57.66%  |
| MBR     | 1260      | 28.48%  |
| Unknown | 613       | 13.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3512      | 79.82%  |
| Yes       | 888       | 20.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3005      | 68.22%  |
| Yes       | 1400      | 31.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 650       | 14.88%  |
| ASUSTek Computer        | 646       | 14.79%  |
| Apple                   | 585       | 13.39%  |
| Hewlett-Packard         | 436       | 9.98%   |
| Dell                    | 378       | 8.65%   |
| Gigabyte Technology     | 282       | 6.46%   |
| MSI                     | 201       | 4.6%    |
| ASRock                  | 158       | 3.62%   |
| Acer                    | 139       | 3.18%   |
| Google                  | 116       | 2.66%   |
| Intel                   | 93        | 2.13%   |
| Raspberry Pi Foundation | 68        | 1.56%   |
| Aquarius                | 45        | 1.03%   |
| ECS                     | 44        | 1.01%   |
| Unknown                 | 42        | 0.96%   |
| Supermicro              | 34        | 0.78%   |
| Samsung Electronics     | 29        | 0.66%   |
| Fujitsu                 | 26        | 0.6%    |
| Toshiba                 | 23        | 0.53%   |
| Foxconn                 | 23        | 0.53%   |
| HUAWEI                  | 22        | 0.5%    |
| Sony                    | 16        | 0.37%   |
| ASRockRack              | 14        | 0.32%   |
| Notebook                | 11        | 0.25%   |
| Packard Bell            | 10        | 0.23%   |
| Pegatron                | 9         | 0.21%   |
| Biostar                 | 9         | 0.21%   |
| AZW                     | 9         | 0.21%   |
| Medion                  | 8         | 0.18%   |
| Positivo                | 7         | 0.16%   |
| Fujitsu Siemens         | 7         | 0.16%   |
| AMI                     | 7         | 0.16%   |
| ZOTAC                   | 6         | 0.14%   |
| sunxi                   | 6         | 0.14%   |
| Microsoft               | 6         | 0.14%   |
| IBM                     | 6         | 0.14%   |
| Hardkernel              | 6         | 0.14%   |
| Clevo                   | 6         | 0.14%   |
| Xunlong                 | 5         | 0.11%   |
| Timi                    | 5         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 303       | 6.94%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 112       | 2.56%   |
| Apple MacBookAir7,1                       | 75        | 1.72%   |
| Google Enguarde                           | 74        | 1.69%   |
| Apple MacBookAir7,2                       | 71        | 1.63%   |
| ASUS All Series                           | 66        | 1.51%   |
| ASUS S20 K29                              | 55        | 1.26%   |
| Apple MacBook2,1                          | 55        | 1.26%   |
| Unknown                                   | 52        | 1.19%   |
| Aquarius NS585                            | 43        | 0.98%   |
| MSI MS-7996                               | 35        | 0.8%    |
| Lenovo ThinkPad E475 20H40006US           | 23        | 0.53%   |
| Apple MacBook4,1                          | 21        | 0.48%   |
| ECS G31T-M9                               | 20        | 0.46%   |
| ASRock H470M-HVS                          | 20        | 0.46%   |
| Google Terra                              | 18        | 0.41%   |
| Gigabyte H81M-S2V                         | 17        | 0.39%   |
| ASUS PRIME H510M-A                        | 17        | 0.39%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 16        | 0.37%   |
| MSI MS-7817                               | 16        | 0.37%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.37%   |
| Gigabyte H410M S2H                        | 16        | 0.37%   |
| ECS H61H2-M13                             | 16        | 0.37%   |
| Acer Aspire A315-23                       | 15        | 0.34%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 14        | 0.32%   |
| ASUS P8H61-M LX3 R2.0                     | 14        | 0.32%   |
| ASUS 1005HA                               | 12        | 0.27%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 11        | 0.25%   |
| HP Notebook                               | 11        | 0.25%   |
| HP Pavilion g6                            | 10        | 0.23%   |
| Google Reks                               | 9         | 0.21%   |
| Dell OptiPlex 7010                        | 9         | 0.21%   |
| Supermicro Super Server                   | 8         | 0.18%   |
| ASUS PRIME B450M-A                        | 8         | 0.18%   |
| ASUS H110M-R                              | 8         | 0.18%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 7         | 0.16%   |
| HP EliteBook 8460p                        | 7         | 0.16%   |
| Gigabyte B360M H                          | 7         | 0.16%   |
| Fujitsu ESPRIMO P720                      | 7         | 0.16%   |
| ASUS PRIME A320M-K                        | 7         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 434       | 9.94%   |
| Apple MacBook5     | 303       | 6.94%   |
| Apple MacBookAir7  | 146       | 3.34%   |
| Dell Latitude      | 94        | 2.15%   |
| Dell Inspiron      | 92        | 2.11%   |
| Acer Aspire        | 91        | 2.08%   |
| ASUS PRIME         | 85        | 1.95%   |
| Lenovo IdeaPad     | 77        | 1.76%   |
| Google Enguarde    | 74        | 1.69%   |
| RPi Raspberry      | 68        | 1.56%   |
| ASUS All           | 66        | 1.51%   |
| HP Pavilion        | 59        | 1.35%   |
| ASUS S20           | 55        | 1.26%   |
| Apple MacBook2     | 55        | 1.26%   |
| HP Laptop          | 52        | 1.19%   |
| Dell OptiPlex      | 52        | 1.19%   |
| Unknown            | 52        | 1.19%   |
| HP EliteBook       | 50        | 1.14%   |
| HP ProBook         | 43        | 0.98%   |
| HP Compaq          | 43        | 0.98%   |
| Aquarius NS585     | 43        | 0.98%   |
| Dell Precision     | 40        | 0.92%   |
| Dell XPS           | 38        | 0.87%   |
| MSI MS-7996        | 35        | 0.8%    |
| Lenovo ThinkCentre | 35        | 0.8%    |
| ASUS ROG           | 34        | 0.78%   |
| ASUS TUF           | 29        | 0.66%   |
| ASUS P8H61-M       | 28        | 0.64%   |
| Dell Vostro        | 27        | 0.62%   |
| ASUS VivoBook      | 26        | 0.6%    |
| Dell PowerEdge     | 23        | 0.53%   |
| Apple MacBook4     | 21        | 0.48%   |
| HP ProLiant        | 20        | 0.46%   |
| ECS G31T-M9        | 20        | 0.46%   |
| ASRock H470M-HVS   | 20        | 0.46%   |
| Toshiba Satellite  | 19        | 0.43%   |
| ASUS ZenBook       | 19        | 0.43%   |
| Google Terra       | 18        | 0.41%   |
| Gigabyte B450M     | 18        | 0.41%   |
| HP 250             | 17        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 570       | 13.05%  |
| 2009    | 446       | 10.21%  |
| 2021    | 399       | 9.13%   |
| 2019    | 338       | 7.74%   |
| 2018    | 310       | 7.1%    |
| 2012    | 290       | 6.64%   |
| 2015    | 261       | 5.98%   |
| 2013    | 237       | 5.43%   |
| 2011    | 232       | 5.31%   |
| 2016    | 225       | 5.15%   |
| 2017    | 218       | 4.99%   |
| 2014    | 181       | 4.14%   |
| 2010    | 137       | 3.14%   |
| 2007    | 134       | 3.07%   |
| 2008    | 125       | 2.86%   |
| 2022    | 100       | 2.29%   |
| Unknown | 94        | 2.15%   |
| 2005    | 26        | 0.6%    |
| 2006    | 22        | 0.5%    |
| 2003    | 13        | 0.3%    |
| 2004    | 6         | 0.14%   |
| 2001    | 3         | 0.07%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2316      | 53.02%  |
| Desktop        | 1584      | 36.26%  |
| Convertible    | 157       | 3.59%   |
| System on chip | 101       | 2.31%   |
| Mini pc        | 84        | 1.92%   |
| Server         | 69        | 1.58%   |
| All in one     | 32        | 0.73%   |
| Tablet         | 20        | 0.46%   |
| Phone          | 3         | 0.07%   |
| Other          | 2         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4151      | 94.64%  |
| Enabled  | 235       | 5.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4245      | 97.16%  |
| Yes  | 124       | 2.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1033      | 23.49%  |
| 3.01-4.0        | 801       | 18.22%  |
| 16.01-24.0      | 773       | 17.58%  |
| 1.01-2.0        | 532       | 12.1%   |
| 8.01-16.0       | 532       | 12.1%   |
| 32.01-64.0      | 314       | 7.14%   |
| 64.01-256.0     | 161       | 3.66%   |
| 2.01-3.0        | 86        | 1.96%   |
| 0.51-1.0        | 79        | 1.8%    |
| 24.01-32.0      | 53        | 1.21%   |
| 0.01-0.5        | 19        | 0.43%   |
| More than 256.0 | 13        | 0.3%    |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1677      | 36.78%  |
| 0.51-1.0    | 927       | 20.33%  |
| 2.01-3.0    | 682       | 14.96%  |
| 4.01-8.0    | 470       | 10.31%  |
| 3.01-4.0    | 376       | 8.25%   |
| 0.01-0.5    | 185       | 4.06%   |
| 8.01-16.0   | 148       | 3.25%   |
| 16.01-24.0  | 43        | 0.94%   |
| 32.01-64.0  | 21        | 0.46%   |
| 24.01-32.0  | 20        | 0.44%   |
| 64.01-256.0 | 8         | 0.18%   |
| Unknown     | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3160      | 71.38%  |
| 2      | 719       | 16.24%  |
| 3      | 225       | 5.08%   |
| 4      | 138       | 3.12%   |
| 5      | 65        | 1.47%   |
| 6      | 30        | 0.68%   |
| 0      | 29        | 0.66%   |
| 7      | 20        | 0.45%   |
| 8      | 17        | 0.38%   |
| 10     | 6         | 0.14%   |
| 12     | 4         | 0.09%   |
| 9      | 4         | 0.09%   |
| 28     | 2         | 0.05%   |
| 14     | 2         | 0.05%   |
| 13     | 2         | 0.05%   |
| 11     | 2         | 0.05%   |
| 27     | 1         | 0.02%   |
| 16     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2928      | 66.86%  |
| Yes       | 1451      | 33.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3746      | 85.66%  |
| No        | 627       | 14.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2969      | 67.83%  |
| No        | 1408      | 32.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2511      | 57.21%  |
| No        | 1878      | 42.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1309      | 29.89%  |
| Russia       | 809       | 18.47%  |
| Germany      | 330       | 7.54%   |
| France       | 231       | 5.28%   |
| Spain        | 165       | 3.77%   |
| Brazil       | 119       | 2.72%   |
| UK           | 108       | 2.47%   |
| Italy        | 101       | 2.31%   |
| Poland       | 93        | 2.12%   |
| Canada       | 69        | 1.58%   |
| Australia    | 68        | 1.55%   |
| Switzerland  | 58        | 1.32%   |
| Netherlands  | 56        | 1.28%   |
| Mexico       | 47        | 1.07%   |
| Ukraine      | 42        | 0.96%   |
| China        | 42        | 0.96%   |
| Argentina    | 38        | 0.87%   |
| Sweden       | 36        | 0.82%   |
| Hungary      | 34        | 0.78%   |
| Austria      | 34        | 0.78%   |
| Belgium      | 28        | 0.64%   |
| Portugal     | 27        | 0.62%   |
| Japan        | 26        | 0.59%   |
| Czechia      | 26        | 0.59%   |
| Venezuela    | 25        | 0.57%   |
| India        | 25        | 0.57%   |
| Turkey       | 24        | 0.55%   |
| Norway       | 23        | 0.53%   |
| Finland      | 22        | 0.5%    |
| Bulgaria     | 19        | 0.43%   |
| Greece       | 17        | 0.39%   |
| Ireland      | 16        | 0.37%   |
| Romania      | 15        | 0.34%   |
| South Africa | 14        | 0.32%   |
| New Zealand  | 14        | 0.32%   |
| Croatia      | 14        | 0.32%   |
| Colombia     | 14        | 0.32%   |
| Chile        | 14        | 0.32%   |
| Kazakhstan   | 10        | 0.23%   |
| Indonesia    | 10        | 0.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangor            | 657       | 14.43%  |
| Voronezh          | 635       | 13.94%  |
| Dover-Foxcroft    | 305       | 6.7%    |
| Seville           | 41        | 0.9%    |
| Paris             | 40        | 0.88%   |
| St Petersburg     | 33        | 0.72%   |
| Berlin            | 31        | 0.68%   |
| Moscow            | 30        | 0.66%   |
| Vienna            | 25        | 0.55%   |
| Madrid            | 25        | 0.55%   |
| Zurich            | 22        | 0.48%   |
| Warsaw            | 22        | 0.48%   |
| Munich            | 21        | 0.46%   |
| Barcelona         | 21        | 0.46%   |
| Amsterdam         | 20        | 0.44%   |
| Sao Paulo         | 17        | 0.37%   |
| Milan             | 17        | 0.37%   |
| Sydney            | 16        | 0.35%   |
| London            | 16        | 0.35%   |
| Perm              | 15        | 0.33%   |
| Brisbane          | 15        | 0.33%   |
| Lyon              | 13        | 0.29%   |
| Blizniew          | 13        | 0.29%   |
| Toronto           | 12        | 0.26%   |
| Melbourne         | 12        | 0.26%   |
| Winterport        | 11        | 0.24%   |
| Stockholm         | 11        | 0.24%   |
| Prague            | 11        | 0.24%   |
| Frankfurt am Main | 11        | 0.24%   |
| Falkenstein       | 11        | 0.24%   |
| Dublin            | 11        | 0.24%   |
| Athens            | 11        | 0.24%   |
| Valencia          | 10        | 0.22%   |
| San Jose          | 10        | 0.22%   |
| Caracas           | 10        | 0.22%   |
| Zagreb            | 9         | 0.2%    |
| Sofia             | 9         | 0.2%    |
| Leipzig           | 9         | 0.2%    |
| Istanbul          | 9         | 0.2%    |
| Helsinki          | 9         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 866       | 1272   | 15%     |
| WDC                 | 770       | 1183   | 13.33%  |
| Seagate             | 732       | 1179   | 12.68%  |
| Toshiba             | 434       | 625    | 7.52%   |
| Kingston            | 342       | 416    | 5.92%   |
| Unknown             | 319       | 420    | 5.52%   |
| Crucial             | 280       | 334    | 4.85%   |
| Fujitsu             | 242       | 249    | 4.19%   |
| SanDisk             | 208       | 255    | 3.6%    |
| Hitachi             | 180       | 215    | 3.12%   |
| Apple               | 171       | 201    | 2.96%   |
| SK hynix            | 117       | 140    | 2.03%   |
| A-DATA Technology   | 117       | 199    | 2.03%   |
| Intel               | 116       | 142    | 2.01%   |
| HGST                | 75        | 114    | 1.3%    |
| Micron Technology   | 63        | 65     | 1.09%   |
| China               | 52        | 57     | 0.9%    |
| KIOXIA              | 35        | 39     | 0.61%   |
| SPCC                | 34        | 37     | 0.59%   |
| Unknown             | 32        | 33     | 0.55%   |
| Netac               | 27        | 90     | 0.47%   |
| SABRENT             | 26        | 27     | 0.45%   |
| PNY                 | 26        | 30     | 0.45%   |
| Phison              | 26        | 35     | 0.45%   |
| Transcend           | 25        | 31     | 0.43%   |
| Intenso             | 25        | 33     | 0.43%   |
| Patriot             | 20        | 22     | 0.35%   |
| Silicon Motion      | 19        | 22     | 0.33%   |
| LITEON              | 19        | 22     | 0.33%   |
| Maxtor              | 16        | 20     | 0.28%   |
| Hewlett-Packard     | 15        | 29     | 0.26%   |
| GOODRAM             | 15        | 24     | 0.26%   |
| OCZ                 | 14        | 17     | 0.24%   |
| JMicron Technology  | 14        | 14     | 0.24%   |
| Corsair             | 14        | 23     | 0.24%   |
| LITEONIT            | 12        | 15     | 0.21%   |
| Gigabyte Technology | 12        | 14     | 0.21%   |
| Team                | 10        | 16     | 0.17%   |
| XPG                 | 9         | 11     | 0.16%   |
| Apacer              | 9         | 9      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 200       | 3.19%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 117       | 1.86%   |
| Kingston SA400S37240G 240GB SSD    | 79        | 1.26%   |
| Apple SSD AP0128H 121GB            | 75        | 1.2%    |
| Crucial CT480BX500SSD1 480GB       | 71        | 1.13%   |
| Apple SSD SM0128G 121GB            | 71        | 1.13%   |
| Seagate ST500DM002-1BD142 500GB    | 67        | 1.07%   |
| Toshiba MK1655GSXF 160GB           | 47        | 0.75%   |
| Kingston SA400S37120G 120GB SSD    | 47        | 0.75%   |
| Toshiba DT01ACA050 500GB           | 46        | 0.73%   |
| A-DATA SU800 512GB SSD             | 46        | 0.73%   |
| Samsung SSD 860 EVO 250GB          | 43        | 0.69%   |
| Toshiba MK1653GSX 160GB            | 42        | 0.67%   |
| Samsung SSD 860 EVO 500GB          | 42        | 0.67%   |
| Unknown AGND3R  16GB               | 39        | 0.62%   |
| Kingston SV300S37A120G 120GB SSD   | 39        | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB     | 38        | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB     | 37        | 0.59%   |
| Samsung SSD 970 EVO Plus 1TB       | 34        | 0.54%   |
| Kingston SA400S37480G 480GB SSD    | 34        | 0.54%   |
| Samsung SSD 860 EVO 1TB            | 32        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB        | 32        | 0.51%   |
| Unknown                            | 32        | 0.51%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 31        | 0.49%   |
| Unknown HAG2e  16GB                | 30        | 0.48%   |
| Samsung SSD 970 EVO Plus 500GB     | 29        | 0.46%   |
| Crucial CT500MX500SSD1 500GB       | 29        | 0.46%   |
| Toshiba HDWD110 1TB                | 28        | 0.45%   |
| Hitachi HDS721050CLA362 500GB      | 28        | 0.45%   |
| Samsung SSD 850 EVO 250GB          | 27        | 0.43%   |
| Unknown MMC Card  32GB             | 26        | 0.41%   |
| SABRENT Disk 1TB                   | 26        | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 25        | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB     | 25        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB           | 24        | 0.38%   |
| Toshiba DT01ACA100 1TB             | 24        | 0.38%   |
| Crucial CT240BX500SSD1 240GB       | 24        | 0.38%   |
| Unknown SDW16G  16GB               | 21        | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB     | 21        | 0.33%   |
| Netac SSD 240GB                    | 20        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 714       | 1150   | 31.44%  |
| WDC                 | 564       | 903    | 24.83%  |
| Toshiba             | 370       | 553    | 16.29%  |
| Fujitsu             | 242       | 249    | 10.66%  |
| Hitachi             | 180       | 215    | 7.93%   |
| HGST                | 75        | 114    | 3.3%    |
| Samsung Electronics | 51        | 64     | 2.25%   |
| Unknown             | 18        | 27     | 0.79%   |
| Maxtor              | 15        | 16     | 0.66%   |
| Apple               | 6         | 8      | 0.26%   |
| Hewlett-Packard     | 5         | 14     | 0.22%   |
| USB3.0              | 4         | 4      | 0.18%   |
| JMicron Technology  | 3         | 3      | 0.13%   |
| Intenso             | 2         | 2      | 0.09%   |
| ASMT                | 2         | 3      | 0.09%   |
| ASMedia             | 2         | 2      | 0.09%   |
| Unknown (CF)        | 1         | 1      | 0.04%   |
| TrueNAS             | 1         | 1      | 0.04%   |
| SILICONMOTION       | 1         | 1      | 0.04%   |
| RSH-319             | 1         | 1      | 0.04%   |
| pqi                 | 1         | 1      | 0.04%   |
| Pear 2TB            | 1         | 1      | 0.04%   |
| NAS                 | 1         | 5      | 0.04%   |
| Maxone              | 1         | 1      | 0.04%   |
| MaxDigital          | 1         | 4      | 0.04%   |
| MARSHAL             | 1         | 1      | 0.04%   |
| IBM/Hitachi         | 1         | 1      | 0.04%   |
| IBM-ESXS            | 1         | 2      | 0.04%   |
| HPE                 | 1         | 2      | 0.04%   |
| Hajaan              | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 1      | 0.04%   |
| AMP                 | 1         | 1      | 0.04%   |
| 3ware               | 1         | 4      | 0.04%   |
| 128MB               | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 398       | 527    | 20.88%  |
| Kingston            | 290       | 356    | 15.22%  |
| Crucial             | 256       | 302    | 13.43%  |
| SanDisk             | 156       | 193    | 8.18%   |
| A-DATA Technology   | 95        | 165    | 4.98%   |
| Apple               | 84        | 88     | 4.41%   |
| WDC                 | 83        | 98     | 4.35%   |
| China               | 51        | 56     | 2.68%   |
| Intel               | 43        | 51     | 2.26%   |
| SPCC                | 30        | 30     | 1.57%   |
| Micron Technology   | 30        | 31     | 1.57%   |
| Netac               | 27        | 90     | 1.42%   |
| Toshiba             | 25        | 28     | 1.31%   |
| SK hynix            | 25        | 30     | 1.31%   |
| Transcend           | 24        | 30     | 1.26%   |
| Intenso             | 21        | 27     | 1.1%    |
| PNY                 | 20        | 23     | 1.05%   |
| Patriot             | 18        | 19     | 0.94%   |
| LITEON              | 16        | 19     | 0.84%   |
| OCZ                 | 14        | 17     | 0.73%   |
| LITEONIT            | 12        | 15     | 0.63%   |
| Goodram             | 12        | 17     | 0.63%   |
| Unknown             | 10        | 11     | 0.52%   |
| Team                | 9         | 15     | 0.47%   |
| Apacer              | 8         | 8      | 0.42%   |
| Seagate             | 7         | 7      | 0.37%   |
| Plextor             | 7         | 9      | 0.37%   |
| Gigabyte Technology | 7         | 7      | 0.37%   |
| Unknown             | 6         | 9      | 0.31%   |
| Lexar               | 6         | 8      | 0.31%   |
| Hajaan              | 6         | 7      | 0.31%   |
| Corsair             | 6         | 9      | 0.31%   |
| Mushkin             | 5         | 6      | 0.26%   |
| Hewlett-Packard     | 5         | 5      | 0.26%   |
| ASMT                | 5         | 6      | 0.26%   |
| Xinhaike            | 4         | 6      | 0.21%   |
| LDLC                | 4         | 4      | 0.21%   |
| KIOXIA-EXCERIA      | 4         | 7      | 0.21%   |
| KingDian            | 4         | 4      | 0.21%   |
| Foxline             | 4         | 4      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2008      | 3357   | 37.55%  |
| SSD     | 1722      | 2427   | 32.2%   |
| NVMe    | 1246      | 1701   | 23.3%   |
| MMC     | 320       | 408    | 5.98%   |
| Unknown | 52        | 80     | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3161      | 5545   | 64.54%  |
| NVMe | 1216      | 1660   | 24.83%  |
| MMC  | 320       | 408    | 6.53%   |
| SAS  | 201       | 360    | 4.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 2537      | 3447   | 65.27%  |
| 0.51-1.0    | 867       | 1289   | 22.31%  |
| 1.01-2.0    | 229       | 400    | 5.89%   |
| 3.01-4.0    | 102       | 253    | 2.62%   |
| 4.01-10.0   | 84        | 219    | 2.16%   |
| 2.01-3.0    | 44        | 72     | 1.13%   |
| 10.01-20.0  | 23        | 100    | 0.59%   |
| 50.01-100.0 | 1         | 4      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1226      | 27.48%  |
| 101-250        | 942       | 21.11%  |
| 251-500        | 717       | 16.07%  |
| 501-1000       | 444       | 9.95%   |
| 1-20           | 261       | 5.85%   |
| 51-100         | 221       | 4.95%   |
| 1001-2000      | 218       | 4.89%   |
| More than 3000 | 192       | 4.3%    |
| 21-50          | 155       | 3.47%   |
| 2001-3000      | 86        | 1.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1537      | 33.91%  |
| Unknown        | 1226      | 27.05%  |
| 21-50          | 393       | 8.67%   |
| 101-250        | 380       | 8.38%   |
| 51-100         | 339       | 7.48%   |
| 251-500        | 249       | 5.49%   |
| 501-1000       | 171       | 3.77%   |
| 1001-2000      | 95        | 2.1%    |
| More than 3000 | 87        | 1.92%   |
| 2001-3000      | 40        | 0.88%   |
| 0              | 16        | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 20        | 20     | 3.44%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 17        | 20     | 2.92%   |
| Seagate ST500DM002-1BD142 500GB    | 16        | 16     | 2.75%   |
| Toshiba MK1653GSX 160GB            | 9         | 9      | 1.55%   |
| Kingston SV300S37A120G 120GB SSD   | 9         | 9      | 1.55%   |
| Toshiba MK1655GSXF 160GB           | 8         | 8      | 1.37%   |
| Hitachi HDS721050CLA362 500GB      | 8         | 8      | 1.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 7         | 8      | 1.2%    |
| WDC WD5000AAKX-08U6AA0 500GB       | 6         | 6      | 1.03%   |
| Seagate ST9500325AS 500GB          | 6         | 8      | 1.03%   |
| Hitachi HTS543216L9SA02 160GB      | 6         | 6      | 1.03%   |
| Seagate ST9500420AS 500GB          | 5         | 5      | 0.86%   |
| Seagate ST3500418AS 500GB          | 5         | 5      | 0.86%   |
| Seagate ST3250318AS 250GB          | 5         | 5      | 0.86%   |
| Seagate ST250DM000-1BD141 250GB    | 5         | 5      | 0.86%   |
| Seagate ST1000DM003-9YN162 1TB     | 5         | 6      | 0.86%   |
| Hitachi HTS542512K9SA00 120GB      | 5         | 6      | 0.86%   |
| Hitachi HDS721050DLE630 500GB      | 5         | 5      | 0.86%   |
| WDC WD20EARS-00MVWB0 2TB           | 4         | 4      | 0.69%   |
| WDC WD1600BUDT-63DPZY0 160GB       | 4         | 4      | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB           | 4         | 4      | 0.69%   |
| Toshiba DT01ACA050 500GB           | 4         | 5      | 0.69%   |
| HGST HTS725050A7E630 500GB         | 4         | 4      | 0.69%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 3         | 3      | 0.52%   |
| WDC WD5000AAKX-001CA0 500GB        | 3         | 3      | 0.52%   |
| WDC WD3200AAJS-08L7A0 320GB        | 3         | 3      | 0.52%   |
| Seagate ST500LT012-9WS142 500GB    | 3         | 3      | 0.52%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 3      | 0.52%   |
| Seagate ST500LM000-SSHD-8GB        | 3         | 3      | 0.52%   |
| Seagate ST31500341AS 1TB           | 3         | 5      | 0.52%   |
| Seagate ST3120827AS 120GB          | 3         | 4      | 0.52%   |
| Seagate ST31000528AS 1TB           | 3         | 3      | 0.52%   |
| Kingston SHFS37A120G 120GB SSD     | 3         | 3      | 0.52%   |
| Hitachi HTS547575A9E384 752GB      | 3         | 3      | 0.52%   |
| Hitachi HTS545050B9A300 500GB      | 3         | 3      | 0.52%   |
| Hitachi HTS545032B9A300 320GB      | 3         | 5      | 0.52%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 0.52%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 2         | 3      | 0.34%   |
| WDC WD2500AAJS-00YZCA0 250GB       | 2         | 2      | 0.34%   |
| WDC WD2500AAJS-00B4A0 250GB        | 2         | 2      | 0.34%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 146       | 181    | 25.7%   |
| WDC                 | 132       | 164    | 23.24%  |
| Hitachi             | 69        | 77     | 12.15%  |
| Toshiba             | 39        | 40     | 6.87%   |
| Samsung Electronics | 29        | 31     | 5.11%   |
| Fujitsu             | 29        | 30     | 5.11%   |
| Kingston            | 21        | 24     | 3.7%    |
| Intel               | 18        | 24     | 3.17%   |
| HGST                | 14        | 14     | 2.46%   |
| SK hynix            | 13        | 16     | 2.29%   |
| Crucial             | 9         | 11     | 1.58%   |
| A-DATA Technology   | 9         | 11     | 1.58%   |
| Micron Technology   | 8         | 8      | 1.41%   |
| SanDisk             | 7         | 8      | 1.23%   |
| Maxtor              | 5         | 5      | 0.88%   |
| LITEONIT            | 3         | 3      | 0.53%   |
| LITEON              | 3         | 3      | 0.53%   |
| Hewlett-Packard     | 2         | 3      | 0.35%   |
| China               | 2         | 2      | 0.35%   |
| USB3.0              | 1         | 1      | 0.18%   |
| ShiJi               | 1         | 1      | 0.18%   |
| PNY                 | 1         | 1      | 0.18%   |
| Lenovo              | 1         | 1      | 0.18%   |
| KingDian            | 1         | 1      | 0.18%   |
| JMicron Technology  | 1         | 1      | 0.18%   |
| IBM/Hitachi         | 1         | 1      | 0.18%   |
| GOODRAM             | 1         | 1      | 0.18%   |
| DGM                 | 1         | 1      | 0.18%   |
| ASMedia             | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 146       | 181    | 32.44%  |
| WDC                 | 129       | 160    | 28.67%  |
| Hitachi             | 69        | 77     | 15.33%  |
| Toshiba             | 39        | 40     | 8.67%   |
| Fujitsu             | 29        | 30     | 6.44%   |
| HGST                | 14        | 14     | 3.11%   |
| Samsung Electronics | 13        | 13     | 2.89%   |
| Maxtor              | 5         | 5      | 1.11%   |
| Hewlett-Packard     | 2         | 3      | 0.44%   |
| USB3.0              | 1         | 1      | 0.22%   |
| JMicron Technology  | 1         | 1      | 0.22%   |
| IBM/Hitachi         | 1         | 1      | 0.22%   |
| ASMedia             | 1         | 1      | 0.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 429       | 527    | 78.28%  |
| SSD  | 99        | 112    | 18.07%  |
| NVMe | 20        | 26     | 3.65%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                 | 1         | 1      | 10%     |
| WDC WD4001FFSX-68JNUN0 4TB                   | 1         | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 10%     |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 10%     |
| Seagate ST500DM005 HD502HJ 500GB             | 1         | 1      | 10%     |
| Seagate ST3500830AS 500GB                    | 1         | 1      | 10%     |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB | 1         | 1      | 10%     |
| KingDian S400 120GB                          | 1         | 1      | 10%     |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 10%     |
| HGST HDN724040ALE640 4TB                     | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 40%     |
| WDC                 | 2         | 2      | 20%     |
| Samsung Electronics | 1         | 1      | 10%     |
| KingDian            | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| HGST                | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3189      | 5411   | 67.43%  |
| Detected | 990       | 1885   | 20.93%  |
| Malfunc  | 538       | 665    | 11.38%  |
| Failed   | 10        | 10     | 0.21%   |
| Limited  | 2         | 2      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2539      | 50.08%  |
| AMD                              | 637       | 12.56%  |
| Samsung Electronics              | 549       | 10.83%  |
| Nvidia                           | 357       | 7.04%   |
| SanDisk                          | 186       | 3.67%   |
| SK hynix                         | 90        | 1.78%   |
| Apple                            | 82        | 1.62%   |
| ASMedia Technology               | 67        | 1.32%   |
| Phison Electronics               | 57        | 1.12%   |
| Kingston Technology Company      | 56        | 1.1%    |
| Marvell Technology Group         | 52        | 1.03%   |
| JMicron Technology               | 44        | 0.87%   |
| Toshiba America Info Systems     | 43        | 0.85%   |
| Silicon Motion                   | 36        | 0.71%   |
| Micron Technology                | 34        | 0.67%   |
| KIOXIA                           | 34        | 0.67%   |
| Micron/Crucial Technology        | 33        | 0.65%   |
| LSI Logic / Symbios Logic        | 31        | 0.61%   |
| ADATA Technology                 | 28        | 0.55%   |
| Broadcom / LSI                   | 21        | 0.41%   |
| VIA Technologies                 | 20        | 0.39%   |
| Solid State Storage Technology   | 9         | 0.18%   |
| Hewlett-Packard                  | 8         | 0.16%   |
| Union Memory (Shenzhen)          | 6         | 0.12%   |
| Realtek Semiconductor            | 6         | 0.12%   |
| Adaptec                          | 6         | 0.12%   |
| Silicon Image                    | 4         | 0.08%   |
| Shenzhen Longsys Electronics     | 4         | 0.08%   |
| Seagate Technology               | 4         | 0.08%   |
| Lenovo                           | 4         | 0.08%   |
| Silicon Integrated Systems [SiS] | 3         | 0.06%   |
| Lite-On Technology               | 3         | 0.06%   |
| 3ware                            | 3         | 0.06%   |
| ULi Electronics                  | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| Unknown                          | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 460       | 7.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 321       | 5.49%   |
| Nvidia MCP79 AHCI Controller                                                            | 310       | 5.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 206       | 3.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 175       | 2.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 140       | 2.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 133       | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 114       | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 110       | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 103       | 1.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 98        | 1.68%   |
| AMD 400 Series Chipset SATA Controller                                                  | 91        | 1.56%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 89        | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 84        | 1.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 82        | 1.4%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 80        | 1.37%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 79        | 1.35%   |
| Samsung Electronics SATA controller                                                     | 78        | 1.33%   |
| Apple S1X NVMe Controller                                                               | 77        | 1.32%   |
| Samsung NVMe SSD Controller 980                                                         | 71        | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 71        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 65        | 1.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 58        | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 56        | 0.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 56        | 0.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 55        | 0.94%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 55        | 0.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 55        | 0.94%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 54        | 0.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 53        | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 52        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 52        | 0.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 50        | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 47        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 47        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 47        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 43        | 0.74%   |
| SK hynix Gold P31 SSD                                                                   | 41        | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 40        | 0.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 40        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3055      | 58.44%  |
| NVMe | 1215      | 23.24%  |
| IDE  | 632       | 12.09%  |
| RAID | 271       | 5.18%   |
| SAS  | 43        | 0.82%   |
| SCSI | 12        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3479      | 79.63%  |
| AMD          | 773       | 17.69%  |
| ARM          | 107       | 2.45%   |
| CentaurHauls | 4         | 0.09%   |
| Phytium      | 3         | 0.07%   |
| Unknown      | 2         | 0.05%   |
| HISILICON    | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 304       | 6.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 159       | 3.64%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 143       | 3.27%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 86        | 1.97%   |
| ARM Processor                                 | 85        | 1.94%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 59        | 1.35%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 58        | 1.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 55        | 1.26%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 44        | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 44        | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 37        | 0.85%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 33        | 0.75%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 33        | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 31        | 0.71%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 28        | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 28        | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 28        | 0.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 27        | 0.62%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 26        | 0.59%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 25        | 0.57%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 25        | 0.57%   |
| AMD Ryzen 5 3600 6-Core Processor             | 24        | 0.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 23        | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 23        | 0.53%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 23        | 0.53%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 23        | 0.53%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 23        | 0.53%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 22        | 0.5%    |
| Intel Atom CPU N270 @ 1.60GHz                 | 21        | 0.48%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 20        | 0.46%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 20        | 0.46%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 19        | 0.43%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 19        | 0.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 18        | 0.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 18        | 0.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 18        | 0.41%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 18        | 0.41%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 17        | 0.39%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 17        | 0.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 899       | 20.57%  |
| Intel Core i7           | 480       | 10.98%  |
| Intel Core 2 Duo        | 466       | 10.66%  |
| Other                   | 440       | 10.07%  |
| Intel Core i3           | 329       | 7.53%   |
| Intel Celeron           | 307       | 7.03%   |
| AMD Ryzen 5             | 205       | 4.69%   |
| Intel Pentium           | 190       | 4.35%   |
| Intel Xeon              | 145       | 3.32%   |
| AMD Ryzen 7             | 118       | 2.7%    |
| Intel Atom              | 77        | 1.76%   |
| Intel Core 2            | 70        | 1.6%    |
| Intel Pentium Dual-Core | 55        | 1.26%   |
| AMD Ryzen 9             | 53        | 1.21%   |
| AMD Ryzen 3             | 43        | 0.98%   |
| AMD FX                  | 42        | 0.96%   |
| Intel Core 2 Quad       | 26        | 0.59%   |
| AMD A6                  | 25        | 0.57%   |
| Intel Core i9           | 21        | 0.48%   |
| AMD Ryzen 7 PRO         | 21        | 0.48%   |
| AMD A10                 | 19        | 0.43%   |
| Intel Pentium M         | 17        | 0.39%   |
| AMD Ryzen Threadripper  | 17        | 0.39%   |
| AMD Athlon              | 17        | 0.39%   |
| Intel Pentium Gold      | 16        | 0.37%   |
| Intel Pentium 4         | 15        | 0.34%   |
| Intel Pentium Dual      | 14        | 0.32%   |
| AMD Athlon 64 X2        | 14        | 0.32%   |
| AMD A4                  | 14        | 0.32%   |
| AMD Ryzen 5 PRO         | 13        | 0.3%    |
| AMD Athlon II X2        | 13        | 0.3%    |
| AMD A8                  | 13        | 0.3%    |
| Intel Genuine           | 12        | 0.27%   |
| AMD Phenom II X4        | 10        | 0.23%   |
| AMD E1                  | 10        | 0.23%   |
| AMD Opteron             | 9         | 0.21%   |
| ARM Allwinner           | 8         | 0.18%   |
| Intel Pentium Silver    | 7         | 0.16%   |
| Intel Celeron M         | 7         | 0.16%   |
| AMD Sempron             | 7         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2030      | 46.42%  |
| 4       | 1417      | 32.4%   |
| 6       | 355       | 8.12%   |
| 8       | 265       | 6.06%   |
| 1       | 152       | 3.48%   |
| 16      | 47        | 1.07%   |
| 12      | 40        | 0.91%   |
| 3       | 17        | 0.39%   |
| 10      | 12        | 0.27%   |
| 32      | 8         | 0.18%   |
| 24      | 7         | 0.16%   |
| Unknown | 5         | 0.11%   |
| 20      | 4         | 0.09%   |
| 14      | 4         | 0.09%   |
| 28      | 3         | 0.07%   |
| 48      | 2         | 0.05%   |
| 44      | 2         | 0.05%   |
| 80      | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4300      | 98.4%   |
| 2       | 64        | 1.46%   |
| Unknown | 5         | 0.11%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2446      | 55.96%  |
| 1       | 1919      | 43.9%   |
| Unknown | 5         | 0.11%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4246      | 97.16%  |
| 32-bit         | 80        | 1.83%   |
| Unknown        | 32        | 0.73%   |
| 64-bit         | 12        | 0.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 769       | 17.37%  |
| 0x1067a    | 444       | 10.03%  |
| 0x806c1    | 219       | 4.95%   |
| 0x306c3    | 204       | 4.61%   |
| 0x306d4    | 193       | 4.36%   |
| 0x206a7    | 186       | 4.2%    |
| 0x306a9    | 185       | 4.18%   |
| 0x906ea    | 116       | 2.62%   |
| 0x30678    | 102       | 2.3%    |
| 0x506e3    | 97        | 2.19%   |
| 0x806ec    | 85        | 1.92%   |
| 0x806e9    | 77        | 1.74%   |
| 0x6f6      | 67        | 1.51%   |
| 0x08108109 | 66        | 1.49%   |
| 0x806ea    | 63        | 1.42%   |
| 0xa0653    | 61        | 1.38%   |
| 0x906eb    | 58        | 1.31%   |
| 0x406e3    | 55        | 1.24%   |
| 0x906e9    | 51        | 1.15%   |
| 0x406c4    | 50        | 1.13%   |
| 0x40651    | 50        | 1.13%   |
| 0x08701021 | 43        | 0.97%   |
| 0x10676    | 41        | 0.93%   |
| 0x20655    | 40        | 0.9%    |
| 0x08600106 | 39        | 0.88%   |
| 0xa0655    | 38        | 0.86%   |
| 0xa0652    | 36        | 0.81%   |
| 0x6fd      | 34        | 0.77%   |
| 0x0a50000c | 33        | 0.75%   |
| 0x0600611a | 33        | 0.75%   |
| 0x706a8    | 31        | 0.7%    |
| 0x0a201016 | 29        | 0.66%   |
| 0x08608103 | 28        | 0.63%   |
| 0x506c9    | 26        | 0.59%   |
| 0x106c2    | 26        | 0.59%   |
| 0x706e5    | 25        | 0.56%   |
| 0x0800820d | 25        | 0.56%   |
| 0xa0671    | 23        | 0.52%   |
| 0x206d7    | 21        | 0.47%   |
| 0x6fb      | 20        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 586       | 13.4%   |
| Penryn           | 511       | 11.69%  |
| Haswell          | 333       | 7.61%   |
| TigerLake        | 252       | 5.76%   |
| SandyBridge      | 246       | 5.63%   |
| IvyBridge        | 246       | 5.63%   |
| Broadwell        | 217       | 4.96%   |
| Skylake          | 192       | 4.39%   |
| Silvermont       | 191       | 4.37%   |
| Unknown          | 188       | 4.3%    |
| Zen 2            | 153       | 3.5%    |
| Core             | 150       | 3.43%   |
| CometLake        | 150       | 3.43%   |
| Zen+             | 147       | 3.36%   |
| Zen 3            | 104       | 2.38%   |
| Westmere         | 89        | 2.04%   |
| Excavator        | 67        | 1.53%   |
| Zen              | 55        | 1.26%   |
| Goldmont plus    | 50        | 1.14%   |
| K10              | 49        | 1.12%   |
| IceLake          | 47        | 1.07%   |
| Bonnell          | 47        | 1.07%   |
| Piledriver       | 43        | 0.98%   |
| P6               | 33        | 0.75%   |
| Nehalem          | 30        | 0.69%   |
| Goldmont         | 30        | 0.69%   |
| K8 Hammer        | 26        | 0.59%   |
| NetBurst         | 25        | 0.57%   |
| Bobcat           | 19        | 0.43%   |
| Puma             | 17        | 0.39%   |
| Steamroller      | 16        | 0.37%   |
| Jaguar           | 14        | 0.32%   |
| Tremont          | 13        | 0.3%    |
| Bulldozer        | 13        | 0.3%    |
| K10 Llano        | 10        | 0.23%   |
| Alderlake Hybrid | 9         | 0.21%   |
| K6               | 3         | 0.07%   |
| K8 & K10 hybrid  | 2         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2578      | 54.32%  |
| Nvidia                           | 1238      | 26.09%  |
| AMD                              | 825       | 17.38%  |
| Matrox Electronics Systems       | 50        | 1.05%   |
| ASPEED Technology                | 44        | 0.93%   |
| VIA Technologies                 | 6         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.06%   |
| S3 Graphics                      | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 303       | 6.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 238       | 4.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 160       | 3.24%   |
| Intel HD Graphics 6000                                                                   | 147       | 2.98%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 138       | 2.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 126       | 2.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 120       | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 113       | 2.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 103       | 2.09%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 86        | 1.74%   |
| Intel UHD Graphics 620                                                                   | 80        | 1.62%   |
| AMD Renoir                                                                               | 78        | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 66        | 1.34%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 66        | 1.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 66        | 1.34%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 64        | 1.3%    |
| Intel HD Graphics 620                                                                    | 64        | 1.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 61        | 1.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 61        | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 60        | 1.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 53        | 1.07%   |
| Intel HD Graphics 5500                                                                   | 52        | 1.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 52        | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 48        | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 48        | 0.97%   |
| Intel HD Graphics 530                                                                    | 48        | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 46        | 0.93%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 46        | 0.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 45        | 0.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 44        | 0.89%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 44        | 0.89%   |
| Intel HD Graphics 630                                                                    | 43        | 0.87%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 43        | 0.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 42        | 0.85%   |
| AMD Cezanne                                                                              | 42        | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 0.75%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 36        | 0.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 36        | 0.73%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 34        | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 33        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 2149      | 49.03%  |
| 1 x Nvidia                        | 861       | 19.64%  |
| 1 x AMD                           | 673       | 15.35%  |
| Intel + Nvidia                    | 322       | 7.35%   |
| Other                             | 124       | 2.83%   |
| Intel + AMD                       | 60        | 1.37%   |
| 1 x Matrox                        | 47        | 1.07%   |
| AMD + Nvidia                      | 44        | 1%      |
| 2 x AMD                           | 40        | 0.91%   |
| 1 x ASPEED                        | 35        | 0.8%    |
| 1 x VIA                           | 6         | 0.14%   |
| AMD + ASPEED                      | 5         | 0.11%   |
| 1 x SiS                           | 3         | 0.07%   |
| Nvidia + ASPEED                   | 3         | 0.07%   |
| Intel + 2 x Nvidia                | 3         | 0.07%   |
| 2 x Nvidia                        | 2         | 0.05%   |
| Nvidia + Matrox                   | 2         | 0.05%   |
| 3 x AMD                           | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.02%   |
| 1 x S3 Graphics                   | 1         | 0.02%   |
| AMD + Matrox                      | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3103      | 70.64%  |
| Unknown     | 946       | 21.53%  |
| Proprietary | 344       | 7.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3175      | 72.03%  |
| 0.01-0.5   | 586       | 13.29%  |
| 1.01-2.0   | 216       | 4.9%    |
| 3.01-4.0   | 141       | 3.2%    |
| 0.51-1.0   | 138       | 3.13%   |
| 7.01-8.0   | 78        | 1.77%   |
| 5.01-6.0   | 43        | 0.98%   |
| 8.01-16.0  | 15        | 0.34%   |
| 2.01-3.0   | 12        | 0.27%   |
| 16.01-24.0 | 3         | 0.07%   |
| 24.01-32.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 574       | 14.89%  |
| AU Optronics            | 484       | 12.56%  |
| Samsung Electronics     | 353       | 9.16%   |
| BOE                     | 332       | 8.61%   |
| Chimei Innolux          | 262       | 6.8%    |
| LG Display              | 257       | 6.67%   |
| Dell                    | 184       | 4.77%   |
| Goldstar                | 168       | 4.36%   |
| Hewlett-Packard         | 97        | 2.52%   |
| BenQ                    | 94        | 2.44%   |
| Acer                    | 86        | 2.23%   |
| Lenovo                  | 81        | 2.1%    |
| AOC                     | 76        | 1.97%   |
| Ancor Communications    | 75        | 1.95%   |
| Philips                 | 63        | 1.63%   |
| Sharp                   | 55        | 1.43%   |
| Iiyama                  | 42        | 1.09%   |
| ViewSonic               | 41        | 1.06%   |
| Unknown                 | 41        | 1.06%   |
| Chi Mei Optoelectronics | 39        | 1.01%   |
| Eizo                    | 31        | 0.8%    |
| InfoVision              | 30        | 0.78%   |
| PANDA                   | 23        | 0.6%    |
| HannStar                | 22        | 0.57%   |
| ASUSTek Computer        | 22        | 0.57%   |
| NEC Computers           | 18        | 0.47%   |
| Sony                    | 17        | 0.44%   |
| LG Philips              | 14        | 0.36%   |
| LG Electronics          | 12        | 0.31%   |
| CSO                     | 11        | 0.29%   |
| Panasonic               | 10        | 0.26%   |
| Toshiba                 | 9         | 0.23%   |
| Vestel Elektronik       | 8         | 0.21%   |
| MSI                     | 7         | 0.18%   |
| Unknown                 | 7         | 0.18%   |
| Vizio                   | 6         | 0.16%   |
| Medion                  | 6         | 0.16%   |
| Mi                      | 5         | 0.13%   |
| Hitachi                 | 5         | 0.13%   |
| Gigabyte Technology     | 5         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 199       | 5.05%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 149       | 3.78%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch       | 110       | 2.79%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 52        | 1.32%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 41        | 1.04%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 40        | 1.02%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 35        | 0.89%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 34        | 0.86%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 32        | 0.81%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 24        | 0.61%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 23        | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 21        | 0.53%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 21        | 0.53%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 20        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 16        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 16        | 0.41%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 15        | 0.38%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch               | 14        | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 13        | 0.33%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 13        | 0.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 11        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 11        | 0.28%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                 | 11        | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 11        | 0.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 11        | 0.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 10        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 10        | 0.25%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 9         | 0.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 9         | 0.23%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch   | 8         | 0.2%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 8         | 0.2%    |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch          | 8         | 0.2%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 8         | 0.2%    |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 8         | 0.2%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 8         | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 7         | 0.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 7         | 0.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 7         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1445      | 38.93%  |
| 1366x768 (WXGA)    | 663       | 17.86%  |
| 1280x800 (WXGA)    | 443       | 11.93%  |
| 3840x2160 (4K)     | 181       | 4.88%   |
| 2560x1440 (QHD)    | 135       | 3.64%   |
| 1280x1024 (SXGA)   | 129       | 3.48%   |
| 1440x900 (WXGA+)   | 126       | 3.39%   |
| 1600x900 (HD+)     | 112       | 3.02%   |
| 1920x1200 (WUXGA)  | 73        | 1.97%   |
| 1680x1050 (WSXGA+) | 68        | 1.83%   |
| Unknown            | 39        | 1.05%   |
| 2288x1287          | 33        | 0.89%   |
| 1024x600           | 33        | 0.89%   |
| 1024x768 (XGA)     | 29        | 0.78%   |
| 2560x1080          | 21        | 0.57%   |
| 1360x768           | 21        | 0.57%   |
| 3440x1440          | 20        | 0.54%   |
| 2560x1600          | 20        | 0.54%   |
| 1600x1200          | 15        | 0.4%    |
| 3840x1080          | 14        | 0.38%   |
| 1920x540           | 10        | 0.27%   |
| 2880x1800          | 8         | 0.22%   |
| 3840x2400          | 7         | 0.19%   |
| 2160x1440          | 7         | 0.19%   |
| 4480x1440          | 5         | 0.13%   |
| 2736x1824          | 4         | 0.11%   |
| 1400x1050          | 4         | 0.11%   |
| 3200x1080          | 3         | 0.08%   |
| 1920x1280          | 3         | 0.08%   |
| 5760x1080          | 2         | 0.05%   |
| 5360x1440          | 2         | 0.05%   |
| 3840x1600          | 2         | 0.05%   |
| 3840x1100          | 2         | 0.05%   |
| 3360x1050          | 2         | 0.05%   |
| 3200x1800 (QHD+)   | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |
| 2048x1152          | 2         | 0.05%   |
| 1800x1200          | 2         | 0.05%   |
| 7680x4320          | 1         | 0.03%   |
| 6400x2160          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 881       | 23.07%  |
| 15      | 683       | 17.89%  |
| 14      | 270       | 7.07%   |
| 24      | 254       | 6.65%   |
| 11      | 219       | 5.74%   |
| 23      | 213       | 5.58%   |
| 27      | 212       | 5.55%   |
| 17      | 163       | 4.27%   |
| 21      | 161       | 4.22%   |
| Unknown | 110       | 2.88%   |
| 19      | 93        | 2.44%   |
| 12      | 85        | 2.23%   |
| 18      | 67        | 1.75%   |
| 31      | 63        | 1.65%   |
| 22      | 50        | 1.31%   |
| 10      | 36        | 0.94%   |
| 20      | 34        | 0.89%   |
| 142     | 32        | 0.84%   |
| 34      | 28        | 0.73%   |
| 84      | 19        | 0.5%    |
| 72      | 15        | 0.39%   |
| 32      | 15        | 0.39%   |
| 25      | 14        | 0.37%   |
| 16      | 13        | 0.34%   |
| 29      | 9         | 0.24%   |
| 54      | 8         | 0.21%   |
| 28      | 8         | 0.21%   |
| 52      | 6         | 0.16%   |
| 40      | 6         | 0.16%   |
| 48      | 5         | 0.13%   |
| 33      | 5         | 0.13%   |
| 65      | 4         | 0.1%    |
| 46      | 4         | 0.1%    |
| 26      | 4         | 0.1%    |
| 55      | 3         | 0.08%   |
| 47      | 3         | 0.08%   |
| 43      | 3         | 0.08%   |
| 42      | 3         | 0.08%   |
| 39      | 3         | 0.08%   |
| 35      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1180      | 31.38%  |
| 201-300        | 1047      | 27.85%  |
| 501-600        | 623       | 16.57%  |
| 401-500        | 341       | 9.07%   |
| 351-400        | 178       | 4.73%   |
| Unknown        | 110       | 2.93%   |
| 601-700        | 108       | 2.87%   |
| 701-800        | 45        | 1.2%    |
| 1001-1500      | 37        | 0.98%   |
| 1501-2000      | 36        | 0.96%   |
| More than 2000 | 32        | 0.85%   |
| 801-900        | 15        | 0.4%    |
| 901-1000       | 6         | 0.16%   |
| 101-200        | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2374      | 67.62%  |
| 16/10   | 758       | 21.59%  |
| 5/4     | 120       | 3.42%   |
| Unknown | 85        | 2.42%   |
| 4/3     | 55        | 1.57%   |
| 21/9    | 37        | 1.05%   |
| 1.00    | 34        | 0.97%   |
| 3/2     | 29        | 0.83%   |
| 6/5     | 6         | 0.17%   |
| 32/9    | 4         | 0.11%   |
| 2.65    | 4         | 0.11%   |
| 3.40    | 2         | 0.06%   |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 858       | 22.67%  |
| 101-110        | 680       | 17.97%  |
| 201-250        | 540       | 14.27%  |
| 71-80          | 293       | 7.74%   |
| 51-60          | 221       | 5.84%   |
| 301-350        | 213       | 5.63%   |
| 151-200        | 180       | 4.76%   |
| 351-500        | 122       | 3.22%   |
| 141-150        | 117       | 3.09%   |
| Unknown        | 110       | 2.91%   |
| 251-300        | 95        | 2.51%   |
| More than 1000 | 92        | 2.43%   |
| 121-130        | 85        | 2.25%   |
| 61-70          | 79        | 2.09%   |
| 41-50          | 36        | 0.95%   |
| 501-1000       | 29        | 0.77%   |
| 131-140        | 15        | 0.4%    |
| 111-120        | 10        | 0.26%   |
| 91-100         | 8         | 0.21%   |
| 1-40           | 2         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1091      | 29.42%  |
| 101-120       | 1081      | 29.15%  |
| 51-100        | 1006      | 27.13%  |
| 161-240       | 284       | 7.66%   |
| Unknown       | 110       | 2.97%   |
| 1-50          | 86        | 2.32%   |
| More than 240 | 50        | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2898      | 65.43%  |
| 0     | 986       | 22.26%  |
| 2     | 493       | 11.13%  |
| 3     | 49        | 1.11%   |
| 4     | 2         | 0.05%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2001      | 31.98%  |
| Intel                             | 1875      | 29.96%  |
| Broadcom                          | 582       | 9.3%    |
| Qualcomm Atheros                  | 567       | 9.06%   |
| Nvidia                            | 351       | 5.61%   |
| Broadcom Limited                  | 207       | 3.31%   |
| Marvell Technology Group          | 119       | 1.9%    |
| Ralink Technology                 | 47        | 0.75%   |
| TP-Link                           | 43        | 0.69%   |
| Ralink                            | 37        | 0.59%   |
| MediaTek                          | 36        | 0.58%   |
| ASIX Electronics                  | 29        | 0.46%   |
| Samsung Electronics               | 22        | 0.35%   |
| Dell                              | 17        | 0.27%   |
| Qualcomm Atheros Communications   | 16        | 0.26%   |
| Microchip Technology              | 16        | 0.26%   |
| Sierra Wireless                   | 15        | 0.24%   |
| Qualcomm                          | 13        | 0.21%   |
| DisplayLink                       | 12        | 0.19%   |
| NetGear                           | 11        | 0.18%   |
| D-Link                            | 11        | 0.18%   |
| Microsoft                         | 10        | 0.16%   |
| Mellanox Technologies             | 10        | 0.16%   |
| Lenovo                            | 10        | 0.16%   |
| Huawei Technologies               | 10        | 0.16%   |
| D-Link System                     | 10        | 0.16%   |
| ASUSTek Computer                  | 10        | 0.16%   |
| Aquantia                          | 10        | 0.16%   |
| Xiaomi                            | 8         | 0.13%   |
| JMicron Technology                | 8         | 0.13%   |
| ICS Advent                        | 8         | 0.13%   |
| Dresden Elektronik                | 7         | 0.11%   |
| VIA Technologies                  | 6         | 0.1%    |
| Hewlett-Packard                   | 6         | 0.1%    |
| Cypress Semiconductor             | 6         | 0.1%    |
| FIBOCOM                           | 5         | 0.08%   |
| Ericsson Business Mobile Networks | 5         | 0.08%   |
| Edimax Technology                 | 5         | 0.08%   |
| American Megatrends               | 5         | 0.08%   |
| Standard Microsystems             | 4         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1446      | 19.95%  |
| Nvidia MCP79 Ethernet                                                                 | 311       | 4.29%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 305       | 4.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 220       | 3.03%   |
| Intel Wi-Fi 6 AX201                                                                   | 208       | 2.87%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 149       | 2.06%   |
| Intel Wi-Fi 6 AX200                                                                   | 139       | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 130       | 1.79%   |
| Intel Ethernet Connection (13) I219-V                                                 | 127       | 1.75%   |
| Intel Wireless 7260                                                                   | 125       | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 119       | 1.64%   |
| Intel Wireless 8265 / 8275                                                            | 102       | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 96        | 1.32%   |
| Intel Wireless 7265                                                                   | 93        | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 68        | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 66        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 62        | 0.86%   |
| Intel I211 Gigabit Network Connection                                                 | 62        | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 60        | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 59        | 0.81%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 0.77%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 56        | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 55        | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 55        | 0.76%   |
| Intel Wireless 8260                                                                   | 54        | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 54        | 0.74%   |
| Intel I210 Gigabit Network Connection                                                 | 53        | 0.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 48        | 0.66%   |
| Intel Wireless 3165                                                                   | 47        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 45        | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                                  | 42        | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 40        | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 40        | 0.55%   |
| Intel Ethernet Connection I217-LM                                                     | 39        | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                                  | 39        | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 33        | 0.46%   |
| Realtek 802.11ac NIC                                                                  | 33        | 0.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 33        | 0.46%   |
| Intel Ethernet Connection (14) I219-V                                                 | 33        | 0.46%   |
| Intel 82579V Gigabit Network Connection                                               | 33        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1355      | 44.01%  |
| Qualcomm Atheros                  | 466       | 15.13%  |
| Broadcom                          | 455       | 14.78%  |
| Realtek Semiconductor             | 366       | 11.89%  |
| Broadcom Limited                  | 175       | 5.68%   |
| Ralink Technology                 | 47        | 1.53%   |
| Ralink                            | 37        | 1.2%    |
| MediaTek                          | 33        | 1.07%   |
| TP-Link                           | 27        | 0.88%   |
| Qualcomm Atheros Communications   | 16        | 0.52%   |
| Sierra Wireless                   | 15        | 0.49%   |
| NetGear                           | 11        | 0.36%   |
| ASUSTek Computer                  | 10        | 0.32%   |
| D-Link                            | 9         | 0.29%   |
| Dell                              | 8         | 0.26%   |
| Microsoft                         | 7         | 0.23%   |
| Fibocom                           | 5         | 0.16%   |
| Edimax Technology                 | 5         | 0.16%   |
| D-Link System                     | 5         | 0.16%   |
| Qualcomm                          | 4         | 0.13%   |
| Marvell Technology Group          | 3         | 0.1%    |
| IMC Networks                      | 3         | 0.1%    |
| Gemtek                            | 3         | 0.1%    |
| Belkin Components                 | 3         | 0.1%    |
| Wilocity                          | 2         | 0.06%   |
| AVM                               | 2         | 0.06%   |
| Z-Com                             | 1         | 0.03%   |
| Sitecom Europe                    | 1         | 0.03%   |
| Micro Star International          | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| Ericsson Business Mobile Networks | 1         | 0.03%   |
| BUFFALO                           | 1         | 0.03%   |
| 3Com                              | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 305       | 9.87%   |
| Intel Wi-Fi 6 AX201                                                                   | 208       | 6.73%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 149       | 4.82%   |
| Intel Wi-Fi 6 AX200                                                                   | 139       | 4.5%    |
| Intel Wireless 7260                                                                   | 125       | 4.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 119       | 3.85%   |
| Intel Wireless 8265 / 8275                                                            | 102       | 3.3%    |
| Intel Wireless 7265                                                                   | 93        | 3.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 68        | 2.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 66        | 2.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 62        | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 59        | 1.91%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 55        | 1.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 55        | 1.78%   |
| Intel Wireless 8260                                                                   | 54        | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 54        | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 48        | 1.55%   |
| Intel Wireless 3165                                                                   | 47        | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 45        | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 40        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 40        | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 33        | 1.07%   |
| Realtek 802.11ac NIC                                                                  | 33        | 1.07%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 33        | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 29        | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 26        | 0.84%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 26        | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 25        | 0.81%   |
| Intel Wireless-AC 9260                                                                | 23        | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 22        | 0.71%   |
| Intel Wireless 3160                                                                   | 21        | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 19        | 0.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 19        | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 19        | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 18        | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 18        | 0.58%   |
| Intel Centrino Advanced-N 6200                                                        | 18        | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 17        | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 17        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1857      | 46.83%  |
| Intel                            | 1069      | 26.96%  |
| Nvidia                           | 351       | 8.85%   |
| Broadcom                         | 156       | 3.93%   |
| Qualcomm Atheros                 | 146       | 3.68%   |
| Marvell Technology Group         | 116       | 2.93%   |
| Broadcom Limited                 | 33        | 0.83%   |
| ASIX Electronics                 | 29        | 0.73%   |
| Samsung Electronics              | 22        | 0.55%   |
| TP-Link                          | 16        | 0.4%    |
| Microchip Technology             | 16        | 0.4%    |
| DisplayLink                      | 12        | 0.3%    |
| Lenovo                           | 10        | 0.25%   |
| Aquantia                         | 10        | 0.25%   |
| Xiaomi                           | 8         | 0.2%    |
| Qualcomm                         | 8         | 0.2%    |
| Mellanox Technologies            | 8         | 0.2%    |
| JMicron Technology               | 8         | 0.2%    |
| ICS Advent                       | 8         | 0.2%    |
| VIA Technologies                 | 6         | 0.15%   |
| Huawei Technologies              | 6         | 0.15%   |
| Cypress Semiconductor            | 6         | 0.15%   |
| D-Link System                    | 5         | 0.13%   |
| American Megatrends              | 5         | 0.13%   |
| Standard Microsystems            | 4         | 0.1%    |
| Silicon Integrated Systems [SiS] | 4         | 0.1%    |
| Attansic Technology              | 4         | 0.1%    |
| NetXen Incorporated              | 3         | 0.08%   |
| Motorola PCS                     | 3         | 0.08%   |
| Microsoft                        | 3         | 0.08%   |
| Apple                            | 3         | 0.08%   |
| QLogic                           | 2         | 0.05%   |
| OPPO Electronics                 | 2         | 0.05%   |
| National Semiconductor           | 2         | 0.05%   |
| MediaTek                         | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| IBM                              | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| Google                           | 2         | 0.05%   |
| D-Link                           | 2         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1446      | 35.53%  |
| Nvidia MCP79 Ethernet                                             | 311       | 7.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 220       | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 130       | 3.19%   |
| Intel Ethernet Connection (13) I219-V                             | 127       | 3.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 96        | 2.36%   |
| Intel I211 Gigabit Network Connection                             | 62        | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 60        | 1.47%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 56        | 1.38%   |
| Intel I210 Gigabit Network Connection                             | 53        | 1.3%    |
| Intel Ethernet Connection (4) I219-V                              | 42        | 1.03%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 0.96%   |
| Intel Ethernet Connection (2) I219-V                              | 39        | 0.96%   |
| Intel Ethernet Connection (14) I219-V                             | 33        | 0.81%   |
| Intel 82579V Gigabit Network Connection                           | 33        | 0.81%   |
| Intel 82574L Gigabit Network Connection                           | 32        | 0.79%   |
| Intel Ethernet Controller I225-V                                  | 30        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 27        | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 0.64%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.61%   |
| Intel Ethernet Connection (6) I219-V                              | 25        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 25        | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 24        | 0.59%   |
| Nvidia MCP61 Ethernet                                             | 22        | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 22        | 0.54%   |
| Intel Ethernet Connection (10) I219-V                             | 22        | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 21        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 20        | 0.49%   |
| Intel I350 Gigabit Network Connection                             | 20        | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 19        | 0.47%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.47%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 17        | 0.42%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 15        | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 15        | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 15        | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3744      | 55.1%   |
| WiFi     | 2966      | 43.65%  |
| Modem    | 76        | 1.12%   |
| Unknown  | 9         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2201      | 50.18%  |
| WiFi     | 2185      | 49.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2237      | 51.11%  |
| 1     | 1839      | 42.02%  |
| 0     | 136       | 3.11%   |
| 3     | 97        | 2.22%   |
| 4     | 40        | 0.91%   |
| 6     | 12        | 0.27%   |
| 5     | 7         | 0.16%   |
| 8     | 4         | 0.09%   |
| 14    | 1         | 0.02%   |
| 13    | 1         | 0.02%   |
| 12    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3694      | 84.11%  |
| Yes  | 698       | 15.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1110      | 43.86%  |
| Apple                           | 571       | 22.56%  |
| Realtek Semiconductor           | 187       | 7.39%   |
| Qualcomm Atheros Communications | 166       | 6.56%   |
| Cambridge Silicon Radio         | 98        | 3.87%   |
| Broadcom                        | 92        | 3.63%   |
| IMC Networks                    | 76        | 3%      |
| Lite-On Technology              | 70        | 2.77%   |
| Foxconn / Hon Hai               | 35        | 1.38%   |
| ASUSTek Computer                | 25        | 0.99%   |
| Dell                            | 24        | 0.95%   |
| Hewlett-Packard                 | 18        | 0.71%   |
| Realtek                         | 11        | 0.43%   |
| Ralink                          | 10        | 0.4%    |
| Toshiba                         | 9         | 0.36%   |
| MediaTek                        | 8         | 0.32%   |
| Taiyo Yuden                     | 3         | 0.12%   |
| Ralink Technology               | 3         | 0.12%   |
| Foxconn International           | 3         | 0.12%   |
| Belkin Components               | 2         | 0.08%   |
| Alps Electric                   | 2         | 0.08%   |
| USI                             | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Dynex                           | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 423       | 16.71%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 307       | 12.12%  |
| Intel AX201 Bluetooth                               | 298       | 11.77%  |
| Apple Bluetooth USB Host Controller                 | 162       | 6.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 140       | 5.53%   |
| Intel AX200 Bluetooth                               | 136       | 5.37%   |
| Realtek Bluetooth Radio                             | 122       | 4.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 103       | 4.07%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 98        | 3.87%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 3%      |
| Realtek  Bluetooth 4.2 Adapter                      | 46        | 1.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 28        | 1.11%   |
| Intel Wireless-AC 3168 Bluetooth                    | 28        | 1.11%   |
| Intel AX210 Bluetooth                               | 25        | 0.99%   |
| IMC Networks Bluetooth Radio                        | 25        | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 22        | 0.87%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 0.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 21        | 0.83%   |
| IMC Networks Bluetooth Device                       | 21        | 0.83%   |
| Apple Bluetooth Host Controller                     | 20        | 0.79%   |
| Lite-On Bluetooth Device                            | 18        | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 0.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 15        | 0.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 0.59%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 13        | 0.51%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 12        | 0.47%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.43%   |
| Realtek Bluetooth Radio                             | 11        | 0.43%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.39%   |
| IMC Networks Wireless_Device                        | 9         | 0.36%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.36%   |
| Dell BCM20702A0 Bluetooth Module                    | 9         | 0.36%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.32%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 8         | 0.32%   |
| MediaTek Wireless_Device                            | 7         | 0.28%   |
| Lite-On Wireless_Device                             | 7         | 0.28%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 7         | 0.28%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2992      | 57.09%  |
| Nvidia                                       | 1000      | 19.08%  |
| AMD                                          | 855       | 16.31%  |
| C-Media Electronics                          | 61        | 1.16%   |
| Logitech                                     | 34        | 0.65%   |
| Texas Instruments                            | 22        | 0.42%   |
| Generalplus Technology                       | 21        | 0.4%    |
| Creative Labs                                | 19        | 0.36%   |
| Plantronics                                  | 15        | 0.29%   |
| Creative Technology                          | 15        | 0.29%   |
| Lenovo                                       | 13        | 0.25%   |
| Realtek Semiconductor                        | 11        | 0.21%   |
| GN Netcom                                    | 11        | 0.21%   |
| JMTek                                        | 10        | 0.19%   |
| ASUSTek Computer                             | 9         | 0.17%   |
| VIA Technologies                             | 8         | 0.15%   |
| Focusrite-Novation                           | 8         | 0.15%   |
| Kingston Technology                          | 7         | 0.13%   |
| GYROCOM C&C                                  | 7         | 0.13%   |
| RODE Microphones                             | 6         | 0.11%   |
| Hewlett-Packard                              | 6         | 0.11%   |
| SteelSeries ApS                              | 5         | 0.1%    |
| Sennheiser Communications                    | 5         | 0.1%    |
| Razer USA                                    | 5         | 0.1%    |
| Microsoft                                    | 5         | 0.1%    |
| Cambridge Silicon Radio                      | 5         | 0.1%    |
| Yamaha                                       | 4         | 0.08%   |
| Unknown                                      | 4         | 0.08%   |
| Micro Star International                     | 4         | 0.08%   |
| BEHRINGER International                      | 4         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.06%   |
| Samson Technologies                          | 3         | 0.06%   |
| M-Audio                                      | 3         | 0.06%   |
| Blue Microphones                             | 3         | 0.06%   |
| Apple                                        | 3         | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.04%   |
| XMOS                                         | 2         | 0.04%   |
| ULi Electronics                              | 2         | 0.04%   |
| Tenx Technology                              | 2         | 0.04%   |
| ROCCAT                                       | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 High Definition Audio                                                                | 312       | 5.02%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 292       | 4.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 251       | 4.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 249       | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 223       | 3.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 216       | 3.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 213       | 3.42%   |
| Intel Broadwell-U Audio Controller                                                                | 205       | 3.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 204       | 3.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 201       | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 174       | 2.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 134       | 2.15%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 132       | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 122       | 1.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 120       | 1.93%   |
| Intel 200 Series PCH HD Audio                                                                     | 116       | 1.86%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 114       | 1.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 112       | 1.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 90        | 1.45%   |
| Intel Comet Lake PCH cAVS                                                                         | 89        | 1.43%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 87        | 1.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 83        | 1.33%   |
| AMD FCH Azalia Controller                                                                         | 75        | 1.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 73        | 1.17%   |
| AMD Kabini HDMI/DP Audio                                                                          | 70        | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 69        | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 68        | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 66        | 1.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 63        | 1.01%   |
| Intel 8 Series HD Audio Controller                                                                | 63        | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 62        | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 59        | 0.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 56        | 0.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 54        | 0.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 50        | 0.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 50        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 50        | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 46        | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 43        | 0.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 39        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 941       | 22.29%  |
| Samsung Electronics | 930       | 22.03%  |
| Kingston            | 433       | 10.26%  |
| Crucial             | 399       | 9.45%   |
| Unknown             | 374       | 8.86%   |
| Micron Technology   | 302       | 7.15%   |
| Corsair             | 137       | 3.25%   |
| Elpida              | 92        | 2.18%   |
| G.Skill             | 87        | 2.06%   |
| Patriot             | 61        | 1.45%   |
| A-DATA Technology   | 59        | 1.4%    |
| Ramaxel Technology  | 56        | 1.33%   |
| Unknown             | 45        | 1.07%   |
| Nanya Technology    | 39        | 0.92%   |
| Unknown (ABCD)      | 27        | 0.64%   |
| Team                | 25        | 0.59%   |
| Goodram             | 23        | 0.54%   |
| Hikvision           | 20        | 0.47%   |
| Smart               | 16        | 0.38%   |
| Transcend           | 14        | 0.33%   |
| AMD                 | 14        | 0.33%   |
| Apacer              | 7         | 0.17%   |
| Hewlett-Packard     | 6         | 0.14%   |
| Qimonda             | 5         | 0.12%   |
| GeIL                | 5         | 0.12%   |
| Wilk                | 4         | 0.09%   |
| Silicon Power       | 4         | 0.09%   |
| Infineon            | 4         | 0.09%   |
| Goldkey             | 4         | 0.09%   |
| ASint Technology    | 4         | 0.09%   |
| 48spaces            | 4         | 0.09%   |
| Unifosa             | 3         | 0.07%   |
| Toshiba             | 3         | 0.07%   |
| Timetec             | 3         | 0.07%   |
| Teikon              | 3         | 0.07%   |
| PNY                 | 3         | 0.07%   |
| Neo Forza           | 3         | 0.07%   |
| Kllisre             | 3         | 0.07%   |
| Avant               | 3         | 0.07%   |
| V-Color             | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                     | 256       | 5.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 135       | 3%      |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                     | 68        | 1.51%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                     | 61        | 1.36%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s        | 61        | 1.36%   |
| Unknown                                                         | 45        | 1%      |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s         | 43        | 0.96%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                      | 36        | 0.8%    |
| Unknown RAM Module 2GB DIMM SDRAM                               | 34        | 0.76%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s           | 31        | 0.69%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s           | 30        | 0.67%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                      | 29        | 0.64%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                    | 27        | 0.6%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s           | 27        | 0.6%    |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s          | 26        | 0.58%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s          | 25        | 0.56%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                     | 24        | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s           | 24        | 0.53%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s            | 24        | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 23        | 0.51%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                     | 20        | 0.44%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s         | 20        | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 19        | 0.42%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 19        | 0.42%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s           | 18        | 0.4%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s       | 18        | 0.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 17        | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 17        | 0.38%   |
| Unknown RAM Module 1GB DIMM SDRAM                               | 16        | 0.36%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 16        | 0.36%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                 | 16        | 0.36%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s            | 16        | 0.36%   |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 15        | 0.33%   |
| Unknown RAM Module 1GB SODIMM SDRAM                             | 15        | 0.33%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s          | 15        | 0.33%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                      | 15        | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s | 14        | 0.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 14        | 0.31%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s       | 14        | 0.31%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 14        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 1545      | 41%     |
| DDR3         | 1248      | 33.12%  |
| DDR2         | 522       | 13.85%  |
| SDRAM        | 129       | 3.42%   |
| Unknown      | 106       | 2.81%   |
| LPDDR4       | 84        | 2.23%   |
| LPDDR3       | 81        | 2.15%   |
| DDR          | 42        | 1.11%   |
| DRAM         | 7         | 0.19%   |
| DDR5         | 3         | 0.08%   |
| DDR2 FB-DIMM | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2183      | 58.06%  |
| DIMM         | 1382      | 36.76%  |
| Row Of Chips | 129       | 3.43%   |
| Unknown      | 34        | 0.9%    |
| Chip         | 25        | 0.66%   |
| FB-DIMM      | 5         | 0.13%   |
| RIMM         | 2         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1230      | 30.45%  |
| 4096  | 985       | 24.39%  |
| 2048  | 667       | 16.51%  |
| 1024  | 528       | 13.07%  |
| 16384 | 431       | 10.67%  |
| 32768 | 131       | 3.24%   |
| 512   | 46        | 1.14%   |
| 256   | 15        | 0.37%   |
| 65536 | 4         | 0.1%    |
| 1536  | 1         | 0.02%   |
| 128   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 851       | 21.29%  |
| 3200    | 559       | 13.99%  |
| 2667    | 488       | 12.21%  |
| 800     | 392       | 9.81%   |
| 1333    | 275       | 6.88%   |
| 2400    | 240       | 6%      |
| 2133    | 162       | 4.05%   |
| 667     | 161       | 4.03%   |
| Unknown | 113       | 2.83%   |
| 1334    | 84        | 2.1%    |
| 3600    | 59        | 1.48%   |
| 1866    | 57        | 1.43%   |
| 2666    | 55        | 1.38%   |
| 1867    | 55        | 1.38%   |
| 1067    | 50        | 1.25%   |
| 4267    | 34        | 0.85%   |
| 1066    | 33        | 0.83%   |
| 3266    | 25        | 0.63%   |
| 2866    | 25        | 0.63%   |
| 3466    | 24        | 0.6%    |
| 3000    | 22        | 0.55%   |
| 3400    | 20        | 0.5%    |
| 2933    | 17        | 0.43%   |
| 533     | 17        | 0.43%   |
| 4199    | 15        | 0.38%   |
| 400     | 14        | 0.35%   |
| 1800    | 13        | 0.33%   |
| 2048    | 12        | 0.3%    |
| 333     | 12        | 0.3%    |
| 3733    | 11        | 0.28%   |
| 266     | 10        | 0.25%   |
| 4333    | 7         | 0.18%   |
| 975     | 7         | 0.18%   |
| 8400    | 6         | 0.15%   |
| 4266    | 6         | 0.15%   |
| 3066    | 6         | 0.15%   |
| 4800    | 5         | 0.13%   |
| 3800    | 5         | 0.13%   |
| 3100    | 5         | 0.13%   |
| 3500    | 4         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 33        | 37.08%  |
| Brother Industries  | 16        | 17.98%  |
| Xerox               | 8         | 8.99%   |
| Canon               | 8         | 8.99%   |
| Samsung Electronics | 7         | 7.87%   |
| Dymo-CoStar         | 4         | 4.49%   |
| Seiko Epson         | 3         | 3.37%   |
| Prolific Technology | 3         | 3.37%   |
| Zebra               | 2         | 2.25%   |
| STMicroelectronics  | 1         | 1.12%   |
| Pantum              | 1         | 1.12%   |
| Kyocera             | 1         | 1.12%   |
| Konica Minolta      | 1         | 1.12%   |
| GODEX INTERNATIONAL | 1         | 1.12%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xerox B205                                                            | 7         | 7.87%   |
| Prolific PL2305 Parallel Port                                         | 3         | 3.37%   |
| HP LaserJet M101-M106                                                 | 3         | 3.37%   |
| HP LaserJet 1200                                                      | 3         | 3.37%   |
| HP LaserJet 1020                                                      | 3         | 3.37%   |
| Samsung ML-1660 Series                                                | 2         | 2.25%   |
| HP LaserJet P1005                                                     | 2         | 2.25%   |
| HP ENVY 4520 series                                                   | 2         | 2.25%   |
| HP DeskJet 2620 All-in-One Printer                                    | 2         | 2.25%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 2.25%   |
| Canon LiDE 400                                                        | 2         | 2.25%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 1.12%   |
| Zebra ZTC ZD420-203dpi ZPL                                            | 1         | 1.12%   |
| Xerox Phaser 3250                                                     | 1         | 1.12%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 1.12%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 1.12%   |
| Seiko Epson L4150 Series                                              | 1         | 1.12%   |
| Seiko Epson ET-2850 Series                                            | 1         | 1.12%   |
| Samsung SCX-4650 4x21S Series                                         | 1         | 1.12%   |
| Samsung SCX-3200 Series                                               | 1         | 1.12%   |
| Samsung ML-216x Series Laser Printer                                  | 1         | 1.12%   |
| Samsung ML-2010P Mono Laser Printer                                   | 1         | 1.12%   |
| Samsung ML-1520 Laser Printer                                         | 1         | 1.12%   |
| Pantum P2500W series                                                  | 1         | 1.12%   |
| Kyocera ECOSYS M5521cdn                                               | 1         | 1.12%   |
| Konica Minolta bizhub 4402P                                           | 1         | 1.12%   |
| HP Officejet J4500 series                                             | 1         | 1.12%   |
| HP Officejet 7110 series                                              | 1         | 1.12%   |
| HP LaserJet Pro M404-M405                                             | 1         | 1.12%   |
| HP LaserJet P2055 series                                              | 1         | 1.12%   |
| HP LaserJet P1006                                                     | 1         | 1.12%   |
| HP LaserJet M14-M17                                                   | 1         | 1.12%   |
| HP LaserJet 400 M401dne                                               | 1         | 1.12%   |
| HP LaserJet 1300                                                      | 1         | 1.12%   |
| HP LaserJet 1160 series                                               | 1         | 1.12%   |
| HP LaserJet 1150                                                      | 1         | 1.12%   |
| HP LaserJet 1022                                                      | 1         | 1.12%   |
| HP LaserJet 1015                                                      | 1         | 1.12%   |
| HP Ink Tank 110 series                                                | 1         | 1.12%   |
| HP ENVY Photo 6200 series                                             | 1         | 1.12%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 14        | 56%     |
| Seiko Epson     | 6         | 24%     |
| Hewlett-Packard | 3         | 12%     |
| AGFA-Gevaert NV | 2         | 8%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                            | 3         | 12%     |
| Canon CanoScan LiDE 220                                       | 3         | 12%     |
| Canon CanoScan LiDE 120                                       | 2         | 8%      |
| Canon CanoScan LiDE 110                                       | 2         | 8%      |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2         | 8%      |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 4%      |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1         | 4%      |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 4%      |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 4%      |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                 | 1         | 4%      |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 4%      |
| HP ScanJet Pro 2500 f1                                        | 1         | 4%      |
| HP ScanJet 3970c                                              | 1         | 4%      |
| HP Scanjet 300                                                | 1         | 4%      |
| Canon CanoScan LIDE 25                                        | 1         | 4%      |
| Canon CanoScan LiDE 210                                       | 1         | 4%      |
| Canon CanoScan 8800F                                          | 1         | 4%      |
| Canon CanoScan 5600F                                          | 1         | 4%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 480       | 22.93%  |
| Acer                                   | 290       | 13.86%  |
| IMC Networks                           | 195       | 9.32%   |
| Quanta                                 | 173       | 8.27%   |
| Microdia                               | 146       | 6.98%   |
| Realtek Semiconductor                  | 125       | 5.97%   |
| Logitech                               | 116       | 5.54%   |
| Sunplus Innovation Technology          | 75        | 3.58%   |
| Cheng Uei Precision Industry (Foxlink) | 62        | 2.96%   |
| Apple                                  | 55        | 2.63%   |
| Suyin                                  | 49        | 2.34%   |
| Syntek                                 | 41        | 1.96%   |
| Lite-On Technology                     | 41        | 1.96%   |
| Luxvisions Innotech Limited            | 37        | 1.77%   |
| Silicon Motion                         | 18        | 0.86%   |
| Alcor Micro                            | 15        | 0.72%   |
| Lenovo                                 | 13        | 0.62%   |
| Generalplus Technology                 | 12        | 0.57%   |
| Z-Star Microelectronics                | 11        | 0.53%   |
| Microsoft                              | 11        | 0.53%   |
| Ricoh                                  | 10        | 0.48%   |
| Samsung Electronics                    | 8         | 0.38%   |
| Sonix Technology                       | 7         | 0.33%   |
| Creative Technology                    | 7         | 0.33%   |
| KYE Systems (Mouse Systems)            | 6         | 0.29%   |
| Genesys Logic                          | 6         | 0.29%   |
| Primax Electronics                     | 5         | 0.24%   |
| Jieli Technology                       | 5         | 0.24%   |
| ARC International                      | 5         | 0.24%   |
| Unknown                                | 4         | 0.19%   |
| ALi                                    | 4         | 0.19%   |
| SunplusIT                              | 3         | 0.14%   |
| Mimaki Engineering                     | 3         | 0.14%   |
| Intel                                  | 3         | 0.14%   |
| Importek                               | 3         | 0.14%   |
| Xiongmai                               | 2         | 0.1%    |
| Sunplus Technology                     | 2         | 0.1%    |
| Razer USA                              | 2         | 0.1%    |
| OmniVision Technologies                | 2         | 0.1%    |
| Novatek Microelectronics               | 2         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 165       | 7.72%   |
| Acer Integrated Camera                              | 121       | 5.66%   |
| Microdia Integrated_Webcam_HD                       | 71        | 3.32%   |
| Acer Integrated 5M Camera                           | 70        | 3.28%   |
| Quanta Chromebook HD Camera                         | 67        | 3.14%   |
| IMC Networks Integrated Camera                      | 63        | 2.95%   |
| Acer BisonCam, NB Pro                               | 49        | 2.29%   |
| Chicony Integrated 5M Camera                        | 43        | 2.01%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 42        | 1.97%   |
| Realtek Integrated_Webcam_HD                        | 38        | 1.78%   |
| Logitech Webcam C270                                | 37        | 1.73%   |
| Chicony HD Webcam                                   | 37        | 1.73%   |
| Chicony USB2.0 HD UVC WebCam                        | 24        | 1.12%   |
| Syntek Integrated Camera                            | 22        | 1.03%   |
| Quanta HP TrueVision HD Camera                      | 22        | 1.03%   |
| Sunplus Integrated_Webcam_HD                        | 21        | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 21        | 0.98%   |
| Apple Built-in iSight                               | 20        | 0.94%   |
| Quanta VGA WebCam                                   | 19        | 0.89%   |
| Chicony HP HD Camera                                | 19        | 0.89%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 18        | 0.84%   |
| Apple iPhone5/5C/5S/6                               | 17        | 0.8%    |
| Realtek USB Camera                                  | 16        | 0.75%   |
| Quanta HD User Facing                               | 16        | 0.75%   |
| Lite-On Integrated Camera                           | 16        | 0.75%   |
| Acer SunplusIT Integrated Camera                    | 16        | 0.75%   |
| Chicony Chromebook HD Camera                        | 15        | 0.7%    |
| Logitech HD Pro Webcam C920                         | 13        | 0.61%   |
| Chicony HP Webcam                                   | 13        | 0.61%   |
| Chicony Integrated Camera (1280x720@30)             | 12        | 0.56%   |
| Acer Lenovo Integrated Webcam                       | 12        | 0.56%   |
| Luxvisions Innotech Limited HP HD Camera            | 11        | 0.51%   |
| Logitech C922 Pro Stream Webcam                     | 11        | 0.51%   |
| Lite-On HP HD Camera                                | 11        | 0.51%   |
| IMC Networks USB 2.0 Camera                         | 11        | 0.51%   |
| IMC Networks HD Camera                              | 11        | 0.51%   |
| Chicony HD User Facing                              | 11        | 0.51%   |
| Suyin HP Truevision HD                              | 10        | 0.47%   |
| Quanta HP HD Camera                                 | 10        | 0.47%   |
| Microdia Integrated Webcam                          | 10        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 229       | 47.91%  |
| Validity Sensors           | 124       | 25.94%  |
| Shenzhen Goodix Technology | 51        | 10.67%  |
| Elan Microelectronics      | 19        | 3.97%   |
| AuthenTec                  | 18        | 3.77%   |
| Upek                       | 17        | 3.56%   |
| LighTuning Technology      | 12        | 2.51%   |
| STMicroelectronics         | 7         | 1.46%   |
| Samsung Electronics        | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 158       | 33.05%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 35        | 7.32%   |
| Shenzhen Goodix  FingerPrint Device                                        | 28        | 5.86%   |
| Unknown                                                                    | 26        | 5.44%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 25        | 5.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 3.97%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 3.97%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 3.35%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 2.51%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 2.51%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.51%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 2.3%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 2.09%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 10        | 2.09%   |
| Elan ELAN:ARM-M4                                                           | 7         | 1.46%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.26%   |
| Synaptics  WBDI                                                            | 6         | 1.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.26%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.05%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.05%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 0.84%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.84%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 0.84%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.63%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.42%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.42%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.42%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.42%   |
| AuthenTec AES2810                                                          | 2         | 0.42%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.42%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.42%   |
| Validity Sensors VFS491                                                    | 1         | 0.21%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.21%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.21%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.21%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.21%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.21%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 60        | 33.9%   |
| Broadcom                  | 58        | 32.77%  |
| Upek                      | 17        | 9.6%    |
| O2 Micro                  | 13        | 7.34%   |
| Lenovo                    | 11        | 6.21%   |
| Gemalto (was Gemplus)     | 4         | 2.26%   |
| Yubico.com                | 3         | 1.69%   |
| SCM Microsystems          | 2         | 1.13%   |
| Clay Logic                | 2         | 1.13%   |
| Cherry                    | 2         | 1.13%   |
| Aladdin Knowledge Systems | 2         | 1.13%   |
| OmniKey                   | 1         | 0.56%   |
| Chicony Electronics       | 1         | 0.56%   |
| C3PO                      | 1         | 0.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 58        | 32.77%  |
| Broadcom 58200                                                               | 20        | 11.3%   |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 10.17%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 9.6%    |
| Broadcom 5880                                                                | 12        | 6.78%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 6.21%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 6.21%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 3.95%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.13%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.13%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.13%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 1.13%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.13%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.13%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.56%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.56%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.56%   |
| OmniKey CardMan 4321                                                         | 1         | 0.56%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.56%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.56%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.56%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.56%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.56%   |
| C3PO LTC31v2                                                                 | 1         | 0.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2481      | 56.23%  |
| 1     | 1619      | 36.7%   |
| 2     | 253       | 5.73%   |
| 3     | 48        | 1.09%   |
| 4     | 6         | 0.14%   |
| 5     | 3         | 0.07%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1004      | 45.59%  |
| Fingerprint reader       | 476       | 21.62%  |
| Multimedia controller    | 204       | 9.26%   |
| Chipcard                 | 154       | 6.99%   |
| Net/wireless             | 143       | 6.49%   |
| Communication controller | 58        | 2.63%   |
| Unassigned class         | 38        | 1.73%   |
| Bluetooth                | 32        | 1.45%   |
| Card reader              | 21        | 0.95%   |
| Storage                  | 17        | 0.77%   |
| Sound                    | 15        | 0.68%   |
| Camera                   | 11        | 0.5%    |
| Network                  | 7         | 0.32%   |
| Net/ethernet             | 6         | 0.27%   |
| Modem                    | 4         | 0.18%   |
| Tv card                  | 3         | 0.14%   |
| Storage/raid             | 3         | 0.14%   |
| Flash memory             | 2         | 0.09%   |
| Dvb card                 | 2         | 0.09%   |
| Storage/ide              | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |

