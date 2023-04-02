Linux in Spain - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

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

Total: 3996

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Chuwi         | GemiBook Pro                | [41b51a471d](https://linux-hardware.org/?probe=41b51a471d) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | [fc4116204b](https://linux-hardware.org/?probe=fc4116204b) | Apr 01, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [6ab0a0226d](https://linux-hardware.org/?probe=6ab0a0226d) | Apr 01, 2023 |
| Intel         | Kabylake Platform           | [2b0fd79264](https://linux-hardware.org/?probe=2b0fd79264) | Mar 31, 2023 |
| Acer          | Aspire E5-571               | [45887eb5f3](https://linux-hardware.org/?probe=45887eb5f3) | Mar 31, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [59b2b4e152](https://linux-hardware.org/?probe=59b2b4e152) | Mar 31, 2023 |
| MSI           | Modern 15 A5M               | [2a00bed043](https://linux-hardware.org/?probe=2a00bed043) | Mar 31, 2023 |
| ASUSTek       | X551MA                      | [5ea823d079](https://linux-hardware.org/?probe=5ea823d079) | Mar 31, 2023 |
| Apple         | MacBookPro9,2               | [8c60cf0ec1](https://linux-hardware.org/?probe=8c60cf0ec1) | Mar 31, 2023 |
| Dell          | G15 5515                    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [faa3d2b7ad](https://linux-hardware.org/?probe=faa3d2b7ad) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| ASUSTek       | K53SD                       | [81710aaa51](https://linux-hardware.org/?probe=81710aaa51) | Mar 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [3836173aad](https://linux-hardware.org/?probe=3836173aad) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [46a8636dfd](https://linux-hardware.org/?probe=46a8636dfd) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| ASUSTek       | N550JX                      | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| TEKNOSERVI... | NJ5x_NJ7xLU                 | [2a0feae3f9](https://linux-hardware.org/?probe=2a0feae3f9) | Mar 28, 2023 |
| Notebook      | L140CU                      | [98b71e9790](https://linux-hardware.org/?probe=98b71e9790) | Mar 28, 2023 |
| Dell          | Precision 5540              | [f9e20de07f](https://linux-hardware.org/?probe=f9e20de07f) | Mar 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | [574bb4272c](https://linux-hardware.org/?probe=574bb4272c) | Mar 27, 2023 |
| Dell          | Precision 3571              | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [bddc9116d1](https://linux-hardware.org/?probe=bddc9116d1) | Mar 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [6a8962feba](https://linux-hardware.org/?probe=6a8962feba) | Mar 27, 2023 |
| Samsung       | N150P/N210P/N220P           | [70d943698c](https://linux-hardware.org/?probe=70d943698c) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ca83615d40](https://linux-hardware.org/?probe=ca83615d40) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | [285462b197](https://linux-hardware.org/?probe=285462b197) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | [fc40632056](https://linux-hardware.org/?probe=fc40632056) | Mar 26, 2023 |
| Dell          | G15 5515                    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | [68017924d7](https://linux-hardware.org/?probe=68017924d7) | Mar 26, 2023 |
| HUAWEI        | BOD-WXX9                    | [bee83a6b50](https://linux-hardware.org/?probe=bee83a6b50) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [8a6705ba5a](https://linux-hardware.org/?probe=8a6705ba5a) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d1427e69b3](https://linux-hardware.org/?probe=d1427e69b3) | Mar 26, 2023 |
| Notebook      | NL40_50CU                   | [4870d52d1e](https://linux-hardware.org/?probe=4870d52d1e) | Mar 25, 2023 |
| Gigabyte      | AERO 15 XD                  | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [05b2003fc0](https://linux-hardware.org/?probe=05b2003fc0) | Mar 25, 2023 |
| MSI           | PE62 7RD                    | [de18d40d94](https://linux-hardware.org/?probe=de18d40d94) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| HP            | 255 G7 Notebook PC          | [2097578b64](https://linux-hardware.org/?probe=2097578b64) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [548c06032b](https://linux-hardware.org/?probe=548c06032b) | Mar 24, 2023 |
| ASUSTek       | K52Jr                       | [a88997ecfd](https://linux-hardware.org/?probe=a88997ecfd) | Mar 24, 2023 |
| Dell          | G15 5515                    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| HP            | 2000                        | [9820715e60](https://linux-hardware.org/?probe=9820715e60) | Mar 24, 2023 |
| ASUSTek       | GL752VW                     | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | [4054877ef0](https://linux-hardware.org/?probe=4054877ef0) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | [da37222f12](https://linux-hardware.org/?probe=da37222f12) | Mar 24, 2023 |
| HP            | 2000                        | [87ba6d3696](https://linux-hardware.org/?probe=87ba6d3696) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e4a3f70cbf](https://linux-hardware.org/?probe=e4a3f70cbf) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d55de052b1](https://linux-hardware.org/?probe=d55de052b1) | Mar 23, 2023 |
| Lenovo        | G500 20236                  | [8688a57db6](https://linux-hardware.org/?probe=8688a57db6) | Mar 22, 2023 |
| Packard Be... | EasyNote LJ75               | [1a3b095372](https://linux-hardware.org/?probe=1a3b095372) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| Dell          | G3 3579                     | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Acer          | Aspire ES1-512              | [901b9b1b6b](https://linux-hardware.org/?probe=901b9b1b6b) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| HP            | 250 G4                      | [46e0314fb1](https://linux-hardware.org/?probe=46e0314fb1) | Mar 20, 2023 |
| MSI           | Pulse GL66 12UEK            | [9790d0bb28](https://linux-hardware.org/?probe=9790d0bb28) | Mar 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [77b7fd07a4](https://linux-hardware.org/?probe=77b7fd07a4) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [5c0e12ebd0](https://linux-hardware.org/?probe=5c0e12ebd0) | Mar 19, 2023 |
| Acer          | Aspire E1-532               | [ed3693c1c8](https://linux-hardware.org/?probe=ed3693c1c8) | Mar 18, 2023 |
| Chuwi         | HeroBook Air                | [e9d0a5dd9a](https://linux-hardware.org/?probe=e9d0a5dd9a) | Mar 18, 2023 |
| Chuwi         | GemiBook Pro                | [7bd3a3e64c](https://linux-hardware.org/?probe=7bd3a3e64c) | Mar 18, 2023 |
| HP            | 250 G8 Notebook PC          | [aade64a567](https://linux-hardware.org/?probe=aade64a567) | Mar 18, 2023 |
| Chuwi         | HeroBook                    | [7a70fa6c57](https://linux-hardware.org/?probe=7a70fa6c57) | Mar 17, 2023 |
| MSI           | GF63 Thin 9SC               | [88dcbd2740](https://linux-hardware.org/?probe=88dcbd2740) | Mar 17, 2023 |
| Apple         | MacBook8,1                  | [a3ef4e5a56](https://linux-hardware.org/?probe=a3ef4e5a56) | Mar 16, 2023 |
| Valve         | Jupiter                     | [0a2038deed](https://linux-hardware.org/?probe=0a2038deed) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [428ea81050](https://linux-hardware.org/?probe=428ea81050) | Mar 15, 2023 |
| Acer          | Aspire E5-573G              | [a24986d87d](https://linux-hardware.org/?probe=a24986d87d) | Mar 15, 2023 |
| HP            | Mini 210-1000               | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| MSI           | Katana GF66 12UC            | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Intel         | powered classmate PC        | [891664a0ae](https://linux-hardware.org/?probe=891664a0ae) | Mar 14, 2023 |
| Dell          | Inspiron 14 5410            | [54ff309c3d](https://linux-hardware.org/?probe=54ff309c3d) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| Chuwi         | GemiBook Pro                | [f30cf91b1c](https://linux-hardware.org/?probe=f30cf91b1c) | Mar 13, 2023 |
| Valve         | Jupiter                     | [95598d1841](https://linux-hardware.org/?probe=95598d1841) | Mar 13, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | [a421f89675](https://linux-hardware.org/?probe=a421f89675) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | [4708653fb3](https://linux-hardware.org/?probe=4708653fb3) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | [1a37e14422](https://linux-hardware.org/?probe=1a37e14422) | Mar 11, 2023 |
| Toshiba       | Satellite Pro L300          | [7c5e811612](https://linux-hardware.org/?probe=7c5e811612) | Mar 11, 2023 |
| Valve         | Jupiter                     | [07f6e9ed10](https://linux-hardware.org/?probe=07f6e9ed10) | Mar 10, 2023 |
| Dynabook      | Satellite Pro C50-G         | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| MSI           | GL75 Leopard 10SEK          | [9fdc1bd5c4](https://linux-hardware.org/?probe=9fdc1bd5c4) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Dell          | Latitude E5420              | [9b346e0658](https://linux-hardware.org/?probe=9b346e0658) | Mar 10, 2023 |
| Acer          | Aspire 5750G                | [b4af1eb2cb](https://linux-hardware.org/?probe=b4af1eb2cb) | Mar 10, 2023 |
| Acer          | Aspire M3-581G              | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| Dell          | Latitude E6540              | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Chuwi         | GemiBook Pro                | [23a97367b7](https://linux-hardware.org/?probe=23a97367b7) | Mar 09, 2023 |
| Intel         | powered classmate PC        | [c25d03cf3f](https://linux-hardware.org/?probe=c25d03cf3f) | Mar 09, 2023 |
| Intel         | powered classmate PC        | [8c62787a5b](https://linux-hardware.org/?probe=8c62787a5b) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fd15fc475a](https://linux-hardware.org/?probe=fd15fc475a) | Mar 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [0e054a9861](https://linux-hardware.org/?probe=0e054a9861) | Mar 08, 2023 |
| HP            | Pavilion g6                 | [35f93de82d](https://linux-hardware.org/?probe=35f93de82d) | Mar 08, 2023 |
| ASUSTek       | K53SC                       | [bd182b6d80](https://linux-hardware.org/?probe=bd182b6d80) | Mar 08, 2023 |
| Sony          | SVF1521B1EW                 | [5b5a9dbc40](https://linux-hardware.org/?probe=5b5a9dbc40) | Mar 08, 2023 |
| Acer          | Aspire 5740                 | [37c0c0602c](https://linux-hardware.org/?probe=37c0c0602c) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| Notebook      | N2x0WU                      | [4948392f03](https://linux-hardware.org/?probe=4948392f03) | Mar 06, 2023 |
| Fujitsu Si... | STYLISTIC ST6012            | [0d9314f673](https://linux-hardware.org/?probe=0d9314f673) | Mar 06, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| Intel         | powered classmate PC        | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| Chuwi         | HeroBook Air                | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Lenovo        | ThinkPad E490 20N8002ASP    | [9b91ef4633](https://linux-hardware.org/?probe=9b91ef4633) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| Acer          | TravelMate 5720             | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3a2e77122d](https://linux-hardware.org/?probe=3a2e77122d) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Dell          | G5 5590                     | [75f2235434](https://linux-hardware.org/?probe=75f2235434) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| Apple         | MacBookPro6,2               | [3696f0b49e](https://linux-hardware.org/?probe=3696f0b49e) | Feb 27, 2023 |
| HP            | 250 G7 Notebook PC          | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Notebook                    | [06dba3c8b3](https://linux-hardware.org/?probe=06dba3c8b3) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [02608a8288](https://linux-hardware.org/?probe=02608a8288) | Feb 25, 2023 |
| HP            | EliteBook Folio 9470m       | [8cc1fdf5b4](https://linux-hardware.org/?probe=8cc1fdf5b4) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Acer          | AOD255                      | [f5f5ed9b36](https://linux-hardware.org/?probe=f5f5ed9b36) | Feb 24, 2023 |
| Acer          | Aspire S3                   | [9d0301c490](https://linux-hardware.org/?probe=9d0301c490) | Feb 24, 2023 |
| Valve         | Jupiter                     | [08585b6c97](https://linux-hardware.org/?probe=08585b6c97) | Feb 24, 2023 |
| Lenovo        | ThinkPad X201 3680U6V       | [abcf384939](https://linux-hardware.org/?probe=abcf384939) | Feb 23, 2023 |
| Acer          | AOD255                      | [b4ccf00506](https://linux-hardware.org/?probe=b4ccf00506) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| HP            | Compaq 6720s                | [48cbefb8f6](https://linux-hardware.org/?probe=48cbefb8f6) | Feb 23, 2023 |
| HP            | Compaq 6720s                | [0dac92bb9d](https://linux-hardware.org/?probe=0dac92bb9d) | Feb 23, 2023 |
| HP            | Pavilion 15                 | [48439104ea](https://linux-hardware.org/?probe=48439104ea) | Feb 23, 2023 |
| Gigabyte      | G5 KD                       | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| Sony          | SVF1521N6EW                 | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Acer          | Swift SF514-54T             | [ebbff689ba](https://linux-hardware.org/?probe=ebbff689ba) | Feb 22, 2023 |
| Acer          | TravelMate P256-MG          | [4dbdb229c5](https://linux-hardware.org/?probe=4dbdb229c5) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [50f5c21eeb](https://linux-hardware.org/?probe=50f5c21eeb) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Toshiba       | PORTEGE Z30-A               | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Unknown       | Unknown                     | [e48cf758d0](https://linux-hardware.org/?probe=e48cf758d0) | Feb 19, 2023 |
| Dell          | XPS M1530                   | [c2f2509941](https://linux-hardware.org/?probe=c2f2509941) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [84d8598da2](https://linux-hardware.org/?probe=84d8598da2) | Feb 18, 2023 |
| Sony          | VPCZ13M9E                   | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Chuwi         | GemiBook Pro                | [af76238a5c](https://linux-hardware.org/?probe=af76238a5c) | Feb 17, 2023 |
| Unknown       | Unknown                     | [8cdf723a7d](https://linux-hardware.org/?probe=8cdf723a7d) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| HP            | G61                         | [52bb3c7afb](https://linux-hardware.org/?probe=52bb3c7afb) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| ASUSTek       | GL553VD                     | [97f3fd27fa](https://linux-hardware.org/?probe=97f3fd27fa) | Feb 16, 2023 |
| Acer          | Aspire V3-372               | [bde68b3ed7](https://linux-hardware.org/?probe=bde68b3ed7) | Feb 16, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [abc91903be](https://linux-hardware.org/?probe=abc91903be) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| Lenovo        | ThinkPad T510 43147VG       | [16b032ccc3](https://linux-hardware.org/?probe=16b032ccc3) | Feb 16, 2023 |
| Acer          | Aspire ES1-512              | [a21a70af4c](https://linux-hardware.org/?probe=a21a70af4c) | Feb 15, 2023 |
| Unknown       | Unknown                     | [7fd524ac5b](https://linux-hardware.org/?probe=7fd524ac5b) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| Acer          | Extensa 5230                | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | [fcf87be002](https://linux-hardware.org/?probe=fcf87be002) | Feb 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [a4f13f23ce](https://linux-hardware.org/?probe=a4f13f23ce) | Feb 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [9368822d6a](https://linux-hardware.org/?probe=9368822d6a) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| Gigabyte      | RC14UD                      | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Acer          | Extensa 5220                | [87682be3fd](https://linux-hardware.org/?probe=87682be3fd) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b84a7339e](https://linux-hardware.org/?probe=9b84a7339e) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [20428fc0ed](https://linux-hardware.org/?probe=20428fc0ed) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Google        | Droid                       | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Acer          | Extensa 5230                | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [96dfdd671c](https://linux-hardware.org/?probe=96dfdd671c) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| MSI           | Prestige 15 A12UD           | [9688180ef7](https://linux-hardware.org/?probe=9688180ef7) | Feb 11, 2023 |
| Dell          | Latitude 5290 2-in-1        | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | [c56001eede](https://linux-hardware.org/?probe=c56001eede) | Feb 10, 2023 |
| HP            | Pavilion 15                 | [408fd874e7](https://linux-hardware.org/?probe=408fd874e7) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Acer          | Aspire A515-51              | [d68fb933eb](https://linux-hardware.org/?probe=d68fb933eb) | Feb 09, 2023 |
| Lenovo        | ThinkPad P53s 20N6CTO1WW    | [6b74ce317f](https://linux-hardware.org/?probe=6b74ce317f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| Acer          | Aspire E5-573G              | [8400619736](https://linux-hardware.org/?probe=8400619736) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| Unknown       | Unknown                     | [b541173c03](https://linux-hardware.org/?probe=b541173c03) | Feb 09, 2023 |
| Samsung       | R530/R730                   | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Lenovo        | B50-70 80EU                 | [637336f0d0](https://linux-hardware.org/?probe=637336f0d0) | Feb 07, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [3b6bf45c6b](https://linux-hardware.org/?probe=3b6bf45c6b) | Feb 07, 2023 |
| Unknown       | Unknown                     | [556a341257](https://linux-hardware.org/?probe=556a341257) | Feb 06, 2023 |
| Acer          | Aspire ES1-512              | [75b3a6b384](https://linux-hardware.org/?probe=75b3a6b384) | Feb 06, 2023 |
| MSI           | Stealth 15M B12UE           | [44de7ac1aa](https://linux-hardware.org/?probe=44de7ac1aa) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [a0fea9707e](https://linux-hardware.org/?probe=a0fea9707e) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| WinPAD 110... | I102A                       | [0619bb5a8d](https://linux-hardware.org/?probe=0619bb5a8d) | Feb 04, 2023 |
| Teclast       | F7S                         | [d4384ca831](https://linux-hardware.org/?probe=d4384ca831) | Feb 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2GD00    | [b80bfcae04](https://linux-hardware.org/?probe=b80bfcae04) | Feb 04, 2023 |
| HP            | Pavilion dv6700             | [d3755b3636](https://linux-hardware.org/?probe=d3755b3636) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | [c0434c976e](https://linux-hardware.org/?probe=c0434c976e) | Feb 04, 2023 |
| Acer          | Aspire ES1-512              | [278fbf008f](https://linux-hardware.org/?probe=278fbf008f) | Feb 03, 2023 |
| Valve         | Jupiter                     | [75208bbb30](https://linux-hardware.org/?probe=75208bbb30) | Feb 03, 2023 |
| Acer          | Aspire A315-58              | [32563eeffc](https://linux-hardware.org/?probe=32563eeffc) | Feb 03, 2023 |
| Unknown       | Unknown                     | [8a95ab4f06](https://linux-hardware.org/?probe=8a95ab4f06) | Feb 03, 2023 |
| Acer          | AOD255                      | [1b65896663](https://linux-hardware.org/?probe=1b65896663) | Feb 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [50d19e4206](https://linux-hardware.org/?probe=50d19e4206) | Feb 03, 2023 |
| MSI           | Stealth 15M B12UE           | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| Apple         | MacBookPro11,1              | [44f90bc9ab](https://linux-hardware.org/?probe=44f90bc9ab) | Feb 01, 2023 |
| HP            | Presario CQ57               | [0e34caefa3](https://linux-hardware.org/?probe=0e34caefa3) | Feb 01, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK AH532              | [cf200b9cf1](https://linux-hardware.org/?probe=cf200b9cf1) | Jan 30, 2023 |
| MSI           | GF75 Thin 10UE              | [1177ccc150](https://linux-hardware.org/?probe=1177ccc150) | Jan 30, 2023 |
| Toshiba       | PORTEGE X30-E               | [01f74415b0](https://linux-hardware.org/?probe=01f74415b0) | Jan 30, 2023 |
| HP            | G62                         | [166ddbe627](https://linux-hardware.org/?probe=166ddbe627) | Jan 29, 2023 |
| HP            | ProBook 5320m               | [b8fc81e61c](https://linux-hardware.org/?probe=b8fc81e61c) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T420 4236PN3       | [3b5c51e8b8](https://linux-hardware.org/?probe=3b5c51e8b8) | Jan 29, 2023 |
| Intel         | powered classmate PC        | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| ASUSTek       | X555LD                      | [3a3e1fafdf](https://linux-hardware.org/?probe=3a3e1fafdf) | Jan 28, 2023 |
| Valve         | Jupiter                     | [4a823b2eef](https://linux-hardware.org/?probe=4a823b2eef) | Jan 28, 2023 |
| ASUSTek       | ProArt StudioBook H7600H... | [8e9b78c0e8](https://linux-hardware.org/?probe=8e9b78c0e8) | Jan 28, 2023 |
| ASUSTek       | X751LB                      | [54094ae0a7](https://linux-hardware.org/?probe=54094ae0a7) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| Samsung       | R520/R522/R620              | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Notebook      | N13_N140ZU                  | [94396ecebc](https://linux-hardware.org/?probe=94396ecebc) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| Packard Be... | EasyNote TS44HR             | [2902a743da](https://linux-hardware.org/?probe=2902a743da) | Jan 26, 2023 |
| MSI           | Raider GE76 12UHS           | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| Acer          | Nitro AN515-52              | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| HP            | Pavilion g6                 | [a247cbd6d4](https://linux-hardware.org/?probe=a247cbd6d4) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [07d5199d1c](https://linux-hardware.org/?probe=07d5199d1c) | Jan 25, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [a1a1be6b56](https://linux-hardware.org/?probe=a1a1be6b56) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Samsung       | 305V4A/305V5A               | [0f78cdd47e](https://linux-hardware.org/?probe=0f78cdd47e) | Jan 23, 2023 |
| Chuwi         | GemiBook Pro                | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| Qilive        | QW2214SP                    | [2dba516c91](https://linux-hardware.org/?probe=2dba516c91) | Jan 22, 2023 |
| Clevo         | W150ER                      | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| MSI           | Stealth 15M B12UE           | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| Acer          | Aspire E1-530               | [af5f0b7f58](https://linux-hardware.org/?probe=af5f0b7f58) | Jan 21, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [65919b95b4](https://linux-hardware.org/?probe=65919b95b4) | Jan 20, 2023 |
| Toshiba       | NB520                       | [0252e3bec1](https://linux-hardware.org/?probe=0252e3bec1) | Jan 20, 2023 |
| HP            | Stream Notebook PC 11       | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Dell          | Latitude 5410               | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [0d3da58e45](https://linux-hardware.org/?probe=0d3da58e45) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| Dell          | Latitude 7490               | [390dc07426](https://linux-hardware.org/?probe=390dc07426) | Jan 17, 2023 |
| ASUSTek       | 1018P                       | [45cdf08df5](https://linux-hardware.org/?probe=45cdf08df5) | Jan 16, 2023 |
| HP            | EliteBook 840 G6            | [5a622c4769](https://linux-hardware.org/?probe=5a622c4769) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Acer          | Aspire 5742G                | [5cda575387](https://linux-hardware.org/?probe=5cda575387) | Jan 16, 2023 |
| HUAWEI        | BOD-WXX9                    | [c854a01151](https://linux-hardware.org/?probe=c854a01151) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | [b0abb21613](https://linux-hardware.org/?probe=b0abb21613) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | [623477fd9e](https://linux-hardware.org/?probe=623477fd9e) | Jan 16, 2023 |
| HP            | Victus by Laptop 16-d0xx... | [a8ab10ee00](https://linux-hardware.org/?probe=a8ab10ee00) | Jan 16, 2023 |
| ASUSTek       | K55DR                       | [0dde03d33e](https://linux-hardware.org/?probe=0dde03d33e) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| Sony          | VGN-AR51J                   | [ff9806f1ac](https://linux-hardware.org/?probe=ff9806f1ac) | Jan 15, 2023 |
| Dell          | Latitude E5550              | [ccbb0c484f](https://linux-hardware.org/?probe=ccbb0c484f) | Jan 15, 2023 |
| Dell          | Latitude E5550              | [28471496b4](https://linux-hardware.org/?probe=28471496b4) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | [9816c00c67](https://linux-hardware.org/?probe=9816c00c67) | Jan 15, 2023 |
| HP            | Presario CQ57               | [f223ceb77a](https://linux-hardware.org/?probe=f223ceb77a) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | [812b55536d](https://linux-hardware.org/?probe=812b55536d) | Jan 15, 2023 |
| Apple         | MacBookAir6,2               | [2931eab7f7](https://linux-hardware.org/?probe=2931eab7f7) | Jan 15, 2023 |
| Chuwi         | GemiBook Pro                | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| MSI           | Stealth GS77 12UHS          | [0dba4d0126](https://linux-hardware.org/?probe=0dba4d0126) | Jan 14, 2023 |
| Lenovo        | B51-80 80LM                 | [0c5b712b3e](https://linux-hardware.org/?probe=0c5b712b3e) | Jan 14, 2023 |
| MSI           | Stealth GS77 12UHS          | [6a6636d3ba](https://linux-hardware.org/?probe=6a6636d3ba) | Jan 14, 2023 |
| eMachines     | E725                        | [048d832cef](https://linux-hardware.org/?probe=048d832cef) | Jan 13, 2023 |
| MSI           | Katana GF66 11UC            | [39b5188695](https://linux-hardware.org/?probe=39b5188695) | Jan 12, 2023 |
| HP            | Mini 110-3100               | [e6f11256b8](https://linux-hardware.org/?probe=e6f11256b8) | Jan 12, 2023 |
| Samsung       | RF510/RF410/RF710           | [9d63c96c7a](https://linux-hardware.org/?probe=9d63c96c7a) | Jan 12, 2023 |
| Acer          | Aspire A315-56              | [6ea0b8eab9](https://linux-hardware.org/?probe=6ea0b8eab9) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| ALLDOCUBE     | i1405C                      | [0713c94107](https://linux-hardware.org/?probe=0713c94107) | Jan 11, 2023 |
| Dell          | Inspiron 15-3552            | [e4ca0a9947](https://linux-hardware.org/?probe=e4ca0a9947) | Jan 11, 2023 |
| ASUSTek       | X541UV                      | [41358ca49b](https://linux-hardware.org/?probe=41358ca49b) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| Toshiba       | Satellite Pro NB10-A-12Q    | [f0c82d2046](https://linux-hardware.org/?probe=f0c82d2046) | Jan 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| Acer          | Aspire 5253G                | [930e997f3a](https://linux-hardware.org/?probe=930e997f3a) | Jan 11, 2023 |
| ASUSTek       | K53U                        | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
| Sony          | VPCCW1S1E                   | [5cc5248e94](https://linux-hardware.org/?probe=5cc5248e94) | Jan 10, 2023 |
| HP            | Notebook                    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| MSI           | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [be6a0a28e1](https://linux-hardware.org/?probe=be6a0a28e1) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| MSI           | Modern 14 B10RBSW           | [3dea4fbc97](https://linux-hardware.org/?probe=3dea4fbc97) | Jan 10, 2023 |
| Acer          | Aspire E1-531G              | [2476cc24c1](https://linux-hardware.org/?probe=2476cc24c1) | Jan 10, 2023 |
| ASUSTek       | K53SC                       | [002a8bdf0c](https://linux-hardware.org/?probe=002a8bdf0c) | Jan 09, 2023 |
| Acer          | Aspire E5-551G              | [dc659db065](https://linux-hardware.org/?probe=dc659db065) | Jan 09, 2023 |
| ASUSTek       | K54L                        | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Lenovo        | G480 20150                  | [31f01e01fe](https://linux-hardware.org/?probe=31f01e01fe) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | [532f3544a2](https://linux-hardware.org/?probe=532f3544a2) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| Dell          | Studio 1558                 | [0e01a19694](https://linux-hardware.org/?probe=0e01a19694) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| MSI           | Bravo 17 A4DDK              | [cf73810d98](https://linux-hardware.org/?probe=cf73810d98) | Jan 08, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| ASUSTek       | X540YA                      | [b7021632b6](https://linux-hardware.org/?probe=b7021632b6) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [333358164d](https://linux-hardware.org/?probe=333358164d) | Jan 08, 2023 |
| MSI           | Stealth 15M B12UE           | [c272167e6a](https://linux-hardware.org/?probe=c272167e6a) | Jan 08, 2023 |
| Acer          | TravelMate P256-MG          | [e090a2b61c](https://linux-hardware.org/?probe=e090a2b61c) | Jan 07, 2023 |
| ASUSTek       | K53U                        | [46610b735e](https://linux-hardware.org/?probe=46610b735e) | Jan 07, 2023 |
| Google        | Candy                       | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| Chuwi         | HeroBook Air                | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6e3d10ba74](https://linux-hardware.org/?probe=6e3d10ba74) | Jan 06, 2023 |
| Apple         | MacBookPro4,1               | [9fd9040304](https://linux-hardware.org/?probe=9fd9040304) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| MSI           | Stealth 15M B12UE           | [9e01a37071](https://linux-hardware.org/?probe=9e01a37071) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [2ede2771be](https://linux-hardware.org/?probe=2ede2771be) | Jan 03, 2023 |
| HP            | 250 G2                      | [430425dd1c](https://linux-hardware.org/?probe=430425dd1c) | Jan 03, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [9ba40bc6b5](https://linux-hardware.org/?probe=9ba40bc6b5) | Jan 03, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | [893d1002f6](https://linux-hardware.org/?probe=893d1002f6) | Jan 02, 2023 |
| Samsung       | RF510/RF410/RF710           | [3da2c535f7](https://linux-hardware.org/?probe=3da2c535f7) | Jan 02, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [31a0bdb593](https://linux-hardware.org/?probe=31a0bdb593) | Jan 02, 2023 |
| ASUSTek       | X550VX                      | [e83ccf9576](https://linux-hardware.org/?probe=e83ccf9576) | Jan 01, 2023 |
| Samsung       | RF510/RF410/RF710           | [220854be2e](https://linux-hardware.org/?probe=220854be2e) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | [5ada77ec03](https://linux-hardware.org/?probe=5ada77ec03) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | [817985e5bf](https://linux-hardware.org/?probe=817985e5bf) | Jan 01, 2023 |
| ASUSTek       | K53SC                       | [25912a6795](https://linux-hardware.org/?probe=25912a6795) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| MSI           | Stealth 15M B12UE           | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| HP            | 250 G8 Notebook PC          | [6b8db26ab8](https://linux-hardware.org/?probe=6b8db26ab8) | Dec 30, 2022 |
| Dell          | Latitude 9420               | [3c43afbd50](https://linux-hardware.org/?probe=3c43afbd50) | Dec 29, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [8e201646a8](https://linux-hardware.org/?probe=8e201646a8) | Dec 29, 2022 |
| HP            | ZBook 15 G2                 | [6d1ae8a0c9](https://linux-hardware.org/?probe=6d1ae8a0c9) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2ea31ca86e](https://linux-hardware.org/?probe=2ea31ca86e) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| HP            | Mini 100e                   | [dd184e04ad](https://linux-hardware.org/?probe=dd184e04ad) | Dec 28, 2022 |
| Gigabyte      | AERO 17 XE5                 | [979483f168](https://linux-hardware.org/?probe=979483f168) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| Valve         | Jupiter                     | [15cbe24d03](https://linux-hardware.org/?probe=15cbe24d03) | Dec 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9dec6385d7](https://linux-hardware.org/?probe=9dec6385d7) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d702a6b606](https://linux-hardware.org/?probe=d702a6b606) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| MSI           | MS-7A34                     | [4668f06370](https://linux-hardware.org/?probe=4668f06370) | Dec 26, 2022 |
| HP            | Mini 100e                   | [bf749ac406](https://linux-hardware.org/?probe=bf749ac406) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | [9b26454313](https://linux-hardware.org/?probe=9b26454313) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | [ee842c64a3](https://linux-hardware.org/?probe=ee842c64a3) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| Acer          | Aspire 5732Z                | [96bc08bcbd](https://linux-hardware.org/?probe=96bc08bcbd) | Dec 26, 2022 |
| ASUSTek       | K55VD                       | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| ASUSTek       | ROG Strix G713IC_G713IC     | [72fa60782d](https://linux-hardware.org/?probe=72fa60782d) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [419580e899](https://linux-hardware.org/?probe=419580e899) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| ASUSTek       | K52JT                       | [915e35ba2b](https://linux-hardware.org/?probe=915e35ba2b) | Dec 24, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [2c6f47974f](https://linux-hardware.org/?probe=2c6f47974f) | Dec 23, 2022 |
| Valve         | Jupiter                     | [fc52b9e656](https://linux-hardware.org/?probe=fc52b9e656) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Acer          | Predator PH315-54           | [84bdb8f2eb](https://linux-hardware.org/?probe=84bdb8f2eb) | Dec 23, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c47eaa75b3](https://linux-hardware.org/?probe=c47eaa75b3) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| Acer          | Aspire A315-54              | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | B590 62743PG                | [622f5d6e45](https://linux-hardware.org/?probe=622f5d6e45) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Acer          | Predator PH315-54           | [c291063360](https://linux-hardware.org/?probe=c291063360) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| Dell          | Latitude E5420              | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Toshiba       | Satellite L10W-B-101        | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| Alienware     | x17 R1                      | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1deb35f268](https://linux-hardware.org/?probe=1deb35f268) | Dec 17, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [be60ec8881](https://linux-hardware.org/?probe=be60ec8881) | Dec 17, 2022 |
| Valve         | Jupiter                     | [4a37142af9](https://linux-hardware.org/?probe=4a37142af9) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| HP            | EliteBook 850 G1            | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| ASUSTek       | X550VX                      | [0ee46688fb](https://linux-hardware.org/?probe=0ee46688fb) | Dec 14, 2022 |
| MSI           | GF63 Thin 9SC               | [e8dcf65234](https://linux-hardware.org/?probe=e8dcf65234) | Dec 14, 2022 |
| Dell          | Vostro 14 5410              | [d858d468cc](https://linux-hardware.org/?probe=d858d468cc) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Dell          | XPS 15 9550                 | [61905b4fac](https://linux-hardware.org/?probe=61905b4fac) | Dec 13, 2022 |
| Acer          | Nitro AN515-58              | [9c13949220](https://linux-hardware.org/?probe=9c13949220) | Dec 13, 2022 |
| Dell          | Inspiron 3493               | [8ee8a5a64c](https://linux-hardware.org/?probe=8ee8a5a64c) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | Notebook                    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [d262eae22d](https://linux-hardware.org/?probe=d262eae22d) | Dec 12, 2022 |
| Unknown       | Unknown                     | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| MSI           | Modern 14 A10RB             | [849203accb](https://linux-hardware.org/?probe=849203accb) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| HP            | Laptop 15-bw0xx             | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| HP            | 620                         | [65ef44647a](https://linux-hardware.org/?probe=65ef44647a) | Dec 11, 2022 |
| Lenovo        | G710                        | [e1c54d8bc8](https://linux-hardware.org/?probe=e1c54d8bc8) | Dec 10, 2022 |
| Lenovo        | G710                        | [b2231f4343](https://linux-hardware.org/?probe=b2231f4343) | Dec 10, 2022 |
| Valve         | Jupiter                     | [e8e7f4358d](https://linux-hardware.org/?probe=e8e7f4358d) | Dec 10, 2022 |
| HP            | ProBook 650 G2              | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d7b8344d86](https://linux-hardware.org/?probe=d7b8344d86) | Dec 09, 2022 |
| Dell          | Latitude E6500              | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | [3327de3dc5](https://linux-hardware.org/?probe=3327de3dc5) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2A50... | [082e17aab7](https://linux-hardware.org/?probe=082e17aab7) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [302b36a67e](https://linux-hardware.org/?probe=302b36a67e) | Dec 05, 2022 |
| Toshiba       | PORTEGE M800                | [baf04ad2b3](https://linux-hardware.org/?probe=baf04ad2b3) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d69f4daaa6](https://linux-hardware.org/?probe=d69f4daaa6) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | [5ae5166847](https://linux-hardware.org/?probe=5ae5166847) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | [1a52a1c699](https://linux-hardware.org/?probe=1a52a1c699) | Dec 05, 2022 |
| Valve         | Jupiter                     | [a1975d14f5](https://linux-hardware.org/?probe=a1975d14f5) | Dec 04, 2022 |
| Acer          | Aspire E5-573               | [30f8bd2ae9](https://linux-hardware.org/?probe=30f8bd2ae9) | Dec 04, 2022 |
| MSI           | GE72 6QD                    | [257a807435](https://linux-hardware.org/?probe=257a807435) | Dec 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c544d40ecb](https://linux-hardware.org/?probe=c544d40ecb) | Dec 02, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Acer          | Aspire A315-34              | [6bf371252b](https://linux-hardware.org/?probe=6bf371252b) | Nov 30, 2022 |
| ASUSTek       | UX550VD                     | [a3f2aafbf1](https://linux-hardware.org/?probe=a3f2aafbf1) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b4aeee5799](https://linux-hardware.org/?probe=b4aeee5799) | Nov 30, 2022 |
| HP            | EliteBook 860 16 inch G9... | [dda393ca54](https://linux-hardware.org/?probe=dda393ca54) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| Acer          | Aspire A315-34              | [56bb76fb28](https://linux-hardware.org/?probe=56bb76fb28) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [ddad96715a](https://linux-hardware.org/?probe=ddad96715a) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| HP            | Notebook                    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| HP            | ProBook 450 G5              | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | [d5f03d47ba](https://linux-hardware.org/?probe=d5f03d47ba) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | [e0701bc81d](https://linux-hardware.org/?probe=e0701bc81d) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | [8bd9aae635](https://linux-hardware.org/?probe=8bd9aae635) | Nov 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [c95bbb16de](https://linux-hardware.org/?probe=c95bbb16de) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | [3be194cb8a](https://linux-hardware.org/?probe=3be194cb8a) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| ASUSTek       | X555YA                      | [0e9bb436b5](https://linux-hardware.org/?probe=0e9bb436b5) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [419b7f448b](https://linux-hardware.org/?probe=419b7f448b) | Nov 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | [4393448090](https://linux-hardware.org/?probe=4393448090) | Nov 25, 2022 |
| HP            | ProBook 430 G3              | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| ASUSTek       | 1001PX                      | [9626b2b4c5](https://linux-hardware.org/?probe=9626b2b4c5) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| MSI           | Modern 14 A10M              | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| Apple         | MacBook5,1                  | [f2ecb3f4a8](https://linux-hardware.org/?probe=f2ecb3f4a8) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | [347af27c05](https://linux-hardware.org/?probe=347af27c05) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8bd0cdff15](https://linux-hardware.org/?probe=8bd0cdff15) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Apple         | MacBook5,1                  | [9311687e42](https://linux-hardware.org/?probe=9311687e42) | Nov 19, 2022 |
| Toshiba       | Satellite P50-B-10Z         | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Acer          | Extensa 5220                | [0bf5f727ac](https://linux-hardware.org/?probe=0bf5f727ac) | Nov 19, 2022 |
| Acer          | Aspire E1-572G              | [36c1e37d05](https://linux-hardware.org/?probe=36c1e37d05) | Nov 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea12bf4774](https://linux-hardware.org/?probe=ea12bf4774) | Nov 18, 2022 |
| HP            | Elite x2 1012 G1            | [ef366c64fe](https://linux-hardware.org/?probe=ef366c64fe) | Nov 18, 2022 |
| Samsung       | R610                        | [b6c7aa2939](https://linux-hardware.org/?probe=b6c7aa2939) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| Apple         | MacBookPro14,1              | [248fcb5f13](https://linux-hardware.org/?probe=248fcb5f13) | Nov 17, 2022 |
| Acer          | Extensa 5220                | [8e9441be64](https://linux-hardware.org/?probe=8e9441be64) | Nov 17, 2022 |
| Toshiba       | Satellite L10W-B-101        | [544ad40774](https://linux-hardware.org/?probe=544ad40774) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [b139741f4f](https://linux-hardware.org/?probe=b139741f4f) | Nov 15, 2022 |
| Dell          | Latitude E5470              | [ae3d91be5a](https://linux-hardware.org/?probe=ae3d91be5a) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| ALURIN        | PR1-M146                    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [722455f99d](https://linux-hardware.org/?probe=722455f99d) | Nov 14, 2022 |
| Lenovo        | V14-ADA 82C6                | [7971c5cda7](https://linux-hardware.org/?probe=7971c5cda7) | Nov 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [465bc481e2](https://linux-hardware.org/?probe=465bc481e2) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| Dell          | G3 3579                     | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Dell          | XPS 13 9343                 | [fed6627c3e](https://linux-hardware.org/?probe=fed6627c3e) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [76609a3bd3](https://linux-hardware.org/?probe=76609a3bd3) | Nov 12, 2022 |
| HP            | Pavilion 15                 | [f6125d7605](https://linux-hardware.org/?probe=f6125d7605) | Nov 11, 2022 |
| HP            | Pavilion 15                 | [a598e64905](https://linux-hardware.org/?probe=a598e64905) | Nov 11, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| LG Electro... | 16Z90Q-G.AD78B              | [e5129b607e](https://linux-hardware.org/?probe=e5129b607e) | Nov 09, 2022 |
| HP            | Pavilion g7                 | [3a18145808](https://linux-hardware.org/?probe=3a18145808) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [94746f0b72](https://linux-hardware.org/?probe=94746f0b72) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [61bf21f7dd](https://linux-hardware.org/?probe=61bf21f7dd) | Nov 09, 2022 |
| Valve         | Jupiter                     | [3e3e947f9e](https://linux-hardware.org/?probe=3e3e947f9e) | Nov 08, 2022 |
| HUAWEI        | BOD-WXX9                    | [c36ab935b5](https://linux-hardware.org/?probe=c36ab935b5) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [bbb94242ec](https://linux-hardware.org/?probe=bbb94242ec) | Nov 07, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [000b225d22](https://linux-hardware.org/?probe=000b225d22) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [80dc1502e1](https://linux-hardware.org/?probe=80dc1502e1) | Nov 06, 2022 |
| LG Electro... | 15Z990-V.AA78B              | [5ca4c426d8](https://linux-hardware.org/?probe=5ca4c426d8) | Nov 05, 2022 |
| HP            | Laptop 15-bs0xx             | [431f0124a5](https://linux-hardware.org/?probe=431f0124a5) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Valve         | Jupiter                     | [5c5b229108](https://linux-hardware.org/?probe=5c5b229108) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| HP            | Compaq Presario A900        | [4c48500597](https://linux-hardware.org/?probe=4c48500597) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [bd3b4f723e](https://linux-hardware.org/?probe=bd3b4f723e) | Nov 04, 2022 |
| HP            | EliteBook Folio 1040 G1     | [1582ffa7f2](https://linux-hardware.org/?probe=1582ffa7f2) | Nov 04, 2022 |
| ASUSTek       | K50IN                       | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| Valve         | Jupiter                     | [62160ec2e5](https://linux-hardware.org/?probe=62160ec2e5) | Nov 03, 2022 |
| HP            | G62                         | [a00ba1aae7](https://linux-hardware.org/?probe=a00ba1aae7) | Nov 03, 2022 |
| HP            | 250 G4                      | [ff497e0d4c](https://linux-hardware.org/?probe=ff497e0d4c) | Nov 02, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [44e281e52c](https://linux-hardware.org/?probe=44e281e52c) | Nov 02, 2022 |
| Valve         | Jupiter                     | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Samsung       | 305V4A/305V5A               | [5df933ddda](https://linux-hardware.org/?probe=5df933ddda) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Toshiba       | Satellite L50-C             | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | [3db734a533](https://linux-hardware.org/?probe=3db734a533) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Panasonic     | CF-19RDRCHH7                | [99e94a7708](https://linux-hardware.org/?probe=99e94a7708) | Oct 31, 2022 |
| Fujitsu       | LIFEBOOK T904               | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [8dfb7265a9](https://linux-hardware.org/?probe=8dfb7265a9) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| Notebook      | W230SD                      | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b8cfddfcbf](https://linux-hardware.org/?probe=b8cfddfcbf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| Apple         | MacBookPro16,1              | [eba036175b](https://linux-hardware.org/?probe=eba036175b) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8429395d7d](https://linux-hardware.org/?probe=8429395d7d) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [366e5edec9](https://linux-hardware.org/?probe=366e5edec9) | Oct 28, 2022 |
| HP            | EliteBook 820 G2            | [7056cf1574](https://linux-hardware.org/?probe=7056cf1574) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| MSI           | GE66 Raider 10UE            | [334d883dd3](https://linux-hardware.org/?probe=334d883dd3) | Oct 27, 2022 |
| Acer          | Aspire A315-21              | [14f5f5ceeb](https://linux-hardware.org/?probe=14f5f5ceeb) | Oct 26, 2022 |
| Lenovo        | G500 20236                  | [b5508a855e](https://linux-hardware.org/?probe=b5508a855e) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [81a4c0f5d5](https://linux-hardware.org/?probe=81a4c0f5d5) | Oct 26, 2022 |
| Acer          | Aspire ES1-511              | [0db2597f65](https://linux-hardware.org/?probe=0db2597f65) | Oct 26, 2022 |
| Apple         | MacBook5,1                  | [a7fa475b56](https://linux-hardware.org/?probe=a7fa475b56) | Oct 25, 2022 |
| ALURIN        | PR1-M146                    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490s 20NYS6FL0... | [ef0cad4118](https://linux-hardware.org/?probe=ef0cad4118) | Oct 25, 2022 |
| ASUSTek       | X550EA                      | [6a7b7a70a5](https://linux-hardware.org/?probe=6a7b7a70a5) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | [e2c2ac571f](https://linux-hardware.org/?probe=e2c2ac571f) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2991b1a2cf](https://linux-hardware.org/?probe=2991b1a2cf) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2015c6f7fc](https://linux-hardware.org/?probe=2015c6f7fc) | Oct 23, 2022 |
| HP            | Pavilion g6                 | [55a5d78e1c](https://linux-hardware.org/?probe=55a5d78e1c) | Oct 22, 2022 |
| HUAWEI        | RLEF-XX                     | [5bebcbd76d](https://linux-hardware.org/?probe=5bebcbd76d) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| HP            | 15                          | [937cf874b0](https://linux-hardware.org/?probe=937cf874b0) | Oct 21, 2022 |
| Toshiba       | Satellite P50-B-103         | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [85a58721ed](https://linux-hardware.org/?probe=85a58721ed) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| ASUSTek       | K54C                        | [124cad3faf](https://linux-hardware.org/?probe=124cad3faf) | Oct 20, 2022 |
| Valve         | Jupiter                     | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| MSI           | Modern 14 C12M              | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| HP            | Pavilion Notebook           | [462a0f1d13](https://linux-hardware.org/?probe=462a0f1d13) | Oct 18, 2022 |
| Chuwi         | HeroBook Air                | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Dell          | Latitude E6330              | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| SLIMBOOK      | TITAN                       | [87177b2371](https://linux-hardware.org/?probe=87177b2371) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| MSI           | Stealth GS66 12UGS          | [10f52ac957](https://linux-hardware.org/?probe=10f52ac957) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| ASUSTek       | X540LA                      | [1680f919c8](https://linux-hardware.org/?probe=1680f919c8) | Oct 15, 2022 |
| Google        | Liara                       | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| Qilive        | QW20141BSP                  | [a497e419fe](https://linux-hardware.org/?probe=a497e419fe) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| VANT          | MOOVE3-15                   | [ed3f1f2728](https://linux-hardware.org/?probe=ed3f1f2728) | Oct 13, 2022 |
| HP            | Laptop 17-cn2xxx            | [55bdfc4aef](https://linux-hardware.org/?probe=55bdfc4aef) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3e43886af3](https://linux-hardware.org/?probe=3e43886af3) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| Dell          | Latitude E7240              | [3f9f9c38d1](https://linux-hardware.org/?probe=3f9f9c38d1) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [a0833e04a4](https://linux-hardware.org/?probe=a0833e04a4) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [dc29e6568f](https://linux-hardware.org/?probe=dc29e6568f) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [71ef13e7f5](https://linux-hardware.org/?probe=71ef13e7f5) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [b188c7c0dc](https://linux-hardware.org/?probe=b188c7c0dc) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [e2b4876c6e](https://linux-hardware.org/?probe=e2b4876c6e) | Oct 07, 2022 |
| HUAWEI        | RLEF-XX                     | [81f1574f73](https://linux-hardware.org/?probe=81f1574f73) | Oct 07, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [3ade8f820b](https://linux-hardware.org/?probe=3ade8f820b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [c3ecfbe57b](https://linux-hardware.org/?probe=c3ecfbe57b) | Oct 07, 2022 |
| Toshiba       | Satellite R830              | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| MSI           | Creator Z16 A11UE           | [ad24aa79d7](https://linux-hardware.org/?probe=ad24aa79d7) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| Valve         | Jupiter                     | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Toshiba       | Satellite L10W-B-101        | [403446f5ce](https://linux-hardware.org/?probe=403446f5ce) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| HP            | Pavilion Notebook           | [17c8e22c3b](https://linux-hardware.org/?probe=17c8e22c3b) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | Notebook                    | [58dd536d7d](https://linux-hardware.org/?probe=58dd536d7d) | Oct 04, 2022 |
| Acer          | Extensa 5230                | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Acer          | Aspire 5253G                | [6bd00aec7a](https://linux-hardware.org/?probe=6bd00aec7a) | Oct 04, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Samsung       | N248P/N143P                 | [56e4d025af](https://linux-hardware.org/?probe=56e4d025af) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [9fd2d2169a](https://linux-hardware.org/?probe=9fd2d2169a) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [1c42236e47](https://linux-hardware.org/?probe=1c42236e47) | Sep 30, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Valve         | Jupiter                     | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Valve         | Jupiter                     | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| Chuwi         | HeroBook Air                | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | [8c4c7f3dc1](https://linux-hardware.org/?probe=8c4c7f3dc1) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E548               | [bf70c9dd7b](https://linux-hardware.org/?probe=bf70c9dd7b) | Sep 27, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e39766ed4d](https://linux-hardware.org/?probe=e39766ed4d) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| Dell          | XPS 13 7390                 | [cfebe9461d](https://linux-hardware.org/?probe=cfebe9461d) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Intel         | H81U                        | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [49b0161bf0](https://linux-hardware.org/?probe=49b0161bf0) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| Lenovo        | ThinkPad T450 20BV001CSP    | [9233c6db8f](https://linux-hardware.org/?probe=9233c6db8f) | Sep 24, 2022 |
| HP            | 15                          | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Unknown       | Unknown                     | [4a1323c81e](https://linux-hardware.org/?probe=4a1323c81e) | Sep 24, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b73b2224d1](https://linux-hardware.org/?probe=b73b2224d1) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [67ec6c656b](https://linux-hardware.org/?probe=67ec6c656b) | Sep 23, 2022 |
| Acer          | TravelMate P256-MG          | [0a7c58d00a](https://linux-hardware.org/?probe=0a7c58d00a) | Sep 23, 2022 |
| Sony          | VPCEB1Z1E                   | [37fea84df6](https://linux-hardware.org/?probe=37fea84df6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| HP            | Presario CQ57               | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [849246d9f3](https://linux-hardware.org/?probe=849246d9f3) | Sep 20, 2022 |
| Dell          | Latitude E7240              | [6db3839532](https://linux-hardware.org/?probe=6db3839532) | Sep 20, 2022 |
| Dell          | Latitude E7240              | [21dc4700da](https://linux-hardware.org/?probe=21dc4700da) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | [329f95e326](https://linux-hardware.org/?probe=329f95e326) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | [5891712135](https://linux-hardware.org/?probe=5891712135) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| Dell          | Latitude 3420               | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | Laptop 15-db0xxx            | [c4a7f1814f](https://linux-hardware.org/?probe=c4a7f1814f) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| HP            | Compaq 6720s                | [75bc6df1df](https://linux-hardware.org/?probe=75bc6df1df) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Valve         | Jupiter                     | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| AXDIA Inte... | WINPAD V10                  | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Dell          | Latitude D630               | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| INFINITY      | Unknown                     | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| Toshiba       | Satellite P50-B-11L         | [eba4212008](https://linux-hardware.org/?probe=eba4212008) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [eb169c543e](https://linux-hardware.org/?probe=eb169c543e) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| Acer          | Aspire 5742                 | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Samsung       | 305V4A/305V5A               | [ba2ad7bf06](https://linux-hardware.org/?probe=ba2ad7bf06) | Sep 13, 2022 |
| Dell          | Latitude 7420               | [84f0ebcfea](https://linux-hardware.org/?probe=84f0ebcfea) | Sep 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [aa9d57c27e](https://linux-hardware.org/?probe=aa9d57c27e) | Sep 13, 2022 |
| MSI           | Prestige 14 A11SCX          | [0c0264943f](https://linux-hardware.org/?probe=0c0264943f) | Sep 13, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [b6b3f2dce1](https://linux-hardware.org/?probe=b6b3f2dce1) | Sep 13, 2022 |
| ASUSTek       | X200LA                      | [e0947fe5c7](https://linux-hardware.org/?probe=e0947fe5c7) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| Toshiba       | Satellite A500              | [0d96df6375](https://linux-hardware.org/?probe=0d96df6375) | Sep 13, 2022 |
| Toshiba       | Satellite L50D-B            | [2d09796251](https://linux-hardware.org/?probe=2d09796251) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | [390223e073](https://linux-hardware.org/?probe=390223e073) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | [0d1c08d02b](https://linux-hardware.org/?probe=0d1c08d02b) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| Dell          | Latitude E7240              | [2976e9106e](https://linux-hardware.org/?probe=2976e9106e) | Sep 10, 2022 |
| AXDIA Inte... | WINPAD V10                  | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| HP            | Compaq 8510w                | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| HP            | Laptop 15s-eq1xxx           | [efc8c6b2e7](https://linux-hardware.org/?probe=efc8c6b2e7) | Sep 08, 2022 |
| Lenovo        | B570e 521524G               | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2959121934](https://linux-hardware.org/?probe=2959121934) | Sep 07, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | [2817268e91](https://linux-hardware.org/?probe=2817268e91) | Sep 07, 2022 |
| HP            | ProBook 430 G6              | [99de13d37c](https://linux-hardware.org/?probe=99de13d37c) | Sep 07, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| Lenovo        | V145-15AST 81MT             | [90d59bf651](https://linux-hardware.org/?probe=90d59bf651) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| MSI           | Prestige 15 A10SC           | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| Chuwi         | Hi10 Go                     | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Notebook      | N141CU                      | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | Compaq 8510w                | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| MSI           | Katana GF66 12UC            | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [f25f0f5499](https://linux-hardware.org/?probe=f25f0f5499) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [7b6028e52d](https://linux-hardware.org/?probe=7b6028e52d) | Sep 01, 2022 |
| LG Electro... | 14Z990-V.AP72B              | [8c67c188a1](https://linux-hardware.org/?probe=8c67c188a1) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c9fcbe9935](https://linux-hardware.org/?probe=c9fcbe9935) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [52efef286f](https://linux-hardware.org/?probe=52efef286f) | Sep 01, 2022 |
| HP            | Laptop 15-db0xxx            | [42879ce5cf](https://linux-hardware.org/?probe=42879ce5cf) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | [3c7e97b769](https://linux-hardware.org/?probe=3c7e97b769) | Aug 31, 2022 |
| Notebook      | N24_25JU                    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| HP            | Compaq 8510w                | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| ASUSTek       | F3F                         | [57c5732aaa](https://linux-hardware.org/?probe=57c5732aaa) | Aug 30, 2022 |
| HP            | Notebook                    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Chuwi         | GemiBook                    | [abca00f582](https://linux-hardware.org/?probe=abca00f582) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| Notebook      | NL4x_NL5xLU                 | [df4630db27](https://linux-hardware.org/?probe=df4630db27) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Dell          | Vostro 3500                 | [e4cd019582](https://linux-hardware.org/?probe=e4cd019582) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | [634c973e53](https://linux-hardware.org/?probe=634c973e53) | Aug 27, 2022 |
| speedmaste... | E131x series                | [69d287c029](https://linux-hardware.org/?probe=69d287c029) | Aug 26, 2022 |
| ASUSTek       | K52Jc                       | [5c10927d11](https://linux-hardware.org/?probe=5c10927d11) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [292f932c92](https://linux-hardware.org/?probe=292f932c92) | Aug 25, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| HUAWEI        | NBD-WXX9                    | [254b378771](https://linux-hardware.org/?probe=254b378771) | Aug 23, 2022 |
| Acer          | Aspire 5742                 | [97c61c3095](https://linux-hardware.org/?probe=97c61c3095) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [ae3bcc6b88](https://linux-hardware.org/?probe=ae3bcc6b88) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [b45c0fb9fa](https://linux-hardware.org/?probe=b45c0fb9fa) | Aug 22, 2022 |
| Dell          | Vostro 3550                 | [230033da23](https://linux-hardware.org/?probe=230033da23) | Aug 22, 2022 |
| Lenovo        | M30-70 80H8                 | [d254ca63b4](https://linux-hardware.org/?probe=d254ca63b4) | Aug 22, 2022 |
| Chuwi         | GemiBook Pro                | [03ed2d6805](https://linux-hardware.org/?probe=03ed2d6805) | Aug 22, 2022 |
| SLIMBOOK      | PROX14-AMD                  | [f01fb4784c](https://linux-hardware.org/?probe=f01fb4784c) | Aug 21, 2022 |
| Acer          | Aspire A517-52              | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| VANT          | MOOVE3-15                   | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| HP            | 250 G7 Notebook PC          | [ec15e7b0c5](https://linux-hardware.org/?probe=ec15e7b0c5) | Aug 19, 2022 |
| Apple         | MacBookPro5,5               | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| HP            | EliteBook 840 G6            | [8af519565f](https://linux-hardware.org/?probe=8af519565f) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| Chuwi         | HeroBook Air                | [6e13e6abe8](https://linux-hardware.org/?probe=6e13e6abe8) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| ASUSTek       | N75SF                       | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [1cdee0174f](https://linux-hardware.org/?probe=1cdee0174f) | Aug 16, 2022 |
| Valve         | Jupiter                     | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [6132aea83b](https://linux-hardware.org/?probe=6132aea83b) | Aug 16, 2022 |
| Valve         | Jupiter                     | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| GPD           | G1618-03                    | [64b056ddb1](https://linux-hardware.org/?probe=64b056ddb1) | Aug 14, 2022 |
| GPD           | G1618-03                    | [7316acf7a6](https://linux-hardware.org/?probe=7316acf7a6) | Aug 14, 2022 |
| Acer          | Aspire E5-521               | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | [5640964630](https://linux-hardware.org/?probe=5640964630) | Aug 12, 2022 |
| HP            | Laptop 15-da0xxx            | [70ea8b51c8](https://linux-hardware.org/?probe=70ea8b51c8) | Aug 12, 2022 |
| Dell          | Latitude D630               | [3650f52bba](https://linux-hardware.org/?probe=3650f52bba) | Aug 11, 2022 |
| Toshiba       | TECRA R950                  | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| ASUSTek       | X555LAB                     | [9c41cf4c2c](https://linux-hardware.org/?probe=9c41cf4c2c) | Aug 10, 2022 |
| HP            | Laptop 15-da0xxx            | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| HP            | EliteBook 2540p             | [14e0900f42](https://linux-hardware.org/?probe=14e0900f42) | Aug 06, 2022 |
| Dell          | Latitude 5520               | [33888d0477](https://linux-hardware.org/?probe=33888d0477) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | [ca0e99f941](https://linux-hardware.org/?probe=ca0e99f941) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| Acer          | Aspire 9410                 | [0d433f48f4](https://linux-hardware.org/?probe=0d433f48f4) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [af83e534ff](https://linux-hardware.org/?probe=af83e534ff) | Aug 04, 2022 |
| Dell          | Latitude 5420               | [d4717e9bb1](https://linux-hardware.org/?probe=d4717e9bb1) | Aug 04, 2022 |
| ASUSTek       | GL752VW                     | [ff8fd29d96](https://linux-hardware.org/?probe=ff8fd29d96) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [5ab3e7f74f](https://linux-hardware.org/?probe=5ab3e7f74f) | Aug 03, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [02d4876457](https://linux-hardware.org/?probe=02d4876457) | Aug 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5d4fdde00](https://linux-hardware.org/?probe=f5d4fdde00) | Aug 02, 2022 |
| ASUSTek       | X540SA                      | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| Dell          | Latitude 7420               | [d498af2db5](https://linux-hardware.org/?probe=d498af2db5) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Chuwi         | GemiBook Pro                | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| HP            | Compaq 8510p                | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| Unknown       | Unknown                     | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [94f1822d11](https://linux-hardware.org/?probe=94f1822d11) | Jul 26, 2022 |
| Dell          | XPS 15 7590                 | [f1c4c81832](https://linux-hardware.org/?probe=f1c4c81832) | Jul 26, 2022 |
| eMachines     | D730                        | [4cba9849a0](https://linux-hardware.org/?probe=4cba9849a0) | Jul 26, 2022 |
| Alienware     | m15 R4                      | [2f80ebdd19](https://linux-hardware.org/?probe=2f80ebdd19) | Jul 26, 2022 |
| Acer          | Aspire 5749                 | [fa3b08453b](https://linux-hardware.org/?probe=fa3b08453b) | Jul 25, 2022 |
| Dell          | Latitude E6540              | [281f1b4a30](https://linux-hardware.org/?probe=281f1b4a30) | Jul 24, 2022 |
| HP            | Notebook                    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| HP            | Stream Notebook             | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Unknown       | Unknown                     | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| Lenovo        | ThinkPad T450 20BUS04A0B    | [afc6d3d00a](https://linux-hardware.org/?probe=afc6d3d00a) | Jul 22, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| Dell          | XPS 15 9510                 | [cf3548c6b4](https://linux-hardware.org/?probe=cf3548c6b4) | Jul 20, 2022 |
| Notebook      | W350STQ/W370ST              | [613b1f9d19](https://linux-hardware.org/?probe=613b1f9d19) | Jul 20, 2022 |
| Acer          | Aspire 5750G                | [08beab61a7](https://linux-hardware.org/?probe=08beab61a7) | Jul 18, 2022 |
| HUAWEI        | MateBook D                  | [5d7a616dd1](https://linux-hardware.org/?probe=5d7a616dd1) | Jul 18, 2022 |
| Toshiba       | Satellite Pro A50-C         | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| ASUSTek       | GL752VW                     | [b13a184720](https://linux-hardware.org/?probe=b13a184720) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| Dell          | Latitude 7390               | [fca3ed2ef5](https://linux-hardware.org/?probe=fca3ed2ef5) | Jul 17, 2022 |
| Toshiba       | Satellite L670              | [d753323f22](https://linux-hardware.org/?probe=d753323f22) | Jul 16, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| Valve         | Jupiter                     | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| Chuwi         | HeroBook Air                | [8f50476a9d](https://linux-hardware.org/?probe=8f50476a9d) | Jul 15, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| Notebook      | W350STQ/W370ST              | [86daf7b30d](https://linux-hardware.org/?probe=86daf7b30d) | Jul 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [046794ca90](https://linux-hardware.org/?probe=046794ca90) | Jul 15, 2022 |
| Apple         | MacBookAir7,2               | [19c5e2272a](https://linux-hardware.org/?probe=19c5e2272a) | Jul 14, 2022 |
| Dell          | Latitude E5540              | [d6a6448930](https://linux-hardware.org/?probe=d6a6448930) | Jul 14, 2022 |
| Chuwi         | HeroBook Air                | [d76b0db2ca](https://linux-hardware.org/?probe=d76b0db2ca) | Jul 13, 2022 |
| MSI           | Modern 15 A5M               | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| MSI           | Katana GF66 12UD            | [2822036910](https://linux-hardware.org/?probe=2822036910) | Jul 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6231802178](https://linux-hardware.org/?probe=6231802178) | Jul 12, 2022 |
| MSI           | Katana GF66 12UD            | [470a18c94b](https://linux-hardware.org/?probe=470a18c94b) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| MSI           | GL73 8SE                    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f3de47ac1f](https://linux-hardware.org/?probe=f3de47ac1f) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| Dell          | Latitude 5285               | [1faeae7b00](https://linux-hardware.org/?probe=1faeae7b00) | Jul 07, 2022 |
| Chuwi         | GemiBook Pro                | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire 5742G                | [3d76189da7](https://linux-hardware.org/?probe=3d76189da7) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Acer          | Aspire 5738                 | [3b93414575](https://linux-hardware.org/?probe=3b93414575) | Jul 05, 2022 |
| Chuwi         | GemiBook                    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| Valve         | Jupiter                     | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [60e5b2ef2c](https://linux-hardware.org/?probe=60e5b2ef2c) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Unknown       | Unknown                     | [f7dd6e9a70](https://linux-hardware.org/?probe=f7dd6e9a70) | Jul 02, 2022 |
| Lenovo        | V110-15IAP 80TG             | [05d0271371](https://linux-hardware.org/?probe=05d0271371) | Jul 01, 2022 |
| Lenovo        | V110-15IAP 80TG             | [23519c6427](https://linux-hardware.org/?probe=23519c6427) | Jul 01, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | [927dbb8452](https://linux-hardware.org/?probe=927dbb8452) | Jul 01, 2022 |
| ASUSTek       | F3JR                        | [b56d8007d7](https://linux-hardware.org/?probe=b56d8007d7) | Jul 01, 2022 |
| Dell          | XPS 9320                    | [f04b491e6d](https://linux-hardware.org/?probe=f04b491e6d) | Jun 30, 2022 |
| Valve         | Jupiter                     | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Acer          | Aspire 5740                 | [1db26fc575](https://linux-hardware.org/?probe=1db26fc575) | Jun 29, 2022 |
| Acer          | Aspire 5740                 | [44a72b9a94](https://linux-hardware.org/?probe=44a72b9a94) | Jun 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [6491230956](https://linux-hardware.org/?probe=6491230956) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [13c3e19573](https://linux-hardware.org/?probe=13c3e19573) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | [c99e2d656f](https://linux-hardware.org/?probe=c99e2d656f) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | [d0e2e3232c](https://linux-hardware.org/?probe=d0e2e3232c) | Jun 26, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| HP            | Pavilion dv6700             | [352a224c3f](https://linux-hardware.org/?probe=352a224c3f) | Jun 26, 2022 |
| HONOR         | BBR-WAX9                    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| Samsung       | RF510/RF410/RF710           | [c68de3d559](https://linux-hardware.org/?probe=c68de3d559) | Jun 23, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [e0dfa460b6](https://linux-hardware.org/?probe=e0dfa460b6) | Jun 23, 2022 |
| Dell          | Precision 5540              | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W06    | [d1a1093555](https://linux-hardware.org/?probe=d1a1093555) | Jun 22, 2022 |
| Toshiba       | Satellite L50D-B            | [500756a7e3](https://linux-hardware.org/?probe=500756a7e3) | Jun 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b248434bc6](https://linux-hardware.org/?probe=b248434bc6) | Jun 21, 2022 |
| Acer          | Ferrari One 200             | [52ba124048](https://linux-hardware.org/?probe=52ba124048) | Jun 21, 2022 |
| HP            | 250 G5 Notebook PC          | [0b40800023](https://linux-hardware.org/?probe=0b40800023) | Jun 21, 2022 |
| Dell          | Latitude E4310              | [180f09a85f](https://linux-hardware.org/?probe=180f09a85f) | Jun 20, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [65359ef780](https://linux-hardware.org/?probe=65359ef780) | Jun 18, 2022 |
| Acer          | Aspire V3-572G              | [efef888970](https://linux-hardware.org/?probe=efef888970) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | Latitude E7270              | [bdf2e224f1](https://linux-hardware.org/?probe=bdf2e224f1) | Jun 18, 2022 |
| Dell          | Inspiron 15 5510            | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Primux Tec... | Primux_1402F_W10            | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dynabook      | TECRA A50-J                 | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| HP            | EliteBook 8460p             | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [2599b4c75d](https://linux-hardware.org/?probe=2599b4c75d) | Jun 12, 2022 |
| Alienware     | m15 R4                      | [5299db8f70](https://linux-hardware.org/?probe=5299db8f70) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| HP            | Compaq 6715b (GR667ET#AB... | [44de2345bb](https://linux-hardware.org/?probe=44de2345bb) | Jun 09, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| Dell          | Inspiron 13-7359            | [c46dcc9b6f](https://linux-hardware.org/?probe=c46dcc9b6f) | Jun 07, 2022 |
| HP            | Stream Notebook PC 13       | [47b55dbb68](https://linux-hardware.org/?probe=47b55dbb68) | Jun 06, 2022 |
| Toshiba       | Satellite M70               | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| ASUSTek       | 1000H                       | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [3dd8394bb5](https://linux-hardware.org/?probe=3dd8394bb5) | Jun 04, 2022 |
| eMachines     | eME732                      | [c6d57c850c](https://linux-hardware.org/?probe=c6d57c850c) | Jun 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [605cbc489f](https://linux-hardware.org/?probe=605cbc489f) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| ASUSTek       | TX201LA                     | [ba677dadab](https://linux-hardware.org/?probe=ba677dadab) | Jun 01, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 386       | 13.25%  |
| Ubuntu 18.04       | 252       | 8.65%   |
| Ubuntu 22.04       | 135       | 4.63%   |
| Debian 11          | 126       | 4.32%   |
| OpenMandriva 4.2   | 84        | 2.88%   |
| KDE neon 20.04     | 63        | 2.16%   |
| Zorin 16           | 59        | 2.02%   |
| OpenMandriva 4.3   | 59        | 2.02%   |
| Linux Mint 20.3    | 44        | 1.51%   |
| Arch               | 41        | 1.41%   |
| Ubuntu 20.10       | 39        | 1.34%   |
| Xubuntu 20.04      | 38        | 1.3%    |
| Linux Mint 19.3    | 37        | 1.27%   |
| Manjaro            | 36        | 1.24%   |
| Debian 10          | 36        | 1.24%   |
| OpenMandriva 23.01 | 35        | 1.2%    |
| Ubuntu 19.10       | 34        | 1.17%   |
| Ubuntu 21.04       | 32        | 1.1%    |
| Ubuntu 19.04       | 32        | 1.1%    |
| Linux Mint 20.1    | 32        | 1.1%    |
| Linux Mint 20      | 30        | 1.03%   |
| Ubuntu 21.10       | 29        | 1%      |
| Fedora 36          | 29        | 1%      |
| Arch Rolling       | 29        | 1%      |
| Kubuntu 20.04      | 28        | 0.96%   |
| Xubuntu 18.04      | 27        | 0.93%   |
| Linux Mint 20.2    | 27        | 0.93%   |
| Fedora 37          | 27        | 0.93%   |
| Zorin 15           | 25        | 0.86%   |
| Fedora 35          | 25        | 0.86%   |
| Ubuntu 22.10       | 24        | 0.82%   |
| Fedora 34          | 24        | 0.82%   |
| Fedora 33          | 24        | 0.82%   |
| ROSA R10           | 22        | 0.75%   |
| Pop!_OS 22.04      | 22        | 0.75%   |
| Ubuntu 18.10       | 21        | 0.72%   |
| Pop!_OS 20.04      | 21        | 0.72%   |
| Linux Mint 21      | 21        | 0.72%   |
| Linux Mint 21.1    | 20        | 0.69%   |
| Pop!_OS 20.10      | 19        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 961       | 34.66%  |
| Linux Mint    | 230       | 8.29%   |
| Debian        | 194       | 7%      |
| OpenMandriva  | 193       | 6.96%   |
| Fedora        | 144       | 5.19%   |
| Endless       | 100       | 3.61%   |
| Manjaro       | 96        | 3.46%   |
| Zorin         | 87        | 3.14%   |
| KDE neon      | 77        | 2.78%   |
| Xubuntu       | 75        | 2.7%    |
| Pop!_OS       | 75        | 2.7%    |
| Arch          | 69        | 2.49%   |
| Kubuntu       | 65        | 2.34%   |
| ROSA          | 54        | 1.95%   |
| Ubuntu MATE   | 31        | 1.12%   |
| Elementary    | 29        | 1.05%   |
| Kali          | 25        | 0.9%    |
| Ubuntu Unity  | 23        | 0.83%   |
| openSUSE      | 22        | 0.79%   |
| SteamOS       | 18        | 0.65%   |
| ArcoLinux     | 18        | 0.65%   |
| Lubuntu       | 17        | 0.61%   |
| BlackPanther  | 16        | 0.58%   |
| Gentoo        | 14        | 0.5%    |
| Parrot        | 13        | 0.47%   |
| LMDE          | 13        | 0.47%   |
| Nobara        | 11        | 0.4%    |
| EndeavourOS   | 9         | 0.32%   |
| Ubuntu Budgie | 7         | 0.25%   |
| MX            | 7         | 0.25%   |
| Clear Linux   | 7         | 0.25%   |
| Deepin        | 5         | 0.18%   |
| CentOS        | 5         | 0.18%   |
| RHEL          | 4         | 0.14%   |
| Garuda Linux  | 4         | 0.14%   |
| Ubuntu Studio | 3         | 0.11%   |
| Solus         | 3         | 0.11%   |
| Reborn OS     | 3         | 0.11%   |
| Q4OS          | 3         | 0.11%   |
| Peppermint    | 3         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 82        | 2.59%   |
| 5.16.7-desktop-1omv4003  | 58        | 1.83%   |
| 5.4.0-42-generic         | 48        | 1.51%   |
| 5.15.0-56-generic        | 34        | 1.07%   |
| 5.10.0-8-amd64           | 34        | 1.07%   |
| 6.1.1-desktop-1omv2290   | 33        | 1.04%   |
| 5.4.0-58-generic         | 33        | 1.04%   |
| 5.15.0-52-generic        | 32        | 1.01%   |
| 5.3.0-28-generic         | 31        | 0.98%   |
| 5.4.0-54-generic         | 27        | 0.85%   |
| 5.4.0-52-generic         | 26        | 0.82%   |
| 5.4.0-26-generic         | 26        | 0.82%   |
| 5.10.0-18-amd64          | 26        | 0.82%   |
| 5.15.0-58-generic        | 22        | 0.69%   |
| 5.15.0-53-generic        | 22        | 0.69%   |
| 5.0.0-37-generic         | 22        | 0.69%   |
| 5.3.0-46-generic         | 21        | 0.66%   |
| 5.3.0-40-generic         | 21        | 0.66%   |
| 5.15.0-48-generic        | 21        | 0.66%   |
| 5.11.0-27-generic        | 21        | 0.66%   |
| 5.4.0-65-generic         | 20        | 0.63%   |
| 5.4.0-48-generic         | 20        | 0.63%   |
| 5.19.0-35-generic        | 19        | 0.6%    |
| 5.11.0-43-generic        | 19        | 0.6%    |
| 5.11.0-41-generic        | 19        | 0.6%    |
| 5.4.0-72-generic         | 18        | 0.57%   |
| 5.4.0-40-generic         | 18        | 0.57%   |
| 5.0.0-32-generic         | 18        | 0.57%   |
| 5.8.0-44-generic         | 17        | 0.54%   |
| 5.4.0-19-generic         | 16        | 0.5%    |
| 5.3.0-45-generic         | 16        | 0.5%    |
| 5.8.0-14-generic         | 15        | 0.47%   |
| 5.4.0-53-generic         | 15        | 0.47%   |
| 5.4.0-29-generic         | 15        | 0.47%   |
| 5.15.0-47-generic        | 15        | 0.47%   |
| 5.13.0-28-generic        | 15        | 0.47%   |
| 5.8.0-43-generic         | 14        | 0.44%   |
| 5.4.0-91-generic         | 14        | 0.44%   |
| 5.4.0-70-generic         | 14        | 0.44%   |
| 5.3.0-51-generic         | 14        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 536       | 17.89%  |
| 5.15.0  | 254       | 8.48%   |
| 4.15.0  | 202       | 6.74%   |
| 5.11.0  | 166       | 5.54%   |
| 5.3.0   | 153       | 5.11%   |
| 5.10.0  | 151       | 5.04%   |
| 5.8.0   | 150       | 5.01%   |
| 5.13.0  | 132       | 4.41%   |
| 5.0.0   | 109       | 3.64%   |
| 5.10.14 | 83        | 2.77%   |
| 5.19.0  | 71        | 2.37%   |
| 4.18.0  | 71        | 2.37%   |
| 5.16.7  | 62        | 2.07%   |
| 4.19.0  | 41        | 1.37%   |
| 6.1.1   | 39        | 1.3%    |
| 6.0.0   | 15        | 0.5%    |
| 5.14.0  | 15        | 0.5%    |
| 4.9.60  | 15        | 0.5%    |
| 6.0.12  | 13        | 0.43%   |
| 5.18.0  | 13        | 0.43%   |
| 4.4.0   | 13        | 0.43%   |
| 4.18.16 | 13        | 0.43%   |
| 6.1.11  | 11        | 0.37%   |
| 6.1.0   | 10        | 0.33%   |
| 5.9.16  | 10        | 0.33%   |
| 5.17.5  | 8         | 0.27%   |
| 6.2.6   | 7         | 0.23%   |
| 6.1.12  | 7         | 0.23%   |
| 6.0.10  | 7         | 0.23%   |
| 5.3.18  | 7         | 0.23%   |
| 5.17.1  | 7         | 0.23%   |
| 5.16.0  | 7         | 0.23%   |
| 5.13.12 | 7         | 0.23%   |
| 5.11.12 | 7         | 0.23%   |
| 6.0.6   | 6         | 0.2%    |
| 5.9.0   | 6         | 0.2%    |
| 5.16.11 | 6         | 0.2%    |
| 5.12.4  | 6         | 0.2%    |
| 4.9.0   | 6         | 0.2%    |
| 6.1.4   | 5         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 569       | 19.26%  |
| 5.15    | 310       | 10.49%  |
| 5.10    | 272       | 9.2%    |
| 4.15    | 202       | 6.84%   |
| 5.11    | 194       | 6.57%   |
| 5.8     | 176       | 5.96%   |
| 5.3     | 168       | 5.69%   |
| 5.13    | 152       | 5.14%   |
| 5.0     | 111       | 3.76%   |
| 5.19    | 104       | 3.52%   |
| 5.16    | 98        | 3.32%   |
| 6.1     | 89        | 3.01%   |
| 4.18    | 84        | 2.84%   |
| 6.0     | 58        | 1.96%   |
| 4.19    | 49        | 1.66%   |
| 5.14    | 41        | 1.39%   |
| 4.9     | 39        | 1.32%   |
| 5.18    | 37        | 1.25%   |
| 5.9     | 29        | 0.98%   |
| 5.17    | 29        | 0.98%   |
| 5.6     | 25        | 0.85%   |
| 5.7     | 24        | 0.81%   |
| 5.12    | 23        | 0.78%   |
| 6.2     | 15        | 0.51%   |
| 5.5     | 14        | 0.47%   |
| 4.4     | 14        | 0.47%   |
| 4.16    | 5         | 0.17%   |
| 5.2     | 4         | 0.14%   |
| 4.1     | 4         | 0.14%   |
| 3.10    | 4         | 0.14%   |
| 5.1     | 3         | 0.1%    |
| 4.20    | 3         | 0.1%    |
| 4.13    | 3         | 0.1%    |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 3.16    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2567      | 95.53%  |
| i686   | 120       | 4.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1235      | 43.89%  |
| KDE5             | 475       | 16.88%  |
| Unknown          | 329       | 11.69%  |
| XFCE             | 224       | 7.96%   |
| X-Cinnamon       | 174       | 6.18%   |
| MATE             | 80        | 2.84%   |
| KDE              | 76        | 2.7%    |
| Cinnamon         | 32        | 1.14%   |
| Pantheon         | 28        | 1%      |
| LXQt             | 23        | 0.82%   |
| Unity            | 22        | 0.78%   |
| KDE4             | 22        | 0.78%   |
| i3               | 19        | 0.68%   |
| LXDE             | 14        | 0.5%    |
| GNOME Flashback  | 11        | 0.39%   |
| Budgie           | 11        | 0.39%   |
| Deepin           | 9         | 0.32%   |
| Openbox          | 6         | 0.21%   |
| GNOME Classic    | 5         | 0.18%   |
| DWM              | 3         | 0.11%   |
| bspwm            | 3         | 0.11%   |
| xmonad           | 1         | 0.04%   |
| trinity          | 1         | 0.04%   |
| river            | 1         | 0.04%   |
| qtile            | 1         | 0.04%   |
| Lubuntu          | 1         | 0.04%   |
| lightdm-xsession | 1         | 0.04%   |
| LeftWM           | 1         | 0.04%   |
| icewm            | 1         | 0.04%   |
| i3-with-shmlog   | 1         | 0.04%   |
| enlightenment    | 1         | 0.04%   |
| Cutefish         | 1         | 0.04%   |
| BunsenLabs       | 1         | 0.04%   |
| awesome          | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2167      | 78.34%  |
| Wayland | 392       | 14.17%  |
| Unknown | 187       | 6.76%   |
| Tty     | 20        | 0.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1427      | 51.24%  |
| SDDM    | 403       | 14.47%  |
| GDM     | 352       | 12.64%  |
| GDM3    | 253       | 9.08%   |
| LightDM | 223       | 8.01%   |
| TDM     | 90        | 3.23%   |
| KDM     | 24        | 0.86%   |
| XDM     | 7         | 0.25%   |
| SLiM    | 3         | 0.11%   |
| Ly      | 3         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| es_ES          | 1586      | 57.44%  |
| en_US          | 502       | 18.18%  |
| Unknown        | 336       | 12.17%  |
| ca_ES          | 109       | 3.95%   |
| en_GB          | 68        | 2.46%   |
| C              | 27        | 0.98%   |
| de_DE          | 20        | 0.72%   |
| gl_ES          | 12        | 0.43%   |
| eu_ES          | 11        | 0.4%    |
| fr_FR          | 10        | 0.36%   |
| ru_RU          | 9         | 0.33%   |
| an_ES          | 9         | 0.33%   |
| it_IT          | 8         | 0.29%   |
| es_MX          | 6         | 0.22%   |
| es_AR          | 6         | 0.22%   |
| pt_BR          | 4         | 0.14%   |
| en_AG          | 4         | 0.14%   |
| ca_AD          | 4         | 0.14%   |
| pl_PL          | 3         | 0.11%   |
| fr_BE          | 3         | 0.11%   |
| nl_NL          | 2         | 0.07%   |
| es_US          | 2         | 0.07%   |
| es_BO          | 2         | 0.07%   |
| en_IE          | 2         | 0.07%   |
| de_AT          | 2         | 0.07%   |
| sp_SP          | 1         | 0.04%   |
| POSIX          | 1         | 0.04%   |
| nb_NO          | 1         | 0.04%   |
| fr_CH          | 1         | 0.04%   |
| et_EE          | 1         | 0.04%   |
| es_VE          | 1         | 0.04%   |
| es_PE          | 1         | 0.04%   |
| en_NZ          | 1         | 0.04%   |
| en_HK          | 1         | 0.04%   |
| en_CA          | 1         | 0.04%   |
| en_AU          | 1         | 0.04%   |
| de_CH          | 1         | 0.04%   |
| ca_ES@valencia | 1         | 0.04%   |
| C.UTF8         | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1471      | 53.74%  |
| BIOS | 1266      | 46.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2174      | 79%     |
| Overlay | 207       | 7.52%   |
| Btrfs   | 184       | 6.69%   |
| Unknown | 111       | 4.03%   |
| Xfs     | 33        | 1.2%    |
| Zfs     | 18        | 0.65%   |
| Ext2    | 10        | 0.36%   |
| Tmpfs   | 5         | 0.18%   |
| Ext3    | 4         | 0.15%   |
| Aufs    | 3         | 0.11%   |
| Jfs     | 2         | 0.07%   |
| F2fs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1517      | 55.3%   |
| GPT     | 941       | 34.31%  |
| MBR     | 285       | 10.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2422      | 88.72%  |
| Yes       | 308       | 11.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1896      | 69.43%  |
| Yes       | 835       | 30.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 504       | 18.76%  |
| Lenovo              | 462       | 17.2%   |
| ASUSTek Computer    | 402       | 14.97%  |
| Acer                | 272       | 10.13%  |
| Dell                | 216       | 8.04%   |
| MSI                 | 170       | 6.33%   |
| Toshiba             | 105       | 3.91%   |
| Apple               | 65        | 2.42%   |
| Sony                | 41        | 1.53%   |
| HUAWEI              | 40        | 1.49%   |
| Packard Bell        | 35        | 1.3%    |
| Chuwi               | 31        | 1.15%   |
| Unknown             | 31        | 1.15%   |
| Notebook            | 30        | 1.12%   |
| Samsung Electronics | 29        | 1.08%   |
| SLIMBOOK            | 26        | 0.97%   |
| LG Electronics      | 20        | 0.74%   |
| Valve               | 18        | 0.67%   |
| Medion              | 13        | 0.48%   |
| Fujitsu             | 13        | 0.48%   |
| Timi                | 12        | 0.45%   |
| Fujitsu Siemens     | 12        | 0.45%   |
| eMachines           | 10        | 0.37%   |
| Teclast             | 8         | 0.3%    |
| Intel               | 8         | 0.3%    |
| Gigabyte Technology | 8         | 0.3%    |
| Dynabook            | 8         | 0.3%    |
| Clevo               | 8         | 0.3%    |
| Razer               | 4         | 0.15%   |
| PC Specialist       | 4         | 0.15%   |
| HONOR               | 4         | 0.15%   |
| Google              | 4         | 0.15%   |
| Qilive              | 3         | 0.11%   |
| IBM                 | 3         | 0.11%   |
| Compal              | 3         | 0.11%   |
| Alienware           | 3         | 0.11%   |
| VANT                | 2         | 0.07%   |
| TUXEDO              | 2         | 0.07%   |
| Thomson             | 2         | 0.07%   |
| TEKNOSERVICE        | 2         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 50        | 1.86%   |
| HP Pavilion g6                             | 22        | 0.82%   |
| HP Pavilion dv6                            | 19        | 0.71%   |
| HP Notebook                                | 19        | 0.71%   |
| Valve Jupiter                              | 18        | 0.67%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.67%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 15        | 0.56%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.56%   |
| HP G62                                     | 11        | 0.41%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 10        | 0.37%   |
| HP Pavilion 15                             | 10        | 0.37%   |
| HP Laptop 15-da0xxx                        | 10        | 0.37%   |
| Dell XPS 13 7390                           | 10        | 0.37%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.34%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.3%    |
| HUAWEI BOHK-WAX9X                          | 8         | 0.3%    |
| Chuwi GemiBook Pro                         | 8         | 0.3%    |
| ASUS X555LAB                               | 8         | 0.3%    |
| ASUS X550VX                                | 8         | 0.3%    |
| ASUS X540NA                                | 8         | 0.3%    |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.3%    |
| Acer Aspire 5750G                          | 8         | 0.3%    |
| Lenovo Y520-15IKBN 80WK                    | 7         | 0.26%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.26%   |
| Lenovo G50-70 20351                        | 7         | 0.26%   |
| HUAWEI NBLK-WAX9X                          | 7         | 0.26%   |
| HP ProBook 450 G8 Notebook PC              | 7         | 0.26%   |
| HP Pavilion dv7                            | 7         | 0.26%   |
| HP OMEN by Laptop                          | 7         | 0.26%   |
| HP Laptop 15s-fq1xxx                       | 7         | 0.26%   |
| HP Laptop 15-bw0xx                         | 7         | 0.26%   |
| Dell XPS 13 9370                           | 7         | 0.26%   |
| Acer Aspire 5738                           | 7         | 0.26%   |
| Lenovo Legion 5 15ACH6H 82JU               | 6         | 0.22%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 6         | 0.22%   |
| HP Pavilion Notebook 15-bc5xxx             | 6         | 0.22%   |
| HP Pavilion Notebook                       | 6         | 0.22%   |
| HP Pavilion Gaming Laptop 15-ec1xxx        | 6         | 0.22%   |
| HP Laptop 15-bs0xx                         | 6         | 0.22%   |
| HP EliteBook 840 G5                        | 6         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 199       | 7.41%   |
| Lenovo ThinkPad       | 177       | 6.59%   |
| Lenovo IdeaPad        | 134       | 4.99%   |
| HP Pavilion           | 124       | 4.62%   |
| Dell Latitude         | 89        | 3.31%   |
| Toshiba Satellite     | 82        | 3.05%   |
| ASUS VivoBook         | 74        | 2.76%   |
| HP Laptop             | 69        | 2.57%   |
| HP EliteBook          | 60        | 2.23%   |
| Dell XPS              | 51        | 1.9%    |
| Unknown               | 50        | 1.86%   |
| HP ProBook            | 39        | 1.45%   |
| HP Compaq             | 38        | 1.41%   |
| Dell Inspiron         | 34        | 1.27%   |
| ASUS ZenBook          | 34        | 1.27%   |
| Packard Bell EasyNote | 32        | 1.19%   |
| HP 250                | 31        | 1.15%   |
| ASUS ROG              | 26        | 0.97%   |
| MSI Prestige          | 25        | 0.93%   |
| Lenovo Legion         | 22        | 0.82%   |
| MSI Modern            | 21        | 0.78%   |
| HP OMEN               | 20        | 0.74%   |
| HP Notebook           | 19        | 0.71%   |
| Acer Extensa          | 19        | 0.71%   |
| Valve Jupiter         | 18        | 0.67%   |
| Acer TravelMate       | 18        | 0.67%   |
| Lenovo ThinkBook      | 17        | 0.63%   |
| ASUS TUF              | 15        | 0.56%   |
| ASUS ASUS             | 15        | 0.56%   |
| HP ENVY               | 14        | 0.52%   |
| Lenovo Yoga           | 12        | 0.45%   |
| Fujitsu LIFEBOOK      | 12        | 0.45%   |
| Dell Vostro           | 12        | 0.45%   |
| Chuwi GemiBook        | 12        | 0.45%   |
| HP G62                | 11        | 0.41%   |
| Toshiba PORTEGE       | 10        | 0.37%   |
| HP Victus             | 9         | 0.34%   |
| HP 255                | 9         | 0.34%   |
| Dell Precision        | 9         | 0.34%   |
| Apple MacBookPro11    | 9         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 277       | 10.31%  |
| 2019    | 273       | 10.16%  |
| 2020    | 248       | 9.23%   |
| 2021    | 215       | 8%      |
| 2015    | 177       | 6.59%   |
| 2014    | 175       | 6.52%   |
| 2011    | 169       | 6.29%   |
| 2017    | 158       | 5.88%   |
| 2010    | 144       | 5.36%   |
| 2013    | 139       | 5.17%   |
| 2012    | 133       | 4.95%   |
| 2008    | 131       | 4.88%   |
| 2016    | 116       | 4.32%   |
| 2009    | 112       | 4.17%   |
| 2007    | 84        | 3.13%   |
| 2022    | 82        | 3.05%   |
| 2006    | 29        | 1.08%   |
| 2005    | 10        | 0.37%   |
| 2004    | 5         | 0.19%   |
| 2003    | 3         | 0.11%   |
| Unknown | 3         | 0.11%   |
| 2023    | 1         | 0.04%   |
| 2002    | 1         | 0.04%   |
| 2001    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2686      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2463      | 91.09%  |
| Enabled  | 241       | 8.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2679      | 99.74%  |
| Yes  | 7         | 0.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 708       | 26.07%  |
| 3.01-4.0    | 609       | 22.42%  |
| 8.01-16.0   | 491       | 18.08%  |
| 16.01-24.0  | 482       | 17.75%  |
| 32.01-64.0  | 159       | 5.85%   |
| 1.01-2.0    | 138       | 5.08%   |
| 2.01-3.0    | 50        | 1.84%   |
| 0.51-1.0    | 46        | 1.69%   |
| 64.01-256.0 | 16        | 0.59%   |
| 24.01-32.0  | 15        | 0.55%   |
| 0.01-0.5    | 2         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1131      | 38.17%  |
| 2.01-3.0   | 782       | 26.39%  |
| 4.01-8.0   | 361       | 12.18%  |
| 3.01-4.0   | 321       | 10.83%  |
| 0.51-1.0   | 238       | 8.03%   |
| 8.01-16.0  | 98        | 3.31%   |
| 0.01-0.5   | 25        | 0.84%   |
| 16.01-24.0 | 4         | 0.13%   |
| 24.01-32.0 | 3         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2070      | 75.8%   |
| 2      | 571       | 20.91%  |
| 3      | 61        | 2.23%   |
| 0      | 23        | 0.84%   |
| 4      | 4         | 0.15%   |
| 5      | 2         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1733      | 64.14%  |
| Yes       | 969       | 35.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2166      | 80.22%  |
| No        | 534       | 19.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2630      | 97.92%  |
| No        | 56        | 2.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1986      | 73.31%  |
| No        | 723       | 26.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 2686      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 463       | 15.79%  |
| Barcelona                  | 317       | 10.81%  |
| Seville                    | 102       | 3.48%   |
| Valencia                   | 87        | 2.97%   |
| Zaragoza                   | 46        | 1.57%   |
| Granada                    | 45        | 1.53%   |
| Málaga                    | 41        | 1.4%    |
| Alcobendas                 | 36        | 1.23%   |
| Palma                      | 32        | 1.09%   |
| Vigo                       | 30        | 1.02%   |
| Valladolid                 | 29        | 0.99%   |
| Sabadell                   | 29        | 0.99%   |
| Bilbao                     | 25        | 0.85%   |
| Córdoba                   | 24        | 0.82%   |
| Las Palmas de Gran Canaria | 22        | 0.75%   |
| Alcalá de Henares         | 22        | 0.75%   |
| Pamplona                   | 20        | 0.68%   |
| Alicante                   | 20        | 0.68%   |
| Santiago de Compostela     | 19        | 0.65%   |
| Donostia / San Sebastian   | 19        | 0.65%   |
| A Coruña                  | 18        | 0.61%   |
| León                      | 17        | 0.58%   |
| Oviedo                     | 16        | 0.55%   |
| Murcia                     | 16        | 0.55%   |
| Mostoles                   | 16        | 0.55%   |
| Gijón                     | 15        | 0.51%   |
| Burgos                     | 15        | 0.51%   |
| Salamanca                  | 13        | 0.44%   |
| Barakaldo                  | 13        | 0.44%   |
| Vitoria-Gasteiz            | 12        | 0.41%   |
| Terrassa                   | 12        | 0.41%   |
| Reus                       | 12        | 0.41%   |
| Getxo                      | 12        | 0.41%   |
| Almería                   | 12        | 0.41%   |
| Dos Hermanas               | 11        | 0.38%   |
| Cartagena                  | 11        | 0.38%   |
| Albacete                   | 11        | 0.38%   |
| Tarragona                  | 10        | 0.34%   |
| Pozuelo de Alarcón        | 10        | 0.34%   |
| Pontevedra                 | 10        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 463       | 564    | 14.25%  |
| WDC                         | 366       | 452    | 11.27%  |
| Seagate                     | 341       | 402    | 10.5%   |
| Kingston                    | 328       | 414    | 10.1%   |
| Toshiba                     | 278       | 343    | 8.56%   |
| SanDisk                     | 205       | 261    | 6.31%   |
| Unknown                     | 158       | 209    | 4.86%   |
| SK hynix                    | 141       | 173    | 4.34%   |
| Hitachi                     | 119       | 140    | 3.66%   |
| Intel                       | 102       | 138    | 3.14%   |
| HGST                        | 101       | 124    | 3.11%   |
| Micron Technology           | 98        | 122    | 3.02%   |
| Crucial                     | 97        | 119    | 2.99%   |
| KIOXIA                      | 33        | 39     | 1.02%   |
| Fujitsu                     | 33        | 37     | 1.02%   |
| China                       | 31        | 44     | 0.95%   |
| Phison                      | 27        | 29     | 0.83%   |
| Apple                       | 24        | 31     | 0.74%   |
| Netac                       | 16        | 26     | 0.49%   |
| LITEON                      | 16        | 17     | 0.49%   |
| Kingston Technology Company | 15        | 20     | 0.46%   |
| KingSpec                    | 14        | 18     | 0.43%   |
| Phison Electronics          | 13        | 13     | 0.4%    |
| Micron/Crucial Technology   | 12        | 14     | 0.37%   |
| A-DATA Technology           | 12        | 14     | 0.37%   |
| JMicron Technology          | 10        | 10     | 0.31%   |
| Transcend                   | 9         | 15     | 0.28%   |
| PNY                         | 8         | 14     | 0.25%   |
| OCZ                         | 8         | 9      | 0.25%   |
| FORESEE                     | 8         | 11     | 0.25%   |
| Unknown                     | 8         | 8      | 0.25%   |
| USB30                       | 7         | 8      | 0.22%   |
| Teclast                     | 7         | 7      | 0.22%   |
| Patriot                     | 5         | 6      | 0.15%   |
| LITEONIT                    | 5         | 6      | 0.15%   |
| KingDian                    | 5         | 5      | 0.15%   |
| Intenso                     | 5         | 8      | 0.15%   |
| Emtec                       | 5         | 5      | 0.15%   |
| Union Memory                | 4         | 5      | 0.12%   |
| TCSUNBOW                    | 4         | 4      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 118       | 3.53%   |
| Kingston SA400S37480G 480GB SSD        | 42        | 1.25%   |
| Seagate ST500LT012-1DG142 500GB        | 41        | 1.22%   |
| Unknown MMC Card  32GB                 | 36        | 1.08%   |
| SK hynix NVMe SSD Drive 512GB          | 34        | 1.02%   |
| HGST HTS721010A9E630 1TB               | 34        | 1.02%   |
| Toshiba MQ01ABD100 1TB                 | 31        | 0.93%   |
| Seagate ST9500325AS 500GB              | 31        | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB         | 31        | 0.93%   |
| Samsung NVMe SSD Drive 512GB           | 31        | 0.93%   |
| Unknown MMC Card  64GB                 | 30        | 0.9%    |
| Toshiba MQ01ABF050 500GB               | 30        | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 30        | 0.9%    |
| Toshiba MQ04ABF100 1TB                 | 27        | 0.81%   |
| SanDisk NVMe SSD Drive 512GB           | 26        | 0.78%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 22        | 0.66%   |
| Toshiba MQ01ABD050 500GB               | 21        | 0.63%   |
| Samsung SSD 850 EVO 250GB              | 21        | 0.63%   |
| Intel NVMe SSD Drive 512GB             | 21        | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB               | 20        | 0.6%    |
| Kingston SUV400S37240G 240GB SSD       | 20        | 0.6%    |
| Kingston SA400S37120G 120GB SSD        | 20        | 0.6%    |
| Samsung SSD 860 EVO 500GB              | 19        | 0.57%   |
| Kingston RBUSC180DS37256GJ 256GB SSD   | 19        | 0.57%   |
| Unknown MMC Card  128GB                | 18        | 0.54%   |
| HGST HTS545050A7E680 500GB             | 18        | 0.54%   |
| HGST HTS541010A9E680 1TB               | 18        | 0.54%   |
| SanDisk SSD PLUS 480GB                 | 17        | 0.51%   |
| SanDisk NVMe SSD Drive 256GB           | 17        | 0.51%   |
| Crucial CT500MX500SSD1 500GB           | 16        | 0.48%   |
| Seagate ST1000LM049-2GH172 1TB         | 14        | 0.42%   |
| Seagate Expansion+ 2TB                 | 14        | 0.42%   |
| Samsung SSD 850 EVO 500GB              | 14        | 0.42%   |
| Micron NVMe SSD Drive 512GB            | 13        | 0.39%   |
| SK hynix NVMe SSD Drive 256GB          | 11        | 0.33%   |
| SanDisk SSD PLUS 1000GB                | 11        | 0.33%   |
| SanDisk NVMe SSD Drive 1024GB          | 11        | 0.33%   |
| Samsung NVMe SSD Drive 1024GB          | 11        | 0.33%   |
| Kingston SA400S37960G 960GB SSD        | 11        | 0.33%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 10        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 337       | 398    | 31.82%  |
| WDC                 | 233       | 279    | 22%     |
| Toshiba             | 186       | 221    | 17.56%  |
| Hitachi             | 119       | 140    | 11.24%  |
| HGST                | 101       | 124    | 9.54%   |
| Fujitsu             | 33        | 37     | 3.12%   |
| Samsung Electronics | 27        | 28     | 2.55%   |
| Unknown             | 6         | 9      | 0.57%   |
| Apple               | 4         | 4      | 0.38%   |
| USB3.0              | 3         | 3      | 0.28%   |
| ASMT                | 3         | 3      | 0.28%   |
| USB                 | 2         | 2      | 0.19%   |
| PHD 3.0             | 1         | 1      | 0.09%   |
| OEM                 | 1         | 1      | 0.09%   |
| Maxone              | 1         | 1      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| IBM                 | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 283       | 359    | 26.9%   |
| Samsung Electronics | 177       | 216    | 16.83%  |
| SanDisk             | 111       | 135    | 10.55%  |
| Crucial             | 88        | 108    | 8.37%   |
| WDC                 | 44        | 58     | 4.18%   |
| Toshiba             | 42        | 52     | 3.99%   |
| SK hynix            | 33        | 36     | 3.14%   |
| Micron Technology   | 31        | 40     | 2.95%   |
| China               | 31        | 44     | 2.95%   |
| Intel               | 21        | 34     | 2%      |
| Netac               | 16        | 26     | 1.52%   |
| LITEON              | 15        | 15     | 1.43%   |
| KingSpec            | 14        | 18     | 1.33%   |
| Apple               | 13        | 15     | 1.24%   |
| A-DATA Technology   | 10        | 12     | 0.95%   |
| Transcend           | 8         | 14     | 0.76%   |
| OCZ                 | 8         | 9      | 0.76%   |
| FORESEE             | 8         | 11     | 0.76%   |
| USB30               | 7         | 8      | 0.67%   |
| Teclast             | 7         | 7      | 0.67%   |
| PNY                 | 6         | 12     | 0.57%   |
| JMicron Technology  | 6         | 6      | 0.57%   |
| LITEONIT            | 5         | 6      | 0.48%   |
| Patriot             | 4         | 5      | 0.38%   |
| KingDian            | 4         | 4      | 0.38%   |
| Intenso             | 4         | 6      | 0.38%   |
| Emtec               | 4         | 4      | 0.38%   |
| Corsair             | 4         | 5      | 0.38%   |
| Unknown             | 3         | 3      | 0.29%   |
| Dogfish             | 3         | 3      | 0.29%   |
| Unknown             | 3         | 3      | 0.29%   |
| TCSUNBOW            | 2         | 2      | 0.19%   |
| ShanDianZhe         | 2         | 2      | 0.19%   |
| Plextor             | 2         | 3      | 0.19%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.19%   |
| BAITITON            | 2         | 2      | 0.19%   |
| Yeyian              | 1         | 1      | 0.1%    |
| W800S               | 1         | 2      | 0.1%    |
| Verbatim            | 1         | 1      | 0.1%    |
| Vaseky              | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1034      | 1253   | 33.25%  |
| SSD     | 983       | 1327   | 31.61%  |
| NVMe    | 898       | 1180   | 28.87%  |
| MMC     | 158       | 207    | 5.08%   |
| Unknown | 37        | 43     | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1792      | 2508   | 60.75%  |
| NVMe | 897       | 1176   | 30.41%  |
| MMC  | 158       | 207    | 5.36%   |
| SAS  | 103       | 119    | 3.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1442      | 1946   | 73.31%  |
| 0.51-1.0   | 468       | 564    | 23.79%  |
| 1.01-2.0   | 47        | 58     | 2.39%   |
| 3.01-4.0   | 5         | 6      | 0.25%   |
| 4.01-10.0  | 4         | 5      | 0.2%    |
| 2.01-3.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 883       | 31.4%   |
| 251-500        | 795       | 28.27%  |
| 501-1000       | 341       | 12.13%  |
| 1-20           | 212       | 7.54%   |
| 51-100         | 203       | 7.22%   |
| 21-50          | 132       | 4.69%   |
| 1001-2000      | 122       | 4.34%   |
| Unknown        | 60        | 2.13%   |
| 2001-3000      | 35        | 1.24%   |
| More than 3000 | 29        | 1.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1226      | 41.67%  |
| 21-50          | 547       | 18.59%  |
| 101-250        | 409       | 13.9%   |
| 51-100         | 331       | 11.25%  |
| 251-500        | 215       | 7.31%   |
| 501-1000       | 108       | 3.67%   |
| Unknown        | 60        | 2.04%   |
| 1001-2000      | 28        | 0.95%   |
| 2001-3000      | 9         | 0.31%   |
| More than 3000 | 7         | 0.24%   |
| 0              | 2         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                | 6         | 7      | 3.68%   |
| Seagate ST500LT012-1DG142 500GB          | 5         | 5      | 3.07%   |
| SanDisk SSD PLUS 480GB                   | 5         | 6      | 3.07%   |
| HGST HTS545050A7E680 500GB               | 5         | 7      | 3.07%   |
| Seagate ST9500420AS 500GB                | 4         | 4      | 2.45%   |
| Seagate ST9250827AS 250GB                | 4         | 4      | 2.45%   |
| Seagate ST1000LM035-1RK172 1TB           | 4         | 4      | 2.45%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 2.45%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 3      | 1.84%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 1.84%   |
| China G521N256GB SSD                     | 3         | 4      | 1.84%   |
| WDC WD5000BPVT-60HXZT3 500GB             | 2         | 2      | 1.23%   |
| Toshiba Q300. 240GB SSD                  | 2         | 2      | 1.23%   |
| Toshiba MK5076GSX 500GB                  | 2         | 2      | 1.23%   |
| Seagate ST9500420ASG 500GB               | 2         | 2      | 1.23%   |
| Seagate ST500LM021-1KJ152 500GB          | 2         | 2      | 1.23%   |
| Seagate ST320LT012-9WS14C 320GB          | 2         | 2      | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 2      | 1.23%   |
| Kingston SV300S37A120G 120GB SSD         | 2         | 2      | 1.23%   |
| Kingston SA400S37480G 480GB SSD          | 2         | 2      | 1.23%   |
| Intel SSDSC2BF180A5H SED 180GB           | 2         | 2      | 1.23%   |
| Hitachi HTS545050B9A300 500GB            | 2         | 2      | 1.23%   |
| Hitachi HTS543232A7A384 320GB            | 2         | 2      | 1.23%   |
| HGST HTS545050A7E380 500GB               | 2         | 2      | 1.23%   |
| Fujitsu MHZ2250BH G2 250GB               | 2         | 2      | 1.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.61%   |
| WDC WD7500BPVT-60HXZT1 752GB             | 1         | 1      | 0.61%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 1      | 0.61%   |
| WDC WD5000BEVT-22A0RT0 500GB             | 1         | 1      | 0.61%   |
| WDC WD3200BEVT-00A0RT0 320GB             | 1         | 1      | 0.61%   |
| WDC WD3200BEKT-60V5T1 320GB              | 1         | 1      | 0.61%   |
| WDC WD3200BEKT-60F3T1 320GB              | 1         | 2      | 0.61%   |
| WDC WD2500BEVS-60UST0 250GB              | 1         | 1      | 0.61%   |
| WDC WD2500BEVS-22UST0 250GB              | 1         | 1      | 0.61%   |
| WDC WD1600BEVT-60ZCT0 160GB              | 1         | 1      | 0.61%   |
| WDC WD1600BEVS-60RST0 160GB              | 1         | 1      | 0.61%   |
| WDC WD1600BEVS-22RST0 160GB              | 1         | 1      | 0.61%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 0.61%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 1         | 1      | 0.61%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 47     | 27.61%  |
| Hitachi             | 20        | 21     | 12.27%  |
| Toshiba             | 19        | 20     | 11.66%  |
| WDC                 | 16        | 17     | 9.82%   |
| HGST                | 16        | 19     | 9.82%   |
| Samsung Electronics | 10        | 10     | 6.13%   |
| SanDisk             | 6         | 7      | 3.68%   |
| Kingston            | 6         | 7      | 3.68%   |
| Intel               | 6         | 6      | 3.68%   |
| Fujitsu             | 5         | 5      | 3.07%   |
| SK hynix            | 3         | 3      | 1.84%   |
| Micron Technology   | 3         | 4      | 1.84%   |
| Crucial             | 3         | 5      | 1.84%   |
| China               | 3         | 4      | 1.84%   |
| OCZ                 | 1         | 1      | 0.61%   |
| IBM                 | 1         | 1      | 0.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 47     | 37.19%  |
| Hitachi             | 20        | 21     | 16.53%  |
| HGST                | 16        | 19     | 13.22%  |
| WDC                 | 15        | 16     | 12.4%   |
| Toshiba             | 14        | 15     | 11.57%  |
| Samsung Electronics | 5         | 5      | 4.13%   |
| Fujitsu             | 5         | 5      | 4.13%   |
| IBM                 | 1         | 1      | 0.83%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 119       | 129    | 74.38%  |
| SSD  | 36        | 43     | 22.5%   |
| NVMe | 5         | 5      | 3.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1655      | 2525   | 58.4%   |
| Works    | 1019      | 1307   | 35.96%  |
| Malfunc  | 159       | 177    | 5.61%   |
| Failed   | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1877      | 60.51%  |
| AMD                              | 298       | 9.61%   |
| Samsung Electronics              | 286       | 9.22%   |
| SanDisk                          | 176       | 5.67%   |
| SK hynix                         | 102       | 3.29%   |
| Micron Technology                | 67        | 2.16%   |
| Kingston Technology Company      | 58        | 1.87%   |
| Toshiba America Info Systems     | 51        | 1.64%   |
| Phison Electronics               | 44        | 1.42%   |
| KIOXIA                           | 38        | 1.23%   |
| Nvidia                           | 26        | 0.84%   |
| Micron/Crucial Technology        | 18        | 0.58%   |
| Silicon Integrated Systems [SiS] | 13        | 0.42%   |
| Silicon Motion                   | 7         | 0.23%   |
| Union Memory (Shenzhen)          | 6         | 0.19%   |
| Apple                            | 6         | 0.19%   |
| VIA Technologies                 | 5         | 0.16%   |
| JMicron Technology               | 5         | 0.16%   |
| Solid State Storage Technology   | 3         | 0.1%    |
| O2 Micro                         | 3         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 2         | 0.06%   |
| Marvell Technology Group         | 2         | 0.06%   |
| Lite-On Technology               | 2         | 0.06%   |
| Lenovo                           | 2         | 0.06%   |
| ADATA Technology                 | 2         | 0.06%   |
| Silicon Image                    | 1         | 0.03%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 253       | 7.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 209       | 6.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 137       | 4.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 137       | 4.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 135       | 4.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 126       | 3.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 122       | 3.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 109       | 3.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 93        | 2.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 87        | 2.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 81        | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 74        | 2.2%    |
| Intel Volume Management Device NVMe RAID Controller                            | 71        | 2.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 67        | 1.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 67        | 1.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 67        | 1.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 67        | 1.99%   |
| Micron NVMe Storage Controller                                                 | 66        | 1.96%   |
| Samsung NVMe SSD Controller 980                                                | 65        | 1.93%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 53        | 1.58%   |
| Intel SSD 660P Series                                                          | 51        | 1.52%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 40        | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 38        | 1.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 36        | 1.07%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 36        | 1.07%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 35        | 1.04%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 34        | 1.01%   |
| Intel Tiger Lake-LP SATA Controller                                            | 34        | 1.01%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 32        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 32        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 29        | 0.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 28        | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 28        | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 27        | 0.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 27        | 0.8%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 26        | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                          | 26        | 0.77%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 25        | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 24        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1891      | 58.2%   |
| NVMe | 906       | 27.89%  |
| IDE  | 239       | 7.36%   |
| RAID | 213       | 6.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2228      | 82.95%  |
| AMD          | 457       | 17.01%  |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 60        | 2.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 53        | 1.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 48        | 1.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 45        | 1.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 43        | 1.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 40        | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 38        | 1.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 38        | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 37        | 1.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 36        | 1.34%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 36        | 1.34%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 36        | 1.34%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 32        | 1.19%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 30        | 1.12%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 1.04%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 28        | 1.04%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 27        | 1%      |
| Intel Celeron CPU N2840 @ 2.16GHz             | 26        | 0.97%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 25        | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 23        | 0.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 23        | 0.86%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 23        | 0.86%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 23        | 0.86%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 21        | 0.78%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 19        | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 18        | 0.67%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 18        | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.67%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.67%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 18        | 0.67%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 18        | 0.67%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 18        | 0.67%   |
| AMD Custom APU 0405                           | 18        | 0.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 17        | 0.63%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 17        | 0.63%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 17        | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.6%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 16        | 0.6%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 16        | 0.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 15        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 636       | 23.67%  |
| Intel Core i5           | 534       | 19.87%  |
| Other                   | 241       | 8.97%   |
| Intel Celeron           | 204       | 7.59%   |
| Intel Core i3           | 200       | 7.44%   |
| Intel Core 2 Duo        | 160       | 5.95%   |
| AMD Ryzen 7             | 125       | 4.65%   |
| Intel Atom              | 100       | 3.72%   |
| AMD Ryzen 5             | 90        | 3.35%   |
| Intel Pentium           | 37        | 1.38%   |
| Intel Pentium Dual-Core | 36        | 1.34%   |
| Intel Pentium Dual      | 29        | 1.08%   |
| AMD A4                  | 28        | 1.04%   |
| AMD A6                  | 27        | 1%      |
| Intel Genuine           | 23        | 0.86%   |
| Intel Core 2            | 23        | 0.86%   |
| AMD E1                  | 21        | 0.78%   |
| AMD A8                  | 17        | 0.63%   |
| AMD E                   | 13        | 0.48%   |
| AMD Ryzen 9             | 12        | 0.45%   |
| AMD Ryzen 3             | 11        | 0.41%   |
| AMD Ryzen 7 PRO         | 10        | 0.37%   |
| Intel Pentium M         | 9         | 0.33%   |
| Intel Core i9           | 9         | 0.33%   |
| AMD Athlon              | 9         | 0.33%   |
| AMD A10                 | 9         | 0.33%   |
| Intel Celeron M         | 8         | 0.3%    |
| Intel Core m3           | 5         | 0.19%   |
| Intel Pentium 4         | 4         | 0.15%   |
| AMD Turion II Dual-Core | 4         | 0.15%   |
| AMD Turion 64 X2 Mobile | 4         | 0.15%   |
| AMD FX                  | 4         | 0.15%   |
| AMD Athlon II           | 4         | 0.15%   |
| AMD Turion 64 Mobile    | 3         | 0.11%   |
| AMD A12                 | 3         | 0.11%   |
| Intel Xeon              | 2         | 0.07%   |
| Intel Pentium Silver    | 2         | 0.07%   |
| Intel Core m5           | 2         | 0.07%   |
| Intel Core Duo          | 2         | 0.07%   |
| AMD Ryzen 5 PRO         | 2         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1337      | 49.74%  |
| 4       | 854       | 31.77%  |
| 6       | 182       | 6.77%   |
| 8       | 159       | 5.92%   |
| 1       | 115       | 4.28%   |
| 14      | 21        | 0.78%   |
| 10      | 9         | 0.33%   |
| 12      | 7         | 0.26%   |
| Unknown | 4         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2685      | 99.96%  |
| 2      | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1896      | 70.54%  |
| 1       | 788       | 29.32%  |
| Unknown | 4         | 0.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2576      | 95.41%  |
| 32-bit         | 56        | 2.07%   |
| Unknown        | 54        | 2%      |
| 64-bit         | 14        | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 518       | 18.71%  |
| 0x206a7    | 137       | 4.95%   |
| 0x306a9    | 113       | 4.08%   |
| 0x806c1    | 101       | 3.65%   |
| 0x806ea    | 97        | 3.5%    |
| 0x906ea    | 95        | 3.43%   |
| 0x40651    | 95        | 3.43%   |
| 0x806ec    | 88        | 3.18%   |
| 0x1067a    | 79        | 2.85%   |
| 0x406e3    | 77        | 2.78%   |
| 0x20655    | 76        | 2.74%   |
| 0x6fd      | 75        | 2.71%   |
| 0x806e9    | 71        | 2.56%   |
| 0x306d4    | 66        | 2.38%   |
| 0x306c3    | 60        | 2.17%   |
| 0x30678    | 51        | 1.84%   |
| 0x08108109 | 42        | 1.52%   |
| 0xa0652    | 40        | 1.44%   |
| 0x706e5    | 39        | 1.41%   |
| 0x10676    | 39        | 1.41%   |
| 0x0a50000c | 37        | 1.34%   |
| 0x20652    | 35        | 1.26%   |
| 0x706a1    | 34        | 1.23%   |
| 0x506e3    | 33        | 1.19%   |
| 0x06006705 | 33        | 1.19%   |
| 0x106ca    | 29        | 1.05%   |
| 0x08108102 | 29        | 1.05%   |
| 0x906e9    | 28        | 1.01%   |
| 0x806eb    | 27        | 0.98%   |
| 0x08600106 | 25        | 0.9%    |
| 0x506c9    | 24        | 0.87%   |
| 0x406c4    | 24        | 0.87%   |
| 0x906a3    | 23        | 0.83%   |
| 0x706a8    | 23        | 0.83%   |
| 0x406c3    | 22        | 0.79%   |
| 0x806d1    | 21        | 0.76%   |
| 0x106c2    | 19        | 0.69%   |
| 0x08600103 | 19        | 0.69%   |
| 0x6f6      | 18        | 0.65%   |
| 0x08608103 | 17        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 496       | 18.47%  |
| Haswell          | 207       | 7.71%   |
| SandyBridge      | 161       | 5.99%   |
| Penryn           | 146       | 5.44%   |
| Core             | 137       | 5.1%    |
| TigerLake        | 136       | 5.06%   |
| Skylake          | 134       | 4.99%   |
| IvyBridge        | 127       | 4.73%   |
| Westmere         | 122       | 4.54%   |
| Silvermont       | 115       | 4.28%   |
| Broadwell        | 83        | 3.09%   |
| Zen+             | 82        | 3.05%   |
| Zen 2            | 73        | 2.72%   |
| Unknown          | 70        | 2.61%   |
| Goldmont plus    | 68        | 2.53%   |
| Bonnell          | 61        | 2.27%   |
| IceLake          | 58        | 2.16%   |
| Excavator        | 58        | 2.16%   |
| CometLake        | 55        | 2.05%   |
| Zen 3            | 51        | 1.9%    |
| Goldmont         | 29        | 1.08%   |
| P6               | 27        | 1.01%   |
| Puma             | 26        | 0.97%   |
| Alderlake Hybrid | 25        | 0.93%   |
| Zen              | 24        | 0.89%   |
| Jaguar           | 23        | 0.86%   |
| Bobcat           | 21        | 0.78%   |
| K8 Hammer        | 14        | 0.52%   |
| K10              | 14        | 0.52%   |
| Tremont          | 9         | 0.34%   |
| Nehalem          | 9         | 0.34%   |
| Piledriver       | 8         | 0.3%    |
| Steamroller      | 5         | 0.19%   |
| NetBurst         | 5         | 0.19%   |
| K10 Llano        | 4         | 0.15%   |
| K8 & K10 hybrid  | 3         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1984      | 57.69%  |
| Nvidia                           | 805       | 23.41%  |
| AMD                              | 637       | 18.52%  |
| Silicon Integrated Systems [SiS] | 8         | 0.23%   |
| VIA Technologies                 | 5         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 145       | 4.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 130       | 3.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 123       | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 122       | 3.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 116       | 3.25%   |
| Intel UHD Graphics 620                                                                   | 105       | 2.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 89        | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 89        | 2.5%    |
| Intel HD Graphics 620                                                                    | 82        | 2.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 82        | 2.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 79        | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 77        | 2.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 75        | 2.1%    |
| Intel HD Graphics 5500                                                                   | 70        | 1.96%   |
| AMD Renoir                                                                               | 70        | 1.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 66        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 64        | 1.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 61        | 1.71%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 59        | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 51        | 1.43%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 48        | 1.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 47        | 1.32%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 46        | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 46        | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 46        | 1.29%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 45        | 1.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 43        | 1.21%   |
| Intel HD Graphics 530                                                                    | 42        | 1.18%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 37        | 1.04%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 36        | 1.01%   |
| Intel HD Graphics 630                                                                    | 33        | 0.93%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 32        | 0.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 0.87%   |
| Intel HD Graphics 500                                                                    | 27        | 0.76%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 27        | 0.76%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 27        | 0.76%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 26        | 0.73%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 25        | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 24        | 0.67%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 24        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1304      | 48.49%  |
| Intel + Nvidia | 586       | 21.79%  |
| 1 x AMD        | 431       | 16.03%  |
| 1 x Nvidia     | 139       | 5.17%   |
| Intel + AMD    | 88        | 3.27%   |
| AMD + Nvidia   | 77        | 2.86%   |
| 2 x AMD        | 40        | 1.49%   |
| 1 x SiS        | 8         | 0.3%    |
| 1 x VIA        | 5         | 0.19%   |
| 2 x Nvidia     | 4         | 0.15%   |
| 2 x Intel      | 4         | 0.15%   |
| Other          | 3         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2263      | 83.26%  |
| Proprietary | 372       | 13.69%  |
| Unknown     | 83        | 3.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1675      | 60.78%  |
| 0.01-0.5   | 350       | 12.7%   |
| 1.01-2.0   | 325       | 11.79%  |
| 3.01-4.0   | 181       | 6.57%   |
| 0.51-1.0   | 155       | 5.62%   |
| 5.01-6.0   | 41        | 1.49%   |
| 7.01-8.0   | 23        | 0.83%   |
| 2.01-3.0   | 3         | 0.11%   |
| 8.01-16.0  | 3         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 518       | 17.3%   |
| Chimei Innolux          | 477       | 15.93%  |
| LG Display              | 416       | 13.89%  |
| BOE                     | 353       | 11.79%  |
| Samsung Electronics     | 280       | 9.35%   |
| Chi Mei Optoelectronics | 89        | 2.97%   |
| Sharp                   | 85        | 2.84%   |
| Goldstar                | 77        | 2.57%   |
| Dell                    | 74        | 2.47%   |
| Apple                   | 64        | 2.14%   |
| PANDA                   | 59        | 1.97%   |
| Hewlett-Packard         | 59        | 1.97%   |
| Lenovo                  | 44        | 1.47%   |
| LG Philips              | 43        | 1.44%   |
| BenQ                    | 42        | 1.4%    |
| Acer                    | 28        | 0.93%   |
| Philips                 | 26        | 0.87%   |
| Ancor Communications    | 21        | 0.7%    |
| HannStar                | 20        | 0.67%   |
| AOC                     | 20        | 0.67%   |
| Sony                    | 18        | 0.6%    |
| InfoVision              | 16        | 0.53%   |
| CPT                     | 14        | 0.47%   |
| ASUSTek Computer        | 12        | 0.4%    |
| CSO                     | 9         | 0.3%    |
| Valve                   | 8         | 0.27%   |
| Quanta Display          | 8         | 0.27%   |
| Analogix                | 7         | 0.23%   |
| ViewSonic               | 6         | 0.2%    |
| Unknown                 | 6         | 0.2%    |
| Seiko/Epson             | 5         | 0.17%   |
| Panasonic               | 5         | 0.17%   |
| MSI                     | 5         | 0.17%   |
| NEC Computers           | 4         | 0.13%   |
| Mi                      | 4         | 0.13%   |
| Toshiba                 | 3         | 0.1%    |
| TMX                     | 3         | 0.1%    |
| Hitachi                 | 3         | 0.1%    |
| BOE Technology Group    | 3         | 0.1%    |
| AGO                     | 3         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 65        | 2.15%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 37        | 1.22%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 31        | 1.02%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 30        | 0.99%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 27        | 0.89%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.69%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.69%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 19        | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 18        | 0.59%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 17        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 17        | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.56%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.56%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 16        | 0.53%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 15        | 0.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 14        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 14        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.46%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 14        | 0.46%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 14        | 0.46%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 13        | 0.43%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 13        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.43%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.43%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 13        | 0.43%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 12        | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.36%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 11        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 11        | 0.36%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 10        | 0.33%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 10        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch         | 10        | 0.33%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 10        | 0.33%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 9         | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 9         | 0.3%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 9         | 0.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 9         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1128      | 40.5%   |
| 1366x768 (WXGA)    | 932       | 33.46%  |
| 1280x800 (WXGA)    | 160       | 5.75%   |
| 3840x2160 (4K)     | 76        | 2.73%   |
| 1600x900 (HD+)     | 73        | 2.62%   |
| 1440x900 (WXGA+)   | 58        | 2.08%   |
| 2560x1440 (QHD)    | 52        | 1.87%   |
| 1024x600           | 43        | 1.54%   |
| 1920x1200 (WUXGA)  | 32        | 1.15%   |
| 1280x1024 (SXGA)   | 31        | 1.11%   |
| 1680x1050 (WSXGA+) | 26        | 0.93%   |
| 2560x1600          | 24        | 0.86%   |
| 2160x1440          | 23        | 0.83%   |
| 800x1280           | 15        | 0.54%   |
| 3440x1440          | 13        | 0.47%   |
| 2880x1800          | 13        | 0.47%   |
| 2560x1080          | 13        | 0.47%   |
| 3200x1800 (QHD+)   | 7         | 0.25%   |
| 1360x768           | 7         | 0.25%   |
| 1024x768 (XGA)     | 7         | 0.25%   |
| 3840x2400          | 6         | 0.22%   |
| Unknown            | 5         | 0.18%   |
| 2288x1287          | 3         | 0.11%   |
| 1920x540           | 3         | 0.11%   |
| 1920x1280          | 3         | 0.11%   |
| 1600x1200          | 3         | 0.11%   |
| 1400x1050          | 3         | 0.11%   |
| 1280x768           | 3         | 0.11%   |
| 3840x1080          | 2         | 0.07%   |
| 3456x2160          | 2         | 0.07%   |
| 3200x2000          | 2         | 0.07%   |
| 3072x1920          | 2         | 0.07%   |
| 2304x1440          | 2         | 0.07%   |
| 5760x1080          | 1         | 0.04%   |
| 3840x1600          | 1         | 0.04%   |
| 3200x1080          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2736x1824          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1469      | 49.06%  |
| 13      | 344       | 11.49%  |
| 14      | 250       | 8.35%   |
| 17      | 167       | 5.58%   |
| 24      | 101       | 3.37%   |
| 27      | 86        | 2.87%   |
| 23      | 79        | 2.64%   |
| 21      | 79        | 2.64%   |
| 12      | 58        | 1.94%   |
| 10      | 50        | 1.67%   |
| 11      | 46        | 1.54%   |
| Unknown | 44        | 1.47%   |
| 16      | 38        | 1.27%   |
| 34      | 27        | 0.9%    |
| 31      | 24        | 0.8%    |
| 19      | 20        | 0.67%   |
| 18      | 14        | 0.47%   |
| 84      | 13        | 0.43%   |
| 20      | 13        | 0.43%   |
| 22      | 8         | 0.27%   |
| 7       | 8         | 0.27%   |
| 72      | 7         | 0.23%   |
| 40      | 7         | 0.23%   |
| 25      | 7         | 0.23%   |
| 54      | 5         | 0.17%   |
| 52      | 3         | 0.1%    |
| 46      | 3         | 0.1%    |
| 38      | 3         | 0.1%    |
| 26      | 3         | 0.1%    |
| 8       | 3         | 0.1%    |
| 142     | 2         | 0.07%   |
| 32      | 2         | 0.07%   |
| 65      | 1         | 0.03%   |
| 57      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 47      | 1         | 0.03%   |
| 42      | 1         | 0.03%   |
| 37      | 1         | 0.03%   |
| 36      | 1         | 0.03%   |
| 35      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1861      | 62.72%  |
| 201-300        | 362       | 12.2%   |
| 501-600        | 253       | 8.53%   |
| 351-400        | 203       | 6.84%   |
| 401-500        | 121       | 4.08%   |
| Unknown        | 44        | 1.48%   |
| 601-700        | 32        | 1.08%   |
| 701-800        | 29        | 0.98%   |
| 1501-2000      | 20        | 0.67%   |
| 1001-1500      | 15        | 0.51%   |
| 801-900        | 12        | 0.4%    |
| 1-100          | 9         | 0.3%    |
| 101-200        | 3         | 0.1%    |
| More than 2000 | 2         | 0.07%   |
| 901-1000       | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2153      | 81.71%  |
| 16/10   | 324       | 12.3%   |
| 3/2     | 37        | 1.4%    |
| 5/4     | 30        | 1.14%   |
| Unknown | 28        | 1.06%   |
| 21/9    | 27        | 1.02%   |
| 4/3     | 15        | 0.57%   |
| 0.67    | 8         | 0.3%    |
| 0.62    | 8         | 0.3%    |
| 1.00    | 2         | 0.08%   |
| 32/9    | 1         | 0.04%   |
| 1.03    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1478      | 49.48%  |
| 81-90          | 427       | 14.3%   |
| 201-250        | 225       | 7.53%   |
| 71-80          | 162       | 5.42%   |
| 121-130        | 118       | 3.95%   |
| 301-350        | 86        | 2.88%   |
| 61-70          | 55        | 1.84%   |
| 351-500        | 52        | 1.74%   |
| 151-200        | 52        | 1.74%   |
| 41-50          | 50        | 1.67%   |
| 51-60          | 46        | 1.54%   |
| Unknown        | 44        | 1.47%   |
| 131-140        | 34        | 1.14%   |
| More than 1000 | 33        | 1.1%    |
| 141-150        | 29        | 0.97%   |
| 251-300        | 28        | 0.94%   |
| 111-120        | 21        | 0.7%    |
| 501-1000       | 18        | 0.6%    |
| 91-100         | 17        | 0.57%   |
| 1-40           | 12        | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1052      | 35.98%  |
| 101-120       | 970       | 33.17%  |
| 51-100        | 573       | 19.6%   |
| 161-240       | 191       | 6.53%   |
| More than 240 | 59        | 2.02%   |
| Unknown       | 44        | 1.5%    |
| 1-50          | 35        | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2173      | 78.99%  |
| 2     | 430       | 15.63%  |
| 0     | 89        | 3.24%   |
| 3     | 54        | 1.96%   |
| 4     | 5         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1500      | 34.55%  |
| Intel                                  | 1270      | 29.25%  |
| Qualcomm Atheros                       | 690       | 15.89%  |
| Broadcom                               | 329       | 7.58%   |
| Broadcom Limited                       | 75        | 1.73%   |
| Marvell Technology Group               | 69        | 1.59%   |
| Ralink                                 | 45        | 1.04%   |
| TP-Link                                | 44        | 1.01%   |
| MediaTek                               | 41        | 0.94%   |
| Ralink Technology                      | 36        | 0.83%   |
| Nvidia                                 | 19        | 0.44%   |
| ASIX Electronics                       | 19        | 0.44%   |
| Samsung Electronics                    | 18        | 0.41%   |
| Xiaomi                                 | 17        | 0.39%   |
| JMicron Technology                     | 14        | 0.32%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.3%    |
| Dell                                   | 13        | 0.3%    |
| Hewlett-Packard                        | 12        | 0.28%   |
| Lenovo                                 | 11        | 0.25%   |
| Ericsson Business Mobile Networks      | 11        | 0.25%   |
| Sierra Wireless                        | 10        | 0.23%   |
| Qualcomm Atheros Communications        | 9         | 0.21%   |
| Qualcomm                               | 9         | 0.21%   |
| DisplayLink                            | 9         | 0.21%   |
| Huawei Technologies                    | 5         | 0.12%   |
| D-Link                                 | 5         | 0.12%   |
| VIA Technologies                       | 4         | 0.09%   |
| LSI                                    | 4         | 0.09%   |
| Edimax Technology                      | 4         | 0.09%   |
| Attansic Technology                    | 4         | 0.09%   |
| ASUSTek Computer                       | 4         | 0.09%   |
| Toshiba                                | 3         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| FIBOCOM                                | 2         | 0.05%   |
| Arduino SA                             | 2         | 0.05%   |
| Accton Technology                      | 2         | 0.05%   |
| T & A Mobile Phones                    | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Sitecom Europe                         | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 859       | 16.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 267       | 5.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 118       | 2.31%   |
| Intel Wi-Fi 6 AX200                                                     | 111       | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 110       | 2.15%   |
| Intel Wi-Fi 6 AX201                                                     | 102       | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 101       | 1.98%   |
| Intel Wireless 8265 / 8275                                              | 101       | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 98        | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 94        | 1.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 93        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 82        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 78        | 1.53%   |
| Intel Wireless 7265                                                     | 72        | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 61        | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 61        | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 61        | 1.19%   |
| Intel Wireless 7260                                                     | 60        | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 56        | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 54        | 1.06%   |
| Intel Wireless 3165                                                     | 53        | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 52        | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                           | 51        | 1%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 45        | 0.88%   |
| Intel WiFi Link 5100                                                    | 40        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 40        | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 37        | 0.72%   |
| Intel Wireless 8260                                                     | 35        | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 35        | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 35        | 0.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 35        | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 34        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 33        | 0.65%   |
| Intel Wireless 3160                                                     | 33        | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 30        | 0.59%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 30        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 29        | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 28        | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 27        | 0.53%   |
| Intel Centrino Advanced-N 6200                                          | 26        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1225      | 43.94%  |
| Qualcomm Atheros                | 578       | 20.73%  |
| Realtek Semiconductor           | 504       | 18.08%  |
| Broadcom                        | 221       | 7.93%   |
| Broadcom Limited                | 51        | 1.83%   |
| Ralink                          | 45        | 1.61%   |
| MediaTek                        | 40        | 1.43%   |
| Ralink Technology               | 36        | 1.29%   |
| TP-Link                         | 29        | 1.04%   |
| Sierra Wireless                 | 10        | 0.36%   |
| Qualcomm Atheros Communications | 9         | 0.32%   |
| Dell                            | 8         | 0.29%   |
| D-Link                          | 5         | 0.18%   |
| Qualcomm                        | 4         | 0.14%   |
| Hewlett-Packard                 | 4         | 0.14%   |
| Edimax Technology               | 4         | 0.14%   |
| ASUSTek Computer                | 4         | 0.14%   |
| FIBOCOM                         | 2         | 0.07%   |
| Accton Technology               | 2         | 0.07%   |
| Sitecom Europe                  | 1         | 0.04%   |
| NetGear                         | 1         | 0.04%   |
| Linksys                         | 1         | 0.04%   |
| Gemtek                          | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| AirTies Wireless Networks       | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 111       | 3.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 110       | 3.92%   |
| Intel Wi-Fi 6 AX201                                                     | 102       | 3.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 101       | 3.6%    |
| Intel Wireless 8265 / 8275                                              | 101       | 3.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 98        | 3.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 94        | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 93        | 3.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 82        | 2.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 78        | 2.78%   |
| Intel Wireless 7265                                                     | 72        | 2.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 61        | 2.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 61        | 2.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 61        | 2.18%   |
| Intel Wireless 7260                                                     | 60        | 2.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 56        | 2%      |
| Intel Wireless 3165                                                     | 53        | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 52        | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 51        | 1.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 45        | 1.6%    |
| Intel WiFi Link 5100                                                    | 40        | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 40        | 1.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 37        | 1.32%   |
| Intel Wireless 8260                                                     | 35        | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 35        | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 35        | 1.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 35        | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 33        | 1.18%   |
| Intel Wireless 3160                                                     | 33        | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 30        | 1.07%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 28        | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 27        | 0.96%   |
| Intel Centrino Advanced-N 6200                                          | 26        | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 25        | 0.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 24        | 0.86%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 24        | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 23        | 0.82%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 23        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 21        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 18        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1284      | 57.58%  |
| Intel                                  | 349       | 15.65%  |
| Qualcomm Atheros                       | 185       | 8.3%    |
| Broadcom                               | 148       | 6.64%   |
| Marvell Technology Group               | 69        | 3.09%   |
| Broadcom Limited                       | 26        | 1.17%   |
| Nvidia                                 | 19        | 0.85%   |
| ASIX Electronics                       | 19        | 0.85%   |
| Samsung Electronics                    | 18        | 0.81%   |
| Xiaomi                                 | 17        | 0.76%   |
| TP-Link                                | 15        | 0.67%   |
| JMicron Technology                     | 14        | 0.63%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.58%   |
| Lenovo                                 | 11        | 0.49%   |
| DisplayLink                            | 9         | 0.4%    |
| Qualcomm                               | 5         | 0.22%   |
| VIA Technologies                       | 4         | 0.18%   |
| LSI                                    | 4         | 0.18%   |
| Hewlett-Packard                        | 4         | 0.18%   |
| Attansic Technology                    | 4         | 0.18%   |
| Huawei Technologies                    | 2         | 0.09%   |
| Google                                 | 2         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| OPPO Electronics                       | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| National Semiconductor                 | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| MediaTek                               | 1         | 0.04%   |
| Davicom Semiconductor                  | 1         | 0.04%   |
| Apple                                  | 1         | 0.04%   |
| ADMtek                                 | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 859       | 38.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 267       | 11.81%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 118       | 5.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 54        | 2.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 34        | 1.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 30        | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29        | 1.28%   |
| Intel 82577LM Gigabit Network Connection                          | 25        | 1.11%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 20        | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 0.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 18        | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 17        | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 16        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 16        | 0.71%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.71%   |
| Intel Ethernet Connection (13) I219-V                             | 16        | 0.71%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 15        | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.66%   |
| Nvidia MCP79 Ethernet                                             | 14        | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 14        | 0.62%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 14        | 0.62%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 12        | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 12        | 0.53%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 0.53%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.53%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.53%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 12        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.49%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 11        | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 10        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2630      | 54.37%  |
| Ethernet | 2163      | 44.72%  |
| Modem    | 42        | 0.87%   |
| Unknown  | 2         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2142      | 75.48%  |
| Ethernet | 696       | 24.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1955      | 72.73%  |
| 1     | 663       | 24.67%  |
| 0     | 57        | 2.12%   |
| 3     | 12        | 0.45%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2605      | 96.45%  |
| Yes  | 96        | 3.55%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 925       | 46.23%  |
| Realtek Semiconductor           | 248       | 12.39%  |
| IMC Networks                    | 149       | 7.45%   |
| Qualcomm Atheros Communications | 136       | 6.8%    |
| Lite-On Technology              | 95        | 4.75%   |
| Broadcom                        | 90        | 4.5%    |
| Foxconn / Hon Hai               | 83        | 4.15%   |
| Apple                           | 58        | 2.9%    |
| Toshiba                         | 36        | 1.8%    |
| Realtek                         | 36        | 1.8%    |
| Cambridge Silicon Radio         | 34        | 1.7%    |
| Dell                            | 27        | 1.35%   |
| Hewlett-Packard                 | 23        | 1.15%   |
| Ralink                          | 17        | 0.85%   |
| ASUSTek Computer                | 13        | 0.65%   |
| Alps Electric                   | 13        | 0.65%   |
| Foxconn International           | 8         | 0.4%    |
| Ralink Technology               | 4         | 0.2%    |
| Taiyo Yuden                     | 2         | 0.1%    |
| Askey Computer                  | 2         | 0.1%    |
| MediaTek                        | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 349       | 17.44%  |
| Intel AX201 Bluetooth                               | 192       | 9.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 171       | 8.55%   |
| Realtek Bluetooth Radio                             | 165       | 8.25%   |
| Intel AX200 Bluetooth                               | 109       | 5.45%   |
| IMC Networks Bluetooth Radio                        | 76        | 3.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 54        | 2.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 50        | 2.5%    |
| IMC Networks Bluetooth Device                       | 38        | 1.9%    |
| Foxconn / Hon Hai Bluetooth Device                  | 38        | 1.9%    |
| Realtek Bluetooth Radio                             | 36        | 1.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 34        | 1.7%    |
| Apple Bluetooth Host Controller                     | 34        | 1.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 32        | 1.6%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 28        | 1.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 24        | 1.2%    |
| Lite-On Bluetooth Device                            | 24        | 1.2%    |
| Lite-On Atheros AR3012 Bluetooth                    | 24        | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                    | 20        | 1%      |
| Intel Bluetooth Device                              | 19        | 0.95%   |
| IMC Networks Wireless_Device                        | 19        | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 18        | 0.9%    |
| Intel AX210 Bluetooth                               | 18        | 0.9%    |
| Ralink RT3290 Bluetooth                             | 17        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 0.85%   |
| Apple Bluetooth USB Host Controller                 | 16        | 0.8%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.75%   |
| Foxconn / Hon Hai Wireless_Device                   | 14        | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 0.65%   |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.55%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.55%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 11        | 0.55%   |
| Realtek RTL8821A Bluetooth                          | 10        | 0.5%    |
| Broadcom BCM2045 Bluetooth                          | 9         | 0.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.4%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.4%    |
| Foxconn International BCM43142A0 Bluetooth module   | 8         | 0.4%    |
| Dell DW375 Bluetooth Module                         | 8         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2145      | 66.18%  |
| AMD                                  | 543       | 16.75%  |
| Nvidia                               | 370       | 11.42%  |
| C-Media Electronics                  | 23        | 0.71%   |
| Logitech                             | 17        | 0.52%   |
| Silicon Integrated Systems [SiS]     | 13        | 0.4%    |
| Lenovo                               | 13        | 0.4%    |
| GN Netcom                            | 10        | 0.31%   |
| Plantronics                          | 9         | 0.28%   |
| Realtek Semiconductor                | 7         | 0.22%   |
| JMTek                                | 7         | 0.22%   |
| VIA Technologies                     | 5         | 0.15%   |
| Texas Instruments                    | 5         | 0.15%   |
| Kingston Technology                  | 5         | 0.15%   |
| Generalplus Technology               | 4         | 0.12%   |
| Corsair                              | 4         | 0.12%   |
| SteelSeries ApS                      | 3         | 0.09%   |
| Sennheiser Communications            | 3         | 0.09%   |
| Hewlett-Packard                      | 3         | 0.09%   |
| Creative Technology                  | 3         | 0.09%   |
| BEHRINGER International              | 3         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.06%   |
| No brand                             | 2         | 0.06%   |
| Guillemot                            | 2         | 0.06%   |
| CMX Systems                          | 2         | 0.06%   |
| Blue Microphones                     | 2         | 0.06%   |
| ASUSTek Computer                     | 2         | 0.06%   |
| Apple                                | 2         | 0.06%   |
| Alesis                               | 2         | 0.06%   |
| Vestax                               | 1         | 0.03%   |
| Veho                                 | 1         | 0.03%   |
| Unknown (ABC)                        | 1         | 0.03%   |
| Trust                                | 1         | 0.03%   |
| ThrustMaster                         | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |
| Sony                                 | 1         | 0.03%   |
| Signalpath International             | 1         | 0.03%   |
| Samsung Electronics                  | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |
| PreSonus Audio Electronics           | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 283       | 7.25%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 256       | 6.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 155       | 3.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 139       | 3.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 136       | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 133       | 3.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 131       | 3.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 124       | 3.18%   |
| Intel Cannon Lake PCH cAVS                                                                        | 124       | 3.18%   |
| Intel 8 Series HD Audio Controller                                                                | 124       | 3.18%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 109       | 2.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 97        | 2.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 96        | 2.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 87        | 2.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 85        | 2.18%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 85        | 2.18%   |
| Intel Broadwell-U Audio Controller                                                                | 83        | 2.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 78        | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 73        | 1.87%   |
| AMD FCH Azalia Controller                                                                         | 73        | 1.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 68        | 1.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 64        | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 59        | 1.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 57        | 1.46%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 49        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 49        | 1.25%   |
| AMD High Definition Audio Controller                                                              | 48        | 1.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 47        | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 44        | 1.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 39        | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 39        | 1%      |
| Nvidia TU106 High Definition Audio Controller                                                     | 37        | 0.95%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 37        | 0.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 37        | 0.95%   |
| Intel CM238 HD Audio Controller                                                                   | 36        | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 34        | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 30        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 29        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 27        | 0.69%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 26        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 496       | 30.19%  |
| SK hynix                     | 350       | 21.3%   |
| Micron Technology            | 206       | 12.54%  |
| Kingston                     | 155       | 9.43%   |
| Unknown                      | 129       | 7.85%   |
| Crucial                      | 84        | 5.11%   |
| Ramaxel Technology           | 55        | 3.35%   |
| Elpida                       | 26        | 1.58%   |
| Unknown (ABCD)               | 24        | 1.46%   |
| A-DATA Technology            | 19        | 1.16%   |
| Nanya Technology             | 15        | 0.91%   |
| Corsair                      | 14        | 0.85%   |
| G.Skill                      | 11        | 0.67%   |
| Silicon Power                | 9         | 0.55%   |
| Unknown                      | 7         | 0.43%   |
| GOODRAM                      | 6         | 0.37%   |
| Transcend                    | 5         | 0.3%    |
| Wilk                         | 3         | 0.18%   |
| Apacer                       | 3         | 0.18%   |
| SHARETRONIC                  | 2         | 0.12%   |
| Patriot                      | 2         | 0.12%   |
| KomputerBay                  | 2         | 0.12%   |
| Avant                        | 2         | 0.12%   |
| Unifosa                      | 1         | 0.06%   |
| Toshiba                      | 1         | 0.06%   |
| Timetec                      | 1         | 0.06%   |
| Team                         | 1         | 0.06%   |
| Qimonda                      | 1         | 0.06%   |
| PNY                          | 1         | 0.06%   |
| Patriot Memory (PDP Systems) | 1         | 0.06%   |
| Netlist                      | 1         | 0.06%   |
| Netac                        | 1         | 0.06%   |
| Neo Forza                    | 1         | 0.06%   |
| Micron/Elpida                | 1         | 0.06%   |
| Kllisre                      | 1         | 0.06%   |
| Kembona                      | 1         | 0.06%   |
| ff                           | 1         | 0.06%   |
| CSX                          | 1         | 0.06%   |
| Atermiter                    | 1         | 0.06%   |
| ASint Technology             | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 28        | 1.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 1.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 24        | 1.4%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 22        | 1.28%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 20        | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 1.17%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 1.11%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 18        | 1.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.93%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.93%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 16        | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.93%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.93%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 15        | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 13        | 0.76%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 13        | 0.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.76%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.64%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.64%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 10        | 0.58%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.58%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 10        | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.58%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 10        | 0.58%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 10        | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 10        | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.52%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 9         | 0.52%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 9         | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.52%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.52%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 9         | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 677       | 48.67%  |
| DDR3    | 432       | 31.06%  |
| DDR2    | 85        | 6.11%   |
| LPDDR4  | 73        | 5.25%   |
| LPDDR3  | 51        | 3.67%   |
| SDRAM   | 29        | 2.08%   |
| DDR5    | 17        | 1.22%   |
| Unknown | 9         | 0.65%   |
| DDR     | 7         | 0.5%    |
| DRAM    | 6         | 0.43%   |
| LPDDR5  | 5         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1244      | 88.6%   |
| Row Of Chips | 142       | 10.11%  |
| DIMM         | 9         | 0.64%   |
| Chip         | 8         | 0.57%   |
| Unknown      | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 583       | 38.63%  |
| 4096  | 438       | 29.03%  |
| 16384 | 219       | 14.51%  |
| 2048  | 174       | 11.53%  |
| 1024  | 58        | 3.84%   |
| 32768 | 30        | 1.99%   |
| 512   | 4         | 0.27%   |
| 256   | 2         | 0.13%   |
| 3072  | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 314       | 20.96%  |
| 1600    | 290       | 19.36%  |
| 3200    | 279       | 18.62%  |
| 2400    | 106       | 7.08%   |
| 2133    | 71        | 4.74%   |
| 1334    | 71        | 4.74%   |
| 667     | 60        | 4.01%   |
| 1333    | 53        | 3.54%   |
| Unknown | 39        | 2.6%    |
| 8400    | 28        | 1.87%   |
| 4267    | 27        | 1.8%    |
| 1067    | 25        | 1.67%   |
| 4800    | 18        | 1.2%    |
| 1867    | 17        | 1.13%   |
| 3266    | 16        | 1.07%   |
| 800     | 16        | 1.07%   |
| 533     | 12        | 0.8%    |
| 4199    | 11        | 0.73%   |
| 2048    | 9         | 0.6%    |
| 6400    | 6         | 0.4%    |
| 4266    | 6         | 0.4%    |
| 1066    | 6         | 0.4%    |
| 975     | 5         | 0.33%   |
| 2933    | 2         | 0.13%   |
| 1639    | 2         | 0.13%   |
| 1200    | 2         | 0.13%   |
| 3733    | 1         | 0.07%   |
| 3000    | 1         | 0.07%   |
| 1866    | 1         | 0.07%   |
| 1776    | 1         | 0.07%   |
| 666     | 1         | 0.07%   |
| 333     | 1         | 0.07%   |
| 266     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 12        | 52.17%  |
| Seiko Epson        | 4         | 17.39%  |
| Canon              | 4         | 17.39%  |
| Brother Industries | 3         | 13.04%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Canon PIXMA MG2500 Series        | 3         | 13.04%  |
| Seiko Epson XP-230 Series        | 1         | 4.35%   |
| Seiko Epson Printer              | 1         | 4.35%   |
| Seiko Epson L555 Series          | 1         | 4.35%   |
| Seiko Epson ET-2700 Series       | 1         | 4.35%   |
| HP PSC 1500 series               | 1         | 4.35%   |
| HP Printing Support              | 1         | 4.35%   |
| HP LaserJet Professional P 1102w | 1         | 4.35%   |
| HP LaserJet Pro M404-M405        | 1         | 4.35%   |
| HP LaserJet 1320                 | 1         | 4.35%   |
| HP LaserJet 1020                 | 1         | 4.35%   |
| HP LaserJet 1018                 | 1         | 4.35%   |
| HP LaserJet 1000                 | 1         | 4.35%   |
| HP DeskJet F300 series           | 1         | 4.35%   |
| HP DeskJet F2492 All-in-One      | 1         | 4.35%   |
| HP DeskJet 2600 series           | 1         | 4.35%   |
| HP Deskjet 2050 J510             | 1         | 4.35%   |
| Canon TS3100 series              | 1         | 4.35%   |
| Brother MFC-J5330DW              | 1         | 4.35%   |
| Brother HL-2030 Laser Printer    | 1         | 4.35%   |
| Brother HL-1210W series          | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP ScanJet 4300c              | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30 | 1         | 33.33%  |
| Canon CanoScan LiDE 210       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 606       | 26.13%  |
| IMC Networks                           | 288       | 12.42%  |
| Acer                                   | 228       | 9.83%   |
| Realtek Semiconductor                  | 155       | 6.68%   |
| Microdia                               | 148       | 6.38%   |
| Suyin                                  | 118       | 5.09%   |
| Quanta                                 | 117       | 5.05%   |
| Sunplus Innovation Technology          | 96        | 4.14%   |
| Cheng Uei Precision Industry (Foxlink) | 93        | 4.01%   |
| Syntek                                 | 70        | 3.02%   |
| Alcor Micro                            | 45        | 1.94%   |
| Apple                                  | 38        | 1.64%   |
| Lite-On Technology                     | 36        | 1.55%   |
| Luxvisions Innotech Limited            | 35        | 1.51%   |
| Ricoh                                  | 31        | 1.34%   |
| Bison Electronics                      | 22        | 0.95%   |
| Logitech                               | 21        | 0.91%   |
| Silicon Motion                         | 20        | 0.86%   |
| Sonix Technology                       | 11        | 0.47%   |
| Samsung Electronics                    | 11        | 0.47%   |
| USB Camera                             | 10        | 0.43%   |
| Z-Star Microelectronics                | 9         | 0.39%   |
| Lenovo                                 | 9         | 0.39%   |
| Importek                               | 9         | 0.39%   |
| ALi                                    | 9         | 0.39%   |
| Intel                                  | 7         | 0.3%    |
| GEMBIRD                                | 7         | 0.3%    |
| Sunplus Technology                     | 6         | 0.26%   |
| Primax Electronics                     | 6         | 0.26%   |
| OmniVision Technologies                | 5         | 0.22%   |
| KYE Systems (Mouse Systems)            | 5         | 0.22%   |
| DigiTech                               | 5         | 0.22%   |
| Genesys Logic                          | 4         | 0.17%   |
| ARC International                      | 4         | 0.17%   |
| Trust                                  | 3         | 0.13%   |
| webcam                                 | 2         | 0.09%   |
| Novatek Microelectronics               | 2         | 0.09%   |
| Microsoft                              | 2         | 0.09%   |
| Generalplus Technology                 | 2         | 0.09%   |
| Creative Technology                    | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 75        | 3.22%   |
| Chicony HD WebCam                                       | 68        | 2.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 66        | 2.84%   |
| Chicony Integrated Camera                               | 64        | 2.75%   |
| Microdia Integrated_Webcam_HD                           | 58        | 2.49%   |
| Acer HD Webcam                                          | 57        | 2.45%   |
| IMC Networks Integrated Camera                          | 44        | 1.89%   |
| Acer Integrated Camera                                  | 43        | 1.85%   |
| Chicony USB2.0 VGA UVC WebCam                           | 40        | 1.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 32        | 1.38%   |
| Realtek Integrated_Webcam_HD                            | 31        | 1.33%   |
| Quanta HP TrueVision HD Camera                          | 29        | 1.25%   |
| Sunplus HD WebCam                                       | 27        | 1.16%   |
| Realtek USB Camera                                      | 27        | 1.16%   |
| Chicony TOSHIBA Web Camera - HD                         | 26        | 1.12%   |
| Chicony EasyCamera                                      | 25        | 1.07%   |
| Syntek Integrated Camera                                | 23        | 0.99%   |
| Chicony USB 2.0 Camera                                  | 23        | 0.99%   |
| Acer EasyCamera                                         | 20        | 0.86%   |
| Chicony USB2.0 HD UVC WebCam                            | 19        | 0.82%   |
| Chicony USB2.0 Camera                                   | 19        | 0.82%   |
| Acer HD Camera                                          | 19        | 0.82%   |
| Syntek Lenovo EasyCamera                                | 18        | 0.77%   |
| Syntek EasyCamera                                       | 18        | 0.77%   |
| Chicony VGA Webcam                                      | 18        | 0.77%   |
| Chicony HP Truevision HD                                | 18        | 0.77%   |
| Realtek Lenovo EasyCamera                               | 17        | 0.73%   |
| Lite-On Integrated Camera                               | 17        | 0.73%   |
| Chicony Integrated Camera (1280x720@30)                 | 17        | 0.73%   |
| Apple Built-in iSight                                   | 17        | 0.73%   |
| Alcor Micro Asus Integrated Webcam                      | 17        | 0.73%   |
| Acer Lenovo EasyCamera                                  | 17        | 0.73%   |
| IMC Networks ov9734_azurewave_camera                    | 16        | 0.69%   |
| Chicony HP HD Camera                                    | 16        | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 16        | 0.69%   |
| Quanta HP HD Camera                                     | 15        | 0.64%   |
| Microdia Webcam Vitade AF                               | 15        | 0.64%   |
| Microdia Integrated Webcam                              | 15        | 0.64%   |
| Sunplus Integrated_Webcam_HD                            | 14        | 0.6%    |
| Chicony HP TrueVision HD Camera                         | 14        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 104       | 28.18%  |
| Validity Sensors           | 87        | 23.58%  |
| Shenzhen Goodix Technology | 62        | 16.8%   |
| Elan Microelectronics      | 38        | 10.3%   |
| AuthenTec                  | 36        | 9.76%   |
| Upek                       | 25        | 6.78%   |
| LighTuning Technology      | 10        | 2.71%   |
| STMicroelectronics         | 7         | 1.9%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 47        | 12.74%  |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 34        | 9.21%   |
| Elan ELAN:Fingerprint                                                      | 34        | 9.21%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 28        | 7.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 5.42%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 5.15%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 4.07%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 3.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 2.98%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.98%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.9%    |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.9%    |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.63%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.63%   |
| AuthenTec AES1600                                                          | 6         | 1.63%   |
| Validity Sensors VFS491                                                    | 5         | 1.36%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.36%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.36%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1.36%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.36%   |
| AuthenTec AES2810                                                          | 5         | 1.36%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 1.36%   |
| Synaptics  WBDI                                                            | 4         | 1.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.08%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.08%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.81%   |
| Synaptics UWP WBDI                                                         | 3         | 0.81%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 0.81%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.81%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.81%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.54%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.54%   |
| Synaptics WBDI                                                             | 2         | 0.54%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.54%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 56        | 35.22%  |
| Broadcom              | 53        | 33.33%  |
| O2 Micro              | 23        | 14.47%  |
| Lenovo                | 8         | 5.03%   |
| Upek                  | 4         | 2.52%   |
| C3PO                  | 4         | 2.52%   |
| Realtek Semiconductor | 3         | 1.89%   |
| Cherry                | 3         | 1.89%   |
| Gemalto (was Gemplus) | 2         | 1.26%   |
| In Focus Systems      | 1         | 0.63%   |
| Chicony Electronics   | 1         | 0.63%   |
| Advanced Card Systems | 1         | 0.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 56        | 35.22%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 13.84%  |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 11.32%  |
| Broadcom 5880                                                                | 16        | 10.06%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 5.66%   |
| Broadcom 58200                                                               | 9         | 5.66%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 5.03%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.52%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.89%   |
| Cherry SmartTerminal XX1X                                                    | 3         | 1.89%   |
| C3PO LTC31v2                                                                 | 3         | 1.89%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.26%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.63%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.63%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.63%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.63%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1783      | 64.6%   |
| 1     | 752       | 27.25%  |
| 2     | 190       | 6.88%   |
| 3     | 24        | 0.87%   |
| 4     | 7         | 0.25%   |
| 5     | 3         | 0.11%   |
| 8     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 360       | 29.9%   |
| Graphics card            | 298       | 24.75%  |
| Net/wireless             | 157       | 13.04%  |
| Chipcard                 | 138       | 11.46%  |
| Multimedia controller    | 69        | 5.73%   |
| Camera                   | 43        | 3.57%   |
| Bluetooth                | 27        | 2.24%   |
| Storage                  | 25        | 2.08%   |
| Communication controller | 24        | 1.99%   |
| Card reader              | 17        | 1.41%   |
| Sound                    | 11        | 0.91%   |
| Net/ethernet             | 11        | 0.91%   |
| Flash memory             | 10        | 0.83%   |
| Modem                    | 8         | 0.66%   |
| Network                  | 3         | 0.25%   |
| Dvb card                 | 3         | 0.25%   |

