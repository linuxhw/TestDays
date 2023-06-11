Gentoo 2.13 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.13.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo_2.13/Desktop/README.md) and [notebooks](/Dist/Gentoo_2.13/Notebook/README.md).

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

Total: 297

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
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c59398619e](https://linux-hardware.org/?probe=c59398619e) | Apr 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [59bdd9d328](https://linux-hardware.org/?probe=59bdd9d328) | Apr 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [79ec23e706](https://linux-hardware.org/?probe=79ec23e706) | Apr 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d19221e116](https://linux-hardware.org/?probe=d19221e116) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [58e2308d1e](https://linux-hardware.org/?probe=58e2308d1e) | Apr 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470p 20J7S25C0... | Notebook    | [c1f70c64ad](https://linux-hardware.org/?probe=c1f70c64ad) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [3599b8e875](https://linux-hardware.org/?probe=3599b8e875) | Mar 31, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [9e60f40931](https://linux-hardware.org/?probe=9e60f40931) | Mar 30, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [8f1dcf05eb](https://linux-hardware.org/?probe=8f1dcf05eb) | Mar 26, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0a19e934c3](https://linux-hardware.org/?probe=0a19e934c3) | Mar 26, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [85fb1a6778](https://linux-hardware.org/?probe=85fb1a6778) | Mar 26, 2023 |
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
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [0932f02541](https://linux-hardware.org/?probe=0932f02541) | Mar 12, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
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
| Dell          | Precision 7770              | Notebook    | [aa1ff5150c](https://linux-hardware.org/?probe=aa1ff5150c) | Mar 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [42edcf638d](https://linux-hardware.org/?probe=42edcf638d) | Mar 06, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [f0cde07b9f](https://linux-hardware.org/?probe=f0cde07b9f) | Mar 05, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [541a6200bc](https://linux-hardware.org/?probe=541a6200bc) | Mar 05, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [6ea10cb77a](https://linux-hardware.org/?probe=6ea10cb77a) | Feb 26, 2023 |
| Lenovo        | 1048 SDK0T08861 WIN 3305... | Desktop     | [e6b48cdec4](https://linux-hardware.org/?probe=e6b48cdec4) | Feb 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [a8da25537c](https://linux-hardware.org/?probe=a8da25537c) | Feb 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [da640089bd](https://linux-hardware.org/?probe=da640089bd) | Feb 21, 2023 |
| Dell          | Precision 7770              | Notebook    | [d8db6fecdd](https://linux-hardware.org/?probe=d8db6fecdd) | Feb 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [6424058c59](https://linux-hardware.org/?probe=6424058c59) | Feb 19, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [48ca6dc3eb](https://linux-hardware.org/?probe=48ca6dc3eb) | Feb 19, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [991db4f096](https://linux-hardware.org/?probe=991db4f096) | Feb 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [94ca7f3e34](https://linux-hardware.org/?probe=94ca7f3e34) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [6a952f7024](https://linux-hardware.org/?probe=6a952f7024) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [e8ba753fae](https://linux-hardware.org/?probe=e8ba753fae) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [12c06a594d](https://linux-hardware.org/?probe=12c06a594d) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [1423d5ac1b](https://linux-hardware.org/?probe=1423d5ac1b) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [bb589c5e58](https://linux-hardware.org/?probe=bb589c5e58) | Feb 10, 2023 |
| Dell          | Precision 7770              | Notebook    | [69b0982ad7](https://linux-hardware.org/?probe=69b0982ad7) | Feb 08, 2023 |
| Dell          | Precision 7770              | Notebook    | [28ba6f72d0](https://linux-hardware.org/?probe=28ba6f72d0) | Feb 07, 2023 |
| Dell          | Precision 7770              | Notebook    | [d05aabf7a5](https://linux-hardware.org/?probe=d05aabf7a5) | Feb 06, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a8dcc6b4c1](https://linux-hardware.org/?probe=a8dcc6b4c1) | Feb 03, 2023 |
| Dell          | Precision 7770              | Notebook    | [20f6b87742](https://linux-hardware.org/?probe=20f6b87742) | Feb 03, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0cf18835cc](https://linux-hardware.org/?probe=0cf18835cc) | Feb 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.1.19-gentoo-x86_64    | 14        | 7.04%   |
| 6.1.19-gentoo           | 13        | 6.53%   |
| 6.1.12-gentoo           | 10        | 5.03%   |
| 6.1.12-gentoo-x86_64    | 7         | 3.52%   |
| 6.1.28-gentoo           | 6         | 3.02%   |
| 6.2.11-gentoo           | 5         | 2.51%   |
| 6.1.22-gentoo-dist      | 5         | 2.51%   |
| 6.3.4-gentoo            | 4         | 2.01%   |
| 6.3.1-gentoo            | 4         | 2.01%   |
| 6.3.0-gentoo            | 4         | 2.01%   |
| 6.2.8-gentoo-x86_64     | 4         | 2.01%   |
| 6.2.11-gentoo-x86_64    | 4         | 2.01%   |
| 6.1.12-gentoo-dist      | 4         | 2.01%   |
| 6.2.2-gentoo            | 3         | 1.51%   |
| 6.1.27-gentoo-r1-x86_64 | 3         | 1.51%   |
| 6.1.24-gentoo-dist      | 3         | 1.51%   |
| 6.1.19-gentoo-dist      | 3         | 1.51%   |
| 6.3.3-gentoo            | 2         | 1.01%   |
| 6.2.9-gentoo-x86_64     | 2         | 1.01%   |
| 6.2.3-gentoo            | 2         | 1.01%   |
| 6.2.12-gentoo-x86_64    | 2         | 1.01%   |
| 6.2.1-gentoo-x86_64     | 2         | 1.01%   |
| 6.2.0                   | 2         | 1.01%   |
| 6.1.9-gentoo-x86_64     | 2         | 1.01%   |
| 6.1.9-gentoo-dist       | 2         | 1.01%   |
| 6.1.31-gentoo-x86_64    | 2         | 1.01%   |
| 6.1.31-gentoo-dist      | 2         | 1.01%   |
| 6.1.27-gentoo-dist      | 2         | 1.01%   |
| 6.1.10-gentoo-x86_64    | 2         | 1.01%   |
| 6.4.0-rc2-x86_64        | 1         | 0.5%    |
| 6.3.6-gentoo-dist       | 1         | 0.5%    |
| 6.3.5-gentoo-x86_64     | 1         | 0.5%    |
| 6.3.4-gentoo-r1         | 1         | 0.5%    |
| 6.3.4-gentoo-c17        | 1         | 0.5%    |
| 6.3.3-gentoo-dist       | 1         | 0.5%    |
| 6.3.2-gentoo-x86_64     | 1         | 0.5%    |
| 6.3.2-gentoo-dist       | 1         | 0.5%    |
| 6.3.2-gentoo            | 1         | 0.5%    |
| 6.3.1-zen1              | 1         | 0.5%    |
| 6.3.1-x86_64            | 1         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.19  | 35        | 17.59%  |
| 6.1.12  | 24        | 12.06%  |
| 6.2.11  | 12        | 6.03%   |
| 6.3.1   | 9         | 4.52%   |
| 6.1.27  | 8         | 4.02%   |
| 6.1.28  | 7         | 3.52%   |
| 6.3.4   | 6         | 3.02%   |
| 6.3.0   | 6         | 3.02%   |
| 6.2.9   | 5         | 2.51%   |
| 6.2.2   | 5         | 2.51%   |
| 6.2.0   | 5         | 2.51%   |
| 6.1.31  | 5         | 2.51%   |
| 6.1.22  | 5         | 2.51%   |
| 6.2.8   | 4         | 2.01%   |
| 6.2.12  | 4         | 2.01%   |
| 6.1.9   | 4         | 2.01%   |
| 6.1.11  | 4         | 2.01%   |
| 6.3.3   | 3         | 1.51%   |
| 6.3.2   | 3         | 1.51%   |
| 6.2.3   | 3         | 1.51%   |
| 6.1.24  | 3         | 1.51%   |
| 6.1.10  | 3         | 1.51%   |
| 6.2.6   | 2         | 1.01%   |
| 6.2.13  | 2         | 1.01%   |
| 6.2.10  | 2         | 1.01%   |
| 6.2.1   | 2         | 1.01%   |
| 6.1.29  | 2         | 1.01%   |
| 5.15.88 | 2         | 1.01%   |
| 5.15.80 | 2         | 1.01%   |
| 6.4.0   | 1         | 0.5%    |
| 6.3.6   | 1         | 0.5%    |
| 6.3.5   | 1         | 0.5%    |
| 6.2.7   | 1         | 0.5%    |
| 6.2.5   | 1         | 0.5%    |
| 6.2.14  | 1         | 0.5%    |
| 6.1.8   | 1         | 0.5%    |
| 6.1.4   | 1         | 0.5%    |
| 6.1.30  | 1         | 0.5%    |
| 6.1.15  | 1         | 0.5%    |
| 6.1.13  | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 91        | 50.28%  |
| 6.2     | 46        | 25.41%  |
| 6.3     | 28        | 15.47%  |
| 5.15    | 12        | 6.63%   |
| 6.4     | 1         | 0.55%   |
| 5.17    | 1         | 0.55%   |
| 5.16    | 1         | 0.55%   |
| 5.10    | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 166       | 97.08%  |
| i686    | 4         | 2.34%   |
| riscv64 | 1         | 0.58%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Unknown   | 54        | 31.03%  |
| KDE5      | 50        | 28.74%  |
| XFCE      | 20        | 11.49%  |
| GNOME     | 18        | 10.34%  |
| MATE      | 6         | 3.45%   |
| LXQt      | 5         | 2.87%   |
| dwm       | 4         | 2.3%    |
| KDE       | 3         | 1.72%   |
| i3        | 3         | 1.72%   |
| Trinity   | 2         | 1.15%   |
| Xsession  | 1         | 0.57%   |
| X-Generic | 1         | 0.57%   |
| sway      | 1         | 0.57%   |
| ratpoison | 1         | 0.57%   |
| openbox   | 1         | 0.57%   |
| LXDE      | 1         | 0.57%   |
| ICEWM     | 1         | 0.57%   |
| Hyprland  | 1         | 0.57%   |
| awesome   | 1         | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 84        | 47.19%  |
| Wayland | 38        | 21.35%  |
| Tty     | 30        | 16.85%  |
| Unknown | 26        | 14.61%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 62        | 35.63%  |
| SDDM    | 57        | 32.76%  |
| LightDM | 24        | 13.79%  |
| GDM     | 17        | 9.77%   |
| SLiM    | 4         | 2.3%    |
| LXDM    | 4         | 2.3%    |
| TDM     | 3         | 1.72%   |
| GREETD  | 2         | 1.15%   |
| XDM     | 1         | 0.57%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 68        | 38.64%  |
| Unknown    | 19        | 10.8%   |
| C.UTF8     | 18        | 10.23%  |
| en_GB      | 13        | 7.39%   |
| de_DE      | 9         | 5.11%   |
| C          | 8         | 4.55%   |
| ru_RU      | 7         | 3.98%   |
| fr_FR      | 7         | 3.98%   |
| en_IE      | 5         | 2.84%   |
| cs_CZ      | 5         | 2.84%   |
| pl_PL      | 2         | 1.14%   |
| it_IT      | 2         | 1.14%   |
| es_ES      | 2         | 1.14%   |
| en_AU      | 2         | 1.14%   |
| uk_UA      | 1         | 0.57%   |
| ru_RU.UTF8 | 1         | 0.57%   |
| ro_RO      | 1         | 0.57%   |
| fr_CA      | 1         | 0.57%   |
| fi_FI      | 1         | 0.57%   |
| es_MX      | 1         | 0.57%   |
| en_IL      | 1         | 0.57%   |
| el_GR      | 1         | 0.57%   |
| da_DK      | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 131       | 75.72%  |
| BIOS | 42        | 24.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 93        | 53.76%  |
| Btrfs    | 56        | 32.37%  |
| F2fs     | 8         | 4.62%   |
| Zfs      | 5         | 2.89%   |
| Xfs      | 5         | 2.89%   |
| XXXXXXX  | 3         | 1.73%   |
| Reiserfs | 2         | 1.16%   |
| Jfs      | 1         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 146       | 84.88%  |
| MBR     | 20        | 11.63%  |
| Unknown | 6         | 3.49%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 62.29%  |
| Yes       | 66        | 37.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 66.47%  |
| Yes       | 58        | 33.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 45        | 26.32%  |
| Lenovo              | 18        | 10.53%  |
| Hewlett-Packard     | 16        | 9.36%   |
| Gigabyte Technology | 16        | 9.36%   |
| ASRock              | 13        | 7.6%    |
| MSI                 | 12        | 7.02%   |
| Dell                | 10        | 5.85%   |
| Acer                | 6         | 3.51%   |
| Unknown             | 6         | 3.51%   |
| Supermicro          | 5         | 2.92%   |
| HUAWEI              | 3         | 1.75%   |
| Intel               | 2         | 1.17%   |
| Foxconn             | 2         | 1.17%   |
| ZOTAC               | 1         | 0.58%   |
| Valve               | 1         | 0.58%   |
| TYAN Computer       | 1         | 0.58%   |
| TUXEDO              | 1         | 0.58%   |
| Toshiba             | 1         | 0.58%   |
| Timi                | 1         | 0.58%   |
| Star Labs           | 1         | 0.58%   |
| realme              | 1         | 0.58%   |
| Pegatron            | 1         | 0.58%   |
| Panasonic           | 1         | 0.58%   |
| Microsoft           | 1         | 0.58%   |
| MAXDATA             | 1         | 0.58%   |
| HPE                 | 1         | 0.58%   |
| Fujitsu Siemens     | 1         | 0.58%   |
| Fujitsu             | 1         | 0.58%   |
| Fanless Mini PC     | 1         | 0.58%   |
| Apple               | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 6         | 3.51%   |
| Supermicro Super Server               | 3         | 1.75%   |
| HP ProLiant MicroServer Gen8          | 3         | 1.75%   |
| ASUS ROG Zephyrus G14 GA401II_GA401II | 3         | 1.75%   |
| MSI MS-7B85                           | 2         | 1.17%   |
| Gigabyte X570S AORUS ELITE AX         | 2         | 1.17%   |
| Dell Precision 7770                   | 2         | 1.17%   |
| ASUS TUF Gaming X570-PLUS             | 2         | 1.17%   |
| ASUS ROG STRIX Z590-F GAMING WIFI     | 2         | 1.17%   |
| ASUS ROG STRIX X570-E GAMING          | 2         | 1.17%   |
| ASUS ROG Strix G513QY_G513QY          | 2         | 1.17%   |
| ASUS ROG STRIX B650E-F GAMING WIFI    | 2         | 1.17%   |
| ASUS M3A78-CM                         | 2         | 1.17%   |
| ASUS All Series                       | 2         | 1.17%   |
| ASRock X570 Taichi                    | 2         | 1.17%   |
| ZOTAC H67ITX-C-E                      | 1         | 0.58%   |
| Valve Jupiter                         | 1         | 0.58%   |
| TYAN VT82C694T                        | 1         | 0.58%   |
| TUXEDO Polaris AMD Gen3 (CZN)         | 1         | 0.58%   |
| Toshiba Satellite L850                | 1         | 0.58%   |
| Timi RedmiBook Pro 15S                | 1         | 0.58%   |
| Supermicro X10SL7-F                   | 1         | 0.58%   |
| Supermicro SSG-6028R-ER12-HDP-AI050   | 1         | 0.58%   |
| Star Labs StarBook                    | 1         | 0.58%   |
| realme RMNBXXXX                       | 1         | 0.58%   |
| Pegatron 810-170st                    | 1         | 0.58%   |
| Panasonic CF-53ASCZGFG                | 1         | 0.58%   |
| MSI Vector GP66 12UEO                 | 1         | 0.58%   |
| MSI MS-7D67                           | 1         | 0.58%   |
| MSI MS-7D09                           | 1         | 0.58%   |
| MSI MS-7C91                           | 1         | 0.58%   |
| MSI MS-7C35                           | 1         | 0.58%   |
| MSI MS-7B18                           | 1         | 0.58%   |
| MSI MS-7817                           | 1         | 0.58%   |
| MSI MS-7640                           | 1         | 0.58%   |
| MSI GS66 Stealth 10UE                 | 1         | 0.58%   |
| MSI GE76 Raider 11UH                  | 1         | 0.58%   |
| Microsoft Surface Laptop 3            | 1         | 0.58%   |
| MAXDATA o.max_5xs                     | 1         | 0.58%   |
| Lenovo Yoga C940-15IRH 81TE           | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| ASUS ROG                            | 20        | 11.7%   |
| Lenovo ThinkPad                     | 11        | 6.43%   |
| ASUS PRIME                          | 7         | 4.09%   |
| Unknown                             | 6         | 3.51%   |
| ASUS TUF                            | 5         | 2.92%   |
| HP EliteBook                        | 4         | 2.34%   |
| Acer Aspire                         | 4         | 2.34%   |
| Supermicro Super                    | 3         | 1.75%   |
| HP ProLiant                         | 3         | 1.75%   |
| Dell Precision                      | 3         | 1.75%   |
| Dell Latitude                       | 3         | 1.75%   |
| ASRock X670E                        | 3         | 1.75%   |
| MSI MS-7B85                         | 2         | 1.17%   |
| Lenovo ThinkStation                 | 2         | 1.17%   |
| Lenovo Legion                       | 2         | 1.17%   |
| HP Victus                           | 2         | 1.17%   |
| HP Pavilion                         | 2         | 1.17%   |
| Gigabyte X570S                      | 2         | 1.17%   |
| Gigabyte X570                       | 2         | 1.17%   |
| Dell XPS                            | 2         | 1.17%   |
| Dell Inspiron                       | 2         | 1.17%   |
| ASUS M3A78-CM                       | 2         | 1.17%   |
| ASUS All                            | 2         | 1.17%   |
| ASRock X570                         | 2         | 1.17%   |
| Acer Swift                          | 2         | 1.17%   |
| ZOTAC H67ITX-C-E                    | 1         | 0.58%   |
| Valve Jupiter                       | 1         | 0.58%   |
| TYAN VT82C694T                      | 1         | 0.58%   |
| TUXEDO Polaris                      | 1         | 0.58%   |
| Toshiba Satellite                   | 1         | 0.58%   |
| Timi RedmiBook                      | 1         | 0.58%   |
| Supermicro X10SL7-F                 | 1         | 0.58%   |
| Supermicro SSG-6028R-ER12-HDP-AI050 | 1         | 0.58%   |
| Star Labs StarBook                  | 1         | 0.58%   |
| realme RMNBXXXX                     | 1         | 0.58%   |
| Pegatron 810-170st                  | 1         | 0.58%   |
| Panasonic CF-53ASCZGFG              | 1         | 0.58%   |
| MSI Vector                          | 1         | 0.58%   |
| MSI MS-7D67                         | 1         | 0.58%   |
| MSI MS-7D09                         | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 29        | 16.96%  |
| 2022    | 28        | 16.37%  |
| 2019    | 22        | 12.87%  |
| 2020    | 18        | 10.53%  |
| 2018    | 14        | 8.19%   |
| 2012    | 10        | 5.85%   |
| 2013    | 8         | 4.68%   |
| 2010    | 7         | 4.09%   |
| 2017    | 6         | 3.51%   |
| 2023    | 5         | 2.92%   |
| 2016    | 5         | 2.92%   |
| 2014    | 4         | 2.34%   |
| 2011    | 3         | 1.75%   |
| 2009    | 3         | 1.75%   |
| 2008    | 3         | 1.75%   |
| 2015    | 2         | 1.17%   |
| 2007    | 1         | 0.58%   |
| 2003    | 1         | 0.58%   |
| 2002    | 1         | 0.58%   |
| Unknown | 1         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 90        | 52.63%  |
| Notebook       | 71        | 41.52%  |
| Server         | 4         | 2.34%   |
| Convertible    | 2         | 1.17%   |
| Stick pc       | 1         | 0.58%   |
| System on chip | 1         | 0.58%   |
| Tablet         | 1         | 0.58%   |
| Mini pc        | 1         | 0.58%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 170       | 99.42%  |
| Enabled  | 1         | 0.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 170       | 99.42%  |
| Yes  | 1         | 0.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 40        | 23.12%  |
| 16.01-24.0      | 32        | 18.5%   |
| 64.01-256.0     | 31        | 17.92%  |
| 8.01-16.0       | 26        | 15.03%  |
| 4.01-8.0        | 16        | 9.25%   |
| 24.01-32.0      | 12        | 6.94%   |
| 3.01-4.0        | 7         | 4.05%   |
| 2.01-3.0        | 3         | 1.73%   |
| 1.01-2.0        | 3         | 1.73%   |
| More than 256.0 | 1         | 0.58%   |
| 0.51-1.0        | 1         | 0.58%   |
| 0.01-0.5        | 1         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 39        | 20.63%  |
| 4.01-8.0   | 34        | 17.99%  |
| 1.01-2.0   | 28        | 14.81%  |
| 8.01-16.0  | 26        | 13.76%  |
| 3.01-4.0   | 21        | 11.11%  |
| 0.51-1.0   | 18        | 9.52%   |
| 0.01-0.5   | 15        | 7.94%   |
| 16.01-24.0 | 4         | 2.12%   |
| 32.01-64.0 | 2         | 1.06%   |
| 24.01-32.0 | 1         | 0.53%   |
| 0          | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 74        | 43.02%  |
| 2      | 43        | 25%     |
| 3      | 19        | 11.05%  |
| 5      | 13        | 7.56%   |
| 4      | 8         | 4.65%   |
| 6      | 5         | 2.91%   |
| 10     | 3         | 1.74%   |
| 7      | 3         | 1.74%   |
| 8      | 2         | 1.16%   |
| 13     | 1         | 0.58%   |
| 0      | 1         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 134       | 78.36%  |
| Yes       | 37        | 21.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 88.95%  |
| No        | 19        | 11.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 69.77%  |
| No        | 52        | 30.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 63.58%  |
| No        | 63        | 36.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 47        | 27.33%  |
| Germany     | 22        | 12.79%  |
| France      | 14        | 8.14%   |
| Russia      | 12        | 6.98%   |
| UK          | 10        | 5.81%   |
| Poland      | 9         | 5.23%   |
| Canada      | 9         | 5.23%   |
| Spain       | 6         | 3.49%   |
| Czechia     | 4         | 2.33%   |
| Sweden      | 3         | 1.74%   |
| Italy       | 3         | 1.74%   |
| Brazil      | 3         | 1.74%   |
| Vietnam     | 2         | 1.16%   |
| Switzerland | 2         | 1.16%   |
| Netherlands | 2         | 1.16%   |
| Hungary     | 2         | 1.16%   |
| China       | 2         | 1.16%   |
| Australia   | 2         | 1.16%   |
| Ukraine     | 1         | 0.58%   |
| Romania     | 1         | 0.58%   |
| Portugal    | 1         | 0.58%   |
| Norway      | 1         | 0.58%   |
| New Zealand | 1         | 0.58%   |
| Mexico      | 1         | 0.58%   |
| Luxembourg  | 1         | 0.58%   |
| Lithuania   | 1         | 0.58%   |
| Israel      | 1         | 0.58%   |
| Ireland     | 1         | 0.58%   |
| Indonesia   | 1         | 0.58%   |
| Iceland     | 1         | 0.58%   |
| Hong Kong   | 1         | 0.58%   |
| Greece      | 1         | 0.58%   |
| Finland     | 1         | 0.58%   |
| Denmark     | 1         | 0.58%   |
| Belarus     | 1         | 0.58%   |
| Algeria     | 1         | 0.58%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 7         | 3.98%   |
| Paris             | 5         | 2.84%   |
| Frankfurt am Main | 4         | 2.27%   |
| Warsaw            | 3         | 1.7%    |
| Sterling          | 3         | 1.7%    |
| St Petersburg     | 3         | 1.7%    |
| Šlapanice        | 3         | 1.7%    |
| Kippens           | 3         | 1.7%    |
| Cieszyn           | 3         | 1.7%    |
| Beaverton         | 3         | 1.7%    |
| Vladivostok       | 2         | 1.14%   |
| Taganrog          | 2         | 1.14%   |
| Summerville       | 2         | 1.14%   |
| Stockholm         | 2         | 1.14%   |
| Pittsburgh        | 2         | 1.14%   |
| Oviedo            | 2         | 1.14%   |
| Moscow            | 2         | 1.14%   |
| Milan             | 2         | 1.14%   |
| Leeds             | 2         | 1.14%   |
| Hanoi             | 2         | 1.14%   |
| Gatineau          | 2         | 1.14%   |
| Flint             | 2         | 1.14%   |
| Cognac            | 2         | 1.14%   |
| Chicago           | 2         | 1.14%   |
| Budapest          | 2         | 1.14%   |
| Bothell           | 2         | 1.14%   |
| Augusta           | 2         | 1.14%   |
| Zurich            | 1         | 0.57%   |
| Yucaipa           | 1         | 0.57%   |
| Wlodawa           | 1         | 0.57%   |
| Whitby            | 1         | 0.57%   |
| Wheaton           | 1         | 0.57%   |
| Vilnius           | 1         | 0.57%   |
| Vechta            | 1         | 0.57%   |
| Vancouver         | 1         | 0.57%   |
| Urbana            | 1         | 0.57%   |
| Trakai            | 1         | 0.57%   |
| Toronto           | 1         | 0.57%   |
| Surabaya          | 1         | 0.57%   |
| Sun Prairie       | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 68        | 119    | 22.59%  |
| WDC                         | 35        | 74     | 11.63%  |
| Seagate                     | 35        | 79     | 11.63%  |
| SanDisk                     | 29        | 34     | 9.63%   |
| Crucial                     | 13        | 19     | 4.32%   |
| Phison Electronics          | 12        | 16     | 3.99%   |
| Toshiba                     | 11        | 18     | 3.65%   |
| Intel                       | 11        | 13     | 3.65%   |
| SK hynix                    | 10        | 10     | 3.32%   |
| Kingston                    | 9         | 11     | 2.99%   |
| China                       | 8         | 20     | 2.66%   |
| Hitachi                     | 6         | 18     | 1.99%   |
| Unknown                     | 5         | 6      | 1.66%   |
| Micron/Crucial Technology   | 5         | 7      | 1.66%   |
| Micron Technology           | 5         | 6      | 1.66%   |
| Kingston Technology Company | 5         | 5      | 1.66%   |
| HGST                        | 5         | 9      | 1.66%   |
| GOODRAM                     | 5         | 14     | 1.66%   |
| A-DATA Technology           | 3         | 3      | 1%      |
| PNY                         | 2         | 4      | 0.66%   |
| Phison                      | 2         | 2      | 0.66%   |
| OCZ                         | 2         | 2      | 0.66%   |
| ADROITLARK                  | 2         | 3      | 0.66%   |
| ADATA Technology            | 2         | 4      | 0.66%   |
| V-GeN                       | 1         | 1      | 0.33%   |
| Transcend                   | 1         | 1      | 0.33%   |
| Silicon Motion              | 1         | 2      | 0.33%   |
| Realtek Semiconductor       | 1         | 1      | 0.33%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.33%   |
| LITEONIT                    | 1         | 1      | 0.33%   |
| KIOXIA                      | 1         | 1      | 0.33%   |
| KingSpec                    | 1         | 1      | 0.33%   |
| Intenso                     | 1         | 1      | 0.33%   |
| Dogfish                     | 1         | 1      | 0.33%   |
| Unknown                     | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 25        | 6.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 21        | 5.83%   |
| Samsung SSD 980 1TB                                 | 8         | 2.22%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 7         | 1.94%   |
| Seagate ST4000DM004-2CV104 4TB                      | 6         | 1.67%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 6         | 1.67%   |
| Seagate ST1000DM010-2EP102 1TB                      | 4         | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 4         | 1.11%   |
| Intel SSD 660P Series 512GB                         | 4         | 1.11%   |
| Crucial CT1000MX500SSD1 1TB                         | 4         | 1.11%   |
| Samsung SSD 860 EVO 1TB                             | 3         | 0.83%   |
| Phison E12 NVMe Controller 256GB                    | 3         | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 3         | 0.83%   |
| WDC WD5000LPLX-66ZNTT1 500GB                        | 2         | 0.56%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 2         | 0.56%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 2         | 0.56%   |
| WDC WD20EARX-00PASB0 2TB                            | 2         | 0.56%   |
| WDC WD2003FZEX-00SRLA0 2TB                          | 2         | 0.56%   |
| WDC WD1502FYPS-02W3B0 1TB                           | 2         | 0.56%   |
| WDC WD120EFBX-68B0EN0 12TB                          | 2         | 0.56%   |
| Unknown MMC Card  128GB                             | 2         | 0.56%   |
| Toshiba DT01ACA200 2TB                              | 2         | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 2         | 0.56%   |
| Seagate ST6000DM003-2CY186 6TB                      | 2         | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.56%   |
| Sandisk WD_BLACK SN770 1TB                          | 2         | 0.56%   |
| Samsung SSD 870 QVO 2TB                             | 2         | 0.56%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.56%   |
| Samsung SSD 860 EVO 4TB                             | 2         | 0.56%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.56%   |
| Phison E7 NVMe Controller 120GB                     | 2         | 0.56%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 2         | 0.56%   |
| Phison Corsair MP600 PRO XT 2TB                     | 2         | 0.56%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                       | 2         | 0.56%   |
| Kingston Company SNV2S2000G 2TB                     | 2         | 0.56%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.56%   |
| Intel SSDPEKNU512GZ 512GB                           | 2         | 0.56%   |
| HGST HTS725050A7E630 500GB                          | 2         | 0.56%   |
| GOODRAM SSDPR-CL100-480-G2 480GB                    | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 77     | 39.33%  |
| WDC                 | 31        | 69     | 34.83%  |
| Toshiba             | 11        | 18     | 12.36%  |
| Hitachi             | 6         | 18     | 6.74%   |
| HGST                | 5         | 9      | 5.62%   |
| Samsung Electronics | 1         | 1      | 1.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 33     | 25.81%  |
| Crucial             | 13        | 19     | 13.98%  |
| SanDisk             | 10        | 12     | 10.75%  |
| China               | 8         | 20     | 8.6%    |
| Kingston            | 7         | 8      | 7.53%   |
| GOODRAM             | 5         | 14     | 5.38%   |
| WDC                 | 4         | 5      | 4.3%    |
| Intel               | 3         | 4      | 3.23%   |
| A-DATA Technology   | 3         | 3      | 3.23%   |
| PNY                 | 2         | 4      | 2.15%   |
| OCZ                 | 2         | 2      | 2.15%   |
| Micron Technology   | 2         | 3      | 2.15%   |
| ADROITLARK          | 2         | 3      | 2.15%   |
| V-GeN               | 1         | 1      | 1.08%   |
| Transcend           | 1         | 1      | 1.08%   |
| SK hynix            | 1         | 1      | 1.08%   |
| LITEONIT            | 1         | 1      | 1.08%   |
| KingSpec            | 1         | 1      | 1.08%   |
| Intenso             | 1         | 1      | 1.08%   |
| Dogfish             | 1         | 1      | 1.08%   |
| Unknown             | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 101       | 170    | 41.06%  |
| SSD     | 71        | 138    | 28.86%  |
| HDD     | 68        | 192    | 27.64%  |
| MMC     | 4         | 5      | 1.63%   |
| Unknown | 2         | 3      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 105       | 320    | 48.61%  |
| NVMe | 101       | 170    | 46.76%  |
| SAS  | 6         | 13     | 2.78%   |
| MMC  | 4         | 5      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 65        | 101    | 36.72%  |
| 0.51-1.0   | 46        | 78     | 25.99%  |
| 1.01-2.0   | 28        | 56     | 15.82%  |
| 3.01-4.0   | 17        | 37     | 9.6%    |
| 4.01-10.0  | 13        | 31     | 7.34%   |
| 2.01-3.0   | 5         | 21     | 2.82%   |
| 10.01-20.0 | 3         | 6      | 1.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 33        | 18.75%  |
| More than 3000 | 32        | 18.18%  |
| 251-500        | 31        | 17.61%  |
| 1001-2000      | 24        | 13.64%  |
| 101-250        | 20        | 11.36%  |
| 2001-3000      | 12        | 6.82%   |
| 1-20           | 8         | 4.55%   |
| 51-100         | 7         | 3.98%   |
| Unknown        | 7         | 3.98%   |
| 21-50          | 2         | 1.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 34        | 18.58%  |
| 501-1000       | 27        | 14.75%  |
| 21-50          | 26        | 14.21%  |
| 101-250        | 22        | 12.02%  |
| 251-500        | 21        | 11.48%  |
| More than 3000 | 17        | 9.29%   |
| 1001-2000      | 14        | 7.65%   |
| 51-100         | 13        | 7.1%    |
| Unknown        | 7         | 3.83%   |
| 2001-3000      | 2         | 1.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba DT01ACA200 2TB               | 2         | 2      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 3      | 6.67%   |
| HGST HTS725050A7E630 500GB           | 2         | 2      | 6.67%   |
| WDC WD60PURZ-85ZUFY1 6TB             | 1         | 1      | 3.33%   |
| WDC WD60EZRX-00MVLB1 6TB             | 1         | 1      | 3.33%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 2      | 3.33%   |
| Toshiba MK5056GSY 500GB              | 1         | 1      | 3.33%   |
| Toshiba MK1633GSG 160GB              | 1         | 1      | 3.33%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 1      | 3.33%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 1      | 3.33%   |
| Seagate ST500DM002-1BC142 500GB      | 1         | 1      | 3.33%   |
| Seagate ST380011A 80GB               | 1         | 1      | 3.33%   |
| Seagate ST3500630NS 500GB            | 1         | 2      | 3.33%   |
| Seagate ST3000DM001-9YN166 3TB       | 1         | 1      | 3.33%   |
| Seagate ST2000DX002-2DV164 2TB       | 1         | 1      | 3.33%   |
| Seagate ST2000DM001-1CH164 2TB       | 1         | 1      | 3.33%   |
| Seagate ST1000DM010-2EP102 1TB       | 1         | 1      | 3.33%   |
| SanDisk SSD PLUS 480GB               | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 980 1TB      | 1         | 1      | 3.33%   |
| PNY SSD2SC120G1LC763C121S459P 120GB  | 1         | 1      | 3.33%   |
| Intel SSDSC2BF180A5L 180GB           | 1         | 1      | 3.33%   |
| Intel SSDSC2BB160G4T 160GB           | 1         | 2      | 3.33%   |
| Hitachi HTS721080G9SA00 80GB         | 1         | 1      | 3.33%   |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 3.33%   |
| Crucial M4-CT512M4SSD2 512GB         | 1         | 1      | 3.33%   |
| China SSD 240GB                      | 1         | 1      | 3.33%   |
| China SATA SSD 960GB                 | 1         | 2      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 12     | 31.03%  |
| Toshiba             | 4         | 4      | 13.79%  |
| WDC                 | 3         | 4      | 10.34%  |
| HGST                | 3         | 3      | 10.34%  |
| Intel               | 2         | 3      | 6.9%    |
| China               | 2         | 3      | 6.9%    |
| SK hynix            | 1         | 1      | 3.45%   |
| SanDisk             | 1         | 1      | 3.45%   |
| Samsung Electronics | 1         | 1      | 3.45%   |
| PNY                 | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 12     | 45%     |
| Toshiba | 4         | 4      | 20%     |
| WDC     | 3         | 4      | 15%     |
| HGST    | 3         | 3      | 15%     |
| Hitachi | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 24     | 67.86%  |
| SSD  | 7         | 9      | 25%     |
| NVMe | 2         | 2      | 7.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB        | 1         | 2      | 50%     |
| Samsung Electronics SSD 980 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 148       | 424    | 75.13%  |
| Malfunc  | 27        | 35     | 13.71%  |
| Detected | 20        | 46     | 10.15%  |
| Failed   | 2         | 3      | 1.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 77        | 27.4%   |
| AMD                         | 61        | 21.71%  |
| Samsung Electronics         | 49        | 17.44%  |
| SanDisk                     | 20        | 7.12%   |
| Phison Electronics          | 13        | 4.63%   |
| ASMedia Technology          | 12        | 4.27%   |
| SK hynix                    | 9         | 3.2%    |
| Kingston Technology Company | 7         | 2.49%   |
| Micron/Crucial Technology   | 5         | 1.78%   |
| Marvell Technology Group    | 5         | 1.78%   |
| JMicron Technology          | 4         | 1.42%   |
| Broadcom / LSI              | 4         | 1.42%   |
| Micron Technology           | 3         | 1.07%   |
| Nvidia                      | 2         | 0.71%   |
| ADATA Technology            | 2         | 0.71%   |
| VIA Technologies            | 1         | 0.36%   |
| Silicon Motion              | 1         | 0.36%   |
| Silicon Image               | 1         | 0.36%   |
| Realtek Semiconductor       | 1         | 0.36%   |
| MAXIO Technology (Hangzhou) | 1         | 0.36%   |
| LSI Logic / Symbios Logic   | 1         | 0.36%   |
| KIOXIA                      | 1         | 0.36%   |
| INNOGRIT                    | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 48        | 15.19%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 24        | 7.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 21        | 6.65%   |
| Samsung NVMe SSD Controller 980                                                | 11        | 3.48%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 10        | 3.16%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.22%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 2.22%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 1.9%    |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 1.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 1.9%    |
| AMD 500 Series Chipset SATA Controller                                         | 6         | 1.9%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 1.58%   |
| Phison E18 PCIe4 NVMe Controller                                               | 5         | 1.58%   |
| Kingston Company Company Non-Volatile memory controller                        | 5         | 1.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.27%   |
| Intel SSD 660P Series                                                          | 4         | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.27%   |
| Intel Non-Volatile memory controller                                           | 4         | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 1.27%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.95%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 0.95%   |
| Micron NVMe Storage Controller                                                 | 3         | 0.95%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 0.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.95%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.95%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                               | 2         | 0.63%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.63%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 2         | 0.63%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 2         | 0.63%   |
| Phison E7 NVMe Controller                                                      | 2         | 0.63%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.63%   |
| Nvidia MCP79 SATA Controller                                                   | 2         | 0.63%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 125       | 49.21%  |
| NVMe | 100       | 39.37%  |
| IDE  | 13        | 5.12%   |
| RAID | 11        | 4.33%   |
| SAS  | 5         | 1.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor     | Computers | Percent |
|------------|-----------|---------|
| Intel      | 94        | 54.97%  |
| AMD        | 76        | 44.44%  |
| thead,c906 | 1         | 0.58%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 9 7900X 12-Core Processor           | 6         | 3.49%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 2.91%   |
| Intel 12th Gen Core i7-12700H                 | 4         | 2.33%   |
| AMD Ryzen 9 7950X 16-Core Processor           | 4         | 2.33%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 2.33%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4         | 2.33%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz           | 3         | 1.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.74%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 3         | 1.74%   |
| AMD Ryzen 7 4800HS with Radeon Graphics       | 3         | 1.74%   |
| Intel Core i9-10850K CPU @ 3.60GHz            | 2         | 1.16%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.16%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.16%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 2         | 1.16%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 2         | 1.16%   |
| Intel Atom CPU D510 @ 1.66GHz                 | 2         | 1.16%   |
| Intel Atom CPU 330 @ 1.60GHz                  | 2         | 1.16%   |
| Intel 12th Gen Core i7-12850HX                | 2         | 1.16%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz      | 2         | 1.16%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.16%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 2         | 1.16%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.16%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 2         | 1.16%   |
| AMD Ryzen 7 5800X3D 8-Core Processor          | 2         | 1.16%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.16%   |
| AMD Ryzen 5 7600X 6-Core Processor            | 2         | 1.16%   |
| AMD Ryzen 5 5500                              | 2         | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.16%   |
| AMD Phenom II X4 955 Processor                | 2         | 1.16%   |
| thead,c906 rv64imafdc                         | 1         | 0.58%   |
| Intel Xeon W-2145 CPU @ 3.70GHz               | 1         | 0.58%   |
| Intel Xeon E-2224 CPU @ 3.40GHz               | 1         | 0.58%   |
| Intel Xeon CPU E5-2696 v4 @ 2.20GHz           | 1         | 0.58%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz           | 1         | 0.58%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.58%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz          | 1         | 0.58%   |
| Intel Xeon CPU D-1521 @ 2.40GHz               | 1         | 0.58%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.58%   |
| Intel Pentium III CPU - S 1400MHz             | 1         | 0.58%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 26        | 15.2%   |
| Intel Core i7        | 26        | 15.2%   |
| AMD Ryzen 9          | 21        | 12.28%  |
| AMD Ryzen 7          | 21        | 12.28%  |
| AMD Ryzen 5          | 20        | 11.7%   |
| Intel Core i5        | 12        | 7.02%   |
| Intel Xeon           | 10        | 5.85%   |
| Intel Atom           | 6         | 3.51%   |
| Intel Core i9        | 4         | 2.34%   |
| Intel Core i3        | 4         | 2.34%   |
| AMD Ryzen 7 PRO      | 3         | 1.75%   |
| AMD Phenom II X4     | 3         | 1.75%   |
| Intel Pentium        | 2         | 1.17%   |
| AMD FX               | 2         | 1.17%   |
| AMD EPYC             | 2         | 1.17%   |
| Intel Pentium Silver | 1         | 0.58%   |
| Intel Pentium III    | 1         | 0.58%   |
| Intel Pentium 4      | 1         | 0.58%   |
| Intel Core Duo       | 1         | 0.58%   |
| Intel Core 2 Duo     | 1         | 0.58%   |
| Intel Celeron        | 1         | 0.58%   |
| AMD Ryzen 5 PRO      | 1         | 0.58%   |
| AMD Athlon II        | 1         | 0.58%   |
| AMD Athlon           | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 46        | 26.9%   |
| 8       | 40        | 23.39%  |
| 6       | 24        | 14.04%  |
| 2       | 24        | 14.04%  |
| 16      | 13        | 7.6%    |
| 12      | 13        | 7.6%    |
| 14      | 4         | 2.34%   |
| 10      | 2         | 1.17%   |
| 1       | 2         | 1.17%   |
| 44      | 1         | 0.58%   |
| 32      | 1         | 0.58%   |
| Unknown | 1         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 168       | 98.25%  |
| 2       | 2         | 1.17%   |
| Unknown | 1         | 0.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 150       | 87.72%  |
| 1       | 20        | 11.7%   |
| Unknown | 1         | 0.58%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 166       | 97.08%  |
| 32-bit         | 4         | 2.34%   |
| Unknown        | 1         | 0.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 31.82%  |
| 0x0a601203 | 12        | 6.82%   |
| 0x806c1    | 8         | 4.55%   |
| 0x0a50000c | 8         | 4.55%   |
| 0x08701021 | 7         | 3.98%   |
| 0x0a20120a | 6         | 3.41%   |
| 0x906ea    | 5         | 2.84%   |
| 0x906e9    | 4         | 2.27%   |
| 0x0800820d | 4         | 2.27%   |
| 0x306c3    | 3         | 1.7%    |
| 0x206a7    | 3         | 1.7%    |
| 0x0a50000d | 3         | 1.7%    |
| 0x08608103 | 3         | 1.7%    |
| 0x08600104 | 3         | 1.7%    |
| 0x08108109 | 3         | 1.7%    |
| 0xa0671    | 2         | 1.14%   |
| 0xa0652    | 2         | 1.14%   |
| 0x906ed    | 2         | 1.14%   |
| 0x906a3    | 2         | 1.14%   |
| 0x90672    | 2         | 1.14%   |
| 0x506e3    | 2         | 1.14%   |
| 0x306a9    | 2         | 1.14%   |
| 0x0a201016 | 2         | 1.14%   |
| 0xf29      | 1         | 0.57%   |
| 0xb06a2    | 1         | 0.57%   |
| 0xa0655    | 1         | 0.57%   |
| 0x806e9    | 1         | 0.57%   |
| 0x806d1    | 1         | 0.57%   |
| 0x706a8    | 1         | 0.57%   |
| 0x50663    | 1         | 0.57%   |
| 0x406f1    | 1         | 0.57%   |
| 0x406e3    | 1         | 0.57%   |
| 0x40651    | 1         | 0.57%   |
| 0x306e4    | 1         | 0.57%   |
| 0x306d4    | 1         | 0.57%   |
| 0x20655    | 1         | 0.57%   |
| 0x106c2    | 1         | 0.57%   |
| 0x106a5    | 1         | 0.57%   |
| 0x0a601201 | 1         | 0.57%   |
| 0x0a404102 | 1         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 3            | 23        | 13.45%  |
| Unknown          | 22        | 12.87%  |
| Zen 2            | 16        | 9.36%   |
| KabyLake         | 14        | 8.19%   |
| Alderlake Hybrid | 11        | 6.43%   |
| IvyBridge        | 10        | 5.85%   |
| Zen+             | 8         | 4.68%   |
| TigerLake        | 8         | 4.68%   |
| Haswell          | 8         | 4.68%   |
| CometLake        | 7         | 4.09%   |
| Skylake          | 6         | 3.51%   |
| SandyBridge      | 6         | 3.51%   |
| Icelake          | 6         | 3.51%   |
| Bonnell          | 6         | 3.51%   |
| K10              | 4         | 2.34%   |
| Broadwell        | 3         | 1.75%   |
| Zen              | 2         | 1.17%   |
| Westmere         | 2         | 1.17%   |
| P6               | 2         | 1.17%   |
| Piledriver       | 1         | 0.58%   |
| Penryn           | 1         | 0.58%   |
| NetBurst         | 1         | 0.58%   |
| Nehalem          | 1         | 0.58%   |
| Jaguar           | 1         | 0.58%   |
| Goldmont plus    | 1         | 0.58%   |
| Bulldozer        | 1         | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| AMD                        | 74        | 35.92%  |
| Nvidia                     | 66        | 32.04%  |
| Intel                      | 57        | 27.67%  |
| ASPEED Technology          | 5         | 2.43%   |
| Matrox Electronics Systems | 4         | 1.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Raphael                                                                   | 10        | 4.46%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 9         | 4.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 3.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 7         | 3.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 6         | 2.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6         | 2.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 5         | 2.23%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 5         | 2.23%   |
| ASPEED Technology ASPEED Graphics Family                                      | 5         | 2.23%   |
| AMD Renoir                                                                    | 5         | 2.23%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                            | 4         | 1.79%   |
| Intel HD Graphics 530                                                         | 4         | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 1.79%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                      | 4         | 1.79%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 4         | 1.79%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 4         | 1.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 1.34%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                    | 3         | 1.34%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 3         | 1.34%   |
| Nvidia AD102 [GeForce RTX 4090]                                               | 3         | 1.34%   |
| Matrox Electronics Systems MGA G200EH                                         | 3         | 1.34%   |
| Intel HD Graphics 630                                                         | 3         | 1.34%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 1.34%   |
| AMD Rembrandt [Radeon 680M]                                                   | 3         | 1.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.34%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 3         | 1.34%   |
| AMD Lucienne                                                                  | 3         | 1.34%   |
| Nvidia TU117M [GeForce MX450]                                                 | 2         | 0.89%   |
| Nvidia GT218 [GeForce 210]                                                    | 2         | 0.89%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 2         | 0.89%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 2         | 0.89%   |
| Nvidia GA106 [Geforce RTX 3050]                                               | 2         | 0.89%   |
| Nvidia GA104GLM [RTX A3000 12GB Laptop GPU]                                   | 2         | 0.89%   |
| Nvidia C79 [ION]                                                              | 2         | 0.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 2         | 0.89%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 0.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 0.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 0.89%   |
| AMD RS780C [Radeon 3100]                                                      | 2         | 0.89%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                    | 2         | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 50        | 28.57%  |
| 1 x Nvidia     | 34        | 19.43%  |
| 1 x Intel      | 28        | 16%     |
| Intel + Nvidia | 22        | 12.57%  |
| 2 x AMD        | 13        | 7.43%   |
| AMD + Nvidia   | 11        | 6.29%   |
| 1 x ASPEED     | 5         | 2.86%   |
| 2 x Intel      | 4         | 2.29%   |
| 1 x Matrox     | 4         | 2.29%   |
| Intel + AMD    | 3         | 1.71%   |
| Other          | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 119       | 68.79%  |
| Proprietary | 39        | 22.54%  |
| Unknown     | 15        | 8.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 39.31%  |
| 8.01-16.0  | 21        | 12.14%  |
| 7.01-8.0   | 19        | 10.98%  |
| 0.01-0.5   | 16        | 9.25%   |
| 0.51-1.0   | 14        | 8.09%   |
| 1.01-2.0   | 12        | 6.94%   |
| 3.01-4.0   | 11        | 6.36%   |
| 16.01-24.0 | 6         | 3.47%   |
| 5.01-6.0   | 5         | 2.89%   |
| 2.01-3.0   | 1         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 23        | 12.57%  |
| Dell                    | 14        | 7.65%   |
| Chimei Innolux          | 13        | 7.1%    |
| BOE                     | 13        | 7.1%    |
| AU Optronics            | 13        | 7.1%    |
| ASUSTek Computer        | 10        | 5.46%   |
| Goldstar                | 9         | 4.92%   |
| BenQ                    | 8         | 4.37%   |
| AOC                     | 8         | 4.37%   |
| LG Display              | 7         | 3.83%   |
| Sharp                   | 5         | 2.73%   |
| Acer                    | 5         | 2.73%   |
| Hewlett-Packard         | 4         | 2.19%   |
| Eizo                    | 4         | 2.19%   |
| Ancor Communications    | 4         | 2.19%   |
| Unknown                 | 3         | 1.64%   |
| PANDA                   | 3         | 1.64%   |
| Lenovo                  | 3         | 1.64%   |
| Gigabyte Technology     | 3         | 1.64%   |
| Philips                 | 2         | 1.09%   |
| Iiyama                  | 2         | 1.09%   |
| Chi Mei Optoelectronics | 2         | 1.09%   |
| BOE Technology Group    | 2         | 1.09%   |
| Unknown                 | 2         | 1.09%   |
| Vizio                   | 1         | 0.55%   |
| Valve                   | 1         | 0.55%   |
| TMX                     | 1         | 0.55%   |
| Sony                    | 1         | 0.55%   |
| Sceptre Tech            | 1         | 0.55%   |
| Onkyo                   | 1         | 0.55%   |
| MStar                   | 1         | 0.55%   |
| Microstep               | 1         | 0.55%   |
| InfoVision              | 1         | 0.55%   |
| Idek Iiyama             | 1         | 0.55%   |
| IBM                     | 1         | 0.55%   |
| HJW                     | 1         | 0.55%   |
| Gateway                 | 1         | 0.55%   |
| Envision Peripherals    | 1         | 0.55%   |
| ELSA                    | 1         | 0.55%   |
| Denver                  | 1         | 0.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch            | 3         | 1.55%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 2         | 1.03%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch    | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SAM7003 3840x2160 1872x1053mm 84.6-inch | 2         | 1.03%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 2         | 1.03%   |
| Gigabyte Technology G27FC A GBT2715 1920x1080 598x336mm 27.0-inch       | 2         | 1.03%   |
| Eizo CS2731 ENC3069 2560x1440 597x336mm 27.0-inch                       | 2         | 1.03%   |
| BOE Technology Group LCD Monitor 1920x1080                              | 2         | 1.03%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                   | 2         | 1.03%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                      | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch          | 2         | 1.03%   |
| AOC LCD Monitor U2879G6 3840x2160                                       | 2         | 1.03%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                      | 2         | 1.03%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                        | 2         | 1.03%   |
| Acer ED320QR S ACR0805 1920x1080 609x348mm 27.6-inch                    | 2         | 1.03%   |
| Unknown                                                                 | 2         | 1.03%   |
| Vizio D43n-E1 VIZ1009 1920x1080 953x543mm 43.2-inch                     | 1         | 0.52%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 1         | 0.52%   |
| Unknown LCD Monitor RTK                                                 | 1         | 0.52%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 0.52%   |
| Sony BW8 MS_9001 2560x1600                                              | 1         | 0.52%   |
| Sharp LQ173M1JW03 SHP14DC 1920x1080 382x215mm 17.3-inch                 | 1         | 0.52%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                 | 1         | 0.52%   |
| Sharp LQ135P1JX51 SHP14B3 2256x1504 285x190mm 13.5-inch                 | 1         | 0.52%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch                 | 1         | 0.52%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                 | 1         | 0.52%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch         | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM05E8 1920x1080                        | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch    | 1         | 0.52%   |
| Samsung Electronics SMT23A350 SAM07A7 1920x1080 510x287mm 23.0-inch     | 1         | 0.52%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch     | 1         | 0.52%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch    | 1         | 0.52%   |
| Samsung Electronics SME2020N SAM06A6 1600x900 443x249mm 20.0-inch       | 1         | 0.52%   |
| Samsung Electronics S27E390 SAM0C1C 1920x1080 598x336mm 27.0-inch       | 1         | 0.52%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch       | 1         | 0.52%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch       | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4179 2560x1440 344x194mm 15.5-inch   | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch   | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch   | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 73        | 41.48%  |
| 3840x2160 (4K)     | 27        | 15.34%  |
| 2560x1440 (QHD)    | 23        | 13.07%  |
| 3440x1440          | 7         | 3.98%   |
| 2560x1600          | 4         | 2.27%   |
| 1920x1200 (WUXGA)  | 4         | 2.27%   |
| 1600x900 (HD+)     | 4         | 2.27%   |
| 1366x768 (WXGA)    | 4         | 2.27%   |
| 3840x1080          | 3         | 1.7%    |
| Unknown            | 3         | 1.7%    |
| 2560x1080          | 2         | 1.14%   |
| 2288x1287          | 2         | 1.14%   |
| 1680x1050 (WSXGA+) | 2         | 1.14%   |
| 1440x900 (WXGA+)   | 2         | 1.14%   |
| 1280x1024 (SXGA)   | 2         | 1.14%   |
| 1024x768 (XGA)     | 2         | 1.14%   |
| 800x1280           | 1         | 0.57%   |
| 3840x1200          | 1         | 0.57%   |
| 3456x2160          | 1         | 0.57%   |
| 3200x2000          | 1         | 0.57%   |
| 2520x1680          | 1         | 0.57%   |
| 2256x1504          | 1         | 0.57%   |
| 2160x1440          | 1         | 0.57%   |
| 1920x540           | 1         | 0.57%   |
| 1600x1200          | 1         | 0.57%   |
| 1360x768           | 1         | 0.57%   |
| 1280x800 (WXGA)    | 1         | 0.57%   |
| 1024x600           | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 27      | 31        | 16.85%  |
| 15      | 27        | 14.67%  |
| Unknown | 15        | 8.15%   |
| 24      | 12        | 6.52%   |
| 17      | 12        | 6.52%   |
| 13      | 12        | 6.52%   |
| 23      | 11        | 5.98%   |
| 14      | 10        | 5.43%   |
| 21      | 8         | 4.35%   |
| 34      | 7         | 3.8%    |
| 31      | 7         | 3.8%    |
| 16      | 5         | 2.72%   |
| 84      | 3         | 1.63%   |
| 32      | 3         | 1.63%   |
| 142     | 2         | 1.09%   |
| 25      | 2         | 1.09%   |
| 22      | 2         | 1.09%   |
| 19      | 2         | 1.09%   |
| 49      | 1         | 0.54%   |
| 48      | 1         | 0.54%   |
| 43      | 1         | 0.54%   |
| 41      | 1         | 0.54%   |
| 40      | 1         | 0.54%   |
| 35      | 1         | 0.54%   |
| 29      | 1         | 0.54%   |
| 26      | 1         | 0.54%   |
| 20      | 1         | 0.54%   |
| 12      | 1         | 0.54%   |
| 10      | 1         | 0.54%   |
| 8       | 1         | 0.54%   |
| 7       | 1         | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 501-600        | 48        | 27.27%  |
| 301-350        | 48        | 27.27%  |
| Unknown        | 15        | 8.52%   |
| 401-500        | 12        | 6.82%   |
| 351-400        | 11        | 6.25%   |
| 701-800        | 10        | 5.68%   |
| 601-700        | 10        | 5.68%   |
| 201-300        | 9         | 5.11%   |
| 1501-2000      | 3         | 1.7%    |
| More than 2000 | 2         | 1.14%   |
| 801-900        | 2         | 1.14%   |
| 1001-1500      | 2         | 1.14%   |
| 901-1000       | 2         | 1.14%   |
| 101-200        | 1         | 0.57%   |
| 1-100          | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 113       | 68.9%   |
| 16/10   | 17        | 10.37%  |
| Unknown | 11        | 6.71%   |
| 21/9    | 8         | 4.88%   |
| 4/3     | 3         | 1.83%   |
| 32/9    | 3         | 1.83%   |
| 3/2     | 3         | 1.83%   |
| 5/4     | 2         | 1.22%   |
| 1.00    | 2         | 1.22%   |
| 0.67    | 1         | 0.61%   |
| 0.62    | 1         | 0.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 32        | 17.78%  |
| 101-110        | 28        | 15.56%  |
| 201-250        | 24        | 13.33%  |
| 351-500        | 18        | 10%     |
| 81-90          | 17        | 9.44%   |
| Unknown        | 15        | 8.33%   |
| 121-130        | 10        | 5.56%   |
| 251-300        | 6         | 3.33%   |
| More than 1000 | 5         | 2.78%   |
| 71-80          | 5         | 2.78%   |
| 501-1000       | 5         | 2.78%   |
| 151-200        | 4         | 2.22%   |
| 111-120        | 4         | 2.22%   |
| 1-40           | 2         | 1.11%   |
| 141-150        | 2         | 1.11%   |
| 61-70          | 1         | 0.56%   |
| 41-50          | 1         | 0.56%   |
| 91-100         | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 50        | 28.25%  |
| 121-160       | 45        | 25.42%  |
| 101-120       | 34        | 19.21%  |
| 161-240       | 22        | 12.43%  |
| Unknown       | 15        | 8.47%   |
| More than 240 | 7         | 3.95%   |
| 1-50          | 4         | 2.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 127       | 72.57%  |
| 2     | 25        | 14.29%  |
| 0     | 15        | 8.57%   |
| 3     | 7         | 4%      |
| 4     | 1         | 0.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 104       | 40.31%  |
| Realtek Semiconductor           | 88        | 34.11%  |
| MediaTek                        | 13        | 5.04%   |
| Qualcomm Atheros                | 10        | 3.88%   |
| Broadcom                        | 9         | 3.49%   |
| Xiaomi                          | 4         | 1.55%   |
| Broadcom Limited                | 3         | 1.16%   |
| ASIX Electronics                | 3         | 1.16%   |
| Qualcomm Atheros Communications | 2         | 0.78%   |
| Qualcomm                        | 2         | 0.78%   |
| Microsoft                       | 2         | 0.78%   |
| ICS Advent                      | 2         | 0.78%   |
| Aquantia                        | 2         | 0.78%   |
| Sierra Wireless                 | 1         | 0.39%   |
| Ralink                          | 1         | 0.39%   |
| OpenMoko                        | 1         | 0.39%   |
| Nvidia                          | 1         | 0.39%   |
| NetGear                         | 1         | 0.39%   |
| Mellanox Technologies           | 1         | 0.39%   |
| Marvell Technology Group        | 1         | 0.39%   |
| Lenovo                          | 1         | 0.39%   |
| Insyde Software                 | 1         | 0.39%   |
| Huawei Technologies             | 1         | 0.39%   |
| Hewlett-Packard                 | 1         | 0.39%   |
| Edimax Technology               | 1         | 0.39%   |
| Dell                            | 1         | 0.39%   |
| Arduino SA                      | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 55        | 17.63%  |
| Intel Wi-Fi 6 AX200                                                     | 20        | 6.41%   |
| Realtek RTL8125 2.5GbE Controller                                       | 18        | 5.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 16        | 5.13%   |
| Intel I211 Gigabit Network Connection                                   | 13        | 4.17%   |
| Intel Ethernet Controller I225-V                                        | 13        | 4.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.6%    |
| Intel Wireless-AC 9260                                                  | 5         | 1.6%    |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 1.28%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.28%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 1.28%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.28%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 4         | 1.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 1.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 0.96%   |
| Intel Wireless 8260                                                     | 3         | 0.96%   |
| Intel Ethernet Connection (7) I219-V                                    | 3         | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 0.96%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.96%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                        | 3         | 0.96%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 2         | 0.64%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.64%   |
| Microsoft XBOX ACC                                                      | 2         | 0.64%   |
| Intel I350 Gigabit Network Connection                                   | 2         | 0.64%   |
| Intel Ethernet Connection I217-V                                        | 2         | 0.64%   |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                    | 2         | 0.64%   |
| Intel Ethernet Connection (17) I219-LM                                  | 2         | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.64%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                    | 2         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 58.27%  |
| Realtek Semiconductor           | 15        | 11.81%  |
| MediaTek                        | 13        | 10.24%  |
| Qualcomm Atheros                | 8         | 6.3%    |
| Broadcom Limited                | 3         | 2.36%   |
| Broadcom                        | 3         | 2.36%   |
| Qualcomm Atheros Communications | 2         | 1.57%   |
| Qualcomm                        | 2         | 1.57%   |
| Microsoft                       | 2         | 1.57%   |
| Sierra Wireless                 | 1         | 0.79%   |
| Ralink                          | 1         | 0.79%   |
| NetGear                         | 1         | 0.79%   |
| Edimax Technology               | 1         | 0.79%   |
| Dell                            | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 20        | 15.63%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 16        | 12.5%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 3.91%   |
| Intel Wireless-AC 9260                                                  | 5         | 3.91%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 3.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 3.13%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 3.13%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.13%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 4         | 3.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 3.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 2.34%   |
| Intel Wireless 8260                                                     | 3         | 2.34%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 2.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.34%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 1.56%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 1.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.56%   |
| Microsoft XBOX ACC                                                      | 2         | 1.56%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.56%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.78%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 0.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.78%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                  | 1         | 0.78%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.78%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.78%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.78%   |
| NetGear WNDA3100v2 802.11abgn [Broadcom BCM4323]                        | 1         | 0.78%   |
| Intel Wireless 7265                                                     | 1         | 0.78%   |
| Intel Wireless 7260                                                     | 1         | 0.78%   |
| Intel Wireless 3165                                                     | 1         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.78%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 82        | 47.95%  |
| Intel                    | 63        | 36.84%  |
| Broadcom                 | 6         | 3.51%   |
| Xiaomi                   | 4         | 2.34%   |
| Qualcomm Atheros         | 4         | 2.34%   |
| ASIX Electronics         | 3         | 1.75%   |
| ICS Advent               | 2         | 1.17%   |
| Aquantia                 | 2         | 1.17%   |
| Nvidia                   | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| Lenovo                   | 1         | 0.58%   |
| Insyde Software          | 1         | 0.58%   |
| Hewlett-Packard          | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 55        | 30.56%  |
| Realtek RTL8125 2.5GbE Controller                                     | 18        | 10%     |
| Intel I211 Gigabit Network Connection                                 | 13        | 7.22%   |
| Intel Ethernet Controller I225-V                                      | 13        | 7.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 6         | 3.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 4         | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 4         | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 3         | 1.67%   |
| Intel Ethernet Connection (7) I219-V                                  | 3         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                                 | 3         | 1.67%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 3         | 1.67%   |
| Realtek Killer E3000 2.5GbE Controller                                | 2         | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 2         | 1.11%   |
| Intel I350 Gigabit Network Connection                                 | 2         | 1.11%   |
| Intel Ethernet Connection I217-V                                      | 2         | 1.11%   |
| Intel Ethernet Connection (5) I219-LM                                 | 2         | 1.11%   |
| Intel Ethernet Connection (2) I219-V                                  | 2         | 1.11%   |
| Intel Ethernet Connection (17) I219-LM                                | 2         | 1.11%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 2         | 1.11%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 2         | 1.11%   |
| ASIX AX88179 Gigabit Ethernet                                         | 2         | 1.11%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                       | 1         | 0.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                            | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                 | 1         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                              | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                                 | 1         | 0.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller               | 1         | 0.56%   |
| Lenovo USB-C Dock Ethernet                                            | 1         | 0.56%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                   | 1         | 0.56%   |
| Intel I210 Gigabit Network Connection                                 | 1         | 0.56%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                         | 1         | 0.56%   |
| Intel Ethernet Controller I226-V                                      | 1         | 0.56%   |
| Intel Ethernet Controller (2) I225-LMvP                               | 1         | 0.56%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                      | 1         | 0.56%   |
| Intel Ethernet Connection I219-V                                      | 1         | 0.56%   |
| Intel Ethernet Connection I217-LM                                     | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection (16) I219-LM                                | 1         | 0.56%   |
| Intel Ethernet Connection (13) I219-LM                                | 1         | 0.56%   |
| Intel Ethernet Connection (11) I219-LM                                | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 153       | 55.23%  |
| WiFi     | 120       | 43.32%  |
| Modem    | 3         | 1.08%   |
| Unknown  | 1         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 104       | 59.43%  |
| WiFi     | 71        | 40.57%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 90        | 52.02%  |
| 1     | 62        | 35.84%  |
| 3     | 12        | 6.94%   |
| 7     | 2         | 1.16%   |
| 6     | 2         | 1.16%   |
| 4     | 2         | 1.16%   |
| 0     | 2         | 1.16%   |
| 5     | 1         | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 118       | 68.21%  |
| Yes  | 55        | 31.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 59.82%  |
| Realtek Semiconductor           | 10        | 8.93%   |
| MediaTek                        | 7         | 6.25%   |
| IMC Networks                    | 6         | 5.36%   |
| Foxconn / Hon Hai               | 4         | 3.57%   |
| Lite-On Technology              | 3         | 2.68%   |
| Cambridge Silicon Radio         | 3         | 2.68%   |
| Broadcom                        | 3         | 2.68%   |
| USI                             | 2         | 1.79%   |
| Realtek                         | 2         | 1.79%   |
| Qualcomm Atheros Communications | 1         | 0.89%   |
| Dell                            | 1         | 0.89%   |
| ASUSTek Computer                | 1         | 0.89%   |
| Apple                           | 1         | 0.89%   |
| Alps Electric                   | 1         | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 20        | 17.86%  |
| Intel AX210 Bluetooth                               | 13        | 11.61%  |
| Intel Bluetooth wireless interface                  | 10        | 8.93%   |
| Realtek Bluetooth Radio                             | 9         | 8.04%   |
| Intel Bluetooth Device                              | 8         | 7.14%   |
| MediaTek Wireless_Device                            | 7         | 6.25%   |
| Intel AX201 Bluetooth                               | 7         | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 4.46%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 3.57%   |
| IMC Networks Wireless_Device                        | 4         | 3.57%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 2.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.68%   |
| USI Bluetooth Device                                | 2         | 1.79%   |
| Realtek Bluetooth Radio                             | 2         | 1.79%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.79%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.79%   |
| Realtek Bluetooth 5.1 Radio                         | 1         | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.89%   |
| Lite-On Wireless_Device                             | 1         | 0.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.89%   |
| Lite-On Bluetooth Device                            | 1         | 0.89%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.89%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.89%   |
| Broadcom BCM20702A0                                 | 1         | 0.89%   |
| ASUS ASUS USB-BT500                                 | 1         | 0.89%   |
| Apple Bluetooth Host Controller                     | 1         | 0.89%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| AMD                                  | 81        | 29.24%  |
| Intel                                | 78        | 28.16%  |
| Nvidia                               | 55        | 19.86%  |
| ASUSTek Computer                     | 11        | 3.97%   |
| C-Media Electronics                  | 8         | 2.89%   |
| SteelSeries ApS                      | 3         | 1.08%   |
| Solid State Logic                    | 2         | 0.72%   |
| Razer USA                            | 2         | 0.72%   |
| Lenovo                               | 2         | 0.72%   |
| Kingston Technology                  | 2         | 0.72%   |
| Creative Labs                        | 2         | 0.72%   |
| Audient                              | 2         | 0.72%   |
| VIA Technologies                     | 1         | 0.36%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.36%   |
| Texas Instruments                    | 1         | 0.36%   |
| TEAC                                 | 1         | 0.36%   |
| Sony                                 | 1         | 0.36%   |
| Schiit Audio                         | 1         | 0.36%   |
| SAVITECH                             | 1         | 0.36%   |
| RODE Microphones                     | 1         | 0.36%   |
| Microsoft                            | 1         | 0.36%   |
| Micro Star International             | 1         | 0.36%   |
| Medeli Electronics                   | 1         | 0.36%   |
| MAG Technology                       | 1         | 0.36%   |
| M-Audio                              | 1         | 0.36%   |
| Logitech                             | 1         | 0.36%   |
| JMTek                                | 1         | 0.36%   |
| Huawei Technologies                  | 1         | 0.36%   |
| GYROCOM C&C                          | 1         | 0.36%   |
| Focusrite-Novation                   | 1         | 0.36%   |
| Elgato Systems                       | 1         | 0.36%   |
| DSEA A/S                             | 1         | 0.36%   |
| DCMT Technology                      | 1         | 0.36%   |
| Corsair                              | 1         | 0.36%   |
| BEHRINGER International              | 1         | 0.36%   |
| AudioQuest                           | 1         | 0.36%   |
| ASRock                               | 1         | 0.36%   |
| ARCAM                                | 1         | 0.36%   |
| Anlya.cn                             | 1         | 0.36%   |
| AKG C44-USB Microphone               | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 34        | 9.83%   |
| AMD Starship/Matisse HD Audio Controller                                   | 20        | 5.78%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 18        | 5.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 17        | 4.91%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 13        | 3.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 8         | 2.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 2.31%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 2.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 2.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 2.02%   |
| Nvidia TU104 HD Audio Controller                                           | 6         | 1.73%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 1.73%   |
| ASUSTek Computer USB Audio                                                 | 6         | 1.73%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5         | 1.45%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.45%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.45%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.45%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.16%   |
| Nvidia GA102 High Definition Audio Controller                              | 4         | 1.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.16%   |
| AMD Navi 31 [Radeon RX 7000 HDMI Audio]                                    | 4         | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.87%   |
| Nvidia AD102 High Definition Audio Controller                              | 3         | 0.87%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.87%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.87%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 0.87%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 0.87%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.58%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.58%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2         | 0.58%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.58%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.58%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 16.57%  |
| G.Skill             | 23        | 13.14%  |
| SK hynix            | 22        | 12.57%  |
| Corsair             | 21        | 12%     |
| Crucial             | 18        | 10.29%  |
| Micron Technology   | 16        | 9.14%   |
| Kingston            | 15        | 8.57%   |
| Unknown             | 14        | 8%      |
| Team                | 4         | 2.29%   |
| A-DATA Technology   | 3         | 1.71%   |
| Nanya Technology    | 2         | 1.14%   |
| Unknown (ABCD)      | 1         | 0.57%   |
| SGS/Thomson         | 1         | 0.57%   |
| Patriot Memory      | 1         | 0.57%   |
| Patriot             | 1         | 0.57%   |
| HPE                 | 1         | 0.57%   |
| Hewlett-Packard     | 1         | 0.57%   |
| GSkill              | 1         | 0.57%   |
| Elpida              | 1         | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 4         | 2.17%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s             | 4         | 2.17%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.63%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 3         | 1.63%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s             | 3         | 1.63%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3400MT/s         | 3         | 1.63%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2         | 1.09%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 2         | 1.09%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 2         | 1.09%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.09%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 2         | 1.09%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.09%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.09%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.09%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 1.09%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 2         | 1.09%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 1.09%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s            | 2         | 1.09%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.54%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.54%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.54%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                             | 1         | 0.54%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.54%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                          | 1         | 0.54%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.54%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 0.54%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 1         | 0.54%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.54%   |
| Team RAM Elite-800 2GB DIMM SDRAM 2048MT/s                       | 1         | 0.54%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.54%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.54%   |
| SK hynix RAM Module 16GB DIMM DDR4 2133MT/s                      | 1         | 0.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.54%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.54%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM DDR3 1067MT/s        | 1         | 0.54%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 85        | 52.47%  |
| DDR3    | 31        | 19.14%  |
| DDR5    | 24        | 14.81%  |
| LPDDR4  | 7         | 4.32%   |
| DDR2    | 7         | 4.32%   |
| Unknown | 3         | 1.85%   |
| SDRAM   | 2         | 1.23%   |
| LPDDR5  | 2         | 1.23%   |
| DDR     | 1         | 0.62%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 89        | 54.27%  |
| SODIMM       | 65        | 39.63%  |
| Row Of Chips | 10        | 6.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 57        | 33.53%  |
| 16384 | 51        | 30%     |
| 32768 | 25        | 14.71%  |
| 4096  | 21        | 12.35%  |
| 2048  | 12        | 7.06%   |
| 1024  | 3         | 1.76%   |
| 512   | 1         | 0.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 32        | 18.82%  |
| 1600    | 20        | 11.76%  |
| 2667    | 14        | 8.24%   |
| 3600    | 12        | 7.06%   |
| 4800    | 11        | 6.47%   |
| 6400    | 8         | 4.71%   |
| 2400    | 7         | 4.12%   |
| 4267    | 6         | 3.53%   |
| 1333    | 6         | 3.53%   |
| 6000    | 4         | 2.35%   |
| 3400    | 4         | 2.35%   |
| 2133    | 4         | 2.35%   |
| 1866    | 4         | 2.35%   |
| 667     | 4         | 2.35%   |
| 3866    | 3         | 1.76%   |
| 3666    | 3         | 1.76%   |
| 800     | 3         | 1.76%   |
| 5200    | 2         | 1.18%   |
| 3800    | 2         | 1.18%   |
| 3466    | 2         | 1.18%   |
| 2666    | 2         | 1.18%   |
| 2048    | 2         | 1.18%   |
| 1334    | 2         | 1.18%   |
| Unknown | 2         | 1.18%   |
| 5600    | 1         | 0.59%   |
| 3933    | 1         | 0.59%   |
| 3733    | 1         | 0.59%   |
| 3534    | 1         | 0.59%   |
| 3533    | 1         | 0.59%   |
| 3100    | 1         | 0.59%   |
| 2933    | 1         | 0.59%   |
| 1067    | 1         | 0.59%   |
| 1066    | 1         | 0.59%   |
| 533     | 1         | 0.59%   |
| 333     | 1         | 0.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 25%     |
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-4200 Series | 1         | 25%     |
| Samsung ML-1630 Series     | 1         | 25%     |
| HP LaserJet M14-M17        | 1         | 25%     |
| Brother MFC-9340CDW        | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 1         | 50%     |
| AGFA-Gevaert NV | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |
| AGFA-Gevaert NV SnapScan e20  | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 20        | 24.1%   |
| Microdia                      | 11        | 13.25%  |
| Logitech                      | 8         | 9.64%   |
| Quanta                        | 6         | 7.23%   |
| Sunplus Innovation Technology | 5         | 6.02%   |
| Luxvisions Innotech Limited   | 5         | 6.02%   |
| Microsoft                     | 4         | 4.82%   |
| IMC Networks                  | 3         | 3.61%   |
| Bison Electronics             | 3         | 3.61%   |
| Samsung Electronics           | 2         | 2.41%   |
| MacroSilicon                  | 2         | 2.41%   |
| Apple                         | 2         | 2.41%   |
| Acer                          | 2         | 2.41%   |
| SunplusIT                     | 1         | 1.2%    |
| Sunplus Technology            | 1         | 1.2%    |
| ShineTech                     | 1         | 1.2%    |
| Realtek Semiconductor         | 1         | 1.2%    |
| Lite-On Technology            | 1         | 1.2%    |
| Holitech                      | 1         | 1.2%    |
| Genesys Logic                 | 1         | 1.2%    |
| GEMBIRD                       | 1         | 1.2%    |
| Elgato Systems                | 1         | 1.2%    |
| A4Tech                        | 1         | 1.2%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 8         | 9.64%   |
| Microdia Integrated_Webcam_HD                        | 3         | 3.61%   |
| Logitech C922 Pro Stream Webcam                      | 3         | 3.61%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 2.41%   |
| Quanta HD User Facing                                | 2         | 2.41%   |
| Microdia Integrated_Webcam_FHD                       | 2         | 2.41%   |
| Microdia CameraA                                     | 2         | 2.41%   |
| MacroSilicon usb video                               | 2         | 2.41%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 2         | 2.41%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 2.41%   |
| Logitech HD Pro Webcam C920                          | 2         | 2.41%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 2         | 2.41%   |
| Chicony HP HD Camera                                 | 2         | 2.41%   |
| Chicony HD WebCam                                    | 2         | 2.41%   |
| Bison Integrated Camera                              | 2         | 2.41%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 2         | 2.41%   |
| SunplusIT 720p HD Camera                             | 1         | 1.2%    |
| Sunplus 1.3M HD WebCam                               | 1         | 1.2%    |
| Sunplus XiaoMi USB 2.0 Webcam                        | 1         | 1.2%    |
| Sunplus MiraBox Video Capture                        | 1         | 1.2%    |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.2%    |
| Sunplus Integrated_Webcam_FHD                        | 1         | 1.2%    |
| Sunplus Aoni FHD Camera                              | 1         | 1.2%    |
| ShineTech HD Camera                                  | 1         | 1.2%    |
| Realtek Integrated_Webcam_HD                         | 1         | 1.2%    |
| Quanta VGA WebCam                                    | 1         | 1.2%    |
| Quanta RGB-IR Camera                                 | 1         | 1.2%    |
| Quanta HP TrueVision HD Camera                       | 1         | 1.2%    |
| Quanta hm1091_techfront                              | 1         | 1.2%    |
| Microsoft Surface Camera Front                       | 1         | 1.2%    |
| Microsoft MicrosoftÂ LifeCam Studio                 | 1         | 1.2%    |
| Microsoft MicrosoftÂ LifeCam Cinema                 | 1         | 1.2%    |
| Microsoft LifeCam Cinema                             | 1         | 1.2%    |
| Microdia Sonix USB 2.0 Camera                        | 1         | 1.2%    |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam       | 1         | 1.2%    |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.2%    |
| Microdia Camera                                      | 1         | 1.2%    |
| Luxvisions Innotech Limited Integrated Camera        | 1         | 1.2%    |
| Logitech Webcam C270                                 | 1         | 1.2%    |
| Logitech BRIO Ultra HD Webcam                        | 1         | 1.2%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 35.29%  |
| Validity Sensors           | 5         | 29.41%  |
| Shenzhen Goodix Technology | 5         | 29.41%  |
| LighTuning Technology      | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                        | 4         | 23.53%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 11.76%  |
| Validity Sensors Synaptics WBDI                            | 2         | 11.76%  |
| Synaptics UWP WBDI Device                                  | 2         | 11.76%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 11.76%  |
| Validity Sensors VFS491                                    | 1         | 5.88%   |
| Synaptics WBDI                                             | 1         | 5.88%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 5.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 5         | 35.71%  |
| Alcor Micro                       | 2         | 14.29%  |
| SCM Microsystems                  | 1         | 7.14%   |
| O2 Micro                          | 1         | 7.14%   |
| Hewlett-Packard                   | 1         | 7.14%   |
| Free Software Initiative of Japan | 1         | 7.14%   |
| Clay Logic                        | 1         | 7.14%   |
| Bit4id                            | 1         | 7.14%   |
| Advanced Card Systems             | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 3         | 21.43%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 14.29%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 7.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.14%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 7.14%   |
| Free Software Initiative of Japan Gnuk Token                                 | 1         | 7.14%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 7.14%   |
| Broadcom 5880                                                                | 1         | 7.14%   |
| Bit4id miniLector-s                                                          | 1         | 7.14%   |
| Advanced Card Systems ACR122U                                                | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 84        | 47.19%  |
| 1     | 48        | 26.97%  |
| 2     | 20        | 11.24%  |
| 3     | 12        | 6.74%   |
| 4     | 7         | 3.93%   |
| 6     | 4         | 2.25%   |
| 5     | 2         | 1.12%   |
| 7     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 29        | 17.68%  |
| Bluetooth                | 22        | 13.41%  |
| Communication controller | 18        | 10.98%  |
| Net/wireless             | 17        | 10.37%  |
| Fingerprint reader       | 16        | 9.76%   |
| Camera                   | 14        | 8.54%   |
| Multimedia controller    | 9         | 5.49%   |
| Chipcard                 | 9         | 5.49%   |
| Sound                    | 8         | 4.88%   |
| Network                  | 5         | 3.05%   |
| Net/ethernet             | 4         | 2.44%   |
| Storage/ide              | 3         | 1.83%   |
| Firewire controller      | 3         | 1.83%   |
| Card reader              | 3         | 1.83%   |
| Storage/ata              | 2         | 1.22%   |
| Unassigned class         | 1         | 0.61%   |
| Storage/raid             | 1         | 0.61%   |

