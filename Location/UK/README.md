Linux in UK - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UK/Desktop/README.md) and [notebooks](/Location/UK/Notebook/README.md).

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

Total: 8954

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 1545               | Notebook    | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | Notebook    | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [12f0d9358a](https://linux-hardware.org/?probe=12f0d9358a) | Oct 01, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [8eaded9cb5](https://linux-hardware.org/?probe=8eaded9cb5) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [cfd0c22e29](https://linux-hardware.org/?probe=cfd0c22e29) | Sep 30, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [f6e2c51367](https://linux-hardware.org/?probe=f6e2c51367) | Sep 30, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [ab0a3e1a94](https://linux-hardware.org/?probe=ab0a3e1a94) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [dab0a00c02](https://linux-hardware.org/?probe=dab0a00c02) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9737fcadf](https://linux-hardware.org/?probe=e9737fcadf) | Sep 30, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [f0eae50061](https://linux-hardware.org/?probe=f0eae50061) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8c116d30f9](https://linux-hardware.org/?probe=8c116d30f9) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c4ccdf9992](https://linux-hardware.org/?probe=c4ccdf9992) | Sep 30, 2022 |
| Dell          | Latitude 7430               | Notebook    | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| HP            | Compaq 6720s                | Notebook    | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Dell          | Inspiron 1564               | Notebook    | [d9dd05aa12](https://linux-hardware.org/?probe=d9dd05aa12) | Sep 29, 2022 |
| Supermicro    | X10SRA-F                    | Server      | [a9aa07ef24](https://linux-hardware.org/?probe=a9aa07ef24) | Sep 28, 2022 |
| Supermicro    | X10SRA-F                    | Server      | [2f41a520ed](https://linux-hardware.org/?probe=2f41a520ed) | Sep 28, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6f1ecca2f0](https://linux-hardware.org/?probe=6f1ecca2f0) | Sep 28, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [7b96f1db41](https://linux-hardware.org/?probe=7b96f1db41) | Sep 28, 2022 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [ac93c3912d](https://linux-hardware.org/?probe=ac93c3912d) | Sep 28, 2022 |
| Medion        | MS-7713                     | Desktop     | [36ca6b7f38](https://linux-hardware.org/?probe=36ca6b7f38) | Sep 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9f85096ed9](https://linux-hardware.org/?probe=9f85096ed9) | Sep 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| HP            | 3031h                       | Desktop     | [8aa316f69f](https://linux-hardware.org/?probe=8aa316f69f) | Sep 27, 2022 |
| HP            | 3031h                       | Desktop     | [8e4696435d](https://linux-hardware.org/?probe=8e4696435d) | Sep 27, 2022 |
| Dell          | 03NVJ6 A03                  | Desktop     | [2241dbc067](https://linux-hardware.org/?probe=2241dbc067) | Sep 26, 2022 |
| Dell          | 03NVJ6 A03                  | Desktop     | [2deb1ce174](https://linux-hardware.org/?probe=2deb1ce174) | Sep 26, 2022 |
| ASUSTek       | P5N7A-VM                    | Desktop     | [e8ac8a9926](https://linux-hardware.org/?probe=e8ac8a9926) | Sep 26, 2022 |
| ASUSTek       | P5N7A-VM                    | Desktop     | [86580fe9f2](https://linux-hardware.org/?probe=86580fe9f2) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6373bf42ef](https://linux-hardware.org/?probe=6373bf42ef) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9ff2009089](https://linux-hardware.org/?probe=9ff2009089) | Sep 26, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [601591c97e](https://linux-hardware.org/?probe=601591c97e) | Sep 26, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [533cc3b3ae](https://linux-hardware.org/?probe=533cc3b3ae) | Sep 26, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8af0b5fe75](https://linux-hardware.org/?probe=8af0b5fe75) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [c3305d9bff](https://linux-hardware.org/?probe=c3305d9bff) | Sep 26, 2022 |
| Jumper        | EZbook                      | Notebook    | [1af58cd7e7](https://linux-hardware.org/?probe=1af58cd7e7) | Sep 25, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [ba4b216db1](https://linux-hardware.org/?probe=ba4b216db1) | Sep 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bc6b161dc9](https://linux-hardware.org/?probe=bc6b161dc9) | Sep 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [1ccf6c5c41](https://linux-hardware.org/?probe=1ccf6c5c41) | Sep 25, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [21121aa007](https://linux-hardware.org/?probe=21121aa007) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | Notebook    | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [cfda1aa63a](https://linux-hardware.org/?probe=cfda1aa63a) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 23476Y7       | Notebook    | [8488ad9e53](https://linux-hardware.org/?probe=8488ad9e53) | Sep 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [bdc8453efc](https://linux-hardware.org/?probe=bdc8453efc) | Sep 24, 2022 |
| Dell          | 0NW73C A00                  | Desktop     | [77cf7277d5](https://linux-hardware.org/?probe=77cf7277d5) | Sep 24, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [eef9de3daf](https://linux-hardware.org/?probe=eef9de3daf) | Sep 24, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [b9e88a43d8](https://linux-hardware.org/?probe=b9e88a43d8) | Sep 24, 2022 |
| Dell          | 0NW73C A00                  | Desktop     | [80835077a4](https://linux-hardware.org/?probe=80835077a4) | Sep 24, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [542249f675](https://linux-hardware.org/?probe=542249f675) | Sep 24, 2022 |
| Lenovo        | ThinkPad T440s 20ARA0YL0... | Notebook    | [93eedc638b](https://linux-hardware.org/?probe=93eedc638b) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [dc3a97d467](https://linux-hardware.org/?probe=dc3a97d467) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [02787c733c](https://linux-hardware.org/?probe=02787c733c) | Sep 23, 2022 |
| ASUSTek       | N750JV                      | Notebook    | [f69fe7dacf](https://linux-hardware.org/?probe=f69fe7dacf) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [fe7ae61ecd](https://linux-hardware.org/?probe=fe7ae61ecd) | Sep 23, 2022 |
| Dell          | 0NW73C A00                  | Desktop     | [7d50214415](https://linux-hardware.org/?probe=7d50214415) | Sep 23, 2022 |
| Dell          | Latitude E6330              | Notebook    | [5f1a272734](https://linux-hardware.org/?probe=5f1a272734) | Sep 23, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [0c47cbc25d](https://linux-hardware.org/?probe=0c47cbc25d) | Sep 23, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [53fc678043](https://linux-hardware.org/?probe=53fc678043) | Sep 23, 2022 |
| Dell          | Latitude 5411               | Notebook    | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [4867faffbf](https://linux-hardware.org/?probe=4867faffbf) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| Dell          | 0YU822 A00                  | Desktop     | [034dbdc359](https://linux-hardware.org/?probe=034dbdc359) | Sep 22, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c4915d8dd2](https://linux-hardware.org/?probe=c4915d8dd2) | Sep 22, 2022 |
| MSI           | GL73 8RD                    | Notebook    | [f197efe030](https://linux-hardware.org/?probe=f197efe030) | Sep 22, 2022 |
| MSI           | GL73 8RD                    | Notebook    | [0534ef55fc](https://linux-hardware.org/?probe=0534ef55fc) | Sep 22, 2022 |
| Dell          | 0D28YY A03                  | Desktop     | [24230f3e30](https://linux-hardware.org/?probe=24230f3e30) | Sep 21, 2022 |
| HP            | 829A                        | Mini pc     | [9fbbfa249d](https://linux-hardware.org/?probe=9fbbfa249d) | Sep 21, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [03428c1a17](https://linux-hardware.org/?probe=03428c1a17) | Sep 21, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [c859bf5e24](https://linux-hardware.org/?probe=c859bf5e24) | Sep 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [721ede2e11](https://linux-hardware.org/?probe=721ede2e11) | Sep 20, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [16d661b4e5](https://linux-hardware.org/?probe=16d661b4e5) | Sep 20, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [20c7b9dcf9](https://linux-hardware.org/?probe=20c7b9dcf9) | Sep 20, 2022 |
| Lenovo        | E50-80 80J2                 | Notebook    | [a399d96de2](https://linux-hardware.org/?probe=a399d96de2) | Sep 20, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [5b55138f5d](https://linux-hardware.org/?probe=5b55138f5d) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [6c7d6ef178](https://linux-hardware.org/?probe=6c7d6ef178) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [e60653a4c7](https://linux-hardware.org/?probe=e60653a4c7) | Sep 20, 2022 |
| Lenovo        | Legion 5-15ACH6H 82JU       | Notebook    | [1f48647e32](https://linux-hardware.org/?probe=1f48647e32) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [dd2687098a](https://linux-hardware.org/?probe=dd2687098a) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [92d0d41e58](https://linux-hardware.org/?probe=92d0d41e58) | Sep 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [6b6ad790c5](https://linux-hardware.org/?probe=6b6ad790c5) | Sep 19, 2022 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [7b17bd93c0](https://linux-hardware.org/?probe=7b17bd93c0) | Sep 19, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [3ee25cf1e4](https://linux-hardware.org/?probe=3ee25cf1e4) | Sep 19, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [060f3bd895](https://linux-hardware.org/?probe=060f3bd895) | Sep 19, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [3f3cb3be79](https://linux-hardware.org/?probe=3f3cb3be79) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8d2c35d5f2](https://linux-hardware.org/?probe=8d2c35d5f2) | Sep 19, 2022 |
| Panasonic     | CF-53JAWZYDE                | Notebook    | [f8b1ca10d1](https://linux-hardware.org/?probe=f8b1ca10d1) | Sep 19, 2022 |
| Lenovo        | E50-80 80J2                 | Notebook    | [1a538a3132](https://linux-hardware.org/?probe=1a538a3132) | Sep 18, 2022 |
| Dell          | Studio 1737                 | Notebook    | [7218731367](https://linux-hardware.org/?probe=7218731367) | Sep 18, 2022 |
| Acer          | Aspire M3970                | Desktop     | [e366f1be3b](https://linux-hardware.org/?probe=e366f1be3b) | Sep 18, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [eb619ed1c5](https://linux-hardware.org/?probe=eb619ed1c5) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [fa4082533e](https://linux-hardware.org/?probe=fa4082533e) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [a418c3e997](https://linux-hardware.org/?probe=a418c3e997) | Sep 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a5d838868a](https://linux-hardware.org/?probe=a5d838868a) | Sep 18, 2022 |
| Dell          | Precision 5530              | Notebook    | [8fc00af945](https://linux-hardware.org/?probe=8fc00af945) | Sep 18, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [1f27376b8e](https://linux-hardware.org/?probe=1f27376b8e) | Sep 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0760539d3d](https://linux-hardware.org/?probe=0760539d3d) | Sep 18, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [c1045050d6](https://linux-hardware.org/?probe=c1045050d6) | Sep 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [1e27521b13](https://linux-hardware.org/?probe=1e27521b13) | Sep 17, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [3f20a5e69d](https://linux-hardware.org/?probe=3f20a5e69d) | Sep 17, 2022 |
| Dell          | Latitude 7390               | Notebook    | [64c9b13553](https://linux-hardware.org/?probe=64c9b13553) | Sep 17, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [2299dc1786](https://linux-hardware.org/?probe=2299dc1786) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [36a7673265](https://linux-hardware.org/?probe=36a7673265) | Sep 17, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [0c3d62f1c9](https://linux-hardware.org/?probe=0c3d62f1c9) | Sep 17, 2022 |
| Teclast       | X4                          | Tablet      | [acfc04d7fa](https://linux-hardware.org/?probe=acfc04d7fa) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [c4dd2bf91f](https://linux-hardware.org/?probe=c4dd2bf91f) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| Teclast       | X4                          | Tablet      | [2279670078](https://linux-hardware.org/?probe=2279670078) | Sep 17, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [379aaf7b61](https://linux-hardware.org/?probe=379aaf7b61) | Sep 16, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6341f27d68](https://linux-hardware.org/?probe=6341f27d68) | Sep 16, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [8d9f049d7e](https://linux-hardware.org/?probe=8d9f049d7e) | Sep 16, 2022 |
| Acidanther... | iMac19,2                    | Notebook    | [94b79ac6e5](https://linux-hardware.org/?probe=94b79ac6e5) | Sep 16, 2022 |
| HP            | ProBook 4340s               | Notebook    | [acca12f9d4](https://linux-hardware.org/?probe=acca12f9d4) | Sep 16, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [4d4809282a](https://linux-hardware.org/?probe=4d4809282a) | Sep 16, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [54588ca345](https://linux-hardware.org/?probe=54588ca345) | Sep 16, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [f686754b27](https://linux-hardware.org/?probe=f686754b27) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [9adc000021](https://linux-hardware.org/?probe=9adc000021) | Sep 15, 2022 |
| Dell          | Latitude 7490               | Notebook    | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | 03TJ75 A00                  | Desktop     | [70ef579566](https://linux-hardware.org/?probe=70ef579566) | Sep 15, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [d923c9e35f](https://linux-hardware.org/?probe=d923c9e35f) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | Notebook    | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [82140783de](https://linux-hardware.org/?probe=82140783de) | Sep 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7ad1180946](https://linux-hardware.org/?probe=7ad1180946) | Sep 14, 2022 |
| Dell          | Latitude E7250              | Notebook    | [80a2e50cfc](https://linux-hardware.org/?probe=80a2e50cfc) | Sep 14, 2022 |
| iOTA          | Flo 360                     | Convertible | [4ec4159519](https://linux-hardware.org/?probe=4ec4159519) | Sep 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [44be9b9134](https://linux-hardware.org/?probe=44be9b9134) | Sep 13, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [b284db5ac4](https://linux-hardware.org/?probe=b284db5ac4) | Sep 13, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [a27c60fbde](https://linux-hardware.org/?probe=a27c60fbde) | Sep 13, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [38928465ac](https://linux-hardware.org/?probe=38928465ac) | Sep 13, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [f23afc903c](https://linux-hardware.org/?probe=f23afc903c) | Sep 13, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [2c5a122ce9](https://linux-hardware.org/?probe=2c5a122ce9) | Sep 12, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [ef3098c81a](https://linux-hardware.org/?probe=ef3098c81a) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4a54854cd7](https://linux-hardware.org/?probe=4a54854cd7) | Sep 12, 2022 |
| Entroware     | Orion                       | Notebook    | [d96888edf9](https://linux-hardware.org/?probe=d96888edf9) | Sep 12, 2022 |
| Entroware     | Orion                       | Notebook    | [c06e53ad80](https://linux-hardware.org/?probe=c06e53ad80) | Sep 12, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [743af62b4c](https://linux-hardware.org/?probe=743af62b4c) | Sep 12, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [e137564f6b](https://linux-hardware.org/?probe=e137564f6b) | Sep 12, 2022 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [3ae7faf18d](https://linux-hardware.org/?probe=3ae7faf18d) | Sep 11, 2022 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [4f27034766](https://linux-hardware.org/?probe=4f27034766) | Sep 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9a2030683a](https://linux-hardware.org/?probe=9a2030683a) | Sep 11, 2022 |
| Acer          | Aspire E5-576G              | Notebook    | [ee2635dbc8](https://linux-hardware.org/?probe=ee2635dbc8) | Sep 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [1e6331a36b](https://linux-hardware.org/?probe=1e6331a36b) | Sep 11, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [a36990dcf7](https://linux-hardware.org/?probe=a36990dcf7) | Sep 10, 2022 |
| ASUSTek       | P5N7A-VM                    | Desktop     | [ac23f75aa7](https://linux-hardware.org/?probe=ac23f75aa7) | Sep 10, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [9768e1fbf4](https://linux-hardware.org/?probe=9768e1fbf4) | Sep 10, 2022 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [2097faef20](https://linux-hardware.org/?probe=2097faef20) | Sep 10, 2022 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [4799406c7d](https://linux-hardware.org/?probe=4799406c7d) | Sep 10, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | Desktop     | [102cf248e9](https://linux-hardware.org/?probe=102cf248e9) | Sep 10, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [576eec419f](https://linux-hardware.org/?probe=576eec419f) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5997c6998f](https://linux-hardware.org/?probe=5997c6998f) | Sep 10, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [6d58a3f327](https://linux-hardware.org/?probe=6d58a3f327) | Sep 09, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [08e7851933](https://linux-hardware.org/?probe=08e7851933) | Sep 09, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [d71609c89e](https://linux-hardware.org/?probe=d71609c89e) | Sep 09, 2022 |
| Tactus        | GeoBook 110                 | Notebook    | [d13211f478](https://linux-hardware.org/?probe=d13211f478) | Sep 09, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [27de3ede0c](https://linux-hardware.org/?probe=27de3ede0c) | Sep 09, 2022 |
| Star Labs     | Lite                        | Notebook    | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d9c6274ead](https://linux-hardware.org/?probe=d9c6274ead) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f5c538e2c7](https://linux-hardware.org/?probe=f5c538e2c7) | Sep 09, 2022 |
| Acer          | Aspire C22-820              | All in one  | [7b21589632](https://linux-hardware.org/?probe=7b21589632) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b3aa7bd9ca](https://linux-hardware.org/?probe=b3aa7bd9ca) | Sep 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [36b349b529](https://linux-hardware.org/?probe=36b349b529) | Sep 09, 2022 |
| HP            | 1494                        | Desktop     | [5f0a73b28f](https://linux-hardware.org/?probe=5f0a73b28f) | Sep 09, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [ae1a9f37a7](https://linux-hardware.org/?probe=ae1a9f37a7) | Sep 08, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [7c3cdfba24](https://linux-hardware.org/?probe=7c3cdfba24) | Sep 08, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [b2cd3df6bc](https://linux-hardware.org/?probe=b2cd3df6bc) | Sep 08, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [478d0564a6](https://linux-hardware.org/?probe=478d0564a6) | Sep 08, 2022 |
| Dell          | 0MN1TX A02                  | Desktop     | [c9d50b8db9](https://linux-hardware.org/?probe=c9d50b8db9) | Sep 08, 2022 |
| Dell          | Precision 5770              | Notebook    | [41e44b27f4](https://linux-hardware.org/?probe=41e44b27f4) | Sep 08, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [408b0d3fd7](https://linux-hardware.org/?probe=408b0d3fd7) | Sep 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c750440eb3](https://linux-hardware.org/?probe=c750440eb3) | Sep 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [19a21d721c](https://linux-hardware.org/?probe=19a21d721c) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4ebd2a22bf](https://linux-hardware.org/?probe=4ebd2a22bf) | Sep 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGA039U... | Notebook    | [43c002ad40](https://linux-hardware.org/?probe=43c002ad40) | Sep 07, 2022 |
| Toshiba       | Satellite NB10t-A-101       | Notebook    | [b824e1e3d5](https://linux-hardware.org/?probe=b824e1e3d5) | Sep 06, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [15fe45edd7](https://linux-hardware.org/?probe=15fe45edd7) | Sep 06, 2022 |
| Toshiba       | Satellite A660              | Notebook    | [8a76871325](https://linux-hardware.org/?probe=8a76871325) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [a4f8e52425](https://linux-hardware.org/?probe=a4f8e52425) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [0daca2662d](https://linux-hardware.org/?probe=0daca2662d) | Sep 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [40d6a47565](https://linux-hardware.org/?probe=40d6a47565) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | Notebook    | [a75fed8b3f](https://linux-hardware.org/?probe=a75fed8b3f) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | Notebook    | [cd613ebcd2](https://linux-hardware.org/?probe=cd613ebcd2) | Sep 05, 2022 |
| Clevo         | P65_P67SE                   | Notebook    | [9a38027b73](https://linux-hardware.org/?probe=9a38027b73) | Sep 05, 2022 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [f0a6826f9d](https://linux-hardware.org/?probe=f0a6826f9d) | Sep 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [04c7e44198](https://linux-hardware.org/?probe=04c7e44198) | Sep 05, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [43f7cbff06](https://linux-hardware.org/?probe=43f7cbff06) | Sep 05, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [4641fe397a](https://linux-hardware.org/?probe=4641fe397a) | Sep 05, 2022 |
| HP            | 805A                        | Desktop     | [78b10fb63d](https://linux-hardware.org/?probe=78b10fb63d) | Sep 04, 2022 |
| Acer          | Aspire V5-552               | Notebook    | [031439a681](https://linux-hardware.org/?probe=031439a681) | Sep 04, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8c4261ac4f](https://linux-hardware.org/?probe=8c4261ac4f) | Sep 04, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [f6e3690dd8](https://linux-hardware.org/?probe=f6e3690dd8) | Sep 04, 2022 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [fb64be85f1](https://linux-hardware.org/?probe=fb64be85f1) | Sep 04, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [2d4eeaf028](https://linux-hardware.org/?probe=2d4eeaf028) | Sep 03, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [47a080e25c](https://linux-hardware.org/?probe=47a080e25c) | Sep 03, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [1822ab5853](https://linux-hardware.org/?probe=1822ab5853) | Sep 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [2c5c9d2233](https://linux-hardware.org/?probe=2c5c9d2233) | Sep 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d664029076](https://linux-hardware.org/?probe=d664029076) | Sep 02, 2022 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [d798ebf303](https://linux-hardware.org/?probe=d798ebf303) | Sep 02, 2022 |
| MSI           | X99A GAMING 7               | Desktop     | [347f4d8534](https://linux-hardware.org/?probe=347f4d8534) | Sep 02, 2022 |
| Gigabyte      | H310N x.x                   | Desktop     | [c6c8617f48](https://linux-hardware.org/?probe=c6c8617f48) | Sep 02, 2022 |
| Dell          | Precision 5530              | Notebook    | [0151d15e28](https://linux-hardware.org/?probe=0151d15e28) | Sep 02, 2022 |
| HP            | 8767 A                      | Desktop     | [62e70ef3e8](https://linux-hardware.org/?probe=62e70ef3e8) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [e9f6cafc6c](https://linux-hardware.org/?probe=e9f6cafc6c) | Sep 02, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [277340da8a](https://linux-hardware.org/?probe=277340da8a) | Sep 02, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bdae2c60cd](https://linux-hardware.org/?probe=bdae2c60cd) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [9cabeefea8](https://linux-hardware.org/?probe=9cabeefea8) | Sep 01, 2022 |
| ASUSTek       | N552VW                      | Notebook    | [99d4a9be86](https://linux-hardware.org/?probe=99d4a9be86) | Sep 01, 2022 |
| Lenovo        | ThinkPad T400 6474W7T       | Notebook    | [f9a9b12b37](https://linux-hardware.org/?probe=f9a9b12b37) | Sep 01, 2022 |
| Lenovo        | ThinkCentre M58e 7408BA5    | Desktop     | [4384314f98](https://linux-hardware.org/?probe=4384314f98) | Sep 01, 2022 |
| MSI           | H81M-P33                    | Desktop     | [8d15799ff9](https://linux-hardware.org/?probe=8d15799ff9) | Sep 01, 2022 |
| Dell          | Precision 5530              | Notebook    | [298ce27830](https://linux-hardware.org/?probe=298ce27830) | Sep 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [55073b08dc](https://linux-hardware.org/?probe=55073b08dc) | Sep 01, 2022 |
| Lenovo        | ThinkPad T400 6474W7T       | Notebook    | [b52974ac00](https://linux-hardware.org/?probe=b52974ac00) | Sep 01, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [7ff88a93c2](https://linux-hardware.org/?probe=7ff88a93c2) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3ea6fa4079](https://linux-hardware.org/?probe=3ea6fa4079) | Aug 31, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [f4d5b9fc69](https://linux-hardware.org/?probe=f4d5b9fc69) | Aug 31, 2022 |
| HP            | Pavilion g6                 | Notebook    | [cc725d880c](https://linux-hardware.org/?probe=cc725d880c) | Aug 31, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [edb6d4d6c2](https://linux-hardware.org/?probe=edb6d4d6c2) | Aug 31, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [36eb80672f](https://linux-hardware.org/?probe=36eb80672f) | Aug 31, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [a76390d5fc](https://linux-hardware.org/?probe=a76390d5fc) | Aug 31, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [555e7c0745](https://linux-hardware.org/?probe=555e7c0745) | Aug 30, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [7763040d56](https://linux-hardware.org/?probe=7763040d56) | Aug 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [1b38f48059](https://linux-hardware.org/?probe=1b38f48059) | Aug 30, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [e58163df64](https://linux-hardware.org/?probe=e58163df64) | Aug 30, 2022 |
| Dell          | Precision M6400             | Notebook    | [3cf32e24fa](https://linux-hardware.org/?probe=3cf32e24fa) | Aug 30, 2022 |
| Alienware     | 01NYPT A00                  | Desktop     | [cd95b79270](https://linux-hardware.org/?probe=cd95b79270) | Aug 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0da338038e](https://linux-hardware.org/?probe=0da338038e) | Aug 29, 2022 |
| Standard      | Unknown                     | Notebook    | [62e0164e5b](https://linux-hardware.org/?probe=62e0164e5b) | Aug 29, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [8a68d394b8](https://linux-hardware.org/?probe=8a68d394b8) | Aug 29, 2022 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [2d66cac294](https://linux-hardware.org/?probe=2d66cac294) | Aug 28, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [2d89536f80](https://linux-hardware.org/?probe=2d89536f80) | Aug 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [155267063a](https://linux-hardware.org/?probe=155267063a) | Aug 28, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [d8bd3d6fc6](https://linux-hardware.org/?probe=d8bd3d6fc6) | Aug 28, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [d67f262815](https://linux-hardware.org/?probe=d67f262815) | Aug 28, 2022 |
| Dell          | Studio 1735                 | Notebook    | [912f409b37](https://linux-hardware.org/?probe=912f409b37) | Aug 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | Notebook    | [1d29556c76](https://linux-hardware.org/?probe=1d29556c76) | Aug 28, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [148c6dd35a](https://linux-hardware.org/?probe=148c6dd35a) | Aug 28, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [5e6e789346](https://linux-hardware.org/?probe=5e6e789346) | Aug 28, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [f17bcbfc4b](https://linux-hardware.org/?probe=f17bcbfc4b) | Aug 28, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [4960a57d91](https://linux-hardware.org/?probe=4960a57d91) | Aug 28, 2022 |
| Lenovo        | ThinkPad 20M8S1K100         | Convertible | [4e77e4b1a0](https://linux-hardware.org/?probe=4e77e4b1a0) | Aug 27, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8841ba5f53](https://linux-hardware.org/?probe=8841ba5f53) | Aug 27, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [37bdc91d97](https://linux-hardware.org/?probe=37bdc91d97) | Aug 26, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [fa74c338ed](https://linux-hardware.org/?probe=fa74c338ed) | Aug 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [846791d8b9](https://linux-hardware.org/?probe=846791d8b9) | Aug 26, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [c8eb396b68](https://linux-hardware.org/?probe=c8eb396b68) | Aug 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [62ce95ce9c](https://linux-hardware.org/?probe=62ce95ce9c) | Aug 26, 2022 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [9839e8eeff](https://linux-hardware.org/?probe=9839e8eeff) | Aug 26, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [741abbfe3d](https://linux-hardware.org/?probe=741abbfe3d) | Aug 26, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [8ee728569a](https://linux-hardware.org/?probe=8ee728569a) | Aug 25, 2022 |
| Lenovo        | SHARKBAY 0B98405 STD        | Desktop     | [f8f9cd2bfc](https://linux-hardware.org/?probe=f8f9cd2bfc) | Aug 25, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [c1c6b26e42](https://linux-hardware.org/?probe=c1c6b26e42) | Aug 25, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [2a441a673b](https://linux-hardware.org/?probe=2a441a673b) | Aug 25, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [4fb948980f](https://linux-hardware.org/?probe=4fb948980f) | Aug 25, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [dfe17e89f1](https://linux-hardware.org/?probe=dfe17e89f1) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [b74760105e](https://linux-hardware.org/?probe=b74760105e) | Aug 25, 2022 |
| Linx          | LINX1010B                   | Notebook    | [07194b77d4](https://linux-hardware.org/?probe=07194b77d4) | Aug 24, 2022 |
| HP            | 2AFB                        | Desktop     | [ea3ce3f8dd](https://linux-hardware.org/?probe=ea3ce3f8dd) | Aug 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [994866ad01](https://linux-hardware.org/?probe=994866ad01) | Aug 24, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [9da770b898](https://linux-hardware.org/?probe=9da770b898) | Aug 24, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [744f838dc2](https://linux-hardware.org/?probe=744f838dc2) | Aug 24, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [e4f7ce1ec7](https://linux-hardware.org/?probe=e4f7ce1ec7) | Aug 23, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [f2bc1e0fae](https://linux-hardware.org/?probe=f2bc1e0fae) | Aug 23, 2022 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [199e70a85c](https://linux-hardware.org/?probe=199e70a85c) | Aug 23, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [e53f196e21](https://linux-hardware.org/?probe=e53f196e21) | Aug 23, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [2ac415ca87](https://linux-hardware.org/?probe=2ac415ca87) | Aug 23, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [a48fff902b](https://linux-hardware.org/?probe=a48fff902b) | Aug 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [7b0f03259b](https://linux-hardware.org/?probe=7b0f03259b) | Aug 23, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [79bc344d85](https://linux-hardware.org/?probe=79bc344d85) | Aug 23, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [4391428197](https://linux-hardware.org/?probe=4391428197) | Aug 22, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [3d9c208d81](https://linux-hardware.org/?probe=3d9c208d81) | Aug 22, 2022 |
| Dell          | 02P9X9 A00                  | Server      | [b7d9a0c4a2](https://linux-hardware.org/?probe=b7d9a0c4a2) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [d08e00053f](https://linux-hardware.org/?probe=d08e00053f) | Aug 22, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [6b5ced2971](https://linux-hardware.org/?probe=6b5ced2971) | Aug 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [fa5f1121d5](https://linux-hardware.org/?probe=fa5f1121d5) | Aug 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f94ce7d00a](https://linux-hardware.org/?probe=f94ce7d00a) | Aug 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5b8c529dab](https://linux-hardware.org/?probe=5b8c529dab) | Aug 22, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e4dec4681f](https://linux-hardware.org/?probe=e4dec4681f) | Aug 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [68fa656563](https://linux-hardware.org/?probe=68fa656563) | Aug 21, 2022 |
| HP            | 805B                        | Desktop     | [e7fa1a7244](https://linux-hardware.org/?probe=e7fa1a7244) | Aug 21, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [19158f2e35](https://linux-hardware.org/?probe=19158f2e35) | Aug 21, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [01416789ab](https://linux-hardware.org/?probe=01416789ab) | Aug 21, 2022 |
| Samsung       | R519/R719                   | Notebook    | [c0720d7924](https://linux-hardware.org/?probe=c0720d7924) | Aug 21, 2022 |
| Unknown       | X79A                        | Desktop     | [5c545069e2](https://linux-hardware.org/?probe=5c545069e2) | Aug 21, 2022 |
| HP            | ProBook 6570b               | Notebook    | [eba0cd02ec](https://linux-hardware.org/?probe=eba0cd02ec) | Aug 21, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [6ba8616656](https://linux-hardware.org/?probe=6ba8616656) | Aug 20, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [cd1755e81d](https://linux-hardware.org/?probe=cd1755e81d) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [3a7a62f6f8](https://linux-hardware.org/?probe=3a7a62f6f8) | Aug 19, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [2efae45a8f](https://linux-hardware.org/?probe=2efae45a8f) | Aug 19, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b7c760ecee](https://linux-hardware.org/?probe=b7c760ecee) | Aug 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [d6b92d1aa0](https://linux-hardware.org/?probe=d6b92d1aa0) | Aug 19, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [23fb1e2721](https://linux-hardware.org/?probe=23fb1e2721) | Aug 19, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [eb35a0b474](https://linux-hardware.org/?probe=eb35a0b474) | Aug 18, 2022 |
| Dell          | Inspiron 7570               | Notebook    | [7d353117aa](https://linux-hardware.org/?probe=7d353117aa) | Aug 18, 2022 |
| Dell          | Inspiron 7570               | Notebook    | [10609a18a8](https://linux-hardware.org/?probe=10609a18a8) | Aug 18, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [f27c089486](https://linux-hardware.org/?probe=f27c089486) | Aug 18, 2022 |
| ECS           | GF8100VM-M5                 | Desktop     | [0dcfde6fc6](https://linux-hardware.org/?probe=0dcfde6fc6) | Aug 18, 2022 |
| HP            | 8591                        | Desktop     | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [f10fe1f561](https://linux-hardware.org/?probe=f10fe1f561) | Aug 18, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [f8675baa98](https://linux-hardware.org/?probe=f8675baa98) | Aug 18, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [9a1a049600](https://linux-hardware.org/?probe=9a1a049600) | Aug 18, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [e056c24d1d](https://linux-hardware.org/?probe=e056c24d1d) | Aug 18, 2022 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [7b66b20b9f](https://linux-hardware.org/?probe=7b66b20b9f) | Aug 17, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6a95ac6709](https://linux-hardware.org/?probe=6a95ac6709) | Aug 17, 2022 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [e6b2ec9760](https://linux-hardware.org/?probe=e6b2ec9760) | Aug 17, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d971bbde47](https://linux-hardware.org/?probe=d971bbde47) | Aug 17, 2022 |
| HP            | 0B54h D                     | Desktop     | [2d1764e553](https://linux-hardware.org/?probe=2d1764e553) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [c395a0f9db](https://linux-hardware.org/?probe=c395a0f9db) | Aug 16, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [58a439770d](https://linux-hardware.org/?probe=58a439770d) | Aug 15, 2022 |
| GEO           | GeoFlex 340                 | Convertible | [d844757fcc](https://linux-hardware.org/?probe=d844757fcc) | Aug 15, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [c4738a316c](https://linux-hardware.org/?probe=c4738a316c) | Aug 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b490a791c0](https://linux-hardware.org/?probe=b490a791c0) | Aug 15, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [fb8a250b12](https://linux-hardware.org/?probe=fb8a250b12) | Aug 15, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [9a1ff39910](https://linux-hardware.org/?probe=9a1ff39910) | Aug 15, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f9d6b2f915](https://linux-hardware.org/?probe=f9d6b2f915) | Aug 14, 2022 |
| Acer          | Aspire XC-330               | Desktop     | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c2c1f93ff4](https://linux-hardware.org/?probe=c2c1f93ff4) | Aug 14, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [1db8ed0da4](https://linux-hardware.org/?probe=1db8ed0da4) | Aug 14, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [105367d5d6](https://linux-hardware.org/?probe=105367d5d6) | Aug 14, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [dc6838dde5](https://linux-hardware.org/?probe=dc6838dde5) | Aug 14, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [84a0545593](https://linux-hardware.org/?probe=84a0545593) | Aug 14, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ac9e2d3187](https://linux-hardware.org/?probe=ac9e2d3187) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [b3df3a51e0](https://linux-hardware.org/?probe=b3df3a51e0) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2043908eed](https://linux-hardware.org/?probe=2043908eed) | Aug 14, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [0006dc34cf](https://linux-hardware.org/?probe=0006dc34cf) | Aug 14, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [b3df6d2bd8](https://linux-hardware.org/?probe=b3df6d2bd8) | Aug 13, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [a92687ac04](https://linux-hardware.org/?probe=a92687ac04) | Aug 13, 2022 |
| Dell          | 0KP561                      | Desktop     | [38f01be008](https://linux-hardware.org/?probe=38f01be008) | Aug 13, 2022 |
| Dell          | 0KP561                      | Desktop     | [293f6f95bb](https://linux-hardware.org/?probe=293f6f95bb) | Aug 13, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [4e57c20454](https://linux-hardware.org/?probe=4e57c20454) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [5ef85261aa](https://linux-hardware.org/?probe=5ef85261aa) | Aug 13, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [50d9a2d6fe](https://linux-hardware.org/?probe=50d9a2d6fe) | Aug 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [762f08a697](https://linux-hardware.org/?probe=762f08a697) | Aug 13, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [44f3f1991f](https://linux-hardware.org/?probe=44f3f1991f) | Aug 13, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [5c8d31c692](https://linux-hardware.org/?probe=5c8d31c692) | Aug 13, 2022 |
| HP            | ProBook 6570b               | Notebook    | [fb2fa26698](https://linux-hardware.org/?probe=fb2fa26698) | Aug 13, 2022 |
| HP            | 2B3E                        | All in one  | [1ba4759f2c](https://linux-hardware.org/?probe=1ba4759f2c) | Aug 13, 2022 |
| MSI           | Z97M-G43                    | Desktop     | [6e7d79dac7](https://linux-hardware.org/?probe=6e7d79dac7) | Aug 12, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [e1f4ef0670](https://linux-hardware.org/?probe=e1f4ef0670) | Aug 12, 2022 |
| Lenovo        | ThinkPad T480 20L6SBD000    | Notebook    | [b0bbce7c9d](https://linux-hardware.org/?probe=b0bbce7c9d) | Aug 12, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [45491460bc](https://linux-hardware.org/?probe=45491460bc) | Aug 12, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [57c63e8fb9](https://linux-hardware.org/?probe=57c63e8fb9) | Aug 12, 2022 |
| HP            | 304Ah                       | Desktop     | [bc1242ecf9](https://linux-hardware.org/?probe=bc1242ecf9) | Aug 12, 2022 |
| HP            | 304Ah                       | Desktop     | [82db2a1b27](https://linux-hardware.org/?probe=82db2a1b27) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [dbbd0524d8](https://linux-hardware.org/?probe=dbbd0524d8) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [c6e02c54e7](https://linux-hardware.org/?probe=c6e02c54e7) | Aug 11, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [73bf30c596](https://linux-hardware.org/?probe=73bf30c596) | Aug 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a03cc7e650](https://linux-hardware.org/?probe=a03cc7e650) | Aug 11, 2022 |
| Dell          | 02C2CP A01                  | Server      | [7cc1fd61f1](https://linux-hardware.org/?probe=7cc1fd61f1) | Aug 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [b94818059a](https://linux-hardware.org/?probe=b94818059a) | Aug 10, 2022 |
| IP3 Tech      | AB1                         | Mini pc     | [1db65c598c](https://linux-hardware.org/?probe=1db65c598c) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [8090e74c22](https://linux-hardware.org/?probe=8090e74c22) | Aug 10, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [a3aa50c16a](https://linux-hardware.org/?probe=a3aa50c16a) | Aug 10, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0acbdaf806](https://linux-hardware.org/?probe=0acbdaf806) | Aug 10, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [1d0bc04c70](https://linux-hardware.org/?probe=1d0bc04c70) | Aug 10, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [6ca46e8126](https://linux-hardware.org/?probe=6ca46e8126) | Aug 09, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [ad3cfbb4c9](https://linux-hardware.org/?probe=ad3cfbb4c9) | Aug 09, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [1934c32bc7](https://linux-hardware.org/?probe=1934c32bc7) | Aug 09, 2022 |
| HP            | G62                         | Notebook    | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [4574011966](https://linux-hardware.org/?probe=4574011966) | Aug 09, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [8454f0f091](https://linux-hardware.org/?probe=8454f0f091) | Aug 09, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [1b59fcaefb](https://linux-hardware.org/?probe=1b59fcaefb) | Aug 09, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [4c372a442f](https://linux-hardware.org/?probe=4c372a442f) | Aug 09, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [4b08e69fe2](https://linux-hardware.org/?probe=4b08e69fe2) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0e2f35ef5e](https://linux-hardware.org/?probe=0e2f35ef5e) | Aug 08, 2022 |
| Dell          | 0782GW A01                  | Desktop     | [b3ebc3aed3](https://linux-hardware.org/?probe=b3ebc3aed3) | Aug 08, 2022 |
| MSI           | MS-AA1511 20                | All in one  | [71c47135fc](https://linux-hardware.org/?probe=71c47135fc) | Aug 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [404319dfd4](https://linux-hardware.org/?probe=404319dfd4) | Aug 07, 2022 |
| Dell          | Latitude E5470              | Notebook    | [c39ddac6c9](https://linux-hardware.org/?probe=c39ddac6c9) | Aug 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [85dc12b4d1](https://linux-hardware.org/?probe=85dc12b4d1) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8ef9609a7](https://linux-hardware.org/?probe=d8ef9609a7) | Aug 07, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [ef0510a3a8](https://linux-hardware.org/?probe=ef0510a3a8) | Aug 07, 2022 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [d04d31476f](https://linux-hardware.org/?probe=d04d31476f) | Aug 07, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [31c87abaf3](https://linux-hardware.org/?probe=31c87abaf3) | Aug 07, 2022 |
| AMI           | Unknown                     | Notebook    | [d40dbd9414](https://linux-hardware.org/?probe=d40dbd9414) | Aug 07, 2022 |
| Acer          | Swift SF114-31              | Notebook    | [b1cba472dc](https://linux-hardware.org/?probe=b1cba472dc) | Aug 06, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4015089c1e](https://linux-hardware.org/?probe=4015089c1e) | Aug 06, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3e7a65077d](https://linux-hardware.org/?probe=3e7a65077d) | Aug 06, 2022 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [000a2985cc](https://linux-hardware.org/?probe=000a2985cc) | Aug 06, 2022 |
| ASUSTek       | G750JM                      | Notebook    | [0fc5828ad1](https://linux-hardware.org/?probe=0fc5828ad1) | Aug 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [a225baa8a4](https://linux-hardware.org/?probe=a225baa8a4) | Aug 05, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [dd98f4e118](https://linux-hardware.org/?probe=dd98f4e118) | Aug 05, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [9655bf78d0](https://linux-hardware.org/?probe=9655bf78d0) | Aug 05, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [eb168cff15](https://linux-hardware.org/?probe=eb168cff15) | Aug 04, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [bce50a8d8b](https://linux-hardware.org/?probe=bce50a8d8b) | Aug 04, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [66c1af1f67](https://linux-hardware.org/?probe=66c1af1f67) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [cc2c2e7ceb](https://linux-hardware.org/?probe=cc2c2e7ceb) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [e0153e91b7](https://linux-hardware.org/?probe=e0153e91b7) | Aug 04, 2022 |
| Dell          | Latitude E6430              | Notebook    | [388b301ced](https://linux-hardware.org/?probe=388b301ced) | Aug 04, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [7c41cd3006](https://linux-hardware.org/?probe=7c41cd3006) | Aug 04, 2022 |
| Star Labs     | LabTop                      | Notebook    | [a32c7d706c](https://linux-hardware.org/?probe=a32c7d706c) | Aug 03, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7c4355417f](https://linux-hardware.org/?probe=7c4355417f) | Aug 03, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [c29778d816](https://linux-hardware.org/?probe=c29778d816) | Aug 03, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [e93346b04c](https://linux-hardware.org/?probe=e93346b04c) | Aug 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6e77095fb6](https://linux-hardware.org/?probe=6e77095fb6) | Aug 03, 2022 |
| HP            | Notebook                    | Notebook    | [661237e74a](https://linux-hardware.org/?probe=661237e74a) | Aug 03, 2022 |
| MSI           | GE62VR 7RF                  | Notebook    | [e5f6f7e14c](https://linux-hardware.org/?probe=e5f6f7e14c) | Aug 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [8689254ee7](https://linux-hardware.org/?probe=8689254ee7) | Aug 03, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [eb77f8f852](https://linux-hardware.org/?probe=eb77f8f852) | Aug 03, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [86bdcba616](https://linux-hardware.org/?probe=86bdcba616) | Aug 02, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [49d857e7bf](https://linux-hardware.org/?probe=49d857e7bf) | Aug 02, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [4e6ea804e9](https://linux-hardware.org/?probe=4e6ea804e9) | Aug 02, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [e430a435bf](https://linux-hardware.org/?probe=e430a435bf) | Aug 02, 2022 |
| Intel         | DQ57TM AAE92694-401         | Desktop     | [d0b939d1ff](https://linux-hardware.org/?probe=d0b939d1ff) | Aug 02, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [b9f727338f](https://linux-hardware.org/?probe=b9f727338f) | Aug 01, 2022 |
| Dell          | Latitude E7450              | Notebook    | [38051fe609](https://linux-hardware.org/?probe=38051fe609) | Aug 01, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [8a4cc1f177](https://linux-hardware.org/?probe=8a4cc1f177) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [b2b969b0e3](https://linux-hardware.org/?probe=b2b969b0e3) | Aug 01, 2022 |
| Packard Be... | EasyNote TK13BZ             | Notebook    | [530d3ad8db](https://linux-hardware.org/?probe=530d3ad8db) | Aug 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b99b5ef83f](https://linux-hardware.org/?probe=b99b5ef83f) | Aug 01, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [75f131a86a](https://linux-hardware.org/?probe=75f131a86a) | Aug 01, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [33a1712f4d](https://linux-hardware.org/?probe=33a1712f4d) | Aug 01, 2022 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [9612659f60](https://linux-hardware.org/?probe=9612659f60) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | Notebook    | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [105d26b09c](https://linux-hardware.org/?probe=105d26b09c) | Aug 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [3898ce2b5f](https://linux-hardware.org/?probe=3898ce2b5f) | Aug 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS02R0G    | Notebook    | [0aa31e3c39](https://linux-hardware.org/?probe=0aa31e3c39) | Jul 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [6962d36f57](https://linux-hardware.org/?probe=6962d36f57) | Jul 31, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [7aeef461ea](https://linux-hardware.org/?probe=7aeef461ea) | Jul 31, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [b3dc6e72d5](https://linux-hardware.org/?probe=b3dc6e72d5) | Jul 31, 2022 |
| Dell          | Precision M6800             | Notebook    | [3584b1693d](https://linux-hardware.org/?probe=3584b1693d) | Jul 31, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [521b86d8af](https://linux-hardware.org/?probe=521b86d8af) | Jul 31, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [3061a63de7](https://linux-hardware.org/?probe=3061a63de7) | Jul 31, 2022 |
| Dell          | 0F8098                      | Desktop     | [4e6058685a](https://linux-hardware.org/?probe=4e6058685a) | Jul 30, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [ae5b3f7aa5](https://linux-hardware.org/?probe=ae5b3f7aa5) | Jul 30, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [c08016125d](https://linux-hardware.org/?probe=c08016125d) | Jul 30, 2022 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [38d33f0f0e](https://linux-hardware.org/?probe=38d33f0f0e) | Jul 30, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [9258c864d5](https://linux-hardware.org/?probe=9258c864d5) | Jul 29, 2022 |
| PC Special... | NS50MU                      | Notebook    | [b5dd220296](https://linux-hardware.org/?probe=b5dd220296) | Jul 29, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [ebe9fe3b1a](https://linux-hardware.org/?probe=ebe9fe3b1a) | Jul 29, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [f2ced448f2](https://linux-hardware.org/?probe=f2ced448f2) | Jul 29, 2022 |
| Lenovo        | Larne CRB 31900058 WIN 2... | All in one  | [6154705788](https://linux-hardware.org/?probe=6154705788) | Jul 29, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [df5276b855](https://linux-hardware.org/?probe=df5276b855) | Jul 28, 2022 |
| Linx          | LINX1010B                   | Notebook    | [60a5211d09](https://linux-hardware.org/?probe=60a5211d09) | Jul 28, 2022 |
| HP            | ProBook 4515s               | Notebook    | [b9759d3b5d](https://linux-hardware.org/?probe=b9759d3b5d) | Jul 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [297217baa1](https://linux-hardware.org/?probe=297217baa1) | Jul 28, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c2bcea4cf1](https://linux-hardware.org/?probe=c2bcea4cf1) | Jul 28, 2022 |
| MSI           | AM1I                        | Desktop     | [63e6d4040e](https://linux-hardware.org/?probe=63e6d4040e) | Jul 28, 2022 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [d30fc86506](https://linux-hardware.org/?probe=d30fc86506) | Jul 28, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [df54f79195](https://linux-hardware.org/?probe=df54f79195) | Jul 28, 2022 |
| HP            | Presario CQ56               | Notebook    | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4a2fff69f5](https://linux-hardware.org/?probe=4a2fff69f5) | Jul 27, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [90656d8ef4](https://linux-hardware.org/?probe=90656d8ef4) | Jul 27, 2022 |
| Foxconn       | A76ML-K 30                  | Desktop     | [7b118c6a6b](https://linux-hardware.org/?probe=7b118c6a6b) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a33f728c24](https://linux-hardware.org/?probe=a33f728c24) | Jul 27, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [98461afcdb](https://linux-hardware.org/?probe=98461afcdb) | Jul 27, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [703ce95e74](https://linux-hardware.org/?probe=703ce95e74) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [f005e0566d](https://linux-hardware.org/?probe=f005e0566d) | Jul 27, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [44954e91a2](https://linux-hardware.org/?probe=44954e91a2) | Jul 27, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [6eec5d972b](https://linux-hardware.org/?probe=6eec5d972b) | Jul 27, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [f9b0fe48d6](https://linux-hardware.org/?probe=f9b0fe48d6) | Jul 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [b41540a078](https://linux-hardware.org/?probe=b41540a078) | Jul 26, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5263528b46](https://linux-hardware.org/?probe=5263528b46) | Jul 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9f2d322e07](https://linux-hardware.org/?probe=9f2d322e07) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [311984b36d](https://linux-hardware.org/?probe=311984b36d) | Jul 26, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [32045fd953](https://linux-hardware.org/?probe=32045fd953) | Jul 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [6ae47baf6d](https://linux-hardware.org/?probe=6ae47baf6d) | Jul 26, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [007bab123f](https://linux-hardware.org/?probe=007bab123f) | Jul 26, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [b45acaf9b7](https://linux-hardware.org/?probe=b45acaf9b7) | Jul 26, 2022 |
| Medion        | MS-7800                     | Desktop     | [cb2ef643bb](https://linux-hardware.org/?probe=cb2ef643bb) | Jul 26, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [d2f8761a45](https://linux-hardware.org/?probe=d2f8761a45) | Jul 25, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [414aede111](https://linux-hardware.org/?probe=414aede111) | Jul 25, 2022 |
| Gigabyte      | AORUS 17 XE4                | Notebook    | [0bddb42774](https://linux-hardware.org/?probe=0bddb42774) | Jul 25, 2022 |
| HP            | G61                         | Notebook    | [1586fc0cba](https://linux-hardware.org/?probe=1586fc0cba) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bf2cecb453](https://linux-hardware.org/?probe=bf2cecb453) | Jul 25, 2022 |
| ASRock        | A520M-ITX/ac                | Desktop     | [876c779461](https://linux-hardware.org/?probe=876c779461) | Jul 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [fe6b7362b8](https://linux-hardware.org/?probe=fe6b7362b8) | Jul 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b874a0aa8e](https://linux-hardware.org/?probe=b874a0aa8e) | Jul 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [375ba933ba](https://linux-hardware.org/?probe=375ba933ba) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e2a1804b90](https://linux-hardware.org/?probe=e2a1804b90) | Jul 24, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [9796d6eca3](https://linux-hardware.org/?probe=9796d6eca3) | Jul 24, 2022 |
| Medion        | MS-7800                     | Desktop     | [320071c9a0](https://linux-hardware.org/?probe=320071c9a0) | Jul 24, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [567addf380](https://linux-hardware.org/?probe=567addf380) | Jul 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6740b94551](https://linux-hardware.org/?probe=6740b94551) | Jul 24, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [903908877a](https://linux-hardware.org/?probe=903908877a) | Jul 24, 2022 |
| Dell          | Latitude E5570              | Notebook    | [fa3d675cde](https://linux-hardware.org/?probe=fa3d675cde) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| Lenovo        | ThinkPad X280 20KES2SN00    | Notebook    | [202423ba73](https://linux-hardware.org/?probe=202423ba73) | Jul 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [3e7b7cb8cd](https://linux-hardware.org/?probe=3e7b7cb8cd) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e512b2f9f2](https://linux-hardware.org/?probe=e512b2f9f2) | Jul 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [73061b2ed5](https://linux-hardware.org/?probe=73061b2ed5) | Jul 23, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [893377b9f7](https://linux-hardware.org/?probe=893377b9f7) | Jul 23, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [21e10aa056](https://linux-hardware.org/?probe=21e10aa056) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | Notebook    | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Dell          | 0J8H4R A01                  | Desktop     | [3d7d06475c](https://linux-hardware.org/?probe=3d7d06475c) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [f5d81fb635](https://linux-hardware.org/?probe=f5d81fb635) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [83cf5f7085](https://linux-hardware.org/?probe=83cf5f7085) | Jul 23, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [60b77cc6b5](https://linux-hardware.org/?probe=60b77cc6b5) | Jul 22, 2022 |
| AZW           | GT-R                        | Notebook    | [eb7604ea1c](https://linux-hardware.org/?probe=eb7604ea1c) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | Notebook    | [fe5dae3d4a](https://linux-hardware.org/?probe=fe5dae3d4a) | Jul 22, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f383b92a53](https://linux-hardware.org/?probe=f383b92a53) | Jul 22, 2022 |
| Toshiba       | EQUIUM A110                 | Notebook    | [4b6ace9122](https://linux-hardware.org/?probe=4b6ace9122) | Jul 22, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [f1af5f5e45](https://linux-hardware.org/?probe=f1af5f5e45) | Jul 22, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [6c43e1dfd6](https://linux-hardware.org/?probe=6c43e1dfd6) | Jul 22, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b73fab8218](https://linux-hardware.org/?probe=b73fab8218) | Jul 22, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [946035188a](https://linux-hardware.org/?probe=946035188a) | Jul 22, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Spectre Folio Convertibl... | Convertible | [5851c79747](https://linux-hardware.org/?probe=5851c79747) | Jul 21, 2022 |
| HP            | G62                         | Notebook    | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [51ddccaf88](https://linux-hardware.org/?probe=51ddccaf88) | Jul 21, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [07be23439c](https://linux-hardware.org/?probe=07be23439c) | Jul 21, 2022 |
| HP            | 1998                        | Desktop     | [82c8302941](https://linux-hardware.org/?probe=82c8302941) | Jul 21, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [511fd3447b](https://linux-hardware.org/?probe=511fd3447b) | Jul 21, 2022 |
| MSI           | B150M BAZOOKA               | Desktop     | [41053f8c0e](https://linux-hardware.org/?probe=41053f8c0e) | Jul 21, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [f3e470d7cf](https://linux-hardware.org/?probe=f3e470d7cf) | Jul 21, 2022 |
| Panasonic     | CF-53JAWZYDE                | Notebook    | [c1c835cb11](https://linux-hardware.org/?probe=c1c835cb11) | Jul 21, 2022 |
| HP            | Spectre Folio Convertibl... | Convertible | [96897aa5e4](https://linux-hardware.org/?probe=96897aa5e4) | Jul 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [34942a8abc](https://linux-hardware.org/?probe=34942a8abc) | Jul 20, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b0cdba7434](https://linux-hardware.org/?probe=b0cdba7434) | Jul 20, 2022 |
| HP            | G62                         | Notebook    | [3c4aab40ae](https://linux-hardware.org/?probe=3c4aab40ae) | Jul 20, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [5889a04334](https://linux-hardware.org/?probe=5889a04334) | Jul 20, 2022 |
| Dell          | Latitude 5285               | Notebook    | [2b46125d79](https://linux-hardware.org/?probe=2b46125d79) | Jul 20, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [45be1164f5](https://linux-hardware.org/?probe=45be1164f5) | Jul 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [55fdb6713c](https://linux-hardware.org/?probe=55fdb6713c) | Jul 19, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [4696230d64](https://linux-hardware.org/?probe=4696230d64) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | Notebook    | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [8f3842495f](https://linux-hardware.org/?probe=8f3842495f) | Jul 18, 2022 |
| Acer          | Predator PO3-620            | Desktop     | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| Dell          | Vostro 3559                 | Notebook    | [3770ab3d4c](https://linux-hardware.org/?probe=3770ab3d4c) | Jul 18, 2022 |
| Dell          | Latitude D430               | Notebook    | [22c020a070](https://linux-hardware.org/?probe=22c020a070) | Jul 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [dac8603f3d](https://linux-hardware.org/?probe=dac8603f3d) | Jul 17, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [b864280c98](https://linux-hardware.org/?probe=b864280c98) | Jul 17, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [9a4907d88c](https://linux-hardware.org/?probe=9a4907d88c) | Jul 17, 2022 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [5096e0dfea](https://linux-hardware.org/?probe=5096e0dfea) | Jul 17, 2022 |
| Lenovo        | ThinkPad W550s 20E2000PU... | Notebook    | [ee30c1c248](https://linux-hardware.org/?probe=ee30c1c248) | Jul 16, 2022 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [4142cbc3d4](https://linux-hardware.org/?probe=4142cbc3d4) | Jul 16, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [68f6109054](https://linux-hardware.org/?probe=68f6109054) | Jul 16, 2022 |
| Dell          | Latitude E6440              | Notebook    | [eabdcd7622](https://linux-hardware.org/?probe=eabdcd7622) | Jul 15, 2022 |
| HP            | 88BF                        | Desktop     | [92b12df551](https://linux-hardware.org/?probe=92b12df551) | Jul 15, 2022 |
| HP            | ProBook 4545s               | Notebook    | [12575a32d1](https://linux-hardware.org/?probe=12575a32d1) | Jul 15, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [7efe67fd9a](https://linux-hardware.org/?probe=7efe67fd9a) | Jul 15, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [7177bb644a](https://linux-hardware.org/?probe=7177bb644a) | Jul 15, 2022 |
| BESSTAR Te... | TL50                        | Desktop     | [c77ff65710](https://linux-hardware.org/?probe=c77ff65710) | Jul 15, 2022 |
| Fusion5       | S14+                        | Notebook    | [64668fa44f](https://linux-hardware.org/?probe=64668fa44f) | Jul 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [ea2c3cd9e9](https://linux-hardware.org/?probe=ea2c3cd9e9) | Jul 14, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [fecf83d1eb](https://linux-hardware.org/?probe=fecf83d1eb) | Jul 14, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [0893dc4cc3](https://linux-hardware.org/?probe=0893dc4cc3) | Jul 14, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [cae0f57919](https://linux-hardware.org/?probe=cae0f57919) | Jul 14, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [63c4a7a0bd](https://linux-hardware.org/?probe=63c4a7a0bd) | Jul 14, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [4de6deb720](https://linux-hardware.org/?probe=4de6deb720) | Jul 14, 2022 |
| Dell          | Inspiron 7570               | Notebook    | [872ca81b40](https://linux-hardware.org/?probe=872ca81b40) | Jul 13, 2022 |
| MSI           | B365M PRO-VDH               | Desktop     | [7ff6dc5131](https://linux-hardware.org/?probe=7ff6dc5131) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ac37352e9b](https://linux-hardware.org/?probe=ac37352e9b) | Jul 13, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [78bb4d2a41](https://linux-hardware.org/?probe=78bb4d2a41) | Jul 13, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [37b04a8093](https://linux-hardware.org/?probe=37b04a8093) | Jul 12, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [575388d90b](https://linux-hardware.org/?probe=575388d90b) | Jul 12, 2022 |
| HP            | 3398                        | Desktop     | [1b964004d9](https://linux-hardware.org/?probe=1b964004d9) | Jul 12, 2022 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [80e47e8ff5](https://linux-hardware.org/?probe=80e47e8ff5) | Jul 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [80bb428b2a](https://linux-hardware.org/?probe=80bb428b2a) | Jul 12, 2022 |
| ASUSTek       | V-P8H61E                    | Desktop     | [f8e5b72d1c](https://linux-hardware.org/?probe=f8e5b72d1c) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [6b4cd20919](https://linux-hardware.org/?probe=6b4cd20919) | Jul 12, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [42b248f049](https://linux-hardware.org/?probe=42b248f049) | Jul 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0967e17760](https://linux-hardware.org/?probe=0967e17760) | Jul 11, 2022 |
| ASRock        | P43DE                       | Desktop     | [0dbb7293a1](https://linux-hardware.org/?probe=0dbb7293a1) | Jul 11, 2022 |
| Google        | Lindar                      | Notebook    | [2e12af7cf7](https://linux-hardware.org/?probe=2e12af7cf7) | Jul 11, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [44a7d0bb16](https://linux-hardware.org/?probe=44a7d0bb16) | Jul 11, 2022 |
| Medion        | Erazer P6661 MD60303        | Notebook    | [35fbb2c055](https://linux-hardware.org/?probe=35fbb2c055) | Jul 10, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [978d27ca8b](https://linux-hardware.org/?probe=978d27ca8b) | Jul 10, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [3209c50980](https://linux-hardware.org/?probe=3209c50980) | Jul 10, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [36252f70d6](https://linux-hardware.org/?probe=36252f70d6) | Jul 10, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [e3197762a9](https://linux-hardware.org/?probe=e3197762a9) | Jul 10, 2022 |
| Dell          | Inspiron 16 7610            | Notebook    | [25dce193df](https://linux-hardware.org/?probe=25dce193df) | Jul 10, 2022 |
| ASRock        | P43DE                       | Desktop     | [2aa8290d56](https://linux-hardware.org/?probe=2aa8290d56) | Jul 10, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [289b6912d0](https://linux-hardware.org/?probe=289b6912d0) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [a03b01d3b5](https://linux-hardware.org/?probe=a03b01d3b5) | Jul 10, 2022 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [de75a91d9f](https://linux-hardware.org/?probe=de75a91d9f) | Jul 09, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [89403f1acb](https://linux-hardware.org/?probe=89403f1acb) | Jul 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [0c2ea27c49](https://linux-hardware.org/?probe=0c2ea27c49) | Jul 09, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [a374367376](https://linux-hardware.org/?probe=a374367376) | Jul 09, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [4f7f102599](https://linux-hardware.org/?probe=4f7f102599) | Jul 08, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [36851c847b](https://linux-hardware.org/?probe=36851c847b) | Jul 08, 2022 |
| ASUSTek       | Z11PG-D24 Series            | Server      | [c874a6d28c](https://linux-hardware.org/?probe=c874a6d28c) | Jul 08, 2022 |
| ASUSTek       | Z11PG-D24 Series            | Server      | [a47b2ecee8](https://linux-hardware.org/?probe=a47b2ecee8) | Jul 08, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [32d1c38bf4](https://linux-hardware.org/?probe=32d1c38bf4) | Jul 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3458084b51](https://linux-hardware.org/?probe=3458084b51) | Jul 08, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d96e1a1528](https://linux-hardware.org/?probe=d96e1a1528) | Jul 08, 2022 |
| HP            | G56                         | Notebook    | [5c38722298](https://linux-hardware.org/?probe=5c38722298) | Jul 07, 2022 |
| Dell          | 0DR845                      | Desktop     | [424649e737](https://linux-hardware.org/?probe=424649e737) | Jul 07, 2022 |
| AZW           | SEi                         | Notebook    | [7556cabcae](https://linux-hardware.org/?probe=7556cabcae) | Jul 07, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [0fecc82851](https://linux-hardware.org/?probe=0fecc82851) | Jul 06, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [744b6063f7](https://linux-hardware.org/?probe=744b6063f7) | Jul 06, 2022 |
| Sony          | VGN-FS415B                  | Notebook    | [0387163846](https://linux-hardware.org/?probe=0387163846) | Jul 06, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [aecc3e1863](https://linux-hardware.org/?probe=aecc3e1863) | Jul 06, 2022 |
| Tactus        | GeoPad 220                  | Tablet      | [e8980ffba5](https://linux-hardware.org/?probe=e8980ffba5) | Jul 06, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [ac1652fd54](https://linux-hardware.org/?probe=ac1652fd54) | Jul 06, 2022 |
| MSI           | Raider GE66 12UH            | Notebook    | [59726526b6](https://linux-hardware.org/?probe=59726526b6) | Jul 06, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [968f07d190](https://linux-hardware.org/?probe=968f07d190) | Jul 05, 2022 |
| ASUSTek       | PN50-E1                     | Mini pc     | [984770369e](https://linux-hardware.org/?probe=984770369e) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [850003c6da](https://linux-hardware.org/?probe=850003c6da) | Jul 05, 2022 |
| Medion        | Erazer P6661 MD60303        | Notebook    | [59417db2d7](https://linux-hardware.org/?probe=59417db2d7) | Jul 05, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [61eaf99aca](https://linux-hardware.org/?probe=61eaf99aca) | Jul 05, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [812733dd89](https://linux-hardware.org/?probe=812733dd89) | Jul 05, 2022 |
| Dell          | 054KM3 A01                  | Desktop     | [407b210bfe](https://linux-hardware.org/?probe=407b210bfe) | Jul 05, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c5155b28a7](https://linux-hardware.org/?probe=c5155b28a7) | Jul 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [685e3d36bc](https://linux-hardware.org/?probe=685e3d36bc) | Jul 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b436712f17](https://linux-hardware.org/?probe=b436712f17) | Jul 04, 2022 |
| Tactus        | GeoPad 220                  | Tablet      | [8af54104e5](https://linux-hardware.org/?probe=8af54104e5) | Jul 04, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [072608d8d8](https://linux-hardware.org/?probe=072608d8d8) | Jul 04, 2022 |
| LG Electro... | 17Z90N-V.AA55A1             | Notebook    | [272164819f](https://linux-hardware.org/?probe=272164819f) | Jul 04, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [61de4b6c7b](https://linux-hardware.org/?probe=61de4b6c7b) | Jul 04, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c76805b11f](https://linux-hardware.org/?probe=c76805b11f) | Jul 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7f4faab065](https://linux-hardware.org/?probe=7f4faab065) | Jul 04, 2022 |
| Linx          | LINX1010B                   | Notebook    | [ae94ac08d9](https://linux-hardware.org/?probe=ae94ac08d9) | Jul 03, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [a6fb0fd95c](https://linux-hardware.org/?probe=a6fb0fd95c) | Jul 03, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [c3e4fb87d2](https://linux-hardware.org/?probe=c3e4fb87d2) | Jul 03, 2022 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [654459e245](https://linux-hardware.org/?probe=654459e245) | Jul 03, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [e2ff106ce0](https://linux-hardware.org/?probe=e2ff106ce0) | Jul 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [24d32e73bd](https://linux-hardware.org/?probe=24d32e73bd) | Jul 03, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [18acc5233d](https://linux-hardware.org/?probe=18acc5233d) | Jul 03, 2022 |
| HP            | 8350                        | Desktop     | [39a8a75ebe](https://linux-hardware.org/?probe=39a8a75ebe) | Jul 03, 2022 |
| Acer          | Aspire TC-1660 V:1.1        | Desktop     | [4b65cbc6e6](https://linux-hardware.org/?probe=4b65cbc6e6) | Jul 03, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [92c11e77c4](https://linux-hardware.org/?probe=92c11e77c4) | Jul 03, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [00370cb2ff](https://linux-hardware.org/?probe=00370cb2ff) | Jul 03, 2022 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | Notebook    | [d90a910042](https://linux-hardware.org/?probe=d90a910042) | Jul 02, 2022 |
| AWOW          | AL34                        | Notebook    | [be240349b7](https://linux-hardware.org/?probe=be240349b7) | Jul 02, 2022 |
| Dell          | Latitude E6400              | Notebook    | [d7b28806a9](https://linux-hardware.org/?probe=d7b28806a9) | Jul 02, 2022 |
| Tactus        | GeoPad 220                  | Tablet      | [0be548592c](https://linux-hardware.org/?probe=0be548592c) | Jul 01, 2022 |
| Tactus        | GeoPad 220                  | Tablet      | [f0421c3e3f](https://linux-hardware.org/?probe=f0421c3e3f) | Jul 01, 2022 |
| Samsung       | Q210/P210                   | Notebook    | [dfc97062be](https://linux-hardware.org/?probe=dfc97062be) | Jul 01, 2022 |
| Acer          | Extensa 5220                | Notebook    | [1ee1e31b52](https://linux-hardware.org/?probe=1ee1e31b52) | Jul 01, 2022 |
| Tactus        | GeoPad 220                  | Tablet      | [a7e3223fa6](https://linux-hardware.org/?probe=a7e3223fa6) | Jul 01, 2022 |
| Acer          | Aspire C22-820              | All in one  | [0bb41ffb71](https://linux-hardware.org/?probe=0bb41ffb71) | Jul 01, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [0bbac8ce1f](https://linux-hardware.org/?probe=0bbac8ce1f) | Jul 01, 2022 |
| HP            | Presario CQ56               | Notebook    | [af108b4933](https://linux-hardware.org/?probe=af108b4933) | Jun 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7e14880c80](https://linux-hardware.org/?probe=7e14880c80) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [142c1c4ef2](https://linux-hardware.org/?probe=142c1c4ef2) | Jun 30, 2022 |
| HP            | 0B54h D                     | Desktop     | [bef89f554e](https://linux-hardware.org/?probe=bef89f554e) | Jun 30, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [7049f819f0](https://linux-hardware.org/?probe=7049f819f0) | Jun 30, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a90f7795b](https://linux-hardware.org/?probe=7a90f7795b) | Jun 30, 2022 |
| Acer          | Aspire 5735                 | Notebook    | [b930fd3fcd](https://linux-hardware.org/?probe=b930fd3fcd) | Jun 29, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [608388f911](https://linux-hardware.org/?probe=608388f911) | Jun 29, 2022 |
| Dell          | Latitude 7389               | Convertible | [6cc0f640ed](https://linux-hardware.org/?probe=6cc0f640ed) | Jun 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1eed1dcced](https://linux-hardware.org/?probe=1eed1dcced) | Jun 29, 2022 |
| Toshiba       | Satellite C850-1NU          | Notebook    | [2b83cb161e](https://linux-hardware.org/?probe=2b83cb161e) | Jun 29, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [828f0b9ef1](https://linux-hardware.org/?probe=828f0b9ef1) | Jun 29, 2022 |
| Dell          | 0XCR8D A02                  | Desktop     | [4573e16702](https://linux-hardware.org/?probe=4573e16702) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [e8d5e4ff14](https://linux-hardware.org/?probe=e8d5e4ff14) | Jun 29, 2022 |
| Lenovo        | ThinkPad E590 20NB001AUK    | Notebook    | [f52aacfbfe](https://linux-hardware.org/?probe=f52aacfbfe) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| Toshiba       | Satellite L750              | Notebook    | [e01155e6ba](https://linux-hardware.org/?probe=e01155e6ba) | Jun 28, 2022 |
| Acer          | Aspire Z3-615               | All in one  | [cccd2abbc8](https://linux-hardware.org/?probe=cccd2abbc8) | Jun 28, 2022 |
| Acer          | Aspire Z3-615               | All in one  | [34700612aa](https://linux-hardware.org/?probe=34700612aa) | Jun 28, 2022 |
| ASRock        | P43DE                       | Desktop     | [f52d106d92](https://linux-hardware.org/?probe=f52d106d92) | Jun 28, 2022 |
| Samsung       | 930QDB                      | Convertible | [e022aed2bc](https://linux-hardware.org/?probe=e022aed2bc) | Jun 28, 2022 |
| HP            | Pavilion TS 14              | Notebook    | [f851b6a57b](https://linux-hardware.org/?probe=f851b6a57b) | Jun 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [6e098b9c49](https://linux-hardware.org/?probe=6e098b9c49) | Jun 27, 2022 |
| HP            | Pavilion 15                 | Notebook    | [9e7a0c1889](https://linux-hardware.org/?probe=9e7a0c1889) | Jun 27, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [287a6346a7](https://linux-hardware.org/?probe=287a6346a7) | Jun 27, 2022 |
| Toshiba       | Satellite C870-1H2          | Notebook    | [edc5098a6f](https://linux-hardware.org/?probe=edc5098a6f) | Jun 27, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [47b4db95ed](https://linux-hardware.org/?probe=47b4db95ed) | Jun 26, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [74401fdf8b](https://linux-hardware.org/?probe=74401fdf8b) | Jun 26, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [dde9afd7cb](https://linux-hardware.org/?probe=dde9afd7cb) | Jun 26, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [f0e913f715](https://linux-hardware.org/?probe=f0e913f715) | Jun 26, 2022 |
| HP            | 1496                        | Desktop     | [97616aecd6](https://linux-hardware.org/?probe=97616aecd6) | Jun 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [f37581d70e](https://linux-hardware.org/?probe=f37581d70e) | Jun 26, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [6c9ee0dadd](https://linux-hardware.org/?probe=6c9ee0dadd) | Jun 26, 2022 |
| Acer          | Aspire A515-55G             | Notebook    | [d05c52e40b](https://linux-hardware.org/?probe=d05c52e40b) | Jun 26, 2022 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [b4ebe70967](https://linux-hardware.org/?probe=b4ebe70967) | Jun 26, 2022 |
| HP            | 1496                        | Desktop     | [3ab73cb742](https://linux-hardware.org/?probe=3ab73cb742) | Jun 26, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [fa3d29c80b](https://linux-hardware.org/?probe=fa3d29c80b) | Jun 25, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [e568c96372](https://linux-hardware.org/?probe=e568c96372) | Jun 25, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [357e062693](https://linux-hardware.org/?probe=357e062693) | Jun 25, 2022 |
| ASRock        | P43DE                       | Desktop     | [80f90e4fcd](https://linux-hardware.org/?probe=80f90e4fcd) | Jun 24, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| Sony          | VGN-FS415B                  | Notebook    | [00d146d9f4](https://linux-hardware.org/?probe=00d146d9f4) | Jun 24, 2022 |
| HP            | 8265                        | Desktop     | [3de1cae37a](https://linux-hardware.org/?probe=3de1cae37a) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| Nvidia        | Tegra                       | Soc         | [cfeb6fb78f](https://linux-hardware.org/?probe=cfeb6fb78f) | Jun 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [d08060fb50](https://linux-hardware.org/?probe=d08060fb50) | Jun 23, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [d87c55111a](https://linux-hardware.org/?probe=d87c55111a) | Jun 23, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [1091cc416e](https://linux-hardware.org/?probe=1091cc416e) | Jun 23, 2022 |
| Medion        | Erazer P6661 MD60303        | Notebook    | [a678044765](https://linux-hardware.org/?probe=a678044765) | Jun 23, 2022 |
| Medion        | Erazer P6661 MD60303        | Notebook    | [babd561a16](https://linux-hardware.org/?probe=babd561a16) | Jun 23, 2022 |
| ABIT          | IP35 Pro                    | Desktop     | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| HP            | 3397                        | Desktop     | [3c7afd0ee2](https://linux-hardware.org/?probe=3c7afd0ee2) | Jun 23, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [4b44fc669a](https://linux-hardware.org/?probe=4b44fc669a) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [f2b61e1e02](https://linux-hardware.org/?probe=f2b61e1e02) | Jun 23, 2022 |
| Dell          | 0C1GJ7 A00                  | All in one  | [c812a957cf](https://linux-hardware.org/?probe=c812a957cf) | Jun 23, 2022 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | Notebook    | [13a427bd3b](https://linux-hardware.org/?probe=13a427bd3b) | Jun 23, 2022 |
| Razer         | Blade                       | Notebook    | [6c8b201cd9](https://linux-hardware.org/?probe=6c8b201cd9) | Jun 23, 2022 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [257f40005f](https://linux-hardware.org/?probe=257f40005f) | Jun 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [213fbe4dd2](https://linux-hardware.org/?probe=213fbe4dd2) | Jun 22, 2022 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [98350f1274](https://linux-hardware.org/?probe=98350f1274) | Jun 22, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [7a571de1b9](https://linux-hardware.org/?probe=7a571de1b9) | Jun 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [6024015ecc](https://linux-hardware.org/?probe=6024015ecc) | Jun 21, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [1f3b17165b](https://linux-hardware.org/?probe=1f3b17165b) | Jun 21, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [1cd927a911](https://linux-hardware.org/?probe=1cd927a911) | Jun 21, 2022 |
| Samsung       | Galaxy Book 12              | Tablet      | [01839134d7](https://linux-hardware.org/?probe=01839134d7) | Jun 21, 2022 |
| HP            | 2B4B                        | Desktop     | [0e699c16a4](https://linux-hardware.org/?probe=0e699c16a4) | Jun 21, 2022 |
| HP            | 2B4B                        | Desktop     | [d179d2050d](https://linux-hardware.org/?probe=d179d2050d) | Jun 21, 2022 |
| Unknown       | A06                         | Server      | [aca491bb91](https://linux-hardware.org/?probe=aca491bb91) | Jun 21, 2022 |
| Dell          | 0XCR8D A02                  | Desktop     | [9423c99e6c](https://linux-hardware.org/?probe=9423c99e6c) | Jun 21, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [6ddca91c97](https://linux-hardware.org/?probe=6ddca91c97) | Jun 21, 2022 |
| Biostar       | N68S3+                      | Desktop     | [efe83d16ac](https://linux-hardware.org/?probe=efe83d16ac) | Jun 21, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [f3176204c8](https://linux-hardware.org/?probe=f3176204c8) | Jun 21, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [b0d232a3c9](https://linux-hardware.org/?probe=b0d232a3c9) | Jun 20, 2022 |
| Sony          | VGN-UX27GN                  | Notebook    | [ed20bd45a4](https://linux-hardware.org/?probe=ed20bd45a4) | Jun 20, 2022 |
| IBM           | ThinkPad X40 2371LBG        | Notebook    | [e7610b86d4](https://linux-hardware.org/?probe=e7610b86d4) | Jun 20, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [f8a734d114](https://linux-hardware.org/?probe=f8a734d114) | Jun 20, 2022 |
| Lenovo        | ThinkPad T430 2349I46       | Notebook    | [3a7df4ea17](https://linux-hardware.org/?probe=3a7df4ea17) | Jun 20, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [0cae0765c9](https://linux-hardware.org/?probe=0cae0765c9) | Jun 20, 2022 |
| HP            | 15                          | Notebook    | [61e6eddc93](https://linux-hardware.org/?probe=61e6eddc93) | Jun 20, 2022 |
| AVITA         | NS14A6                      | Notebook    | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [604913c4e4](https://linux-hardware.org/?probe=604913c4e4) | Jun 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eeadb7465a](https://linux-hardware.org/?probe=eeadb7465a) | Jun 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d5af99ece6](https://linux-hardware.org/?probe=d5af99ece6) | Jun 20, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [8cecec73c6](https://linux-hardware.org/?probe=8cecec73c6) | Jun 19, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [714a296099](https://linux-hardware.org/?probe=714a296099) | Jun 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [560fa88cad](https://linux-hardware.org/?probe=560fa88cad) | Jun 19, 2022 |
| AWOW          | NY41                        | Mini pc     | [f420b36754](https://linux-hardware.org/?probe=f420b36754) | Jun 19, 2022 |
| AWOW          | NY41                        | Mini pc     | [e8f74093f9](https://linux-hardware.org/?probe=e8f74093f9) | Jun 19, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [8cc15a5651](https://linux-hardware.org/?probe=8cc15a5651) | Jun 19, 2022 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [d04b14aef0](https://linux-hardware.org/?probe=d04b14aef0) | Jun 19, 2022 |
| HP            | 843B                        | Desktop     | [21619041e8](https://linux-hardware.org/?probe=21619041e8) | Jun 19, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [ff71b93299](https://linux-hardware.org/?probe=ff71b93299) | Jun 19, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [d7e8fa7984](https://linux-hardware.org/?probe=d7e8fa7984) | Jun 19, 2022 |
| Lenovo        | ThinkPad T470 20HD000EUK    | Notebook    | [6cc2ca4099](https://linux-hardware.org/?probe=6cc2ca4099) | Jun 19, 2022 |
| HP            | 1494                        | Desktop     | [2dc41c0b99](https://linux-hardware.org/?probe=2dc41c0b99) | Jun 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bbe948274e](https://linux-hardware.org/?probe=bbe948274e) | Jun 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c61fdedfff](https://linux-hardware.org/?probe=c61fdedfff) | Jun 18, 2022 |
| Dell          | Inspiron 7370               | Notebook    | [e8a53b7f1b](https://linux-hardware.org/?probe=e8a53b7f1b) | Jun 18, 2022 |
| Unknown       | A06                         | Server      | [3bf8edf992](https://linux-hardware.org/?probe=3bf8edf992) | Jun 18, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [f399990b6e](https://linux-hardware.org/?probe=f399990b6e) | Jun 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [8121d73bc9](https://linux-hardware.org/?probe=8121d73bc9) | Jun 18, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [41945e4369](https://linux-hardware.org/?probe=41945e4369) | Jun 18, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3b177fe0af](https://linux-hardware.org/?probe=3b177fe0af) | Jun 17, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [8fb623d313](https://linux-hardware.org/?probe=8fb623d313) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [f4178c276d](https://linux-hardware.org/?probe=f4178c276d) | Jun 16, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [d6be55432d](https://linux-hardware.org/?probe=d6be55432d) | Jun 16, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [cee122d15f](https://linux-hardware.org/?probe=cee122d15f) | Jun 16, 2022 |
| Sony          | VGN-P11Z_Q                  | Notebook    | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [198f6e8fca](https://linux-hardware.org/?probe=198f6e8fca) | Jun 16, 2022 |
| AZW           | Gemini T34                  | Desktop     | [553b174ce2](https://linux-hardware.org/?probe=553b174ce2) | Jun 16, 2022 |
| HP            | 3031h                       | Desktop     | [00080c0264](https://linux-hardware.org/?probe=00080c0264) | Jun 16, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [42fd0dcad9](https://linux-hardware.org/?probe=42fd0dcad9) | Jun 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [e8f85ab771](https://linux-hardware.org/?probe=e8f85ab771) | Jun 16, 2022 |
| HP            | ProBook 455 G3              | Notebook    | [507dcf06fc](https://linux-hardware.org/?probe=507dcf06fc) | Jun 16, 2022 |
| HP            | ProBook 455 G3              | Notebook    | [64794fafd4](https://linux-hardware.org/?probe=64794fafd4) | Jun 16, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [994f64f470](https://linux-hardware.org/?probe=994f64f470) | Jun 15, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d5cefb3aa6](https://linux-hardware.org/?probe=d5cefb3aa6) | Jun 15, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [5afd9dcda0](https://linux-hardware.org/?probe=5afd9dcda0) | Jun 15, 2022 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [e00b8334dd](https://linux-hardware.org/?probe=e00b8334dd) | Jun 15, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [8e0da08d4d](https://linux-hardware.org/?probe=8e0da08d4d) | Jun 15, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [cf4df37657](https://linux-hardware.org/?probe=cf4df37657) | Jun 15, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [b6cdb73504](https://linux-hardware.org/?probe=b6cdb73504) | Jun 15, 2022 |
| Dell          | 0XCR8D A02                  | Desktop     | [134e7208cc](https://linux-hardware.org/?probe=134e7208cc) | Jun 15, 2022 |
| Lenovo        | ThinkPad T430 2349AZ6       | Notebook    | [7369a5bd6b](https://linux-hardware.org/?probe=7369a5bd6b) | Jun 15, 2022 |
| MSI           | GP60 2OD                    | Notebook    | [6edff2c2ad](https://linux-hardware.org/?probe=6edff2c2ad) | Jun 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [131a938c5e](https://linux-hardware.org/?probe=131a938c5e) | Jun 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [5b6f3d52c5](https://linux-hardware.org/?probe=5b6f3d52c5) | Jun 14, 2022 |
| Samsung       | 935QDB                      | Convertible | [a140a593c5](https://linux-hardware.org/?probe=a140a593c5) | Jun 14, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [15cb74d079](https://linux-hardware.org/?probe=15cb74d079) | Jun 13, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [c1be5f13af](https://linux-hardware.org/?probe=c1be5f13af) | Jun 13, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [d40967b111](https://linux-hardware.org/?probe=d40967b111) | Jun 13, 2022 |
| Dell          | Studio XPS 1640             | Notebook    | [aac66b6b7b](https://linux-hardware.org/?probe=aac66b6b7b) | Jun 13, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [45ca271974](https://linux-hardware.org/?probe=45ca271974) | Jun 13, 2022 |
| Dell          | 09D2HH A00                  | Desktop     | [fde3cee794](https://linux-hardware.org/?probe=fde3cee794) | Jun 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e69ce900b7](https://linux-hardware.org/?probe=e69ce900b7) | Jun 13, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [6eef40304f](https://linux-hardware.org/?probe=6eef40304f) | Jun 13, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [72ea50523c](https://linux-hardware.org/?probe=72ea50523c) | Jun 13, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [05b64cc5de](https://linux-hardware.org/?probe=05b64cc5de) | Jun 12, 2022 |
| HP            | 18E5                        | Desktop     | [275b8ca77c](https://linux-hardware.org/?probe=275b8ca77c) | Jun 12, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [c1e6618ac5](https://linux-hardware.org/?probe=c1e6618ac5) | Jun 12, 2022 |
| MSI           | P65 Creator 9SE             | Notebook    | [da30629803](https://linux-hardware.org/?probe=da30629803) | Jun 11, 2022 |
| Dell          | Inspiron 16 7610            | Notebook    | [9967260c3c](https://linux-hardware.org/?probe=9967260c3c) | Jun 11, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [0a0828f262](https://linux-hardware.org/?probe=0a0828f262) | Jun 11, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [83f46a355b](https://linux-hardware.org/?probe=83f46a355b) | Jun 11, 2022 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [64cf410189](https://linux-hardware.org/?probe=64cf410189) | Jun 10, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8e47a3c188](https://linux-hardware.org/?probe=8e47a3c188) | Jun 10, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [53c2e38d14](https://linux-hardware.org/?probe=53c2e38d14) | Jun 10, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [ce4d95c7bf](https://linux-hardware.org/?probe=ce4d95c7bf) | Jun 10, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [ec0c59238f](https://linux-hardware.org/?probe=ec0c59238f) | Jun 10, 2022 |
| Dell          | Latitude E7270              | Notebook    | [8d8f0db52c](https://linux-hardware.org/?probe=8d8f0db52c) | Jun 10, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [31275cdf72](https://linux-hardware.org/?probe=31275cdf72) | Jun 10, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [9e574bef7c](https://linux-hardware.org/?probe=9e574bef7c) | Jun 10, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b8e097f983](https://linux-hardware.org/?probe=b8e097f983) | Jun 10, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [843d2132ad](https://linux-hardware.org/?probe=843d2132ad) | Jun 09, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d29d3120fb](https://linux-hardware.org/?probe=d29d3120fb) | Jun 09, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [7cdc9be674](https://linux-hardware.org/?probe=7cdc9be674) | Jun 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6d195af721](https://linux-hardware.org/?probe=6d195af721) | Jun 09, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| AZW           | Gemini J45                  | Desktop     | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| Acer          | Aspire C24-865              | All in one  | [232cfe0afa](https://linux-hardware.org/?probe=232cfe0afa) | Jun 08, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | Notebook    | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | Desktop     | [36d73de92c](https://linux-hardware.org/?probe=36d73de92c) | Jun 08, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [b56845a5b8](https://linux-hardware.org/?probe=b56845a5b8) | Jun 08, 2022 |
| Lenovo        | S130-11IGM 81J1             | Notebook    | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude E6510              | Notebook    | [083f1d576d](https://linux-hardware.org/?probe=083f1d576d) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [737a4183c8](https://linux-hardware.org/?probe=737a4183c8) | Jun 07, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [13c7b714dc](https://linux-hardware.org/?probe=13c7b714dc) | Jun 07, 2022 |
| Dell          | 0C1GJ7 A00                  | All in one  | [d67bb7d7c0](https://linux-hardware.org/?probe=d67bb7d7c0) | Jun 07, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [d6662c5acf](https://linux-hardware.org/?probe=d6662c5acf) | Jun 07, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [902546cb45](https://linux-hardware.org/?probe=902546cb45) | Jun 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0b042e37b3](https://linux-hardware.org/?probe=0b042e37b3) | Jun 06, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [f5ded88514](https://linux-hardware.org/?probe=f5ded88514) | Jun 06, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [e993e32a56](https://linux-hardware.org/?probe=e993e32a56) | Jun 06, 2022 |
| Lenovo        | ThinkPad T480 20L5000AUK    | Notebook    | [0bf67e4018](https://linux-hardware.org/?probe=0bf67e4018) | Jun 06, 2022 |
| Dell          | Latitude E6400              | Notebook    | [e4f54892c2](https://linux-hardware.org/?probe=e4f54892c2) | Jun 05, 2022 |
| Acer          | Aspire C22-820              | All in one  | [32cb850c67](https://linux-hardware.org/?probe=32cb850c67) | Jun 05, 2022 |
| HP            | 8350                        | Desktop     | [63a9e40af6](https://linux-hardware.org/?probe=63a9e40af6) | Jun 05, 2022 |
| HYPA          | FLUX                        | Notebook    | [76b0337ef8](https://linux-hardware.org/?probe=76b0337ef8) | Jun 05, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [e579d912d0](https://linux-hardware.org/?probe=e579d912d0) | Jun 04, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [39c37e56ec](https://linux-hardware.org/?probe=39c37e56ec) | Jun 04, 2022 |
| HP            | G62                         | Notebook    | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| Acer          | Aspire C22-820              | All in one  | [682fb84b70](https://linux-hardware.org/?probe=682fb84b70) | Jun 04, 2022 |
| Acer          | Aspire C24-865              | All in one  | [62cdbbbf11](https://linux-hardware.org/?probe=62cdbbbf11) | Jun 04, 2022 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [13a3f2e1cd](https://linux-hardware.org/?probe=13a3f2e1cd) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [d147abfc52](https://linux-hardware.org/?probe=d147abfc52) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [eaad038fde](https://linux-hardware.org/?probe=eaad038fde) | Jun 03, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [df0357703d](https://linux-hardware.org/?probe=df0357703d) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9829bd8f60](https://linux-hardware.org/?probe=9829bd8f60) | Jun 03, 2022 |
| Lenovo        | G780 2182                   | Notebook    | [878e602f7d](https://linux-hardware.org/?probe=878e602f7d) | Jun 02, 2022 |
| HP            | 8055                        | Desktop     | [400c0e19cc](https://linux-hardware.org/?probe=400c0e19cc) | Jun 02, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2a7bfa492d](https://linux-hardware.org/?probe=2a7bfa492d) | Jun 02, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [e683ab1965](https://linux-hardware.org/?probe=e683ab1965) | Jun 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bede15789b](https://linux-hardware.org/?probe=bede15789b) | Jun 02, 2022 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [8b67a50c5e](https://linux-hardware.org/?probe=8b67a50c5e) | Jun 01, 2022 |
| Alienware     | M11x R2                     | Notebook    | [0b6837debb](https://linux-hardware.org/?probe=0b6837debb) | Jun 01, 2022 |
| Acer          | Aspire S3                   | Notebook    | [a78c44019e](https://linux-hardware.org/?probe=a78c44019e) | Jun 01, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM    | Notebook    | [8db5953984](https://linux-hardware.org/?probe=8db5953984) | Jun 01, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [86b732afda](https://linux-hardware.org/?probe=86b732afda) | Jun 01, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [fdadcc5b74](https://linux-hardware.org/?probe=fdadcc5b74) | Jun 01, 2022 |
| Dell          | G7 7700                     | Notebook    | [25e22bc243](https://linux-hardware.org/?probe=25e22bc243) | May 31, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [2940e1d0b2](https://linux-hardware.org/?probe=2940e1d0b2) | May 31, 2022 |
| HP            | Presario C500 (RT155EA#A... | Notebook    | [5eb3ee9cc2](https://linux-hardware.org/?probe=5eb3ee9cc2) | May 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [85d314bfd8](https://linux-hardware.org/?probe=85d314bfd8) | May 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [dc3ee2e520](https://linux-hardware.org/?probe=dc3ee2e520) | May 31, 2022 |
| HP            | 09E8h                       | Desktop     | [9c75a338fc](https://linux-hardware.org/?probe=9c75a338fc) | May 31, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [aae8744a5c](https://linux-hardware.org/?probe=aae8744a5c) | May 31, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [4863034bc5](https://linux-hardware.org/?probe=4863034bc5) | May 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [f5ae9fef9c](https://linux-hardware.org/?probe=f5ae9fef9c) | May 31, 2022 |
| HYPA          | FLUX                        | Notebook    | [8a69e3a34e](https://linux-hardware.org/?probe=8a69e3a34e) | May 31, 2022 |
| Alienware     | M11x R2                     | Notebook    | [4a364390a6](https://linux-hardware.org/?probe=4a364390a6) | May 31, 2022 |
| Alienware     | M11x R2                     | Notebook    | [87e8835eba](https://linux-hardware.org/?probe=87e8835eba) | May 30, 2022 |
| Gigabyte      | Q35M-S2                     | Desktop     | [7ef3498226](https://linux-hardware.org/?probe=7ef3498226) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [5a813419eb](https://linux-hardware.org/?probe=5a813419eb) | May 30, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [69e61d13d7](https://linux-hardware.org/?probe=69e61d13d7) | May 30, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| ECS           | GF8100VM-M5                 | Desktop     | [f36fc15fdc](https://linux-hardware.org/?probe=f36fc15fdc) | May 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [923158d12f](https://linux-hardware.org/?probe=923158d12f) | May 30, 2022 |
| Razer         | Blade                       | Notebook    | [d7271bb7c4](https://linux-hardware.org/?probe=d7271bb7c4) | May 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [ece4d207f3](https://linux-hardware.org/?probe=ece4d207f3) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| Intel         | DQ35JO AAD82085-803         | Desktop     | [40429e6d9a](https://linux-hardware.org/?probe=40429e6d9a) | May 29, 2022 |
| Toshiba       | Satellite C850-1KN          | Notebook    | [60b2c12831](https://linux-hardware.org/?probe=60b2c12831) | May 29, 2022 |
| AZW           | GT-R                        | Notebook    | [7823df6a86](https://linux-hardware.org/?probe=7823df6a86) | May 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [c11ae8de66](https://linux-hardware.org/?probe=c11ae8de66) | May 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [0e5f6d9e4c](https://linux-hardware.org/?probe=0e5f6d9e4c) | May 29, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d6adaef7cc](https://linux-hardware.org/?probe=d6adaef7cc) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c848e4649e](https://linux-hardware.org/?probe=c848e4649e) | May 28, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [8d120a2350](https://linux-hardware.org/?probe=8d120a2350) | May 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [1094233e96](https://linux-hardware.org/?probe=1094233e96) | May 28, 2022 |
| PC Special... | NH5x_7xDCx_DDx              | Notebook    | [bd70d45ed2](https://linux-hardware.org/?probe=bd70d45ed2) | May 28, 2022 |
| Microsoft     | Surface Go 2                | Tablet      | [2e809f0e07](https://linux-hardware.org/?probe=2e809f0e07) | May 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [8e0891e3c7](https://linux-hardware.org/?probe=8e0891e3c7) | May 27, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b98a471ead](https://linux-hardware.org/?probe=b98a471ead) | May 27, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [44162ea497](https://linux-hardware.org/?probe=44162ea497) | May 27, 2022 |
| MSI           | TRX40 PRO WIFI              | Desktop     | [36ee0ea60c](https://linux-hardware.org/?probe=36ee0ea60c) | May 27, 2022 |
| YANYU         | ITX-N29 VER:1.3             | Desktop     | [b577dd621f](https://linux-hardware.org/?probe=b577dd621f) | May 27, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [5dc9e065e3](https://linux-hardware.org/?probe=5dc9e065e3) | May 27, 2022 |
| Dell          | Precision 5530              | Notebook    | [2ecf3390bf](https://linux-hardware.org/?probe=2ecf3390bf) | May 27, 2022 |
| Dell          | Latitude 7389               | Convertible | [c7c04eece7](https://linux-hardware.org/?probe=c7c04eece7) | May 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [372a1d69d7](https://linux-hardware.org/?probe=372a1d69d7) | May 27, 2022 |
| Dell          | 02K9CR A03                  | Desktop     | [5656d7a0d5](https://linux-hardware.org/?probe=5656d7a0d5) | May 27, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d1891c2d3b](https://linux-hardware.org/?probe=d1891c2d3b) | May 27, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [d4bef1e450](https://linux-hardware.org/?probe=d4bef1e450) | May 26, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [4f083f0d35](https://linux-hardware.org/?probe=4f083f0d35) | May 25, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [d4af21adb8](https://linux-hardware.org/?probe=d4af21adb8) | May 25, 2022 |
| Alienware     | x17 R1                      | Notebook    | [a4cfdafe9d](https://linux-hardware.org/?probe=a4cfdafe9d) | May 25, 2022 |
| Acer          | Aspire C24-865              | All in one  | [c0215bd100](https://linux-hardware.org/?probe=c0215bd100) | May 25, 2022 |
| HP            | 8103 A01                    | Mini pc     | [e46d84c5c8](https://linux-hardware.org/?probe=e46d84c5c8) | May 25, 2022 |
| Toshiba       | TECRA A50-C                 | Notebook    | [60a580cb3b](https://linux-hardware.org/?probe=60a580cb3b) | May 25, 2022 |
| Acer          | Aspire S3                   | Notebook    | [d91145e274](https://linux-hardware.org/?probe=d91145e274) | May 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a649429f59](https://linux-hardware.org/?probe=a649429f59) | May 25, 2022 |
| Dell          | 0WG864                      | Desktop     | [5bda6fbb3a](https://linux-hardware.org/?probe=5bda6fbb3a) | May 24, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [fea70c6484](https://linux-hardware.org/?probe=fea70c6484) | May 24, 2022 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [94cf17bcb6](https://linux-hardware.org/?probe=94cf17bcb6) | May 24, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [de2c57e521](https://linux-hardware.org/?probe=de2c57e521) | May 24, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [da9b5c2be2](https://linux-hardware.org/?probe=da9b5c2be2) | May 24, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [2be14c5fa8](https://linux-hardware.org/?probe=2be14c5fa8) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f87621c475](https://linux-hardware.org/?probe=f87621c475) | May 24, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [7152b312be](https://linux-hardware.org/?probe=7152b312be) | May 23, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [0339b395ed](https://linux-hardware.org/?probe=0339b395ed) | May 23, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [70b5e91823](https://linux-hardware.org/?probe=70b5e91823) | May 23, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [afb47f4860](https://linux-hardware.org/?probe=afb47f4860) | May 23, 2022 |
| BOX           | W54_W94_W955TU,-T,-C        | Notebook    | [a36f54939d](https://linux-hardware.org/?probe=a36f54939d) | May 23, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [f833ddc13b](https://linux-hardware.org/?probe=f833ddc13b) | May 23, 2022 |
| Entroware     | Apollo                      | Notebook    | [30881be24b](https://linux-hardware.org/?probe=30881be24b) | May 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [7d3f9c0a5f](https://linux-hardware.org/?probe=7d3f9c0a5f) | May 23, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [2034bf506d](https://linux-hardware.org/?probe=2034bf506d) | May 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [fe1d187774](https://linux-hardware.org/?probe=fe1d187774) | May 22, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [47c446b3d8](https://linux-hardware.org/?probe=47c446b3d8) | May 22, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [90d0bb5bc0](https://linux-hardware.org/?probe=90d0bb5bc0) | May 22, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [48047cdaf6](https://linux-hardware.org/?probe=48047cdaf6) | May 22, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [63d7169ac1](https://linux-hardware.org/?probe=63d7169ac1) | May 22, 2022 |
| Acer          | Aspire C24-865              | All in one  | [98c5c2fbfd](https://linux-hardware.org/?probe=98c5c2fbfd) | May 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [595b06f6c9](https://linux-hardware.org/?probe=595b06f6c9) | May 22, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [5bf86728dc](https://linux-hardware.org/?probe=5bf86728dc) | May 22, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [e856d4589a](https://linux-hardware.org/?probe=e856d4589a) | May 21, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [adddbe7947](https://linux-hardware.org/?probe=adddbe7947) | May 21, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| MSI           | 2AE0                        | Desktop     | [d99294cadc](https://linux-hardware.org/?probe=d99294cadc) | May 21, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [1609781085](https://linux-hardware.org/?probe=1609781085) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [2211d5c2a2](https://linux-hardware.org/?probe=2211d5c2a2) | May 20, 2022 |
| Entroware     | Triton                      | Notebook    | [2bfa3e5cc8](https://linux-hardware.org/?probe=2bfa3e5cc8) | May 20, 2022 |
| Acer          | Aspire C24-865              | All in one  | [97f59bfda5](https://linux-hardware.org/?probe=97f59bfda5) | May 20, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [45fa54c9ff](https://linux-hardware.org/?probe=45fa54c9ff) | May 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [7cae58580a](https://linux-hardware.org/?probe=7cae58580a) | May 20, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5c989cad8d](https://linux-hardware.org/?probe=5c989cad8d) | May 20, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ab767eaa59](https://linux-hardware.org/?probe=ab767eaa59) | May 19, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [27ebc7fd11](https://linux-hardware.org/?probe=27ebc7fd11) | May 19, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [ae9b0dc77e](https://linux-hardware.org/?probe=ae9b0dc77e) | May 19, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [9e2c754ed6](https://linux-hardware.org/?probe=9e2c754ed6) | May 19, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d5712e1976](https://linux-hardware.org/?probe=d5712e1976) | May 19, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [e30e3da709](https://linux-hardware.org/?probe=e30e3da709) | May 18, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [8f9f8c2634](https://linux-hardware.org/?probe=8f9f8c2634) | May 18, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b098eb44db](https://linux-hardware.org/?probe=b098eb44db) | May 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [2e663e698c](https://linux-hardware.org/?probe=2e663e698c) | May 18, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [382192bd2c](https://linux-hardware.org/?probe=382192bd2c) | May 18, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [f92e29b330](https://linux-hardware.org/?probe=f92e29b330) | May 17, 2022 |
| Lenovo        | SDK0F82993 WIN              | All in one  | [39c4df81a2](https://linux-hardware.org/?probe=39c4df81a2) | May 17, 2022 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [2e9d55d3a7](https://linux-hardware.org/?probe=2e9d55d3a7) | May 17, 2022 |
| ASUSTek       | G15DK                       | Desktop     | [1df44e40e2](https://linux-hardware.org/?probe=1df44e40e2) | May 17, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [78fe695a2f](https://linux-hardware.org/?probe=78fe695a2f) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [b1afeba24a](https://linux-hardware.org/?probe=b1afeba24a) | May 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [7fcd8503ab](https://linux-hardware.org/?probe=7fcd8503ab) | May 16, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [874d108fe3](https://linux-hardware.org/?probe=874d108fe3) | May 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [06afc33451](https://linux-hardware.org/?probe=06afc33451) | May 16, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [6c433b3b60](https://linux-hardware.org/?probe=6c433b3b60) | May 16, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [7807aa5ed4](https://linux-hardware.org/?probe=7807aa5ed4) | May 16, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [ee54db9f9e](https://linux-hardware.org/?probe=ee54db9f9e) | May 16, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [06625fa3f2](https://linux-hardware.org/?probe=06625fa3f2) | May 15, 2022 |
| HP            | Unknown                     | Notebook    | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [0f70996b58](https://linux-hardware.org/?probe=0f70996b58) | May 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [beaaf4e7f7](https://linux-hardware.org/?probe=beaaf4e7f7) | May 15, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [b37b4cdbbb](https://linux-hardware.org/?probe=b37b4cdbbb) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [2555fd899e](https://linux-hardware.org/?probe=2555fd899e) | May 15, 2022 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [8586a581d0](https://linux-hardware.org/?probe=8586a581d0) | May 15, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a48bb9c613](https://linux-hardware.org/?probe=a48bb9c613) | May 14, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [951323a711](https://linux-hardware.org/?probe=951323a711) | May 14, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [3fc95850aa](https://linux-hardware.org/?probe=3fc95850aa) | May 14, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [eef86f3d24](https://linux-hardware.org/?probe=eef86f3d24) | May 14, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [b46632bd9a](https://linux-hardware.org/?probe=b46632bd9a) | May 14, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [67dbfe0d98](https://linux-hardware.org/?probe=67dbfe0d98) | May 14, 2022 |
| Lenovo        | ThinkPad T470 20HES1RB06    | Notebook    | [0d115ce977](https://linux-hardware.org/?probe=0d115ce977) | May 14, 2022 |
| Acer          | Aspire C24-1650             | All in one  | [a28b44985d](https://linux-hardware.org/?probe=a28b44985d) | May 13, 2022 |
| Acer          | Aspire C24-865              | All in one  | [b164e17b68](https://linux-hardware.org/?probe=b164e17b68) | May 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [44952d0fff](https://linux-hardware.org/?probe=44952d0fff) | May 13, 2022 |
| Star Labs     | Lite                        | Notebook    | [dbe031aada](https://linux-hardware.org/?probe=dbe031aada) | May 13, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [40cc6f33b5](https://linux-hardware.org/?probe=40cc6f33b5) | May 13, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [433432f3ee](https://linux-hardware.org/?probe=433432f3ee) | May 12, 2022 |
| AZW           | BT3 X                       | Desktop     | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | Notebook    | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [578328d0b5](https://linux-hardware.org/?probe=578328d0b5) | May 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5d84102fa2](https://linux-hardware.org/?probe=5d84102fa2) | May 11, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [4142d08db8](https://linux-hardware.org/?probe=4142d08db8) | May 11, 2022 |
| Dell          | Precision M6600             | Notebook    | [730205ec1e](https://linux-hardware.org/?probe=730205ec1e) | May 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c703872774](https://linux-hardware.org/?probe=c703872774) | May 11, 2022 |
| Lenovo        | ThinkPad T480 20L6S5M40M    | Notebook    | [f2213829f0](https://linux-hardware.org/?probe=f2213829f0) | May 11, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [08deba5f5f](https://linux-hardware.org/?probe=08deba5f5f) | May 11, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [f790f52fa7](https://linux-hardware.org/?probe=f790f52fa7) | May 11, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [72b102de04](https://linux-hardware.org/?probe=72b102de04) | May 10, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [debc8c7d47](https://linux-hardware.org/?probe=debc8c7d47) | May 10, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [bef0e3659e](https://linux-hardware.org/?probe=bef0e3659e) | May 10, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [0fed762686](https://linux-hardware.org/?probe=0fed762686) | May 10, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [b9afe34b9a](https://linux-hardware.org/?probe=b9afe34b9a) | May 10, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [bfdc40105f](https://linux-hardware.org/?probe=bfdc40105f) | May 10, 2022 |
| HP            | EliteBook 2730p             | Notebook    | [d4c5b7824d](https://linux-hardware.org/?probe=d4c5b7824d) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [20eb5bfb9f](https://linux-hardware.org/?probe=20eb5bfb9f) | May 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ace8669bdd](https://linux-hardware.org/?probe=ace8669bdd) | May 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 1095      | 17.43%  |
| Ubuntu 18.04      | 587       | 9.34%   |
| Ubuntu 22.04      | 157       | 2.5%    |
| OpenMandriva 4.2  | 130       | 2.07%   |
| Zorin 16          | 129       | 2.05%   |
| Linux Mint 20.2   | 111       | 1.77%   |
| OpenMandriva 4.3  | 110       | 1.75%   |
| Linux Mint 19.3   | 110       | 1.75%   |
| KDE neon 20.04    | 110       | 1.75%   |
| Debian 11         | 108       | 1.72%   |
| Pop!_OS 20.04     | 107       | 1.7%    |
| Ubuntu 19.04      | 105       | 1.67%   |
| Ubuntu 20.10      | 100       | 1.59%   |
| Pop!_OS 21.04     | 100       | 1.59%   |
| Arch              | 99        | 1.58%   |
| Arch Rolling      | 96        | 1.53%   |
| Ubuntu 21.10      | 94        | 1.5%    |
| Linux Mint 20.3   | 94        | 1.5%    |
| Manjaro           | 92        | 1.46%   |
| Zorin 15          | 89        | 1.42%   |
| Ubuntu 19.10      | 89        | 1.42%   |
| Pop!_OS 20.10     | 85        | 1.35%   |
| Linux Mint 20.1   | 84        | 1.34%   |
| Ubuntu 21.04      | 80        | 1.27%   |
| ArcoLinux Rolling | 76        | 1.21%   |
| Xubuntu 20.04     | 73        | 1.16%   |
| Linux Mint 20     | 66        | 1.05%   |
| Fedora 34         | 60        | 0.96%   |
| Pop!_OS 21.10     | 57        | 0.91%   |
| Ubuntu 18.10      | 56        | 0.89%   |
| Kubuntu 20.04     | 56        | 0.89%   |
| Fedora 35         | 55        | 0.88%   |
| Fedora 36         | 51        | 0.81%   |
| Pop!_OS 22.04     | 49        | 0.78%   |
| Fedora 33         | 48        | 0.76%   |
| Fedora 31         | 48        | 0.76%   |
| Debian 10         | 46        | 0.73%   |
| Fedora 32         | 43        | 0.68%   |
| BlackPanther 18.1 | 39        | 0.62%   |
| Xubuntu 18.04     | 33        | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2306      | 38.37%  |
| Linux Mint    | 519       | 8.64%   |
| Pop!_OS       | 375       | 6.24%   |
| Fedora        | 312       | 5.19%   |
| OpenMandriva  | 275       | 4.58%   |
| Zorin         | 228       | 3.79%   |
| Manjaro       | 200       | 3.33%   |
| Debian        | 197       | 3.28%   |
| Arch          | 193       | 3.21%   |
| Xubuntu       | 132       | 2.2%    |
| Kubuntu       | 126       | 2.1%    |
| KDE neon      | 123       | 2.05%   |
| ArcoLinux     | 80        | 1.33%   |
| ROSA          | 73        | 1.21%   |
| Elementary    | 66        | 1.1%    |
| Ubuntu MATE   | 58        | 0.97%   |
| Gentoo        | 58        | 0.97%   |
| openSUSE      | 52        | 0.87%   |
| Endless       | 52        | 0.87%   |
| Ubuntu Unity  | 45        | 0.75%   |
| Lubuntu       | 44        | 0.73%   |
| Clear Linux   | 43        | 0.72%   |
| BlackPanther  | 40        | 0.67%   |
| Kali          | 36        | 0.6%    |
| SteamOS       | 31        | 0.52%   |
| LMDE          | 25        | 0.42%   |
| CentOS        | 25        | 0.42%   |
| Garuda Linux  | 20        | 0.33%   |
| Ubuntu Budgie | 18        | 0.3%    |
| MX            | 18        | 0.3%    |
| EndeavourOS   | 18        | 0.3%    |
| Raspbian      | 16        | 0.27%   |
| Peppermint    | 16        | 0.27%   |
| RHEL          | 15        | 0.25%   |
| Parrot        | 12        | 0.2%    |
| Slackware     | 11        | 0.18%   |
| NixOS         | 8         | 0.13%   |
| Alpine        | 8         | 0.13%   |
| Mageia        | 7         | 0.12%   |
| Reborn OS     | 6         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 152       | 2.17%   |
| 5.10.14-desktop-1omv4002 | 127       | 1.81%   |
| 5.16.7-desktop-1omv4003  | 107       | 1.52%   |
| 5.4.0-48-generic         | 81        | 1.15%   |
| 5.4.0-52-generic         | 76        | 1.08%   |
| 5.4.0-29-generic         | 73        | 1.04%   |
| 5.4.0-26-generic         | 70        | 1%      |
| 5.3.0-28-generic         | 65        | 0.93%   |
| 5.3.0-40-generic         | 60        | 0.85%   |
| 5.15.0-46-generic        | 60        | 0.85%   |
| 5.4.0-40-generic         | 53        | 0.76%   |
| 5.4.0-37-generic         | 51        | 0.73%   |
| 5.11.0-27-generic        | 51        | 0.73%   |
| 5.4.0-58-generic         | 50        | 0.71%   |
| 5.4.0-65-generic         | 45        | 0.64%   |
| 5.4.0-33-generic         | 45        | 0.64%   |
| 5.11.0-38-generic        | 45        | 0.64%   |
| 5.0.0-32-generic         | 45        | 0.64%   |
| 5.13.0-7614-generic      | 43        | 0.61%   |
| 5.11.0-25-generic        | 43        | 0.61%   |
| 5.4.0-91-generic         | 41        | 0.58%   |
| 5.4.0-7634-generic       | 41        | 0.58%   |
| 5.4.0-54-generic         | 41        | 0.58%   |
| 5.3.0-46-generic         | 41        | 0.58%   |
| 5.4.0-74-generic         | 40        | 0.57%   |
| 5.4.0-66-generic         | 40        | 0.57%   |
| 5.8.0-7630-generic       | 39        | 0.56%   |
| 5.8.0-43-generic         | 39        | 0.56%   |
| 5.11.0-7620-generic      | 39        | 0.56%   |
| 5.0.0-37-generic         | 39        | 0.56%   |
| 5.11.0-40-generic        | 38        | 0.54%   |
| 5.11.0-37-generic        | 38        | 0.54%   |
| 5.3.0-42-generic         | 37        | 0.53%   |
| 5.13.0-28-generic        | 37        | 0.53%   |
| 5.8.0-50-generic         | 36        | 0.51%   |
| 5.8.0-44-generic         | 36        | 0.51%   |
| 5.4.0-56-generic         | 36        | 0.51%   |
| 5.11.0-43-generic        | 36        | 0.51%   |
| 5.4.0-47-generic         | 35        | 0.5%    |
| 5.13.0-39-generic        | 35        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1453      | 22.36%  |
| 5.11.0  | 452       | 6.96%   |
| 5.8.0   | 447       | 6.88%   |
| 4.15.0  | 411       | 6.33%   |
| 5.13.0  | 391       | 6.02%   |
| 5.3.0   | 374       | 5.76%   |
| 5.15.0  | 272       | 4.19%   |
| 5.0.0   | 244       | 3.76%   |
| 4.18.0  | 178       | 2.74%   |
| 5.10.0  | 143       | 2.2%    |
| 5.10.14 | 127       | 1.95%   |
| 5.16.7  | 108       | 1.66%   |
| 4.19.0  | 56        | 0.86%   |
| 4.18.16 | 32        | 0.49%   |
| 5.17.5  | 30        | 0.46%   |
| 5.14.0  | 27        | 0.42%   |
| 4.9.60  | 26        | 0.4%    |
| 5.9.16  | 25        | 0.38%   |
| 5.19.0  | 21        | 0.32%   |
| 4.4.0   | 21        | 0.32%   |
| 5.18.0  | 19        | 0.29%   |
| 5.17.1  | 19        | 0.29%   |
| 5.18.12 | 18        | 0.28%   |
| 5.16.11 | 18        | 0.28%   |
| 5.15.12 | 17        | 0.26%   |
| 5.13.12 | 17        | 0.26%   |
| 5.16.0  | 16        | 0.25%   |
| 4.9.20  | 16        | 0.25%   |
| 5.7.0   | 15        | 0.23%   |
| 5.15.15 | 15        | 0.23%   |
| 5.12.4  | 15        | 0.23%   |
| 5.12.13 | 15        | 0.23%   |
| 5.6.14  | 14        | 0.22%   |
| 5.6.0   | 14        | 0.22%   |
| 5.3.18  | 14        | 0.22%   |
| 5.17.0  | 14        | 0.22%   |
| 5.8.6   | 13        | 0.2%    |
| 4.9.0   | 13        | 0.2%    |
| 5.9.11  | 12        | 0.18%   |
| 5.9.1   | 12        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1542      | 24.06%  |
| 5.8     | 535       | 8.35%   |
| 5.11    | 510       | 7.96%   |
| 5.13    | 477       | 7.44%   |
| 5.15    | 431       | 6.72%   |
| 5.3     | 424       | 6.62%   |
| 4.15    | 413       | 6.44%   |
| 5.10    | 400       | 6.24%   |
| 5.0     | 254       | 3.96%   |
| 5.16    | 213       | 3.32%   |
| 4.18    | 213       | 3.32%   |
| 5.17    | 97        | 1.51%   |
| 5.9     | 95        | 1.48%   |
| 5.14    | 95        | 1.48%   |
| 5.12    | 88        | 1.37%   |
| 4.19    | 88        | 1.37%   |
| 5.18    | 86        | 1.34%   |
| 5.6     | 75        | 1.17%   |
| 4.9     | 72        | 1.12%   |
| 5.19    | 71        | 1.11%   |
| 5.7     | 67        | 1.05%   |
| 5.5     | 42        | 0.66%   |
| 4.4     | 25        | 0.39%   |
| 5.2     | 23        | 0.36%   |
| 5.1     | 16        | 0.25%   |
| 4.14    | 10        | 0.16%   |
| 4.1     | 9         | 0.14%   |
| 3.10    | 8         | 0.12%   |
| 4.20    | 5         | 0.08%   |
| 4.13    | 5         | 0.08%   |
| 3.13    | 4         | 0.06%   |
| 6.0     | 3         | 0.05%   |
| 4.16    | 3         | 0.05%   |
| 4.12    | 3         | 0.05%   |
| 4.8     | 2         | 0.03%   |
| 5       | 1         | 0.02%   |
| 4.6     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| 3.19    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5526      | 95.7%   |
| i686    | 168       | 2.91%   |
| aarch64 | 59        | 1.02%   |
| armv7l  | 21        | 0.36%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2775      | 45.75%  |
| Unknown          | 885       | 14.59%  |
| KDE5             | 815       | 13.44%  |
| X-Cinnamon       | 413       | 6.81%   |
| XFCE             | 394       | 6.5%    |
| KDE              | 173       | 2.85%   |
| MATE             | 155       | 2.56%   |
| Cinnamon         | 83        | 1.37%   |
| Pantheon         | 62        | 1.02%   |
| Unity            | 47        | 0.77%   |
| LXQt             | 42        | 0.69%   |
| LXDE             | 38        | 0.63%   |
| KDE4             | 36        | 0.59%   |
| Budgie           | 26        | 0.43%   |
| i3               | 25        | 0.41%   |
| GNOME Flashback  | 23        | 0.38%   |
| Deepin           | 12        | 0.2%    |
| sway             | 9         | 0.15%   |
| Openbox          | 8         | 0.13%   |
| qtile            | 6         | 0.1%    |
| GNOME Classic    | 6         | 0.1%    |
| awesome          | 5         | 0.08%   |
| xmonad           | 4         | 0.07%   |
| lightdm-xsession | 3         | 0.05%   |
| DWM              | 3         | 0.05%   |
| bspwm            | 3         | 0.05%   |
| trinity          | 2         | 0.03%   |
| i3-with-shmlog   | 2         | 0.03%   |
| enlightenment    | 2         | 0.03%   |
| Cutefish         | 2         | 0.03%   |
| xubuntu          | 1         | 0.02%   |
| WindowMaker      | 1         | 0.02%   |
| Phosh:GNOME      | 1         | 0.02%   |
| LeftWM           | 1         | 0.02%   |
| icewm            | 1         | 0.02%   |
| GNUstep          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4743      | 80.04%  |
| Wayland | 610       | 10.29%  |
| Unknown | 444       | 7.49%   |
| Tty     | 128       | 2.16%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3623      | 60.24%  |
| SDDM    | 715       | 11.89%  |
| GDM     | 613       | 10.19%  |
| LightDM | 408       | 6.78%   |
| GDM3    | 392       | 6.52%   |
| TDM     | 196       | 3.26%   |
| KDM     | 35        | 0.58%   |
| XDM     | 14        | 0.23%   |
| LXDM    | 5         | 0.08%   |
| SLiM    | 4         | 0.07%   |
| Ly      | 4         | 0.07%   |
| XINIT   | 1         | 0.02%   |
| NODM    | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |
| CDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| en_GB          | 4221      | 71.31%  |
| Unknown        | 803       | 13.57%  |
| en_US          | 633       | 10.69%  |
| C              | 86        | 1.45%   |
| pl_PL          | 50        | 0.84%   |
| ru_RU          | 10        | 0.17%   |
| POSIX          | 10        | 0.17%   |
| en_CA          | 10        | 0.17%   |
| en_IE          | 9         | 0.15%   |
| de_DE          | 9         | 0.15%   |
| it_IT          | 8         | 0.14%   |
| en_IN          | 6         | 0.1%    |
| cs_CZ          | 6         | 0.1%    |
| ro_RO          | 5         | 0.08%   |
| hu_HU          | 5         | 0.08%   |
| en_AU          | 5         | 0.08%   |
| pt_PT          | 4         | 0.07%   |
| fr_FR          | 4         | 0.07%   |
| zh_CN          | 3         | 0.05%   |
| sk_SK          | 3         | 0.05%   |
| pt_BR          | 3         | 0.05%   |
| es_ES          | 3         | 0.05%   |
| C.UTF8         | 3         | 0.05%   |
| uk_UA          | 2         | 0.03%   |
| nl_NL          | 2         | 0.03%   |
| da_DK          | 2         | 0.03%   |
| bg_BG          | 2         | 0.03%   |
| wbp_AU         | 1         | 0.02%   |
| tr_TR          | 1         | 0.02%   |
| nl_BE          | 1         | 0.02%   |
| fi_FI          | 1         | 0.02%   |
| en_ZA          | 1         | 0.02%   |
| en_US.utf-8    | 1         | 0.02%   |
| en_IL          | 1         | 0.02%   |
| en_HK          | 1         | 0.02%   |
| en_GG          | 1         | 0.02%   |
| en_GB.utf-8    | 1         | 0.02%   |
| en_GB.iso88591 | 1         | 0.02%   |
| en_AG          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3152      | 53.42%  |
| EFI  | 2748      | 46.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4732      | 80.04%  |
| Btrfs    | 396       | 6.7%    |
| Overlay  | 370       | 6.26%   |
| Unknown  | 232       | 3.92%   |
| Xfs      | 82        | 1.39%   |
| Zfs      | 45        | 0.76%   |
| Ext2     | 19        | 0.32%   |
| Tmpfs    | 14        | 0.24%   |
| Ext3     | 10        | 0.17%   |
| F2fs     | 8         | 0.14%   |
| Reiserfs | 1         | 0.02%   |
| Lvm      | 1         | 0.02%   |
| ExX4     | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3821      | 64.92%  |
| GPT     | 1571      | 26.69%  |
| MBR     | 494       | 8.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5000      | 84.9%   |
| Yes       | 889       | 15.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4258      | 72.53%  |
| Yes       | 1613      | 27.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 934       | 16.19%  |
| ASUSTek Computer        | 839       | 14.54%  |
| Hewlett-Packard         | 737       | 12.77%  |
| Lenovo                  | 693       | 12.01%  |
| Gigabyte Technology     | 428       | 7.42%   |
| MSI                     | 313       | 5.42%   |
| Acer                    | 282       | 4.89%   |
| ASRock                  | 183       | 3.17%   |
| Apple                   | 171       | 2.96%   |
| Toshiba                 | 135       | 2.34%   |
| Intel                   | 109       | 1.89%   |
| Samsung Electronics     | 70        | 1.21%   |
| Raspberry Pi Foundation | 62        | 1.07%   |
| Sony                    | 53        | 0.92%   |
| Fujitsu                 | 41        | 0.71%   |
| PC Specialist           | 37        | 0.64%   |
| Unknown                 | 37        | 0.64%   |
| HUAWEI                  | 36        | 0.62%   |
| Packard Bell            | 32        | 0.55%   |
| Foxconn                 | 29        | 0.5%    |
| Notebook                | 27        | 0.47%   |
| Microsoft               | 27        | 0.47%   |
| Valve                   | 24        | 0.42%   |
| Google                  | 24        | 0.42%   |
| Pegatron                | 21        | 0.36%   |
| Fujitsu Siemens         | 19        | 0.33%   |
| Alienware               | 19        | 0.33%   |
| Razer                   | 16        | 0.28%   |
| Medion                  | 16        | 0.28%   |
| Star Labs               | 15        | 0.26%   |
| Biostar                 | 15        | 0.26%   |
| Dixonsxp                | 13        | 0.23%   |
| Linx                    | 12        | 0.21%   |
| Entroware               | 12        | 0.21%   |
| AMI                     | 12        | 0.21%   |
| Chuwi                   | 10        | 0.17%   |
| Advent                  | 10        | 0.17%   |
| Jumper                  | 9         | 0.16%   |
| Clevo                   | 9         | 0.16%   |
| Supermicro              | 8         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 62        | 1.07%   |
| Unknown                            | 60        | 1.04%   |
| Dell OptiPlex 7010                 | 27        | 0.47%   |
| Valve Jupiter                      | 24        | 0.42%   |
| MSI MS-7C02                        | 24        | 0.42%   |
| RPi Raspberry Pi                   | 22        | 0.38%   |
| HP Pavilion g6                     | 21        | 0.36%   |
| Dell OptiPlex 755                  | 18        | 0.31%   |
| HP Pavilion 15                     | 17        | 0.29%   |
| Dell OptiPlex 780                  | 17        | 0.29%   |
| ASUS ROG STRIX B450-F GAMING       | 17        | 0.29%   |
| ASUS M5A78L-M/USB3                 | 17        | 0.29%   |
| MSI MS-7C37                        | 16        | 0.28%   |
| HP Pavilion Notebook               | 15        | 0.26%   |
| Dell OptiPlex 790                  | 15        | 0.26%   |
| HP Notebook                        | 14        | 0.24%   |
| Dell Inspiron 1545                 | 14        | 0.24%   |
| ASUS TUF Gaming X570-PLUS          | 14        | 0.24%   |
| Dell XPS 13 9370                   | 13        | 0.23%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 12        | 0.21%   |
| Gigabyte X570 AORUS ELITE          | 12        | 0.21%   |
| Dell XPS 15 9560                   | 12        | 0.21%   |
| Dell XPS 15 7590                   | 12        | 0.21%   |
| Dell XPS 13 9360                   | 12        | 0.21%   |
| Gigabyte 970A-DS3P                 | 11        | 0.19%   |
| Dell XPS 15 9570                   | 11        | 0.19%   |
| Dell Latitude E6410                | 11        | 0.19%   |
| Dell Latitude E6400                | 11        | 0.19%   |
| ASUS PRIME A320M-K                 | 11        | 0.19%   |
| Lenovo V145-15AST 81MT             | 10        | 0.17%   |
| HP ProLiant MicroServer            | 10        | 0.17%   |
| Gigabyte GA-78LMT-USB3 6.0         | 10        | 0.17%   |
| Gigabyte GA-78LMT-USB3             | 10        | 0.17%   |
| Dell XPS 13 9380                   | 10        | 0.17%   |
| Dell Latitude E7240                | 10        | 0.17%   |
| Apple MacBookPro9,2                | 10        | 0.17%   |
| Microsoft Surface Pro 4            | 9         | 0.16%   |
| Lenovo Z50-75 80EC                 | 9         | 0.16%   |
| HP Laptop 15-bw0xx                 | 9         | 0.16%   |
| HP 15                              | 9         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 327       | 5.67%   |
| Dell Latitude          | 207       | 3.59%   |
| Acer Aspire            | 207       | 3.59%   |
| Dell Inspiron          | 199       | 3.45%   |
| Dell OptiPlex          | 164       | 2.84%   |
| Dell XPS               | 154       | 2.67%   |
| HP Pavilion            | 127       | 2.2%    |
| ASUS ROG               | 121       | 2.1%    |
| Toshiba Satellite      | 118       | 2.05%   |
| Lenovo IdeaPad         | 107       | 1.85%   |
| ASUS PRIME             | 102       | 1.77%   |
| HP EliteBook           | 86        | 1.49%   |
| Dell Precision         | 86        | 1.49%   |
| HP Compaq              | 85        | 1.47%   |
| RPi Raspberry          | 62        | 1.07%   |
| ASUS All               | 62        | 1.07%   |
| Unknown                | 60        | 1.04%   |
| Lenovo ThinkCentre     | 52        | 0.9%    |
| HP ProBook             | 50        | 0.87%   |
| HP Laptop              | 48        | 0.83%   |
| ASUS TUF               | 44        | 0.76%   |
| Dell Vostro            | 42        | 0.73%   |
| HP ENVY                | 41        | 0.71%   |
| ASUS VivoBook          | 41        | 0.71%   |
| Lenovo Yoga            | 30        | 0.52%   |
| HP ProLiant            | 30        | 0.52%   |
| Gigabyte X570          | 30        | 0.52%   |
| Microsoft Surface      | 27        | 0.47%   |
| Valve Jupiter          | 24        | 0.42%   |
| MSI MS-7C02            | 24        | 0.42%   |
| HP Stream              | 24        | 0.42%   |
| Gigabyte GA-78LMT-USB3 | 24        | 0.42%   |
| ASUS M5A78L-M          | 24        | 0.42%   |
| HP EliteDesk           | 23        | 0.4%    |
| HP Spectre             | 22        | 0.38%   |
| Acer Swift             | 20        | 0.35%   |
| Lenovo Legion          | 19        | 0.33%   |
| Fujitsu ESPRIMO        | 18        | 0.31%   |
| Dell PowerEdge         | 17        | 0.29%   |
| ASUS ZenBook           | 17        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 594       | 10.29%  |
| 2019    | 527       | 9.13%   |
| 2012    | 483       | 8.37%   |
| 2020    | 448       | 7.76%   |
| 2013    | 422       | 7.31%   |
| 2011    | 404       | 7%      |
| 2017    | 396       | 6.86%   |
| 2014    | 371       | 6.43%   |
| 2010    | 340       | 5.89%   |
| 2015    | 315       | 5.46%   |
| 2016    | 299       | 5.18%   |
| 2021    | 270       | 4.68%   |
| 2009    | 259       | 4.49%   |
| 2008    | 245       | 4.25%   |
| 2007    | 173       | 3%      |
| 2006    | 73        | 1.27%   |
| Unknown | 62        | 1.07%   |
| 2022    | 54        | 0.94%   |
| 2005    | 24        | 0.42%   |
| 2004    | 6         | 0.1%    |
| 2003    | 3         | 0.05%   |
| 2002    | 2         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2913      | 50.49%  |
| Desktop        | 2358      | 40.87%  |
| Convertible    | 104       | 1.8%    |
| All in one     | 102       | 1.77%   |
| Mini pc        | 100       | 1.73%   |
| System on chip | 72        | 1.25%   |
| Tablet         | 69        | 1.2%    |
| Server         | 47        | 0.81%   |
| Phone          | 4         | 0.07%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5353      | 92.07%  |
| Enabled  | 461       | 7.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5734      | 99.38%  |
| Yes  | 36        | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1291      | 22%     |
| 16.01-24.0      | 1260      | 21.48%  |
| 3.01-4.0        | 1064      | 18.14%  |
| 8.01-16.0       | 999       | 17.03%  |
| 32.01-64.0      | 576       | 9.82%   |
| 1.01-2.0        | 278       | 4.74%   |
| 64.01-256.0     | 150       | 2.56%   |
| 2.01-3.0        | 112       | 1.91%   |
| 24.01-32.0      | 75        | 1.28%   |
| 0.51-1.0        | 52        | 0.89%   |
| More than 256.0 | 6         | 0.1%    |
| 0.01-0.5        | 4         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 2503      | 38.76%  |
| 2.01-3.0    | 1567      | 24.27%  |
| 4.01-8.0    | 795       | 12.31%  |
| 3.01-4.0    | 742       | 11.49%  |
| 0.51-1.0    | 458       | 7.09%   |
| 8.01-16.0   | 229       | 3.55%   |
| 0.01-0.5    | 92        | 1.42%   |
| 16.01-24.0  | 35        | 0.54%   |
| 24.01-32.0  | 16        | 0.25%   |
| 32.01-64.0  | 13        | 0.2%    |
| Unknown     | 4         | 0.06%   |
| 64.01-256.0 | 3         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3359      | 56.18%  |
| 2       | 1493      | 24.97%  |
| 3       | 490       | 8.2%    |
| 4       | 266       | 4.45%   |
| 5       | 145       | 2.43%   |
| 6       | 75        | 1.25%   |
| 0       | 64        | 1.07%   |
| 7       | 34        | 0.57%   |
| 9       | 14        | 0.23%   |
| 8       | 14        | 0.23%   |
| Unknown | 8         | 0.13%   |
| 11      | 5         | 0.08%   |
| 12      | 4         | 0.07%   |
| 13      | 3         | 0.05%   |
| 10      | 2         | 0.03%   |
| 21      | 1         | 0.02%   |
| 20      | 1         | 0.02%   |
| 14      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3353      | 57.49%  |
| Yes       | 2479      | 42.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4927      | 85.26%  |
| No        | 852       | 14.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4367      | 75.06%  |
| No        | 1451      | 24.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3280      | 56.14%  |
| No        | 2563      | 43.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 5770      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| London              | 330       | 5.23%   |
| Manchester          | 133       | 2.11%   |
| Bristol             | 102       | 1.62%   |
| Birmingham          | 98        | 1.55%   |
| Glasgow             | 93        | 1.47%   |
| Edinburgh           | 88        | 1.39%   |
| Sheffield           | 82        | 1.3%    |
| Nottingham          | 77        | 1.22%   |
| Liverpool           | 73        | 1.16%   |
| Leeds               | 60        | 0.95%   |
| Islington           | 58        | 0.92%   |
| Reading             | 55        | 0.87%   |
| Norwich             | 54        | 0.86%   |
| Cambridge           | 54        | 0.86%   |
| Milton Keynes       | 43        | 0.68%   |
| Croydon             | 42        | 0.67%   |
| Southampton         | 41        | 0.65%   |
| Coventry            | 41        | 0.65%   |
| Leicester           | 38        | 0.6%    |
| Derby               | 38        | 0.6%    |
| Aberdeen            | 38        | 0.6%    |
| Cardiff             | 37        | 0.59%   |
| Hackney             | 34        | 0.54%   |
| Bradford            | 34        | 0.54%   |
| Swindon             | 33        | 0.52%   |
| Gloucester          | 33        | 0.52%   |
| Oxford              | 32        | 0.51%   |
| Wolverhampton       | 31        | 0.49%   |
| Kensington          | 31        | 0.49%   |
| Brighton            | 31        | 0.49%   |
| York                | 30        | 0.48%   |
| Newcastle upon Tyne | 30        | 0.48%   |
| Clapham             | 30        | 0.48%   |
| Bolton              | 29        | 0.46%   |
| Wigan               | 28        | 0.44%   |
| Walsall             | 28        | 0.44%   |
| Sunderland          | 28        | 0.44%   |
| Plymouth            | 27        | 0.43%   |
| Camden              | 26        | 0.41%   |
| Bromley             | 26        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1362      | 2253   | 15.67%  |
| Samsung Electronics       | 1309      | 2017   | 15.06%  |
| WDC                       | 1265      | 2075   | 14.56%  |
| Toshiba                   | 614       | 829    | 7.06%   |
| SanDisk                   | 492       | 648    | 5.66%   |
| Unknown                   | 456       | 635    | 5.25%   |
| Crucial                   | 436       | 628    | 5.02%   |
| Kingston                  | 377       | 515    | 4.34%   |
| Hitachi                   | 354       | 476    | 4.07%   |
| SK hynix                  | 173       | 205    | 1.99%   |
| Intel                     | 173       | 231    | 1.99%   |
| HGST                      | 149       | 216    | 1.71%   |
| Phison                    | 139       | 186    | 1.6%    |
| China                     | 88        | 119    | 1.01%   |
| Apple                     | 88        | 119    | 1.01%   |
| Micron Technology         | 87        | 104    | 1%      |
| A-DATA Technology         | 83        | 108    | 0.96%   |
| OCZ                       | 56        | 65     | 0.64%   |
| Maxtor                    | 55        | 82     | 0.63%   |
| PNY                       | 52        | 65     | 0.6%    |
| LITEON                    | 48        | 56     | 0.55%   |
| KIOXIA                    | 48        | 65     | 0.55%   |
| Corsair                   | 45        | 62     | 0.52%   |
| Transcend                 | 43        | 52     | 0.49%   |
| Silicon Motion            | 43        | 54     | 0.49%   |
| Fujitsu                   | 39        | 53     | 0.45%   |
| LITEONIT                  | 30        | 37     | 0.35%   |
| ASMT                      | 22        | 51     | 0.25%   |
| JMicron Technology        | 21        | 32     | 0.24%   |
| Unknown                   | 21        | 26     | 0.24%   |
| Micron/Crucial Technology | 20        | 29     | 0.23%   |
| SABRENT                   | 19        | 21     | 0.22%   |
| Integral                  | 19        | 23     | 0.22%   |
| Patriot                   | 18        | 30     | 0.21%   |
| Gigabyte Technology       | 17        | 23     | 0.2%    |
| Drevo                     | 15        | 20     | 0.17%   |
| Team                      | 14        | 15     | 0.16%   |
| Netac                     | 14        | 17     | 0.16%   |
| SPCC                      | 13        | 22     | 0.15%   |
| Hewlett-Packard           | 13        | 38     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  32GB             | 108       | 1.1%    |
| Seagate ST3500312CS 500GB          | 79        | 0.81%   |
| Samsung SSD 850 EVO 250GB          | 78        | 0.8%    |
| Samsung SSD 850 EVO 500GB          | 69        | 0.71%   |
| Kingston SA400S37240G 240GB SSD    | 67        | 0.69%   |
| Samsung NVMe SSD Drive 500GB       | 63        | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 61        | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB     | 61        | 0.62%   |
| Crucial CT500MX500SSD1 500GB       | 61        | 0.62%   |
| Kingston SA400S37120G 120GB SSD    | 60        | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB     | 58        | 0.59%   |
| Unknown MMC Card  64GB             | 57        | 0.58%   |
| Crucial CT1000MX500SSD1 1TB        | 57        | 0.58%   |
| Samsung SSD 860 EVO 500GB          | 56        | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB     | 55        | 0.56%   |
| Samsung NVMe SSD Drive 512GB       | 54        | 0.55%   |
| Seagate ST500DM002-1BD142 500GB    | 50        | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB       | 50        | 0.51%   |
| Samsung NVMe SSD Drive 1TB         | 50        | 0.51%   |
| Unknown MMC Card  128GB            | 49        | 0.5%    |
| Samsung NVMe SSD Drive 256GB       | 49        | 0.5%    |
| Toshiba MQ01ABD100 1TB             | 47        | 0.48%   |
| Samsung SSD 860 EVO 1TB            | 47        | 0.48%   |
| Crucial CT250MX500SSD1 250GB       | 37        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD   | 36        | 0.37%   |
| Seagate Expansion 1TB              | 35        | 0.36%   |
| Samsung SSD 840 EVO 250GB          | 35        | 0.36%   |
| HGST HTS721010A9E630 1TB           | 35        | 0.36%   |
| Crucial CT240BX500SSD1 240GB       | 35        | 0.36%   |
| Unknown SD/MMC/MS PRO 2GB          | 33        | 0.34%   |
| Toshiba NVMe SSD Drive 256GB       | 33        | 0.34%   |
| Toshiba DT01ACA100 1TB             | 32        | 0.33%   |
| Seagate ST2000DM001-1ER164 2TB     | 32        | 0.33%   |
| Seagate ST4000DM004-2CV104 4TB     | 31        | 0.32%   |
| Seagate ST1000DM003-1ER162 1TB     | 31        | 0.32%   |
| SanDisk SSD PLUS 240GB             | 31        | 0.32%   |
| HGST HTS541010A9E680 1TB           | 31        | 0.32%   |
| SanDisk SSD PLUS 480GB             | 29        | 0.3%    |
| SanDisk NVMe SSD Drive 1TB         | 29        | 0.3%    |
| Seagate ST1000DM003-1CH162 1TB     | 28        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1318      | 2163   | 35.62%  |
| WDC                 | 1002      | 1688   | 27.08%  |
| Toshiba             | 451       | 619    | 12.19%  |
| Hitachi             | 353       | 474    | 9.54%   |
| Samsung Electronics | 189       | 267    | 5.11%   |
| HGST                | 149       | 216    | 4.03%   |
| Maxtor              | 45        | 72     | 1.22%   |
| Apple               | 42        | 48     | 1.14%   |
| Unknown             | 40        | 53     | 1.08%   |
| Fujitsu             | 39        | 53     | 1.05%   |
| ASMT                | 15        | 44     | 0.41%   |
| Hewlett-Packard     | 12        | 37     | 0.32%   |
| USB3.0              | 7         | 11     | 0.19%   |
| ASMedia             | 5         | 10     | 0.14%   |
| HPE                 | 3         | 5      | 0.08%   |
| ASMT109x            | 3         | 5      | 0.08%   |
| WD MediaMax         | 2         | 2      | 0.05%   |
| USB                 | 2         | 2      | 0.05%   |
| LaCie               | 2         | 2      | 0.05%   |
| KESU                | 2         | 6      | 0.05%   |
| JMicron Technology  | 2         | 4      | 0.05%   |
| IBM/Hitachi         | 2         | 2      | 0.05%   |
| ExcelStor           | 2         | 4      | 0.05%   |
| TrueNAS             | 1         | 3      | 0.03%   |
| SATAFIRM            | 1         | 2      | 0.03%   |
| SAGE                | 1         | 1      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| NETAPP              | 1         | 4      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| Magnetic Data       | 1         | 1      | 0.03%   |
| LIO-ORG             | 1         | 8      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 677       | 988    | 22.93%  |
| Crucial             | 405       | 591    | 13.72%  |
| SanDisk             | 358       | 450    | 12.13%  |
| Kingston            | 327       | 439    | 11.08%  |
| WDC                 | 164       | 225    | 5.56%   |
| China               | 84        | 115    | 2.85%   |
| Intel               | 76        | 87     | 2.57%   |
| A-DATA Technology   | 64        | 81     | 2.17%   |
| OCZ                 | 56        | 65     | 1.9%    |
| Toshiba             | 54        | 65     | 1.83%   |
| PNY                 | 49        | 58     | 1.66%   |
| Micron Technology   | 49        | 60     | 1.66%   |
| SK hynix            | 47        | 58     | 1.59%   |
| LITEON              | 47        | 55     | 1.59%   |
| Apple               | 42        | 55     | 1.42%   |
| Transcend           | 41        | 50     | 1.39%   |
| LITEONIT            | 30        | 37     | 1.02%   |
| Corsair             | 26        | 37     | 0.88%   |
| Integral            | 19        | 23     | 0.64%   |
| Patriot             | 18        | 30     | 0.61%   |
| Unknown             | 17        | 19     | 0.58%   |
| Seagate             | 17        | 20     | 0.58%   |
| Drevo               | 15        | 20     | 0.51%   |
| Team                | 13        | 14     | 0.44%   |
| Netac               | 13        | 14     | 0.44%   |
| Gigabyte Technology | 12        | 16     | 0.41%   |
| Vaseky              | 11        | 15     | 0.37%   |
| SPCC                | 10        | 19     | 0.34%   |
| Maxtor              | 10        | 10     | 0.34%   |
| Lexar               | 10        | 12     | 0.34%   |
| TO Exter            | 9         | 10     | 0.3%    |
| TCSUNBOW            | 9         | 14     | 0.3%    |
| KingDian            | 7         | 10     | 0.24%   |
| ASMT                | 7         | 7      | 0.24%   |
| Plextor             | 6         | 9      | 0.2%    |
| ORTIAL              | 6         | 6      | 0.2%    |
| NGFF                | 6         | 6      | 0.2%    |
| KIOXIA-EXCERIA      | 6         | 10     | 0.2%    |
| KingSpec            | 6         | 8      | 0.2%    |
| Star                | 5         | 6      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3009      | 5813   | 39.58%  |
| SSD     | 2501      | 3973   | 32.9%   |
| NVMe    | 1560      | 2243   | 20.52%  |
| MMC     | 405       | 557    | 5.33%   |
| Unknown | 127       | 188    | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4482      | 9381   | 65.95%  |
| NVMe | 1537      | 2199   | 22.62%  |
| MMC  | 405       | 557    | 5.96%   |
| SAS  | 372       | 637    | 5.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3367      | 5541   | 56.84%  |
| 0.51-1.0   | 1585      | 2428   | 26.76%  |
| 1.01-2.0   | 545       | 943    | 9.2%    |
| 2.01-3.0   | 147       | 267    | 2.48%   |
| 3.01-4.0   | 145       | 277    | 2.45%   |
| 4.01-10.0  | 117       | 285    | 1.98%   |
| 10.01-20.0 | 17        | 44     | 0.29%   |
| 0          | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1709      | 27.89%  |
| 251-500        | 1183      | 19.31%  |
| 501-1000       | 894       | 14.59%  |
| 1001-2000      | 472       | 7.7%    |
| 51-100         | 410       | 6.69%   |
| 1-20           | 404       | 6.59%   |
| More than 3000 | 358       | 5.84%   |
| 21-50          | 303       | 4.95%   |
| 2001-3000      | 202       | 3.3%    |
| Unknown        | 192       | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2584      | 40.58%  |
| 21-50          | 1040      | 16.33%  |
| 101-250        | 729       | 11.45%  |
| 51-100         | 662       | 10.4%   |
| 251-500        | 440       | 6.91%   |
| 501-1000       | 311       | 4.88%   |
| 1001-2000      | 205       | 3.22%   |
| Unknown        | 192       | 3.02%   |
| More than 3000 | 132       | 2.07%   |
| 2001-3000      | 72        | 1.13%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 6         | 6      | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 6         | 8      | 1.43%   |
| HGST HTS725050A7E630 500GB            | 6         | 9      | 1.43%   |
| Seagate ST500DM002-1BD142 500GB       | 5         | 5      | 1.19%   |
| Seagate ST3500418AS 500GB             | 5         | 5      | 1.19%   |
| Samsung Electronics HD103UJ 1TB       | 5         | 7      | 1.19%   |
| Seagate ST9500325AS 500GB             | 4         | 5      | 0.95%   |
| Seagate ST3500312CS 500GB             | 4         | 6      | 0.95%   |
| Hitachi HTS545025B9A300 250GB         | 4         | 4      | 0.95%   |
| HGST HTS721010A9E630 1TB              | 4         | 4      | 0.95%   |
| WDC WD5000BEVT-75A0RT0 500GB          | 3         | 5      | 0.72%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 3         | 3      | 0.72%   |
| Toshiba DT01ACA050 500GB              | 3         | 4      | 0.72%   |
| Seagate ST3500620AS 500GB             | 3         | 4      | 0.72%   |
| Seagate ST1000LM014-SSHD-8GB          | 3         | 4      | 0.72%   |
| Samsung Electronics SSD 960 EVO 250GB | 3         | 4      | 0.72%   |
| Samsung Electronics HD103SJ 1TB       | 3         | 3      | 0.72%   |
| Hitachi HUA723030ALA640 3TB           | 3         | 4      | 0.72%   |
| Hitachi HTS547575A9E384 752GB         | 3         | 5      | 0.72%   |
| Hitachi HTS542512K9SA00 120GB         | 3         | 3      | 0.72%   |
| Hitachi HDT721010SLA360 1TB           | 3         | 4      | 0.72%   |
| Hitachi HDS721010CLA332 1TB           | 3         | 3      | 0.72%   |
| Hitachi HDP725050GLA360 500GB         | 3         | 3      | 0.72%   |
| HGST HTS541010A9E680 1TB              | 3         | 3      | 0.72%   |
| Crucial CT525MX300SSD4 528GB          | 3         | 3      | 0.72%   |
| WDC WD800JD-00HKA0 80GB               | 2         | 2      | 0.48%   |
| WDC WD6400AAKS-22A7B2 640GB           | 2         | 2      | 0.48%   |
| WDC WD6400AAKS-22A7B0 640GB           | 2         | 2      | 0.48%   |
| WDC WD5000BEVT-60A0RT0 500GB          | 2         | 3      | 0.48%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 2         | 2      | 0.48%   |
| WDC WD3200AAKS-75B3A0 320GB           | 2         | 2      | 0.48%   |
| WDC WD2500BEVT-80A23T0 250GB          | 2         | 4      | 0.48%   |
| WDC WD10EZEX-00WN4A0 1TB              | 2         | 2      | 0.48%   |
| WDC WD10EADS-00L5B1 1TB               | 2         | 2      | 0.48%   |
| Unknown MM0500EBKAE 500GB             | 2         | 2      | 0.48%   |
| Toshiba MK3276GSX -63 320GB           | 2         | 2      | 0.48%   |
| Toshiba MK1656GSY 160GB               | 2         | 2      | 0.48%   |
| Toshiba DT01ACA100 1TB                | 2         | 2      | 0.48%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 0.48%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 106       | 127    | 26.04%  |
| WDC                 | 87        | 139    | 21.38%  |
| Hitachi             | 53        | 76     | 13.02%  |
| Samsung Electronics | 33        | 41     | 8.11%   |
| Toshiba             | 22        | 27     | 5.41%   |
| Crucial             | 21        | 27     | 5.16%   |
| HGST                | 17        | 20     | 4.18%   |
| SanDisk             | 11        | 15     | 2.7%    |
| Intel               | 10        | 12     | 2.46%   |
| Kingston            | 6         | 8      | 1.47%   |
| SK hynix            | 4         | 4      | 0.98%   |
| Maxtor              | 4         | 4      | 0.98%   |
| Fujitsu             | 4         | 4      | 0.98%   |
| A-DATA Technology   | 4         | 4      | 0.98%   |
| Micron Technology   | 3         | 3      | 0.74%   |
| LITEON              | 3         | 3      | 0.74%   |
| Corsair             | 3         | 7      | 0.74%   |
| Unknown             | 2         | 2      | 0.49%   |
| Hewlett-Packard     | 2         | 2      | 0.49%   |
| Drevo               | 2         | 3      | 0.49%   |
| Zheino              | 1         | 2      | 0.25%   |
| VENO                | 1         | 1      | 0.25%   |
| Team                | 1         | 1      | 0.25%   |
| OCZ                 | 1         | 1      | 0.25%   |
| Faspeed             | 1         | 1      | 0.25%   |
| China               | 1         | 1      | 0.25%   |
| BIWIN               | 1         | 1      | 0.25%   |
| BAITITON            | 1         | 3      | 0.25%   |
| Apple               | 1         | 2      | 0.25%   |
| Apacer              | 1         | 1      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 106       | 127    | 34.08%  |
| WDC                 | 85        | 137    | 27.33%  |
| Hitachi             | 53        | 76     | 17.04%  |
| Toshiba             | 21        | 26     | 6.75%   |
| HGST                | 17        | 20     | 5.47%   |
| Samsung Electronics | 16        | 20     | 5.14%   |
| Maxtor              | 4         | 4      | 1.29%   |
| Fujitsu             | 4         | 4      | 1.29%   |
| Unknown             | 2         | 2      | 0.64%   |
| Hewlett-Packard     | 2         | 2      | 0.64%   |
| Apple               | 1         | 2      | 0.32%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 282       | 420    | 74.6%   |
| SSD  | 80        | 103    | 21.16%  |
| NVMe | 16        | 19     | 4.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB  | 2         | 3      | 33.33%  |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 16.67%  |
| Seagate ST3160815AS 160GB         | 1         | 1      | 16.67%  |
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 16.67%  |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 4      | 50%     |
| Seagate             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3993      | 8616   | 64.66%  |
| Works    | 1810      | 3609   | 29.31%  |
| Malfunc  | 367       | 542    | 5.94%   |
| Failed   | 5         | 7      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3705      | 51.75%  |
| AMD                              | 1244      | 17.38%  |
| Samsung Electronics              | 614       | 8.58%   |
| SanDisk                          | 245       | 3.42%   |
| Phison Electronics               | 168       | 2.35%   |
| ASMedia Technology               | 149       | 2.08%   |
| Nvidia                           | 136       | 1.9%    |
| Toshiba America Info Systems     | 123       | 1.72%   |
| SK hynix                         | 121       | 1.69%   |
| Marvell Technology Group         | 105       | 1.47%   |
| JMicron Technology               | 77        | 1.08%   |
| Kingston Technology Company      | 56        | 0.78%   |
| Micron/Crucial Technology        | 51        | 0.71%   |
| Silicon Motion                   | 47        | 0.66%   |
| KIOXIA                           | 44        | 0.61%   |
| Micron Technology                | 40        | 0.56%   |
| ADATA Technology                 | 32        | 0.45%   |
| LSI Logic / Symbios Logic        | 30        | 0.42%   |
| Broadcom / LSI                   | 21        | 0.29%   |
| VIA Technologies                 | 20        | 0.28%   |
| Silicon Image                    | 18        | 0.25%   |
| Seagate Technology               | 18        | 0.25%   |
| Silicon Integrated Systems [SiS] | 15        | 0.21%   |
| Hewlett-Packard                  | 11        | 0.15%   |
| Apple                            | 9         | 0.13%   |
| Adaptec                          | 8         | 0.11%   |
| Realtek Semiconductor            | 7         | 0.1%    |
| Lenovo                           | 7         | 0.1%    |
| Solid State Storage Technology   | 5         | 0.07%   |
| Union Memory (Shenzhen)          | 4         | 0.06%   |
| Shenzhen Longsys Electronics     | 4         | 0.06%   |
| O2 Micro                         | 4         | 0.06%   |
| Lite-On Technology               | 4         | 0.06%   |
| Integrated Technology Express    | 3         | 0.04%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.03%   |
| Dell                             | 2         | 0.03%   |
| ULi Electronics                  | 1         | 0.01%   |
| OCZ Technology Group             | 1         | 0.01%   |
| Initio                           | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 834       | 9.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 346       | 4.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 247       | 2.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 236       | 2.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 233       | 2.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 201       | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                                  | 179       | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 161       | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 155       | 1.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 149       | 1.77%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 142       | 1.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 141       | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 139       | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 121       | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 115       | 1.36%   |
| Intel SATA Controller [RAID mode]                                                       | 110       | 1.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 108       | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 108       | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 101       | 1.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 100       | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 96        | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 96        | 1.14%   |
| Phison E12 NVMe Controller                                                              | 95        | 1.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 93        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 90        | 1.07%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 82        | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 78        | 0.92%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 77        | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 73        | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                                  | 72        | 0.85%   |
| Samsung NVMe SSD Controller 980                                                         | 69        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 65        | 0.77%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 64        | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 62        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 62        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 62        | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 59        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 55        | 0.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 54        | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 54        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4155      | 57.51%  |
| NVMe | 1557      | 21.55%  |
| IDE  | 986       | 13.65%  |
| RAID | 469       | 6.49%   |
| SAS  | 33        | 0.46%   |
| SCSI | 25        | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 4242      | 73.52%  |
| AMD          | 1449      | 25.11%  |
| ARM          | 77        | 1.33%   |
| QUALCOMM     | 1         | 0.02%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 72        | 1.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 57        | 0.99%   |
| ARM Processor                           | 57        | 0.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 47        | 0.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 45        | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 43        | 0.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 40        | 0.69%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 40        | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 38        | 0.66%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 38        | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 37        | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 37        | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 35        | 0.6%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 35        | 0.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz       | 35        | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz       | 34        | 0.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 34        | 0.59%   |
| AMD FX-8350 Eight-Core Processor        | 34        | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 33        | 0.57%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 33        | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 33        | 0.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 33        | 0.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 32        | 0.55%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 31        | 0.54%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 31        | 0.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 31        | 0.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 28        | 0.48%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 28        | 0.48%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 27        | 0.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 26        | 0.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 25        | 0.43%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 25        | 0.43%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 25        | 0.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 24        | 0.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 24        | 0.41%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 24        | 0.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 24        | 0.41%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 24        | 0.41%   |
| AMD Custom APU 0405                     | 24        | 0.41%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 23        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1166      | 20.18%  |
| Intel Core i7           | 1133      | 19.61%  |
| Intel Core i3           | 371       | 6.42%   |
| AMD Ryzen 5             | 293       | 5.07%   |
| Intel Celeron           | 280       | 4.85%   |
| Other                   | 279       | 4.83%   |
| Intel Core 2 Duo        | 277       | 4.79%   |
| AMD Ryzen 7             | 233       | 4.03%   |
| Intel Xeon              | 173       | 2.99%   |
| Intel Pentium           | 160       | 2.77%   |
| AMD FX                  | 127       | 2.2%    |
| Intel Atom              | 109       | 1.89%   |
| AMD Ryzen 9             | 95        | 1.64%   |
| AMD A6                  | 71        | 1.23%   |
| AMD Ryzen 3             | 70        | 1.21%   |
| AMD A8                  | 68        | 1.18%   |
| Intel Pentium Dual-Core | 64        | 1.11%   |
| Intel Core 2 Quad       | 61        | 1.06%   |
| Intel Core 2            | 52        | 0.9%    |
| AMD A10                 | 51        | 0.88%   |
| Intel Core i9           | 43        | 0.74%   |
| Intel Pentium Dual      | 39        | 0.67%   |
| AMD Athlon II X2        | 36        | 0.62%   |
| AMD A4                  | 35        | 0.61%   |
| AMD Phenom II X4        | 30        | 0.52%   |
| Intel Genuine           | 26        | 0.45%   |
| Intel Pentium 4         | 22        | 0.38%   |
| AMD Athlon 64 X2        | 21        | 0.36%   |
| AMD Ryzen Threadripper  | 20        | 0.35%   |
| Intel Celeron Dual-Core | 19        | 0.33%   |
| ARM BCM                 | 19        | 0.33%   |
| AMD E1                  | 19        | 0.33%   |
| AMD E                   | 19        | 0.33%   |
| AMD Athlon              | 19        | 0.33%   |
| Intel Pentium D         | 15        | 0.26%   |
| AMD Athlon II X4        | 15        | 0.26%   |
| Intel Pentium Silver    | 13        | 0.22%   |
| Intel Celeron M         | 13        | 0.22%   |
| AMD Phenom II X6        | 12        | 0.21%   |
| AMD Phenom              | 12        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2426      | 41.99%  |
| 4       | 2024      | 35.03%  |
| 6       | 538       | 9.31%   |
| 8       | 386       | 6.68%   |
| 1       | 168       | 2.91%   |
| 12      | 76        | 1.32%   |
| 3       | 54        | 0.93%   |
| 16      | 53        | 0.92%   |
| 10      | 14        | 0.24%   |
| 14      | 12        | 0.21%   |
| 24      | 11        | 0.19%   |
| 32      | 5         | 0.09%   |
| Unknown | 3         | 0.05%   |
| 40      | 2         | 0.03%   |
| 28      | 2         | 0.03%   |
| 20      | 2         | 0.03%   |
| 64      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5688      | 98.58%  |
| 2       | 76        | 1.32%   |
| Unknown | 3         | 0.05%   |
| 4       | 2         | 0.03%   |
| 3       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3628      | 62.82%  |
| 1       | 2144      | 37.13%  |
| Unknown | 3         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5554      | 95.81%  |
| Unknown        | 168       | 2.9%    |
| 32-bit         | 70        | 1.21%   |
| 64-bit         | 5         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1299      | 21.76%  |
| 0x206a7    | 330       | 5.53%   |
| 0x306a9    | 329       | 5.51%   |
| 0x306c3    | 271       | 4.54%   |
| 0x1067a    | 242       | 4.05%   |
| 0x906ea    | 147       | 2.46%   |
| 0x806ea    | 125       | 2.09%   |
| 0x506e3    | 122       | 2.04%   |
| 0x08701021 | 114       | 1.91%   |
| 0x406e3    | 113       | 1.89%   |
| 0x40651    | 108       | 1.81%   |
| 0x20655    | 107       | 1.79%   |
| 0x806e9    | 106       | 1.78%   |
| 0x806ec    | 104       | 1.74%   |
| 0x906e9    | 96        | 1.61%   |
| 0x6fd      | 89        | 1.49%   |
| 0x306d4    | 89        | 1.49%   |
| 0x406c4    | 81        | 1.36%   |
| 0x806c1    | 79        | 1.32%   |
| 0x010000c8 | 72        | 1.21%   |
| 0x06000852 | 67        | 1.12%   |
| 0x06001119 | 65        | 1.09%   |
| 0x30678    | 61        | 1.02%   |
| 0x10676    | 59        | 0.99%   |
| 0x0800820d | 55        | 0.92%   |
| 0x08108109 | 51        | 0.85%   |
| 0x08701013 | 50        | 0.84%   |
| 0x6fb      | 45        | 0.75%   |
| 0x506c9    | 45        | 0.75%   |
| 0xa0652    | 44        | 0.74%   |
| 0x906ed    | 43        | 0.72%   |
| 0x20652    | 43        | 0.72%   |
| 0x06006705 | 40        | 0.67%   |
| 0x406c3    | 37        | 0.62%   |
| 0x08108102 | 36        | 0.6%    |
| 0x706a1    | 35        | 0.59%   |
| 0x706e5    | 34        | 0.57%   |
| 0x6f6      | 34        | 0.57%   |
| 0x206c2    | 33        | 0.55%   |
| 0x106e5    | 31        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 843       | 14.59%  |
| Haswell          | 493       | 8.53%   |
| SandyBridge      | 425       | 7.36%   |
| IvyBridge        | 414       | 7.17%   |
| Penryn           | 349       | 6.04%   |
| Skylake          | 298       | 5.16%   |
| Zen 2            | 290       | 5.02%   |
| Core             | 234       | 4.05%   |
| Silvermont       | 221       | 3.83%   |
| Westmere         | 217       | 3.76%   |
| Zen+             | 196       | 3.39%   |
| Piledriver       | 175       | 3.03%   |
| K10              | 157       | 2.72%   |
| Unknown          | 154       | 2.67%   |
| Zen              | 126       | 2.18%   |
| Broadwell        | 126       | 2.18%   |
| Zen 3            | 104       | 1.8%    |
| TigerLake        | 101       | 1.75%   |
| CometLake        | 99        | 1.71%   |
| Excavator        | 96        | 1.66%   |
| Nehalem          | 71        | 1.23%   |
| IceLake          | 70        | 1.21%   |
| Goldmont plus    | 64        | 1.11%   |
| Goldmont         | 54        | 0.93%   |
| K8 Hammer        | 52        | 0.9%    |
| Steamroller      | 47        | 0.81%   |
| Puma             | 47        | 0.81%   |
| NetBurst         | 42        | 0.73%   |
| Bobcat           | 41        | 0.71%   |
| Bonnell          | 40        | 0.69%   |
| P6               | 38        | 0.66%   |
| Jaguar           | 24        | 0.42%   |
| Bulldozer        | 24        | 0.42%   |
| Alderlake Hybrid | 16        | 0.28%   |
| K8 & K10 hybrid  | 10        | 0.17%   |
| K10 Llano        | 10        | 0.17%   |
| Tremont          | 5         | 0.09%   |
| K6               | 4         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3163      | 48.62%  |
| Nvidia                                       | 1816      | 27.92%  |
| AMD                                          | 1454      | 22.35%  |
| Matrox Electronics Systems                   | 32        | 0.49%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.23%   |
| ASPEED Technology                            | 9         | 0.14%   |
| ATI Technologies                             | 8         | 0.12%   |
| VIA Technologies                             | 5         | 0.08%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Huawei Technologies                          | 1         | 0.02%   |
| Alliance Semiconductor                       | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 311       | 4.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 224       | 3.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 142       | 2.11%   |
| Intel UHD Graphics 620                                                                   | 138       | 2.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 135       | 2.01%   |
| Intel Core Processor Integrated Graphics Controller                                      | 134       | 1.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 133       | 1.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 129       | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 125       | 1.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 112       | 1.67%   |
| Intel HD Graphics 620                                                                    | 111       | 1.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 111       | 1.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 107       | 1.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 92        | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 91        | 1.35%   |
| Intel HD Graphics 5500                                                                   | 91        | 1.35%   |
| Intel HD Graphics 630                                                                    | 90        | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 88        | 1.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 86        | 1.28%   |
| Intel HD Graphics 530                                                                    | 79        | 1.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 77        | 1.14%   |
| AMD Renoir                                                                               | 74        | 1.1%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 71        | 1.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 63        | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 55        | 0.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 54        | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 54        | 0.8%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 53        | 0.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 51        | 0.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 50        | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 48        | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 48        | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 47        | 0.7%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 47        | 0.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 46        | 0.68%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 45        | 0.67%   |
| Intel HD Graphics 500                                                                    | 44        | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 41        | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 40        | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 39        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 2462      | 42.3%   |
| 1 x AMD                              | 1244      | 21.37%  |
| 1 x Nvidia                           | 1180      | 20.27%  |
| Intel + Nvidia                       | 541       | 9.29%   |
| Intel + AMD                          | 89        | 1.53%   |
| Other                                | 86        | 1.48%   |
| 2 x AMD                              | 62        | 1.07%   |
| AMD + Nvidia                         | 57        | 0.98%   |
| 1 x Matrox                           | 28        | 0.48%   |
| 2 x Nvidia                           | 26        | 0.45%   |
| 1 x SiS                              | 14        | 0.24%   |
| 1 x VIA                              | 5         | 0.09%   |
| Nvidia + ASPEED                      | 5         | 0.09%   |
| 1 x ASPEED                           | 4         | 0.07%   |
| Nvidia + Matrox                      | 3         | 0.05%   |
| 2 x AMD + 1 x Nvidia                 | 2         | 0.03%   |
| Intel + 2 x Nvidia                   | 2         | 0.03%   |
| Intel + AMD + 1 x Nvidia             | 2         | 0.03%   |
| 3 x AMD                              | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.02%   |
| 2 x Intel                            | 1         | 0.02%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.02%   |
| 1 x XGI                              | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia               | 1         | 0.02%   |
| 1 x Huawei Technologies              | 1         | 0.02%   |
| AMD + SiS                            | 1         | 0.02%   |
| AMD + ASPEED                         | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4541      | 77.29%  |
| Proprietary | 1039      | 17.69%  |
| Unknown     | 295       | 5.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3211      | 53.88%  |
| 0.01-0.5   | 717       | 12.03%  |
| 1.01-2.0   | 681       | 11.43%  |
| 0.51-1.0   | 443       | 7.43%   |
| 3.01-4.0   | 370       | 6.21%   |
| 7.01-8.0   | 275       | 4.61%   |
| 5.01-6.0   | 142       | 2.38%   |
| 8.01-16.0  | 73        | 1.22%   |
| 2.01-3.0   | 42        | 0.7%    |
| 16.01-24.0 | 3         | 0.05%   |
| 4.01-5.0   | 1         | 0.02%   |
| 24.01-32.0 | 1         | 0.02%   |
| 0          | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 707       | 11.62%  |
| AU Optronics            | 683       | 11.22%  |
| LG Display              | 518       | 8.51%   |
| Dell                    | 438       | 7.2%    |
| Chimei Innolux          | 385       | 6.33%   |
| BOE                     | 360       | 5.92%   |
| Acer                    | 270       | 4.44%   |
| Goldstar                | 221       | 3.63%   |
| Hewlett-Packard         | 205       | 3.37%   |
| BenQ                    | 191       | 3.14%   |
| AOC                     | 189       | 3.11%   |
| Sharp                   | 179       | 2.94%   |
| Apple                   | 136       | 2.24%   |
| Iiyama                  | 122       | 2%      |
| Ancor Communications    | 120       | 1.97%   |
| Lenovo                  | 111       | 1.82%   |
| Philips                 | 91        | 1.5%    |
| ViewSonic               | 71        | 1.17%   |
| Sony                    | 69        | 1.13%   |
| Chi Mei Optoelectronics | 69        | 1.13%   |
| Unknown                 | 61        | 1%      |
| HannStar                | 54        | 0.89%   |
| PANDA                   | 52        | 0.85%   |
| ASUSTek Computer        | 45        | 0.74%   |
| Panasonic               | 42        | 0.69%   |
| LG Philips              | 42        | 0.69%   |
| Toshiba                 | 38        | 0.62%   |
| LG Electronics          | 36        | 0.59%   |
| InfoVision              | 34        | 0.56%   |
| Vestel Elektronik       | 33        | 0.54%   |
| NEC Computers           | 24        | 0.39%   |
| MSI                     | 23        | 0.38%   |
| ANX                     | 21        | 0.35%   |
| OEM                     | 16        | 0.26%   |
| Hitachi                 | 15        | 0.25%   |
| Gigabyte Technology     | 13        | 0.21%   |
| Fujitsu Siemens         | 13        | 0.21%   |
| LGD                     | 12        | 0.2%    |
| Idek Iiyama             | 12        | 0.2%    |
| InnoLux Display         | 11        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 37        | 0.59%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 33        | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 28        | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 27        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 26        | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 24        | 0.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 24        | 0.38%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 23        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 22        | 0.35%   |
| ANX ANX7530 U ANX7539 800x1280                                        | 21        | 0.33%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 17        | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 16        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 16        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 15        | 0.24%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 15        | 0.24%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 14        | 0.22%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                       | 14        | 0.22%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 13        | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 13        | 0.21%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 13        | 0.21%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 13        | 0.21%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 13        | 0.21%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 13        | 0.21%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 12        | 0.19%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch  | 12        | 0.19%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 12        | 0.19%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 12        | 0.19%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 12        | 0.19%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 12        | 0.19%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 12        | 0.19%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 12        | 0.19%   |
| Toshiba 32W_LCD_TV TSB3700 1920x1080 710x400mm 32.1-inch              | 11        | 0.17%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 11        | 0.17%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch | 11        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 11        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 11        | 0.17%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 11        | 0.17%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 11        | 0.17%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 11        | 0.17%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 11        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2461      | 41.68%  |
| 1366x768 (WXGA)    | 1007      | 17.06%  |
| 3840x2160 (4K)     | 432       | 7.32%   |
| 2560x1440 (QHD)    | 287       | 4.86%   |
| 1280x1024 (SXGA)   | 215       | 3.64%   |
| 1280x800 (WXGA)    | 183       | 3.1%    |
| 1600x900 (HD+)     | 168       | 2.85%   |
| 1440x900 (WXGA+)   | 162       | 2.74%   |
| 1680x1050 (WSXGA+) | 156       | 2.64%   |
| 1920x1200 (WUXGA)  | 124       | 2.1%    |
| Unknown            | 100       | 1.69%   |
| 3440x1440          | 67        | 1.13%   |
| 1360x768           | 51        | 0.86%   |
| 2560x1080          | 46        | 0.78%   |
| 3840x1080          | 42        | 0.71%   |
| 1920x540           | 37        | 0.63%   |
| 2560x1600          | 33        | 0.56%   |
| 1024x768 (XGA)     | 28        | 0.47%   |
| 3840x2400          | 26        | 0.44%   |
| 800x1280           | 24        | 0.41%   |
| 3200x1800 (QHD+)   | 22        | 0.37%   |
| 1600x1200          | 20        | 0.34%   |
| 2736x1824          | 18        | 0.3%    |
| 1280x720 (HD)      | 18        | 0.3%    |
| 1024x600           | 18        | 0.3%    |
| 2160x1440          | 14        | 0.24%   |
| 2880x1800          | 13        | 0.22%   |
| 2288x1287          | 8         | 0.14%   |
| 5760x1080          | 7         | 0.12%   |
| 5120x1440          | 7         | 0.12%   |
| 1920x1280          | 6         | 0.1%    |
| 7680x2160          | 5         | 0.08%   |
| 3840x1200          | 5         | 0.08%   |
| 2256x1504          | 5         | 0.08%   |
| 3200x1080          | 4         | 0.07%   |
| 2880x1920          | 4         | 0.07%   |
| 1680x945           | 4         | 0.07%   |
| 5760x2160          | 3         | 0.05%   |
| 4480x1440          | 3         | 0.05%   |
| 3456x2160          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1389      | 22.91%  |
| 13      | 569       | 9.38%   |
| 27      | 469       | 7.73%   |
| Unknown | 464       | 7.65%   |
| 24      | 431       | 7.11%   |
| 23      | 385       | 6.35%   |
| 21      | 341       | 5.62%   |
| 14      | 326       | 5.38%   |
| 17      | 315       | 5.19%   |
| 12      | 180       | 2.97%   |
| 19      | 170       | 2.8%    |
| 31      | 112       | 1.85%   |
| 22      | 97        | 1.6%    |
| 11      | 95        | 1.57%   |
| 84      | 90        | 1.48%   |
| 34      | 83        | 1.37%   |
| 18      | 78        | 1.29%   |
| 20      | 64        | 1.06%   |
| 72      | 49        | 0.81%   |
| 26      | 36        | 0.59%   |
| 25      | 31        | 0.51%   |
| 10      | 31        | 0.51%   |
| 54      | 28        | 0.46%   |
| 32      | 26        | 0.43%   |
| 16      | 22        | 0.36%   |
| 33      | 16        | 0.26%   |
| 48      | 14        | 0.23%   |
| 65      | 12        | 0.2%    |
| 40      | 12        | 0.2%    |
| 39      | 12        | 0.2%    |
| 46      | 11        | 0.18%   |
| 28      | 11        | 0.18%   |
| 60      | 10        | 0.16%   |
| 55      | 10        | 0.16%   |
| 52      | 8         | 0.13%   |
| 35      | 8         | 0.13%   |
| 43      | 7         | 0.12%   |
| 8       | 7         | 0.12%   |
| 29      | 6         | 0.1%    |
| 142     | 5         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2006      | 33.55%  |
| 501-600        | 1204      | 20.13%  |
| 201-300        | 660       | 11.04%  |
| 401-500        | 648       | 10.84%  |
| Unknown        | 464       | 7.76%   |
| 351-400        | 366       | 6.12%   |
| 601-700        | 196       | 3.28%   |
| 1501-2000      | 140       | 2.34%   |
| 701-800        | 125       | 2.09%   |
| 1001-1500      | 112       | 1.87%   |
| 801-900        | 35        | 0.59%   |
| 901-1000       | 10        | 0.17%   |
| More than 2000 | 7         | 0.12%   |
| 101-200        | 7         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4023      | 72.12%  |
| 16/10   | 682       | 12.23%  |
| Unknown | 385       | 6.9%    |
| 5/4     | 197       | 3.53%   |
| 21/9    | 98        | 1.76%   |
| 3/2     | 72        | 1.29%   |
| 4/3     | 60        | 1.08%   |
| 0.62    | 25        | 0.45%   |
| 32/9    | 16        | 0.29%   |
| 6/5     | 10        | 0.18%   |
| 1.00    | 7         | 0.13%   |
| 3.20    | 2         | 0.04%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1383      | 23.02%  |
| 201-250        | 1003      | 16.7%   |
| 81-90          | 594       | 9.89%   |
| 301-350        | 495       | 8.24%   |
| Unknown        | 464       | 7.72%   |
| 151-200        | 356       | 5.93%   |
| 71-80          | 314       | 5.23%   |
| 351-500        | 254       | 4.23%   |
| More than 1000 | 226       | 3.76%   |
| 121-130        | 175       | 2.91%   |
| 251-300        | 162       | 2.7%    |
| 61-70          | 160       | 2.66%   |
| 141-150        | 149       | 2.48%   |
| 51-60          | 98        | 1.63%   |
| 501-1000       | 68        | 1.13%   |
| 131-140        | 40        | 0.67%   |
| 41-50          | 28        | 0.47%   |
| 111-120        | 22        | 0.37%   |
| 91-100         | 9         | 0.15%   |
| 1-40           | 7         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1889      | 32.24%  |
| 101-120       | 1451      | 24.76%  |
| 121-160       | 1361      | 23.23%  |
| Unknown       | 464       | 7.92%   |
| 161-240       | 359       | 6.13%   |
| More than 240 | 169       | 2.88%   |
| 1-50          | 167       | 2.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4775      | 80.71%  |
| 2     | 764       | 12.91%  |
| 0     | 288       | 4.87%   |
| 3     | 80        | 1.35%   |
| 4     | 8         | 0.14%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2854      | 33.14%  |
| Realtek Semiconductor             | 2829      | 32.85%  |
| Qualcomm Atheros                  | 933       | 10.83%  |
| Broadcom                          | 622       | 7.22%   |
| Ralink Technology                 | 175       | 2.03%   |
| Marvell Technology Group          | 140       | 1.63%   |
| Broadcom Limited                  | 126       | 1.46%   |
| Nvidia                            | 111       | 1.29%   |
| Ralink                            | 100       | 1.16%   |
| TP-Link                           | 89        | 1.03%   |
| MediaTek                          | 42        | 0.49%   |
| Ericsson Business Mobile Networks | 35        | 0.41%   |
| Dell                              | 34        | 0.39%   |
| DisplayLink                       | 32        | 0.37%   |
| Microsoft                         | 31        | 0.36%   |
| ASIX Electronics                  | 28        | 0.33%   |
| Samsung Electronics               | 26        | 0.3%    |
| Belkin Components                 | 25        | 0.29%   |
| Qualcomm Atheros Communications   | 24        | 0.28%   |
| NetGear                           | 24        | 0.28%   |
| Edimax Technology                 | 22        | 0.26%   |
| Huawei Technologies               | 21        | 0.24%   |
| Lenovo                            | 17        | 0.2%    |
| Hewlett-Packard                   | 16        | 0.19%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.17%   |
| Aquantia                          | 15        | 0.17%   |
| Qualcomm                          | 14        | 0.16%   |
| ASUSTek Computer                  | 11        | 0.13%   |
| VIA Technologies                  | 10        | 0.12%   |
| JMicron Technology                | 9         | 0.1%    |
| Xiaomi                            | 8         | 0.09%   |
| Sierra Wireless                   | 8         | 0.09%   |
| Mellanox Technologies             | 8         | 0.09%   |
| D-Link                            | 8         | 0.09%   |
| Apple                             | 8         | 0.09%   |
| Microchip Technology              | 7         | 0.08%   |
| D-Link System                     | 7         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.06%   |
| Motorola PCS                      | 5         | 0.06%   |
| Micro Star International          | 5         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1863      | 18.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 355       | 3.49%   |
| Intel Wi-Fi 6 AX200                                               | 279       | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 250       | 2.46%   |
| Intel I211 Gigabit Network Connection                             | 201       | 1.98%   |
| Intel Wireless 8265 / 8275                                        | 165       | 1.62%   |
| Intel Wireless 7260                                               | 139       | 1.37%   |
| Intel Wireless 7265                                               | 137       | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 133       | 1.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 128       | 1.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 125       | 1.23%   |
| Realtek 802.11ac NIC                                              | 122       | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 115       | 1.13%   |
| Intel Ethernet Connection (2) I219-V                              | 104       | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 100       | 0.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 99        | 0.97%   |
| Intel Wireless 8260                                               | 97        | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 93        | 0.91%   |
| Intel Wireless 3165                                               | 93        | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 89        | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 82        | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 80        | 0.79%   |
| Intel Wireless-AC 9260                                            | 78        | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 77        | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 73        | 0.72%   |
| Intel Wi-Fi 6 AX201                                               | 66        | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 62        | 0.61%   |
| Intel 82577LM Gigabit Network Connection                          | 62        | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 61        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 61        | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 61        | 0.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 60        | 0.59%   |
| Ralink MT7601U Wireless Adapter                                   | 59        | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 58        | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                     | 55        | 0.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 52        | 0.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 52        | 0.51%   |
| Intel Ethernet Connection I218-LM                                 | 51        | 0.5%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 51        | 0.5%    |
| Intel Wireless 3160                                               | 50        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2027      | 43.37%  |
| Realtek Semiconductor             | 774       | 16.56%  |
| Qualcomm Atheros                  | 756       | 16.17%  |
| Broadcom                          | 385       | 8.24%   |
| Ralink Technology                 | 175       | 3.74%   |
| Ralink                            | 99        | 2.12%   |
| Broadcom Limited                  | 90        | 1.93%   |
| TP-Link                           | 83        | 1.78%   |
| MediaTek                          | 32        | 0.68%   |
| Microsoft                         | 30        | 0.64%   |
| Belkin Components                 | 25        | 0.53%   |
| Qualcomm Atheros Communications   | 24        | 0.51%   |
| NetGear                           | 24        | 0.51%   |
| Marvell Technology Group          | 23        | 0.49%   |
| Edimax Technology                 | 22        | 0.47%   |
| Dell                              | 19        | 0.41%   |
| ASUSTek Computer                  | 10        | 0.21%   |
| Sierra Wireless                   | 8         | 0.17%   |
| D-Link                            | 8         | 0.17%   |
| D-Link System                     | 6         | 0.13%   |
| Qualcomm                          | 5         | 0.11%   |
| Micro Star International          | 5         | 0.11%   |
| IMC Networks                      | 5         | 0.11%   |
| Ericsson Business Mobile Networks | 5         | 0.11%   |
| ZyDAS                             | 4         | 0.09%   |
| TRENDnet                          | 3         | 0.06%   |
| Sitecom Europe                    | 3         | 0.06%   |
| Linksys                           | 3         | 0.06%   |
| Gemtek                            | 3         | 0.06%   |
| Wilocity                          | 2         | 0.04%   |
| Wacom                             | 2         | 0.04%   |
| Fibocom                           | 2         | 0.04%   |
| Texas Instruments                 | 1         | 0.02%   |
| Senao                             | 1         | 0.02%   |
| Samsung Electronics               | 1         | 0.02%   |
| Philips (or NXP)                  | 1         | 0.02%   |
| InProComm                         | 1         | 0.02%   |
| Hewlett-Packard                   | 1         | 0.02%   |
| Fujitsu Siemens Computers         | 1         | 0.02%   |
| CyberTAN Technology               | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 279       | 5.92%   |
| Intel Wireless 8265 / 8275                                              | 165       | 3.5%    |
| Intel Wireless 7260                                                     | 139       | 2.95%   |
| Intel Wireless 7265                                                     | 137       | 2.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 133       | 2.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 125       | 2.65%   |
| Realtek 802.11ac NIC                                                    | 122       | 2.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 115       | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 100       | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 99        | 2.1%    |
| Intel Wireless 8260                                                     | 97        | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 93        | 1.97%   |
| Intel Wireless 3165                                                     | 93        | 1.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 80        | 1.7%    |
| Intel Wireless-AC 9260                                                  | 78        | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 77        | 1.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 73        | 1.55%   |
| Intel Wi-Fi 6 AX201                                                     | 66        | 1.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 61        | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 61        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 60        | 1.27%   |
| Ralink MT7601U Wireless Adapter                                         | 59        | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 58        | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 55        | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 52        | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 52        | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 51        | 1.08%   |
| Intel Wireless 3160                                                     | 50        | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 48        | 1.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 46        | 0.98%   |
| Ralink RT5370 Wireless Adapter                                          | 45        | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 45        | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 45        | 0.95%   |
| Intel WiFi Link 5100                                                    | 45        | 0.95%   |
| Intel Centrino Advanced-N 6200                                          | 40        | 0.85%   |
| Intel Centrino Ultimate-N 6300                                          | 39        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 38        | 0.81%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 37        | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 37        | 0.78%   |
| Intel Centrino Advanced-N 6235                                          | 37        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2496      | 47.84%  |
| Intel                                  | 1591      | 30.5%   |
| Broadcom                               | 331       | 6.34%   |
| Qualcomm Atheros                       | 259       | 4.96%   |
| Marvell Technology Group               | 117       | 2.24%   |
| Nvidia                                 | 111       | 2.13%   |
| Broadcom Limited                       | 39        | 0.75%   |
| DisplayLink                            | 32        | 0.61%   |
| ASIX Electronics                       | 28        | 0.54%   |
| Samsung Electronics                    | 25        | 0.48%   |
| Huawei Technologies                    | 17        | 0.33%   |
| Lenovo                                 | 16        | 0.31%   |
| Aquantia                               | 15        | 0.29%   |
| Silicon Integrated Systems [SiS]       | 14        | 0.27%   |
| VIA Technologies                       | 10        | 0.19%   |
| Qualcomm                               | 9         | 0.17%   |
| MediaTek                               | 9         | 0.17%   |
| JMicron Technology                     | 9         | 0.17%   |
| Xiaomi                                 | 8         | 0.15%   |
| Microchip Technology                   | 7         | 0.13%   |
| Mellanox Technologies                  | 7         | 0.13%   |
| TP-Link                                | 6         | 0.12%   |
| Apple                                  | 6         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 5         | 0.1%    |
| Motorola PCS                           | 5         | 0.1%    |
| Attansic Technology                    | 5         | 0.1%    |
| OPPO Electronics                       | 4         | 0.08%   |
| ICS Advent                             | 4         | 0.08%   |
| Google                                 | 4         | 0.08%   |
| T & A Mobile Phones                    | 3         | 0.06%   |
| Hewlett-Packard                        | 3         | 0.06%   |
| 3Com                                   | 3         | 0.06%   |
| Standard Microsystems                  | 2         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.04%   |
| QLogic                                 | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.04%   |
| HMD Global                             | 2         | 0.04%   |
| Emulex                                 | 2         | 0.04%   |
| SysKonnect                             | 1         | 0.02%   |
| Research In Motion                     | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1863      | 34.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 355       | 6.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 250       | 4.69%   |
| Intel I211 Gigabit Network Connection                             | 201       | 3.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 128       | 2.4%    |
| Intel Ethernet Connection (2) I219-V                              | 104       | 1.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 89        | 1.67%   |
| Intel Ethernet Connection I217-LM                                 | 82        | 1.54%   |
| Intel 82579V Gigabit Network Connection                           | 62        | 1.16%   |
| Intel 82577LM Gigabit Network Connection                          | 62        | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 61        | 1.14%   |
| Intel Ethernet Connection I218-LM                                 | 51        | 0.96%   |
| Nvidia MCP61 Ethernet                                             | 48        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 46        | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 45        | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 40        | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 39        | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 38        | 0.71%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 37        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 35        | 0.66%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 35        | 0.66%   |
| Intel Ethernet Controller I225-V                                  | 34        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 34        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 34        | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 34        | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 33        | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 31        | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 31        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 31        | 0.58%   |
| Intel 82567LM Gigabit Network Connection                          | 30        | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 30        | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 25        | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 24        | 0.45%   |
| Nvidia MCP79 Ethernet                                             | 24        | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 23        | 0.43%   |
| Intel I210 Gigabit Network Connection                             | 23        | 0.43%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 22        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4923      | 52.33%  |
| WiFi     | 4361      | 46.36%  |
| Modem    | 108       | 1.15%   |
| Unknown  | 15        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3393      | 56.87%  |
| Ethernet | 2570      | 43.08%  |
| Modem    | 2         | 0.03%   |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3082      | 53.02%  |
| 1     | 2385      | 41.03%  |
| 0     | 162       | 2.79%   |
| 3     | 128       | 2.2%    |
| 4     | 35        | 0.6%    |
| 5     | 16        | 0.28%   |
| 6     | 4         | 0.07%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5243      | 89.64%  |
| Yes  | 606       | 10.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1524      | 45.78%  |
| Cambridge Silicon Radio         | 270       | 8.11%   |
| Qualcomm Atheros Communications | 259       | 7.78%   |
| Realtek Semiconductor           | 246       | 7.39%   |
| Broadcom                        | 238       | 7.15%   |
| Apple                           | 162       | 4.87%   |
| IMC Networks                    | 107       | 3.21%   |
| Lite-On Technology              | 90        | 2.7%    |
| Foxconn / Hon Hai               | 77        | 2.31%   |
| Dell                            | 70        | 2.1%    |
| ASUSTek Computer                | 65        | 1.95%   |
| Toshiba                         | 41        | 1.23%   |
| Hewlett-Packard                 | 38        | 1.14%   |
| Marvell Semiconductor           | 23        | 0.69%   |
| Realtek                         | 19        | 0.57%   |
| Alps Electric                   | 17        | 0.51%   |
| Belkin Components               | 15        | 0.45%   |
| Foxconn International           | 13        | 0.39%   |
| Ralink                          | 9         | 0.27%   |
| Integrated System Solution      | 8         | 0.24%   |
| Askey Computer                  | 6         | 0.18%   |
| Taiyo Yuden                     | 5         | 0.15%   |
| Ralink Technology               | 5         | 0.15%   |
| TP-Link                         | 4         | 0.12%   |
| Logitech                        | 3         | 0.09%   |
| HTC (High Tech Computer)        | 3         | 0.09%   |
| Micro Star International        | 2         | 0.06%   |
| MediaTek                        | 2         | 0.06%   |
| Edimax Technology               | 2         | 0.06%   |
| Sitecom Europe                  | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Cypress Semiconductor           | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 637       | 19.13%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 270       | 8.11%   |
| Intel AX200 Bluetooth                               | 255       | 7.66%   |
| Intel AX201 Bluetooth                               | 200       | 6.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 171       | 5.14%   |
| Realtek Bluetooth Radio                             | 156       | 4.68%   |
| Qualcomm Atheros  Bluetooth Device                  | 95        | 2.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 69        | 2.07%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 68        | 2.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 66        | 1.98%   |
| Apple Bluetooth USB Host Controller                 | 64        | 1.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 63        | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 58        | 1.74%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 57        | 1.71%   |
| Apple Bluetooth Host Controller                     | 56        | 1.68%   |
| Foxconn / Hon Hai Bluetooth Device                  | 48        | 1.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 46        | 1.38%   |
| Intel AX210 Bluetooth                               | 43        | 1.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 37        | 1.11%   |
| Broadcom BCM2045B (BDC-2.1)                         | 35        | 1.05%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 29        | 0.87%   |
| IMC Networks Bluetooth Radio                        | 29        | 0.87%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 27        | 0.81%   |
| IMC Networks Bluetooth Device                       | 26        | 0.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.75%   |
| IMC Networks 802.11ac WLAN Adapter                  | 24        | 0.72%   |
| Dell DW375 Bluetooth Module                         | 24        | 0.72%   |
| Lite-On Bluetooth Device                            | 22        | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 22        | 0.66%   |
| Marvell Bluetooth and Wireless LAN Composite        | 21        | 0.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 21        | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.6%    |
| Realtek Bluetooth Radio                             | 19        | 0.57%   |
| Lite-On Atheros AR3012 Bluetooth                    | 18        | 0.54%   |
| Dell BCM20702A0 Bluetooth Module                    | 18        | 0.54%   |
| Apple Bluetooth HCI                                 | 18        | 0.54%   |
| Intel Bluetooth Device                              | 14        | 0.42%   |
| HP Broadcom 2070 Bluetooth Combo                    | 14        | 0.42%   |
| Broadcom BCM2045 Bluetooth                          | 14        | 0.42%   |
| Realtek RTL8723B Bluetooth                          | 13        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3997      | 50.2%   |
| AMD                                  | 1657      | 20.81%  |
| Nvidia                               | 1423      | 17.87%  |
| C-Media Electronics                  | 147       | 1.85%   |
| Creative Labs                        | 77        | 0.97%   |
| Logitech                             | 46        | 0.58%   |
| Texas Instruments                    | 45        | 0.57%   |
| JMTek                                | 30        | 0.38%   |
| Focusrite-Novation                   | 28        | 0.35%   |
| Creative Technology                  | 28        | 0.35%   |
| Realtek Semiconductor                | 24        | 0.3%    |
| SteelSeries ApS                      | 22        | 0.28%   |
| Plantronics                          | 22        | 0.28%   |
| GN Netcom                            | 22        | 0.28%   |
| Razer USA                            | 21        | 0.26%   |
| VIA Technologies                     | 17        | 0.21%   |
| Corsair                              | 17        | 0.21%   |
| Kingston Technology                  | 16        | 0.2%    |
| Blue Microphones                     | 16        | 0.2%    |
| Silicon Integrated Systems [SiS]     | 15        | 0.19%   |
| ASUSTek Computer                     | 14        | 0.18%   |
| Generalplus Technology               | 12        | 0.15%   |
| Dell                                 | 10        | 0.13%   |
| Apple                                | 10        | 0.13%   |
| Micro Star International             | 9         | 0.11%   |
| Lenovo                               | 9         | 0.11%   |
| Sennheiser Communications            | 8         | 0.1%    |
| ATI Technologies                     | 8         | 0.1%    |
| AKAI Professional M.I.               | 8         | 0.1%    |
| Tenx Technology                      | 7         | 0.09%   |
| Sony                                 | 7         | 0.09%   |
| GYROCOM C&C                          | 7         | 0.09%   |
| XMOS                                 | 6         | 0.08%   |
| Conexant Systems                     | 6         | 0.08%   |
| BEHRINGER International              | 6         | 0.08%   |
| Yamaha                               | 5         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.06%   |
| Samson Technologies                  | 5         | 0.06%   |
| Unknown                              | 4         | 0.05%   |
| Turtle Beach                         | 4         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 411       | 4.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 400       | 4.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 370       | 3.93%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 303       | 3.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 271       | 2.88%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 268       | 2.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 248       | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 245       | 2.6%    |
| AMD FCH Azalia Controller                                                                         | 217       | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 215       | 2.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 209       | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 208       | 2.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 153       | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 151       | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 149       | 1.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 146       | 1.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 136       | 1.44%   |
| Intel 8 Series HD Audio Controller                                                                | 131       | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 129       | 1.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 126       | 1.34%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 121       | 1.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 121       | 1.29%   |
| Intel Broadwell-U Audio Controller                                                                | 117       | 1.24%   |
| Intel 200 Series PCH HD Audio                                                                     | 116       | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 113       | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 105       | 1.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 101       | 1.07%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 100       | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 92        | 0.98%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 90        | 0.96%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 86        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 86        | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 85        | 0.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 80        | 0.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 77        | 0.82%   |
| Nvidia High Definition Audio Controller                                                           | 74        | 0.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 74        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 68        | 0.72%   |
| AMD High Definition Audio Controller                                                              | 68        | 0.72%   |
| Intel CM238 HD Audio Controller                                                                   | 66        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 591       | 19.54%  |
| SK hynix                     | 529       | 17.49%  |
| Corsair                      | 364       | 12.04%  |
| Unknown                      | 307       | 10.15%  |
| Micron Technology            | 303       | 10.02%  |
| Crucial                      | 296       | 9.79%   |
| Kingston                     | 269       | 8.9%    |
| Ramaxel Technology           | 46        | 1.52%   |
| Elpida                       | 39        | 1.29%   |
| Nanya Technology             | 38        | 1.26%   |
| A-DATA Technology            | 37        | 1.22%   |
| G.Skill                      | 29        | 0.96%   |
| Unknown (ABCD)               | 26        | 0.86%   |
| Team                         | 25        | 0.83%   |
| Patriot                      | 15        | 0.5%    |
| Transcend                    | 9         | 0.3%    |
| Qimonda                      | 8         | 0.26%   |
| ASint Technology             | 7         | 0.23%   |
| Unknown                      | 7         | 0.23%   |
| Hewlett-Packard              | 6         | 0.2%    |
| A Force                      | 6         | 0.2%    |
| GOODRAM                      | 5         | 0.17%   |
| Apacer                       | 4         | 0.13%   |
| Toshiba                      | 3         | 0.1%    |
| Timetec                      | 3         | 0.1%    |
| KLEVV                        | 3         | 0.1%    |
| Axiom                        | 3         | 0.1%    |
| V-Color                      | 2         | 0.07%   |
| Unknown (F301)               | 2         | 0.07%   |
| Unknown (0x0702)             | 2         | 0.07%   |
| Infineon                     | 2         | 0.07%   |
| GSkill                       | 2         | 0.07%   |
| Essencore                    | 2         | 0.07%   |
| CSX                          | 2         | 0.07%   |
| Avant                        | 2         | 0.07%   |
| ATP                          | 2         | 0.07%   |
| Wilk Elektronik              | 1         | 0.03%   |
| Uroad                        | 1         | 0.03%   |
| Unknown (0x4000000000000000) | 1         | 0.03%   |
| Unifosa                      | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 36        | 1.1%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 29        | 0.89%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 26        | 0.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 23        | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.55%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 17        | 0.52%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 17        | 0.52%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 16        | 0.49%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 15        | 0.46%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 14        | 0.43%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 14        | 0.43%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 14        | 0.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 13        | 0.4%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 13        | 0.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 13        | 0.4%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 13        | 0.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.4%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.4%    |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s       | 13        | 0.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 0.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 11        | 0.34%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 11        | 0.34%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 10        | 0.31%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 10        | 0.31%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.31%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 10        | 0.31%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 10        | 0.31%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s           | 10        | 0.31%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s  | 9         | 0.27%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.27%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 9         | 0.27%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 8         | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1173      | 44.69%  |
| DDR3    | 898       | 34.21%  |
| DDR2    | 156       | 5.94%   |
| LPDDR3  | 94        | 3.58%   |
| Unknown | 90        | 3.43%   |
| LPDDR4  | 89        | 3.39%   |
| SDRAM   | 85        | 3.24%   |
| DDR     | 23        | 0.88%   |
| DDR5    | 9         | 0.34%   |
| DRAM    | 8         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1354      | 52.32%  |
| DIMM         | 1024      | 39.57%  |
| Row Of Chips | 174       | 6.72%   |
| Chip         | 17        | 0.66%   |
| Unknown      | 10        | 0.39%   |
| RIMM         | 6         | 0.23%   |
| FB-DIMM      | 3         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1018      | 35.9%   |
| 4096   | 823       | 29.02%  |
| 16384  | 396       | 13.96%  |
| 2048   | 376       | 13.26%  |
| 1024   | 132       | 4.65%   |
| 32768  | 71        | 2.5%    |
| 512    | 16        | 0.56%   |
| 131072 | 1         | 0.04%   |
| 256    | 1         | 0.04%   |
| 16     | 1         | 0.04%   |
| 13     | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 598       | 20.92%  |
| 2667    | 391       | 13.68%  |
| 3200    | 300       | 10.49%  |
| 2400    | 232       | 8.11%   |
| 1333    | 226       | 7.9%    |
| 2133    | 153       | 5.35%   |
| 667     | 93        | 3.25%   |
| 3600    | 91        | 3.18%   |
| 1867    | 82        | 2.87%   |
| 800     | 74        | 2.59%   |
| 1334    | 67        | 2.34%   |
| Unknown | 53        | 1.85%   |
| 1067    | 40        | 1.4%    |
| 4267    | 37        | 1.29%   |
| 3400    | 33        | 1.15%   |
| 3266    | 32        | 1.12%   |
| 3000    | 31        | 1.08%   |
| 2048    | 27        | 0.94%   |
| 1066    | 27        | 0.94%   |
| 1866    | 19        | 0.66%   |
| 4199    | 18        | 0.63%   |
| 3733    | 18        | 0.63%   |
| 3466    | 18        | 0.63%   |
| 2800    | 17        | 0.59%   |
| 2666    | 17        | 0.59%   |
| 533     | 17        | 0.59%   |
| 2933    | 16        | 0.56%   |
| 400     | 15        | 0.52%   |
| 1800    | 13        | 0.45%   |
| 975     | 11        | 0.38%   |
| 4800    | 10        | 0.35%   |
| 49926   | 6         | 0.21%   |
| 8400    | 6         | 0.21%   |
| 4266    | 6         | 0.21%   |
| 1639    | 6         | 0.21%   |
| 3100    | 5         | 0.17%   |
| 3800    | 4         | 0.14%   |
| 3007    | 4         | 0.14%   |
| 2000    | 4         | 0.14%   |
| 2733    | 3         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 60        | 41.96%  |
| Canon                 | 24        | 16.78%  |
| Seiko Epson           | 14        | 9.79%   |
| Samsung Electronics   | 13        | 9.09%   |
| Brother Industries    | 11        | 7.69%   |
| Prolific Technology   | 5         | 3.5%    |
| STMicroelectronics    | 2         | 1.4%    |
| QinHeng Electronics   | 2         | 1.4%    |
| Oki Data              | 2         | 1.4%    |
| Lexmark International | 2         | 1.4%    |
| Kyocera               | 2         | 1.4%    |
| Dymo-CoStar           | 2         | 1.4%    |
| Seiko Instruments     | 1         | 0.7%    |
| Ricoh                 | 1         | 0.7%    |
| Dell                  | 1         | 0.7%    |
| Apple                 | 1         | 0.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                       | 6         | 4.14%   |
| Prolific PL2305 Parallel Port                             | 5         | 3.45%   |
| HP ENVY 5000 series                                       | 5         | 3.45%   |
| HP ENVY 4520 series                                       | 5         | 3.45%   |
| Canon PIXMA MG2500 Series                                 | 5         | 3.45%   |
| HP DeskJet 2620 All-in-One Printer                        | 4         | 2.76%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.38%   |
| Seiko Epson XP-243 245 247 Series                         | 2         | 1.38%   |
| Seiko Epson XP-202 203 206 Series                         | 2         | 1.38%   |
| Samsung ML-2250 Series                                    | 2         | 1.38%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.38%   |
| Samsung C43x Series                                       | 2         | 1.38%   |
| QinHeng CH340S                                            | 2         | 1.38%   |
| Oki Data USB Device                                       | 2         | 1.38%   |
| HP LaserJet 200 colorMFP M276nw                           | 2         | 1.38%   |
| HP Deskjet F2280 series                                   | 2         | 1.38%   |
| HP DeskJet 3630 series                                    | 2         | 1.38%   |
| HP Deskjet 2540 series                                    | 2         | 1.38%   |
| HP DeskJet 2130 series                                    | 2         | 1.38%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.38%   |
| HP Color LaserJet CP1215                                  | 2         | 1.38%   |
| Canon PIXMA MX920 Series                                  | 2         | 1.38%   |
| Canon PIXMA MP495                                         | 2         | 1.38%   |
| Canon MG5700 series                                       | 2         | 1.38%   |
| Canon LiDE 300                                            | 2         | 1.38%   |
| Canon iP7200 series                                       | 2         | 1.38%   |
| Brother HL-3140CW series                                  | 2         | 1.38%   |
| Brother DCP-7055 scanner/printer                          | 2         | 1.38%   |
| Seiko Instruments SLP-450 Driver                          | 1         | 0.69%   |
| Seiko Epson XP-211 214 216 Series                         | 1         | 0.69%   |
| Seiko Epson WF-3520 Series                                | 1         | 0.69%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.69%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.69%   |
| Seiko Epson L355 Series                                   | 1         | 0.69%   |
| Samsung SCX-4300 Series                                   | 1         | 0.69%   |
| Samsung ML-1865                                           | 1         | 0.69%   |
| Samsung ML-1510 Laser Printer                             | 1         | 0.69%   |
| Samsung M2020 Series                                      | 1         | 0.69%   |
| Samsung CLX-6260 Series                                   | 1         | 0.69%   |
| Samsung CLP-300 Series                                    | 1         | 0.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 21        | 60%     |
| Seiko Epson        | 8         | 22.86%  |
| Ultima Electronics | 2         | 5.71%   |
| Hewlett-Packard    | 2         | 5.71%   |
| Mustek Systems     | 1         | 2.86%   |
| AGFA-Gevaert NV    | 1         | 2.86%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30                                                         | 4         | 11.43%  |
| Canon CanoScan LiDE 220                                                               | 4         | 11.43%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3         | 8.57%   |
| Canon CanoScan LiDE 110                                                               | 3         | 8.57%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 5.71%   |
| Seiko Epson Scanner                                                                   | 2         | 5.71%   |
| HP ScanJet 5300c/5370c                                                                | 2         | 5.71%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 1         | 2.86%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.86%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 2.86%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 2.86%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 2.86%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 2.86%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1         | 2.86%   |
| Canon CanoScan LiDE 90                                                                | 1         | 2.86%   |
| Canon CanoScan LiDE 70                                                                | 1         | 2.86%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 2.86%   |
| Canon CanoScan LiDE 210                                                               | 1         | 2.86%   |
| Canon CanoScan LiDE 200                                                               | 1         | 2.86%   |
| Canon CanoScan LiDE 100                                                               | 1         | 2.86%   |
| Canon CanoScan 3000/3000F/3000ex                                                      | 1         | 2.86%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 1         | 2.86%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 699       | 21.41%  |
| Microdia                               | 344       | 10.54%  |
| Realtek Semiconductor                  | 266       | 8.15%   |
| Logitech                               | 225       | 6.89%   |
| IMC Networks                           | 218       | 6.68%   |
| Acer                                   | 189       | 5.79%   |
| Sunplus Innovation Technology          | 156       | 4.78%   |
| Apple                                  | 128       | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 118       | 3.61%   |
| Suyin                                  | 104       | 3.19%   |
| Quanta                                 | 104       | 3.19%   |
| Lite-On Technology                     | 72        | 2.21%   |
| Microsoft                              | 62        | 1.9%    |
| Syntek                                 | 60        | 1.84%   |
| Silicon Motion                         | 51        | 1.56%   |
| Alcor Micro                            | 48        | 1.47%   |
| Ricoh                                  | 42        | 1.29%   |
| Samsung Electronics                    | 39        | 1.19%   |
| Lenovo                                 | 31        | 0.95%   |
| Z-Star Microelectronics                | 24        | 0.74%   |
| ARC International                      | 22        | 0.67%   |
| Generalplus Technology                 | 21        | 0.64%   |
| GEMBIRD                                | 19        | 0.58%   |
| Luxvisions Innotech Limited            | 14        | 0.43%   |
| Creative Technology                    | 13        | 0.4%    |
| MacroSilicon                           | 12        | 0.37%   |
| ALi                                    | 12        | 0.37%   |
| Primax Electronics                     | 11        | 0.34%   |
| Aveo Technology                        | 10        | 0.31%   |
| Razer USA                              | 9         | 0.28%   |
| Sonix Technology                       | 8         | 0.25%   |
| Huawei Technologies                    | 8         | 0.25%   |
| Unknown                                | 7         | 0.21%   |
| Genesys Logic                          | 7         | 0.21%   |
| Sunplus Technology                     | 6         | 0.18%   |
| OmniVision Technologies                | 6         | 0.18%   |
| Importek                               | 6         | 0.18%   |
| Hewlett-Packard                        | 5         | 0.15%   |
| DigiTech                               | 5         | 0.15%   |
| Tobii Technology AB                    | 4         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 152       | 4.61%   |
| Chicony Integrated Camera                               | 114       | 3.46%   |
| Realtek Integrated_Webcam_HD                            | 85        | 2.58%   |
| Logitech HD Pro Webcam C920                             | 66        | 2%      |
| IMC Networks Integrated Camera                          | 66        | 2%      |
| Chicony HD WebCam                                       | 58        | 1.76%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 48        | 1.46%   |
| Sunplus Integrated_Webcam_HD                            | 47        | 1.43%   |
| Logitech Webcam C270                                    | 42        | 1.28%   |
| Chicony TOSHIBA Web Camera - HD                         | 42        | 1.28%   |
| Samsung Galaxy A5 (MTP)                                 | 39        | 1.18%   |
| Apple Built-in iSight                                   | 39        | 1.18%   |
| Apple FaceTime HD Camera (Built-in)                     | 38        | 1.15%   |
| Realtek USB Camera                                      | 37        | 1.12%   |
| Acer Integrated Camera                                  | 37        | 1.12%   |
| Microdia Integrated Webcam                              | 32        | 0.97%   |
| Chicony USB2.0 Camera                                   | 32        | 0.97%   |
| Lite-On Integrated Camera                               | 30        | 0.91%   |
| Microdia Webcam Vitade AF                               | 28        | 0.85%   |
| Chicony USB 2.0 Camera                                  | 28        | 0.85%   |
| Apple iPhone5/5C/5S/6                                   | 28        | 0.85%   |
| Chicony HP TrueVision HD Camera                         | 26        | 0.79%   |
| Microsoft LifeCam HD-3000                               | 23        | 0.7%    |
| Chicony HP TrueVision HD                                | 23        | 0.7%    |
| Microsoft LifeCam Cinema                                | 22        | 0.67%   |
| Chicony EasyCamera                                      | 22        | 0.67%   |
| ARC International Camera                                | 22        | 0.67%   |
| Acer Lenovo EasyCamera                                  | 22        | 0.67%   |
| Syntek Lenovo EasyCamera                                | 21        | 0.64%   |
| Apple FaceTime HD Camera                                | 21        | 0.64%   |
| Acer SunplusIT Integrated Camera                        | 21        | 0.64%   |
| Acer BisonCam,NB Pro                                    | 21        | 0.64%   |
| Chicony VGA Webcam                                      | 20        | 0.61%   |
| Chicony HP HD Camera                                    | 20        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 20        | 0.61%   |
| Syntek Integrated Camera                                | 17        | 0.52%   |
| Quanta HD User Facing                                   | 17        | 0.52%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 17        | 0.52%   |
| Chicony Integrated Camera (1280x720@30)                 | 17        | 0.52%   |
| Alcor Micro SHUNCCM2MP                                  | 17        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 180       | 31.91%  |
| Synaptics                  | 148       | 26.24%  |
| Shenzhen Goodix Technology | 85        | 15.07%  |
| AuthenTec                  | 41        | 7.27%   |
| Upek                       | 37        | 6.56%   |
| LighTuning Technology      | 27        | 4.79%   |
| Elan Microelectronics      | 27        | 4.79%   |
| STMicroelectronics         | 15        | 2.66%   |
| Samsung Electronics        | 2         | 0.35%   |
| HOLTEK                     | 1         | 0.18%   |
| Focal-systems.Corp         | 1         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 46        | 8.16%   |
| Unknown                                                                    | 45        | 7.98%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 36        | 6.38%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 34        | 6.03%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 34        | 6.03%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 30        | 5.32%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 3.9%    |
| Shenzhen Goodix Fingerprint Reader                                         | 20        | 3.55%   |
| Shenzhen Goodix FingerPrint                                                | 19        | 3.37%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 3.01%   |
| Synaptics  WBDI                                                            | 15        | 2.66%   |
| STMicroelectronics Fingerprint Reader                                      | 15        | 2.66%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 2.66%   |
| Validity Sensors VFS491                                                    | 13        | 2.3%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 2.3%    |
| Elan ELAN:Fingerprint                                                      | 13        | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 2.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 2.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 12        | 2.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.95%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 1.95%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.77%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.6%    |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 9         | 1.6%    |
| AuthenTec AES2810                                                          | 8         | 1.42%   |
| Synaptics WBDI Device                                                      | 7         | 1.24%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.24%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 6         | 1.06%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 1.06%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.06%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 0.89%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.89%   |
| Elan ELAN:ARM-M4                                                           | 5         | 0.89%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.89%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.89%   |
| AuthenTec AES1600                                                          | 5         | 0.89%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.71%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.71%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.53%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 141       | 52.03%  |
| Alcor Micro           | 60        | 22.14%  |
| Upek                  | 22        | 8.12%   |
| O2 Micro              | 18        | 6.64%   |
| Lenovo                | 17        | 6.27%   |
| Gemalto (was Gemplus) | 4         | 1.48%   |
| SCM Microsystems      | 3         | 1.11%   |
| Purism, SPC           | 1         | 0.37%   |
| OmniKey               | 1         | 0.37%   |
| Hewlett-Packard       | 1         | 0.37%   |
| Clay Logic            | 1         | 0.37%   |
| Chicony Electronics   | 1         | 0.37%   |
| Bit4id                | 1         | 0.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 62        | 22.88%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 56        | 20.66%  |
| Broadcom 5880                                                                | 33        | 12.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 27        | 9.96%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 8.12%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 6.27%   |
| Broadcom 58200                                                               | 17        | 6.27%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 13        | 4.8%    |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.85%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.48%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.11%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.74%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.74%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.37%   |
| Purism, SPC Librem Key                                                       | 1         | 0.37%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.37%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.37%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.37%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.37%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.37%   |
| Bit4id miniLector EVO                                                        | 1         | 0.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4212      | 71.09%  |
| 1     | 1359      | 22.94%  |
| 2     | 294       | 4.96%   |
| 3     | 41        | 0.69%   |
| 4     | 11        | 0.19%   |
| 5     | 3         | 0.05%   |
| 7     | 2         | 0.03%   |
| 6     | 2         | 0.03%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 548       | 26.52%  |
| Graphics card            | 393       | 19.02%  |
| Net/wireless             | 350       | 16.94%  |
| Chipcard                 | 252       | 12.2%   |
| Multimedia controller    | 124       | 6%      |
| Communication controller | 101       | 4.89%   |
| Unassigned class         | 47        | 2.27%   |
| Sound                    | 42        | 2.03%   |
| Camera                   | 42        | 2.03%   |
| Bluetooth                | 39        | 1.89%   |
| Storage                  | 35        | 1.69%   |
| Net/ethernet             | 19        | 0.92%   |
| Modem                    | 16        | 0.77%   |
| Card reader              | 16        | 0.77%   |
| Network                  | 13        | 0.63%   |
| Flash memory             | 8         | 0.39%   |
| Storage/raid             | 7         | 0.34%   |
| Firewire controller      | 5         | 0.24%   |
| Storage/ide              | 4         | 0.19%   |
| Dvb card                 | 3         | 0.15%   |
| Storage/nvme             | 2         | 0.1%    |

