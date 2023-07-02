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

Total: 13300

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire E5-772               | Notebook    | [b33f11c7c9](https://linux-hardware.org/?probe=b33f11c7c9) | Jul 01, 2023 |
| ASUSTek       | K52Dr                       | Notebook    | [f97425ba5f](https://linux-hardware.org/?probe=f97425ba5f) | Jun 30, 2023 |
| Sony          | VGN-NS38E_S                 | Notebook    | [270e8b9fb7](https://linux-hardware.org/?probe=270e8b9fb7) | Jun 30, 2023 |
| Sony          | VGN-NS38E_S                 | Notebook    | [ca33cfbc67](https://linux-hardware.org/?probe=ca33cfbc67) | Jun 30, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | Desktop     | [0d3ecc7c44](https://linux-hardware.org/?probe=0d3ecc7c44) | Jun 30, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [08d14942e4](https://linux-hardware.org/?probe=08d14942e4) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Notebook    | [6a4f9f32d6](https://linux-hardware.org/?probe=6a4f9f32d6) | Jun 30, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [6c6741deb9](https://linux-hardware.org/?probe=6c6741deb9) | Jun 30, 2023 |
| ASUSTek       | P8H67-V                     | Desktop     | [afe93b44f3](https://linux-hardware.org/?probe=afe93b44f3) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [954ac9a8e4](https://linux-hardware.org/?probe=954ac9a8e4) | Jun 30, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [99e1623ea0](https://linux-hardware.org/?probe=99e1623ea0) | Jun 29, 2023 |
| HP            | ProBook 4530s               | Notebook    | [d1c3bf37ff](https://linux-hardware.org/?probe=d1c3bf37ff) | Jun 29, 2023 |
| MSI           | GT70                        | Notebook    | [7471aab8f7](https://linux-hardware.org/?probe=7471aab8f7) | Jun 29, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6c7621fe04](https://linux-hardware.org/?probe=6c7621fe04) | Jun 29, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [1f2cf12e26](https://linux-hardware.org/?probe=1f2cf12e26) | Jun 29, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [171e61b165](https://linux-hardware.org/?probe=171e61b165) | Jun 29, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [49f05e412e](https://linux-hardware.org/?probe=49f05e412e) | Jun 28, 2023 |
| HP            | Pavilion 17                 | Notebook    | [01c3ae7698](https://linux-hardware.org/?probe=01c3ae7698) | Jun 28, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [5c049dc792](https://linux-hardware.org/?probe=5c049dc792) | Jun 28, 2023 |
| Dell          | Precision 3560              | Notebook    | [d7dfa3c472](https://linux-hardware.org/?probe=d7dfa3c472) | Jun 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 3 ... | Convertible | [d6d67cffd3](https://linux-hardware.org/?probe=d6d67cffd3) | Jun 28, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [1025bf4027](https://linux-hardware.org/?probe=1025bf4027) | Jun 28, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [b8453a6830](https://linux-hardware.org/?probe=b8453a6830) | Jun 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0081fa215e](https://linux-hardware.org/?probe=0081fa215e) | Jun 28, 2023 |
| ASUSTek       | M4N78                       | Desktop     | [03e5d24ba1](https://linux-hardware.org/?probe=03e5d24ba1) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [cb40f5d060](https://linux-hardware.org/?probe=cb40f5d060) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [13ac46e7fb](https://linux-hardware.org/?probe=13ac46e7fb) | Jun 28, 2023 |
| ASUSTek       | N75SF                       | Notebook    | [eda2a0d726](https://linux-hardware.org/?probe=eda2a0d726) | Jun 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [90a10ed8ed](https://linux-hardware.org/?probe=90a10ed8ed) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| Dell          | Latitude E6530              | Notebook    | [f015f73aef](https://linux-hardware.org/?probe=f015f73aef) | Jun 27, 2023 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [dae5fc72df](https://linux-hardware.org/?probe=dae5fc72df) | Jun 27, 2023 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [c91c09307d](https://linux-hardware.org/?probe=c91c09307d) | Jun 27, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [177c923e5a](https://linux-hardware.org/?probe=177c923e5a) | Jun 27, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [7478cd5b81](https://linux-hardware.org/?probe=7478cd5b81) | Jun 27, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [8b04801d40](https://linux-hardware.org/?probe=8b04801d40) | Jun 27, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [465cc8968f](https://linux-hardware.org/?probe=465cc8968f) | Jun 27, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [3928ad0893](https://linux-hardware.org/?probe=3928ad0893) | Jun 27, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [f296b651e4](https://linux-hardware.org/?probe=f296b651e4) | Jun 27, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [309cb87000](https://linux-hardware.org/?probe=309cb87000) | Jun 26, 2023 |
| LG Electro... | 17Z90R-G.AD79F              | Notebook    | [0d641b84fe](https://linux-hardware.org/?probe=0d641b84fe) | Jun 26, 2023 |
| Neousys Te... | NVS-9000 Rev. ES2           | Server      | [1680be6585](https://linux-hardware.org/?probe=1680be6585) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [b8a3042b9d](https://linux-hardware.org/?probe=b8a3042b9d) | Jun 26, 2023 |
| Timi          | TM1613                      | Notebook    | [e6b5bc59c2](https://linux-hardware.org/?probe=e6b5bc59c2) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M91p 7033A1G    | Desktop     | [a3ca410b6a](https://linux-hardware.org/?probe=a3ca410b6a) | Jun 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3505659de8](https://linux-hardware.org/?probe=3505659de8) | Jun 25, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [96184db86b](https://linux-hardware.org/?probe=96184db86b) | Jun 25, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | Notebook    | [ba30e1369c](https://linux-hardware.org/?probe=ba30e1369c) | Jun 25, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [eb8a9d675b](https://linux-hardware.org/?probe=eb8a9d675b) | Jun 25, 2023 |
| Toshiba       | Satellite Pro L500          | Notebook    | [44e57dc97b](https://linux-hardware.org/?probe=44e57dc97b) | Jun 25, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [d02e6a9fa6](https://linux-hardware.org/?probe=d02e6a9fa6) | Jun 25, 2023 |
| HP            | 8055                        | Desktop     | [7fac5a1354](https://linux-hardware.org/?probe=7fac5a1354) | Jun 24, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [b7bbc8246f](https://linux-hardware.org/?probe=b7bbc8246f) | Jun 24, 2023 |
| Dell          | Latitude E6410              | Notebook    | [7d1989fd84](https://linux-hardware.org/?probe=7d1989fd84) | Jun 24, 2023 |
| Dell          | Precision 5510              | Notebook    | [38d61a4475](https://linux-hardware.org/?probe=38d61a4475) | Jun 24, 2023 |
| ASRock        | B85 Pro4                    | Desktop     | [f42da342bc](https://linux-hardware.org/?probe=f42da342bc) | Jun 24, 2023 |
| Intel         | DH55HC AAE70933-503         | Desktop     | [8dab0b7f0d](https://linux-hardware.org/?probe=8dab0b7f0d) | Jun 24, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [96f79c634a](https://linux-hardware.org/?probe=96f79c634a) | Jun 24, 2023 |
| HP            | 1496                        | Desktop     | [9d4549de6c](https://linux-hardware.org/?probe=9d4549de6c) | Jun 24, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9151f79ebe](https://linux-hardware.org/?probe=9151f79ebe) | Jun 24, 2023 |
| HP            | Pavilion dv7                | Notebook    | [ab7310809d](https://linux-hardware.org/?probe=ab7310809d) | Jun 24, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [6ed0182e96](https://linux-hardware.org/?probe=6ed0182e96) | Jun 24, 2023 |
| Alienware     | 17                          | Notebook    | [63b34ffc64](https://linux-hardware.org/?probe=63b34ffc64) | Jun 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4a11a4190a](https://linux-hardware.org/?probe=4a11a4190a) | Jun 23, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [19350653f7](https://linux-hardware.org/?probe=19350653f7) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ac715f3941](https://linux-hardware.org/?probe=ac715f3941) | Jun 23, 2023 |
| eMachines     | eMG520                      | Notebook    | [2a33e0b985](https://linux-hardware.org/?probe=2a33e0b985) | Jun 23, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [649bcffd26](https://linux-hardware.org/?probe=649bcffd26) | Jun 23, 2023 |
| Packard Be... | EN Butterfly m              | Notebook    | [70bae75df2](https://linux-hardware.org/?probe=70bae75df2) | Jun 23, 2023 |
| Dell          | Precision 3581              | Notebook    | [2e960d89db](https://linux-hardware.org/?probe=2e960d89db) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| Dell          | XPS 15 9575                 | Convertible | [150b8d631e](https://linux-hardware.org/?probe=150b8d631e) | Jun 23, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [622462c1d1](https://linux-hardware.org/?probe=622462c1d1) | Jun 23, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [117e92a397](https://linux-hardware.org/?probe=117e92a397) | Jun 23, 2023 |
| AZW           | SER                         | Mini pc     | [4375fcb36a](https://linux-hardware.org/?probe=4375fcb36a) | Jun 23, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [83eb8cda4a](https://linux-hardware.org/?probe=83eb8cda4a) | Jun 23, 2023 |
| Lenovo        | ThinkPad E460 20ETCTO1WW    | Notebook    | [762add0eb1](https://linux-hardware.org/?probe=762add0eb1) | Jun 22, 2023 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [b36de255fe](https://linux-hardware.org/?probe=b36de255fe) | Jun 22, 2023 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [f8f4049a95](https://linux-hardware.org/?probe=f8f4049a95) | Jun 22, 2023 |
| Acer          | WG43M                       | Desktop     | [b3eae58854](https://linux-hardware.org/?probe=b3eae58854) | Jun 22, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [fc54744449](https://linux-hardware.org/?probe=fc54744449) | Jun 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [0a065bce17](https://linux-hardware.org/?probe=0a065bce17) | Jun 22, 2023 |
| AZW           | SER                         | Mini pc     | [9ef166eb46](https://linux-hardware.org/?probe=9ef166eb46) | Jun 22, 2023 |
| Dell          | 0NKW6Y A01                  | Desktop     | [def5a35ba4](https://linux-hardware.org/?probe=def5a35ba4) | Jun 21, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [596a01e7a5](https://linux-hardware.org/?probe=596a01e7a5) | Jun 21, 2023 |
| Lenovo        | ThinkPad L440 20ASS19B03    | Notebook    | [3acd887212](https://linux-hardware.org/?probe=3acd887212) | Jun 21, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [e6b0f20906](https://linux-hardware.org/?probe=e6b0f20906) | Jun 21, 2023 |
| Dell          | Latitude 5430               | Notebook    | [458a2111da](https://linux-hardware.org/?probe=458a2111da) | Jun 21, 2023 |
| ASUSTek       | K73SD                       | Notebook    | [2dcb7bb5c9](https://linux-hardware.org/?probe=2dcb7bb5c9) | Jun 21, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [004f9be7a7](https://linux-hardware.org/?probe=004f9be7a7) | Jun 21, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [386c32d302](https://linux-hardware.org/?probe=386c32d302) | Jun 21, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [ff224b2f9d](https://linux-hardware.org/?probe=ff224b2f9d) | Jun 21, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [acbd33c5c8](https://linux-hardware.org/?probe=acbd33c5c8) | Jun 21, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [a7e4d1a6bd](https://linux-hardware.org/?probe=a7e4d1a6bd) | Jun 21, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f1acdd3081](https://linux-hardware.org/?probe=f1acdd3081) | Jun 20, 2023 |
| Dell          | Latitude E5520              | Notebook    | [4c041a09f6](https://linux-hardware.org/?probe=4c041a09f6) | Jun 20, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ec5318fcd1](https://linux-hardware.org/?probe=ec5318fcd1) | Jun 20, 2023 |
| Dell          | 0VHRW1 A03                  | Desktop     | [f077d9dc8f](https://linux-hardware.org/?probe=f077d9dc8f) | Jun 20, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [f84ddd7cac](https://linux-hardware.org/?probe=f84ddd7cac) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5a51d4431b](https://linux-hardware.org/?probe=5a51d4431b) | Jun 20, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [68d3aeda15](https://linux-hardware.org/?probe=68d3aeda15) | Jun 20, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [d9d8f74eca](https://linux-hardware.org/?probe=d9d8f74eca) | Jun 19, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Lenovo        | ThinkPad L440 20ASS19B03    | Notebook    | [a881db7c2b](https://linux-hardware.org/?probe=a881db7c2b) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [27bfb2de7d](https://linux-hardware.org/?probe=27bfb2de7d) | Jun 19, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [257c60290f](https://linux-hardware.org/?probe=257c60290f) | Jun 19, 2023 |
| HP            | 1497                        | Desktop     | [a922d11f63](https://linux-hardware.org/?probe=a922d11f63) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Otazak        | iPC45                       | Convertible | [5448e32422](https://linux-hardware.org/?probe=5448e32422) | Jun 19, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [fcec0ed2a4](https://linux-hardware.org/?probe=fcec0ed2a4) | Jun 19, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [ade4d4c90c](https://linux-hardware.org/?probe=ade4d4c90c) | Jun 19, 2023 |
| HP            | Pavilion 17                 | Notebook    | [46ae665800](https://linux-hardware.org/?probe=46ae665800) | Jun 18, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [733af664a4](https://linux-hardware.org/?probe=733af664a4) | Jun 18, 2023 |
| Dell          | Latitude 5430               | Notebook    | [7c591ed7d8](https://linux-hardware.org/?probe=7c591ed7d8) | Jun 18, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [fcbe9b509b](https://linux-hardware.org/?probe=fcbe9b509b) | Jun 18, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4d509da42f](https://linux-hardware.org/?probe=4d509da42f) | Jun 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [651988e989](https://linux-hardware.org/?probe=651988e989) | Jun 18, 2023 |
| Xunlong       | Orange Pi Lite              | Soc         | [f7e41df8d6](https://linux-hardware.org/?probe=f7e41df8d6) | Jun 18, 2023 |
| HP            | Pavilion 17                 | Notebook    | [f0e1e5aae8](https://linux-hardware.org/?probe=f0e1e5aae8) | Jun 18, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [02de076b1c](https://linux-hardware.org/?probe=02de076b1c) | Jun 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [37b1f672d0](https://linux-hardware.org/?probe=37b1f672d0) | Jun 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | Notebook    | [591e97398c](https://linux-hardware.org/?probe=591e97398c) | Jun 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [8dc64586cc](https://linux-hardware.org/?probe=8dc64586cc) | Jun 18, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [6fb60cf84a](https://linux-hardware.org/?probe=6fb60cf84a) | Jun 18, 2023 |
| Toshiba       | Satellite Pro L500          | Notebook    | [14765b8284](https://linux-hardware.org/?probe=14765b8284) | Jun 18, 2023 |
| HP            | 2820h                       | Desktop     | [b6d16a685f](https://linux-hardware.org/?probe=b6d16a685f) | Jun 17, 2023 |
| Lenovo        | ThinkPad P50 20EQS4840B     | Notebook    | [a60f1ae93e](https://linux-hardware.org/?probe=a60f1ae93e) | Jun 17, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f008a78339](https://linux-hardware.org/?probe=f008a78339) | Jun 17, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [7a3f7dcd73](https://linux-hardware.org/?probe=7a3f7dcd73) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Gigabyte      | AORUS 15P XC                | Notebook    | [bc59248a6c](https://linux-hardware.org/?probe=bc59248a6c) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| Dell          | 0P301D A00                  | Desktop     | [91bec0952f](https://linux-hardware.org/?probe=91bec0952f) | Jun 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3c45e54fd2](https://linux-hardware.org/?probe=3c45e54fd2) | Jun 17, 2023 |
| MSI           | GT70                        | Notebook    | [3ccbd6cfb4](https://linux-hardware.org/?probe=3ccbd6cfb4) | Jun 17, 2023 |
| Intel         | DQ77KB AAG81483-500         | Desktop     | [f06eae8b41](https://linux-hardware.org/?probe=f06eae8b41) | Jun 17, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [bbb32d23be](https://linux-hardware.org/?probe=bbb32d23be) | Jun 17, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [ec95321dfb](https://linux-hardware.org/?probe=ec95321dfb) | Jun 17, 2023 |
| Dell          | Precision M2800             | Notebook    | [e9f259595a](https://linux-hardware.org/?probe=e9f259595a) | Jun 17, 2023 |
| ASUSTek       | P5K Premium                 | Desktop     | [dddb2b8bdf](https://linux-hardware.org/?probe=dddb2b8bdf) | Jun 17, 2023 |
| Toshiba       | Satellite C870-199          | Notebook    | [cc18b4ff53](https://linux-hardware.org/?probe=cc18b4ff53) | Jun 16, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1f5163e415](https://linux-hardware.org/?probe=1f5163e415) | Jun 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [cfea5ce0fe](https://linux-hardware.org/?probe=cfea5ce0fe) | Jun 16, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [63cf4a0f41](https://linux-hardware.org/?probe=63cf4a0f41) | Jun 16, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [4c6361a099](https://linux-hardware.org/?probe=4c6361a099) | Jun 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [ec46ef5f36](https://linux-hardware.org/?probe=ec46ef5f36) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [f94cf27a96](https://linux-hardware.org/?probe=f94cf27a96) | Jun 15, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [56c650c8b1](https://linux-hardware.org/?probe=56c650c8b1) | Jun 15, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [d517ea1435](https://linux-hardware.org/?probe=d517ea1435) | Jun 15, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [41d5c8b913](https://linux-hardware.org/?probe=41d5c8b913) | Jun 15, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [448a3cf6b1](https://linux-hardware.org/?probe=448a3cf6b1) | Jun 15, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [67b278ea0e](https://linux-hardware.org/?probe=67b278ea0e) | Jun 15, 2023 |
| Dell          | Precision 5570              | Notebook    | [76bbf6a26f](https://linux-hardware.org/?probe=76bbf6a26f) | Jun 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [1858e12df4](https://linux-hardware.org/?probe=1858e12df4) | Jun 15, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [c488929cdc](https://linux-hardware.org/?probe=c488929cdc) | Jun 15, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a3990bdddb](https://linux-hardware.org/?probe=a3990bdddb) | Jun 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [23a8eeaa23](https://linux-hardware.org/?probe=23a8eeaa23) | Jun 15, 2023 |
| Lenovo        | ThinkPad L420 78545EG       | Notebook    | [bb42ee1009](https://linux-hardware.org/?probe=bb42ee1009) | Jun 14, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [5540ea0d6f](https://linux-hardware.org/?probe=5540ea0d6f) | Jun 14, 2023 |
| ZOTAC         | ZBOX-EN760                  | Mini pc     | [e36c953da7](https://linux-hardware.org/?probe=e36c953da7) | Jun 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [ea8e583821](https://linux-hardware.org/?probe=ea8e583821) | Jun 14, 2023 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [887bfc11d5](https://linux-hardware.org/?probe=887bfc11d5) | Jun 14, 2023 |
| Dell          | Latitude E5570              | Notebook    | [43171e0f19](https://linux-hardware.org/?probe=43171e0f19) | Jun 14, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2f23e52c68](https://linux-hardware.org/?probe=2f23e52c68) | Jun 14, 2023 |
| Sony          | SVS1312J3EW                 | Notebook    | [6668ed0dbe](https://linux-hardware.org/?probe=6668ed0dbe) | Jun 14, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [40ec446343](https://linux-hardware.org/?probe=40ec446343) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [04f1fdc3c9](https://linux-hardware.org/?probe=04f1fdc3c9) | Jun 14, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [2bc004d4b4](https://linux-hardware.org/?probe=2bc004d4b4) | Jun 14, 2023 |
| HP            | ENVY Notebook               | Notebook    | [6e714661f6](https://linux-hardware.org/?probe=6e714661f6) | Jun 14, 2023 |
| MSI           | GT75 Titan 8RG              | Notebook    | [9e25159fb6](https://linux-hardware.org/?probe=9e25159fb6) | Jun 14, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [b3b70ef13b](https://linux-hardware.org/?probe=b3b70ef13b) | Jun 14, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [aea3f705ed](https://linux-hardware.org/?probe=aea3f705ed) | Jun 13, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [1cddf187c5](https://linux-hardware.org/?probe=1cddf187c5) | Jun 13, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [db1a941e2c](https://linux-hardware.org/?probe=db1a941e2c) | Jun 13, 2023 |
| Samsung       | R540/R538/SA41/E452         | Notebook    | [678c5510d3](https://linux-hardware.org/?probe=678c5510d3) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [0f19266aaf](https://linux-hardware.org/?probe=0f19266aaf) | Jun 13, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a22e7ac3ea](https://linux-hardware.org/?probe=a22e7ac3ea) | Jun 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [6a1f1e134c](https://linux-hardware.org/?probe=6a1f1e134c) | Jun 13, 2023 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | Notebook    | [a0b003c3b1](https://linux-hardware.org/?probe=a0b003c3b1) | Jun 13, 2023 |
| Alienware     | m15 R7                      | Notebook    | [c4a2634a83](https://linux-hardware.org/?probe=c4a2634a83) | Jun 13, 2023 |
| Alienware     | m15 R7                      | Notebook    | [7b53840b8b](https://linux-hardware.org/?probe=7b53840b8b) | Jun 13, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [a515b0dbf7](https://linux-hardware.org/?probe=a515b0dbf7) | Jun 12, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | Notebook    | [20b91b813f](https://linux-hardware.org/?probe=20b91b813f) | Jun 12, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [b870560cb8](https://linux-hardware.org/?probe=b870560cb8) | Jun 12, 2023 |
| Biostar       | A520MH                      | Desktop     | [70760c5e70](https://linux-hardware.org/?probe=70760c5e70) | Jun 12, 2023 |
| Supermicro    | X9DAi                       | Desktop     | [07f73cff06](https://linux-hardware.org/?probe=07f73cff06) | Jun 12, 2023 |
| Dell          | Precision 7560              | Notebook    | [fc461aad87](https://linux-hardware.org/?probe=fc461aad87) | Jun 12, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [69f20a331c](https://linux-hardware.org/?probe=69f20a331c) | Jun 12, 2023 |
| Dell          | Latitude 5520               | Notebook    | [f0fc9a8003](https://linux-hardware.org/?probe=f0fc9a8003) | Jun 11, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c433d533f0](https://linux-hardware.org/?probe=c433d533f0) | Jun 11, 2023 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [c544318b46](https://linux-hardware.org/?probe=c544318b46) | Jun 11, 2023 |
| ASUSTek       | V-P5G43 R1.04G              | Desktop     | [e2400bfebe](https://linux-hardware.org/?probe=e2400bfebe) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [cacba08c72](https://linux-hardware.org/?probe=cacba08c72) | Jun 11, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [008148f553](https://linux-hardware.org/?probe=008148f553) | Jun 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [db301ecd59](https://linux-hardware.org/?probe=db301ecd59) | Jun 11, 2023 |
| Dell          | Precision 5570              | Notebook    | [32975fdf08](https://linux-hardware.org/?probe=32975fdf08) | Jun 11, 2023 |
| NEC Comput... | PC-LM550LS6R                | Notebook    | [695f9825a6](https://linux-hardware.org/?probe=695f9825a6) | Jun 11, 2023 |
| Microsoft     | Surface Laptop Studio       | Tablet      | [58dde53dbd](https://linux-hardware.org/?probe=58dde53dbd) | Jun 11, 2023 |
| Microsoft     | Surface Laptop Studio       | Tablet      | [a2c786f205](https://linux-hardware.org/?probe=a2c786f205) | Jun 11, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [99f3070065](https://linux-hardware.org/?probe=99f3070065) | Jun 11, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [81e4b3fe5c](https://linux-hardware.org/?probe=81e4b3fe5c) | Jun 10, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [b5aee5a0a1](https://linux-hardware.org/?probe=b5aee5a0a1) | Jun 10, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [89aee96c82](https://linux-hardware.org/?probe=89aee96c82) | Jun 10, 2023 |
| Lenovo        | ThinkPad X240 20AMS5XY00    | Notebook    | [3b98c592e0](https://linux-hardware.org/?probe=3b98c592e0) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [c768cfa03d](https://linux-hardware.org/?probe=c768cfa03d) | Jun 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | Notebook    | [3d3375df75](https://linux-hardware.org/?probe=3d3375df75) | Jun 10, 2023 |
| Pegatron      | Benicia                     | Desktop     | [c57fee6ea0](https://linux-hardware.org/?probe=c57fee6ea0) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0eae3567d9](https://linux-hardware.org/?probe=0eae3567d9) | Jun 10, 2023 |
| HP            | 339B                        | Desktop     | [bc6de07e07](https://linux-hardware.org/?probe=bc6de07e07) | Jun 09, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [77145a587d](https://linux-hardware.org/?probe=77145a587d) | Jun 09, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [c605e51eca](https://linux-hardware.org/?probe=c605e51eca) | Jun 09, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c9f26e18c2](https://linux-hardware.org/?probe=c9f26e18c2) | Jun 09, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [98a10d2fd9](https://linux-hardware.org/?probe=98a10d2fd9) | Jun 08, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [65f988a0c3](https://linux-hardware.org/?probe=65f988a0c3) | Jun 08, 2023 |
| AZW           | SEi                         | Desktop     | [399b4a7add](https://linux-hardware.org/?probe=399b4a7add) | Jun 08, 2023 |
| Dell          | Precision 3551              | Notebook    | [0e484bd6a5](https://linux-hardware.org/?probe=0e484bd6a5) | Jun 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [2c3b00b1ae](https://linux-hardware.org/?probe=2c3b00b1ae) | Jun 08, 2023 |
| Dell          | Precision 5510              | Notebook    | [24317d94ff](https://linux-hardware.org/?probe=24317d94ff) | Jun 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [cd3bb98a1e](https://linux-hardware.org/?probe=cd3bb98a1e) | Jun 08, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [f87fe0fe34](https://linux-hardware.org/?probe=f87fe0fe34) | Jun 08, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [f78a07f792](https://linux-hardware.org/?probe=f78a07f792) | Jun 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [57b238a5ff](https://linux-hardware.org/?probe=57b238a5ff) | Jun 08, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [87f789c059](https://linux-hardware.org/?probe=87f789c059) | Jun 07, 2023 |
| MSI           | CreatorPro X17 A12UKS       | Notebook    | [ee827c186c](https://linux-hardware.org/?probe=ee827c186c) | Jun 07, 2023 |
| MSI           | A88XM-E35                   | Desktop     | [efe1285363](https://linux-hardware.org/?probe=efe1285363) | Jun 07, 2023 |
| HP            | 8169                        | Desktop     | [45543e5040](https://linux-hardware.org/?probe=45543e5040) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [933978a1ae](https://linux-hardware.org/?probe=933978a1ae) | Jun 07, 2023 |
| Dell          | Latitude 5530               | Notebook    | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [8b82994313](https://linux-hardware.org/?probe=8b82994313) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [8f3282c700](https://linux-hardware.org/?probe=8f3282c700) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [326a620bbd](https://linux-hardware.org/?probe=326a620bbd) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [9cfd61dae7](https://linux-hardware.org/?probe=9cfd61dae7) | Jun 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| Dell          | Latitude 5530               | Notebook    | [44aa9db289](https://linux-hardware.org/?probe=44aa9db289) | Jun 06, 2023 |
| MSI           | Crosshair 15 C12VF          | Notebook    | [6cd11169d0](https://linux-hardware.org/?probe=6cd11169d0) | Jun 05, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [5534470ef5](https://linux-hardware.org/?probe=5534470ef5) | Jun 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a06e6ab7ad](https://linux-hardware.org/?probe=a06e6ab7ad) | Jun 05, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [cdb3539c93](https://linux-hardware.org/?probe=cdb3539c93) | Jun 05, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [f8789775fe](https://linux-hardware.org/?probe=f8789775fe) | Jun 05, 2023 |
| Intel         | DE3815TYKH H26998-402       | Desktop     | [d2f97c16e9](https://linux-hardware.org/?probe=d2f97c16e9) | Jun 05, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [c68dff0dd7](https://linux-hardware.org/?probe=c68dff0dd7) | Jun 05, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [74b01a9071](https://linux-hardware.org/?probe=74b01a9071) | Jun 05, 2023 |
| ASUSTek       | K95VJ                       | Notebook    | [9bbcec82c6](https://linux-hardware.org/?probe=9bbcec82c6) | Jun 05, 2023 |
| HP            | 1850                        | Desktop     | [bddc14be8b](https://linux-hardware.org/?probe=bddc14be8b) | Jun 05, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Intel         | DH55HC AAE70933-503         | Desktop     | [b3d5e112eb](https://linux-hardware.org/?probe=b3d5e112eb) | Jun 04, 2023 |
| Jumper        | EZbook                      | Notebook    | [950179fe29](https://linux-hardware.org/?probe=950179fe29) | Jun 04, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [1b9656a4a1](https://linux-hardware.org/?probe=1b9656a4a1) | Jun 04, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [f492ab6829](https://linux-hardware.org/?probe=f492ab6829) | Jun 04, 2023 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [f1b932f397](https://linux-hardware.org/?probe=f1b932f397) | Jun 04, 2023 |
| IP3 Tech      | AP1                         | Notebook    | [d24ecf10e2](https://linux-hardware.org/?probe=d24ecf10e2) | Jun 04, 2023 |
| MSI           | H81M-P32                    | Desktop     | [f2423b3ef9](https://linux-hardware.org/?probe=f2423b3ef9) | Jun 04, 2023 |
| MSI           | H81M-P32                    | Desktop     | [f1d0b1d487](https://linux-hardware.org/?probe=f1d0b1d487) | Jun 04, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [968005c798](https://linux-hardware.org/?probe=968005c798) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [d45c069b9f](https://linux-hardware.org/?probe=d45c069b9f) | Jun 04, 2023 |
| Samsung       | 950XED                      | Notebook    | [185834c02e](https://linux-hardware.org/?probe=185834c02e) | Jun 04, 2023 |
| Schenker      | XMG FOCUS (M22)             | Notebook    | [31203c3645](https://linux-hardware.org/?probe=31203c3645) | Jun 03, 2023 |
| Acer          | Aspire TC-705               | Desktop     | [8aa3bc4947](https://linux-hardware.org/?probe=8aa3bc4947) | Jun 03, 2023 |
| HONOR         | HGF-WX6                     | Notebook    | [13d0d7b145](https://linux-hardware.org/?probe=13d0d7b145) | Jun 03, 2023 |
| MSI           | H97M-G43                    | Desktop     | [6bd1b61977](https://linux-hardware.org/?probe=6bd1b61977) | Jun 03, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [75ba9fba2f](https://linux-hardware.org/?probe=75ba9fba2f) | Jun 03, 2023 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [610ba5871f](https://linux-hardware.org/?probe=610ba5871f) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [9b83a4575b](https://linux-hardware.org/?probe=9b83a4575b) | Jun 02, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d856669333](https://linux-hardware.org/?probe=d856669333) | Jun 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [d1fec35ece](https://linux-hardware.org/?probe=d1fec35ece) | Jun 02, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [558ee7e63f](https://linux-hardware.org/?probe=558ee7e63f) | Jun 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4d170e024e](https://linux-hardware.org/?probe=4d170e024e) | Jun 02, 2023 |
| Acer          | Aspire X3950                | Desktop     | [82aa882647](https://linux-hardware.org/?probe=82aa882647) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ECS           | Nettle2                     | Desktop     | [6fe297e475](https://linux-hardware.org/?probe=6fe297e475) | Jun 02, 2023 |
| Acer          | Aspire X3950                | Desktop     | [1c7f0f7567](https://linux-hardware.org/?probe=1c7f0f7567) | Jun 02, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [7739f949e1](https://linux-hardware.org/?probe=7739f949e1) | Jun 02, 2023 |
| HP            | 802E                        | Desktop     | [1837c96bfd](https://linux-hardware.org/?probe=1837c96bfd) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [def2c6020b](https://linux-hardware.org/?probe=def2c6020b) | Jun 01, 2023 |
| MSI           | H81M-E34                    | Desktop     | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [f517c1893a](https://linux-hardware.org/?probe=f517c1893a) | Jun 01, 2023 |
| HP            | 18E5                        | Desktop     | [9d89c3065b](https://linux-hardware.org/?probe=9d89c3065b) | Jun 01, 2023 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [0bb0a8be66](https://linux-hardware.org/?probe=0bb0a8be66) | Jun 01, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Dell          | Latitude E5510              | Notebook    | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [1b1a5c05ac](https://linux-hardware.org/?probe=1b1a5c05ac) | Jun 01, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [3ca0d2f1a7](https://linux-hardware.org/?probe=3ca0d2f1a7) | Jun 01, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [ffc6b5e345](https://linux-hardware.org/?probe=ffc6b5e345) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | Desktop     | [8511ce89ad](https://linux-hardware.org/?probe=8511ce89ad) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [f66667b7fb](https://linux-hardware.org/?probe=f66667b7fb) | Jun 01, 2023 |
| Dell          | Latitude E5510              | Notebook    | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [9faf2de183](https://linux-hardware.org/?probe=9faf2de183) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Acer          | Aspire 3830TG               | Notebook    | [abd7d9a412](https://linux-hardware.org/?probe=abd7d9a412) | May 31, 2023 |
| Packard Be... | EasyNote LJ75               | Notebook    | [95c733d00f](https://linux-hardware.org/?probe=95c733d00f) | May 31, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [ceaf9120eb](https://linux-hardware.org/?probe=ceaf9120eb) | May 31, 2023 |
| MSI           | GE70 2QE                    | Notebook    | [a075b8b77d](https://linux-hardware.org/?probe=a075b8b77d) | May 31, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | Notebook    | [239faf8c55](https://linux-hardware.org/?probe=239faf8c55) | May 31, 2023 |
| MSI           | B85M-G43                    | Desktop     | [38fb05719a](https://linux-hardware.org/?probe=38fb05719a) | May 31, 2023 |
| Dell          | Inspiron 3502               | Notebook    | [3c734d2900](https://linux-hardware.org/?probe=3c734d2900) | May 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [6c3655186f](https://linux-hardware.org/?probe=6c3655186f) | May 31, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | Notebook    | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Dell          | Latitude E5510              | Notebook    | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| ASUSTek       | P4S8L                       | Desktop     | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| Acer          | Aspire V3-574G              | Notebook    | [728459dd4a](https://linux-hardware.org/?probe=728459dd4a) | May 30, 2023 |
| Samsung       | R610                        | Notebook    | [4e3be533ba](https://linux-hardware.org/?probe=4e3be533ba) | May 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [86e04155f2](https://linux-hardware.org/?probe=86e04155f2) | May 30, 2023 |
| Nvidia        | Tegra                       | Soc         | [235f3fa96f](https://linux-hardware.org/?probe=235f3fa96f) | May 30, 2023 |
| Cincoze       | 1.0.01.001                  | Desktop     | [1552e93368](https://linux-hardware.org/?probe=1552e93368) | May 30, 2023 |
| MSI           | H55M-ED55                   | Desktop     | [a89bdc8ec0](https://linux-hardware.org/?probe=a89bdc8ec0) | May 30, 2023 |
| Dell          | Latitude 3480               | Notebook    | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| HP            | 0B54h D                     | Desktop     | [c7813156eb](https://linux-hardware.org/?probe=c7813156eb) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [cddd43859b](https://linux-hardware.org/?probe=cddd43859b) | May 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d4cc055d3a](https://linux-hardware.org/?probe=d4cc055d3a) | May 30, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [afb02cee29](https://linux-hardware.org/?probe=afb02cee29) | May 29, 2023 |
| MSI           | Z170A MPOWER GAMING TITA... | Desktop     | [0e9239c5f7](https://linux-hardware.org/?probe=0e9239c5f7) | May 29, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [1e0fbe86da](https://linux-hardware.org/?probe=1e0fbe86da) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [509bb7aae7](https://linux-hardware.org/?probe=509bb7aae7) | May 29, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [7a52f09646](https://linux-hardware.org/?probe=7a52f09646) | May 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [a46f523ea2](https://linux-hardware.org/?probe=a46f523ea2) | May 29, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [88f3c7f5e5](https://linux-hardware.org/?probe=88f3c7f5e5) | May 29, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | Notebook    | [8d25da413c](https://linux-hardware.org/?probe=8d25da413c) | May 29, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [ece00aac41](https://linux-hardware.org/?probe=ece00aac41) | May 29, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [ae0b46c29f](https://linux-hardware.org/?probe=ae0b46c29f) | May 28, 2023 |
| Dell          | 048DY8 A01                  | Desktop     | [9bfe61714e](https://linux-hardware.org/?probe=9bfe61714e) | May 28, 2023 |
| Dell          | XPS 9320                    | Notebook    | [33e7d964ad](https://linux-hardware.org/?probe=33e7d964ad) | May 28, 2023 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [f7d00f30cb](https://linux-hardware.org/?probe=f7d00f30cb) | May 28, 2023 |
| Shuttle       | X50V5                       | Notebook    | [277cc7ca36](https://linux-hardware.org/?probe=277cc7ca36) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [7af2cff4d7](https://linux-hardware.org/?probe=7af2cff4d7) | May 27, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [d62f60891d](https://linux-hardware.org/?probe=d62f60891d) | May 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [449d13baa5](https://linux-hardware.org/?probe=449d13baa5) | May 27, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [7d4df58daf](https://linux-hardware.org/?probe=7d4df58daf) | May 27, 2023 |
| Dell          | Precision 3581              | Notebook    | [9fb00fd492](https://linux-hardware.org/?probe=9fb00fd492) | May 27, 2023 |
| MSI           | H55M-ED55                   | Desktop     | [61e1fc3841](https://linux-hardware.org/?probe=61e1fc3841) | May 27, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [9dc73257dc](https://linux-hardware.org/?probe=9dc73257dc) | May 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [efe0b55153](https://linux-hardware.org/?probe=efe0b55153) | May 27, 2023 |
| HP            | 81BA                        | All in one  | [d41186191f](https://linux-hardware.org/?probe=d41186191f) | May 27, 2023 |
| Dell          | 0TP406                      | Desktop     | [c7300f35f4](https://linux-hardware.org/?probe=c7300f35f4) | May 26, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c3af0f3242](https://linux-hardware.org/?probe=c3af0f3242) | May 26, 2023 |
| Dell          | Latitude 3520               | Notebook    | [bfa8a18cb5](https://linux-hardware.org/?probe=bfa8a18cb5) | May 26, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [07be92d6f3](https://linux-hardware.org/?probe=07be92d6f3) | May 26, 2023 |
| Dell          | G15 5510                    | Notebook    | [f9e862a5dd](https://linux-hardware.org/?probe=f9e862a5dd) | May 26, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [76a373f9dd](https://linux-hardware.org/?probe=76a373f9dd) | May 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [4c3aa6334b](https://linux-hardware.org/?probe=4c3aa6334b) | May 26, 2023 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [d86873ceab](https://linux-hardware.org/?probe=d86873ceab) | May 26, 2023 |
| ASUSTek       | P4S8L                       | Desktop     | [75096a0d55](https://linux-hardware.org/?probe=75096a0d55) | May 25, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [4a6c3586fa](https://linux-hardware.org/?probe=4a6c3586fa) | May 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [10adda3362](https://linux-hardware.org/?probe=10adda3362) | May 25, 2023 |
| ASUSTek       | N75SF                       | Notebook    | [38840055c8](https://linux-hardware.org/?probe=38840055c8) | May 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [a764ae9f3c](https://linux-hardware.org/?probe=a764ae9f3c) | May 25, 2023 |
| Acer          | EG31M R01-A4                | Desktop     | [447645dad3](https://linux-hardware.org/?probe=447645dad3) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ab42ac444e](https://linux-hardware.org/?probe=ab42ac444e) | May 24, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [9fbeb26e54](https://linux-hardware.org/?probe=9fbeb26e54) | May 24, 2023 |
| Dell          | Precision 5470              | Notebook    | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | 1496                        | Desktop     | [2edc574902](https://linux-hardware.org/?probe=2edc574902) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [8fd8cdb823](https://linux-hardware.org/?probe=8fd8cdb823) | May 24, 2023 |
| Lenovo        | 318E SDK0L22692 WIN 3792... | Desktop     | [5fb6f16a6d](https://linux-hardware.org/?probe=5fb6f16a6d) | May 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d92b2ec905](https://linux-hardware.org/?probe=d92b2ec905) | May 24, 2023 |
| ASRock        | E350M1                      | Desktop     | [d366f5f318](https://linux-hardware.org/?probe=d366f5f318) | May 24, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [2b12b33767](https://linux-hardware.org/?probe=2b12b33767) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [dcafbb2a69](https://linux-hardware.org/?probe=dcafbb2a69) | May 23, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [cbe27885cb](https://linux-hardware.org/?probe=cbe27885cb) | May 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5837575ac6](https://linux-hardware.org/?probe=5837575ac6) | May 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [dc47e13a60](https://linux-hardware.org/?probe=dc47e13a60) | May 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [4e817c1abf](https://linux-hardware.org/?probe=4e817c1abf) | May 23, 2023 |
| ASRock        | E350M1                      | Desktop     | [1debe3dcdf](https://linux-hardware.org/?probe=1debe3dcdf) | May 23, 2023 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [b3062be7f2](https://linux-hardware.org/?probe=b3062be7f2) | May 23, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [f8ef460648](https://linux-hardware.org/?probe=f8ef460648) | May 23, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [4400f1205b](https://linux-hardware.org/?probe=4400f1205b) | May 23, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | Notebook    | [91945b5bb5](https://linux-hardware.org/?probe=91945b5bb5) | May 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fadd25f4c5](https://linux-hardware.org/?probe=fadd25f4c5) | May 23, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| HP            | Pavilion 17                 | Notebook    | [eb6c222cf7](https://linux-hardware.org/?probe=eb6c222cf7) | May 23, 2023 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [3642f34cd6](https://linux-hardware.org/?probe=3642f34cd6) | May 23, 2023 |
| ASUSTek       | K73SD                       | Notebook    | [063e42ac60](https://linux-hardware.org/?probe=063e42ac60) | May 22, 2023 |
| ASUSTek       | UX301LAB                    | Notebook    | [69f7b4ae4f](https://linux-hardware.org/?probe=69f7b4ae4f) | May 22, 2023 |
| HP            | 1791                        | Desktop     | [7fa95d1b7b](https://linux-hardware.org/?probe=7fa95d1b7b) | May 22, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [28a8978593](https://linux-hardware.org/?probe=28a8978593) | May 22, 2023 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [ac40ad8213](https://linux-hardware.org/?probe=ac40ad8213) | May 22, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [012c721256](https://linux-hardware.org/?probe=012c721256) | May 22, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [82f235bfbb](https://linux-hardware.org/?probe=82f235bfbb) | May 22, 2023 |
| Dell          | Latitude E4200              | Notebook    | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b2367f9b1](https://linux-hardware.org/?probe=2b2367f9b1) | May 22, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b3fb445705](https://linux-hardware.org/?probe=b3fb445705) | May 22, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [8b4b66a085](https://linux-hardware.org/?probe=8b4b66a085) | May 22, 2023 |
| HP            | 1589                        | Desktop     | [a7d56849a5](https://linux-hardware.org/?probe=a7d56849a5) | May 22, 2023 |
| Lenovo        | 3753 NOK                    | Desktop     | [f2971c14a7](https://linux-hardware.org/?probe=f2971c14a7) | May 21, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [9db5706bfc](https://linux-hardware.org/?probe=9db5706bfc) | May 21, 2023 |
| HP            | ProBook 4310s               | Notebook    | [1a32d434c0](https://linux-hardware.org/?probe=1a32d434c0) | May 21, 2023 |
| MSI           | PS63 Modern 8MO             | Notebook    | [5d6f78bfbb](https://linux-hardware.org/?probe=5d6f78bfbb) | May 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [bfaa8e099f](https://linux-hardware.org/?probe=bfaa8e099f) | May 21, 2023 |
| ASUSTek       | G752VY                      | Notebook    | [2762dac255](https://linux-hardware.org/?probe=2762dac255) | May 21, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [31c946c569](https://linux-hardware.org/?probe=31c946c569) | May 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [32e623c724](https://linux-hardware.org/?probe=32e623c724) | May 21, 2023 |
| Rockchip      | Unknown                     | Soc         | [f02cc91719](https://linux-hardware.org/?probe=f02cc91719) | May 21, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [473ea193d5](https://linux-hardware.org/?probe=473ea193d5) | May 21, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [ed99950768](https://linux-hardware.org/?probe=ed99950768) | May 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [c5fee7bb50](https://linux-hardware.org/?probe=c5fee7bb50) | May 20, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [14e978a000](https://linux-hardware.org/?probe=14e978a000) | May 20, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [b38a68e146](https://linux-hardware.org/?probe=b38a68e146) | May 20, 2023 |
| MSI           | H97M-G43                    | Desktop     | [2e31a2b7e0](https://linux-hardware.org/?probe=2e31a2b7e0) | May 20, 2023 |
| Lenovo        | ThinkPad W510 4391DK3       | Notebook    | [ac8db768ce](https://linux-hardware.org/?probe=ac8db768ce) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [de162ff16c](https://linux-hardware.org/?probe=de162ff16c) | May 20, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [c1089ff84e](https://linux-hardware.org/?probe=c1089ff84e) | May 20, 2023 |
| Pegatron      | Benicia                     | Desktop     | [24fc512198](https://linux-hardware.org/?probe=24fc512198) | May 19, 2023 |
| Dell          | Precision 5470              | Notebook    | [e600af2d5a](https://linux-hardware.org/?probe=e600af2d5a) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9f1830f264](https://linux-hardware.org/?probe=9f1830f264) | May 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [73aafcfb9c](https://linux-hardware.org/?probe=73aafcfb9c) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [52bfbb69ee](https://linux-hardware.org/?probe=52bfbb69ee) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [6d04bdb08d](https://linux-hardware.org/?probe=6d04bdb08d) | May 19, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [bb5b5bd73c](https://linux-hardware.org/?probe=bb5b5bd73c) | May 19, 2023 |
| Pegatron      | Benicia                     | Desktop     | [6bb420fe9a](https://linux-hardware.org/?probe=6bb420fe9a) | May 19, 2023 |
| ASUSTek       | F7Se                        | Notebook    | [1cd79e84fd](https://linux-hardware.org/?probe=1cd79e84fd) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d8d391a609](https://linux-hardware.org/?probe=d8d391a609) | May 18, 2023 |
| Packard Be... | PT890-8237A                 | Desktop     | [b15e7cc105](https://linux-hardware.org/?probe=b15e7cc105) | May 18, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [f4548ca81b](https://linux-hardware.org/?probe=f4548ca81b) | May 18, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c09d32ebc2](https://linux-hardware.org/?probe=c09d32ebc2) | May 18, 2023 |
| Toshiba       | Satellite C855-22N          | Notebook    | [f5ccfb46ea](https://linux-hardware.org/?probe=f5ccfb46ea) | May 18, 2023 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [2914e5278a](https://linux-hardware.org/?probe=2914e5278a) | May 18, 2023 |
| ASUSTek       | M4A77TD                     | Desktop     | [ccd791a9d4](https://linux-hardware.org/?probe=ccd791a9d4) | May 18, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | Notebook    | [d1569df0f6](https://linux-hardware.org/?probe=d1569df0f6) | May 18, 2023 |
| Gateway       | DS10G                       | Desktop     | [556a92e56a](https://linux-hardware.org/?probe=556a92e56a) | May 18, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [5b51a121e2](https://linux-hardware.org/?probe=5b51a121e2) | May 18, 2023 |
| Pegatron      | Benicia                     | Desktop     | [8d49889e39](https://linux-hardware.org/?probe=8d49889e39) | May 18, 2023 |
| Dell          | Precision 5520              | Notebook    | [6e4c751579](https://linux-hardware.org/?probe=6e4c751579) | May 18, 2023 |
| HP            | ProBook 4310s               | Notebook    | [dfcb51e697](https://linux-hardware.org/?probe=dfcb51e697) | May 17, 2023 |
| Dell          | Latitude 7490               | Notebook    | [392cde1432](https://linux-hardware.org/?probe=392cde1432) | May 17, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | Notebook    | [baa1b942cf](https://linux-hardware.org/?probe=baa1b942cf) | May 17, 2023 |
| Dell          | Inspiron 5580               | Notebook    | [7ced5f9473](https://linux-hardware.org/?probe=7ced5f9473) | May 17, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [2a6dcbf826](https://linux-hardware.org/?probe=2a6dcbf826) | May 17, 2023 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [d43fc4e5b9](https://linux-hardware.org/?probe=d43fc4e5b9) | May 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [863f20642f](https://linux-hardware.org/?probe=863f20642f) | May 17, 2023 |
| ASUSTek       | B150-PLUS                   | Desktop     | [41b19667a8](https://linux-hardware.org/?probe=41b19667a8) | May 17, 2023 |
| Acer          | TravelMate X514-51          | Notebook    | [24465d2184](https://linux-hardware.org/?probe=24465d2184) | May 17, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [04a6fe63c1](https://linux-hardware.org/?probe=04a6fe63c1) | May 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [add6bcd4f7](https://linux-hardware.org/?probe=add6bcd4f7) | May 16, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2616bd6b98](https://linux-hardware.org/?probe=2616bd6b98) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | Notebook    | [d825262368](https://linux-hardware.org/?probe=d825262368) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | Notebook    | [18ca79ef29](https://linux-hardware.org/?probe=18ca79ef29) | May 16, 2023 |
| SLIMBOOK      | Executive                   | Notebook    | [0a70f31ce9](https://linux-hardware.org/?probe=0a70f31ce9) | May 16, 2023 |
| Dell          | Precision 5530              | Notebook    | [16366ef886](https://linux-hardware.org/?probe=16366ef886) | May 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [05441101a8](https://linux-hardware.org/?probe=05441101a8) | May 16, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [b06c75ac5e](https://linux-hardware.org/?probe=b06c75ac5e) | May 16, 2023 |
| Lenovo        | ThinkPad T440 20B7S1MF0D    | Notebook    | [6173458650](https://linux-hardware.org/?probe=6173458650) | May 16, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [050d9ad83f](https://linux-hardware.org/?probe=050d9ad83f) | May 16, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [2fa63538ef](https://linux-hardware.org/?probe=2fa63538ef) | May 15, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [4529ae76bb](https://linux-hardware.org/?probe=4529ae76bb) | May 15, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [6a8a2f481e](https://linux-hardware.org/?probe=6a8a2f481e) | May 15, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [55eb2f47b9](https://linux-hardware.org/?probe=55eb2f47b9) | May 15, 2023 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [02da78340f](https://linux-hardware.org/?probe=02da78340f) | May 15, 2023 |
| HP            | 8436                        | Desktop     | [ae94b377fd](https://linux-hardware.org/?probe=ae94b377fd) | May 15, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [2e2744285f](https://linux-hardware.org/?probe=2e2744285f) | May 15, 2023 |
| Sony          | VPCF11M1E                   | Notebook    | [b42c56ac73](https://linux-hardware.org/?probe=b42c56ac73) | May 14, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b08b887e1a](https://linux-hardware.org/?probe=b08b887e1a) | May 14, 2023 |
| Sony          | VGN-FW51MF_H                | Notebook    | [572b403a00](https://linux-hardware.org/?probe=572b403a00) | May 14, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [d200313f91](https://linux-hardware.org/?probe=d200313f91) | May 14, 2023 |
| Sony          | VGN-FW51MF_H                | Notebook    | [0b0cc4f60e](https://linux-hardware.org/?probe=0b0cc4f60e) | May 14, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [d8735e3006](https://linux-hardware.org/?probe=d8735e3006) | May 14, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [bf3ff003f9](https://linux-hardware.org/?probe=bf3ff003f9) | May 14, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [ffe7a5c97b](https://linux-hardware.org/?probe=ffe7a5c97b) | May 14, 2023 |
| HP            | Notebook                    | Notebook    | [decd46d3ed](https://linux-hardware.org/?probe=decd46d3ed) | May 14, 2023 |
| Dell          | Latitude E5420              | Notebook    | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [6335ace28b](https://linux-hardware.org/?probe=6335ace28b) | May 14, 2023 |
| AMI           | Intel                       | Notebook    | [958f5ffc92](https://linux-hardware.org/?probe=958f5ffc92) | May 14, 2023 |
| AMI           | Intel                       | Notebook    | [0c9a68a20c](https://linux-hardware.org/?probe=0c9a68a20c) | May 13, 2023 |
| HP            | 3397                        | Desktop     | [c6f97f09f1](https://linux-hardware.org/?probe=c6f97f09f1) | May 13, 2023 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [56783f77b9](https://linux-hardware.org/?probe=56783f77b9) | May 13, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [0f3a2fae1b](https://linux-hardware.org/?probe=0f3a2fae1b) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | Desktop     | [ede664c4ca](https://linux-hardware.org/?probe=ede664c4ca) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | Desktop     | [4849aadd59](https://linux-hardware.org/?probe=4849aadd59) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [ef9c6905f1](https://linux-hardware.org/?probe=ef9c6905f1) | May 13, 2023 |
| Dell          | Latitude 7490               | Notebook    | [16cfe08da3](https://linux-hardware.org/?probe=16cfe08da3) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [bfff1b604f](https://linux-hardware.org/?probe=bfff1b604f) | May 13, 2023 |
| Jumper        | EZbook                      | Notebook    | [56321a4f9c](https://linux-hardware.org/?probe=56321a4f9c) | May 13, 2023 |
| ASUSTek       | GL10CS                      | Desktop     | [270c5658e6](https://linux-hardware.org/?probe=270c5658e6) | May 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ef37458c10](https://linux-hardware.org/?probe=ef37458c10) | May 13, 2023 |
| Dell          | 0D883F A05                  | Desktop     | [99e782e805](https://linux-hardware.org/?probe=99e782e805) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [804de32208](https://linux-hardware.org/?probe=804de32208) | May 13, 2023 |
| MSI           | GL73 8RC                    | Notebook    | [4eb76264f2](https://linux-hardware.org/?probe=4eb76264f2) | May 12, 2023 |
| ASUSTek       | X411UA                      | Notebook    | [bd54bb7c02](https://linux-hardware.org/?probe=bd54bb7c02) | May 12, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Dell          | Precision 5550              | Notebook    | [f6d4846655](https://linux-hardware.org/?probe=f6d4846655) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| HP            | Stream Notebook             | Notebook    | [5ed3be74da](https://linux-hardware.org/?probe=5ed3be74da) | May 12, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [30bda7d8cb](https://linux-hardware.org/?probe=30bda7d8cb) | May 12, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [848eedb681](https://linux-hardware.org/?probe=848eedb681) | May 12, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87edc3a632](https://linux-hardware.org/?probe=87edc3a632) | May 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [f5d0a04a09](https://linux-hardware.org/?probe=f5d0a04a09) | May 12, 2023 |
| Medion        | Crawler E40                 | Notebook    | [d0df38a2da](https://linux-hardware.org/?probe=d0df38a2da) | May 12, 2023 |
| Medion        | Crawler E40                 | Notebook    | [c58193ce55](https://linux-hardware.org/?probe=c58193ce55) | May 12, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [ba542c09f2](https://linux-hardware.org/?probe=ba542c09f2) | May 12, 2023 |
| Dell          | Latitude 7400               | Notebook    | [c8ce2e462f](https://linux-hardware.org/?probe=c8ce2e462f) | May 11, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [aec2bbbb46](https://linux-hardware.org/?probe=aec2bbbb46) | May 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [64159d4a10](https://linux-hardware.org/?probe=64159d4a10) | May 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [68caa87cfd](https://linux-hardware.org/?probe=68caa87cfd) | May 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a1cb5cae49](https://linux-hardware.org/?probe=a1cb5cae49) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7b53d1c3dc](https://linux-hardware.org/?probe=7b53d1c3dc) | May 11, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [f56ecb2642](https://linux-hardware.org/?probe=f56ecb2642) | May 11, 2023 |
| Dell          | Latitude E4310              | Notebook    | [84d1a3fda9](https://linux-hardware.org/?probe=84d1a3fda9) | May 11, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [6131eb37d1](https://linux-hardware.org/?probe=6131eb37d1) | May 11, 2023 |
| Lenovo        | ThinkPad X240 20AMS1J100    | Notebook    | [86edc6c6d6](https://linux-hardware.org/?probe=86edc6c6d6) | May 11, 2023 |
| ASUSTek       | X411UA                      | Notebook    | [bc27160391](https://linux-hardware.org/?probe=bc27160391) | May 10, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [0337ec13a6](https://linux-hardware.org/?probe=0337ec13a6) | May 10, 2023 |
| Dell          | Precision 5520              | Notebook    | [5dfdbeff37](https://linux-hardware.org/?probe=5dfdbeff37) | May 10, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [7df7ca9fbf](https://linux-hardware.org/?probe=7df7ca9fbf) | May 10, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [4d0b606423](https://linux-hardware.org/?probe=4d0b606423) | May 10, 2023 |
| HP            | Presario CQ62               | Notebook    | [7619e0cff9](https://linux-hardware.org/?probe=7619e0cff9) | May 10, 2023 |
| Sony          | SVE1713K1EB                 | Notebook    | [96244b73e7](https://linux-hardware.org/?probe=96244b73e7) | May 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [25b993b097](https://linux-hardware.org/?probe=25b993b097) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [0b797e8428](https://linux-hardware.org/?probe=0b797e8428) | May 10, 2023 |
| Notebook      | N150ZU                      | Notebook    | [bfd69adf4e](https://linux-hardware.org/?probe=bfd69adf4e) | May 10, 2023 |
| Thomson       | N14C64WF                    | Notebook    | [4e5a5f6e51](https://linux-hardware.org/?probe=4e5a5f6e51) | May 10, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [4d84deed6b](https://linux-hardware.org/?probe=4d84deed6b) | May 09, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ba75f23f44](https://linux-hardware.org/?probe=ba75f23f44) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [dc1db599ea](https://linux-hardware.org/?probe=dc1db599ea) | May 09, 2023 |
| Dell          | G5 5590                     | Notebook    | [c07c29d5de](https://linux-hardware.org/?probe=c07c29d5de) | May 09, 2023 |
| MSI           | B85-G43                     | Desktop     | [461e3ed4bc](https://linux-hardware.org/?probe=461e3ed4bc) | May 09, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [db93afa653](https://linux-hardware.org/?probe=db93afa653) | May 09, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [0a758d5a5d](https://linux-hardware.org/?probe=0a758d5a5d) | May 08, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [1f7840b315](https://linux-hardware.org/?probe=1f7840b315) | May 08, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [7934eebd9b](https://linux-hardware.org/?probe=7934eebd9b) | May 08, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [5bc5ccdcad](https://linux-hardware.org/?probe=5bc5ccdcad) | May 08, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [4c3f70e8d3](https://linux-hardware.org/?probe=4c3f70e8d3) | May 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [dc97e2fc43](https://linux-hardware.org/?probe=dc97e2fc43) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4e424e0ad2](https://linux-hardware.org/?probe=4e424e0ad2) | May 08, 2023 |
| Dell          | 0T656F A01                  | Desktop     | [94294c8cf0](https://linux-hardware.org/?probe=94294c8cf0) | May 08, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [995e6d9580](https://linux-hardware.org/?probe=995e6d9580) | May 08, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [0d2ac684c8](https://linux-hardware.org/?probe=0d2ac684c8) | May 08, 2023 |
| HP            | EliteBook 725 G4            | Notebook    | [bf3ce4741e](https://linux-hardware.org/?probe=bf3ce4741e) | May 08, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [ea808c2e80](https://linux-hardware.org/?probe=ea808c2e80) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [f4d1f788e1](https://linux-hardware.org/?probe=f4d1f788e1) | May 08, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [382b81c0d1](https://linux-hardware.org/?probe=382b81c0d1) | May 08, 2023 |
| HP            | 3031h                       | Desktop     | [dc7b257f83](https://linux-hardware.org/?probe=dc7b257f83) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X432... | Notebook    | [395097d3a3](https://linux-hardware.org/?probe=395097d3a3) | May 08, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [bbf20cfdad](https://linux-hardware.org/?probe=bbf20cfdad) | May 08, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [48d87e5c6e](https://linux-hardware.org/?probe=48d87e5c6e) | May 08, 2023 |
| Sony          | VPCZ12C5E                   | Notebook    | [512da95fb0](https://linux-hardware.org/?probe=512da95fb0) | May 08, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYFR    | Notebook    | [f945ec106e](https://linux-hardware.org/?probe=f945ec106e) | May 07, 2023 |
| Dell          | Precision 5510              | Notebook    | [9a4ba61d41](https://linux-hardware.org/?probe=9a4ba61d41) | May 07, 2023 |
| Dell          | MXG061                      | Notebook    | [8ef701b61d](https://linux-hardware.org/?probe=8ef701b61d) | May 07, 2023 |
| ASUSTek       | K73SJ                       | Notebook    | [99ede66d8d](https://linux-hardware.org/?probe=99ede66d8d) | May 07, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [c7d1eac585](https://linux-hardware.org/?probe=c7d1eac585) | May 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [816f9e047a](https://linux-hardware.org/?probe=816f9e047a) | May 07, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [e69f8169fc](https://linux-hardware.org/?probe=e69f8169fc) | May 07, 2023 |
| Lenovo        | ThinkPad SL500 27464DG      | Notebook    | [f2bb35c6d3](https://linux-hardware.org/?probe=f2bb35c6d3) | May 07, 2023 |
| Sony          | VPCZ12C5E                   | Notebook    | [67e1fdf9c2](https://linux-hardware.org/?probe=67e1fdf9c2) | May 07, 2023 |
| ASUSTek       | K73SJ                       | Notebook    | [13b8c8be10](https://linux-hardware.org/?probe=13b8c8be10) | May 07, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0fa7cb39ce](https://linux-hardware.org/?probe=0fa7cb39ce) | May 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [270eaa3e12](https://linux-hardware.org/?probe=270eaa3e12) | May 07, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [4681975f9d](https://linux-hardware.org/?probe=4681975f9d) | May 07, 2023 |
| HP            | Presario CQ57               | Notebook    | [370295ac6d](https://linux-hardware.org/?probe=370295ac6d) | May 07, 2023 |
| Alienware     | 18                          | Notebook    | [4c6abf91cd](https://linux-hardware.org/?probe=4c6abf91cd) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [50b503ae3e](https://linux-hardware.org/?probe=50b503ae3e) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [64bbfa416b](https://linux-hardware.org/?probe=64bbfa416b) | May 07, 2023 |
| Shuttle       | FZ77                        | Desktop     | [e4a71bcb2d](https://linux-hardware.org/?probe=e4a71bcb2d) | May 07, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [6c404ee491](https://linux-hardware.org/?probe=6c404ee491) | May 06, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [9d7736a816](https://linux-hardware.org/?probe=9d7736a816) | May 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [dd406112de](https://linux-hardware.org/?probe=dd406112de) | May 06, 2023 |
| Dell          | Precision 7550              | Notebook    | [5f962aaea0](https://linux-hardware.org/?probe=5f962aaea0) | May 06, 2023 |
| Acer          | Aspire 7720                 | Notebook    | [e28510b64d](https://linux-hardware.org/?probe=e28510b64d) | May 06, 2023 |
| Intel         | WADE-8076-ST-WMS            | Desktop     | [ae71682181](https://linux-hardware.org/?probe=ae71682181) | May 06, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [c67960852a](https://linux-hardware.org/?probe=c67960852a) | May 06, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [985f971691](https://linux-hardware.org/?probe=985f971691) | May 06, 2023 |
| ASUSTek       | Strix GL504GS_GL504GS       | Notebook    | [cdb842cc09](https://linux-hardware.org/?probe=cdb842cc09) | May 06, 2023 |
| Acer          | NC-V3-772G-747A8G1TMAKK     | Notebook    | [58f420d816](https://linux-hardware.org/?probe=58f420d816) | May 06, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b4f013c967](https://linux-hardware.org/?probe=b4f013c967) | May 06, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [4b45fabd96](https://linux-hardware.org/?probe=4b45fabd96) | May 05, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [7c3b61fab9](https://linux-hardware.org/?probe=7c3b61fab9) | May 05, 2023 |
| Acer          | Aspire 7720                 | Notebook    | [2e216b0830](https://linux-hardware.org/?probe=2e216b0830) | May 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS46900    | Notebook    | [523dce6a6d](https://linux-hardware.org/?probe=523dce6a6d) | May 05, 2023 |
| HP            | 1589                        | Desktop     | [dd3e55b423](https://linux-hardware.org/?probe=dd3e55b423) | May 05, 2023 |
| Unknown       | X133                        | Notebook    | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| Dell          | 0PU052                      | Desktop     | [03c6b8486e](https://linux-hardware.org/?probe=03c6b8486e) | May 05, 2023 |
| eMachines     | eMG620                      | Notebook    | [224dc7209e](https://linux-hardware.org/?probe=224dc7209e) | May 04, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [11a0e59867](https://linux-hardware.org/?probe=11a0e59867) | May 04, 2023 |
| Dell          | 05WNJ2 A03                  | Server      | [fe6dc0d9c7](https://linux-hardware.org/?probe=fe6dc0d9c7) | May 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [65d9b877b5](https://linux-hardware.org/?probe=65d9b877b5) | May 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [383b9d3aec](https://linux-hardware.org/?probe=383b9d3aec) | May 04, 2023 |
| Acer          | Aspire X1430                | Desktop     | [4bdb74f57e](https://linux-hardware.org/?probe=4bdb74f57e) | May 04, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [e31c30bd52](https://linux-hardware.org/?probe=e31c30bd52) | May 04, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [da8be5a40f](https://linux-hardware.org/?probe=da8be5a40f) | May 04, 2023 |
| ASUSTek       | K61IC                       | Notebook    | [727b9fae92](https://linux-hardware.org/?probe=727b9fae92) | May 03, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [b11821f4a1](https://linux-hardware.org/?probe=b11821f4a1) | May 03, 2023 |
| HP            | Unknown                     | Notebook    | [b99510884b](https://linux-hardware.org/?probe=b99510884b) | May 03, 2023 |
| HPE           | ProLiant DL360 Gen10 Plu... | Server      | [74466ad718](https://linux-hardware.org/?probe=74466ad718) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [fc1bd7fffc](https://linux-hardware.org/?probe=fc1bd7fffc) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [c8373114ef](https://linux-hardware.org/?probe=c8373114ef) | May 03, 2023 |
| HP            | Pavilion dm4                | Notebook    | [cb567d8263](https://linux-hardware.org/?probe=cb567d8263) | May 03, 2023 |
| Acer          | H57M01                      | Desktop     | [affe73e1a5](https://linux-hardware.org/?probe=affe73e1a5) | May 03, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [456582ed94](https://linux-hardware.org/?probe=456582ed94) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [f115308631](https://linux-hardware.org/?probe=f115308631) | May 03, 2023 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a60578cfe2](https://linux-hardware.org/?probe=a60578cfe2) | May 02, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [ee33a17baa](https://linux-hardware.org/?probe=ee33a17baa) | May 02, 2023 |
| HP            | 2AFB                        | Desktop     | [a2d8494867](https://linux-hardware.org/?probe=a2d8494867) | May 01, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [6bfbb6bee6](https://linux-hardware.org/?probe=6bfbb6bee6) | May 01, 2023 |
| MSI           | Katana GF76 12UEK           | Notebook    | [5af5d6aec3](https://linux-hardware.org/?probe=5af5d6aec3) | May 01, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [4946cab965](https://linux-hardware.org/?probe=4946cab965) | May 01, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [4eb2bc6e88](https://linux-hardware.org/?probe=4eb2bc6e88) | May 01, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [ee97e0f5f0](https://linux-hardware.org/?probe=ee97e0f5f0) | May 01, 2023 |
| ASUSTek       | ZenBook UX535LI             | Notebook    | [35adc352dd](https://linux-hardware.org/?probe=35adc352dd) | May 01, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [2fd44c38fd](https://linux-hardware.org/?probe=2fd44c38fd) | May 01, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3be920565f](https://linux-hardware.org/?probe=3be920565f) | May 01, 2023 |
| Sony          | VGN-AW11M_H                 | Notebook    | [2c9f98ca31](https://linux-hardware.org/?probe=2c9f98ca31) | May 01, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [50a67ab03c](https://linux-hardware.org/?probe=50a67ab03c) | May 01, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [0d041ed447](https://linux-hardware.org/?probe=0d041ed447) | May 01, 2023 |
| MSI           | X99A GAMING 7               | Desktop     | [dfb285267c](https://linux-hardware.org/?probe=dfb285267c) | May 01, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [4b23b933b5](https://linux-hardware.org/?probe=4b23b933b5) | May 01, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [02c2bfee54](https://linux-hardware.org/?probe=02c2bfee54) | May 01, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ba99960d5f](https://linux-hardware.org/?probe=ba99960d5f) | May 01, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [4bec088d90](https://linux-hardware.org/?probe=4bec088d90) | Apr 30, 2023 |
| MSI           | IONA                        | Desktop     | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [4c8bb5eff0](https://linux-hardware.org/?probe=4c8bb5eff0) | Apr 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [3bee1a3271](https://linux-hardware.org/?probe=3bee1a3271) | Apr 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [2dd85470a0](https://linux-hardware.org/?probe=2dd85470a0) | Apr 30, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [9a1d443928](https://linux-hardware.org/?probe=9a1d443928) | Apr 30, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [00fbe71b59](https://linux-hardware.org/?probe=00fbe71b59) | Apr 30, 2023 |
| Samsung       | 950XED                      | Notebook    | [41f620de17](https://linux-hardware.org/?probe=41f620de17) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [8cb7a3612c](https://linux-hardware.org/?probe=8cb7a3612c) | Apr 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [99a89a2055](https://linux-hardware.org/?probe=99a89a2055) | Apr 30, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [6f4c134615](https://linux-hardware.org/?probe=6f4c134615) | Apr 29, 2023 |
| Sony          | VPCF11M1E                   | Notebook    | [16772fe220](https://linux-hardware.org/?probe=16772fe220) | Apr 29, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [c203c197b7](https://linux-hardware.org/?probe=c203c197b7) | Apr 29, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [244cfe88a4](https://linux-hardware.org/?probe=244cfe88a4) | Apr 29, 2023 |
| MSI           | P65 Creator 9SF             | Notebook    | [4e682b2c20](https://linux-hardware.org/?probe=4e682b2c20) | Apr 29, 2023 |
| Acer          | Aspire E5-722               | Notebook    | [d02052aeab](https://linux-hardware.org/?probe=d02052aeab) | Apr 29, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [2f3308a2ee](https://linux-hardware.org/?probe=2f3308a2ee) | Apr 29, 2023 |
| COPELION I... | QX-250 Series               | Notebook    | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c17b468722](https://linux-hardware.org/?probe=c17b468722) | Apr 29, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [aa8c0bb2b9](https://linux-hardware.org/?probe=aa8c0bb2b9) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [09d6d7e570](https://linux-hardware.org/?probe=09d6d7e570) | Apr 28, 2023 |
| Lenovo        | ThinkPad L560 20F2S13L00    | Notebook    | [7695cef903](https://linux-hardware.org/?probe=7695cef903) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Dell          | Precision 3551              | Notebook    | [99ff11c325](https://linux-hardware.org/?probe=99ff11c325) | Apr 28, 2023 |
| Dell          | Precision 3551              | Notebook    | [93a38e7384](https://linux-hardware.org/?probe=93a38e7384) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Dell          | 0KFKMF A00                  | All in one  | [cbae954ecc](https://linux-hardware.org/?probe=cbae954ecc) | Apr 28, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [dcfa7042da](https://linux-hardware.org/?probe=dcfa7042da) | Apr 28, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [815dd8e866](https://linux-hardware.org/?probe=815dd8e866) | Apr 28, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [990335263d](https://linux-hardware.org/?probe=990335263d) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [266688994a](https://linux-hardware.org/?probe=266688994a) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [af0663fd52](https://linux-hardware.org/?probe=af0663fd52) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [31bdde77c9](https://linux-hardware.org/?probe=31bdde77c9) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [eb550390c1](https://linux-hardware.org/?probe=eb550390c1) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [7c34e35183](https://linux-hardware.org/?probe=7c34e35183) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [266477f792](https://linux-hardware.org/?probe=266477f792) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [ceaa38e624](https://linux-hardware.org/?probe=ceaa38e624) | Apr 28, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [6daa7002c8](https://linux-hardware.org/?probe=6daa7002c8) | Apr 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b21dd8d75a](https://linux-hardware.org/?probe=b21dd8d75a) | Apr 27, 2023 |
| Dell          | Latitude E7270              | Notebook    | [5bacf4eea3](https://linux-hardware.org/?probe=5bacf4eea3) | Apr 27, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [710070cf4a](https://linux-hardware.org/?probe=710070cf4a) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [f549cb502c](https://linux-hardware.org/?probe=f549cb502c) | Apr 27, 2023 |
| HP            | Pavilion g6                 | Notebook    | [716373f59a](https://linux-hardware.org/?probe=716373f59a) | Apr 27, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e694779b17](https://linux-hardware.org/?probe=e694779b17) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [1e07e42dd3](https://linux-hardware.org/?probe=1e07e42dd3) | Apr 26, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [474c43577f](https://linux-hardware.org/?probe=474c43577f) | Apr 26, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [7bed835979](https://linux-hardware.org/?probe=7bed835979) | Apr 26, 2023 |
| Timi          | TM1703                      | Notebook    | [7e6b948ea9](https://linux-hardware.org/?probe=7e6b948ea9) | Apr 26, 2023 |
| Samsung       | 950XED                      | Notebook    | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| HP            | 1825                        | Desktop     | [5a26051aec](https://linux-hardware.org/?probe=5a26051aec) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [a89604dccd](https://linux-hardware.org/?probe=a89604dccd) | Apr 26, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [d9decf6f0a](https://linux-hardware.org/?probe=d9decf6f0a) | Apr 26, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [e37d368767](https://linux-hardware.org/?probe=e37d368767) | Apr 26, 2023 |
| ASUSTek       | K73BR                       | Notebook    | [547b19cd2c](https://linux-hardware.org/?probe=547b19cd2c) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| Dell          | Latitude 5430               | Notebook    | [75ac9d10bf](https://linux-hardware.org/?probe=75ac9d10bf) | Apr 26, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [bf207e9dc3](https://linux-hardware.org/?probe=bf207e9dc3) | Apr 25, 2023 |
| ASRock        | G31M-S                      | Desktop     | [98c2b2c382](https://linux-hardware.org/?probe=98c2b2c382) | Apr 25, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [da35752b66](https://linux-hardware.org/?probe=da35752b66) | Apr 25, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [290f3ebad7](https://linux-hardware.org/?probe=290f3ebad7) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [cb8885f205](https://linux-hardware.org/?probe=cb8885f205) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [cacc141f4f](https://linux-hardware.org/?probe=cacc141f4f) | Apr 25, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | Desktop     | [f82b3152d0](https://linux-hardware.org/?probe=f82b3152d0) | Apr 25, 2023 |
| LDLC          | SPC-I                       | Notebook    | [899fb46a02](https://linux-hardware.org/?probe=899fb46a02) | Apr 25, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e4c737a64d](https://linux-hardware.org/?probe=e4c737a64d) | Apr 25, 2023 |
| MSI           | H110M ECO                   | Desktop     | [bfa2b17374](https://linux-hardware.org/?probe=bfa2b17374) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [253f35c2c3](https://linux-hardware.org/?probe=253f35c2c3) | Apr 24, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [ebe492b020](https://linux-hardware.org/?probe=ebe492b020) | Apr 24, 2023 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [a62e386eae](https://linux-hardware.org/?probe=a62e386eae) | Apr 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [e36f5e17a5](https://linux-hardware.org/?probe=e36f5e17a5) | Apr 24, 2023 |
| Samsung       | 950XED                      | Notebook    | [6226147e11](https://linux-hardware.org/?probe=6226147e11) | Apr 24, 2023 |
| LG Electro... | 16Z90Q-G.AD78F              | Notebook    | [99bbc09adb](https://linux-hardware.org/?probe=99bbc09adb) | Apr 24, 2023 |
| G7-2011       | X79                         | Desktop     | [5070a0a7a7](https://linux-hardware.org/?probe=5070a0a7a7) | Apr 24, 2023 |
| Dell          | 0VHRW1 A03                  | Desktop     | [6316886f98](https://linux-hardware.org/?probe=6316886f98) | Apr 24, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [5e6b796278](https://linux-hardware.org/?probe=5e6b796278) | Apr 24, 2023 |
| HP            | 15                          | Notebook    | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [bd9d832f72](https://linux-hardware.org/?probe=bd9d832f72) | Apr 23, 2023 |
| Sony          | VPCEH3U1E                   | Notebook    | [6fa28ef21c](https://linux-hardware.org/?probe=6fa28ef21c) | Apr 23, 2023 |
| HP            | ProBook 6570b               | Notebook    | [4e2ba781e2](https://linux-hardware.org/?probe=4e2ba781e2) | Apr 23, 2023 |
| Dell          | Latitude 5591               | Notebook    | [b4dfa57eea](https://linux-hardware.org/?probe=b4dfa57eea) | Apr 23, 2023 |
| Gigabyte      | Z97P-D3                     | Desktop     | [5da4c37f75](https://linux-hardware.org/?probe=5da4c37f75) | Apr 23, 2023 |
| Dell          | Latitude 5591               | Notebook    | [1a45f96f80](https://linux-hardware.org/?probe=1a45f96f80) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [45d7bd0907](https://linux-hardware.org/?probe=45d7bd0907) | Apr 23, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [9ba55985fd](https://linux-hardware.org/?probe=9ba55985fd) | Apr 23, 2023 |
| Shuttle       | DS20U                       | Desktop     | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [c7367bfdff](https://linux-hardware.org/?probe=c7367bfdff) | Apr 23, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [2508f138a4](https://linux-hardware.org/?probe=2508f138a4) | Apr 23, 2023 |
| HP            | 845A                        | Desktop     | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [aa01246f8b](https://linux-hardware.org/?probe=aa01246f8b) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [9a6f040039](https://linux-hardware.org/?probe=9a6f040039) | Apr 23, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [90f041e2a1](https://linux-hardware.org/?probe=90f041e2a1) | Apr 23, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [6d06ef4fa1](https://linux-hardware.org/?probe=6d06ef4fa1) | Apr 23, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [bee14868f2](https://linux-hardware.org/?probe=bee14868f2) | Apr 23, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [5d61deb4d4](https://linux-hardware.org/?probe=5d61deb4d4) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | Desktop     | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | Notebook    | [77a309dcf1](https://linux-hardware.org/?probe=77a309dcf1) | Apr 22, 2023 |
| Gigabyte      | EP45-UD3                    | Desktop     | [5d45f63468](https://linux-hardware.org/?probe=5d45f63468) | Apr 22, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | Notebook    | [4c60675864](https://linux-hardware.org/?probe=4c60675864) | Apr 22, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [7a873a7baa](https://linux-hardware.org/?probe=7a873a7baa) | Apr 22, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [3e4c8bce3b](https://linux-hardware.org/?probe=3e4c8bce3b) | Apr 22, 2023 |
| Dell          | 0CRH6C A00                  | Desktop     | [cbb78e1785](https://linux-hardware.org/?probe=cbb78e1785) | Apr 22, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [f64336848a](https://linux-hardware.org/?probe=f64336848a) | Apr 22, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [c9e17ad011](https://linux-hardware.org/?probe=c9e17ad011) | Apr 22, 2023 |
| MSI           | X399 SLI PLUS               | Desktop     | [ebb44ab29d](https://linux-hardware.org/?probe=ebb44ab29d) | Apr 22, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Compal        | HEL81I                      | Notebook    | [426788b00c](https://linux-hardware.org/?probe=426788b00c) | Apr 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [90e0cff0ad](https://linux-hardware.org/?probe=90e0cff0ad) | Apr 22, 2023 |
| Dell          | Precision 5510              | Notebook    | [94b5586a2c](https://linux-hardware.org/?probe=94b5586a2c) | Apr 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [0f5a55a8d1](https://linux-hardware.org/?probe=0f5a55a8d1) | Apr 22, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f23eeda727](https://linux-hardware.org/?probe=f23eeda727) | Apr 22, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [1ffb09ff2a](https://linux-hardware.org/?probe=1ffb09ff2a) | Apr 22, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [89b64bbfb6](https://linux-hardware.org/?probe=89b64bbfb6) | Apr 22, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [2a5d9adcd4](https://linux-hardware.org/?probe=2a5d9adcd4) | Apr 21, 2023 |
| MSI           | GS65 Stealth 8SE            | Notebook    | [f813e87465](https://linux-hardware.org/?probe=f813e87465) | Apr 21, 2023 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [868456ca5d](https://linux-hardware.org/?probe=868456ca5d) | Apr 21, 2023 |
| Medion        | MS-7621                     | Desktop     | [efb8293786](https://linux-hardware.org/?probe=efb8293786) | Apr 21, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [78adec215e](https://linux-hardware.org/?probe=78adec215e) | Apr 21, 2023 |
| MSI           | GS65 Stealth 8SE            | Notebook    | [53951da2d7](https://linux-hardware.org/?probe=53951da2d7) | Apr 21, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [c974888840](https://linux-hardware.org/?probe=c974888840) | Apr 21, 2023 |
| Intel         | D54250WYK H13922-305        | Desktop     | [a7ef0d6dad](https://linux-hardware.org/?probe=a7ef0d6dad) | Apr 21, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [acbe851404](https://linux-hardware.org/?probe=acbe851404) | Apr 21, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [fd91075868](https://linux-hardware.org/?probe=fd91075868) | Apr 21, 2023 |
| PC Special... | TN1-156M                    | Notebook    | [ef6b57e807](https://linux-hardware.org/?probe=ef6b57e807) | Apr 21, 2023 |
| HP            | Notebook                    | Notebook    | [150b1d6ae7](https://linux-hardware.org/?probe=150b1d6ae7) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [a0ee1dbeff](https://linux-hardware.org/?probe=a0ee1dbeff) | Apr 20, 2023 |
| ASUSTek       | K61IC                       | Notebook    | [985a269b26](https://linux-hardware.org/?probe=985a269b26) | Apr 20, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [9f81660d12](https://linux-hardware.org/?probe=9f81660d12) | Apr 20, 2023 |
| MSI           | CR61 3M                     | Notebook    | [0ee98cd841](https://linux-hardware.org/?probe=0ee98cd841) | Apr 20, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8c43353ee9](https://linux-hardware.org/?probe=8c43353ee9) | Apr 20, 2023 |
| Lenovo        | ThinkCentre M90p 3282B5G    | Desktop     | [9741f7bd1e](https://linux-hardware.org/?probe=9741f7bd1e) | Apr 20, 2023 |
| Acer          | TravelMate 5320             | Notebook    | [fa41e30258](https://linux-hardware.org/?probe=fa41e30258) | Apr 20, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [9af253f4e0](https://linux-hardware.org/?probe=9af253f4e0) | Apr 20, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [fd6d8a7cd7](https://linux-hardware.org/?probe=fd6d8a7cd7) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6ea882bacb](https://linux-hardware.org/?probe=6ea882bacb) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [8b560b455e](https://linux-hardware.org/?probe=8b560b455e) | Apr 19, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [fc12fc0a9d](https://linux-hardware.org/?probe=fc12fc0a9d) | Apr 19, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [64ea7a1e04](https://linux-hardware.org/?probe=64ea7a1e04) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1B30... | Notebook    | [c0207e5f9a](https://linux-hardware.org/?probe=c0207e5f9a) | Apr 19, 2023 |
| Intel         | D510MO AAE76523-401         | Desktop     | [cf5c07a318](https://linux-hardware.org/?probe=cf5c07a318) | Apr 19, 2023 |
| ZOTAC         | H67ITX-C-E 02/03/05         | Desktop     | [27131cb048](https://linux-hardware.org/?probe=27131cb048) | Apr 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [bac14fb22e](https://linux-hardware.org/?probe=bac14fb22e) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [270e47ceb8](https://linux-hardware.org/?probe=270e47ceb8) | Apr 19, 2023 |
| HP            | 1825                        | Desktop     | [5c637a9ef6](https://linux-hardware.org/?probe=5c637a9ef6) | Apr 18, 2023 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [65c0a28c58](https://linux-hardware.org/?probe=65c0a28c58) | Apr 18, 2023 |
| ASUSTek       | X751BP                      | Notebook    | [0bea82acba](https://linux-hardware.org/?probe=0bea82acba) | Apr 18, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [ec0532e3e3](https://linux-hardware.org/?probe=ec0532e3e3) | Apr 18, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| ASUSTek       | K55A                        | Notebook    | [99fe712761](https://linux-hardware.org/?probe=99fe712761) | Apr 17, 2023 |
| ASUSTek       | UX303LB                     | Notebook    | [48c19abe8c](https://linux-hardware.org/?probe=48c19abe8c) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [d12e0064fc](https://linux-hardware.org/?probe=d12e0064fc) | Apr 17, 2023 |
| HP            | Pavilion 17                 | Notebook    | [b06b49ac95](https://linux-hardware.org/?probe=b06b49ac95) | Apr 17, 2023 |
| Dell          | Precision 3571              | Notebook    | [d1fcff8b8f](https://linux-hardware.org/?probe=d1fcff8b8f) | Apr 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [f3a91915df](https://linux-hardware.org/?probe=f3a91915df) | Apr 17, 2023 |
| HP            | 18E7                        | Desktop     | [ef0b00cf80](https://linux-hardware.org/?probe=ef0b00cf80) | Apr 17, 2023 |
| ASUSTek       | P4C800-E                    | Desktop     | [4521f2b9b4](https://linux-hardware.org/?probe=4521f2b9b4) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d5db24c28d](https://linux-hardware.org/?probe=d5db24c28d) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [89eb2b2c32](https://linux-hardware.org/?probe=89eb2b2c32) | Apr 17, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4296a1241d](https://linux-hardware.org/?probe=4296a1241d) | Apr 17, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [64e06d7111](https://linux-hardware.org/?probe=64e06d7111) | Apr 17, 2023 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [ebd62c0513](https://linux-hardware.org/?probe=ebd62c0513) | Apr 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [7820a9b7bc](https://linux-hardware.org/?probe=7820a9b7bc) | Apr 16, 2023 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [c31465c0a1](https://linux-hardware.org/?probe=c31465c0a1) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [fec4fc20a6](https://linux-hardware.org/?probe=fec4fc20a6) | Apr 16, 2023 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [4ac44c74a3](https://linux-hardware.org/?probe=4ac44c74a3) | Apr 16, 2023 |
| eMachines     | E945GCU                     | Desktop     | [4e6aa4be24](https://linux-hardware.org/?probe=4e6aa4be24) | Apr 16, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [65b2e4afa9](https://linux-hardware.org/?probe=65b2e4afa9) | Apr 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f0353d1327](https://linux-hardware.org/?probe=f0353d1327) | Apr 16, 2023 |
| Dell          | 0TP412                      | Desktop     | [7491d6d66d](https://linux-hardware.org/?probe=7491d6d66d) | Apr 16, 2023 |
| ASUSTek       | K53BE                       | Notebook    | [f21e7219ce](https://linux-hardware.org/?probe=f21e7219ce) | Apr 16, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [af72ecc689](https://linux-hardware.org/?probe=af72ecc689) | Apr 16, 2023 |
| Dell          | 0TP412                      | Desktop     | [c5f0ba736e](https://linux-hardware.org/?probe=c5f0ba736e) | Apr 16, 2023 |
| Dell          | Vostro 15 7510              | Notebook    | [d9e766f446](https://linux-hardware.org/?probe=d9e766f446) | Apr 16, 2023 |
| MSI           | B150A GAMING PRO            | Desktop     | [26432a7622](https://linux-hardware.org/?probe=26432a7622) | Apr 16, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [da62023f35](https://linux-hardware.org/?probe=da62023f35) | Apr 15, 2023 |
| Dell          | Latitude E5520              | Notebook    | [5e04eeccae](https://linux-hardware.org/?probe=5e04eeccae) | Apr 15, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [f534984150](https://linux-hardware.org/?probe=f534984150) | Apr 15, 2023 |
| HP            | 83E2                        | Desktop     | [af01123687](https://linux-hardware.org/?probe=af01123687) | Apr 15, 2023 |
| HP            | 83E2                        | Desktop     | [f5052291a4](https://linux-hardware.org/?probe=f5052291a4) | Apr 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0e89a3c19b](https://linux-hardware.org/?probe=0e89a3c19b) | Apr 15, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [8de126d84d](https://linux-hardware.org/?probe=8de126d84d) | Apr 15, 2023 |
| ASUSTek       | X302LJ                      | Notebook    | [e045b269b1](https://linux-hardware.org/?probe=e045b269b1) | Apr 14, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [c3c64a7016](https://linux-hardware.org/?probe=c3c64a7016) | Apr 14, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [2b7836fd04](https://linux-hardware.org/?probe=2b7836fd04) | Apr 14, 2023 |
| HP            | 2B4B                        | Desktop     | [9103ce1fce](https://linux-hardware.org/?probe=9103ce1fce) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e5b11f4136](https://linux-hardware.org/?probe=e5b11f4136) | Apr 14, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [6fdb6931f0](https://linux-hardware.org/?probe=6fdb6931f0) | Apr 14, 2023 |
| Gigabyte      | P55-UD3R                    | Desktop     | [5e8538987d](https://linux-hardware.org/?probe=5e8538987d) | Apr 14, 2023 |
| HP            | ProBook 6570b               | Notebook    | [af45cce5b8](https://linux-hardware.org/?probe=af45cce5b8) | Apr 14, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [6cfca82c2f](https://linux-hardware.org/?probe=6cfca82c2f) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [df35f6916a](https://linux-hardware.org/?probe=df35f6916a) | Apr 14, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN         | Desktop     | [9ab9baf194](https://linux-hardware.org/?probe=9ab9baf194) | Apr 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [30d6d32fc1](https://linux-hardware.org/?probe=30d6d32fc1) | Apr 13, 2023 |
| sunxi         | LeMaker Banana Pi           | Soc         | [7a60bb63b4](https://linux-hardware.org/?probe=7a60bb63b4) | Apr 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [70e0ac9475](https://linux-hardware.org/?probe=70e0ac9475) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [b223f5fbf1](https://linux-hardware.org/?probe=b223f5fbf1) | Apr 13, 2023 |
| Dell          | G15 5510                    | Notebook    | [6b4ef54307](https://linux-hardware.org/?probe=6b4ef54307) | Apr 13, 2023 |
| ASRock        | H410M-HVS R2.0              | Desktop     | [7f388965d7](https://linux-hardware.org/?probe=7f388965d7) | Apr 13, 2023 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [4e09a1cd3e](https://linux-hardware.org/?probe=4e09a1cd3e) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [d79266b94f](https://linux-hardware.org/?probe=d79266b94f) | Apr 13, 2023 |
| Dell          | XPS L322X                   | Notebook    | [cbf247e5a6](https://linux-hardware.org/?probe=cbf247e5a6) | Apr 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [bcb170c5f0](https://linux-hardware.org/?probe=bcb170c5f0) | Apr 13, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [527e436d2b](https://linux-hardware.org/?probe=527e436d2b) | Apr 12, 2023 |
| HP            | Pavilion TS 15              | Notebook    | [43b322dcf3](https://linux-hardware.org/?probe=43b322dcf3) | Apr 12, 2023 |
| HP            | Pavilion dv6                | Notebook    | [09b80dd551](https://linux-hardware.org/?probe=09b80dd551) | Apr 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [4363479bf0](https://linux-hardware.org/?probe=4363479bf0) | Apr 12, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [d98390c8a7](https://linux-hardware.org/?probe=d98390c8a7) | Apr 12, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [0d8eb6aa86](https://linux-hardware.org/?probe=0d8eb6aa86) | Apr 12, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [796f3afe73](https://linux-hardware.org/?probe=796f3afe73) | Apr 12, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [6cbdeb350e](https://linux-hardware.org/?probe=6cbdeb350e) | Apr 12, 2023 |
| Dell          | Precision 3571              | Notebook    | [e6e8267b6a](https://linux-hardware.org/?probe=e6e8267b6a) | Apr 12, 2023 |
| Dell          | Latitude 5420               | Notebook    | [248e22982d](https://linux-hardware.org/?probe=248e22982d) | Apr 12, 2023 |
| Intel         | D33217GKE G76540-203        | Desktop     | [c07a4d67ca](https://linux-hardware.org/?probe=c07a4d67ca) | Apr 12, 2023 |
| Dell          | Precision 7520              | Notebook    | [1d23894711](https://linux-hardware.org/?probe=1d23894711) | Apr 12, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [9cd0292459](https://linux-hardware.org/?probe=9cd0292459) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [905a2aee02](https://linux-hardware.org/?probe=905a2aee02) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| MSI           | GP72MVR 7RFX                | Notebook    | [17f60a29f5](https://linux-hardware.org/?probe=17f60a29f5) | Apr 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [32bf664d90](https://linux-hardware.org/?probe=32bf664d90) | Apr 11, 2023 |
| HP            | 2AF7                        | Desktop     | [e9621d5a9c](https://linux-hardware.org/?probe=e9621d5a9c) | Apr 11, 2023 |
| HP            | 2AF7                        | Desktop     | [b187733415](https://linux-hardware.org/?probe=b187733415) | Apr 11, 2023 |
| HP            | 8298                        | Desktop     | [ccde341ebf](https://linux-hardware.org/?probe=ccde341ebf) | Apr 11, 2023 |
| HP            | 8298                        | Desktop     | [bab1bd2943](https://linux-hardware.org/?probe=bab1bd2943) | Apr 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f4190d2c4e](https://linux-hardware.org/?probe=f4190d2c4e) | Apr 11, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| ASRock        | B85M-HDS R2.0               | Desktop     | [24bdbac13a](https://linux-hardware.org/?probe=24bdbac13a) | Apr 11, 2023 |
| Gigabyte      | X7X7                        | Notebook    | [8f58573ff3](https://linux-hardware.org/?probe=8f58573ff3) | Apr 11, 2023 |
| MSI           | Prestige 14Evo B13M         | Notebook    | [a3967e84ad](https://linux-hardware.org/?probe=a3967e84ad) | Apr 11, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [eb294beef7](https://linux-hardware.org/?probe=eb294beef7) | Apr 11, 2023 |
| ASUSTek       | G751JY                      | Notebook    | [618a195c21](https://linux-hardware.org/?probe=618a195c21) | Apr 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [c31f7b3b5c](https://linux-hardware.org/?probe=c31f7b3b5c) | Apr 10, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [35f953cfe0](https://linux-hardware.org/?probe=35f953cfe0) | Apr 10, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [ab53417291](https://linux-hardware.org/?probe=ab53417291) | Apr 10, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [979e7ab8f3](https://linux-hardware.org/?probe=979e7ab8f3) | Apr 10, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [bf18b5af69](https://linux-hardware.org/?probe=bf18b5af69) | Apr 10, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [704f5bcf78](https://linux-hardware.org/?probe=704f5bcf78) | Apr 10, 2023 |
| Sony          | VPCEB1M1E                   | Notebook    | [c182925286](https://linux-hardware.org/?probe=c182925286) | Apr 09, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [2b039ea053](https://linux-hardware.org/?probe=2b039ea053) | Apr 09, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [fe939f268b](https://linux-hardware.org/?probe=fe939f268b) | Apr 09, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [709cc4af2c](https://linux-hardware.org/?probe=709cc4af2c) | Apr 09, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [955a648772](https://linux-hardware.org/?probe=955a648772) | Apr 09, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [bb9f88795d](https://linux-hardware.org/?probe=bb9f88795d) | Apr 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [0f364f6e82](https://linux-hardware.org/?probe=0f364f6e82) | Apr 09, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [7806838777](https://linux-hardware.org/?probe=7806838777) | Apr 09, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [ee2678d76f](https://linux-hardware.org/?probe=ee2678d76f) | Apr 09, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [803ac095e7](https://linux-hardware.org/?probe=803ac095e7) | Apr 08, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [bff5545041](https://linux-hardware.org/?probe=bff5545041) | Apr 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [12faf271f6](https://linux-hardware.org/?probe=12faf271f6) | Apr 08, 2023 |
| ASUSTek       | X751LN                      | Notebook    | [8bf4f37814](https://linux-hardware.org/?probe=8bf4f37814) | Apr 08, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d01569c067](https://linux-hardware.org/?probe=d01569c067) | Apr 08, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | Desktop     | [9cd5518f53](https://linux-hardware.org/?probe=9cd5518f53) | Apr 08, 2023 |
| HP            | ENVY dv6                    | Notebook    | [0d89a1797e](https://linux-hardware.org/?probe=0d89a1797e) | Apr 08, 2023 |
| MSI           | B85-G43                     | Desktop     | [49c7de9ea6](https://linux-hardware.org/?probe=49c7de9ea6) | Apr 08, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [fc2425ffde](https://linux-hardware.org/?probe=fc2425ffde) | Apr 08, 2023 |
| ASRock        | X79 Extreme6                | Desktop     | [2b3f00ac79](https://linux-hardware.org/?probe=2b3f00ac79) | Apr 08, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [185c4824b7](https://linux-hardware.org/?probe=185c4824b7) | Apr 07, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [c7444ac7f0](https://linux-hardware.org/?probe=c7444ac7f0) | Apr 07, 2023 |
| Dell          | G3 3500                     | Notebook    | [cae0e09f03](https://linux-hardware.org/?probe=cae0e09f03) | Apr 07, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [fc1b119dca](https://linux-hardware.org/?probe=fc1b119dca) | Apr 07, 2023 |
| Dell          | G3 3500                     | Notebook    | [9f77f9158a](https://linux-hardware.org/?probe=9f77f9158a) | Apr 07, 2023 |
| Lenovo        | Aptio CRB NOK               | Mini pc     | [e4d5290d7b](https://linux-hardware.org/?probe=e4d5290d7b) | Apr 07, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [cb0b33006e](https://linux-hardware.org/?probe=cb0b33006e) | Apr 07, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [2c731aefae](https://linux-hardware.org/?probe=2c731aefae) | Apr 07, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [64b9978ed0](https://linux-hardware.org/?probe=64b9978ed0) | Apr 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [d5c75a0967](https://linux-hardware.org/?probe=d5c75a0967) | Apr 06, 2023 |
| QTQD          | Unknown                     | Desktop     | [5cb163c75a](https://linux-hardware.org/?probe=5cb163c75a) | Apr 06, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [e2dd28ca36](https://linux-hardware.org/?probe=e2dd28ca36) | Apr 06, 2023 |
| MSI           | GL73 8RC                    | Notebook    | [c134ae92fc](https://linux-hardware.org/?probe=c134ae92fc) | Apr 06, 2023 |
| HP            | Sona                        | Notebook    | [64fa63647b](https://linux-hardware.org/?probe=64fa63647b) | Apr 06, 2023 |
| Dell          | Precision 7560              | Notebook    | [b474fb4429](https://linux-hardware.org/?probe=b474fb4429) | Apr 06, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [bab2c0f0e4](https://linux-hardware.org/?probe=bab2c0f0e4) | Apr 06, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [0e0a176bf8](https://linux-hardware.org/?probe=0e0a176bf8) | Apr 06, 2023 |
| Dell          | Latitude E7470              | Notebook    | [64721a0d8a](https://linux-hardware.org/?probe=64721a0d8a) | Apr 05, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [4d639304bf](https://linux-hardware.org/?probe=4d639304bf) | Apr 05, 2023 |
| HP            | 84FD                        | Desktop     | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [eb35e0beff](https://linux-hardware.org/?probe=eb35e0beff) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| eMachines     | eMachiens G443              | Notebook    | [58c297218a](https://linux-hardware.org/?probe=58c297218a) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [d89431372f](https://linux-hardware.org/?probe=d89431372f) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [5d0489d439](https://linux-hardware.org/?probe=5d0489d439) | Apr 05, 2023 |
| Toshiba       | Satellite C855D-12J         | Notebook    | [cb3dedf5e8](https://linux-hardware.org/?probe=cb3dedf5e8) | Apr 05, 2023 |
| HP            | Notebook                    | Notebook    | [99a9d4cae5](https://linux-hardware.org/?probe=99a9d4cae5) | Apr 05, 2023 |
| System76      | Lemur Pro                   | Notebook    | [2232424d5a](https://linux-hardware.org/?probe=2232424d5a) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f98b9efce7](https://linux-hardware.org/?probe=f98b9efce7) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| ASUSTek       | X71Q                        | Notebook    | [9a7d0f4b2b](https://linux-hardware.org/?probe=9a7d0f4b2b) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [dad967cc87](https://linux-hardware.org/?probe=dad967cc87) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [0f75295895](https://linux-hardware.org/?probe=0f75295895) | Apr 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [2d32794500](https://linux-hardware.org/?probe=2d32794500) | Apr 05, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [9ea45909a2](https://linux-hardware.org/?probe=9ea45909a2) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [f04b34af52](https://linux-hardware.org/?probe=f04b34af52) | Apr 04, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [fa9fe4337a](https://linux-hardware.org/?probe=fa9fe4337a) | Apr 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [9ef9150c8c](https://linux-hardware.org/?probe=9ef9150c8c) | Apr 04, 2023 |
| MSI           | PS42 Modern 8MO             | Notebook    | [60633671a2](https://linux-hardware.org/?probe=60633671a2) | Apr 04, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [b75b9b9fa2](https://linux-hardware.org/?probe=b75b9b9fa2) | Apr 04, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [b5106f816a](https://linux-hardware.org/?probe=b5106f816a) | Apr 04, 2023 |
| MSI           | H110M ECO                   | Desktop     | [983153c81e](https://linux-hardware.org/?probe=983153c81e) | Apr 04, 2023 |
| ASRock        | A320M-DVS R3.0              | Desktop     | [518d9bcac3](https://linux-hardware.org/?probe=518d9bcac3) | Apr 04, 2023 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | Notebook    | [ceeafa59a2](https://linux-hardware.org/?probe=ceeafa59a2) | Apr 04, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [a1dceb9ce7](https://linux-hardware.org/?probe=a1dceb9ce7) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ec6a09a6ba](https://linux-hardware.org/?probe=ec6a09a6ba) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | Notebook    | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [1dbae9d685](https://linux-hardware.org/?probe=1dbae9d685) | Apr 04, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [1158a2ec97](https://linux-hardware.org/?probe=1158a2ec97) | Apr 04, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [84f877fde3](https://linux-hardware.org/?probe=84f877fde3) | Apr 04, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [86de0a83c3](https://linux-hardware.org/?probe=86de0a83c3) | Apr 04, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [bbb597effc](https://linux-hardware.org/?probe=bbb597effc) | Apr 04, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [1978d77ba2](https://linux-hardware.org/?probe=1978d77ba2) | Apr 03, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [e6b864d24e](https://linux-hardware.org/?probe=e6b864d24e) | Apr 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [248ef68079](https://linux-hardware.org/?probe=248ef68079) | Apr 03, 2023 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [757ae6aa73](https://linux-hardware.org/?probe=757ae6aa73) | Apr 03, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [7c446415d8](https://linux-hardware.org/?probe=7c446415d8) | Apr 03, 2023 |
| Dell          | 07N90W A02                  | Desktop     | [fd992821e0](https://linux-hardware.org/?probe=fd992821e0) | Apr 03, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [ef04e5d464](https://linux-hardware.org/?probe=ef04e5d464) | Apr 03, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [f9eb684250](https://linux-hardware.org/?probe=f9eb684250) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [661283d296](https://linux-hardware.org/?probe=661283d296) | Apr 03, 2023 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [ecd1f451f0](https://linux-hardware.org/?probe=ecd1f451f0) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [3c10c8c51a](https://linux-hardware.org/?probe=3c10c8c51a) | Apr 03, 2023 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [49b1cef736](https://linux-hardware.org/?probe=49b1cef736) | Apr 03, 2023 |
| HP            | Pavilion 17                 | Notebook    | [487bc77c07](https://linux-hardware.org/?probe=487bc77c07) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [1c15668c5d](https://linux-hardware.org/?probe=1c15668c5d) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | Notebook    | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| ASRock        | G31M-S                      | Desktop     | [70f35c82f1](https://linux-hardware.org/?probe=70f35c82f1) | Apr 03, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [ed4e86ebbb](https://linux-hardware.org/?probe=ed4e86ebbb) | Apr 03, 2023 |
| HP            | 1905                        | Desktop     | [2044e303ea](https://linux-hardware.org/?probe=2044e303ea) | Apr 02, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [ada2cb6e08](https://linux-hardware.org/?probe=ada2cb6e08) | Apr 02, 2023 |
| ASUSTek       | ZenBook UX463FL_UX463FL     | Convertible | [595b975199](https://linux-hardware.org/?probe=595b975199) | Apr 02, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a761c8f978](https://linux-hardware.org/?probe=a761c8f978) | Apr 02, 2023 |
| MSI           | A88XM-E35                   | Desktop     | [fb40e13d92](https://linux-hardware.org/?probe=fb40e13d92) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [e382f0f4f1](https://linux-hardware.org/?probe=e382f0f4f1) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [37beaa5cbb](https://linux-hardware.org/?probe=37beaa5cbb) | Apr 02, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [d56ea84c5f](https://linux-hardware.org/?probe=d56ea84c5f) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [892ffd1727](https://linux-hardware.org/?probe=892ffd1727) | Apr 02, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [6399f19b22](https://linux-hardware.org/?probe=6399f19b22) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ba6e80b2b7](https://linux-hardware.org/?probe=ba6e80b2b7) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | Desktop     | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| Notebook      | P15SM                       | Notebook    | [070f808c28](https://linux-hardware.org/?probe=070f808c28) | Apr 02, 2023 |
| ASUSTek       | G71V                        | Notebook    | [6594dac071](https://linux-hardware.org/?probe=6594dac071) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [195ab3d907](https://linux-hardware.org/?probe=195ab3d907) | Apr 02, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [e1c055e8dc](https://linux-hardware.org/?probe=e1c055e8dc) | Apr 02, 2023 |
| Acer          | Veriton X2632G V:1.0        | Desktop     | [f5eafafc96](https://linux-hardware.org/?probe=f5eafafc96) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [e97e71fc7a](https://linux-hardware.org/?probe=e97e71fc7a) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [0941828bd0](https://linux-hardware.org/?probe=0941828bd0) | Apr 01, 2023 |
| Lenovo        | ThinkPad 10 20C3S0Q200      | Tablet      | [e014609915](https://linux-hardware.org/?probe=e014609915) | Apr 01, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [f96e01d74d](https://linux-hardware.org/?probe=f96e01d74d) | Apr 01, 2023 |
| Dell          | 040DDP A00                  | Desktop     | [0771f1547e](https://linux-hardware.org/?probe=0771f1547e) | Apr 01, 2023 |
| Acer          | RS880M05                    | Desktop     | [bddd902030](https://linux-hardware.org/?probe=bddd902030) | Apr 01, 2023 |
| Acer          | Aspire X3400                | Desktop     | [093b0a0239](https://linux-hardware.org/?probe=093b0a0239) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [95c5f574c9](https://linux-hardware.org/?probe=95c5f574c9) | Apr 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [79ef948789](https://linux-hardware.org/?probe=79ef948789) | Apr 01, 2023 |
| Lenovo        | ThinkPad L560 20F2S1AJ00    | Notebook    | [8987605dde](https://linux-hardware.org/?probe=8987605dde) | Apr 01, 2023 |
| Lenovo        | ThinkPad 10 20C3S0Q200      | Tablet      | [9ee9bc67cf](https://linux-hardware.org/?probe=9ee9bc67cf) | Apr 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [f9083bca8d](https://linux-hardware.org/?probe=f9083bca8d) | Apr 01, 2023 |
| Google        | Lulu                        | Notebook    | [0183eadbc8](https://linux-hardware.org/?probe=0183eadbc8) | Apr 01, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| ASUSTek       | N752VX                      | Notebook    | [d426499408](https://linux-hardware.org/?probe=d426499408) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [35bae3b94d](https://linux-hardware.org/?probe=35bae3b94d) | Apr 01, 2023 |
| HP            | Presario CQ58               | Notebook    | [e8f8f289ac](https://linux-hardware.org/?probe=e8f8f289ac) | Apr 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [87bc2601f3](https://linux-hardware.org/?probe=87bc2601f3) | Apr 01, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [f8afb163dc](https://linux-hardware.org/?probe=f8afb163dc) | Apr 01, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [916adbdf9f](https://linux-hardware.org/?probe=916adbdf9f) | Apr 01, 2023 |
| MSI           | H97M-G43                    | Desktop     | [b93caf26e4](https://linux-hardware.org/?probe=b93caf26e4) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [3599b8e875](https://linux-hardware.org/?probe=3599b8e875) | Mar 31, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1755      | 17.71%  |
| Ubuntu 22.04       | 658       | 6.64%   |
| Ubuntu 18.04       | 556       | 5.61%   |
| Debian 11          | 408       | 4.12%   |
| OpenMandriva 4.2   | 368       | 3.71%   |
| OpenMandriva 4.3   | 304       | 3.07%   |
| Xubuntu 20.04      | 197       | 1.99%   |
| Linux Mint 20.3    | 195       | 1.97%   |
| Arch Rolling       | 167       | 1.69%   |
| OpenMandriva 23.01 | 153       | 1.54%   |
| Debian 10          | 135       | 1.36%   |
| Linux Mint 21.1    | 126       | 1.27%   |
| Arch               | 124       | 1.25%   |
| Ubuntu 21.10       | 122       | 1.23%   |
| Ubuntu 20.10       | 109       | 1.1%    |
| Linux Mint 20.2    | 108       | 1.09%   |
| Ubuntu 21.04       | 106       | 1.07%   |
| Linux Mint 20.1    | 106       | 1.07%   |
| Zorin 16           | 102       | 1.03%   |
| Manjaro            | 95        | 0.96%   |
| OpenMandriva 23.03 | 89        | 0.9%    |
| Linux Mint 19.3    | 89        | 0.9%    |
| Fedora 33          | 89        | 0.9%    |
| Ubuntu 19.10       | 85        | 0.86%   |
| Kubuntu 20.04      | 83        | 0.84%   |
| Linux Mint 21      | 80        | 0.81%   |
| Xubuntu 18.04      | 78        | 0.79%   |
| Linux Mint 20      | 78        | 0.79%   |
| Ubuntu 22.10       | 77        | 0.78%   |
| Fedora 34          | 75        | 0.76%   |
| Pop!_OS 22.04      | 74        | 0.75%   |
| Ubuntu 19.04       | 71        | 0.72%   |
| KDE neon 20.04     | 71        | 0.72%   |
| Fedora 35          | 71        | 0.72%   |
| Fedora 32          | 69        | 0.7%    |
| Fedora 37          | 68        | 0.69%   |
| Fedora 36          | 66        | 0.67%   |
| Ubuntu MATE 20.04  | 65        | 0.66%   |
| Xubuntu 22.04      | 61        | 0.62%   |
| Lubuntu 20.04      | 61        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3486      | 37.2%   |
| OpenMandriva  | 966       | 10.31%  |
| Linux Mint    | 789       | 8.42%   |
| Debian        | 672       | 7.17%   |
| Fedora        | 447       | 4.77%   |
| Xubuntu       | 375       | 4%      |
| Arch          | 285       | 3.04%   |
| Manjaro       | 250       | 2.67%   |
| Pop!_OS       | 235       | 2.51%   |
| Kubuntu       | 220       | 2.35%   |
| ROSA          | 175       | 1.87%   |
| Zorin         | 148       | 1.58%   |
| Ubuntu MATE   | 133       | 1.42%   |
| Lubuntu       | 114       | 1.22%   |
| KDE neon      | 101       | 1.08%   |
| openSUSE      | 74        | 0.79%   |
| Ubuntu Unity  | 72        | 0.77%   |
| Gentoo        | 67        | 0.71%   |
| Kali          | 58        | 0.62%   |
| ArcoLinux     | 57        | 0.61%   |
| Endless       | 52        | 0.55%   |
| Elementary    | 49        | 0.52%   |
| Ubuntu Budgie | 46        | 0.49%   |
| EndeavourOS   | 39        | 0.42%   |
| LMDE          | 37        | 0.39%   |
| BlackPanther  | 35        | 0.37%   |
| SteamOS       | 29        | 0.31%   |
| CentOS        | 29        | 0.31%   |
| Ubuntu Studio | 22        | 0.23%   |
| Mageia        | 22        | 0.23%   |
| Parrot        | 21        | 0.22%   |
| Clear Linux   | 19        | 0.2%    |
| MX            | 18        | 0.19%   |
| Raspbian      | 13        | 0.14%   |
| Devuan        | 13        | 0.14%   |
| Nobara        | 12        | 0.13%   |
| Kaisen        | 12        | 0.13%   |
| NixOS         | 11        | 0.12%   |
| Artix         | 11        | 0.12%   |
| Manjaro-ARM   | 10        | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 351       | 3.24%   |
| 5.16.7-desktop-1omv4003  | 278       | 2.57%   |
| 6.1.1-desktop-1omv2290   | 135       | 1.25%   |
| 5.15.0-56-generic        | 129       | 1.19%   |
| 5.4.0-42-generic         | 128       | 1.18%   |
| 5.4.0-58-generic         | 99        | 0.91%   |
| 5.15.0-58-generic        | 99        | 0.91%   |
| 5.15.0-52-generic        | 94        | 0.87%   |
| 5.4.0-52-generic         | 81        | 0.75%   |
| 6.2.6-desktop-1omv2390   | 79        | 0.73%   |
| 5.11.0-27-generic        | 78        | 0.72%   |
| 5.11.0-38-generic        | 77        | 0.71%   |
| 5.15.0-48-generic        | 74        | 0.68%   |
| 5.4.0-26-generic         | 73        | 0.67%   |
| 5.8.0-43-generic         | 69        | 0.64%   |
| 5.4.0-48-generic         | 69        | 0.64%   |
| 5.15.0-46-generic        | 66        | 0.61%   |
| 5.11.0-37-generic        | 66        | 0.61%   |
| 5.4.0-65-generic         | 65        | 0.6%    |
| 5.8.0-50-generic         | 63        | 0.58%   |
| 5.15.0-43-generic        | 61        | 0.56%   |
| 5.19.0-38-generic        | 60        | 0.55%   |
| 5.19.0-35-generic        | 58        | 0.54%   |
| 5.11.0-40-generic        | 57        | 0.53%   |
| 5.4.0-91-generic         | 55        | 0.51%   |
| 5.4.0-29-generic         | 55        | 0.51%   |
| 5.15.0-47-generic        | 55        | 0.51%   |
| 5.13.0-28-generic        | 55        | 0.51%   |
| 5.8.0-44-generic         | 54        | 0.5%    |
| 5.4.0-54-generic         | 54        | 0.5%    |
| 5.8.0-48-generic         | 53        | 0.49%   |
| 5.4.0-37-generic         | 53        | 0.49%   |
| 5.13.0-39-generic        | 52        | 0.48%   |
| 5.15.0-60-generic        | 51        | 0.47%   |
| 5.11.0-43-generic        | 51        | 0.47%   |
| 5.15.0-53-generic        | 49        | 0.45%   |
| 5.4.0-81-generic         | 48        | 0.44%   |
| 5.11.0-34-generic        | 48        | 0.44%   |
| 5.19.0-41-generic        | 47        | 0.43%   |
| 5.8.0-59-generic         | 46        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1788      | 17.54%  |
| 5.15.0  | 1074      | 10.54%  |
| 5.11.0  | 635       | 6.23%   |
| 5.8.0   | 612       | 6.01%   |
| 5.13.0  | 522       | 5.12%   |
| 4.15.0  | 440       | 4.32%   |
| 5.10.0  | 422       | 4.14%   |
| 5.19.0  | 382       | 3.75%   |
| 5.10.14 | 354       | 3.47%   |
| 5.3.0   | 288       | 2.83%   |
| 5.16.7  | 280       | 2.75%   |
| 5.0.0   | 164       | 1.61%   |
| 6.1.1   | 149       | 1.46%   |
| 4.18.0  | 137       | 1.34%   |
| 4.19.0  | 129       | 1.27%   |
| 6.2.6   | 96        | 0.94%   |
| 6.1.0   | 50        | 0.49%   |
| 5.14.0  | 47        | 0.46%   |
| 6.2.0   | 44        | 0.43%   |
| 6.0.0   | 40        | 0.39%   |
| 4.9.20  | 35        | 0.34%   |
| 5.18.0  | 34        | 0.33%   |
| 5.11.12 | 34        | 0.33%   |
| 5.16.13 | 33        | 0.32%   |
| 5.18.12 | 32        | 0.31%   |
| 4.18.16 | 32        | 0.31%   |
| 5.17.5  | 31        | 0.3%    |
| 4.4.0   | 29        | 0.28%   |
| 5.16.0  | 28        | 0.27%   |
| 5.9.0   | 25        | 0.25%   |
| 5.19.12 | 23        | 0.23%   |
| 5.12.4  | 23        | 0.23%   |
| 4.9.60  | 23        | 0.23%   |
| 5.13.19 | 19        | 0.19%   |
| 6.0.12  | 18        | 0.18%   |
| 5.9.16  | 18        | 0.18%   |
| 5.9.11  | 18        | 0.18%   |
| 5.7.0   | 18        | 0.18%   |
| 5.6.0   | 18        | 0.18%   |
| 5.17.0  | 18        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1883      | 18.72%  |
| 5.15    | 1285      | 12.77%  |
| 5.10    | 921       | 9.16%   |
| 5.11    | 730       | 7.26%   |
| 5.8     | 701       | 6.97%   |
| 5.13    | 605       | 6.01%   |
| 5.19    | 477       | 4.74%   |
| 4.15    | 441       | 4.38%   |
| 5.16    | 411       | 4.09%   |
| 5.3     | 330       | 3.28%   |
| 6.1     | 313       | 3.11%   |
| 6.2     | 240       | 2.39%   |
| 5.0     | 177       | 1.76%   |
| 4.18    | 172       | 1.71%   |
| 4.19    | 146       | 1.45%   |
| 6.0     | 141       | 1.4%    |
| 5.14    | 136       | 1.35%   |
| 5.18    | 132       | 1.31%   |
| 4.9     | 120       | 1.19%   |
| 5.9     | 119       | 1.18%   |
| 5.17    | 108       | 1.07%   |
| 5.6     | 82        | 0.82%   |
| 5.7     | 73        | 0.73%   |
| 5.12    | 70        | 0.7%    |
| 6.3     | 62        | 0.62%   |
| 5.5     | 39        | 0.39%   |
| 4.4     | 34        | 0.34%   |
| 4.1     | 24        | 0.24%   |
| 3.10    | 15        | 0.15%   |
| 5.2     | 13        | 0.13%   |
| 4.14    | 12        | 0.12%   |
| 4.12    | 9         | 0.09%   |
| 4.20    | 7         | 0.07%   |
| 4.13    | 7         | 0.07%   |
| 5.1     | 6         | 0.06%   |
| 4.10    | 4         | 0.04%   |
| 4.8     | 3         | 0.03%   |
| 6.4     | 2         | 0.02%   |
| 4.17    | 2         | 0.02%   |
| 3.4     | 2         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 8801      | 96.75%  |
| i686    | 220       | 2.42%   |
| aarch64 | 48        | 0.53%   |
| armv7l  | 21        | 0.23%   |
| armv6l  | 4         | 0.04%   |
| armv8l  | 2         | 0.02%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 4170      | 44.14%  |
| KDE5              | 1689      | 17.88%  |
| Unknown           | 919       | 9.73%   |
| XFCE              | 829       | 8.78%   |
| X-Cinnamon        | 567       | 6%      |
| MATE              | 364       | 3.85%   |
| Cinnamon          | 134       | 1.42%   |
| LXQt              | 133       | 1.41%   |
| KDE               | 118       | 1.25%   |
| KDE4              | 115       | 1.22%   |
| Unity             | 73        | 0.77%   |
| i3                | 72        | 0.76%   |
| Budgie            | 56        | 0.59%   |
| Pantheon          | 52        | 0.55%   |
| LXDE              | 44        | 0.47%   |
| GNOME Flashback   | 29        | 0.31%   |
| GNOME Classic     | 13        | 0.14%   |
| Deepin            | 12        | 0.13%   |
| sway              | 10        | 0.11%   |
| awesome           | 7         | 0.07%   |
| qtile             | 5         | 0.05%   |
| bspwm             | 5         | 0.05%   |
| trinity           | 3         | 0.03%   |
| lightdm-xsession  | 3         | 0.03%   |
| icewm             | 3         | 0.03%   |
| i3-with-shmlog    | 3         | 0.03%   |
| Openbox           | 2         | 0.02%   |
| Hyprland          | 2         | 0.02%   |
| GNUstep           | 2         | 0.02%   |
| Enlightenment     | 2         | 0.02%   |
| Yaru:ubuntu:GNOME | 1         | 0.01%   |
| xmonad            | 1         | 0.01%   |
| wmaker-common     | 1         | 0.01%   |
| ubuntu:pika:GNOME | 1         | 0.01%   |
| Lubuntu           | 1         | 0.01%   |
| LeftWM            | 1         | 0.01%   |
| INPT              | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |
| dwm-sc            | 1         | 0.01%   |
| DWM               | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 7224      | 77.21%  |
| Wayland | 1400      | 14.96%  |
| Unknown | 441       | 4.71%   |
| Tty     | 290       | 3.1%    |
| Xcb     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3501      | 37%     |
| SDDM    | 1670      | 17.65%  |
| GDM     | 1581      | 16.71%  |
| GDM3    | 1117      | 11.81%  |
| LightDM | 1104      | 11.67%  |
| TDM     | 334       | 3.53%   |
| KDM     | 111       | 1.17%   |
| SLiM    | 12        | 0.13%   |
| XDM     | 11        | 0.12%   |
| Ly      | 8         | 0.08%   |
| LXDM    | 5         | 0.05%   |
| NODM    | 3         | 0.03%   |
| GREETD  | 2         | 0.02%   |
| WDM     | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| fr_FR       | 6466      | 69.71%  |
| en_US       | 1566      | 16.88%  |
| Unknown     | 755       | 8.14%   |
| en_GB       | 152       | 1.64%   |
| C           | 105       | 1.13%   |
| de_DE       | 28        | 0.3%    |
| ru_RU       | 23        | 0.25%   |
| it_IT       | 15        | 0.16%   |
| es_ES       | 15        | 0.16%   |
| nl_NL       | 12        | 0.13%   |
| fr_CH       | 12        | 0.13%   |
| pl_PL       | 10        | 0.11%   |
| fr_CA       | 10        | 0.11%   |
| en_IE       | 10        | 0.11%   |
| pt_PT       | 8         | 0.09%   |
| fr_BE       | 7         | 0.08%   |
| POSIX       | 6         | 0.06%   |
| C.UTF8      | 5         | 0.05%   |
| sv_SE       | 4         | 0.04%   |
| ru_UA       | 4         | 0.04%   |
| en_IN       | 4         | 0.04%   |
| en_DK       | 4         | 0.04%   |
| en_AU       | 4         | 0.04%   |
| pt_BR       | 3         | 0.03%   |
| fr_FR.UTF8  | 3         | 0.03%   |
| en_AG       | 3         | 0.03%   |
| ro_RO       | 2         | 0.02%   |
| nb_NO       | 2         | 0.02%   |
| hu_HU       | 2         | 0.02%   |
| fr_LU       | 2         | 0.02%   |
| fr_FR.utf-8 | 2         | 0.02%   |
| en_CA       | 2         | 0.02%   |
| cs_CZ       | 2         | 0.02%   |
| zh_CN       | 1         | 0.01%   |
| UTF-8       | 1         | 0.01%   |
| tr_TR       | 1         | 0.01%   |
| sr_RS@latin | 1         | 0.01%   |
| sr_RS       | 1         | 0.01%   |
| sk_SK       | 1         | 0.01%   |
| oc_FR       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4826      | 52.02%  |
| BIOS | 4451      | 47.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 7377      | 79.24%  |
| Overlay  | 863       | 9.27%   |
| Btrfs    | 575       | 6.18%   |
| Unknown  | 222       | 2.38%   |
| Xfs      | 97        | 1.04%   |
| Tmpfs    | 70        | 0.75%   |
| Zfs      | 55        | 0.59%   |
| Ext2     | 16        | 0.17%   |
| F2fs     | 15        | 0.16%   |
| Ext3     | 14        | 0.15%   |
| Reiserfs | 3         | 0.03%   |
| Rootfs   | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |
| Aufs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4186      | 44.86%  |
| Unknown | 3682      | 39.46%  |
| MBR     | 1464      | 15.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7548      | 81.38%  |
| Yes       | 1727      | 18.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6252      | 67.57%  |
| Yes       | 3001      | 32.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1821      | 20.03%  |
| Dell                    | 1316      | 14.47%  |
| Hewlett-Packard         | 1171      | 12.88%  |
| Lenovo                  | 1019      | 11.21%  |
| MSI                     | 762       | 8.38%   |
| Gigabyte Technology     | 532       | 5.85%   |
| Acer                    | 460       | 5.06%   |
| ASRock                  | 221       | 2.43%   |
| Toshiba                 | 170       | 1.87%   |
| Apple                   | 159       | 1.75%   |
| Intel                   | 130       | 1.43%   |
| Packard Bell            | 102       | 1.12%   |
| Notebook                | 88        | 0.97%   |
| HUAWEI                  | 81        | 0.89%   |
| Unknown                 | 71        | 0.78%   |
| Samsung Electronics     | 69        | 0.76%   |
| Sony                    | 66        | 0.73%   |
| Foxconn                 | 51        | 0.56%   |
| Pegatron                | 44        | 0.48%   |
| Fujitsu                 | 43        | 0.47%   |
| Raspberry Pi Foundation | 42        | 0.46%   |
| eMachines               | 38        | 0.42%   |
| Medion                  | 33        | 0.36%   |
| TUXEDO                  | 29        | 0.32%   |
| Valve                   | 26        | 0.29%   |
| Supermicro              | 26        | 0.29%   |
| Timi                    | 25        | 0.27%   |
| Alienware               | 25        | 0.27%   |
| Microsoft               | 23        | 0.25%   |
| AZW                     | 23        | 0.25%   |
| UNOWHY                  | 22        | 0.24%   |
| Fujitsu Siemens         | 22        | 0.24%   |
| Thomson                 | 21        | 0.23%   |
| Clevo                   | 20        | 0.22%   |
| Shuttle                 | 18        | 0.2%    |
| PC Specialist           | 15        | 0.16%   |
| Chuwi                   | 15        | 0.16%   |
| Google                  | 14        | 0.15%   |
| ECS                     | 14        | 0.15%   |
| BESSTAR Tech            | 14        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| ASUS All Series           | 124       | 1.36%   |
| Unknown                   | 93        | 1.02%   |
| HP Notebook               | 40        | 0.44%   |
| HP Pavilion 17            | 29        | 0.32%   |
| Gigabyte B450M DS3H       | 29        | 0.32%   |
| HP Pavilion dv6           | 28        | 0.31%   |
| Valve Jupiter             | 26        | 0.29%   |
| HP Pavilion dv7           | 25        | 0.27%   |
| ASUS S551LN               | 22        | 0.24%   |
| Dell OptiPlex 390         | 21        | 0.23%   |
| Dell OptiPlex 7010        | 20        | 0.22%   |
| Dell OptiPlex 9020        | 19        | 0.21%   |
| HP Pavilion g7            | 18        | 0.2%    |
| Dell XPS 13 9310          | 18        | 0.2%    |
| ASUS PRIME A320M-K        | 18        | 0.2%    |
| MSI MS-7816               | 17        | 0.19%   |
| MSI MS-7C91               | 16        | 0.18%   |
| MSI MS-7C02               | 15        | 0.16%   |
| HP Pavilion Notebook      | 15        | 0.16%   |
| Dell XPS 13 9380          | 15        | 0.16%   |
| Dell XPS 13 7390          | 15        | 0.16%   |
| Dell Latitude E6420       | 15        | 0.16%   |
| MSI MS-7C37               | 14        | 0.15%   |
| MSI MS-7817               | 14        | 0.15%   |
| HUAWEI HVY-WXX9           | 14        | 0.15%   |
| HP EliteBook 840 G3       | 14        | 0.15%   |
| Dell XPS 15 9570          | 14        | 0.15%   |
| Dell OptiPlex 3020        | 14        | 0.15%   |
| MSI MS-7758               | 13        | 0.14%   |
| HP Pavilion g6            | 13        | 0.14%   |
| HP EliteBook 840 G2       | 13        | 0.14%   |
| HP Compaq Elite 8300 SFF  | 13        | 0.14%   |
| Gigabyte B450 AORUS ELITE | 13        | 0.14%   |
| Gigabyte 970A-DS3P        | 13        | 0.14%   |
| Dell XPS 15 7590          | 13        | 0.14%   |
| Dell Latitude 5420        | 13        | 0.14%   |
| MSI MS-7A38               | 12        | 0.13%   |
| MSI MS-7693               | 12        | 0.13%   |
| HP Pavilion 15            | 12        | 0.13%   |
| Dell XPS 15 9500          | 12        | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 494       | 5.43%   |
| Dell Latitude         | 366       | 4.03%   |
| Acer Aspire           | 306       | 3.37%   |
| HP Pavilion           | 247       | 2.72%   |
| Dell Precision        | 245       | 2.69%   |
| Dell OptiPlex         | 190       | 2.09%   |
| Dell XPS              | 185       | 2.03%   |
| HP EliteBook          | 177       | 1.95%   |
| Dell Inspiron         | 174       | 1.91%   |
| Lenovo IdeaPad        | 165       | 1.81%   |
| ASUS PRIME            | 154       | 1.69%   |
| Toshiba Satellite     | 140       | 1.54%   |
| HP ProBook            | 131       | 1.44%   |
| ASUS VivoBook         | 128       | 1.41%   |
| ASUS All              | 124       | 1.36%   |
| HP Compaq             | 122       | 1.34%   |
| ASUS ROG              | 120       | 1.32%   |
| Lenovo ThinkCentre    | 101       | 1.11%   |
| Unknown               | 93        | 1.02%   |
| ASUS TUF              | 84        | 0.92%   |
| HP Laptop             | 78        | 0.86%   |
| ASUS ZenBook          | 60        | 0.66%   |
| Dell Vostro           | 52        | 0.57%   |
| Packard Bell EasyNote | 51        | 0.56%   |
| Acer Swift            | 46        | 0.51%   |
| Lenovo Legion         | 43        | 0.47%   |
| RPi Raspberry         | 42        | 0.46%   |
| HP Notebook           | 40        | 0.44%   |
| HP ENVY               | 40        | 0.44%   |
| Lenovo Yoga           | 35        | 0.38%   |
| HP ZBook              | 35        | 0.38%   |
| Gigabyte B450M        | 35        | 0.38%   |
| ASUS ASUS             | 31        | 0.34%   |
| Packard Bell IMEDIA   | 30        | 0.33%   |
| HP EliteDesk          | 30        | 0.33%   |
| Dell PowerEdge        | 28        | 0.31%   |
| Acer Nitro            | 28        | 0.31%   |
| HP ProDesk            | 27        | 0.3%    |
| Valve Jupiter         | 26        | 0.29%   |
| HP OMEN               | 26        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 843       | 9.27%   |
| 2020    | 830       | 9.13%   |
| 2019    | 792       | 8.71%   |
| 2012    | 708       | 7.79%   |
| 2013    | 681       | 7.49%   |
| 2011    | 596       | 6.55%   |
| 2021    | 589       | 6.48%   |
| 2014    | 542       | 5.96%   |
| 2015    | 532       | 5.85%   |
| 2017    | 515       | 5.66%   |
| 2010    | 486       | 5.34%   |
| 2016    | 458       | 5.04%   |
| 2008    | 402       | 4.42%   |
| 2009    | 395       | 4.34%   |
| 2022    | 262       | 2.88%   |
| 2007    | 202       | 2.22%   |
| 2006    | 103       | 1.13%   |
| Unknown | 65        | 0.71%   |
| 2005    | 48        | 0.53%   |
| 2023    | 19        | 0.21%   |
| 2004    | 12        | 0.13%   |
| 2003    | 9         | 0.1%    |
| 2002    | 2         | 0.02%   |
| 2001    | 2         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 5046      | 55.49%  |
| Desktop        | 3476      | 38.23%  |
| Convertible    | 143       | 1.57%   |
| Mini pc        | 129       | 1.42%   |
| All in one     | 102       | 1.12%   |
| Server         | 73        | 0.8%    |
| System on chip | 60        | 0.66%   |
| Tablet         | 53        | 0.58%   |
| Phone          | 10        | 0.11%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 8362      | 91.37%  |
| Enabled  | 790       | 8.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9071      | 99.75%  |
| Yes  | 23        | 0.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 2031      | 22.03%  |
| 3.01-4.0        | 1956      | 21.22%  |
| 16.01-24.0      | 1897      | 20.58%  |
| 8.01-16.0       | 1574      | 17.07%  |
| 32.01-64.0      | 796       | 8.63%   |
| 1.01-2.0        | 363       | 3.94%   |
| 64.01-256.0     | 205       | 2.22%   |
| 2.01-3.0        | 156       | 1.69%   |
| 24.01-32.0      | 143       | 1.55%   |
| 0.51-1.0        | 68        | 0.74%   |
| 0.01-0.5        | 15        | 0.16%   |
| More than 256.0 | 10        | 0.11%   |
| Unknown         | 5         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 3517      | 35.16%  |
| 2.01-3.0    | 2447      | 24.46%  |
| 4.01-8.0    | 1441      | 14.41%  |
| 3.01-4.0    | 1279      | 12.79%  |
| 0.51-1.0    | 662       | 6.62%   |
| 8.01-16.0   | 405       | 4.05%   |
| 0.01-0.5    | 143       | 1.43%   |
| 16.01-24.0  | 61        | 0.61%   |
| 32.01-64.0  | 18        | 0.18%   |
| 24.01-32.0  | 18        | 0.18%   |
| Unknown     | 9         | 0.09%   |
| 64.01-256.0 | 3         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5465      | 58.56%  |
| 2       | 2353      | 25.21%  |
| 3       | 755       | 8.09%   |
| 4       | 357       | 3.83%   |
| 5       | 159       | 1.7%    |
| 6       | 83        | 0.89%   |
| 0       | 78        | 0.84%   |
| 7       | 43        | 0.46%   |
| 8       | 15        | 0.16%   |
| 9       | 10        | 0.11%   |
| Unknown | 4         | 0.04%   |
| 11      | 3         | 0.03%   |
| 10      | 2         | 0.02%   |
| 25      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |
| 21      | 1         | 0.01%   |
| 17      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |
| 13      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5151      | 56.15%  |
| Yes       | 4023      | 43.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7928      | 86.96%  |
| No        | 1189      | 13.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6713      | 73.28%  |
| No        | 2448      | 26.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5162      | 56.07%  |
| No        | 4045      | 43.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| France  | 9093      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 1401      | 14.23%  |
| Lyon             | 196       | 1.99%   |
| Marseille        | 175       | 1.78%   |
| Toulouse         | 149       | 1.51%   |
| Nantes           | 117       | 1.19%   |
| Strasbourg       | 105       | 1.07%   |
| Montpellier      | 98        | 1%      |
| Rennes           | 88        | 0.89%   |
| Bordeaux         | 80        | 0.81%   |
| Lille            | 75        | 0.76%   |
| Roubaix          | 70        | 0.71%   |
| Grenoble         | 69        | 0.7%    |
| Nice             | 63        | 0.64%   |
| Clichy-sous-Bois | 61        | 0.62%   |
| Brest            | 46        | 0.47%   |
| Caen             | 44        | 0.45%   |
| Tours            | 40        | 0.41%   |
| Villeurbanne     | 39        | 0.4%    |
| La Rochelle      | 39        | 0.4%    |
| Poitiers         | 37        | 0.38%   |
| Toulon           | 35        | 0.36%   |
| Rouen            | 35        | 0.36%   |
| Argenteuil       | 34        | 0.35%   |
| Clermont-Ferrand | 32        | 0.33%   |
| Aix-en-Provence  | 31        | 0.31%   |
| Nîmes           | 30        | 0.3%    |
| Nancy            | 30        | 0.3%    |
| Versailles       | 29        | 0.29%   |
| Metz             | 29        | 0.29%   |
| Limoges          | 29        | 0.29%   |
| Besançon        | 29        | 0.29%   |
| Pau              | 28        | 0.28%   |
| Dijon            | 28        | 0.28%   |
| Orléans         | 27        | 0.27%   |
| Valenciennes     | 26        | 0.26%   |
| Cergy            | 26        | 0.26%   |
| Amiens           | 26        | 0.26%   |
| Perpignan        | 25        | 0.25%   |
| Angers           | 25        | 0.25%   |
| Saint-Denis      | 24        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 2083      | 3161   | 15.54%  |
| Samsung Electronics         | 2080      | 3177   | 15.52%  |
| WDC                         | 1922      | 2937   | 14.34%  |
| Crucial                     | 924       | 1281   | 6.89%   |
| Toshiba                     | 866       | 1125   | 6.46%   |
| SanDisk                     | 651       | 832    | 4.86%   |
| Kingston                    | 642       | 789    | 4.79%   |
| Unknown                     | 506       | 672    | 3.77%   |
| Hitachi                     | 410       | 520    | 3.06%   |
| SK hynix                    | 381       | 461    | 2.84%   |
| HGST                        | 351       | 460    | 2.62%   |
| Intel                       | 296       | 365    | 2.21%   |
| Micron Technology           | 233       | 276    | 1.74%   |
| PNY                         | 174       | 209    | 1.3%    |
| KIOXIA                      | 113       | 130    | 0.84%   |
| Maxtor                      | 108       | 138    | 0.81%   |
| LDLC                        | 100       | 147    | 0.75%   |
| China                       | 92        | 114    | 0.69%   |
| Phison                      | 87        | 105    | 0.65%   |
| Transcend                   | 80        | 92     | 0.6%    |
| Corsair                     | 74        | 87     | 0.55%   |
| Micron/Crucial Technology   | 66        | 86     | 0.49%   |
| Apple                       | 64        | 81     | 0.48%   |
| SPCC                        | 60        | 74     | 0.45%   |
| OCZ                         | 52        | 70     | 0.39%   |
| Fujitsu                     | 51        | 69     | 0.38%   |
| LITEON                      | 49        | 55     | 0.37%   |
| JMicron Technology          | 45        | 59     | 0.34%   |
| A-DATA Technology           | 41        | 50     | 0.31%   |
| Unknown                     | 37        | 42     | 0.28%   |
| LITEONIT                    | 36        | 38     | 0.27%   |
| Silicon Motion              | 32        | 43     | 0.24%   |
| Phison Electronics          | 30        | 36     | 0.22%   |
| Emtec                       | 28        | 34     | 0.21%   |
| Kingston Technology Company | 27        | 29     | 0.2%    |
| Gigabyte Technology         | 26        | 30     | 0.19%   |
| ASMT                        | 23        | 30     | 0.17%   |
| Intenso                     | 22        | 25     | 0.16%   |
| Hewlett-Packard             | 17        | 56     | 0.13%   |
| Netac                       | 16        | 18     | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB                        | 148       | 1%      |
| Samsung SSD 860 EVO 500GB                           | 141       | 0.95%   |
| Crucial CT500MX500SSD1 500GB                        | 133       | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB                      | 113       | 0.77%   |
| HGST HTS721010A9E630 1TB                            | 113       | 0.77%   |
| Kingston SA400S37240G 240GB SSD                     | 105       | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 104       | 0.7%    |
| Toshiba MQ01ABD100 1TB                              | 99        | 0.67%   |
| Samsung SSD 850 EVO 250GB                           | 95        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB                      | 92        | 0.62%   |
| Samsung SSD 850 EVO 500GB                           | 92        | 0.62%   |
| Seagate ST500DM002-1BD142 500GB                     | 91        | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB                      | 87        | 0.59%   |
| Crucial CT1000MX500SSD1 1TB                         | 84        | 0.57%   |
| Unknown MMC Card  32GB                              | 78        | 0.53%   |
| Samsung SSD 860 EVO 1TB                             | 72        | 0.49%   |
| Seagate ST2000DM001-1ER164 2TB                      | 71        | 0.48%   |
| Crucial CT480BX500SSD1 480GB                        | 69        | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB                      | 66        | 0.45%   |
| Samsung SSD 860 EVO 250GB                           | 65        | 0.44%   |
| Unknown MMC Card  64GB                              | 64        | 0.43%   |
| Toshiba MQ04ABF100 1TB                              | 64        | 0.43%   |
| Seagate ST1000DM003-1ER162 1TB                      | 64        | 0.43%   |
| Kingston SA400S37120G 120GB SSD                     | 62        | 0.42%   |
| Samsung SSD 870 QVO 1TB                             | 61        | 0.41%   |
| HGST HTS541010A9E680 1TB                            | 60        | 0.41%   |
| Unknown SD/MMC/MS PRO 250GB                         | 59        | 0.4%    |
| Toshiba DT01ACA100 1TB                              | 58        | 0.39%   |
| Kingston SA400S37480G 480GB SSD                     | 56        | 0.38%   |
| Seagate ST2000DM001-1CH164 2TB                      | 55        | 0.37%   |
| Samsung NVMe SSD Drive 512GB                        | 55        | 0.37%   |
| PNY CS900 120GB SSD                                 | 54        | 0.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 53        | 0.36%   |
| PNY CS900 240GB SSD                                 | 52        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                    | 52        | 0.35%   |
| Samsung SSD 860 QVO 1TB                             | 49        | 0.33%   |
| Crucial CT120BX500SSD1 120GB                        | 49        | 0.33%   |
| Samsung NVMe SSD Drive 500GB                        | 47        | 0.32%   |
| SanDisk NVMe SSD Drive 512GB                        | 46        | 0.31%   |
| Seagate ST500LT012-1DG142 500GB                     | 44        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2048      | 3085   | 36.32%  |
| WDC                 | 1584      | 2476   | 28.1%   |
| Toshiba             | 659       | 842    | 11.69%  |
| Hitachi             | 410       | 520    | 7.27%   |
| HGST                | 350       | 458    | 6.21%   |
| Samsung Electronics | 259       | 385    | 4.59%   |
| Maxtor              | 108       | 138    | 1.92%   |
| Unknown             | 66        | 75     | 1.17%   |
| Fujitsu             | 50        | 68     | 0.89%   |
| Apple               | 18        | 20     | 0.32%   |
| ASMT                | 11        | 16     | 0.2%    |
| Hewlett-Packard     | 9         | 19     | 0.16%   |
| ASMedia             | 8         | 10     | 0.14%   |
| Inateck             | 7         | 7      | 0.12%   |
| Magnetic Data       | 6         | 6      | 0.11%   |
| LaCie               | 5         | 5      | 0.09%   |
| IBM/Hitachi         | 5         | 6      | 0.09%   |
| USB3.0              | 4         | 4      | 0.07%   |
| JMicron Technology  | 4         | 10     | 0.07%   |
| Intenso             | 3         | 4      | 0.05%   |
| HGST HTS            | 3         | 5      | 0.05%   |
| ASMT109x            | 3         | 4      | 0.05%   |
| RSH-319             | 2         | 3      | 0.04%   |
| PHD 3.0             | 2         | 2      | 0.04%   |
| H/W                 | 2         | 10     | 0.04%   |
| USB                 | 1         | 1      | 0.02%   |
| Storeva             | 1         | 1      | 0.02%   |
| SILICONMOTION       | 1         | 1      | 0.02%   |
| QEMU                | 1         | 1      | 0.02%   |
| MDT                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| ICY BOX             | 1         | 1      | 0.02%   |
| HPE                 | 1         | 4      | 0.02%   |
| Generic-            | 1         | 1      | 0.02%   |
| ExcelStor           | 1         | 1      | 0.02%   |
| DELLBOSS            | 1         | 1      | 0.02%   |
| APPLE HD            | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1122      | 1595   | 25.04%  |
| Crucial             | 825       | 1138   | 18.42%  |
| Kingston            | 526       | 652    | 11.74%  |
| SanDisk             | 443       | 549    | 9.89%   |
| PNY                 | 158       | 189    | 3.53%   |
| WDC                 | 140       | 164    | 3.13%   |
| Intel               | 119       | 138    | 2.66%   |
| Micron Technology   | 96        | 125    | 2.14%   |
| SK hynix            | 92        | 112    | 2.05%   |
| China               | 91        | 113    | 2.03%   |
| Transcend           | 76        | 88     | 1.7%    |
| LDLC                | 73        | 96     | 1.63%   |
| Toshiba             | 58        | 73     | 1.29%   |
| SPCC                | 54        | 68     | 1.21%   |
| OCZ                 | 51        | 66     | 1.14%   |
| LITEON              | 41        | 45     | 0.92%   |
| Apple               | 41        | 53     | 0.92%   |
| Corsair             | 40        | 46     | 0.89%   |
| LITEONIT            | 36        | 38     | 0.8%    |
| A-DATA Technology   | 33        | 42     | 0.74%   |
| Emtec               | 26        | 30     | 0.58%   |
| KingSpec            | 16        | 19     | 0.36%   |
| Intenso             | 16        | 18     | 0.36%   |
| Patriot             | 14        | 19     | 0.31%   |
| Unknown             | 14        | 17     | 0.31%   |
| Netac               | 12        | 14     | 0.27%   |
| TEXTORM             | 11        | 12     | 0.25%   |
| Plextor             | 11        | 16     | 0.25%   |
| ASMT                | 11        | 13     | 0.25%   |
| Verbatim            | 10        | 10     | 0.22%   |
| JMicron Technology  | 10        | 11     | 0.22%   |
| Gigabyte Technology | 10        | 13     | 0.22%   |
| Dogfish             | 10        | 17     | 0.22%   |
| BHT                 | 10        | 14     | 0.22%   |
| KingDian            | 9         | 14     | 0.2%    |
| Apacer              | 8         | 8      | 0.18%   |
| Teclast             | 7         | 9      | 0.16%   |
| Seagate             | 7         | 7      | 0.16%   |
| BAITITON            | 7         | 7      | 0.16%   |
| Unknown             | 6         | 10     | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4701      | 8193   | 39.46%  |
| SSD     | 3889      | 5834   | 32.65%  |
| NVMe    | 2685      | 3705   | 22.54%  |
| MMC     | 450       | 605    | 3.78%   |
| Unknown | 187       | 288    | 1.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6900      | 13618  | 65.69%  |
| NVMe | 2662      | 3654   | 25.34%  |
| SAS  | 492       | 748    | 4.68%   |
| MMC  | 450       | 605    | 4.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5081      | 8061   | 56.31%  |
| 0.51-1.0   | 2737      | 3988   | 30.33%  |
| 1.01-2.0   | 728       | 1180   | 8.07%   |
| 3.01-4.0   | 217       | 351    | 2.4%    |
| 2.01-3.0   | 141       | 226    | 1.56%   |
| 4.01-10.0  | 100       | 174    | 1.11%   |
| 10.01-20.0 | 19        | 47     | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2383      | 24.85%  |
| 251-500        | 2163      | 22.56%  |
| 501-1000       | 1548      | 16.14%  |
| 1001-2000      | 772       | 8.05%   |
| 1-20           | 762       | 7.95%   |
| 51-100         | 538       | 5.61%   |
| More than 3000 | 450       | 4.69%   |
| 21-50          | 356       | 3.71%   |
| Unknown        | 322       | 3.36%   |
| 2001-3000      | 295       | 3.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3561      | 35.94%  |
| 21-50          | 1556      | 15.71%  |
| 101-250        | 1276      | 12.88%  |
| 51-100         | 1150      | 11.61%  |
| 251-500        | 819       | 8.27%   |
| 501-1000       | 616       | 6.22%   |
| 1001-2000      | 329       | 3.32%   |
| Unknown        | 322       | 3.25%   |
| More than 3000 | 153       | 1.54%   |
| 2001-3000      | 122       | 1.23%   |
| 0              | 3         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB           | 21        | 25     | 1.8%    |
| HGST HTS541010A9E680 1TB           | 15        | 16     | 1.29%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 14        | 15     | 1.2%    |
| Seagate ST500LM021-1KJ152 500GB    | 13        | 15     | 1.12%   |
| Seagate ST500DM002-1BD142 500GB    | 13        | 14     | 1.12%   |
| Seagate ST9500325AS 500GB          | 12        | 13     | 1.03%   |
| Toshiba MQ01ABD100 1TB             | 11        | 13     | 0.94%   |
| Seagate ST500LT012-1DG142 500GB    | 9         | 9      | 0.77%   |
| Seagate ST2000DM001-1CH164 2TB     | 9         | 10     | 0.77%   |
| Seagate ST1000LM035-1RK172 1TB     | 9         | 9      | 0.77%   |
| WDC WD10JPVX-22JC3T0 1TB           | 8         | 8      | 0.69%   |
| WDC WD10EADS-22M2B0 1TB            | 7         | 7      | 0.6%    |
| Seagate ST31000528AS 1TB           | 7         | 7      | 0.6%    |
| Samsung Electronics HD103SJ 1TB    | 7         | 8      | 0.6%    |
| HGST HTS725050A7E630 500GB         | 7         | 9      | 0.6%    |
| Toshiba MQ01ABF050 500GB           | 6         | 6      | 0.52%   |
| Seagate ST3250310AS 250GB          | 6         | 6      | 0.52%   |
| Seagate ST320LT007-9ZV142 320GB    | 6         | 7      | 0.52%   |
| Seagate ST31000524AS 1TB           | 6         | 6      | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB     | 6         | 7      | 0.52%   |
| LDLC SSD 120GB                     | 6         | 8      | 0.52%   |
| Kingston SV300S37A120G 120GB SSD   | 6         | 8      | 0.52%   |
| HGST HTS545050A7E380 500GB         | 6         | 6      | 0.52%   |
| Crucial CT525MX300SSD1 528GB       | 6         | 6      | 0.52%   |
| WDC WD6400AAKS-22A7B2 640GB        | 5         | 7      | 0.43%   |
| WDC WD10EADS-00M2B0 1TB            | 5         | 7      | 0.43%   |
| Toshiba MQ01ABD050 500GB           | 5         | 5      | 0.43%   |
| Toshiba DT01ACA100 1TB             | 5         | 6      | 0.43%   |
| Seagate ST3320820AS 320GB          | 5         | 5      | 0.43%   |
| Seagate ST1000DM003-9YN162 1TB     | 5         | 6      | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB     | 5         | 5      | 0.43%   |
| Samsung Electronics HD103UJ 1TB    | 5         | 6      | 0.43%   |
| Maxtor 6V160E0 160GB               | 5         | 5      | 0.43%   |
| Hitachi HTS727575A9E364 752GB      | 5         | 5      | 0.43%   |
| Hitachi HTS547575A9E384 752GB      | 5         | 5      | 0.43%   |
| Hitachi HTS545050B9A300 500GB      | 5         | 5      | 0.43%   |
| Hitachi HTS545050A7E380 500GB      | 5         | 5      | 0.43%   |
| HGST HTS545050A7E680 500GB         | 5         | 5      | 0.43%   |
| Crucial CT275MX300SSD1 275GB       | 5         | 6      | 0.43%   |
| WDC WD5000AAKX-001CA0 500GB        | 4         | 5      | 0.34%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 282       | 329    | 24.76%  |
| WDC                 | 247       | 297    | 21.69%  |
| Hitachi             | 97        | 108    | 8.52%   |
| Toshiba             | 89        | 100    | 7.81%   |
| Samsung Electronics | 84        | 98     | 7.37%   |
| HGST                | 64        | 71     | 5.62%   |
| Crucial             | 41        | 45     | 3.6%    |
| Maxtor              | 36        | 40     | 3.16%   |
| Kingston            | 32        | 36     | 2.81%   |
| Intel               | 30        | 33     | 2.63%   |
| SK hynix            | 25        | 32     | 2.19%   |
| SanDisk             | 22        | 26     | 1.93%   |
| Fujitsu             | 10        | 10     | 0.88%   |
| LDLC                | 9         | 11     | 0.79%   |
| OCZ                 | 8         | 9      | 0.7%    |
| Micron Technology   | 8         | 10     | 0.7%    |
| China               | 5         | 5      | 0.44%   |
| LITEONIT            | 4         | 4      | 0.35%   |
| Corsair             | 4         | 5      | 0.35%   |
| A-DATA Technology   | 4         | 4      | 0.35%   |
| SPCC                | 3         | 3      | 0.26%   |
| Netac               | 3         | 3      | 0.26%   |
| Apacer              | 3         | 3      | 0.26%   |
| 2.5"                | 3         | 4      | 0.26%   |
| LITEON              | 2         | 2      | 0.18%   |
| KingSpec            | 2         | 2      | 0.18%   |
| JMicron Technology  | 2         | 2      | 0.18%   |
| Intenso             | 2         | 2      | 0.18%   |
| Hewlett-Packard     | 2         | 2      | 0.18%   |
| Dogfish             | 2         | 2      | 0.18%   |
| ASMT                | 2         | 2      | 0.18%   |
| Apple               | 2         | 2      | 0.18%   |
| Unknown             | 1         | 1      | 0.09%   |
| Transcend           | 1         | 1      | 0.09%   |
| TEXTORM             | 1         | 1      | 0.09%   |
| TakeMS              | 1         | 1      | 0.09%   |
| Phison              | 1         | 1      | 0.09%   |
| OCZ-VERTEX          | 1         | 1      | 0.09%   |
| Magnetic Data       | 1         | 1      | 0.09%   |
| INNOVATION IT       | 1         | 1      | 0.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 282       | 329    | 32.27%  |
| WDC                 | 241       | 291    | 27.57%  |
| Hitachi             | 97        | 108    | 11.1%   |
| Toshiba             | 84        | 95     | 9.61%   |
| HGST                | 64        | 71     | 7.32%   |
| Samsung Electronics | 52        | 59     | 5.95%   |
| Maxtor              | 36        | 40     | 4.12%   |
| Fujitsu             | 10        | 10     | 1.14%   |
| Hewlett-Packard     | 2         | 2      | 0.23%   |
| ASMT                | 2         | 2      | 0.23%   |
| Unknown             | 1         | 1      | 0.11%   |
| Magnetic Data       | 1         | 1      | 0.11%   |
| IBM/Hitachi         | 1         | 1      | 0.11%   |
| Apple               | 1         | 1      | 0.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 809       | 1011   | 75.54%  |
| SSD     | 237       | 272    | 22.13%  |
| NVMe    | 23        | 27     | 2.15%   |
| Unknown | 2         | 2      | 0.19%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB                     | 2         | 3      | 5.71%   |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 5.71%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 5.71%   |
| WDC WD800BB-00FJA0 80GB                          | 1         | 1      | 2.86%   |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 2.86%   |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 2.86%   |
| WDC WD3200AAJS-22VWA0 320GB                      | 1         | 1      | 2.86%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 2      | 2.86%   |
| WDC WD20EARS-00J99B0 2TB                         | 1         | 2      | 2.86%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 2.86%   |
| WDC WD10EALX-759BA1 1TB                          | 1         | 1      | 2.86%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 2.86%   |
| Toshiba MQ02ABF050H 500GB                        | 1         | 1      | 2.86%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 2.86%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 2.86%   |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 2.86%   |
| Toshiba MK3259GSXP 320GB                         | 1         | 2      | 2.86%   |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 1         | 1      | 2.86%   |
| Seagate ST3500418ASQ 500GB                       | 1         | 1      | 2.86%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 2.86%   |
| Seagate ST3300657SS 304GB                        | 1         | 2      | 2.86%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 2.86%   |
| Seagate ST1000LM048-2E7172 1TB                   | 1         | 1      | 2.86%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB      | 1         | 1      | 2.86%   |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 2.86%   |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 2.86%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 2.86%   |
| Samsung Electronics HD501LJ 500GB                | 1         | 1      | 2.86%   |
| Kingston SMS200S360G 64GB SSD                    | 1         | 1      | 2.86%   |
| Intel SSDSC2KW256G8 256GB                        | 1         | 1      | 2.86%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 2.86%   |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 2.86%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 15     | 34.29%  |
| Samsung Electronics | 7         | 11     | 20%     |
| Toshiba             | 6         | 7      | 17.14%  |
| Seagate             | 5         | 6      | 14.29%  |
| HGST                | 2         | 2      | 5.71%   |
| SK hynix            | 1         | 1      | 2.86%   |
| Kingston            | 1         | 1      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4603      | 8092   | 45.7%   |
| Detected | 4396      | 9175   | 43.65%  |
| Malfunc  | 1036      | 1312   | 10.29%  |
| Failed   | 35        | 44     | 0.35%   |
| Fixed    | 1         | 1      | 0.01%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6227      | 54.77%  |
| AMD                              | 1585      | 13.94%  |
| Samsung Electronics              | 894       | 7.86%   |
| SanDisk                          | 421       | 3.7%    |
| SK hynix                         | 282       | 2.48%   |
| Nvidia                           | 202       | 1.78%   |
| Toshiba America Info Systems     | 174       | 1.53%   |
| Phison Electronics               | 170       | 1.5%    |
| Micron/Crucial Technology        | 169       | 1.49%   |
| Marvell Technology Group         | 169       | 1.49%   |
| ASMedia Technology               | 156       | 1.37%   |
| Kingston Technology Company      | 147       | 1.29%   |
| Micron Technology                | 145       | 1.28%   |
| JMicron Technology               | 145       | 1.28%   |
| KIOXIA                           | 105       | 0.92%   |
| VIA Technologies                 | 57        | 0.5%    |
| Silicon Motion                   | 44        | 0.39%   |
| Broadcom / LSI                   | 30        | 0.26%   |
| LSI Logic / Symbios Logic        | 26        | 0.23%   |
| Silicon Image                    | 23        | 0.2%    |
| Silicon Integrated Systems [SiS] | 22        | 0.19%   |
| Lite-On Technology               | 21        | 0.18%   |
| Union Memory (Shenzhen)          | 20        | 0.18%   |
| Seagate Technology               | 16        | 0.14%   |
| Solid State Storage Technology   | 15        | 0.13%   |
| ADATA Technology                 | 14        | 0.12%   |
| Adaptec                          | 11        | 0.1%    |
| Yangtze Memory Technologies      | 10        | 0.09%   |
| Realtek Semiconductor            | 10        | 0.09%   |
| Hewlett-Packard                  | 8         | 0.07%   |
| Shenzhen Longsys Electronics     | 7         | 0.06%   |
| Integrated Technology Express    | 7         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.05%   |
| Lenovo                           | 6         | 0.05%   |
| Apple                            | 5         | 0.04%   |
| Promise Technology               | 3         | 0.03%   |
| O2 Micro                         | 3         | 0.03%   |
| ULi Electronics                  | 2         | 0.02%   |
| Transcend                        | 1         | 0.01%   |
| Tekram Technology                | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1045      | 7.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 485       | 3.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 422       | 3.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 396       | 3.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 370       | 2.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 296       | 2.26%   |
| Intel Volume Management Device NVMe RAID Controller                            | 259       | 1.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 246       | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 228       | 1.74%   |
| AMD 400 Series Chipset SATA Controller                                         | 222       | 1.69%   |
| Samsung NVMe SSD Controller 980                                                | 216       | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 215       | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 212       | 1.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 208       | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 202       | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 192       | 1.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 184       | 1.4%    |
| Intel SATA Controller [RAID mode]                                              | 183       | 1.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 160       | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 157       | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 156       | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 144       | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 141       | 1.08%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 138       | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 130       | 0.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 130       | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 126       | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                         | 121       | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 119       | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 116       | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 112       | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 107       | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 107       | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 106       | 0.81%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 99        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 99        | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 97        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 97        | 0.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 96        | 0.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 92        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6504      | 56.73%  |
| NVMe | 2688      | 23.45%  |
| IDE  | 1336      | 11.65%  |
| RAID | 877       | 7.65%   |
| SAS  | 38        | 0.33%   |
| SCSI | 22        | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 7029      | 77.3%   |
| AMD                   | 1987      | 21.85%  |
| ARM                   | 68        | 0.75%   |
| QUALCOMM              | 4         | 0.04%   |
| CentaurHauls          | 3         | 0.03%   |
| Marvell Semiconductor | 1         | 0.01%   |
| Unknown               | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 122       | 1.34%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 83        | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 76        | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 74        | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 71        | 0.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 70        | 0.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 66        | 0.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 64        | 0.7%    |
| AMD Ryzen 5 3600 6-Core Processor             | 64        | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 61        | 0.67%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 57        | 0.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 54        | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 54        | 0.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 53        | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 52        | 0.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 52        | 0.57%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 52        | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 49        | 0.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 49        | 0.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 49        | 0.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 48        | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 48        | 0.53%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 48        | 0.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 46        | 0.5%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 45        | 0.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 44        | 0.48%   |
| ARM Processor                                 | 44        | 0.48%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 40        | 0.44%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 40        | 0.44%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 38        | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 38        | 0.42%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 36        | 0.4%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 36        | 0.4%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 35        | 0.38%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 35        | 0.38%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 35        | 0.38%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 35        | 0.38%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 34        | 0.37%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 34        | 0.37%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 34        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2021      | 22.19%  |
| Intel Core i7           | 1647      | 18.08%  |
| Intel Core i3           | 723       | 7.94%   |
| Other                   | 657       | 7.21%   |
| AMD Ryzen 5             | 461       | 5.06%   |
| Intel Celeron           | 412       | 4.52%   |
| Intel Core 2 Duo        | 407       | 4.47%   |
| AMD Ryzen 7             | 355       | 3.9%    |
| Intel Pentium           | 251       | 2.76%   |
| Intel Xeon              | 239       | 2.62%   |
| Intel Atom              | 178       | 1.95%   |
| Intel Pentium Dual-Core | 122       | 1.34%   |
| AMD Ryzen 9             | 102       | 1.12%   |
| AMD FX                  | 98        | 1.08%   |
| Intel Core 2 Quad       | 97        | 1.07%   |
| AMD Ryzen 3             | 77        | 0.85%   |
| Intel Pentium Dual      | 69        | 0.76%   |
| AMD A4                  | 68        | 0.75%   |
| Intel Core 2            | 63        | 0.69%   |
| AMD Athlon II X2        | 62        | 0.68%   |
| AMD E1                  | 61        | 0.67%   |
| Intel Core i9           | 57        | 0.63%   |
| AMD Athlon 64 X2        | 56        | 0.61%   |
| AMD A8                  | 52        | 0.57%   |
| AMD A6                  | 52        | 0.57%   |
| AMD E2                  | 46        | 0.51%   |
| AMD Ryzen 7 PRO         | 42        | 0.46%   |
| AMD E                   | 42        | 0.46%   |
| AMD Phenom II X4        | 41        | 0.45%   |
| Intel Pentium 4         | 33        | 0.36%   |
| Intel Genuine           | 32        | 0.35%   |
| AMD Athlon              | 30        | 0.33%   |
| AMD Ryzen 5 PRO         | 27        | 0.3%    |
| Intel Pentium Silver    | 24        | 0.26%   |
| Intel Pentium D         | 21        | 0.23%   |
| AMD A10                 | 21        | 0.23%   |
| AMD Athlon 64           | 19        | 0.21%   |
| AMD Sempron             | 17        | 0.19%   |
| AMD Ryzen Threadripper  | 17        | 0.19%   |
| Intel Pentium Gold      | 16        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3573      | 39.19%  |
| 4       | 3415      | 37.45%  |
| 6       | 882       | 9.67%   |
| 8       | 602       | 6.6%    |
| 1       | 249       | 2.73%   |
| 12      | 134       | 1.47%   |
| 3       | 51        | 0.56%   |
| 14      | 46        | 0.5%    |
| 10      | 46        | 0.5%    |
| 16      | 40        | 0.44%   |
| Unknown | 37        | 0.41%   |
| 20      | 12        | 0.13%   |
| 24      | 11        | 0.12%   |
| 32      | 9         | 0.1%    |
| 64      | 4         | 0.04%   |
| 40      | 2         | 0.02%   |
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
| 1       | 8996      | 98.88%  |
| 2       | 91        | 1%      |
| Unknown | 7         | 0.08%   |
| 4       | 2         | 0.02%   |
| 3       | 1         | 0.01%   |
| 0       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5737      | 62.9%   |
| 1       | 3344      | 36.66%  |
| Unknown | 37        | 0.41%   |
| 4       | 3         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 8914      | 97.85%  |
| Unknown        | 120       | 1.32%   |
| 32-bit         | 71        | 0.78%   |
| 64-bit         | 5         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1951      | 20.72%  |
| 0x306a9    | 519       | 5.51%   |
| 0x206a7    | 519       | 5.51%   |
| 0x306c3    | 515       | 5.47%   |
| 0x1067a    | 374       | 3.97%   |
| 0x906ea    | 288       | 3.06%   |
| 0x506e3    | 237       | 2.52%   |
| 0x806c1    | 236       | 2.51%   |
| 0x806ec    | 212       | 2.25%   |
| 0x806ea    | 179       | 1.9%    |
| 0x40651    | 175       | 1.86%   |
| 0x306d4    | 169       | 1.8%    |
| 0x406e3    | 167       | 1.77%   |
| 0x906e9    | 165       | 1.75%   |
| 0x806e9    | 148       | 1.57%   |
| 0x20655    | 140       | 1.49%   |
| 0x6fd      | 138       | 1.47%   |
| 0x08108109 | 106       | 1.13%   |
| 0x010000c8 | 106       | 1.13%   |
| 0x08701021 | 100       | 1.06%   |
| 0x10676    | 93        | 0.99%   |
| 0x08600106 | 89        | 0.95%   |
| 0xa0652    | 85        | 0.9%    |
| 0x30678    | 83        | 0.88%   |
| 0x0800820d | 79        | 0.84%   |
| 0x406c4    | 77        | 0.82%   |
| 0x906ed    | 70        | 0.74%   |
| 0x106e5    | 66        | 0.7%    |
| 0x0a50000c | 66        | 0.7%    |
| 0x706e5    | 60        | 0.64%   |
| 0x06001119 | 60        | 0.64%   |
| 0x906a3    | 58        | 0.62%   |
| 0x06000852 | 57        | 0.61%   |
| 0x506c9    | 56        | 0.59%   |
| 0x806eb    | 55        | 0.58%   |
| 0x08701013 | 54        | 0.57%   |
| 0x07030105 | 53        | 0.56%   |
| 0x05000119 | 53        | 0.56%   |
| 0x706a1    | 52        | 0.55%   |
| 0x6fb      | 52        | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1422      | 15.62%  |
| Haswell          | 887       | 9.74%   |
| IvyBridge        | 630       | 6.92%   |
| SandyBridge      | 627       | 6.89%   |
| Penryn           | 544       | 5.97%   |
| Skylake          | 539       | 5.92%   |
| Zen 2            | 385       | 4.23%   |
| Core             | 308       | 3.38%   |
| TigerLake        | 294       | 3.23%   |
| Unknown          | 277       | 3.04%   |
| Zen+             | 275       | 3.02%   |
| Silvermont       | 266       | 2.92%   |
| Westmere         | 252       | 2.77%   |
| Broadwell        | 236       | 2.59%   |
| Zen 3            | 216       | 2.37%   |
| CometLake        | 209       | 2.3%    |
| K10              | 202       | 2.22%   |
| Piledriver       | 158       | 1.74%   |
| Zen              | 150       | 1.65%   |
| Icelake          | 147       | 1.61%   |
| Goldmont plus    | 119       | 1.31%   |
| K8 Hammer        | 118       | 1.3%    |
| Nehalem          | 116       | 1.27%   |
| Alderlake Hybrid | 113       | 1.24%   |
| Bobcat           | 89        | 0.98%   |
| Excavator        | 82        | 0.9%    |
| Puma             | 78        | 0.86%   |
| Bonnell          | 74        | 0.81%   |
| Goldmont         | 73        | 0.8%    |
| NetBurst         | 60        | 0.66%   |
| Jaguar           | 47        | 0.52%   |
| K10 Llano        | 26        | 0.29%   |
| P6               | 25        | 0.27%   |
| Steamroller      | 17        | 0.19%   |
| K8 & K10 hybrid  | 14        | 0.15%   |
| Tremont          | 12        | 0.13%   |
| Bulldozer        | 12        | 0.13%   |
| K6               | 5         | 0.05%   |
| Sapphire Rapids  | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5137      | 47.51%  |
| Nvidia                                       | 3326      | 30.76%  |
| AMD                                          | 2238      | 20.7%   |
| Matrox Electronics Systems                   | 52        | 0.48%   |
| ASPEED Technology                            | 30        | 0.28%   |
| Silicon Integrated Systems [SiS]             | 14        | 0.13%   |
| VIA Technologies                             | 9         | 0.08%   |
| ATI Technologies                             | 3         | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |
| Red Hat                                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 423       | 3.81%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 339       | 3.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 272       | 2.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 234       | 2.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 211       | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 202       | 1.82%   |
| Intel UHD Graphics 620                                                                   | 189       | 1.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 183       | 1.65%   |
| Intel HD Graphics 530                                                                    | 180       | 1.62%   |
| Intel HD Graphics 5500                                                                   | 177       | 1.59%   |
| AMD Renoir                                                                               | 174       | 1.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 171       | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 170       | 1.53%   |
| Intel HD Graphics 620                                                                    | 169       | 1.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 163       | 1.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 162       | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 155       | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 143       | 1.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 130       | 1.17%   |
| Intel HD Graphics 630                                                                    | 127       | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 119       | 1.07%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 106       | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 104       | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 97        | 0.87%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 96        | 0.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 96        | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 95        | 0.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 94        | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 84        | 0.76%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 78        | 0.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 75        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 69        | 0.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 69        | 0.62%   |
| Nvidia GT218 [GeForce 210]                                                               | 68        | 0.61%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 68        | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 67        | 0.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 64        | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 59        | 0.53%   |
| Intel HD Graphics 500                                                                    | 58        | 0.52%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 56        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 3505      | 38.23%  |
| 1 x Nvidia           | 1885      | 20.56%  |
| 1 x AMD              | 1756      | 19.15%  |
| Intel + Nvidia       | 1297      | 14.15%  |
| Intel + AMD          | 223       | 2.43%   |
| 2 x AMD              | 132       | 1.44%   |
| AMD + Nvidia         | 127       | 1.39%   |
| Other                | 81        | 0.88%   |
| 1 x Matrox           | 47        | 0.51%   |
| 2 x Nvidia           | 26        | 0.28%   |
| 1 x ASPEED           | 25        | 0.27%   |
| 2 x Intel            | 22        | 0.24%   |
| 1 x SiS              | 14        | 0.15%   |
| 1 x VIA              | 9         | 0.1%    |
| Nvidia + Matrox      | 4         | 0.04%   |
| 3 x AMD              | 2         | 0.02%   |
| Nvidia + ASPEED      | 2         | 0.02%   |
| Intel + 2 x Nvidia   | 2         | 0.02%   |
| AMD + ASPEED         | 2         | 0.02%   |
| 3 x Nvidia           | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.01%   |
| 2 x AMD + 1 x ASPEED | 1         | 0.01%   |
| 1 x XGI              | 1         | 0.01%   |
| 1 x S3 Graphics      | 1         | 0.01%   |
| 1 x Red Hat          | 1         | 0.01%   |
| Intel + 2 x AMD      | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 7256      | 78.59%  |
| Proprietary | 1562      | 16.92%  |
| Unknown     | 415       | 4.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4934      | 52.81%  |
| 0.01-0.5   | 1205      | 12.9%   |
| 1.01-2.0   | 1155      | 12.36%  |
| 0.51-1.0   | 789       | 8.44%   |
| 3.01-4.0   | 583       | 6.24%   |
| 7.01-8.0   | 285       | 3.05%   |
| 5.01-6.0   | 205       | 2.19%   |
| 8.01-16.0  | 93        | 1%      |
| 2.01-3.0   | 75        | 0.8%    |
| 16.01-24.0 | 13        | 0.14%   |
| 4.01-5.0   | 5         | 0.05%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1234      | 12.39%  |
| AU Optronics            | 1187      | 11.92%  |
| Chimei Innolux          | 799       | 8.02%   |
| LG Display              | 790       | 7.93%   |
| BOE                     | 714       | 7.17%   |
| Iiyama                  | 519       | 5.21%   |
| Dell                    | 513       | 5.15%   |
| Hewlett-Packard         | 398       | 4%      |
| Acer                    | 347       | 3.48%   |
| Goldstar                | 335       | 3.36%   |
| Ancor Communications    | 276       | 2.77%   |
| Philips                 | 259       | 2.6%    |
| AOC                     | 227       | 2.28%   |
| Sharp                   | 215       | 2.16%   |
| BenQ                    | 199       | 2%      |
| Lenovo                  | 161       | 1.62%   |
| Chi Mei Optoelectronics | 155       | 1.56%   |
| Apple                   | 145       | 1.46%   |
| ViewSonic               | 119       | 1.19%   |
| ASUSTek Computer        | 81        | 0.81%   |
| PANDA                   | 78        | 0.78%   |
| InfoVision              | 76        | 0.76%   |
| LG Philips              | 72        | 0.72%   |
| Sony                    | 58        | 0.58%   |
| Unknown                 | 51        | 0.51%   |
| HannStar                | 49        | 0.49%   |
| Idek Iiyama             | 36        | 0.36%   |
| Packard Bell            | 35        | 0.35%   |
| LG Electronics          | 34        | 0.34%   |
| Fujitsu Siemens         | 32        | 0.32%   |
| Vestel Elektronik       | 30        | 0.3%    |
| Toshiba                 | 27        | 0.27%   |
| NEC Computers           | 26        | 0.26%   |
| Eizo                    | 26        | 0.26%   |
| CSO                     | 25        | 0.25%   |
| MSI                     | 23        | 0.23%   |
| Medion                  | 22        | 0.22%   |
| Hitachi                 | 22        | 0.22%   |
| Denver                  | 22        | 0.22%   |
| Panasonic               | 21        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                     | 47        | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 46        | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 43        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 35        | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 34        | 0.33%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch      | 30        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 29        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 29        | 0.28%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 28        | 0.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 26        | 0.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 26        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 26        | 0.25%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 26        | 0.25%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 26        | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 25        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 25        | 0.24%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 25        | 0.24%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 24        | 0.23%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 24        | 0.23%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 22        | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 21        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 21        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 21        | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 20        | 0.19%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                         | 20        | 0.19%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 19        | 0.18%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 18        | 0.18%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                     | 18        | 0.18%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 18        | 0.18%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 18        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 18        | 0.18%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                    | 17        | 0.17%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 17        | 0.17%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                     | 17        | 0.17%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 17        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 17        | 0.17%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch             | 17        | 0.17%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 17        | 0.17%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 17        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4313      | 45.65%  |
| 1366x768 (WXGA)    | 1357      | 14.36%  |
| 1600x900 (HD+)     | 591       | 6.25%   |
| 3840x2160 (4K)     | 439       | 4.65%   |
| 2560x1440 (QHD)    | 417       | 4.41%   |
| 1680x1050 (WSXGA+) | 369       | 3.91%   |
| 1280x1024 (SXGA)   | 351       | 3.71%   |
| 1440x900 (WXGA+)   | 291       | 3.08%   |
| 1920x1200 (WUXGA)  | 290       | 3.07%   |
| 1280x800 (WXGA)    | 198       | 2.1%    |
| Unknown            | 120       | 1.27%   |
| 3440x1440          | 72        | 0.76%   |
| 2560x1080          | 59        | 0.62%   |
| 1360x768           | 59        | 0.62%   |
| 3840x1080          | 56        | 0.59%   |
| 2560x1600          | 47        | 0.5%    |
| 1024x600           | 33        | 0.35%   |
| 2880x1800          | 32        | 0.34%   |
| 1600x1200          | 32        | 0.34%   |
| 3840x2400          | 27        | 0.29%   |
| 2160x1440          | 27        | 0.29%   |
| 1024x768 (XGA)     | 26        | 0.28%   |
| 800x1280           | 22        | 0.23%   |
| 1920x540           | 20        | 0.21%   |
| 3200x1800 (QHD+)   | 13        | 0.14%   |
| 2288x1287          | 13        | 0.14%   |
| 3000x2000          | 10        | 0.11%   |
| 3840x1600          | 9         | 0.1%    |
| 4480x1440          | 8         | 0.08%   |
| 2736x1824          | 8         | 0.08%   |
| 3200x1080          | 7         | 0.07%   |
| 3600x1080          | 6         | 0.06%   |
| 1680x945           | 6         | 0.06%   |
| 5760x2160          | 5         | 0.05%   |
| 5760x1080          | 5         | 0.05%   |
| 3840x1200          | 5         | 0.05%   |
| 2048x1152          | 5         | 0.05%   |
| 1280x720 (HD)      | 5         | 0.05%   |
| 3072x1920          | 4         | 0.04%   |
| 2520x1680          | 4         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2191      | 22.07%  |
| 17      | 966       | 9.73%   |
| 13      | 860       | 8.66%   |
| 24      | 822       | 8.28%   |
| 23      | 791       | 7.97%   |
| 27      | 721       | 7.26%   |
| 14      | 593       | 5.97%   |
| 21      | 579       | 5.83%   |
| Unknown | 458       | 4.61%   |
| 19      | 331       | 3.33%   |
| 22      | 236       | 2.38%   |
| 12      | 173       | 1.74%   |
| 20      | 154       | 1.55%   |
| 18      | 147       | 1.48%   |
| 31      | 117       | 1.18%   |
| 34      | 106       | 1.07%   |
| 11      | 79        | 0.8%    |
| 16      | 75        | 0.76%   |
| 84      | 64        | 0.64%   |
| 10      | 49        | 0.49%   |
| 72      | 48        | 0.48%   |
| 32      | 43        | 0.43%   |
| 25      | 43        | 0.43%   |
| 40      | 38        | 0.38%   |
| 54      | 26        | 0.26%   |
| 26      | 25        | 0.25%   |
| 33      | 23        | 0.23%   |
| 46      | 14        | 0.14%   |
| 65      | 12        | 0.12%   |
| 52      | 12        | 0.12%   |
| 48      | 12        | 0.12%   |
| 29      | 11        | 0.11%   |
| 7       | 11        | 0.11%   |
| 3       | 11        | 0.11%   |
| 142     | 9         | 0.09%   |
| 49      | 8         | 0.08%   |
| 36      | 7         | 0.07%   |
| 35      | 7         | 0.07%   |
| 42      | 6         | 0.06%   |
| 39      | 6         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3292      | 33.85%  |
| 501-600        | 2150      | 22.11%  |
| 401-500        | 1247      | 12.82%  |
| 351-400        | 1088      | 11.19%  |
| 201-300        | 786       | 8.08%   |
| Unknown        | 458       | 4.71%   |
| 601-700        | 207       | 2.13%   |
| 701-800        | 179       | 1.84%   |
| 1501-2000      | 114       | 1.17%   |
| 1001-1500      | 99        | 1.02%   |
| 801-900        | 64        | 0.66%   |
| 1-100          | 21        | 0.22%   |
| More than 2000 | 9         | 0.09%   |
| 901-1000       | 8         | 0.08%   |
| 101-200        | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 6613      | 74.01%  |
| 16/10   | 1214      | 13.59%  |
| Unknown | 378       | 4.23%   |
| 5/4     | 329       | 3.68%   |
| 21/9    | 129       | 1.44%   |
| 3/2     | 100       | 1.12%   |
| 4/3     | 87        | 0.97%   |
| 6/5     | 29        | 0.32%   |
| 32/9    | 19        | 0.21%   |
| 0.67    | 11        | 0.12%   |
| 1.00    | 9         | 0.1%    |
| 3.20    | 4         | 0.04%   |
| 3.73    | 3         | 0.03%   |
| 11/10   | 2         | 0.02%   |
| 0.62    | 2         | 0.02%   |
| 0.56    | 2         | 0.02%   |
| 3.88    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2186      | 22.28%  |
| 201-250        | 1952      | 19.9%   |
| 81-90          | 1045      | 10.65%  |
| 301-350        | 748       | 7.62%   |
| 121-130        | 670       | 6.83%   |
| 151-200        | 669       | 6.82%   |
| Unknown        | 458       | 4.67%   |
| 71-80          | 420       | 4.28%   |
| 351-500        | 299       | 3.05%   |
| 251-300        | 289       | 2.95%   |
| 141-150        | 259       | 2.64%   |
| More than 1000 | 187       | 1.91%   |
| 61-70          | 149       | 1.52%   |
| 131-140        | 132       | 1.35%   |
| 501-1000       | 108       | 1.1%    |
| 51-60          | 79        | 0.81%   |
| 111-120        | 69        | 0.7%    |
| 41-50          | 50        | 0.51%   |
| 1-40           | 23        | 0.23%   |
| 91-100         | 19        | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3433      | 35.97%  |
| 101-120       | 2404      | 25.19%  |
| 121-160       | 2400      | 25.15%  |
| 161-240       | 515       | 5.4%    |
| Unknown       | 458       | 4.8%    |
| More than 240 | 187       | 1.96%   |
| 1-50          | 146       | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 7189      | 77.33%  |
| 2     | 1477      | 15.89%  |
| 0     | 454       | 4.88%   |
| 3     | 165       | 1.77%   |
| 4     | 9         | 0.1%    |
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
| Realtek Semiconductor             | 4855      | 35.85%  |
| Intel                             | 4372      | 32.28%  |
| Qualcomm Atheros                  | 1592      | 11.76%  |
| Broadcom                          | 755       | 5.57%   |
| Marvell Technology Group          | 194       | 1.43%   |
| Broadcom Limited                  | 159       | 1.17%   |
| Nvidia                            | 149       | 1.1%    |
| Ralink                            | 148       | 1.09%   |
| MediaTek                          | 138       | 1.02%   |
| TP-Link                           | 104       | 0.77%   |
| NetGear                           | 82        | 0.61%   |
| Ralink Technology                 | 79        | 0.58%   |
| ASIX Electronics                  | 75        | 0.55%   |
| Samsung Electronics               | 65        | 0.48%   |
| Dell                              | 46        | 0.34%   |
| Xiaomi                            | 44        | 0.32%   |
| D-Link System                     | 41        | 0.3%    |
| DisplayLink                       | 32        | 0.24%   |
| D-Link                            | 32        | 0.24%   |
| Ericsson Business Mobile Networks | 29        | 0.21%   |
| Sierra Wireless                   | 28        | 0.21%   |
| Qualcomm                          | 28        | 0.21%   |
| Aquantia                          | 28        | 0.21%   |
| Huawei Technologies               | 26        | 0.19%   |
| VIA Technologies                  | 25        | 0.18%   |
| Microsoft                         | 24        | 0.18%   |
| JMicron Technology                | 23        | 0.17%   |
| Lenovo                            | 22        | 0.16%   |
| Belkin Components                 | 22        | 0.16%   |
| Qualcomm Atheros Communications   | 19        | 0.14%   |
| Google                            | 16        | 0.12%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.11%   |
| OPPO Electronics                  | 15        | 0.11%   |
| Guillemot                         | 15        | 0.11%   |
| Attansic Technology               | 14        | 0.1%    |
| ASUSTek Computer                  | 14        | 0.1%    |
| Microchip Technology              | 13        | 0.1%    |
| Hewlett-Packard                   | 13        | 0.1%    |
| Edimax Technology                 | 10        | 0.07%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3323      | 20.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 483       | 3.04%   |
| Intel Wi-Fi 6 AX200                                               | 381       | 2.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 334       | 2.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 296       | 1.86%   |
| Intel Wireless 8265 / 8275                                        | 241       | 1.52%   |
| Intel Wi-Fi 6 AX201                                               | 226       | 1.42%   |
| Intel Wireless 7265                                               | 224       | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 218       | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 191       | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 189       | 1.19%   |
| Intel Wireless 8260                                               | 181       | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 176       | 1.11%   |
| Intel Wireless 7260                                               | 174       | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 167       | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 161       | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 160       | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 144       | 0.91%   |
| Intel I211 Gigabit Network Connection                             | 142       | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 136       | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 136       | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 135       | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 132       | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 126       | 0.79%   |
| Intel Wireless 3165                                               | 121       | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 120       | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 114       | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 106       | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 102       | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 95        | 0.6%    |
| Intel Wireless-AC 9260                                            | 94        | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 94        | 0.59%   |
| Intel 82579V Gigabit Network Connection                           | 93        | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 86        | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 83        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 80        | 0.5%    |
| Broadcom BCM43142 802.11b/g/n                                     | 80        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 79        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 79        | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 72        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3234      | 46.11%  |
| Qualcomm Atheros                      | 1215      | 17.32%  |
| Realtek Semiconductor                 | 1190      | 16.97%  |
| Broadcom                              | 457       | 6.52%   |
| Ralink                                | 148       | 2.11%   |
| MediaTek                              | 124       | 1.77%   |
| TP-Link                               | 97        | 1.38%   |
| Broadcom Limited                      | 94        | 1.34%   |
| Ralink Technology                     | 79        | 1.13%   |
| NetGear                               | 78        | 1.11%   |
| D-Link                                | 30        | 0.43%   |
| Sierra Wireless                       | 28        | 0.4%    |
| Microsoft                             | 24        | 0.34%   |
| Dell                                  | 23        | 0.33%   |
| D-Link System                         | 22        | 0.31%   |
| Belkin Components                     | 22        | 0.31%   |
| Qualcomm Atheros Communications       | 19        | 0.27%   |
| Marvell Technology Group              | 18        | 0.26%   |
| Qualcomm                              | 16        | 0.23%   |
| Guillemot                             | 15        | 0.21%   |
| ASUSTek Computer                      | 14        | 0.2%    |
| Edimax Technology                     | 10        | 0.14%   |
| Fibocom                               | 7         | 0.1%    |
| Hewlett-Packard                       | 6         | 0.09%   |
| Sagem                                 | 5         | 0.07%   |
| IMC Networks                          | 5         | 0.07%   |
| TRENDnet                              | 4         | 0.06%   |
| Gemtek                                | 4         | 0.06%   |
| ZyDAS                                 | 3         | 0.04%   |
| Accton Technology                     | 3         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.04%   |
| Toshiba                               | 2         | 0.03%   |
| Realtek                               | 2         | 0.03%   |
| Linksys                               | 2         | 0.03%   |
| Fujitsu Siemens Computers             | 2         | 0.03%   |
| ZyXEL Communications                  | 1         | 0.01%   |
| Z-Com                                 | 1         | 0.01%   |
| Yoctopuce Sarl                        | 1         | 0.01%   |
| Wilocity                              | 1         | 0.01%   |
| Wacom                                 | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 381       | 5.4%    |
| Intel Wireless 8265 / 8275                                              | 241       | 3.42%   |
| Intel Wi-Fi 6 AX201                                                     | 226       | 3.2%    |
| Intel Wireless 7265                                                     | 224       | 3.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 218       | 3.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 191       | 2.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 189       | 2.68%   |
| Intel Wireless 8260                                                     | 181       | 2.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 176       | 2.49%   |
| Intel Wireless 7260                                                     | 174       | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 161       | 2.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 160       | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 144       | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 136       | 1.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 132       | 1.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 126       | 1.79%   |
| Intel Wireless 3165                                                     | 121       | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 120       | 1.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 114       | 1.62%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 106       | 1.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 102       | 1.45%   |
| Intel Wireless-AC 9260                                                  | 94        | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 94        | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 86        | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                           | 80        | 1.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 65        | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 65        | 0.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 63        | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 63        | 0.89%   |
| Intel Wireless 3160                                                     | 61        | 0.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 0.86%   |
| Intel WiFi Link 5100                                                    | 60        | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 59        | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 59        | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 58        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 57        | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 55        | 0.78%   |
| Intel Centrino Wireless-N 2230                                          | 54        | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 53        | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 49        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4408      | 52.13%  |
| Intel                            | 2218      | 26.23%  |
| Qualcomm Atheros                 | 556       | 6.58%   |
| Broadcom                         | 369       | 4.36%   |
| Marvell Technology Group         | 176       | 2.08%   |
| Nvidia                           | 149       | 1.76%   |
| ASIX Electronics                 | 75        | 0.89%   |
| Broadcom Limited                 | 68        | 0.8%    |
| Samsung Electronics              | 51        | 0.6%    |
| Xiaomi                           | 44        | 0.52%   |
| DisplayLink                      | 32        | 0.38%   |
| Aquantia                         | 28        | 0.33%   |
| JMicron Technology               | 23        | 0.27%   |
| VIA Technologies                 | 22        | 0.26%   |
| Lenovo                           | 22        | 0.26%   |
| Huawei Technologies              | 20        | 0.24%   |
| D-Link System                    | 19        | 0.22%   |
| Google                           | 16        | 0.19%   |
| OPPO Electronics                 | 15        | 0.18%   |
| Silicon Integrated Systems [SiS] | 14        | 0.17%   |
| Attansic Technology              | 14        | 0.17%   |
| MediaTek                         | 13        | 0.15%   |
| Qualcomm                         | 12        | 0.14%   |
| Microchip Technology             | 9         | 0.11%   |
| TP-Link                          | 7         | 0.08%   |
| OnePlus Technology (Shenzhen)    | 7         | 0.08%   |
| ICS Advent                       | 7         | 0.08%   |
| Apple                            | 6         | 0.07%   |
| Motorola PCS                     | 5         | 0.06%   |
| QLogic                           | 4         | 0.05%   |
| NetGear                          | 4         | 0.05%   |
| Mellanox Technologies            | 4         | 0.05%   |
| 3Com                             | 4         | 0.05%   |
| Linksys                          | 3         | 0.04%   |
| HTC (High Tech Computer)         | 3         | 0.04%   |
| Hisense                          | 2         | 0.02%   |
| Dell                             | 2         | 0.02%   |
| D-Link                           | 2         | 0.02%   |
| Cypress Semiconductor            | 2         | 0.02%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3323      | 38.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 483       | 5.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 334       | 3.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 296       | 3.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 167       | 1.93%   |
| Intel I211 Gigabit Network Connection                             | 142       | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 136       | 1.57%   |
| Intel Ethernet Connection (2) I219-V                              | 135       | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 95        | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 93        | 1.07%   |
| Intel Ethernet Connection (7) I219-V                              | 83        | 0.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 80        | 0.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 79        | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 79        | 0.91%   |
| Intel Ethernet Connection I217-V                                  | 72        | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 69        | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 68        | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 64        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 63        | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 62        | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 62        | 0.72%   |
| Intel Ethernet Controller I225-V                                  | 59        | 0.68%   |
| Nvidia MCP61 Ethernet                                             | 54        | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 52        | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 51        | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 50        | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 49        | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 46        | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 45        | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 44        | 0.51%   |
| Intel 82574L Gigabit Network Connection                           | 44        | 0.51%   |
| Intel I210 Gigabit Network Connection                             | 43        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 42        | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 41        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 41        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 40        | 0.46%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39        | 0.45%   |
| Intel 82567LM Gigabit Network Connection                          | 39        | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 38        | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 37        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7921      | 53.54%  |
| WiFi     | 6708      | 45.34%  |
| Modem    | 150       | 1.01%   |
| Unknown  | 16        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4965      | 52.35%  |
| Ethernet | 4518      | 47.64%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4932      | 53.99%  |
| 1     | 3804      | 41.64%  |
| 0     | 172       | 1.88%   |
| 3     | 171       | 1.87%   |
| 4     | 37        | 0.41%   |
| 5     | 7         | 0.08%   |
| 8     | 4         | 0.04%   |
| 6     | 4         | 0.04%   |
| 7     | 3         | 0.03%   |
| 9     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5822      | 62.06%  |
| Yes  | 3559      | 37.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2613      | 50.11%  |
| Realtek Semiconductor           | 420       | 8.05%   |
| IMC Networks                    | 350       | 6.71%   |
| Cambridge Silicon Radio         | 328       | 6.29%   |
| Qualcomm Atheros Communications | 296       | 5.68%   |
| Broadcom                        | 243       | 4.66%   |
| Apple                           | 157       | 3.01%   |
| Lite-On Technology              | 150       | 2.88%   |
| Foxconn / Hon Hai               | 150       | 2.88%   |
| ASUSTek Computer                | 101       | 1.94%   |
| Dell                            | 85        | 1.63%   |
| Realtek                         | 47        | 0.9%    |
| Hewlett-Packard                 | 41        | 0.79%   |
| Toshiba                         | 39        | 0.75%   |
| Ralink                          | 34        | 0.65%   |
| Ralink Technology               | 22        | 0.42%   |
| MediaTek                        | 21        | 0.4%    |
| Belkin Components               | 19        | 0.36%   |
| TP-Link                         | 18        | 0.35%   |
| Marvell Semiconductor           | 14        | 0.27%   |
| Foxconn International           | 14        | 0.27%   |
| Alps Electric                   | 14        | 0.27%   |
| Chicony Electronics             | 7         | 0.13%   |
| USI                             | 6         | 0.12%   |
| Integrated System Solution      | 6         | 0.12%   |
| HTC (High Tech Computer)        | 3         | 0.06%   |
| Fujitsu                         | 2         | 0.04%   |
| Conwise Technology              | 2         | 0.04%   |
| TRENDnet                        | 1         | 0.02%   |
| Syntek                          | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Kensington                      | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| D-Link System                   | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Com One                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 956       | 18.32%  |
| Intel AX201 Bluetooth                               | 512       | 9.81%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 384       | 7.36%   |
| Intel AX200 Bluetooth                               | 355       | 6.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 328       | 6.29%   |
| Realtek Bluetooth Radio                             | 279       | 5.35%   |
| IMC Networks Bluetooth Device                       | 129       | 2.47%   |
| Qualcomm Atheros  Bluetooth Device                  | 113       | 2.17%   |
| IMC Networks Bluetooth Radio                        | 113       | 2.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 99        | 1.9%    |
| Intel Bluetooth Device                              | 91        | 1.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 86        | 1.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 80        | 1.53%   |
| Intel Wireless-AC 3168 Bluetooth                    | 61        | 1.17%   |
| Foxconn / Hon Hai Bluetooth Device                  | 61        | 1.17%   |
| Apple Bluetooth Host Controller                     | 57        | 1.09%   |
| Intel AX210 Bluetooth                               | 56        | 1.07%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 55        | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 53        | 1.02%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 51        | 0.98%   |
| Apple Bluetooth USB Host Controller                 | 49        | 0.94%   |
| Realtek Bluetooth Radio                             | 47        | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 47        | 0.9%    |
| Lite-On Bluetooth Device                            | 39        | 0.75%   |
| IMC Networks Wireless_Device                        | 38        | 0.73%   |
| Dell DW375 Bluetooth Module                         | 37        | 0.71%   |
| Ralink RT3290 Bluetooth                             | 34        | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 33        | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 30        | 0.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 29        | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 29        | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 26        | 0.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 25        | 0.48%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 25        | 0.48%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 0.44%   |
| Broadcom BCM43142A0 Bluetooth Device                | 23        | 0.44%   |
| Apple Bluetooth HCI                                 | 23        | 0.44%   |
| Realtek RTL8723B Bluetooth                          | 21        | 0.4%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 21        | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6667      | 52.18%  |
| AMD                              | 2398      | 18.77%  |
| Nvidia                           | 2376      | 18.6%   |
| C-Media Electronics              | 186       | 1.46%   |
| Logitech                         | 121       | 0.95%   |
| Creative Labs                    | 81        | 0.63%   |
| Realtek Semiconductor            | 70        | 0.55%   |
| GN Netcom                        | 68        | 0.53%   |
| Kingston Technology              | 48        | 0.38%   |
| Texas Instruments                | 44        | 0.34%   |
| JMTek                            | 44        | 0.34%   |
| Corsair                          | 44        | 0.34%   |
| Plantronics                      | 43        | 0.34%   |
| VIA Technologies                 | 40        | 0.31%   |
| Focusrite-Novation               | 30        | 0.23%   |
| SteelSeries ApS                  | 28        | 0.22%   |
| Generalplus Technology           | 28        | 0.22%   |
| Razer USA                        | 24        | 0.19%   |
| Silicon Integrated Systems [SiS] | 21        | 0.16%   |
| Lenovo                           | 21        | 0.16%   |
| Sennheiser Communications        | 20        | 0.16%   |
| Hewlett-Packard                  | 17        | 0.13%   |
| ASUSTek Computer                 | 16        | 0.13%   |
| XMOS                             | 13        | 0.1%    |
| Creative Technology              | 13        | 0.1%    |
| M-Audio                          | 12        | 0.09%   |
| Sony                             | 10        | 0.08%   |
| BEHRINGER International          | 9         | 0.07%   |
| RODE Microphones                 | 8         | 0.06%   |
| PreSonus Audio Electronics       | 8         | 0.06%   |
| Turtle Beach                     | 7         | 0.05%   |
| Tenx Technology                  | 7         | 0.05%   |
| GYROCOM C&C                      | 7         | 0.05%   |
| Ensoniq                          | 7         | 0.05%   |
| Dell                             | 7         | 0.05%   |
| Yamaha                           | 6         | 0.05%   |
| Scarlett                         | 6         | 0.05%   |
| Micro Star International         | 6         | 0.05%   |
| DSEA A/S                         | 6         | 0.05%   |
| Alesis                           | 6         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 621       | 4.15%   |
| AMD Family 17h/19h HD Audio Controller                                     | 614       | 4.11%   |
| Intel Sunrise Point-LP HD Audio                                            | 593       | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 563       | 3.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 525       | 3.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 402       | 2.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 394       | 2.63%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 330       | 2.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 326       | 2.18%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 322       | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 307       | 2.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 293       | 1.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 292       | 1.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 283       | 1.89%   |
| AMD FCH Azalia Controller                                                  | 277       | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 254       | 1.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 219       | 1.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 217       | 1.45%   |
| Intel 8 Series HD Audio Controller                                         | 216       | 1.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 212       | 1.42%   |
| Intel Broadwell-U Audio Controller                                         | 210       | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 206       | 1.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 194       | 1.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 191       | 1.28%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 176       | 1.18%   |
| Intel Comet Lake PCH-LP cAVS                                               | 168       | 1.12%   |
| Intel 200 Series PCH HD Audio                                              | 163       | 1.09%   |
| Intel Comet Lake PCH cAVS                                                  | 143       | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                   | 142       | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 140       | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 137       | 0.92%   |
| Nvidia High Definition Audio Controller                                    | 134       | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                              | 123       | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 119       | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 115       | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                              | 115       | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 109       | 0.73%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 108       | 0.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 108       | 0.72%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 107       | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1540      | 22.41%  |
| SK hynix            | 1348      | 19.62%  |
| Unknown             | 693       | 10.08%  |
| Kingston            | 692       | 10.07%  |
| Micron Technology   | 671       | 9.76%   |
| Corsair             | 458       | 6.66%   |
| Crucial             | 450       | 6.55%   |
| G.Skill             | 325       | 4.73%   |
| Elpida              | 101       | 1.47%   |
| Ramaxel Technology  | 97        | 1.41%   |
| Nanya Technology    | 96        | 1.4%    |
| A-DATA Technology   | 64        | 0.93%   |
| Unknown (ABCD)      | 62        | 0.9%    |
| Transcend           | 33        | 0.48%   |
| Unknown             | 30        | 0.44%   |
| Team                | 18        | 0.26%   |
| Patriot             | 18        | 0.26%   |
| PNY                 | 16        | 0.23%   |
| Unifosa             | 14        | 0.2%    |
| Timetec             | 11        | 0.16%   |
| ASint Technology    | 9         | 0.13%   |
| Qimonda             | 8         | 0.12%   |
| Unknown (0x0C97)    | 6         | 0.09%   |
| Toshiba             | 6         | 0.09%   |
| TEXTORM             | 5         | 0.07%   |
| Hewlett-Packard     | 5         | 0.07%   |
| Apacer              | 5         | 0.07%   |
| Lexar               | 4         | 0.06%   |
| V-Color             | 3         | 0.04%   |
| Swissbit            | 3         | 0.04%   |
| Silicon Power       | 3         | 0.04%   |
| SHARETRONIC         | 3         | 0.04%   |
| OCZ                 | 3         | 0.04%   |
| Innodisk            | 3         | 0.04%   |
| Avant               | 3         | 0.04%   |
| Unknown (F301)      | 2         | 0.03%   |
| Unknown (07FB)      | 2         | 0.03%   |
| TakeMS              | 2         | 0.03%   |
| Ramos Technology    | 2         | 0.03%   |
| Neo Forza           | 2         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 63        | 0.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 61        | 0.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 61        | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 56        | 0.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 54        | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 52        | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 47        | 0.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 46        | 0.63%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 45        | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 43        | 0.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 42        | 0.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 42        | 0.57%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 39        | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 39        | 0.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 38        | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 37        | 0.5%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 37        | 0.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 37        | 0.5%    |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 37        | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 34        | 0.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 32        | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 31        | 0.42%   |
| Unknown                                                          | 30        | 0.41%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 25        | 0.34%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 25        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 0.34%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 24        | 0.33%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 23        | 0.31%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 23        | 0.31%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 23        | 0.31%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 20        | 0.27%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 20        | 0.27%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 20        | 0.27%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s             | 20        | 0.27%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 19        | 0.26%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 19        | 0.26%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.26%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 19        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2607      | 43.57%  |
| DDR3    | 2161      | 36.12%  |
| DDR2    | 357       | 5.97%   |
| SDRAM   | 206       | 3.44%   |
| LPDDR4  | 200       | 3.34%   |
| Unknown | 166       | 2.77%   |
| LPDDR3  | 123       | 2.06%   |
| DDR     | 59        | 0.99%   |
| DDR5    | 49        | 0.82%   |
| LPDDR5  | 43        | 0.72%   |
| DRAM    | 10        | 0.17%   |
| RAM     | 1         | 0.02%   |
| EEPROM  | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3304      | 55.74%  |
| DIMM         | 2215      | 37.37%  |
| Row Of Chips | 357       | 6.02%   |
| Chip         | 22        | 0.37%   |
| Unknown      | 12        | 0.2%    |
| RIMM         | 9         | 0.15%   |
| FB-DIMM      | 9         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2296      | 35.31%  |
| 4096  | 2001      | 30.77%  |
| 2048  | 943       | 14.5%   |
| 16384 | 804       | 12.36%  |
| 1024  | 287       | 4.41%   |
| 32768 | 125       | 1.92%   |
| 512   | 40        | 0.62%   |
| 65536 | 3         | 0.05%   |
| 256   | 3         | 0.05%   |
| 1     | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1395      | 21.64%  |
| 3200    | 877       | 13.61%  |
| 2667    | 874       | 13.56%  |
| 1333    | 440       | 6.83%   |
| 2400    | 435       | 6.75%   |
| 2133    | 319       | 4.95%   |
| 1334    | 198       | 3.07%   |
| 667     | 187       | 2.9%    |
| 800     | 166       | 2.58%   |
| 3600    | 126       | 1.96%   |
| 1867    | 126       | 1.96%   |
| Unknown | 111       | 1.72%   |
| 1066    | 89        | 1.38%   |
| 4267    | 88        | 1.37%   |
| 1067    | 77        | 1.19%   |
| 3266    | 72        | 1.12%   |
| 2048    | 53        | 0.82%   |
| 4800    | 52        | 0.81%   |
| 1866    | 52        | 0.81%   |
| 3000    | 49        | 0.76%   |
| 2933    | 48        | 0.74%   |
| 2666    | 44        | 0.68%   |
| 6400    | 42        | 0.65%   |
| 1800    | 41        | 0.64%   |
| 3400    | 37        | 0.57%   |
| 533     | 37        | 0.57%   |
| 4199    | 36        | 0.56%   |
| 975     | 24        | 0.37%   |
| 400     | 24        | 0.37%   |
| 3733    | 22        | 0.34%   |
| 2800    | 20        | 0.31%   |
| 3533    | 18        | 0.28%   |
| 4266    | 17        | 0.26%   |
| 3800    | 17        | 0.26%   |
| 3466    | 16        | 0.25%   |
| 3666    | 15        | 0.23%   |
| 333     | 15        | 0.23%   |
| 1639    | 13        | 0.2%    |
| 2465    | 12        | 0.19%   |
| 2000    | 11        | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 113       | 43.63%  |
| Canon                 | 41        | 15.83%  |
| Brother Industries    | 41        | 15.83%  |
| Samsung Electronics   | 32        | 12.36%  |
| Seiko Epson           | 17        | 6.56%   |
| Prolific Technology   | 3         | 1.16%   |
| STMicroelectronics    | 2         | 0.77%   |
| Ricoh                 | 2         | 0.77%   |
| QinHeng Electronics   | 2         | 0.77%   |
| Lexmark International | 2         | 0.77%   |
| Xiaomi                | 1         | 0.39%   |
| Xerox                 | 1         | 0.39%   |
| Kyocera               | 1         | 0.39%   |
| Apple                 | 1         | 0.39%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 11        | 4.23%   |
| Samsung M2070 Series                                      | 9         | 3.46%   |
| HP ENVY 4520 series                                       | 9         | 3.46%   |
| HP DeskJet 3630 series                                    | 9         | 3.46%   |
| HP ENVY Photo 6200 series                                 | 6         | 2.31%   |
| Canon PIXMA MG3600 Series                                 | 6         | 2.31%   |
| HP OfficeJet 3830 series                                  | 5         | 1.92%   |
| HP DeskJet 2620 All-in-One Printer                        | 5         | 1.92%   |
| HP ENVY 5000 series                                       | 4         | 1.54%   |
| HP DeskJet Plus 4100 series                               | 4         | 1.54%   |
| HP DeskJet 3700 series                                    | 4         | 1.54%   |
| Brother HL-2030 Laser Printer                             | 4         | 1.54%   |
| Seiko Epson XP-240 Series                                 | 3         | 1.15%   |
| Samsung M2020 Series                                      | 3         | 1.15%   |
| Samsung CLX-3170 Series                                   | 3         | 1.15%   |
| Prolific PL2305 Parallel Port                             | 3         | 1.15%   |
| HP Deskjet 3050A                                          | 3         | 1.15%   |
| Canon PIXMA MG2500 Series                                 | 3         | 1.15%   |
| Brother Printer                                           | 3         | 1.15%   |
| Brother MFC-L2710DW series                                | 3         | 1.15%   |
| Brother DCP-7055 scanner/printer                          | 3         | 1.15%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 0.77%   |
| Seiko Epson XP-255 257 Series                             | 2         | 0.77%   |
| Seiko Epson XP-2100 Series                                | 2         | 0.77%   |
| Seiko Epson WF-2830 Series                                | 2         | 0.77%   |
| Samsung SCX-3400 Series                                   | 2         | 0.77%   |
| Samsung SCX-3200 Series                                   | 2         | 0.77%   |
| Samsung ML-1660 Series                                    | 2         | 0.77%   |
| Samsung ML-1640 Series Laser Printer                      | 2         | 0.77%   |
| Samsung ML-1630 Series                                    | 2         | 0.77%   |
| Samsung CLX-3180 Series                                   | 2         | 0.77%   |
| QinHeng CH340S                                            | 2         | 0.77%   |
| HP OfficeJet Pro 69                                       | 2         | 0.77%   |
| HP LaserJet 1200                                          | 2         | 0.77%   |
| HP ENVY Pro 6400 series                                   | 2         | 0.77%   |
| HP ENVY 5540 series                                       | 2         | 0.77%   |
| HP ENVY 4500 series                                       | 2         | 0.77%   |
| HP DeskJet F4200 series                                   | 2         | 0.77%   |
| HP DeskJet 5550                                           | 2         | 0.77%   |
| HP Deskjet 3070 B611 series                               | 2         | 0.77%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 57        | 61.29%  |
| Seiko Epson     | 24        | 25.81%  |
| Hewlett-Packard | 8         | 8.6%    |
| AGFA-Gevaert NV | 4         | 4.3%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                            | 9         | 9.68%   |
| Canon CanoScan N1240U/LiDE 30                                 | 9         | 9.68%   |
| Canon CanoScan LiDE 110                                       | 9         | 9.68%   |
| Canon CanoScan LIDE 25                                        | 7         | 7.53%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 4         | 4.3%    |
| Canon CanoScan LiDE 60                                        | 3         | 3.23%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                        | 3         | 3.23%   |
| Canon CanoScan LiDE 200                                       | 3         | 3.23%   |
| AGFA-Gevaert NV SnapScan e20                                  | 3         | 3.23%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 2         | 2.15%   |
| Seiko Epson GT-F700 [Perfection V350]                         | 2         | 2.15%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 2         | 2.15%   |
| Seiko Epson GT-9800F [Perfection 3200]                        | 2         | 2.15%   |
| Seiko Epson GT-6600U [Perfection 610]                         | 2         | 2.15%   |
| HP ScanJet 3570c                                              | 2         | 2.15%   |
| Canon CanoScan N650U/N656U                                    | 2         | 2.15%   |
| Canon CanoScan LiDE 220                                       | 2         | 2.15%   |
| Canon CanoScan LiDE 210                                       | 2         | 2.15%   |
| Canon CanoScan LiDE 120                                       | 2         | 2.15%   |
| Canon CanoScan 4200F                                          | 2         | 2.15%   |
| Seiko Epson Scanner                                           | 1         | 1.08%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]              | 1         | 1.08%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                   | 1         | 1.08%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]       | 1         | 1.08%   |
| Seiko Epson GT-F600 [Perfection 4180]                         | 1         | 1.08%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 1.08%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 1.08%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]            | 1         | 1.08%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]   | 1         | 1.08%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 1.08%   |
| HP ScanJet G4010                                              | 1         | 1.08%   |
| HP ScanJet 5200c                                              | 1         | 1.08%   |
| HP ScanJet 4570c                                              | 1         | 1.08%   |
| HP ScanJet 3500c                                              | 1         | 1.08%   |
| HP ScanJet 2300c                                              | 1         | 1.08%   |
| HP PSC 1200                                                   | 1         | 1.08%   |
| Canon CanoScan LiDE 70                                        | 1         | 1.08%   |
| Canon CanoScan LiDE 100                                       | 1         | 1.08%   |
| Canon CanoScan 9000F Mark II                                  | 1         | 1.08%   |
| Canon CanoScan 4400F                                          | 1         | 1.08%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1176      | 21.76%  |
| IMC Networks                           | 547       | 10.12%  |
| Microdia                               | 500       | 9.25%   |
| Realtek Semiconductor                  | 461       | 8.53%   |
| Logitech                               | 360       | 6.66%   |
| Sunplus Innovation Technology          | 307       | 5.68%   |
| Bison Electronics                      | 234       | 4.33%   |
| Suyin                                  | 197       | 3.64%   |
| Cheng Uei Precision Industry (Foxlink) | 191       | 3.53%   |
| Quanta                                 | 187       | 3.46%   |
| Acer                                   | 159       | 2.94%   |
| Apple                                  | 144       | 2.66%   |
| Lite-On Technology                     | 121       | 2.24%   |
| Syntek                                 | 103       | 1.91%   |
| Alcor Micro                            | 67        | 1.24%   |
| Samsung Electronics                    | 58        | 1.07%   |
| Luxvisions Innotech Limited            | 58        | 1.07%   |
| Microsoft                              | 54        | 1%      |
| Ricoh                                  | 49        | 0.91%   |
| Silicon Motion                         | 45        | 0.83%   |
| Sonix Technology                       | 31        | 0.57%   |
| Guillemot                              | 25        | 0.46%   |
| Z-Star Microelectronics                | 22        | 0.41%   |
| Lenovo                                 | 22        | 0.41%   |
| Primax Electronics                     | 18        | 0.33%   |
| ARC International                      | 17        | 0.31%   |
| Importek                               | 15        | 0.28%   |
| GEMBIRD                                | 15        | 0.28%   |
| Generalplus Technology                 | 14        | 0.26%   |
| DigiTech                               | 14        | 0.26%   |
| Creative Technology                    | 14        | 0.26%   |
| ALi                                    | 12        | 0.22%   |
| Hewlett-Packard                        | 10        | 0.19%   |
| USB Camera                             | 8         | 0.15%   |
| KYE Systems (Mouse Systems)            | 8         | 0.15%   |
| 2M UVC CAMERA                          | 8         | 0.15%   |
| Y Media                                | 7         | 0.13%   |
| Sunplus IT                             | 7         | 0.13%   |
| OmniVision Technologies                | 6         | 0.11%   |
| Cubeternet                             | 6         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 249       | 4.58%   |
| Realtek Integrated_Webcam_HD             | 204       | 3.76%   |
| Chicony Integrated Camera                | 179       | 3.3%    |
| IMC Networks USB2.0 HD UVC WebCam        | 132       | 2.43%   |
| IMC Networks Integrated Camera           | 99        | 1.82%   |
| Chicony HD WebCam                        | 98        | 1.8%    |
| IMC Networks USB2.0 VGA UVC WebCam       | 92        | 1.69%   |
| Logitech Webcam C270                     | 82        | 1.51%   |
| Sunplus Integrated_Webcam_HD             | 77        | 1.42%   |
| Samsung Galaxy A5 (MTP)                  | 58        | 1.07%   |
| Realtek USB Camera                       | 58        | 1.07%   |
| Chicony HP HD Camera                     | 56        | 1.03%   |
| Chicony USB2.0 Camera                    | 55        | 1.01%   |
| Chicony USB2.0 VGA UVC WebCam            | 52        | 0.96%   |
| Bison Integrated Camera                  | 51        | 0.94%   |
| Acer HD Webcam                           | 49        | 0.9%    |
| Syntek Integrated Camera                 | 48        | 0.88%   |
| Apple Built-in iSight                    | 47        | 0.87%   |
| Chicony USB2.0 HD UVC WebCam             | 45        | 0.83%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 44        | 0.81%   |
| Microdia Integrated Webcam               | 43        | 0.79%   |
| Chicony TOSHIBA Web Camera - HD          | 43        | 0.79%   |
| Sunplus Asus Webcam                      | 41        | 0.75%   |
| Logitech HD Pro Webcam C920              | 41        | 0.75%   |
| Chicony HP Truevision HD                 | 41        | 0.75%   |
| Lite-On Integrated Camera                | 40        | 0.74%   |
| Acer Integrated Camera                   | 40        | 0.74%   |
| Chicony USB 2.0 Camera                   | 39        | 0.72%   |
| Chicony HP Truevision HD camera          | 38        | 0.7%    |
| Bison BisonCam,NB Pro                    | 38        | 0.7%    |
| Chicony HP HD Webcam                     | 36        | 0.66%   |
| Quanta HP HD Camera                      | 35        | 0.64%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 32        | 0.59%   |
| Alcor Micro USB 2.0 Camera               | 32        | 0.59%   |
| Logitech HD Webcam C525                  | 31        | 0.57%   |
| Chicony VGA Webcam                       | 30        | 0.55%   |
| Sunplus HD WebCam                        | 29        | 0.53%   |
| Realtek USB2.0 HD UVC WebCam             | 29        | 0.53%   |
| IMC Networks UVC VGA Webcam              | 28        | 0.52%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 28        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 308       | 34.92%  |
| Synaptics                          | 203       | 23.02%  |
| Shenzhen Goodix Technology         | 166       | 18.82%  |
| AuthenTec                          | 66        | 7.48%   |
| Elan Microelectronics              | 48        | 5.44%   |
| LighTuning Technology              | 43        | 4.88%   |
| Upek                               | 35        | 3.97%   |
| STMicroelectronics                 | 11        | 1.25%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.11%   |
| Focal-systems.Corp                 | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 85        | 9.64%   |
| Shenzhen Goodix  FingerPrint Device                                        | 84        | 9.52%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 70        | 7.94%   |
| Shenzhen Goodix FingerPrint                                                | 43        | 4.88%   |
| Shenzhen Goodix Fingerprint Reader                                         | 39        | 4.42%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 37        | 4.2%    |
| Elan ELAN:Fingerprint                                                      | 34        | 3.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 31        | 3.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 3.4%    |
| Validity Sensors VFS491                                                    | 24        | 2.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 2.72%   |
| AuthenTec AES2810                                                          | 24        | 2.72%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 2.27%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 18        | 2.04%   |
| Synaptics UWP WBDI                                                         | 17        | 1.93%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 1.81%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 16        | 1.81%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 15        | 1.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 15        | 1.7%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 1.59%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 1.59%   |
| AuthenTec Fingerprint Sensor                                               | 14        | 1.59%   |
| AuthenTec AES1600                                                          | 14        | 1.59%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 13        | 1.47%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 13        | 1.47%   |
| Synaptics  WBDI                                                            | 12        | 1.36%   |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 1.25%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.25%   |
| Elan ELAN:ARM-M4                                                           | 11        | 1.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.13%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 10        | 1.13%   |
| Unknown                                                                    | 8         | 0.91%   |
| Synaptics WBDI                                                             | 6         | 0.68%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.57%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.57%   |
| Synaptics WBDI Device                                                      | 5         | 0.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.34%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 245       | 54.32%  |
| Alcor Micro               | 92        | 20.4%   |
| O2 Micro                  | 37        | 8.2%    |
| Upek                      | 17        | 3.77%   |
| Lenovo                    | 16        | 3.55%   |
| Hewlett-Packard           | 9         | 2%      |
| Gemalto (was Gemplus)     | 9         | 2%      |
| Aladdin Knowledge Systems | 5         | 1.11%   |
| Yubico.com                | 4         | 0.89%   |
| Clay Logic                | 3         | 0.67%   |
| Chicony Electronics       | 3         | 0.67%   |
| SCM Microsystems          | 2         | 0.44%   |
| Realtek Semiconductor     | 2         | 0.44%   |
| Feitian Technologies      | 2         | 0.44%   |
| ST-Ericsson               | 1         | 0.22%   |
| SpringCard                | 1         | 0.22%   |
| OmniKey                   | 1         | 0.22%   |
| Cherry                    | 1         | 0.22%   |
| Advanced Card Systems     | 1         | 0.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 91        | 20.18%  |
| Broadcom BCM5880 Secure Applications Processor                               | 79        | 17.52%  |
| Broadcom 58200                                                               | 79        | 17.52%  |
| Broadcom 5880                                                                | 51        | 11.31%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 7.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 33        | 7.32%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 3.77%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 3.55%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 9         | 2%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 1.33%   |
| Aladdin Knowledge Systems Token JC                                           | 5         | 1.11%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 4         | 0.89%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 0.89%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 0.67%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.44%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.44%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.44%   |
| ST-Ericsson Chipcard Reader                                                  | 1         | 0.22%   |
| SpringCard Two                                                               | 1         | 0.22%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.22%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.22%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.22%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.22%   |
| Feitian Technologies U2F CCID KB                                             | 1         | 0.22%   |
| Feitian Technologies FT SCR310                                               | 1         | 0.22%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.22%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.22%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.22%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.22%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 6631      | 71.09%  |
| 1     | 2150      | 23.05%  |
| 2     | 431       | 4.62%   |
| 3     | 81        | 0.87%   |
| 4     | 20        | 0.21%   |
| 5     | 7         | 0.08%   |
| 6     | 3         | 0.03%   |
| 9     | 2         | 0.02%   |
| 7     | 2         | 0.02%   |
| 8     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 872       | 26.89%  |
| Graphics card            | 793       | 24.45%  |
| Chipcard                 | 409       | 12.61%  |
| Net/wireless             | 347       | 10.7%   |
| Multimedia controller    | 159       | 4.9%    |
| Communication controller | 126       | 3.89%   |
| Camera                   | 113       | 3.48%   |
| Bluetooth                | 86        | 2.65%   |
| Unassigned class         | 77        | 2.37%   |
| Storage                  | 58        | 1.79%   |
| Sound                    | 50        | 1.54%   |
| Card reader              | 46        | 1.42%   |
| Net/ethernet             | 32        | 0.99%   |
| Modem                    | 21        | 0.65%   |
| Network                  | 17        | 0.52%   |
| Storage/raid             | 7         | 0.22%   |
| Firewire controller      | 7         | 0.22%   |
| Storage/ide              | 5         | 0.15%   |
| Dvb card                 | 5         | 0.15%   |
| Flash memory             | 4         | 0.12%   |
| Wireless                 | 3         | 0.09%   |
| Unclassified device      | 2         | 0.06%   |
| Tv card                  | 2         | 0.06%   |
| Storage/nvme             | 1         | 0.03%   |
| Storage/ata              | 1         | 0.03%   |

