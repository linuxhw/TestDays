Linux in Ukraine - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ukraine.

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

Total: 2967

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 5555               | [3c796c719e](https://linux-hardware.org/?probe=3c796c719e) | Dec 28, 2025 |
| MSI           | Cyborg 15 B13WEKG           | [6fc3b6c3ac](https://linux-hardware.org/?probe=6fc3b6c3ac) | Dec 26, 2025 |
| Gigabyte      | G5 MF                       | [ddb898d45b](https://linux-hardware.org/?probe=ddb898d45b) | Dec 25, 2025 |
| Samsung       | R55S                        | [fc6cd115ef](https://linux-hardware.org/?probe=fc6cd115ef) | Dec 23, 2025 |
| Dell          | Inspiron 3521               | [db687bea2b](https://linux-hardware.org/?probe=db687bea2b) | Dec 20, 2025 |
| MSI           | Cyborg 15 B13WEKG           | [a1f0013017](https://linux-hardware.org/?probe=a1f0013017) | Dec 17, 2025 |
| Samsung       | R55S                        | [07fe452be0](https://linux-hardware.org/?probe=07fe452be0) | Dec 16, 2025 |
| Acer          | Aspire A515-57G             | [88e6dfc294](https://linux-hardware.org/?probe=88e6dfc294) | Dec 16, 2025 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [d6851aa06f](https://linux-hardware.org/?probe=d6851aa06f) | Dec 12, 2025 |
| ASUSTek       | K52F                        | [92f40ae93e](https://linux-hardware.org/?probe=92f40ae93e) | Dec 07, 2025 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [ed70b6349b](https://linux-hardware.org/?probe=ed70b6349b) | Dec 03, 2025 |
| HP            | 635                         | [ac9c0ef664](https://linux-hardware.org/?probe=ac9c0ef664) | Nov 24, 2025 |
| Lenovo        | IdeaPad S400 Touch 20283    | [d2f868b9f1](https://linux-hardware.org/?probe=d2f868b9f1) | Nov 20, 2025 |
| Samsung       | R55S                        | [c704feaef1](https://linux-hardware.org/?probe=c704feaef1) | Nov 13, 2025 |
| HP            | Pavilion dv6                | [700910c8ae](https://linux-hardware.org/?probe=700910c8ae) | Nov 12, 2025 |
| HP            | Pavilion dv6                | [6f3ede3ea4](https://linux-hardware.org/?probe=6f3ede3ea4) | Nov 12, 2025 |
| Samsung       | R55S                        | [053366ef76](https://linux-hardware.org/?probe=053366ef76) | Nov 11, 2025 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [c050c80aac](https://linux-hardware.org/?probe=c050c80aac) | Nov 08, 2025 |
| HP            | Laptop 15-bs0xx             | [f49001d46a](https://linux-hardware.org/?probe=f49001d46a) | Nov 02, 2025 |
| Samsung       | R55S                        | [2d46b73b12](https://linux-hardware.org/?probe=2d46b73b12) | Nov 02, 2025 |
| Dell          | Vostro 5402                 | [1b853c807c](https://linux-hardware.org/?probe=1b853c807c) | Oct 26, 2025 |
| Acer          | Extensa 215-55              | [c169f1fbda](https://linux-hardware.org/?probe=c169f1fbda) | Oct 20, 2025 |
| Samsung       | R55S                        | [eb294069e5](https://linux-hardware.org/?probe=eb294069e5) | Oct 17, 2025 |
| Unknown       | Unknown                     | [74ba89ad9b](https://linux-hardware.org/?probe=74ba89ad9b) | Oct 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [e37d12c12c](https://linux-hardware.org/?probe=e37d12c12c) | Oct 15, 2025 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [de62bd3b5d](https://linux-hardware.org/?probe=de62bd3b5d) | Oct 14, 2025 |
| Lenovo        | V15 G4 AMN 82YU             | [c1e101f64f](https://linux-hardware.org/?probe=c1e101f64f) | Oct 07, 2025 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [8925d431c5](https://linux-hardware.org/?probe=8925d431c5) | Oct 06, 2025 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [a707e3d2fc](https://linux-hardware.org/?probe=a707e3d2fc) | Oct 06, 2025 |
| TECNO Mobi... | MEGABOOK K15S AMD           | [94c9143459](https://linux-hardware.org/?probe=94c9143459) | Sep 29, 2025 |
| Acer          | Aspire A315-59              | [2cac4e7f00](https://linux-hardware.org/?probe=2cac4e7f00) | Sep 29, 2025 |
| Dell          | G3 3779                     | [cdcece12c4](https://linux-hardware.org/?probe=cdcece12c4) | Sep 26, 2025 |
| InnJoo Tec... | Voom Excellence             | [b83a1a506a](https://linux-hardware.org/?probe=b83a1a506a) | Sep 17, 2025 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [b87add21ba](https://linux-hardware.org/?probe=b87add21ba) | Sep 05, 2025 |
| Lenovo        | G580 20150                  | [8e2d6381b6](https://linux-hardware.org/?probe=8e2d6381b6) | Sep 05, 2025 |
| Lenovo        | V15-ADA 82C7                | [4f2789d0dc](https://linux-hardware.org/?probe=4f2789d0dc) | Sep 04, 2025 |
| Acer          | Aspire A315-21              | [3118b09d3d](https://linux-hardware.org/?probe=3118b09d3d) | Sep 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop S560... | [3ac4d8a8c8](https://linux-hardware.org/?probe=3ac4d8a8c8) | Aug 31, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop S560... | [25c4fbb5cc](https://linux-hardware.org/?probe=25c4fbb5cc) | Aug 31, 2025 |
| Acer          | Aspire 7540                 | [d622492cf3](https://linux-hardware.org/?probe=d622492cf3) | Aug 30, 2025 |
| Samsung       | R55S                        | [b830e16ac7](https://linux-hardware.org/?probe=b830e16ac7) | Jul 28, 2025 |
| DEXP          | C15-ICW300                  | [648ed90371](https://linux-hardware.org/?probe=648ed90371) | Jul 28, 2025 |
| Valve         | Galileo                     | [4b596f486f](https://linux-hardware.org/?probe=4b596f486f) | Jul 21, 2025 |
| Dell          | Inspiron 3542               | [d4dde7e0da](https://linux-hardware.org/?probe=d4dde7e0da) | Jul 16, 2025 |
| DIGMA Pro     | Fortis M DN15R5-ADXW07      | [bf4579658c](https://linux-hardware.org/?probe=bf4579658c) | Jul 13, 2025 |
| Dell          | Latitude 5420 Rugged        | [fdb03d7ae1](https://linux-hardware.org/?probe=fdb03d7ae1) | Jul 08, 2025 |
| Fujitsu       | LIFEBOOK E734               | [a208fc1359](https://linux-hardware.org/?probe=a208fc1359) | Jul 02, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [6c89df7bde](https://linux-hardware.org/?probe=6c89df7bde) | Jun 28, 2025 |
| Lenovo        | G550 20023                  | [21532c1b80](https://linux-hardware.org/?probe=21532c1b80) | Jun 26, 2025 |
| ASUSTek       | X542UQ                      | [0a5f515c70](https://linux-hardware.org/?probe=0a5f515c70) | Jun 25, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [c501e355b8](https://linux-hardware.org/?probe=c501e355b8) | Jun 15, 2025 |
| Lenovo        | ThinkPad T420 4236PGG       | [8d6611f2f1](https://linux-hardware.org/?probe=8d6611f2f1) | Jun 14, 2025 |
| ASUSTek       | U31SD                       | [338c18b05a](https://linux-hardware.org/?probe=338c18b05a) | Jun 14, 2025 |
| Acer          | Aspire A515-54G             | [29b76a5fc1](https://linux-hardware.org/?probe=29b76a5fc1) | Jun 12, 2025 |
| Dell          | Vostro 15 3530              | [2b029a5ebf](https://linux-hardware.org/?probe=2b029a5ebf) | Jun 11, 2025 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [8a3a2e9fb7](https://linux-hardware.org/?probe=8a3a2e9fb7) | Jun 10, 2025 |
| Acer          | Aspire A515-45G             | [92df7af45a](https://linux-hardware.org/?probe=92df7af45a) | Jun 08, 2025 |
| Acer          | Aspire A515-45G             | [428c786207](https://linux-hardware.org/?probe=428c786207) | Jun 08, 2025 |
| Timi          | TM1801                      | [5b03537ba4](https://linux-hardware.org/?probe=5b03537ba4) | Jun 05, 2025 |
| ASUSTek       | GL553VE                     | [ee3bfac389](https://linux-hardware.org/?probe=ee3bfac389) | May 26, 2025 |
| Lenovo        | ThinkPad P52 20M9S1GQ01     | [94ddaca6cb](https://linux-hardware.org/?probe=94ddaca6cb) | May 24, 2025 |
| Acer          | Aspire A315-44P             | [a8a5f65950](https://linux-hardware.org/?probe=a8a5f65950) | May 16, 2025 |
| Unknown       | Unknown                     | [71d25628cd](https://linux-hardware.org/?probe=71d25628cd) | May 14, 2025 |
| Acer          | Aspire A515-56G             | [e6579208d9](https://linux-hardware.org/?probe=e6579208d9) | May 10, 2025 |
| Lenovo        | ThinkPad E14 20RA001LRT     | [64e4e79aa1](https://linux-hardware.org/?probe=64e4e79aa1) | May 09, 2025 |
| Lenovo        | ThinkPad E14 20RA001LRT     | [b6fbc293e2](https://linux-hardware.org/?probe=b6fbc293e2) | May 09, 2025 |
| HP            | ProBook 445 14 inch G9 N... | [2f716d5eba](https://linux-hardware.org/?probe=2f716d5eba) | May 08, 2025 |
| Acer          | Aspire A315-34              | [4df5e96514](https://linux-hardware.org/?probe=4df5e96514) | May 06, 2025 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [adbed8b743](https://linux-hardware.org/?probe=adbed8b743) | May 05, 2025 |
| HP            | Presario CQ57               | [7222346fd8](https://linux-hardware.org/?probe=7222346fd8) | May 02, 2025 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | [97bfa3cc68](https://linux-hardware.org/?probe=97bfa3cc68) | Apr 27, 2025 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b373b215c9](https://linux-hardware.org/?probe=b373b215c9) | Apr 27, 2025 |
| Apple         | MacBookPro3,1               | [1cb904b528](https://linux-hardware.org/?probe=1cb904b528) | Apr 22, 2025 |
| HP            | Laptop 14s-fq0xxx           | [bc494458a7](https://linux-hardware.org/?probe=bc494458a7) | Apr 19, 2025 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2a8a900faf](https://linux-hardware.org/?probe=2a8a900faf) | Apr 15, 2025 |
| Dell          | Inspiron 5720               | [2ff58e327f](https://linux-hardware.org/?probe=2ff58e327f) | Apr 13, 2025 |
| ASUSTek       | 1001PXD                     | [be3b13b24e](https://linux-hardware.org/?probe=be3b13b24e) | Apr 07, 2025 |
| HP            | ProBook 6550b               | [0c08b3c2f7](https://linux-hardware.org/?probe=0c08b3c2f7) | Apr 03, 2025 |
| HP            | ProBook 6550b               | [1cf614e73e](https://linux-hardware.org/?probe=1cf614e73e) | Apr 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3ed8ac80f4](https://linux-hardware.org/?probe=3ed8ac80f4) | Apr 01, 2025 |
| Aquarius      | NS483                       | [c180a9957f](https://linux-hardware.org/?probe=c180a9957f) | Mar 28, 2025 |
| HP            | EliteBook 820 G3            | [512c002085](https://linux-hardware.org/?probe=512c002085) | Mar 28, 2025 |
| Lenovo        | ThinkPad T490s 20NX003NR... | [ef0b2ee269](https://linux-hardware.org/?probe=ef0b2ee269) | Mar 26, 2025 |
| Apple         | MacBookPro3,1               | [8e73f70fea](https://linux-hardware.org/?probe=8e73f70fea) | Mar 24, 2025 |
| Apple         | MacBookPro3,1               | [8ef5e7b92d](https://linux-hardware.org/?probe=8ef5e7b92d) | Mar 24, 2025 |
| Dell          | Inspiron 5520               | [b3196ccf2e](https://linux-hardware.org/?probe=b3196ccf2e) | Mar 17, 2025 |
| Acer          | Nitro AN515-45              | [c7a5c8fc5b](https://linux-hardware.org/?probe=c7a5c8fc5b) | Mar 16, 2025 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [124ee5a8bd](https://linux-hardware.org/?probe=124ee5a8bd) | Mar 12, 2025 |
| Star Labs     | StarBook                    | [f0593d8f1b](https://linux-hardware.org/?probe=f0593d8f1b) | Mar 12, 2025 |
| Apple         | MacBookPro3,1               | [0646de1868](https://linux-hardware.org/?probe=0646de1868) | Mar 11, 2025 |
| Apple         | MacBookPro3,1               | [7a97f1d4e8](https://linux-hardware.org/?probe=7a97f1d4e8) | Mar 11, 2025 |
| InnJoo Tec... | Voom Excellence             | [0ce30f78eb](https://linux-hardware.org/?probe=0ce30f78eb) | Mar 11, 2025 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [fdc099da48](https://linux-hardware.org/?probe=fdc099da48) | Mar 08, 2025 |
| Lenovo        | ThinkPad X60 2510AE9        | [56f9e3d5e1](https://linux-hardware.org/?probe=56f9e3d5e1) | Mar 07, 2025 |
| Toshiba       | Satellite C70-B             | [461acbfbb2](https://linux-hardware.org/?probe=461acbfbb2) | Feb 28, 2025 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [ed3ad2a096](https://linux-hardware.org/?probe=ed3ad2a096) | Feb 26, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [890b2ea5cf](https://linux-hardware.org/?probe=890b2ea5cf) | Feb 19, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [8d88edb31b](https://linux-hardware.org/?probe=8d88edb31b) | Feb 14, 2025 |
| ICL           | RAYbook Si1406              | [39a34ddf55](https://linux-hardware.org/?probe=39a34ddf55) | Feb 09, 2025 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [2729224cea](https://linux-hardware.org/?probe=2729224cea) | Feb 09, 2025 |
| ASUSTek       | ASUS EXPERTBOOK P5405CSA    | [1caa4bc5cd](https://linux-hardware.org/?probe=1caa4bc5cd) | Feb 03, 2025 |
| Acer          | Aspire 5542                 | [a2eb622091](https://linux-hardware.org/?probe=a2eb622091) | Feb 02, 2025 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [d3f8c8605b](https://linux-hardware.org/?probe=d3f8c8605b) | Jan 25, 2025 |
| Acer          | Aspire A715-72G             | [d2bc3d68cc](https://linux-hardware.org/?probe=d2bc3d68cc) | Jan 22, 2025 |
| Adreamer      | PN1308P                     | [9e722ec5b9](https://linux-hardware.org/?probe=9e722ec5b9) | Jan 20, 2025 |
| Dell          | Inspiron 5767               | [ba0b75cb1a](https://linux-hardware.org/?probe=ba0b75cb1a) | Jan 18, 2025 |
| Dell          | Inspiron 5767               | [70b0a9aec2](https://linux-hardware.org/?probe=70b0a9aec2) | Jan 18, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [1061d101a9](https://linux-hardware.org/?probe=1061d101a9) | Jan 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [4ce71c370a](https://linux-hardware.org/?probe=4ce71c370a) | Jan 16, 2025 |
| Acer          | Predator PHN16-72           | [90c78ec2cc](https://linux-hardware.org/?probe=90c78ec2cc) | Jan 09, 2025 |
| Lenovo        | ThinkPad Edge E440 20C5A... | [bef55a717d](https://linux-hardware.org/?probe=bef55a717d) | Jan 07, 2025 |
| Lenovo        | V15 G2 IJL 82QY             | [cd9b055146](https://linux-hardware.org/?probe=cd9b055146) | Dec 31, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [8e64cf40ca](https://linux-hardware.org/?probe=8e64cf40ca) | Dec 30, 2024 |
| Samsung       | SR58P                       | [70e6a978b7](https://linux-hardware.org/?probe=70e6a978b7) | Dec 23, 2024 |
| TECNO Mobi... | MEGABOOK T15DA              | [eb2b432d23](https://linux-hardware.org/?probe=eb2b432d23) | Dec 22, 2024 |
| HP            | 250 G4                      | [0d0786ce85](https://linux-hardware.org/?probe=0d0786ce85) | Dec 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [f2663b158a](https://linux-hardware.org/?probe=f2663b158a) | Dec 09, 2024 |
| Lenovo        | G570 20079                  | [d7ca5ffb0b](https://linux-hardware.org/?probe=d7ca5ffb0b) | Dec 06, 2024 |
| Apple         | MacBookAir3,1               | [8517a48127](https://linux-hardware.org/?probe=8517a48127) | Dec 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [e2e36578a2](https://linux-hardware.org/?probe=e2e36578a2) | Nov 22, 2024 |
| Lenovo        | G500 20236                  | [7dcaf25e66](https://linux-hardware.org/?probe=7dcaf25e66) | Nov 17, 2024 |
| Timi          | A35S                        | [009b192f2b](https://linux-hardware.org/?probe=009b192f2b) | Nov 16, 2024 |
| Acer          | Aspire xxxx                 | [33a1540b7a](https://linux-hardware.org/?probe=33a1540b7a) | Nov 11, 2024 |
| HP            | ProBook 450 G5              | [022c2f84fc](https://linux-hardware.org/?probe=022c2f84fc) | Nov 10, 2024 |
| Acer          | Swift SF114-34              | [691b0eb5d2](https://linux-hardware.org/?probe=691b0eb5d2) | Nov 07, 2024 |
| Acer          | Aspire A515-57              | [9eb047fb07](https://linux-hardware.org/?probe=9eb047fb07) | Nov 03, 2024 |
| Google        | Pantheon                    | [41f0a72dc6](https://linux-hardware.org/?probe=41f0a72dc6) | Nov 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | [98eb489724](https://linux-hardware.org/?probe=98eb489724) | Oct 31, 2024 |
| Timi          | TM1707                      | [6f1f7e4e34](https://linux-hardware.org/?probe=6f1f7e4e34) | Oct 30, 2024 |
| ASUSTek       | U31SD                       | [fe2a70f7fa](https://linux-hardware.org/?probe=fe2a70f7fa) | Oct 29, 2024 |
| HP            | Pavilion g6                 | [3033d9b319](https://linux-hardware.org/?probe=3033d9b319) | Oct 28, 2024 |
| Samsung       | R40P/R41P                   | [7055d764e4](https://linux-hardware.org/?probe=7055d764e4) | Oct 28, 2024 |
| ASUSTek       | U31SD                       | [2c5c09f1df](https://linux-hardware.org/?probe=2c5c09f1df) | Oct 25, 2024 |
| Acer          | Aspire V5-551G              | [9193076b94](https://linux-hardware.org/?probe=9193076b94) | Oct 22, 2024 |
| Acer          | Aspire V5-551G              | [6f186ef3f1](https://linux-hardware.org/?probe=6f186ef3f1) | Oct 22, 2024 |
| ASUSTek       | K55VD                       | [55353ea5e1](https://linux-hardware.org/?probe=55353ea5e1) | Oct 21, 2024 |
| Razer         | Blade 16 - RZ09-0483        | [87977c5666](https://linux-hardware.org/?probe=87977c5666) | Oct 21, 2024 |
| Gigabyte      | G5 GE                       | [26c1aed963](https://linux-hardware.org/?probe=26c1aed963) | Oct 17, 2024 |
| HP            | Laptop 15s-eq2xxx           | [d0ac53c68a](https://linux-hardware.org/?probe=d0ac53c68a) | Oct 16, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [ab67f0f4c4](https://linux-hardware.org/?probe=ab67f0f4c4) | Oct 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8dfb3bab34](https://linux-hardware.org/?probe=8dfb3bab34) | Oct 07, 2024 |
| Lenovo        | G580 20150                  | [21162c92b4](https://linux-hardware.org/?probe=21162c92b4) | Oct 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [23f6034531](https://linux-hardware.org/?probe=23f6034531) | Oct 04, 2024 |
| Valve         | Galileo                     | [a8bc5582e6](https://linux-hardware.org/?probe=a8bc5582e6) | Oct 03, 2024 |
| HP            | Pavilion g6                 | [810492a8e1](https://linux-hardware.org/?probe=810492a8e1) | Sep 30, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [9dccdf1596](https://linux-hardware.org/?probe=9dccdf1596) | Sep 30, 2024 |
| Dell          | Inspiron 3542               | [1d55438162](https://linux-hardware.org/?probe=1d55438162) | Sep 29, 2024 |
| HP            | 655                         | [ce046ad965](https://linux-hardware.org/?probe=ce046ad965) | Sep 26, 2024 |
| Valve         | Galileo                     | [8ab5e110e2](https://linux-hardware.org/?probe=8ab5e110e2) | Sep 24, 2024 |
| Dell          | G3 3579                     | [1786c1ecdd](https://linux-hardware.org/?probe=1786c1ecdd) | Sep 15, 2024 |
| HP            | EliteBook 840 G1            | [f8dd4f91b9](https://linux-hardware.org/?probe=f8dd4f91b9) | Sep 12, 2024 |
| Valve         | Jupiter                     | [96d9e41b2c](https://linux-hardware.org/?probe=96d9e41b2c) | Sep 06, 2024 |
| ASUSTek       | ROG Strix G713PU_G713PU     | [0cf32a7c28](https://linux-hardware.org/?probe=0cf32a7c28) | Sep 03, 2024 |
| HP            | EliteBook 850 G1            | [c5f7728016](https://linux-hardware.org/?probe=c5f7728016) | Sep 01, 2024 |
| HP            | EliteBook 850 G1            | [ee85acc05d](https://linux-hardware.org/?probe=ee85acc05d) | Sep 01, 2024 |
| HP            | Laptop 15-da0xxx            | [19aa76bbf1](https://linux-hardware.org/?probe=19aa76bbf1) | Aug 30, 2024 |
| Gigabyte      | G5 GD                       | [2840fa5a43](https://linux-hardware.org/?probe=2840fa5a43) | Aug 27, 2024 |
| Dell          | Vostro 5370                 | [ab603bbc81](https://linux-hardware.org/?probe=ab603bbc81) | Aug 24, 2024 |
| Dell          | Vostro 5370                 | [233641b58a](https://linux-hardware.org/?probe=233641b58a) | Aug 24, 2024 |
| Dell          | Precision 7530              | [67e1c5e840](https://linux-hardware.org/?probe=67e1c5e840) | Aug 24, 2024 |
| Gigabyte      | AERO 16 XE4                 | [491d0f5415](https://linux-hardware.org/?probe=491d0f5415) | Aug 22, 2024 |
| Dell          | Precision 7530              | [6dbff427a7](https://linux-hardware.org/?probe=6dbff427a7) | Aug 21, 2024 |
| Dell          | Precision 7530              | [f24cdeec73](https://linux-hardware.org/?probe=f24cdeec73) | Aug 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [252054bbbb](https://linux-hardware.org/?probe=252054bbbb) | Aug 14, 2024 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [eaf1b08e39](https://linux-hardware.org/?probe=eaf1b08e39) | Aug 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [1647e0bf63](https://linux-hardware.org/?probe=1647e0bf63) | Aug 14, 2024 |
| Acer          | Aspire E1-530G              | [30fac12d0e](https://linux-hardware.org/?probe=30fac12d0e) | Aug 13, 2024 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [af25c599ca](https://linux-hardware.org/?probe=af25c599ca) | Aug 12, 2024 |
| Lenovo        | ThinkPad E595 20NF001HRT    | [ed43fa321d](https://linux-hardware.org/?probe=ed43fa321d) | Aug 11, 2024 |
| Unknown       | Apple MacBook Pro (13-in... | [47a5c4679c](https://linux-hardware.org/?probe=47a5c4679c) | Aug 08, 2024 |
| Lenovo        | S10-3                       | [64d128d74c](https://linux-hardware.org/?probe=64d128d74c) | Aug 04, 2024 |
| HP            | ProBook 450 G3              | [e0891897e9](https://linux-hardware.org/?probe=e0891897e9) | Aug 01, 2024 |
| Lenovo        | S10-3                       | [c25cc431f8](https://linux-hardware.org/?probe=c25cc431f8) | Aug 01, 2024 |
| HONOR         | BMH-WDX9                    | [34156676c7](https://linux-hardware.org/?probe=34156676c7) | Jul 28, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [6959309c2f](https://linux-hardware.org/?probe=6959309c2f) | Jul 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [efd2967461](https://linux-hardware.org/?probe=efd2967461) | Jul 26, 2024 |
| HP            | Laptop 17-by0xxx            | [29acbbfa9a](https://linux-hardware.org/?probe=29acbbfa9a) | Jul 25, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [926de0d0c1](https://linux-hardware.org/?probe=926de0d0c1) | Jul 22, 2024 |
| Dell          | Latitude E4310              | [134a985afc](https://linux-hardware.org/?probe=134a985afc) | Jul 21, 2024 |
| Acer          | Aspire A315-58              | [2a5f95f23f](https://linux-hardware.org/?probe=2a5f95f23f) | Jul 20, 2024 |
| Apple         | MacBookAir4,2               | [9644df5e86](https://linux-hardware.org/?probe=9644df5e86) | Jul 19, 2024 |
| Fujitsu       | LIFEBOOK E734               | [f0cc03e825](https://linux-hardware.org/?probe=f0cc03e825) | Jul 15, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [77fc74f4e0](https://linux-hardware.org/?probe=77fc74f4e0) | Jun 29, 2024 |
| Acer          | Aspire A515-58P             | [40becc9aaa](https://linux-hardware.org/?probe=40becc9aaa) | Jun 29, 2024 |
| Acer          | Nitro AN17-51               | [f208c4063a](https://linux-hardware.org/?probe=f208c4063a) | Jun 26, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [c054b11de9](https://linux-hardware.org/?probe=c054b11de9) | Jun 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [e66c347a99](https://linux-hardware.org/?probe=e66c347a99) | Jun 21, 2024 |
| Lenovo        | IdeaPad Z580                | [3c9898faa1](https://linux-hardware.org/?probe=3c9898faa1) | Jun 20, 2024 |
| Lenovo        | IdeaPad Z580                | [50ac519b75](https://linux-hardware.org/?probe=50ac519b75) | Jun 20, 2024 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3d565cd28e](https://linux-hardware.org/?probe=3d565cd28e) | Jun 18, 2024 |
| HP            | ProBook 450 G7              | [e984cb8d82](https://linux-hardware.org/?probe=e984cb8d82) | Jun 18, 2024 |
| Lenovo        | ThinkPad T490 20N2000LUK    | [d1053bfafb](https://linux-hardware.org/?probe=d1053bfafb) | Jun 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [12ee24bdf8](https://linux-hardware.org/?probe=12ee24bdf8) | Jun 14, 2024 |
| Acer          | Extensa 215-22              | [604d8cb84d](https://linux-hardware.org/?probe=604d8cb84d) | Jun 11, 2024 |
| HP            | OMEN by Laptop 15-dh1xxx    | [b50b6a8837](https://linux-hardware.org/?probe=b50b6a8837) | Jun 09, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [91bb1074d9](https://linux-hardware.org/?probe=91bb1074d9) | Jun 09, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [4892cf872e](https://linux-hardware.org/?probe=4892cf872e) | Jun 09, 2024 |
| Dell          | Studio 1537                 | [9c73780c05](https://linux-hardware.org/?probe=9c73780c05) | Jun 07, 2024 |
| Valve         | Galileo                     | [c1cd10e2c9](https://linux-hardware.org/?probe=c1cd10e2c9) | Jun 05, 2024 |
| THUNDEROBO... | 911S                        | [bcc5c0d77c](https://linux-hardware.org/?probe=bcc5c0d77c) | May 29, 2024 |
| Fujitsu       | LIFEBOOK E734               | [74c8e530ad](https://linux-hardware.org/?probe=74c8e530ad) | May 22, 2024 |
| Fujitsu       | LIFEBOOK E734               | [de96d1e8d8](https://linux-hardware.org/?probe=de96d1e8d8) | May 22, 2024 |
| HP            | ProBook 450 G5              | [611c9b917e](https://linux-hardware.org/?probe=611c9b917e) | May 16, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20YE0... | [2dbc872484](https://linux-hardware.org/?probe=2dbc872484) | May 14, 2024 |
| Valve         | Jupiter                     | [23799f6a79](https://linux-hardware.org/?probe=23799f6a79) | May 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [29989717a9](https://linux-hardware.org/?probe=29989717a9) | May 09, 2024 |
| Apple         | MacBookPro11,1              | [5d23c7ed6f](https://linux-hardware.org/?probe=5d23c7ed6f) | May 08, 2024 |
| Dell          | XPS 15 9530                 | [5aee2550ce](https://linux-hardware.org/?probe=5aee2550ce) | May 08, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [826e5c0fc6](https://linux-hardware.org/?probe=826e5c0fc6) | May 05, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [2cc53cfafd](https://linux-hardware.org/?probe=2cc53cfafd) | May 05, 2024 |
| Acer          | Aspire A315-42              | [bff5263ba8](https://linux-hardware.org/?probe=bff5263ba8) | Apr 07, 2024 |
| HP            | EliteBook 8440p             | [d4fbc831bb](https://linux-hardware.org/?probe=d4fbc831bb) | Apr 07, 2024 |
| HP            | Stream 11 Pro G5            | [60dbf47721](https://linux-hardware.org/?probe=60dbf47721) | Apr 06, 2024 |
| ASUSTek       | K54C                        | [d43311570d](https://linux-hardware.org/?probe=d43311570d) | Apr 01, 2024 |
| HONOR         | BOHK-WAX9X                  | [90a8f20c20](https://linux-hardware.org/?probe=90a8f20c20) | Mar 28, 2024 |
| Acer          | Aspire E3-112               | [bba28f3708](https://linux-hardware.org/?probe=bba28f3708) | Mar 27, 2024 |
| Apple         | MacBook4,1                  | [a66fe7ad17](https://linux-hardware.org/?probe=a66fe7ad17) | Mar 22, 2024 |
| Apple         | MacBook4,1                  | [82eace2b3c](https://linux-hardware.org/?probe=82eace2b3c) | Mar 22, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [153f16ac8d](https://linux-hardware.org/?probe=153f16ac8d) | Mar 18, 2024 |
| DEXP          | C15-ICW300                  | [9965e88dba](https://linux-hardware.org/?probe=9965e88dba) | Mar 11, 2024 |
| DEXP          | C15-ICW300                  | [8d8494680f](https://linux-hardware.org/?probe=8d8494680f) | Mar 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [15f6244fa0](https://linux-hardware.org/?probe=15f6244fa0) | Mar 11, 2024 |
| HONOR         | BOD-WXX9                    | [a4942d27af](https://linux-hardware.org/?probe=a4942d27af) | Mar 09, 2024 |
| Acer          | Aspire A315-34              | [de7da2949d](https://linux-hardware.org/?probe=de7da2949d) | Mar 03, 2024 |
| Valve         | Jupiter                     | [a3062daa4e](https://linux-hardware.org/?probe=a3062daa4e) | Mar 01, 2024 |
| HP            | Pavilion dv6                | [ccc6fb70da](https://linux-hardware.org/?probe=ccc6fb70da) | Feb 25, 2024 |
| Maibenben     | MaiBook M                   | [7f6b3c0f92](https://linux-hardware.org/?probe=7f6b3c0f92) | Feb 13, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [f4930d0549](https://linux-hardware.org/?probe=f4930d0549) | Feb 09, 2024 |
| Valve         | Jupiter                     | [f3af706ee0](https://linux-hardware.org/?probe=f3af706ee0) | Jan 29, 2024 |
| Acer          | TravelMate P259-MG          | [0192eb7c53](https://linux-hardware.org/?probe=0192eb7c53) | Jan 28, 2024 |
| Acer          | Aspire A717-71G             | [b7fb65f8f0](https://linux-hardware.org/?probe=b7fb65f8f0) | Jan 24, 2024 |
| Valve         | Jupiter                     | [07ee2b0014](https://linux-hardware.org/?probe=07ee2b0014) | Jan 12, 2024 |
| HP            | EliteBook 8440p             | [889462ebed](https://linux-hardware.org/?probe=889462ebed) | Jan 10, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | [0350f7e562](https://linux-hardware.org/?probe=0350f7e562) | Jan 05, 2024 |
| Chuwi         | HeroBook Pro                | [97c2ff9710](https://linux-hardware.org/?probe=97c2ff9710) | Jan 01, 2024 |
| HP            | ProBook 445 14 inch G9 N... | [d3e1c0dbdc](https://linux-hardware.org/?probe=d3e1c0dbdc) | Dec 25, 2023 |
| MSI           | EX610                       | [95fe9d0294](https://linux-hardware.org/?probe=95fe9d0294) | Dec 25, 2023 |
| Packard Be... | EasyNote TE11HC             | [2c88ade0b2](https://linux-hardware.org/?probe=2c88ade0b2) | Dec 23, 2023 |
| Acer          | Aspire E5-571G              | [c136ca6eff](https://linux-hardware.org/?probe=c136ca6eff) | Dec 11, 2023 |
| TECNO Mobi... | MEGABOOK T15DA              | [afe1407fd9](https://linux-hardware.org/?probe=afe1407fd9) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ac0fd4af39](https://linux-hardware.org/?probe=ac0fd4af39) | Dec 05, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [a8192548ea](https://linux-hardware.org/?probe=a8192548ea) | Dec 03, 2023 |
| MSI           | Vector GP66 12UGS           | [9598e79260](https://linux-hardware.org/?probe=9598e79260) | Dec 01, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [7d194a5396](https://linux-hardware.org/?probe=7d194a5396) | Dec 01, 2023 |
| HUAWEI        | RLEF-XX                     | [9b8fabda07](https://linux-hardware.org/?probe=9b8fabda07) | Nov 29, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [f5949df300](https://linux-hardware.org/?probe=f5949df300) | Nov 28, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [ee929504ae](https://linux-hardware.org/?probe=ee929504ae) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [83d5ded7d9](https://linux-hardware.org/?probe=83d5ded7d9) | Nov 27, 2023 |
| Acer          | Aspire A515-45G             | [d9f708d5f2](https://linux-hardware.org/?probe=d9f708d5f2) | Nov 26, 2023 |
| MSI           | Vector GP66 12UGS           | [0fd3c87878](https://linux-hardware.org/?probe=0fd3c87878) | Nov 24, 2023 |
| ASUSTek       | N750JV                      | [27e9669d13](https://linux-hardware.org/?probe=27e9669d13) | Nov 24, 2023 |
| Acer          | TravelMate P259-MG          | [9ab55a1799](https://linux-hardware.org/?probe=9ab55a1799) | Nov 23, 2023 |
| Acer          | TravelMate P259-MG          | [aea9b092e1](https://linux-hardware.org/?probe=aea9b092e1) | Nov 23, 2023 |
| Acer          | Aspire E1-532G              | [986077984e](https://linux-hardware.org/?probe=986077984e) | Nov 18, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [613acc55d8](https://linux-hardware.org/?probe=613acc55d8) | Nov 13, 2023 |
| Unknown       | Unknown                     | [66296a4edd](https://linux-hardware.org/?probe=66296a4edd) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [daab2f9dc6](https://linux-hardware.org/?probe=daab2f9dc6) | Nov 11, 2023 |
| HP            | ProBook 640 G1              | [63a4283226](https://linux-hardware.org/?probe=63a4283226) | Nov 10, 2023 |
| Dynabook      | PORTEGE X30L-K              | [161674ce4a](https://linux-hardware.org/?probe=161674ce4a) | Nov 10, 2023 |
| Acer          | TravelMate P259-MG          | [b9429814ad](https://linux-hardware.org/?probe=b9429814ad) | Nov 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ac8533d263](https://linux-hardware.org/?probe=ac8533d263) | Nov 06, 2023 |
| Lenovo        | IdeaPad 710S Plus-13ISK ... | [f143d09ba7](https://linux-hardware.org/?probe=f143d09ba7) | Nov 04, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [96bda876c8](https://linux-hardware.org/?probe=96bda876c8) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [0a990e1165](https://linux-hardware.org/?probe=0a990e1165) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [3d7ad8a1d6](https://linux-hardware.org/?probe=3d7ad8a1d6) | Oct 26, 2023 |
| Dell          | Latitude E6220              | [afc941b941](https://linux-hardware.org/?probe=afc941b941) | Oct 25, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [e0a819cb8d](https://linux-hardware.org/?probe=e0a819cb8d) | Oct 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [47186b8e71](https://linux-hardware.org/?probe=47186b8e71) | Oct 24, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [817e0c8438](https://linux-hardware.org/?probe=817e0c8438) | Oct 23, 2023 |
| Acer          | Aspire V3-571G              | [5e50c3624b](https://linux-hardware.org/?probe=5e50c3624b) | Oct 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fbf9250075](https://linux-hardware.org/?probe=fbf9250075) | Oct 15, 2023 |
| Acer          | TravelMate 5744Z            | [38f2a731a5](https://linux-hardware.org/?probe=38f2a731a5) | Oct 13, 2023 |
| Acer          | Aspire A515-43              | [2b5409e1b5](https://linux-hardware.org/?probe=2b5409e1b5) | Oct 11, 2023 |
| Acer          | Aspire A515-43              | [66b780f57f](https://linux-hardware.org/?probe=66b780f57f) | Oct 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [814f6c5c52](https://linux-hardware.org/?probe=814f6c5c52) | Oct 09, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [a9fb0ad7d5](https://linux-hardware.org/?probe=a9fb0ad7d5) | Oct 06, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [30bf4415dc](https://linux-hardware.org/?probe=30bf4415dc) | Sep 30, 2023 |
| Valve         | Jupiter                     | [937f10463d](https://linux-hardware.org/?probe=937f10463d) | Sep 29, 2023 |
| Lenovo        | ThinkPad T490s 20NX003NR... | [0a38f1e9a4](https://linux-hardware.org/?probe=0a38f1e9a4) | Sep 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [549941d843](https://linux-hardware.org/?probe=549941d843) | Sep 25, 2023 |
| Google        | Magpie                      | [3da6f69ed3](https://linux-hardware.org/?probe=3da6f69ed3) | Sep 24, 2023 |
| Lenovo        | G560 20042                  | [a8a67a12c7](https://linux-hardware.org/?probe=a8a67a12c7) | Sep 23, 2023 |
| ASUSTek       | X510UAR                     | [1253ebfcfb](https://linux-hardware.org/?probe=1253ebfcfb) | Sep 17, 2023 |
| HP            | Laptop 15-db0xxx            | [3cbd0bc118](https://linux-hardware.org/?probe=3cbd0bc118) | Sep 16, 2023 |
| Packard Be... | EasyNote TE11HC             | [7f6effbc07](https://linux-hardware.org/?probe=7f6effbc07) | Sep 16, 2023 |
| Packard Be... | EasyNote TE11HC             | [7b4955f7d2](https://linux-hardware.org/?probe=7b4955f7d2) | Sep 16, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [175e57d54f](https://linux-hardware.org/?probe=175e57d54f) | Sep 15, 2023 |
| Gateway       | NV55C                       | [1086491e2c](https://linux-hardware.org/?probe=1086491e2c) | Sep 12, 2023 |
| ASUSTek       | X555LN                      | [d5d9b73baa](https://linux-hardware.org/?probe=d5d9b73baa) | Sep 11, 2023 |
| ASUSTek       | X555LN                      | [3aef7779ec](https://linux-hardware.org/?probe=3aef7779ec) | Sep 11, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [bb0607322d](https://linux-hardware.org/?probe=bb0607322d) | Sep 09, 2023 |
| Lenovo        | V580c 20160                 | [87f8bad27d](https://linux-hardware.org/?probe=87f8bad27d) | Sep 07, 2023 |
| ASUSTek       | X541NC                      | [927ba04557](https://linux-hardware.org/?probe=927ba04557) | Sep 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ceade9f24f](https://linux-hardware.org/?probe=ceade9f24f) | Sep 04, 2023 |
| Acer          | Nitro AN515-52              | [45e892a632](https://linux-hardware.org/?probe=45e892a632) | Sep 03, 2023 |
| Lenovo        | IdeaPad Slim 5 16IAH8 83... | [2cfbf5b20c](https://linux-hardware.org/?probe=2cfbf5b20c) | Sep 02, 2023 |
| Dell          | Inspiron 5520               | [0aac344d78](https://linux-hardware.org/?probe=0aac344d78) | Sep 01, 2023 |
| Acer          | TravelMate 5744Z            | [6a875dbee6](https://linux-hardware.org/?probe=6a875dbee6) | Sep 01, 2023 |
| Samsung       | R518                        | [1869c33e8e](https://linux-hardware.org/?probe=1869c33e8e) | Aug 31, 2023 |
| ASUSTek       | N76VZ                       | [096dcfdc21](https://linux-hardware.org/?probe=096dcfdc21) | Aug 27, 2023 |
| Dell          | Inspiron 5520               | [5b99637f66](https://linux-hardware.org/?probe=5b99637f66) | Aug 25, 2023 |
| MSI           | GS65 Stealth Thin 8RE       | [b53212efce](https://linux-hardware.org/?probe=b53212efce) | Aug 24, 2023 |
| Lenovo        | ThinkPad E490 20N8001BUS    | [85d80ec89f](https://linux-hardware.org/?probe=85d80ec89f) | Aug 22, 2023 |
| HP            | ProBook 650 G1              | [b176d8959a](https://linux-hardware.org/?probe=b176d8959a) | Aug 08, 2023 |
| Acer          | TravelMate 5744Z            | [19297331fd](https://linux-hardware.org/?probe=19297331fd) | Aug 05, 2023 |
| Lenovo        | G580 20150                  | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Acer          | Aspire E5-576G              | [eac04b4464](https://linux-hardware.org/?probe=eac04b4464) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [7a6a20b8ed](https://linux-hardware.org/?probe=7a6a20b8ed) | Jul 23, 2023 |
| Google        | Lillipup                    | [7f7ba76942](https://linux-hardware.org/?probe=7f7ba76942) | Jul 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [1367b103ae](https://linux-hardware.org/?probe=1367b103ae) | Jul 09, 2023 |
| ASUSTek       | N55SL                       | [1223d8b536](https://linux-hardware.org/?probe=1223d8b536) | Jul 07, 2023 |
| HP            | Laptop 14s-fq0xxx           | [638a590e01](https://linux-hardware.org/?probe=638a590e01) | Jul 05, 2023 |
| Chuwi         | HeroBook Pro                | [d1abb5f348](https://linux-hardware.org/?probe=d1abb5f348) | Jul 02, 2023 |
| Chuwi         | HeroBook Pro                | [c0238ceb53](https://linux-hardware.org/?probe=c0238ceb53) | Jul 02, 2023 |
| Dell          | System XPS L321X            | [abf6b8b341](https://linux-hardware.org/?probe=abf6b8b341) | Jun 29, 2023 |
| MSI           | GE66 Dragonshield 10SF      | [42f6b46bb1](https://linux-hardware.org/?probe=42f6b46bb1) | Jun 28, 2023 |
| MSI           | GE66 Dragonshield 10SF      | [00fd5b9706](https://linux-hardware.org/?probe=00fd5b9706) | Jun 26, 2023 |
| Acer          | Aspire A515-56              | [0ee45fd3e8](https://linux-hardware.org/?probe=0ee45fd3e8) | Jun 26, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d7ca07df46](https://linux-hardware.org/?probe=d7ca07df46) | Jun 22, 2023 |
| Toshiba       | Satellite L45-B             | [85b5d49142](https://linux-hardware.org/?probe=85b5d49142) | Jun 13, 2023 |
| Samsung       | RV408/RV508                 | [4ec36cfa9e](https://linux-hardware.org/?probe=4ec36cfa9e) | Jun 13, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [fba7b6bdc0](https://linux-hardware.org/?probe=fba7b6bdc0) | Jun 12, 2023 |
| Valve         | Jupiter                     | [fab558feb4](https://linux-hardware.org/?probe=fab558feb4) | Jun 10, 2023 |
| Valve         | Jupiter                     | [06f5f2068f](https://linux-hardware.org/?probe=06f5f2068f) | Jun 09, 2023 |
| Acer          | Aspire V5-551G              | [7c55457a7e](https://linux-hardware.org/?probe=7c55457a7e) | Jun 06, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [7b5291c6f8](https://linux-hardware.org/?probe=7b5291c6f8) | Jun 02, 2023 |
| Acer          | TravelMate 5744Z            | [bde6d2f364](https://linux-hardware.org/?probe=bde6d2f364) | May 31, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| THUNDEROBO... | IGER F1                     | [d492356b33](https://linux-hardware.org/?probe=d492356b33) | May 25, 2023 |
| Dell          | Vostro 15-3568              | [d80a3cd0b7](https://linux-hardware.org/?probe=d80a3cd0b7) | May 17, 2023 |
| Dell          | Vostro 15-3568              | [b4a9463feb](https://linux-hardware.org/?probe=b4a9463feb) | May 17, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [d30d7d859b](https://linux-hardware.org/?probe=d30d7d859b) | May 11, 2023 |
| HUAWEI        | BOM-WXX9                    | [8f910a1997](https://linux-hardware.org/?probe=8f910a1997) | May 09, 2023 |
| Lenovo        | ThinkPad T470 20HES63400    | [6628ac6681](https://linux-hardware.org/?probe=6628ac6681) | May 03, 2023 |
| Apple         | MacBookAir3,2               | [e0f325b239](https://linux-hardware.org/?probe=e0f325b239) | May 01, 2023 |
| Lenovo        | G585 20137                  | [f0b4e5c5fd](https://linux-hardware.org/?probe=f0b4e5c5fd) | Apr 29, 2023 |
| Samsung       | R528/R728                   | [1e0b02f4c5](https://linux-hardware.org/?probe=1e0b02f4c5) | Apr 28, 2023 |
| HP            | Laptop 17-ak0xx             | [6eed1fda15](https://linux-hardware.org/?probe=6eed1fda15) | Apr 27, 2023 |
| Toshiba       | Satellite L45-B             | [6869e08d2d](https://linux-hardware.org/?probe=6869e08d2d) | Apr 18, 2023 |
| Dell          | Inspiron 5559               | [945c1a2fe3](https://linux-hardware.org/?probe=945c1a2fe3) | Apr 17, 2023 |
| Dell          | Inspiron 5559               | [a25bcc21e8](https://linux-hardware.org/?probe=a25bcc21e8) | Apr 17, 2023 |
| HP            | ProBook 450 G7              | [cccf1dadac](https://linux-hardware.org/?probe=cccf1dadac) | Apr 12, 2023 |
| HP            | 635                         | [416f1683f6](https://linux-hardware.org/?probe=416f1683f6) | Apr 12, 2023 |
| Timi          | TM1707                      | [0e015e68ec](https://linux-hardware.org/?probe=0e015e68ec) | Apr 12, 2023 |
| Timi          | TM1707                      | [b611ba24ed](https://linux-hardware.org/?probe=b611ba24ed) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | [d9f6e45e3e](https://linux-hardware.org/?probe=d9f6e45e3e) | Apr 05, 2023 |
| ASUSTek       | N53SV                       | [5b2c0ea506](https://linux-hardware.org/?probe=5b2c0ea506) | Apr 02, 2023 |
| Valve         | Jupiter                     | [1f2e4d7cd8](https://linux-hardware.org/?probe=1f2e4d7cd8) | Mar 26, 2023 |
| HP            | ProBook 5330m               | [6844efa448](https://linux-hardware.org/?probe=6844efa448) | Mar 24, 2023 |
| Fujitsu       | LIFEBOOK E734               | [0c4119f8b3](https://linux-hardware.org/?probe=0c4119f8b3) | Mar 20, 2023 |
| HONOR         | BOD-WXX9                    | [9bca2e7122](https://linux-hardware.org/?probe=9bca2e7122) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [613aec2276](https://linux-hardware.org/?probe=613aec2276) | Mar 17, 2023 |
| Fujitsu       | LIFEBOOK E734               | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| Acer          | Aspire M3-581TG             | [2f8939e9ed](https://linux-hardware.org/?probe=2f8939e9ed) | Mar 06, 2023 |
| Acer          | Swift SFX16-52G             | [fb45390054](https://linux-hardware.org/?probe=fb45390054) | Mar 05, 2023 |
| Acer          | Swift SFX16-52G             | [b86acec192](https://linux-hardware.org/?probe=b86acec192) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [b9677c823b](https://linux-hardware.org/?probe=b9677c823b) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [47f08e4094](https://linux-hardware.org/?probe=47f08e4094) | Mar 04, 2023 |
| Dell          | Vostro 3700                 | [ea14c47abb](https://linux-hardware.org/?probe=ea14c47abb) | Mar 04, 2023 |
| MSI           | GF63 Thin 10SC              | [29fae9ef99](https://linux-hardware.org/?probe=29fae9ef99) | Mar 03, 2023 |
| MSI           | GF63 Thin 10SC              | [36078cfcb3](https://linux-hardware.org/?probe=36078cfcb3) | Mar 03, 2023 |
| MSI           | GF63 Thin 10SC              | [3603c7c3e9](https://linux-hardware.org/?probe=3603c7c3e9) | Mar 03, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [e5b411431c](https://linux-hardware.org/?probe=e5b411431c) | Mar 02, 2023 |
| ASUSTek       | N550JK                      | [1a041d0aad](https://linux-hardware.org/?probe=1a041d0aad) | Mar 01, 2023 |
| HP            | ProBook 635 Aero G8 Note... | [93ee76f198](https://linux-hardware.org/?probe=93ee76f198) | Feb 28, 2023 |
| HP            | Laptop 15t-dy200            | [3ea4171270](https://linux-hardware.org/?probe=3ea4171270) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Sony          | VGN-Z21WRN_B                | [c1b765e164](https://linux-hardware.org/?probe=c1b765e164) | Feb 26, 2023 |
| Dell          | Latitude E5430 non-vPro     | [67e31f8e42](https://linux-hardware.org/?probe=67e31f8e42) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [2bb4e30118](https://linux-hardware.org/?probe=2bb4e30118) | Feb 25, 2023 |
| Acer          | AO725                       | [9c6719e733](https://linux-hardware.org/?probe=9c6719e733) | Feb 24, 2023 |
| Lenovo        | Flex 2-14 20404             | [49445991dc](https://linux-hardware.org/?probe=49445991dc) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0dba794459](https://linux-hardware.org/?probe=0dba794459) | Feb 22, 2023 |
| HUAWEI        | CREF-XX                     | [e523c006bf](https://linux-hardware.org/?probe=e523c006bf) | Feb 22, 2023 |
| Timi          | TM1707                      | [9bc429fbd6](https://linux-hardware.org/?probe=9bc429fbd6) | Feb 22, 2023 |
| Acer          | Nitro AN515-52              | [9989903f85](https://linux-hardware.org/?probe=9989903f85) | Feb 21, 2023 |
| Lenovo        | ThinkPad T460p 20FWS0A60... | [c059bdf126](https://linux-hardware.org/?probe=c059bdf126) | Feb 12, 2023 |
| Dell          | Inspiron 3576               | [a025641dfc](https://linux-hardware.org/?probe=a025641dfc) | Feb 09, 2023 |
| ASUSTek       | P552SJ                      | [314c83cb10](https://linux-hardware.org/?probe=314c83cb10) | Feb 06, 2023 |
| Dell          | Vostro 1015                 | [d93258a6f8](https://linux-hardware.org/?probe=d93258a6f8) | Feb 05, 2023 |
| Valve         | Jupiter                     | [f0309f442d](https://linux-hardware.org/?probe=f0309f442d) | Feb 03, 2023 |
| Dell          | Latitude E5410              | [22df8731a9](https://linux-hardware.org/?probe=22df8731a9) | Jan 26, 2023 |
| HP            | Laptop 15-db0xxx            | [a9dace6356](https://linux-hardware.org/?probe=a9dace6356) | Jan 24, 2023 |
| Lenovo        | G505s 20255                 | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [082d1b40bc](https://linux-hardware.org/?probe=082d1b40bc) | Jan 21, 2023 |
| HONOR         | NBR-WAX9                    | [ca0282295b](https://linux-hardware.org/?probe=ca0282295b) | Jan 20, 2023 |
| Dell          | Venue 11 Pro 7139           | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| Lenovo        | IdeaPad Z580                | [f51c90cadc](https://linux-hardware.org/?probe=f51c90cadc) | Jan 15, 2023 |
| Irbis         | NB264                       | [ed534a1d30](https://linux-hardware.org/?probe=ed534a1d30) | Jan 15, 2023 |
| Acer          | Swift SFX16-52G             | [c8b31b22f8](https://linux-hardware.org/?probe=c8b31b22f8) | Jan 14, 2023 |
| Dell          | Inspiron 1012               | [ae34ca229c](https://linux-hardware.org/?probe=ae34ca229c) | Jan 13, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [9ebcc90bcf](https://linux-hardware.org/?probe=9ebcc90bcf) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [322e6e6dbe](https://linux-hardware.org/?probe=322e6e6dbe) | Jan 10, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [f75fea559f](https://linux-hardware.org/?probe=f75fea559f) | Jan 08, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c721dc5ba1](https://linux-hardware.org/?probe=c721dc5ba1) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| Dell          | Vostro 15 3510              | [aaf276dad9](https://linux-hardware.org/?probe=aaf276dad9) | Jan 06, 2023 |
| Acer          | Swift SFX16-52G             | [7ff6038cf3](https://linux-hardware.org/?probe=7ff6038cf3) | Jan 04, 2023 |
| Dell          | Latitude 5420               | [b7315d38e1](https://linux-hardware.org/?probe=b7315d38e1) | Jan 04, 2023 |
| Acer          | Swift SFX16-52G             | [bd8403001c](https://linux-hardware.org/?probe=bd8403001c) | Jan 02, 2023 |
| Dell          | Latitude D620               | [5337d0b0f9](https://linux-hardware.org/?probe=5337d0b0f9) | Dec 31, 2022 |
| Dell          | Latitude D620               | [ea81d9f6a5](https://linux-hardware.org/?probe=ea81d9f6a5) | Dec 31, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [bc961748be](https://linux-hardware.org/?probe=bc961748be) | Dec 25, 2022 |
| Acer          | Aspire A315-53              | [e012bb5bc1](https://linux-hardware.org/?probe=e012bb5bc1) | Dec 25, 2022 |
| Dell          | Inspiron 7720               | [0a7621cb40](https://linux-hardware.org/?probe=0a7621cb40) | Dec 17, 2022 |
| Fujitsu       | LIFEBOOK E734               | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [50e8243e50](https://linux-hardware.org/?probe=50e8243e50) | Dec 11, 2022 |
| Acer          | Aspire A114-33              | [0bb6c29bb6](https://linux-hardware.org/?probe=0bb6c29bb6) | Dec 07, 2022 |
| HIPER Tech... | HTHLP-04R/i5-8279u          | [1ead815604](https://linux-hardware.org/?probe=1ead815604) | Dec 05, 2022 |
| Dell          | Latitude E7470              | [457187e169](https://linux-hardware.org/?probe=457187e169) | Dec 01, 2022 |
| Dell          | Latitude E7470              | [b24884fe44](https://linux-hardware.org/?probe=b24884fe44) | Dec 01, 2022 |
| Acer          | Aspire 5741G                | [0a336099ba](https://linux-hardware.org/?probe=0a336099ba) | Dec 01, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [8a99ec717f](https://linux-hardware.org/?probe=8a99ec717f) | Nov 29, 2022 |
| Lenovo        | B590 20208                  | [b1551151f5](https://linux-hardware.org/?probe=b1551151f5) | Nov 24, 2022 |
| Acer          | Aspire A515-57              | [374b408342](https://linux-hardware.org/?probe=374b408342) | Nov 22, 2022 |
| Samsung       | R528/R728                   | [ea586efd66](https://linux-hardware.org/?probe=ea586efd66) | Nov 19, 2022 |
| Chuwi         | HeroBook Air                | [9749e5705a](https://linux-hardware.org/?probe=9749e5705a) | Nov 13, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [c3612a66aa](https://linux-hardware.org/?probe=c3612a66aa) | Nov 10, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [40cce7a719](https://linux-hardware.org/?probe=40cce7a719) | Nov 09, 2022 |
| Dell          | Inspiron 7720               | [38d24e4b4a](https://linux-hardware.org/?probe=38d24e4b4a) | Nov 06, 2022 |
| MSI           | MS-1688                     | [21dad91aac](https://linux-hardware.org/?probe=21dad91aac) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [cb2a07da11](https://linux-hardware.org/?probe=cb2a07da11) | Oct 30, 2022 |
| ASUSTek       | X501A1                      | [037e1402b1](https://linux-hardware.org/?probe=037e1402b1) | Oct 30, 2022 |
| Dell          | Inspiron 7720               | [f1478df888](https://linux-hardware.org/?probe=f1478df888) | Oct 30, 2022 |
| Acer          | Enduro EUN314-51W           | [2655b43e2b](https://linux-hardware.org/?probe=2655b43e2b) | Oct 25, 2022 |
| Acer          | Extensa 5630                | [bdc63e9670](https://linux-hardware.org/?probe=bdc63e9670) | Oct 25, 2022 |
| Timi          | RedmiBook Pro 14S           | [f81e674faf](https://linux-hardware.org/?probe=f81e674faf) | Oct 21, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [2dd0b46420](https://linux-hardware.org/?probe=2dd0b46420) | Oct 16, 2022 |
| ASUSTek       | K53TA                       | [8759f9f39c](https://linux-hardware.org/?probe=8759f9f39c) | Oct 15, 2022 |
| ASUSTek       | K53TA                       | [dd95142fda](https://linux-hardware.org/?probe=dd95142fda) | Oct 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [7af879de72](https://linux-hardware.org/?probe=7af879de72) | Oct 13, 2022 |
| HP            | Laptop 15-db0xxx            | [16bb04d1db](https://linux-hardware.org/?probe=16bb04d1db) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [52c4e232f3](https://linux-hardware.org/?probe=52c4e232f3) | Oct 10, 2022 |
| HONOR         | BOD-WXX9                    | [26c4b5f06a](https://linux-hardware.org/?probe=26c4b5f06a) | Oct 06, 2022 |
| Apple         | MacBookPro9,2               | [bdc21c1bad](https://linux-hardware.org/?probe=bdc21c1bad) | Oct 04, 2022 |
| Apple         | MacBookPro9,2               | [50e50f0533](https://linux-hardware.org/?probe=50e50f0533) | Oct 04, 2022 |
| Sony          | VPCEB1M1R                   | [343feefe62](https://linux-hardware.org/?probe=343feefe62) | Oct 02, 2022 |
| Acer          | Aspire V3-571G              | [bfd8dc3c18](https://linux-hardware.org/?probe=bfd8dc3c18) | Oct 02, 2022 |
| Acer          | Enduro EN314-51W            | [46782cf8f5](https://linux-hardware.org/?probe=46782cf8f5) | Oct 01, 2022 |
| Dell          | Latitude E7240              | [75501a47b5](https://linux-hardware.org/?probe=75501a47b5) | Sep 24, 2022 |
| HP            | ENVY Notebook               | [1eef25f6d8](https://linux-hardware.org/?probe=1eef25f6d8) | Sep 22, 2022 |
| HP            | ENVY Notebook               | [b95a98e133](https://linux-hardware.org/?probe=b95a98e133) | Sep 22, 2022 |
| Acer          | Aspire A315-23              | [dd730980b1](https://linux-hardware.org/?probe=dd730980b1) | Sep 20, 2022 |
| HP            | Pavilion g6                 | [dfd4d1f4e2](https://linux-hardware.org/?probe=dfd4d1f4e2) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [d9742b9445](https://linux-hardware.org/?probe=d9742b9445) | Sep 19, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [6c5e991427](https://linux-hardware.org/?probe=6c5e991427) | Sep 18, 2022 |
| Lenovo        | G580 20150                  | [fe325d1046](https://linux-hardware.org/?probe=fe325d1046) | Sep 18, 2022 |
| HP            | Pavilion dv6                | [9c9c531c6b](https://linux-hardware.org/?probe=9c9c531c6b) | Sep 15, 2022 |
| Timi          | RedmiBook Pro 14S           | [1662163cb8](https://linux-hardware.org/?probe=1662163cb8) | Sep 15, 2022 |
| Acer          | TravelMate 5744Z            | [f9846e0165](https://linux-hardware.org/?probe=f9846e0165) | Sep 13, 2022 |
| Lenovo        | Unknown                     | [b5842ca017](https://linux-hardware.org/?probe=b5842ca017) | Sep 10, 2022 |
| Timi          | TM1703                      | [5c30ece6ff](https://linux-hardware.org/?probe=5c30ece6ff) | Sep 08, 2022 |
| Timi          | TM1703                      | [fb7386017f](https://linux-hardware.org/?probe=fb7386017f) | Sep 06, 2022 |
| Lenovo        | G580 20150                  | [8dba025148](https://linux-hardware.org/?probe=8dba025148) | Sep 05, 2022 |
| Dell          | Latitude 5591               | [b860997149](https://linux-hardware.org/?probe=b860997149) | Sep 01, 2022 |
| Timi          | A35                         | [df50ea1876](https://linux-hardware.org/?probe=df50ea1876) | Aug 29, 2022 |
| Acer          | Aspire 5570Z                | [38fe74cbe3](https://linux-hardware.org/?probe=38fe74cbe3) | Aug 26, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [ba23396754](https://linux-hardware.org/?probe=ba23396754) | Aug 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [b8859a4f21](https://linux-hardware.org/?probe=b8859a4f21) | Aug 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [ce734a061a](https://linux-hardware.org/?probe=ce734a061a) | Aug 23, 2022 |
| ASUSTek       | N56VZ                       | [e9e40a7df5](https://linux-hardware.org/?probe=e9e40a7df5) | Aug 20, 2022 |
| Timi          | A35                         | [cf89c68d08](https://linux-hardware.org/?probe=cf89c68d08) | Aug 19, 2022 |
| Acer          | Aspire ES1-532G             | [cf05c858ab](https://linux-hardware.org/?probe=cf05c858ab) | Aug 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a533aea5e5](https://linux-hardware.org/?probe=a533aea5e5) | Aug 14, 2022 |
| Timi          | A35                         | [944f3f0942](https://linux-hardware.org/?probe=944f3f0942) | Aug 12, 2022 |
| Dell          | XPS 15 9550                 | [abf6de9a2d](https://linux-hardware.org/?probe=abf6de9a2d) | Aug 09, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [7594659719](https://linux-hardware.org/?probe=7594659719) | Aug 05, 2022 |
| ASUSTek       | X301A1                      | [60d9f2bc4d](https://linux-hardware.org/?probe=60d9f2bc4d) | Aug 02, 2022 |
| Acer          | Aspire A315-42              | [7d8e339d92](https://linux-hardware.org/?probe=7d8e339d92) | Aug 02, 2022 |
| HP            | 255 G7 Notebook PC          | [bc1a82a647](https://linux-hardware.org/?probe=bc1a82a647) | Jul 28, 2022 |
| Acer          | Iconia W700                 | [694887391c](https://linux-hardware.org/?probe=694887391c) | Jul 26, 2022 |
| Acer          | TravelMate 5744Z            | [aa1416d2e3](https://linux-hardware.org/?probe=aa1416d2e3) | Jul 26, 2022 |
| HP            | 255 G7 Notebook PC          | [8173942fbb](https://linux-hardware.org/?probe=8173942fbb) | Jul 25, 2022 |
| Dell          | XPS 15 9550                 | [b4691ae23b](https://linux-hardware.org/?probe=b4691ae23b) | Jul 22, 2022 |
| Fujitsu       | LIFEBOOK AH512              | [de59ca3757](https://linux-hardware.org/?probe=de59ca3757) | Jul 17, 2022 |
| Acer          | Iconia W700                 | [f290f68268](https://linux-hardware.org/?probe=f290f68268) | Jul 14, 2022 |
| Dell          | Latitude 7280               | [75ce6d31bc](https://linux-hardware.org/?probe=75ce6d31bc) | Jul 14, 2022 |
| Toshiba       | Satellite C660              | [fa23f41617](https://linux-hardware.org/?probe=fa23f41617) | Jul 13, 2022 |
| Lenovo        | Y50-70 Touch 20349          | [19209d1119](https://linux-hardware.org/?probe=19209d1119) | Jul 12, 2022 |
| MSI           | Bravo 17 A4DDK              | [9f9d1cac61](https://linux-hardware.org/?probe=9f9d1cac61) | Jul 09, 2022 |
| ASUSTek       | F3JR                        | [9a1e994bcb](https://linux-hardware.org/?probe=9a1e994bcb) | Jul 08, 2022 |
| Prestigio     | Multipad Visconte V         | [d582eea1af](https://linux-hardware.org/?probe=d582eea1af) | Jul 08, 2022 |
| MSI           | Prestige 14 A10SC           | [f1632a7901](https://linux-hardware.org/?probe=f1632a7901) | Jul 06, 2022 |
| Fujitsu       | LIFEBOOK E734               | [6494f9e1ef](https://linux-hardware.org/?probe=6494f9e1ef) | Jul 05, 2022 |
| ASUSTek       | TP501UB                     | [4cebce6bab](https://linux-hardware.org/?probe=4cebce6bab) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | [6ee62813e8](https://linux-hardware.org/?probe=6ee62813e8) | Jul 04, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [f63cb64736](https://linux-hardware.org/?probe=f63cb64736) | Jul 03, 2022 |
| Acer          | Aspire 5741G                | [228eb87fbc](https://linux-hardware.org/?probe=228eb87fbc) | Jul 02, 2022 |
| Lenovo        | G550 20023                  | [0a2aa10fd1](https://linux-hardware.org/?probe=0a2aa10fd1) | Jun 27, 2022 |
| Acer          | Swift SF314-41              | [735d7a92b5](https://linux-hardware.org/?probe=735d7a92b5) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [6ebb8676bf](https://linux-hardware.org/?probe=6ebb8676bf) | Jun 16, 2022 |
| HP            | Pavilion g6                 | [c43a328a7d](https://linux-hardware.org/?probe=c43a328a7d) | Jun 13, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5c07fd1664](https://linux-hardware.org/?probe=5c07fd1664) | Jun 12, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [44704fc87d](https://linux-hardware.org/?probe=44704fc87d) | Jun 12, 2022 |
| HP            | ProBook 455 G7              | [60bf6f8388](https://linux-hardware.org/?probe=60bf6f8388) | Jun 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [29f2cd44d5](https://linux-hardware.org/?probe=29f2cd44d5) | Jun 11, 2022 |
| Acer          | Swift SF314-43              | [2a3a49ac86](https://linux-hardware.org/?probe=2a3a49ac86) | Jun 10, 2022 |
| Lenovo        | ThinkPad P52s 20LBS04700    | [96e3e051da](https://linux-hardware.org/?probe=96e3e051da) | Jun 09, 2022 |
| Lenovo        | ThinkPad P52s 20LBS04700    | [547e2586ca](https://linux-hardware.org/?probe=547e2586ca) | Jun 09, 2022 |
| eMachines     | eME528                      | [1a6f2ee67f](https://linux-hardware.org/?probe=1a6f2ee67f) | Jun 09, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [f0b7599192](https://linux-hardware.org/?probe=f0b7599192) | Jun 08, 2022 |
| Acer          | Aspire A315-32              | [a610c5537a](https://linux-hardware.org/?probe=a610c5537a) | Jun 07, 2022 |
| Lenovo        | G580 20150                  | [6cb0b47bb4](https://linux-hardware.org/?probe=6cb0b47bb4) | Jun 02, 2022 |
| HP            | Pavilion g6                 | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| HP            | ProBook 455 G7              | [658e8ce62f](https://linux-hardware.org/?probe=658e8ce62f) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | [c4880f9bab](https://linux-hardware.org/?probe=c4880f9bab) | Jun 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5330a5aa11](https://linux-hardware.org/?probe=5330a5aa11) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | [7f8acf64cd](https://linux-hardware.org/?probe=7f8acf64cd) | May 31, 2022 |
| HP            | ProBook 455 G7              | [d95897f938](https://linux-hardware.org/?probe=d95897f938) | May 31, 2022 |
| HP            | ProBook 450 G5              | [2fbbe84744](https://linux-hardware.org/?probe=2fbbe84744) | May 31, 2022 |
| ASUSTek       | X75A1                       | [59159b4b05](https://linux-hardware.org/?probe=59159b4b05) | May 27, 2022 |
| Minix         | Z64 V1.2                    | [97525a1dc3](https://linux-hardware.org/?probe=97525a1dc3) | May 27, 2022 |
| HP            | Pavilion g6                 | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| HP            | Pavilion g7                 | [e038c828f9](https://linux-hardware.org/?probe=e038c828f9) | May 25, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7200a39439](https://linux-hardware.org/?probe=7200a39439) | May 23, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [377330c2b5](https://linux-hardware.org/?probe=377330c2b5) | May 23, 2022 |
| Dell          | Vostro 15 3515              | [90d9ac6bf3](https://linux-hardware.org/?probe=90d9ac6bf3) | May 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1e61b49f67](https://linux-hardware.org/?probe=1e61b49f67) | May 18, 2022 |
| Dell          | Precision M6800             | [65d5a77965](https://linux-hardware.org/?probe=65d5a77965) | May 14, 2022 |
| Irbis         | NB144                       | [abb6000f0b](https://linux-hardware.org/?probe=abb6000f0b) | May 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [eb297f3c7b](https://linux-hardware.org/?probe=eb297f3c7b) | May 12, 2022 |
| Minix         | Z64 V1.2                    | [8796deded0](https://linux-hardware.org/?probe=8796deded0) | May 12, 2022 |
| Lenovo        | Unknown                     | [3cced8a4fa](https://linux-hardware.org/?probe=3cced8a4fa) | May 12, 2022 |
| Samsung       | R530/R730/P530              | [d209735fd8](https://linux-hardware.org/?probe=d209735fd8) | May 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [ac2c2a5969](https://linux-hardware.org/?probe=ac2c2a5969) | May 06, 2022 |
| Lenovo        | ThinkPad X220 4290LD4       | [0a28279824](https://linux-hardware.org/?probe=0a28279824) | May 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [26cfc77ab9](https://linux-hardware.org/?probe=26cfc77ab9) | May 02, 2022 |
| ICL           | RAYbook Si1507              | [eaf9bd7ea3](https://linux-hardware.org/?probe=eaf9bd7ea3) | May 02, 2022 |
| HP            | ProBook 4520s               | [ba430a31ae](https://linux-hardware.org/?probe=ba430a31ae) | May 01, 2022 |
| Lenovo        | G700 20251                  | [94272db5ec](https://linux-hardware.org/?probe=94272db5ec) | Apr 30, 2022 |
| ASUSTek       | UX31A                       | [59228e735e](https://linux-hardware.org/?probe=59228e735e) | Apr 30, 2022 |
| Acer          | TravelMate 2490             | [8cc2cf84f4](https://linux-hardware.org/?probe=8cc2cf84f4) | Apr 29, 2022 |
| Timi          | A35S                        | [8a3195e10c](https://linux-hardware.org/?probe=8a3195e10c) | Apr 27, 2022 |
| Timi          | RedmiBook Pro 15S           | [d060ed71c3](https://linux-hardware.org/?probe=d060ed71c3) | Apr 26, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [4f92840d8c](https://linux-hardware.org/?probe=4f92840d8c) | Apr 26, 2022 |
| Lenovo        | G510 20238                  | [906f1626d7](https://linux-hardware.org/?probe=906f1626d7) | Apr 24, 2022 |
| Acer          | AOD257                      | [9b11649bce](https://linux-hardware.org/?probe=9b11649bce) | Apr 22, 2022 |
| Acer          | AOD257                      | [e321b17ef8](https://linux-hardware.org/?probe=e321b17ef8) | Apr 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [76bb32f682](https://linux-hardware.org/?probe=76bb32f682) | Apr 20, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | [4ed718df3e](https://linux-hardware.org/?probe=4ed718df3e) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | [402c31b107](https://linux-hardware.org/?probe=402c31b107) | Apr 18, 2022 |
| ASUSTek       | UX303LB                     | [104779add9](https://linux-hardware.org/?probe=104779add9) | Apr 17, 2022 |
| HP            | 250 G2                      | [eafcfe8215](https://linux-hardware.org/?probe=eafcfe8215) | Apr 17, 2022 |
| ASUSTek       | K50IJ                       | [ad5a24dbb3](https://linux-hardware.org/?probe=ad5a24dbb3) | Apr 15, 2022 |
| ASUSTek       | ROG Strix G713QC_G713QC     | [c54b458c01](https://linux-hardware.org/?probe=c54b458c01) | Apr 14, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | [9e8785fcdd](https://linux-hardware.org/?probe=9e8785fcdd) | Apr 14, 2022 |
| ASUSTek       | X75VCP                      | [21e0b65e1b](https://linux-hardware.org/?probe=21e0b65e1b) | Apr 13, 2022 |
| Lenovo        | G780 20138                  | [0cabea6484](https://linux-hardware.org/?probe=0cabea6484) | Apr 08, 2022 |
| Lenovo        | B570 HuronRiver Platform    | [cdb5f43cd7](https://linux-hardware.org/?probe=cdb5f43cd7) | Apr 07, 2022 |
| Timi          | A35                         | [90a30461d2](https://linux-hardware.org/?probe=90a30461d2) | Apr 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [262e4f8317](https://linux-hardware.org/?probe=262e4f8317) | Apr 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [27f986af8c](https://linux-hardware.org/?probe=27f986af8c) | Mar 30, 2022 |
| Insignia      | NS-P11W7100                 | [daa476af8c](https://linux-hardware.org/?probe=daa476af8c) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [b431dc3d73](https://linux-hardware.org/?probe=b431dc3d73) | Mar 28, 2022 |
| HP            | ZBook 17 G3                 | [b016648f02](https://linux-hardware.org/?probe=b016648f02) | Mar 27, 2022 |
| Aquarius      | NS585 R32                   | [582389ca98](https://linux-hardware.org/?probe=582389ca98) | Mar 24, 2022 |
| ASUSTek       | X75VCP                      | [54e978fcca](https://linux-hardware.org/?probe=54e978fcca) | Mar 23, 2022 |
| Timi          | RedmiBook Pro 15            | [78f30b04b6](https://linux-hardware.org/?probe=78f30b04b6) | Mar 21, 2022 |
| Samsung       | R59P/R60P/R61P              | [2ec6236c3a](https://linux-hardware.org/?probe=2ec6236c3a) | Mar 20, 2022 |
| Insignia      | NS-P11W7100                 | [20aa266b33](https://linux-hardware.org/?probe=20aa266b33) | Mar 19, 2022 |
| Unknown       | Unknown                     | [58912ced73](https://linux-hardware.org/?probe=58912ced73) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [4652b9e771](https://linux-hardware.org/?probe=4652b9e771) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [091eb95750](https://linux-hardware.org/?probe=091eb95750) | Mar 17, 2022 |
| Lenovo        | IdeaPad Z580                | [80a27aca02](https://linux-hardware.org/?probe=80a27aca02) | Mar 17, 2022 |
| Insignia      | NS-P11W7100                 | [44de443312](https://linux-hardware.org/?probe=44de443312) | Mar 11, 2022 |
| HP            | ProBook 450 G7              | [5d73b6f2f7](https://linux-hardware.org/?probe=5d73b6f2f7) | Mar 08, 2022 |
| ASUSTek       | S301LP                      | [5c29218ebd](https://linux-hardware.org/?probe=5c29218ebd) | Mar 08, 2022 |
| Lenovo        | Unknown                     | [4308edfd8d](https://linux-hardware.org/?probe=4308edfd8d) | Mar 07, 2022 |
| Acer          | Swift SF314-43              | [6d16601f06](https://linux-hardware.org/?probe=6d16601f06) | Mar 07, 2022 |
| HP            | 250 G8 Notebook PC          | [11ca11b21d](https://linux-hardware.org/?probe=11ca11b21d) | Mar 03, 2022 |
| Dell          | Vostro 5470                 | [fda73ff759](https://linux-hardware.org/?probe=fda73ff759) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| Dell          | Inspiron 15-3552            | [969cea89d7](https://linux-hardware.org/?probe=969cea89d7) | Feb 24, 2022 |
| HP            | ProBook 4540s               | [6bc6c84af5](https://linux-hardware.org/?probe=6bc6c84af5) | Feb 24, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [72f330a117](https://linux-hardware.org/?probe=72f330a117) | Feb 23, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [f6175c2b08](https://linux-hardware.org/?probe=f6175c2b08) | Feb 22, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [a941fd5481](https://linux-hardware.org/?probe=a941fd5481) | Feb 21, 2022 |
| Timi          | RedmiBook Pro 15S           | [1998552d88](https://linux-hardware.org/?probe=1998552d88) | Feb 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b4979c164c](https://linux-hardware.org/?probe=b4979c164c) | Feb 20, 2022 |
| Lenovo        | ThinkPad ThinkPad L14 20... | [369c625e43](https://linux-hardware.org/?probe=369c625e43) | Feb 20, 2022 |
| Acer          | Swift SF315-52              | [74009233c2](https://linux-hardware.org/?probe=74009233c2) | Feb 19, 2022 |
| HP            | Compaq CQ58                 | [6f67712b57](https://linux-hardware.org/?probe=6f67712b57) | Feb 19, 2022 |
| Timi          | RedmiBook Pro 15S           | [8b0dc90a9e](https://linux-hardware.org/?probe=8b0dc90a9e) | Feb 19, 2022 |
| ASUSTek       | K54L                        | [5850a8dd22](https://linux-hardware.org/?probe=5850a8dd22) | Feb 19, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [489854bd7b](https://linux-hardware.org/?probe=489854bd7b) | Feb 18, 2022 |
| Lenovo        | ThinkPad Edge E531 68851... | [54269ad944](https://linux-hardware.org/?probe=54269ad944) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [3c30a8c6a1](https://linux-hardware.org/?probe=3c30a8c6a1) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4fba279b51](https://linux-hardware.org/?probe=4fba279b51) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [42cf76ea1b](https://linux-hardware.org/?probe=42cf76ea1b) | Feb 18, 2022 |
| Dell          | Vostro 2521                 | [b4e4037c5e](https://linux-hardware.org/?probe=b4e4037c5e) | Feb 18, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d98a594e28](https://linux-hardware.org/?probe=d98a594e28) | Feb 18, 2022 |
| Samsung       | 535U4C                      | [f5f9256781](https://linux-hardware.org/?probe=f5f9256781) | Feb 16, 2022 |
| HP            | ProBook 440 G7              | [bf3d7b3f6c](https://linux-hardware.org/?probe=bf3d7b3f6c) | Feb 15, 2022 |
| Lenovo        | G500 20236                  | [725807db6f](https://linux-hardware.org/?probe=725807db6f) | Feb 15, 2022 |
| ASUSTek       | X553MA                      | [94ebaa5d9b](https://linux-hardware.org/?probe=94ebaa5d9b) | Feb 15, 2022 |
| HP            | Pavilion g6                 | [5601a4d596](https://linux-hardware.org/?probe=5601a4d596) | Feb 14, 2022 |
| MSI           | MS-16F1                     | [cd35935349](https://linux-hardware.org/?probe=cd35935349) | Feb 13, 2022 |
| Acer          | Extensa 5620                | [d56ce9d11a](https://linux-hardware.org/?probe=d56ce9d11a) | Feb 13, 2022 |
| ASUSTek       | X550VB                      | [0485b98343](https://linux-hardware.org/?probe=0485b98343) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E531 68851... | [e82c11b42e](https://linux-hardware.org/?probe=e82c11b42e) | Feb 13, 2022 |
| Dell          | Latitude 5480               | [1804ba8af6](https://linux-hardware.org/?probe=1804ba8af6) | Feb 12, 2022 |
| Dell          | Latitude 5480               | [198846e977](https://linux-hardware.org/?probe=198846e977) | Feb 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [42674c38b2](https://linux-hardware.org/?probe=42674c38b2) | Feb 12, 2022 |
| HP            | 250 G5 Notebook PC          | [1e1f5d2acb](https://linux-hardware.org/?probe=1e1f5d2acb) | Feb 11, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [2cfb1f14b9](https://linux-hardware.org/?probe=2cfb1f14b9) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c4ac76b8e8](https://linux-hardware.org/?probe=c4ac76b8e8) | Feb 10, 2022 |
| Lenovo        | IdeaPad Z580                | [bfdd2f78ce](https://linux-hardware.org/?probe=bfdd2f78ce) | Feb 10, 2022 |
| HP            | Pavilion g6                 | [5d20c75fe1](https://linux-hardware.org/?probe=5d20c75fe1) | Feb 08, 2022 |
| Razer         | Blade Stealth               | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [1bbcbcc9a2](https://linux-hardware.org/?probe=1bbcbcc9a2) | Feb 07, 2022 |
| Acer          | Aspire E1-571               | [2de4d69854](https://linux-hardware.org/?probe=2de4d69854) | Feb 06, 2022 |
| Lenovo        | IdeaPad S110 20126          | [1d55b1f711](https://linux-hardware.org/?probe=1d55b1f711) | Feb 06, 2022 |
| ASUSTek       | N61Ja                       | [77e8b534fb](https://linux-hardware.org/?probe=77e8b534fb) | Feb 05, 2022 |
| Lenovo        | IdeaPad S110 20126          | [b7ae05b6a1](https://linux-hardware.org/?probe=b7ae05b6a1) | Feb 05, 2022 |
| ASUSTek       | N61Ja                       | [3fee6a87f0](https://linux-hardware.org/?probe=3fee6a87f0) | Feb 05, 2022 |
| HP            | EliteBook 840 G3            | [020d6c69c2](https://linux-hardware.org/?probe=020d6c69c2) | Feb 05, 2022 |
| Packard Be... | EasyNote_NJ66               | [11d3d91c9d](https://linux-hardware.org/?probe=11d3d91c9d) | Feb 04, 2022 |
| Packard Be... | EasyNote_NJ66               | [a686d7ec8d](https://linux-hardware.org/?probe=a686d7ec8d) | Feb 04, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [b4c8891709](https://linux-hardware.org/?probe=b4c8891709) | Feb 03, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [d9cc5f0548](https://linux-hardware.org/?probe=d9cc5f0548) | Feb 03, 2022 |
| Timi          | RedmiBook 14-APCS           | [2f335a9d87](https://linux-hardware.org/?probe=2f335a9d87) | Feb 01, 2022 |
| HP            | ProBook 440 G5              | [0e27902494](https://linux-hardware.org/?probe=0e27902494) | Jan 31, 2022 |
| MSI           | GF63 Thin 10SC              | [6ff4bcaf7c](https://linux-hardware.org/?probe=6ff4bcaf7c) | Jan 31, 2022 |
| MSI           | GF63 Thin 10SC              | [be02f0bd97](https://linux-hardware.org/?probe=be02f0bd97) | Jan 31, 2022 |
| MSI           | GF63 Thin 10SC              | [4ffd0d7f19](https://linux-hardware.org/?probe=4ffd0d7f19) | Jan 31, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ebe757d792](https://linux-hardware.org/?probe=ebe757d792) | Jan 30, 2022 |
| HP            | ProBook 440 G5              | [930aa74ba2](https://linux-hardware.org/?probe=930aa74ba2) | Jan 30, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [d3f7315d42](https://linux-hardware.org/?probe=d3f7315d42) | Jan 30, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [a1b813490a](https://linux-hardware.org/?probe=a1b813490a) | Jan 29, 2022 |
| Dell          | Vostro 3300                 | [4213d2a7a3](https://linux-hardware.org/?probe=4213d2a7a3) | Jan 29, 2022 |
| HP            | Laptop 14-cf3xxx            | [52d1ace9ee](https://linux-hardware.org/?probe=52d1ace9ee) | Jan 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c573633ba7](https://linux-hardware.org/?probe=c573633ba7) | Jan 28, 2022 |
| Lenovo        | G500 20236                  | [5d49bf2ce4](https://linux-hardware.org/?probe=5d49bf2ce4) | Jan 27, 2022 |
| Lenovo        | G500 20236                  | [c346ce1a75](https://linux-hardware.org/?probe=c346ce1a75) | Jan 27, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [c42d3ff769](https://linux-hardware.org/?probe=c42d3ff769) | Jan 27, 2022 |
| HP            | ProBook 6560b               | [e61fbcfd64](https://linux-hardware.org/?probe=e61fbcfd64) | Jan 27, 2022 |
| MSI           | Pulse GL66 11UDK            | [06d5ba6ef3](https://linux-hardware.org/?probe=06d5ba6ef3) | Jan 26, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [d44db9ca0d](https://linux-hardware.org/?probe=d44db9ca0d) | Jan 24, 2022 |
| Timi          | RedmiBook Pro 15            | [6ed1fe66db](https://linux-hardware.org/?probe=6ed1fe66db) | Jan 24, 2022 |
| Lenovo        | ThinkPad E590 20NB0058RT    | [0b56eb1e6e](https://linux-hardware.org/?probe=0b56eb1e6e) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [06eb5b9d8d](https://linux-hardware.org/?probe=06eb5b9d8d) | Jan 23, 2022 |
| HP            | ProBook 4540s               | [4dea69e6af](https://linux-hardware.org/?probe=4dea69e6af) | Jan 23, 2022 |
| Dell          | Inspiron 5720               | [4dab658338](https://linux-hardware.org/?probe=4dab658338) | Jan 22, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [ff7be689c1](https://linux-hardware.org/?probe=ff7be689c1) | Jan 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [7926e3c998](https://linux-hardware.org/?probe=7926e3c998) | Jan 19, 2022 |
| Timi          | RedmiBook Pro 14            | [b243482994](https://linux-hardware.org/?probe=b243482994) | Jan 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [49d5581480](https://linux-hardware.org/?probe=49d5581480) | Jan 19, 2022 |
| Shuttle       | DS68U                       | [5ac4aed9d9](https://linux-hardware.org/?probe=5ac4aed9d9) | Jan 19, 2022 |
| HP            | 250 G5 Notebook PC          | [677a43f9a4](https://linux-hardware.org/?probe=677a43f9a4) | Jan 18, 2022 |
| HP            | ZBook 15v G5                | [e21cdc9211](https://linux-hardware.org/?probe=e21cdc9211) | Jan 18, 2022 |
| Dell          | Latitude 7490               | [66984a4e2b](https://linux-hardware.org/?probe=66984a4e2b) | Jan 18, 2022 |
| HP            | 255 G8 Notebook PC          | [c1f8df4bbd](https://linux-hardware.org/?probe=c1f8df4bbd) | Jan 18, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [a84625d725](https://linux-hardware.org/?probe=a84625d725) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [a748bb8955](https://linux-hardware.org/?probe=a748bb8955) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [08613587e8](https://linux-hardware.org/?probe=08613587e8) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [f5b0fd8e22](https://linux-hardware.org/?probe=f5b0fd8e22) | Jan 18, 2022 |
| Lenovo        | V580 20147                  | [b59112177d](https://linux-hardware.org/?probe=b59112177d) | Jan 17, 2022 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [3b8acf9181](https://linux-hardware.org/?probe=3b8acf9181) | Jan 17, 2022 |
| Timi          | A18R                        | [37b8388616](https://linux-hardware.org/?probe=37b8388616) | Jan 16, 2022 |
| Lenovo        | IdeaPad Z580                | [abd0e9203d](https://linux-hardware.org/?probe=abd0e9203d) | Jan 13, 2022 |
| Packard Be... | EasyNote ENTE70BH           | [decd20a2d5](https://linux-hardware.org/?probe=decd20a2d5) | Jan 13, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [7e083c332f](https://linux-hardware.org/?probe=7e083c332f) | Jan 12, 2022 |
| Timi          | RedmiBook 14-APCS           | [ea556dd23d](https://linux-hardware.org/?probe=ea556dd23d) | Jan 12, 2022 |
| Timi          | RedmiBook Pro 14            | [c115b553a2](https://linux-hardware.org/?probe=c115b553a2) | Jan 12, 2022 |
| Acer          | Aspire A515-56              | [4b9aea4afc](https://linux-hardware.org/?probe=4b9aea4afc) | Jan 11, 2022 |
| HP            | ProBook 440 G5              | [ff9bfac8e3](https://linux-hardware.org/?probe=ff9bfac8e3) | Jan 10, 2022 |
| HP            | ProBook 5310m               | [e3c8188e1e](https://linux-hardware.org/?probe=e3c8188e1e) | Jan 10, 2022 |
| HP            | Pavilion 15                 | [6e63d80da8](https://linux-hardware.org/?probe=6e63d80da8) | Jan 09, 2022 |
| HP            | ZBook 15v G5                | [f529eb1829](https://linux-hardware.org/?probe=f529eb1829) | Jan 08, 2022 |
| HP            | ZBook 15v G5                | [5d912e6781](https://linux-hardware.org/?probe=5d912e6781) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [bdfe615a8e](https://linux-hardware.org/?probe=bdfe615a8e) | Jan 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [b9751c3304](https://linux-hardware.org/?probe=b9751c3304) | Jan 07, 2022 |
| HP            | Laptop 14s-fq1xxx           | [5f51ec95e1](https://linux-hardware.org/?probe=5f51ec95e1) | Jan 05, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [65d859bfe1](https://linux-hardware.org/?probe=65d859bfe1) | Jan 05, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [cd84c7dfde](https://linux-hardware.org/?probe=cd84c7dfde) | Jan 04, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [7ed7ce0cb7](https://linux-hardware.org/?probe=7ed7ce0cb7) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [43f3abae3d](https://linux-hardware.org/?probe=43f3abae3d) | Jan 04, 2022 |
| ilife         | S806                        | [72d842b86c](https://linux-hardware.org/?probe=72d842b86c) | Jan 04, 2022 |
| Samsung       | R538/R578/R778              | [617d9d3835](https://linux-hardware.org/?probe=617d9d3835) | Jan 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [08b04c15d3](https://linux-hardware.org/?probe=08b04c15d3) | Jan 03, 2022 |
| ASUSTek       | N55SF                       | [545345d609](https://linux-hardware.org/?probe=545345d609) | Jan 02, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [86160c79c7](https://linux-hardware.org/?probe=86160c79c7) | Jan 01, 2022 |
| HP            | Cario CQ57                  | [5ac4e3101c](https://linux-hardware.org/?probe=5ac4e3101c) | Dec 31, 2021 |
| Acer          | Aspire E5-575G              | [f6d8856ace](https://linux-hardware.org/?probe=f6d8856ace) | Dec 30, 2021 |
| Timi          | A35                         | [253959bb70](https://linux-hardware.org/?probe=253959bb70) | Dec 30, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [b744f2896b](https://linux-hardware.org/?probe=b744f2896b) | Dec 30, 2021 |
| HP            | Laptop 15s-eq1xxx           | [988270bc86](https://linux-hardware.org/?probe=988270bc86) | Dec 30, 2021 |
| Acer          | Aspire 1810TZ               | [0b7bd5c1fa](https://linux-hardware.org/?probe=0b7bd5c1fa) | Dec 30, 2021 |
| Acer          | Aspire 5715Z                | [d2074751d0](https://linux-hardware.org/?probe=d2074751d0) | Dec 29, 2021 |
| Lenovo        | B50-30 20382                | [896ea31fe5](https://linux-hardware.org/?probe=896ea31fe5) | Dec 28, 2021 |
| Acer          | Swift SF114-34              | [f3683a3e4e](https://linux-hardware.org/?probe=f3683a3e4e) | Dec 28, 2021 |
| Acer          | Swift SF114-34              | [891cb4d0fd](https://linux-hardware.org/?probe=891cb4d0fd) | Dec 28, 2021 |
| Dell          | Vostro 1510                 | [38a24e373f](https://linux-hardware.org/?probe=38a24e373f) | Dec 28, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [cc15a65a54](https://linux-hardware.org/?probe=cc15a65a54) | Dec 27, 2021 |
| Google        | Barla                       | [61c74be569](https://linux-hardware.org/?probe=61c74be569) | Dec 26, 2021 |
| HP            | EliteBook 2570p             | [e17f3ed027](https://linux-hardware.org/?probe=e17f3ed027) | Dec 26, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [43c784fc78](https://linux-hardware.org/?probe=43c784fc78) | Dec 25, 2021 |
| HP            | Presario CQ57               | [0294a92fd1](https://linux-hardware.org/?probe=0294a92fd1) | Dec 25, 2021 |
| ASUSTek       | X550VC                      | [cf07bb8280](https://linux-hardware.org/?probe=cf07bb8280) | Dec 25, 2021 |
| Timi          | A35                         | [66e9c6919d](https://linux-hardware.org/?probe=66e9c6919d) | Dec 24, 2021 |
| Dell          | Latitude E7470              | [e712cd258c](https://linux-hardware.org/?probe=e712cd258c) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [a02655b4b8](https://linux-hardware.org/?probe=a02655b4b8) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [6e08796257](https://linux-hardware.org/?probe=6e08796257) | Dec 24, 2021 |
| Acer          | Swift SF314-42              | [02cb3d9b90](https://linux-hardware.org/?probe=02cb3d9b90) | Dec 23, 2021 |
| ASUSTek       | E502NA                      | [66ade120a5](https://linux-hardware.org/?probe=66ade120a5) | Dec 23, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [3a7331c884](https://linux-hardware.org/?probe=3a7331c884) | Dec 22, 2021 |
| Timi          | Mi Gaming Laptop 15.6       | [0001a4fb5e](https://linux-hardware.org/?probe=0001a4fb5e) | Dec 22, 2021 |
| Dell          | Precision M3800             | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Acer          | Aspire A715-75G             | [f33ca54f97](https://linux-hardware.org/?probe=f33ca54f97) | Dec 19, 2021 |
| Timi          | RedmiBook 14 II             | [b6179a5282](https://linux-hardware.org/?probe=b6179a5282) | Dec 19, 2021 |
| Fujitsu       | CELSIUS H700                | [63c35d8f1d](https://linux-hardware.org/?probe=63c35d8f1d) | Dec 19, 2021 |
| Lenovo        | G585 20137                  | [7832d9f8f6](https://linux-hardware.org/?probe=7832d9f8f6) | Dec 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e8a4a4a5f4](https://linux-hardware.org/?probe=e8a4a4a5f4) | Dec 19, 2021 |
| MSI           | Prestige 14Evo A11M         | [2ebe52d75c](https://linux-hardware.org/?probe=2ebe52d75c) | Dec 19, 2021 |
| MSI           | Prestige 14Evo A11M         | [224bb4de1c](https://linux-hardware.org/?probe=224bb4de1c) | Dec 19, 2021 |
| HP            | 630                         | [027b9733fa](https://linux-hardware.org/?probe=027b9733fa) | Dec 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [ce3508ebb4](https://linux-hardware.org/?probe=ce3508ebb4) | Dec 17, 2021 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [6ac6be1d38](https://linux-hardware.org/?probe=6ac6be1d38) | Dec 17, 2021 |
| Timi          | RedmiBook Pro 14            | [62be8931a0](https://linux-hardware.org/?probe=62be8931a0) | Dec 16, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [8218845f08](https://linux-hardware.org/?probe=8218845f08) | Dec 15, 2021 |
| Chuwi         | GemiBook                    | [9ed21194f5](https://linux-hardware.org/?probe=9ed21194f5) | Dec 15, 2021 |
| HP            | ProBook 430 G5              | [a0faef8a2b](https://linux-hardware.org/?probe=a0faef8a2b) | Dec 14, 2021 |
| HP            | 250 G5 Notebook PC          | [4e0a6f267e](https://linux-hardware.org/?probe=4e0a6f267e) | Dec 13, 2021 |
| Acer          | Extensa 5635ZG              | [d232d67b9e](https://linux-hardware.org/?probe=d232d67b9e) | Dec 13, 2021 |
| Dell          | Latitude 7290               | [8a2ecfe430](https://linux-hardware.org/?probe=8a2ecfe430) | Dec 12, 2021 |
| Lenovo        | G550 20023                  | [39aa70e7d6](https://linux-hardware.org/?probe=39aa70e7d6) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [22eeff89e5](https://linux-hardware.org/?probe=22eeff89e5) | Dec 11, 2021 |
| ASUSTek       | X705UAR                     | [74b8b78444](https://linux-hardware.org/?probe=74b8b78444) | Dec 11, 2021 |
| Lenovo        | IdeaPad Z580                | [d801c31eda](https://linux-hardware.org/?probe=d801c31eda) | Dec 10, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [8fa17a7ab6](https://linux-hardware.org/?probe=8fa17a7ab6) | Dec 10, 2021 |
| Toshiba       | Satellite L300              | [a676b11b67](https://linux-hardware.org/?probe=a676b11b67) | Dec 08, 2021 |
| HP            | Laptop 15t-dy200            | [b624d90ea8](https://linux-hardware.org/?probe=b624d90ea8) | Dec 08, 2021 |
| Lenovo        | IdeaPad Z580                | [c07a32f1c5](https://linux-hardware.org/?probe=c07a32f1c5) | Dec 08, 2021 |
| Apple         | MacBookPro8,3               | [11e7db0824](https://linux-hardware.org/?probe=11e7db0824) | Dec 06, 2021 |
| Apple         | MacBookPro8,3               | [cbc310d77b](https://linux-hardware.org/?probe=cbc310d77b) | Dec 06, 2021 |
| Dell          | Latitude E6430              | [eee07229a4](https://linux-hardware.org/?probe=eee07229a4) | Dec 05, 2021 |
| ASUSTek       | K84L                        | [dce2044275](https://linux-hardware.org/?probe=dce2044275) | Dec 05, 2021 |
| HP            | EliteBook 2760p             | [9efe885c4c](https://linux-hardware.org/?probe=9efe885c4c) | Dec 04, 2021 |
| Lenovo        | G500 20236                  | [8aadcee8ff](https://linux-hardware.org/?probe=8aadcee8ff) | Dec 04, 2021 |
| Chuwi         | GemiBook                    | [1e8e0ca774](https://linux-hardware.org/?probe=1e8e0ca774) | Dec 03, 2021 |
| HP            | Pavilion g6                 | [35f8ef913e](https://linux-hardware.org/?probe=35f8ef913e) | Dec 02, 2021 |
| HP            | Pavilion g6                 | [c009dd878b](https://linux-hardware.org/?probe=c009dd878b) | Dec 02, 2021 |
| Acer          | Swift SF314-43              | [dc17b5db95](https://linux-hardware.org/?probe=dc17b5db95) | Dec 01, 2021 |
| Acer          | Aspire 5630                 | [90453b887a](https://linux-hardware.org/?probe=90453b887a) | Dec 01, 2021 |
| Lenovo        | G500 20236                  | [f61434ecc0](https://linux-hardware.org/?probe=f61434ecc0) | Nov 30, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [132b5eba42](https://linux-hardware.org/?probe=132b5eba42) | Nov 29, 2021 |
| Lenovo        | S10-3                       | [19cd43f2f7](https://linux-hardware.org/?probe=19cd43f2f7) | Nov 29, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [b4a83f65e8](https://linux-hardware.org/?probe=b4a83f65e8) | Nov 27, 2021 |
| HP            | Pavilion Notebook 15-bc5... | [dc1f8255a1](https://linux-hardware.org/?probe=dc1f8255a1) | Nov 27, 2021 |
| Lenovo        | G500 20236                  | [c1dd144b77](https://linux-hardware.org/?probe=c1dd144b77) | Nov 27, 2021 |
| Timi          | A35                         | [d1461858c8](https://linux-hardware.org/?probe=d1461858c8) | Nov 27, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [1a6e8764f5](https://linux-hardware.org/?probe=1a6e8764f5) | Nov 27, 2021 |
| ASUSTek       | 1101HA                      | [a97c9a7464](https://linux-hardware.org/?probe=a97c9a7464) | Nov 25, 2021 |
| ASUSTek       | 1101HA                      | [c54c721669](https://linux-hardware.org/?probe=c54c721669) | Nov 25, 2021 |
| HP            | Presario CQ56               | [a9203b72bb](https://linux-hardware.org/?probe=a9203b72bb) | Nov 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [9cffad20cd](https://linux-hardware.org/?probe=9cffad20cd) | Nov 25, 2021 |
| Timi          | A35                         | [ce66e74002](https://linux-hardware.org/?probe=ce66e74002) | Nov 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5f4fb6db3f](https://linux-hardware.org/?probe=5f4fb6db3f) | Nov 24, 2021 |
| Chuwi         | GemiBook Pro                | [1dc5d193a3](https://linux-hardware.org/?probe=1dc5d193a3) | Nov 24, 2021 |
| Timi          | RedmiBook Pro 15            | [342085ddb3](https://linux-hardware.org/?probe=342085ddb3) | Nov 24, 2021 |
| HP            | Presario CQ56               | [b50968704d](https://linux-hardware.org/?probe=b50968704d) | Nov 24, 2021 |
| Dell          | Inspiron 5558               | [772ca16963](https://linux-hardware.org/?probe=772ca16963) | Nov 23, 2021 |
| Lenovo        | ThinkPad E14 20RA0037RT     | [5a1e17caef](https://linux-hardware.org/?probe=5a1e17caef) | Nov 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a8d3bc914a](https://linux-hardware.org/?probe=a8d3bc914a) | Nov 23, 2021 |
| HP            | ProBook 440 G7              | [7863ad05f4](https://linux-hardware.org/?probe=7863ad05f4) | Nov 23, 2021 |
| HP            | Pavilion Notebook           | [7045bece2c](https://linux-hardware.org/?probe=7045bece2c) | Nov 23, 2021 |
| Lenovo        | G510 20238                  | [46cddf1bf1](https://linux-hardware.org/?probe=46cddf1bf1) | Nov 21, 2021 |
| HP            | ProBook 4540s               | [5d7d756044](https://linux-hardware.org/?probe=5d7d756044) | Nov 20, 2021 |
| HP            | ProBook 450 G7              | [c80f09c408](https://linux-hardware.org/?probe=c80f09c408) | Nov 19, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c07f000594](https://linux-hardware.org/?probe=c07f000594) | Nov 19, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [55554fa68d](https://linux-hardware.org/?probe=55554fa68d) | Nov 18, 2021 |
| Apple         | MacBook4,1                  | [f9ee489abd](https://linux-hardware.org/?probe=f9ee489abd) | Nov 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [9fc64a9c41](https://linux-hardware.org/?probe=9fc64a9c41) | Nov 15, 2021 |
| Acer          | Aspire A715-71G             | [dd0bfcd823](https://linux-hardware.org/?probe=dd0bfcd823) | Nov 15, 2021 |
| Lenovo        | ThinkPad E450 20DCS01J00    | [ce5eb49ae7](https://linux-hardware.org/?probe=ce5eb49ae7) | Nov 14, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [8020390e6c](https://linux-hardware.org/?probe=8020390e6c) | Nov 12, 2021 |
| ASUSTek       | X750JB                      | [05e39baf5f](https://linux-hardware.org/?probe=05e39baf5f) | Nov 12, 2021 |
| ASUSTek       | 1011PX                      | [2d96503388](https://linux-hardware.org/?probe=2d96503388) | Nov 10, 2021 |
| HP            | Laptop 15s-eq2xxx           | [0ac3172f62](https://linux-hardware.org/?probe=0ac3172f62) | Nov 09, 2021 |
| Lenovo        | ThinkPad E450 20DCS01J00    | [ee83aa5751](https://linux-hardware.org/?probe=ee83aa5751) | Nov 08, 2021 |
| Apple         | MacBook4,1                  | [a87d85ac9f](https://linux-hardware.org/?probe=a87d85ac9f) | Nov 08, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [0812e26e5a](https://linux-hardware.org/?probe=0812e26e5a) | Nov 08, 2021 |
| HP            | ProBook 450 G6              | [ded9086b7c](https://linux-hardware.org/?probe=ded9086b7c) | Nov 06, 2021 |
| Dell          | Latitude E6530              | [949bc94abe](https://linux-hardware.org/?probe=949bc94abe) | Nov 05, 2021 |
| Dell          | Latitude E6530              | [3160f800e5](https://linux-hardware.org/?probe=3160f800e5) | Nov 05, 2021 |
| Acer          | Swift SF114-33              | [9e177a92f3](https://linux-hardware.org/?probe=9e177a92f3) | Nov 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Lenovo        | PIWG1                       | [96ae269001](https://linux-hardware.org/?probe=96ae269001) | Nov 03, 2021 |
| HP            | Pavilion dv6                | [461518c8a8](https://linux-hardware.org/?probe=461518c8a8) | Nov 03, 2021 |
| Lenovo        | G710 20252                  | [6c197fdb65](https://linux-hardware.org/?probe=6c197fdb65) | Nov 02, 2021 |
| Dell          | Latitude 5520               | [51ae6048ea](https://linux-hardware.org/?probe=51ae6048ea) | Nov 01, 2021 |
| Dell          | Inspiron 5558               | [d876caae1e](https://linux-hardware.org/?probe=d876caae1e) | Oct 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [4eb6b00cac](https://linux-hardware.org/?probe=4eb6b00cac) | Oct 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c9153e029e](https://linux-hardware.org/?probe=c9153e029e) | Oct 31, 2021 |
| Acer          | Swift SF114-34              | [84b1c46f3c](https://linux-hardware.org/?probe=84b1c46f3c) | Oct 31, 2021 |
| MSI           | GT72 6QD                    | [64f2d60b7e](https://linux-hardware.org/?probe=64f2d60b7e) | Oct 30, 2021 |
| HP            | ZBook 14u G6                | [a814284f0b](https://linux-hardware.org/?probe=a814284f0b) | Oct 29, 2021 |
| Lenovo        | V580c 20160                 | [779684e41d](https://linux-hardware.org/?probe=779684e41d) | Oct 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4770866d46](https://linux-hardware.org/?probe=4770866d46) | Oct 27, 2021 |
| Apple         | MacBookPro8,2               | [966b07a428](https://linux-hardware.org/?probe=966b07a428) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [cc4c888046](https://linux-hardware.org/?probe=cc4c888046) | Oct 27, 2021 |
| Dell          | Inspiron 5558               | [e22971aa36](https://linux-hardware.org/?probe=e22971aa36) | Oct 27, 2021 |
| Acer          | Nitro AN515-55              | [2b3ef0e291](https://linux-hardware.org/?probe=2b3ef0e291) | Oct 26, 2021 |
| Acer          | Nitro AN515-55              | [2d7ac3338d](https://linux-hardware.org/?probe=2d7ac3338d) | Oct 26, 2021 |
| Acer          | Swift SF314-59              | [1e4856a770](https://linux-hardware.org/?probe=1e4856a770) | Oct 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1c91bc1deb](https://linux-hardware.org/?probe=1c91bc1deb) | Oct 23, 2021 |
| Samsung       | R59P/R60P/R61P              | [fb06ae58f0](https://linux-hardware.org/?probe=fb06ae58f0) | Oct 22, 2021 |
| HP            | 255 G7 Notebook PC          | [318a6d484a](https://linux-hardware.org/?probe=318a6d484a) | Oct 22, 2021 |
| Timi          | TM1701                      | [6ee47924bd](https://linux-hardware.org/?probe=6ee47924bd) | Oct 22, 2021 |
| Dell          | Inspiron 5558               | [6ada321924](https://linux-hardware.org/?probe=6ada321924) | Oct 22, 2021 |
| Lenovo        | V580c 20160                 | [fbeb39e0ce](https://linux-hardware.org/?probe=fbeb39e0ce) | Oct 20, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [456b686d28](https://linux-hardware.org/?probe=456b686d28) | Oct 20, 2021 |
| HP            | ZBook Firefly 15 inch G8... | [25c0517a63](https://linux-hardware.org/?probe=25c0517a63) | Oct 20, 2021 |
| Sony          | VGN-CR19VN_B                | [409f7c6aed](https://linux-hardware.org/?probe=409f7c6aed) | Oct 19, 2021 |
| Shuttle       | DS57U                       | [780ca9b317](https://linux-hardware.org/?probe=780ca9b317) | Oct 19, 2021 |
| Timi          | RedmiBook Pro 14            | [0a5df275dd](https://linux-hardware.org/?probe=0a5df275dd) | Oct 18, 2021 |
| Framework     | Laptop                      | [591c9d1d8f](https://linux-hardware.org/?probe=591c9d1d8f) | Oct 18, 2021 |
| HP            | 255 G1                      | [d37ee677e9](https://linux-hardware.org/?probe=d37ee677e9) | Oct 17, 2021 |
| Acer          | Swift SF314-41              | [589beb7652](https://linux-hardware.org/?probe=589beb7652) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | [5b965ea234](https://linux-hardware.org/?probe=5b965ea234) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | [3a5976d4eb](https://linux-hardware.org/?probe=3a5976d4eb) | Oct 17, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [532cb2dfc8](https://linux-hardware.org/?probe=532cb2dfc8) | Oct 17, 2021 |
| Acer          | Aspire A315-42G             | [6134bf279a](https://linux-hardware.org/?probe=6134bf279a) | Oct 17, 2021 |
| eMachines     | eM350                       | [09b8fc981c](https://linux-hardware.org/?probe=09b8fc981c) | Oct 16, 2021 |
| Dell          | Latitude E6440              | [e6d39c35d6](https://linux-hardware.org/?probe=e6d39c35d6) | Oct 16, 2021 |
| Acer          | TravelMate P215-53          | [3d398d4b58](https://linux-hardware.org/?probe=3d398d4b58) | Oct 16, 2021 |
| Apple         | MacBookPro14,1              | [dc7e454319](https://linux-hardware.org/?probe=dc7e454319) | Oct 15, 2021 |
| Apple         | MacBookPro14,1              | [bf9482b190](https://linux-hardware.org/?probe=bf9482b190) | Oct 15, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [3818b62208](https://linux-hardware.org/?probe=3818b62208) | Oct 15, 2021 |
| Lenovo        | IdeaPad Z580                | [6b1d1f059f](https://linux-hardware.org/?probe=6b1d1f059f) | Oct 15, 2021 |
| Lenovo        | IdeaPad Z580                | [661f69eb29](https://linux-hardware.org/?probe=661f69eb29) | Oct 15, 2021 |
| Acer          | Aspire A515-51G             | [af67b942ec](https://linux-hardware.org/?probe=af67b942ec) | Oct 14, 2021 |
| HP            | 250 G8 Notebook PC          | [7a564f9af9](https://linux-hardware.org/?probe=7a564f9af9) | Oct 14, 2021 |
| Dell          | Latitude E6440              | [a12ce4cf4a](https://linux-hardware.org/?probe=a12ce4cf4a) | Oct 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [08cda4fcb0](https://linux-hardware.org/?probe=08cda4fcb0) | Oct 13, 2021 |
| Lenovo        | S40-70 80GQ                 | [5515480ed0](https://linux-hardware.org/?probe=5515480ed0) | Oct 13, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [89840aac65](https://linux-hardware.org/?probe=89840aac65) | Oct 13, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [139f682d03](https://linux-hardware.org/?probe=139f682d03) | Oct 12, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [fcc9eab970](https://linux-hardware.org/?probe=fcc9eab970) | Oct 12, 2021 |
| Acer          | Aspire 6935                 | [93e47a1ab3](https://linux-hardware.org/?probe=93e47a1ab3) | Oct 12, 2021 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [80718210cc](https://linux-hardware.org/?probe=80718210cc) | Oct 12, 2021 |
| Timi          | RedmiBook 13 R              | [e6c38e5b79](https://linux-hardware.org/?probe=e6c38e5b79) | Oct 10, 2021 |
| HP            | EliteBook 2760p             | [0b1f6a34ce](https://linux-hardware.org/?probe=0b1f6a34ce) | Oct 10, 2021 |
| Lenovo        | G710 20252                  | [61b036977b](https://linux-hardware.org/?probe=61b036977b) | Oct 10, 2021 |
| Dell          | System Inspiron 7720        | [6728cba5a1](https://linux-hardware.org/?probe=6728cba5a1) | Oct 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [d36b70e744](https://linux-hardware.org/?probe=d36b70e744) | Oct 09, 2021 |
| Timi          | RedmiBook 16                | [23546f7a48](https://linux-hardware.org/?probe=23546f7a48) | Oct 07, 2021 |
| Dell          | Latitude E6430              | [c9b6be5ccb](https://linux-hardware.org/?probe=c9b6be5ccb) | Oct 07, 2021 |
| HP            | ProBook 455R G6             | [9cfde72e18](https://linux-hardware.org/?probe=9cfde72e18) | Oct 07, 2021 |
| HP            | ProBook 450 G7              | [b4488791d9](https://linux-hardware.org/?probe=b4488791d9) | Oct 07, 2021 |
| Lenovo        | ThinkPad T490s 20NX003NR... | [9ca00402e4](https://linux-hardware.org/?probe=9ca00402e4) | Oct 07, 2021 |
| Dell          | Precision 7510              | [c2bddf370f](https://linux-hardware.org/?probe=c2bddf370f) | Oct 05, 2021 |
| Lenovo        | G500 20236                  | [e3d2756797](https://linux-hardware.org/?probe=e3d2756797) | Oct 03, 2021 |
| ASUSTek       | K55VM                       | [848fef92f0](https://linux-hardware.org/?probe=848fef92f0) | Oct 02, 2021 |
| HP            | 255 G7 Notebook PC          | [472633cfb7](https://linux-hardware.org/?probe=472633cfb7) | Oct 02, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [3a0cd09aa4](https://linux-hardware.org/?probe=3a0cd09aa4) | Oct 01, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [c69f22bca8](https://linux-hardware.org/?probe=c69f22bca8) | Oct 01, 2021 |
| HP            | Laptop 15s-fq2xxx           | [b1066885ba](https://linux-hardware.org/?probe=b1066885ba) | Oct 01, 2021 |
| Lenovo        | ThinkPad T460p 20FWS0A60... | [fbcd17f6bc](https://linux-hardware.org/?probe=fbcd17f6bc) | Oct 01, 2021 |
| HP            | 250 G7 Notebook PC          | [20517ef47c](https://linux-hardware.org/?probe=20517ef47c) | Sep 30, 2021 |
| Lenovo        | G500 20236                  | [2e1b563aa1](https://linux-hardware.org/?probe=2e1b563aa1) | Sep 29, 2021 |
| Lenovo        | ThinkPad T460p 20FWS0A60... | [27c1d71909](https://linux-hardware.org/?probe=27c1d71909) | Sep 29, 2021 |
| Lenovo        | ThinkPad T490 20N20009RT    | [4d28ac0812](https://linux-hardware.org/?probe=4d28ac0812) | Sep 29, 2021 |
| ASUSTek       | X751SA                      | [9b5b69452d](https://linux-hardware.org/?probe=9b5b69452d) | Sep 29, 2021 |
| HP            | ENVY Laptop 15-ep0xxx       | [834c40e64f](https://linux-hardware.org/?probe=834c40e64f) | Sep 29, 2021 |
| ASUSTek       | 1000HE                      | [c002c44040](https://linux-hardware.org/?probe=c002c44040) | Sep 27, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [591896b2ee](https://linux-hardware.org/?probe=591896b2ee) | Sep 27, 2021 |
| HP            | ProBook 450 G7              | [0696ed1853](https://linux-hardware.org/?probe=0696ed1853) | Sep 27, 2021 |
| HP            | ProBook 450 G7              | [dc36f3a40d](https://linux-hardware.org/?probe=dc36f3a40d) | Sep 27, 2021 |
| HP            | Pavilion dv6                | [ffc397f9f8](https://linux-hardware.org/?probe=ffc397f9f8) | Sep 26, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [c4680da2f6](https://linux-hardware.org/?probe=c4680da2f6) | Sep 26, 2021 |
| HP            | Pavilion dv6                | [2a6a76f702](https://linux-hardware.org/?probe=2a6a76f702) | Sep 26, 2021 |
| HP            | 250 G7 Notebook PC          | [5fbac554c3](https://linux-hardware.org/?probe=5fbac554c3) | Sep 25, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c248e4551a](https://linux-hardware.org/?probe=c248e4551a) | Sep 25, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [de58749699](https://linux-hardware.org/?probe=de58749699) | Sep 25, 2021 |
| ASUSTek       | UX330UA                     | [175fc7f169](https://linux-hardware.org/?probe=175fc7f169) | Sep 25, 2021 |
| Acer          | TravelMate 8572G            | [dafac228b8](https://linux-hardware.org/?probe=dafac228b8) | Sep 25, 2021 |
| Acer          | Aspire 5250                 | [ae41600fd9](https://linux-hardware.org/?probe=ae41600fd9) | Sep 24, 2021 |
| Sony          | VPCS131FM                   | [b5bba0e07f](https://linux-hardware.org/?probe=b5bba0e07f) | Sep 22, 2021 |
| Sony          | VPCS131FM                   | [54923e2372](https://linux-hardware.org/?probe=54923e2372) | Sep 22, 2021 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [1b82bac47b](https://linux-hardware.org/?probe=1b82bac47b) | Sep 21, 2021 |
| MSI           | U270 series                 | [6b98f78732](https://linux-hardware.org/?probe=6b98f78732) | Sep 19, 2021 |
| MSI           | U270 series                 | [725e0a6a36](https://linux-hardware.org/?probe=725e0a6a36) | Sep 18, 2021 |
| Dell          | Inspiron 3543               | [030a6cb62d](https://linux-hardware.org/?probe=030a6cb62d) | Sep 18, 2021 |
| Acer          | Aspire 5560                 | [f35af81d19](https://linux-hardware.org/?probe=f35af81d19) | Sep 18, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [3656e9b0ae](https://linux-hardware.org/?probe=3656e9b0ae) | Sep 18, 2021 |
| HP            | Laptop 15s-eq2xxx           | [0d59451bad](https://linux-hardware.org/?probe=0d59451bad) | Sep 16, 2021 |
| HP            | ZBook 17 G6                 | [dbebd11a10](https://linux-hardware.org/?probe=dbebd11a10) | Sep 16, 2021 |
| HP            | Laptop 15-db1xxx            | [c085ff8d88](https://linux-hardware.org/?probe=c085ff8d88) | Sep 15, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [dd10c770ed](https://linux-hardware.org/?probe=dd10c770ed) | Sep 15, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [c51f5529e4](https://linux-hardware.org/?probe=c51f5529e4) | Sep 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [f55a8d5ce5](https://linux-hardware.org/?probe=f55a8d5ce5) | Sep 14, 2021 |
| Dell          | Inspiron 3595               | [14ac87b8bc](https://linux-hardware.org/?probe=14ac87b8bc) | Sep 14, 2021 |
| HP            | Laptop 15s-eq2xxx           | [1fbb778cec](https://linux-hardware.org/?probe=1fbb778cec) | Sep 12, 2021 |
| Samsung       | RF510/RF410/RF710           | [66ec4435e0](https://linux-hardware.org/?probe=66ec4435e0) | Sep 12, 2021 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [3c2564d223](https://linux-hardware.org/?probe=3c2564d223) | Sep 11, 2021 |
| HP            | ProBook 455 G7              | [c3d2892b84](https://linux-hardware.org/?probe=c3d2892b84) | Sep 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [0fc95e8662](https://linux-hardware.org/?probe=0fc95e8662) | Sep 09, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [7787c87e7f](https://linux-hardware.org/?probe=7787c87e7f) | Sep 09, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [3dca1ff09e](https://linux-hardware.org/?probe=3dca1ff09e) | Sep 09, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [ca3a7ba56b](https://linux-hardware.org/?probe=ca3a7ba56b) | Sep 09, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [422d6cdb0b](https://linux-hardware.org/?probe=422d6cdb0b) | Sep 08, 2021 |
| HP            | 250 G7 Notebook PC          | [2327ab2724](https://linux-hardware.org/?probe=2327ab2724) | Sep 07, 2021 |
| HP            | 250 G7 Notebook PC          | [52b780559c](https://linux-hardware.org/?probe=52b780559c) | Sep 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9e4676c4a4](https://linux-hardware.org/?probe=9e4676c4a4) | Sep 07, 2021 |
| HP            | Laptop 15s-eq1xxx           | [9256f3fece](https://linux-hardware.org/?probe=9256f3fece) | Sep 06, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [8bbaa65e84](https://linux-hardware.org/?probe=8bbaa65e84) | Sep 06, 2021 |
| Dell          | Vostro 3500                 | [9be94cd5b2](https://linux-hardware.org/?probe=9be94cd5b2) | Sep 06, 2021 |
| Lenovo        | G500 20236                  | [6da34b890e](https://linux-hardware.org/?probe=6da34b890e) | Sep 06, 2021 |
| Acer          | TravelMate 8572G            | [3cb180e970](https://linux-hardware.org/?probe=3cb180e970) | Sep 05, 2021 |
| Lenovo        | U310                        | [0be64d0c02](https://linux-hardware.org/?probe=0be64d0c02) | Sep 03, 2021 |
| HP            | Pavilion dv6                | [db6f843983](https://linux-hardware.org/?probe=db6f843983) | Sep 02, 2021 |
| Lenovo        | ThinkPad T490s 20NX003NR... | [972f2ce955](https://linux-hardware.org/?probe=972f2ce955) | Sep 02, 2021 |
| Dell          | Latitude 7400               | [a72ba74a3f](https://linux-hardware.org/?probe=a72ba74a3f) | Sep 02, 2021 |
| Lenovo        | IdeaPad Y580                | [e206f222ab](https://linux-hardware.org/?probe=e206f222ab) | Aug 31, 2021 |
| Dell          | Latitude 7400               | [256ab697f4](https://linux-hardware.org/?probe=256ab697f4) | Aug 31, 2021 |
| HP            | Pavilion g6                 | [5b26455c9d](https://linux-hardware.org/?probe=5b26455c9d) | Aug 30, 2021 |
| Intel         | SandyBridge Platform        | [cde550fde9](https://linux-hardware.org/?probe=cde550fde9) | Aug 30, 2021 |
| VINGA         | Iron S140                   | [8a48730847](https://linux-hardware.org/?probe=8a48730847) | Aug 29, 2021 |
| Lenovo        | G500 20236                  | [63cfcbea30](https://linux-hardware.org/?probe=63cfcbea30) | Aug 27, 2021 |
| Acer          | Swift SF314-59              | [c4ec7d7706](https://linux-hardware.org/?probe=c4ec7d7706) | Aug 27, 2021 |
| Intel         | SandyBridge Platform        | [3b2180f4ae](https://linux-hardware.org/?probe=3b2180f4ae) | Aug 26, 2021 |
| HP            | ProBook 4530s               | [2b4cab4d7c](https://linux-hardware.org/?probe=2b4cab4d7c) | Aug 25, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [54d26d998a](https://linux-hardware.org/?probe=54d26d998a) | Aug 25, 2021 |
| HP            | 630                         | [004d2b364d](https://linux-hardware.org/?probe=004d2b364d) | Aug 25, 2021 |
| HP            | Laptop 15s-fq2xxx           | [f755838fd8](https://linux-hardware.org/?probe=f755838fd8) | Aug 24, 2021 |
| HP            | 250 G4                      | [5d47aa9804](https://linux-hardware.org/?probe=5d47aa9804) | Aug 24, 2021 |
| Dell          | Inspiron 5559               | [bb902b38e1](https://linux-hardware.org/?probe=bb902b38e1) | Aug 24, 2021 |
| Lenovo        | ThinkPad X240 20AL00C6MZ    | [fb0a4dfc32](https://linux-hardware.org/?probe=fb0a4dfc32) | Aug 23, 2021 |
| Acer          | Aspire V3-551               | [9fd29f4a13](https://linux-hardware.org/?probe=9fd29f4a13) | Aug 23, 2021 |
| Acer          | Aspire V3-551               | [7952925c50](https://linux-hardware.org/?probe=7952925c50) | Aug 23, 2021 |
| Lenovo        | G500 20236                  | [a23cf0d12d](https://linux-hardware.org/?probe=a23cf0d12d) | Aug 22, 2021 |
| Acer          | Swift SF314-56G             | [5584375657](https://linux-hardware.org/?probe=5584375657) | Aug 20, 2021 |
| Packard Be... | EasyNote_NJ66               | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| ASUSTek       | G55VW                       | [7daa09d3c3](https://linux-hardware.org/?probe=7daa09d3c3) | Aug 19, 2021 |
| Dell          | Inspiron 3541               | [231f84ef9a](https://linux-hardware.org/?probe=231f84ef9a) | Aug 18, 2021 |
| HP            | 620                         | [c2402bee8f](https://linux-hardware.org/?probe=c2402bee8f) | Aug 18, 2021 |
| HP            | ProBook 650 G2              | [c78497a286](https://linux-hardware.org/?probe=c78497a286) | Aug 17, 2021 |
| HP            | 630                         | [a57ed15001](https://linux-hardware.org/?probe=a57ed15001) | Aug 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | [31fcb375f4](https://linux-hardware.org/?probe=31fcb375f4) | Aug 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d2601ba1b4](https://linux-hardware.org/?probe=d2601ba1b4) | Aug 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [92440ecd49](https://linux-hardware.org/?probe=92440ecd49) | Aug 14, 2021 |
| Lenovo        | G40-30 80FY                 | [883ec5e5c4](https://linux-hardware.org/?probe=883ec5e5c4) | Aug 14, 2021 |
| Dell          | Vostro 15-3568              | [7739bbdcc5](https://linux-hardware.org/?probe=7739bbdcc5) | Aug 13, 2021 |
| HP            | Compaq CQ58                 | [23b1aab5c3](https://linux-hardware.org/?probe=23b1aab5c3) | Aug 13, 2021 |
| Pixus         | Rise                        | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| HP            | ProBook 4530s               | [14a78c65a1](https://linux-hardware.org/?probe=14a78c65a1) | Aug 12, 2021 |
| Dell          | Vostro 15-3568              | [fd1b17a77d](https://linux-hardware.org/?probe=fd1b17a77d) | Aug 11, 2021 |
| HP            | 250 G4                      | [5640b0689d](https://linux-hardware.org/?probe=5640b0689d) | Aug 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | [4ce98656a4](https://linux-hardware.org/?probe=4ce98656a4) | Aug 10, 2021 |
| HP            | 250 G5 Notebook PC          | [99d6dd75ef](https://linux-hardware.org/?probe=99d6dd75ef) | Aug 09, 2021 |
| Lenovo        | G550 20023                  | [d997251cee](https://linux-hardware.org/?probe=d997251cee) | Aug 09, 2021 |
| HP            | EliteBook 8740w             | [3c345bc85c](https://linux-hardware.org/?probe=3c345bc85c) | Aug 09, 2021 |
| Dell          | Latitude E7470              | [1cc51aab6f](https://linux-hardware.org/?probe=1cc51aab6f) | Aug 09, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ca859cbf25](https://linux-hardware.org/?probe=ca859cbf25) | Aug 08, 2021 |
| HP            | Laptop 15s-fq2xxx           | [a89cdf06f5](https://linux-hardware.org/?probe=a89cdf06f5) | Aug 07, 2021 |
| HP            | 630                         | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [2b7700c6d3](https://linux-hardware.org/?probe=2b7700c6d3) | Aug 07, 2021 |
| Dell          | XPS 15 9560                 | [cb3d844d9a](https://linux-hardware.org/?probe=cb3d844d9a) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0db1faaeaf](https://linux-hardware.org/?probe=0db1faaeaf) | Aug 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [268e93bc48](https://linux-hardware.org/?probe=268e93bc48) | Aug 05, 2021 |
| Timi          | TM1612                      | [9c80791f81](https://linux-hardware.org/?probe=9c80791f81) | Aug 04, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0030... | [c4db4594bf](https://linux-hardware.org/?probe=c4db4594bf) | Aug 03, 2021 |
| HP            | Laptop 14-cf3xxx            | [0f4f35c2dc](https://linux-hardware.org/?probe=0f4f35c2dc) | Aug 02, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [847bf89546](https://linux-hardware.org/?probe=847bf89546) | Aug 02, 2021 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [22790f2a7e](https://linux-hardware.org/?probe=22790f2a7e) | Aug 01, 2021 |
| Samsung       | RV408/RV508                 | [20dabc5192](https://linux-hardware.org/?probe=20dabc5192) | Jul 31, 2021 |
| HP            | ZBook 15v G5                | [49ecc85467](https://linux-hardware.org/?probe=49ecc85467) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 429053G       | [5f553465bf](https://linux-hardware.org/?probe=5f553465bf) | Jul 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [829ad54d2c](https://linux-hardware.org/?probe=829ad54d2c) | Jul 27, 2021 |
| Acer          | Aspire V3-551               | [3d4f4e38ce](https://linux-hardware.org/?probe=3d4f4e38ce) | Jul 27, 2021 |
| Acer          | Aspire V3-551               | [a86f57cf53](https://linux-hardware.org/?probe=a86f57cf53) | Jul 27, 2021 |
| Acer          | AOD270                      | [61e7dc1d25](https://linux-hardware.org/?probe=61e7dc1d25) | Jul 26, 2021 |
| ASUSTek       | 701                         | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude 7400               | [0ad7b49f7a](https://linux-hardware.org/?probe=0ad7b49f7a) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Dell          | Vostro 5481                 | [4b9f94e0d0](https://linux-hardware.org/?probe=4b9f94e0d0) | Jul 25, 2021 |
| HP            | Laptop 15-db1xxx            | [97b8085def](https://linux-hardware.org/?probe=97b8085def) | Jul 25, 2021 |
| LG Electro... | S525-L.ACO1R1               | [0af3286dbd](https://linux-hardware.org/?probe=0af3286dbd) | Jul 25, 2021 |
| Acer          | Extensa 7620                | [e0e9a2e532](https://linux-hardware.org/?probe=e0e9a2e532) | Jul 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [aeb61148cb](https://linux-hardware.org/?probe=aeb61148cb) | Jul 21, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [c9a87ca2b2](https://linux-hardware.org/?probe=c9a87ca2b2) | Jul 21, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [67727f3553](https://linux-hardware.org/?probe=67727f3553) | Jul 21, 2021 |
| Acer          | Aspire 7750                 | [1d55be6cb0](https://linux-hardware.org/?probe=1d55be6cb0) | Jul 21, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [be36333f4c](https://linux-hardware.org/?probe=be36333f4c) | Jul 20, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [06f084cc9f](https://linux-hardware.org/?probe=06f084cc9f) | Jul 20, 2021 |
| Dell          | Inspiron 15-3565            | [931f3dd3ce](https://linux-hardware.org/?probe=931f3dd3ce) | Jul 20, 2021 |
| Lenovo        | IdeaPad Z580                | [b6b62cb7e9](https://linux-hardware.org/?probe=b6b62cb7e9) | Jul 19, 2021 |
| ASUSTek       | X705UDR                     | [216de55d6c](https://linux-hardware.org/?probe=216de55d6c) | Jul 18, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [1ffbe324f9](https://linux-hardware.org/?probe=1ffbe324f9) | Jul 17, 2021 |
| Acer          | Aspire 7720                 | [4c7c08aef4](https://linux-hardware.org/?probe=4c7c08aef4) | Jul 17, 2021 |
| ASUSTek       | X550CL                      | [2ac04e226b](https://linux-hardware.org/?probe=2ac04e226b) | Jul 16, 2021 |
| ASUSTek       | X550CL                      | [86f477d984](https://linux-hardware.org/?probe=86f477d984) | Jul 16, 2021 |
| Acer          | AN515-52                    | [7b3eceebae](https://linux-hardware.org/?probe=7b3eceebae) | Jul 15, 2021 |
| Acer          | AN515-52                    | [f75a99b20b](https://linux-hardware.org/?probe=f75a99b20b) | Jul 15, 2021 |
| HP            | ProBook 440 G7              | [3e04f9763c](https://linux-hardware.org/?probe=3e04f9763c) | Jul 15, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ukraine/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 215       | 9.67%   |
| ROSA R10          | 142       | 6.39%   |
| ROSA R11          | 118       | 5.31%   |
| Ubuntu 18.04      | 117       | 5.26%   |
| ROSA R8.1         | 97        | 4.36%   |
| ROSA R9           | 72        | 3.24%   |
| ROSA R11.1        | 68        | 3.06%   |
| ROSA R8           | 61        | 2.74%   |
| Arch Rolling      | 35        | 1.57%   |
| Ubuntu 22.04      | 33        | 1.48%   |
| OpenMandriva 4.2  | 32        | 1.44%   |
| ROSA 12.2         | 31        | 1.39%   |
| Linux Mint 19.3   | 30        | 1.35%   |
| KDE neon 20.04    | 29        | 1.3%    |
| Debian 11         | 27        | 1.21%   |
| Linux Mint 20     | 25        | 1.12%   |
| Arch              | 25        | 1.12%   |
| Manjaro           | 24        | 1.08%   |
| ROSA 12.4         | 23        | 1.03%   |
| Linux Mint 20.2   | 20        | 0.9%    |
| Debian 10         | 19        | 0.85%   |
| Ubuntu 24.04      | 18        | 0.81%   |
| Ubuntu 19.10      | 18        | 0.81%   |
| ROSA 12.5.1       | 18        | 0.81%   |
| Ubuntu 21.10      | 17        | 0.76%   |
| OpenMandriva 4.3  | 17        | 0.76%   |
| Linux Mint 20.1   | 17        | 0.76%   |
| Kubuntu 20.04     | 17        | 0.76%   |
| Linux Mint 19.2   | 16        | 0.72%   |
| Fedora 34         | 16        | 0.72%   |
| ArcoLinux Rolling | 16        | 0.72%   |
| Ubuntu 19.04      | 15        | 0.67%   |
| Debian 12         | 15        | 0.67%   |
| Xubuntu 18.04     | 14        | 0.63%   |
| Ubuntu 21.04      | 14        | 0.63%   |
| Linux Mint 20.3   | 14        | 0.63%   |
| Linux Mint 19.1   | 13        | 0.58%   |
| Linux Mint 18.3   | 13        | 0.58%   |
| Ubuntu 20.10      | 12        | 0.54%   |
| Fedora 33         | 12        | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| ROSA          | 574       | 27.77%  |
| Ubuntu        | 465       | 22.5%   |
| Linux Mint    | 179       | 8.66%   |
| Endless       | 99        | 4.79%   |
| Manjaro       | 92        | 4.45%   |
| OpenMandriva  | 82        | 3.97%   |
| Fedora        | 81        | 3.92%   |
| Debian        | 72        | 3.48%   |
| Arch          | 59        | 2.85%   |
| KDE neon      | 45        | 2.18%   |
| Kubuntu       | 38        | 1.84%   |
| Xubuntu       | 32        | 1.55%   |
| Pop!_OS       | 21        | 1.02%   |
| ArcoLinux     | 17        | 0.82%   |
| Zorin         | 16        | 0.77%   |
| Elementary    | 16        | 0.77%   |
| Gentoo        | 15        | 0.73%   |
| SteamOS       | 12        | 0.58%   |
| openSUSE      | 12        | 0.58%   |
| Lubuntu       | 11        | 0.53%   |
| Kali          | 11        | 0.53%   |
| Ubuntu MATE   | 10        | 0.48%   |
| LMDE          | 9         | 0.44%   |
| Ubuntu Unity  | 8         | 0.39%   |
| EndeavourOS   | 8         | 0.39%   |
| Clear Linux   | 8         | 0.39%   |
| NixOS         | 6         | 0.29%   |
| MX            | 6         | 0.29%   |
| Ubuntu Budgie | 5         | 0.24%   |
| Nobara        | 5         | 0.24%   |
| Devuan        | 5         | 0.24%   |
| Void Linux    | 4         | 0.19%   |
| Red OS        | 4         | 0.19%   |
| Linux Lite    | 4         | 0.19%   |
| CentOS        | 4         | 0.19%   |
| Artix         | 4         | 0.19%   |
| ALT Linux     | 4         | 0.19%   |
| CachyOS       | 3         | 0.15%   |
| UbuntuDDE     | 2         | 0.1%    |
| Solus         | 2         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 57        | 2.43%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 57        | 2.43%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 42        | 1.79%   |
| 5.4.0-42-generic                    | 33        | 1.4%    |
| 5.10.14-desktop-1omv4002            | 32        | 1.36%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 29        | 1.23%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 26        | 1.11%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 25        | 1.06%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 24        | 1.02%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 19        | 0.81%   |
| 5.8.0-14-generic                    | 18        | 0.77%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 18        | 0.77%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 17        | 0.72%   |
| 5.4.0-58-generic                    | 15        | 0.64%   |
| 5.3.0-40-generic                    | 15        | 0.64%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 15        | 0.64%   |
| 4.18.0-15-generic                   | 15        | 0.64%   |
| 4.15.0-desktop-45.1rosa-i586        | 15        | 0.64%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 15        | 0.64%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 15        | 0.64%   |
| 5.4.0-52-generic                    | 14        | 0.6%    |
| 5.16.7-desktop-1omv4003             | 14        | 0.6%    |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 14        | 0.6%    |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 14        | 0.6%    |
| 5.4.0-48-generic                    | 13        | 0.55%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 13        | 0.55%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 13        | 0.55%   |
| 5.4.0-19-generic                    | 12        | 0.51%   |
| 5.3.0-28-generic                    | 12        | 0.51%   |
| 5.4.83-generic-2rosa-x86_64         | 11        | 0.47%   |
| 5.4.0-26-generic                    | 11        | 0.47%   |
| 5.3.0-46-generic                    | 11        | 0.47%   |
| 5.3.0-42-generic                    | 11        | 0.47%   |
| 5.11.0-43-generic                   | 11        | 0.47%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 11        | 0.47%   |
| 5.0.0-32-generic                    | 11        | 0.47%   |
| 5.4.0-91-generic                    | 10        | 0.43%   |
| 5.4.0-65-generic                    | 10        | 0.43%   |
| 5.4.0-29-generic                    | 10        | 0.43%   |
| 5.3.0-51-generic                    | 10        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.4.0    | 272       | 11.91%  |
| 4.15.0   | 267       | 11.69%  |
| 5.8.0    | 100       | 4.38%   |
| 5.3.0    | 93        | 4.07%   |
| 4.9.60   | 82        | 3.59%   |
| 5.11.0   | 69        | 3.02%   |
| 4.9.20   | 69        | 3.02%   |
| 5.0.0    | 60        | 2.63%   |
| 5.15.0   | 52        | 2.28%   |
| 5.13.0   | 49        | 2.15%   |
| 4.18.0   | 45        | 1.97%   |
| 4.1.34   | 44        | 1.93%   |
| 5.10.0   | 33        | 1.44%   |
| 4.9.124  | 33        | 1.44%   |
| 5.10.14  | 32        | 1.4%    |
| 4.9.9    | 32        | 1.4%    |
| 6.8.0    | 30        | 1.31%   |
| 5.10.74  | 27        | 1.18%   |
| 4.19.0   | 27        | 1.18%   |
| 4.1.38   | 27        | 1.18%   |
| 4.9.41   | 23        | 1.01%   |
| 4.9.76   | 20        | 0.88%   |
| 5.4.83   | 19        | 0.83%   |
| 4.13.0   | 19        | 0.83%   |
| 5.16.7   | 17        | 0.74%   |
| 6.1.0    | 16        | 0.7%    |
| 4.9.155  | 16        | 0.7%    |
| 5.4.32   | 14        | 0.61%   |
| 5.19.0   | 14        | 0.61%   |
| 5.10.71  | 11        | 0.48%   |
| 6.2.0    | 10        | 0.44%   |
| 4.9.95   | 10        | 0.44%   |
| 6.14.2   | 9         | 0.39%   |
| 6.11.0   | 9         | 0.39%   |
| 6.1.20   | 9         | 0.39%   |
| 5.10.118 | 9         | 0.39%   |
| 5.9.16   | 8         | 0.35%   |
| 4.1.25   | 8         | 0.35%   |
| 6.6.27   | 7         | 0.31%   |
| 6.5.0    | 7         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 324       | 14.62%  |
| 4.9     | 281       | 12.68%  |
| 4.15    | 267       | 12.05%  |
| 5.10    | 159       | 7.18%   |
| 5.8     | 127       | 5.73%   |
| 5.3     | 102       | 4.6%    |
| 5.11    | 84        | 3.79%   |
| 5.15    | 82        | 3.7%    |
| 4.1     | 76        | 3.43%   |
| 5.13    | 67        | 3.02%   |
| 5.0     | 62        | 2.8%    |
| 6.1     | 52        | 2.35%   |
| 4.18    | 46        | 2.08%   |
| 6.8     | 37        | 1.67%   |
| 4.19    | 35        | 1.58%   |
| 5.16    | 33        | 1.49%   |
| 6.6     | 31        | 1.4%    |
| 5.14    | 27        | 1.22%   |
| 6.12    | 26        | 1.17%   |
| 5.6     | 25        | 1.13%   |
| 4.13    | 20        | 0.9%    |
| 6.2     | 19        | 0.86%   |
| 5.9     | 19        | 0.86%   |
| 6.14    | 18        | 0.81%   |
| 5.12    | 17        | 0.77%   |
| 5.19    | 16        | 0.72%   |
| 6.5     | 15        | 0.68%   |
| 6.11    | 15        | 0.68%   |
| 6.10    | 13        | 0.59%   |
| 5.17    | 13        | 0.59%   |
| 5.5     | 12        | 0.54%   |
| 6.4     | 11        | 0.5%    |
| 4.14    | 9         | 0.41%   |
| 6.0     | 8         | 0.36%   |
| 5.7     | 7         | 0.32%   |
| 4.4     | 7         | 0.32%   |
| 6.9     | 5         | 0.23%   |
| 5.18    | 5         | 0.23%   |
| 5.2     | 4         | 0.18%   |
| 5.1     | 4         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1824      | 90.07%  |
| i686    | 200       | 9.88%   |
| aarch64 | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 616       | 29.11%  |
| KDE4             | 368       | 17.39%  |
| KDE5             | 351       | 16.59%  |
| Unknown          | 236       | 11.15%  |
| XFCE             | 115       | 5.43%   |
| X-Cinnamon       | 80        | 3.78%   |
| MATE             | 61        | 2.88%   |
| Cinnamon         | 59        | 2.79%   |
| KDE              | 57        | 2.69%   |
| LXQt             | 54        | 2.55%   |
| KDE6             | 39        | 1.84%   |
| i3               | 15        | 0.71%   |
| Pantheon         | 14        | 0.66%   |
| Unity            | 8         | 0.38%   |
| LXDE             | 7         | 0.33%   |
| GNOME Flashback  | 5         | 0.24%   |
| Budgie           | 5         | 0.24%   |
| Hyprland         | 4         | 0.19%   |
| Deepin           | 4         | 0.19%   |
| openbox          | 3         | 0.14%   |
| GNOME Classic    | 3         | 0.14%   |
| xmonad           | 2         | 0.09%   |
| bspwm            | 2         | 0.09%   |
| qtile            | 1         | 0.05%   |
| none+i3          | 1         | 0.05%   |
| lightdm-xsession | 1         | 0.05%   |
| KDE:KDE-Wayland  | 1         | 0.05%   |
| i3-with-shmlog   | 1         | 0.05%   |
| fluxbox          | 1         | 0.05%   |
| Enlightenment    | 1         | 0.05%   |
| Endless:GNOME    | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1623      | 78.86%  |
| Wayland | 302       | 14.67%  |
| Unknown | 126       | 6.12%   |
| Tty     | 7         | 0.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 730       | 34.56%  |
| SDDM    | 397       | 18.8%   |
| KDM     | 369       | 17.47%  |
| GDM     | 256       | 12.12%  |
| LightDM | 149       | 7.05%   |
| TDM     | 112       | 5.3%    |
| GDM3    | 82        | 3.88%   |
| MDM     | 6         | 0.28%   |
| XDM     | 5         | 0.24%   |
| SLiM    | 2         | 0.09%   |
| GREETD  | 2         | 0.09%   |
| LY-DM   | 1         | 0.05%   |
| LXDM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 672       | 32.29%  |
| en_US       | 544       | 26.14%  |
| ru_RU       | 369       | 17.73%  |
| ru_UA       | 278       | 13.36%  |
| uk_UA       | 144       | 6.92%   |
| C           | 36        | 1.73%   |
| en_GB       | 17        | 0.82%   |
| ru_RU.UTF_8 | 7         | 0.34%   |
| en_CA       | 3         | 0.14%   |
| hu_HU       | 2         | 0.1%    |
| es_ES       | 2         | 0.1%    |
| POSIX       | 1         | 0.05%   |
| fr_FR       | 1         | 0.05%   |
| en_ZA       | 1         | 0.05%   |
| en_IE       | 1         | 0.05%   |
| en_AG       | 1         | 0.05%   |
| de_DE       | 1         | 0.05%   |
| C.UTF8      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1085      | 52.72%  |
| EFI  | 973       | 47.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1399      | 67.23%  |
| Unknown | 382       | 18.36%  |
| Btrfs   | 155       | 7.45%   |
| Overlay | 89        | 4.28%   |
| Tmpfs   | 25        | 1.2%    |
| Xfs     | 11        | 0.53%   |
| Zfs     | 9         | 0.43%   |
| Ext3    | 6         | 0.29%   |
| Ext2    | 3         | 0.14%   |
| F2fs    | 2         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 876       | 41.99%  |
| GPT     | 702       | 33.65%  |
| MBR     | 508       | 24.35%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1807      | 87.85%  |
| Yes       | 250       | 12.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1491      | 71.65%  |
| Yes       | 590       | 28.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 431       | 21.38%  |
| Hewlett-Packard      | 394       | 19.54%  |
| ASUSTek Computer     | 375       | 18.6%   |
| Acer                 | 266       | 13.19%  |
| Dell                 | 209       | 10.37%  |
| Samsung Electronics  | 64        | 3.17%   |
| Timi                 | 30        | 1.49%   |
| MSI                  | 30        | 1.49%   |
| Toshiba              | 25        | 1.24%   |
| Apple                | 18        | 0.89%   |
| Fujitsu              | 13        | 0.64%   |
| Sony                 | 12        | 0.6%    |
| Valve                | 11        | 0.55%   |
| eMachines            | 11        | 0.55%   |
| Packard Bell         | 8         | 0.4%    |
| Fujitsu Siemens      | 8         | 0.4%    |
| Unknown              | 8         | 0.4%    |
| HUAWEI               | 6         | 0.3%    |
| Gigabyte Technology  | 6         | 0.3%    |
| Google               | 5         | 0.25%   |
| VINGA                | 4         | 0.2%    |
| HONOR                | 4         | 0.2%    |
| Chuwi                | 4         | 0.2%    |
| TECNO Mobile Limited | 3         | 0.15%   |
| Shuttle              | 3         | 0.15%   |
| Notebook             | 3         | 0.15%   |
| Navigator            | 3         | 0.15%   |
| Medion               | 3         | 0.15%   |
| THUNDEROBOT          | 2         | 0.1%    |
| Razer                | 2         | 0.1%    |
| Prestigio            | 2         | 0.1%    |
| Pixus                | 2         | 0.1%    |
| Minix                | 2         | 0.1%    |
| LG Electronics       | 2         | 0.1%    |
| Irbis                | 2         | 0.1%    |
| ICL                  | 2         | 0.1%    |
| Hampoo               | 2         | 0.1%    |
| Gateway              | 2         | 0.1%    |
| Dream Machines       | 2         | 0.1%    |
| DEXP                 | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Pavilion g6                             | 24        | 1.19%   |
| Unknown                                    | 16        | 0.79%   |
| Lenovo G500 20236                          | 13        | 0.64%   |
| HP Pavilion dv6                            | 12        | 0.6%    |
| HP Pavilion 15                             | 12        | 0.6%    |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 12        | 0.6%    |
| Lenovo G580 20150                          | 8         | 0.4%    |
| Acer Aspire V3-571G                        | 8         | 0.4%    |
| Valve Jupiter                              | 7         | 0.35%   |
| Lenovo V580c 20160                         | 7         | 0.35%   |
| Lenovo IdeaPad Z580                        | 7         | 0.35%   |
| Lenovo IdeaPad Z510 20287                  | 7         | 0.35%   |
| Lenovo G550 20023                          | 7         | 0.35%   |
| HP 250 G5 Notebook PC                      | 7         | 0.35%   |
| Samsung R59P/R60P/R61P                     | 6         | 0.3%    |
| Samsung R528/R728                          | 6         | 0.3%    |
| Lenovo G580 20157                          | 6         | 0.3%    |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 6         | 0.3%    |
| HP Pavilion g7                             | 6         | 0.3%    |
| HP Notebook                                | 6         | 0.3%    |
| HP Laptop 15-bw0xx                         | 6         | 0.3%    |
| HP 620                                     | 6         | 0.3%    |
| HP 255 G7 Notebook PC                      | 6         | 0.3%    |
| HP 250 G4                                  | 6         | 0.3%    |
| ASUS VivoBook 15_ASUS Laptop X540UBR       | 6         | 0.3%    |
| Lenovo S10-3                               | 5         | 0.25%   |
| Lenovo IdeaPad S340-14API 81NB             | 5         | 0.25%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 5         | 0.25%   |
| HP ZBook 15v G5                            | 5         | 0.25%   |
| HP ProBook 650 G1                          | 5         | 0.25%   |
| HP ProBook 450 G7                          | 5         | 0.25%   |
| HP ProBook 450 G6                          | 5         | 0.25%   |
| HP ProBook 440 G7                          | 5         | 0.25%   |
| HP Laptop 15s-eq1xxx                       | 5         | 0.25%   |
| HP 250 G6 Notebook PC                      | 5         | 0.25%   |
| Dell Vostro 15-3568                        | 5         | 0.25%   |
| Dell Inspiron N5010                        | 5         | 0.25%   |
| Dell Inspiron 3582                         | 5         | 0.25%   |
| Dell Inspiron 3576                         | 5         | 0.25%   |
| Dell Inspiron 3521                         | 5         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 160       | 7.94%   |
| Lenovo IdeaPad        | 136       | 6.75%   |
| Lenovo ThinkPad       | 118       | 5.85%   |
| HP Pavilion           | 96        | 4.76%   |
| HP ProBook            | 95        | 4.71%   |
| ASUS VivoBook         | 94        | 4.66%   |
| Dell Inspiron         | 88        | 4.37%   |
| Dell Latitude         | 55        | 2.73%   |
| HP Laptop             | 45        | 2.23%   |
| Acer Swift            | 32        | 1.59%   |
| HP EliteBook          | 30        | 1.49%   |
| HP 250                | 26        | 1.29%   |
| Dell Vostro           | 26        | 1.29%   |
| HP ZBook              | 24        | 1.19%   |
| Toshiba Satellite     | 20        | 0.99%   |
| Lenovo Legion         | 18        | 0.89%   |
| Acer TravelMate       | 17        | 0.84%   |
| Acer Nitro            | 17        | 0.84%   |
| Acer Extensa          | 17        | 0.84%   |
| HP Compaq             | 16        | 0.79%   |
| ASUS ROG              | 16        | 0.79%   |
| Unknown               | 16        | 0.79%   |
| Lenovo ThinkBook      | 15        | 0.74%   |
| Lenovo G580           | 15        | 0.74%   |
| HP 255                | 14        | 0.69%   |
| Lenovo G500           | 13        | 0.64%   |
| Timi RedmiBook        | 12        | 0.6%    |
| Fujitsu LIFEBOOK      | 12        | 0.6%    |
| Dell Precision        | 12        | 0.6%    |
| Dell XPS              | 11        | 0.55%   |
| ASUS ASUS             | 11        | 0.55%   |
| HP Presario           | 8         | 0.4%    |
| Valve Jupiter         | 7         | 0.35%   |
| Packard Bell EasyNote | 7         | 0.35%   |
| Lenovo V580c          | 7         | 0.35%   |
| Lenovo G550           | 7         | 0.35%   |
| Lenovo B590           | 7         | 0.35%   |
| ASUS ZenBook          | 7         | 0.35%   |
| Samsung R59P          | 6         | 0.3%    |
| Samsung R528          | 6         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 208       | 10.32%  |
| 2011    | 202       | 10.02%  |
| 2018    | 179       | 8.88%   |
| 2019    | 166       | 8.23%   |
| 2017    | 155       | 7.69%   |
| 2013    | 151       | 7.49%   |
| 2010    | 134       | 6.65%   |
| 2020    | 131       | 6.5%    |
| 2015    | 97        | 4.81%   |
| 2021    | 95        | 4.71%   |
| 2016    | 92        | 4.56%   |
| 2009    | 82        | 4.07%   |
| 2007    | 68        | 3.37%   |
| 2014    | 67        | 3.32%   |
| 2008    | 67        | 3.32%   |
| 2023    | 38        | 1.88%   |
| 2022    | 33        | 1.64%   |
| 2006    | 27        | 1.34%   |
| 2005    | 11        | 0.55%   |
| 2024    | 9         | 0.45%   |
| 2025    | 3         | 0.15%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2016      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1896      | 93.54%  |
| Enabled  | 131       | 6.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2008      | 99.6%   |
| Yes  | 8         | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 545       | 26.59%  |
| 3.01-4.0    | 494       | 24.1%   |
| 8.01-16.0   | 322       | 15.71%  |
| 16.01-24.0  | 284       | 13.85%  |
| 1.01-2.0    | 174       | 8.49%   |
| 2.01-3.0    | 93        | 4.54%   |
| 32.01-64.0  | 85        | 4.15%   |
| 0.51-1.0    | 24        | 1.17%   |
| 24.01-32.0  | 16        | 0.78%   |
| 64.01-256.0 | 9         | 0.44%   |
| 0.01-0.5    | 4         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 719       | 32.4%   |
| 2.01-3.0   | 472       | 21.27%  |
| 0.51-1.0   | 355       | 16%     |
| 4.01-8.0   | 298       | 13.43%  |
| 3.01-4.0   | 236       | 10.64%  |
| 8.01-16.0  | 86        | 3.88%   |
| 0.01-0.5   | 43        | 1.94%   |
| 16.01-24.0 | 7         | 0.32%   |
| Unknown    | 2         | 0.09%   |
| 24.01-32.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1567      | 76.51%  |
| 2      | 421       | 20.56%  |
| 3      | 41        | 2%      |
| 0      | 12        | 0.59%   |
| 4      | 6         | 0.29%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1285      | 63.36%  |
| Yes       | 743       | 36.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1695      | 83.91%  |
| No        | 325       | 16.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1977      | 98.07%  |
| No        | 39        | 1.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1535      | 75.17%  |
| No        | 507       | 24.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ukraine | 2016      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Kyiv            | 522       | 24.82%  |
| Kharkiv         | 121       | 5.75%   |
| Simferopol      | 100       | 4.76%   |
| Lviv            | 92        | 4.37%   |
| Dnipro          | 89        | 4.23%   |
| Sevastopol      | 84        | 3.99%   |
| Odessa          | 84        | 3.99%   |
| Donetsk         | 62        | 2.95%   |
| Zaporizhzhya    | 29        | 1.38%   |
| Vinnytsia       | 28        | 1.33%   |
| Ternopil        | 27        | 1.28%   |
| Mykolayiv       | 26        | 1.24%   |
| Cherkasy        | 24        | 1.14%   |
| Zaporizhzhia    | 23        | 1.09%   |
| Poltava         | 21        | 1%      |
| Mariupol        | 21        | 1%      |
| Chernihiv       | 21        | 1%      |
| Odesa           | 20        | 0.95%   |
| Kryvyi Rih      | 20        | 0.95%   |
| Ivano-Frankivsk | 20        | 0.95%   |
| Yalta           | 18        | 0.86%   |
| Kremenchug      | 17        | 0.81%   |
| Kherson         | 17        | 0.81%   |
| Luhansk         | 14        | 0.67%   |
| Yasinovataya    | 13        | 0.62%   |
| Sumy            | 13        | 0.62%   |
| Horlivka        | 13        | 0.62%   |
| Zhytomyr        | 12        | 0.57%   |
| Rivne           | 12        | 0.57%   |
| Irpin           | 12        | 0.57%   |
| Uzhhorod        | 11        | 0.52%   |
| Novopskov       | 11        | 0.52%   |
| Mykytyn Rog     | 10        | 0.48%   |
| Yevpatoriya     | 9         | 0.43%   |
| Pavlohrad       | 9         | 0.43%   |
| Kramatorsk      | 9         | 0.43%   |
| Syeverodonets'k | 8         | 0.38%   |
| Osipenko        | 8         | 0.38%   |
| Myrnohrad       | 8         | 0.38%   |
| Kamianske       | 8         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 367       | 456    | 14.78%  |
| WDC                         | 342       | 405    | 13.77%  |
| Samsung Electronics         | 303       | 369    | 12.2%   |
| Toshiba                     | 225       | 280    | 9.06%   |
| Kingston                    | 155       | 181    | 6.24%   |
| Hitachi                     | 134       | 171    | 5.4%    |
| Unknown                     | 111       | 135    | 4.47%   |
| SK hynix                    | 92        | 109    | 3.71%   |
| HGST                        | 90        | 113    | 3.62%   |
| SanDisk                     | 82        | 100    | 3.3%    |
| Intel                       | 72        | 93     | 2.9%    |
| Micron Technology           | 57        | 73     | 2.3%    |
| GOODRAM                     | 42        | 46     | 1.69%   |
| KIOXIA                      | 28        | 35     | 1.13%   |
| Apacer                      | 28        | 29     | 1.13%   |
| Patriot                     | 23        | 27     | 0.93%   |
| Transcend                   | 22        | 27     | 0.89%   |
| China                       | 20        | 22     | 0.81%   |
| A-DATA Technology           | 20        | 22     | 0.81%   |
| Crucial                     | 19        | 20     | 0.77%   |
| SPCC                        | 18        | 23     | 0.72%   |
| LITEON                      | 14        | 16     | 0.56%   |
| Kingston Technology Company | 14        | 15     | 0.56%   |
| Team                        | 12        | 12     | 0.48%   |
| Apple                       | 12        | 15     | 0.48%   |
| JMicron Technology          | 10        | 9      | 0.4%    |
| Phison Electronics          | 9         | 9      | 0.36%   |
| Fujitsu                     | 9         | 12     | 0.36%   |
| Silicon Motion              | 7         | 8      | 0.28%   |
| LITEONIT                    | 7         | 8      | 0.28%   |
| KingSpec                    | 7         | 8      | 0.28%   |
| StoreJet                    | 6         | 6      | 0.24%   |
| OCZ                         | 6         | 6      | 0.24%   |
| AMD                         | 6         | 8      | 0.24%   |
| Phison                      | 5         | 7      | 0.2%    |
| Gigabyte Technology         | 5         | 6      | 0.2%    |
| Yangtze Memory Technologies | 4         | 5      | 0.16%   |
| UMIS                        | 4         | 4      | 0.16%   |
| Plextor                     | 4         | 5      | 0.16%   |
| Netac                       | 4         | 4      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 69        | 2.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 53        | 2.08%   |
| Toshiba MQ01ABF050 500GB                          | 46        | 1.8%    |
| Seagate ST9500325AS 500GB                         | 34        | 1.33%   |
| Seagate ST500LT012-1DG142 500GB                   | 34        | 1.33%   |
| Toshiba MQ01ABD100 1TB                            | 30        | 1.18%   |
| Toshiba MQ04ABF100 1TB                            | 23        | 0.9%    |
| Kingston SA400S37240G 240GB SSD                   | 22        | 0.86%   |
| HGST HTS545050A7E680 500GB                        | 19        | 0.74%   |
| Samsung NVMe SSD Drive 256GB                      | 18        | 0.71%   |
| Kingston SA400S37120G 120GB SSD                   | 18        | 0.71%   |
| HGST HTS721010A9E630 1TB                          | 17        | 0.67%   |
| Seagate ST9320325AS 320GB                         | 16        | 0.63%   |
| Seagate ST500LT012-9WS142 500GB                   | 16        | 0.63%   |
| Hitachi HTS543232A7A384 320GB                     | 15        | 0.59%   |
| Unknown MMC Card  64GB                            | 14        | 0.55%   |
| Intel NVMe SSD Drive 512GB                        | 13        | 0.51%   |
| Hitachi HTS545032B9A300 320GB                     | 13        | 0.51%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 12        | 0.47%   |
| SK hynix NVMe SSD Drive 256GB                     | 12        | 0.47%   |
| Seagate ST9250315AS 250GB                         | 12        | 0.47%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 12        | 0.47%   |
| Samsung SSD 860 EVO 250GB                         | 12        | 0.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 12        | 0.47%   |
| Patriot Burst 120GB SSD                           | 12        | 0.47%   |
| HGST HTS545050A7E380 500GB                        | 12        | 0.47%   |
| GOODRAM SSD 120GB                                 | 12        | 0.47%   |
| WDC WD5000LPCX-24VHAT0 500GB                      | 11        | 0.43%   |
| WDC WD3200BPVT-22JJ5T0 320GB                      | 11        | 0.43%   |
| Unknown MMC Card  32GB                            | 11        | 0.43%   |
| Samsung SSD 860 EVO 500GB                         | 11        | 0.43%   |
| Samsung NVMe SSD Drive 512GB                      | 11        | 0.43%   |
| Hitachi HTS545050B9A300 500GB                     | 11        | 0.43%   |
| Hitachi HTS545050A7E380 500GB                     | 11        | 0.43%   |
| HGST HTS541010A9E680 1TB                          | 11        | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                      | 10        | 0.39%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD               | 10        | 0.39%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 9         | 0.35%   |
| Toshiba MQ01ABD050 500GB                          | 9         | 0.35%   |
| SK hynix NVMe SSD Drive 512GB                     | 9         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 365       | 451    | 32.44%  |
| WDC                 | 287       | 328    | 25.51%  |
| Toshiba             | 187       | 233    | 16.62%  |
| Hitachi             | 134       | 171    | 11.91%  |
| HGST                | 90        | 113    | 8%      |
| Samsung Electronics | 33        | 40     | 2.93%   |
| Fujitsu             | 9         | 12     | 0.8%    |
| JMicron Technology  | 6         | 6      | 0.53%   |
| USB3.0              | 3         | 3      | 0.27%   |
| Unknown             | 2         | 3      | 0.18%   |
| HGST HTS            | 2         | 2      | 0.18%   |
| Apple               | 2         | 2      | 0.18%   |
| USB                 | 1         | 1      | 0.09%   |
| StoreJet            | 1         | 1      | 0.09%   |
| SILICONMOTION       | 1         | 1      | 0.09%   |
| SAGE                | 1         | 1      | 0.09%   |
| IBM/Hitachi         | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 131       | 162    | 18.85%  |
| Kingston            | 120       | 141    | 17.27%  |
| SanDisk             | 40        | 49     | 5.76%   |
| GOODRAM             | 40        | 44     | 5.76%   |
| Apacer              | 27        | 28     | 3.88%   |
| SK hynix            | 26        | 32     | 3.74%   |
| Micron Technology   | 25        | 29     | 3.6%    |
| Patriot             | 23        | 27     | 3.31%   |
| Transcend           | 20        | 25     | 2.88%   |
| Intel               | 20        | 25     | 2.88%   |
| China               | 20        | 22     | 2.88%   |
| Crucial             | 19        | 20     | 2.73%   |
| SPCC                | 18        | 23     | 2.59%   |
| A-DATA Technology   | 18        | 20     | 2.59%   |
| WDC                 | 16        | 20     | 2.3%    |
| LITEON              | 13        | 15     | 1.87%   |
| Team                | 12        | 12     | 1.73%   |
| Toshiba             | 10        | 15     | 1.44%   |
| Apple               | 8         | 8      | 1.15%   |
| LITEONIT            | 7         | 8      | 1.01%   |
| OCZ                 | 6         | 6      | 0.86%   |
| StoreJet            | 5         | 5      | 0.72%   |
| KingSpec            | 5         | 6      | 0.72%   |
| Gigabyte Technology | 5         | 6      | 0.72%   |
| AMD                 | 5         | 7      | 0.72%   |
| Plextor             | 3         | 4      | 0.43%   |
| Netac               | 3         | 3      | 0.43%   |
| Leven               | 3         | 3      | 0.43%   |
| Indilinx            | 3         | 3      | 0.43%   |
| Verbatim            | 2         | 2      | 0.29%   |
| Unknown             | 2         | 2      | 0.29%   |
| KingDian            | 2         | 2      | 0.29%   |
| DeTech              | 2         | 3      | 0.29%   |
| BIWIN               | 2         | 2      | 0.29%   |
| XrayDisk            | 1         | 1      | 0.14%   |
| WHALEKOM            | 1         | 1      | 0.14%   |
| UNIC2               | 1         | 1      | 0.14%   |
| Teclast             | 1         | 1      | 0.14%   |
| SSSTC               | 1         | 1      | 0.14%   |
| SILICONMOTION       | 1         | 2      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1094      | 1369   | 45.6%   |
| SSD     | 655       | 816    | 27.3%   |
| NVMe    | 528       | 662    | 22.01%  |
| MMC     | 103       | 129    | 4.29%   |
| Unknown | 19        | 19     | 0.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1526      | 2153   | 69.21%  |
| NVMe | 528       | 662    | 23.95%  |
| MMC  | 103       | 129    | 4.67%   |
| SAS  | 48        | 51     | 2.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1216      | 1598   | 72.12%  |
| 0.51-1.0   | 444       | 555    | 26.33%  |
| 1.01-2.0   | 24        | 29     | 1.42%   |
| 3.01-4.0   | 1         | 2      | 0.06%   |
| 4.01-10.0  | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 617       | 28.74%  |
| 251-500        | 589       | 27.43%  |
| 501-1000       | 285       | 13.27%  |
| 51-100         | 184       | 8.57%   |
| 1-20           | 180       | 8.38%   |
| 21-50          | 156       | 7.27%   |
| 1001-2000      | 81        | 3.77%   |
| Unknown        | 32        | 1.49%   |
| More than 3000 | 13        | 0.61%   |
| 2001-3000      | 10        | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 979       | 44.78%  |
| 21-50          | 397       | 18.16%  |
| 51-100         | 271       | 12.4%   |
| 101-250        | 260       | 11.89%  |
| 251-500        | 150       | 6.86%   |
| 501-1000       | 75        | 3.43%   |
| Unknown        | 32        | 1.46%   |
| 1001-2000      | 14        | 0.64%   |
| More than 3000 | 4         | 0.18%   |
| 2001-3000      | 2         | 0.09%   |
| 0              | 2         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 19        | 22     | 4.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 15        | 23     | 3.89%   |
| Hitachi HTS543232A7A384 320GB       | 12        | 13     | 3.11%   |
| Seagate ST9320325AS 320GB           | 11        | 11     | 2.85%   |
| Seagate ST500LT012-1DG142 500GB     | 11        | 13     | 2.85%   |
| Seagate ST500LT012-9WS142 500GB     | 10        | 12     | 2.59%   |
| Seagate ST9250315AS 250GB           | 8         | 9      | 2.07%   |
| HGST HTS545050A7E680 500GB          | 7         | 9      | 1.81%   |
| Toshiba MQ01ABD050 500GB            | 6         | 8      | 1.55%   |
| Hitachi HTS545032B9A300 320GB       | 6         | 8      | 1.55%   |
| Toshiba MQ01ABD100 1TB              | 5         | 5      | 1.3%    |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 6      | 1.3%    |
| Hitachi HTS545050A7E380 500GB       | 5         | 5      | 1.3%    |
| Hitachi HTS542516K9SA00 160GB       | 5         | 5      | 1.3%    |
| HGST HTS545050A7E380 500GB          | 5         | 5      | 1.3%    |
| WDC WD5000BEVT-22A0RT0 500GB        | 4         | 5      | 1.04%   |
| WDC WD3200BEVT-22A23T0 320GB        | 4         | 4      | 1.04%   |
| Seagate ST9500420AS 500GB           | 4         | 4      | 1.04%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 4         | 4      | 1.04%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 7      | 1.04%   |
| Seagate ST320LT020-9YG142 320GB     | 4         | 5      | 1.04%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 5      | 1.04%   |
| Hitachi HTS541612J9SA00 120GB       | 4         | 4      | 1.04%   |
| WDC WD3200BEVT-60A23T0 320GB        | 3         | 3      | 0.78%   |
| Toshiba MK2555GSX 250GB             | 3         | 3      | 0.78%   |
| Seagate ST9160821AS 160GB           | 3         | 3      | 0.78%   |
| Seagate ST1000LM014-1EJ164 1TB      | 3         | 4      | 0.78%   |
| Samsung Electronics HM160HI 160GB   | 3         | 3      | 0.78%   |
| Hitachi HTS543232L9A300 320GB       | 3         | 4      | 0.78%   |
| HGST HTS541010A9E680 1TB            | 3         | 4      | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 2      | 0.52%   |
| WDC WD6400BPVT-80HXZT3 640GB        | 2         | 2      | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.52%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 3      | 0.52%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 2         | 2      | 0.52%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 2         | 2      | 0.52%   |
| WDC WD3200BPVT-16JJ5T0 320GB        | 2         | 2      | 0.52%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 2      | 0.52%   |
| WDC WD2500BEVT-60A23T0 250GB        | 2         | 2      | 0.52%   |
| WDC WD10JPVX-60JC3T0 1TB            | 2         | 2      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 131       | 159    | 34.03%  |
| Hitachi                     | 69        | 94     | 17.92%  |
| WDC                         | 68        | 75     | 17.66%  |
| Toshiba                     | 44        | 55     | 11.43%  |
| HGST                        | 17        | 21     | 4.42%   |
| Samsung Electronics         | 15        | 16     | 3.9%    |
| SanDisk                     | 5         | 7      | 1.3%    |
| SK hynix                    | 4         | 4      | 1.04%   |
| A-DATA Technology           | 4         | 4      | 1.04%   |
| Kingston                    | 3         | 4      | 0.78%   |
| Fujitsu                     | 3         | 6      | 0.78%   |
| OCZ                         | 2         | 2      | 0.52%   |
| LITEON                      | 2         | 3      | 0.52%   |
| Crucial                     | 2         | 2      | 0.52%   |
| China                       | 2         | 2      | 0.52%   |
| Team                        | 1         | 1      | 0.26%   |
| Patriot                     | 1         | 1      | 0.26%   |
| Netac                       | 1         | 1      | 0.26%   |
| Micron Technology           | 1         | 1      | 0.26%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.26%   |
| LS                          | 1         | 1      | 0.26%   |
| LITEONIT                    | 1         | 1      | 0.26%   |
| KingSpec                    | 1         | 1      | 0.26%   |
| JDa                         | 1         | 1      | 0.26%   |
| IBM/Hitachi                 | 1         | 1      | 0.26%   |
| HGST HTS                    | 1         | 1      | 0.26%   |
| DeTech                      | 1         | 1      | 0.26%   |
| Apple                       | 1         | 1      | 0.26%   |
| ADATA Technology            | 1         | 1      | 0.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 131       | 159    | 38.08%  |
| Hitachi             | 69        | 94     | 20.06%  |
| WDC                 | 66        | 73     | 19.19%  |
| Toshiba             | 44        | 55     | 12.79%  |
| HGST                | 17        | 21     | 4.94%   |
| Samsung Electronics | 12        | 13     | 3.49%   |
| Fujitsu             | 3         | 6      | 0.87%   |
| IBM/Hitachi         | 1         | 1      | 0.29%   |
| HGST HTS            | 1         | 1      | 0.29%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 338       | 423    | 89.18%  |
| SSD  | 36        | 40     | 9.5%    |
| NVMe | 5         | 5      | 1.32%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 2         | 4      | 22.22%  |
| WDC WD3200BEVT-24A23T0 320GB          | 1         | 1      | 11.11%  |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 1      | 11.11%  |
| Toshiba MK1059GSM 1TB                 | 1         | 1      | 11.11%  |
| Seagate ST9250315AS 250GB             | 1         | 1      | 11.11%  |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 11.11%  |
| Samsung Electronics SSD PM800 TM 64GB | 1         | 1      | 11.11%  |
| Intel SSDSC2KB960G8 960GB             | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 6      | 44.44%  |
| WDC                 | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Intel               | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 943       | 1286   | 42.96%  |
| Detected | 868       | 1230   | 39.54%  |
| Malfunc  | 375       | 468    | 17.08%  |
| Failed   | 9         | 11     | 0.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1478      | 64.18%  |
| AMD                              | 298       | 12.94%  |
| Samsung Electronics              | 152       | 6.6%    |
| SanDisk                          | 79        | 3.43%   |
| SK hynix                         | 64        | 2.78%   |
| Kingston Technology Company      | 47        | 2.04%   |
| Micron Technology                | 33        | 1.43%   |
| KIOXIA                           | 30        | 1.3%    |
| Toshiba America Info Systems     | 28        | 1.22%   |
| Phison Electronics               | 15        | 0.65%   |
| Union Memory (Shenzhen)          | 12        | 0.52%   |
| Nvidia                           | 11        | 0.48%   |
| Silicon Motion                   | 9         | 0.39%   |
| ADATA Technology                 | 8         | 0.35%   |
| Silicon Integrated Systems [SiS] | 7         | 0.3%    |
| Yangtze Memory Technologies      | 5         | 0.22%   |
| Shenzhen Longsys Electronics     | 5         | 0.22%   |
| Lite-On Technology               | 4         | 0.17%   |
| VIA Technologies                 | 3         | 0.13%   |
| Solid State Storage Technology   | 3         | 0.13%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.13%   |
| Transcend                        | 2         | 0.09%   |
| Realtek Semiconductor            | 2         | 0.09%   |
| Micron/Crucial Technology        | 2         | 0.09%   |
| Netac Technology                 | 1         | 0.04%   |
| JMicron Technology               | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 212       | 8.46%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 203       | 8.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 180       | 7.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 124       | 4.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 87        | 3.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 82        | 3.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 64        | 2.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 63        | 2.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 56        | 2.23%   |
| Intel Volume Management Device NVMe RAID Controller                              | 51        | 2.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 51        | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 51        | 2.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 46        | 1.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 46        | 1.84%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 41        | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 38        | 1.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 37        | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 37        | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 36        | 1.44%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 35        | 1.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 31        | 1.24%   |
| Intel SSD 660P Series                                                            | 29        | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 29        | 1.16%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 28        | 1.12%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 28        | 1.12%   |
| AMD SB600 IDE                                                                    | 28        | 1.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 27        | 1.08%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 26        | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                            | 26        | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 24        | 0.96%   |
| SK hynix BC511 NVMe SSD                                                          | 23        | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 21        | 0.84%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 19        | 0.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 19        | 0.76%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 17        | 0.68%   |
| Intel Tiger Lake-LP SATA Controller                                              | 17        | 0.68%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD [E8]                              | 16        | 0.64%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 15        | 0.6%    |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 15        | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 13        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1534      | 63.34%  |
| NVMe | 535       | 22.09%  |
| IDE  | 204       | 8.42%   |
| RAID | 149       | 6.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1637      | 81.2%   |
| AMD     | 378       | 18.75%  |
| Unknown | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 38        | 1.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 36        | 1.78%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 27        | 1.34%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 27        | 1.34%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 26        | 1.29%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 1.24%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 24        | 1.19%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 24        | 1.19%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 23        | 1.14%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 21        | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 21        | 1.04%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 20        | 0.99%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 19        | 0.94%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 18        | 0.89%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 18        | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 17        | 0.84%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 17        | 0.84%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 16        | 0.79%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 15        | 0.74%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 15        | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 0.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 0.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 14        | 0.69%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 14        | 0.69%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 14        | 0.69%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 14        | 0.69%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 13        | 0.64%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 13        | 0.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 13        | 0.64%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 13        | 0.64%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 12        | 0.59%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 12        | 0.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 0.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 11        | 0.55%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 11        | 0.55%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 11        | 0.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 0.55%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 11        | 0.55%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 11        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 403       | 19.97%  |
| Intel Core i7                  | 295       | 14.62%  |
| Intel Core i3                  | 231       | 11.45%  |
| Intel Celeron                  | 148       | 7.33%   |
| Intel Pentium                  | 142       | 7.04%   |
| Other                          | 116       | 5.75%   |
| AMD Ryzen 5                    | 78        | 3.87%   |
| Intel Core 2 Duo               | 77        | 3.82%   |
| Intel Atom                     | 72        | 3.57%   |
| AMD Ryzen 7                    | 58        | 2.87%   |
| Intel Pentium Silver           | 29        | 1.44%   |
| Intel Pentium Dual-Core        | 29        | 1.44%   |
| AMD A6                         | 29        | 1.44%   |
| Intel Core 2                   | 24        | 1.19%   |
| AMD Ryzen 3                    | 22        | 1.09%   |
| AMD E                          | 21        | 1.04%   |
| AMD A4                         | 20        | 0.99%   |
| AMD E1                         | 19        | 0.94%   |
| Intel Celeron Dual-Core        | 17        | 0.84%   |
| AMD A10                        | 17        | 0.84%   |
| Intel Pentium Dual             | 15        | 0.74%   |
| Intel Genuine                  | 15        | 0.74%   |
| Intel Celeron M                | 13        | 0.64%   |
| AMD E2                         | 13        | 0.64%   |
| AMD Athlon II                  | 12        | 0.59%   |
| AMD A8                         | 12        | 0.59%   |
| Intel Core Duo                 | 8         | 0.4%    |
| Intel Pentium M                | 7         | 0.35%   |
| AMD Ryzen 9                    | 6         | 0.3%    |
| AMD Athlon II Dual-Core        | 6         | 0.3%    |
| AMD Turion 64 X2 Mobile        | 5         | 0.25%   |
| AMD Athlon                     | 5         | 0.25%   |
| Intel Xeon                     | 4         | 0.2%    |
| Intel Celeron D                | 4         | 0.2%    |
| AMD Ryzen 7 PRO                | 4         | 0.2%    |
| AMD C-50                       | 4         | 0.2%    |
| AMD Athlon X2                  | 4         | 0.2%    |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.15%   |
| AMD C-60                       | 3         | 0.15%   |
| AMD Athlon 64 X2               | 3         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1141      | 56.32%  |
| 4       | 580       | 28.63%  |
| 6       | 88        | 4.34%   |
| 1       | 79        | 3.9%    |
| 8       | 69        | 3.41%   |
| Unknown | 39        | 1.92%   |
| 12      | 11        | 0.54%   |
| 14      | 8         | 0.39%   |
| 10      | 6         | 0.3%    |
| 24      | 3         | 0.15%   |
| 16      | 2         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2012      | 99.8%   |
| 2       | 3         | 0.15%   |
| Unknown | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1260      | 62.13%  |
| 1       | 729       | 35.95%  |
| Unknown | 39        | 1.92%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1904      | 94.16%  |
| Unknown        | 64        | 3.17%   |
| 32-bit         | 53        | 2.62%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 429       | 20.84%  |
| 0x206a7    | 171       | 8.31%   |
| 0x306a9    | 155       | 7.53%   |
| 0x806ea    | 77        | 3.74%   |
| 0x1067a    | 73        | 3.55%   |
| 0x806ec    | 57        | 2.77%   |
| 0x806e9    | 54        | 2.62%   |
| 0x20655    | 51        | 2.48%   |
| 0x306c3    | 47        | 2.28%   |
| 0x406e3    | 46        | 2.23%   |
| 0x906ea    | 44        | 2.14%   |
| 0x806c1    | 41        | 1.99%   |
| 0x6fd      | 41        | 1.99%   |
| 0x40651    | 41        | 1.99%   |
| 0x706a1    | 34        | 1.65%   |
| 0x306d4    | 33        | 1.6%    |
| 0x106ca    | 32        | 1.55%   |
| 0x406c4    | 28        | 1.36%   |
| 0x06001119 | 28        | 1.36%   |
| 0x30678    | 27        | 1.31%   |
| 0x08108109 | 23        | 1.12%   |
| 0x05000119 | 23        | 1.12%   |
| 0xa0652    | 20        | 0.97%   |
| 0x906e9    | 19        | 0.92%   |
| 0x506c9    | 18        | 0.87%   |
| 0x08600106 | 18        | 0.87%   |
| 0x08108102 | 18        | 0.87%   |
| 0x506e3    | 17        | 0.83%   |
| 0x20652    | 17        | 0.83%   |
| 0x806eb    | 16        | 0.78%   |
| 0x10676    | 16        | 0.78%   |
| 0x6d8      | 15        | 0.73%   |
| 0x406c3    | 15        | 0.73%   |
| 0x08600103 | 15        | 0.73%   |
| 0x010000c8 | 15        | 0.73%   |
| 0x03000027 | 14        | 0.68%   |
| 0x6f6      | 13        | 0.63%   |
| 0x06006705 | 13        | 0.63%   |
| 0x6ec      | 12        | 0.58%   |
| 0x07030105 | 12        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 363       | 17.96%  |
| SandyBridge       | 202       | 10%     |
| IvyBridge         | 173       | 8.56%   |
| Haswell           | 104       | 5.15%   |
| Penryn            | 99        | 4.9%    |
| Core              | 88        | 4.35%   |
| Skylake           | 82        | 4.06%   |
| Westmere          | 76        | 3.76%   |
| Silvermont        | 76        | 3.76%   |
| Unknown           | 67        | 3.32%   |
| Goldmont plus     | 65        | 3.22%   |
| TigerLake         | 60        | 2.97%   |
| Bonnell           | 52        | 2.57%   |
| Zen+              | 49        | 2.42%   |
| Zen 2             | 49        | 2.42%   |
| Bobcat            | 41        | 2.03%   |
| Broadwell         | 40        | 1.98%   |
| Piledriver        | 33        | 1.63%   |
| Zen 3             | 32        | 1.58%   |
| P6                | 32        | 1.58%   |
| Excavator         | 32        | 1.58%   |
| CometLake         | 27        | 1.34%   |
| Alderlake Hybrid  | 27        | 1.34%   |
| K10               | 26        | 1.29%   |
| Goldmont          | 21        | 1.04%   |
| Puma              | 17        | 0.84%   |
| Icelake           | 17        | 0.84%   |
| Zen               | 15        | 0.74%   |
| K10 Llano         | 15        | 0.74%   |
| Jaguar            | 10        | 0.49%   |
| K8 & K10 hybrid   | 9         | 0.45%   |
| Tremont           | 7         | 0.35%   |
| K8 Hammer         | 7         | 0.35%   |
| Nehalem           | 5         | 0.25%   |
| Meteorlake Hybrid | 1         | 0.05%   |
| Lunarlake Hybrid  | 1         | 0.05%   |
| Gracemont         | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1461      | 54.21%  |
| Nvidia                           | 631       | 23.41%  |
| AMD                              | 593       | 22%     |
| Silicon Integrated Systems [SiS] | 5         | 0.19%   |
| VIA Technologies                 | 3         | 0.11%   |
| ATI Technologies                 | 2         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 186       | 6.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 169       | 5.97%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 86        | 3.04%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 65        | 2.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 64        | 2.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 63        | 2.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 62        | 2.19%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 51        | 1.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 51        | 1.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 50        | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 48        | 1.7%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 48        | 1.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 1.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 46        | 1.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 41        | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 1.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 1.27%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 36        | 1.27%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 32        | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 31        | 1.1%    |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 31        | 1.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 30        | 1.06%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 30        | 1.06%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 28        | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 28        | 0.99%   |
| Nvidia GP108M [GeForce MX150]                                                            | 27        | 0.95%   |
| Nvidia GM108M [GeForce MX110]                                                            | 27        | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 26        | 0.92%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 26        | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 25        | 0.88%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 25        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 24        | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 24        | 0.85%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 24        | 0.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 24        | 0.85%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 23        | 0.81%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 23        | 0.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 0.81%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 22        | 0.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 21        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 817       | 40.47%  |
| Intel + Nvidia | 506       | 25.06%  |
| 1 x AMD        | 345       | 17.09%  |
| Intel + AMD    | 132       | 6.54%   |
| 1 x Nvidia     | 85        | 4.21%   |
| 2 x AMD        | 79        | 3.91%   |
| AMD + Nvidia   | 39        | 1.93%   |
| 2 x Intel      | 5         | 0.25%   |
| 1 x SiS        | 5         | 0.25%   |
| Other          | 3         | 0.15%   |
| 1 x VIA        | 3         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1742      | 85.27%  |
| Proprietary | 236       | 11.55%  |
| Unknown     | 65        | 3.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 944       | 45.58%  |
| 1.01-2.0   | 475       | 22.94%  |
| 0.01-0.5   | 357       | 17.24%  |
| 0.51-1.0   | 142       | 6.86%   |
| 3.01-4.0   | 119       | 5.75%   |
| 5.01-6.0   | 17        | 0.82%   |
| 7.01-8.0   | 9         | 0.43%   |
| 2.01-3.0   | 7         | 0.34%   |
| 8.01-16.0  | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 447       | 20.32%  |
| LG Display              | 360       | 16.36%  |
| Samsung Electronics     | 290       | 13.18%  |
| Chimei Innolux          | 277       | 12.59%  |
| BOE                     | 273       | 12.41%  |
| Chi Mei Optoelectronics | 92        | 4.18%   |
| Dell                    | 63        | 2.86%   |
| Goldstar                | 48        | 2.18%   |
| LG Philips              | 34        | 1.55%   |
| Lenovo                  | 34        | 1.55%   |
| Philips                 | 30        | 1.36%   |
| PANDA                   | 30        | 1.36%   |
| Sharp                   | 29        | 1.32%   |
| Apple                   | 19        | 0.86%   |
| HannStar                | 18        | 0.82%   |
| Hewlett-Packard         | 14        | 0.64%   |
| Ancor Communications    | 13        | 0.59%   |
| Acer                    | 13        | 0.59%   |
| AOC                     | 12        | 0.55%   |
| Valve                   | 11        | 0.5%    |
| CPT                     | 10        | 0.45%   |
| BenQ                    | 10        | 0.45%   |
| Sony                    | 5         | 0.23%   |
| InfoVision              | 5         | 0.23%   |
| CSOT                    | 5         | 0.23%   |
| ViewSonic               | 4         | 0.18%   |
| Toshiba                 | 4         | 0.18%   |
| TMX                     | 4         | 0.18%   |
| Quanta Display          | 4         | 0.18%   |
| Panasonic               | 3         | 0.14%   |
| LGD                     | 3         | 0.14%   |
| InnoLux Display         | 3         | 0.14%   |
| HKC                     | 3         | 0.14%   |
| CSO                     | 3         | 0.14%   |
| Xiaomi                  | 2         | 0.09%   |
| MStar                   | 2         | 0.09%   |
| KTC                     | 2         | 0.09%   |
| CVT                     | 2         | 0.09%   |
| Belinea                 | 2         | 0.09%   |
| ASUSTek Computer        | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 34        | 1.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 29        | 1.31%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 26        | 1.17%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 24        | 1.08%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 24        | 1.08%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 23        | 1.04%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 22        | 0.99%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 21        | 0.95%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 21        | 0.95%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 20        | 0.9%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 19        | 0.86%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 18        | 0.81%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.81%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 18        | 0.81%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 18        | 0.81%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 16        | 0.72%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 15        | 0.68%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 15        | 0.68%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 12        | 0.54%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 12        | 0.54%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 11        | 0.5%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.5%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 11        | 0.5%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.5%    |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 10        | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 10        | 0.45%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 10        | 0.45%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 9         | 0.41%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 9         | 0.41%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 9         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 8         | 0.36%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch             | 8         | 0.36%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 8         | 0.36%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 8         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 8         | 0.36%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                    | 8         | 0.36%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 8         | 0.36%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 8         | 0.36%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 8         | 0.36%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 7         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 834       | 39.9%   |
| 1366x768 (WXGA)    | 731       | 34.98%  |
| 1600x900 (HD+)     | 130       | 6.22%   |
| 1280x800 (WXGA)    | 96        | 4.59%   |
| 3840x2160 (4K)     | 50        | 2.39%   |
| 1024x600           | 43        | 2.06%   |
| 2560x1440 (QHD)    | 29        | 1.39%   |
| 1440x900 (WXGA+)   | 28        | 1.34%   |
| 1920x1200 (WUXGA)  | 26        | 1.24%   |
| 1280x1024 (SXGA)   | 24        | 1.15%   |
| 2560x1600          | 19        | 0.91%   |
| 1680x1050 (WSXGA+) | 18        | 0.86%   |
| 800x1280           | 11        | 0.53%   |
| 1024x768 (XGA)     | 8         | 0.38%   |
| 1360x768           | 6         | 0.29%   |
| 2560x1080          | 5         | 0.24%   |
| 3456x2160          | 4         | 0.19%   |
| 3200x2000          | 4         | 0.19%   |
| 3840x2400          | 3         | 0.14%   |
| 3200x1800 (QHD+)   | 3         | 0.14%   |
| 1280x720 (HD)      | 3         | 0.14%   |
| 2880x1620          | 2         | 0.1%    |
| 2160x1440          | 2         | 0.1%    |
| 1600x1200          | 2         | 0.1%    |
| 3840x1100          | 1         | 0.05%   |
| 2966x900           | 1         | 0.05%   |
| 2880x1800          | 1         | 0.05%   |
| 2520x1680          | 1         | 0.05%   |
| 2256x1504          | 1         | 0.05%   |
| 1920x540           | 1         | 0.05%   |
| 1400x1050          | 1         | 0.05%   |
| 1280x768           | 1         | 0.05%   |
| Unknown            | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1198      | 54.41%  |
| 14      | 190       | 8.63%   |
| 13      | 174       | 7.9%    |
| 17      | 164       | 7.45%   |
| 24      | 66        | 3%      |
| 23      | 52        | 2.36%   |
| 21      | 50        | 2.27%   |
| 11      | 40        | 1.82%   |
| 10      | 40        | 1.82%   |
| 27      | 35        | 1.59%   |
| 12      | 35        | 1.59%   |
| 16      | 31        | 1.41%   |
| Unknown | 21        | 0.95%   |
| 18      | 17        | 0.77%   |
| 19      | 15        | 0.68%   |
| 31      | 12        | 0.54%   |
| 7       | 11        | 0.5%    |
| 22      | 9         | 0.41%   |
| 32      | 5         | 0.23%   |
| 25      | 5         | 0.23%   |
| 20      | 5         | 0.23%   |
| 8       | 4         | 0.18%   |
| 72      | 3         | 0.14%   |
| 63      | 3         | 0.14%   |
| 40      | 3         | 0.14%   |
| 84      | 2         | 0.09%   |
| 52      | 2         | 0.09%   |
| 26      | 2         | 0.09%   |
| 65      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 54      | 1         | 0.05%   |
| 46      | 1         | 0.05%   |
| 43      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |
| 35      | 1         | 0.05%   |
| 34      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1485      | 67.65%  |
| 351-400     | 198       | 9.02%   |
| 201-300     | 197       | 8.97%   |
| 501-600     | 153       | 6.97%   |
| 401-500     | 81        | 3.69%   |
| Unknown     | 21        | 0.96%   |
| 601-700     | 19        | 0.87%   |
| 1-100       | 11        | 0.5%    |
| 1001-1500   | 9         | 0.41%   |
| 701-800     | 6         | 0.27%   |
| 1501-2000   | 5         | 0.23%   |
| 801-900     | 4         | 0.18%   |
| 101-200     | 4         | 0.18%   |
| 901-1000    | 2         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1719      | 86.08%  |
| 16/10   | 206       | 10.32%  |
| 5/4     | 25        | 1.25%   |
| Unknown | 13        | 0.65%   |
| 4/3     | 12        | 0.6%    |
| 3/2     | 7         | 0.35%   |
| 0.67    | 7         | 0.35%   |
| 0.62    | 4         | 0.2%    |
| 21/9    | 2         | 0.1%    |
| 32/9    | 1         | 0.05%   |
| 3.40    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1199      | 54.4%   |
| 81-90          | 293       | 13.29%  |
| 201-250        | 153       | 6.94%   |
| 121-130        | 131       | 5.94%   |
| 71-80          | 66        | 2.99%   |
| 51-60          | 41        | 1.86%   |
| 41-50          | 40        | 1.81%   |
| 301-350        | 35        | 1.59%   |
| 61-70          | 34        | 1.54%   |
| 151-200        | 30        | 1.36%   |
| 141-150        | 28        | 1.27%   |
| 111-120        | 25        | 1.13%   |
| 131-140        | 24        | 1.09%   |
| 251-300        | 21        | 0.95%   |
| Unknown        | 21        | 0.95%   |
| 351-500        | 19        | 0.86%   |
| 1-40           | 15        | 0.68%   |
| More than 1000 | 13        | 0.59%   |
| 91-100         | 10        | 0.45%   |
| 501-1000       | 6         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 834       | 38.45%  |
| 101-120       | 806       | 37.16%  |
| 51-100        | 383       | 17.66%  |
| 161-240       | 86        | 3.96%   |
| More than 240 | 28        | 1.29%   |
| Unknown       | 21        | 0.97%   |
| 1-50          | 11        | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1739      | 84.87%  |
| 2     | 266       | 12.98%  |
| 0     | 32        | 1.56%   |
| 3     | 12        | 0.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1153      | 34.92%  |
| Intel                                  | 779       | 23.59%  |
| Qualcomm Atheros                       | 683       | 20.68%  |
| Broadcom                               | 276       | 8.36%   |
| Broadcom Limited                       | 69        | 2.09%   |
| Marvell Technology Group               | 57        | 1.73%   |
| Ralink                                 | 55        | 1.67%   |
| MediaTek                               | 40        | 1.21%   |
| Ralink Technology                      | 22        | 0.67%   |
| Xiaomi                                 | 14        | 0.42%   |
| Huawei Technologies                    | 12        | 0.36%   |
| Dell                                   | 12        | 0.36%   |
| Attansic Technology                    | 12        | 0.36%   |
| Samsung Electronics                    | 11        | 0.33%   |
| JMicron Technology                     | 8         | 0.24%   |
| ASIX Electronics                       | 8         | 0.24%   |
| Sierra Wireless                        | 7         | 0.21%   |
| Qualcomm Atheros Communications        | 7         | 0.21%   |
| Ericsson Business Mobile Networks      | 7         | 0.21%   |
| TP-Link                                | 6         | 0.18%   |
| Shenzhen Goodix Technology             | 5         | 0.15%   |
| Qualcomm                               | 5         | 0.15%   |
| ICS Advent                             | 5         | 0.15%   |
| Hewlett-Packard                        | 5         | 0.15%   |
| VIA Technologies                       | 4         | 0.12%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.12%   |
| Lenovo                                 | 3         | 0.09%   |
| Fibocom                                | 3         | 0.09%   |
| DisplayLink                            | 3         | 0.09%   |
| ASUSTek Computer                       | 3         | 0.09%   |
| Spreadtrum Communications              | 2         | 0.06%   |
| Nokia Mobile Phones                    | 2         | 0.06%   |
| Motorola PCS                           | 2         | 0.06%   |
| D-Link System                          | 2         | 0.06%   |
| D-Link                                 | 2         | 0.06%   |
| ZyDAS                                  | 1         | 0.03%   |
| U-Blox                                 | 1         | 0.03%   |
| Toshiba                                | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QinHeng Electronics                    | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 709       | 18.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 286       | 7.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 154       | 4.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 108       | 2.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 102       | 2.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 91        | 2.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 88        | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 85        | 2.21%   |
| Intel Wireless 8265 / 8275                                              | 63        | 1.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 52        | 1.35%   |
| Intel Wireless 7260                                                     | 48        | 1.25%   |
| Intel Wi-Fi 6 AX201                                                     | 48        | 1.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 44        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 43        | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 43        | 1.12%   |
| Intel Wi-Fi 6 AX200                                                     | 41        | 1.07%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 39        | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 39        | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                           | 38        | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 36        | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 35        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 34        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 34        | 0.88%   |
| Intel Wireless 3165                                                     | 32        | 0.83%   |
| Intel Wireless 8260                                                     | 31        | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 30        | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 30        | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 29        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 28        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 27        | 0.7%    |
| Intel Wireless 7265                                                     | 26        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 25        | 0.65%   |
| Intel Centrino Wireless-N 2230                                          | 24        | 0.62%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 23        | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 23        | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 22        | 0.57%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 22        | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 21        | 0.55%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 21        | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 21        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 740       | 36.22%  |
| Qualcomm Atheros                | 589       | 28.83%  |
| Realtek Semiconductor           | 304       | 14.88%  |
| Broadcom                        | 208       | 10.18%  |
| Ralink                          | 55        | 2.69%   |
| Broadcom Limited                | 43        | 2.1%    |
| MediaTek                        | 38        | 1.86%   |
| Ralink Technology               | 22        | 1.08%   |
| Dell                            | 8         | 0.39%   |
| Sierra Wireless                 | 7         | 0.34%   |
| Qualcomm Atheros Communications | 7         | 0.34%   |
| Qualcomm                        | 5         | 0.24%   |
| TP-Link                         | 4         | 0.2%    |
| Fibocom                         | 3         | 0.15%   |
| D-Link System                   | 2         | 0.1%    |
| D-Link                          | 2         | 0.1%    |
| ZyDAS                           | 1         | 0.05%   |
| Microsoft                       | 1         | 0.05%   |
| Hewlett-Packard                 | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| ASUSTek Computer                | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 154       | 7.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 108       | 5.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 102       | 4.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 91        | 4.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 88        | 4.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 85        | 4.15%   |
| Intel Wireless 8265 / 8275                                              | 63        | 3.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 52        | 2.54%   |
| Intel Wireless 7260                                                     | 48        | 2.34%   |
| Intel Wi-Fi 6 AX201                                                     | 48        | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 43        | 2.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 43        | 2.1%    |
| Intel Wi-Fi 6 AX200                                                     | 41        | 2%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 39        | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 39        | 1.91%   |
| Broadcom BCM43142 802.11b/g/n                                           | 38        | 1.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 36        | 1.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 35        | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 34        | 1.66%   |
| Intel Wireless 3165                                                     | 32        | 1.56%   |
| Intel Wireless 8260                                                     | 31        | 1.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 30        | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 29        | 1.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 28        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 27        | 1.32%   |
| Intel Wireless 7265                                                     | 26        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 25        | 1.22%   |
| Intel Centrino Wireless-N 2230                                          | 24        | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 23        | 1.12%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 22        | 1.07%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 21        | 1.03%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 21        | 1.03%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 20        | 0.98%   |
| Intel Centrino Ultimate-N 6300                                          | 19        | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 18        | 0.88%   |
| Intel WiFi Link 5100                                                    | 16        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 16        | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 15        | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 13        | 0.64%   |
| Ralink MT7601U Wireless Adapter                                         | 12        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1049      | 60.01%  |
| Intel                                  | 230       | 13.16%  |
| Qualcomm Atheros                       | 187       | 10.7%   |
| Broadcom                               | 95        | 5.43%   |
| Marvell Technology Group               | 57        | 3.26%   |
| Broadcom Limited                       | 28        | 1.6%    |
| Xiaomi                                 | 14        | 0.8%    |
| Attansic Technology                    | 12        | 0.69%   |
| Samsung Electronics                    | 11        | 0.63%   |
| Huawei Technologies                    | 10        | 0.57%   |
| JMicron Technology                     | 8         | 0.46%   |
| ASIX Electronics                       | 8         | 0.46%   |
| ICS Advent                             | 5         | 0.29%   |
| VIA Technologies                       | 4         | 0.23%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.23%   |
| Lenovo                                 | 3         | 0.17%   |
| Hewlett-Packard                        | 3         | 0.17%   |
| DisplayLink                            | 3         | 0.17%   |
| TP-Link                                | 2         | 0.11%   |
| Spreadtrum Communications              | 2         | 0.11%   |
| Motorola PCS                           | 2         | 0.11%   |
| MediaTek                               | 2         | 0.11%   |
| ASUSTek Computer                       | 2         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| QinHeng Electronics                    | 1         | 0.06%   |
| OPPO Electronics                       | 1         | 0.06%   |
| OKB SAPR                               | 1         | 0.06%   |
| Nvidia                                 | 1         | 0.06%   |
| LSI                                    | 1         | 0.06%   |
| Android                                | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 709       | 40.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 286       | 16.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 44        | 2.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 34        | 1.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 1.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 23        | 1.31%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 22        | 1.25%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 21        | 1.19%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 20        | 1.14%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 20        | 1.14%   |
| Intel Ethernet Connection (6) I219-V                                   | 17        | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 16        | 0.91%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 15        | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 14        | 0.8%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 14        | 0.8%    |
| Intel Ethernet Connection (4) I219-V                                   | 13        | 0.74%   |
| Intel Ethernet Connection I218-LM                                      | 12        | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                                  | 12        | 0.68%   |
| Intel 82577LM Gigabit Network Connection                               | 12        | 0.68%   |
| Attansic AR8152 v2.0 Fast Ethernet                                     | 12        | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 11        | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 11        | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 11        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 0.63%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 0.57%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 0.57%   |
| Intel 82567LM Gigabit Network Connection                               | 10        | 0.57%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 10        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 9         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 9         | 0.51%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 9         | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                                  | 9         | 0.51%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 9         | 0.51%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 8         | 0.45%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 0.45%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 8         | 0.45%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 8         | 0.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 8         | 0.45%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 8         | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1977      | 53.36%  |
| Ethernet | 1692      | 45.67%  |
| Modem    | 35        | 0.94%   |
| Unknown  | 1         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1672      | 78.57%  |
| Ethernet | 456       | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1612      | 79.96%  |
| 1     | 379       | 18.8%   |
| 0     | 21        | 1.04%   |
| 3     | 4         | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1992      | 98.81%  |
| Yes  | 24        | 1.19%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 554       | 35.86%  |
| Qualcomm Atheros Communications | 189       | 12.23%  |
| Realtek Semiconductor           | 183       | 11.84%  |
| IMC Networks                    | 157       | 10.16%  |
| Lite-On Technology              | 105       | 6.8%    |
| Broadcom                        | 96        | 6.21%   |
| Foxconn / Hon Hai               | 69        | 4.47%   |
| Ralink                          | 36        | 2.33%   |
| Hewlett-Packard                 | 29        | 1.88%   |
| Dell                            | 21        | 1.36%   |
| ASUSTek Computer                | 20        | 1.29%   |
| Apple                           | 17        | 1.1%    |
| Cambridge Silicon Radio         | 14        | 0.91%   |
| Toshiba                         | 11        | 0.71%   |
| Ralink Technology               | 10        | 0.65%   |
| Foxconn International           | 9         | 0.58%   |
| Realtek                         | 5         | 0.32%   |
| Opticis                         | 4         | 0.26%   |
| Alps Electric                   | 4         | 0.26%   |
| Micro Star International        | 3         | 0.19%   |
| MediaTek                        | 3         | 0.19%   |
| Taiyo Yuden                     | 2         | 0.13%   |
| Askey Computer                  | 2         | 0.13%   |
| Fujitsu                         | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 201       | 13.01%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 109       | 7.06%   |
| Intel AX201 Bluetooth                               | 102       | 6.6%    |
| Realtek Bluetooth Radio                             | 97        | 6.28%   |
| Qualcomm Atheros  Bluetooth Device                  | 74        | 4.79%   |
| IMC Networks Bluetooth Radio                        | 65        | 4.21%   |
| Realtek  Bluetooth 4.2 Adapter                      | 58        | 3.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 48        | 3.11%   |
| IMC Networks Bluetooth Device                       | 43        | 2.78%   |
| Intel AX200 Bluetooth                               | 40        | 2.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 38        | 2.46%   |
| Ralink RT3290 Bluetooth                             | 36        | 2.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 34        | 2.2%    |
| Lite-On Bluetooth Device                            | 34        | 2.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 28        | 1.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 25        | 1.62%   |
| Intel Wireless-AC 3168 Bluetooth                    | 24        | 1.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 22        | 1.42%   |
| IMC Networks Wireless_Device                        | 17        | 1.1%    |
| Intel Bluetooth Device                              | 16        | 1.04%   |
| HP Broadcom 2070 Bluetooth Combo                    | 16        | 1.04%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14        | 0.91%   |
| Qualcomm Atheros Bluetooth                          | 13        | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 13        | 0.84%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 12        | 0.78%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 12        | 0.78%   |
| Lite-On Wireless_Device                             | 11        | 0.71%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 11        | 0.71%   |
| Realtek RTL8821A Bluetooth                          | 10        | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 10        | 0.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 10        | 0.65%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.65%   |
| Broadcom BCM2045 Bluetooth                          | 10        | 0.65%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 9         | 0.58%   |
| Foxconn International BCM43142A0 Bluetooth module   | 9         | 0.58%   |
| Broadcom BCM20702A0                                 | 9         | 0.58%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 9         | 0.58%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 8         | 0.52%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 8         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1578      | 67.09%  |
| AMD                              | 459       | 19.52%  |
| Nvidia                           | 232       | 9.86%   |
| C-Media Electronics              | 9         | 0.38%   |
| Logitech                         | 8         | 0.34%   |
| Silicon Integrated Systems [SiS] | 7         | 0.3%    |
| Realtek Semiconductor            | 6         | 0.26%   |
| Plantronics                      | 6         | 0.26%   |
| Lenovo                           | 5         | 0.21%   |
| VIA Technologies                 | 3         | 0.13%   |
| JMTek                            | 3         | 0.13%   |
| Hewlett-Packard                  | 3         | 0.13%   |
| GN Netcom                        | 3         | 0.13%   |
| DSEA A/S                         | 3         | 0.13%   |
| Texas Instruments                | 2         | 0.09%   |
| SteelSeries ApS                  | 2         | 0.09%   |
| Shenzhen Rapoo Technology        | 2         | 0.09%   |
| M-Audio                          | 2         | 0.09%   |
| Kingston Technology              | 2         | 0.09%   |
| Generalplus Technology           | 2         | 0.09%   |
| Trust                            | 1         | 0.04%   |
| Sony                             | 1         | 0.04%   |
| Silicon Motion                   | 1         | 0.04%   |
| Samsung Electronics              | 1         | 0.04%   |
| Razer USA                        | 1         | 0.04%   |
| MV-SILICON                       | 1         | 0.04%   |
| Microsoft                        | 1         | 0.04%   |
| iCreate Technologies             | 1         | 0.04%   |
| HECATE G4 TE GAMING HEADSET      | 1         | 0.04%   |
| Google                           | 1         | 0.04%   |
| Focusrite-Novation               | 1         | 0.04%   |
| ESS Technology                   | 1         | 0.04%   |
| Cirrus Logic                     | 1         | 0.04%   |
| Audio-Technica                   | 1         | 0.04%   |
| ASUSTek Computer                 | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 233       | 8.28%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 230       | 8.18%   |
| AMD Ryzen HD Audio Controller                                                                     | 173       | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 141       | 5.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 90        | 3.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 90        | 3.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 89        | 3.16%   |
| AMD FCH Azalia Controller                                                                         | 88        | 3.13%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 84        | 2.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 81        | 2.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 70        | 2.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 65        | 2.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 63        | 2.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 61        | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 59        | 2.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 55        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 51        | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 49        | 1.74%   |
| Intel 8 Series HD Audio Controller                                                                | 49        | 1.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 41        | 1.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 41        | 1.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 40        | 1.42%   |
| Intel Broadwell-U Audio Controller                                                                | 40        | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 39        | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 38        | 1.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 35        | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 34        | 1.21%   |
| AMD Wrestler HDMI Audio                                                                           | 33        | 1.17%   |
| AMD Trinity HDMI Audio Controller                                                                 | 33        | 1.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 31        | 1.1%    |
| Intel CM238 HD Audio Controller                                                                   | 24        | 0.85%   |
| AMD High Definition Audio Controller                                                              | 24        | 0.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 23        | 0.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 22        | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 21        | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21        | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 20        | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 0.71%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 20        | 0.71%   |
| AMD Radeon High Definition Audio Controller                                                       | 20        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 445       | 26.61%  |
| SK hynix                     | 343       | 20.51%  |
| Micron Technology            | 181       | 10.83%  |
| Unknown                      | 172       | 10.29%  |
| Kingston                     | 156       | 9.33%   |
| Ramaxel Technology           | 64        | 3.83%   |
| Elpida                       | 56        | 3.35%   |
| A-DATA Technology            | 35        | 2.09%   |
| Nanya Technology             | 31        | 1.85%   |
| GOODRAM                      | 24        | 1.44%   |
| Crucial                      | 22        | 1.32%   |
| Team                         | 17        | 1.02%   |
| Unknown (ABCD)               | 13        | 0.78%   |
| Transcend                    | 12        | 0.72%   |
| AMD                          | 11        | 0.66%   |
| ASint Technology             | 9         | 0.54%   |
| SHARETRONIC                  | 8         | 0.48%   |
| 48spaces                     | 8         | 0.48%   |
| Apacer                       | 7         | 0.42%   |
| Patriot                      | 6         | 0.36%   |
| Unknown                      | 5         | 0.3%    |
| Exceleram                    | 4         | 0.24%   |
| Toshiba                      | 3         | 0.18%   |
| Silicon Power                | 3         | 0.18%   |
| Qimonda                      | 3         | 0.18%   |
| G.Skill                      | 3         | 0.18%   |
| Unifosa                      | 2         | 0.12%   |
| Kllisre                      | 2         | 0.12%   |
| Goldkey                      | 2         | 0.12%   |
| DeTech                       | 2         | 0.12%   |
| Corsair                      | 2         | 0.12%   |
| Wodposit                     | 1         | 0.06%   |
| Unknown (C289)               | 1         | 0.06%   |
| Unknown (768A)               | 1         | 0.06%   |
| Unknown (0x0B49)             | 1         | 0.06%   |
| Unknown (0B79)               | 1         | 0.06%   |
| Teikon                       | 1         | 0.06%   |
| Qumo                         | 1         | 0.06%   |
| Patriot Memory (PDP Systems) | 1         | 0.06%   |
| Kreton                       | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 1.21%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 1.05%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 19        | 1.05%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 1.05%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 18        | 0.99%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.94%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 16        | 0.88%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.88%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 14        | 0.77%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 14        | 0.77%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 14        | 0.77%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 14        | 0.77%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 13        | 0.72%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 13        | 0.72%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 13        | 0.72%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 12        | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.66%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.61%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 11        | 0.61%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 0.61%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 11        | 0.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 11        | 0.61%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 11        | 0.61%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 10        | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 10        | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.55%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 10        | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.55%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s          | 10        | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 9         | 0.5%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 9         | 0.5%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 9         | 0.5%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 9         | 0.5%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 9         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 8         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 615       | 43.37%  |
| DDR4    | 483       | 34.06%  |
| DDR2    | 112       | 7.9%    |
| SDRAM   | 70        | 4.94%   |
| LPDDR4  | 54        | 3.81%   |
| LPDDR3  | 16        | 1.13%   |
| DDR5    | 16        | 1.13%   |
| DDR     | 16        | 1.13%   |
| DRAM    | 14        | 0.99%   |
| Unknown | 13        | 0.92%   |
| LPDDR5  | 9         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1296      | 94.39%  |
| Row Of Chips | 60        | 4.37%   |
| DIMM         | 9         | 0.66%   |
| Chip         | 7         | 0.51%   |
| Unknown      | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 533       | 32.94%  |
| 8192  | 428       | 26.45%  |
| 2048  | 335       | 20.7%   |
| 16384 | 157       | 9.7%    |
| 1024  | 111       | 6.86%   |
| 32768 | 33        | 2.04%   |
| 512   | 18        | 1.11%   |
| 256   | 3         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 412       | 26.36%  |
| 2667    | 221       | 14.14%  |
| 3200    | 178       | 11.39%  |
| 1334    | 122       | 7.81%   |
| 2400    | 106       | 6.78%   |
| 1333    | 94        | 6.01%   |
| Unknown | 69        | 4.41%   |
| 667     | 65        | 4.16%   |
| 2133    | 53        | 3.39%   |
| 4199    | 37        | 2.37%   |
| 1067    | 31        | 1.98%   |
| 800     | 21        | 1.34%   |
| 3266    | 16        | 1.02%   |
| 1066    | 13        | 0.83%   |
| 533     | 13        | 0.83%   |
| 4267    | 12        | 0.77%   |
| 2048    | 12        | 0.77%   |
| 1867    | 12        | 0.77%   |
| 8400    | 10        | 0.64%   |
| 5600    | 10        | 0.64%   |
| 4266    | 10        | 0.64%   |
| 4800    | 7         | 0.45%   |
| 975     | 7         | 0.45%   |
| 400     | 7         | 0.45%   |
| 333     | 7         | 0.45%   |
| 6400    | 6         | 0.38%   |
| 2933    | 3         | 0.19%   |
| 8533    | 1         | 0.06%   |
| 7500    | 1         | 0.06%   |
| 5500    | 1         | 0.06%   |
| 1866    | 1         | 0.06%   |
| 1776    | 1         | 0.06%   |
| 1639    | 1         | 0.06%   |
| 1596    | 1         | 0.06%   |
| 1200    | 1         | 0.06%   |
| 266     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 13        | 50%     |
| Samsung Electronics | 4         | 15.38%  |
| Hewlett-Packard     | 4         | 15.38%  |
| Xiaomi              | 1         | 3.85%   |
| Xerox               | 1         | 3.85%   |
| Seiko Epson         | 1         | 3.85%   |
| Pantum              | 1         | 3.85%   |
| Dell                | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP LaserJet P1102               | 2         | 7.69%   |
| Xiaomi MiMouse 2                | 1         | 3.85%   |
| Xerox WorkCenter M15            | 1         | 3.85%   |
| Seiko Epson L3050 Series        | 1         | 3.85%   |
| Samsung SCX-4100 Scanner        | 1         | 3.85%   |
| Samsung M2070 Series            | 1         | 3.85%   |
| Samsung Laser Printer           | 1         | 3.85%   |
| Samsung CLX-3300 Series         | 1         | 3.85%   |
| Pantum P2510 series             | 1         | 3.85%   |
| HP Ink Tank Wireless 410 series | 1         | 3.85%   |
| HP Deskjet 3540 series          | 1         | 3.85%   |
| Dell AIO 810                    | 1         | 3.85%   |
| Canon PIXMA MP495               | 1         | 3.85%   |
| Canon PIXMA MP280               | 1         | 3.85%   |
| Canon MG2200 series             | 1         | 3.85%   |
| Canon MF4410                    | 1         | 3.85%   |
| Canon MF4010 series             | 1         | 3.85%   |
| Canon MF3010                    | 1         | 3.85%   |
| Canon LBP6030/6030B/6018L       | 1         | 3.85%   |
| Canon LBP6000                   | 1         | 3.85%   |
| Canon LBP3010/LBP3018/LBP3050   | 1         | 3.85%   |
| Canon LBP2900                   | 1         | 3.85%   |
| Canon G4010 series              | 1         | 3.85%   |
| Canon G2010 series              | 1         | 3.85%   |
| Canon CAPT USB Device           | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 3         | 60%     |
| Seiko Epson    | 1         | 20%     |
| Canon          | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson GT-9800F [Perfection 3200] | 1         | 20%     |
| Mustek Systems SNAPSCAN e22            | 1         | 20%     |
| Mustek Systems BearPaw 2448 CU Pro     | 1         | 20%     |
| Mustek Systems BearPaw 1200 CU Plus    | 1         | 20%     |
| Canon CanoScan LiDE 120                | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 459       | 25.4%   |
| IMC Networks                           | 256       | 14.17%  |
| Bison Electronics                      | 142       | 7.86%   |
| Realtek Semiconductor                  | 119       | 6.59%   |
| Quanta                                 | 112       | 6.2%    |
| Microdia                               | 112       | 6.2%    |
| Sunplus Innovation Technology          | 99        | 5.48%   |
| Suyin                                  | 85        | 4.7%    |
| Cheng Uei Precision Industry (Foxlink) | 85        | 4.7%    |
| Syntek                                 | 56        | 3.1%    |
| Silicon Motion                         | 41        | 2.27%   |
| Alcor Micro                            | 36        | 1.99%   |
| Lite-On Technology                     | 34        | 1.88%   |
| Luxvisions Innotech Limited            | 23        | 1.27%   |
| Apple                                  | 23        | 1.27%   |
| Z-Star Microelectronics                | 16        | 0.89%   |
| Logitech                               | 14        | 0.77%   |
| Sonix Technology                       | 11        | 0.61%   |
| DigiTech                               | 11        | 0.61%   |
| Acer                                   | 9         | 0.5%    |
| Ricoh                                  | 8         | 0.44%   |
| Primax Electronics                     | 7         | 0.39%   |
| ALi                                    | 7         | 0.39%   |
| Lenovo                                 | 4         | 0.22%   |
| Sunplus Technology                     | 3         | 0.17%   |
| SunplusIT                              | 2         | 0.11%   |
| ShineTech                              | 2         | 0.11%   |
| Shine-optics                           | 2         | 0.11%   |
| Samsung Electronics                    | 2         | 0.11%   |
| Importek                               | 2         | 0.11%   |
| icSpring                               | 2         | 0.11%   |
| HYGD-221208-J                          | 2         | 0.11%   |
| Genesys Logic                          | 2         | 0.11%   |
| GEMBIRD                                | 2         | 0.11%   |
| BillionPixels                          | 2         | 0.11%   |
| Alpha Imaging Technology               | 2         | 0.11%   |
| Xiaomi                                 | 1         | 0.06%   |
| USB Camera CS                          | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Razer USA                              | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                         | 72        | 3.97%   |
| Chicony Integrated Camera                                                  | 59        | 3.25%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 39        | 2.15%   |
| Chicony Lenovo EasyCamera                                                  | 38        | 2.09%   |
| Bison Lenovo Integrated Webcam                                             | 38        | 2.09%   |
| Chicony HD Webcam                                                          | 37        | 2.04%   |
| IMC Networks Integrated Camera                                             | 30        | 1.65%   |
| Sunplus Integrated_Webcam_HD                                               | 28        | 1.54%   |
| Quanta HD User Facing                                                      | 27        | 1.49%   |
| Microdia Integrated_Webcam_HD                                              | 27        | 1.49%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 27        | 1.49%   |
| Syntek Lenovo EasyCamera                                                   | 25        | 1.38%   |
| Bison Lenovo EasyCamera                                                    | 25        | 1.38%   |
| Realtek Integrated_Webcam_HD                                               | 23        | 1.27%   |
| Chicony HP HD Camera                                                       | 23        | 1.27%   |
| Quanta HP TrueVision HD Camera                                             | 20        | 1.1%    |
| Quanta HD Webcam                                                           | 19        | 1.05%   |
| Bison Integrated Camera                                                    | 19        | 1.05%   |
| Chicony HP Webcam                                                          | 18        | 0.99%   |
| Sunplus HD WebCam                                                          | 16        | 0.88%   |
| IMC Networks Lenovo EasyCamera                                             | 16        | 0.88%   |
| Syntek Integrated Camera                                                   | 15        | 0.83%   |
| Chicony HP Wide Vision HD Camera                                           | 15        | 0.83%   |
| Bison EasyCamera                                                           | 15        | 0.83%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 14        | 0.77%   |
| Sunplus Asus Webcam                                                        | 14        | 0.77%   |
| Quanta VGA WebCam                                                          | 14        | 0.77%   |
| IMC Networks UVC VGA Webcam                                                | 14        | 0.77%   |
| Chicony HP Truevision HD                                                   | 14        | 0.77%   |
| Chicony HD User Facing                                                     | 14        | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 14        | 0.77%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 13        | 0.72%   |
| Lite-On Integrated Camera                                                  | 13        | 0.72%   |
| Lite-On HP HD Camera                                                       | 13        | 0.72%   |
| IMC Networks Integrated Webcam                                             | 13        | 0.72%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 13        | 0.72%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 12        | 0.66%   |
| Realtek Integrated Webcam                                                  | 12        | 0.66%   |
| Quanta HP HD Camera                                                        | 12        | 0.66%   |
| Chicony VGA WebCam                                                         | 12        | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 104       | 34.1%   |
| Synaptics                          | 64        | 20.98%  |
| Upek                               | 30        | 9.84%   |
| LighTuning Technology              | 27        | 8.85%   |
| Shenzhen Goodix Technology         | 26        | 8.52%   |
| Elan Microelectronics              | 25        | 8.2%    |
| AuthenTec                          | 15        | 4.92%   |
| STMicroelectronics                 | 7         | 2.3%    |
| HOLTEK                             | 4         | 1.31%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.66%   |
| Samsung Electronics                | 1         | 0.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 37        | 12.13%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 9.84%   |
| Elan ELAN:Fingerprint                                                      | 22        | 7.21%   |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 5.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 16        | 5.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 4.59%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 4.26%   |
| Synaptics Fingerprint reader [HP G6]                                       | 12        | 3.93%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 3.28%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 3.28%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 2.62%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 2.62%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 2.62%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 2.3%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.3%    |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.97%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.97%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 1.97%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 1.97%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.64%   |
| AuthenTec AES1600                                                          | 5         | 1.64%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 1.31%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 1.31%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.31%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.31%   |
| HOLTEK FocalTech Fingerprint Device                                        | 4         | 1.31%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.98%   |
| LighTuning Fingerprint Reader                                              | 3         | 0.98%   |
| Elan ELAN:ARM-M4                                                           | 3         | 0.98%   |
| AuthenTec AES2810                                                          | 3         | 0.98%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.66%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.33%   |
| Validity Sensors VFS491                                                    | 1         | 0.33%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.33%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.33%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.33%   |
| Synaptics WBDI                                                             | 1         | 0.33%   |
| Synaptics  WBDI                                                            | 1         | 0.33%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 41        | 50%     |
| Alcor Micro               | 26        | 31.71%  |
| O2 Micro                  | 8         | 9.76%   |
| Upek                      | 3         | 3.66%   |
| Lenovo                    | 2         | 2.44%   |
| Gemalto (was Gemplus)     | 1         | 1.22%   |
| Aladdin Knowledge Systems | 1         | 1.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 31.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 19.28%  |
| Broadcom 5880                                                                | 15        | 18.07%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 8.43%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 6.02%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 3.61%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 3.61%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 3         | 3.61%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.41%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.2%    |
| Broadcom 58200                                                               | 1         | 1.2%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.2%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1304      | 63.18%  |
| 1     | 617       | 29.89%  |
| 2     | 127       | 6.15%   |
| 3     | 10        | 0.48%   |
| 4     | 4         | 0.19%   |
| 6     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 303       | 33.97%  |
| Graphics card            | 272       | 30.49%  |
| Net/wireless             | 76        | 8.52%   |
| Chipcard                 | 66        | 7.4%    |
| Bluetooth                | 46        | 5.16%   |
| Multimedia controller    | 43        | 4.82%   |
| Communication controller | 22        | 2.47%   |
| Storage                  | 14        | 1.57%   |
| Camera                   | 14        | 1.57%   |
| Card reader              | 13        | 1.46%   |
| Flash memory             | 7         | 0.78%   |
| Net/ethernet             | 5         | 0.56%   |
| Sound                    | 3         | 0.34%   |
| Network                  | 3         | 0.34%   |
| Modem                    | 3         | 0.34%   |
| Storage/ata              | 1         | 0.11%   |
| Firewire controller      | 1         | 0.11%   |

