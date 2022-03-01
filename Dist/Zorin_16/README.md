Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [1df5245912](https://linux-hardware.org/?probe=1df5245912) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [bd438d0f08](https://linux-hardware.org/?probe=bd438d0f08) | Mar 01, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [d7b8815296](https://linux-hardware.org/?probe=d7b8815296) | Feb 28, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [61f8410abd](https://linux-hardware.org/?probe=61f8410abd) | Feb 28, 2022 |
| BESSTAR Te... | TL50                        | Desktop     | [54383b0005](https://linux-hardware.org/?probe=54383b0005) | Feb 28, 2022 |
| HP            | 821D                        | Desktop     | [fdfcbe172a](https://linux-hardware.org/?probe=fdfcbe172a) | Feb 28, 2022 |
| Dell          | Latitude 3550               | Notebook    | [5b0d9e3d13](https://linux-hardware.org/?probe=5b0d9e3d13) | Feb 28, 2022 |
| Acer          | Aspire TC-875 V:1.0         | Desktop     | [47018f3ae4](https://linux-hardware.org/?probe=47018f3ae4) | Feb 28, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| ASRock        | H77M                        | Desktop     | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| Dell          | Precision M4800             | Notebook    | [546f292b66](https://linux-hardware.org/?probe=546f292b66) | Feb 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [f553433011](https://linux-hardware.org/?probe=f553433011) | Feb 27, 2022 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [f67c401f47](https://linux-hardware.org/?probe=f67c401f47) | Feb 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [52c633564d](https://linux-hardware.org/?probe=52c633564d) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [cef4c5a609](https://linux-hardware.org/?probe=cef4c5a609) | Feb 27, 2022 |
| MSI           | B85M-E45                    | Desktop     | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [821b101c53](https://linux-hardware.org/?probe=821b101c53) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [49fb58c88b](https://linux-hardware.org/?probe=49fb58c88b) | Feb 27, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c84caad5a2](https://linux-hardware.org/?probe=c84caad5a2) | Feb 26, 2022 |
| Dell          | Latitude E5500              | Notebook    | [38a51b4721](https://linux-hardware.org/?probe=38a51b4721) | Feb 26, 2022 |
| HP            | 630                         | Notebook    | [6bf505d86b](https://linux-hardware.org/?probe=6bf505d86b) | Feb 26, 2022 |
| Gigabyte      | N3160TN                     | Desktop     | [f080ac90fa](https://linux-hardware.org/?probe=f080ac90fa) | Feb 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [359368d345](https://linux-hardware.org/?probe=359368d345) | Feb 26, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [fabf12f128](https://linux-hardware.org/?probe=fabf12f128) | Feb 26, 2022 |
| Dell          | Inspiron 5448               | Notebook    | [2458e07e0d](https://linux-hardware.org/?probe=2458e07e0d) | Feb 25, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [5e8e80fa4c](https://linux-hardware.org/?probe=5e8e80fa4c) | Feb 25, 2022 |
| Intel         | X79M-S                      | Desktop     | [a175e713d6](https://linux-hardware.org/?probe=a175e713d6) | Feb 25, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d318ba4e2c](https://linux-hardware.org/?probe=d318ba4e2c) | Feb 25, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [c55ba8cab2](https://linux-hardware.org/?probe=c55ba8cab2) | Feb 25, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [c9447d244f](https://linux-hardware.org/?probe=c9447d244f) | Feb 24, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [d1fd917c74](https://linux-hardware.org/?probe=d1fd917c74) | Feb 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [b1354ad7df](https://linux-hardware.org/?probe=b1354ad7df) | Feb 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d685366566](https://linux-hardware.org/?probe=d685366566) | Feb 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e3ae28a6a2](https://linux-hardware.org/?probe=e3ae28a6a2) | Feb 24, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [ae66a9051d](https://linux-hardware.org/?probe=ae66a9051d) | Feb 24, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [0bbf5e3155](https://linux-hardware.org/?probe=0bbf5e3155) | Feb 24, 2022 |
| Packard Be... | DOT S                       | Notebook    | [e90543b727](https://linux-hardware.org/?probe=e90543b727) | Feb 24, 2022 |
| Fujitsu       | LIFEBOOK AH512              | Notebook    | [d7889a52d1](https://linux-hardware.org/?probe=d7889a52d1) | Feb 24, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [40de7f3fd4](https://linux-hardware.org/?probe=40de7f3fd4) | Feb 23, 2022 |
| Medion        | MS-7707                     | Desktop     | [563fc4ee5a](https://linux-hardware.org/?probe=563fc4ee5a) | Feb 23, 2022 |
| Medion        | MS-7707                     | Desktop     | [f3b9e8796b](https://linux-hardware.org/?probe=f3b9e8796b) | Feb 23, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [b83fdc23d3](https://linux-hardware.org/?probe=b83fdc23d3) | Feb 23, 2022 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [e224468100](https://linux-hardware.org/?probe=e224468100) | Feb 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [1c1f4685eb](https://linux-hardware.org/?probe=1c1f4685eb) | Feb 22, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [6c5203e00a](https://linux-hardware.org/?probe=6c5203e00a) | Feb 22, 2022 |
| Acer          | V5-171                      | Notebook    | [2ef877834d](https://linux-hardware.org/?probe=2ef877834d) | Feb 22, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [320aa1e42f](https://linux-hardware.org/?probe=320aa1e42f) | Feb 22, 2022 |
| Gigabyte      | P64V7                       | Notebook    | [fdac76c228](https://linux-hardware.org/?probe=fdac76c228) | Feb 22, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [8efe63496f](https://linux-hardware.org/?probe=8efe63496f) | Feb 22, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [979289afcb](https://linux-hardware.org/?probe=979289afcb) | Feb 21, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [9e9fdbfba5](https://linux-hardware.org/?probe=9e9fdbfba5) | Feb 21, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [10cb1ec92a](https://linux-hardware.org/?probe=10cb1ec92a) | Feb 21, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [62fc974ec7](https://linux-hardware.org/?probe=62fc974ec7) | Feb 21, 2022 |
| Toshiba       | Satellite S55t-C            | Notebook    | [45b90ca745](https://linux-hardware.org/?probe=45b90ca745) | Feb 21, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [c857a2c621](https://linux-hardware.org/?probe=c857a2c621) | Feb 21, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [362ee918ac](https://linux-hardware.org/?probe=362ee918ac) | Feb 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [85c2284ffa](https://linux-hardware.org/?probe=85c2284ffa) | Feb 21, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [a2949c69ea](https://linux-hardware.org/?probe=a2949c69ea) | Feb 21, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [435006f81f](https://linux-hardware.org/?probe=435006f81f) | Feb 20, 2022 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [9264e93f98](https://linux-hardware.org/?probe=9264e93f98) | Feb 20, 2022 |
| Multilaser    | PC130                       | Notebook    | [4a49294d21](https://linux-hardware.org/?probe=4a49294d21) | Feb 20, 2022 |
| Multilaser    | PC130                       | Notebook    | [4681b7ae9e](https://linux-hardware.org/?probe=4681b7ae9e) | Feb 20, 2022 |
| Dell          | Studio 1555                 | Notebook    | [19d02a6eb8](https://linux-hardware.org/?probe=19d02a6eb8) | Feb 20, 2022 |
| Dell          | Precision M4800             | Notebook    | [9734390386](https://linux-hardware.org/?probe=9734390386) | Feb 19, 2022 |
| GEO           | GeoBook 120                 | Notebook    | [3eeed29e23](https://linux-hardware.org/?probe=3eeed29e23) | Feb 19, 2022 |
| GEO           | GeoBook 120                 | Notebook    | [5c26a23921](https://linux-hardware.org/?probe=5c26a23921) | Feb 19, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f091d19c91](https://linux-hardware.org/?probe=f091d19c91) | Feb 19, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [1990e2040f](https://linux-hardware.org/?probe=1990e2040f) | Feb 19, 2022 |
| Google        | Akemi                       | Notebook    | [fc9b479395](https://linux-hardware.org/?probe=fc9b479395) | Feb 19, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4425c178f2](https://linux-hardware.org/?probe=4425c178f2) | Feb 19, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [bcbc783948](https://linux-hardware.org/?probe=bcbc783948) | Feb 19, 2022 |
| Lenovo        | ThinkPad T61 7658CTO        | Notebook    | [99465a8eb3](https://linux-hardware.org/?probe=99465a8eb3) | Feb 19, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [aad26f0aa8](https://linux-hardware.org/?probe=aad26f0aa8) | Feb 19, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [413a122ef8](https://linux-hardware.org/?probe=413a122ef8) | Feb 19, 2022 |
| Lenovo        | ThinkPad T440 20B7008ABR    | Notebook    | [b690de8548](https://linux-hardware.org/?probe=b690de8548) | Feb 19, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [bc37eeb385](https://linux-hardware.org/?probe=bc37eeb385) | Feb 19, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [0db1efa0f5](https://linux-hardware.org/?probe=0db1efa0f5) | Feb 18, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [e5dd39a008](https://linux-hardware.org/?probe=e5dd39a008) | Feb 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c545739154](https://linux-hardware.org/?probe=c545739154) | Feb 18, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [c204579cc4](https://linux-hardware.org/?probe=c204579cc4) | Feb 18, 2022 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [bccc2f8988](https://linux-hardware.org/?probe=bccc2f8988) | Feb 18, 2022 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [43a7b2c585](https://linux-hardware.org/?probe=43a7b2c585) | Feb 18, 2022 |
| ASUSTek       | A4110                       | All in one  | [8fd1f10c40](https://linux-hardware.org/?probe=8fd1f10c40) | Feb 18, 2022 |
| Gigabyte      | P64V7                       | Notebook    | [646aa28c13](https://linux-hardware.org/?probe=646aa28c13) | Feb 18, 2022 |
| Dell          | Latitude 5179               | Notebook    | [b28766add3](https://linux-hardware.org/?probe=b28766add3) | Feb 18, 2022 |
| MSI           | B360M PRO-VDH               | Desktop     | [dfb03c38d4](https://linux-hardware.org/?probe=dfb03c38d4) | Feb 18, 2022 |
| HP            | 255 G2                      | Notebook    | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | Notebook    | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| Acer          | Predator G9-792             | Notebook    | [e516ba85b9](https://linux-hardware.org/?probe=e516ba85b9) | Feb 17, 2022 |
| HP            | OMEN Notebook               | Notebook    | [a952f9c2f2](https://linux-hardware.org/?probe=a952f9c2f2) | Feb 17, 2022 |
| ASUSTek       | ZenBook UX334FL_UX334FL     | Notebook    | [89c2a0f939](https://linux-hardware.org/?probe=89c2a0f939) | Feb 17, 2022 |
| Lenovo        | ThinkPad Edge E530 32599... | Notebook    | [d6fafc8b8b](https://linux-hardware.org/?probe=d6fafc8b8b) | Feb 17, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [59f1a1a3e0](https://linux-hardware.org/?probe=59f1a1a3e0) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a62793c371](https://linux-hardware.org/?probe=a62793c371) | Feb 16, 2022 |
| ASUSTek       | A4110                       | All in one  | [1bbadb977d](https://linux-hardware.org/?probe=1bbadb977d) | Feb 16, 2022 |
| ASUSTek       | A4110                       | All in one  | [ede6469471](https://linux-hardware.org/?probe=ede6469471) | Feb 16, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [9abcb12076](https://linux-hardware.org/?probe=9abcb12076) | Feb 16, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [311429d9ef](https://linux-hardware.org/?probe=311429d9ef) | Feb 16, 2022 |
| Dell          | Vostro 1700                 | Notebook    | [efaa6a2512](https://linux-hardware.org/?probe=efaa6a2512) | Feb 16, 2022 |
| Dell          | Vostro 1700                 | Notebook    | [d003670f08](https://linux-hardware.org/?probe=d003670f08) | Feb 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [497a009b81](https://linux-hardware.org/?probe=497a009b81) | Feb 15, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [e52f9b0748](https://linux-hardware.org/?probe=e52f9b0748) | Feb 15, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [70b0938bc3](https://linux-hardware.org/?probe=70b0938bc3) | Feb 15, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [918d93ea7a](https://linux-hardware.org/?probe=918d93ea7a) | Feb 15, 2022 |
| Acer          | E1-510                      | Notebook    | [0120aaf250](https://linux-hardware.org/?probe=0120aaf250) | Feb 15, 2022 |
| Acer          | E1-510                      | Notebook    | [7a3678f7d1](https://linux-hardware.org/?probe=7a3678f7d1) | Feb 15, 2022 |
| HP            | 2B15A                       | Desktop     | [ca58e13d8f](https://linux-hardware.org/?probe=ca58e13d8f) | Feb 15, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [092df404d4](https://linux-hardware.org/?probe=092df404d4) | Feb 15, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [54a56f3b09](https://linux-hardware.org/?probe=54a56f3b09) | Feb 15, 2022 |
| Dell          | Latitude 9420               | Convertible | [ded4b64e52](https://linux-hardware.org/?probe=ded4b64e52) | Feb 15, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [8306c2af49](https://linux-hardware.org/?probe=8306c2af49) | Feb 15, 2022 |
| Intel         | X79M-S                      | Desktop     | [b655865606](https://linux-hardware.org/?probe=b655865606) | Feb 14, 2022 |
| Dell          | Vostro 1500                 | Notebook    | [1780b4d18b](https://linux-hardware.org/?probe=1780b4d18b) | Feb 14, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [79e65b1e06](https://linux-hardware.org/?probe=79e65b1e06) | Feb 14, 2022 |
| IBM           | 81077AG                     | Desktop     | [934878ed63](https://linux-hardware.org/?probe=934878ed63) | Feb 14, 2022 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [c3c921f8e2](https://linux-hardware.org/?probe=c3c921f8e2) | Feb 14, 2022 |
| Lenovo        | ThinkPad T420 4178A47       | Notebook    | [cda9da09dc](https://linux-hardware.org/?probe=cda9da09dc) | Feb 14, 2022 |
| ASUSTek       | P8H61-M EVO                 | Desktop     | [40ed7abcc5](https://linux-hardware.org/?probe=40ed7abcc5) | Feb 14, 2022 |
| e-shop.gr     | V113                        | Notebook    | [e9a1ae2e96](https://linux-hardware.org/?probe=e9a1ae2e96) | Feb 14, 2022 |
| ASRock        | X299 Taichi                 | Desktop     | [cb4047cf07](https://linux-hardware.org/?probe=cb4047cf07) | Feb 13, 2022 |
| ASUSTek       | P8H61-M EVO                 | Desktop     | [94bcb91d02](https://linux-hardware.org/?probe=94bcb91d02) | Feb 13, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [0412384bc2](https://linux-hardware.org/?probe=0412384bc2) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [be994742e1](https://linux-hardware.org/?probe=be994742e1) | Feb 13, 2022 |
| HP            | Unknown                     | Notebook    | [2f4edd8b04](https://linux-hardware.org/?probe=2f4edd8b04) | Feb 13, 2022 |
| HP            | Unknown                     | Notebook    | [1284e8c58f](https://linux-hardware.org/?probe=1284e8c58f) | Feb 13, 2022 |
| ASRock        | 970A-G                      | Desktop     | [7b3694013f](https://linux-hardware.org/?probe=7b3694013f) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eeeac91ae4](https://linux-hardware.org/?probe=eeeac91ae4) | Feb 13, 2022 |
| Toshiba       | Satellite C50-A283          | Notebook    | [66f810c5f5](https://linux-hardware.org/?probe=66f810c5f5) | Feb 13, 2022 |
| HP            | 0B54h D                     | Desktop     | [c9f9611ea4](https://linux-hardware.org/?probe=c9f9611ea4) | Feb 12, 2022 |
| e-shop.gr     | V113                        | Notebook    | [6d015f399b](https://linux-hardware.org/?probe=6d015f399b) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d97414cfe4](https://linux-hardware.org/?probe=d97414cfe4) | Feb 12, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [7ae6513197](https://linux-hardware.org/?probe=7ae6513197) | Feb 12, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [bd8bfe9447](https://linux-hardware.org/?probe=bd8bfe9447) | Feb 12, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [a9034f065e](https://linux-hardware.org/?probe=a9034f065e) | Feb 11, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [fc3d05ce13](https://linux-hardware.org/?probe=fc3d05ce13) | Feb 11, 2022 |
| Sony          | VGN-Z575FN                  | Notebook    | [4998f7ae6d](https://linux-hardware.org/?probe=4998f7ae6d) | Feb 11, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [c0cce21524](https://linux-hardware.org/?probe=c0cce21524) | Feb 11, 2022 |
| Intel         | H61                         | Desktop     | [e06357425a](https://linux-hardware.org/?probe=e06357425a) | Feb 11, 2022 |
| HP            | ProBook 4525s               | Notebook    | [2db6879863](https://linux-hardware.org/?probe=2db6879863) | Feb 11, 2022 |
| MSI           | A75A-G35                    | Desktop     | [47677a6e5f](https://linux-hardware.org/?probe=47677a6e5f) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [b79b4aaf10](https://linux-hardware.org/?probe=b79b4aaf10) | Feb 11, 2022 |
| HP            | 198E                        | Desktop     | [f4781dd683](https://linux-hardware.org/?probe=f4781dd683) | Feb 10, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [092acae00b](https://linux-hardware.org/?probe=092acae00b) | Feb 10, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [804f3b74e0](https://linux-hardware.org/?probe=804f3b74e0) | Feb 10, 2022 |
| ASUSTek       | TUF GAMING Z690-PLUS WIF... | Desktop     | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [9e1c3acaf3](https://linux-hardware.org/?probe=9e1c3acaf3) | Feb 10, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [c56c62ab01](https://linux-hardware.org/?probe=c56c62ab01) | Feb 10, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [3dffdcc5d3](https://linux-hardware.org/?probe=3dffdcc5d3) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [e86fa9ee02](https://linux-hardware.org/?probe=e86fa9ee02) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [1b6aa0ce08](https://linux-hardware.org/?probe=1b6aa0ce08) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [961be2a608](https://linux-hardware.org/?probe=961be2a608) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [4ab26645c2](https://linux-hardware.org/?probe=4ab26645c2) | Feb 09, 2022 |
| HP            | 550                         | Notebook    | [7e286dd830](https://linux-hardware.org/?probe=7e286dd830) | Feb 08, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [2558403513](https://linux-hardware.org/?probe=2558403513) | Feb 08, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [f37984fec2](https://linux-hardware.org/?probe=f37984fec2) | Feb 08, 2022 |
| HP            | 8350                        | Desktop     | [31f2f10b25](https://linux-hardware.org/?probe=31f2f10b25) | Feb 08, 2022 |
| HP            | 1906                        | Desktop     | [c2107ad290](https://linux-hardware.org/?probe=c2107ad290) | Feb 08, 2022 |
| HP            | 1906                        | Desktop     | [9f08673e43](https://linux-hardware.org/?probe=9f08673e43) | Feb 08, 2022 |
| MSI           | 2AE0                        | Desktop     | [7026cf0c86](https://linux-hardware.org/?probe=7026cf0c86) | Feb 07, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [8233b1191c](https://linux-hardware.org/?probe=8233b1191c) | Feb 07, 2022 |
| ASUSTek       | TUF GAMING B460M-PLUS       | Desktop     | [cec6148a23](https://linux-hardware.org/?probe=cec6148a23) | Feb 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| MSI           | B85M-E45                    | Desktop     | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Dell          | 09CGW2 A13                  | Server      | [bcdccddec2](https://linux-hardware.org/?probe=bcdccddec2) | Feb 07, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [d14b339c4f](https://linux-hardware.org/?probe=d14b339c4f) | Feb 07, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | Desktop     | [c5db8c7811](https://linux-hardware.org/?probe=c5db8c7811) | Feb 06, 2022 |
| ASUSTek       | T101HA                      | Notebook    | [3ec67a3424](https://linux-hardware.org/?probe=3ec67a3424) | Feb 06, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | Desktop     | [96e92c90a5](https://linux-hardware.org/?probe=96e92c90a5) | Feb 06, 2022 |
| Dell          | Vostro 1700                 | Notebook    | [56ab8ae4cc](https://linux-hardware.org/?probe=56ab8ae4cc) | Feb 06, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [dd6e3f3a64](https://linux-hardware.org/?probe=dd6e3f3a64) | Feb 06, 2022 |
| HP            | 635                         | Notebook    | [3f689c9c23](https://linux-hardware.org/?probe=3f689c9c23) | Feb 06, 2022 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [5ef683a8ed](https://linux-hardware.org/?probe=5ef683a8ed) | Feb 06, 2022 |
| Quanta        | XV1                         | All in one  | [da739641d3](https://linux-hardware.org/?probe=da739641d3) | Feb 06, 2022 |
| ASUSTek       | TUF GAMING X570-PRO WIFI... | Desktop     | [81b3cfa233](https://linux-hardware.org/?probe=81b3cfa233) | Feb 06, 2022 |
| Acer          | Aspire TC-115               | Desktop     | [03188d20fc](https://linux-hardware.org/?probe=03188d20fc) | Feb 05, 2022 |
| ASUSTek       | X405UA                      | Notebook    | [bf196d4470](https://linux-hardware.org/?probe=bf196d4470) | Feb 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [7848918b1d](https://linux-hardware.org/?probe=7848918b1d) | Feb 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [b1106ffeae](https://linux-hardware.org/?probe=b1106ffeae) | Feb 05, 2022 |
| ASUSTek       | ROG Strix G513QR            | Notebook    | [f562940afa](https://linux-hardware.org/?probe=f562940afa) | Feb 05, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [a4e86f6259](https://linux-hardware.org/?probe=a4e86f6259) | Feb 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [25fa8ea018](https://linux-hardware.org/?probe=25fa8ea018) | Feb 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [4b20e9f979](https://linux-hardware.org/?probe=4b20e9f979) | Feb 04, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [80cf2c4065](https://linux-hardware.org/?probe=80cf2c4065) | Feb 04, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [3f45fd6cf2](https://linux-hardware.org/?probe=3f45fd6cf2) | Feb 03, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [71b93f7b57](https://linux-hardware.org/?probe=71b93f7b57) | Feb 03, 2022 |
| ASUSTek       | Maximus V GENE              | Desktop     | [749946734b](https://linux-hardware.org/?probe=749946734b) | Feb 03, 2022 |
| HP            | 2B3B                        | All in one  | [b3dccf594c](https://linux-hardware.org/?probe=b3dccf594c) | Feb 03, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [5bb62c21b7](https://linux-hardware.org/?probe=5bb62c21b7) | Feb 03, 2022 |
| Novatech      | 15.6 nSpire Laptop          | Notebook    | [6fe78d2f4b](https://linux-hardware.org/?probe=6fe78d2f4b) | Feb 02, 2022 |
| HP            | ProBook 4310s               | Notebook    | [6d2a66aa1e](https://linux-hardware.org/?probe=6d2a66aa1e) | Feb 02, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [5683d776e0](https://linux-hardware.org/?probe=5683d776e0) | Feb 02, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [e14121100b](https://linux-hardware.org/?probe=e14121100b) | Feb 02, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [421c016644](https://linux-hardware.org/?probe=421c016644) | Feb 02, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [ae25a7a57d](https://linux-hardware.org/?probe=ae25a7a57d) | Feb 02, 2022 |
| Dell          | Inspiron 5748               | Notebook    | [07c8076d3e](https://linux-hardware.org/?probe=07c8076d3e) | Feb 01, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [3e6d5943dd](https://linux-hardware.org/?probe=3e6d5943dd) | Feb 01, 2022 |
| HP            | Pavilion Laptop 15z-eh00... | Notebook    | [76a973d25c](https://linux-hardware.org/?probe=76a973d25c) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [b76b53bf53](https://linux-hardware.org/?probe=b76b53bf53) | Feb 01, 2022 |
| RCA           | W101SA23T2                  | Tablet      | [40bb04e3a3](https://linux-hardware.org/?probe=40bb04e3a3) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [45f03f7991](https://linux-hardware.org/?probe=45f03f7991) | Jan 31, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [70e86eb89a](https://linux-hardware.org/?probe=70e86eb89a) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | Notebook    | [cf01ca64c3](https://linux-hardware.org/?probe=cf01ca64c3) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | Notebook    | [17015b4fbe](https://linux-hardware.org/?probe=17015b4fbe) | Jan 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [690eba21e0](https://linux-hardware.org/?probe=690eba21e0) | Jan 30, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [af1d1e8c47](https://linux-hardware.org/?probe=af1d1e8c47) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [7450ea2cad](https://linux-hardware.org/?probe=7450ea2cad) | Jan 30, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [05fc3bd63b](https://linux-hardware.org/?probe=05fc3bd63b) | Jan 29, 2022 |
| Dell          | Latitude E5420              | Notebook    | [89a74ff338](https://linux-hardware.org/?probe=89a74ff338) | Jan 29, 2022 |
| HP            | 3047h                       | Desktop     | [48f624cbea](https://linux-hardware.org/?probe=48f624cbea) | Jan 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [504e2036d3](https://linux-hardware.org/?probe=504e2036d3) | Jan 29, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [bcdcd2eeb6](https://linux-hardware.org/?probe=bcdcd2eeb6) | Jan 29, 2022 |
| Dell          | Latitude E6220              | Notebook    | [808db5a1c8](https://linux-hardware.org/?probe=808db5a1c8) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [95423d6649](https://linux-hardware.org/?probe=95423d6649) | Jan 28, 2022 |
| MSI           | 2AE0                        | Desktop     | [1a55336eb9](https://linux-hardware.org/?probe=1a55336eb9) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | Notebook    | [ccc3361d04](https://linux-hardware.org/?probe=ccc3361d04) | Jan 28, 2022 |
| HP            | 2B3B                        | All in one  | [35e4a2dffb](https://linux-hardware.org/?probe=35e4a2dffb) | Jan 28, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | Desktop     | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [0143cbef50](https://linux-hardware.org/?probe=0143cbef50) | Jan 28, 2022 |
| Wortmann      | TERRA_PC                    | Desktop     | [4fea20e2bf](https://linux-hardware.org/?probe=4fea20e2bf) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | Notebook    | [6b9b9f727e](https://linux-hardware.org/?probe=6b9b9f727e) | Jan 28, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [1a1b794c06](https://linux-hardware.org/?probe=1a1b794c06) | Jan 28, 2022 |
| Jumper        | EZbook                      | Notebook    | [4fa449c0ce](https://linux-hardware.org/?probe=4fa449c0ce) | Jan 27, 2022 |
| Acer          | Aspire 5552                 | Notebook    | [ef57c29f8c](https://linux-hardware.org/?probe=ef57c29f8c) | Jan 27, 2022 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [78f310c42a](https://linux-hardware.org/?probe=78f310c42a) | Jan 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0977601aad](https://linux-hardware.org/?probe=0977601aad) | Jan 27, 2022 |
| ASRock        | G31M-S                      | Desktop     | [e579ce1757](https://linux-hardware.org/?probe=e579ce1757) | Jan 26, 2022 |
| HP            | Pavilion dv7                | Notebook    | [927e580b5a](https://linux-hardware.org/?probe=927e580b5a) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [2c70e74055](https://linux-hardware.org/?probe=2c70e74055) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [6a692a4e11](https://linux-hardware.org/?probe=6a692a4e11) | Jan 26, 2022 |
| ASUSTek       | ROG Strix G513QR            | Notebook    | [fb81914651](https://linux-hardware.org/?probe=fb81914651) | Jan 26, 2022 |
| HP            | 2B3B                        | All in one  | [44d4e60321](https://linux-hardware.org/?probe=44d4e60321) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | Desktop     | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | Desktop     | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Lenovo        | ThinkPad X61 7673C44        | Notebook    | [ab461bd99e](https://linux-hardware.org/?probe=ab461bd99e) | Jan 26, 2022 |
| Dell          | 07KY25 A00                  | Desktop     | [102d10e806](https://linux-hardware.org/?probe=102d10e806) | Jan 26, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [75f4b47111](https://linux-hardware.org/?probe=75f4b47111) | Jan 26, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [dbc44c9f4a](https://linux-hardware.org/?probe=dbc44c9f4a) | Jan 25, 2022 |
| HP            | 1497                        | Desktop     | [a32eadf3ab](https://linux-hardware.org/?probe=a32eadf3ab) | Jan 25, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [693f4a0a48](https://linux-hardware.org/?probe=693f4a0a48) | Jan 25, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c639bc4c98](https://linux-hardware.org/?probe=c639bc4c98) | Jan 25, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [7078a1a373](https://linux-hardware.org/?probe=7078a1a373) | Jan 25, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [e521380180](https://linux-hardware.org/?probe=e521380180) | Jan 25, 2022 |
| ASUSTek       | Q87T                        | Desktop     | [1bcaa6dedf](https://linux-hardware.org/?probe=1bcaa6dedf) | Jan 24, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [ed5c6cf88d](https://linux-hardware.org/?probe=ed5c6cf88d) | Jan 24, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [b3aec22953](https://linux-hardware.org/?probe=b3aec22953) | Jan 24, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [31189769c5](https://linux-hardware.org/?probe=31189769c5) | Jan 24, 2022 |
| ASUSTek       | ROG Strix G513QR            | Notebook    | [a31fd268eb](https://linux-hardware.org/?probe=a31fd268eb) | Jan 24, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [5fa0a123f4](https://linux-hardware.org/?probe=5fa0a123f4) | Jan 24, 2022 |
| Dell          | Latitude E6420              | Notebook    | [1cf74dd114](https://linux-hardware.org/?probe=1cf74dd114) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [06eb5b9d8d](https://linux-hardware.org/?probe=06eb5b9d8d) | Jan 23, 2022 |
| Toshiba       | TECRA A9                    | Notebook    | [7ba32a721d](https://linux-hardware.org/?probe=7ba32a721d) | Jan 23, 2022 |
| Acer          | NC-E1-572-54208G            | Notebook    | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [e5723eaa42](https://linux-hardware.org/?probe=e5723eaa42) | Jan 23, 2022 |
| Clevo         | W24/250CU                   | Notebook    | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| ASUSTek       | T100TAS                     | Notebook    | [a37b7c51fd](https://linux-hardware.org/?probe=a37b7c51fd) | Jan 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a0034083eb](https://linux-hardware.org/?probe=a0034083eb) | Jan 22, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [2a8b893eb6](https://linux-hardware.org/?probe=2a8b893eb6) | Jan 22, 2022 |
| HP            | Laptop 14q-cs0xxx           | Notebook    | [ec9061dcb1](https://linux-hardware.org/?probe=ec9061dcb1) | Jan 22, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [4b5e81151e](https://linux-hardware.org/?probe=4b5e81151e) | Jan 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [af38735785](https://linux-hardware.org/?probe=af38735785) | Jan 22, 2022 |
| MSI           | A75A-G35                    | Desktop     | [e2148dff19](https://linux-hardware.org/?probe=e2148dff19) | Jan 22, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [0d0222d2e9](https://linux-hardware.org/?probe=0d0222d2e9) | Jan 21, 2022 |
| Dell          | 0CU409                      | Desktop     | [8fc6c3decf](https://linux-hardware.org/?probe=8fc6c3decf) | Jan 21, 2022 |
| Dell          | 0CU409                      | Desktop     | [953718318f](https://linux-hardware.org/?probe=953718318f) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4c95ae549f](https://linux-hardware.org/?probe=4c95ae549f) | Jan 21, 2022 |
| Dell          | Latitude E5470              | Notebook    | [df22d71530](https://linux-hardware.org/?probe=df22d71530) | Jan 21, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [81cbc7d48a](https://linux-hardware.org/?probe=81cbc7d48a) | Jan 21, 2022 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [a89dd04d3a](https://linux-hardware.org/?probe=a89dd04d3a) | Jan 20, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [c56fbf1529](https://linux-hardware.org/?probe=c56fbf1529) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c996d7e988](https://linux-hardware.org/?probe=c996d7e988) | Jan 20, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [8d54c83082](https://linux-hardware.org/?probe=8d54c83082) | Jan 20, 2022 |
| HP            | Notebook                    | Notebook    | [25a9e6d8a1](https://linux-hardware.org/?probe=25a9e6d8a1) | Jan 20, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [99ff6cb58a](https://linux-hardware.org/?probe=99ff6cb58a) | Jan 20, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | Desktop     | [586012f45e](https://linux-hardware.org/?probe=586012f45e) | Jan 20, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e22a47facd](https://linux-hardware.org/?probe=e22a47facd) | Jan 20, 2022 |
| Acer          | Aspire V5-571PG             | Notebook    | [19c732cd05](https://linux-hardware.org/?probe=19c732cd05) | Jan 20, 2022 |
| Multilaser    | UB32X                       | Notebook    | [bd6f4152df](https://linux-hardware.org/?probe=bd6f4152df) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | Desktop     | [2ab8f0375c](https://linux-hardware.org/?probe=2ab8f0375c) | Jan 20, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [4544642750](https://linux-hardware.org/?probe=4544642750) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | Desktop     | [5308c77880](https://linux-hardware.org/?probe=5308c77880) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [81be3d94a3](https://linux-hardware.org/?probe=81be3d94a3) | Jan 18, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [d089029f6c](https://linux-hardware.org/?probe=d089029f6c) | Jan 18, 2022 |
| ASUSTek       | K93SV                       | Notebook    | [30f5830a2d](https://linux-hardware.org/?probe=30f5830a2d) | Jan 18, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ffaca9cabf](https://linux-hardware.org/?probe=ffaca9cabf) | Jan 18, 2022 |
| ASUSTek       | T100TAS                     | Notebook    | [86df8cdba1](https://linux-hardware.org/?probe=86df8cdba1) | Jan 18, 2022 |
| Acer          | Predator G9-792             | Notebook    | [06a6edfaae](https://linux-hardware.org/?probe=06a6edfaae) | Jan 17, 2022 |
| Oracle        | ASM, MOBO TRAY, CONC        | Server      | [a243fde4e1](https://linux-hardware.org/?probe=a243fde4e1) | Jan 17, 2022 |
| Oracle        | ASM, MOBO TRAY, CONC        | Server      | [621429f71f](https://linux-hardware.org/?probe=621429f71f) | Jan 17, 2022 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [bc94da6089](https://linux-hardware.org/?probe=bc94da6089) | Jan 17, 2022 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [149d38e543](https://linux-hardware.org/?probe=149d38e543) | Jan 17, 2022 |
| HP            | 15                          | Notebook    | [4dde4c5c0e](https://linux-hardware.org/?probe=4dde4c5c0e) | Jan 17, 2022 |
| Google        | Ultima                      | Notebook    | [d942b9081b](https://linux-hardware.org/?probe=d942b9081b) | Jan 16, 2022 |
| HP            | 250 G4                      | Notebook    | [4de0cf1eb0](https://linux-hardware.org/?probe=4de0cf1eb0) | Jan 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [940b702411](https://linux-hardware.org/?probe=940b702411) | Jan 16, 2022 |
| Lenovo        | ThinkPad T460s 20FAS09Y0... | Notebook    | [339ea299c8](https://linux-hardware.org/?probe=339ea299c8) | Jan 16, 2022 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [11bf29bdd1](https://linux-hardware.org/?probe=11bf29bdd1) | Jan 16, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [4bcdec655f](https://linux-hardware.org/?probe=4bcdec655f) | Jan 16, 2022 |
| Lenovo        | ThinkPad X230 2325WR3       | Notebook    | [decbecce89](https://linux-hardware.org/?probe=decbecce89) | Jan 16, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [04e666772c](https://linux-hardware.org/?probe=04e666772c) | Jan 15, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [7136b51cd1](https://linux-hardware.org/?probe=7136b51cd1) | Jan 15, 2022 |
| Positivo      | C464C                       | Convertible | [cbc3e3ed97](https://linux-hardware.org/?probe=cbc3e3ed97) | Jan 15, 2022 |
| MSI           | H61M-P25                    | Desktop     | [3433cb58a1](https://linux-hardware.org/?probe=3433cb58a1) | Jan 14, 2022 |
| Acer          | Aspire 5552                 | Notebook    | [5d3b462042](https://linux-hardware.org/?probe=5d3b462042) | Jan 14, 2022 |
| HP            | 3047h                       | Desktop     | [9a81422518](https://linux-hardware.org/?probe=9a81422518) | Jan 14, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [8545fedf93](https://linux-hardware.org/?probe=8545fedf93) | Jan 14, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [0607e7f57e](https://linux-hardware.org/?probe=0607e7f57e) | Jan 14, 2022 |
| MSI           | MS-7053                     | Desktop     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| MSI           | MS-7053                     | Desktop     | [61c46371e7](https://linux-hardware.org/?probe=61c46371e7) | Jan 13, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [6261e290d6](https://linux-hardware.org/?probe=6261e290d6) | Jan 13, 2022 |
| MSI           | H61M-P25                    | Desktop     | [c745684371](https://linux-hardware.org/?probe=c745684371) | Jan 13, 2022 |
| MSI           | H61M-P25                    | Desktop     | [f4fa2b39ad](https://linux-hardware.org/?probe=f4fa2b39ad) | Jan 13, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [de99d855c5](https://linux-hardware.org/?probe=de99d855c5) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [edb752adea](https://linux-hardware.org/?probe=edb752adea) | Jan 13, 2022 |
| ASUSTek       | K54C                        | Notebook    | [048477ec85](https://linux-hardware.org/?probe=048477ec85) | Jan 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [b694d6fa5f](https://linux-hardware.org/?probe=b694d6fa5f) | Jan 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [0f2222fc06](https://linux-hardware.org/?probe=0f2222fc06) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [eb7e68d366](https://linux-hardware.org/?probe=eb7e68d366) | Jan 13, 2022 |
| Razer         | Blade Stealth               | Notebook    | [3e3430ddeb](https://linux-hardware.org/?probe=3e3430ddeb) | Jan 13, 2022 |
| Acer          | Aspire E5-774G              | Notebook    | [bd6fa29ee0](https://linux-hardware.org/?probe=bd6fa29ee0) | Jan 13, 2022 |
| HP            | 2B3B                        | All in one  | [013bf0239d](https://linux-hardware.org/?probe=013bf0239d) | Jan 13, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [a4b1346944](https://linux-hardware.org/?probe=a4b1346944) | Jan 13, 2022 |
| EVGA          | 152-HR-E979                 | Desktop     | [669c7a3ef6](https://linux-hardware.org/?probe=669c7a3ef6) | Jan 12, 2022 |
| EVGA          | 152-HR-E979                 | Desktop     | [075a31a3c5](https://linux-hardware.org/?probe=075a31a3c5) | Jan 12, 2022 |
| Mediacom      | GTZS                        | Notebook    | [ad6de0b39b](https://linux-hardware.org/?probe=ad6de0b39b) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [086b27dc7a](https://linux-hardware.org/?probe=086b27dc7a) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [c7e776c4f2](https://linux-hardware.org/?probe=c7e776c4f2) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [c16f448f2e](https://linux-hardware.org/?probe=c16f448f2e) | Jan 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [e14f742bb9](https://linux-hardware.org/?probe=e14f742bb9) | Jan 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [62f049acf1](https://linux-hardware.org/?probe=62f049acf1) | Jan 12, 2022 |
| ASUSTek       | X542BA                      | Notebook    | [d5180ebfbc](https://linux-hardware.org/?probe=d5180ebfbc) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [368df270dc](https://linux-hardware.org/?probe=368df270dc) | Jan 11, 2022 |
| Acer          | Predator G9-792             | Notebook    | [870f7b6ea5](https://linux-hardware.org/?probe=870f7b6ea5) | Jan 11, 2022 |
| Acer          | Predator G9-792             | Notebook    | [908edac358](https://linux-hardware.org/?probe=908edac358) | Jan 11, 2022 |
| Dell          | Vostro 1500                 | Notebook    | [d81572b40f](https://linux-hardware.org/?probe=d81572b40f) | Jan 11, 2022 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | Notebook    | [4013d5dc28](https://linux-hardware.org/?probe=4013d5dc28) | Jan 11, 2022 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [b7ee3c3e93](https://linux-hardware.org/?probe=b7ee3c3e93) | Jan 11, 2022 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [5b08de311b](https://linux-hardware.org/?probe=5b08de311b) | Jan 10, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [3cd5068430](https://linux-hardware.org/?probe=3cd5068430) | Jan 10, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [98c10ce544](https://linux-hardware.org/?probe=98c10ce544) | Jan 10, 2022 |
| HP            | 2B3B                        | All in one  | [57472b76b7](https://linux-hardware.org/?probe=57472b76b7) | Jan 10, 2022 |
| HP            | ProBook 6450b               | Notebook    | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| HP            | 2B3B                        | All in one  | [f03a5fe290](https://linux-hardware.org/?probe=f03a5fe290) | Jan 10, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [cf21ff9bc1](https://linux-hardware.org/?probe=cf21ff9bc1) | Jan 09, 2022 |
| Dell          | Latitude E6510              | Notebook    | [df2d1f8aa1](https://linux-hardware.org/?probe=df2d1f8aa1) | Jan 09, 2022 |
| ASRock        | G31M-S                      | Desktop     | [1006244941](https://linux-hardware.org/?probe=1006244941) | Jan 09, 2022 |
| HP            | Pavilion 15                 | Notebook    | [95f3d87b66](https://linux-hardware.org/?probe=95f3d87b66) | Jan 09, 2022 |
| HP            | Compaq 8510p                | Notebook    | [94c5350957](https://linux-hardware.org/?probe=94c5350957) | Jan 09, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [c5d880e138](https://linux-hardware.org/?probe=c5d880e138) | Jan 09, 2022 |
| Unknown       | SCHNEIDER                   | Notebook    | [03b1f6dfed](https://linux-hardware.org/?probe=03b1f6dfed) | Jan 09, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [3a10a50e1f](https://linux-hardware.org/?probe=3a10a50e1f) | Jan 09, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [69a4959007](https://linux-hardware.org/?probe=69a4959007) | Jan 09, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [cdf5230fdb](https://linux-hardware.org/?probe=cdf5230fdb) | Jan 09, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [ddb6347103](https://linux-hardware.org/?probe=ddb6347103) | Jan 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [6759388aa1](https://linux-hardware.org/?probe=6759388aa1) | Jan 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [6a368aefbd](https://linux-hardware.org/?probe=6a368aefbd) | Jan 09, 2022 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [3b4d6e5abd](https://linux-hardware.org/?probe=3b4d6e5abd) | Jan 08, 2022 |
| ASRock        | G31M-S                      | Desktop     | [b33a983889](https://linux-hardware.org/?probe=b33a983889) | Jan 08, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [dd061ae267](https://linux-hardware.org/?probe=dd061ae267) | Jan 08, 2022 |
| MSI           | H61M-P25                    | Desktop     | [5f095c2bf8](https://linux-hardware.org/?probe=5f095c2bf8) | Jan 08, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [e6c704567e](https://linux-hardware.org/?probe=e6c704567e) | Jan 08, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [b2a3538121](https://linux-hardware.org/?probe=b2a3538121) | Jan 08, 2022 |
| ASRock        | AM1B-ITX                    | Desktop     | [c374329271](https://linux-hardware.org/?probe=c374329271) | Jan 07, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [e51ad2ec06](https://linux-hardware.org/?probe=e51ad2ec06) | Jan 07, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [95c067b96e](https://linux-hardware.org/?probe=95c067b96e) | Jan 07, 2022 |
| Dell          | 0YXT71 A02                  | Desktop     | [682c40786b](https://linux-hardware.org/?probe=682c40786b) | Jan 07, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [35884b0e77](https://linux-hardware.org/?probe=35884b0e77) | Jan 07, 2022 |
| MSI           | GE75 Raider 8SF             | Notebook    | [23aab4b14f](https://linux-hardware.org/?probe=23aab4b14f) | Jan 06, 2022 |
| ASUSTek       | X542BP                      | Notebook    | [1f13c19485](https://linux-hardware.org/?probe=1f13c19485) | Jan 06, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [398f9ebe03](https://linux-hardware.org/?probe=398f9ebe03) | Jan 06, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a46fcf64bb](https://linux-hardware.org/?probe=a46fcf64bb) | Jan 06, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [613096a5ad](https://linux-hardware.org/?probe=613096a5ad) | Jan 06, 2022 |
| HP            | Laptop 15s-dr0xxx           | Notebook    | [be60e498db](https://linux-hardware.org/?probe=be60e498db) | Jan 06, 2022 |
| HP            | ProBook 4510s               | Notebook    | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [1715a3e584](https://linux-hardware.org/?probe=1715a3e584) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | Notebook    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [5459dba29c](https://linux-hardware.org/?probe=5459dba29c) | Jan 06, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [2f03831c23](https://linux-hardware.org/?probe=2f03831c23) | Jan 05, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [e89e415451](https://linux-hardware.org/?probe=e89e415451) | Jan 05, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [fc860fdb7a](https://linux-hardware.org/?probe=fc860fdb7a) | Jan 05, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [dad1a9143d](https://linux-hardware.org/?probe=dad1a9143d) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [5694489e55](https://linux-hardware.org/?probe=5694489e55) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [c9ece2a64e](https://linux-hardware.org/?probe=c9ece2a64e) | Jan 05, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [a2ba361f2c](https://linux-hardware.org/?probe=a2ba361f2c) | Jan 05, 2022 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [ab12119d4f](https://linux-hardware.org/?probe=ab12119d4f) | Jan 05, 2022 |
| Acer          | E1-510                      | Notebook    | [f5a0998e25](https://linux-hardware.org/?probe=f5a0998e25) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B460M-PLUS       | Desktop     | [1ad802006b](https://linux-hardware.org/?probe=1ad802006b) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B460M-PLUS       | Desktop     | [32d0fda197](https://linux-hardware.org/?probe=32d0fda197) | Jan 05, 2022 |
| MSI           | H61M-P25                    | Desktop     | [16e6027ba2](https://linux-hardware.org/?probe=16e6027ba2) | Jan 04, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [2c3f24c851](https://linux-hardware.org/?probe=2c3f24c851) | Jan 04, 2022 |
| MSI           | H61M-P25                    | Desktop     | [3679d16bdb](https://linux-hardware.org/?probe=3679d16bdb) | Jan 04, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [a10e6b5ec0](https://linux-hardware.org/?probe=a10e6b5ec0) | Jan 04, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [929cea53e3](https://linux-hardware.org/?probe=929cea53e3) | Jan 04, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [827adb411f](https://linux-hardware.org/?probe=827adb411f) | Jan 04, 2022 |
| HP            | 3047h                       | Desktop     | [8faa43060a](https://linux-hardware.org/?probe=8faa43060a) | Jan 04, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [04b904c594](https://linux-hardware.org/?probe=04b904c594) | Jan 04, 2022 |
| MSI           | H61M-P25                    | Desktop     | [004392f0ef](https://linux-hardware.org/?probe=004392f0ef) | Jan 04, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4670daefab](https://linux-hardware.org/?probe=4670daefab) | Jan 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b838b1e1cc](https://linux-hardware.org/?probe=b838b1e1cc) | Jan 04, 2022 |
| NEC Comput... | PC-LL550RG                  | Notebook    | [43435578b7](https://linux-hardware.org/?probe=43435578b7) | Jan 04, 2022 |
| Toshiba       | TECRA A9                    | Notebook    | [783735cff8](https://linux-hardware.org/?probe=783735cff8) | Jan 04, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9f6ca62b59](https://linux-hardware.org/?probe=9f6ca62b59) | Jan 04, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [9062bc4b1d](https://linux-hardware.org/?probe=9062bc4b1d) | Jan 03, 2022 |
| Dell          | Inspiron 13-5378            | Notebook    | [8d019441d1](https://linux-hardware.org/?probe=8d019441d1) | Jan 03, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [d2a528221c](https://linux-hardware.org/?probe=d2a528221c) | Jan 03, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [22a9d41db0](https://linux-hardware.org/?probe=22a9d41db0) | Jan 02, 2022 |
| Dell          | Latitude E7440              | Notebook    | [9df6480d3e](https://linux-hardware.org/?probe=9df6480d3e) | Jan 02, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [1d759e7171](https://linux-hardware.org/?probe=1d759e7171) | Jan 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [6100abe0e1](https://linux-hardware.org/?probe=6100abe0e1) | Jan 02, 2022 |
| Dell          | Latitude E7440              | Notebook    | [60b74121ad](https://linux-hardware.org/?probe=60b74121ad) | Jan 02, 2022 |
| Lenovo        | ThinkPad T490 20N3S6US00    | Notebook    | [087fbff7d6](https://linux-hardware.org/?probe=087fbff7d6) | Jan 02, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [0e81199f2c](https://linux-hardware.org/?probe=0e81199f2c) | Jan 02, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [a0014a562d](https://linux-hardware.org/?probe=a0014a562d) | Jan 02, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [81a98f588a](https://linux-hardware.org/?probe=81a98f588a) | Jan 02, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Lenovo        | ThinkPad T490 20N3S6US00    | Notebook    | [f748f15a80](https://linux-hardware.org/?probe=f748f15a80) | Jan 01, 2022 |
| Jumper        | EZbook                      | Notebook    | [aed28b71f9](https://linux-hardware.org/?probe=aed28b71f9) | Jan 01, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [4754d83d04](https://linux-hardware.org/?probe=4754d83d04) | Jan 01, 2022 |
| MSI           | EX705                       | Notebook    | [a969bd4369](https://linux-hardware.org/?probe=a969bd4369) | Dec 31, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [0bfa74fa9f](https://linux-hardware.org/?probe=0bfa74fa9f) | Dec 31, 2021 |
| Acer          | Aspire M3970                | Desktop     | [e10ce7d132](https://linux-hardware.org/?probe=e10ce7d132) | Dec 31, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [dd99198f60](https://linux-hardware.org/?probe=dd99198f60) | Dec 31, 2021 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [5b97adba13](https://linux-hardware.org/?probe=5b97adba13) | Dec 31, 2021 |
| ECS           | G31T-M7                     | Desktop     | [8cd5d79924](https://linux-hardware.org/?probe=8cd5d79924) | Dec 31, 2021 |
| ECS           | G31T-M7                     | Desktop     | [9ebfb53472](https://linux-hardware.org/?probe=9ebfb53472) | Dec 31, 2021 |
| Dell          | 0DT021 A02                  | Server      | [4cc109a2ab](https://linux-hardware.org/?probe=4cc109a2ab) | Dec 31, 2021 |
| Dell          | 0DT021 A02                  | Server      | [f7becdb1ea](https://linux-hardware.org/?probe=f7becdb1ea) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [90d57a20ee](https://linux-hardware.org/?probe=90d57a20ee) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [4db624e8a0](https://linux-hardware.org/?probe=4db624e8a0) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b79e118712](https://linux-hardware.org/?probe=b79e118712) | Dec 31, 2021 |
| HP            | 1998                        | Desktop     | [07bdd01c09](https://linux-hardware.org/?probe=07bdd01c09) | Dec 31, 2021 |
| MSI           | GE-700                      | Notebook    | [9ccf434539](https://linux-hardware.org/?probe=9ccf434539) | Dec 31, 2021 |
| MSI           | GE-700                      | Notebook    | [dd9998069e](https://linux-hardware.org/?probe=dd9998069e) | Dec 31, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [fc547136cc](https://linux-hardware.org/?probe=fc547136cc) | Dec 31, 2021 |
| ASUSTek       | GL552VW                     | Notebook    | [42fd7ed22b](https://linux-hardware.org/?probe=42fd7ed22b) | Dec 31, 2021 |
| HP            | Pavilion dv5                | Notebook    | [7017ea359e](https://linux-hardware.org/?probe=7017ea359e) | Dec 31, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [2599126547](https://linux-hardware.org/?probe=2599126547) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [1c32c6a027](https://linux-hardware.org/?probe=1c32c6a027) | Dec 30, 2021 |
| MSI           | H81M-P33                    | Desktop     | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [7397141676](https://linux-hardware.org/?probe=7397141676) | Dec 30, 2021 |
| Acer          | Aspire 1810TZ               | Notebook    | [0b7bd5c1fa](https://linux-hardware.org/?probe=0b7bd5c1fa) | Dec 30, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| ASRock        | Z87 Pro4                    | Desktop     | [2a8588f61e](https://linux-hardware.org/?probe=2a8588f61e) | Dec 29, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [f20a77fa7e](https://linux-hardware.org/?probe=f20a77fa7e) | Dec 29, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [cef3f4f826](https://linux-hardware.org/?probe=cef3f4f826) | Dec 28, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5536599b58](https://linux-hardware.org/?probe=5536599b58) | Dec 28, 2021 |
| HP            | ProBook 4730s               | Notebook    | [08cca0b4b5](https://linux-hardware.org/?probe=08cca0b4b5) | Dec 28, 2021 |
| Lenovo        | ThinkPad L540 20AV0031MB    | Notebook    | [5abe6c6347](https://linux-hardware.org/?probe=5abe6c6347) | Dec 28, 2021 |
| ASUSTek       | X302LA                      | Notebook    | [3c747e6bb0](https://linux-hardware.org/?probe=3c747e6bb0) | Dec 28, 2021 |
| Dell          | Latitude 7490               | Notebook    | [044b1ea3d3](https://linux-hardware.org/?probe=044b1ea3d3) | Dec 28, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [127916f66f](https://linux-hardware.org/?probe=127916f66f) | Dec 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [55b2c93259](https://linux-hardware.org/?probe=55b2c93259) | Dec 28, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [edbe69efff](https://linux-hardware.org/?probe=edbe69efff) | Dec 28, 2021 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [82a0c6cd43](https://linux-hardware.org/?probe=82a0c6cd43) | Dec 28, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [82c3a0ea01](https://linux-hardware.org/?probe=82c3a0ea01) | Dec 28, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [fa2df1f6f0](https://linux-hardware.org/?probe=fa2df1f6f0) | Dec 27, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [60ba71333c](https://linux-hardware.org/?probe=60ba71333c) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | Notebook    | [1cd129ee35](https://linux-hardware.org/?probe=1cd129ee35) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | Notebook    | [f2deb9ec59](https://linux-hardware.org/?probe=f2deb9ec59) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | Desktop     | [cb83ad3d6c](https://linux-hardware.org/?probe=cb83ad3d6c) | Dec 27, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [adcf14bf31](https://linux-hardware.org/?probe=adcf14bf31) | Dec 27, 2021 |
| Microsoft     | Surface Go 3                | Tablet      | [e9c76dbca4](https://linux-hardware.org/?probe=e9c76dbca4) | Dec 26, 2021 |
| Intel         | Cherry Trail CR H91596-3... | Desktop     | [76e7cab82a](https://linux-hardware.org/?probe=76e7cab82a) | Dec 26, 2021 |
| Acer          | Aspire M5-481T              | Notebook    | [2515a869a5](https://linux-hardware.org/?probe=2515a869a5) | Dec 26, 2021 |
| Acer          | Aspire M5-481T              | Notebook    | [1ef9b940b2](https://linux-hardware.org/?probe=1ef9b940b2) | Dec 26, 2021 |
| Fusion5       | FWIN232_PLUS                | Notebook    | [ce10f25e8c](https://linux-hardware.org/?probe=ce10f25e8c) | Dec 25, 2021 |
| Dell          | Latitude 12 Rugged Table... | Notebook    | [13cc8e2abf](https://linux-hardware.org/?probe=13cc8e2abf) | Dec 25, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [39f562f189](https://linux-hardware.org/?probe=39f562f189) | Dec 25, 2021 |
| ASUSTek       | M50Vm                       | Notebook    | [bc36782a82](https://linux-hardware.org/?probe=bc36782a82) | Dec 25, 2021 |
| HP            | Pavilion dv7                | Notebook    | [67230f9226](https://linux-hardware.org/?probe=67230f9226) | Dec 25, 2021 |
| Dell          | Latitude 3440               | Notebook    | [e80fdcee0c](https://linux-hardware.org/?probe=e80fdcee0c) | Dec 25, 2021 |
| Dell          | 0VNP2H A00                  | Desktop     | [e64f51e52a](https://linux-hardware.org/?probe=e64f51e52a) | Dec 24, 2021 |
| Toshiba       | TECRA S11                   | Notebook    | [b846fd9c93](https://linux-hardware.org/?probe=b846fd9c93) | Dec 24, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| Dell          | Latitude 3540               | Notebook    | [7e7f291d68](https://linux-hardware.org/?probe=7e7f291d68) | Dec 24, 2021 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [5c4ae9536f](https://linux-hardware.org/?probe=5c4ae9536f) | Dec 24, 2021 |
| Gigabyte      | EG41MFT-US2H                | Desktop     | [2bfb4702c3](https://linux-hardware.org/?probe=2bfb4702c3) | Dec 23, 2021 |
| Gigabyte      | EG41MFT-US2H                | Desktop     | [b29d64341c](https://linux-hardware.org/?probe=b29d64341c) | Dec 23, 2021 |
| ASUSTek       | TUF GAMING X570-PRO WIFI... | Desktop     | [69d74c89b4](https://linux-hardware.org/?probe=69d74c89b4) | Dec 23, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [3415419b6b](https://linux-hardware.org/?probe=3415419b6b) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4453e33b88](https://linux-hardware.org/?probe=4453e33b88) | Dec 22, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [0832f6d0fd](https://linux-hardware.org/?probe=0832f6d0fd) | Dec 22, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [d1d6054fc3](https://linux-hardware.org/?probe=d1d6054fc3) | Dec 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [5823ca14b0](https://linux-hardware.org/?probe=5823ca14b0) | Dec 22, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [95f5a7b84d](https://linux-hardware.org/?probe=95f5a7b84d) | Dec 22, 2021 |
| ASUSTek       | P8Z77-M                     | Desktop     | [667e676c78](https://linux-hardware.org/?probe=667e676c78) | Dec 21, 2021 |
| ASUSTek       | K53E                        | Notebook    | [0a089d38c0](https://linux-hardware.org/?probe=0a089d38c0) | Dec 21, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [200701934f](https://linux-hardware.org/?probe=200701934f) | Dec 21, 2021 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [c38dcdb848](https://linux-hardware.org/?probe=c38dcdb848) | Dec 21, 2021 |
| Sony          | VGN-FW21E                   | Notebook    | [0c58cd8d69](https://linux-hardware.org/?probe=0c58cd8d69) | Dec 20, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [685819bc74](https://linux-hardware.org/?probe=685819bc74) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | Notebook    | [a7e83ee775](https://linux-hardware.org/?probe=a7e83ee775) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | Notebook    | [f10ab27170](https://linux-hardware.org/?probe=f10ab27170) | Dec 20, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [462b93b05b](https://linux-hardware.org/?probe=462b93b05b) | Dec 20, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [4384deed19](https://linux-hardware.org/?probe=4384deed19) | Dec 20, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [210f1589c4](https://linux-hardware.org/?probe=210f1589c4) | Dec 20, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [b40c57df26](https://linux-hardware.org/?probe=b40c57df26) | Dec 20, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [09d76b803c](https://linux-hardware.org/?probe=09d76b803c) | Dec 20, 2021 |
| HP            | 2B3B                        | All in one  | [583460f9ab](https://linux-hardware.org/?probe=583460f9ab) | Dec 20, 2021 |
| Intel         | B75                         | Desktop     | [9178fa9053](https://linux-hardware.org/?probe=9178fa9053) | Dec 19, 2021 |
| Digibras      | NH4CU03                     | Notebook    | [517425552d](https://linux-hardware.org/?probe=517425552d) | Dec 19, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [35182a65bb](https://linux-hardware.org/?probe=35182a65bb) | Dec 19, 2021 |
| Sony          | VGN-FW21E                   | Notebook    | [d90a22e7b0](https://linux-hardware.org/?probe=d90a22e7b0) | Dec 19, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [717b852409](https://linux-hardware.org/?probe=717b852409) | Dec 19, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [5189bf7726](https://linux-hardware.org/?probe=5189bf7726) | Dec 19, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [38a4bbf8d3](https://linux-hardware.org/?probe=38a4bbf8d3) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [2013d9d5d8](https://linux-hardware.org/?probe=2013d9d5d8) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [67286f0d11](https://linux-hardware.org/?probe=67286f0d11) | Dec 19, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [f86ed2049c](https://linux-hardware.org/?probe=f86ed2049c) | Dec 19, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [063c3ec5d2](https://linux-hardware.org/?probe=063c3ec5d2) | Dec 19, 2021 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [24fef50189](https://linux-hardware.org/?probe=24fef50189) | Dec 19, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [0dc23e59a4](https://linux-hardware.org/?probe=0dc23e59a4) | Dec 19, 2021 |
| HP            | 2B3B                        | All in one  | [4c39b178ad](https://linux-hardware.org/?probe=4c39b178ad) | Dec 19, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [6eab2c603a](https://linux-hardware.org/?probe=6eab2c603a) | Dec 19, 2021 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [4c845a464c](https://linux-hardware.org/?probe=4c845a464c) | Dec 19, 2021 |
| Acer          | Aspire XC-330               | Desktop     | [1803a4622c](https://linux-hardware.org/?probe=1803a4622c) | Dec 19, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [897b589a83](https://linux-hardware.org/?probe=897b589a83) | Dec 19, 2021 |
| ASUSTek       | Benicia                     | Desktop     | [e572d5ceff](https://linux-hardware.org/?probe=e572d5ceff) | Dec 19, 2021 |
| Shuttle       | FH61V                       | Desktop     | [39d341d8be](https://linux-hardware.org/?probe=39d341d8be) | Dec 19, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [68a3cbb84c](https://linux-hardware.org/?probe=68a3cbb84c) | Dec 18, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [20f9c7a4ef](https://linux-hardware.org/?probe=20f9c7a4ef) | Dec 18, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [6f860db242](https://linux-hardware.org/?probe=6f860db242) | Dec 18, 2021 |
| MSI           | MS-7053                     | Desktop     | [3e9330e811](https://linux-hardware.org/?probe=3e9330e811) | Dec 18, 2021 |
| MSI           | MS-7053                     | Desktop     | [b32db3cd18](https://linux-hardware.org/?probe=b32db3cd18) | Dec 18, 2021 |
| Dell          | Latitude E6500              | Notebook    | [5a29db9bdf](https://linux-hardware.org/?probe=5a29db9bdf) | Dec 18, 2021 |
| Lenovo        | ThinkPad X230 2325SYU       | Notebook    | [3b01a9e8eb](https://linux-hardware.org/?probe=3b01a9e8eb) | Dec 18, 2021 |
| Unknown       | C51GM-M                     | Desktop     | [91386c4f7c](https://linux-hardware.org/?probe=91386c4f7c) | Dec 17, 2021 |
| Lenovo        | ThinkCentre M57e 9489W1U    | Desktop     | [ba5156ef68](https://linux-hardware.org/?probe=ba5156ef68) | Dec 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [dda5e17a21](https://linux-hardware.org/?probe=dda5e17a21) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | Desktop     | [49e9492dd4](https://linux-hardware.org/?probe=49e9492dd4) | Dec 17, 2021 |
| Dell          | 0Y2K8N A01                  | Desktop     | [2e29930670](https://linux-hardware.org/?probe=2e29930670) | Dec 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [dfbadf6708](https://linux-hardware.org/?probe=dfbadf6708) | Dec 17, 2021 |
| Intel         | B75                         | Desktop     | [95258dab55](https://linux-hardware.org/?probe=95258dab55) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | Desktop     | [cd4d96fefa](https://linux-hardware.org/?probe=cd4d96fefa) | Dec 17, 2021 |
| Toshiba       | TECRA A9                    | Notebook    | [53cba6b9d1](https://linux-hardware.org/?probe=53cba6b9d1) | Dec 16, 2021 |
| Acer          | Aspire XC-330               | Desktop     | [61dd8de51b](https://linux-hardware.org/?probe=61dd8de51b) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | Notebook    | [58eb588f8b](https://linux-hardware.org/?probe=58eb588f8b) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | Notebook    | [84cabc70f7](https://linux-hardware.org/?probe=84cabc70f7) | Dec 16, 2021 |
| Dell          | 0D24M8 A01                  | Desktop     | [a306863279](https://linux-hardware.org/?probe=a306863279) | Dec 16, 2021 |
| Compaq        | Presario 21                 | Notebook    | [86e7a85db3](https://linux-hardware.org/?probe=86e7a85db3) | Dec 16, 2021 |
| Toshiba       | QOSMIO X770                 | Notebook    | [c8c9ab4cf8](https://linux-hardware.org/?probe=c8c9ab4cf8) | Dec 16, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [761a2419e5](https://linux-hardware.org/?probe=761a2419e5) | Dec 16, 2021 |
| RCA           | WT9503W004                  | Notebook    | [c858eb3cbc](https://linux-hardware.org/?probe=c858eb3cbc) | Dec 15, 2021 |
| Dell          | Latitude E6400              | Notebook    | [dc0d35221e](https://linux-hardware.org/?probe=dc0d35221e) | Dec 15, 2021 |
| HP            | EliteBook 8730w             | Notebook    | [e35ce8395b](https://linux-hardware.org/?probe=e35ce8395b) | Dec 15, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [d197761676](https://linux-hardware.org/?probe=d197761676) | Dec 15, 2021 |
| Google        | Squawks                     | Notebook    | [e75aa07dad](https://linux-hardware.org/?probe=e75aa07dad) | Dec 15, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [071a8f0709](https://linux-hardware.org/?probe=071a8f0709) | Dec 15, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [6cf66f6290](https://linux-hardware.org/?probe=6cf66f6290) | Dec 15, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [6ff1581ca6](https://linux-hardware.org/?probe=6ff1581ca6) | Dec 14, 2021 |
| Acer          | AOD255                      | Notebook    | [08a007120e](https://linux-hardware.org/?probe=08a007120e) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| HP            | 18E5                        | Desktop     | [88f87a7a1b](https://linux-hardware.org/?probe=88f87a7a1b) | Dec 14, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [11eea57427](https://linux-hardware.org/?probe=11eea57427) | Dec 14, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [0db50aad32](https://linux-hardware.org/?probe=0db50aad32) | Dec 14, 2021 |
| Digibras      | NH4CU03                     | Notebook    | [97b0f21219](https://linux-hardware.org/?probe=97b0f21219) | Dec 14, 2021 |
| HP            | 2179                        | All in one  | [c2dd79384a](https://linux-hardware.org/?probe=c2dd79384a) | Dec 14, 2021 |
| ASUSTek       | VM40B                       | Desktop     | [c53952beab](https://linux-hardware.org/?probe=c53952beab) | Dec 14, 2021 |
| MSI           | PS42 Modern 8RC             | Notebook    | [2686d73cb8](https://linux-hardware.org/?probe=2686d73cb8) | Dec 13, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [788c6b0550](https://linux-hardware.org/?probe=788c6b0550) | Dec 13, 2021 |
| Lenovo        | ThinkPad X270 20HN0043AD    | Notebook    | [24160af893](https://linux-hardware.org/?probe=24160af893) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | Desktop     | [b471a79340](https://linux-hardware.org/?probe=b471a79340) | Dec 13, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [447bffefc3](https://linux-hardware.org/?probe=447bffefc3) | Dec 13, 2021 |
| Google        | Squawks                     | Notebook    | [31cb595893](https://linux-hardware.org/?probe=31cb595893) | Dec 13, 2021 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [e2a6d57861](https://linux-hardware.org/?probe=e2a6d57861) | Dec 13, 2021 |
| Intel         | B75                         | Desktop     | [652828f7b9](https://linux-hardware.org/?probe=652828f7b9) | Dec 13, 2021 |
| Digibras      | NH4CU03                     | Notebook    | [5ffb383677](https://linux-hardware.org/?probe=5ffb383677) | Dec 13, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [6b33adaacf](https://linux-hardware.org/?probe=6b33adaacf) | Dec 13, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [aa92a82326](https://linux-hardware.org/?probe=aa92a82326) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | Desktop     | [8e659f2b89](https://linux-hardware.org/?probe=8e659f2b89) | Dec 12, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [54680bac44](https://linux-hardware.org/?probe=54680bac44) | Dec 12, 2021 |
| Dell          | Precision M4600             | Notebook    | [32034c26c7](https://linux-hardware.org/?probe=32034c26c7) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [abb6a94373](https://linux-hardware.org/?probe=abb6a94373) | Dec 12, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d364ff0c44](https://linux-hardware.org/?probe=d364ff0c44) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [d9e04ee743](https://linux-hardware.org/?probe=d9e04ee743) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [1d768c3c63](https://linux-hardware.org/?probe=1d768c3c63) | Dec 12, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [54846cdc88](https://linux-hardware.org/?probe=54846cdc88) | Dec 12, 2021 |
| Dell          | Latitude E5410              | Notebook    | [8b6bc5cf8e](https://linux-hardware.org/?probe=8b6bc5cf8e) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [7bf355c3c1](https://linux-hardware.org/?probe=7bf355c3c1) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [807bd77769](https://linux-hardware.org/?probe=807bd77769) | Dec 12, 2021 |
| Positivo      | CHT14B                      | Notebook    | [6ebdfd7b1f](https://linux-hardware.org/?probe=6ebdfd7b1f) | Dec 12, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [6a8480268d](https://linux-hardware.org/?probe=6a8480268d) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| Dell          | Precision M4600             | Notebook    | [f3f7be37a2](https://linux-hardware.org/?probe=f3f7be37a2) | Dec 12, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [0fb07d458a](https://linux-hardware.org/?probe=0fb07d458a) | Dec 12, 2021 |
| Acer          | Aspire A517-52              | Notebook    | [a51b1f9eb7](https://linux-hardware.org/?probe=a51b1f9eb7) | Dec 11, 2021 |
| Acer          | Aspire A517-52              | Notebook    | [bbf5c7ea28](https://linux-hardware.org/?probe=bbf5c7ea28) | Dec 11, 2021 |
| Dell          | Latitude E5400              | Notebook    | [2444de97e0](https://linux-hardware.org/?probe=2444de97e0) | Dec 11, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [a5528e8f98](https://linux-hardware.org/?probe=a5528e8f98) | Dec 11, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [493d55cb16](https://linux-hardware.org/?probe=493d55cb16) | Dec 11, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [1301218290](https://linux-hardware.org/?probe=1301218290) | Dec 11, 2021 |
| TCL Commun... | 8085                        | Notebook    | [3d795ceee0](https://linux-hardware.org/?probe=3d795ceee0) | Dec 11, 2021 |
| HP            | 339A                        | Desktop     | [7081fc45a3](https://linux-hardware.org/?probe=7081fc45a3) | Dec 11, 2021 |
| Dell          | Latitude E5400              | Notebook    | [212020992c](https://linux-hardware.org/?probe=212020992c) | Dec 11, 2021 |
| HP            | Pavilion dv3                | Notebook    | [484e48a117](https://linux-hardware.org/?probe=484e48a117) | Dec 11, 2021 |
| HP            | 304Ah                       | Desktop     | [6d87535158](https://linux-hardware.org/?probe=6d87535158) | Dec 10, 2021 |
| eMachines     | EL1850G                     | Desktop     | [ccd7758cbe](https://linux-hardware.org/?probe=ccd7758cbe) | Dec 10, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [3be4065d87](https://linux-hardware.org/?probe=3be4065d87) | Dec 10, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [c06d1d8915](https://linux-hardware.org/?probe=c06d1d8915) | Dec 10, 2021 |
| Dell          | Latitude E7440              | Notebook    | [ff067012c5](https://linux-hardware.org/?probe=ff067012c5) | Dec 09, 2021 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [eed2dcde15](https://linux-hardware.org/?probe=eed2dcde15) | Dec 09, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [028ad01454](https://linux-hardware.org/?probe=028ad01454) | Dec 09, 2021 |
| Biostar       | A320MH                      | Desktop     | [fbbe7a436a](https://linux-hardware.org/?probe=fbbe7a436a) | Dec 09, 2021 |
| Biostar       | A320MH                      | Desktop     | [3870a17dfe](https://linux-hardware.org/?probe=3870a17dfe) | Dec 09, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [cfa6005bc4](https://linux-hardware.org/?probe=cfa6005bc4) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [0e19f8e2ae](https://linux-hardware.org/?probe=0e19f8e2ae) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [a37d2cc42f](https://linux-hardware.org/?probe=a37d2cc42f) | Dec 09, 2021 |
| NEC Comput... | PC-TW508CAS                 | Tablet      | [06fe78096e](https://linux-hardware.org/?probe=06fe78096e) | Dec 09, 2021 |
| NEC Comput... | PC-TW508CAS                 | Tablet      | [7e305e10d6](https://linux-hardware.org/?probe=7e305e10d6) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [1a5b0a8d39](https://linux-hardware.org/?probe=1a5b0a8d39) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [f4d8f580dc](https://linux-hardware.org/?probe=f4d8f580dc) | Dec 09, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [836af3b8c6](https://linux-hardware.org/?probe=836af3b8c6) | Dec 08, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [c64aed90a9](https://linux-hardware.org/?probe=c64aed90a9) | Dec 08, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [a7d3526867](https://linux-hardware.org/?probe=a7d3526867) | Dec 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [dc07419c59](https://linux-hardware.org/?probe=dc07419c59) | Dec 08, 2021 |
| Dell          | Latitude E5400              | Notebook    | [a4fa2f67d3](https://linux-hardware.org/?probe=a4fa2f67d3) | Dec 08, 2021 |
| Lenovo        | ThinkPad T400 741722U       | Notebook    | [2739940ec1](https://linux-hardware.org/?probe=2739940ec1) | Dec 08, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [b041919f38](https://linux-hardware.org/?probe=b041919f38) | Dec 08, 2021 |
| HP            | 87C3                        | Desktop     | [16cc7e0bcb](https://linux-hardware.org/?probe=16cc7e0bcb) | Dec 07, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [c31f062314](https://linux-hardware.org/?probe=c31f062314) | Dec 07, 2021 |
| HP            | HDX 16                      | Notebook    | [cf114f9094](https://linux-hardware.org/?probe=cf114f9094) | Dec 07, 2021 |
| HP            | 339A                        | Desktop     | [50c24f7d34](https://linux-hardware.org/?probe=50c24f7d34) | Dec 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [9e9e0598b6](https://linux-hardware.org/?probe=9e9e0598b6) | Dec 07, 2021 |
| ZOTAC         | ZBOXNANO-ID62               | Mini pc     | [306fbc1b87](https://linux-hardware.org/?probe=306fbc1b87) | Dec 07, 2021 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [4853c251a8](https://linux-hardware.org/?probe=4853c251a8) | Dec 07, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [85d594af54](https://linux-hardware.org/?probe=85d594af54) | Dec 07, 2021 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [9c64eb115e](https://linux-hardware.org/?probe=9c64eb115e) | Dec 07, 2021 |
| Lenovo        | ThinkPad T400 741722U       | Notebook    | [2933ad8c69](https://linux-hardware.org/?probe=2933ad8c69) | Dec 07, 2021 |
| HP            | 81B4 01                     | Desktop     | [1477bd5a44](https://linux-hardware.org/?probe=1477bd5a44) | Dec 07, 2021 |
| Dell          | 0T656F A01                  | Desktop     | [552210319c](https://linux-hardware.org/?probe=552210319c) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [2ce114a1c7](https://linux-hardware.org/?probe=2ce114a1c7) | Dec 06, 2021 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [572b9da8d1](https://linux-hardware.org/?probe=572b9da8d1) | Dec 06, 2021 |
| Dell          | Inspiron 5748               | Notebook    | [77f278682e](https://linux-hardware.org/?probe=77f278682e) | Dec 06, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [f454c30e46](https://linux-hardware.org/?probe=f454c30e46) | Dec 05, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [3acb23e27c](https://linux-hardware.org/?probe=3acb23e27c) | Dec 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [fc540c3951](https://linux-hardware.org/?probe=fc540c3951) | Dec 05, 2021 |
| Dell          | Inspiron 5770               | Notebook    | [c8a717a1c9](https://linux-hardware.org/?probe=c8a717a1c9) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [ce3d88a2a2](https://linux-hardware.org/?probe=ce3d88a2a2) | Dec 05, 2021 |
| ASUSTek       | X553MA                      | Notebook    | [958551b7eb](https://linux-hardware.org/?probe=958551b7eb) | Dec 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [49fe509dd2](https://linux-hardware.org/?probe=49fe509dd2) | Dec 04, 2021 |
| Sony          | SVF1532Z1EB                 | Notebook    | [d65626b69d](https://linux-hardware.org/?probe=d65626b69d) | Dec 04, 2021 |
| ASUSTek       | X553MA                      | Notebook    | [78414b8bc4](https://linux-hardware.org/?probe=78414b8bc4) | Dec 04, 2021 |
| Lenovo        | G700                        | Notebook    | [2b7a430fcd](https://linux-hardware.org/?probe=2b7a430fcd) | Dec 04, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [4d64247a8a](https://linux-hardware.org/?probe=4d64247a8a) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [e6b7b57ea7](https://linux-hardware.org/?probe=e6b7b57ea7) | Dec 04, 2021 |
| Dell          | 0G254H A00                  | Desktop     | [11897b38da](https://linux-hardware.org/?probe=11897b38da) | Dec 03, 2021 |
| HP            | 2B44                        | Desktop     | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| ASUSTek       | K53TK                       | Notebook    | [043ef58552](https://linux-hardware.org/?probe=043ef58552) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [6c468accc0](https://linux-hardware.org/?probe=6c468accc0) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ee27adb248](https://linux-hardware.org/?probe=ee27adb248) | Dec 03, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [48e3c0e6c7](https://linux-hardware.org/?probe=48e3c0e6c7) | Dec 03, 2021 |
| HP            | OMEN Notebook               | Notebook    | [5b8b235c98](https://linux-hardware.org/?probe=5b8b235c98) | Dec 03, 2021 |
| Samsung       | 700T                        | Notebook    | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| Dell          | Latitude E6530              | Notebook    | [fe6dbdef48](https://linux-hardware.org/?probe=fe6dbdef48) | Dec 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [e39465a63b](https://linux-hardware.org/?probe=e39465a63b) | Dec 03, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [ad90caf60d](https://linux-hardware.org/?probe=ad90caf60d) | Dec 03, 2021 |
| Pegatron      | JESSE                       | Desktop     | [9091bacc33](https://linux-hardware.org/?probe=9091bacc33) | Dec 03, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [29ff3edb05](https://linux-hardware.org/?probe=29ff3edb05) | Dec 03, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [0e3a82aad6](https://linux-hardware.org/?probe=0e3a82aad6) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [c806323840](https://linux-hardware.org/?probe=c806323840) | Dec 03, 2021 |
| ASUSTek       | LEONITE                     | Desktop     | [704345be69](https://linux-hardware.org/?probe=704345be69) | Dec 03, 2021 |
| Dell          | Latitude 7280               | Notebook    | [8baf21a38d](https://linux-hardware.org/?probe=8baf21a38d) | Dec 02, 2021 |
| Biostar       | A780L3C                     | Desktop     | [a50e3d0532](https://linux-hardware.org/?probe=a50e3d0532) | Dec 02, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [25a3151fc1](https://linux-hardware.org/?probe=25a3151fc1) | Dec 02, 2021 |
| Foxconn       | 2A8C                        | Desktop     | [8d24862bd6](https://linux-hardware.org/?probe=8d24862bd6) | Dec 02, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9ae517f952](https://linux-hardware.org/?probe=9ae517f952) | Dec 02, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [57b4dae376](https://linux-hardware.org/?probe=57b4dae376) | Dec 02, 2021 |
| Biostar       | A780L3C                     | Desktop     | [497f29a343](https://linux-hardware.org/?probe=497f29a343) | Dec 02, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a6f2461500](https://linux-hardware.org/?probe=a6f2461500) | Dec 02, 2021 |
| HP            | 15                          | Notebook    | [8d1ef12e0e](https://linux-hardware.org/?probe=8d1ef12e0e) | Dec 02, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [ca49dc0eee](https://linux-hardware.org/?probe=ca49dc0eee) | Dec 02, 2021 |
| HP            | 15                          | Notebook    | [b374916ca6](https://linux-hardware.org/?probe=b374916ca6) | Dec 02, 2021 |
| Dell          | Inspiron 7791 2n1           | Convertible | [9d726bf2b9](https://linux-hardware.org/?probe=9d726bf2b9) | Dec 02, 2021 |
| Toshiba       | Satellite L55-B             | Notebook    | [0bc52401f0](https://linux-hardware.org/?probe=0bc52401f0) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [cb2302b704](https://linux-hardware.org/?probe=cb2302b704) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [f580be444b](https://linux-hardware.org/?probe=f580be444b) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [e2fbd06e2a](https://linux-hardware.org/?probe=e2fbd06e2a) | Dec 02, 2021 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [c7eeb775f9](https://linux-hardware.org/?probe=c7eeb775f9) | Dec 02, 2021 |
| HP            | 15                          | Notebook    | [cb278b1a6b](https://linux-hardware.org/?probe=cb278b1a6b) | Dec 02, 2021 |
| Dell          | Latitude E5570              | Notebook    | [d7beab52f4](https://linux-hardware.org/?probe=d7beab52f4) | Dec 02, 2021 |
| Avell High... | B.ON                        | Notebook    | [a7513f22ee](https://linux-hardware.org/?probe=a7513f22ee) | Dec 02, 2021 |
| Primux        | 15R5A                       | Notebook    | [3aef7d25e8](https://linux-hardware.org/?probe=3aef7d25e8) | Dec 01, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [1255f30eea](https://linux-hardware.org/?probe=1255f30eea) | Dec 01, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [bd33efb6f7](https://linux-hardware.org/?probe=bd33efb6f7) | Dec 01, 2021 |
| HP            | 339A                        | Desktop     | [4a377796cf](https://linux-hardware.org/?probe=4a377796cf) | Dec 01, 2021 |
| Dell          | 0PU052                      | Desktop     | [a943d9f217](https://linux-hardware.org/?probe=a943d9f217) | Dec 01, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [d51c794107](https://linux-hardware.org/?probe=d51c794107) | Nov 30, 2021 |
| ASUSTek       | X751LAB                     | Notebook    | [4383b601f4](https://linux-hardware.org/?probe=4383b601f4) | Nov 30, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5fa96d5863](https://linux-hardware.org/?probe=5fa96d5863) | Nov 30, 2021 |
| HP            | 8299                        | Desktop     | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| Medion        | MS-7707                     | Desktop     | [3d0a46f2ef](https://linux-hardware.org/?probe=3d0a46f2ef) | Nov 30, 2021 |
| MSI           | GF63 Thin 10SC              | Notebook    | [5f908f227a](https://linux-hardware.org/?probe=5f908f227a) | Nov 30, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [cecc697189](https://linux-hardware.org/?probe=cecc697189) | Nov 30, 2021 |
| ASRock        | H67DE3                      | Desktop     | [d710784470](https://linux-hardware.org/?probe=d710784470) | Nov 30, 2021 |
| HP            | 8299                        | Desktop     | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [24b15affa6](https://linux-hardware.org/?probe=24b15affa6) | Nov 29, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [0574fefb71](https://linux-hardware.org/?probe=0574fefb71) | Nov 29, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [3a2bf12582](https://linux-hardware.org/?probe=3a2bf12582) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [7184635417](https://linux-hardware.org/?probe=7184635417) | Nov 29, 2021 |
| Dell          | Latitude 7275               | Notebook    | [bf808d506c](https://linux-hardware.org/?probe=bf808d506c) | Nov 29, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [911b855817](https://linux-hardware.org/?probe=911b855817) | Nov 28, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [b8f87029fa](https://linux-hardware.org/?probe=b8f87029fa) | Nov 28, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [032a2baaca](https://linux-hardware.org/?probe=032a2baaca) | Nov 28, 2021 |
| Dell          | Latitude E5420              | Notebook    | [9f504b4e6b](https://linux-hardware.org/?probe=9f504b4e6b) | Nov 28, 2021 |
| ASUSTek       | P453UJ                      | Notebook    | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | Desktop     | [382bfc4a86](https://linux-hardware.org/?probe=382bfc4a86) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [cd296f933b](https://linux-hardware.org/?probe=cd296f933b) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [44c0cf428f](https://linux-hardware.org/?probe=44c0cf428f) | Nov 28, 2021 |
| MSI           | X370 GAMING PLUS            | Desktop     | [0b71d2652d](https://linux-hardware.org/?probe=0b71d2652d) | Nov 27, 2021 |
| Dell          | 0VNP2H A00                  | Desktop     | [803e55fd86](https://linux-hardware.org/?probe=803e55fd86) | Nov 27, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [df3010e1b8](https://linux-hardware.org/?probe=df3010e1b8) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ae57475767](https://linux-hardware.org/?probe=ae57475767) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3925ce16ae](https://linux-hardware.org/?probe=3925ce16ae) | Nov 27, 2021 |
| ASUSTek       | X455LJ                      | Notebook    | [018d5bcbac](https://linux-hardware.org/?probe=018d5bcbac) | Nov 27, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | Desktop     | [cd58d98b6a](https://linux-hardware.org/?probe=cd58d98b6a) | Nov 27, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [205025f3c7](https://linux-hardware.org/?probe=205025f3c7) | Nov 27, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [bb642022a6](https://linux-hardware.org/?probe=bb642022a6) | Nov 27, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [a0483c5539](https://linux-hardware.org/?probe=a0483c5539) | Nov 27, 2021 |
| ASRock        | ALiveNF6G-DVI               | Desktop     | [2761f434e8](https://linux-hardware.org/?probe=2761f434e8) | Nov 26, 2021 |
| Microsoft     | Surface Laptop 4            | Tablet      | [51711f9018](https://linux-hardware.org/?probe=51711f9018) | Nov 26, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [24645f6ab5](https://linux-hardware.org/?probe=24645f6ab5) | Nov 26, 2021 |
| Microsoft     | Surface Laptop 4            | Tablet      | [92fdb2f531](https://linux-hardware.org/?probe=92fdb2f531) | Nov 25, 2021 |
| HP            | 2179                        | All in one  | [121210497a](https://linux-hardware.org/?probe=121210497a) | Nov 25, 2021 |
| Dell          | 0VNP2H A00                  | Desktop     | [fe9de9a896](https://linux-hardware.org/?probe=fe9de9a896) | Nov 25, 2021 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | Notebook    | [25e2834604](https://linux-hardware.org/?probe=25e2834604) | Nov 25, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [757863f7de](https://linux-hardware.org/?probe=757863f7de) | Nov 25, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1462cc237c](https://linux-hardware.org/?probe=1462cc237c) | Nov 25, 2021 |
| Notebook      | NH50_70RA                   | Notebook    | [baa1c5d2ca](https://linux-hardware.org/?probe=baa1c5d2ca) | Nov 24, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [5e2d2a574d](https://linux-hardware.org/?probe=5e2d2a574d) | Nov 24, 2021 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [74894434bb](https://linux-hardware.org/?probe=74894434bb) | Nov 24, 2021 |
| ASUSTek       | GL552VW                     | Notebook    | [77929060f7](https://linux-hardware.org/?probe=77929060f7) | Nov 24, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [755b7b85f5](https://linux-hardware.org/?probe=755b7b85f5) | Nov 24, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [ca30b13118](https://linux-hardware.org/?probe=ca30b13118) | Nov 24, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| Acer          | Okinawa                     | Notebook    | [2953f32ed9](https://linux-hardware.org/?probe=2953f32ed9) | Nov 23, 2021 |
| HP            | Pavilion 17                 | Notebook    | [315037ddfd](https://linux-hardware.org/?probe=315037ddfd) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | Notebook    | [33a3597313](https://linux-hardware.org/?probe=33a3597313) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | Notebook    | [c1bf05d67a](https://linux-hardware.org/?probe=c1bf05d67a) | Nov 23, 2021 |
| HP            | 18E7                        | Desktop     | [7385ca30d4](https://linux-hardware.org/?probe=7385ca30d4) | Nov 23, 2021 |
| Pegatron      | 2A86E01                     | Desktop     | [b57d9ec4a4](https://linux-hardware.org/?probe=b57d9ec4a4) | Nov 23, 2021 |
| ASUSTek       | GL552VW                     | Notebook    | [59670a3933](https://linux-hardware.org/?probe=59670a3933) | Nov 23, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [83e388363c](https://linux-hardware.org/?probe=83e388363c) | Nov 23, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [56ff76e064](https://linux-hardware.org/?probe=56ff76e064) | Nov 23, 2021 |
| Dell          | 0PU052                      | Desktop     | [a41541bab5](https://linux-hardware.org/?probe=a41541bab5) | Nov 23, 2021 |
| ASUSTek       | G750JX                      | Notebook    | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [8031417427](https://linux-hardware.org/?probe=8031417427) | Nov 23, 2021 |
| HP            | Pavilion dv7                | Notebook    | [fa2ac7c179](https://linux-hardware.org/?probe=fa2ac7c179) | Nov 23, 2021 |
| Intel         | DB65AL AAG12530-309         | Desktop     | [44c8025eee](https://linux-hardware.org/?probe=44c8025eee) | Nov 23, 2021 |
| MSI           | B360M PRO-VD                | Desktop     | [e1f68c6698](https://linux-hardware.org/?probe=e1f68c6698) | Nov 22, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [baade6ba54](https://linux-hardware.org/?probe=baade6ba54) | Nov 22, 2021 |
| Gigabyte      | H77M-D3H                    | Desktop     | [2819a870a8](https://linux-hardware.org/?probe=2819a870a8) | Nov 22, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [b7718027af](https://linux-hardware.org/?probe=b7718027af) | Nov 22, 2021 |
| HP            | 15                          | Notebook    | [1753404669](https://linux-hardware.org/?probe=1753404669) | Nov 22, 2021 |
| HP            | Notebook                    | Notebook    | [9e9ce14e95](https://linux-hardware.org/?probe=9e9ce14e95) | Nov 22, 2021 |
| ASUSTek       | X751SA                      | Notebook    | [d19fd8c59f](https://linux-hardware.org/?probe=d19fd8c59f) | Nov 22, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [30bfdcb5ff](https://linux-hardware.org/?probe=30bfdcb5ff) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | Notebook    | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| HP            | 0AA4h                       | Desktop     | [22c6e4fffd](https://linux-hardware.org/?probe=22c6e4fffd) | Nov 22, 2021 |
| ASRock        | P67 Extreme6                | Desktop     | [54cd91039c](https://linux-hardware.org/?probe=54cd91039c) | Nov 22, 2021 |
| Fujitsu Si... | AMILO Pa 1510               | Notebook    | [9f731acb7e](https://linux-hardware.org/?probe=9f731acb7e) | Nov 22, 2021 |
| HP            | 15                          | Notebook    | [bca58eb5e0](https://linux-hardware.org/?probe=bca58eb5e0) | Nov 22, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [c796aedb22](https://linux-hardware.org/?probe=c796aedb22) | Nov 22, 2021 |
| Apple         | MacBookPro5,3               | Notebook    | [5a4e91eace](https://linux-hardware.org/?probe=5a4e91eace) | Nov 22, 2021 |
| ASUSTek       | U56E                        | Notebook    | [2b347f1923](https://linux-hardware.org/?probe=2b347f1923) | Nov 22, 2021 |
| Lenovo        | G560 0679                   | Notebook    | [15348ebbf9](https://linux-hardware.org/?probe=15348ebbf9) | Nov 22, 2021 |
| HP            | Pavilion 15                 | Notebook    | [0f1442bb2c](https://linux-hardware.org/?probe=0f1442bb2c) | Nov 22, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [fa922e6e20](https://linux-hardware.org/?probe=fa922e6e20) | Nov 22, 2021 |
| ASRock        | 775i945GZ                   | Desktop     | [8d3cfee95d](https://linux-hardware.org/?probe=8d3cfee95d) | Nov 22, 2021 |
| ASRock        | ALiveNF6G-DVI               | Desktop     | [23a839f917](https://linux-hardware.org/?probe=23a839f917) | Nov 21, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [ae91e01910](https://linux-hardware.org/?probe=ae91e01910) | Nov 21, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [47688cd36a](https://linux-hardware.org/?probe=47688cd36a) | Nov 21, 2021 |
| Toshiba       | Satellite U300              | Notebook    | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7c745f9e5a](https://linux-hardware.org/?probe=7c745f9e5a) | Nov 21, 2021 |
| HP            | ENVY Notebook               | Notebook    | [09767edae3](https://linux-hardware.org/?probe=09767edae3) | Nov 21, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [00a8a0ab87](https://linux-hardware.org/?probe=00a8a0ab87) | Nov 21, 2021 |
| Dell          | Latitude E6440              | Notebook    | [babff23db6](https://linux-hardware.org/?probe=babff23db6) | Nov 21, 2021 |
| Dell          | G7 7700                     | Notebook    | [730daa1080](https://linux-hardware.org/?probe=730daa1080) | Nov 21, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [2355c29da1](https://linux-hardware.org/?probe=2355c29da1) | Nov 21, 2021 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [16e0d2d71a](https://linux-hardware.org/?probe=16e0d2d71a) | Nov 21, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | Notebook    | [c99c5700f6](https://linux-hardware.org/?probe=c99c5700f6) | Nov 20, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [ca1ccc6e65](https://linux-hardware.org/?probe=ca1ccc6e65) | Nov 20, 2021 |
| ASUSTek       | K53U                        | Notebook    | [12136b1cbd](https://linux-hardware.org/?probe=12136b1cbd) | Nov 20, 2021 |
| Dell          | 0KWVT8 A00                  | Desktop     | [a6f003d198](https://linux-hardware.org/?probe=a6f003d198) | Nov 20, 2021 |
| HP            | Pavilion 15                 | Notebook    | [687ecf1c58](https://linux-hardware.org/?probe=687ecf1c58) | Nov 20, 2021 |
| Sony          | SVE1713D1EW                 | Notebook    | [20d3ee7401](https://linux-hardware.org/?probe=20d3ee7401) | Nov 20, 2021 |
| ASUSTek       | K53U                        | Notebook    | [5a5b8c420f](https://linux-hardware.org/?probe=5a5b8c420f) | Nov 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [89fdff42c1](https://linux-hardware.org/?probe=89fdff42c1) | Nov 20, 2021 |
| Intel         | S5520HC E26045-457          | Server      | [a30dcb5033](https://linux-hardware.org/?probe=a30dcb5033) | Nov 20, 2021 |
| LattePanda    | Alpha                       | Desktop     | [24c2fc6f7b](https://linux-hardware.org/?probe=24c2fc6f7b) | Nov 20, 2021 |
| Dell          | Precision M6700             | Notebook    | [a8bf3915fb](https://linux-hardware.org/?probe=a8bf3915fb) | Nov 20, 2021 |
| LattePanda    | Alpha                       | Desktop     | [4aa879f7ac](https://linux-hardware.org/?probe=4aa879f7ac) | Nov 20, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [7ddd35d3e8](https://linux-hardware.org/?probe=7ddd35d3e8) | Nov 20, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [4a77a751d9](https://linux-hardware.org/?probe=4a77a751d9) | Nov 20, 2021 |
| Toshiba       | Satellite C50D-B            | Notebook    | [6c92d7fef6](https://linux-hardware.org/?probe=6c92d7fef6) | Nov 19, 2021 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8a53d67102](https://linux-hardware.org/?probe=8a53d67102) | Nov 19, 2021 |
| Dell          | Latitude E5550              | Notebook    | [2f52aa274c](https://linux-hardware.org/?probe=2f52aa274c) | Nov 19, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [ac8f38525e](https://linux-hardware.org/?probe=ac8f38525e) | Nov 19, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [96d8266022](https://linux-hardware.org/?probe=96d8266022) | Nov 19, 2021 |
| Sony          | SVE1713D1EW                 | Notebook    | [cf21ed12bc](https://linux-hardware.org/?probe=cf21ed12bc) | Nov 18, 2021 |
| Intel         | S5520HC E26045-457          | Server      | [94107c0065](https://linux-hardware.org/?probe=94107c0065) | Nov 18, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6807e3fa8c](https://linux-hardware.org/?probe=6807e3fa8c) | Nov 18, 2021 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [b69858171e](https://linux-hardware.org/?probe=b69858171e) | Nov 18, 2021 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [3aa16a7b49](https://linux-hardware.org/?probe=3aa16a7b49) | Nov 18, 2021 |
| Dell          | 0KWVT8 A00                  | Desktop     | [93b90c3da4](https://linux-hardware.org/?probe=93b90c3da4) | Nov 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S1GW1Q    | Notebook    | [3b8a61e460](https://linux-hardware.org/?probe=3b8a61e460) | Nov 18, 2021 |
| Google        | Lars                        | Notebook    | [c346746b7e](https://linux-hardware.org/?probe=c346746b7e) | Nov 18, 2021 |
| Dell          | Latitude 5590               | Notebook    | [8bef1790bd](https://linux-hardware.org/?probe=8bef1790bd) | Nov 18, 2021 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [e3e16a0c1f](https://linux-hardware.org/?probe=e3e16a0c1f) | Nov 17, 2021 |
| Acer          | TravelMate 6292             | Notebook    | [2cec3b7547](https://linux-hardware.org/?probe=2cec3b7547) | Nov 17, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [8bc6042d3f](https://linux-hardware.org/?probe=8bc6042d3f) | Nov 17, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [b3319a217d](https://linux-hardware.org/?probe=b3319a217d) | Nov 17, 2021 |
| HP            | ENVY m7 Notebook            | Notebook    | [4b101cc132](https://linux-hardware.org/?probe=4b101cc132) | Nov 17, 2021 |
| HP            | 8446                        | All in one  | [2e8e2bd9b3](https://linux-hardware.org/?probe=2e8e2bd9b3) | Nov 17, 2021 |
| HP            | Stream Notebook PC 14       | Notebook    | [31499aa79d](https://linux-hardware.org/?probe=31499aa79d) | Nov 17, 2021 |
| ASRock        | X370M-HDV                   | Desktop     | [a991fee412](https://linux-hardware.org/?probe=a991fee412) | Nov 17, 2021 |
| HP            | Stream Notebook PC 14       | Notebook    | [8c30001e99](https://linux-hardware.org/?probe=8c30001e99) | Nov 17, 2021 |
| Dell          | Precision M6700             | Notebook    | [fb4051d1de](https://linux-hardware.org/?probe=fb4051d1de) | Nov 17, 2021 |
| Dell          | 0GXM1W A01                  | Desktop     | [7e9f638277](https://linux-hardware.org/?probe=7e9f638277) | Nov 17, 2021 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [0cae2ebf49](https://linux-hardware.org/?probe=0cae2ebf49) | Nov 16, 2021 |
| Lenovo        | ThinkPad T430 23445PU       | Notebook    | [e5fe64db56](https://linux-hardware.org/?probe=e5fe64db56) | Nov 16, 2021 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [bb50b7d97c](https://linux-hardware.org/?probe=bb50b7d97c) | Nov 16, 2021 |
| Toshiba       | Satellite C655D             | Notebook    | [cd8abc5170](https://linux-hardware.org/?probe=cd8abc5170) | Nov 16, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | Notebook    | [bfef77542f](https://linux-hardware.org/?probe=bfef77542f) | Nov 15, 2021 |
| MSI           | 2A9C                        | Desktop     | [80ef0caf18](https://linux-hardware.org/?probe=80ef0caf18) | Nov 15, 2021 |
| MSI           | 2A9C                        | Desktop     | [44e1dcea05](https://linux-hardware.org/?probe=44e1dcea05) | Nov 15, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [469541e3f1](https://linux-hardware.org/?probe=469541e3f1) | Nov 14, 2021 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [e90a1881c7](https://linux-hardware.org/?probe=e90a1881c7) | Nov 14, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [a92c32b60a](https://linux-hardware.org/?probe=a92c32b60a) | Nov 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [542b1538bf](https://linux-hardware.org/?probe=542b1538bf) | Nov 14, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | Notebook    | [76b69deb69](https://linux-hardware.org/?probe=76b69deb69) | Nov 14, 2021 |
| ASUSTek       | Vivobook_ASUSLaptop M350... | Notebook    | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| HP            | 8653 A                      | Desktop     | [88b53507c9](https://linux-hardware.org/?probe=88b53507c9) | Nov 13, 2021 |
| HP            | 3048h                       | Desktop     | [200317605d](https://linux-hardware.org/?probe=200317605d) | Nov 13, 2021 |
| Dell          | 0GXM1W A02                  | Desktop     | [d446993ec9](https://linux-hardware.org/?probe=d446993ec9) | Nov 13, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2070d323c9](https://linux-hardware.org/?probe=2070d323c9) | Nov 13, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [8977322809](https://linux-hardware.org/?probe=8977322809) | Nov 13, 2021 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [0c64127bf0](https://linux-hardware.org/?probe=0c64127bf0) | Nov 13, 2021 |
| HP            | Notebook                    | Notebook    | [226dc7dc39](https://linux-hardware.org/?probe=226dc7dc39) | Nov 12, 2021 |
| HP            | Notebook                    | Notebook    | [c03f407f50](https://linux-hardware.org/?probe=c03f407f50) | Nov 12, 2021 |
| HP            | Notebook                    | Notebook    | [a2bae8d4b8](https://linux-hardware.org/?probe=a2bae8d4b8) | Nov 12, 2021 |
| HP            | Notebook                    | Notebook    | [87dec3cf7c](https://linux-hardware.org/?probe=87dec3cf7c) | Nov 12, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [e3997c3bcb](https://linux-hardware.org/?probe=e3997c3bcb) | Nov 12, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [e8879e98df](https://linux-hardware.org/?probe=e8879e98df) | Nov 12, 2021 |
| Google        | Kindred                     | Notebook    | [0046ef8942](https://linux-hardware.org/?probe=0046ef8942) | Nov 12, 2021 |
| Google        | Kindred                     | Notebook    | [9d72c8972c](https://linux-hardware.org/?probe=9d72c8972c) | Nov 12, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| HP            | 1790                        | Desktop     | [e86cdf904a](https://linux-hardware.org/?probe=e86cdf904a) | Nov 12, 2021 |
| Dell          | Precision M6700             | Notebook    | [9bf18c23c6](https://linux-hardware.org/?probe=9bf18c23c6) | Nov 12, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [d342b54224](https://linux-hardware.org/?probe=d342b54224) | Nov 12, 2021 |
| HP            | 339A                        | Desktop     | [6dc037bf1f](https://linux-hardware.org/?probe=6dc037bf1f) | Nov 11, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [d0eae9ef10](https://linux-hardware.org/?probe=d0eae9ef10) | Nov 11, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7a2464824d](https://linux-hardware.org/?probe=7a2464824d) | Nov 11, 2021 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [32988fae95](https://linux-hardware.org/?probe=32988fae95) | Nov 11, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [c8e4265515](https://linux-hardware.org/?probe=c8e4265515) | Nov 11, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [eece1d5528](https://linux-hardware.org/?probe=eece1d5528) | Nov 11, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [c948868090](https://linux-hardware.org/?probe=c948868090) | Nov 11, 2021 |
| Dell          | Inspiron 1750               | Notebook    | [6ffff20ec8](https://linux-hardware.org/?probe=6ffff20ec8) | Nov 11, 2021 |
| Sony          | SVF14211CLB                 | Notebook    | [7c0dacdd54](https://linux-hardware.org/?probe=7c0dacdd54) | Nov 10, 2021 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [1841ab2aff](https://linux-hardware.org/?probe=1841ab2aff) | Nov 10, 2021 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3b1f90f3ab](https://linux-hardware.org/?probe=3b1f90f3ab) | Nov 10, 2021 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3858faa240](https://linux-hardware.org/?probe=3858faa240) | Nov 10, 2021 |
| Sony          | SVF14211CLB                 | Notebook    | [fdfd650fcc](https://linux-hardware.org/?probe=fdfd650fcc) | Nov 10, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [94da614270](https://linux-hardware.org/?probe=94da614270) | Nov 10, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4de5ef77a4](https://linux-hardware.org/?probe=4de5ef77a4) | Nov 10, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | Notebook    | [72dd15e9c5](https://linux-hardware.org/?probe=72dd15e9c5) | Nov 10, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [0e688f660f](https://linux-hardware.org/?probe=0e688f660f) | Nov 10, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [0d017f9835](https://linux-hardware.org/?probe=0d017f9835) | Nov 10, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [476167fea8](https://linux-hardware.org/?probe=476167fea8) | Nov 10, 2021 |
| ASUSTek       | U46E                        | Notebook    | [d52a43c7fd](https://linux-hardware.org/?probe=d52a43c7fd) | Nov 10, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [20a705fd56](https://linux-hardware.org/?probe=20a705fd56) | Nov 10, 2021 |
| HP            | 8653 A                      | Desktop     | [f84c67582a](https://linux-hardware.org/?probe=f84c67582a) | Nov 09, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [e7579f2fcf](https://linux-hardware.org/?probe=e7579f2fcf) | Nov 09, 2021 |
| HP            | 1790                        | Desktop     | [6030cabe49](https://linux-hardware.org/?probe=6030cabe49) | Nov 09, 2021 |
| Dell          | Latitude 3440               | Notebook    | [eb76b9d1cf](https://linux-hardware.org/?probe=eb76b9d1cf) | Nov 09, 2021 |
| HP            | 1825                        | Desktop     | [7cf6c3590a](https://linux-hardware.org/?probe=7cf6c3590a) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [d4c15ae33a](https://linux-hardware.org/?probe=d4c15ae33a) | Nov 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [605479abf7](https://linux-hardware.org/?probe=605479abf7) | Nov 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [b7a410c2e6](https://linux-hardware.org/?probe=b7a410c2e6) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [886c08185e](https://linux-hardware.org/?probe=886c08185e) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e141b2d36a](https://linux-hardware.org/?probe=e141b2d36a) | Nov 08, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [d85e7a0ad3](https://linux-hardware.org/?probe=d85e7a0ad3) | Nov 07, 2021 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [62ae26dca0](https://linux-hardware.org/?probe=62ae26dca0) | Nov 07, 2021 |
| Dell          | Latitude E5420              | Notebook    | [b53c6bd6d2](https://linux-hardware.org/?probe=b53c6bd6d2) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [520a472266](https://linux-hardware.org/?probe=520a472266) | Nov 07, 2021 |
| HP            | Compaq 8510p                | Notebook    | [ddecc261a1](https://linux-hardware.org/?probe=ddecc261a1) | Nov 07, 2021 |
| HP            | Compaq 8510p                | Notebook    | [c2434c1c08](https://linux-hardware.org/?probe=c2434c1c08) | Nov 07, 2021 |
| Dell          | 0HY9JP A00                  | Desktop     | [05c38bf92c](https://linux-hardware.org/?probe=05c38bf92c) | Nov 07, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [a0d13572a5](https://linux-hardware.org/?probe=a0d13572a5) | Nov 06, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [384fb31833](https://linux-hardware.org/?probe=384fb31833) | Nov 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f57575ffaf](https://linux-hardware.org/?probe=f57575ffaf) | Nov 06, 2021 |
| Dell          | 0VNP2H A02                  | Desktop     | [5402226d98](https://linux-hardware.org/?probe=5402226d98) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [746f64d20b](https://linux-hardware.org/?probe=746f64d20b) | Nov 06, 2021 |
| Intel         | S5520HC E26045-457          | Server      | [b8feff0b22](https://linux-hardware.org/?probe=b8feff0b22) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [245941966f](https://linux-hardware.org/?probe=245941966f) | Nov 06, 2021 |
| Sony          | SVE1713D1EW                 | Notebook    | [64fd6b328f](https://linux-hardware.org/?probe=64fd6b328f) | Nov 06, 2021 |
| Sony          | SVE1713D1EW                 | Notebook    | [45609f28be](https://linux-hardware.org/?probe=45609f28be) | Nov 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [e6e813115f](https://linux-hardware.org/?probe=e6e813115f) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | Notebook    | [5d577f71a4](https://linux-hardware.org/?probe=5d577f71a4) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | Notebook    | [c37780e9ad](https://linux-hardware.org/?probe=c37780e9ad) | Nov 06, 2021 |
| HP            | 0A98h                       | Desktop     | [110c37e799](https://linux-hardware.org/?probe=110c37e799) | Nov 06, 2021 |
| ASUSTek       | K53TA                       | Notebook    | [e924b214bc](https://linux-hardware.org/?probe=e924b214bc) | Nov 06, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7b21a0bc71](https://linux-hardware.org/?probe=7b21a0bc71) | Nov 06, 2021 |
| Acer          | Aspire ES1-521              | Notebook    | [5ef4af5924](https://linux-hardware.org/?probe=5ef4af5924) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [73b5ea9e0b](https://linux-hardware.org/?probe=73b5ea9e0b) | Nov 06, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [82a09e132d](https://linux-hardware.org/?probe=82a09e132d) | Nov 05, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [a96a96d455](https://linux-hardware.org/?probe=a96a96d455) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| ASUSTek       | K45A                        | Notebook    | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | Notebook    | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Gigabyte      | F2A78M-D3H                  | Desktop     | [43e09b8e80](https://linux-hardware.org/?probe=43e09b8e80) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | Desktop     | [1383828428](https://linux-hardware.org/?probe=1383828428) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | Desktop     | [f5ee7a26d5](https://linux-hardware.org/?probe=f5ee7a26d5) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [3e4d5dd09d](https://linux-hardware.org/?probe=3e4d5dd09d) | Nov 05, 2021 |
| Sony          | VPCEG23EL                   | Notebook    | [cc967c03fb](https://linux-hardware.org/?probe=cc967c03fb) | Nov 05, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [b506625dc2](https://linux-hardware.org/?probe=b506625dc2) | Nov 05, 2021 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [7f3894059d](https://linux-hardware.org/?probe=7f3894059d) | Nov 04, 2021 |
| HP            | 18E4                        | Desktop     | [3069846b25](https://linux-hardware.org/?probe=3069846b25) | Nov 04, 2021 |
| MSI           | G41M-P23                    | Desktop     | [82e51e3f78](https://linux-hardware.org/?probe=82e51e3f78) | Nov 04, 2021 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [00fe882e5d](https://linux-hardware.org/?probe=00fe882e5d) | Nov 04, 2021 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [4bbc26f44b](https://linux-hardware.org/?probe=4bbc26f44b) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [d7a405763d](https://linux-hardware.org/?probe=d7a405763d) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | X751NV                      | Notebook    | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| Dell          | Precision M6700             | Notebook    | [1865ed7cca](https://linux-hardware.org/?probe=1865ed7cca) | Nov 03, 2021 |
| Dell          | Latitude 5490               | Notebook    | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | Notebook    | [9e7a883a59](https://linux-hardware.org/?probe=9e7a883a59) | Nov 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [2d26d5b578](https://linux-hardware.org/?probe=2d26d5b578) | Nov 02, 2021 |
| Samsung       | 950QDB                      | Convertible | [515607bf99](https://linux-hardware.org/?probe=515607bf99) | Nov 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| HP            | Notebook                    | Notebook    | [ee3bc3deef](https://linux-hardware.org/?probe=ee3bc3deef) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [3acc230d6a](https://linux-hardware.org/?probe=3acc230d6a) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c88adaac6e](https://linux-hardware.org/?probe=c88adaac6e) | Nov 02, 2021 |
| ASUSTek       | M11AD                       | Desktop     | [0cb5032c53](https://linux-hardware.org/?probe=0cb5032c53) | Nov 02, 2021 |
| Lenovo        | ThinkPad T430 2349ED5       | Notebook    | [0697993e7c](https://linux-hardware.org/?probe=0697993e7c) | Nov 02, 2021 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [ef25dfbaa3](https://linux-hardware.org/?probe=ef25dfbaa3) | Nov 02, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [0f9c8eb860](https://linux-hardware.org/?probe=0f9c8eb860) | Nov 02, 2021 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [7e5a2d91f8](https://linux-hardware.org/?probe=7e5a2d91f8) | Nov 02, 2021 |
| HP            | ProBook 440 G4              | Notebook    | [695b9a4e0c](https://linux-hardware.org/?probe=695b9a4e0c) | Nov 01, 2021 |
| HP            | ProBook 440 G4              | Notebook    | [4bba4734e8](https://linux-hardware.org/?probe=4bba4734e8) | Nov 01, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [9ad082f18e](https://linux-hardware.org/?probe=9ad082f18e) | Nov 01, 2021 |
| Gigabyte      | GA-E6010N                   | Desktop     | [3c81474040](https://linux-hardware.org/?probe=3c81474040) | Nov 01, 2021 |
| Gigabyte      | GA-E6010N                   | Desktop     | [2a2aaffd43](https://linux-hardware.org/?probe=2a2aaffd43) | Nov 01, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [600b7b9957](https://linux-hardware.org/?probe=600b7b9957) | Nov 01, 2021 |
| Acer          | Spin SP513-55N              | Convertible | [b9b87d1c64](https://linux-hardware.org/?probe=b9b87d1c64) | Nov 01, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [56b475a93d](https://linux-hardware.org/?probe=56b475a93d) | Nov 01, 2021 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [42cd4d28bd](https://linux-hardware.org/?probe=42cd4d28bd) | Nov 01, 2021 |
| Toshiba       | Satellite Pro T110          | Notebook    | [3ae7a19459](https://linux-hardware.org/?probe=3ae7a19459) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | Notebook    | [e3fc4e0622](https://linux-hardware.org/?probe=e3fc4e0622) | Oct 31, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [83d642714b](https://linux-hardware.org/?probe=83d642714b) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [eabb3946ad](https://linux-hardware.org/?probe=eabb3946ad) | Oct 31, 2021 |
| eMachines     | EL1850G                     | Desktop     | [01dbf1b5ec](https://linux-hardware.org/?probe=01dbf1b5ec) | Oct 31, 2021 |
| MSI           | P55-CD53                    | Desktop     | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | Notebook    | [3861fce83e](https://linux-hardware.org/?probe=3861fce83e) | Oct 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [75cc8a67e9](https://linux-hardware.org/?probe=75cc8a67e9) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [2388e68622](https://linux-hardware.org/?probe=2388e68622) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | Desktop     | [111e98ddef](https://linux-hardware.org/?probe=111e98ddef) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | Desktop     | [6cee757cf0](https://linux-hardware.org/?probe=6cee757cf0) | Oct 31, 2021 |
| Dell          | Inspiron 7720               | Notebook    | [9f298535a5](https://linux-hardware.org/?probe=9f298535a5) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | Desktop     | [96c9053284](https://linux-hardware.org/?probe=96c9053284) | Oct 31, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d998d59215](https://linux-hardware.org/?probe=d998d59215) | Oct 31, 2021 |
| Dell          | 06NWYK A01                  | Desktop     | [497c824fd5](https://linux-hardware.org/?probe=497c824fd5) | Oct 31, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [0981774043](https://linux-hardware.org/?probe=0981774043) | Oct 30, 2021 |
| ASRock        | B85M-HDS                    | Desktop     | [69dd0cf598](https://linux-hardware.org/?probe=69dd0cf598) | Oct 30, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [cb9c15cf6f](https://linux-hardware.org/?probe=cb9c15cf6f) | Oct 30, 2021 |
| Dell          | Latitude E6500              | Notebook    | [e475348b1e](https://linux-hardware.org/?probe=e475348b1e) | Oct 30, 2021 |
| MECER         | Z140C+Home                  | Notebook    | [2fbf6f153b](https://linux-hardware.org/?probe=2fbf6f153b) | Oct 30, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [85a55f5c3c](https://linux-hardware.org/?probe=85a55f5c3c) | Oct 30, 2021 |
| Dell          | 06NWYK A01                  | Desktop     | [1d0625eb89](https://linux-hardware.org/?probe=1d0625eb89) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [16ebdc4388](https://linux-hardware.org/?probe=16ebdc4388) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6260be6de5](https://linux-hardware.org/?probe=6260be6de5) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [867e533368](https://linux-hardware.org/?probe=867e533368) | Oct 30, 2021 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [80adff7646](https://linux-hardware.org/?probe=80adff7646) | Oct 30, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [af0a995721](https://linux-hardware.org/?probe=af0a995721) | Oct 30, 2021 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [1a267b14d3](https://linux-hardware.org/?probe=1a267b14d3) | Oct 29, 2021 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [5b4cea000b](https://linux-hardware.org/?probe=5b4cea000b) | Oct 29, 2021 |
| Intel         | S5520HC E26045-457          | Server      | [451f363726](https://linux-hardware.org/?probe=451f363726) | Oct 29, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [b67ec8af25](https://linux-hardware.org/?probe=b67ec8af25) | Oct 29, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [88286c36e9](https://linux-hardware.org/?probe=88286c36e9) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | Desktop     | [4e19df8e3c](https://linux-hardware.org/?probe=4e19df8e3c) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [f5f4e2457b](https://linux-hardware.org/?probe=f5f4e2457b) | Oct 29, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [ef7d0f49e1](https://linux-hardware.org/?probe=ef7d0f49e1) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | Desktop     | [c220480b4c](https://linux-hardware.org/?probe=c220480b4c) | Oct 29, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [c74557d180](https://linux-hardware.org/?probe=c74557d180) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [35b5fcb787](https://linux-hardware.org/?probe=35b5fcb787) | Oct 28, 2021 |
| ASUSTek       | N71Jv                       | Notebook    | [29e3747e17](https://linux-hardware.org/?probe=29e3747e17) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [a73fabcd4c](https://linux-hardware.org/?probe=a73fabcd4c) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [528cec41bc](https://linux-hardware.org/?probe=528cec41bc) | Oct 28, 2021 |
| Alienware     | 08PG26 A00                  | Desktop     | [bb2fd997ab](https://linux-hardware.org/?probe=bb2fd997ab) | Oct 28, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b676d9030a](https://linux-hardware.org/?probe=b676d9030a) | Oct 28, 2021 |
| Acer          | Spin SP513-55N              | Convertible | [8c3b4736cd](https://linux-hardware.org/?probe=8c3b4736cd) | Oct 27, 2021 |
| ASUSTek       | X750JB                      | Notebook    | [90fd9f38fc](https://linux-hardware.org/?probe=90fd9f38fc) | Oct 27, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [cc07ebf9b6](https://linux-hardware.org/?probe=cc07ebf9b6) | Oct 27, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [f527983cc9](https://linux-hardware.org/?probe=f527983cc9) | Oct 27, 2021 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [08819513f2](https://linux-hardware.org/?probe=08819513f2) | Oct 27, 2021 |
| Intel         | S5520HC E26045-457          | Server      | [f7e2ea06ad](https://linux-hardware.org/?probe=f7e2ea06ad) | Oct 27, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [4207c6eaac](https://linux-hardware.org/?probe=4207c6eaac) | Oct 27, 2021 |
| Lenovo        | Legion Y920-17IKB Laptop... | Notebook    | [830d4c9d9d](https://linux-hardware.org/?probe=830d4c9d9d) | Oct 26, 2021 |
| Acer          | Aspire 5737Z                | Notebook    | [9bbf3befab](https://linux-hardware.org/?probe=9bbf3befab) | Oct 26, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [dfb2070b53](https://linux-hardware.org/?probe=dfb2070b53) | Oct 26, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | Notebook    | [4104e265ea](https://linux-hardware.org/?probe=4104e265ea) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | Notebook    | [3da20846f5](https://linux-hardware.org/?probe=3da20846f5) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | Notebook    | [2d19155e7f](https://linux-hardware.org/?probe=2d19155e7f) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [ed4e9d1a03](https://linux-hardware.org/?probe=ed4e9d1a03) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [f5b1e904b7](https://linux-hardware.org/?probe=f5b1e904b7) | Oct 26, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [87b3274937](https://linux-hardware.org/?probe=87b3274937) | Oct 26, 2021 |
| HP            | Stream Notebook PC 11       | Notebook    | [c240a088a9](https://linux-hardware.org/?probe=c240a088a9) | Oct 26, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [23d7c3ed4a](https://linux-hardware.org/?probe=23d7c3ed4a) | Oct 26, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [17f5a136fa](https://linux-hardware.org/?probe=17f5a136fa) | Oct 26, 2021 |
| Alienware     | 08PG26 A00                  | Desktop     | [7d6b559bf8](https://linux-hardware.org/?probe=7d6b559bf8) | Oct 26, 2021 |
| Intel         | S5520HC E26045-457          | Server      | [fdb4d4b838](https://linux-hardware.org/?probe=fdb4d4b838) | Oct 25, 2021 |
| Intel         | S5520HC E26045-457          | Server      | [cd7c995e3f](https://linux-hardware.org/?probe=cd7c995e3f) | Oct 25, 2021 |
| HP            | ENVY m7 Notebook            | Notebook    | [235fa5cacd](https://linux-hardware.org/?probe=235fa5cacd) | Oct 25, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [a1cf5282ba](https://linux-hardware.org/?probe=a1cf5282ba) | Oct 25, 2021 |
| ASRock        | H110M-HDS R3.0              | Desktop     | [718ad346b7](https://linux-hardware.org/?probe=718ad346b7) | Oct 25, 2021 |
| Dell          | Latitude E6430              | Notebook    | [fa4d12994d](https://linux-hardware.org/?probe=fa4d12994d) | Oct 25, 2021 |
| MSI           | 2AE0                        | Desktop     | [64a3b3ae41](https://linux-hardware.org/?probe=64a3b3ae41) | Oct 24, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [cc46a59d6c](https://linux-hardware.org/?probe=cc46a59d6c) | Oct 24, 2021 |
| Schenker      | VIA 15 Pro                  | Notebook    | [7242436545](https://linux-hardware.org/?probe=7242436545) | Oct 24, 2021 |
| MSI           | P55-CD53                    | Desktop     | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| Toshiba       | Satellite C70-B             | Notebook    | [a17b7c3888](https://linux-hardware.org/?probe=a17b7c3888) | Oct 24, 2021 |
| Thomson       | N17C512                     | Notebook    | [20abb09d3a](https://linux-hardware.org/?probe=20abb09d3a) | Oct 24, 2021 |
| Notebook      | X170SM                      | Notebook    | [2054d0dee6](https://linux-hardware.org/?probe=2054d0dee6) | Oct 24, 2021 |
| Notebook      | X170SM                      | Notebook    | [f704af17a3](https://linux-hardware.org/?probe=f704af17a3) | Oct 24, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [693d2a5966](https://linux-hardware.org/?probe=693d2a5966) | Oct 24, 2021 |
| Dell          | Latitude D630               | Notebook    | [1cfebe8169](https://linux-hardware.org/?probe=1cfebe8169) | Oct 23, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [fca2aa4310](https://linux-hardware.org/?probe=fca2aa4310) | Oct 23, 2021 |
| Dell          | Latitude E6410              | Notebook    | [f4cdc942dc](https://linux-hardware.org/?probe=f4cdc942dc) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db85bd77fc](https://linux-hardware.org/?probe=db85bd77fc) | Oct 23, 2021 |
| HP            | ProBook 6550b               | Notebook    | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | Notebook    | [c6582bba7d](https://linux-hardware.org/?probe=c6582bba7d) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | Notebook    | [248ab157b8](https://linux-hardware.org/?probe=248ab157b8) | Oct 23, 2021 |
| Dell          | 0VHXCD A00                  | Desktop     | [7c99a6ed29](https://linux-hardware.org/?probe=7c99a6ed29) | Oct 22, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [915961c057](https://linux-hardware.org/?probe=915961c057) | Oct 22, 2021 |
| HP            | Notebook                    | Notebook    | [11013f1334](https://linux-hardware.org/?probe=11013f1334) | Oct 22, 2021 |
| Biostar       | A68N-5100                   | Desktop     | [bc5b7a2417](https://linux-hardware.org/?probe=bc5b7a2417) | Oct 22, 2021 |
| MSI           | Z68A-G43                    | Desktop     | [b781916d8e](https://linux-hardware.org/?probe=b781916d8e) | Oct 22, 2021 |
| Google        | Kindred                     | Notebook    | [675265477a](https://linux-hardware.org/?probe=675265477a) | Oct 22, 2021 |
| HP            | 255 G4 Notebook PC          | Notebook    | [e7e49e8cc0](https://linux-hardware.org/?probe=e7e49e8cc0) | Oct 22, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [baee5192b6](https://linux-hardware.org/?probe=baee5192b6) | Oct 22, 2021 |
| Dell          | Latitude E7470              | Notebook    | [061c5e449c](https://linux-hardware.org/?probe=061c5e449c) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| MSI           | Modern 14 B10MW             | Notebook    | [ae43e74753](https://linux-hardware.org/?probe=ae43e74753) | Oct 21, 2021 |
| HP            | 1589                        | Desktop     | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | Notebook    | [8668abcc62](https://linux-hardware.org/?probe=8668abcc62) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | Notebook    | [18cf55aa72](https://linux-hardware.org/?probe=18cf55aa72) | Oct 21, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [985ff9ba03](https://linux-hardware.org/?probe=985ff9ba03) | Oct 21, 2021 |
| Unknown       | Phitronics G41-M3           | Desktop     | [a6ccedb5bd](https://linux-hardware.org/?probe=a6ccedb5bd) | Oct 20, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Unknown       | Phitronics G41-M3           | Desktop     | [fbe886aee7](https://linux-hardware.org/?probe=fbe886aee7) | Oct 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [8c412b3b5b](https://linux-hardware.org/?probe=8c412b3b5b) | Oct 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | Notebook    | [6d2d97674c](https://linux-hardware.org/?probe=6d2d97674c) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | Notebook    | [facdd98487](https://linux-hardware.org/?probe=facdd98487) | Oct 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [961f066acf](https://linux-hardware.org/?probe=961f066acf) | Oct 19, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [9fc60b0ba8](https://linux-hardware.org/?probe=9fc60b0ba8) | Oct 19, 2021 |
| Dell          | Latitude E7470              | Notebook    | [fdc6203a6e](https://linux-hardware.org/?probe=fdc6203a6e) | Oct 18, 2021 |
| Quanta        | XV1                         | All in one  | [c421f15879](https://linux-hardware.org/?probe=c421f15879) | Oct 18, 2021 |
| Dell          | Latitude E6420              | Notebook    | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6210b749a1](https://linux-hardware.org/?probe=6210b749a1) | Oct 18, 2021 |
| HP            | 2B38                        | Desktop     | [2cf327f158](https://linux-hardware.org/?probe=2cf327f158) | Oct 18, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [fa1ceccee5](https://linux-hardware.org/?probe=fa1ceccee5) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [dbf1e020b0](https://linux-hardware.org/?probe=dbf1e020b0) | Oct 18, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [2f5f509752](https://linux-hardware.org/?probe=2f5f509752) | Oct 18, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | Desktop     | [a7ea75f7c5](https://linux-hardware.org/?probe=a7ea75f7c5) | Oct 18, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [2ffe8489e1](https://linux-hardware.org/?probe=2ffe8489e1) | Oct 18, 2021 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [076883700d](https://linux-hardware.org/?probe=076883700d) | Oct 17, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [10f8e5f5cf](https://linux-hardware.org/?probe=10f8e5f5cf) | Oct 17, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [90a3d77b31](https://linux-hardware.org/?probe=90a3d77b31) | Oct 17, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [9f22e32d08](https://linux-hardware.org/?probe=9f22e32d08) | Oct 17, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [014464c088](https://linux-hardware.org/?probe=014464c088) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [15ce74dcd6](https://linux-hardware.org/?probe=15ce74dcd6) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [97c3495c65](https://linux-hardware.org/?probe=97c3495c65) | Oct 17, 2021 |
| Unknown       | CherryTrail                 | Notebook    | [01d095b201](https://linux-hardware.org/?probe=01d095b201) | Oct 17, 2021 |
| ASUSTek       | P6T                         | Desktop     | [69397b40d4](https://linux-hardware.org/?probe=69397b40d4) | Oct 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [058d7e8e3e](https://linux-hardware.org/?probe=058d7e8e3e) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ce2e0740c8](https://linux-hardware.org/?probe=ce2e0740c8) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a3dbbf3c03](https://linux-hardware.org/?probe=a3dbbf3c03) | Oct 17, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [76090a2652](https://linux-hardware.org/?probe=76090a2652) | Oct 16, 2021 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [ff6de8e062](https://linux-hardware.org/?probe=ff6de8e062) | Oct 16, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [d0d0d99be6](https://linux-hardware.org/?probe=d0d0d99be6) | Oct 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [5de4ff60b0](https://linux-hardware.org/?probe=5de4ff60b0) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [ef609865b5](https://linux-hardware.org/?probe=ef609865b5) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [4fc5c2f99f](https://linux-hardware.org/?probe=4fc5c2f99f) | Oct 16, 2021 |
| Dell          | Latitude E7440              | Notebook    | [cfe53904bc](https://linux-hardware.org/?probe=cfe53904bc) | Oct 16, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [e3806f5c09](https://linux-hardware.org/?probe=e3806f5c09) | Oct 16, 2021 |
| Unknown       | Unknown                     | Notebook    | [3233e1293c](https://linux-hardware.org/?probe=3233e1293c) | Oct 15, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [a89127ff6a](https://linux-hardware.org/?probe=a89127ff6a) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7de05cdbc3](https://linux-hardware.org/?probe=7de05cdbc3) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [66b0e77a10](https://linux-hardware.org/?probe=66b0e77a10) | Oct 15, 2021 |
| Acer          | Aspire E5-576G              | Notebook    | [6f17f5d2c0](https://linux-hardware.org/?probe=6f17f5d2c0) | Oct 15, 2021 |
| HP            | Pavilion dv7                | Notebook    | [2d35a2ee5d](https://linux-hardware.org/?probe=2d35a2ee5d) | Oct 15, 2021 |
| Dell          | 0VHXCD A00                  | Desktop     | [ccd75d2752](https://linux-hardware.org/?probe=ccd75d2752) | Oct 15, 2021 |
| HP            | ENVY m7 Notebook            | Notebook    | [f0af05f6f9](https://linux-hardware.org/?probe=f0af05f6f9) | Oct 15, 2021 |
| Unknown       | Unknown                     | Notebook    | [ddc6d80716](https://linux-hardware.org/?probe=ddc6d80716) | Oct 15, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [fdaa2dd77e](https://linux-hardware.org/?probe=fdaa2dd77e) | Oct 14, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [3f90ae6d67](https://linux-hardware.org/?probe=3f90ae6d67) | Oct 14, 2021 |
| Dell          | Latitude E6420              | Notebook    | [14b08ab14d](https://linux-hardware.org/?probe=14b08ab14d) | Oct 14, 2021 |
| ASUSTek       | GL702VI                     | Notebook    | [c342d6fdc1](https://linux-hardware.org/?probe=c342d6fdc1) | Oct 14, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [c0beced761](https://linux-hardware.org/?probe=c0beced761) | Oct 14, 2021 |
| HP            | 15                          | Notebook    | [5534f9e3fc](https://linux-hardware.org/?probe=5534f9e3fc) | Oct 14, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [2cd9b13bb1](https://linux-hardware.org/?probe=2cd9b13bb1) | Oct 14, 2021 |
| HP            | 15                          | Notebook    | [bfc196e22b](https://linux-hardware.org/?probe=bfc196e22b) | Oct 13, 2021 |
| ASUSTek       | X501A1                      | Notebook    | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [95f8cd653d](https://linux-hardware.org/?probe=95f8cd653d) | Oct 12, 2021 |
| HP            | Notebook                    | Notebook    | [58c6628ba2](https://linux-hardware.org/?probe=58c6628ba2) | Oct 12, 2021 |
| HP            | Notebook                    | Notebook    | [f3f5e6256d](https://linux-hardware.org/?probe=f3f5e6256d) | Oct 12, 2021 |
| ASUSTek       | M5A78L                      | Desktop     | [a027b0f5ba](https://linux-hardware.org/?probe=a027b0f5ba) | Oct 12, 2021 |
| HP            | 81C7 MVB 0C                 | Desktop     | [23d528f392](https://linux-hardware.org/?probe=23d528f392) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [a13d0383b6](https://linux-hardware.org/?probe=a13d0383b6) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [686377ccd0](https://linux-hardware.org/?probe=686377ccd0) | Oct 12, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [9bb8ba744e](https://linux-hardware.org/?probe=9bb8ba744e) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [01a3f25bec](https://linux-hardware.org/?probe=01a3f25bec) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [d8de6fc953](https://linux-hardware.org/?probe=d8de6fc953) | Oct 12, 2021 |
| Giani Limi... | ENY1158M                    | Notebook    | [1f9a85e980](https://linux-hardware.org/?probe=1f9a85e980) | Oct 11, 2021 |
| Giani Limi... | ENY1158M                    | Notebook    | [4516242881](https://linux-hardware.org/?probe=4516242881) | Oct 11, 2021 |
| ASUSTek       | M5A78L                      | Desktop     | [071d7e45a0](https://linux-hardware.org/?probe=071d7e45a0) | Oct 11, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [471414140c](https://linux-hardware.org/?probe=471414140c) | Oct 11, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [6265908eb4](https://linux-hardware.org/?probe=6265908eb4) | Oct 11, 2021 |
| Unknown       | Z3735F-T02 V1.2             | Notebook    | [6ef4e9edf6](https://linux-hardware.org/?probe=6ef4e9edf6) | Oct 11, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [f5147cd609](https://linux-hardware.org/?probe=f5147cd609) | Oct 10, 2021 |
| Biostar       | G41-M7                      | Desktop     | [94efede651](https://linux-hardware.org/?probe=94efede651) | Oct 10, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | Notebook    | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | Notebook    | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [af0bf465e5](https://linux-hardware.org/?probe=af0bf465e5) | Oct 09, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [1892bf50b9](https://linux-hardware.org/?probe=1892bf50b9) | Oct 09, 2021 |
| HP            | 81C7 MVB 0C                 | Desktop     | [5bfcd88031](https://linux-hardware.org/?probe=5bfcd88031) | Oct 09, 2021 |
| Biostar       | G41-M7                      | Desktop     | [4f1889a1de](https://linux-hardware.org/?probe=4f1889a1de) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [e1a73cbf10](https://linux-hardware.org/?probe=e1a73cbf10) | Oct 09, 2021 |
| Samsung       | 700Z3C/700Z5C               | Notebook    | [007ba2bac1](https://linux-hardware.org/?probe=007ba2bac1) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [63e608b4af](https://linux-hardware.org/?probe=63e608b4af) | Oct 09, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [237a82041b](https://linux-hardware.org/?probe=237a82041b) | Oct 09, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [e988105956](https://linux-hardware.org/?probe=e988105956) | Oct 09, 2021 |
| ASUSTek       | X555YA                      | Notebook    | [7bbcc6c5af](https://linux-hardware.org/?probe=7bbcc6c5af) | Oct 09, 2021 |
| HP            | Laptop 17z-cp000            | Notebook    | [db7c1566db](https://linux-hardware.org/?probe=db7c1566db) | Oct 09, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [f0a1062216](https://linux-hardware.org/?probe=f0a1062216) | Oct 09, 2021 |
| HP            | ENVY dv6                    | Notebook    | [21a3477c3d](https://linux-hardware.org/?probe=21a3477c3d) | Oct 08, 2021 |
| Dell          | 0VHXCD A00                  | Desktop     | [7a2b25ff42](https://linux-hardware.org/?probe=7a2b25ff42) | Oct 08, 2021 |
| Dell          | 04Y8V0 A01                  | Desktop     | [453beab8c3](https://linux-hardware.org/?probe=453beab8c3) | Oct 08, 2021 |
| MSI           | GE66 Raider 10UH            | Notebook    | [43c72c2ff3](https://linux-hardware.org/?probe=43c72c2ff3) | Oct 08, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [c9d3dce156](https://linux-hardware.org/?probe=c9d3dce156) | Oct 08, 2021 |
| HP            | Unknown                     | Notebook    | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| ASUSTek       | CM5570                      | Desktop     | [75b8bca0fa](https://linux-hardware.org/?probe=75b8bca0fa) | Oct 07, 2021 |
| Acer          | TravelMate P259-MG          | Notebook    | [c62543cf86](https://linux-hardware.org/?probe=c62543cf86) | Oct 07, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [b81ab61049](https://linux-hardware.org/?probe=b81ab61049) | Oct 07, 2021 |
| HP            | Pavilion dv7                | Notebook    | [e139664dbf](https://linux-hardware.org/?probe=e139664dbf) | Oct 07, 2021 |
| HP            | 8591                        | Desktop     | [22dca8a98c](https://linux-hardware.org/?probe=22dca8a98c) | Oct 07, 2021 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [2550a17ad0](https://linux-hardware.org/?probe=2550a17ad0) | Oct 07, 2021 |
| Dell          | 0VHXCD A00                  | Desktop     | [7f81996b23](https://linux-hardware.org/?probe=7f81996b23) | Oct 07, 2021 |
| Star Labs     | LabTop                      | Notebook    | [711f2b9e6d](https://linux-hardware.org/?probe=711f2b9e6d) | Oct 07, 2021 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [a392dd59eb](https://linux-hardware.org/?probe=a392dd59eb) | Oct 06, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [ae113c0df0](https://linux-hardware.org/?probe=ae113c0df0) | Oct 06, 2021 |
| Dell          | Latitude E5400              | Notebook    | [6878f58676](https://linux-hardware.org/?probe=6878f58676) | Oct 06, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [a87e581c64](https://linux-hardware.org/?probe=a87e581c64) | Oct 06, 2021 |
| Dell          | Latitude E5400              | Notebook    | [b69897eca3](https://linux-hardware.org/?probe=b69897eca3) | Oct 06, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [afe8fca994](https://linux-hardware.org/?probe=afe8fca994) | Oct 06, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [dc9074514c](https://linux-hardware.org/?probe=dc9074514c) | Oct 06, 2021 |
| ASUSTek       | X550LB                      | Notebook    | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6717c35dc9](https://linux-hardware.org/?probe=6717c35dc9) | Oct 05, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [ed77d40eeb](https://linux-hardware.org/?probe=ed77d40eeb) | Oct 05, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [f67c2f8d32](https://linux-hardware.org/?probe=f67c2f8d32) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| HP            | Notebook                    | Notebook    | [88b07c9f57](https://linux-hardware.org/?probe=88b07c9f57) | Oct 05, 2021 |
| HP            | Notebook                    | Notebook    | [28c9b584b1](https://linux-hardware.org/?probe=28c9b584b1) | Oct 05, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [9e18ebff31](https://linux-hardware.org/?probe=9e18ebff31) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | Notebook    | [ccc6db1c41](https://linux-hardware.org/?probe=ccc6db1c41) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | Notebook    | [55ec005acb](https://linux-hardware.org/?probe=55ec005acb) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [173104cfcf](https://linux-hardware.org/?probe=173104cfcf) | Oct 04, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Toshiba       | Satellite C70-B             | Notebook    | [2d4b467fdc](https://linux-hardware.org/?probe=2d4b467fdc) | Oct 04, 2021 |
| Dell          | Latitude E5570              | Notebook    | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [0890806446](https://linux-hardware.org/?probe=0890806446) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [6d94d45cf0](https://linux-hardware.org/?probe=6d94d45cf0) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [ab6b537db8](https://linux-hardware.org/?probe=ab6b537db8) | Oct 04, 2021 |
| HP            | Notebook                    | Notebook    | [c405133048](https://linux-hardware.org/?probe=c405133048) | Oct 03, 2021 |
| Dell          | Latitude 7390               | Notebook    | [50080eb85e](https://linux-hardware.org/?probe=50080eb85e) | Oct 03, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [163b47753d](https://linux-hardware.org/?probe=163b47753d) | Oct 03, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [a2ee189c63](https://linux-hardware.org/?probe=a2ee189c63) | Oct 03, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [224b713b5c](https://linux-hardware.org/?probe=224b713b5c) | Oct 03, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [a4f833babc](https://linux-hardware.org/?probe=a4f833babc) | Oct 03, 2021 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| HP            | Pavilion dv7                | Notebook    | [30875abc8f](https://linux-hardware.org/?probe=30875abc8f) | Oct 03, 2021 |
| Dell          | Inspiron 7773               | Notebook    | [2713f21dd7](https://linux-hardware.org/?probe=2713f21dd7) | Oct 03, 2021 |
| Dell          | Latitude E5400              | Notebook    | [ffc2d5a399](https://linux-hardware.org/?probe=ffc2d5a399) | Oct 03, 2021 |
| Toshiba       | Satellite L455D             | Notebook    | [9413906eaa](https://linux-hardware.org/?probe=9413906eaa) | Oct 03, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [e3247b14fa](https://linux-hardware.org/?probe=e3247b14fa) | Oct 02, 2021 |
| Dell          | Latitude E5400              | Notebook    | [529e29fb9d](https://linux-hardware.org/?probe=529e29fb9d) | Oct 02, 2021 |
| Toshiba       | Satellite Pro T110          | Notebook    | [3bd8210e7e](https://linux-hardware.org/?probe=3bd8210e7e) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [a02538183c](https://linux-hardware.org/?probe=a02538183c) | Oct 01, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [10d8a84245](https://linux-hardware.org/?probe=10d8a84245) | Oct 01, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [d68bf2f2b0](https://linux-hardware.org/?probe=d68bf2f2b0) | Oct 01, 2021 |
| Dell          | Latitude E6520              | Notebook    | [e1bf1df5ae](https://linux-hardware.org/?probe=e1bf1df5ae) | Oct 01, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [2a8da86d79](https://linux-hardware.org/?probe=2a8da86d79) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [b6eca9083a](https://linux-hardware.org/?probe=b6eca9083a) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [415f0d9244](https://linux-hardware.org/?probe=415f0d9244) | Oct 01, 2021 |
| Unknown       | Unknown                     | Notebook    | [f92fca6d48](https://linux-hardware.org/?probe=f92fca6d48) | Oct 01, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [a7a50b0dbf](https://linux-hardware.org/?probe=a7a50b0dbf) | Oct 01, 2021 |
| Dell          | 0HN7XN A00                  | Desktop     | [cc8a68bbd6](https://linux-hardware.org/?probe=cc8a68bbd6) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | Desktop     | [8137456421](https://linux-hardware.org/?probe=8137456421) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | Desktop     | [3411428e31](https://linux-hardware.org/?probe=3411428e31) | Sep 30, 2021 |
| Dell          | 0HN7XN A00                  | Desktop     | [5f56956871](https://linux-hardware.org/?probe=5f56956871) | Sep 30, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [33c6d2d214](https://linux-hardware.org/?probe=33c6d2d214) | Sep 30, 2021 |
| HP            | Pavilion dv7                | Notebook    | [590a48aff9](https://linux-hardware.org/?probe=590a48aff9) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [359171629f](https://linux-hardware.org/?probe=359171629f) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [4e125287e4](https://linux-hardware.org/?probe=4e125287e4) | Sep 30, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [d0c34db7d4](https://linux-hardware.org/?probe=d0c34db7d4) | Sep 29, 2021 |
| HP            | ENVY 15                     | Notebook    | [4b949c1a1b](https://linux-hardware.org/?probe=4b949c1a1b) | Sep 29, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [3688fae067](https://linux-hardware.org/?probe=3688fae067) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [3befe3f6e3](https://linux-hardware.org/?probe=3befe3f6e3) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [401d1460e9](https://linux-hardware.org/?probe=401d1460e9) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| Lenovo        | IdeaCentre K330             | Desktop     | [ed6e765fea](https://linux-hardware.org/?probe=ed6e765fea) | Sep 29, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [8f7adb6cd3](https://linux-hardware.org/?probe=8f7adb6cd3) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [9e3d0f86c2](https://linux-hardware.org/?probe=9e3d0f86c2) | Sep 28, 2021 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [1d15930339](https://linux-hardware.org/?probe=1d15930339) | Sep 28, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5b8eb94d7](https://linux-hardware.org/?probe=d5b8eb94d7) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [cc9cc9e925](https://linux-hardware.org/?probe=cc9cc9e925) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [6cf7de2b6b](https://linux-hardware.org/?probe=6cf7de2b6b) | Sep 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7e0b76f736](https://linux-hardware.org/?probe=7e0b76f736) | Sep 28, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [d36367eb22](https://linux-hardware.org/?probe=d36367eb22) | Sep 28, 2021 |
| Acer          | Aspire A315-56              | Notebook    | [3fc47b2c92](https://linux-hardware.org/?probe=3fc47b2c92) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [f322cce11b](https://linux-hardware.org/?probe=f322cce11b) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| Dell          | 0TNXNR A01                  | Desktop     | [781c19cc33](https://linux-hardware.org/?probe=781c19cc33) | Sep 27, 2021 |
| Dell          | Latitude E5570              | Notebook    | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | Notebook    | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | Notebook    | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [0625659706](https://linux-hardware.org/?probe=0625659706) | Sep 27, 2021 |
| Dell          | 0NYCKR A00                  | All in one  | [aefac2fb50](https://linux-hardware.org/?probe=aefac2fb50) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| Dell          | 0NYCKR A00                  | All in one  | [e0e687f0f9](https://linux-hardware.org/?probe=e0e687f0f9) | Sep 27, 2021 |
| MSI           | MS-B1061                    | All in one  | [1bc488324f](https://linux-hardware.org/?probe=1bc488324f) | Sep 27, 2021 |
| ASUSTek       | X405UA                      | Notebook    | [3a78f7edf5](https://linux-hardware.org/?probe=3a78f7edf5) | Sep 26, 2021 |
| Dell          | 0TP406                      | Desktop     | [39f9e67ae2](https://linux-hardware.org/?probe=39f9e67ae2) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| HP            | 18E7                        | Desktop     | [94f692683b](https://linux-hardware.org/?probe=94f692683b) | Sep 26, 2021 |
| Lenovo        | ThinkPad T520 4242W19       | Notebook    | [0bbb8d9004](https://linux-hardware.org/?probe=0bbb8d9004) | Sep 26, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [4bc5eb3bbc](https://linux-hardware.org/?probe=4bc5eb3bbc) | Sep 25, 2021 |
| eMachines     | EL1850G                     | Desktop     | [f5b47069bb](https://linux-hardware.org/?probe=f5b47069bb) | Sep 25, 2021 |
| HP            | 8245 001                    | All in one  | [8ea38831d5](https://linux-hardware.org/?probe=8ea38831d5) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [8bc152aa27](https://linux-hardware.org/?probe=8bc152aa27) | Sep 25, 2021 |
| Lenovo        | ThinkCentre M58 3231W2Y     | Desktop     | [a2da2733ac](https://linux-hardware.org/?probe=a2da2733ac) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [5cc1a01b2f](https://linux-hardware.org/?probe=5cc1a01b2f) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [2b341862f1](https://linux-hardware.org/?probe=2b341862f1) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [9267f59e81](https://linux-hardware.org/?probe=9267f59e81) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [5404d5874a](https://linux-hardware.org/?probe=5404d5874a) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Dell          | Latitude E6220              | Notebook    | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [9d3daebd14](https://linux-hardware.org/?probe=9d3daebd14) | Sep 25, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [65ebe53761](https://linux-hardware.org/?probe=65ebe53761) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [6b6f1c017d](https://linux-hardware.org/?probe=6b6f1c017d) | Sep 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [953ed13df8](https://linux-hardware.org/?probe=953ed13df8) | Sep 24, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [663af51c43](https://linux-hardware.org/?probe=663af51c43) | Sep 24, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [4d4844cfbe](https://linux-hardware.org/?probe=4d4844cfbe) | Sep 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [a65f8af3ac](https://linux-hardware.org/?probe=a65f8af3ac) | Sep 24, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [2d0d6ceff3](https://linux-hardware.org/?probe=2d0d6ceff3) | Sep 24, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | Desktop     | [dc87018670](https://linux-hardware.org/?probe=dc87018670) | Sep 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8617cbbc27](https://linux-hardware.org/?probe=8617cbbc27) | Sep 24, 2021 |
| ASRock        | 775VM800                    | Desktop     | [e07158e4ab](https://linux-hardware.org/?probe=e07158e4ab) | Sep 24, 2021 |
| KOGAN         | KAL11C250SB                 | Notebook    | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1af2027db5](https://linux-hardware.org/?probe=1af2027db5) | Sep 24, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5e66bde0c9](https://linux-hardware.org/?probe=5e66bde0c9) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | Notebook    | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| HP            | Presario V6000 (GM018UA#... | Notebook    | [944d6af89a](https://linux-hardware.org/?probe=944d6af89a) | Sep 23, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [fe99af6254](https://linux-hardware.org/?probe=fe99af6254) | Sep 23, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [4d2aa790e0](https://linux-hardware.org/?probe=4d2aa790e0) | Sep 23, 2021 |
| HP            | 18E7                        | Desktop     | [29fa39d7e9](https://linux-hardware.org/?probe=29fa39d7e9) | Sep 23, 2021 |
| ASRock        | 880GMH/U3S3                 | Desktop     | [ec55312287](https://linux-hardware.org/?probe=ec55312287) | Sep 23, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [cb23f25d7f](https://linux-hardware.org/?probe=cb23f25d7f) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [74410f0d0c](https://linux-hardware.org/?probe=74410f0d0c) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ad81766325](https://linux-hardware.org/?probe=ad81766325) | Sep 23, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [bc7d0dc232](https://linux-hardware.org/?probe=bc7d0dc232) | Sep 22, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | Desktop     | [529a9f4c74](https://linux-hardware.org/?probe=529a9f4c74) | Sep 22, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [bfa3ee0eda](https://linux-hardware.org/?probe=bfa3ee0eda) | Sep 22, 2021 |
| Cube          | SurfTab twin 11.6           | Convertible | [74fe90715f](https://linux-hardware.org/?probe=74fe90715f) | Sep 22, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [effa7b0365](https://linux-hardware.org/?probe=effa7b0365) | Sep 22, 2021 |
| HP            | Notebook                    | Notebook    | [91d439a6a4](https://linux-hardware.org/?probe=91d439a6a4) | Sep 22, 2021 |
| Dynabook      | PORTEGE A30-E               | Notebook    | [93fd738472](https://linux-hardware.org/?probe=93fd738472) | Sep 21, 2021 |
| Dynabook      | PORTEGE A30-E               | Notebook    | [0ec5acd020](https://linux-hardware.org/?probe=0ec5acd020) | Sep 21, 2021 |
| HP            | 213D A01                    | Desktop     | [8d4dd8359c](https://linux-hardware.org/?probe=8d4dd8359c) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a43f2dc4bf](https://linux-hardware.org/?probe=a43f2dc4bf) | Sep 21, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [3354edcb58](https://linux-hardware.org/?probe=3354edcb58) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [069c0cafd0](https://linux-hardware.org/?probe=069c0cafd0) | Sep 21, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [10baeecbf5](https://linux-hardware.org/?probe=10baeecbf5) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [c514cd3934](https://linux-hardware.org/?probe=c514cd3934) | Sep 21, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [fdb65b8597](https://linux-hardware.org/?probe=fdb65b8597) | Sep 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [699803b74c](https://linux-hardware.org/?probe=699803b74c) | Sep 21, 2021 |
| Dell          | 09CGW2 A13                  | Server      | [46d07193b2](https://linux-hardware.org/?probe=46d07193b2) | Sep 21, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3ef59689e6](https://linux-hardware.org/?probe=3ef59689e6) | Sep 21, 2021 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [70511c9675](https://linux-hardware.org/?probe=70511c9675) | Sep 21, 2021 |
| Lenovo        | G580                        | Notebook    | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [91055c07be](https://linux-hardware.org/?probe=91055c07be) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [ae16407ef3](https://linux-hardware.org/?probe=ae16407ef3) | Sep 20, 2021 |
| MSI           | H81M-E33                    | Desktop     | [5ef84c22e6](https://linux-hardware.org/?probe=5ef84c22e6) | Sep 20, 2021 |
| MSI           | H81M-E33                    | Desktop     | [db96085729](https://linux-hardware.org/?probe=db96085729) | Sep 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a0b7d0cf25](https://linux-hardware.org/?probe=a0b7d0cf25) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c05636068f](https://linux-hardware.org/?probe=c05636068f) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [1a012b3021](https://linux-hardware.org/?probe=1a012b3021) | Sep 20, 2021 |
| Dell          | 09CGW2 A13                  | Server      | [97926688ff](https://linux-hardware.org/?probe=97926688ff) | Sep 20, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [c294748851](https://linux-hardware.org/?probe=c294748851) | Sep 20, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [39f083f836](https://linux-hardware.org/?probe=39f083f836) | Sep 20, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [59eb49e544](https://linux-hardware.org/?probe=59eb49e544) | Sep 20, 2021 |
| Acer          | Aspire E1-532               | Notebook    | [b0407bdd1c](https://linux-hardware.org/?probe=b0407bdd1c) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [b9259e3604](https://linux-hardware.org/?probe=b9259e3604) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [9eb1254056](https://linux-hardware.org/?probe=9eb1254056) | Sep 19, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [c86625aa34](https://linux-hardware.org/?probe=c86625aa34) | Sep 19, 2021 |
| HP            | 2B28                        | Desktop     | [14681c925a](https://linux-hardware.org/?probe=14681c925a) | Sep 19, 2021 |
| TianBei       | TB-H7                       | Notebook    | [06300b96a7](https://linux-hardware.org/?probe=06300b96a7) | Sep 19, 2021 |
| Sapphire T... | PURE PLATINUM 970A-PLUS     | Desktop     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [6129e531d9](https://linux-hardware.org/?probe=6129e531d9) | Sep 19, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [37f34b16c5](https://linux-hardware.org/?probe=37f34b16c5) | Sep 19, 2021 |
| Acer          | Aspire 4352                 | Notebook    | [3a9aedb538](https://linux-hardware.org/?probe=3a9aedb538) | Sep 19, 2021 |
| ASUSTek       | U31F                        | Notebook    | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [183fc0dd5e](https://linux-hardware.org/?probe=183fc0dd5e) | Sep 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [bc3e2da7f3](https://linux-hardware.org/?probe=bc3e2da7f3) | Sep 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e8f361170f](https://linux-hardware.org/?probe=e8f361170f) | Sep 18, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [4dda7e9a7e](https://linux-hardware.org/?probe=4dda7e9a7e) | Sep 18, 2021 |
| ASUSTek       | U31F                        | Notebook    | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Dell          | System XPS L321X            | Notebook    | [2345076968](https://linux-hardware.org/?probe=2345076968) | Sep 18, 2021 |
| Dell          | Latitude E6430              | Notebook    | [2d96c4a645](https://linux-hardware.org/?probe=2d96c4a645) | Sep 17, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [30f36dc15d](https://linux-hardware.org/?probe=30f36dc15d) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [42d68963c6](https://linux-hardware.org/?probe=42d68963c6) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [50f90e7684](https://linux-hardware.org/?probe=50f90e7684) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [73a4cd0692](https://linux-hardware.org/?probe=73a4cd0692) | Sep 17, 2021 |
| HP            | Unknown                     | Notebook    | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [518209a322](https://linux-hardware.org/?probe=518209a322) | Sep 17, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [b3a1acb0f6](https://linux-hardware.org/?probe=b3a1acb0f6) | Sep 17, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [b7fe3ed969](https://linux-hardware.org/?probe=b7fe3ed969) | Sep 17, 2021 |
| Dell          | Latitude E5470              | Notebook    | [9a036a26a4](https://linux-hardware.org/?probe=9a036a26a4) | Sep 17, 2021 |
| HP            | Notebook                    | Notebook    | [6b2785c2e0](https://linux-hardware.org/?probe=6b2785c2e0) | Sep 17, 2021 |
| Dell          | Latitude E5500              | Notebook    | [286c99863b](https://linux-hardware.org/?probe=286c99863b) | Sep 16, 2021 |
| HP            | 245 G5 Notebook PC          | Notebook    | [ece740cf39](https://linux-hardware.org/?probe=ece740cf39) | Sep 16, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [042032eec7](https://linux-hardware.org/?probe=042032eec7) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | Notebook    | [04ba56c326](https://linux-hardware.org/?probe=04ba56c326) | Sep 16, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [142e3e40c2](https://linux-hardware.org/?probe=142e3e40c2) | Sep 16, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [152dd3680d](https://linux-hardware.org/?probe=152dd3680d) | Sep 16, 2021 |
| Jumper        | EZpad .A002                 | Notebook    | [c62d842a68](https://linux-hardware.org/?probe=c62d842a68) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | Notebook    | [6d381b570b](https://linux-hardware.org/?probe=6d381b570b) | Sep 15, 2021 |
| HP            | 255 G4 Notebook PC          | Notebook    | [c8a384ed00](https://linux-hardware.org/?probe=c8a384ed00) | Sep 15, 2021 |
| Acer          | One S1003                   | Tablet      | [e021ddcbf1](https://linux-hardware.org/?probe=e021ddcbf1) | Sep 15, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Latitude E7440              | Notebook    | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| Dell          | Latitude E6520              | Notebook    | [1bd8b6a82f](https://linux-hardware.org/?probe=1bd8b6a82f) | Sep 15, 2021 |
| Intel         | X99                         | Desktop     | [814b3326d1](https://linux-hardware.org/?probe=814b3326d1) | Sep 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [983922cfbf](https://linux-hardware.org/?probe=983922cfbf) | Sep 15, 2021 |
| NCR           | Talladega                   | Desktop     | [95445fa221](https://linux-hardware.org/?probe=95445fa221) | Sep 14, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Notebook                    | Notebook    | [d6825ad86c](https://linux-hardware.org/?probe=d6825ad86c) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [93a071ca7e](https://linux-hardware.org/?probe=93a071ca7e) | Sep 14, 2021 |
| Foxconn       | 17A0                        | Desktop     | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [874dcada55](https://linux-hardware.org/?probe=874dcada55) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [199ae9a9dd](https://linux-hardware.org/?probe=199ae9a9dd) | Sep 14, 2021 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [68ad9fb8e9](https://linux-hardware.org/?probe=68ad9fb8e9) | Sep 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [b3b1991c64](https://linux-hardware.org/?probe=b3b1991c64) | Sep 14, 2021 |
| Dell          | Latitude E5470              | Notebook    | [032f256bab](https://linux-hardware.org/?probe=032f256bab) | Sep 14, 2021 |
| Sony          | VPCF215FX                   | Notebook    | [173d8636d4](https://linux-hardware.org/?probe=173d8636d4) | Sep 14, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [93db4618cc](https://linux-hardware.org/?probe=93db4618cc) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b054524aac](https://linux-hardware.org/?probe=b054524aac) | Sep 14, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [864dde8a99](https://linux-hardware.org/?probe=864dde8a99) | Sep 13, 2021 |
| Acer          | One S1003                   | Tablet      | [a049a2a4d3](https://linux-hardware.org/?probe=a049a2a4d3) | Sep 13, 2021 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [d4a19b90eb](https://linux-hardware.org/?probe=d4a19b90eb) | Sep 13, 2021 |
| ASUSTek       | Benicia                     | Desktop     | [2a764dd662](https://linux-hardware.org/?probe=2a764dd662) | Sep 13, 2021 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [3818ff8f07](https://linux-hardware.org/?probe=3818ff8f07) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [6928772253](https://linux-hardware.org/?probe=6928772253) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [93a0d7ac6a](https://linux-hardware.org/?probe=93a0d7ac6a) | Sep 12, 2021 |
| HP            | Victus by HP Laptop 16-e... | Notebook    | [6a980ac620](https://linux-hardware.org/?probe=6a980ac620) | Sep 12, 2021 |
| HP            | 339A                        | Desktop     | [9284a70a92](https://linux-hardware.org/?probe=9284a70a92) | Sep 12, 2021 |
| Dell          | Latitude E6430              | Notebook    | [aff84b5ec1](https://linux-hardware.org/?probe=aff84b5ec1) | Sep 12, 2021 |
| Google        | Kindred                     | Notebook    | [c9ee8560b8](https://linux-hardware.org/?probe=c9ee8560b8) | Sep 12, 2021 |
| Dell          | XPS M1330                   | Notebook    | [404d33775d](https://linux-hardware.org/?probe=404d33775d) | Sep 12, 2021 |
| Dell          | Latitude E5500              | Notebook    | [1e20247950](https://linux-hardware.org/?probe=1e20247950) | Sep 12, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [8693b86435](https://linux-hardware.org/?probe=8693b86435) | Sep 12, 2021 |
| NCR           | Talladega                   | Desktop     | [6de6d8c2a3](https://linux-hardware.org/?probe=6de6d8c2a3) | Sep 12, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [6b02d3fa6f](https://linux-hardware.org/?probe=6b02d3fa6f) | Sep 11, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8b0f703471](https://linux-hardware.org/?probe=8b0f703471) | Sep 11, 2021 |
| Lenovo        | SDK0E50519 WIN              | Desktop     | [7c58527193](https://linux-hardware.org/?probe=7c58527193) | Sep 11, 2021 |
| Intel         | X79M-S                      | Desktop     | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| Dell          | XPS M1330                   | Notebook    | [3dcddbd59e](https://linux-hardware.org/?probe=3dcddbd59e) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [728e0facd6](https://linux-hardware.org/?probe=728e0facd6) | Sep 11, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [4e69ac73e4](https://linux-hardware.org/?probe=4e69ac73e4) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [33fd6d8c8f](https://linux-hardware.org/?probe=33fd6d8c8f) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [fa33f94b27](https://linux-hardware.org/?probe=fa33f94b27) | Sep 11, 2021 |
| MSI           | GE75 Raider 8RF             | Notebook    | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| Toshiba       | Satellite Pro L450D         | Notebook    | [a15c916899](https://linux-hardware.org/?probe=a15c916899) | Sep 10, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [1ff7b16ce4](https://linux-hardware.org/?probe=1ff7b16ce4) | Sep 10, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [dab9a23b27](https://linux-hardware.org/?probe=dab9a23b27) | Sep 10, 2021 |
| Toshiba       | Satellite C850-1CP          | Notebook    | [8cec9884a8](https://linux-hardware.org/?probe=8cec9884a8) | Sep 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Dell          | Latitude E5470              | Notebook    | [f6d8fa5367](https://linux-hardware.org/?probe=f6d8fa5367) | Sep 10, 2021 |
| Dell          | Latitude E5470              | Notebook    | [87b52d41c7](https://linux-hardware.org/?probe=87b52d41c7) | Sep 10, 2021 |
| HP            | Notebook                    | Notebook    | [24690d1b8b](https://linux-hardware.org/?probe=24690d1b8b) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [6ab68f26ba](https://linux-hardware.org/?probe=6ab68f26ba) | Sep 09, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [34e6b7697f](https://linux-hardware.org/?probe=34e6b7697f) | Sep 09, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [5ce713a2f7](https://linux-hardware.org/?probe=5ce713a2f7) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [52b22746e0](https://linux-hardware.org/?probe=52b22746e0) | Sep 09, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7fdf917680](https://linux-hardware.org/?probe=7fdf917680) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [15f063a517](https://linux-hardware.org/?probe=15f063a517) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [5b8b652e27](https://linux-hardware.org/?probe=5b8b652e27) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [e3e702ab7b](https://linux-hardware.org/?probe=e3e702ab7b) | Sep 09, 2021 |
| HP            | 2187 A01                    | Desktop     | [0c11e3b726](https://linux-hardware.org/?probe=0c11e3b726) | Sep 09, 2021 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | Notebook    | [ccb4dc3d9a](https://linux-hardware.org/?probe=ccb4dc3d9a) | Sep 09, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [0f52ac751b](https://linux-hardware.org/?probe=0f52ac751b) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [97b34f8c7f](https://linux-hardware.org/?probe=97b34f8c7f) | Sep 08, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [f3c9b271f1](https://linux-hardware.org/?probe=f3c9b271f1) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [7dbf053877](https://linux-hardware.org/?probe=7dbf053877) | Sep 08, 2021 |
| MSI           | H81M-P33                    | Desktop     | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 20RAS1Q800     | Notebook    | [a4d93ee5d2](https://linux-hardware.org/?probe=a4d93ee5d2) | Sep 08, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [6bff88fb9e](https://linux-hardware.org/?probe=6bff88fb9e) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | Notebook    | [3fc588a18d](https://linux-hardware.org/?probe=3fc588a18d) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | Notebook    | [fd38e5bf9d](https://linux-hardware.org/?probe=fd38e5bf9d) | Sep 08, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [22d88098a9](https://linux-hardware.org/?probe=22d88098a9) | Sep 08, 2021 |
| Dell          | 0D28YY A03                  | Desktop     | [3eb7b9cb7b](https://linux-hardware.org/?probe=3eb7b9cb7b) | Sep 08, 2021 |
| RCA           | W101-CS                     | Tablet      | [7ba24072d5](https://linux-hardware.org/?probe=7ba24072d5) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [be8d4bd453](https://linux-hardware.org/?probe=be8d4bd453) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [47317abce2](https://linux-hardware.org/?probe=47317abce2) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [98874d48b2](https://linux-hardware.org/?probe=98874d48b2) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f872b42a74](https://linux-hardware.org/?probe=f872b42a74) | Sep 07, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [2f680da4b8](https://linux-hardware.org/?probe=2f680da4b8) | Sep 07, 2021 |
| Acer          | V5-171                      | Notebook    | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| HP            | Notebook                    | Notebook    | [62a2618cde](https://linux-hardware.org/?probe=62a2618cde) | Sep 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [b00795951c](https://linux-hardware.org/?probe=b00795951c) | Sep 07, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [92d22f65bf](https://linux-hardware.org/?probe=92d22f65bf) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Dell          | Precision 3520              | Notebook    | [15e6e2c91d](https://linux-hardware.org/?probe=15e6e2c91d) | Sep 07, 2021 |
| Dell          | Precision 5550              | Notebook    | [8ae36d685d](https://linux-hardware.org/?probe=8ae36d685d) | Sep 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [368f488133](https://linux-hardware.org/?probe=368f488133) | Sep 07, 2021 |
| MSI           | GL62 7RDX                   | Notebook    | [be53fd4c86](https://linux-hardware.org/?probe=be53fd4c86) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [807eed7553](https://linux-hardware.org/?probe=807eed7553) | Sep 06, 2021 |
| ASRock        | Q1900M                      | Desktop     | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock        | Q1900M                      | Desktop     | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| Intel         | X79M-S                      | Desktop     | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [28754f0456](https://linux-hardware.org/?probe=28754f0456) | Sep 06, 2021 |
| HP            | Pavilion dv5                | Notebook    | [27607d962e](https://linux-hardware.org/?probe=27607d962e) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [46499caf7a](https://linux-hardware.org/?probe=46499caf7a) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | Notebook    | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d94c35ce11](https://linux-hardware.org/?probe=d94c35ce11) | Sep 05, 2021 |
| Acer          | One S1003                   | Tablet      | [879a8ee9da](https://linux-hardware.org/?probe=879a8ee9da) | Sep 05, 2021 |
| Acer          | One S1003                   | Tablet      | [e5d901c7a5](https://linux-hardware.org/?probe=e5d901c7a5) | Sep 05, 2021 |
| MSI           | IONA                        | Desktop     | [8a4454604a](https://linux-hardware.org/?probe=8a4454604a) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [791768dfbd](https://linux-hardware.org/?probe=791768dfbd) | Sep 04, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [ff8f35986b](https://linux-hardware.org/?probe=ff8f35986b) | Sep 04, 2021 |
| MSI           | IONA                        | Desktop     | [b775cef84a](https://linux-hardware.org/?probe=b775cef84a) | Sep 04, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [920ab9b385](https://linux-hardware.org/?probe=920ab9b385) | Sep 04, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | Desktop     | [149099265c](https://linux-hardware.org/?probe=149099265c) | Sep 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [391c101a92](https://linux-hardware.org/?probe=391c101a92) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [263eeefef0](https://linux-hardware.org/?probe=263eeefef0) | Sep 04, 2021 |
| HP            | 2B4B                        | Desktop     | [d36296bddf](https://linux-hardware.org/?probe=d36296bddf) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8cd745db58](https://linux-hardware.org/?probe=8cd745db58) | Sep 04, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [9e6ccaa1f3](https://linux-hardware.org/?probe=9e6ccaa1f3) | Sep 04, 2021 |
| Biostar       | X470NH                      | Desktop     | [f0449b9946](https://linux-hardware.org/?probe=f0449b9946) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | 255 G3                      | Notebook    | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | Notebook    | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [980716e0a8](https://linux-hardware.org/?probe=980716e0a8) | Sep 03, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [126d9974b1](https://linux-hardware.org/?probe=126d9974b1) | Sep 03, 2021 |
| ASUSTek       | GR8                         | Notebook    | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | Notebook    | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire E5-521G              | Notebook    | [d1aa71f003](https://linux-hardware.org/?probe=d1aa71f003) | Sep 02, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Toshiba       | Satellite C850D-11C         | Notebook    | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | 1497                        | Desktop     | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [3c88709f8a](https://linux-hardware.org/?probe=3c88709f8a) | Sep 01, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | Notebook    | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| Insyde        | i101c                       | Notebook    | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [baa289fe51](https://linux-hardware.org/?probe=baa289fe51) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [cc326a093e](https://linux-hardware.org/?probe=cc326a093e) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [4c711d446d](https://linux-hardware.org/?probe=4c711d446d) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [efb9bccc60](https://linux-hardware.org/?probe=efb9bccc60) | Aug 31, 2021 |
| HP            | Pavilion 15                 | Notebook    | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | Notebook    | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [000d760a55](https://linux-hardware.org/?probe=000d760a55) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [3b05a7b317](https://linux-hardware.org/?probe=3b05a7b317) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | Notebook    | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | Notebook    | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | Notebook    | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| MSI           | Z87-G43                     | Desktop     | [a219ff197d](https://linux-hardware.org/?probe=a219ff197d) | Aug 29, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [01a43874df](https://linux-hardware.org/?probe=01a43874df) | Aug 28, 2021 |
| Acer          | Aspire 5100                 | Notebook    | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | Notebook    | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | Notebook    | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [5cd3f43e28](https://linux-hardware.org/?probe=5cd3f43e28) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6ed5f8c32b](https://linux-hardware.org/?probe=6ed5f8c32b) | Aug 27, 2021 |
| ASRock        | Z390 Phantom Gaming 4-IB    | Desktop     | [b01269fbc1](https://linux-hardware.org/?probe=b01269fbc1) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [c59a1fff0d](https://linux-hardware.org/?probe=c59a1fff0d) | Aug 26, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [accc3b9ebb](https://linux-hardware.org/?probe=accc3b9ebb) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| Acer          | AO722                       | Notebook    | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| HP            | 802E                        | Desktop     | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [8620323354](https://linux-hardware.org/?probe=8620323354) | Aug 25, 2021 |
| TianBei       | TB-H7                       | Notebook    | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Dell          | 0TP406                      | Desktop     | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| HP            | 2B4B                        | Desktop     | [4c5411522b](https://linux-hardware.org/?probe=4c5411522b) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | Notebook    | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | Notebook    | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [a720e3326a](https://linux-hardware.org/?probe=a720e3326a) | Aug 23, 2021 |
| Acer          | Aspire 8940G                | Notebook    | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | Notebook    | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | Notebook    | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [e6f053c5be](https://linux-hardware.org/?probe=e6f053c5be) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [8eed93b589](https://linux-hardware.org/?probe=8eed93b589) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [372a125910](https://linux-hardware.org/?probe=372a125910) | Aug 22, 2021 |
| Lenovo        | Unknown                     | Desktop     | [b4e9579228](https://linux-hardware.org/?probe=b4e9579228) | Aug 21, 2021 |
| Lenovo        | Unknown                     | Desktop     | [12088eed17](https://linux-hardware.org/?probe=12088eed17) | Aug 21, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [68c6a2734b](https://linux-hardware.org/?probe=68c6a2734b) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | Notebook    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | Notebook    | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | Notebook    | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | Notebook    | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [4bbb9f60f9](https://linux-hardware.org/?probe=4bbb9f60f9) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [0acfc1ab65](https://linux-hardware.org/?probe=0acfc1ab65) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [27898f0b8e](https://linux-hardware.org/?probe=27898f0b8e) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | Notebook    | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | Notebook    | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d78450d852](https://linux-hardware.org/?probe=d78450d852) | Aug 19, 2021 |
| Acer          | Aspire XC-605G              | Desktop     | [8bb6f8ef72](https://linux-hardware.org/?probe=8bb6f8ef72) | Aug 18, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [daf6bf889f](https://linux-hardware.org/?probe=daf6bf889f) | Aug 18, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [3be5b7f90e](https://linux-hardware.org/?probe=3be5b7f90e) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [06872ddde7](https://linux-hardware.org/?probe=06872ddde7) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [65567a1be4](https://linux-hardware.org/?probe=65567a1be4) | Aug 10, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | Desktop     | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [01e77d1c5f](https://linux-hardware.org/?probe=01e77d1c5f) | Aug 04, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [c5d61df0df](https://linux-hardware.org/?probe=c5d61df0df) | Aug 03, 2021 |
| Gigabyte      | B550M H                     | Desktop     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [733eb370f2](https://linux-hardware.org/?probe=733eb370f2) | Jul 27, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [79b20f33a0](https://linux-hardware.org/?probe=79b20f33a0) | Jul 24, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [94ef768b69](https://linux-hardware.org/?probe=94ef768b69) | Jul 24, 2021 |
| Acer          | Aspire E5-551G              | Notebook    | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [3bed53aab7](https://linux-hardware.org/?probe=3bed53aab7) | Jul 14, 2021 |
| Dell          | 0V8WGR A00                  | Desktop     | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Dell          | XPS L501X                   | Notebook    | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | Notebook    | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI           | 2AE0                        | Desktop     | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI           | 2AE0                        | Desktop     | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| Dell          | Inspiron 3582               | Notebook    | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [b9d86eb932](https://linux-hardware.org/?probe=b9d86eb932) | Jun 17, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [71de5617aa](https://linux-hardware.org/?probe=71de5617aa) | Jun 17, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | Notebook    | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| HP            | 843C                        | Desktop     | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | Notebook    | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP            | 8591                        | Desktop     | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP            | 8591                        | Desktop     | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| HP            | Unknown                     | Notebook    | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | Notebook    | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar       | A320MH                      | Desktop     | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar       | A320MH                      | Desktop     | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c41eec9cd3](https://linux-hardware.org/?probe=c41eec9cd3) | May 21, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | Notebook    | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Quanta        | XV1                         | All in one  | [d3b0fddedf](https://linux-hardware.org/?probe=d3b0fddedf) | May 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Quanta        | XV1                         | All in one  | [5d38d7934e](https://linux-hardware.org/?probe=5d38d7934e) | Apr 30, 2021 |
| Pegatron      | Benicia                     | Desktop     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [236ed4432a](https://linux-hardware.org/?probe=236ed4432a) | Apr 24, 2021 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek       | P5K                         | Desktop     | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell          | 0PGKWF A02                  | Desktop     | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0761ed6181](https://linux-hardware.org/?probe=0761ed6181) | Apr 16, 2021 |
| Acer          | Aspire XC-605G              | Desktop     | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.11.0-38-generic           | 168       | 13.74%  |
| 5.11.0-27-generic           | 154       | 12.59%  |
| 5.11.0-40-generic           | 122       | 9.98%   |
| 5.11.0-37-generic           | 112       | 9.16%   |
| 5.11.0-41-generic           | 105       | 8.59%   |
| 5.11.0-43-generic           | 104       | 8.5%    |
| 5.11.0-34-generic           | 94        | 7.69%   |
| 5.13.0-28-generic           | 71        | 5.81%   |
| 5.13.0-27-generic           | 55        | 4.5%    |
| 5.13.0-30-generic           | 41        | 3.35%   |
| 5.11.0-36-generic           | 39        | 3.19%   |
| 5.11.0-44-generic           | 36        | 2.94%   |
| 5.11.0-46-generic           | 35        | 2.86%   |
| 5.11.0-25-generic           | 16        | 1.31%   |
| 5.8.0-53-generic            | 13        | 1.06%   |
| 5.8.0-50-generic            | 12        | 0.98%   |
| 5.8.0-55-generic            | 10        | 0.82%   |
| 5.8.0-59-generic            | 8         | 0.65%   |
| 5.8.0-49-generic            | 5         | 0.41%   |
| 5.8.0-63-generic            | 4         | 0.33%   |
| 5.13.0-25-generic           | 3         | 0.25%   |
| 5.8.0-45-generic            | 1         | 0.08%   |
| 5.4.0-42-generic            | 1         | 0.08%   |
| 5.16.5-surface              | 1         | 0.08%   |
| 5.16.0-051600rc8-lowlatency | 1         | 0.08%   |
| 5.16.0-051600rc4-generic    | 1         | 0.08%   |
| 5.15.24-xanmod1             | 1         | 0.08%   |
| 5.15.13-051513-generic      | 1         | 0.08%   |
| 5.15.0-8.1-liquorix-amd64   | 1         | 0.08%   |
| 5.15.0-10.2-liquorix-amd64  | 1         | 0.08%   |
| 5.15.0-051500-generic       | 1         | 0.08%   |
| 5.14.0-15.1-liquorix-amd64  | 1         | 0.08%   |
| 5.14.0-1010-oem             | 1         | 0.08%   |
| 5.13.18-xanmod1             | 1         | 0.08%   |
| 5.13.0-1020-oem             | 1         | 0.08%   |
| 5.10.0-1052-oem             | 1         | 0.08%   |
| 5.10.0-1044-oem             | 1         | 0.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 932       | 80.07%  |
| 5.13.0  | 166       | 14.26%  |
| 5.8.0   | 52        | 4.47%   |
| 5.15.0  | 3         | 0.26%   |
| 5.16.0  | 2         | 0.17%   |
| 5.14.0  | 2         | 0.17%   |
| 5.10.0  | 2         | 0.17%   |
| 5.4.0   | 1         | 0.09%   |
| 5.16.5  | 1         | 0.09%   |
| 5.15.24 | 1         | 0.09%   |
| 5.15.13 | 1         | 0.09%   |
| 5.13.18 | 1         | 0.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 932       | 80.07%  |
| 5.13    | 167       | 14.35%  |
| 5.8     | 52        | 4.47%   |
| 5.15    | 5         | 0.43%   |
| 5.16    | 3         | 0.26%   |
| 5.14    | 2         | 0.17%   |
| 5.10    | 2         | 0.17%   |
| 5.4     | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 1133      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 1062      | 93.32%  |
| XFCE       | 62        | 5.45%   |
| Unknown    | 9         | 0.79%   |
| X-Cinnamon | 1         | 0.09%   |
| MATE       | 1         | 0.09%   |
| KDE        | 1         | 0.09%   |
| Cinnamon   | 1         | 0.09%   |
| Budgie     | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1118      | 98.42%  |
| Wayland | 15        | 1.32%   |
| Unknown | 3         | 0.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 924       | 80.98%  |
| GDM3    | 107       | 9.38%   |
| GDM     | 101       | 8.85%   |
| LightDM | 7         | 0.61%   |
| TDM     | 1         | 0.09%   |
| SDDM    | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 462       | 40.63%  |
| de_DE       | 114       | 10.03%  |
| en_GB       | 90        | 7.92%   |
| pt_BR       | 61        | 5.36%   |
| es_ES       | 35        | 3.08%   |
| en_IN       | 34        | 2.99%   |
| pl_PL       | 31        | 2.73%   |
| en_CA       | 31        | 2.73%   |
| fr_FR       | 26        | 2.29%   |
| it_IT       | 25        | 2.2%    |
| nl_NL       | 20        | 1.76%   |
| en_AU       | 20        | 1.76%   |
| es_MX       | 18        | 1.58%   |
| ru_RU       | 14        | 1.23%   |
| pt_PT       | 11        | 0.97%   |
| cs_CZ       | 11        | 0.97%   |
| es_CL       | 10        | 0.88%   |
| en_ZA       | 10        | 0.88%   |
| hu_HU       | 8         | 0.7%    |
| fr_BE       | 8         | 0.7%    |
| en_NZ       | 7         | 0.62%   |
| sv_SE       | 6         | 0.53%   |
| es_AR       | 6         | 0.53%   |
| nl_BE       | 5         | 0.44%   |
| de_CH       | 5         | 0.44%   |
| tr_TR       | 4         | 0.35%   |
| nb_NO       | 4         | 0.35%   |
| ja_JP       | 4         | 0.35%   |
| de_AT       | 4         | 0.35%   |
| sl_SI       | 3         | 0.26%   |
| ru_UA       | 3         | 0.26%   |
| fr_CA       | 3         | 0.26%   |
| fi_FI       | 3         | 0.26%   |
| es_CO       | 3         | 0.26%   |
| el_GR       | 3         | 0.26%   |
| bg_BG       | 3         | 0.26%   |
| zh_TW       | 2         | 0.18%   |
| sk_SK       | 2         | 0.18%   |
| hr_HR       | 2         | 0.18%   |
| es_PE       | 2         | 0.18%   |
| es_PA       | 2         | 0.18%   |
| en_SG       | 2         | 0.18%   |
| en_IL       | 2         | 0.18%   |
| C           | 2         | 0.18%   |
| ar_EG       | 2         | 0.18%   |
| zh_CN       | 1         | 0.09%   |
| sr_RS@latin | 1         | 0.09%   |
| sr_RS       | 1         | 0.09%   |
| ro_RO       | 1         | 0.09%   |
| he_IL       | 1         | 0.09%   |
| fr_CH       | 1         | 0.09%   |
| es_UY       | 1         | 0.09%   |
| es_NI       | 1         | 0.09%   |
| es_GT       | 1         | 0.09%   |
| es_EC       | 1         | 0.09%   |
| es_CR       | 1         | 0.09%   |
| es_BO       | 1         | 0.09%   |
| en_PH       | 1         | 0.09%   |
| da_DK       | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 631       | 55.16%  |
| BIOS | 513       | 44.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1067      | 94.17%  |
| Zfs      | 21        | 1.85%   |
| Overlay  | 19        | 1.68%   |
| Btrfs    | 16        | 1.41%   |
| Xfs      | 3         | 0.26%   |
| Ext3     | 3         | 0.26%   |
| Ext2     | 3         | 0.26%   |
| Reiserfs | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1030      | 90.35%  |
| GPT     | 96        | 8.42%   |
| MBR     | 14        | 1.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1106      | 97.44%  |
| Yes       | 29        | 2.56%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1016      | 89.36%  |
| Yes       | 121       | 10.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 190       | 16.77%  |
| Hewlett-Packard             | 181       | 15.98%  |
| Dell                        | 155       | 13.68%  |
| Lenovo                      | 137       | 12.09%  |
| Gigabyte Technology         | 72        | 6.35%   |
| Acer                        | 68        | 6%      |
| MSI                         | 55        | 4.85%   |
| ASRock                      | 38        | 3.35%   |
| Apple                       | 35        | 3.09%   |
| Toshiba                     | 30        | 2.65%   |
| Intel                       | 22        | 1.94%   |
| Unknown                     | 13        | 1.15%   |
| Sony                        | 12        | 1.06%   |
| Samsung Electronics         | 12        | 1.06%   |
| Fujitsu                     | 8         | 0.71%   |
| Microsoft                   | 6         | 0.53%   |
| Google                      | 6         | 0.53%   |
| Foxconn                     | 6         | 0.53%   |
| Biostar                     | 6         | 0.53%   |
| Packard Bell                | 4         | 0.35%   |
| Notebook                    | 4         | 0.35%   |
| LG Electronics              | 4         | 0.35%   |
| RCA                         | 3         | 0.26%   |
| Razer                       | 3         | 0.26%   |
| Positivo                    | 3         | 0.26%   |
| Pegatron                    | 3         | 0.26%   |
| Jumper                      | 3         | 0.26%   |
| HUAWEI                      | 3         | 0.26%   |
| TUXEDO                      | 2         | 0.18%   |
| NEC Computers               | 2         | 0.18%   |
| Multilaser                  | 2         | 0.18%   |
| Fujitsu Siemens             | 2         | 0.18%   |
| ECS                         | 2         | 0.18%   |
| Digibras                    | 2         | 0.18%   |
| Chuwi                       | 2         | 0.18%   |
| ZOTAC                       | 1         | 0.09%   |
| Wortmann AG                 | 1         | 0.09%   |
| UNOWHY                      | 1         | 0.09%   |
| TianBei                     | 1         | 0.09%   |
| Thomson                     | 1         | 0.09%   |
| TCL Communication           | 1         | 0.09%   |
| Star Labs                   | 1         | 0.09%   |
| Shuttle                     | 1         | 0.09%   |
| Schenker                    | 1         | 0.09%   |
| Sapphire Technology Limited | 1         | 0.09%   |
| Quanta                      | 1         | 0.09%   |
| Primux                      | 1         | 0.09%   |
| Oracle                      | 1         | 0.09%   |
| Novatech                    | 1         | 0.09%   |
| NCR                         | 1         | 0.09%   |
| mPTech                      | 1         | 0.09%   |
| Medion                      | 1         | 0.09%   |
| Mediacom                    | 1         | 0.09%   |
| MECER                       | 1         | 0.09%   |
| Login Informatica           | 1         | 0.09%   |
| LattePanda                  | 1         | 0.09%   |
| KOGAN                       | 1         | 0.09%   |
| Insyde                      | 1         | 0.09%   |
| IBM                         | 1         | 0.09%   |
| Giani Limited               | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 16        | 1.41%   |
| ASUS All Series                | 11        | 0.97%   |
| HP Notebook                    | 8         | 0.71%   |
| HP 15                          | 6         | 0.53%   |
| Dell OptiPlex 990              | 5         | 0.44%   |
| Dell OptiPlex 790              | 5         | 0.44%   |
| Dell OptiPlex 7010             | 5         | 0.44%   |
| MSI MS-7817                    | 4         | 0.35%   |
| HP Pavilion 15                 | 4         | 0.35%   |
| Dell Latitude E7440            | 4         | 0.35%   |
| MSI MS-7C02                    | 3         | 0.26%   |
| Lenovo IdeaPad S340-14API 81NB | 3         | 0.26%   |
| Lenovo IdeaPad S145-15API 81V7 | 3         | 0.26%   |
| Intel X79M-S                   | 3         | 0.26%   |
| HP Pavilion Notebook           | 3         | 0.26%   |
| HP OMEN by Laptop 15-dc1xxx    | 3         | 0.26%   |
| Gigabyte A320M-S2H             | 3         | 0.26%   |
| Dell Latitude E6420            | 3         | 0.26%   |
| ASUS P8Z77-V LX                | 3         | 0.26%   |
| ASUS M5A78L-M/USB3             | 3         | 0.26%   |
| ASRock B450M Pro4              | 3         | 0.26%   |
| Apple MacBookPro8,1            | 3         | 0.26%   |
| Apple MacBookPro11,1           | 3         | 0.26%   |
| Apple iMac12,2                 | 3         | 0.26%   |
| Packard Bell EasyNote TK85     | 2         | 0.18%   |
| MSI MS-7B89                    | 2         | 0.18%   |
| MSI MS-7693                    | 2         | 0.18%   |
| Microsoft Surface Pro          | 2         | 0.18%   |
| Lenovo Yoga 530-14IKB 81EK     | 2         | 0.18%   |
| Lenovo Yoga 3 Pro-1370 80HE    | 2         | 0.18%   |
| Lenovo IdeaPad Yoga 13 20175   | 2         | 0.18%   |
| Lenovo IdeaPad Flex-14API 81SS | 2         | 0.18%   |
| Lenovo IdeaPad 3 15IIL05 81WE  | 2         | 0.18%   |
| Lenovo G50-70 20351            | 2         | 0.18%   |
| Jumper EZbook                  | 2         | 0.18%   |
| Intel DQ77MK-R01               | 2         | 0.18%   |
| HP ProOne 400 G1 AiO           | 2         | 0.18%   |
| HP ProDesk 600 G1 SFF          | 2         | 0.18%   |
| HP ProBook 6450b               | 2         | 0.18%   |
| HP Pavilion Laptop 15-cs3xxx   | 2         | 0.18%   |
| HP Pavilion g6                 | 2         | 0.18%   |
| HP Pavilion dv7                | 2         | 0.18%   |
| HP Pavilion dv5                | 2         | 0.18%   |
| HP OMEN Notebook               | 2         | 0.18%   |
| HP Laptop 15-bw0xx             | 2         | 0.18%   |
| HP ENVY Sleekbook 4 PC         | 2         | 0.18%   |
| HP EliteBook Folio 9470m       | 2         | 0.18%   |
| HP EliteBook 8440p             | 2         | 0.18%   |
| HP EliteBook 840 G1            | 2         | 0.18%   |
| HP Compaq Pro 6300 SFF         | 2         | 0.18%   |
| HP Compaq 8510p                | 2         | 0.18%   |
| HP Compaq 6200 Pro SFF PC      | 2         | 0.18%   |
| Google Kindred                 | 2         | 0.18%   |
| Gigabyte X570 AORUS MASTER     | 2         | 0.18%   |
| Gigabyte X570 AORUS ELITE      | 2         | 0.18%   |
| Gigabyte G31M-ES2L             | 2         | 0.18%   |
| Gigabyte B75M-D3H              | 2         | 0.18%   |
| Gigabyte B560M AORUS ELITE     | 2         | 0.18%   |
| Gigabyte B450 AORUS M          | 2         | 0.18%   |
| Gigabyte 970A-DS3P             | 2         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 47        | 4.15%   |
| Dell Latitude          | 46        | 4.06%   |
| Lenovo ThinkPad        | 44        | 3.88%   |
| Dell Inspiron          | 38        | 3.35%   |
| Lenovo IdeaPad         | 32        | 2.82%   |
| HP Pavilion            | 31        | 2.74%   |
| Dell OptiPlex          | 31        | 2.74%   |
| Toshiba Satellite      | 22        | 1.94%   |
| HP EliteBook           | 19        | 1.68%   |
| HP ProBook             | 17        | 1.5%    |
| ASUS PRIME             | 16        | 1.41%   |
| Unknown                | 16        | 1.41%   |
| HP ENVY                | 13        | 1.15%   |
| HP Compaq              | 13        | 1.15%   |
| ASUS VivoBook          | 13        | 1.15%   |
| Lenovo ThinkCentre     | 12        | 1.06%   |
| Dell XPS               | 12        | 1.06%   |
| ASUS ROG               | 12        | 1.06%   |
| Dell Precision         | 11        | 0.97%   |
| ASUS All               | 11        | 0.97%   |
| Lenovo Yoga            | 10        | 0.88%   |
| HP Laptop              | 10        | 0.88%   |
| ASUS TUF               | 9         | 0.79%   |
| HP Notebook            | 8         | 0.71%   |
| HP OMEN                | 7         | 0.62%   |
| HP 15                  | 7         | 0.62%   |
| Dell Vostro            | 7         | 0.62%   |
| Microsoft Surface      | 6         | 0.53%   |
| HP Stream              | 6         | 0.53%   |
| ASUS ZenBook           | 6         | 0.53%   |
| HP EliteDesk           | 5         | 0.44%   |
| HP 255                 | 5         | 0.44%   |
| Gigabyte X570          | 5         | 0.44%   |
| Gigabyte B450          | 5         | 0.44%   |
| ASUS M5A97             | 5         | 0.44%   |
| ASUS M5A78L-M          | 5         | 0.44%   |
| ASRock B450M           | 5         | 0.44%   |
| Apple MacBookPro11     | 5         | 0.44%   |
| Acer Swift             | 5         | 0.44%   |
| Toshiba PORTEGE        | 4         | 0.35%   |
| MSI MS-7817            | 4         | 0.35%   |
| Fujitsu ESPRIMO        | 4         | 0.35%   |
| ASUS P8Z77-V           | 4         | 0.35%   |
| ASUS P8H61-M           | 4         | 0.35%   |
| ASUS ASUS              | 4         | 0.35%   |
| Apple iMac12           | 4         | 0.35%   |
| Packard Bell EasyNote  | 3         | 0.26%   |
| MSI MS-7C02            | 3         | 0.26%   |
| Lenovo ThinkBook       | 3         | 0.26%   |
| Lenovo MIIX            | 3         | 0.26%   |
| Lenovo Legion          | 3         | 0.26%   |
| Lenovo IdeaCentre      | 3         | 0.26%   |
| Intel X79M-S           | 3         | 0.26%   |
| HP ProDesk             | 3         | 0.26%   |
| Gigabyte GA-78LMT-USB3 | 3         | 0.26%   |
| Gigabyte B450M         | 3         | 0.26%   |
| Gigabyte A320M-S2H     | 3         | 0.26%   |
| Fujitsu LIFEBOOK       | 3         | 0.26%   |
| ASUS P5G41T-M          | 3         | 0.26%   |
| ASRock B450            | 3         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 113       | 9.97%   |
| 2011 | 106       | 9.36%   |
| 2013 | 102       | 9%      |
| 2019 | 96        | 8.47%   |
| 2018 | 93        | 8.21%   |
| 2014 | 89        | 7.86%   |
| 2020 | 88        | 7.77%   |
| 2017 | 73        | 6.44%   |
| 2021 | 72        | 6.35%   |
| 2016 | 68        | 6%      |
| 2010 | 58        | 5.12%   |
| 2008 | 48        | 4.24%   |
| 2015 | 47        | 4.15%   |
| 2009 | 41        | 3.62%   |
| 2007 | 30        | 2.65%   |
| 2006 | 6         | 0.53%   |
| 2005 | 2         | 0.18%   |
| 2022 | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 632       | 55.78%  |
| Desktop     | 416       | 36.72%  |
| Convertible | 27        | 2.38%   |
| All in one  | 27        | 2.38%   |
| Tablet      | 14        | 1.24%   |
| Mini pc     | 13        | 1.15%   |
| Server      | 4         | 0.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1012      | 88.69%  |
| Enabled  | 129       | 11.31%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1126      | 99.38%  |
| Yes  | 7         | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 306       | 26.87%  |
| 3.01-4.0    | 241       | 21.16%  |
| 8.01-16.0   | 209       | 18.35%  |
| 16.01-24.0  | 197       | 17.3%   |
| 32.01-64.0  | 90        | 7.9%    |
| 1.01-2.0    | 53        | 4.65%   |
| 64.01-256.0 | 19        | 1.67%   |
| 2.01-3.0    | 14        | 1.23%   |
| 24.01-32.0  | 9         | 0.79%   |
| 0.51-1.0    | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 517       | 43.01%  |
| 2.01-3.0   | 391       | 32.53%  |
| 3.01-4.0   | 153       | 12.73%  |
| 4.01-8.0   | 109       | 9.07%   |
| 0.51-1.0   | 17        | 1.41%   |
| 8.01-16.0  | 12        | 1%      |
| 24.01-32.0 | 2         | 0.17%   |
| 16.01-24.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 709       | 61.71%  |
| 2      | 281       | 24.46%  |
| 3      | 77        | 6.7%    |
| 4      | 33        | 2.87%   |
| 5      | 20        | 1.74%   |
| 6      | 14        | 1.22%   |
| 0      | 6         | 0.52%   |
| 8      | 4         | 0.35%   |
| 7      | 3         | 0.26%   |
| 30     | 1         | 0.09%   |
| 11     | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 614       | 53.91%  |
| Yes       | 525       | 46.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 984       | 86.77%  |
| No        | 150       | 13.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 889       | 78.4%   |
| No        | 245       | 21.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 672       | 58.95%  |
| No        | 468       | 41.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 285       | 25.13%  |
| Germany                | 124       | 10.93%  |
| UK                     | 75        | 6.61%   |
| Brazil                 | 70        | 6.17%   |
| Spain                  | 40        | 3.53%   |
| Canada                 | 37        | 3.26%   |
| India                  | 35        | 3.09%   |
| Netherlands            | 29        | 2.56%   |
| Italy                  | 28        | 2.47%   |
| Poland                 | 27        | 2.38%   |
| France                 | 24        | 2.12%   |
| Mexico                 | 22        | 1.94%   |
| Australia              | 22        | 1.94%   |
| Belgium                | 19        | 1.68%   |
| Austria                | 15        | 1.32%   |
| South Africa           | 14        | 1.23%   |
| Russia                 | 13        | 1.15%   |
| Hungary                | 13        | 1.15%   |
| Sweden                 | 12        | 1.06%   |
| Czechia                | 11        | 0.97%   |
| Chile                  | 11        | 0.97%   |
| Switzerland            | 10        | 0.88%   |
| Portugal               | 10        | 0.88%   |
| Norway                 | 10        | 0.88%   |
| Turkey                 | 9         | 0.79%   |
| Romania                | 9         | 0.79%   |
| Japan                  | 9         | 0.79%   |
| New Zealand            | 8         | 0.71%   |
| Greece                 | 8         | 0.71%   |
| Argentina              | 8         | 0.71%   |
| Ukraine                | 6         | 0.53%   |
| Denmark                | 6         | 0.53%   |
| Malaysia               | 5         | 0.44%   |
| Indonesia              | 5         | 0.44%   |
| Finland                | 5         | 0.44%   |
| Croatia                | 5         | 0.44%   |
| Colombia               | 5         | 0.44%   |
| Bulgaria               | 5         | 0.44%   |
| Israel                 | 4         | 0.35%   |
| Vietnam                | 3         | 0.26%   |
| Taiwan                 | 3         | 0.26%   |
| Slovenia               | 3         | 0.26%   |
| Saudi Arabia           | 3         | 0.26%   |
| Morocco                | 3         | 0.26%   |
| Kenya                  | 3         | 0.26%   |
| Ireland                | 3         | 0.26%   |
| Egypt                  | 3         | 0.26%   |
| Bangladesh             | 3         | 0.26%   |
| Thailand               | 2         | 0.18%   |
| Slovakia               | 2         | 0.18%   |
| Singapore              | 2         | 0.18%   |
| Serbia                 | 2         | 0.18%   |
| Philippines            | 2         | 0.18%   |
| Panama                 | 2         | 0.18%   |
| Moldova                | 2         | 0.18%   |
| Lithuania              | 2         | 0.18%   |
| Ghana                  | 2         | 0.18%   |
| El Salvador            | 2         | 0.18%   |
| China                  | 2         | 0.18%   |
| Bosnia and Herzegovina | 2         | 0.18%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Berlin         | 11        | 0.95%   |
| Athens         | 10        | 0.87%   |
| Vienna         | 9         | 0.78%   |
| Sydney         | 7         | 0.61%   |
| Dallas         | 7         | 0.61%   |
| Hamburg        | 6         | 0.52%   |
| Warsaw         | 5         | 0.43%   |
| SÃ£o Paulo   | 5         | 0.43%   |
| Rome           | 5         | 0.43%   |
| Munich         | 5         | 0.43%   |
| Melbourne      | 5         | 0.43%   |
| Cape Town      | 5         | 0.43%   |
| Bernissart     | 5         | 0.43%   |
| Amsterdam      | 5         | 0.43%   |
| Zagreb         | 4         | 0.35%   |
| Stuttgart      | 4         | 0.35%   |
| Perth          | 4         | 0.35%   |
| Paris          | 4         | 0.35%   |
| New York       | 4         | 0.35%   |
| Moscow         | 4         | 0.35%   |
| Minneapolis    | 4         | 0.35%   |
| London         | 4         | 0.35%   |
| Johannesburg   | 4         | 0.35%   |
| Helsinki       | 4         | 0.35%   |
| Glasgow        | 4         | 0.35%   |
| Dortmund       | 4         | 0.35%   |
| Chicago        | 4         | 0.35%   |
| Chennai        | 4         | 0.35%   |
| Budapest       | 4         | 0.35%   |
| Auckland       | 4         | 0.35%   |
| Valencia       | 3         | 0.26%   |
| Stockholm      | 3         | 0.26%   |
| SÃ£o LuÃ­s | 3         | 0.26%   |
| Santiago       | 3         | 0.26%   |
| San Jose       | 3         | 0.26%   |
| San Francisco  | 3         | 0.26%   |
| Salt Lake City | 3         | 0.26%   |
| Rio de Janeiro | 3         | 0.26%   |
| Richmond       | 3         | 0.26%   |
| Neath          | 3         | 0.26%   |
| Nairobi        | 3         | 0.26%   |
| Montreal       | 3         | 0.26%   |
| Milan          | 3         | 0.26%   |
| Mexico City    | 3         | 0.26%   |
| Mentor         | 3         | 0.26%   |
| Madrid         | 3         | 0.26%   |
| Kyiv           | 3         | 0.26%   |
| Kuala Lumpur   | 3         | 0.26%   |
| Houston        | 3         | 0.26%   |
| Fortaleza      | 3         | 0.26%   |
| Eugene         | 3         | 0.26%   |
| Dayton         | 3         | 0.26%   |
| Charlotte      | 3         | 0.26%   |
| Brussels       | 3         | 0.26%   |
| Blue Springs   | 3         | 0.26%   |
| Bengaluru      | 3         | 0.26%   |
| Barcelona      | 3         | 0.26%   |
| Austin         | 3         | 0.26%   |
| Ankara         | 3         | 0.26%   |
| Alexandria     | 3         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 265       | 370    | 16.45%  |
| Samsung Electronics         | 236       | 328    | 14.65%  |
| WDC                         | 217       | 275    | 13.47%  |
| Toshiba                     | 119       | 131    | 7.39%   |
| SanDisk                     | 108       | 125    | 6.7%    |
| Kingston                    | 86        | 109    | 5.34%   |
| Unknown                     | 82        | 105    | 5.09%   |
| Hitachi                     | 66        | 91     | 4.1%    |
| Crucial                     | 55        | 68     | 3.41%   |
| SK Hynix                    | 27        | 36     | 1.68%   |
| Intel                       | 27        | 34     | 1.68%   |
| A-DATA Technology           | 27        | 29     | 1.68%   |
| HGST                        | 26        | 33     | 1.61%   |
| Micron Technology           | 19        | 20     | 1.18%   |
| PHISON                      | 18        | 22     | 1.12%   |
| Apple                       | 15        | 16     | 0.93%   |
| China                       | 13        | 14     | 0.81%   |
| Silicon Motion              | 11        | 18     | 0.68%   |
| Intenso                     | 9         | 9      | 0.56%   |
| Hewlett-Packard             | 9         | 12     | 0.56%   |
| SPCC                        | 8         | 11     | 0.5%    |
| PNY                         | 8         | 10     | 0.5%    |
| KIOXIA                      | 8         | 8      | 0.5%    |
| JMicron                     | 8         | 10     | 0.5%    |
| Transcend                   | 7         | 22     | 0.43%   |
| OCZ                         | 6         | 6      | 0.37%   |
| MAXTOR                      | 6         | 7      | 0.37%   |
| Lexar                       | 6         | 6      | 0.37%   |
| GOODRAM                     | 6         | 6      | 0.37%   |
| Realtek Semiconductor       | 5         | 6      | 0.31%   |
| Patriot                     | 5         | 5      | 0.31%   |
| Netac                       | 5         | 5      | 0.31%   |
| KingSpec                    | 5         | 6      | 0.31%   |
| Fujitsu                     | 5         | 6      | 0.31%   |
| Super Talent                | 4         | 5      | 0.25%   |
| SABRENT                     | 4         | 5      | 0.25%   |
| Micron/Crucial Technology   | 4         | 4      | 0.25%   |
| LITEONIT                    | 4         | 5      | 0.25%   |
| Gigabyte Technology         | 4         | 4      | 0.25%   |
| XPG                         | 3         | 3      | 0.19%   |
| Team                        | 3         | 4      | 0.19%   |
| OWC                         | 3         | 3      | 0.19%   |
| Lite-On                     | 3         | 5      | 0.19%   |
| KIOXIA-EXCERIA              | 3         | 4      | 0.19%   |
| Corsair                     | 3         | 3      | 0.19%   |
| Unknown                     | 3         | 3      | 0.19%   |
| Verbatim                    | 2         | 2      | 0.12%   |
| Teclast                     | 2         | 2      | 0.12%   |
| T-FORCE                     | 2         | 3      | 0.12%   |
| LITEON                      | 2         | 2      | 0.12%   |
| KingFast                    | 2         | 2      | 0.12%   |
| BHT                         | 2         | 2      | 0.12%   |
| Apacer                      | 2         | 2      | 0.12%   |
| Yangtze Memory Technologies | 1         | 1      | 0.06%   |
| XrayDisk                    | 1         | 1      | 0.06%   |
| WD MediaMax                 | 1         | 2      | 0.06%   |
| Vaseky                      | 1         | 2      | 0.06%   |
| USB30                       | 1         | 4      | 0.06%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.06%   |
| TO Exter                    | 1         | 1      | 0.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 30        | 1.67%   |
| Kingston SA400S37240G 240GB SSD        | 24        | 1.34%   |
| Unknown MMC Card  64GB                 | 23        | 1.28%   |
| Seagate ST500DM002-1BD142 500GB        | 19        | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 18        | 1%      |
| Samsung SSD 860 EVO 500GB              | 18        | 1%      |
| Samsung NVMe SSD Drive 512GB           | 17        | 0.95%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 16        | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB         | 14        | 0.78%   |
| Samsung NVMe SSD Drive 500GB           | 14        | 0.78%   |
| Kingston SA400S37120G 120GB SSD        | 14        | 0.78%   |
| Samsung NVMe SSD Drive 1TB             | 13        | 0.72%   |
| Toshiba MQ04ABF100 1TB                 | 12        | 0.67%   |
| Toshiba MQ01ABD100 1TB                 | 12        | 0.67%   |
| Sandisk NVMe SSD Drive 256GB           | 12        | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB               | 11        | 0.61%   |
| Unknown SD/MMC/MS PRO 64GB             | 11        | 0.61%   |
| Sandisk NVMe SSD Drive 512GB           | 11        | 0.61%   |
| Samsung SSD 850 EVO 250GB              | 11        | 0.61%   |
| Crucial CT500MX500SSD1 500GB           | 11        | 0.61%   |
| Crucial CT240BX500SSD1 240GB           | 11        | 0.61%   |
| Unknown MMC Card  128GB                | 10        | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB         | 10        | 0.56%   |
| Samsung SSD 850 EVO 500GB              | 10        | 0.56%   |
| Samsung SSD 840 EVO 250GB              | 10        | 0.56%   |
| Kingston SA400S37480G 480GB SSD        | 10        | 0.56%   |
| Toshiba MQ01ABF050 500GB               | 9         | 0.5%    |
| Seagate ST3500418AS 500GB              | 9         | 0.5%    |
| Samsung SSD 860 EVO 250GB              | 9         | 0.5%    |
| Seagate ST9500325AS 500GB              | 8         | 0.45%   |
| Seagate ST3500413AS 500GB              | 8         | 0.45%   |
| Seagate Expansion+ 2TB                 | 8         | 0.45%   |
| Sandisk NVMe SSD Drive 1TB             | 8         | 0.45%   |
| Samsung SSD 860 EVO 1TB                | 8         | 0.45%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 7         | 0.39%   |
| Toshiba HDWD110 1TB                    | 7         | 0.39%   |
| Toshiba DT01ACA100 1TB                 | 7         | 0.39%   |
| Seagate ST1000DM003-1CH162 1TB         | 7         | 0.39%   |
| SanDisk SSD PLUS 240GB                 | 7         | 0.39%   |
| Samsung SSD 870 QVO 1TB                | 7         | 0.39%   |
| Kingston SV300S37A120G 120GB SSD       | 7         | 0.39%   |
| Intel NVMe SSD Drive 512GB             | 7         | 0.39%   |
| Crucial CT480BX500SSD1 480GB           | 7         | 0.39%   |
| Toshiba DT01ACA050 500GB               | 6         | 0.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 6         | 0.33%   |
| Seagate ST3500312CS 500GB              | 6         | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB         | 6         | 0.33%   |
| Seagate ST2000DM001-1CH164 2TB         | 6         | 0.33%   |
| Seagate ST1000LM049-2GH172 1TB         | 6         | 0.33%   |
| Samsung SSD 870 EVO 1TB                | 6         | 0.33%   |
| Intel NVMe SSD Drive 1024GB            | 6         | 0.33%   |
| HGST HTS721010A9E630 1TB               | 6         | 0.33%   |
| Crucial CT1000MX500SSD1 1TB            | 6         | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 5         | 0.28%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 5         | 0.28%   |
| SK Hynix NVMe SSD Drive 512GB          | 5         | 0.28%   |
| SK Hynix NVMe SSD Drive 256GB          | 5         | 0.28%   |
| Seagate ST9500420AS 500GB              | 5         | 0.28%   |
| Seagate ST2000DM001-9YN164 2TB         | 5         | 0.28%   |
| Seagate ST1000DM003-1ER162 1TB         | 5         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 263       | 360    | 37.52%  |
| WDC                 | 188       | 230    | 26.82%  |
| Toshiba             | 94        | 105    | 13.41%  |
| Hitachi             | 66        | 91     | 9.42%   |
| HGST                | 26        | 33     | 3.71%   |
| Samsung Electronics | 24        | 32     | 3.42%   |
| Unknown             | 11        | 13     | 1.57%   |
| Apple               | 8         | 8      | 1.14%   |
| MAXTOR              | 6         | 7      | 0.86%   |
| Fujitsu             | 5         | 6      | 0.71%   |
| SABRENT             | 4         | 5      | 0.57%   |
| Hewlett-Packard     | 3         | 5      | 0.43%   |
| KESU                | 1         | 1      | 0.14%   |
| Intenso             | 1         | 1      | 0.14%   |
| ASMT                | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 142       | 180    | 24.7%   |
| Kingston            | 76        | 96     | 13.22%  |
| SanDisk             | 66        | 79     | 11.48%  |
| Crucial             | 54        | 66     | 9.39%   |
| WDC                 | 26        | 33     | 4.52%   |
| A-DATA Technology   | 22        | 24     | 3.83%   |
| Toshiba             | 15        | 15     | 2.61%   |
| China               | 13        | 14     | 2.26%   |
| Micron Technology   | 12        | 13     | 2.09%   |
| SK Hynix            | 11        | 11     | 1.91%   |
| Intel               | 9         | 9      | 1.57%   |
| PNY                 | 8         | 10     | 1.39%   |
| Intenso             | 8         | 8      | 1.39%   |
| Transcend           | 7         | 22     | 1.22%   |
| SPCC                | 7         | 10     | 1.22%   |
| OCZ                 | 6         | 6      | 1.04%   |
| Lexar               | 6         | 6      | 1.04%   |
| Hewlett-Packard     | 6         | 7      | 1.04%   |
| GOODRAM             | 6         | 6      | 1.04%   |
| Apple               | 6         | 6      | 1.04%   |
| Patriot             | 5         | 5      | 0.87%   |
| Netac               | 5         | 5      | 0.87%   |
| KingSpec            | 5         | 6      | 0.87%   |
| Super Talent        | 4         | 5      | 0.7%    |
| LITEONIT            | 4         | 5      | 0.7%    |
| Gigabyte Technology | 4         | 4      | 0.7%    |
| Team                | 3         | 4      | 0.52%   |
| OWC                 | 3         | 3      | 0.52%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.52%   |
| Verbatim            | 2         | 2      | 0.35%   |
| Teclast             | 2         | 2      | 0.35%   |
| Seagate             | 2         | 2      | 0.35%   |
| LITEON              | 2         | 2      | 0.35%   |
| Corsair             | 2         | 2      | 0.35%   |
| BHT                 | 2         | 2      | 0.35%   |
| Apacer              | 2         | 2      | 0.35%   |
| USB30               | 1         | 4      | 0.17%   |
| TO Exter            | 1         | 1      | 0.17%   |
| SuperSSpeed         | 1         | 2      | 0.17%   |
| Star                | 1         | 1      | 0.17%   |
| Smartbuy            | 1         | 1      | 0.17%   |
| PLEXTOR             | 1         | 1      | 0.17%   |
| PHISON              | 1         | 1      | 0.17%   |
| OSCOO               | 1         | 1      | 0.17%   |
| ORTIAL              | 1         | 1      | 0.17%   |
| OCZ-VERTEX          | 1         | 1      | 0.17%   |
| MyDigitalSSD        | 1         | 1      | 0.17%   |
| Mushkin             | 1         | 1      | 0.17%   |
| MidasForce          | 1         | 1      | 0.17%   |
| INNOVATION IT       | 1         | 1      | 0.17%   |
| HS-SSD-E100         | 1         | 1      | 0.17%   |
| GALAX               | 1         | 1      | 0.17%   |
| FORESEE             | 1         | 1      | 0.17%   |
| Dogfish             | 1         | 2      | 0.17%   |
| BUFFALO             | 1         | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 587       | 898    | 40.57%  |
| SSD     | 507       | 700    | 35.04%  |
| NVMe    | 253       | 338    | 17.48%  |
| MMC     | 71        | 88     | 4.91%   |
| Unknown | 29        | 38     | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 931       | 1552   | 70.85%  |
| NVMe | 251       | 334    | 19.1%   |
| MMC  | 71        | 88     | 5.4%    |
| SAS  | 61        | 88     | 4.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 692       | 957    | 60.02%  |
| 0.51-1.0   | 329       | 443    | 28.53%  |
| 1.01-2.0   | 82        | 110    | 7.11%   |
| 3.01-4.0   | 22        | 35     | 1.91%   |
| 4.01-10.0  | 15        | 23     | 1.3%    |
| 2.01-3.0   | 13        | 30     | 1.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 369       | 31.95%  |
| 251-500        | 285       | 24.68%  |
| 501-1000       | 176       | 15.24%  |
| 51-100         | 102       | 8.83%   |
| 1001-2000      | 60        | 5.19%   |
| 21-50          | 51        | 4.42%   |
| More than 3000 | 47        | 4.07%   |
| 2001-3000      | 24        | 2.08%   |
| 1-20           | 24        | 2.08%   |
| Unknown        | 17        | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 507       | 42.71%  |
| 21-50          | 304       | 25.61%  |
| 51-100         | 124       | 10.45%  |
| 101-250        | 100       | 8.42%   |
| 251-500        | 48        | 4.04%   |
| 501-1000       | 38        | 3.2%    |
| More than 3000 | 24        | 2.02%   |
| 1001-2000      | 21        | 1.77%   |
| Unknown        | 17        | 1.43%   |
| 2001-3000      | 4         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB            | 2         | 2      | 8.7%    |
| Seagate ST9500420AS 500GB          | 2         | 2      | 8.7%    |
| WDC WD3200AAKS-22B3A0 320GB        | 1         | 1      | 4.35%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 1      | 4.35%   |
| WDC WD10SPZX-75Z10T2 1TB           | 1         | 1      | 4.35%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 4.35%   |
| WDC WD10EZEX-21M2NA0 1TB           | 1         | 2      | 4.35%   |
| Toshiba MK3265GSX 320GB            | 1         | 1      | 4.35%   |
| Seagate ST9200420ASG 200GB         | 1         | 1      | 4.35%   |
| Seagate ST4000DM004-2CV104 4TB     | 1         | 1      | 4.35%   |
| Seagate ST3500514NS 500GB          | 1         | 1      | 4.35%   |
| Seagate ST3320620AS 320GB          | 1         | 1      | 4.35%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 4.35%   |
| Seagate ST2000DM001-9YN164 2TB     | 1         | 1      | 4.35%   |
| Seagate ST2000DL003-9VT166 2TB     | 1         | 1      | 4.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 4.35%   |
| Hitachi HTS725032A9A364 320GB      | 1         | 1      | 4.35%   |
| HGST HTS725050A7E630 500GB         | 1         | 1      | 4.35%   |
| HGST HTS545050A7E680 500GB         | 1         | 1      | 4.35%   |
| Hewlett-Packard SSD S600 240GB     | 1         | 1      | 4.35%   |
| A-DATA Technology SX8200PNP 256GB  | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 9         | 10     | 40.91%  |
| WDC               | 5         | 6      | 22.73%  |
| Toshiba           | 3         | 3      | 13.64%  |
| HGST              | 2         | 2      | 9.09%   |
| Hitachi           | 1         | 1      | 4.55%   |
| Hewlett-Packard   | 1         | 1      | 4.55%   |
| A-DATA Technology | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 10     | 45%     |
| WDC     | 5         | 6      | 25%     |
| Toshiba | 3         | 3      | 15%     |
| HGST    | 2         | 2      | 10%     |
| Hitachi | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 22     | 90.48%  |
| NVMe | 1         | 1      | 4.76%   |
| SSD  | 1         | 1      | 4.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                 | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1028      | 1865   | 88.32%  |
| Works    | 114       | 172    | 9.79%   |
| Malfunc  | 21        | 24     | 1.8%    |
| Failed   | 1         | 1      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 803       | 60.06%  |
| AMD                              | 212       | 15.86%  |
| Samsung Electronics              | 94        | 7.03%   |
| Sandisk                          | 46        | 3.44%   |
| ASMedia Technology               | 22        | 1.65%   |
| Phison Electronics               | 18        | 1.35%   |
| SK Hynix                         | 16        | 1.2%    |
| Nvidia                           | 13        | 0.97%   |
| Silicon Motion                   | 12        | 0.9%    |
| Marvell Technology Group         | 12        | 0.9%    |
| Kingston Technology Company      | 12        | 0.9%    |
| Toshiba America Info Systems     | 10        | 0.75%   |
| KIOXIA                           | 9         | 0.67%   |
| JMicron Technology               | 8         | 0.6%    |
| Micron Technology                | 7         | 0.52%   |
| ADATA Technology                 | 7         | 0.52%   |
| Realtek Semiconductor            | 6         | 0.45%   |
| VIA Technologies                 | 5         | 0.37%   |
| Micron/Crucial Technology        | 5         | 0.37%   |
| Silicon Image                    | 3         | 0.22%   |
| Lite-On Technology               | 3         | 0.22%   |
| Broadcom / LSI                   | 3         | 0.22%   |
| Seagate Technology               | 2         | 0.15%   |
| LSI Logic / Symbios Logic        | 2         | 0.15%   |
| Yangtze Memory Technologies      | 1         | 0.07%   |
| Union Memory (Shenzhen)          | 1         | 0.07%   |
| Solid State Storage Technology   | 1         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| Dell                             | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |
| Adaptec                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 136       | 8.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 63        | 4.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 59        | 3.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 59        | 3.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 47        | 3.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 45        | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 45        | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 37        | 2.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 36        | 2.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 34        | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 34        | 2.19%   |
| AMD 400 Series Chipset SATA Controller                                                  | 32        | 2.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26        | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 24        | 1.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 24        | 1.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 24        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 24        | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 23        | 1.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 22        | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 22        | 1.41%   |
| Intel SATA Controller [RAID mode]                                                       | 21        | 1.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 21        | 1.35%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 20        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 19        | 1.22%   |
| Samsung NVMe SSD Controller 980                                                         | 18        | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 18        | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15        | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 14        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 14        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 14        | 0.9%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 13        | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 13        | 0.84%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 12        | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 12        | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 12        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 12        | 0.77%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12        | 0.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 11        | 0.71%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 11        | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 11        | 0.71%   |
| Intel SSD 660P Series                                                                   | 10        | 0.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 10        | 0.64%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 9         | 0.58%   |
| Phison E12 NVMe Controller                                                              | 9         | 0.58%   |
| KIOXIA Non-Volatile memory controller                                                   | 9         | 0.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 9         | 0.58%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9         | 0.58%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9         | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 8         | 0.51%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 8         | 0.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8         | 0.51%   |
| AMD FCH IDE Controller                                                                  | 8         | 0.51%   |
| Sandisk Non-Volatile memory controller                                                  | 7         | 0.45%   |
| Micron Non-Volatile memory controller                                                   | 7         | 0.45%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 7         | 0.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 0.45%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 7         | 0.45%   |
| AMD FCH SATA Controller D                                                               | 7         | 0.45%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 858       | 62.04%  |
| NVMe | 251       | 18.15%  |
| IDE  | 166       | 12%     |
| RAID | 104       | 7.52%   |
| SAS  | 2         | 0.14%   |
| SCSI | 2         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 893       | 78.82%  |
| AMD    | 240       | 21.18%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 17        | 1.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 1.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.15%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 13        | 1.15%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 12        | 1.06%   |
| AMD Ryzen 5 3600 6-Core Processor             | 11        | 0.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 0.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 0.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.71%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 8         | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 0.71%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.71%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 8         | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.62%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.62%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 0.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 7         | 0.62%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.62%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 0.62%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 7         | 0.62%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 6         | 0.53%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 6         | 0.53%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 6         | 0.53%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 6         | 0.53%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 5         | 0.44%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 5         | 0.44%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.44%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 0.44%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 0.44%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 0.44%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.44%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 5         | 0.44%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 5         | 0.44%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 5         | 0.44%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 5         | 0.44%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 5         | 0.44%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 5         | 0.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 5         | 0.44%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.44%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 5         | 0.44%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 5         | 0.44%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 4         | 0.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.35%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 4         | 0.35%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 0.35%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.35%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 0.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.35%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 4         | 0.35%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 4         | 0.35%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 4         | 0.35%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 0.35%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 4         | 0.35%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 0.35%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 4         | 0.35%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 4         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 282       | 24.89%  |
| Intel Core i7                        | 176       | 15.53%  |
| Intel Core i3                        | 117       | 10.33%  |
| Intel Celeron                        | 63        | 5.56%   |
| Intel Core 2 Duo                     | 58        | 5.12%   |
| AMD Ryzen 5                          | 57        | 5.03%   |
| Other                                | 44        | 3.88%   |
| Intel Pentium                        | 38        | 3.35%   |
| AMD Ryzen 7                          | 32        | 2.82%   |
| Intel Atom                           | 31        | 2.74%   |
| AMD FX                               | 25        | 2.21%   |
| Intel Xeon                           | 23        | 2.03%   |
| AMD A6                               | 18        | 1.59%   |
| Intel Core 2 Quad                    | 14        | 1.24%   |
| AMD Ryzen 3                          | 14        | 1.24%   |
| Intel Pentium Dual-Core              | 12        | 1.06%   |
| AMD A10                              | 12        | 1.06%   |
| Intel Pentium Dual                   | 11        | 0.97%   |
| AMD A8                               | 8         | 0.71%   |
| AMD Ryzen 9                          | 7         | 0.62%   |
| AMD E1                               | 7         | 0.62%   |
| AMD Athlon II X2                     | 6         | 0.53%   |
| AMD Phenom II X4                     | 5         | 0.44%   |
| AMD E                                | 5         | 0.44%   |
| Intel Pentium Gold                   | 4         | 0.35%   |
| Intel Core m5                        | 4         | 0.35%   |
| AMD A4                               | 4         | 0.35%   |
| Intel Pentium Silver                 | 3         | 0.26%   |
| Intel Pentium 4                      | 3         | 0.26%   |
| Intel Core i9                        | 3         | 0.26%   |
| Intel Core 2                         | 3         | 0.26%   |
| AMD Athlon II X4                     | 3         | 0.26%   |
| AMD Athlon II X3                     | 3         | 0.26%   |
| AMD Athlon                           | 3         | 0.26%   |
| Intel Core m3                        | 2         | 0.18%   |
| Intel Core M                         | 2         | 0.18%   |
| Intel Celeron Dual-Core              | 2         | 0.18%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.18%   |
| AMD Phenom II X6                     | 2         | 0.18%   |
| AMD GX                               | 2         | 0.18%   |
| AMD E2                               | 2         | 0.18%   |
| AMD Athlon X4                        | 2         | 0.18%   |
| AMD Athlon 64 X2                     | 2         | 0.18%   |
| AMD Athlon 64                        | 2         | 0.18%   |
| Intel Pentium D                      | 1         | 0.09%   |
| Intel Genuine                        | 1         | 0.09%   |
| Intel Celeron M                      | 1         | 0.09%   |
| AMD Turion II                        | 1         | 0.09%   |
| AMD Turion 64 X2 Mobile              | 1         | 0.09%   |
| AMD Turion 64 Mobile                 | 1         | 0.09%   |
| AMD Sempron                          | 1         | 0.09%   |
| AMD Ryzen 7 PRO                      | 1         | 0.09%   |
| AMD Ryzen 5 PRO                      | 1         | 0.09%   |
| AMD Phenom II                        | 1         | 0.09%   |
| AMD Phenom                           | 1         | 0.09%   |
| AMD Opteron                          | 1         | 0.09%   |
| AMD C-60                             | 1         | 0.09%   |
| AMD Athlon X2                        | 1         | 0.09%   |
| AMD Athlon II                        | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 530       | 46.78%  |
| 4      | 434       | 38.31%  |
| 6      | 82        | 7.24%   |
| 8      | 47        | 4.15%   |
| 1      | 16        | 1.41%   |
| 3      | 11        | 0.97%   |
| 12     | 7         | 0.62%   |
| 10     | 4         | 0.35%   |
| 16     | 2         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1128      | 99.56%  |
| 2      | 5         | 0.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 690       | 60.9%   |
| 1      | 443       | 39.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1133      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 104       | 9.08%   |
| 0x306a9    | 93        | 8.12%   |
| Unknown    | 73        | 6.37%   |
| 0x306c3    | 71        | 6.2%    |
| 0x1067a    | 52        | 4.54%   |
| 0x40651    | 39        | 3.4%    |
| 0x406e3    | 30        | 2.62%   |
| 0x806ea    | 27        | 2.36%   |
| 0x806c1    | 27        | 2.36%   |
| 0x506e3    | 27        | 2.36%   |
| 0x406c4    | 26        | 2.27%   |
| 0x806e9    | 25        | 2.18%   |
| 0x20655    | 25        | 2.18%   |
| 0x306d4    | 24        | 2.09%   |
| 0x806ec    | 23        | 2.01%   |
| 0x906ea    | 22        | 1.92%   |
| 0x08701021 | 21        | 1.83%   |
| 0x906e9    | 20        | 1.75%   |
| 0x30678    | 19        | 1.66%   |
| 0x6fd      | 17        | 1.48%   |
| 0x06000852 | 17        | 1.48%   |
| 0x6fb      | 15        | 1.31%   |
| 0x10676    | 15        | 1.31%   |
| 0x20652    | 13        | 1.13%   |
| 0x506c9    | 12        | 1.05%   |
| 0x08108109 | 12        | 1.05%   |
| 0x08108102 | 12        | 1.05%   |
| 0x706e5    | 11        | 0.96%   |
| 0x08600106 | 11        | 0.96%   |
| 0x07030105 | 11        | 0.96%   |
| 0x0800820d | 10        | 0.87%   |
| 0x06001119 | 10        | 0.87%   |
| 0x706a8    | 9         | 0.79%   |
| 0x406c3    | 9         | 0.79%   |
| 0xa0655    | 8         | 0.7%    |
| 0x010000c8 | 8         | 0.7%    |
| 0x0700010f | 7         | 0.61%   |
| 0x0600063e | 7         | 0.61%   |
| 0xa0671    | 6         | 0.52%   |
| 0xa0652    | 6         | 0.52%   |
| 0x906eb    | 6         | 0.52%   |
| 0x706a1    | 6         | 0.52%   |
| 0x106e5    | 6         | 0.52%   |
| 0x0a201016 | 6         | 0.52%   |
| 0x08701013 | 6         | 0.52%   |
| 0x06006705 | 6         | 0.52%   |
| 0x05000119 | 6         | 0.52%   |
| 0xa0653    | 5         | 0.44%   |
| 0x806eb    | 5         | 0.44%   |
| 0x6f6      | 5         | 0.44%   |
| 0x07030106 | 5         | 0.44%   |
| 0x06003106 | 5         | 0.44%   |
| 0x206c2    | 4         | 0.35%   |
| 0x08608103 | 4         | 0.35%   |
| 0x08101016 | 4         | 0.35%   |
| 0x06006704 | 4         | 0.35%   |
| 0x0600611a | 4         | 0.35%   |
| 0x03000027 | 4         | 0.35%   |
| 0x010000dc | 4         | 0.35%   |
| 0x010000db | 4         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 148       | 13.06%  |
| Haswell          | 121       | 10.68%  |
| SandyBridge      | 111       | 9.8%    |
| IvyBridge        | 97        | 8.56%   |
| Penryn           | 69        | 6.09%   |
| Skylake          | 60        | 5.3%    |
| Silvermont       | 57        | 5.03%   |
| Zen 2            | 44        | 3.88%   |
| Westmere         | 43        | 3.8%    |
| Core             | 41        | 3.62%   |
| Zen+             | 36        | 3.18%   |
| TigerLake        | 30        | 2.65%   |
| Piledriver       | 28        | 2.47%   |
| Broadwell        | 25        | 2.21%   |
| K10              | 23        | 2.03%   |
| Icelake          | 22        | 1.94%   |
| CometLake        | 20        | 1.77%   |
| Puma             | 18        | 1.59%   |
| Excavator        | 16        | 1.41%   |
| Zen 3            | 15        | 1.32%   |
| Goldmont plus    | 15        | 1.32%   |
| Zen              | 13        | 1.15%   |
| Goldmont         | 13        | 1.15%   |
| Nehalem          | 9         | 0.79%   |
| Jaguar           | 9         | 0.79%   |
| Bulldozer        | 7         | 0.62%   |
| Bobcat           | 7         | 0.62%   |
| K8 Hammer        | 6         | 0.53%   |
| Unknown          | 6         | 0.53%   |
| Steamroller      | 5         | 0.44%   |
| Bonnell          | 5         | 0.44%   |
| NetBurst         | 4         | 0.35%   |
| K8 & K10 hybrid  | 4         | 0.35%   |
| K10 Llano        | 4         | 0.35%   |
| Tremont          | 1         | 0.09%   |
| Alderlake Hybrid | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 688       | 52.8%   |
| Nvidia                           | 330       | 25.33%  |
| AMD                              | 280       | 21.49%  |
| Matrox Electronics Systems       | 2         | 0.15%   |
| VIA Technologies                 | 1         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |
| ASPEED Technology                | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 83        | 6.21%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 59        | 4.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 41        | 3.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 2.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 33        | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 29        | 2.17%   |
| Intel UHD Graphics 620                                                                   | 27        | 2.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 1.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 1.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 23        | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 1.57%   |
| Intel HD Graphics 620                                                                    | 18        | 1.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 1.27%   |
| Intel HD Graphics 630                                                                    | 17        | 1.27%   |
| Intel HD Graphics 5500                                                                   | 17        | 1.27%   |
| AMD Renoir                                                                               | 17        | 1.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 17        | 1.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 1.2%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 15        | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 0.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 0.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 0.9%    |
| Intel HD Graphics 530                                                                    | 12        | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 0.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 11        | 0.82%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 11        | 0.82%   |
| Intel HD Graphics 500                                                                    | 10        | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 9         | 0.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 9         | 0.67%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 8         | 0.6%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 8         | 0.6%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 8         | 0.6%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 0.6%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.52%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 7         | 0.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.52%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 7         | 0.52%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 0.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6         | 0.45%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 6         | 0.45%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 6         | 0.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 0.45%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 6         | 0.45%   |
| AMD RS780L [Radeon 3000]                                                                 | 6         | 0.45%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6         | 0.45%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.37%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.37%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 5         | 0.37%   |
| Intel Tiger Lake UHD Graphics                                                            | 5         | 0.37%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.37%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 0.37%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.37%   |
| AMD Lucienne                                                                             | 5         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 537       | 47.27%  |
| 1 x AMD        | 224       | 19.72%  |
| 1 x Nvidia     | 203       | 17.87%  |
| Intel + Nvidia | 110       | 9.68%   |
| Intel + AMD    | 25        | 2.2%    |
| 2 x AMD        | 17        | 1.5%    |
| AMD + Nvidia   | 13        | 1.14%   |
| 1 x Matrox     | 2         | 0.18%   |
| 2 x Nvidia     | 1         | 0.09%   |
| 2 x Intel      | 1         | 0.09%   |
| 1 x VIA        | 1         | 0.09%   |
| 1 x SiS        | 1         | 0.09%   |
| 1 x ASPEED     | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 897       | 79.17%  |
| Proprietary | 205       | 18.09%  |
| Unknown     | 31        | 2.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 637       | 55.63%  |
| 1.01-2.0   | 132       | 11.53%  |
| 0.01-0.5   | 127       | 11.09%  |
| 0.51-1.0   | 110       | 9.61%   |
| 3.01-4.0   | 58        | 5.07%   |
| 7.01-8.0   | 34        | 2.97%   |
| 5.01-6.0   | 28        | 2.45%   |
| 2.01-3.0   | 9         | 0.79%   |
| 8.01-16.0  | 8         | 0.7%    |
| 16.01-24.0 | 2         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 162       | 13.87%  |
| AU Optronics            | 137       | 11.73%  |
| Chimei Innolux          | 110       | 9.42%   |
| LG Display              | 99        | 8.48%   |
| BOE                     | 84        | 7.19%   |
| Dell                    | 56        | 4.79%   |
| Goldstar                | 53        | 4.54%   |
| Hewlett-Packard         | 42        | 3.6%    |
| Acer                    | 34        | 2.91%   |
| AOC                     | 32        | 2.74%   |
| Apple                   | 30        | 2.57%   |
| Philips                 | 25        | 2.14%   |
| Chi Mei Optoelectronics | 25        | 2.14%   |
| BenQ                    | 22        | 1.88%   |
| Sharp                   | 20        | 1.71%   |
| Lenovo                  | 18        | 1.54%   |
| Ancor Communications    | 18        | 1.54%   |
| LG Electronics          | 15        | 1.28%   |
| PANDA                   | 12        | 1.03%   |
| Vizio                   | 11        | 0.94%   |
| Iiyama                  | 9         | 0.77%   |
| ViewSonic               | 8         | 0.68%   |
| Sony                    | 8         | 0.68%   |
| Sceptre Tech            | 8         | 0.68%   |
| LG Philips              | 8         | 0.68%   |
| Unknown                 | 8         | 0.68%   |
| Unknown                 | 6         | 0.51%   |
| InfoVision              | 6         | 0.51%   |
| HPN                     | 6         | 0.51%   |
| LGD                     | 5         | 0.43%   |
| Fujitsu Siemens         | 5         | 0.43%   |
| Panasonic               | 4         | 0.34%   |
| NEC Computers           | 4         | 0.34%   |
| HannStar                | 4         | 0.34%   |
| Vestel                  | 3         | 0.26%   |
| Toshiba                 | 3         | 0.26%   |
| Microstep               | 3         | 0.26%   |
| Medion                  | 3         | 0.26%   |
| CPT                     | 3         | 0.26%   |
| AUS                     | 3         | 0.26%   |
| ASUSTek Computer        | 3         | 0.26%   |
| Sanyo                   | 2         | 0.17%   |
| Quanta Display          | 2         | 0.17%   |
| OEM                     | 2         | 0.17%   |
| MStar                   | 2         | 0.17%   |
| Lenovo Group Limited    | 2         | 0.17%   |
| KDC                     | 2         | 0.17%   |
| Gateway                 | 2         | 0.17%   |
| FUS                     | 2         | 0.17%   |
| Eizo                    | 2         | 0.17%   |
| BOE Technology Group    | 2         | 0.17%   |
| Belinea                 | 2         | 0.17%   |
| Xiaomi                  | 1         | 0.09%   |
| Westinghouse            | 1         | 0.09%   |
| WAN                     | 1         | 0.09%   |
| Viotek                  | 1         | 0.09%   |
| VIE                     | 1         | 0.09%   |
| Vestel Elektronik       | 1         | 0.09%   |
| Unknown (AAA)           | 1         | 0.09%   |
| SLD                     | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 8         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 7         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 0.58%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 7         | 0.58%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.5%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.42%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 0.42%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 5         | 0.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.42%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 5         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch          | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 4         | 0.33%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                                | 3         | 0.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 3         | 0.25%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 3         | 0.25%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.25%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch    | 3         | 0.25%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 3         | 0.25%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 3         | 0.25%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.25%   |
| Goldstar W1942 GSM4B6F 1440x900 410x260mm 19.1-inch                      | 3         | 0.25%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 3         | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 350x190mm 15.7-inch | 3         | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1590 1366x768 344x194mm 15.5-inch | 3         | 0.25%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 3         | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.25%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 0.25%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                    | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch           | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 3         | 0.25%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch                | 2         | 0.17%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                      | 2         | 0.17%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 2         | 0.17%   |
| Sceptre Tech E24 SPT099D 1920x1080 409x230mm 18.5-inch                   | 2         | 0.17%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch        | 2         | 0.17%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch        | 2         | 0.17%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch     | 2         | 0.17%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.17%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch     | 2         | 0.17%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch     | 2         | 0.17%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 2         | 0.17%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 2         | 0.17%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch    | 2         | 0.17%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 2         | 0.17%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 2         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 434       | 37.87%  |
| 1366x768 (WXGA)    | 292       | 25.48%  |
| 1600x900 (HD+)     | 66        | 5.76%   |
| 3840x2160 (4K)     | 62        | 5.41%   |
| 1680x1050 (WSXGA+) | 33        | 2.88%   |
| 1280x800 (WXGA)    | 33        | 2.88%   |
| 1280x1024 (SXGA)   | 29        | 2.53%   |
| Unknown            | 29        | 2.53%   |
| 1440x900 (WXGA+)   | 25        | 2.18%   |
| 2560x1440 (QHD)    | 23        | 2.01%   |
| 1920x1200 (WUXGA)  | 14        | 1.22%   |
| 3840x1080          | 13        | 1.13%   |
| 1360x768           | 13        | 1.13%   |
| 3440x1440          | 9         | 0.79%   |
| 2560x1600          | 7         | 0.61%   |
| 3200x1800 (QHD+)   | 5         | 0.44%   |
| 2736x1824          | 4         | 0.35%   |
| 2256x1504          | 4         | 0.35%   |
| 1920x540           | 4         | 0.35%   |
| 3840x2400          | 3         | 0.26%   |
| 2880x1800          | 3         | 0.26%   |
| 2560x1080          | 3         | 0.26%   |
| 2160x1440          | 3         | 0.26%   |
| 1024x600           | 3         | 0.26%   |
| 5760x2160          | 2         | 0.17%   |
| 5760x1080          | 2         | 0.17%   |
| 3600x1080          | 2         | 0.17%   |
| 3360x1080          | 2         | 0.17%   |
| 1920x515           | 2         | 0.17%   |
| 1920x1280          | 2         | 0.17%   |
| 1600x1200          | 2         | 0.17%   |
| 1024x768 (XGA)     | 2         | 0.17%   |
| 6400x1440          | 1         | 0.09%   |
| 4480x1600          | 1         | 0.09%   |
| 4480x1440          | 1         | 0.09%   |
| 4160x1440          | 1         | 0.09%   |
| 3840x1600          | 1         | 0.09%   |
| 3840x1200          | 1         | 0.09%   |
| 3780x2160          | 1         | 0.09%   |
| 3360x1050          | 1         | 0.09%   |
| 3200x1200          | 1         | 0.09%   |
| 3120x1050          | 1         | 0.09%   |
| 2944x1080          | 1         | 0.09%   |
| 2496x1664          | 1         | 0.09%   |
| 2464x900           | 1         | 0.09%   |
| 1834x1031          | 1         | 0.09%   |
| 1680x945           | 1         | 0.09%   |
| 1280x720 (HD)      | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 295       | 25.61%  |
| 13      | 117       | 10.16%  |
| Unknown | 117       | 10.16%  |
| 14      | 81        | 7.03%   |
| 17      | 73        | 6.34%   |
| 27      | 63        | 5.47%   |
| 24      | 55        | 4.77%   |
| 23      | 51        | 4.43%   |
| 21      | 49        | 4.25%   |
| 19      | 31        | 2.69%   |
| 18      | 27        | 2.34%   |
| 12      | 26        | 2.26%   |
| 31      | 25        | 2.17%   |
| 22      | 22        | 1.91%   |
| 20      | 22        | 1.91%   |
| 11      | 18        | 1.56%   |
| 34      | 9         | 0.78%   |
| 84      | 7         | 0.61%   |
| 26      | 6         | 0.52%   |
| 54      | 5         | 0.43%   |
| 32      | 5         | 0.43%   |
| 10      | 5         | 0.43%   |
| 72      | 4         | 0.35%   |
| 40      | 4         | 0.35%   |
| 25      | 4         | 0.35%   |
| 48      | 3         | 0.26%   |
| 16      | 3         | 0.26%   |
| 74      | 2         | 0.17%   |
| 64      | 2         | 0.17%   |
| 52      | 2         | 0.17%   |
| 49      | 2         | 0.17%   |
| 41      | 2         | 0.17%   |
| 37      | 2         | 0.17%   |
| 35      | 2         | 0.17%   |
| 33      | 2         | 0.17%   |
| 28      | 2         | 0.17%   |
| 55      | 1         | 0.09%   |
| 50      | 1         | 0.09%   |
| 47      | 1         | 0.09%   |
| 46      | 1         | 0.09%   |
| 43      | 1         | 0.09%   |
| 42      | 1         | 0.09%   |
| 36      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 436       | 38.35%  |
| 501-600     | 159       | 13.98%  |
| 401-500     | 134       | 11.79%  |
| Unknown     | 117       | 10.29%  |
| 201-300     | 108       | 9.5%    |
| 351-400     | 86        | 7.56%   |
| 601-700     | 37        | 3.25%   |
| 1001-1500   | 18        | 1.58%   |
| 701-800     | 17        | 1.5%    |
| 1501-2000   | 13        | 1.14%   |
| 801-900     | 8         | 0.7%    |
| 901-1000    | 4         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 784       | 73.27%  |
| 16/10   | 115       | 10.75%  |
| Unknown | 107       | 10%     |
| 5/4     | 25        | 2.34%   |
| 3/2     | 16        | 1.5%    |
| 21/9    | 13        | 1.21%   |
| 4/3     | 6         | 0.56%   |
| 3.73    | 2         | 0.19%   |
| 6/5     | 1         | 0.09%   |
| 32/9    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 296       | 25.78%  |
| 81-90          | 152       | 13.24%  |
| 201-250        | 147       | 12.8%   |
| Unknown        | 117       | 10.19%  |
| 151-200        | 70        | 6.1%    |
| 301-350        | 64        | 5.57%   |
| 121-130        | 52        | 4.53%   |
| 71-80          | 49        | 4.27%   |
| 351-500        | 44        | 3.83%   |
| 141-150        | 35        | 3.05%   |
| More than 1000 | 28        | 2.44%   |
| 251-300        | 24        | 2.09%   |
| 61-70          | 22        | 1.92%   |
| 51-60          | 19        | 1.66%   |
| 501-1000       | 14        | 1.22%   |
| 131-140        | 7         | 0.61%   |
| 41-50          | 4         | 0.35%   |
| 111-120        | 2         | 0.17%   |
| 91-100         | 2         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 350       | 31.19%  |
| 51-100        | 317       | 28.25%  |
| 121-160       | 236       | 21.03%  |
| Unknown       | 117       | 10.43%  |
| 161-240       | 55        | 4.9%    |
| 1-50          | 31        | 2.76%   |
| More than 240 | 16        | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 964       | 84.41%  |
| 2     | 142       | 12.43%  |
| 0     | 30        | 2.63%   |
| 3     | 5         | 0.44%   |
| 4     | 1         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 610       | 35.04%  |
| Intel                             | 491       | 28.2%   |
| Qualcomm Atheros                  | 234       | 13.44%  |
| Broadcom                          | 120       | 6.89%   |
| Broadcom Limited                  | 33        | 1.9%    |
| Ralink Technology                 | 32        | 1.84%   |
| Ralink                            | 24        | 1.38%   |
| TP-Link                           | 22        | 1.26%   |
| Marvell Technology Group          | 18        | 1.03%   |
| ASIX Electronics                  | 15        | 0.86%   |
| Samsung Electronics               | 11        | 0.63%   |
| Nvidia                            | 10        | 0.57%   |
| DisplayLink                       | 10        | 0.57%   |
| Xiaomi                            | 9         | 0.52%   |
| Dell                              | 9         | 0.52%   |
| MEDIATEK                          | 8         | 0.46%   |
| NetGear                           | 6         | 0.34%   |
| Huawei Technologies               | 6         | 0.34%   |
| Edimax Technology                 | 6         | 0.34%   |
| D-Link System                     | 6         | 0.34%   |
| Qualcomm Atheros Communications   | 5         | 0.29%   |
| Motorola PCS                      | 4         | 0.23%   |
| Microsoft                         | 4         | 0.23%   |
| Hewlett-Packard                   | 4         | 0.23%   |
| T & A Mobile Phones               | 3         | 0.17%   |
| Sierra Wireless                   | 3         | 0.17%   |
| JMicron Technology                | 3         | 0.17%   |
| Qualcomm                          | 2         | 0.11%   |
| OPPO Electronics                  | 2         | 0.11%   |
| Linksys                           | 2         | 0.11%   |
| Lenovo                            | 2         | 0.11%   |
| Google                            | 2         | 0.11%   |
| Exar                              | 2         | 0.11%   |
| Ericsson Business Mobile Networks | 2         | 0.11%   |
| D-Link                            | 2         | 0.11%   |
| ZyXEL Communications              | 1         | 0.06%   |
| ZyDAS                             | 1         | 0.06%   |
| Sun Microsystems                  | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.06%   |
| Research In Motion                | 1         | 0.06%   |
| Panasonic (Matsushita)            | 1         | 0.06%   |
| Padix (Rockfire)                  | 1         | 0.06%   |
| OnePlus                           | 1         | 0.06%   |
| Novatel Wireless                  | 1         | 0.06%   |
| Motorola BCS                      | 1         | 0.06%   |
| Mellanox Technologies             | 1         | 0.06%   |
| ICS Advent                        | 1         | 0.06%   |
| Gemtek                            | 1         | 0.06%   |
| Fibocom                           | 1         | 0.06%   |
| DJI Technology                    | 1         | 0.06%   |
| Belkin Components                 | 1         | 0.06%   |
| ASUSTek Computer                  | 1         | 0.06%   |
| Arduino SA                        | 1         | 0.06%   |
| ADMtek                            | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 417       | 20.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 90        | 4.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 62        | 3.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 49        | 2.41%   |
| Intel Wi-Fi 6 AX200                                                     | 37        | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 31        | 1.52%   |
| Intel Wireless 7265                                                     | 27        | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 26        | 1.28%   |
| Intel Wireless 7260                                                     | 26        | 1.28%   |
| Intel Wireless 8265 / 8275                                              | 25        | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 24        | 1.18%   |
| Intel Wireless 8260                                                     | 24        | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.13%   |
| Intel Wi-Fi 6 AX201                                                     | 23        | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 22        | 1.08%   |
| Intel Ethernet Connection I217-LM                                       | 21        | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 0.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 18        | 0.88%   |
| Realtek 802.11ac NIC                                                    | 16        | 0.79%   |
| Intel Wireless 3165                                                     | 16        | 0.79%   |
| Intel I211 Gigabit Network Connection                                   | 16        | 0.79%   |
| Ralink MT7601U Wireless Adapter                                         | 15        | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                       | 14        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 14        | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 0.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 12        | 0.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 0.59%   |
| Intel Ethernet Connection I219-LM                                       | 12        | 0.59%   |
| Intel Ethernet Connection (2) I219-V                                    | 12        | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 12        | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                           | 12        | 0.59%   |
| Intel WiFi Link 5100                                                    | 11        | 0.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 11        | 0.54%   |
| Intel Ethernet Controller I225-V                                        | 10        | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 10        | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 0.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.44%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 0.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 0.44%   |
| Intel 82577LM Gigabit Network Connection                                | 9         | 0.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 9         | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 8         | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 8         | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 0.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 8         | 0.39%   |
| Intel Ethernet Connection I218-LM                                       | 8         | 0.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 0.39%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 0.39%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.39%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 7         | 0.34%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 7         | 0.34%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 7         | 0.34%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 371       | 39.05%  |
| Qualcomm Atheros                | 183       | 19.26%  |
| Realtek Semiconductor           | 164       | 17.26%  |
| Broadcom                        | 78        | 8.21%   |
| Ralink Technology               | 32        | 3.37%   |
| Ralink                          | 24        | 2.53%   |
| Broadcom Limited                | 22        | 2.32%   |
| TP-Link                         | 19        | 2%      |
| NetGear                         | 6         | 0.63%   |
| MEDIATEK                        | 6         | 0.63%   |
| Edimax Technology               | 6         | 0.63%   |
| Qualcomm Atheros Communications | 5         | 0.53%   |
| Dell                            | 5         | 0.53%   |
| D-Link System                   | 5         | 0.53%   |
| Microsoft                       | 4         | 0.42%   |
| Sierra Wireless                 | 3         | 0.32%   |
| Marvell Technology Group        | 3         | 0.32%   |
| Linksys                         | 2         | 0.21%   |
| D-Link                          | 2         | 0.21%   |
| ZyXEL Communications            | 1         | 0.11%   |
| ZyDAS                           | 1         | 0.11%   |
| Qualcomm                        | 1         | 0.11%   |
| Panasonic (Matsushita)          | 1         | 0.11%   |
| Hewlett-Packard                 | 1         | 0.11%   |
| Gemtek                          | 1         | 0.11%   |
| Fibocom                         | 1         | 0.11%   |
| Belkin Components               | 1         | 0.11%   |
| ASUSTek Computer                | 1         | 0.11%   |
| ADMtek                          | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 49        | 5.11%   |
| Intel Wi-Fi 6 AX200                                                     | 37        | 3.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 31        | 3.24%   |
| Intel Wireless 7265                                                     | 27        | 2.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 26        | 2.71%   |
| Intel Wireless 7260                                                     | 26        | 2.71%   |
| Intel Wireless 8265 / 8275                                              | 25        | 2.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 24        | 2.51%   |
| Intel Wireless 8260                                                     | 24        | 2.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 2.4%    |
| Intel Wi-Fi 6 AX201                                                     | 23        | 2.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 2.3%    |
| Broadcom BCM43142 802.11b/g/n                                           | 22        | 2.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 1.88%   |
| Realtek 802.11ac NIC                                                    | 16        | 1.67%   |
| Intel Wireless 3165                                                     | 16        | 1.67%   |
| Ralink MT7601U Wireless Adapter                                         | 15        | 1.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 1.36%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 12        | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 12        | 1.25%   |
| Intel WiFi Link 5100                                                    | 11        | 1.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 11        | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.94%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 0.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 8         | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 0.84%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.84%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.73%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 7         | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 7         | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.73%   |
| Intel Wireless-AC 9260                                                  | 7         | 0.73%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 0.73%   |
| Intel Centrino Advanced-N 6235                                          | 7         | 0.73%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 7         | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.63%   |
| Ralink RT5370 Wireless Adapter                                          | 6         | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.63%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 6         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 0.52%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 5         | 0.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.52%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 0.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 0.42%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 4         | 0.42%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.42%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.42%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 551       | 53.03%  |
| Intel                            | 250       | 24.06%  |
| Qualcomm Atheros                 | 69        | 6.64%   |
| Broadcom                         | 57        | 5.49%   |
| Marvell Technology Group         | 15        | 1.44%   |
| ASIX Electronics                 | 15        | 1.44%   |
| Broadcom Limited                 | 13        | 1.25%   |
| Samsung Electronics              | 10        | 0.96%   |
| Nvidia                           | 10        | 0.96%   |
| DisplayLink                      | 10        | 0.96%   |
| Xiaomi                           | 9         | 0.87%   |
| Huawei Technologies              | 5         | 0.48%   |
| TP-Link                          | 3         | 0.29%   |
| JMicron Technology               | 3         | 0.29%   |
| OPPO Electronics                 | 2         | 0.19%   |
| Motorola PCS                     | 2         | 0.19%   |
| MediaTek                         | 2         | 0.19%   |
| Google                           | 2         | 0.19%   |
| Sun Microsystems                 | 1         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |
| Research In Motion               | 1         | 0.1%    |
| Qualcomm                         | 1         | 0.1%    |
| OnePlus                          | 1         | 0.1%    |
| Novatel Wireless                 | 1         | 0.1%    |
| Motorola BCS                     | 1         | 0.1%    |
| Lenovo                           | 1         | 0.1%    |
| ICS Advent                       | 1         | 0.1%    |
| Hewlett-Packard                  | 1         | 0.1%    |
| D-Link System                    | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 417       | 39.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 90        | 8.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 5.88%   |
| Intel Ethernet Connection I217-LM                                 | 21        | 1.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 1.71%   |
| Intel I211 Gigabit Network Connection                             | 16        | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 1.33%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 1.14%   |
| Intel Ethernet Connection (2) I219-V                              | 12        | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 1.14%   |
| Intel Ethernet Controller I225-V                                  | 10        | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 0.85%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 9         | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 7         | 0.66%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 7         | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 6         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.47%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.47%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 0.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5         | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4         | 0.38%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.38%   |
| Nvidia MCP61 Ethernet                                             | 4         | 0.38%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 0.38%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.38%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.38%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.38%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 3         | 0.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.28%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.28%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.28%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.28%   |
| Intel Ethernet Connection (3) I218-V                              | 3         | 0.28%   |
| Intel 82577LC Gigabit Network Connection                          | 3         | 0.28%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.28%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3         | 0.28%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 3         | 0.28%   |
| Huawei E353/E3131                                                 | 3         | 0.28%   |
| DisplayLink Dell Universal Dock D6000                             | 3         | 0.28%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 982       | 51.85%  |
| WiFi     | 890       | 46.99%  |
| Modem    | 15        | 0.79%   |
| Unknown  | 7         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 918       | 52.22%  |
| WiFi     | 834       | 47.44%  |
| Modem    | 3         | 0.17%   |
| Unknown  | 3         | 0.17%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 642       | 56.56%  |
| 1     | 437       | 38.5%   |
| 0     | 36        | 3.17%   |
| 3     | 18        | 1.59%   |
| 5     | 2         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 803       | 70.19%  |
| Yes  | 341       | 29.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 272       | 39.88%  |
| Realtek Semiconductor           | 78        | 11.44%  |
| Qualcomm Atheros Communications | 61        | 8.94%   |
| Broadcom                        | 47        | 6.89%   |
| Cambridge Silicon Radio         | 38        | 5.57%   |
| Apple                           | 32        | 4.69%   |
| Lite-On Technology              | 24        | 3.52%   |
| IMC Networks                    | 24        | 3.52%   |
| Foxconn / Hon Hai               | 23        | 3.37%   |
| Dell                            | 16        | 2.35%   |
| Toshiba                         | 10        | 1.47%   |
| Qualcomm Atheros                | 9         | 1.32%   |
| Hewlett-Packard                 | 9         | 1.32%   |
| ASUSTek Computer                | 8         | 1.17%   |
| Ralink                          | 6         | 0.88%   |
| Foxconn International           | 4         | 0.59%   |
| MediaTek                        | 3         | 0.44%   |
| Marvell Semiconductor           | 3         | 0.44%   |
| Integrated System Solution      | 3         | 0.44%   |
| Alps Electric                   | 3         | 0.44%   |
| Realtek                         | 2         | 0.29%   |
| Dynex                           | 2         | 0.29%   |
| National Semiconductor          | 1         | 0.15%   |
| Micro Star International        | 1         | 0.15%   |
| D-Link System                   | 1         | 0.15%   |
| Belkin Components               | 1         | 0.15%   |
| Askey Computer                  | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 96        | 14.08%  |
| Intel Bluetooth wireless interface                                                  | 76        | 11.14%  |
| Realtek Bluetooth Radio                                                             | 58        | 8.5%    |
| Intel AX201 Bluetooth                                                               | 39        | 5.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 38        | 5.57%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 37        | 5.43%   |
| Intel AX200 Bluetooth                                                               | 30        | 4.4%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 16        | 2.35%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 2.35%   |
| Lite-On Bluetooth Device                                                            | 13        | 1.91%   |
| IMC Networks Bluetooth Device                                                       | 11        | 1.61%   |
| Apple Bluetooth Host Controller                                                     | 11        | 1.61%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 10        | 1.47%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 10        | 1.47%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 9         | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 9         | 1.32%   |
| IMC Networks Bluetooth Radio                                                        | 9         | 1.32%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 9         | 1.32%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 8         | 1.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 8         | 1.17%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 8         | 1.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 8         | 1.17%   |
| Apple Bluetooth USB Host Controller                                                 | 8         | 1.17%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 1.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 7         | 1.03%   |
| Ralink RT3290 Bluetooth                                                             | 6         | 0.88%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 0.88%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 0.73%   |
| Dell BCM20702A0                                                                     | 5         | 0.73%   |
| Apple Bluetooth HCI                                                                 | 5         | 0.73%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 0.59%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.44%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 3         | 0.44%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 3         | 0.44%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 3         | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 0.44%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 3         | 0.44%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 3         | 0.44%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 3         | 0.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 3         | 0.44%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 3         | 0.44%   |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 0.29%   |
| Toshiba BCM43142A0                                                                  | 2         | 0.29%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.29%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.29%   |
| MediaTek Wireless_Device                                                            | 2         | 0.29%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.29%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.29%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.29%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 2         | 0.29%   |
| Dell BT Mini-Receiver                                                               | 2         | 0.29%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.29%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 0.29%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.29%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.29%   |
| ASUS Qualcomm Bluetooth 4.1                                                         | 2         | 0.29%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.15%   |
| Toshiba BRCM Bluetooth Controller BCM2070                                           | 1         | 0.15%   |
| Toshiba Askey for                                                                   | 1         | 0.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 846       | 55.84%  |
| AMD                                  | 310       | 20.46%  |
| Nvidia                               | 251       | 16.57%  |
| C-Media Electronics                  | 18        | 1.19%   |
| Creative Labs                        | 8         | 0.53%   |
| Logitech                             | 6         | 0.4%    |
| Texas Instruments                    | 5         | 0.33%   |
| Razer USA                            | 5         | 0.33%   |
| JMTek                                | 5         | 0.33%   |
| GN Netcom                            | 5         | 0.33%   |
| Plantronics                          | 4         | 0.26%   |
| VIA Technologies                     | 3         | 0.2%    |
| SteelSeries ApS                      | 3         | 0.2%    |
| Realtek Semiconductor                | 3         | 0.2%    |
| Kingston Technology                  | 3         | 0.2%    |
| Corsair                              | 3         | 0.2%    |
| Thesycon Systemsoftware & Consulting | 2         | 0.13%   |
| Tenx Technology                      | 2         | 0.13%   |
| Numark                               | 2         | 0.13%   |
| Focusrite-Novation                   | 2         | 0.13%   |
| Creative Technology                  | 2         | 0.13%   |
| ASUSTek Computer                     | 2         | 0.13%   |
| XMOS                                 | 1         | 0.07%   |
| Valve Software                       | 1         | 0.07%   |
| Swissonic                            | 1         | 0.07%   |
| Silicon Labs                         | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.07%   |
| Sennheiser Communications            | 1         | 0.07%   |
| SAVITECH                             | 1         | 0.07%   |
| Samsung Electronics                  | 1         | 0.07%   |
| ROCCAT                               | 1         | 0.07%   |
| Microsoft                            | 1         | 0.07%   |
| Micronas                             | 1         | 0.07%   |
| Micro Star International             | 1         | 0.07%   |
| LucidSound                           | 1         | 0.07%   |
| Lenovo                               | 1         | 0.07%   |
| Klipsch Audio                        | 1         | 0.07%   |
| Insignia (Best Buy)                  | 1         | 0.07%   |
| iCreate Technologies                 | 1         | 0.07%   |
| iConnectivity                        | 1         | 0.07%   |
| Google                               | 1         | 0.07%   |
| Generalplus Technology               | 1         | 0.07%   |
| GEMBIRD                              | 1         | 0.07%   |
| FIFINE Microphones                   | 1         | 0.07%   |
| Conexant Systems                     | 1         | 0.07%   |
| AudioQuest                           | 1         | 0.07%   |
| Asahi Kasei Microsystems             | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 107       | 5.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 100       | 5.59%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 89        | 4.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 68        | 3.8%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 59        | 3.3%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 53        | 2.96%   |
| AMD FCH Azalia Controller                                                                         | 50        | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 48        | 2.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 47        | 2.63%   |
| Intel 8 Series HD Audio Controller                                                                | 41        | 2.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 38        | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 35        | 1.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 35        | 1.96%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 35        | 1.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 31        | 1.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 30        | 1.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 30        | 1.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 27        | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 27        | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 27        | 1.51%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 26        | 1.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 25        | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 1.34%   |
| Intel Broadwell-U Audio Controller                                                                | 24        | 1.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 1.28%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 17        | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 17        | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 16        | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 16        | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 15        | 0.84%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 15        | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 15        | 0.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 14        | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 14        | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 14        | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 0.78%   |
| Nvidia High Definition Audio Controller                                                           | 13        | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 0.73%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13        | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 12        | 0.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 12        | 0.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 11        | 0.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 11        | 0.61%   |
| Intel 200 Series PCH HD Audio                                                                     | 10        | 0.56%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 10        | 0.56%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 9         | 0.5%    |
| AMD High Definition Audio Controller                                                              | 9         | 0.5%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 8         | 0.45%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 8         | 0.45%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 8         | 0.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 8         | 0.45%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 8         | 0.45%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 8         | 0.45%   |
| AMD Navi 10 HDMI Audio                                                                            | 8         | 0.45%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8         | 0.45%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 7         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 47        | 22.71%  |
| SK Hynix            | 40        | 19.32%  |
| Micron Technology   | 24        | 11.59%  |
| Unknown             | 21        | 10.14%  |
| Kingston            | 15        | 7.25%   |
| Crucial             | 11        | 5.31%   |
| Corsair             | 8         | 3.86%   |
| G.Skill             | 7         | 3.38%   |
| Unknown (ABCD)      | 6         | 2.9%    |
| Ramaxel Technology  | 5         | 2.42%   |
| A-DATA Technology   | 5         | 2.42%   |
| Team                | 3         | 1.45%   |
| Nanya Technology    | 3         | 1.45%   |
| Patriot             | 2         | 0.97%   |
| TIMETEC             | 1         | 0.48%   |
| Teikon              | 1         | 0.48%   |
| Strontium           | 1         | 0.48%   |
| Puskill             | 1         | 0.48%   |
| Goldkey             | 1         | 0.48%   |
| F7852C80            | 1         | 0.48%   |
| ELPIDA              | 1         | 0.48%   |
| AXIOM               | 1         | 0.48%   |
| Avant               | 1         | 0.48%   |
| Unknown             | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 6         | 2.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 5         | 2.28%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 4         | 1.83%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 4         | 1.83%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 1.37%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s              | 3         | 1.37%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.91%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 2         | 0.91%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                        | 2         | 0.91%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 2         | 0.91%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.91%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.91%   |
| SK Hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.91%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 2         | 0.91%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 2         | 0.91%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 0.91%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.91%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 0.91%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 0.91%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s              | 2         | 0.91%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s             | 2         | 0.91%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 2         | 0.91%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 0.91%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                   | 2         | 0.91%   |
| A-DATA RAM AE4S240038G17-BHYA 8192MB SODIMM DDR4 2400MT/s           | 2         | 0.91%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s             | 1         | 0.46%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 0.46%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                         | 1         | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                           | 1         | 0.46%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                | 1         | 0.46%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s                        | 1         | 0.46%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                        | 1         | 0.46%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 0.46%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1         | 0.46%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                      | 1         | 0.46%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                        | 1         | 0.46%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s                         | 1         | 0.46%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                              | 1         | 0.46%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                        | 1         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 1         | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR2 1333MT/s                        | 1         | 0.46%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2133MT/s                     | 1         | 0.46%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s                  | 1         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s        | 1         | 0.46%   |
| TIMETEC RAM SD3-1600 8192MB SODIMM DDR3 1600MT/s                    | 1         | 0.46%   |
| Teikon RAM TMT351S6EFR8A-PBHJ 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.46%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s               | 1         | 0.46%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s                  | 1         | 0.46%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s                | 1         | 0.46%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s                | 1         | 0.46%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                   | 1         | 0.46%   |
| SK Hynix RAM HYMP112S64CP6-Y5 1024MB SODIMM DDR 667MT/s             | 1         | 0.46%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.46%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.46%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.46%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 0.46%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s                | 1         | 0.46%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 79        | 43.65%  |
| DDR3    | 64        | 35.36%  |
| LPDDR4  | 15        | 8.29%   |
| LPDDR3  | 8         | 4.42%   |
| DDR2    | 5         | 2.76%   |
| Unknown | 5         | 2.76%   |
| SDRAM   | 4         | 2.21%   |
| DDR     | 1         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 109       | 61.24%  |
| DIMM         | 51        | 28.65%  |
| Row Of Chips | 17        | 9.55%   |
| Chip         | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 79        | 39.7%   |
| 8192  | 74        | 37.19%  |
| 16384 | 20        | 10.05%  |
| 2048  | 20        | 10.05%  |
| 32768 | 3         | 1.51%   |
| 1024  | 3         | 1.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 42        | 21.54%  |
| 2667    | 37        | 18.97%  |
| 3200    | 20        | 10.26%  |
| 2400    | 17        | 8.72%   |
| 1333    | 16        | 8.21%   |
| 2133    | 10        | 5.13%   |
| 1334    | 7         | 3.59%   |
| 4267    | 6         | 3.08%   |
| 3266    | 6         | 3.08%   |
| 1867    | 4         | 2.05%   |
| Unknown | 4         | 2.05%   |
| 3600    | 3         | 1.54%   |
| 1800    | 3         | 1.54%   |
| 800     | 3         | 1.54%   |
| 667     | 3         | 1.54%   |
| 4199    | 2         | 1.03%   |
| 2048    | 2         | 1.03%   |
| 8400    | 1         | 0.51%   |
| 3466    | 1         | 0.51%   |
| 3333    | 1         | 0.51%   |
| 3000    | 1         | 0.51%   |
| 2933    | 1         | 0.51%   |
| 2800    | 1         | 0.51%   |
| 2666    | 1         | 0.51%   |
| 1866    | 1         | 0.51%   |
| 1400    | 1         | 0.51%   |
| 1067    | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 34.78%  |
| Canon               | 7         | 30.43%  |
| Samsung Electronics | 4         | 17.39%  |
| Seiko Epson         | 2         | 8.7%    |
| Brother Industries  | 2         | 8.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Canon TS3100 series               | 2         | 8.7%    |
| Seiko Epson XP-202 203 206 Series | 1         | 4.35%   |
| Seiko Epson L3110 Series          | 1         | 4.35%   |
| Samsung SCX-483x 5x3x Series      | 1         | 4.35%   |
| Samsung SCX-4200 series           | 1         | 4.35%   |
| Samsung SCX-3400 Series           | 1         | 4.35%   |
| Samsung C460 Series               | 1         | 4.35%   |
| HP OfficeJet Pro 9010 series      | 1         | 4.35%   |
| HP OfficeJet 4650 series          | 1         | 4.35%   |
| HP LaserJet Professional P1102w   | 1         | 4.35%   |
| HP LaserJet 1200                  | 1         | 4.35%   |
| HP LaserJet 1000                  | 1         | 4.35%   |
| HP ENVY Photo 6200 series         | 1         | 4.35%   |
| HP DeskJet 2700 series            | 1         | 4.35%   |
| HP DeskJet 1110 series            | 1         | 4.35%   |
| Canon TR4500 series               | 1         | 4.35%   |
| Canon PIXMA MG3000 series         | 1         | 4.35%   |
| Canon PIXMA MG2500 Series         | 1         | 4.35%   |
| Canon LiDE 400                    | 1         | 4.35%   |
| Canon iP4200                      | 1         | 4.35%   |
| Brother MFC-9140CDN               | 1         | 4.35%   |
| Brother DCP-L2540DW               | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 60%     |
| Seiko Epson     | 1         | 20%     |
| Hewlett-Packard | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 1         | 20%     |
| HP ScanJet 2400c                            | 1         | 20%     |
| Canon CanoScan LiDE 90                      | 1         | 20%     |
| Canon CanoScan LiDE 100                     | 1         | 20%     |
| Canon CanoScan 8800F                        | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 150       | 22.59%  |
| Realtek Semiconductor                  | 69        | 10.39%  |
| IMC Networks                           | 59        | 8.89%   |
| Microdia                               | 49        | 7.38%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 5.27%   |
| Sunplus Innovation Technology          | 34        | 5.12%   |
| Acer                                   | 34        | 5.12%   |
| Apple                                  | 27        | 4.07%   |
| Suyin                                  | 24        | 3.61%   |
| Logitech                               | 24        | 3.61%   |
| Syntek                                 | 21        | 3.16%   |
| Quanta                                 | 21        | 3.16%   |
| Lite-On Technology                     | 12        | 1.81%   |
| Alcor Micro                            | 11        | 1.66%   |
| Ricoh                                  | 10        | 1.51%   |
| Silicon Motion                         | 9         | 1.36%   |
| Samsung Electronics                    | 9         | 1.36%   |
| Microsoft                              | 7         | 1.05%   |
| Primax Electronics                     | 4         | 0.6%    |
| Generalplus Technology                 | 4         | 0.6%    |
| ARC International                      | 4         | 0.6%    |
| Luxvisions Innotech Limited            | 3         | 0.45%   |
| Genesys Logic                          | 3         | 0.45%   |
| DJKANA1BIF866I                         | 3         | 0.45%   |
| Z-Star Microelectronics                | 2         | 0.3%    |
| Sunplus Technology                     | 2         | 0.3%    |
| Razer USA                              | 2         | 0.3%    |
| icSpring                               | 2         | 0.3%    |
| ALi                                    | 2         | 0.3%    |
| YGTek                                  | 1         | 0.15%   |
| Y Media                                | 1         | 0.15%   |
| Xiongmai                               | 1         | 0.15%   |
| Unknown                                | 1         | 0.15%   |
| Teslong Camera                         | 1         | 0.15%   |
| SunplusIT                              | 1         | 0.15%   |
| Sonix Technology                       | 1         | 0.15%   |
| Pixart Imaging                         | 1         | 0.15%   |
| Panasonic (Matsushita)                 | 1         | 0.15%   |
| OmniVision Technologies                | 1         | 0.15%   |
| lihappe8                               | 1         | 0.15%   |
| LG Electronics                         | 1         | 0.15%   |
| Lenovo                                 | 1         | 0.15%   |
| KYE Systems (Mouse Systems)            | 1         | 0.15%   |
| Jieli Technology                       | 1         | 0.15%   |
| INOGENI                                | 1         | 0.15%   |
| Importek                               | 1         | 0.15%   |
| Huawei Technologies                    | 1         | 0.15%   |
| HD 2MP WEBCAM                          | 1         | 0.15%   |
| Guillemot                              | 1         | 0.15%   |
| GenesysLogic Technology                | 1         | 0.15%   |
| GEMBIRD                                | 1         | 0.15%   |
| DigiTech                               | 1         | 0.15%   |
| Denron                                 | 1         | 0.15%   |
| Creative Technology                    | 1         | 0.15%   |
| AVerMedia Technologies                 | 1         | 0.15%   |
| Arkmicro Technologies                  | 1         | 0.15%   |
| Anchor Chips                           | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                   | 18        | 2.7%    |
| Chicony HD WebCam                                              | 18        | 2.7%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 17        | 2.55%   |
| Chicony Integrated Camera                                      | 16        | 2.4%    |
| Microdia Integrated_Webcam_HD                                  | 15        | 2.25%   |
| Realtek USB Camera                                             | 12        | 1.8%    |
| IMC Networks Integrated Camera                                 | 12        | 1.8%    |
| Acer Integrated Camera                                         | 12        | 1.8%    |
| Chicony TOSHIBA Web Camera - HD                                | 11        | 1.65%   |
| Apple FaceTime HD Camera (Built-in)                            | 11        | 1.65%   |
| Syntek Integrated Camera                                       | 10        | 1.5%    |
| Microdia Integrated Webcam                                     | 10        | 1.5%    |
| Samsung Galaxy A5 (MTP)                                        | 9         | 1.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 9         | 1.35%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 7         | 1.05%   |
| Chicony HP Truevision HD                                       | 7         | 1.05%   |
| Sunplus Integrated_Webcam_HD                                   | 6         | 0.9%    |
| Sunplus HD WebCam                                              | 6         | 0.9%    |
| Realtek Integrated Webcam                                      | 6         | 0.9%    |
| Microdia Webcam Vitade AF                                      | 6         | 0.9%    |
| Logitech Webcam C270                                           | 6         | 0.9%    |
| Apple Built-in iSight                                          | 6         | 0.9%    |
| Syntek Lenovo EasyCamera                                       | 5         | 0.75%   |
| Quanta HD User Facing                                          | 5         | 0.75%   |
| Chicony VGA Webcam                                             | 5         | 0.75%   |
| Chicony USB 2.0 Camera                                         | 5         | 0.75%   |
| Chicony Lenovo EasyCamera                                      | 5         | 0.75%   |
| Chicony HP Webcam                                              | 5         | 0.75%   |
| Chicony EasyCamera                                             | 5         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 5         | 0.75%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 5         | 0.75%   |
| Alcor Micro USB 2.0 Camera                                     | 5         | 0.75%   |
| Acer Lenovo Integrated Webcam                                  | 5         | 0.75%   |
| Acer Lenovo EasyCamera                                         | 5         | 0.75%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 4         | 0.6%    |
| Suyin HP TrueVision HD                                         | 4         | 0.6%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 4         | 0.6%    |
| Realtek USB2.0 HD UVC WebCam                                   | 4         | 0.6%    |
| Realtek Lenovo EasyCamera                                      | 4         | 0.6%    |
| Realtek Integrated Webcam HD                                   | 4         | 0.6%    |
| Realtek HP Truevision HD integrated webcam                     | 4         | 0.6%    |
| Quanta VGA WebCam                                              | 4         | 0.6%    |
| Microsoft LifeCam HD-3000                                      | 4         | 0.6%    |
| Logitech HD Pro Webcam C920                                    | 4         | 0.6%    |
| Lite-On HP HD Camera                                           | 4         | 0.6%    |
| Generalplus GENERAL WEBCAM                                     | 4         | 0.6%    |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 4         | 0.6%    |
| Chicony HP Wide Vision HD Camera                               | 4         | 0.6%    |
| Chicony HP Truevision HD camera                                | 4         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.6%    |
| ARC International Camera                                       | 4         | 0.6%    |
| Apple FaceTime HD Camera                                       | 4         | 0.6%    |
| Alcor Micro Asus Integrated Webcam                             | 4         | 0.6%    |
| Syntek EasyCamera                                              | 3         | 0.45%   |
| Sunplus HP Truevision Full HD                                  | 3         | 0.45%   |
| Ricoh USB2.0 Camera                                            | 3         | 0.45%   |
| Ricoh Laptop_Integrated_Webcam_FHD                             | 3         | 0.45%   |
| Quanta HP Wide Vision HD Camera                                | 3         | 0.45%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 0.45%   |
| IMC Networks USB Camera                                        | 3         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 45        | 43.27%  |
| Shenzhen Goodix Technology | 14        | 13.46%  |
| Upek                       | 13        | 12.5%   |
| Synaptics                  | 12        | 11.54%  |
| AuthenTec                  | 11        | 10.58%  |
| STMicroelectronics         | 4         | 3.85%   |
| LighTuning Technology      | 4         | 3.85%   |
| Focal-systems.Corp         | 1         | 0.96%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 11.54%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 9.62%   |
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 5.77%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 5.77%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 4.81%   |
| Unknown                                                                    | 5         | 4.81%   |
| Validity Sensors VFS491                                                    | 4         | 3.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 3.85%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.88%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.88%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.88%   |
| Synaptics  WBDI                                                            | 3         | 2.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 2.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.88%   |
| AuthenTec AES2810                                                          | 3         | 2.88%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 2.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.92%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.92%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.92%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.92%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.92%   |
| AuthenTec AES1600                                                          | 2         | 1.92%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.96%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.96%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.96%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.96%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.96%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.96%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.96%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.96%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 31        | 54.39%  |
| Alcor Micro                       | 10        | 17.54%  |
| O2 Micro                          | 4         | 7.02%   |
| Yubico.com                        | 2         | 3.51%   |
| Upek                              | 2         | 3.51%   |
| Lenovo                            | 2         | 3.51%   |
| VASCO Data Security International | 1         | 1.75%   |
| SCM Microsystems                  | 1         | 1.75%   |
| Reiner SCT Kartensysteme          | 1         | 1.75%   |
| Realtek Semiconductor             | 1         | 1.75%   |
| OmniKey                           | 1         | 1.75%   |
| Advanced Card Systems             | 1         | 1.75%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 17.54%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 17.54%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 17.54%  |
| Broadcom 5880                                                                | 9         | 15.79%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 7.02%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 2         | 3.51%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.51%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.51%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 1.75%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.75%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 1.75%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.75%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.75%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.75%   |
| Broadcom 58200                                                               | 1         | 1.75%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.75%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 834       | 72.84%  |
| 1     | 248       | 21.66%  |
| 2     | 59        | 5.15%   |
| 3     | 4         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 103       | 28.07%  |
| Graphics card            | 73        | 19.89%  |
| Net/wireless             | 62        | 16.89%  |
| Chipcard                 | 49        | 13.35%  |
| Multimedia controller    | 42        | 11.44%  |
| Storage                  | 11        | 3%      |
| Bluetooth                | 8         | 2.18%   |
| Camera                   | 4         | 1.09%   |
| Communication controller | 3         | 0.82%   |
| Unassigned class         | 2         | 0.54%   |
| Storage/ide              | 2         | 0.54%   |
| Sound                    | 2         | 0.54%   |
| Flash memory             | 2         | 0.54%   |
| Network                  | 1         | 0.27%   |
| Net/ethernet             | 1         | 0.27%   |
| Dvb card                 | 1         | 0.27%   |
| Card reader              | 1         | 0.27%   |

