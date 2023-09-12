Pop!_OS 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS_22.04/Desktop/README.md) and [notebooks](/Dist/Pop!_OS_22.04/Notebook/README.md).

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

Total: 4670

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Alpha 15 A3DDK              | Notebook    | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [d061b57b29](https://linux-hardware.org/?probe=d061b57b29) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [3221a3e5dd](https://linux-hardware.org/?probe=3221a3e5dd) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [13bae1c4e9](https://linux-hardware.org/?probe=13bae1c4e9) | Sep 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| Dell          | 0WN7Y6 A02                  | Desktop     | [aaf64e4624](https://linux-hardware.org/?probe=aaf64e4624) | Sep 07, 2023 |
| Biostar       | A58MD                       | Desktop     | [40f078fcfc](https://linux-hardware.org/?probe=40f078fcfc) | Sep 06, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [bfdd099826](https://linux-hardware.org/?probe=bfdd099826) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [611bb4fe1a](https://linux-hardware.org/?probe=611bb4fe1a) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [38f9d1abd9](https://linux-hardware.org/?probe=38f9d1abd9) | Sep 05, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [56f00eec4a](https://linux-hardware.org/?probe=56f00eec4a) | Sep 05, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [613e4acc75](https://linux-hardware.org/?probe=613e4acc75) | Sep 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [a33ec74b50](https://linux-hardware.org/?probe=a33ec74b50) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [d5cd8916d0](https://linux-hardware.org/?probe=d5cd8916d0) | Sep 05, 2023 |
| Gigabyte      | Z590 AORUS MASTER           | Desktop     | [40785211e9](https://linux-hardware.org/?probe=40785211e9) | Sep 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [11c016fb1b](https://linux-hardware.org/?probe=11c016fb1b) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B460-H GAMING     | Desktop     | [865ce7b55b](https://linux-hardware.org/?probe=865ce7b55b) | Sep 04, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ee1a881e82](https://linux-hardware.org/?probe=ee1a881e82) | Sep 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [9ea11da090](https://linux-hardware.org/?probe=9ea11da090) | Sep 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [68e90ee0cb](https://linux-hardware.org/?probe=68e90ee0cb) | Sep 04, 2023 |
| ASUSTek       | K53E                        | Notebook    | [5604fe515d](https://linux-hardware.org/?probe=5604fe515d) | Sep 04, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a30ea8885d](https://linux-hardware.org/?probe=a30ea8885d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [e9faf4759d](https://linux-hardware.org/?probe=e9faf4759d) | Sep 03, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [ffc201e884](https://linux-hardware.org/?probe=ffc201e884) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [515e1f4bce](https://linux-hardware.org/?probe=515e1f4bce) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [4a31ab4d2b](https://linux-hardware.org/?probe=4a31ab4d2b) | Sep 02, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [1c82c8d8b5](https://linux-hardware.org/?probe=1c82c8d8b5) | Sep 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [b4907a6220](https://linux-hardware.org/?probe=b4907a6220) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| MSI           | A320M-A PRO M2              | Desktop     | [6745b7e37d](https://linux-hardware.org/?probe=6745b7e37d) | Sep 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [6ddc9b767d](https://linux-hardware.org/?probe=6ddc9b767d) | Sep 01, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [76b83d4e93](https://linux-hardware.org/?probe=76b83d4e93) | Sep 01, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [d0cdea5d23](https://linux-hardware.org/?probe=d0cdea5d23) | Sep 01, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [b2effdc956](https://linux-hardware.org/?probe=b2effdc956) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [67f553625a](https://linux-hardware.org/?probe=67f553625a) | Sep 01, 2023 |
| Dell          | Latitude E7470              | Notebook    | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | Notebook    | [1213d3bf46](https://linux-hardware.org/?probe=1213d3bf46) | Aug 31, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [ba11958a48](https://linux-hardware.org/?probe=ba11958a48) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [158ed240bf](https://linux-hardware.org/?probe=158ed240bf) | Aug 31, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [875427cd72](https://linux-hardware.org/?probe=875427cd72) | Aug 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3b890e064f](https://linux-hardware.org/?probe=3b890e064f) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [085b3d4330](https://linux-hardware.org/?probe=085b3d4330) | Aug 31, 2023 |
| Google        | Kefka                       | Notebook    | [284517c2b3](https://linux-hardware.org/?probe=284517c2b3) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [98b18bb67a](https://linux-hardware.org/?probe=98b18bb67a) | Aug 31, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [45f86c066d](https://linux-hardware.org/?probe=45f86c066d) | Aug 30, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [84f61e2225](https://linux-hardware.org/?probe=84f61e2225) | Aug 30, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Google        | Kefka                       | Notebook    | [a018ae3fb5](https://linux-hardware.org/?probe=a018ae3fb5) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [90a72df8ef](https://linux-hardware.org/?probe=90a72df8ef) | Aug 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | Notebook    | [481b37b0fc](https://linux-hardware.org/?probe=481b37b0fc) | Aug 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [ebebe5ddf7](https://linux-hardware.org/?probe=ebebe5ddf7) | Aug 29, 2023 |
| Dell          | Latitude 5330               | Notebook    | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [0be67de1c9](https://linux-hardware.org/?probe=0be67de1c9) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | Notebook    | [2f669d797f](https://linux-hardware.org/?probe=2f669d797f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | Notebook    | [39f2feeed5](https://linux-hardware.org/?probe=39f2feeed5) | Aug 29, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [4cdf174574](https://linux-hardware.org/?probe=4cdf174574) | Aug 29, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6d2186fdd9](https://linux-hardware.org/?probe=6d2186fdd9) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | Notebook    | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [ef97f75590](https://linux-hardware.org/?probe=ef97f75590) | Aug 28, 2023 |
| Dell          | Precision 5510              | Notebook    | [c6d08d9c28](https://linux-hardware.org/?probe=c6d08d9c28) | Aug 27, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [b07775a194](https://linux-hardware.org/?probe=b07775a194) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | Notebook    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Precision M4600             | Notebook    | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Unknown       | V00                         | Mini pc     | [b63adaac28](https://linux-hardware.org/?probe=b63adaac28) | Aug 27, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [9e0b5b0b7e](https://linux-hardware.org/?probe=9e0b5b0b7e) | Aug 26, 2023 |
| Dell          | Precision M6800             | Notebook    | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [e3a47f55c9](https://linux-hardware.org/?probe=e3a47f55c9) | Aug 26, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [f3874bf2fc](https://linux-hardware.org/?probe=f3874bf2fc) | Aug 26, 2023 |
| HP            | ProBook 4730s               | Notebook    | [32f610b810](https://linux-hardware.org/?probe=32f610b810) | Aug 26, 2023 |
| Google        | Kasumi                      | Notebook    | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| System76      | Gazelle                     | Notebook    | [b3fb438915](https://linux-hardware.org/?probe=b3fb438915) | Aug 25, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [8d952e28e1](https://linux-hardware.org/?probe=8d952e28e1) | Aug 25, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [51d4eefbc9](https://linux-hardware.org/?probe=51d4eefbc9) | Aug 25, 2023 |
| System76      | Thelio Major thelio-majo... | Desktop     | [e5caa63b77](https://linux-hardware.org/?probe=e5caa63b77) | Aug 25, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [958521d2be](https://linux-hardware.org/?probe=958521d2be) | Aug 25, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [254f8aee40](https://linux-hardware.org/?probe=254f8aee40) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [6f72852248](https://linux-hardware.org/?probe=6f72852248) | Aug 25, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [acc5fdd0f3](https://linux-hardware.org/?probe=acc5fdd0f3) | Aug 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [34fc2a5f83](https://linux-hardware.org/?probe=34fc2a5f83) | Aug 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [c0bf920a5b](https://linux-hardware.org/?probe=c0bf920a5b) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [40660610aa](https://linux-hardware.org/?probe=40660610aa) | Aug 24, 2023 |
| Dell          | Latitude 7430               | Notebook    | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [18df557333](https://linux-hardware.org/?probe=18df557333) | Aug 24, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [82be53cac0](https://linux-hardware.org/?probe=82be53cac0) | Aug 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [2970428ad3](https://linux-hardware.org/?probe=2970428ad3) | Aug 23, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [5abce3a991](https://linux-hardware.org/?probe=5abce3a991) | Aug 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b0ca2ee250](https://linux-hardware.org/?probe=b0ca2ee250) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [6f0e38b5e8](https://linux-hardware.org/?probe=6f0e38b5e8) | Aug 23, 2023 |
| HP            | 18E7                        | Desktop     | [a78496c36e](https://linux-hardware.org/?probe=a78496c36e) | Aug 23, 2023 |
| Samsung       | 750TDA                      | Notebook    | [7b1ec96afa](https://linux-hardware.org/?probe=7b1ec96afa) | Aug 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [4cd19df49e](https://linux-hardware.org/?probe=4cd19df49e) | Aug 23, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [145d800029](https://linux-hardware.org/?probe=145d800029) | Aug 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | Notebook    | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [fdd24243bf](https://linux-hardware.org/?probe=fdd24243bf) | Aug 22, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [54794fb9e8](https://linux-hardware.org/?probe=54794fb9e8) | Aug 22, 2023 |
| Supermicro    | X12SPA-TF                   | Server      | [b0d65c559f](https://linux-hardware.org/?probe=b0d65c559f) | Aug 22, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [0f5028d5fc](https://linux-hardware.org/?probe=0f5028d5fc) | Aug 22, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [d86049c586](https://linux-hardware.org/?probe=d86049c586) | Aug 21, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [be53b5931f](https://linux-hardware.org/?probe=be53b5931f) | Aug 21, 2023 |
| HP            | ProBook 4730s               | Notebook    | [5b4d88bc67](https://linux-hardware.org/?probe=5b4d88bc67) | Aug 21, 2023 |
| AZW           | GTR V02                     | Desktop     | [d699113f95](https://linux-hardware.org/?probe=d699113f95) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [930d312c36](https://linux-hardware.org/?probe=930d312c36) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [2bc8c24081](https://linux-hardware.org/?probe=2bc8c24081) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b66d308d42](https://linux-hardware.org/?probe=b66d308d42) | Aug 21, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [f9742049fc](https://linux-hardware.org/?probe=f9742049fc) | Aug 20, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [83b6cab3cd](https://linux-hardware.org/?probe=83b6cab3cd) | Aug 20, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b7e0bd11e5](https://linux-hardware.org/?probe=b7e0bd11e5) | Aug 20, 2023 |
| Dell          | Precision 5520              | Notebook    | [42587aac96](https://linux-hardware.org/?probe=42587aac96) | Aug 20, 2023 |
| Dell          | Precision 5520              | Notebook    | [bec735d800](https://linux-hardware.org/?probe=bec735d800) | Aug 20, 2023 |
| NZXT          | N7 B550                     | Desktop     | [1f105eadd8](https://linux-hardware.org/?probe=1f105eadd8) | Aug 20, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [31861c8357](https://linux-hardware.org/?probe=31861c8357) | Aug 20, 2023 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [04df52e837](https://linux-hardware.org/?probe=04df52e837) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR    | Notebook    | [5d063a6e59](https://linux-hardware.org/?probe=5d063a6e59) | Aug 19, 2023 |
| Lenovo        | B490 377224P                | Notebook    | [0e516ea22b](https://linux-hardware.org/?probe=0e516ea22b) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [63d06430e4](https://linux-hardware.org/?probe=63d06430e4) | Aug 18, 2023 |
| HP            | 0266                        | Desktop     | [636546711d](https://linux-hardware.org/?probe=636546711d) | Aug 18, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [70eda3a12d](https://linux-hardware.org/?probe=70eda3a12d) | Aug 18, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a77f908bb5](https://linux-hardware.org/?probe=a77f908bb5) | Aug 18, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a1ab007f7f](https://linux-hardware.org/?probe=a1ab007f7f) | Aug 18, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [53c4af621d](https://linux-hardware.org/?probe=53c4af621d) | Aug 18, 2023 |
| ASUSTek       | U38N                        | Notebook    | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [a6a7224d63](https://linux-hardware.org/?probe=a6a7224d63) | Aug 17, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [680fae2274](https://linux-hardware.org/?probe=680fae2274) | Aug 17, 2023 |
| HP            | 2AF7                        | Desktop     | [4e55d08586](https://linux-hardware.org/?probe=4e55d08586) | Aug 17, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [43fd1aad67](https://linux-hardware.org/?probe=43fd1aad67) | Aug 17, 2023 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [7c09135f98](https://linux-hardware.org/?probe=7c09135f98) | Aug 17, 2023 |
| System76      | Lemur Pro                   | Notebook    | [af3b387574](https://linux-hardware.org/?probe=af3b387574) | Aug 16, 2023 |
| HP            | Elite Dragonfly             | Convertible | [7419fe990e](https://linux-hardware.org/?probe=7419fe990e) | Aug 16, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [ec4afb1917](https://linux-hardware.org/?probe=ec4afb1917) | Aug 16, 2023 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [59faf4a458](https://linux-hardware.org/?probe=59faf4a458) | Aug 15, 2023 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [537cce8a8e](https://linux-hardware.org/?probe=537cce8a8e) | Aug 15, 2023 |
| Positivo      | POS-RIQ470EN 11190998       | Desktop     | [1eec60309a](https://linux-hardware.org/?probe=1eec60309a) | Aug 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c2cfa9bd7a](https://linux-hardware.org/?probe=c2cfa9bd7a) | Aug 15, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0927025cfc](https://linux-hardware.org/?probe=0927025cfc) | Aug 15, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [431ac1b880](https://linux-hardware.org/?probe=431ac1b880) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| Intel         | B75A                        | Desktop     | [c081fb2ca8](https://linux-hardware.org/?probe=c081fb2ca8) | Aug 15, 2023 |
| System76      | Galago Pro                  | Notebook    | [54348f9c55](https://linux-hardware.org/?probe=54348f9c55) | Aug 14, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [61ff7ac5f1](https://linux-hardware.org/?probe=61ff7ac5f1) | Aug 14, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [18b513f5f0](https://linux-hardware.org/?probe=18b513f5f0) | Aug 14, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [1f27d0f994](https://linux-hardware.org/?probe=1f27d0f994) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0b194349eb](https://linux-hardware.org/?probe=0b194349eb) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [9a8e4bc08d](https://linux-hardware.org/?probe=9a8e4bc08d) | Aug 14, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [302fb03dce](https://linux-hardware.org/?probe=302fb03dce) | Aug 13, 2023 |
| HP            | ProBook 4540s               | Notebook    | [84dbf6b759](https://linux-hardware.org/?probe=84dbf6b759) | Aug 13, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [2c2aca991d](https://linux-hardware.org/?probe=2c2aca991d) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [ee66d3a81c](https://linux-hardware.org/?probe=ee66d3a81c) | Aug 13, 2023 |
| MSI           | X99A GODLIKE GAMING         | Desktop     | [b87f112952](https://linux-hardware.org/?probe=b87f112952) | Aug 13, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [edf714498f](https://linux-hardware.org/?probe=edf714498f) | Aug 13, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [213d229837](https://linux-hardware.org/?probe=213d229837) | Aug 13, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [ae586a02aa](https://linux-hardware.org/?probe=ae586a02aa) | Aug 13, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [823e276406](https://linux-hardware.org/?probe=823e276406) | Aug 13, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [a38cee5cc9](https://linux-hardware.org/?probe=a38cee5cc9) | Aug 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [eb83156c5f](https://linux-hardware.org/?probe=eb83156c5f) | Aug 12, 2023 |
| Intel         | B75A                        | Desktop     | [91f9e56ace](https://linux-hardware.org/?probe=91f9e56ace) | Aug 12, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | Notebook    | [6ac135c81c](https://linux-hardware.org/?probe=6ac135c81c) | Aug 12, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [db9f130ade](https://linux-hardware.org/?probe=db9f130ade) | Aug 12, 2023 |
| Dell          | G7 7588                     | Notebook    | [48faf46c2c](https://linux-hardware.org/?probe=48faf46c2c) | Aug 12, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [2832e701f2](https://linux-hardware.org/?probe=2832e701f2) | Aug 12, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [2c92ed92eb](https://linux-hardware.org/?probe=2c92ed92eb) | Aug 12, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [580fda2e6b](https://linux-hardware.org/?probe=580fda2e6b) | Aug 12, 2023 |
| MSI           | A55M-E33                    | Desktop     | [7d538db764](https://linux-hardware.org/?probe=7d538db764) | Aug 12, 2023 |
| MSI           | A55M-E33                    | Desktop     | [9e64865fbc](https://linux-hardware.org/?probe=9e64865fbc) | Aug 12, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [0d45e9e048](https://linux-hardware.org/?probe=0d45e9e048) | Aug 12, 2023 |
| Dell          | Precision M4600             | Notebook    | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [361e073b5c](https://linux-hardware.org/?probe=361e073b5c) | Aug 11, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [a6d2358585](https://linux-hardware.org/?probe=a6d2358585) | Aug 11, 2023 |
| Acer          | Nitro AN715-51              | Notebook    | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [cf0d6729b4](https://linux-hardware.org/?probe=cf0d6729b4) | Aug 11, 2023 |
| ASRock        | B650M-HDV/M.2               | Desktop     | [ffd395aee0](https://linux-hardware.org/?probe=ffd395aee0) | Aug 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e22f71b79d](https://linux-hardware.org/?probe=e22f71b79d) | Aug 11, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [e98d8d116d](https://linux-hardware.org/?probe=e98d8d116d) | Aug 10, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [d4c5a12d06](https://linux-hardware.org/?probe=d4c5a12d06) | Aug 10, 2023 |
| HP            | 2AF9                        | Desktop     | [b31b796804](https://linux-hardware.org/?probe=b31b796804) | Aug 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [7f91d6f9d8](https://linux-hardware.org/?probe=7f91d6f9d8) | Aug 10, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [739bc450b8](https://linux-hardware.org/?probe=739bc450b8) | Aug 09, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [b77ff095f8](https://linux-hardware.org/?probe=b77ff095f8) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [b1a8fc0704](https://linux-hardware.org/?probe=b1a8fc0704) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [920797388b](https://linux-hardware.org/?probe=920797388b) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 4330s               | Notebook    | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | Notebook    | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [13b739e83a](https://linux-hardware.org/?probe=13b739e83a) | Aug 09, 2023 |
| System76      | Darter Pro                  | Notebook    | [5162d61c01](https://linux-hardware.org/?probe=5162d61c01) | Aug 09, 2023 |
| NZXT          | N7 Z590                     | Desktop     | [3831033bdc](https://linux-hardware.org/?probe=3831033bdc) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [b041192310](https://linux-hardware.org/?probe=b041192310) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [c4ac4952a4](https://linux-hardware.org/?probe=c4ac4952a4) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [62a5817462](https://linux-hardware.org/?probe=62a5817462) | Aug 09, 2023 |
| Alienware     | 14                          | Notebook    | [192b13997d](https://linux-hardware.org/?probe=192b13997d) | Aug 09, 2023 |
| HP            | Victus by 15.6 inch Gami... | Notebook    | [67f88ab571](https://linux-hardware.org/?probe=67f88ab571) | Aug 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6abad99081](https://linux-hardware.org/?probe=6abad99081) | Aug 08, 2023 |
| Dell          | Inspiron 5482               | Convertible | [7e2aa092cf](https://linux-hardware.org/?probe=7e2aa092cf) | Aug 08, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [afa081b440](https://linux-hardware.org/?probe=afa081b440) | Aug 08, 2023 |
| Acer          | Ferrari One 200             | Notebook    | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [f485bf4b6e](https://linux-hardware.org/?probe=f485bf4b6e) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [00b169d241](https://linux-hardware.org/?probe=00b169d241) | Aug 08, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c415fd317b](https://linux-hardware.org/?probe=c415fd317b) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [5e0c7f7bfc](https://linux-hardware.org/?probe=5e0c7f7bfc) | Aug 08, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [57f1225daf](https://linux-hardware.org/?probe=57f1225daf) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [58208c1f16](https://linux-hardware.org/?probe=58208c1f16) | Aug 08, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [088a8fad47](https://linux-hardware.org/?probe=088a8fad47) | Aug 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [45fe14954d](https://linux-hardware.org/?probe=45fe14954d) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [d1bca9ae8b](https://linux-hardware.org/?probe=d1bca9ae8b) | Aug 07, 2023 |
| System76      | Oryx Pro                    | Notebook    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [5fe9a17769](https://linux-hardware.org/?probe=5fe9a17769) | Aug 07, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [43eb53850c](https://linux-hardware.org/?probe=43eb53850c) | Aug 06, 2023 |
| Clevo         | W150HRM                     | Notebook    | [1ddcfcbecc](https://linux-hardware.org/?probe=1ddcfcbecc) | Aug 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [16936ef482](https://linux-hardware.org/?probe=16936ef482) | Aug 06, 2023 |
| Dell          | Inspiron 5482               | Convertible | [9c910c0949](https://linux-hardware.org/?probe=9c910c0949) | Aug 06, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [6d2bc8aa9e](https://linux-hardware.org/?probe=6d2bc8aa9e) | Aug 06, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [ac2bdfc67b](https://linux-hardware.org/?probe=ac2bdfc67b) | Aug 06, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [576241bbd4](https://linux-hardware.org/?probe=576241bbd4) | Aug 06, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [93917e587f](https://linux-hardware.org/?probe=93917e587f) | Aug 06, 2023 |
| Notebook      | 1745                        | Notebook    | [3561a5dbbe](https://linux-hardware.org/?probe=3561a5dbbe) | Aug 06, 2023 |
| HP            | Pavilion dm4                | Notebook    | [521b8518ed](https://linux-hardware.org/?probe=521b8518ed) | Aug 06, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [9a45c9f834](https://linux-hardware.org/?probe=9a45c9f834) | Aug 05, 2023 |
| Dell          | Latitude 5430               | Notebook    | [f63444b0be](https://linux-hardware.org/?probe=f63444b0be) | Aug 05, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [4e0084cd74](https://linux-hardware.org/?probe=4e0084cd74) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [3cfd827251](https://linux-hardware.org/?probe=3cfd827251) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [a4a6f81455](https://linux-hardware.org/?probe=a4a6f81455) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [ef010c9d51](https://linux-hardware.org/?probe=ef010c9d51) | Aug 05, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [7d17fc9ff6](https://linux-hardware.org/?probe=7d17fc9ff6) | Aug 05, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [5746742389](https://linux-hardware.org/?probe=5746742389) | Aug 04, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [af453d6ef1](https://linux-hardware.org/?probe=af453d6ef1) | Aug 04, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [92ef92268a](https://linux-hardware.org/?probe=92ef92268a) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ca1a97268c](https://linux-hardware.org/?probe=ca1a97268c) | Aug 04, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [286cc8b0dd](https://linux-hardware.org/?probe=286cc8b0dd) | Aug 04, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [6ec952b536](https://linux-hardware.org/?probe=6ec952b536) | Aug 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [983329d56b](https://linux-hardware.org/?probe=983329d56b) | Aug 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS0GY0R    | Notebook    | [4d618e08b3](https://linux-hardware.org/?probe=4d618e08b3) | Aug 03, 2023 |
| JHZD          | X830                        | Desktop     | [7de7f6bb75](https://linux-hardware.org/?probe=7de7f6bb75) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | Notebook    | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| JHZD          | X830                        | Desktop     | [4fed3648c0](https://linux-hardware.org/?probe=4fed3648c0) | Aug 03, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [cf49ff3004](https://linux-hardware.org/?probe=cf49ff3004) | Aug 03, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2254be2ae2](https://linux-hardware.org/?probe=2254be2ae2) | Aug 03, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [1a9566fa0a](https://linux-hardware.org/?probe=1a9566fa0a) | Aug 03, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ec5ec88e59](https://linux-hardware.org/?probe=ec5ec88e59) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [99ccd043cb](https://linux-hardware.org/?probe=99ccd043cb) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [d4e267a214](https://linux-hardware.org/?probe=d4e267a214) | Aug 02, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [d041df173b](https://linux-hardware.org/?probe=d041df173b) | Aug 02, 2023 |
| Dell          | 07PR60 A00                  | Desktop     | [590695e09f](https://linux-hardware.org/?probe=590695e09f) | Aug 02, 2023 |
| HP            | 8054                        | Desktop     | [f53df18325](https://linux-hardware.org/?probe=f53df18325) | Aug 02, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [542578b4cf](https://linux-hardware.org/?probe=542578b4cf) | Aug 02, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| HP            | 8309                        | Desktop     | [6cb1cfc925](https://linux-hardware.org/?probe=6cb1cfc925) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [0a3c5e5c4d](https://linux-hardware.org/?probe=0a3c5e5c4d) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [9f852ea211](https://linux-hardware.org/?probe=9f852ea211) | Aug 02, 2023 |
| ASUSTek       | GL502VSK                    | Notebook    | [0ed7feaa05](https://linux-hardware.org/?probe=0ed7feaa05) | Aug 01, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [d252fa93be](https://linux-hardware.org/?probe=d252fa93be) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3500               | Notebook    | [df5211a816](https://linux-hardware.org/?probe=df5211a816) | Aug 01, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [41d4bd6cfe](https://linux-hardware.org/?probe=41d4bd6cfe) | Aug 01, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [3a655f04e1](https://linux-hardware.org/?probe=3a655f04e1) | Aug 01, 2023 |
| Dell          | Latitude 5490               | Notebook    | [e24a9f877c](https://linux-hardware.org/?probe=e24a9f877c) | Aug 01, 2023 |
| Apple         | Mac-F2218FC8                | All in one  | [1e13eec6e4](https://linux-hardware.org/?probe=1e13eec6e4) | Aug 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [1ba844bc69](https://linux-hardware.org/?probe=1ba844bc69) | Aug 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [e019d33faf](https://linux-hardware.org/?probe=e019d33faf) | Aug 01, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [82be4b3dfb](https://linux-hardware.org/?probe=82be4b3dfb) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c44863a1c](https://linux-hardware.org/?probe=1c44863a1c) | Jul 31, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [030f8afe2d](https://linux-hardware.org/?probe=030f8afe2d) | Jul 31, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [ed53779d9a](https://linux-hardware.org/?probe=ed53779d9a) | Jul 31, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [d1d59592c3](https://linux-hardware.org/?probe=d1d59592c3) | Jul 30, 2023 |
| ASUSTek       | K95VM                       | Notebook    | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [ac4682042f](https://linux-hardware.org/?probe=ac4682042f) | Jul 30, 2023 |
| Dell          | Latitude E7440              | Notebook    | [7509a5f756](https://linux-hardware.org/?probe=7509a5f756) | Jul 30, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [44937ea360](https://linux-hardware.org/?probe=44937ea360) | Jul 30, 2023 |
| System76      | Darter Pro                  | Notebook    | [0220d19f38](https://linux-hardware.org/?probe=0220d19f38) | Jul 30, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [96b197dffc](https://linux-hardware.org/?probe=96b197dffc) | Jul 29, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [d693783e7a](https://linux-hardware.org/?probe=d693783e7a) | Jul 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| HP            | 3646h                       | Desktop     | [e00952810b](https://linux-hardware.org/?probe=e00952810b) | Jul 29, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [59f0eb6b57](https://linux-hardware.org/?probe=59f0eb6b57) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [bc88e3dbae](https://linux-hardware.org/?probe=bc88e3dbae) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [cb2f78abf0](https://linux-hardware.org/?probe=cb2f78abf0) | Jul 28, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [b5fec7d5ff](https://linux-hardware.org/?probe=b5fec7d5ff) | Jul 28, 2023 |
| Dell          | Precision 3550              | Notebook    | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | Notebook    | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| System76      | Oryx Pro                    | Notebook    | [0ad8c1d8a7](https://linux-hardware.org/?probe=0ad8c1d8a7) | Jul 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [f4941e530b](https://linux-hardware.org/?probe=f4941e530b) | Jul 28, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [0e3aa83494](https://linux-hardware.org/?probe=0e3aa83494) | Jul 28, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [785fb534be](https://linux-hardware.org/?probe=785fb534be) | Jul 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [aac37c9ed6](https://linux-hardware.org/?probe=aac37c9ed6) | Jul 27, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [fba35d8a25](https://linux-hardware.org/?probe=fba35d8a25) | Jul 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Dell          | G15 5520                    | Notebook    | [7a5b503737](https://linux-hardware.org/?probe=7a5b503737) | Jul 27, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [0be5bf84c6](https://linux-hardware.org/?probe=0be5bf84c6) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4152e1f98e](https://linux-hardware.org/?probe=4152e1f98e) | Jul 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [619c6e4b99](https://linux-hardware.org/?probe=619c6e4b99) | Jul 27, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [b9bba11373](https://linux-hardware.org/?probe=b9bba11373) | Jul 27, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [23b23d59aa](https://linux-hardware.org/?probe=23b23d59aa) | Jul 27, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [2c300ff820](https://linux-hardware.org/?probe=2c300ff820) | Jul 27, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [b54bb52258](https://linux-hardware.org/?probe=b54bb52258) | Jul 27, 2023 |
| Dell          | 07PR60 A00                  | Desktop     | [67ef05bdd5](https://linux-hardware.org/?probe=67ef05bdd5) | Jul 27, 2023 |
| Intel         | H81                         | Desktop     | [6fa9f0cd2d](https://linux-hardware.org/?probe=6fa9f0cd2d) | Jul 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [65b9117b13](https://linux-hardware.org/?probe=65b9117b13) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [9920824f1f](https://linux-hardware.org/?probe=9920824f1f) | Jul 27, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [247f6d8816](https://linux-hardware.org/?probe=247f6d8816) | Jul 27, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [00e9bb8973](https://linux-hardware.org/?probe=00e9bb8973) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [22b2519a90](https://linux-hardware.org/?probe=22b2519a90) | Jul 26, 2023 |
| Dell          | 0YXG0N A00                  | Desktop     | [fb365f50a0](https://linux-hardware.org/?probe=fb365f50a0) | Jul 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [7e0e30c1cf](https://linux-hardware.org/?probe=7e0e30c1cf) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [b583a1fbee](https://linux-hardware.org/?probe=b583a1fbee) | Jul 26, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [c950e4d2f9](https://linux-hardware.org/?probe=c950e4d2f9) | Jul 25, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [3d3696e8fa](https://linux-hardware.org/?probe=3d3696e8fa) | Jul 25, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [e074ee90be](https://linux-hardware.org/?probe=e074ee90be) | Jul 25, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [b34b7fa5fb](https://linux-hardware.org/?probe=b34b7fa5fb) | Jul 25, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [25f155c61a](https://linux-hardware.org/?probe=25f155c61a) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [6b80b41fee](https://linux-hardware.org/?probe=6b80b41fee) | Jul 24, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [fa64a82283](https://linux-hardware.org/?probe=fa64a82283) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [88cfdb061d](https://linux-hardware.org/?probe=88cfdb061d) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [53bab7ac5e](https://linux-hardware.org/?probe=53bab7ac5e) | Jul 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [b2b0895194](https://linux-hardware.org/?probe=b2b0895194) | Jul 24, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [3d8ec4447b](https://linux-hardware.org/?probe=3d8ec4447b) | Jul 24, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [fe2ff0c21f](https://linux-hardware.org/?probe=fe2ff0c21f) | Jul 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2cd0946aba](https://linux-hardware.org/?probe=2cd0946aba) | Jul 23, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [3c39100c6f](https://linux-hardware.org/?probe=3c39100c6f) | Jul 23, 2023 |
| PC Special... | Standard                    | Notebook    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [50cf88ae28](https://linux-hardware.org/?probe=50cf88ae28) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bf4dff1328](https://linux-hardware.org/?probe=bf4dff1328) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Google        | Snappy                      | Notebook    | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [c78a2441ee](https://linux-hardware.org/?probe=c78a2441ee) | Jul 23, 2023 |
| Dell          | Latitude 3500               | Notebook    | [0755576e96](https://linux-hardware.org/?probe=0755576e96) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| MSI           | Boston                      | Desktop     | [d71010f2a7](https://linux-hardware.org/?probe=d71010f2a7) | Jul 22, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [05acc63d53](https://linux-hardware.org/?probe=05acc63d53) | Jul 22, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [46283ad18b](https://linux-hardware.org/?probe=46283ad18b) | Jul 22, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [f4cddb5e86](https://linux-hardware.org/?probe=f4cddb5e86) | Jul 22, 2023 |
| HP            | 829A                        | Mini pc     | [f768f29747](https://linux-hardware.org/?probe=f768f29747) | Jul 22, 2023 |
| Dell          | Latitude 5410               | Notebook    | [82217114b4](https://linux-hardware.org/?probe=82217114b4) | Jul 21, 2023 |
| Intel         | X99H                        | Desktop     | [474e78b162](https://linux-hardware.org/?probe=474e78b162) | Jul 21, 2023 |
| Dell          | Latitude 5520               | Notebook    | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [c3994db136](https://linux-hardware.org/?probe=c3994db136) | Jul 21, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [9a1d731109](https://linux-hardware.org/?probe=9a1d731109) | Jul 21, 2023 |
| Dell          | Precision 7530              | Notebook    | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d23dfad700](https://linux-hardware.org/?probe=d23dfad700) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [243f0a8cab](https://linux-hardware.org/?probe=243f0a8cab) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ebb1eed757](https://linux-hardware.org/?probe=ebb1eed757) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [f310abe0bb](https://linux-hardware.org/?probe=f310abe0bb) | Jul 20, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Dell          | Latitude E5270              | Notebook    | [9ea13fdc27](https://linux-hardware.org/?probe=9ea13fdc27) | Jul 20, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6e17b916ee](https://linux-hardware.org/?probe=6e17b916ee) | Jul 20, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [ac1a8eea0e](https://linux-hardware.org/?probe=ac1a8eea0e) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [fe36d4fde0](https://linux-hardware.org/?probe=fe36d4fde0) | Jul 19, 2023 |
| Schenker      | XMG NEO (CML/E20)           | Notebook    | [9f99e57705](https://linux-hardware.org/?probe=9f99e57705) | Jul 19, 2023 |
| ASUSTek       | K53E                        | Notebook    | [7fddec038e](https://linux-hardware.org/?probe=7fddec038e) | Jul 19, 2023 |
| Dell          | Latitude 7275               | Tablet      | [fdeba04a06](https://linux-hardware.org/?probe=fdeba04a06) | Jul 19, 2023 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [1dc0977942](https://linux-hardware.org/?probe=1dc0977942) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [8cb16d19aa](https://linux-hardware.org/?probe=8cb16d19aa) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1f57cb78e8](https://linux-hardware.org/?probe=1f57cb78e8) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d3413475e2](https://linux-hardware.org/?probe=d3413475e2) | Jul 18, 2023 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [098f2f58c7](https://linux-hardware.org/?probe=098f2f58c7) | Jul 18, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [9a9670d446](https://linux-hardware.org/?probe=9a9670d446) | Jul 18, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [37a65534a3](https://linux-hardware.org/?probe=37a65534a3) | Jul 18, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| HP            | 635                         | Notebook    | [500e11147e](https://linux-hardware.org/?probe=500e11147e) | Jul 18, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | Desktop     | [199e0d2e12](https://linux-hardware.org/?probe=199e0d2e12) | Jul 18, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [69f0859638](https://linux-hardware.org/?probe=69f0859638) | Jul 18, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [1426cda0a7](https://linux-hardware.org/?probe=1426cda0a7) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [0bbd5c68bb](https://linux-hardware.org/?probe=0bbd5c68bb) | Jul 17, 2023 |
| Dell          | Precision M6800             | Notebook    | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [25737bce66](https://linux-hardware.org/?probe=25737bce66) | Jul 17, 2023 |
| Lenovo        | ThinkPad X390 20Q1S67S00    | Notebook    | [be43004463](https://linux-hardware.org/?probe=be43004463) | Jul 17, 2023 |
| System76      | Serval WS                   | Notebook    | [a916a92726](https://linux-hardware.org/?probe=a916a92726) | Jul 17, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [55a5100039](https://linux-hardware.org/?probe=55a5100039) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [ad8f031cb2](https://linux-hardware.org/?probe=ad8f031cb2) | Jul 16, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [83175318ff](https://linux-hardware.org/?probe=83175318ff) | Jul 16, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [71e33b92ad](https://linux-hardware.org/?probe=71e33b92ad) | Jul 16, 2023 |
| Alienware     | 0XJKKD A01                  | Desktop     | [b47699e30d](https://linux-hardware.org/?probe=b47699e30d) | Jul 16, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [0063ae1936](https://linux-hardware.org/?probe=0063ae1936) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [e984f2562d](https://linux-hardware.org/?probe=e984f2562d) | Jul 16, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [437209972c](https://linux-hardware.org/?probe=437209972c) | Jul 15, 2023 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [91dbb2c969](https://linux-hardware.org/?probe=91dbb2c969) | Jul 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [32b56b85c4](https://linux-hardware.org/?probe=32b56b85c4) | Jul 15, 2023 |
| Dell          | G15 5510                    | Notebook    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| System76      | Pangolin                    | Notebook    | [486df7ead2](https://linux-hardware.org/?probe=486df7ead2) | Jul 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [4be00d26b2](https://linux-hardware.org/?probe=4be00d26b2) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | ENVY 15                     | Notebook    | [5cfb9d33bd](https://linux-hardware.org/?probe=5cfb9d33bd) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [21fc63e4dd](https://linux-hardware.org/?probe=21fc63e4dd) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [e53c63af42](https://linux-hardware.org/?probe=e53c63af42) | Jul 14, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [c1dba9e7b8](https://linux-hardware.org/?probe=c1dba9e7b8) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | Notebook    | [fb022ada73](https://linux-hardware.org/?probe=fb022ada73) | Jul 14, 2023 |
| HP            | 0B40h                       | Desktop     | [b452ab2c8d](https://linux-hardware.org/?probe=b452ab2c8d) | Jul 14, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [2afe11b7e4](https://linux-hardware.org/?probe=2afe11b7e4) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e84bf83ac1](https://linux-hardware.org/?probe=e84bf83ac1) | Jul 13, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [080a9244cf](https://linux-hardware.org/?probe=080a9244cf) | Jul 13, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [c82bb58705](https://linux-hardware.org/?probe=c82bb58705) | Jul 13, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | Notebook    | [5a675551df](https://linux-hardware.org/?probe=5a675551df) | Jul 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [089bfa3da7](https://linux-hardware.org/?probe=089bfa3da7) | Jul 13, 2023 |
| HP            | 0AA8h                       | Desktop     | [297e7364cb](https://linux-hardware.org/?probe=297e7364cb) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d4910e3f43](https://linux-hardware.org/?probe=d4910e3f43) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [7a9624e7cc](https://linux-hardware.org/?probe=7a9624e7cc) | Jul 12, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [2f5bf1f247](https://linux-hardware.org/?probe=2f5bf1f247) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| HP            | 0AA8h                       | Desktop     | [db16057ca8](https://linux-hardware.org/?probe=db16057ca8) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [801537f1d4](https://linux-hardware.org/?probe=801537f1d4) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [a95cc808e9](https://linux-hardware.org/?probe=a95cc808e9) | Jul 12, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [20e2180dc1](https://linux-hardware.org/?probe=20e2180dc1) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [d962460a5e](https://linux-hardware.org/?probe=d962460a5e) | Jul 12, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [2c4a8d9d63](https://linux-hardware.org/?probe=2c4a8d9d63) | Jul 12, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d08295d5f4](https://linux-hardware.org/?probe=d08295d5f4) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | Notebook    | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [2239b2744d](https://linux-hardware.org/?probe=2239b2744d) | Jul 11, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [556ef4473f](https://linux-hardware.org/?probe=556ef4473f) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1453f984c9](https://linux-hardware.org/?probe=1453f984c9) | Jul 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [ee2dc6ac7b](https://linux-hardware.org/?probe=ee2dc6ac7b) | Jul 11, 2023 |
| Biostar       | A960D+V2                    | Desktop     | [e6bfab517b](https://linux-hardware.org/?probe=e6bfab517b) | Jul 10, 2023 |
| Positivo      | POS-MIH61CF POSITIVO        | Desktop     | [02113d0b75](https://linux-hardware.org/?probe=02113d0b75) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [b581326f50](https://linux-hardware.org/?probe=b581326f50) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [5a7dbc5d7c](https://linux-hardware.org/?probe=5a7dbc5d7c) | Jul 10, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [293ddc3253](https://linux-hardware.org/?probe=293ddc3253) | Jul 10, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [a4650f89f7](https://linux-hardware.org/?probe=a4650f89f7) | Jul 10, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [3937b5d17a](https://linux-hardware.org/?probe=3937b5d17a) | Jul 09, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | Notebook    | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [0aea3d9721](https://linux-hardware.org/?probe=0aea3d9721) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | Notebook    | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [cf96aafbc0](https://linux-hardware.org/?probe=cf96aafbc0) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [1f88a40c05](https://linux-hardware.org/?probe=1f88a40c05) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [e1f22afb69](https://linux-hardware.org/?probe=e1f22afb69) | Jul 08, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [a34d0d8290](https://linux-hardware.org/?probe=a34d0d8290) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [12e3f9ecc7](https://linux-hardware.org/?probe=12e3f9ecc7) | Jul 07, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4e0acb57f9](https://linux-hardware.org/?probe=4e0acb57f9) | Jul 07, 2023 |
| HP            | 8918                        | Desktop     | [af366ea249](https://linux-hardware.org/?probe=af366ea249) | Jul 07, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [cae21c5121](https://linux-hardware.org/?probe=cae21c5121) | Jul 07, 2023 |
| ASUSTek       | N55SL                       | Notebook    | [1223d8b536](https://linux-hardware.org/?probe=1223d8b536) | Jul 07, 2023 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [e689bf355c](https://linux-hardware.org/?probe=e689bf355c) | Jul 07, 2023 |
| Panasonic     | FZ55-1                      | Notebook    | [4d12f02737](https://linux-hardware.org/?probe=4d12f02737) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [80164b7a44](https://linux-hardware.org/?probe=80164b7a44) | Jul 07, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [d122a1cedc](https://linux-hardware.org/?probe=d122a1cedc) | Jul 07, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e657049abf](https://linux-hardware.org/?probe=e657049abf) | Jul 06, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [b5157e26b1](https://linux-hardware.org/?probe=b5157e26b1) | Jul 06, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [88649252eb](https://linux-hardware.org/?probe=88649252eb) | Jul 06, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [f2a99b72dc](https://linux-hardware.org/?probe=f2a99b72dc) | Jul 06, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [495b6e6e4a](https://linux-hardware.org/?probe=495b6e6e4a) | Jul 06, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5ddd2d6cf0](https://linux-hardware.org/?probe=5ddd2d6cf0) | Jul 05, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [9971e8a3da](https://linux-hardware.org/?probe=9971e8a3da) | Jul 05, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f634e3942a](https://linux-hardware.org/?probe=f634e3942a) | Jul 05, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [8115e08748](https://linux-hardware.org/?probe=8115e08748) | Jul 05, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [0d9ce2b3d2](https://linux-hardware.org/?probe=0d9ce2b3d2) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [46e6f4b081](https://linux-hardware.org/?probe=46e6f4b081) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [6bf093ef61](https://linux-hardware.org/?probe=6bf093ef61) | Jul 05, 2023 |
| Unknown       | 1.31                        | Desktop     | [d34eb9e5d4](https://linux-hardware.org/?probe=d34eb9e5d4) | Jul 05, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [e2706e4472](https://linux-hardware.org/?probe=e2706e4472) | Jul 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [6013dcdf1e](https://linux-hardware.org/?probe=6013dcdf1e) | Jul 04, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [bc423a1cb9](https://linux-hardware.org/?probe=bc423a1cb9) | Jul 04, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [a99946b8f0](https://linux-hardware.org/?probe=a99946b8f0) | Jul 04, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [09dffdde54](https://linux-hardware.org/?probe=09dffdde54) | Jul 04, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [156f923a72](https://linux-hardware.org/?probe=156f923a72) | Jul 04, 2023 |
| Acer          | Aspire E1-470G              | Notebook    | [db4125a1c5](https://linux-hardware.org/?probe=db4125a1c5) | Jul 04, 2023 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [1c527ab64f](https://linux-hardware.org/?probe=1c527ab64f) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [dda9b242fd](https://linux-hardware.org/?probe=dda9b242fd) | Jul 03, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [baec2d3618](https://linux-hardware.org/?probe=baec2d3618) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a44e9e946f](https://linux-hardware.org/?probe=a44e9e946f) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [cc5348e995](https://linux-hardware.org/?probe=cc5348e995) | Jul 03, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b8ff99b486](https://linux-hardware.org/?probe=b8ff99b486) | Jul 03, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [1f5703db9b](https://linux-hardware.org/?probe=1f5703db9b) | Jul 03, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [e8ff92b585](https://linux-hardware.org/?probe=e8ff92b585) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [73015ee7be](https://linux-hardware.org/?probe=73015ee7be) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [6db9b5e42a](https://linux-hardware.org/?probe=6db9b5e42a) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [73d4fb6c33](https://linux-hardware.org/?probe=73d4fb6c33) | Jul 02, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [228db73d17](https://linux-hardware.org/?probe=228db73d17) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [3861c91dd4](https://linux-hardware.org/?probe=3861c91dd4) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [ab8898b9f3](https://linux-hardware.org/?probe=ab8898b9f3) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| Dell          | Precision 7510              | Notebook    | [46b90e25b0](https://linux-hardware.org/?probe=46b90e25b0) | Jul 02, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [38e6f08816](https://linux-hardware.org/?probe=38e6f08816) | Jul 02, 2023 |
| MSI           | GT72VR 6RD                  | Notebook    | [ea6887d031](https://linux-hardware.org/?probe=ea6887d031) | Jul 01, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [7797ece08f](https://linux-hardware.org/?probe=7797ece08f) | Jul 01, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [6ee8b4e949](https://linux-hardware.org/?probe=6ee8b4e949) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [18b6484d81](https://linux-hardware.org/?probe=18b6484d81) | Jul 01, 2023 |
| Dell          | Latitude 3500               | Notebook    | [8293ebc591](https://linux-hardware.org/?probe=8293ebc591) | Jul 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [a70ec8bdf1](https://linux-hardware.org/?probe=a70ec8bdf1) | Jul 01, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [446ce08df0](https://linux-hardware.org/?probe=446ce08df0) | Jun 30, 2023 |
| Gigabyte      | B550 UD AC                  | Desktop     | [7d7d37522c](https://linux-hardware.org/?probe=7d7d37522c) | Jun 30, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| Teclast       | F7 Plus                     | Notebook    | [cebd3b027c](https://linux-hardware.org/?probe=cebd3b027c) | Jun 30, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [59d1be1c5d](https://linux-hardware.org/?probe=59d1be1c5d) | Jun 30, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [878e617ba4](https://linux-hardware.org/?probe=878e617ba4) | Jun 30, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [cdb77bf9b6](https://linux-hardware.org/?probe=cdb77bf9b6) | Jun 30, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [d7dfcc4a38](https://linux-hardware.org/?probe=d7dfcc4a38) | Jun 30, 2023 |
| Positivo      | Mobile                      | Notebook    | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [568380fd59](https://linux-hardware.org/?probe=568380fd59) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [54013b2dfd](https://linux-hardware.org/?probe=54013b2dfd) | Jun 30, 2023 |
| Positivo      | H14CU02                     | Notebook    | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | Notebook    | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [323464eebb](https://linux-hardware.org/?probe=323464eebb) | Jun 28, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b1b4052442](https://linux-hardware.org/?probe=b1b4052442) | Jun 28, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [4054ebeac8](https://linux-hardware.org/?probe=4054ebeac8) | Jun 28, 2023 |
| MSI           | GE70 2PL                    | Notebook    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [cad43414b4](https://linux-hardware.org/?probe=cad43414b4) | Jun 27, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [0dda4e26da](https://linux-hardware.org/?probe=0dda4e26da) | Jun 27, 2023 |
| Dell          | Precision M6800             | Notebook    | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [975e5164c6](https://linux-hardware.org/?probe=975e5164c6) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | Notebook    | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [6b44c8513d](https://linux-hardware.org/?probe=6b44c8513d) | Jun 26, 2023 |
| Dell          | Precision M6800             | Notebook    | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | Notebook    | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1bd3b2b912](https://linux-hardware.org/?probe=1bd3b2b912) | Jun 25, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d436c6bcdf](https://linux-hardware.org/?probe=d436c6bcdf) | Jun 25, 2023 |
| HP            | Notebook                    | Notebook    | [ea00ce6c5b](https://linux-hardware.org/?probe=ea00ce6c5b) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [3907252056](https://linux-hardware.org/?probe=3907252056) | Jun 25, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [9888e54285](https://linux-hardware.org/?probe=9888e54285) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [8bd62ffdf1](https://linux-hardware.org/?probe=8bd62ffdf1) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [210d09c5dd](https://linux-hardware.org/?probe=210d09c5dd) | Jun 24, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [12f361cd8c](https://linux-hardware.org/?probe=12f361cd8c) | Jun 24, 2023 |
| System76      | Oryx Pro                    | Notebook    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [737204f453](https://linux-hardware.org/?probe=737204f453) | Jun 24, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [7f13c620bf](https://linux-hardware.org/?probe=7f13c620bf) | Jun 23, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [70954bb61e](https://linux-hardware.org/?probe=70954bb61e) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [510d2844bd](https://linux-hardware.org/?probe=510d2844bd) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [6e68a59ffb](https://linux-hardware.org/?probe=6e68a59ffb) | Jun 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [41a5a93ebb](https://linux-hardware.org/?probe=41a5a93ebb) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [082d9a4988](https://linux-hardware.org/?probe=082d9a4988) | Jun 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [5b2b7d4a7f](https://linux-hardware.org/?probe=5b2b7d4a7f) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| HP            | Notebook                    | Notebook    | [35b8a2a187](https://linux-hardware.org/?probe=35b8a2a187) | Jun 22, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [3c27e4a91d](https://linux-hardware.org/?probe=3c27e4a91d) | Jun 22, 2023 |
| Acidanther... | Mac-77EB7D7DAF985301 iMa... | All in one  | [1b2f8eb529](https://linux-hardware.org/?probe=1b2f8eb529) | Jun 22, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f7c2ec659b](https://linux-hardware.org/?probe=f7c2ec659b) | Jun 22, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [8634954b1c](https://linux-hardware.org/?probe=8634954b1c) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Intel         | H55                         | Desktop     | [545c7e42b3](https://linux-hardware.org/?probe=545c7e42b3) | Jun 21, 2023 |
| HP            | 89B5 A                      | Desktop     | [01e8a85a35](https://linux-hardware.org/?probe=01e8a85a35) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [b255195205](https://linux-hardware.org/?probe=b255195205) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Latitude E7240              | Notebook    | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [383aed9129](https://linux-hardware.org/?probe=383aed9129) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [3996492e80](https://linux-hardware.org/?probe=3996492e80) | Jun 20, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ec5318fcd1](https://linux-hardware.org/?probe=ec5318fcd1) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [4a18635ad7](https://linux-hardware.org/?probe=4a18635ad7) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [1d14950f1e](https://linux-hardware.org/?probe=1d14950f1e) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [46baecef13](https://linux-hardware.org/?probe=46baecef13) | Jun 20, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [796769b68a](https://linux-hardware.org/?probe=796769b68a) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [d2550efee5](https://linux-hardware.org/?probe=d2550efee5) | Jun 19, 2023 |
| System76      | Lemur Pro                   | Notebook    | [5074769fee](https://linux-hardware.org/?probe=5074769fee) | Jun 19, 2023 |
| Dell          | Latitude 7430               | Notebook    | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [0699537327](https://linux-hardware.org/?probe=0699537327) | Jun 19, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [26d77cd5be](https://linux-hardware.org/?probe=26d77cd5be) | Jun 19, 2023 |
| HP            | 829A                        | Mini pc     | [0ca8c646bb](https://linux-hardware.org/?probe=0ca8c646bb) | Jun 19, 2023 |
| MSI           | Raider GE66 12UGS           | Notebook    | [73b20b76a3](https://linux-hardware.org/?probe=73b20b76a3) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [fcbe9b509b](https://linux-hardware.org/?probe=fcbe9b509b) | Jun 18, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [ae0a1a134a](https://linux-hardware.org/?probe=ae0a1a134a) | Jun 18, 2023 |
| HP            | 8949 11                     | Desktop     | [bd6b95fc23](https://linux-hardware.org/?probe=bd6b95fc23) | Jun 18, 2023 |
| Biostar       | A320MH                      | Desktop     | [0c38427f58](https://linux-hardware.org/?probe=0c38427f58) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [e9dd574827](https://linux-hardware.org/?probe=e9dd574827) | Jun 18, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [c45aea7474](https://linux-hardware.org/?probe=c45aea7474) | Jun 18, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [6c2811bbf5](https://linux-hardware.org/?probe=6c2811bbf5) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | Notebook    | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c2f10ad55c](https://linux-hardware.org/?probe=c2f10ad55c) | Jun 17, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [10eb079da8](https://linux-hardware.org/?probe=10eb079da8) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | Notebook    | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2b3a058830](https://linux-hardware.org/?probe=2b3a058830) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| MSI           | H67MA-E35                   | Desktop     | [8b37f91738](https://linux-hardware.org/?probe=8b37f91738) | Jun 16, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | Notebook    | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| Dell          | Inspiron 5481               | Convertible | [4e24ca3b12](https://linux-hardware.org/?probe=4e24ca3b12) | Jun 16, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [da12f0d8e3](https://linux-hardware.org/?probe=da12f0d8e3) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [989287c8b1](https://linux-hardware.org/?probe=989287c8b1) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | Notebook    | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| System76      | Gazelle                     | Notebook    | [79c4236cdd](https://linux-hardware.org/?probe=79c4236cdd) | Jun 15, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [1bcfd50d08](https://linux-hardware.org/?probe=1bcfd50d08) | Jun 15, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [04b5148080](https://linux-hardware.org/?probe=04b5148080) | Jun 15, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [1e6fdd560b](https://linux-hardware.org/?probe=1e6fdd560b) | Jun 14, 2023 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [c7c537bd79](https://linux-hardware.org/?probe=c7c537bd79) | Jun 14, 2023 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [42e6a44062](https://linux-hardware.org/?probe=42e6a44062) | Jun 14, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | Notebook    | [667f0a20c1](https://linux-hardware.org/?probe=667f0a20c1) | Jun 14, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| System76      | Gazelle                     | Notebook    | [117f199b15](https://linux-hardware.org/?probe=117f199b15) | Jun 14, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [384ee8b42e](https://linux-hardware.org/?probe=384ee8b42e) | Jun 13, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [ad75eab286](https://linux-hardware.org/?probe=ad75eab286) | Jun 13, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d7c90a9c25](https://linux-hardware.org/?probe=d7c90a9c25) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b3303b8ed6](https://linux-hardware.org/?probe=b3303b8ed6) | Jun 13, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [b5294ee338](https://linux-hardware.org/?probe=b5294ee338) | Jun 13, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [5281ad2271](https://linux-hardware.org/?probe=5281ad2271) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [fff5e11f1c](https://linux-hardware.org/?probe=fff5e11f1c) | Jun 13, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [d730799661](https://linux-hardware.org/?probe=d730799661) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [0190531869](https://linux-hardware.org/?probe=0190531869) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [648161a6ff](https://linux-hardware.org/?probe=648161a6ff) | Jun 12, 2023 |
| ASUSTek       | Zenbook UP6502ZD_Q539ZD     | Convertible | [e2cd0602f8](https://linux-hardware.org/?probe=e2cd0602f8) | Jun 12, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [3e7cbbb991](https://linux-hardware.org/?probe=3e7cbbb991) | Jun 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [fd51db661f](https://linux-hardware.org/?probe=fd51db661f) | Jun 12, 2023 |
| Dell          | Latitude E7470              | Notebook    | [1253de4554](https://linux-hardware.org/?probe=1253de4554) | Jun 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [1f4d0ebdc1](https://linux-hardware.org/?probe=1f4d0ebdc1) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | Notebook    | [c09c4a0f69](https://linux-hardware.org/?probe=c09c4a0f69) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a9bb4cfb62](https://linux-hardware.org/?probe=a9bb4cfb62) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9c0f9bf219](https://linux-hardware.org/?probe=9c0f9bf219) | Jun 12, 2023 |
| Toshiba       | Satellite P55t-B            | Notebook    | [efc0f87778](https://linux-hardware.org/?probe=efc0f87778) | Jun 11, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [b74cc9dfff](https://linux-hardware.org/?probe=b74cc9dfff) | Jun 11, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [609c2921d3](https://linux-hardware.org/?probe=609c2921d3) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [86c52dcc7a](https://linux-hardware.org/?probe=86c52dcc7a) | Jun 11, 2023 |
| HP            | 89B5 A                      | Desktop     | [7bf638dc35](https://linux-hardware.org/?probe=7bf638dc35) | Jun 10, 2023 |
| MSI           | X99A GODLIKE GAMING         | Desktop     | [19511501c7](https://linux-hardware.org/?probe=19511501c7) | Jun 10, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [fd388e00c3](https://linux-hardware.org/?probe=fd388e00c3) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| HP            | 8949 11                     | Desktop     | [f5e1f4b6c9](https://linux-hardware.org/?probe=f5e1f4b6c9) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [cac24c37e5](https://linux-hardware.org/?probe=cac24c37e5) | Jun 10, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | Notebook    | [4160d59c4f](https://linux-hardware.org/?probe=4160d59c4f) | Jun 10, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [280baa2765](https://linux-hardware.org/?probe=280baa2765) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0f42ca8c95](https://linux-hardware.org/?probe=0f42ca8c95) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [50b022f065](https://linux-hardware.org/?probe=50b022f065) | Jun 09, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [b0daafa057](https://linux-hardware.org/?probe=b0daafa057) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1189f6696f](https://linux-hardware.org/?probe=1189f6696f) | Jun 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1256480fca](https://linux-hardware.org/?probe=1256480fca) | Jun 09, 2023 |
| ASUSTek       | M4A785G-HTPC                | Desktop     | [76304dfb4a](https://linux-hardware.org/?probe=76304dfb4a) | Jun 09, 2023 |
| AZW           | SEi                         | Desktop     | [2b085e7ed2](https://linux-hardware.org/?probe=2b085e7ed2) | Jun 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| Dell          | Latitude E6420              | Notebook    | [d408418ddd](https://linux-hardware.org/?probe=d408418ddd) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [975246674d](https://linux-hardware.org/?probe=975246674d) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [348173e172](https://linux-hardware.org/?probe=348173e172) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [35c7fcb130](https://linux-hardware.org/?probe=35c7fcb130) | Jun 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [896e71aaaf](https://linux-hardware.org/?probe=896e71aaaf) | Jun 08, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e127b4c2f4](https://linux-hardware.org/?probe=e127b4c2f4) | Jun 08, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [ee2b6b0279](https://linux-hardware.org/?probe=ee2b6b0279) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [70c409a2b8](https://linux-hardware.org/?probe=70c409a2b8) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| Machcreato... | 14                          | Notebook    | [d889b02b13](https://linux-hardware.org/?probe=d889b02b13) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [276844abe2](https://linux-hardware.org/?probe=276844abe2) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [d7d155d89d](https://linux-hardware.org/?probe=d7d155d89d) | Jun 07, 2023 |
| Dell          | Latitude E6420              | Notebook    | [620ca905d2](https://linux-hardware.org/?probe=620ca905d2) | Jun 07, 2023 |
| Dell          | Latitude 7200 2-in-1        | Tablet      | [4d60f57084](https://linux-hardware.org/?probe=4d60f57084) | Jun 07, 2023 |
| Machcreato... | 14                          | Notebook    | [f0a27a9f97](https://linux-hardware.org/?probe=f0a27a9f97) | Jun 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | Notebook    | [2834fee64f](https://linux-hardware.org/?probe=2834fee64f) | Jun 06, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [e6bf4ead0a](https://linux-hardware.org/?probe=e6bf4ead0a) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [804abce033](https://linux-hardware.org/?probe=804abce033) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [7c76016c9d](https://linux-hardware.org/?probe=7c76016c9d) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | Notebook    | [5dd18339de](https://linux-hardware.org/?probe=5dd18339de) | Jun 05, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [5a2d788a64](https://linux-hardware.org/?probe=5a2d788a64) | Jun 05, 2023 |
| HP            | 8949 11                     | Desktop     | [06bca18276](https://linux-hardware.org/?probe=06bca18276) | Jun 04, 2023 |
| ASUSTek       | M4N72-E                     | Desktop     | [51d39945ec](https://linux-hardware.org/?probe=51d39945ec) | Jun 04, 2023 |
| MSI           | A55M-E33                    | Desktop     | [336b7f877d](https://linux-hardware.org/?probe=336b7f877d) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [aafda7cf63](https://linux-hardware.org/?probe=aafda7cf63) | Jun 04, 2023 |
| Dell          | Inspiron 5437               | Notebook    | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Foxconn       | A74ML-K                     | Desktop     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| HP            | 8949 11                     | Desktop     | [f06749002f](https://linux-hardware.org/?probe=f06749002f) | Jun 03, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [5c280bbd6c](https://linux-hardware.org/?probe=5c280bbd6c) | Jun 03, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [3fc6303165](https://linux-hardware.org/?probe=3fc6303165) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [e0008bd879](https://linux-hardware.org/?probe=e0008bd879) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [979df15914](https://linux-hardware.org/?probe=979df15914) | Jun 03, 2023 |
| Dell          | Inspiron 7472               | Notebook    | [53b9d0dfa6](https://linux-hardware.org/?probe=53b9d0dfa6) | Jun 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9966a3f6d1](https://linux-hardware.org/?probe=9966a3f6d1) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b3b398ba61](https://linux-hardware.org/?probe=b3b398ba61) | Jun 03, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [2354c37832](https://linux-hardware.org/?probe=2354c37832) | Jun 02, 2023 |
| MSI           | Prestige 16 A12UD           | Notebook    | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [b86be4f1de](https://linux-hardware.org/?probe=b86be4f1de) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a8f8239e40](https://linux-hardware.org/?probe=a8f8239e40) | Jun 02, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [7f2c514dff](https://linux-hardware.org/?probe=7f2c514dff) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [1de529b11c](https://linux-hardware.org/?probe=1de529b11c) | Jun 01, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [df7287f2c8](https://linux-hardware.org/?probe=df7287f2c8) | Jun 01, 2023 |
| HP            | 212A                        | Desktop     | [a0e56b03e2](https://linux-hardware.org/?probe=a0e56b03e2) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| System76      | Adder WS                    | Notebook    | [5cfa553a01](https://linux-hardware.org/?probe=5cfa553a01) | May 31, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [a494d94087](https://linux-hardware.org/?probe=a494d94087) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [cc24e32ab1](https://linux-hardware.org/?probe=cc24e32ab1) | May 30, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [ca4e5a8f82](https://linux-hardware.org/?probe=ca4e5a8f82) | May 30, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [cb78f83d80](https://linux-hardware.org/?probe=cb78f83d80) | May 30, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [2334995ee9](https://linux-hardware.org/?probe=2334995ee9) | May 30, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4f41d4f16f](https://linux-hardware.org/?probe=4f41d4f16f) | May 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [907448944d](https://linux-hardware.org/?probe=907448944d) | May 30, 2023 |
| AZW           | GTR V01                     | Mini pc     | [9144d0218a](https://linux-hardware.org/?probe=9144d0218a) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [1793fc9d72](https://linux-hardware.org/?probe=1793fc9d72) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [83f869ee2a](https://linux-hardware.org/?probe=83f869ee2a) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [23af21bb34](https://linux-hardware.org/?probe=23af21bb34) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [94fda2dea0](https://linux-hardware.org/?probe=94fda2dea0) | May 30, 2023 |
| Toshiba       | Satellite P755              | Notebook    | [5dc8f46db5](https://linux-hardware.org/?probe=5dc8f46db5) | May 29, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [650fb21fd0](https://linux-hardware.org/?probe=650fb21fd0) | May 29, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | 0NM64V A01                  | Desktop     | [a109a924f0](https://linux-hardware.org/?probe=a109a924f0) | May 29, 2023 |
| ASUSTek       | TUF Gaming H770-PRO WIFI    | Desktop     | [6729d5ffa7](https://linux-hardware.org/?probe=6729d5ffa7) | May 29, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8b1445b47c](https://linux-hardware.org/?probe=8b1445b47c) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [06318d2354](https://linux-hardware.org/?probe=06318d2354) | May 29, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [c24eb2f7dd](https://linux-hardware.org/?probe=c24eb2f7dd) | May 29, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | Notebook    | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [2f1017a58e](https://linux-hardware.org/?probe=2f1017a58e) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [d6de84e0c6](https://linux-hardware.org/?probe=d6de84e0c6) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [5624c5b0e8](https://linux-hardware.org/?probe=5624c5b0e8) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [2522fb534f](https://linux-hardware.org/?probe=2522fb534f) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [439a2f1c9e](https://linux-hardware.org/?probe=439a2f1c9e) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | Notebook    | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| AZW           | EQ                          | Desktop     | [8e6c18ebbb](https://linux-hardware.org/?probe=8e6c18ebbb) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| AZW           | EQ                          | Desktop     | [98e5ea581c](https://linux-hardware.org/?probe=98e5ea581c) | May 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [46460561e1](https://linux-hardware.org/?probe=46460561e1) | May 27, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [b2672eb1db](https://linux-hardware.org/?probe=b2672eb1db) | May 27, 2023 |
| Lenovo        | Yoga 700-11ISK 80QE         | Notebook    | [149dfccfe7](https://linux-hardware.org/?probe=149dfccfe7) | May 27, 2023 |
| Google        | Kohaku                      | Notebook    | [2b46417afd](https://linux-hardware.org/?probe=2b46417afd) | May 27, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [07b70ac9e5](https://linux-hardware.org/?probe=07b70ac9e5) | May 27, 2023 |
| System76      | Galago Pro                  | Notebook    | [51cc594a01](https://linux-hardware.org/?probe=51cc594a01) | May 27, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [8d5c73bd4d](https://linux-hardware.org/?probe=8d5c73bd4d) | May 27, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ea5ba11b48](https://linux-hardware.org/?probe=ea5ba11b48) | May 27, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [ce5179659e](https://linux-hardware.org/?probe=ce5179659e) | May 26, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c3af0f3242](https://linux-hardware.org/?probe=c3af0f3242) | May 26, 2023 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [9b2b467879](https://linux-hardware.org/?probe=9b2b467879) | May 26, 2023 |
| HP            | 0AA4h                       | Desktop     | [41ec821e77](https://linux-hardware.org/?probe=41ec821e77) | May 26, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [8c61dd5381](https://linux-hardware.org/?probe=8c61dd5381) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [92223e639f](https://linux-hardware.org/?probe=92223e639f) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9a58438669](https://linux-hardware.org/?probe=9a58438669) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [a12e26f683](https://linux-hardware.org/?probe=a12e26f683) | May 26, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [6d237fdf95](https://linux-hardware.org/?probe=6d237fdf95) | May 26, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [248bd35ba0](https://linux-hardware.org/?probe=248bd35ba0) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [486d6ac497](https://linux-hardware.org/?probe=486d6ac497) | May 25, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [7b19816353](https://linux-hardware.org/?probe=7b19816353) | May 25, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | Notebook    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [a8b595f03c](https://linux-hardware.org/?probe=a8b595f03c) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| Dell          | Precision 5470              | Notebook    | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [41755306e6](https://linux-hardware.org/?probe=41755306e6) | May 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [31ea0c4ab8](https://linux-hardware.org/?probe=31ea0c4ab8) | May 24, 2023 |
| Dell          | G15 5511                    | Notebook    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [f339d13a59](https://linux-hardware.org/?probe=f339d13a59) | May 24, 2023 |
| HP            | 212A                        | Desktop     | [87b3c9809f](https://linux-hardware.org/?probe=87b3c9809f) | May 23, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [8604115d8b](https://linux-hardware.org/?probe=8604115d8b) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | Notebook    | [90df3b7bfa](https://linux-hardware.org/?probe=90df3b7bfa) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | Notebook    | [0f0ad128aa](https://linux-hardware.org/?probe=0f0ad128aa) | May 23, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | Notebook    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [c2b6ba6654](https://linux-hardware.org/?probe=c2b6ba6654) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [da701ce37f](https://linux-hardware.org/?probe=da701ce37f) | May 23, 2023 |
| Acidanther... | Mac-77EB7D7DAF985301 iMa... | All in one  | [b021476220](https://linux-hardware.org/?probe=b021476220) | May 23, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [77ccb1431b](https://linux-hardware.org/?probe=77ccb1431b) | May 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e781194fb3](https://linux-hardware.org/?probe=e781194fb3) | May 23, 2023 |
| Lenovo        | Unknown                     | Notebook    | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [8226c82b49](https://linux-hardware.org/?probe=8226c82b49) | May 21, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [6a8e6201be](https://linux-hardware.org/?probe=6a8e6201be) | May 21, 2023 |
| Lenovo        | Unknown                     | Notebook    | [1288108e10](https://linux-hardware.org/?probe=1288108e10) | May 21, 2023 |
| Unknown       | V00                         | Mini pc     | [7b8747aad5](https://linux-hardware.org/?probe=7b8747aad5) | May 21, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0df526f042](https://linux-hardware.org/?probe=0df526f042) | May 21, 2023 |
| Dell          | G15 5511                    | Notebook    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| Toshiba       | Satellite L855D             | Notebook    | [5be0280c53](https://linux-hardware.org/?probe=5be0280c53) | May 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [fb1832d859](https://linux-hardware.org/?probe=fb1832d859) | May 20, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [4c5dce3a01](https://linux-hardware.org/?probe=4c5dce3a01) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [51f87ac309](https://linux-hardware.org/?probe=51f87ac309) | May 20, 2023 |
| Gigabyte      | B660M AORUS PRO DDR4        | Desktop     | [6a3afbb593](https://linux-hardware.org/?probe=6a3afbb593) | May 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [1acd938f30](https://linux-hardware.org/?probe=1acd938f30) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [7384b29d21](https://linux-hardware.org/?probe=7384b29d21) | May 20, 2023 |
| Samsung       | DeskTop System              | Desktop     | [0f49fcc9e8](https://linux-hardware.org/?probe=0f49fcc9e8) | May 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [e16a632eca](https://linux-hardware.org/?probe=e16a632eca) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a5fdda0f63](https://linux-hardware.org/?probe=a5fdda0f63) | May 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [2cde0cc93d](https://linux-hardware.org/?probe=2cde0cc93d) | May 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a100e90e0b](https://linux-hardware.org/?probe=a100e90e0b) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [d51c5680e8](https://linux-hardware.org/?probe=d51c5680e8) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [986792e4f0](https://linux-hardware.org/?probe=986792e4f0) | May 19, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [75d3691dae](https://linux-hardware.org/?probe=75d3691dae) | May 18, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [08df098150](https://linux-hardware.org/?probe=08df098150) | May 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [994adfd229](https://linux-hardware.org/?probe=994adfd229) | May 18, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [e28f96322d](https://linux-hardware.org/?probe=e28f96322d) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [9d2439e8d7](https://linux-hardware.org/?probe=9d2439e8d7) | May 18, 2023 |
| Reliance C... | R141TL5                     | Notebook    | [a21525c003](https://linux-hardware.org/?probe=a21525c003) | May 18, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [06003cbcc2](https://linux-hardware.org/?probe=06003cbcc2) | May 18, 2023 |
| PS            | X570 Pro4                   | Desktop     | [cde38918e6](https://linux-hardware.org/?probe=cde38918e6) | May 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [a1cb84300e](https://linux-hardware.org/?probe=a1cb84300e) | May 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [620177b4fa](https://linux-hardware.org/?probe=620177b4fa) | May 17, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| Dell          | Inspiron 14 5408            | Notebook    | [c1853f7df2](https://linux-hardware.org/?probe=c1853f7df2) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [dd1e6376c2](https://linux-hardware.org/?probe=dd1e6376c2) | May 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63c991635f](https://linux-hardware.org/?probe=63c991635f) | May 17, 2023 |
| Google        | Blorb                       | Notebook    | [7537bc5890](https://linux-hardware.org/?probe=7537bc5890) | May 17, 2023 |
| Dell          | 048DY8 A01                  | Desktop     | [aaf390dad1](https://linux-hardware.org/?probe=aaf390dad1) | May 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [add6bcd4f7](https://linux-hardware.org/?probe=add6bcd4f7) | May 16, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [aa87f447d5](https://linux-hardware.org/?probe=aa87f447d5) | May 16, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2616bd6b98](https://linux-hardware.org/?probe=2616bd6b98) | May 16, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | Desktop     | [af5b595698](https://linux-hardware.org/?probe=af5b595698) | May 16, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [9a08def3ae](https://linux-hardware.org/?probe=9a08def3ae) | May 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [d35caae2b6](https://linux-hardware.org/?probe=d35caae2b6) | May 15, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [9f4a8a37c0](https://linux-hardware.org/?probe=9f4a8a37c0) | May 15, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [829665d7bf](https://linux-hardware.org/?probe=829665d7bf) | May 15, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a7c2953571](https://linux-hardware.org/?probe=a7c2953571) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [681e1f8c61](https://linux-hardware.org/?probe=681e1f8c61) | May 15, 2023 |
| HP            | 3398                        | Desktop     | [7339f433ef](https://linux-hardware.org/?probe=7339f433ef) | May 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e21cdf9e37](https://linux-hardware.org/?probe=e21cdf9e37) | May 15, 2023 |
| MSI           | H61M-P23                    | Desktop     | [e6b643867b](https://linux-hardware.org/?probe=e6b643867b) | May 15, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [9be042ca8a](https://linux-hardware.org/?probe=9be042ca8a) | May 14, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [38a459c2e0](https://linux-hardware.org/?probe=38a459c2e0) | May 14, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [a431f34e2b](https://linux-hardware.org/?probe=a431f34e2b) | May 14, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [3d3bfc28a6](https://linux-hardware.org/?probe=3d3bfc28a6) | May 14, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c74505560b](https://linux-hardware.org/?probe=c74505560b) | May 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [f67b1d428b](https://linux-hardware.org/?probe=f67b1d428b) | May 14, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [e48ff4432d](https://linux-hardware.org/?probe=e48ff4432d) | May 14, 2023 |
| MSI           | H110I PRO                   | Desktop     | [1224d45c07](https://linux-hardware.org/?probe=1224d45c07) | May 14, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [88a88bec15](https://linux-hardware.org/?probe=88a88bec15) | May 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [effc7c876e](https://linux-hardware.org/?probe=effc7c876e) | May 14, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [d26275a2de](https://linux-hardware.org/?probe=d26275a2de) | May 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [676c25e644](https://linux-hardware.org/?probe=676c25e644) | May 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| Dell          | G7 7700                     | Notebook    | [6568ba5b4d](https://linux-hardware.org/?probe=6568ba5b4d) | May 13, 2023 |
| Gigabyte      | P34V7                       | Notebook    | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1d4c35daa6](https://linux-hardware.org/?probe=1d4c35daa6) | May 13, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [275f194797](https://linux-hardware.org/?probe=275f194797) | May 13, 2023 |
| System76      | Galago Pro                  | Notebook    | [a30efb5622](https://linux-hardware.org/?probe=a30efb5622) | May 13, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [9a5e07f865](https://linux-hardware.org/?probe=9a5e07f865) | May 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed810bd154](https://linux-hardware.org/?probe=ed810bd154) | May 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [415306aabf](https://linux-hardware.org/?probe=415306aabf) | May 12, 2023 |
| System76      | Gazelle                     | Notebook    | [bd4e912b20](https://linux-hardware.org/?probe=bd4e912b20) | May 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [7dd8e30770](https://linux-hardware.org/?probe=7dd8e30770) | May 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [d6598957ff](https://linux-hardware.org/?probe=d6598957ff) | May 12, 2023 |
| Lenovo        | ThinkPad T590 20N4002WGE    | Notebook    | [6caedd8a7b](https://linux-hardware.org/?probe=6caedd8a7b) | May 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [cf7c801d5c](https://linux-hardware.org/?probe=cf7c801d5c) | May 12, 2023 |
| ASUSTek       | ZenBook UX431FN             | Notebook    | [ee40bf2168](https://linux-hardware.org/?probe=ee40bf2168) | May 12, 2023 |
| System76      | Gazelle                     | Notebook    | [83ef9e6d2d](https://linux-hardware.org/?probe=83ef9e6d2d) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [ffffd119fb](https://linux-hardware.org/?probe=ffffd119fb) | May 12, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6ad3215735](https://linux-hardware.org/?probe=6ad3215735) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [f54531cd16](https://linux-hardware.org/?probe=f54531cd16) | May 11, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [eefa55009a](https://linux-hardware.org/?probe=eefa55009a) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a7155be531](https://linux-hardware.org/?probe=a7155be531) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [f46fe8b9ee](https://linux-hardware.org/?probe=f46fe8b9ee) | May 11, 2023 |
| HP            | 158A                        | Desktop     | [a085c7a516](https://linux-hardware.org/?probe=a085c7a516) | May 11, 2023 |
| Dell          | 0T2HR0 A01                  | Desktop     | [96c6b065e8](https://linux-hardware.org/?probe=96c6b065e8) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [5d50ca41ef](https://linux-hardware.org/?probe=5d50ca41ef) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [0e8fab037b](https://linux-hardware.org/?probe=0e8fab037b) | May 11, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [96310a4cfe](https://linux-hardware.org/?probe=96310a4cfe) | May 11, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [ed6a0c4e82](https://linux-hardware.org/?probe=ed6a0c4e82) | May 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4276c0fd28](https://linux-hardware.org/?probe=4276c0fd28) | May 11, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [30036be67b](https://linux-hardware.org/?probe=30036be67b) | May 10, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [8ba2d54929](https://linux-hardware.org/?probe=8ba2d54929) | May 10, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [ceebdc263a](https://linux-hardware.org/?probe=ceebdc263a) | May 10, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [5f3555ab64](https://linux-hardware.org/?probe=5f3555ab64) | May 10, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [e1e22ae448](https://linux-hardware.org/?probe=e1e22ae448) | May 10, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [6d6dffc4fe](https://linux-hardware.org/?probe=6d6dffc4fe) | May 10, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [1fe1a8fcd2](https://linux-hardware.org/?probe=1fe1a8fcd2) | May 09, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [695a40ecc7](https://linux-hardware.org/?probe=695a40ecc7) | May 09, 2023 |
| MSI           | GL65 Leopard 10SCSR         | Notebook    | [4d9a7df494](https://linux-hardware.org/?probe=4d9a7df494) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [28e1a5c2e9](https://linux-hardware.org/?probe=28e1a5c2e9) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [fed7278850](https://linux-hardware.org/?probe=fed7278850) | May 09, 2023 |
| Lenovo        | ThinkPad T410 2522AA6       | Notebook    | [82755e3688](https://linux-hardware.org/?probe=82755e3688) | May 08, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [c40e865226](https://linux-hardware.org/?probe=c40e865226) | May 08, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [95dbf74d72](https://linux-hardware.org/?probe=95dbf74d72) | May 08, 2023 |
| ASUSTek       | M3N WS                      | Desktop     | [fb7920c5f9](https://linux-hardware.org/?probe=fb7920c5f9) | May 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [51eba04846](https://linux-hardware.org/?probe=51eba04846) | May 08, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [da1c6920b6](https://linux-hardware.org/?probe=da1c6920b6) | May 08, 2023 |
| Alienware     | Area-51m R2 A00             | Notebook    | [3cc417c9d9](https://linux-hardware.org/?probe=3cc417c9d9) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [6bc581f37c](https://linux-hardware.org/?probe=6bc581f37c) | May 08, 2023 |
| ASUSTek       | P8P67-M                     | Desktop     | [386d7c9de4](https://linux-hardware.org/?probe=386d7c9de4) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | Desktop     | [1945ccd76d](https://linux-hardware.org/?probe=1945ccd76d) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [894029cc14](https://linux-hardware.org/?probe=894029cc14) | May 07, 2023 |
| Notebook      | N141CU                      | Notebook    | [535b4ca746](https://linux-hardware.org/?probe=535b4ca746) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | Desktop     | [a5c758152f](https://linux-hardware.org/?probe=a5c758152f) | May 07, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [8c5b603452](https://linux-hardware.org/?probe=8c5b603452) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [619dc53d25](https://linux-hardware.org/?probe=619dc53d25) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [078d3ae45f](https://linux-hardware.org/?probe=078d3ae45f) | May 06, 2023 |
| Notebook      | P15SM                       | Notebook    | [dcea4ec037](https://linux-hardware.org/?probe=dcea4ec037) | May 06, 2023 |
| Packard Be... | EasyNote LM85               | Notebook    | [d37b9e6687](https://linux-hardware.org/?probe=d37b9e6687) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9001HUS    | Notebook    | [4bad3ee37e](https://linux-hardware.org/?probe=4bad3ee37e) | May 06, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [ecb5894e85](https://linux-hardware.org/?probe=ecb5894e85) | May 06, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [7c3b61fab9](https://linux-hardware.org/?probe=7c3b61fab9) | May 05, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [fbe46d0c6e](https://linux-hardware.org/?probe=fbe46d0c6e) | May 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.2.6-76060206-generic   | 816       | 22.57%  |
| 6.0.12-76060006-generic  | 474       | 13.11%  |
| 5.19.0-76051900-generic  | 446       | 12.33%  |
| 5.17.5-76051705-generic  | 417       | 11.53%  |
| 6.0.6-76060006-generic   | 300       | 8.3%    |
| 5.18.10-76051810-generic | 207       | 5.72%   |
| 5.17.15-76051715-generic | 185       | 5.12%   |
| 6.4.6-76060406-generic   | 151       | 4.18%   |
| 6.2.0-76060200-generic   | 121       | 3.35%   |
| 5.16.19-76051619-generic | 121       | 3.35%   |
| 6.0.2-76060002-generic   | 92        | 2.54%   |
| 6.1.11-76060111-generic  | 90        | 2.49%   |
| 5.19.16-76051916-generic | 43        | 1.19%   |
| 6.0.3-76060003-generic   | 39        | 1.08%   |
| 6.3.7-060307-generic     | 5         | 0.14%   |
| 6.3.4-060304-generic     | 3         | 0.08%   |
| 6.1.0-1006-oem           | 3         | 0.08%   |
| 5.16.15-76051615-generic | 3         | 0.08%   |
| 6.4.0-060400-generic     | 2         | 0.06%   |
| 6.2.11-060211-generic    | 2         | 0.06%   |
| 6.1.8-060108-generic     | 2         | 0.06%   |
| 6.1.0-x64v1-xanmod1      | 2         | 0.06%   |
| 6.0.9-060009-generic     | 2         | 0.06%   |
| 6.0.2-x64v1-xanmod1      | 2         | 0.06%   |
| 5.19.12-xanmod1          | 2         | 0.06%   |
| 5.17.7-051707-generic    | 2         | 0.06%   |
| 5.17.5-051705-generic    | 2         | 0.06%   |
| 6.5.0-rc2                | 1         | 0.03%   |
| 6.4.8-x64v3-xanmod1      | 1         | 0.03%   |
| 6.4.7-surface            | 1         | 0.03%   |
| 6.4.5-x64v2-xanmod1      | 1         | 0.03%   |
| 6.4.3-060403-generic     | 1         | 0.03%   |
| 6.4.2-surface            | 1         | 0.03%   |
| 6.4.12-2-liquorix-amd64  | 1         | 0.03%   |
| 6.3.9-x64v3-xanmod1      | 1         | 0.03%   |
| 6.3.9-060309-generic     | 1         | 0.03%   |
| 6.3.8-x64v1-xanmod1      | 1         | 0.03%   |
| 6.3.8-1-liquorix-amd64   | 1         | 0.03%   |
| 6.3.5-x64v1-xanmod1      | 1         | 0.03%   |
| 6.3.4-x64v1-xanmod1      | 1         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 817       | 22.6%   |
| 6.0.12  | 475       | 13.14%  |
| 5.19.0  | 450       | 12.45%  |
| 5.17.5  | 420       | 11.62%  |
| 6.0.6   | 301       | 8.33%   |
| 5.18.10 | 207       | 5.73%   |
| 5.17.15 | 185       | 5.12%   |
| 6.4.6   | 151       | 4.18%   |
| 6.2.0   | 121       | 3.35%   |
| 5.16.19 | 121       | 3.35%   |
| 6.0.2   | 95        | 2.63%   |
| 6.1.11  | 91        | 2.52%   |
| 5.19.16 | 43        | 1.19%   |
| 6.0.3   | 39        | 1.08%   |
| 6.1.0   | 6         | 0.17%   |
| 5.15.0  | 6         | 0.17%   |
| 6.3.7   | 5         | 0.14%   |
| 6.3.4   | 4         | 0.11%   |
| 6.1.8   | 3         | 0.08%   |
| 6.0.9   | 3         | 0.08%   |
| 5.16.15 | 3         | 0.08%   |
| 6.4.0   | 2         | 0.06%   |
| 6.3.9   | 2         | 0.06%   |
| 6.3.8   | 2         | 0.06%   |
| 6.3.1   | 2         | 0.06%   |
| 6.2.9   | 2         | 0.06%   |
| 6.2.2   | 2         | 0.06%   |
| 6.2.11  | 2         | 0.06%   |
| 6.1.9   | 2         | 0.06%   |
| 6.1.12  | 2         | 0.06%   |
| 6.0.0   | 2         | 0.06%   |
| 5.19.12 | 2         | 0.06%   |
| 5.18.0  | 2         | 0.06%   |
| 5.17.7  | 2         | 0.06%   |
| 5.17.0  | 2         | 0.06%   |
| 6.5.0   | 1         | 0.03%   |
| 6.4.8   | 1         | 0.03%   |
| 6.4.7   | 1         | 0.03%   |
| 6.4.5   | 1         | 0.03%   |
| 6.4.3   | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 937       | 26.36%  |
| 6.0     | 889       | 25.01%  |
| 5.17    | 601       | 16.91%  |
| 5.19    | 495       | 13.93%  |
| 5.18    | 213       | 5.99%   |
| 6.4     | 158       | 4.45%   |
| 5.16    | 125       | 3.52%   |
| 6.1     | 108       | 3.04%   |
| 6.3     | 17        | 0.48%   |
| 5.15    | 9         | 0.25%   |
| 6.5     | 1         | 0.03%   |
| 5.4     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3255      | 99.88%  |
| aarch64 | 4         | 0.12%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 3169      | 96.91%  |
| KDE5            | 44        | 1.35%   |
| Unknown         | 20        | 0.61%   |
| X-Cinnamon      | 14        | 0.43%   |
| GNOME Flashback | 6         | 0.18%   |
| Unity           | 4         | 0.12%   |
| LXQt            | 4         | 0.12%   |
| Cinnamon        | 3         | 0.09%   |
| XFCE            | 2         | 0.06%   |
| MATE            | 2         | 0.06%   |
| i3              | 2         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3120      | 95.12%  |
| Wayland | 141       | 4.3%    |
| Unknown | 14        | 0.43%   |
| Tty     | 5         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2458      | 74.92%  |
| GDM3    | 804       | 24.5%   |
| SDDM    | 10        | 0.3%    |
| GDM     | 7         | 0.21%   |
| LightDM | 2         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1964      | 59.79%  |
| en_GB   | 216       | 6.58%   |
| pt_BR   | 179       | 5.45%   |
| de_DE   | 147       | 4.47%   |
| C       | 102       | 3.11%   |
| en_AU   | 73        | 2.22%   |
| it_IT   | 65        | 1.98%   |
| en_CA   | 62        | 1.89%   |
| fr_FR   | 59        | 1.8%    |
| es_ES   | 43        | 1.31%   |
| ru_RU   | 36        | 1.1%    |
| pl_PL   | 33        | 1%      |
| Unknown | 20        | 0.61%   |
| sv_SE   | 19        | 0.58%   |
| nb_NO   | 19        | 0.58%   |
| pt_PT   | 16        | 0.49%   |
| nl_NL   | 15        | 0.46%   |
| fi_FI   | 15        | 0.46%   |
| en_IN   | 13        | 0.4%    |
| es_MX   | 12        | 0.37%   |
| es_CL   | 12        | 0.37%   |
| en_IE   | 12        | 0.37%   |
| ja_JP   | 10        | 0.3%    |
| en_NZ   | 10        | 0.3%    |
| de_CH   | 10        | 0.3%    |
| da_DK   | 10        | 0.3%    |
| fr_CA   | 9         | 0.27%   |
| es_AR   | 9         | 0.27%   |
| de_AT   | 9         | 0.27%   |
| en_ZA   | 8         | 0.24%   |
| en_DK   | 8         | 0.24%   |
| tr_TR   | 7         | 0.21%   |
| cs_CZ   | 7         | 0.21%   |
| fr_CH   | 4         | 0.12%   |
| fr_BE   | 4         | 0.12%   |
| es_CO   | 4         | 0.12%   |
| ro_RO   | 3         | 0.09%   |
| zh_TW   | 2         | 0.06%   |
| zh_CN   | 2         | 0.06%   |
| sk_SK   | 2         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2501      | 76.25%  |
| EFI  | 779       | 23.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3093      | 94.59%  |
| Btrfs   | 96        | 2.94%   |
| Overlay | 66        | 2.02%   |
| Xfs     | 10        | 0.31%   |
| Zfs     | 3         | 0.09%   |
| Tmpfs   | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2439      | 74.34%  |
| GPT     | 790       | 24.08%  |
| MBR     | 52        | 1.58%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3164      | 96.79%  |
| Yes       | 105       | 3.21%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2941      | 89.97%  |
| Yes       | 328       | 10.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 580       | 17.8%   |
| Lenovo                  | 465       | 14.27%  |
| Dell                    | 408       | 12.52%  |
| Hewlett-Packard         | 372       | 11.41%  |
| MSI                     | 241       | 7.39%   |
| Gigabyte Technology     | 211       | 6.47%   |
| Apple                   | 179       | 5.49%   |
| Acer                    | 151       | 4.63%   |
| ASRock                  | 99        | 3.04%   |
| System76                | 74        | 2.27%   |
| Intel                   | 41        | 1.26%   |
| Samsung Electronics     | 36        | 1.1%    |
| Toshiba                 | 35        | 1.07%   |
| HUAWEI                  | 27        | 0.83%   |
| Alienware               | 24        | 0.74%   |
| Microsoft               | 20        | 0.61%   |
| Unknown                 | 18        | 0.55%   |
| Google                  | 17        | 0.52%   |
| Fujitsu                 | 17        | 0.52%   |
| Notebook                | 13        | 0.4%    |
| Sony                    | 11        | 0.34%   |
| Positivo                | 11        | 0.34%   |
| AZW                     | 11        | 0.34%   |
| GPU Company             | 10        | 0.31%   |
| BESSTAR Tech            | 10        | 0.31%   |
| Razer                   | 9         | 0.28%   |
| Timi                    | 8         | 0.25%   |
| Framework               | 7         | 0.21%   |
| Supermicro              | 6         | 0.18%   |
| MACHINIST               | 6         | 0.18%   |
| HONOR                   | 6         | 0.18%   |
| Avell High Performance  | 6         | 0.18%   |
| Pegatron                | 5         | 0.15%   |
| Foxconn                 | 5         | 0.15%   |
| Biostar                 | 5         | 0.15%   |
| ZOTAC                   | 4         | 0.12%   |
| TUXEDO                  | 4         | 0.12%   |
| Raspberry Pi Foundation | 4         | 0.12%   |
| PC Specialist           | 4         | 0.12%   |
| NZXT                    | 4         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 25        | 0.77%   |
| ASUS All Series                | 21        | 0.64%   |
| System76 Oryx Pro              | 17        | 0.52%   |
| ASUS ROG STRIX B550-F GAMING   | 15        | 0.46%   |
| System76 Lemur Pro             | 14        | 0.43%   |
| Apple MacBookPro12,1           | 12        | 0.37%   |
| Apple MacBookAir7,2            | 12        | 0.37%   |
| System76 Gazelle               | 11        | 0.34%   |
| ASUS ROG STRIX B550-I GAMING   | 10        | 0.31%   |
| ASUS ROG STRIX B450-F GAMING   | 10        | 0.31%   |
| HP Dev One Notebook PC         | 9         | 0.28%   |
| Gigabyte X570 AORUS ELITE      | 9         | 0.28%   |
| Apple MacBookPro9,2            | 9         | 0.28%   |
| Apple MacBookPro11,3           | 9         | 0.28%   |
| Apple MacBookAir6,2            | 9         | 0.28%   |
| ASUS TUF Gaming X570-PLUS      | 8         | 0.25%   |
| ASUS TUF Gaming B550-PLUS      | 8         | 0.25%   |
| System76 Galago Pro            | 7         | 0.21%   |
| MSI MS-7C91                    | 7         | 0.21%   |
| MSI MS-7B86                    | 7         | 0.21%   |
| Gigabyte B450 AORUS M          | 7         | 0.21%   |
| Apple MacBookPro8,1            | 7         | 0.21%   |
| System76 Thelio                | 6         | 0.18%   |
| MSI MS-7A38                    | 6         | 0.18%   |
| Lenovo IdeaPad S145-15API 81V7 | 6         | 0.18%   |
| HP Notebook                    | 6         | 0.18%   |
| Gigabyte B550M DS3H            | 6         | 0.18%   |
| Gigabyte A320M-S2H             | 6         | 0.18%   |
| Dell XPS 15 9570               | 6         | 0.18%   |
| Dell XPS 15 9520               | 6         | 0.18%   |
| Dell XPS 13 9310               | 6         | 0.18%   |
| Dell Latitude E7240            | 6         | 0.18%   |
| ASUS TUF Gaming B550M-PLUS     | 6         | 0.18%   |
| ASUS PRIME B550M-A             | 6         | 0.18%   |
| Apple MacBookPro7,1            | 6         | 0.18%   |
| Acer Aspire A515-45            | 6         | 0.18%   |
| MSI MS-7D54                    | 5         | 0.15%   |
| MSI MS-7D32                    | 5         | 0.15%   |
| MSI MS-7C95                    | 5         | 0.15%   |
| MSI MS-7C37                    | 5         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 185       | 5.68%   |
| ASUS ROG           | 160       | 4.91%   |
| Dell Inspiron      | 106       | 3.25%   |
| Lenovo IdeaPad     | 101       | 3.1%    |
| Acer Aspire        | 91        | 2.79%   |
| Dell Latitude      | 83        | 2.55%   |
| Dell XPS           | 73        | 2.24%   |
| HP Pavilion        | 63        | 1.93%   |
| ASUS TUF           | 56        | 1.72%   |
| ASUS PRIME         | 56        | 1.72%   |
| Dell Precision     | 53        | 1.63%   |
| HP EliteBook       | 48        | 1.47%   |
| ASUS Vivobook      | 47        | 1.44%   |
| Lenovo Legion      | 44        | 1.35%   |
| HP Laptop          | 42        | 1.29%   |
| Dell OptiPlex      | 35        | 1.07%   |
| HP ProBook         | 31        | 0.95%   |
| Toshiba Satellite  | 30        | 0.92%   |
| Lenovo Yoga        | 30        | 0.92%   |
| HP ENVY            | 30        | 0.92%   |
| ASUS ASUS          | 29        | 0.89%   |
| ASUS ZenBook       | 25        | 0.77%   |
| Unknown            | 25        | 0.77%   |
| Lenovo ThinkCentre | 24        | 0.74%   |
| Gigabyte X570      | 22        | 0.68%   |
| Acer Swift         | 22        | 0.68%   |
| HP Compaq          | 21        | 0.64%   |
| ASUS All           | 21        | 0.64%   |
| Microsoft Surface  | 20        | 0.61%   |
| HP ZBook           | 20        | 0.61%   |
| Acer Nitro         | 20        | 0.61%   |
| Dell Vostro        | 19        | 0.58%   |
| Apple MacBookPro11 | 19        | 0.58%   |
| HP OMEN            | 18        | 0.55%   |
| Gigabyte B450      | 18        | 0.55%   |
| System76 Oryx      | 17        | 0.52%   |
| System76 Lemur     | 14        | 0.43%   |
| Lenovo ThinkBook   | 13        | 0.4%    |
| HP EliteDesk       | 13        | 0.4%    |
| Gigabyte B550      | 13        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 447       | 13.72%  |
| 2020    | 419       | 12.86%  |
| 2022    | 366       | 11.23%  |
| 2018    | 312       | 9.57%   |
| 2019    | 307       | 9.42%   |
| 2013    | 189       | 5.8%    |
| 2012    | 174       | 5.34%   |
| 2017    | 167       | 5.12%   |
| 2015    | 160       | 4.91%   |
| 2016    | 151       | 4.63%   |
| 2011    | 147       | 4.51%   |
| 2014    | 145       | 4.45%   |
| 2010    | 93        | 2.85%   |
| 2009    | 79        | 2.42%   |
| 2023    | 46        | 1.41%   |
| 2008    | 34        | 1.04%   |
| 2007    | 14        | 0.43%   |
| Unknown | 6         | 0.18%   |
| 2006    | 2         | 0.06%   |
| 2005    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1879      | 57.66%  |
| Desktop        | 1119      | 34.34%  |
| Convertible    | 112       | 3.44%   |
| Mini pc        | 60        | 1.84%   |
| All in one     | 42        | 1.29%   |
| Tablet         | 32        | 0.98%   |
| Server         | 10        | 0.31%   |
| System on chip | 5         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3258      | 99.94%  |
| Enabled  | 2         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3194      | 98.01%  |
| Yes  | 65        | 1.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 872       | 26.49%  |
| 4.01-8.0        | 711       | 21.6%   |
| 8.01-16.0       | 590       | 17.92%  |
| 32.01-64.0      | 560       | 17.01%  |
| 3.01-4.0        | 285       | 8.66%   |
| 64.01-256.0     | 171       | 5.19%   |
| 24.01-32.0      | 82        | 2.49%   |
| 1.01-2.0        | 10        | 0.3%    |
| 2.01-3.0        | 8         | 0.24%   |
| More than 256.0 | 3         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1150      | 32.4%   |
| 2.01-3.0    | 911       | 25.67%  |
| 3.01-4.0    | 777       | 21.89%  |
| 8.01-16.0   | 345       | 9.72%   |
| 1.01-2.0    | 294       | 8.28%   |
| 16.01-24.0  | 45        | 1.27%   |
| 24.01-32.0  | 14        | 0.39%   |
| 32.01-64.0  | 8         | 0.23%   |
| 0.51-1.0    | 3         | 0.08%   |
| 64.01-256.0 | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1922      | 57.96%  |
| 2      | 850       | 25.63%  |
| 3      | 283       | 8.53%   |
| 4      | 129       | 3.89%   |
| 5      | 66        | 1.99%   |
| 6      | 28        | 0.84%   |
| 0      | 14        | 0.42%   |
| 7      | 13        | 0.39%   |
| 9      | 3         | 0.09%   |
| 8      | 3         | 0.09%   |
| 10     | 2         | 0.06%   |
| 26     | 1         | 0.03%   |
| 19     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2522      | 77.22%  |
| Yes       | 744       | 22.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2677      | 81.69%  |
| No        | 600       | 18.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2742      | 83.96%  |
| No        | 524       | 16.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2353      | 71.78%  |
| No        | 925       | 28.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1035      | 31.57%  |
| Brazil       | 251       | 7.66%   |
| Germany      | 219       | 6.68%   |
| UK           | 151       | 4.61%   |
| Canada       | 146       | 4.45%   |
| Italy        | 117       | 3.57%   |
| Australia    | 103       | 3.14%   |
| India        | 86        | 2.62%   |
| France       | 85        | 2.59%   |
| Netherlands  | 64        | 1.95%   |
| Russia       | 60        | 1.83%   |
| Poland       | 54        | 1.65%   |
| Spain        | 53        | 1.62%   |
| Sweden       | 48        | 1.46%   |
| Norway       | 43        | 1.31%   |
| Mexico       | 42        | 1.28%   |
| Portugal     | 36        | 1.1%    |
| Finland      | 34        | 1.04%   |
| Austria      | 29        | 0.88%   |
| Switzerland  | 28        | 0.85%   |
| Greece       | 26        | 0.79%   |
| Denmark      | 25        | 0.76%   |
| Turkey       | 24        | 0.73%   |
| Chile        | 23        | 0.7%    |
| Argentina    | 23        | 0.7%    |
| Romania      | 22        | 0.67%   |
| Philippines  | 22        | 0.67%   |
| New Zealand  | 22        | 0.67%   |
| Japan        | 22        | 0.67%   |
| Czechia      | 22        | 0.67%   |
| Indonesia    | 21        | 0.64%   |
| Belgium      | 20        | 0.61%   |
| Hungary      | 18        | 0.55%   |
| South Africa | 17        | 0.52%   |
| Ireland      | 17        | 0.52%   |
| Serbia       | 15        | 0.46%   |
| Thailand     | 14        | 0.43%   |
| Malaysia     | 14        | 0.43%   |
| Bulgaria     | 13        | 0.4%    |
| Slovakia     | 10        | 0.31%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 26        | 0.76%   |
| Melbourne      | 25        | 0.73%   |
| Milan          | 23        | 0.68%   |
| Brisbane       | 23        | 0.68%   |
| Sydney         | 22        | 0.65%   |
| Helsinki       | 22        | 0.65%   |
| Berlin         | 21        | 0.62%   |
| Seattle        | 20        | 0.59%   |
| Rio de Janeiro | 20        | 0.59%   |
| Vienna         | 19        | 0.56%   |
| Oslo           | 19        | 0.56%   |
| Moscow         | 17        | 0.5%    |
| Istanbul       | 16        | 0.47%   |
| Madrid         | 15        | 0.44%   |
| Chicago        | 15        | 0.44%   |
| Bengaluru      | 14        | 0.41%   |
| Warsaw         | 13        | 0.38%   |
| Rome           | 13        | 0.38%   |
| Lisbon         | 13        | 0.38%   |
| Zurich         | 12        | 0.35%   |
| New York       | 12        | 0.35%   |
| London         | 12        | 0.35%   |
| Hamburg        | 12        | 0.35%   |
| Denver         | 12        | 0.35%   |
| Dallas         | 12        | 0.35%   |
| Belgrade       | 12        | 0.35%   |
| Toronto        | 11        | 0.32%   |
| San Antonio    | 11        | 0.32%   |
| Paris          | 11        | 0.32%   |
| Munich         | 11        | 0.32%   |
| Edmonton       | 11        | 0.32%   |
| Amsterdam      | 11        | 0.32%   |
| Prague         | 10        | 0.29%   |
| Portland       | 10        | 0.29%   |
| Dublin         | 10        | 0.29%   |
| Calgary        | 10        | 0.29%   |
| Auckland       | 10        | 0.29%   |
| Stockholm      | 9         | 0.26%   |
| San Jose       | 9         | 0.26%   |
| Mumbai         | 9         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 947       | 1373   | 19%     |
| WDC                         | 541       | 734    | 10.85%  |
| Seagate                     | 521       | 726    | 10.45%  |
| Sandisk                     | 382       | 493    | 7.66%   |
| Kingston                    | 258       | 306    | 5.18%   |
| Toshiba                     | 230       | 272    | 4.61%   |
| Crucial                     | 216       | 290    | 4.33%   |
| SK hynix                    | 189       | 222    | 3.79%   |
| Intel                       | 142       | 184    | 2.85%   |
| Unknown                     | 130       | 171    | 2.61%   |
| Micron Technology           | 118       | 142    | 2.37%   |
| Apple                       | 100       | 113    | 2.01%   |
| Hitachi                     | 75        | 113    | 1.5%    |
| Phison Electronics          | 72        | 100    | 1.44%   |
| A-DATA Technology           | 70        | 78     | 1.4%    |
| Micron/Crucial Technology   | 69        | 90     | 1.38%   |
| HGST                        | 68        | 79     | 1.36%   |
| Phison                      | 52        | 63     | 1.04%   |
| KIOXIA                      | 49        | 55     | 0.98%   |
| China                       | 49        | 66     | 0.98%   |
| PNY                         | 47        | 61     | 0.94%   |
| Silicon Motion              | 43        | 54     | 0.86%   |
| Kingston Technology Company | 40        | 45     | 0.8%    |
| SPCC                        | 28        | 37     | 0.56%   |
| Netac                       | 22        | 23     | 0.44%   |
| Intenso                     | 21        | 30     | 0.42%   |
| Unknown                     | 21        | 25     | 0.42%   |
| ADATA Technology            | 20        | 22     | 0.4%    |
| Team                        | 18        | 23     | 0.36%   |
| Realtek Semiconductor       | 16        | 16     | 0.32%   |
| Patriot                     | 16        | 19     | 0.32%   |
| JMicron Technology          | 16        | 26     | 0.32%   |
| LITEON                      | 15        | 18     | 0.3%    |
| OCZ                         | 14        | 19     | 0.28%   |
| LITEONIT                    | 14        | 23     | 0.28%   |
| KingSpec                    | 14        | 15     | 0.28%   |
| Transcend                   | 13        | 16     | 0.26%   |
| XPG                         | 12        | 14     | 0.24%   |
| Lexar                       | 11        | 14     | 0.22%   |
| Union Memory (Shenzhen)     | 10        | 12     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 119       | 2.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 71        | 1.29%   |
| Kingston SA400S37240G 240GB SSD                       | 63        | 1.15%   |
| SanDisk NVMe SSD Drive 1TB                            | 41        | 0.75%   |
| Samsung SSD 860 EVO 1TB                               | 38        | 0.69%   |
| Samsung SSD 850 EVO 250GB                             | 37        | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB                        | 36        | 0.65%   |
| Samsung NVMe SSD Drive 1TB                            | 36        | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB                        | 35        | 0.64%   |
| Samsung SSD 850 EVO 500GB                             | 35        | 0.64%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 35        | 0.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 33        | 0.6%    |
| Kingston SA400S37480G 480GB SSD                       | 32        | 0.58%   |
| Samsung SSD 860 EVO 500GB                             | 31        | 0.56%   |
| Kingston SA400S37120G 120GB SSD                       | 31        | 0.56%   |
| Crucial CT1000MX500SSD1 1TB                           | 31        | 0.56%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 30        | 0.55%   |
| Phison E12 NVMe Controller 256GB                      | 30        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB                        | 29        | 0.53%   |
| Samsung NVMe SSD Drive 500GB                          | 29        | 0.53%   |
| Crucial CT240BX500SSD1 240GB                          | 27        | 0.49%   |
| Crucial CT500MX500SSD1 500GB                          | 25        | 0.45%   |
| Samsung SSD 980 1TB                                   | 23        | 0.42%   |
| Unknown MMC Card  64GB                                | 22        | 0.4%    |
| Samsung NVMe SSD Drive 512GB                          | 22        | 0.4%    |
| Toshiba MQ01ABD100 1TB                                | 21        | 0.38%   |
| Intel SSD 660P Series 512GB                           | 21        | 0.38%   |
| Unknown                                               | 21        | 0.38%   |
| Seagate ST500DM002-1BD142 500GB                       | 20        | 0.36%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 20        | 0.36%   |
| Samsung NVMe SSD Drive 2TB                            | 20        | 0.36%   |
| HGST HTS721010A9E630 1TB                              | 20        | 0.36%   |
| Crucial CT1000BX500SSD1 1TB                           | 20        | 0.36%   |
| Seagate ST4000DM004-2CV104 4TB                        | 19        | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 19        | 0.35%   |
| Seagate Expansion 2TB                                 | 19        | 0.35%   |
| Unknown SD/MMC/MS PRO 1GB                             | 18        | 0.33%   |
| Unknown MMC Card  128GB                               | 18        | 0.33%   |
| Toshiba MQ04ABF100 1TB                                | 18        | 0.33%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 18        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 502       | 690    | 38.79%  |
| WDC                 | 381       | 529    | 29.44%  |
| Toshiba             | 160       | 188    | 12.36%  |
| Hitachi             | 75        | 113    | 5.8%    |
| HGST                | 68        | 79     | 5.26%   |
| Samsung Electronics | 35        | 44     | 2.7%    |
| Apple               | 20        | 23     | 1.55%   |
| Unknown             | 19        | 23     | 1.47%   |
| SABRENT             | 7         | 11     | 0.54%   |
| Fujitsu             | 6         | 9      | 0.46%   |
| Maxtor              | 3         | 3      | 0.23%   |
| PHD 3.0             | 2         | 2      | 0.15%   |
| JMicron Technology  | 2         | 9      | 0.15%   |
| Intenso             | 2         | 5      | 0.15%   |
| ASMT                | 2         | 2      | 0.15%   |
| WD MediaMax         | 1         | 1      | 0.08%   |
| USB3.0              | 1         | 1      | 0.08%   |
| StoreJet            | 1         | 1      | 0.08%   |
| RSH-339             | 1         | 1      | 0.08%   |
| LaCie               | 1         | 2      | 0.08%   |
| HGST HDN            | 1         | 1      | 0.08%   |
| External            | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |
| Asm                 | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 376       | 529    | 23.15%  |
| Kingston            | 197       | 229    | 12.13%  |
| Crucial             | 190       | 253    | 11.7%   |
| SanDisk             | 137       | 169    | 8.44%   |
| WDC                 | 94        | 112    | 5.79%   |
| Apple               | 68        | 73     | 4.19%   |
| China               | 48        | 65     | 2.96%   |
| A-DATA Technology   | 48        | 53     | 2.96%   |
| PNY                 | 45        | 59     | 2.77%   |
| Intel               | 32        | 42     | 1.97%   |
| SK hynix            | 30        | 35     | 1.85%   |
| Micron Technology   | 27        | 29     | 1.66%   |
| SPCC                | 22        | 26     | 1.35%   |
| Toshiba             | 20        | 20     | 1.23%   |
| Netac               | 18        | 19     | 1.11%   |
| Patriot             | 15        | 18     | 0.92%   |
| OCZ                 | 14        | 19     | 0.86%   |
| LITEONIT            | 14        | 23     | 0.86%   |
| KingSpec            | 14        | 15     | 0.86%   |
| Intenso             | 14        | 19     | 0.86%   |
| LITEON              | 13        | 16     | 0.8%    |
| Transcend           | 12        | 15     | 0.74%   |
| Team                | 11        | 15     | 0.68%   |
| JMicron Technology  | 10        | 11     | 0.62%   |
| Apacer              | 9         | 14     | 0.55%   |
| Lexar               | 7         | 9      | 0.43%   |
| Hewlett-Packard     | 7         | 10     | 0.43%   |
| Seagate             | 5         | 6      | 0.31%   |
| KingDian            | 5         | 10     | 0.31%   |
| GOODRAM             | 5         | 5      | 0.31%   |
| Gigabyte Technology | 5         | 5      | 0.31%   |
| Verbatim            | 4         | 8      | 0.25%   |
| Mushkin             | 4         | 6      | 0.25%   |
| Dogfish             | 4         | 4      | 0.25%   |
| Corsair             | 4         | 5      | 0.25%   |
| Unknown             | 4         | 4      | 0.25%   |
| TO Exter            | 3         | 3      | 0.18%   |
| OWC                 | 3         | 3      | 0.18%   |
| MyDigitalSSD        | 3         | 3      | 0.18%   |
| INTEL SS            | 3         | 5      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1711      | 2486   | 38.9%   |
| SSD     | 1405      | 2051   | 31.95%  |
| HDD     | 1088      | 1741   | 24.74%  |
| MMC     | 105       | 123    | 2.39%   |
| Unknown | 89        | 151    | 2.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2010      | 3596   | 49.78%  |
| NVMe | 1706      | 2476   | 42.25%  |
| SAS  | 217       | 357    | 5.37%   |
| MMC  | 105       | 123    | 2.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1376      | 1993   | 51.77%  |
| 0.51-1.0   | 834       | 1122   | 31.38%  |
| 1.01-2.0   | 275       | 393    | 10.35%  |
| 3.01-4.0   | 75        | 112    | 2.82%   |
| 4.01-10.0  | 58        | 105    | 2.18%   |
| 2.01-3.0   | 34        | 54     | 1.28%   |
| 10.01-20.0 | 6         | 13     | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 913       | 27.11%  |
| 251-500        | 847       | 25.15%  |
| 501-1000       | 719       | 21.35%  |
| 1001-2000      | 318       | 9.44%   |
| More than 3000 | 190       | 5.64%   |
| 2001-3000      | 126       | 3.74%   |
| 51-100         | 103       | 3.06%   |
| 1-20           | 81        | 2.4%    |
| 21-50          | 49        | 1.45%   |
| Unknown        | 22        | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1000      | 28.56%  |
| 21-50          | 773       | 22.08%  |
| 101-250        | 520       | 14.85%  |
| 51-100         | 439       | 12.54%  |
| 251-500        | 335       | 9.57%   |
| 501-1000       | 194       | 5.54%   |
| 1001-2000      | 108       | 3.08%   |
| More than 3000 | 69        | 1.97%   |
| 2001-3000      | 41        | 1.17%   |
| Unknown        | 22        | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1TB          | 3         | 3      | 3.09%   |
| HGST HTS725050A7E630 500GB                  | 3         | 4      | 3.09%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 2         | 2      | 2.06%   |
| Seagate ST3250310AS 250GB                   | 2         | 3      | 2.06%   |
| Seagate ST1000LX015-1U7172 1TB              | 2         | 2      | 2.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 2         | 2      | 2.06%   |
| Samsung Electronics SSD 850 EVO 250GB       | 2         | 2      | 2.06%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD            | 1         | 1      | 1.03%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 1      | 1.03%   |
| WDC WDS100T2B0B-00YS70 1TB SSD              | 1         | 1      | 1.03%   |
| WDC WD60EFRX-68L0BN1 6TB                    | 1         | 1      | 1.03%   |
| WDC WD5001AALS-00J7B1 500GB                 | 1         | 1      | 1.03%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 1      | 1.03%   |
| WDC WD5000AADS-00S9B0 500GB                 | 1         | 1      | 1.03%   |
| WDC WD3200BEKX-75B7WT0 320GB                | 1         | 1      | 1.03%   |
| WDC WD3200BEKT-60PVMT0 320GB                | 1         | 1      | 1.03%   |
| WDC WD20EFRX-68AX9N0 2TB                    | 1         | 5      | 1.03%   |
| WDC WD15EADS-00P8B0 1TB                     | 1         | 1      | 1.03%   |
| WDC WD10SPZX-22Z10T0 1TB                    | 1         | 1      | 1.03%   |
| WDC WD10JPVX-60JC3T1 1TB                    | 1         | 1      | 1.03%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 1      | 1.03%   |
| WDC WD10EARS-00MVWB0 1TB                    | 1         | 1      | 1.03%   |
| WDC WD1002FAEX-00Z3A0 1TB                   | 1         | 1      | 1.03%   |
| WDC WD1001FALS-00E8B0 1TB                   | 1         | 1      | 1.03%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB        | 1         | 1      | 1.03%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD    | 1         | 1      | 1.03%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD    | 1         | 1      | 1.03%   |
| Toshiba MQ04ABF100 1TB                      | 1         | 1      | 1.03%   |
| Toshiba MQ01ACF050 500GB                    | 1         | 1      | 1.03%   |
| Toshiba MK7559GSXP 752GB                    | 1         | 1      | 1.03%   |
| Toshiba MK3252GSX 320GB                     | 1         | 1      | 1.03%   |
| Toshiba MK1655GSX 160GB                     | 1         | 1      | 1.03%   |
| Team TM8FP4004T 4TB                         | 1         | 1      | 1.03%   |
| Team T253X1120G 120GB SSD                   | 1         | 1      | 1.03%   |
| SK hynix PC711 HFS512GDE9X073N 512GB        | 1         | 1      | 1.03%   |
| SK hynix HFS512G39TND-N210A 512GB SSD       | 1         | 1      | 1.03%   |
| SK hynix HFS128G39TND-N210A 128GB SSD       | 1         | 1      | 1.03%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1      | 1.03%   |
| Seagate STM3500418AS 500GB                  | 1         | 1      | 1.03%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 1.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 24     | 21.28%  |
| Seagate             | 19        | 22     | 20.21%  |
| Samsung Electronics | 10        | 11     | 10.64%  |
| Toshiba             | 7         | 7      | 7.45%   |
| SK hynix            | 7         | 7      | 7.45%   |
| HGST                | 7         | 8      | 7.45%   |
| Kingston            | 3         | 4      | 3.19%   |
| Intel               | 3         | 3      | 3.19%   |
| Hitachi             | 3         | 5      | 3.19%   |
| Team                | 2         | 2      | 2.13%   |
| Micron Technology   | 2         | 4      | 2.13%   |
| Crucial             | 2         | 2      | 2.13%   |
| A-DATA Technology   | 2         | 2      | 2.13%   |
| SanDisk             | 1         | 1      | 1.06%   |
| SABRENT             | 1         | 1      | 1.06%   |
| Plextor             | 1         | 1      | 1.06%   |
| Lexar               | 1         | 1      | 1.06%   |
| Leven               | 1         | 1      | 1.06%   |
| China               | 1         | 1      | 1.06%   |
| BAITITON            | 1         | 1      | 1.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 35.85%  |
| WDC                 | 16        | 20     | 30.19%  |
| HGST                | 7         | 8      | 13.21%  |
| Toshiba             | 5         | 5      | 9.43%   |
| Hitachi             | 3         | 5      | 5.66%   |
| Samsung Electronics | 2         | 2      | 3.77%   |
| SABRENT             | 1         | 1      | 1.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 63     | 55.43%  |
| SSD  | 27        | 29     | 29.35%  |
| NVMe | 14        | 16     | 15.22%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 33.33%  |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 33.33%  |
| KingDian S400 120GB               | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| KingDian            | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2529      | 5108   | 73.35%  |
| Works    | 826       | 1332   | 23.96%  |
| Malfunc  | 90        | 108    | 2.61%   |
| Failed   | 3         | 4      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1812      | 38.63%  |
| AMD                            | 810       | 17.27%  |
| Samsung Electronics            | 658       | 14.03%  |
| SanDisk                        | 319       | 6.8%    |
| SK hynix                       | 160       | 3.41%   |
| Phison Electronics             | 131       | 2.79%   |
| Kingston Technology Company    | 100       | 2.13%   |
| Micron/Crucial Technology      | 95        | 2.03%   |
| Micron Technology              | 91        | 1.94%   |
| ASMedia Technology             | 67        | 1.43%   |
| Toshiba America Info Systems   | 56        | 1.19%   |
| Silicon Motion                 | 51        | 1.09%   |
| KIOXIA                         | 48        | 1.02%   |
| Nvidia                         | 47        | 1%      |
| ADATA Technology               | 44        | 0.94%   |
| Marvell Technology Group       | 35        | 0.75%   |
| Realtek Semiconductor          | 25        | 0.53%   |
| Solid State Storage Technology | 24        | 0.51%   |
| JMicron Technology             | 17        | 0.36%   |
| Union Memory (Shenzhen)        | 16        | 0.34%   |
| Apple                          | 14        | 0.3%    |
| Seagate Technology             | 12        | 0.26%   |
| Shenzhen Longsys Electronics   | 8         | 0.17%   |
| Broadcom / LSI                 | 8         | 0.17%   |
| MAXIO Technology (Hangzhou)    | 7         | 0.15%   |
| LSI Logic / Symbios Logic      | 6         | 0.13%   |
| Lite-On Technology             | 5         | 0.11%   |
| INNOGRIT                       | 5         | 0.11%   |
| VIA Technologies               | 3         | 0.06%   |
| Solidigm                       | 3         | 0.06%   |
| Netac Technology               | 3         | 0.06%   |
| Hewlett-Packard                | 3         | 0.06%   |
| Silicon Image                  | 2         | 0.04%   |
| Yangtze Memory Technologies    | 1         | 0.02%   |
| Western Digital                | 1         | 0.02%   |
| Transcend                      | 1         | 0.02%   |
| O2 Micro                       | 1         | 0.02%   |
| Biwin Storage Technology       | 1         | 0.02%   |
| Adaptec                        | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 578       | 11.16%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 285       | 5.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 142       | 2.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 140       | 2.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 138       | 2.66%   |
| AMD 500 Series Chipset SATA Controller                                         | 137       | 2.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 130       | 2.51%   |
| Samsung NVMe SSD Controller 980                                                | 125       | 2.41%   |
| AMD 400 Series Chipset SATA Controller                                         | 117       | 2.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 104       | 2.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 96        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 90        | 1.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 83        | 1.6%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 70        | 1.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 65        | 1.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 62        | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 62        | 1.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 61        | 1.18%   |
| Phison E12 NVMe Controller                                                     | 59        | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 57        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                          | 54        | 1.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 53        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 53        | 1.02%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 52        | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 50        | 0.97%   |
| Intel SSD 660P Series                                                          | 49        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 45        | 0.87%   |
| Intel SATA Controller [RAID mode]                                              | 44        | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 40        | 0.77%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 40        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 39        | 0.75%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 39        | 0.75%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 35        | 0.68%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 34        | 0.66%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 33        | 0.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 32        | 0.62%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 31        | 0.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 31        | 0.6%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 31        | 0.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 31        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2303      | 50.85%  |
| NVMe | 1700      | 37.54%  |
| RAID | 324       | 7.15%   |
| IDE  | 186       | 4.11%   |
| SAS  | 15        | 0.33%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2205      | 67.66%  |
| AMD    | 1050      | 32.22%  |
| ARM    | 4         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 47        | 1.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 46        | 1.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 38        | 1.16%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 38        | 1.16%   |
| AMD Ryzen 5 3600 6-Core Processor             | 38        | 1.16%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 35        | 1.07%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 35        | 1.07%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 35        | 1.07%   |
| Intel 12th Gen Core i7-12700H                 | 33        | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 30        | 0.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.92%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 30        | 0.92%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 29        | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 28        | 0.86%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 28        | 0.86%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 27        | 0.83%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 27        | 0.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 26        | 0.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 25        | 0.77%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 24        | 0.74%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 23        | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 23        | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 22        | 0.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 21        | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 21        | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.64%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 20        | 0.61%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 20        | 0.61%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 17        | 0.52%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 17        | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 16        | 0.49%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 16        | 0.49%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 16        | 0.49%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 16        | 0.49%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 16        | 0.49%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 15        | 0.46%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 15        | 0.46%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 15        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 693       | 21.23%  |
| Intel Core i5           | 625       | 19.15%  |
| Other                   | 409       | 12.53%  |
| AMD Ryzen 5             | 333       | 10.2%   |
| AMD Ryzen 7             | 328       | 10.05%  |
| Intel Core i3           | 152       | 4.66%   |
| AMD Ryzen 9             | 136       | 4.17%   |
| Intel Celeron           | 79        | 2.42%   |
| Intel Core 2 Duo        | 77        | 2.36%   |
| Intel Xeon              | 67        | 2.05%   |
| AMD FX                  | 39        | 1.19%   |
| AMD Ryzen 3             | 33        | 1.01%   |
| Intel Pentium           | 31        | 0.95%   |
| Intel Core i9           | 28        | 0.86%   |
| AMD Ryzen 7 PRO         | 25        | 0.77%   |
| AMD A8                  | 22        | 0.67%   |
| AMD A10                 | 17        | 0.52%   |
| AMD A6                  | 14        | 0.43%   |
| AMD Ryzen Threadripper  | 11        | 0.34%   |
| Intel Pentium Dual-Core | 10        | 0.31%   |
| Intel Core 2 Quad       | 10        | 0.31%   |
| AMD Ryzen 5 PRO         | 10        | 0.31%   |
| AMD A4                  | 9         | 0.28%   |
| Intel Pentium Silver    | 8         | 0.25%   |
| AMD Athlon              | 8         | 0.25%   |
| Intel Pentium Gold      | 7         | 0.21%   |
| AMD Athlon II X2        | 7         | 0.21%   |
| AMD Athlon II X4        | 6         | 0.18%   |
| Intel Core m5           | 5         | 0.15%   |
| Intel Atom              | 5         | 0.15%   |
| AMD Phenom II X4        | 5         | 0.15%   |
| Intel Core 2            | 4         | 0.12%   |
| AMD Ryzen 3 PRO         | 4         | 0.12%   |
| AMD Phenom II X6        | 4         | 0.12%   |
| AMD E1                  | 4         | 0.12%   |
| AMD E                   | 4         | 0.12%   |
| Intel Pentium D         | 3         | 0.09%   |
| AMD Phenom              | 3         | 0.09%   |
| AMD Athlon X4           | 3         | 0.09%   |
| AMD Athlon X2           | 3         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1105      | 33.85%  |
| 2       | 830       | 25.43%  |
| 8       | 498       | 15.26%  |
| 6       | 484       | 14.83%  |
| 12      | 106       | 3.25%   |
| 16      | 75        | 2.3%    |
| 14      | 66        | 2.02%   |
| 10      | 51        | 1.56%   |
| 3       | 16        | 0.49%   |
| 1       | 14        | 0.43%   |
| 24      | 9         | 0.28%   |
| Unknown | 4         | 0.12%   |
| 32      | 2         | 0.06%   |
| 64      | 1         | 0.03%   |
| 40      | 1         | 0.03%   |
| 36      | 1         | 0.03%   |
| 18      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3238      | 99.36%  |
| 2       | 17        | 0.52%   |
| Unknown | 4         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2681      | 82.19%  |
| 1       | 577       | 17.69%  |
| Unknown | 4         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3256      | 99.91%  |
| 64-bit         | 3         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2618      | 79.17%  |
| 0x806c1    | 49        | 1.48%   |
| 0x0a50000c | 43        | 1.3%    |
| 0x806ec    | 26        | 0.79%   |
| 0x906a3    | 24        | 0.73%   |
| 0x806ea    | 24        | 0.73%   |
| 0x806d1    | 24        | 0.73%   |
| 0x08701021 | 24        | 0.73%   |
| 0x08600106 | 23        | 0.7%    |
| 0x306a9    | 22        | 0.67%   |
| 0x906ea    | 21        | 0.64%   |
| 0x08608103 | 21        | 0.64%   |
| 0xa0652    | 20        | 0.6%    |
| 0x0a404101 | 16        | 0.48%   |
| 0x0a601203 | 15        | 0.45%   |
| 0x0a50000d | 15        | 0.45%   |
| 0x0a404102 | 15        | 0.45%   |
| 0x08108109 | 15        | 0.45%   |
| 0x506e3    | 14        | 0.42%   |
| 0x406e3    | 14        | 0.42%   |
| 0x206a7    | 14        | 0.42%   |
| 0x0a201016 | 14        | 0.42%   |
| 0x806e9    | 13        | 0.39%   |
| 0x306c3    | 13        | 0.39%   |
| 0x0800820d | 13        | 0.39%   |
| 0x906a4    | 12        | 0.36%   |
| 0x40651    | 12        | 0.36%   |
| 0x906e9    | 11        | 0.33%   |
| 0x08600104 | 10        | 0.3%    |
| 0x306d4    | 9         | 0.27%   |
| 0x706e5    | 8         | 0.24%   |
| 0x1067a    | 8         | 0.24%   |
| 0x706a8    | 7         | 0.21%   |
| 0x0a20120a | 6         | 0.18%   |
| 0x08600103 | 6         | 0.18%   |
| 0x906ec    | 5         | 0.15%   |
| 0x90672    | 5         | 0.15%   |
| 0x806eb    | 5         | 0.15%   |
| 0x0a201205 | 5         | 0.15%   |
| 0x08701013 | 5         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 511       | 15.64%  |
| Unknown          | 337       | 10.32%  |
| Zen 3            | 313       | 9.58%   |
| Haswell          | 290       | 8.88%   |
| Zen 2            | 200       | 6.12%   |
| SandyBridge      | 171       | 5.23%   |
| Skylake          | 163       | 4.99%   |
| IvyBridge        | 162       | 4.96%   |
| TigerLake        | 143       | 4.38%   |
| Zen+             | 138       | 4.22%   |
| CometLake        | 106       | 3.24%   |
| Broadwell        | 92        | 2.82%   |
| Penryn           | 88        | 2.69%   |
| Alderlake Hybrid | 75        | 2.3%    |
| Zen              | 68        | 2.08%   |
| Icelake          | 61        | 1.87%   |
| Westmere         | 57        | 1.74%   |
| Piledriver       | 55        | 1.68%   |
| Goldmont plus    | 39        | 1.19%   |
| Silvermont       | 30        | 0.92%   |
| K10              | 30        | 0.92%   |
| Nehalem          | 28        | 0.86%   |
| Excavator        | 23        | 0.7%    |
| Core             | 19        | 0.58%   |
| Puma             | 15        | 0.46%   |
| Steamroller      | 14        | 0.43%   |
| Goldmont         | 8         | 0.24%   |
| K10 Llano        | 7         | 0.21%   |
| Jaguar           | 5         | 0.15%   |
| Bobcat           | 5         | 0.15%   |
| K8 Hammer        | 4         | 0.12%   |
| Tremont          | 3         | 0.09%   |
| NetBurst         | 3         | 0.09%   |
| Bulldozer        | 3         | 0.09%   |
| K8 & K10 hybrid  | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1696      | 42.16%  |
| Nvidia                     | 1298      | 32.26%  |
| AMD                        | 1024      | 25.45%  |
| Matrox Electronics Systems | 4         | 0.1%    |
| ASPEED Technology          | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 129       | 3.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 127       | 3.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 122       | 2.96%   |
| Intel UHD Graphics 620                                                      | 96        | 2.33%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 93        | 2.25%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 85        | 2.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 85        | 2.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 82        | 1.99%   |
| AMD Renoir                                                                  | 81        | 1.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 80        | 1.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 68        | 1.65%   |
| AMD Lucienne                                                                | 67        | 1.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 62        | 1.5%    |
| Intel HD Graphics 620                                                       | 60        | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 59        | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 56        | 1.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 55        | 1.33%   |
| Intel HD Graphics 5500                                                      | 54        | 1.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 54        | 1.31%   |
| AMD Rembrandt [Radeon 680M]                                                 | 54        | 1.31%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 52        | 1.26%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 48        | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 44        | 1.07%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 42        | 1.02%   |
| Intel HD Graphics 530                                                       | 41        | 0.99%   |
| Intel HD Graphics 630                                                       | 37        | 0.9%    |
| AMD Raphael                                                                 | 37        | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 36        | 0.87%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 36        | 0.87%   |
| Intel Core Processor Integrated Graphics Controller                         | 36        | 0.87%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 35        | 0.85%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 34        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 31        | 0.75%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 31        | 0.75%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 28        | 0.68%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 27        | 0.65%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 25        | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 25        | 0.61%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 24        | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 23        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 1104      | 33.61%  |
| 1 x AMD              | 728       | 22.16%  |
| 1 x Nvidia           | 652       | 19.85%  |
| Intel + Nvidia       | 471       | 14.34%  |
| AMD + Nvidia         | 156       | 4.75%   |
| Intel + AMD          | 74        | 2.25%   |
| 2 x AMD              | 68        | 2.07%   |
| 2 x Nvidia           | 13        | 0.4%    |
| Other                | 8         | 0.24%   |
| 1 x Matrox           | 4         | 0.12%   |
| Intel + 2 x Nvidia   | 3         | 0.09%   |
| 2 x Intel            | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.03%   |
| Nvidia + ASPEED      | 1         | 0.03%   |
| AMD + 2 x Nvidia     | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2165      | 65.79%  |
| Proprietary | 1046      | 31.78%  |
| Unknown     | 80        | 2.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2664      | 80.53%  |
| 7.01-8.0   | 128       | 3.87%   |
| 0.01-0.5   | 116       | 3.51%   |
| 1.01-2.0   | 111       | 3.36%   |
| 3.01-4.0   | 97        | 2.93%   |
| 5.01-6.0   | 75        | 2.27%   |
| 8.01-16.0  | 66        | 2%      |
| 0.51-1.0   | 27        | 0.82%   |
| 2.01-3.0   | 14        | 0.42%   |
| 16.01-24.0 | 9         | 0.27%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 437       | 11.6%   |
| Samsung Electronics     | 409       | 10.85%  |
| BOE                     | 367       | 9.74%   |
| Chimei Innolux          | 344       | 9.13%   |
| LG Display              | 288       | 7.64%   |
| Goldstar                | 246       | 6.53%   |
| Dell                    | 233       | 6.18%   |
| Apple                   | 137       | 3.64%   |
| Acer                    | 128       | 3.4%    |
| Hewlett-Packard         | 108       | 2.87%   |
| AOC                     | 98        | 2.6%    |
| Sharp                   | 93        | 2.47%   |
| ASUSTek Computer        | 81        | 2.15%   |
| Ancor Communications    | 70        | 1.86%   |
| BenQ                    | 67        | 1.78%   |
| Lenovo                  | 58        | 1.54%   |
| PANDA                   | 55        | 1.46%   |
| Philips                 | 52        | 1.38%   |
| MSI                     | 31        | 0.82%   |
| InfoVision              | 31        | 0.82%   |
| Iiyama                  | 30        | 0.8%    |
| Chi Mei Optoelectronics | 25        | 0.66%   |
| CSO                     | 24        | 0.64%   |
| ViewSonic               | 22        | 0.58%   |
| Sceptre Tech            | 18        | 0.48%   |
| Gigabyte Technology     | 18        | 0.48%   |
| Sony                    | 16        | 0.42%   |
| NEC Computers           | 15        | 0.4%    |
| Panasonic               | 14        | 0.37%   |
| Vizio                   | 12        | 0.32%   |
| Toshiba                 | 9         | 0.24%   |
| TMX                     | 9         | 0.24%   |
| Unknown                 | 8         | 0.21%   |
| HKC                     | 8         | 0.21%   |
| Vestel Elektronik       | 7         | 0.19%   |
| Insignia                | 6         | 0.16%   |
| Hitachi                 | 6         | 0.16%   |
| Eizo                    | 6         | 0.16%   |
| Pioneer                 | 5         | 0.13%   |
| LG Electronics          | 5         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch  | 23        | 0.59%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch  | 22        | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch  | 21        | 0.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch    | 20        | 0.52%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch           | 19        | 0.49%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch          | 18        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch  | 16        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 14        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch   | 13        | 0.33%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch              | 12        | 0.31%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch    | 11        | 0.28%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch      | 10        | 0.26%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch      | 10        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch  | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch     | 10        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 9         | 0.23%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch      | 9         | 0.23%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch           | 9         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch  | 9         | 0.23%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch             | 9         | 0.23%   |
| AOC 27G2WG3 AOC2702 1920x1080 598x336mm 27.0-inch                 | 9         | 0.23%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch       | 8         | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 8         | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                 | 8         | 0.21%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                 | 8         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch   | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch     | 8         | 0.21%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                     | 7         | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch | 7         | 0.18%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch      | 7         | 0.18%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch       | 7         | 0.18%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch             | 7         | 0.18%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                 | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch  | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch  | 7         | 0.18%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch             | 7         | 0.18%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch             | 7         | 0.18%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch             | 7         | 0.18%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch    | 7         | 0.18%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch    | 7         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1676      | 46.91%  |
| 1366x768 (WXGA)    | 477       | 13.35%  |
| 3840x2160 (4K)     | 327       | 9.15%   |
| 2560x1440 (QHD)    | 259       | 7.25%   |
| 1920x1200 (WUXGA)  | 104       | 2.91%   |
| 1600x900 (HD+)     | 91        | 2.55%   |
| 3440x1440          | 81        | 2.27%   |
| 2560x1080          | 67        | 1.88%   |
| 2560x1600          | 63        | 1.76%   |
| 1440x900 (WXGA+)   | 59        | 1.65%   |
| 1680x1050 (WSXGA+) | 48        | 1.34%   |
| 2880x1800          | 47        | 1.32%   |
| 1280x1024 (SXGA)   | 44        | 1.23%   |
| 1280x800 (WXGA)    | 41        | 1.15%   |
| 3840x1080          | 22        | 0.62%   |
| 1360x768           | 19        | 0.53%   |
| 3840x2400          | 17        | 0.48%   |
| 1920x540           | 13        | 0.36%   |
| 2160x1440          | 11        | 0.31%   |
| 2736x1824          | 9         | 0.25%   |
| 2256x1504          | 9         | 0.25%   |
| 3840x1600          | 8         | 0.22%   |
| 3072x1920          | 8         | 0.22%   |
| Unknown            | 8         | 0.22%   |
| 3200x1800 (QHD+)   | 7         | 0.2%    |
| 1920x1280          | 6         | 0.17%   |
| 1024x768 (XGA)     | 6         | 0.17%   |
| 1600x1200          | 5         | 0.14%   |
| 3456x2160          | 4         | 0.11%   |
| 3200x2000          | 4         | 0.11%   |
| 1280x720 (HD)      | 4         | 0.11%   |
| 3840x1100          | 3         | 0.08%   |
| 3000x2000          | 3         | 0.08%   |
| 800x1280           | 2         | 0.06%   |
| 4480x1440          | 2         | 0.06%   |
| 2880x1620          | 2         | 0.06%   |
| 2304x1440          | 2         | 0.06%   |
| 2240x1400          | 2         | 0.06%   |
| 5120x1440          | 1         | 0.03%   |
| 3840x1200          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 939       | 24.9%   |
| 13      | 416       | 11.03%  |
| 27      | 355       | 9.41%   |
| 24      | 288       | 7.64%   |
| 14      | 288       | 7.64%   |
| 23      | 210       | 5.57%   |
| 17      | 174       | 4.61%   |
| 21      | 155       | 4.11%   |
| 31      | 152       | 4.03%   |
| 34      | 131       | 3.47%   |
| 16      | 66        | 1.75%   |
| 12      | 62        | 1.64%   |
| 19      | 56        | 1.49%   |
| Unknown | 54        | 1.43%   |
| 84      | 40        | 1.06%   |
| 32      | 39        | 1.03%   |
| 18      | 37        | 0.98%   |
| 22      | 36        | 0.95%   |
| 20      | 29        | 0.77%   |
| 11      | 28        | 0.74%   |
| 72      | 26        | 0.69%   |
| 48      | 22        | 0.58%   |
| 40      | 18        | 0.48%   |
| 28      | 17        | 0.45%   |
| 54      | 16        | 0.42%   |
| 26      | 12        | 0.32%   |
| 37      | 11        | 0.29%   |
| 25      | 11        | 0.29%   |
| 35      | 9         | 0.24%   |
| 29      | 8         | 0.21%   |
| 65      | 7         | 0.19%   |
| 33      | 7         | 0.19%   |
| 52      | 6         | 0.16%   |
| 49      | 6         | 0.16%   |
| 46      | 5         | 0.13%   |
| 36      | 4         | 0.11%   |
| 74      | 3         | 0.08%   |
| 57      | 3         | 0.08%   |
| 44      | 3         | 0.08%   |
| 42      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1483      | 40.34%  |
| 501-600     | 763       | 20.76%  |
| 201-300     | 316       | 8.6%    |
| 401-500     | 281       | 7.64%   |
| 601-700     | 214       | 5.82%   |
| 351-400     | 193       | 5.25%   |
| 701-800     | 176       | 4.79%   |
| 1501-2000   | 74        | 2.01%   |
| 1001-1500   | 71        | 1.93%   |
| Unknown     | 54        | 1.47%   |
| 801-900     | 43        | 1.17%   |
| 901-1000    | 5         | 0.14%   |
| 1-100       | 2         | 0.05%   |
| 101-200     | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2597      | 77.73%  |
| 16/10   | 422       | 12.63%  |
| 21/9    | 158       | 4.73%   |
| 5/4     | 46        | 1.38%   |
| 3/2     | 39        | 1.17%   |
| 32/9    | 26        | 0.78%   |
| Unknown | 25        | 0.75%   |
| 4/3     | 18        | 0.54%   |
| 3.40    | 3         | 0.09%   |
| 6/5     | 2         | 0.06%   |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.63    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 938       | 25.18%  |
| 81-90          | 535       | 14.36%  |
| 201-250        | 533       | 14.31%  |
| 301-350        | 369       | 9.91%   |
| 351-500        | 344       | 9.23%   |
| 71-80          | 171       | 4.59%   |
| 121-130        | 138       | 3.7%    |
| 151-200        | 124       | 3.33%   |
| More than 1000 | 113       | 3.03%   |
| 251-300        | 106       | 2.85%   |
| 501-1000       | 70        | 1.88%   |
| 111-120        | 64        | 1.72%   |
| 141-150        | 60        | 1.61%   |
| Unknown        | 54        | 1.45%   |
| 61-70          | 49        | 1.32%   |
| 51-60          | 31        | 0.83%   |
| 131-140        | 13        | 0.35%   |
| 91-100         | 10        | 0.27%   |
| 1-40           | 3         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1146      | 31.83%  |
| 51-100        | 1056      | 29.33%  |
| 101-120       | 816       | 22.67%  |
| 161-240       | 318       | 8.83%   |
| More than 240 | 126       | 3.5%    |
| 1-50          | 84        | 2.33%   |
| Unknown       | 54        | 1.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2514      | 75.84%  |
| 2     | 599       | 18.07%  |
| 0     | 102       | 3.08%   |
| 3     | 92        | 2.78%   |
| 4     | 7         | 0.21%   |
| 6     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1761      | 35.38%  |
| Intel                             | 1711      | 34.37%  |
| Qualcomm Atheros                  | 450       | 9.04%   |
| Broadcom                          | 269       | 5.4%    |
| MediaTek                          | 167       | 3.35%   |
| Broadcom Limited                  | 78        | 1.57%   |
| TP-Link                           | 53        | 1.06%   |
| ASIX Electronics                  | 41        | 0.82%   |
| Marvell Technology Group          | 39        | 0.78%   |
| Nvidia                            | 33        | 0.66%   |
| Samsung Electronics               | 32        | 0.64%   |
| Ralink Technology                 | 30        | 0.6%    |
| Ralink                            | 27        | 0.54%   |
| NetGear                           | 22        | 0.44%   |
| Xiaomi                            | 20        | 0.4%    |
| DisplayLink                       | 18        | 0.36%   |
| Aquantia                          | 18        | 0.36%   |
| Dell                              | 15        | 0.3%    |
| Qualcomm                          | 14        | 0.28%   |
| Microsoft                         | 13        | 0.26%   |
| InterBiometrics                   | 12        | 0.24%   |
| Lenovo                            | 11        | 0.22%   |
| Google                            | 11        | 0.22%   |
| Sierra Wireless                   | 10        | 0.2%    |
| D-Link                            | 9         | 0.18%   |
| OPPO Electronics                  | 8         | 0.16%   |
| Linksys                           | 8         | 0.16%   |
| ASUSTek Computer                  | 8         | 0.16%   |
| Qualcomm Atheros Communications   | 7         | 0.14%   |
| JMicron Technology                | 7         | 0.14%   |
| D-Link System                     | 7         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.12%   |
| Huawei Technologies               | 6         | 0.12%   |
| Hewlett-Packard                   | 6         | 0.12%   |
| Motorola PCS                      | 4         | 0.08%   |
| Ericsson Business Mobile Networks | 4         | 0.08%   |
| Edimax Technology                 | 4         | 0.08%   |
| Mellanox Technologies             | 3         | 0.06%   |
| Fibocom                           | 3         | 0.06%   |
| Apple                             | 3         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1119      | 18.99%  |
| Intel Wi-Fi 6 AX200                                               | 260       | 4.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 171       | 2.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 136       | 2.31%   |
| Intel I211 Gigabit Network Connection                             | 132       | 2.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 120       | 2.04%   |
| Intel Wi-Fi 6 AX201                                               | 115       | 1.95%   |
| Intel Wireless 8265 / 8275                                        | 111       | 1.88%   |
| Intel Ethernet Controller I225-V                                  | 109       | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 102       | 1.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 81        | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 77        | 1.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 74        | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 69        | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 69        | 1.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 65        | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 64        | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 64        | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 63        | 1.07%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 59        | 1%      |
| Intel Wireless 7265                                               | 59        | 1%      |
| Intel Wireless 8260                                               | 56        | 0.95%   |
| Intel Wireless 7260                                               | 54        | 0.92%   |
| Intel Ethernet Connection I217-LM                                 | 54        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 52        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 51        | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 51        | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 49        | 0.83%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 47        | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 46        | 0.78%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 40        | 0.68%   |
| Intel Wireless-AC 9260                                            | 39        | 0.66%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 38        | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 36        | 0.61%   |
| Realtek 802.11ac NIC                                              | 36        | 0.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 35        | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 34        | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 33        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1397      | 48.27%  |
| Realtek Semiconductor                 | 447       | 15.45%  |
| Qualcomm Atheros                      | 357       | 12.34%  |
| Broadcom                              | 214       | 7.39%   |
| MediaTek                              | 166       | 5.74%   |
| Broadcom Limited                      | 66        | 2.28%   |
| TP-Link                               | 46        | 1.59%   |
| Ralink Technology                     | 30        | 1.04%   |
| Ralink                                | 27        | 0.93%   |
| NetGear                               | 22        | 0.76%   |
| Marvell Technology Group              | 14        | 0.48%   |
| Microsoft                             | 13        | 0.45%   |
| Dell                                  | 13        | 0.45%   |
| Qualcomm                              | 12        | 0.41%   |
| Sierra Wireless                       | 10        | 0.35%   |
| Linksys                               | 8         | 0.28%   |
| D-Link                                | 8         | 0.28%   |
| Qualcomm Atheros Communications       | 7         | 0.24%   |
| ASUSTek Computer                      | 7         | 0.24%   |
| D-Link System                         | 6         | 0.21%   |
| Edimax Technology                     | 4         | 0.14%   |
| Hewlett-Packard                       | 3         | 0.1%    |
| Fibocom                               | 3         | 0.1%    |
| Belkin Components                     | 2         | 0.07%   |
| Accton Technology                     | 2         | 0.07%   |
| ZyDAS                                 | 1         | 0.03%   |
| Wacom                                 | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| IMC Networks                          | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |
| Ericsson Business Mobile Networks     | 1         | 0.03%   |
| AVM                                   | 1         | 0.03%   |
| Arduino SA                            | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 260       | 8.93%   |
| Intel Wi-Fi 6 AX201                                            | 115       | 3.95%   |
| Intel Wireless 8265 / 8275                                     | 111       | 3.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 102       | 3.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 77        | 2.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 74        | 2.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 69        | 2.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 69        | 2.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 65        | 2.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 64        | 2.2%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 64        | 2.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 63        | 2.16%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 59        | 2.03%   |
| Intel Wireless 7265                                            | 59        | 2.03%   |
| Intel Wireless 8260                                            | 56        | 1.92%   |
| Intel Wireless 7260                                            | 54        | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 52        | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 51        | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 51        | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 49        | 1.68%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 47        | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 46        | 1.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 40        | 1.37%   |
| Intel Wireless-AC 9260                                         | 39        | 1.34%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 38        | 1.3%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 36        | 1.24%   |
| Realtek 802.11ac NIC                                           | 36        | 1.24%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 35        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 34        | 1.17%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 32        | 1.1%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 28        | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 24        | 0.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 24        | 0.82%   |
| Broadcom BCM43142 802.11b/g/n                                  | 24        | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 23        | 0.79%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 23        | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 22        | 0.76%   |
| Intel Wireless 3165                                            | 22        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 21        | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 18        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 1560      | 54.32%  |
| Intel                         | 797       | 27.75%  |
| Qualcomm Atheros              | 132       | 4.6%    |
| Broadcom                      | 110       | 3.83%   |
| ASIX Electronics              | 41        | 1.43%   |
| Nvidia                        | 33        | 1.15%   |
| Samsung Electronics           | 32        | 1.11%   |
| Marvell Technology Group      | 25        | 0.87%   |
| Xiaomi                        | 20        | 0.7%    |
| DisplayLink                   | 18        | 0.63%   |
| Aquantia                      | 18        | 0.63%   |
| Broadcom Limited              | 12        | 0.42%   |
| Lenovo                        | 11        | 0.38%   |
| Google                        | 11        | 0.38%   |
| OPPO Electronics              | 8         | 0.28%   |
| TP-Link                       | 7         | 0.24%   |
| JMicron Technology            | 7         | 0.24%   |
| OnePlus Technology (Shenzhen) | 5         | 0.17%   |
| Huawei Technologies           | 5         | 0.17%   |
| Motorola PCS                  | 3         | 0.1%    |
| Mellanox Technologies         | 3         | 0.1%    |
| Qualcomm                      | 2         | 0.07%   |
| Hewlett-Packard               | 2         | 0.07%   |
| Apple                         | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.03%   |
| VIA Technologies              | 1         | 0.03%   |
| T & A Mobile Phones           | 1         | 0.03%   |
| Insyde Software               | 1         | 0.03%   |
| D-Link System                 | 1         | 0.03%   |
| D-Link                        | 1         | 0.03%   |
| ASUSTek Computer              | 1         | 0.03%   |
| American Megatrends           | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1119      | 38.04%  |
| Realtek RTL8125 2.5GbE Controller                                 | 171       | 5.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 136       | 4.62%   |
| Intel I211 Gigabit Network Connection                             | 132       | 4.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 120       | 4.08%   |
| Intel Ethernet Controller I225-V                                  | 109       | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 81        | 2.75%   |
| Intel Ethernet Connection I217-LM                                 | 54        | 1.84%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 1.36%   |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                     | 33        | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 27        | 0.92%   |
| Intel Ethernet Connection (7) I219-V                              | 25        | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 24        | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 24        | 0.82%   |
| Nvidia MCP79 Ethernet                                             | 23        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 22        | 0.75%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 21        | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 20        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 20        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 20        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 16        | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.54%   |
| Intel Ethernet Connection (2) I218-V                              | 15        | 0.51%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 0.48%   |
| Intel I210 Gigabit Network Connection                             | 13        | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 13        | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 12        | 0.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 12        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 0.41%   |
| Intel Ethernet Connection (6) I219-V                              | 12        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.37%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.37%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9         | 0.31%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 9         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2745      | 50.35%  |
| Ethernet | 2669      | 48.95%  |
| Modem    | 27        | 0.5%    |
| Unknown  | 11        | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2134      | 61.71%  |
| Ethernet | 1324      | 38.29%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1824      | 55.9%   |
| 1     | 1300      | 39.84%  |
| 3     | 95        | 2.91%   |
| 0     | 35        | 1.07%   |
| 4     | 7         | 0.21%   |
| 5     | 2         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2295      | 69.5%   |
| Yes  | 1007      | 30.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1245      | 52.42%  |
| Realtek Semiconductor           | 226       | 9.52%   |
| Apple                           | 165       | 6.95%   |
| Qualcomm Atheros Communications | 161       | 6.78%   |
| IMC Networks                    | 100       | 4.21%   |
| Cambridge Silicon Radio         | 93        | 3.92%   |
| Foxconn / Hon Hai               | 90        | 3.79%   |
| Lite-On Technology              | 64        | 2.69%   |
| Broadcom                        | 50        | 2.11%   |
| MediaTek                        | 42        | 1.77%   |
| ASUSTek Computer                | 27        | 1.14%   |
| Dell                            | 15        | 0.63%   |
| Marvell Semiconductor           | 14        | 0.59%   |
| Realtek                         | 13        | 0.55%   |
| TP-Link                         | 11        | 0.46%   |
| Toshiba                         | 10        | 0.42%   |
| Hewlett-Packard                 | 8         | 0.34%   |
| Dynex                           | 6         | 0.25%   |
| Ralink                          | 4         | 0.17%   |
| Actions                         | 4         | 0.17%   |
| Opticis                         | 3         | 0.13%   |
| Micro Star International        | 3         | 0.13%   |
| Integrated System Solution      | 3         | 0.13%   |
| Foxconn International           | 3         | 0.13%   |
| Taiyo Yuden                     | 2         | 0.08%   |
| Smart Modular Technologies      | 2         | 0.08%   |
| Ralink Technology               | 2         | 0.08%   |
| Fujitsu                         | 2         | 0.08%   |
| Edimax Technology               | 2         | 0.08%   |
| USI                             | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| HTC (High Tech Computer)        | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 301       | 12.66%  |
| Intel AX201 Bluetooth                               | 286       | 12.03%  |
| Intel AX200 Bluetooth                               | 245       | 10.31%  |
| Realtek Bluetooth Radio                             | 167       | 7.03%   |
| Intel Bluetooth Device                              | 143       | 6.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 142       | 5.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 93        | 3.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 89        | 3.74%   |
| Apple Bluetooth Host Controller                     | 87        | 3.66%   |
| Intel AX210 Bluetooth                               | 58        | 2.44%   |
| Realtek  Bluetooth 4.2 Adapter                      | 47        | 1.98%   |
| Apple Bluetooth USB Host Controller                 | 45        | 1.89%   |
| MediaTek Wireless_Device                            | 42        | 1.77%   |
| IMC Networks Wireless_Device                        | 42        | 1.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 35        | 1.47%   |
| Foxconn / Hon Hai Wireless_Device                   | 29        | 1.22%   |
| Foxconn / Hon Hai Bluetooth Device                  | 25        | 1.05%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 0.97%   |
| IMC Networks Bluetooth Radio                        | 23        | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 0.93%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 22        | 0.93%   |
| IMC Networks Bluetooth Device                       | 18        | 0.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 17        | 0.72%   |
| Lite-On Wireless_Device                             | 15        | 0.63%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 13        | 0.55%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 13        | 0.55%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 0.5%    |
| Lite-On Bluetooth Device                            | 12        | 0.5%    |
| TP-Link UB5A Adapter                                | 11        | 0.46%   |
| Realtek 802.11ac WLAN Adapter                       | 11        | 0.46%   |
| Marvell Bluetooth and Wireless LAN Composite        | 11        | 0.46%   |
| Apple Bluetooth HCI                                 | 11        | 0.46%   |
| Lite-On Bluetooth Radio                             | 10        | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 9         | 0.38%   |
| ASUS ASUS USB-BT500                                 | 9         | 0.38%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 0.34%   |
| Broadcom BCM2045B (BDC-2.1)                         | 8         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2136      | 42%     |
| AMD                                  | 1201      | 23.61%  |
| Nvidia                               | 1040      | 20.45%  |
| C-Media Electronics                  | 87        | 1.71%   |
| Logitech                             | 55        | 1.08%   |
| Kingston Technology                  | 38        | 0.75%   |
| Razer USA                            | 29        | 0.57%   |
| Focusrite-Novation                   | 29        | 0.57%   |
| JMTek                                | 28        | 0.55%   |
| ASUSTek Computer                     | 27        | 0.53%   |
| Generalplus Technology               | 24        | 0.47%   |
| SteelSeries ApS                      | 22        | 0.43%   |
| Micro Star International             | 22        | 0.43%   |
| Creative Labs                        | 22        | 0.43%   |
| GN Netcom                            | 19        | 0.37%   |
| Lenovo                               | 17        | 0.33%   |
| Texas Instruments                    | 16        | 0.31%   |
| Realtek Semiconductor                | 15        | 0.29%   |
| Corsair                              | 15        | 0.29%   |
| Creative Technology                  | 13        | 0.26%   |
| Sony                                 | 12        | 0.24%   |
| Apple                                | 12        | 0.24%   |
| Hewlett-Packard                      | 10        | 0.2%    |
| Blue Microphones                     | 10        | 0.2%    |
| Plantronics                          | 9         | 0.18%   |
| DSEA A/S                             | 8         | 0.16%   |
| FiiO Electronics Technology          | 5         | 0.1%    |
| DCMT Technology                      | 5         | 0.1%    |
| Astro Gaming                         | 5         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 4         | 0.08%   |
| Tenx Technology                      | 4         | 0.08%   |
| Medeli Electronics                   | 4         | 0.08%   |
| Mackie Designs                       | 4         | 0.08%   |
| M-Audio                              | 4         | 0.08%   |
| Jieli Technology                     | 4         | 0.08%   |
| Giga-Byte Technology                 | 4         | 0.08%   |
| BEHRINGER International              | 4         | 0.08%   |
| Antlion Audio                        | 4         | 0.08%   |
| Yamaha                               | 3         | 0.06%   |
| Valve Software                       | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 519       | 8.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 280       | 4.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 250       | 4.06%   |
| Intel Sunrise Point-LP HD Audio                                            | 238       | 3.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 170       | 2.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 161       | 2.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 152       | 2.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 143       | 2.32%   |
| Intel Cannon Lake PCH cAVS                                                 | 132       | 2.15%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 120       | 1.95%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 115       | 1.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 111       | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 106       | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 101       | 1.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 87        | 1.41%   |
| Nvidia GA106 High Definition Audio Controller                              | 84        | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 84        | 1.37%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 84        | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 82        | 1.33%   |
| Intel Haswell-ULT HD Audio Controller                                      | 81        | 1.32%   |
| Intel Comet Lake PCH cAVS                                                  | 81        | 1.32%   |
| Intel 8 Series HD Audio Controller                                         | 80        | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 76        | 1.24%   |
| Nvidia Audio device                                                        | 74        | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                              | 73        | 1.19%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 69        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 67        | 1.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 66        | 1.07%   |
| Nvidia TU106 High Definition Audio Controller                              | 65        | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 65        | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                               | 65        | 1.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 63        | 1.02%   |
| AMD FCH Azalia Controller                                                  | 62        | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                              | 61        | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 61        | 0.99%   |
| Nvidia GP106 High Definition Audio Controller                              | 60        | 0.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 59        | 0.96%   |
| Intel 200 Series PCH HD Audio                                              | 58        | 0.94%   |
| Nvidia TU104 HD Audio Controller                                           | 46        | 0.75%   |
| Nvidia GA102 High Definition Audio Controller                              | 45        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 260       | 24.93%  |
| SK hynix                     | 201       | 19.27%  |
| Micron Technology            | 135       | 12.94%  |
| Kingston                     | 89        | 8.53%   |
| Corsair                      | 75        | 7.19%   |
| Crucial                      | 64        | 6.14%   |
| G.Skill                      | 47        | 4.51%   |
| Unknown                      | 26        | 2.49%   |
| Team                         | 23        | 2.21%   |
| A-DATA Technology            | 20        | 1.92%   |
| Smart                        | 13        | 1.25%   |
| Unknown                      | 12        | 1.15%   |
| Neo Forza                    | 9         | 0.86%   |
| Elpida                       | 9         | 0.86%   |
| Unknown (ABCD)               | 8         | 0.77%   |
| Ramaxel Technology           | 8         | 0.77%   |
| Goldkey                      | 8         | 0.77%   |
| PNY                          | 4         | 0.38%   |
| Nanya Technology             | 4         | 0.38%   |
| GSkill                       | 3         | 0.29%   |
| Avant                        | 3         | 0.29%   |
| Transcend                    | 2         | 0.19%   |
| Teikon                       | 2         | 0.19%   |
| Smart Brazil                 | 2         | 0.19%   |
| Gold Key                     | 2         | 0.19%   |
| Apacer                       | 2         | 0.19%   |
| Unknown (8A02)               | 1         | 0.1%    |
| Unknown (09B6)               | 1         | 0.1%    |
| Unknown (09A4)               | 1         | 0.1%    |
| Timetec                      | 1         | 0.1%    |
| Patriot Memory (PDP Systems) | 1         | 0.1%    |
| Patriot Memory               | 1         | 0.1%    |
| Patriot                      | 1         | 0.1%    |
| Kllisre                      | 1         | 0.1%    |
| GeIL                         | 1         | 0.1%    |
| CSX                          | 1         | 0.1%    |
| ChangXin Memory              | 1         | 0.1%    |
| Asgard                       | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 2.11%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 1.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 1.38%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 1.28%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 12        | 1.1%    |
| Unknown                                                          | 12        | 1.1%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 11        | 1.01%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.83%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 8         | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 0.73%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 8         | 0.73%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 8         | 0.73%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 8         | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 7         | 0.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 7         | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.64%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.64%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.64%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 6         | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.55%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 6         | 0.55%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 0.55%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.55%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 6         | 0.55%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.55%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.55%   |
| Team RAM TEAMGROUP-SD4-3200 8192MB SODIMM DDR4 3200MT/s          | 5         | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.46%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 5         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 4         | 0.37%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 4         | 0.37%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 4         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 589       | 64.73%  |
| DDR3    | 140       | 15.38%  |
| DDR5    | 60        | 6.59%   |
| LPDDR4  | 52        | 5.71%   |
| LPDDR5  | 31        | 3.41%   |
| LPDDR3  | 23        | 2.53%   |
| DDR2    | 8         | 0.88%   |
| SDRAM   | 4         | 0.44%   |
| Unknown | 3         | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 583       | 63.03%  |
| DIMM         | 214       | 23.14%  |
| Row Of Chips | 122       | 13.19%  |
| Chip         | 4         | 0.43%   |
| Unknown      | 2         | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 440       | 45.08%  |
| 16384 | 228       | 23.36%  |
| 4096  | 193       | 19.77%  |
| 32768 | 71        | 7.27%   |
| 2048  | 40        | 4.1%    |
| 1024  | 4         | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 275       | 28.26%  |
| 2667  | 163       | 16.75%  |
| 1600  | 107       | 11%     |
| 2400  | 57        | 5.86%   |
| 4800  | 45        | 4.62%   |
| 3600  | 41        | 4.21%   |
| 2133  | 38        | 3.91%   |
| 6400  | 33        | 3.39%   |
| 4267  | 31        | 3.19%   |
| 1867  | 14        | 1.44%   |
| 1333  | 14        | 1.44%   |
| 3733  | 13        | 1.34%   |
| 3800  | 12        | 1.23%   |
| 3266  | 10        | 1.03%   |
| 1334  | 10        | 1.03%   |
| 8400  | 8         | 0.82%   |
| 3533  | 8         | 0.82%   |
| 1067  | 7         | 0.72%   |
| 800   | 7         | 0.72%   |
| 6000  | 6         | 0.62%   |
| 4266  | 6         | 0.62%   |
| 3000  | 6         | 0.62%   |
| 2933  | 6         | 0.62%   |
| 3534  | 5         | 0.51%   |
| 3400  | 5         | 0.51%   |
| 5200  | 3         | 0.31%   |
| 3866  | 3         | 0.31%   |
| 2800  | 3         | 0.31%   |
| 2666  | 3         | 0.31%   |
| 1866  | 3         | 0.31%   |
| 5600  | 2         | 0.21%   |
| 4199  | 2         | 0.21%   |
| 4000  | 2         | 0.21%   |
| 3666  | 2         | 0.21%   |
| 3466  | 2         | 0.21%   |
| 3333  | 2         | 0.21%   |
| 3100  | 2         | 0.21%   |
| 2048  | 2         | 0.21%   |
| 667   | 2         | 0.21%   |
| 6800  | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 30.77%  |
| Canon               | 9         | 17.31%  |
| Brother Industries  | 9         | 17.31%  |
| Samsung Electronics | 6         | 11.54%  |
| Seiko Epson         | 4         | 7.69%   |
| STMicroelectronics  | 2         | 3.85%   |
| Xerox               | 1         | 1.92%   |
| QinHeng Electronics | 1         | 1.92%   |
| Prolific Technology | 1         | 1.92%   |
| ICS Advent          | 1         | 1.92%   |
| Dymo-CoStar         | 1         | 1.92%   |
| Dell                | 1         | 1.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Brother HL-2130 series                                    | 3         | 5.66%   |
| Seiko Epson WF-4830 Series                                | 2         | 3.77%   |
| HP ENVY Pro 6400 series                                   | 2         | 3.77%   |
| Canon PIXMA MX920 Series                                  | 2         | 3.77%   |
| Xerox B215                                                | 1         | 1.89%   |
| STMicroelectronics USB Printer P                          | 1         | 1.89%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.89%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 1.89%   |
| Seiko Epson ET-2800 Series                                | 1         | 1.89%   |
| Samsung SCX-4500 Laser Printer                            | 1         | 1.89%   |
| Samsung SCX-3400 Series                                   | 1         | 1.89%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.89%   |
| Samsung ML-191x/ML-252x Laser Printer                     | 1         | 1.89%   |
| Samsung M2070 Series                                      | 1         | 1.89%   |
| Samsung M2020 Series                                      | 1         | 1.89%   |
| QinHeng CH340S                                            | 1         | 1.89%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.89%   |
| ICS Advent Parallel Adapter                               | 1         | 1.89%   |
| HP PSC-1315/PSC-1317                                      | 1         | 1.89%   |
| HP OfficeJet Pro 9010 series                              | 1         | 1.89%   |
| HP OfficeJet 3830 series                                  | 1         | 1.89%   |
| HP LaserJet Professional P1102w                           | 1         | 1.89%   |
| HP LaserJet Professional P 1102w                          | 1         | 1.89%   |
| HP LaserJet Pro M201dw                                    | 1         | 1.89%   |
| HP LaserJet P2035                                         | 1         | 1.89%   |
| HP LaserJet 3050                                          | 1         | 1.89%   |
| HP LaserJet 1010                                          | 1         | 1.89%   |
| HP Ink Tank Wireless 410 series                           | 1         | 1.89%   |
| HP Ink Tank 110 series                                    | 1         | 1.89%   |
| HP ENVY 5000 series                                       | 1         | 1.89%   |
| HP DeskJet 2600 series                                    | 1         | 1.89%   |
| HP Color LaserJet CP2025dn                                | 1         | 1.89%   |
| Dymo-CoStar DYMO LabelWriter 4XL                          | 1         | 1.89%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 1         | 1.89%   |
| Dell Laser Printer 1720                                   | 1         | 1.89%   |
| Canon TS9100 series                                       | 1         | 1.89%   |
| Canon TR8500 series                                       | 1         | 1.89%   |
| Canon TR4700 series                                       | 1         | 1.89%   |
| Canon Pro9000II series                                    | 1         | 1.89%   |
| Canon PIXMA MP240                                         | 1         | 1.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 44.44%  |
| Seiko Epson     | 3         | 33.33%  |
| Mustek Systems  | 1         | 11.11%  |
| Hewlett-Packard | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 11.11%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 11.11%  |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1         | 11.11%  |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 11.11%  |
| HP ScanJet 82x0C                                        | 1         | 11.11%  |
| Canon CanoScan N650U/N656U                              | 1         | 11.11%  |
| Canon CanoScan LiDE 60                                  | 1         | 11.11%  |
| Canon CanoScan LiDE 200                                 | 1         | 11.11%  |
| Canon CanoScan 9000F Mark II                            | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 401       | 18.65%  |
| IMC Networks                           | 207       | 9.63%   |
| Microdia                               | 205       | 9.53%   |
| Bison Electronics                      | 170       | 7.91%   |
| Realtek Semiconductor                  | 153       | 7.12%   |
| Logitech                               | 134       | 6.23%   |
| Apple                                  | 126       | 5.86%   |
| Quanta                                 | 118       | 5.49%   |
| Sunplus Innovation Technology          | 105       | 4.88%   |
| Luxvisions Innotech Limited            | 58        | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) | 54        | 2.51%   |
| Syntek                                 | 47        | 2.19%   |
| Lite-On Technology                     | 40        | 1.86%   |
| Acer                                   | 36        | 1.67%   |
| Suyin                                  | 28        | 1.3%    |
| Microsoft                              | 26        | 1.21%   |
| Sonix Technology                       | 21        | 0.98%   |
| Silicon Motion                         | 19        | 0.88%   |
| Samsung Electronics                    | 19        | 0.88%   |
| SunplusIT                              | 15        | 0.7%    |
| Razer USA                              | 12        | 0.56%   |
| Z-Star Microelectronics                | 9         | 0.42%   |
| Generalplus Technology                 | 9         | 0.42%   |
| Alcor Micro                            | 9         | 0.42%   |
| Creative Technology                    | 7         | 0.33%   |
| Ricoh                                  | 6         | 0.28%   |
| Primax Electronics                     | 6         | 0.28%   |
| Jieli Technology                       | 6         | 0.28%   |
| MacroSilicon                           | 5         | 0.23%   |
| Lenovo                                 | 5         | 0.23%   |
| ARC International                      | 5         | 0.23%   |
| LG Electronics                         | 4         | 0.19%   |
| icSpring                               | 4         | 0.19%   |
| Cubeternet                             | 4         | 0.19%   |
| AVerMedia Technologies                 | 4         | 0.19%   |
| Trust                                  | 3         | 0.14%   |
| Tobii Technology AB                    | 3         | 0.14%   |
| Importek                               | 3         | 0.14%   |
| HRY                                    | 3         | 0.14%   |
| ALi                                    | 3         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 93        | 4.28%   |
| Chicony Integrated Camera                           | 89        | 4.1%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 83        | 3.82%   |
| Realtek Integrated_Webcam_HD                        | 66        | 3.04%   |
| IMC Networks Integrated Camera                      | 50        | 2.3%    |
| Bison Integrated Camera                             | 39        | 1.79%   |
| Chicony HD Webcam                                   | 38        | 1.75%   |
| Syntek Integrated Camera                            | 37        | 1.7%    |
| Apple Built-in iSight                               | 36        | 1.66%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 34        | 1.56%   |
| Logitech HD Pro Webcam C920                         | 33        | 1.52%   |
| Bison BisonCam,NB Pro                               | 33        | 1.52%   |
| Logitech Webcam C270                                | 31        | 1.43%   |
| Chicony USB2.0 Camera                               | 30        | 1.38%   |
| Apple FaceTime HD Camera (Built-in)                 | 30        | 1.38%   |
| Bison HD Webcam                                     | 29        | 1.33%   |
| Sunplus Integrated_Webcam_HD                        | 28        | 1.29%   |
| Quanta HD User Facing                               | 27        | 1.24%   |
| Apple FaceTime HD Camera                            | 21        | 0.97%   |
| Chicony HP HD Camera                                | 20        | 0.92%   |
| Samsung Galaxy series, misc. (MTP mode)             | 19        | 0.87%   |
| Quanta HP HD Camera                                 | 19        | 0.87%   |
| Chicony HD User Facing                              | 19        | 0.87%   |
| Sonix USB2.0 HD UVC WebCam                          | 16        | 0.74%   |
| Bison SunplusIT Integrated Camera                   | 16        | 0.74%   |
| Quanta HP TrueVision HD Camera                      | 15        | 0.69%   |
| Microdia Webcam Vitade AF                           | 15        | 0.69%   |
| Microdia Integrated Webcam                          | 15        | 0.69%   |
| Lite-On Integrated Camera                           | 15        | 0.69%   |
| Chicony USB2.0 VGA UVC WebCam                       | 14        | 0.64%   |
| Realtek Integrated Webcam                           | 13        | 0.6%    |
| Luxvisions Innotech Limited HP HD Camera            | 13        | 0.6%    |
| Chicony Integrated Camera (1280x720@30)             | 13        | 0.6%    |
| Quanta HP Wide Vision HD Camera                     | 12        | 0.55%   |
| Microdia Integrated_Webcam_FHD                      | 12        | 0.55%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 12        | 0.55%   |
| Logitech C922 Pro Stream Webcam                     | 12        | 0.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 12        | 0.55%   |
| Chicony HP Wide Vision HD Camera                    | 12        | 0.55%   |
| Chicony HP Truevision HD camera                     | 12        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 140       | 35.71%  |
| Validity Sensors                   | 101       | 25.77%  |
| Shenzhen Goodix Technology         | 76        | 19.39%  |
| Elan Microelectronics              | 24        | 6.12%   |
| LighTuning Technology              | 15        | 3.83%   |
| Upek                               | 14        | 3.57%   |
| AuthenTec                          | 8         | 2.04%   |
| Focal-systems.Corp                 | 5         | 1.28%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 1.02%   |
| HOLTEK                             | 3         | 0.77%   |
| Samsung Electronics                | 1         | 0.26%   |
| DigitalPersona                     | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 34        | 8.67%   |
| Shenzhen Goodix  Fingerprint Device                                        | 33        | 8.42%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 6.89%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 5.61%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 5.61%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 4.34%   |
| Shenzhen Goodix FingerPrint                                                | 16        | 4.08%   |
| Elan ELAN:ARM-M4                                                           | 14        | 3.57%   |
| Synaptics UWP WBDI                                                         | 13        | 3.32%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 2.81%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 2.55%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 2.3%    |
| Synaptics WBDI Device                                                      | 9         | 2.3%    |
| Validity Sensors Synaptics WBDI                                            | 8         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 2.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 2.04%   |
| Elan ELAN:Fingerprint                                                      | 8         | 2.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 1.79%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.79%   |
| Synaptics WBDI                                                             | 7         | 1.79%   |
| Synaptics  WBDI                                                            | 7         | 1.79%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.53%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 1.53%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.53%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 1.53%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.28%   |
| Synaptics UWP WBDI Device                                                  | 5         | 1.28%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.28%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 1.28%   |
| Unknown                                                                    | 5         | 1.28%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 1.02%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.02%   |
| Validity Sensors VFS491                                                    | 3         | 0.77%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.77%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.77%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.77%   |
| HOLTEK FocalTech Fingerprint Device                                        | 3         | 0.77%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.51%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 64        | 51.61%  |
| Alcor Micro           | 39        | 31.45%  |
| O2 Micro              | 6         | 4.84%   |
| Lenovo                | 5         | 4.03%   |
| Upek                  | 4         | 3.23%   |
| OmniKey               | 2         | 1.61%   |
| SCM Microsystems      | 1         | 0.81%   |
| Gemalto (was Gemplus) | 1         | 0.81%   |
| Clay Logic            | 1         | 0.81%   |
| Advanced Card Systems | 1         | 0.81%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 38        | 30.65%  |
| Broadcom 58200                                                               | 22        | 17.74%  |
| Broadcom 5880                                                                | 17        | 13.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 12.9%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 7.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 4.03%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.03%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.23%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.81%   |
| OmniKey CardMan 4321                                                         | 1         | 0.81%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.81%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.81%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.81%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.81%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.81%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.81%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2221      | 67.02%  |
| 1     | 887       | 26.77%  |
| 2     | 172       | 5.19%   |
| 3     | 29        | 0.88%   |
| 4     | 3         | 0.09%   |
| 6     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 380       | 29.46%  |
| Net/wireless             | 185       | 14.34%  |
| Graphics card            | 184       | 14.26%  |
| Multimedia controller    | 180       | 13.95%  |
| Chipcard                 | 117       | 9.07%   |
| Bluetooth                | 67        | 5.19%   |
| Camera                   | 45        | 3.49%   |
| Sound                    | 27        | 2.09%   |
| Unassigned class         | 21        | 1.63%   |
| Communication controller | 19        | 1.47%   |
| Net/ethernet             | 16        | 1.24%   |
| Network                  | 12        | 0.93%   |
| Storage                  | 9         | 0.7%    |
| Card reader              | 8         | 0.62%   |
| Modem                    | 7         | 0.54%   |
| Storage/raid             | 4         | 0.31%   |
| Storage/ide              | 4         | 0.31%   |
| Storage/nvme             | 3         | 0.23%   |
| Wireless                 | 1         | 0.08%   |
| Firewire controller      | 1         | 0.08%   |

