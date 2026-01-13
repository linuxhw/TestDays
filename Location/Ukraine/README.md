Linux in Ukraine - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ukraine.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ukraine/Desktop/README.md) and [notebooks](/Location/Ukraine/Notebook/README.md).

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

Total: 5309

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | J3355M                      | Desktop     | [38e0553402](https://linux-hardware.org/?probe=38e0553402) | Jan 01, 2026 |
| Dell          | Inspiron 5555               | Notebook    | [3c796c719e](https://linux-hardware.org/?probe=3c796c719e) | Dec 28, 2025 |
| MSI           | Cyborg 15 B13WEKG           | Notebook    | [6fc3b6c3ac](https://linux-hardware.org/?probe=6fc3b6c3ac) | Dec 26, 2025 |
| Gigabyte      | G5 MF                       | Notebook    | [ddb898d45b](https://linux-hardware.org/?probe=ddb898d45b) | Dec 25, 2025 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [73dbe60577](https://linux-hardware.org/?probe=73dbe60577) | Dec 24, 2025 |
| ASUSTek       | TUF Gaming B850-E WIFI      | Desktop     | [fdaad6fd21](https://linux-hardware.org/?probe=fdaad6fd21) | Dec 24, 2025 |
| Samsung       | R55S                        | Notebook    | [fc6cd115ef](https://linux-hardware.org/?probe=fc6cd115ef) | Dec 23, 2025 |
| Dell          | Inspiron 3521               | Notebook    | [db687bea2b](https://linux-hardware.org/?probe=db687bea2b) | Dec 20, 2025 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [fd0293430c](https://linux-hardware.org/?probe=fd0293430c) | Dec 20, 2025 |
| Biostar       | G31-M7 TE                   | Desktop     | [f4bfa72320](https://linux-hardware.org/?probe=f4bfa72320) | Dec 20, 2025 |
| Biostar       | G31-M7 TE                   | Desktop     | [760cd7abcb](https://linux-hardware.org/?probe=760cd7abcb) | Dec 20, 2025 |
| Gigabyte      | H410M H V3                  | Desktop     | [f6643ae299](https://linux-hardware.org/?probe=f6643ae299) | Dec 19, 2025 |
| MSI           | Cyborg 15 B13WEKG           | Notebook    | [a1f0013017](https://linux-hardware.org/?probe=a1f0013017) | Dec 17, 2025 |
| Samsung       | R55S                        | Notebook    | [07fe452be0](https://linux-hardware.org/?probe=07fe452be0) | Dec 16, 2025 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [cdbecb3ebe](https://linux-hardware.org/?probe=cdbecb3ebe) | Dec 16, 2025 |
| Acer          | Aspire A515-57G             | Notebook    | [88e6dfc294](https://linux-hardware.org/?probe=88e6dfc294) | Dec 16, 2025 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [d6851aa06f](https://linux-hardware.org/?probe=d6851aa06f) | Dec 12, 2025 |
| ASUSTek       | K52F                        | Notebook    | [92f40ae93e](https://linux-hardware.org/?probe=92f40ae93e) | Dec 07, 2025 |
| MSI           | B550-A PRO                  | Desktop     | [eb384ffc7d](https://linux-hardware.org/?probe=eb384ffc7d) | Dec 06, 2025 |
| Unknown       | Unknown                     | Desktop     | [a74e5fe873](https://linux-hardware.org/?probe=a74e5fe873) | Dec 04, 2025 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [ed70b6349b](https://linux-hardware.org/?probe=ed70b6349b) | Dec 03, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c620992f9b](https://linux-hardware.org/?probe=c620992f9b) | Dec 03, 2025 |
| HP            | 635                         | Notebook    | [ac9c0ef664](https://linux-hardware.org/?probe=ac9c0ef664) | Nov 24, 2025 |
| Lenovo        | IdeaPad S400 Touch 20283    | Notebook    | [d2f868b9f1](https://linux-hardware.org/?probe=d2f868b9f1) | Nov 20, 2025 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [a16470a802](https://linux-hardware.org/?probe=a16470a802) | Nov 19, 2025 |
| Samsung       | R55S                        | Notebook    | [c704feaef1](https://linux-hardware.org/?probe=c704feaef1) | Nov 13, 2025 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8c3cf5f28e](https://linux-hardware.org/?probe=8c3cf5f28e) | Nov 13, 2025 |
| HP            | Pavilion dv6                | Notebook    | [700910c8ae](https://linux-hardware.org/?probe=700910c8ae) | Nov 12, 2025 |
| HP            | Pavilion dv6                | Notebook    | [6f3ede3ea4](https://linux-hardware.org/?probe=6f3ede3ea4) | Nov 12, 2025 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [599373cced](https://linux-hardware.org/?probe=599373cced) | Nov 12, 2025 |
| Samsung       | R55S                        | Notebook    | [053366ef76](https://linux-hardware.org/?probe=053366ef76) | Nov 11, 2025 |
| Gigabyte      | H55M-S2H                    | Desktop     | [c873b6a777](https://linux-hardware.org/?probe=c873b6a777) | Nov 09, 2025 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [c050c80aac](https://linux-hardware.org/?probe=c050c80aac) | Nov 08, 2025 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f49001d46a](https://linux-hardware.org/?probe=f49001d46a) | Nov 02, 2025 |
| Samsung       | R55S                        | Notebook    | [2d46b73b12](https://linux-hardware.org/?probe=2d46b73b12) | Nov 02, 2025 |
| Dell          | Vostro 5402                 | Notebook    | [1b853c807c](https://linux-hardware.org/?probe=1b853c807c) | Oct 26, 2025 |
| ASUSTek       | M4A77TD                     | Desktop     | [a6783c37a0](https://linux-hardware.org/?probe=a6783c37a0) | Oct 26, 2025 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [ef80fc943b](https://linux-hardware.org/?probe=ef80fc943b) | Oct 25, 2025 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [600930fa3c](https://linux-hardware.org/?probe=600930fa3c) | Oct 22, 2025 |
| Acer          | Extensa 215-55              | Notebook    | [c169f1fbda](https://linux-hardware.org/?probe=c169f1fbda) | Oct 20, 2025 |
| Samsung       | R55S                        | Notebook    | [eb294069e5](https://linux-hardware.org/?probe=eb294069e5) | Oct 17, 2025 |
| Unknown       | Unknown                     | Notebook    | [74ba89ad9b](https://linux-hardware.org/?probe=74ba89ad9b) | Oct 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [e37d12c12c](https://linux-hardware.org/?probe=e37d12c12c) | Oct 15, 2025 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [de62bd3b5d](https://linux-hardware.org/?probe=de62bd3b5d) | Oct 14, 2025 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [c1e101f64f](https://linux-hardware.org/?probe=c1e101f64f) | Oct 07, 2025 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [50d401f8bb](https://linux-hardware.org/?probe=50d401f8bb) | Oct 07, 2025 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [8925d431c5](https://linux-hardware.org/?probe=8925d431c5) | Oct 06, 2025 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [a707e3d2fc](https://linux-hardware.org/?probe=a707e3d2fc) | Oct 06, 2025 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [ee7674fc61](https://linux-hardware.org/?probe=ee7674fc61) | Sep 30, 2025 |
| TECNO Mobi... | MEGABOOK K15S AMD           | Notebook    | [94c9143459](https://linux-hardware.org/?probe=94c9143459) | Sep 29, 2025 |
| Acer          | Aspire A315-59              | Notebook    | [2cac4e7f00](https://linux-hardware.org/?probe=2cac4e7f00) | Sep 29, 2025 |
| MACHINIST     | X99-G7 V1.0                 | Desktop     | [fa8f104b28](https://linux-hardware.org/?probe=fa8f104b28) | Sep 27, 2025 |
| Dell          | G3 3779                     | Notebook    | [cdcece12c4](https://linux-hardware.org/?probe=cdcece12c4) | Sep 26, 2025 |
| Gigabyte      | B450M S2H                   | Desktop     | [90c483d81b](https://linux-hardware.org/?probe=90c483d81b) | Sep 20, 2025 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [ad2d064a85](https://linux-hardware.org/?probe=ad2d064a85) | Sep 17, 2025 |
| InnJoo Tec... | Voom Excellence             | Notebook    | [b83a1a506a](https://linux-hardware.org/?probe=b83a1a506a) | Sep 17, 2025 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [a2ba8a7147](https://linux-hardware.org/?probe=a2ba8a7147) | Sep 13, 2025 |
| ASUSTek       | TUF Gaming B850-PLUS WIF... | Desktop     | [d3948c6b39](https://linux-hardware.org/?probe=d3948c6b39) | Sep 13, 2025 |
| ASUSTek       | TUF Gaming B850-PLUS WIF... | Desktop     | [b76e05172a](https://linux-hardware.org/?probe=b76e05172a) | Sep 13, 2025 |
| Biostar       | H510MHP                     | Desktop     | [902223928b](https://linux-hardware.org/?probe=902223928b) | Sep 12, 2025 |
| INTECH PRO    | H6104D4G V2.0               | Desktop     | [cc7600dd9c](https://linux-hardware.org/?probe=cc7600dd9c) | Sep 11, 2025 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [9247cf7fe8](https://linux-hardware.org/?probe=9247cf7fe8) | Sep 10, 2025 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8b62c4333a](https://linux-hardware.org/?probe=8b62c4333a) | Sep 08, 2025 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [4cc2d7e454](https://linux-hardware.org/?probe=4cc2d7e454) | Sep 07, 2025 |
| ASRock        | H470M-HDV/M.2               | Desktop     | [587f34a876](https://linux-hardware.org/?probe=587f34a876) | Sep 05, 2025 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [b87add21ba](https://linux-hardware.org/?probe=b87add21ba) | Sep 05, 2025 |
| Lenovo        | G580 20150                  | Notebook    | [8e2d6381b6](https://linux-hardware.org/?probe=8e2d6381b6) | Sep 05, 2025 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [175c748da2](https://linux-hardware.org/?probe=175c748da2) | Sep 04, 2025 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [4f2789d0dc](https://linux-hardware.org/?probe=4f2789d0dc) | Sep 04, 2025 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [81dc053747](https://linux-hardware.org/?probe=81dc053747) | Sep 03, 2025 |
| Acer          | Aspire A315-21              | Notebook    | [3118b09d3d](https://linux-hardware.org/?probe=3118b09d3d) | Sep 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop S560... | Notebook    | [3ac4d8a8c8](https://linux-hardware.org/?probe=3ac4d8a8c8) | Aug 31, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop S560... | Notebook    | [25c4fbb5cc](https://linux-hardware.org/?probe=25c4fbb5cc) | Aug 31, 2025 |
| Acer          | Aspire 7540                 | Notebook    | [d622492cf3](https://linux-hardware.org/?probe=d622492cf3) | Aug 30, 2025 |
| Gigabyte      | P67A-UD4-B3                 | Desktop     | [9c4c8b8396](https://linux-hardware.org/?probe=9c4c8b8396) | Aug 25, 2025 |
| Getac         | K120                        | Tablet      | [f131a5e037](https://linux-hardware.org/?probe=f131a5e037) | Aug 24, 2025 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [291259ed7d](https://linux-hardware.org/?probe=291259ed7d) | Aug 12, 2025 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [332ad42e97](https://linux-hardware.org/?probe=332ad42e97) | Aug 08, 2025 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [0ceec83ddc](https://linux-hardware.org/?probe=0ceec83ddc) | Jul 31, 2025 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [326d83570e](https://linux-hardware.org/?probe=326d83570e) | Jul 31, 2025 |
| Samsung       | R55S                        | Notebook    | [b830e16ac7](https://linux-hardware.org/?probe=b830e16ac7) | Jul 28, 2025 |
| DEXP          | C15-ICW300                  | Notebook    | [648ed90371](https://linux-hardware.org/?probe=648ed90371) | Jul 28, 2025 |
| Valve         | Galileo                     | Notebook    | [4b596f486f](https://linux-hardware.org/?probe=4b596f486f) | Jul 21, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [d4dde7e0da](https://linux-hardware.org/?probe=d4dde7e0da) | Jul 16, 2025 |
| OE            | B75 Ver:1.51                | Desktop     | [507fb78497](https://linux-hardware.org/?probe=507fb78497) | Jul 15, 2025 |
| ASRock        | B250 Pro4                   | Desktop     | [892c78069a](https://linux-hardware.org/?probe=892c78069a) | Jul 15, 2025 |
| DIGMA Pro     | Fortis M DN15R5-ADXW07      | Notebook    | [bf4579658c](https://linux-hardware.org/?probe=bf4579658c) | Jul 13, 2025 |
| ASUSTek       | AM1M-A                      | Desktop     | [0d3f4000c7](https://linux-hardware.org/?probe=0d3f4000c7) | Jul 11, 2025 |
| Dell          | Latitude 5420 Rugged        | Notebook    | [fdb03d7ae1](https://linux-hardware.org/?probe=fdb03d7ae1) | Jul 08, 2025 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [a208fc1359](https://linux-hardware.org/?probe=a208fc1359) | Jul 02, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [6c89df7bde](https://linux-hardware.org/?probe=6c89df7bde) | Jun 28, 2025 |
| Lenovo        | G550 20023                  | Notebook    | [21532c1b80](https://linux-hardware.org/?probe=21532c1b80) | Jun 26, 2025 |
| ASUSTek       | X542UQ                      | Notebook    | [0a5f515c70](https://linux-hardware.org/?probe=0a5f515c70) | Jun 25, 2025 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [fa4e83caf0](https://linux-hardware.org/?probe=fa4e83caf0) | Jun 18, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [c501e355b8](https://linux-hardware.org/?probe=c501e355b8) | Jun 15, 2025 |
| Lenovo        | ThinkPad T420 4236PGG       | Notebook    | [8d6611f2f1](https://linux-hardware.org/?probe=8d6611f2f1) | Jun 14, 2025 |
| ASUSTek       | U31SD                       | Notebook    | [338c18b05a](https://linux-hardware.org/?probe=338c18b05a) | Jun 14, 2025 |
| Acer          | Aspire A515-54G             | Notebook    | [29b76a5fc1](https://linux-hardware.org/?probe=29b76a5fc1) | Jun 12, 2025 |
| Dell          | Vostro 15 3530              | Notebook    | [2b029a5ebf](https://linux-hardware.org/?probe=2b029a5ebf) | Jun 11, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [24d6e874cf](https://linux-hardware.org/?probe=24d6e874cf) | Jun 11, 2025 |
| HP            | 1905                        | Desktop     | [ad91f250db](https://linux-hardware.org/?probe=ad91f250db) | Jun 11, 2025 |
| HP            | 1905                        | Desktop     | [5a7f62b703](https://linux-hardware.org/?probe=5a7f62b703) | Jun 11, 2025 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [8a3a2e9fb7](https://linux-hardware.org/?probe=8a3a2e9fb7) | Jun 10, 2025 |
| Acer          | Aspire A515-45G             | Notebook    | [92df7af45a](https://linux-hardware.org/?probe=92df7af45a) | Jun 08, 2025 |
| Acer          | Aspire A515-45G             | Notebook    | [428c786207](https://linux-hardware.org/?probe=428c786207) | Jun 08, 2025 |
| Timi          | TM1801                      | Notebook    | [5b03537ba4](https://linux-hardware.org/?probe=5b03537ba4) | Jun 05, 2025 |
| ASUSTek       | GL553VE                     | Notebook    | [ee3bfac389](https://linux-hardware.org/?probe=ee3bfac389) | May 26, 2025 |
| Lenovo        | ThinkPad P52 20M9S1GQ01     | Notebook    | [94ddaca6cb](https://linux-hardware.org/?probe=94ddaca6cb) | May 24, 2025 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [85df4deaac](https://linux-hardware.org/?probe=85df4deaac) | May 18, 2025 |
| Acer          | Aspire A315-44P             | Notebook    | [a8a5f65950](https://linux-hardware.org/?probe=a8a5f65950) | May 16, 2025 |
| MSI           | A320M-A PRO                 | Desktop     | [5a90bb3421](https://linux-hardware.org/?probe=5a90bb3421) | May 14, 2025 |
| Unknown       | Unknown                     | Notebook    | [71d25628cd](https://linux-hardware.org/?probe=71d25628cd) | May 14, 2025 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [8da9f8cd29](https://linux-hardware.org/?probe=8da9f8cd29) | May 11, 2025 |
| Acer          | Aspire A515-56G             | Notebook    | [e6579208d9](https://linux-hardware.org/?probe=e6579208d9) | May 10, 2025 |
| Lenovo        | ThinkPad E14 20RA001LRT     | Notebook    | [64e4e79aa1](https://linux-hardware.org/?probe=64e4e79aa1) | May 09, 2025 |
| Lenovo        | ThinkPad E14 20RA001LRT     | Notebook    | [b6fbc293e2](https://linux-hardware.org/?probe=b6fbc293e2) | May 09, 2025 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [2f716d5eba](https://linux-hardware.org/?probe=2f716d5eba) | May 08, 2025 |
| Acer          | Aspire A315-34              | Notebook    | [4df5e96514](https://linux-hardware.org/?probe=4df5e96514) | May 06, 2025 |
| ASUSTek       | ROG Strix G614JV_G614JV     | Notebook    | [adbed8b743](https://linux-hardware.org/?probe=adbed8b743) | May 05, 2025 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5219e561b2](https://linux-hardware.org/?probe=5219e561b2) | May 03, 2025 |
| HP            | Presario CQ57               | Notebook    | [7222346fd8](https://linux-hardware.org/?probe=7222346fd8) | May 02, 2025 |
| Gigabyte      | M68MT-S2                    | Desktop     | [19ad3136ab](https://linux-hardware.org/?probe=19ad3136ab) | Apr 28, 2025 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | Notebook    | [97bfa3cc68](https://linux-hardware.org/?probe=97bfa3cc68) | Apr 27, 2025 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [b373b215c9](https://linux-hardware.org/?probe=b373b215c9) | Apr 27, 2025 |
| Huanan        | X99-BD4 V1.34               | Desktop     | [4d5ba48c4c](https://linux-hardware.org/?probe=4d5ba48c4c) | Apr 25, 2025 |
| Apple         | MacBookPro3,1               | Notebook    | [1cb904b528](https://linux-hardware.org/?probe=1cb904b528) | Apr 22, 2025 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [bc494458a7](https://linux-hardware.org/?probe=bc494458a7) | Apr 19, 2025 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [4c59cf96cc](https://linux-hardware.org/?probe=4c59cf96cc) | Apr 17, 2025 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [2a8a900faf](https://linux-hardware.org/?probe=2a8a900faf) | Apr 15, 2025 |
| INFERIT       | IFMBH610IP                  | Desktop     | [3db2c86380](https://linux-hardware.org/?probe=3db2c86380) | Apr 15, 2025 |
| Dell          | Inspiron 5720               | Notebook    | [2ff58e327f](https://linux-hardware.org/?probe=2ff58e327f) | Apr 13, 2025 |
| ASUSTek       | 1001PXD                     | Notebook    | [be3b13b24e](https://linux-hardware.org/?probe=be3b13b24e) | Apr 07, 2025 |
| HP            | ProBook 6550b               | Notebook    | [0c08b3c2f7](https://linux-hardware.org/?probe=0c08b3c2f7) | Apr 03, 2025 |
| HP            | ProBook 6550b               | Notebook    | [1cf614e73e](https://linux-hardware.org/?probe=1cf614e73e) | Apr 03, 2025 |
| Gigabyte      | A520M H                     | Desktop     | [4d35d3ef89](https://linux-hardware.org/?probe=4d35d3ef89) | Apr 02, 2025 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [04929921ce](https://linux-hardware.org/?probe=04929921ce) | Apr 02, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3ed8ac80f4](https://linux-hardware.org/?probe=3ed8ac80f4) | Apr 01, 2025 |
| Supermicro    | X8SIE                       | Desktop     | [740b0d6bca](https://linux-hardware.org/?probe=740b0d6bca) | Mar 29, 2025 |
| Aquarius      | NS483                       | Notebook    | [c180a9957f](https://linux-hardware.org/?probe=c180a9957f) | Mar 28, 2025 |
| HP            | EliteBook 820 G3            | Notebook    | [512c002085](https://linux-hardware.org/?probe=512c002085) | Mar 28, 2025 |
| Lenovo        | ThinkPad T490s 20NX003NR... | Notebook    | [ef0b2ee269](https://linux-hardware.org/?probe=ef0b2ee269) | Mar 26, 2025 |
| ASUSTek       | A68HM-K                     | Desktop     | [3bf0f595a3](https://linux-hardware.org/?probe=3bf0f595a3) | Mar 25, 2025 |
| Dell          | 09KPNV A01                  | Desktop     | [b7580e1447](https://linux-hardware.org/?probe=b7580e1447) | Mar 25, 2025 |
| Apple         | MacBookPro3,1               | Notebook    | [8e73f70fea](https://linux-hardware.org/?probe=8e73f70fea) | Mar 24, 2025 |
| Apple         | MacBookPro3,1               | Notebook    | [8ef5e7b92d](https://linux-hardware.org/?probe=8ef5e7b92d) | Mar 24, 2025 |
| MSI           | MPG Z690 EDGE WIFI          | Desktop     | [5a7ac66e7a](https://linux-hardware.org/?probe=5a7ac66e7a) | Mar 24, 2025 |
| Dell          | 09KPNV A01                  | Desktop     | [0743f19a18](https://linux-hardware.org/?probe=0743f19a18) | Mar 22, 2025 |
| Dell          | Inspiron 5520               | Notebook    | [b3196ccf2e](https://linux-hardware.org/?probe=b3196ccf2e) | Mar 17, 2025 |
| Acer          | Nitro AN515-45              | Notebook    | [c7a5c8fc5b](https://linux-hardware.org/?probe=c7a5c8fc5b) | Mar 16, 2025 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [df876435c0](https://linux-hardware.org/?probe=df876435c0) | Mar 16, 2025 |
| MSI           | H81M-P33                    | Desktop     | [7aa38648ee](https://linux-hardware.org/?probe=7aa38648ee) | Mar 14, 2025 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [6ece4b4f19](https://linux-hardware.org/?probe=6ece4b4f19) | Mar 14, 2025 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [124ee5a8bd](https://linux-hardware.org/?probe=124ee5a8bd) | Mar 12, 2025 |
| Star Labs     | StarBook                    | Notebook    | [f0593d8f1b](https://linux-hardware.org/?probe=f0593d8f1b) | Mar 12, 2025 |
| Apple         | MacBookPro3,1               | Notebook    | [0646de1868](https://linux-hardware.org/?probe=0646de1868) | Mar 11, 2025 |
| Apple         | MacBookPro3,1               | Notebook    | [7a97f1d4e8](https://linux-hardware.org/?probe=7a97f1d4e8) | Mar 11, 2025 |
| InnJoo Tec... | Voom Excellence             | Notebook    | [0ce30f78eb](https://linux-hardware.org/?probe=0ce30f78eb) | Mar 11, 2025 |
| ASRock        | B450 Pro4                   | Desktop     | [853589ef70](https://linux-hardware.org/?probe=853589ef70) | Mar 09, 2025 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [fdc099da48](https://linux-hardware.org/?probe=fdc099da48) | Mar 08, 2025 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [4c5dce9271](https://linux-hardware.org/?probe=4c5dce9271) | Mar 07, 2025 |
| Lenovo        | ThinkPad X60 2510AE9        | Notebook    | [56f9e3d5e1](https://linux-hardware.org/?probe=56f9e3d5e1) | Mar 07, 2025 |
| Toshiba       | Satellite C70-B             | Notebook    | [461acbfbb2](https://linux-hardware.org/?probe=461acbfbb2) | Feb 28, 2025 |
| ASUSTek       | H110M-R                     | Desktop     | [160ee899e6](https://linux-hardware.org/?probe=160ee899e6) | Feb 27, 2025 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [ed3ad2a096](https://linux-hardware.org/?probe=ed3ad2a096) | Feb 26, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [00d1da3042](https://linux-hardware.org/?probe=00d1da3042) | Feb 22, 2025 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b4e40279f1](https://linux-hardware.org/?probe=b4e40279f1) | Feb 22, 2025 |
| Orange Pi     | 5 Plus                      | Soc         | [cb8274509c](https://linux-hardware.org/?probe=cb8274509c) | Feb 22, 2025 |
| Orange Pi     | 5 Plus                      | Soc         | [8223d35d11](https://linux-hardware.org/?probe=8223d35d11) | Feb 22, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [890b2ea5cf](https://linux-hardware.org/?probe=890b2ea5cf) | Feb 19, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [8d88edb31b](https://linux-hardware.org/?probe=8d88edb31b) | Feb 14, 2025 |
| Gigabyte      | GA-770T-D3L                 | Desktop     | [74cbffb1a9](https://linux-hardware.org/?probe=74cbffb1a9) | Feb 13, 2025 |
| ASUSTek       | PRIME H510M-R R2.0          | Desktop     | [8c6e89d4ff](https://linux-hardware.org/?probe=8c6e89d4ff) | Feb 13, 2025 |
| ICL           | RAYbook Si1406              | Notebook    | [39a34ddf55](https://linux-hardware.org/?probe=39a34ddf55) | Feb 09, 2025 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [2729224cea](https://linux-hardware.org/?probe=2729224cea) | Feb 09, 2025 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [459a09518a](https://linux-hardware.org/?probe=459a09518a) | Feb 08, 2025 |
| ASUSTek       | B150M-C                     | Desktop     | [8cdad1d6c4](https://linux-hardware.org/?probe=8cdad1d6c4) | Feb 07, 2025 |
| Gigabyte      | H310M S2V                   | Desktop     | [12a89f79b3](https://linux-hardware.org/?probe=12a89f79b3) | Feb 05, 2025 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [a6fce0b2a8](https://linux-hardware.org/?probe=a6fce0b2a8) | Feb 04, 2025 |
| Gigabyte      | P55-UD3L                    | Desktop     | [82ff2350c4](https://linux-hardware.org/?probe=82ff2350c4) | Feb 03, 2025 |
| ASUSTek       | ASUS EXPERTBOOK P5405CSA    | Notebook    | [1caa4bc5cd](https://linux-hardware.org/?probe=1caa4bc5cd) | Feb 03, 2025 |
| Acer          | Aspire 5542                 | Notebook    | [a2eb622091](https://linux-hardware.org/?probe=a2eb622091) | Feb 02, 2025 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [2f10249b36](https://linux-hardware.org/?probe=2f10249b36) | Feb 01, 2025 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [d3f8c8605b](https://linux-hardware.org/?probe=d3f8c8605b) | Jan 25, 2025 |
| Acer          | Aspire A715-72G             | Notebook    | [d2bc3d68cc](https://linux-hardware.org/?probe=d2bc3d68cc) | Jan 22, 2025 |
| ASUSTek       | PRIME H610I-PLUS D4         | Desktop     | [a9f761706d](https://linux-hardware.org/?probe=a9f761706d) | Jan 22, 2025 |
| Adreamer      | PN1308P                     | Notebook    | [9e722ec5b9](https://linux-hardware.org/?probe=9e722ec5b9) | Jan 20, 2025 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [7e2a937cf6](https://linux-hardware.org/?probe=7e2a937cf6) | Jan 20, 2025 |
| Gigabyte      | B560M H                     | Desktop     | [87cedec9b3](https://linux-hardware.org/?probe=87cedec9b3) | Jan 19, 2025 |
| Dell          | Inspiron 5767               | Notebook    | [ba0b75cb1a](https://linux-hardware.org/?probe=ba0b75cb1a) | Jan 18, 2025 |
| Dell          | Inspiron 5767               | Notebook    | [70b0a9aec2](https://linux-hardware.org/?probe=70b0a9aec2) | Jan 18, 2025 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [62c865e215](https://linux-hardware.org/?probe=62c865e215) | Jan 16, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1061d101a9](https://linux-hardware.org/?probe=1061d101a9) | Jan 16, 2025 |
| Koloe         | X58-PRO                     | Desktop     | [c372eb95d2](https://linux-hardware.org/?probe=c372eb95d2) | Jan 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [4ce71c370a](https://linux-hardware.org/?probe=4ce71c370a) | Jan 16, 2025 |
| Huanan        | X99-BD4 V1.34               | Desktop     | [dd1478bee0](https://linux-hardware.org/?probe=dd1478bee0) | Jan 12, 2025 |
| Gigabyte      | GA-MA74GM-S2                | Desktop     | [847cb58de2](https://linux-hardware.org/?probe=847cb58de2) | Jan 09, 2025 |
| Acer          | Predator PHN16-72           | Notebook    | [90c78ec2cc](https://linux-hardware.org/?probe=90c78ec2cc) | Jan 09, 2025 |
| Lenovo        | ThinkPad Edge E440 20C5A... | Notebook    | [bef55a717d](https://linux-hardware.org/?probe=bef55a717d) | Jan 07, 2025 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [053a6288cb](https://linux-hardware.org/?probe=053a6288cb) | Jan 04, 2025 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [5a05ac75d9](https://linux-hardware.org/?probe=5a05ac75d9) | Jan 03, 2025 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [cd9b055146](https://linux-hardware.org/?probe=cd9b055146) | Dec 31, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [8e64cf40ca](https://linux-hardware.org/?probe=8e64cf40ca) | Dec 30, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [dae8bf9671](https://linux-hardware.org/?probe=dae8bf9671) | Dec 29, 2024 |
| ASRock        | G31M-GS                     | Desktop     | [43edae3bca](https://linux-hardware.org/?probe=43edae3bca) | Dec 27, 2024 |
| ASUSTek       | M5A78L LE                   | Desktop     | [0705f8159c](https://linux-hardware.org/?probe=0705f8159c) | Dec 25, 2024 |
| Samsung       | SR58P                       | Notebook    | [70e6a978b7](https://linux-hardware.org/?probe=70e6a978b7) | Dec 23, 2024 |
| ASRock        | X399 Taichi                 | Desktop     | [fb9ee0f91d](https://linux-hardware.org/?probe=fb9ee0f91d) | Dec 22, 2024 |
| TECNO Mobi... | MEGABOOK T15DA              | Notebook    | [eb2b432d23](https://linux-hardware.org/?probe=eb2b432d23) | Dec 22, 2024 |
| ECS           | H61H2-M6                    | Desktop     | [ee83334d6e](https://linux-hardware.org/?probe=ee83334d6e) | Dec 21, 2024 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [6f78f8b204](https://linux-hardware.org/?probe=6f78f8b204) | Dec 20, 2024 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [69b82b01c8](https://linux-hardware.org/?probe=69b82b01c8) | Dec 16, 2024 |
| HP            | 250 G4                      | Notebook    | [0d0786ce85](https://linux-hardware.org/?probe=0d0786ce85) | Dec 13, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [474d59def7](https://linux-hardware.org/?probe=474d59def7) | Dec 12, 2024 |
| ASRock        | G31M-GS                     | Desktop     | [769e2a4b35](https://linux-hardware.org/?probe=769e2a4b35) | Dec 11, 2024 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [53bab82fae](https://linux-hardware.org/?probe=53bab82fae) | Dec 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [f2663b158a](https://linux-hardware.org/?probe=f2663b158a) | Dec 09, 2024 |
| Lenovo        | G570 20079                  | Notebook    | [d7ca5ffb0b](https://linux-hardware.org/?probe=d7ca5ffb0b) | Dec 06, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3ac8b9ac4d](https://linux-hardware.org/?probe=3ac8b9ac4d) | Dec 05, 2024 |
| ASRock        | Z270M Extreme4              | Desktop     | [1759ae4e5c](https://linux-hardware.org/?probe=1759ae4e5c) | Dec 05, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [8517a48127](https://linux-hardware.org/?probe=8517a48127) | Dec 03, 2024 |
| MSI           | A88X-G43                    | Desktop     | [17b626db6d](https://linux-hardware.org/?probe=17b626db6d) | Dec 02, 2024 |
| Intel         | JSL MRD                     | Desktop     | [0f704c481a](https://linux-hardware.org/?probe=0f704c481a) | Nov 30, 2024 |
| Intel         | JSL MRD                     | Desktop     | [b9e83ac911](https://linux-hardware.org/?probe=b9e83ac911) | Nov 30, 2024 |
| ASRock        | G31M-S                      | Desktop     | [eb86f2cd39](https://linux-hardware.org/?probe=eb86f2cd39) | Nov 25, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [9e94883925](https://linux-hardware.org/?probe=9e94883925) | Nov 24, 2024 |
| MSI           | A88X-G43                    | Desktop     | [0a4c2c7e14](https://linux-hardware.org/?probe=0a4c2c7e14) | Nov 23, 2024 |
| MSI           | A88X-G43                    | Desktop     | [144a4d42dc](https://linux-hardware.org/?probe=144a4d42dc) | Nov 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [e2e36578a2](https://linux-hardware.org/?probe=e2e36578a2) | Nov 22, 2024 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [4f46a03b8f](https://linux-hardware.org/?probe=4f46a03b8f) | Nov 18, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [7dcaf25e66](https://linux-hardware.org/?probe=7dcaf25e66) | Nov 17, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [461bc5c613](https://linux-hardware.org/?probe=461bc5c613) | Nov 16, 2024 |
| Timi          | A35S                        | Notebook    | [009b192f2b](https://linux-hardware.org/?probe=009b192f2b) | Nov 16, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [2bf1a8297a](https://linux-hardware.org/?probe=2bf1a8297a) | Nov 14, 2024 |
| Acer          | Aspire xxxx                 | Notebook    | [33a1540b7a](https://linux-hardware.org/?probe=33a1540b7a) | Nov 11, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [022c2f84fc](https://linux-hardware.org/?probe=022c2f84fc) | Nov 10, 2024 |
| Acer          | Swift SF114-34              | Notebook    | [691b0eb5d2](https://linux-hardware.org/?probe=691b0eb5d2) | Nov 07, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [b9654bc74b](https://linux-hardware.org/?probe=b9654bc74b) | Nov 05, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [9eb047fb07](https://linux-hardware.org/?probe=9eb047fb07) | Nov 03, 2024 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [155af677bf](https://linux-hardware.org/?probe=155af677bf) | Nov 03, 2024 |
| Google        | Pantheon                    | Notebook    | [41f0a72dc6](https://linux-hardware.org/?probe=41f0a72dc6) | Nov 02, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cb259b05e2](https://linux-hardware.org/?probe=cb259b05e2) | Nov 02, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5a5d4093a4](https://linux-hardware.org/?probe=5a5d4093a4) | Nov 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | Notebook    | [98eb489724](https://linux-hardware.org/?probe=98eb489724) | Oct 31, 2024 |
| Timi          | TM1707                      | Notebook    | [6f1f7e4e34](https://linux-hardware.org/?probe=6f1f7e4e34) | Oct 30, 2024 |
| ASUSTek       | U31SD                       | Notebook    | [fe2a70f7fa](https://linux-hardware.org/?probe=fe2a70f7fa) | Oct 29, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7a97ff29a8](https://linux-hardware.org/?probe=7a97ff29a8) | Oct 28, 2024 |
| HP            | Pavilion g6                 | Notebook    | [3033d9b319](https://linux-hardware.org/?probe=3033d9b319) | Oct 28, 2024 |
| Samsung       | R40P/R41P                   | Notebook    | [7055d764e4](https://linux-hardware.org/?probe=7055d764e4) | Oct 28, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [a3f29d92d6](https://linux-hardware.org/?probe=a3f29d92d6) | Oct 27, 2024 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [65e4944972](https://linux-hardware.org/?probe=65e4944972) | Oct 25, 2024 |
| ASUSTek       | U31SD                       | Notebook    | [2c5c09f1df](https://linux-hardware.org/?probe=2c5c09f1df) | Oct 25, 2024 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [8cf1a27cdd](https://linux-hardware.org/?probe=8cf1a27cdd) | Oct 24, 2024 |
| Acer          | Aspire V5-551G              | Notebook    | [9193076b94](https://linux-hardware.org/?probe=9193076b94) | Oct 22, 2024 |
| Acer          | Aspire V5-551G              | Notebook    | [6f186ef3f1](https://linux-hardware.org/?probe=6f186ef3f1) | Oct 22, 2024 |
| ASUSTek       | K55VD                       | Notebook    | [55353ea5e1](https://linux-hardware.org/?probe=55353ea5e1) | Oct 21, 2024 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [87977c5666](https://linux-hardware.org/?probe=87977c5666) | Oct 21, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [38f2255ffb](https://linux-hardware.org/?probe=38f2255ffb) | Oct 18, 2024 |
| Gigabyte      | G5 GE                       | Notebook    | [26c1aed963](https://linux-hardware.org/?probe=26c1aed963) | Oct 17, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d0ac53c68a](https://linux-hardware.org/?probe=d0ac53c68a) | Oct 16, 2024 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [754ae30695](https://linux-hardware.org/?probe=754ae30695) | Oct 16, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [05e504a8d0](https://linux-hardware.org/?probe=05e504a8d0) | Oct 12, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [ab67f0f4c4](https://linux-hardware.org/?probe=ab67f0f4c4) | Oct 07, 2024 |
| Biostar       | N68S3                       | Desktop     | [1763cb7b1a](https://linux-hardware.org/?probe=1763cb7b1a) | Oct 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8dfb3bab34](https://linux-hardware.org/?probe=8dfb3bab34) | Oct 07, 2024 |
| ASUSTek       | A55BM-K                     | Desktop     | [a10e7e5307](https://linux-hardware.org/?probe=a10e7e5307) | Oct 06, 2024 |
| MACHINIST     | E5-MR9A PRO V1.2            | Desktop     | [74c4c3fbbd](https://linux-hardware.org/?probe=74c4c3fbbd) | Oct 06, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [21162c92b4](https://linux-hardware.org/?probe=21162c92b4) | Oct 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [23f6034531](https://linux-hardware.org/?probe=23f6034531) | Oct 04, 2024 |
| Valve         | Galileo                     | Notebook    | [a8bc5582e6](https://linux-hardware.org/?probe=a8bc5582e6) | Oct 03, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [3f4da3a3ef](https://linux-hardware.org/?probe=3f4da3a3ef) | Oct 02, 2024 |
| Biostar       | A68MHE                      | Desktop     | [89d56ae37c](https://linux-hardware.org/?probe=89d56ae37c) | Sep 30, 2024 |
| HP            | Pavilion g6                 | Notebook    | [810492a8e1](https://linux-hardware.org/?probe=810492a8e1) | Sep 30, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [82065600d6](https://linux-hardware.org/?probe=82065600d6) | Sep 30, 2024 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [9dccdf1596](https://linux-hardware.org/?probe=9dccdf1596) | Sep 30, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [1d55438162](https://linux-hardware.org/?probe=1d55438162) | Sep 29, 2024 |
| Gigabyte      | B365M D3H-RD-CF             | Desktop     | [6c23dcaf5c](https://linux-hardware.org/?probe=6c23dcaf5c) | Sep 29, 2024 |
| HP            | 655                         | Notebook    | [ce046ad965](https://linux-hardware.org/?probe=ce046ad965) | Sep 26, 2024 |
| Valve         | Galileo                     | Notebook    | [8ab5e110e2](https://linux-hardware.org/?probe=8ab5e110e2) | Sep 24, 2024 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [1966702f2f](https://linux-hardware.org/?probe=1966702f2f) | Sep 22, 2024 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [f2f522b55b](https://linux-hardware.org/?probe=f2f522b55b) | Sep 20, 2024 |
| ASRock        | P4i65G                      | Desktop     | [4b8718c271](https://linux-hardware.org/?probe=4b8718c271) | Sep 20, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [0cbaddaedf](https://linux-hardware.org/?probe=0cbaddaedf) | Sep 17, 2024 |
| Gigabyte      | M68MT-S2                    | Desktop     | [22af2f7840](https://linux-hardware.org/?probe=22af2f7840) | Sep 15, 2024 |
| Dell          | G3 3579                     | Notebook    | [1786c1ecdd](https://linux-hardware.org/?probe=1786c1ecdd) | Sep 15, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [f8dd4f91b9](https://linux-hardware.org/?probe=f8dd4f91b9) | Sep 12, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [414cce51f0](https://linux-hardware.org/?probe=414cce51f0) | Sep 12, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [bc07a3067b](https://linux-hardware.org/?probe=bc07a3067b) | Sep 09, 2024 |
| ASUSTek       | PRIME H610I-PLUS D4         | Desktop     | [27f0d99cec](https://linux-hardware.org/?probe=27f0d99cec) | Sep 09, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [5ac0a5a0cd](https://linux-hardware.org/?probe=5ac0a5a0cd) | Sep 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [96d9e41b2c](https://linux-hardware.org/?probe=96d9e41b2c) | Sep 06, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [3d9822f68f](https://linux-hardware.org/?probe=3d9822f68f) | Sep 06, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [06bcd2a1a6](https://linux-hardware.org/?probe=06bcd2a1a6) | Sep 06, 2024 |
| ASUSTek       | ROG Strix G713PU_G713PU     | Notebook    | [0cf32a7c28](https://linux-hardware.org/?probe=0cf32a7c28) | Sep 03, 2024 |
| HP            | EliteBook 850 G1            | Notebook    | [c5f7728016](https://linux-hardware.org/?probe=c5f7728016) | Sep 01, 2024 |
| HP            | EliteBook 850 G1            | Notebook    | [ee85acc05d](https://linux-hardware.org/?probe=ee85acc05d) | Sep 01, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [19aa76bbf1](https://linux-hardware.org/?probe=19aa76bbf1) | Aug 30, 2024 |
| Gigabyte      | G5 GD                       | Notebook    | [2840fa5a43](https://linux-hardware.org/?probe=2840fa5a43) | Aug 27, 2024 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [0156c25135](https://linux-hardware.org/?probe=0156c25135) | Aug 24, 2024 |
| Dell          | Vostro 5370                 | Notebook    | [ab603bbc81](https://linux-hardware.org/?probe=ab603bbc81) | Aug 24, 2024 |
| Dell          | Vostro 5370                 | Notebook    | [233641b58a](https://linux-hardware.org/?probe=233641b58a) | Aug 24, 2024 |
| Dell          | Precision 7530              | Notebook    | [67e1c5e840](https://linux-hardware.org/?probe=67e1c5e840) | Aug 24, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [3f778f0500](https://linux-hardware.org/?probe=3f778f0500) | Aug 22, 2024 |
| Gigabyte      | AERO 16 XE4                 | Notebook    | [491d0f5415](https://linux-hardware.org/?probe=491d0f5415) | Aug 22, 2024 |
| Dell          | Precision 7530              | Notebook    | [6dbff427a7](https://linux-hardware.org/?probe=6dbff427a7) | Aug 21, 2024 |
| Dell          | Precision 7530              | Notebook    | [f24cdeec73](https://linux-hardware.org/?probe=f24cdeec73) | Aug 18, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ae6954169b](https://linux-hardware.org/?probe=ae6954169b) | Aug 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [252054bbbb](https://linux-hardware.org/?probe=252054bbbb) | Aug 14, 2024 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [eaf1b08e39](https://linux-hardware.org/?probe=eaf1b08e39) | Aug 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [1647e0bf63](https://linux-hardware.org/?probe=1647e0bf63) | Aug 14, 2024 |
| Acer          | Aspire E1-530G              | Notebook    | [30fac12d0e](https://linux-hardware.org/?probe=30fac12d0e) | Aug 13, 2024 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [af25c599ca](https://linux-hardware.org/?probe=af25c599ca) | Aug 12, 2024 |
| Lenovo        | ThinkPad E595 20NF001HRT    | Notebook    | [ed43fa321d](https://linux-hardware.org/?probe=ed43fa321d) | Aug 11, 2024 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [47a5c4679c](https://linux-hardware.org/?probe=47a5c4679c) | Aug 08, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c81b3df757](https://linux-hardware.org/?probe=c81b3df757) | Aug 05, 2024 |
| Lenovo        | S10-3                       | Notebook    | [64d128d74c](https://linux-hardware.org/?probe=64d128d74c) | Aug 04, 2024 |
| HP            | 339A                        | Desktop     | [e55b214c4e](https://linux-hardware.org/?probe=e55b214c4e) | Aug 04, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [e0891897e9](https://linux-hardware.org/?probe=e0891897e9) | Aug 01, 2024 |
| Lenovo        | S10-3                       | Notebook    | [c25cc431f8](https://linux-hardware.org/?probe=c25cc431f8) | Aug 01, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [97eeb04e17](https://linux-hardware.org/?probe=97eeb04e17) | Jul 31, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [34156676c7](https://linux-hardware.org/?probe=34156676c7) | Jul 28, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | Notebook    | [6959309c2f](https://linux-hardware.org/?probe=6959309c2f) | Jul 28, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [c6b8951769](https://linux-hardware.org/?probe=c6b8951769) | Jul 27, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [c972a50979](https://linux-hardware.org/?probe=c972a50979) | Jul 26, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [efd2967461](https://linux-hardware.org/?probe=efd2967461) | Jul 26, 2024 |
| HP            | Laptop 17-by0xxx            | Notebook    | [29acbbfa9a](https://linux-hardware.org/?probe=29acbbfa9a) | Jul 25, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [926de0d0c1](https://linux-hardware.org/?probe=926de0d0c1) | Jul 22, 2024 |
| ASUSTek       | M4A78LT-M-LE                | Desktop     | [f4985cfd49](https://linux-hardware.org/?probe=f4985cfd49) | Jul 21, 2024 |
| Dell          | Latitude E4310              | Notebook    | [134a985afc](https://linux-hardware.org/?probe=134a985afc) | Jul 21, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [2a5f95f23f](https://linux-hardware.org/?probe=2a5f95f23f) | Jul 20, 2024 |
| Apple         | MacBookAir4,2               | Notebook    | [9644df5e86](https://linux-hardware.org/?probe=9644df5e86) | Jul 19, 2024 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [f0cc03e825](https://linux-hardware.org/?probe=f0cc03e825) | Jul 15, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [24d5092933](https://linux-hardware.org/?probe=24d5092933) | Jul 04, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [77fc74f4e0](https://linux-hardware.org/?probe=77fc74f4e0) | Jun 29, 2024 |
| Acer          | Aspire A515-58P             | Notebook    | [40becc9aaa](https://linux-hardware.org/?probe=40becc9aaa) | Jun 29, 2024 |
| Acer          | Nitro AN17-51               | Notebook    | [f208c4063a](https://linux-hardware.org/?probe=f208c4063a) | Jun 26, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c054b11de9](https://linux-hardware.org/?probe=c054b11de9) | Jun 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [e66c347a99](https://linux-hardware.org/?probe=e66c347a99) | Jun 21, 2024 |
| Lenovo        | IdeaPad Z580                | Notebook    | [3c9898faa1](https://linux-hardware.org/?probe=3c9898faa1) | Jun 20, 2024 |
| Lenovo        | IdeaPad Z580                | Notebook    | [50ac519b75](https://linux-hardware.org/?probe=50ac519b75) | Jun 20, 2024 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [3d565cd28e](https://linux-hardware.org/?probe=3d565cd28e) | Jun 18, 2024 |
| HP            | ProBook 450 G7              | Notebook    | [e984cb8d82](https://linux-hardware.org/?probe=e984cb8d82) | Jun 18, 2024 |
| Lenovo        | ThinkPad T490 20N2000LUK    | Notebook    | [d1053bfafb](https://linux-hardware.org/?probe=d1053bfafb) | Jun 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [12ee24bdf8](https://linux-hardware.org/?probe=12ee24bdf8) | Jun 14, 2024 |
| Acer          | Extensa 215-22              | Notebook    | [604d8cb84d](https://linux-hardware.org/?probe=604d8cb84d) | Jun 11, 2024 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [b50b6a8837](https://linux-hardware.org/?probe=b50b6a8837) | Jun 09, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [91bb1074d9](https://linux-hardware.org/?probe=91bb1074d9) | Jun 09, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4892cf872e](https://linux-hardware.org/?probe=4892cf872e) | Jun 09, 2024 |
| Dell          | Studio 1537                 | Notebook    | [9c73780c05](https://linux-hardware.org/?probe=9c73780c05) | Jun 07, 2024 |
| Valve         | Galileo                     | Notebook    | [c1cd10e2c9](https://linux-hardware.org/?probe=c1cd10e2c9) | Jun 05, 2024 |
| ASUSTek       | M2N-E                       | Desktop     | [291f148ef6](https://linux-hardware.org/?probe=291f148ef6) | Jun 01, 2024 |
| HP            | 8062                        | Desktop     | [e3ffb51a35](https://linux-hardware.org/?probe=e3ffb51a35) | May 31, 2024 |
| THUNDEROBO... | 911S                        | Notebook    | [bcc5c0d77c](https://linux-hardware.org/?probe=bcc5c0d77c) | May 29, 2024 |
| ASRock        | A520M Pro4                  | Desktop     | [84ba0c3f89](https://linux-hardware.org/?probe=84ba0c3f89) | May 26, 2024 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [74c8e530ad](https://linux-hardware.org/?probe=74c8e530ad) | May 22, 2024 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [de96d1e8d8](https://linux-hardware.org/?probe=de96d1e8d8) | May 22, 2024 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [bd144bdd4c](https://linux-hardware.org/?probe=bd144bdd4c) | May 22, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [611c9b917e](https://linux-hardware.org/?probe=611c9b917e) | May 16, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20YE0... | Notebook    | [2dbc872484](https://linux-hardware.org/?probe=2dbc872484) | May 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [23799f6a79](https://linux-hardware.org/?probe=23799f6a79) | May 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [29989717a9](https://linux-hardware.org/?probe=29989717a9) | May 09, 2024 |
| Intel         | X99H                        | Desktop     | [cad02cec7d](https://linux-hardware.org/?probe=cad02cec7d) | May 09, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [5d23c7ed6f](https://linux-hardware.org/?probe=5d23c7ed6f) | May 08, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [5aee2550ce](https://linux-hardware.org/?probe=5aee2550ce) | May 08, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [826e5c0fc6](https://linux-hardware.org/?probe=826e5c0fc6) | May 05, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [2cc53cfafd](https://linux-hardware.org/?probe=2cc53cfafd) | May 05, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [a671f5391b](https://linux-hardware.org/?probe=a671f5391b) | Apr 22, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [eb6c0896d5](https://linux-hardware.org/?probe=eb6c0896d5) | Apr 17, 2024 |
| ASRock        | A520M Pro4                  | Desktop     | [9d7e14b058](https://linux-hardware.org/?probe=9d7e14b058) | Apr 14, 2024 |
| ASRock        | A520M Pro4                  | Desktop     | [03f2a575e4](https://linux-hardware.org/?probe=03f2a575e4) | Apr 12, 2024 |
| Packard Be... | EG43M                       | Desktop     | [4fc4ce3736](https://linux-hardware.org/?probe=4fc4ce3736) | Apr 08, 2024 |
| Acer          | Aspire A315-42              | Notebook    | [bff5263ba8](https://linux-hardware.org/?probe=bff5263ba8) | Apr 07, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [d4fbc831bb](https://linux-hardware.org/?probe=d4fbc831bb) | Apr 07, 2024 |
| HP            | Stream 11 Pro G5            | Notebook    | [60dbf47721](https://linux-hardware.org/?probe=60dbf47721) | Apr 06, 2024 |
| ASRock        | A520M Pro4                  | Desktop     | [dd6acd4be2](https://linux-hardware.org/?probe=dd6acd4be2) | Apr 04, 2024 |
| Foxconn       | G31MX Series                | Desktop     | [283c7c622c](https://linux-hardware.org/?probe=283c7c622c) | Apr 03, 2024 |
| ASUSTek       | K54C                        | Notebook    | [d43311570d](https://linux-hardware.org/?probe=d43311570d) | Apr 01, 2024 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [5cefaeeb6a](https://linux-hardware.org/?probe=5cefaeeb6a) | Mar 31, 2024 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [90a8f20c20](https://linux-hardware.org/?probe=90a8f20c20) | Mar 28, 2024 |
| Acer          | Aspire E3-112               | Notebook    | [bba28f3708](https://linux-hardware.org/?probe=bba28f3708) | Mar 27, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [a66fe7ad17](https://linux-hardware.org/?probe=a66fe7ad17) | Mar 22, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [82eace2b3c](https://linux-hardware.org/?probe=82eace2b3c) | Mar 22, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1f7d74bee8](https://linux-hardware.org/?probe=1f7d74bee8) | Mar 20, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [153f16ac8d](https://linux-hardware.org/?probe=153f16ac8d) | Mar 18, 2024 |
| DEXP          | C15-ICW300                  | Notebook    | [9965e88dba](https://linux-hardware.org/?probe=9965e88dba) | Mar 11, 2024 |
| DEXP          | C15-ICW300                  | Notebook    | [8d8494680f](https://linux-hardware.org/?probe=8d8494680f) | Mar 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [15f6244fa0](https://linux-hardware.org/?probe=15f6244fa0) | Mar 11, 2024 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [5dc203d476](https://linux-hardware.org/?probe=5dc203d476) | Mar 10, 2024 |
| HONOR         | BOD-WXX9                    | Notebook    | [a4942d27af](https://linux-hardware.org/?probe=a4942d27af) | Mar 09, 2024 |
| Acer          | Aspire A315-34              | Notebook    | [de7da2949d](https://linux-hardware.org/?probe=de7da2949d) | Mar 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [a3062daa4e](https://linux-hardware.org/?probe=a3062daa4e) | Mar 01, 2024 |
| ASRock        | X470 Taichi                 | Desktop     | [798acc343c](https://linux-hardware.org/?probe=798acc343c) | Feb 29, 2024 |
| MSI           | KA780G                      | Desktop     | [fe87302b59](https://linux-hardware.org/?probe=fe87302b59) | Feb 27, 2024 |
| HP            | Pavilion dv6                | Notebook    | [ccc6fb70da](https://linux-hardware.org/?probe=ccc6fb70da) | Feb 25, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [969b42aca3](https://linux-hardware.org/?probe=969b42aca3) | Feb 24, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [7f6b3c0f92](https://linux-hardware.org/?probe=7f6b3c0f92) | Feb 13, 2024 |
| ASUSTek       | M4A77TD                     | Desktop     | [75afd83494](https://linux-hardware.org/?probe=75afd83494) | Feb 11, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [f4930d0549](https://linux-hardware.org/?probe=f4930d0549) | Feb 09, 2024 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [b00734a23e](https://linux-hardware.org/?probe=b00734a23e) | Feb 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [f3af706ee0](https://linux-hardware.org/?probe=f3af706ee0) | Jan 29, 2024 |
| Acer          | TravelMate P259-MG          | Notebook    | [0192eb7c53](https://linux-hardware.org/?probe=0192eb7c53) | Jan 28, 2024 |
| Acer          | Aspire A717-71G             | Notebook    | [b7fb65f8f0](https://linux-hardware.org/?probe=b7fb65f8f0) | Jan 24, 2024 |
| Biostar       | A770E                       | Desktop     | [a149b3aeb6](https://linux-hardware.org/?probe=a149b3aeb6) | Jan 17, 2024 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [4854968095](https://linux-hardware.org/?probe=4854968095) | Jan 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [07ee2b0014](https://linux-hardware.org/?probe=07ee2b0014) | Jan 12, 2024 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [f13e1664ba](https://linux-hardware.org/?probe=f13e1664ba) | Jan 12, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [889462ebed](https://linux-hardware.org/?probe=889462ebed) | Jan 10, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [0350f7e562](https://linux-hardware.org/?probe=0350f7e562) | Jan 05, 2024 |
| Chuwi         | HeroBook Pro                | Notebook    | [97c2ff9710](https://linux-hardware.org/?probe=97c2ff9710) | Jan 01, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | Desktop     | [843542e7eb](https://linux-hardware.org/?probe=843542e7eb) | Dec 30, 2023 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [d3e1c0dbdc](https://linux-hardware.org/?probe=d3e1c0dbdc) | Dec 25, 2023 |
| MSI           | EX610                       | Notebook    | [95fe9d0294](https://linux-hardware.org/?probe=95fe9d0294) | Dec 25, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [2c88ade0b2](https://linux-hardware.org/?probe=2c88ade0b2) | Dec 23, 2023 |
| Gigabyte      | H57M-USB3                   | Desktop     | [38bb251f37](https://linux-hardware.org/?probe=38bb251f37) | Dec 15, 2023 |
| Teclast       | X6 plus                     | Tablet      | [ea768f654f](https://linux-hardware.org/?probe=ea768f654f) | Dec 15, 2023 |
| ASRock        | H570 Phantom Gaming 4       | Desktop     | [b942870c3a](https://linux-hardware.org/?probe=b942870c3a) | Dec 15, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [c136ca6eff](https://linux-hardware.org/?probe=c136ca6eff) | Dec 11, 2023 |
| TECNO Mobi... | MEGABOOK T15DA              | Notebook    | [afe1407fd9](https://linux-hardware.org/?probe=afe1407fd9) | Dec 08, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [49e317cfc8](https://linux-hardware.org/?probe=49e317cfc8) | Dec 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1ceb5c4792](https://linux-hardware.org/?probe=1ceb5c4792) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ac0fd4af39](https://linux-hardware.org/?probe=ac0fd4af39) | Dec 05, 2023 |
| Gigabyte      | Z68XP-UD4                   | Desktop     | [3cdd72e242](https://linux-hardware.org/?probe=3cdd72e242) | Dec 05, 2023 |
| Intel         | DP965LT AAD41694-207        | Desktop     | [fe8b5b0a62](https://linux-hardware.org/?probe=fe8b5b0a62) | Dec 04, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [e2c26c5e1f](https://linux-hardware.org/?probe=e2c26c5e1f) | Dec 03, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [a8192548ea](https://linux-hardware.org/?probe=a8192548ea) | Dec 03, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [9598e79260](https://linux-hardware.org/?probe=9598e79260) | Dec 01, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [7d194a5396](https://linux-hardware.org/?probe=7d194a5396) | Dec 01, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [9b8fabda07](https://linux-hardware.org/?probe=9b8fabda07) | Nov 29, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [f5949df300](https://linux-hardware.org/?probe=f5949df300) | Nov 28, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [c179f18d96](https://linux-hardware.org/?probe=c179f18d96) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [ee929504ae](https://linux-hardware.org/?probe=ee929504ae) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [83d5ded7d9](https://linux-hardware.org/?probe=83d5ded7d9) | Nov 27, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [aa7fb6a279](https://linux-hardware.org/?probe=aa7fb6a279) | Nov 26, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [d9f708d5f2](https://linux-hardware.org/?probe=d9f708d5f2) | Nov 26, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [0fd3c87878](https://linux-hardware.org/?probe=0fd3c87878) | Nov 24, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [27e9669d13](https://linux-hardware.org/?probe=27e9669d13) | Nov 24, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [9ab55a1799](https://linux-hardware.org/?probe=9ab55a1799) | Nov 23, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [aea9b092e1](https://linux-hardware.org/?probe=aea9b092e1) | Nov 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cd2ed07d2e](https://linux-hardware.org/?probe=cd2ed07d2e) | Nov 22, 2023 |
| Acer          | Aspire E1-532G              | Notebook    | [986077984e](https://linux-hardware.org/?probe=986077984e) | Nov 18, 2023 |
| HP            | 845A                        | Desktop     | [ecda0525f3](https://linux-hardware.org/?probe=ecda0525f3) | Nov 17, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [613acc55d8](https://linux-hardware.org/?probe=613acc55d8) | Nov 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [66296a4edd](https://linux-hardware.org/?probe=66296a4edd) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [daab2f9dc6](https://linux-hardware.org/?probe=daab2f9dc6) | Nov 11, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b29f519183](https://linux-hardware.org/?probe=b29f519183) | Nov 10, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [63a4283226](https://linux-hardware.org/?probe=63a4283226) | Nov 10, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [cf5ee36e07](https://linux-hardware.org/?probe=cf5ee36e07) | Nov 10, 2023 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [161674ce4a](https://linux-hardware.org/?probe=161674ce4a) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f1d0c200c0](https://linux-hardware.org/?probe=f1d0c200c0) | Nov 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9d1f66b6c6](https://linux-hardware.org/?probe=9d1f66b6c6) | Nov 09, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [b9429814ad](https://linux-hardware.org/?probe=b9429814ad) | Nov 07, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [a1650d3328](https://linux-hardware.org/?probe=a1650d3328) | Nov 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ac8533d263](https://linux-hardware.org/?probe=ac8533d263) | Nov 06, 2023 |
| Lenovo        | IdeaPad 710S Plus-13ISK ... | Notebook    | [f143d09ba7](https://linux-hardware.org/?probe=f143d09ba7) | Nov 04, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [96bda876c8](https://linux-hardware.org/?probe=96bda876c8) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [0a990e1165](https://linux-hardware.org/?probe=0a990e1165) | Oct 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [908b330ba2](https://linux-hardware.org/?probe=908b330ba2) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [3d7ad8a1d6](https://linux-hardware.org/?probe=3d7ad8a1d6) | Oct 26, 2023 |
| Dell          | Latitude E6220              | Notebook    | [afc941b941](https://linux-hardware.org/?probe=afc941b941) | Oct 25, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [e0a819cb8d](https://linux-hardware.org/?probe=e0a819cb8d) | Oct 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [47186b8e71](https://linux-hardware.org/?probe=47186b8e71) | Oct 24, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [817e0c8438](https://linux-hardware.org/?probe=817e0c8438) | Oct 23, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [5e50c3624b](https://linux-hardware.org/?probe=5e50c3624b) | Oct 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fbf9250075](https://linux-hardware.org/?probe=fbf9250075) | Oct 15, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [ff0a453a0e](https://linux-hardware.org/?probe=ff0a453a0e) | Oct 13, 2023 |
| Acer          | TravelMate 5744Z            | Notebook    | [38f2a731a5](https://linux-hardware.org/?probe=38f2a731a5) | Oct 13, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [2b5409e1b5](https://linux-hardware.org/?probe=2b5409e1b5) | Oct 11, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [66b780f57f](https://linux-hardware.org/?probe=66b780f57f) | Oct 11, 2023 |
| MSI           | MS-7309                     | Desktop     | [4cc166d943](https://linux-hardware.org/?probe=4cc166d943) | Oct 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [814f6c5c52](https://linux-hardware.org/?probe=814f6c5c52) | Oct 09, 2023 |
| ASRock        | P4i65G                      | Desktop     | [251a845634](https://linux-hardware.org/?probe=251a845634) | Oct 08, 2023 |
| MSI           | X299 RAIDER                 | Desktop     | [ec7eb75235](https://linux-hardware.org/?probe=ec7eb75235) | Oct 08, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [93e4a63cfa](https://linux-hardware.org/?probe=93e4a63cfa) | Oct 08, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4ab4a75cc2](https://linux-hardware.org/?probe=4ab4a75cc2) | Oct 08, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [a9fb0ad7d5](https://linux-hardware.org/?probe=a9fb0ad7d5) | Oct 06, 2023 |
| Dell          | 0YXT71 A03                  | Desktop     | [afcc6fb467](https://linux-hardware.org/?probe=afcc6fb467) | Oct 05, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [5ff17db8f9](https://linux-hardware.org/?probe=5ff17db8f9) | Oct 03, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [30bf4415dc](https://linux-hardware.org/?probe=30bf4415dc) | Sep 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [937f10463d](https://linux-hardware.org/?probe=937f10463d) | Sep 29, 2023 |
| ASRock        | A520M Pro4                  | Desktop     | [5a7da2e0de](https://linux-hardware.org/?probe=5a7da2e0de) | Sep 28, 2023 |
| Lenovo        | ThinkPad T490s 20NX003NR... | Notebook    | [0a38f1e9a4](https://linux-hardware.org/?probe=0a38f1e9a4) | Sep 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [549941d843](https://linux-hardware.org/?probe=549941d843) | Sep 25, 2023 |
| ASRock        | P4i65G                      | Desktop     | [9f283a95d6](https://linux-hardware.org/?probe=9f283a95d6) | Sep 24, 2023 |
| Google        | Magpie                      | Notebook    | [3da6f69ed3](https://linux-hardware.org/?probe=3da6f69ed3) | Sep 24, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [a8a67a12c7](https://linux-hardware.org/?probe=a8a67a12c7) | Sep 23, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [a13e4d4b27](https://linux-hardware.org/?probe=a13e4d4b27) | Sep 22, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [1253ebfcfb](https://linux-hardware.org/?probe=1253ebfcfb) | Sep 17, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [3cbd0bc118](https://linux-hardware.org/?probe=3cbd0bc118) | Sep 16, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [7f6effbc07](https://linux-hardware.org/?probe=7f6effbc07) | Sep 16, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [7b4955f7d2](https://linux-hardware.org/?probe=7b4955f7d2) | Sep 16, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [175e57d54f](https://linux-hardware.org/?probe=175e57d54f) | Sep 15, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [c0980eee03](https://linux-hardware.org/?probe=c0980eee03) | Sep 13, 2023 |
| Gateway       | NV55C                       | Notebook    | [1086491e2c](https://linux-hardware.org/?probe=1086491e2c) | Sep 12, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [d5d9b73baa](https://linux-hardware.org/?probe=d5d9b73baa) | Sep 11, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [3aef7779ec](https://linux-hardware.org/?probe=3aef7779ec) | Sep 11, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [bb0607322d](https://linux-hardware.org/?probe=bb0607322d) | Sep 09, 2023 |
| Lenovo        | V580c 20160                 | Notebook    | [87f8bad27d](https://linux-hardware.org/?probe=87f8bad27d) | Sep 07, 2023 |
| ASUSTek       | M3N78-VM                    | Desktop     | [0e8a4a2220](https://linux-hardware.org/?probe=0e8a4a2220) | Sep 05, 2023 |
| MSI           | H270 GAMING M3              | Desktop     | [1c93682de6](https://linux-hardware.org/?probe=1c93682de6) | Sep 05, 2023 |
| ASUSTek       | X541NC                      | Notebook    | [927ba04557](https://linux-hardware.org/?probe=927ba04557) | Sep 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ceade9f24f](https://linux-hardware.org/?probe=ceade9f24f) | Sep 04, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [dd19cc0d48](https://linux-hardware.org/?probe=dd19cc0d48) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [fc0731667e](https://linux-hardware.org/?probe=fc0731667e) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [5e3f2f01d4](https://linux-hardware.org/?probe=5e3f2f01d4) | Sep 03, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [45e892a632](https://linux-hardware.org/?probe=45e892a632) | Sep 03, 2023 |
| Lenovo        | IdeaPad Slim 5 16IAH8 83... | Notebook    | [2cfbf5b20c](https://linux-hardware.org/?probe=2cfbf5b20c) | Sep 02, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [193a173166](https://linux-hardware.org/?probe=193a173166) | Sep 02, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [0aac344d78](https://linux-hardware.org/?probe=0aac344d78) | Sep 01, 2023 |
| Acer          | TravelMate 5744Z            | Notebook    | [6a875dbee6](https://linux-hardware.org/?probe=6a875dbee6) | Sep 01, 2023 |
| Samsung       | R518                        | Notebook    | [1869c33e8e](https://linux-hardware.org/?probe=1869c33e8e) | Aug 31, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [6d77cf1b8f](https://linux-hardware.org/?probe=6d77cf1b8f) | Aug 31, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [a139f22d59](https://linux-hardware.org/?probe=a139f22d59) | Aug 27, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [096dcfdc21](https://linux-hardware.org/?probe=096dcfdc21) | Aug 27, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [5b99637f66](https://linux-hardware.org/?probe=5b99637f66) | Aug 25, 2023 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [b53212efce](https://linux-hardware.org/?probe=b53212efce) | Aug 24, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [73a003bf4b](https://linux-hardware.org/?probe=73a003bf4b) | Aug 22, 2023 |
| Lenovo        | ThinkPad E490 20N8001BUS    | Notebook    | [85d80ec89f](https://linux-hardware.org/?probe=85d80ec89f) | Aug 22, 2023 |
| Unknown       | Variscite DART-MX8M-MINI... | Soc         | [a185c83285](https://linux-hardware.org/?probe=a185c83285) | Aug 15, 2023 |
| HP            | 0AACh                       | Desktop     | [f65fb50f69](https://linux-hardware.org/?probe=f65fb50f69) | Aug 14, 2023 |
| HP            | 225E                        | Desktop     | [293a079528](https://linux-hardware.org/?probe=293a079528) | Aug 14, 2023 |
| HP            | 225E                        | Desktop     | [0a353f94ec](https://linux-hardware.org/?probe=0a353f94ec) | Aug 14, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [61908d704c](https://linux-hardware.org/?probe=61908d704c) | Aug 13, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [e3cf4cec26](https://linux-hardware.org/?probe=e3cf4cec26) | Aug 09, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b176d8959a](https://linux-hardware.org/?probe=b176d8959a) | Aug 08, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [663f9e62db](https://linux-hardware.org/?probe=663f9e62db) | Aug 08, 2023 |
| Acer          | TravelMate 5744Z            | Notebook    | [19297331fd](https://linux-hardware.org/?probe=19297331fd) | Aug 05, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [eac04b4464](https://linux-hardware.org/?probe=eac04b4464) | Jul 29, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [4800f23655](https://linux-hardware.org/?probe=4800f23655) | Jul 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [7a6a20b8ed](https://linux-hardware.org/?probe=7a6a20b8ed) | Jul 23, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [6f489ed497](https://linux-hardware.org/?probe=6f489ed497) | Jul 20, 2023 |
| Google        | Lillipup                    | Notebook    | [7f7ba76942](https://linux-hardware.org/?probe=7f7ba76942) | Jul 18, 2023 |
| MSI           | MS-7309                     | Desktop     | [16f6545b66](https://linux-hardware.org/?probe=16f6545b66) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [1367b103ae](https://linux-hardware.org/?probe=1367b103ae) | Jul 09, 2023 |
| ASUSTek       | N55SL                       | Notebook    | [1223d8b536](https://linux-hardware.org/?probe=1223d8b536) | Jul 07, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [638a590e01](https://linux-hardware.org/?probe=638a590e01) | Jul 05, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [d1abb5f348](https://linux-hardware.org/?probe=d1abb5f348) | Jul 02, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [c0238ceb53](https://linux-hardware.org/?probe=c0238ceb53) | Jul 02, 2023 |
| Dell          | System XPS L321X            | Notebook    | [abf6b8b341](https://linux-hardware.org/?probe=abf6b8b341) | Jun 29, 2023 |
| MSI           | Z87 MPOWER                  | Desktop     | [e34420b76e](https://linux-hardware.org/?probe=e34420b76e) | Jun 29, 2023 |
| MSI           | GE66 Dragonshield 10SF      | Notebook    | [42f6b46bb1](https://linux-hardware.org/?probe=42f6b46bb1) | Jun 28, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [4b069e524d](https://linux-hardware.org/?probe=4b069e524d) | Jun 26, 2023 |
| MSI           | GE66 Dragonshield 10SF      | Notebook    | [00fd5b9706](https://linux-hardware.org/?probe=00fd5b9706) | Jun 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [0ee45fd3e8](https://linux-hardware.org/?probe=0ee45fd3e8) | Jun 26, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d7ca07df46](https://linux-hardware.org/?probe=d7ca07df46) | Jun 22, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | Desktop     | [52e2d1b77a](https://linux-hardware.org/?probe=52e2d1b77a) | Jun 21, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [eb9aad2d45](https://linux-hardware.org/?probe=eb9aad2d45) | Jun 18, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [6ce49c3f6f](https://linux-hardware.org/?probe=6ce49c3f6f) | Jun 18, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [adc38f998a](https://linux-hardware.org/?probe=adc38f998a) | Jun 17, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [85b5d49142](https://linux-hardware.org/?probe=85b5d49142) | Jun 13, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [4ec36cfa9e](https://linux-hardware.org/?probe=4ec36cfa9e) | Jun 13, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [fba7b6bdc0](https://linux-hardware.org/?probe=fba7b6bdc0) | Jun 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [fab558feb4](https://linux-hardware.org/?probe=fab558feb4) | Jun 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [06f5f2068f](https://linux-hardware.org/?probe=06f5f2068f) | Jun 09, 2023 |
| Acer          | Aspire V5-551G              | Notebook    | [7c55457a7e](https://linux-hardware.org/?probe=7c55457a7e) | Jun 06, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | Notebook    | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [7b5291c6f8](https://linux-hardware.org/?probe=7b5291c6f8) | Jun 02, 2023 |
| Acer          | TravelMate 5744Z            | Notebook    | [bde6d2f364](https://linux-hardware.org/?probe=bde6d2f364) | May 31, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [2881299761](https://linux-hardware.org/?probe=2881299761) | May 30, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [a7e774154c](https://linux-hardware.org/?probe=a7e774154c) | May 29, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [05a6cc11bb](https://linux-hardware.org/?probe=05a6cc11bb) | May 27, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [b0435ce0dc](https://linux-hardware.org/?probe=b0435ce0dc) | May 27, 2023 |
| THUNDEROBO... | IGER F1                     | Notebook    | [d492356b33](https://linux-hardware.org/?probe=d492356b33) | May 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9c184f4251](https://linux-hardware.org/?probe=9c184f4251) | May 22, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [875d854ec4](https://linux-hardware.org/?probe=875d854ec4) | May 18, 2023 |
| Gigabyte      | E2100N                      | Desktop     | [cce0e87f11](https://linux-hardware.org/?probe=cce0e87f11) | May 17, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [d80a3cd0b7](https://linux-hardware.org/?probe=d80a3cd0b7) | May 17, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [b4a9463feb](https://linux-hardware.org/?probe=b4a9463feb) | May 17, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [84ee42ec2e](https://linux-hardware.org/?probe=84ee42ec2e) | May 17, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [e814f06497](https://linux-hardware.org/?probe=e814f06497) | May 17, 2023 |
| ASUSTek       | H110-PLUS                   | Desktop     | [c0db0f99d2](https://linux-hardware.org/?probe=c0db0f99d2) | May 12, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [d30d7d859b](https://linux-hardware.org/?probe=d30d7d859b) | May 11, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [9c9461f26c](https://linux-hardware.org/?probe=9c9461f26c) | May 09, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [8f910a1997](https://linux-hardware.org/?probe=8f910a1997) | May 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [b9d976ae11](https://linux-hardware.org/?probe=b9d976ae11) | May 07, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [0501f3a43b](https://linux-hardware.org/?probe=0501f3a43b) | May 04, 2023 |
| Lenovo        | ThinkPad T470 20HES63400    | Notebook    | [6628ac6681](https://linux-hardware.org/?probe=6628ac6681) | May 03, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [77ef33da62](https://linux-hardware.org/?probe=77ef33da62) | May 02, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [1c158dca0e](https://linux-hardware.org/?probe=1c158dca0e) | May 02, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [e0f325b239](https://linux-hardware.org/?probe=e0f325b239) | May 01, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [68e3e9ca66](https://linux-hardware.org/?probe=68e3e9ca66) | May 01, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [f0b4e5c5fd](https://linux-hardware.org/?probe=f0b4e5c5fd) | Apr 29, 2023 |
| Biostar       | A780L3C                     | Desktop     | [056ea662e6](https://linux-hardware.org/?probe=056ea662e6) | Apr 29, 2023 |
| Samsung       | R528/R728                   | Notebook    | [1e0b02f4c5](https://linux-hardware.org/?probe=1e0b02f4c5) | Apr 28, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [9f88a0a110](https://linux-hardware.org/?probe=9f88a0a110) | Apr 28, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [6eed1fda15](https://linux-hardware.org/?probe=6eed1fda15) | Apr 27, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [e30ee0a621](https://linux-hardware.org/?probe=e30ee0a621) | Apr 27, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [5ce448176d](https://linux-hardware.org/?probe=5ce448176d) | Apr 26, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [079c071335](https://linux-hardware.org/?probe=079c071335) | Apr 22, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [6869e08d2d](https://linux-hardware.org/?probe=6869e08d2d) | Apr 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [945c1a2fe3](https://linux-hardware.org/?probe=945c1a2fe3) | Apr 17, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [a25bcc21e8](https://linux-hardware.org/?probe=a25bcc21e8) | Apr 17, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [cccf1dadac](https://linux-hardware.org/?probe=cccf1dadac) | Apr 12, 2023 |
| HP            | 635                         | Notebook    | [416f1683f6](https://linux-hardware.org/?probe=416f1683f6) | Apr 12, 2023 |
| Timi          | TM1707                      | Notebook    | [0e015e68ec](https://linux-hardware.org/?probe=0e015e68ec) | Apr 12, 2023 |
| Timi          | TM1707                      | Notebook    | [b611ba24ed](https://linux-hardware.org/?probe=b611ba24ed) | Apr 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fa729987de](https://linux-hardware.org/?probe=fa729987de) | Apr 09, 2023 |
| Lenovo        | SKYBAY SDK0J40679 WIN 32... | All in one  | [810692eb45](https://linux-hardware.org/?probe=810692eb45) | Apr 09, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [d4e3e5d85c](https://linux-hardware.org/?probe=d4e3e5d85c) | Apr 07, 2023 |
| MSI           | MS-7253                     | Desktop     | [1b9074e1ac](https://linux-hardware.org/?probe=1b9074e1ac) | Apr 06, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [d9f6e45e3e](https://linux-hardware.org/?probe=d9f6e45e3e) | Apr 05, 2023 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [04694eb1f9](https://linux-hardware.org/?probe=04694eb1f9) | Apr 05, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [5b2c0ea506](https://linux-hardware.org/?probe=5b2c0ea506) | Apr 02, 2023 |
| MSI           | P43T-C51                    | Desktop     | [d16b44b442](https://linux-hardware.org/?probe=d16b44b442) | Apr 01, 2023 |
| ASUSTek       | M4A79 Deluxe                | Desktop     | [59c5a88b80](https://linux-hardware.org/?probe=59c5a88b80) | Mar 29, 2023 |
| Maxtang       | FP30 V1.0                   | Desktop     | [e184bdb89c](https://linux-hardware.org/?probe=e184bdb89c) | Mar 29, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [220c640743](https://linux-hardware.org/?probe=220c640743) | Mar 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [1f2e4d7cd8](https://linux-hardware.org/?probe=1f2e4d7cd8) | Mar 26, 2023 |
| Gigabyte      | Z590 D                      | Desktop     | [095ade7803](https://linux-hardware.org/?probe=095ade7803) | Mar 26, 2023 |
| HP            | ProBook 5330m               | Notebook    | [6844efa448](https://linux-hardware.org/?probe=6844efa448) | Mar 24, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [7c5033ad07](https://linux-hardware.org/?probe=7c5033ad07) | Mar 20, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [0c4119f8b3](https://linux-hardware.org/?probe=0c4119f8b3) | Mar 20, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [8c50fc6c24](https://linux-hardware.org/?probe=8c50fc6c24) | Mar 19, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [2283637069](https://linux-hardware.org/?probe=2283637069) | Mar 18, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [d7d537c353](https://linux-hardware.org/?probe=d7d537c353) | Mar 18, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [213f4f774f](https://linux-hardware.org/?probe=213f4f774f) | Mar 18, 2023 |
| HONOR         | BOD-WXX9                    | Notebook    | [9bca2e7122](https://linux-hardware.org/?probe=9bca2e7122) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [613aec2276](https://linux-hardware.org/?probe=613aec2276) | Mar 17, 2023 |
| Gigabyte      | E350N WIN8                  | Desktop     | [fd71263100](https://linux-hardware.org/?probe=fd71263100) | Mar 14, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [462b15ab1b](https://linux-hardware.org/?probe=462b15ab1b) | Mar 13, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [811704abe4](https://linux-hardware.org/?probe=811704abe4) | Mar 11, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [262750077e](https://linux-hardware.org/?probe=262750077e) | Mar 10, 2023 |
| HP            | 212B                        | Desktop     | [566c269965](https://linux-hardware.org/?probe=566c269965) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| Huanan        | X79-ZD3 INTEL (INTEL Xeo... | Desktop     | [0e00a19a03](https://linux-hardware.org/?probe=0e00a19a03) | Mar 07, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [3ce9d7353f](https://linux-hardware.org/?probe=3ce9d7353f) | Mar 07, 2023 |
| Acer          | Aspire M3-581TG             | Notebook    | [2f8939e9ed](https://linux-hardware.org/?probe=2f8939e9ed) | Mar 06, 2023 |
| Acer          | Swift SFX16-52G             | Notebook    | [fb45390054](https://linux-hardware.org/?probe=fb45390054) | Mar 05, 2023 |
| Acer          | Swift SFX16-52G             | Notebook    | [b86acec192](https://linux-hardware.org/?probe=b86acec192) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [b9677c823b](https://linux-hardware.org/?probe=b9677c823b) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [47f08e4094](https://linux-hardware.org/?probe=47f08e4094) | Mar 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ce8df757cc](https://linux-hardware.org/?probe=ce8df757cc) | Mar 04, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [ea14c47abb](https://linux-hardware.org/?probe=ea14c47abb) | Mar 04, 2023 |
| Intel         | H55                         | Desktop     | [e154e893d2](https://linux-hardware.org/?probe=e154e893d2) | Mar 04, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [eadfad8fc8](https://linux-hardware.org/?probe=eadfad8fc8) | Mar 04, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [29fae9ef99](https://linux-hardware.org/?probe=29fae9ef99) | Mar 03, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [36078cfcb3](https://linux-hardware.org/?probe=36078cfcb3) | Mar 03, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [3603c7c3e9](https://linux-hardware.org/?probe=3603c7c3e9) | Mar 03, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e5b411431c](https://linux-hardware.org/?probe=e5b411431c) | Mar 02, 2023 |
| AMI           | Aptio CRB E220AQ-600        | Mini pc     | [f341b62f96](https://linux-hardware.org/?probe=f341b62f96) | Mar 02, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [1a041d0aad](https://linux-hardware.org/?probe=1a041d0aad) | Mar 01, 2023 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [93ee76f198](https://linux-hardware.org/?probe=93ee76f198) | Feb 28, 2023 |
| HP            | Laptop 15t-dy200            | Notebook    | [3ea4171270](https://linux-hardware.org/?probe=3ea4171270) | Feb 27, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [a9e3b8c2d2](https://linux-hardware.org/?probe=a9e3b8c2d2) | Feb 26, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Sony          | VGN-Z21WRN_B                | Notebook    | [c1b765e164](https://linux-hardware.org/?probe=c1b765e164) | Feb 26, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [67e31f8e42](https://linux-hardware.org/?probe=67e31f8e42) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2bb4e30118](https://linux-hardware.org/?probe=2bb4e30118) | Feb 25, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [29b1432f2c](https://linux-hardware.org/?probe=29b1432f2c) | Feb 25, 2023 |
| Acer          | AO725                       | Notebook    | [9c6719e733](https://linux-hardware.org/?probe=9c6719e733) | Feb 24, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [d39a85e759](https://linux-hardware.org/?probe=d39a85e759) | Feb 24, 2023 |
| Biostar       | N68S3B                      | Desktop     | [4572b3d965](https://linux-hardware.org/?probe=4572b3d965) | Feb 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [49445991dc](https://linux-hardware.org/?probe=49445991dc) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0dba794459](https://linux-hardware.org/?probe=0dba794459) | Feb 22, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [e523c006bf](https://linux-hardware.org/?probe=e523c006bf) | Feb 22, 2023 |
| Timi          | TM1707                      | Notebook    | [9bc429fbd6](https://linux-hardware.org/?probe=9bc429fbd6) | Feb 22, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [9989903f85](https://linux-hardware.org/?probe=9989903f85) | Feb 21, 2023 |
| Acer          | EG43M                       | Desktop     | [080dfdf76f](https://linux-hardware.org/?probe=080dfdf76f) | Feb 19, 2023 |
| AMI           | Aptio CRB E220AQ-600        | Mini pc     | [b93e11cebc](https://linux-hardware.org/?probe=b93e11cebc) | Feb 13, 2023 |
| Lenovo        | ThinkPad T460p 20FWS0A60... | Notebook    | [c059bdf126](https://linux-hardware.org/?probe=c059bdf126) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [120404606a](https://linux-hardware.org/?probe=120404606a) | Feb 11, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [a025641dfc](https://linux-hardware.org/?probe=a025641dfc) | Feb 09, 2023 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [6c056321fa](https://linux-hardware.org/?probe=6c056321fa) | Feb 08, 2023 |
| ASUSTek       | P552SJ                      | Notebook    | [314c83cb10](https://linux-hardware.org/?probe=314c83cb10) | Feb 06, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [d93258a6f8](https://linux-hardware.org/?probe=d93258a6f8) | Feb 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [f0309f442d](https://linux-hardware.org/?probe=f0309f442d) | Feb 03, 2023 |
| ASRock        | Q1900M                      | Desktop     | [872fb866c6](https://linux-hardware.org/?probe=872fb866c6) | Feb 02, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [42f1a36ace](https://linux-hardware.org/?probe=42f1a36ace) | Feb 01, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b83b751380](https://linux-hardware.org/?probe=b83b751380) | Feb 01, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [c790793197](https://linux-hardware.org/?probe=c790793197) | Feb 01, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [75a3416ebc](https://linux-hardware.org/?probe=75a3416ebc) | Jan 31, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [676f900958](https://linux-hardware.org/?probe=676f900958) | Jan 27, 2023 |
| Dell          | Latitude E5410              | Notebook    | [22df8731a9](https://linux-hardware.org/?probe=22df8731a9) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [df1811bf5d](https://linux-hardware.org/?probe=df1811bf5d) | Jan 26, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [a9dace6356](https://linux-hardware.org/?probe=a9dace6356) | Jan 24, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Biostar       | Hi-Fi A85W                  | Desktop     | [4da9f87ebb](https://linux-hardware.org/?probe=4da9f87ebb) | Jan 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [082d1b40bc](https://linux-hardware.org/?probe=082d1b40bc) | Jan 21, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [ca0282295b](https://linux-hardware.org/?probe=ca0282295b) | Jan 20, 2023 |
| Dell          | Venue 11 Pro 7139           | Notebook    | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [b7771b2b5d](https://linux-hardware.org/?probe=b7771b2b5d) | Jan 19, 2023 |
| Intel         | DG41MJ AAE54659-206         | Desktop     | [98a0ca82de](https://linux-hardware.org/?probe=98a0ca82de) | Jan 18, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f51c90cadc](https://linux-hardware.org/?probe=f51c90cadc) | Jan 15, 2023 |
| Irbis         | NB264                       | Notebook    | [ed534a1d30](https://linux-hardware.org/?probe=ed534a1d30) | Jan 15, 2023 |
| Acer          | Swift SFX16-52G             | Notebook    | [c8b31b22f8](https://linux-hardware.org/?probe=c8b31b22f8) | Jan 14, 2023 |
| Dell          | Inspiron 1012               | Notebook    | [ae34ca229c](https://linux-hardware.org/?probe=ae34ca229c) | Jan 13, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [9ebcc90bcf](https://linux-hardware.org/?probe=9ebcc90bcf) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [322e6e6dbe](https://linux-hardware.org/?probe=322e6e6dbe) | Jan 10, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [aabe4a2438](https://linux-hardware.org/?probe=aabe4a2438) | Jan 10, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [f75fea559f](https://linux-hardware.org/?probe=f75fea559f) | Jan 08, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [c721dc5ba1](https://linux-hardware.org/?probe=c721dc5ba1) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | Notebook    | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [aaf276dad9](https://linux-hardware.org/?probe=aaf276dad9) | Jan 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [406b407b64](https://linux-hardware.org/?probe=406b407b64) | Jan 06, 2023 |
| Acer          | Swift SFX16-52G             | Notebook    | [7ff6038cf3](https://linux-hardware.org/?probe=7ff6038cf3) | Jan 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [b7315d38e1](https://linux-hardware.org/?probe=b7315d38e1) | Jan 04, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [f75b0a7e71](https://linux-hardware.org/?probe=f75b0a7e71) | Jan 03, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [32e666defa](https://linux-hardware.org/?probe=32e666defa) | Jan 03, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [ee31a67035](https://linux-hardware.org/?probe=ee31a67035) | Jan 03, 2023 |
| Acer          | Swift SFX16-52G             | Notebook    | [bd8403001c](https://linux-hardware.org/?probe=bd8403001c) | Jan 02, 2023 |
| Dell          | Latitude D620               | Notebook    | [5337d0b0f9](https://linux-hardware.org/?probe=5337d0b0f9) | Dec 31, 2022 |
| Dell          | Latitude D620               | Notebook    | [ea81d9f6a5](https://linux-hardware.org/?probe=ea81d9f6a5) | Dec 31, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [a6c0667059](https://linux-hardware.org/?probe=a6c0667059) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [ad94a727ab](https://linux-hardware.org/?probe=ad94a727ab) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [bc961748be](https://linux-hardware.org/?probe=bc961748be) | Dec 25, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [e012bb5bc1](https://linux-hardware.org/?probe=e012bb5bc1) | Dec 25, 2022 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [70312467b7](https://linux-hardware.org/?probe=70312467b7) | Dec 24, 2022 |
| ASUSTek       | P5K                         | Desktop     | [e88b53b804](https://linux-hardware.org/?probe=e88b53b804) | Dec 20, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [0a7621cb40](https://linux-hardware.org/?probe=0a7621cb40) | Dec 17, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [c888c743e3](https://linux-hardware.org/?probe=c888c743e3) | Dec 15, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [f09e3c0e19](https://linux-hardware.org/?probe=f09e3c0e19) | Dec 12, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [50e8243e50](https://linux-hardware.org/?probe=50e8243e50) | Dec 11, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [0bb6c29bb6](https://linux-hardware.org/?probe=0bb6c29bb6) | Dec 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [7d63af1d84](https://linux-hardware.org/?probe=7d63af1d84) | Dec 07, 2022 |
| HIPER Tech... | HTHLP-04R/i5-8279u          | Notebook    | [1ead815604](https://linux-hardware.org/?probe=1ead815604) | Dec 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [5ea265ad9a](https://linux-hardware.org/?probe=5ea265ad9a) | Dec 05, 2022 |
| Dell          | Latitude E7470              | Notebook    | [457187e169](https://linux-hardware.org/?probe=457187e169) | Dec 01, 2022 |
| HP            | 8184 X4                     | Desktop     | [2b5ea5e34c](https://linux-hardware.org/?probe=2b5ea5e34c) | Dec 01, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b24884fe44](https://linux-hardware.org/?probe=b24884fe44) | Dec 01, 2022 |
| Acer          | Aspire 5741G                | Notebook    | [0a336099ba](https://linux-hardware.org/?probe=0a336099ba) | Dec 01, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [8a99ec717f](https://linux-hardware.org/?probe=8a99ec717f) | Nov 29, 2022 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [b2eb1eccbd](https://linux-hardware.org/?probe=b2eb1eccbd) | Nov 28, 2022 |
| HP            | 82F1                        | Desktop     | [17ed0cee6a](https://linux-hardware.org/?probe=17ed0cee6a) | Nov 28, 2022 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [82b84f846b](https://linux-hardware.org/?probe=82b84f846b) | Nov 27, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [b1551151f5](https://linux-hardware.org/?probe=b1551151f5) | Nov 24, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [374b408342](https://linux-hardware.org/?probe=374b408342) | Nov 22, 2022 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [e4514feafe](https://linux-hardware.org/?probe=e4514feafe) | Nov 20, 2022 |
| Samsung       | R528/R728                   | Notebook    | [ea586efd66](https://linux-hardware.org/?probe=ea586efd66) | Nov 19, 2022 |
| Huanan        | B75                         | Desktop     | [cfc1803ca1](https://linux-hardware.org/?probe=cfc1803ca1) | Nov 19, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [550bd99088](https://linux-hardware.org/?probe=550bd99088) | Nov 17, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [dd28f73303](https://linux-hardware.org/?probe=dd28f73303) | Nov 14, 2022 |
| MSI           | MS-7360                     | Desktop     | [4899c85a97](https://linux-hardware.org/?probe=4899c85a97) | Nov 14, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [9749e5705a](https://linux-hardware.org/?probe=9749e5705a) | Nov 13, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [c3612a66aa](https://linux-hardware.org/?probe=c3612a66aa) | Nov 10, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [40cce7a719](https://linux-hardware.org/?probe=40cce7a719) | Nov 09, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [38d24e4b4a](https://linux-hardware.org/?probe=38d24e4b4a) | Nov 06, 2022 |
| MSI           | MS-1688                     | Notebook    | [21dad91aac](https://linux-hardware.org/?probe=21dad91aac) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [cb2a07da11](https://linux-hardware.org/?probe=cb2a07da11) | Oct 30, 2022 |
| ASUSTek       | X501A1                      | Notebook    | [037e1402b1](https://linux-hardware.org/?probe=037e1402b1) | Oct 30, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [f1478df888](https://linux-hardware.org/?probe=f1478df888) | Oct 30, 2022 |
| Acer          | Enduro EUN314-51W           | Notebook    | [2655b43e2b](https://linux-hardware.org/?probe=2655b43e2b) | Oct 25, 2022 |
| Acer          | Extensa 5630                | Notebook    | [bdc63e9670](https://linux-hardware.org/?probe=bdc63e9670) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| Acer          | Aspire X3990                | Desktop     | [e741844a8f](https://linux-hardware.org/?probe=e741844a8f) | Oct 23, 2022 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [f81e674faf](https://linux-hardware.org/?probe=f81e674faf) | Oct 21, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [03d7b75880](https://linux-hardware.org/?probe=03d7b75880) | Oct 21, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [f094b82a05](https://linux-hardware.org/?probe=f094b82a05) | Oct 17, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [2dd0b46420](https://linux-hardware.org/?probe=2dd0b46420) | Oct 16, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [8759f9f39c](https://linux-hardware.org/?probe=8759f9f39c) | Oct 15, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [dd95142fda](https://linux-hardware.org/?probe=dd95142fda) | Oct 14, 2022 |
| Lenovo        | 32C0 No DPK                 | All in one  | [231f210ff5](https://linux-hardware.org/?probe=231f210ff5) | Oct 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [7af879de72](https://linux-hardware.org/?probe=7af879de72) | Oct 13, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [8d0d1ba821](https://linux-hardware.org/?probe=8d0d1ba821) | Oct 12, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [16bb04d1db](https://linux-hardware.org/?probe=16bb04d1db) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [52c4e232f3](https://linux-hardware.org/?probe=52c4e232f3) | Oct 10, 2022 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [81e6a3e257](https://linux-hardware.org/?probe=81e6a3e257) | Oct 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d80b0be3f0](https://linux-hardware.org/?probe=d80b0be3f0) | Oct 06, 2022 |
| HONOR         | BOD-WXX9                    | Notebook    | [26c4b5f06a](https://linux-hardware.org/?probe=26c4b5f06a) | Oct 06, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [4a6d780641](https://linux-hardware.org/?probe=4a6d780641) | Oct 05, 2022 |
| MSI           | Z87 MPOWER                  | Desktop     | [75177d19fc](https://linux-hardware.org/?probe=75177d19fc) | Oct 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [bdc21c1bad](https://linux-hardware.org/?probe=bdc21c1bad) | Oct 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [50e50f0533](https://linux-hardware.org/?probe=50e50f0533) | Oct 04, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [ad1e756112](https://linux-hardware.org/?probe=ad1e756112) | Oct 03, 2022 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [6e0ea7e989](https://linux-hardware.org/?probe=6e0ea7e989) | Oct 03, 2022 |
| MSI           | Z87 MPOWER                  | Desktop     | [092a0bd2e3](https://linux-hardware.org/?probe=092a0bd2e3) | Oct 02, 2022 |
| Sony          | VPCEB1M1R                   | Notebook    | [343feefe62](https://linux-hardware.org/?probe=343feefe62) | Oct 02, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [bfd8dc3c18](https://linux-hardware.org/?probe=bfd8dc3c18) | Oct 02, 2022 |
| Acer          | Enduro EN314-51W            | Notebook    | [46782cf8f5](https://linux-hardware.org/?probe=46782cf8f5) | Oct 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [75501a47b5](https://linux-hardware.org/?probe=75501a47b5) | Sep 24, 2022 |
| eMachines     | EZ1700                      | All in one  | [211c6e13f3](https://linux-hardware.org/?probe=211c6e13f3) | Sep 22, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [34db101d55](https://linux-hardware.org/?probe=34db101d55) | Sep 22, 2022 |
| HP            | ENVY Notebook               | Notebook    | [1eef25f6d8](https://linux-hardware.org/?probe=1eef25f6d8) | Sep 22, 2022 |
| HP            | ENVY Notebook               | Notebook    | [b95a98e133](https://linux-hardware.org/?probe=b95a98e133) | Sep 22, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [5b22a32f45](https://linux-hardware.org/?probe=5b22a32f45) | Sep 20, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [dd730980b1](https://linux-hardware.org/?probe=dd730980b1) | Sep 20, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dfd4d1f4e2](https://linux-hardware.org/?probe=dfd4d1f4e2) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [d9742b9445](https://linux-hardware.org/?probe=d9742b9445) | Sep 19, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [6c5e991427](https://linux-hardware.org/?probe=6c5e991427) | Sep 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [fe325d1046](https://linux-hardware.org/?probe=fe325d1046) | Sep 18, 2022 |
| HP            | Pavilion dv6                | Notebook    | [9c9c531c6b](https://linux-hardware.org/?probe=9c9c531c6b) | Sep 15, 2022 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [1662163cb8](https://linux-hardware.org/?probe=1662163cb8) | Sep 15, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| Acer          | TravelMate 5744Z            | Notebook    | [f9846e0165](https://linux-hardware.org/?probe=f9846e0165) | Sep 13, 2022 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [a5ce933202](https://linux-hardware.org/?probe=a5ce933202) | Sep 12, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [80a20ec3fe](https://linux-hardware.org/?probe=80a20ec3fe) | Sep 11, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b5842ca017](https://linux-hardware.org/?probe=b5842ca017) | Sep 10, 2022 |
| ECS           | H61H2-M6                    | Desktop     | [99f3146843](https://linux-hardware.org/?probe=99f3146843) | Sep 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [021bcda428](https://linux-hardware.org/?probe=021bcda428) | Sep 10, 2022 |
| Timi          | TM1703                      | Notebook    | [5c30ece6ff](https://linux-hardware.org/?probe=5c30ece6ff) | Sep 08, 2022 |
| Timi          | TM1703                      | Notebook    | [fb7386017f](https://linux-hardware.org/?probe=fb7386017f) | Sep 06, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [8dba025148](https://linux-hardware.org/?probe=8dba025148) | Sep 05, 2022 |
| Gigabyte      | MSQ87TN-00                  | Desktop     | [af31e1b75a](https://linux-hardware.org/?probe=af31e1b75a) | Sep 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5ba20eb04b](https://linux-hardware.org/?probe=5ba20eb04b) | Sep 01, 2022 |
| Dell          | Latitude 5591               | Notebook    | [b860997149](https://linux-hardware.org/?probe=b860997149) | Sep 01, 2022 |
| Timi          | A35                         | Notebook    | [df50ea1876](https://linux-hardware.org/?probe=df50ea1876) | Aug 29, 2022 |
| ASUSTek       | F1A75-M-PRO R2.0            | Desktop     | [e7e057dd6d](https://linux-hardware.org/?probe=e7e057dd6d) | Aug 27, 2022 |
| Acer          | Aspire 5570Z                | Notebook    | [38fe74cbe3](https://linux-hardware.org/?probe=38fe74cbe3) | Aug 26, 2022 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [ba23396754](https://linux-hardware.org/?probe=ba23396754) | Aug 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [b8859a4f21](https://linux-hardware.org/?probe=b8859a4f21) | Aug 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [ce734a061a](https://linux-hardware.org/?probe=ce734a061a) | Aug 23, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [e9e40a7df5](https://linux-hardware.org/?probe=e9e40a7df5) | Aug 20, 2022 |
| Timi          | A35                         | Notebook    | [cf89c68d08](https://linux-hardware.org/?probe=cf89c68d08) | Aug 19, 2022 |
| Acer          | Aspire ES1-532G             | Notebook    | [cf05c858ab](https://linux-hardware.org/?probe=cf05c858ab) | Aug 15, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [55c4e8059c](https://linux-hardware.org/?probe=55c4e8059c) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a533aea5e5](https://linux-hardware.org/?probe=a533aea5e5) | Aug 14, 2022 |
| Timi          | A35                         | Notebook    | [944f3f0942](https://linux-hardware.org/?probe=944f3f0942) | Aug 12, 2022 |
| Samsung       | GTA4XLWIFI EUR OPEN 04A ... | Soc         | [dcdd87e0cd](https://linux-hardware.org/?probe=dcdd87e0cd) | Aug 10, 2022 |
| Unknown       | Unknown                     | Soc         | [89a777ca81](https://linux-hardware.org/?probe=89a777ca81) | Aug 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4b083cc768](https://linux-hardware.org/?probe=4b083cc768) | Aug 10, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [abf6de9a2d](https://linux-hardware.org/?probe=abf6de9a2d) | Aug 09, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [e115d77240](https://linux-hardware.org/?probe=e115d77240) | Aug 07, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [8ed3ede567](https://linux-hardware.org/?probe=8ed3ede567) | Aug 06, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [7594659719](https://linux-hardware.org/?probe=7594659719) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [e963ce265b](https://linux-hardware.org/?probe=e963ce265b) | Aug 04, 2022 |
| ASUSTek       | X301A1                      | Notebook    | [60d9f2bc4d](https://linux-hardware.org/?probe=60d9f2bc4d) | Aug 02, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [7d8e339d92](https://linux-hardware.org/?probe=7d8e339d92) | Aug 02, 2022 |
| ASRock        | A780LM-S                    | Desktop     | [83b44b9bd6](https://linux-hardware.org/?probe=83b44b9bd6) | Jul 31, 2022 |
| ASRock        | A780LM-S                    | Desktop     | [2a1ce55c1b](https://linux-hardware.org/?probe=2a1ce55c1b) | Jul 31, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bc1a82a647](https://linux-hardware.org/?probe=bc1a82a647) | Jul 28, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [46201e4773](https://linux-hardware.org/?probe=46201e4773) | Jul 27, 2022 |
| Acer          | Iconia W700                 | Notebook    | [694887391c](https://linux-hardware.org/?probe=694887391c) | Jul 26, 2022 |
| Acer          | TravelMate 5744Z            | Notebook    | [aa1416d2e3](https://linux-hardware.org/?probe=aa1416d2e3) | Jul 26, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8173942fbb](https://linux-hardware.org/?probe=8173942fbb) | Jul 25, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| HP            | 8715                        | Mini pc     | [75c873bb8e](https://linux-hardware.org/?probe=75c873bb8e) | Jul 23, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [b4691ae23b](https://linux-hardware.org/?probe=b4691ae23b) | Jul 22, 2022 |
| Gigabyte      | P31-DS3L                    | Desktop     | [3b8118fb89](https://linux-hardware.org/?probe=3b8118fb89) | Jul 19, 2022 |
| ASRock        | H61M                        | Desktop     | [6a10cdfa42](https://linux-hardware.org/?probe=6a10cdfa42) | Jul 18, 2022 |
| Fujitsu       | LIFEBOOK AH512              | Notebook    | [de59ca3757](https://linux-hardware.org/?probe=de59ca3757) | Jul 17, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [37e5cc640d](https://linux-hardware.org/?probe=37e5cc640d) | Jul 14, 2022 |
| Acer          | Iconia W700                 | Notebook    | [f290f68268](https://linux-hardware.org/?probe=f290f68268) | Jul 14, 2022 |
| Dell          | Latitude 7280               | Notebook    | [75ce6d31bc](https://linux-hardware.org/?probe=75ce6d31bc) | Jul 14, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [fa23f41617](https://linux-hardware.org/?probe=fa23f41617) | Jul 13, 2022 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [19209d1119](https://linux-hardware.org/?probe=19209d1119) | Jul 12, 2022 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [9f9d1cac61](https://linux-hardware.org/?probe=9f9d1cac61) | Jul 09, 2022 |
| ASUSTek       | F3JR                        | Notebook    | [9a1e994bcb](https://linux-hardware.org/?probe=9a1e994bcb) | Jul 08, 2022 |
| Prestigio     | Multipad Visconte V         | Notebook    | [d582eea1af](https://linux-hardware.org/?probe=d582eea1af) | Jul 08, 2022 |
| MSI           | Prestige 14 A10SC           | Notebook    | [f1632a7901](https://linux-hardware.org/?probe=f1632a7901) | Jul 06, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [6494f9e1ef](https://linux-hardware.org/?probe=6494f9e1ef) | Jul 05, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [41c609be91](https://linux-hardware.org/?probe=41c609be91) | Jul 05, 2022 |
| ASUSTek       | TP501UB                     | Notebook    | [4cebce6bab](https://linux-hardware.org/?probe=4cebce6bab) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | Notebook    | [6ee62813e8](https://linux-hardware.org/?probe=6ee62813e8) | Jul 04, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [df4856796e](https://linux-hardware.org/?probe=df4856796e) | Jul 04, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [f63cb64736](https://linux-hardware.org/?probe=f63cb64736) | Jul 03, 2022 |
| Acer          | Aspire 5741G                | Notebook    | [228eb87fbc](https://linux-hardware.org/?probe=228eb87fbc) | Jul 02, 2022 |
| Acer          | Aspire M3910                | Desktop     | [ad06b5a93e](https://linux-hardware.org/?probe=ad06b5a93e) | Jun 28, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0ea9a6be3a](https://linux-hardware.org/?probe=0ea9a6be3a) | Jun 28, 2022 |
| Lenovo        | G550 20023                  | Notebook    | [0a2aa10fd1](https://linux-hardware.org/?probe=0a2aa10fd1) | Jun 27, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [47cddfb141](https://linux-hardware.org/?probe=47cddfb141) | Jun 25, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [ad5514340b](https://linux-hardware.org/?probe=ad5514340b) | Jun 25, 2022 |
| ASRock        | A320M-DVS R3.0              | Desktop     | [9244f4847e](https://linux-hardware.org/?probe=9244f4847e) | Jun 22, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [735d7a92b5](https://linux-hardware.org/?probe=735d7a92b5) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [6ebb8676bf](https://linux-hardware.org/?probe=6ebb8676bf) | Jun 16, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [684cf228c4](https://linux-hardware.org/?probe=684cf228c4) | Jun 15, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [041f94473b](https://linux-hardware.org/?probe=041f94473b) | Jun 15, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c43a328a7d](https://linux-hardware.org/?probe=c43a328a7d) | Jun 13, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [5c07fd1664](https://linux-hardware.org/?probe=5c07fd1664) | Jun 12, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [44704fc87d](https://linux-hardware.org/?probe=44704fc87d) | Jun 12, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [60bf6f8388](https://linux-hardware.org/?probe=60bf6f8388) | Jun 12, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [246525a65f](https://linux-hardware.org/?probe=246525a65f) | Jun 11, 2022 |
| Gigabyte      | EX58-UD5                    | Desktop     | [ffcbf35eec](https://linux-hardware.org/?probe=ffcbf35eec) | Jun 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [29f2cd44d5](https://linux-hardware.org/?probe=29f2cd44d5) | Jun 11, 2022 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [5df0f93da9](https://linux-hardware.org/?probe=5df0f93da9) | Jun 10, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [2a3a49ac86](https://linux-hardware.org/?probe=2a3a49ac86) | Jun 10, 2022 |
| Lenovo        | ThinkPad P52s 20LBS04700    | Notebook    | [96e3e051da](https://linux-hardware.org/?probe=96e3e051da) | Jun 09, 2022 |
| Lenovo        | ThinkPad P52s 20LBS04700    | Notebook    | [547e2586ca](https://linux-hardware.org/?probe=547e2586ca) | Jun 09, 2022 |
| eMachines     | eME528                      | Notebook    | [1a6f2ee67f](https://linux-hardware.org/?probe=1a6f2ee67f) | Jun 09, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [f0b7599192](https://linux-hardware.org/?probe=f0b7599192) | Jun 08, 2022 |
| Acer          | Aspire A315-32              | Notebook    | [a610c5537a](https://linux-hardware.org/?probe=a610c5537a) | Jun 07, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [49c5364599](https://linux-hardware.org/?probe=49c5364599) | Jun 04, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6cb0b47bb4](https://linux-hardware.org/?probe=6cb0b47bb4) | Jun 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [658e8ce62f](https://linux-hardware.org/?probe=658e8ce62f) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [c4880f9bab](https://linux-hardware.org/?probe=c4880f9bab) | Jun 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [5330a5aa11](https://linux-hardware.org/?probe=5330a5aa11) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [7f8acf64cd](https://linux-hardware.org/?probe=7f8acf64cd) | May 31, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [d95897f938](https://linux-hardware.org/?probe=d95897f938) | May 31, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [2fbbe84744](https://linux-hardware.org/?probe=2fbbe84744) | May 31, 2022 |
| ASUSTek       | F1A75-M-PRO R2.0            | Desktop     | [070e59ce1e](https://linux-hardware.org/?probe=070e59ce1e) | May 30, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [f1ed3c6a46](https://linux-hardware.org/?probe=f1ed3c6a46) | May 30, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [bcc7398945](https://linux-hardware.org/?probe=bcc7398945) | May 29, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [59159b4b05](https://linux-hardware.org/?probe=59159b4b05) | May 27, 2022 |
| Minix         | Z64 V1.2                    | Notebook    | [97525a1dc3](https://linux-hardware.org/?probe=97525a1dc3) | May 27, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [bdcda1dabc](https://linux-hardware.org/?probe=bdcda1dabc) | May 27, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [e4ccdee802](https://linux-hardware.org/?probe=e4ccdee802) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [e038c828f9](https://linux-hardware.org/?probe=e038c828f9) | May 25, 2022 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0b675c4390](https://linux-hardware.org/?probe=0b675c4390) | May 24, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [7200a39439](https://linux-hardware.org/?probe=7200a39439) | May 23, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [377330c2b5](https://linux-hardware.org/?probe=377330c2b5) | May 23, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [90d9ac6bf3](https://linux-hardware.org/?probe=90d9ac6bf3) | May 18, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [63acfbdc55](https://linux-hardware.org/?probe=63acfbdc55) | May 18, 2022 |
| HP            | 82A5                        | Mini pc     | [4390094fd8](https://linux-hardware.org/?probe=4390094fd8) | May 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1e61b49f67](https://linux-hardware.org/?probe=1e61b49f67) | May 18, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [614f6cf0c6](https://linux-hardware.org/?probe=614f6cf0c6) | May 16, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [2c91bb6c51](https://linux-hardware.org/?probe=2c91bb6c51) | May 16, 2022 |
| Dell          | Precision M6800             | Notebook    | [65d5a77965](https://linux-hardware.org/?probe=65d5a77965) | May 14, 2022 |
| Irbis         | NB144                       | Notebook    | [abb6000f0b](https://linux-hardware.org/?probe=abb6000f0b) | May 14, 2022 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [ecacfd48de](https://linux-hardware.org/?probe=ecacfd48de) | May 14, 2022 |
| Samsung       | 940X5N                      | Convertible | [5464750288](https://linux-hardware.org/?probe=5464750288) | May 13, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [adbb3eb389](https://linux-hardware.org/?probe=adbb3eb389) | May 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eb297f3c7b](https://linux-hardware.org/?probe=eb297f3c7b) | May 12, 2022 |
| Minix         | Z64 V1.2                    | Notebook    | [8796deded0](https://linux-hardware.org/?probe=8796deded0) | May 12, 2022 |
| Lenovo        | Unknown                     | Notebook    | [3cced8a4fa](https://linux-hardware.org/?probe=3cced8a4fa) | May 12, 2022 |
| ASUSTek       | Q170T                       | Desktop     | [7b142a9bf8](https://linux-hardware.org/?probe=7b142a9bf8) | May 10, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [d329ab7f27](https://linux-hardware.org/?probe=d329ab7f27) | May 10, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [1906da1cb4](https://linux-hardware.org/?probe=1906da1cb4) | May 08, 2022 |
| Samsung       | R530/R730/P530              | Notebook    | [d209735fd8](https://linux-hardware.org/?probe=d209735fd8) | May 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | Notebook    | [ac2c2a5969](https://linux-hardware.org/?probe=ac2c2a5969) | May 06, 2022 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [9f255eb7d5](https://linux-hardware.org/?probe=9f255eb7d5) | May 06, 2022 |
| Lenovo        | ThinkPad X220 4290LD4       | Notebook    | [0a28279824](https://linux-hardware.org/?probe=0a28279824) | May 05, 2022 |
| Gigabyte      | IMB1900N                    | Desktop     | [8ed8cb17d5](https://linux-hardware.org/?probe=8ed8cb17d5) | May 04, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [08bd0f2662](https://linux-hardware.org/?probe=08bd0f2662) | May 04, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [2f061f5e18](https://linux-hardware.org/?probe=2f061f5e18) | May 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [26cfc77ab9](https://linux-hardware.org/?probe=26cfc77ab9) | May 02, 2022 |
| ICL           | RAYbook Si1507              | Notebook    | [eaf9bd7ea3](https://linux-hardware.org/?probe=eaf9bd7ea3) | May 02, 2022 |
| HP            | ProBook 4520s               | Notebook    | [ba430a31ae](https://linux-hardware.org/?probe=ba430a31ae) | May 01, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [94272db5ec](https://linux-hardware.org/?probe=94272db5ec) | Apr 30, 2022 |
| ASUSTek       | UX31A                       | Notebook    | [59228e735e](https://linux-hardware.org/?probe=59228e735e) | Apr 30, 2022 |
| Acer          | TravelMate 2490             | Notebook    | [8cc2cf84f4](https://linux-hardware.org/?probe=8cc2cf84f4) | Apr 29, 2022 |
| Intel         | X79 V2.72B                  | Desktop     | [396faf60b6](https://linux-hardware.org/?probe=396faf60b6) | Apr 29, 2022 |
| Timi          | A35S                        | Notebook    | [8a3195e10c](https://linux-hardware.org/?probe=8a3195e10c) | Apr 27, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [67f24b974b](https://linux-hardware.org/?probe=67f24b974b) | Apr 27, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [d060ed71c3](https://linux-hardware.org/?probe=d060ed71c3) | Apr 26, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [4f92840d8c](https://linux-hardware.org/?probe=4f92840d8c) | Apr 26, 2022 |
| Biostar       | G31M+                       | Desktop     | [b756b9bc9f](https://linux-hardware.org/?probe=b756b9bc9f) | Apr 26, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [906f1626d7](https://linux-hardware.org/?probe=906f1626d7) | Apr 24, 2022 |
| Acer          | AOD257                      | Notebook    | [9b11649bce](https://linux-hardware.org/?probe=9b11649bce) | Apr 22, 2022 |
| Acer          | AOD257                      | Notebook    | [e321b17ef8](https://linux-hardware.org/?probe=e321b17ef8) | Apr 22, 2022 |
| MSI           | MS-7267                     | Desktop     | [d0d0dc78d5](https://linux-hardware.org/?probe=d0d0dc78d5) | Apr 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [76bb32f682](https://linux-hardware.org/?probe=76bb32f682) | Apr 20, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | Notebook    | [4ed718df3e](https://linux-hardware.org/?probe=4ed718df3e) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | Notebook    | [402c31b107](https://linux-hardware.org/?probe=402c31b107) | Apr 18, 2022 |
| ASUSTek       | UX303LB                     | Notebook    | [104779add9](https://linux-hardware.org/?probe=104779add9) | Apr 17, 2022 |
| HP            | 250 G2                      | Notebook    | [eafcfe8215](https://linux-hardware.org/?probe=eafcfe8215) | Apr 17, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [ad5a24dbb3](https://linux-hardware.org/?probe=ad5a24dbb3) | Apr 15, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [c0b4f81509](https://linux-hardware.org/?probe=c0b4f81509) | Apr 15, 2022 |
| ASUSTek       | ROG Strix G713QC_G713QC     | Notebook    | [c54b458c01](https://linux-hardware.org/?probe=c54b458c01) | Apr 14, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [e05349d6a0](https://linux-hardware.org/?probe=e05349d6a0) | Apr 14, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | Notebook    | [9e8785fcdd](https://linux-hardware.org/?probe=9e8785fcdd) | Apr 14, 2022 |
| ASUSTek       | X75VCP                      | Notebook    | [21e0b65e1b](https://linux-hardware.org/?probe=21e0b65e1b) | Apr 13, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [eae6b5ed56](https://linux-hardware.org/?probe=eae6b5ed56) | Apr 12, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [54f7cac3d4](https://linux-hardware.org/?probe=54f7cac3d4) | Apr 11, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [f0045560de](https://linux-hardware.org/?probe=f0045560de) | Apr 09, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [263621f796](https://linux-hardware.org/?probe=263621f796) | Apr 08, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [0cabea6484](https://linux-hardware.org/?probe=0cabea6484) | Apr 08, 2022 |
| ASRock        | Z270 Extreme4               | Desktop     | [526a5a16bd](https://linux-hardware.org/?probe=526a5a16bd) | Apr 07, 2022 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [cdb5f43cd7](https://linux-hardware.org/?probe=cdb5f43cd7) | Apr 07, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [ac5d29c839](https://linux-hardware.org/?probe=ac5d29c839) | Apr 05, 2022 |
| Dell          | 0CT017                      | Desktop     | [27bdeec11d](https://linux-hardware.org/?probe=27bdeec11d) | Apr 04, 2022 |
| Timi          | A35                         | Notebook    | [90a30461d2](https://linux-hardware.org/?probe=90a30461d2) | Apr 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [262e4f8317](https://linux-hardware.org/?probe=262e4f8317) | Apr 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [27f986af8c](https://linux-hardware.org/?probe=27f986af8c) | Mar 30, 2022 |
| ASUSTek       | P8H61-I                     | Desktop     | [2e1b862b8b](https://linux-hardware.org/?probe=2e1b862b8b) | Mar 28, 2022 |
| Insignia      | NS-P11W7100                 | Notebook    | [daa476af8c](https://linux-hardware.org/?probe=daa476af8c) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [b431dc3d73](https://linux-hardware.org/?probe=b431dc3d73) | Mar 28, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [c9cc022a93](https://linux-hardware.org/?probe=c9cc022a93) | Mar 28, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [b016648f02](https://linux-hardware.org/?probe=b016648f02) | Mar 27, 2022 |
| Aquarius      | NS585 R32                   | Notebook    | [582389ca98](https://linux-hardware.org/?probe=582389ca98) | Mar 24, 2022 |
| ASUSTek       | X75VCP                      | Notebook    | [54e978fcca](https://linux-hardware.org/?probe=54e978fcca) | Mar 23, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [78f30b04b6](https://linux-hardware.org/?probe=78f30b04b6) | Mar 21, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [46c12ec623](https://linux-hardware.org/?probe=46c12ec623) | Mar 21, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [2ec6236c3a](https://linux-hardware.org/?probe=2ec6236c3a) | Mar 20, 2022 |
| Insignia      | NS-P11W7100                 | Notebook    | [20aa266b33](https://linux-hardware.org/?probe=20aa266b33) | Mar 19, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [725c0249b8](https://linux-hardware.org/?probe=725c0249b8) | Mar 19, 2022 |
| Unknown       | Unknown                     | Notebook    | [58912ced73](https://linux-hardware.org/?probe=58912ced73) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [4652b9e771](https://linux-hardware.org/?probe=4652b9e771) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [091eb95750](https://linux-hardware.org/?probe=091eb95750) | Mar 17, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [80a27aca02](https://linux-hardware.org/?probe=80a27aca02) | Mar 17, 2022 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [2a053f027f](https://linux-hardware.org/?probe=2a053f027f) | Mar 12, 2022 |
| Insignia      | NS-P11W7100                 | Notebook    | [44de443312](https://linux-hardware.org/?probe=44de443312) | Mar 11, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [13a9aa4fb3](https://linux-hardware.org/?probe=13a9aa4fb3) | Mar 08, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [5d73b6f2f7](https://linux-hardware.org/?probe=5d73b6f2f7) | Mar 08, 2022 |
| ASUSTek       | S301LP                      | Notebook    | [5c29218ebd](https://linux-hardware.org/?probe=5c29218ebd) | Mar 08, 2022 |
| Lenovo        | Unknown                     | Notebook    | [4308edfd8d](https://linux-hardware.org/?probe=4308edfd8d) | Mar 07, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [6d16601f06](https://linux-hardware.org/?probe=6d16601f06) | Mar 07, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [9f1edfd714](https://linux-hardware.org/?probe=9f1edfd714) | Mar 07, 2022 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [9e62e2e6d8](https://linux-hardware.org/?probe=9e62e2e6d8) | Mar 07, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [be99e3e64a](https://linux-hardware.org/?probe=be99e3e64a) | Mar 07, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [11ca11b21d](https://linux-hardware.org/?probe=11ca11b21d) | Mar 03, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [fda73ff759](https://linux-hardware.org/?probe=fda73ff759) | Mar 02, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [c11fd047fb](https://linux-hardware.org/?probe=c11fd047fb) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| Unknown       | TB-4000                     | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| ASRock        | P4i65G                      | Desktop     | [aa7a236464](https://linux-hardware.org/?probe=aa7a236464) | Feb 26, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [969cea89d7](https://linux-hardware.org/?probe=969cea89d7) | Feb 24, 2022 |
| HP            | ProBook 4540s               | Notebook    | [6bc6c84af5](https://linux-hardware.org/?probe=6bc6c84af5) | Feb 24, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [72f330a117](https://linux-hardware.org/?probe=72f330a117) | Feb 23, 2022 |
| ASRock        | J4005M                      | Desktop     | [bff0e9d532](https://linux-hardware.org/?probe=bff0e9d532) | Feb 22, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [f6175c2b08](https://linux-hardware.org/?probe=f6175c2b08) | Feb 22, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [4c10662fd3](https://linux-hardware.org/?probe=4c10662fd3) | Feb 21, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [a941fd5481](https://linux-hardware.org/?probe=a941fd5481) | Feb 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [facec46bd5](https://linux-hardware.org/?probe=facec46bd5) | Feb 20, 2022 |
| ASRock        | J4005M                      | Desktop     | [aa149b39ea](https://linux-hardware.org/?probe=aa149b39ea) | Feb 20, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [90a12c2aa1](https://linux-hardware.org/?probe=90a12c2aa1) | Feb 20, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [1998552d88](https://linux-hardware.org/?probe=1998552d88) | Feb 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b4979c164c](https://linux-hardware.org/?probe=b4979c164c) | Feb 20, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ukraine/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 319       | 8.02%   |
| ROSA R10          | 283       | 7.11%   |
| ROSA R11          | 242       | 6.08%   |
| ROSA R8.1         | 203       | 5.1%    |
| Ubuntu 18.04      | 200       | 5.03%   |
| ROSA R9           | 146       | 3.67%   |
| ROSA R11.1        | 138       | 3.47%   |
| ROSA R8           | 136       | 3.42%   |
| OpenMandriva 4.2  | 75        | 1.89%   |
| Arch Rolling      | 67        | 1.68%   |
| ROSA 12.2         | 59        | 1.48%   |
| KDE neon 20.04    | 56        | 1.41%   |
| Debian 11         | 53        | 1.33%   |
| Arch              | 53        | 1.33%   |
| OpenMandriva 4.3  | 48        | 1.21%   |
| Linux Mint 19.3   | 46        | 1.16%   |
| Linux Mint 20     | 44        | 1.11%   |
| Manjaro           | 43        | 1.08%   |
| Ubuntu 22.04      | 42        | 1.06%   |
| Linux Mint 20.2   | 37        | 0.93%   |
| ROSA 12.4         | 35        | 0.88%   |
| Linux Mint 20.1   | 32        | 0.8%    |
| Kubuntu 20.04     | 32        | 0.8%    |
| ROSA 12.5.1       | 31        | 0.78%   |
| Debian 10         | 31        | 0.78%   |
| Ubuntu 19.10      | 29        | 0.73%   |
| Ubuntu 20.10      | 26        | 0.65%   |
| Xubuntu 18.04     | 25        | 0.63%   |
| Linux Mint 19.1   | 25        | 0.63%   |
| Fedora 34         | 25        | 0.63%   |
| ArcoLinux Rolling | 25        | 0.63%   |
| Ubuntu 21.10      | 24        | 0.6%    |
| Ubuntu 19.04      | 24        | 0.6%    |
| Linux Mint 19.2   | 24        | 0.6%    |
| Debian 12         | 24        | 0.6%    |
| Ubuntu 24.04      | 23        | 0.58%   |
| Ubuntu 21.04      | 23        | 0.58%   |
| Linux Mint 18.3   | 23        | 0.58%   |
| Fedora 33         | 23        | 0.58%   |
| Xubuntu 20.04     | 22        | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| ROSA          | 1164      | 31.6%   |
| Ubuntu        | 734       | 19.92%  |
| Linux Mint    | 301       | 8.17%   |
| OpenMandriva  | 196       | 5.32%   |
| Manjaro       | 153       | 4.15%   |
| Fedora        | 138       | 3.75%   |
| Debian        | 127       | 3.45%   |
| Arch          | 118       | 3.2%    |
| Endless       | 117       | 3.18%   |
| KDE neon      | 76        | 2.06%   |
| Kubuntu       | 68        | 1.85%   |
| Xubuntu       | 62        | 1.68%   |
| Pop!_OS       | 37        | 1%      |
| Gentoo        | 27        | 0.73%   |
| Zorin         | 26        | 0.71%   |
| ArcoLinux     | 26        | 0.71%   |
| Kali          | 24        | 0.65%   |
| openSUSE      | 21        | 0.57%   |
| Elementary    | 21        | 0.57%   |
| Ubuntu MATE   | 16        | 0.43%   |
| LMDE          | 16        | 0.43%   |
| ALT Linux     | 15        | 0.41%   |
| Ubuntu Unity  | 14        | 0.38%   |
| SteamOS       | 12        | 0.33%   |
| Lubuntu       | 12        | 0.33%   |
| MX            | 10        | 0.27%   |
| Clear Linux   | 10        | 0.27%   |
| CentOS        | 10        | 0.27%   |
| NixOS         | 9         | 0.24%   |
| EndeavourOS   | 9         | 0.24%   |
| Devuan        | 9         | 0.24%   |
| Ubuntu Budgie | 8         | 0.22%   |
| Red OS        | 6         | 0.16%   |
| Nobara        | 6         | 0.16%   |
| BlackPanther  | 6         | 0.16%   |
| Android       | 6         | 0.16%   |
| Linux Lite    | 5         | 0.14%   |
| Artix         | 5         | 0.14%   |
| Void Linux    | 4         | 0.11%   |
| RELS          | 4         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 116       | 2.75%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 103       | 2.44%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 96        | 2.27%   |
| 5.10.14-desktop-1omv4002            | 74        | 1.75%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 65        | 1.54%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 57        | 1.35%   |
| 5.4.0-42-generic                    | 54        | 1.28%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 48        | 1.14%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 47        | 1.11%   |
| 5.16.7-desktop-1omv4003             | 43        | 1.02%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 43        | 1.02%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 41        | 0.97%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 40        | 0.95%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 36        | 0.85%   |
| 4.15.0-desktop-45.1rosa-i586        | 34        | 0.8%    |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 31        | 0.73%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 31        | 0.73%   |
| 5.3.0-40-generic                    | 29        | 0.69%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 29        | 0.69%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 29        | 0.69%   |
| 5.4.0-48-generic                    | 26        | 0.62%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 26        | 0.62%   |
| 5.4.0-58-generic                    | 25        | 0.59%   |
| 5.8.0-14-generic                    | 23        | 0.54%   |
| 5.4.83-generic-2rosa-x86_64         | 23        | 0.54%   |
| 5.4.0-52-generic                    | 23        | 0.54%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 23        | 0.54%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 23        | 0.54%   |
| 4.18.0-15-generic                   | 21        | 0.5%    |
| 5.8.0-50-generic                    | 20        | 0.47%   |
| 5.4.32-generic-2rosa-x86_64         | 20        | 0.47%   |
| 5.4.0-66-generic                    | 20        | 0.47%   |
| 5.4.0-65-generic                    | 20        | 0.47%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 20        | 0.47%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 20        | 0.47%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 20        | 0.47%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 19        | 0.45%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 19        | 0.45%   |
| 5.4.0-54-generic                    | 18        | 0.43%   |
| 5.3.0-28-generic                    | 18        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 481       | 11.76%  |
| 5.4.0    | 452       | 11.05%  |
| 4.9.60   | 163       | 3.99%   |
| 5.8.0    | 160       | 3.91%   |
| 5.3.0    | 149       | 3.64%   |
| 4.9.20   | 145       | 3.55%   |
| 5.11.0   | 110       | 2.69%   |
| 4.1.34   | 105       | 2.57%   |
| 5.0.0    | 100       | 2.45%   |
| 5.15.0   | 76        | 1.86%   |
| 5.10.14  | 75        | 1.83%   |
| 4.1.38   | 75        | 1.83%   |
| 5.13.0   | 72        | 1.76%   |
| 4.18.0   | 68        | 1.66%   |
| 5.10.0   | 65        | 1.59%   |
| 4.9.9    | 65        | 1.59%   |
| 5.10.74  | 61        | 1.49%   |
| 4.9.124  | 56        | 1.37%   |
| 4.19.0   | 48        | 1.17%   |
| 5.16.7   | 46        | 1.12%   |
| 4.9.76   | 42        | 1.03%   |
| 4.9.41   | 41        | 1%      |
| 6.8.0    | 40        | 0.98%   |
| 5.4.83   | 34        | 0.83%   |
| 4.9.155  | 33        | 0.81%   |
| 5.4.32   | 30        | 0.73%   |
| 6.1.0    | 25        | 0.61%   |
| 4.9.95   | 24        | 0.59%   |
| 4.13.0   | 24        | 0.59%   |
| 5.19.0   | 21        | 0.51%   |
| 5.10.71  | 19        | 0.46%   |
| 6.2.0    | 17        | 0.42%   |
| 6.1.20   | 16        | 0.39%   |
| 4.4.0    | 15        | 0.37%   |
| 6.14.2   | 14        | 0.34%   |
| 5.10.118 | 14        | 0.34%   |
| 6.6.27   | 13        | 0.32%   |
| 6.11.0   | 13        | 0.32%   |
| 5.9.16   | 13        | 0.32%   |
| 4.9.111  | 13        | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 563       | 14.21%  |
| 4.9     | 558       | 14.08%  |
| 4.15    | 481       | 12.14%  |
| 5.10    | 307       | 7.75%   |
| 5.8     | 199       | 5.02%   |
| 4.1     | 182       | 4.59%   |
| 5.3     | 165       | 4.16%   |
| 5.15    | 146       | 3.68%   |
| 5.11    | 140       | 3.53%   |
| 5.0     | 104       | 2.62%   |
| 5.13    | 98        | 2.47%   |
| 6.1     | 82        | 2.07%   |
| 4.18    | 75        | 1.89%   |
| 5.16    | 70        | 1.77%   |
| 4.19    | 62        | 1.56%   |
| 6.6     | 61        | 1.54%   |
| 6.12    | 53        | 1.34%   |
| 6.8     | 52        | 1.31%   |
| 5.6     | 44        | 1.11%   |
| 6.2     | 37        | 0.93%   |
| 5.14    | 37        | 0.93%   |
| 5.9     | 36        | 0.91%   |
| 5.12    | 33        | 0.83%   |
| 6.14    | 28        | 0.71%   |
| 6.11    | 26        | 0.66%   |
| 4.13    | 25        | 0.63%   |
| 5.19    | 24        | 0.61%   |
| 6.4     | 23        | 0.58%   |
| 6.5     | 21        | 0.53%   |
| 5.7     | 20        | 0.5%    |
| 6.10    | 18        | 0.45%   |
| 5.5     | 18        | 0.45%   |
| 5.17    | 18        | 0.45%   |
| 4.4     | 17        | 0.43%   |
| 4.14    | 15        | 0.38%   |
| 6.0     | 11        | 0.28%   |
| 4.8     | 10        | 0.25%   |
| 6.17    | 9         | 0.23%   |
| 6.9     | 8         | 0.2%    |
| 5.18    | 8         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3205      | 88.83%  |
| i686    | 379       | 10.5%   |
| aarch64 | 19        | 0.53%   |
| armv7l  | 5         | 0.14%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 968       | 25.58%  |
| KDE4             | 744       | 19.66%  |
| KDE5             | 735       | 19.42%  |
| Unknown          | 388       | 10.25%  |
| XFCE             | 217       | 5.73%   |
| X-Cinnamon       | 139       | 3.67%   |
| MATE             | 114       | 3.01%   |
| Cinnamon         | 104       | 2.75%   |
| KDE              | 99        | 2.62%   |
| LXQt             | 77        | 2.03%   |
| KDE6             | 69        | 1.82%   |
| i3               | 22        | 0.58%   |
| Pantheon         | 20        | 0.53%   |
| Unity            | 14        | 0.37%   |
| LXDE             | 13        | 0.34%   |
| Budgie           | 11        | 0.29%   |
| Deepin           | 10        | 0.26%   |
| GNOME Flashback  | 9         | 0.24%   |
| Hyprland         | 5         | 0.13%   |
| GNOME Classic    | 5         | 0.13%   |
| Openbox          | 4         | 0.11%   |
| xmonad           | 2         | 0.05%   |
| none+i3          | 2         | 0.05%   |
| fluxbox          | 2         | 0.05%   |
| bspwm            | 2         | 0.05%   |
| wlroots          | 1         | 0.03%   |
| Trinity          | 1         | 0.03%   |
| qtile            | 1         | 0.03%   |
| lightdm-xsession | 1         | 0.03%   |
| KDE:KDE-Wayland  | 1         | 0.03%   |
| i3-with-shmlog   | 1         | 0.03%   |
| Enlightenment    | 1         | 0.03%   |
| Endless:GNOME    | 1         | 0.03%   |
| COSMIC           | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2921      | 79.55%  |
| Wayland | 516       | 14.05%  |
| Unknown | 201       | 5.47%   |
| Tty     | 34        | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1212      | 32.17%  |
| SDDM    | 789       | 20.95%  |
| KDM     | 747       | 19.83%  |
| GDM     | 423       | 11.23%  |
| LightDM | 238       | 6.32%   |
| TDM     | 203       | 5.39%   |
| GDM3    | 120       | 3.19%   |
| MDM     | 12        | 0.32%   |
| XDM     | 9         | 0.24%   |
| SLiM    | 6         | 0.16%   |
| Ly      | 2         | 0.05%   |
| LXDM    | 2         | 0.05%   |
| GREETD  | 2         | 0.05%   |
| NODM    | 1         | 0.03%   |
| LY-DM   | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1291      | 34.8%   |
| en_US          | 818       | 22.05%  |
| ru_RU          | 709       | 19.11%  |
| ru_UA          | 502       | 13.53%  |
| uk_UA          | 266       | 7.17%   |
| C              | 61        | 1.64%   |
| en_GB          | 27        | 0.73%   |
| ru_RU.UTF_8    | 8         | 0.22%   |
| pl_PL          | 4         | 0.11%   |
| es_ES          | 4         | 0.11%   |
| en_CA          | 4         | 0.11%   |
| hu_HU          | 3         | 0.08%   |
| POSIX          | 2         | 0.05%   |
| C.UTF8         | 2         | 0.05%   |
| UTF-8          | 1         | 0.03%   |
| it_IT          | 1         | 0.03%   |
| fr_FR          | 1         | 0.03%   |
| en_ZA          | 1         | 0.03%   |
| en_US.US-ASCII | 1         | 0.03%   |
| en_NZ          | 1         | 0.03%   |
| en_IE          | 1         | 0.03%   |
| en_AG          | 1         | 0.03%   |
| de_DE          | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2201      | 60.33%  |
| EFI  | 1447      | 39.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2412      | 64.98%  |
| Unknown | 727       | 19.59%  |
| Btrfs   | 257       | 6.92%   |
| Overlay | 198       | 5.33%   |
| Tmpfs   | 44        | 1.19%   |
| Xfs     | 28        | 0.75%   |
| Zfs     | 17        | 0.46%   |
| Ext3    | 12        | 0.32%   |
| Ext2    | 12        | 0.32%   |
| F2fs    | 3         | 0.08%   |
| SAMSUNG | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1500      | 40.28%  |
| GPT     | 1143      | 30.69%  |
| MBR     | 1081      | 29.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3113      | 84.94%  |
| Yes       | 552       | 15.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2543      | 68.58%  |
| Yes       | 1165      | 31.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 937       | 26.17%  |
| Lenovo                  | 460       | 12.85%  |
| Hewlett-Packard         | 448       | 12.51%  |
| Acer                    | 283       | 7.9%    |
| Gigabyte Technology     | 261       | 7.29%   |
| Dell                    | 245       | 6.84%   |
| MSI                     | 204       | 5.7%    |
| ASRock                  | 192       | 5.36%   |
| Samsung Electronics     | 67        | 1.87%   |
| Biostar                 | 56        | 1.56%   |
| Intel                   | 36        | 1.01%   |
| Unknown                 | 36        | 1.01%   |
| Timi                    | 30        | 0.84%   |
| Toshiba                 | 25        | 0.7%    |
| Apple                   | 24        | 0.67%   |
| Fujitsu                 | 23        | 0.64%   |
| ECS                     | 18        | 0.5%    |
| Sony                    | 12        | 0.34%   |
| Raspberry Pi Foundation | 12        | 0.34%   |
| eMachines               | 12        | 0.34%   |
| Valve                   | 11        | 0.31%   |
| Fujitsu Siemens         | 11        | 0.31%   |
| Packard Bell            | 10        | 0.28%   |
| Huanan                  | 10        | 0.28%   |
| Foxconn                 | 10        | 0.28%   |
| Pegatron                | 6         | 0.17%   |
| HUAWEI                  | 6         | 0.17%   |
| Google                  | 6         | 0.17%   |
| AMI                     | 5         | 0.14%   |
| VINGA                   | 4         | 0.11%   |
| Supermicro              | 4         | 0.11%   |
| Medion                  | 4         | 0.11%   |
| HONOR                   | 4         | 0.11%   |
| Chuwi                   | 4         | 0.11%   |
| WinFast                 | 3         | 0.08%   |
| TECNO Mobile Limited    | 3         | 0.08%   |
| Shuttle                 | 3         | 0.08%   |
| Nvidia                  | 3         | 0.08%   |
| Notebook                | 3         | 0.08%   |
| Navigator               | 3         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 44        | 1.23%   |
| ASUS All Series                            | 29        | 0.81%   |
| HP Pavilion g6                             | 24        | 0.67%   |
| Lenovo G500 20236                          | 13        | 0.36%   |
| ASUS M5A78L-M LX3                          | 13        | 0.36%   |
| HP Pavilion dv6                            | 12        | 0.34%   |
| HP Pavilion 15                             | 12        | 0.34%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 12        | 0.34%   |
| ASRock N68C-S UCC                          | 12        | 0.34%   |
| ASUS M5A97 R2.0                            | 9         | 0.25%   |
| Lenovo G580 20150                          | 8         | 0.22%   |
| ECS H61H2-M6                               | 8         | 0.22%   |
| ASUS PRIME A320M-K                         | 8         | 0.22%   |
| Acer Aspire V3-571G                        | 8         | 0.22%   |
| Valve Jupiter                              | 7         | 0.2%    |
| MSI MS-7B86                                | 7         | 0.2%    |
| Lenovo V580c 20160                         | 7         | 0.2%    |
| Lenovo IdeaPad Z580                        | 7         | 0.2%    |
| Lenovo IdeaPad Z510 20287                  | 7         | 0.2%    |
| Lenovo G550 20023                          | 7         | 0.2%    |
| HP 250 G5 Notebook PC                      | 7         | 0.2%    |
| Gigabyte G41M-Combo                        | 7         | 0.2%    |
| ASUS P5GC-MX/1333                          | 7         | 0.2%    |
| Samsung R59P/R60P/R61P                     | 6         | 0.17%   |
| Samsung R528/R728                          | 6         | 0.17%   |
| MSI MS-7817                                | 6         | 0.17%   |
| Lenovo G580 20157                          | 6         | 0.17%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 6         | 0.17%   |
| HP Pavilion g7                             | 6         | 0.17%   |
| HP Notebook                                | 6         | 0.17%   |
| HP Laptop 15-bw0xx                         | 6         | 0.17%   |
| HP 620                                     | 6         | 0.17%   |
| HP 255 G7 Notebook PC                      | 6         | 0.17%   |
| HP 250 G4                                  | 6         | 0.17%   |
| Gigabyte B450M DS3H                        | 6         | 0.17%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR       | 6         | 0.17%   |
| ASUS P5Q                                   | 6         | 0.17%   |
| ASUS M4A77TD                               | 6         | 0.17%   |
| ASUS H110M-R                               | 6         | 0.17%   |
| MSI MS-7C56                                | 5         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 170       | 4.75%   |
| Lenovo IdeaPad    | 136       | 3.8%    |
| Lenovo ThinkPad   | 120       | 3.35%   |
| HP Pavilion       | 96        | 2.68%   |
| HP ProBook        | 95        | 2.65%   |
| ASUS VivoBook     | 95        | 2.65%   |
| Dell Inspiron     | 91        | 2.54%   |
| ASUS PRIME        | 64        | 1.79%   |
| Dell Latitude     | 56        | 1.56%   |
| HP Laptop         | 45        | 1.26%   |
| Unknown           | 44        | 1.23%   |
| ASUS TUF          | 34        | 0.95%   |
| HP Compaq         | 33        | 0.92%   |
| ASUS ROG          | 32        | 0.89%   |
| Acer Swift        | 32        | 0.89%   |
| HP EliteBook      | 30        | 0.84%   |
| ASUS All          | 29        | 0.81%   |
| Dell Vostro       | 28        | 0.78%   |
| HP 250            | 26        | 0.73%   |
| ASUS M5A78L-M     | 25        | 0.7%    |
| HP ZBook          | 24        | 0.67%   |
| Dell OptiPlex     | 21        | 0.59%   |
| Toshiba Satellite | 20        | 0.56%   |
| Lenovo Legion     | 19        | 0.53%   |
| Gigabyte B450M    | 19        | 0.53%   |
| ASUS M5A97        | 18        | 0.5%    |
| Acer TravelMate   | 18        | 0.5%    |
| Acer Nitro        | 18        | 0.5%    |
| Acer Extensa      | 17        | 0.47%   |
| Dell Precision    | 16        | 0.45%   |
| Lenovo ThinkBook  | 15        | 0.42%   |
| Lenovo G580       | 15        | 0.42%   |
| HP 255            | 14        | 0.39%   |
| Dell XPS          | 14        | 0.39%   |
| ASUS P8H61-M      | 14        | 0.39%   |
| ASUS P5Q          | 14        | 0.39%   |
| Lenovo G500       | 13        | 0.36%   |
| Timi RedmiBook    | 12        | 0.34%   |
| RPi Raspberry     | 12        | 0.34%   |
| Fujitsu LIFEBOOK  | 12        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 385       | 10.75%  |
| 2011    | 330       | 9.22%   |
| 2018    | 312       | 8.71%   |
| 2010    | 260       | 7.26%   |
| 2019    | 236       | 6.59%   |
| 2017    | 234       | 6.53%   |
| 2013    | 229       | 6.39%   |
| 2020    | 200       | 5.59%   |
| 2009    | 194       | 5.42%   |
| 2007    | 178       | 4.97%   |
| 2016    | 160       | 4.47%   |
| 2015    | 158       | 4.41%   |
| 2008    | 150       | 4.19%   |
| 2014    | 149       | 4.16%   |
| 2021    | 134       | 3.74%   |
| 2006    | 95        | 2.65%   |
| 2022    | 46        | 1.28%   |
| 2023    | 43        | 1.2%    |
| 2005    | 42        | 1.17%   |
| Unknown | 20        | 0.56%   |
| 2024    | 11        | 0.31%   |
| 2025    | 5         | 0.14%   |
| 2004    | 5         | 0.14%   |
| 2003    | 3         | 0.08%   |
| 2002    | 2         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2016      | 56.3%   |
| Desktop        | 1472      | 41.11%  |
| All in one     | 21        | 0.59%   |
| Convertible    | 19        | 0.53%   |
| System on chip | 18        | 0.5%    |
| Mini pc        | 18        | 0.5%    |
| Tablet         | 9         | 0.25%   |
| Phone          | 4         | 0.11%   |
| Server         | 4         | 0.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3445      | 95.88%  |
| Enabled  | 148       | 4.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3573      | 99.78%  |
| Yes  | 8         | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 867       | 23.65%  |
| 4.01-8.0        | 805       | 21.96%  |
| 8.01-16.0       | 661       | 18.03%  |
| 16.01-24.0      | 555       | 15.14%  |
| 1.01-2.0        | 291       | 7.94%   |
| 32.01-64.0      | 195       | 5.32%   |
| 2.01-3.0        | 158       | 4.31%   |
| 0.51-1.0        | 57        | 1.55%   |
| 24.01-32.0      | 39        | 1.06%   |
| 64.01-256.0     | 32        | 0.87%   |
| 0.01-0.5        | 5         | 0.14%   |
| More than 256.0 | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1362      | 34.24%  |
| 2.01-3.0   | 764       | 19.21%  |
| 0.51-1.0   | 723       | 18.17%  |
| 4.01-8.0   | 483       | 12.14%  |
| 3.01-4.0   | 387       | 9.73%   |
| 8.01-16.0  | 148       | 3.72%   |
| 0.01-0.5   | 90        | 2.26%   |
| 16.01-24.0 | 13        | 0.33%   |
| 24.01-32.0 | 4         | 0.1%    |
| Unknown    | 3         | 0.08%   |
| 32.01-64.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2334      | 63.34%  |
| 2      | 909       | 24.67%  |
| 3      | 265       | 7.19%   |
| 4      | 89        | 2.42%   |
| 5      | 38        | 1.03%   |
| 0      | 33        | 0.9%    |
| 6      | 9         | 0.24%   |
| 8      | 4         | 0.11%   |
| 7      | 3         | 0.08%   |
| 9      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2274      | 62.82%  |
| Yes       | 1346      | 37.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3197      | 89.15%  |
| No        | 389       | 10.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2428      | 67.35%  |
| No        | 1177      | 32.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1838      | 50.59%  |
| No        | 1795      | 49.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ukraine | 3581      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Kyiv            | 841       | 22.56%  |
| Kharkiv         | 241       | 6.46%   |
| Simferopol      | 189       | 5.07%   |
| Sevastopol      | 154       | 4.13%   |
| Dnipro          | 153       | 4.1%    |
| Lviv            | 149       | 4%      |
| Odessa          | 139       | 3.73%   |
| Donetsk         | 120       | 3.22%   |
| Zaporizhzhya    | 49        | 1.31%   |
| Mykolayiv       | 49        | 1.31%   |
| Mariupol        | 47        | 1.26%   |
| Zaporizhzhia    | 43        | 1.15%   |
| Vinnytsia       | 39        | 1.05%   |
| Ternopil        | 38        | 1.02%   |
| Kryvyi Rih      | 38        | 1.02%   |
| Poltava         | 35        | 0.94%   |
| Odesa           | 35        | 0.94%   |
| Luhansk         | 35        | 0.94%   |
| Kherson         | 34        | 0.91%   |
| Chernihiv       | 33        | 0.89%   |
| Cherkasy        | 32        | 0.86%   |
| Kremenchug      | 28        | 0.75%   |
| Ivano-Frankivsk | 27        | 0.72%   |
| Yasinovataya    | 26        | 0.7%    |
| Novopskov       | 26        | 0.7%    |
| Horlivka        | 26        | 0.7%    |
| Yalta           | 24        | 0.64%   |
| Uzhhorod        | 23        | 0.62%   |
| Zhytomyr        | 22        | 0.59%   |
| Makiivka        | 21        | 0.56%   |
| Sumy            | 19        | 0.51%   |
| Rivne           | 19        | 0.51%   |
| Lutsk           | 19        | 0.51%   |
| Kerch           | 19        | 0.51%   |
| Kramatorsk      | 18        | 0.48%   |
| Bucha           | 18        | 0.48%   |
| Irpin           | 16        | 0.43%   |
| Yevpatoriya     | 15        | 0.4%    |
| Syeverodonets'k | 15        | 0.4%    |
| Brovary         | 15        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 895       | 1264   | 17.59%  |
| Seagate                     | 827       | 1129   | 16.25%  |
| Samsung Electronics         | 689       | 929    | 13.54%  |
| Toshiba                     | 400       | 506    | 7.86%   |
| Kingston                    | 366       | 475    | 7.19%   |
| Hitachi                     | 273       | 347    | 5.37%   |
| Unknown                     | 144       | 176    | 2.83%   |
| HGST                        | 123       | 173    | 2.42%   |
| SanDisk                     | 109       | 129    | 2.14%   |
| GOODRAM                     | 101       | 119    | 1.99%   |
| SK hynix                    | 98        | 115    | 1.93%   |
| Intel                       | 90        | 115    | 1.77%   |
| Apacer                      | 73        | 79     | 1.43%   |
| Patriot                     | 69        | 80     | 1.36%   |
| Micron Technology           | 60        | 77     | 1.18%   |
| Crucial                     | 59        | 66     | 1.16%   |
| A-DATA Technology           | 50        | 63     | 0.98%   |
| SPCC                        | 46        | 56     | 0.9%    |
| China                       | 46        | 52     | 0.9%    |
| Transcend                   | 41        | 57     | 0.81%   |
| Team                        | 40        | 52     | 0.79%   |
| KIOXIA                      | 29        | 36     | 0.57%   |
| Silicon Motion              | 27        | 33     | 0.53%   |
| Kingston Technology Company | 23        | 27     | 0.45%   |
| Maxtor                      | 21        | 24     | 0.41%   |
| AMD                         | 20        | 43     | 0.39%   |
| JMicron Technology          | 17        | 22     | 0.33%   |
| Phison Electronics          | 15        | 16     | 0.29%   |
| OCZ                         | 15        | 15     | 0.29%   |
| Apple                       | 15        | 18     | 0.29%   |
| LITEON                      | 14        | 16     | 0.28%   |
| KingSpec                    | 14        | 15     | 0.28%   |
| Fujitsu                     | 14        | 17     | 0.28%   |
| Leven                       | 13        | 15     | 0.26%   |
| KingDian                    | 12        | 16     | 0.24%   |
| Plextor                     | 10        | 11     | 0.2%    |
| Gigabyte Technology         | 10        | 11     | 0.2%    |
| Phison                      | 9         | 12     | 0.18%   |
| Netac                       | 9         | 10     | 0.18%   |
| LITEONIT                    | 9         | 11     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 76        | 1.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 60        | 1.1%    |
| Kingston SA400S37240G 240GB SSD                   | 57        | 1.04%   |
| Kingston SA400S37120G 120GB SSD                   | 54        | 0.99%   |
| Toshiba MQ01ABF050 500GB                          | 50        | 0.91%   |
| Samsung SSD 860 EVO 250GB                         | 44        | 0.8%    |
| Seagate ST9500325AS 500GB                         | 42        | 0.77%   |
| Seagate ST500DM002-1BD142 500GB                   | 42        | 0.77%   |
| Toshiba DT01ACA100 1TB                            | 41        | 0.75%   |
| Toshiba DT01ACA050 500GB                          | 38        | 0.69%   |
| Seagate ST500LT012-1DG142 500GB                   | 35        | 0.64%   |
| Toshiba MQ01ABD100 1TB                            | 33        | 0.6%    |
| Toshiba HDWD110 1TB                               | 31        | 0.57%   |
| Kingston SV300S37A120G 120GB SSD                  | 26        | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 25        | 0.46%   |
| Toshiba MQ04ABF100 1TB                            | 25        | 0.46%   |
| Samsung SSD 860 EVO 500GB                         | 25        | 0.46%   |
| HGST HTS545050A7E680 500GB                        | 25        | 0.46%   |
| HGST HTS721010A9E630 1TB                          | 24        | 0.44%   |
| Patriot Burst 120GB SSD                           | 23        | 0.42%   |
| Seagate ST3500418AS 500GB                         | 22        | 0.4%    |
| Samsung NVMe SSD Drive 256GB                      | 21        | 0.38%   |
| Seagate ST9320325AS 320GB                         | 20        | 0.37%   |
| Kingston SA400S37480G 480GB SSD                   | 19        | 0.35%   |
| GOODRAM SSD 120GB                                 | 19        | 0.35%   |
| Seagate ST500LT012-9WS142 500GB                   | 18        | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB                    | 18        | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB                    | 18        | 0.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 18        | 0.33%   |
| Patriot Burst 240GB SSD                           | 18        | 0.33%   |
| Unknown MMC Card  64GB                            | 16        | 0.29%   |
| Hitachi HTS543232A7A384 320GB                     | 16        | 0.29%   |
| WDC WD5000AAKX-001CA0 500GB                       | 15        | 0.27%   |
| Unknown MMC Card  32GB                            | 15        | 0.27%   |
| Samsung SSD 850 EVO 250GB                         | 15        | 0.27%   |
| Kingston SUV400S37120G 120GB SSD                  | 15        | 0.27%   |
| Intel NVMe SSD Drive 512GB                        | 15        | 0.27%   |
| HGST HTS541010A9E680 1TB                          | 15        | 0.27%   |
| SK hynix NVMe SSD Drive 256GB                     | 14        | 0.26%   |
| Seagate ST9250315AS 250GB                         | 14        | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 824       | 1161   | 30.23%  |
| Seagate             | 821       | 1120   | 30.12%  |
| Toshiba             | 357       | 449    | 13.1%   |
| Hitachi             | 273       | 347    | 10.01%  |
| Samsung Electronics | 255       | 357    | 9.35%   |
| HGST                | 123       | 173    | 4.51%   |
| Maxtor              | 21        | 24     | 0.77%   |
| Fujitsu             | 14        | 17     | 0.51%   |
| JMicron Technology  | 9         | 13     | 0.33%   |
| Unknown             | 6         | 8      | 0.22%   |
| Apple               | 4         | 4      | 0.15%   |
| USB3.0              | 3         | 3      | 0.11%   |
| StoreJet            | 2         | 2      | 0.07%   |
| HGST HTS            | 2         | 2      | 0.07%   |
| External            | 2         | 3      | 0.07%   |
| ASMT                | 2         | 6      | 0.07%   |
| USB                 | 1         | 1      | 0.04%   |
| TPH00100500GB       | 1         | 1      | 0.04%   |
| SILICONMOTION       | 1         | 1      | 0.04%   |
| SAGE                | 1         | 1      | 0.04%   |
| IBM/Hitachi         | 1         | 1      | 0.04%   |
| Ext Hard            | 1         | 1      | 0.04%   |
| Config              | 1         | 1      | 0.04%   |
| China               | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 315       | 407    | 21.4%   |
| Samsung Electronics | 241       | 317    | 16.37%  |
| GOODRAM             | 96        | 113    | 6.52%   |
| Apacer              | 69        | 75     | 4.69%   |
| Patriot             | 68        | 79     | 4.62%   |
| SanDisk             | 58        | 67     | 3.94%   |
| Crucial             | 58        | 65     | 3.94%   |
| China               | 45        | 51     | 3.06%   |
| SPCC                | 42        | 50     | 2.85%   |
| A-DATA Technology   | 42        | 55     | 2.85%   |
| Team                | 39        | 48     | 2.65%   |
| Transcend           | 35        | 48     | 2.38%   |
| Intel               | 34        | 41     | 2.31%   |
| WDC                 | 33        | 38     | 2.24%   |
| SK hynix            | 27        | 33     | 1.83%   |
| Micron Technology   | 27        | 31     | 1.83%   |
| AMD                 | 18        | 41     | 1.22%   |
| Toshiba             | 15        | 21     | 1.02%   |
| OCZ                 | 15        | 15     | 1.02%   |
| LITEON              | 13        | 15     | 0.88%   |
| Leven               | 12        | 14     | 0.82%   |
| KingSpec            | 12        | 13     | 0.82%   |
| KingDian            | 12        | 16     | 0.82%   |
| Gigabyte Technology | 10        | 11     | 0.68%   |
| LITEONIT            | 9         | 11     | 0.61%   |
| Plextor             | 8         | 9      | 0.54%   |
| Apple               | 8         | 8      | 0.54%   |
| Netac               | 6         | 6      | 0.41%   |
| StoreJet            | 5         | 5      | 0.34%   |
| DeTech              | 5         | 6      | 0.34%   |
| Verbatim            | 4         | 4      | 0.27%   |
| Smartbuy            | 4         | 5      | 0.27%   |
| Unknown             | 4         | 4      | 0.27%   |
| Pioneer             | 3         | 3      | 0.2%    |
| Indilinx            | 3         | 3      | 0.2%    |
| Corsair             | 3         | 3      | 0.2%    |
| Unknown             | 2         | 2      | 0.14%   |
| Teclast             | 2         | 2      | 0.14%   |
| PNY                 | 2         | 2      | 0.14%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2329      | 3697   | 51.29%  |
| SSD     | 1327      | 1817   | 29.22%  |
| NVMe    | 719       | 935    | 15.83%  |
| MMC     | 128       | 158    | 2.82%   |
| Unknown | 38        | 42     | 0.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2992      | 5450   | 76.27%  |
| NVMe | 719       | 935    | 18.33%  |
| MMC  | 128       | 158    | 3.26%   |
| SAS  | 84        | 106    | 2.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2458      | 3838   | 67.34%  |
| 0.51-1.0   | 942       | 1307   | 25.81%  |
| 1.01-2.0   | 167       | 236    | 4.58%   |
| 2.01-3.0   | 34        | 54     | 0.93%   |
| 3.01-4.0   | 29        | 49     | 0.79%   |
| 4.01-10.0  | 19        | 29     | 0.52%   |
| 20.01-50.0 | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1037      | 26.91%  |
| 251-500        | 858       | 22.27%  |
| 501-1000       | 483       | 12.54%  |
| 1-20           | 370       | 9.6%    |
| 51-100         | 359       | 9.32%   |
| 21-50          | 285       | 7.4%    |
| 1001-2000      | 239       | 6.2%    |
| More than 3000 | 79        | 2.05%   |
| Unknown        | 72        | 1.87%   |
| 2001-3000      | 71        | 1.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1731      | 44.27%  |
| 21-50          | 620       | 15.86%  |
| 101-250        | 473       | 12.1%   |
| 51-100         | 417       | 10.66%  |
| 251-500        | 268       | 6.85%   |
| 501-1000       | 192       | 4.91%   |
| 1001-2000      | 81        | 2.07%   |
| Unknown        | 72        | 1.84%   |
| More than 3000 | 27        | 0.69%   |
| 2001-3000      | 25        | 0.64%   |
| 0              | 4         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 24        | 27     | 2.49%   |
| Seagate ST500DM002-1BD142 500GB    | 16        | 21     | 1.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 15        | 23     | 1.56%   |
| Seagate ST9320325AS 320GB          | 14        | 17     | 1.45%   |
| Seagate ST500LT012-9WS142 500GB    | 12        | 14     | 1.25%   |
| Hitachi HTS543232A7A384 320GB      | 12        | 13     | 1.25%   |
| Seagate ST500LT012-1DG142 500GB    | 11        | 13     | 1.14%   |
| Seagate ST3500418AS 500GB          | 10        | 11     | 1.04%   |
| Samsung Electronics HD321KJ 320GB  | 9         | 12     | 0.93%   |
| HGST HTS545050A7E680 500GB         | 9         | 14     | 0.93%   |
| WDC WD5000AADS-00S9B0 500GB        | 8         | 8      | 0.83%   |
| Seagate ST9250315AS 250GB          | 8         | 9      | 0.83%   |
| Samsung Electronics HD080HJ/ 80GB  | 8         | 8      | 0.83%   |
| WDC WD5000AAKX-001CA0 500GB        | 7         | 8      | 0.73%   |
| Toshiba MQ01ABD100 1TB             | 7         | 7      | 0.73%   |
| Toshiba MQ01ABD050 500GB           | 7         | 9      | 0.73%   |
| Toshiba DT01ACA050 500GB           | 7         | 8      | 0.73%   |
| Seagate ST31000524AS 1TB           | 7         | 9      | 0.73%   |
| Hitachi HTS545050B9A300 500GB      | 7         | 9      | 0.73%   |
| Seagate ST3320620AS 320GB          | 6         | 8      | 0.62%   |
| Seagate ST3250318AS 250GB          | 6         | 8      | 0.62%   |
| Seagate ST320LT020-9YG142 320GB    | 6         | 7      | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB     | 6         | 7      | 0.62%   |
| Samsung Electronics SP2514N 250GB  | 6         | 7      | 0.62%   |
| Hitachi HTS545032B9A300 320GB      | 6         | 8      | 0.62%   |
| Hitachi HTS542516K9SA00 160GB      | 6         | 6      | 0.62%   |
| WDC WD3200BEVT-22A23T0 320GB       | 5         | 5      | 0.52%   |
| WDC WD10EZEX-60ZF5A0 1TB           | 5         | 6      | 0.52%   |
| Seagate ST3250410AS 250GB          | 5         | 8      | 0.52%   |
| Seagate ST3250310AS 250GB          | 5         | 6      | 0.52%   |
| Seagate ST3160811AS 160GB          | 5         | 5      | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB     | 5         | 7      | 0.52%   |
| Samsung Electronics SP2504C 250GB  | 5         | 6      | 0.52%   |
| Samsung Electronics SP2004C 200GB  | 5         | 5      | 0.52%   |
| Samsung Electronics HD403LJ 400GB  | 5         | 6      | 0.52%   |
| Samsung Electronics HD160JJ 160GB  | 5         | 7      | 0.52%   |
| Samsung Electronics HD103SJ 1TB    | 5         | 7      | 0.52%   |
| Maxtor STM3250820AS 250GB          | 5         | 6      | 0.52%   |
| Hitachi HTS545050A7E380 500GB      | 5         | 5      | 0.52%   |
| Hitachi HTS542512K9A300 120GB      | 5         | 6      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 281       | 351    | 29.8%   |
| WDC                         | 214       | 253    | 22.69%  |
| Samsung Electronics         | 130       | 153    | 13.79%  |
| Hitachi                     | 128       | 170    | 13.57%  |
| Toshiba                     | 70        | 85     | 7.42%   |
| Kingston                    | 20        | 27     | 2.12%   |
| HGST                        | 20        | 27     | 2.12%   |
| Maxtor                      | 12        | 14     | 1.27%   |
| SanDisk                     | 7         | 9      | 0.74%   |
| A-DATA Technology           | 7         | 8      | 0.74%   |
| Fujitsu                     | 5         | 8      | 0.53%   |
| SK hynix                    | 4         | 4      | 0.42%   |
| Patriot                     | 4         | 4      | 0.42%   |
| Intel                       | 4         | 4      | 0.42%   |
| OCZ                         | 3         | 3      | 0.32%   |
| Micron Technology           | 3         | 3      | 0.32%   |
| Crucial                     | 3         | 3      | 0.32%   |
| China                       | 3         | 3      | 0.32%   |
| SPCC                        | 2         | 3      | 0.21%   |
| LITEON                      | 2         | 3      | 0.21%   |
| Apple                       | 2         | 2      | 0.21%   |
| Apacer                      | 2         | 4      | 0.21%   |
| Transcend                   | 1         | 1      | 0.11%   |
| TPH00100500GB               | 1         | 1      | 0.11%   |
| Team                        | 1         | 1      | 0.11%   |
| Netac                       | 1         | 1      | 0.11%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.11%   |
| LS                          | 1         | 1      | 0.11%   |
| LITEONIT                    | 1         | 1      | 0.11%   |
| KingSpec                    | 1         | 1      | 0.11%   |
| JMicron Technology          | 1         | 1      | 0.11%   |
| JIAWEI                      | 1         | 1      | 0.11%   |
| JDa                         | 1         | 1      | 0.11%   |
| IBM/Hitachi                 | 1         | 1      | 0.11%   |
| HGST HTS                    | 1         | 1      | 0.11%   |
| GOODRAM                     | 1         | 1      | 0.11%   |
| DeTech                      | 1         | 1      | 0.11%   |
| Corsair                     | 1         | 1      | 0.11%   |
| ADATA Technology            | 1         | 1      | 0.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 281       | 351    | 32.9%   |
| WDC                 | 212       | 251    | 24.82%  |
| Hitachi             | 128       | 170    | 14.99%  |
| Samsung Electronics | 121       | 144    | 14.17%  |
| Toshiba             | 70        | 85     | 8.2%    |
| HGST                | 20        | 27     | 2.34%   |
| Maxtor              | 12        | 14     | 1.41%   |
| Fujitsu             | 5         | 8      | 0.59%   |
| TPH00100500GB       | 1         | 1      | 0.12%   |
| JMicron Technology  | 1         | 1      | 0.12%   |
| IBM/Hitachi         | 1         | 1      | 0.12%   |
| HGST HTS            | 1         | 1      | 0.12%   |
| Apple               | 1         | 1      | 0.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 772       | 1055   | 89.66%  |
| SSD  | 82        | 96     | 9.52%   |
| NVMe | 7         | 7      | 0.81%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 2         | 4      | 6.06%   |
| Seagate ST9250315AS 250GB             | 2         | 2      | 6.06%   |
| Seagate ST31000528AS 1TB              | 2         | 2      | 6.06%   |
| WDC WD5000AAKS-00V1A0 500GB           | 1         | 2      | 3.03%   |
| WDC WD3200BEVT-24A23T0 320GB          | 1         | 1      | 3.03%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 1      | 3.03%   |
| WDC WD3200AAJS-60Z0A0 320GB           | 1         | 1      | 3.03%   |
| WDC WD2500JS-22NCB1 250GB             | 1         | 1      | 3.03%   |
| WDC WD2500AAKS-00F0A0 250GB           | 1         | 1      | 3.03%   |
| WDC WD1600AAJB-00WRA0 160GB           | 1         | 1      | 3.03%   |
| WDC WD1001FALS-00E8B0 1TB             | 1         | 1      | 3.03%   |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 3.03%   |
| Toshiba MK1059GSM 1TB                 | 1         | 1      | 3.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 3.03%   |
| Seagate ST3750525AS 752GB             | 1         | 1      | 3.03%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 3.03%   |
| Seagate ST3500410AS 500GB             | 1         | 1      | 3.03%   |
| Seagate ST320DM001 HD322GJ 320GB      | 1         | 1      | 3.03%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 3.03%   |
| Seagate ST31000340NS 1TB              | 1         | 1      | 3.03%   |
| Samsung Electronics SSD PM800 TM 64GB | 1         | 1      | 3.03%   |
| Samsung Electronics HM321HI 320GB     | 1         | 1      | 3.03%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 3.03%   |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 3.03%   |
| Samsung Electronics HD502HJ 500GB     | 1         | 1      | 3.03%   |
| Samsung Electronics HD252HJ 250GB     | 1         | 4      | 3.03%   |
| Intel SSDSC2KB960G8 960GB             | 1         | 1      | 3.03%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 3.03%   |
| Hitachi HDS721010DLE630 1TB           | 1         | 1      | 3.03%   |
| Hitachi HDS721010CLA332 1TB           | 1         | 1      | 3.03%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 39.39%  |
| WDC                 | 8         | 9      | 24.24%  |
| Samsung Electronics | 6         | 9      | 18.18%  |
| Hitachi             | 3         | 3      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| Intel               | 1         | 1      | 3.03%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1759      | 3041   | 43.44%  |
| Detected | 1415      | 2411   | 34.95%  |
| Malfunc  | 842       | 1158   | 20.8%   |
| Failed   | 33        | 39     | 0.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2376      | 56.05%  |
| AMD                              | 779       | 18.38%  |
| Samsung Electronics              | 220       | 5.19%   |
| Nvidia                           | 137       | 3.23%   |
| SanDisk                          | 94        | 2.22%   |
| JMicron Technology               | 84        | 1.98%   |
| Kingston Technology Company      | 74        | 1.75%   |
| SK hynix                         | 69        | 1.63%   |
| Marvell Technology Group         | 59        | 1.39%   |
| ASMedia Technology               | 48        | 1.13%   |
| Silicon Motion                   | 35        | 0.83%   |
| Micron Technology                | 34        | 0.8%    |
| KIOXIA                           | 33        | 0.78%   |
| Phison Electronics               | 32        | 0.75%   |
| Toshiba America Info Systems     | 31        | 0.73%   |
| ADATA Technology                 | 22        | 0.52%   |
| VIA Technologies                 | 21        | 0.5%    |
| Union Memory (Shenzhen)          | 12        | 0.28%   |
| Silicon Integrated Systems [SiS] | 10        | 0.24%   |
| Shenzhen Longsys Electronics     | 9         | 0.21%   |
| MAXIO Technology (Hangzhou)      | 9         | 0.21%   |
| Realtek Semiconductor            | 7         | 0.17%   |
| Yangtze Memory Technologies      | 5         | 0.12%   |
| Silicon Image                    | 5         | 0.12%   |
| Micron/Crucial Technology        | 5         | 0.12%   |
| Lite-On Technology               | 5         | 0.12%   |
| Solid State Storage Technology   | 4         | 0.09%   |
| ULi Electronics                  | 3         | 0.07%   |
| Transcend                        | 3         | 0.07%   |
| Netac Technology                 | 3         | 0.07%   |
| Integrated Technology Express    | 3         | 0.07%   |
| Broadcom / LSI                   | 2         | 0.05%   |
| Apple                            | 2         | 0.05%   |
| Seagate Technology               | 1         | 0.02%   |
| LSI Logic / Symbios Logic        | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 404       | 7.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 215       | 4.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 190       | 3.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 156       | 2.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 143       | 2.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 141       | 2.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 132       | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 125       | 2.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 115       | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 106       | 2.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 95        | 1.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 91        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 88        | 1.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 82        | 1.57%   |
| Nvidia MCP61 SATA Controller                                                            | 77        | 1.48%   |
| AMD 400 Series Chipset SATA Controller                                                  | 74        | 1.42%   |
| Nvidia MCP61 IDE                                                                        | 72        | 1.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 72        | 1.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 69        | 1.32%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 54        | 1.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 52        | 1%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 51        | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 51        | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 51        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 50        | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 50        | 0.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 46        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 46        | 0.88%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 46        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 45        | 0.86%   |
| AMD SB600 IDE                                                                           | 44        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 42        | 0.81%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 42        | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 40        | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 40        | 0.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 39        | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 36        | 0.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 35        | 0.67%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 34        | 0.65%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 34        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2570      | 58.29%  |
| IDE  | 909       | 20.62%  |
| NVMe | 726       | 16.47%  |
| RAID | 198       | 4.49%   |
| SAS  | 5         | 0.11%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2570      | 71.77%  |
| AMD          | 985       | 27.51%  |
| ARM          | 22        | 0.61%   |
| CentaurHauls | 2         | 0.06%   |
| Unknown      | 2         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 39        | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 39        | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 29        | 0.81%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 27        | 0.75%   |
| AMD Athlon II X2 250 Processor                | 27        | 0.75%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 26        | 0.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 25        | 0.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 0.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 24        | 0.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 23        | 0.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 23        | 0.64%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 21        | 0.58%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 21        | 0.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 19        | 0.53%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 18        | 0.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 18        | 0.5%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 18        | 0.5%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 17        | 0.47%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 17        | 0.47%   |
| AMD Ryzen 5 3600 6-Core Processor             | 17        | 0.47%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 16        | 0.44%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 16        | 0.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 16        | 0.44%   |
| AMD FX-8350 Eight-Core Processor              | 16        | 0.44%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 15        | 0.42%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 15        | 0.42%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 15        | 0.42%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 15        | 0.42%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 0.39%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 0.39%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 14        | 0.39%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 14        | 0.39%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 14        | 0.39%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 14        | 0.39%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 14        | 0.39%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 13        | 0.36%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 13        | 0.36%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.36%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 13        | 0.36%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 13        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 594       | 16.51%  |
| Intel Core i3           | 375       | 10.43%  |
| Intel Core i7           | 373       | 10.37%  |
| Intel Celeron           | 247       | 6.87%   |
| Intel Pentium           | 208       | 5.78%   |
| Intel Core 2 Duo        | 159       | 4.42%   |
| AMD Ryzen 5             | 156       | 4.34%   |
| Other                   | 155       | 4.31%   |
| AMD Ryzen 7             | 96        | 2.67%   |
| Intel Xeon              | 86        | 2.39%   |
| Intel Atom              | 86        | 2.39%   |
| AMD FX                  | 70        | 1.95%   |
| AMD Athlon II X2        | 70        | 1.95%   |
| Intel Pentium Dual-Core | 61        | 1.7%    |
| AMD Athlon 64 X2        | 57        | 1.58%   |
| AMD Ryzen 3             | 49        | 1.36%   |
| Intel Core 2            | 42        | 1.17%   |
| AMD A4                  | 42        | 1.17%   |
| AMD Phenom II X4        | 41        | 1.14%   |
| AMD A6                  | 41        | 1.14%   |
| Intel Core 2 Quad       | 37        | 1.03%   |
| AMD A8                  | 32        | 0.89%   |
| Intel Pentium Dual      | 31        | 0.86%   |
| Intel Pentium Silver    | 30        | 0.83%   |
| AMD A10                 | 30        | 0.83%   |
| Intel Pentium 4         | 29        | 0.81%   |
| AMD Athlon II X4        | 25        | 0.7%    |
| AMD E                   | 24        | 0.67%   |
| AMD Athlon              | 23        | 0.64%   |
| AMD E1                  | 22        | 0.61%   |
| Intel Genuine           | 21        | 0.58%   |
| AMD Ryzen 9             | 21        | 0.58%   |
| Intel Celeron Dual-Core | 17        | 0.47%   |
| AMD Athlon II X3        | 17        | 0.47%   |
| Intel Pentium D         | 16        | 0.44%   |
| AMD Athlon X4           | 16        | 0.44%   |
| AMD Sempron             | 15        | 0.42%   |
| Intel Celeron M         | 13        | 0.36%   |
| AMD E2                  | 13        | 0.36%   |
| AMD Athlon II           | 12        | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1754      | 48.39%  |
| 4       | 1098      | 30.29%  |
| 6       | 242       | 6.68%   |
| 1       | 170       | 4.69%   |
| 8       | 133       | 3.67%   |
| Unknown | 118       | 3.26%   |
| 3       | 34        | 0.94%   |
| 12      | 33        | 0.91%   |
| 16      | 15        | 0.41%   |
| 14      | 10        | 0.28%   |
| 10      | 9         | 0.25%   |
| 24      | 5         | 0.14%   |
| 36      | 1         | 0.03%   |
| 32      | 1         | 0.03%   |
| 20      | 1         | 0.03%   |
| 18      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3561      | 99.44%  |
| 2       | 15        | 0.42%   |
| Unknown | 4         | 0.11%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1871      | 51.6%   |
| 1       | 1637      | 45.15%  |
| Unknown | 118       | 3.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3428      | 95.41%  |
| Unknown        | 91        | 2.53%   |
| 32-bit         | 72        | 2%      |
| 64-bit         | 2         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 796       | 21.62%  |
| 0x206a7    | 259       | 7.04%   |
| 0x306a9    | 232       | 6.3%    |
| 0x1067a    | 170       | 4.62%   |
| 0x306c3    | 116       | 3.15%   |
| 0x010000c8 | 113       | 3.07%   |
| 0x806ea    | 83        | 2.25%   |
| 0x906ea    | 68        | 1.85%   |
| 0x20655    | 65        | 1.77%   |
| 0x06001119 | 65        | 1.77%   |
| 0x806ec    | 62        | 1.68%   |
| 0x6fd      | 62        | 1.68%   |
| 0x506e3    | 57        | 1.55%   |
| 0x806e9    | 56        | 1.52%   |
| 0x906e9    | 54        | 1.47%   |
| 0x406e3    | 49        | 1.33%   |
| 0x10676    | 46        | 1.25%   |
| 0x806c1    | 41        | 1.11%   |
| 0x40651    | 41        | 1.11%   |
| 0x706a1    | 38        | 1.03%   |
| 0x106ca    | 38        | 1.03%   |
| 0x08108109 | 37        | 1.01%   |
| 0x30678    | 36        | 0.98%   |
| 0x306d4    | 35        | 0.95%   |
| 0x03000027 | 32        | 0.87%   |
| 0x406c4    | 31        | 0.84%   |
| 0x06000852 | 29        | 0.79%   |
| 0x6fb      | 28        | 0.76%   |
| 0x506c9    | 28        | 0.76%   |
| 0x20652    | 27        | 0.73%   |
| 0x6f6      | 24        | 0.65%   |
| 0x05000119 | 23        | 0.62%   |
| 0xa0652    | 21        | 0.57%   |
| 0x406c3    | 20        | 0.54%   |
| 0x906eb    | 19        | 0.52%   |
| 0x08600106 | 19        | 0.52%   |
| 0x08108102 | 19        | 0.52%   |
| 0x010000c7 | 19        | 0.52%   |
| 0x6f2      | 18        | 0.49%   |
| 0x06003106 | 18        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 489       | 13.58%  |
| SandyBridge       | 317       | 8.8%    |
| IvyBridge         | 277       | 7.69%   |
| Penryn            | 247       | 6.86%   |
| K10               | 197       | 5.47%   |
| Haswell           | 197       | 5.47%   |
| Core              | 172       | 4.78%   |
| Skylake           | 138       | 3.83%   |
| Piledriver        | 125       | 3.47%   |
| Unknown           | 121       | 3.36%   |
| Westmere          | 112       | 3.11%   |
| Silvermont        | 97        | 2.69%   |
| Zen 2             | 94        | 2.61%   |
| K8 Hammer         | 92        | 2.55%   |
| Zen+              | 91        | 2.53%   |
| Zen               | 77        | 2.14%   |
| Goldmont plus     | 73        | 2.03%   |
| Zen 3             | 62        | 1.72%   |
| TigerLake         | 61        | 1.69%   |
| Bonnell           | 60        | 1.67%   |
| NetBurst          | 55        | 1.53%   |
| CometLake         | 54        | 1.5%    |
| Broadwell         | 45        | 1.25%   |
| Bobcat            | 44        | 1.22%   |
| Excavator         | 42        | 1.17%   |
| K10 Llano         | 33        | 0.92%   |
| P6                | 32        | 0.89%   |
| Goldmont          | 31        | 0.86%   |
| Alderlake Hybrid  | 30        | 0.83%   |
| Icelake           | 25        | 0.69%   |
| Steamroller       | 21        | 0.58%   |
| Nehalem           | 20        | 0.56%   |
| Puma              | 19        | 0.53%   |
| Bulldozer         | 17        | 0.47%   |
| Jaguar            | 14        | 0.39%   |
| K8 & K10 hybrid   | 9         | 0.25%   |
| Tremont           | 7         | 0.19%   |
| Meteorlake Hybrid | 1         | 0.03%   |
| Lunarlake Hybrid  | 1         | 0.03%   |
| K6                | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1882      | 43.3%   |
| Nvidia                                       | 1326      | 30.51%  |
| AMD                                          | 1114      | 25.63%  |
| VIA Technologies                             | 7         | 0.16%   |
| Silicon Integrated Systems [SiS]             | 6         | 0.14%   |
| ATI Technologies                             | 6         | 0.14%   |
| Matrox Electronics Systems                   | 2         | 0.05%   |
| ASPEED Technology                            | 2         | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 240       | 5.28%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 170       | 3.74%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 91        | 2%      |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 69        | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 65        | 1.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 65        | 1.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 64        | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 63        | 1.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 60        | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 58        | 1.28%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 55        | 1.21%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 54        | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 51        | 1.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 51        | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 48        | 1.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 1.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 1.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 40        | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 40        | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 38        | 0.84%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 37        | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 37        | 0.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 36        | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 36        | 0.79%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 34        | 0.75%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 33        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 32        | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 30        | 0.66%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 30        | 0.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 30        | 0.66%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 30        | 0.66%   |
| Nvidia GP108M [GeForce MX150]                                                            | 29        | 0.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 29        | 0.64%   |
| Nvidia GM108M [GeForce MX110]                                                            | 28        | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 26        | 0.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 26        | 0.57%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 26        | 0.57%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 26        | 0.57%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 26        | 0.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 26        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 1169      | 32.32%  |
| 1 x AMD                | 806       | 22.28%  |
| 1 x Nvidia             | 742       | 20.51%  |
| Intel + Nvidia         | 527       | 14.57%  |
| Intel + AMD            | 148       | 4.09%   |
| 2 x AMD                | 119       | 3.29%   |
| AMD + Nvidia           | 48        | 1.33%   |
| Other                  | 26        | 0.72%   |
| 1 x VIA                | 7         | 0.19%   |
| 1 x SiS                | 6         | 0.17%   |
| 2 x Intel              | 5         | 0.14%   |
| 2 x Nvidia             | 4         | 0.11%   |
| Intel + 2 x Nvidia     | 2         | 0.06%   |
| 3 x Nvidia             | 1         | 0.03%   |
| 1 x XGI                | 1         | 0.03%   |
| Nvidia + Matrox        | 1         | 0.03%   |
| Nvidia + ASPEED        | 1         | 0.03%   |
| 1 x Matrox             | 1         | 0.03%   |
| 1 x Intel + 7 x Nvidia | 1         | 0.03%   |
| Intel + 2 x AMD        | 1         | 0.03%   |
| 1 x ASPEED             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2937      | 80.27%  |
| Proprietary | 557       | 15.22%  |
| Unknown     | 165       | 4.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1431      | 38.64%  |
| 1.01-2.0   | 725       | 19.58%  |
| 0.01-0.5   | 680       | 18.36%  |
| 0.51-1.0   | 436       | 11.77%  |
| 3.01-4.0   | 252       | 6.81%   |
| 7.01-8.0   | 82        | 2.21%   |
| 5.01-6.0   | 47        | 1.27%   |
| 2.01-3.0   | 29        | 0.78%   |
| 8.01-16.0  | 21        | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 682       | 18.09%  |
| AU Optronics            | 452       | 11.99%  |
| Goldstar                | 363       | 9.63%   |
| LG Display              | 361       | 9.58%   |
| Chimei Innolux          | 283       | 7.51%   |
| BOE                     | 279       | 7.4%    |
| Philips                 | 179       | 4.75%   |
| Dell                    | 179       | 4.75%   |
| Acer                    | 101       | 2.68%   |
| Chi Mei Optoelectronics | 94        | 2.49%   |
| Ancor Communications    | 83        | 2.2%    |
| BenQ                    | 68        | 1.8%    |
| AOC                     | 62        | 1.64%   |
| Hewlett-Packard         | 50        | 1.33%   |
| Lenovo                  | 43        | 1.14%   |
| LG Philips              | 35        | 0.93%   |
| ViewSonic               | 34        | 0.9%    |
| Sharp                   | 34        | 0.9%    |
| PANDA                   | 30        | 0.8%    |
| Apple                   | 25        | 0.66%   |
| Iiyama                  | 24        | 0.64%   |
| LG Electronics          | 22        | 0.58%   |
| HannStar                | 21        | 0.56%   |
| Sony                    | 18        | 0.48%   |
| NEC Computers           | 18        | 0.48%   |
| ASUSTek Computer        | 18        | 0.48%   |
| Unknown                 | 14        | 0.37%   |
| Valve                   | 11        | 0.29%   |
| CPT                     | 10        | 0.27%   |
| Mi                      | 8         | 0.21%   |
| Belinea                 | 8         | 0.21%   |
| Toshiba                 | 6         | 0.16%   |
| Xiaomi                  | 5         | 0.13%   |
| Plain Tree Systems      | 5         | 0.13%   |
| MStar                   | 5         | 0.13%   |
| MSI                     | 5         | 0.13%   |
| InfoVision              | 5         | 0.13%   |
| CSOT                    | 5         | 0.13%   |
| ___                     | 4         | 0.11%   |
| TMX                     | 4         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 34        | 0.88%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 30        | 0.78%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 27        | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 27        | 0.7%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 26        | 0.67%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 24        | 0.62%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 23        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 22        | 0.57%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 21        | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 21        | 0.54%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 20        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 19        | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 18        | 0.47%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.47%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 18        | 0.47%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 18        | 0.47%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 17        | 0.44%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 16        | 0.41%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 15        | 0.39%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 15        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 15        | 0.39%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 14        | 0.36%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.31%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 12        | 0.31%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 12        | 0.31%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                     | 12        | 0.31%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch     | 11        | 0.28%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 11        | 0.28%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.28%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 11        | 0.28%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.28%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch     | 10        | 0.26%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 10        | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 10        | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 10        | 0.26%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 9         | 0.23%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 9         | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 9         | 0.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 9         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1508      | 41.47%  |
| 1366x768 (WXGA)    | 797       | 21.92%  |
| 1280x1024 (SXGA)   | 279       | 7.67%   |
| 1600x900 (HD+)     | 163       | 4.48%   |
| 1680x1050 (WSXGA+) | 161       | 4.43%   |
| 3840x2160 (4K)     | 109       | 3%      |
| 1280x800 (WXGA)    | 97        | 2.67%   |
| 1440x900 (WXGA+)   | 91        | 2.5%    |
| 2560x1440 (QHD)    | 83        | 2.28%   |
| 1920x1200 (WUXGA)  | 63        | 1.73%   |
| 1024x600           | 44        | 1.21%   |
| 1360x768           | 26        | 0.72%   |
| 1024x768 (XGA)     | 24        | 0.66%   |
| Unknown            | 23        | 0.63%   |
| 1600x1200          | 22        | 0.61%   |
| 2560x1600          | 20        | 0.55%   |
| 2560x1080          | 19        | 0.52%   |
| 800x1280           | 11        | 0.3%    |
| 3440x1440          | 10        | 0.28%   |
| 1920x540           | 7         | 0.19%   |
| 3840x1080          | 6         | 0.17%   |
| 2288x1287          | 6         | 0.17%   |
| 1280x720 (HD)      | 6         | 0.17%   |
| 2048x1536          | 5         | 0.14%   |
| 1400x1050          | 5         | 0.14%   |
| 3456x2160          | 4         | 0.11%   |
| 3200x2000          | 4         | 0.11%   |
| 3840x2400          | 3         | 0.08%   |
| 3200x1800 (QHD+)   | 3         | 0.08%   |
| 2048x1152          | 3         | 0.08%   |
| 5520x1080          | 2         | 0.06%   |
| 4480x1440          | 2         | 0.06%   |
| 3200x1080          | 2         | 0.06%   |
| 2880x1620          | 2         | 0.06%   |
| 2160x1440          | 2         | 0.06%   |
| 1280x960           | 2         | 0.06%   |
| 1280x768           | 2         | 0.06%   |
| 7040x2160          | 1         | 0.03%   |
| 5280x1200          | 1         | 0.03%   |
| 5120x1440          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1249      | 33.12%  |
| 21      | 300       | 7.96%   |
| 17      | 283       | 7.5%    |
| 23      | 280       | 7.43%   |
| 24      | 214       | 5.67%   |
| 14      | 192       | 5.09%   |
| 19      | 183       | 4.85%   |
| 13      | 182       | 4.83%   |
| Unknown | 130       | 3.45%   |
| 27      | 128       | 3.39%   |
| 18      | 95        | 2.52%   |
| 20      | 87        | 2.31%   |
| 22      | 83        | 2.2%    |
| 31      | 44        | 1.17%   |
| 12      | 42        | 1.11%   |
| 11      | 41        | 1.09%   |
| 10      | 41        | 1.09%   |
| 16      | 40        | 1.06%   |
| 32      | 28        | 0.74%   |
| 34      | 18        | 0.48%   |
| 7       | 12        | 0.32%   |
| 72      | 11        | 0.29%   |
| 54      | 11        | 0.29%   |
| 25      | 10        | 0.27%   |
| 26      | 7         | 0.19%   |
| 142     | 6         | 0.16%   |
| 42      | 6         | 0.16%   |
| 40      | 6         | 0.16%   |
| 63      | 5         | 0.13%   |
| 52      | 5         | 0.13%   |
| 46      | 5         | 0.13%   |
| 65      | 4         | 0.11%   |
| 8       | 4         | 0.11%   |
| 84      | 3         | 0.08%   |
| 48      | 2         | 0.05%   |
| 47      | 2         | 0.05%   |
| 43      | 2         | 0.05%   |
| 28      | 2         | 0.05%   |
| 75      | 1         | 0.03%   |
| 58      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1657      | 44.41%  |
| 401-500        | 620       | 16.62%  |
| 501-600        | 592       | 15.87%  |
| 351-400        | 324       | 8.68%   |
| 201-300        | 212       | 5.68%   |
| Unknown        | 130       | 3.48%   |
| 601-700        | 59        | 1.58%   |
| 701-800        | 45        | 1.21%   |
| 1001-1500      | 37        | 0.99%   |
| 1501-2000      | 15        | 0.4%    |
| 1-100          | 11        | 0.29%   |
| 801-900        | 10        | 0.27%   |
| 901-1000       | 8         | 0.21%   |
| More than 2000 | 6         | 0.16%   |
| 101-200        | 5         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2564      | 73.24%  |
| 16/10   | 427       | 12.2%   |
| 5/4     | 249       | 7.11%   |
| Unknown | 105       | 3%      |
| 4/3     | 84        | 2.4%    |
| 3/2     | 26        | 0.74%   |
| 21/9    | 19        | 0.54%   |
| 0.67    | 7         | 0.2%    |
| 6/5     | 6         | 0.17%   |
| 1.00    | 6         | 0.17%   |
| 0.62    | 4         | 0.11%   |
| 32/9    | 2         | 0.06%   |
| 3.40    | 1         | 0.03%   |
| 0.89    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1223      | 32.67%  |
| 201-250        | 752       | 20.09%  |
| 151-200        | 331       | 8.84%   |
| 81-90          | 299       | 7.99%   |
| 141-150        | 204       | 5.45%   |
| 121-130        | 138       | 3.69%   |
| 301-350        | 130       | 3.47%   |
| Unknown        | 130       | 3.47%   |
| 351-500        | 93        | 2.48%   |
| 71-80          | 73        | 1.95%   |
| 251-300        | 68        | 1.82%   |
| 111-120        | 53        | 1.42%   |
| More than 1000 | 50        | 1.34%   |
| 51-60          | 42        | 1.12%   |
| 41-50          | 41        | 1.1%    |
| 61-70          | 36        | 0.96%   |
| 131-140        | 29        | 0.77%   |
| 501-1000       | 24        | 0.64%   |
| 1-40           | 16        | 0.43%   |
| 91-100         | 12        | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1355      | 37.14%  |
| 101-120       | 1110      | 30.43%  |
| 121-160       | 864       | 23.68%  |
| Unknown       | 130       | 3.56%   |
| 161-240       | 106       | 2.91%   |
| 1-50          | 49        | 1.34%   |
| More than 240 | 34        | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3065      | 84.34%  |
| 2     | 414       | 11.39%  |
| 0     | 121       | 3.33%   |
| 3     | 34        | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2186      | 41.14%  |
| Intel                             | 1085      | 20.42%  |
| Qualcomm Atheros                  | 866       | 16.3%   |
| Broadcom                          | 309       | 5.82%   |
| Ralink Technology                 | 109       | 2.05%   |
| Nvidia                            | 104       | 1.96%   |
| Broadcom Limited                  | 81        | 1.52%   |
| Marvell Technology Group          | 76        | 1.43%   |
| Ralink                            | 70        | 1.32%   |
| MediaTek                          | 53        | 1%      |
| Qualcomm Atheros Communications   | 41        | 0.77%   |
| TP-Link                           | 38        | 0.72%   |
| Huawei Technologies               | 26        | 0.49%   |
| Xiaomi                            | 24        | 0.45%   |
| VIA Technologies                  | 21        | 0.4%    |
| Samsung Electronics               | 17        | 0.32%   |
| D-Link System                     | 13        | 0.24%   |
| ASUSTek Computer                  | 13        | 0.24%   |
| Dell                              | 12        | 0.23%   |
| Attansic Technology               | 12        | 0.23%   |
| Sundance Technology Inc / IC Plus | 11        | 0.21%   |
| ASIX Electronics                  | 10        | 0.19%   |
| Sierra Wireless                   | 9         | 0.17%   |
| Qualcomm                          | 8         | 0.15%   |
| JMicron Technology                | 8         | 0.15%   |
| Silicon Integrated Systems [SiS]  | 7         | 0.13%   |
| Ericsson Business Mobile Networks | 7         | 0.13%   |
| Shenzhen Goodix Technology        | 6         | 0.11%   |
| ICS Advent                        | 6         | 0.11%   |
| D-Link                            | 6         | 0.11%   |
| Microsoft                         | 5         | 0.09%   |
| Hewlett-Packard                   | 5         | 0.09%   |
| DisplayLink                       | 4         | 0.08%   |
| Aquantia                          | 4         | 0.08%   |
| Microchip Technology              | 3         | 0.06%   |
| Lenovo                            | 3         | 0.06%   |
| IMC Networks                      | 3         | 0.06%   |
| Google                            | 3         | 0.06%   |
| Fibocom                           | 3         | 0.06%   |
| Edimax Technology                 | 3         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 1538      | 25.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 331       | 5.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 158       | 2.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 117       | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 112       | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 108       | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 99        | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 94        | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 86        | 1.43%   |
| Intel Wireless 8265 / 8275                                              | 71        | 1.18%   |
| Intel Wi-Fi 6 AX200                                                     | 69        | 1.15%   |
| Ralink MT7601U Wireless Adapter                                         | 66        | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 66        | 1.1%    |
| Nvidia MCP61 Ethernet                                                   | 64        | 1.07%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 60        | 1%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 52        | 0.87%   |
| Intel Wireless 7260                                                     | 51        | 0.85%   |
| Intel Wi-Fi 6 AX201                                                     | 49        | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 47        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 46        | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 43        | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 40        | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 40        | 0.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 39        | 0.65%   |
| Intel I211 Gigabit Network Connection                                   | 38        | 0.63%   |
| Broadcom BCM43142 802.11b/g/n                                           | 38        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 37        | 0.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 36        | 0.6%    |
| Intel Wireless 3165                                                     | 36        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 35        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 33        | 0.55%   |
| Realtek RTL8125 2.5GbE Controller                                       | 33        | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 33        | 0.55%   |
| Qualcomm Atheros AR9271 802.11n                                         | 32        | 0.53%   |
| Intel Ethernet Connection (2) I219-V                                    | 32        | 0.53%   |
| Intel Wireless 8260                                                     | 31        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 30        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 30        | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 29        | 0.48%   |
| Intel Wireless 7265                                                     | 29        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 844       | 33.51%  |
| Qualcomm Atheros                | 645       | 25.61%  |
| Realtek Semiconductor           | 389       | 15.44%  |
| Broadcom                        | 222       | 8.81%   |
| Ralink Technology               | 109       | 4.33%   |
| Ralink                          | 70        | 2.78%   |
| Broadcom Limited                | 47        | 1.87%   |
| MediaTek                        | 46        | 1.83%   |
| Qualcomm Atheros Communications | 41        | 1.63%   |
| TP-Link                         | 35        | 1.39%   |
| ASUSTek Computer                | 10        | 0.4%    |
| Sierra Wireless                 | 9         | 0.36%   |
| Dell                            | 8         | 0.32%   |
| D-Link System                   | 8         | 0.32%   |
| D-Link                          | 6         | 0.24%   |
| Qualcomm                        | 5         | 0.2%    |
| Microsoft                       | 5         | 0.2%    |
| IMC Networks                    | 3         | 0.12%   |
| Fibocom                         | 3         | 0.12%   |
| Edimax Technology               | 3         | 0.12%   |
| Linksys                         | 2         | 0.08%   |
| ZyDAS                           | 1         | 0.04%   |
| Xiaomi                          | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| NetGear                         | 1         | 0.04%   |
| Mercucys                        | 1         | 0.04%   |
| LG Electronics                  | 1         | 0.04%   |
| Hewlett-Packard                 | 1         | 0.04%   |
| Gemtek                          | 1         | 0.04%   |
| Fujitsu Siemens Computers       | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 158       | 6.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 112       | 4.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 108       | 4.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 99        | 3.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 94        | 3.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 86        | 3.4%    |
| Intel Wireless 8265 / 8275                                              | 71        | 2.81%   |
| Intel Wi-Fi 6 AX200                                                     | 69        | 2.73%   |
| Ralink MT7601U Wireless Adapter                                         | 66        | 2.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 52        | 2.06%   |
| Intel Wireless 7260                                                     | 51        | 2.02%   |
| Intel Wi-Fi 6 AX201                                                     | 49        | 1.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 47        | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 46        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 43        | 1.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 40        | 1.58%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 39        | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                           | 38        | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 37        | 1.46%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 36        | 1.43%   |
| Intel Wireless 3165                                                     | 36        | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 35        | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 33        | 1.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 33        | 1.31%   |
| Qualcomm Atheros AR9271 802.11n                                         | 32        | 1.27%   |
| Intel Wireless 8260                                                     | 31        | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 29        | 1.15%   |
| Intel Wireless 7265                                                     | 29        | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 29        | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 27        | 1.07%   |
| Intel Centrino Wireless-N 2230                                          | 25        | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 24        | 0.95%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 22        | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 22        | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 21        | 0.83%   |
| Ralink RT5370 Wireless Adapter                                          | 20        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 20        | 0.79%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 20        | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 19        | 0.75%   |
| Intel Centrino Ultimate-N 6300                                          | 19        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2047      | 60.83%  |
| Intel                                  | 471       | 14%     |
| Qualcomm Atheros                       | 320       | 9.51%   |
| Broadcom                               | 116       | 3.45%   |
| Nvidia                                 | 104       | 3.09%   |
| Marvell Technology Group               | 76        | 2.26%   |
| Broadcom Limited                       | 36        | 1.07%   |
| Xiaomi                                 | 23        | 0.68%   |
| VIA Technologies                       | 21        | 0.62%   |
| Huawei Technologies                    | 19        | 0.56%   |
| Samsung Electronics                    | 17        | 0.51%   |
| Attansic Technology                    | 12        | 0.36%   |
| Sundance Technology Inc / IC Plus      | 11        | 0.33%   |
| ASIX Electronics                       | 10        | 0.3%    |
| JMicron Technology                     | 8         | 0.24%   |
| Silicon Integrated Systems [SiS]       | 7         | 0.21%   |
| MediaTek                               | 6         | 0.18%   |
| ICS Advent                             | 6         | 0.18%   |
| D-Link System                          | 5         | 0.15%   |
| DisplayLink                            | 4         | 0.12%   |
| Aquantia                               | 4         | 0.12%   |
| TP-Link                                | 3         | 0.09%   |
| Qualcomm                               | 3         | 0.09%   |
| Microchip Technology                   | 3         | 0.09%   |
| Lenovo                                 | 3         | 0.09%   |
| Hewlett-Packard                        | 3         | 0.09%   |
| Google                                 | 3         | 0.09%   |
| ASUSTek Computer                       | 3         | 0.09%   |
| Spreadtrum Communications              | 2         | 0.06%   |
| Raspberry Pi                           | 2         | 0.06%   |
| Motorola PCS                           | 2         | 0.06%   |
| HMD Global                             | 2         | 0.06%   |
| Tehuti Networks                        | 1         | 0.03%   |
| Standard Microsystems [SMC]            | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QinHeng Electronics                    | 1         | 0.03%   |
| OPPO Electronics                       | 1         | 0.03%   |
| OKB SAPR                               | 1         | 0.03%   |
| LSI                                    | 1         | 0.03%   |
| HTC (High Tech Computer)               | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1538      | 44.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 331       | 9.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 117       | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 66        | 1.93%   |
| Nvidia MCP61 Ethernet                                                  | 64        | 1.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 60        | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 40        | 1.17%   |
| Intel I211 Gigabit Network Connection                                  | 38        | 1.11%   |
| Realtek RTL8125 2.5GbE Controller                                      | 33        | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                   | 32        | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 30        | 0.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 30        | 0.88%   |
| Intel 82579V Gigabit Network Connection                                | 28        | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 23        | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 23        | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 22        | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 21        | 0.61%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 21        | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 21        | 0.61%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 20        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 20        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 20        | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 18        | 0.53%   |
| Intel Ethernet Connection (6) I219-V                                   | 18        | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 17        | 0.5%    |
| Intel Ethernet Connection I217-LM                                      | 17        | 0.5%    |
| Intel Ethernet Connection I217-V                                       | 15        | 0.44%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 15        | 0.44%   |
| Intel Ethernet Connection (7) I219-V                                   | 14        | 0.41%   |
| Intel Ethernet Connection (4) I219-V                                   | 14        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 13        | 0.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 13        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                                  | 13        | 0.38%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 13        | 0.38%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 12        | 0.35%   |
| Nvidia MCP51 Ethernet Controller                                       | 12        | 0.35%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 0.35%   |
| Intel Ethernet Connection I218-LM                                      | 12        | 0.35%   |
| Intel 82577LM Gigabit Network Connection                               | 12        | 0.35%   |
| Attansic AR8152 v2.0 Fast Ethernet                                     | 12        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3192      | 56.3%   |
| WiFi     | 2427      | 42.8%   |
| Modem    | 49        | 0.86%   |
| Unknown  | 2         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1944      | 52.6%   |
| Ethernet | 1752      | 47.4%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1914      | 53.27%  |
| 1     | 1571      | 43.72%  |
| 0     | 70        | 1.95%   |
| 3     | 36        | 1%      |
| 6     | 1         | 0.03%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3538      | 98.72%  |
| Yes  | 46        | 1.28%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 650       | 35.15%  |
| Qualcomm Atheros Communications | 204       | 11.03%  |
| Realtek Semiconductor           | 202       | 10.92%  |
| IMC Networks                    | 169       | 9.14%   |
| Cambridge Silicon Radio         | 119       | 6.44%   |
| Lite-On Technology              | 108       | 5.84%   |
| Broadcom                        | 104       | 5.62%   |
| Foxconn / Hon Hai               | 74        | 4%      |
| Ralink                          | 36        | 1.95%   |
| ASUSTek Computer                | 36        | 1.95%   |
| Hewlett-Packard                 | 30        | 1.62%   |
| Apple                           | 25        | 1.35%   |
| Dell                            | 21        | 1.14%   |
| Toshiba                         | 11        | 0.59%   |
| Ralink Technology               | 10        | 0.54%   |
| Foxconn International           | 9         | 0.49%   |
| Realtek                         | 6         | 0.32%   |
| MediaTek                        | 5         | 0.27%   |
| Opticis                         | 4         | 0.22%   |
| Alps Electric                   | 4         | 0.22%   |
| Micro Star International        | 3         | 0.16%   |
| Conwise Technology              | 3         | 0.16%   |
| Taiyo Yuden                     | 2         | 0.11%   |
| Edimax Technology               | 2         | 0.11%   |
| D-Link                          | 2         | 0.11%   |
| Askey Computer                  | 2         | 0.11%   |
| TP-Link                         | 1         | 0.05%   |
| Roper                           | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| Integrated System Solution      | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 224       | 12.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 121       | 6.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 119       | 6.44%   |
| Realtek Bluetooth Radio                             | 113       | 6.11%   |
| Intel AX201 Bluetooth                               | 109       | 5.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 76        | 4.11%   |
| Intel AX200 Bluetooth                               | 67        | 3.62%   |
| IMC Networks Bluetooth Radio                        | 67        | 3.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 59        | 3.19%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 59        | 3.19%   |
| IMC Networks Bluetooth Device                       | 47        | 2.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 39        | 2.11%   |
| Ralink RT3290 Bluetooth                             | 36        | 1.95%   |
| Lite-On Bluetooth Device                            | 36        | 1.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 34        | 1.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 32        | 1.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 28        | 1.51%   |
| Foxconn / Hon Hai Bluetooth Device                  | 28        | 1.51%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 22        | 1.19%   |
| IMC Networks Wireless_Device                        | 21        | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 16        | 0.87%   |
| Intel Bluetooth Device                              | 16        | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                    | 16        | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.81%   |
| Intel AX210 Bluetooth                               | 14        | 0.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 14        | 0.76%   |
| Broadcom BCM2045 Bluetooth                          | 14        | 0.76%   |
| Qualcomm Atheros Bluetooth                          | 13        | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 12        | 0.65%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 12        | 0.65%   |
| Lite-On Wireless_Device                             | 11        | 0.59%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 11        | 0.59%   |
| Realtek RTL8821A Bluetooth                          | 10        | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 10        | 0.54%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 10        | 0.54%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.54%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 9         | 0.49%   |
| Foxconn International BCM43142A0 Bluetooth module   | 9         | 0.49%   |
| Broadcom BCM20702A0                                 | 9         | 0.49%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 9         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2456      | 51.59%  |
| AMD                              | 1121      | 23.55%  |
| Nvidia                           | 848       | 17.81%  |
| C-Media Electronics              | 75        | 1.58%   |
| Creative Labs                    | 50        | 1.05%   |
| Logitech                         | 23        | 0.48%   |
| VIA Technologies                 | 14        | 0.29%   |
| JMTek                            | 13        | 0.27%   |
| Plantronics                      | 11        | 0.23%   |
| Generalplus Technology           | 11        | 0.23%   |
| ASUSTek Computer                 | 11        | 0.23%   |
| Silicon Integrated Systems [SiS] | 10        | 0.21%   |
| Texas Instruments                | 9         | 0.19%   |
| Realtek Semiconductor            | 8         | 0.17%   |
| SteelSeries ApS                  | 6         | 0.13%   |
| DSEA A/S                         | 6         | 0.13%   |
| Lenovo                           | 5         | 0.11%   |
| Razer USA                        | 4         | 0.08%   |
| Kingston Technology              | 4         | 0.08%   |
| GN Netcom                        | 4         | 0.08%   |
| Yamaha                           | 3         | 0.06%   |
| ULi Electronics                  | 3         | 0.06%   |
| SAVITECH                         | 3         | 0.06%   |
| Micro Star International         | 3         | 0.06%   |
| M-Audio                          | 3         | 0.06%   |
| KTMicro                          | 3         | 0.06%   |
| Hewlett-Packard                  | 3         | 0.06%   |
| Ensoniq                          | 3         | 0.06%   |
| Creative Technology              | 3         | 0.06%   |
| Tenx Technology                  | 2         | 0.04%   |
| Sony                             | 2         | 0.04%   |
| Shenzhen Rapoo Technology        | 2         | 0.04%   |
| Microsoft                        | 2         | 0.04%   |
| Focusrite-Novation               | 2         | 0.04%   |
| Cirrus Logic                     | 2         | 0.04%   |
| BEHRINGER International          | 2         | 0.04%   |
| ZOOM                             | 1         | 0.02%   |
| Vitana                           | 1         | 0.02%   |
| USB MICROPHONE                   | 1         | 0.02%   |
| Trust                            | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 296       | 5.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 277       | 4.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 274       | 4.93%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 244       | 4.39%   |
| AMD Ryzen HD Audio Controller                                                                     | 232       | 4.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 218       | 3.92%   |
| AMD FCH Azalia Controller                                                                         | 178       | 3.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 132       | 2.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 122       | 2.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 115       | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 107       | 1.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 103       | 1.85%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 97        | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 93        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 90        | 1.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 83        | 1.49%   |
| Nvidia MCP61 High Definition Audio                                                                | 76        | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 73        | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 73        | 1.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 67        | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 66        | 1.19%   |
| Nvidia High Definition Audio Controller                                                           | 64        | 1.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 62        | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 60        | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 59        | 1.06%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 58        | 1.04%   |
| Intel 200 Series PCH HD Audio                                                                     | 54        | 0.97%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 51        | 0.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 51        | 0.92%   |
| AMD Trinity HDMI Audio Controller                                                                 | 51        | 0.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 51        | 0.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 49        | 0.88%   |
| Intel 8 Series HD Audio Controller                                                                | 49        | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 48        | 0.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 45        | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 45        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 44        | 0.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 44        | 0.79%   |
| Intel Broadwell-U Audio Controller                                                                | 43        | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 42        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 659       | 22.27%  |
| Samsung Electronics | 524       | 17.71%  |
| SK hynix            | 409       | 13.82%  |
| Kingston            | 382       | 12.91%  |
| Micron Technology   | 212       | 7.16%   |
| Goodram             | 68        | 2.3%    |
| Crucial             | 68        | 2.3%    |
| Ramaxel Technology  | 66        | 2.23%   |
| Team                | 61        | 2.06%   |
| Elpida              | 60        | 2.03%   |
| Nanya Technology    | 41        | 1.39%   |
| A-DATA Technology   | 41        | 1.39%   |
| G.Skill             | 39        | 1.32%   |
| Corsair             | 32        | 1.08%   |
| AMD                 | 32        | 1.08%   |
| Transcend           | 30        | 1.01%   |
| Silicon Power       | 21        | 0.71%   |
| Patriot             | 19        | 0.64%   |
| Exceleram           | 18        | 0.61%   |
| Apacer              | 17        | 0.57%   |
| Unknown (ABCD)      | 15        | 0.51%   |
| Unknown             | 15        | 0.51%   |
| ASint Technology    | 9         | 0.3%    |
| SHARETRONIC         | 8         | 0.27%   |
| Kllisre             | 8         | 0.27%   |
| GeIL                | 8         | 0.27%   |
| 48spaces            | 8         | 0.27%   |
| Qimonda             | 6         | 0.2%    |
| Goldkey             | 5         | 0.17%   |
| Unifosa             | 4         | 0.14%   |
| TwinMOS             | 4         | 0.14%   |
| Toshiba             | 4         | 0.14%   |
| Kingmax             | 4         | 0.14%   |
| Wilk                | 3         | 0.1%    |
| TakeMS              | 3         | 0.1%    |
| Swissbit            | 3         | 0.1%    |
| Qumo                | 3         | 0.1%    |
| KingSpec            | 3         | 0.1%    |
| Foxline             | 3         | 0.1%    |
| PNY                 | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 36        | 1.1%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 26        | 0.79%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 23        | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.67%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 21        | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 21        | 0.64%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 20        | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.58%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 19        | 0.58%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 18        | 0.55%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 17        | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.52%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 16        | 0.49%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.49%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.46%   |
| Unknown                                                          | 15        | 0.46%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                           | 14        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 14        | 0.43%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 14        | 0.43%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 14        | 0.43%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 14        | 0.43%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.43%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 13        | 0.4%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.4%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 13        | 0.4%    |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 12        | 0.37%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                      | 12        | 0.37%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 12        | 0.37%   |
| Unknown RAM Module 1024MB DIMM                                   | 12        | 0.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.37%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 12        | 0.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 12        | 0.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 12        | 0.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.37%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 12        | 0.37%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 12        | 0.37%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 11        | 0.34%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 11        | 0.34%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.34%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 11        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 976       | 38.11%  |
| DDR4    | 758       | 29.6%   |
| DDR2    | 271       | 10.58%  |
| Unknown | 222       | 8.67%   |
| SDRAM   | 160       | 6.25%   |
| LPDDR4  | 59        | 2.3%    |
| DDR     | 50        | 1.95%   |
| LPDDR3  | 19        | 0.74%   |
| DDR5    | 19        | 0.74%   |
| DRAM    | 16        | 0.62%   |
| LPDDR5  | 9         | 0.35%   |
| EEPROM  | 2         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1349      | 54.13%  |
| DIMM         | 1065      | 42.74%  |
| Row Of Chips | 65        | 2.61%   |
| Chip         | 10        | 0.4%    |
| RIMM         | 1         | 0.04%   |
| FB-DIMM      | 1         | 0.04%   |
| Unknown      | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 852       | 29.19%  |
| 8192  | 765       | 26.21%  |
| 2048  | 686       | 23.5%   |
| 1024  | 265       | 9.08%   |
| 16384 | 226       | 7.74%   |
| 32768 | 59        | 2.02%   |
| 512   | 53        | 1.82%   |
| 256   | 11        | 0.38%   |
| 1     | 2         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 622       | 22.13%  |
| 1333    | 273       | 9.71%   |
| 2667    | 255       | 9.07%   |
| 3200    | 229       | 8.15%   |
| Unknown | 173       | 6.15%   |
| 2400    | 163       | 5.8%    |
| 800     | 144       | 5.12%   |
| 667     | 144       | 5.12%   |
| 1334    | 125       | 4.45%   |
| 2133    | 117       | 4.16%   |
| 400     | 45        | 1.6%    |
| 1867    | 38        | 1.35%   |
| 1067    | 38        | 1.35%   |
| 4199    | 37        | 1.32%   |
| 1866    | 32        | 1.14%   |
| 1066    | 31        | 1.1%    |
| 533     | 27        | 0.96%   |
| 333     | 25        | 0.89%   |
| 3600    | 22        | 0.78%   |
| 3266    | 18        | 0.64%   |
| 3733    | 17        | 0.6%    |
| 2048    | 17        | 0.6%    |
| 3400    | 14        | 0.5%    |
| 4267    | 13        | 0.46%   |
| 3333    | 13        | 0.46%   |
| 4266    | 11        | 0.39%   |
| 8400    | 10        | 0.36%   |
| 5600    | 10        | 0.36%   |
| 3466    | 10        | 0.36%   |
| 3800    | 9         | 0.32%   |
| 3000    | 9         | 0.32%   |
| 1639    | 8         | 0.28%   |
| 4800    | 7         | 0.25%   |
| 975     | 7         | 0.25%   |
| 266     | 7         | 0.25%   |
| 6400    | 6         | 0.21%   |
| 4000    | 6         | 0.21%   |
| 3066    | 6         | 0.21%   |
| 2933    | 6         | 0.21%   |
| 2666    | 6         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Canon                 | 37        | 35.58%  |
| Samsung Electronics   | 27        | 25.96%  |
| Hewlett-Packard       | 15        | 14.42%  |
| Seiko Epson           | 7         | 6.73%   |
| Pantum                | 4         | 3.85%   |
| Brother Industries    | 3         | 2.88%   |
| Xerox                 | 2         | 1.92%   |
| WinChipHead           | 2         | 1.92%   |
| Prolific Technology   | 2         | 1.92%   |
| Zebra                 | 1         | 0.96%   |
| Xiaomi                | 1         | 0.96%   |
| Oki Data              | 1         | 0.96%   |
| Lexmark International | 1         | 0.96%   |
| Dell                  | 1         | 0.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Samsung SCX-4200 series                       | 6         | 5.77%   |
| Canon MF4410                                  | 4         | 3.85%   |
| Samsung SCX-4100 Scanner                      | 3         | 2.88%   |
| Samsung ML-1520 Laser Printer                 | 3         | 2.88%   |
| Samsung M2070 Series                          | 3         | 2.88%   |
| Canon MP160                                   | 3         | 2.88%   |
| WinChipHead CH34x printer adapter cable       | 2         | 1.92%   |
| Seiko Epson L210 Series                       | 2         | 1.92%   |
| Samsung Xerox Phaser 3117 Laser Printer       | 2         | 1.92%   |
| Samsung ML-1710 Printer                       | 2         | 1.92%   |
| Samsung M2020 Series                          | 2         | 1.92%   |
| Prolific PL2305 Parallel Port                 | 2         | 1.92%   |
| HP LaserJet P1102                             | 2         | 1.92%   |
| HP LaserJet P1005                             | 2         | 1.92%   |
| HP LaserJet 1020                              | 2         | 1.92%   |
| HP LaserJet 1018                              | 2         | 1.92%   |
| HP LaserJet 1012                              | 2         | 1.92%   |
| Canon PIXMA MP280                             | 2         | 1.92%   |
| Canon MF4320-4350                             | 2         | 1.92%   |
| Canon MF4010 series                           | 2         | 1.92%   |
| Canon MF3010                                  | 2         | 1.92%   |
| Canon LBP3010/LBP3018/LBP3050                 | 2         | 1.92%   |
| Canon LBP2900                                 | 2         | 1.92%   |
| Canon LaserShot LBP-1120 Printer              | 2         | 1.92%   |
| Canon iP2700 series                           | 2         | 1.92%   |
| Canon CAPT USB Device                         | 2         | 1.92%   |
| Zebra ZTC S4M-200dpi ZPL                      | 1         | 0.96%   |
| Xiaomi MiMouse 2                              | 1         | 0.96%   |
| Xerox WorkCenter M15                          | 1         | 0.96%   |
| Xerox Printing Support                        | 1         | 0.96%   |
| Seiko Epson XP-240 Series                     | 1         | 0.96%   |
| Seiko Epson Printer                           | 1         | 0.96%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 0.96%   |
| Seiko Epson L380 Series                       | 1         | 0.96%   |
| Seiko Epson L3050 Series                      | 1         | 0.96%   |
| Samsung Xerox Phaser 3150                     | 1         | 0.96%   |
| Samsung SCX-4216F Scanner                     | 1         | 0.96%   |
| Samsung Phaser 3121                           | 1         | 0.96%   |
| Samsung ML-1660 Series                        | 1         | 0.96%   |
| Samsung Laser Printer                         | 1         | 0.96%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 7         | 29.17%  |
| Seiko Epson        | 6         | 25%     |
| Mustek Systems     | 5         | 20.83%  |
| Ultima Electronics | 3         | 12.5%   |
| Hewlett-Packard    | 3         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 3         | 12.5%   |
| Canon CanoScan LIDE 25                                                                | 3         | 12.5%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2         | 8.33%   |
| Mustek Systems SNAPSCAN e22                                                           | 2         | 8.33%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2         | 8.33%   |
| Seiko Epson Scanner                                                                   | 1         | 4.17%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 1         | 4.17%   |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 4.17%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1         | 4.17%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 1         | 4.17%   |
| HP ScanJet 4400c                                                                      | 1         | 4.17%   |
| HP ScanJet 3800c                                                                      | 1         | 4.17%   |
| HP ScanJet 2400c                                                                      | 1         | 4.17%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1         | 4.17%   |
| Canon CanoScan LiDE 60                                                                | 1         | 4.17%   |
| Canon CanoScan LiDE 120                                                               | 1         | 4.17%   |
| Canon CanoScan LiDE 110                                                               | 1         | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 465       | 20.96%  |
| IMC Networks                           | 265       | 11.94%  |
| Microdia                               | 154       | 6.94%   |
| Bison Electronics                      | 144       | 6.49%   |
| Logitech                               | 140       | 6.31%   |
| Realtek Semiconductor                  | 130       | 5.86%   |
| Quanta                                 | 114       | 5.14%   |
| Sunplus Innovation Technology          | 102       | 4.6%    |
| Z-Star Microelectronics                | 94        | 4.24%   |
| Cheng Uei Precision Industry (Foxlink) | 88        | 3.97%   |
| Suyin                                  | 87        | 3.92%   |
| Syntek                                 | 58        | 2.61%   |
| Silicon Motion                         | 45        | 2.03%   |
| Alcor Micro                            | 39        | 1.76%   |
| Lite-On Technology                     | 34        | 1.53%   |
| Apple                                  | 33        | 1.49%   |
| Luxvisions Innotech Limited            | 23        | 1.04%   |
| Aveo Technology                        | 21        | 0.95%   |
| KYE Systems (Mouse Systems)            | 16        | 0.72%   |
| Sonix Technology                       | 11        | 0.5%    |
| DigiTech                               | 11        | 0.5%    |
| Pixart Imaging                         | 10        | 0.45%   |
| Microsoft                              | 10        | 0.45%   |
| GEMBIRD                                | 9         | 0.41%   |
| Acer                                   | 9         | 0.41%   |
| Ricoh                                  | 8         | 0.36%   |
| Primax Electronics                     | 7         | 0.32%   |
| Cubeternet                             | 7         | 0.32%   |
| Arkmicro Technologies                  | 7         | 0.32%   |
| ALi                                    | 7         | 0.32%   |
| Samsung Electronics                    | 6         | 0.27%   |
| Hewlett-Packard                        | 5         | 0.23%   |
| Lenovo                                 | 4         | 0.18%   |
| Generalplus Technology                 | 4         | 0.18%   |
| SunplusIT                              | 3         | 0.14%   |
| Sunplus Technology                     | 3         | 0.14%   |
| icSpring                               | 3         | 0.14%   |
| Google                                 | 3         | 0.14%   |
| Unknown                                | 2         | 0.09%   |
| ShineTech                              | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                         | 72        | 3.23%   |
| Chicony Integrated Camera                                                  | 60        | 2.69%   |
| Logitech Webcam C270                                                       | 58        | 2.6%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 45        | 2.02%   |
| Z-Star Venus USB2.0 Camera                                                 | 39        | 1.75%   |
| Chicony Lenovo EasyCamera                                                  | 38        | 1.7%    |
| Bison Lenovo Integrated Webcam                                             | 38        | 1.7%    |
| Chicony HD Webcam                                                          | 37        | 1.66%   |
| IMC Networks Integrated Camera                                             | 30        | 1.35%   |
| Microdia Integrated_Webcam_HD                                              | 29        | 1.3%    |
| Sunplus Integrated_Webcam_HD                                               | 28        | 1.26%   |
| Quanta HD User Facing                                                      | 27        | 1.21%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 27        | 1.21%   |
| Realtek Integrated_Webcam_HD                                               | 26        | 1.17%   |
| Syntek Lenovo EasyCamera                                                   | 25        | 1.12%   |
| Bison Lenovo EasyCamera                                                    | 25        | 1.12%   |
| Chicony HP HD Camera                                                       | 23        | 1.03%   |
| Logitech Webcam C310                                                       | 22        | 0.99%   |
| Bison Integrated Camera                                                    | 21        | 0.94%   |
| Quanta HP TrueVision HD Camera                                             | 20        | 0.9%    |
| Quanta HD Webcam                                                           | 19        | 0.85%   |
| Microdia Camera                                                            | 18        | 0.81%   |
| Chicony HP Webcam                                                          | 18        | 0.81%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 18        | 0.81%   |
| Microdia Sonix USB 2.0 Camera                                              | 17        | 0.76%   |
| Syntek Integrated Camera                                                   | 16        | 0.72%   |
| Sunplus HD WebCam                                                          | 16        | 0.72%   |
| Logitech Webcam C170                                                       | 16        | 0.72%   |
| IMC Networks Lenovo EasyCamera                                             | 16        | 0.72%   |
| Chicony HP Wide Vision HD Camera                                           | 16        | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 15        | 0.67%   |
| Bison EasyCamera                                                           | 15        | 0.67%   |
| Z-Star A4 TECH USB 2.0 Camera J                                            | 14        | 0.63%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 14        | 0.63%   |
| Sunplus Asus Webcam                                                        | 14        | 0.63%   |
| Quanta VGA WebCam                                                          | 14        | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 14        | 0.63%   |
| IMC Networks UVC VGA Webcam                                                | 14        | 0.63%   |
| Chicony HP Truevision HD                                                   | 14        | 0.63%   |
| Chicony HD User Facing                                                     | 14        | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 105       | 33.65%  |
| Synaptics                          | 67        | 21.47%  |
| Upek                               | 30        | 9.62%   |
| LighTuning Technology              | 28        | 8.97%   |
| Shenzhen Goodix Technology         | 26        | 8.33%   |
| Elan Microelectronics              | 26        | 8.33%   |
| AuthenTec                          | 15        | 4.81%   |
| STMicroelectronics                 | 7         | 2.24%   |
| HOLTEK                             | 4         | 1.28%   |
| Samsung Electronics                | 2         | 0.64%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.64%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 37        | 11.86%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 9.62%   |
| Elan ELAN:Fingerprint                                                      | 23        | 7.37%   |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 5.77%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 17        | 5.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 4.49%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 4.17%   |
| Synaptics Fingerprint reader [HP G6]                                       | 12        | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 3.21%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 3.21%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 2.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 2.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 2.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 2.24%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.24%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.24%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.92%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.92%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 1.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 1.92%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.6%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.6%    |
| AuthenTec AES1600                                                          | 5         | 1.6%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 1.28%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 1.28%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.28%   |
| HOLTEK FocalTech Fingerprint Device                                        | 4         | 1.28%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.96%   |
| Synaptics UWP WBDI                                                         | 3         | 0.96%   |
| LighTuning Fingerprint Reader                                              | 3         | 0.96%   |
| Elan ELAN:ARM-M4                                                           | 3         | 0.96%   |
| AuthenTec AES2810                                                          | 3         | 0.96%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.64%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.32%   |
| Validity Sensors VFS491                                                    | 1         | 0.32%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.32%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.32%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.32%   |
| Synaptics WBDI                                                             | 1         | 0.32%   |
| Synaptics  WBDI                                                            | 1         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 42        | 47.73%  |
| Alcor Micro               | 27        | 30.68%  |
| O2 Micro                  | 8         | 9.09%   |
| Upek                      | 3         | 3.41%   |
| Avtor                     | 3         | 3.41%   |
| Lenovo                    | 2         | 2.27%   |
| Gemalto (was Gemplus)     | 1         | 1.14%   |
| Aladdin Knowledge Systems | 1         | 1.14%   |
| Advanced Card Systems     | 1         | 1.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 30.34%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 17.98%  |
| Broadcom 5880                                                                | 15        | 16.85%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 7.87%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 5.62%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 3.37%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 3.37%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 3         | 3.37%   |
| Avtor SecureToken                                                            | 3         | 3.37%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.25%   |
| Broadcom 58200                                                               | 2         | 2.25%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.12%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.12%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.12%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2690      | 73.58%  |
| 1     | 794       | 21.72%  |
| 2     | 149       | 4.08%   |
| 3     | 13        | 0.36%   |
| 4     | 7         | 0.19%   |
| 7     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 376       | 33.54%  |
| Fingerprint reader       | 310       | 27.65%  |
| Net/wireless             | 115       | 10.26%  |
| Chipcard                 | 69        | 6.16%   |
| Multimedia controller    | 53        | 4.73%   |
| Bluetooth                | 49        | 4.37%   |
| Communication controller | 44        | 3.93%   |
| Camera                   | 20        | 1.78%   |
| Storage                  | 15        | 1.34%   |
| Unassigned class         | 14        | 1.25%   |
| Card reader              | 13        | 1.16%   |
| Sound                    | 12        | 1.07%   |
| Net/ethernet             | 9         | 0.8%    |
| Flash memory             | 7         | 0.62%   |
| Modem                    | 4         | 0.36%   |
| Storage/ide              | 3         | 0.27%   |
| Network                  | 3         | 0.27%   |
| Storage/raid             | 2         | 0.18%   |
| Storage/ata              | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |
| Dvb card                 | 1         | 0.09%   |

