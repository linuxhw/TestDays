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

Total: 346

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 16 5625            | Notebook    | [bf36f89d32](https://linux-hardware.org/?probe=bf36f89d32) | Jul 01, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [af8af2c7e8](https://linux-hardware.org/?probe=af8af2c7e8) | Jun 30, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [cbbe256fa2](https://linux-hardware.org/?probe=cbbe256fa2) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [4df7190c46](https://linux-hardware.org/?probe=4df7190c46) | Jun 29, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [6388cc47ae](https://linux-hardware.org/?probe=6388cc47ae) | Jun 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [2d16f5be74](https://linux-hardware.org/?probe=2d16f5be74) | Jun 29, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c7a5d0ef6c](https://linux-hardware.org/?probe=c7a5d0ef6c) | Jun 29, 2023 |
| Intel         | NUC11PABi5 M68265-501       | Mini pc     | [b6c0bd1df6](https://linux-hardware.org/?probe=b6c0bd1df6) | Jun 28, 2023 |
| Intel         | NUC11PABi5 M68265-501       | Mini pc     | [498d9375d4](https://linux-hardware.org/?probe=498d9375d4) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [8619447305](https://linux-hardware.org/?probe=8619447305) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [bddefdfb2c](https://linux-hardware.org/?probe=bddefdfb2c) | Jun 27, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [d675031e74](https://linux-hardware.org/?probe=d675031e74) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [178ed56625](https://linux-hardware.org/?probe=178ed56625) | Jun 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e55023fb8b](https://linux-hardware.org/?probe=e55023fb8b) | Jun 26, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0b72aec1b9](https://linux-hardware.org/?probe=0b72aec1b9) | Jun 26, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [37e828b0b6](https://linux-hardware.org/?probe=37e828b0b6) | Jun 24, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [e1678729ff](https://linux-hardware.org/?probe=e1678729ff) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [094d8e8ecf](https://linux-hardware.org/?probe=094d8e8ecf) | Jun 22, 2023 |
| ASRock        | J3160M                      | Desktop     | [0521c9a5a7](https://linux-hardware.org/?probe=0521c9a5a7) | Jun 22, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a013e4866a](https://linux-hardware.org/?probe=a013e4866a) | Jun 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [12153cd235](https://linux-hardware.org/?probe=12153cd235) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6c766e53cb](https://linux-hardware.org/?probe=6c766e53cb) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [91e2324734](https://linux-hardware.org/?probe=91e2324734) | Jun 20, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [cd78108f1f](https://linux-hardware.org/?probe=cd78108f1f) | Jun 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [e65deab189](https://linux-hardware.org/?probe=e65deab189) | Jun 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [22d8476417](https://linux-hardware.org/?probe=22d8476417) | Jun 19, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e2fc6bb607](https://linux-hardware.org/?probe=e2fc6bb607) | Jun 19, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4d509da42f](https://linux-hardware.org/?probe=4d509da42f) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [8e26542f2d](https://linux-hardware.org/?probe=8e26542f2d) | Jun 17, 2023 |
| HP            | ENVY m6                     | Notebook    | [2776e20c0a](https://linux-hardware.org/?probe=2776e20c0a) | Jun 17, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [eb29f214f3](https://linux-hardware.org/?probe=eb29f214f3) | Jun 17, 2023 |
| Dell          | Precision 5530              | Notebook    | [29ec4c7e1d](https://linux-hardware.org/?probe=29ec4c7e1d) | Jun 16, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1f5163e415](https://linux-hardware.org/?probe=1f5163e415) | Jun 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7e699d65f7](https://linux-hardware.org/?probe=7e699d65f7) | Jun 16, 2023 |
| Dell          | Precision 5530              | Notebook    | [cff5125fb6](https://linux-hardware.org/?probe=cff5125fb6) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a7728ed657](https://linux-hardware.org/?probe=a7728ed657) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [03c8eed64b](https://linux-hardware.org/?probe=03c8eed64b) | Jun 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [ec46ef5f36](https://linux-hardware.org/?probe=ec46ef5f36) | Jun 15, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [9b08f8189d](https://linux-hardware.org/?probe=9b08f8189d) | Jun 15, 2023 |
| Google        | Nightfury                   | Notebook    | [02badb166b](https://linux-hardware.org/?probe=02badb166b) | Jun 14, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [deeef80345](https://linux-hardware.org/?probe=deeef80345) | Jun 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ad01f2c38d](https://linux-hardware.org/?probe=ad01f2c38d) | Jun 13, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [fc0318992c](https://linux-hardware.org/?probe=fc0318992c) | Jun 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [273795ce3d](https://linux-hardware.org/?probe=273795ce3d) | Jun 12, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8a9a32ba11](https://linux-hardware.org/?probe=8a9a32ba11) | Jun 12, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [272de7ad6b](https://linux-hardware.org/?probe=272de7ad6b) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [153ae28a9e](https://linux-hardware.org/?probe=153ae28a9e) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [6f6440cf1e](https://linux-hardware.org/?probe=6f6440cf1e) | Jun 10, 2023 |
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
| 6.1.19-gentoo-x86_64    | 14        | 6.42%   |
| 6.1.19-gentoo           | 13        | 5.96%   |
| 6.1.12-gentoo           | 10        | 4.59%   |
| 6.1.12-gentoo-x86_64    | 7         | 3.21%   |
| 6.1.28-gentoo           | 6         | 2.75%   |
| 6.2.11-gentoo           | 5         | 2.29%   |
| 6.1.31-gentoo-x86_64    | 5         | 2.29%   |
| 6.1.22-gentoo-dist      | 5         | 2.29%   |
| 6.3.4-gentoo            | 4         | 1.83%   |
| 6.3.1-gentoo            | 4         | 1.83%   |
| 6.3.0-gentoo            | 4         | 1.83%   |
| 6.2.8-gentoo-x86_64     | 4         | 1.83%   |
| 6.2.11-gentoo-x86_64    | 4         | 1.83%   |
| 6.1.31-gentoo-dist      | 4         | 1.83%   |
| 6.1.12-gentoo-dist      | 4         | 1.83%   |
| 6.3.8-gentoo-dist       | 3         | 1.38%   |
| 6.2.2-gentoo            | 3         | 1.38%   |
| 6.1.27-gentoo-r1-x86_64 | 3         | 1.38%   |
| 6.1.24-gentoo-dist      | 3         | 1.38%   |
| 6.1.19-gentoo-dist      | 3         | 1.38%   |
| 6.3.8-gentoo            | 2         | 0.92%   |
| 6.3.3-gentoo            | 2         | 0.92%   |
| 6.2.9-gentoo-x86_64     | 2         | 0.92%   |
| 6.2.3-gentoo            | 2         | 0.92%   |
| 6.2.12-gentoo-x86_64    | 2         | 0.92%   |
| 6.2.1-gentoo-x86_64     | 2         | 0.92%   |
| 6.2.0                   | 2         | 0.92%   |
| 6.1.9-gentoo-x86_64     | 2         | 0.92%   |
| 6.1.9-gentoo-dist       | 2         | 0.92%   |
| 6.1.31-gentoo           | 2         | 0.92%   |
| 6.1.27-gentoo-dist      | 2         | 0.92%   |
| 6.1.10-gentoo-x86_64    | 2         | 0.92%   |
| 6.4.0-rc2-x86_64        | 1         | 0.46%   |
| 6.4.0-gentoo            | 1         | 0.46%   |
| 6.3.7-gentoo_ap         | 1         | 0.46%   |
| 6.3.6-gentoo-dist       | 1         | 0.46%   |
| 6.3.5-ivybridge-xanmod1 | 1         | 0.46%   |
| 6.3.5-gentoo-x86_64     | 1         | 0.46%   |
| 6.3.4-gentoo-r1         | 1         | 0.46%   |
| 6.3.4-gentoo-dist       | 1         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.19  | 35        | 16.06%  |
| 6.1.12  | 24        | 11.01%  |
| 6.1.31  | 13        | 5.96%   |
| 6.2.11  | 12        | 5.5%    |
| 6.3.1   | 9         | 4.13%   |
| 6.1.27  | 8         | 3.67%   |
| 6.3.4   | 7         | 3.21%   |
| 6.1.28  | 7         | 3.21%   |
| 6.3.0   | 6         | 2.75%   |
| 6.3.8   | 5         | 2.29%   |
| 6.2.9   | 5         | 2.29%   |
| 6.2.8   | 5         | 2.29%   |
| 6.2.2   | 5         | 2.29%   |
| 6.2.0   | 5         | 2.29%   |
| 6.1.22  | 5         | 2.29%   |
| 6.2.12  | 4         | 1.83%   |
| 6.1.9   | 4         | 1.83%   |
| 6.1.11  | 4         | 1.83%   |
| 6.3.3   | 3         | 1.38%   |
| 6.3.2   | 3         | 1.38%   |
| 6.2.3   | 3         | 1.38%   |
| 6.1.24  | 3         | 1.38%   |
| 6.1.10  | 3         | 1.38%   |
| 6.4.0   | 2         | 0.92%   |
| 6.3.5   | 2         | 0.92%   |
| 6.2.6   | 2         | 0.92%   |
| 6.2.13  | 2         | 0.92%   |
| 6.2.10  | 2         | 0.92%   |
| 6.2.1   | 2         | 0.92%   |
| 6.1.29  | 2         | 0.92%   |
| 5.15.88 | 2         | 0.92%   |
| 5.15.80 | 2         | 0.92%   |
| 6.3.7   | 1         | 0.46%   |
| 6.3.6   | 1         | 0.46%   |
| 6.2.7   | 1         | 0.46%   |
| 6.2.5   | 1         | 0.46%   |
| 6.2.14  | 1         | 0.46%   |
| 6.1.8   | 1         | 0.46%   |
| 6.1.4   | 1         | 0.46%   |
| 6.1.30  | 1         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 99        | 50%     |
| 6.2     | 47        | 23.74%  |
| 6.3     | 35        | 17.68%  |
| 5.15    | 12        | 6.06%   |
| 6.4     | 2         | 1.01%   |
| 5.17    | 1         | 0.51%   |
| 5.16    | 1         | 0.51%   |
| 5.10    | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 181       | 97.31%  |
| i686    | 4         | 2.15%   |
| riscv64 | 1         | 0.54%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Unknown   | 60        | 31.58%  |
| KDE5      | 55        | 28.95%  |
| XFCE      | 22        | 11.58%  |
| GNOME     | 20        | 10.53%  |
| MATE      | 6         | 3.16%   |
| LXQt      | 5         | 2.63%   |
| DWM       | 4         | 2.11%   |
| KDE       | 3         | 1.58%   |
| i3        | 3         | 1.58%   |
| Trinity   | 2         | 1.05%   |
| sway      | 2         | 1.05%   |
| Xsession  | 1         | 0.53%   |
| X-Generic | 1         | 0.53%   |
| ratpoison | 1         | 0.53%   |
| openbox   | 1         | 0.53%   |
| LXDE      | 1         | 0.53%   |
| ICEWM     | 1         | 0.53%   |
| Hyprland  | 1         | 0.53%   |
| awesome   | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 88        | 45.36%  |
| Wayland | 45        | 23.2%   |
| Tty     | 31        | 15.98%  |
| Unknown | 30        | 15.46%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 67        | 35.45%  |
| SDDM    | 62        | 32.8%   |
| LightDM | 25        | 13.23%  |
| GDM     | 19        | 10.05%  |
| SLiM    | 5         | 2.65%   |
| LXDM    | 4         | 2.12%   |
| TDM     | 3         | 1.59%   |
| GREETD  | 3         | 1.59%   |
| XDM     | 1         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 75        | 39.27%  |
| C.UTF8     | 21        | 10.99%  |
| Unknown    | 20        | 10.47%  |
| en_GB      | 15        | 7.85%   |
| de_DE      | 11        | 5.76%   |
| C          | 8         | 4.19%   |
| ru_RU      | 7         | 3.66%   |
| fr_FR      | 7         | 3.66%   |
| en_IE      | 5         | 2.62%   |
| cs_CZ      | 5         | 2.62%   |
| pl_PL      | 2         | 1.05%   |
| it_IT      | 2         | 1.05%   |
| es_ES      | 2         | 1.05%   |
| en_AU      | 2         | 1.05%   |
| uk_UA      | 1         | 0.52%   |
| ru_RU.UTF8 | 1         | 0.52%   |
| ro_RO      | 1         | 0.52%   |
| fr_CA      | 1         | 0.52%   |
| fi_FI      | 1         | 0.52%   |
| es_MX      | 1         | 0.52%   |
| en_IL      | 1         | 0.52%   |
| el_GR      | 1         | 0.52%   |
| da_DK      | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 141       | 75%     |
| BIOS | 47        | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 102       | 54.26%  |
| Btrfs    | 60        | 31.91%  |
| F2fs     | 9         | 4.79%   |
| Zfs      | 6         | 3.19%   |
| Xfs      | 5         | 2.66%   |
| XXXXXXX  | 3         | 1.6%    |
| Reiserfs | 2         | 1.06%   |
| Jfs      | 1         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 159       | 85.03%  |
| MBR     | 22        | 11.76%  |
| Unknown | 6         | 3.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 119       | 62.63%  |
| Yes       | 71        | 37.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 125       | 66.49%  |
| Yes       | 63        | 33.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 49        | 26.34%  |
| Lenovo              | 20        | 10.75%  |
| Hewlett-Packard     | 20        | 10.75%  |
| Gigabyte Technology | 16        | 8.6%    |
| ASRock              | 15        | 8.06%   |
| MSI                 | 12        | 6.45%   |
| Dell                | 11        | 5.91%   |
| Acer                | 6         | 3.23%   |
| Unknown             | 6         | 3.23%   |
| Supermicro          | 5         | 2.69%   |
| Intel               | 3         | 1.61%   |
| HUAWEI              | 3         | 1.61%   |
| Foxconn             | 2         | 1.08%   |
| ZOTAC               | 1         | 0.54%   |
| Valve               | 1         | 0.54%   |
| TYAN Computer       | 1         | 0.54%   |
| TUXEDO              | 1         | 0.54%   |
| Toshiba             | 1         | 0.54%   |
| Timi                | 1         | 0.54%   |
| Star Labs           | 1         | 0.54%   |
| realme              | 1         | 0.54%   |
| Pegatron            | 1         | 0.54%   |
| Panasonic           | 1         | 0.54%   |
| Microsoft           | 1         | 0.54%   |
| MAXDATA             | 1         | 0.54%   |
| HPE                 | 1         | 0.54%   |
| Google              | 1         | 0.54%   |
| Fujitsu Siemens     | 1         | 0.54%   |
| Fujitsu             | 1         | 0.54%   |
| Fanless Mini PC     | 1         | 0.54%   |
| Apple               | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 6         | 3.23%   |
| Supermicro Super Server               | 3         | 1.61%   |
| HP ProLiant MicroServer Gen8          | 3         | 1.61%   |
| ASUS ROG Zephyrus G14 GA401II_GA401II | 3         | 1.61%   |
| ASRock X570 Taichi                    | 3         | 1.61%   |
| MSI MS-7B85                           | 2         | 1.08%   |
| Gigabyte X570S AORUS ELITE AX         | 2         | 1.08%   |
| Dell Precision 7770                   | 2         | 1.08%   |
| ASUS TUF Gaming X570-PLUS             | 2         | 1.08%   |
| ASUS ROG STRIX Z590-F GAMING WIFI     | 2         | 1.08%   |
| ASUS ROG STRIX X570-E GAMING          | 2         | 1.08%   |
| ASUS ROG Strix G513QY_G513QY          | 2         | 1.08%   |
| ASUS ROG STRIX B650E-F GAMING WIFI    | 2         | 1.08%   |
| ASUS M3A78-CM                         | 2         | 1.08%   |
| ASUS All Series                       | 2         | 1.08%   |
| ZOTAC H67ITX-C-E                      | 1         | 0.54%   |
| Valve Jupiter                         | 1         | 0.54%   |
| TYAN VT82C694T                        | 1         | 0.54%   |
| TUXEDO Polaris AMD Gen3 (CZN)         | 1         | 0.54%   |
| Toshiba Satellite L850                | 1         | 0.54%   |
| Timi RedmiBook Pro 15S                | 1         | 0.54%   |
| Supermicro X10SL7-F                   | 1         | 0.54%   |
| Supermicro SSG-6028R-ER12-HDP-AI050   | 1         | 0.54%   |
| Star Labs StarBook                    | 1         | 0.54%   |
| realme RMNBXXXX                       | 1         | 0.54%   |
| Pegatron 810-170st                    | 1         | 0.54%   |
| Panasonic CF-53ASCZGFG                | 1         | 0.54%   |
| MSI Vector GP66 12UEO                 | 1         | 0.54%   |
| MSI MS-7D67                           | 1         | 0.54%   |
| MSI MS-7D09                           | 1         | 0.54%   |
| MSI MS-7C91                           | 1         | 0.54%   |
| MSI MS-7C35                           | 1         | 0.54%   |
| MSI MS-7B18                           | 1         | 0.54%   |
| MSI MS-7817                           | 1         | 0.54%   |
| MSI MS-7640                           | 1         | 0.54%   |
| MSI GS66 Stealth 10UE                 | 1         | 0.54%   |
| MSI GE76 Raider 11UH                  | 1         | 0.54%   |
| Microsoft Surface Laptop 3            | 1         | 0.54%   |
| MAXDATA o.max_5xs                     | 1         | 0.54%   |
| Lenovo Yoga C940-15IRH 81TE           | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| ASUS ROG                            | 21        | 11.29%  |
| Lenovo ThinkPad                     | 13        | 6.99%   |
| ASUS PRIME                          | 8         | 4.3%    |
| Unknown                             | 6         | 3.23%   |
| HP EliteBook                        | 5         | 2.69%   |
| ASUS TUF                            | 5         | 2.69%   |
| Acer Aspire                         | 4         | 2.15%   |
| Supermicro Super                    | 3         | 1.61%   |
| HP ProLiant                         | 3         | 1.61%   |
| HP Pavilion                         | 3         | 1.61%   |
| Dell Precision                      | 3         | 1.61%   |
| Dell Latitude                       | 3         | 1.61%   |
| Dell Inspiron                       | 3         | 1.61%   |
| ASRock X670E                        | 3         | 1.61%   |
| ASRock X570                         | 3         | 1.61%   |
| MSI MS-7B85                         | 2         | 1.08%   |
| Lenovo ThinkStation                 | 2         | 1.08%   |
| Lenovo Legion                       | 2         | 1.08%   |
| HP Victus                           | 2         | 1.08%   |
| Gigabyte X570S                      | 2         | 1.08%   |
| Gigabyte X570                       | 2         | 1.08%   |
| Dell XPS                            | 2         | 1.08%   |
| ASUS M3A78-CM                       | 2         | 1.08%   |
| ASUS ASUS                           | 2         | 1.08%   |
| ASUS All                            | 2         | 1.08%   |
| Acer Swift                          | 2         | 1.08%   |
| ZOTAC H67ITX-C-E                    | 1         | 0.54%   |
| Valve Jupiter                       | 1         | 0.54%   |
| TYAN VT82C694T                      | 1         | 0.54%   |
| TUXEDO Polaris                      | 1         | 0.54%   |
| Toshiba Satellite                   | 1         | 0.54%   |
| Timi RedmiBook                      | 1         | 0.54%   |
| Supermicro X10SL7-F                 | 1         | 0.54%   |
| Supermicro SSG-6028R-ER12-HDP-AI050 | 1         | 0.54%   |
| Star Labs StarBook                  | 1         | 0.54%   |
| realme RMNBXXXX                     | 1         | 0.54%   |
| Pegatron 810-170st                  | 1         | 0.54%   |
| Panasonic CF-53ASCZGFG              | 1         | 0.54%   |
| MSI Vector                          | 1         | 0.54%   |
| MSI MS-7D67                         | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 32        | 17.2%   |
| 2021    | 32        | 17.2%   |
| 2019    | 23        | 12.37%  |
| 2020    | 19        | 10.22%  |
| 2018    | 14        | 7.53%   |
| 2012    | 11        | 5.91%   |
| 2013    | 8         | 4.3%    |
| 2010    | 8         | 4.3%    |
| 2017    | 7         | 3.76%   |
| 2016    | 6         | 3.23%   |
| 2023    | 5         | 2.69%   |
| 2014    | 4         | 2.15%   |
| 2008    | 4         | 2.15%   |
| 2015    | 3         | 1.61%   |
| 2011    | 3         | 1.61%   |
| 2009    | 3         | 1.61%   |
| 2007    | 1         | 0.54%   |
| 2003    | 1         | 0.54%   |
| 2002    | 1         | 0.54%   |
| Unknown | 1         | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 93        | 50%     |
| Notebook       | 81        | 43.55%  |
| Server         | 4         | 2.15%   |
| Convertible    | 3         | 1.61%   |
| Mini pc        | 2         | 1.08%   |
| Stick pc       | 1         | 0.54%   |
| System on chip | 1         | 0.54%   |
| Tablet         | 1         | 0.54%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 185       | 99.46%  |
| Enabled  | 1         | 0.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 184       | 98.92%  |
| Yes  | 2         | 1.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 42        | 22.34%  |
| 16.01-24.0      | 33        | 17.55%  |
| 64.01-256.0     | 32        | 17.02%  |
| 8.01-16.0       | 28        | 14.89%  |
| 4.01-8.0        | 22        | 11.7%   |
| 24.01-32.0      | 14        | 7.45%   |
| 3.01-4.0        | 8         | 4.26%   |
| 2.01-3.0        | 3         | 1.6%    |
| 1.01-2.0        | 3         | 1.6%    |
| More than 256.0 | 1         | 0.53%   |
| 0.51-1.0        | 1         | 0.53%   |
| 0.01-0.5        | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 42        | 20.39%  |
| 4.01-8.0   | 37        | 17.96%  |
| 1.01-2.0   | 29        | 14.08%  |
| 8.01-16.0  | 26        | 12.62%  |
| 3.01-4.0   | 25        | 12.14%  |
| 0.51-1.0   | 21        | 10.19%  |
| 0.01-0.5   | 17        | 8.25%   |
| 16.01-24.0 | 5         | 2.43%   |
| 32.01-64.0 | 2         | 0.97%   |
| 24.01-32.0 | 1         | 0.49%   |
| 0          | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 85        | 45.45%  |
| 2      | 44        | 23.53%  |
| 3      | 20        | 10.7%   |
| 5      | 14        | 7.49%   |
| 4      | 8         | 4.28%   |
| 6      | 5         | 2.67%   |
| 10     | 3         | 1.6%    |
| 7      | 3         | 1.6%    |
| 8      | 2         | 1.07%   |
| 21     | 1         | 0.53%   |
| 13     | 1         | 0.53%   |
| 0      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 79.03%  |
| Yes       | 39        | 20.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 165       | 88.24%  |
| No        | 22        | 11.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 72.19%  |
| No        | 52        | 27.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 65.43%  |
| No        | 65        | 34.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 52        | 27.66%  |
| Germany     | 24        | 12.77%  |
| France      | 15        | 7.98%   |
| Russia      | 14        | 7.45%   |
| UK          | 11        | 5.85%   |
| Poland      | 9         | 4.79%   |
| Canada      | 9         | 4.79%   |
| Spain       | 6         | 3.19%   |
| Czechia     | 4         | 2.13%   |
| Sweden      | 3         | 1.6%    |
| Italy       | 3         | 1.6%    |
| China       | 3         | 1.6%    |
| Brazil      | 3         | 1.6%    |
| Vietnam     | 2         | 1.06%   |
| Switzerland | 2         | 1.06%   |
| Netherlands | 2         | 1.06%   |
| Indonesia   | 2         | 1.06%   |
| Hungary     | 2         | 1.06%   |
| Australia   | 2         | 1.06%   |
| Ukraine     | 1         | 0.53%   |
| Romania     | 1         | 0.53%   |
| Portugal    | 1         | 0.53%   |
| Norway      | 1         | 0.53%   |
| New Zealand | 1         | 0.53%   |
| Moldova     | 1         | 0.53%   |
| Mexico      | 1         | 0.53%   |
| Luxembourg  | 1         | 0.53%   |
| Lithuania   | 1         | 0.53%   |
| Israel      | 1         | 0.53%   |
| Ireland     | 1         | 0.53%   |
| Iran        | 1         | 0.53%   |
| Iceland     | 1         | 0.53%   |
| Hong Kong   | 1         | 0.53%   |
| Greece      | 1         | 0.53%   |
| Finland     | 1         | 0.53%   |
| Denmark     | 1         | 0.53%   |
| Belgium     | 1         | 0.53%   |
| Belarus     | 1         | 0.53%   |
| Algeria     | 1         | 0.53%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 8         | 4.12%   |
| Paris             | 5         | 2.58%   |
| St Petersburg     | 4         | 2.06%   |
| Frankfurt am Main | 4         | 2.06%   |
| Warsaw            | 3         | 1.55%   |
| Sterling          | 3         | 1.55%   |
| Šlapanice        | 3         | 1.55%   |
| Moscow            | 3         | 1.55%   |
| Kippens           | 3         | 1.55%   |
| Cieszyn           | 3         | 1.55%   |
| Beaverton         | 3         | 1.55%   |
| Vladivostok       | 2         | 1.03%   |
| Taganrog          | 2         | 1.03%   |
| Summerville       | 2         | 1.03%   |
| Stockholm         | 2         | 1.03%   |
| Seattle           | 2         | 1.03%   |
| Pittsburgh        | 2         | 1.03%   |
| Oviedo            | 2         | 1.03%   |
| Milan             | 2         | 1.03%   |
| Leeds             | 2         | 1.03%   |
| Hanoi             | 2         | 1.03%   |
| Gatineau          | 2         | 1.03%   |
| Flint             | 2         | 1.03%   |
| Étampes          | 2         | 1.03%   |
| Cognac            | 2         | 1.03%   |
| Chicago           | 2         | 1.03%   |
| Budapest          | 2         | 1.03%   |
| Bothell           | 2         | 1.03%   |
| Augusta           | 2         | 1.03%   |
| Zurich            | 1         | 0.52%   |
| Yucaipa           | 1         | 0.52%   |
| Wlodawa           | 1         | 0.52%   |
| Whitby            | 1         | 0.52%   |
| Wheaton           | 1         | 0.52%   |
| Wandsworth        | 1         | 0.52%   |
| Vilnius           | 1         | 0.52%   |
| Vechta            | 1         | 0.52%   |
| Vancouver         | 1         | 0.52%   |
| Urbana            | 1         | 0.52%   |
| Trakai            | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 73        | 138    | 22.53%  |
| WDC                         | 36        | 76     | 11.11%  |
| Seagate                     | 36        | 80     | 11.11%  |
| Sandisk                     | 31        | 36     | 9.57%   |
| Crucial                     | 14        | 27     | 4.32%   |
| Toshiba                     | 13        | 20     | 4.01%   |
| Phison Electronics          | 12        | 16     | 3.7%    |
| Intel                       | 12        | 16     | 3.7%    |
| Kingston                    | 11        | 13     | 3.4%    |
| SK hynix                    | 10        | 11     | 3.09%   |
| China                       | 8         | 20     | 2.47%   |
| Unknown                     | 6         | 7      | 1.85%   |
| Kingston Technology Company | 6         | 6      | 1.85%   |
| Hitachi                     | 6         | 18     | 1.85%   |
| HGST                        | 6         | 10     | 1.85%   |
| Micron/Crucial Technology   | 5         | 8      | 1.54%   |
| Micron Technology           | 5         | 6      | 1.54%   |
| GOODRAM                     | 5         | 14     | 1.54%   |
| A-DATA Technology           | 4         | 4      | 1.23%   |
| PNY                         | 2         | 4      | 0.62%   |
| Phison                      | 2         | 3      | 0.62%   |
| OCZ                         | 2         | 2      | 0.62%   |
| KIOXIA                      | 2         | 3      | 0.62%   |
| ADROITLARK                  | 2         | 3      | 0.62%   |
| ADATA Technology            | 2         | 4      | 0.62%   |
| V-GeN                       | 1         | 1      | 0.31%   |
| Transcend                   | 1         | 1      | 0.31%   |
| Teleplan                    | 1         | 1      | 0.31%   |
| T-FORCE                     | 1         | 1      | 0.31%   |
| Silicon Motion              | 1         | 2      | 0.31%   |
| SABRENT                     | 1         | 1      | 0.31%   |
| Realtek Semiconductor       | 1         | 1      | 0.31%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.31%   |
| LITEONIT                    | 1         | 1      | 0.31%   |
| KingSpec                    | 1         | 1      | 0.31%   |
| Intenso                     | 1         | 1      | 0.31%   |
| Dogfish                     | 1         | 1      | 0.31%   |
| Unknown                     | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 25        | 6.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 23        | 5.97%   |
| Samsung SSD 980 1TB                                 | 9         | 2.34%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 7         | 1.82%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 7         | 1.82%   |
| Seagate ST4000DM004-2CV104 4TB                      | 6         | 1.56%   |
| Crucial CT1000MX500SSD1 1TB                         | 5         | 1.3%    |
| Seagate ST1000DM010-2EP102 1TB                      | 4         | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 4         | 1.04%   |
| Intel SSD 660P Series 512GB                         | 4         | 1.04%   |
| Unknown MMC Card  128GB                             | 3         | 0.78%   |
| Samsung SSD 870 EVO 1TB                             | 3         | 0.78%   |
| Samsung SSD 860 EVO 1TB                             | 3         | 0.78%   |
| Samsung SSD 850 EVO 250GB                           | 3         | 0.78%   |
| Phison E12 NVMe Controller 1TB                      | 3         | 0.78%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 3         | 0.78%   |
| Kingston Company SNV2S2000G 2TB                     | 3         | 0.78%   |
| WDC WD80EFAX-68KNBN0 8TB                            | 2         | 0.52%   |
| WDC WD5000LPLX-66ZNTT1 500GB                        | 2         | 0.52%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 2         | 0.52%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 2         | 0.52%   |
| WDC WD20EARX-00PASB0 2TB                            | 2         | 0.52%   |
| WDC WD2003FZEX-00SRLA0 2TB                          | 2         | 0.52%   |
| WDC WD1502FYPS-02W3B0 1TB                           | 2         | 0.52%   |
| WDC WD120EFBX-68B0EN0 12TB                          | 2         | 0.52%   |
| Toshiba DT01ACA200 2TB                              | 2         | 0.52%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 2         | 0.52%   |
| Seagate ST6000DM003-2CY186 6TB                      | 2         | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.52%   |
| Sandisk WD_BLACK SN770 1TB                          | 2         | 0.52%   |
| Samsung SSD 870 QVO 2TB                             | 2         | 0.52%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.52%   |
| Samsung SSD 860 EVO 4TB                             | 2         | 0.52%   |
| Phison E7 NVMe Controller 120GB                     | 2         | 0.52%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 2         | 0.52%   |
| Phison Corsair MP600 PRO XT 2TB                     | 2         | 0.52%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                       | 2         | 0.52%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.52%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 78     | 38.3%   |
| WDC                 | 32        | 71     | 34.04%  |
| Toshiba             | 12        | 19     | 12.77%  |
| Hitachi             | 6         | 18     | 6.38%   |
| HGST                | 6         | 10     | 6.38%   |
| Teleplan            | 1         | 1      | 1.06%   |
| Samsung Electronics | 1         | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 46     | 27.45%  |
| Crucial             | 14        | 27     | 13.73%  |
| SanDisk             | 10        | 12     | 9.8%    |
| Kingston            | 9         | 10     | 8.82%   |
| China               | 8         | 20     | 7.84%   |
| GOODRAM             | 5         | 14     | 4.9%    |
| WDC                 | 4         | 5      | 3.92%   |
| A-DATA Technology   | 4         | 4      | 3.92%   |
| Intel               | 3         | 4      | 2.94%   |
| PNY                 | 2         | 4      | 1.96%   |
| OCZ                 | 2         | 2      | 1.96%   |
| Micron Technology   | 2         | 3      | 1.96%   |
| ADROITLARK          | 2         | 3      | 1.96%   |
| V-GeN               | 1         | 1      | 0.98%   |
| Transcend           | 1         | 1      | 0.98%   |
| T-FORCE             | 1         | 1      | 0.98%   |
| SK hynix            | 1         | 1      | 0.98%   |
| LITEONIT            | 1         | 1      | 0.98%   |
| KingSpec            | 1         | 1      | 0.98%   |
| Intenso             | 1         | 1      | 0.98%   |
| Dogfish             | 1         | 1      | 0.98%   |
| Unknown             | 1         | 1      | 0.98%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 110       | 189    | 41.51%  |
| SSD     | 77        | 163    | 29.06%  |
| HDD     | 71        | 198    | 26.79%  |
| MMC     | 5         | 6      | 1.89%   |
| Unknown | 2         | 3      | 0.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 113       | 351    | 48.09%  |
| NVMe | 110       | 188    | 46.81%  |
| SAS  | 7         | 14     | 2.98%   |
| MMC  | 5         | 6      | 2.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 71        | 109    | 37.17%  |
| 0.51-1.0   | 49        | 97     | 25.65%  |
| 1.01-2.0   | 31        | 59     | 16.23%  |
| 3.01-4.0   | 17        | 36     | 8.9%    |
| 4.01-10.0  | 15        | 33     | 7.85%   |
| 2.01-3.0   | 5         | 21     | 2.62%   |
| 10.01-20.0 | 3         | 6      | 1.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 36        | 18.85%  |
| More than 3000 | 33        | 17.28%  |
| 251-500        | 33        | 17.28%  |
| 1001-2000      | 26        | 13.61%  |
| 101-250        | 24        | 12.57%  |
| 2001-3000      | 13        | 6.81%   |
| 1-20           | 8         | 4.19%   |
| 51-100         | 8         | 4.19%   |
| Unknown        | 8         | 4.19%   |
| 21-50          | 2         | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 39        | 19.6%   |
| 21-50          | 29        | 14.57%  |
| 501-1000       | 27        | 13.57%  |
| 101-250        | 24        | 12.06%  |
| 251-500        | 23        | 11.56%  |
| More than 3000 | 18        | 9.05%   |
| 51-100         | 15        | 7.54%   |
| 1001-2000      | 14        | 7.04%   |
| Unknown        | 8         | 4.02%   |
| 2001-3000      | 2         | 1.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba DT01ACA200 2TB               | 2         | 2      | 6.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 3      | 6.45%   |
| HGST HTS725050A7E630 500GB           | 2         | 2      | 6.45%   |
| WDC WD60PURZ-85ZUFY1 6TB             | 1         | 1      | 3.23%   |
| WDC WD60EZRX-00MVLB1 6TB             | 1         | 1      | 3.23%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 2      | 3.23%   |
| Toshiba MK5056GSY 500GB              | 1         | 1      | 3.23%   |
| Toshiba MK1633GSG 160GB              | 1         | 1      | 3.23%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 2      | 3.23%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 1      | 3.23%   |
| Seagate ST500DM002-1BC142 500GB      | 1         | 1      | 3.23%   |
| Seagate ST380011A 80GB               | 1         | 1      | 3.23%   |
| Seagate ST3500630NS 500GB            | 1         | 2      | 3.23%   |
| Seagate ST3000DM001-9YN166 3TB       | 1         | 1      | 3.23%   |
| Seagate ST2000DX002-2DV164 2TB       | 1         | 1      | 3.23%   |
| Seagate ST2000DM001-1CH164 2TB       | 1         | 1      | 3.23%   |
| Seagate ST1000DM010-2EP102 1TB       | 1         | 1      | 3.23%   |
| SanDisk SSD PLUS 480GB               | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 980 1TB      | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 870 EVO 1TB  | 1         | 8      | 3.23%   |
| PNY SSD2SC120G1LC763C121S459P 120GB  | 1         | 1      | 3.23%   |
| Intel SSDSC2BF180A5L 180GB           | 1         | 1      | 3.23%   |
| Intel SSDSC2BB160G4T 160GB           | 1         | 2      | 3.23%   |
| Hitachi HTS721080G9SA00 80GB         | 1         | 1      | 3.23%   |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 3.23%   |
| Crucial M4-CT512M4SSD2 512GB         | 1         | 1      | 3.23%   |
| China SSD 240GB                      | 1         | 1      | 3.23%   |
| China SATA SSD 960GB                 | 1         | 2      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 12     | 30%     |
| Toshiba             | 4         | 4      | 13.33%  |
| WDC                 | 3         | 4      | 10%     |
| HGST                | 3         | 3      | 10%     |
| Samsung Electronics | 2         | 9      | 6.67%   |
| Intel               | 2         | 3      | 6.67%   |
| China               | 2         | 3      | 6.67%   |
| SK hynix            | 1         | 2      | 3.33%   |
| SanDisk             | 1         | 1      | 3.33%   |
| PNY                 | 1         | 1      | 3.33%   |
| Hitachi             | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |

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
| HDD  | 19        | 24     | 65.52%  |
| SSD  | 8         | 17     | 27.59%  |
| NVMe | 2         | 3      | 6.9%    |

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
| Works    | 162       | 465    | 76.06%  |
| Malfunc  | 28        | 44     | 13.15%  |
| Detected | 21        | 47     | 9.86%   |
| Failed   | 2         | 3      | 0.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 86        | 28.48%  |
| AMD                          | 63        | 20.86%  |
| Samsung Electronics          | 52        | 17.22%  |
| SanDisk                      | 22        | 7.28%   |
| Phison Electronics           | 13        | 4.3%    |
| ASMedia Technology           | 13        | 4.3%    |
| SK hynix                     | 9         | 2.98%   |
| Kingston Technology Company  | 8         | 2.65%   |
| Micron/Crucial Technology    | 5         | 1.66%   |
| Marvell Technology Group     | 5         | 1.66%   |
| Broadcom / LSI               | 5         | 1.66%   |
| JMicron Technology           | 4         | 1.32%   |
| Micron Technology            | 3         | 0.99%   |
| Nvidia                       | 2         | 0.66%   |
| KIOXIA                       | 2         | 0.66%   |
| ADATA Technology             | 2         | 0.66%   |
| VIA Technologies             | 1         | 0.33%   |
| Toshiba America Info Systems | 1         | 0.33%   |
| Silicon Motion               | 1         | 0.33%   |
| Silicon Image                | 1         | 0.33%   |
| Realtek Semiconductor        | 1         | 0.33%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.33%   |
| LSI Logic / Symbios Logic    | 1         | 0.33%   |
| INNOGRIT                     | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 50        | 14.75%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 24        | 7.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 23        | 6.78%   |
| Samsung NVMe SSD Controller 980                                                | 12        | 3.54%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 10        | 2.95%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 2.06%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 2.06%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.06%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 2.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 1.77%   |
| AMD 500 Series Chipset SATA Controller                                         | 6         | 1.77%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.47%   |
| Phison E18 PCIe4 NVMe Controller                                               | 5         | 1.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.18%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 1.18%   |
| Intel SSD 660P Series                                                          | 4         | 1.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.18%   |
| Intel Non-Volatile memory controller                                           | 4         | 1.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.18%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 1.18%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.88%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 0.88%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 3         | 0.88%   |
| Kingston Company FURY Renegade NVMe SSD                                        | 3         | 0.88%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 0.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.88%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 0.88%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                            | 3         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.88%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2         | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.59%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 2         | 0.59%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 2         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 133       | 48.36%  |
| NVMe | 109       | 39.64%  |
| RAID | 14        | 5.09%   |
| IDE  | 13        | 4.73%   |
| SAS  | 6         | 2.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor     | Computers | Percent |
|------------|-----------|---------|
| Intel      | 106       | 56.99%  |
| AMD        | 79        | 42.47%  |
| thead,c906 | 1         | 0.54%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 9 7900X 12-Core Processor           | 6         | 3.21%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 2.67%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 2.67%   |
| AMD Ryzen 9 7950X 16-Core Processor           | 4         | 2.14%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 2.14%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4         | 2.14%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz           | 3         | 1.6%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.6%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 1.6%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 3         | 1.6%    |
| AMD Ryzen 7 4800HS with Radeon Graphics       | 3         | 1.6%    |
| Intel Core i9-10850K CPU @ 3.60GHz            | 2         | 1.07%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.07%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.07%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 2         | 1.07%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 2         | 1.07%   |
| Intel Atom CPU D510 @ 1.66GHz                 | 2         | 1.07%   |
| Intel Atom CPU 330 @ 1.60GHz                  | 2         | 1.07%   |
| Intel 12th Gen Core i7-12850HX                | 2         | 1.07%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz      | 2         | 1.07%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.07%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.07%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.07%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 2         | 1.07%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics    | 2         | 1.07%   |
| AMD Ryzen 7 5800X3D 8-Core Processor          | 2         | 1.07%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.07%   |
| AMD Ryzen 5 7600X 6-Core Processor            | 2         | 1.07%   |
| AMD Ryzen 5 5500                              | 2         | 1.07%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.07%   |
| AMD Phenom II X4 955 Processor                | 2         | 1.07%   |
| thead,c906 rv64imafdc                         | 1         | 0.53%   |
| Intel Xeon W-2145 CPU @ 3.70GHz               | 1         | 0.53%   |
| Intel Xeon E-2224 CPU @ 3.40GHz               | 1         | 0.53%   |
| Intel Xeon CPU E5-2696 v4 @ 2.20GHz           | 1         | 0.53%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz           | 1         | 0.53%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.53%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz          | 1         | 0.53%   |
| Intel Xeon CPU D-1521 @ 2.40GHz               | 1         | 0.53%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 30        | 16.13%  |
| Other                | 29        | 15.59%  |
| AMD Ryzen 9          | 22        | 11.83%  |
| AMD Ryzen 7          | 22        | 11.83%  |
| AMD Ryzen 5          | 20        | 10.75%  |
| Intel Core i5        | 14        | 7.53%   |
| Intel Xeon           | 10        | 5.38%   |
| Intel Atom           | 6         | 3.23%   |
| Intel Core i9        | 5         | 2.69%   |
| Intel Core i3        | 5         | 2.69%   |
| AMD Ryzen 7 PRO      | 4         | 2.15%   |
| AMD Phenom II X4     | 3         | 1.61%   |
| Intel Pentium        | 2         | 1.08%   |
| Intel Celeron        | 2         | 1.08%   |
| AMD FX               | 2         | 1.08%   |
| AMD EPYC             | 2         | 1.08%   |
| Intel Pentium Silver | 1         | 0.54%   |
| Intel Pentium III    | 1         | 0.54%   |
| Intel Pentium 4      | 1         | 0.54%   |
| Intel Core Duo       | 1         | 0.54%   |
| Intel Core 2 Duo     | 1         | 0.54%   |
| AMD Ryzen 5 PRO      | 1         | 0.54%   |
| AMD Athlon II        | 1         | 0.54%   |
| AMD Athlon           | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 48        | 25.81%  |
| 8       | 42        | 22.58%  |
| 2       | 29        | 15.59%  |
| 6       | 28        | 15.05%  |
| 16      | 14        | 7.53%   |
| 12      | 13        | 6.99%   |
| 14      | 5         | 2.69%   |
| 10      | 2         | 1.08%   |
| 1       | 2         | 1.08%   |
| 44      | 1         | 0.54%   |
| 32      | 1         | 0.54%   |
| Unknown | 1         | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 183       | 98.39%  |
| 2       | 2         | 1.08%   |
| Unknown | 1         | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 164       | 88.17%  |
| 1       | 21        | 11.29%  |
| Unknown | 1         | 0.54%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 181       | 97.31%  |
| 32-bit         | 4         | 2.15%   |
| Unknown        | 1         | 0.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 31.94%  |
| 0x0a601203 | 12        | 6.28%   |
| 0x806c1    | 9         | 4.71%   |
| 0x0a50000c | 8         | 4.19%   |
| 0x08701021 | 7         | 3.66%   |
| 0x906ea    | 6         | 3.14%   |
| 0x0a20120a | 6         | 3.14%   |
| 0x906e9    | 4         | 2.09%   |
| 0x0a50000d | 4         | 2.09%   |
| 0x0800820d | 4         | 2.09%   |
| 0xa0652    | 3         | 1.57%   |
| 0x306c3    | 3         | 1.57%   |
| 0x206a7    | 3         | 1.57%   |
| 0x08608103 | 3         | 1.57%   |
| 0x08600104 | 3         | 1.57%   |
| 0x08108109 | 3         | 1.57%   |
| 0xa0671    | 2         | 1.05%   |
| 0x906ed    | 2         | 1.05%   |
| 0x906a3    | 2         | 1.05%   |
| 0x90672    | 2         | 1.05%   |
| 0x806d1    | 2         | 1.05%   |
| 0x506e3    | 2         | 1.05%   |
| 0x306a9    | 2         | 1.05%   |
| 0x20655    | 2         | 1.05%   |
| 0x0a404102 | 2         | 1.05%   |
| 0x0a201016 | 2         | 1.05%   |
| 0xf29      | 1         | 0.52%   |
| 0xb06a2    | 1         | 0.52%   |
| 0xa0655    | 1         | 0.52%   |
| 0x806ec    | 1         | 0.52%   |
| 0x806e9    | 1         | 0.52%   |
| 0x706a8    | 1         | 0.52%   |
| 0x50663    | 1         | 0.52%   |
| 0x50654    | 1         | 0.52%   |
| 0x406f1    | 1         | 0.52%   |
| 0x406e3    | 1         | 0.52%   |
| 0x406c4    | 1         | 0.52%   |
| 0x40651    | 1         | 0.52%   |
| 0x306e4    | 1         | 0.52%   |
| 0x306d4    | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 3            | 25        | 13.44%  |
| Unknown          | 23        | 12.37%  |
| Zen 2            | 16        | 8.6%    |
| KabyLake         | 16        | 8.6%    |
| Alderlake Hybrid | 12        | 6.45%   |
| IvyBridge        | 11        | 5.91%   |
| TigerLake        | 9         | 4.84%   |
| Zen+             | 8         | 4.3%    |
| Haswell          | 8         | 4.3%    |
| CometLake        | 8         | 4.3%    |
| Skylake          | 7         | 3.76%   |
| SandyBridge      | 7         | 3.76%   |
| Icelake          | 7         | 3.76%   |
| Bonnell          | 6         | 3.23%   |
| K10              | 4         | 2.15%   |
| Broadwell        | 4         | 2.15%   |
| Westmere         | 3         | 1.61%   |
| Zen              | 2         | 1.08%   |
| P6               | 2         | 1.08%   |
| Silvermont       | 1         | 0.54%   |
| Piledriver       | 1         | 0.54%   |
| Penryn           | 1         | 0.54%   |
| NetBurst         | 1         | 0.54%   |
| Nehalem          | 1         | 0.54%   |
| Jaguar           | 1         | 0.54%   |
| Goldmont plus    | 1         | 0.54%   |
| Bulldozer        | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| AMD                        | 79        | 34.96%  |
| Nvidia                     | 72        | 31.86%  |
| Intel                      | 66        | 29.2%   |
| ASPEED Technology          | 5         | 2.21%   |
| Matrox Electronics Systems | 4         | 1.77%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Raphael                                                                   | 10        | 4.1%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 9         | 3.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 3.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 7         | 2.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 7         | 2.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 7         | 2.87%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 6         | 2.46%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 5         | 2.05%   |
| ASPEED Technology ASPEED Graphics Family                                      | 5         | 2.05%   |
| AMD Renoir                                                                    | 5         | 2.05%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                      | 5         | 2.05%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                            | 4         | 1.64%   |
| Intel HD Graphics 530                                                         | 4         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 1.64%   |
| AMD Rembrandt [Radeon 680M]                                                   | 4         | 1.64%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 4         | 1.64%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 4         | 1.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 1.23%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                    | 3         | 1.23%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 3         | 1.23%   |
| Nvidia AD102 [GeForce RTX 4090]                                               | 3         | 1.23%   |
| Matrox Electronics Systems MGA G200EH                                         | 3         | 1.23%   |
| Intel HD Graphics 630                                                         | 3         | 1.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 1.23%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.23%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 3         | 1.23%   |
| AMD Lucienne                                                                  | 3         | 1.23%   |
| Nvidia TU117M [GeForce MX450]                                                 | 2         | 0.82%   |
| Nvidia GT218 [GeForce 210]                                                    | 2         | 0.82%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 2         | 0.82%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 2         | 0.82%   |
| Nvidia GA106 [Geforce RTX 3050]                                               | 2         | 0.82%   |
| Nvidia GA104GLM [RTX A3000 12GB Laptop GPU]                                   | 2         | 0.82%   |
| Nvidia GA104 [GeForce RTX 3070]                                               | 2         | 0.82%   |
| Nvidia C79 [ION]                                                              | 2         | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 2         | 0.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 0.82%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 0.82%   |
| Intel HD Graphics 5500                                                        | 2         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 53        | 27.89%  |
| 1 x Nvidia     | 37        | 19.47%  |
| 1 x Intel      | 32        | 16.84%  |
| Intel + Nvidia | 25        | 13.16%  |
| 2 x AMD        | 13        | 6.84%   |
| AMD + Nvidia   | 11        | 5.79%   |
| Intel + AMD    | 5         | 2.63%   |
| 1 x ASPEED     | 5         | 2.63%   |
| 2 x Intel      | 4         | 2.11%   |
| 1 x Matrox     | 4         | 2.11%   |
| Other          | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 131       | 69.68%  |
| Proprietary | 42        | 22.34%  |
| Unknown     | 15        | 7.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 41.49%  |
| 7.01-8.0   | 21        | 11.17%  |
| 8.01-16.0  | 21        | 11.17%  |
| 0.01-0.5   | 17        | 9.04%   |
| 0.51-1.0   | 15        | 7.98%   |
| 3.01-4.0   | 12        | 6.38%   |
| 1.01-2.0   | 12        | 6.38%   |
| 16.01-24.0 | 6         | 3.19%   |
| 5.01-6.0   | 5         | 2.66%   |
| 2.01-3.0   | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 23        | 11.5%   |
| Chimei Innolux          | 18        | 9%      |
| Dell                    | 17        | 8.5%    |
| AU Optronics            | 16        | 8%      |
| BOE                     | 13        | 6.5%    |
| Goldstar                | 11        | 5.5%    |
| ASUSTek Computer        | 10        | 5%      |
| LG Display              | 8         | 4%      |
| BenQ                    | 8         | 4%      |
| AOC                     | 8         | 4%      |
| Sharp                   | 5         | 2.5%    |
| Acer                    | 5         | 2.5%    |
| Hewlett-Packard         | 4         | 2%      |
| Eizo                    | 4         | 2%      |
| Ancor Communications    | 4         | 2%      |
| Unknown                 | 3         | 1.5%    |
| PANDA                   | 3         | 1.5%    |
| Lenovo                  | 3         | 1.5%    |
| Gigabyte Technology     | 3         | 1.5%    |
| Chi Mei Optoelectronics | 3         | 1.5%    |
| Philips                 | 2         | 1%      |
| Iiyama                  | 2         | 1%      |
| CSO                     | 2         | 1%      |
| BOE Technology Group    | 2         | 1%      |
| Unknown                 | 2         | 1%      |
| Vizio                   | 1         | 0.5%    |
| Valve                   | 1         | 0.5%    |
| TMX                     | 1         | 0.5%    |
| Sony                    | 1         | 0.5%    |
| Sceptre Tech            | 1         | 0.5%    |
| Onkyo                   | 1         | 0.5%    |
| MStar                   | 1         | 0.5%    |
| Microstep               | 1         | 0.5%    |
| InfoVision              | 1         | 0.5%    |
| Idek Iiyama             | 1         | 0.5%    |
| IBM                     | 1         | 0.5%    |
| HJW                     | 1         | 0.5%    |
| Gateway                 | 1         | 0.5%    |
| Envision Peripherals    | 1         | 0.5%    |
| ELSA                    | 1         | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch           | 3         | 1.42%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 0.94%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch   | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SAM7003 3840x2160 1420x800mm 64.2-inch | 2         | 0.94%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                | 2         | 0.94%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 2         | 0.94%   |
| Gigabyte Technology G27FC A GBT2715 1920x1080 598x336mm 27.0-inch      | 2         | 0.94%   |
| Eizo CS2731 ENC3069 2560x1440 597x336mm 27.0-inch                      | 2         | 0.94%   |
| BOE Technology Group LCD Monitor 1920x1080                             | 2         | 0.94%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 2         | 0.94%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                     | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 2         | 0.94%   |
| AOC LCD Monitor U2879G6 3840x2160                                      | 2         | 0.94%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 2         | 0.94%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 2         | 0.94%   |
| Acer ED320QR S ACR0805 1920x1080 609x348mm 27.6-inch                   | 2         | 0.94%   |
| Unknown                                                                | 2         | 0.94%   |
| Vizio D43n-E1 VIZ1009 1920x1080 953x543mm 43.2-inch                    | 1         | 0.47%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 1         | 0.47%   |
| Unknown LCD Monitor RTK                                                | 1         | 0.47%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                | 1         | 0.47%   |
| Sony BW8 MS_9001 2560x1600                                             | 1         | 0.47%   |
| Sharp LQ173M1JW03 SHP14DC 1920x1080 382x215mm 17.3-inch                | 1         | 0.47%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                | 1         | 0.47%   |
| Sharp LQ135P1JX51 SHP14B3 2256x1504 285x190mm 13.5-inch                | 1         | 0.47%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch                | 1         | 0.47%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 0.47%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch        | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM05E8 1920x1080                       | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch   | 1         | 0.47%   |
| Samsung Electronics SMT23A350 SAM07A7 1920x1080 510x287mm 23.0-inch    | 1         | 0.47%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch    | 1         | 0.47%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch   | 1         | 0.47%   |
| Samsung Electronics SME2020N SAM06A6 1600x900 443x249mm 20.0-inch      | 1         | 0.47%   |
| Samsung Electronics S27E390 SAM0C1C 1920x1080 598x336mm 27.0-inch      | 1         | 0.47%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch      | 1         | 0.47%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch      | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4179 2560x1440 344x194mm 15.5-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch  | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 79        | 40.93%  |
| 3840x2160 (4K)     | 29        | 15.03%  |
| 2560x1440 (QHD)    | 23        | 11.92%  |
| 3440x1440          | 7         | 3.63%   |
| 1366x768 (WXGA)    | 7         | 3.63%   |
| 1920x1200 (WUXGA)  | 6         | 3.11%   |
| 1600x900 (HD+)     | 5         | 2.59%   |
| 2560x1600          | 4         | 2.07%   |
| 3840x1080          | 3         | 1.55%   |
| Unknown            | 3         | 1.55%   |
| 2560x1080          | 2         | 1.04%   |
| 2288x1287          | 2         | 1.04%   |
| 1680x1050 (WSXGA+) | 2         | 1.04%   |
| 1440x900 (WXGA+)   | 2         | 1.04%   |
| 1280x800 (WXGA)    | 2         | 1.04%   |
| 1280x1024 (SXGA)   | 2         | 1.04%   |
| 1024x768 (XGA)     | 2         | 1.04%   |
| 800x1280           | 1         | 0.52%   |
| 3840x2400          | 1         | 0.52%   |
| 3840x1200          | 1         | 0.52%   |
| 3456x2160          | 1         | 0.52%   |
| 3200x2000          | 1         | 0.52%   |
| 3072x1920          | 1         | 0.52%   |
| 2520x1680          | 1         | 0.52%   |
| 2256x1504          | 1         | 0.52%   |
| 2160x1440          | 1         | 0.52%   |
| 1920x540           | 1         | 0.52%   |
| 1600x1200          | 1         | 0.52%   |
| 1360x768           | 1         | 0.52%   |
| 1024x600           | 1         | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 33        | 16.34%  |
| 27      | 32        | 15.84%  |
| Unknown | 15        | 7.43%   |
| 24      | 14        | 6.93%   |
| 17      | 13        | 6.44%   |
| 13      | 13        | 6.44%   |
| 23      | 11        | 5.45%   |
| 14      | 11        | 5.45%   |
| 21      | 8         | 3.96%   |
| 34      | 7         | 3.47%   |
| 31      | 7         | 3.47%   |
| 16      | 7         | 3.47%   |
| 84      | 3         | 1.49%   |
| 32      | 3         | 1.49%   |
| 19      | 3         | 1.49%   |
| 142     | 2         | 0.99%   |
| 25      | 2         | 0.99%   |
| 22      | 2         | 0.99%   |
| 49      | 1         | 0.5%    |
| 48      | 1         | 0.5%    |
| 43      | 1         | 0.5%    |
| 42      | 1         | 0.5%    |
| 41      | 1         | 0.5%    |
| 40      | 1         | 0.5%    |
| 35      | 1         | 0.5%    |
| 29      | 1         | 0.5%    |
| 26      | 1         | 0.5%    |
| 20      | 1         | 0.5%    |
| 18      | 1         | 0.5%    |
| 12      | 1         | 0.5%    |
| 10      | 1         | 0.5%    |
| 9       | 1         | 0.5%    |
| 8       | 1         | 0.5%    |
| 7       | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 57        | 29.53%  |
| 501-600        | 50        | 25.91%  |
| Unknown        | 15        | 7.77%   |
| 401-500        | 14        | 7.25%   |
| 351-400        | 12        | 6.22%   |
| 201-300        | 11        | 5.7%    |
| 701-800        | 10        | 5.18%   |
| 601-700        | 10        | 5.18%   |
| 1501-2000      | 3         | 1.55%   |
| 901-1000       | 3         | 1.55%   |
| More than 2000 | 2         | 1.04%   |
| 801-900        | 2         | 1.04%   |
| 1001-1500      | 2         | 1.04%   |
| 101-200        | 1         | 0.52%   |
| 1-100          | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 123       | 68.72%  |
| 16/10   | 22        | 12.29%  |
| Unknown | 11        | 6.15%   |
| 21/9    | 8         | 4.47%   |
| 4/3     | 3         | 1.68%   |
| 32/9    | 3         | 1.68%   |
| 3/2     | 3         | 1.68%   |
| 5/4     | 2         | 1.12%   |
| 1.00    | 2         | 1.12%   |
| 0.67    | 1         | 0.56%   |
| 0.62    | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 17.17%  |
| 301-350        | 33        | 16.67%  |
| 201-250        | 25        | 12.63%  |
| 81-90          | 18        | 9.09%   |
| 351-500        | 18        | 9.09%   |
| Unknown        | 15        | 7.58%   |
| 121-130        | 11        | 5.56%   |
| 251-300        | 7         | 3.54%   |
| 71-80          | 6         | 3.03%   |
| 111-120        | 6         | 3.03%   |
| 501-1000       | 6         | 3.03%   |
| More than 1000 | 5         | 2.53%   |
| 151-200        | 5         | 2.53%   |
| 141-150        | 3         | 1.52%   |
| 41-50          | 2         | 1.01%   |
| 1-40           | 2         | 1.01%   |
| 61-70          | 1         | 0.51%   |
| 91-100         | 1         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 54        | 27.98%  |
| 121-160       | 51        | 26.42%  |
| 101-120       | 36        | 18.65%  |
| 161-240       | 25        | 12.95%  |
| Unknown       | 15        | 7.77%   |
| More than 240 | 8         | 4.15%   |
| 1-50          | 4         | 2.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 139       | 72.77%  |
| 2     | 26        | 13.61%  |
| 0     | 16        | 8.38%   |
| 3     | 8         | 4.19%   |
| 4     | 2         | 1.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 114       | 40.28%  |
| Realtek Semiconductor           | 95        | 33.57%  |
| MediaTek                        | 15        | 5.3%    |
| Qualcomm Atheros                | 12        | 4.24%   |
| Broadcom                        | 10        | 3.53%   |
| Xiaomi                          | 4         | 1.41%   |
| Qualcomm                        | 3         | 1.06%   |
| Broadcom Limited                | 3         | 1.06%   |
| ASIX Electronics                | 3         | 1.06%   |
| Qualcomm Atheros Communications | 2         | 0.71%   |
| Microsoft                       | 2         | 0.71%   |
| ICS Advent                      | 2         | 0.71%   |
| Aquantia                        | 2         | 0.71%   |
| Wilocity                        | 1         | 0.35%   |
| Sierra Wireless                 | 1         | 0.35%   |
| Samsung Electronics             | 1         | 0.35%   |
| Ralink                          | 1         | 0.35%   |
| OpenMoko                        | 1         | 0.35%   |
| Nvidia                          | 1         | 0.35%   |
| NetGear                         | 1         | 0.35%   |
| Mellanox Technologies           | 1         | 0.35%   |
| Marvell Technology Group        | 1         | 0.35%   |
| Lenovo                          | 1         | 0.35%   |
| Insyde Software                 | 1         | 0.35%   |
| Huawei Technologies             | 1         | 0.35%   |
| Hewlett-Packard                 | 1         | 0.35%   |
| Edimax Technology               | 1         | 0.35%   |
| Dell                            | 1         | 0.35%   |
| Arduino SA                      | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 62        | 18.13%  |
| Intel Wi-Fi 6 AX200                                                     | 22        | 6.43%   |
| Realtek RTL8125 2.5GbE Controller                                       | 18        | 5.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 16        | 4.68%   |
| Intel I211 Gigabit Network Connection                                   | 15        | 4.39%   |
| Intel Ethernet Controller I225-V                                        | 14        | 4.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 2.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.46%   |
| Intel Wireless-AC 9260                                                  | 5         | 1.46%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 1.17%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 1.17%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 4         | 1.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 1.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 0.88%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 3         | 0.88%   |
| Intel Wireless 8260                                                     | 3         | 0.88%   |
| Intel Ethernet Connection (7) I219-V                                    | 3         | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                    | 3         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.88%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                        | 3         | 0.88%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 2         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.58%   |
| Microsoft Xbox Wireless Adapter for Windows                             | 2         | 0.58%   |
| Intel I350 Gigabit Network Connection                                   | 2         | 0.58%   |
| Intel Ethernet Connection I217-V                                        | 2         | 0.58%   |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 0.58%   |
| Intel Ethernet Connection (17) I219-LM                                  | 2         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 83        | 58.04%  |
| Realtek Semiconductor           | 15        | 10.49%  |
| MediaTek                        | 15        | 10.49%  |
| Qualcomm Atheros                | 10        | 6.99%   |
| Broadcom                        | 4         | 2.8%    |
| Qualcomm                        | 3         | 2.1%    |
| Broadcom Limited                | 3         | 2.1%    |
| Qualcomm Atheros Communications | 2         | 1.4%    |
| Microsoft                       | 2         | 1.4%    |
| Wilocity                        | 1         | 0.7%    |
| Sierra Wireless                 | 1         | 0.7%    |
| Ralink                          | 1         | 0.7%    |
| NetGear                         | 1         | 0.7%    |
| Edimax Technology               | 1         | 0.7%    |
| Dell                            | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 22        | 15.28%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 16        | 11.11%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 4.86%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 4.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.47%   |
| Intel Wireless-AC 9260                                                  | 5         | 3.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 3.47%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 2.78%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 2.78%   |
| Intel Wireless 8265 / 8275                                              | 4         | 2.78%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 4         | 2.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 2.08%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 3         | 2.08%   |
| Intel Wireless 8260                                                     | 3         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 2.08%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.39%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 1.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.39%   |
| Microsoft Xbox Wireless Adapter for Windows                             | 2         | 1.39%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.39%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                      | 1         | 0.69%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.69%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                  | 1         | 0.69%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.69%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.69%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.69%   |
| NetGear WNDA3100v2 802.11abgn [Broadcom BCM4323]                        | 1         | 0.69%   |
| Intel Wireless 7265                                                     | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 89        | 48.37%  |
| Intel                    | 68        | 36.96%  |
| Broadcom                 | 6         | 3.26%   |
| Xiaomi                   | 4         | 2.17%   |
| Qualcomm Atheros         | 4         | 2.17%   |
| ASIX Electronics         | 3         | 1.63%   |
| ICS Advent               | 2         | 1.09%   |
| Aquantia                 | 2         | 1.09%   |
| Samsung Electronics      | 1         | 0.54%   |
| Nvidia                   | 1         | 0.54%   |
| Marvell Technology Group | 1         | 0.54%   |
| Lenovo                   | 1         | 0.54%   |
| Insyde Software          | 1         | 0.54%   |
| Hewlett-Packard          | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 62        | 31.96%  |
| Realtek RTL8125 2.5GbE Controller                                     | 18        | 9.28%   |
| Intel I211 Gigabit Network Connection                                 | 15        | 7.73%   |
| Intel Ethernet Controller I225-V                                      | 14        | 7.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 6         | 3.09%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 4         | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 4         | 2.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 3         | 1.55%   |
| Intel Ethernet Connection (7) I219-V                                  | 3         | 1.55%   |
| Intel Ethernet Connection (2) I219-V                                  | 3         | 1.55%   |
| Intel Ethernet Connection (2) I219-LM                                 | 3         | 1.55%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 3         | 1.55%   |
| Realtek Killer E3000 2.5GbE Controller                                | 2         | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 2         | 1.03%   |
| Intel I350 Gigabit Network Connection                                 | 2         | 1.03%   |
| Intel Ethernet Connection I217-V                                      | 2         | 1.03%   |
| Intel Ethernet Connection (5) I219-LM                                 | 2         | 1.03%   |
| Intel Ethernet Connection (17) I219-LM                                | 2         | 1.03%   |
| Intel Ethernet Connection (11) I219-LM                                | 2         | 1.03%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 2         | 1.03%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 2         | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                         | 2         | 1.03%   |
| Samsung Galaxy series, misc. (tethering mode)                         | 1         | 0.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                       | 1         | 0.52%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                            | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                 | 1         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                              | 1         | 0.52%   |
| Nvidia MCP79 Ethernet                                                 | 1         | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller               | 1         | 0.52%   |
| Lenovo USB-C Dock Ethernet                                            | 1         | 0.52%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                   | 1         | 0.52%   |
| Intel I210 Gigabit Network Connection                                 | 1         | 0.52%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                         | 1         | 0.52%   |
| Intel Ethernet Controller I226-V                                      | 1         | 0.52%   |
| Intel Ethernet Controller (2) I225-LMvP                               | 1         | 0.52%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                      | 1         | 0.52%   |
| Intel Ethernet Connection I219-V                                      | 1         | 0.52%   |
| Intel Ethernet Connection I217-LM                                     | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1         | 0.52%   |
| Intel Ethernet Connection (16) I219-LM                                | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 165       | 54.28%  |
| WiFi     | 135       | 44.41%  |
| Modem    | 3         | 0.99%   |
| Unknown  | 1         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 110       | 57.89%  |
| WiFi     | 80        | 42.11%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 101       | 53.72%  |
| 1     | 65        | 34.57%  |
| 3     | 12        | 6.38%   |
| 4     | 3         | 1.6%    |
| 7     | 2         | 1.06%   |
| 6     | 2         | 1.06%   |
| 0     | 2         | 1.06%   |
| 5     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 130       | 68.78%  |
| Yes  | 59        | 31.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 60%     |
| Realtek Semiconductor           | 10        | 8%      |
| MediaTek                        | 7         | 5.6%    |
| IMC Networks                    | 7         | 5.6%    |
| Foxconn / Hon Hai               | 5         | 4%      |
| Broadcom                        | 4         | 3.2%    |
| USI                             | 3         | 2.4%    |
| Lite-On Technology              | 3         | 2.4%    |
| Cambridge Silicon Radio         | 3         | 2.4%    |
| Realtek                         | 2         | 1.6%    |
| ASUSTek Computer                | 2         | 1.6%    |
| Qualcomm Atheros Communications | 1         | 0.8%    |
| Dell                            | 1         | 0.8%    |
| Apple                           | 1         | 0.8%    |
| Alps Electric                   | 1         | 0.8%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 22        | 17.6%   |
| Intel AX210 Bluetooth                               | 13        | 10.4%   |
| Realtek Bluetooth Radio                             | 10        | 8%      |
| Intel Bluetooth wireless interface                  | 10        | 8%      |
| Intel AX201 Bluetooth                               | 10        | 8%      |
| Intel Bluetooth Device                              | 9         | 7.2%    |
| MediaTek Wireless_Device                            | 7         | 5.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 4%      |
| IMC Networks Wireless_Device                        | 5         | 4%      |
| USI Bluetooth Device                                | 3         | 2.4%    |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 2.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.4%    |
| Realtek Bluetooth Radio                             | 2         | 1.6%    |
| IMC Networks Bluetooth Radio                        | 2         | 1.6%    |
| Broadcom HP Portable SoftSailing                    | 2         | 1.6%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.8%    |
| Lite-On Wireless_Device                             | 1         | 0.8%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.8%    |
| Lite-On Bluetooth Device                            | 1         | 0.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 0.8%    |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 1         | 0.8%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.8%    |
| Dell Wireless 365 Bluetooth                         | 1         | 0.8%    |
| Broadcom BCM20702A0                                 | 1         | 0.8%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.8%    |
| ASUS Bluetooth Device                               | 1         | 0.8%    |
| ASUS ASUS USB-BT500                                 | 1         | 0.8%    |
| Apple Bluetooth Host Controller                     | 1         | 0.8%    |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 0.8%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 90        | 29.32%  |
| AMD                                  | 84        | 27.36%  |
| Nvidia                               | 61        | 19.87%  |
| ASUSTek Computer                     | 12        | 3.91%   |
| C-Media Electronics                  | 10        | 3.26%   |
| SteelSeries ApS                      | 3         | 0.98%   |
| Razer USA                            | 3         | 0.98%   |
| Creative Labs                        | 3         | 0.98%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.65%   |
| Solid State Logic                    | 2         | 0.65%   |
| Lenovo                               | 2         | 0.65%   |
| Kingston Technology                  | 2         | 0.65%   |
| Audient                              | 2         | 0.65%   |
| AKG C44-USB Microphone               | 2         | 0.65%   |
| Yamaha                               | 1         | 0.33%   |
| VIA Technologies                     | 1         | 0.33%   |
| Texas Instruments                    | 1         | 0.33%   |
| TEAC                                 | 1         | 0.33%   |
| Sony                                 | 1         | 0.33%   |
| Schiit Audio                         | 1         | 0.33%   |
| Scarlett                             | 1         | 0.33%   |
| SAVITECH                             | 1         | 0.33%   |
| RODE Microphones                     | 1         | 0.33%   |
| Microsoft                            | 1         | 0.33%   |
| Micro Star International             | 1         | 0.33%   |
| Medeli Electronics                   | 1         | 0.33%   |
| MAG Technology                       | 1         | 0.33%   |
| M-Audio                              | 1         | 0.33%   |
| Logitech                             | 1         | 0.33%   |
| JMTek                                | 1         | 0.33%   |
| Huawei Technologies                  | 1         | 0.33%   |
| GYROCOM C&C                          | 1         | 0.33%   |
| Elgato Systems                       | 1         | 0.33%   |
| DSEA A/S                             | 1         | 0.33%   |
| DCMT Technology                      | 1         | 0.33%   |
| Corsair                              | 1         | 0.33%   |
| BEHRINGER International              | 1         | 0.33%   |
| AudioQuest                           | 1         | 0.33%   |
| ASRock                               | 1         | 0.33%   |
| ARCAM                                | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 36        | 9.47%   |
| AMD Starship/Matisse HD Audio Controller                                   | 21        | 5.53%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 4.74%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 18        | 4.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 14        | 3.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 9         | 2.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 2.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 2.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 2.11%   |
| ASUSTek Computer USB Audio                                                 | 7         | 1.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 1.84%   |
| Nvidia TU104 HD Audio Controller                                           | 6         | 1.58%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 1.58%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 1.58%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5         | 1.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.32%   |
| AMD Navi 31 [Radeon RX 7000 HDMI Audio]                                    | 5         | 1.32%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.05%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 1.05%   |
| Nvidia GA102 High Definition Audio Controller                              | 4         | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.05%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 1.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.05%   |
| Nvidia AD102 High Definition Audio Controller                              | 3         | 0.79%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 0.79%   |
| Thesycon Systemsoftware & Consulting SABAJ USB AUDIO                       | 2         | 0.53%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.53%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.53%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2         | 0.53%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.53%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.53%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 18.65%  |
| G.Skill             | 26        | 13.47%  |
| SK hynix            | 24        | 12.44%  |
| Corsair             | 22        | 11.4%   |
| Micron Technology   | 18        | 9.33%   |
| Crucial             | 18        | 9.33%   |
| Kingston            | 15        | 7.77%   |
| Unknown             | 14        | 7.25%   |
| Team                | 4         | 2.07%   |
| Nanya Technology    | 3         | 1.55%   |
| A-DATA Technology   | 3         | 1.55%   |
| Patriot             | 2         | 1.04%   |
| Elpida              | 2         | 1.04%   |
| Unknown (ABCD)      | 1         | 0.52%   |
| SGS/Thomson         | 1         | 0.52%   |
| Patriot Memory      | 1         | 0.52%   |
| HPE                 | 1         | 0.52%   |
| Hewlett-Packard     | 1         | 0.52%   |
| GSkill              | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 4         | 1.98%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s             | 4         | 1.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.49%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.49%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 3         | 1.49%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s             | 3         | 1.49%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3400MT/s         | 3         | 1.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2         | 0.99%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 2         | 0.99%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.99%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.99%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.99%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 2         | 0.99%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.99%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.99%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.99%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 0.99%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.99%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 2         | 0.99%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 0.99%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s            | 2         | 0.99%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM 1066MT/s                             | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                          | 1         | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 0.5%    |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.5%    |
| Team RAM Elite-800 2GB DIMM SDRAM 2048MT/s                       | 1         | 0.5%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.5%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.5%    |
| SK hynix RAM Module 16GB DIMM DDR4 2133MT/s                      | 1         | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 93        | 52.54%  |
| DDR3    | 36        | 20.34%  |
| DDR5    | 24        | 13.56%  |
| LPDDR4  | 7         | 3.95%   |
| DDR2    | 7         | 3.95%   |
| LPDDR5  | 3         | 1.69%   |
| Unknown | 3         | 1.69%   |
| SDRAM   | 2         | 1.13%   |
| LPDDR3  | 1         | 0.56%   |
| DDR     | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 92        | 51.4%   |
| SODIMM       | 76        | 42.46%  |
| Row Of Chips | 11        | 6.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 63        | 33.87%  |
| 16384 | 52        | 27.96%  |
| 32768 | 27        | 14.52%  |
| 4096  | 27        | 14.52%  |
| 2048  | 13        | 6.99%   |
| 1024  | 3         | 1.61%   |
| 512   | 1         | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 38        | 20.54%  |
| 1600    | 23        | 12.43%  |
| 2667    | 14        | 7.57%   |
| 3600    | 12        | 6.49%   |
| 4800    | 11        | 5.95%   |
| 6400    | 9         | 4.86%   |
| 2400    | 7         | 3.78%   |
| 1333    | 7         | 3.78%   |
| 4267    | 6         | 3.24%   |
| 2133    | 5         | 2.7%    |
| 6000    | 4         | 2.16%   |
| 3400    | 4         | 2.16%   |
| 1866    | 4         | 2.16%   |
| 667     | 4         | 2.16%   |
| 3866    | 3         | 1.62%   |
| 3666    | 3         | 1.62%   |
| 2666    | 3         | 1.62%   |
| 1334    | 3         | 1.62%   |
| 800     | 3         | 1.62%   |
| 5200    | 2         | 1.08%   |
| 3800    | 2         | 1.08%   |
| 3466    | 2         | 1.08%   |
| 2048    | 2         | 1.08%   |
| Unknown | 2         | 1.08%   |
| 8400    | 1         | 0.54%   |
| 5600    | 1         | 0.54%   |
| 3933    | 1         | 0.54%   |
| 3733    | 1         | 0.54%   |
| 3534    | 1         | 0.54%   |
| 3533    | 1         | 0.54%   |
| 3100    | 1         | 0.54%   |
| 2933    | 1         | 0.54%   |
| 1067    | 1         | 0.54%   |
| 1066    | 1         | 0.54%   |
| 533     | 1         | 0.54%   |
| 333     | 1         | 0.54%   |

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
| Chicony Electronics           | 20        | 21.51%  |
| Microdia                      | 12        | 12.9%   |
| Logitech                      | 9         | 9.68%   |
| Quanta                        | 6         | 6.45%   |
| Luxvisions Innotech Limited   | 6         | 6.45%   |
| Sunplus Innovation Technology | 5         | 5.38%   |
| IMC Networks                  | 5         | 5.38%   |
| Bison Electronics             | 5         | 5.38%   |
| Microsoft                     | 4         | 4.3%    |
| Samsung Electronics           | 2         | 2.15%   |
| Realtek Semiconductor         | 2         | 2.15%   |
| MacroSilicon                  | 2         | 2.15%   |
| Apple                         | 2         | 2.15%   |
| Suyin                         | 1         | 1.08%   |
| SunplusIT                     | 1         | 1.08%   |
| Sunplus Technology            | 1         | 1.08%   |
| Silicon Motion                | 1         | 1.08%   |
| ShineTech                     | 1         | 1.08%   |
| Lite-On Technology            | 1         | 1.08%   |
| kingcome                      | 1         | 1.08%   |
| Holitech                      | 1         | 1.08%   |
| Genesys Logic                 | 1         | 1.08%   |
| GEMBIRD                       | 1         | 1.08%   |
| Elgato Systems                | 1         | 1.08%   |
| Acer                          | 1         | 1.08%   |
| A4Tech                        | 1         | 1.08%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 8         | 8.6%    |
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 4.3%    |
| Microdia Integrated_Webcam_HD                        | 3         | 3.23%   |
| Microdia Integrated_Webcam_FHD                       | 3         | 3.23%   |
| Logitech C922 Pro Stream Webcam                      | 3         | 3.23%   |
| Samsung Galaxy A5 (MTP)                              | 2         | 2.15%   |
| Quanta HD User Facing                                | 2         | 2.15%   |
| Microdia REDRAGON Live Camera Audio                  | 2         | 2.15%   |
| MacroSilicon USB Video                               | 2         | 2.15%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 2         | 2.15%   |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 2.15%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 2.15%   |
| Logitech HD Pro Webcam C920                          | 2         | 2.15%   |
| Chicony HP HD Camera                                 | 2         | 2.15%   |
| Chicony HD WebCam                                    | 2         | 2.15%   |
| Bison Integrated Camera                              | 2         | 2.15%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 2         | 2.15%   |
| Suyin HP Truevision HD                               | 1         | 1.08%   |
| SunplusIT 720p HD Camera                             | 1         | 1.08%   |
| Sunplus 1.3M HD WebCam                               | 1         | 1.08%   |
| Sunplus XiaoMi USB 2.0 Webcam                        | 1         | 1.08%   |
| Sunplus MiraBox Video Capture                        | 1         | 1.08%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.08%   |
| Sunplus Integrated_Webcam_FHD                        | 1         | 1.08%   |
| Sunplus Full HD webcam                               | 1         | 1.08%   |
| Silicon Motion 300k Pixel Camera                     | 1         | 1.08%   |
| ShineTech HD Camera                                  | 1         | 1.08%   |
| Realtek USB Camera                                   | 1         | 1.08%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.08%   |
| Quanta VGA WebCam                                    | 1         | 1.08%   |
| Quanta RGB-IR Camera                                 | 1         | 1.08%   |
| Quanta HP TrueVision HD Camera                       | 1         | 1.08%   |
| Quanta hm1091_techfront                              | 1         | 1.08%   |
| Microsoft Surface Camera Front                       | 1         | 1.08%   |
| Microsoft MicrosoftÂ LifeCam Studio                 | 1         | 1.08%   |
| Microsoft MicrosoftÂ LifeCam Cinema                 | 1         | 1.08%   |
| Microsoft LifeCam Cinema                             | 1         | 1.08%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 1.08%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam       | 1         | 1.08%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 35%     |
| Synaptics                  | 7         | 35%     |
| Shenzhen Goodix Technology | 5         | 25%     |
| LighTuning Technology      | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                        | 4         | 20%     |
| Synaptics UWP WBDI Device                                  | 3         | 15%     |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 10%     |
| Validity Sensors Synaptics WBDI                            | 2         | 10%     |
| Validity Sensors Fingerprint scanner                       | 2         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 10%     |
| Validity Sensors VFS491                                    | 1         | 5%      |
| Synaptics WBDI                                             | 1         | 5%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5%      |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 5         | 33.33%  |
| Alcor Micro                       | 3         | 20%     |
| SCM Microsystems                  | 1         | 6.67%   |
| O2 Micro                          | 1         | 6.67%   |
| Hewlett-Packard                   | 1         | 6.67%   |
| Free Software Initiative of Japan | 1         | 6.67%   |
| Clay Logic                        | 1         | 6.67%   |
| Bit4id                            | 1         | 6.67%   |
| Advanced Card Systems             | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 3         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 20%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 6.67%   |
| Free Software Initiative of Japan Gnuk Token                                 | 1         | 6.67%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 6.67%   |
| Broadcom 5880                                                                | 1         | 6.67%   |
| Bit4id miniLector-s                                                          | 1         | 6.67%   |
| Advanced Card Systems ACR122U                                                | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 89        | 45.88%  |
| 1     | 54        | 27.84%  |
| 2     | 23        | 11.86%  |
| 3     | 12        | 6.19%   |
| 4     | 7         | 3.61%   |
| 6     | 4         | 2.06%   |
| 5     | 4         | 2.06%   |
| 7     | 1         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 31        | 16.85%  |
| Bluetooth                | 25        | 13.59%  |
| Net/wireless             | 21        | 11.41%  |
| Communication controller | 20        | 10.87%  |
| Fingerprint reader       | 19        | 10.33%  |
| Camera                   | 15        | 8.15%   |
| Sound                    | 10        | 5.43%   |
| Multimedia controller    | 10        | 5.43%   |
| Chipcard                 | 10        | 5.43%   |
| Network                  | 6         | 3.26%   |
| Net/ethernet             | 4         | 2.17%   |
| Storage/ide              | 3         | 1.63%   |
| Firewire controller      | 3         | 1.63%   |
| Card reader              | 3         | 1.63%   |
| Storage/ata              | 2         | 1.09%   |
| Unassigned class         | 1         | 0.54%   |
| Storage/raid             | 1         | 0.54%   |

