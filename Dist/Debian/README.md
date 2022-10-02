Debian - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Debian.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian/Desktop/README.md) and [notebooks](/Dist/Debian/Notebook/README.md).

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

Total: 10342

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A715-41G             | Notebook    | [1a473e9809](https://linux-hardware.org/?probe=1a473e9809) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| MSI           | 2A9C                        | Desktop     | [a933ad6bca](https://linux-hardware.org/?probe=a933ad6bca) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [9b59ddb3b2](https://linux-hardware.org/?probe=9b59ddb3b2) | Oct 01, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [d3d117cf14](https://linux-hardware.org/?probe=d3d117cf14) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [53e99a8ce6](https://linux-hardware.org/?probe=53e99a8ce6) | Oct 01, 2022 |
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
| HUAWEI        | KLVL-WXXW                   | Notebook    | [fd8b95bb3b](https://linux-hardware.org/?probe=fd8b95bb3b) | Sep 29, 2022 |
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
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [fb2de59c3f](https://linux-hardware.org/?probe=fb2de59c3f) | Sep 27, 2022 |
| Medion        | MS-7728                     | Desktop     | [0b9b2ca570](https://linux-hardware.org/?probe=0b9b2ca570) | Sep 27, 2022 |
| HP            | 339A                        | Desktop     | [25ef7556cc](https://linux-hardware.org/?probe=25ef7556cc) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [757d465447](https://linux-hardware.org/?probe=757d465447) | Sep 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [e3826dca71](https://linux-hardware.org/?probe=e3826dca71) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [f4e2b14498](https://linux-hardware.org/?probe=f4e2b14498) | Sep 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fdf2d015bc](https://linux-hardware.org/?probe=fdf2d015bc) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [4f58ff1174](https://linux-hardware.org/?probe=4f58ff1174) | Sep 26, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [76a7224818](https://linux-hardware.org/?probe=76a7224818) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| HP            | 339A                        | Desktop     | [07986ca95e](https://linux-hardware.org/?probe=07986ca95e) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [f750ea8b83](https://linux-hardware.org/?probe=f750ea8b83) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [2cc7eefe57](https://linux-hardware.org/?probe=2cc7eefe57) | Sep 26, 2022 |
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
| Lenovo        | ThinkPad T420 4236WS7       | Notebook    | [23f425e425](https://linux-hardware.org/?probe=23f425e425) | Sep 24, 2022 |
| Dell          | Inspiron 14 5425            | Notebook    | [209be443ac](https://linux-hardware.org/?probe=209be443ac) | Sep 24, 2022 |
| Google        | Teemo                       | Desktop     | [5ddc8b97b8](https://linux-hardware.org/?probe=5ddc8b97b8) | Sep 24, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [1d76ae9f44](https://linux-hardware.org/?probe=1d76ae9f44) | Sep 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | Notebook    | [f3527878e5](https://linux-hardware.org/?probe=f3527878e5) | Sep 24, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [89a019875a](https://linux-hardware.org/?probe=89a019875a) | Sep 24, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [8a734f0799](https://linux-hardware.org/?probe=8a734f0799) | Sep 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [6cdacdb935](https://linux-hardware.org/?probe=6cdacdb935) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | Notebook    | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| Dell          | Latitude 3320               | Notebook    | [3296a12784](https://linux-hardware.org/?probe=3296a12784) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [0299e4f7b1](https://linux-hardware.org/?probe=0299e4f7b1) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [cad0f6f375](https://linux-hardware.org/?probe=cad0f6f375) | Sep 24, 2022 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [405ea9a4ca](https://linux-hardware.org/?probe=405ea9a4ca) | Sep 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4658ef6703](https://linux-hardware.org/?probe=4658ef6703) | Sep 24, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | Notebook    | [0adb7bc0b1](https://linux-hardware.org/?probe=0adb7bc0b1) | Sep 24, 2022 |
| VIT           | P2402                       | Notebook    | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| MSI           | C236A WORKSTATION           | Desktop     | [67432a461e](https://linux-hardware.org/?probe=67432a461e) | Sep 24, 2022 |
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
| Dell          | XPS 15 9520                 | Notebook    | [1a7e610c32](https://linux-hardware.org/?probe=1a7e610c32) | Sep 23, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [985fa1c4c7](https://linux-hardware.org/?probe=985fa1c4c7) | Sep 23, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [39a94459dc](https://linux-hardware.org/?probe=39a94459dc) | Sep 23, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [c9f00bec8e](https://linux-hardware.org/?probe=c9f00bec8e) | Sep 23, 2022 |
| HP            | 876C SMVB                   | Desktop     | [c6fbf7c631](https://linux-hardware.org/?probe=c6fbf7c631) | Sep 23, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [f77dda559d](https://linux-hardware.org/?probe=f77dda559d) | Sep 23, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [c05619dc16](https://linux-hardware.org/?probe=c05619dc16) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | Notebook    | [c9457ee571](https://linux-hardware.org/?probe=c9457ee571) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | Notebook    | [412296c83f](https://linux-hardware.org/?probe=412296c83f) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [5488a2b9ff](https://linux-hardware.org/?probe=5488a2b9ff) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [3d7933270a](https://linux-hardware.org/?probe=3d7933270a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [1e6b1b068a](https://linux-hardware.org/?probe=1e6b1b068a) | Sep 22, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [db6f733994](https://linux-hardware.org/?probe=db6f733994) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | Notebook    | [21ba0d8f46](https://linux-hardware.org/?probe=21ba0d8f46) | Sep 22, 2022 |
| Pegatron      | 2ACD                        | Desktop     | [31c266d23c](https://linux-hardware.org/?probe=31c266d23c) | Sep 22, 2022 |
| Lenovo        | ThinkPad X220 4291G26       | Notebook    | [33654dfbfa](https://linux-hardware.org/?probe=33654dfbfa) | Sep 22, 2022 |
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
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [69d5dcb9b7](https://linux-hardware.org/?probe=69d5dcb9b7) | Sep 21, 2022 |
| Thecus        | N2810 0001                  | Desktop     | [f54df3994c](https://linux-hardware.org/?probe=f54df3994c) | Sep 21, 2022 |
| Avell High... | B.ON                        | Notebook    | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| ECS           | G31T-M9                     | Desktop     | [6e67780df1](https://linux-hardware.org/?probe=6e67780df1) | Sep 21, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a9e18191f7](https://linux-hardware.org/?probe=a9e18191f7) | Sep 21, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [e267d78b42](https://linux-hardware.org/?probe=e267d78b42) | Sep 21, 2022 |
| Dell          | Latitude 7530               | Notebook    | [39b655888c](https://linux-hardware.org/?probe=39b655888c) | Sep 21, 2022 |
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
| HP            | Folio 13                    | Notebook    | [eafa8204e9](https://linux-hardware.org/?probe=eafa8204e9) | Sep 20, 2022 |
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
| Gigabyte      | B550 VISION D-P             | Desktop     | [b1f764b4ca](https://linux-hardware.org/?probe=b1f764b4ca) | Sep 19, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [ee235bf98c](https://linux-hardware.org/?probe=ee235bf98c) | Sep 19, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e98a0964e8](https://linux-hardware.org/?probe=e98a0964e8) | Sep 19, 2022 |
| Lenovo        | ThinkPad SL400 2743AQC      | Notebook    | [beb74c65cc](https://linux-hardware.org/?probe=beb74c65cc) | Sep 19, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [89adb3b190](https://linux-hardware.org/?probe=89adb3b190) | Sep 19, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [ae4e13ddc1](https://linux-hardware.org/?probe=ae4e13ddc1) | Sep 19, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [4b412dd569](https://linux-hardware.org/?probe=4b412dd569) | Sep 19, 2022 |
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
| MSI           | J1800I                      | Desktop     | [ff28c29a3e](https://linux-hardware.org/?probe=ff28c29a3e) | Sep 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [87c3b99589](https://linux-hardware.org/?probe=87c3b99589) | Sep 18, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [c1045050d6](https://linux-hardware.org/?probe=c1045050d6) | Sep 17, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [3de0a6e725](https://linux-hardware.org/?probe=3de0a6e725) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [f474823b5a](https://linux-hardware.org/?probe=f474823b5a) | Sep 17, 2022 |
| Dell          | Latitude E7440              | Notebook    | [5194c92c15](https://linux-hardware.org/?probe=5194c92c15) | Sep 17, 2022 |
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
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [968c24205d](https://linux-hardware.org/?probe=968c24205d) | Sep 17, 2022 |
| Dell          | 0UW816 A00                  | Server      | [bd29b42f73](https://linux-hardware.org/?probe=bd29b42f73) | Sep 17, 2022 |
| Dell          | 0UW816 A00                  | Server      | [9959a5f63d](https://linux-hardware.org/?probe=9959a5f63d) | Sep 17, 2022 |
| HP            | Unknown                     | Notebook    | [e87c925eb0](https://linux-hardware.org/?probe=e87c925eb0) | Sep 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [189e23ff6a](https://linux-hardware.org/?probe=189e23ff6a) | Sep 16, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [3ace24ebfc](https://linux-hardware.org/?probe=3ace24ebfc) | Sep 16, 2022 |
| Dell          | Latitude E5540              | Notebook    | [8e44a11e6c](https://linux-hardware.org/?probe=8e44a11e6c) | Sep 16, 2022 |
| Dell          | Latitude E5540              | Notebook    | [c2d57deba4](https://linux-hardware.org/?probe=c2d57deba4) | Sep 16, 2022 |
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
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4c33a54701](https://linux-hardware.org/?probe=4c33a54701) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [a1f16914f7](https://linux-hardware.org/?probe=a1f16914f7) | Sep 16, 2022 |
| Aquarius      | NS585                       | Notebook    | [249e3f9a7c](https://linux-hardware.org/?probe=249e3f9a7c) | Sep 16, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c63f6d45b4](https://linux-hardware.org/?probe=c63f6d45b4) | Sep 16, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [4dce87f7fa](https://linux-hardware.org/?probe=4dce87f7fa) | Sep 16, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [283a38bb80](https://linux-hardware.org/?probe=283a38bb80) | Sep 16, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [00ca986a4c](https://linux-hardware.org/?probe=00ca986a4c) | Sep 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [c292f41bc5](https://linux-hardware.org/?probe=c292f41bc5) | Sep 15, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [14cbf91f0c](https://linux-hardware.org/?probe=14cbf91f0c) | Sep 15, 2022 |
| Google        | Stout                       | Notebook    | [82b966b9ad](https://linux-hardware.org/?probe=82b966b9ad) | Sep 15, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3cb0c31aff](https://linux-hardware.org/?probe=3cb0c31aff) | Sep 15, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b99fc6c4d7](https://linux-hardware.org/?probe=b99fc6c4d7) | Sep 15, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d2a3eb186f](https://linux-hardware.org/?probe=d2a3eb186f) | Sep 15, 2022 |
| Dell          | Precision 3571              | Notebook    | [01f5d7f7f8](https://linux-hardware.org/?probe=01f5d7f7f8) | Sep 15, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [23194305f6](https://linux-hardware.org/?probe=23194305f6) | Sep 15, 2022 |
| Aquarius      | NS585                       | Notebook    | [e86929e9a3](https://linux-hardware.org/?probe=e86929e9a3) | Sep 15, 2022 |
| Aquarius      | NS585                       | Notebook    | [a1568949cd](https://linux-hardware.org/?probe=a1568949cd) | Sep 15, 2022 |
| Aquarius      | NS585                       | Notebook    | [feedc8a0ba](https://linux-hardware.org/?probe=feedc8a0ba) | Sep 15, 2022 |
| Aquarius      | NS585                       | Notebook    | [eb2906fdc5](https://linux-hardware.org/?probe=eb2906fdc5) | Sep 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [9f2a08c261](https://linux-hardware.org/?probe=9f2a08c261) | Sep 15, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [007e9d4205](https://linux-hardware.org/?probe=007e9d4205) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [3bf32bc004](https://linux-hardware.org/?probe=3bf32bc004) | Sep 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [15d3d95ab2](https://linux-hardware.org/?probe=15d3d95ab2) | Sep 15, 2022 |
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
| Valve         | Jupiter                     | Notebook    | [28bed644da](https://linux-hardware.org/?probe=28bed644da) | Sep 14, 2022 |
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
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [5784c0a7e3](https://linux-hardware.org/?probe=5784c0a7e3) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | Notebook    | [b8665b7aed](https://linux-hardware.org/?probe=b8665b7aed) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [e65b9d439e](https://linux-hardware.org/?probe=e65b9d439e) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | Notebook    | [22c2adf69b](https://linux-hardware.org/?probe=22c2adf69b) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | Notebook    | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [8ec7217b7d](https://linux-hardware.org/?probe=8ec7217b7d) | Sep 14, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [c8994c7912](https://linux-hardware.org/?probe=c8994c7912) | Sep 14, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [c3b834caec](https://linux-hardware.org/?probe=c3b834caec) | Sep 14, 2022 |
| IPASON        | MaxBook P1X                 | Notebook    | [18d0740712](https://linux-hardware.org/?probe=18d0740712) | Sep 13, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Google        | Terra                       | Notebook    | [a7150f06c7](https://linux-hardware.org/?probe=a7150f06c7) | Sep 13, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [5a69611620](https://linux-hardware.org/?probe=5a69611620) | Sep 13, 2022 |
| Lenovo        | SHARKBAY 0C48431 WIN        | Desktop     | [4598920e84](https://linux-hardware.org/?probe=4598920e84) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| HP            | 876C SMVB                   | Desktop     | [61df16cfc9](https://linux-hardware.org/?probe=61df16cfc9) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [4c5dc2ec7d](https://linux-hardware.org/?probe=4c5dc2ec7d) | Sep 13, 2022 |
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
| ASUSTek       | P5Q SE2                     | Desktop     | [1552e587a8](https://linux-hardware.org/?probe=1552e587a8) | Sep 13, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [7acd0e62aa](https://linux-hardware.org/?probe=7acd0e62aa) | Sep 12, 2022 |
| Google        | Terra                       | Notebook    | [6b591d8c39](https://linux-hardware.org/?probe=6b591d8c39) | Sep 12, 2022 |
| Google        | Terra                       | Notebook    | [b3993f460f](https://linux-hardware.org/?probe=b3993f460f) | Sep 12, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [1d95c5b6ef](https://linux-hardware.org/?probe=1d95c5b6ef) | Sep 12, 2022 |
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
| Unknown       | Unknown                     | Notebook    | [b686d4f2b7](https://linux-hardware.org/?probe=b686d4f2b7) | Sep 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [5b6bbb71d1](https://linux-hardware.org/?probe=5b6bbb71d1) | Sep 12, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| MSI           | GS60 2PE                    | Notebook    | [0164cbee91](https://linux-hardware.org/?probe=0164cbee91) | Sep 12, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [e8da6da2b0](https://linux-hardware.org/?probe=e8da6da2b0) | Sep 12, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [613f741235](https://linux-hardware.org/?probe=613f741235) | Sep 12, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [09d0fcce0e](https://linux-hardware.org/?probe=09d0fcce0e) | Sep 12, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [3a6e62d846](https://linux-hardware.org/?probe=3a6e62d846) | Sep 12, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [c18f89b2bb](https://linux-hardware.org/?probe=c18f89b2bb) | Sep 11, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [e007728e0a](https://linux-hardware.org/?probe=e007728e0a) | Sep 11, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [06c0b65315](https://linux-hardware.org/?probe=06c0b65315) | Sep 11, 2022 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [5987ef39e4](https://linux-hardware.org/?probe=5987ef39e4) | Sep 11, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [59d8ed6557](https://linux-hardware.org/?probe=59d8ed6557) | Sep 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [cd49377ddf](https://linux-hardware.org/?probe=cd49377ddf) | Sep 11, 2022 |
| HP            | G42                         | Notebook    | [092b9e2c38](https://linux-hardware.org/?probe=092b9e2c38) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [21ae14e7a0](https://linux-hardware.org/?probe=21ae14e7a0) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [3ddd0d7aa0](https://linux-hardware.org/?probe=3ddd0d7aa0) | Sep 11, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [a683b361e4](https://linux-hardware.org/?probe=a683b361e4) | Sep 11, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | Notebook    | [c55fef18c3](https://linux-hardware.org/?probe=c55fef18c3) | Sep 11, 2022 |
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
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [823dbe2390](https://linux-hardware.org/?probe=823dbe2390) | Sep 10, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [6a4fa8ebe7](https://linux-hardware.org/?probe=6a4fa8ebe7) | Sep 09, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [965f8fe14d](https://linux-hardware.org/?probe=965f8fe14d) | Sep 09, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [70c2613095](https://linux-hardware.org/?probe=70c2613095) | Sep 09, 2022 |
| Acer          | AO532h                      | Notebook    | [3ea8a4ba38](https://linux-hardware.org/?probe=3ea8a4ba38) | Sep 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [a0c1db14a0](https://linux-hardware.org/?probe=a0c1db14a0) | Sep 09, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Biostar       | NF560-A2G                   | Desktop     | [68ffa42095](https://linux-hardware.org/?probe=68ffa42095) | Sep 09, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [4f0ec780ee](https://linux-hardware.org/?probe=4f0ec780ee) | Sep 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e4d2c1c120](https://linux-hardware.org/?probe=e4d2c1c120) | Sep 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d28677add3](https://linux-hardware.org/?probe=d28677add3) | Sep 09, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [2557dd83ce](https://linux-hardware.org/?probe=2557dd83ce) | Sep 09, 2022 |
| Dell          | Latitude E6330              | Notebook    | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| Dell          | Latitude 3320               | Notebook    | [1ab9888966](https://linux-hardware.org/?probe=1ab9888966) | Sep 09, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c008fc6206](https://linux-hardware.org/?probe=c008fc6206) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [92ae6811fa](https://linux-hardware.org/?probe=92ae6811fa) | Sep 09, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [d37b0f4483](https://linux-hardware.org/?probe=d37b0f4483) | Sep 08, 2022 |
| ASRock        | Q1900M                      | Desktop     | [aadbe54f8d](https://linux-hardware.org/?probe=aadbe54f8d) | Sep 08, 2022 |
| HP            | ProLiant DL585 G7           | Server      | [1dbd0517e3](https://linux-hardware.org/?probe=1dbd0517e3) | Sep 08, 2022 |
| HP            | ProLiant DL585 G7           | Server      | [1f46338236](https://linux-hardware.org/?probe=1f46338236) | Sep 08, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [9449630b6a](https://linux-hardware.org/?probe=9449630b6a) | Sep 08, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [c8f2e1da45](https://linux-hardware.org/?probe=c8f2e1da45) | Sep 08, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [87580733cb](https://linux-hardware.org/?probe=87580733cb) | Sep 08, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [17675b7bc8](https://linux-hardware.org/?probe=17675b7bc8) | Sep 08, 2022 |
| Google        | Reks                        | Notebook    | [a171b11595](https://linux-hardware.org/?probe=a171b11595) | Sep 08, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [32ab96441e](https://linux-hardware.org/?probe=32ab96441e) | Sep 08, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [478d0564a6](https://linux-hardware.org/?probe=478d0564a6) | Sep 08, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [1c48e52b18](https://linux-hardware.org/?probe=1c48e52b18) | Sep 08, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| HP            | 2175                        | Desktop     | [97d08b25c7](https://linux-hardware.org/?probe=97d08b25c7) | Sep 08, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [06db70e407](https://linux-hardware.org/?probe=06db70e407) | Sep 08, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [141712c674](https://linux-hardware.org/?probe=141712c674) | Sep 07, 2022 |
| Lenovo        | B570e 521524G               | Notebook    | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c75460abba](https://linux-hardware.org/?probe=c75460abba) | Sep 07, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c65eb0b5c8](https://linux-hardware.org/?probe=c65eb0b5c8) | Sep 07, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [044bee5e0c](https://linux-hardware.org/?probe=044bee5e0c) | Sep 07, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [b090ccb8fe](https://linux-hardware.org/?probe=b090ccb8fe) | Sep 07, 2022 |
| Dell          | XPS 17 9720                 | Notebook    | [b85068c001](https://linux-hardware.org/?probe=b85068c001) | Sep 07, 2022 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [6949fd04b7](https://linux-hardware.org/?probe=6949fd04b7) | Sep 07, 2022 |
| ASUSTek       | X99-E WS                    | Desktop     | [fcf815d38f](https://linux-hardware.org/?probe=fcf815d38f) | Sep 07, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [754b9daf74](https://linux-hardware.org/?probe=754b9daf74) | Sep 07, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ca8d36ee7e](https://linux-hardware.org/?probe=ca8d36ee7e) | Sep 07, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [611d7b9001](https://linux-hardware.org/?probe=611d7b9001) | Sep 07, 2022 |
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
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [f4a0990d22](https://linux-hardware.org/?probe=f4a0990d22) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | Notebook    | [fefa3f4935](https://linux-hardware.org/?probe=fefa3f4935) | Sep 06, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dacafc4729](https://linux-hardware.org/?probe=dacafc4729) | Sep 06, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [b76e5a62e8](https://linux-hardware.org/?probe=b76e5a62e8) | Sep 06, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [1020dfb637](https://linux-hardware.org/?probe=1020dfb637) | Sep 06, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | Desktop     | [2c5b0be3af](https://linux-hardware.org/?probe=2c5b0be3af) | Sep 06, 2022 |
| Dell          | XPS 9320                    | Notebook    | [54c8e046a1](https://linux-hardware.org/?probe=54c8e046a1) | Sep 06, 2022 |
| Dell          | Latitude 5530               | Notebook    | [4a2fb0c4c2](https://linux-hardware.org/?probe=4a2fb0c4c2) | Sep 06, 2022 |
| Dell          | Latitude 5530               | Notebook    | [a0896a063c](https://linux-hardware.org/?probe=a0896a063c) | Sep 06, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [b10937286d](https://linux-hardware.org/?probe=b10937286d) | Sep 06, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [4071a8ff9b](https://linux-hardware.org/?probe=4071a8ff9b) | Sep 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [312e33b434](https://linux-hardware.org/?probe=312e33b434) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [6bd37547d3](https://linux-hardware.org/?probe=6bd37547d3) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [5df6bc21c7](https://linux-hardware.org/?probe=5df6bc21c7) | Sep 05, 2022 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [4c68e17f1a](https://linux-hardware.org/?probe=4c68e17f1a) | Sep 05, 2022 |
| Dell          | 0N36HY A06                  | Server      | [ad80e5c56d](https://linux-hardware.org/?probe=ad80e5c56d) | Sep 05, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [26e63d2357](https://linux-hardware.org/?probe=26e63d2357) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e6117fb016](https://linux-hardware.org/?probe=e6117fb016) | Sep 05, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [beb1aeb4ad](https://linux-hardware.org/?probe=beb1aeb4ad) | Sep 05, 2022 |
| HP            | 805D                        | Desktop     | [fdf50a9e36](https://linux-hardware.org/?probe=fdf50a9e36) | Sep 05, 2022 |
| Acer          | Aspire A517-52G             | Notebook    | [c1709e40b7](https://linux-hardware.org/?probe=c1709e40b7) | Sep 05, 2022 |
| Dell          | 06FW8P A00                  | Desktop     | [6023e5aa76](https://linux-hardware.org/?probe=6023e5aa76) | Sep 05, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3438959476](https://linux-hardware.org/?probe=3438959476) | Sep 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [efb1e9883d](https://linux-hardware.org/?probe=efb1e9883d) | Sep 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [20178af23f](https://linux-hardware.org/?probe=20178af23f) | Sep 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f44a7ef51c](https://linux-hardware.org/?probe=f44a7ef51c) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [f85aa66b33](https://linux-hardware.org/?probe=f85aa66b33) | Sep 04, 2022 |
| Dell          | 0N36HY A06                  | Server      | [e50147dafa](https://linux-hardware.org/?probe=e50147dafa) | Sep 04, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [b9f3857d65](https://linux-hardware.org/?probe=b9f3857d65) | Sep 04, 2022 |
| Dell          | Latitude E6330              | Notebook    | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| ASRock        | Q1900M                      | Desktop     | [55a86f60b9](https://linux-hardware.org/?probe=55a86f60b9) | Sep 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c2cd1091cd](https://linux-hardware.org/?probe=c2cd1091cd) | Sep 04, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [ea93dfd855](https://linux-hardware.org/?probe=ea93dfd855) | Sep 04, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [fe5c97cc44](https://linux-hardware.org/?probe=fe5c97cc44) | Sep 04, 2022 |
| Hardkernel    | ODROID-U3 board based on... | Soc         | [04b62e9eb2](https://linux-hardware.org/?probe=04b62e9eb2) | Sep 04, 2022 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [8ffe312747](https://linux-hardware.org/?probe=8ffe312747) | Sep 04, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [438d359ee9](https://linux-hardware.org/?probe=438d359ee9) | Sep 04, 2022 |
| AZW           | SER                         | Mini pc     | [2c0baab61c](https://linux-hardware.org/?probe=2c0baab61c) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 232438J       | Notebook    | [dca0e2fa77](https://linux-hardware.org/?probe=dca0e2fa77) | Sep 04, 2022 |
| Lenovo        | ThinkPad E450 20DCA087CD    | Notebook    | [26928f83da](https://linux-hardware.org/?probe=26928f83da) | Sep 04, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [878661705c](https://linux-hardware.org/?probe=878661705c) | Sep 04, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [eb29524a90](https://linux-hardware.org/?probe=eb29524a90) | Sep 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [3a599be2f2](https://linux-hardware.org/?probe=3a599be2f2) | Sep 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [9736522a27](https://linux-hardware.org/?probe=9736522a27) | Sep 03, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [082520f2d8](https://linux-hardware.org/?probe=082520f2d8) | Sep 03, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| PC Special... | 14 Fusion IV                | Notebook    | [dd9ed93b55](https://linux-hardware.org/?probe=dd9ed93b55) | Sep 03, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9b8eef74b8](https://linux-hardware.org/?probe=9b8eef74b8) | Sep 03, 2022 |
| HP            | Compaq 6910p                | Notebook    | [0165c7d3c6](https://linux-hardware.org/?probe=0165c7d3c6) | Sep 03, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [5c0b32f572](https://linux-hardware.org/?probe=5c0b32f572) | Sep 03, 2022 |
| Chuwi         | LarkBook                    | Notebook    | [351478ee65](https://linux-hardware.org/?probe=351478ee65) | Sep 03, 2022 |
| Aquarius      | NS585                       | Notebook    | [b11a34556d](https://linux-hardware.org/?probe=b11a34556d) | Sep 03, 2022 |
| Dell          | Latitude E6330              | Notebook    | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | Notebook    | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [9a2200f8f8](https://linux-hardware.org/?probe=9a2200f8f8) | Sep 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [b5c7b2be02](https://linux-hardware.org/?probe=b5c7b2be02) | Sep 03, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [1822ab5853](https://linux-hardware.org/?probe=1822ab5853) | Sep 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [2c5c9d2233](https://linux-hardware.org/?probe=2c5c9d2233) | Sep 02, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [0be6c5963d](https://linux-hardware.org/?probe=0be6c5963d) | Sep 02, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [262c6222d1](https://linux-hardware.org/?probe=262c6222d1) | Sep 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [acdd27f635](https://linux-hardware.org/?probe=acdd27f635) | Sep 02, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [3870423379](https://linux-hardware.org/?probe=3870423379) | Sep 02, 2022 |
| Pine Micro... | Pine64+                     | Soc         | [dc7e6f17d4](https://linux-hardware.org/?probe=dc7e6f17d4) | Sep 02, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [2dbc615641](https://linux-hardware.org/?probe=2dbc615641) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [c8bf09dd8d](https://linux-hardware.org/?probe=c8bf09dd8d) | Sep 02, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [11f9e9fa68](https://linux-hardware.org/?probe=11f9e9fa68) | Sep 02, 2022 |
| HP            | 8767 A                      | Desktop     | [62e70ef3e8](https://linux-hardware.org/?probe=62e70ef3e8) | Sep 02, 2022 |
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
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [f25f0f5499](https://linux-hardware.org/?probe=f25f0f5499) | Sep 01, 2022 |
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
| SZMZ          | X99M-G2                     | Desktop     | [eff1231310](https://linux-hardware.org/?probe=eff1231310) | Aug 31, 2022 |
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
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [a77d5e141e](https://linux-hardware.org/?probe=a77d5e141e) | Aug 30, 2022 |
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
| Dell          | 09KPNV A00                  | Desktop     | [7e03afa646](https://linux-hardware.org/?probe=7e03afa646) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [7ed4b144d7](https://linux-hardware.org/?probe=7ed4b144d7) | Aug 28, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [31d4a8fc43](https://linux-hardware.org/?probe=31d4a8fc43) | Aug 28, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | Notebook    | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [ef43339df1](https://linux-hardware.org/?probe=ef43339df1) | Aug 28, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [dff587f11e](https://linux-hardware.org/?probe=dff587f11e) | Aug 28, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [9158baf2c0](https://linux-hardware.org/?probe=9158baf2c0) | Aug 28, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [f17bcbfc4b](https://linux-hardware.org/?probe=f17bcbfc4b) | Aug 28, 2022 |
| Dell          | Latitude 5420               | Notebook    | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [4960a57d91](https://linux-hardware.org/?probe=4960a57d91) | Aug 28, 2022 |
| MSI           | E350IA-E45                  | Desktop     | [d1d570a455](https://linux-hardware.org/?probe=d1d570a455) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| BANGHO        | AERO X2 I1002               | Notebook    | [f24ddb9619](https://linux-hardware.org/?probe=f24ddb9619) | Aug 28, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | Notebook    | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [859b3cb78a](https://linux-hardware.org/?probe=859b3cb78a) | Aug 28, 2022 |
| ASRock        | 990FX Extreme9              | Desktop     | [1a472eb51c](https://linux-hardware.org/?probe=1a472eb51c) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | Notebook    | [a10cbdb73b](https://linux-hardware.org/?probe=a10cbdb73b) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | Notebook    | [562d827323](https://linux-hardware.org/?probe=562d827323) | Aug 27, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | Notebook    | [3d1138a71c](https://linux-hardware.org/?probe=3d1138a71c) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c155c4b324](https://linux-hardware.org/?probe=c155c4b324) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [e4cd019582](https://linux-hardware.org/?probe=e4cd019582) | Aug 27, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6398be9a3e](https://linux-hardware.org/?probe=6398be9a3e) | Aug 27, 2022 |
| HP            | Compaq 6910p                | Notebook    | [894b5297c8](https://linux-hardware.org/?probe=894b5297c8) | Aug 27, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e0fedafd62](https://linux-hardware.org/?probe=e0fedafd62) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8231da35ed](https://linux-hardware.org/?probe=8231da35ed) | Aug 27, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2KU0... | Notebook    | [6500c142f5](https://linux-hardware.org/?probe=6500c142f5) | Aug 27, 2022 |
| Lenovo        | ThinkPad X260 20F5A050IG    | Notebook    | [33b5154a7a](https://linux-hardware.org/?probe=33b5154a7a) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [634c973e53](https://linux-hardware.org/?probe=634c973e53) | Aug 27, 2022 |
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
| MSI           | Creator 15 A11UH            | Notebook    | [fdd5e2b26a](https://linux-hardware.org/?probe=fdd5e2b26a) | Aug 26, 2022 |
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
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [783495e971](https://linux-hardware.org/?probe=783495e971) | Aug 25, 2022 |
| Google        | Terra                       | Notebook    | [72965945d5](https://linux-hardware.org/?probe=72965945d5) | Aug 25, 2022 |
| Dell          | 0D4MD1 A02                  | Desktop     | [7a06622253](https://linux-hardware.org/?probe=7a06622253) | Aug 25, 2022 |
| Google        | Terra                       | Notebook    | [78436fd3bf](https://linux-hardware.org/?probe=78436fd3bf) | Aug 25, 2022 |
| Dell          | 0WG864                      | Desktop     | [a333ec7f99](https://linux-hardware.org/?probe=a333ec7f99) | Aug 25, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [c1c6b26e42](https://linux-hardware.org/?probe=c1c6b26e42) | Aug 25, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [27095a2962](https://linux-hardware.org/?probe=27095a2962) | Aug 25, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e399d35565](https://linux-hardware.org/?probe=e399d35565) | Aug 25, 2022 |
| ASUSTek       | A7N8X2.0                    | Desktop     | [f063b3e61a](https://linux-hardware.org/?probe=f063b3e61a) | Aug 25, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b2dc63405c](https://linux-hardware.org/?probe=b2dc63405c) | Aug 25, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [222aa7a498](https://linux-hardware.org/?probe=222aa7a498) | Aug 25, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [0bcf6f0268](https://linux-hardware.org/?probe=0bcf6f0268) | Aug 25, 2022 |
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
| MSI           | GF63 Thin 10SCSR            | Notebook    | [f3facd36da](https://linux-hardware.org/?probe=f3facd36da) | Aug 24, 2022 |
| Lenovo        | ThinkPad E490 20N8001EUS    | Notebook    | [1620f0e5ff](https://linux-hardware.org/?probe=1620f0e5ff) | Aug 24, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [6bcc6b550f](https://linux-hardware.org/?probe=6bcc6b550f) | Aug 24, 2022 |
| Dell          | 0D4MD1 A02                  | Desktop     | [b634bcdfa9](https://linux-hardware.org/?probe=b634bcdfa9) | Aug 24, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | Notebook    | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [11cfa7a502](https://linux-hardware.org/?probe=11cfa7a502) | Aug 24, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [bc4f5f8811](https://linux-hardware.org/?probe=bc4f5f8811) | Aug 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4b5ebc25d2](https://linux-hardware.org/?probe=4b5ebc25d2) | Aug 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [8b346ab142](https://linux-hardware.org/?probe=8b346ab142) | Aug 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [aa03f81ccc](https://linux-hardware.org/?probe=aa03f81ccc) | Aug 24, 2022 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [01eeb8ce29](https://linux-hardware.org/?probe=01eeb8ce29) | Aug 24, 2022 |
| Google        | Reks                        | Notebook    | [043b648dc5](https://linux-hardware.org/?probe=043b648dc5) | Aug 23, 2022 |
| Google        | Terra                       | Notebook    | [b720f3ca23](https://linux-hardware.org/?probe=b720f3ca23) | Aug 23, 2022 |
| Google        | Terra                       | Notebook    | [0fd5baced8](https://linux-hardware.org/?probe=0fd5baced8) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [dfbced302f](https://linux-hardware.org/?probe=dfbced302f) | Aug 23, 2022 |
| Google        | Terra                       | Notebook    | [92efdef775](https://linux-hardware.org/?probe=92efdef775) | Aug 23, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [e5d3453caa](https://linux-hardware.org/?probe=e5d3453caa) | Aug 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [cdfd15fef9](https://linux-hardware.org/?probe=cdfd15fef9) | Aug 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [182b375456](https://linux-hardware.org/?probe=182b375456) | Aug 23, 2022 |
| Dell          | 0X3D66 A14                  | Server      | [03b4bc97ad](https://linux-hardware.org/?probe=03b4bc97ad) | Aug 23, 2022 |
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
| retsamarre... | Unknown                     | Desktop     | [5bc4dd4776](https://linux-hardware.org/?probe=5bc4dd4776) | Aug 23, 2022 |
| retsamarre... | Unknown                     | Desktop     | [8f8e0f49df](https://linux-hardware.org/?probe=8f8e0f49df) | Aug 23, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [1231c2fabe](https://linux-hardware.org/?probe=1231c2fabe) | Aug 23, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [d0b18cffdb](https://linux-hardware.org/?probe=d0b18cffdb) | Aug 23, 2022 |
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
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [936ce5ca55](https://linux-hardware.org/?probe=936ce5ca55) | Aug 22, 2022 |
| HP            | 2187 A01                    | Desktop     | [ab44144f07](https://linux-hardware.org/?probe=ab44144f07) | Aug 22, 2022 |
| ASUSTek       | Z10PA-U8 Series             | Desktop     | [3e560a4018](https://linux-hardware.org/?probe=3e560a4018) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [aacdd42304](https://linux-hardware.org/?probe=aacdd42304) | Aug 22, 2022 |
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
| MSI           | G31M3                       | Desktop     | [3bb7906f56](https://linux-hardware.org/?probe=3bb7906f56) | Aug 20, 2022 |
| VANT          | MOOVE3-15                   | Notebook    | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [9f5e59e0b9](https://linux-hardware.org/?probe=9f5e59e0b9) | Aug 20, 2022 |
| MSI           | GF75 Thin 10SCSXR           | Notebook    | [095c130069](https://linux-hardware.org/?probe=095c130069) | Aug 20, 2022 |
| Google        | Teemo                       | Desktop     | [4cc9295e6d](https://linux-hardware.org/?probe=4cc9295e6d) | Aug 20, 2022 |
| HP            | 620                         | Notebook    | [d3b1eb8b4e](https://linux-hardware.org/?probe=d3b1eb8b4e) | Aug 20, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [6ba8616656](https://linux-hardware.org/?probe=6ba8616656) | Aug 20, 2022 |
| Samsung       | 935XDB                      | Notebook    | [a8d4f5e6a0](https://linux-hardware.org/?probe=a8d4f5e6a0) | Aug 20, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [9131aa23c4](https://linux-hardware.org/?probe=9131aa23c4) | Aug 20, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [2efae45a8f](https://linux-hardware.org/?probe=2efae45a8f) | Aug 19, 2022 |
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
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [f526447f78](https://linux-hardware.org/?probe=f526447f78) | Aug 19, 2022 |
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
| Lenovo        | ThinkPad Edge E431 62774... | Notebook    | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
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
| Acer          | Nitro AN515-56              | Notebook    | [c62f8ea53b](https://linux-hardware.org/?probe=c62f8ea53b) | Aug 17, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [b648d56b04](https://linux-hardware.org/?probe=b648d56b04) | Aug 17, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [d066e1bcdf](https://linux-hardware.org/?probe=d066e1bcdf) | Aug 17, 2022 |
| ECS           | G31T-M9                     | Desktop     | [6192258c32](https://linux-hardware.org/?probe=6192258c32) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [125fdc6af1](https://linux-hardware.org/?probe=125fdc6af1) | Aug 17, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57732104cd](https://linux-hardware.org/?probe=57732104cd) | Aug 17, 2022 |
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
| ASUSTek       | P6T WS PRO                  | Desktop     | [155ba78790](https://linux-hardware.org/?probe=155ba78790) | Aug 15, 2022 |
| ASUSTek       | WS C422 DC                  | Desktop     | [92d816348a](https://linux-hardware.org/?probe=92d816348a) | Aug 15, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [fee71ca4bf](https://linux-hardware.org/?probe=fee71ca4bf) | Aug 15, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [bfcafd66de](https://linux-hardware.org/?probe=bfcafd66de) | Aug 15, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [9a1ff39910](https://linux-hardware.org/?probe=9a1ff39910) | Aug 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [265b666497](https://linux-hardware.org/?probe=265b666497) | Aug 14, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [39da8f51fe](https://linux-hardware.org/?probe=39da8f51fe) | Aug 14, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [49e3ff7af1](https://linux-hardware.org/?probe=49e3ff7af1) | Aug 14, 2022 |
| Dell          | Latitude 3320               | Notebook    | [b8e1190875](https://linux-hardware.org/?probe=b8e1190875) | Aug 14, 2022 |
| Dell          | Latitude 3320               | Notebook    | [f489cd4f21](https://linux-hardware.org/?probe=f489cd4f21) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [fcdd677280](https://linux-hardware.org/?probe=fcdd677280) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [eeed6b3d08](https://linux-hardware.org/?probe=eeed6b3d08) | Aug 14, 2022 |
| HP            | Compaq 6910p                | Notebook    | [97e8467d4d](https://linux-hardware.org/?probe=97e8467d4d) | Aug 13, 2022 |
| Dell          | Latitude E5430 vPro         | Notebook    | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [cdba281a27](https://linux-hardware.org/?probe=cdba281a27) | Aug 13, 2022 |
| HP            | Pavilion g7                 | Notebook    | [34a327329a](https://linux-hardware.org/?probe=34a327329a) | Aug 13, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [8b417889e1](https://linux-hardware.org/?probe=8b417889e1) | Aug 13, 2022 |
| ASRock        | AB350 Gaming K4             | Desktop     | [8a6141848a](https://linux-hardware.org/?probe=8a6141848a) | Aug 13, 2022 |
| Dell          | 0WWJRX A00                  | Desktop     | [c9a3a6e952](https://linux-hardware.org/?probe=c9a3a6e952) | Aug 13, 2022 |
| HP            | Presario CQ56               | Notebook    | [48dfc2da91](https://linux-hardware.org/?probe=48dfc2da91) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [188bfa465d](https://linux-hardware.org/?probe=188bfa465d) | Aug 13, 2022 |
| Dell          | Latitude E6330              | Notebook    | [b48c021700](https://linux-hardware.org/?probe=b48c021700) | Aug 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [94eb72e4ac](https://linux-hardware.org/?probe=94eb72e4ac) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8c792d555c](https://linux-hardware.org/?probe=8c792d555c) | Aug 12, 2022 |
| Intel         | S1200BTL E98681-352         | Server      | [1db51bcff9](https://linux-hardware.org/?probe=1db51bcff9) | Aug 12, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [5b24d3e87b](https://linux-hardware.org/?probe=5b24d3e87b) | Aug 12, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [3dd4d44be4](https://linux-hardware.org/?probe=3dd4d44be4) | Aug 12, 2022 |
| Dell          | 0WG864                      | Desktop     | [de74f89735](https://linux-hardware.org/?probe=de74f89735) | Aug 12, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [471a1ec71e](https://linux-hardware.org/?probe=471a1ec71e) | Aug 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [ed94063eb8](https://linux-hardware.org/?probe=ed94063eb8) | Aug 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [84771d9750](https://linux-hardware.org/?probe=84771d9750) | Aug 12, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [434ba505a3](https://linux-hardware.org/?probe=434ba505a3) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [ed37ad46b6](https://linux-hardware.org/?probe=ed37ad46b6) | Aug 12, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [7afaba2067](https://linux-hardware.org/?probe=7afaba2067) | Aug 12, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [57be8a8829](https://linux-hardware.org/?probe=57be8a8829) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [2fab557514](https://linux-hardware.org/?probe=2fab557514) | Aug 12, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [6f828c5743](https://linux-hardware.org/?probe=6f828c5743) | Aug 12, 2022 |
| System76      | Oryx Pro                    | Notebook    | [87b38f5a99](https://linux-hardware.org/?probe=87b38f5a99) | Aug 12, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [c38e80ade4](https://linux-hardware.org/?probe=c38e80ade4) | Aug 11, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [efd4ec3ee7](https://linux-hardware.org/?probe=efd4ec3ee7) | Aug 11, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [059e0786bf](https://linux-hardware.org/?probe=059e0786bf) | Aug 11, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [934583e785](https://linux-hardware.org/?probe=934583e785) | Aug 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 4368      | 59.27%  |
| Debian 10                       | 1715      | 23.27%  |
| Debian Testing                  | 618       | 8.39%   |
| Debian 9                        | 318       | 4.31%   |
| Debian Unstable                 | 260       | 3.53%   |
| Debian 11-updates               | 38        | 0.52%   |
| Debian 8                        | 33        | 0.45%   |
| Debian Testing/unstable         | 5         | 0.07%   |
| Debian 7                        | 4         | 0.05%   |
| Debian Testing-proposed-updates | 3         | 0.04%   |
| Debian Sid                      | 2         | 0.03%   |
| Debian 21                       | 2         | 0.03%   |
| Debian                          | 2         | 0.03%   |
| Debian 99                       | 1         | 0.01%   |
| Debian 16                       | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Debian | 7182      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.10.0-8-amd64  | 977       | 12.01%  |
| 5.10.0-7-amd64  | 654       | 8.04%   |
| 5.10.0-10-amd64 | 570       | 7.01%   |
| 5.10.0-16-amd64 | 350       | 4.3%    |
| 5.10.0-9-amd64  | 324       | 3.98%   |
| 5.10.0-13-amd64 | 256       | 3.15%   |
| 5.10.0-11-amd64 | 192       | 2.36%   |
| 4.19.0-6-amd64  | 144       | 1.77%   |
| 4.19.0-9-amd64  | 143       | 1.76%   |
| 5.10.0-14-amd64 | 137       | 1.68%   |
| 4.19.0-13-amd64 | 123       | 1.51%   |
| 4.19.0-8-amd64  | 119       | 1.46%   |
| 5.10.0-17-amd64 | 118       | 1.45%   |
| 5.10.0-2-amd64  | 114       | 1.4%    |
| 4.19.0-16-amd64 | 108       | 1.33%   |
| 4.19.0-14-amd64 | 104       | 1.28%   |
| 5.15.0-2-amd64  | 95        | 1.17%   |
| 5.10.0-18-amd64 | 95        | 1.17%   |
| 4.19.0-17-amd64 | 94        | 1.16%   |
| 4.19.0-12-amd64 | 88        | 1.08%   |
| 4.19.0-10-amd64 | 87        | 1.07%   |
| 5.10.0-15-amd64 | 83        | 1.02%   |
| 5.10.0-12-amd64 | 72        | 0.88%   |
| 4.9.0-8-amd64   | 70        | 0.86%   |
| 5.10.0-6-amd64  | 66        | 0.81%   |
| 5.6.0-2-amd64   | 53        | 0.65%   |
| 5.18.0-2-amd64  | 52        | 0.64%   |
| 4.19.0-5-amd64  | 48        | 0.59%   |
| 5.4.0-4-amd64   | 45        | 0.55%   |
| 5.7.0-1-amd64   | 44        | 0.54%   |
| 5.10.0-3-amd64  | 44        | 0.54%   |
| 5.17.0-1-amd64  | 40        | 0.49%   |
| 4.19.0-11-amd64 | 40        | 0.49%   |
| 5.8.0-2-amd64   | 36        | 0.44%   |
| 5.18.0-4-amd64  | 36        | 0.44%   |
| 5.16.0-6-amd64  | 36        | 0.44%   |
| 5.9.0-1-amd64   | 35        | 0.43%   |
| 5.10.0-5-amd64  | 35        | 0.43%   |
| 4.19.0-18-amd64 | 35        | 0.43%   |
| 5.19.0-1-amd64  | 34        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 4044      | 53.1%   |
| 4.19.0  | 1210      | 15.89%  |
| 4.9.0   | 240       | 3.15%   |
| 5.18.0  | 170       | 2.23%   |
| 5.15.0  | 158       | 2.07%   |
| 5.9.0   | 149       | 1.96%   |
| 5.16.0  | 127       | 1.67%   |
| 5.8.0   | 120       | 1.58%   |
| 5.7.0   | 120       | 1.58%   |
| 5.4.0   | 118       | 1.55%   |
| 5.6.0   | 100       | 1.31%   |
| 5.14.0  | 89        | 1.17%   |
| 5.17.0  | 69        | 0.91%   |
| 5.13.19 | 51        | 0.67%   |
| 5.19.0  | 47        | 0.62%   |
| 5.3.0   | 39        | 0.51%   |
| 5.5.0   | 32        | 0.42%   |
| 5.11.22 | 27        | 0.35%   |
| 5.2.0   | 21        | 0.28%   |
| 4.18.0  | 21        | 0.28%   |
| 5.15.32 | 18        | 0.24%   |
| 3.16.0  | 18        | 0.24%   |
| 5.15.39 | 17        | 0.22%   |
| 5.15.35 | 17        | 0.22%   |
| 5.4.106 | 15        | 0.2%    |
| 4.15.18 | 14        | 0.18%   |
| 5.10.92 | 13        | 0.17%   |
| 5.15.30 | 12        | 0.16%   |
| 5.4.78  | 11        | 0.14%   |
| 5.15.53 | 11        | 0.14%   |
| 5.13.0  | 11        | 0.14%   |
| 5.4.65  | 9         | 0.12%   |
| 5.12.0  | 9         | 0.12%   |
| 5.10.63 | 8         | 0.11%   |
| 4.17.0  | 8         | 0.11%   |
| 5.4.44  | 7         | 0.09%   |
| 5.8.16  | 6         | 0.08%   |
| 5.3.18  | 6         | 0.08%   |
| 5.15.61 | 6         | 0.08%   |
| 5.11.0  | 6         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 4135      | 54.52%  |
| 4.19    | 1223      | 16.12%  |
| 5.15    | 265       | 3.49%   |
| 4.9     | 250       | 3.3%    |
| 5.4     | 214       | 2.82%   |
| 5.18    | 180       | 2.37%   |
| 5.9     | 158       | 2.08%   |
| 5.16    | 134       | 1.77%   |
| 5.8     | 132       | 1.74%   |
| 5.7     | 128       | 1.69%   |
| 5.6     | 110       | 1.45%   |
| 5.14    | 98        | 1.29%   |
| 5.17    | 84        | 1.11%   |
| 5.13    | 75        | 0.99%   |
| 5.3     | 64        | 0.84%   |
| 5.19    | 53        | 0.7%    |
| 5.11    | 49        | 0.65%   |
| 5.5     | 38        | 0.5%    |
| 5.2     | 26        | 0.34%   |
| 4.18    | 22        | 0.29%   |
| 4.15    | 19        | 0.25%   |
| 3.16    | 18        | 0.24%   |
| 5.12    | 16        | 0.21%   |
| 5.0     | 13        | 0.17%   |
| 5       | 11        | 0.15%   |
| 4.4     | 11        | 0.15%   |
| 4.17    | 8         | 0.11%   |
| 5.1     | 6         | 0.08%   |
| 4.14    | 6         | 0.08%   |
| 6.0     | 4         | 0.05%   |
| 4.1     | 4         | 0.05%   |
| 3.10    | 4         | 0.05%   |
| 4.20    | 3         | 0.04%   |
| 4.16    | 3         | 0.04%   |
| 4.13    | 3         | 0.04%   |
| 4.8     | 2         | 0.03%   |
| 4.10    | 2         | 0.03%   |
| 3.18    | 2         | 0.03%   |
| 5.4.104 | 1         | 0.01%   |
| 5.15.6  | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6744      | 93.88%  |
| i686    | 252       | 3.51%   |
| aarch64 | 134       | 1.87%   |
| armv7l  | 40        | 0.56%   |
| riscv64 | 6         | 0.08%   |
| ppc64   | 3         | 0.04%   |
| sh4a    | 1         | 0.01%   |
| ppc64le | 1         | 0.01%   |
| mips64  | 1         | 0.01%   |
| i586    | 1         | 0.01%   |
| armv6l  | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 2525      | 34.4%   |
| GNOME             | 1553      | 21.16%  |
| XFCE              | 881       | 12%     |
| KDE5              | 795       | 10.83%  |
| MATE              | 312       | 4.25%   |
| X-Cinnamon        | 217       | 2.96%   |
| Cinnamon          | 206       | 2.81%   |
| KDE               | 200       | 2.72%   |
| LXDE              | 196       | 2.67%   |
| i3                | 104       | 1.42%   |
| LXQt              | 99        | 1.35%   |
| GNOME Flashback   | 44        | 0.6%    |
| Openbox           | 43        | 0.59%   |
| lightdm-xsession  | 39        | 0.53%   |
| Budgie            | 22        | 0.3%    |
| Trinity           | 20        | 0.27%   |
| GNOME Classic     | 17        | 0.23%   |
| awesome           | 9         | 0.12%   |
| sway              | 7         | 0.1%    |
| KDE4              | 6         | 0.08%   |
| fluxbox           | 6         | 0.08%   |
| Enlightenment     | 5         | 0.07%   |
| ICEWM             | 4         | 0.05%   |
| DWM               | 4         | 0.05%   |
| bspwm             | 4         | 0.05%   |
| default           | 3         | 0.04%   |
| Cutefish          | 3         | 0.04%   |
| xmonad            | 2         | 0.03%   |
| Unity             | 2         | 0.03%   |
| Phosh:GNOME       | 2         | 0.03%   |
| GNUstep           | 2         | 0.03%   |
| x-session-manager | 1         | 0.01%   |
| wmaker-common     | 1         | 0.01%   |
| UKUI              | 1         | 0.01%   |
| matchbox          | 1         | 0.01%   |
| jwm               | 1         | 0.01%   |
| i3-with-shmlog    | 1         | 0.01%   |
| i3-gaps           | 1         | 0.01%   |
| fvwm              | 1         | 0.01%   |
| Deepin            | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3838      | 52.52%  |
| Unknown | 1781      | 24.37%  |
| Wayland | 1027      | 14.05%  |
| Tty     | 662       | 9.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3586      | 48.87%  |
| GDM     | 1144      | 15.59%  |
| LightDM | 927       | 12.63%  |
| SDDM    | 784       | 10.68%  |
| TDM     | 597       | 8.14%   |
| GDM3    | 214       | 2.92%   |
| XDM     | 30        | 0.41%   |
| SLiM    | 26        | 0.35%   |
| NODM    | 14        | 0.19%   |
| KDM     | 10        | 0.14%   |
| LXDM    | 3         | 0.04%   |
| WDM     | 2         | 0.03%   |
| Ly      | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2207      | 30.27%  |
| Unknown | 1359      | 18.64%  |
| ru_RU   | 920       | 12.62%  |
| de_DE   | 404       | 5.54%   |
| fr_FR   | 332       | 4.55%   |
| en_GB   | 328       | 4.5%    |
| pt_BR   | 235       | 3.22%   |
| es_ES   | 196       | 2.69%   |
| it_IT   | 144       | 1.98%   |
| pl_PL   | 99        | 1.36%   |
| en_AU   | 94        | 1.29%   |
| C       | 93        | 1.28%   |
| en_CA   | 84        | 1.15%   |
| en_IN   | 49        | 0.67%   |
| zh_CN   | 45        | 0.62%   |
| es_MX   | 44        | 0.6%    |
| en_IE   | 39        | 0.53%   |
| hu_HU   | 36        | 0.49%   |
| es_AR   | 36        | 0.49%   |
| es_CL   | 32        | 0.44%   |
| es_VE   | 31        | 0.43%   |
| ja_JP   | 27        | 0.37%   |
| pt_PT   | 26        | 0.36%   |
| de_CH   | 25        | 0.34%   |
| de_AT   | 23        | 0.32%   |
| nl_NL   | 21        | 0.29%   |
| en_ZA   | 20        | 0.27%   |
| cs_CZ   | 20        | 0.27%   |
| sv_SE   | 18        | 0.25%   |
| en_NZ   | 18        | 0.25%   |
| ru_UA   | 15        | 0.21%   |
| fi_FI   | 14        | 0.19%   |
| es_CO   | 14        | 0.19%   |
| nl_BE   | 12        | 0.16%   |
| fr_CH   | 12        | 0.16%   |
| uk_UA   | 11        | 0.15%   |
| fr_BE   | 11        | 0.15%   |
| tr_TR   | 10        | 0.14%   |
| en_SG   | 10        | 0.14%   |
| ca_ES   | 10        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3693      | 50.76%  |
| BIOS | 3582      | 49.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type       | Computers | Percent |
|------------|-----------|---------|
| Ext4       | 4910      | 67.82%  |
| Overlay    | 1647      | 22.75%  |
| Btrfs      | 243       | 3.36%   |
| Unknown    | 168       | 2.32%   |
| Zfs        | 92        | 1.27%   |
| Xfs        | 90        | 1.24%   |
| Ext3       | 26        | 0.36%   |
| Ext2       | 23        | 0.32%   |
| Tmpfs      | 11        | 0.15%   |
| Rootfs     | 11        | 0.15%   |
| F2fs       | 6         | 0.08%   |
| Aufs       | 6         | 0.08%   |
| XXXXXXX    | 2         | 0.03%   |
| Ubifs      | 2         | 0.03%   |
| Jfs        | 2         | 0.03%   |
| Fuse.sshfs | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3899      | 53.25%  |
| MBR     | 1890      | 25.81%  |
| Unknown | 1533      | 20.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5885      | 81.02%  |
| Yes       | 1379      | 18.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5142      | 70.77%  |
| Yes       | 2124      | 29.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1121      | 15.61%  |
| Lenovo                  | 1058      | 14.73%  |
| Hewlett-Packard         | 762       | 10.61%  |
| Dell                    | 752       | 10.47%  |
| Apple                   | 625       | 8.7%    |
| Gigabyte Technology     | 478       | 6.66%   |
| MSI                     | 345       | 4.8%    |
| ASRock                  | 298       | 4.15%   |
| Acer                    | 260       | 3.62%   |
| Intel                   | 161       | 2.24%   |
| Google                  | 125       | 1.74%   |
| Raspberry Pi Foundation | 84        | 1.17%   |
| Unknown                 | 81        | 1.13%   |
| Supermicro              | 68        | 0.95%   |
| Samsung Electronics     | 63        | 0.88%   |
| Toshiba                 | 55        | 0.77%   |
| ECS                     | 48        | 0.67%   |
| Aquarius                | 45        | 0.63%   |
| Fujitsu                 | 41        | 0.57%   |
| Sony                    | 36        | 0.5%    |
| Foxconn                 | 33        | 0.46%   |
| HUAWEI                  | 32        | 0.45%   |
| Positivo                | 24        | 0.33%   |
| Notebook                | 21        | 0.29%   |
| Medion                  | 20        | 0.28%   |
| Biostar                 | 18        | 0.25%   |
| ASRockRack              | 18        | 0.25%   |
| IBM                     | 17        | 0.24%   |
| Fujitsu Siemens         | 17        | 0.24%   |
| AZW                     | 17        | 0.24%   |
| Pegatron                | 16        | 0.22%   |
| Alienware               | 16        | 0.22%   |
| sunxi                   | 12        | 0.17%   |
| Pine Microsystems       | 12        | 0.17%   |
| Microsoft               | 12        | 0.17%   |
| Packard Bell            | 11        | 0.15%   |
| AMI                     | 11        | 0.15%   |
| Timi                    | 10        | 0.14%   |
| Shuttle                 | 10        | 0.14%   |
| Hardkernel              | 10        | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 304       | 4.23%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 112       | 1.56%   |
| Unknown                                   | 109       | 1.52%   |
| ASUS All Series                           | 108       | 1.5%    |
| Apple MacBookAir7,1                       | 75        | 1.04%   |
| Google Enguarde                           | 74        | 1.03%   |
| Apple MacBookAir7,2                       | 72        | 1%      |
| Apple MacBook2,1                          | 56        | 0.78%   |
| ASUS S20 K29                              | 55        | 0.77%   |
| Aquarius NS585                            | 43        | 0.6%    |
| MSI MS-7996                               | 35        | 0.49%   |
| Lenovo ThinkPad E475 20H40006US           | 23        | 0.32%   |
| Apple MacBook4,1                          | 23        | 0.32%   |
| ECS G31T-M9                               | 20        | 0.28%   |
| ASRock H470M-HVS                          | 20        | 0.28%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 19        | 0.26%   |
| MSI MS-7817                               | 19        | 0.26%   |
| HP Notebook                               | 19        | 0.26%   |
| ASUS PRIME H510M-A                        | 19        | 0.26%   |
| Google Terra                              | 18        | 0.25%   |
| Gigabyte H81M-S2V                         | 17        | 0.24%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 16        | 0.22%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.22%   |
| Gigabyte H410M S2H                        | 16        | 0.22%   |
| ECS H61H2-M13                             | 16        | 0.22%   |
| Acer Aspire A315-23                       | 16        | 0.22%   |
| Supermicro Super Server                   | 15        | 0.21%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 14        | 0.19%   |
| HP Pavilion g6                            | 14        | 0.19%   |
| Dell OptiPlex 7010                        | 14        | 0.19%   |
| ASUS P8H61-M LX3 R2.0                     | 14        | 0.19%   |
| ASUS 1005HA                               | 13        | 0.18%   |
| ASUS PRIME A320M-K                        | 12        | 0.17%   |
| Gigabyte B450M DS3H                       | 11        | 0.15%   |
| ASUS TUF Gaming X570-PLUS                 | 11        | 0.15%   |
| MSI MS-7C56                               | 10        | 0.14%   |
| Gigabyte B450M S2H                        | 10        | 0.14%   |
| ASUS PRIME B450M-A                        | 10        | 0.14%   |
| ASRock B450M Pro4                         | 10        | 0.14%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 9         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 666       | 9.27%   |
| Apple MacBook5     | 305       | 4.25%   |
| Dell Latitude      | 198       | 2.76%   |
| Dell Inspiron      | 190       | 2.65%   |
| Acer Aspire        | 167       | 2.33%   |
| Apple MacBookAir7  | 147       | 2.05%   |
| Lenovo IdeaPad     | 146       | 2.03%   |
| ASUS PRIME         | 144       | 2.01%   |
| Unknown            | 109       | 1.52%   |
| ASUS All           | 108       | 1.5%    |
| HP EliteBook       | 105       | 1.46%   |
| HP Pavilion        | 102       | 1.42%   |
| Dell OptiPlex      | 95        | 1.32%   |
| RPi Raspberry      | 84        | 1.17%   |
| HP Compaq          | 76        | 1.06%   |
| HP ProBook         | 74        | 1.03%   |
| HP Laptop          | 74        | 1.03%   |
| Google Enguarde    | 74        | 1.03%   |
| Dell XPS           | 69        | 0.96%   |
| Dell Precision     | 68        | 0.95%   |
| ASUS ROG           | 66        | 0.92%   |
| Dell Vostro        | 57        | 0.79%   |
| Apple MacBook2     | 56        | 0.78%   |
| ASUS S20           | 55        | 0.77%   |
| ASUS TUF           | 52        | 0.72%   |
| Lenovo ThinkCentre | 49        | 0.68%   |
| Aquarius NS585     | 43        | 0.6%    |
| Toshiba Satellite  | 42        | 0.58%   |
| Dell PowerEdge     | 41        | 0.57%   |
| ASUS VivoBook      | 39        | 0.54%   |
| MSI MS-7996        | 35        | 0.49%   |
| HP ProLiant        | 35        | 0.49%   |
| ASUS P8H61-M       | 31        | 0.43%   |
| Gigabyte B450M     | 28        | 0.39%   |
| HP 250             | 27        | 0.38%   |
| ASUS ZenBook       | 25        | 0.35%   |
| Lenovo Yoga        | 24        | 0.33%   |
| HP EliteDesk       | 23        | 0.32%   |
| Apple MacBook4     | 23        | 0.32%   |
| HP ENVY            | 22        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 786       | 10.94%  |
| 2019    | 640       | 8.91%   |
| 2018    | 603       | 8.4%    |
| 2009    | 578       | 8.05%   |
| 2012    | 511       | 7.12%   |
| 2021    | 480       | 6.68%   |
| 2011    | 461       | 6.42%   |
| 2017    | 439       | 6.11%   |
| 2013    | 417       | 5.81%   |
| 2015    | 411       | 5.72%   |
| 2016    | 379       | 5.28%   |
| 2014    | 341       | 4.75%   |
| 2010    | 285       | 3.97%   |
| 2008    | 234       | 3.26%   |
| 2007    | 206       | 2.87%   |
| Unknown | 156       | 2.17%   |
| 2022    | 126       | 1.75%   |
| 2006    | 52        | 0.72%   |
| 2005    | 38        | 0.53%   |
| 2004    | 17        | 0.24%   |
| 2003    | 15        | 0.21%   |
| 2002    | 3         | 0.04%   |
| 2001    | 3         | 0.04%   |
| 2000    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3714      | 51.71%  |
| Desktop        | 2742      | 38.18%  |
| Convertible    | 217       | 3.02%   |
| System on chip | 143       | 1.99%   |
| Server         | 135       | 1.88%   |
| Mini pc        | 129       | 1.8%    |
| All in one     | 55        | 0.77%   |
| Tablet         | 36        | 0.5%    |
| Phone          | 9         | 0.13%   |
| Other          | 2         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6857      | 95.01%  |
| Enabled  | 360       | 4.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7038      | 97.98%  |
| Yes  | 145       | 2.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1531      | 21.1%   |
| 16.01-24.0      | 1345      | 18.54%  |
| 3.01-4.0        | 1277      | 17.6%   |
| 8.01-16.0       | 1097      | 15.12%  |
| 1.01-2.0        | 665       | 9.17%   |
| 32.01-64.0      | 608       | 8.38%   |
| 64.01-256.0     | 276       | 3.8%    |
| 2.01-3.0        | 148       | 2.04%   |
| 0.51-1.0        | 129       | 1.78%   |
| 24.01-32.0      | 110       | 1.52%   |
| 0.01-0.5        | 37        | 0.51%   |
| More than 256.0 | 23        | 0.32%   |
| Unknown         | 9         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2518      | 32.68%  |
| 2.01-3.0        | 1349      | 17.51%  |
| 0.51-1.0        | 1226      | 15.91%  |
| 4.01-8.0        | 1000      | 12.98%  |
| 3.01-4.0        | 743       | 9.64%   |
| 8.01-16.0       | 351       | 4.56%   |
| 0.01-0.5        | 308       | 4%      |
| 16.01-24.0      | 97        | 1.26%   |
| 32.01-64.0      | 42        | 0.55%   |
| 24.01-32.0      | 36        | 0.47%   |
| 64.01-256.0     | 16        | 0.21%   |
| Unknown         | 16        | 0.21%   |
| More than 256.0 | 1         | 0.01%   |
| 0               | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4694      | 64.05%  |
| 2       | 1474      | 20.11%  |
| 3       | 493       | 6.73%   |
| 4       | 281       | 3.83%   |
| 5       | 137       | 1.87%   |
| 6       | 70        | 0.96%   |
| 0       | 48        | 0.65%   |
| 7       | 46        | 0.63%   |
| 8       | 31        | 0.42%   |
| 9       | 17        | 0.23%   |
| 10      | 10        | 0.14%   |
| 11      | 6         | 0.08%   |
| 12      | 5         | 0.07%   |
| 14      | 4         | 0.05%   |
| 13      | 3         | 0.04%   |
| Unknown | 3         | 0.04%   |
| 28      | 2         | 0.03%   |
| 16      | 2         | 0.03%   |
| 46      | 1         | 0.01%   |
| 27      | 1         | 0.01%   |
| 17      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4749      | 65.76%  |
| Yes       | 2473      | 34.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6259      | 86.99%  |
| No        | 936       | 13.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4873      | 67.59%  |
| No        | 2337      | 32.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3984      | 55.03%  |
| No        | 3256      | 44.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1710      | 23.69%  |
| Russia       | 1063      | 14.73%  |
| Germany      | 640       | 8.87%   |
| France       | 447       | 6.19%   |
| Brazil       | 362       | 5.01%   |
| Spain        | 291       | 4.03%   |
| Italy        | 223       | 3.09%   |
| UK           | 197       | 2.73%   |
| Poland       | 158       | 2.19%   |
| Canada       | 136       | 1.88%   |
| Switzerland  | 118       | 1.63%   |
| Australia    | 115       | 1.59%   |
| Netherlands  | 107       | 1.48%   |
| Ukraine      | 88        | 1.22%   |
| China        | 82        | 1.14%   |
| Mexico       | 73        | 1.01%   |
| India        | 73        | 1.01%   |
| Hungary      | 67        | 0.93%   |
| Sweden       | 64        | 0.89%   |
| Argentina    | 62        | 0.86%   |
| Austria      | 60        | 0.83%   |
| Belgium      | 59        | 0.82%   |
| Portugal     | 56        | 0.78%   |
| Finland      | 50        | 0.69%   |
| Czechia      | 50        | 0.69%   |
| Turkey       | 44        | 0.61%   |
| Norway       | 40        | 0.55%   |
| Chile        | 39        | 0.54%   |
| Japan        | 38        | 0.53%   |
| Venezuela    | 36        | 0.5%    |
| Greece       | 35        | 0.48%   |
| Ireland      | 32        | 0.44%   |
| Romania      | 30        | 0.42%   |
| Bulgaria     | 30        | 0.42%   |
| New Zealand  | 27        | 0.37%   |
| South Africa | 26        | 0.36%   |
| Colombia     | 25        | 0.35%   |
| Indonesia    | 23        | 0.32%   |
| Denmark      | 23        | 0.32%   |
| Belarus      | 20        | 0.28%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangor            | 657       | 8.67%   |
| Voronezh          | 643       | 8.49%   |
| Dover-Foxcroft    | 305       | 4.03%   |
| Moscow            | 100       | 1.32%   |
| St Petersburg     | 96        | 1.27%   |
| Paris             | 74        | 0.98%   |
| Berlin            | 62        | 0.82%   |
| Sao Paulo         | 59        | 0.78%   |
| Madrid            | 49        | 0.65%   |
| Seville           | 47        | 0.62%   |
| Vienna            | 45        | 0.59%   |
| Zurich            | 44        | 0.58%   |
| Warsaw            | 40        | 0.53%   |
| Munich            | 37        | 0.49%   |
| Amsterdam         | 37        | 0.49%   |
| Barcelona         | 30        | 0.4%    |
| Sydney            | 29        | 0.38%   |
| Milan             | 29        | 0.38%   |
| Hamburg           | 29        | 0.38%   |
| Perm              | 28        | 0.37%   |
| Budapest          | 28        | 0.37%   |
| London            | 25        | 0.33%   |
| Brisbane          | 24        | 0.32%   |
| Prague            | 23        | 0.3%    |
| Melbourne         | 23        | 0.3%    |
| Frankfurt am Main | 23        | 0.3%    |
| Rio de Janeiro    | 22        | 0.29%   |
| Kyiv              | 22        | 0.29%   |
| Helsinki          | 22        | 0.29%   |
| Toronto           | 21        | 0.28%   |
| Dublin            | 21        | 0.28%   |
| Yekaterinburg     | 19        | 0.25%   |
| San José         | 19        | 0.25%   |
| Falkenstein       | 19        | 0.25%   |
| Brasília         | 19        | 0.25%   |
| Athens            | 19        | 0.25%   |
| New York          | 18        | 0.24%   |
| Cologne           | 17        | 0.22%   |
| Valencia          | 16        | 0.21%   |
| Stockholm         | 16        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1535      | 2293   | 15.13%  |
| WDC                 | 1513      | 2477   | 14.91%  |
| Seagate             | 1414      | 2317   | 13.94%  |
| Toshiba             | 727       | 1066   | 7.17%   |
| Kingston            | 586       | 740    | 5.78%   |
| Unknown             | 525       | 714    | 5.17%   |
| Crucial             | 466       | 600    | 4.59%   |
| SanDisk             | 388       | 491    | 3.82%   |
| Hitachi             | 326       | 430    | 3.21%   |
| Fujitsu             | 258       | 267    | 2.54%   |
| Intel               | 216       | 296    | 2.13%   |
| SK hynix            | 202       | 252    | 1.99%   |
| A-DATA Technology   | 194       | 302    | 1.91%   |
| Apple               | 190       | 228    | 1.87%   |
| HGST                | 171       | 270    | 1.69%   |
| Micron Technology   | 107       | 115    | 1.05%   |
| China               | 75        | 84     | 0.74%   |
| Phison              | 59        | 84     | 0.58%   |
| Transcend           | 55        | 64     | 0.54%   |
| SPCC                | 52        | 58     | 0.51%   |
| OCZ                 | 52        | 64     | 0.51%   |
| KIOXIA              | 49        | 60     | 0.48%   |
| PNY                 | 42        | 56     | 0.41%   |
| Intenso             | 41        | 56     | 0.4%    |
| Patriot             | 40        | 49     | 0.39%   |
| Maxtor              | 39        | 51     | 0.38%   |
| Unknown             | 39        | 41     | 0.38%   |
| Hewlett-Packard     | 38        | 64     | 0.37%   |
| Corsair             | 38        | 53     | 0.37%   |
| LITEON              | 35        | 41     | 0.34%   |
| Silicon Motion      | 33        | 38     | 0.33%   |
| Netac               | 30        | 95     | 0.3%    |
| SABRENT             | 29        | 31     | 0.29%   |
| Gigabyte Technology | 26        | 32     | 0.26%   |
| GOODRAM             | 24        | 35     | 0.24%   |
| JMicron Technology  | 23        | 24     | 0.23%   |
| XPG                 | 18        | 25     | 0.18%   |
| Team                | 18        | 27     | 0.18%   |
| Plextor             | 18        | 23     | 0.18%   |
| LITEONIT            | 17        | 21     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 201       | 1.79%   |
| Kingston SA400S37240G 240GB SSD    | 128       | 1.14%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 125       | 1.12%   |
| Seagate ST500DM002-1BD142 500GB    | 91        | 0.81%   |
| Kingston SA400S37120G 120GB SSD    | 86        | 0.77%   |
| Crucial CT480BX500SSD1 480GB       | 81        | 0.72%   |
| Apple SSD AP0128H 121GB            | 75        | 0.67%   |
| Samsung SSD 860 EVO 500GB          | 72        | 0.64%   |
| Apple SSD SM0128G 121GB            | 72        | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB     | 70        | 0.62%   |
| Samsung SSD 850 EVO 250GB          | 68        | 0.61%   |
| Samsung SSD 860 EVO 1TB            | 65        | 0.58%   |
| Seagate ST1000LM035-1RK172 1TB     | 64        | 0.57%   |
| Samsung SSD 860 EVO 250GB          | 62        | 0.55%   |
| Kingston SV300S37A120G 120GB SSD   | 61        | 0.54%   |
| Kingston SA400S37480G 480GB SSD    | 59        | 0.53%   |
| Toshiba DT01ACA050 500GB           | 58        | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 56        | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB       | 55        | 0.49%   |
| Crucial CT500MX500SSD1 500GB       | 55        | 0.49%   |
| Unknown MMC Card  32GB             | 52        | 0.46%   |
| A-DATA SU800 512GB SSD             | 49        | 0.44%   |
| Toshiba MK1655GSXF 160GB           | 47        | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB     | 46        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB        | 46        | 0.41%   |
| Crucial CT240BX500SSD1 240GB       | 45        | 0.4%    |
| Toshiba HDWD110 1TB                | 43        | 0.38%   |
| Toshiba MQ01ABD100 1TB             | 42        | 0.37%   |
| Toshiba MK1653GSX 160GB            | 42        | 0.37%   |
| Toshiba DT01ACA100 1TB             | 42        | 0.37%   |
| Unknown AGND3R  16GB               | 40        | 0.36%   |
| HGST HTS721010A9E630 1TB           | 39        | 0.35%   |
| Unknown                            | 39        | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB           | 38        | 0.34%   |
| Samsung SSD 850 EVO 500GB          | 38        | 0.34%   |
| Unknown MMC Card  64GB             | 36        | 0.32%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 35        | 0.31%   |
| Seagate ST2000DM008-2FR102 2TB     | 35        | 0.31%   |
| Seagate ST1000DM003-1ER162 1TB     | 35        | 0.31%   |
| Hitachi HDS721050CLA362 500GB      | 33        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1379      | 2261   | 32.79%  |
| WDC                 | 1169      | 1985   | 27.8%   |
| Toshiba             | 588       | 890    | 13.98%  |
| Hitachi             | 325       | 428    | 7.73%   |
| Fujitsu             | 258       | 267    | 6.14%   |
| HGST                | 171       | 270    | 4.07%   |
| Samsung Electronics | 155       | 206    | 3.69%   |
| Maxtor              | 38        | 44     | 0.9%    |
| Unknown             | 31        | 45     | 0.74%   |
| Apple               | 14        | 18     | 0.33%   |
| Hewlett-Packard     | 9         | 23     | 0.21%   |
| ASMT                | 7         | 15     | 0.17%   |
| Intenso             | 6         | 7      | 0.14%   |
| IBM/Hitachi         | 5         | 6      | 0.12%   |
| USB3.0              | 4         | 4      | 0.1%    |
| JMicron Technology  | 4         | 5      | 0.1%    |
| HPE                 | 3         | 5      | 0.07%   |
| SILICONMOTION       | 2         | 2      | 0.05%   |
| Pear 2TB            | 2         | 2      | 0.05%   |
| NETAPP              | 2         | 6      | 0.05%   |
| IET                 | 2         | 2      | 0.05%   |
| ASMedia             | 2         | 2      | 0.05%   |
| USB 3.0             | 1         | 2      | 0.02%   |
| Unknown (CF)        | 1         | 1      | 0.02%   |
| TrueNAS             | 1         | 1      | 0.02%   |
| SABRENT             | 1         | 2      | 0.02%   |
| RSH-319             | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| QNAP                | 1         | 2      | 0.02%   |
| pqi                 | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| NAS                 | 1         | 10     | 0.02%   |
| Maxone              | 1         | 1      | 0.02%   |
| MaxDigital          | 1         | 4      | 0.02%   |
| MARSHAL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |
| LIO-ORG             | 1         | 8      | 0.02%   |
| LaCie               | 1         | 1      | 0.02%   |
| Innodisk            | 1         | 1      | 0.02%   |
| Inateck             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 742       | 1027   | 21.87%  |
| Kingston            | 506       | 639    | 14.91%  |
| Crucial             | 431       | 551    | 12.7%   |
| SanDisk             | 300       | 383    | 8.84%   |
| WDC                 | 162       | 198    | 4.77%   |
| A-DATA Technology   | 151       | 243    | 4.45%   |
| Apple               | 92        | 97     | 2.71%   |
| Intel               | 89        | 118    | 2.62%   |
| China               | 74        | 83     | 2.18%   |
| Micron Technology   | 57        | 63     | 1.68%   |
| Toshiba             | 53        | 68     | 1.56%   |
| OCZ                 | 52        | 64     | 1.53%   |
| Transcend           | 51        | 60     | 1.5%    |
| SK hynix            | 49        | 57     | 1.44%   |
| SPCC                | 43        | 45     | 1.27%   |
| Patriot             | 33        | 39     | 0.97%   |
| PNY                 | 32        | 42     | 0.94%   |
| Intenso             | 32        | 43     | 0.94%   |
| Netac               | 30        | 95     | 0.88%   |
| LITEON              | 28        | 34     | 0.83%   |
| GOODRAM             | 20        | 27     | 0.59%   |
| Corsair             | 19        | 23     | 0.56%   |
| Plextor             | 17        | 22     | 0.5%    |
| LITEONIT            | 17        | 21     | 0.5%    |
| Team                | 16        | 25     | 0.47%   |
| KingDian            | 15        | 16     | 0.44%   |
| Seagate             | 13        | 14     | 0.38%   |
| Hewlett-Packard     | 13        | 14     | 0.38%   |
| Gigabyte Technology | 13        | 15     | 0.38%   |
| Unknown             | 11        | 14     | 0.32%   |
| LDLC                | 11        | 11     | 0.32%   |
| Unknown             | 11        | 12     | 0.32%   |
| KingSpec            | 10        | 11     | 0.29%   |
| Apacer              | 9         | 9      | 0.27%   |
| Mushkin             | 8         | 9      | 0.24%   |
| Lexar               | 8         | 11     | 0.24%   |
| Hajaan              | 7         | 10     | 0.21%   |
| ASMT                | 7         | 8      | 0.21%   |
| BIWIN               | 6         | 6      | 0.18%   |
| Dogfish             | 5         | 7      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3577      | 6551   | 39.02%  |
| SSD     | 3007      | 4426   | 32.8%   |
| NVMe    | 1970      | 2786   | 21.49%  |
| MMC     | 515       | 683    | 5.62%   |
| Unknown | 99        | 150    | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5394      | 10573  | 65.84%  |
| NVMe | 1935      | 2736   | 23.62%  |
| MMC  | 515       | 683    | 6.29%   |
| SAS  | 348       | 604    | 4.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives  | Percent |
|-------------|-----------|---------|---------|
| 0.01-0.5    | 4201      | 6125    | 60.44%  |
| 0.51-1.0    | 1723      | 2633    | 24.79%  |
| 1.01-2.0    | 490       | 884     | 7.05%   |
| 3.01-4.0    | 216       | 504     | 3.11%   |
| 4.01-10.0   | 163       | 455     | 2.34%   |
| 2.01-3.0    | 121       | 219     | 1.74%   |
| 10.01-20.0  | 35        | 153     | 0.5%    |
| 50.01-100.0 | 1         | 4       | 0.01%   |
| 0           | 1         | Unknown | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1649      | 22.23%  |
| Unknown        | 1383      | 18.65%  |
| 251-500        | 1323      | 17.84%  |
| 501-1000       | 890       | 12%     |
| 1001-2000      | 486       | 6.55%   |
| 51-100         | 461       | 6.22%   |
| More than 3000 | 399       | 5.38%   |
| 1-20           | 351       | 4.73%   |
| 21-50          | 284       | 3.83%   |
| 2001-3000      | 191       | 2.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2430      | 31.93%  |
| Unknown        | 1383      | 18.17%  |
| 101-250        | 838       | 11.01%  |
| 21-50          | 811       | 10.66%  |
| 51-100         | 664       | 8.72%   |
| 251-500        | 556       | 7.31%   |
| 501-1000       | 397       | 5.22%   |
| 1001-2000      | 241       | 3.17%   |
| More than 3000 | 180       | 2.36%   |
| 2001-3000      | 94        | 1.24%   |
| 0              | 17        | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 21        | 21     | 2.02%   |
| Fujitsu MHZ2160BH FFS G1 160GB      | 20        | 20     | 1.93%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 17        | 20     | 1.64%   |
| Kingston SV300S37A120G 120GB SSD    | 12        | 12     | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 11        | 14     | 1.06%   |
| Seagate ST9500325AS 500GB           | 10        | 12     | 0.96%   |
| Hitachi HDS721050CLA362 500GB       | 10        | 10     | 0.96%   |
| Toshiba MK1653GSX 160GB             | 9         | 9      | 0.87%   |
| Toshiba MK1655GSXF 160GB            | 8         | 8      | 0.77%   |
| Seagate ST9500420AS 500GB           | 8         | 8      | 0.77%   |
| Seagate ST3500418AS 500GB           | 8         | 11     | 0.77%   |
| Toshiba MQ01ABD100 1TB              | 7         | 7      | 0.67%   |
| Seagate ST31500341AS 1TB            | 7         | 13     | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB      | 7         | 8      | 0.67%   |
| HGST HTS725050A7E630 500GB          | 7         | 8      | 0.67%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 6         | 6      | 0.58%   |
| WDC WD5000AAKX-001CA0 500GB         | 6         | 8      | 0.58%   |
| Toshiba DT01ACA100 1TB              | 6         | 7      | 0.58%   |
| Seagate ST500LT012-9WS142 500GB     | 6         | 7      | 0.58%   |
| Seagate ST3250318AS 250GB           | 6         | 7      | 0.58%   |
| Seagate ST3160815AS 160GB           | 6         | 8      | 0.58%   |
| Seagate ST31000528AS 1TB            | 6         | 6      | 0.58%   |
| Hitachi HTS543216L9SA02 160GB       | 6         | 6      | 0.58%   |
| WDC WD10EADS-00M2B0 1TB             | 5         | 5      | 0.48%   |
| Toshiba DT01ACA050 500GB            | 5         | 6      | 0.48%   |
| Seagate ST31000524AS 1TB            | 5         | 5      | 0.48%   |
| Seagate ST250DM000-1BD141 250GB     | 5         | 5      | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 5      | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB      | 5         | 5      | 0.48%   |
| Samsung Electronics SSD 850 EVO 1TB | 5         | 6      | 0.48%   |
| Hitachi HTS545050B9A300 500GB       | 5         | 5      | 0.48%   |
| Hitachi HTS542512K9SA00 120GB       | 5         | 6      | 0.48%   |
| Hitachi HDS721050DLE630 500GB       | 5         | 5      | 0.48%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 4         | 4      | 0.39%   |
| WDC WD20EFRX-68EUZN0 2TB            | 4         | 15     | 0.39%   |
| WDC WD20EARS-00MVWB0 2TB            | 4         | 4      | 0.39%   |
| WDC WD1600BUDT-63DPZY0 160GB        | 4         | 4      | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB            | 4         | 4      | 0.39%   |
| WDC WD10EARS-00Y5B1 1TB             | 4         | 4      | 0.39%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 4      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 260       | 339    | 25.92%  |
| WDC                 | 217       | 289    | 21.64%  |
| Hitachi             | 107       | 127    | 10.67%  |
| Samsung Electronics | 74        | 83     | 7.38%   |
| Toshiba             | 72        | 81     | 7.18%   |
| Kingston            | 36        | 40     | 3.59%   |
| Fujitsu             | 35        | 36     | 3.49%   |
| Intel               | 28        | 38     | 2.79%   |
| HGST                | 26        | 27     | 2.59%   |
| Crucial             | 22        | 26     | 2.19%   |
| A-DATA Technology   | 20        | 27     | 1.99%   |
| SK hynix            | 16        | 20     | 1.6%    |
| SanDisk             | 15        | 20     | 1.5%    |
| Micron Technology   | 13        | 13     | 1.3%    |
| Maxtor              | 12        | 13     | 1.2%    |
| OCZ                 | 6         | 7      | 0.6%    |
| KingDian            | 5         | 5      | 0.5%    |
| LITEONIT            | 4         | 4      | 0.4%    |
| LITEON              | 4         | 4      | 0.4%    |
| Corsair             | 4         | 4      | 0.4%    |
| China               | 4         | 4      | 0.4%    |
| Unknown             | 2         | 2      | 0.2%    |
| IBM/Hitachi         | 2         | 2      | 0.2%    |
| Hewlett-Packard     | 2         | 3      | 0.2%    |
| Zheino              | 1         | 1      | 0.1%    |
| USB3.0              | 1         | 1      | 0.1%    |
| Team                | 1         | 1      | 0.1%    |
| ShiJi               | 1         | 1      | 0.1%    |
| PNY                 | 1         | 1      | 0.1%    |
| Plextor             | 1         | 2      | 0.1%    |
| Lenovo              | 1         | 1      | 0.1%    |
| KingSpec            | 1         | 1      | 0.1%    |
| JMicron Technology  | 1         | 1      | 0.1%    |
| IBM                 | 1         | 1      | 0.1%    |
| Hypertec            | 1         | 1      | 0.1%    |
| HP Phison           | 1         | 1      | 0.1%    |
| GOODRAM             | 1         | 1      | 0.1%    |
| DGM                 | 1         | 1      | 0.1%    |
| ASMT                | 1         | 2      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 260       | 339    | 33.38%  |
| WDC                 | 211       | 282    | 27.09%  |
| Hitachi             | 107       | 127    | 13.74%  |
| Toshiba             | 71        | 80     | 9.11%   |
| Samsung Electronics | 47        | 52     | 6.03%   |
| Fujitsu             | 35        | 36     | 4.49%   |
| HGST                | 26        | 27     | 3.34%   |
| Maxtor              | 12        | 13     | 1.54%   |
| IBM/Hitachi         | 2         | 2      | 0.26%   |
| Hewlett-Packard     | 2         | 3      | 0.26%   |
| USB3.0              | 1         | 1      | 0.13%   |
| Unknown             | 1         | 1      | 0.13%   |
| JMicron Technology  | 1         | 1      | 0.13%   |
| IBM                 | 1         | 1      | 0.13%   |
| ASMT                | 1         | 2      | 0.13%   |
| ASMedia             | 1         | 1      | 0.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 732       | 968    | 76.49%  |
| SSD  | 198       | 232    | 20.69%  |
| NVMe | 27        | 33     | 2.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 11.11%  |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 5.56%   |
| WDC WD4001FFSX-68JNUN0 4TB                       | 1         | 1      | 5.56%   |
| WDC WD30EZRS-00J99B0 3TB                         | 1         | 1      | 5.56%   |
| Toshiba MK6465GSX 640GB                          | 1         | 1      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 5.56%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 5.56%   |
| Seagate ST500DM005 HD502HJ 500GB                 | 1         | 1      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 5.56%   |
| Seagate ST3500830AS 500GB                        | 1         | 1      | 5.56%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB     | 1         | 1      | 5.56%   |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 5.56%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 5.56%   |
| KingDian S400 120GB                              | 1         | 1      | 5.56%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 5.56%   |
| HGST HDN724040ALE640 4TB                         | 1         | 1      | 5.56%   |
| Crucial CT1000P1SSD8 1TB                         | 1         | 1      | 5.56%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 27.78%  |
| Samsung Electronics | 5         | 9      | 27.78%  |
| WDC                 | 3         | 3      | 16.67%  |
| Toshiba             | 1         | 1      | 5.56%   |
| KingDian            | 1         | 1      | 5.56%   |
| Hitachi             | 1         | 1      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |
| Crucial             | 1         | 1      | 5.56%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4887      | 9180   | 61.29%  |
| Detected | 2139      | 4159   | 26.82%  |
| Malfunc  | 928       | 1233   | 11.64%  |
| Failed   | 18        | 22     | 0.23%   |
| Limited  | 2         | 2      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4401      | 51.49%  |
| AMD                              | 1178      | 13.78%  |
| Samsung Electronics              | 829       | 9.7%    |
| Nvidia                           | 402       | 4.7%    |
| SanDisk                          | 284       | 3.32%   |
| SK hynix                         | 144       | 1.68%   |
| ASMedia Technology               | 137       | 1.6%    |
| Marvell Technology Group         | 121       | 1.42%   |
| Phison Electronics               | 118       | 1.38%   |
| Toshiba America Info Systems     | 95        | 1.11%   |
| Kingston Technology Company      | 89        | 1.04%   |
| Apple                            | 84        | 0.98%   |
| JMicron Technology               | 79        | 0.92%   |
| Silicon Motion                   | 70        | 0.82%   |
| LSI Logic / Symbios Logic        | 69        | 0.81%   |
| ADATA Technology                 | 59        | 0.69%   |
| Micron/Crucial Technology        | 55        | 0.64%   |
| Micron Technology                | 51        | 0.6%    |
| KIOXIA                           | 48        | 0.56%   |
| Broadcom / LSI                   | 39        | 0.46%   |
| VIA Technologies                 | 35        | 0.41%   |
| Silicon Image                    | 18        | 0.21%   |
| Hewlett-Packard                  | 15        | 0.18%   |
| Adaptec                          | 15        | 0.18%   |
| Silicon Integrated Systems [SiS] | 13        | 0.15%   |
| Seagate Technology               | 13        | 0.15%   |
| Realtek Semiconductor            | 12        | 0.14%   |
| Union Memory (Shenzhen)          | 11        | 0.13%   |
| Solid State Storage Technology   | 11        | 0.13%   |
| Lite-On Technology               | 11        | 0.13%   |
| Shenzhen Longsys Electronics     | 6         | 0.07%   |
| Lenovo                           | 5         | 0.06%   |
| 3ware                            | 4         | 0.05%   |
| Integrated Technology Express    | 3         | 0.04%   |
| ULi Electronics                  | 2         | 0.02%   |
| OCZ Technology Group             | 2         | 0.02%   |
| Mylex                            | 2         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.02%   |
| HighPoint Technologies           | 2         | 0.02%   |
| Chelsio Communications           | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 818       | 8.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 487       | 4.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 346       | 3.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 327       | 3.29%   |
| Nvidia MCP79 AHCI Controller                                                            | 315       | 3.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 252       | 2.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 195       | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 173       | 1.74%   |
| AMD 400 Series Chipset SATA Controller                                                  | 170       | 1.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 169       | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 164       | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 163       | 1.64%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 161       | 1.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 158       | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 140       | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 125       | 1.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 123       | 1.24%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 122       | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 118       | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 117       | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 108       | 1.09%   |
| Samsung NVMe SSD Controller 980                                                         | 107       | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 107       | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 97        | 0.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 94        | 0.95%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 90        | 0.91%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 85        | 0.86%   |
| Samsung Electronics SATA controller                                                     | 84        | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 84        | 0.85%   |
| AMD 500 Series Chipset SATA Controller                                                  | 82        | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 79        | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 77        | 0.77%   |
| Apple S1X NVMe Controller                                                               | 77        | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 77        | 0.77%   |
| Intel SATA Controller [RAID mode]                                                       | 76        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 75        | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 72        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 71        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 70        | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 68        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5106      | 58.47%  |
| NVMe | 1948      | 22.31%  |
| IDE  | 1095      | 12.54%  |
| RAID | 475       | 5.44%   |
| SAS  | 76        | 0.87%   |
| SCSI | 33        | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 5587      | 77.78%  |
| AMD               | 1401      | 19.5%   |
| ARM               | 167       | 2.32%   |
| CentaurHauls      | 7         | 0.1%    |
| Unknown           | 7         | 0.1%    |
| sifive,bullet0    | 3         | 0.04%   |
| Phytium           | 3         | 0.04%   |
| CHRP IBM,9131-52A | 2         | 0.03%   |
| sifive,u74-mc     | 1         | 0.01%   |
| QUALCOMM          | 1         | 0.01%   |
| PowerNV FP5466G2  | 1         | 0.01%   |
| HISILICON         | 1         | 0.01%   |
| CHRP IBM,8233-E8B | 1         | 0.01%   |
| AppliedMicro      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 305       | 4.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 169       | 2.35%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 144       | 2%      |
| ARM Processor                                 | 117       | 1.63%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 90        | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 72        | 1%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 71        | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 68        | 0.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 67        | 0.93%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 62        | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 61        | 0.85%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 60        | 0.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 54        | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 51        | 0.71%   |
| AMD Ryzen 5 3600 6-Core Processor             | 51        | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 48        | 0.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 48        | 0.67%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 46        | 0.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 42        | 0.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 41        | 0.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 41        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 40        | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 36        | 0.5%    |
| Intel Pentium CPU G3420 @ 3.20GHz             | 35        | 0.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 33        | 0.46%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 31        | 0.43%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 31        | 0.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 29        | 0.4%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 29        | 0.4%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.4%    |
| Intel Atom CPU N270 @ 1.60GHz                 | 29        | 0.4%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 27        | 0.38%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 27        | 0.38%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 27        | 0.38%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 27        | 0.38%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 27        | 0.38%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 26        | 0.36%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 26        | 0.36%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 0.36%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 26        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1480      | 20.6%   |
| Intel Core i7           | 1044      | 14.53%  |
| Intel Core 2 Duo        | 587       | 8.17%   |
| Other                   | 567       | 7.89%   |
| Intel Core i3           | 525       | 7.31%   |
| Intel Celeron           | 442       | 6.15%   |
| AMD Ryzen 5             | 337       | 4.69%   |
| Intel Xeon              | 276       | 3.84%   |
| Intel Pentium           | 242       | 3.37%   |
| AMD Ryzen 7             | 230       | 3.2%    |
| Intel Atom              | 157       | 2.19%   |
| Intel Core 2            | 95        | 1.32%   |
| AMD FX                  | 95        | 1.32%   |
| AMD Ryzen 9             | 86        | 1.2%    |
| Intel Pentium Dual-Core | 80        | 1.11%   |
| AMD Ryzen 3             | 70        | 0.97%   |
| Intel Core 2 Quad       | 51        | 0.71%   |
| AMD A8                  | 41        | 0.57%   |
| AMD A6                  | 37        | 0.52%   |
| AMD Ryzen 7 PRO         | 35        | 0.49%   |
| Intel Core i9           | 33        | 0.46%   |
| Intel Pentium Dual      | 32        | 0.45%   |
| AMD A10                 | 32        | 0.45%   |
| AMD Athlon 64 X2        | 29        | 0.4%    |
| Intel Pentium M         | 28        | 0.39%   |
| Intel Pentium 4         | 28        | 0.39%   |
| AMD Athlon              | 28        | 0.39%   |
| AMD Ryzen Threadripper  | 27        | 0.38%   |
| AMD Athlon II X2        | 27        | 0.38%   |
| AMD A4                  | 27        | 0.38%   |
| AMD Phenom II X4        | 25        | 0.35%   |
| Intel Pentium Gold      | 23        | 0.32%   |
| AMD Ryzen 5 PRO         | 22        | 0.31%   |
| AMD E1                  | 21        | 0.29%   |
| Intel Genuine           | 20        | 0.28%   |
| AMD E                   | 17        | 0.24%   |
| Intel Pentium Silver    | 15        | 0.21%   |
| ARM Allwinner           | 15        | 0.21%   |
| AMD Sempron             | 13        | 0.18%   |
| AMD Phenom II X6        | 12        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3163      | 43.97%  |
| 4       | 2429      | 33.76%  |
| 6       | 602       | 8.37%   |
| 8       | 439       | 6.1%    |
| 1       | 270       | 3.75%   |
| 12      | 82        | 1.14%   |
| 16      | 74        | 1.03%   |
| 3       | 33        | 0.46%   |
| 10      | 24        | 0.33%   |
| 14      | 16        | 0.22%   |
| 32      | 13        | 0.18%   |
| 24      | 13        | 0.18%   |
| 20      | 11        | 0.15%   |
| Unknown | 11        | 0.15%   |
| 44      | 3         | 0.04%   |
| 28      | 3         | 0.04%   |
| 64      | 2         | 0.03%   |
| 48      | 2         | 0.03%   |
| 18      | 2         | 0.03%   |
| 80      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7045      | 98.01%  |
| 2       | 128       | 1.78%   |
| Unknown | 11        | 0.15%   |
| 4       | 4         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4266      | 59.36%  |
| 1       | 2907      | 40.45%  |
| Unknown | 11        | 0.15%   |
| 4       | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6838      | 95.08%  |
| Unknown        | 212       | 2.95%   |
| 32-bit         | 127       | 1.77%   |
| 64-bit         | 15        | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1726      | 23.44%  |
| 0x1067a    | 531       | 7.21%   |
| 0x206a7    | 323       | 4.39%   |
| 0x306c3    | 317       | 4.31%   |
| 0x306a9    | 302       | 4.1%    |
| 0x806c1    | 248       | 3.37%   |
| 0x306d4    | 239       | 3.25%   |
| 0x906ea    | 177       | 2.4%    |
| 0x806ec    | 171       | 2.32%   |
| 0x506e3    | 138       | 1.87%   |
| 0x806e9    | 130       | 1.77%   |
| 0x30678    | 126       | 1.71%   |
| 0x806ea    | 123       | 1.67%   |
| 0x40651    | 99        | 1.34%   |
| 0x406e3    | 96        | 1.3%    |
| 0x08701021 | 93        | 1.26%   |
| 0x906e9    | 91        | 1.24%   |
| 0x08108109 | 85        | 1.15%   |
| 0x6f6      | 76        | 1.03%   |
| 0xa0653    | 70        | 0.95%   |
| 0x20655    | 68        | 0.92%   |
| 0x406c4    | 67        | 0.91%   |
| 0x906eb    | 66        | 0.9%    |
| 0x10676    | 59        | 0.8%    |
| 0x6fd      | 56        | 0.76%   |
| 0x08600106 | 55        | 0.75%   |
| 0xa0655    | 51        | 0.69%   |
| 0xa0652    | 51        | 0.69%   |
| 0x0a50000c | 51        | 0.69%   |
| 0x0800820d | 50        | 0.68%   |
| 0x08108102 | 45        | 0.61%   |
| 0x706e5    | 42        | 0.57%   |
| 0x706a8    | 41        | 0.56%   |
| 0x506c9    | 41        | 0.56%   |
| 0x206d7    | 40        | 0.54%   |
| 0x0a201016 | 39        | 0.53%   |
| 0x906ed    | 38        | 0.52%   |
| 0x106c2    | 37        | 0.5%    |
| 0x6fb      | 35        | 0.48%   |
| 0x08608103 | 35        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1079      | 15.01%  |
| Penryn           | 665       | 9.25%   |
| Haswell          | 581       | 8.08%   |
| SandyBridge      | 469       | 6.52%   |
| IvyBridge        | 436       | 6.06%   |
| Skylake          | 343       | 4.77%   |
| Broadwell        | 287       | 3.99%   |
| TigerLake        | 284       | 3.95%   |
| Unknown          | 280       | 3.89%   |
| Zen 2            | 276       | 3.84%   |
| Silvermont       | 276       | 3.84%   |
| Zen+             | 246       | 3.42%   |
| Core             | 237       | 3.3%    |
| CometLake        | 201       | 2.8%    |
| Westmere         | 175       | 2.43%   |
| Zen 3            | 142       | 1.98%   |
| Zen              | 133       | 1.85%   |
| K10              | 112       | 1.56%   |
| Piledriver       | 102       | 1.42%   |
| Bonnell          | 93        | 1.29%   |
| Excavator        | 88        | 1.22%   |
| Goldmont plus    | 80        | 1.11%   |
| IceLake          | 70        | 0.97%   |
| Nehalem          | 66        | 0.92%   |
| K8 Hammer        | 64        | 0.89%   |
| Goldmont         | 62        | 0.86%   |
| P6               | 54        | 0.75%   |
| NetBurst         | 47        | 0.65%   |
| Bobcat           | 42        | 0.58%   |
| Steamroller      | 36        | 0.5%    |
| Jaguar           | 31        | 0.43%   |
| Alderlake Hybrid | 30        | 0.42%   |
| Puma             | 29        | 0.4%    |
| Bulldozer        | 26        | 0.36%   |
| K10 Llano        | 20        | 0.28%   |
| Tremont          | 16        | 0.22%   |
| K6               | 6         | 0.08%   |
| K8 & K10 hybrid  | 5         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4166      | 52.55%  |
| Nvidia                           | 2057      | 25.95%  |
| AMD                              | 1502      | 18.95%  |
| Matrox Electronics Systems       | 104       | 1.31%   |
| ASPEED Technology                | 73        | 0.92%   |
| VIA Technologies                 | 11        | 0.14%   |
| Silicon Integrated Systems [SiS] | 8         | 0.1%    |
| S3 Graphics                      | 2         | 0.03%   |
| Silicon Motion                   | 1         | 0.01%   |
| Neomagic                         | 1         | 0.01%   |
| Loongson Technology              | 1         | 0.01%   |
| Huawei Technologies              | 1         | 0.01%   |
| ATI Technologies                 | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 306       | 3.72%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 304       | 3.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 267       | 3.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 233       | 2.84%   |
| Intel UHD Graphics 620                                                                   | 176       | 2.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 166       | 2.02%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 166       | 2.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 157       | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 155       | 1.89%   |
| Intel HD Graphics 6000                                                                   | 149       | 1.81%   |
| Intel HD Graphics 620                                                                    | 141       | 1.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 136       | 1.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 131       | 1.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 130       | 1.58%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 118       | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 116       | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 114       | 1.39%   |
| AMD Renoir                                                                               | 111       | 1.35%   |
| Intel HD Graphics 5500                                                                   | 106       | 1.29%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 105       | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 92        | 1.12%   |
| Intel HD Graphics 530                                                                    | 85        | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 82        | 1%      |
| Intel HD Graphics 630                                                                    | 82        | 1%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 82        | 1%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 75        | 0.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 74        | 0.9%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 74        | 0.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 73        | 0.89%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 73        | 0.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 71        | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 70        | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 70        | 0.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 70        | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 65        | 0.79%   |
| AMD Cezanne                                                                              | 60        | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 59        | 0.72%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 58        | 0.71%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 57        | 0.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 57        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 3336      | 46.22%  |
| 1 x Nvidia                        | 1358      | 18.81%  |
| 1 x AMD                           | 1220      | 16.9%   |
| Intel + Nvidia                    | 617       | 8.55%   |
| Other                             | 197       | 2.73%   |
| Intel + AMD                       | 140       | 1.94%   |
| 1 x Matrox                        | 98        | 1.36%   |
| 2 x AMD                           | 75        | 1.04%   |
| 1 x ASPEED                        | 60        | 0.83%   |
| AMD + Nvidia                      | 56        | 0.78%   |
| 1 x VIA                           | 11        | 0.15%   |
| 2 x Nvidia                        | 10        | 0.14%   |
| 1 x SiS                           | 8         | 0.11%   |
| Nvidia + ASPEED                   | 7         | 0.1%    |
| Intel + 2 x Nvidia                | 5         | 0.07%   |
| AMD + ASPEED                      | 5         | 0.07%   |
| Nvidia + Matrox                   | 4         | 0.06%   |
| 1 x S3 Graphics                   | 2         | 0.03%   |
| AMD + Matrox                      | 2         | 0.03%   |
| 3 x AMD                           | 1         | 0.01%   |
| 2 x Loongson Technology           | 1         | 0.01%   |
| 2 x Intel                         | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.01%   |
| 1 x Silicon Motion                | 1         | 0.01%   |
| Nvidia + Huawei Technologies      | 1         | 0.01%   |
| 1 x Neomagic                      | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5306      | 73.24%  |
| Unknown     | 1155      | 15.94%  |
| Proprietary | 784       | 10.82%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5047      | 69.19%  |
| 0.01-0.5   | 808       | 11.08%  |
| 1.01-2.0   | 488       | 6.69%   |
| 0.51-1.0   | 330       | 4.52%   |
| 3.01-4.0   | 281       | 3.85%   |
| 7.01-8.0   | 172       | 2.36%   |
| 5.01-6.0   | 96        | 1.32%   |
| 2.01-3.0   | 33        | 0.45%   |
| 8.01-16.0  | 33        | 0.45%   |
| 16.01-24.0 | 5         | 0.07%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 840       | 12.34%  |
| Samsung Electronics     | 736       | 10.81%  |
| Apple                   | 607       | 8.92%   |
| BOE                     | 551       | 8.1%    |
| LG Display              | 502       | 7.38%   |
| Chimei Innolux          | 457       | 6.71%   |
| Dell                    | 408       | 5.99%   |
| Goldstar                | 324       | 4.76%   |
| Hewlett-Packard         | 206       | 3.03%   |
| BenQ                    | 189       | 2.78%   |
| Acer                    | 175       | 2.57%   |
| AOC                     | 160       | 2.35%   |
| Philips                 | 152       | 2.23%   |
| Lenovo                  | 146       | 2.15%   |
| Ancor Communications    | 135       | 1.98%   |
| Sharp                   | 93        | 1.37%   |
| Iiyama                  | 89        | 1.31%   |
| ViewSonic               | 77        | 1.13%   |
| Chi Mei Optoelectronics | 69        | 1.01%   |
| Unknown                 | 66        | 0.97%   |
| InfoVision              | 53        | 0.78%   |
| Eizo                    | 46        | 0.68%   |
| PANDA                   | 41        | 0.6%    |
| Sony                    | 37        | 0.54%   |
| HannStar                | 37        | 0.54%   |
| ASUSTek Computer        | 37        | 0.54%   |
| NEC Computers           | 31        | 0.46%   |
| LG Electronics          | 31        | 0.46%   |
| LG Philips              | 24        | 0.35%   |
| CSO                     | 21        | 0.31%   |
| Fujitsu Siemens         | 17        | 0.25%   |
| Panasonic               | 15        | 0.22%   |
| Medion                  | 15        | 0.22%   |
| CPT                     | 14        | 0.21%   |
| Vizio                   | 13        | 0.19%   |
| Toshiba                 | 12        | 0.18%   |
| Hitachi                 | 11        | 0.16%   |
| Vestel Elektronik       | 10        | 0.15%   |
| MSI                     | 10        | 0.15%   |
| Unknown                 | 9         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 200       | 2.85%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 151       | 2.15%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch       | 110       | 1.57%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 52        | 0.74%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 43        | 0.61%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 40        | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 38        | 0.54%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 37        | 0.53%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 35        | 0.5%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 32        | 0.46%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 31        | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 30        | 0.43%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 28        | 0.4%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 24        | 0.34%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 23        | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 23        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 22        | 0.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 22        | 0.31%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 21        | 0.3%    |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 21        | 0.3%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 19        | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 19        | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 16        | 0.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 16        | 0.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 16        | 0.23%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 16        | 0.23%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch               | 14        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 14        | 0.2%    |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 14        | 0.2%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 13        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 13        | 0.19%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 13        | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch    | 12        | 0.17%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 12        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 12        | 0.17%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 12        | 0.17%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 12        | 0.17%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 12        | 0.17%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 11        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2612      | 39.87%  |
| 1366x768 (WXGA)    | 1177      | 17.97%  |
| 1280x800 (WXGA)    | 500       | 7.63%   |
| 3840x2160 (4K)     | 351       | 5.36%   |
| 1280x1024 (SXGA)   | 259       | 3.95%   |
| 2560x1440 (QHD)    | 255       | 3.89%   |
| 1600x900 (HD+)     | 229       | 3.5%    |
| 1440x900 (WXGA+)   | 190       | 2.9%    |
| 1920x1200 (WUXGA)  | 180       | 2.75%   |
| 1680x1050 (WSXGA+) | 163       | 2.49%   |
| Unknown            | 81        | 1.24%   |
| 2560x1080          | 58        | 0.89%   |
| 1024x600           | 55        | 0.84%   |
| 1024x768 (XGA)     | 46        | 0.7%    |
| 3440x1440          | 43        | 0.66%   |
| 1360x768           | 43        | 0.66%   |
| 2560x1600          | 37        | 0.56%   |
| 2288x1287          | 33        | 0.5%    |
| 1600x1200          | 31        | 0.47%   |
| 3840x1080          | 28        | 0.43%   |
| 1920x540           | 19        | 0.29%   |
| 2880x1800          | 14        | 0.21%   |
| 3840x2400          | 13        | 0.2%    |
| 2160x1440          | 10        | 0.15%   |
| 3200x1800 (QHD+)   | 9         | 0.14%   |
| 1280x720 (HD)      | 8         | 0.12%   |
| 4480x1440          | 7         | 0.11%   |
| 2736x1824          | 7         | 0.11%   |
| 3200x1080          | 6         | 0.09%   |
| 3840x1600          | 5         | 0.08%   |
| 1400x1050          | 5         | 0.08%   |
| 7680x2160          | 4         | 0.06%   |
| 5760x2160          | 4         | 0.06%   |
| 5760x1080          | 4         | 0.06%   |
| 1920x1280          | 4         | 0.06%   |
| 3840x1100          | 3         | 0.05%   |
| 3360x1050          | 3         | 0.05%   |
| 2256x1504          | 3         | 0.05%   |
| 2240x1400          | 3         | 0.05%   |
| 2048x1152          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1291      | 19.04%  |
| 13      | 1137      | 16.77%  |
| 14      | 534       | 7.88%   |
| 24      | 491       | 7.24%   |
| 27      | 433       | 6.39%   |
| 23      | 405       | 5.97%   |
| 21      | 334       | 4.93%   |
| 17      | 326       | 4.81%   |
| Unknown | 271       | 4%      |
| 11      | 251       | 3.7%    |
| 19      | 195       | 2.88%   |
| 12      | 168       | 2.48%   |
| 18      | 132       | 1.95%   |
| 22      | 108       | 1.59%   |
| 31      | 102       | 1.5%    |
| 20      | 84        | 1.24%   |
| 34      | 79        | 1.17%   |
| 10      | 57        | 0.84%   |
| 25      | 41        | 0.6%    |
| 84      | 39        | 0.58%   |
| 72      | 34        | 0.5%    |
| 142     | 32        | 0.47%   |
| 16      | 26        | 0.38%   |
| 54      | 23        | 0.34%   |
| 32      | 23        | 0.34%   |
| 29      | 17        | 0.25%   |
| 40      | 16        | 0.24%   |
| 26      | 14        | 0.21%   |
| 52      | 13        | 0.19%   |
| 28      | 13        | 0.19%   |
| 48      | 11        | 0.16%   |
| 46      | 9         | 0.13%   |
| 65      | 7         | 0.1%    |
| 39      | 7         | 0.1%    |
| 43      | 6         | 0.09%   |
| 33      | 6         | 0.09%   |
| 8       | 6         | 0.09%   |
| 49      | 5         | 0.07%   |
| 37      | 5         | 0.07%   |
| 55      | 4         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2220      | 33.31%  |
| 201-300        | 1307      | 19.61%  |
| 501-600        | 1236      | 18.54%  |
| 401-500        | 720       | 10.8%   |
| 351-400        | 373       | 5.6%    |
| Unknown        | 271       | 4.07%   |
| 601-700        | 192       | 2.88%   |
| 701-800        | 106       | 1.59%   |
| 1001-1500      | 79        | 1.19%   |
| 1501-2000      | 75        | 1.13%   |
| 801-900        | 35        | 0.53%   |
| More than 2000 | 32        | 0.48%   |
| 901-1000       | 11        | 0.17%   |
| 101-200        | 8         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4298      | 69.67%  |
| 16/10   | 1095      | 17.75%  |
| 5/4     | 238       | 3.86%   |
| Unknown | 218       | 3.53%   |
| 4/3     | 101       | 1.64%   |
| 21/9    | 95        | 1.54%   |
| 3/2     | 55        | 0.89%   |
| 1.00    | 34        | 0.55%   |
| 32/9    | 12        | 0.19%   |
| 6/5     | 10        | 0.16%   |
| 2.65    | 4         | 0.06%   |
| 3.40    | 3         | 0.05%   |
| 1.96    | 2         | 0.03%   |
| 3.73    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1282      | 19.07%  |
| 81-90          | 1265      | 18.82%  |
| 201-250        | 1051      | 15.64%  |
| 301-350        | 440       | 6.55%   |
| 71-80          | 411       | 6.12%   |
| 151-200        | 382       | 5.68%   |
| Unknown        | 271       | 4.03%   |
| 51-60          | 254       | 3.78%   |
| 351-500        | 233       | 3.47%   |
| 141-150        | 220       | 3.27%   |
| 251-300        | 218       | 3.24%   |
| 121-130        | 179       | 2.66%   |
| More than 1000 | 162       | 2.41%   |
| 61-70          | 154       | 2.29%   |
| 501-1000       | 65        | 0.97%   |
| 41-50          | 57        | 0.85%   |
| 131-140        | 32        | 0.48%   |
| 111-120        | 21        | 0.31%   |
| 91-100         | 16        | 0.24%   |
| 1-40           | 8         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1998      | 30.56%  |
| 121-160       | 1789      | 27.36%  |
| 101-120       | 1786      | 27.32%  |
| 161-240       | 449       | 6.87%   |
| Unknown       | 272       | 4.16%   |
| 1-50          | 148       | 2.26%   |
| More than 240 | 96        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4980      | 68.02%  |
| 0     | 1268      | 17.32%  |
| 2     | 961       | 13.13%  |
| 3     | 106       | 1.45%   |
| 4     | 5         | 0.07%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3407      | 32.7%   |
| Intel                             | 3253      | 31.22%  |
| Qualcomm Atheros                  | 1069      | 10.26%  |
| Broadcom                          | 796       | 7.64%   |
| Nvidia                            | 386       | 3.71%   |
| Broadcom Limited                  | 262       | 2.51%   |
| Marvell Technology Group          | 180       | 1.73%   |
| Ralink Technology                 | 92        | 0.88%   |
| Ralink                            | 85        | 0.82%   |
| TP-Link                           | 75        | 0.72%   |
| ASIX Electronics                  | 53        | 0.51%   |
| MediaTek                          | 50        | 0.48%   |
| Samsung Electronics               | 40        | 0.38%   |
| Dell                              | 32        | 0.31%   |
| Lenovo                            | 29        | 0.28%   |
| JMicron Technology                | 27        | 0.26%   |
| Huawei Technologies               | 26        | 0.25%   |
| Qualcomm Atheros Communications   | 25        | 0.24%   |
| Microchip Technology              | 25        | 0.24%   |
| Sierra Wireless                   | 24        | 0.23%   |
| D-Link System                     | 23        | 0.22%   |
| Microsoft                         | 20        | 0.19%   |
| Aquantia                          | 20        | 0.19%   |
| Mellanox Technologies             | 18        | 0.17%   |
| ASUSTek Computer                  | 18        | 0.17%   |
| Qualcomm                          | 17        | 0.16%   |
| Ericsson Business Mobile Networks | 17        | 0.16%   |
| Xiaomi                            | 16        | 0.15%   |
| DisplayLink                       | 16        | 0.15%   |
| D-Link                            | 15        | 0.14%   |
| VIA Technologies                  | 14        | 0.13%   |
| Silicon Integrated Systems [SiS]  | 13        | 0.12%   |
| NetGear                           | 13        | 0.12%   |
| FIBOCOM                           | 12        | 0.12%   |
| Hewlett-Packard                   | 11        | 0.11%   |
| Edimax Technology                 | 10        | 0.1%    |
| ICS Advent                        | 9         | 0.09%   |
| IBM                               | 9         | 0.09%   |
| 3Com                              | 9         | 0.09%   |
| Motorola PCS                      | 8         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 2445      | 20.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 385       | 3.17%   |
| Nvidia MCP79 Ethernet                                                                 | 316       | 2.6%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 311       | 2.56%   |
| Intel Wi-Fi 6 AX200                                                                   | 237       | 1.95%   |
| Intel Wi-Fi 6 AX201                                                                   | 232       | 1.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 230       | 1.89%   |
| Intel Wireless 7260                                                                   | 187       | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 186       | 1.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 176       | 1.45%   |
| Intel Wireless 8265 / 8275                                                            | 176       | 1.45%   |
| Intel I211 Gigabit Network Connection                                                 | 159       | 1.31%   |
| Intel Wireless 7265                                                                   | 156       | 1.28%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 153       | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 135       | 1.11%   |
| Intel Ethernet Connection (13) I219-V                                                 | 130       | 1.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 115       | 0.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 108       | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 102       | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 102       | 0.84%   |
| Intel Wireless 8260                                                                   | 101       | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 101       | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 101       | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 99        | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 97        | 0.8%    |
| Intel Wireless 3165                                                                   | 89        | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 86        | 0.71%   |
| Intel Ethernet Connection (2) I219-V                                                  | 84        | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 83        | 0.68%   |
| Intel I210 Gigabit Network Connection                                                 | 82        | 0.67%   |
| Intel 82579V Gigabit Network Connection                                               | 74        | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 71        | 0.58%   |
| Intel Ethernet Connection I217-LM                                                     | 70        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 69        | 0.57%   |
| Intel 82574L Gigabit Network Connection                                               | 66        | 0.54%   |
| Intel Wireless-AC 9260                                                                | 65        | 0.53%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 62        | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 61        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                                  | 60        | 0.49%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 58        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2294      | 45.34%  |
| Qualcomm Atheros                  | 872       | 17.24%  |
| Realtek Semiconductor             | 632       | 12.49%  |
| Broadcom                          | 575       | 11.37%  |
| Broadcom Limited                  | 201       | 3.97%   |
| Ralink Technology                 | 92        | 1.82%   |
| Ralink                            | 85        | 1.68%   |
| TP-Link                           | 53        | 1.05%   |
| MediaTek                          | 43        | 0.85%   |
| Qualcomm Atheros Communications   | 25        | 0.49%   |
| Sierra Wireless                   | 24        | 0.47%   |
| ASUSTek Computer                  | 18        | 0.36%   |
| Dell                              | 15        | 0.3%    |
| NetGear                           | 13        | 0.26%   |
| Microsoft                         | 13        | 0.26%   |
| D-Link System                     | 13        | 0.26%   |
| D-Link                            | 13        | 0.26%   |
| FIBOCOM                           | 11        | 0.22%   |
| Edimax Technology                 | 10        | 0.2%    |
| Marvell Technology Group          | 9         | 0.18%   |
| Belkin Components                 | 6         | 0.12%   |
| Qualcomm                          | 5         | 0.1%    |
| IMC Networks                      | 5         | 0.1%    |
| Wilocity                          | 4         | 0.08%   |
| Gemtek                            | 4         | 0.08%   |
| Linksys                           | 3         | 0.06%   |
| Hewlett-Packard                   | 3         | 0.06%   |
| Micro Star International          | 2         | 0.04%   |
| Ericsson Business Mobile Networks | 2         | 0.04%   |
| AVM                               | 2         | 0.04%   |
| 3Com                              | 2         | 0.04%   |
| ZyXEL Communications              | 1         | 0.02%   |
| Z-Com                             | 1         | 0.02%   |
| TRENDnet                          | 1         | 0.02%   |
| Sitecom Europe                    | 1         | 0.02%   |
| Quectel Wireless Solutions        | 1         | 0.02%   |
| PLANEX                            | 1         | 0.02%   |
| Fiberline                         | 1         | 0.02%   |
| Cinterion                         | 1         | 0.02%   |
| BUFFALO                           | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 311       | 6.11%   |
| Intel Wi-Fi 6 AX200                                                                   | 237       | 4.66%   |
| Intel Wi-Fi 6 AX201                                                                   | 232       | 4.56%   |
| Intel Wireless 7260                                                                   | 187       | 3.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 186       | 3.66%   |
| Intel Wireless 8265 / 8275                                                            | 176       | 3.46%   |
| Intel Wireless 7265                                                                   | 156       | 3.07%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 153       | 3.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 135       | 2.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 115       | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 108       | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 102       | 2.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 102       | 2.01%   |
| Intel Wireless 8260                                                                   | 101       | 1.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 101       | 1.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 101       | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 99        | 1.95%   |
| Intel Wireless 3165                                                                   | 89        | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 86        | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 83        | 1.63%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 71        | 1.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 69        | 1.36%   |
| Intel Wireless-AC 9260                                                                | 65        | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 61        | 1.2%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 58        | 1.14%   |
| Realtek 802.11ac NIC                                                                  | 49        | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 49        | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 46        | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 45        | 0.88%   |
| Intel Wireless 3160                                                                   | 41        | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 41        | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 39        | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 39        | 0.77%   |
| Ralink MT7601U Wireless Adapter                                                       | 34        | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 34        | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 34        | 0.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 33        | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 32        | 0.63%   |
| Intel Centrino Ultimate-N 6300                                                        | 32        | 0.63%   |
| Intel Centrino Advanced-N 6200                                                        | 30        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3166      | 47.26%  |
| Intel                             | 1890      | 28.21%  |
| Nvidia                            | 386       | 5.76%   |
| Qualcomm Atheros                  | 295       | 4.4%    |
| Broadcom                          | 267       | 3.99%   |
| Marvell Technology Group          | 171       | 2.55%   |
| Broadcom Limited                  | 62        | 0.93%   |
| ASIX Electronics                  | 53        | 0.79%   |
| Samsung Electronics               | 40        | 0.6%    |
| Lenovo                            | 29        | 0.43%   |
| JMicron Technology                | 27        | 0.4%    |
| Microchip Technology              | 24        | 0.36%   |
| TP-Link                           | 22        | 0.33%   |
| Aquantia                          | 20        | 0.3%    |
| Huawei Technologies               | 18        | 0.27%   |
| Xiaomi                            | 16        | 0.24%   |
| Mellanox Technologies             | 16        | 0.24%   |
| DisplayLink                       | 16        | 0.24%   |
| VIA Technologies                  | 14        | 0.21%   |
| Silicon Integrated Systems [SiS]  | 13        | 0.19%   |
| Qualcomm                          | 10        | 0.15%   |
| D-Link System                     | 10        | 0.15%   |
| ICS Advent                        | 9         | 0.13%   |
| IBM                               | 9         | 0.13%   |
| Cypress Semiconductor             | 8         | 0.12%   |
| American Megatrends               | 8         | 0.12%   |
| Motorola PCS                      | 7         | 0.1%    |
| Microsoft                         | 7         | 0.1%    |
| 3Com                              | 7         | 0.1%    |
| MediaTek                          | 6         | 0.09%   |
| Attansic Technology               | 6         | 0.09%   |
| Apple                             | 6         | 0.09%   |
| Sundance Technology Inc / IC Plus | 5         | 0.07%   |
| Standard Microsystems             | 5         | 0.07%   |
| NetXen Incorporated               | 4         | 0.06%   |
| Google                            | 4         | 0.06%   |
| Spreadtrum Communications         | 3         | 0.04%   |
| QLogic                            | 3         | 0.04%   |
| OPPO Electronics                  | 3         | 0.04%   |
| LG Electronics                    | 3         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2445      | 35.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 385       | 5.58%   |
| Nvidia MCP79 Ethernet                                             | 316       | 4.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 230       | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 176       | 2.55%   |
| Intel I211 Gigabit Network Connection                             | 159       | 2.3%    |
| Intel Ethernet Connection (13) I219-V                             | 130       | 1.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 97        | 1.41%   |
| Intel Ethernet Connection (2) I219-V                              | 84        | 1.22%   |
| Intel I210 Gigabit Network Connection                             | 82        | 1.19%   |
| Intel 82579V Gigabit Network Connection                           | 74        | 1.07%   |
| Intel Ethernet Connection I217-LM                                 | 70        | 1.01%   |
| Intel 82574L Gigabit Network Connection                           | 66        | 0.96%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 62        | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 60        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 52        | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 52        | 0.75%   |
| Intel Ethernet Connection (6) I219-V                              | 52        | 0.75%   |
| Intel Ethernet Connection (7) I219-V                              | 46        | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 45        | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 43        | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 42        | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 42        | 0.61%   |
| Intel I350 Gigabit Network Connection                             | 41        | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 41        | 0.59%   |
| Nvidia MCP61 Ethernet                                             | 38        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 38        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                          | 38        | 0.55%   |
| Intel Ethernet Connection (2) I218-V                              | 37        | 0.54%   |
| Intel Ethernet Connection (14) I219-V                             | 36        | 0.52%   |
| Intel Ethernet Controller I225-V                                  | 35        | 0.51%   |
| Intel Ethernet Connection (10) I219-V                             | 35        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 35        | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 30        | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 30        | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 29        | 0.42%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 29        | 0.42%   |
| Intel 82567LM Gigabit Network Connection                          | 29        | 0.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 27        | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 26        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6254      | 55.42%  |
| WiFi     | 4862      | 43.09%  |
| Modem    | 149       | 1.32%   |
| Unknown  | 19        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3704      | 51.12%  |
| WiFi     | 3539      | 48.84%  |
| Unknown  | 2         | 0.03%   |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3771      | 52.36%  |
| 1     | 2890      | 40.13%  |
| 0     | 242       | 3.36%   |
| 3     | 180       | 2.5%    |
| 4     | 75        | 1.04%   |
| 6     | 19        | 0.26%   |
| 5     | 10        | 0.14%   |
| 8     | 7         | 0.1%    |
| 10    | 2         | 0.03%   |
| 21    | 1         | 0.01%   |
| 14    | 1         | 0.01%   |
| 13    | 1         | 0.01%   |
| 12    | 1         | 0.01%   |
| 9     | 1         | 0.01%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 6286      | 86.49%  |
| Yes     | 981       | 13.5%   |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1839      | 45.66%  |
| Apple                           | 607       | 15.07%  |
| Qualcomm Atheros Communications | 321       | 7.97%   |
| Realtek Semiconductor           | 307       | 7.62%   |
| Broadcom                        | 196       | 4.87%   |
| Cambridge Silicon Radio         | 185       | 4.59%   |
| IMC Networks                    | 121       | 3%      |
| Lite-On Technology              | 110       | 2.73%   |
| ASUSTek Computer                | 75        | 1.86%   |
| Foxconn / Hon Hai               | 67        | 1.66%   |
| Dell                            | 51        | 1.27%   |
| Hewlett-Packard                 | 37        | 0.92%   |
| Toshiba                         | 20        | 0.5%    |
| Ralink                          | 18        | 0.45%   |
| Realtek                         | 17        | 0.42%   |
| MediaTek                        | 9         | 0.22%   |
| Foxconn International           | 7         | 0.17%   |
| Alps Electric                   | 5         | 0.12%   |
| Ralink Technology               | 4         | 0.1%    |
| Belkin Components               | 4         | 0.1%    |
| Taiyo Yuden                     | 3         | 0.07%   |
| Marvell Semiconductor           | 3         | 0.07%   |
| Edimax Technology               | 3         | 0.07%   |
| Unknown                         | 2         | 0.05%   |
| Qcom                            | 2         | 0.05%   |
| Micro Star International        | 2         | 0.05%   |
| Integrated System Solution      | 2         | 0.05%   |
| USI                             | 1         | 0.02%   |
| TP-Link                         | 1         | 0.02%   |
| Sitecom Europe                  | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Kensington                      | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Com One                         | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 709       | 17.58%  |
| Intel AX201 Bluetooth                               | 392       | 9.72%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 313       | 7.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 254       | 6.3%    |
| Intel AX200 Bluetooth                               | 230       | 5.7%    |
| Realtek Bluetooth Radio                             | 197       | 4.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 185       | 4.59%   |
| Qualcomm Atheros  Bluetooth Device                  | 179       | 4.44%   |
| Apple Bluetooth USB Host Controller                 | 169       | 4.19%   |
| Realtek  Bluetooth 4.2 Adapter                      | 81        | 2.01%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 79        | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                    | 67        | 1.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 62        | 1.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 46        | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 43        | 1.07%   |
| IMC Networks Bluetooth Device                       | 41        | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 38        | 0.94%   |
| IMC Networks Bluetooth Radio                        | 37        | 0.92%   |
| Intel AX210 Bluetooth                               | 36        | 0.89%   |
| Broadcom BCM2045B (BDC-2.1)                         | 35        | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 34        | 0.84%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 33        | 0.82%   |
| Apple Bluetooth Host Controller                     | 33        | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 29        | 0.72%   |
| Lite-On Bluetooth Device                            | 27        | 0.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 27        | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 26        | 0.64%   |
| Foxconn / Hon Hai Bluetooth Device                  | 25        | 0.62%   |
| Intel Bluetooth Device                              | 21        | 0.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 20        | 0.5%    |
| Ralink RT3290 Bluetooth                             | 18        | 0.45%   |
| Dell DW375 Bluetooth Module                         | 18        | 0.45%   |
| Realtek Bluetooth Radio                             | 17        | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.42%   |
| HP Broadcom 2070 Bluetooth Combo                    | 17        | 0.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 15        | 0.37%   |
| Realtek RTL8723B Bluetooth                          | 14        | 0.35%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 14        | 0.35%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 13        | 0.32%   |
| Dell BCM20702A0 Bluetooth Module                    | 13        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4922      | 55.43%  |
| Nvidia                           | 1587      | 17.87%  |
| AMD                              | 1577      | 17.76%  |
| C-Media Electronics              | 118       | 1.33%   |
| Logitech                         | 72        | 0.81%   |
| Creative Labs                    | 43        | 0.48%   |
| Texas Instruments                | 40        | 0.45%   |
| Lenovo                           | 29        | 0.33%   |
| Generalplus Technology           | 29        | 0.33%   |
| Plantronics                      | 28        | 0.32%   |
| GN Netcom                        | 28        | 0.32%   |
| Realtek Semiconductor            | 27        | 0.3%    |
| Creative Technology              | 23        | 0.26%   |
| JMTek                            | 19        | 0.21%   |
| ASUSTek Computer                 | 19        | 0.21%   |
| Kingston Technology              | 16        | 0.18%   |
| VIA Technologies                 | 15        | 0.17%   |
| Focusrite-Novation               | 15        | 0.17%   |
| Silicon Integrated Systems [SiS] | 13        | 0.15%   |
| Hewlett-Packard                  | 12        | 0.14%   |
| RODE Microphones                 | 11        | 0.12%   |
| Dell                             | 11        | 0.12%   |
| Razer USA                        | 10        | 0.11%   |
| BEHRINGER International          | 10        | 0.11%   |
| Microsoft                        | 9         | 0.1%    |
| Micro Star International         | 9         | 0.1%    |
| GYROCOM C&C                      | 9         | 0.1%    |
| Sennheiser Communications        | 8         | 0.09%   |
| Blue Microphones                 | 8         | 0.09%   |
| SteelSeries ApS                  | 7         | 0.08%   |
| Corsair                          | 7         | 0.08%   |
| Yamaha                           | 6         | 0.07%   |
| M-Audio                          | 6         | 0.07%   |
| Cambridge Silicon Radio          | 5         | 0.06%   |
| XMOS                             | 4         | 0.05%   |
| Unknown                          | 4         | 0.05%   |
| Tenx Technology                  | 4         | 0.05%   |
| Samsung Electronics              | 4         | 0.05%   |
| Samson Technologies              | 4         | 0.05%   |
| Apple                            | 4         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 503       | 4.79%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 441       | 4.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 406       | 3.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 393       | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 336       | 3.2%    |
| Nvidia MCP79 High Definition Audio                                                                | 317       | 3.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 306       | 2.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 283       | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 268       | 2.55%   |
| Intel Broadwell-U Audio Controller                                                                | 266       | 2.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 263       | 2.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 220       | 2.1%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 216       | 2.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 210       | 2%      |
| Intel Cannon Lake PCH cAVS                                                                        | 207       | 1.97%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 190       | 1.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 180       | 1.72%   |
| Intel 200 Series PCH HD Audio                                                                     | 166       | 1.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 163       | 1.55%   |
| AMD FCH Azalia Controller                                                                         | 162       | 1.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 153       | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 151       | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 137       | 1.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 133       | 1.27%   |
| Intel 8 Series HD Audio Controller                                                                | 133       | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 132       | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 125       | 1.19%   |
| Intel Comet Lake PCH cAVS                                                                         | 124       | 1.18%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 122       | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 122       | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 112       | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 111       | 1.06%   |
| AMD Kabini HDMI/DP Audio                                                                          | 103       | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 102       | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 81        | 0.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 79        | 0.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 79        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 74        | 0.71%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 73        | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 72        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1391      | 21.23%  |
| SK hynix            | 1315      | 20.07%  |
| Kingston            | 765       | 11.68%  |
| Unknown             | 683       | 10.42%  |
| Crucial             | 537       | 8.2%    |
| Micron Technology   | 492       | 7.51%   |
| Corsair             | 254       | 3.88%   |
| G.Skill             | 181       | 2.76%   |
| Elpida              | 130       | 1.98%   |
| A-DATA Technology   | 99        | 1.51%   |
| Ramaxel Technology  | 88        | 1.34%   |
| Patriot             | 74        | 1.13%   |
| Nanya Technology    | 61        | 0.93%   |
| Unknown             | 50        | 0.76%   |
| Unknown (ABCD)      | 48        | 0.73%   |
| Smart               | 37        | 0.56%   |
| Team                | 34        | 0.52%   |
| Transcend           | 30        | 0.46%   |
| GOODRAM             | 27        | 0.41%   |
| AMD                 | 21        | 0.32%   |
| Hikvision           | 20        | 0.31%   |
| Teikon              | 13        | 0.2%    |
| Apacer              | 13        | 0.2%    |
| Hewlett-Packard     | 11        | 0.17%   |
| 48spaces            | 10        | 0.15%   |
| Silicon Power       | 9         | 0.14%   |
| Qimonda             | 8         | 0.12%   |
| GeIL                | 7         | 0.11%   |
| PNY                 | 6         | 0.09%   |
| Smart Brazil        | 5         | 0.08%   |
| Goldkey             | 5         | 0.08%   |
| Avant               | 5         | 0.08%   |
| ASint Technology    | 5         | 0.08%   |
| Wilk                | 4         | 0.06%   |
| Timetec             | 4         | 0.06%   |
| Neo Forza           | 4         | 0.06%   |
| Infineon            | 4         | 0.06%   |
| CSX                 | 4         | 0.06%   |
| Unifosa             | 3         | 0.05%   |
| Toshiba             | 3         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 256       | 3.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 142       | 2.01%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 0.96%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s         | 67        | 0.95%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 61        | 0.86%   |
| Unknown                                                          | 50        | 0.71%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 43        | 0.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 38        | 0.54%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 37        | 0.52%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 36        | 0.51%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 36        | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 33        | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 33        | 0.47%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s            | 31        | 0.44%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s            | 31        | 0.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 30        | 0.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 30        | 0.43%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 29        | 0.41%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 29        | 0.41%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 28        | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 27        | 0.38%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s           | 26        | 0.37%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s  | 25        | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 25        | 0.35%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.35%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 24        | 0.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 24        | 0.34%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s             | 24        | 0.34%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 23        | 0.33%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 22        | 0.31%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.31%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.28%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 20        | 0.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.28%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 0.28%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 20        | 0.28%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s          | 20        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 2408      | 41.42%  |
| DDR3         | 2010      | 34.58%  |
| DDR2         | 660       | 11.35%  |
| SDRAM        | 188       | 3.23%   |
| Unknown      | 184       | 3.17%   |
| LPDDR4       | 143       | 2.46%   |
| LPDDR3       | 127       | 2.18%   |
| DDR          | 60        | 1.03%   |
| DRAM         | 14        | 0.24%   |
| DDR5         | 12        | 0.21%   |
| LPDDR5       | 5         | 0.09%   |
| RAM          | 1         | 0.02%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3208      | 55.45%  |
| DIMM         | 2252      | 38.93%  |
| Row Of Chips | 231       | 3.99%   |
| Unknown      | 46        | 0.8%    |
| Chip         | 32        | 0.55%   |
| FB-DIMM      | 12        | 0.21%   |
| RIMM         | 4         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1989      | 31.62%  |
| 4096  | 1607      | 25.55%  |
| 2048  | 995       | 15.82%  |
| 16384 | 784       | 12.46%  |
| 1024  | 633       | 10.06%  |
| 32768 | 187       | 2.97%   |
| 512   | 63        | 1%      |
| 256   | 20        | 0.32%   |
| 65536 | 4         | 0.06%   |
| 1536  | 4         | 0.06%   |
| 128   | 4         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1358      | 21.82%  |
| 2667    | 808       | 12.98%  |
| 3200    | 750       | 12.05%  |
| 800     | 456       | 7.33%   |
| 1333    | 448       | 7.2%    |
| 2400    | 404       | 6.49%   |
| 2133    | 306       | 4.92%   |
| 667     | 244       | 3.92%   |
| Unknown | 175       | 2.81%   |
| 1334    | 148       | 2.38%   |
| 3600    | 119       | 1.91%   |
| 1867    | 89        | 1.43%   |
| 1866    | 78        | 1.25%   |
| 1067    | 77        | 1.24%   |
| 2666    | 76        | 1.22%   |
| 1066    | 58        | 0.93%   |
| 4267    | 56        | 0.9%    |
| 2933    | 40        | 0.64%   |
| 3000    | 38        | 0.61%   |
| 3266    | 37        | 0.59%   |
| 3466    | 36        | 0.58%   |
| 533     | 34        | 0.55%   |
| 3400    | 33        | 0.53%   |
| 400     | 27        | 0.43%   |
| 4199    | 26        | 0.42%   |
| 2866    | 26        | 0.42%   |
| 2048    | 21        | 0.34%   |
| 3733    | 19        | 0.31%   |
| 1800    | 18        | 0.29%   |
| 975     | 17        | 0.27%   |
| 333     | 16        | 0.26%   |
| 8400    | 14        | 0.22%   |
| 4800    | 14        | 0.22%   |
| 266     | 12        | 0.19%   |
| 4266    | 11        | 0.18%   |
| 3800    | 11        | 0.18%   |
| 3100    | 9         | 0.14%   |
| 3334    | 8         | 0.13%   |
| 3333    | 8         | 0.13%   |
| 4333    | 7         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 54        | 35.29%  |
| Brother Industries    | 25        | 16.34%  |
| Canon                 | 16        | 10.46%  |
| Samsung Electronics   | 12        | 7.84%   |
| Xerox                 | 8         | 5.23%   |
| Seiko Epson           | 8         | 5.23%   |
| Prolific Technology   | 5         | 3.27%   |
| Dymo-CoStar           | 5         | 3.27%   |
| Zebra                 | 3         | 1.96%   |
| Kyocera               | 3         | 1.96%   |
| STMicroelectronics    | 2         | 1.31%   |
| Pantum                | 2         | 1.31%   |
| Datamax-O'Neil        | 2         | 1.31%   |
| Xiaomi                | 1         | 0.65%   |
| Ricoh                 | 1         | 0.65%   |
| QinHeng Electronics   | 1         | 0.65%   |
| Oki Data              | 1         | 0.65%   |
| Lexmark International | 1         | 0.65%   |
| Konica Minolta        | 1         | 0.65%   |
| GODEX INTERNATIONAL   | 1         | 0.65%   |
| Dell                  | 1         | 0.65%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xerox B205                                                            | 7         | 4.52%   |
| HP LaserJet 1020                                                      | 7         | 4.52%   |
| Prolific PL2305 Parallel Port                                         | 5         | 3.23%   |
| HP LaserJet 1200                                                      | 4         | 2.58%   |
| HP LaserJet M101-M106                                                 | 3         | 1.94%   |
| HP DeskJet 2130 series                                                | 3         | 1.94%   |
| Brother HL-52x0 series                                                | 3         | 1.94%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 2         | 1.29%   |
| Samsung ML-216x Series Laser Printer                                  | 2         | 1.29%   |
| Samsung ML-1660 Series                                                | 2         | 1.29%   |
| Pantum P2500W series                                                  | 2         | 1.29%   |
| HP LaserJet Pro M404-M405                                             | 2         | 1.29%   |
| HP LaserJet P1005                                                     | 2         | 1.29%   |
| HP LaserJet M14-M17                                                   | 2         | 1.29%   |
| HP LaserJet 400 M401dne                                               | 2         | 1.29%   |
| HP ENVY Photo 6200 series                                             | 2         | 1.29%   |
| HP ENVY 4520 series                                                   | 2         | 1.29%   |
| HP DeskJet Plus 4100 series                                           | 2         | 1.29%   |
| HP DeskJet 2620 All-in-One Printer                                    | 2         | 1.29%   |
| Dymo-CoStar LabelWriter 450                                           | 2         | 1.29%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 1.29%   |
| Datamax-O'Neil Datamax E-4304                                         | 2         | 1.29%   |
| Canon PIXMA MG3600 Series                                             | 2         | 1.29%   |
| Canon LiDE 400                                                        | 2         | 1.29%   |
| Brother Printer                                                       | 2         | 1.29%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.65%   |
| Zebra ZTC ZD420-203dpi ZPL                                            | 1         | 0.65%   |
| Zebra ZTC S4M-200dpi ZPL                                              | 1         | 0.65%   |
| Xiaomi MiMouse 2                                                      | 1         | 0.65%   |
| Xerox Phaser 3250                                                     | 1         | 0.65%   |
| Seiko Epson XP-15000 Series                                           | 1         | 0.65%   |
| Seiko Epson Printer                                                   | 1         | 0.65%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.65%   |
| Seiko Epson L4150 Series                                              | 1         | 0.65%   |
| Seiko Epson L395 Series                                               | 1         | 0.65%   |
| Seiko Epson L210 Series                                               | 1         | 0.65%   |
| Seiko Epson ET-2850 Series                                            | 1         | 0.65%   |
| Seiko Epson AL-M310DN                                                 | 1         | 0.65%   |
| Samsung SCX-4650 4x21S Series                                         | 1         | 0.65%   |
| Samsung SCX-4600 Series                                               | 1         | 0.65%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 27        | 55.1%   |
| Seiko Epson        | 11        | 22.45%  |
| Hewlett-Packard    | 6         | 12.24%  |
| Mustek Systems     | 2         | 4.08%   |
| AGFA-Gevaert NV    | 2         | 4.08%   |
| Ultima Electronics | 1         | 2.04%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 8         | 16.33%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 5         | 10.2%   |
| Canon CanoScan LiDE 220                                                               | 3         | 6.12%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 4.08%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 4.08%   |
| Canon CanoScan LIDE 25                                                                | 2         | 4.08%   |
| Canon CanoScan LiDE 210                                                               | 2         | 4.08%   |
| Canon CanoScan LiDE 120                                                               | 2         | 4.08%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2         | 4.08%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 2.04%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 2.04%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1         | 2.04%   |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 2.04%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 2.04%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 2.04%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1         | 2.04%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 2.04%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1         | 2.04%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1         | 2.04%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 2.04%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1         | 2.04%   |
| HP ScanJet Pro 2500 f1                                                                | 1         | 2.04%   |
| HP ScanJet 82x0C                                                                      | 1         | 2.04%   |
| HP ScanJet 7650                                                                       | 1         | 2.04%   |
| HP ScanJet 3970c                                                                      | 1         | 2.04%   |
| HP Scanjet 300                                                                        | 1         | 2.04%   |
| HP Scanjet 200                                                                        | 1         | 2.04%   |
| Canon CanoScan 9000F Mark II                                                          | 1         | 2.04%   |
| Canon CanoScan 8800F                                                                  | 1         | 2.04%   |
| Canon CanoScan 5600F                                                                  | 1         | 2.04%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 793       | 21.92%  |
| Acer                                   | 397       | 10.98%  |
| IMC Networks                           | 328       | 9.07%   |
| Microdia                               | 287       | 7.93%   |
| Realtek Semiconductor                  | 256       | 7.08%   |
| Logitech                               | 236       | 6.52%   |
| Quanta                                 | 220       | 6.08%   |
| Sunplus Innovation Technology          | 174       | 4.81%   |
| Suyin                                  | 99        | 2.74%   |
| Cheng Uei Precision Industry (Foxlink) | 99        | 2.74%   |
| Apple                                  | 86        | 2.38%   |
| Lite-On Technology                     | 76        | 2.1%    |
| Syntek                                 | 71        | 1.96%   |
| Luxvisions Innotech Limited            | 46        | 1.27%   |
| Silicon Motion                         | 44        | 1.22%   |
| Alcor Micro                            | 39        | 1.08%   |
| Samsung Electronics                    | 32        | 0.88%   |
| Z-Star Microelectronics                | 30        | 0.83%   |
| Microsoft                              | 30        | 0.83%   |
| Ricoh                                  | 28        | 0.77%   |
| Lenovo                                 | 25        | 0.69%   |
| Generalplus Technology                 | 20        | 0.55%   |
| Creative Technology                    | 13        | 0.36%   |
| Primax Electronics                     | 11        | 0.3%    |
| Genesys Logic                          | 10        | 0.28%   |
| ARC International                      | 10        | 0.28%   |
| KYE Systems (Mouse Systems)            | 9         | 0.25%   |
| Jieli Technology                       | 9         | 0.25%   |
| GEMBIRD                                | 9         | 0.25%   |
| ALi                                    | 9         | 0.25%   |
| Unknown                                | 8         | 0.22%   |
| Sonix Technology                       | 8         | 0.22%   |
| MacroSilicon                           | 6         | 0.17%   |
| OmniVision Technologies                | 5         | 0.14%   |
| Importek                               | 5         | 0.14%   |
| Hewlett-Packard                        | 5         | 0.14%   |
| Cubeternet                             | 5         | 0.14%   |
| Intel                                  | 4         | 0.11%   |
| icSpring                               | 4         | 0.11%   |
| Huawei Technologies                    | 4         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 235       | 6.4%    |
| Acer Integrated Camera                              | 148       | 4.03%   |
| Microdia Integrated_Webcam_HD                       | 119       | 3.24%   |
| IMC Networks Integrated Camera                      | 115       | 3.13%   |
| Realtek Integrated_Webcam_HD                        | 92        | 2.5%    |
| Acer Integrated 5M Camera                           | 70        | 1.91%   |
| Quanta Chromebook HD Camera                         | 68        | 1.85%   |
| Chicony HD Webcam                                   | 68        | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 66        | 1.8%    |
| Logitech Webcam C270                                | 60        | 1.63%   |
| Acer BisonCam, NB Pro                               | 55        | 1.5%    |
| Sunplus Integrated_Webcam_HD                        | 54        | 1.47%   |
| Chicony Integrated 5M Camera                        | 43        | 1.17%   |
| Syntek Integrated Camera                            | 38        | 1.03%   |
| Logitech HD Pro Webcam C920                         | 37        | 1.01%   |
| Chicony HP HD Camera                                | 35        | 0.95%   |
| Lite-On Integrated Camera                           | 32        | 0.87%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 32        | 0.87%   |
| Chicony USB2.0 HD UVC WebCam                        | 32        | 0.87%   |
| Samsung Galaxy A5 (MTP)                             | 31        | 0.84%   |
| Quanta HP TrueVision HD Camera                      | 31        | 0.84%   |
| Apple iPhone5/5C/5S/6                               | 28        | 0.76%   |
| Acer SunplusIT Integrated Camera                    | 28        | 0.76%   |
| Apple Built-in iSight                               | 27        | 0.73%   |
| Acer Lenovo EasyCamera                              | 24        | 0.65%   |
| Microdia Integrated Webcam                          | 23        | 0.63%   |
| Logitech C922 Pro Stream Webcam                     | 23        | 0.63%   |
| Chicony Integrated Camera (1280x720@30)             | 23        | 0.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 22        | 0.6%    |
| Realtek USB Camera                                  | 21        | 0.57%   |
| Quanta VGA WebCam                                   | 21        | 0.57%   |
| Sunplus HD WebCam                                   | 20        | 0.54%   |
| Realtek USB2.0 HD UVC WebCam                        | 19        | 0.52%   |
| Quanta HP HD Camera                                 | 19        | 0.52%   |
| Quanta HD User Facing                               | 19        | 0.52%   |
| Chicony EasyCamera                                  | 18        | 0.49%   |
| Acer Lenovo Integrated Webcam                       | 18        | 0.49%   |
| Realtek Integrated Webcam                           | 17        | 0.46%   |
| Lite-On HP HD Camera                                | 17        | 0.46%   |
| Chicony USB 2.0 Camera                              | 17        | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 327       | 42.36%  |
| Validity Sensors           | 211       | 27.33%  |
| Shenzhen Goodix Technology | 83        | 10.75%  |
| AuthenTec                  | 40        | 5.18%   |
| Elan Microelectronics      | 37        | 4.79%   |
| Upek                       | 36        | 4.66%   |
| LighTuning Technology      | 20        | 2.59%   |
| STMicroelectronics         | 13        | 1.68%   |
| Samsung Electronics        | 4         | 0.52%   |
| Microsoft                  | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 198       | 25.65%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 51        | 6.61%   |
| Shenzhen Goodix  FingerPrint Device                                        | 46        | 5.96%   |
| Unknown                                                                    | 43        | 5.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 42        | 5.44%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 35        | 4.53%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 33        | 4.27%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 27        | 3.5%    |
| Elan ELAN:Fingerprint                                                      | 24        | 3.11%   |
| Shenzhen Goodix Fingerprint Reader                                         | 23        | 2.98%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.2%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 17        | 2.2%    |
| AuthenTec AES2810                                                          | 16        | 2.07%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 15        | 1.94%   |
| Synaptics  WBDI                                                            | 14        | 1.81%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 1.81%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 1.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.55%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 12        | 1.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 1.55%   |
| Elan ELAN:ARM-M4                                                           | 12        | 1.55%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.42%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 1.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 1.04%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.78%   |
| Validity Sensors VFS491                                                    | 5         | 0.65%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.52%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.52%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.52%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.39%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.39%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 0.39%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.39%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.39%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.26%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.26%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.26%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 118       | 34.71%  |
| Alcor Micro                | 116       | 34.12%  |
| Upek                       | 24        | 7.06%   |
| Lenovo                     | 22        | 6.47%   |
| O2 Micro                   | 21        | 6.18%   |
| Gemalto (was Gemplus)      | 7         | 2.06%   |
| Clay Logic                 | 6         | 1.76%   |
| Yubico.com                 | 4         | 1.18%   |
| SCM Microsystems           | 4         | 1.18%   |
| Cherry                     | 4         | 1.18%   |
| Aladdin Knowledge Systems  | 4         | 1.18%   |
| Chicony Electronics        | 2         | 0.59%   |
| Advanced Card Systems      | 2         | 0.59%   |
| Reiner SCT Kartensysteme   | 1         | 0.29%   |
| Realtek Semiconductor      | 1         | 0.29%   |
| OmniKey                    | 1         | 0.29%   |
| Hewlett-Packard            | 1         | 0.29%   |
| C3PO                       | 1         | 0.29%   |
| Athena Smartcard Solutions | 1         | 0.29%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 113       | 33.24%  |
| Broadcom BCM5880 Secure Applications Processor                               | 39        | 11.47%  |
| Broadcom 58200                                                               | 31        | 9.12%   |
| Broadcom 5880                                                                | 29        | 8.53%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 7.06%   |
| Lenovo Integrated Smart Card Reader                                          | 22        | 6.47%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 5.29%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 5.29%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 1.18%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 1.18%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.88%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.88%   |
| Clay Logic Nitrokey Start                                                    | 3         | 0.88%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.88%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.88%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.59%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.59%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 0.59%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.59%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.29%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.29%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.29%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.29%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.29%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.29%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.29%   |
| OmniKey CardMan 4321                                                         | 1         | 0.29%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.29%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.29%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.29%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.29%   |
| C3PO LTC31v2                                                                 | 1         | 0.29%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.29%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.29%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4441      | 60.81%  |
| 1     | 2297      | 31.45%  |
| 2     | 445       | 6.09%   |
| 3     | 92        | 1.26%   |
| 4     | 16        | 0.22%   |
| 5     | 7         | 0.1%    |
| 6     | 3         | 0.04%   |
| 7     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1294      | 38.26%  |
| Fingerprint reader       | 768       | 22.71%  |
| Chipcard                 | 294       | 8.69%   |
| Multimedia controller    | 264       | 7.81%   |
| Net/wireless             | 258       | 7.63%   |
| Communication controller | 126       | 3.73%   |
| Unassigned class         | 79        | 2.34%   |
| Bluetooth                | 65        | 1.92%   |
| Card reader              | 47        | 1.39%   |
| Camera                   | 41        | 1.21%   |
| Sound                    | 37        | 1.09%   |
| Storage                  | 34        | 1.01%   |
| Net/ethernet             | 25        | 0.74%   |
| Network                  | 16        | 0.47%   |
| Modem                    | 8         | 0.24%   |
| Storage/ide              | 6         | 0.18%   |
| Storage/raid             | 5         | 0.15%   |
| Flash memory             | 4         | 0.12%   |
| Dvb card                 | 4         | 0.12%   |
| Tv card                  | 3         | 0.09%   |
| Firewire controller      | 2         | 0.06%   |
| Wireless                 | 1         | 0.03%   |
| Storage/ata              | 1         | 0.03%   |

