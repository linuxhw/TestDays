Gentoo - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Gentoo.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo/Desktop/README.md) and [notebooks](/Dist/Gentoo/Notebook/README.md).

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

Total: 2660

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [4cb72d56f7](https://linux-hardware.org/?probe=4cb72d56f7) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [26262445d4](https://linux-hardware.org/?probe=26262445d4) | Jun 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8632ddc565](https://linux-hardware.org/?probe=8632ddc565) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | Notebook    | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [87f789c059](https://linux-hardware.org/?probe=87f789c059) | Jun 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [96256dca48](https://linux-hardware.org/?probe=96256dca48) | Jun 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e7c8a1c727](https://linux-hardware.org/?probe=e7c8a1c727) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [50304f8088](https://linux-hardware.org/?probe=50304f8088) | Jun 06, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [60bf4b0442](https://linux-hardware.org/?probe=60bf4b0442) | Jun 05, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df787c227](https://linux-hardware.org/?probe=1df787c227) | Jun 05, 2023 |
| Dell          | Precision 5530              | Notebook    | [8b4e10b85a](https://linux-hardware.org/?probe=8b4e10b85a) | Jun 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [580ae6529e](https://linux-hardware.org/?probe=580ae6529e) | Jun 05, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [4d71226d7c](https://linux-hardware.org/?probe=4d71226d7c) | Jun 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d7ae224bea](https://linux-hardware.org/?probe=d7ae224bea) | Jun 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [4192000802](https://linux-hardware.org/?probe=4192000802) | Jun 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [168fa7f541](https://linux-hardware.org/?probe=168fa7f541) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [72fc2eea56](https://linux-hardware.org/?probe=72fc2eea56) | Jun 03, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [c1cfe9f08d](https://linux-hardware.org/?probe=c1cfe9f08d) | Jun 02, 2023 |
| Dell          | Precision 5530              | Notebook    | [151584f5aa](https://linux-hardware.org/?probe=151584f5aa) | Jun 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [9faf2de183](https://linux-hardware.org/?probe=9faf2de183) | Jun 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d2ce08a746](https://linux-hardware.org/?probe=d2ce08a746) | May 30, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df34e179b](https://linux-hardware.org/?probe=1df34e179b) | May 30, 2023 |
| Pegatron      | 2ACE                        | Desktop     | [fd6056dba8](https://linux-hardware.org/?probe=fd6056dba8) | May 29, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [edfe02a7ae](https://linux-hardware.org/?probe=edfe02a7ae) | May 29, 2023 |
| MSI           | GE76 Raider 11UH            | Notebook    | [64a17da7a3](https://linux-hardware.org/?probe=64a17da7a3) | May 28, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [2bb14772ce](https://linux-hardware.org/?probe=2bb14772ce) | May 28, 2023 |
| Lenovo        | 1036 SDK0Q40112 WIN 3305... | Desktop     | [5384efc9d9](https://linux-hardware.org/?probe=5384efc9d9) | May 28, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [39f6ad44fe](https://linux-hardware.org/?probe=39f6ad44fe) | May 28, 2023 |
| Supermicro    | H12SSL-CT                   | Server      | [00dea5aed8](https://linux-hardware.org/?probe=00dea5aed8) | May 28, 2023 |
| Lenovo        | 1036 SDK0Q40112 WIN 3305... | Desktop     | [f7a170dd7d](https://linux-hardware.org/?probe=f7a170dd7d) | May 28, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5162ff793e](https://linux-hardware.org/?probe=5162ff793e) | May 27, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [f4889c41be](https://linux-hardware.org/?probe=f4889c41be) | May 27, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [95231653d0](https://linux-hardware.org/?probe=95231653d0) | May 26, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8962578738](https://linux-hardware.org/?probe=8962578738) | May 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [852932c13b](https://linux-hardware.org/?probe=852932c13b) | May 26, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [08eec5e6ca](https://linux-hardware.org/?probe=08eec5e6ca) | May 26, 2023 |
| ASRock        | X670E Taichi                | Desktop     | [6c74d47711](https://linux-hardware.org/?probe=6c74d47711) | May 25, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [d44b92320b](https://linux-hardware.org/?probe=d44b92320b) | May 25, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [99bcbfbb2a](https://linux-hardware.org/?probe=99bcbfbb2a) | May 25, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [aa919fe5b3](https://linux-hardware.org/?probe=aa919fe5b3) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [a3798147d9](https://linux-hardware.org/?probe=a3798147d9) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [f2655b5798](https://linux-hardware.org/?probe=f2655b5798) | May 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [654aa3909f](https://linux-hardware.org/?probe=654aa3909f) | May 24, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [41ca623e3c](https://linux-hardware.org/?probe=41ca623e3c) | May 24, 2023 |
| ASRock        | Z170 OC Formula             | Desktop     | [d7a354fa41](https://linux-hardware.org/?probe=d7a354fa41) | May 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e4f2e7ecb6](https://linux-hardware.org/?probe=e4f2e7ecb6) | May 23, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [9063693561](https://linux-hardware.org/?probe=9063693561) | May 23, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [35a7542634](https://linux-hardware.org/?probe=35a7542634) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [7ad8de5a40](https://linux-hardware.org/?probe=7ad8de5a40) | May 22, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [e0611754f3](https://linux-hardware.org/?probe=e0611754f3) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [c956e9cbab](https://linux-hardware.org/?probe=c956e9cbab) | May 22, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e7af79968d](https://linux-hardware.org/?probe=e7af79968d) | May 22, 2023 |
| Foxconn       | TPS01                       | Desktop     | [385129d471](https://linux-hardware.org/?probe=385129d471) | May 21, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [46697ea0e2](https://linux-hardware.org/?probe=46697ea0e2) | May 20, 2023 |
| Foxconn       | TPS01                       | Desktop     | [853284b818](https://linux-hardware.org/?probe=853284b818) | May 20, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [7c52ccb596](https://linux-hardware.org/?probe=7c52ccb596) | May 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [22ef34bb50](https://linux-hardware.org/?probe=22ef34bb50) | May 20, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [f051e7f6da](https://linux-hardware.org/?probe=f051e7f6da) | May 20, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [8bd01d7d16](https://linux-hardware.org/?probe=8bd01d7d16) | May 19, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [3f5ffac86c](https://linux-hardware.org/?probe=3f5ffac86c) | May 19, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [7c4f12c4ed](https://linux-hardware.org/?probe=7c4f12c4ed) | May 18, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [beacb75b2c](https://linux-hardware.org/?probe=beacb75b2c) | May 18, 2023 |
| TYAN Compu... | S2505T                      | Desktop     | [a17c60c707](https://linux-hardware.org/?probe=a17c60c707) | May 16, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [9257bb2c1a](https://linux-hardware.org/?probe=9257bb2c1a) | May 16, 2023 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [4160bd4f84](https://linux-hardware.org/?probe=4160bd4f84) | May 16, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [6d60b321b1](https://linux-hardware.org/?probe=6d60b321b1) | May 16, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [a13951a75b](https://linux-hardware.org/?probe=a13951a75b) | May 16, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [b25434cdf3](https://linux-hardware.org/?probe=b25434cdf3) | May 15, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2b6c863711](https://linux-hardware.org/?probe=2b6c863711) | May 15, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4b1b35b4ec](https://linux-hardware.org/?probe=4b1b35b4ec) | May 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4a352d010e](https://linux-hardware.org/?probe=4a352d010e) | May 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0aa84055bf](https://linux-hardware.org/?probe=0aa84055bf) | May 15, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [7fe35591e7](https://linux-hardware.org/?probe=7fe35591e7) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Foxconn       | nT-330i                     | Desktop     | [b95166587e](https://linux-hardware.org/?probe=b95166587e) | May 14, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [334b015373](https://linux-hardware.org/?probe=334b015373) | May 14, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [4e208c9155](https://linux-hardware.org/?probe=4e208c9155) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [4b3b94a776](https://linux-hardware.org/?probe=4b3b94a776) | May 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [e172257a22](https://linux-hardware.org/?probe=e172257a22) | May 13, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| Supermicro    | X10SL7-F                    | Server      | [1cf183101b](https://linux-hardware.org/?probe=1cf183101b) | May 13, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b1b041ac47](https://linux-hardware.org/?probe=b1b041ac47) | May 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9f88d81e33](https://linux-hardware.org/?probe=9f88d81e33) | May 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [870c85a9ac](https://linux-hardware.org/?probe=870c85a9ac) | May 12, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [847d86e573](https://linux-hardware.org/?probe=847d86e573) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [721f9583d7](https://linux-hardware.org/?probe=721f9583d7) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9cbcc36a48](https://linux-hardware.org/?probe=9cbcc36a48) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0ae43bcc58](https://linux-hardware.org/?probe=0ae43bcc58) | May 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [49ad1e2075](https://linux-hardware.org/?probe=49ad1e2075) | May 09, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [afe5236688](https://linux-hardware.org/?probe=afe5236688) | May 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b5c0679341](https://linux-hardware.org/?probe=b5c0679341) | May 08, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [aa2af0a4bc](https://linux-hardware.org/?probe=aa2af0a4bc) | May 08, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [bfd53a8d28](https://linux-hardware.org/?probe=bfd53a8d28) | May 08, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a8e82695ee](https://linux-hardware.org/?probe=a8e82695ee) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c88845ae9b](https://linux-hardware.org/?probe=c88845ae9b) | May 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [82281ca3d5](https://linux-hardware.org/?probe=82281ca3d5) | May 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [5d774e899c](https://linux-hardware.org/?probe=5d774e899c) | May 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6aa9a8317d](https://linux-hardware.org/?probe=6aa9a8317d) | May 04, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [61cde0d9b2](https://linux-hardware.org/?probe=61cde0d9b2) | May 04, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [063e548538](https://linux-hardware.org/?probe=063e548538) | May 03, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [8ebf347e24](https://linux-hardware.org/?probe=8ebf347e24) | May 03, 2023 |
| Acer          | Swift SF314-41              | Notebook    | [520066013b](https://linux-hardware.org/?probe=520066013b) | May 03, 2023 |
| HP            | 1589                        | Desktop     | [c817b08584](https://linux-hardware.org/?probe=c817b08584) | May 02, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [6f015f949c](https://linux-hardware.org/?probe=6f015f949c) | May 02, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [a17449f761](https://linux-hardware.org/?probe=a17449f761) | May 02, 2023 |
| HP            | 1589                        | Desktop     | [890241aeb6](https://linux-hardware.org/?probe=890241aeb6) | May 02, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [77ef33da62](https://linux-hardware.org/?probe=77ef33da62) | May 02, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [1c158dca0e](https://linux-hardware.org/?probe=1c158dca0e) | May 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2a2bf698ed](https://linux-hardware.org/?probe=2a2bf698ed) | May 01, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c03693e806](https://linux-hardware.org/?probe=c03693e806) | May 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [a158a30802](https://linux-hardware.org/?probe=a158a30802) | Apr 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [eeb1550b82](https://linux-hardware.org/?probe=eeb1550b82) | Apr 29, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [855bed0070](https://linux-hardware.org/?probe=855bed0070) | Apr 28, 2023 |
| HP            | G62                         | Notebook    | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| ASUSTek       | N550JX                      | Notebook    | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [78b4f0cd2f](https://linux-hardware.org/?probe=78b4f0cd2f) | Apr 27, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [f3b21405ff](https://linux-hardware.org/?probe=f3b21405ff) | Apr 27, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a16e963c10](https://linux-hardware.org/?probe=a16e963c10) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8bc0a29b23](https://linux-hardware.org/?probe=8bc0a29b23) | Apr 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a48c247194](https://linux-hardware.org/?probe=a48c247194) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [11844fed4d](https://linux-hardware.org/?probe=11844fed4d) | Apr 25, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [b53354af62](https://linux-hardware.org/?probe=b53354af62) | Apr 25, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [fe2d361db9](https://linux-hardware.org/?probe=fe2d361db9) | Apr 25, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [c78c7e9ec1](https://linux-hardware.org/?probe=c78c7e9ec1) | Apr 24, 2023 |
| Dell          | Precision 7770              | Notebook    | [e9208415d5](https://linux-hardware.org/?probe=e9208415d5) | Apr 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7bbac9f9bf](https://linux-hardware.org/?probe=7bbac9f9bf) | Apr 24, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [35c362eb4f](https://linux-hardware.org/?probe=35c362eb4f) | Apr 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [0f7e30ded3](https://linux-hardware.org/?probe=0f7e30ded3) | Apr 23, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [f98c5f7d2e](https://linux-hardware.org/?probe=f98c5f7d2e) | Apr 23, 2023 |
| Gigabyte      | B460 HD3                    | Desktop     | [c9e3b1d5ea](https://linux-hardware.org/?probe=c9e3b1d5ea) | Apr 22, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [89b64bbfb6](https://linux-hardware.org/?probe=89b64bbfb6) | Apr 22, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [80ead18196](https://linux-hardware.org/?probe=80ead18196) | Apr 21, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [0f17162503](https://linux-hardware.org/?probe=0f17162503) | Apr 21, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [3d88744f22](https://linux-hardware.org/?probe=3d88744f22) | Apr 20, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [056db62b47](https://linux-hardware.org/?probe=056db62b47) | Apr 20, 2023 |
| Dell          | Latitude 7420               | Notebook    | [480290fd34](https://linux-hardware.org/?probe=480290fd34) | Apr 19, 2023 |
| Intel         | D510MO AAE76523-401         | Desktop     | [cf5c07a318](https://linux-hardware.org/?probe=cf5c07a318) | Apr 19, 2023 |
| ZOTAC         | H67ITX-C-E 02/03/05         | Desktop     | [27131cb048](https://linux-hardware.org/?probe=27131cb048) | Apr 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [bac14fb22e](https://linux-hardware.org/?probe=bac14fb22e) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [270e47ceb8](https://linux-hardware.org/?probe=270e47ceb8) | Apr 19, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [0a544df503](https://linux-hardware.org/?probe=0a544df503) | Apr 17, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [a70c93f2e7](https://linux-hardware.org/?probe=a70c93f2e7) | Apr 17, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [21c928caeb](https://linux-hardware.org/?probe=21c928caeb) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [1c99075a1d](https://linux-hardware.org/?probe=1c99075a1d) | Apr 16, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [2fd09b6ba5](https://linux-hardware.org/?probe=2fd09b6ba5) | Apr 16, 2023 |
| MAXDATA       | o.max_5xs                   | Notebook    | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cb21111c89](https://linux-hardware.org/?probe=cb21111c89) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3faf4e88e1](https://linux-hardware.org/?probe=3faf4e88e1) | Apr 16, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [962c5734bc](https://linux-hardware.org/?probe=962c5734bc) | Apr 15, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [c8bf9d49d4](https://linux-hardware.org/?probe=c8bf9d49d4) | Apr 15, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8a1ef40351](https://linux-hardware.org/?probe=8a1ef40351) | Apr 15, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [6b71471847](https://linux-hardware.org/?probe=6b71471847) | Apr 15, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [d00ebfbc62](https://linux-hardware.org/?probe=d00ebfbc62) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8b0e1ffa20](https://linux-hardware.org/?probe=8b0e1ffa20) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [3b2ac9206c](https://linux-hardware.org/?probe=3b2ac9206c) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [16ee5e0082](https://linux-hardware.org/?probe=16ee5e0082) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [1b21351033](https://linux-hardware.org/?probe=1b21351033) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [f6f55c801f](https://linux-hardware.org/?probe=f6f55c801f) | Apr 14, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [83ec457b1d](https://linux-hardware.org/?probe=83ec457b1d) | Apr 14, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [ccf77bf033](https://linux-hardware.org/?probe=ccf77bf033) | Apr 14, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [7f20e3160b](https://linux-hardware.org/?probe=7f20e3160b) | Apr 13, 2023 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [1b44c95410](https://linux-hardware.org/?probe=1b44c95410) | Apr 13, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [f46283dc4c](https://linux-hardware.org/?probe=f46283dc4c) | Apr 13, 2023 |
| MAXDATA       | o.max_5xs                   | Notebook    | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2ecd45a19e](https://linux-hardware.org/?probe=2ecd45a19e) | Apr 13, 2023 |
| Acer          | Aspire one                  | Notebook    | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f5241c853f](https://linux-hardware.org/?probe=f5241c853f) | Apr 12, 2023 |
| Dell          | Precision 7770              | Notebook    | [5091c10fa2](https://linux-hardware.org/?probe=5091c10fa2) | Apr 11, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [d829fac91c](https://linux-hardware.org/?probe=d829fac91c) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [bd05976130](https://linux-hardware.org/?probe=bd05976130) | Apr 10, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [001091b5fd](https://linux-hardware.org/?probe=001091b5fd) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [34f1d57aec](https://linux-hardware.org/?probe=34f1d57aec) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0beaf2366c](https://linux-hardware.org/?probe=0beaf2366c) | Apr 09, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [2cf04d07fb](https://linux-hardware.org/?probe=2cf04d07fb) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f85fdf6564](https://linux-hardware.org/?probe=f85fdf6564) | Apr 09, 2023 |
| Supermicro    | H12SSL-NT                   | Server      | [9384fef88d](https://linux-hardware.org/?probe=9384fef88d) | Apr 08, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [e378272577](https://linux-hardware.org/?probe=e378272577) | Apr 08, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [97e76297c9](https://linux-hardware.org/?probe=97e76297c9) | Apr 08, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [cb0b33006e](https://linux-hardware.org/?probe=cb0b33006e) | Apr 07, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a71051ab5a](https://linux-hardware.org/?probe=a71051ab5a) | Apr 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2fccbc61e2](https://linux-hardware.org/?probe=2fccbc61e2) | Apr 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c59398619e](https://linux-hardware.org/?probe=c59398619e) | Apr 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [59bdd9d328](https://linux-hardware.org/?probe=59bdd9d328) | Apr 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [79ec23e706](https://linux-hardware.org/?probe=79ec23e706) | Apr 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d19221e116](https://linux-hardware.org/?probe=d19221e116) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [58e2308d1e](https://linux-hardware.org/?probe=58e2308d1e) | Apr 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470p 20J7S25C0... | Notebook    | [c1f70c64ad](https://linux-hardware.org/?probe=c1f70c64ad) | Apr 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [3599b8e875](https://linux-hardware.org/?probe=3599b8e875) | Mar 31, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [9e60f40931](https://linux-hardware.org/?probe=9e60f40931) | Mar 30, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [8f1dcf05eb](https://linux-hardware.org/?probe=8f1dcf05eb) | Mar 26, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0a19e934c3](https://linux-hardware.org/?probe=0a19e934c3) | Mar 26, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [85fb1a6778](https://linux-hardware.org/?probe=85fb1a6778) | Mar 26, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [cc262bb41a](https://linux-hardware.org/?probe=cc262bb41a) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [f2b287b461](https://linux-hardware.org/?probe=f2b287b461) | Mar 25, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [276aa0b036](https://linux-hardware.org/?probe=276aa0b036) | Mar 25, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [72f90312db](https://linux-hardware.org/?probe=72f90312db) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [dac7782920](https://linux-hardware.org/?probe=dac7782920) | Mar 24, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [96fe7c184c](https://linux-hardware.org/?probe=96fe7c184c) | Mar 24, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [2c8daaa4f2](https://linux-hardware.org/?probe=2c8daaa4f2) | Mar 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [4bf7fa5f9c](https://linux-hardware.org/?probe=4bf7fa5f9c) | Mar 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [35b30305ec](https://linux-hardware.org/?probe=35b30305ec) | Mar 23, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [caf636a252](https://linux-hardware.org/?probe=caf636a252) | Mar 22, 2023 |
| Lenovo        | ThinkPad X200 7459L61       | Notebook    | [42742477e3](https://linux-hardware.org/?probe=42742477e3) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [644c9b9e55](https://linux-hardware.org/?probe=644c9b9e55) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [06bd07f367](https://linux-hardware.org/?probe=06bd07f367) | Mar 21, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7b4a68e88a](https://linux-hardware.org/?probe=7b4a68e88a) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f048ae8dec](https://linux-hardware.org/?probe=f048ae8dec) | Mar 19, 2023 |
| MSI           | 990FXA-GD80                 | Desktop     | [e79acda971](https://linux-hardware.org/?probe=e79acda971) | Mar 19, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [4f98540a7b](https://linux-hardware.org/?probe=4f98540a7b) | Mar 19, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [dc0a9ba834](https://linux-hardware.org/?probe=dc0a9ba834) | Mar 19, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [cb3b7c5bfb](https://linux-hardware.org/?probe=cb3b7c5bfb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [135aa0e418](https://linux-hardware.org/?probe=135aa0e418) | Mar 18, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [210b2e16e3](https://linux-hardware.org/?probe=210b2e16e3) | Mar 18, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [67c8f562e5](https://linux-hardware.org/?probe=67c8f562e5) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [d2af864fbb](https://linux-hardware.org/?probe=d2af864fbb) | Mar 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [7e11b106d7](https://linux-hardware.org/?probe=7e11b106d7) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [d0ab04cac0](https://linux-hardware.org/?probe=d0ab04cac0) | Mar 16, 2023 |
| Star Labs     | StarBook                    | Notebook    | [0b249699ba](https://linux-hardware.org/?probe=0b249699ba) | Mar 16, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [fab37d7522](https://linux-hardware.org/?probe=fab37d7522) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [4d5bb23ec0](https://linux-hardware.org/?probe=4d5bb23ec0) | Mar 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [8c2507428d](https://linux-hardware.org/?probe=8c2507428d) | Mar 15, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [58f8534073](https://linux-hardware.org/?probe=58f8534073) | Mar 14, 2023 |
| Foxconn       | TPS01                       | Desktop     | [60ae6d3891](https://linux-hardware.org/?probe=60ae6d3891) | Mar 14, 2023 |
| Fujitsu Si... | D1547 S26361-D1547          | Desktop     | [95a9c8655d](https://linux-hardware.org/?probe=95a9c8655d) | Mar 14, 2023 |
| Dell          | Precision 7770              | Notebook    | [b13d6bed73](https://linux-hardware.org/?probe=b13d6bed73) | Mar 14, 2023 |
| Dell          | Precision 7770              | Notebook    | [38f84c4cfc](https://linux-hardware.org/?probe=38f84c4cfc) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [06d54f03f9](https://linux-hardware.org/?probe=06d54f03f9) | Mar 13, 2023 |
| Unknown       | Unknown                     | Soc         | [211fbfe507](https://linux-hardware.org/?probe=211fbfe507) | Mar 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a0590e6829](https://linux-hardware.org/?probe=a0590e6829) | Mar 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [540bfa93eb](https://linux-hardware.org/?probe=540bfa93eb) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [3b52326a3e](https://linux-hardware.org/?probe=3b52326a3e) | Mar 12, 2023 |
| Samsung       | 950QDB                      | Convertible | [525ce83d74](https://linux-hardware.org/?probe=525ce83d74) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [e3c4587227](https://linux-hardware.org/?probe=e3c4587227) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [0932f02541](https://linux-hardware.org/?probe=0932f02541) | Mar 12, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| Dell          | Precision 7770              | Notebook    | [7d5207e1c1](https://linux-hardware.org/?probe=7d5207e1c1) | Mar 09, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [a0eb3774fc](https://linux-hardware.org/?probe=a0eb3774fc) | Mar 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Supermicro    | X10DRi-LN4+                 | Desktop     | [4e805ce5a1](https://linux-hardware.org/?probe=4e805ce5a1) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [87cbc99c85](https://linux-hardware.org/?probe=87cbc99c85) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [ad6e1bbda5](https://linux-hardware.org/?probe=ad6e1bbda5) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e455dce9f3](https://linux-hardware.org/?probe=e455dce9f3) | Mar 07, 2023 |
| ASRock        | H170 Pro4                   | Desktop     | [7d749add31](https://linux-hardware.org/?probe=7d749add31) | Mar 07, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [4d48b829ca](https://linux-hardware.org/?probe=4d48b829ca) | Mar 07, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [397eb062bf](https://linux-hardware.org/?probe=397eb062bf) | Mar 07, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [dee1b60a0d](https://linux-hardware.org/?probe=dee1b60a0d) | Mar 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [70eb1caef5](https://linux-hardware.org/?probe=70eb1caef5) | Mar 07, 2023 |
| Dell          | Precision 7770              | Notebook    | [dea25f9c87](https://linux-hardware.org/?probe=dea25f9c87) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6493617e39](https://linux-hardware.org/?probe=6493617e39) | Mar 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [ffd546b665](https://linux-hardware.org/?probe=ffd546b665) | Mar 07, 2023 |
| Supermicro    | X10DRi-LN4+                 | Desktop     | [d445859477](https://linux-hardware.org/?probe=d445859477) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [5f35f09385](https://linux-hardware.org/?probe=5f35f09385) | Mar 06, 2023 |
| Dell          | Precision 7770              | Notebook    | [aa1ff5150c](https://linux-hardware.org/?probe=aa1ff5150c) | Mar 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [42edcf638d](https://linux-hardware.org/?probe=42edcf638d) | Mar 06, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [f0cde07b9f](https://linux-hardware.org/?probe=f0cde07b9f) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ccca18039f](https://linux-hardware.org/?probe=ccca18039f) | Mar 05, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [24373477d9](https://linux-hardware.org/?probe=24373477d9) | Mar 05, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [541a6200bc](https://linux-hardware.org/?probe=541a6200bc) | Mar 05, 2023 |
| IBM           | ThinkPad T41 23737JU        | Notebook    | [5495bd2109](https://linux-hardware.org/?probe=5495bd2109) | Mar 03, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [6553b59bfe](https://linux-hardware.org/?probe=6553b59bfe) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9a42993edb](https://linux-hardware.org/?probe=9a42993edb) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [e8f0217102](https://linux-hardware.org/?probe=e8f0217102) | Mar 03, 2023 |
| Huanan        | X99-F8D V2.4                | Desktop     | [e260724901](https://linux-hardware.org/?probe=e260724901) | Mar 03, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [8f8eaa9d53](https://linux-hardware.org/?probe=8f8eaa9d53) | Mar 01, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7f93c1a4e3](https://linux-hardware.org/?probe=7f93c1a4e3) | Feb 28, 2023 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [0de52a6150](https://linux-hardware.org/?probe=0de52a6150) | Feb 28, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [5f8c1e2d90](https://linux-hardware.org/?probe=5f8c1e2d90) | Feb 28, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [373f4f8123](https://linux-hardware.org/?probe=373f4f8123) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [aa86292f52](https://linux-hardware.org/?probe=aa86292f52) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f8d42c3767](https://linux-hardware.org/?probe=f8d42c3767) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [54e5bda708](https://linux-hardware.org/?probe=54e5bda708) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [83af08dd1d](https://linux-hardware.org/?probe=83af08dd1d) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c5a45c78fc](https://linux-hardware.org/?probe=c5a45c78fc) | Feb 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [cf1d88a388](https://linux-hardware.org/?probe=cf1d88a388) | Feb 26, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [6ea10cb77a](https://linux-hardware.org/?probe=6ea10cb77a) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [7f2823a756](https://linux-hardware.org/?probe=7f2823a756) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [0b1c4036b1](https://linux-hardware.org/?probe=0b1c4036b1) | Feb 26, 2023 |
| Lenovo        | 1048 SDK0T08861 WIN 3305... | Desktop     | [e6b48cdec4](https://linux-hardware.org/?probe=e6b48cdec4) | Feb 26, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [2029821da8](https://linux-hardware.org/?probe=2029821da8) | Feb 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| ASRock        | X370 Professional Gaming    | Desktop     | [cff46cb07b](https://linux-hardware.org/?probe=cff46cb07b) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FBA... | Convertible | [cede8b490a](https://linux-hardware.org/?probe=cede8b490a) | Feb 22, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [f2049b8af1](https://linux-hardware.org/?probe=f2049b8af1) | Feb 21, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [ec5a8efdcd](https://linux-hardware.org/?probe=ec5a8efdcd) | Feb 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6a44442cfc](https://linux-hardware.org/?probe=6a44442cfc) | Feb 21, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [a8da25537c](https://linux-hardware.org/?probe=a8da25537c) | Feb 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [da640089bd](https://linux-hardware.org/?probe=da640089bd) | Feb 21, 2023 |
| Alienware     | 17                          | Notebook    | [848d5cd7e9](https://linux-hardware.org/?probe=848d5cd7e9) | Feb 20, 2023 |
| Dell          | Precision 7770              | Notebook    | [d8db6fecdd](https://linux-hardware.org/?probe=d8db6fecdd) | Feb 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cc8a99e630](https://linux-hardware.org/?probe=cc8a99e630) | Feb 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7b0fb49186](https://linux-hardware.org/?probe=7b0fb49186) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [6424058c59](https://linux-hardware.org/?probe=6424058c59) | Feb 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4fac3ddf27](https://linux-hardware.org/?probe=4fac3ddf27) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [e2facdc650](https://linux-hardware.org/?probe=e2facdc650) | Feb 19, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [48ca6dc3eb](https://linux-hardware.org/?probe=48ca6dc3eb) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [84e946f098](https://linux-hardware.org/?probe=84e946f098) | Feb 18, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [a526504d18](https://linux-hardware.org/?probe=a526504d18) | Feb 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [46289356fa](https://linux-hardware.org/?probe=46289356fa) | Feb 18, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [fa6a3fe6e3](https://linux-hardware.org/?probe=fa6a3fe6e3) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [7d36f8eee5](https://linux-hardware.org/?probe=7d36f8eee5) | Feb 16, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [39b9facc37](https://linux-hardware.org/?probe=39b9facc37) | Feb 16, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [2c0799202c](https://linux-hardware.org/?probe=2c0799202c) | Feb 15, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [991db4f096](https://linux-hardware.org/?probe=991db4f096) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e474459ee0](https://linux-hardware.org/?probe=e474459ee0) | Feb 13, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [94ca7f3e34](https://linux-hardware.org/?probe=94ca7f3e34) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [6a952f7024](https://linux-hardware.org/?probe=6a952f7024) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [e8ba753fae](https://linux-hardware.org/?probe=e8ba753fae) | Feb 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7eb2b7e26f](https://linux-hardware.org/?probe=7eb2b7e26f) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [36a0d5221f](https://linux-hardware.org/?probe=36a0d5221f) | Feb 13, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [aedfc67444](https://linux-hardware.org/?probe=aedfc67444) | Feb 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [e0fd4c1db9](https://linux-hardware.org/?probe=e0fd4c1db9) | Feb 11, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [95337ab460](https://linux-hardware.org/?probe=95337ab460) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [12c06a594d](https://linux-hardware.org/?probe=12c06a594d) | Feb 10, 2023 |
| Supermicro    | H11SSL-i                    | Server      | [ba881ed411](https://linux-hardware.org/?probe=ba881ed411) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [469eaa6fba](https://linux-hardware.org/?probe=469eaa6fba) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [1423d5ac1b](https://linux-hardware.org/?probe=1423d5ac1b) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [bb589c5e58](https://linux-hardware.org/?probe=bb589c5e58) | Feb 10, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [4998be684f](https://linux-hardware.org/?probe=4998be684f) | Feb 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2cfb05371e](https://linux-hardware.org/?probe=2cfb05371e) | Feb 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4468518165](https://linux-hardware.org/?probe=4468518165) | Feb 09, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [85b07c179c](https://linux-hardware.org/?probe=85b07c179c) | Feb 09, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [238c7a2c08](https://linux-hardware.org/?probe=238c7a2c08) | Feb 09, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [f09cd898c8](https://linux-hardware.org/?probe=f09cd898c8) | Feb 09, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [c71dba27f2](https://linux-hardware.org/?probe=c71dba27f2) | Feb 08, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [83b847229c](https://linux-hardware.org/?probe=83b847229c) | Feb 08, 2023 |
| Dell          | Precision 7770              | Notebook    | [69b0982ad7](https://linux-hardware.org/?probe=69b0982ad7) | Feb 08, 2023 |
| Dell          | Precision 7770              | Notebook    | [28ba6f72d0](https://linux-hardware.org/?probe=28ba6f72d0) | Feb 07, 2023 |
| Dell          | Precision 7770              | Notebook    | [d05aabf7a5](https://linux-hardware.org/?probe=d05aabf7a5) | Feb 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [42a3945648](https://linux-hardware.org/?probe=42a3945648) | Feb 06, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [bc0593280c](https://linux-hardware.org/?probe=bc0593280c) | Feb 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [2ac999e9b0](https://linux-hardware.org/?probe=2ac999e9b0) | Feb 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [5f77ae27c2](https://linux-hardware.org/?probe=5f77ae27c2) | Feb 04, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [78a631609d](https://linux-hardware.org/?probe=78a631609d) | Feb 04, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [e12e1d2598](https://linux-hardware.org/?probe=e12e1d2598) | Feb 04, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [be3ef90301](https://linux-hardware.org/?probe=be3ef90301) | Feb 04, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [37d0cc301b](https://linux-hardware.org/?probe=37d0cc301b) | Feb 03, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a8dcc6b4c1](https://linux-hardware.org/?probe=a8dcc6b4c1) | Feb 03, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [a08ee9b387](https://linux-hardware.org/?probe=a08ee9b387) | Feb 03, 2023 |
| Dell          | Precision 7770              | Notebook    | [20f6b87742](https://linux-hardware.org/?probe=20f6b87742) | Feb 03, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0cf18835cc](https://linux-hardware.org/?probe=0cf18835cc) | Feb 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| ASUSTek       | GL702VT                     | Notebook    | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| MSI           | GP60 2PE                    | Notebook    | [a1bb8934a0](https://linux-hardware.org/?probe=a1bb8934a0) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9fb41ee5bc](https://linux-hardware.org/?probe=9fb41ee5bc) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4bb9990abe](https://linux-hardware.org/?probe=4bb9990abe) | Feb 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [396877a008](https://linux-hardware.org/?probe=396877a008) | Jan 31, 2023 |
| Sony          | PCG-GRT230(UC)              | Notebook    | [0a7c76da78](https://linux-hardware.org/?probe=0a7c76da78) | Jan 30, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5a2c721748](https://linux-hardware.org/?probe=5a2c721748) | Jan 30, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [c93e84b79b](https://linux-hardware.org/?probe=c93e84b79b) | Jan 29, 2023 |
| Google        | Helios                      | Notebook    | [c8b5d0660b](https://linux-hardware.org/?probe=c8b5d0660b) | Jan 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [f71299a9c6](https://linux-hardware.org/?probe=f71299a9c6) | Jan 27, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [a30690db0c](https://linux-hardware.org/?probe=a30690db0c) | Jan 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9001ac4e36](https://linux-hardware.org/?probe=9001ac4e36) | Jan 27, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [90f37ac742](https://linux-hardware.org/?probe=90f37ac742) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [e524d7c4d9](https://linux-hardware.org/?probe=e524d7c4d9) | Jan 26, 2023 |
| Dell          | XPS 9320                    | Notebook    | [a1040b4a3f](https://linux-hardware.org/?probe=a1040b4a3f) | Jan 26, 2023 |
| Dell          | Latitude 5530               | Notebook    | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Lenovo        | 1030 SDK0Q40104 WIN 3305... | Desktop     | [6a876fb2b4](https://linux-hardware.org/?probe=6a876fb2b4) | Jan 23, 2023 |
| Lenovo        | 1030 SDK0Q40104 WIN 3305... | Desktop     | [287d005187](https://linux-hardware.org/?probe=287d005187) | Jan 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c2f89a9e58](https://linux-hardware.org/?probe=c2f89a9e58) | Jan 23, 2023 |
| Dell          | Precision 7770              | Notebook    | [47044d362f](https://linux-hardware.org/?probe=47044d362f) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2f02d895e2](https://linux-hardware.org/?probe=2f02d895e2) | Jan 22, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [92280be854](https://linux-hardware.org/?probe=92280be854) | Jan 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS27Y0... | Notebook    | [e1678320fc](https://linux-hardware.org/?probe=e1678320fc) | Jan 22, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [69bf20ee28](https://linux-hardware.org/?probe=69bf20ee28) | Jan 21, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [dfd88e113a](https://linux-hardware.org/?probe=dfd88e113a) | Jan 21, 2023 |
| Dell          | XPS 9320                    | Notebook    | [ebe686793d](https://linux-hardware.org/?probe=ebe686793d) | Jan 21, 2023 |
| Dell          | XPS 9320                    | Notebook    | [706152a268](https://linux-hardware.org/?probe=706152a268) | Jan 21, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [d37b338c87](https://linux-hardware.org/?probe=d37b338c87) | Jan 21, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [413cd3b7cf](https://linux-hardware.org/?probe=413cd3b7cf) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [69f4adcf81](https://linux-hardware.org/?probe=69f4adcf81) | Jan 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f935f0c7b](https://linux-hardware.org/?probe=1f935f0c7b) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [0e8d25f649](https://linux-hardware.org/?probe=0e8d25f649) | Jan 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4932579d3e](https://linux-hardware.org/?probe=4932579d3e) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a1b3ac9ccc](https://linux-hardware.org/?probe=a1b3ac9ccc) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [b11a63e25d](https://linux-hardware.org/?probe=b11a63e25d) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [753a61e1de](https://linux-hardware.org/?probe=753a61e1de) | Jan 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7aa00b2d9f](https://linux-hardware.org/?probe=7aa00b2d9f) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [b14d57e1a3](https://linux-hardware.org/?probe=b14d57e1a3) | Jan 19, 2023 |
| Dell          | Precision 7720              | Notebook    | [9a00916b91](https://linux-hardware.org/?probe=9a00916b91) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0770f064de](https://linux-hardware.org/?probe=0770f064de) | Jan 19, 2023 |
| Schenker      | XMG PRO (E22)               | Notebook    | [475e812e56](https://linux-hardware.org/?probe=475e812e56) | Jan 19, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [7427c997d7](https://linux-hardware.org/?probe=7427c997d7) | Jan 18, 2023 |
| Dell          | Latitude 5410               | Notebook    | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [b4e1da9857](https://linux-hardware.org/?probe=b4e1da9857) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [d78fd14781](https://linux-hardware.org/?probe=d78fd14781) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [0d5c9f7a33](https://linux-hardware.org/?probe=0d5c9f7a33) | Jan 16, 2023 |
| Dell          | Precision 7720              | Notebook    | [f8e1c53257](https://linux-hardware.org/?probe=f8e1c53257) | Jan 16, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [8e35281ea5](https://linux-hardware.org/?probe=8e35281ea5) | Jan 16, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5e6192ed2b](https://linux-hardware.org/?probe=5e6192ed2b) | Jan 16, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [94ba7a4ca6](https://linux-hardware.org/?probe=94ba7a4ca6) | Jan 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [25cf332260](https://linux-hardware.org/?probe=25cf332260) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3f12fad87c](https://linux-hardware.org/?probe=3f12fad87c) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ca74e79834](https://linux-hardware.org/?probe=ca74e79834) | Jan 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [eeeb041ca6](https://linux-hardware.org/?probe=eeeb041ca6) | Jan 13, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [306315e4d8](https://linux-hardware.org/?probe=306315e4d8) | Jan 12, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [4fe502c977](https://linux-hardware.org/?probe=4fe502c977) | Jan 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [aac6fb4537](https://linux-hardware.org/?probe=aac6fb4537) | Jan 09, 2023 |
| Google        | Sasuke                      | Notebook    | [aa3a09aaef](https://linux-hardware.org/?probe=aa3a09aaef) | Jan 07, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [b5dd8ee9f3](https://linux-hardware.org/?probe=b5dd8ee9f3) | Jan 07, 2023 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [7ea6f8ee94](https://linux-hardware.org/?probe=7ea6f8ee94) | Jan 06, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [0944e31ade](https://linux-hardware.org/?probe=0944e31ade) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [659196ed95](https://linux-hardware.org/?probe=659196ed95) | Jan 06, 2023 |
| HP            | 212A                        | Desktop     | [21acb67653](https://linux-hardware.org/?probe=21acb67653) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S04Q00    | Notebook    | [0dbae6cda4](https://linux-hardware.org/?probe=0dbae6cda4) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S04Q00    | Notebook    | [bca9343f96](https://linux-hardware.org/?probe=bca9343f96) | Jan 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [bb78c165c7](https://linux-hardware.org/?probe=bb78c165c7) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [40a6c7370b](https://linux-hardware.org/?probe=40a6c7370b) | Jan 05, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [c39cf71ff8](https://linux-hardware.org/?probe=c39cf71ff8) | Jan 05, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [3b32e784a3](https://linux-hardware.org/?probe=3b32e784a3) | Jan 03, 2023 |
| Dell          | Precision 7720              | Notebook    | [59813a7461](https://linux-hardware.org/?probe=59813a7461) | Jan 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [92052e9c47](https://linux-hardware.org/?probe=92052e9c47) | Jan 02, 2023 |
| Supermicro    | H12SSL-NT                   | Server      | [954e228bd5](https://linux-hardware.org/?probe=954e228bd5) | Dec 31, 2022 |
| Dell          | 0TWFTR A02                  | All in one  | [5f63c2fd15](https://linux-hardware.org/?probe=5f63c2fd15) | Dec 31, 2022 |
| Phoenix       | 945GM                       | Desktop     | [d391eaf6e2](https://linux-hardware.org/?probe=d391eaf6e2) | Dec 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a5030d74d4](https://linux-hardware.org/?probe=a5030d74d4) | Dec 31, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [9b6998f35c](https://linux-hardware.org/?probe=9b6998f35c) | Dec 31, 2022 |
| Lenovo        | ThinkPad W540 20BG0033RT    | Notebook    | [5cfa12cec1](https://linux-hardware.org/?probe=5cfa12cec1) | Dec 31, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [4b130212a2](https://linux-hardware.org/?probe=4b130212a2) | Dec 30, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [0c7ced8708](https://linux-hardware.org/?probe=0c7ced8708) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [bd53b75b7b](https://linux-hardware.org/?probe=bd53b75b7b) | Dec 30, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9a05e8c413](https://linux-hardware.org/?probe=9a05e8c413) | Dec 30, 2022 |
| Unknown       | Freecom Silverstore HNCN... | Desktop     | [723fbcd23f](https://linux-hardware.org/?probe=723fbcd23f) | Dec 29, 2022 |
| Dell          | Precision 7720              | Notebook    | [56db0ab146](https://linux-hardware.org/?probe=56db0ab146) | Dec 28, 2022 |
| Dell          | Precision 7720              | Notebook    | [e94a7bb989](https://linux-hardware.org/?probe=e94a7bb989) | Dec 28, 2022 |
| Dell          | G3 3500                     | Notebook    | [78e803b44e](https://linux-hardware.org/?probe=78e803b44e) | Dec 28, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [03cca95360](https://linux-hardware.org/?probe=03cca95360) | Dec 27, 2022 |
| System76      | Darter Pro                  | Notebook    | [c5aebaaece](https://linux-hardware.org/?probe=c5aebaaece) | Dec 27, 2022 |
| Dell          | G5 5505                     | Notebook    | [87f62bee87](https://linux-hardware.org/?probe=87f62bee87) | Dec 26, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [9c75de7af7](https://linux-hardware.org/?probe=9c75de7af7) | Dec 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5d2498f405](https://linux-hardware.org/?probe=5d2498f405) | Dec 26, 2022 |
| Star Labs     | StarLite                    | Notebook    | [0d27e6f7ee](https://linux-hardware.org/?probe=0d27e6f7ee) | Dec 25, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [d759e5fe02](https://linux-hardware.org/?probe=d759e5fe02) | Dec 25, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [77390ced3c](https://linux-hardware.org/?probe=77390ced3c) | Dec 24, 2022 |
| Supermicro    | X10DSC+                     | Desktop     | [cf559d5e84](https://linux-hardware.org/?probe=cf559d5e84) | Dec 24, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [f694fa24c8](https://linux-hardware.org/?probe=f694fa24c8) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [0c1d9b9b28](https://linux-hardware.org/?probe=0c1d9b9b28) | Dec 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [25cbb2c39a](https://linux-hardware.org/?probe=25cbb2c39a) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [000660b461](https://linux-hardware.org/?probe=000660b461) | Dec 23, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0277928378](https://linux-hardware.org/?probe=0277928378) | Dec 23, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ec6b0e70a2](https://linux-hardware.org/?probe=ec6b0e70a2) | Dec 21, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [5fd1a2d6e1](https://linux-hardware.org/?probe=5fd1a2d6e1) | Dec 21, 2022 |
| HP            | 0980h                       | Desktop     | [d54665c87c](https://linux-hardware.org/?probe=d54665c87c) | Dec 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [638667a90f](https://linux-hardware.org/?probe=638667a90f) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b9aed745da](https://linux-hardware.org/?probe=b9aed745da) | Dec 20, 2022 |
| HP            | 0980h                       | Desktop     | [3faf0c7996](https://linux-hardware.org/?probe=3faf0c7996) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [c7cea6dd19](https://linux-hardware.org/?probe=c7cea6dd19) | Dec 20, 2022 |
| HP            | 83E9                        | Desktop     | [02e854bd7c](https://linux-hardware.org/?probe=02e854bd7c) | Dec 20, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [3d33008fb2](https://linux-hardware.org/?probe=3d33008fb2) | Dec 19, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [2318fda45f](https://linux-hardware.org/?probe=2318fda45f) | Dec 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [70a0e2a296](https://linux-hardware.org/?probe=70a0e2a296) | Dec 19, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [e0f5a5db4c](https://linux-hardware.org/?probe=e0f5a5db4c) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470p 20J7S25C0... | Notebook    | [3dc497faf1](https://linux-hardware.org/?probe=3dc497faf1) | Dec 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [f15a27fd5e](https://linux-hardware.org/?probe=f15a27fd5e) | Dec 17, 2022 |
| HP            | 83E9                        | Desktop     | [cdf4ff19a6](https://linux-hardware.org/?probe=cdf4ff19a6) | Dec 17, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d8774d83a7](https://linux-hardware.org/?probe=d8774d83a7) | Dec 16, 2022 |
| HP            | 83E9                        | Desktop     | [53f1974d93](https://linux-hardware.org/?probe=53f1974d93) | Dec 16, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1860105d14](https://linux-hardware.org/?probe=1860105d14) | Dec 16, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [3807037a5c](https://linux-hardware.org/?probe=3807037a5c) | Dec 15, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [34676168fa](https://linux-hardware.org/?probe=34676168fa) | Dec 14, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [0f9b4ae170](https://linux-hardware.org/?probe=0f9b4ae170) | Dec 14, 2022 |
| HP            | 212A                        | Desktop     | [c21bb6d20d](https://linux-hardware.org/?probe=c21bb6d20d) | Dec 14, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [8370a57760](https://linux-hardware.org/?probe=8370a57760) | Dec 12, 2022 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [b7374c7211](https://linux-hardware.org/?probe=b7374c7211) | Dec 12, 2022 |
| Supermicro    | H12SSL-NT                   | Server      | [82bfec7c72](https://linux-hardware.org/?probe=82bfec7c72) | Dec 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [177dded9e0](https://linux-hardware.org/?probe=177dded9e0) | Dec 12, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7541ce9ac6](https://linux-hardware.org/?probe=7541ce9ac6) | Dec 11, 2022 |
| MSI           | K9N2 Diamond                | Desktop     | [0a42d5e656](https://linux-hardware.org/?probe=0a42d5e656) | Dec 11, 2022 |
| Star Labs     | StarLite                    | Notebook    | [0d83c191fa](https://linux-hardware.org/?probe=0d83c191fa) | Dec 10, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6dd02812db](https://linux-hardware.org/?probe=6dd02812db) | Dec 10, 2022 |
| HP            | ProBook 6570b               | Notebook    | [073546a981](https://linux-hardware.org/?probe=073546a981) | Dec 10, 2022 |
| Supermicro    | H12SSL-NT                   | Server      | [afb0183c71](https://linux-hardware.org/?probe=afb0183c71) | Dec 10, 2022 |
| Star Labs     | StarLite                    | Notebook    | [4446ba1d6a](https://linux-hardware.org/?probe=4446ba1d6a) | Dec 10, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [bede7701b9](https://linux-hardware.org/?probe=bede7701b9) | Dec 08, 2022 |
| Google        | Eve                         | Notebook    | [d78558c833](https://linux-hardware.org/?probe=d78558c833) | Dec 08, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [26f56cc499](https://linux-hardware.org/?probe=26f56cc499) | Dec 08, 2022 |
| Google        | Eve                         | Notebook    | [92d1d03fed](https://linux-hardware.org/?probe=92d1d03fed) | Dec 08, 2022 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [15f27b7ac6](https://linux-hardware.org/?probe=15f27b7ac6) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [15d7102174](https://linux-hardware.org/?probe=15d7102174) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [52525a1058](https://linux-hardware.org/?probe=52525a1058) | Dec 08, 2022 |
| ASRock        | AB350M                      | Desktop     | [95a14fd558](https://linux-hardware.org/?probe=95a14fd558) | Dec 07, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [13ac8bc162](https://linux-hardware.org/?probe=13ac8bc162) | Dec 06, 2022 |
| Samsung       | 950QED                      | Convertible | [396d57bb34](https://linux-hardware.org/?probe=396d57bb34) | Dec 06, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [c3510d4787](https://linux-hardware.org/?probe=c3510d4787) | Dec 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ccf3e1f074](https://linux-hardware.org/?probe=ccf3e1f074) | Dec 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60b1be0a32](https://linux-hardware.org/?probe=60b1be0a32) | Dec 05, 2022 |
| Gigabyte      | B650M DS3H                  | Desktop     | [73b49404f9](https://linux-hardware.org/?probe=73b49404f9) | Dec 05, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [6d92129c25](https://linux-hardware.org/?probe=6d92129c25) | Dec 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9fec7bdfdc](https://linux-hardware.org/?probe=9fec7bdfdc) | Dec 04, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [22fc01fd20](https://linux-hardware.org/?probe=22fc01fd20) | Dec 04, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [84a50cd483](https://linux-hardware.org/?probe=84a50cd483) | Dec 03, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [debbc3f9ff](https://linux-hardware.org/?probe=debbc3f9ff) | Dec 03, 2022 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [2adb8631b0](https://linux-hardware.org/?probe=2adb8631b0) | Dec 03, 2022 |
| HP            | G62                         | Notebook    | [494d9e65e4](https://linux-hardware.org/?probe=494d9e65e4) | Dec 03, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [29d43d4af8](https://linux-hardware.org/?probe=29d43d4af8) | Dec 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ee24c782fa](https://linux-hardware.org/?probe=ee24c782fa) | Dec 02, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [f9379c4ffb](https://linux-hardware.org/?probe=f9379c4ffb) | Dec 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [dceef2a9d5](https://linux-hardware.org/?probe=dceef2a9d5) | Dec 01, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [3d92c6cbc8](https://linux-hardware.org/?probe=3d92c6cbc8) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [d313455fa8](https://linux-hardware.org/?probe=d313455fa8) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [31b9efe771](https://linux-hardware.org/?probe=31b9efe771) | Dec 01, 2022 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [d77cb5ebb0](https://linux-hardware.org/?probe=d77cb5ebb0) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e3f55c7b9d](https://linux-hardware.org/?probe=e3f55c7b9d) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [54407c7caa](https://linux-hardware.org/?probe=54407c7caa) | Nov 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [6bf87b9885](https://linux-hardware.org/?probe=6bf87b9885) | Nov 28, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [af7d162434](https://linux-hardware.org/?probe=af7d162434) | Nov 28, 2022 |
| HP            | 86EE                        | All in one  | [8533afb703](https://linux-hardware.org/?probe=8533afb703) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [02c62a5eb8](https://linux-hardware.org/?probe=02c62a5eb8) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [6206268283](https://linux-hardware.org/?probe=6206268283) | Nov 27, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [f2fe1d140e](https://linux-hardware.org/?probe=f2fe1d140e) | Nov 26, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [ba4ed6c5f4](https://linux-hardware.org/?probe=ba4ed6c5f4) | Nov 26, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1bd15590c9](https://linux-hardware.org/?probe=1bd15590c9) | Nov 25, 2022 |
| Razer         | Blade Pro                   | Notebook    | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| MSI           | TRX40 PRO WIFI              | Desktop     | [3617f324a2](https://linux-hardware.org/?probe=3617f324a2) | Nov 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [fa4e2d1d61](https://linux-hardware.org/?probe=fa4e2d1d61) | Nov 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b0d3226df4](https://linux-hardware.org/?probe=b0d3226df4) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [c150f785ea](https://linux-hardware.org/?probe=c150f785ea) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4f36ecd91b](https://linux-hardware.org/?probe=4f36ecd91b) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f58f70b732](https://linux-hardware.org/?probe=f58f70b732) | Nov 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [16fc755db2](https://linux-hardware.org/?probe=16fc755db2) | Nov 19, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8ffb460b9e](https://linux-hardware.org/?probe=8ffb460b9e) | Nov 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ea05374336](https://linux-hardware.org/?probe=ea05374336) | Nov 19, 2022 |
| Unknown       | QNAP TS-221                 | Desktop     | [b9ff535a3f](https://linux-hardware.org/?probe=b9ff535a3f) | Nov 18, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [74a3983b1e](https://linux-hardware.org/?probe=74a3983b1e) | Nov 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [45fbc31f55](https://linux-hardware.org/?probe=45fbc31f55) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [a5eb8c6aaa](https://linux-hardware.org/?probe=a5eb8c6aaa) | Nov 17, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [8a94d169c5](https://linux-hardware.org/?probe=8a94d169c5) | Nov 17, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [fbe52d681e](https://linux-hardware.org/?probe=fbe52d681e) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [5fd36e3d66](https://linux-hardware.org/?probe=5fd36e3d66) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [62b2a72fa9](https://linux-hardware.org/?probe=62b2a72fa9) | Nov 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [f3222cf843](https://linux-hardware.org/?probe=f3222cf843) | Nov 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [9217d900c4](https://linux-hardware.org/?probe=9217d900c4) | Nov 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [b870eb1d72](https://linux-hardware.org/?probe=b870eb1d72) | Nov 15, 2022 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [de10599614](https://linux-hardware.org/?probe=de10599614) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [dea1636b05](https://linux-hardware.org/?probe=dea1636b05) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [9ed613b632](https://linux-hardware.org/?probe=9ed613b632) | Nov 15, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [642a889fcc](https://linux-hardware.org/?probe=642a889fcc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [1798f04a0b](https://linux-hardware.org/?probe=1798f04a0b) | Nov 14, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [346303c711](https://linux-hardware.org/?probe=346303c711) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7f21362848](https://linux-hardware.org/?probe=7f21362848) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | Notebook    | [cbd0b88f5f](https://linux-hardware.org/?probe=cbd0b88f5f) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | Notebook    | [0e9a1a51a5](https://linux-hardware.org/?probe=0e9a1a51a5) | Nov 14, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [2e29461f3b](https://linux-hardware.org/?probe=2e29461f3b) | Nov 13, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [cd18d68895](https://linux-hardware.org/?probe=cd18d68895) | Nov 13, 2022 |
| Supermicro    | X10DRT-P                    | Server      | [a56f11112b](https://linux-hardware.org/?probe=a56f11112b) | Nov 13, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [9d91de9f87](https://linux-hardware.org/?probe=9d91de9f87) | Nov 12, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [da754cf27a](https://linux-hardware.org/?probe=da754cf27a) | Nov 11, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [9db585ddc5](https://linux-hardware.org/?probe=9db585ddc5) | Nov 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [332cc61ddc](https://linux-hardware.org/?probe=332cc61ddc) | Nov 11, 2022 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [7a41c26bea](https://linux-hardware.org/?probe=7a41c26bea) | Nov 09, 2022 |
| Dell          | Precision 5540              | Notebook    | [2d459a448d](https://linux-hardware.org/?probe=2d459a448d) | Nov 09, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [9f4cb2a547](https://linux-hardware.org/?probe=9f4cb2a547) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [8939445388](https://linux-hardware.org/?probe=8939445388) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [420aaf8ede](https://linux-hardware.org/?probe=420aaf8ede) | Nov 09, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a8f533624d](https://linux-hardware.org/?probe=a8f533624d) | Nov 08, 2022 |
| Dell          | G3 3500                     | Notebook    | [d3ae8a9d72](https://linux-hardware.org/?probe=d3ae8a9d72) | Nov 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [159ca02eca](https://linux-hardware.org/?probe=159ca02eca) | Nov 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [972094820e](https://linux-hardware.org/?probe=972094820e) | Nov 07, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [16154018bb](https://linux-hardware.org/?probe=16154018bb) | Nov 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [d238949b9f](https://linux-hardware.org/?probe=d238949b9f) | Nov 06, 2022 |
| Unknown       | X79-P3                      | Desktop     | [f069ed7bd9](https://linux-hardware.org/?probe=f069ed7bd9) | Nov 04, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7b65a89d4f](https://linux-hardware.org/?probe=7b65a89d4f) | Nov 04, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [9a7d0e6d37](https://linux-hardware.org/?probe=9a7d0e6d37) | Nov 03, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [81a04d40a3](https://linux-hardware.org/?probe=81a04d40a3) | Nov 03, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [dda5d2dd10](https://linux-hardware.org/?probe=dda5d2dd10) | Nov 03, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [953e399168](https://linux-hardware.org/?probe=953e399168) | Nov 03, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [c0f68304d1](https://linux-hardware.org/?probe=c0f68304d1) | Nov 03, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [8ca3bfde82](https://linux-hardware.org/?probe=8ca3bfde82) | Nov 02, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | G3 3500                     | Notebook    | [c595a16f59](https://linux-hardware.org/?probe=c595a16f59) | Nov 02, 2022 |
| ASRock        | N68C-GS UCC                 | Desktop     | [9430ecf81c](https://linux-hardware.org/?probe=9430ecf81c) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [48c0ef6251](https://linux-hardware.org/?probe=48c0ef6251) | Nov 02, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [5f81698e9a](https://linux-hardware.org/?probe=5f81698e9a) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [1cc623c804](https://linux-hardware.org/?probe=1cc623c804) | Nov 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [310895b721](https://linux-hardware.org/?probe=310895b721) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [1a88842782](https://linux-hardware.org/?probe=1a88842782) | Nov 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [966eb5bb18](https://linux-hardware.org/?probe=966eb5bb18) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [860f45c4c1](https://linux-hardware.org/?probe=860f45c4c1) | Oct 31, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c085788e44](https://linux-hardware.org/?probe=c085788e44) | Oct 31, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [2e39c3ce92](https://linux-hardware.org/?probe=2e39c3ce92) | Oct 30, 2022 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [33df9c20bf](https://linux-hardware.org/?probe=33df9c20bf) | Oct 30, 2022 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [c63ee0d1b7](https://linux-hardware.org/?probe=c63ee0d1b7) | Oct 30, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [057163f0e4](https://linux-hardware.org/?probe=057163f0e4) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [42fcb880db](https://linux-hardware.org/?probe=42fcb880db) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [242fbb2c79](https://linux-hardware.org/?probe=242fbb2c79) | Oct 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [98fe919d0e](https://linux-hardware.org/?probe=98fe919d0e) | Oct 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9a6e9239e1](https://linux-hardware.org/?probe=9a6e9239e1) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [7800fc7b5b](https://linux-hardware.org/?probe=7800fc7b5b) | Oct 29, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [836d9e4de1](https://linux-hardware.org/?probe=836d9e4de1) | Oct 29, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b7b7481628](https://linux-hardware.org/?probe=b7b7481628) | Oct 29, 2022 |
| Acer          | AOD257                      | Notebook    | [d3efba72cc](https://linux-hardware.org/?probe=d3efba72cc) | Oct 28, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [ac6587adbb](https://linux-hardware.org/?probe=ac6587adbb) | Oct 27, 2022 |
| Acer          | AOD257                      | Notebook    | [c399f9db2b](https://linux-hardware.org/?probe=c399f9db2b) | Oct 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a44f774778](https://linux-hardware.org/?probe=a44f774778) | Oct 27, 2022 |
| Dell          | Precision 5570              | Notebook    | [d74abc314b](https://linux-hardware.org/?probe=d74abc314b) | Oct 25, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c1ce4e70e0](https://linux-hardware.org/?probe=c1ce4e70e0) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [64e6199c96](https://linux-hardware.org/?probe=64e6199c96) | Oct 25, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [35cf015c33](https://linux-hardware.org/?probe=35cf015c33) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [cc2fc1e863](https://linux-hardware.org/?probe=cc2fc1e863) | Oct 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [9115752bd4](https://linux-hardware.org/?probe=9115752bd4) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [aaad9f52d4](https://linux-hardware.org/?probe=aaad9f52d4) | Oct 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ce77ed764b](https://linux-hardware.org/?probe=ce77ed764b) | Oct 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [d18380bf4c](https://linux-hardware.org/?probe=d18380bf4c) | Oct 24, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [16f90b14dc](https://linux-hardware.org/?probe=16f90b14dc) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b89b177dd7](https://linux-hardware.org/?probe=b89b177dd7) | Oct 22, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [80032ce2ea](https://linux-hardware.org/?probe=80032ce2ea) | Oct 22, 2022 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [7bc7482286](https://linux-hardware.org/?probe=7bc7482286) | Oct 21, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f3890a4db1](https://linux-hardware.org/?probe=f3890a4db1) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | Notebook    | [77de0f71bd](https://linux-hardware.org/?probe=77de0f71bd) | Oct 21, 2022 |
| Gigabyte      | G5 KD                       | Notebook    | [c0f91f7282](https://linux-hardware.org/?probe=c0f91f7282) | Oct 20, 2022 |
| Gigabyte      | G5 KD                       | Notebook    | [35db9f3cd8](https://linux-hardware.org/?probe=35db9f3cd8) | Oct 19, 2022 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [d066cccd5a](https://linux-hardware.org/?probe=d066cccd5a) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [0f13ae1769](https://linux-hardware.org/?probe=0f13ae1769) | Oct 19, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | Notebook    | [e480e5d6ae](https://linux-hardware.org/?probe=e480e5d6ae) | Oct 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [4644a299f3](https://linux-hardware.org/?probe=4644a299f3) | Oct 18, 2022 |
| Dell          | Precision 7760              | Notebook    | [44b60a4fcf](https://linux-hardware.org/?probe=44b60a4fcf) | Oct 18, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [2b0983acd6](https://linux-hardware.org/?probe=2b0983acd6) | Oct 18, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [71ab3d919c](https://linux-hardware.org/?probe=71ab3d919c) | Oct 18, 2022 |
| Sony          | PCG-GRT230(UC)              | Notebook    | [b33a31225b](https://linux-hardware.org/?probe=b33a31225b) | Oct 18, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [caf126d0af](https://linux-hardware.org/?probe=caf126d0af) | Oct 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [41d3e4e97d](https://linux-hardware.org/?probe=41d3e4e97d) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [6243f8cdb8](https://linux-hardware.org/?probe=6243f8cdb8) | Oct 17, 2022 |
| Dell          | G3 3500                     | Notebook    | [64698d52bb](https://linux-hardware.org/?probe=64698d52bb) | Oct 17, 2022 |
| Dell          | G3 3500                     | Notebook    | [902fc2d51b](https://linux-hardware.org/?probe=902fc2d51b) | Oct 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e8377da07e](https://linux-hardware.org/?probe=e8377da07e) | Oct 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [f60fd55235](https://linux-hardware.org/?probe=f60fd55235) | Oct 16, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [8bfcad8486](https://linux-hardware.org/?probe=8bfcad8486) | Oct 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d2b5d08432](https://linux-hardware.org/?probe=d2b5d08432) | Oct 15, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [843e47e886](https://linux-hardware.org/?probe=843e47e886) | Oct 14, 2022 |
| Dell          | G3 3500                     | Notebook    | [f7cc47bb67](https://linux-hardware.org/?probe=f7cc47bb67) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | Notebook    | [d71c1d033a](https://linux-hardware.org/?probe=d71c1d033a) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | Notebook    | [07783bd6a7](https://linux-hardware.org/?probe=07783bd6a7) | Oct 13, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [f57f16d11b](https://linux-hardware.org/?probe=f57f16d11b) | Oct 13, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [55e6578ade](https://linux-hardware.org/?probe=55e6578ade) | Oct 13, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [63731688d0](https://linux-hardware.org/?probe=63731688d0) | Oct 13, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [0dc42d7e5e](https://linux-hardware.org/?probe=0dc42d7e5e) | Oct 12, 2022 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| HP            | 2B26 A01                    | All in one  | [dec1b9e40f](https://linux-hardware.org/?probe=dec1b9e40f) | Oct 12, 2022 |
| HP            | 2B26 A01                    | All in one  | [3a0980d3d4](https://linux-hardware.org/?probe=3a0980d3d4) | Oct 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [c88027a227](https://linux-hardware.org/?probe=c88027a227) | Oct 11, 2022 |
| IBM           | ThinkPad T42 2373K1U        | Notebook    | [934a3226e9](https://linux-hardware.org/?probe=934a3226e9) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [11fb952122](https://linux-hardware.org/?probe=11fb952122) | Oct 10, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [42b7bc6ee4](https://linux-hardware.org/?probe=42b7bc6ee4) | Oct 10, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [b04149c5ea](https://linux-hardware.org/?probe=b04149c5ea) | Oct 10, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [d7bcf0afa3](https://linux-hardware.org/?probe=d7bcf0afa3) | Oct 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [99d95e9424](https://linux-hardware.org/?probe=99d95e9424) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [cbac2de735](https://linux-hardware.org/?probe=cbac2de735) | Oct 08, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [bacb30816f](https://linux-hardware.org/?probe=bacb30816f) | Oct 07, 2022 |
| ASUSTek       | ProArt Studiobook H7600Z... | Notebook    | [5db7aac5d3](https://linux-hardware.org/?probe=5db7aac5d3) | Oct 07, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [d81190b4e7](https://linux-hardware.org/?probe=d81190b4e7) | Oct 06, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [237fe18fcd](https://linux-hardware.org/?probe=237fe18fcd) | Oct 05, 2022 |
| Alienware     | x14                         | Notebook    | [ad37874de1](https://linux-hardware.org/?probe=ad37874de1) | Oct 05, 2022 |
| Quanta        | S210-X12MS 31S2MMB0040      | Server      | [73fb38c162](https://linux-hardware.org/?probe=73fb38c162) | Oct 05, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [ae4533cfd6](https://linux-hardware.org/?probe=ae4533cfd6) | Oct 03, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6437ed8b0e](https://linux-hardware.org/?probe=6437ed8b0e) | Oct 03, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [ae88619ae9](https://linux-hardware.org/?probe=ae88619ae9) | Oct 03, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [0eb2e22fc1](https://linux-hardware.org/?probe=0eb2e22fc1) | Oct 03, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [60bab6fe12](https://linux-hardware.org/?probe=60bab6fe12) | Oct 02, 2022 |
| Sony          | PCG-GRT230(UC)              | Notebook    | [cab24d4c04](https://linux-hardware.org/?probe=cab24d4c04) | Oct 01, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [1cfda531dd](https://linux-hardware.org/?probe=1cfda531dd) | Oct 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6d9c960574](https://linux-hardware.org/?probe=6d9c960574) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [4479784a2e](https://linux-hardware.org/?probe=4479784a2e) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [d0808e8abe](https://linux-hardware.org/?probe=d0808e8abe) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b3b8d3e04f](https://linux-hardware.org/?probe=b3b8d3e04f) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9795d4f9aa](https://linux-hardware.org/?probe=9795d4f9aa) | Sep 26, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6d3f575c3d](https://linux-hardware.org/?probe=6d3f575c3d) | Sep 26, 2022 |
| Sony          | PCG-GRT230(UC)              | Notebook    | [af843c265c](https://linux-hardware.org/?probe=af843c265c) | Sep 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c447921f07](https://linux-hardware.org/?probe=c447921f07) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | Notebook    | [b32a413aa9](https://linux-hardware.org/?probe=b32a413aa9) | Sep 25, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6c8a53f608](https://linux-hardware.org/?probe=6c8a53f608) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | Notebook    | [6ea4c40a80](https://linux-hardware.org/?probe=6ea4c40a80) | Sep 25, 2022 |
| ASRock        | J3160M                      | Desktop     | [c9cc54f48e](https://linux-hardware.org/?probe=c9cc54f48e) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [cdbc7c7949](https://linux-hardware.org/?probe=cdbc7c7949) | Sep 25, 2022 |
| Supermicro    | H11SSL-i                    | Server      | [dd3ce003e4](https://linux-hardware.org/?probe=dd3ce003e4) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [907383d255](https://linux-hardware.org/?probe=907383d255) | Sep 25, 2022 |
| Matsushita... | CF-29LTQGZBM                | Notebook    | [29f52f862c](https://linux-hardware.org/?probe=29f52f862c) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| Lenovo        | ThinkPad L580 20LWCTO1WW    | Notebook    | [a80367f777](https://linux-hardware.org/?probe=a80367f777) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [d22f082243](https://linux-hardware.org/?probe=d22f082243) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [e4f1a8245a](https://linux-hardware.org/?probe=e4f1a8245a) | Sep 21, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [a6e61a9993](https://linux-hardware.org/?probe=a6e61a9993) | Sep 19, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [eb1c0556c3](https://linux-hardware.org/?probe=eb1c0556c3) | Sep 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5a9ab0de04](https://linux-hardware.org/?probe=5a9ab0de04) | Sep 18, 2022 |
| System76      | Gazelle Professional        | Notebook    | [95f19a0c4c](https://linux-hardware.org/?probe=95f19a0c4c) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d4d8cc3f34](https://linux-hardware.org/?probe=d4d8cc3f34) | Sep 16, 2022 |
| Dell          | G7 7588                     | Notebook    | [583c4a4c91](https://linux-hardware.org/?probe=583c4a4c91) | Sep 16, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [475ed7f917](https://linux-hardware.org/?probe=475ed7f917) | Sep 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7ad1180946](https://linux-hardware.org/?probe=7ad1180946) | Sep 14, 2022 |
| Timi          | TM1604                      | Notebook    | [80f52c9545](https://linux-hardware.org/?probe=80f52c9545) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7bc7cbca76](https://linux-hardware.org/?probe=7bc7cbca76) | Sep 12, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [225bd59ba7](https://linux-hardware.org/?probe=225bd59ba7) | Sep 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ed5273b278](https://linux-hardware.org/?probe=ed5273b278) | Sep 11, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [3cb7aa6549](https://linux-hardware.org/?probe=3cb7aa6549) | Sep 11, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2e0d41f272](https://linux-hardware.org/?probe=2e0d41f272) | Sep 10, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [06ee689632](https://linux-hardware.org/?probe=06ee689632) | Sep 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5cfe072b9c](https://linux-hardware.org/?probe=5cfe072b9c) | Sep 10, 2022 |
| ASRock        | Z390 Phantom Gaming 4S      | Desktop     | [146e7ebf49](https://linux-hardware.org/?probe=146e7ebf49) | Sep 08, 2022 |
| Gigabyte      | B660 GAMING X AX DDR4       | Desktop     | [3d12a72937](https://linux-hardware.org/?probe=3d12a72937) | Sep 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [cc1fde17e8](https://linux-hardware.org/?probe=cc1fde17e8) | Sep 06, 2022 |
| Dell          | Latitude D410               | Notebook    | [6782e0a28f](https://linux-hardware.org/?probe=6782e0a28f) | Sep 05, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [12fbd247f5](https://linux-hardware.org/?probe=12fbd247f5) | Sep 05, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [1d90e3b685](https://linux-hardware.org/?probe=1d90e3b685) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d02a951b89](https://linux-hardware.org/?probe=d02a951b89) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Toshiba       | Satellite C850D-118         | Notebook    | [1950f0aeac](https://linux-hardware.org/?probe=1950f0aeac) | Aug 31, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| Toshiba       | Satellite C850D-118         | Notebook    | [07000e4194](https://linux-hardware.org/?probe=07000e4194) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | Notebook    | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [5a51c31ac9](https://linux-hardware.org/?probe=5a51c31ac9) | Aug 29, 2022 |
| Eluktronic... | MAX-17                      | Notebook    | [627ecbeb36](https://linux-hardware.org/?probe=627ecbeb36) | Aug 29, 2022 |
| Dell          | Precision 3570              | Notebook    | [7f7a44c923](https://linux-hardware.org/?probe=7f7a44c923) | Aug 29, 2022 |
| Timi          | A35                         | Notebook    | [df50ea1876](https://linux-hardware.org/?probe=df50ea1876) | Aug 29, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [7e810b23be](https://linux-hardware.org/?probe=7e810b23be) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [cf7da7df12](https://linux-hardware.org/?probe=cf7da7df12) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [76db86107b](https://linux-hardware.org/?probe=76db86107b) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Lenovo        | ThinkPad Yoga 460 20EMCT... | Convertible | [73c79e8944](https://linux-hardware.org/?probe=73c79e8944) | Aug 25, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [294fe7d6c8](https://linux-hardware.org/?probe=294fe7d6c8) | Aug 24, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [2952e542e1](https://linux-hardware.org/?probe=2952e542e1) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0df091061c](https://linux-hardware.org/?probe=0df091061c) | Aug 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c80683e2a](https://linux-hardware.org/?probe=0c80683e2a) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [8445aa0041](https://linux-hardware.org/?probe=8445aa0041) | Aug 20, 2022 |
| Timi          | A35                         | Notebook    | [cf89c68d08](https://linux-hardware.org/?probe=cf89c68d08) | Aug 19, 2022 |
| IBM           | 2722BDG                     | Notebook    | [e0fe2162a3](https://linux-hardware.org/?probe=e0fe2162a3) | Aug 18, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [80760b8e4b](https://linux-hardware.org/?probe=80760b8e4b) | Aug 16, 2022 |
| Dell          | G3 3500                     | Notebook    | [6a860d7c0f](https://linux-hardware.org/?probe=6a860d7c0f) | Aug 15, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| Purism        | Librem 15 v4                | Notebook    | [4448709e50](https://linux-hardware.org/?probe=4448709e50) | Aug 13, 2022 |
| Purism        | Librem 15 v4                | Notebook    | [9e76f9e7ff](https://linux-hardware.org/?probe=9e76f9e7ff) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ee6f495403](https://linux-hardware.org/?probe=ee6f495403) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [289850f128](https://linux-hardware.org/?probe=289850f128) | Aug 13, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8d95c82a1d](https://linux-hardware.org/?probe=8d95c82a1d) | Aug 12, 2022 |
| Timi          | A35                         | Notebook    | [944f3f0942](https://linux-hardware.org/?probe=944f3f0942) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [7d7ceef044](https://linux-hardware.org/?probe=7d7ceef044) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Notebook      | N141CU                      | Notebook    | [4d96f7358c](https://linux-hardware.org/?probe=4d96f7358c) | Aug 10, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| Unknown       | QNAP TS-221                 | Desktop     | [8d3f7ca9cf](https://linux-hardware.org/?probe=8d3f7ca9cf) | Aug 10, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [2781a13b80](https://linux-hardware.org/?probe=2781a13b80) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [9b228ae787](https://linux-hardware.org/?probe=9b228ae787) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [9f2e51f185](https://linux-hardware.org/?probe=9f2e51f185) | Aug 10, 2022 |
| ASRock        | P67 Extreme4 Gen3           | Desktop     | [b94e1be5ab](https://linux-hardware.org/?probe=b94e1be5ab) | Aug 09, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [0e7d0b5d33](https://linux-hardware.org/?probe=0e7d0b5d33) | Aug 09, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f10876798](https://linux-hardware.org/?probe=1f10876798) | Aug 08, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [f97852a196](https://linux-hardware.org/?probe=f97852a196) | Aug 08, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [78f846e0e5](https://linux-hardware.org/?probe=78f846e0e5) | Aug 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ac538e23dc](https://linux-hardware.org/?probe=ac538e23dc) | Aug 07, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [ca880d8154](https://linux-hardware.org/?probe=ca880d8154) | Aug 06, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3e7a65077d](https://linux-hardware.org/?probe=3e7a65077d) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [2ff6a7fe85](https://linux-hardware.org/?probe=2ff6a7fe85) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [d54acf14ff](https://linux-hardware.org/?probe=d54acf14ff) | Aug 06, 2022 |
| Toshiba       | NB100                       | Notebook    | [b91ee9b36b](https://linux-hardware.org/?probe=b91ee9b36b) | Aug 05, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [019849a487](https://linux-hardware.org/?probe=019849a487) | Aug 04, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [b875ef6dbf](https://linux-hardware.org/?probe=b875ef6dbf) | Aug 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [f14436327b](https://linux-hardware.org/?probe=f14436327b) | Aug 04, 2022 |
| Samsung       | 700G7C                      | Notebook    | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3db1e1ee37](https://linux-hardware.org/?probe=3db1e1ee37) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | Notebook    | [fa1566785a](https://linux-hardware.org/?probe=fa1566785a) | Aug 03, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [2cea7378e8](https://linux-hardware.org/?probe=2cea7378e8) | Aug 03, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [69188053f5](https://linux-hardware.org/?probe=69188053f5) | Aug 02, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [eed9f05678](https://linux-hardware.org/?probe=eed9f05678) | Aug 01, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [19d2273e6b](https://linux-hardware.org/?probe=19d2273e6b) | Aug 01, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [effa59ed64](https://linux-hardware.org/?probe=effa59ed64) | Aug 01, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [0ac4f27d0f](https://linux-hardware.org/?probe=0ac4f27d0f) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f22250f00c](https://linux-hardware.org/?probe=f22250f00c) | Jul 31, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1051593809](https://linux-hardware.org/?probe=1051593809) | Jul 31, 2022 |
| Gigabyte      | 970A-DS3                    | Desktop     | [78f00bd2aa](https://linux-hardware.org/?probe=78f00bd2aa) | Jul 30, 2022 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [359f708604](https://linux-hardware.org/?probe=359f708604) | Jul 30, 2022 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [d3d824f468](https://linux-hardware.org/?probe=d3d824f468) | Jul 29, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [29a26324b9](https://linux-hardware.org/?probe=29a26324b9) | Jul 29, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [88a326be83](https://linux-hardware.org/?probe=88a326be83) | Jul 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [a8dc9cfc07](https://linux-hardware.org/?probe=a8dc9cfc07) | Jul 27, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [5ff32931fa](https://linux-hardware.org/?probe=5ff32931fa) | Jul 27, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [dc7eff27cf](https://linux-hardware.org/?probe=dc7eff27cf) | Jul 26, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | Notebook    | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b15fb90c18](https://linux-hardware.org/?probe=b15fb90c18) | Jul 26, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [c98fed5f84](https://linux-hardware.org/?probe=c98fed5f84) | Jul 25, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [dae325b47b](https://linux-hardware.org/?probe=dae325b47b) | Jul 25, 2022 |
| Dell          | 0FKD45 A03                  | Server      | [0caba2e4b0](https://linux-hardware.org/?probe=0caba2e4b0) | Jul 25, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8f46b7dcca](https://linux-hardware.org/?probe=8f46b7dcca) | Jul 25, 2022 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [64dad58b71](https://linux-hardware.org/?probe=64dad58b71) | Jul 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [6302f1ee8b](https://linux-hardware.org/?probe=6302f1ee8b) | Jul 25, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e1e16aa154](https://linux-hardware.org/?probe=e1e16aa154) | Jul 25, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [153acd77c2](https://linux-hardware.org/?probe=153acd77c2) | Jul 24, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [a15c82ba0c](https://linux-hardware.org/?probe=a15c82ba0c) | Jul 24, 2022 |
| TYAN Compu... | S7025                       | Server      | [844d96fcd7](https://linux-hardware.org/?probe=844d96fcd7) | Jul 22, 2022 |
| Unknown       | QNAP TS-221                 | Desktop     | [fb3741faab](https://linux-hardware.org/?probe=fb3741faab) | Jul 21, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [56d5853243](https://linux-hardware.org/?probe=56d5853243) | Jul 19, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d3d26541f1](https://linux-hardware.org/?probe=d3d26541f1) | Jul 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8f2f1582e8](https://linux-hardware.org/?probe=8f2f1582e8) | Jul 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [056d74f1a9](https://linux-hardware.org/?probe=056d74f1a9) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [e6b6d3b5e6](https://linux-hardware.org/?probe=e6b6d3b5e6) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [93f8a4ce9f](https://linux-hardware.org/?probe=93f8a4ce9f) | Jul 16, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [e9e0b50bbb](https://linux-hardware.org/?probe=e9e0b50bbb) | Jul 15, 2022 |
| Dell          | Latitude 5289               | Convertible | [a0844cdadd](https://linux-hardware.org/?probe=a0844cdadd) | Jul 15, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [4d636c74d3](https://linux-hardware.org/?probe=4d636c74d3) | Jul 14, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [8602f7246a](https://linux-hardware.org/?probe=8602f7246a) | Jul 12, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [0d6de2415e](https://linux-hardware.org/?probe=0d6de2415e) | Jul 11, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [30ad17796f](https://linux-hardware.org/?probe=30ad17796f) | Jul 11, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [f67a64f833](https://linux-hardware.org/?probe=f67a64f833) | Jul 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [dccb88852f](https://linux-hardware.org/?probe=dccb88852f) | Jul 10, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0237c9df10](https://linux-hardware.org/?probe=0237c9df10) | Jul 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85dbd84c37](https://linux-hardware.org/?probe=85dbd84c37) | Jul 09, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [aa87616696](https://linux-hardware.org/?probe=aa87616696) | Jul 09, 2022 |
| Dell          | Latitude D420               | Notebook    | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [097cc820d3](https://linux-hardware.org/?probe=097cc820d3) | Jul 08, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [5bdfb575ae](https://linux-hardware.org/?probe=5bdfb575ae) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [850003c6da](https://linux-hardware.org/?probe=850003c6da) | Jul 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [685e3d36bc](https://linux-hardware.org/?probe=685e3d36bc) | Jul 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b436712f17](https://linux-hardware.org/?probe=b436712f17) | Jul 04, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d442c531e8](https://linux-hardware.org/?probe=d442c531e8) | Jul 03, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [cf8784ac23](https://linux-hardware.org/?probe=cf8784ac23) | Jul 03, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [c1e5d91a40](https://linux-hardware.org/?probe=c1e5d91a40) | Jul 02, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [253c441703](https://linux-hardware.org/?probe=253c441703) | Jul 02, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [d030e357db](https://linux-hardware.org/?probe=d030e357db) | Jul 02, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [1af80d1cdb](https://linux-hardware.org/?probe=1af80d1cdb) | Jul 01, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [fb3b3f37d5](https://linux-hardware.org/?probe=fb3b3f37d5) | Jun 30, 2022 |
| Dell          | Latitude D420               | Notebook    | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [f03dcf744a](https://linux-hardware.org/?probe=f03dcf744a) | Jun 26, 2022 |
| Dell          | Precision 7550              | Notebook    | [4779d18806](https://linux-hardware.org/?probe=4779d18806) | Jun 24, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [74060af6fc](https://linux-hardware.org/?probe=74060af6fc) | Jun 23, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [bab7d495b0](https://linux-hardware.org/?probe=bab7d495b0) | Jun 21, 2022 |
| AVITA         | NS14A6                      | Notebook    | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Intel         | S5000XVN                    | Server      | [da50147a63](https://linux-hardware.org/?probe=da50147a63) | Jun 20, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [b290cf5fe0](https://linux-hardware.org/?probe=b290cf5fe0) | Jun 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [2028b239fc](https://linux-hardware.org/?probe=2028b239fc) | Jun 19, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [20c198dd50](https://linux-hardware.org/?probe=20c198dd50) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [9d03e8cba7](https://linux-hardware.org/?probe=9d03e8cba7) | Jun 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| Dell          | G3 3500                     | Notebook    | [396a536231](https://linux-hardware.org/?probe=396a536231) | Jun 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fe7fa5fe7a](https://linux-hardware.org/?probe=fe7fa5fe7a) | Jun 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [6fa09c2dd0](https://linux-hardware.org/?probe=6fa09c2dd0) | Jun 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [d3f9fd8f0c](https://linux-hardware.org/?probe=d3f9fd8f0c) | Jun 16, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [283958f1a4](https://linux-hardware.org/?probe=283958f1a4) | Jun 12, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [197f417cea](https://linux-hardware.org/?probe=197f417cea) | Jun 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [80a6dc4a46](https://linux-hardware.org/?probe=80a6dc4a46) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [f237211ddb](https://linux-hardware.org/?probe=f237211ddb) | Jun 09, 2022 |
| Pegatron      | 2ACE                        | Desktop     | [838cad5bc2](https://linux-hardware.org/?probe=838cad5bc2) | Jun 06, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [5745c8b787](https://linux-hardware.org/?probe=5745c8b787) | Jun 06, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [fd5c0c6f83](https://linux-hardware.org/?probe=fd5c0c6f83) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| Dell          | G3 3500                     | Notebook    | [edbd452524](https://linux-hardware.org/?probe=edbd452524) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6f9883076](https://linux-hardware.org/?probe=c6f9883076) | Jun 05, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [f2ca17eb5d](https://linux-hardware.org/?probe=f2ca17eb5d) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [4abb49be35](https://linux-hardware.org/?probe=4abb49be35) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [102ed915c5](https://linux-hardware.org/?probe=102ed915c5) | Jun 02, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [d17975e27b](https://linux-hardware.org/?probe=d17975e27b) | Jun 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0a458659f6](https://linux-hardware.org/?probe=0a458659f6) | Jun 01, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [09fcdacb15](https://linux-hardware.org/?probe=09fcdacb15) | Jun 01, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [d33b756434](https://linux-hardware.org/?probe=d33b756434) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2c33cbbbe2](https://linux-hardware.org/?probe=2c33cbbbe2) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6e43e1d4f1](https://linux-hardware.org/?probe=6e43e1d4f1) | May 30, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [bd36f27f9b](https://linux-hardware.org/?probe=bd36f27f9b) | May 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [641c79318b](https://linux-hardware.org/?probe=641c79318b) | May 27, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [86021dcc38](https://linux-hardware.org/?probe=86021dcc38) | May 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e879d3c292](https://linux-hardware.org/?probe=e879d3c292) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [0948f30719](https://linux-hardware.org/?probe=0948f30719) | May 26, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [b8603fccc0](https://linux-hardware.org/?probe=b8603fccc0) | May 26, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [1d5fe9025a](https://linux-hardware.org/?probe=1d5fe9025a) | May 25, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [38ac6de56d](https://linux-hardware.org/?probe=38ac6de56d) | May 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [59eda31291](https://linux-hardware.org/?probe=59eda31291) | May 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [b253c6e007](https://linux-hardware.org/?probe=b253c6e007) | May 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [add67dab1a](https://linux-hardware.org/?probe=add67dab1a) | May 24, 2022 |
| ASRockRack    | E3C232D2I                   | Desktop     | [0442460b97](https://linux-hardware.org/?probe=0442460b97) | May 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e370a75aa](https://linux-hardware.org/?probe=4e370a75aa) | May 23, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [e254f29ffd](https://linux-hardware.org/?probe=e254f29ffd) | May 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [93700a286d](https://linux-hardware.org/?probe=93700a286d) | May 23, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [6f78dba14b](https://linux-hardware.org/?probe=6f78dba14b) | May 23, 2022 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [ce350dd874](https://linux-hardware.org/?probe=ce350dd874) | May 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f129f3b1d5](https://linux-hardware.org/?probe=f129f3b1d5) | May 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [8f47f3a71c](https://linux-hardware.org/?probe=8f47f3a71c) | May 22, 2022 |
| Supermicro    | H12SSL-NT                   | Server      | [6492614879](https://linux-hardware.org/?probe=6492614879) | May 21, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [04a6359630](https://linux-hardware.org/?probe=04a6359630) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [47297bafb5](https://linux-hardware.org/?probe=47297bafb5) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [7b878500c1](https://linux-hardware.org/?probe=7b878500c1) | May 21, 2022 |
| MSI           | MS-7A34                     | Notebook    | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f7225b80ed](https://linux-hardware.org/?probe=f7225b80ed) | May 18, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [84a0dc5b83](https://linux-hardware.org/?probe=84a0dc5b83) | May 18, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [1dbb37fcd0](https://linux-hardware.org/?probe=1dbb37fcd0) | May 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d5477b3bb9](https://linux-hardware.org/?probe=d5477b3bb9) | May 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [818ee286b7](https://linux-hardware.org/?probe=818ee286b7) | May 17, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [0de514cd0b](https://linux-hardware.org/?probe=0de514cd0b) | May 16, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [56fb967887](https://linux-hardware.org/?probe=56fb967887) | May 16, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f64f274146](https://linux-hardware.org/?probe=f64f274146) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [d1a9527039](https://linux-hardware.org/?probe=d1a9527039) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [d675d89c8a](https://linux-hardware.org/?probe=d675d89c8a) | May 16, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [9afc74ed46](https://linux-hardware.org/?probe=9afc74ed46) | May 16, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [28b47bc364](https://linux-hardware.org/?probe=28b47bc364) | May 15, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [49a3292018](https://linux-hardware.org/?probe=49a3292018) | May 15, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [020e862674](https://linux-hardware.org/?probe=020e862674) | May 15, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [59c5dbcb22](https://linux-hardware.org/?probe=59c5dbcb22) | May 15, 2022 |
| ASUSTek       | Z8NR-D12                    | Desktop     | [e65adcd0da](https://linux-hardware.org/?probe=e65adcd0da) | May 14, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [07e2cea31c](https://linux-hardware.org/?probe=07e2cea31c) | May 13, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [cf73bc12e8](https://linux-hardware.org/?probe=cf73bc12e8) | May 13, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | Notebook    | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [df570dd8e0](https://linux-hardware.org/?probe=df570dd8e0) | May 12, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [8328bbecb9](https://linux-hardware.org/?probe=8328bbecb9) | May 12, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [2fcf37c00a](https://linux-hardware.org/?probe=2fcf37c00a) | May 11, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [474578814d](https://linux-hardware.org/?probe=474578814d) | May 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [5ccbf39183](https://linux-hardware.org/?probe=5ccbf39183) | May 10, 2022 |
| HP            | 8704                        | Desktop     | [b66f290b02](https://linux-hardware.org/?probe=b66f290b02) | May 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [0f04e6b439](https://linux-hardware.org/?probe=0f04e6b439) | May 09, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [bd6c3ca5b4](https://linux-hardware.org/?probe=bd6c3ca5b4) | May 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [81aa293c77](https://linux-hardware.org/?probe=81aa293c77) | May 08, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ee92f88374](https://linux-hardware.org/?probe=ee92f88374) | May 07, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [67dbf0ac88](https://linux-hardware.org/?probe=67dbf0ac88) | May 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [8919eebaa3](https://linux-hardware.org/?probe=8919eebaa3) | May 05, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [b51c7ae18b](https://linux-hardware.org/?probe=b51c7ae18b) | May 04, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [48fa5d3b93](https://linux-hardware.org/?probe=48fa5d3b93) | May 04, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [8df6782398](https://linux-hardware.org/?probe=8df6782398) | May 02, 2022 |
| Dell          | Precision 3520              | Notebook    | [caae9a5055](https://linux-hardware.org/?probe=caae9a5055) | May 02, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [b24677a908](https://linux-hardware.org/?probe=b24677a908) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [55402e38ae](https://linux-hardware.org/?probe=55402e38ae) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [df7b5507c1](https://linux-hardware.org/?probe=df7b5507c1) | Apr 30, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [07a115654d](https://linux-hardware.org/?probe=07a115654d) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [970d30df6d](https://linux-hardware.org/?probe=970d30df6d) | Apr 29, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [94d74e9b78](https://linux-hardware.org/?probe=94d74e9b78) | Apr 29, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [45630a42df](https://linux-hardware.org/?probe=45630a42df) | Apr 29, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Gentoo/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Gentoo 2.7     | 555       | 33.53%  |
| Gentoo 2.6     | 412       | 24.89%  |
| Gentoo 2.8     | 306       | 18.49%  |
| Gentoo 2.13    | 171       | 10.33%  |
| Gentoo 2.9     | 159       | 9.61%   |
| Gentoo 2.4.1   | 14        | 0.85%   |
| Gentoo         | 11        | 0.66%   |
| Gentoo 2.3     | 9         | 0.54%   |
| Gentoo 2.2     | 7         | 0.42%   |
| Gentoo 1       | 3         | 0.18%   |
| Gentoo 22.0.1  | 2         | 0.12%   |
| Gentoo Pelikan | 1         | 0.06%   |
| Gentoo 23      | 1         | 0.06%   |
| Gentoo 22      | 1         | 0.06%   |
| Gentoo 2022    | 1         | 0.06%   |
| Gentoo 2.1     | 1         | 0.06%   |
| Gentoo 13.0    | 1         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Gentoo | 1457      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.38-gentoo            | 26        | 1.34%   |
| 5.10.27-gentoo           | 25        | 1.29%   |
| 5.10.61-gentoo           | 23        | 1.19%   |
| 5.15.32-gentoo-r1        | 18        | 0.93%   |
| 5.15.80-gentoo-x86_64    | 16        | 0.83%   |
| 5.15.80-gentoo           | 16        | 0.83%   |
| 6.1.12-gentoo            | 15        | 0.78%   |
| 5.4.80-gentoo-r1         | 15        | 0.78%   |
| 5.4.48-gentoo            | 15        | 0.78%   |
| 6.1.19-gentoo-x86_64     | 14        | 0.72%   |
| 5.4.97-gentoo            | 14        | 0.72%   |
| 5.4.28-gentoo            | 14        | 0.72%   |
| 5.10.76-gentoo-r1        | 14        | 0.72%   |
| 6.1.19-gentoo            | 13        | 0.67%   |
| 5.15.75-gentoo-x86_64    | 13        | 0.67%   |
| 5.10.61-gentoo-x86_64    | 13        | 0.67%   |
| 5.10.27-gentoo-x86_64    | 13        | 0.67%   |
| 5.15.59-gentoo-x86_64    | 12        | 0.62%   |
| 5.15.32-gentoo-r1-x86_64 | 12        | 0.62%   |
| 5.10.52-gentoo           | 12        | 0.62%   |
| 5.7.0-gentoo             | 11        | 0.57%   |
| 5.4.60-gentoo            | 11        | 0.57%   |
| 5.15.88-gentoo           | 11        | 0.57%   |
| 5.4.38-gentoo-x86_64     | 10        | 0.52%   |
| 6.1.12-gentoo-x86_64     | 9         | 0.47%   |
| 5.15.75-gentoo           | 9         | 0.47%   |
| 5.15.59-gentoo           | 9         | 0.47%   |
| 5.15.52-gentoo-x86_64    | 9         | 0.47%   |
| 5.15.52-gentoo           | 9         | 0.47%   |
| 5.15.41-gentoo-x86_64    | 9         | 0.47%   |
| 5.10.76-gentoo-r1-x86_64 | 9         | 0.47%   |
| 5.6.15-gentoo            | 8         | 0.41%   |
| 5.4.66-gentoo            | 8         | 0.41%   |
| 5.4.48-gentoo-x86_64     | 8         | 0.41%   |
| 5.15.69-gentoo           | 8         | 0.41%   |
| 5.15.41-gentoo           | 8         | 0.41%   |
| 4.19.86-gentoo           | 8         | 0.41%   |
| 5.4.97-gentoo-x86_64     | 7         | 0.36%   |
| 5.4.66-gentoo-x86_64     | 7         | 0.36%   |
| 5.17.1-gentoo-r1         | 7         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.27 | 46        | 2.38%   |
| 5.4.38  | 45        | 2.33%   |
| 5.15.32 | 41        | 2.12%   |
| 5.10.61 | 39        | 2.02%   |
| 6.1.19  | 35        | 1.81%   |
| 6.1.12  | 34        | 1.76%   |
| 5.15.80 | 34        | 1.76%   |
| 5.4.48  | 33        | 1.71%   |
| 5.10.76 | 32        | 1.66%   |
| 5.15.75 | 30        | 1.55%   |
| 5.4.97  | 25        | 1.29%   |
| 5.4.28  | 25        | 1.29%   |
| 5.15.59 | 25        | 1.29%   |
| 5.15.52 | 24        | 1.24%   |
| 5.15.41 | 23        | 1.19%   |
| 5.10.52 | 23        | 1.19%   |
| 5.4.80  | 22        | 1.14%   |
| 5.15.11 | 19        | 0.98%   |
| 5.4.66  | 17        | 0.88%   |
| 5.15.88 | 17        | 0.88%   |
| 5.6.15  | 16        | 0.83%   |
| 5.4.60  | 16        | 0.83%   |
| 5.17.1  | 16        | 0.83%   |
| 5.15.69 | 16        | 0.83%   |
| 5.7.0   | 15        | 0.78%   |
| 5.15.72 | 15        | 0.78%   |
| 5.15.23 | 15        | 0.78%   |
| 5.4.72  | 13        | 0.67%   |
| 4.19.97 | 13        | 0.67%   |
| 6.2.11  | 12        | 0.62%   |
| 6.0.0   | 12        | 0.62%   |
| 5.9.11  | 12        | 0.62%   |
| 5.19.0  | 12        | 0.62%   |
| 5.15.74 | 12        | 0.62%   |
| 5.15.26 | 12        | 0.62%   |
| 5.15.10 | 12        | 0.62%   |
| 6.1.7   | 10        | 0.52%   |
| 5.9.8   | 10        | 0.52%   |
| 5.8.0   | 10        | 0.52%   |
| 4.19.86 | 10        | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 331       | 18.56%  |
| 5.4     | 230       | 12.9%   |
| 5.10    | 224       | 12.56%  |
| 6.1     | 138       | 7.74%   |
| 4.19    | 66        | 3.7%    |
| 5.6     | 64        | 3.59%   |
| 5.9     | 58        | 3.25%   |
| 5.8     | 54        | 3.03%   |
| 6.2     | 53        | 2.97%   |
| 5.7     | 49        | 2.75%   |
| 5.16    | 49        | 2.75%   |
| 5.14    | 49        | 2.75%   |
| 5.17    | 48        | 2.69%   |
| 6.0     | 45        | 2.52%   |
| 5.18    | 41        | 2.3%    |
| 5.11    | 41        | 2.3%    |
| 5.19    | 36        | 2.02%   |
| 5.13    | 36        | 2.02%   |
| 5.12    | 30        | 1.68%   |
| 6.3     | 28        | 1.57%   |
| 5.5     | 17        | 0.95%   |
| 4.14    | 17        | 0.95%   |
| 5.2     | 12        | 0.67%   |
| 5.1     | 10        | 0.56%   |
| 5.3     | 9         | 0.5%    |
| 5.0     | 9         | 0.5%    |
| 4.9     | 8         | 0.45%   |
| 4.4     | 8         | 0.45%   |
| 4.18    | 7         | 0.39%   |
| 4.6     | 3         | 0.17%   |
| 4.12    | 3         | 0.17%   |
| 4.20    | 2         | 0.11%   |
| 4.10    | 2         | 0.11%   |
| 6.4     | 1         | 0.06%   |
| 4.5     | 1         | 0.06%   |
| 4.16    | 1         | 0.06%   |
| 4.13    | 1         | 0.06%   |
| 4.1     | 1         | 0.06%   |
| 3.18    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| x86_64   | 1396      | 95.81%  |
| i686     | 31        | 2.13%   |
| aarch64  | 12        | 0.82%   |
| ppc      | 7         | 0.48%   |
| armv7l   | 3         | 0.21%   |
| armv6l   | 3         | 0.21%   |
| armv5tel | 2         | 0.14%   |
| riscv64  | 1         | 0.07%   |
| ppc64le  | 1         | 0.07%   |
| ppc64    | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 665       | 42.52%  |
| KDE5           | 335       | 21.42%  |
| GNOME          | 190       | 12.15%  |
| XFCE           | 137       | 8.76%   |
| KDE            | 60        | 3.84%   |
| MATE           | 40        | 2.56%   |
| DWM            | 24        | 1.53%   |
| LXQt           | 17        | 1.09%   |
| sway           | 13        | 0.83%   |
| X-Cinnamon     | 10        | 0.64%   |
| i3             | 10        | 0.64%   |
| Enlightenment  | 8         | 0.51%   |
| LXDE           | 7         | 0.45%   |
| Xsession       | 6         | 0.38%   |
| Cinnamon       | 6         | 0.38%   |
| awesome        | 6         | 0.38%   |
| Hyprland       | 5         | 0.32%   |
| openbox        | 4         | 0.26%   |
| bspwm          | 4         | 0.26%   |
| Trinity        | 3         | 0.19%   |
| Unity          | 2         | 0.13%   |
| GNOME Classic  | 2         | 0.13%   |
| xmonad         | 1         | 0.06%   |
| X-Generic      | 1         | 0.06%   |
| sussy_bspwm    | 1         | 0.06%   |
| ratpoison      | 1         | 0.06%   |
| qt5ct          | 1         | 0.06%   |
| LeftWM         | 1         | 0.06%   |
| ICEWM          | 1         | 0.06%   |
| i3-with-shmlog | 1         | 0.06%   |
| fvwm           | 1         | 0.06%   |
| fluxbox        | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 845       | 54.03%  |
| Unknown | 298       | 19.05%  |
| Tty     | 242       | 15.47%  |
| Wayland | 179       | 11.45%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 738       | 48.27%  |
| SDDM    | 396       | 25.9%   |
| LightDM | 173       | 11.31%  |
| GDM     | 133       | 8.7%    |
| XDM     | 27        | 1.77%   |
| SLiM    | 26        | 1.7%    |
| LXDM    | 19        | 1.24%   |
| GREETD  | 8         | 0.52%   |
| TDM     | 7         | 0.46%   |
| KDM     | 1         | 0.07%   |
| GDM3    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 566       | 36.95%  |
| Unknown    | 229       | 14.95%  |
| C.UTF8     | 137       | 8.94%   |
| de_DE      | 97        | 6.33%   |
| en_GB      | 94        | 6.14%   |
| ru_RU      | 65        | 4.24%   |
| C          | 40        | 2.61%   |
| fr_FR      | 30        | 1.96%   |
| es_ES      | 23        | 1.5%    |
| en_CA      | 22        | 1.44%   |
| it_IT      | 20        | 1.31%   |
| cs_CZ      | 19        | 1.24%   |
| en_AU      | 18        | 1.17%   |
| pl_PL      | 16        | 1.04%   |
| zh_CN      | 10        | 0.65%   |
| pt_BR      | 10        | 0.65%   |
| en_IE      | 9         | 0.59%   |
| sv_SE      | 6         | 0.39%   |
| ru_RU.UTF8 | 6         | 0.39%   |
| POSIX      | 6         | 0.39%   |
| nl_NL      | 6         | 0.39%   |
| en_US.UTF8 | 6         | 0.39%   |
| el_GR      | 6         | 0.39%   |
| nl_BE      | 5         | 0.33%   |
| ja_JP      | 5         | 0.33%   |
| fi_FI      | 5         | 0.33%   |
| ca_ES      | 5         | 0.33%   |
| uk_UA      | 4         | 0.26%   |
| fr_CA      | 4         | 0.26%   |
| de_CH      | 4         | 0.26%   |
| zh_TW      | 3         | 0.2%    |
| ro_RO      | 3         | 0.2%    |
| es_MX      | 3         | 0.2%    |
| es_AR      | 3         | 0.2%    |
| en_ZA      | 3         | 0.2%    |
| ru_UA      | 2         | 0.13%   |
| pt_PT      | 2         | 0.13%   |
| mi_NZ      | 2         | 0.13%   |
| ko_KR      | 2         | 0.13%   |
| es_CL      | 2         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1062      | 71.42%  |
| BIOS | 425       | 28.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 881       | 59.13%  |
| Btrfs    | 348       | 23.36%  |
| Xfs      | 58        | 3.89%   |
| Zfs      | 54        | 3.62%   |
| F2fs     | 53        | 3.56%   |
| Unknown  | 46        | 3.09%   |
| XXXXXXX  | 20        | 1.34%   |
| Reiserfs | 16        | 1.07%   |
| Overlay  | 3         | 0.2%    |
| Jfs      | 3         | 0.2%    |
| Ext3     | 3         | 0.2%    |
| XXX      | 2         | 0.13%   |
| Xtrfs    | 1         | 0.07%   |
| Ext2     | 1         | 0.07%   |
| Bcachefs | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1226      | 82.84%  |
| MBR     | 170       | 11.49%  |
| Unknown | 84        | 5.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1025      | 67.17%  |
| Yes       | 501       | 32.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 996       | 66.67%  |
| Yes       | 498       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 330       | 22.65%  |
| Lenovo                  | 214       | 14.69%  |
| Dell                    | 141       | 9.68%   |
| Hewlett-Packard         | 128       | 8.79%   |
| MSI                     | 125       | 8.58%   |
| Gigabyte Technology     | 97        | 6.66%   |
| ASRock                  | 89        | 6.11%   |
| Acer                    | 48        | 3.29%   |
| Unknown                 | 29        | 1.99%   |
| Intel                   | 28        | 1.92%   |
| Apple                   | 25        | 1.72%   |
| Supermicro              | 21        | 1.44%   |
| Raspberry Pi Foundation | 13        | 0.89%   |
| HUAWEI                  | 12        | 0.82%   |
| Timi                    | 11        | 0.75%   |
| Samsung Electronics     | 11        | 0.75%   |
| Fujitsu                 | 11        | 0.75%   |
| Toshiba                 | 9         | 0.62%   |
| TUXEDO                  | 7         | 0.48%   |
| Razer                   | 5         | 0.34%   |
| IBM                     | 5         | 0.34%   |
| ASRockRack              | 5         | 0.34%   |
| TYAN Computer           | 4         | 0.27%   |
| Notebook                | 4         | 0.27%   |
| Google                  | 4         | 0.27%   |
| Tekram Technology       | 3         | 0.21%   |
| System76                | 3         | 0.21%   |
| Sony                    | 3         | 0.21%   |
| Pegatron                | 3         | 0.21%   |
| Medion                  | 3         | 0.21%   |
| Foxconn                 | 3         | 0.21%   |
| Alienware               | 3         | 0.21%   |
| ZOTAC                   | 2         | 0.14%   |
| win element             | 2         | 0.14%   |
| Valve                   | 2         | 0.14%   |
| Star Labs               | 2         | 0.14%   |
| Schenker                | 2         | 0.14%   |
| Purism                  | 2         | 0.14%   |
| Positivo                | 2         | 0.14%   |
| Microsoft               | 2         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 36        | 2.47%   |
| ASUS All Series                       | 21        | 1.44%   |
| ASUS TUF Gaming X570-PLUS             | 12        | 0.82%   |
| Supermicro Super Server               | 9         | 0.62%   |
| ASUS PRIME X570-PRO                   | 8         | 0.55%   |
| ASUS PRIME X470-PRO                   | 7         | 0.48%   |
| MSI MS-7C02                           | 6         | 0.41%   |
| MSI MS-7A38                           | 6         | 0.41%   |
| Dell XPS 15 9570                      | 6         | 0.41%   |
| ASUS ROG STRIX X570-E GAMING          | 6         | 0.41%   |
| MSI MS-7C37                           | 5         | 0.34%   |
| MSI MS-7C35                           | 5         | 0.34%   |
| HP Pavilion Notebook                  | 5         | 0.34%   |
| HP OMEN by Laptop                     | 5         | 0.34%   |
| ASUS TUF Gaming B550-PLUS             | 5         | 0.34%   |
| ASUS ROG Strix G513QY_G513QY          | 5         | 0.34%   |
| ASUS ROG CROSSHAIR VIII HERO          | 5         | 0.34%   |
| ASUS PRIME X370-PRO                   | 5         | 0.34%   |
| ASRock B450 Pro4                      | 5         | 0.34%   |
| MSI MS-7C91                           | 4         | 0.27%   |
| MSI MS-7B89                           | 4         | 0.27%   |
| MSI MS-7B86                           | 4         | 0.27%   |
| MSI MS-7B79                           | 4         | 0.27%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 4         | 0.27%   |
| HP Laptop 14-dk1xxx                   | 4         | 0.27%   |
| Dell XPS 17 9710                      | 4         | 0.27%   |
| Dell XPS 13 9310                      | 4         | 0.27%   |
| ASUS Z170 PRO GAMING                  | 4         | 0.27%   |
| ASUS ROG Zephyrus G14 GA401II_GA401II | 4         | 0.27%   |
| ASUS ROG STRIX B550-F GAMING          | 4         | 0.27%   |
| ASUS ROG STRIX B450-F GAMING          | 4         | 0.27%   |
| ASUS ROG CROSSHAIR VIII DARK HERO     | 4         | 0.27%   |
| ASUS ROG CROSSHAIR VII HERO           | 4         | 0.27%   |
| ASUS PRIME X570-P                     | 4         | 0.27%   |
| ASUS PRIME B450M-A                    | 4         | 0.27%   |
| ASUS M4A89GTD-PRO/USB3                | 4         | 0.27%   |
| ASRock B550M Steel Legend             | 4         | 0.27%   |
| TYAN S7025                            | 3         | 0.21%   |
| Tekram P6B40-A4X-i440BX Rev           | 3         | 0.21%   |
| Supermicro X10SAE                     | 3         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 121       | 8.3%    |
| ASUS ROG          | 84        | 5.77%   |
| ASUS PRIME        | 55        | 3.77%   |
| Dell Latitude     | 41        | 2.81%   |
| ASUS TUF          | 41        | 2.81%   |
| Dell XPS          | 40        | 2.75%   |
| Unknown           | 36        | 2.47%   |
| Acer Aspire       | 28        | 1.92%   |
| Lenovo Legion     | 25        | 1.72%   |
| Lenovo IdeaPad    | 25        | 1.72%   |
| HP Pavilion       | 25        | 1.72%   |
| HP EliteBook      | 21        | 1.44%   |
| ASUS All          | 21        | 1.44%   |
| Dell Inspiron     | 18        | 1.24%   |
| Dell Precision    | 17        | 1.17%   |
| HP Laptop         | 15        | 1.03%   |
| Lenovo Yoga       | 14        | 0.96%   |
| RPi Raspberry     | 13        | 0.89%   |
| HP OMEN           | 12        | 0.82%   |
| Gigabyte X570     | 11        | 0.75%   |
| ASRock X570       | 11        | 0.75%   |
| Supermicro Super  | 9         | 0.62%   |
| HP ProBook        | 9         | 0.62%   |
| Dell OptiPlex     | 9         | 0.62%   |
| Gigabyte B450M    | 8         | 0.55%   |
| Gigabyte B450     | 8         | 0.55%   |
| ASUS ZenBook      | 8         | 0.55%   |
| ASUS VivoBook     | 8         | 0.55%   |
| ASRock X370       | 8         | 0.55%   |
| Acer Swift        | 8         | 0.55%   |
| Toshiba Satellite | 7         | 0.48%   |
| HP ProLiant       | 7         | 0.48%   |
| Acer Nitro        | 7         | 0.48%   |
| Timi RedmiBook    | 6         | 0.41%   |
| MSI MS-7C02       | 6         | 0.41%   |
| MSI MS-7A38       | 6         | 0.41%   |
| HP ZBook          | 6         | 0.41%   |
| HP Compaq         | 6         | 0.41%   |
| ASRock B450       | 6         | 0.41%   |
| Razer Blade       | 5         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 231       | 15.85%  |
| 2020    | 204       | 14%     |
| 2018    | 188       | 12.9%   |
| 2021    | 150       | 10.3%   |
| 2017    | 92        | 6.31%   |
| 2015    | 69        | 4.74%   |
| 2012    | 68        | 4.67%   |
| 2022    | 67        | 4.6%    |
| 2016    | 59        | 4.05%   |
| 2013    | 57        | 3.91%   |
| 2014    | 56        | 3.84%   |
| 2011    | 49        | 3.36%   |
| 2010    | 42        | 2.88%   |
| 2008    | 29        | 1.99%   |
| 2009    | 28        | 1.92%   |
| Unknown | 28        | 1.92%   |
| 2007    | 10        | 0.69%   |
| 2006    | 7         | 0.48%   |
| 2023    | 5         | 0.34%   |
| 2005    | 5         | 0.34%   |
| 2004    | 5         | 0.34%   |
| 2003    | 4         | 0.27%   |
| 2000    | 3         | 0.21%   |
| 2002    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 681       | 46.74%  |
| Desktop        | 662       | 45.44%  |
| Server         | 39        | 2.68%   |
| Convertible    | 32        | 2.2%    |
| System on chip | 16        | 1.1%    |
| Mini pc        | 15        | 1.03%   |
| All in one     | 7         | 0.48%   |
| Tablet         | 3         | 0.21%   |
| Phone          | 1         | 0.07%   |
| Stick pc       | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1435      | 98.15%  |
| Enabled  | 27        | 1.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1447      | 99.31%  |
| Yes  | 10        | 0.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 361       | 24.1%   |
| 16.01-24.0      | 359       | 23.97%  |
| 8.01-16.0       | 227       | 15.15%  |
| 4.01-8.0        | 176       | 11.75%  |
| 64.01-256.0     | 159       | 10.61%  |
| 3.01-4.0        | 79        | 5.27%   |
| 24.01-32.0      | 58        | 3.87%   |
| 1.01-2.0        | 29        | 1.94%   |
| 0.51-1.0        | 20        | 1.34%   |
| 2.01-3.0        | 19        | 1.27%   |
| 0.01-0.5        | 8         | 0.53%   |
| More than 256.0 | 3         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 350       | 20.14%  |
| 4.01-8.0    | 324       | 18.64%  |
| 2.01-3.0    | 297       | 17.09%  |
| 3.01-4.0    | 192       | 11.05%  |
| 8.01-16.0   | 182       | 10.47%  |
| 0.01-0.5    | 169       | 9.72%   |
| 0.51-1.0    | 149       | 8.57%   |
| 16.01-24.0  | 43        | 2.47%   |
| 32.01-64.0  | 14        | 0.81%   |
| 24.01-32.0  | 11        | 0.63%   |
| 64.01-256.0 | 4         | 0.23%   |
| 0           | 3         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 670       | 43.76%  |
| 2      | 398       | 26%     |
| 3      | 181       | 11.82%  |
| 4      | 99        | 6.47%   |
| 5      | 75        | 4.9%    |
| 6      | 34        | 2.22%   |
| 7      | 28        | 1.83%   |
| 8      | 13        | 0.85%   |
| 0      | 12        | 0.78%   |
| 9      | 5         | 0.33%   |
| 13     | 4         | 0.26%   |
| 10     | 4         | 0.26%   |
| 12     | 3         | 0.2%    |
| 26     | 1         | 0.07%   |
| 21     | 1         | 0.07%   |
| 18     | 1         | 0.07%   |
| 17     | 1         | 0.07%   |
| 11     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1157      | 78.23%  |
| Yes       | 322       | 21.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1269      | 86.56%  |
| No        | 197       | 13.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 999       | 68.14%  |
| No        | 467       | 31.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 922       | 62.38%  |
| No        | 556       | 37.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 307       | 20.83%  |
| Germany      | 214       | 14.52%  |
| Russia       | 130       | 8.82%   |
| UK           | 72        | 4.88%   |
| France       | 66        | 4.48%   |
| Canada       | 59        | 4%      |
| Spain        | 48        | 3.26%   |
| Poland       | 46        | 3.12%   |
| China        | 45        | 3.05%   |
| Czechia      | 35        | 2.37%   |
| Australia    | 34        | 2.31%   |
| Italy        | 32        | 2.17%   |
| Sweden       | 31        | 2.1%    |
| Netherlands  | 30        | 2.04%   |
| Finland      | 26        | 1.76%   |
| Ukraine      | 22        | 1.49%   |
| Brazil       | 19        | 1.29%   |
| Switzerland  | 18        | 1.22%   |
| Greece       | 16        | 1.09%   |
| Belgium      | 14        | 0.95%   |
| Mexico       | 13        | 0.88%   |
| Austria      | 12        | 0.81%   |
| Norway       | 11        | 0.75%   |
| Japan        | 11        | 0.75%   |
| Romania      | 10        | 0.68%   |
| Belarus      | 10        | 0.68%   |
| Turkey       | 9         | 0.61%   |
| India        | 9         | 0.61%   |
| Hungary      | 9         | 0.61%   |
| Hong Kong    | 9         | 0.61%   |
| Taiwan       | 6         | 0.41%   |
| Slovakia     | 6         | 0.41%   |
| Portugal     | 6         | 0.41%   |
| Argentina    | 6         | 0.41%   |
| Vietnam      | 5         | 0.34%   |
| Slovenia     | 5         | 0.34%   |
| New Zealand  | 5         | 0.34%   |
| Denmark      | 5         | 0.34%   |
| South Africa | 4         | 0.27%   |
| Lithuania    | 4         | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 54        | 3.35%   |
| Moscow            | 45        | 2.79%   |
| St Petersburg     | 20        | 1.24%   |
| Sydney            | 17        | 1.05%   |
| Athens            | 16        | 0.99%   |
| Warsaw            | 15        | 0.93%   |
| Munich            | 14        | 0.87%   |
| Paris             | 13        | 0.81%   |
| Los Angeles       | 12        | 0.74%   |
| Frankfurt am Main | 12        | 0.74%   |
| Vancouver         | 11        | 0.68%   |
| Helsinki          | 11        | 0.68%   |
| Amsterdam         | 11        | 0.68%   |
| Milan             | 10        | 0.62%   |
| Kyiv              | 10        | 0.62%   |
| Cieszyn           | 10        | 0.62%   |
| Vladivostok       | 9         | 0.56%   |
| Prague            | 9         | 0.56%   |
| Guangzhou         | 9         | 0.56%   |
| Wuelfrath         | 8         | 0.5%    |
| Melbourne         | 8         | 0.5%    |
| Seattle           | 7         | 0.43%   |
| Oulu              | 7         | 0.43%   |
| Ottawa            | 7         | 0.43%   |
| Minsk             | 7         | 0.43%   |
| Beijing           | 7         | 0.43%   |
| Zurich            | 6         | 0.37%   |
| Woolwich          | 6         | 0.37%   |
| Weatherford       | 6         | 0.37%   |
| Vienna            | 6         | 0.37%   |
| Stockholm         | 6         | 0.37%   |
| Sterling          | 6         | 0.37%   |
| Perth             | 6         | 0.37%   |
| New York          | 6         | 0.37%   |
| Manitowoc         | 6         | 0.37%   |
| Hamburg           | 6         | 0.37%   |
| Dienheim          | 6         | 0.37%   |
| Barcelona         | 6         | 0.37%   |
| Yekaterinburg     | 5         | 0.31%   |
| Toronto           | 5         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 560       | 1128   | 22.45%  |
| WDC                         | 417       | 931    | 16.72%  |
| Seagate                     | 303       | 662    | 12.15%  |
| SanDisk                     | 127       | 178    | 5.09%   |
| Kingston                    | 121       | 171    | 4.85%   |
| Toshiba                     | 118       | 195    | 4.73%   |
| Intel                       | 112       | 179    | 4.49%   |
| Crucial                     | 76        | 128    | 3.05%   |
| SK hynix                    | 69        | 82     | 2.77%   |
| Unknown                     | 61        | 89     | 2.45%   |
| Hitachi                     | 59        | 153    | 2.37%   |
| HGST                        | 57        | 93     | 2.29%   |
| A-DATA Technology           | 38        | 54     | 1.52%   |
| Micron Technology           | 35        | 45     | 1.4%    |
| Phison Electronics          | 25        | 32     | 1%      |
| Phison                      | 21        | 31     | 0.84%   |
| KIOXIA                      | 18        | 23     | 0.72%   |
| Corsair                     | 18        | 33     | 0.72%   |
| OCZ                         | 16        | 22     | 0.64%   |
| China                       | 13        | 33     | 0.52%   |
| Kingston Technology Company | 10        | 11     | 0.4%    |
| GOODRAM                     | 10        | 46     | 0.4%    |
| Apple                       | 9         | 11     | 0.36%   |
| Transcend                   | 8         | 13     | 0.32%   |
| Micron/Crucial Technology   | 8         | 11     | 0.32%   |
| Silicon Motion              | 7         | 14     | 0.28%   |
| PNY                         | 7         | 10     | 0.28%   |
| Plextor                     | 7         | 8      | 0.28%   |
| Patriot                     | 7         | 11     | 0.28%   |
| Fujitsu                     | 7         | 10     | 0.28%   |
| XPG                         | 6         | 12     | 0.24%   |
| SPCC                        | 6         | 6      | 0.24%   |
| Mushkin                     | 6         | 6      | 0.24%   |
| LITEONIT                    | 6         | 7      | 0.24%   |
| Team                        | 5         | 12     | 0.2%    |
| Realtek Semiconductor       | 5         | 10     | 0.2%    |
| LITEON                      | 5         | 8      | 0.2%    |
| IBM                         | 5         | 6      | 0.2%    |
| Apacer                      | 5         | 7      | 0.2%    |
| ADATA Technology            | 5         | 7      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 59        | 1.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 38        | 1.26%   |
| Samsung SSD 860 EVO 1TB                             | 30        | 1%      |
| Samsung SSD 850 EVO 250GB                           | 29        | 0.96%   |
| HGST HTS721010A9E630 1TB                            | 25        | 0.83%   |
| Samsung SSD 860 EVO 500GB                           | 23        | 0.76%   |
| Samsung SSD 850 EVO 500GB                           | 22        | 0.73%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 21        | 0.7%    |
| Kingston SA400S37240G 240GB SSD                     | 21        | 0.7%    |
| Samsung SSD 980 1TB                                 | 19        | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB                      | 19        | 0.63%   |
| Samsung SSD 860 EVO 250GB                           | 19        | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB                      | 18        | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB                        | 15        | 0.5%    |
| Samsung SSD 970 EVO 500GB                           | 15        | 0.5%    |
| Seagate ST4000DM004-2CV104 4TB                      | 14        | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 13        | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB                      | 13        | 0.43%   |
| Samsung SSD 970 EVO 250GB                           | 13        | 0.43%   |
| Samsung SSD 970 EVO 1TB                             | 13        | 0.43%   |
| Unknown MMC Card  32GB                              | 12        | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB                      | 12        | 0.4%    |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 12        | 0.4%    |
| Samsung SSD 980 PRO 1TB                             | 12        | 0.4%    |
| Kingston SA400S37480G 480GB SSD                     | 12        | 0.4%    |
| WDC WD40EZRZ-00GXCB0 4TB                            | 11        | 0.37%   |
| Seagate ST500DM002-1BD142 500GB                     | 11        | 0.37%   |
| Samsung SSD 970 PRO 512GB                           | 11        | 0.37%   |
| Samsung SSD 840 EVO 120GB                           | 11        | 0.37%   |
| Intel SSDPEKNW010T8 1TB                             | 11        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                         | 11        | 0.37%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 10        | 0.33%   |
| Seagate ST3500418AS 500GB                           | 10        | 0.33%   |
| Samsung SSD 970 PRO 1TB                             | 10        | 0.33%   |
| Samsung SSD 970 EVO Plus 250GB                      | 10        | 0.33%   |
| Samsung SSD 870 EVO 1TB                             | 10        | 0.33%   |
| Samsung SSD 850 EVO 1TB                             | 10        | 0.33%   |
| Samsung SSD 840 EVO 250GB                           | 10        | 0.33%   |
| Samsung MZVLB512HBJQ-000L2 512GB                    | 10        | 0.33%   |
| Intel SSD 660P Series 512GB                         | 10        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 313       | 747    | 36.31%  |
| Seagate             | 294       | 646    | 34.11%  |
| Toshiba             | 81        | 147    | 9.4%    |
| Hitachi             | 59        | 153    | 6.84%   |
| HGST                | 57        | 93     | 6.61%   |
| Samsung Electronics | 27        | 40     | 3.13%   |
| Fujitsu             | 7         | 10     | 0.81%   |
| IBM                 | 5         | 6      | 0.58%   |
| Unknown             | 3         | 4      | 0.35%   |
| IBM/Hitachi         | 3         | 4      | 0.35%   |
| MDT                 | 2         | 2      | 0.23%   |
| LaCie               | 2         | 12     | 0.23%   |
| Apple               | 2         | 2      | 0.23%   |
| Maxtor              | 1         | 1      | 0.12%   |
| HGST HTS            | 1         | 1      | 0.12%   |
| Hewlett-Packard     | 1         | 2      | 0.12%   |
| FNK TECH            | 1         | 1      | 0.12%   |
| Dyconn H            | 1         | 1      | 0.12%   |
| ASMedia             | 1         | 1      | 0.12%   |
| AFAYA               | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 271       | 480    | 33.25%  |
| Kingston            | 89        | 126    | 10.92%  |
| SanDisk             | 75        | 113    | 9.2%    |
| Crucial             | 68        | 113    | 8.34%   |
| WDC                 | 49        | 69     | 6.01%   |
| Intel               | 38        | 49     | 4.66%   |
| A-DATA Technology   | 24        | 34     | 2.94%   |
| OCZ                 | 15        | 21     | 1.84%   |
| Micron Technology   | 15        | 23     | 1.84%   |
| SK hynix            | 13        | 14     | 1.6%    |
| China               | 13        | 33     | 1.6%    |
| Corsair             | 11        | 18     | 1.35%   |
| Toshiba             | 10        | 12     | 1.23%   |
| GOODRAM             | 10        | 46     | 1.23%   |
| Transcend           | 7         | 12     | 0.86%   |
| PNY                 | 6         | 9      | 0.74%   |
| Plextor             | 6         | 6      | 0.74%   |
| LITEONIT            | 6         | 7      | 0.74%   |
| SPCC                | 5         | 5      | 0.61%   |
| Patriot             | 5         | 9      | 0.61%   |
| Mushkin             | 5         | 5      | 0.61%   |
| Apple               | 5         | 6      | 0.61%   |
| Team                | 4         | 6      | 0.49%   |
| Intenso             | 4         | 5      | 0.49%   |
| Seagate             | 3         | 6      | 0.37%   |
| Dogfish             | 3         | 3      | 0.37%   |
| Apacer              | 3         | 5      | 0.37%   |
| TO Exter            | 2         | 2      | 0.25%   |
| T-FORCE             | 2         | 7      | 0.25%   |
| Smartbuy            | 2         | 2      | 0.25%   |
| Netac               | 2         | 2      | 0.25%   |
| MyDigitalSSD        | 2         | 2      | 0.25%   |
| LITEON              | 2         | 3      | 0.25%   |
| Linux               | 2         | 2      | 0.25%   |
| KingSpec            | 2         | 3      | 0.25%   |
| KingDian            | 2         | 2      | 0.25%   |
| ADROITLARK          | 2         | 3      | 0.25%   |
| Unknown             | 2         | 3      | 0.25%   |
| Zheino              | 1         | 1      | 0.12%   |
| XrayDisk            | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 783       | 1358   | 35.92%  |
| HDD     | 670       | 1874   | 30.73%  |
| SSD     | 665       | 1304   | 30.5%   |
| MMC     | 54        | 79     | 2.48%   |
| Unknown | 8         | 11     | 0.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 987       | 3108   | 52.81%  |
| NVMe | 782       | 1357   | 41.84%  |
| MMC  | 54        | 79     | 2.89%   |
| SAS  | 46        | 82     | 2.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 667       | 1274   | 43.71%  |
| 0.51-1.0   | 440       | 745    | 28.83%  |
| 1.01-2.0   | 192       | 458    | 12.58%  |
| 3.01-4.0   | 97        | 225    | 6.36%   |
| 4.01-10.0  | 60        | 250    | 3.93%   |
| 2.01-3.0   | 54        | 180    | 3.54%   |
| 10.01-20.0 | 15        | 45     | 0.98%   |
| 20.01-50.0 | 1         | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 304       | 19.24%  |
| 101-250        | 283       | 17.91%  |
| 501-1000       | 263       | 16.65%  |
| 1001-2000      | 190       | 12.03%  |
| More than 3000 | 176       | 11.14%  |
| Unknown        | 90        | 5.7%    |
| 2001-3000      | 84        | 5.32%   |
| 51-100         | 80        | 5.06%   |
| 1-20           | 73        | 4.62%   |
| 21-50          | 37        | 2.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 338       | 20.42%  |
| 21-50          | 234       | 14.14%  |
| 101-250        | 234       | 14.14%  |
| 251-500        | 207       | 12.51%  |
| 501-1000       | 159       | 9.61%   |
| 51-100         | 159       | 9.61%   |
| 1001-2000      | 109       | 6.59%   |
| Unknown        | 90        | 5.44%   |
| More than 3000 | 83        | 5.02%   |
| 2001-3000      | 42        | 2.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Computers | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                                  | 7         | 8      | 2.45%   |
| Seagate ST3500418AS 500GB                                 | 6         | 7      | 2.1%    |
| WDC WD40EFRX-68WT0N0 4TB                                  | 4         | 14     | 1.4%    |
| Seagate ST500DM002-1BD142 500GB                           | 4         | 4      | 1.4%    |
| Seagate ST500DM002-1BC142 500GB                           | 4         | 4      | 1.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                        | 4         | 8      | 1.4%    |
| WDC WD30EFRX-68EUZN0 3TB                                  | 3         | 4      | 1.05%   |
| WDC WD30EFRX-68AX9N0 3TB                                  | 3         | 6      | 1.05%   |
| Seagate ST8000AS0002-1NA17Z 8TB                           | 3         | 15     | 1.05%   |
| Samsung Electronics SSD 980 1TB                           | 3         | 3      | 1.05%   |
| Samsung Electronics SSD 850 EVO 1TB                       | 3         | 3      | 1.05%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD                   | 3         | 3      | 1.05%   |
| IBM DJSA-220 12GB                                         | 3         | 3      | 1.05%   |
| WDC WD60EFRX-68MYMN1 6TB                                  | 2         | 5      | 0.7%    |
| WDC WD5000BEVT-22ZAT0 500GB                               | 2         | 2      | 0.7%    |
| WDC WD40EFRX-68N32N0 4TB                                  | 2         | 2      | 0.7%    |
| WDC WD20EZRX-00D8PB0 2TB                                  | 2         | 3      | 0.7%    |
| WDC WD20EFRX-68EUZN0 2TB                                  | 2         | 5      | 0.7%    |
| WDC WD20EARS-00MVWB0 2TB                                  | 2         | 2      | 0.7%    |
| WDC WD2002FAEX-007BA0 2TB                                 | 2         | 2      | 0.7%    |
| WDC WD1600AAJS-75B4A0 160GB                               | 2         | 2      | 0.7%    |
| WDC WD15EARS-00Z5B1 1TB                                   | 2         | 2      | 0.7%    |
| WDC WD10JPVX-75JC3T0 1TB                                  | 2         | 2      | 0.7%    |
| Toshiba DT01ACA200 2TB                                    | 2         | 2      | 0.7%    |
| SK hynix HFS256G39TND-N210A 256GB SSD                     | 2         | 2      | 0.7%    |
| Seagate ST4000DM000-1F2168 4TB                            | 2         | 2      | 0.7%    |
| Seagate ST31000340NS 1TB                                  | 2         | 3      | 0.7%    |
| Seagate ST3000DM001-9YN166 3TB                            | 2         | 3      | 0.7%    |
| Seagate ST2000LX001-1RG174 2TB                            | 2         | 2      | 0.7%    |
| Seagate ST2000DX002-2DV164 2TB                            | 2         | 2      | 0.7%    |
| Seagate ST2000DL003-9VT166 2TB                            | 2         | 3      | 0.7%    |
| Seagate ST1000NM0011 1TB                                  | 2         | 6      | 0.7%    |
| SanDisk SSD PLUS 480GB                                    | 2         | 2      | 0.7%    |
| SanDisk SSD PLUS 1000GB                                   | 2         | 2      | 0.7%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD                       | 2         | 2      | 0.7%    |
| Samsung Electronics SSD 870 EVO 500GB                     | 2         | 3      | 0.7%    |
| Samsung Electronics SSD 840 PRO Series 512GB              | 2         | 4      | 0.7%    |
| Samsung Electronics HD103UJ 1TB                           | 2         | 2      | 0.7%    |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 512GB | 2         | 3      | 0.7%    |
| MDT MD2000KS-00MJB0 200GB                                 | 2         | 2      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 63        | 98     | 23.16%  |
| WDC                         | 61        | 112    | 22.43%  |
| Samsung Electronics         | 30        | 43     | 11.03%  |
| Toshiba                     | 16        | 18     | 5.88%   |
| Hitachi                     | 16        | 32     | 5.88%   |
| HGST                        | 13        | 15     | 4.78%   |
| SanDisk                     | 9         | 11     | 3.31%   |
| Intel                       | 7         | 8      | 2.57%   |
| Crucial                     | 7         | 7      | 2.57%   |
| SK hynix                    | 6         | 7      | 2.21%   |
| Kingston                    | 6         | 6      | 2.21%   |
| IBM                         | 4         | 4      | 1.47%   |
| Fujitsu                     | 4         | 4      | 1.47%   |
| Realtek Semiconductor       | 3         | 7      | 1.1%    |
| OCZ                         | 3         | 3      | 1.1%    |
| PNY                         | 2         | 2      | 0.74%   |
| Plextor                     | 2         | 2      | 0.74%   |
| MDT                         | 2         | 2      | 0.74%   |
| IBM/Hitachi                 | 2         | 2      | 0.74%   |
| Corsair                     | 2         | 5      | 0.74%   |
| China                       | 2         | 3      | 0.74%   |
| A-DATA Technology           | 2         | 2      | 0.74%   |
| Transcend                   | 1         | 1      | 0.37%   |
| SPCC                        | 1         | 1      | 0.37%   |
| Mushkin                     | 1         | 1      | 0.37%   |
| Maxtor                      | 1         | 1      | 0.37%   |
| LITEON                      | 1         | 2      | 0.37%   |
| Kingston Technology Company | 1         | 1      | 0.37%   |
| HGST HTS                    | 1         | 1      | 0.37%   |
| Emtec                       | 1         | 2      | 0.37%   |
| Apple                       | 1         | 1      | 0.37%   |
| 2.5"                        | 1         | 1      | 0.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 98     | 33.69%  |
| WDC                 | 60        | 111    | 32.09%  |
| Hitachi             | 16        | 32     | 8.56%   |
| Toshiba             | 15        | 17     | 8.02%   |
| HGST                | 13        | 15     | 6.95%   |
| Samsung Electronics | 5         | 6      | 2.67%   |
| IBM                 | 4         | 4      | 2.14%   |
| Fujitsu             | 4         | 4      | 2.14%   |
| MDT                 | 2         | 2      | 1.07%   |
| IBM/Hitachi         | 2         | 2      | 1.07%   |
| Maxtor              | 1         | 1      | 0.53%   |
| HGST HTS            | 1         | 1      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 177       | 294    | 67.56%  |
| SSD  | 63        | 79     | 24.05%  |
| NVMe | 22        | 32     | 8.4%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB                 | 2         | 2      | 22.22%  |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 11.11%  |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 2      | 11.11%  |
| Seagate ST3500630AS 500GB                        | 1         | 2      | 11.11%  |
| Seagate ST31500341AS 1TB                         | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 11.11%  |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1         | 2      | 11.11%  |
| Hitachi HTS721010G9SA00 100GB                    | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 3      | 22.22%  |
| Toshiba             | 2         | 2      | 22.22%  |
| Seagate             | 2         | 3      | 22.22%  |
| Samsung Electronics | 2         | 3      | 22.22%  |
| Hitachi             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1263      | 3795   | 73.17%  |
| Malfunc  | 250       | 405    | 14.48%  |
| Detected | 204       | 414    | 11.82%  |
| Failed   | 9         | 12     | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 764       | 35%     |
| AMD                              | 430       | 19.7%   |
| Samsung Electronics              | 359       | 16.45%  |
| SanDisk                          | 125       | 5.73%   |
| ASMedia Technology               | 72        | 3.3%    |
| SK hynix                         | 56        | 2.57%   |
| Phison Electronics               | 56        | 2.57%   |
| Kingston Technology Company      | 43        | 1.97%   |
| Toshiba America Info Systems     | 32        | 1.47%   |
| Marvell Technology Group         | 31        | 1.42%   |
| Nvidia                           | 22        | 1.01%   |
| ADATA Technology                 | 22        | 1.01%   |
| Micron Technology                | 21        | 0.96%   |
| KIOXIA                           | 20        | 0.92%   |
| JMicron Technology               | 18        | 0.82%   |
| Micron/Crucial Technology        | 16        | 0.73%   |
| Silicon Motion                   | 14        | 0.64%   |
| Broadcom / LSI                   | 14        | 0.64%   |
| LSI Logic / Symbios Logic        | 12        | 0.55%   |
| Realtek Semiconductor            | 8         | 0.37%   |
| Seagate Technology               | 6         | 0.27%   |
| Adaptec                          | 6         | 0.27%   |
| Silicon Image                    | 5         | 0.23%   |
| Solid State Storage Technology   | 4         | 0.18%   |
| Silicon Integrated Systems [SiS] | 3         | 0.14%   |
| Lite-On Technology               | 3         | 0.14%   |
| INNOGRIT                         | 3         | 0.14%   |
| VIA Technologies                 | 2         | 0.09%   |
| Union Memory (Shenzhen)          | 2         | 0.09%   |
| Lenovo                           | 2         | 0.09%   |
| Hewlett-Packard                  | 2         | 0.09%   |
| Apple                            | 2         | 0.09%   |
| 3ware                            | 2         | 0.09%   |
| Yangtze Memory Technologies      | 1         | 0.05%   |
| OCZ Technology Group             | 1         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.05%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.05%   |
| Integrated Technology Express    | 1         | 0.05%   |
| Broadcom                         | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 330       | 13.28%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 217       | 8.73%   |
| AMD 400 Series Chipset SATA Controller                                         | 95        | 3.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 68        | 2.74%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 64        | 2.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 55        | 2.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 50        | 2.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 47        | 1.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 46        | 1.85%   |
| Samsung NVMe SSD Controller 980                                                | 44        | 1.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 41        | 1.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 41        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 39        | 1.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 38        | 1.53%   |
| Intel SSD 660P Series                                                          | 34        | 1.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 34        | 1.37%   |
| Intel Volume Management Device NVMe RAID Controller                            | 32        | 1.29%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 29        | 1.17%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 28        | 1.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 28        | 1.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 27        | 1.09%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 26        | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 23        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 22        | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 22        | 0.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 22        | 0.89%   |
| Micron NVMe Storage Controller                                                 | 20        | 0.8%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 20        | 0.8%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 20        | 0.8%    |
| Phison E12 NVMe Controller                                                     | 19        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 19        | 0.76%   |
| AMD X370 Series Chipset SATA Controller                                        | 19        | 0.76%   |
| Phison E16 PCIe4 NVMe Controller                                               | 18        | 0.72%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 17        | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 16        | 0.64%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 15        | 0.6%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 15        | 0.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 15        | 0.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 0.6%    |
| Intel SATA Controller [RAID mode]                                              | 14        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1053      | 50.21%  |
| NVMe | 789       | 37.63%  |
| IDE  | 120       | 5.72%   |
| RAID | 104       | 4.96%   |
| SAS  | 24        | 1.14%   |
| SCSI | 7         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 895       | 61.43%  |
| AMD                      | 532       | 36.51%  |
| ARM                      | 17        | 1.17%   |
| Marvell Semiconductor    | 3         | 0.21%   |
| thead,c906               | 1         | 0.07%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.07%   |
| PowerMac8,1              | 1         | 0.07%   |
| PowerMac3,6              | 1         | 0.07%   |
| PowerMac10,2             | 1         | 0.07%   |
| PowerBook6,7             | 1         | 0.07%   |
| PowerBook5,6             | 1         | 0.07%   |
| PowerBook5,5             | 1         | 0.07%   |
| PowerBook5,4             | 1         | 0.07%   |
| PowerBook3,4             | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor            | 29        | 1.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 24        | 1.63%   |
| AMD Ryzen 5 3600 6-Core Processor             | 20        | 1.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 19        | 1.29%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 19        | 1.29%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 18        | 1.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.16%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 17        | 1.16%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 17        | 1.16%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 1.09%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 16        | 1.09%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 15        | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 0.95%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 14        | 0.95%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 0.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 0.88%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 13        | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 12        | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.82%   |
| ARM Processor                                 | 12        | 0.82%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 0.82%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 12        | 0.82%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 12        | 0.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 0.75%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 0.75%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 10        | 0.68%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 10        | 0.68%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.68%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 10        | 0.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.61%   |
| Intel 12th Gen Core i7-12700H                 | 9         | 0.61%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 9         | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 9         | 0.61%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 8         | 0.54%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 8         | 0.54%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 8         | 0.54%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 336       | 22.94%  |
| Intel Core i5          | 200       | 13.65%  |
| AMD Ryzen 7            | 173       | 11.81%  |
| Other                  | 134       | 9.15%   |
| AMD Ryzen 5            | 126       | 8.6%    |
| AMD Ryzen 9            | 92        | 6.28%   |
| Intel Xeon             | 71        | 4.85%   |
| AMD Ryzen 7 PRO        | 27        | 1.84%   |
| Intel Atom             | 26        | 1.77%   |
| Intel Celeron          | 25        | 1.71%   |
| Intel Core i9          | 24        | 1.64%   |
| AMD FX                 | 22        | 1.5%    |
| Intel Core i3          | 21        | 1.43%   |
| Intel Core 2 Duo       | 21        | 1.43%   |
| Intel Pentium          | 18        | 1.23%   |
| AMD Ryzen 3            | 16        | 1.09%   |
| Intel Core 2 Quad      | 10        | 0.68%   |
| AMD Phenom II X4       | 10        | 0.68%   |
| Intel Pentium M        | 9         | 0.61%   |
| AMD Ryzen Threadripper | 9         | 0.61%   |
| Intel Pentium 4        | 8         | 0.55%   |
| AMD Ryzen 5 PRO        | 8         | 0.55%   |
| AMD Phenom II X6       | 6         | 0.41%   |
| AMD A6                 | 6         | 0.41%   |
| AMD A10                | 5         | 0.34%   |
| Intel Pentium Silver   | 4         | 0.27%   |
| Intel Pentium III      | 4         | 0.27%   |
| ARM BCM                | 4         | 0.27%   |
| AMD Sempron            | 4         | 0.27%   |
| AMD EPYC               | 4         | 0.27%   |
| AMD Athlon             | 4         | 0.27%   |
| Intel Core m3          | 3         | 0.2%    |
| Intel Core 2           | 3         | 0.2%    |
| AMD E                  | 3         | 0.2%    |
| AMD Athlon II X3       | 3         | 0.2%    |
| AMD Athlon 64 X2       | 3         | 0.2%    |
| AMD A8                 | 3         | 0.2%    |
| Intel Genuine          | 2         | 0.14%   |
| Intel Core Duo         | 2         | 0.14%   |
| AMD E1                 | 2         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 496       | 33.83%  |
| 8       | 274       | 18.69%  |
| 6       | 240       | 16.37%  |
| 2       | 233       | 15.89%  |
| 12      | 70        | 4.77%   |
| 16      | 52        | 3.55%   |
| 1       | 47        | 3.21%   |
| 14      | 14        | 0.95%   |
| Unknown | 11        | 0.75%   |
| 10      | 8         | 0.55%   |
| 3       | 7         | 0.48%   |
| 32      | 4         | 0.27%   |
| 28      | 2         | 0.14%   |
| 24      | 2         | 0.14%   |
| 20      | 2         | 0.14%   |
| 64      | 1         | 0.07%   |
| 44      | 1         | 0.07%   |
| 22      | 1         | 0.07%   |
| 18      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1420      | 97.33%  |
| 2       | 29        | 1.99%   |
| Unknown | 10        | 0.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1153      | 78.65%  |
| 1       | 301       | 20.53%  |
| Unknown | 11        | 0.75%   |
| 4       | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1407      | 96.57%  |
| 32-bit         | 35        | 2.4%    |
| Unknown        | 15        | 1.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 247       | 16.19%  |
| 0x906ea    | 70        | 4.59%   |
| 0x08701021 | 61        | 4%      |
| 0x506e3    | 54        | 3.54%   |
| 0x306c3    | 46        | 3.01%   |
| 0x306a9    | 46        | 3.01%   |
| 0x806ec    | 41        | 2.69%   |
| 0x0800820d | 40        | 2.62%   |
| 0x906e9    | 39        | 2.56%   |
| 0x0a50000c | 38        | 2.49%   |
| 0x806ea    | 36        | 2.36%   |
| 0x806c1    | 36        | 2.36%   |
| 0x08701013 | 35        | 2.29%   |
| 0x206a7    | 34        | 2.23%   |
| 0x08600106 | 31        | 2.03%   |
| 0x0a201016 | 28        | 1.83%   |
| 0x806e9    | 27        | 1.77%   |
| 0x906ed    | 23        | 1.51%   |
| 0x0a201009 | 20        | 1.31%   |
| 0x08108109 | 20        | 1.31%   |
| 0x08001138 | 20        | 1.31%   |
| 0xa0652    | 18        | 1.18%   |
| 0x806d1    | 17        | 1.11%   |
| 0x40651    | 17        | 1.11%   |
| 0x1067a    | 17        | 1.11%   |
| 0x0a601203 | 17        | 1.11%   |
| 0x906a3    | 16        | 1.05%   |
| 0x406e3    | 15        | 0.98%   |
| 0x08600103 | 14        | 0.92%   |
| 0x206c2    | 13        | 0.85%   |
| 0x306f2    | 12        | 0.79%   |
| 0x306d4    | 12        | 0.79%   |
| 0x0a20120a | 12        | 0.79%   |
| 0xa0671    | 11        | 0.72%   |
| 0x90672    | 11        | 0.72%   |
| 0x08608103 | 11        | 0.72%   |
| 0x08108102 | 11        | 0.72%   |
| 0xa0655    | 10        | 0.66%   |
| 0x306e4    | 10        | 0.66%   |
| 0x08600104 | 10        | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 282       | 19.21%  |
| Zen 2            | 175       | 11.92%  |
| Zen 3            | 117       | 7.97%   |
| Unknown          | 90        | 6.13%   |
| Haswell          | 89        | 6.06%   |
| Zen+             | 83        | 5.65%   |
| Skylake          | 79        | 5.38%   |
| IvyBridge        | 62        | 4.22%   |
| SandyBridge      | 48        | 3.27%   |
| Zen              | 41        | 2.79%   |
| TigerLake        | 41        | 2.79%   |
| CometLake        | 38        | 2.59%   |
| IceLake          | 37        | 2.52%   |
| Alderlake Hybrid | 36        | 2.45%   |
| Broadwell        | 27        | 1.84%   |
| Westmere         | 23        | 1.57%   |
| Penryn           | 23        | 1.57%   |
| Silvermont       | 22        | 1.5%    |
| K10              | 22        | 1.5%    |
| Piledriver       | 20        | 1.36%   |
| P6               | 18        | 1.23%   |
| Bonnell          | 17        | 1.16%   |
| Core             | 14        | 0.95%   |
| Nehalem          | 9         | 0.61%   |
| Goldmont plus    | 9         | 0.61%   |
| NetBurst         | 8         | 0.54%   |
| K8 Hammer        | 7         | 0.48%   |
| Steamroller      | 5         | 0.34%   |
| Bulldozer        | 5         | 0.34%   |
| Bobcat           | 5         | 0.34%   |
| Jaguar           | 4         | 0.27%   |
| Goldmont         | 4         | 0.27%   |
| Excavator        | 3         | 0.2%    |
| Puma             | 2         | 0.14%   |
| K10 Llano        | 2         | 0.14%   |
| Tremont          | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 607       | 35.05%  |
| Nvidia                           | 572       | 33.03%  |
| AMD                              | 508       | 29.33%  |
| ASPEED Technology                | 28        | 1.62%   |
| Matrox Electronics Systems       | 16        | 0.92%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 82        | 4.54%   |
| AMD Renoir                                                                  | 61        | 3.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 59        | 3.26%   |
| Intel UHD Graphics 620                                                      | 43        | 2.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 39        | 2.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 38        | 2.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 37        | 2.05%   |
| Intel HD Graphics 530                                                       | 34        | 1.88%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 34        | 1.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 31        | 1.71%   |
| ASPEED Technology ASPEED Graphics Family                                    | 28        | 1.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 26        | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 25        | 1.38%   |
| Intel HD Graphics 620                                                       | 22        | 1.22%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 22        | 1.22%   |
| Intel HD Graphics 630                                                       | 20        | 1.11%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 20        | 1.11%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 20        | 1.11%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 19        | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 18        | 1%      |
| Intel Haswell-ULT Integrated Graphics Controller                            | 18        | 1%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 17        | 0.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 16        | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 15        | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 15        | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 15        | 0.83%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 15        | 0.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 15        | 0.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 15        | 0.83%   |
| AMD Raphael                                                                 | 15        | 0.83%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 13        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 13        | 0.72%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 13        | 0.72%   |
| AMD Lucienne                                                                | 13        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 12        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 12        | 0.66%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 12        | 0.66%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 12        | 0.66%   |
| Intel HD Graphics 5500                                                      | 12        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 12        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x AMD                  | 408       | 27.53%  |
| 1 x Intel                | 360       | 24.29%  |
| 1 x Nvidia               | 321       | 21.66%  |
| Intel + Nvidia           | 202       | 13.63%  |
| AMD + Nvidia             | 45        | 3.04%   |
| 2 x AMD                  | 33        | 2.23%   |
| Other                    | 25        | 1.69%   |
| 1 x ASPEED               | 25        | 1.69%   |
| Intel + AMD              | 22        | 1.48%   |
| 1 x Matrox               | 14        | 0.94%   |
| 2 x Intel                | 12        | 0.81%   |
| 2 x Nvidia               | 7         | 0.47%   |
| AMD + ASPEED             | 2         | 0.13%   |
| 1 x SiS                  | 1         | 0.07%   |
| Nvidia + Matrox          | 1         | 0.07%   |
| Nvidia + ASPEED          | 1         | 0.07%   |
| Intel + 2 x Nvidia       | 1         | 0.07%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.07%   |
| AMD + Matrox             | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1029      | 68.69%  |
| Proprietary | 353       | 23.56%  |
| Unknown     | 116       | 7.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 697       | 45.73%  |
| 7.01-8.0   | 174       | 11.42%  |
| 0.01-0.5   | 153       | 10.04%  |
| 1.01-2.0   | 140       | 9.19%   |
| 3.01-4.0   | 127       | 8.33%   |
| 0.51-1.0   | 76        | 4.99%   |
| 8.01-16.0  | 71        | 4.66%   |
| 5.01-6.0   | 59        | 3.87%   |
| 2.01-3.0   | 16        | 1.05%   |
| 16.01-24.0 | 9         | 0.59%   |
| 4.01-5.0   | 2         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 177       | 10.68%  |
| AU Optronics            | 148       | 8.93%   |
| Dell                    | 138       | 8.33%   |
| BOE                     | 125       | 7.54%   |
| LG Display              | 110       | 6.64%   |
| Chimei Innolux          | 98        | 5.91%   |
| Goldstar                | 81        | 4.89%   |
| AOC                     | 57        | 3.44%   |
| Ancor Communications    | 57        | 3.44%   |
| Sharp                   | 55        | 3.32%   |
| Hewlett-Packard         | 55        | 3.32%   |
| BenQ                    | 54        | 3.26%   |
| Acer                    | 50        | 3.02%   |
| ASUSTek Computer        | 38        | 2.29%   |
| Lenovo                  | 36        | 2.17%   |
| Iiyama                  | 35        | 2.11%   |
| ViewSonic               | 32        | 1.93%   |
| Philips                 | 31        | 1.87%   |
| Apple                   | 29        | 1.75%   |
| Eizo                    | 18        | 1.09%   |
| Chi Mei Optoelectronics | 16        | 0.97%   |
| PANDA                   | 12        | 0.72%   |
| LG Electronics          | 12        | 0.72%   |
| Unknown                 | 11        | 0.66%   |
| Gigabyte Technology     | 10        | 0.6%    |
| CSO                     | 10        | 0.6%    |
| Fujitsu Siemens         | 9         | 0.54%   |
| MSI                     | 8         | 0.48%   |
| Unknown                 | 7         | 0.42%   |
| Sony                    | 6         | 0.36%   |
| NEC Computers           | 6         | 0.36%   |
| InfoVision              | 6         | 0.36%   |
| Idek Iiyama             | 6         | 0.36%   |
| HannStar                | 6         | 0.36%   |
| Sceptre Tech            | 5         | 0.3%    |
| Panasonic               | 4         | 0.24%   |
| Envision Peripherals    | 4         | 0.24%   |
| Toshiba                 | 3         | 0.18%   |
| TMX                     | 3         | 0.18%   |
| RTK                     | 3         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 9         | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 9         | 0.51%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 8         | 0.46%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                | 8         | 0.46%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 7         | 0.4%    |
| Unknown                                                              | 7         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch    | 6         | 0.34%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                | 6         | 0.34%   |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 518x324mm 24.1-inch     | 6         | 0.34%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 6         | 0.34%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 6         | 0.34%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 5         | 0.28%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 5         | 0.28%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 5         | 0.28%   |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                    | 5         | 0.28%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                    | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch     | 5         | 0.28%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                   | 5         | 0.28%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 5         | 0.28%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 4         | 0.23%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch      | 4         | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 4         | 0.23%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 4         | 0.23%   |
| Hewlett-Packard 22es HWP331B 1920x1080 476x268mm 21.5-inch           | 4         | 0.23%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 4         | 0.23%   |
| Envision Peripherals LCD2361 ENV2361 1920x1080 521x293mm 23.5-inch   | 4         | 0.23%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                | 4         | 0.23%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch         | 4         | 0.23%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                     | 4         | 0.23%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch     | 4         | 0.23%   |
| Acer T232HL ACR041F 1920x1080 509x286mm 23.0-inch                    | 4         | 0.23%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch              | 3         | 0.17%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 3         | 0.17%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch              | 3         | 0.17%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch              | 3         | 0.17%   |
| Sharp LCD Monitor SHP14D6 3840x2400 370x230mm 17.2-inch              | 3         | 0.17%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch              | 3         | 0.17%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 610x350mm 27.7-inch    | 3         | 0.17%   |
| Samsung Electronics SyncMaster SAM0584 2048x1152 510x287mm 23.0-inch | 3         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 739       | 46.77%  |
| 2560x1440 (QHD)    | 152       | 9.62%   |
| 3840x2160 (4K)     | 149       | 9.43%   |
| 1366x768 (WXGA)    | 87        | 5.51%   |
| 1920x1200 (WUXGA)  | 49        | 3.1%    |
| 1680x1050 (WSXGA+) | 40        | 2.53%   |
| 1280x1024 (SXGA)   | 40        | 2.53%   |
| 3440x1440          | 38        | 2.41%   |
| 1600x900 (HD+)     | 32        | 2.03%   |
| Unknown            | 32        | 2.03%   |
| 2560x1600          | 23        | 1.46%   |
| 1440x900 (WXGA+)   | 23        | 1.46%   |
| 2560x1080          | 19        | 1.2%    |
| 3840x2400          | 18        | 1.14%   |
| 3840x1080          | 17        | 1.08%   |
| 1280x800 (WXGA)    | 12        | 0.76%   |
| 1024x600           | 8         | 0.51%   |
| 2880x1800          | 6         | 0.38%   |
| 1600x1200          | 6         | 0.38%   |
| 3840x1200          | 5         | 0.32%   |
| 2160x1440          | 5         | 0.32%   |
| 3200x1800 (QHD+)   | 4         | 0.25%   |
| 2288x1287          | 4         | 0.25%   |
| 2048x1152          | 4         | 0.25%   |
| 1360x768           | 4         | 0.25%   |
| 1024x768 (XGA)     | 4         | 0.25%   |
| 7680x2160          | 3         | 0.19%   |
| 3456x2160          | 3         | 0.19%   |
| 3200x2000          | 3         | 0.19%   |
| 2256x1504          | 3         | 0.19%   |
| 2160x1200          | 3         | 0.19%   |
| 1920x540           | 3         | 0.19%   |
| 1280x960           | 3         | 0.19%   |
| 1280x854           | 3         | 0.19%   |
| 800x1280           | 2         | 0.13%   |
| 2240x1400          | 2         | 0.13%   |
| 1920x1280          | 2         | 0.13%   |
| 1400x1050          | 2         | 0.13%   |
| 1280x720 (HD)      | 2         | 0.13%   |
| 6720x2160          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 302       | 18.39%  |
| 27      | 219       | 13.34%  |
| 24      | 150       | 9.14%   |
| 23      | 134       | 8.16%   |
| 13      | 129       | 7.86%   |
| 14      | 103       | 6.27%   |
| Unknown | 99        | 6.03%   |
| 17      | 87        | 5.3%    |
| 21      | 86        | 5.24%   |
| 34      | 48        | 2.92%   |
| 19      | 38        | 2.31%   |
| 12      | 31        | 1.89%   |
| 31      | 27        | 1.64%   |
| 22      | 27        | 1.64%   |
| 16      | 20        | 1.22%   |
| 25      | 16        | 0.97%   |
| 11      | 13        | 0.79%   |
| 20      | 12        | 0.73%   |
| 84      | 11        | 0.67%   |
| 32      | 11        | 0.67%   |
| 18      | 9         | 0.55%   |
| 10      | 7         | 0.43%   |
| 48      | 6         | 0.37%   |
| 26      | 6         | 0.37%   |
| 72      | 5         | 0.3%    |
| 54      | 5         | 0.3%    |
| 40      | 5         | 0.3%    |
| 29      | 5         | 0.3%    |
| 142     | 4         | 0.24%   |
| 49      | 4         | 0.24%   |
| 8       | 3         | 0.18%   |
| 58      | 2         | 0.12%   |
| 47      | 2         | 0.12%   |
| 43      | 2         | 0.12%   |
| 28      | 2         | 0.12%   |
| 75      | 1         | 0.06%   |
| 65      | 1         | 0.06%   |
| 52      | 1         | 0.06%   |
| 50      | 1         | 0.06%   |
| 42      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 487       | 30.74%  |
| 501-600        | 440       | 27.78%  |
| 401-500        | 151       | 9.53%   |
| 201-300        | 127       | 8.02%   |
| Unknown        | 99        | 6.25%   |
| 351-400        | 96        | 6.06%   |
| 601-700        | 65        | 4.1%    |
| 701-800        | 60        | 3.79%   |
| 1001-1500      | 23        | 1.45%   |
| 1501-2000      | 17        | 1.07%   |
| 801-900        | 7         | 0.44%   |
| More than 2000 | 4         | 0.25%   |
| 101-200        | 3         | 0.19%   |
| 901-1000       | 3         | 0.19%   |
| 1-100          | 2         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1020      | 70.78%  |
| 16/10   | 189       | 13.12%  |
| Unknown | 83        | 5.76%   |
| 21/9    | 52        | 3.61%   |
| 5/4     | 38        | 2.64%   |
| 3/2     | 21        | 1.46%   |
| 4/3     | 14        | 0.97%   |
| 32/9    | 11        | 0.76%   |
| 1.00    | 5         | 0.35%   |
| 6/5     | 3         | 0.21%   |
| 3.40    | 1         | 0.07%   |
| 3.20    | 1         | 0.07%   |
| 0.67    | 1         | 0.07%   |
| 0.62    | 1         | 0.07%   |
| 0.31    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 301       | 18.59%  |
| 201-250        | 296       | 18.28%  |
| 301-350        | 223       | 13.77%  |
| 81-90          | 166       | 10.25%  |
| Unknown        | 99        | 6.11%   |
| 351-500        | 90        | 5.56%   |
| 251-300        | 78        | 4.82%   |
| 151-200        | 72        | 4.45%   |
| 71-80          | 65        | 4.01%   |
| 121-130        | 58        | 3.58%   |
| More than 1000 | 33        | 2.04%   |
| 61-70          | 28        | 1.73%   |
| 141-150        | 28        | 1.73%   |
| 111-120        | 21        | 1.3%    |
| 501-1000       | 20        | 1.24%   |
| 51-60          | 15        | 0.93%   |
| 131-140        | 9         | 0.56%   |
| 41-50          | 6         | 0.37%   |
| 91-100         | 6         | 0.37%   |
| 1-40           | 5         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 487       | 31.38%  |
| 121-160       | 443       | 28.54%  |
| 101-120       | 294       | 18.94%  |
| 161-240       | 133       | 8.57%   |
| Unknown       | 99        | 6.38%   |
| More than 240 | 71        | 4.57%   |
| 1-50          | 25        | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1033      | 67.83%  |
| 2     | 287       | 18.84%  |
| 0     | 139       | 9.13%   |
| 3     | 55        | 3.61%   |
| 4     | 9         | 0.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 911       | 42.81%  |
| Realtek Semiconductor             | 687       | 32.28%  |
| Qualcomm Atheros                  | 141       | 6.63%   |
| Broadcom                          | 88        | 4.14%   |
| MediaTek                          | 37        | 1.74%   |
| Aquantia                          | 21        | 0.99%   |
| ASIX Electronics                  | 20        | 0.94%   |
| Nvidia                            | 18        | 0.85%   |
| Marvell Technology Group          | 17        | 0.8%    |
| Lenovo                            | 13        | 0.61%   |
| Qualcomm                          | 10        | 0.47%   |
| Apple                             | 10        | 0.47%   |
| TP-Link                           | 9         | 0.42%   |
| Dell                              | 9         | 0.42%   |
| Broadcom Limited                  | 9         | 0.42%   |
| Qualcomm Atheros Communications   | 8         | 0.38%   |
| Microsoft                         | 8         | 0.38%   |
| Sierra Wireless                   | 7         | 0.33%   |
| Xiaomi                            | 6         | 0.28%   |
| Ralink                            | 6         | 0.28%   |
| Ralink Technology                 | 5         | 0.23%   |
| Fibocom                           | 5         | 0.23%   |
| Ericsson Business Mobile Networks | 5         | 0.23%   |
| Samsung Electronics               | 4         | 0.19%   |
| D-Link System                     | 4         | 0.19%   |
| Standard Microsystems             | 3         | 0.14%   |
| NetGear                           | 3         | 0.14%   |
| Microchip Technology              | 3         | 0.14%   |
| ICS Advent                        | 3         | 0.14%   |
| Huawei Technologies               | 3         | 0.14%   |
| D-Link                            | 3         | 0.14%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.09%   |
| STMicroelectronics                | 2         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.09%   |
| Sigma Designs                     | 2         | 0.09%   |
| QLogic                            | 2         | 0.09%   |
| OpenMoko                          | 2         | 0.09%   |
| Netchip Technology                | 2         | 0.09%   |
| Metrologic Instruments            | 2         | 0.09%   |
| Google                            | 2         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 498       | 19.36%  |
| Intel Wi-Fi 6 AX200                                               | 153       | 5.95%   |
| Intel I211 Gigabit Network Connection                             | 113       | 4.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 67        | 2.6%    |
| Intel Wireless 8265 / 8275                                        | 61        | 2.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54        | 2.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 45        | 1.75%   |
| Intel Ethernet Controller I225-V                                  | 42        | 1.63%   |
| Intel I210 Gigabit Network Connection                             | 36        | 1.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 35        | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.21%   |
| Intel Wi-Fi 6 AX201                                               | 31        | 1.21%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 1.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 1.17%   |
| Intel Wireless-AC 9260                                            | 29        | 1.13%   |
| Intel Wireless 8260                                               | 27        | 1.05%   |
| Intel Wireless 7265                                               | 27        | 1.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 25        | 0.97%   |
| Intel 82574L Gigabit Network Connection                           | 25        | 0.97%   |
| Intel Ethernet Connection (7) I219-V                              | 24        | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.93%   |
| Intel Wireless 7260                                               | 23        | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 22        | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 20        | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 19        | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 17        | 0.66%   |
| Intel Wireless 3165                                               | 17        | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 17        | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 15        | 0.58%   |
| Intel I350 Gigabit Network Connection                             | 15        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 15        | 0.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 0.54%   |
| Intel Ethernet Connection (2) I218-V                              | 13        | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 12        | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 12        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 648       | 61.71%  |
| Realtek Semiconductor                 | 118       | 11.24%  |
| Qualcomm Atheros                      | 107       | 10.19%  |
| Broadcom                              | 58        | 5.52%   |
| MediaTek                              | 35        | 3.33%   |
| Qualcomm                              | 10        | 0.95%   |
| Qualcomm Atheros Communications       | 8         | 0.76%   |
| Microsoft                             | 8         | 0.76%   |
| Sierra Wireless                       | 7         | 0.67%   |
| Dell                                  | 7         | 0.67%   |
| TP-Link                               | 6         | 0.57%   |
| Ralink                                | 6         | 0.57%   |
| Broadcom Limited                      | 6         | 0.57%   |
| Ralink Technology                     | 5         | 0.48%   |
| Fibocom                               | 5         | 0.48%   |
| NetGear                               | 3         | 0.29%   |
| D-Link System                         | 3         | 0.29%   |
| D-Link                                | 3         | 0.29%   |
| Texas Instruments                     | 1         | 0.1%    |
| Senao                                 | 1         | 0.1%    |
| Quectel Wireless Solutions            | 1         | 0.1%    |
| Edimax Technology                     | 1         | 0.1%    |
| Cisco Aironet Wireless Communications | 1         | 0.1%    |
| BUFFALO                               | 1         | 0.1%    |
| AVM                                   | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 153       | 14.5%   |
| Intel Wireless 8265 / 8275                                              | 61        | 5.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 45        | 4.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 35        | 3.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 31        | 2.94%   |
| Intel Wi-Fi 6 AX201                                                     | 31        | 2.94%   |
| Intel Wireless-AC 9260                                                  | 29        | 2.75%   |
| Intel Wireless 8260                                                     | 27        | 2.56%   |
| Intel Wireless 7265                                                     | 27        | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 25        | 2.37%   |
| Intel Wireless 7260                                                     | 23        | 2.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 22        | 2.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.9%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 20        | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 20        | 1.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 19        | 1.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 17        | 1.61%   |
| Intel Wireless 3165                                                     | 17        | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 15        | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 15        | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 12        | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.14%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 12        | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 1.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 11        | 1.04%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10        | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 9         | 0.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 9         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.76%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.66%   |
| Qualcomm Atheros AR9271 802.11n                                         | 7         | 0.66%   |
| Intel Wireless 3160                                                     | 7         | 0.66%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 7         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 647       | 46.41%  |
| Intel                            | 516       | 37.02%  |
| Qualcomm Atheros                 | 47        | 3.37%   |
| Broadcom                         | 40        | 2.87%   |
| Aquantia                         | 21        | 1.51%   |
| ASIX Electronics                 | 20        | 1.43%   |
| Nvidia                           | 18        | 1.29%   |
| Marvell Technology Group         | 17        | 1.22%   |
| Lenovo                           | 13        | 0.93%   |
| Apple                            | 10        | 0.72%   |
| Xiaomi                           | 6         | 0.43%   |
| TP-Link                          | 3         | 0.22%   |
| Standard Microsystems            | 3         | 0.22%   |
| Microchip Technology             | 3         | 0.22%   |
| ICS Advent                       | 3         | 0.22%   |
| Broadcom Limited                 | 3         | 0.22%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.14%   |
| Silicon Integrated Systems [SiS] | 2         | 0.14%   |
| Samsung Electronics              | 2         | 0.14%   |
| QLogic                           | 2         | 0.14%   |
| Google                           | 2         | 0.14%   |
| DisplayLink                      | 2         | 0.14%   |
| 3Com                             | 2         | 0.14%   |
| NetXen Incorporated              | 1         | 0.07%   |
| MediaTek                         | 1         | 0.07%   |
| JMicron Technology               | 1         | 0.07%   |
| Insyde Software                  | 1         | 0.07%   |
| Huawei Technologies              | 1         | 0.07%   |
| Hewlett-Packard                  | 1         | 0.07%   |
| Gemtek                           | 1         | 0.07%   |
| Davicom Semiconductor            | 1         | 0.07%   |
| D-Link System                    | 1         | 0.07%   |
| American Megatrends              | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 498       | 33.92%  |
| Intel I211 Gigabit Network Connection                                         | 113       | 7.7%    |
| Realtek RTL8125 2.5GbE Controller                                             | 67        | 4.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 54        | 3.68%   |
| Intel Ethernet Controller I225-V                                              | 42        | 2.86%   |
| Intel I210 Gigabit Network Connection                                         | 36        | 2.45%   |
| Intel Ethernet Connection (2) I219-V                                          | 30        | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 30        | 2.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 26        | 1.77%   |
| Intel 82574L Gigabit Network Connection                                       | 25        | 1.7%    |
| Intel Ethernet Connection (7) I219-V                                          | 24        | 1.63%   |
| Intel Ethernet Connection (2) I219-LM                                         | 24        | 1.63%   |
| Intel Ethernet Connection (4) I219-LM                                         | 19        | 1.29%   |
| Intel I350 Gigabit Network Connection                                         | 15        | 1.02%   |
| Intel Ethernet Connection (2) I218-V                                          | 13        | 0.89%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 12        | 0.82%   |
| Intel Ethernet Connection (4) I219-V                                          | 12        | 0.82%   |
| Intel Ethernet Connection I217-LM                                             | 11        | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                         | 10        | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                          | 10        | 0.68%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 10        | 0.68%   |
| Intel 82579V Gigabit Network Connection                                       | 9         | 0.61%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 9         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 8         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 7         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7         | 0.48%   |
| Nvidia MCP77 Ethernet                                                         | 7         | 0.48%   |
| Intel Ethernet Connection I218-LM                                             | 7         | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                                         | 7         | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 7         | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 7         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 6         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6         | 0.41%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 6         | 0.41%   |
| Intel Ethernet Connection I219-LM                                             | 6         | 0.41%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 0.41%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 6         | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 5         | 0.34%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 5         | 0.34%   |
| Nvidia MCP79 Ethernet                                                         | 5         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1269      | 54.86%  |
| WiFi     | 997       | 43.1%   |
| Modem    | 45        | 1.95%   |
| Unknown  | 2         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 838       | 54.91%  |
| WiFi     | 688       | 45.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 737       | 49.97%  |
| 1     | 583       | 39.53%  |
| 3     | 86        | 5.83%   |
| 0     | 27        | 1.83%   |
| 4     | 22        | 1.49%   |
| 6     | 7         | 0.47%   |
| 5     | 7         | 0.47%   |
| 8     | 2         | 0.14%   |
| 7     | 2         | 0.14%   |
| 12    | 1         | 0.07%   |
| 9     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1247      | 83.02%  |
| Yes  | 255       | 16.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 581       | 61.55%  |
| Realtek Semiconductor           | 74        | 7.84%   |
| Cambridge Silicon Radio         | 56        | 5.93%   |
| Apple                           | 33        | 3.5%    |
| IMC Networks                    | 27        | 2.86%   |
| Qualcomm Atheros Communications | 26        | 2.75%   |
| Foxconn / Hon Hai               | 24        | 2.54%   |
| Broadcom                        | 24        | 2.54%   |
| Lite-On Technology              | 22        | 2.33%   |
| ASUSTek Computer                | 21        | 2.22%   |
| MediaTek                        | 11        | 1.17%   |
| Realtek                         | 8         | 0.85%   |
| Dell                            | 8         | 0.85%   |
| Toshiba                         | 5         | 0.53%   |
| USI                             | 4         | 0.42%   |
| Hewlett-Packard                 | 4         | 0.42%   |
| HTC (High Tech Computer)        | 3         | 0.32%   |
| Belkin Components               | 3         | 0.32%   |
| Foxconn International           | 2         | 0.21%   |
| Ralink Technology               | 1         | 0.11%   |
| Opticis                         | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| Dynex                           | 1         | 0.11%   |
| Chicony Electronics             | 1         | 0.11%   |
| Askey Computer                  | 1         | 0.11%   |
| Alps Electric                   | 1         | 0.11%   |
| Actiontec Electronics           | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 156       | 16.51%  |
| Intel AX200 Bluetooth                                                | 154       | 16.3%   |
| Intel AX201 Bluetooth                                                | 89        | 9.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 77        | 8.15%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 56        | 5.93%   |
| Realtek Bluetooth Radio                                              | 48        | 5.08%   |
| Intel AX210 Bluetooth                                                | 32        | 3.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 30        | 3.17%   |
| Intel Bluetooth Device                                               | 21        | 2.22%   |
| Apple Bluetooth Host Controller                                      | 17        | 1.8%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 15        | 1.59%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 14        | 1.48%   |
| IMC Networks Wireless_Device                                         | 12        | 1.27%   |
| MediaTek Wireless_Device                                             | 11        | 1.16%   |
| IMC Networks Bluetooth Radio                                         | 10        | 1.06%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 9         | 0.95%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 9         | 0.95%   |
| Realtek Bluetooth Radio                                              | 8         | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 8         | 0.85%   |
| Qualcomm Atheros  Bluetooth Device                                   | 7         | 0.74%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 7         | 0.74%   |
| Lite-On Bluetooth Device                                             | 7         | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 7         | 0.74%   |
| Foxconn / Hon Hai Wireless_Device                                    | 6         | 0.63%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 6         | 0.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 6         | 0.63%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 5         | 0.53%   |
| Realtek RTL8723B Bluetooth                                           | 5         | 0.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 5         | 0.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5         | 0.53%   |
| USI Bluetooth Device                                                 | 4         | 0.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 4         | 0.42%   |
| IMC Networks Bluetooth Device                                        | 4         | 0.42%   |
| Broadcom HP Portable SoftSailing                                     | 4         | 0.42%   |
| Apple Bluetooth USB Host Controller                                  | 4         | 0.42%   |
| Apple Bluetooth HCI                                                  | 4         | 0.42%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 3         | 0.32%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 3         | 0.32%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3         | 0.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 3         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 801       | 35.49%  |
| AMD                                  | 586       | 25.96%  |
| Nvidia                               | 448       | 19.85%  |
| C-Media Electronics                  | 55        | 2.44%   |
| Logitech                             | 29        | 1.28%   |
| Creative Labs                        | 21        | 0.93%   |
| ASUSTek Computer                     | 21        | 0.93%   |
| SteelSeries ApS                      | 17        | 0.75%   |
| Lenovo                               | 15        | 0.66%   |
| Creative Technology                  | 15        | 0.66%   |
| Realtek Semiconductor                | 14        | 0.62%   |
| Texas Instruments                    | 13        | 0.58%   |
| Razer USA                            | 11        | 0.49%   |
| JMTek                                | 11        | 0.49%   |
| Focusrite-Novation                   | 10        | 0.44%   |
| Kingston Technology                  | 9         | 0.4%    |
| Plantronics                          | 8         | 0.35%   |
| GYROCOM C&C                          | 8         | 0.35%   |
| Blue Microphones                     | 8         | 0.35%   |
| Thesycon Systemsoftware & Consulting | 7         | 0.31%   |
| AudioQuest                           | 7         | 0.31%   |
| GN Netcom                            | 6         | 0.27%   |
| DSEA A/S                             | 6         | 0.27%   |
| Corsair                              | 6         | 0.27%   |
| BEHRINGER International              | 6         | 0.27%   |
| Samson Technologies                  | 5         | 0.22%   |
| RODE Microphones                     | 5         | 0.22%   |
| Generalplus Technology               | 5         | 0.22%   |
| Dell                                 | 5         | 0.22%   |
| Sony                                 | 4         | 0.18%   |
| Solid State Logic                    | 4         | 0.18%   |
| SAVITECH                             | 4         | 0.18%   |
| Trust                                | 3         | 0.13%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.13%   |
| No brand                             | 3         | 0.13%   |
| Microsoft                            | 3         | 0.13%   |
| Micro Star International             | 3         | 0.13%   |
| Guangzhou FiiO Electronics           | 3         | 0.13%   |
| Audio-Technica                       | 3         | 0.13%   |
| Audient                              | 3         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 184       | 6.73%   |
| AMD Starship/Matisse HD Audio Controller                                   | 161       | 5.89%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 106       | 3.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 95        | 3.48%   |
| Intel Sunrise Point-LP HD Audio                                            | 90        | 3.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 85        | 3.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 74        | 2.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 56        | 2.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 50        | 1.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 47        | 1.72%   |
| AMD Navi 10 HDMI Audio                                                     | 47        | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 42        | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 41        | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 41        | 1.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 40        | 1.46%   |
| Nvidia GP106 High Definition Audio Controller                              | 34        | 1.24%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 34        | 1.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 33        | 1.21%   |
| Nvidia GP104 High Definition Audio Controller                              | 33        | 1.21%   |
| Nvidia TU106 High Definition Audio Controller                              | 32        | 1.17%   |
| Nvidia TU104 HD Audio Controller                                           | 29        | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 29        | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 28        | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 27        | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 27        | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 0.99%   |
| Intel Comet Lake PCH cAVS                                                  | 27        | 0.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 27        | 0.99%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 26        | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 25        | 0.92%   |
| Nvidia GA104 High Definition Audio Controller                              | 24        | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24        | 0.88%   |
| Intel CM238 HD Audio Controller                                            | 24        | 0.88%   |
| Intel 200 Series PCH HD Audio                                              | 22        | 0.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 21        | 0.77%   |
| Nvidia GA102 High Definition Audio Controller                              | 20        | 0.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 20        | 0.73%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 20        | 0.73%   |
| Nvidia GM206 High Definition Audio Controller                              | 18        | 0.66%   |
| Nvidia GM204 High Definition Audio Controller                              | 18        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 310       | 20.13%  |
| Kingston                     | 211       | 13.7%   |
| SK hynix                     | 205       | 13.31%  |
| Corsair                      | 147       | 9.55%   |
| Micron Technology            | 139       | 9.03%   |
| Unknown                      | 125       | 8.12%   |
| G.Skill                      | 124       | 8.05%   |
| Crucial                      | 120       | 7.79%   |
| Ramaxel Technology           | 19        | 1.23%   |
| A-DATA Technology            | 17        | 1.1%    |
| Team                         | 16        | 1.04%   |
| Patriot                      | 13        | 0.84%   |
| Elpida                       | 11        | 0.71%   |
| Transcend                    | 10        | 0.65%   |
| Nanya Technology             | 9         | 0.58%   |
| GOODRAM                      | 8         | 0.52%   |
| Unknown                      | 8         | 0.52%   |
| Unknown (ABCD)               | 4         | 0.26%   |
| AMD                          | 4         | 0.26%   |
| Timetec                      | 3         | 0.19%   |
| Apacer                       | 3         | 0.19%   |
| Toshiba                      | 2         | 0.13%   |
| KLEVV                        | 2         | 0.13%   |
| Avant                        | 2         | 0.13%   |
| Unknown (0x5D00000000000000) | 1         | 0.06%   |
| Thermaltake                  | 1         | 0.06%   |
| Teikon                       | 1         | 0.06%   |
| T-FORCE                      | 1         | 0.06%   |
| SGS/Thomson                  | 1         | 0.06%   |
| Saikano                      | 1         | 0.06%   |
| Qumo                         | 1         | 0.06%   |
| Qimonda                      | 1         | 0.06%   |
| PUSKILL                      | 1         | 0.06%   |
| PNY                          | 1         | 0.06%   |
| Patriot Memory (PDP Systems) | 1         | 0.06%   |
| Patriot Memory               | 1         | 0.06%   |
| Magnum Tech                  | 1         | 0.06%   |
| Kllisre                      | 1         | 0.06%   |
| Kimtigo                      | 1         | 0.06%   |
| Innodisk                     | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 14        | 0.85%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 13        | 0.79%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 12        | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 12        | 0.73%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 12        | 0.73%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 11        | 0.67%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 11        | 0.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 10        | 0.61%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 10        | 0.61%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s     | 10        | 0.61%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 9         | 0.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 9         | 0.55%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 9         | 0.55%   |
| Unknown RAM Module 1GB SODIMM DDR                           | 8         | 0.49%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 8         | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 8         | 0.49%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s      | 8         | 0.49%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 8         | 0.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 8         | 0.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 8         | 0.49%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 8         | 0.49%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 8         | 0.49%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s       | 8         | 0.49%   |
| Unknown                                                     | 8         | 0.49%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 7         | 0.43%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 7         | 0.43%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s       | 7         | 0.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s           | 7         | 0.43%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 6         | 0.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 6         | 0.37%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s       | 6         | 0.37%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s         | 6         | 0.37%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s       | 6         | 0.37%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s      | 6         | 0.37%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s         | 6         | 0.37%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s      | 6         | 0.37%   |
| Unknown RAM Module 1024MB DIMM SDRAM                        | 5         | 0.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 5         | 0.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 5         | 0.31%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s   | 5         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 847       | 61.64%  |
| DDR3    | 295       | 21.47%  |
| DDR2    | 48        | 3.49%   |
| LPDDR4  | 42        | 3.06%   |
| DDR5    | 37        | 2.69%   |
| Unknown | 30        | 2.18%   |
| LPDDR3  | 26        | 1.89%   |
| SDRAM   | 19        | 1.38%   |
| DDR     | 16        | 1.16%   |
| LPDDR5  | 13        | 0.95%   |
| DRAM    | 1         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 649       | 47.2%   |
| SODIMM       | 635       | 46.18%  |
| Row Of Chips | 82        | 5.96%   |
| Chip         | 6         | 0.44%   |
| Unknown      | 2         | 0.15%   |
| RIMM         | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 598       | 40.57%  |
| 16384 | 382       | 25.92%  |
| 4096  | 239       | 16.21%  |
| 32768 | 112       | 7.6%    |
| 2048  | 92        | 6.24%   |
| 1024  | 38        | 2.58%   |
| 512   | 8         | 0.54%   |
| 256   | 5         | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 273       | 18.38%  |
| 2667    | 222       | 14.95%  |
| 1600    | 182       | 12.26%  |
| 2400    | 98        | 6.6%    |
| 3600    | 84        | 5.66%   |
| 2133    | 82        | 5.52%   |
| 1333    | 66        | 4.44%   |
| 667     | 32        | 2.15%   |
| 800     | 30        | 2.02%   |
| Unknown | 27        | 1.82%   |
| 3000    | 26        | 1.75%   |
| 4267    | 25        | 1.68%   |
| 3733    | 25        | 1.68%   |
| 4800    | 23        | 1.55%   |
| 3400    | 22        | 1.48%   |
| 6400    | 21        | 1.41%   |
| 1867    | 20        | 1.35%   |
| 2933    | 19        | 1.28%   |
| 1334    | 15        | 1.01%   |
| 2666    | 14        | 0.94%   |
| 3800    | 12        | 0.81%   |
| 3266    | 12        | 0.81%   |
| 1866    | 12        | 0.81%   |
| 3466    | 11        | 0.74%   |
| 8400    | 10        | 0.67%   |
| 1066    | 10        | 0.67%   |
| 3866    | 9         | 0.61%   |
| 1067    | 9         | 0.61%   |
| 3533    | 8         | 0.54%   |
| 3666    | 7         | 0.47%   |
| 4000    | 6         | 0.4%    |
| 3534    | 6         | 0.4%    |
| 2800    | 6         | 0.4%    |
| 400     | 6         | 0.4%    |
| 6000    | 5         | 0.34%   |
| 3333    | 5         | 0.34%   |
| 3933    | 4         | 0.27%   |
| 2048    | 4         | 0.27%   |
| 533     | 4         | 0.27%   |
| 5200    | 3         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 39.29%  |
| Seiko Epson           | 4         | 14.29%  |
| Samsung Electronics   | 4         | 14.29%  |
| Canon                 | 3         | 10.71%  |
| Brother Industries    | 3         | 10.71%  |
| Xiaomi                | 1         | 3.57%   |
| Lexmark International | 1         | 3.57%   |
| Konica Minolta        | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon LiDE 400                        | 2         | 7.14%   |
| Xiaomi MiMouse 2                      | 1         | 3.57%   |
| Seiko Epson XP-4200 Series            | 1         | 3.57%   |
| Seiko Epson WF-3520 Series            | 1         | 3.57%   |
| Seiko Epson WF-2510 Series            | 1         | 3.57%   |
| Seiko Epson AL-M310DN                 | 1         | 3.57%   |
| Samsung ML-191x/ML-252x Laser Printer | 1         | 3.57%   |
| Samsung ML-1630 Series                | 1         | 3.57%   |
| Samsung CLP-325 Color Laser Printer   | 1         | 3.57%   |
| Samsung C460 Series                   | 1         | 3.57%   |
| Lexmark International Lexmark E352dn  | 1         | 3.57%   |
| Konica Minolta magicolor 1680MF scan  | 1         | 3.57%   |
| HP PhotoSmart 130                     | 1         | 3.57%   |
| HP LaserJet P2055 series              | 1         | 3.57%   |
| HP LaserJet M14-M17                   | 1         | 3.57%   |
| HP LaserJet 3200                      | 1         | 3.57%   |
| HP LaserJet 1020                      | 1         | 3.57%   |
| HP LaserJet 1018                      | 1         | 3.57%   |
| HP LaserJet 1010                      | 1         | 3.57%   |
| HP Deskjet D1500 series               | 1         | 3.57%   |
| HP DeskJet 5440                       | 1         | 3.57%   |
| HP DeskJet 3630 series                | 1         | 3.57%   |
| HP Deskjet 2050 J510                  | 1         | 3.57%   |
| Canon LiDE 300                        | 1         | 3.57%   |
| Brother MFC-L2700DW                   | 1         | 3.57%   |
| Brother MFC-9340CDW                   | 1         | 3.57%   |
| Brother MFC-9130CW                    | 1         | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 83.33%  |
| AGFA-Gevaert NV | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 2         | 33.33%  |
| Canon CanoScan LiDE 600F      | 1         | 16.67%  |
| Canon CanoScan LiDE 220       | 1         | 16.67%  |
| Canon CanoScan LiDE 110       | 1         | 16.67%  |
| AGFA-Gevaert NV SnapScan e20  | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 162       | 20.25%  |
| Logitech                               | 103       | 12.88%  |
| IMC Networks                           | 87        | 10.88%  |
| Microdia                               | 74        | 9.25%   |
| Realtek Semiconductor                  | 53        | 6.63%   |
| Sunplus Innovation Technology          | 42        | 5.25%   |
| Bison Electronics                      | 36        | 4.5%    |
| Quanta                                 | 34        | 4.25%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 2.88%   |
| Lite-On Technology                     | 22        | 2.75%   |
| Apple                                  | 19        | 2.38%   |
| Luxvisions Innotech Limited            | 18        | 2.25%   |
| Acer                                   | 18        | 2.25%   |
| Syntek                                 | 17        | 2.13%   |
| Samsung Electronics                    | 12        | 1.5%    |
| Z-Star Microelectronics                | 8         | 1%      |
| Microsoft                              | 7         | 0.88%   |
| MacroSilicon                           | 4         | 0.5%    |
| DigiTech                               | 4         | 0.5%    |
| Suyin                                  | 3         | 0.38%   |
| Generalplus Technology                 | 3         | 0.38%   |
| Creative Technology                    | 3         | 0.38%   |
| AVerMedia Technologies                 | 3         | 0.38%   |
| ARC International                      | 3         | 0.38%   |
| SunplusIT                              | 2         | 0.25%   |
| Silicon Motion                         | 2         | 0.25%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.25%   |
| Razer USA                              | 2         | 0.25%   |
| LG Electronics                         | 2         | 0.25%   |
| KYE Systems (Mouse Systems)            | 2         | 0.25%   |
| Genesys Logic                          | 2         | 0.25%   |
| Elgato Systems                         | 2         | 0.25%   |
| Cubeternet                             | 2         | 0.25%   |
| Alcor Micro                            | 2         | 0.25%   |
| Xiaomi                                 | 1         | 0.13%   |
| webcam                                 | 1         | 0.13%   |
| WaveRider Communications               | 1         | 0.13%   |
| Valve Software                         | 1         | 0.13%   |
| USB3.0 HD Audio Capture                | 1         | 0.13%   |
| Sunplus Technology                     | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 52        | 6.41%   |
| Microdia Integrated_Webcam_HD                 | 38        | 4.69%   |
| IMC Networks Integrated Camera                | 36        | 4.44%   |
| Logitech HD Pro Webcam C920                   | 31        | 3.82%   |
| IMC Networks USB2.0 HD UVC WebCam             | 23        | 2.84%   |
| Realtek Integrated_Webcam_HD                  | 22        | 2.71%   |
| Logitech Webcam C270                          | 18        | 2.22%   |
| Bison Integrated Camera                       | 18        | 2.22%   |
| Chicony HD WebCam                             | 16        | 1.97%   |
| Syntek Integrated Camera                      | 12        | 1.48%   |
| Samsung Galaxy series, misc. (MTP mode)       | 12        | 1.48%   |
| Sunplus Integrated_Webcam_HD                  | 11        | 1.36%   |
| Chicony HP HD Camera                          | 11        | 1.36%   |
| Lite-On Integrated Camera                     | 9         | 1.11%   |
| Chicony USB2.0 Camera                         | 9         | 1.11%   |
| Microdia CameraA                              | 8         | 0.99%   |
| Logitech C922 Pro Stream Webcam               | 8         | 0.99%   |
| Quanta HD User Facing                         | 7         | 0.86%   |
| Logitech Webcam C310                          | 7         | 0.86%   |
| Logitech BRIO Ultra HD Webcam                 | 7         | 0.86%   |
| Sunplus HD WebCam                             | 6         | 0.74%   |
| Realtek Integrated Webcam HD                  | 6         | 0.74%   |
| Quanta HP Wide Vision HD Camera               | 6         | 0.74%   |
| Bison SunplusIT Integrated Camera             | 6         | 0.74%   |
| Apple FaceTime HD Camera                      | 6         | 0.74%   |
| Acer Integrated Camera                        | 6         | 0.74%   |
| IMC Networks ov9734_azurewave_camera          | 5         | 0.62%   |
| Chicony Lenovo EasyCamera                     | 5         | 0.62%   |
| Chicony Integrated Camera (1280x720@30)       | 5         | 0.62%   |
| Chicony HD User Facing                        | 5         | 0.62%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 5         | 0.62%   |
| Z-Star Venus USB2.0 Camera                    | 4         | 0.49%   |
| Sunplus HP Wide Vision HD                     | 4         | 0.49%   |
| Quanta RGB-IR Camera                          | 4         | 0.49%   |
| Quanta HD Webcam                              | 4         | 0.49%   |
| Microdia Laptop_Integrated_Webcam_HD          | 4         | 0.49%   |
| Microdia Integrated Webcam                    | 4         | 0.49%   |
| Microdia Camera                               | 4         | 0.49%   |
| MacroSilicon usb video                        | 4         | 0.49%   |
| Luxvisions Innotech Limited Integrated Camera | 4         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 67        | 44.37%  |
| Validity Sensors           | 36        | 23.84%  |
| Shenzhen Goodix Technology | 24        | 15.89%  |
| Elan Microelectronics      | 8         | 5.3%    |
| STMicroelectronics         | 4         | 2.65%   |
| LighTuning Technology      | 4         | 2.65%   |
| AuthenTec                  | 4         | 2.65%   |
| DigitalPersona             | 2         | 1.32%   |
| Upek                       | 1         | 0.66%   |
| Samsung Electronics        | 1         | 0.66%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 25        | 16.56%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 15        | 9.93%   |
| Shenzhen Goodix  Fingerprint Device                        | 10        | 6.62%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 9         | 5.96%   |
| Validity Sensors Synaptics WBDI                            | 9         | 5.96%   |
| Synaptics WBDI                                             | 8         | 5.3%    |
| Shenzhen Goodix Fingerprint Reader                         | 8         | 5.3%    |
| Validity Sensors VFS 5011 fingerprint sensor               | 7         | 4.64%   |
| Shenzhen Goodix FingerPrint                                | 6         | 3.97%   |
| Elan ELAN:Fingerprint                                      | 6         | 3.97%   |
| Synaptics UWP WBDI Device                                  | 4         | 2.65%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 4         | 2.65%   |
| STMicroelectronics Fingerprint Reader                      | 4         | 2.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 1.99%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 3         | 1.99%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 2         | 1.32%   |
| Validity Sensors VFS491                                    | 2         | 1.32%   |
| Validity Sensors Fingerprint scanner                       | 2         | 1.32%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint   | 2         | 1.32%   |
| Elan ELAN:ARM-M4                                           | 2         | 1.32%   |
| DigitalPersona Fingerprint Reader                          | 2         | 1.32%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 1.32%   |
| Unknown                                                    | 2         | 1.32%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 0.66%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 0.66%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 0.66%   |
| Synaptics WBDI Device                                      | 1         | 0.66%   |
| Synaptics UWP WBDI                                         | 1         | 0.66%   |
| Synaptics  WBDI                                            | 1         | 0.66%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 0.66%   |
| Samsung Fingerprint Sensor Device - 730B                   | 1         | 0.66%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 0.66%   |
| AuthenTec Fingerprint Sensor                               | 1         | 0.66%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 0.66%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 38        | 34.55%  |
| Broadcom                          | 37        | 33.64%  |
| Clay Logic                        | 5         | 4.55%   |
| Yubico.com                        | 4         | 3.64%   |
| Upek                              | 4         | 3.64%   |
| SCM Microsystems                  | 4         | 3.64%   |
| O2 Micro                          | 4         | 3.64%   |
| Hewlett-Packard                   | 2         | 1.82%   |
| Gemalto (was Gemplus)             | 2         | 1.82%   |
| Advanced Card Systems             | 2         | 1.82%   |
| VASCO Data Security International | 1         | 0.91%   |
| Purism, SPC                       | 1         | 0.91%   |
| Microchip Technology              | 1         | 0.91%   |
| Free Software Initiative of Japan | 1         | 0.91%   |
| Feitian Technologies              | 1         | 0.91%   |
| Bit4id                            | 1         | 0.91%   |
| Aladdin Knowledge Systems         | 1         | 0.91%   |
| Aktiv                             | 1         | 0.91%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 38        | 34.55%  |
| Broadcom 58200                                                               | 14        | 12.73%  |
| Broadcom 5880                                                                | 12        | 10.91%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 5.45%   |
| Clay Logic Nitrokey Pro                                                      | 5         | 4.55%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.64%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 4         | 3.64%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 3.64%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 2.73%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.82%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 2         | 1.82%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 1.82%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.82%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.91%   |
| Purism, SPC Librem Key                                                       | 1         | 0.91%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.91%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.91%   |
| Free Software Initiative of Japan Gnuk Token                                 | 1         | 0.91%   |
| Feitian Technologies U2F CCID KB                                             | 1         | 0.91%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.91%   |
| Bit4id miniLector-s                                                          | 1         | 0.91%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.91%   |
| Aktiv Rutoken lite                                                           | 1         | 0.91%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.91%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.91%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 699       | 43.12%  |
| 1     | 454       | 28.01%  |
| 2     | 220       | 13.57%  |
| 3     | 121       | 7.46%   |
| 4     | 72        | 4.44%   |
| 5     | 30        | 1.85%   |
| 6     | 19        | 1.17%   |
| 7     | 5         | 0.31%   |
| 8     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 299       | 17.88%  |
| Graphics card            | 223       | 13.34%  |
| Bluetooth                | 208       | 12.44%  |
| Camera                   | 178       | 10.65%  |
| Fingerprint reader       | 149       | 8.91%   |
| Net/wireless             | 119       | 7.12%   |
| Chipcard                 | 83        | 4.96%   |
| Sound                    | 76        | 4.55%   |
| Card reader              | 74        | 4.43%   |
| Multimedia controller    | 72        | 4.31%   |
| Network                  | 29        | 1.73%   |
| Firewire controller      | 28        | 1.67%   |
| Net/ethernet             | 26        | 1.56%   |
| Unassigned class         | 23        | 1.38%   |
| Modem                    | 20        | 1.2%    |
| Storage/ide              | 19        | 1.14%   |
| Storage/ata              | 15        | 0.9%    |
| Storage/raid             | 8         | 0.48%   |
| Tv card                  | 7         | 0.42%   |
| Storage                  | 6         | 0.36%   |
| Storage/nvme             | 4         | 0.24%   |
| Dvb card                 | 4         | 0.24%   |
| Wireless                 | 1         | 0.06%   |
| Unclassified device      | 1         | 0.06%   |

