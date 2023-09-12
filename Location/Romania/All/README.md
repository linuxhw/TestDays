Linux in Romania - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Romania.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Romania/Desktop/README.md) and [notebooks](/Location/Romania/Notebook/README.md).

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

Total: 2691

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | EQ45LM                      | Desktop     | [22af76a0b6](https://linux-hardware.org/?probe=22af76a0b6) | Sep 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7263435dde](https://linux-hardware.org/?probe=7263435dde) | Sep 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [f66ec50e55](https://linux-hardware.org/?probe=f66ec50e55) | Sep 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [9a31047350](https://linux-hardware.org/?probe=9a31047350) | Sep 05, 2023 |
| Acer          | Nitro AN515-41              | Notebook    | [8d55fa5be4](https://linux-hardware.org/?probe=8d55fa5be4) | Sep 03, 2023 |
| HP            | 15                          | Notebook    | [db9d960b39](https://linux-hardware.org/?probe=db9d960b39) | Sep 03, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [66df65e0f0](https://linux-hardware.org/?probe=66df65e0f0) | Sep 02, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [d3c3b72e39](https://linux-hardware.org/?probe=d3c3b72e39) | Sep 01, 2023 |
| Acer          | TMP645-M                    | Notebook    | [17838ce9b0](https://linux-hardware.org/?probe=17838ce9b0) | Aug 30, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [ca4dd5a11e](https://linux-hardware.org/?probe=ca4dd5a11e) | Aug 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d036282290](https://linux-hardware.org/?probe=d036282290) | Aug 29, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [b866599fbc](https://linux-hardware.org/?probe=b866599fbc) | Aug 29, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [90b8d2cb66](https://linux-hardware.org/?probe=90b8d2cb66) | Aug 28, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [a8a97f9555](https://linux-hardware.org/?probe=a8a97f9555) | Aug 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8169effdbe](https://linux-hardware.org/?probe=8169effdbe) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [dd4626de1b](https://linux-hardware.org/?probe=dd4626de1b) | Aug 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [78a62eeefe](https://linux-hardware.org/?probe=78a62eeefe) | Aug 26, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [db9336b4db](https://linux-hardware.org/?probe=db9336b4db) | Aug 26, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [7aca2d97c0](https://linux-hardware.org/?probe=7aca2d97c0) | Aug 25, 2023 |
| Acer          | EQ45LM                      | Desktop     | [aa8ea529f7](https://linux-hardware.org/?probe=aa8ea529f7) | Aug 24, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [05eae6c877](https://linux-hardware.org/?probe=05eae6c877) | Aug 22, 2023 |
| ASRock        | 890GX Pro3                  | Desktop     | [c36b43c52a](https://linux-hardware.org/?probe=c36b43c52a) | Aug 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b3f1d927a1](https://linux-hardware.org/?probe=b3f1d927a1) | Aug 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d7b6d2a997](https://linux-hardware.org/?probe=d7b6d2a997) | Aug 21, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d7805c8232](https://linux-hardware.org/?probe=d7805c8232) | Aug 19, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [8946b925ea](https://linux-hardware.org/?probe=8946b925ea) | Aug 18, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [8478931432](https://linux-hardware.org/?probe=8478931432) | Aug 17, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [3fa65d407a](https://linux-hardware.org/?probe=3fa65d407a) | Aug 17, 2023 |
| HP            | Compaq 6710b (FG040EC#AB... | Notebook    | [a0cd8c1b40](https://linux-hardware.org/?probe=a0cd8c1b40) | Aug 16, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [8bc67959d1](https://linux-hardware.org/?probe=8bc67959d1) | Aug 16, 2023 |
| ASUSTek       | GL552JX                     | Notebook    | [9594a231bd](https://linux-hardware.org/?probe=9594a231bd) | Aug 16, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [f0d90b715d](https://linux-hardware.org/?probe=f0d90b715d) | Aug 15, 2023 |
| Gigabyte      | Z270M-D3H-CF                | Desktop     | [74d96ec17a](https://linux-hardware.org/?probe=74d96ec17a) | Aug 15, 2023 |
| Gigabyte      | Z270M-D3H-CF                | Desktop     | [8e4f3bf14e](https://linux-hardware.org/?probe=8e4f3bf14e) | Aug 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [18d3d9a7c1](https://linux-hardware.org/?probe=18d3d9a7c1) | Aug 14, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [f0f6b13bf3](https://linux-hardware.org/?probe=f0f6b13bf3) | Aug 13, 2023 |
| Allview       | Allbook H                   | Notebook    | [1a8e5e7f8f](https://linux-hardware.org/?probe=1a8e5e7f8f) | Aug 13, 2023 |
| Intel         | NUC7i5BNB J31144-303        | Mini pc     | [144f77980e](https://linux-hardware.org/?probe=144f77980e) | Aug 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [7fd3205fde](https://linux-hardware.org/?probe=7fd3205fde) | Aug 11, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [ce593ff6c7](https://linux-hardware.org/?probe=ce593ff6c7) | Aug 07, 2023 |
| Acer          | AO756                       | Notebook    | [60475c9d52](https://linux-hardware.org/?probe=60475c9d52) | Aug 06, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| WEIGO         | CDA-141AU                   | Notebook    | [35c705bd70](https://linux-hardware.org/?probe=35c705bd70) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [66d6565a06](https://linux-hardware.org/?probe=66d6565a06) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [70aa79986f](https://linux-hardware.org/?probe=70aa79986f) | Aug 05, 2023 |
| Acer          | EQ45LM                      | Desktop     | [b9be16315e](https://linux-hardware.org/?probe=b9be16315e) | Aug 05, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [cc0ea700cc](https://linux-hardware.org/?probe=cc0ea700cc) | Aug 04, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a7b2a3fcc](https://linux-hardware.org/?probe=0a7b2a3fcc) | Aug 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [9171e8e6b9](https://linux-hardware.org/?probe=9171e8e6b9) | Aug 03, 2023 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [c279d0ba16](https://linux-hardware.org/?probe=c279d0ba16) | Aug 02, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [8de1f944a7](https://linux-hardware.org/?probe=8de1f944a7) | Jul 30, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | Desktop     | [9cc0db1a3d](https://linux-hardware.org/?probe=9cc0db1a3d) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [d1bf55b135](https://linux-hardware.org/?probe=d1bf55b135) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ea8a893b11](https://linux-hardware.org/?probe=ea8a893b11) | Jul 29, 2023 |
| Lenovo        | ThinkPad W541 20EFS00N00    | Notebook    | [c9f80b56fc](https://linux-hardware.org/?probe=c9f80b56fc) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [9f04167710](https://linux-hardware.org/?probe=9f04167710) | Jul 27, 2023 |
| Acer          | EQ45LM                      | Desktop     | [29e2f587cd](https://linux-hardware.org/?probe=29e2f587cd) | Jul 26, 2023 |
| Acer          | EQ45LM                      | Desktop     | [37f6c76c11](https://linux-hardware.org/?probe=37f6c76c11) | Jul 25, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [798cadd754](https://linux-hardware.org/?probe=798cadd754) | Jul 25, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | Desktop     | [6417b2e0e3](https://linux-hardware.org/?probe=6417b2e0e3) | Jul 24, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [e9a58d14e7](https://linux-hardware.org/?probe=e9a58d14e7) | Jul 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [93857a3b66](https://linux-hardware.org/?probe=93857a3b66) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [dac4434339](https://linux-hardware.org/?probe=dac4434339) | Jul 18, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [3dfd41fda9](https://linux-hardware.org/?probe=3dfd41fda9) | Jul 17, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [c5bee4d8fe](https://linux-hardware.org/?probe=c5bee4d8fe) | Jul 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3057a60e0f](https://linux-hardware.org/?probe=3057a60e0f) | Jul 17, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [501969ed00](https://linux-hardware.org/?probe=501969ed00) | Jul 15, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [85d4919b9c](https://linux-hardware.org/?probe=85d4919b9c) | Jul 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [052b5c1741](https://linux-hardware.org/?probe=052b5c1741) | Jul 12, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [9fc68063e3](https://linux-hardware.org/?probe=9fc68063e3) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [f35543549c](https://linux-hardware.org/?probe=f35543549c) | Jul 11, 2023 |
| Unknown       | HP Chromebook 14            | Notebook    | [63b183aa51](https://linux-hardware.org/?probe=63b183aa51) | Jul 11, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [0ae95a7985](https://linux-hardware.org/?probe=0ae95a7985) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [3cad86057a](https://linux-hardware.org/?probe=3cad86057a) | Jul 09, 2023 |
| Acer          | EQ45LM                      | Desktop     | [3cafc83ffb](https://linux-hardware.org/?probe=3cafc83ffb) | Jul 08, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [a29509646a](https://linux-hardware.org/?probe=a29509646a) | Jul 08, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [952e97925b](https://linux-hardware.org/?probe=952e97925b) | Jul 08, 2023 |
| Dell          | Latitude 3500               | Notebook    | [38a0d6b099](https://linux-hardware.org/?probe=38a0d6b099) | Jul 08, 2023 |
| Dell          | Studio 1749                 | Notebook    | [fe1e5d7b8f](https://linux-hardware.org/?probe=fe1e5d7b8f) | Jul 05, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [79d631563a](https://linux-hardware.org/?probe=79d631563a) | Jul 01, 2023 |
| Acer          | EQ45LM                      | Desktop     | [30781f8f1b](https://linux-hardware.org/?probe=30781f8f1b) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8862b2d8db](https://linux-hardware.org/?probe=8862b2d8db) | Jun 25, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [dc2aebbc48](https://linux-hardware.org/?probe=dc2aebbc48) | Jun 24, 2023 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | Notebook    | [a74b5c2880](https://linux-hardware.org/?probe=a74b5c2880) | Jun 24, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [f0ab10725e](https://linux-hardware.org/?probe=f0ab10725e) | Jun 23, 2023 |
| Acer          | Aspire A315-58G             | Notebook    | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Acer          | Swift SF314-52G             | Notebook    | [4eab971a60](https://linux-hardware.org/?probe=4eab971a60) | Jun 21, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [530f6272c9](https://linux-hardware.org/?probe=530f6272c9) | Jun 20, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [928b30815b](https://linux-hardware.org/?probe=928b30815b) | Jun 18, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [c6a929a9ec](https://linux-hardware.org/?probe=c6a929a9ec) | Jun 17, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [d72b8e616f](https://linux-hardware.org/?probe=d72b8e616f) | Jun 17, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [0ef00ccccc](https://linux-hardware.org/?probe=0ef00ccccc) | Jun 16, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [f1f16d8add](https://linux-hardware.org/?probe=f1f16d8add) | Jun 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [2346d706e3](https://linux-hardware.org/?probe=2346d706e3) | Jun 15, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [7747deeb57](https://linux-hardware.org/?probe=7747deeb57) | Jun 15, 2023 |
| HP            | 81B3                        | Desktop     | [9ba98d3c27](https://linux-hardware.org/?probe=9ba98d3c27) | Jun 14, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [1c62ecb77d](https://linux-hardware.org/?probe=1c62ecb77d) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e073b99b63](https://linux-hardware.org/?probe=e073b99b63) | Jun 13, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [e722fda49e](https://linux-hardware.org/?probe=e722fda49e) | Jun 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [0f5b161a60](https://linux-hardware.org/?probe=0f5b161a60) | Jun 13, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [9e763f2e63](https://linux-hardware.org/?probe=9e763f2e63) | Jun 12, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [d567ae409c](https://linux-hardware.org/?probe=d567ae409c) | Jun 12, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [b6a626c812](https://linux-hardware.org/?probe=b6a626c812) | Jun 10, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [b9eb9677f5](https://linux-hardware.org/?probe=b9eb9677f5) | Jun 10, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [fadb7a6aa8](https://linux-hardware.org/?probe=fadb7a6aa8) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b7ab29fbb5](https://linux-hardware.org/?probe=b7ab29fbb5) | Jun 06, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [05530e670e](https://linux-hardware.org/?probe=05530e670e) | Jun 06, 2023 |
| Acer          | EQ45LM                      | Desktop     | [73f7a3078f](https://linux-hardware.org/?probe=73f7a3078f) | Jun 06, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ea07821e39](https://linux-hardware.org/?probe=ea07821e39) | Jun 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [1285aacf1b](https://linux-hardware.org/?probe=1285aacf1b) | Jun 04, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [7cd25ddbda](https://linux-hardware.org/?probe=7cd25ddbda) | Jun 04, 2023 |
| ASUSTek       | Zenbook UM5401RA_RM5401R... | Notebook    | [763a52f3e8](https://linux-hardware.org/?probe=763a52f3e8) | Jun 03, 2023 |
| HP            | ENVY 17                     | Notebook    | [79fd438f05](https://linux-hardware.org/?probe=79fd438f05) | Jun 03, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [055866f703](https://linux-hardware.org/?probe=055866f703) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [dc0e29f0bb](https://linux-hardware.org/?probe=dc0e29f0bb) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [693005f5b4](https://linux-hardware.org/?probe=693005f5b4) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [1f18cef2df](https://linux-hardware.org/?probe=1f18cef2df) | Jun 01, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [7ae3edd73e](https://linux-hardware.org/?probe=7ae3edd73e) | Jun 01, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [f93dd394e8](https://linux-hardware.org/?probe=f93dd394e8) | May 31, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [6bec5a03df](https://linux-hardware.org/?probe=6bec5a03df) | May 30, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [3ecf79af69](https://linux-hardware.org/?probe=3ecf79af69) | May 29, 2023 |
| Dell          | Latitude E6440              | Notebook    | [821e3e3246](https://linux-hardware.org/?probe=821e3e3246) | May 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [acee298918](https://linux-hardware.org/?probe=acee298918) | May 26, 2023 |
| Acer          | EQ45LM                      | Desktop     | [a49c4c8438](https://linux-hardware.org/?probe=a49c4c8438) | May 26, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [c8c9f63237](https://linux-hardware.org/?probe=c8c9f63237) | May 25, 2023 |
| Dell          | G15 5510                    | Notebook    | [325fcf6e78](https://linux-hardware.org/?probe=325fcf6e78) | May 25, 2023 |
| HP            | ProBook 6440b               | Notebook    | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [7a892801c0](https://linux-hardware.org/?probe=7a892801c0) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [61b85cdced](https://linux-hardware.org/?probe=61b85cdced) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [b167237d46](https://linux-hardware.org/?probe=b167237d46) | May 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [117db8031d](https://linux-hardware.org/?probe=117db8031d) | May 24, 2023 |
| Dell          | Precision 7540              | Notebook    | [65605ee5e8](https://linux-hardware.org/?probe=65605ee5e8) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [a1e2fa6222](https://linux-hardware.org/?probe=a1e2fa6222) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [cb3e4d2c2b](https://linux-hardware.org/?probe=cb3e4d2c2b) | May 24, 2023 |
| Allview       | Allbook H                   | Notebook    | [8b0c0a3436](https://linux-hardware.org/?probe=8b0c0a3436) | May 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [64ceddcdd4](https://linux-hardware.org/?probe=64ceddcdd4) | May 24, 2023 |
| Dell          | G15 5510                    | Notebook    | [730985e467](https://linux-hardware.org/?probe=730985e467) | May 24, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [319f4883aa](https://linux-hardware.org/?probe=319f4883aa) | May 22, 2023 |
| HP            | 805D                        | Desktop     | [2ac4992bcd](https://linux-hardware.org/?probe=2ac4992bcd) | May 22, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [5309c41b94](https://linux-hardware.org/?probe=5309c41b94) | May 21, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b8ed6a8b77](https://linux-hardware.org/?probe=b8ed6a8b77) | May 18, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ceeff309eb](https://linux-hardware.org/?probe=ceeff309eb) | May 18, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [00685614c4](https://linux-hardware.org/?probe=00685614c4) | May 16, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [fc6d34934a](https://linux-hardware.org/?probe=fc6d34934a) | May 14, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [cbd408a1a6](https://linux-hardware.org/?probe=cbd408a1a6) | May 13, 2023 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [f1884eebc6](https://linux-hardware.org/?probe=f1884eebc6) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| Acer          | Extensa 5220                | Notebook    | [935b52f12c](https://linux-hardware.org/?probe=935b52f12c) | May 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [af96be2497](https://linux-hardware.org/?probe=af96be2497) | May 11, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [5921d78ceb](https://linux-hardware.org/?probe=5921d78ceb) | May 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5f4146c326](https://linux-hardware.org/?probe=5f4146c326) | May 10, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [8f9a64c245](https://linux-hardware.org/?probe=8f9a64c245) | May 08, 2023 |
| Dell          | Inspiron 11-3162            | Notebook    | [62813124bb](https://linux-hardware.org/?probe=62813124bb) | May 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [a312f0545f](https://linux-hardware.org/?probe=a312f0545f) | May 07, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [2a321db63e](https://linux-hardware.org/?probe=2a321db63e) | May 07, 2023 |
| Dell          | 0YXT71 A03                  | Desktop     | [b8281f77a3](https://linux-hardware.org/?probe=b8281f77a3) | May 07, 2023 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [f86e67c005](https://linux-hardware.org/?probe=f86e67c005) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [85648a82df](https://linux-hardware.org/?probe=85648a82df) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d905babc43](https://linux-hardware.org/?probe=d905babc43) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [bb7835495e](https://linux-hardware.org/?probe=bb7835495e) | May 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [af9c3172bc](https://linux-hardware.org/?probe=af9c3172bc) | May 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [862ef64565](https://linux-hardware.org/?probe=862ef64565) | May 05, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [425ecbf896](https://linux-hardware.org/?probe=425ecbf896) | May 04, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [7a04e30859](https://linux-hardware.org/?probe=7a04e30859) | May 03, 2023 |
| HP            | Notebook                    | Notebook    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [7c56fae21c](https://linux-hardware.org/?probe=7c56fae21c) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3b04b16c3e](https://linux-hardware.org/?probe=3b04b16c3e) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1234a4cf5a](https://linux-hardware.org/?probe=1234a4cf5a) | May 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e055c16455](https://linux-hardware.org/?probe=e055c16455) | May 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5101f4e19d](https://linux-hardware.org/?probe=5101f4e19d) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [2a4cf994ac](https://linux-hardware.org/?probe=2a4cf994ac) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ed2a323b49](https://linux-hardware.org/?probe=ed2a323b49) | May 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [4607549f5a](https://linux-hardware.org/?probe=4607549f5a) | May 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [754b22a59c](https://linux-hardware.org/?probe=754b22a59c) | May 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d1b974c33a](https://linux-hardware.org/?probe=d1b974c33a) | May 01, 2023 |
| Lenovo        | 36DB No DPK                 | All in one  | [01458c55a9](https://linux-hardware.org/?probe=01458c55a9) | Apr 28, 2023 |
| Lenovo        | 36DB No DPK                 | All in one  | [df53e54c69](https://linux-hardware.org/?probe=df53e54c69) | Apr 28, 2023 |
| Acer          | Aspire 5110                 | Notebook    | [b43b059257](https://linux-hardware.org/?probe=b43b059257) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2beb48be05](https://linux-hardware.org/?probe=2beb48be05) | Apr 27, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [f58ab8b9c4](https://linux-hardware.org/?probe=f58ab8b9c4) | Apr 27, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| ASUSTek       | K53SM                       | Notebook    | [92ac292547](https://linux-hardware.org/?probe=92ac292547) | Apr 24, 2023 |
| Acer          | Aspire V5-122P              | Notebook    | [baf567c71f](https://linux-hardware.org/?probe=baf567c71f) | Apr 23, 2023 |
| Samsung       | 730QDA                      | Convertible | [a6fef02901](https://linux-hardware.org/?probe=a6fef02901) | Apr 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [481c5a9169](https://linux-hardware.org/?probe=481c5a9169) | Apr 23, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [6e52b3ea77](https://linux-hardware.org/?probe=6e52b3ea77) | Apr 22, 2023 |
| Allview       | Allbook J                   | Notebook    | [96a3d7d3ef](https://linux-hardware.org/?probe=96a3d7d3ef) | Apr 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [1127dfa79c](https://linux-hardware.org/?probe=1127dfa79c) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [3f01c5df6e](https://linux-hardware.org/?probe=3f01c5df6e) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [a5ef39681b](https://linux-hardware.org/?probe=a5ef39681b) | Apr 21, 2023 |
| Allview       | Allbook J                   | Notebook    | [4ff8627338](https://linux-hardware.org/?probe=4ff8627338) | Apr 18, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c7ca0e9fd1](https://linux-hardware.org/?probe=c7ca0e9fd1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [0c4578a674](https://linux-hardware.org/?probe=0c4578a674) | Apr 14, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [356ff49c7c](https://linux-hardware.org/?probe=356ff49c7c) | Apr 13, 2023 |
| HP            | 1495                        | Desktop     | [569a6f28f4](https://linux-hardware.org/?probe=569a6f28f4) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [da4c241466](https://linux-hardware.org/?probe=da4c241466) | Apr 10, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [5244868737](https://linux-hardware.org/?probe=5244868737) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | Notebook    | [ae8c333d72](https://linux-hardware.org/?probe=ae8c333d72) | Apr 07, 2023 |
| ASUSTek       | X55U                        | Notebook    | [0abf7df439](https://linux-hardware.org/?probe=0abf7df439) | Apr 06, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [6b554016fe](https://linux-hardware.org/?probe=6b554016fe) | Apr 03, 2023 |
| ASUSTek       | J1900I-C                    | Desktop     | [0fbd47b12e](https://linux-hardware.org/?probe=0fbd47b12e) | Apr 02, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [90796fbad9](https://linux-hardware.org/?probe=90796fbad9) | Mar 31, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [5d5862d22a](https://linux-hardware.org/?probe=5d5862d22a) | Mar 31, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [5be11a9a6e](https://linux-hardware.org/?probe=5be11a9a6e) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [bfa850ddad](https://linux-hardware.org/?probe=bfa850ddad) | Mar 29, 2023 |
| HP            | 3047h                       | Desktop     | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [577947c9d3](https://linux-hardware.org/?probe=577947c9d3) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [08e7388619](https://linux-hardware.org/?probe=08e7388619) | Mar 27, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [bef27b5a10](https://linux-hardware.org/?probe=bef27b5a10) | Mar 26, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [daac2899b2](https://linux-hardware.org/?probe=daac2899b2) | Mar 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [84af25ca8c](https://linux-hardware.org/?probe=84af25ca8c) | Mar 26, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [f99591fe95](https://linux-hardware.org/?probe=f99591fe95) | Mar 26, 2023 |
| Acer          | V5-131                      | Notebook    | [f35bd55401](https://linux-hardware.org/?probe=f35bd55401) | Mar 26, 2023 |
| Acer          | TravelMate 5744             | Notebook    | [3ad8bf7639](https://linux-hardware.org/?probe=3ad8bf7639) | Mar 22, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [c5b2997e80](https://linux-hardware.org/?probe=c5b2997e80) | Mar 21, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [4a4c44f0dd](https://linux-hardware.org/?probe=4a4c44f0dd) | Mar 18, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ceb794a09f](https://linux-hardware.org/?probe=ceb794a09f) | Mar 17, 2023 |
| ASUSTek       | P9X79 WS                    | Desktop     | [29e03bb7ce](https://linux-hardware.org/?probe=29e03bb7ce) | Mar 17, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| HP            | ZBook 15                    | Notebook    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [8912f590e3](https://linux-hardware.org/?probe=8912f590e3) | Mar 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [d56d3939f9](https://linux-hardware.org/?probe=d56d3939f9) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [abebd8a5c2](https://linux-hardware.org/?probe=abebd8a5c2) | Mar 11, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | Notebook    | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a3a158ccf2](https://linux-hardware.org/?probe=a3a158ccf2) | Mar 08, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [72d0284bdd](https://linux-hardware.org/?probe=72d0284bdd) | Mar 05, 2023 |
| HP            | Compaq 6735b                | Notebook    | [8c664182a2](https://linux-hardware.org/?probe=8c664182a2) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [9fba7bceb7](https://linux-hardware.org/?probe=9fba7bceb7) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2dea6717ae](https://linux-hardware.org/?probe=2dea6717ae) | Mar 02, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| ASUSTek       | FX503VD                     | Notebook    | [46954919f7](https://linux-hardware.org/?probe=46954919f7) | Feb 27, 2023 |
| ASUSTek       | FX503VD                     | Notebook    | [60e1742e7e](https://linux-hardware.org/?probe=60e1742e7e) | Feb 27, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [ea8bb4c0e4](https://linux-hardware.org/?probe=ea8bb4c0e4) | Feb 27, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [edf748dbbb](https://linux-hardware.org/?probe=edf748dbbb) | Feb 26, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [22cf774ac0](https://linux-hardware.org/?probe=22cf774ac0) | Feb 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [46aedb5579](https://linux-hardware.org/?probe=46aedb5579) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | Notebook    | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [0f251d6bbf](https://linux-hardware.org/?probe=0f251d6bbf) | Feb 23, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [bf6718f1d0](https://linux-hardware.org/?probe=bf6718f1d0) | Feb 22, 2023 |
| Dell          | Latitude 5580               | Notebook    | [91567566be](https://linux-hardware.org/?probe=91567566be) | Feb 21, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [e8963c4e59](https://linux-hardware.org/?probe=e8963c4e59) | Feb 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [c205da78c9](https://linux-hardware.org/?probe=c205da78c9) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [8942075e7b](https://linux-hardware.org/?probe=8942075e7b) | Feb 18, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [dc294f018e](https://linux-hardware.org/?probe=dc294f018e) | Feb 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [e614d24613](https://linux-hardware.org/?probe=e614d24613) | Feb 17, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [f36e84dcaf](https://linux-hardware.org/?probe=f36e84dcaf) | Feb 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [684445aeab](https://linux-hardware.org/?probe=684445aeab) | Feb 16, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| HP            | 0AA8h                       | Desktop     | [e7bbc5903b](https://linux-hardware.org/?probe=e7bbc5903b) | Feb 15, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [6047c68386](https://linux-hardware.org/?probe=6047c68386) | Feb 11, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [199c8805ee](https://linux-hardware.org/?probe=199c8805ee) | Feb 10, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [1360d3227f](https://linux-hardware.org/?probe=1360d3227f) | Feb 10, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [fa2a1dba2d](https://linux-hardware.org/?probe=fa2a1dba2d) | Feb 09, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [e7b8536ad4](https://linux-hardware.org/?probe=e7b8536ad4) | Feb 09, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [a2729c9880](https://linux-hardware.org/?probe=a2729c9880) | Feb 08, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [6161d6b31d](https://linux-hardware.org/?probe=6161d6b31d) | Feb 08, 2023 |
| HP            | 1494                        | Desktop     | [ba7c61bf23](https://linux-hardware.org/?probe=ba7c61bf23) | Feb 07, 2023 |
| HP            | 1494                        | Desktop     | [a582a0d6c7](https://linux-hardware.org/?probe=a582a0d6c7) | Feb 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0c14eb04ce](https://linux-hardware.org/?probe=0c14eb04ce) | Feb 06, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [2f47f8d73d](https://linux-hardware.org/?probe=2f47f8d73d) | Feb 05, 2023 |
| Toshiba       | Satellite C55-A-168         | Notebook    | [e92c2babc4](https://linux-hardware.org/?probe=e92c2babc4) | Feb 05, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [c4c5c0888a](https://linux-hardware.org/?probe=c4c5c0888a) | Feb 04, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [4ed27fe851](https://linux-hardware.org/?probe=4ed27fe851) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [a2ff80e7dd](https://linux-hardware.org/?probe=a2ff80e7dd) | Feb 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [2791787281](https://linux-hardware.org/?probe=2791787281) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [e2ad5b033f](https://linux-hardware.org/?probe=e2ad5b033f) | Jan 31, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [6c3dd54582](https://linux-hardware.org/?probe=6c3dd54582) | Jan 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| ASRock        | J4125M                      | Desktop     | [535c1b6821](https://linux-hardware.org/?probe=535c1b6821) | Jan 30, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [da2056876e](https://linux-hardware.org/?probe=da2056876e) | Jan 29, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [b7377ee894](https://linux-hardware.org/?probe=b7377ee894) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [b8891cfc9b](https://linux-hardware.org/?probe=b8891cfc9b) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [fb0a23c0e6](https://linux-hardware.org/?probe=fb0a23c0e6) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [24b6a47ebb](https://linux-hardware.org/?probe=24b6a47ebb) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [5d58c53672](https://linux-hardware.org/?probe=5d58c53672) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [b352f0af44](https://linux-hardware.org/?probe=b352f0af44) | Jan 27, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3e65f42529](https://linux-hardware.org/?probe=3e65f42529) | Jan 26, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [e030231e2c](https://linux-hardware.org/?probe=e030231e2c) | Jan 25, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [5f584c387e](https://linux-hardware.org/?probe=5f584c387e) | Jan 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [5b2fd24ed7](https://linux-hardware.org/?probe=5b2fd24ed7) | Jan 24, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [ac4fa9fd5f](https://linux-hardware.org/?probe=ac4fa9fd5f) | Jan 23, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [36d99ec94e](https://linux-hardware.org/?probe=36d99ec94e) | Jan 22, 2023 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [cd23d81f65](https://linux-hardware.org/?probe=cd23d81f65) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [adbc469f95](https://linux-hardware.org/?probe=adbc469f95) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [9249ff32b3](https://linux-hardware.org/?probe=9249ff32b3) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [a7ba34fed5](https://linux-hardware.org/?probe=a7ba34fed5) | Jan 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [de713cedce](https://linux-hardware.org/?probe=de713cedce) | Jan 21, 2023 |
| Acer          | V5WE2                       | Notebook    | [021281441e](https://linux-hardware.org/?probe=021281441e) | Jan 20, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [be320f363d](https://linux-hardware.org/?probe=be320f363d) | Jan 19, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [e3d0558aee](https://linux-hardware.org/?probe=e3d0558aee) | Jan 19, 2023 |
| Dell          | Precision M6600             | Notebook    | [478f51f2be](https://linux-hardware.org/?probe=478f51f2be) | Jan 17, 2023 |
| MSI           | 970A-G43                    | Desktop     | [086e04b65f](https://linux-hardware.org/?probe=086e04b65f) | Jan 17, 2023 |
| Dell          | Precision M6600             | Notebook    | [7511681884](https://linux-hardware.org/?probe=7511681884) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [bf8115e391](https://linux-hardware.org/?probe=bf8115e391) | Jan 15, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [25cf332260](https://linux-hardware.org/?probe=25cf332260) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3f12fad87c](https://linux-hardware.org/?probe=3f12fad87c) | Jan 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6584beb723](https://linux-hardware.org/?probe=6584beb723) | Jan 15, 2023 |
| Gigabyte      | H67M-D2-B3                  | Desktop     | [6a4e71bb84](https://linux-hardware.org/?probe=6a4e71bb84) | Jan 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [020abf67f6](https://linux-hardware.org/?probe=020abf67f6) | Jan 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [f32463429a](https://linux-hardware.org/?probe=f32463429a) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [6f39a15710](https://linux-hardware.org/?probe=6f39a15710) | Jan 13, 2023 |
| ASUSTek       | X406UAR                     | Notebook    | [68da6f6220](https://linux-hardware.org/?probe=68da6f6220) | Jan 13, 2023 |
| ASUSTek       | J1900I-C                    | Desktop     | [f12439ce42](https://linux-hardware.org/?probe=f12439ce42) | Jan 13, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [0eb36758be](https://linux-hardware.org/?probe=0eb36758be) | Jan 13, 2023 |
| HP            | 21F5                        | Desktop     | [141aa3faa6](https://linux-hardware.org/?probe=141aa3faa6) | Jan 12, 2023 |
| ASUSTek       | X406UAR                     | Notebook    | [729e2e0d41](https://linux-hardware.org/?probe=729e2e0d41) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [de94c3e313](https://linux-hardware.org/?probe=de94c3e313) | Jan 12, 2023 |
| ASUSTek       | PN50                        | Mini pc     | [564c992a69](https://linux-hardware.org/?probe=564c992a69) | Jan 11, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [9a698e2879](https://linux-hardware.org/?probe=9a698e2879) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| Acer          | TMP645-M                    | Notebook    | [8e0b2f5e90](https://linux-hardware.org/?probe=8e0b2f5e90) | Jan 10, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [afe262fc54](https://linux-hardware.org/?probe=afe262fc54) | Jan 09, 2023 |
| ASUSTek       | K50IE                       | Notebook    | [4fdb15502c](https://linux-hardware.org/?probe=4fdb15502c) | Jan 09, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | Notebook    | [fc35d7e62b](https://linux-hardware.org/?probe=fc35d7e62b) | Jan 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [69cda32447](https://linux-hardware.org/?probe=69cda32447) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [c4ae03416f](https://linux-hardware.org/?probe=c4ae03416f) | Jan 07, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [cc98c43ea0](https://linux-hardware.org/?probe=cc98c43ea0) | Jan 07, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [9320df061f](https://linux-hardware.org/?probe=9320df061f) | Jan 06, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Neousys Te... | POC-200 Series              | Notebook    | [7c37ff8631](https://linux-hardware.org/?probe=7c37ff8631) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| ASRock        | FM2A88M-HD+ R3.0            | Desktop     | [acbd8114d2](https://linux-hardware.org/?probe=acbd8114d2) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [3fb1b015e3](https://linux-hardware.org/?probe=3fb1b015e3) | Jan 02, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [cdb2bf4725](https://linux-hardware.org/?probe=cdb2bf4725) | Jan 02, 2023 |
| MSI           | PRO B660M-E DDR4            | Desktop     | [6ae9b30e34](https://linux-hardware.org/?probe=6ae9b30e34) | Jan 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [8db34630c3](https://linux-hardware.org/?probe=8db34630c3) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1ff4c4bf09](https://linux-hardware.org/?probe=1ff4c4bf09) | Dec 28, 2022 |
| Lenovo        | No DPK                      | Desktop     | [944f84567a](https://linux-hardware.org/?probe=944f84567a) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [57a42cabf6](https://linux-hardware.org/?probe=57a42cabf6) | Dec 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [9a6b000b23](https://linux-hardware.org/?probe=9a6b000b23) | Dec 23, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [2892951c9c](https://linux-hardware.org/?probe=2892951c9c) | Dec 23, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [81f7e4d804](https://linux-hardware.org/?probe=81f7e4d804) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [ddc35a5b0d](https://linux-hardware.org/?probe=ddc35a5b0d) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | Notebook    | [6306be2273](https://linux-hardware.org/?probe=6306be2273) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | Notebook    | [cf8576151f](https://linux-hardware.org/?probe=cf8576151f) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| HP            | 89E8 0100                   | All in one  | [0e9567b0a5](https://linux-hardware.org/?probe=0e9567b0a5) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [d27a2a4e0f](https://linux-hardware.org/?probe=d27a2a4e0f) | Dec 20, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [30aec905c0](https://linux-hardware.org/?probe=30aec905c0) | Dec 19, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [20544e55bb](https://linux-hardware.org/?probe=20544e55bb) | Dec 14, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d087536cbf](https://linux-hardware.org/?probe=d087536cbf) | Dec 14, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [20c4b98c2c](https://linux-hardware.org/?probe=20c4b98c2c) | Dec 14, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| MSI           | MS-B1591                    | Desktop     | [33cb107fb9](https://linux-hardware.org/?probe=33cb107fb9) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [a1f1288337](https://linux-hardware.org/?probe=a1f1288337) | Dec 13, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [d1b0bc1c03](https://linux-hardware.org/?probe=d1b0bc1c03) | Dec 12, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [05c7382806](https://linux-hardware.org/?probe=05c7382806) | Dec 11, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [97691e3dca](https://linux-hardware.org/?probe=97691e3dca) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a7a3ccf712](https://linux-hardware.org/?probe=a7a3ccf712) | Dec 11, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [32e7431c24](https://linux-hardware.org/?probe=32e7431c24) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [83b02f1ffb](https://linux-hardware.org/?probe=83b02f1ffb) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ec32b72261](https://linux-hardware.org/?probe=ec32b72261) | Dec 09, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [e7495f12e4](https://linux-hardware.org/?probe=e7495f12e4) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea7638c0f9](https://linux-hardware.org/?probe=ea7638c0f9) | Dec 07, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [fd65cfedda](https://linux-hardware.org/?probe=fd65cfedda) | Dec 07, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [10f8aab734](https://linux-hardware.org/?probe=10f8aab734) | Dec 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a35bac4078](https://linux-hardware.org/?probe=a35bac4078) | Dec 06, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [2f693620e1](https://linux-hardware.org/?probe=2f693620e1) | Dec 06, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [586b9fe0a6](https://linux-hardware.org/?probe=586b9fe0a6) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b387887bb6](https://linux-hardware.org/?probe=b387887bb6) | Dec 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [d5ada57985](https://linux-hardware.org/?probe=d5ada57985) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3d64de28f5](https://linux-hardware.org/?probe=3d64de28f5) | Dec 01, 2022 |
| MSI           | G41M-S03                    | Desktop     | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1FR0... | Notebook    | [517347d2cf](https://linux-hardware.org/?probe=517347d2cf) | Nov 30, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b7a1fc62d1](https://linux-hardware.org/?probe=b7a1fc62d1) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [972f6f4355](https://linux-hardware.org/?probe=972f6f4355) | Nov 28, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [5b2f9bfd5c](https://linux-hardware.org/?probe=5b2f9bfd5c) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a39632439e](https://linux-hardware.org/?probe=a39632439e) | Nov 27, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [16679f50e3](https://linux-hardware.org/?probe=16679f50e3) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a178e673c3](https://linux-hardware.org/?probe=a178e673c3) | Nov 26, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [c1d5a26691](https://linux-hardware.org/?probe=c1d5a26691) | Nov 26, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a41bb9177a](https://linux-hardware.org/?probe=a41bb9177a) | Nov 23, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6c797b4554](https://linux-hardware.org/?probe=6c797b4554) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [b8379d261b](https://linux-hardware.org/?probe=b8379d261b) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Dell          | Latitude E6410              | Notebook    | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [75af06e026](https://linux-hardware.org/?probe=75af06e026) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c5ec7b9dcc](https://linux-hardware.org/?probe=c5ec7b9dcc) | Nov 20, 2022 |
| Lenovo        | V15 G1 IML 82NB             | Notebook    | [a120cac88b](https://linux-hardware.org/?probe=a120cac88b) | Nov 18, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2089ec3efb](https://linux-hardware.org/?probe=2089ec3efb) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | Desktop     | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Allview       | Allbook H                   | Notebook    | [4de72c8cba](https://linux-hardware.org/?probe=4de72c8cba) | Nov 17, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| HP            | 843B                        | Desktop     | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [30916d8420](https://linux-hardware.org/?probe=30916d8420) | Nov 16, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [61bcea3891](https://linux-hardware.org/?probe=61bcea3891) | Nov 13, 2022 |
| Alienware     | Area-51m                    | Notebook    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| Dell          | Latitude E7270              | Notebook    | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e80d2221f5](https://linux-hardware.org/?probe=e80d2221f5) | Nov 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [8384350121](https://linux-hardware.org/?probe=8384350121) | Nov 08, 2022 |
| Acer          | Aspire A314-35              | Notebook    | [14751e1ae3](https://linux-hardware.org/?probe=14751e1ae3) | Nov 08, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [7dc3ed5f76](https://linux-hardware.org/?probe=7dc3ed5f76) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81A8     | Notebook    | [85efda7536](https://linux-hardware.org/?probe=85efda7536) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [f9238c2035](https://linux-hardware.org/?probe=f9238c2035) | Oct 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [9e8ec19352](https://linux-hardware.org/?probe=9e8ec19352) | Oct 26, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [7274eca48b](https://linux-hardware.org/?probe=7274eca48b) | Oct 23, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [84941aaa84](https://linux-hardware.org/?probe=84941aaa84) | Oct 14, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [a6a5cdbf04](https://linux-hardware.org/?probe=a6a5cdbf04) | Oct 13, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [478ba58d34](https://linux-hardware.org/?probe=478ba58d34) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| ASUSTek       | V222GAR                     | All in one  | [e7e07dca5c](https://linux-hardware.org/?probe=e7e07dca5c) | Oct 12, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [79236a7a89](https://linux-hardware.org/?probe=79236a7a89) | Oct 11, 2022 |
| Medion        | Akoya E6239                 | Notebook    | [46ce690b32](https://linux-hardware.org/?probe=46ce690b32) | Oct 10, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [abc991002e](https://linux-hardware.org/?probe=abc991002e) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| Dell          | Latitude E6410              | Notebook    | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| HP            | 2AED                        | All in one  | [9092720ed6](https://linux-hardware.org/?probe=9092720ed6) | Oct 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9474bd3b9](https://linux-hardware.org/?probe=d9474bd3b9) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [cf4537f9cb](https://linux-hardware.org/?probe=cf4537f9cb) | Oct 02, 2022 |
| Medion        | Akoya P2214T                | Notebook    | [428205d2a5](https://linux-hardware.org/?probe=428205d2a5) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [3e92ba3812](https://linux-hardware.org/?probe=3e92ba3812) | Sep 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [96c4c8ba02](https://linux-hardware.org/?probe=96c4c8ba02) | Sep 28, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [11f99758e6](https://linux-hardware.org/?probe=11f99758e6) | Sep 28, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | Notebook    | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [deed57ec88](https://linux-hardware.org/?probe=deed57ec88) | Sep 23, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [38e1cc9153](https://linux-hardware.org/?probe=38e1cc9153) | Sep 22, 2022 |
| Fusion5       | S14                         | Notebook    | [9b3e06c4e4](https://linux-hardware.org/?probe=9b3e06c4e4) | Sep 22, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [b673d5cfe9](https://linux-hardware.org/?probe=b673d5cfe9) | Sep 22, 2022 |
| Dell          | Precision 3561              | Notebook    | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [aba8915769](https://linux-hardware.org/?probe=aba8915769) | Sep 19, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [d52ac897f4](https://linux-hardware.org/?probe=d52ac897f4) | Sep 15, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [39f83f7692](https://linux-hardware.org/?probe=39f83f7692) | Sep 13, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2af6edb7a0](https://linux-hardware.org/?probe=2af6edb7a0) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [43311add57](https://linux-hardware.org/?probe=43311add57) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c13cd2c2ac](https://linux-hardware.org/?probe=c13cd2c2ac) | Sep 09, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [3474424d64](https://linux-hardware.org/?probe=3474424d64) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e47c8e6967](https://linux-hardware.org/?probe=e47c8e6967) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [3f805d59b5](https://linux-hardware.org/?probe=3f805d59b5) | Sep 04, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [dcf7869cf6](https://linux-hardware.org/?probe=dcf7869cf6) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [c129f7c9b1](https://linux-hardware.org/?probe=c129f7c9b1) | Aug 29, 2022 |
| Dell          | Latitude E7470              | Notebook    | [568c9bfd40](https://linux-hardware.org/?probe=568c9bfd40) | Aug 28, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [4c16a58579](https://linux-hardware.org/?probe=4c16a58579) | Aug 28, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [fbf3d4a87a](https://linux-hardware.org/?probe=fbf3d4a87a) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [8b85141416](https://linux-hardware.org/?probe=8b85141416) | Aug 26, 2022 |
| Complet       | MY8312                      | Notebook    | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [09feb7053d](https://linux-hardware.org/?probe=09feb7053d) | Aug 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [69281b6cc3](https://linux-hardware.org/?probe=69281b6cc3) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| Dell          | Latitude 7410               | Notebook    | [ae90ce90ed](https://linux-hardware.org/?probe=ae90ce90ed) | Aug 22, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [5cbe471be8](https://linux-hardware.org/?probe=5cbe471be8) | Aug 19, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [1a0800fc4a](https://linux-hardware.org/?probe=1a0800fc4a) | Aug 19, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [4b585d8c34](https://linux-hardware.org/?probe=4b585d8c34) | Aug 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [f45a97ca40](https://linux-hardware.org/?probe=f45a97ca40) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [ca6a3b3fba](https://linux-hardware.org/?probe=ca6a3b3fba) | Aug 12, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [cdee8ca864](https://linux-hardware.org/?probe=cdee8ca864) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [eb79423b1d](https://linux-hardware.org/?probe=eb79423b1d) | Aug 12, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [86523f9a5f](https://linux-hardware.org/?probe=86523f9a5f) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [6826a8d40d](https://linux-hardware.org/?probe=6826a8d40d) | Aug 08, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [83626d765b](https://linux-hardware.org/?probe=83626d765b) | Aug 08, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [94d50a1c56](https://linux-hardware.org/?probe=94d50a1c56) | Aug 08, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1fe8a14d3b](https://linux-hardware.org/?probe=1fe8a14d3b) | Aug 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Unknown       | 1.0                         | Desktop     | [4394243123](https://linux-hardware.org/?probe=4394243123) | Aug 05, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | Notebook    | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| Unknown       | 1.0                         | Desktop     | [545d9cf73c](https://linux-hardware.org/?probe=545d9cf73c) | Aug 04, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [fbe4f4d2ce](https://linux-hardware.org/?probe=fbe4f4d2ce) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [eeccdc2b7f](https://linux-hardware.org/?probe=eeccdc2b7f) | Aug 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e6bfde2a29](https://linux-hardware.org/?probe=e6bfde2a29) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8b3fd99e18](https://linux-hardware.org/?probe=8b3fd99e18) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4ee4fc0689](https://linux-hardware.org/?probe=4ee4fc0689) | Jul 26, 2022 |
| HP            | 8704                        | Desktop     | [eaa4bc0059](https://linux-hardware.org/?probe=eaa4bc0059) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | Notebook    | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [892229b650](https://linux-hardware.org/?probe=892229b650) | Jul 21, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [9a5f11c4b9](https://linux-hardware.org/?probe=9a5f11c4b9) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Acer          | Aspire SW3-016              | Notebook    | [c48cdf5576](https://linux-hardware.org/?probe=c48cdf5576) | Jul 17, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [84cd652e24](https://linux-hardware.org/?probe=84cd652e24) | Jul 16, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [55efce6cdc](https://linux-hardware.org/?probe=55efce6cdc) | Jul 13, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [be909dd3b4](https://linux-hardware.org/?probe=be909dd3b4) | Jul 12, 2022 |
| HP            | 355 G2                      | Notebook    | [55239c5062](https://linux-hardware.org/?probe=55239c5062) | Jul 11, 2022 |
| HP            | 355 G2                      | Notebook    | [9b5e64b838](https://linux-hardware.org/?probe=9b5e64b838) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| HP            | 250 G4                      | Notebook    | [33dcd9203d](https://linux-hardware.org/?probe=33dcd9203d) | Jul 09, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [99172a6e6f](https://linux-hardware.org/?probe=99172a6e6f) | Jul 08, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [cb302e010e](https://linux-hardware.org/?probe=cb302e010e) | Jul 08, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [f991c1fba8](https://linux-hardware.org/?probe=f991c1fba8) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [a5f338ae1a](https://linux-hardware.org/?probe=a5f338ae1a) | Jul 07, 2022 |
| HP            | ProBook 4310s               | Notebook    | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [32463f298d](https://linux-hardware.org/?probe=32463f298d) | Jul 05, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [457aa90e64](https://linux-hardware.org/?probe=457aa90e64) | Jul 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [2fda374f06](https://linux-hardware.org/?probe=2fda374f06) | Jun 24, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [70d6947d54](https://linux-hardware.org/?probe=70d6947d54) | Jun 16, 2022 |
| HP            | 1790                        | Desktop     | [341a6c4c70](https://linux-hardware.org/?probe=341a6c4c70) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [1e88796016](https://linux-hardware.org/?probe=1e88796016) | Jun 15, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4b2037715f](https://linux-hardware.org/?probe=4b2037715f) | Jun 15, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Dell          | Latitude E6440              | Notebook    | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a144e0b75e](https://linux-hardware.org/?probe=a144e0b75e) | Jun 08, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [992f232db5](https://linux-hardware.org/?probe=992f232db5) | Jun 08, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Prestigio     | PSB141C04CGP                | Notebook    | [4fa2ee47c0](https://linux-hardware.org/?probe=4fa2ee47c0) | Jun 01, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [083e3a354a](https://linux-hardware.org/?probe=083e3a354a) | May 29, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [83209051cb](https://linux-hardware.org/?probe=83209051cb) | May 29, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [74c64ebe72](https://linux-hardware.org/?probe=74c64ebe72) | May 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [3115570400](https://linux-hardware.org/?probe=3115570400) | May 24, 2022 |
| Allview       | Allbook H                   | Notebook    | [9ea4897c6b](https://linux-hardware.org/?probe=9ea4897c6b) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b01633e1ae](https://linux-hardware.org/?probe=b01633e1ae) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [815dbb114b](https://linux-hardware.org/?probe=815dbb114b) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9a6c29a243](https://linux-hardware.org/?probe=9a6c29a243) | May 21, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [949f8f3e50](https://linux-hardware.org/?probe=949f8f3e50) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [4d2d33c41c](https://linux-hardware.org/?probe=4d2d33c41c) | May 20, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| Lenovo        | ThinkPad P53 20QNS01900     | Notebook    | [158f212b30](https://linux-hardware.org/?probe=158f212b30) | May 13, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [550824d592](https://linux-hardware.org/?probe=550824d592) | May 12, 2022 |
| HP            | 0AA8h                       | Desktop     | [7d29587a1a](https://linux-hardware.org/?probe=7d29587a1a) | May 11, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [324d1abe3b](https://linux-hardware.org/?probe=324d1abe3b) | May 08, 2022 |
| HP            | ProBook 4520s               | Notebook    | [06e044a425](https://linux-hardware.org/?probe=06e044a425) | May 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [52c2a321a4](https://linux-hardware.org/?probe=52c2a321a4) | May 07, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [9fe037820e](https://linux-hardware.org/?probe=9fe037820e) | May 05, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [7a6aa0c236](https://linux-hardware.org/?probe=7a6aa0c236) | May 03, 2022 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [713358f855](https://linux-hardware.org/?probe=713358f855) | May 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [a8e967a378](https://linux-hardware.org/?probe=a8e967a378) | May 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6537fb670a](https://linux-hardware.org/?probe=6537fb670a) | May 01, 2022 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| HP            | ProBook 4520s               | Notebook    | [60eab2c6c5](https://linux-hardware.org/?probe=60eab2c6c5) | Apr 30, 2022 |
| Pegatron      | Spring Peak                 | Notebook    | [66a1692171](https://linux-hardware.org/?probe=66a1692171) | Apr 30, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [efcd6be006](https://linux-hardware.org/?probe=efcd6be006) | Apr 27, 2022 |
| Dell          | Latitude E4310              | Notebook    | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [afe44fa080](https://linux-hardware.org/?probe=afe44fa080) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8ece944a7b](https://linux-hardware.org/?probe=8ece944a7b) | Apr 27, 2022 |
| Dell          | Latitude E6520              | Notebook    | [1ca407a69f](https://linux-hardware.org/?probe=1ca407a69f) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bcc0c7612d](https://linux-hardware.org/?probe=bcc0c7612d) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1EH0... | Notebook    | [fae5ee6551](https://linux-hardware.org/?probe=fae5ee6551) | Apr 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [c7dfc69b32](https://linux-hardware.org/?probe=c7dfc69b32) | Apr 26, 2022 |
| HP            | ProBook 4520s               | Notebook    | [1621eddc70](https://linux-hardware.org/?probe=1621eddc70) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [41276f12db](https://linux-hardware.org/?probe=41276f12db) | Apr 23, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [55733b5ae3](https://linux-hardware.org/?probe=55733b5ae3) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [a551ef1ec7](https://linux-hardware.org/?probe=a551ef1ec7) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [fd6718859d](https://linux-hardware.org/?probe=fd6718859d) | Apr 23, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [2518b6daad](https://linux-hardware.org/?probe=2518b6daad) | Apr 22, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [17d51c502f](https://linux-hardware.org/?probe=17d51c502f) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a3a204ed56](https://linux-hardware.org/?probe=a3a204ed56) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4521315d14](https://linux-hardware.org/?probe=4521315d14) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [fff2447e5a](https://linux-hardware.org/?probe=fff2447e5a) | Apr 21, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | Notebook    | [de746c72d1](https://linux-hardware.org/?probe=de746c72d1) | Apr 20, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [5d95841f54](https://linux-hardware.org/?probe=5d95841f54) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | Notebook    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [8b54af493a](https://linux-hardware.org/?probe=8b54af493a) | Apr 19, 2022 |
| Dell          | Latitude E6440              | Notebook    | [33955db41e](https://linux-hardware.org/?probe=33955db41e) | Apr 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1825f45bfa](https://linux-hardware.org/?probe=1825f45bfa) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| HP            | Pavilion 17                 | Notebook    | [acb0c7fd0e](https://linux-hardware.org/?probe=acb0c7fd0e) | Apr 16, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | Notebook    | [a572c901ca](https://linux-hardware.org/?probe=a572c901ca) | Apr 15, 2022 |
| HP            | Pavilion 17                 | Notebook    | [014f42ecee](https://linux-hardware.org/?probe=014f42ecee) | Apr 15, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [73d1368d93](https://linux-hardware.org/?probe=73d1368d93) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9709ffeb9a](https://linux-hardware.org/?probe=9709ffeb9a) | Apr 14, 2022 |
| Dell          | System XPS L702X            | Notebook    | [9ed530100f](https://linux-hardware.org/?probe=9ed530100f) | Apr 13, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [95ddaa1dae](https://linux-hardware.org/?probe=95ddaa1dae) | Apr 13, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ba6f51707b](https://linux-hardware.org/?probe=ba6f51707b) | Apr 13, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [a06e300bfd](https://linux-hardware.org/?probe=a06e300bfd) | Apr 12, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [ffb5635168](https://linux-hardware.org/?probe=ffb5635168) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [59b9f6ab96](https://linux-hardware.org/?probe=59b9f6ab96) | Apr 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [27e9b2e124](https://linux-hardware.org/?probe=27e9b2e124) | Apr 09, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [5fea9b2c3a](https://linux-hardware.org/?probe=5fea9b2c3a) | Apr 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dd2c447b48](https://linux-hardware.org/?probe=dd2c447b48) | Apr 07, 2022 |
| HP            | 0AA8h                       | Desktop     | [0de7915496](https://linux-hardware.org/?probe=0de7915496) | Apr 06, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [beeceac759](https://linux-hardware.org/?probe=beeceac759) | Apr 04, 2022 |
| Lenovo        | B590 37612LG                | Notebook    | [153a6c2343](https://linux-hardware.org/?probe=153a6c2343) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| HP            | 1790                        | Desktop     | [9b8f0779ab](https://linux-hardware.org/?probe=9b8f0779ab) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [13aa7656f3](https://linux-hardware.org/?probe=13aa7656f3) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [62982f1e80](https://linux-hardware.org/?probe=62982f1e80) | Apr 02, 2022 |
| Medion        | H81H3-EM2                   | Desktop     | [4c887e357d](https://linux-hardware.org/?probe=4c887e357d) | Mar 31, 2022 |
| HP            | 250 G4                      | Notebook    | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [c2d3fbb93e](https://linux-hardware.org/?probe=c2d3fbb93e) | Mar 30, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [ffde31bd20](https://linux-hardware.org/?probe=ffde31bd20) | Mar 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [2bbea411a6](https://linux-hardware.org/?probe=2bbea411a6) | Mar 24, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [c55e29b1e9](https://linux-hardware.org/?probe=c55e29b1e9) | Mar 22, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [ce6cc28ca1](https://linux-hardware.org/?probe=ce6cc28ca1) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8d1c371df2](https://linux-hardware.org/?probe=8d1c371df2) | Mar 21, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [35da4bbe2c](https://linux-hardware.org/?probe=35da4bbe2c) | Mar 21, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [626ee37f9b](https://linux-hardware.org/?probe=626ee37f9b) | Mar 21, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a93c59159d](https://linux-hardware.org/?probe=a93c59159d) | Mar 20, 2022 |
| Acer          | Swift SF514-55GT            | Notebook    | [ae09c5da41](https://linux-hardware.org/?probe=ae09c5da41) | Mar 20, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [7e8098be12](https://linux-hardware.org/?probe=7e8098be12) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b8b480e048](https://linux-hardware.org/?probe=b8b480e048) | Mar 20, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [a3a8154156](https://linux-hardware.org/?probe=a3a8154156) | Mar 17, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |
| Dell          | 05R2TK A01                  | All in one  | [d678cbb1cc](https://linux-hardware.org/?probe=d678cbb1cc) | Mar 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [5da90f10f4](https://linux-hardware.org/?probe=5da90f10f4) | Mar 15, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [4bc060dc9d](https://linux-hardware.org/?probe=4bc060dc9d) | Mar 14, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [28303b98cc](https://linux-hardware.org/?probe=28303b98cc) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a339fe7a39](https://linux-hardware.org/?probe=a339fe7a39) | Mar 13, 2022 |
| Intel         | DG31PR AAD97573-300         | Desktop     | [509c41b106](https://linux-hardware.org/?probe=509c41b106) | Mar 13, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [c82a0d33a2](https://linux-hardware.org/?probe=c82a0d33a2) | Mar 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [e8c3922bb3](https://linux-hardware.org/?probe=e8c3922bb3) | Mar 12, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [6034a2269a](https://linux-hardware.org/?probe=6034a2269a) | Mar 09, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [385d1914ee](https://linux-hardware.org/?probe=385d1914ee) | Mar 07, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [ad5413d163](https://linux-hardware.org/?probe=ad5413d163) | Mar 06, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [3b3220eeee](https://linux-hardware.org/?probe=3b3220eeee) | Mar 06, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [b1ac4ae8e7](https://linux-hardware.org/?probe=b1ac4ae8e7) | Mar 05, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [6d26072b9e](https://linux-hardware.org/?probe=6d26072b9e) | Mar 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [53d74176e9](https://linux-hardware.org/?probe=53d74176e9) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [73881ad12e](https://linux-hardware.org/?probe=73881ad12e) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Dell          | 0XHGV1 A02                  | Desktop     | [768657efd5](https://linux-hardware.org/?probe=768657efd5) | Mar 03, 2022 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [6090fb66ea](https://linux-hardware.org/?probe=6090fb66ea) | Mar 02, 2022 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [c56a98389f](https://linux-hardware.org/?probe=c56a98389f) | Mar 01, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| Medion        | E16402                      | Notebook    | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c57b3c9081](https://linux-hardware.org/?probe=c57b3c9081) | Feb 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0P900      | Tablet      | [a7034fd62e](https://linux-hardware.org/?probe=a7034fd62e) | Feb 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0P900      | Tablet      | [61c4a46887](https://linux-hardware.org/?probe=61c4a46887) | Feb 26, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [c8dd47fb82](https://linux-hardware.org/?probe=c8dd47fb82) | Feb 26, 2022 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [800ecfe818](https://linux-hardware.org/?probe=800ecfe818) | Feb 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [402a27e190](https://linux-hardware.org/?probe=402a27e190) | Feb 24, 2022 |
| ASUSTek       | X55U                        | Notebook    | [c7c38f077d](https://linux-hardware.org/?probe=c7c38f077d) | Feb 24, 2022 |
| HP            | 84DE                        | All in one  | [43184fd6bf](https://linux-hardware.org/?probe=43184fd6bf) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6083eed5da](https://linux-hardware.org/?probe=6083eed5da) | Feb 21, 2022 |
| Lenovo        | ThinkPad T430 2349U15       | Notebook    | [38a194c33d](https://linux-hardware.org/?probe=38a194c33d) | Feb 20, 2022 |
| MSI           | MS-7392                     | Desktop     | [c64a5b4adf](https://linux-hardware.org/?probe=c64a5b4adf) | Feb 20, 2022 |
| MSI           | MS-7392                     | Desktop     | [308ed6c0c6](https://linux-hardware.org/?probe=308ed6c0c6) | Feb 20, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [417a759484](https://linux-hardware.org/?probe=417a759484) | Feb 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [dfc7dad0ee](https://linux-hardware.org/?probe=dfc7dad0ee) | Feb 17, 2022 |
| Lenovo        | ThinkPad P50 20ENS0FQ00     | Notebook    | [8d8e30fdfb](https://linux-hardware.org/?probe=8d8e30fdfb) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [5d2de5cd73](https://linux-hardware.org/?probe=5d2de5cd73) | Feb 17, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [be010e2d04](https://linux-hardware.org/?probe=be010e2d04) | Feb 17, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [fec0662c03](https://linux-hardware.org/?probe=fec0662c03) | Feb 16, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [f6383e06d7](https://linux-hardware.org/?probe=f6383e06d7) | Feb 16, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [13989d56ec](https://linux-hardware.org/?probe=13989d56ec) | Feb 14, 2022 |
| MSI           | EX620                       | Notebook    | [8eda01e2a8](https://linux-hardware.org/?probe=8eda01e2a8) | Feb 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e48e07387e](https://linux-hardware.org/?probe=e48e07387e) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [be994742e1](https://linux-hardware.org/?probe=be994742e1) | Feb 13, 2022 |
| HP            | 09F8h                       | Desktop     | [d887fef9ff](https://linux-hardware.org/?probe=d887fef9ff) | Feb 13, 2022 |
| HP            | EliteBook 8530p             | Notebook    | [6b45115b9e](https://linux-hardware.org/?probe=6b45115b9e) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eeeac91ae4](https://linux-hardware.org/?probe=eeeac91ae4) | Feb 13, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [a016adec7d](https://linux-hardware.org/?probe=a016adec7d) | Feb 12, 2022 |
| HP            | 339A                        | Desktop     | [a4eac4d7b8](https://linux-hardware.org/?probe=a4eac4d7b8) | Feb 11, 2022 |
| Lenovo        | NOK                         | Desktop     | [f860aaeaf3](https://linux-hardware.org/?probe=f860aaeaf3) | Feb 11, 2022 |
| HP            | 0AA8h                       | Desktop     | [a78b5c3460](https://linux-hardware.org/?probe=a78b5c3460) | Feb 10, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [5e071a1807](https://linux-hardware.org/?probe=5e071a1807) | Feb 09, 2022 |
| Lenovo        | ThinkPad T410 2522Y15       | Notebook    | [66a496ba4c](https://linux-hardware.org/?probe=66a496ba4c) | Feb 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7d600bcdc7](https://linux-hardware.org/?probe=7d600bcdc7) | Feb 08, 2022 |
| Lenovo        | ThinkPad L380 20M5003FUK    | Notebook    | [fe486b4de6](https://linux-hardware.org/?probe=fe486b4de6) | Feb 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS3W300    | Notebook    | [a49c14ab70](https://linux-hardware.org/?probe=a49c14ab70) | Feb 06, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [275d33a826](https://linux-hardware.org/?probe=275d33a826) | Feb 06, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [23b715cc77](https://linux-hardware.org/?probe=23b715cc77) | Feb 05, 2022 |
| Allview       | Allbook H                   | Notebook    | [f1ba3f22c4](https://linux-hardware.org/?probe=f1ba3f22c4) | Feb 05, 2022 |
| Gigabyte      | P35-DS3R                    | Desktop     | [3164a5ed5b](https://linux-hardware.org/?probe=3164a5ed5b) | Feb 05, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [4975c3b6b7](https://linux-hardware.org/?probe=4975c3b6b7) | Feb 05, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [5eaea69c49](https://linux-hardware.org/?probe=5eaea69c49) | Feb 04, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [d554447e6b](https://linux-hardware.org/?probe=d554447e6b) | Feb 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [63c8ab5447](https://linux-hardware.org/?probe=63c8ab5447) | Feb 03, 2022 |
| HP            | EliteBook x360 1040 G5      | Notebook    | [4aa3aa1f30](https://linux-hardware.org/?probe=4aa3aa1f30) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [1e330f1e0e](https://linux-hardware.org/?probe=1e330f1e0e) | Feb 02, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [5d9bab6a00](https://linux-hardware.org/?probe=5d9bab6a00) | Feb 02, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [94fefac9e1](https://linux-hardware.org/?probe=94fefac9e1) | Feb 01, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [b80429c5fe](https://linux-hardware.org/?probe=b80429c5fe) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [7c2762f41c](https://linux-hardware.org/?probe=7c2762f41c) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [2aa45a8d1b](https://linux-hardware.org/?probe=2aa45a8d1b) | Jan 31, 2022 |
| Acer          | RS880M05                    | Desktop     | [43b14c0f42](https://linux-hardware.org/?probe=43b14c0f42) | Jan 31, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [b61bba90ad](https://linux-hardware.org/?probe=b61bba90ad) | Jan 30, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Acer          | Extensa 2510                | Notebook    | [1fcabc0254](https://linux-hardware.org/?probe=1fcabc0254) | Jan 26, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [3bcb1d5f53](https://linux-hardware.org/?probe=3bcb1d5f53) | Jan 25, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [6d62bb9596](https://linux-hardware.org/?probe=6d62bb9596) | Jan 24, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [0e47f03d64](https://linux-hardware.org/?probe=0e47f03d64) | Jan 24, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [ded9015aff](https://linux-hardware.org/?probe=ded9015aff) | Jan 23, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [6ab6d3c8b2](https://linux-hardware.org/?probe=6ab6d3c8b2) | Jan 23, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [d90de3e8f7](https://linux-hardware.org/?probe=d90de3e8f7) | Jan 21, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [3609f04919](https://linux-hardware.org/?probe=3609f04919) | Jan 19, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [8e66dbbe5c](https://linux-hardware.org/?probe=8e66dbbe5c) | Jan 19, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [d4187f35fd](https://linux-hardware.org/?probe=d4187f35fd) | Jan 19, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [2f55e0a142](https://linux-hardware.org/?probe=2f55e0a142) | Jan 19, 2022 |
| Dell          | MXG071                      | Notebook    | [cd914ee2f0](https://linux-hardware.org/?probe=cd914ee2f0) | Jan 18, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [e4489c39b8](https://linux-hardware.org/?probe=e4489c39b8) | Jan 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [4b51693e30](https://linux-hardware.org/?probe=4b51693e30) | Jan 17, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | Notebook    | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| Samsung       | R580/R590                   | Notebook    | [be1e77de84](https://linux-hardware.org/?probe=be1e77de84) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [342f6f2beb](https://linux-hardware.org/?probe=342f6f2beb) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [34f103b8d2](https://linux-hardware.org/?probe=34f103b8d2) | Jan 16, 2022 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [12db3650f6](https://linux-hardware.org/?probe=12db3650f6) | Jan 14, 2022 |
| MSI           | 2A9C                        | Desktop     | [09004ce71d](https://linux-hardware.org/?probe=09004ce71d) | Jan 14, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [efe75d8f3f](https://linux-hardware.org/?probe=efe75d8f3f) | Jan 14, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [6976b6ebbd](https://linux-hardware.org/?probe=6976b6ebbd) | Jan 14, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [15dd95fdfd](https://linux-hardware.org/?probe=15dd95fdfd) | Jan 14, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [615ed31a98](https://linux-hardware.org/?probe=615ed31a98) | Jan 13, 2022 |
| Acer          | Aspire T3-710 V:1.1         | Desktop     | [088a0a9608](https://linux-hardware.org/?probe=088a0a9608) | Jan 12, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [5f41c8e050](https://linux-hardware.org/?probe=5f41c8e050) | Jan 12, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [56d6ea164b](https://linux-hardware.org/?probe=56d6ea164b) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d9bd1bab23](https://linux-hardware.org/?probe=d9bd1bab23) | Jan 09, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [353534e82a](https://linux-hardware.org/?probe=353534e82a) | Jan 08, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [ba78c8aef3](https://linux-hardware.org/?probe=ba78c8aef3) | Jan 07, 2022 |
| HP            | 843B                        | Desktop     | [24e5dae02e](https://linux-hardware.org/?probe=24e5dae02e) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [1630e680bc](https://linux-hardware.org/?probe=1630e680bc) | Jan 06, 2022 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [3e7d72e09a](https://linux-hardware.org/?probe=3e7d72e09a) | Jan 06, 2022 |
| Chuwi         | Hero Book                   | Notebook    | [b111f44fad](https://linux-hardware.org/?probe=b111f44fad) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Dell          | Inspiron 7586               | Convertible | [9a480f9de9](https://linux-hardware.org/?probe=9a480f9de9) | Jan 04, 2022 |
| ASUSTek       | X550VL                      | Notebook    | [46ed51f6ef](https://linux-hardware.org/?probe=46ed51f6ef) | Jan 04, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [0132076c85](https://linux-hardware.org/?probe=0132076c85) | Jan 04, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291B78       | Notebook    | [76350af57f](https://linux-hardware.org/?probe=76350af57f) | Jan 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a7217db810](https://linux-hardware.org/?probe=a7217db810) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [286ce69daf](https://linux-hardware.org/?probe=286ce69daf) | Jan 02, 2022 |
| HP            | 1497                        | Desktop     | [540458f943](https://linux-hardware.org/?probe=540458f943) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [f5eafcc9e4](https://linux-hardware.org/?probe=f5eafcc9e4) | Jan 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [50a5dc78eb](https://linux-hardware.org/?probe=50a5dc78eb) | Jan 02, 2022 |
| MSI           | EX705                       | Notebook    | [a969bd4369](https://linux-hardware.org/?probe=a969bd4369) | Dec 31, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [64743b9e56](https://linux-hardware.org/?probe=64743b9e56) | Dec 30, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [a8b3cc88b1](https://linux-hardware.org/?probe=a8b3cc88b1) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [af923f06cc](https://linux-hardware.org/?probe=af923f06cc) | Dec 29, 2021 |
| Dell          | Latitude E5420m             | Notebook    | [6f5af5da5c](https://linux-hardware.org/?probe=6f5af5da5c) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [a7a37c26c7](https://linux-hardware.org/?probe=a7a37c26c7) | Dec 29, 2021 |
| Dream Mach... | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [c3f88b03df](https://linux-hardware.org/?probe=c3f88b03df) | Dec 28, 2021 |
| Lenovo        | ThinkStation E20 4220RF8    | Desktop     | [e525340bef](https://linux-hardware.org/?probe=e525340bef) | Dec 28, 2021 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [82a0c6cd43](https://linux-hardware.org/?probe=82a0c6cd43) | Dec 28, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b2b9ea9e60](https://linux-hardware.org/?probe=b2b9ea9e60) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 4291B78       | Notebook    | [2c8a912b3e](https://linux-hardware.org/?probe=2c8a912b3e) | Dec 24, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [e4dc4b8711](https://linux-hardware.org/?probe=e4dc4b8711) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1f334f4c1c](https://linux-hardware.org/?probe=1f334f4c1c) | Dec 22, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| HP            | 18E7                        | Desktop     | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [6748ebc68a](https://linux-hardware.org/?probe=6748ebc68a) | Dec 20, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [00868d9166](https://linux-hardware.org/?probe=00868d9166) | Dec 17, 2021 |
| HP            | 1998                        | Desktop     | [9bfa0ed638](https://linux-hardware.org/?probe=9bfa0ed638) | Dec 17, 2021 |
| Timi          | TM1701                      | Notebook    | [f063712cce](https://linux-hardware.org/?probe=f063712cce) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [ac40d89d27](https://linux-hardware.org/?probe=ac40d89d27) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [7da5a1020d](https://linux-hardware.org/?probe=7da5a1020d) | Dec 15, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| Chuwi         | Hero Book                   | Notebook    | [27e37e5a15](https://linux-hardware.org/?probe=27e37e5a15) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [85770fb8f5](https://linux-hardware.org/?probe=85770fb8f5) | Dec 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | Notebook    | [b68de5799e](https://linux-hardware.org/?probe=b68de5799e) | Dec 12, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [5d06e53d08](https://linux-hardware.org/?probe=5d06e53d08) | Dec 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ed065155fb](https://linux-hardware.org/?probe=ed065155fb) | Dec 11, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [7fe98389c6](https://linux-hardware.org/?probe=7fe98389c6) | Dec 11, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [5be7aac3a2](https://linux-hardware.org/?probe=5be7aac3a2) | Dec 09, 2021 |
| ASUSTek       | V241FA                      | All in one  | [60c6c7ea7c](https://linux-hardware.org/?probe=60c6c7ea7c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [98f25277f5](https://linux-hardware.org/?probe=98f25277f5) | Dec 08, 2021 |
| ASRockRack    | E3C232D4U-V1L               | Desktop     | [139a75e689](https://linux-hardware.org/?probe=139a75e689) | Dec 07, 2021 |
| Dell          | Inspiron 7586               | Convertible | [53604c12d1](https://linux-hardware.org/?probe=53604c12d1) | Dec 05, 2021 |
| INET          | Z12B                        | Mini pc     | [95470b9d91](https://linux-hardware.org/?probe=95470b9d91) | Dec 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [1c6db4a61b](https://linux-hardware.org/?probe=1c6db4a61b) | Dec 03, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [902395fcce](https://linux-hardware.org/?probe=902395fcce) | Dec 03, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [ad91050095](https://linux-hardware.org/?probe=ad91050095) | Dec 03, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [e73cda5c1e](https://linux-hardware.org/?probe=e73cda5c1e) | Dec 02, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [d3040ac7d5](https://linux-hardware.org/?probe=d3040ac7d5) | Nov 30, 2021 |
| Allview       | Allbook J                   | Notebook    | [957074dbe3](https://linux-hardware.org/?probe=957074dbe3) | Nov 30, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [317b686b33](https://linux-hardware.org/?probe=317b686b33) | Nov 29, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [c323b490bf](https://linux-hardware.org/?probe=c323b490bf) | Nov 26, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [755b7b85f5](https://linux-hardware.org/?probe=755b7b85f5) | Nov 24, 2021 |
| Medion        | E7218                       | Notebook    | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [dba80843bc](https://linux-hardware.org/?probe=dba80843bc) | Nov 23, 2021 |
| HP            | Compaq 2510p                | Notebook    | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [eb7191f8cb](https://linux-hardware.org/?probe=eb7191f8cb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [1169bef865](https://linux-hardware.org/?probe=1169bef865) | Nov 22, 2021 |
| HP            | Compaq 2510p                | Notebook    | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb48a45349](https://linux-hardware.org/?probe=bb48a45349) | Nov 22, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [9a83e53e34](https://linux-hardware.org/?probe=9a83e53e34) | Nov 22, 2021 |
| ASUSTek       | X450CP                      | Notebook    | [7228a5157c](https://linux-hardware.org/?probe=7228a5157c) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [04fa536869](https://linux-hardware.org/?probe=04fa536869) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [097de81570](https://linux-hardware.org/?probe=097de81570) | Nov 20, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [4a77a751d9](https://linux-hardware.org/?probe=4a77a751d9) | Nov 20, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Dell          | Latitude 7410               | Notebook    | [226f912726](https://linux-hardware.org/?probe=226f912726) | Nov 18, 2021 |
| ASUSTek       | K53U                        | Notebook    | [8b542e61d9](https://linux-hardware.org/?probe=8b542e61d9) | Nov 18, 2021 |
| Dell          | Latitude E7470              | Notebook    | [0358863974](https://linux-hardware.org/?probe=0358863974) | Nov 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2e7ed34d33](https://linux-hardware.org/?probe=2e7ed34d33) | Nov 16, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [6677eae4da](https://linux-hardware.org/?probe=6677eae4da) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| ASUSTek       | X540SA                      | Notebook    | [1292ab6f15](https://linux-hardware.org/?probe=1292ab6f15) | Nov 14, 2021 |
| Dell          | Latitude E6410              | Notebook    | [1a31fa8433](https://linux-hardware.org/?probe=1a31fa8433) | Nov 13, 2021 |
| ASUSTek       | X540SA                      | Notebook    | [463e1f35a9](https://linux-hardware.org/?probe=463e1f35a9) | Nov 13, 2021 |
| Sony          | SVF14N1E2ES                 | Notebook    | [a04441e5cd](https://linux-hardware.org/?probe=a04441e5cd) | Nov 13, 2021 |
| Dell          | Precision 3541              | Notebook    | [8f6085ab9d](https://linux-hardware.org/?probe=8f6085ab9d) | Nov 12, 2021 |
| Packard Be... | EasyNote TN36               | Notebook    | [17ebc64721](https://linux-hardware.org/?probe=17ebc64721) | Nov 11, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [e70882b3fd](https://linux-hardware.org/?probe=e70882b3fd) | Nov 11, 2021 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [32988fae95](https://linux-hardware.org/?probe=32988fae95) | Nov 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b79aef683b](https://linux-hardware.org/?probe=b79aef683b) | Nov 11, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [c32869e5a8](https://linux-hardware.org/?probe=c32869e5a8) | Nov 08, 2021 |
| ASUSTek       | A58M-K                      | Desktop     | [0dbc01db57](https://linux-hardware.org/?probe=0dbc01db57) | Nov 08, 2021 |
| Gigabyte      | P31-DS3L                    | Desktop     | [c0ef5646a8](https://linux-hardware.org/?probe=c0ef5646a8) | Nov 07, 2021 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [6dd5b7f191](https://linux-hardware.org/?probe=6dd5b7f191) | Nov 06, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [c1bd9abdd2](https://linux-hardware.org/?probe=c1bd9abdd2) | Nov 03, 2021 |
| HP            | 18E4                        | Desktop     | [1c3ea795a0](https://linux-hardware.org/?probe=1c3ea795a0) | Nov 03, 2021 |
| HP            | 18E4                        | Desktop     | [4994f5c700](https://linux-hardware.org/?probe=4994f5c700) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| Dell          | G3 3579                     | Notebook    | [f9fdeb003b](https://linux-hardware.org/?probe=f9fdeb003b) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [8cdb34dbc8](https://linux-hardware.org/?probe=8cdb34dbc8) | Nov 01, 2021 |
| Lenovo        | ThinkPad T430 2349U15       | Notebook    | [c9d8efc9b9](https://linux-hardware.org/?probe=c9d8efc9b9) | Oct 31, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [f31e6e3dd0](https://linux-hardware.org/?probe=f31e6e3dd0) | Oct 29, 2021 |
| ASUSTek       | V241EA                      | All in one  | [243713e97a](https://linux-hardware.org/?probe=243713e97a) | Oct 28, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Romania/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 209       | 10.56%  |
| Ubuntu 18.04                 | 106       | 5.35%   |
| Ubuntu 22.04                 | 82        | 4.14%   |
| BlackPanther 18.1            | 61        | 3.08%   |
| OpenMandriva 4.3             | 46        | 2.32%   |
| OpenMandriva 4.2             | 45        | 2.27%   |
| Manjaro                      | 31        | 1.57%   |
| Debian 11                    | 30        | 1.52%   |
| Arch                         | 28        | 1.41%   |
| Zorin 16                     | 27        | 1.36%   |
| ROSA R10                     | 27        | 1.36%   |
| Arch Rolling                 | 27        | 1.36%   |
| KDE neon 20.04               | 24        | 1.21%   |
| Pop!_OS 21.04                | 23        | 1.16%   |
| Pop!_OS 22.04                | 22        | 1.11%   |
| ArcoLinux Rolling            | 21        | 1.06%   |
| Ubuntu 21.10                 | 20        | 1.01%   |
| Pop!_OS 20.04                | 20        | 1.01%   |
| Linux Mint 21.1              | 20        | 1.01%   |
| Endless 3.7.8                | 20        | 1.01%   |
| Zorin 15                     | 19        | 0.96%   |
| Fedora 35                    | 19        | 0.96%   |
| Ubuntu 20.10                 | 18        | 0.91%   |
| Endless 3.9.5                | 18        | 0.91%   |
| Endless 3.9.1                | 18        | 0.91%   |
| Ubuntu 19.10                 | 17        | 0.86%   |
| OpenMandriva 23.01           | 17        | 0.86%   |
| Ubuntu 21.04                 | 16        | 0.81%   |
| Ubuntu 19.04                 | 15        | 0.76%   |
| Pop!_OS 20.10                | 15        | 0.76%   |
| openSUSE Tumbleweed-XXXXXXXX | 15        | 0.76%   |
| Linux Mint 20.3              | 15        | 0.76%   |
| Linux Mint 20.2              | 15        | 0.76%   |
| Fedora 34                    | 15        | 0.76%   |
| Endless 3.8.6                | 15        | 0.76%   |
| Endless 3.8.0                | 15        | 0.76%   |
| Ubuntu 22.10                 | 14        | 0.71%   |
| Linux Mint 20.1              | 14        | 0.71%   |
| Fedora 36                    | 14        | 0.71%   |
| ROSA R9                      | 13        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 502       | 27.43%  |
| Endless       | 250       | 13.66%  |
| OpenMandriva  | 144       | 7.87%   |
| Linux Mint    | 107       | 5.85%   |
| Fedora        | 100       | 5.46%   |
| Pop!_OS       | 88        | 4.81%   |
| ROSA          | 66        | 3.61%   |
| BlackPanther  | 63        | 3.44%   |
| Manjaro       | 61        | 3.33%   |
| Debian        | 54        | 2.95%   |
| Arch          | 54        | 2.95%   |
| Zorin         | 49        | 2.68%   |
| KDE neon      | 33        | 1.8%    |
| Xubuntu       | 23        | 1.26%   |
| ArcoLinux     | 23        | 1.26%   |
| Kubuntu       | 22        | 1.2%    |
| openSUSE      | 19        | 1.04%   |
| Clear Linux   | 14        | 0.77%   |
| Ubuntu Unity  | 13        | 0.71%   |
| Kali          | 12        | 0.66%   |
| Gentoo        | 11        | 0.6%    |
| Elementary    | 10        | 0.55%   |
| Ubuntu MATE   | 9         | 0.49%   |
| SteamOS       | 8         | 0.44%   |
| EndeavourOS   | 8         | 0.44%   |
| Peppermint    | 7         | 0.38%   |
| Garuda Linux  | 7         | 0.38%   |
| MX            | 6         | 0.33%   |
| Linux Lite    | 6         | 0.33%   |
| Lubuntu       | 5         | 0.27%   |
| LMDE          | 5         | 0.27%   |
| Xero          | 4         | 0.22%   |
| Ubuntu Budgie | 4         | 0.22%   |
| Raspbian      | 4         | 0.22%   |
| Nobara        | 4         | 0.22%   |
| CentOS        | 4         | 0.22%   |
| Artix         | 4         | 0.22%   |
| Solus         | 3         | 0.16%   |
| Ubuntu Studio | 2         | 0.11%   |
| RHEL          | 2         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-14-generic                | 70        | 3.35%   |
| 5.4.0-42-generic                | 50        | 2.39%   |
| 4.18.16-desktop-1bP             | 47        | 2.25%   |
| 5.10.14-desktop-1omv4002        | 44        | 2.1%    |
| 5.16.7-desktop-1omv4003         | 38        | 1.82%   |
| 5.4.0-19-generic                | 32        | 1.53%   |
| 5.3.0-28-generic                | 26        | 1.24%   |
| 5.3.0-23-generic                | 18        | 0.86%   |
| 5.11.0-35-generic               | 18        | 0.86%   |
| 6.1.1-desktop-1omv2290          | 17        | 0.81%   |
| 4.18.0-15-generic               | 17        | 0.81%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 16        | 0.77%   |
| 5.0.0-25-generic                | 15        | 0.72%   |
| 6.2.6-desktop-1omv2390          | 14        | 0.67%   |
| 5.6.14-desktop-2bP              | 14        | 0.67%   |
| 5.4.0-40-generic                | 14        | 0.67%   |
| 5.15.0-58-generic               | 14        | 0.67%   |
| 5.3.0-46-generic                | 13        | 0.62%   |
| 5.0.0-20-generic                | 12        | 0.57%   |
| 5.4.0-52-generic                | 11        | 0.53%   |
| 5.4.0-29-generic                | 11        | 0.53%   |
| 5.4.0-26-generic                | 11        | 0.53%   |
| 5.3.0-19-generic                | 11        | 0.53%   |
| 5.15.0-52-generic               | 11        | 0.53%   |
| 5.4.0-56-generic                | 10        | 0.48%   |
| 5.4.0-54-generic                | 10        | 0.48%   |
| 5.15.0-56-generic               | 10        | 0.48%   |
| 5.13.0-28-generic               | 10        | 0.48%   |
| 5.11.0-7620-generic             | 10        | 0.48%   |
| 5.11.0-43-generic               | 10        | 0.48%   |
| 5.0.0-37-generic                | 10        | 0.48%   |
| 4.15.0-15-generic               | 10        | 0.48%   |
| 5.8.0-50-generic                | 9         | 0.43%   |
| 5.4.0-7634-generic              | 9         | 0.43%   |
| 5.4.0-74-generic                | 9         | 0.43%   |
| 5.4.0-66-generic                | 9         | 0.43%   |
| 5.4.0-47-generic                | 9         | 0.43%   |
| 5.4.0-37-generic                | 9         | 0.43%   |
| 5.4.0-31-generic                | 9         | 0.43%   |
| 5.3.0-51-generic                | 9         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 305       | 15.23%  |
| 5.8.0   | 151       | 7.54%   |
| 5.15.0  | 133       | 6.64%   |
| 5.3.0   | 117       | 5.84%   |
| 5.11.0  | 101       | 5.04%   |
| 4.15.0  | 97        | 4.84%   |
| 5.0.0   | 80        | 3.99%   |
| 5.13.0  | 68        | 3.39%   |
| 4.18.0  | 52        | 2.6%    |
| 5.19.0  | 50        | 2.5%    |
| 4.18.16 | 47        | 2.35%   |
| 5.10.14 | 45        | 2.25%   |
| 5.10.0  | 39        | 1.95%   |
| 5.16.7  | 38        | 1.9%    |
| 6.1.1   | 20        | 1%      |
| 6.2.6   | 19        | 0.95%   |
| 4.9.60  | 18        | 0.9%    |
| 6.2.0   | 17        | 0.85%   |
| 5.6.14  | 15        | 0.75%   |
| 4.9.20  | 15        | 0.75%   |
| 6.3.5   | 11        | 0.55%   |
| 6.1.0   | 11        | 0.55%   |
| 4.19.0  | 11        | 0.55%   |
| 6.1.12  | 10        | 0.5%    |
| 4.13.0  | 10        | 0.5%    |
| 5.16.13 | 9         | 0.45%   |
| 4.9.76  | 8         | 0.4%    |
| 6.0.11  | 7         | 0.35%   |
| 5.8.18  | 7         | 0.35%   |
| 6.0.0   | 6         | 0.3%    |
| 5.18.10 | 6         | 0.3%    |
| 5.17.0  | 6         | 0.3%    |
| 6.4.11  | 5         | 0.25%   |
| 6.0.6   | 5         | 0.25%   |
| 6.0.12  | 5         | 0.25%   |
| 5.9.16  | 5         | 0.25%   |
| 5.9.0   | 5         | 0.25%   |
| 5.18.12 | 5         | 0.25%   |
| 5.18.0  | 5         | 0.25%   |
| 5.15.8  | 5         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 327       | 16.52%  |
| 5.15    | 180       | 9.09%   |
| 5.8     | 178       | 8.99%   |
| 5.3     | 127       | 6.41%   |
| 5.11    | 115       | 5.81%   |
| 5.10    | 107       | 5.4%    |
| 4.18    | 101       | 5.1%    |
| 4.15    | 97        | 4.9%    |
| 5.0     | 85        | 4.29%   |
| 5.13    | 75        | 3.79%   |
| 5.16    | 71        | 3.59%   |
| 5.19    | 69        | 3.48%   |
| 6.1     | 61        | 3.08%   |
| 6.2     | 51        | 2.58%   |
| 4.9     | 50        | 2.53%   |
| 6.0     | 36        | 1.82%   |
| 5.6     | 29        | 1.46%   |
| 5.18    | 26        | 1.31%   |
| 6.3     | 23        | 1.16%   |
| 5.9     | 22        | 1.11%   |
| 5.17    | 22        | 1.11%   |
| 5.14    | 19        | 0.96%   |
| 6.4     | 18        | 0.91%   |
| 5.12    | 18        | 0.91%   |
| 4.19    | 14        | 0.71%   |
| 5.7     | 10        | 0.51%   |
| 4.13    | 10        | 0.51%   |
| 4.1     | 8         | 0.4%    |
| 5.5     | 7         | 0.35%   |
| 5.2     | 5         | 0.25%   |
| 6.5     | 4         | 0.2%    |
| 5.1     | 4         | 0.2%    |
| 4.8     | 3         | 0.15%   |
| 4.12    | 2         | 0.1%    |
| 4.4     | 1         | 0.05%   |
| 4.17    | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.14    | 1         | 0.05%   |
| 3.10    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1721      | 97.56%  |
| i686    | 34        | 1.93%   |
| armv7l  | 5         | 0.28%   |
| aarch64 | 4         | 0.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 861       | 46.87%  |
| KDE5             | 353       | 19.22%  |
| Unknown          | 225       | 12.25%  |
| XFCE             | 104       | 5.66%   |
| X-Cinnamon       | 77        | 4.19%   |
| KDE4             | 44        | 2.4%    |
| KDE              | 39        | 2.12%   |
| MATE             | 28        | 1.52%   |
| LXQt             | 16        | 0.87%   |
| Cinnamon         | 14        | 0.76%   |
| Unity            | 13        | 0.71%   |
| LXDE             | 13        | 0.71%   |
| i3               | 9         | 0.49%   |
| Pantheon         | 8         | 0.44%   |
| Budgie           | 5         | 0.27%   |
| sway             | 3         | 0.16%   |
| Openbox          | 3         | 0.16%   |
| GNOME Classic    | 3         | 0.16%   |
| Deepin           | 3         | 0.16%   |
| xmonad           | 2         | 0.11%   |
| Hyprland         | 2         | 0.11%   |
| GNOME Flashback  | 2         | 0.11%   |
| awesome          | 2         | 0.11%   |
| sussy_bspwm      | 1         | 0.05%   |
| qtile            | 1         | 0.05%   |
| lightdm-xsession | 1         | 0.05%   |
| jwm              | 1         | 0.05%   |
| GNUstep          | 1         | 0.05%   |
| GNOME-Flashback  | 1         | 0.05%   |
| dusk             | 1         | 0.05%   |
| bspwm            | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1400      | 77.48%  |
| Wayland     | 232       | 12.84%  |
| Unknown     | 148       | 8.19%   |
| Tty         | 26        | 1.44%   |
| Unspecified | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 976       | 53.16%  |
| SDDM    | 314       | 17.1%   |
| GDM     | 173       | 9.42%   |
| GDM3    | 155       | 8.44%   |
| LightDM | 123       | 6.7%    |
| KDM     | 44        | 2.4%    |
| TDM     | 41        | 2.23%   |
| XDM     | 4         | 0.22%   |
| SLiM    | 3         | 0.16%   |
| Ly      | 1         | 0.05%   |
| LXDM    | 1         | 0.05%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1076      | 59.25%  |
| Unknown     | 312       | 17.18%  |
| ro_RO       | 307       | 16.91%  |
| en_GB       | 37        | 2.04%   |
| C           | 27        | 1.49%   |
| hu_HU       | 15        | 0.83%   |
| it_IT       | 10        | 0.55%   |
| es_ES       | 7         | 0.39%   |
| de_DE       | 4         | 0.22%   |
| fr_FR       | 3         | 0.17%   |
| en_IL       | 3         | 0.17%   |
| ru_RU       | 2         | 0.11%   |
| en_IN       | 2         | 0.11%   |
| en_AG       | 2         | 0.11%   |
| nl_NL       | 1         | 0.06%   |
| fr_CH       | 1         | 0.06%   |
| es_MX       | 1         | 0.06%   |
| en_US.UTF8  | 1         | 0.06%   |
| en_US.utf-8 | 1         | 0.06%   |
| en_DE       | 1         | 0.06%   |
| en_CA       | 1         | 0.06%   |
| en_001      | 1         | 0.06%   |
| C.UTF8      | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 916       | 50.97%  |
| BIOS | 881       | 49.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1304      | 71.89%  |
| Overlay | 180       | 9.92%   |
| Unknown | 154       | 8.49%   |
| Btrfs   | 124       | 6.84%   |
| Tmpfs   | 21        | 1.16%   |
| Xfs     | 17        | 0.94%   |
| Zfs     | 6         | 0.33%   |
| F2fs    | 3         | 0.17%   |
| Ext2    | 3         | 0.17%   |
| Jfs     | 1         | 0.06%   |
| Ext3    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1008      | 56.03%  |
| GPT     | 551       | 30.63%  |
| MBR     | 240       | 13.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1555      | 86.58%  |
| Yes       | 241       | 13.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1310      | 72.86%  |
| Yes       | 488       | 27.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 454       | 25.77%  |
| Lenovo                  | 281       | 15.95%  |
| Hewlett-Packard         | 209       | 11.86%  |
| Dell                    | 203       | 11.52%  |
| Acer                    | 133       | 7.55%   |
| Gigabyte Technology     | 130       | 7.38%   |
| MSI                     | 80        | 4.54%   |
| ASRock                  | 47        | 2.67%   |
| Toshiba                 | 25        | 1.42%   |
| Intel                   | 15        | 0.85%   |
| Fujitsu Siemens         | 14        | 0.79%   |
| Apple                   | 13        | 0.74%   |
| Complet                 | 12        | 0.68%   |
| Unknown                 | 11        | 0.62%   |
| Sony                    | 10        | 0.57%   |
| Fujitsu                 | 10        | 0.57%   |
| Medion                  | 9         | 0.51%   |
| Raspberry Pi Foundation | 8         | 0.45%   |
| HUAWEI                  | 8         | 0.45%   |
| Valve                   | 7         | 0.4%    |
| Samsung Electronics     | 7         | 0.4%    |
| Allview                 | 7         | 0.4%    |
| Pegatron                | 6         | 0.34%   |
| Foxconn                 | 6         | 0.34%   |
| Chuwi                   | 5         | 0.28%   |
| Packard Bell            | 4         | 0.23%   |
| Alienware               | 3         | 0.17%   |
| TUXEDO                  | 2         | 0.11%   |
| Timi                    | 2         | 0.11%   |
| Supermicro              | 2         | 0.11%   |
| IBM                     | 2         | 0.11%   |
| AMI                     | 2         | 0.11%   |
| ZOTAC                   | 1         | 0.06%   |
| WEIGO                   | 1         | 0.06%   |
| Visual Fan              | 1         | 0.06%   |
| VALE                    | 1         | 0.06%   |
| Thomson                 | 1         | 0.06%   |
| SLIMBOOK                | 1         | 0.06%   |
| Razer                   | 1         | 0.06%   |
| Prestigio               | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS X541NA                                | 17        | 0.96%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 17        | 0.96%   |
| Unknown                                    | 14        | 0.79%   |
| ASUS All Series                            | 13        | 0.74%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 10        | 0.57%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA     | 9         | 0.51%   |
| Acer Veriton L670G                         | 9         | 0.51%   |
| Valve Jupiter                              | 7         | 0.4%    |
| Gigabyte B450M DS3H                        | 7         | 0.4%    |
| Dell XPS 15 9530                           | 7         | 0.4%    |
| Complet MY8312                             | 7         | 0.4%    |
| ASUS X406UAR                               | 7         | 0.4%    |
| Lenovo Legion Y530-15ICH 81FV              | 6         | 0.34%   |
| ASUS X541UVK                               | 6         | 0.34%   |
| ASUS X541UAK                               | 6         | 0.34%   |
| ASUS VivoBook_ASUSLaptop X509FB_X509FB     | 6         | 0.34%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_A540MA | 6         | 0.34%   |
| Lenovo V330-15IKB 81AX                     | 5         | 0.28%   |
| HP Notebook                                | 5         | 0.28%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 5         | 0.28%   |
| ASUS VivoBook_ASUS Laptop X505ZA_A505ZA    | 5         | 0.28%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 5         | 0.28%   |
| ASUS PRIME A320M-K                         | 5         | 0.28%   |
| ASUS GL552JX                               | 5         | 0.28%   |
| Allview Allbook H                          | 5         | 0.28%   |
| Acer Aspire A315-21G                       | 5         | 0.28%   |
| MSI MS-7996                                | 4         | 0.23%   |
| MSI MS-7721                                | 4         | 0.23%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 4         | 0.23%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 4         | 0.23%   |
| Lenovo G510 20238                          | 4         | 0.23%   |
| Gigabyte X470 AORUS ULTRA GAMING           | 4         | 0.23%   |
| Dell OptiPlex 7010                         | 4         | 0.23%   |
| Dell Latitude E6410                        | 4         | 0.23%   |
| Dell Inspiron 5558                         | 4         | 0.23%   |
| Dell Inspiron 1545                         | 4         | 0.23%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.23%   |
| ASUS X542UAR                               | 4         | 0.23%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA     | 4         | 0.23%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA     | 4         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUS VivoBook           | 119       | 6.75%   |
| Lenovo ThinkPad         | 84        | 4.77%   |
| Lenovo IdeaPad          | 84        | 4.77%   |
| Acer Aspire             | 82        | 4.65%   |
| Dell Latitude           | 55        | 3.12%   |
| Dell Inspiron           | 52        | 2.95%   |
| HP Compaq               | 35        | 1.99%   |
| ASUS PRIME              | 32        | 1.82%   |
| HP ProBook              | 30        | 1.7%    |
| HP EliteBook            | 30        | 1.7%    |
| Dell OptiPlex           | 30        | 1.7%    |
| ASUS ROG                | 30        | 1.7%    |
| Lenovo Legion           | 25        | 1.42%   |
| Toshiba Satellite       | 24        | 1.36%   |
| HP Pavilion             | 24        | 1.36%   |
| Dell XPS                | 19        | 1.08%   |
| ASUS ASUS               | 19        | 1.08%   |
| Lenovo ThinkCentre      | 17        | 0.96%   |
| HP Laptop               | 17        | 0.96%   |
| ASUS X541NA             | 17        | 0.96%   |
| ASUS TUF                | 17        | 0.96%   |
| Acer Veriton            | 14        | 0.79%   |
| Unknown                 | 14        | 0.79%   |
| Dell Vostro             | 13        | 0.74%   |
| ASUS ZenBook            | 13        | 0.74%   |
| ASUS All                | 13        | 0.74%   |
| Dell Precision          | 12        | 0.68%   |
| Lenovo ThinkBook        | 10        | 0.57%   |
| HP 250                  | 10        | 0.57%   |
| Gigabyte B450M          | 9         | 0.51%   |
| Fujitsu Siemens ESPRIMO | 9         | 0.51%   |
| Acer Nitro              | 9         | 0.51%   |
| RPi Raspberry           | 8         | 0.45%   |
| Lenovo Yoga             | 8         | 0.45%   |
| Valve Jupiter           | 7         | 0.4%    |
| HP ZBook                | 7         | 0.4%    |
| Complet MY8312          | 7         | 0.4%    |
| ASUS X406UAR            | 7         | 0.4%    |
| Allview Allbook         | 7         | 0.4%    |
| Acer Swift              | 7         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 219       | 12.43%  |
| 2018    | 202       | 11.46%  |
| 2020    | 151       | 8.57%   |
| 2017    | 148       | 8.4%    |
| 2013    | 114       | 6.47%   |
| 2015    | 113       | 6.41%   |
| 2021    | 112       | 6.36%   |
| 2012    | 96        | 5.45%   |
| 2011    | 95        | 5.39%   |
| 2014    | 89        | 5.05%   |
| 2010    | 81        | 4.6%    |
| 2008    | 75        | 4.26%   |
| 2016    | 74        | 4.2%    |
| 2009    | 57        | 3.23%   |
| 2007    | 56        | 3.18%   |
| 2022    | 43        | 2.44%   |
| 2006    | 18        | 1.02%   |
| Unknown | 9         | 0.51%   |
| 2005    | 5         | 0.28%   |
| 2023    | 3         | 0.17%   |
| 2004    | 2         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1147      | 65.1%   |
| Desktop        | 535       | 30.36%  |
| All in one     | 22        | 1.25%   |
| Convertible    | 17        | 0.96%   |
| Mini pc        | 16        | 0.91%   |
| Tablet         | 9         | 0.51%   |
| System on chip | 8         | 0.45%   |
| Server         | 8         | 0.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1682      | 94.81%  |
| Enabled  | 92        | 5.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1762      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 482       | 26.84%  |
| 4.01-8.0        | 418       | 23.27%  |
| 8.01-16.0       | 320       | 17.82%  |
| 16.01-24.0      | 291       | 16.2%   |
| 32.01-64.0      | 122       | 6.79%   |
| 1.01-2.0        | 74        | 4.12%   |
| 64.01-256.0     | 37        | 2.06%   |
| 24.01-32.0      | 19        | 1.06%   |
| 2.01-3.0        | 17        | 0.95%   |
| 0.51-1.0        | 15        | 0.84%   |
| More than 256.0 | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 737       | 37.39%  |
| 2.01-3.0    | 500       | 25.37%  |
| 3.01-4.0    | 226       | 11.47%  |
| 4.01-8.0    | 200       | 10.15%  |
| 0.51-1.0    | 192       | 9.74%   |
| 8.01-16.0   | 64        | 3.25%   |
| 0.01-0.5    | 41        | 2.08%   |
| 16.01-24.0  | 5         | 0.25%   |
| 32.01-64.0  | 2         | 0.1%    |
| 24.01-32.0  | 2         | 0.1%    |
| 64.01-256.0 | 2         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1181      | 65.03%  |
| 2      | 412       | 22.69%  |
| 3      | 115       | 6.33%   |
| 4      | 48        | 2.64%   |
| 5      | 24        | 1.32%   |
| 0      | 14        | 0.77%   |
| 6      | 6         | 0.33%   |
| 9      | 4         | 0.22%   |
| 7      | 4         | 0.22%   |
| 8      | 3         | 0.17%   |
| 24     | 1         | 0.06%   |
| 15     | 1         | 0.06%   |
| 14     | 1         | 0.06%   |
| 11     | 1         | 0.06%   |
| 10     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1093      | 61.54%  |
| Yes       | 683       | 38.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1458      | 82.65%  |
| No        | 306       | 17.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1356      | 76.44%  |
| No        | 418       | 23.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1099      | 61.6%   |
| No        | 685       | 38.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Romania | 1762      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Bucharest             | 563       | 30.04%  |
| Cluj-Napoca           | 129       | 6.88%   |
| Iasi                  | 89        | 4.75%   |
| Timișoara            | 70        | 3.74%   |
| Târgu Mureş         | 56        | 2.99%   |
| Brasov                | 54        | 2.88%   |
| Ploieşti             | 42        | 2.24%   |
| Constanța            | 38        | 2.03%   |
| Sibiu                 | 35        | 1.87%   |
| Oradea                | 33        | 1.76%   |
| Piteşti              | 30        | 1.6%    |
| Arad                  | 28        | 1.49%   |
| Craiova               | 25        | 1.33%   |
| Popesti-Leordeni      | 21        | 1.12%   |
| Baia Mare             | 21        | 1.12%   |
| Galati                | 20        | 1.07%   |
| Voluntari             | 18        | 0.96%   |
| Zalău                | 17        | 0.91%   |
| Bacau                 | 16        | 0.85%   |
| Râmnicu Vâlcea      | 15        | 0.8%    |
| Targoviste            | 14        | 0.75%   |
| Satu Mare             | 14        | 0.75%   |
| Miercurea-Ciuc        | 14        | 0.75%   |
| Piatra Neamţ         | 13        | 0.69%   |
| Botosani              | 13        | 0.69%   |
| Reşiţa              | 11        | 0.59%   |
| Focşani              | 11        | 0.59%   |
| Floresti              | 11        | 0.59%   |
| Braila                | 11        | 0.59%   |
| Drobeta-Turnu Severin | 10        | 0.53%   |
| Alba Iulia            | 10        | 0.53%   |
| Tulcea                | 9         | 0.48%   |
| Târgu Jiu            | 9         | 0.48%   |
| Mediaş               | 9         | 0.48%   |
| Sfantu Gheorghe       | 8         | 0.43%   |
| Deva                  | 8         | 0.43%   |
| Beiuș                | 8         | 0.43%   |
| Alexandria            | 8         | 0.43%   |
| Sighetu Marmaţiei    | 7         | 0.37%   |
| Buzau                 | 7         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 377       | 549    | 15.1%   |
| Seagate                     | 365       | 574    | 14.62%  |
| Samsung Electronics         | 326       | 447    | 13.06%  |
| Kingston                    | 296       | 406    | 11.86%  |
| Toshiba                     | 170       | 213    | 6.81%   |
| SanDisk                     | 93        | 113    | 3.73%   |
| A-DATA Technology           | 91        | 113    | 3.65%   |
| Unknown                     | 90        | 119    | 3.61%   |
| Intel                       | 84        | 104    | 3.37%   |
| SK hynix                    | 73        | 96     | 2.92%   |
| Hitachi                     | 66        | 85     | 2.64%   |
| HGST                        | 61        | 78     | 2.44%   |
| Micron Technology           | 44        | 54     | 1.76%   |
| Crucial                     | 36        | 46     | 1.44%   |
| Patriot                     | 22        | 26     | 0.88%   |
| Kingston Technology Company | 17        | 19     | 0.68%   |
| Phison                      | 16        | 19     | 0.64%   |
| Maxtor                      | 16        | 23     | 0.64%   |
| SPCC                        | 15        | 18     | 0.6%    |
| KIOXIA                      | 14        | 14     | 0.56%   |
| Hewlett-Packard             | 13        | 15     | 0.52%   |
| OCZ                         | 10        | 20     | 0.4%    |
| XPG                         | 9         | 13     | 0.36%   |
| FORESEE                     | 9         | 10     | 0.36%   |
| Corsair                     | 9         | 17     | 0.36%   |
| Transcend                   | 8         | 10     | 0.32%   |
| Silicon Motion              | 7         | 8      | 0.28%   |
| Realtek Semiconductor       | 7         | 8      | 0.28%   |
| Phison Electronics          | 7         | 7      | 0.28%   |
| Netac                       | 7         | 9      | 0.28%   |
| Kingmax                     | 7         | 8      | 0.28%   |
| Gigabyte Technology         | 7         | 9      | 0.28%   |
| Fujitsu                     | 7         | 8      | 0.28%   |
| China                       | 7         | 7      | 0.28%   |
| GOODRAM                     | 6         | 6      | 0.24%   |
| ASMT                        | 6         | 6      | 0.24%   |
| Apple                       | 6         | 9      | 0.24%   |
| Team                        | 5         | 5      | 0.2%    |
| Plextor                     | 5         | 6      | 0.2%    |
| Verbatim                    | 4         | 6      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 71        | 2.64%   |
| Toshiba MQ01ABF050 500GB                            | 45        | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB                      | 45        | 1.67%   |
| Kingston SA400S37480G 480GB SSD                     | 33        | 1.23%   |
| Seagate ST500LT012-1DG142 500GB                     | 30        | 1.12%   |
| Kingston SA400S37120G 120GB SSD                     | 30        | 1.12%   |
| Seagate ST1000DM010-2EP102 1TB                      | 26        | 0.97%   |
| Kingston SV300S37A120G 120GB SSD                    | 23        | 0.86%   |
| Toshiba MQ04ABF100 1TB                              | 22        | 0.82%   |
| Unknown MMC Card  32GB                              | 21        | 0.78%   |
| Samsung NVMe SSD Drive 512GB                        | 21        | 0.78%   |
| HGST HTS721010A9E630 1TB                            | 20        | 0.74%   |
| Samsung SSD 860 EVO 500GB                           | 19        | 0.71%   |
| Samsung SSD 850 EVO 250GB                           | 19        | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 18        | 0.67%   |
| SanDisk NVMe SSD Drive 256GB                        | 18        | 0.67%   |
| SanDisk NVMe SSD Drive 512GB                        | 17        | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 16        | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 15        | 0.56%   |
| Kingston SV300S37A240G 240GB SSD                    | 15        | 0.56%   |
| Toshiba MQ01ABD100 1TB                              | 14        | 0.52%   |
| Seagate ST500DM002-1BD142 500GB                     | 14        | 0.52%   |
| A-DATA SU650 240GB SSD                              | 14        | 0.52%   |
| Kingston SUV400S37120G 120GB SSD                    | 13        | 0.48%   |
| SK hynix NVMe SSD Drive 512GB                       | 12        | 0.45%   |
| Seagate Expansion 2TB                               | 12        | 0.45%   |
| Patriot Burst 120GB SSD                             | 12        | 0.45%   |
| Intel NVMe SSD Drive 512GB                          | 12        | 0.45%   |
| Toshiba DT01ACA050 500GB                            | 11        | 0.41%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 11        | 0.41%   |
| Samsung SSD 860 EVO 250GB                           | 11        | 0.41%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 11        | 0.41%   |
| HGST HTS545050A7E680 500GB                          | 11        | 0.41%   |
| Unknown MMC Card  64GB                              | 10        | 0.37%   |
| HGST HTS541010A9E680 1TB                            | 10        | 0.37%   |
| WDC WD1600AAJS-22L7A0 160GB                         | 9         | 0.33%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 9         | 0.33%   |
| Kingston RBUSNS8180DS3256GJ 256GB SSD               | 9         | 0.33%   |
| Kingston RBUSC180DS37256GJ 256GB SSD                | 9         | 0.33%   |
| A-DATA SU630 240GB SSD                              | 9         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 360       | 565    | 35.19%  |
| WDC                 | 313       | 469    | 30.6%   |
| Toshiba             | 145       | 181    | 14.17%  |
| Hitachi             | 66        | 85     | 6.45%   |
| HGST                | 61        | 78     | 5.96%   |
| Samsung Electronics | 33        | 41     | 3.23%   |
| Maxtor              | 15        | 22     | 1.47%   |
| Unknown             | 8         | 9      | 0.78%   |
| Fujitsu             | 7         | 8      | 0.68%   |
| Apple               | 3         | 4      | 0.29%   |
| LaCie               | 2         | 8      | 0.2%    |
| IBM/Hitachi         | 2         | 2      | 0.2%    |
| Hewlett-Packard     | 2         | 3      | 0.2%    |
| Intenso             | 1         | 1      | 0.1%    |
| HGST HTS            | 1         | 1      | 0.1%    |
| External            | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 1      | 0.1%    |
| ASMT109x            | 1         | 1      | 0.1%    |
| ASMT                | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 258       | 347    | 30.94%  |
| Samsung Electronics | 137       | 189    | 16.43%  |
| A-DATA Technology   | 85        | 107    | 10.19%  |
| SanDisk             | 42        | 56     | 5.04%   |
| Crucial             | 32        | 42     | 3.84%   |
| WDC                 | 29        | 33     | 3.48%   |
| Intel               | 28        | 31     | 3.36%   |
| SK hynix            | 24        | 32     | 2.88%   |
| Patriot             | 21        | 25     | 2.52%   |
| Micron Technology   | 18        | 20     | 2.16%   |
| SPCC                | 15        | 18     | 1.8%    |
| Toshiba             | 10        | 11     | 1.2%    |
| OCZ                 | 10        | 20     | 1.2%    |
| Hewlett-Packard     | 9         | 9      | 1.08%   |
| FORESEE             | 9         | 10     | 1.08%   |
| Transcend           | 7         | 9      | 0.84%   |
| Netac               | 7         | 9      | 0.84%   |
| Kingmax             | 7         | 8      | 0.84%   |
| Corsair             | 7         | 14     | 0.84%   |
| China               | 7         | 7      | 0.84%   |
| GOODRAM             | 6         | 6      | 0.72%   |
| Gigabyte Technology | 6         | 8      | 0.72%   |
| Team                | 5         | 5      | 0.6%    |
| ASMT                | 5         | 5      | 0.6%    |
| Verbatim            | 4         | 6      | 0.48%   |
| Emtec               | 4         | 4      | 0.48%   |
| Apacer              | 4         | 5      | 0.48%   |
| TO Exter            | 3         | 6      | 0.36%   |
| PNY                 | 3         | 4      | 0.36%   |
| LITEON              | 3         | 3      | 0.36%   |
| Teclast             | 2         | 2      | 0.24%   |
| Seagate             | 2         | 2      | 0.24%   |
| MicroFrom           | 2         | 2      | 0.24%   |
| LITEONIT            | 2         | 2      | 0.24%   |
| Lite-On             | 2         | 2      | 0.24%   |
| Intenso             | 2         | 2      | 0.24%   |
| Wibtek              | 1         | 1      | 0.12%   |
| W800S               | 1         | 1      | 0.12%   |
| Unknown             | 1         | 1      | 0.12%   |
| OCZ-VERTEX3         | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 885       | 1481   | 39.44%  |
| SSD     | 743       | 1084   | 33.11%  |
| NVMe    | 521       | 708    | 23.22%  |
| MMC     | 78        | 103    | 3.48%   |
| Unknown | 17        | 22     | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1319      | 2469   | 66.12%  |
| NVMe | 520       | 707    | 26.07%  |
| SAS  | 78        | 119    | 3.91%   |
| MMC  | 78        | 103    | 3.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1032      | 1647   | 63.51%  |
| 0.51-1.0   | 444       | 611    | 27.32%  |
| 1.01-2.0   | 93        | 159    | 5.72%   |
| 3.01-4.0   | 22        | 44     | 1.35%   |
| 4.01-10.0  | 16        | 50     | 0.98%   |
| 2.01-3.0   | 15        | 49     | 0.92%   |
| 10.01-20.0 | 3         | 5      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 521       | 27.68%  |
| 251-500        | 414       | 22%     |
| 501-1000       | 292       | 15.52%  |
| 1-20           | 178       | 9.46%   |
| 51-100         | 126       | 6.7%    |
| 1001-2000      | 103       | 5.47%   |
| 21-50          | 82        | 4.36%   |
| Unknown        | 77        | 4.09%   |
| More than 3000 | 48        | 2.55%   |
| 2001-3000      | 41        | 2.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 780       | 40.29%  |
| 21-50          | 380       | 19.63%  |
| 101-250        | 211       | 10.9%   |
| 51-100         | 200       | 10.33%  |
| 251-500        | 116       | 5.99%   |
| 501-1000       | 94        | 4.86%   |
| Unknown        | 77        | 3.98%   |
| 1001-2000      | 50        | 2.58%   |
| More than 3000 | 19        | 0.98%   |
| 2001-3000      | 9         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Hitachi HTS725032A7E630 320GB        | 7         | 7      | 3.32%   |
| HGST HTS541010A9E680 1TB             | 5         | 5      | 2.37%   |
| HGST HTS545050A7E680 500GB           | 4         | 4      | 1.9%    |
| WDC WD5000AAKX-001CA0 500GB          | 3         | 3      | 1.42%   |
| WDC WD3200AAJS-60Z0A0 320GB          | 3         | 6      | 1.42%   |
| Seagate ST9500420AS 500GB            | 3         | 3      | 1.42%   |
| Seagate ST3500312CS 500GB            | 3         | 3      | 1.42%   |
| HGST HTS725050A7E630 500GB           | 3         | 4      | 1.42%   |
| WDC WD5000AADS-00S9B0 500GB          | 2         | 2      | 0.95%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2         | 2      | 0.95%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB | 2         | 2      | 0.95%   |
| Toshiba MQ01ABF050 500GB             | 2         | 2      | 0.95%   |
| Seagate STM3250318AS 250GB           | 2         | 3      | 0.95%   |
| Seagate ST95005620AS 500GB           | 2         | 5      | 0.95%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 0.95%   |
| Seagate ST9160821AS 160GB            | 2         | 2      | 0.95%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 3      | 0.95%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 2      | 0.95%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 2      | 0.95%   |
| Seagate ST3500320AS 500GB            | 2         | 3      | 0.95%   |
| Seagate ST3250318AS 250GB            | 2         | 3      | 0.95%   |
| Seagate ST1000LX015-1U7172 1TB       | 2         | 2      | 0.95%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 2      | 0.95%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 3      | 0.95%   |
| OCZ ARC100 240GB SSD                 | 2         | 2      | 0.95%   |
| Maxtor STM3250310AS 250GB            | 2         | 3      | 0.95%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 2      | 0.95%   |
| Hitachi HTS725032A9A364 320GB        | 2         | 2      | 0.95%   |
| Hitachi HTS545016B9A300 160GB        | 2         | 2      | 0.95%   |
| Hitachi HDS721616PLA380 160GB        | 2         | 2      | 0.95%   |
| Apacer 16GB SATA Flash Drive SSD     | 2         | 3      | 0.95%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 1      | 0.47%   |
| WDC WD7500BPVT-60HXZT3 752GB         | 1         | 2      | 0.47%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 1      | 0.47%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1      | 0.47%   |
| WDC WD5000BPKT-60PK4T0 500GB         | 1         | 2      | 0.47%   |
| WDC WD5000BEVT-60A0RT0 500GB         | 1         | 1      | 0.47%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 1      | 0.47%   |
| WDC WD5000AACS-00G8B1 500GB          | 1         | 7      | 0.47%   |
| WDC WD400EB-00CPF0 40GB              | 1         | 1      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 66     | 25.25%  |
| WDC                 | 47        | 73     | 23.27%  |
| Hitachi             | 24        | 27     | 11.88%  |
| Samsung Electronics | 15        | 17     | 7.43%   |
| HGST                | 15        | 16     | 7.43%   |
| Toshiba             | 11        | 12     | 5.45%   |
| Maxtor              | 6         | 8      | 2.97%   |
| Kingston            | 6         | 7      | 2.97%   |
| SK hynix            | 5         | 5      | 2.48%   |
| Intel               | 3         | 3      | 1.49%   |
| Patriot             | 2         | 2      | 0.99%   |
| OCZ                 | 2         | 2      | 0.99%   |
| Hewlett-Packard     | 2         | 2      | 0.99%   |
| Fujitsu             | 2         | 2      | 0.99%   |
| Apacer              | 2         | 3      | 0.99%   |
| A-DATA Technology   | 2         | 2      | 0.99%   |
| Teclast             | 1         | 1      | 0.5%    |
| SanDisk             | 1         | 1      | 0.5%    |
| Plextor             | 1         | 1      | 0.5%    |
| Micron Technology   | 1         | 1      | 0.5%    |
| LITEONIT            | 1         | 1      | 0.5%    |
| Crucial             | 1         | 1      | 0.5%    |
| Corsair             | 1         | 7      | 0.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 66     | 30.91%  |
| WDC                 | 44        | 70     | 26.67%  |
| Hitachi             | 24        | 27     | 14.55%  |
| HGST                | 15        | 16     | 9.09%   |
| Samsung Electronics | 12        | 14     | 7.27%   |
| Toshiba             | 11        | 12     | 6.67%   |
| Maxtor              | 6         | 8      | 3.64%   |
| Fujitsu             | 2         | 2      | 1.21%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 153       | 215    | 80.53%  |
| SSD  | 36        | 44     | 18.95%  |
| NVMe | 1         | 1      | 0.53%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60KA9T0 320GB | 1         | 1      | 33.33%  |
| WDC WD2500BEVS-22UST0 250GB  | 1         | 1      | 33.33%  |
| Seagate ST3160215A 160GB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1110      | 2025   | 57.48%  |
| Works    | 637       | 1110   | 32.99%  |
| Malfunc  | 181       | 260    | 9.37%   |
| Failed   | 3         | 3      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1284      | 58.76%  |
| AMD                              | 292       | 13.36%  |
| Samsung Electronics              | 176       | 8.05%   |
| SanDisk                          | 88        | 4.03%   |
| Kingston Technology Company      | 60        | 2.75%   |
| SK hynix                         | 48        | 2.2%    |
| Micron Technology                | 26        | 1.19%   |
| Phison Electronics               | 23        | 1.05%   |
| ASMedia Technology               | 23        | 1.05%   |
| ADATA Technology                 | 18        | 0.82%   |
| Toshiba America Info Systems     | 16        | 0.73%   |
| Nvidia                           | 16        | 0.73%   |
| Marvell Technology Group         | 16        | 0.73%   |
| KIOXIA                           | 16        | 0.73%   |
| JMicron Technology               | 15        | 0.69%   |
| Silicon Motion                   | 12        | 0.55%   |
| Realtek Semiconductor            | 12        | 0.55%   |
| Lite-On Technology               | 6         | 0.27%   |
| Silicon Integrated Systems [SiS] | 5         | 0.23%   |
| Micron/Crucial Technology        | 5         | 0.23%   |
| VIA Technologies                 | 4         | 0.18%   |
| Silicon Image                    | 4         | 0.18%   |
| LSI Logic / Symbios Logic        | 4         | 0.18%   |
| Broadcom / LSI                   | 4         | 0.18%   |
| Union Memory (Shenzhen)          | 2         | 0.09%   |
| Solid State Storage Technology   | 2         | 0.09%   |
| Seagate Technology               | 2         | 0.09%   |
| Lenovo                           | 2         | 0.09%   |
| Hewlett-Packard                  | 2         | 0.09%   |
| Integrated Technology Express    | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 214       | 8.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 115       | 4.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 92        | 3.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 79        | 3.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 78        | 3.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 72        | 2.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 63        | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 49        | 1.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 48        | 1.91%   |
| Samsung NVMe SSD Controller 980                                                | 45        | 1.79%   |
| Intel Volume Management Device NVMe RAID Controller                            | 43        | 1.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 42        | 1.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 39        | 1.55%   |
| AMD 400 Series Chipset SATA Controller                                         | 38        | 1.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 37        | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 36        | 1.43%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 32        | 1.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 32        | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 30        | 1.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 29        | 1.15%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 29        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 28        | 1.11%   |
| Kingston Company A2000 NVMe SSD                                                | 27        | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 27        | 1.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 27        | 1.07%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 26        | 1.03%   |
| Intel SSD 660P Series                                                          | 26        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 26        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 25        | 0.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 24        | 0.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 23        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 23        | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 23        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 23        | 0.92%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 22        | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 22        | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 22        | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 22        | 0.88%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 21        | 0.84%   |
| Intel Tiger Lake-LP SATA Controller                                            | 19        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1314      | 58.37%  |
| NVMe | 529       | 23.5%   |
| IDE  | 231       | 10.26%  |
| RAID | 170       | 7.55%   |
| SAS  | 7         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1377      | 78.15%  |
| AMD    | 376       | 21.34%  |
| ARM    | 9         | 0.51%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 43        | 2.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 1.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 27        | 1.53%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 24        | 1.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 20        | 1.13%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 18        | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 0.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 16        | 0.91%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 16        | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 0.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 0.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 0.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.74%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 12        | 0.68%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 12        | 0.68%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.62%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 11        | 0.62%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 11        | 0.62%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 10        | 0.57%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 10        | 0.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 10        | 0.57%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 10        | 0.57%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 10        | 0.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.57%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 0.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 9         | 0.51%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 9         | 0.51%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 9         | 0.51%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 9         | 0.51%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 0.51%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 8         | 0.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.45%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 8         | 0.45%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 0.45%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 0.45%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 0.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 334       | 18.93%  |
| Intel Core i5           | 334       | 18.93%  |
| Intel Core i3           | 182       | 10.32%  |
| Intel Celeron           | 150       | 8.5%    |
| Other                   | 99        | 5.61%   |
| AMD Ryzen 5             | 91        | 5.16%   |
| Intel Core 2 Duo        | 89        | 5.05%   |
| AMD Ryzen 7             | 82        | 4.65%   |
| Intel Pentium           | 54        | 3.06%   |
| AMD Ryzen 3             | 30        | 1.7%    |
| Intel Atom              | 28        | 1.59%   |
| Intel Xeon              | 24        | 1.36%   |
| AMD Ryzen 9             | 24        | 1.36%   |
| Intel Pentium Dual-Core | 21        | 1.19%   |
| AMD A4                  | 18        | 1.02%   |
| Intel Core 2 Quad       | 17        | 0.96%   |
| AMD FX                  | 16        | 0.91%   |
| Intel Core i9           | 14        | 0.79%   |
| Intel Core 2            | 13        | 0.74%   |
| AMD A8                  | 13        | 0.74%   |
| Intel Genuine           | 10        | 0.57%   |
| Intel Pentium Dual      | 9         | 0.51%   |
| AMD Phenom II X4        | 8         | 0.45%   |
| AMD Ryzen 7 PRO         | 6         | 0.34%   |
| AMD E                   | 6         | 0.34%   |
| AMD Athlon              | 6         | 0.34%   |
| AMD Ryzen Threadripper  | 5         | 0.28%   |
| AMD E2                  | 5         | 0.28%   |
| Intel Pentium Silver    | 4         | 0.23%   |
| Intel Celeron M         | 4         | 0.23%   |
| ARM BCM                 | 4         | 0.23%   |
| AMD Sempron             | 4         | 0.23%   |
| AMD Athlon II X4        | 4         | 0.23%   |
| AMD A6                  | 4         | 0.23%   |
| AMD A10                 | 4         | 0.23%   |
| AMD Turion 64 X2 Mobile | 3         | 0.17%   |
| AMD Athlon II X3        | 3         | 0.17%   |
| AMD Athlon 64 X2        | 3         | 0.17%   |
| Intel Pentium Gold      | 2         | 0.11%   |
| Intel Pentium D         | 2         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 776       | 44.02%  |
| 4      | 620       | 35.17%  |
| 6      | 138       | 7.83%   |
| 8      | 127       | 7.2%    |
| 1      | 42        | 2.38%   |
| 12     | 22        | 1.25%   |
| 3      | 10        | 0.57%   |
| 16     | 8         | 0.45%   |
| 10     | 8         | 0.45%   |
| 14     | 5         | 0.28%   |
| 32     | 3         | 0.17%   |
| 24     | 2         | 0.11%   |
| 64     | 1         | 0.06%   |
| 20     | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1749      | 99.26%  |
| 2      | 13        | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1132      | 64.21%  |
| 1      | 629       | 35.68%  |
| 4      | 2         | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1666      | 94.18%  |
| Unknown        | 89        | 5.03%   |
| 32-bit         | 14        | 0.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 394       | 21.62%  |
| 0x306c3    | 87        | 4.77%   |
| 0x206a7    | 87        | 4.77%   |
| 0x306a9    | 79        | 4.34%   |
| 0x1067a    | 62        | 3.4%    |
| 0x806ea    | 61        | 3.35%   |
| 0x906ea    | 56        | 3.07%   |
| 0x806ec    | 54        | 2.96%   |
| 0x706a1    | 51        | 2.8%    |
| 0x906e9    | 44        | 2.41%   |
| 0x40651    | 38        | 2.09%   |
| 0x506e3    | 34        | 1.87%   |
| 0x506c9    | 34        | 1.87%   |
| 0x806e9    | 33        | 1.81%   |
| 0x806c1    | 32        | 1.76%   |
| 0x20655    | 32        | 1.76%   |
| 0x306d4    | 29        | 1.59%   |
| 0x10676    | 25        | 1.37%   |
| 0x806eb    | 24        | 1.32%   |
| 0x406e3    | 24        | 1.32%   |
| 0x0a50000c | 23        | 1.26%   |
| 0x08108109 | 21        | 1.15%   |
| 0x6fd      | 20        | 1.1%    |
| 0x706e5    | 19        | 1.04%   |
| 0x010000c8 | 19        | 1.04%   |
| 0x406c4    | 17        | 0.93%   |
| 0x08108102 | 16        | 0.88%   |
| 0xa0652    | 13        | 0.71%   |
| 0x08701021 | 13        | 0.71%   |
| 0x08600104 | 13        | 0.71%   |
| 0x0810100b | 13        | 0.71%   |
| 0x906ed    | 12        | 0.66%   |
| 0x6fb      | 12        | 0.66%   |
| 0x08600106 | 12        | 0.66%   |
| 0x06001119 | 12        | 0.66%   |
| 0x706a8    | 11        | 0.6%    |
| 0x406c3    | 11        | 0.6%    |
| 0x08701013 | 10        | 0.55%   |
| 0x0800820d | 10        | 0.55%   |
| 0x806d1    | 9         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 348       | 19.69%  |
| Haswell          | 158       | 8.94%   |
| SandyBridge      | 103       | 5.83%   |
| Penryn           | 103       | 5.83%   |
| IvyBridge        | 97        | 5.49%   |
| Skylake          | 74        | 4.19%   |
| Goldmont plus    | 72        | 4.07%   |
| Zen 2            | 71        | 4.02%   |
| Zen+             | 63        | 3.57%   |
| Core             | 60        | 3.4%    |
| Westmere         | 55        | 3.11%   |
| Unknown          | 54        | 3.06%   |
| Silvermont       | 50        | 2.83%   |
| Zen 3            | 49        | 2.77%   |
| TigerLake        | 44        | 2.49%   |
| Broadwell        | 42        | 2.38%   |
| Zen              | 40        | 2.26%   |
| Goldmont         | 39        | 2.21%   |
| CometLake        | 34        | 1.92%   |
| Icelake          | 32        | 1.81%   |
| Piledriver       | 29        | 1.64%   |
| K10              | 29        | 1.64%   |
| Excavator        | 20        | 1.13%   |
| Alderlake Hybrid | 16        | 0.91%   |
| K8 Hammer        | 13        | 0.74%   |
| P6               | 12        | 0.68%   |
| Bonnell          | 11        | 0.62%   |
| Nehalem          | 10        | 0.57%   |
| Bobcat           | 8         | 0.45%   |
| Puma             | 7         | 0.4%    |
| NetBurst         | 6         | 0.34%   |
| K8 & K10 hybrid  | 4         | 0.23%   |
| K10 Llano        | 4         | 0.23%   |
| Jaguar           | 4         | 0.23%   |
| Steamroller      | 3         | 0.17%   |
| Tremont          | 2         | 0.11%   |
| Bulldozer        | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1116      | 51.43%  |
| Nvidia                           | 591       | 27.24%  |
| AMD                              | 448       | 20.65%  |
| Silicon Integrated Systems [SiS] | 5         | 0.23%   |
| Matrox Electronics Systems       | 5         | 0.23%   |
| ASPEED Technology                | 4         | 0.18%   |
| VIA Technologies                 | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 78        | 3.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 69        | 3.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 63        | 2.83%   |
| Intel UHD Graphics 620                                                                   | 60        | 2.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 55        | 2.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 51        | 2.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 46        | 2.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 45        | 2.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 44        | 1.97%   |
| Intel HD Graphics 620                                                                    | 41        | 1.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 40        | 1.79%   |
| Intel HD Graphics 5500                                                                   | 39        | 1.75%   |
| Intel HD Graphics 630                                                                    | 38        | 1.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 36        | 1.61%   |
| AMD Renoir                                                                               | 34        | 1.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 32        | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 32        | 1.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 31        | 1.39%   |
| Intel HD Graphics 530                                                                    | 30        | 1.35%   |
| Intel HD Graphics 500                                                                    | 28        | 1.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 25        | 1.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 24        | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 24        | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 23        | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22        | 0.99%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 21        | 0.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 19        | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 0.76%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 16        | 0.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 0.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 16        | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.67%   |
| Nvidia GP108M [GeForce MX150]                                                            | 15        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.67%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 15        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 0.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 14        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 739       | 41.8%   |
| 1 x AMD        | 319       | 18.04%  |
| Intel + Nvidia | 296       | 16.74%  |
| 1 x Nvidia     | 250       | 14.14%  |
| Intel + AMD    | 60        | 3.39%   |
| AMD + Nvidia   | 44        | 2.49%   |
| 2 x AMD        | 24        | 1.36%   |
| 2 x Intel      | 10        | 0.57%   |
| Other          | 9         | 0.51%   |
| 1 x SiS        | 5         | 0.28%   |
| 1 x Matrox     | 5         | 0.28%   |
| 1 x ASPEED     | 3         | 0.17%   |
| 2 x Nvidia     | 2         | 0.11%   |
| 1 x VIA        | 1         | 0.06%   |
| AMD + ASPEED   | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1396      | 78.34%  |
| Proprietary | 336       | 18.86%  |
| Unknown     | 50        | 2.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1010      | 55.56%  |
| 1.01-2.0   | 249       | 13.7%   |
| 0.01-0.5   | 192       | 10.56%  |
| 3.01-4.0   | 129       | 7.1%    |
| 0.51-1.0   | 117       | 6.44%   |
| 7.01-8.0   | 59        | 3.25%   |
| 5.01-6.0   | 37        | 2.04%   |
| 8.01-16.0  | 11        | 0.61%   |
| 2.01-3.0   | 10        | 0.55%   |
| 16.01-24.0 | 3         | 0.17%   |
| 0          | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 234       | 12.49%  |
| Samsung Electronics     | 231       | 12.33%  |
| Chimei Innolux          | 209       | 11.15%  |
| BOE                     | 200       | 10.67%  |
| LG Display              | 183       | 9.77%   |
| Dell                    | 127       | 6.78%   |
| Goldstar                | 97        | 5.18%   |
| Philips                 | 67        | 3.58%   |
| PANDA                   | 46        | 2.45%   |
| BenQ                    | 42        | 2.24%   |
| Lenovo                  | 37        | 1.97%   |
| Chi Mei Optoelectronics | 35        | 1.87%   |
| AOC                     | 32        | 1.71%   |
| Hewlett-Packard         | 31        | 1.65%   |
| Ancor Communications    | 30        | 1.6%    |
| Acer                    | 30        | 1.6%    |
| Sharp                   | 27        | 1.44%   |
| Fujitsu Siemens         | 21        | 1.12%   |
| ASUSTek Computer        | 16        | 0.85%   |
| LG Philips              | 14        | 0.75%   |
| LG Electronics          | 12        | 0.64%   |
| Unknown                 | 10        | 0.53%   |
| Apple                   | 10        | 0.53%   |
| Sony                    | 9         | 0.48%   |
| CSO                     | 8         | 0.43%   |
| KTC                     | 7         | 0.37%   |
| InfoVision              | 7         | 0.37%   |
| Vestel Elektronik       | 6         | 0.32%   |
| Lenovo Group Limited    | 6         | 0.32%   |
| Eizo                    | 6         | 0.32%   |
| ViewSonic               | 5         | 0.27%   |
| Toshiba                 | 5         | 0.27%   |
| Panasonic               | 5         | 0.27%   |
| LGD                     | 4         | 0.21%   |
| Iiyama                  | 4         | 0.21%   |
| HannStar                | 4         | 0.21%   |
| CPT                     | 4         | 0.21%   |
| Valve                   | 3         | 0.16%   |
| InnoLux Display         | 3         | 0.16%   |
| Belinea                 | 3         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 26        | 1.35%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 24        | 1.25%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 22        | 1.14%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 1.09%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.78%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 13        | 0.67%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 11        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 11        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.57%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 11        | 0.57%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 10        | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.52%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.47%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 9         | 0.47%   |
| Goldstar E2250 GSM578D 1920x1080 477x268mm 21.5-inch                     | 9         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 9         | 0.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 9         | 0.47%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 8         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 8         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 8         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 8         | 0.42%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                  | 7         | 0.36%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 7         | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.36%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 7         | 0.36%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                            | 6         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch    | 6         | 0.31%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 6         | 0.31%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 6         | 0.31%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 6         | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 6         | 0.31%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 6         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.31%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 6         | 0.31%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 829       | 46.06%  |
| 1366x768 (WXGA)    | 392       | 21.78%  |
| 3840x2160 (4K)     | 75        | 4.17%   |
| 1280x1024 (SXGA)   | 75        | 4.17%   |
| 2560x1440 (QHD)    | 60        | 3.33%   |
| 1600x900 (HD+)     | 59        | 3.28%   |
| 1680x1050 (WSXGA+) | 48        | 2.67%   |
| 1280x800 (WXGA)    | 40        | 2.22%   |
| 1920x1200 (WUXGA)  | 31        | 1.72%   |
| 1440x900 (WXGA+)   | 28        | 1.56%   |
| Unknown            | 20        | 1.11%   |
| 1360x768           | 15        | 0.83%   |
| 2880x1800          | 14        | 0.78%   |
| 2560x1080          | 13        | 0.72%   |
| 3440x1440          | 11        | 0.61%   |
| 3200x1800 (QHD+)   | 11        | 0.61%   |
| 2560x1600          | 11        | 0.61%   |
| 1024x600           | 8         | 0.44%   |
| 3840x1080          | 7         | 0.39%   |
| 1024x768 (XGA)     | 7         | 0.39%   |
| 800x1280           | 6         | 0.33%   |
| 2160x1440          | 6         | 0.33%   |
| 5120x1440          | 2         | 0.11%   |
| 3840x2400          | 2         | 0.11%   |
| 3840x1600          | 2         | 0.11%   |
| 1920x540           | 2         | 0.11%   |
| 1600x1200          | 2         | 0.11%   |
| 1400x1050          | 2         | 0.11%   |
| 1280x720 (HD)      | 2         | 0.11%   |
| 800x600            | 1         | 0.06%   |
| 7680x1440          | 1         | 0.06%   |
| 6400x1440          | 1         | 0.06%   |
| 6000x1440          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 4960x1080          | 1         | 0.06%   |
| 3926x1440          | 1         | 0.06%   |
| 3840x2524          | 1         | 0.06%   |
| 3600x1200          | 1         | 0.06%   |
| 3360x1080          | 1         | 0.06%   |
| 3286x1080          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 708       | 38.08%  |
| 14      | 133       | 7.15%   |
| 24      | 119       | 6.4%    |
| 13      | 117       | 6.29%   |
| 17      | 114       | 6.13%   |
| 21      | 107       | 5.76%   |
| 23      | 101       | 5.43%   |
| 27      | 86        | 4.63%   |
| Unknown | 75        | 4.03%   |
| 19      | 53        | 2.85%   |
| 22      | 33        | 1.78%   |
| 18      | 27        | 1.45%   |
| 31      | 26        | 1.4%    |
| 34      | 22        | 1.18%   |
| 12      | 18        | 0.97%   |
| 84      | 15        | 0.81%   |
| 20      | 12        | 0.65%   |
| 16      | 11        | 0.59%   |
| 54      | 10        | 0.54%   |
| 11      | 9         | 0.48%   |
| 10      | 9         | 0.48%   |
| 72      | 6         | 0.32%   |
| 65      | 6         | 0.32%   |
| 40      | 6         | 0.32%   |
| 32      | 6         | 0.32%   |
| 28      | 3         | 0.16%   |
| 26      | 3         | 0.16%   |
| 7       | 3         | 0.16%   |
| 3       | 3         | 0.16%   |
| 52      | 2         | 0.11%   |
| 42      | 2         | 0.11%   |
| 37      | 2         | 0.11%   |
| 29      | 2         | 0.11%   |
| 25      | 2         | 0.11%   |
| 8       | 2         | 0.11%   |
| 142     | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 49      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 46      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 925       | 50.35%  |
| 501-600        | 284       | 15.46%  |
| 401-500        | 189       | 10.29%  |
| 351-400        | 149       | 8.11%   |
| 201-300        | 86        | 4.68%   |
| Unknown        | 75        | 4.08%   |
| 601-700        | 38        | 2.07%   |
| 701-800        | 28        | 1.52%   |
| 1001-1500      | 22        | 1.2%    |
| 1501-2000      | 21        | 1.14%   |
| 801-900        | 8         | 0.44%   |
| 1-100          | 6         | 0.33%   |
| 901-1000       | 3         | 0.16%   |
| 101-200        | 2         | 0.11%   |
| More than 2000 | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1355      | 78.73%  |
| 16/10   | 170       | 9.88%   |
| 5/4     | 67        | 3.89%   |
| Unknown | 65        | 3.78%   |
| 21/9    | 25        | 1.45%   |
| 4/3     | 14        | 0.81%   |
| 3/2     | 12        | 0.7%    |
| 6/5     | 8         | 0.46%   |
| 0.67    | 3         | 0.17%   |
| 32/9    | 1         | 0.06%   |
| 1.00    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 709       | 38.37%  |
| 201-250        | 293       | 15.85%  |
| 81-90          | 209       | 11.31%  |
| 151-200        | 95        | 5.14%   |
| 301-350        | 89        | 4.82%   |
| 121-130        | 79        | 4.27%   |
| Unknown        | 75        | 4.06%   |
| 351-500        | 56        | 3.03%   |
| 141-150        | 46        | 2.49%   |
| More than 1000 | 42        | 2.27%   |
| 251-300        | 39        | 2.11%   |
| 71-80          | 38        | 2.06%   |
| 61-70          | 16        | 0.87%   |
| 501-1000       | 13        | 0.7%    |
| 131-140        | 10        | 0.54%   |
| 51-60          | 9         | 0.49%   |
| 41-50          | 9         | 0.49%   |
| 1-40           | 8         | 0.43%   |
| 111-120        | 8         | 0.43%   |
| 91-100         | 5         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 547       | 30.02%  |
| 101-120       | 538       | 29.53%  |
| 51-100        | 517       | 28.38%  |
| Unknown       | 75        | 4.12%   |
| 161-240       | 73        | 4.01%   |
| More than 240 | 39        | 2.14%   |
| 1-50          | 33        | 1.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1508      | 84.01%  |
| 2     | 203       | 11.31%  |
| 0     | 58        | 3.23%   |
| 3     | 25        | 1.39%   |
| 4     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1009      | 39.08%  |
| Intel                             | 773       | 29.94%  |
| Qualcomm Atheros                  | 306       | 11.85%  |
| Broadcom                          | 137       | 5.31%   |
| TP-Link                           | 54        | 2.09%   |
| MediaTek                          | 50        | 1.94%   |
| Broadcom Limited                  | 27        | 1.05%   |
| Ralink                            | 24        | 0.93%   |
| Marvell Technology Group          | 23        | 0.89%   |
| Ralink Technology                 | 22        | 0.85%   |
| Nvidia                            | 14        | 0.54%   |
| ASUSTek Computer                  | 13        | 0.5%    |
| Huawei Technologies               | 11        | 0.43%   |
| ASIX Electronics                  | 9         | 0.35%   |
| Samsung Electronics               | 8         | 0.31%   |
| D-Link                            | 8         | 0.31%   |
| Xiaomi                            | 7         | 0.27%   |
| Ericsson Business Mobile Networks | 7         | 0.27%   |
| Qualcomm Atheros Communications   | 6         | 0.23%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.19%   |
| Microsoft                         | 5         | 0.19%   |
| Hewlett-Packard                   | 5         | 0.19%   |
| Aquantia                          | 5         | 0.19%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.15%   |
| Lenovo                            | 4         | 0.15%   |
| JMicron Technology                | 4         | 0.15%   |
| Google                            | 4         | 0.15%   |
| VIA Technologies                  | 3         | 0.12%   |
| Standard Microsystems             | 2         | 0.08%   |
| IMC Networks                      | 2         | 0.08%   |
| Giga-Byte Technology              | 2         | 0.08%   |
| Fibocom                           | 2         | 0.08%   |
| Edimax Technology                 | 2         | 0.08%   |
| DisplayLink                       | 2         | 0.08%   |
| Dell                              | 2         | 0.08%   |
| D-Link System                     | 2         | 0.08%   |
| Belkin Components                 | 2         | 0.08%   |
| U-Blox                            | 1         | 0.04%   |
| Texas Instruments                 | 1         | 0.04%   |
| Tenda                             | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 663       | 22.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 127       | 4.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 81        | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 66        | 2.19%   |
| Intel Wireless 8265 / 8275                                        | 62        | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 59        | 1.96%   |
| Intel Wi-Fi 6 AX200                                               | 56        | 1.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 55        | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 51        | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 46        | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 40        | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 39        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 35        | 1.16%   |
| Intel Wi-Fi 6 AX201                                               | 33        | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 1%      |
| Intel I211 Gigabit Network Connection                             | 30        | 1%      |
| Intel Wireless 7260                                               | 28        | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 28        | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 27        | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 27        | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 27        | 0.9%    |
| Intel Wireless 7265                                               | 27        | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 23        | 0.76%   |
| Intel Wireless 8260                                               | 22        | 0.73%   |
| Intel Wireless 3165                                               | 22        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                              | 22        | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 22        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 21        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 20        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.63%   |
| Intel Wireless 3160                                               | 19        | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18        | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                     | 18        | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 0.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 16        | 0.53%   |
| Intel Centrino Advanced-N 6200                                    | 16        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 14        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 580       | 40.82%  |
| Realtek Semiconductor             | 301       | 21.18%  |
| Qualcomm Atheros                  | 248       | 17.45%  |
| Broadcom                          | 89        | 6.26%   |
| TP-Link                           | 46        | 3.24%   |
| MediaTek                          | 44        | 3.1%    |
| Ralink                            | 24        | 1.69%   |
| Ralink Technology                 | 22        | 1.55%   |
| Broadcom Limited                  | 13        | 0.91%   |
| ASUSTek Computer                  | 13        | 0.91%   |
| D-Link                            | 8         | 0.56%   |
| Qualcomm Atheros Communications   | 6         | 0.42%   |
| Microsoft                         | 5         | 0.35%   |
| Ericsson Business Mobile Networks | 4         | 0.28%   |
| IMC Networks                      | 2         | 0.14%   |
| Fibocom                           | 2         | 0.14%   |
| Edimax Technology                 | 2         | 0.14%   |
| Belkin Components                 | 2         | 0.14%   |
| Tenda                             | 1         | 0.07%   |
| Sitecom Europe                    | 1         | 0.07%   |
| Sierra Wireless                   | 1         | 0.07%   |
| Qualcomm                          | 1         | 0.07%   |
| Qcom                              | 1         | 0.07%   |
| NetGear                           | 1         | 0.07%   |
| Micro Star International          | 1         | 0.07%   |
| Mercucys                          | 1         | 0.07%   |
| D-Link System                     | 1         | 0.07%   |
| Belkin                            | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 81        | 5.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 66        | 4.62%   |
| Intel Wireless 8265 / 8275                                              | 62        | 4.34%   |
| Intel Wi-Fi 6 AX200                                                     | 56        | 3.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 55        | 3.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 51        | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 46        | 3.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 40        | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 39        | 2.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 39        | 2.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 35        | 2.45%   |
| Intel Wi-Fi 6 AX201                                                     | 33        | 2.31%   |
| Intel Wireless 7260                                                     | 28        | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 27        | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 1.89%   |
| Intel Wireless 7265                                                     | 27        | 1.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 23        | 1.61%   |
| Intel Wireless 8260                                                     | 22        | 1.54%   |
| Intel Wireless 3165                                                     | 22        | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 21        | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 20        | 1.4%    |
| Intel Wireless 3160                                                     | 19        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 18        | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                           | 18        | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 17        | 1.19%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 16        | 1.12%   |
| Intel Centrino Advanced-N 6200                                          | 16        | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 14        | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 0.77%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 0.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 11        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 10        | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 0.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 9         | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.63%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 9         | 0.63%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 859       | 55.96%  |
| Intel                            | 380       | 24.76%  |
| Qualcomm Atheros                 | 91        | 5.93%   |
| Broadcom                         | 71        | 4.63%   |
| Marvell Technology Group         | 23        | 1.5%    |
| Nvidia                           | 14        | 0.91%   |
| Broadcom Limited                 | 14        | 0.91%   |
| Huawei Technologies              | 9         | 0.59%   |
| ASIX Electronics                 | 9         | 0.59%   |
| TP-Link                          | 8         | 0.52%   |
| Samsung Electronics              | 8         | 0.52%   |
| Xiaomi                           | 7         | 0.46%   |
| MediaTek                         | 6         | 0.39%   |
| Aquantia                         | 5         | 0.33%   |
| Silicon Integrated Systems [SiS] | 4         | 0.26%   |
| Lenovo                           | 4         | 0.26%   |
| JMicron Technology               | 4         | 0.26%   |
| Google                           | 4         | 0.26%   |
| VIA Technologies                 | 3         | 0.2%    |
| Standard Microsystems            | 2         | 0.13%   |
| Giga-Byte Technology             | 2         | 0.13%   |
| DisplayLink                      | 2         | 0.13%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.07%   |
| QLogic                           | 1         | 0.07%   |
| HMD Global                       | 1         | 0.07%   |
| Dell                             | 1         | 0.07%   |
| D-Link System                    | 1         | 0.07%   |
| 3Com                             | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 663       | 42.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 127       | 8.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 59        | 3.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 1.92%   |
| Intel I211 Gigabit Network Connection                             | 30        | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 28        | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 27        | 1.73%   |
| Intel Ethernet Connection (2) I219-V                              | 22        | 1.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 22        | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 1.22%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 1.03%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 0.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 14        | 0.9%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.77%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.58%   |
| Intel Ethernet Controller I225-V                                  | 9         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.51%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8         | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8         | 0.51%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 8         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7         | 0.45%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 7         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.45%   |
| Nvidia MCP61 Ethernet                                             | 7         | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.45%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.45%   |
| Huawei MLA-L11                                                    | 7         | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 6         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1456      | 51.38%  |
| WiFi     | 1354      | 47.78%  |
| Modem    | 19        | 0.67%   |
| Unknown  | 5         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1079      | 58.87%  |
| Ethernet | 753       | 41.08%  |
| Unknown  | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 954       | 54.05%  |
| 1     | 740       | 41.93%  |
| 0     | 36        | 2.04%   |
| 3     | 29        | 1.64%   |
| 4     | 4         | 0.23%   |
| 8     | 1         | 0.06%   |
| 6     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1506      | 83.62%  |
| Yes  | 295       | 16.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 462       | 41.77%  |
| IMC Networks                    | 152       | 13.74%  |
| Realtek Semiconductor           | 135       | 12.21%  |
| Qualcomm Atheros Communications | 74        | 6.69%   |
| Lite-On Technology              | 59        | 5.33%   |
| Broadcom                        | 41        | 3.71%   |
| Cambridge Silicon Radio         | 35        | 3.16%   |
| ASUSTek Computer                | 29        | 2.62%   |
| Foxconn / Hon Hai               | 26        | 2.35%   |
| Dell                            | 19        | 1.72%   |
| Hewlett-Packard                 | 14        | 1.27%   |
| Toshiba                         | 12        | 1.08%   |
| Apple                           | 10        | 0.9%    |
| Ralink                          | 9         | 0.81%   |
| MediaTek                        | 6         | 0.54%   |
| Realtek                         | 3         | 0.27%   |
| Alps Electric                   | 3         | 0.27%   |
| SINO WEALTH                     | 2         | 0.18%   |
| Integrated System Solution      | 2         | 0.18%   |
| Chicony Electronics             | 2         | 0.18%   |
| USI                             | 1         | 0.09%   |
| TP-Link                         | 1         | 0.09%   |
| Ralink Technology               | 1         | 0.09%   |
| Opticis                         | 1         | 0.09%   |
| Micro Star International        | 1         | 0.09%   |
| Foxconn International           | 1         | 0.09%   |
| Edimax Technology               | 1         | 0.09%   |
| Conwise Technology              | 1         | 0.09%   |
| Belkin Components               | 1         | 0.09%   |
| Askey Computer                  | 1         | 0.09%   |
| Accel Semiconductor             | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 186       | 16.82%  |
| Realtek Bluetooth Radio                             | 98        | 8.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 91        | 8.23%   |
| IMC Networks Bluetooth Radio                        | 91        | 8.23%   |
| Intel AX201 Bluetooth                               | 82        | 7.41%   |
| Intel AX200 Bluetooth                               | 55        | 4.97%   |
| Qualcomm Atheros  Bluetooth Device                  | 41        | 3.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 35        | 3.16%   |
| IMC Networks Bluetooth Device                       | 33        | 2.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 26        | 2.35%   |
| IMC Networks Wireless_Device                        | 21        | 1.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 20        | 1.81%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 19        | 1.72%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 13        | 1.18%   |
| Lite-On Bluetooth Device                            | 12        | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 1.08%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 0.99%   |
| Intel Bluetooth Device                              | 11        | 0.99%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 9         | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.81%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.72%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 0.63%   |
| Intel AX210 Bluetooth                               | 7         | 0.63%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 0.63%   |
| Broadcom BCM2045A0                                  | 7         | 0.63%   |
| ASUS ASUS USB-BT500                                 | 7         | 0.63%   |
| Toshiba Bluetooth Device                            | 6         | 0.54%   |
| MediaTek Wireless_Device                            | 6         | 0.54%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.54%   |
| Lite-On Wireless_Device                             | 5         | 0.45%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.45%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.36%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 0.36%   |
| Foxconn / Hon Hai BCM20702A0                        | 4         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1330      | 57.11%  |
| AMD                                          | 425       | 18.25%  |
| Nvidia                                       | 378       | 16.23%  |
| C-Media Electronics                          | 36        | 1.55%   |
| Creative Labs                                | 22        | 0.94%   |
| Logitech                                     | 13        | 0.56%   |
| GN Netcom                                    | 9         | 0.39%   |
| Creative Technology                          | 9         | 0.39%   |
| Trust                                        | 7         | 0.3%    |
| Texas Instruments                            | 6         | 0.26%   |
| ASUSTek Computer                             | 6         | 0.26%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.21%   |
| Lenovo                                       | 5         | 0.21%   |
| Kingston Technology                          | 5         | 0.21%   |
| Giga-Byte Technology                         | 5         | 0.21%   |
| DSEA A/S                                     | 5         | 0.21%   |
| Realtek Semiconductor                        | 4         | 0.17%   |
| Plantronics                                  | 4         | 0.17%   |
| Generalplus Technology                       | 4         | 0.17%   |
| VIA Technologies                             | 3         | 0.13%   |
| Tenx Technology                              | 3         | 0.13%   |
| Razer USA                                    | 3         | 0.13%   |
| Dell                                         | 3         | 0.13%   |
| XMOS                                         | 2         | 0.09%   |
| Sennheiser Communications                    | 2         | 0.09%   |
| JMTek                                        | 2         | 0.09%   |
| GYROCOM C&C                                  | 2         | 0.09%   |
| Focusrite-Novation                           | 2         | 0.09%   |
| Edifier Technology                           | 2         | 0.09%   |
| Corsair                                      | 2         | 0.09%   |
| Audio-Technica                               | 2         | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| Unknown                                      | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.04%   |
| TEAC                                         | 1         | 0.04%   |
| Studiologic                                  | 1         | 0.04%   |
| Sony                                         | 1         | 0.04%   |
| Samson Technologies                          | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.04%   |
| Nam Tai E&E Products                         | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 165       | 5.95%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 139       | 5.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 98        | 3.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 93        | 3.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 92        | 3.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 78        | 2.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 73        | 2.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 71        | 2.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 70        | 2.53%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 67        | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 60        | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 57        | 2.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 55        | 1.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 55        | 1.98%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 51        | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 51        | 1.84%   |
| Intel 8 Series HD Audio Controller                                                                | 50        | 1.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 49        | 1.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 44        | 1.59%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 43        | 1.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 41        | 1.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 40        | 1.44%   |
| Intel Broadwell-U Audio Controller                                                                | 40        | 1.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 39        | 1.41%   |
| AMD FCH Azalia Controller                                                                         | 37        | 1.34%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 36        | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 35        | 1.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 33        | 1.19%   |
| Intel 200 Series PCH HD Audio                                                                     | 33        | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 32        | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 31        | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 28        | 1.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 26        | 0.94%   |
| Intel Comet Lake PCH cAVS                                                                         | 24        | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 22        | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 22        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 21        | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 21        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 21        | 0.76%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 21        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 241       | 24.08%  |
| SK hynix                     | 172       | 17.18%  |
| Kingston                     | 150       | 14.99%  |
| Micron Technology            | 95        | 9.49%   |
| Unknown                      | 81        | 8.09%   |
| Corsair                      | 71        | 7.09%   |
| Crucial                      | 28        | 2.8%    |
| A-DATA Technology            | 27        | 2.7%    |
| Ramaxel Technology           | 26        | 2.6%    |
| Nanya Technology             | 20        | 2%      |
| Elpida                       | 19        | 1.9%    |
| G.Skill                      | 16        | 1.6%    |
| Unknown (ABCD)               | 10        | 1%      |
| Kingmax                      | 9         | 0.9%    |
| Unknown                      | 5         | 0.5%    |
| Patriot                      | 4         | 0.4%    |
| Apacer                       | 4         | 0.4%    |
| GOODRAM                      | 3         | 0.3%    |
| Transcend                    | 2         | 0.2%    |
| Silicon Power                | 2         | 0.2%    |
| Qimonda                      | 2         | 0.2%    |
| Unknown (0x7FDA000000000000) | 1         | 0.1%    |
| Unknown (0B45)               | 1         | 0.1%    |
| Team                         | 1         | 0.1%    |
| TakeMS                       | 1         | 0.1%    |
| SK_Hynix                     | 1         | 0.1%    |
| SHARETRONIC                  | 1         | 0.1%    |
| S                            | 1         | 0.1%    |
| Kingmax Semiconductor        | 1         | 0.1%    |
| KingFast                     | 1         | 0.1%    |
| Infineon                     | 1         | 0.1%    |
| H                            | 1         | 0.1%    |
| Exceleram                    | 1         | 0.1%    |
| Avant                        | 1         | 0.1%    |
| ASint Technology             | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 1.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 11        | 1%      |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 10        | 0.91%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.82%   |
| Samsung RAM M4 70T5663RZ3-CE6 2GB SODIMM DDR2 667MT/s            | 9         | 0.82%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 8         | 0.73%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.73%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 8         | 0.73%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.64%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 6         | 0.55%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.55%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.55%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.55%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.55%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s             | 6         | 0.55%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 5         | 0.45%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 5         | 0.45%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.45%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.45%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.45%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.45%   |
| Unknown                                                          | 5         | 0.45%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.36%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.36%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.36%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.36%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.36%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.36%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.36%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 4         | 0.36%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 407       | 47.55%  |
| DDR3    | 280       | 32.71%  |
| DDR2    | 62        | 7.24%   |
| SDRAM   | 31        | 3.62%   |
| LPDDR4  | 21        | 2.45%   |
| Unknown | 21        | 2.45%   |
| LPDDR3  | 14        | 1.64%   |
| DDR5    | 9         | 1.05%   |
| LPDDR5  | 5         | 0.58%   |
| DDR     | 4         | 0.47%   |
| DRAM    | 2         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 527       | 62.44%  |
| DIMM         | 273       | 32.35%  |
| Row Of Chips | 38        | 4.5%    |
| Chip         | 4         | 0.47%   |
| RIMM         | 1         | 0.12%   |
| FB-DIMM      | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 341       | 36.67%  |
| 4096  | 269       | 28.92%  |
| 16384 | 127       | 13.66%  |
| 2048  | 118       | 12.69%  |
| 1024  | 49        | 5.27%   |
| 32768 | 21        | 2.26%   |
| 512   | 5         | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 184       | 19.31%  |
| 2667    | 138       | 14.48%  |
| 3200    | 137       | 14.38%  |
| 2400    | 95        | 9.97%   |
| 1333    | 57        | 5.98%   |
| 1334    | 38        | 3.99%   |
| 2133    | 37        | 3.88%   |
| 667     | 35        | 3.67%   |
| 800     | 28        | 2.94%   |
| 3600    | 22        | 2.31%   |
| Unknown | 18        | 1.89%   |
| 3266    | 17        | 1.78%   |
| 3000    | 10        | 1.05%   |
| 1067    | 10        | 1.05%   |
| 1867    | 9         | 0.94%   |
| 975     | 9         | 0.94%   |
| 4267    | 8         | 0.84%   |
| 3400    | 8         | 0.84%   |
| 1866    | 6         | 0.63%   |
| 533     | 6         | 0.63%   |
| 6400    | 5         | 0.52%   |
| 4800    | 5         | 0.52%   |
| 4199    | 5         | 0.52%   |
| 2933    | 5         | 0.52%   |
| 2048    | 5         | 0.52%   |
| 1066    | 5         | 0.52%   |
| 2800    | 4         | 0.42%   |
| 2666    | 4         | 0.42%   |
| 4266    | 3         | 0.31%   |
| 3866    | 3         | 0.31%   |
| 3733    | 3         | 0.31%   |
| 3500    | 3         | 0.31%   |
| 1800    | 3         | 0.31%   |
| 400     | 3         | 0.31%   |
| 3466    | 2         | 0.21%   |
| 1648    | 2         | 0.21%   |
| 1639    | 2         | 0.21%   |
| 49926   | 1         | 0.1%    |
| 8192    | 1         | 0.1%    |
| 6000    | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 24.53%  |
| Canon                 | 10        | 18.87%  |
| Samsung Electronics   | 8         | 15.09%  |
| Brother Industries    | 8         | 15.09%  |
| Seiko Epson           | 7         | 13.21%  |
| Xerox                 | 2         | 3.77%   |
| Lexmark International | 2         | 3.77%   |
| Zebra                 | 1         | 1.89%   |
| QinHeng Electronics   | 1         | 1.89%   |
| ATEN International    | 1         | 1.89%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                      | 2         | 3.77%   |
| Seiko Epson ET-2710 Series                    | 2         | 3.77%   |
| Samsung M2070 Series                          | 2         | 3.77%   |
| Samsung Composite Device                      | 2         | 3.77%   |
| Lexmark International InkJet Color Printer    | 2         | 3.77%   |
| HP DeskJet 2130 series                        | 2         | 3.77%   |
| Canon MF4010 series                           | 2         | 3.77%   |
| Brother HL-1110 series                        | 2         | 3.77%   |
| Zebra GK420t Label Printer                    | 1         | 1.89%   |
| Xerox Phaser 6130N                            | 1         | 1.89%   |
| Xerox Phaser 3020                             | 1         | 1.89%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.89%   |
| Seiko Epson L6160 Series                      | 1         | 1.89%   |
| Seiko Epson L396 Series                       | 1         | 1.89%   |
| Samsung ML-216x Series Laser Printer          | 1         | 1.89%   |
| Samsung M267x 287x Series                     | 1         | 1.89%   |
| Samsung M2020 Series                          | 1         | 1.89%   |
| Samsung CLP-310 Color Laser Printer           | 1         | 1.89%   |
| QinHeng CH340S                                | 1         | 1.89%   |
| HP LaserJet M14-M17                           | 1         | 1.89%   |
| HP LaserJet 3050                              | 1         | 1.89%   |
| HP LaserJet 1022                              | 1         | 1.89%   |
| HP LaserJet 1018                              | 1         | 1.89%   |
| HP Laser 107w                                 | 1         | 1.89%   |
| HP Deskjet F4500 series                       | 1         | 1.89%   |
| HP DeskJet F2492 All-in-One                   | 1         | 1.89%   |
| HP Deskjet 3050A                              | 1         | 1.89%   |
| HP DeskJet 2700 series                        | 1         | 1.89%   |
| HP DeskJet 2300 series                        | 1         | 1.89%   |
| HP Deskjet 2050 J510                          | 1         | 1.89%   |
| Canon PIXMA MP280                             | 1         | 1.89%   |
| Canon PIXMA MP250                             | 1         | 1.89%   |
| Canon MF4320-4350                             | 1         | 1.89%   |
| Canon MF3200 series                           | 1         | 1.89%   |
| Canon MF3110                                  | 1         | 1.89%   |
| Canon LBP2900                                 | 1         | 1.89%   |
| Canon iP7200 series                           | 1         | 1.89%   |
| Canon CanoScan LiDE 300                       | 1         | 1.89%   |
| Brother MFC-7420                              | 1         | 1.89%   |
| Brother HL-5380DN series                      | 1         | 1.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 100 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 257       | 22.37%  |
| Chicony Electronics                    | 235       | 20.45%  |
| Realtek Semiconductor                  | 99        | 8.62%   |
| Microdia                               | 86        | 7.48%   |
| Bison Electronics                      | 63        | 5.48%   |
| Sunplus Innovation Technology          | 61        | 5.31%   |
| Quanta                                 | 51        | 4.44%   |
| Syntek                                 | 29        | 2.52%   |
| Cheng Uei Precision Industry (Foxlink) | 28        | 2.44%   |
| Lite-On Technology                     | 26        | 2.26%   |
| Alcor Micro                            | 26        | 2.26%   |
| Logitech                               | 24        | 2.09%   |
| Suyin                                  | 20        | 1.74%   |
| Acer                                   | 16        | 1.39%   |
| Sonix Technology                       | 15        | 1.31%   |
| Apple                                  | 12        | 1.04%   |
| Samsung Electronics                    | 11        | 0.96%   |
| Luxvisions Innotech Limited            | 10        | 0.87%   |
| Ricoh                                  | 9         | 0.78%   |
| Microsoft                              | 9         | 0.78%   |
| Silicon Motion                         | 7         | 0.61%   |
| Z-Star Microelectronics                | 6         | 0.52%   |
| OmniVision Technologies                | 5         | 0.44%   |
| ALi                                    | 4         | 0.35%   |
| Primax Electronics                     | 3         | 0.26%   |
| Lenovo                                 | 3         | 0.26%   |
| GEMBIRD                                | 3         | 0.26%   |
| Cubeternet                             | 3         | 0.26%   |
| Sunplus Technology                     | 2         | 0.17%   |
| Jieli Technology                       | 2         | 0.17%   |
| Importek                               | 2         | 0.17%   |
| Genesys Logic                          | 2         | 0.17%   |
| Aveo Technology                        | 2         | 0.17%   |
| WaveRider Communications               | 1         | 0.09%   |
| Unknown                                | 1         | 0.09%   |
| Trust                                  | 1         | 0.09%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.09%   |
| Philips (or NXP)                       | 1         | 0.09%   |
| Novatek Microelectronics               | 1         | 0.09%   |
| Nikon                                  | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam      | 107       | 9.3%    |
| IMC Networks USB2.0 HD UVC WebCam       | 81        | 7.04%   |
| Chicony Integrated Camera               | 51        | 4.43%   |
| IMC Networks Integrated Camera          | 31        | 2.69%   |
| Realtek Integrated_Webcam_HD            | 30        | 2.61%   |
| Microdia Integrated_Webcam_HD           | 25        | 2.17%   |
| Bison Integrated Camera                 | 21        | 1.82%   |
| Chicony USB2.0 VGA UVC WebCam           | 19        | 1.65%   |
| Syntek Integrated Camera                | 16        | 1.39%   |
| Chicony USB2.0 HD UVC WebCam            | 15        | 1.3%    |
| Chicony HD Webcam                       | 15        | 1.3%    |
| Sunplus HD WebCam                       | 14        | 1.22%   |
| Realtek USB Camera                      | 13        | 1.13%   |
| Sonix USB2.0 HD UVC WebCam              | 11        | 0.96%   |
| Samsung Galaxy series, misc. (MTP mode) | 11        | 0.96%   |
| Chicony TOSHIBA Web Camera - HD         | 11        | 0.96%   |
| Quanta VGA WebCam                       | 10        | 0.87%   |
| Chicony EasyCamera                      | 10        | 0.87%   |
| Lite-On Integrated Camera               | 9         | 0.78%   |
| Chicony HP Webcam                       | 9         | 0.78%   |
| Bison SunplusIT Integrated Camera       | 9         | 0.78%   |
| Alcor Micro USB 2.0 PC Camera           | 9         | 0.78%   |
| Microdia Integrated Webcam              | 8         | 0.7%    |
| Microdia Camera                         | 8         | 0.7%    |
| Chicony VGA WebCam                      | 8         | 0.7%    |
| Bison EasyCamera                        | 8         | 0.7%    |
| Alcor Micro USB 2.0 PC cam              | 8         | 0.7%    |
| Acer Lenovo EasyCamera                  | 8         | 0.7%    |
| Syntek EasyCamera                       | 7         | 0.61%   |
| Sunplus Integrated_Webcam_HD            | 7         | 0.61%   |
| Realtek USB2.0 VGA UVC WebCam           | 7         | 0.61%   |
| Realtek USB2.0 HD UVC WebCam            | 7         | 0.61%   |
| Realtek Integrated Webcam               | 7         | 0.61%   |
| Microsoft LifeCam HD-3000               | 7         | 0.61%   |
| IMC Networks USB2.0 UVC HD Webcam       | 7         | 0.61%   |
| Sunplus ASUS Webcam                     | 6         | 0.52%   |
| Realtek Lenovo EasyCamera               | 6         | 0.52%   |
| Quanta HD WebCam                        | 6         | 0.52%   |
| Lite-On HP Wide Vision HD Camera        | 6         | 0.52%   |
| Chicony HP HD Webcam                    | 6         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 58        | 33.92%  |
| Synaptics                  | 45        | 26.32%  |
| Shenzhen Goodix Technology | 21        | 12.28%  |
| Elan Microelectronics      | 15        | 8.77%   |
| Upek                       | 11        | 6.43%   |
| AuthenTec                  | 9         | 5.26%   |
| LighTuning Technology      | 7         | 4.09%   |
| Focal-systems.Corp         | 2         | 1.17%   |
| STMicroelectronics         | 1         | 0.58%   |
| Samsung Electronics        | 1         | 0.58%   |
| GDMicroelectronics         | 1         | 0.58%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 8.19%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 13        | 7.6%    |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 7.6%    |
| Synaptics  WBDI                                                            | 11        | 6.43%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 5.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 5.26%   |
| Elan ELAN:Fingerprint                                                      | 9         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 4.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 3.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.51%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 3.51%   |
| AuthenTec AES2810                                                          | 6         | 3.51%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.92%   |
| Elan ELAN:ARM-M4                                                           | 5         | 2.92%   |
| Validity Sensors VFS491                                                    | 4         | 2.34%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.34%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.75%   |
| Synaptics WBDI                                                             | 3         | 1.75%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.75%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.75%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.75%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.75%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.17%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.17%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.17%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 1.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.17%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.58%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.58%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.58%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.58%   |
| Synaptics UWP WBDI                                                         | 1         | 0.58%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.58%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.58%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.58%   |
| GDMicroelectronics Touch Fingerprint Sensor                                | 1         | 0.58%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 0.58%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.58%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 41        | 53.95%  |
| Alcor Micro               | 18        | 23.68%  |
| Upek                      | 5         | 6.58%   |
| Lenovo                    | 5         | 6.58%   |
| O2 Micro                  | 3         | 3.95%   |
| Gemalto (was Gemplus)     | 1         | 1.32%   |
| Fujitsu Siemens Computers | 1         | 1.32%   |
| Chicony Electronics       | 1         | 1.32%   |
| Aladdin Knowledge Systems | 1         | 1.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 23.68%  |
| Broadcom 58200                                                               | 13        | 17.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 13.16%  |
| Broadcom 5880                                                                | 10        | 13.16%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 10.53%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 6.58%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 6.58%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.95%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.32%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 1.32%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.32%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1297      | 72.42%  |
| 1     | 402       | 22.45%  |
| 2     | 82        | 4.58%   |
| 3     | 8         | 0.45%   |
| 10    | 1         | 0.06%   |
| 4     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 170       | 29.01%  |
| Graphics card            | 131       | 22.35%  |
| Net/wireless             | 71        | 12.12%  |
| Chipcard                 | 69        | 11.77%  |
| Multimedia controller    | 36        | 6.14%   |
| Communication controller | 22        | 3.75%   |
| Camera                   | 21        | 3.58%   |
| Bluetooth                | 16        | 2.73%   |
| Storage                  | 15        | 2.56%   |
| Card reader              | 8         | 1.37%   |
| Sound                    | 7         | 1.19%   |
| Unassigned class         | 4         | 0.68%   |
| Network                  | 3         | 0.51%   |
| Net/ethernet             | 3         | 0.51%   |
| Storage/ide              | 2         | 0.34%   |
| Flash memory             | 2         | 0.34%   |
| Unclassified device      | 1         | 0.17%   |
| Storage/raid             | 1         | 0.17%   |
| Storage/nvme             | 1         | 0.17%   |
| Modem                    | 1         | 0.17%   |
| Firewire controller      | 1         | 0.17%   |
| Dvb card                 | 1         | 0.17%   |

