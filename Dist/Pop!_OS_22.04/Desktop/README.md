Pop!_OS 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 437

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B450M DS3H WIFI-CF          | [fb12fe29dd](https://linux-hardware.org/?probe=fb12fe29dd) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [e311938d4a](https://linux-hardware.org/?probe=e311938d4a) | Sep 01, 2022 |
| ASRock        | B450M/ac                    | [393a08345e](https://linux-hardware.org/?probe=393a08345e) | Sep 01, 2022 |
| Acer          | Aspire X3400                | [705a3242ae](https://linux-hardware.org/?probe=705a3242ae) | Sep 01, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [1dd7a06125](https://linux-hardware.org/?probe=1dd7a06125) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [cb5288e92d](https://linux-hardware.org/?probe=cb5288e92d) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [5e9e5dd1ce](https://linux-hardware.org/?probe=5e9e5dd1ce) | Aug 31, 2022 |
| Lenovo        | MAHOBAY                     | [53af4f5de7](https://linux-hardware.org/?probe=53af4f5de7) | Aug 30, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d0ca11a18a](https://linux-hardware.org/?probe=d0ca11a18a) | Aug 29, 2022 |
| ASRock        | B450M Pro4 R2.0             | [fb155ef3bd](https://linux-hardware.org/?probe=fb155ef3bd) | Aug 29, 2022 |
| Dell          | 0KWVT8 A03                  | [b91ce43523](https://linux-hardware.org/?probe=b91ce43523) | Aug 29, 2022 |
| HP            | 1497                        | [625185d1db](https://linux-hardware.org/?probe=625185d1db) | Aug 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [281360b58a](https://linux-hardware.org/?probe=281360b58a) | Aug 29, 2022 |
| BESSTAR Te... | UM700                       | [13fdf5ef5e](https://linux-hardware.org/?probe=13fdf5ef5e) | Aug 29, 2022 |
| MSI           | B450M MORTAR MAX            | [2d89536f80](https://linux-hardware.org/?probe=2d89536f80) | Aug 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a328df0016](https://linux-hardware.org/?probe=a328df0016) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | [3a448c33f9](https://linux-hardware.org/?probe=3a448c33f9) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | [4210c6a219](https://linux-hardware.org/?probe=4210c6a219) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [f07bd2b99b](https://linux-hardware.org/?probe=f07bd2b99b) | Aug 28, 2022 |
| Lenovo        | Bantry CRB 31900058 STD     | [d0c37f7188](https://linux-hardware.org/?probe=d0c37f7188) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [dbb099ef3e](https://linux-hardware.org/?probe=dbb099ef3e) | Aug 28, 2022 |
| Gigabyte      | H67A-USB3-B3                | [b04fc1333e](https://linux-hardware.org/?probe=b04fc1333e) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [a90735a9e9](https://linux-hardware.org/?probe=a90735a9e9) | Aug 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [704ce84e6a](https://linux-hardware.org/?probe=704ce84e6a) | Aug 27, 2022 |
| ASRock        | B560 Steel Legend           | [55ebdff357](https://linux-hardware.org/?probe=55ebdff357) | Aug 26, 2022 |
| HP            | 1850                        | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| ASRock        | X570 Creator                | [612ada6405](https://linux-hardware.org/?probe=612ada6405) | Aug 26, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [d988a14a82](https://linux-hardware.org/?probe=d988a14a82) | Aug 26, 2022 |
| Acer          | Aspire X3400                | [81acff75f6](https://linux-hardware.org/?probe=81acff75f6) | Aug 25, 2022 |
| Dell          | 0KWVT8 A03                  | [967ff51388](https://linux-hardware.org/?probe=967ff51388) | Aug 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [18102e8a9a](https://linux-hardware.org/?probe=18102e8a9a) | Aug 24, 2022 |
| ASRock        | B660-ITX                    | [316ae22af8](https://linux-hardware.org/?probe=316ae22af8) | Aug 24, 2022 |
| HP            | 3647h                       | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [8118d6f78c](https://linux-hardware.org/?probe=8118d6f78c) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [beb3c92510](https://linux-hardware.org/?probe=beb3c92510) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [8e57e188c9](https://linux-hardware.org/?probe=8e57e188c9) | Aug 23, 2022 |
| ASUSTek       | P9X79 LE                    | [1fbde15177](https://linux-hardware.org/?probe=1fbde15177) | Aug 22, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [a44650a9d8](https://linux-hardware.org/?probe=a44650a9d8) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e8bee7737a](https://linux-hardware.org/?probe=e8bee7737a) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b182084c88](https://linux-hardware.org/?probe=b182084c88) | Aug 22, 2022 |
| MSI           | FM2-A55M-E33                | [fac0116bf7](https://linux-hardware.org/?probe=fac0116bf7) | Aug 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [23c07b5d2b](https://linux-hardware.org/?probe=23c07b5d2b) | Aug 21, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [c717f7c6d5](https://linux-hardware.org/?probe=c717f7c6d5) | Aug 21, 2022 |
| MSI           | Z170A PC MATE               | [8df71394cd](https://linux-hardware.org/?probe=8df71394cd) | Aug 20, 2022 |
| Gigabyte      | B550M DS3H                  | [774796ffbd](https://linux-hardware.org/?probe=774796ffbd) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [3a7a62f6f8](https://linux-hardware.org/?probe=3a7a62f6f8) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [93c5d7b0f9](https://linux-hardware.org/?probe=93c5d7b0f9) | Aug 19, 2022 |
| Dell          | 0KWVT8 A03                  | [7af77fd850](https://linux-hardware.org/?probe=7af77fd850) | Aug 18, 2022 |
| Gigabyte      | X299 AORUS MASTER           | [8d76a030ca](https://linux-hardware.org/?probe=8d76a030ca) | Aug 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8a1a495053](https://linux-hardware.org/?probe=8a1a495053) | Aug 18, 2022 |
| ASUSTek       | B150M-C/BR                  | [b15c721e4c](https://linux-hardware.org/?probe=b15c721e4c) | Aug 18, 2022 |
| Acer          | Predator PO5-600s V:1.0     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| MSI           | B450-A PRO MAX              | [9a1a049600](https://linux-hardware.org/?probe=9a1a049600) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [169469e8b6](https://linux-hardware.org/?probe=169469e8b6) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d98e5c8b5e](https://linux-hardware.org/?probe=d98e5c8b5e) | Aug 17, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1e4e125d11](https://linux-hardware.org/?probe=1e4e125d11) | Aug 17, 2022 |
| HP            | 2215                        | [71a33dc713](https://linux-hardware.org/?probe=71a33dc713) | Aug 17, 2022 |
| HP            | 2215                        | [aa386126ad](https://linux-hardware.org/?probe=aa386126ad) | Aug 17, 2022 |
| MSI           | H110M PRO-VH PLUS           | [e6e4efd93a](https://linux-hardware.org/?probe=e6e4efd93a) | Aug 17, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [8441adcca9](https://linux-hardware.org/?probe=8441adcca9) | Aug 17, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [5c2c3d81ef](https://linux-hardware.org/?probe=5c2c3d81ef) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [0a5775d3a8](https://linux-hardware.org/?probe=0a5775d3a8) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e75de6c205](https://linux-hardware.org/?probe=e75de6c205) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| HP            | 8054                        | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [5a5538ce52](https://linux-hardware.org/?probe=5a5538ce52) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [5ef85261aa](https://linux-hardware.org/?probe=5ef85261aa) | Aug 13, 2022 |
| Gigabyte      | H97N-WIFI                   | [966a3e1593](https://linux-hardware.org/?probe=966a3e1593) | Aug 13, 2022 |
| BESSTAR Te... | UM700                       | [81a59240ea](https://linux-hardware.org/?probe=81a59240ea) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| MSI           | Z87-G45 GAMING              | [2f541727e1](https://linux-hardware.org/?probe=2f541727e1) | Aug 12, 2022 |
| ASRock        | A320M                       | [1e0a574078](https://linux-hardware.org/?probe=1e0a574078) | Aug 12, 2022 |
| ASUSTek       | H97-PLUS                    | [4ca1b1050d](https://linux-hardware.org/?probe=4ca1b1050d) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [230d7247c0](https://linux-hardware.org/?probe=230d7247c0) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| HP            | 3397                        | [9beccd0ca8](https://linux-hardware.org/?probe=9beccd0ca8) | Aug 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [d0b0186eb9](https://linux-hardware.org/?probe=d0b0186eb9) | Aug 09, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [80bb75a792](https://linux-hardware.org/?probe=80bb75a792) | Aug 07, 2022 |
| ASUSTek       | Z87-K                       | [d1954b42ae](https://linux-hardware.org/?probe=d1954b42ae) | Aug 06, 2022 |
| HP            | 1998                        | [5164a156e2](https://linux-hardware.org/?probe=5164a156e2) | Aug 05, 2022 |
| Intel         | D955XBK AAC96732-501        | [d6463d7629](https://linux-hardware.org/?probe=d6463d7629) | Aug 05, 2022 |
| MSI           | 970A-G43                    | [a77e1878ae](https://linux-hardware.org/?probe=a77e1878ae) | Aug 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [56b0b42020](https://linux-hardware.org/?probe=56b0b42020) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [585bf3495e](https://linux-hardware.org/?probe=585bf3495e) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [2d017b110e](https://linux-hardware.org/?probe=2d017b110e) | Aug 04, 2022 |
| Gigabyte      | AX370-Gaming K7             | [14447cf212](https://linux-hardware.org/?probe=14447cf212) | Aug 04, 2022 |
| Intel         | D955XBK AAC96732-501        | [53e0f1bc02](https://linux-hardware.org/?probe=53e0f1bc02) | Aug 03, 2022 |
| ASUSTek       | P8Z77-V LK                  | [9878a3365c](https://linux-hardware.org/?probe=9878a3365c) | Aug 03, 2022 |
| Intel         | D955XBK AAC96732-501        | [ed4b3ec577](https://linux-hardware.org/?probe=ed4b3ec577) | Aug 03, 2022 |
| Intel         | DP55WB AAE64798-208         | [0c66cac06d](https://linux-hardware.org/?probe=0c66cac06d) | Aug 03, 2022 |
| ASUSTek       | PRIME B550M-A               | [3f1ccf427a](https://linux-hardware.org/?probe=3f1ccf427a) | Aug 03, 2022 |
| Intel         | DQ35JO AAD82085-801         | [754017fe21](https://linux-hardware.org/?probe=754017fe21) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [73b2c51a7e](https://linux-hardware.org/?probe=73b2c51a7e) | Aug 02, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | [6127d6e7a3](https://linux-hardware.org/?probe=6127d6e7a3) | Aug 02, 2022 |
| Gigabyte      | A520I AC                    | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| EVGA          | 134-KS-E377                 | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| MSI           | MEG Z690 UNIFY              | [571f500e5e](https://linux-hardware.org/?probe=571f500e5e) | Jul 30, 2022 |
| Dell          | 0TP412                      | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| Gigabyte      | A520I AC                    | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| MSI           | B450M MORTAR MAX            | [1316e90024](https://linux-hardware.org/?probe=1316e90024) | Jul 30, 2022 |
| HP            | 2215                        | [6e351e6da3](https://linux-hardware.org/?probe=6e351e6da3) | Jul 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [31b2d82a52](https://linux-hardware.org/?probe=31b2d82a52) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [622aa6421e](https://linux-hardware.org/?probe=622aa6421e) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [d8c0404bad](https://linux-hardware.org/?probe=d8c0404bad) | Jul 29, 2022 |
| MACHINIST     | X79 V2.82H                  | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASUSTek       | PRIME Z390-A                | [b8e8d2b6c4](https://linux-hardware.org/?probe=b8e8d2b6c4) | Jul 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [567addf380](https://linux-hardware.org/?probe=567addf380) | Jul 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [221bb14fbd](https://linux-hardware.org/?probe=221bb14fbd) | Jul 24, 2022 |
| MSI           | MEG X570 ACE                | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8f131b55b9](https://linux-hardware.org/?probe=8f131b55b9) | Jul 22, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [20d32236ad](https://linux-hardware.org/?probe=20d32236ad) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a52692425](https://linux-hardware.org/?probe=5a52692425) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f524dac3fa](https://linux-hardware.org/?probe=f524dac3fa) | Jul 20, 2022 |
| MSI           | Z590-A PRO                  | [9500cfd7e1](https://linux-hardware.org/?probe=9500cfd7e1) | Jul 19, 2022 |
| Dell          | 02YYK5 A01                  | [94b2dc99fa](https://linux-hardware.org/?probe=94b2dc99fa) | Jul 19, 2022 |
| Lenovo        | MAHOBAY                     | [c1c146a0f9](https://linux-hardware.org/?probe=c1c146a0f9) | Jul 18, 2022 |
| Gigabyte      | B75M-D3H                    | [1c0d0a79d1](https://linux-hardware.org/?probe=1c0d0a79d1) | Jul 17, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | [3c55557131](https://linux-hardware.org/?probe=3c55557131) | Jul 17, 2022 |
| Gigabyte      | H97M-Gaming 3               | [a72ad8ba14](https://linux-hardware.org/?probe=a72ad8ba14) | Jul 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [36ad4a7384](https://linux-hardware.org/?probe=36ad4a7384) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [a23b73c3ff](https://linux-hardware.org/?probe=a23b73c3ff) | Jul 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [2e73a9947c](https://linux-hardware.org/?probe=2e73a9947c) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c9ff108124](https://linux-hardware.org/?probe=c9ff108124) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M90p 5864A1U    | [406232d6c2](https://linux-hardware.org/?probe=406232d6c2) | Jul 15, 2022 |
| MSI           | Z170A GAMING M5             | [16d2d7469b](https://linux-hardware.org/?probe=16d2d7469b) | Jul 15, 2022 |
| Gigabyte      | H310M S2 x.x                | [a55538b651](https://linux-hardware.org/?probe=a55538b651) | Jul 14, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [608d209fe5](https://linux-hardware.org/?probe=608d209fe5) | Jul 14, 2022 |
| ASRock        | Z77 Pro4-M                  | [69b486ea31](https://linux-hardware.org/?probe=69b486ea31) | Jul 14, 2022 |
| Dell          | 02YYK5 A01                  | [ca4bfe598b](https://linux-hardware.org/?probe=ca4bfe598b) | Jul 14, 2022 |
| ASUSTek       | M4A79XTD EVO                | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASRock        | B450M Steel Legend          | [3732c0ad0c](https://linux-hardware.org/?probe=3732c0ad0c) | Jul 13, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [a6d5a615d0](https://linux-hardware.org/?probe=a6d5a615d0) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d7e4d34816](https://linux-hardware.org/?probe=d7e4d34816) | Jul 12, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [a3c14e06c9](https://linux-hardware.org/?probe=a3c14e06c9) | Jul 11, 2022 |
| MSI           | P67A-C43                    | [c76725f62c](https://linux-hardware.org/?probe=c76725f62c) | Jul 11, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [84e5c2ab51](https://linux-hardware.org/?probe=84e5c2ab51) | Jul 11, 2022 |
| ASUSTek       | P5Q-PRO                     | [ad6eedb5e5](https://linux-hardware.org/?probe=ad6eedb5e5) | Jul 10, 2022 |
| ASUSTek       | Z170-A                      | [1ac13f76b1](https://linux-hardware.org/?probe=1ac13f76b1) | Jul 10, 2022 |
| Dell          | 042P49 A02                  | [1b8b98b54d](https://linux-hardware.org/?probe=1b8b98b54d) | Jul 10, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [0e0d93b899](https://linux-hardware.org/?probe=0e0d93b899) | Jul 10, 2022 |
| ASUSTek       | P5Q-PRO                     | [9860ca66f6](https://linux-hardware.org/?probe=9860ca66f6) | Jul 09, 2022 |
| Gigabyte      | B450 AORUS M                | [5d50b40871](https://linux-hardware.org/?probe=5d50b40871) | Jul 09, 2022 |
| HP            | 1495                        | [3e67bd3405](https://linux-hardware.org/?probe=3e67bd3405) | Jul 09, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [a374367376](https://linux-hardware.org/?probe=a374367376) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [fe383d7488](https://linux-hardware.org/?probe=fe383d7488) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [786c9e341c](https://linux-hardware.org/?probe=786c9e341c) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [833f3df27a](https://linux-hardware.org/?probe=833f3df27a) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [199e7db55a](https://linux-hardware.org/?probe=199e7db55a) | Jul 09, 2022 |
| Gigabyte      | B550 AORUS PRO AX           | [9ad45447d4](https://linux-hardware.org/?probe=9ad45447d4) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6ebe4f89b7](https://linux-hardware.org/?probe=6ebe4f89b7) | Jul 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [3458084b51](https://linux-hardware.org/?probe=3458084b51) | Jul 08, 2022 |
| HP            | 3398                        | [fb1290d5b3](https://linux-hardware.org/?probe=fb1290d5b3) | Jul 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8b1a622249](https://linux-hardware.org/?probe=8b1a622249) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [9c2efc454e](https://linux-hardware.org/?probe=9c2efc454e) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [eb5d4499aa](https://linux-hardware.org/?probe=eb5d4499aa) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [e068e197b4](https://linux-hardware.org/?probe=e068e197b4) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Soyo          | SY-A68M FS V2.0             | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [7a6f484b16](https://linux-hardware.org/?probe=7a6f484b16) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [bfa2b2f092](https://linux-hardware.org/?probe=bfa2b2f092) | Jul 05, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [161f8c2665](https://linux-hardware.org/?probe=161f8c2665) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [15118ef9fd](https://linux-hardware.org/?probe=15118ef9fd) | Jul 03, 2022 |
| HP            | 18E7                        | [8f2b2cb5e5](https://linux-hardware.org/?probe=8f2b2cb5e5) | Jul 02, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7da3547526](https://linux-hardware.org/?probe=7da3547526) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d979555615](https://linux-hardware.org/?probe=d979555615) | Jul 01, 2022 |
| ASRock        | B450 Gaming K4              | [2bdfc5f472](https://linux-hardware.org/?probe=2bdfc5f472) | Jul 01, 2022 |
| MSI           | B250M PRO-VD                | [b48e88849b](https://linux-hardware.org/?probe=b48e88849b) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [8c29343495](https://linux-hardware.org/?probe=8c29343495) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [2631bf2ae1](https://linux-hardware.org/?probe=2631bf2ae1) | Jul 01, 2022 |
| HP            | 18E7                        | [1808b6dee4](https://linux-hardware.org/?probe=1808b6dee4) | Jul 01, 2022 |
| Dell          | 0HHV7N A00                  | [41255f7150](https://linux-hardware.org/?probe=41255f7150) | Jun 30, 2022 |
| ASRock        | X399 Taichi                 | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [b85b1f9277](https://linux-hardware.org/?probe=b85b1f9277) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | [f01192b57e](https://linux-hardware.org/?probe=f01192b57e) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [0a66ce61c6](https://linux-hardware.org/?probe=0a66ce61c6) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [f2b790de57](https://linux-hardware.org/?probe=f2b790de57) | Jun 29, 2022 |
| HP            | 3647h                       | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| Gigabyte      | Z170-Gaming K3              | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [8efb1d3556](https://linux-hardware.org/?probe=8efb1d3556) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [5b239d8bba](https://linux-hardware.org/?probe=5b239d8bba) | Jun 28, 2022 |
| ASRock        | B450 Gaming K4              | [6ecc609381](https://linux-hardware.org/?probe=6ecc609381) | Jun 27, 2022 |
| ASRock        | B450 Steel Legend           | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| ASUSTek       | VM40B                       | [35f67bace1](https://linux-hardware.org/?probe=35f67bace1) | Jun 26, 2022 |
| Dell          | 0D6H9T A00                  | [fd65f44d25](https://linux-hardware.org/?probe=fd65f44d25) | Jun 26, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [6580b51e30](https://linux-hardware.org/?probe=6580b51e30) | Jun 25, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [01fcd4495e](https://linux-hardware.org/?probe=01fcd4495e) | Jun 25, 2022 |
| Dell          | 040DDP A00                  | [02721926a7](https://linux-hardware.org/?probe=02721926a7) | Jun 25, 2022 |
| MSI           | MAG Z690 TORPEDO            | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| ASUSTek       | LEUCITE                     | [c4d2ed5723](https://linux-hardware.org/?probe=c4d2ed5723) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| Dell          | 0WMJ54 A01                  | [ee865231c1](https://linux-hardware.org/?probe=ee865231c1) | Jun 24, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [055977bdee](https://linux-hardware.org/?probe=055977bdee) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [0bd1e7d592](https://linux-hardware.org/?probe=0bd1e7d592) | Jun 23, 2022 |
| ASUSTek       | PRIME B550M-A               | [d4492d1e5d](https://linux-hardware.org/?probe=d4492d1e5d) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ae30cadddf](https://linux-hardware.org/?probe=ae30cadddf) | Jun 22, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [21d1dc43e6](https://linux-hardware.org/?probe=21d1dc43e6) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [27bc9defca](https://linux-hardware.org/?probe=27bc9defca) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [941b96e6ab](https://linux-hardware.org/?probe=941b96e6ab) | Jun 22, 2022 |
| BESSTAR Te... | UM700                       | [5dc08ee2d7](https://linux-hardware.org/?probe=5dc08ee2d7) | Jun 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d5fd58e3b0](https://linux-hardware.org/?probe=d5fd58e3b0) | Jun 21, 2022 |
| ASUSTek       | PRIME Z370-A                | [8dca736a46](https://linux-hardware.org/?probe=8dca736a46) | Jun 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [f747d1bfd3](https://linux-hardware.org/?probe=f747d1bfd3) | Jun 21, 2022 |
| System76      | Thelio thelio-r2            | [b9b9d5ffda](https://linux-hardware.org/?probe=b9b9d5ffda) | Jun 21, 2022 |
| MSI           | B550M-A PRO                 | [1765b91360](https://linux-hardware.org/?probe=1765b91360) | Jun 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [eb61c79793](https://linux-hardware.org/?probe=eb61c79793) | Jun 21, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [6ddca91c97](https://linux-hardware.org/?probe=6ddca91c97) | Jun 21, 2022 |
| Biostar       | N68S3+                      | [efe83d16ac](https://linux-hardware.org/?probe=efe83d16ac) | Jun 21, 2022 |
| Intel         | MAHOBAY                     | [f615165669](https://linux-hardware.org/?probe=f615165669) | Jun 21, 2022 |
| ASRock        | B450 Gaming K4              | [230bdf84a1](https://linux-hardware.org/?probe=230bdf84a1) | Jun 20, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [ec3bc83e7a](https://linux-hardware.org/?probe=ec3bc83e7a) | Jun 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [d5af99ece6](https://linux-hardware.org/?probe=d5af99ece6) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V LX                  | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | [3d4d492e9d](https://linux-hardware.org/?probe=3d4d492e9d) | Jun 19, 2022 |
| Dell          | 0YXT71 A03                  | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| HP            | 158B                        | [b66a2770e7](https://linux-hardware.org/?probe=b66a2770e7) | Jun 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [6ba04b0f37](https://linux-hardware.org/?probe=6ba04b0f37) | Jun 18, 2022 |
| BESSTAR Te... | UM700                       | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | [755ead951d](https://linux-hardware.org/?probe=755ead951d) | Jun 17, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [5241a60357](https://linux-hardware.org/?probe=5241a60357) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f4178c276d](https://linux-hardware.org/?probe=f4178c276d) | Jun 16, 2022 |
| Intel         | MAHOBAY                     | [91039940ea](https://linux-hardware.org/?probe=91039940ea) | Jun 16, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [24140a62de](https://linux-hardware.org/?probe=24140a62de) | Jun 16, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| MSI           | B450 TOMAHAWK               | [e11d001f52](https://linux-hardware.org/?probe=e11d001f52) | Jun 15, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Medion        | MS-7728                     | [ae02539c17](https://linux-hardware.org/?probe=ae02539c17) | Jun 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [5be4039515](https://linux-hardware.org/?probe=5be4039515) | Jun 15, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [507c214577](https://linux-hardware.org/?probe=507c214577) | Jun 15, 2022 |
| MSI           | B550-A PRO                  | [f7201ee1de](https://linux-hardware.org/?probe=f7201ee1de) | Jun 14, 2022 |
| HP            | 1905                        | [b3d0170095](https://linux-hardware.org/?probe=b3d0170095) | Jun 14, 2022 |
| HP            | 18E7                        | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| Lenovo        | 0B98401 PRO                 | [23de86aa97](https://linux-hardware.org/?probe=23de86aa97) | Jun 14, 2022 |
| Alienware     | 0R3FWM A00                  | [6690a39447](https://linux-hardware.org/?probe=6690a39447) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f9e74fdcd3](https://linux-hardware.org/?probe=f9e74fdcd3) | Jun 13, 2022 |
| Dell          | 073MMW A03                  | [3e206d2462](https://linux-hardware.org/?probe=3e206d2462) | Jun 13, 2022 |
| ASUSTek       | Z87-K                       | [cafc34944d](https://linux-hardware.org/?probe=cafc34944d) | Jun 13, 2022 |
| MSI           | B350 PC MATE                | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [a332c946a2](https://linux-hardware.org/?probe=a332c946a2) | Jun 11, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d02f89642d](https://linux-hardware.org/?probe=d02f89642d) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [a4277bcba9](https://linux-hardware.org/?probe=a4277bcba9) | Jun 11, 2022 |
| MSI           | MEG X570 ACE                | [d88374c06d](https://linux-hardware.org/?probe=d88374c06d) | Jun 11, 2022 |
| Unknown       | Unknown                     | [19d1362c66](https://linux-hardware.org/?probe=19d1362c66) | Jun 10, 2022 |
| Gigabyte      | H87M-HD3                    | [eadd724efa](https://linux-hardware.org/?probe=eadd724efa) | Jun 10, 2022 |
| MSI           | H97 GAMING 3                | [839bbee3fa](https://linux-hardware.org/?probe=839bbee3fa) | Jun 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [1fef4f1cf3](https://linux-hardware.org/?probe=1fef4f1cf3) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [44a6f3e33d](https://linux-hardware.org/?probe=44a6f3e33d) | Jun 07, 2022 |
| Gigabyte      | Z390 UD                     | [cd4b8b609f](https://linux-hardware.org/?probe=cd4b8b609f) | Jun 07, 2022 |
| Dell          | 0JW6C6 A01                  | [34d9fc3968](https://linux-hardware.org/?probe=34d9fc3968) | Jun 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [56c4428636](https://linux-hardware.org/?probe=56c4428636) | Jun 06, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a0c155ffb9](https://linux-hardware.org/?probe=a0c155ffb9) | Jun 05, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [816b4e757d](https://linux-hardware.org/?probe=816b4e757d) | Jun 05, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [e92e195362](https://linux-hardware.org/?probe=e92e195362) | Jun 05, 2022 |
| ASUSTek       | P8Z68-V LX                  | [e7e3608105](https://linux-hardware.org/?probe=e7e3608105) | Jun 04, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [a65dd5834e](https://linux-hardware.org/?probe=a65dd5834e) | Jun 04, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [81bfe17cb5](https://linux-hardware.org/?probe=81bfe17cb5) | Jun 04, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [95db56a864](https://linux-hardware.org/?probe=95db56a864) | Jun 03, 2022 |
| ASUSTek       | Z87-K                       | [915e2819c0](https://linux-hardware.org/?probe=915e2819c0) | Jun 02, 2022 |
| ASRock        | Z390 Phantom Gaming SLI/... | [5f40da7ae9](https://linux-hardware.org/?probe=5f40da7ae9) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5348dd6576](https://linux-hardware.org/?probe=5348dd6576) | Jun 01, 2022 |
| ASUSTek       | PRIME Z590-A                | [fa29e357fa](https://linux-hardware.org/?probe=fa29e357fa) | Jun 01, 2022 |
| ASUSTek       | F2A85-M                     | [82b4935292](https://linux-hardware.org/?probe=82b4935292) | Jun 01, 2022 |
| MSI           | Z170A MPOWER GAMING TITA... | [538feade4f](https://linux-hardware.org/?probe=538feade4f) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [bee74ec003](https://linux-hardware.org/?probe=bee74ec003) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| System76      | Thelio Major thelio-majo... | [291730a3bb](https://linux-hardware.org/?probe=291730a3bb) | May 31, 2022 |
| Dell          | 0Y2MRG A00                  | [013e0da975](https://linux-hardware.org/?probe=013e0da975) | May 30, 2022 |
| Dell          | 0D02VH A01                  | [fc97b0a5bf](https://linux-hardware.org/?probe=fc97b0a5bf) | May 30, 2022 |
| ASUSTek       | PRIME Z590-A                | [1058cdf867](https://linux-hardware.org/?probe=1058cdf867) | May 30, 2022 |
| HP            | 8266                        | [d0e35451ab](https://linux-hardware.org/?probe=d0e35451ab) | May 29, 2022 |
| Gigabyte      | H270-Gaming 3               | [c28c21c4d8](https://linux-hardware.org/?probe=c28c21c4d8) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [5d899f8fc5](https://linux-hardware.org/?probe=5d899f8fc5) | May 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d1923db949](https://linux-hardware.org/?probe=d1923db949) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b78390767c](https://linux-hardware.org/?probe=b78390767c) | May 28, 2022 |
| MSI           | MS-7717                     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| MSI           | MS-7717                     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Dell          | 040DDP A01                  | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| HP            | 158B                        | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [bdf54228e5](https://linux-hardware.org/?probe=bdf54228e5) | May 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f5195788f8](https://linux-hardware.org/?probe=f5195788f8) | May 27, 2022 |
| ASUSTek       | PRIME Z270-A                | [5d1ee4048a](https://linux-hardware.org/?probe=5d1ee4048a) | May 27, 2022 |
| ASUSTek       | P5KPL-SE                    | [c4b27d79ef](https://linux-hardware.org/?probe=c4b27d79ef) | May 26, 2022 |
| ASUSTek       | P5QPL-AM                    | [938ab3ec5c](https://linux-hardware.org/?probe=938ab3ec5c) | May 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ae0ada290a](https://linux-hardware.org/?probe=ae0ada290a) | May 26, 2022 |
| ASRock        | H670M-ITX/ax                | [b3f7ff3d98](https://linux-hardware.org/?probe=b3f7ff3d98) | May 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | [852a292ba3](https://linux-hardware.org/?probe=852a292ba3) | May 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [4738560555](https://linux-hardware.org/?probe=4738560555) | May 25, 2022 |
| HP            | 8703                        | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| ASRock        | H470M-ITX/ac                | [181f7decc6](https://linux-hardware.org/?probe=181f7decc6) | May 24, 2022 |
| Dell          | 0Y2MRG A00                  | [08527b166e](https://linux-hardware.org/?probe=08527b166e) | May 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1122022ae1](https://linux-hardware.org/?probe=1122022ae1) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | MAHOBAY                     | [dbfb736222](https://linux-hardware.org/?probe=dbfb736222) | May 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [78bb2ba75c](https://linux-hardware.org/?probe=78bb2ba75c) | May 23, 2022 |
| Foxconn       | 2ABF                        | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [21818b99b4](https://linux-hardware.org/?probe=21818b99b4) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [f1db82519f](https://linux-hardware.org/?probe=f1db82519f) | May 22, 2022 |
| MSI           | MEG Z390 ACE                | [0065576586](https://linux-hardware.org/?probe=0065576586) | May 22, 2022 |
| Gigabyte      | H67N-USB3-B3                | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| ASRock        | B450 Steel Legend           | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| ASUSTek       | P7P55D-E LX                 | [358e85c524](https://linux-hardware.org/?probe=358e85c524) | May 21, 2022 |
| MSI           | B250M PRO-VD                | [540e0831b1](https://linux-hardware.org/?probe=540e0831b1) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [a810336f3f](https://linux-hardware.org/?probe=a810336f3f) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [6993400976](https://linux-hardware.org/?probe=6993400976) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [2211d5c2a2](https://linux-hardware.org/?probe=2211d5c2a2) | May 20, 2022 |
| ASUSTek       | H110M-R                     | [7cae58580a](https://linux-hardware.org/?probe=7cae58580a) | May 20, 2022 |
| ASRock        | Z390 Phantom Gaming 4-IB    | [543ab770e8](https://linux-hardware.org/?probe=543ab770e8) | May 20, 2022 |
| Positivo      | POS-MI945AA                 | [0f9875e8fc](https://linux-hardware.org/?probe=0f9875e8fc) | May 19, 2022 |
| Lenovo        | MAHOBAY                     | [fa1f318919](https://linux-hardware.org/?probe=fa1f318919) | May 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [d94f4b0a43](https://linux-hardware.org/?probe=d94f4b0a43) | May 19, 2022 |
| Gigabyte      | B450 AORUS M                | [5ddfbf547b](https://linux-hardware.org/?probe=5ddfbf547b) | May 19, 2022 |
| Supermicro    | X8SIL                       | [66e8a4001f](https://linux-hardware.org/?probe=66e8a4001f) | May 18, 2022 |
| MSI           | B350M MORTAR                | [fd66fd9a5a](https://linux-hardware.org/?probe=fd66fd9a5a) | May 18, 2022 |
| Supermicro    | X8SIL                       | [5cb6f1067b](https://linux-hardware.org/?probe=5cb6f1067b) | May 18, 2022 |
| HP            | 8054                        | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| ASUSTek       | GA15DH                      | [ca68812bf2](https://linux-hardware.org/?probe=ca68812bf2) | May 17, 2022 |
| MSI           | Z270-A PRO                  | [f005623f03](https://linux-hardware.org/?probe=f005623f03) | May 17, 2022 |
| ASUSTek       | AM1M-A/BR                   | [e23e8291e0](https://linux-hardware.org/?probe=e23e8291e0) | May 17, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | [2f7a99c28b](https://linux-hardware.org/?probe=2f7a99c28b) | May 17, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [ee4e4a7bc7](https://linux-hardware.org/?probe=ee4e4a7bc7) | May 17, 2022 |
| Dell          | 040DDP A00                  | [4806ca2a7e](https://linux-hardware.org/?probe=4806ca2a7e) | May 17, 2022 |
| Gigabyte      | H310M S2H x.x               | [4d76b03e66](https://linux-hardware.org/?probe=4d76b03e66) | May 17, 2022 |
| ASUSTek       | Z87-K                       | [2daea316b2](https://linux-hardware.org/?probe=2daea316b2) | May 16, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [91d8b47a30](https://linux-hardware.org/?probe=91d8b47a30) | May 15, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [608664ce7a](https://linux-hardware.org/?probe=608664ce7a) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a049c51989](https://linux-hardware.org/?probe=a049c51989) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [0cc824e2a5](https://linux-hardware.org/?probe=0cc824e2a5) | May 13, 2022 |
| NZXT          | N7 B550                     | [73441bbfc4](https://linux-hardware.org/?probe=73441bbfc4) | May 12, 2022 |
| Unknown       | BTC79X5                     | [42b222eb65](https://linux-hardware.org/?probe=42b222eb65) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| AZW           | BT3 X                       | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| Gigabyte      | B660 AORUS MASTER DDR4      | [e5981a9f20](https://linux-hardware.org/?probe=e5981a9f20) | May 11, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| NZXT          | N7 B550                     | [147247dfb6](https://linux-hardware.org/?probe=147247dfb6) | May 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [396a39e5a6](https://linux-hardware.org/?probe=396a39e5a6) | May 10, 2022 |
| ASRock        | X370 Professional Gaming    | [1e22ba0468](https://linux-hardware.org/?probe=1e22ba0468) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [0b3cda16db](https://linux-hardware.org/?probe=0b3cda16db) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [90190717eb](https://linux-hardware.org/?probe=90190717eb) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| ASUSTek       | Z97-AR                      | [29c93ea162](https://linux-hardware.org/?probe=29c93ea162) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| ASRock        | X299 Taichi CLX             | [47a45fca48](https://linux-hardware.org/?probe=47a45fca48) | May 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8964a4c5ec](https://linux-hardware.org/?probe=8964a4c5ec) | May 08, 2022 |
| ECS           | Nettle3                     | [36f8cde007](https://linux-hardware.org/?probe=36f8cde007) | May 08, 2022 |
| ASUSTek       | PRIME X570-P                | [65d94c8458](https://linux-hardware.org/?probe=65d94c8458) | May 08, 2022 |
| ECS           | Nettle3                     | [646fb53a2c](https://linux-hardware.org/?probe=646fb53a2c) | May 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [61a4daec98](https://linux-hardware.org/?probe=61a4daec98) | May 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [180dd73bd6](https://linux-hardware.org/?probe=180dd73bd6) | May 07, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| MSI           | B450-A PRO                  | [5b5ceb0f53](https://linux-hardware.org/?probe=5b5ceb0f53) | May 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [4fe934e84d](https://linux-hardware.org/?probe=4fe934e84d) | May 06, 2022 |
| ASRock        | 970M Pro3                   | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| ASRock        | 970M Pro3                   | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [7b7f29e504](https://linux-hardware.org/?probe=7b7f29e504) | May 05, 2022 |
| ASRock        | X470 Taichi                 | [e133868179](https://linux-hardware.org/?probe=e133868179) | May 05, 2022 |
| ASRock        | X470 Taichi                 | [93d6fb1610](https://linux-hardware.org/?probe=93d6fb1610) | May 05, 2022 |
| ASRock        | A320M-HDV R4.0              | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| ASUSTek       | B85M-E                      | [2b6338d755](https://linux-hardware.org/?probe=2b6338d755) | May 04, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [7196bf2ec6](https://linux-hardware.org/?probe=7196bf2ec6) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [65a2309744](https://linux-hardware.org/?probe=65a2309744) | May 03, 2022 |
| Alienware     | 0CPDXD A00                  | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| ASUSTek       | B85M-E                      | [9645231d87](https://linux-hardware.org/?probe=9645231d87) | May 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [c0ef0738b5](https://linux-hardware.org/?probe=c0ef0738b5) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [4a09f5d3f3](https://linux-hardware.org/?probe=4a09f5d3f3) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [ab716981c3](https://linux-hardware.org/?probe=ab716981c3) | May 02, 2022 |
| Alienware     | 0P0JWX A00                  | [e6e1548aa1](https://linux-hardware.org/?probe=e6e1548aa1) | May 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [a456619489](https://linux-hardware.org/?probe=a456619489) | May 02, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [925447d7e9](https://linux-hardware.org/?probe=925447d7e9) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b1e331055f](https://linux-hardware.org/?probe=b1e331055f) | May 01, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [dec71580c4](https://linux-hardware.org/?probe=dec71580c4) | May 01, 2022 |
| Gigabyte      | X570S AERO G                | [ab6b8eaa71](https://linux-hardware.org/?probe=ab6b8eaa71) | May 01, 2022 |
| MSI           | 970 GAMING                  | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| MSI           | B450M GAMING PLUS           | [0929d58de7](https://linux-hardware.org/?probe=0929d58de7) | Apr 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [3edd5f05f7](https://linux-hardware.org/?probe=3edd5f05f7) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | [d45e1e88db](https://linux-hardware.org/?probe=d45e1e88db) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | [41cec63ac6](https://linux-hardware.org/?probe=41cec63ac6) | Apr 30, 2022 |
| EVGA          | X58 SLI Classified Tyler... | [07254f2dbb](https://linux-hardware.org/?probe=07254f2dbb) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [bce425f138](https://linux-hardware.org/?probe=bce425f138) | Apr 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [e37bc471b1](https://linux-hardware.org/?probe=e37bc471b1) | Apr 29, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [2b7167b16e](https://linux-hardware.org/?probe=2b7167b16e) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [aed5ee3ded](https://linux-hardware.org/?probe=aed5ee3ded) | Apr 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ab83eedd1f](https://linux-hardware.org/?probe=ab83eedd1f) | Apr 28, 2022 |
| MSI           | H55M-E23                    | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [46430e1117](https://linux-hardware.org/?probe=46430e1117) | Apr 28, 2022 |
| Dell          | 09KPNV A00                  | [5046e0575b](https://linux-hardware.org/?probe=5046e0575b) | Apr 28, 2022 |
| Dell          | 0NW73C A00                  | [344e2b816e](https://linux-hardware.org/?probe=344e2b816e) | Apr 28, 2022 |
| Dell          | 088DT1 A01                  | [b664b8720e](https://linux-hardware.org/?probe=b664b8720e) | Apr 28, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [19e0445e6f](https://linux-hardware.org/?probe=19e0445e6f) | Apr 27, 2022 |
| Dell          | 0R1PCR A00                  | [feec38a0f5](https://linux-hardware.org/?probe=feec38a0f5) | Apr 27, 2022 |
| Unknown       | Unknown                     | [82ad7e86b5](https://linux-hardware.org/?probe=82ad7e86b5) | Apr 27, 2022 |
| ASUSTek       | GA15DH                      | [30a22d7be3](https://linux-hardware.org/?probe=30a22d7be3) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| System76      | Thelio thelio-r2            | [aae937be8b](https://linux-hardware.org/?probe=aae937be8b) | Apr 25, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| MSI           | B250M BAZOOKA               | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.17.5-76051705-generic   | 155      | 44.29%  |
| 5.18.10-76051810-generic  | 67       | 19.14%  |
| 5.17.15-76051715-generic  | 62       | 17.71%  |
| 5.16.19-76051619-generic  | 40       | 11.43%  |
| 5.19.0-76051900-generic   | 23       | 6.57%   |
| 5.18.0-9.1-liquorix-amd64 | 1        | 0.29%   |
| 5.17.4-051704-generic     | 1        | 0.29%   |
| 5.16.15-76051615-generic  | 1        | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.5  | 155      | 44.29%  |
| 5.18.10 | 67       | 19.14%  |
| 5.17.15 | 62       | 17.71%  |
| 5.16.19 | 40       | 11.43%  |
| 5.19.0  | 23       | 6.57%   |
| 5.18.0  | 1        | 0.29%   |
| 5.17.4  | 1        | 0.29%   |
| 5.16.15 | 1        | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17    | 212      | 61.63%  |
| 5.18    | 68       | 19.77%  |
| 5.16    | 41       | 11.92%  |
| 5.19    | 23       | 6.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 331      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 318      | 96.07%  |
| KDE5       | 8        | 2.42%   |
| X-Cinnamon | 2        | 0.6%    |
| LXQt       | 1        | 0.3%    |
| Cinnamon   | 1        | 0.3%    |
| Unknown    | 1        | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 324      | 97.89%  |
| Wayland | 5        | 1.51%   |
| Tty     | 1        | 0.3%    |
| Unknown | 1        | 0.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 281      | 84.89%  |
| GDM3    | 46       | 13.9%   |
| SDDM    | 3        | 0.91%   |
| GDM     | 1        | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 201      | 60.54%  |
| pt_BR   | 16       | 4.82%   |
| en_GB   | 16       | 4.82%   |
| de_DE   | 16       | 4.82%   |
| C       | 16       | 4.82%   |
| en_CA   | 12       | 3.61%   |
| en_AU   | 10       | 3.01%   |
| fr_FR   | 8        | 2.41%   |
| pl_PL   | 5        | 1.51%   |
| sv_SE   | 4        | 1.2%    |
| es_ES   | 4        | 1.2%    |
| es_CL   | 3        | 0.9%    |
| nl_NL   | 2        | 0.6%    |
| ja_JP   | 2        | 0.6%    |
| en_IN   | 2        | 0.6%    |
| ru_RU   | 1        | 0.3%    |
| ro_RO   | 1        | 0.3%    |
| nl_BE   | 1        | 0.3%    |
| nb_NO   | 1        | 0.3%    |
| it_IT   | 1        | 0.3%    |
| fi_FI   | 1        | 0.3%    |
| es_UY   | 1        | 0.3%    |
| es_DO   | 1        | 0.3%    |
| en_IL   | 1        | 0.3%    |
| en_IE   | 1        | 0.3%    |
| en_FI   | 1        | 0.3%    |
| en_DK   | 1        | 0.3%    |
| de_AT   | 1        | 0.3%    |
| cs_CZ   | 1        | 0.3%    |
| Unknown | 1        | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 288      | 87.01%  |
| EFI  | 43       | 12.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 311      | 93.96%  |
| Btrfs   | 10       | 3.02%   |
| Overlay | 9        | 2.72%   |
| Xfs     | 1        | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 280      | 84.59%  |
| GPT     | 47       | 14.2%   |
| MBR     | 4        | 1.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 322      | 97.28%  |
| Yes       | 9        | 2.72%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 297      | 89.73%  |
| Yes       | 34       | 10.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 97       | 29.31%  |
| Gigabyte Technology | 69       | 20.85%  |
| MSI                 | 51       | 15.41%  |
| ASRock              | 27       | 8.16%   |
| Dell                | 22       | 6.65%   |
| Hewlett-Packard     | 16       | 4.83%   |
| Lenovo              | 12       | 3.63%   |
| Intel               | 4        | 1.21%   |
| Alienware           | 4        | 1.21%   |
| System76            | 3        | 0.91%   |
| Unknown             | 3        | 0.91%   |
| MACHINIST           | 2        | 0.6%    |
| Fujitsu             | 2        | 0.6%    |
| Foxconn             | 2        | 0.6%    |
| EVGA                | 2        | 0.6%    |
| BESSTAR Tech        | 2        | 0.6%    |
| Acer                | 2        | 0.6%    |
| Supermicro          | 1        | 0.3%    |
| Soyo                | 1        | 0.3%    |
| SIEMENS             | 1        | 0.3%    |
| Positivo            | 1        | 0.3%    |
| NZXT                | 1        | 0.3%    |
| Medion              | 1        | 0.3%    |
| ECS                 | 1        | 0.3%    |
| Biostar             | 1        | 0.3%    |
| AZW                 | 1        | 0.3%    |
| Apple               | 1        | 0.3%    |
| Acidanthera         | 1        | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| ASUS All Series                                    | 6        | 1.81%   |
| Gigabyte X570 AORUS ELITE                          | 5        | 1.51%   |
| Gigabyte B450 AORUS M                              | 4        | 1.21%   |
| ASUS TUF Gaming B550-PLUS                          | 4        | 1.21%   |
| ASUS PRIME B450M-A                                 | 4        | 1.21%   |
| MSI MS-7C02                                        | 3        | 0.91%   |
| Gigabyte B450M DS3H                                | 3        | 0.91%   |
| Dell OptiPlex 3020                                 | 3        | 0.91%   |
| ASUS ROG STRIX B550-I GAMING                       | 3        | 0.91%   |
| ASUS ROG STRIX B450-F GAMING                       | 3        | 0.91%   |
| ASUS ROG CROSSHAIR VIII DARK HERO                  | 3        | 0.91%   |
| ASUS P6X58D PREMIUM                                | 3        | 0.91%   |
| Unknown                                            | 3        | 0.91%   |
| System76 Thelio                                    | 2        | 0.6%    |
| MSI MS-7D54                                        | 2        | 0.6%    |
| MSI MS-7D32                                        | 2        | 0.6%    |
| MSI MS-7D25                                        | 2        | 0.6%    |
| MSI MS-7C91                                        | 2        | 0.6%    |
| MSI MS-7C37                                        | 2        | 0.6%    |
| MSI MS-7C35                                        | 2        | 0.6%    |
| MSI MS-7B89                                        | 2        | 0.6%    |
| MSI MS-7B86                                        | 2        | 0.6%    |
| MSI MS-7A32                                        | 2        | 0.6%    |
| MSI MS-7693                                        | 2        | 0.6%    |
| HP ProDesk 600 G1 SFF                              | 2        | 0.6%    |
| HP EliteDesk 705 G1 SFF                            | 2        | 0.6%    |
| Gigabyte Z170-HD3P                                 | 2        | 0.6%    |
| Gigabyte Z170-Gaming K3                            | 2        | 0.6%    |
| Gigabyte X570 I AORUS PRO WIFI                     | 2        | 0.6%    |
| Gigabyte X570 AORUS MASTER                         | 2        | 0.6%    |
| Gigabyte B450M DS3H WIFI                           | 2        | 0.6%    |
| Gigabyte AB350-Gaming 3                            | 2        | 0.6%    |
| BESSTAR Tech UM700                                 | 2        | 0.6%    |
| ASUS TUF B450M-PLUS GAMING                         | 2        | 0.6%    |
| ASUS ROG STRIX B550-F GAMING                       | 2        | 0.6%    |
| ASUS ROG STRIX B450-I GAMING                       | 2        | 0.6%    |
| ASUS ROG Maximus XI HERO                           | 2        | 0.6%    |
| ASUS ROG CROSSHAIR VIII HERO                       | 2        | 0.6%    |
| ASUS PRIME Z390-A                                  | 2        | 0.6%    |
| ASUS M5A78L-M/USB3                                 | 2        | 0.6%    |
| ASRock X470 Taichi                                 | 2        | 0.6%    |
| ASRock B450 Gaming K4                              | 2        | 0.6%    |
| Alienware Aurora R8                                | 2        | 0.6%    |
| System76 Thelio Major                              | 1        | 0.3%    |
| Supermicro X8SIL                                   | 1        | 0.3%    |
| Soyo SY-A68M FS V2.0                               | 1        | 0.3%    |
| SIEMENS SIMATIC BOX PC 627B/PANEL PC 677B Profibus | 1        | 0.3%    |
| Positivo POS-MI945AA                               | 1        | 0.3%    |
| NZXT N7 B550                                       | 1        | 0.3%    |
| MSI MS-7D28                                        | 1        | 0.3%    |
| MSI MS-7D09                                        | 1        | 0.3%    |
| MSI MS-7C96                                        | 1        | 0.3%    |
| MSI MS-7C75                                        | 1        | 0.3%    |
| MSI MS-7C56                                        | 1        | 0.3%    |
| MSI MS-7B87                                        | 1        | 0.3%    |
| MSI MS-7B85                                        | 1        | 0.3%    |
| MSI MS-7B17                                        | 1        | 0.3%    |
| MSI MS-7B12                                        | 1        | 0.3%    |
| MSI MS-7A74                                        | 1        | 0.3%    |
| MSI MS-7A71                                        | 1        | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 32       | 9.67%   |
| ASUS PRIME            | 17       | 5.14%   |
| ASUS TUF              | 11       | 3.32%   |
| Gigabyte X570         | 10       | 3.02%   |
| Dell OptiPlex         | 9        | 2.72%   |
| Lenovo ThinkCentre    | 7        | 2.11%   |
| HP Compaq             | 6        | 1.81%   |
| Gigabyte B450         | 6        | 1.81%   |
| Dell Precision        | 6        | 1.81%   |
| ASUS All              | 6        | 1.81%   |
| HP EliteDesk          | 5        | 1.51%   |
| Gigabyte B450M        | 5        | 1.51%   |
| Dell Inspiron         | 4        | 1.21%   |
| ASRock B450           | 4        | 1.21%   |
| Alienware Aurora      | 4        | 1.21%   |
| System76 Thelio       | 3        | 0.91%   |
| MSI MS-7C02           | 3        | 0.91%   |
| Gigabyte B550         | 3        | 0.91%   |
| Gigabyte AB350-Gaming | 3        | 0.91%   |
| Dell XPS              | 3        | 0.91%   |
| ASUS P6X58D           | 3        | 0.91%   |
| ASRock B450M          | 3        | 0.91%   |
| Unknown               | 3        | 0.91%   |
| MSI MS-7D54           | 2        | 0.6%    |
| MSI MS-7D32           | 2        | 0.6%    |
| MSI MS-7D25           | 2        | 0.6%    |
| MSI MS-7C91           | 2        | 0.6%    |
| MSI MS-7C37           | 2        | 0.6%    |
| MSI MS-7C35           | 2        | 0.6%    |
| MSI MS-7B89           | 2        | 0.6%    |
| MSI MS-7B86           | 2        | 0.6%    |
| MSI MS-7A32           | 2        | 0.6%    |
| MSI MS-7693           | 2        | 0.6%    |
| Lenovo IdeaCentre     | 2        | 0.6%    |
| HP ProDesk            | 2        | 0.6%    |
| Gigabyte Z390         | 2        | 0.6%    |
| Gigabyte Z170-HD3P    | 2        | 0.6%    |
| Gigabyte Z170-Gaming  | 2        | 0.6%    |
| Gigabyte X470         | 2        | 0.6%    |
| Gigabyte H310M        | 2        | 0.6%    |
| Gigabyte B550M        | 2        | 0.6%    |
| Fujitsu ESPRIMO       | 2        | 0.6%    |
| BESSTAR Tech UM700    | 2        | 0.6%    |
| ASUS P8Z77-V          | 2        | 0.6%    |
| ASUS M5A78L-M         | 2        | 0.6%    |
| ASRock Z390           | 2        | 0.6%    |
| ASRock X470           | 2        | 0.6%    |
| ASRock X370           | 2        | 0.6%    |
| ASRock B550           | 2        | 0.6%    |
| Supermicro X8SIL      | 1        | 0.3%    |
| Soyo SY-A68M          | 1        | 0.3%    |
| SIEMENS SIMATIC       | 1        | 0.3%    |
| Positivo POS-MI945AA  | 1        | 0.3%    |
| NZXT N7               | 1        | 0.3%    |
| MSI MS-7D28           | 1        | 0.3%    |
| MSI MS-7D09           | 1        | 0.3%    |
| MSI MS-7C96           | 1        | 0.3%    |
| MSI MS-7C75           | 1        | 0.3%    |
| MSI MS-7C56           | 1        | 0.3%    |
| MSI MS-7B87           | 1        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 54       | 16.31%  |
| 2020 | 40       | 12.08%  |
| 2019 | 38       | 11.48%  |
| 2021 | 35       | 10.57%  |
| 2017 | 21       | 6.34%   |
| 2014 | 19       | 5.74%   |
| 2011 | 19       | 5.74%   |
| 2013 | 18       | 5.44%   |
| 2012 | 18       | 5.44%   |
| 2016 | 16       | 4.83%   |
| 2015 | 13       | 3.93%   |
| 2010 | 12       | 3.63%   |
| 2022 | 10       | 3.02%   |
| 2009 | 9        | 2.72%   |
| 2008 | 5        | 1.51%   |
| 2007 | 3        | 0.91%   |
| 2006 | 1        | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 331      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 330      | 99.7%   |
| Enabled  | 1        | 0.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 331      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 111      | 33.13%  |
| 32.01-64.0      | 83       | 24.78%  |
| 8.01-16.0       | 57       | 17.01%  |
| 64.01-256.0     | 32       | 9.55%   |
| 4.01-8.0        | 28       | 8.36%   |
| 3.01-4.0        | 16       | 4.78%   |
| 24.01-32.0      | 4        | 1.19%   |
| More than 256.0 | 2        | 0.6%    |
| 2.01-3.0        | 1        | 0.3%    |
| 1.01-2.0        | 1        | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 101      | 28.77%  |
| 4.01-8.0   | 92       | 26.21%  |
| 3.01-4.0   | 86       | 24.5%   |
| 1.01-2.0   | 45       | 12.82%  |
| 8.01-16.0  | 19       | 5.41%   |
| 16.01-24.0 | 5        | 1.42%   |
| 32.01-64.0 | 3        | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 120      | 36.04%  |
| 1      | 85       | 25.53%  |
| 3      | 71       | 21.32%  |
| 4      | 22       | 6.61%   |
| 5      | 15       | 4.5%    |
| 6      | 12       | 3.6%    |
| 7      | 5        | 1.5%    |
| 11     | 1        | 0.3%    |
| 10     | 1        | 0.3%    |
| 9      | 1        | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 229      | 68.98%  |
| Yes       | 103      | 31.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 327      | 98.79%  |
| No        | 4        | 1.21%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 190      | 57.4%   |
| No        | 141      | 42.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 194      | 58.43%  |
| Yes       | 138      | 41.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| USA                | 136      | 40.96%  |
| Germany            | 21       | 6.33%   |
| Canada             | 18       | 5.42%   |
| Brazil             | 18       | 5.42%   |
| UK                 | 13       | 3.92%   |
| Australia          | 12       | 3.61%   |
| Netherlands        | 11       | 3.31%   |
| France             | 10       | 3.01%   |
| Norway             | 7        | 2.11%   |
| Sweden             | 5        | 1.51%   |
| Austria            | 5        | 1.51%   |
| Switzerland        | 4        | 1.2%    |
| Spain              | 4        | 1.2%    |
| Poland             | 4        | 1.2%    |
| Mexico             | 4        | 1.2%    |
| Japan              | 4        | 1.2%    |
| Italy              | 4        | 1.2%    |
| Ireland            | 4        | 1.2%    |
| Romania            | 3        | 0.9%    |
| India              | 3        | 0.9%    |
| Finland            | 3        | 0.9%    |
| Chile              | 3        | 0.9%    |
| Belgium            | 3        | 0.9%    |
| Thailand           | 2        | 0.6%    |
| South Africa       | 2        | 0.6%    |
| Russia             | 2        | 0.6%    |
| Philippines        | 2        | 0.6%    |
| Hong Kong          | 2        | 0.6%    |
| Greece             | 2        | 0.6%    |
| Czechia            | 2        | 0.6%    |
| Uruguay            | 1        | 0.3%    |
| Turkey             | 1        | 0.3%    |
| Tunisia            | 1        | 0.3%    |
| South Korea        | 1        | 0.3%    |
| Slovenia           | 1        | 0.3%    |
| Slovakia           | 1        | 0.3%    |
| Saudi Arabia       | 1        | 0.3%    |
| Portugal           | 1        | 0.3%    |
| Nicaragua          | 1        | 0.3%    |
| Lithuania          | 1        | 0.3%    |
| Jordan             | 1        | 0.3%    |
| Israel             | 1        | 0.3%    |
| Indonesia          | 1        | 0.3%    |
| Hungary            | 1        | 0.3%    |
| Dominican Republic | 1        | 0.3%    |
| Denmark            | 1        | 0.3%    |
| Colombia           | 1        | 0.3%    |
| Azerbaijan         | 1        | 0.3%    |
| Argentina          | 1        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| San Francisco       | 4        | 1.19%   |
| Berlin              | 4        | 1.19%   |
| Vienna              | 3        | 0.9%    |
| Sydney              | 3        | 0.9%    |
| Seattle             | 3        | 0.9%    |
| Cleveland           | 3        | 0.9%    |
| Bedford             | 3        | 0.9%    |
| Zurich              | 2        | 0.6%    |
| Weimar              | 2        | 0.6%    |
| Trondheim           | 2        | 0.6%    |
| Springfield         | 2        | 0.6%    |
| Sapporo             | 2        | 0.6%    |
| Sao Paulo           | 2        | 0.6%    |
| Richmond            | 2        | 0.6%    |
| Ogden               | 2        | 0.6%    |
| Melbourne           | 2        | 0.6%    |
| Mannheim            | 2        | 0.6%    |
| Madrid              | 2        | 0.6%    |
| Ludwigsburg         | 2        | 0.6%    |
| Kolkata             | 2        | 0.6%    |
| Goiânia            | 2        | 0.6%    |
| Fresno              | 2        | 0.6%    |
| Dublin              | 2        | 0.6%    |
| Chicago             | 2        | 0.6%    |
| Broomfield          | 2        | 0.6%    |
| Brisbane            | 2        | 0.6%    |
| Atlanta             | 2        | 0.6%    |
| Żyrardów          | 1        | 0.3%    |
| Zaragoza            | 1        | 0.3%    |
| Zapopan             | 1        | 0.3%    |
| Yekaterinburg       | 1        | 0.3%    |
| Woodstock           | 1        | 0.3%    |
| Winter Garden       | 1        | 0.3%    |
| Wilmslow            | 1        | 0.3%    |
| Wichita             | 1        | 0.3%    |
| Weston-super-Mare   | 1        | 0.3%    |
| Westland            | 1        | 0.3%    |
| Wausau              | 1        | 0.3%    |
| Wasilla             | 1        | 0.3%    |
| Walker              | 1        | 0.3%    |
| Virginia Beach      | 1        | 0.3%    |
| Vilnius             | 1        | 0.3%    |
| Vicksburg           | 1        | 0.3%    |
| Ventura             | 1        | 0.3%    |
| Vedevag             | 1        | 0.3%    |
| Västerås          | 1        | 0.3%    |
| Varel               | 1        | 0.3%    |
| Valparaiso de Goias | 1        | 0.3%    |
| Valparaiso          | 1        | 0.3%    |
| Vallenar            | 1        | 0.3%    |
| Utrecht             | 1        | 0.3%    |
| Union               | 1        | 0.3%    |
| Turku               | 1        | 0.3%    |
| Tunis               | 1        | 0.3%    |
| Tuen Mun            | 1        | 0.3%    |
| Tucson              | 1        | 0.3%    |
| Tuam                | 1        | 0.3%    |
| Toronto             | 1        | 0.3%    |
| Thessaloniki        | 1        | 0.3%    |
| Theilingen          | 1        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 127      | 183    | 18.81%  |
| Seagate                   | 120      | 172    | 17.78%  |
| WDC                       | 104      | 151    | 15.41%  |
| Crucial                   | 45       | 66     | 6.67%   |
| SanDisk                   | 42       | 51     | 6.22%   |
| Toshiba                   | 33       | 38     | 4.89%   |
| Kingston                  | 29       | 38     | 4.3%    |
| Phison                    | 18       | 23     | 2.67%   |
| Hitachi                   | 17       | 23     | 2.52%   |
| Intel                     | 14       | 15     | 2.07%   |
| A-DATA Technology         | 12       | 13     | 1.78%   |
| China                     | 10       | 11     | 1.48%   |
| Silicon Motion            | 8        | 11     | 1.19%   |
| Micron/Crucial Technology | 8        | 10     | 1.19%   |
| PNY                       | 7        | 9      | 1.04%   |
| SPCC                      | 6        | 9      | 0.89%   |
| Micron Technology         | 6        | 7      | 0.89%   |
| SK hynix                  | 5        | 5      | 0.74%   |
| OCZ                       | 5        | 5      | 0.74%   |
| Hewlett-Packard           | 4        | 4      | 0.59%   |
| Unknown                   | 3        | 4      | 0.44%   |
| Patriot                   | 3        | 3      | 0.44%   |
| Maxtor                    | 3        | 3      | 0.44%   |
| Lexar                     | 3        | 3      | 0.44%   |
| Intenso                   | 3        | 3      | 0.44%   |
| HGST                      | 3        | 3      | 0.44%   |
| XPG                       | 2        | 2      | 0.3%    |
| WALRAM                    | 2        | 2      | 0.3%    |
| Mushkin                   | 2        | 3      | 0.3%    |
| LITEON                    | 2        | 2      | 0.3%    |
| JMicron Technology        | 2        | 2      | 0.3%    |
| Fujitsu                   | 2        | 3      | 0.3%    |
| Corsair                   | 2        | 3      | 0.3%    |
| Apple                     | 2        | 2      | 0.3%    |
| TurXun                    | 1        | 1      | 0.15%   |
| Transcend                 | 1        | 2      | 0.15%   |
| TO Exter                  | 1        | 1      | 0.15%   |
| T-FORCE                   | 1        | 2      | 0.15%   |
| Realtek Semiconductor     | 1        | 1      | 0.15%   |
| Qunion                    | 1        | 2      | 0.15%   |
| PNY USB                   | 1        | 1      | 0.15%   |
| Plextor                   | 1        | 1      | 0.15%   |
| MaxDigital                | 1        | 1      | 0.15%   |
| Mass                      | 1        | 1      | 0.15%   |
| KXG60ZNV                  | 1        | 1      | 0.15%   |
| KingFast                  | 1        | 2      | 0.15%   |
| Indilinx                  | 1        | 1      | 0.15%   |
| HS-SSD-E100N              | 1        | 1      | 0.15%   |
| HS-SSD-C100               | 1        | 2      | 0.15%   |
| Gigabyte Technology       | 1        | 1      | 0.15%   |
| GALAX                     | 1        | 1      | 0.15%   |
| FORESEE                   | 1        | 2      | 0.15%   |
| ASMT                      | 1        | 1      | 0.15%   |
| Apacer                    | 1        | 1      | 0.15%   |
| Unknown                   | 1        | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB          | 24       | 2.99%   |
| Seagate ST2000DM008-2FR102 2TB      | 18       | 2.24%   |
| Samsung NVMe SSD Drive 500GB        | 15       | 1.87%   |
| SanDisk NVMe SSD Drive 1TB          | 13       | 1.62%   |
| Samsung SSD 860 EVO 1TB             | 9        | 1.12%   |
| Samsung SSD 850 EVO 500GB           | 9        | 1.12%   |
| Samsung NVMe SSD Drive 2TB          | 9        | 1.12%   |
| Samsung SSD 850 EVO 250GB           | 8        | 1%      |
| WDC WD10EZEX-08WN4A0 1TB            | 7        | 0.87%   |
| Seagate ST500DM002-1BD142 500GB     | 7        | 0.87%   |
| Seagate ST4000DM004-2CV104 4TB      | 7        | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB      | 7        | 0.87%   |
| Seagate ST1000DM003-1CH162 1TB      | 7        | 0.87%   |
| Phison NVMe SSD Drive 1TB           | 7        | 0.87%   |
| Kingston SA400S37240G 240GB SSD     | 7        | 0.87%   |
| Crucial CT2000MX500SSD1 2TB         | 7        | 0.87%   |
| Crucial CT1000MX500SSD1 1TB         | 7        | 0.87%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 6        | 0.75%   |
| Seagate ST1000DM003-1ER162 1TB      | 6        | 0.75%   |
| SanDisk NVMe SSD Drive 500GB        | 6        | 0.75%   |
| Samsung SSD 860 EVO 500GB           | 6        | 0.75%   |
| Micron/Crucial NVMe SSD Drive 1TB   | 6        | 0.75%   |
| Kingston SA400S37120G 120GB SSD     | 6        | 0.75%   |
| Seagate Expansion 500GB             | 5        | 0.62%   |
| Samsung SSD 970 EVO Plus 1TB        | 5        | 0.62%   |
| Phison NVMe SSD Drive 2TB           | 5        | 0.62%   |
| Crucial CT1000BX500SSD1 1TB         | 5        | 0.62%   |
| WDC WD30EFRX-68EUZN0 3TB            | 4        | 0.5%    |
| Toshiba HDWD120 2TB                 | 4        | 0.5%    |
| Toshiba DT01ACA200 2TB              | 4        | 0.5%    |
| Toshiba DT01ACA100 1TB              | 4        | 0.5%    |
| Seagate ST8000DM004-2CX188 8TB      | 4        | 0.5%    |
| Seagate ST4000DM000-1F2168 4TB      | 4        | 0.5%    |
| Seagate ST31000528AS 1TB            | 4        | 0.5%    |
| Seagate ST2000DM001-1ER164 2TB      | 4        | 0.5%    |
| SanDisk NVMe SSD Drive 512GB        | 4        | 0.5%    |
| PNY CS900 500GB SSD                 | 4        | 0.5%    |
| Kingston SV300S37A120G 120GB SSD    | 4        | 0.5%    |
| WDC WDS100T3X0C-00SJG0 1TB          | 3        | 0.37%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 3        | 0.37%   |
| WDC WD20EZAZ-00GGJB0 2TB            | 3        | 0.37%   |
| WDC WD20EARS-00MVWB0 2TB            | 3        | 0.37%   |
| WDC WD10EZEX-08M2NA0 1TB            | 3        | 0.37%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3        | 0.37%   |
| WDC WD10EZEX-00BN5A0 1TB            | 3        | 0.37%   |
| Toshiba DT01ACA050 500GB            | 3        | 0.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 0.37%   |
| Seagate ST3500418AS 500GB           | 3        | 0.37%   |
| Seagate ST31000524AS 1TB            | 3        | 0.37%   |
| Seagate ST2000DX002-2DV164 2TB      | 3        | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB      | 3        | 0.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3        | 0.37%   |
| Seagate ST1000DM003-1SB10C 1TB      | 3        | 0.37%   |
| Seagate NVMe SSD Drive 1TB          | 3        | 0.37%   |
| SanDisk SSD PLUS 240GB              | 3        | 0.37%   |
| Samsung SSD 970 EVO 500GB           | 3        | 0.37%   |
| Samsung SSD 870 EVO 250GB           | 3        | 0.37%   |
| Samsung SSD 860 EVO M.2 500GB       | 3        | 0.37%   |
| Samsung NVMe SSD Drive 512GB        | 3        | 0.37%   |
| Phison NVMe SSD Drive 1024GB        | 3        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 114      | 161    | 42.07%  |
| WDC                 | 87       | 121    | 32.1%   |
| Toshiba             | 30       | 35     | 11.07%  |
| Hitachi             | 17       | 23     | 6.27%   |
| Samsung Electronics | 13       | 17     | 4.8%    |
| HGST                | 3        | 3      | 1.11%   |
| Maxtor              | 2        | 2      | 0.74%   |
| Apple               | 2        | 2      | 0.74%   |
| Unknown             | 1        | 1      | 0.37%   |
| Fujitsu             | 1        | 2      | 0.37%   |
| ASMT                | 1        | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 57       | 80     | 24.46%  |
| Crucial             | 41       | 59     | 17.6%   |
| Kingston            | 26       | 32     | 11.16%  |
| WDC                 | 19       | 23     | 8.15%   |
| SanDisk             | 15       | 18     | 6.44%   |
| A-DATA Technology   | 10       | 11     | 4.29%   |
| China               | 9        | 10     | 3.86%   |
| PNY                 | 7        | 9      | 3%      |
| Intel               | 7        | 7      | 3%      |
| OCZ                 | 5        | 5      | 2.15%   |
| SPCC                | 4        | 5      | 1.72%   |
| SK hynix            | 3        | 3      | 1.29%   |
| Patriot             | 3        | 3      | 1.29%   |
| Lexar               | 3        | 3      | 1.29%   |
| Hewlett-Packard     | 3        | 3      | 1.29%   |
| Toshiba             | 2        | 2      | 0.86%   |
| Mushkin             | 2        | 3      | 0.86%   |
| Micron Technology   | 2        | 2      | 0.86%   |
| Transcend           | 1        | 2      | 0.43%   |
| TO Exter            | 1        | 1      | 0.43%   |
| Seagate             | 1        | 1      | 0.43%   |
| PNY USB             | 1        | 1      | 0.43%   |
| Plextor             | 1        | 1      | 0.43%   |
| Maxtor              | 1        | 1      | 0.43%   |
| LITEON              | 1        | 1      | 0.43%   |
| JMicron Technology  | 1        | 1      | 0.43%   |
| Intenso             | 1        | 1      | 0.43%   |
| HS-SSD-E100N        | 1        | 1      | 0.43%   |
| Gigabyte Technology | 1        | 1      | 0.43%   |
| Fujitsu             | 1        | 1      | 0.43%   |
| FORESEE             | 1        | 2      | 0.43%   |
| Corsair             | 1        | 2      | 0.43%   |
| Apacer              | 1        | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 211      | 368    | 37.21%  |
| SSD     | 193      | 296    | 34.04%  |
| NVMe    | 141      | 217    | 24.87%  |
| Unknown | 21       | 27     | 3.7%    |
| MMC     | 1        | 1      | 0.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 293      | 652    | 63.15%  |
| NVMe | 141      | 217    | 30.39%  |
| SAS  | 29       | 39     | 6.25%   |
| MMC  | 1        | 1      | 0.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 192      | 295    | 40.94%  |
| 0.51-1.0   | 135      | 196    | 28.78%  |
| 1.01-2.0   | 86       | 102    | 18.34%  |
| 3.01-4.0   | 26       | 31     | 5.54%   |
| 4.01-10.0  | 15       | 20     | 3.2%    |
| 2.01-3.0   | 14       | 17     | 2.99%   |
| 10.01-20.0 | 1        | 3      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 72       | 21.36%  |
| 251-500        | 60       | 17.8%   |
| 1001-2000      | 59       | 17.51%  |
| 101-250        | 54       | 16.02%  |
| More than 3000 | 44       | 13.06%  |
| 2001-3000      | 22       | 6.53%   |
| 1-20           | 11       | 3.26%   |
| 51-100         | 8        | 2.37%   |
| 21-50          | 4        | 1.19%   |
| Unknown        | 3        | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 82       | 23.84%  |
| 21-50          | 54       | 15.7%   |
| 101-250        | 47       | 13.66%  |
| 51-100         | 43       | 12.5%   |
| 251-500        | 39       | 11.34%  |
| 1001-2000      | 26       | 7.56%   |
| 501-1000       | 25       | 7.27%   |
| More than 3000 | 18       | 5.23%   |
| 2001-3000      | 7        | 2.03%   |
| Unknown        | 3        | 0.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD5001AALS-00J7B1 500GB                  | 1        | 1      | 5.88%   |
| WDC WD5000AADS-00S9B0 500GB                  | 1        | 1      | 5.88%   |
| WDC WD20EFRX-68AX9N0 2TB                     | 1        | 2      | 5.88%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1        | 1      | 5.88%   |
| WDC WD1001FALS-00E8B0 1TB                    | 1        | 1      | 5.88%   |
| Seagate ST5000LM000-2AN170 5TB               | 1        | 1      | 5.88%   |
| Seagate ST320LM001 HN-M320MBB 320GB          | 1        | 1      | 5.88%   |
| Seagate ST2000DM008-2FR102 2TB               | 1        | 1      | 5.88%   |
| Seagate ST2000DM006-2DM164 2TB               | 1        | 1      | 5.88%   |
| Samsung Electronics SSD 850 PRO 256GB        | 1        | 1      | 5.88%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 1        | 1      | 5.88%   |
| Samsung Electronics HD103SI 1TB              | 1        | 1      | 5.88%   |
| Plextor PX-128M6M 128GB SSD                  | 1        | 1      | 5.88%   |
| Kingston SV300S37A240G 240GB SSD             | 1        | 1      | 5.88%   |
| Hitachi HDP725050GLA360 500GB                | 1        | 1      | 5.88%   |
| Crucial CT525MX300SSD1 528GB                 | 1        | 1      | 5.88%   |
| A-DATA Technology SU800 512GB SSD            | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 31.25%  |
| Seagate             | 3        | 4      | 18.75%  |
| Samsung Electronics | 3        | 3      | 18.75%  |
| Plextor             | 1        | 1      | 6.25%   |
| Kingston            | 1        | 1      | 6.25%   |
| Hitachi             | 1        | 1      | 6.25%   |
| Crucial             | 1        | 1      | 6.25%   |
| A-DATA Technology   | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 50%     |
| Seagate             | 3        | 4      | 30%     |
| Samsung Electronics | 1        | 1      | 10%     |
| Hitachi             | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 12     | 62.5%   |
| SSD  | 6        | 6      | 37.5%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 286      | 764    | 80.11%  |
| Works    | 57       | 127    | 15.97%  |
| Malfunc  | 14       | 18     | 3.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 177      | 32.96%  |
| AMD                          | 155      | 28.86%  |
| Samsung Electronics          | 74       | 13.78%  |
| SanDisk                      | 29       | 5.4%    |
| Phison Electronics           | 22       | 4.1%    |
| ASMedia Technology           | 17       | 3.17%   |
| Micron/Crucial Technology    | 12       | 2.23%   |
| Silicon Motion               | 10       | 1.86%   |
| Marvell Technology Group     | 8        | 1.49%   |
| Seagate Technology           | 4        | 0.74%   |
| Nvidia                       | 4        | 0.74%   |
| Micron Technology            | 4        | 0.74%   |
| Kingston Technology Company  | 4        | 0.74%   |
| JMicron Technology           | 3        | 0.56%   |
| ADATA Technology             | 3        | 0.56%   |
| SK hynix                     | 2        | 0.37%   |
| Silicon Image                | 2        | 0.37%   |
| Realtek Semiconductor        | 2        | 0.37%   |
| VIA Technologies             | 1        | 0.19%   |
| Toshiba America Info Systems | 1        | 0.19%   |
| LSI Logic / Symbios Logic    | 1        | 0.19%   |
| Lite-On Technology           | 1        | 0.19%   |
| Broadcom / LSI               | 1        | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 99       | 15.21%  |
| AMD 400 Series Chipset SATA Controller                                                  | 47       | 7.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 44       | 6.76%   |
| AMD 500 Series Chipset SATA Controller                                                  | 28       | 4.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 20       | 3.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18       | 2.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 18       | 2.76%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 16       | 2.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14       | 2.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14       | 2.15%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 1.84%   |
| Phison E12 NVMe Controller                                                              | 11       | 1.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 1.54%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 10       | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 1.54%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9        | 1.38%   |
| Samsung NVMe SSD Controller 980                                                         | 9        | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 1.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 7        | 1.08%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 7        | 1.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 1.08%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 1.08%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 1.08%   |
| AMD X370 Series Chipset SATA Controller                                                 | 7        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 0.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 0.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 5        | 0.77%   |
| SanDisk Non-Volatile memory controller                                                  | 5        | 0.77%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 5        | 0.77%   |
| Intel SSD 660P Series                                                                   | 5        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.77%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 4        | 0.61%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4        | 0.61%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 4        | 0.61%   |
| Micron Non-Volatile memory controller                                                   | 4        | 0.61%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.46%   |
| Seagate FireCuda 530 SSD                                                                | 3        | 0.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 0.46%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3        | 0.46%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3        | 0.46%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.46%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.46%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.46%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 0.46%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 0.46%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.46%   |
| AMD FCH SATA Controller D                                                               | 3        | 0.46%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.46%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2        | 0.31%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 2        | 0.31%   |
| Micron/Crucial NVMe Controller                                                          | 2        | 0.31%   |
| Micron/Crucial Non-Volatile memory controller                                           | 2        | 0.31%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.31%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 2        | 0.31%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 2        | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 291      | 57.74%  |
| NVMe | 142      | 28.17%  |
| IDE  | 46       | 9.13%   |
| RAID | 23       | 4.56%   |
| SAS  | 2        | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 172      | 51.96%  |
| AMD    | 159      | 48.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 18       | 5.42%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 12       | 3.61%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 10       | 3.01%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 9        | 2.71%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 8        | 2.41%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 7        | 2.11%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 6        | 1.81%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 6        | 1.81%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 6        | 1.81%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 5        | 1.51%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 5        | 1.51%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 5        | 1.51%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 5        | 1.51%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 5        | 1.51%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 4        | 1.2%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4        | 1.2%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4        | 1.2%    |
| Intel Core i5-6600K CPU @ 3.50GHz             | 4        | 1.2%    |
| AMD Ryzen 9 3950X 16-Core Processor           | 4        | 1.2%    |
| AMD Ryzen 7 1700 Eight-Core Processor         | 4        | 1.2%    |
| AMD Ryzen 5 2600X Six-Core Processor          | 4        | 1.2%    |
| AMD FX-8350 Eight-Core Processor              | 4        | 1.2%    |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3        | 0.9%    |
| Intel Core i7-9700K CPU @ 3.60GHz             | 3        | 0.9%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3        | 0.9%    |
| Intel Core i7 CPU 950 @ 3.07GHz               | 3        | 0.9%    |
| Intel Core i5-9600K CPU @ 3.70GHz             | 3        | 0.9%    |
| Intel Core i5-3570K CPU @ 3.40GHz             | 3        | 0.9%    |
| Intel Core i5 CPU 650 @ 3.20GHz               | 3        | 0.9%    |
| Intel 12th Gen Core i9-12900K                 | 3        | 0.9%    |
| AMD Ryzen 7 1800X Eight-Core Processor        | 3        | 0.9%    |
| AMD Ryzen 5 3600X 6-Core Processor            | 3        | 0.9%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 3        | 0.9%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 3        | 0.9%    |
| AMD Ryzen 5 1600X Six-Core Processor          | 3        | 0.9%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 3        | 0.9%    |
| AMD FX-6300 Six-Core Processor                | 3        | 0.9%    |
| Intel Core i9-10900X CPU @ 3.70GHz            | 2        | 0.6%    |
| Intel Core i7-9700 CPU @ 3.00GHz              | 2        | 0.6%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2        | 0.6%    |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2        | 0.6%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2        | 0.6%    |
| Intel Core i5-9400 CPU @ 2.90GHz              | 2        | 0.6%    |
| Intel Core i5-6600 CPU @ 3.30GHz              | 2        | 0.6%    |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2        | 0.6%    |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2        | 0.6%    |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2        | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2        | 0.6%    |
| Intel Core i5-2500K CPU @ 3.30GHz             | 2        | 0.6%    |
| Intel Core i5-10400F CPU @ 2.90GHz            | 2        | 0.6%    |
| Intel Core i5 CPU 760 @ 2.80GHz               | 2        | 0.6%    |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2        | 0.6%    |
| Intel Core i3-4150 CPU @ 3.50GHz              | 2        | 0.6%    |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2        | 0.6%    |
| Intel Core i3-10105 CPU @ 3.70GHz             | 2        | 0.6%    |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 2        | 0.6%    |
| Intel 12th Gen Core i7-12700K                 | 2        | 0.6%    |
| Intel 12th Gen Core i5-12600K                 | 2        | 0.6%    |
| Intel 11th Gen Core i7-11700K @ 3.60GHz       | 2        | 0.6%    |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 58       | 17.47%  |
| Intel Core i7           | 52       | 15.66%  |
| Intel Core i5           | 51       | 15.36%  |
| AMD Ryzen 7             | 40       | 12.05%  |
| AMD Ryzen 9             | 26       | 7.83%   |
| Other                   | 14       | 4.22%   |
| Intel Core i3           | 14       | 4.22%   |
| Intel Xeon              | 11       | 3.31%   |
| AMD FX                  | 10       | 3.01%   |
| Intel Core i9           | 9        | 2.71%   |
| Intel Core 2 Quad       | 5        | 1.51%   |
| AMD A8                  | 4        | 1.2%    |
| Intel Pentium Gold      | 3        | 0.9%    |
| Intel Pentium           | 3        | 0.9%    |
| Intel Celeron           | 3        | 0.9%    |
| AMD Ryzen Threadripper  | 3        | 0.9%    |
| Intel Pentium D         | 2        | 0.6%    |
| Intel Core 2            | 2        | 0.6%    |
| AMD Ryzen 3             | 2        | 0.6%    |
| AMD Phenom II X4        | 2        | 0.6%    |
| AMD Phenom              | 2        | 0.6%    |
| AMD Athlon II X4        | 2        | 0.6%    |
| AMD Athlon II X2        | 2        | 0.6%    |
| AMD A4                  | 2        | 0.6%    |
| Intel Pentium Dual-Core | 1        | 0.3%    |
| Intel Pentium Dual      | 1        | 0.3%    |
| Intel Core 2 Duo        | 1        | 0.3%    |
| AMD Sempron             | 1        | 0.3%    |
| AMD PRO A10             | 1        | 0.3%    |
| AMD Phenom II X6        | 1        | 0.3%    |
| AMD Phenom II X3        | 1        | 0.3%    |
| AMD Athlon              | 1        | 0.3%    |
| AMD A6                  | 1        | 0.3%    |
| AMD A10                 | 1        | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 108      | 32.53%  |
| 6      | 77       | 23.19%  |
| 8      | 55       | 16.57%  |
| 2      | 40       | 12.05%  |
| 12     | 19       | 5.72%   |
| 16     | 15       | 4.52%   |
| 10     | 6        | 1.81%   |
| 3      | 5        | 1.51%   |
| 32     | 2        | 0.6%    |
| 1      | 2        | 0.6%    |
| 24     | 1        | 0.3%    |
| 18     | 1        | 0.3%    |
| 14     | 1        | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 328      | 99.09%  |
| 2      | 3        | 0.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 239      | 72.21%  |
| 1      | 92       | 27.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 331      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 276      | 83.13%  |
| 0x08701021 | 7        | 2.11%   |
| 0x0800820d | 6        | 1.81%   |
| 0x906ec    | 4        | 1.2%    |
| 0x206a7    | 4        | 1.2%    |
| 0x506e3    | 3        | 0.9%    |
| 0x0a201016 | 3        | 0.9%    |
| 0x06003106 | 3        | 0.9%    |
| 0xa0653    | 2        | 0.6%    |
| 0x906ea    | 2        | 0.6%    |
| 0x906e9    | 2        | 0.6%    |
| 0x90672    | 2        | 0.6%    |
| 0x50657    | 2        | 0.6%    |
| 0x306c3    | 2        | 0.6%    |
| 0x08701013 | 2        | 0.6%    |
| 0x08001138 | 2        | 0.6%    |
| 0x08001137 | 2        | 0.6%    |
| 0xa0655    | 1        | 0.3%    |
| 0x0a201006 | 1        | 0.3%    |
| 0x08301039 | 1        | 0.3%    |
| 0x08108109 | 1        | 0.3%    |
| 0x08101016 | 1        | 0.3%    |
| 0x08001129 | 1        | 0.3%    |
| 0x0600611a | 1        | 0.3%    |
| 0x06000852 | 1        | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 51       | 15.36%  |
| Zen 2            | 44       | 13.25%  |
| KabyLake         | 31       | 9.34%   |
| Haswell          | 26       | 7.83%   |
| Skylake          | 23       | 6.93%   |
| Zen+             | 22       | 6.63%   |
| IvyBridge        | 19       | 5.72%   |
| SandyBridge      | 18       | 5.42%   |
| Zen              | 13       | 3.92%   |
| Unknown          | 13       | 3.92%   |
| Piledriver       | 12       | 3.61%   |
| K10              | 10       | 3.01%   |
| CometLake        | 10       | 3.01%   |
| Nehalem          | 9        | 2.71%   |
| Penryn           | 7        | 2.11%   |
| Westmere         | 4        | 1.2%    |
| Steamroller      | 4        | 1.2%    |
| Core             | 4        | 1.2%    |
| NetBurst         | 2        | 0.6%    |
| Excavator        | 2        | 0.6%    |
| Broadwell        | 2        | 0.6%    |
| Alderlake Hybrid | 2        | 0.6%    |
| Silvermont       | 1        | 0.3%    |
| K10 Llano        | 1        | 0.3%    |
| Jaguar           | 1        | 0.3%    |
| Goldmont         | 1        | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 170      | 47.62%  |
| AMD                        | 135      | 37.82%  |
| Intel                      | 51       | 14.29%  |
| Matrox Electronics Systems | 1        | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 16       | 4.31%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 12       | 3.23%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 11       | 2.96%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 9        | 2.43%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 9        | 2.43%   |
| AMD Cezanne                                                                 | 9        | 2.43%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 2.16%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 8        | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 2.16%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 8        | 2.16%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 6        | 1.62%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 1.62%   |
| Intel AlderLake-S GT1                                                       | 6        | 1.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 1.62%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 5        | 1.35%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 1.35%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 1.35%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 1.35%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 5        | 1.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.35%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.35%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 1.08%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 1.08%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 4        | 1.08%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 4        | 1.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.08%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 3        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.81%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 0.81%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 0.81%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 0.81%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 0.81%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3        | 0.81%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 3        | 0.81%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 0.81%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 3        | 0.81%   |
| Intel HD Graphics 530                                                       | 3        | 0.81%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 3        | 0.81%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                      | 3        | 0.81%   |
| AMD Cypress XT [Radeon HD 5870]                                             | 3        | 0.81%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 0.81%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 0.81%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.54%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 0.54%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 0.54%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.54%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 0.54%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.54%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.54%   |
| Nvidia GK107 [GeForce GT 640]                                               | 2        | 0.54%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 2        | 0.54%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 2        | 0.54%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 2        | 0.54%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 0.54%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 0.54%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 2        | 0.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 0.54%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 158      | 46.88%  |
| 1 x AMD              | 123      | 36.5%   |
| 1 x Intel            | 31       | 9.2%    |
| 2 x AMD              | 6        | 1.78%   |
| 2 x Nvidia           | 5        | 1.48%   |
| Intel + Nvidia       | 5        | 1.48%   |
| Intel + AMD          | 3        | 0.89%   |
| AMD + Nvidia         | 2        | 0.59%   |
| Other                | 1        | 0.3%    |
| 2 x AMD + 1 x Nvidia | 1        | 0.3%    |
| 1 x Matrox           | 1        | 0.3%    |
| AMD + 2 x Nvidia     | 1        | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 176      | 52.38%  |
| Proprietary | 147      | 43.75%  |
| Unknown     | 13       | 3.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 193      | 57.27%  |
| 7.01-8.0   | 37       | 10.98%  |
| 3.01-4.0   | 23       | 6.82%   |
| 1.01-2.0   | 23       | 6.82%   |
| 8.01-16.0  | 23       | 6.82%   |
| 5.01-6.0   | 22       | 6.53%   |
| 2.01-3.0   | 7        | 2.08%   |
| 0.51-1.0   | 4        | 1.19%   |
| 16.01-24.0 | 2        | 0.59%   |
| 0.01-0.5   | 2        | 0.59%   |
| 32.01-64.0 | 1        | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 66       | 17.98%  |
| Dell                 | 49       | 13.35%  |
| Goldstar             | 39       | 10.63%  |
| Hewlett-Packard      | 29       | 7.9%    |
| Ancor Communications | 21       | 5.72%   |
| BenQ                 | 19       | 5.18%   |
| AOC                  | 18       | 4.9%    |
| Acer                 | 18       | 4.9%    |
| ASUSTek Computer     | 17       | 4.63%   |
| MSI                  | 6        | 1.63%   |
| Lenovo               | 6        | 1.63%   |
| Iiyama               | 6        | 1.63%   |
| Sceptre Tech         | 5        | 1.36%   |
| NEC Computers        | 5        | 1.36%   |
| Gigabyte Technology  | 5        | 1.36%   |
| ViewSonic            | 4        | 1.09%   |
| Unknown              | 4        | 1.09%   |
| Philips              | 4        | 1.09%   |
| Vizio                | 2        | 0.54%   |
| Viotek               | 2        | 0.54%   |
| Vestel Elektronik    | 2        | 0.54%   |
| Sharp                | 2        | 0.54%   |
| ITE                  | 2        | 0.54%   |
| ___                  | 1        | 0.27%   |
| VOXICON              | 1        | 0.27%   |
| Valve                | 1        | 0.27%   |
| Unknown (XXX)        | 1        | 0.27%   |
| Toshiba              | 1        | 0.27%   |
| STD                  | 1        | 0.27%   |
| SKY                  | 1        | 0.27%   |
| RTK                  | 1        | 0.27%   |
| Positivo             | 1        | 0.27%   |
| Plain Tree Systems   | 1        | 0.27%   |
| Pixio                | 1        | 0.27%   |
| Pioneer              | 1        | 0.27%   |
| Orion                | 1        | 0.27%   |
| ONN                  | 1        | 0.27%   |
| Onkyo                | 1        | 0.27%   |
| OEM                  | 1        | 0.27%   |
| MiTAC                | 1        | 0.27%   |
| Mi                   | 1        | 0.27%   |
| Medion Akoya         | 1        | 0.27%   |
| LLL                  | 1        | 0.27%   |
| LG Electronics       | 1        | 0.27%   |
| KON                  | 1        | 0.27%   |
| Kogan                | 1        | 0.27%   |
| Impression           | 1        | 0.27%   |
| Huion                | 1        | 0.27%   |
| HUAWEI               | 1        | 0.27%   |
| Hitachi              | 1        | 0.27%   |
| GVE                  | 1        | 0.27%   |
| GDH                  | 1        | 0.27%   |
| G-Story              | 1        | 0.27%   |
| Fujitsu Siemens      | 1        | 0.27%   |
| Eizo                 | 1        | 0.27%   |
| CVT                  | 1        | 0.27%   |
| Compal               | 1        | 0.27%   |
| AU Optronics         | 1        | 0.27%   |
| Arnos Instruments    | 1        | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 4        | 1.04%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 3        | 0.78%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch            | 3        | 0.78%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                        | 3        | 0.78%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 2        | 0.52%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 2        | 0.52%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 520x290mm 23.4-inch       | 2        | 0.52%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2        | 0.52%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 2        | 0.52%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch      | 2        | 0.52%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 2        | 0.52%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch       | 2        | 0.52%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch       | 2        | 0.52%   |
| Hewlett-Packard 2310 HWP288F 1920x1080 510x287mm 23.0-inch              | 2        | 0.52%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 2        | 0.52%   |
| Goldstar 34GL750 GSM773B 2560x1080 798x334mm 34.1-inch                  | 2        | 0.52%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch        | 2        | 0.52%   |
| Dell U2212HM DELD048 1920x1080 475x267mm 21.5-inch                      | 2        | 0.52%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                      | 2        | 0.52%   |
| Dell S2340M DELD05A 1920x1080 509x286mm 23.0-inch                       | 2        | 0.52%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 2        | 0.52%   |
| Dell AW3821DW DELA17F 3840x1600 880x367mm 37.5-inch                     | 2        | 0.52%   |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                      | 2        | 0.52%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                      | 2        | 0.52%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                       | 2        | 0.52%   |
| ASUSTek Computer VG279 AUS2782 1920x1080 598x336mm 27.0-inch            | 2        | 0.52%   |
| AOC LE24H067 AOC2410 1920x1080 521x293mm 23.5-inch                      | 2        | 0.52%   |
| Ancor Communications VG248 ACI24A5 1920x1080 531x299mm 24.0-inch        | 2        | 0.52%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch        | 2        | 0.52%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch        | 2        | 0.52%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 2        | 0.52%   |
| Acer G276HL ACR0300 1920x1080 598x336mm 27.0-inch                       | 2        | 0.52%   |
| ___ LCDTV16 ___9000 1360x768                                            | 1        | 0.26%   |
| VOXICON D27Q0 DUS2700 2560x1440 597x336mm 27.0-inch                     | 1        | 0.26%   |
| Vizio M55Q7-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                    | 1        | 0.26%   |
| Vizio D32hn-E0 VIZ1031 1366x768 698x392mm 31.5-inch                     | 1        | 0.26%   |
| Viotek VIOTEKGN27C2 VTK0027 1920x1080 598x336mm 27.0-inch               | 1        | 0.26%   |
| Viotek SUW49DA VTK0490 2560x1440 1194x336mm 48.8-inch                   | 1        | 0.26%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch           | 1        | 0.26%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch              | 1        | 0.26%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch           | 1        | 0.26%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch           | 1        | 0.26%   |
| Valve Index HMD VLV91A8                                                 | 1        | 0.26%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                    | 1        | 0.26%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 0.26%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.26%   |
| Unknown LCD Monitor MEC MD20491 1920x1080                               | 1        | 0.26%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1        | 0.26%   |
| Toshiba TV TSB0108 1920x1080 708x398mm 32.0-inch                        | 1        | 0.26%   |
| STD LED STD0110 1366x768 410x230mm 18.5-inch                            | 1        | 0.26%   |
| SKY M16U1 SKY0156 3840x2160 345x194mm 15.6-inch                         | 1        | 0.26%   |
| Sharp LL-153A-B SHP2163 1024x768 304x228mm 15.0-inch                    | 1        | 0.26%   |
| Sharp HDMI SHP0FEC 1920x1080 820x460mm 37.0-inch                        | 1        | 0.26%   |
| Sceptre Tech U435CV-UMC SPT1109 3840x2160 575x323mm 26.0-inch           | 1        | 0.26%   |
| Sceptre Tech Sceptre M25 SPT09FB 1920x1080 544x303mm 24.5-inch          | 1        | 0.26%   |
| Sceptre Tech Sceptre J20 SPT080D 1600x900 435x237mm 19.5-inch           | 1        | 0.26%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch          | 1        | 0.26%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1        | 0.26%   |
| Samsung Electronics SyncMaster SAM0613 1920x1080                        | 1        | 0.26%   |
| Samsung Electronics SyncMaster SAM0604 1920x1080                        | 1        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 167      | 47.99%  |
| 3840x2160 (4K)     | 50       | 14.37%  |
| 2560x1440 (QHD)    | 36       | 10.34%  |
| 1680x1050 (WSXGA+) | 15       | 4.31%   |
| 3440x1440          | 14       | 4.02%   |
| 2560x1080          | 11       | 3.16%   |
| 1280x1024 (SXGA)   | 11       | 3.16%   |
| 1366x768 (WXGA)    | 8        | 2.3%    |
| 1920x1200 (WUXGA)  | 6        | 1.72%   |
| 1600x900 (HD+)     | 5        | 1.44%   |
| 3840x1080          | 4        | 1.15%   |
| 1920x540           | 4        | 1.15%   |
| 3840x1600          | 3        | 0.86%   |
| 1440x900 (WXGA+)   | 3        | 0.86%   |
| 1360x768           | 3        | 0.86%   |
| 1024x768 (XGA)     | 3        | 0.86%   |
| Unknown            | 2        | 0.57%   |
| 3040x900           | 1        | 0.29%   |
| 2560x1600          | 1        | 0.29%   |
| 1280x800 (WXGA)    | 1        | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 61       | 16.85%  |
| 24      | 54       | 14.92%  |
| 23      | 48       | 13.26%  |
| 21      | 31       | 8.56%   |
| 31      | 30       | 8.29%   |
| 34      | 23       | 6.35%   |
| Unknown | 15       | 4.14%   |
| 22      | 10       | 2.76%   |
| 19      | 10       | 2.76%   |
| 32      | 9        | 2.49%   |
| 84      | 8        | 2.21%   |
| 18      | 7        | 1.93%   |
| 72      | 6        | 1.66%   |
| 20      | 6        | 1.66%   |
| 25      | 5        | 1.38%   |
| 17      | 5        | 1.38%   |
| 15      | 5        | 1.38%   |
| 48      | 4        | 1.1%    |
| 37      | 4        | 1.1%    |
| 26      | 4        | 1.1%    |
| 54      | 2        | 0.55%   |
| 46      | 2        | 0.55%   |
| 35      | 2        | 0.55%   |
| 69      | 1        | 0.28%   |
| 65      | 1        | 0.28%   |
| 52      | 1        | 0.28%   |
| 49      | 1        | 0.28%   |
| 47      | 1        | 0.28%   |
| 44      | 1        | 0.28%   |
| 42      | 1        | 0.28%   |
| 33      | 1        | 0.28%   |
| 30      | 1        | 0.28%   |
| 29      | 1        | 0.28%   |
| 28      | 1        | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 153      | 43.97%  |
| 401-500     | 56       | 16.09%  |
| 601-700     | 39       | 11.21%  |
| 701-800     | 33       | 9.48%   |
| 1501-2000   | 15       | 4.31%   |
| Unknown     | 15       | 4.31%   |
| 1001-1500   | 12       | 3.45%   |
| 301-350     | 10       | 2.87%   |
| 351-400     | 7        | 2.01%   |
| 801-900     | 6        | 1.72%   |
| 901-1000    | 2        | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 245      | 74.02%  |
| 21/9    | 29       | 8.76%   |
| 16/10   | 28       | 8.46%   |
| 5/4     | 11       | 3.32%   |
| Unknown | 7        | 2.11%   |
| 32/9    | 6        | 1.81%   |
| 4/3     | 5        | 1.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 109      | 31.32%  |
| 351-500        | 65       | 18.68%  |
| 301-350        | 65       | 18.68%  |
| 151-200        | 25       | 7.18%   |
| 251-300        | 21       | 6.03%   |
| More than 1000 | 19       | 5.46%   |
| Unknown        | 15       | 4.31%   |
| 501-1000       | 13       | 3.74%   |
| 141-150        | 11       | 3.16%   |
| 101-110        | 5        | 1.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 199      | 60.86%  |
| 101-120       | 72       | 22.02%  |
| 121-160       | 19       | 5.81%   |
| 1-50          | 15       | 4.59%   |
| Unknown       | 15       | 4.59%   |
| 161-240       | 6        | 1.83%   |
| More than 240 | 1        | 0.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 242      | 72.67%  |
| 2     | 66       | 19.82%  |
| 0     | 14       | 4.2%    |
| 3     | 9        | 2.7%    |
| 6     | 1        | 0.3%    |
| 4     | 1        | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 191      | 38.2%   |
| Intel                           | 180      | 36%     |
| Qualcomm Atheros                | 33       | 6.6%    |
| Broadcom                        | 18       | 3.6%    |
| TP-Link                         | 8        | 1.6%    |
| Ralink Technology               | 8        | 1.6%    |
| Microsoft                       | 5        | 1%      |
| Aquantia                        | 5        | 1%      |
| Xiaomi                          | 4        | 0.8%    |
| Nvidia                          | 4        | 0.8%    |
| NetGear                         | 4        | 0.8%    |
| MediaTek                        | 4        | 0.8%    |
| Qualcomm Atheros Communications | 3        | 0.6%    |
| ASUSTek Computer                | 3        | 0.6%    |
| Samsung Electronics             | 2        | 0.4%    |
| Ralink                          | 2        | 0.4%    |
| Mellanox Technologies           | 2        | 0.4%    |
| InterBiometrics                 | 2        | 0.4%    |
| D-Link                          | 2        | 0.4%    |
| Broadcom Limited                | 2        | 0.4%    |
| STMicroelectronics              | 1        | 0.2%    |
| Sitecom Europe                  | 1        | 0.2%    |
| SIEMENS                         | 1        | 0.2%    |
| Realtek                         | 1        | 0.2%    |
| Qualcomm                        | 1        | 0.2%    |
| OPPO Electronics                | 1        | 0.2%    |
| Micro Star International        | 1        | 0.2%    |
| Marvell Technology Group        | 1        | 0.2%    |
| Manta                           | 1        | 0.2%    |
| IMC Networks                    | 1        | 0.2%    |
| Hyperkin                        | 1        | 0.2%    |
| Huawei Technologies             | 1        | 0.2%    |
| Google                          | 1        | 0.2%    |
| Gemtek                          | 1        | 0.2%    |
| DisplayLink                     | 1        | 0.2%    |
| D-Link System                   | 1        | 0.2%    |
| Belkin Components               | 1        | 0.2%    |
| AVM                             | 1        | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 127      | 21.78%  |
| Intel I211 Gigabit Network Connection                                                         | 48       | 8.23%   |
| Intel Wi-Fi 6 AX200                                                                           | 42       | 7.2%    |
| Realtek RTL8125 2.5GbE Controller                                                             | 37       | 6.35%   |
| Intel Ethernet Controller I225-V                                                              | 22       | 3.77%   |
| Intel Ethernet Connection (2) I219-V                                                          | 16       | 2.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 15       | 2.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 13       | 2.23%   |
| Realtek 802.11ac NIC                                                                          | 10       | 1.72%   |
| Intel Ethernet Connection I217-LM                                                             | 9        | 1.54%   |
| Intel Ethernet Connection (7) I219-V                                                          | 9        | 1.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 8        | 1.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 7        | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 7        | 1.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 6        | 1.03%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 6        | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 6        | 1.03%   |
| Intel Wireless-AC 9260                                                                        | 6        | 1.03%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 6        | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 4        | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 0.69%   |
| TP-Link TL-WN722N v2                                                                          | 3        | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3        | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 3        | 0.51%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 3        | 0.51%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 0.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3        | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 3        | 0.51%   |
| Nvidia MCP61 Ethernet                                                                         | 3        | 0.51%   |
| NetGear A6210                                                                                 | 3        | 0.51%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 3        | 0.51%   |
| Intel Wireless 7265                                                                           | 3        | 0.51%   |
| Intel Ethernet Connection I217-V                                                              | 3        | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                                          | 3        | 0.51%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 3        | 0.51%   |
| Intel 82579V Gigabit Network Connection                                                       | 3        | 0.51%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                              | 3        | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                             | 3        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 2        | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                          | 2        | 0.34%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2        | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2        | 0.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.34%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.34%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 2        | 0.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2        | 0.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 2        | 0.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 0.34%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 2        | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 2        | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                | 2        | 0.34%   |
| Microsoft XBOX ACC                                                                            | 2        | 0.34%   |
| Mellanox MT27500 Family [ConnectX-3]                                                          | 2        | 0.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 2        | 0.34%   |
| InterBiometrics Io                                                                            | 2        | 0.34%   |
| Intel Wireless Gigabit 17265                                                                  | 2        | 0.34%   |
| Intel Wireless 8265 / 8275                                                                    | 2        | 0.34%   |
| Intel Wireless 7260                                                                           | 2        | 0.34%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2        | 0.34%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 2        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 97       | 48.02%  |
| Realtek Semiconductor           | 33       | 16.34%  |
| Qualcomm Atheros                | 15       | 7.43%   |
| Broadcom                        | 11       | 5.45%   |
| Ralink Technology               | 8        | 3.96%   |
| TP-Link                         | 7        | 3.47%   |
| Microsoft                       | 5        | 2.48%   |
| NetGear                         | 4        | 1.98%   |
| MediaTek                        | 4        | 1.98%   |
| Qualcomm Atheros Communications | 3        | 1.49%   |
| ASUSTek Computer                | 3        | 1.49%   |
| Ralink                          | 2        | 0.99%   |
| D-Link                          | 2        | 0.99%   |
| Sitecom Europe                  | 1        | 0.5%    |
| Realtek                         | 1        | 0.5%    |
| Micro Star International        | 1        | 0.5%    |
| IMC Networks                    | 1        | 0.5%    |
| Gemtek                          | 1        | 0.5%    |
| D-Link System                   | 1        | 0.5%    |
| Belkin Components               | 1        | 0.5%    |
| AVM                             | 1        | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 42       | 20.59%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 15       | 7.35%   |
| Realtek 802.11ac NIC                                                                          | 10       | 4.9%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 8        | 3.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 7        | 3.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 7        | 3.43%   |
| Intel Wireless-AC 9260                                                                        | 6        | 2.94%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 6        | 2.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 4        | 1.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 1.96%   |
| TP-Link TL-WN722N v2                                                                          | 3        | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3        | 1.47%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 3        | 1.47%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3        | 1.47%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 3        | 1.47%   |
| NetGear A6210                                                                                 | 3        | 1.47%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 3        | 1.47%   |
| Intel Wireless 7265                                                                           | 3        | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 3        | 1.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2        | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.98%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 2        | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 0.98%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 2        | 0.98%   |
| Microsoft XBOX ACC                                                                            | 2        | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 2        | 0.98%   |
| Intel Wireless Gigabit 17265                                                                  | 2        | 0.98%   |
| Intel Wireless 8265 / 8275                                                                    | 2        | 0.98%   |
| Intel Wireless 7260                                                                           | 2        | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2        | 0.98%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                                                   | 1        | 0.49%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 0.49%   |
| Sitecom Europe WL-344 Wireless Adapter 300N X2 [Ralink RT3071]                                | 1        | 0.49%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 0.49%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 0.49%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 0.49%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.49%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 0.49%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.49%   |
| Ralink RT3572 Wireless Adapter                                                                | 1        | 0.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 0.49%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1        | 0.49%   |
| Ralink RT5592 PCIe Wireless Network Adapter                                                   | 1        | 0.49%   |
| Ralink RT2500 Wireless 802.11bg                                                               | 1        | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 0.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1        | 0.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1        | 0.49%   |
| Qualcomm Atheros AR922x Wireless Network Adapter                                              | 1        | 0.49%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1        | 0.49%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express)         | 1        | 0.49%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                                   | 1        | 0.49%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]                    | 1        | 0.49%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 0.49%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                            | 1        | 0.49%   |
| Intel Wireless 8260                                                                           | 1        | 0.49%   |
| Intel Wireless 3165                                                                           | 1        | 0.49%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                          | 1        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 172      | 46.87%  |
| Intel                    | 142      | 38.69%  |
| Qualcomm Atheros         | 19       | 5.18%   |
| Broadcom                 | 8        | 2.18%   |
| Aquantia                 | 5        | 1.36%   |
| Xiaomi                   | 4        | 1.09%   |
| Nvidia                   | 4        | 1.09%   |
| Samsung Electronics      | 2        | 0.54%   |
| Mellanox Technologies    | 2        | 0.54%   |
| Broadcom Limited         | 2        | 0.54%   |
| TP-Link                  | 1        | 0.27%   |
| Qualcomm                 | 1        | 0.27%   |
| OPPO Electronics         | 1        | 0.27%   |
| Marvell Technology Group | 1        | 0.27%   |
| Huawei Technologies      | 1        | 0.27%   |
| Google                   | 1        | 0.27%   |
| DisplayLink              | 1        | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 127      | 34.05%  |
| Intel I211 Gigabit Network Connection                             | 48       | 12.87%  |
| Realtek RTL8125 2.5GbE Controller                                 | 37       | 9.92%   |
| Intel Ethernet Controller I225-V                                  | 22       | 5.9%    |
| Intel Ethernet Connection (2) I219-V                              | 16       | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13       | 3.49%   |
| Intel Ethernet Connection I217-LM                                 | 9        | 2.41%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 1.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6        | 1.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6        | 1.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.8%    |
| Nvidia MCP61 Ethernet                                             | 3        | 0.8%    |
| Intel Ethernet Connection I217-V                                  | 3        | 0.8%    |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.8%    |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.8%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 3        | 0.8%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.54%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.54%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.54%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.54%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.54%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.54%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.27%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.27%   |
| Qualcomm Nokia X100                                               | 1        | 0.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.27%   |
| OPPO 9R                                                           | 1        | 0.27%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.27%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.27%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.27%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.27%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.27%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.27%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.27%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.27%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.27%   |
| Huawei JNY-LX1                                                    | 1        | 0.27%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1        | 0.27%   |
| DisplayLink USB3.0 Dual Video Dock                                | 1        | 0.27%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.27%   |
| Broadcom NetLink BCM5787 Gigabit Ethernet PCI Express             | 1        | 0.27%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.27%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 0.27%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 0.27%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.27%   |
| Aquantia AQC108 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 328      | 62.48%  |
| WiFi     | 191      | 36.38%  |
| Modem    | 3        | 0.57%   |
| Unknown  | 3        | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 246      | 71.93%  |
| WiFi     | 96       | 28.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 178      | 53.61%  |
| 2     | 123      | 37.05%  |
| 3     | 24       | 7.23%   |
| 0     | 5        | 1.51%   |
| 4     | 2        | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 233      | 69.97%  |
| Yes  | 100      | 30.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 87       | 61.27%  |
| Cambridge Silicon Radio         | 23       | 16.2%   |
| ASUSTek Computer                | 9        | 6.34%   |
| Qualcomm Atheros Communications | 5        | 3.52%   |
| Broadcom                        | 5        | 3.52%   |
| Realtek Semiconductor           | 3        | 2.11%   |
| Foxconn / Hon Hai               | 3        | 2.11%   |
| Apple                           | 2        | 1.41%   |
| TP-Link                         | 1        | 0.7%    |
| Micro Star International        | 1        | 0.7%    |
| MediaTek                        | 1        | 0.7%    |
| IMC Networks                    | 1        | 0.7%    |
| Edimax Technology               | 1        | 0.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 37       | 26.06%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 23       | 16.2%   |
| Intel Wireless-AC 3168 Bluetooth                      | 14       | 9.86%   |
| Intel AX201 Bluetooth                                 | 9        | 6.34%   |
| Intel Bluetooth wireless interface                    | 8        | 5.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 7        | 4.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 5        | 3.52%   |
| Intel AX210 Bluetooth                                 | 5        | 3.52%   |
| ASUS Bluetooth Radio                                  | 4        | 2.82%   |
| Qualcomm Atheros  Bluetooth Device                    | 3        | 2.11%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 2.11%   |
| Realtek Bluetooth Radio                               | 2        | 1.41%   |
| Intel Bluetooth Device                                | 2        | 1.41%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 1.41%   |
| ASUS ASUS USB-BT500                                   | 2        | 1.41%   |
| TP-Link UB500 Adapter                                 | 1        | 0.7%    |
| Realtek RTL8821A Bluetooth                            | 1        | 0.7%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 0.7%    |
| Micro Star International Bluetooth Device             | 1        | 0.7%    |
| MediaTek Wireless_Device                              | 1        | 0.7%    |
| IMC Networks Bluetooth Radio                          | 1        | 0.7%    |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 0.7%    |
| Edimax Bluetooth Adapter                              | 1        | 0.7%    |
| Broadcom BCM43142 Bluetooth 4.0                       | 1        | 0.7%    |
| Broadcom BCM2035 Bluetooth dongle                     | 1        | 0.7%    |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 0.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 0.7%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.7%    |
| Apple Bluetooth USB Host Controller                   | 1        | 0.7%    |
| Apple Bluetooth HCI                                   | 1        | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 193      | 29.42%  |
| Nvidia                               | 168      | 25.61%  |
| Intel                                | 164      | 25%     |
| C-Media Electronics                  | 18       | 2.74%   |
| Logitech                             | 10       | 1.52%   |
| Kingston Technology                  | 10       | 1.52%   |
| Creative Labs                        | 7        | 1.07%   |
| JMTek                                | 6        | 0.91%   |
| Focusrite-Novation                   | 6        | 0.91%   |
| Corsair                              | 5        | 0.76%   |
| SteelSeries ApS                      | 4        | 0.61%   |
| Razer USA                            | 4        | 0.61%   |
| Micro Star International             | 4        | 0.61%   |
| ASUSTek Computer                     | 4        | 0.61%   |
| Texas Instruments                    | 3        | 0.46%   |
| GN Netcom                            | 3        | 0.46%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.3%    |
| Sennheiser Communications            | 2        | 0.3%    |
| Creative Technology                  | 2        | 0.3%    |
| BEHRINGER International              | 2        | 0.3%    |
| Antlion Audio                        | 2        | 0.3%    |
| Yamaha                               | 1        | 0.15%   |
| Valve Software                       | 1        | 0.15%   |
| USB MIDI                             | 1        | 0.15%   |
| Unknown                              | 1        | 0.15%   |
| Turtle Beach                         | 1        | 0.15%   |
| Trust                                | 1        | 0.15%   |
| Tenx Technology                      | 1        | 0.15%   |
| Sony                                 | 1        | 0.15%   |
| Solid State System                   | 1        | 0.15%   |
| Shure                                | 1        | 0.15%   |
| Shenzhen Rapoo Technology            | 1        | 0.15%   |
| SAVITECH                             | 1        | 0.15%   |
| Samson Technologies                  | 1        | 0.15%   |
| Realtek Semiconductor                | 1        | 0.15%   |
| Plantronics                          | 1        | 0.15%   |
| Native Instruments                   | 1        | 0.15%   |
| Microsoft                            | 1        | 0.15%   |
| Micronas                             | 1        | 0.15%   |
| Medeli Electronics                   | 1        | 0.15%   |
| Mackie Designs                       | 1        | 0.15%   |
| JOUNIVO JV601                        | 1        | 0.15%   |
| GYROCOM C&C                          | 1        | 0.15%   |
| Google                               | 1        | 0.15%   |
| Giga-Byte Technology                 | 1        | 0.15%   |
| Generalplus Technology               | 1        | 0.15%   |
| GEMBIRD                              | 1        | 0.15%   |
| FiiO Electronics Technology          | 1        | 0.15%   |
| fifinemicrophone.com                 | 1        | 0.15%   |
| FIFINE Microphones                   | 1        | 0.15%   |
| DEXP BK-20                           | 1        | 0.15%   |
| DCMT Technology                      | 1        | 0.15%   |
| CMX Systems                          | 1        | 0.15%   |
| Blue Microphones                     | 1        | 0.15%   |
| Barco Display Systems                | 1        | 0.15%   |
| AudioQuest                           | 1        | 0.15%   |
| Audient                              | 1        | 0.15%   |
| Ableton                              | 1        | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 77       | 9.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 33       | 4.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 27       | 3.49%   |
| AMD Family 17h/19h HD Audio Controller                                     | 22       | 2.85%   |
| Intel 200 Series PCH HD Audio                                              | 20       | 2.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 18       | 2.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17       | 2.2%    |
| Nvidia GP106 High Definition Audio Controller                              | 17       | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17       | 2.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17       | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16       | 2.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16       | 2.07%   |
| Nvidia TU116 High Definition Audio Controller                              | 15       | 1.94%   |
| Nvidia GP104 High Definition Audio Controller                              | 14       | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 14       | 1.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14       | 1.81%   |
| Nvidia TU104 HD Audio Controller                                           | 13       | 1.68%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13       | 1.68%   |
| AMD Navi 10 HDMI Audio                                                     | 12       | 1.55%   |
| Nvidia GA104 High Definition Audio Controller                              | 11       | 1.42%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 11       | 1.42%   |
| Nvidia GA106 High Definition Audio Controller                              | 10       | 1.29%   |
| Nvidia GA102 High Definition Audio Controller                              | 10       | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 1.29%   |
| Intel Alder Lake-S HD Audio Controller                                     | 10       | 1.29%   |
| AMD FCH Azalia Controller                                                  | 9        | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 1.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8        | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 0.91%   |
| Kingston Technology HyperX 7.1 Audio                                       | 7        | 0.91%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                              | 6        | 0.78%   |
| Nvidia GK104 HDMI Audio Controller                                         | 6        | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 0.78%   |
| Nvidia TU102 High Definition Audio Controller                              | 5        | 0.65%   |
| Nvidia GP108 High Definition Audio Controller                              | 5        | 0.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 0.65%   |
| Intel Audio device                                                         | 5        | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 0.52%   |
| Micro Star International USB Audio                                         | 4        | 0.52%   |
| JMTek USB PnP Audio Device                                                 | 4        | 0.52%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 0.52%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.52%   |
| Focusrite-Novation Scarlett 2i2 Camera                                     | 4        | 0.52%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 4        | 0.52%   |
| C-Media Electronics Blue Snowball                                          | 4        | 0.52%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 4        | 0.52%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 0.39%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 0.39%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.39%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 0.39%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 0.39%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 0.39%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 0.39%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.39%   |
| C-Media Electronics USB Audio Device                                       | 3        | 0.39%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 0.39%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3        | 0.39%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 3        | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 20       | 31.75%  |
| G.Skill             | 10       | 15.87%  |
| Kingston            | 8        | 12.7%   |
| Unknown             | 4        | 6.35%   |
| Team                | 4        | 6.35%   |
| Samsung Electronics | 4        | 6.35%   |
| Crucial             | 4        | 6.35%   |
| SK hynix            | 2        | 3.17%   |
| Micron Technology   | 2        | 3.17%   |
| Unknown             | 2        | 3.17%   |
| Teikon              | 1        | 1.59%   |
| Patriot Memory      | 1        | 1.59%   |
| Avant               | 1        | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 4        | 6.06%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 4        | 6.06%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s       | 2        | 3.03%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 2        | 3.03%   |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s      | 2        | 3.03%   |
| Unknown                                                   | 2        | 3.03%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                      | 1        | 1.52%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 1.52%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 1.52%   |
| Unknown RAM Module 16GB DIMM DDR4 3600MT/s                | 1        | 1.52%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s        | 1        | 1.52%   |
| Teikon RAM TMT451U6BFR8C-PBHJ 4GB DIMM DDR3 1600MT/s      | 1        | 1.52%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s        | 1        | 1.52%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s        | 1        | 1.52%   |
| SK hynix RAM HMT351U6CFR8C-PBA 2GB DIMM DDR3 1600MT/s     | 1        | 1.52%   |
| SK hynix RAM HMA82GU6DJR8N-WM 16GB DIMM DDR4 2933MT/s     | 1        | 1.52%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s       | 1        | 1.52%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.52%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s       | 1        | 1.52%   |
| Patriot Memory RAM 4400 C19 Series 8GB DIMM DDR4 3000MT/s | 1        | 1.52%   |
| Micron RAM M378A1K43BB2G3A141 8GB DIMM DDR4 2400MT/s      | 1        | 1.52%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s    | 1        | 1.52%   |
| Kingston RAM Module 16GB DIMM DDR4 2666MT/s               | 1        | 1.52%   |
| Kingston RAM KVT8FP-HYC 4GB DIMM DDR3 1600MT/s            | 1        | 1.52%   |
| Kingston RAM KHX3600C18D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 1.52%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s       | 1        | 1.52%   |
| Kingston RAM CL16-18-18 D4-3000 8GB DIMM DDR4 3000MT/s    | 1        | 1.52%   |
| Kingston RAM 99U5471-033.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 1.52%   |
| Kingston RAM 99P5471-033.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 1.52%   |
| Kingston RAM 9905702-136.A00G 8GB DIMM DDR4 2667MT/s      | 1        | 1.52%   |
| G.Skill RAM F4-3600C18-8GVK 8GB DIMM DDR4 3600MT/s        | 1        | 1.52%   |
| G.Skill RAM F4-3600C18-32GTZN 32GB DIMM DDR4 3600MT/s     | 1        | 1.52%   |
| G.Skill RAM F4-3600C16-8GVKC 8GB DIMM DDR4 3600MT/s       | 1        | 1.52%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s       | 1        | 1.52%   |
| G.Skill RAM F4-3200C16-4GVKB 4GB DIMM DDR4 3200MT/s       | 1        | 1.52%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 1        | 1.52%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 1        | 1.52%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s        | 1        | 1.52%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s     | 1        | 1.52%   |
| Crucial RAM CT51264BA1339.M16F 4GB DIMM DDR3 1333MT/s     | 1        | 1.52%   |
| Crucial RAM BLS8G4D30AESEK.M8FE 8GB DIMM DDR4 3600MT/s    | 1        | 1.52%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3200MT/s  | 1        | 1.52%   |
| Corsair RAM Module 16GB SODIMM DDR4 2400MT/s              | 1        | 1.52%   |
| Corsair RAM CMY8GX3M2A2400C11 4GB DIMM DDR3 2133MT/s      | 1        | 1.52%   |
| Corsair RAM CMX16GX3M4A1333C9 4GB DIMM DDR3 1333MT/s      | 1        | 1.52%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s     | 1        | 1.52%   |
| Corsair RAM CMV8GX4M1A2133C15 8192MB DIMM DDR4 2733MT/s   | 1        | 1.52%   |
| Corsair RAM CMT32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s    | 1        | 1.52%   |
| Corsair RAM CMK8GX4M1A2400C14 8192MB DIMM DDR4 2800MT/s   | 1        | 1.52%   |
| Corsair RAM CMK32GX4M4A2400C14 8GB DIMM DDR4 2666MT/s     | 1        | 1.52%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s    | 1        | 1.52%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s    | 1        | 1.52%   |
| Corsair RAM CMK32GX4M2A2666C16 16384MB DIMM DDR4 3100MT/s | 1        | 1.52%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s     | 1        | 1.52%   |
| Corsair RAM CMG32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s    | 1        | 1.52%   |
| Avant RAM W641GU42J5213NB 8GB DIMM DDR4 2133MT/s          | 1        | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 47       | 81.03%  |
| DDR3    | 9        | 15.52%  |
| Unknown | 2        | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 57       | 98.28%  |
| SODIMM | 1        | 1.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 30       | 49.18%  |
| 16384 | 15       | 24.59%  |
| 4096  | 11       | 18.03%  |
| 32768 | 4        | 6.56%   |
| 2048  | 1        | 1.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 17       | 27.42%  |
| 3200  | 10       | 16.13%  |
| 1600  | 8        | 12.9%   |
| 3466  | 5        | 8.06%   |
| 3000  | 3        | 4.84%   |
| 1333  | 3        | 4.84%   |
| 2933  | 2        | 3.23%   |
| 2667  | 2        | 3.23%   |
| 2666  | 2        | 3.23%   |
| 2400  | 2        | 3.23%   |
| 2133  | 2        | 3.23%   |
| 3266  | 1        | 1.61%   |
| 3100  | 1        | 1.61%   |
| 3067  | 1        | 1.61%   |
| 2800  | 1        | 1.61%   |
| 2733  | 1        | 1.61%   |
| 1866  | 1        | 1.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 18.75%  |
| Hewlett-Packard     | 3        | 18.75%  |
| Brother Industries  | 3        | 18.75%  |
| Seiko Epson         | 2        | 12.5%   |
| Canon               | 2        | 12.5%   |
| QinHeng Electronics | 1        | 6.25%   |
| Prolific Technology | 1        | 6.25%   |
| Dymo-CoStar         | 1        | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seiko Epson WF-4830 Series             | 1        | 5.88%   |
| Seiko Epson ET-2800 Series             | 1        | 5.88%   |
| Samsung SCX-3400 Series                | 1        | 5.88%   |
| Samsung ML-191x/ML-252x Laser Printer  | 1        | 5.88%   |
| Samsung M2070 Series                   | 1        | 5.88%   |
| QinHeng CH340S                         | 1        | 5.88%   |
| Prolific PL2305 Parallel Port          | 1        | 5.88%   |
| HP PSC-1315/PSC-1317                   | 1        | 5.88%   |
| HP LaserJet P2035                      | 1        | 5.88%   |
| HP ENVY Pro 6400 series                | 1        | 5.88%   |
| Dymo-CoStar DYMO LabelWriter 4XL       | 1        | 5.88%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 5.88%   |
| Canon TR8500 series                    | 1        | 5.88%   |
| Canon Pro9000II series                 | 1        | 5.88%   |
| Brother MFC-L2700DW                    | 1        | 5.88%   |
| Brother MFC-5440CN                     | 1        | 5.88%   |
| Brother HL-2130 series                 | 1        | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Canon CanoScan N650U/N656U | 1        | 50%     |
| Canon CanoScan LiDE 60     | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 31       | 37.35%  |
| Sunplus Innovation Technology | 6        | 7.23%   |
| Microdia                      | 6        | 7.23%   |
| Samsung Electronics           | 5        | 6.02%   |
| Jieli Technology              | 4        | 4.82%   |
| Microsoft                     | 3        | 3.61%   |
| Apple                         | 3        | 3.61%   |
| Sunplus IT                    | 2        | 2.41%   |
| Realtek Semiconductor         | 2        | 2.41%   |
| Razer USA                     | 2        | 2.41%   |
| MacroSilicon                  | 2        | 2.41%   |
| AVerMedia Technologies        | 2        | 2.41%   |
| ARC International             | 2        | 2.41%   |
| Z-Star Microelectronics       | 1        | 1.2%    |
| YGTek                         | 1        | 1.2%    |
| XHT-210518                    | 1        | 1.2%    |
| WaveRider Communications      | 1        | 1.2%    |
| Valve Software                | 1        | 1.2%    |
| SN0002                        | 1        | 1.2%    |
| KYE Systems (Mouse Systems)   | 1        | 1.2%    |
| icSpring                      | 1        | 1.2%    |
| Hewlett-Packard               | 1        | 1.2%    |
| GenesysLogic Technology       | 1        | 1.2%    |
| Generalplus Technology        | 1        | 1.2%    |
| eMeet                         | 1        | 1.2%    |
| Creative Technology           | 1        | 1.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 8        | 9.64%   |
| Logitech HD Pro Webcam C920                | 7        | 8.43%   |
| Samsung Galaxy series, misc. (MTP mode)    | 5        | 6.02%   |
| Jieli USB PHY 2.0                          | 4        | 4.82%   |
| Logitech C922 Pro Stream Webcam            | 3        | 3.61%   |
| Apple iPhone 5/5C/5S/6/SE                  | 3        | 3.61%   |
| Sunplus IT AUKEY PC-LM1 USB Camera         | 2        | 2.41%   |
| Sunplus SPCA2281 Web Camera                | 2        | 2.41%   |
| Razer USA Gaming Webcam [Kiyo]             | 2        | 2.41%   |
| Microsoft LifeCam Cinema                   | 2        | 2.41%   |
| Microdia USB 2.0 Camera                    | 2        | 2.41%   |
| MacroSilicon USB Video                     | 2        | 2.41%   |
| Logitech Webcam C930e                      | 2        | 2.41%   |
| Logitech Webcam C925e                      | 2        | 2.41%   |
| Logitech HD Webcam C615                    | 2        | 2.41%   |
| AVerMedia Live Streamer CAM 313            | 2        | 2.41%   |
| ARC International Camera                   | 2        | 2.41%   |
| Z-Star A4 TECH USB2.0 PC Camera E          | 1        | 1.2%    |
| YGTek Webcam                               | 1        | 1.2%    |
| XHT-210518 EC500X                          | 1        | 1.2%    |
| WaveRider USB Live camera                  | 1        | 1.2%    |
| Valve Software 3D Camera                   | 1        | 1.2%    |
| Sunplus MiraBox Video Capture              | 1        | 1.2%    |
| Sunplus HD 720P webcam                     | 1        | 1.2%    |
| Sunplus Full HD webcam                     | 1        | 1.2%    |
| Sunplus Canyon CNS-CWC5 Webcam             | 1        | 1.2%    |
| SN0002 1080P Web Camera                    | 1        | 1.2%    |
| Realtek Thronmax StreamGo Webcam           | 1        | 1.2%    |
| Realtek FULL HD 1080P Webcam               | 1        | 1.2%    |
| Microsoft MicrosoftÂ LifeCam Studio       | 1        | 1.2%    |
| Microdia Webcam Vitade AF                  | 1        | 1.2%    |
| Microdia Rapoo camera                      | 1        | 1.2%    |
| Microdia Integrated Camera                 | 1        | 1.2%    |
| Microdia AUKEY PC-W1                       | 1        | 1.2%    |
| Logitech Webcam Pro 9000                   | 1        | 1.2%    |
| Logitech Logitech Webcam C160              | 1        | 1.2%    |
| Logitech HD Webcam C525                    | 1        | 1.2%    |
| Logitech HD Webcam C510                    | 1        | 1.2%    |
| Logitech CrystalCam                        | 1        | 1.2%    |
| Logitech C920 PRO HD Webcam                | 1        | 1.2%    |
| Logitech BRIO Ultra HD Webcam              | 1        | 1.2%    |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 1.2%    |
| icSpring camera                            | 1        | 1.2%    |
| HP USB Webcam                              | 1        | 1.2%    |
| GenesysLogic USB2.0 UVC PC Camera          | 1        | 1.2%    |
| Generalplus GENERAL WEBCAM                 | 1        | 1.2%    |
| eMeet HD Webcam C960                       | 1        | 1.2%    |
| Creative Live! Cam Optia                   | 1        | 1.2%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 279      | 84.04%  |
| 1     | 49       | 14.76%  |
| 2     | 3        | 0.9%    |
| 3     | 1        | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 23       | 39.66%  |
| Graphics card            | 15       | 25.86%  |
| Bluetooth                | 5        | 8.62%   |
| Unassigned class         | 3        | 5.17%   |
| Network                  | 2        | 3.45%   |
| Net/ethernet             | 2        | 3.45%   |
| Multimedia controller    | 2        | 3.45%   |
| Communication controller | 2        | 3.45%   |
| Storage/ide              | 1        | 1.72%   |
| Sound                    | 1        | 1.72%   |
| Fingerprint reader       | 1        | 1.72%   |
| Chipcard                 | 1        | 1.72%   |

