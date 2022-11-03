Linux in France - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in France.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/France/Desktop/README.md) and [notebooks](/Location/France/Notebook/README.md).

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

Total: 10438

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite C70D-A            | Notebook    | [7a421ed810](https://linux-hardware.org/?probe=7a421ed810) | Nov 02, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [d82227846b](https://linux-hardware.org/?probe=d82227846b) | Nov 02, 2022 |
| Dell          | G3 3500                     | Notebook    | [c595a16f59](https://linux-hardware.org/?probe=c595a16f59) | Nov 02, 2022 |
| Dell          | 0JGM7F A00                  | Desktop     | [28f4800b2b](https://linux-hardware.org/?probe=28f4800b2b) | Nov 02, 2022 |
| Dell          | Latitude 5420               | Notebook    | [679fbcb14f](https://linux-hardware.org/?probe=679fbcb14f) | Nov 02, 2022 |
| Dell          | 0TWFTR A02                  | All in one  | [21b78069dd](https://linux-hardware.org/?probe=21b78069dd) | Nov 02, 2022 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [075f628a80](https://linux-hardware.org/?probe=075f628a80) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [9fa0489d64](https://linux-hardware.org/?probe=9fa0489d64) | Nov 01, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [411a5da53c](https://linux-hardware.org/?probe=411a5da53c) | Nov 01, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [6a0d7d5f39](https://linux-hardware.org/?probe=6a0d7d5f39) | Nov 01, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8f551aaa52](https://linux-hardware.org/?probe=8f551aaa52) | Nov 01, 2022 |
| HP            | Pavilion dv5                | Notebook    | [fb23cec1a6](https://linux-hardware.org/?probe=fb23cec1a6) | Nov 01, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [ccf4e200fb](https://linux-hardware.org/?probe=ccf4e200fb) | Nov 01, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [08649bd1e9](https://linux-hardware.org/?probe=08649bd1e9) | Nov 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [cf9998e9b9](https://linux-hardware.org/?probe=cf9998e9b9) | Nov 01, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [9d237f0d30](https://linux-hardware.org/?probe=9d237f0d30) | Oct 31, 2022 |
| Dell          | 03NVJ6 A03                  | Desktop     | [adebd09dc4](https://linux-hardware.org/?probe=adebd09dc4) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | Notebook    | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [865aef7529](https://linux-hardware.org/?probe=865aef7529) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [fb96cd8e21](https://linux-hardware.org/?probe=fb96cd8e21) | Oct 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [ce59648f62](https://linux-hardware.org/?probe=ce59648f62) | Oct 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [e993af2670](https://linux-hardware.org/?probe=e993af2670) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X270 20HN0014FR    | Notebook    | [d6fc7c48a1](https://linux-hardware.org/?probe=d6fc7c48a1) | Oct 30, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [1e0daee604](https://linux-hardware.org/?probe=1e0daee604) | Oct 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ad558f1150](https://linux-hardware.org/?probe=ad558f1150) | Oct 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [e8a1f8f6bf](https://linux-hardware.org/?probe=e8a1f8f6bf) | Oct 30, 2022 |
| HP            | 158B                        | Desktop     | [9c02b7fe58](https://linux-hardware.org/?probe=9c02b7fe58) | Oct 30, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [c24c24ab27](https://linux-hardware.org/?probe=c24c24ab27) | Oct 30, 2022 |
| Dell          | XPS L322X                   | Notebook    | [cacebfe41e](https://linux-hardware.org/?probe=cacebfe41e) | Oct 30, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d4552d84d5](https://linux-hardware.org/?probe=d4552d84d5) | Oct 30, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [95238cc6e8](https://linux-hardware.org/?probe=95238cc6e8) | Oct 30, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [51a91ba41f](https://linux-hardware.org/?probe=51a91ba41f) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [6873e5b579](https://linux-hardware.org/?probe=6873e5b579) | Oct 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4c562a178](https://linux-hardware.org/?probe=d4c562a178) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [da1b668449](https://linux-hardware.org/?probe=da1b668449) | Oct 30, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [18ca81370b](https://linux-hardware.org/?probe=18ca81370b) | Oct 29, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [0a95698cb6](https://linux-hardware.org/?probe=0a95698cb6) | Oct 29, 2022 |
| HP            | Compaq 615                  | Notebook    | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [16815dacc1](https://linux-hardware.org/?probe=16815dacc1) | Oct 29, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [610be75cca](https://linux-hardware.org/?probe=610be75cca) | Oct 29, 2022 |
| ASUSTek       | X751NV                      | Notebook    | [9ef2717db0](https://linux-hardware.org/?probe=9ef2717db0) | Oct 29, 2022 |
| HP            | 8653 A                      | Desktop     | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| IP3 Tech      | AP1                         | Notebook    | [0562a6a46d](https://linux-hardware.org/?probe=0562a6a46d) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | Notebook    | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| IP3 Tech      | AP1                         | Notebook    | [2a9c0ff1c5](https://linux-hardware.org/?probe=2a9c0ff1c5) | Oct 28, 2022 |
| Dell          | 02M8NY A01                  | Desktop     | [47c0e65f02](https://linux-hardware.org/?probe=47c0e65f02) | Oct 28, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8fad928e72](https://linux-hardware.org/?probe=8fad928e72) | Oct 28, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [2501d67199](https://linux-hardware.org/?probe=2501d67199) | Oct 28, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [9827bdf3f6](https://linux-hardware.org/?probe=9827bdf3f6) | Oct 28, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [267b0a3f94](https://linux-hardware.org/?probe=267b0a3f94) | Oct 28, 2022 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | Notebook    | [05ff2d32fa](https://linux-hardware.org/?probe=05ff2d32fa) | Oct 28, 2022 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | Notebook    | [403a99d8b2](https://linux-hardware.org/?probe=403a99d8b2) | Oct 28, 2022 |
| ASUSTek       | ET2700I                     | Desktop     | [ce0d0e61eb](https://linux-hardware.org/?probe=ce0d0e61eb) | Oct 28, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [0c6a68368c](https://linux-hardware.org/?probe=0c6a68368c) | Oct 27, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [07f7d43f09](https://linux-hardware.org/?probe=07f7d43f09) | Oct 27, 2022 |
| Acer          | Extensa 2509                | Notebook    | [a27b3d38a9](https://linux-hardware.org/?probe=a27b3d38a9) | Oct 27, 2022 |
| Intel         | ArcherCity                  | Server      | [625da68153](https://linux-hardware.org/?probe=625da68153) | Oct 27, 2022 |
| Alienware     | m17 R4                      | Notebook    | [14770101cf](https://linux-hardware.org/?probe=14770101cf) | Oct 27, 2022 |
| MSI           | B85-G43                     | Desktop     | [48ac016cd9](https://linux-hardware.org/?probe=48ac016cd9) | Oct 27, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [8c9d6eb128](https://linux-hardware.org/?probe=8c9d6eb128) | Oct 27, 2022 |
| Dell          | Latitude 5310               | Notebook    | [10b8371dbd](https://linux-hardware.org/?probe=10b8371dbd) | Oct 27, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [6aaeaf667c](https://linux-hardware.org/?probe=6aaeaf667c) | Oct 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | Notebook    | [9564d50ef8](https://linux-hardware.org/?probe=9564d50ef8) | Oct 27, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [951c734c1b](https://linux-hardware.org/?probe=951c734c1b) | Oct 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [088235cbff](https://linux-hardware.org/?probe=088235cbff) | Oct 26, 2022 |
| Dell          | Precision 7560              | Notebook    | [c82d6a32a5](https://linux-hardware.org/?probe=c82d6a32a5) | Oct 26, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [6062baa35c](https://linux-hardware.org/?probe=6062baa35c) | Oct 26, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [34be38a48b](https://linux-hardware.org/?probe=34be38a48b) | Oct 26, 2022 |
| Dell          | 05WNJ2 A02                  | Server      | [97d42fd93a](https://linux-hardware.org/?probe=97d42fd93a) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [08b067d2cf](https://linux-hardware.org/?probe=08b067d2cf) | Oct 25, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a128f79c0a](https://linux-hardware.org/?probe=a128f79c0a) | Oct 25, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | Notebook    | [eadb224c05](https://linux-hardware.org/?probe=eadb224c05) | Oct 25, 2022 |
| Raspberry ... | Raspberry Pi Zero Rev 1.... | Soc         | [80cd406dda](https://linux-hardware.org/?probe=80cd406dda) | Oct 25, 2022 |
| Dell          | Inspiron 7737               | Notebook    | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [8f246bccb1](https://linux-hardware.org/?probe=8f246bccb1) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [bc5adf7f4b](https://linux-hardware.org/?probe=bc5adf7f4b) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [6ed87cbcfb](https://linux-hardware.org/?probe=6ed87cbcfb) | Oct 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [055062356e](https://linux-hardware.org/?probe=055062356e) | Oct 25, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [ec7f3834d1](https://linux-hardware.org/?probe=ec7f3834d1) | Oct 25, 2022 |
| Toshiba       | Satellite A505              | Notebook    | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4e2d4383c0](https://linux-hardware.org/?probe=4e2d4383c0) | Oct 25, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [a9e26a3899](https://linux-hardware.org/?probe=a9e26a3899) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3ab5922ddf](https://linux-hardware.org/?probe=3ab5922ddf) | Oct 25, 2022 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [814da05eec](https://linux-hardware.org/?probe=814da05eec) | Oct 25, 2022 |
| Lenovo        | G50-45 80MQ                 | Notebook    | [1c6d041ce2](https://linux-hardware.org/?probe=1c6d041ce2) | Oct 25, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [2c4d63c9b2](https://linux-hardware.org/?probe=2c4d63c9b2) | Oct 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [544988df6e](https://linux-hardware.org/?probe=544988df6e) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [fe664e172e](https://linux-hardware.org/?probe=fe664e172e) | Oct 24, 2022 |
| Dell          | 0GX297                      | Desktop     | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d6e17c05b2](https://linux-hardware.org/?probe=d6e17c05b2) | Oct 24, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [af2163c4dd](https://linux-hardware.org/?probe=af2163c4dd) | Oct 24, 2022 |
| Packard Be... | H17HV                       | Notebook    | [2e94cfdd84](https://linux-hardware.org/?probe=2e94cfdd84) | Oct 24, 2022 |
| HP            | 8055                        | Desktop     | [624dddbaec](https://linux-hardware.org/?probe=624dddbaec) | Oct 24, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [bb06dc4756](https://linux-hardware.org/?probe=bb06dc4756) | Oct 24, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [d165241883](https://linux-hardware.org/?probe=d165241883) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| ASRock        | P45TS                       | Desktop     | [484f63b830](https://linux-hardware.org/?probe=484f63b830) | Oct 24, 2022 |
| Packard Be... | EasyNote ENTE70BH           | Notebook    | [2135a5aed7](https://linux-hardware.org/?probe=2135a5aed7) | Oct 23, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [17adb9ee1e](https://linux-hardware.org/?probe=17adb9ee1e) | Oct 23, 2022 |
| Sony          | VGN-SZ3XP_C                 | Notebook    | [72f83141a0](https://linux-hardware.org/?probe=72f83141a0) | Oct 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [50b6612f7d](https://linux-hardware.org/?probe=50b6612f7d) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| HP            | 805D                        | Desktop     | [916b6f09ac](https://linux-hardware.org/?probe=916b6f09ac) | Oct 23, 2022 |
| Dell          | Precision 7750              | Notebook    | [dd51bb7ccd](https://linux-hardware.org/?probe=dd51bb7ccd) | Oct 23, 2022 |
| HP            | 8055                        | Desktop     | [27793140bf](https://linux-hardware.org/?probe=27793140bf) | Oct 23, 2022 |
| Lenovo        | ThinkPad X240 20AMS01M00    | Notebook    | [2f1c7b7716](https://linux-hardware.org/?probe=2f1c7b7716) | Oct 23, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [e2d21dcb54](https://linux-hardware.org/?probe=e2d21dcb54) | Oct 23, 2022 |
| Dell          | Latitude E6510              | Notebook    | [73cd1082f8](https://linux-hardware.org/?probe=73cd1082f8) | Oct 22, 2022 |
| Dell          | Latitude 5420               | Notebook    | [dd9b95a216](https://linux-hardware.org/?probe=dd9b95a216) | Oct 22, 2022 |
| Acer          | TravelMate P256-M           | Notebook    | [7ca952de68](https://linux-hardware.org/?probe=7ca952de68) | Oct 22, 2022 |
| ASUSTek       | ZenBook UX534FAC_UX534FA    | Notebook    | [928997f65c](https://linux-hardware.org/?probe=928997f65c) | Oct 22, 2022 |
| MSI           | MAG Z690 TORPEDO            | Desktop     | [381a618ea5](https://linux-hardware.org/?probe=381a618ea5) | Oct 22, 2022 |
| Dell          | Latitude E6520              | Notebook    | [88af6c857c](https://linux-hardware.org/?probe=88af6c857c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | Notebook    | [246517ceab](https://linux-hardware.org/?probe=246517ceab) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [312828c6a3](https://linux-hardware.org/?probe=312828c6a3) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [57bfd1e0e9](https://linux-hardware.org/?probe=57bfd1e0e9) | Oct 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [77463ad1d7](https://linux-hardware.org/?probe=77463ad1d7) | Oct 21, 2022 |
| HP            | ProBook 6550b               | Notebook    | [cc300bedc8](https://linux-hardware.org/?probe=cc300bedc8) | Oct 21, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [85bbd08363](https://linux-hardware.org/?probe=85bbd08363) | Oct 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [a22e54462c](https://linux-hardware.org/?probe=a22e54462c) | Oct 21, 2022 |
| HP            | Stream Notebook             | Notebook    | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [45d7e6a1aa](https://linux-hardware.org/?probe=45d7e6a1aa) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | Notebook    | [c7e03dae2f](https://linux-hardware.org/?probe=c7e03dae2f) | Oct 21, 2022 |
| Radxa         | ROCK Pi X v1.4              | Notebook    | [133d713246](https://linux-hardware.org/?probe=133d713246) | Oct 21, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [3d5bfd2ba5](https://linux-hardware.org/?probe=3d5bfd2ba5) | Oct 21, 2022 |
| Lenovo        | ThinkPad R61 8935AC7        | Notebook    | [94d73589fc](https://linux-hardware.org/?probe=94d73589fc) | Oct 21, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [47ca27793e](https://linux-hardware.org/?probe=47ca27793e) | Oct 21, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5e86d7b8a7](https://linux-hardware.org/?probe=5e86d7b8a7) | Oct 21, 2022 |
| ASUSTek       | M32CD4-K                    | Desktop     | [0b5131c630](https://linux-hardware.org/?probe=0b5131c630) | Oct 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [26c773d138](https://linux-hardware.org/?probe=26c773d138) | Oct 21, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [a9f7d04fbd](https://linux-hardware.org/?probe=a9f7d04fbd) | Oct 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [4bc1726059](https://linux-hardware.org/?probe=4bc1726059) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | Notebook    | [0f73d884ff](https://linux-hardware.org/?probe=0f73d884ff) | Oct 21, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [d575515de3](https://linux-hardware.org/?probe=d575515de3) | Oct 20, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [02643d35a4](https://linux-hardware.org/?probe=02643d35a4) | Oct 20, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [ea0d3e9186](https://linux-hardware.org/?probe=ea0d3e9186) | Oct 20, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [535cc5230e](https://linux-hardware.org/?probe=535cc5230e) | Oct 20, 2022 |
| Gigabyte      | X7X7                        | Notebook    | [f2c35e3917](https://linux-hardware.org/?probe=f2c35e3917) | Oct 20, 2022 |
| HP            | ProBook 6550b               | Notebook    | [176fc347d2](https://linux-hardware.org/?probe=176fc347d2) | Oct 20, 2022 |
| HP            | EliteBook 840 Aero G8 No... | Notebook    | [80738ede80](https://linux-hardware.org/?probe=80738ede80) | Oct 20, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [ef1acaa7da](https://linux-hardware.org/?probe=ef1acaa7da) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [3ec2887574](https://linux-hardware.org/?probe=3ec2887574) | Oct 20, 2022 |
| Dell          | Precision 5510              | Notebook    | [bb7788ce01](https://linux-hardware.org/?probe=bb7788ce01) | Oct 20, 2022 |
| Alienware     | x15 R2                      | Notebook    | [39d9f7988a](https://linux-hardware.org/?probe=39d9f7988a) | Oct 20, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [13830a8b2b](https://linux-hardware.org/?probe=13830a8b2b) | Oct 20, 2022 |
| Dell          | Latitude 5420               | Notebook    | [a6ef44d08a](https://linux-hardware.org/?probe=a6ef44d08a) | Oct 20, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [4becf50dac](https://linux-hardware.org/?probe=4becf50dac) | Oct 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [cd36bb86da](https://linux-hardware.org/?probe=cd36bb86da) | Oct 19, 2022 |
| Dell          | Latitude 7300               | Notebook    | [5674456b5d](https://linux-hardware.org/?probe=5674456b5d) | Oct 19, 2022 |
| Dell          | 0CRH6C A00                  | Desktop     | [457122aa94](https://linux-hardware.org/?probe=457122aa94) | Oct 19, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [b97b4b3d9a](https://linux-hardware.org/?probe=b97b4b3d9a) | Oct 19, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [827927ddce](https://linux-hardware.org/?probe=827927ddce) | Oct 19, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [23f7ae20e3](https://linux-hardware.org/?probe=23f7ae20e3) | Oct 19, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [285952dd76](https://linux-hardware.org/?probe=285952dd76) | Oct 19, 2022 |
| HP            | 1905                        | Desktop     | [34b81558fc](https://linux-hardware.org/?probe=34b81558fc) | Oct 19, 2022 |
| HP            | 620                         | Notebook    | [263e2a0ba9](https://linux-hardware.org/?probe=263e2a0ba9) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [0f13ae1769](https://linux-hardware.org/?probe=0f13ae1769) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [2df95e6892](https://linux-hardware.org/?probe=2df95e6892) | Oct 19, 2022 |
| HP            | 620                         | Notebook    | [ad17206515](https://linux-hardware.org/?probe=ad17206515) | Oct 18, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [e0c8c2fe15](https://linux-hardware.org/?probe=e0c8c2fe15) | Oct 18, 2022 |
| MSI           | H61M-E33                    | Desktop     | [7591f8fa5f](https://linux-hardware.org/?probe=7591f8fa5f) | Oct 18, 2022 |
| HP            | 1905                        | Desktop     | [37cd2f3dc2](https://linux-hardware.org/?probe=37cd2f3dc2) | Oct 18, 2022 |
| Dell          | Precision 7750              | Notebook    | [93dcf0527b](https://linux-hardware.org/?probe=93dcf0527b) | Oct 18, 2022 |
| Dell          | Precision 7750              | Notebook    | [d32782f149](https://linux-hardware.org/?probe=d32782f149) | Oct 18, 2022 |
| Dell          | 0K7CVF A03                  | Server      | [f5274874b0](https://linux-hardware.org/?probe=f5274874b0) | Oct 18, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [5ee12be257](https://linux-hardware.org/?probe=5ee12be257) | Oct 18, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [aa5b8fb98e](https://linux-hardware.org/?probe=aa5b8fb98e) | Oct 18, 2022 |
| Insyde        | WindTab89                   | Notebook    | [8eb81874bb](https://linux-hardware.org/?probe=8eb81874bb) | Oct 18, 2022 |
| ASRock        | H310M-STX                   | Desktop     | [56f9a169fa](https://linux-hardware.org/?probe=56f9a169fa) | Oct 18, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [f7f13866aa](https://linux-hardware.org/?probe=f7f13866aa) | Oct 18, 2022 |
| Dell          | Latitude 7300               | Notebook    | [c9bc03da26](https://linux-hardware.org/?probe=c9bc03da26) | Oct 18, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [fde830d956](https://linux-hardware.org/?probe=fde830d956) | Oct 18, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [db3ce64578](https://linux-hardware.org/?probe=db3ce64578) | Oct 18, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [621cca0fca](https://linux-hardware.org/?probe=621cca0fca) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | Notebook    | [aff8f19a59](https://linux-hardware.org/?probe=aff8f19a59) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | Notebook    | [c33d20c223](https://linux-hardware.org/?probe=c33d20c223) | Oct 18, 2022 |
| HP            | Pavilion dv7                | Notebook    | [bb650e8400](https://linux-hardware.org/?probe=bb650e8400) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e61760eab3](https://linux-hardware.org/?probe=e61760eab3) | Oct 18, 2022 |
| Dell          | Precision 3570              | Notebook    | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| ASUSTek       | F9S                         | Notebook    | [c8df776935](https://linux-hardware.org/?probe=c8df776935) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bbff53957f](https://linux-hardware.org/?probe=bbff53957f) | Oct 17, 2022 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [359822ae5f](https://linux-hardware.org/?probe=359822ae5f) | Oct 17, 2022 |
| Gigabyte      | 970A-D3                     | Desktop     | [9f5d48a7c6](https://linux-hardware.org/?probe=9f5d48a7c6) | Oct 17, 2022 |
| Dell          | G3 3500                     | Notebook    | [64698d52bb](https://linux-hardware.org/?probe=64698d52bb) | Oct 17, 2022 |
| Dell          | G3 3500                     | Notebook    | [902fc2d51b](https://linux-hardware.org/?probe=902fc2d51b) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [10bcc184e7](https://linux-hardware.org/?probe=10bcc184e7) | Oct 17, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [fca234fc49](https://linux-hardware.org/?probe=fca234fc49) | Oct 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [a4ebad3748](https://linux-hardware.org/?probe=a4ebad3748) | Oct 17, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [28d9942c9f](https://linux-hardware.org/?probe=28d9942c9f) | Oct 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [9e37b60507](https://linux-hardware.org/?probe=9e37b60507) | Oct 16, 2022 |
| Lenovo        | 3307 NOK                    | Mini pc     | [df054eec71](https://linux-hardware.org/?probe=df054eec71) | Oct 16, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [a88a291921](https://linux-hardware.org/?probe=a88a291921) | Oct 16, 2022 |
| ASUSTek       | M70Vn                       | Notebook    | [e9301bdee2](https://linux-hardware.org/?probe=e9301bdee2) | Oct 16, 2022 |
| Dell          | Latitude 3500               | Notebook    | [d578b45420](https://linux-hardware.org/?probe=d578b45420) | Oct 16, 2022 |
| Dell          | Latitude E5420              | Notebook    | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| HP            | ENVY 17                     | Notebook    | [ab25d54223](https://linux-hardware.org/?probe=ab25d54223) | Oct 16, 2022 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [c210cda35b](https://linux-hardware.org/?probe=c210cda35b) | Oct 16, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [d73a82b798](https://linux-hardware.org/?probe=d73a82b798) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [7559400f9a](https://linux-hardware.org/?probe=7559400f9a) | Oct 15, 2022 |
| ASUSTek       | X751NV                      | Notebook    | [174ee8f3e7](https://linux-hardware.org/?probe=174ee8f3e7) | Oct 15, 2022 |
| HP            | 1850                        | Desktop     | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [645c7a01da](https://linux-hardware.org/?probe=645c7a01da) | Oct 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| Acer          | AOD257                      | Notebook    | [41a717913c](https://linux-hardware.org/?probe=41a717913c) | Oct 15, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [5038f48b66](https://linux-hardware.org/?probe=5038f48b66) | Oct 15, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [1a0ed356d7](https://linux-hardware.org/?probe=1a0ed356d7) | Oct 15, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [3f3d531577](https://linux-hardware.org/?probe=3f3d531577) | Oct 15, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [4796b36078](https://linux-hardware.org/?probe=4796b36078) | Oct 15, 2022 |
| Acer          | Aspire 7740                 | Notebook    | [a68780a6fd](https://linux-hardware.org/?probe=a68780a6fd) | Oct 15, 2022 |
| Lenovo        | ThinkPad L420 78545EG       | Notebook    | [d2c975644c](https://linux-hardware.org/?probe=d2c975644c) | Oct 15, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [aee52607f0](https://linux-hardware.org/?probe=aee52607f0) | Oct 14, 2022 |
| Medion        | MS-7797                     | Desktop     | [c6174b67dd](https://linux-hardware.org/?probe=c6174b67dd) | Oct 14, 2022 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [ebada4e791](https://linux-hardware.org/?probe=ebada4e791) | Oct 14, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [85766540b3](https://linux-hardware.org/?probe=85766540b3) | Oct 14, 2022 |
| Lenovo        | 3307 NOK                    | Mini pc     | [5bb64d91e9](https://linux-hardware.org/?probe=5bb64d91e9) | Oct 14, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [06e46e98b4](https://linux-hardware.org/?probe=06e46e98b4) | Oct 14, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [5a0485a292](https://linux-hardware.org/?probe=5a0485a292) | Oct 14, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [b93a697af0](https://linux-hardware.org/?probe=b93a697af0) | Oct 14, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [fd260f87a9](https://linux-hardware.org/?probe=fd260f87a9) | Oct 14, 2022 |
| Dell          | G3 3500                     | Notebook    | [f7cc47bb67](https://linux-hardware.org/?probe=f7cc47bb67) | Oct 13, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| Pegatron      | 2A94                        | Desktop     | [038d49b359](https://linux-hardware.org/?probe=038d49b359) | Oct 13, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [fe9dde997d](https://linux-hardware.org/?probe=fe9dde997d) | Oct 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [8a680cbcbe](https://linux-hardware.org/?probe=8a680cbcbe) | Oct 13, 2022 |
| MSI           | Z87 XPOWER                  | Desktop     | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| MSI           | GE70 2QE                    | Notebook    | [2825343a52](https://linux-hardware.org/?probe=2825343a52) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [d1c1c4adea](https://linux-hardware.org/?probe=d1c1c4adea) | Oct 13, 2022 |
| Lenovo        | ThinkCentre M71e 3167B28    | Desktop     | [0cfbd3c2fc](https://linux-hardware.org/?probe=0cfbd3c2fc) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34481... | Notebook    | [adce18affa](https://linux-hardware.org/?probe=adce18affa) | Oct 13, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [679af656c1](https://linux-hardware.org/?probe=679af656c1) | Oct 13, 2022 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [2be4dc3fc2](https://linux-hardware.org/?probe=2be4dc3fc2) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [dfc5a5f754](https://linux-hardware.org/?probe=dfc5a5f754) | Oct 13, 2022 |
| Dell          | Latitude E5550              | Notebook    | [fc1fa79f81](https://linux-hardware.org/?probe=fc1fa79f81) | Oct 13, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [2656af4553](https://linux-hardware.org/?probe=2656af4553) | Oct 13, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [d170871784](https://linux-hardware.org/?probe=d170871784) | Oct 13, 2022 |
| MSI           | B360I GMAING PRO AC         | Desktop     | [2584a31610](https://linux-hardware.org/?probe=2584a31610) | Oct 12, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [f1fcb66794](https://linux-hardware.org/?probe=f1fcb66794) | Oct 12, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [9744660229](https://linux-hardware.org/?probe=9744660229) | Oct 12, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| ASUSTek       | M70Vn                       | Notebook    | [62cb9744e6](https://linux-hardware.org/?probe=62cb9744e6) | Oct 12, 2022 |
| Thomson       | N14C4WH64                   | Notebook    | [bfc16b9ded](https://linux-hardware.org/?probe=bfc16b9ded) | Oct 12, 2022 |
| eMachines     | EL1352                      | Desktop     | [ff2899db03](https://linux-hardware.org/?probe=ff2899db03) | Oct 11, 2022 |
| ASUSTek       | M32CD4-K                    | Desktop     | [0e8ec5b69d](https://linux-hardware.org/?probe=0e8ec5b69d) | Oct 11, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [1680fa50c0](https://linux-hardware.org/?probe=1680fa50c0) | Oct 11, 2022 |
| ASUSTek       | N53Jg                       | Notebook    | [0b4302ed6c](https://linux-hardware.org/?probe=0b4302ed6c) | Oct 11, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [cbadb49ecd](https://linux-hardware.org/?probe=cbadb49ecd) | Oct 11, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [33c86327c4](https://linux-hardware.org/?probe=33c86327c4) | Oct 11, 2022 |
| Dell          | Latitude E6410              | Notebook    | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| Lenovo        | ThinkCentre M58 7359WES     | Desktop     | [1c00ee45c1](https://linux-hardware.org/?probe=1c00ee45c1) | Oct 11, 2022 |
| eMachines     | EL1352                      | Desktop     | [805958ae53](https://linux-hardware.org/?probe=805958ae53) | Oct 11, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [4eacf977db](https://linux-hardware.org/?probe=4eacf977db) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [3341f329c9](https://linux-hardware.org/?probe=3341f329c9) | Oct 11, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [92ab2501ea](https://linux-hardware.org/?probe=92ab2501ea) | Oct 11, 2022 |
| Acer          | Aspire XC-230               | Desktop     | [d213bca85f](https://linux-hardware.org/?probe=d213bca85f) | Oct 10, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f96c4889db](https://linux-hardware.org/?probe=f96c4889db) | Oct 10, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [b90b027e31](https://linux-hardware.org/?probe=b90b027e31) | Oct 10, 2022 |
| AOpen         | D1007 0BBA                  | Desktop     | [b3597a7cbc](https://linux-hardware.org/?probe=b3597a7cbc) | Oct 10, 2022 |
| Letni         | Z156                        | Notebook    | [994c588906](https://linux-hardware.org/?probe=994c588906) | Oct 10, 2022 |
| Dell          | Latitude 5400               | Notebook    | [ff8eb160c9](https://linux-hardware.org/?probe=ff8eb160c9) | Oct 10, 2022 |
| HP            | Notebook                    | Notebook    | [2fd3bd5ee0](https://linux-hardware.org/?probe=2fd3bd5ee0) | Oct 10, 2022 |
| Alienware     | m15 R7                      | Notebook    | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| Lenovo        | Dory CRB                    | Desktop     | [33ae78632a](https://linux-hardware.org/?probe=33ae78632a) | Oct 09, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [900e75392f](https://linux-hardware.org/?probe=900e75392f) | Oct 09, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [ec2b212e33](https://linux-hardware.org/?probe=ec2b212e33) | Oct 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [fef2c17618](https://linux-hardware.org/?probe=fef2c17618) | Oct 09, 2022 |
| Dell          | Inspiron 16 7610            | Notebook    | [fddf8f17bd](https://linux-hardware.org/?probe=fddf8f17bd) | Oct 08, 2022 |
| Dell          | 0NV103 A00                  | All in one  | [092f9c7f2b](https://linux-hardware.org/?probe=092f9c7f2b) | Oct 08, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [58d2cda88f](https://linux-hardware.org/?probe=58d2cda88f) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [72f51c852d](https://linux-hardware.org/?probe=72f51c852d) | Oct 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [8f1aa49dc2](https://linux-hardware.org/?probe=8f1aa49dc2) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [1b720b4302](https://linux-hardware.org/?probe=1b720b4302) | Oct 08, 2022 |
| Lenovo        | ThinkCentre M71z 1741A7G    | Desktop     | [805de67dc2](https://linux-hardware.org/?probe=805de67dc2) | Oct 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| Lenovo        | ThinkCentre M71z 1741A7G    | Desktop     | [900d02c2ab](https://linux-hardware.org/?probe=900d02c2ab) | Oct 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2643af430d](https://linux-hardware.org/?probe=2643af430d) | Oct 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [f8bf937f1e](https://linux-hardware.org/?probe=f8bf937f1e) | Oct 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [ac8df9496c](https://linux-hardware.org/?probe=ac8df9496c) | Oct 08, 2022 |
| HP            | 3396                        | Desktop     | [c5924b78db](https://linux-hardware.org/?probe=c5924b78db) | Oct 08, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [9f434d86be](https://linux-hardware.org/?probe=9f434d86be) | Oct 08, 2022 |
| MSI           | H81M-E34                    | Desktop     | [154cb109bf](https://linux-hardware.org/?probe=154cb109bf) | Oct 08, 2022 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [5b543dbd16](https://linux-hardware.org/?probe=5b543dbd16) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9525ea0de3](https://linux-hardware.org/?probe=9525ea0de3) | Oct 07, 2022 |
| Acer          | Swift SF314-51              | Notebook    | [cfc56878f0](https://linux-hardware.org/?probe=cfc56878f0) | Oct 07, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| Clevo         | W2xxHSQ                     | Notebook    | [3a05b61e0b](https://linux-hardware.org/?probe=3a05b61e0b) | Oct 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [e6eac5c882](https://linux-hardware.org/?probe=e6eac5c882) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8901403de4](https://linux-hardware.org/?probe=8901403de4) | Oct 07, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [ae56e506c3](https://linux-hardware.org/?probe=ae56e506c3) | Oct 06, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c1c51b96ef](https://linux-hardware.org/?probe=c1c51b96ef) | Oct 06, 2022 |
| Dell          | Latitude 7300               | Notebook    | [3eb18574b3](https://linux-hardware.org/?probe=3eb18574b3) | Oct 06, 2022 |
| ASUSTek       | X550LA                      | Notebook    | [c0c98c2051](https://linux-hardware.org/?probe=c0c98c2051) | Oct 06, 2022 |
| Dell          | Latitude 7480               | Notebook    | [aa3f8d08a6](https://linux-hardware.org/?probe=aa3f8d08a6) | Oct 06, 2022 |
| HP            | 3398                        | Desktop     | [c70e10b68b](https://linux-hardware.org/?probe=c70e10b68b) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| PC Special... | PCX0DX                      | Notebook    | [35e44699ff](https://linux-hardware.org/?probe=35e44699ff) | Oct 06, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [8b9d7f32d1](https://linux-hardware.org/?probe=8b9d7f32d1) | Oct 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| Sony          | VGN-SZ3XP_C                 | Notebook    | [f4fd751216](https://linux-hardware.org/?probe=f4fd751216) | Oct 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [85eb59fc6d](https://linux-hardware.org/?probe=85eb59fc6d) | Oct 05, 2022 |
| Dell          | Latitude 7300               | Notebook    | [a57bc6e1a5](https://linux-hardware.org/?probe=a57bc6e1a5) | Oct 05, 2022 |
| HP            | Compaq 15                   | Notebook    | [bba22531ad](https://linux-hardware.org/?probe=bba22531ad) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7590ca8bff](https://linux-hardware.org/?probe=7590ca8bff) | Oct 05, 2022 |
| Lenovo        | ThinkPad L430 24641J9       | Notebook    | [4f4932300b](https://linux-hardware.org/?probe=4f4932300b) | Oct 05, 2022 |
| HP            | Compaq 15                   | Notebook    | [0f48335990](https://linux-hardware.org/?probe=0f48335990) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [bdb441bda7](https://linux-hardware.org/?probe=bdb441bda7) | Oct 04, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [b56c08cbcf](https://linux-hardware.org/?probe=b56c08cbcf) | Oct 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [33b42f3ed1](https://linux-hardware.org/?probe=33b42f3ed1) | Oct 04, 2022 |
| Jumper        | Ezpad                       | Tablet      | [20a54bbe35](https://linux-hardware.org/?probe=20a54bbe35) | Oct 04, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [3a644dd82f](https://linux-hardware.org/?probe=3a644dd82f) | Oct 04, 2022 |
| HP            | ZBook 14u G6                | Notebook    | [87437a85a7](https://linux-hardware.org/?probe=87437a85a7) | Oct 04, 2022 |
| Jumper        | Ezpad                       | Tablet      | [a887c036ac](https://linux-hardware.org/?probe=a887c036ac) | Oct 04, 2022 |
| MSI           | CR61 3M                     | Notebook    | [496910c25b](https://linux-hardware.org/?probe=496910c25b) | Oct 04, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [326db47f49](https://linux-hardware.org/?probe=326db47f49) | Oct 04, 2022 |
| Medion        | E7214                       | Notebook    | [c4ee9367cf](https://linux-hardware.org/?probe=c4ee9367cf) | Oct 04, 2022 |
| Medion        | E7214                       | Notebook    | [e8e78221ca](https://linux-hardware.org/?probe=e8e78221ca) | Oct 04, 2022 |
| Dell          | Latitude E6230              | Notebook    | [a4af37beac](https://linux-hardware.org/?probe=a4af37beac) | Oct 04, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [38f5b56e5d](https://linux-hardware.org/?probe=38f5b56e5d) | Oct 04, 2022 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [54083a4f07](https://linux-hardware.org/?probe=54083a4f07) | Oct 04, 2022 |
| ASUSTek       | G15DK                       | Desktop     | [3c8be02775](https://linux-hardware.org/?probe=3c8be02775) | Oct 04, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [eb1ee8ad1f](https://linux-hardware.org/?probe=eb1ee8ad1f) | Oct 04, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [84fbbaf62c](https://linux-hardware.org/?probe=84fbbaf62c) | Oct 04, 2022 |
| Lenovo        | B590 62743BG                | Notebook    | [8c120b5fea](https://linux-hardware.org/?probe=8c120b5fea) | Oct 03, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [5a5aada87f](https://linux-hardware.org/?probe=5a5aada87f) | Oct 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [cc0d33aedb](https://linux-hardware.org/?probe=cc0d33aedb) | Oct 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [81ac41d8b9](https://linux-hardware.org/?probe=81ac41d8b9) | Oct 03, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [bc9c9eb996](https://linux-hardware.org/?probe=bc9c9eb996) | Oct 03, 2022 |
| ASUSTek       | G15DK                       | Desktop     | [76a03b7071](https://linux-hardware.org/?probe=76a03b7071) | Oct 03, 2022 |
| Dell          | 0NDYHG A01                  | Desktop     | [a43be6f15b](https://linux-hardware.org/?probe=a43be6f15b) | Oct 03, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [4af26bb39b](https://linux-hardware.org/?probe=4af26bb39b) | Oct 03, 2022 |
| Dell          | 0CRH6C A00                  | Desktop     | [72bd267fdc](https://linux-hardware.org/?probe=72bd267fdc) | Oct 03, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [5bcba21765](https://linux-hardware.org/?probe=5bcba21765) | Oct 03, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [2209533c27](https://linux-hardware.org/?probe=2209533c27) | Oct 03, 2022 |
| Dell          | Latitude 7300               | Notebook    | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Dell          | Precision 5560              | Notebook    | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Sony          | VPCSB1S1E                   | Notebook    | [b85b92339b](https://linux-hardware.org/?probe=b85b92339b) | Oct 03, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2f9e023d1e](https://linux-hardware.org/?probe=2f9e023d1e) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [48e867fba8](https://linux-hardware.org/?probe=48e867fba8) | Oct 02, 2022 |
| Dell          | Latitude 7490               | Notebook    | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| ASUSTek       | M4A78LT-LE                  | Desktop     | [3ff1278fbe](https://linux-hardware.org/?probe=3ff1278fbe) | Oct 02, 2022 |
| Dell          | Latitude E6410              | Notebook    | [7f89aefd99](https://linux-hardware.org/?probe=7f89aefd99) | Oct 02, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c03bbc1dfb](https://linux-hardware.org/?probe=c03bbc1dfb) | Oct 02, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [73aab58eda](https://linux-hardware.org/?probe=73aab58eda) | Oct 02, 2022 |
| Lenovo        | ThinkPad R500 27148UG       | Notebook    | [1c968e44cb](https://linux-hardware.org/?probe=1c968e44cb) | Oct 02, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [ee5752ed3f](https://linux-hardware.org/?probe=ee5752ed3f) | Oct 02, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6121fee541](https://linux-hardware.org/?probe=6121fee541) | Oct 02, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [80a2948ff1](https://linux-hardware.org/?probe=80a2948ff1) | Oct 02, 2022 |
| Sony          | VGN-SZ3XP_C                 | Notebook    | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [43694e5952](https://linux-hardware.org/?probe=43694e5952) | Oct 02, 2022 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [e513ef6b84](https://linux-hardware.org/?probe=e513ef6b84) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| Dell          | Latitude E6510              | Notebook    | [71b8d3743e](https://linux-hardware.org/?probe=71b8d3743e) | Oct 02, 2022 |
| ASUSTek       | M32CD4-K                    | Desktop     | [dd34ecfa95](https://linux-hardware.org/?probe=dd34ecfa95) | Oct 02, 2022 |
| ASUSTek       | M32CD4-K                    | Desktop     | [cbddf3b882](https://linux-hardware.org/?probe=cbddf3b882) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [d0a30f35b6](https://linux-hardware.org/?probe=d0a30f35b6) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [e192869dc8](https://linux-hardware.org/?probe=e192869dc8) | Oct 02, 2022 |
| ASUSTek       | X71Q                        | Notebook    | [830c8ab6d2](https://linux-hardware.org/?probe=830c8ab6d2) | Oct 02, 2022 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [b9f2861719](https://linux-hardware.org/?probe=b9f2861719) | Oct 02, 2022 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [5c4c517651](https://linux-hardware.org/?probe=5c4c517651) | Oct 02, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [3f70868547](https://linux-hardware.org/?probe=3f70868547) | Oct 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1043db8cf](https://linux-hardware.org/?probe=e1043db8cf) | Oct 02, 2022 |
| MSI           | CR61 3M                     | Notebook    | [818a721825](https://linux-hardware.org/?probe=818a721825) | Oct 02, 2022 |
| HP            | Pavilion dv7                | Notebook    | [2da8f083a7](https://linux-hardware.org/?probe=2da8f083a7) | Oct 01, 2022 |
| MSI           | B360I GMAING PRO AC         | Desktop     | [bbdf7b4f77](https://linux-hardware.org/?probe=bbdf7b4f77) | Oct 01, 2022 |
| Unknown       | X79-P3                      | Desktop     | [9269fd5ff4](https://linux-hardware.org/?probe=9269fd5ff4) | Oct 01, 2022 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [537828a21f](https://linux-hardware.org/?probe=537828a21f) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [014d8c23f8](https://linux-hardware.org/?probe=014d8c23f8) | Oct 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [462f9bbdbe](https://linux-hardware.org/?probe=462f9bbdbe) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Dell          | 0RW203                      | Desktop     | [c8a408311d](https://linux-hardware.org/?probe=c8a408311d) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [dda857d7e6](https://linux-hardware.org/?probe=dda857d7e6) | Oct 01, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [53e99a8ce6](https://linux-hardware.org/?probe=53e99a8ce6) | Oct 01, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [1cfda531dd](https://linux-hardware.org/?probe=1cfda531dd) | Oct 01, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [6f96dc34e2](https://linux-hardware.org/?probe=6f96dc34e2) | Oct 01, 2022 |
| ASUSTek       | B75M-A                      | Desktop     | [cbeab03cbd](https://linux-hardware.org/?probe=cbeab03cbd) | Oct 01, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [d967f57569](https://linux-hardware.org/?probe=d967f57569) | Oct 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [24aefc4138](https://linux-hardware.org/?probe=24aefc4138) | Oct 01, 2022 |
| Shuttle       | FS35V4                      | Desktop     | [e38fd71e40](https://linux-hardware.org/?probe=e38fd71e40) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [571271ed93](https://linux-hardware.org/?probe=571271ed93) | Sep 30, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [9da1f3fe66](https://linux-hardware.org/?probe=9da1f3fe66) | Sep 30, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8e301a5e4e](https://linux-hardware.org/?probe=8e301a5e4e) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Pegatron      | 2A94                        | Desktop     | [6425f7a434](https://linux-hardware.org/?probe=6425f7a434) | Sep 30, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [aa49a31777](https://linux-hardware.org/?probe=aa49a31777) | Sep 30, 2022 |
| HP            | ProBook 6570b               | Notebook    | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [47c190b6e9](https://linux-hardware.org/?probe=47c190b6e9) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [5a8032ee05](https://linux-hardware.org/?probe=5a8032ee05) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [4e9248b1eb](https://linux-hardware.org/?probe=4e9248b1eb) | Sep 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [786e0c1f5d](https://linux-hardware.org/?probe=786e0c1f5d) | Sep 30, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [1669dae0a6](https://linux-hardware.org/?probe=1669dae0a6) | Sep 30, 2022 |
| Toshiba       | Satellite L670              | Notebook    | [3b3e7965a5](https://linux-hardware.org/?probe=3b3e7965a5) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [a7d5bbb754](https://linux-hardware.org/?probe=a7d5bbb754) | Sep 29, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5f261094bf](https://linux-hardware.org/?probe=5f261094bf) | Sep 29, 2022 |
| TUXEDO        | Book_XA1510                 | Notebook    | [f39b64916d](https://linux-hardware.org/?probe=f39b64916d) | Sep 29, 2022 |
| Acer          | Predator G6-710             | Desktop     | [12fd4575f7](https://linux-hardware.org/?probe=12fd4575f7) | Sep 29, 2022 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [0cbacebb95](https://linux-hardware.org/?probe=0cbacebb95) | Sep 29, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [1ad22cf7a8](https://linux-hardware.org/?probe=1ad22cf7a8) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [f758c22d98](https://linux-hardware.org/?probe=f758c22d98) | Sep 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [d5185ee60b](https://linux-hardware.org/?probe=d5185ee60b) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [b08fc47990](https://linux-hardware.org/?probe=b08fc47990) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [262a244d81](https://linux-hardware.org/?probe=262a244d81) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [30507c8461](https://linux-hardware.org/?probe=30507c8461) | Sep 27, 2022 |
| Dell          | Latitude E6540              | Notebook    | [27c854b1a0](https://linux-hardware.org/?probe=27c854b1a0) | Sep 27, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [ec59847e5b](https://linux-hardware.org/?probe=ec59847e5b) | Sep 27, 2022 |
| Lenovo        | ThinkStation S30 056839G    | Desktop     | [427d10a5ca](https://linux-hardware.org/?probe=427d10a5ca) | Sep 27, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [5168af6134](https://linux-hardware.org/?probe=5168af6134) | Sep 27, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [356dc77824](https://linux-hardware.org/?probe=356dc77824) | Sep 27, 2022 |
| Dell          | Latitude E5250              | Notebook    | [6116460e52](https://linux-hardware.org/?probe=6116460e52) | Sep 27, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [8e872a0556](https://linux-hardware.org/?probe=8e872a0556) | Sep 27, 2022 |
| HP            | 0A60h                       | Desktop     | [ccb90a4b31](https://linux-hardware.org/?probe=ccb90a4b31) | Sep 27, 2022 |
| Dell          | 0NV103 A00                  | All in one  | [62a89ede99](https://linux-hardware.org/?probe=62a89ede99) | Sep 27, 2022 |
| Timi          | TM1604                      | Notebook    | [2ee795db1a](https://linux-hardware.org/?probe=2ee795db1a) | Sep 27, 2022 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [37d9172163](https://linux-hardware.org/?probe=37d9172163) | Sep 26, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [378e1d3133](https://linux-hardware.org/?probe=378e1d3133) | Sep 26, 2022 |
| Packard Be... | EasyNote LS44SB             | Notebook    | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| Insyde        | WindTab89                   | Notebook    | [0073af9597](https://linux-hardware.org/?probe=0073af9597) | Sep 26, 2022 |
| Insyde        | WindTab89                   | Notebook    | [6935ebecaa](https://linux-hardware.org/?probe=6935ebecaa) | Sep 26, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [202e51c5d3](https://linux-hardware.org/?probe=202e51c5d3) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [291b07ce5f](https://linux-hardware.org/?probe=291b07ce5f) | Sep 26, 2022 |
| HP            | Spectre Pro x360 G2         | Notebook    | [d9248f7b2e](https://linux-hardware.org/?probe=d9248f7b2e) | Sep 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [109d0ef34c](https://linux-hardware.org/?probe=109d0ef34c) | Sep 26, 2022 |
| MSI           | C847IS-P33                  | Desktop     | [9b2205d329](https://linux-hardware.org/?probe=9b2205d329) | Sep 25, 2022 |
| Acer          | Aspire 3810T                | Notebook    | [de19c5a7e9](https://linux-hardware.org/?probe=de19c5a7e9) | Sep 25, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [53c469011c](https://linux-hardware.org/?probe=53c469011c) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [c6c3ce5c04](https://linux-hardware.org/?probe=c6c3ce5c04) | Sep 25, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [c65cbf84dc](https://linux-hardware.org/?probe=c65cbf84dc) | Sep 25, 2022 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [a7aadaeed0](https://linux-hardware.org/?probe=a7aadaeed0) | Sep 25, 2022 |
| ASUSTek       | G10AJ                       | Desktop     | [bf77a2476d](https://linux-hardware.org/?probe=bf77a2476d) | Sep 25, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [2d7ce63bce](https://linux-hardware.org/?probe=2d7ce63bce) | Sep 25, 2022 |
| Acer          | Aspire SW5-012              | Notebook    | [ed8f3f7403](https://linux-hardware.org/?probe=ed8f3f7403) | Sep 25, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [1d76ae9f44](https://linux-hardware.org/?probe=1d76ae9f44) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Dell          | 0C7195                      | Desktop     | [9711ab00d7](https://linux-hardware.org/?probe=9711ab00d7) | Sep 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [8a734f0799](https://linux-hardware.org/?probe=8a734f0799) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [61dd74082f](https://linux-hardware.org/?probe=61dd74082f) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d07b0cb7a0](https://linux-hardware.org/?probe=d07b0cb7a0) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | Notebook    | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| Acidanther... | Mac-A369DDC4E67F1C45 iMa... | All in one  | [0e9b82f312](https://linux-hardware.org/?probe=0e9b82f312) | Sep 24, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [33398b1a21](https://linux-hardware.org/?probe=33398b1a21) | Sep 23, 2022 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [8a4819f23d](https://linux-hardware.org/?probe=8a4819f23d) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [1553f6266c](https://linux-hardware.org/?probe=1553f6266c) | Sep 23, 2022 |
| Intel         | NUC8BEB J72688-309          | Mini pc     | [7d035aef45](https://linux-hardware.org/?probe=7d035aef45) | Sep 23, 2022 |
| Dell          | XPS 9320                    | Notebook    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| Dell          | Precision 3561              | Notebook    | [78b8d776ed](https://linux-hardware.org/?probe=78b8d776ed) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7d69f0c6c6](https://linux-hardware.org/?probe=7d69f0c6c6) | Sep 23, 2022 |
| Notebook      | NL40_50GU                   | Notebook    | [da07f4c223](https://linux-hardware.org/?probe=da07f4c223) | Sep 23, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [7e3170527c](https://linux-hardware.org/?probe=7e3170527c) | Sep 22, 2022 |
| Dell          | Precision 5540              | Notebook    | [0f09e447ea](https://linux-hardware.org/?probe=0f09e447ea) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | Notebook    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| ASUSTek       | UX510UXK                    | Notebook    | [baa57d8e16](https://linux-hardware.org/?probe=baa57d8e16) | Sep 21, 2022 |
| Lenovo        | ThinkPad Edge E320 1298A... | Notebook    | [869b076838](https://linux-hardware.org/?probe=869b076838) | Sep 21, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [5e4d865987](https://linux-hardware.org/?probe=5e4d865987) | Sep 21, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [ba47323a29](https://linux-hardware.org/?probe=ba47323a29) | Sep 21, 2022 |
| HPE           | ProLiant DL385 Gen10 Plu... | Server      | [9a0a9c455a](https://linux-hardware.org/?probe=9a0a9c455a) | Sep 21, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [49b3253936](https://linux-hardware.org/?probe=49b3253936) | Sep 21, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Dell          | Precision 7540              | Notebook    | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [e234a2b52a](https://linux-hardware.org/?probe=e234a2b52a) | Sep 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [982931b71f](https://linux-hardware.org/?probe=982931b71f) | Sep 21, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [facc4c1755](https://linux-hardware.org/?probe=facc4c1755) | Sep 21, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [98d21fb774](https://linux-hardware.org/?probe=98d21fb774) | Sep 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [6d0a2986ad](https://linux-hardware.org/?probe=6d0a2986ad) | Sep 21, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a454bf3aa7](https://linux-hardware.org/?probe=a454bf3aa7) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [3aeb184ce4](https://linux-hardware.org/?probe=3aeb184ce4) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [5d42a6abab](https://linux-hardware.org/?probe=5d42a6abab) | Sep 20, 2022 |
| Toshiba       | Satellite L875-11M          | Notebook    | [42f3498e9e](https://linux-hardware.org/?probe=42f3498e9e) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | Notebook    | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [180561f253](https://linux-hardware.org/?probe=180561f253) | Sep 20, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [3c8fefe578](https://linux-hardware.org/?probe=3c8fefe578) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [83ed33f7e6](https://linux-hardware.org/?probe=83ed33f7e6) | Sep 20, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [1975320cad](https://linux-hardware.org/?probe=1975320cad) | Sep 20, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [c6320d5d3c](https://linux-hardware.org/?probe=c6320d5d3c) | Sep 20, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [635c6895e1](https://linux-hardware.org/?probe=635c6895e1) | Sep 20, 2022 |
| Lenovo        | 3728 SDK0R32862 WIN 3258... | Desktop     | [d78d85bde3](https://linux-hardware.org/?probe=d78d85bde3) | Sep 20, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [bb0b1764e0](https://linux-hardware.org/?probe=bb0b1764e0) | Sep 19, 2022 |
| PC Special... | NS50MU                      | Notebook    | [1843dfbb66](https://linux-hardware.org/?probe=1843dfbb66) | Sep 19, 2022 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [89894daeb7](https://linux-hardware.org/?probe=89894daeb7) | Sep 19, 2022 |
| Dell          | 0XC837                      | Desktop     | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| Dell          | Precision 7750              | Notebook    | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| HP            | 470 G7 Notebook PC          | Notebook    | [a9f6ad0c32](https://linux-hardware.org/?probe=a9f6ad0c32) | Sep 19, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [df362e9796](https://linux-hardware.org/?probe=df362e9796) | Sep 18, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [a251261add](https://linux-hardware.org/?probe=a251261add) | Sep 18, 2022 |
| Lenovo        | ThinkPad X200 7458VL3       | Notebook    | [700ff6630e](https://linux-hardware.org/?probe=700ff6630e) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [b94564300a](https://linux-hardware.org/?probe=b94564300a) | Sep 18, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [aa3908e5fc](https://linux-hardware.org/?probe=aa3908e5fc) | Sep 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a06139b33d](https://linux-hardware.org/?probe=a06139b33d) | Sep 17, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [fde2d03f98](https://linux-hardware.org/?probe=fde2d03f98) | Sep 17, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [88fdbf1a94](https://linux-hardware.org/?probe=88fdbf1a94) | Sep 16, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [3ace24ebfc](https://linux-hardware.org/?probe=3ace24ebfc) | Sep 16, 2022 |
| Dell          | Latitude E5540              | Notebook    | [8e44a11e6c](https://linux-hardware.org/?probe=8e44a11e6c) | Sep 16, 2022 |
| Dell          | Latitude E5540              | Notebook    | [c2d57deba4](https://linux-hardware.org/?probe=c2d57deba4) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [47ac328960](https://linux-hardware.org/?probe=47ac328960) | Sep 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [7a390e81b1](https://linux-hardware.org/?probe=7a390e81b1) | Sep 16, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [b136916fb3](https://linux-hardware.org/?probe=b136916fb3) | Sep 16, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [cba8ef504c](https://linux-hardware.org/?probe=cba8ef504c) | Sep 16, 2022 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [f543e0852f](https://linux-hardware.org/?probe=f543e0852f) | Sep 16, 2022 |
| Lenovo        | ThinkPad T440s 20ARS0CN1... | Notebook    | [2f9eaf5711](https://linux-hardware.org/?probe=2f9eaf5711) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [382325db11](https://linux-hardware.org/?probe=382325db11) | Sep 16, 2022 |
| ASUSTek       | X550JK                      | Notebook    | [5c399f4fb0](https://linux-hardware.org/?probe=5c399f4fb0) | Sep 15, 2022 |
| ASUSTek       | X550JK                      | Notebook    | [59df382a23](https://linux-hardware.org/?probe=59df382a23) | Sep 15, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | Notebook    | [1a1ae1e398](https://linux-hardware.org/?probe=1a1ae1e398) | Sep 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c99c4f9785](https://linux-hardware.org/?probe=c99c4f9785) | Sep 15, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [bc275a0476](https://linux-hardware.org/?probe=bc275a0476) | Sep 15, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | Notebook    | [84dee7df6c](https://linux-hardware.org/?probe=84dee7df6c) | Sep 15, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [a803a04b1f](https://linux-hardware.org/?probe=a803a04b1f) | Sep 15, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [50f0cfbfad](https://linux-hardware.org/?probe=50f0cfbfad) | Sep 15, 2022 |
| Dell          | Precision 3571              | Notebook    | [01f5d7f7f8](https://linux-hardware.org/?probe=01f5d7f7f8) | Sep 15, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [fc23b3a13b](https://linux-hardware.org/?probe=fc23b3a13b) | Sep 15, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [000eb38ea7](https://linux-hardware.org/?probe=000eb38ea7) | Sep 15, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [282afe0352](https://linux-hardware.org/?probe=282afe0352) | Sep 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [2d33f80fbd](https://linux-hardware.org/?probe=2d33f80fbd) | Sep 15, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [af4b9d7add](https://linux-hardware.org/?probe=af4b9d7add) | Sep 14, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| Dell          | Precision 7550              | Notebook    | [f6a8b38020](https://linux-hardware.org/?probe=f6a8b38020) | Sep 14, 2022 |
| Dell          | Inspiron 15 3520            | Notebook    | [1d74f86789](https://linux-hardware.org/?probe=1d74f86789) | Sep 14, 2022 |
| HP            | 1496                        | Desktop     | [cb6033fc21](https://linux-hardware.org/?probe=cb6033fc21) | Sep 14, 2022 |
| Dell          | Precision 3571              | Notebook    | [72e1a27ea7](https://linux-hardware.org/?probe=72e1a27ea7) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8935b3f204](https://linux-hardware.org/?probe=8935b3f204) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| HP            | 81C5 MVB                    | Desktop     | [e274dcadcd](https://linux-hardware.org/?probe=e274dcadcd) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [5784c0a7e3](https://linux-hardware.org/?probe=5784c0a7e3) | Sep 14, 2022 |
| Dell          | Precision 7520              | Notebook    | [b83fea6b96](https://linux-hardware.org/?probe=b83fea6b96) | Sep 14, 2022 |
| HP            | Pavilion dv7                | Notebook    | [f94d6a4e8f](https://linux-hardware.org/?probe=f94d6a4e8f) | Sep 14, 2022 |
| Dell          | Latitude E5550              | Notebook    | [90674e3069](https://linux-hardware.org/?probe=90674e3069) | Sep 13, 2022 |
| ASUSTek       | X750JB                      | Notebook    | [dd6137189b](https://linux-hardware.org/?probe=dd6137189b) | Sep 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P5440FA_... | Notebook    | [d441c68f40](https://linux-hardware.org/?probe=d441c68f40) | Sep 13, 2022 |
| Samsung       | 950XED                      | Notebook    | [f8a15210f0](https://linux-hardware.org/?probe=f8a15210f0) | Sep 13, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [3e00c86066](https://linux-hardware.org/?probe=3e00c86066) | Sep 13, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [8774a8312b](https://linux-hardware.org/?probe=8774a8312b) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [999cbe4e8f](https://linux-hardware.org/?probe=999cbe4e8f) | Sep 13, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [9211f5de76](https://linux-hardware.org/?probe=9211f5de76) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [0e6413e94b](https://linux-hardware.org/?probe=0e6413e94b) | Sep 13, 2022 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [5e67e25052](https://linux-hardware.org/?probe=5e67e25052) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cacc85ca2e](https://linux-hardware.org/?probe=cacc85ca2e) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0c6d5b57dd](https://linux-hardware.org/?probe=0c6d5b57dd) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [82b9d1247e](https://linux-hardware.org/?probe=82b9d1247e) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7fb82d496f](https://linux-hardware.org/?probe=7fb82d496f) | Sep 12, 2022 |
| HP            | 470 G7 Notebook PC          | Notebook    | [f1c4e72e54](https://linux-hardware.org/?probe=f1c4e72e54) | Sep 12, 2022 |
| Dell          | 0H8052                      | Desktop     | [1ade497706](https://linux-hardware.org/?probe=1ade497706) | Sep 12, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [6c88032385](https://linux-hardware.org/?probe=6c88032385) | Sep 12, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [d2ed0e3000](https://linux-hardware.org/?probe=d2ed0e3000) | Sep 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [823924f975](https://linux-hardware.org/?probe=823924f975) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [3d1d8301c3](https://linux-hardware.org/?probe=3d1d8301c3) | Sep 12, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [2b699a677b](https://linux-hardware.org/?probe=2b699a677b) | Sep 11, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [06c0b65315](https://linux-hardware.org/?probe=06c0b65315) | Sep 11, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [59d8ed6557](https://linux-hardware.org/?probe=59d8ed6557) | Sep 11, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [1b43b0d291](https://linux-hardware.org/?probe=1b43b0d291) | Sep 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [72a8c650c5](https://linux-hardware.org/?probe=72a8c650c5) | Sep 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [46c51b7097](https://linux-hardware.org/?probe=46c51b7097) | Sep 11, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [5d0092ffc1](https://linux-hardware.org/?probe=5d0092ffc1) | Sep 11, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [a683b361e4](https://linux-hardware.org/?probe=a683b361e4) | Sep 11, 2022 |
| Apple         | MacBookPro13,1              | Notebook    | [4b7f579852](https://linux-hardware.org/?probe=4b7f579852) | Sep 11, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [9cbf9fdc4a](https://linux-hardware.org/?probe=9cbf9fdc4a) | Sep 11, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [512a6bd927](https://linux-hardware.org/?probe=512a6bd927) | Sep 11, 2022 |
| HP            | 84DE                        | All in one  | [cdb6233482](https://linux-hardware.org/?probe=cdb6233482) | Sep 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [66c2198f48](https://linux-hardware.org/?probe=66c2198f48) | Sep 10, 2022 |
| Framework     | Laptop                      | Notebook    | [b0b7801b11](https://linux-hardware.org/?probe=b0b7801b11) | Sep 10, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [8df1767beb](https://linux-hardware.org/?probe=8df1767beb) | Sep 10, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [4ad8216bf8](https://linux-hardware.org/?probe=4ad8216bf8) | Sep 10, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [bfaebac5d4](https://linux-hardware.org/?probe=bfaebac5d4) | Sep 10, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [40c43aff10](https://linux-hardware.org/?probe=40c43aff10) | Sep 10, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [4911a898bd](https://linux-hardware.org/?probe=4911a898bd) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [cd84312899](https://linux-hardware.org/?probe=cd84312899) | Sep 09, 2022 |
| Dell          | 0C7195                      | Desktop     | [728b74ef0c](https://linux-hardware.org/?probe=728b74ef0c) | Sep 09, 2022 |
| Dell          | 04075X A00                  | All in one  | [e2ff438b3c](https://linux-hardware.org/?probe=e2ff438b3c) | Sep 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d946b5e886](https://linux-hardware.org/?probe=d946b5e886) | Sep 09, 2022 |
| MSI           | Z77A-G45                    | Desktop     | [e26581d20e](https://linux-hardware.org/?probe=e26581d20e) | Sep 09, 2022 |
| Dell          | Precision 7560              | Notebook    | [3e2d1a120c](https://linux-hardware.org/?probe=3e2d1a120c) | Sep 09, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [e42f779622](https://linux-hardware.org/?probe=e42f779622) | Sep 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| ASUSTek       | GL702VSK                    | Notebook    | [5001a76a0e](https://linux-hardware.org/?probe=5001a76a0e) | Sep 09, 2022 |
| Packard Be... | IMEDIA S2883                | Desktop     | [c4fe9ee6f0](https://linux-hardware.org/?probe=c4fe9ee6f0) | Sep 08, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [c8f2e1da45](https://linux-hardware.org/?probe=c8f2e1da45) | Sep 08, 2022 |
| HP            | ZBook 15                    | Notebook    | [89a1ed226b](https://linux-hardware.org/?probe=89a1ed226b) | Sep 08, 2022 |
| Nvidia        | Tegra                       | Soc         | [bf3fee013b](https://linux-hardware.org/?probe=bf3fee013b) | Sep 08, 2022 |
| System76      | Lemur                       | Notebook    | [5993c130bc](https://linux-hardware.org/?probe=5993c130bc) | Sep 07, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [c89a7d5488](https://linux-hardware.org/?probe=c89a7d5488) | Sep 07, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c75460abba](https://linux-hardware.org/?probe=c75460abba) | Sep 07, 2022 |
| Dell          | 0JCTF8 A00                  | Desktop     | [7a0145000a](https://linux-hardware.org/?probe=7a0145000a) | Sep 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [280ca4dce2](https://linux-hardware.org/?probe=280ca4dce2) | Sep 07, 2022 |
| ASUSTek       | X99-E WS                    | Desktop     | [fcf815d38f](https://linux-hardware.org/?probe=fcf815d38f) | Sep 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [9d494c5486](https://linux-hardware.org/?probe=9d494c5486) | Sep 07, 2022 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [14a3a316d5](https://linux-hardware.org/?probe=14a3a316d5) | Sep 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0efcfb2037](https://linux-hardware.org/?probe=0efcfb2037) | Sep 07, 2022 |
| Intel         | NUC9i9QNB K49243-403        | Mini pc     | [8749b43db1](https://linux-hardware.org/?probe=8749b43db1) | Sep 06, 2022 |
| MSI           | MS-7387                     | Desktop     | [1f49477abf](https://linux-hardware.org/?probe=1f49477abf) | Sep 06, 2022 |
| Dell          | Latitude 9520               | Notebook    | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [7c202a088d](https://linux-hardware.org/?probe=7c202a088d) | Sep 06, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [7e1557713a](https://linux-hardware.org/?probe=7e1557713a) | Sep 06, 2022 |
| HP            | 843B                        | Desktop     | [55206c17b9](https://linux-hardware.org/?probe=55206c17b9) | Sep 06, 2022 |
| Lenovo        | ThinkPad L440 20ASS11T00    | Notebook    | [526d97c730](https://linux-hardware.org/?probe=526d97c730) | Sep 06, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [6098d39f63](https://linux-hardware.org/?probe=6098d39f63) | Sep 05, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a132b449e4](https://linux-hardware.org/?probe=a132b449e4) | Sep 05, 2022 |
| Dell          | 0N36HY A06                  | Server      | [ad80e5c56d](https://linux-hardware.org/?probe=ad80e5c56d) | Sep 05, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [d9a3103936](https://linux-hardware.org/?probe=d9a3103936) | Sep 05, 2022 |
| Dell          | 06JWJY A00                  | Desktop     | [a5f1112e93](https://linux-hardware.org/?probe=a5f1112e93) | Sep 05, 2022 |
| Dell          | 06FW8P A00                  | Desktop     | [6023e5aa76](https://linux-hardware.org/?probe=6023e5aa76) | Sep 05, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6810a0954f](https://linux-hardware.org/?probe=6810a0954f) | Sep 05, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [2d99107aa6](https://linux-hardware.org/?probe=2d99107aa6) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| Dell          | 0N36HY A06                  | Server      | [e50147dafa](https://linux-hardware.org/?probe=e50147dafa) | Sep 04, 2022 |
| ASUSTek       | X302LA                      | Notebook    | [bc5ccb7df4](https://linux-hardware.org/?probe=bc5ccb7df4) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [e61768b292](https://linux-hardware.org/?probe=e61768b292) | Sep 04, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [57e1ced53d](https://linux-hardware.org/?probe=57e1ced53d) | Sep 04, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b704a0ae67](https://linux-hardware.org/?probe=b704a0ae67) | Sep 04, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | Notebook    | [0a729ebdd9](https://linux-hardware.org/?probe=0a729ebdd9) | Sep 04, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5065144435](https://linux-hardware.org/?probe=5065144435) | Sep 04, 2022 |
| HP            | 3397                        | Desktop     | [c66c292876](https://linux-hardware.org/?probe=c66c292876) | Sep 04, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [ebf696b876](https://linux-hardware.org/?probe=ebf696b876) | Sep 03, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [eb29524a90](https://linux-hardware.org/?probe=eb29524a90) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [e30f86bc30](https://linux-hardware.org/?probe=e30f86bc30) | Sep 03, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [7ec410bfe6](https://linux-hardware.org/?probe=7ec410bfe6) | Sep 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5f37e7a618](https://linux-hardware.org/?probe=5f37e7a618) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [f06eee5c49](https://linux-hardware.org/?probe=f06eee5c49) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [18fcb4170b](https://linux-hardware.org/?probe=18fcb4170b) | Sep 03, 2022 |
| Lenovo        | ThinkPad L390 20NSS11E00    | Notebook    | [d5dbbd658f](https://linux-hardware.org/?probe=d5dbbd658f) | Sep 03, 2022 |
| HP            | 18E4                        | Desktop     | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| ASUSTek       | X756UAM                     | Notebook    | [23f0391963](https://linux-hardware.org/?probe=23f0391963) | Sep 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [7c04c344cb](https://linux-hardware.org/?probe=7c04c344cb) | Sep 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [cd935b0146](https://linux-hardware.org/?probe=cd935b0146) | Sep 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [be1fece9bd](https://linux-hardware.org/?probe=be1fece9bd) | Sep 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [8e1f677318](https://linux-hardware.org/?probe=8e1f677318) | Sep 02, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [b765d1e662](https://linux-hardware.org/?probe=b765d1e662) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [4f4717cb85](https://linux-hardware.org/?probe=4f4717cb85) | Sep 02, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [756431d18d](https://linux-hardware.org/?probe=756431d18d) | Sep 02, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [c8bf09dd8d](https://linux-hardware.org/?probe=c8bf09dd8d) | Sep 02, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [45ff2a4622](https://linux-hardware.org/?probe=45ff2a4622) | Sep 02, 2022 |
| Acer          | Aspire 5715Z                | Notebook    | [82086ce1c6](https://linux-hardware.org/?probe=82086ce1c6) | Sep 01, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [e2fc506c38](https://linux-hardware.org/?probe=e2fc506c38) | Sep 01, 2022 |
| Dell          | XPS 9320                    | Notebook    | [525a1bd6b6](https://linux-hardware.org/?probe=525a1bd6b6) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [efc46d8d23](https://linux-hardware.org/?probe=efc46d8d23) | Sep 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1a173c5ea0](https://linux-hardware.org/?probe=1a173c5ea0) | Sep 01, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [8f4a2b603a](https://linux-hardware.org/?probe=8f4a2b603a) | Aug 31, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [d98546fd95](https://linux-hardware.org/?probe=d98546fd95) | Aug 31, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [aacd965d80](https://linux-hardware.org/?probe=aacd965d80) | Aug 31, 2022 |
| HP            | Notebook                    | Notebook    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| Toshiba       | Satellite Pro L500          | Notebook    | [7f523718cf](https://linux-hardware.org/?probe=7f523718cf) | Aug 31, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [c5547cac7c](https://linux-hardware.org/?probe=c5547cac7c) | Aug 31, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [97883c54a3](https://linux-hardware.org/?probe=97883c54a3) | Aug 31, 2022 |
| Dell          | Precision 3551              | Notebook    | [c9ffa625ad](https://linux-hardware.org/?probe=c9ffa625ad) | Aug 31, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [193310218d](https://linux-hardware.org/?probe=193310218d) | Aug 31, 2022 |
| HP            | 83E0                        | Desktop     | [af9b15b8e7](https://linux-hardware.org/?probe=af9b15b8e7) | Aug 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d36b7bb077](https://linux-hardware.org/?probe=d36b7bb077) | Aug 31, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [1e70cd86f6](https://linux-hardware.org/?probe=1e70cd86f6) | Aug 31, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [c0a39342c3](https://linux-hardware.org/?probe=c0a39342c3) | Aug 31, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [09ffe165d3](https://linux-hardware.org/?probe=09ffe165d3) | Aug 30, 2022 |
| HP            | Compaq nc6400 (RU626ET#A... | Notebook    | [e94cb8e943](https://linux-hardware.org/?probe=e94cb8e943) | Aug 30, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [e770273b10](https://linux-hardware.org/?probe=e770273b10) | Aug 30, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [f9a9be3a35](https://linux-hardware.org/?probe=f9a9be3a35) | Aug 30, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7e839a0ef4](https://linux-hardware.org/?probe=7e839a0ef4) | Aug 30, 2022 |
| ASUSTek       | K501LX                      | Notebook    | [993e5d9848](https://linux-hardware.org/?probe=993e5d9848) | Aug 29, 2022 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [aa43ab7091](https://linux-hardware.org/?probe=aa43ab7091) | Aug 29, 2022 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [4882cfb195](https://linux-hardware.org/?probe=4882cfb195) | Aug 29, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [fd6324377f](https://linux-hardware.org/?probe=fd6324377f) | Aug 29, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [d462e3b9d0](https://linux-hardware.org/?probe=d462e3b9d0) | Aug 29, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [a561fb6354](https://linux-hardware.org/?probe=a561fb6354) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [2d013c60ed](https://linux-hardware.org/?probe=2d013c60ed) | Aug 29, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [58f0ba95c3](https://linux-hardware.org/?probe=58f0ba95c3) | Aug 29, 2022 |
| Acer          | TravelMate P215-53          | Notebook    | [4ba2e9fbba](https://linux-hardware.org/?probe=4ba2e9fbba) | Aug 29, 2022 |
| Dell          | Precision 3570              | Notebook    | [7f7a44c923](https://linux-hardware.org/?probe=7f7a44c923) | Aug 29, 2022 |
| ASUSTek       | X751LJC                     | Notebook    | [36c35406c9](https://linux-hardware.org/?probe=36c35406c9) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| ASUSTek       | N71Jv                       | Notebook    | [b30a3030ae](https://linux-hardware.org/?probe=b30a3030ae) | Aug 28, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [a66f7c7a3a](https://linux-hardware.org/?probe=a66f7c7a3a) | Aug 28, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [91371e505d](https://linux-hardware.org/?probe=91371e505d) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [859b3cb78a](https://linux-hardware.org/?probe=859b3cb78a) | Aug 28, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [0454b1e087](https://linux-hardware.org/?probe=0454b1e087) | Aug 27, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | Notebook    | [3d1138a71c](https://linux-hardware.org/?probe=3d1138a71c) | Aug 27, 2022 |
| Dell          | Latitude E5470              | Notebook    | [7d49878b0d](https://linux-hardware.org/?probe=7d49878b0d) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8231da35ed](https://linux-hardware.org/?probe=8231da35ed) | Aug 27, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [353da69160](https://linux-hardware.org/?probe=353da69160) | Aug 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [3f94d521d4](https://linux-hardware.org/?probe=3f94d521d4) | Aug 26, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [73c598ebe7](https://linux-hardware.org/?probe=73c598ebe7) | Aug 26, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [49b01e516c](https://linux-hardware.org/?probe=49b01e516c) | Aug 26, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [8418a8e83c](https://linux-hardware.org/?probe=8418a8e83c) | Aug 26, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [46efca142c](https://linux-hardware.org/?probe=46efca142c) | Aug 26, 2022 |
| Lenovo        | ThinkPad T400 2768BM2       | Notebook    | [f2d91055c9](https://linux-hardware.org/?probe=f2d91055c9) | Aug 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | Notebook    | [a624a45cda](https://linux-hardware.org/?probe=a624a45cda) | Aug 26, 2022 |
| Dell          | 0K7CVF A03                  | Server      | [e4ead551b7](https://linux-hardware.org/?probe=e4ead551b7) | Aug 26, 2022 |
| HP            | 18E5                        | Desktop     | [9196bf639b](https://linux-hardware.org/?probe=9196bf639b) | Aug 26, 2022 |
| Lenovo        | 7033EW4                     | Desktop     | [54417ae55f](https://linux-hardware.org/?probe=54417ae55f) | Aug 26, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [b56c1d75a6](https://linux-hardware.org/?probe=b56c1d75a6) | Aug 25, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [4b8f3feaa7](https://linux-hardware.org/?probe=4b8f3feaa7) | Aug 25, 2022 |
| Dell          | 0RJ290                      | Desktop     | [ca82162ed5](https://linux-hardware.org/?probe=ca82162ed5) | Aug 25, 2022 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [0b76e0f97d](https://linux-hardware.org/?probe=0b76e0f97d) | Aug 25, 2022 |
| ASUSTek       | UN62                        | Desktop     | [49fcd1324f](https://linux-hardware.org/?probe=49fcd1324f) | Aug 25, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [0bf839f496](https://linux-hardware.org/?probe=0bf839f496) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| Dell          | Precision M4800             | Notebook    | [b00f73e4a3](https://linux-hardware.org/?probe=b00f73e4a3) | Aug 24, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [c4f7e439a9](https://linux-hardware.org/?probe=c4f7e439a9) | Aug 24, 2022 |
| Dell          | Latitude E7240              | Notebook    | [0e15063cb3](https://linux-hardware.org/?probe=0e15063cb3) | Aug 24, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [e51675ce88](https://linux-hardware.org/?probe=e51675ce88) | Aug 24, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [4306baa541](https://linux-hardware.org/?probe=4306baa541) | Aug 24, 2022 |
| HP            | ProBook 4540s               | Notebook    | [f082a7566a](https://linux-hardware.org/?probe=f082a7566a) | Aug 24, 2022 |
| HP            | ProBook 4540s               | Notebook    | [de08e9b296](https://linux-hardware.org/?probe=de08e9b296) | Aug 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [663509c999](https://linux-hardware.org/?probe=663509c999) | Aug 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [2b7d1d59a1](https://linux-hardware.org/?probe=2b7d1d59a1) | Aug 24, 2022 |
| HP            | 21D0                        | Desktop     | [1bd58d519c](https://linux-hardware.org/?probe=1bd58d519c) | Aug 24, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [476ca6c833](https://linux-hardware.org/?probe=476ca6c833) | Aug 24, 2022 |
| Dell          | XPS L421X                   | Notebook    | [227df9dc9e](https://linux-hardware.org/?probe=227df9dc9e) | Aug 24, 2022 |
| Dell          | 0MWYPT A02                  | Desktop     | [017af6f58d](https://linux-hardware.org/?probe=017af6f58d) | Aug 23, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [fc9bb1e6fa](https://linux-hardware.org/?probe=fc9bb1e6fa) | Aug 23, 2022 |
| Dell          | XPS L421X                   | Notebook    | [80a474140e](https://linux-hardware.org/?probe=80a474140e) | Aug 22, 2022 |
| HP            | 3397                        | Desktop     | [335f59c96f](https://linux-hardware.org/?probe=335f59c96f) | Aug 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [2aa681b773](https://linux-hardware.org/?probe=2aa681b773) | Aug 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [a51a82210b](https://linux-hardware.org/?probe=a51a82210b) | Aug 22, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [161cae6726](https://linux-hardware.org/?probe=161cae6726) | Aug 22, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [82481d6225](https://linux-hardware.org/?probe=82481d6225) | Aug 22, 2022 |
| ASRock        | A520M-HVS                   | Desktop     | [842ad7d4d2](https://linux-hardware.org/?probe=842ad7d4d2) | Aug 22, 2022 |
| ASUSTek       | X751LN                      | Notebook    | [68cd0152fb](https://linux-hardware.org/?probe=68cd0152fb) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [52a1f16ef3](https://linux-hardware.org/?probe=52a1f16ef3) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [ae19610f33](https://linux-hardware.org/?probe=ae19610f33) | Aug 21, 2022 |
| Fujitsu       | LIFEBOOK UH552              | Notebook    | [15a1f49654](https://linux-hardware.org/?probe=15a1f49654) | Aug 21, 2022 |
| Acer          | AO725                       | Notebook    | [5eed64f77d](https://linux-hardware.org/?probe=5eed64f77d) | Aug 21, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [838dcef1f9](https://linux-hardware.org/?probe=838dcef1f9) | Aug 21, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [a8bf4ad2a0](https://linux-hardware.org/?probe=a8bf4ad2a0) | Aug 21, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [8de83c544f](https://linux-hardware.org/?probe=8de83c544f) | Aug 21, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [1b2c4f25a7](https://linux-hardware.org/?probe=1b2c4f25a7) | Aug 21, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3eed86b908](https://linux-hardware.org/?probe=3eed86b908) | Aug 21, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [36a4120390](https://linux-hardware.org/?probe=36a4120390) | Aug 20, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [b2ac87cffc](https://linux-hardware.org/?probe=b2ac87cffc) | Aug 20, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [59fadaa084](https://linux-hardware.org/?probe=59fadaa084) | Aug 20, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [d5e91a17b8](https://linux-hardware.org/?probe=d5e91a17b8) | Aug 20, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [45bfdfa985](https://linux-hardware.org/?probe=45bfdfa985) | Aug 19, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| HP            | 1497                        | Desktop     | [580e1a6efe](https://linux-hardware.org/?probe=580e1a6efe) | Aug 19, 2022 |
| Lenovo        | ThinkPad T520 4239CTO       | Notebook    | [c88fbf8cc5](https://linux-hardware.org/?probe=c88fbf8cc5) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [e6003f393e](https://linux-hardware.org/?probe=e6003f393e) | Aug 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [bdb88a532f](https://linux-hardware.org/?probe=bdb88a532f) | Aug 19, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [f7fc2a9686](https://linux-hardware.org/?probe=f7fc2a9686) | Aug 19, 2022 |
| Dell          | Latitude 5500               | Notebook    | [1c7c8639aa](https://linux-hardware.org/?probe=1c7c8639aa) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f9ec8eaac3](https://linux-hardware.org/?probe=f9ec8eaac3) | Aug 18, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [de98920808](https://linux-hardware.org/?probe=de98920808) | Aug 18, 2022 |
| Intel         | D54250WYK H13922-302        | Desktop     | [ba78bd360c](https://linux-hardware.org/?probe=ba78bd360c) | Aug 18, 2022 |
| eMachines     | ET1350                      | Desktop     | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [ea6140bf28](https://linux-hardware.org/?probe=ea6140bf28) | Aug 18, 2022 |
| Packard Be... | EasyNote TJ65               | Notebook    | [df3b457c00](https://linux-hardware.org/?probe=df3b457c00) | Aug 18, 2022 |
| ASUSTek       | K70IJ                       | Notebook    | [99bb1459e7](https://linux-hardware.org/?probe=99bb1459e7) | Aug 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | Notebook    | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [0e2658915d](https://linux-hardware.org/?probe=0e2658915d) | Aug 17, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [4cd1658b87](https://linux-hardware.org/?probe=4cd1658b87) | Aug 17, 2022 |
| Packard Be... | EasyNote TK37               | Notebook    | [996a14d9f4](https://linux-hardware.org/?probe=996a14d9f4) | Aug 17, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [d38b463d7d](https://linux-hardware.org/?probe=d38b463d7d) | Aug 17, 2022 |
| ASUSTek       | X556UQ                      | Notebook    | [cc792932e6](https://linux-hardware.org/?probe=cc792932e6) | Aug 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e9d1b72a88](https://linux-hardware.org/?probe=e9d1b72a88) | Aug 17, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [b648d56b04](https://linux-hardware.org/?probe=b648d56b04) | Aug 17, 2022 |
| Toshiba       | Satellite C870-1F3          | Notebook    | [6738afe025](https://linux-hardware.org/?probe=6738afe025) | Aug 17, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [dd79ae2b92](https://linux-hardware.org/?probe=dd79ae2b92) | Aug 17, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [34b4c61308](https://linux-hardware.org/?probe=34b4c61308) | Aug 17, 2022 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [a5ed221478](https://linux-hardware.org/?probe=a5ed221478) | Aug 17, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [8e32248e29](https://linux-hardware.org/?probe=8e32248e29) | Aug 17, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [ad3134e010](https://linux-hardware.org/?probe=ad3134e010) | Aug 17, 2022 |
| Dell          | 0YXT71 A00                  | Desktop     | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [92c0a6fe2a](https://linux-hardware.org/?probe=92c0a6fe2a) | Aug 17, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [a7af0ea5e7](https://linux-hardware.org/?probe=a7af0ea5e7) | Aug 17, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | UX303LN                     | Notebook    | [63d5525864](https://linux-hardware.org/?probe=63d5525864) | Aug 16, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [ec4014a549](https://linux-hardware.org/?probe=ec4014a549) | Aug 16, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [ed6155d213](https://linux-hardware.org/?probe=ed6155d213) | Aug 16, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [84a3ba511d](https://linux-hardware.org/?probe=84a3ba511d) | Aug 16, 2022 |
| Dell          | 0GM819                      | Desktop     | [f7745d3d3a](https://linux-hardware.org/?probe=f7745d3d3a) | Aug 16, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [ce62975b20](https://linux-hardware.org/?probe=ce62975b20) | Aug 15, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [87f8cc8553](https://linux-hardware.org/?probe=87f8cc8553) | Aug 15, 2022 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [da0503d5dd](https://linux-hardware.org/?probe=da0503d5dd) | Aug 15, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [d5b4217f4a](https://linux-hardware.org/?probe=d5b4217f4a) | Aug 15, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [bf211d4e64](https://linux-hardware.org/?probe=bf211d4e64) | Aug 15, 2022 |
| Dell          | G3 3500                     | Notebook    | [6a860d7c0f](https://linux-hardware.org/?probe=6a860d7c0f) | Aug 15, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [a16dfdfe7b](https://linux-hardware.org/?probe=a16dfdfe7b) | Aug 15, 2022 |
| Notebook      | N15_17RD                    | Notebook    | [eef224fc6b](https://linux-hardware.org/?probe=eef224fc6b) | Aug 15, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [cd43fbf16a](https://linux-hardware.org/?probe=cd43fbf16a) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [53429d945b](https://linux-hardware.org/?probe=53429d945b) | Aug 15, 2022 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [757de6f4df](https://linux-hardware.org/?probe=757de6f4df) | Aug 15, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [3d2bd6d842](https://linux-hardware.org/?probe=3d2bd6d842) | Aug 15, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [deaaa5c32c](https://linux-hardware.org/?probe=deaaa5c32c) | Aug 15, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [b7352cd745](https://linux-hardware.org/?probe=b7352cd745) | Aug 14, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [9374a96d80](https://linux-hardware.org/?probe=9374a96d80) | Aug 14, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [33c14d0936](https://linux-hardware.org/?probe=33c14d0936) | Aug 14, 2022 |
| Gigabyte      | B460 AORUS PRO AC           | Desktop     | [ab9e6d26d6](https://linux-hardware.org/?probe=ab9e6d26d6) | Aug 14, 2022 |
| Lenovo        | ThinkPad W540 20BHS0F206    | Notebook    | [7f24672b73](https://linux-hardware.org/?probe=7f24672b73) | Aug 14, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [44a8059d13](https://linux-hardware.org/?probe=44a8059d13) | Aug 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| HP            | 470 G7 Notebook PC          | Notebook    | [adae536639](https://linux-hardware.org/?probe=adae536639) | Aug 13, 2022 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [966a3e1593](https://linux-hardware.org/?probe=966a3e1593) | Aug 13, 2022 |
| MSI           | GE75 Raider 10SF            | Notebook    | [0fafeaaa76](https://linux-hardware.org/?probe=0fafeaaa76) | Aug 13, 2022 |
| Panasonic     | CF-31XEUAXMF                | Notebook    | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [50b7221c5a](https://linux-hardware.org/?probe=50b7221c5a) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8c792d555c](https://linux-hardware.org/?probe=8c792d555c) | Aug 12, 2022 |
| HP            | 15                          | Notebook    | [30a35c4e04](https://linux-hardware.org/?probe=30a35c4e04) | Aug 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [d67ec558d4](https://linux-hardware.org/?probe=d67ec558d4) | Aug 12, 2022 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [ff1be50f8c](https://linux-hardware.org/?probe=ff1be50f8c) | Aug 12, 2022 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [3d93d807ca](https://linux-hardware.org/?probe=3d93d807ca) | Aug 12, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [2f541727e1](https://linux-hardware.org/?probe=2f541727e1) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX534FAC            | Notebook    | [419660b78b](https://linux-hardware.org/?probe=419660b78b) | Aug 12, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [c1b14847f1](https://linux-hardware.org/?probe=c1b14847f1) | Aug 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1f75df3828](https://linux-hardware.org/?probe=1f75df3828) | Aug 12, 2022 |
| ASRock        | Z97M Pro4                   | Desktop     | [245d189a61](https://linux-hardware.org/?probe=245d189a61) | Aug 11, 2022 |
| Panasonic     | CF-53JSWZGFF                | Notebook    | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| Dell          | System XPS 15Z              | Notebook    | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Dell          | XPS 9320                    | Notebook    | [2c76534231](https://linux-hardware.org/?probe=2c76534231) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| ASUSTek       | GL502VT                     | Notebook    | [5e95e514a4](https://linux-hardware.org/?probe=5e95e514a4) | Aug 11, 2022 |
| ASRock        | H61M/U3S3                   | Desktop     | [be0d853621](https://linux-hardware.org/?probe=be0d853621) | Aug 11, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [33dc68fe04](https://linux-hardware.org/?probe=33dc68fe04) | Aug 11, 2022 |
| Notebook      | N141CU                      | Notebook    | [4d96f7358c](https://linux-hardware.org/?probe=4d96f7358c) | Aug 10, 2022 |
| Toshiba       | Satellite L875-11M          | Notebook    | [5a01928c94](https://linux-hardware.org/?probe=5a01928c94) | Aug 10, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [1b439cee14](https://linux-hardware.org/?probe=1b439cee14) | Aug 10, 2022 |
| Vorke         | V1 Plus                     | Desktop     | [a31728f53e](https://linux-hardware.org/?probe=a31728f53e) | Aug 10, 2022 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [f57b28ff2c](https://linux-hardware.org/?probe=f57b28ff2c) | Aug 10, 2022 |
| ASUSTek       | X751LJ                      | Notebook    | [5c3767ccc2](https://linux-hardware.org/?probe=5c3767ccc2) | Aug 10, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [9a77cf2f22](https://linux-hardware.org/?probe=9a77cf2f22) | Aug 10, 2022 |
| Dell          | XPS 9320                    | Notebook    | [f1ce1578ed](https://linux-hardware.org/?probe=f1ce1578ed) | Aug 10, 2022 |
| Dell          | Inspiron 5523               | Notebook    | [6a6928a8a5](https://linux-hardware.org/?probe=6a6928a8a5) | Aug 10, 2022 |
| Acer          | Veriton Z4810G              | All in one  | [d85c47c623](https://linux-hardware.org/?probe=d85c47c623) | Aug 10, 2022 |
| eMachines     | Veriton V2110               | Desktop     | [3492540d77](https://linux-hardware.org/?probe=3492540d77) | Aug 09, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [346b22a42e](https://linux-hardware.org/?probe=346b22a42e) | Aug 09, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | Notebook    | [2ac0968200](https://linux-hardware.org/?probe=2ac0968200) | Aug 09, 2022 |
| ASUSTek       | X751LJ                      | Notebook    | [e35689c8f1](https://linux-hardware.org/?probe=e35689c8f1) | Aug 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [77396822d3](https://linux-hardware.org/?probe=77396822d3) | Aug 09, 2022 |
| Toshiba       | Satellite L875-11M          | Notebook    | [1b423f639e](https://linux-hardware.org/?probe=1b423f639e) | Aug 09, 2022 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [fa0e4ba168](https://linux-hardware.org/?probe=fa0e4ba168) | Aug 09, 2022 |
| Notebook      | N230WU                      | Notebook    | [f00a446001](https://linux-hardware.org/?probe=f00a446001) | Aug 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [1713317338](https://linux-hardware.org/?probe=1713317338) | Aug 09, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [a6cd208cf2](https://linux-hardware.org/?probe=a6cd208cf2) | Aug 09, 2022 |
| OEM           | Unknown                     | Notebook    | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Lenovo        | Bantry CRB NOK              | Desktop     | [fbeb21c99a](https://linux-hardware.org/?probe=fbeb21c99a) | Aug 09, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [89d9f69018](https://linux-hardware.org/?probe=89d9f69018) | Aug 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [66235597aa](https://linux-hardware.org/?probe=66235597aa) | Aug 09, 2022 |
| Lenovo        | ThinkPad X230 23259T0       | Notebook    | [04b33f4a65](https://linux-hardware.org/?probe=04b33f4a65) | Aug 08, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c9bb066a9b](https://linux-hardware.org/?probe=c9bb066a9b) | Aug 08, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7bc9d5090f](https://linux-hardware.org/?probe=7bc9d5090f) | Aug 08, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [e9d631e886](https://linux-hardware.org/?probe=e9d631e886) | Aug 08, 2022 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [8e83a5b7d3](https://linux-hardware.org/?probe=8e83a5b7d3) | Aug 08, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [d1215796fb](https://linux-hardware.org/?probe=d1215796fb) | Aug 08, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [613f8a0c36](https://linux-hardware.org/?probe=613f8a0c36) | Aug 08, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [f833eca9da](https://linux-hardware.org/?probe=f833eca9da) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330s-15ARR 81FB     | Notebook    | [4546912e7b](https://linux-hardware.org/?probe=4546912e7b) | Aug 08, 2022 |
| Dell          | Precision 5510              | Notebook    | [02dd64eff3](https://linux-hardware.org/?probe=02dd64eff3) | Aug 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [21e646de39](https://linux-hardware.org/?probe=21e646de39) | Aug 08, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ee62b165ef](https://linux-hardware.org/?probe=ee62b165ef) | Aug 08, 2022 |
| Intel         | JV10_CS                     | Notebook    | [07ca100ab3](https://linux-hardware.org/?probe=07ca100ab3) | Aug 08, 2022 |
| Dell          | 060K5C A06                  | Server      | [56aaa332b3](https://linux-hardware.org/?probe=56aaa332b3) | Aug 08, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [1c4298ff33](https://linux-hardware.org/?probe=1c4298ff33) | Aug 08, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [0f1ad8ccf7](https://linux-hardware.org/?probe=0f1ad8ccf7) | Aug 08, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [40808a05c1](https://linux-hardware.org/?probe=40808a05c1) | Aug 07, 2022 |
| HP            | Compaq 15                   | Notebook    | [de4b6e0511](https://linux-hardware.org/?probe=de4b6e0511) | Aug 07, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [19b3f7fe4b](https://linux-hardware.org/?probe=19b3f7fe4b) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [977159d1d8](https://linux-hardware.org/?probe=977159d1d8) | Aug 07, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [bfa218709f](https://linux-hardware.org/?probe=bfa218709f) | Aug 07, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f9850e0a1e](https://linux-hardware.org/?probe=f9850e0a1e) | Aug 07, 2022 |
| Intel         | NUC11ATBC4 M53051-202       | Mini pc     | [95e97a827b](https://linux-hardware.org/?probe=95e97a827b) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [13a118ae0b](https://linux-hardware.org/?probe=13a118ae0b) | Aug 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | Notebook    | [89b2da04d8](https://linux-hardware.org/?probe=89b2da04d8) | Aug 06, 2022 |
| Acer          | Aspire V3-372T              | Notebook    | [9dc2882992](https://linux-hardware.org/?probe=9dc2882992) | Aug 06, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [64b08b679f](https://linux-hardware.org/?probe=64b08b679f) | Aug 05, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [bbcc5fa79d](https://linux-hardware.org/?probe=bbcc5fa79d) | Aug 05, 2022 |
| Lenovo        | ThinkPad R500 27148UG       | Notebook    | [1b7557ac14](https://linux-hardware.org/?probe=1b7557ac14) | Aug 05, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [255c2dd960](https://linux-hardware.org/?probe=255c2dd960) | Aug 05, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [034cd98301](https://linux-hardware.org/?probe=034cd98301) | Aug 05, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [237cf11989](https://linux-hardware.org/?probe=237cf11989) | Aug 05, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [aec2ac880f](https://linux-hardware.org/?probe=aec2ac880f) | Aug 05, 2022 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [85037ebcb0](https://linux-hardware.org/?probe=85037ebcb0) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Notebook      | NJ50_70CU                   | Notebook    | [fc31dfa99e](https://linux-hardware.org/?probe=fc31dfa99e) | Aug 04, 2022 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [237c4a2367](https://linux-hardware.org/?probe=237c4a2367) | Aug 04, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [f293c53dec](https://linux-hardware.org/?probe=f293c53dec) | Aug 04, 2022 |
| Dell          | Latitude E5520              | Notebook    | [1e3f6832b1](https://linux-hardware.org/?probe=1e3f6832b1) | Aug 04, 2022 |
| Dell          | 0HGFJM A00                  | Desktop     | [b1011ae242](https://linux-hardware.org/?probe=b1011ae242) | Aug 04, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [37ccdc4cf7](https://linux-hardware.org/?probe=37ccdc4cf7) | Aug 04, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [fa975ac535](https://linux-hardware.org/?probe=fa975ac535) | Aug 04, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [e43f32d47e](https://linux-hardware.org/?probe=e43f32d47e) | Aug 04, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [5eee2883a9](https://linux-hardware.org/?probe=5eee2883a9) | Aug 04, 2022 |
| ASUSTek       | P6T                         | Desktop     | [978f8623ff](https://linux-hardware.org/?probe=978f8623ff) | Aug 03, 2022 |
| HP            | Pavilion 17                 | Notebook    | [cbbaa8f0db](https://linux-hardware.org/?probe=cbbaa8f0db) | Aug 03, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | Notebook    | [0aa70716b7](https://linux-hardware.org/?probe=0aa70716b7) | Aug 03, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [81b60bd487](https://linux-hardware.org/?probe=81b60bd487) | Aug 03, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [06e06f9c67](https://linux-hardware.org/?probe=06e06f9c67) | Aug 03, 2022 |
| Dell          | Latitude E7440              | Notebook    | [4d132a5fd7](https://linux-hardware.org/?probe=4d132a5fd7) | Aug 03, 2022 |
| ASRock        | NUC-8265U                   | Desktop     | [32b0ae0f97](https://linux-hardware.org/?probe=32b0ae0f97) | Aug 03, 2022 |
| Supermicro    | X7DCL                       | Desktop     | [4b841e9401](https://linux-hardware.org/?probe=4b841e9401) | Aug 03, 2022 |
| ASUSTek       | 1225B                       | Notebook    | [a5fb38b287](https://linux-hardware.org/?probe=a5fb38b287) | Aug 03, 2022 |
| Dell          | 0KW626                      | Desktop     | [629c1c7800](https://linux-hardware.org/?probe=629c1c7800) | Aug 03, 2022 |
| Lenovo        | ThinkPad SL510 28477NG      | Notebook    | [5ddf195177](https://linux-hardware.org/?probe=5ddf195177) | Aug 03, 2022 |
| ASUSTek       | K50IE                       | Notebook    | [0472e4609b](https://linux-hardware.org/?probe=0472e4609b) | Aug 03, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [182bfa1039](https://linux-hardware.org/?probe=182bfa1039) | Aug 02, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7f574acfee](https://linux-hardware.org/?probe=7f574acfee) | Aug 02, 2022 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [f513bdb1f5](https://linux-hardware.org/?probe=f513bdb1f5) | Aug 02, 2022 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [ec9385b488](https://linux-hardware.org/?probe=ec9385b488) | Aug 02, 2022 |
| HP            | Notebook                    | Notebook    | [5320991330](https://linux-hardware.org/?probe=5320991330) | Aug 02, 2022 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [89d09548e4](https://linux-hardware.org/?probe=89d09548e4) | Aug 02, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [d2c534d06f](https://linux-hardware.org/?probe=d2c534d06f) | Aug 02, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [1a35a6d7dc](https://linux-hardware.org/?probe=1a35a6d7dc) | Aug 02, 2022 |
| Lenovo        | 314F SDK0Q40112 WIN 3305... | Desktop     | [e906976bea](https://linux-hardware.org/?probe=e906976bea) | Aug 02, 2022 |
| Intel         | NUC11PABi3 M11790-305       | Mini pc     | [792c8d97b5](https://linux-hardware.org/?probe=792c8d97b5) | Aug 02, 2022 |
| ASUSTek       | X751LJC                     | Notebook    | [e71a9f6a85](https://linux-hardware.org/?probe=e71a9f6a85) | Aug 02, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [e63e46c5a4](https://linux-hardware.org/?probe=e63e46c5a4) | Aug 02, 2022 |
| Acidanther... | MacBookPro13,1              | Notebook    | [5c8158f059](https://linux-hardware.org/?probe=5c8158f059) | Aug 01, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [83e4b444ae](https://linux-hardware.org/?probe=83e4b444ae) | Aug 01, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [4e335cb7ce](https://linux-hardware.org/?probe=4e335cb7ce) | Aug 01, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [d4524b40db](https://linux-hardware.org/?probe=d4524b40db) | Aug 01, 2022 |
| HP            | Spectre                     | Convertible | [65226ddc27](https://linux-hardware.org/?probe=65226ddc27) | Aug 01, 2022 |
| HP            | Spectre                     | Convertible | [4d0f459190](https://linux-hardware.org/?probe=4d0f459190) | Aug 01, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [daaf600950](https://linux-hardware.org/?probe=daaf600950) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [41b26f984c](https://linux-hardware.org/?probe=41b26f984c) | Aug 01, 2022 |
| HP            | Spectre                     | Convertible | [afab893436](https://linux-hardware.org/?probe=afab893436) | Aug 01, 2022 |
| HP            | Spectre                     | Convertible | [60d75d422c](https://linux-hardware.org/?probe=60d75d422c) | Aug 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0d7342cca0](https://linux-hardware.org/?probe=0d7342cca0) | Aug 01, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [d67cc48957](https://linux-hardware.org/?probe=d67cc48957) | Aug 01, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [5f41623898](https://linux-hardware.org/?probe=5f41623898) | Aug 01, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [7137ca1923](https://linux-hardware.org/?probe=7137ca1923) | Aug 01, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [9a5e39bf87](https://linux-hardware.org/?probe=9a5e39bf87) | Aug 01, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [4e266f6d7f](https://linux-hardware.org/?probe=4e266f6d7f) | Jul 31, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7ae6c1826c](https://linux-hardware.org/?probe=7ae6c1826c) | Jul 31, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [932a460553](https://linux-hardware.org/?probe=932a460553) | Jul 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f312865dc0](https://linux-hardware.org/?probe=f312865dc0) | Jul 31, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [86ef744d76](https://linux-hardware.org/?probe=86ef744d76) | Jul 31, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [054fdc9187](https://linux-hardware.org/?probe=054fdc9187) | Jul 31, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [1a2713a2b0](https://linux-hardware.org/?probe=1a2713a2b0) | Jul 31, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [5dcf2bfdbd](https://linux-hardware.org/?probe=5dcf2bfdbd) | Jul 30, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [86af6982c5](https://linux-hardware.org/?probe=86af6982c5) | Jul 30, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [7325fb8135](https://linux-hardware.org/?probe=7325fb8135) | Jul 30, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [76083d81dc](https://linux-hardware.org/?probe=76083d81dc) | Jul 30, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [bc1c5d997f](https://linux-hardware.org/?probe=bc1c5d997f) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9ea9e6f737](https://linux-hardware.org/?probe=9ea9e6f737) | Jul 30, 2022 |
| Sony          | SVE1511Y1ESI                | Notebook    | [7e5ced1b91](https://linux-hardware.org/?probe=7e5ced1b91) | Jul 30, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [3ec038d45b](https://linux-hardware.org/?probe=3ec038d45b) | Jul 30, 2022 |
| HP            | Pavilion dm4                | Notebook    | [2bde69365c](https://linux-hardware.org/?probe=2bde69365c) | Jul 29, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [efa02942f2](https://linux-hardware.org/?probe=efa02942f2) | Jul 29, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [fca54dfc19](https://linux-hardware.org/?probe=fca54dfc19) | Jul 29, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [4321f0776b](https://linux-hardware.org/?probe=4321f0776b) | Jul 29, 2022 |
| Dell          | Latitude E6410              | Notebook    | [f2220a772e](https://linux-hardware.org/?probe=f2220a772e) | Jul 29, 2022 |
| Lenovo        | ThinkPad S5 Yoga 15 20DR... | Notebook    | [147d305ac1](https://linux-hardware.org/?probe=147d305ac1) | Jul 29, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [74626c2a4d](https://linux-hardware.org/?probe=74626c2a4d) | Jul 29, 2022 |
| ASUSTek       | B85M-E/DASH                 | Desktop     | [2ebbaa4052](https://linux-hardware.org/?probe=2ebbaa4052) | Jul 29, 2022 |
| Dell          | Latitude 9420               | Notebook    | [1ee70bdfc6](https://linux-hardware.org/?probe=1ee70bdfc6) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [4158c1696a](https://linux-hardware.org/?probe=4158c1696a) | Jul 29, 2022 |
| HP            | 339A                        | Desktop     | [fa0d80162a](https://linux-hardware.org/?probe=fa0d80162a) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [1a5b34b200](https://linux-hardware.org/?probe=1a5b34b200) | Jul 29, 2022 |
| Dell          | 0W0CHX A00                  | Desktop     | [be7cc4f033](https://linux-hardware.org/?probe=be7cc4f033) | Jul 29, 2022 |
| Dell          | Latitude 5480               | Notebook    | [2e2d540cb0](https://linux-hardware.org/?probe=2e2d540cb0) | Jul 29, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [bd5b812271](https://linux-hardware.org/?probe=bd5b812271) | Jul 29, 2022 |
| Acer          | Veriton M4610G              | Desktop     | [00ec5bea11](https://linux-hardware.org/?probe=00ec5bea11) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2953cb274f](https://linux-hardware.org/?probe=2953cb274f) | Jul 28, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [db534130d2](https://linux-hardware.org/?probe=db534130d2) | Jul 28, 2022 |
| HP            | 21F5                        | Desktop     | [27cf2d6a42](https://linux-hardware.org/?probe=27cf2d6a42) | Jul 28, 2022 |
| HP            | 8754                        | Mini pc     | [1b0ae59d1f](https://linux-hardware.org/?probe=1b0ae59d1f) | Jul 28, 2022 |
| ASUSTek       | X75A                        | Notebook    | [646a5239a8](https://linux-hardware.org/?probe=646a5239a8) | Jul 28, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [7922ab1018](https://linux-hardware.org/?probe=7922ab1018) | Jul 28, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2d3706b78b](https://linux-hardware.org/?probe=2d3706b78b) | Jul 28, 2022 |
| Notebook      | NL4x_NL5xLU                 | Notebook    | [12d6dbed8b](https://linux-hardware.org/?probe=12d6dbed8b) | Jul 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 1660      | 21.46%  |
| Ubuntu 18.04      | 544       | 7.03%   |
| OpenMandriva 4.2  | 350       | 4.52%   |
| Debian 11         | 254       | 3.28%   |
| Ubuntu 22.04      | 246       | 3.18%   |
| OpenMandriva 4.3  | 232       | 3%      |
| Xubuntu 20.04     | 185       | 2.39%   |
| Linux Mint 20.3   | 160       | 2.07%   |
| Debian 10         | 134       | 1.73%   |
| Arch              | 124       | 1.6%    |
| Ubuntu 21.10      | 121       | 1.56%   |
| Arch Rolling      | 110       | 1.42%   |
| Ubuntu 20.10      | 109       | 1.41%   |
| Ubuntu 21.04      | 105       | 1.36%   |
| Linux Mint 20.1   | 105       | 1.36%   |
| Linux Mint 20.2   | 102       | 1.32%   |
| Fedora 33         | 88        | 1.14%   |
| Linux Mint 19.3   | 86        | 1.11%   |
| Ubuntu 19.10      | 85        | 1.1%    |
| Kubuntu 20.04     | 82        | 1.06%   |
| Manjaro           | 76        | 0.98%   |
| Xubuntu 18.04     | 74        | 0.96%   |
| Linux Mint 20     | 73        | 0.94%   |
| Fedora 34         | 73        | 0.94%   |
| Ubuntu 19.04      | 71        | 0.92%   |
| KDE neon 20.04    | 71        | 0.92%   |
| Fedora 32         | 69        | 0.89%   |
| Fedora 35         | 64        | 0.83%   |
| Zorin 16          | 61        | 0.79%   |
| Ubuntu MATE 20.04 | 58        | 0.75%   |
| Lubuntu 20.04     | 54        | 0.7%    |
| Fedora 36         | 54        | 0.7%    |
| Pop!_OS 21.04     | 50        | 0.65%   |
| Pop!_OS 20.04     | 49        | 0.63%   |
| ROSA R11          | 47        | 0.61%   |
| Pop!_OS 20.10     | 46        | 0.59%   |
| Debian Testing    | 45        | 0.58%   |
| Linux Mint 21     | 44        | 0.57%   |
| ArcoLinux Rolling | 41        | 0.53%   |
| Zorin 15          | 40        | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2892      | 39.32%  |
| OpenMandriva  | 650       | 8.84%   |
| Linux Mint    | 589       | 8.01%   |
| Debian        | 473       | 6.43%   |
| Fedora        | 341       | 4.64%   |
| Xubuntu       | 319       | 4.34%   |
| Arch          | 230       | 3.13%   |
| Manjaro       | 204       | 2.77%   |
| Pop!_OS       | 198       | 2.69%   |
| ROSA          | 170       | 2.31%   |
| Kubuntu       | 167       | 2.27%   |
| Zorin         | 104       | 1.41%   |
| Ubuntu MATE   | 103       | 1.4%    |
| Lubuntu       | 85        | 1.16%   |
| KDE neon      | 79        | 1.07%   |
| Ubuntu Unity  | 62        | 0.84%   |
| openSUSE      | 55        | 0.75%   |
| Gentoo        | 48        | 0.65%   |
| Endless       | 48        | 0.65%   |
| ArcoLinux     | 42        | 0.57%   |
| Kali          | 41        | 0.56%   |
| Ubuntu Budgie | 38        | 0.52%   |
| Elementary    | 37        | 0.5%    |
| BlackPanther  | 31        | 0.42%   |
| EndeavourOS   | 30        | 0.41%   |
| LMDE          | 28        | 0.38%   |
| CentOS        | 23        | 0.31%   |
| Ubuntu Studio | 19        | 0.26%   |
| Mageia        | 18        | 0.24%   |
| Clear Linux   | 18        | 0.24%   |
| SteamOS       | 16        | 0.22%   |
| Parrot        | 15        | 0.2%    |
| MX            | 11        | 0.15%   |
| Kaisen        | 11        | 0.15%   |
| Artix         | 10        | 0.14%   |
| Manjaro-ARM   | 8         | 0.11%   |
| LinuxFX       | 8         | 0.11%   |
| Devuan        | 8         | 0.11%   |
| Raspbian      | 7         | 0.1%    |
| Linux Lite    | 7         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 333       | 3.93%   |
| 5.16.7-desktop-1omv4003  | 224       | 2.64%   |
| 5.4.0-42-generic         | 128       | 1.51%   |
| 5.4.0-58-generic         | 99        | 1.17%   |
| 5.4.0-52-generic         | 79        | 0.93%   |
| 5.11.0-38-generic        | 75        | 0.88%   |
| 5.11.0-27-generic        | 75        | 0.88%   |
| 5.15.0-48-generic        | 74        | 0.87%   |
| 5.4.0-26-generic         | 71        | 0.84%   |
| 5.4.0-48-generic         | 69        | 0.81%   |
| 5.8.0-43-generic         | 68        | 0.8%    |
| 5.15.0-46-generic        | 66        | 0.78%   |
| 5.11.0-37-generic        | 66        | 0.78%   |
| 5.4.0-65-generic         | 65        | 0.77%   |
| 5.8.0-50-generic         | 63        | 0.74%   |
| 5.11.0-40-generic        | 57        | 0.67%   |
| 5.4.0-29-generic         | 55        | 0.65%   |
| 5.13.0-28-generic        | 55        | 0.65%   |
| 5.8.0-44-generic         | 54        | 0.64%   |
| 5.4.0-91-generic         | 54        | 0.64%   |
| 5.4.0-54-generic         | 54        | 0.64%   |
| 5.8.0-48-generic         | 53        | 0.63%   |
| 5.4.0-37-generic         | 53        | 0.63%   |
| 5.15.0-47-generic        | 53        | 0.63%   |
| 5.13.0-39-generic        | 52        | 0.61%   |
| 5.11.0-43-generic        | 51        | 0.6%    |
| 5.4.0-81-generic         | 48        | 0.57%   |
| 5.11.0-34-generic        | 48        | 0.57%   |
| 5.8.0-59-generic         | 46        | 0.54%   |
| 5.4.0-31-generic         | 45        | 0.53%   |
| 5.15.0-43-generic        | 45        | 0.53%   |
| 5.13.0-40-generic        | 45        | 0.53%   |
| 5.15.0-41-generic        | 42        | 0.5%    |
| 5.13.0-27-generic        | 42        | 0.5%    |
| 5.8.0-53-generic         | 41        | 0.48%   |
| 5.4.0-73-generic         | 40        | 0.47%   |
| 5.10.0-8-amd64           | 40        | 0.47%   |
| 5.8.0-41-generic         | 39        | 0.46%   |
| 5.4.0-66-generic         | 39        | 0.46%   |
| 5.4.0-72-generic         | 38        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1694      | 21.27%  |
| 5.11.0  | 624       | 7.84%   |
| 5.8.0   | 609       | 7.65%   |
| 5.13.0  | 505       | 6.34%   |
| 5.15.0  | 477       | 5.99%   |
| 4.15.0  | 424       | 5.32%   |
| 5.10.14 | 336       | 4.22%   |
| 5.3.0   | 288       | 3.62%   |
| 5.10.0  | 287       | 3.6%    |
| 5.16.7  | 226       | 2.84%   |
| 5.0.0   | 164       | 2.06%   |
| 4.18.0  | 136       | 1.71%   |
| 4.19.0  | 128       | 1.61%   |
| 5.19.0  | 38        | 0.48%   |
| 5.14.0  | 36        | 0.45%   |
| 4.9.20  | 35        | 0.44%   |
| 5.18.12 | 31        | 0.39%   |
| 5.11.12 | 31        | 0.39%   |
| 5.17.5  | 29        | 0.36%   |
| 5.18.0  | 28        | 0.35%   |
| 5.16.0  | 28        | 0.35%   |
| 4.18.16 | 28        | 0.35%   |
| 4.4.0   | 26        | 0.33%   |
| 5.9.0   | 25        | 0.31%   |
| 5.12.4  | 23        | 0.29%   |
| 4.9.60  | 23        | 0.29%   |
| 5.13.19 | 19        | 0.24%   |
| 5.9.16  | 18        | 0.23%   |
| 5.9.11  | 18        | 0.23%   |
| 5.7.0   | 18        | 0.23%   |
| 5.6.0   | 18        | 0.23%   |
| 5.17.1  | 17        | 0.21%   |
| 4.9.0   | 17        | 0.21%   |
| 5.13.12 | 16        | 0.2%    |
| 5.14.14 | 15        | 0.19%   |
| 5.4.32  | 14        | 0.18%   |
| 5.14.9  | 14        | 0.18%   |
| 5.8.18  | 13        | 0.16%   |
| 4.1.38  | 13        | 0.16%   |
| 5.9.1   | 12        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4      | 1788      | 22.74%  |
| 5.10     | 761       | 9.68%   |
| 5.11     | 716       | 9.11%   |
| 5.8      | 698       | 8.88%   |
| 5.15     | 643       | 8.18%   |
| 5.13     | 588       | 7.48%   |
| 4.15     | 425       | 5.41%   |
| 5.16     | 336       | 4.27%   |
| 5.3      | 327       | 4.16%   |
| 5.0      | 177       | 2.25%   |
| 4.18     | 167       | 2.12%   |
| 4.19     | 145       | 1.84%   |
| 5.18     | 124       | 1.58%   |
| 5.14     | 119       | 1.51%   |
| 5.9      | 118       | 1.5%    |
| 4.9      | 118       | 1.5%    |
| 5.19     | 104       | 1.32%   |
| 5.17     | 96        | 1.22%   |
| 5.6      | 82        | 1.04%   |
| 5.7      | 73        | 0.93%   |
| 5.12     | 70        | 0.89%   |
| 5.5      | 39        | 0.5%    |
| 4.4      | 30        | 0.38%   |
| 4.1      | 24        | 0.31%   |
| 5.2      | 13        | 0.17%   |
| 6.0      | 12        | 0.15%   |
| 4.14     | 12        | 0.15%   |
| 3.10     | 12        | 0.15%   |
| 4.12     | 9         | 0.11%   |
| 4.20     | 7         | 0.09%   |
| 4.13     | 7         | 0.09%   |
| 5.1      | 6         | 0.08%   |
| 4.10     | 4         | 0.05%   |
| 4.8      | 3         | 0.04%   |
| 4.17     | 2         | 0.03%   |
| 3.4      | 2         | 0.03%   |
| 6.1      | 1         | 0.01%   |
| 5        | 1         | 0.01%   |
| 4.9.273~ | 1         | 0.01%   |
| 3.14     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6888      | 96.3%   |
| i686    | 207       | 2.89%   |
| aarch64 | 38        | 0.53%   |
| armv7l  | 16        | 0.22%   |
| armv8l  | 2         | 0.03%   |
| armv6l  | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 3332      | 44.86%  |
| KDE5              | 1187      | 15.98%  |
| Unknown           | 817       | 11%     |
| XFCE              | 664       | 8.94%   |
| X-Cinnamon        | 407       | 5.48%   |
| MATE              | 273       | 3.68%   |
| KDE4              | 114       | 1.53%   |
| KDE               | 114       | 1.53%   |
| Cinnamon          | 112       | 1.51%   |
| LXQt              | 89        | 1.2%    |
| Unity             | 63        | 0.85%   |
| i3                | 59        | 0.79%   |
| Budgie            | 45        | 0.61%   |
| Pantheon          | 38        | 0.51%   |
| LXDE              | 34        | 0.46%   |
| GNOME Flashback   | 19        | 0.26%   |
| Deepin            | 11        | 0.15%   |
| GNOME Classic     | 9         | 0.12%   |
| qtile             | 5         | 0.07%   |
| bspwm             | 5         | 0.07%   |
| sway              | 4         | 0.05%   |
| awesome           | 4         | 0.05%   |
| trinity           | 3         | 0.04%   |
| i3-with-shmlog    | 3         | 0.04%   |
| openbox           | 2         | 0.03%   |
| lightdm-xsession  | 2         | 0.03%   |
| ICEWM             | 2         | 0.03%   |
| Enlightenment     | 2         | 0.03%   |
| Yaru:ubuntu:GNOME | 1         | 0.01%   |
| xmonad            | 1         | 0.01%   |
| wmaker-common     | 1         | 0.01%   |
| Lubuntu           | 1         | 0.01%   |
| LeftWM            | 1         | 0.01%   |
| GNUstep           | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |
| dwm-sc            | 1         | 0.01%   |
| DWM               | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5900      | 80.4%   |
| Wayland | 840       | 11.45%  |
| Unknown | 404       | 5.51%   |
| Tty     | 194       | 2.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3089      | 41.61%  |
| GDM     | 1369      | 18.44%  |
| SDDM    | 1197      | 16.13%  |
| LightDM | 722       | 9.73%   |
| GDM3    | 575       | 7.75%   |
| TDM     | 334       | 4.5%    |
| KDM     | 111       | 1.5%    |
| XDM     | 10        | 0.13%   |
| SLiM    | 6         | 0.08%   |
| Ly      | 5         | 0.07%   |
| NODM    | 2         | 0.03%   |
| WDM     | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| fr_FR       | 5008      | 68.77%  |
| en_US       | 1159      | 15.92%  |
| Unknown     | 738       | 10.13%  |
| en_GB       | 115       | 1.58%   |
| C           | 82        | 1.13%   |
| ru_RU       | 19        | 0.26%   |
| de_DE       | 19        | 0.26%   |
| es_ES       | 14        | 0.19%   |
| it_IT       | 13        | 0.18%   |
| nl_NL       | 12        | 0.16%   |
| pl_PL       | 10        | 0.14%   |
| fr_CH       | 10        | 0.14%   |
| fr_CA       | 8         | 0.11%   |
| pt_PT       | 7         | 0.1%    |
| fr_BE       | 7         | 0.1%    |
| POSIX       | 5         | 0.07%   |
| en_IE       | 4         | 0.05%   |
| C.UTF8      | 4         | 0.05%   |
| sv_SE       | 3         | 0.04%   |
| pt_BR       | 3         | 0.04%   |
| fr_FR.UTF8  | 3         | 0.04%   |
| en_IN       | 3         | 0.04%   |
| en_AU       | 3         | 0.04%   |
| ru_UA       | 2         | 0.03%   |
| hu_HU       | 2         | 0.03%   |
| fr_LU       | 2         | 0.03%   |
| en_DK       | 2         | 0.03%   |
| en_CA       | 2         | 0.03%   |
| cs_CZ       | 2         | 0.03%   |
| sr_RS@latin | 1         | 0.01%   |
| sr_RS       | 1         | 0.01%   |
| sk_SK       | 1         | 0.01%   |
| ro_RO       | 1         | 0.01%   |
| nb_NO       | 1         | 0.01%   |
| fr_FR.utf-8 | 1         | 0.01%   |
| eu_ES       | 1         | 0.01%   |
| es_VE       | 1         | 0.01%   |
| es_UY       | 1         | 0.01%   |
| es_AR       | 1         | 0.01%   |
| en_ZA       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3689      | 50.64%  |
| BIOS | 3596      | 49.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5862      | 80.52%  |
| Overlay  | 644       | 8.85%   |
| Btrfs    | 395       | 5.43%   |
| Unknown  | 221       | 3.04%   |
| Xfs      | 73        | 1%      |
| Zfs      | 41        | 0.56%   |
| Ext2     | 14        | 0.19%   |
| Ext3     | 12        | 0.16%   |
| F2fs     | 11        | 0.15%   |
| Reiserfs | 3         | 0.04%   |
| Tmpfs    | 1         | 0.01%   |
| Rootfs   | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |
| Aufs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3340      | 45.77%  |
| GPT     | 2831      | 38.79%  |
| MBR     | 1127      | 15.44%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5913      | 81.27%  |
| Yes       | 1363      | 18.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4883      | 67.15%  |
| Yes       | 2389      | 32.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1459      | 20.41%  |
| Dell                    | 1033      | 14.45%  |
| Hewlett-Packard         | 908       | 12.7%   |
| Lenovo                  | 785       | 10.98%  |
| MSI                     | 612       | 8.56%   |
| Gigabyte Technology     | 409       | 5.72%   |
| Acer                    | 358       | 5.01%   |
| ASRock                  | 178       | 2.49%   |
| Toshiba                 | 132       | 1.85%   |
| Apple                   | 128       | 1.79%   |
| Intel                   | 106       | 1.48%   |
| Packard Bell            | 85        | 1.19%   |
| Notebook                | 77        | 1.08%   |
| Samsung Electronics     | 60        | 0.84%   |
| HUAWEI                  | 57        | 0.8%    |
| Unknown                 | 57        | 0.8%    |
| Sony                    | 51        | 0.71%   |
| Foxconn                 | 41        | 0.57%   |
| Pegatron                | 37        | 0.52%   |
| eMachines               | 33        | 0.46%   |
| Raspberry Pi Foundation | 31        | 0.43%   |
| Fujitsu                 | 31        | 0.43%   |
| Medion                  | 28        | 0.39%   |
| Supermicro              | 23        | 0.32%   |
| TUXEDO                  | 22        | 0.31%   |
| Clevo                   | 20        | 0.28%   |
| Microsoft               | 19        | 0.27%   |
| Timi                    | 18        | 0.25%   |
| Fujitsu Siemens         | 18        | 0.25%   |
| Alienware               | 18        | 0.25%   |
| UNOWHY                  | 15        | 0.21%   |
| Thomson                 | 15        | 0.21%   |
| Shuttle                 | 14        | 0.2%    |
| Valve                   | 13        | 0.18%   |
| PC Specialist           | 13        | 0.18%   |
| ECS                     | 13        | 0.18%   |
| Chuwi                   | 13        | 0.18%   |
| AZW                     | 12        | 0.17%   |
| Razer                   | 11        | 0.15%   |
| BESSTAR Tech            | 11        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| ASUS All Series          | 106       | 1.48%   |
| Unknown                  | 74        | 1.04%   |
| HP Notebook              | 29        | 0.41%   |
| Gigabyte B450M DS3H      | 26        | 0.36%   |
| HP Pavilion dv6          | 24        | 0.34%   |
| HP Pavilion dv7          | 22        | 0.31%   |
| Dell XPS 13 9310         | 17        | 0.24%   |
| Dell OptiPlex 390        | 17        | 0.24%   |
| HP Pavilion g7           | 16        | 0.22%   |
| HP Pavilion 17           | 16        | 0.22%   |
| Dell OptiPlex 9020       | 16        | 0.22%   |
| MSI MS-7C91              | 14        | 0.2%    |
| Dell XPS 13 7390         | 14        | 0.2%    |
| Dell OptiPlex 7010       | 14        | 0.2%    |
| ASUS PRIME A320M-K       | 14        | 0.2%    |
| Valve Jupiter            | 13        | 0.18%   |
| Dell XPS 15 7590         | 13        | 0.18%   |
| MSI MS-7C37              | 12        | 0.17%   |
| MSI MS-7C02              | 12        | 0.17%   |
| MSI MS-7816              | 12        | 0.17%   |
| HP Pavilion Notebook     | 12        | 0.17%   |
| HP EliteBook 840 G2      | 12        | 0.17%   |
| Dell XPS 15 9570         | 12        | 0.17%   |
| Dell XPS 13 9380         | 12        | 0.17%   |
| Dell Latitude E6420      | 12        | 0.17%   |
| ASUS S551LN              | 12        | 0.17%   |
| MSI MS-7817              | 11        | 0.15%   |
| HUAWEI HVY-WXX9          | 11        | 0.15%   |
| HP Pavilion g6           | 11        | 0.15%   |
| HP Compaq Elite 8300 SFF | 11        | 0.15%   |
| Gigabyte 970A-DS3P       | 11        | 0.15%   |
| Dell OptiPlex 3020       | 11        | 0.15%   |
| MSI MS-7B79              | 10        | 0.14%   |
| MSI MS-7A38              | 10        | 0.14%   |
| MSI MS-7758              | 10        | 0.14%   |
| MSI MS-7693              | 10        | 0.14%   |
| Lenovo G50-30 80G0       | 10        | 0.14%   |
| HP ProBook 650 G1        | 10        | 0.14%   |
| HP Pavilion 15           | 10        | 0.14%   |
| HP OMEN by Laptop        | 10        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 384       | 5.37%   |
| Dell Latitude         | 295       | 4.13%   |
| Acer Aspire           | 238       | 3.33%   |
| HP Pavilion           | 201       | 2.81%   |
| Dell Precision        | 183       | 2.56%   |
| Dell XPS              | 155       | 2.17%   |
| Dell OptiPlex         | 145       | 2.03%   |
| Dell Inspiron         | 135       | 1.89%   |
| HP EliteBook          | 124       | 1.73%   |
| Lenovo IdeaPad        | 122       | 1.71%   |
| ASUS PRIME            | 115       | 1.61%   |
| Toshiba Satellite     | 113       | 1.58%   |
| HP ProBook            | 112       | 1.57%   |
| ASUS All              | 106       | 1.48%   |
| HP Compaq             | 99        | 1.38%   |
| ASUS ROG              | 94        | 1.31%   |
| ASUS VivoBook         | 92        | 1.29%   |
| Lenovo ThinkCentre    | 75        | 1.05%   |
| Unknown               | 74        | 1.04%   |
| ASUS TUF              | 69        | 0.97%   |
| HP Laptop             | 56        | 0.78%   |
| Packard Bell EasyNote | 45        | 0.63%   |
| ASUS ZenBook          | 43        | 0.6%    |
| Dell Vostro           | 42        | 0.59%   |
| Acer Swift            | 39        | 0.55%   |
| Lenovo Legion         | 32        | 0.45%   |
| RPi Raspberry         | 31        | 0.43%   |
| Gigabyte B450M        | 31        | 0.43%   |
| HP Notebook           | 29        | 0.41%   |
| HP ENVY               | 28        | 0.39%   |
| HP ZBook              | 26        | 0.36%   |
| Lenovo Yoga           | 24        | 0.34%   |
| Packard Bell IMEDIA   | 23        | 0.32%   |
| HP ProDesk            | 22        | 0.31%   |
| HP EliteDesk          | 21        | 0.29%   |
| HP OMEN               | 20        | 0.28%   |
| Dell PowerEdge        | 20        | 0.28%   |
| ASUS P8Z77-V          | 20        | 0.28%   |
| Microsoft Surface     | 19        | 0.27%   |
| Gigabyte B450         | 18        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 706       | 9.88%   |
| 2019    | 670       | 9.37%   |
| 2020    | 641       | 8.97%   |
| 2012    | 562       | 7.86%   |
| 2013    | 550       | 7.69%   |
| 2011    | 485       | 6.78%   |
| 2017    | 431       | 6.03%   |
| 2015    | 420       | 5.87%   |
| 2014    | 417       | 5.83%   |
| 2010    | 403       | 5.64%   |
| 2021    | 380       | 5.32%   |
| 2016    | 360       | 5.04%   |
| 2009    | 335       | 4.69%   |
| 2008    | 333       | 4.66%   |
| 2007    | 177       | 2.48%   |
| 2006    | 88        | 1.23%   |
| 2022    | 80        | 1.12%   |
| Unknown | 47        | 0.66%   |
| 2005    | 43        | 0.6%    |
| 2004    | 12        | 0.17%   |
| 2003    | 6         | 0.08%   |
| 2002    | 2         | 0.03%   |
| 2001    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3935      | 55.04%  |
| Desktop        | 2771      | 38.76%  |
| Convertible    | 106       | 1.48%   |
| Mini pc        | 100       | 1.4%    |
| All in one     | 81        | 1.13%   |
| Server         | 58        | 0.81%   |
| Tablet         | 45        | 0.63%   |
| System on chip | 44        | 0.62%   |
| Phone          | 8         | 0.11%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6588      | 91.58%  |
| Enabled  | 606       | 8.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7135      | 99.79%  |
| Yes  | 15        | 0.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1598      | 22.08%  |
| 4.01-8.0        | 1582      | 21.86%  |
| 16.01-24.0      | 1490      | 20.59%  |
| 8.01-16.0       | 1225      | 16.93%  |
| 32.01-64.0      | 572       | 7.9%    |
| 1.01-2.0        | 316       | 4.37%   |
| 64.01-256.0     | 154       | 2.13%   |
| 2.01-3.0        | 124       | 1.71%   |
| 24.01-32.0      | 98        | 1.35%   |
| 0.51-1.0        | 56        | 0.77%   |
| 0.01-0.5        | 10        | 0.14%   |
| More than 256.0 | 6         | 0.08%   |
| Unknown         | 5         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 2858      | 36.54%  |
| 2.01-3.0    | 1882      | 24.06%  |
| 4.01-8.0    | 1078      | 13.78%  |
| 3.01-4.0    | 960       | 12.27%  |
| 0.51-1.0    | 562       | 7.19%   |
| 8.01-16.0   | 294       | 3.76%   |
| 0.01-0.5    | 108       | 1.38%   |
| 16.01-24.0  | 40        | 0.51%   |
| 24.01-32.0  | 15        | 0.19%   |
| 32.01-64.0  | 14        | 0.18%   |
| Unknown     | 9         | 0.12%   |
| 64.01-256.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4275      | 58.31%  |
| 2       | 1847      | 25.19%  |
| 3       | 612       | 8.35%   |
| 4       | 286       | 3.9%    |
| 5       | 134       | 1.83%   |
| 0       | 67        | 0.91%   |
| 6       | 59        | 0.8%    |
| 7       | 30        | 0.41%   |
| 8       | 9         | 0.12%   |
| 9       | 5         | 0.07%   |
| Unknown | 4         | 0.05%   |
| 22      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |
| 11      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3940      | 54.64%  |
| Yes       | 3271      | 45.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6300      | 87.92%  |
| No        | 866       | 12.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5253      | 72.95%  |
| No        | 1948      | 27.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3961      | 54.77%  |
| No        | 3271      | 45.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| France  | 7149      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 1126      | 14.7%   |
| Lyon             | 154       | 2.01%   |
| Marseille        | 129       | 1.68%   |
| Toulouse         | 116       | 1.51%   |
| Nantes           | 98        | 1.28%   |
| Strasbourg       | 85        | 1.11%   |
| Montpellier      | 71        | 0.93%   |
| Lille            | 62        | 0.81%   |
| Rennes           | 61        | 0.8%    |
| Bordeaux         | 56        | 0.73%   |
| Clichy-sous-Bois | 55        | 0.72%   |
| Grenoble         | 54        | 0.7%    |
| Roubaix          | 51        | 0.67%   |
| Nice             | 51        | 0.67%   |
| Brest            | 39        | 0.51%   |
| Tours            | 37        | 0.48%   |
| La Rochelle      | 33        | 0.43%   |
| Villeurbanne     | 30        | 0.39%   |
| Toulon           | 30        | 0.39%   |
| Caen             | 28        | 0.37%   |
| Rouen            | 26        | 0.34%   |
| Poitiers         | 25        | 0.33%   |
| Aix-en-Provence  | 25        | 0.33%   |
| Metz             | 24        | 0.31%   |
| Clermont-Ferrand | 24        | 0.31%   |
| Besançon        | 24        | 0.31%   |
| Amiens           | 24        | 0.31%   |
| Nîmes           | 23        | 0.3%    |
| Nancy            | 23        | 0.3%    |
| Cergy            | 22        | 0.29%   |
| Argenteuil       | 22        | 0.29%   |
| Limoges          | 21        | 0.27%   |
| Versailles       | 20        | 0.26%   |
| Perpignan        | 20        | 0.26%   |
| Pau              | 20        | 0.26%   |
| Orléans         | 20        | 0.26%   |
| Angers           | 20        | 0.26%   |
| Dijon            | 19        | 0.25%   |
| Colmar           | 19        | 0.25%   |
| Saint-Denis      | 18        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1695      | 2560   | 16.17%  |
| Samsung Electronics       | 1595      | 2452   | 15.22%  |
| WDC                       | 1547      | 2322   | 14.76%  |
| Crucial                   | 731       | 1004   | 6.97%   |
| Toshiba                   | 701       | 914    | 6.69%   |
| Kingston                  | 514       | 626    | 4.9%    |
| SanDisk                   | 506       | 623    | 4.83%   |
| Unknown                   | 385       | 516    | 3.67%   |
| Hitachi                   | 344       | 425    | 3.28%   |
| SK hynix                  | 289       | 348    | 2.76%   |
| HGST                      | 282       | 374    | 2.69%   |
| Intel                     | 223       | 276    | 2.13%   |
| Micron Technology         | 164       | 196    | 1.56%   |
| PNY                       | 126       | 147    | 1.2%    |
| Maxtor                    | 89        | 115    | 0.85%   |
| LDLC                      | 79        | 120    | 0.75%   |
| KIOXIA                    | 75        | 85     | 0.72%   |
| Phison                    | 70        | 88     | 0.67%   |
| Transcend                 | 67        | 77     | 0.64%   |
| Corsair                   | 62        | 72     | 0.59%   |
| China                     | 57        | 72     | 0.54%   |
| Apple                     | 53        | 68     | 0.51%   |
| OCZ                       | 46        | 63     | 0.44%   |
| Fujitsu                   | 45        | 62     | 0.43%   |
| Micron/Crucial Technology | 44        | 58     | 0.42%   |
| LITEON                    | 38        | 43     | 0.36%   |
| A-DATA Technology         | 36        | 44     | 0.34%   |
| SPCC                      | 34        | 44     | 0.32%   |
| LITEONIT                  | 27        | 27     | 0.26%   |
| Unknown                   | 25        | 28     | 0.24%   |
| JMicron Technology        | 24        | 29     | 0.23%   |
| Silicon Motion            | 23        | 33     | 0.22%   |
| Gigabyte Technology       | 18        | 22     | 0.17%   |
| Emtec                     | 17        | 20     | 0.16%   |
| Patriot                   | 15        | 21     | 0.14%   |
| Intenso                   | 15        | 16     | 0.14%   |
| ASMT                      | 15        | 18     | 0.14%   |
| Hewlett-Packard           | 14        | 21     | 0.13%   |
| KingSpec                  | 13        | 16     | 0.12%   |
| LaCie                     | 12        | 13     | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 121       | 1.05%   |
| Crucial CT240BX500SSD1 240GB       | 117       | 1.02%   |
| Crucial CT500MX500SSD1 500GB       | 111       | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB     | 96        | 0.83%   |
| HGST HTS721010A9E630 1TB           | 95        | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 87        | 0.76%   |
| Samsung SSD 850 EVO 250GB          | 83        | 0.72%   |
| Kingston SA400S37240G 240GB SSD    | 81        | 0.7%    |
| Toshiba MQ01ABD100 1TB             | 80        | 0.69%   |
| Seagate ST500DM002-1BD142 500GB    | 77        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB     | 75        | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB     | 70        | 0.61%   |
| Samsung SSD 850 EVO 500GB          | 68        | 0.59%   |
| Unknown MMC Card  32GB             | 61        | 0.53%   |
| Samsung SSD 860 EVO 1TB            | 61        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB        | 61        | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB     | 56        | 0.49%   |
| Samsung SSD 860 EVO 250GB          | 55        | 0.48%   |
| Samsung NVMe SSD Drive 512GB       | 55        | 0.48%   |
| Kingston SA400S37120G 120GB SSD    | 53        | 0.46%   |
| Crucial CT480BX500SSD1 480GB       | 53        | 0.46%   |
| Toshiba MQ04ABF100 1TB             | 52        | 0.45%   |
| Seagate ST1000DM003-1ER162 1TB     | 51        | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB     | 49        | 0.43%   |
| Unknown MMC Card  64GB             | 48        | 0.42%   |
| Toshiba DT01ACA100 1TB             | 47        | 0.41%   |
| Samsung NVMe SSD Drive 500GB       | 47        | 0.41%   |
| Unknown SD/MMC/MS PRO 1TB          | 46        | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB     | 46        | 0.4%    |
| Samsung SSD 870 QVO 1TB            | 45        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD   | 45        | 0.39%   |
| HGST HTS541010A9E680 1TB           | 45        | 0.39%   |
| Samsung SSD 860 QVO 1TB            | 43        | 0.37%   |
| SanDisk NVMe SSD Drive 512GB       | 42        | 0.36%   |
| PNY CS900 240GB SSD                | 41        | 0.36%   |
| PNY CS900 120GB SSD                | 41        | 0.36%   |
| Kingston SA400S37480G 480GB SSD    | 41        | 0.36%   |
| Crucial CT120BX500SSD1 120GB       | 37        | 0.32%   |
| Seagate ST500LT012-1DG142 500GB    | 36        | 0.31%   |
| Seagate ST2000DM006-2DM164 2TB     | 36        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1675      | 2505   | 36.26%  |
| WDC                 | 1296      | 1981   | 28.05%  |
| Toshiba             | 533       | 679    | 11.54%  |
| Hitachi             | 344       | 425    | 7.45%   |
| HGST                | 282       | 374    | 6.1%    |
| Samsung Electronics | 218       | 324    | 4.72%   |
| Maxtor              | 89        | 115    | 1.93%   |
| Unknown             | 52        | 60     | 1.13%   |
| Fujitsu             | 44        | 61     | 0.95%   |
| Apple               | 14        | 15     | 0.3%    |
| SABRENT             | 10        | 10     | 0.22%   |
| Hewlett-Packard     | 7         | 13     | 0.15%   |
| Magnetic Data       | 6         | 6      | 0.13%   |
| Inateck             | 5         | 5      | 0.11%   |
| IBM/Hitachi         | 5         | 6      | 0.11%   |
| ASMT                | 5         | 7      | 0.11%   |
| LaCie               | 3         | 3      | 0.06%   |
| JMicron Technology  | 3         | 4      | 0.06%   |
| Intenso             | 3         | 3      | 0.06%   |
| ASMT109x            | 3         | 4      | 0.06%   |
| ASMedia             | 3         | 3      | 0.06%   |
| USB3.0              | 2         | 2      | 0.04%   |
| USB                 | 2         | 2      | 0.04%   |
| RSH-319             | 2         | 3      | 0.04%   |
| PHD 3.0             | 2         | 2      | 0.04%   |
| HGST HTS            | 2         | 2      | 0.04%   |
| Storeva             | 1         | 1      | 0.02%   |
| SILICONMOTION       | 1         | 1      | 0.02%   |
| SATAFIRM            | 1         | 1      | 0.02%   |
| MDT                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| ICY BOX             | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Generic-            | 1         | 1      | 0.02%   |
| DELLBOSS            | 1         | 1      | 0.02%   |
| APPLE HD            | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 889       | 1263   | 25.23%  |
| Crucial             | 661       | 909    | 18.76%  |
| Kingston            | 430       | 523    | 12.21%  |
| SanDisk             | 361       | 444    | 10.25%  |
| PNY                 | 115       | 132    | 3.26%   |
| WDC                 | 100       | 119    | 2.84%   |
| Intel               | 98        | 114    | 2.78%   |
| Micron Technology   | 76        | 101    | 2.16%   |
| SK hynix            | 74        | 93     | 2.1%    |
| Transcend           | 63        | 73     | 1.79%   |
| LDLC                | 57        | 76     | 1.62%   |
| China               | 55        | 70     | 1.56%   |
| OCZ                 | 45        | 59     | 1.28%   |
| Toshiba             | 41        | 55     | 1.16%   |
| Corsair             | 35        | 40     | 0.99%   |
| Apple               | 34        | 46     | 0.97%   |
| LITEON              | 32        | 35     | 0.91%   |
| SPCC                | 31        | 41     | 0.88%   |
| A-DATA Technology   | 29        | 37     | 0.82%   |
| LITEONIT            | 27        | 27     | 0.77%   |
| Emtec               | 15        | 17     | 0.43%   |
| Unknown             | 15        | 17     | 0.43%   |
| Patriot             | 14        | 19     | 0.4%    |
| KingSpec            | 13        | 16     | 0.37%   |
| Intenso             | 11        | 12     | 0.31%   |
| Plextor             | 10        | 11     | 0.28%   |
| Dogfish             | 10        | 14     | 0.28%   |
| ASMT                | 10        | 11     | 0.28%   |
| TEXTORM             | 9         | 10     | 0.26%   |
| Netac               | 8         | 9      | 0.23%   |
| KingDian            | 8         | 10     | 0.23%   |
| BHT                 | 8         | 11     | 0.23%   |
| Apacer              | 8         | 8      | 0.23%   |
| Verbatim            | 7         | 7      | 0.2%    |
| Unknown             | 6         | 10     | 0.17%   |
| TCSUNBOW            | 6         | 9      | 0.17%   |
| Gigabyte Technology | 6         | 9      | 0.17%   |
| BAITITON            | 6         | 6      | 0.17%   |
| TO Exter            | 5         | 5      | 0.14%   |
| GALAX               | 5         | 5      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3873      | 6624   | 41.38%  |
| SSD     | 3068      | 4578   | 32.78%  |
| NVMe    | 1931      | 2614   | 20.63%  |
| MMC     | 337       | 458    | 3.6%    |
| Unknown | 150       | 219    | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5562      | 10908  | 67.93%  |
| NVMe | 1916      | 2588   | 23.4%   |
| SAS  | 373       | 539    | 4.56%   |
| MMC  | 337       | 458    | 4.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4111      | 6509   | 56.53%  |
| 0.51-1.0   | 2198      | 3162   | 30.23%  |
| 1.01-2.0   | 602       | 953    | 8.28%   |
| 3.01-4.0   | 168       | 271    | 2.31%   |
| 2.01-3.0   | 116       | 174    | 1.6%    |
| 4.01-10.0  | 66        | 116    | 0.91%   |
| 10.01-20.0 | 11        | 17     | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1914      | 25.46%  |
| 251-500        | 1678      | 22.32%  |
| 501-1000       | 1198      | 15.94%  |
| 1001-2000      | 597       | 7.94%   |
| 1-20           | 595       | 7.92%   |
| 51-100         | 418       | 5.56%   |
| More than 3000 | 341       | 4.54%   |
| 21-50          | 290       | 3.86%   |
| Unknown        | 253       | 3.37%   |
| 2001-3000      | 233       | 3.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2848      | 36.63%  |
| 21-50          | 1192      | 15.33%  |
| 101-250        | 988       | 12.71%  |
| 51-100         | 908       | 11.68%  |
| 251-500        | 634       | 8.16%   |
| 501-1000       | 474       | 6.1%    |
| 1001-2000      | 267       | 3.43%   |
| Unknown        | 253       | 3.25%   |
| More than 3000 | 116       | 1.49%   |
| 2001-3000      | 91        | 1.17%   |
| 0              | 3         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB              | 17        | 21     | 2.04%   |
| HGST HTS541010A9E680 1TB              | 11        | 11     | 1.32%   |
| Seagate ST500DM002-1BD142 500GB       | 10        | 11     | 1.2%    |
| Toshiba MQ01ABD100 1TB                | 9         | 11     | 1.08%   |
| Seagate ST9500325AS 500GB             | 9         | 10     | 1.08%   |
| Seagate ST500LM021-1KJ152 500GB       | 8         | 10     | 0.96%   |
| WDC WD10JPVX-22JC3T0 1TB              | 7         | 7      | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB        | 7         | 7      | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 7         | 7      | 0.84%   |
| Seagate ST2000DM001-1CH164 2TB        | 6         | 7      | 0.72%   |
| Kingston SV300S37A120G 120GB SSD      | 6         | 8      | 0.72%   |
| HGST HTS725050A7E630 500GB            | 6         | 8      | 0.72%   |
| Toshiba MQ01ABD050 500GB              | 5         | 5      | 0.6%    |
| Seagate ST500LT012-1DG142 500GB       | 5         | 5      | 0.6%    |
| Seagate ST31000524AS 1TB              | 5         | 5      | 0.6%    |
| Seagate ST1000DM003-1CH162 1TB        | 5         | 5      | 0.6%    |
| Hitachi HTS727575A9E364 752GB         | 5         | 5      | 0.6%    |
| Hitachi HTS545050B9A300 500GB         | 5         | 5      | 0.6%    |
| Crucial CT525MX300SSD1 528GB          | 5         | 5      | 0.6%    |
| WDC WD5000AAKX-001CA0 500GB           | 4         | 4      | 0.48%   |
| WDC WD3200AAKS-00L9A0 320GB           | 4         | 4      | 0.48%   |
| WDC WD10EADS-22M2B0 1TB               | 4         | 4      | 0.48%   |
| WDC WD10EADS-00M2B0 1TB               | 4         | 6      | 0.48%   |
| Toshiba MK5055GSX 500GB               | 4         | 4      | 0.48%   |
| Toshiba MK3265GSX 320GB               | 4         | 5      | 0.48%   |
| Toshiba DT01ACA100 1TB                | 4         | 5      | 0.48%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 4         | 4      | 0.48%   |
| Seagate ST3500320AS 500GB             | 4         | 4      | 0.48%   |
| Seagate ST1000LM048-2E7172 1TB        | 4         | 4      | 0.48%   |
| Samsung Electronics HD321KJ 320GB     | 4         | 4      | 0.48%   |
| Samsung Electronics HD103SJ 1TB       | 4         | 5      | 0.48%   |
| LDLC SSD 120GB                        | 4         | 6      | 0.48%   |
| Hitachi HTS547575A9E384 752GB         | 4         | 4      | 0.48%   |
| Hitachi HTS545050A7E380 500GB         | 4         | 4      | 0.48%   |
| Hitachi HTS543232A7A384 320GB         | 4         | 6      | 0.48%   |
| Crucial CT275MX300SSD1 275GB          | 4         | 5      | 0.48%   |
| Crucial CT120M500SSD1 120GB           | 4         | 5      | 0.48%   |
| WDC WD6400AAKS-22A7B2 640GB           | 3         | 5      | 0.36%   |
| WDC WD5000BEKT-75KA9T0 500GB          | 3         | 3      | 0.36%   |
| WDC WD5000AADS-00S9B0 500GB           | 3         | 3      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 196       | 225    | 23.82%  |
| WDC                 | 179       | 211    | 21.75%  |
| Hitachi             | 77        | 86     | 9.36%   |
| Toshiba             | 59        | 69     | 7.17%   |
| Samsung Electronics | 57        | 63     | 6.93%   |
| HGST                | 47        | 53     | 5.71%   |
| Crucial             | 29        | 32     | 3.52%   |
| Maxtor              | 25        | 29     | 3.04%   |
| Intel               | 25        | 27     | 3.04%   |
| Kingston            | 24        | 27     | 2.92%   |
| SK hynix            | 20        | 26     | 2.43%   |
| SanDisk             | 17        | 20     | 2.07%   |
| Fujitsu             | 8         | 8      | 0.97%   |
| OCZ                 | 7         | 7      | 0.85%   |
| Micron Technology   | 6         | 8      | 0.73%   |
| LDLC                | 6         | 8      | 0.73%   |
| LITEONIT            | 4         | 4      | 0.49%   |
| Corsair             | 4         | 4      | 0.49%   |
| A-DATA Technology   | 4         | 4      | 0.49%   |
| Apacer              | 3         | 3      | 0.36%   |
| SPCC                | 2         | 2      | 0.24%   |
| LITEON              | 2         | 2      | 0.24%   |
| KingSpec            | 2         | 2      | 0.24%   |
| Dogfish             | 2         | 2      | 0.24%   |
| China               | 2         | 2      | 0.24%   |
| Unknown             | 1         | 1      | 0.12%   |
| TEXTORM             | 1         | 1      | 0.12%   |
| TakeMS              | 1         | 1      | 0.12%   |
| Phison              | 1         | 1      | 0.12%   |
| OCZ-VERTEX          | 1         | 1      | 0.12%   |
| Netac               | 1         | 1      | 0.12%   |
| Magnetic Data       | 1         | 1      | 0.12%   |
| JMicron Technology  | 1         | 1      | 0.12%   |
| Intenso             | 1         | 1      | 0.12%   |
| INNOVATION IT       | 1         | 1      | 0.12%   |
| IBM/Hitachi         | 1         | 1      | 0.12%   |
| Hewlett-Packard     | 1         | 1      | 0.12%   |
| ASMT                | 1         | 1      | 0.12%   |
| ASENNO              | 1         | 1      | 0.12%   |
| Apple               | 1         | 1      | 0.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 196       | 225    | 31.16%  |
| WDC                 | 177       | 209    | 28.14%  |
| Hitachi             | 77        | 86     | 12.24%  |
| Toshiba             | 56        | 66     | 8.9%    |
| HGST                | 47        | 53     | 7.47%   |
| Samsung Electronics | 39        | 42     | 6.2%    |
| Maxtor              | 25        | 29     | 3.97%   |
| Fujitsu             | 8         | 8      | 1.27%   |
| Unknown             | 1         | 1      | 0.16%   |
| Magnetic Data       | 1         | 1      | 0.16%   |
| IBM/Hitachi         | 1         | 1      | 0.16%   |
| Hewlett-Packard     | 1         | 1      | 0.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 585       | 722    | 75.39%  |
| SSD     | 177       | 201    | 22.81%  |
| NVMe    | 13        | 16     | 1.68%   |
| Unknown | 1         | 1      | 0.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB                     | 2         | 2      | 7.41%   |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 7.41%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 7.41%   |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 3.7%    |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 3.7%    |
| WDC WD20EARS-00J99B0 2TB                         | 1         | 1      | 3.7%    |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 3.7%    |
| WDC WD10EALX-759BA1 1TB                          | 1         | 1      | 3.7%    |
| Toshiba MQ02ABF050H 500GB                        | 1         | 1      | 3.7%    |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 3.7%    |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 3.7%    |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 3.7%    |
| Toshiba MK3259GSXP 320GB                         | 1         | 1      | 3.7%    |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 1         | 1      | 3.7%    |
| Seagate ST3500418ASQ 500GB                       | 1         | 1      | 3.7%    |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 3.7%    |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 3.7%    |
| Seagate ST1000LM048-2E7172 1TB                   | 1         | 1      | 3.7%    |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 3.7%    |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 3.7%    |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 3.7%    |
| Samsung Electronics HD501LJ 500GB                | 1         | 1      | 3.7%    |
| Kingston SMS200S360G 64GB SSD                    | 1         | 1      | 3.7%    |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 3.7%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 33.33%  |
| Samsung Electronics | 6         | 10     | 22.22%  |
| Toshiba             | 5         | 5      | 18.52%  |
| Seagate             | 4         | 4      | 14.81%  |
| SK hynix            | 1         | 1      | 3.7%    |
| Kingston            | 1         | 1      | 3.7%    |
| HGST                | 1         | 1      | 3.7%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3659      | 7606   | 46.65%  |
| Works    | 3401      | 5915   | 43.36%  |
| Malfunc  | 756       | 940    | 9.64%   |
| Failed   | 27        | 31     | 0.34%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4919      | 55.79%  |
| AMD                              | 1252      | 14.2%   |
| Samsung Electronics              | 647       | 7.34%   |
| SanDisk                          | 303       | 3.44%   |
| SK hynix                         | 209       | 2.37%   |
| Nvidia                           | 178       | 2.02%   |
| Toshiba America Info Systems     | 149       | 1.69%   |
| Marvell Technology Group         | 147       | 1.67%   |
| JMicron Technology               | 123       | 1.4%    |
| Phison Electronics               | 122       | 1.38%   |
| Micron/Crucial Technology        | 118       | 1.34%   |
| ASMedia Technology               | 113       | 1.28%   |
| Micron Technology                | 95        | 1.08%   |
| Kingston Technology Company      | 94        | 1.07%   |
| KIOXIA                           | 70        | 0.79%   |
| VIA Technologies                 | 49        | 0.56%   |
| Silicon Motion                   | 32        | 0.36%   |
| LSI Logic / Symbios Logic        | 23        | 0.26%   |
| Silicon Image                    | 20        | 0.23%   |
| Broadcom / LSI                   | 19        | 0.22%   |
| Union Memory (Shenzhen)          | 17        | 0.19%   |
| Silicon Integrated Systems [SiS] | 17        | 0.19%   |
| Lite-On Technology               | 16        | 0.18%   |
| ADATA Technology                 | 11        | 0.12%   |
| Solid State Storage Technology   | 9         | 0.1%    |
| Adaptec                          | 9         | 0.1%    |
| Seagate Technology               | 8         | 0.09%   |
| Yangtze Memory Technologies      | 7         | 0.08%   |
| Lenovo                           | 6         | 0.07%   |
| Integrated Technology Express    | 6         | 0.07%   |
| Hewlett-Packard                  | 6         | 0.07%   |
| Realtek Semiconductor            | 5         | 0.06%   |
| Apple                            | 5         | 0.06%   |
| ULi Electronics                  | 2         | 0.02%   |
| Promise Technology               | 2         | 0.02%   |
| Transcend                        | 1         | 0.01%   |
| Tekram Technology                | 1         | 0.01%   |
| Shenzhen Longsys Electronics     | 1         | 0.01%   |
| OCZ Technology Group             | 1         | 0.01%   |
| O2 Micro                         | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 835       | 8.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 400       | 3.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 334       | 3.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 308       | 3.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 304       | 2.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 242       | 2.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 192       | 1.88%   |
| AMD 400 Series Chipset SATA Controller                                         | 190       | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 184       | 1.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 176       | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 171       | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 170       | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 169       | 1.65%   |
| Intel Volume Management Device NVMe RAID Controller                            | 154       | 1.5%    |
| Intel SATA Controller [RAID mode]                                              | 152       | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 141       | 1.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 139       | 1.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 138       | 1.35%   |
| Samsung NVMe SSD Controller 980                                                | 131       | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 130       | 1.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 125       | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 117       | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 112       | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 109       | 1.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 103       | 1.01%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 103       | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 101       | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 96        | 0.94%   |
| Micron Non-Volatile memory controller                                          | 95        | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 89        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 88        | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 85        | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 84        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 83        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 83        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 81        | 0.79%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 79        | 0.77%   |
| AMD 500 Series Chipset SATA Controller                                         | 76        | 0.74%   |
| Nvidia MCP61 SATA Controller                                                   | 69        | 0.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 68        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5124      | 57.54%  |
| NVMe | 1943      | 21.82%  |
| IDE  | 1128      | 12.67%  |
| RAID | 667       | 7.49%   |
| SAS  | 27        | 0.3%    |
| SCSI | 16        | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5536      | 77.44%  |
| AMD                   | 1554      | 21.74%  |
| ARM                   | 50        | 0.7%    |
| QUALCOMM              | 4         | 0.06%   |
| CentaurHauls          | 3         | 0.04%   |
| Marvell Semiconductor | 1         | 0.01%   |
| Unknown               | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 96        | 1.34%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 64        | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 63        | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 62        | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 60        | 0.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 59        | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 55        | 0.77%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 52        | 0.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 51        | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 48        | 0.67%   |
| AMD Ryzen 5 3600 6-Core Processor             | 48        | 0.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 44        | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 44        | 0.61%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 44        | 0.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 44        | 0.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 43        | 0.6%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 41        | 0.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 41        | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 40        | 0.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 40        | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 40        | 0.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 38        | 0.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 36        | 0.5%    |
| ARM Processor                                 | 35        | 0.49%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 34        | 0.47%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 33        | 0.46%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 32        | 0.45%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 31        | 0.43%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 31        | 0.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 30        | 0.42%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 30        | 0.42%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 29        | 0.4%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 28        | 0.39%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 28        | 0.39%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 28        | 0.39%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 27        | 0.38%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 27        | 0.38%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 26        | 0.36%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 26        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1599      | 22.34%  |
| Intel Core i7           | 1358      | 18.97%  |
| Intel Core i3           | 560       | 7.82%   |
| Other                   | 390       | 5.45%   |
| AMD Ryzen 5             | 346       | 4.83%   |
| Intel Core 2 Duo        | 339       | 4.74%   |
| Intel Celeron           | 309       | 4.32%   |
| AMD Ryzen 7             | 256       | 3.58%   |
| Intel Pentium           | 214       | 2.99%   |
| Intel Xeon              | 185       | 2.58%   |
| Intel Atom              | 149       | 2.08%   |
| Intel Pentium Dual-Core | 104       | 1.45%   |
| Intel Core 2 Quad       | 81        | 1.13%   |
| AMD Ryzen 9             | 76        | 1.06%   |
| AMD FX                  | 76        | 1.06%   |
| AMD Ryzen 3             | 68        | 0.95%   |
| AMD A4                  | 61        | 0.85%   |
| Intel Pentium Dual      | 60        | 0.84%   |
| AMD Athlon II X2        | 58        | 0.81%   |
| AMD E1                  | 54        | 0.75%   |
| Intel Core 2            | 53        | 0.74%   |
| AMD Athlon 64 X2        | 52        | 0.73%   |
| Intel Core i9           | 49        | 0.68%   |
| AMD A6                  | 42        | 0.59%   |
| AMD A8                  | 39        | 0.54%   |
| AMD Phenom II X4        | 38        | 0.53%   |
| AMD E2                  | 37        | 0.52%   |
| AMD E                   | 32        | 0.45%   |
| Intel Pentium 4         | 31        | 0.43%   |
| AMD Ryzen 7 PRO         | 29        | 0.41%   |
| Intel Genuine           | 26        | 0.36%   |
| AMD Athlon              | 23        | 0.32%   |
| Intel Pentium Silver    | 19        | 0.27%   |
| AMD Athlon 64           | 19        | 0.27%   |
| Intel Pentium D         | 17        | 0.24%   |
| AMD Ryzen 5 PRO         | 16        | 0.22%   |
| AMD A10                 | 16        | 0.22%   |
| AMD Sempron             | 15        | 0.21%   |
| Intel Pentium Gold      | 13        | 0.18%   |
| AMD Ryzen Threadripper  | 13        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2877      | 40.15%  |
| 4       | 2740      | 38.24%  |
| 6       | 648       | 9.04%   |
| 8       | 441       | 6.15%   |
| 1       | 210       | 2.93%   |
| 12      | 93        | 1.3%    |
| 3       | 38        | 0.53%   |
| Unknown | 35        | 0.49%   |
| 16      | 20        | 0.28%   |
| 10      | 17        | 0.24%   |
| 14      | 12        | 0.17%   |
| 20      | 10        | 0.14%   |
| 32      | 8         | 0.11%   |
| 24      | 6         | 0.08%   |
| 64      | 4         | 0.06%   |
| 40      | 2         | 0.03%   |
| 104     | 1         | 0.01%   |
| 48      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7076      | 98.91%  |
| 2       | 71        | 0.99%   |
| Unknown | 5         | 0.07%   |
| 4       | 1         | 0.01%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4411      | 61.52%  |
| 1       | 2723      | 37.98%  |
| Unknown | 35        | 0.49%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6984      | 97.5%   |
| Unknown        | 111       | 1.55%   |
| 32-bit         | 64        | 0.89%   |
| 64-bit         | 4         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1292      | 17.54%  |
| 0x306c3    | 444       | 6.03%   |
| 0x206a7    | 436       | 5.92%   |
| 0x306a9    | 430       | 5.84%   |
| 0x1067a    | 311       | 4.22%   |
| 0x906ea    | 242       | 3.28%   |
| 0x506e3    | 198       | 2.69%   |
| 0x806ec    | 180       | 2.44%   |
| 0x806c1    | 169       | 2.29%   |
| 0x806ea    | 148       | 2.01%   |
| 0x906e9    | 143       | 1.94%   |
| 0x306d4    | 137       | 1.86%   |
| 0x40651    | 135       | 1.83%   |
| 0x406e3    | 130       | 1.76%   |
| 0x806e9    | 129       | 1.75%   |
| 0x20655    | 123       | 1.67%   |
| 0x6fd      | 122       | 1.66%   |
| 0x010000c8 | 90        | 1.22%   |
| 0x08108109 | 86        | 1.17%   |
| 0x10676    | 85        | 1.15%   |
| 0x08701021 | 79        | 1.07%   |
| 0x406c4    | 72        | 0.98%   |
| 0x08600106 | 70        | 0.95%   |
| 0x0800820d | 68        | 0.92%   |
| 0xa0652    | 63        | 0.86%   |
| 0x30678    | 61        | 0.83%   |
| 0x106e5    | 58        | 0.79%   |
| 0x906ed    | 56        | 0.76%   |
| 0x706e5    | 55        | 0.75%   |
| 0x08701013 | 49        | 0.67%   |
| 0x06001119 | 49        | 0.67%   |
| 0x06000852 | 49        | 0.67%   |
| 0x806eb    | 47        | 0.64%   |
| 0x07030105 | 47        | 0.64%   |
| 0x406c3    | 46        | 0.62%   |
| 0x706a1    | 45        | 0.61%   |
| 0x6fb      | 43        | 0.58%   |
| 0x506c9    | 43        | 0.58%   |
| 0x05000119 | 43        | 0.58%   |
| 0x20652    | 41        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1160      | 16.21%  |
| Haswell          | 709       | 9.91%   |
| SandyBridge      | 512       | 7.16%   |
| IvyBridge        | 499       | 6.98%   |
| Penryn           | 457       | 6.39%   |
| Skylake          | 422       | 5.9%    |
| Zen 2            | 307       | 4.29%   |
| Core             | 257       | 3.59%   |
| Zen+             | 231       | 3.23%   |
| Silvermont       | 222       | 3.1%    |
| Westmere         | 205       | 2.87%   |
| TigerLake        | 200       | 2.8%    |
| Broadwell        | 179       | 2.5%    |
| K10              | 174       | 2.43%   |
| CometLake        | 155       | 2.17%   |
| Unknown          | 151       | 2.11%   |
| Zen 3            | 126       | 1.76%   |
| Zen              | 124       | 1.73%   |
| Piledriver       | 124       | 1.73%   |
| IceLake          | 114       | 1.59%   |
| K8 Hammer        | 108       | 1.51%   |
| Nehalem          | 99        | 1.38%   |
| Goldmont plus    | 85        | 1.19%   |
| Bobcat           | 74        | 1.03%   |
| Puma             | 65        | 0.91%   |
| Excavator        | 65        | 0.91%   |
| Bonnell          | 61        | 0.85%   |
| Goldmont         | 53        | 0.74%   |
| NetBurst         | 52        | 0.73%   |
| Jaguar           | 39        | 0.55%   |
| Alderlake Hybrid | 34        | 0.48%   |
| K10 Llano        | 24        | 0.34%   |
| P6               | 22        | 0.31%   |
| Steamroller      | 12        | 0.17%   |
| Bulldozer        | 11        | 0.15%   |
| K8 & K10 hybrid  | 10        | 0.14%   |
| Tremont          | 6         | 0.08%   |
| K6               | 5         | 0.07%   |
| Sapphire Rapids  | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3996      | 47.21%  |
| Nvidia                                       | 2630      | 31.07%  |
| AMD                                          | 1749      | 20.66%  |
| Matrox Electronics Systems                   | 41        | 0.48%   |
| ASPEED Technology                            | 24        | 0.28%   |
| Silicon Integrated Systems [SiS]             | 10        | 0.12%   |
| VIA Technologies                             | 9         | 0.11%   |
| ATI Technologies                             | 3         | 0.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 347       | 3.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 276       | 3.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 202       | 2.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 190       | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 167       | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 156       | 1.79%   |
| Intel UHD Graphics 620                                                                   | 148       | 1.7%    |
| Intel HD Graphics 530                                                                    | 144       | 1.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 141       | 1.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 139       | 1.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 138       | 1.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 138       | 1.59%   |
| AMD Renoir                                                                               | 138       | 1.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 137       | 1.57%   |
| Intel HD Graphics 5500                                                                   | 131       | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 131       | 1.51%   |
| Intel HD Graphics 620                                                                    | 130       | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 128       | 1.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 107       | 1.23%   |
| Intel HD Graphics 630                                                                    | 100       | 1.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 92        | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 87        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 84        | 0.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 75        | 0.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 71        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 69        | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 67        | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 66        | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 61        | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 59        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 59        | 0.68%   |
| AMD Cezanne                                                                              | 58        | 0.67%   |
| Nvidia GT218 [GeForce 210]                                                               | 55        | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 52        | 0.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 48        | 0.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 48        | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 47        | 0.54%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 44        | 0.51%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 44        | 0.51%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 44        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 2747      | 38.13%  |
| 1 x Nvidia           | 1534      | 21.29%  |
| 1 x AMD              | 1381      | 19.17%  |
| Intel + Nvidia       | 994       | 13.8%   |
| Intel + AMD          | 177       | 2.46%   |
| 2 x AMD              | 106       | 1.47%   |
| AMD + Nvidia         | 88        | 1.22%   |
| Other                | 62        | 0.86%   |
| 1 x Matrox           | 36        | 0.5%    |
| 2 x Nvidia           | 23        | 0.32%   |
| 1 x ASPEED           | 21        | 0.29%   |
| 1 x SiS              | 10        | 0.14%   |
| 1 x VIA              | 9         | 0.12%   |
| 2 x Intel            | 4         | 0.06%   |
| Nvidia + Matrox      | 4         | 0.06%   |
| AMD + ASPEED         | 2         | 0.03%   |
| 3 x Nvidia           | 1         | 0.01%   |
| 3 x AMD              | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.01%   |
| 1 x XGI              | 1         | 0.01%   |
| 1 x S3 Graphics      | 1         | 0.01%   |
| Nvidia + ASPEED      | 1         | 0.01%   |
| Intel + 2 x Nvidia   | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5661      | 77.99%  |
| Proprietary | 1278      | 17.61%  |
| Unknown     | 320       | 4.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3728      | 50.87%  |
| 0.01-0.5   | 1018      | 13.89%  |
| 1.01-2.0   | 943       | 12.87%  |
| 0.51-1.0   | 624       | 8.52%   |
| 3.01-4.0   | 482       | 6.58%   |
| 7.01-8.0   | 228       | 3.11%   |
| 5.01-6.0   | 169       | 2.31%   |
| 8.01-16.0  | 63        | 0.86%   |
| 2.01-3.0   | 61        | 0.83%   |
| 16.01-24.0 | 8         | 0.11%   |
| 4.01-5.0   | 4         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1008      | 12.79%  |
| AU Optronics            | 953       | 12.09%  |
| LG Display              | 618       | 7.84%   |
| Chimei Innolux          | 605       | 7.67%   |
| BOE                     | 538       | 6.82%   |
| Dell                    | 412       | 5.23%   |
| Iiyama                  | 411       | 5.21%   |
| Hewlett-Packard         | 314       | 3.98%   |
| Acer                    | 280       | 3.55%   |
| Goldstar                | 273       | 3.46%   |
| Ancor Communications    | 226       | 2.87%   |
| Philips                 | 196       | 2.49%   |
| AOC                     | 176       | 2.23%   |
| Sharp                   | 163       | 2.07%   |
| BenQ                    | 153       | 1.94%   |
| Lenovo                  | 132       | 1.67%   |
| Chi Mei Optoelectronics | 132       | 1.67%   |
| Apple                   | 117       | 1.48%   |
| ViewSonic               | 97        | 1.23%   |
| PANDA                   | 60        | 0.76%   |
| LG Philips              | 57        | 0.72%   |
| ASUSTek Computer        | 57        | 0.72%   |
| InfoVision              | 52        | 0.66%   |
| HannStar                | 47        | 0.6%    |
| Sony                    | 42        | 0.53%   |
| Unknown                 | 41        | 0.52%   |
| Packard Bell            | 31        | 0.39%   |
| LG Electronics          | 29        | 0.37%   |
| Fujitsu Siemens         | 28        | 0.36%   |
| Vestel Elektronik       | 27        | 0.34%   |
| Idek Iiyama             | 27        | 0.34%   |
| NEC Computers           | 23        | 0.29%   |
| Toshiba                 | 21        | 0.27%   |
| Medion                  | 21        | 0.27%   |
| Panasonic               | 20        | 0.25%   |
| Hitachi                 | 20        | 0.25%   |
| Eizo                    | 20        | 0.25%   |
| CPT                     | 18        | 0.23%   |
| SNC                     | 15        | 0.19%   |
| MSI                     | 15        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 40        | 0.49%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                     | 36        | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 35        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 32        | 0.39%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 29        | 0.36%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 27        | 0.33%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch      | 24        | 0.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 24        | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 23        | 0.28%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 23        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 23        | 0.28%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 23        | 0.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 23        | 0.28%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 22        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 21        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 21        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 19        | 0.23%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 18        | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 18        | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 18        | 0.22%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 18        | 0.22%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 17        | 0.21%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 16        | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 16        | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch         | 15        | 0.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 15        | 0.18%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                     | 15        | 0.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 15        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 15        | 0.18%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 15        | 0.18%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 15        | 0.18%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 14        | 0.17%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 14        | 0.17%   |
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                      | 14        | 0.17%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 13        | 0.16%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                      | 13        | 0.16%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                  | 13        | 0.16%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 13        | 0.16%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 13        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3352      | 44.81%  |
| 1366x768 (WXGA)    | 1121      | 14.99%  |
| 1600x900 (HD+)     | 477       | 6.38%   |
| 3840x2160 (4K)     | 343       | 4.59%   |
| 1680x1050 (WSXGA+) | 312       | 4.17%   |
| 2560x1440 (QHD)    | 311       | 4.16%   |
| 1280x1024 (SXGA)   | 295       | 3.94%   |
| 1440x900 (WXGA+)   | 233       | 3.11%   |
| 1920x1200 (WUXGA)  | 219       | 2.93%   |
| 1280x800 (WXGA)    | 170       | 2.27%   |
| Unknown            | 105       | 1.4%    |
| 3840x1080          | 45        | 0.6%    |
| 1360x768           | 45        | 0.6%    |
| 3440x1440          | 44        | 0.59%   |
| 2560x1080          | 42        | 0.56%   |
| 2560x1600          | 31        | 0.41%   |
| 1600x1200          | 30        | 0.4%    |
| 1024x600           | 30        | 0.4%    |
| 1024x768 (XGA)     | 24        | 0.32%   |
| 2160x1440          | 22        | 0.29%   |
| 2880x1800          | 20        | 0.27%   |
| 1920x540           | 16        | 0.21%   |
| 3840x2400          | 15        | 0.2%    |
| 800x1280           | 14        | 0.19%   |
| 3200x1800 (QHD+)   | 12        | 0.16%   |
| 4480x1440          | 8         | 0.11%   |
| 3840x1600          | 7         | 0.09%   |
| 3200x1080          | 7         | 0.09%   |
| 2736x1824          | 7         | 0.09%   |
| 3000x2000          | 6         | 0.08%   |
| 2288x1287          | 6         | 0.08%   |
| 1680x945           | 6         | 0.08%   |
| 5760x2160          | 5         | 0.07%   |
| 3840x1200          | 5         | 0.07%   |
| 3600x1080          | 5         | 0.07%   |
| 1280x720 (HD)      | 5         | 0.07%   |
| 5760x1080          | 4         | 0.05%   |
| 2048x1152          | 4         | 0.05%   |
| 1920x515           | 4         | 0.05%   |
| 1400x1050          | 4         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1736      | 22.14%  |
| 17      | 775       | 9.88%   |
| 13      | 673       | 8.58%   |
| 24      | 630       | 8.03%   |
| 23      | 624       | 7.96%   |
| 27      | 571       | 7.28%   |
| 21      | 457       | 5.83%   |
| 14      | 452       | 5.76%   |
| Unknown | 403       | 5.14%   |
| 19      | 277       | 3.53%   |
| 22      | 213       | 2.72%   |
| 12      | 135       | 1.72%   |
| 20      | 132       | 1.68%   |
| 18      | 124       | 1.58%   |
| 31      | 91        | 1.16%   |
| 34      | 70        | 0.89%   |
| 11      | 67        | 0.85%   |
| 84      | 52        | 0.66%   |
| 16      | 45        | 0.57%   |
| 10      | 45        | 0.57%   |
| 72      | 40        | 0.51%   |
| 32      | 33        | 0.42%   |
| 25      | 32        | 0.41%   |
| 54      | 26        | 0.33%   |
| 33      | 18        | 0.23%   |
| 26      | 18        | 0.23%   |
| 46      | 13        | 0.17%   |
| 40      | 11        | 0.14%   |
| 65      | 7         | 0.09%   |
| 48      | 7         | 0.09%   |
| 52      | 6         | 0.08%   |
| 49      | 6         | 0.08%   |
| 29      | 6         | 0.08%   |
| 43      | 5         | 0.06%   |
| 42      | 5         | 0.06%   |
| 37      | 5         | 0.06%   |
| 39      | 4         | 0.05%   |
| 38      | 4         | 0.05%   |
| 35      | 4         | 0.05%   |
| 142     | 3         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2578      | 33.57%  |
| 501-600        | 1672      | 21.77%  |
| 401-500        | 1030      | 13.41%  |
| 351-400        | 881       | 11.47%  |
| 201-300        | 625       | 8.14%   |
| Unknown        | 403       | 5.25%   |
| 601-700        | 161       | 2.1%    |
| 701-800        | 121       | 1.58%   |
| 1501-2000      | 94        | 1.22%   |
| 1001-1500      | 73        | 0.95%   |
| 801-900        | 29        | 0.38%   |
| 901-1000       | 7         | 0.09%   |
| More than 2000 | 3         | 0.04%   |
| 101-200        | 2         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5215      | 73.85%  |
| 16/10   | 955       | 13.52%  |
| Unknown | 327       | 4.63%   |
| 5/4     | 283       | 4.01%   |
| 21/9    | 84        | 1.19%   |
| 4/3     | 73        | 1.03%   |
| 3/2     | 70        | 0.99%   |
| 0.62    | 15        | 0.21%   |
| 6/5     | 12        | 0.17%   |
| 32/9    | 11        | 0.16%   |
| 3.20    | 4         | 0.06%   |
| 3.73    | 3         | 0.04%   |
| 1.00    | 3         | 0.04%   |
| 11/10   | 2         | 0.03%   |
| 3.88    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1749      | 22.54%  |
| 201-250        | 1539      | 19.84%  |
| 81-90          | 799       | 10.3%   |
| 301-350        | 590       | 7.6%    |
| 151-200        | 571       | 7.36%   |
| 121-130        | 536       | 6.91%   |
| Unknown        | 403       | 5.19%   |
| 71-80          | 335       | 4.32%   |
| 251-300        | 229       | 2.95%   |
| 351-500        | 217       | 2.8%    |
| 141-150        | 217       | 2.8%    |
| More than 1000 | 142       | 1.83%   |
| 61-70          | 117       | 1.51%   |
| 131-140        | 102       | 1.31%   |
| 51-60          | 67        | 0.86%   |
| 501-1000       | 61        | 0.79%   |
| 41-50          | 46        | 0.59%   |
| 111-120        | 23        | 0.3%    |
| 91-100         | 14        | 0.18%   |
| 1-40           | 2         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2749      | 36.45%  |
| 101-120       | 1931      | 25.6%   |
| 121-160       | 1851      | 24.54%  |
| Unknown       | 403       | 5.34%   |
| 161-240       | 358       | 4.75%   |
| More than 240 | 137       | 1.82%   |
| 1-50          | 113       | 1.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5669      | 77.62%  |
| 2     | 1151      | 15.76%  |
| 0     | 352       | 4.82%   |
| 3     | 124       | 1.7%    |
| 4     | 6         | 0.08%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3810      | 35.81%  |
| Intel                             | 3385      | 31.81%  |
| Qualcomm Atheros                  | 1331      | 12.51%  |
| Broadcom                          | 612       | 5.75%   |
| Marvell Technology Group          | 170       | 1.6%    |
| Nvidia                            | 133       | 1.25%   |
| Broadcom Limited                  | 124       | 1.17%   |
| Ralink                            | 122       | 1.15%   |
| TP-Link                           | 87        | 0.82%   |
| Ralink Technology                 | 65        | 0.61%   |
| MediaTek                          | 65        | 0.61%   |
| NetGear                           | 62        | 0.58%   |
| ASIX Electronics                  | 46        | 0.43%   |
| Samsung Electronics               | 45        | 0.42%   |
| Dell                              | 40        | 0.38%   |
| D-Link System                     | 33        | 0.31%   |
| Xiaomi                            | 29        | 0.27%   |
| Huawei Technologies               | 24        | 0.23%   |
| VIA Technologies                  | 23        | 0.22%   |
| Ericsson Business Mobile Networks | 23        | 0.22%   |
| D-Link                            | 23        | 0.22%   |
| Microsoft                         | 21        | 0.2%    |
| DisplayLink                       | 21        | 0.2%    |
| Sierra Wireless                   | 19        | 0.18%   |
| JMicron Technology                | 19        | 0.18%   |
| Aquantia                          | 19        | 0.18%   |
| Belkin Components                 | 17        | 0.16%   |
| Qualcomm                          | 16        | 0.15%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.13%   |
| Qualcomm Atheros Communications   | 14        | 0.13%   |
| Attansic Technology               | 13        | 0.12%   |
| Lenovo                            | 12        | 0.11%   |
| Guillemot                         | 11        | 0.1%    |
| ASUSTek Computer                  | 11        | 0.1%    |
| Hewlett-Packard                   | 9         | 0.08%   |
| Google                            | 9         | 0.08%   |
| Microchip Technology              | 8         | 0.08%   |
| Edimax Technology                 | 8         | 0.08%   |
| OnePlus                           | 7         | 0.07%   |
| ICS Advent                        | 7         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2667      | 21.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 380       | 3.05%   |
| Intel Wi-Fi 6 AX200                                               | 311       | 2.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 254       | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 235       | 1.88%   |
| Intel Wireless 8265 / 8275                                        | 195       | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 182       | 1.46%   |
| Intel Wireless 7265                                               | 173       | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 161       | 1.29%   |
| Intel Wi-Fi 6 AX201                                               | 157       | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 155       | 1.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 147       | 1.18%   |
| Intel Wireless 8260                                               | 133       | 1.07%   |
| Intel Wireless 7260                                               | 130       | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 128       | 1.03%   |
| Intel I211 Gigabit Network Connection                             | 120       | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 118       | 0.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 117       | 0.94%   |
| Intel Ethernet Connection (2) I219-V                              | 112       | 0.9%    |
| Intel Ethernet Connection I217-LM                                 | 109       | 0.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 108       | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 106       | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 103       | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 99        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 94        | 0.75%   |
| Intel Wireless 3165                                               | 92        | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 89        | 0.71%   |
| Intel Wireless-AC 9260                                            | 83        | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 82        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 80        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 78        | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 75        | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 73        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 67        | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 66        | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 64        | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 61        | 0.49%   |
| Broadcom BCM43142 802.11b/g/n                                     | 59        | 0.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 57        | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 56        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2492      | 45.57%  |
| Qualcomm Atheros                      | 1018      | 18.61%  |
| Realtek Semiconductor                 | 907       | 16.58%  |
| Broadcom                              | 373       | 6.82%   |
| Ralink                                | 122       | 2.23%   |
| TP-Link                               | 82        | 1.5%    |
| Broadcom Limited                      | 71        | 1.3%    |
| Ralink Technology                     | 65        | 1.19%   |
| NetGear                               | 58        | 1.06%   |
| MediaTek                              | 52        | 0.95%   |
| D-Link                                | 22        | 0.4%    |
| Microsoft                             | 21        | 0.38%   |
| Sierra Wireless                       | 19        | 0.35%   |
| Dell                                  | 19        | 0.35%   |
| D-Link System                         | 17        | 0.31%   |
| Belkin Components                     | 17        | 0.31%   |
| Marvell Technology Group              | 16        | 0.29%   |
| Qualcomm Atheros Communications       | 14        | 0.26%   |
| Guillemot                             | 11        | 0.2%    |
| ASUSTek Computer                      | 11        | 0.2%    |
| Qualcomm                              | 8         | 0.15%   |
| Edimax Technology                     | 8         | 0.15%   |
| FIBOCOM                               | 6         | 0.11%   |
| Sagem                                 | 5         | 0.09%   |
| IMC Networks                          | 5         | 0.09%   |
| TRENDnet                              | 4         | 0.07%   |
| Hewlett-Packard                       | 4         | 0.07%   |
| Gemtek                                | 3         | 0.05%   |
| Accton Technology                     | 3         | 0.05%   |
| ZyDAS                                 | 2         | 0.04%   |
| Toshiba                               | 2         | 0.04%   |
| Linksys                               | 2         | 0.04%   |
| Fujitsu Siemens Computers             | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| Wilocity                              | 1         | 0.02%   |
| Texas Instruments                     | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| Apple                                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 311       | 5.65%   |
| Intel Wireless 8265 / 8275                                              | 195       | 3.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 182       | 3.31%   |
| Intel Wireless 7265                                                     | 173       | 3.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 161       | 2.93%   |
| Intel Wi-Fi 6 AX201                                                     | 157       | 2.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 155       | 2.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 147       | 2.67%   |
| Intel Wireless 8260                                                     | 133       | 2.42%   |
| Intel Wireless 7260                                                     | 130       | 2.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 128       | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 118       | 2.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 117       | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 106       | 1.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 103       | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 99        | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 94        | 1.71%   |
| Intel Wireless 3165                                                     | 92        | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 89        | 1.62%   |
| Intel Wireless-AC 9260                                                  | 83        | 1.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 82        | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 78        | 1.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 73        | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 59        | 1.07%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 57        | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 51        | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 51        | 0.93%   |
| Intel Wireless 3160                                                     | 49        | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 47        | 0.85%   |
| Intel WiFi Link 5100                                                    | 47        | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 46        | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 45        | 0.82%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 44        | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 42        | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 42        | 0.76%   |
| Intel Centrino Wireless-N 2230                                          | 42        | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 40        | 0.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 40        | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 39        | 0.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 39        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3481      | 52.05%  |
| Intel                             | 1733      | 25.91%  |
| Qualcomm Atheros                  | 463       | 6.92%   |
| Broadcom                          | 294       | 4.4%    |
| Marvell Technology Group          | 154       | 2.3%    |
| Nvidia                            | 133       | 1.99%   |
| Broadcom Limited                  | 56        | 0.84%   |
| ASIX Electronics                  | 46        | 0.69%   |
| Samsung Electronics               | 44        | 0.66%   |
| Xiaomi                            | 29        | 0.43%   |
| DisplayLink                       | 21        | 0.31%   |
| VIA Technologies                  | 20        | 0.3%    |
| JMicron Technology                | 19        | 0.28%   |
| Aquantia                          | 19        | 0.28%   |
| Huawei Technologies               | 18        | 0.27%   |
| D-Link System                     | 16        | 0.24%   |
| Silicon Integrated Systems [SiS]  | 13        | 0.19%   |
| Attansic Technology               | 13        | 0.19%   |
| MediaTek                          | 12        | 0.18%   |
| Lenovo                            | 12        | 0.18%   |
| Google                            | 9         | 0.13%   |
| Qualcomm                          | 8         | 0.12%   |
| OnePlus                           | 7         | 0.1%    |
| ICS Advent                        | 7         | 0.1%    |
| OPPO Electronics                  | 6         | 0.09%   |
| TP-Link                           | 5         | 0.07%   |
| Microchip Technology              | 5         | 0.07%   |
| NetGear                           | 4         | 0.06%   |
| Mellanox Technologies             | 4         | 0.06%   |
| Apple                             | 4         | 0.06%   |
| QLogic                            | 3         | 0.04%   |
| Motorola PCS                      | 3         | 0.04%   |
| 3Com                              | 3         | 0.04%   |
| Linksys                           | 2         | 0.03%   |
| HTC (High Tech Computer)          | 2         | 0.03%   |
| Cypress Semiconductor             | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.01%   |
| ULi Electronics                   | 1         | 0.01%   |
| Tehuti Networks                   | 1         | 0.01%   |
| Sundance Technology Inc / IC Plus | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2667      | 38.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 380       | 5.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 254       | 3.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 235       | 3.43%   |
| Intel I211 Gigabit Network Connection                             | 120       | 1.75%   |
| Intel Ethernet Connection (2) I219-V                              | 112       | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 109       | 1.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 108       | 1.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 80        | 1.17%   |
| Intel 82579V Gigabit Network Connection                           | 75        | 1.1%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 67        | 0.98%   |
| Intel Ethernet Connection (7) I219-V                              | 66        | 0.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 64        | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 61        | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                             | 56        | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 52        | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 51        | 0.74%   |
| Nvidia MCP61 Ethernet                                             | 51        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 49        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                             | 48        | 0.7%    |
| Intel Ethernet Connection (6) I219-V                              | 47        | 0.69%   |
| Intel Ethernet Connection (2) I218-V                              | 45        | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 42        | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 42        | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 40        | 0.58%   |
| Intel 82574L Gigabit Network Connection                           | 40        | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 40        | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 38        | 0.55%   |
| Intel I210 Gigabit Network Connection                             | 38        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                          | 37        | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 36        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 36        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 35        | 0.51%   |
| Intel Ethernet Controller I225-V                                  | 35        | 0.51%   |
| Intel Ethernet Connection I218-LM                                 | 34        | 0.5%    |
| Intel 82567LM Gigabit Network Connection                          | 33        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 30        | 0.44%   |
| Nvidia MCP79 Ethernet                                             | 29        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 29        | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 28        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6294      | 53.92%  |
| WiFi     | 5252      | 44.99%  |
| Modem    | 112       | 0.96%   |
| Unknown  | 15        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3903      | 52.39%  |
| Ethernet | 3546      | 47.6%   |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3940      | 54.9%   |
| 1     | 2932      | 40.85%  |
| 3     | 135       | 1.88%   |
| 0     | 131       | 1.83%   |
| 4     | 28        | 0.39%   |
| 5     | 5         | 0.07%   |
| 8     | 3         | 0.04%   |
| 6     | 3         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4961      | 67.46%  |
| Yes  | 2393      | 32.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1981      | 49.53%  |
| Realtek Semiconductor           | 317       | 7.93%   |
| Cambridge Silicon Radio         | 265       | 6.63%   |
| IMC Networks                    | 263       | 6.58%   |
| Qualcomm Atheros Communications | 246       | 6.15%   |
| Broadcom                        | 191       | 4.78%   |
| Apple                           | 125       | 3.13%   |
| Lite-On Technology              | 117       | 2.93%   |
| Foxconn / Hon Hai               | 96        | 2.4%    |
| ASUSTek Computer                | 80        | 2%      |
| Dell                            | 74        | 1.85%   |
| Realtek                         | 36        | 0.9%    |
| Hewlett-Packard                 | 35        | 0.88%   |
| Toshiba                         | 33        | 0.83%   |
| Ralink                          | 29        | 0.73%   |
| Ralink Technology               | 19        | 0.48%   |
| Belkin Components               | 13        | 0.33%   |
| Marvell Semiconductor           | 12        | 0.3%    |
| Foxconn International           | 12        | 0.3%    |
| Alps Electric                   | 12        | 0.3%    |
| MediaTek                        | 9         | 0.23%   |
| TP-Link                         | 8         | 0.2%    |
| Integrated System Solution      | 5         | 0.13%   |
| Chicony Electronics             | 5         | 0.13%   |
| HTC (High Tech Computer)        | 3         | 0.08%   |
| USI                             | 2         | 0.05%   |
| Conwise Technology              | 2         | 0.05%   |
| TRENDnet                        | 1         | 0.03%   |
| Syntek                          | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| Kensington                      | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| D-Link System                   | 1         | 0.03%   |
| D-Link                          | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| Com One                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 732       | 18.3%   |
| Intel AX201 Bluetooth                               | 369       | 9.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 311       | 7.77%   |
| Intel AX200 Bluetooth                               | 294       | 7.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 265       | 6.62%   |
| Realtek Bluetooth Radio                             | 200       | 5%      |
| IMC Networks Bluetooth Device                       | 109       | 2.72%   |
| Qualcomm Atheros  Bluetooth Device                  | 91        | 2.27%   |
| Realtek  Bluetooth 4.2 Adapter                      | 82        | 2.05%   |
| IMC Networks Bluetooth Radio                        | 80        | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 74        | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 65        | 1.62%   |
| Foxconn / Hon Hai Bluetooth Device                  | 48        | 1.2%    |
| Apple Bluetooth Host Controller                     | 47        | 1.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 45        | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 44        | 1.1%    |
| Intel Wireless-AC 3168 Bluetooth                    | 44        | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 42        | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 42        | 1.05%   |
| Realtek Bluetooth Radio                             | 36        | 0.9%    |
| Apple Bluetooth USB Host Controller                 | 36        | 0.9%    |
| Lite-On Bluetooth Device                            | 35        | 0.87%   |
| Intel AX210 Bluetooth                               | 35        | 0.87%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 31        | 0.77%   |
| Dell DW375 Bluetooth Module                         | 30        | 0.75%   |
| Ralink RT3290 Bluetooth                             | 29        | 0.72%   |
| Intel Bluetooth Device                              | 26        | 0.65%   |
| Broadcom BCM2045B (BDC-2.1)                         | 24        | 0.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 23        | 0.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 23        | 0.57%   |
| Lite-On Atheros AR3012 Bluetooth                    | 22        | 0.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 22        | 0.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 21        | 0.52%   |
| Apple Bluetooth HCI                                 | 20        | 0.5%    |
| Realtek RTL8723B Bluetooth                          | 19        | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 0.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 19        | 0.47%   |
| IMC Networks Wireless_Device                        | 16        | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.4%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 16        | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5237      | 52.31%  |
| Nvidia                           | 1881      | 18.79%  |
| AMD                              | 1872      | 18.7%   |
| C-Media Electronics              | 149       | 1.49%   |
| Logitech                         | 92        | 0.92%   |
| Creative Labs                    | 69        | 0.69%   |
| Realtek Semiconductor            | 57        | 0.57%   |
| GN Netcom                        | 56        | 0.56%   |
| Kingston Technology              | 38        | 0.38%   |
| JMTek                            | 37        | 0.37%   |
| Texas Instruments                | 35        | 0.35%   |
| Plantronics                      | 34        | 0.34%   |
| Corsair                          | 33        | 0.33%   |
| VIA Technologies                 | 31        | 0.31%   |
| Focusrite-Novation               | 24        | 0.24%   |
| SteelSeries ApS                  | 23        | 0.23%   |
| Sennheiser Communications        | 18        | 0.18%   |
| Silicon Integrated Systems [SiS] | 17        | 0.17%   |
| Razer USA                        | 16        | 0.16%   |
| Generalplus Technology           | 16        | 0.16%   |
| Lenovo                           | 15        | 0.15%   |
| Creative Technology              | 11        | 0.11%   |
| XMOS                             | 10        | 0.1%    |
| Hewlett-Packard                  | 10        | 0.1%    |
| M-Audio                          | 8         | 0.08%   |
| Sony                             | 7         | 0.07%   |
| ASUSTek Computer                 | 7         | 0.07%   |
| RODE Microphones                 | 6         | 0.06%   |
| Ensoniq                          | 6         | 0.06%   |
| Dell                             | 6         | 0.06%   |
| BEHRINGER International          | 6         | 0.06%   |
| Turtle Beach                     | 5         | 0.05%   |
| Tenx Technology                  | 5         | 0.05%   |
| Medeli Electronics               | 5         | 0.05%   |
| GYROCOM C&C                      | 5         | 0.05%   |
| DSEA A/S                         | 5         | 0.05%   |
| Blue Microphones                 | 5         | 0.05%   |
| Yamaha                           | 4         | 0.04%   |
| Unknown                          | 4         | 0.04%   |
| ROCCAT                           | 4         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 496       | 4.24%   |
| Intel Sunrise Point-LP HD Audio                                            | 463       | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 458       | 3.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 435       | 3.72%   |
| AMD Family 17h/19h HD Audio Controller                                     | 435       | 3.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 333       | 2.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 324       | 2.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 269       | 2.3%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 266       | 2.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 249       | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 241       | 2.06%   |
| AMD FCH Azalia Controller                                                  | 231       | 1.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 221       | 1.89%   |
| AMD Starship/Matisse HD Audio Controller                                   | 218       | 1.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 215       | 1.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 199       | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 180       | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                            | 179       | 1.53%   |
| Intel 8 Series HD Audio Controller                                         | 159       | 1.36%   |
| Intel Broadwell-U Audio Controller                                         | 158       | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                      | 156       | 1.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 156       | 1.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 154       | 1.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 150       | 1.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 142       | 1.21%   |
| Intel Comet Lake PCH-LP cAVS                                               | 140       | 1.2%    |
| Intel 200 Series PCH HD Audio                                              | 129       | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                   | 117       | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 115       | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                              | 114       | 0.98%   |
| Nvidia High Definition Audio Controller                                    | 113       | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 104       | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 100       | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                              | 96        | 0.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 93        | 0.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 88        | 0.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 87        | 0.74%   |
| Intel CM238 HD Audio Controller                                            | 85        | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 85        | 0.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 83        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1128      | 21.72%  |
| SK hynix            | 1044      | 20.1%   |
| Unknown             | 558       | 10.75%  |
| Kingston            | 512       | 9.86%   |
| Micron Technology   | 480       | 9.24%   |
| Corsair             | 368       | 7.09%   |
| Crucial             | 339       | 6.53%   |
| G.Skill             | 253       | 4.87%   |
| Elpida              | 84        | 1.62%   |
| Nanya Technology    | 72        | 1.39%   |
| Ramaxel Technology  | 61        | 1.17%   |
| A-DATA Technology   | 50        | 0.96%   |
| Unknown (ABCD)      | 43        | 0.83%   |
| Transcend           | 27        | 0.52%   |
| Unknown             | 16        | 0.31%   |
| PNY                 | 15        | 0.29%   |
| Team                | 14        | 0.27%   |
| Patriot             | 14        | 0.27%   |
| Unifosa             | 8         | 0.15%   |
| Qimonda             | 6         | 0.12%   |
| ASint Technology    | 6         | 0.12%   |
| Toshiba             | 5         | 0.1%    |
| Apacer              | 4         | 0.08%   |
| V-Color             | 3         | 0.06%   |
| Unknown (0x0C97)    | 3         | 0.06%   |
| Timetec             | 3         | 0.06%   |
| TEXTORM             | 3         | 0.06%   |
| Swissbit            | 3         | 0.06%   |
| Silicon Power       | 3         | 0.06%   |
| SHARETRONIC         | 3         | 0.06%   |
| OCZ                 | 3         | 0.06%   |
| Lexar               | 3         | 0.06%   |
| Innodisk            | 3         | 0.06%   |
| Hewlett-Packard     | 3         | 0.06%   |
| Unknown (07FB)      | 2         | 0.04%   |
| Ramos Technology    | 2         | 0.04%   |
| Kllisre             | 2         | 0.04%   |
| KLEVV               | 2         | 0.04%   |
| Goldkey             | 2         | 0.04%   |
| GeIL                | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 49        | 0.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 48        | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 45        | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 42        | 0.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 39        | 0.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 34        | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 33        | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 33        | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 32        | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 32        | 0.58%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 32        | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 32        | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 31        | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 31        | 0.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 30        | 0.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 29        | 0.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 28        | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 27        | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 26        | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 25        | 0.45%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s            | 25        | 0.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 24        | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 24        | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 24        | 0.43%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 19        | 0.34%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 17        | 0.31%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 16        | 0.29%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 16        | 0.29%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 16        | 0.29%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 16        | 0.29%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s                 | 16        | 0.29%   |
| Unknown                                                             | 16        | 0.29%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 15        | 0.27%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 15        | 0.27%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 15        | 0.27%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 15        | 0.27%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s             | 14        | 0.25%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 14        | 0.25%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 14        | 0.25%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s             | 14        | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1946      | 43.08%  |
| DDR3    | 1655      | 36.64%  |
| DDR2    | 274       | 6.07%   |
| SDRAM   | 151       | 3.34%   |
| LPDDR4  | 150       | 3.32%   |
| Unknown | 144       | 3.19%   |
| LPDDR3  | 107       | 2.37%   |
| DDR     | 56        | 1.24%   |
| LPDDR5  | 13        | 0.29%   |
| DDR5    | 13        | 0.29%   |
| DRAM    | 7         | 0.15%   |
| EEPROM  | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2467      | 55.1%   |
| DIMM         | 1714      | 38.28%  |
| Row Of Chips | 264       | 5.9%    |
| Chip         | 16        | 0.36%   |
| FB-DIMM      | 6         | 0.13%   |
| Unknown      | 6         | 0.13%   |
| RIMM         | 4         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1660      | 33.97%  |
| 4096  | 1557      | 31.87%  |
| 2048  | 724       | 14.82%  |
| 16384 | 587       | 12.01%  |
| 1024  | 231       | 4.73%   |
| 32768 | 82        | 1.68%   |
| 512   | 38        | 0.78%   |
| 65536 | 3         | 0.06%   |
| 256   | 3         | 0.06%   |
| 1     | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1064      | 21.9%   |
| 2667    | 686       | 14.12%  |
| 3200    | 612       | 12.6%   |
| 1333    | 360       | 7.41%   |
| 2400    | 346       | 7.12%   |
| 2133    | 253       | 5.21%   |
| 1334    | 150       | 3.09%   |
| 667     | 143       | 2.94%   |
| 800     | 140       | 2.88%   |
| 1867    | 97        | 2%      |
| 3600    | 96        | 1.98%   |
| Unknown | 93        | 1.91%   |
| 1066    | 75        | 1.54%   |
| 4267    | 71        | 1.46%   |
| 1067    | 62        | 1.28%   |
| 3266    | 57        | 1.17%   |
| 2933    | 38        | 0.78%   |
| 3000    | 37        | 0.76%   |
| 2048    | 35        | 0.72%   |
| 2666    | 32        | 0.66%   |
| 1866    | 30        | 0.62%   |
| 1800    | 29        | 0.6%    |
| 533     | 28        | 0.58%   |
| 3466    | 27        | 0.56%   |
| 4199    | 25        | 0.51%   |
| 3400    | 21        | 0.43%   |
| 400     | 20        | 0.41%   |
| 4800    | 19        | 0.39%   |
| 975     | 15        | 0.31%   |
| 6400    | 14        | 0.29%   |
| 2800    | 14        | 0.29%   |
| 333     | 13        | 0.27%   |
| 4266    | 12        | 0.25%   |
| 2465    | 11        | 0.23%   |
| 3733    | 10        | 0.21%   |
| 1639    | 10        | 0.21%   |
| 3800    | 9         | 0.19%   |
| 8400    | 8         | 0.16%   |
| 3866    | 8         | 0.16%   |
| 2000    | 8         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 99        | 46.05%  |
| Canon               | 34        | 15.81%  |
| Brother Industries  | 29        | 13.49%  |
| Samsung Electronics | 24        | 11.16%  |
| Seiko Epson         | 17        | 7.91%   |
| Prolific Technology | 3         | 1.4%    |
| STMicroelectronics  | 2         | 0.93%   |
| Ricoh               | 2         | 0.93%   |
| QinHeng Electronics | 2         | 0.93%   |
| Xiaomi              | 1         | 0.47%   |
| Xerox               | 1         | 0.47%   |
| Kyocera             | 1         | 0.47%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 3630 series                                    | 9         | 4.17%   |
| HP DeskJet 2700 series                                    | 9         | 4.17%   |
| HP ENVY 4520 series                                       | 8         | 3.7%    |
| Samsung M2070 Series                                      | 6         | 2.78%   |
| Canon PIXMA MG3600 Series                                 | 6         | 2.78%   |
| HP ENVY Photo 6200 series                                 | 5         | 2.31%   |
| HP DeskJet Plus 4100 series                               | 4         | 1.85%   |
| HP DeskJet 3700 series                                    | 4         | 1.85%   |
| Brother HL-2030 Laser Printer                             | 4         | 1.85%   |
| Seiko Epson XP-243 245 247 Series                         | 3         | 1.39%   |
| Samsung M2020 Series                                      | 3         | 1.39%   |
| Prolific PL2305 Parallel Port                             | 3         | 1.39%   |
| HP OfficeJet 3830 series                                  | 3         | 1.39%   |
| HP ENVY 5000 series                                       | 3         | 1.39%   |
| HP Deskjet 3050A                                          | 3         | 1.39%   |
| HP DeskJet 2620 All-in-One Printer                        | 3         | 1.39%   |
| Brother Printer                                           | 3         | 1.39%   |
| Brother MFC-L2710DW series                                | 3         | 1.39%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 0.93%   |
| Seiko Epson XP-255 257 Series                             | 2         | 0.93%   |
| Seiko Epson XP-2100 Series                                | 2         | 0.93%   |
| Seiko Epson WF-2830 Series                                | 2         | 0.93%   |
| Samsung SCX-3400 Series                                   | 2         | 0.93%   |
| Samsung SCX-3200 Series                                   | 2         | 0.93%   |
| Samsung CLX-3180 Series                                   | 2         | 0.93%   |
| Samsung CLX-3170 Series                                   | 2         | 0.93%   |
| QinHeng CH340S                                            | 2         | 0.93%   |
| HP OfficeJet Pro 69                                       | 2         | 0.93%   |
| HP ENVY 5540 series                                       | 2         | 0.93%   |
| HP ENVY 4500 series                                       | 2         | 0.93%   |
| HP DeskJet F4200 series                                   | 2         | 0.93%   |
| HP DeskJet 5550                                           | 2         | 0.93%   |
| HP Deskjet 3070 B611 series                               | 2         | 0.93%   |
| HP Deskjet 1510                                           | 2         | 0.93%   |
| Canon PIXMA MP270 All-In-One Printer                      | 2         | 0.93%   |
| Canon PIXMA MG3500 Series                                 | 2         | 0.93%   |
| Canon PIXMA MG2500 Series                                 | 2         | 0.93%   |
| Canon iP7200 series                                       | 2         | 0.93%   |
| Brother MFC-J5335DW                                       | 2         | 0.93%   |
| Brother HL-L2350DW series                                 | 2         | 0.93%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 47        | 65.28%  |
| Seiko Epson     | 15        | 20.83%  |
| Hewlett-Packard | 8         | 11.11%  |
| AGFA-Gevaert NV | 2         | 2.78%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30                                 | 9         | 12.5%   |
| Canon CanoScan N670U/N676U/LiDE 20                            | 8         | 11.11%  |
| Canon CanoScan LiDE 110                                       | 7         | 9.72%   |
| Canon CanoScan LIDE 25                                        | 6         | 8.33%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 4         | 5.56%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                        | 3         | 4.17%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 2         | 2.78%   |
| HP ScanJet 3570c                                              | 2         | 2.78%   |
| Canon CanoScan N650U/N656U                                    | 2         | 2.78%   |
| Canon CanoScan LiDE 60                                        | 2         | 2.78%   |
| Canon CanoScan LiDE 220                                       | 2         | 2.78%   |
| Canon CanoScan LiDE 210                                       | 2         | 2.78%   |
| Canon CanoScan LiDE 200                                       | 2         | 2.78%   |
| Seiko Epson Scanner                                           | 1         | 1.39%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                   | 1         | 1.39%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 1.39%   |
| Seiko Epson GT-F600 [Perfection 4180]                         | 1         | 1.39%   |
| Seiko Epson GT-9800F [Perfection 3200]                        | 1         | 1.39%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 1.39%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 1.39%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]   | 1         | 1.39%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 1.39%   |
| HP ScanJet G4010                                              | 1         | 1.39%   |
| HP ScanJet 5200c                                              | 1         | 1.39%   |
| HP ScanJet 4570c                                              | 1         | 1.39%   |
| HP ScanJet 3500c                                              | 1         | 1.39%   |
| HP ScanJet 2300c                                              | 1         | 1.39%   |
| HP PSC 1200                                                   | 1         | 1.39%   |
| Canon CanoScan LiDE 120                                       | 1         | 1.39%   |
| Canon CanoScan 9000F Mark II                                  | 1         | 1.39%   |
| Canon CanoScan 4400F                                          | 1         | 1.39%   |
| Canon CanoScan 4200F                                          | 1         | 1.39%   |
| AGFA-Gevaert NV SnapScan e20                                  | 1         | 1.39%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 1         | 1.39%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 903       | 21.48%  |
| IMC Networks                           | 437       | 10.39%  |
| Microdia                               | 392       | 9.32%   |
| Realtek Semiconductor                  | 352       | 8.37%   |
| Acer                                   | 319       | 7.59%   |
| Logitech                               | 279       | 6.64%   |
| Sunplus Innovation Technology          | 239       | 5.69%   |
| Suyin                                  | 156       | 3.71%   |
| Cheng Uei Precision Industry (Foxlink) | 152       | 3.62%   |
| Quanta                                 | 123       | 2.93%   |
| Apple                                  | 115       | 2.74%   |
| Lite-On Technology                     | 106       | 2.52%   |
| Syntek                                 | 79        | 1.88%   |
| Alcor Micro                            | 52        | 1.24%   |
| Samsung Electronics                    | 47        | 1.12%   |
| Microsoft                              | 45        | 1.07%   |
| Silicon Motion                         | 42        | 1%      |
| Ricoh                                  | 42        | 1%      |
| Luxvisions Innotech Limited            | 34        | 0.81%   |
| Lenovo                                 | 20        | 0.48%   |
| Guillemot                              | 18        | 0.43%   |
| Z-Star Microelectronics                | 17        | 0.4%    |
| Primax Electronics                     | 17        | 0.4%    |
| GEMBIRD                                | 14        | 0.33%   |
| Sonix Technology                       | 13        | 0.31%   |
| Importek                               | 13        | 0.31%   |
| Generalplus Technology                 | 12        | 0.29%   |
| DigiTech                               | 12        | 0.29%   |
| ARC International                      | 12        | 0.29%   |
| Creative Technology                    | 11        | 0.26%   |
| ALi                                    | 10        | 0.24%   |
| Hewlett-Packard                        | 9         | 0.21%   |
| 2M UVC CAMERA                          | 7         | 0.17%   |
| OmniVision Technologies                | 6         | 0.14%   |
| KYE Systems (Mouse Systems)            | 6         | 0.14%   |
| Cubeternet                             | 6         | 0.14%   |
| Jieli Technology                       | 4         | 0.1%    |
| Intel                                  | 4         | 0.1%    |
| AVerMedia Technologies                 | 4         | 0.1%    |
| Arkmicro Technologies                  | 4         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 198       | 4.69%   |
| Realtek Integrated_Webcam_HD             | 154       | 3.65%   |
| Chicony Integrated Camera                | 135       | 3.2%    |
| IMC Networks USB2.0 HD UVC WebCam        | 99        | 2.34%   |
| Chicony HD WebCam                        | 90        | 2.13%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 79        | 1.87%   |
| IMC Networks Integrated Camera           | 79        | 1.87%   |
| Acer Integrated Camera                   | 75        | 1.78%   |
| Logitech Webcam C270                     | 60        | 1.42%   |
| Sunplus Integrated_Webcam_HD             | 56        | 1.33%   |
| Samsung Galaxy series, misc. (MTP mode)  | 47        | 1.11%   |
| Acer HD Webcam                           | 46        | 1.09%   |
| Chicony USB2.0 VGA UVC WebCam            | 41        | 0.97%   |
| Chicony USB2.0 Camera                    | 41        | 0.97%   |
| Apple Built-in iSight                    | 40        | 0.95%   |
| Chicony USB2.0 HD UVC WebCam             | 39        | 0.92%   |
| Realtek USB Camera                       | 37        | 0.88%   |
| Sunplus ASUS Webcam                      | 35        | 0.83%   |
| Chicony TOSHIBA Web Camera - HD          | 35        | 0.83%   |
| Apple iPhone 5/5C/5S/6/SE                | 35        | 0.83%   |
| Acer BisonCam,NB Pro                     | 35        | 0.83%   |
| Syntek Integrated Camera                 | 34        | 0.8%    |
| Microdia Integrated Webcam               | 34        | 0.8%    |
| Chicony HP HD Camera                     | 34        | 0.8%    |
| Logitech HD Pro Webcam C920              | 33        | 0.78%   |
| Lite-On Integrated Camera                | 32        | 0.76%   |
| Chicony HP HD Webcam                     | 32        | 0.76%   |
| Chicony USB 2.0 Camera                   | 31        | 0.73%   |
| Chicony HP Truevision HD                 | 30        | 0.71%   |
| Realtek USB2.0 HD UVC WebCam             | 29        | 0.69%   |
| Acer BisonCam, NB Pro                    | 29        | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 25        | 0.59%   |
| Logitech HD Webcam C525                  | 25        | 0.59%   |
| Acer Lenovo EasyCamera                   | 25        | 0.59%   |
| IMC Networks UVC VGA Webcam              | 24        | 0.57%   |
| Chicony VGA Webcam                       | 23        | 0.54%   |
| Chicony HP Truevision HD camera          | 23        | 0.54%   |
| Sunplus HD WebCam                        | 22        | 0.52%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 22        | 0.52%   |
| Quanta HP HD Camera                      | 21        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 244       | 35.16%  |
| Synaptics                  | 159       | 22.91%  |
| Shenzhen Goodix Technology | 130       | 18.73%  |
| AuthenTec                  | 52        | 7.49%   |
| Elan Microelectronics      | 40        | 5.76%   |
| LighTuning Technology      | 34        | 4.9%    |
| Upek                       | 26        | 3.75%   |
| STMicroelectronics         | 8         | 1.15%   |
| Focal-systems.Corp         | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 67        | 9.65%   |
| Shenzhen Goodix  Fingerprint Device                                        | 62        | 8.93%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 56        | 8.07%   |
| Unknown                                                                    | 47        | 6.77%   |
| Shenzhen Goodix FingerPrint                                                | 35        | 5.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 33        | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 31        | 4.47%   |
| Elan ELAN:Fingerprint                                                      | 30        | 4.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 27        | 3.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 3.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 3.03%   |
| Validity Sensors VFS491                                                    | 20        | 2.88%   |
| AuthenTec AES2810                                                          | 20        | 2.88%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 2.31%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 2.16%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 2.16%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 2.16%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.73%   |
| AuthenTec AES1600                                                          | 12        | 1.73%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 1.59%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 1.59%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 1.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.3%    |
| AuthenTec Fingerprint Sensor                                               | 9         | 1.3%    |
| Synaptics  WBDI                                                            | 8         | 1.15%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 1.15%   |
| Elan ELAN:ARM-M4                                                           | 8         | 1.15%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 1.01%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 1.01%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.72%   |
| Synaptics WBDI Device                                                      | 5         | 0.72%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.58%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.58%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.43%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.43%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.43%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.29%   |
| LighTuning EgisTec_ES603                                                   | 2         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 191       | 53.06%  |
| Alcor Micro               | 72        | 20%     |
| O2 Micro                  | 30        | 8.33%   |
| Upek                      | 15        | 4.17%   |
| Lenovo                    | 12        | 3.33%   |
| Hewlett-Packard           | 9         | 2.5%    |
| Gemalto (was Gemplus)     | 9         | 2.5%    |
| Aladdin Knowledge Systems | 4         | 1.11%   |
| Yubico.com                | 3         | 0.83%   |
| Clay Logic                | 3         | 0.83%   |
| SCM Microsystems          | 2         | 0.56%   |
| Feitian Technologies      | 2         | 0.56%   |
| Chicony Electronics       | 2         | 0.56%   |
| ST-Ericsson               | 1         | 0.28%   |
| SpringCard                | 1         | 0.28%   |
| Realtek Semiconductor     | 1         | 0.28%   |
| OmniKey                   | 1         | 0.28%   |
| Cherry                    | 1         | 0.28%   |
| Advanced Card Systems     | 1         | 0.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 71        | 19.72%  |
| Broadcom BCM5880 Secure Applications Processor                               | 68        | 18.89%  |
| Broadcom 58200                                                               | 55        | 15.28%  |
| Broadcom 5880                                                                | 40        | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 27        | 7.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 27        | 7.5%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 15        | 4.17%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 3.33%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 9         | 2.5%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 1.67%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 1.11%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.83%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.83%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.56%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.56%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.56%   |
| ST-Ericsson Chipcard Reader                                                  | 1         | 0.28%   |
| SpringCard Two                                                               | 1         | 0.28%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.28%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.28%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.28%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.28%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.28%   |
| Feitian Technologies U2F CCID KB                                             | 1         | 0.28%   |
| Feitian Technologies FT SCR310                                               | 1         | 0.28%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.28%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.28%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.28%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.28%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5246      | 71.65%  |
| 1     | 1655      | 22.6%   |
| 2     | 327       | 4.47%   |
| 3     | 65        | 0.89%   |
| 4     | 15        | 0.2%    |
| 5     | 6         | 0.08%   |
| 7     | 3         | 0.04%   |
| 6     | 3         | 0.04%   |
| 9     | 1         | 0.01%   |
| 8     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 684       | 27.33%  |
| Graphics card            | 574       | 22.93%  |
| Chipcard                 | 326       | 13.02%  |
| Net/wireless             | 272       | 10.87%  |
| Multimedia controller    | 123       | 4.91%   |
| Communication controller | 106       | 4.23%   |
| Camera                   | 80        | 3.2%    |
| Bluetooth                | 69        | 2.76%   |
| Unassigned class         | 59        | 2.36%   |
| Storage                  | 46        | 1.84%   |
| Sound                    | 42        | 1.68%   |
| Card reader              | 34        | 1.36%   |
| Net/ethernet             | 26        | 1.04%   |
| Modem                    | 19        | 0.76%   |
| Network                  | 13        | 0.52%   |
| Storage/raid             | 7         | 0.28%   |
| Firewire controller      | 6         | 0.24%   |
| Dvb card                 | 4         | 0.16%   |
| Storage/ide              | 3         | 0.12%   |
| Flash memory             | 3         | 0.12%   |
| Wireless                 | 2         | 0.08%   |
| Unclassified device      | 2         | 0.08%   |
| Tv card                  | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |

